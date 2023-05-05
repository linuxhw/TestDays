Linux in Netherlands - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 5588

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B450M Pro4                  | Desktop     | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| VIOS          | LTH17                       | Notebook    | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [9a1134210f](https://linux-hardware.org/?probe=9a1134210f) | Apr 30, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [3316360d7a](https://linux-hardware.org/?probe=3316360d7a) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | Notebook    | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Insyde        | M890BAP                     | Notebook    | [151efb0278](https://linux-hardware.org/?probe=151efb0278) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Latitude 3301               | Notebook    | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e3f05fe37f](https://linux-hardware.org/?probe=e3f05fe37f) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [bd3dba564e](https://linux-hardware.org/?probe=bd3dba564e) | Apr 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [da542ba626](https://linux-hardware.org/?probe=da542ba626) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [cab1aa59e0](https://linux-hardware.org/?probe=cab1aa59e0) | Apr 28, 2023 |
| ASRock        | Z790 Steel Legend WiFi      | Desktop     | [36175223a5](https://linux-hardware.org/?probe=36175223a5) | Apr 28, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [fa82c3b6ba](https://linux-hardware.org/?probe=fa82c3b6ba) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [c416a3f44a](https://linux-hardware.org/?probe=c416a3f44a) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | Desktop     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [589810ee4b](https://linux-hardware.org/?probe=589810ee4b) | Apr 28, 2023 |
| Dell          | Latitude 3301               | Notebook    | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [858404838d](https://linux-hardware.org/?probe=858404838d) | Apr 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0bf066e179](https://linux-hardware.org/?probe=0bf066e179) | Apr 27, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [6b17eb81f8](https://linux-hardware.org/?probe=6b17eb81f8) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| AZW           | SER                         | Mini pc     | [74f148fb60](https://linux-hardware.org/?probe=74f148fb60) | Apr 26, 2023 |
| Acer          | Aspire X3995                | Desktop     | [877c9deb7a](https://linux-hardware.org/?probe=877c9deb7a) | Apr 25, 2023 |
| Acer          | Predator G3-605             | Desktop     | [37cd92a7f0](https://linux-hardware.org/?probe=37cd92a7f0) | Apr 25, 2023 |
| Acer          | Predator G3-605             | Desktop     | [0b966e7b88](https://linux-hardware.org/?probe=0b966e7b88) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5236dde38f](https://linux-hardware.org/?probe=5236dde38f) | Apr 25, 2023 |
| Gigabyte      | Z270X-UD3-CF                | Desktop     | [06fbe4d0b6](https://linux-hardware.org/?probe=06fbe4d0b6) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [40df32580a](https://linux-hardware.org/?probe=40df32580a) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [1d6082efe8](https://linux-hardware.org/?probe=1d6082efe8) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [d86639089a](https://linux-hardware.org/?probe=d86639089a) | Apr 25, 2023 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [2337ae230f](https://linux-hardware.org/?probe=2337ae230f) | Apr 24, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [09eb88ba6c](https://linux-hardware.org/?probe=09eb88ba6c) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [6cacf7a9f9](https://linux-hardware.org/?probe=6cacf7a9f9) | Apr 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [90db0063b0](https://linux-hardware.org/?probe=90db0063b0) | Apr 24, 2023 |
| BTO           | 17X1183                     | Notebook    | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | Notebook    | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| Dell          | Latitude 9520               | Notebook    | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b906572f4b](https://linux-hardware.org/?probe=b906572f4b) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [65ba6571a2](https://linux-hardware.org/?probe=65ba6571a2) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [72088721ec](https://linux-hardware.org/?probe=72088721ec) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Dell          | Latitude E4300              | Notebook    | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Medion        | E4251                       | Notebook    | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [2e828158e5](https://linux-hardware.org/?probe=2e828158e5) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [a26039eb50](https://linux-hardware.org/?probe=a26039eb50) | Apr 22, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [7e7a982c3c](https://linux-hardware.org/?probe=7e7a982c3c) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Acer          | TP-SW3-013-181M             | Notebook    | [d231dc8846](https://linux-hardware.org/?probe=d231dc8846) | Apr 22, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| ASUSTek       | ZenBook UX333FN_RX333FN     | Notebook    | [8027ff2b04](https://linux-hardware.org/?probe=8027ff2b04) | Apr 21, 2023 |
| EVERCOM NE... | Unknown                     | Desktop     | [d36803f05d](https://linux-hardware.org/?probe=d36803f05d) | Apr 21, 2023 |
| HP            | 1494                        | Desktop     | [625373a1de](https://linux-hardware.org/?probe=625373a1de) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [e8332849a1](https://linux-hardware.org/?probe=e8332849a1) | Apr 20, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [bca816c594](https://linux-hardware.org/?probe=bca816c594) | Apr 20, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [4e45f9c51f](https://linux-hardware.org/?probe=4e45f9c51f) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| ASUSTek       | K501LX                      | Notebook    | [00676747c4](https://linux-hardware.org/?probe=00676747c4) | Apr 19, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [6a0eced5fc](https://linux-hardware.org/?probe=6a0eced5fc) | Apr 19, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [f691871296](https://linux-hardware.org/?probe=f691871296) | Apr 19, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5fc25cc033](https://linux-hardware.org/?probe=5fc25cc033) | Apr 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [abcb6ed7e8](https://linux-hardware.org/?probe=abcb6ed7e8) | Apr 19, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [213cd129cd](https://linux-hardware.org/?probe=213cd129cd) | Apr 18, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | Desktop     | [ae7ea68877](https://linux-hardware.org/?probe=ae7ea68877) | Apr 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Acer          | Iconia                      | Notebook    | [1ebc88d3ab](https://linux-hardware.org/?probe=1ebc88d3ab) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a99920ebba](https://linux-hardware.org/?probe=a99920ebba) | Apr 17, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | Desktop     | [6c08e40387](https://linux-hardware.org/?probe=6c08e40387) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c370821f44](https://linux-hardware.org/?probe=c370821f44) | Apr 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [6c62f23970](https://linux-hardware.org/?probe=6c62f23970) | Apr 16, 2023 |
| HP            | 18E7                        | Desktop     | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [5994a04ee0](https://linux-hardware.org/?probe=5994a04ee0) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [ca89b451bd](https://linux-hardware.org/?probe=ca89b451bd) | Apr 15, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [df2e4c0c56](https://linux-hardware.org/?probe=df2e4c0c56) | Apr 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2c7e1238eb](https://linux-hardware.org/?probe=2c7e1238eb) | Apr 15, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [fcf729207a](https://linux-hardware.org/?probe=fcf729207a) | Apr 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Medion        | MS-7857                     | Desktop     | [5d04997966](https://linux-hardware.org/?probe=5d04997966) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [7f4d0d2d91](https://linux-hardware.org/?probe=7f4d0d2d91) | Apr 14, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [f3114cd0d7](https://linux-hardware.org/?probe=f3114cd0d7) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| Wortmann      | TERRA_MOBILE_1160           | Notebook    | [d40eed27fd](https://linux-hardware.org/?probe=d40eed27fd) | Apr 13, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [0a09da06be](https://linux-hardware.org/?probe=0a09da06be) | Apr 13, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [5411d789c3](https://linux-hardware.org/?probe=5411d789c3) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| Dell          | 03V7GF A01                  | Desktop     | [c309233437](https://linux-hardware.org/?probe=c309233437) | Apr 12, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d2fbfe344c](https://linux-hardware.org/?probe=d2fbfe344c) | Apr 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e8645a51dc](https://linux-hardware.org/?probe=e8645a51dc) | Apr 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3d0ccace69](https://linux-hardware.org/?probe=3d0ccace69) | Apr 11, 2023 |
| Notebook      | NH55RGQ                     | Notebook    | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a2aa745e5c](https://linux-hardware.org/?probe=a2aa745e5c) | Apr 10, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [94efe20a0f](https://linux-hardware.org/?probe=94efe20a0f) | Apr 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [5a903505c7](https://linux-hardware.org/?probe=5a903505c7) | Apr 10, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [02bbb66fe9](https://linux-hardware.org/?probe=02bbb66fe9) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [3fe1220d26](https://linux-hardware.org/?probe=3fe1220d26) | Apr 08, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [76af734c86](https://linux-hardware.org/?probe=76af734c86) | Apr 07, 2023 |
| Notebook      | N141CU                      | Notebook    | [8648ddb323](https://linux-hardware.org/?probe=8648ddb323) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Acer          | Aspire M1930                | Desktop     | [2bc158bf57](https://linux-hardware.org/?probe=2bc158bf57) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| Acer          | Spin SP314-51               | Convertible | [4b3e9e100d](https://linux-hardware.org/?probe=4b3e9e100d) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [405f73f1fd](https://linux-hardware.org/?probe=405f73f1fd) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [0af2f7cc7f](https://linux-hardware.org/?probe=0af2f7cc7f) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [10213d8aa1](https://linux-hardware.org/?probe=10213d8aa1) | Apr 05, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [b34f7e7ea6](https://linux-hardware.org/?probe=b34f7e7ea6) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [e8a69f8de9](https://linux-hardware.org/?probe=e8a69f8de9) | Apr 05, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [519d2a4d5a](https://linux-hardware.org/?probe=519d2a4d5a) | Apr 04, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [f211babaa5](https://linux-hardware.org/?probe=f211babaa5) | Apr 04, 2023 |
| HP            | ProBook 6570b               | Notebook    | [d42564b34f](https://linux-hardware.org/?probe=d42564b34f) | Apr 04, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ec3a161d36](https://linux-hardware.org/?probe=ec3a161d36) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [316e31eae5](https://linux-hardware.org/?probe=316e31eae5) | Apr 04, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [088a09317e](https://linux-hardware.org/?probe=088a09317e) | Apr 04, 2023 |
| HP            | 3032h                       | Desktop     | [75792234b4](https://linux-hardware.org/?probe=75792234b4) | Apr 03, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [1af731cc92](https://linux-hardware.org/?probe=1af731cc92) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [2296872799](https://linux-hardware.org/?probe=2296872799) | Apr 03, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| Toxic         | GM5MPHY                     | Notebook    | [9ce64fb49a](https://linux-hardware.org/?probe=9ce64fb49a) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ac5393930b](https://linux-hardware.org/?probe=ac5393930b) | Apr 02, 2023 |
| ilife         | S806                        | Notebook    | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| Intel         | VALLEYVIEW C0 PLATFORM      | Tablet      | [3dcf212c95](https://linux-hardware.org/?probe=3dcf212c95) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [644ab9aa21](https://linux-hardware.org/?probe=644ab9aa21) | Apr 01, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [3494157f4b](https://linux-hardware.org/?probe=3494157f4b) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5ef1391fb2](https://linux-hardware.org/?probe=5ef1391fb2) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [046d59655e](https://linux-hardware.org/?probe=046d59655e) | Apr 01, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [c1f349f579](https://linux-hardware.org/?probe=c1f349f579) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [8bf693a890](https://linux-hardware.org/?probe=8bf693a890) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ca8ae50d80](https://linux-hardware.org/?probe=ca8ae50d80) | Mar 31, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e18d9530c1](https://linux-hardware.org/?probe=e18d9530c1) | Mar 31, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [c3065ba2b6](https://linux-hardware.org/?probe=c3065ba2b6) | Mar 31, 2023 |
| Medion        | Iron238G                    | All in one  | [55cab5c7fa](https://linux-hardware.org/?probe=55cab5c7fa) | Mar 31, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [96107a824d](https://linux-hardware.org/?probe=96107a824d) | Mar 31, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [34bd6f42b1](https://linux-hardware.org/?probe=34bd6f42b1) | Mar 30, 2023 |
| HP            | 843F                        | Desktop     | [862f573134](https://linux-hardware.org/?probe=862f573134) | Mar 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7edc7c9f47](https://linux-hardware.org/?probe=7edc7c9f47) | Mar 30, 2023 |
| Foxconn       | ETON                        | Desktop     | [52e92b5803](https://linux-hardware.org/?probe=52e92b5803) | Mar 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6ade0ea04f](https://linux-hardware.org/?probe=6ade0ea04f) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [0028f21c3e](https://linux-hardware.org/?probe=0028f21c3e) | Mar 30, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [de3828d539](https://linux-hardware.org/?probe=de3828d539) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [61ede0b764](https://linux-hardware.org/?probe=61ede0b764) | Mar 29, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [39d6f86500](https://linux-hardware.org/?probe=39d6f86500) | Mar 29, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [3cb72ca21c](https://linux-hardware.org/?probe=3cb72ca21c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [799a14a5d5](https://linux-hardware.org/?probe=799a14a5d5) | Mar 28, 2023 |
| MSI           | H87-G41 PC Mate             | Desktop     | [0d1345af82](https://linux-hardware.org/?probe=0d1345af82) | Mar 28, 2023 |
| ZOTAC         | AMD M1                      | Desktop     | [2b2c8fd4fa](https://linux-hardware.org/?probe=2b2c8fd4fa) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [68175ccbea](https://linux-hardware.org/?probe=68175ccbea) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [5fff36a878](https://linux-hardware.org/?probe=5fff36a878) | Mar 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [79c876bced](https://linux-hardware.org/?probe=79c876bced) | Mar 25, 2023 |
| MSI           | 2AE0                        | Desktop     | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Haier         | S15                         | Notebook    | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [8a7f87172d](https://linux-hardware.org/?probe=8a7f87172d) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [55f0bb1013](https://linux-hardware.org/?probe=55f0bb1013) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [1ee3769d23](https://linux-hardware.org/?probe=1ee3769d23) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [06d6af1db0](https://linux-hardware.org/?probe=06d6af1db0) | Mar 23, 2023 |
| Acer          | Aspire M1930                | Desktop     | [228747d646](https://linux-hardware.org/?probe=228747d646) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| HP            | EliteBook 725 G2            | Notebook    | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| HP            | 1494                        | Desktop     | [e682c9975e](https://linux-hardware.org/?probe=e682c9975e) | Mar 21, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [82f97b14f4](https://linux-hardware.org/?probe=82f97b14f4) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [b73f7b46c4](https://linux-hardware.org/?probe=b73f7b46c4) | Mar 20, 2023 |
| Dell          | Latitude E6520              | Notebook    | [7f92514d4e](https://linux-hardware.org/?probe=7f92514d4e) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [3a6814a18f](https://linux-hardware.org/?probe=3a6814a18f) | Mar 20, 2023 |
| Medion        | MS-7797                     | Desktop     | [180b0242e8](https://linux-hardware.org/?probe=180b0242e8) | Mar 20, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a6054e6f0e](https://linux-hardware.org/?probe=a6054e6f0e) | Mar 20, 2023 |
| Lenovo        | [3633AC1] STC               | Server      | [aef7266e33](https://linux-hardware.org/?probe=aef7266e33) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [9d7f6de46c](https://linux-hardware.org/?probe=9d7f6de46c) | Mar 19, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [149e050820](https://linux-hardware.org/?probe=149e050820) | Mar 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [92ae74e13d](https://linux-hardware.org/?probe=92ae74e13d) | Mar 19, 2023 |
| HP            | 8056                        | Desktop     | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e90a87f6f2](https://linux-hardware.org/?probe=e90a87f6f2) | Mar 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [5356d2a0ef](https://linux-hardware.org/?probe=5356d2a0ef) | Mar 18, 2023 |
| HP            | 198E                        | Desktop     | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | Desktop     | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [ba56245418](https://linux-hardware.org/?probe=ba56245418) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| HP            | Compaq 6730s                | Notebook    | [7e2310fcf0](https://linux-hardware.org/?probe=7e2310fcf0) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e0fa4709db](https://linux-hardware.org/?probe=e0fa4709db) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3e5167941c](https://linux-hardware.org/?probe=3e5167941c) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [edf7e8521c](https://linux-hardware.org/?probe=edf7e8521c) | Mar 17, 2023 |
| Dell          | 072T6D A01                  | Server      | [ba5febe33b](https://linux-hardware.org/?probe=ba5febe33b) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| Acer          | Predator PO3-630            | Desktop     | [07ac5c2647](https://linux-hardware.org/?probe=07ac5c2647) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| HP            | 3397                        | Desktop     | [5f261fa554](https://linux-hardware.org/?probe=5f261fa554) | Mar 15, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [a78f938382](https://linux-hardware.org/?probe=a78f938382) | Mar 15, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [1c6475f7da](https://linux-hardware.org/?probe=1c6475f7da) | Mar 15, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fcb50f0e4f](https://linux-hardware.org/?probe=fcb50f0e4f) | Mar 14, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fc7320db54](https://linux-hardware.org/?probe=fc7320db54) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b3e091147a](https://linux-hardware.org/?probe=b3e091147a) | Mar 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [e6d2f2a3b4](https://linux-hardware.org/?probe=e6d2f2a3b4) | Mar 14, 2023 |
| Samsung       | 930QED                      | Convertible | [a3182e0455](https://linux-hardware.org/?probe=a3182e0455) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [70e1aa9793](https://linux-hardware.org/?probe=70e1aa9793) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Dell          | 09N44V A05                  | Server      | [d1a141052c](https://linux-hardware.org/?probe=d1a141052c) | Mar 13, 2023 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [659e2861d9](https://linux-hardware.org/?probe=659e2861d9) | Mar 13, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [9911027e53](https://linux-hardware.org/?probe=9911027e53) | Mar 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [66f70aa8f4](https://linux-hardware.org/?probe=66f70aa8f4) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [eb987f6db2](https://linux-hardware.org/?probe=eb987f6db2) | Mar 12, 2023 |
| Medion        | E4251                       | Notebook    | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [7434247d21](https://linux-hardware.org/?probe=7434247d21) | Mar 12, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [53357f1807](https://linux-hardware.org/?probe=53357f1807) | Mar 11, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | Notebook    | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [3283454c2d](https://linux-hardware.org/?probe=3283454c2d) | Mar 10, 2023 |
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [14bbc3a006](https://linux-hardware.org/?probe=14bbc3a006) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [21595cd5ed](https://linux-hardware.org/?probe=21595cd5ed) | Mar 09, 2023 |
| ASRock        | H87M Pro4                   | Desktop     | [49a012cecd](https://linux-hardware.org/?probe=49a012cecd) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [f4dd257e1d](https://linux-hardware.org/?probe=f4dd257e1d) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [c6119be13a](https://linux-hardware.org/?probe=c6119be13a) | Mar 07, 2023 |
| HP            | 3398                        | Desktop     | [024ce6b407](https://linux-hardware.org/?probe=024ce6b407) | Mar 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Google        | Rammus                      | Notebook    | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [53b112adac](https://linux-hardware.org/?probe=53b112adac) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [52169be881](https://linux-hardware.org/?probe=52169be881) | Mar 05, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [d841b24c32](https://linux-hardware.org/?probe=d841b24c32) | Mar 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [76243066c7](https://linux-hardware.org/?probe=76243066c7) | Mar 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [9667db85fc](https://linux-hardware.org/?probe=9667db85fc) | Mar 05, 2023 |
| HP            | 89B5 A                      | Desktop     | [b1f4e34d2d](https://linux-hardware.org/?probe=b1f4e34d2d) | Mar 04, 2023 |
| ASUSTek       | P5B-MX                      | Desktop     | [823575b2b0](https://linux-hardware.org/?probe=823575b2b0) | Mar 04, 2023 |
| Dell          | Studio XPS 1647             | Notebook    | [484c629656](https://linux-hardware.org/?probe=484c629656) | Mar 04, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [b5b5f89ca1](https://linux-hardware.org/?probe=b5b5f89ca1) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Alienware     | m15                         | Notebook    | [180a0251f5](https://linux-hardware.org/?probe=180a0251f5) | Mar 02, 2023 |
| HP            | 3398                        | Desktop     | [6479dbaa0e](https://linux-hardware.org/?probe=6479dbaa0e) | Mar 02, 2023 |
| HP            | Notebook                    | Notebook    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [bbdc843fb2](https://linux-hardware.org/?probe=bbdc843fb2) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [5bc379ea65](https://linux-hardware.org/?probe=5bc379ea65) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [71b8cbeda5](https://linux-hardware.org/?probe=71b8cbeda5) | Feb 28, 2023 |
| ASUSTek       | N76VB                       | Notebook    | [0043164762](https://linux-hardware.org/?probe=0043164762) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| Sony          | VGN-FW11M                   | Notebook    | [06b355e1de](https://linux-hardware.org/?probe=06b355e1de) | Feb 28, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [6bf890e60c](https://linux-hardware.org/?probe=6bf890e60c) | Feb 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [979b4559fe](https://linux-hardware.org/?probe=979b4559fe) | Feb 27, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [323a03f1c6](https://linux-hardware.org/?probe=323a03f1c6) | Feb 27, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c16b58c7ce](https://linux-hardware.org/?probe=c16b58c7ce) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [9d8016f80e](https://linux-hardware.org/?probe=9d8016f80e) | Feb 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8184285a7d](https://linux-hardware.org/?probe=8184285a7d) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3aae5788cf](https://linux-hardware.org/?probe=3aae5788cf) | Feb 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [8f46d24897](https://linux-hardware.org/?probe=8f46d24897) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2978ec71b8](https://linux-hardware.org/?probe=2978ec71b8) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [ca2ef50547](https://linux-hardware.org/?probe=ca2ef50547) | Feb 25, 2023 |
| Lenovo        | 851F 60072                  | Tablet      | [8466ce344b](https://linux-hardware.org/?probe=8466ce344b) | Feb 24, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3899b2f13e](https://linux-hardware.org/?probe=3899b2f13e) | Feb 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [926fcff980](https://linux-hardware.org/?probe=926fcff980) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [f91140d700](https://linux-hardware.org/?probe=f91140d700) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [66b104fc61](https://linux-hardware.org/?probe=66b104fc61) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [7233b168b4](https://linux-hardware.org/?probe=7233b168b4) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [9398719812](https://linux-hardware.org/?probe=9398719812) | Feb 24, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [2cb9f58eae](https://linux-hardware.org/?probe=2cb9f58eae) | Feb 24, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fa08c93ecd](https://linux-hardware.org/?probe=fa08c93ecd) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a3d9851893](https://linux-hardware.org/?probe=a3d9851893) | Feb 23, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [f348e93361](https://linux-hardware.org/?probe=f348e93361) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [1cca7fe830](https://linux-hardware.org/?probe=1cca7fe830) | Feb 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [de79cbb975](https://linux-hardware.org/?probe=de79cbb975) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [5e92cdeee7](https://linux-hardware.org/?probe=5e92cdeee7) | Feb 22, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [cd66af8994](https://linux-hardware.org/?probe=cd66af8994) | Feb 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1ecf49cbaf](https://linux-hardware.org/?probe=1ecf49cbaf) | Feb 21, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e1c694b371](https://linux-hardware.org/?probe=e1c694b371) | Feb 20, 2023 |
| Dell          | Latitude 7300               | Notebook    | [65690f7efc](https://linux-hardware.org/?probe=65690f7efc) | Feb 20, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0b5bcfefc5](https://linux-hardware.org/?probe=0b5bcfefc5) | Feb 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8ca2b786db](https://linux-hardware.org/?probe=8ca2b786db) | Feb 19, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [db95126414](https://linux-hardware.org/?probe=db95126414) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [c2e0245ec5](https://linux-hardware.org/?probe=c2e0245ec5) | Feb 19, 2023 |
| Dell          | Latitude E6320              | Notebook    | [8110ff7717](https://linux-hardware.org/?probe=8110ff7717) | Feb 19, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [0a015cdb94](https://linux-hardware.org/?probe=0a015cdb94) | Feb 18, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [5857177f10](https://linux-hardware.org/?probe=5857177f10) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3886d9287f](https://linux-hardware.org/?probe=3886d9287f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [1b401aa3cf](https://linux-hardware.org/?probe=1b401aa3cf) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c59694e05c](https://linux-hardware.org/?probe=c59694e05c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c614caec4a](https://linux-hardware.org/?probe=c614caec4a) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c273319d9d](https://linux-hardware.org/?probe=c273319d9d) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [4fe16ec4fe](https://linux-hardware.org/?probe=4fe16ec4fe) | Feb 16, 2023 |
| HP            | Notebook                    | Notebook    | [3de841fd56](https://linux-hardware.org/?probe=3de841fd56) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [130fe12846](https://linux-hardware.org/?probe=130fe12846) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7ca9bf386b](https://linux-hardware.org/?probe=7ca9bf386b) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| HP            | 3031h                       | Desktop     | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [940563622b](https://linux-hardware.org/?probe=940563622b) | Feb 16, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [38c3a4311b](https://linux-hardware.org/?probe=38c3a4311b) | Feb 16, 2023 |
| HP            | 870C                        | Desktop     | [76ae5c62cf](https://linux-hardware.org/?probe=76ae5c62cf) | Feb 15, 2023 |
| Medion        | MS-7616                     | Desktop     | [0655a4e58c](https://linux-hardware.org/?probe=0655a4e58c) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3039ccd4b0](https://linux-hardware.org/?probe=3039ccd4b0) | Feb 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d2754bf08f](https://linux-hardware.org/?probe=d2754bf08f) | Feb 14, 2023 |
| HP            | 3648h                       | Desktop     | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [0d16c9013f](https://linux-hardware.org/?probe=0d16c9013f) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E5570              | Notebook    | [16e090c63c](https://linux-hardware.org/?probe=16e090c63c) | Feb 13, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [7c1423b767](https://linux-hardware.org/?probe=7c1423b767) | Feb 13, 2023 |
| Acer          | Aspire M1930                | Desktop     | [3b78f6fb4e](https://linux-hardware.org/?probe=3b78f6fb4e) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [ea169af948](https://linux-hardware.org/?probe=ea169af948) | Feb 13, 2023 |
| HP            | 843F                        | Desktop     | [3047a0ff5b](https://linux-hardware.org/?probe=3047a0ff5b) | Feb 13, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [672b71db3e](https://linux-hardware.org/?probe=672b71db3e) | Feb 12, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [86026e4f54](https://linux-hardware.org/?probe=86026e4f54) | Feb 12, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [5629f3ed8c](https://linux-hardware.org/?probe=5629f3ed8c) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e1dc99210d](https://linux-hardware.org/?probe=e1dc99210d) | Feb 11, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [95875d4afc](https://linux-hardware.org/?probe=95875d4afc) | Feb 11, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [f5a8290d38](https://linux-hardware.org/?probe=f5a8290d38) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [845d2e4d52](https://linux-hardware.org/?probe=845d2e4d52) | Feb 10, 2023 |
| Dell          | Latitude 3120               | Convertible | [3bf2bfe867](https://linux-hardware.org/?probe=3bf2bfe867) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| Dell          | Precision 3571              | Notebook    | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [353bd3a5b2](https://linux-hardware.org/?probe=353bd3a5b2) | Feb 09, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [f3eb8a2592](https://linux-hardware.org/?probe=f3eb8a2592) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [eeafe897ae](https://linux-hardware.org/?probe=eeafe897ae) | Feb 09, 2023 |
| Medion        | MS-7797                     | Desktop     | [3421cd9be4](https://linux-hardware.org/?probe=3421cd9be4) | Feb 09, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [0779ef912a](https://linux-hardware.org/?probe=0779ef912a) | Feb 08, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [7091e6ba95](https://linux-hardware.org/?probe=7091e6ba95) | Feb 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [2513ec83c8](https://linux-hardware.org/?probe=2513ec83c8) | Feb 08, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [bb851866ac](https://linux-hardware.org/?probe=bb851866ac) | Feb 08, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [e92a6b0131](https://linux-hardware.org/?probe=e92a6b0131) | Feb 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [20d7058e4f](https://linux-hardware.org/?probe=20d7058e4f) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [b376c55e80](https://linux-hardware.org/?probe=b376c55e80) | Feb 07, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [cdc1678cae](https://linux-hardware.org/?probe=cdc1678cae) | Feb 07, 2023 |
| Dell          | Latitude E6320              | Notebook    | [6d1fe4f041](https://linux-hardware.org/?probe=6d1fe4f041) | Feb 06, 2023 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [5d737e59ae](https://linux-hardware.org/?probe=5d737e59ae) | Feb 06, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2e581dc622](https://linux-hardware.org/?probe=2e581dc622) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [3b4320a91a](https://linux-hardware.org/?probe=3b4320a91a) | Feb 06, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [33639358ab](https://linux-hardware.org/?probe=33639358ab) | Feb 06, 2023 |
| Standard      | Unknown                     | Notebook    | [c983c471de](https://linux-hardware.org/?probe=c983c471de) | Feb 05, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [b6333de3ab](https://linux-hardware.org/?probe=b6333de3ab) | Feb 05, 2023 |
| MSI           | MS-7376                     | Desktop     | [5f62748624](https://linux-hardware.org/?probe=5f62748624) | Feb 04, 2023 |
| MSI           | MS-7376                     | Desktop     | [33fa767f72](https://linux-hardware.org/?probe=33fa767f72) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [04c5cc4aec](https://linux-hardware.org/?probe=04c5cc4aec) | Feb 04, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [82a573d8cd](https://linux-hardware.org/?probe=82a573d8cd) | Feb 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [8dee1d9415](https://linux-hardware.org/?probe=8dee1d9415) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [b9e4e36496](https://linux-hardware.org/?probe=b9e4e36496) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [ac1f8787af](https://linux-hardware.org/?probe=ac1f8787af) | Feb 03, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [2a25e1c4d6](https://linux-hardware.org/?probe=2a25e1c4d6) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | Desktop     | [e68a009e8f](https://linux-hardware.org/?probe=e68a009e8f) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [66b96d9a0f](https://linux-hardware.org/?probe=66b96d9a0f) | Jan 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [798466ab86](https://linux-hardware.org/?probe=798466ab86) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [4dbe55873b](https://linux-hardware.org/?probe=4dbe55873b) | Jan 31, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [30a093116e](https://linux-hardware.org/?probe=30a093116e) | Jan 30, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [2469884587](https://linux-hardware.org/?probe=2469884587) | Jan 30, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [bdb3c91476](https://linux-hardware.org/?probe=bdb3c91476) | Jan 29, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [debdb8208f](https://linux-hardware.org/?probe=debdb8208f) | Jan 29, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [d17dc00a8a](https://linux-hardware.org/?probe=d17dc00a8a) | Jan 29, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [8bee986aca](https://linux-hardware.org/?probe=8bee986aca) | Jan 28, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [fb0dcf8d7e](https://linux-hardware.org/?probe=fb0dcf8d7e) | Jan 28, 2023 |
| HP            | 17E2                        | Mini pc     | [41fdb27963](https://linux-hardware.org/?probe=41fdb27963) | Jan 28, 2023 |
| HP            | 0A08h                       | Desktop     | [f9b0168de1](https://linux-hardware.org/?probe=f9b0168de1) | Jan 28, 2023 |
| Dell          | 0599V5 A12                  | Server      | [14f503ae4a](https://linux-hardware.org/?probe=14f503ae4a) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [a50b0e3645](https://linux-hardware.org/?probe=a50b0e3645) | Jan 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [97d1ab1b7d](https://linux-hardware.org/?probe=97d1ab1b7d) | Jan 28, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [86e3285b31](https://linux-hardware.org/?probe=86e3285b31) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [b9793eca79](https://linux-hardware.org/?probe=b9793eca79) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [ee769c62bf](https://linux-hardware.org/?probe=ee769c62bf) | Jan 27, 2023 |
| HP            | 8055                        | Desktop     | [81fa44d8fa](https://linux-hardware.org/?probe=81fa44d8fa) | Jan 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b1079b0bf](https://linux-hardware.org/?probe=1b1079b0bf) | Jan 27, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [c0468fe8fd](https://linux-hardware.org/?probe=c0468fe8fd) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [ab38ecfb97](https://linux-hardware.org/?probe=ab38ecfb97) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | Notebook    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [cb8c4c9711](https://linux-hardware.org/?probe=cb8c4c9711) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [076783b777](https://linux-hardware.org/?probe=076783b777) | Jan 26, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [b5cb34ea4d](https://linux-hardware.org/?probe=b5cb34ea4d) | Jan 26, 2023 |
| Toshiba       | Satellite C870-12F          | Notebook    | [fc9a6d3a7e](https://linux-hardware.org/?probe=fc9a6d3a7e) | Jan 25, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4efa4db490](https://linux-hardware.org/?probe=4efa4db490) | Jan 25, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9b7c80b059](https://linux-hardware.org/?probe=9b7c80b059) | Jan 25, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [dad68fd07f](https://linux-hardware.org/?probe=dad68fd07f) | Jan 24, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [b61b0f981e](https://linux-hardware.org/?probe=b61b0f981e) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [47ff2a2e42](https://linux-hardware.org/?probe=47ff2a2e42) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [a3672f1d47](https://linux-hardware.org/?probe=a3672f1d47) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [3194fb8316](https://linux-hardware.org/?probe=3194fb8316) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [8e124bc501](https://linux-hardware.org/?probe=8e124bc501) | Jan 24, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [75362fb07d](https://linux-hardware.org/?probe=75362fb07d) | Jan 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [7630683952](https://linux-hardware.org/?probe=7630683952) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c427938e2](https://linux-hardware.org/?probe=8c427938e2) | Jan 24, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [5ca72b0d88](https://linux-hardware.org/?probe=5ca72b0d88) | Jan 24, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [5e4253b22d](https://linux-hardware.org/?probe=5e4253b22d) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b4b7ebe3f9](https://linux-hardware.org/?probe=b4b7ebe3f9) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [54313c1c76](https://linux-hardware.org/?probe=54313c1c76) | Jan 23, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [459ab8ae3d](https://linux-hardware.org/?probe=459ab8ae3d) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| Medion        | E4251                       | Notebook    | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0a3f1269f7](https://linux-hardware.org/?probe=0a3f1269f7) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b2792832c2](https://linux-hardware.org/?probe=b2792832c2) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [9beaa4240c](https://linux-hardware.org/?probe=9beaa4240c) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [ffc0fa7fb5](https://linux-hardware.org/?probe=ffc0fa7fb5) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [7933a58a32](https://linux-hardware.org/?probe=7933a58a32) | Jan 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [733770beaf](https://linux-hardware.org/?probe=733770beaf) | Jan 22, 2023 |
| Dell          | Latitude 5520               | Notebook    | [a3541758f7](https://linux-hardware.org/?probe=a3541758f7) | Jan 22, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [40cc1bf7d9](https://linux-hardware.org/?probe=40cc1bf7d9) | Jan 21, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [325f9e8310](https://linux-hardware.org/?probe=325f9e8310) | Jan 21, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [eeea0542b8](https://linux-hardware.org/?probe=eeea0542b8) | Jan 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5d606f2c60](https://linux-hardware.org/?probe=5d606f2c60) | Jan 21, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [acf0fd5893](https://linux-hardware.org/?probe=acf0fd5893) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | Notebook    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [4a2292e809](https://linux-hardware.org/?probe=4a2292e809) | Jan 19, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c7f97640a5](https://linux-hardware.org/?probe=c7f97640a5) | Jan 19, 2023 |
| ASUSTek       | P6T                         | Desktop     | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [1a61029965](https://linux-hardware.org/?probe=1a61029965) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | Notebook                    | Notebook    | [63f0c0b90c](https://linux-hardware.org/?probe=63f0c0b90c) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [da0d1f442a](https://linux-hardware.org/?probe=da0d1f442a) | Jan 19, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [3591fb1d6c](https://linux-hardware.org/?probe=3591fb1d6c) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [798a545fa8](https://linux-hardware.org/?probe=798a545fa8) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [411db3ea66](https://linux-hardware.org/?probe=411db3ea66) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f0ce1e8b3f](https://linux-hardware.org/?probe=f0ce1e8b3f) | Jan 18, 2023 |
| Dell          | Latitude E6540              | Notebook    | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [62d01a5b26](https://linux-hardware.org/?probe=62d01a5b26) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [09e31ee1c8](https://linux-hardware.org/?probe=09e31ee1c8) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f9325236bb](https://linux-hardware.org/?probe=f9325236bb) | Jan 17, 2023 |
| Dell          | Latitude 5530               | Notebook    | [fafa35ef88](https://linux-hardware.org/?probe=fafa35ef88) | Jan 17, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [2cc8923eb1](https://linux-hardware.org/?probe=2cc8923eb1) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [856324369f](https://linux-hardware.org/?probe=856324369f) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [4da81f73f5](https://linux-hardware.org/?probe=4da81f73f5) | Jan 16, 2023 |
| Google        | Banon                       | Notebook    | [6bb3ed04f9](https://linux-hardware.org/?probe=6bb3ed04f9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | Notebook    | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [dc5f6d7ac6](https://linux-hardware.org/?probe=dc5f6d7ac6) | Jan 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [976f23d99e](https://linux-hardware.org/?probe=976f23d99e) | Jan 16, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [01c0e96288](https://linux-hardware.org/?probe=01c0e96288) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [895f75daf7](https://linux-hardware.org/?probe=895f75daf7) | Jan 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [57cd4eaca3](https://linux-hardware.org/?probe=57cd4eaca3) | Jan 15, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [bdfc087b4d](https://linux-hardware.org/?probe=bdfc087b4d) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | Latitude E5410              | Notebook    | [909ca0fd93](https://linux-hardware.org/?probe=909ca0fd93) | Jan 14, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [116b26047d](https://linux-hardware.org/?probe=116b26047d) | Jan 14, 2023 |
| Supermicro    | A1SA2-2750F                 | Server      | [e134d7a317](https://linux-hardware.org/?probe=e134d7a317) | Jan 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [c4cfa1aa47](https://linux-hardware.org/?probe=c4cfa1aa47) | Jan 13, 2023 |
| HP            | ZBook Studio G4             | Notebook    | [67168cc8a9](https://linux-hardware.org/?probe=67168cc8a9) | Jan 13, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [85d6a0b721](https://linux-hardware.org/?probe=85d6a0b721) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | Notebook    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| realme        | CloudProXXXX                | Notebook    | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [178c6f90fa](https://linux-hardware.org/?probe=178c6f90fa) | Jan 13, 2023 |
| Dell          | Latitude 3350               | Notebook    | [065c4a4a95](https://linux-hardware.org/?probe=065c4a4a95) | Jan 12, 2023 |
| Lenovo        | G770 1037                   | Notebook    | [da21020be1](https://linux-hardware.org/?probe=da21020be1) | Jan 12, 2023 |
| HP            | 8648                        | Desktop     | [df76c90c20](https://linux-hardware.org/?probe=df76c90c20) | Jan 12, 2023 |
| Notebook      | NS50MU                      | Notebook    | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| Standard      | Unknown                     | Notebook    | [b6f4b12847](https://linux-hardware.org/?probe=b6f4b12847) | Jan 12, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [77c659307a](https://linux-hardware.org/?probe=77c659307a) | Jan 11, 2023 |
| HP            | Pavilion dv9500             | Notebook    | [0f8c99e8d7](https://linux-hardware.org/?probe=0f8c99e8d7) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [3696db52a7](https://linux-hardware.org/?probe=3696db52a7) | Jan 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [379a5aa220](https://linux-hardware.org/?probe=379a5aa220) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | Notebook    | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7588fecfe8](https://linux-hardware.org/?probe=7588fecfe8) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [69b3403f94](https://linux-hardware.org/?probe=69b3403f94) | Jan 10, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [27b63fd8b1](https://linux-hardware.org/?probe=27b63fd8b1) | Jan 10, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [16a4dc82f5](https://linux-hardware.org/?probe=16a4dc82f5) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [be24cf68d4](https://linux-hardware.org/?probe=be24cf68d4) | Jan 10, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [1375baed6d](https://linux-hardware.org/?probe=1375baed6d) | Jan 09, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [4bbe8325bd](https://linux-hardware.org/?probe=4bbe8325bd) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5663965a51](https://linux-hardware.org/?probe=5663965a51) | Jan 09, 2023 |
| Gigabyte      | J1900N-D2H                  | Desktop     | [62be43a4a3](https://linux-hardware.org/?probe=62be43a4a3) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [1f97553f11](https://linux-hardware.org/?probe=1f97553f11) | Jan 08, 2023 |
| Dell          | 0WG855                      | Desktop     | [0a2e7733bf](https://linux-hardware.org/?probe=0a2e7733bf) | Jan 08, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b39a58c2e6](https://linux-hardware.org/?probe=b39a58c2e6) | Jan 08, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [0d0c035342](https://linux-hardware.org/?probe=0d0c035342) | Jan 08, 2023 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [8ca4d7b38b](https://linux-hardware.org/?probe=8ca4d7b38b) | Jan 08, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [ebf4546adf](https://linux-hardware.org/?probe=ebf4546adf) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Standard      | X50-V2                      | Desktop     | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [67b5b9902a](https://linux-hardware.org/?probe=67b5b9902a) | Jan 06, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [1ff445305d](https://linux-hardware.org/?probe=1ff445305d) | Jan 06, 2023 |
| Unknown       | HX90                        | Desktop     | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e3c76a5b82](https://linux-hardware.org/?probe=e3c76a5b82) | Jan 05, 2023 |
| HP            | 8648                        | Desktop     | [2345926399](https://linux-hardware.org/?probe=2345926399) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| HP            | Pavilion 17                 | Notebook    | [fe325358d6](https://linux-hardware.org/?probe=fe325358d6) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4335d83dfc](https://linux-hardware.org/?probe=4335d83dfc) | Jan 04, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [8027cc9eeb](https://linux-hardware.org/?probe=8027cc9eeb) | Jan 04, 2023 |
| Dell          | Latitude E6330              | Notebook    | [0341a89f2f](https://linux-hardware.org/?probe=0341a89f2f) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | Notebook    | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2f148d690a](https://linux-hardware.org/?probe=2f148d690a) | Jan 03, 2023 |
| ASUSTek       | F1A55-V                     | Desktop     | [fec2a24044](https://linux-hardware.org/?probe=fec2a24044) | Jan 03, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [96c68886cf](https://linux-hardware.org/?probe=96c68886cf) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [efa2748c95](https://linux-hardware.org/?probe=efa2748c95) | Jan 02, 2023 |
| HP            | 3048h                       | Desktop     | [dabc36c98f](https://linux-hardware.org/?probe=dabc36c98f) | Jan 02, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [e93bf27a59](https://linux-hardware.org/?probe=e93bf27a59) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f31ae01428](https://linux-hardware.org/?probe=f31ae01428) | Jan 02, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [0229b8166f](https://linux-hardware.org/?probe=0229b8166f) | Jan 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | Notebook    | [e8b6dd6f1f](https://linux-hardware.org/?probe=e8b6dd6f1f) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [d1f655b9b1](https://linux-hardware.org/?probe=d1f655b9b1) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [c87d61d0cd](https://linux-hardware.org/?probe=c87d61d0cd) | Dec 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [bbf52af119](https://linux-hardware.org/?probe=bbf52af119) | Dec 31, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fc108fb0d8](https://linux-hardware.org/?probe=fc108fb0d8) | Dec 31, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [9e794046d8](https://linux-hardware.org/?probe=9e794046d8) | Dec 30, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [c14cfe5386](https://linux-hardware.org/?probe=c14cfe5386) | Dec 29, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [9f431b484a](https://linux-hardware.org/?probe=9f431b484a) | Dec 29, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [b8cb61c70a](https://linux-hardware.org/?probe=b8cb61c70a) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Alienware     | x17 R2                      | Notebook    | [5a7ea2683a](https://linux-hardware.org/?probe=5a7ea2683a) | Dec 28, 2022 |
| Gigabyte      | GB-BRR3H-4300               | Desktop     | [241d631981](https://linux-hardware.org/?probe=241d631981) | Dec 28, 2022 |
| Dell          | Latitude 2120               | Notebook    | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [488d26f3e8](https://linux-hardware.org/?probe=488d26f3e8) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| LG Electro... | 17Z90Q-G.AA79G              | Notebook    | [59d7266746](https://linux-hardware.org/?probe=59d7266746) | Dec 26, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [43c2d92e5f](https://linux-hardware.org/?probe=43c2d92e5f) | Dec 26, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5d95c28ac6](https://linux-hardware.org/?probe=5d95c28ac6) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [a98ca87f6a](https://linux-hardware.org/?probe=a98ca87f6a) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [00af244895](https://linux-hardware.org/?probe=00af244895) | Dec 25, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5047d29893](https://linux-hardware.org/?probe=5047d29893) | Dec 24, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [ce9fc7a224](https://linux-hardware.org/?probe=ce9fc7a224) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [82cc0b362d](https://linux-hardware.org/?probe=82cc0b362d) | Dec 23, 2022 |
| Intel         | X99                         | Desktop     | [191fefa053](https://linux-hardware.org/?probe=191fefa053) | Dec 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [313bf04928](https://linux-hardware.org/?probe=313bf04928) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | Notebook    | [b5c5aba33a](https://linux-hardware.org/?probe=b5c5aba33a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | Notebook    | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [9b188c358e](https://linux-hardware.org/?probe=9b188c358e) | Dec 21, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [6a6ba7eba1](https://linux-hardware.org/?probe=6a6ba7eba1) | Dec 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [90331ea7da](https://linux-hardware.org/?probe=90331ea7da) | Dec 21, 2022 |
| Dell          | Latitude 5521               | Notebook    | [6fcbfd9271](https://linux-hardware.org/?probe=6fcbfd9271) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| HP            | 3048h                       | Desktop     | [4535cf0f5a](https://linux-hardware.org/?probe=4535cf0f5a) | Dec 20, 2022 |
| HP            | 3048h                       | Desktop     | [1d795fdd33](https://linux-hardware.org/?probe=1d795fdd33) | Dec 19, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2fa8510855](https://linux-hardware.org/?probe=2fa8510855) | Dec 19, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [8d876c21b0](https://linux-hardware.org/?probe=8d876c21b0) | Dec 18, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [71575f3d8c](https://linux-hardware.org/?probe=71575f3d8c) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [3b242628e4](https://linux-hardware.org/?probe=3b242628e4) | Dec 18, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [06f90011b2](https://linux-hardware.org/?probe=06f90011b2) | Dec 18, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [64f5eb2f4b](https://linux-hardware.org/?probe=64f5eb2f4b) | Dec 17, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [5681babfa5](https://linux-hardware.org/?probe=5681babfa5) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [db147cf534](https://linux-hardware.org/?probe=db147cf534) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [fa2cc2d975](https://linux-hardware.org/?probe=fa2cc2d975) | Dec 17, 2022 |
| Acer          | Aspire XC-1660 V:1.1        | Desktop     | [88aa1f841a](https://linux-hardware.org/?probe=88aa1f841a) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [3fd939cef5](https://linux-hardware.org/?probe=3fd939cef5) | Dec 17, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [182e467ce6](https://linux-hardware.org/?probe=182e467ce6) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | Latitude 3120               | Notebook    | [e886df2722](https://linux-hardware.org/?probe=e886df2722) | Dec 16, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [cb963df304](https://linux-hardware.org/?probe=cb963df304) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bc8782be9a](https://linux-hardware.org/?probe=bc8782be9a) | Dec 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d320b71c77](https://linux-hardware.org/?probe=d320b71c77) | Dec 15, 2022 |
| HP            | 3048h                       | Desktop     | [63f57e3458](https://linux-hardware.org/?probe=63f57e3458) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [35ef32b165](https://linux-hardware.org/?probe=35ef32b165) | Dec 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b90d5cfed0](https://linux-hardware.org/?probe=b90d5cfed0) | Dec 14, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [de26ffa293](https://linux-hardware.org/?probe=de26ffa293) | Dec 14, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd65da9c9b](https://linux-hardware.org/?probe=dd65da9c9b) | Dec 14, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Gigabyte      | P35-DS4                     | Desktop     | [3f787740f8](https://linux-hardware.org/?probe=3f787740f8) | Dec 12, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [ee22896cd2](https://linux-hardware.org/?probe=ee22896cd2) | Dec 12, 2022 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [e9c5ef16cd](https://linux-hardware.org/?probe=e9c5ef16cd) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| HP            | 339A                        | Desktop     | [63c184fafd](https://linux-hardware.org/?probe=63c184fafd) | Dec 12, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [f1aa6058e3](https://linux-hardware.org/?probe=f1aa6058e3) | Dec 12, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [56adac1fcb](https://linux-hardware.org/?probe=56adac1fcb) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2c52e941ea](https://linux-hardware.org/?probe=2c52e941ea) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Supermicro    | C7SIM-Q                     | Desktop     | [76cf2b62db](https://linux-hardware.org/?probe=76cf2b62db) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| HP            | 3048h                       | Desktop     | [c2fd939c1f](https://linux-hardware.org/?probe=c2fd939c1f) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [869e2a9671](https://linux-hardware.org/?probe=869e2a9671) | Dec 09, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [503b61f120](https://linux-hardware.org/?probe=503b61f120) | Dec 09, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [1a4bdc4874](https://linux-hardware.org/?probe=1a4bdc4874) | Dec 07, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [611fd80398](https://linux-hardware.org/?probe=611fd80398) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [27dc9420ed](https://linux-hardware.org/?probe=27dc9420ed) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9b7c1953a6](https://linux-hardware.org/?probe=9b7c1953a6) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [a7d8d66fb7](https://linux-hardware.org/?probe=a7d8d66fb7) | Dec 07, 2022 |
| Dell          | XPS 9320                    | Notebook    | [34c3b0b6a0](https://linux-hardware.org/?probe=34c3b0b6a0) | Dec 06, 2022 |
| Medion        | E4251                       | Notebook    | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [da82fb083d](https://linux-hardware.org/?probe=da82fb083d) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [86e9e1e21e](https://linux-hardware.org/?probe=86e9e1e21e) | Dec 05, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [942312fe9e](https://linux-hardware.org/?probe=942312fe9e) | Dec 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [344b0c3082](https://linux-hardware.org/?probe=344b0c3082) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | Desktop     | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Intel         | Unknown                     | Desktop     | [d00187a52a](https://linux-hardware.org/?probe=d00187a52a) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8890572a5](https://linux-hardware.org/?probe=d8890572a5) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | Notebook    | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c300b0a438](https://linux-hardware.org/?probe=c300b0a438) | Dec 03, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [b0437249b0](https://linux-hardware.org/?probe=b0437249b0) | Dec 03, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [f86e02dee0](https://linux-hardware.org/?probe=f86e02dee0) | Dec 03, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [5864876eff](https://linux-hardware.org/?probe=5864876eff) | Dec 02, 2022 |
| Acer          | Iconia W4-820               | Notebook    | [cf25eeba85](https://linux-hardware.org/?probe=cf25eeba85) | Dec 01, 2022 |
| MSI           | GL62M 7RE                   | Notebook    | [5fcb394edb](https://linux-hardware.org/?probe=5fcb394edb) | Dec 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [df74bf8e13](https://linux-hardware.org/?probe=df74bf8e13) | Dec 01, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e8d75cbeed](https://linux-hardware.org/?probe=e8d75cbeed) | Dec 01, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [b461d54421](https://linux-hardware.org/?probe=b461d54421) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | Notebook    | [29c5e0f7b1](https://linux-hardware.org/?probe=29c5e0f7b1) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [8398d00a16](https://linux-hardware.org/?probe=8398d00a16) | Nov 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d7025eb475](https://linux-hardware.org/?probe=d7025eb475) | Nov 30, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [729bb4ef87](https://linux-hardware.org/?probe=729bb4ef87) | Nov 30, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e214cb1bb9](https://linux-hardware.org/?probe=e214cb1bb9) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | Desktop     | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [dae405ee81](https://linux-hardware.org/?probe=dae405ee81) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [43fa54b5bc](https://linux-hardware.org/?probe=43fa54b5bc) | Nov 28, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [219a616346](https://linux-hardware.org/?probe=219a616346) | Nov 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [bcbdb4bf67](https://linux-hardware.org/?probe=bcbdb4bf67) | Nov 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [f77e444066](https://linux-hardware.org/?probe=f77e444066) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c4bbe90221](https://linux-hardware.org/?probe=c4bbe90221) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [81b0ea6c7a](https://linux-hardware.org/?probe=81b0ea6c7a) | Nov 27, 2022 |
| HP            | ProBook 5330m               | Notebook    | [3763f505a0](https://linux-hardware.org/?probe=3763f505a0) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee2852cb0](https://linux-hardware.org/?probe=bee2852cb0) | Nov 27, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| ASUSTek       | A6R                         | Notebook    | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [8de1db7f12](https://linux-hardware.org/?probe=8de1db7f12) | Nov 25, 2022 |
| Dell          | Latitude 3120               | Convertible | [bb40e36093](https://linux-hardware.org/?probe=bb40e36093) | Nov 24, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [e2a8d64086](https://linux-hardware.org/?probe=e2a8d64086) | Nov 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [6049221fab](https://linux-hardware.org/?probe=6049221fab) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [4adc436e33](https://linux-hardware.org/?probe=4adc436e33) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [84a0005ad3](https://linux-hardware.org/?probe=84a0005ad3) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| HP            | 3397                        | Desktop     | [eb8968148c](https://linux-hardware.org/?probe=eb8968148c) | Nov 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5d3424245f](https://linux-hardware.org/?probe=5d3424245f) | Nov 22, 2022 |
| Dell          | Latitude 5401               | Notebook    | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [72406b1647](https://linux-hardware.org/?probe=72406b1647) | Nov 21, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [635e9fe863](https://linux-hardware.org/?probe=635e9fe863) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [e80e97466d](https://linux-hardware.org/?probe=e80e97466d) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [12799c9216](https://linux-hardware.org/?probe=12799c9216) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e7b9730a4](https://linux-hardware.org/?probe=1e7b9730a4) | Nov 21, 2022 |
| HP            | Unknown                     | Notebook    | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [52c86bac3f](https://linux-hardware.org/?probe=52c86bac3f) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [9c9af5a79e](https://linux-hardware.org/?probe=9c9af5a79e) | Nov 20, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [acb3ae70b9](https://linux-hardware.org/?probe=acb3ae70b9) | Nov 20, 2022 |
| Unknown       | X99H                        | Desktop     | [1c931e307d](https://linux-hardware.org/?probe=1c931e307d) | Nov 20, 2022 |
| Unknown       | X99H                        | Desktop     | [06c69ccbcb](https://linux-hardware.org/?probe=06c69ccbcb) | Nov 20, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [3b5c35b319](https://linux-hardware.org/?probe=3b5c35b319) | Nov 19, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [39a6819014](https://linux-hardware.org/?probe=39a6819014) | Nov 19, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [3e2911ed20](https://linux-hardware.org/?probe=3e2911ed20) | Nov 19, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [3b08108f59](https://linux-hardware.org/?probe=3b08108f59) | Nov 19, 2022 |
| Intel         | X99                         | Desktop     | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| HP            | Notebook                    | Notebook    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [a09398bb26](https://linux-hardware.org/?probe=a09398bb26) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | Notebook    | [5170b27e5c](https://linux-hardware.org/?probe=5170b27e5c) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [62586ed7f9](https://linux-hardware.org/?probe=62586ed7f9) | Nov 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [d5a16ba775](https://linux-hardware.org/?probe=d5a16ba775) | Nov 16, 2022 |
| HP            | Pavilion dv9500             | Notebook    | [65a473401c](https://linux-hardware.org/?probe=65a473401c) | Nov 16, 2022 |
| Acer          | Aspire X3470                | Desktop     | [ccaec6d2cb](https://linux-hardware.org/?probe=ccaec6d2cb) | Nov 15, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [4a80ba0608](https://linux-hardware.org/?probe=4a80ba0608) | Nov 15, 2022 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [6f1cef8a17](https://linux-hardware.org/?probe=6f1cef8a17) | Nov 15, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [d2cf28fbb9](https://linux-hardware.org/?probe=d2cf28fbb9) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [e9182b2177](https://linux-hardware.org/?probe=e9182b2177) | Nov 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [21a6415538](https://linux-hardware.org/?probe=21a6415538) | Nov 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [3ce2f9981f](https://linux-hardware.org/?probe=3ce2f9981f) | Nov 15, 2022 |
| Dell          | Latitude E7450              | Notebook    | [3020a4edfc](https://linux-hardware.org/?probe=3020a4edfc) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [db1488b844](https://linux-hardware.org/?probe=db1488b844) | Nov 15, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [54afa1ee72](https://linux-hardware.org/?probe=54afa1ee72) | Nov 15, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [35f0fc8a5a](https://linux-hardware.org/?probe=35f0fc8a5a) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [bcce834785](https://linux-hardware.org/?probe=bcce834785) | Nov 14, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [26fad3df24](https://linux-hardware.org/?probe=26fad3df24) | Nov 14, 2022 |
| SLIMBOOK      | PROX14                      | Notebook    | [a109c5bf52](https://linux-hardware.org/?probe=a109c5bf52) | Nov 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [92eb4009f3](https://linux-hardware.org/?probe=92eb4009f3) | Nov 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [85c469c069](https://linux-hardware.org/?probe=85c469c069) | Nov 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [dc86aa7d1e](https://linux-hardware.org/?probe=dc86aa7d1e) | Nov 13, 2022 |
| Acer          | Predator G3-710             | Desktop     | [4be3a9e016](https://linux-hardware.org/?probe=4be3a9e016) | Nov 13, 2022 |
| Dell          | Latitude 3380               | Notebook    | [f770a70f68](https://linux-hardware.org/?probe=f770a70f68) | Nov 12, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b4f06e5e2f](https://linux-hardware.org/?probe=b4f06e5e2f) | Nov 12, 2022 |
| HP            | Compaq 6820s                | Notebook    | [c852376664](https://linux-hardware.org/?probe=c852376664) | Nov 12, 2022 |
| HP            | Compaq 6820s                | Notebook    | [dee9dbd56f](https://linux-hardware.org/?probe=dee9dbd56f) | Nov 12, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [7e2577bf51](https://linux-hardware.org/?probe=7e2577bf51) | Nov 10, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [70d68c6ca1](https://linux-hardware.org/?probe=70d68c6ca1) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6dd51f8707](https://linux-hardware.org/?probe=6dd51f8707) | Nov 10, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [a5b6d827b2](https://linux-hardware.org/?probe=a5b6d827b2) | Nov 10, 2022 |
| Panasonic     | CF-R9KWCTDR                 | Notebook    | [2a414f5dc5](https://linux-hardware.org/?probe=2a414f5dc5) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [89aa240b37](https://linux-hardware.org/?probe=89aa240b37) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [e7de2507a0](https://linux-hardware.org/?probe=e7de2507a0) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [b10bd50d9c](https://linux-hardware.org/?probe=b10bd50d9c) | Nov 09, 2022 |
| MSI           | MS-1688                     | Notebook    | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| Dell          | Precision 5550              | Notebook    | [16b375ce77](https://linux-hardware.org/?probe=16b375ce77) | Nov 08, 2022 |
| Dell          | Precision 5550              | Notebook    | [1499c28fe9](https://linux-hardware.org/?probe=1499c28fe9) | Nov 08, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [d29c069985](https://linux-hardware.org/?probe=d29c069985) | Nov 08, 2022 |
| Acer          | SW5-017                     | Notebook    | [d4ff3ee29e](https://linux-hardware.org/?probe=d4ff3ee29e) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [0373b83f63](https://linux-hardware.org/?probe=0373b83f63) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [c383da71e1](https://linux-hardware.org/?probe=c383da71e1) | Nov 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [43eefaca07](https://linux-hardware.org/?probe=43eefaca07) | Nov 06, 2022 |
| ASUSTek       | K56CA                       | Notebook    | [032fa97b2a](https://linux-hardware.org/?probe=032fa97b2a) | Nov 05, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [f80b5eaa0b](https://linux-hardware.org/?probe=f80b5eaa0b) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | Notebook    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [eeda582315](https://linux-hardware.org/?probe=eeda582315) | Nov 04, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [afeb473322](https://linux-hardware.org/?probe=afeb473322) | Nov 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2ff0e6e61e](https://linux-hardware.org/?probe=2ff0e6e61e) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [11d229ea2c](https://linux-hardware.org/?probe=11d229ea2c) | Nov 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [24eea2c3f7](https://linux-hardware.org/?probe=24eea2c3f7) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| HP            | 3646h                       | Desktop     | [e49a380102](https://linux-hardware.org/?probe=e49a380102) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b4f9d04f4d](https://linux-hardware.org/?probe=b4f9d04f4d) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [d1b0eff99b](https://linux-hardware.org/?probe=d1b0eff99b) | Nov 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [020d8fd7e0](https://linux-hardware.org/?probe=020d8fd7e0) | Nov 03, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2ece2f7351](https://linux-hardware.org/?probe=2ece2f7351) | Nov 02, 2022 |
| HP            | 1589                        | Desktop     | [81a347a6a7](https://linux-hardware.org/?probe=81a347a6a7) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| HP            | 212A                        | Desktop     | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | ProBook 4530s               | Notebook    | [6490664312](https://linux-hardware.org/?probe=6490664312) | Nov 01, 2022 |
| HP            | 3646h                       | Desktop     | [f88c9632b4](https://linux-hardware.org/?probe=f88c9632b4) | Nov 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [a85aef0a90](https://linux-hardware.org/?probe=a85aef0a90) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [678ca55a4c](https://linux-hardware.org/?probe=678ca55a4c) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [3cb8d29f84](https://linux-hardware.org/?probe=3cb8d29f84) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [71de876615](https://linux-hardware.org/?probe=71de876615) | Oct 30, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [21aa0f31b3](https://linux-hardware.org/?probe=21aa0f31b3) | Oct 30, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [c54736f079](https://linux-hardware.org/?probe=c54736f079) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Lenovo        | Legion Y740-17ICHg 81HH     | Notebook    | [ea1c9e069e](https://linux-hardware.org/?probe=ea1c9e069e) | Oct 29, 2022 |
| Medion        | X682X                       | Notebook    | [f05dd25a08](https://linux-hardware.org/?probe=f05dd25a08) | Oct 29, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [856d32288b](https://linux-hardware.org/?probe=856d32288b) | Oct 29, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a0714fbb29](https://linux-hardware.org/?probe=a0714fbb29) | Oct 28, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [1b93a2f7df](https://linux-hardware.org/?probe=1b93a2f7df) | Oct 28, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [9a01d62b1e](https://linux-hardware.org/?probe=9a01d62b1e) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [8e25520b70](https://linux-hardware.org/?probe=8e25520b70) | Oct 27, 2022 |
| Dell          | Inspiron 7773               | Notebook    | [34d97b7ea2](https://linux-hardware.org/?probe=34d97b7ea2) | Oct 26, 2022 |
| Dell          | Inspiron 7773               | Notebook    | [c2cff54e7c](https://linux-hardware.org/?probe=c2cff54e7c) | Oct 26, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [6cb48a4d86](https://linux-hardware.org/?probe=6cb48a4d86) | Oct 25, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [0cb3fb3efc](https://linux-hardware.org/?probe=0cb3fb3efc) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [28c38a498d](https://linux-hardware.org/?probe=28c38a498d) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [d761710495](https://linux-hardware.org/?probe=d761710495) | Oct 25, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [54710cefe5](https://linux-hardware.org/?probe=54710cefe5) | Oct 24, 2022 |
| HP            | 1589                        | Desktop     | [0be048ec45](https://linux-hardware.org/?probe=0be048ec45) | Oct 24, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [2c1e50d1a2](https://linux-hardware.org/?probe=2c1e50d1a2) | Oct 22, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [0fd183c6a8](https://linux-hardware.org/?probe=0fd183c6a8) | Oct 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [2b377dce0a](https://linux-hardware.org/?probe=2b377dce0a) | Oct 21, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [b864fd7ffa](https://linux-hardware.org/?probe=b864fd7ffa) | Oct 20, 2022 |
| Gigabyte      | GA-6LXSV 00000001           | Desktop     | [ac15415eca](https://linux-hardware.org/?probe=ac15415eca) | Oct 20, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [51f4793383](https://linux-hardware.org/?probe=51f4793383) | Oct 20, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [c37d6f2369](https://linux-hardware.org/?probe=c37d6f2369) | Oct 20, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [e389da5691](https://linux-hardware.org/?probe=e389da5691) | Oct 20, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [ad9d78fb43](https://linux-hardware.org/?probe=ad9d78fb43) | Oct 19, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [d54932d557](https://linux-hardware.org/?probe=d54932d557) | Oct 19, 2022 |
| Dell          | Latitude 3380               | Notebook    | [352bedd96b](https://linux-hardware.org/?probe=352bedd96b) | Oct 18, 2022 |
| Acer          | Aspire M1930                | Desktop     | [5b9cbd4f58](https://linux-hardware.org/?probe=5b9cbd4f58) | Oct 18, 2022 |
| Dell          | Precision 5530              | Notebook    | [9b344fe820](https://linux-hardware.org/?probe=9b344fe820) | Oct 18, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [ff225777df](https://linux-hardware.org/?probe=ff225777df) | Oct 18, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7919e68317](https://linux-hardware.org/?probe=7919e68317) | Oct 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [8ba8f257d2](https://linux-hardware.org/?probe=8ba8f257d2) | Oct 18, 2022 |
| HP            | ZBook 14u G5                | Notebook    | [151433ee2e](https://linux-hardware.org/?probe=151433ee2e) | Oct 18, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [1117fe6b9e](https://linux-hardware.org/?probe=1117fe6b9e) | Oct 17, 2022 |
| Dell          | Latitude 7480               | Notebook    | [8d55df4648](https://linux-hardware.org/?probe=8d55df4648) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [319c3b9f03](https://linux-hardware.org/?probe=319c3b9f03) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [d1b9bb0a39](https://linux-hardware.org/?probe=d1b9bb0a39) | Oct 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c19a6241e1](https://linux-hardware.org/?probe=c19a6241e1) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [ab6969eabd](https://linux-hardware.org/?probe=ab6969eabd) | Oct 17, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Acer          | Aspire M1930                | Desktop     | [9fa87ae442](https://linux-hardware.org/?probe=9fa87ae442) | Oct 16, 2022 |
| HP            | 3646h                       | Desktop     | [c7436e0f9e](https://linux-hardware.org/?probe=c7436e0f9e) | Oct 16, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [79a5162024](https://linux-hardware.org/?probe=79a5162024) | Oct 16, 2022 |
| Acer          | Predator G3-710             | Desktop     | [289b6c8a18](https://linux-hardware.org/?probe=289b6c8a18) | Oct 16, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [289b913df1](https://linux-hardware.org/?probe=289b913df1) | Oct 16, 2022 |
| Dell          | Latitude E7450              | Notebook    | [500311a1b8](https://linux-hardware.org/?probe=500311a1b8) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [6a6f7314c0](https://linux-hardware.org/?probe=6a6f7314c0) | Oct 15, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Dell          | 0JD6X3 A05                  | Server      | [746232aa34](https://linux-hardware.org/?probe=746232aa34) | Oct 13, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [b75d98cfc2](https://linux-hardware.org/?probe=b75d98cfc2) | Oct 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c39709c3b2](https://linux-hardware.org/?probe=c39709c3b2) | Oct 12, 2022 |
| Lenovo        | Y310                        | Notebook    | [0fe2ca4221](https://linux-hardware.org/?probe=0fe2ca4221) | Oct 12, 2022 |
| Dell          | Latitude E6420              | Notebook    | [0083bd14b8](https://linux-hardware.org/?probe=0083bd14b8) | Oct 12, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| ASUSTek       | P7P55-M                     | Desktop     | [5f84ed0900](https://linux-hardware.org/?probe=5f84ed0900) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5be6738277](https://linux-hardware.org/?probe=5be6738277) | Oct 11, 2022 |
| HP            | 304Ah                       | Desktop     | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [f74cee10ac](https://linux-hardware.org/?probe=f74cee10ac) | Oct 11, 2022 |
| Standard      | X50-V2                      | Desktop     | [fbcfd56903](https://linux-hardware.org/?probe=fbcfd56903) | Oct 11, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [379aad9180](https://linux-hardware.org/?probe=379aad9180) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [11b9941d1c](https://linux-hardware.org/?probe=11b9941d1c) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Medion        | H110H4-EM2                  | Desktop     | [7bd38709d3](https://linux-hardware.org/?probe=7bd38709d3) | Oct 09, 2022 |
| MSI           | GP60 2PE                    | Notebook    | [530a81df09](https://linux-hardware.org/?probe=530a81df09) | Oct 09, 2022 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [8858f6d8f3](https://linux-hardware.org/?probe=8858f6d8f3) | Oct 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 575       | 14.29%  |
| Ubuntu 18.04                 | 305       | 7.58%   |
| Ubuntu 22.04                 | 198       | 4.92%   |
| OpenMandriva 4.3             | 196       | 4.87%   |
| Debian 11                    | 97        | 2.41%   |
| Zorin 16                     | 83        | 2.06%   |
| Linux Mint 20.3              | 71        | 1.76%   |
| Ubuntu 20.10                 | 66        | 1.64%   |
| Arch                         | 66        | 1.64%   |
| Xubuntu 20.04                | 55        | 1.37%   |
| OpenMandriva 4.2             | 55        | 1.37%   |
| Manjaro                      | 55        | 1.37%   |
| KDE neon 20.04               | 54        | 1.34%   |
| Arch Rolling                 | 54        | 1.34%   |
| Fedora 36                    | 53        | 1.32%   |
| Fedora 34                    | 53        | 1.32%   |
| Linux Mint 20.2              | 52        | 1.29%   |
| Ubuntu 21.10                 | 51        | 1.27%   |
| openSUSE Tumbleweed-XXXXXXXX | 49        | 1.22%   |
| Pop!_OS 22.04                | 48        | 1.19%   |
| Fedora 37                    | 48        | 1.19%   |
| Ubuntu 21.04                 | 46        | 1.14%   |
| Linux Mint 20.1              | 46        | 1.14%   |
| Linux Mint 19.3              | 46        | 1.14%   |
| Ubuntu 19.10                 | 43        | 1.07%   |
| Fedora 35                    | 42        | 1.04%   |
| Pop!_OS 20.10                | 41        | 1.02%   |
| Linux Mint 21.1              | 41        | 1.02%   |
| Fedora 33                    | 41        | 1.02%   |
| Pop!_OS 21.04                | 39        | 0.97%   |
| Pop!_OS 20.04                | 39        | 0.97%   |
| Zorin 15                     | 38        | 0.94%   |
| Kubuntu 20.04                | 38        | 0.94%   |
| Fedora 31                    | 38        | 0.94%   |
| Linux Mint 20                | 37        | 0.92%   |
| Ubuntu 22.10                 | 35        | 0.87%   |
| Ubuntu 19.04                 | 35        | 0.87%   |
| Pop!_OS 21.10                | 35        | 0.87%   |
| OpenMandriva 23.01           | 33        | 0.82%   |
| Fedora 32                    | 33        | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1328      | 34.83%  |
| Linux Mint    | 338       | 8.86%   |
| OpenMandriva  | 314       | 8.23%   |
| Fedora        | 288       | 7.55%   |
| Pop!_OS       | 194       | 5.09%   |
| Debian        | 154       | 4.04%   |
| Manjaro       | 147       | 3.86%   |
| Zorin         | 130       | 3.41%   |
| Arch          | 121       | 3.17%   |
| Xubuntu       | 96        | 2.52%   |
| Kubuntu       | 83        | 2.18%   |
| KDE neon      | 73        | 1.91%   |
| openSUSE      | 64        | 1.68%   |
| ArcoLinux     | 36        | 0.94%   |
| Gentoo        | 29        | 0.76%   |
| Kali          | 28        | 0.73%   |
| EndeavourOS   | 27        | 0.71%   |
| ROSA          | 26        | 0.68%   |
| Lubuntu       | 25        | 0.66%   |
| Elementary    | 25        | 0.66%   |
| Ubuntu Unity  | 22        | 0.58%   |
| Ubuntu MATE   | 21        | 0.55%   |
| Clear Linux   | 20        | 0.52%   |
| SteamOS       | 18        | 0.47%   |
| Endless       | 16        | 0.42%   |
| Ubuntu Budgie | 14        | 0.37%   |
| LMDE          | 13        | 0.34%   |
| Parrot        | 12        | 0.31%   |
| MX            | 12        | 0.31%   |
| Peppermint    | 10        | 0.26%   |
| Garuda Linux  | 10        | 0.26%   |
| CentOS        | 10        | 0.26%   |
| Raspbian      | 9         | 0.24%   |
| Solus         | 8         | 0.21%   |
| Nobara        | 6         | 0.16%   |
| BlackPanther  | 6         | 0.16%   |
| RHEL          | 5         | 0.13%   |
| Reborn OS     | 5         | 0.13%   |
| LinuxFX       | 4         | 0.1%    |
| Devuan        | 4         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 195       | 4.37%   |
| 5.4.0-42-generic         | 69        | 1.55%   |
| 5.10.14-desktop-1omv4002 | 54        | 1.21%   |
| 5.4.0-58-generic         | 43        | 0.96%   |
| 5.8.0-50-generic         | 41        | 0.92%   |
| 5.15.0-56-generic        | 38        | 0.85%   |
| 5.15.0-58-generic        | 37        | 0.83%   |
| 5.4.0-52-generic         | 36        | 0.81%   |
| 5.4.0-48-generic         | 35        | 0.78%   |
| 5.11.0-38-generic        | 33        | 0.74%   |
| 5.15.0-46-generic        | 30        | 0.67%   |
| 6.1.1-desktop-1omv2290   | 27        | 0.6%    |
| 5.8.0-43-generic         | 26        | 0.58%   |
| 5.13.0-28-generic        | 26        | 0.58%   |
| 5.11.0-27-generic        | 26        | 0.58%   |
| 5.4.0-77-generic         | 25        | 0.56%   |
| 5.4.0-26-generic         | 25        | 0.56%   |
| 5.15.0-52-generic        | 25        | 0.56%   |
| 5.4.0-40-generic         | 24        | 0.54%   |
| 5.15.0-43-generic        | 24        | 0.54%   |
| 5.19.0-35-generic        | 23        | 0.52%   |
| 5.4.0-37-generic         | 22        | 0.49%   |
| 5.15.0-60-generic        | 22        | 0.49%   |
| 5.15.0-48-generic        | 22        | 0.49%   |
| 6.2.6-desktop-1omv2390   | 21        | 0.47%   |
| 5.8.0-53-generic         | 21        | 0.47%   |
| 5.4.0-65-generic         | 21        | 0.47%   |
| 5.15.0-67-generic        | 21        | 0.47%   |
| 5.13.0-39-generic        | 21        | 0.47%   |
| 5.11.0-7620-generic      | 21        | 0.47%   |
| 5.8.0-7630-generic       | 20        | 0.45%   |
| 5.4.0-56-generic         | 20        | 0.45%   |
| 5.4.0-33-generic         | 20        | 0.45%   |
| 5.4.0-29-generic         | 20        | 0.45%   |
| 5.3.0-46-generic         | 19        | 0.43%   |
| 5.8.0-48-generic         | 18        | 0.4%    |
| 5.4.0-54-generic         | 18        | 0.4%    |
| 5.4.0-47-generic         | 18        | 0.4%    |
| 5.11.0-43-generic        | 18        | 0.4%    |
| 4.15.0-29-generic        | 18        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 713       | 17.02%  |
| 5.15.0  | 355       | 8.48%   |
| 5.8.0   | 284       | 6.78%   |
| 4.15.0  | 240       | 5.73%   |
| 5.11.0  | 235       | 5.61%   |
| 5.13.0  | 199       | 4.75%   |
| 5.16.7  | 198       | 4.73%   |
| 5.3.0   | 141       | 3.37%   |
| 5.10.0  | 114       | 2.72%   |
| 5.0.0   | 106       | 2.53%   |
| 5.19.0  | 96        | 2.29%   |
| 4.18.0  | 72        | 1.72%   |
| 5.10.14 | 57        | 1.36%   |
| 4.19.0  | 36        | 0.86%   |
| 6.1.1   | 31        | 0.74%   |
| 6.2.6   | 27        | 0.64%   |
| 5.14.0  | 23        | 0.55%   |
| 4.4.0   | 18        | 0.43%   |
| 5.6.0   | 16        | 0.38%   |
| 5.16.11 | 16        | 0.38%   |
| 5.17.5  | 15        | 0.36%   |
| 6.0.6   | 14        | 0.33%   |
| 5.9.16  | 14        | 0.33%   |
| 6.1.0   | 13        | 0.31%   |
| 6.0.0   | 11        | 0.26%   |
| 5.3.18  | 11        | 0.26%   |
| 5.18.0  | 11        | 0.26%   |
| 5.17.1  | 11        | 0.26%   |
| 6.0.12  | 10        | 0.24%   |
| 5.16.0  | 10        | 0.24%   |
| 6.3.0   | 9         | 0.21%   |
| 6.2.8   | 9         | 0.21%   |
| 5.9.8   | 9         | 0.21%   |
| 5.9.0   | 9         | 0.21%   |
| 5.8.16  | 9         | 0.21%   |
| 5.17.0  | 9         | 0.21%   |
| 5.16.19 | 9         | 0.21%   |
| 5.15.5  | 9         | 0.21%   |
| 5.15.12 | 9         | 0.21%   |
| 5.14.14 | 9         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 777       | 18.77%  |
| 5.15    | 466       | 11.26%  |
| 5.8     | 335       | 8.09%   |
| 5.11    | 281       | 6.79%   |
| 5.16    | 265       | 6.4%    |
| 4.15    | 241       | 5.82%   |
| 5.13    | 240       | 5.8%    |
| 5.10    | 237       | 5.72%   |
| 5.3     | 173       | 4.18%   |
| 5.19    | 133       | 3.21%   |
| 5.0     | 110       | 2.66%   |
| 6.1     | 100       | 2.42%   |
| 4.18    | 86        | 2.08%   |
| 6.0     | 81        | 1.96%   |
| 6.2     | 74        | 1.79%   |
| 5.17    | 68        | 1.64%   |
| 5.14    | 62        | 1.5%    |
| 5.18    | 61        | 1.47%   |
| 5.9     | 56        | 1.35%   |
| 5.6     | 51        | 1.23%   |
| 4.19    | 49        | 1.18%   |
| 5.12    | 36        | 0.87%   |
| 5.7     | 32        | 0.77%   |
| 5.5     | 28        | 0.68%   |
| 4.9     | 26        | 0.63%   |
| 4.4     | 20        | 0.48%   |
| 6.3     | 9         | 0.22%   |
| 5.2     | 9         | 0.22%   |
| 4.16    | 5         | 0.12%   |
| 4.10    | 5         | 0.12%   |
| 4.20    | 4         | 0.1%    |
| 4.14    | 4         | 0.1%    |
| 4.12    | 4         | 0.1%    |
| 3.10    | 3         | 0.07%   |
| 4.1     | 2         | 0.05%   |
| 3.16    | 2         | 0.05%   |
| 5.17.1  | 1         | 0.02%   |
| 5.1     | 1         | 0.02%   |
| 4.7     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3555      | 95.9%   |
| i686    | 102       | 2.75%   |
| aarch64 | 41        | 1.11%   |
| armv7l  | 7         | 0.19%   |
| armv8l  | 1         | 0.03%   |
| armv6l  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1708      | 44.34%  |
| KDE5             | 668       | 17.34%  |
| Unknown          | 528       | 13.71%  |
| XFCE             | 273       | 7.09%   |
| X-Cinnamon       | 252       | 6.54%   |
| KDE              | 93        | 2.41%   |
| MATE             | 82        | 2.13%   |
| Cinnamon         | 35        | 0.91%   |
| LXQt             | 27        | 0.7%    |
| Pantheon         | 25        | 0.65%   |
| LXDE             | 23        | 0.6%    |
| Budgie           | 23        | 0.6%    |
| Unity            | 22        | 0.57%   |
| i3               | 16        | 0.42%   |
| KDE4             | 15        | 0.39%   |
| GNOME Flashback  | 12        | 0.31%   |
| Openbox          | 6         | 0.16%   |
| Deepin           | 6         | 0.16%   |
| sway             | 5         | 0.13%   |
| icewm            | 5         | 0.13%   |
| enlightenment    | 5         | 0.13%   |
| qtile            | 4         | 0.1%    |
| awesome          | 4         | 0.1%    |
| trinity          | 2         | 0.05%   |
| lightdm-xsession | 2         | 0.05%   |
| GNOME Classic    | 2         | 0.05%   |
| xmonad           | 1         | 0.03%   |
| LeftWM           | 1         | 0.03%   |
| jwm              | 1         | 0.03%   |
| herbstluftwm     | 1         | 0.03%   |
| fluxbox          | 1         | 0.03%   |
| DWM              | 1         | 0.03%   |
| dusk             | 1         | 0.03%   |
| Core             | 1         | 0.03%   |
| bspwm            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2876      | 75.76%  |
| Wayland | 582       | 15.33%  |
| Unknown | 256       | 6.74%   |
| Tty     | 81        | 2.13%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1967      | 51.25%  |
| SDDM    | 564       | 14.7%   |
| GDM     | 459       | 11.96%  |
| GDM3    | 396       | 10.32%  |
| LightDM | 323       | 8.42%   |
| TDM     | 94        | 2.45%   |
| KDM     | 14        | 0.36%   |
| XDM     | 8         | 0.21%   |
| Ly      | 4         | 0.1%    |
| SLiM    | 3         | 0.08%   |
| GREETD  | 3         | 0.08%   |
| NODM    | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1807      | 47.62%  |
| nl_NL       | 1090      | 28.72%  |
| Unknown     | 431       | 11.36%  |
| en_GB       | 152       | 4.01%   |
| C           | 61        | 1.61%   |
| de_DE       | 37        | 0.97%   |
| pl_PL       | 33        | 0.87%   |
| ru_RU       | 24        | 0.63%   |
| en_IE       | 13        | 0.34%   |
| POSIX       | 12        | 0.32%   |
| en_NL       | 12        | 0.32%   |
| fr_FR       | 10        | 0.26%   |
| it_IT       | 8         | 0.21%   |
| en_CA       | 7         | 0.18%   |
| en_IN       | 6         | 0.16%   |
| nl_BE       | 5         | 0.13%   |
| fr_BE       | 5         | 0.13%   |
| es_ES       | 5         | 0.13%   |
| en_DK       | 5         | 0.13%   |
| sv_SE       | 4         | 0.11%   |
| ru_UA       | 4         | 0.11%   |
| pt_PT       | 4         | 0.11%   |
| en_AG       | 4         | 0.11%   |
| de_AT       | 4         | 0.11%   |
| C.UTF8      | 4         | 0.11%   |
| sk_SK       | 3         | 0.08%   |
| nb_NO       | 3         | 0.08%   |
| es_MX       | 3         | 0.08%   |
| en_US.utf-8 | 3         | 0.08%   |
| en_AU       | 3         | 0.08%   |
| cs_CZ       | 3         | 0.08%   |
| zh_CN       | 2         | 0.05%   |
| uk_UA       | 2         | 0.05%   |
| pt_BR       | 2         | 0.05%   |
| nl_AW       | 2         | 0.05%   |
| hu_HU       | 2         | 0.05%   |
| en_ZA       | 2         | 0.05%   |
| en_SG       | 2         | 0.05%   |
| ar_KW       | 2         | 0.05%   |
| tr_TR       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1949      | 51.64%  |
| BIOS | 1825      | 48.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2866      | 75.84%  |
| Overlay | 351       | 9.29%   |
| Btrfs   | 314       | 8.31%   |
| Unknown | 125       | 3.31%   |
| Xfs     | 51        | 1.35%   |
| Zfs     | 38        | 1.01%   |
| Ext2    | 10        | 0.26%   |
| F2fs    | 9         | 0.24%   |
| Tmpfs   | 6         | 0.16%   |
| Ext3    | 5         | 0.13%   |
| Aufs    | 3         | 0.08%   |
| Jfs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2102      | 55.65%  |
| GPT     | 1349      | 35.72%  |
| MBR     | 326       | 8.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3220      | 85.43%  |
| Yes       | 549       | 14.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2636      | 70.2%   |
| Yes       | 1119      | 29.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 596       | 16.11%  |
| Hewlett-Packard         | 585       | 15.81%  |
| ASUSTek Computer        | 522       | 14.11%  |
| Lenovo                  | 413       | 11.16%  |
| Acer                    | 230       | 6.22%   |
| Gigabyte Technology     | 206       | 5.57%   |
| MSI                     | 205       | 5.54%   |
| ASRock                  | 149       | 4.03%   |
| Apple                   | 114       | 3.08%   |
| Intel                   | 80        | 2.16%   |
| Medion                  | 61        | 1.65%   |
| Toshiba                 | 53        | 1.43%   |
| Notebook                | 50        | 1.35%   |
| Raspberry Pi Foundation | 43        | 1.16%   |
| Unknown                 | 27        | 0.73%   |
| Packard Bell            | 26        | 0.7%    |
| Samsung Electronics     | 24        | 0.65%   |
| Fujitsu                 | 21        | 0.57%   |
| Google                  | 18        | 0.49%   |
| Valve                   | 16        | 0.43%   |
| Microsoft               | 16        | 0.43%   |
| Sony                    | 15        | 0.41%   |
| HUAWEI                  | 14        | 0.38%   |
| Fujitsu Siemens         | 12        | 0.32%   |
| Foxconn                 | 12        | 0.32%   |
| Alienware               | 10        | 0.27%   |
| Supermicro              | 8         | 0.22%   |
| Pegatron                | 8         | 0.22%   |
| Biostar                 | 7         | 0.19%   |
| TUXEDO                  | 6         | 0.16%   |
| Timi                    | 6         | 0.16%   |
| Shuttle                 | 6         | 0.16%   |
| Insyde                  | 6         | 0.16%   |
| BESSTAR Tech            | 6         | 0.16%   |
| ZOTAC                   | 5         | 0.14%   |
| Chuwi                   | 5         | 0.14%   |
| AMI                     | 5         | 0.14%   |
| System76                | 4         | 0.11%   |
| SLIMBOOK                | 4         | 0.11%   |
| PC Specialist           | 4         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell Latitude 3120                  | 55        | 1.49%   |
| Dell Latitude 3190 2-in-1           | 41        | 1.11%   |
| Unknown                             | 39        | 1.05%   |
| Dell Latitude 3310                  | 31        | 0.84%   |
| ASUS All Series                     | 27        | 0.73%   |
| RPi Raspberry Pi                    | 17        | 0.46%   |
| Valve Jupiter                       | 16        | 0.43%   |
| Dell XPS 15 7590                    | 12        | 0.32%   |
| Dell OptiPlex 7010                  | 11        | 0.3%    |
| RPi Raspberry Pi 4 Model B Rev 1.4  | 10        | 0.27%   |
| MSI MS-7C02                         | 10        | 0.27%   |
| HP Notebook                         | 10        | 0.27%   |
| HP Pavilion dv7                     | 9         | 0.24%   |
| HP ZBook Studio G5                  | 8         | 0.22%   |
| HP Pavilion g7                      | 8         | 0.22%   |
| Dell XPS 15 9560                    | 8         | 0.22%   |
| Dell OptiPlex 3020                  | 8         | 0.22%   |
| Dell Latitude 3300                  | 8         | 0.22%   |
| ASRock B450M Pro4                   | 8         | 0.22%   |
| Apple MacBookPro9,2                 | 8         | 0.22%   |
| MSI MS-7C37                         | 7         | 0.19%   |
| MSI MS-7B86                         | 7         | 0.19%   |
| MSI MS-7817                         | 7         | 0.19%   |
| HP Pavilion Laptop 15-cw1xxx        | 7         | 0.19%   |
| HP Pavilion Gaming Laptop 15-cx0xxx | 7         | 0.19%   |
| HP Pavilion g6                      | 7         | 0.19%   |
| Dell XPS 13 9310                    | 7         | 0.19%   |
| Dell Latitude E6410                 | 7         | 0.19%   |
| MSI MS-7721                         | 6         | 0.16%   |
| Intel NUC8i3BEH                     | 6         | 0.16%   |
| HP ProBook 6570b                    | 6         | 0.16%   |
| HP Pavilion dv6                     | 6         | 0.16%   |
| HP EliteBook 8570w                  | 6         | 0.16%   |
| HP EliteBook 8460p                  | 6         | 0.16%   |
| HP Compaq Elite 8300 SFF            | 6         | 0.16%   |
| HP Compaq dc7900 Small Form Factor  | 6         | 0.16%   |
| Dell XPS 15 9570                    | 6         | 0.16%   |
| Dell XPS 15 9550                    | 6         | 0.16%   |
| Dell XPS 15 9500                    | 6         | 0.16%   |
| Dell XPS 13 9360                    | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 304       | 8.22%   |
| Lenovo ThinkPad       | 210       | 5.68%   |
| Acer Aspire           | 156       | 4.22%   |
| HP Compaq             | 102       | 2.76%   |
| HP Pavilion           | 101       | 2.73%   |
| HP EliteBook          | 95        | 2.57%   |
| Dell XPS              | 95        | 2.57%   |
| Lenovo IdeaPad        | 68        | 1.84%   |
| HP ProBook            | 65        | 1.76%   |
| Dell OptiPlex         | 63        | 1.7%    |
| ASUS PRIME            | 58        | 1.57%   |
| ASUS ROG              | 49        | 1.32%   |
| Toshiba Satellite     | 48        | 1.3%    |
| Dell Inspiron         | 47        | 1.27%   |
| RPi Raspberry         | 43        | 1.16%   |
| Unknown               | 39        | 1.05%   |
| HP ZBook              | 34        | 0.92%   |
| Dell Precision        | 33        | 0.89%   |
| Lenovo Yoga           | 32        | 0.86%   |
| HP ENVY               | 29        | 0.78%   |
| ASUS All              | 27        | 0.73%   |
| Lenovo Legion         | 24        | 0.65%   |
| ASUS VivoBook         | 22        | 0.59%   |
| HP Laptop             | 20        | 0.54%   |
| Packard Bell EasyNote | 19        | 0.51%   |
| Gigabyte X570         | 19        | 0.51%   |
| ASUS TUF              | 19        | 0.51%   |
| Valve Jupiter         | 16        | 0.43%   |
| Microsoft Surface     | 16        | 0.43%   |
| Lenovo ThinkCentre    | 14        | 0.38%   |
| Acer Swift            | 14        | 0.38%   |
| Lenovo ThinkBook      | 13        | 0.35%   |
| HP ProDesk            | 13        | 0.35%   |
| Fujitsu LIFEBOOK      | 13        | 0.35%   |
| ASUS ZenBook          | 13        | 0.35%   |
| Acer TravelMate       | 12        | 0.32%   |
| HP Spectre            | 11        | 0.3%    |
| Dell Studio           | 11        | 0.3%    |
| ASRock B450M          | 11        | 0.3%    |
| MSI MS-7C02           | 10        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 441       | 11.92%  |
| 2018    | 321       | 8.68%   |
| 2020    | 288       | 7.78%   |
| 2012    | 280       | 7.57%   |
| 2021    | 276       | 7.46%   |
| 2011    | 249       | 6.73%   |
| 2013    | 237       | 6.41%   |
| 2017    | 223       | 6.03%   |
| 2014    | 199       | 5.38%   |
| 2016    | 189       | 5.11%   |
| 2010    | 187       | 5.05%   |
| 2015    | 185       | 5%      |
| 2008    | 152       | 4.11%   |
| 2009    | 148       | 4%      |
| 2007    | 109       | 2.95%   |
| 2022    | 96        | 2.59%   |
| 2006    | 49        | 1.32%   |
| Unknown | 45        | 1.22%   |
| 2005    | 12        | 0.32%   |
| 2004    | 6         | 0.16%   |
| 2023    | 4         | 0.11%   |
| 2003    | 3         | 0.08%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1963      | 53.05%  |
| Desktop        | 1297      | 35.05%  |
| Convertible    | 192       | 5.19%   |
| Mini pc        | 86        | 2.32%   |
| System on chip | 47        | 1.27%   |
| All in one     | 46        | 1.24%   |
| Tablet         | 40        | 1.08%   |
| Server         | 27        | 0.73%   |
| Phone          | 2         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3416      | 91.7%   |
| Enabled  | 309       | 8.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3676      | 99.35%  |
| Yes  | 24        | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 876       | 23.29%  |
| 16.01-24.0      | 769       | 20.45%  |
| 3.01-4.0        | 689       | 18.32%  |
| 8.01-16.0       | 637       | 16.94%  |
| 32.01-64.0      | 378       | 10.05%  |
| 1.01-2.0        | 144       | 3.83%   |
| 64.01-256.0     | 95        | 2.53%   |
| 2.01-3.0        | 69        | 1.83%   |
| 24.01-32.0      | 67        | 1.78%   |
| 0.51-1.0        | 35        | 0.93%   |
| More than 256.0 | 1         | 0.03%   |
| 0.01-0.5        | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1514      | 37.14%  |
| 2.01-3.0    | 950       | 23.3%   |
| 4.01-8.0    | 548       | 13.44%  |
| 3.01-4.0    | 519       | 12.73%  |
| 0.51-1.0    | 268       | 6.57%   |
| 8.01-16.0   | 191       | 4.68%   |
| 0.01-0.5    | 39        | 0.96%   |
| 16.01-24.0  | 34        | 0.83%   |
| 32.01-64.0  | 10        | 0.25%   |
| 24.01-32.0  | 3         | 0.07%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2230      | 58.78%  |
| 2       | 938       | 24.72%  |
| 3       | 292       | 7.7%    |
| 4       | 145       | 3.82%   |
| 5       | 72        | 1.9%    |
| 0       | 51        | 1.34%   |
| 6       | 30        | 0.79%   |
| 7       | 19        | 0.5%    |
| 8       | 6         | 0.16%   |
| 9       | 4         | 0.11%   |
| Unknown | 4         | 0.11%   |
| 28      | 1         | 0.03%   |
| 27      | 1         | 0.03%   |
| 10      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2343      | 62.76%  |
| Yes       | 1390      | 37.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3093      | 83.32%  |
| No        | 619       | 16.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2739      | 73.69%  |
| No        | 978       | 26.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2231      | 59.3%   |
| No        | 1531      | 40.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 3700      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 685       | 17.4%   |
| The Hague              | 191       | 4.85%   |
| Schagen                | 142       | 3.61%   |
| Rotterdam              | 128       | 3.25%   |
| Utrecht                | 94        | 2.39%   |
| Delft                  | 81        | 2.06%   |
| Haarlem                | 78        | 1.98%   |
| Groningen              | 67        | 1.7%    |
| Almere Stad            | 58        | 1.47%   |
| Eindhoven              | 57        | 1.45%   |
| Tilburg                | 46        | 1.17%   |
| Amersfoort             | 46        | 1.17%   |
| Naaldwijk              | 43        | 1.09%   |
| Leiden                 | 38        | 0.97%   |
| Enschede               | 36        | 0.91%   |
| Nijmegen               | 34        | 0.86%   |
| Zoetermeer             | 32        | 0.81%   |
| Breda                  | 30        | 0.76%   |
| Arnhem                 | 30        | 0.76%   |
| Apeldoorn              | 28        | 0.71%   |
| Almelo                 | 28        | 0.71%   |
| Hilversum              | 27        | 0.69%   |
| Capelle aan den IJssel | 24        | 0.61%   |
| Amstelveen             | 24        | 0.61%   |
| Zwolle                 | 23        | 0.58%   |
| Zeist                  | 23        | 0.58%   |
| Maastricht             | 21        | 0.53%   |
| Dordrecht              | 21        | 0.53%   |
| Assen                  | 21        | 0.53%   |
| Roosendaal             | 20        | 0.51%   |
| Lelystad               | 20        | 0.51%   |
| Alkmaar                | 20        | 0.51%   |
| 's-Hertogenbosch       | 20        | 0.51%   |
| Schiedam               | 17        | 0.43%   |
| Purmerend              | 17        | 0.43%   |
| Leeuwarden             | 17        | 0.43%   |
| Gouda                  | 17        | 0.43%   |
| Heerlen                | 16        | 0.41%   |
| Meppel                 | 15        | 0.38%   |
| Hoofddorp              | 15        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1218      | 1971   | 22.93%  |
| WDC                         | 701       | 1074   | 13.2%   |
| Seagate                     | 649       | 1023   | 12.22%  |
| Kingston                    | 324       | 425    | 6.1%    |
| Toshiba                     | 291       | 397    | 5.48%   |
| SanDisk                     | 236       | 318    | 4.44%   |
| Unknown                     | 227       | 284    | 4.27%   |
| Crucial                     | 227       | 294    | 4.27%   |
| SK hynix                    | 188       | 219    | 3.54%   |
| Hitachi                     | 162       | 208    | 3.05%   |
| Intel                       | 160       | 215    | 3.01%   |
| HGST                        | 94        | 116    | 1.77%   |
| Micron Technology           | 68        | 81     | 1.28%   |
| A-DATA Technology           | 60        | 65     | 1.13%   |
| Apple                       | 50        | 70     | 0.94%   |
| KIOXIA                      | 49        | 63     | 0.92%   |
| LITEON                      | 41        | 51     | 0.77%   |
| Maxtor                      | 31        | 43     | 0.58%   |
| OCZ                         | 29        | 37     | 0.55%   |
| Corsair                     | 27        | 36     | 0.51%   |
| China                       | 27        | 37     | 0.51%   |
| Phison                      | 26        | 39     | 0.49%   |
| Transcend                   | 23        | 28     | 0.43%   |
| LITEONIT                    | 23        | 26     | 0.43%   |
| PNY                         | 21        | 25     | 0.4%    |
| Fujitsu                     | 21        | 23     | 0.4%    |
| SSSTC                       | 19        | 20     | 0.36%   |
| Kingston Technology Company | 16        | 18     | 0.3%    |
| Gigabyte Technology         | 15        | 20     | 0.28%   |
| ASMT                        | 15        | 17     | 0.28%   |
| Micron/Crucial Technology   | 14        | 18     | 0.26%   |
| Intenso                     | 14        | 14     | 0.26%   |
| KingFast                    | 13        | 17     | 0.24%   |
| Unknown                     | 13        | 16     | 0.24%   |
| SPCC                        | 12        | 13     | 0.23%   |
| Patriot                     | 12        | 15     | 0.23%   |
| GOODRAM                     | 12        | 13     | 0.23%   |
| JMicron Technology          | 11        | 18     | 0.21%   |
| Phison Electronics          | 9         | 11     | 0.17%   |
| XPG                         | 8         | 10     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                          | 94        | 1.57%   |
| Samsung SSD 860 EVO 500GB                          | 65        | 1.09%   |
| Samsung SSD 850 EVO 500GB                          | 59        | 0.99%   |
| Samsung NVMe SSD Drive 500GB                       | 47        | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 47        | 0.79%   |
| Samsung NVMe SSD Drive 1TB                         | 46        | 0.77%   |
| Kingston SA400S37240G 240GB SSD                    | 45        | 0.75%   |
| Unknown MMC Card  32GB                             | 43        | 0.72%   |
| Samsung SSD 840 EVO 250GB                          | 40        | 0.67%   |
| Kingston SA400S37120G 120GB SSD                    | 40        | 0.67%   |
| Seagate Expansion 4TB                              | 32        | 0.54%   |
| Samsung SSD 860 EVO 1TB                            | 31        | 0.52%   |
| Samsung SSD 840 EVO 120GB                          | 31        | 0.52%   |
| Crucial CT500MX500SSD1 500GB                       | 31        | 0.52%   |
| Samsung SSD 970 EVO 1TB                            | 30        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                    | 29        | 0.49%   |
| Kingston SV300S37A120G 120GB SSD                   | 29        | 0.49%   |
| Unknown MMC Card  64GB                             | 28        | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                     | 28        | 0.47%   |
| Samsung NVMe SSD Drive 256GB                       | 28        | 0.47%   |
| Seagate ST1000LM035-1RK172 970GB                   | 26        | 0.43%   |
| HGST HTS721010A9E630 1TB                           | 26        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                       | 25        | 0.42%   |
| Samsung SSD 980 1TB                                | 24        | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 23        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                        | 23        | 0.38%   |
| Toshiba DT01ACA100 1TB                             | 22        | 0.37%   |
| SK hynix BC711 NVMe 128GB                          | 22        | 0.37%   |
| Seagate ST9500325AS 500GB                          | 22        | 0.37%   |
| Samsung NVMe SSD Drive 1024GB                      | 22        | 0.37%   |
| Toshiba MQ01ABF050 500GB                           | 21        | 0.35%   |
| Samsung SSD 860 QVO 1TB                            | 21        | 0.35%   |
| Crucial CT240BX500SSD1 240GB                       | 21        | 0.35%   |
| Seagate ST1000DM010-2EP102 1TB                     | 20        | 0.33%   |
| Samsung SSD 970 EVO Plus 1TB                       | 20        | 0.33%   |
| Samsung SSD 870 QVO 1TB                            | 20        | 0.33%   |
| Toshiba MQ01ABD100 1TB                             | 19        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                       | 19        | 0.32%   |
| Samsung SSD 860 EVO 250GB                          | 19        | 0.32%   |
| Samsung SSD 850 EVO 120GB                          | 17        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 640       | 1006   | 33.72%  |
| WDC                 | 565       | 877    | 29.77%  |
| Toshiba             | 198       | 280    | 10.43%  |
| Hitachi             | 162       | 208    | 8.54%   |
| Samsung Electronics | 133       | 212    | 7.01%   |
| HGST                | 94        | 116    | 4.95%   |
| Maxtor              | 31        | 43     | 1.63%   |
| Fujitsu             | 21        | 23     | 1.11%   |
| Apple               | 11        | 15     | 0.58%   |
| Unknown             | 8         | 15     | 0.42%   |
| JMicron Technology  | 7         | 10     | 0.37%   |
| Intenso             | 3         | 3      | 0.16%   |
| HGST HTS            | 3         | 4      | 0.16%   |
| ASMT                | 3         | 5      | 0.16%   |
| SAGE                | 2         | 2      | 0.11%   |
| KESU                | 2         | 2      | 0.11%   |
| IBM/Hitachi         | 2         | 2      | 0.11%   |
| ExcelStor           | 2         | 2      | 0.11%   |
| ASMedia             | 2         | 4      | 0.11%   |
| Synology            | 1         | 1      | 0.05%   |
| QNAP                | 1         | 1      | 0.05%   |
| NAS                 | 1         | 10     | 0.05%   |
| Maxtor 6            | 1         | 2      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| LIO-ORG             | 1         | 4      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| Inateck             | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 648       | 964    | 34.16%  |
| Kingston            | 242       | 305    | 12.76%  |
| Crucial             | 216       | 283    | 11.39%  |
| SanDisk             | 153       | 190    | 8.07%   |
| WDC                 | 74        | 102    | 3.9%    |
| Intel               | 66        | 83     | 3.48%   |
| A-DATA Technology   | 50        | 55     | 2.64%   |
| SK hynix            | 42        | 53     | 2.21%   |
| LITEON              | 34        | 44     | 1.79%   |
| Micron Technology   | 32        | 42     | 1.69%   |
| OCZ                 | 29        | 37     | 1.53%   |
| Apple               | 28        | 34     | 1.48%   |
| China               | 27        | 37     | 1.42%   |
| Toshiba             | 26        | 31     | 1.37%   |
| LITEONIT            | 23        | 26     | 1.21%   |
| PNY                 | 21        | 25     | 1.11%   |
| Corsair             | 20        | 28     | 1.05%   |
| Transcend           | 19        | 24     | 1%      |
| SPCC                | 12        | 13     | 0.63%   |
| Patriot             | 12        | 15     | 0.63%   |
| GOODRAM             | 12        | 13     | 0.63%   |
| ASMT                | 12        | 12     | 0.63%   |
| Intenso             | 9         | 9      | 0.47%   |
| Mushkin             | 5         | 7      | 0.26%   |
| KingSpec            | 5         | 6      | 0.26%   |
| KingFast            | 5         | 6      | 0.26%   |
| Gigabyte Technology | 5         | 9      | 0.26%   |
| Netac               | 4         | 4      | 0.21%   |
| Apacer              | 4         | 4      | 0.21%   |
| ACASIS              | 4         | 4      | 0.21%   |
| Unknown             | 4         | 7      | 0.21%   |
| Unknown             | 3         | 3      | 0.16%   |
| SSSTC               | 3         | 3      | 0.16%   |
| Plextor             | 3         | 4      | 0.16%   |
| Leven               | 3         | 3      | 0.16%   |
| Vaseky              | 2         | 2      | 0.11%   |
| Team                | 2         | 4      | 0.11%   |
| Seagate             | 2         | 2      | 0.11%   |
| Phison              | 2         | 5      | 0.11%   |
| KingDian            | 2         | 2      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1669      | 2540   | 34.72%  |
| HDD     | 1564      | 2851   | 32.54%  |
| NVMe    | 1296      | 1851   | 26.96%  |
| MMC     | 224       | 270    | 4.66%   |
| Unknown | 54        | 68     | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2582      | 5130   | 59.89%  |
| NVMe | 1294      | 1844   | 30.02%  |
| MMC  | 224       | 270    | 5.2%    |
| SAS  | 211       | 336    | 4.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2100      | 3291   | 61.66%  |
| 0.51-1.0   | 814       | 1223   | 23.9%   |
| 1.01-2.0   | 268       | 441    | 7.87%   |
| 3.01-4.0   | 101       | 189    | 2.97%   |
| 2.01-3.0   | 58        | 82     | 1.7%    |
| 4.01-10.0  | 53        | 127    | 1.56%   |
| 10.01-20.0 | 11        | 37     | 0.32%   |
| 20.01-50.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1040      | 26.58%  |
| 251-500        | 758       | 19.38%  |
| 501-1000       | 509       | 13.01%  |
| 1-20           | 414       | 10.58%  |
| 1001-2000      | 325       | 8.31%   |
| 51-100         | 253       | 6.47%   |
| More than 3000 | 217       | 5.55%   |
| 21-50          | 178       | 4.55%   |
| 2001-3000      | 115       | 2.94%   |
| Unknown        | 103       | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1644      | 40.7%   |
| 21-50          | 588       | 14.56%  |
| 101-250        | 467       | 11.56%  |
| 51-100         | 430       | 10.65%  |
| 251-500        | 292       | 7.23%   |
| 501-1000       | 249       | 6.16%   |
| 1001-2000      | 124       | 3.07%   |
| Unknown        | 103       | 2.55%   |
| More than 3000 | 91        | 2.25%   |
| 2001-3000      | 49        | 1.21%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 1.7%    |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 4         | 4      | 1.7%    |
| Kingston SV300S37A120G 120GB SSD      | 4         | 5      | 1.7%    |
| WDC WD10EADS-22M2B0 1TB               | 3         | 3      | 1.28%   |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 1.28%   |
| Seagate ST9250410AS 250GB             | 3         | 3      | 1.28%   |
| Intel SSDSC2BW120A4 120GB             | 3         | 4      | 1.28%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.28%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 1.28%   |
| Crucial CT128MX100SSD1 128GB          | 3         | 3      | 1.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.85%   |
| WDC WD60EFRX-68MYMN1 6TB              | 2         | 2      | 0.85%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 2      | 0.85%   |
| Toshiba MQ01ABD050 500GB              | 2         | 3      | 0.85%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 0.85%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.85%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.85%   |
| Seagate ST380011A 80GB                | 2         | 2      | 0.85%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 0.85%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 0.85%   |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 0.85%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 0.85%   |
| Samsung Electronics HM500JI 500GB     | 2         | 2      | 0.85%   |
| Samsung Electronics HD753LJ 752GB     | 2         | 2      | 0.85%   |
| Samsung Electronics HD103UJ 1TB       | 2         | 2      | 0.85%   |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 0.85%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 0.85%   |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 0.85%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 3      | 0.85%   |
| Hitachi HTS725050A7E630 500GB         | 2         | 2      | 0.85%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 3      | 0.85%   |
| Fujitsu MHZ2320BH G2 320GB            | 2         | 2      | 0.85%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 0.85%   |
| WDC WD800JD-00HKA0 80GB               | 1         | 1      | 0.43%   |
| WDC WD7500BPVT-08HXZT3 752GB          | 1         | 1      | 0.43%   |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.43%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.43%   |
| WDC WD600UE-22HCT0 64GB               | 1         | 1      | 0.43%   |
| WDC WD5000HHTZ-04N21V0 500GB          | 1         | 1      | 0.43%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 55        | 66     | 23.71%  |
| Seagate                     | 43        | 58     | 18.53%  |
| Samsung Electronics         | 16        | 19     | 6.9%    |
| Kingston                    | 15        | 17     | 6.47%   |
| Hitachi                     | 15        | 16     | 6.47%   |
| Intel                       | 14        | 19     | 6.03%   |
| Crucial                     | 12        | 19     | 5.17%   |
| Toshiba                     | 11        | 12     | 4.74%   |
| HGST                        | 10        | 12     | 4.31%   |
| SanDisk                     | 8         | 8      | 3.45%   |
| SK hynix                    | 6         | 6      | 2.59%   |
| Fujitsu                     | 4         | 4      | 1.72%   |
| Micron Technology           | 3         | 3      | 1.29%   |
| Maxtor                      | 3         | 5      | 1.29%   |
| OCZ                         | 2         | 2      | 0.86%   |
| LITEON                      | 2         | 4      | 0.86%   |
| Corsair                     | 2         | 4      | 0.86%   |
| A-DATA Technology           | 2         | 2      | 0.86%   |
| Realtek                     | 1         | 1      | 0.43%   |
| Patriot                     | 1         | 1      | 0.43%   |
| LITEONIT                    | 1         | 1      | 0.43%   |
| Kingston Technology Company | 1         | 1      | 0.43%   |
| Intenso                     | 1         | 1      | 0.43%   |
| GOODRAM                     | 1         | 1      | 0.43%   |
| C-Series                    | 1         | 1      | 0.43%   |
| Apple                       | 1         | 1      | 0.43%   |
| Anobit                      | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 53        | 64     | 36.05%  |
| Seagate             | 43        | 58     | 29.25%  |
| Hitachi             | 15        | 16     | 10.2%   |
| Toshiba             | 10        | 11     | 6.8%    |
| HGST                | 10        | 12     | 6.8%    |
| Samsung Electronics | 8         | 8      | 5.44%   |
| Fujitsu             | 4         | 4      | 2.72%   |
| Maxtor              | 3         | 5      | 2.04%   |
| Apple               | 1         | 1      | 0.68%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 137       | 179    | 61.71%  |
| SSD  | 76        | 91     | 34.23%  |
| NVMe | 9         | 15     | 4.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 1      | 14.29%  |
| Toshiba MK5065GSXN 500GB          | 1         | 1      | 14.29%  |
| Seagate ST2000DL001-9VT156 2TB    | 1         | 1      | 14.29%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 14.29%  |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 14.29%  |
| Crucial M4-CT256M4SSD3 256GB      | 1         | 1      | 14.29%  |
| Apple HDD HTS541010A9E662 1TB     | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |
| Apple               | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2375      | 4968   | 60.26%  |
| Works    | 1346      | 2320   | 34.15%  |
| Malfunc  | 213       | 285    | 5.4%    |
| Failed   | 7         | 7      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2419      | 52.4%   |
| Samsung Electronics              | 579       | 12.54%  |
| AMD                              | 577       | 12.5%   |
| SanDisk                          | 152       | 3.29%   |
| SK hynix                         | 144       | 3.12%   |
| Kingston Technology Company      | 97        | 2.1%    |
| Toshiba America Info Systems     | 79        | 1.71%   |
| ASMedia Technology               | 71        | 1.54%   |
| JMicron Technology               | 59        | 1.28%   |
| Nvidia                           | 57        | 1.23%   |
| Marvell Technology Group         | 51        | 1.1%    |
| Phison Electronics               | 50        | 1.08%   |
| KIOXIA                           | 48        | 1.04%   |
| Micron Technology                | 37        | 0.8%    |
| Micron/Crucial Technology        | 23        | 0.5%    |
| Solid State Storage Technology   | 17        | 0.37%   |
| VIA Technologies                 | 15        | 0.32%   |
| Silicon Motion                   | 14        | 0.3%    |
| ADATA Technology                 | 14        | 0.3%    |
| Silicon Integrated Systems [SiS] | 13        | 0.28%   |
| Apple                            | 12        | 0.26%   |
| Broadcom / LSI                   | 11        | 0.24%   |
| Lite-On Technology               | 10        | 0.22%   |
| Silicon Image                    | 8         | 0.17%   |
| Seagate Technology               | 8         | 0.17%   |
| Realtek Semiconductor            | 8         | 0.17%   |
| LSI Logic / Symbios Logic        | 8         | 0.17%   |
| Union Memory (Shenzhen)          | 7         | 0.15%   |
| Hewlett-Packard                  | 5         | 0.11%   |
| O2 Micro                         | 4         | 0.09%   |
| Integrated Technology Express    | 3         | 0.06%   |
| Adaptec                          | 3         | 0.06%   |
| ULi Electronics                  | 2         | 0.04%   |
| Transcend                        | 2         | 0.04%   |
| Promise Technology               | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 373       | 6.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 299       | 5.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 171       | 3.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 167       | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 158       | 2.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 149       | 2.79%   |
| Samsung NVMe SSD Controller 980                                                | 126       | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 108       | 2.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 94        | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 86        | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 85        | 1.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 73        | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 72        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 72        | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 69        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 68        | 1.27%   |
| Intel SATA Controller [RAID mode]                                              | 66        | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 66        | 1.24%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 65        | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 64        | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 59        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 59        | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                            | 57        | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 57        | 1.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 57        | 1.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 56        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 55        | 1.03%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 53        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 53        | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                         | 53        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 52        | 0.97%   |
| Kingston Company A2000 NVMe SSD                                                | 50        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 50        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 50        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 47        | 0.88%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 46        | 0.86%   |
| Intel SSD 660P Series                                                          | 43        | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 43        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 43        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 42        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2488      | 53.13%  |
| NVMe | 1306      | 27.89%  |
| IDE  | 549       | 11.72%  |
| RAID | 325       | 6.94%   |
| SAS  | 8         | 0.17%   |
| SCSI | 7         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2904      | 78.49%  |
| AMD          | 744       | 20.11%  |
| ARM          | 49        | 1.32%   |
| CentaurHauls | 2         | 0.05%   |
| QUALCOMM     | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 57        | 1.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 44        | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 42        | 1.13%   |
| ARM Processor                                 | 39        | 1.05%   |
| AMD Ryzen 5 3600 6-Core Processor             | 38        | 1.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 35        | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 0.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 0.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 31        | 0.84%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 29        | 0.78%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 29        | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.73%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 26        | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 25        | 0.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 24        | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 0.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 21        | 0.57%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 21        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 20        | 0.54%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 20        | 0.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 20        | 0.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 19        | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.51%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 19        | 0.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 0.51%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 18        | 0.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 18        | 0.49%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 17        | 0.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 17        | 0.46%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 16        | 0.43%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 16        | 0.43%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 16        | 0.43%   |
| AMD Custom APU 0405                           | 16        | 0.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 807       | 21.78%  |
| Intel Core i7           | 749       | 20.22%  |
| Intel Core i3           | 282       | 7.61%   |
| Other                   | 232       | 6.26%   |
| AMD Ryzen 5             | 179       | 4.83%   |
| AMD Ryzen 7             | 171       | 4.62%   |
| Intel Core 2 Duo        | 165       | 4.45%   |
| Intel Celeron           | 126       | 3.4%    |
| Intel Pentium Silver    | 104       | 2.81%   |
| Intel Atom              | 88        | 2.38%   |
| Intel Pentium           | 84        | 2.27%   |
| Intel Xeon              | 78        | 2.11%   |
| Intel Pentium Dual-Core | 53        | 1.43%   |
| AMD Ryzen 9             | 49        | 1.32%   |
| Intel Core 2 Quad       | 42        | 1.13%   |
| AMD FX                  | 33        | 0.89%   |
| Intel Core i9           | 31        | 0.84%   |
| Intel Core 2            | 29        | 0.78%   |
| Intel Pentium Dual      | 25        | 0.67%   |
| AMD A6                  | 25        | 0.67%   |
| AMD Ryzen 7 PRO         | 23        | 0.62%   |
| Intel Genuine           | 22        | 0.59%   |
| AMD A8                  | 21        | 0.57%   |
| AMD Ryzen 5 PRO         | 19        | 0.51%   |
| AMD Athlon 64 X2        | 19        | 0.51%   |
| AMD Ryzen 3             | 16        | 0.43%   |
| AMD Phenom II X4        | 16        | 0.43%   |
| AMD A4                  | 16        | 0.43%   |
| AMD A10                 | 15        | 0.4%    |
| Intel Pentium 4         | 14        | 0.38%   |
| Intel Pentium D         | 13        | 0.35%   |
| AMD E                   | 13        | 0.35%   |
| AMD Athlon II X2        | 13        | 0.35%   |
| AMD E1                  | 10        | 0.27%   |
| ARM BCM                 | 9         | 0.24%   |
| AMD Athlon II X4        | 8         | 0.22%   |
| AMD Athlon              | 8         | 0.22%   |
| AMD Ryzen Threadripper  | 7         | 0.19%   |
| Intel Core m3           | 6         | 0.16%   |
| AMD E2                  | 6         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1477      | 39.84%  |
| 2       | 1379      | 37.2%   |
| 6       | 359       | 9.68%   |
| 8       | 263       | 7.09%   |
| 1       | 86        | 2.32%   |
| 12      | 60        | 1.62%   |
| 10      | 24        | 0.65%   |
| 16      | 20        | 0.54%   |
| 14      | 11        | 0.3%    |
| 3       | 10        | 0.27%   |
| Unknown | 7         | 0.19%   |
| 24      | 6         | 0.16%   |
| 64      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 32      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3664      | 99.03%  |
| 2       | 29        | 0.78%   |
| Unknown | 5         | 0.14%   |
| 4       | 1         | 0.03%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2368      | 63.93%  |
| 1       | 1328      | 35.85%  |
| Unknown | 7         | 0.19%   |
| 16      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3586      | 96.66%  |
| Unknown        | 91        | 2.45%   |
| 32-bit         | 30        | 0.81%   |
| 64-bit         | 3         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 928       | 24.22%  |
| 0x306a9    | 207       | 5.4%    |
| 0x206a7    | 193       | 5.04%   |
| 0x306c3    | 165       | 4.31%   |
| 0x1067a    | 138       | 3.6%    |
| 0x806ec    | 122       | 3.18%   |
| 0x906ea    | 108       | 2.82%   |
| 0x806ea    | 75        | 1.96%   |
| 0x806c1    | 74        | 1.93%   |
| 0x406e3    | 74        | 1.93%   |
| 0x506e3    | 72        | 1.88%   |
| 0x40651    | 70        | 1.83%   |
| 0x20655    | 65        | 1.7%    |
| 0x806e9    | 64        | 1.67%   |
| 0x906e9    | 60        | 1.57%   |
| 0x906c0    | 58        | 1.51%   |
| 0x6fd      | 58        | 1.51%   |
| 0x08701021 | 53        | 1.38%   |
| 0x306d4    | 46        | 1.2%    |
| 0x08600106 | 42        | 1.1%    |
| 0x706a8    | 40        | 1.04%   |
| 0x30678    | 40        | 1.04%   |
| 0x0a50000c | 37        | 0.97%   |
| 0x6fb      | 34        | 0.89%   |
| 0x010000c8 | 33        | 0.86%   |
| 0x806eb    | 31        | 0.81%   |
| 0x08701013 | 31        | 0.81%   |
| 0xa0652    | 28        | 0.73%   |
| 0x10676    | 28        | 0.73%   |
| 0x0800820d | 26        | 0.68%   |
| 0x706e5    | 25        | 0.65%   |
| 0x406c4    | 25        | 0.65%   |
| 0x906ed    | 24        | 0.63%   |
| 0x706a1    | 24        | 0.63%   |
| 0x20652    | 24        | 0.63%   |
| 0x106e5    | 24        | 0.63%   |
| 0x08108109 | 24        | 0.63%   |
| 0x08108102 | 23        | 0.6%    |
| 0x506c9    | 22        | 0.57%   |
| 0x06001119 | 22        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 648       | 17.49%  |
| Haswell          | 324       | 8.74%   |
| IvyBridge        | 265       | 7.15%   |
| SandyBridge      | 252       | 6.8%    |
| Penryn           | 203       | 5.48%   |
| Skylake          | 202       | 5.45%   |
| Zen 2            | 186       | 5.02%   |
| Core             | 147       | 3.97%   |
| Unknown          | 134       | 3.62%   |
| Westmere         | 126       | 3.4%    |
| Silvermont       | 123       | 3.32%   |
| Zen 3            | 106       | 2.86%   |
| Zen+             | 98        | 2.65%   |
| TigerLake        | 92        | 2.48%   |
| Broadwell        | 73        | 1.97%   |
| Goldmont plus    | 67        | 1.81%   |
| CometLake        | 66        | 1.78%   |
| K10              | 56        | 1.51%   |
| Piledriver       | 54        | 1.46%   |
| Nehalem          | 54        | 1.46%   |
| Tremont          | 52        | 1.4%    |
| Zen              | 50        | 1.35%   |
| IceLake          | 47        | 1.27%   |
| Alderlake Hybrid | 36        | 0.97%   |
| K8 Hammer        | 35        | 0.94%   |
| NetBurst         | 31        | 0.84%   |
| Goldmont         | 28        | 0.76%   |
| Excavator        | 22        | 0.59%   |
| Bobcat           | 21        | 0.57%   |
| Bonnell          | 20        | 0.54%   |
| K10 Llano        | 17        | 0.46%   |
| P6               | 16        | 0.43%   |
| Jaguar           | 16        | 0.43%   |
| Steamroller      | 12        | 0.32%   |
| Puma             | 10        | 0.27%   |
| K8 & K10 hybrid  | 8         | 0.22%   |
| Bulldozer        | 7         | 0.19%   |
| CannonLake       | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2180      | 50.7%   |
| Nvidia                           | 1195      | 27.79%  |
| AMD                              | 886       | 20.6%   |
| Matrox Electronics Systems       | 15        | 0.35%   |
| ASPEED Technology                | 9         | 0.21%   |
| VIA Technologies                 | 7         | 0.16%   |
| Silicon Integrated Systems [SiS] | 7         | 0.16%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 185       | 4.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 154       | 3.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 117       | 2.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 109       | 2.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 84        | 1.9%    |
| Intel UHD Graphics 620                                                                   | 82        | 1.86%   |
| AMD Renoir                                                                               | 78        | 1.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 76        | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 69        | 1.56%   |
| Intel HD Graphics 620                                                                    | 69        | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 67        | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 63        | 1.43%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 63        | 1.43%   |
| Intel JasperLake [UHD Graphics]                                                          | 61        | 1.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 61        | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 61        | 1.38%   |
| Intel HD Graphics 630                                                                    | 60        | 1.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 59        | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 58        | 1.31%   |
| Intel HD Graphics 530                                                                    | 56        | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 51        | 1.16%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 47        | 1.07%   |
| Intel HD Graphics 5500                                                                   | 44        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 40        | 0.91%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 40        | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 34        | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 33        | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 33        | 0.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 31        | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 30        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 30        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 30        | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 27        | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 26        | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 25        | 0.57%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 24        | 0.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 23        | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 22        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1593      | 42.72%  |
| 1 x AMD                  | 731       | 19.6%   |
| 1 x Nvidia               | 679       | 18.21%  |
| Intel + Nvidia           | 462       | 12.39%  |
| Intel + AMD              | 72        | 1.93%   |
| Other                    | 55        | 1.47%   |
| 2 x AMD                  | 41        | 1.1%    |
| AMD + Nvidia             | 41        | 1.1%    |
| 1 x Matrox               | 12        | 0.32%   |
| 2 x Nvidia               | 9         | 0.24%   |
| 1 x VIA                  | 7         | 0.19%   |
| 1 x SiS                  | 7         | 0.19%   |
| 2 x Intel                | 6         | 0.16%   |
| Nvidia + ASPEED          | 4         | 0.11%   |
| 1 x ASPEED               | 4         | 0.11%   |
| Nvidia + Matrox          | 2         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.05%   |
| AMD + Matrox             | 1         | 0.03%   |
| AMD + ASPEED             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2951      | 78.36%  |
| Proprietary | 636       | 16.89%  |
| Unknown     | 179       | 4.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2201      | 57.8%   |
| 1.01-2.0   | 410       | 10.77%  |
| 0.01-0.5   | 378       | 9.93%   |
| 0.51-1.0   | 278       | 7.3%    |
| 3.01-4.0   | 247       | 6.49%   |
| 7.01-8.0   | 161       | 4.23%   |
| 5.01-6.0   | 76        | 2%      |
| 8.01-16.0  | 30        | 0.79%   |
| 2.01-3.0   | 25        | 0.66%   |
| 16.01-24.0 | 2         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 532       | 13.13%  |
| Samsung Electronics     | 509       | 12.56%  |
| LG Display              | 337       | 8.32%   |
| BOE                     | 311       | 7.68%   |
| Chimei Innolux          | 268       | 6.61%   |
| Dell                    | 227       | 5.6%    |
| Philips                 | 180       | 4.44%   |
| Iiyama                  | 176       | 4.34%   |
| Goldstar                | 173       | 4.27%   |
| Hewlett-Packard         | 140       | 3.46%   |
| Acer                    | 129       | 3.18%   |
| Apple                   | 101       | 2.49%   |
| Sharp                   | 92        | 2.27%   |
| AOC                     | 83        | 2.05%   |
| BenQ                    | 82        | 2.02%   |
| Chi Mei Optoelectronics | 58        | 1.43%   |
| Ancor Communications    | 53        | 1.31%   |
| Lenovo                  | 46        | 1.14%   |
| LG Philips              | 34        | 0.84%   |
| Sony                    | 31        | 0.77%   |
| Medion                  | 31        | 0.77%   |
| Idek Iiyama             | 29        | 0.72%   |
| InfoVision              | 26        | 0.64%   |
| LG Electronics          | 22        | 0.54%   |
| Eizo                    | 19        | 0.47%   |
| CSO                     | 17        | 0.42%   |
| PANDA                   | 16        | 0.39%   |
| ASUSTek Computer        | 16        | 0.39%   |
| Unknown                 | 15        | 0.37%   |
| MSI                     | 15        | 0.37%   |
| Panasonic               | 14        | 0.35%   |
| Valve                   | 12        | 0.3%    |
| Fujitsu Siemens         | 12        | 0.3%    |
| ViewSonic               | 11        | 0.27%   |
| Packard Bell            | 11        | 0.27%   |
| NEC Computers           | 11        | 0.27%   |
| Vestel Elektronik       | 10        | 0.25%   |
| Toshiba                 | 9         | 0.22%   |
| HannStar                | 9         | 0.22%   |
| Gigabyte Technology     | 9         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                      | 33        | 0.78%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 25        | 0.59%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 22        | 0.52%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 18        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 17        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 16        | 0.38%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch     | 15        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 15        | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 15        | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 14        | 0.33%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                      | 13        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch             | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 12        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 11        | 0.26%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 10        | 0.24%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 9         | 0.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 9         | 0.21%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 9         | 0.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.21%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 9         | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 8         | 0.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 8         | 0.19%   |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.19%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch          | 8         | 0.19%   |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                      | 8         | 0.19%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                     | 8         | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 7         | 0.17%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 7         | 0.17%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 7         | 0.17%   |
| Iiyama PLT1931 IVM483F 1280x1024 376x301mm 19.0-inch                      | 7         | 0.17%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                      | 7         | 0.17%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 7         | 0.17%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 7         | 0.17%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 7         | 0.17%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 7         | 0.17%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1644      | 41.98%  |
| 1366x768 (WXGA)    | 550       | 14.04%  |
| 3840x2160 (4K)     | 253       | 6.46%   |
| 2560x1440 (QHD)    | 223       | 5.69%   |
| 1600x900 (HD+)     | 171       | 4.37%   |
| 1680x1050 (WSXGA+) | 142       | 3.63%   |
| 1280x1024 (SXGA)   | 141       | 3.6%    |
| 1280x800 (WXGA)    | 111       | 2.83%   |
| 1920x1200 (WUXGA)  | 104       | 2.66%   |
| 1440x900 (WXGA+)   | 97        | 2.48%   |
| 3440x1440          | 61        | 1.56%   |
| Unknown            | 56        | 1.43%   |
| 2560x1080          | 43        | 1.1%    |
| 2560x1600          | 36        | 0.92%   |
| 1360x768           | 31        | 0.79%   |
| 2880x1800          | 27        | 0.69%   |
| 3840x2400          | 26        | 0.66%   |
| 3840x1080          | 19        | 0.49%   |
| 1024x768 (XGA)     | 18        | 0.46%   |
| 1920x540           | 13        | 0.33%   |
| 800x1280           | 12        | 0.31%   |
| 2736x1824          | 9         | 0.23%   |
| 1280x720 (HD)      | 9         | 0.23%   |
| 1600x1200          | 8         | 0.2%    |
| 2160x1440          | 7         | 0.18%   |
| 3200x1800 (QHD+)   | 6         | 0.15%   |
| 3840x1600          | 5         | 0.13%   |
| 3840x1200          | 5         | 0.13%   |
| 3600x1080          | 5         | 0.13%   |
| 3000x2000          | 5         | 0.13%   |
| 2048x1152          | 5         | 0.13%   |
| 1400x1050          | 5         | 0.13%   |
| 7680x2160          | 4         | 0.1%    |
| 5760x1080          | 4         | 0.1%    |
| 3456x2160          | 4         | 0.1%    |
| 2256x1504          | 4         | 0.1%    |
| 1280x960           | 4         | 0.1%    |
| 1024x600           | 4         | 0.1%    |
| 3072x1920          | 3         | 0.08%   |
| 1680x945           | 3         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 893       | 22.03%  |
| 13      | 354       | 8.73%   |
| 17      | 321       | 7.92%   |
| 24      | 291       | 7.18%   |
| 27      | 281       | 6.93%   |
| 23      | 251       | 6.19%   |
| 14      | 244       | 6.02%   |
| Unknown | 241       | 5.94%   |
| 21      | 192       | 4.74%   |
| 11      | 141       | 3.48%   |
| 19      | 110       | 2.71%   |
| 22      | 90        | 2.22%   |
| 12      | 87        | 2.15%   |
| 34      | 81        | 2%      |
| 31      | 67        | 1.65%   |
| 20      | 55        | 1.36%   |
| 18      | 41        | 1.01%   |
| 25      | 33        | 0.81%   |
| 84      | 32        | 0.79%   |
| 16      | 26        | 0.64%   |
| 40      | 24        | 0.59%   |
| 72      | 22        | 0.54%   |
| 65      | 14        | 0.35%   |
| 54      | 14        | 0.35%   |
| 10      | 14        | 0.35%   |
| 28      | 11        | 0.27%   |
| 32      | 10        | 0.25%   |
| 26      | 10        | 0.25%   |
| 33      | 9         | 0.22%   |
| 7       | 9         | 0.22%   |
| 29      | 8         | 0.2%    |
| 37      | 7         | 0.17%   |
| 35      | 7         | 0.17%   |
| 46      | 6         | 0.15%   |
| 36      | 6         | 0.15%   |
| 58      | 5         | 0.12%   |
| 43      | 5         | 0.12%   |
| 42      | 5         | 0.12%   |
| 57      | 4         | 0.1%    |
| 52      | 4         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1311      | 32.91%  |
| 501-600        | 787       | 19.76%  |
| 201-300        | 477       | 11.98%  |
| 401-500        | 403       | 10.12%  |
| 351-400        | 363       | 9.11%   |
| Unknown        | 241       | 6.05%   |
| 601-700        | 112       | 2.81%   |
| 701-800        | 102       | 2.56%   |
| 1001-1500      | 61        | 1.53%   |
| 1501-2000      | 56        | 1.41%   |
| 801-900        | 45        | 1.13%   |
| 901-1000       | 13        | 0.33%   |
| 1-100          | 9         | 0.23%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2587      | 70.32%  |
| 16/10   | 544       | 14.79%  |
| Unknown | 198       | 5.38%   |
| 5/4     | 133       | 3.62%   |
| 21/9    | 101       | 2.75%   |
| 3/2     | 43        | 1.17%   |
| 4/3     | 41        | 1.11%   |
| 0.67    | 9         | 0.24%   |
| 6/5     | 6         | 0.16%   |
| 32/9    | 6         | 0.16%   |
| 0.62    | 5         | 0.14%   |
| 3.40    | 1         | 0.03%   |
| 3.33    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |
| 0.80    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |
| 0.45    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 886       | 22.03%  |
| 201-250        | 645       | 16.04%  |
| 81-90          | 402       | 10%     |
| 301-350        | 290       | 7.21%   |
| Unknown        | 241       | 5.99%   |
| 151-200        | 230       | 5.72%   |
| 121-130        | 209       | 5.2%    |
| 71-80          | 203       | 5.05%   |
| 351-500        | 192       | 4.77%   |
| 51-60          | 143       | 3.56%   |
| 251-300        | 139       | 3.46%   |
| More than 1000 | 105       | 2.61%   |
| 141-150        | 92        | 2.29%   |
| 61-70          | 74        | 1.84%   |
| 501-1000       | 66        | 1.64%   |
| 131-140        | 44        | 1.09%   |
| 111-120        | 30        | 0.75%   |
| 41-50          | 13        | 0.32%   |
| 1-40           | 11        | 0.27%   |
| 91-100         | 6         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1242      | 31.68%  |
| 121-160       | 1098      | 28.01%  |
| 101-120       | 850       | 21.68%  |
| 161-240       | 256       | 6.53%   |
| Unknown       | 241       | 6.15%   |
| More than 240 | 142       | 3.62%   |
| 1-50          | 91        | 2.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2934      | 77.31%  |
| 2     | 609       | 16.05%  |
| 0     | 183       | 4.82%   |
| 3     | 64        | 1.69%   |
| 4     | 4         | 0.11%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1962      | 36.12%  |
| Realtek Semiconductor                 | 1778      | 32.73%  |
| Qualcomm Atheros                      | 529       | 9.74%   |
| Broadcom                              | 342       | 6.3%    |
| Broadcom Limited                      | 81        | 1.49%   |
| Marvell Technology Group              | 72        | 1.33%   |
| TP-Link                               | 71        | 1.31%   |
| Ralink Technology                     | 65        | 1.2%    |
| Ralink                                | 57        | 1.05%   |
| Nvidia                                | 45        | 0.83%   |
| MediaTek                              | 45        | 0.83%   |
| ASIX Electronics                      | 34        | 0.63%   |
| Dell                                  | 28        | 0.52%   |
| DisplayLink                           | 26        | 0.48%   |
| Hewlett-Packard                       | 24        | 0.44%   |
| Sitecom Europe                        | 15        | 0.28%   |
| Microsoft                             | 15        | 0.28%   |
| Huawei Technologies                   | 13        | 0.24%   |
| NetGear                               | 12        | 0.22%   |
| JMicron Technology                    | 12        | 0.22%   |
| Ericsson Business Mobile Networks     | 12        | 0.22%   |
| Sierra Wireless                       | 11        | 0.2%    |
| Samsung Electronics                   | 11        | 0.2%    |
| IMC Networks                          | 11        | 0.2%    |
| ASUSTek Computer                      | 11        | 0.2%    |
| Silicon Integrated Systems [SiS]      | 9         | 0.17%   |
| Qualcomm                              | 8         | 0.15%   |
| Lenovo                                | 8         | 0.15%   |
| VIA Technologies                      | 6         | 0.11%   |
| Gemtek                                | 6         | 0.11%   |
| D-Link                                | 6         | 0.11%   |
| Aquantia                              | 6         | 0.11%   |
| Mellanox Technologies                 | 5         | 0.09%   |
| Xiaomi                                | 4         | 0.07%   |
| U-Blox                                | 4         | 0.07%   |
| Microchip Technology                  | 4         | 0.07%   |
| Fibocom                               | 4         | 0.07%   |
| Edimax Technology                     | 4         | 0.07%   |
| Belkin Components                     | 4         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1281      | 20.2%   |
| Intel Wi-Fi 6 AX200                                               | 201       | 3.17%   |
| Intel Wireless 8265 / 8275                                        | 154       | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 154       | 2.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 150       | 2.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 130       | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 113       | 1.78%   |
| Intel Wireless 7265                                               | 89        | 1.4%    |
| Intel I211 Gigabit Network Connection                             | 87        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 74        | 1.17%   |
| Intel Wi-Fi 6 AX201                                               | 73        | 1.15%   |
| Intel Wireless 7260                                               | 71        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 63        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 60        | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 59        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58        | 0.91%   |
| Intel Wireless 8260                                               | 58        | 0.91%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 58        | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 54        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 50        | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 48        | 0.76%   |
| Intel Wireless 3165                                               | 46        | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 45        | 0.71%   |
| Intel Wireless-AC 9260                                            | 43        | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 42        | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 42        | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 42        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 42        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 41        | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 38        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 36        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                    | 36        | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 35        | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 34        | 0.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 32        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 31        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.49%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 31        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1504      | 52.19%  |
| Qualcomm Atheros                      | 419       | 14.54%  |
| Realtek Semiconductor                 | 333       | 11.55%  |
| Broadcom                              | 212       | 7.36%   |
| Ralink Technology                     | 65        | 2.26%   |
| TP-Link                               | 62        | 2.15%   |
| Ralink                                | 57        | 1.98%   |
| MediaTek                              | 43        | 1.49%   |
| Broadcom Limited                      | 41        | 1.42%   |
| Sitecom Europe                        | 15        | 0.52%   |
| Microsoft                             | 13        | 0.45%   |
| Marvell Technology Group              | 13        | 0.45%   |
| NetGear                               | 12        | 0.42%   |
| IMC Networks                          | 11        | 0.38%   |
| Dell                                  | 11        | 0.38%   |
| ASUSTek Computer                      | 11        | 0.38%   |
| Sierra Wireless                       | 7         | 0.24%   |
| Gemtek                                | 6         | 0.21%   |
| D-Link                                | 6         | 0.21%   |
| Qualcomm                              | 5         | 0.17%   |
| Hewlett-Packard                       | 4         | 0.14%   |
| Fibocom                               | 4         | 0.14%   |
| Edimax Technology                     | 4         | 0.14%   |
| Belkin Components                     | 4         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.14%   |
| Qualcomm Atheros Communications       | 3         | 0.1%    |
| Linksys                               | 3         | 0.1%    |
| Senao                                 | 2         | 0.07%   |
| Sagem                                 | 2         | 0.07%   |
| Wilocity                              | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| CyberTAN Technology                   | 1         | 0.03%   |
| Cinterion                             | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 201       | 6.95%   |
| Intel Wireless 8265 / 8275                                              | 154       | 5.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 113       | 3.9%    |
| Intel Wireless 7265                                                     | 89        | 3.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 74        | 2.56%   |
| Intel Wi-Fi 6 AX201                                                     | 73        | 2.52%   |
| Intel Wireless 7260                                                     | 71        | 2.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 60        | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 59        | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 58        | 2%      |
| Intel Wireless 8260                                                     | 58        | 2%      |
| Intel Wi-Fi 6 AX201 160MHz                                              | 58        | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 54        | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 50        | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 48        | 1.66%   |
| Intel Wireless 3165                                                     | 46        | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 45        | 1.55%   |
| Intel Wireless-AC 9260                                                  | 43        | 1.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 42        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 42        | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 42        | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 1.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 36        | 1.24%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 35        | 1.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 32        | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 31        | 1.07%   |
| Intel Wireless 3160                                                     | 30        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 30        | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 29        | 1%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 29        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                          | 29        | 1%      |
| Intel Centrino Advanced-N 6200                                          | 27        | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 0.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 23        | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 22        | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 22        | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 21        | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 20        | 0.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 19        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1643      | 50.11%  |
| Intel                                  | 957       | 29.19%  |
| Broadcom                               | 181       | 5.52%   |
| Qualcomm Atheros                       | 173       | 5.28%   |
| Marvell Technology Group               | 59        | 1.8%    |
| Nvidia                                 | 44        | 1.34%   |
| Broadcom Limited                       | 40        | 1.22%   |
| ASIX Electronics                       | 34        | 1.04%   |
| DisplayLink                            | 26        | 0.79%   |
| JMicron Technology                     | 12        | 0.37%   |
| TP-Link                                | 9         | 0.27%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.27%   |
| Huawei Technologies                    | 9         | 0.27%   |
| Lenovo                                 | 8         | 0.24%   |
| Samsung Electronics                    | 7         | 0.21%   |
| VIA Technologies                       | 6         | 0.18%   |
| Hewlett-Packard                        | 6         | 0.18%   |
| Aquantia                               | 6         | 0.18%   |
| Xiaomi                                 | 4         | 0.12%   |
| Sierra Wireless                        | 4         | 0.12%   |
| Mellanox Technologies                  | 4         | 0.12%   |
| Standard Microsystems                  | 3         | 0.09%   |
| Qualcomm                               | 3         | 0.09%   |
| 3Com                                   | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.06%   |
| ULi Electronics                        | 2         | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| MosChip Semiconductor                  | 2         | 0.06%   |
| Microsoft                              | 2         | 0.06%   |
| Microchip Technology                   | 2         | 0.06%   |
| ICS Advent                             | 2         | 0.06%   |
| Accton Technology                      | 2         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| MediaTek                               | 1         | 0.03%   |
| Jolla Oy                               | 1         | 0.03%   |
| Google                                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1281      | 38.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 154       | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 150       | 4.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 130       | 3.87%   |
| Intel I211 Gigabit Network Connection                             | 87        | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64        | 1.9%    |
| Intel Ethernet Connection (2) I219-V                              | 63        | 1.87%   |
| Intel Ethernet Connection I217-LM                                 | 42        | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 41        | 1.22%   |
| Intel Ethernet Connection (6) I219-V                              | 34        | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 31        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.92%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 29        | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 29        | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 28        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 27        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 26        | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 25        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 22        | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 17        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 16        | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 16        | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 15        | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 14        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 13        | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3093      | 52.31%  |
| WiFi     | 2737      | 46.29%  |
| Modem    | 75        | 1.27%   |
| Unknown  | 8         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2087      | 53.86%  |
| Ethernet | 1787      | 46.12%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1925      | 51.87%  |
| 1     | 1584      | 42.68%  |
| 0     | 104       | 2.8%    |
| 3     | 70        | 1.89%   |
| 4     | 17        | 0.46%   |
| 5     | 4         | 0.11%   |
| 7     | 3         | 0.08%   |
| 6     | 3         | 0.08%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3025      | 79.84%  |
| Yes  | 764       | 20.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1203      | 53.37%  |
| Cambridge Silicon Radio         | 185       | 8.21%   |
| Realtek Semiconductor           | 145       | 6.43%   |
| Qualcomm Atheros Communications | 122       | 5.41%   |
| Apple                           | 101       | 4.48%   |
| Broadcom                        | 99        | 4.39%   |
| IMC Networks                    | 79        | 3.5%    |
| Lite-On Technology              | 63        | 2.8%    |
| Foxconn / Hon Hai               | 56        | 2.48%   |
| Hewlett-Packard                 | 42        | 1.86%   |
| ASUSTek Computer                | 39        | 1.73%   |
| Dell                            | 37        | 1.64%   |
| Toshiba                         | 19        | 0.84%   |
| Marvell Semiconductor           | 13        | 0.58%   |
| MediaTek                        | 11        | 0.49%   |
| Ralink                          | 10        | 0.44%   |
| TP-Link                         | 5         | 0.22%   |
| Realtek                         | 5         | 0.22%   |
| Alps Electric                   | 4         | 0.18%   |
| Ralink Technology               | 3         | 0.13%   |
| Sitecom Europe                  | 2         | 0.09%   |
| Micro Star International        | 2         | 0.09%   |
| Integrated System Solution      | 2         | 0.09%   |
| Foxconn International           | 2         | 0.09%   |
| USI                             | 1         | 0.04%   |
| Roper                           | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 427       | 18.93%  |
| Intel AX201 Bluetooth                               | 221       | 9.8%    |
| Intel AX200 Bluetooth                               | 193       | 8.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 185       | 8.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 179       | 7.93%   |
| Realtek Bluetooth Radio                             | 84        | 3.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 69        | 3.06%   |
| Apple Bluetooth Host Controller                     | 44        | 1.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 43        | 1.91%   |
| Intel Wireless-AC 3168 Bluetooth                    | 42        | 1.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 41        | 1.82%   |
| IMC Networks Bluetooth Radio                        | 32        | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 30        | 1.33%   |
| Lite-On Bluetooth Device                            | 29        | 1.29%   |
| Intel Bluetooth Device                              | 29        | 1.29%   |
| Intel AX210 Bluetooth                               | 28        | 1.24%   |
| Apple Bluetooth USB Host Controller                 | 26        | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                  | 24        | 1.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 0.98%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.93%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.93%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 20        | 0.89%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.84%   |
| IMC Networks Bluetooth Device                       | 18        | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                   | 15        | 0.66%   |
| Broadcom HP Portable SoftSailing                    | 15        | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.62%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 14        | 0.62%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.58%   |
| IMC Networks Wireless_Device                        | 12        | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.53%   |
| Marvell Bluetooth and Wireless LAN Composite        | 11        | 0.49%   |
| Apple Bluetooth HCI                                 | 11        | 0.49%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.44%   |
| MediaTek Wireless_Device                            | 10        | 0.44%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2719      | 53.64%  |
| AMD                              | 948       | 18.7%   |
| Nvidia                           | 850       | 16.77%  |
| C-Media Electronics              | 76        | 1.5%    |
| Logitech                         | 43        | 0.85%   |
| Realtek Semiconductor            | 36        | 0.71%   |
| Creative Labs                    | 32        | 0.63%   |
| GN Netcom                        | 26        | 0.51%   |
| Texas Instruments                | 24        | 0.47%   |
| Focusrite-Novation               | 18        | 0.36%   |
| Creative Technology              | 15        | 0.3%    |
| Silicon Integrated Systems [SiS] | 12        | 0.24%   |
| Plantronics                      | 12        | 0.24%   |
| BEHRINGER International          | 12        | 0.24%   |
| SteelSeries ApS                  | 11        | 0.22%   |
| JMTek                            | 11        | 0.22%   |
| VIA Technologies                 | 10        | 0.2%    |
| Kingston Technology              | 10        | 0.2%    |
| Corsair                          | 10        | 0.2%    |
| Hewlett-Packard                  | 9         | 0.18%   |
| Apple                            | 9         | 0.18%   |
| ASUSTek Computer                 | 8         | 0.16%   |
| Sony                             | 7         | 0.14%   |
| GYROCOM C&C                      | 7         | 0.14%   |
| Sennheiser Communications        | 6         | 0.12%   |
| RODE Microphones                 | 6         | 0.12%   |
| Razer USA                        | 6         | 0.12%   |
| Lenovo                           | 6         | 0.12%   |
| Generalplus Technology           | 6         | 0.12%   |
| Yamaha                           | 5         | 0.1%    |
| Cambridge Silicon Radio          | 5         | 0.1%    |
| XMOS                             | 4         | 0.08%   |
| SAVITECH                         | 4         | 0.08%   |
| Samson Technologies              | 4         | 0.08%   |
| Native Instruments               | 4         | 0.08%   |
| Valve Software                   | 3         | 0.06%   |
| Tenx Technology                  | 3         | 0.06%   |
| No brand                         | 3         | 0.06%   |
| Micro Star International         | 3         | 0.06%   |
| M-Audio                          | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 263       | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 263       | 4.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 247       | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 228       | 3.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 191       | 3.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 157       | 2.66%   |
| AMD Starship/Matisse HD Audio Controller                                   | 145       | 2.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 139       | 2.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 137       | 2.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 136       | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 132       | 2.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 120       | 2.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 110       | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 102       | 1.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 96        | 1.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 92        | 1.56%   |
| AMD FCH Azalia Controller                                                  | 86        | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                            | 81        | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 78        | 1.32%   |
| Intel 8 Series HD Audio Controller                                         | 78        | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 73        | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 69        | 1.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 68        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 67        | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 67        | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 66        | 1.12%   |
| Nvidia High Definition Audio Controller                                    | 64        | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 64        | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 64        | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 63        | 1.07%   |
| Intel Jasper Lake HD Audio                                                 | 61        | 1.03%   |
| Intel 200 Series PCH HD Audio                                              | 61        | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 53        | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 53        | 0.9%    |
| Intel CM238 HD Audio Controller                                            | 51        | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 51        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 50        | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                              | 47        | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                              | 46        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 44        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 464       | 22.21%  |
| Samsung Electronics | 407       | 19.48%  |
| Kingston            | 229       | 10.96%  |
| Micron Technology   | 220       | 10.53%  |
| Corsair             | 172       | 8.23%   |
| Unknown             | 163       | 7.8%    |
| Crucial             | 139       | 6.65%   |
| G.Skill             | 62        | 2.97%   |
| A-DATA Technology   | 32        | 1.53%   |
| Ramaxel Technology  | 31        | 1.48%   |
| Nanya Technology    | 31        | 1.48%   |
| Elpida              | 20        | 0.96%   |
| Unknown             | 14        | 0.67%   |
| Transcend           | 11        | 0.53%   |
| Unknown (ABCD)      | 8         | 0.38%   |
| GOODRAM             | 8         | 0.38%   |
| Team                | 7         | 0.34%   |
| Qimonda             | 6         | 0.29%   |
| ASint Technology    | 5         | 0.24%   |
| Patriot             | 4         | 0.19%   |
| 48spaces            | 4         | 0.19%   |
| Wilk                | 3         | 0.14%   |
| GeIL                | 3         | 0.14%   |
| Axiom               | 3         | 0.14%   |
| Toshiba             | 2         | 0.1%    |
| TakeMS              | 2         | 0.1%    |
| Goldkey             | 2         | 0.1%    |
| Atermiter           | 2         | 0.1%    |
| AMD                 | 2         | 0.1%    |
| A-DA                | 2         | 0.1%    |
| A Force             | 2         | 0.1%    |
| ZIFEI               | 1         | 0.05%   |
| zApacer             | 1         | 0.05%   |
| Unknown (AD8A)      | 1         | 0.05%   |
| Unknown (0x873E)    | 1         | 0.05%   |
| Unknown (08C8)      | 1         | 0.05%   |
| Timetec             | 1         | 0.05%   |
| tigo                | 1         | 0.05%   |
| Smart               | 1         | 0.05%   |
| SHARETRONIC         | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 43        | 1.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 30        | 1.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 24        | 1.08%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s             | 19        | 0.86%   |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 17        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.77%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.63%   |
| Unknown                                                          | 14        | 0.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 13        | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 0.54%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 12        | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.5%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 9         | 0.41%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 9         | 0.41%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 8         | 0.36%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 8         | 0.36%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.36%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.36%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.36%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.36%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 8         | 0.36%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 7         | 0.32%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 7         | 0.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.32%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 7         | 0.32%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.32%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 7         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 890       | 48.32%  |
| DDR3    | 567       | 30.78%  |
| LPDDR4  | 117       | 6.35%   |
| DDR2    | 77        | 4.18%   |
| LPDDR3  | 63        | 3.42%   |
| SDRAM   | 52        | 2.82%   |
| Unknown | 29        | 1.57%   |
| DDR5    | 19        | 1.03%   |
| LPDDR5  | 12        | 0.65%   |
| DDR     | 12        | 0.65%   |
| DRAM    | 3         | 0.16%   |
| EEPROM  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1064      | 57.83%  |
| DIMM         | 558       | 30.33%  |
| Row Of Chips | 197       | 10.71%  |
| Chip         | 9         | 0.49%   |
| Unknown      | 9         | 0.49%   |
| RIMM         | 1         | 0.05%   |
| FB-DIMM      | 1         | 0.05%   |
| DIP          | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 775       | 38.96%  |
| 4096  | 517       | 25.99%  |
| 16384 | 301       | 15.13%  |
| 2048  | 254       | 12.77%  |
| 1024  | 74        | 3.72%   |
| 32768 | 55        | 2.77%   |
| 512   | 10        | 0.5%    |
| 256   | 1         | 0.05%   |
| 64    | 1         | 0.05%   |
| 1     | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 341       | 17.39%  |
| 2667    | 292       | 14.89%  |
| 3200    | 290       | 14.79%  |
| 2400    | 151       | 7.7%    |
| 1333    | 131       | 6.68%   |
| 2133    | 105       | 5.35%   |
| 4267    | 87        | 4.44%   |
| 1334    | 59        | 3.01%   |
| 3600    | 56        | 2.86%   |
| 1867    | 50        | 2.55%   |
| 800     | 46        | 2.35%   |
| 667     | 42        | 2.14%   |
| Unknown | 31        | 1.58%   |
| 1066    | 22        | 1.12%   |
| 3466    | 15        | 0.76%   |
| 4800    | 14        | 0.71%   |
| 3400    | 14        | 0.71%   |
| 2933    | 14        | 0.71%   |
| 3266    | 13        | 0.66%   |
| 1067    | 13        | 0.66%   |
| 6400    | 12        | 0.61%   |
| 1866    | 12        | 0.61%   |
| 8400    | 11        | 0.56%   |
| 3000    | 11        | 0.56%   |
| 2048    | 10        | 0.51%   |
| 3866    | 9         | 0.46%   |
| 4199    | 8         | 0.41%   |
| 3800    | 8         | 0.41%   |
| 400     | 8         | 0.41%   |
| 4266    | 7         | 0.36%   |
| 1639    | 7         | 0.36%   |
| 3733    | 6         | 0.31%   |
| 2666    | 6         | 0.31%   |
| 533     | 6         | 0.31%   |
| 6000    | 5         | 0.25%   |
| 2800    | 5         | 0.25%   |
| 1800    | 4         | 0.2%    |
| 49926   | 3         | 0.15%   |
| 3333    | 3         | 0.15%   |
| 333     | 3         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 25        | 29.41%  |
| Brother Industries  | 17        | 20%     |
| Canon               | 15        | 17.65%  |
| Samsung Electronics | 9         | 10.59%  |
| Dymo-CoStar         | 7         | 8.24%   |
| Seiko Epson         | 5         | 5.88%   |
| Citizen             | 4         | 4.71%   |
| Zebra               | 1         | 1.18%   |
| STMicroelectronics  | 1         | 1.18%   |
| Prolific Technology | 1         | 1.18%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer                        | 4         | 4.71%   |
| Dymo-CoStar LabelWriter 450                               | 4         | 4.71%   |
| Citizen Thermal Receipt Printer [CT-E351]                 | 4         | 4.71%   |
| HP Deskjet 2540 series                                    | 3         | 3.53%   |
| Samsung SCX-4600 Series                                   | 2         | 2.35%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 2.35%   |
| HP ENVY 5000 series                                       | 2         | 2.35%   |
| Canon TS3100 series                                       | 2         | 2.35%   |
| Canon PIXMA MX920 Series                                  | 2         | 2.35%   |
| Canon PIXMA MG2500 Series                                 | 2         | 2.35%   |
| Canon MG5600 series                                       | 2         | 2.35%   |
| Brother Printer                                           | 2         | 2.35%   |
| Brother HL-2030 Laser Printer                             | 2         | 2.35%   |
| Zebra Printer                                             | 1         | 1.18%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.18%   |
| Seiko Epson XP-200 Series                                 | 1         | 1.18%   |
| Seiko Epson Thermal Receipt Printer [TM-T20]              | 1         | 1.18%   |
| Seiko Epson Printer                                       | 1         | 1.18%   |
| Seiko Epson ET-2820 Series                                | 1         | 1.18%   |
| Seiko Epson ET-2720 Series                                | 1         | 1.18%   |
| Samsung SCX-4300 Series                                   | 1         | 1.18%   |
| Samsung ML-2240 Series                                    | 1         | 1.18%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.18%   |
| Samsung C48x Series                                       | 1         | 1.18%   |
| Samsung C43x Series                                       | 1         | 1.18%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.18%   |
| HP Printing Support                                       | 1         | 1.18%   |
| HP OfficeJet Pro 8020 series                              | 1         | 1.18%   |
| HP OfficeJet 6950                                         | 1         | 1.18%   |
| HP OfficeJet 3830 series                                  | 1         | 1.18%   |
| HP LaserJet Professional P1102w                           | 1         | 1.18%   |
| HP LaserJet P1005                                         | 1         | 1.18%   |
| HP LaserJet 1320                                          | 1         | 1.18%   |
| HP Laser 107w                                             | 1         | 1.18%   |
| HP DeskJet F2100 Printer series                           | 1         | 1.18%   |
| HP Deskjet D1500 series                                   | 1         | 1.18%   |
| HP DeskJet 916C                                           | 1         | 1.18%   |
| HP DeskJet 6940 series                                    | 1         | 1.18%   |
| HP DeskJet 3630 series                                    | 1         | 1.18%   |
| HP DeskJet 2700 series                                    | 1         | 1.18%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 23        | 63.89%  |
| Seiko Epson     | 7         | 19.44%  |
| Mustek Systems  | 3         | 8.33%   |
| Hewlett-Packard | 2         | 5.56%   |
| Plustek         | 1         | 2.78%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                       | 4         | 10.81%  |
| Canon CanoScan LiDE 210                       | 4         | 10.81%  |
| Mustek Systems ScanExpress 1200 UB            | 3         | 8.11%   |
| Seiko Epson Scanner                           | 2         | 5.41%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 2         | 5.41%   |
| Seiko Epson GT-X770 [Perfection V500]         | 2         | 5.41%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 5.41%   |
| Canon CanoScan N650U/N656U                    | 2         | 5.41%   |
| Canon CanoScan LiDE 200                       | 2         | 5.41%   |
| Canon CanoScan LiDE 120                       | 2         | 5.41%   |
| Canon CanoScan LiDE 110                       | 2         | 5.41%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 2.7%    |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 2.7%    |
| Plustek 600dpi USB Scanner                    | 1         | 2.7%    |
| HP ScanJet 5590                               | 1         | 2.7%    |
| HP ScanJet 3300c                              | 1         | 2.7%    |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 2.7%    |
| Canon CanoScan LiDE 60                        | 1         | 2.7%    |
| Canon CanoScan FB630U                         | 1         | 2.7%    |
| Canon CanoScan 9000F Mark II                  | 1         | 2.7%    |
| Canon CanoScan 5600F                          | 1         | 2.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 479       | 21.25%  |
| Microdia                               | 260       | 11.54%  |
| Realtek Semiconductor                  | 221       | 9.8%    |
| IMC Networks                           | 181       | 8.03%   |
| Sunplus Innovation Technology          | 155       | 6.88%   |
| Logitech                               | 144       | 6.39%   |
| Cheng Uei Precision Industry (Foxlink) | 98        | 4.35%   |
| Apple                                  | 89        | 3.95%   |
| Acer                                   | 79        | 3.5%    |
| Quanta                                 | 73        | 3.24%   |
| Suyin                                  | 69        | 3.06%   |
| Bison Electronics                      | 68        | 3.02%   |
| Lite-On Technology                     | 44        | 1.95%   |
| Syntek                                 | 30        | 1.33%   |
| Samsung Electronics                    | 22        | 0.98%   |
| Luxvisions Innotech Limited            | 22        | 0.98%   |
| Silicon Motion                         | 21        | 0.93%   |
| Ricoh                                  | 18        | 0.8%    |
| Microsoft                              | 16        | 0.71%   |
| Alcor Micro                            | 16        | 0.71%   |
| Lenovo                                 | 14        | 0.62%   |
| Primax Electronics                     | 13        | 0.58%   |
| Trust                                  | 10        | 0.44%   |
| Sonix Technology                       | 7         | 0.31%   |
| Jieli Technology                       | 6         | 0.27%   |
| Importek                               | 6         | 0.27%   |
| Generalplus Technology                 | 6         | 0.27%   |
| MacroSilicon                           | 5         | 0.22%   |
| Sweex                                  | 4         | 0.18%   |
| Creative Technology                    | 4         | 0.18%   |
| ARC International                      | 4         | 0.18%   |
| ALi                                    | 4         | 0.18%   |
| Z-Star Microelectronics                | 3         | 0.13%   |
| Y Media                                | 3         | 0.13%   |
| Valve Software                         | 3         | 0.13%   |
| SunplusIT                              | 3         | 0.13%   |
| LG Electronics                         | 3         | 0.13%   |
| Genesys Logic                          | 3         | 0.13%   |
| Tobii Technology AB                    | 2         | 0.09%   |
| Sunplus IT                             | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 159       | 6.91%   |
| Realtek Integrated_Webcam_HD                                               | 83        | 3.61%   |
| Chicony Integrated Camera                                                  | 77        | 3.35%   |
| Chicony HD WebCam                                                          | 68        | 2.96%   |
| Realtek Integrated_Webcam_5M                                               | 67        | 2.91%   |
| IMC Networks Integrated Camera                                             | 66        | 2.87%   |
| Sunplus Integrated_Webcam_HD                                               | 65        | 2.82%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 37        | 1.61%   |
| Chicony HP HD Camera                                                       | 32        | 1.39%   |
| Logitech Webcam C270                                                       | 30        | 1.3%    |
| Apple Built-in iSight                                                      | 27        | 1.17%   |
| Chicony USB2.0 Camera                                                      | 24        | 1.04%   |
| Acer Integrated Camera                                                     | 24        | 1.04%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 23        | 1%      |
| Samsung Galaxy series, misc. (MTP mode)                                    | 22        | 0.96%   |
| Logitech HD Pro Webcam C920                                                | 21        | 0.91%   |
| Chicony HP Wide Vision HD Camera                                           | 21        | 0.91%   |
| Microdia Integrated_Webcam_5M                                              | 20        | 0.87%   |
| Chicony USB 2.0 Camera                                                     | 19        | 0.83%   |
| Syntek Integrated Camera                                                   | 18        | 0.78%   |
| Apple FaceTime HD Camera (Built-in)                                        | 18        | 0.78%   |
| Chicony TOSHIBA Web Camera - HD                                            | 17        | 0.74%   |
| Bison BisonCam,NB Pro                                                      | 17        | 0.74%   |
| Apple FaceTime HD Camera                                                   | 17        | 0.74%   |
| Sunplus HD Webcam                                                          | 16        | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 16        | 0.7%    |
| Bison Integrated Camera                                                    | 16        | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 15        | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 14        | 0.61%   |
| Logitech Webcam C310                                                       | 14        | 0.61%   |
| Realtek USB Camera                                                         | 13        | 0.56%   |
| Microdia Integrated Webcam                                                 | 13        | 0.56%   |
| Quanta HD User Facing                                                      | 12        | 0.52%   |
| Lite-On Integrated Camera                                                  | 12        | 0.52%   |
| Lite-On HP HD Camera                                                       | 12        | 0.52%   |
| IMC Networks Integrated Webcam                                             | 12        | 0.52%   |
| Chicony Integrated HP HD Webcam                                            | 12        | 0.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 12        | 0.52%   |
| Bison SunplusIT Integrated Camera                                          | 12        | 0.52%   |
| Quanta HP Wide Vision HD Camera                                            | 11        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 149       | 33.11%  |
| Synaptics                          | 143       | 31.78%  |
| Shenzhen Goodix Technology         | 57        | 12.67%  |
| AuthenTec                          | 32        | 7.11%   |
| Elan Microelectronics              | 24        | 5.33%   |
| LighTuning Technology              | 21        | 4.67%   |
| Upek                               | 19        | 4.22%   |
| STMicroelectronics                 | 3         | 0.67%   |
| Samsung Electronics                | 1         | 0.22%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 49        | 10.89%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 39        | 8.67%   |
| Shenzhen Goodix  FingerPrint Device                                        | 24        | 5.33%   |
| Synaptics UWP WBDI                                                         | 20        | 4.44%   |
| Validity Sensors VFS491                                                    | 19        | 4.22%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 4.22%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 4.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 3.11%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 3.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 3.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 2.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 2.67%   |
| Synaptics  WBDI                                                            | 12        | 2.67%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.67%   |
| Elan ELAN:ARM-M4                                                           | 12        | 2.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.67%   |
| Synaptics WBDI                                                             | 11        | 2.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 2.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 2.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.22%   |
| AuthenTec AES2810                                                          | 9         | 2%      |
| Unknown                                                                    | 7         | 1.56%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.33%   |
| AuthenTec AES1600                                                          | 6         | 1.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.11%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.11%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.11%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.11%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.89%   |
| Synaptics WBDI Device                                                      | 4         | 0.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.67%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.67%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.67%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.44%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.44%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 103       | 51.76%  |
| Alcor Micro                       | 53        | 26.63%  |
| O2 Micro                          | 23        | 11.56%  |
| Upek                              | 6         | 3.02%   |
| Lenovo                            | 6         | 3.02%   |
| VASCO Data Security International | 1         | 0.5%    |
| SCM Microsystems                  | 1         | 0.5%    |
| OmniKey                           | 1         | 0.5%    |
| Gemalto (was Gemplus)             | 1         | 0.5%    |
| Fujitsu Siemens Computers         | 1         | 0.5%    |
| Clay Logic                        | 1         | 0.5%    |
| Chicony Electronics               | 1         | 0.5%    |
| Advanced Card Systems             | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 53        | 26.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 17.59%  |
| Broadcom 58200                                                               | 28        | 14.07%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.55%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 10.55%  |
| Broadcom 5880                                                                | 19        | 9.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3.02%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.02%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.01%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.5%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.5%    |
| OmniKey 5422 Smartcard Reader                                                | 1         | 0.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.5%    |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.5%    |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.5%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.5%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2574      | 67.81%  |
| 1     | 957       | 25.21%  |
| 2     | 212       | 5.58%   |
| 3     | 35        | 0.92%   |
| 4     | 10        | 0.26%   |
| 5     | 4         | 0.11%   |
| 6     | 3         | 0.08%   |
| 8     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 445       | 29.71%  |
| Graphics card            | 308       | 20.56%  |
| Chipcard                 | 175       | 11.68%  |
| Net/wireless             | 146       | 9.75%   |
| Multimedia controller    | 146       | 9.75%   |
| Communication controller | 58        | 3.87%   |
| Camera                   | 49        | 3.27%   |
| Bluetooth                | 28        | 1.87%   |
| Unassigned class         | 27        | 1.8%    |
| Sound                    | 24        | 1.6%    |
| Storage                  | 20        | 1.34%   |
| Network                  | 15        | 1%      |
| Card reader              | 15        | 1%      |
| Net/ethernet             | 13        | 0.87%   |
| Flash memory             | 8         | 0.53%   |
| Storage/ide              | 5         | 0.33%   |
| Storage/ata              | 5         | 0.33%   |
| Modem                    | 3         | 0.2%    |
| Tv card                  | 2         | 0.13%   |
| Storage/raid             | 2         | 0.13%   |
| Storage/nvme             | 2         | 0.13%   |
| Firewire controller      | 1         | 0.07%   |
| Dvb card                 | 1         | 0.07%   |

