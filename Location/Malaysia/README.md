Linux in Malaysia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Malaysia/Desktop/README.md) and [notebooks](/Location/Malaysia/Notebook/README.md).

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

Total: 610

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-52              | Notebook    | [3932620fb9](https://linux-hardware.org/?probe=3932620fb9) | Jun 30, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [1a84c61bd4](https://linux-hardware.org/?probe=1a84c61bd4) | Jun 27, 2023 |
| HP            | 2B2C                        | Desktop     | [a8ec805431](https://linux-hardware.org/?probe=a8ec805431) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [a03717af50](https://linux-hardware.org/?probe=a03717af50) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | Notebook    | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| HP            | 2B2C                        | Desktop     | [3b82186362](https://linux-hardware.org/?probe=3b82186362) | Jun 26, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [4269ca2c0b](https://linux-hardware.org/?probe=4269ca2c0b) | Jun 25, 2023 |
| AZW           | GT-R                        | Notebook    | [11f032f354](https://linux-hardware.org/?probe=11f032f354) | Jun 24, 2023 |
| HP            | 2B2C                        | Desktop     | [4303d28839](https://linux-hardware.org/?probe=4303d28839) | Jun 22, 2023 |
| Unknown       | Unknown                     | Phone       | [32b03337ba](https://linux-hardware.org/?probe=32b03337ba) | Jun 19, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [1623fa6455](https://linux-hardware.org/?probe=1623fa6455) | Jun 11, 2023 |
| MSI           | MS-7388                     | Desktop     | [6d3a406400](https://linux-hardware.org/?probe=6d3a406400) | Jun 10, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| MSI           | MS-7388                     | Desktop     | [fc12ac6b90](https://linux-hardware.org/?probe=fc12ac6b90) | Jun 02, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7957c81218](https://linux-hardware.org/?probe=7957c81218) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1aedc7da48](https://linux-hardware.org/?probe=1aedc7da48) | May 17, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [83537861c1](https://linux-hardware.org/?probe=83537861c1) | May 14, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1f22322c4a](https://linux-hardware.org/?probe=1f22322c4a) | May 11, 2023 |
| MSI           | Stealth 14Studio A13VE      | Notebook    | [86f43bbff1](https://linux-hardware.org/?probe=86f43bbff1) | May 10, 2023 |
| Samsung       | 535U3C                      | Notebook    | [5f2e46be0a](https://linux-hardware.org/?probe=5f2e46be0a) | May 05, 2023 |
| MSI           | MS-7388                     | Desktop     | [948e1d2358](https://linux-hardware.org/?probe=948e1d2358) | May 03, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [0a9bdb3cea](https://linux-hardware.org/?probe=0a9bdb3cea) | May 02, 2023 |
| MSI           | MS-7388                     | Desktop     | [ec819aca80](https://linux-hardware.org/?probe=ec819aca80) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| MSI           | MS-7388                     | Desktop     | [4efa2b04da](https://linux-hardware.org/?probe=4efa2b04da) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| HP            | Notebook                    | Notebook    | [5fc60b1d5f](https://linux-hardware.org/?probe=5fc60b1d5f) | Apr 13, 2023 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [04eb10296f](https://linux-hardware.org/?probe=04eb10296f) | Apr 13, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [ffdcd55e2e](https://linux-hardware.org/?probe=ffdcd55e2e) | Apr 13, 2023 |
| MSI           | MS-7388                     | Desktop     | [d7f892b3e2](https://linux-hardware.org/?probe=d7f892b3e2) | Apr 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [d76bd92923](https://linux-hardware.org/?probe=d76bd92923) | Apr 07, 2023 |
| NEC Comput... | PC-VK27MCZCK                | Notebook    | [e9572ebd2e](https://linux-hardware.org/?probe=e9572ebd2e) | Apr 06, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [f64cf6a2ae](https://linux-hardware.org/?probe=f64cf6a2ae) | Apr 02, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [54789b15f3](https://linux-hardware.org/?probe=54789b15f3) | Mar 29, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [798462942d](https://linux-hardware.org/?probe=798462942d) | Mar 25, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [eb1d734a53](https://linux-hardware.org/?probe=eb1d734a53) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Biostar       | G41D3+                      | Desktop     | [ebb9a17568](https://linux-hardware.org/?probe=ebb9a17568) | Mar 23, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [b54b641b36](https://linux-hardware.org/?probe=b54b641b36) | Mar 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [dcde5e81ed](https://linux-hardware.org/?probe=dcde5e81ed) | Mar 04, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [c9b32e7136](https://linux-hardware.org/?probe=c9b32e7136) | Mar 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [59d082bd5f](https://linux-hardware.org/?probe=59d082bd5f) | Feb 26, 2023 |
| ASUSTek       | ZenBook UX462DA             | Convertible | [4f45a3b6bd](https://linux-hardware.org/?probe=4f45a3b6bd) | Feb 25, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c812182e32](https://linux-hardware.org/?probe=c812182e32) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [9763d78500](https://linux-hardware.org/?probe=9763d78500) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [43bd1ca5e1](https://linux-hardware.org/?probe=43bd1ca5e1) | Feb 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [0a0e30ba0a](https://linux-hardware.org/?probe=0a0e30ba0a) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| HP            | 18E4                        | Desktop     | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| HP            | ENVY 4                      | Notebook    | [0344f89eea](https://linux-hardware.org/?probe=0344f89eea) | Feb 07, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [56e5f689ab](https://linux-hardware.org/?probe=56e5f689ab) | Feb 06, 2023 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | Notebook    | [5260560c15](https://linux-hardware.org/?probe=5260560c15) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [2d40451b53](https://linux-hardware.org/?probe=2d40451b53) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [903e8715e4](https://linux-hardware.org/?probe=903e8715e4) | Feb 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6013489300](https://linux-hardware.org/?probe=6013489300) | Feb 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a195487665](https://linux-hardware.org/?probe=a195487665) | Jan 30, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [d356c9846a](https://linux-hardware.org/?probe=d356c9846a) | Jan 30, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [e660f922a4](https://linux-hardware.org/?probe=e660f922a4) | Jan 27, 2023 |
| HP            | ENVY 4                      | Notebook    | [55ee9d4ca9](https://linux-hardware.org/?probe=55ee9d4ca9) | Jan 27, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [cb932accdb](https://linux-hardware.org/?probe=cb932accdb) | Jan 24, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [d3e44e2970](https://linux-hardware.org/?probe=d3e44e2970) | Jan 20, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [d16f5ca08a](https://linux-hardware.org/?probe=d16f5ca08a) | Jan 19, 2023 |
| Dell          | Latitude 3410               | Notebook    | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0fe4db1f37](https://linux-hardware.org/?probe=0fe4db1f37) | Jan 16, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [20e990e236](https://linux-hardware.org/?probe=20e990e236) | Jan 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [5d228e798d](https://linux-hardware.org/?probe=5d228e798d) | Jan 16, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [4acb924b75](https://linux-hardware.org/?probe=4acb924b75) | Jan 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [f34e2c982f](https://linux-hardware.org/?probe=f34e2c982f) | Jan 13, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [72a6b9a90b](https://linux-hardware.org/?probe=72a6b9a90b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a712e2524b](https://linux-hardware.org/?probe=a712e2524b) | Jan 09, 2023 |
| HP            | 2B2C                        | Desktop     | [1a74d92aaf](https://linux-hardware.org/?probe=1a74d92aaf) | Jan 08, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| Dell          | Latitude 5420               | Notebook    | [06dc453cbc](https://linux-hardware.org/?probe=06dc453cbc) | Dec 27, 2022 |
| HP            | Notebook                    | Notebook    | [8ba42c8ebc](https://linux-hardware.org/?probe=8ba42c8ebc) | Dec 27, 2022 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [44d3b06704](https://linux-hardware.org/?probe=44d3b06704) | Dec 23, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [fd4611b301](https://linux-hardware.org/?probe=fd4611b301) | Dec 21, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4efe19137d](https://linux-hardware.org/?probe=4efe19137d) | Dec 21, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [2b0d31db9d](https://linux-hardware.org/?probe=2b0d31db9d) | Dec 18, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [10a6f30aeb](https://linux-hardware.org/?probe=10a6f30aeb) | Dec 04, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [725404aadb](https://linux-hardware.org/?probe=725404aadb) | Dec 04, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| HP            | 2B2C                        | Desktop     | [91862a2497](https://linux-hardware.org/?probe=91862a2497) | Nov 19, 2022 |
| Dell          | Latitude E6220              | Notebook    | [c92cd25690](https://linux-hardware.org/?probe=c92cd25690) | Nov 19, 2022 |
| HP            | 2B2C                        | Desktop     | [2eb8311f18](https://linux-hardware.org/?probe=2eb8311f18) | Nov 16, 2022 |
| Lenovo        | ThinkPad T450 20BUS1S81K    | Notebook    | [ee3fb9c9d2](https://linux-hardware.org/?probe=ee3fb9c9d2) | Nov 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1fef4a8aa5](https://linux-hardware.org/?probe=1fef4a8aa5) | Nov 13, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| Dell          | 0V52N7 A02                  | Server      | [3151a21ebf](https://linux-hardware.org/?probe=3151a21ebf) | Nov 09, 2022 |
| Dell          | Latitude E6230              | Notebook    | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b39c12a9a4](https://linux-hardware.org/?probe=b39c12a9a4) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Seco          | C40 C                       | Desktop     | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| NEC Comput... | PC-VK27MXZCG                | Notebook    | [04c88c4087](https://linux-hardware.org/?probe=04c88c4087) | Oct 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [dcf74e5715](https://linux-hardware.org/?probe=dcf74e5715) | Oct 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [f514228295](https://linux-hardware.org/?probe=f514228295) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| ASUSTek       | UN65U                       | Mini pc     | [f0bab8d97c](https://linux-hardware.org/?probe=f0bab8d97c) | Oct 06, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1cceb45dea](https://linux-hardware.org/?probe=1cceb45dea) | Oct 04, 2022 |
| HP            | 2B2C                        | Desktop     | [df8a8ec9bc](https://linux-hardware.org/?probe=df8a8ec9bc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | Notebook    | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3e5af3e86c](https://linux-hardware.org/?probe=3e5af3e86c) | Sep 25, 2022 |
| HP            | 18E7                        | Desktop     | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [3f33a64102](https://linux-hardware.org/?probe=3f33a64102) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0d8e7f2e92](https://linux-hardware.org/?probe=0d8e7f2e92) | Sep 21, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Alienware     | M14xR1                      | Notebook    | [a4064c0342](https://linux-hardware.org/?probe=a4064c0342) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [3162a68bf5](https://linux-hardware.org/?probe=3162a68bf5) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [d764e72d74](https://linux-hardware.org/?probe=d764e72d74) | Sep 12, 2022 |
| Alienware     | M14xR1                      | Notebook    | [ea2adf914b](https://linux-hardware.org/?probe=ea2adf914b) | Sep 10, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [3310a4c592](https://linux-hardware.org/?probe=3310a4c592) | Sep 02, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [25e7e97937](https://linux-hardware.org/?probe=25e7e97937) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9b0e2c480f](https://linux-hardware.org/?probe=9b0e2c480f) | Aug 28, 2022 |
| Alienware     | M14xR1                      | Notebook    | [498d5f5254](https://linux-hardware.org/?probe=498d5f5254) | Aug 27, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [398f6d4b78](https://linux-hardware.org/?probe=398f6d4b78) | Aug 25, 2022 |
| Dell          | 0PU052                      | Desktop     | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [23316377ee](https://linux-hardware.org/?probe=23316377ee) | Aug 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [9630e2d4f5](https://linux-hardware.org/?probe=9630e2d4f5) | Aug 21, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [ee6cfb6de5](https://linux-hardware.org/?probe=ee6cfb6de5) | Aug 19, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [0aefa0613d](https://linux-hardware.org/?probe=0aefa0613d) | Aug 15, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [d000ce4d8c](https://linux-hardware.org/?probe=d000ce4d8c) | Aug 15, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [66a759db9c](https://linux-hardware.org/?probe=66a759db9c) | Aug 14, 2022 |
| Acer          | Peppy                       | Notebook    | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| GPD           | G1619-02                    | Notebook    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Lenovo        | ThinkCentre M58 7359DHJ     | Desktop     | [46c2c1db62](https://linux-hardware.org/?probe=46c2c1db62) | Jul 26, 2022 |
| ONDA          | H110-MINI V3.00 Ver:3.00    | Desktop     | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [82b077a668](https://linux-hardware.org/?probe=82b077a668) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [aa2a721361](https://linux-hardware.org/?probe=aa2a721361) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [616a2b7524](https://linux-hardware.org/?probe=616a2b7524) | Jul 12, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [71758de9e1](https://linux-hardware.org/?probe=71758de9e1) | Jul 06, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [5540b74d09](https://linux-hardware.org/?probe=5540b74d09) | Jul 03, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [c793608515](https://linux-hardware.org/?probe=c793608515) | Jul 03, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [c5a5b25674](https://linux-hardware.org/?probe=c5a5b25674) | Jun 28, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [4692c93a71](https://linux-hardware.org/?probe=4692c93a71) | Jun 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| ASUSTek       | K42Jc                       | Notebook    | [29538e9e80](https://linux-hardware.org/?probe=29538e9e80) | May 21, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d525e0eb0c](https://linux-hardware.org/?probe=d525e0eb0c) | May 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [0a9f8b0a4a](https://linux-hardware.org/?probe=0a9f8b0a4a) | May 09, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [f34555b3d6](https://linux-hardware.org/?probe=f34555b3d6) | Apr 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [43adb86887](https://linux-hardware.org/?probe=43adb86887) | Apr 25, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ba9b8d5ac1](https://linux-hardware.org/?probe=ba9b8d5ac1) | Apr 25, 2022 |
| ECS           | Iris8                       | Desktop     | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| HP            | 2B2C                        | Desktop     | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c4456aaa4f](https://linux-hardware.org/?probe=c4456aaa4f) | Apr 19, 2022 |
| HP            | 2B2C                        | Desktop     | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| ILLEGEAR      | ROGUE                       | Notebook    | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ddd1338d3](https://linux-hardware.org/?probe=9ddd1338d3) | Apr 08, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [6cd967267b](https://linux-hardware.org/?probe=6cd967267b) | Mar 31, 2022 |
| Lenovo        | 30D9 NOK                    | Desktop     | [c378cd6fd3](https://linux-hardware.org/?probe=c378cd6fd3) | Mar 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [d9e3d65314](https://linux-hardware.org/?probe=d9e3d65314) | Mar 24, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell          | Inspiron 15 5501            | Notebook    | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a1c0612337](https://linux-hardware.org/?probe=a1c0612337) | Mar 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [d52d9feb9e](https://linux-hardware.org/?probe=d52d9feb9e) | Mar 09, 2022 |
| Dell          | Precision 7730              | Notebook    | [9e9710e890](https://linux-hardware.org/?probe=9e9710e890) | Mar 08, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [8d3f72c54f](https://linux-hardware.org/?probe=8d3f72c54f) | Mar 03, 2022 |
| Biostar       | G41D3+                      | Desktop     | [62ba30cf71](https://linux-hardware.org/?probe=62ba30cf71) | Mar 02, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [bbedea92ea](https://linux-hardware.org/?probe=bbedea92ea) | Mar 01, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [297c168632](https://linux-hardware.org/?probe=297c168632) | Mar 01, 2022 |
| Shuttle       | FH170                       | Desktop     | [768e13fd34](https://linux-hardware.org/?probe=768e13fd34) | Feb 25, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [1dec2ddfad](https://linux-hardware.org/?probe=1dec2ddfad) | Feb 19, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [747515703c](https://linux-hardware.org/?probe=747515703c) | Jan 25, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5d1c8ba7f2](https://linux-hardware.org/?probe=5d1c8ba7f2) | Jan 18, 2022 |
| Dell          | Precision 5550              | Notebook    | [6b866b7c2f](https://linux-hardware.org/?probe=6b866b7c2f) | Jan 18, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [7e0ee3374e](https://linux-hardware.org/?probe=7e0ee3374e) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [ff2f0db3fe](https://linux-hardware.org/?probe=ff2f0db3fe) | Jan 09, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | Desktop     | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | Latitude 7490               | Notebook    | [4ac5151ac0](https://linux-hardware.org/?probe=4ac5151ac0) | Dec 29, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9fe5f60531](https://linux-hardware.org/?probe=9fe5f60531) | Dec 26, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c8ca1c8cc8](https://linux-hardware.org/?probe=c8ca1c8cc8) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | Notebook    | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [c748f77108](https://linux-hardware.org/?probe=c748f77108) | Dec 12, 2021 |
| HP            | 2B44                        | Desktop     | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [faf1be45ae](https://linux-hardware.org/?probe=faf1be45ae) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [16b69bfefc](https://linux-hardware.org/?probe=16b69bfefc) | Dec 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [eb4fb496ae](https://linux-hardware.org/?probe=eb4fb496ae) | Dec 01, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5c4ae3bd8c](https://linux-hardware.org/?probe=5c4ae3bd8c) | Nov 30, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c731d25471](https://linux-hardware.org/?probe=c731d25471) | Nov 30, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [644d197332](https://linux-hardware.org/?probe=644d197332) | Nov 17, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [bece194d5a](https://linux-hardware.org/?probe=bece194d5a) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [b5393ad660](https://linux-hardware.org/?probe=b5393ad660) | Nov 12, 2021 |
| ASUSTek       | T200TA                      | Notebook    | [1f55c83774](https://linux-hardware.org/?probe=1f55c83774) | Nov 04, 2021 |
| ASUSTek       | M2N32-SLI DELUXE            | Desktop     | [87fff05f0f](https://linux-hardware.org/?probe=87fff05f0f) | Nov 03, 2021 |
| Lenovo        | U310                        | Notebook    | [986ba47618](https://linux-hardware.org/?probe=986ba47618) | Oct 24, 2021 |
| Lenovo        | U310                        | Notebook    | [c74a07756c](https://linux-hardware.org/?probe=c74a07756c) | Oct 24, 2021 |
| Intel         | B75                         | Desktop     | [fef715f491](https://linux-hardware.org/?probe=fef715f491) | Oct 23, 2021 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [ccd587fde5](https://linux-hardware.org/?probe=ccd587fde5) | Oct 21, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | Notebook                    | Notebook    | [2761140513](https://linux-hardware.org/?probe=2761140513) | Oct 14, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [8fee3106f7](https://linux-hardware.org/?probe=8fee3106f7) | Oct 12, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [f79000e059](https://linux-hardware.org/?probe=f79000e059) | Oct 12, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Biostar       | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [09b2cd1736](https://linux-hardware.org/?probe=09b2cd1736) | Oct 06, 2021 |
| Biostar       | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| HP            | Notebook                    | Notebook    | [32d9b71796](https://linux-hardware.org/?probe=32d9b71796) | Sep 25, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [1292424ff8](https://linux-hardware.org/?probe=1292424ff8) | Sep 17, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [7441498212](https://linux-hardware.org/?probe=7441498212) | Sep 14, 2021 |
| Lenovo        | Flex 6-11IGM 81A7           | Convertible | [17e78af479](https://linux-hardware.org/?probe=17e78af479) | Sep 14, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [c2533e9d48](https://linux-hardware.org/?probe=c2533e9d48) | Sep 11, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [8137e09a97](https://linux-hardware.org/?probe=8137e09a97) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9c46f65e1d](https://linux-hardware.org/?probe=9c46f65e1d) | Sep 06, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| HP            | ENVY 4                      | Notebook    | [b61e9946e0](https://linux-hardware.org/?probe=b61e9946e0) | Sep 04, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [acc6c11a97](https://linux-hardware.org/?probe=acc6c11a97) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7b28a98a35](https://linux-hardware.org/?probe=7b28a98a35) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7fada0ab8c](https://linux-hardware.org/?probe=7fada0ab8c) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a61ee6d83a](https://linux-hardware.org/?probe=a61ee6d83a) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a1ec21ae3f](https://linux-hardware.org/?probe=a1ec21ae3f) | Aug 29, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cac6720bff](https://linux-hardware.org/?probe=cac6720bff) | Aug 29, 2021 |
| Lenovo        | G400s VILG1                 | Notebook    | [20d6b25fd3](https://linux-hardware.org/?probe=20d6b25fd3) | Aug 29, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [777faedb05](https://linux-hardware.org/?probe=777faedb05) | Aug 27, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [9e8fa8f32d](https://linux-hardware.org/?probe=9e8fa8f32d) | Aug 23, 2021 |
| HP            | Notebook                    | Notebook    | [4028a5fb73](https://linux-hardware.org/?probe=4028a5fb73) | Aug 21, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [de1fa2ccc0](https://linux-hardware.org/?probe=de1fa2ccc0) | Aug 20, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [bb82d97c94](https://linux-hardware.org/?probe=bb82d97c94) | Aug 10, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [38abf3b8e9](https://linux-hardware.org/?probe=38abf3b8e9) | Aug 10, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [89188fe3ca](https://linux-hardware.org/?probe=89188fe3ca) | Aug 08, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [b10f021bef](https://linux-hardware.org/?probe=b10f021bef) | Aug 01, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [36562061d6](https://linux-hardware.org/?probe=36562061d6) | Jul 30, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [4cf28c3600](https://linux-hardware.org/?probe=4cf28c3600) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| HP            | Notebook                    | Notebook    | [458741e8e2](https://linux-hardware.org/?probe=458741e8e2) | Jul 23, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [e71a7fc65b](https://linux-hardware.org/?probe=e71a7fc65b) | Jul 23, 2021 |
| HP            | Pavilion 14                 | Notebook    | [0556a517ff](https://linux-hardware.org/?probe=0556a517ff) | Jul 23, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [fe43d29e0e](https://linux-hardware.org/?probe=fe43d29e0e) | Jul 22, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [3e66028cf8](https://linux-hardware.org/?probe=3e66028cf8) | Jul 22, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3c81cd98ac](https://linux-hardware.org/?probe=3c81cd98ac) | Jul 21, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3da0ea28fa](https://linux-hardware.org/?probe=3da0ea28fa) | Jul 20, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [5a349c4952](https://linux-hardware.org/?probe=5a349c4952) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [275304e806](https://linux-hardware.org/?probe=275304e806) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [99df792e3b](https://linux-hardware.org/?probe=99df792e3b) | Jul 18, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9ffbb5bc79](https://linux-hardware.org/?probe=9ffbb5bc79) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [0e8b29c721](https://linux-hardware.org/?probe=0e8b29c721) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [da8679ccca](https://linux-hardware.org/?probe=da8679ccca) | Jul 14, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2495cf9be5](https://linux-hardware.org/?probe=2495cf9be5) | Jul 12, 2021 |
| HP            | Compaq 6530b (VA036PA#UU... | Notebook    | [ac0b6b96cc](https://linux-hardware.org/?probe=ac0b6b96cc) | Jul 11, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| HP            | Notebook                    | Notebook    | [2f040042a3](https://linux-hardware.org/?probe=2f040042a3) | Jul 10, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [82c73cf6be](https://linux-hardware.org/?probe=82c73cf6be) | Jul 09, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [416014c8b8](https://linux-hardware.org/?probe=416014c8b8) | Jul 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [a630867e0a](https://linux-hardware.org/?probe=a630867e0a) | Jul 06, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [e8965c736d](https://linux-hardware.org/?probe=e8965c736d) | Jul 05, 2021 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [e1a02c3dcb](https://linux-hardware.org/?probe=e1a02c3dcb) | Jul 04, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [939fe39f71](https://linux-hardware.org/?probe=939fe39f71) | Jul 01, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [44c1472c85](https://linux-hardware.org/?probe=44c1472c85) | Jun 30, 2021 |
| AZW           | GT-R                        | Notebook    | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [de1dbcbd7f](https://linux-hardware.org/?probe=de1dbcbd7f) | Jun 27, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [ddb8152ea4](https://linux-hardware.org/?probe=ddb8152ea4) | Jun 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [1104a3ca5a](https://linux-hardware.org/?probe=1104a3ca5a) | Jun 26, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a5a80d3f13](https://linux-hardware.org/?probe=a5a80d3f13) | Jun 24, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [d9270ab2c1](https://linux-hardware.org/?probe=d9270ab2c1) | Jun 23, 2021 |
| Lenovo        | ThinkPad X201 3626RZ4       | Notebook    | [737819a617](https://linux-hardware.org/?probe=737819a617) | Jun 22, 2021 |
| HP            | Notebook                    | Notebook    | [0f663cf796](https://linux-hardware.org/?probe=0f663cf796) | Jun 20, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [9a397ba3b9](https://linux-hardware.org/?probe=9a397ba3b9) | Jun 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [0183eeb644](https://linux-hardware.org/?probe=0183eeb644) | Jun 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4a2d2d3c9](https://linux-hardware.org/?probe=e4a2d2d3c9) | Jun 06, 2021 |
| MSI           | H81M-P33                    | Desktop     | [69a8b43e74](https://linux-hardware.org/?probe=69a8b43e74) | Jun 02, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a67e6bcfce](https://linux-hardware.org/?probe=a67e6bcfce) | Jun 02, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [49a2755ccd](https://linux-hardware.org/?probe=49a2755ccd) | May 31, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [00658a23ab](https://linux-hardware.org/?probe=00658a23ab) | May 27, 2021 |
| Lenovo        | ThinkPad X120e 0611CTO      | Notebook    | [72608b2ea0](https://linux-hardware.org/?probe=72608b2ea0) | May 27, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [5f39051050](https://linux-hardware.org/?probe=5f39051050) | May 26, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [1a314f201b](https://linux-hardware.org/?probe=1a314f201b) | May 26, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [4c5c7570f6](https://linux-hardware.org/?probe=4c5c7570f6) | May 25, 2021 |
| HP            | Notebook                    | Notebook    | [a075cb3a8d](https://linux-hardware.org/?probe=a075cb3a8d) | May 24, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [2b0de1ba10](https://linux-hardware.org/?probe=2b0de1ba10) | May 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [021e17aa96](https://linux-hardware.org/?probe=021e17aa96) | May 19, 2021 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [0cd0f0c51f](https://linux-hardware.org/?probe=0cd0f0c51f) | May 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [71f7778600](https://linux-hardware.org/?probe=71f7778600) | May 13, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [d6ab5352b8](https://linux-hardware.org/?probe=d6ab5352b8) | May 10, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| HP            | 0AA8h                       | Desktop     | [5f350b471f](https://linux-hardware.org/?probe=5f350b471f) | Apr 29, 2021 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [6bb8ea7872](https://linux-hardware.org/?probe=6bb8ea7872) | Apr 23, 2021 |
| System76      | Galago Pro                  | Notebook    | [e712e1fadc](https://linux-hardware.org/?probe=e712e1fadc) | Apr 21, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [07efcf431f](https://linux-hardware.org/?probe=07efcf431f) | Apr 14, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [9f265d798d](https://linux-hardware.org/?probe=9f265d798d) | Apr 14, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [87041c97fb](https://linux-hardware.org/?probe=87041c97fb) | Apr 14, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [6d3642385e](https://linux-hardware.org/?probe=6d3642385e) | Apr 11, 2021 |
| HP            | 2B1C MVB,A                  | All in one  | [ea47f5adbe](https://linux-hardware.org/?probe=ea47f5adbe) | Apr 05, 2021 |
| Dell          | XPS L412Z                   | Notebook    | [e383c24416](https://linux-hardware.org/?probe=e383c24416) | Apr 01, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [006be2bbab](https://linux-hardware.org/?probe=006be2bbab) | Mar 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1a6bdfe860](https://linux-hardware.org/?probe=1a6bdfe860) | Mar 22, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [7a17fa61d9](https://linux-hardware.org/?probe=7a17fa61d9) | Mar 17, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [d476794634](https://linux-hardware.org/?probe=d476794634) | Mar 16, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [fc405347a5](https://linux-hardware.org/?probe=fc405347a5) | Mar 12, 2021 |
| Sony          | VPCEA42EG                   | Notebook    | [e49095cfef](https://linux-hardware.org/?probe=e49095cfef) | Mar 09, 2021 |
| ASUSTek       | S550CM                      | Notebook    | [5ac3e9de20](https://linux-hardware.org/?probe=5ac3e9de20) | Mar 08, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [597b4f88b9](https://linux-hardware.org/?probe=597b4f88b9) | Mar 08, 2021 |
| HP            | Presario CQ43               | Notebook    | [4f9c0e744c](https://linux-hardware.org/?probe=4f9c0e744c) | Feb 28, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [082f8fd3e5](https://linux-hardware.org/?probe=082f8fd3e5) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [1555ed8743](https://linux-hardware.org/?probe=1555ed8743) | Feb 27, 2021 |
| ASUSTek       | H110M-D                     | Desktop     | [19e3cff2be](https://linux-hardware.org/?probe=19e3cff2be) | Feb 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [4f82ee745a](https://linux-hardware.org/?probe=4f82ee745a) | Feb 25, 2021 |
| HP            | Presario CQ43               | Notebook    | [e6e7199511](https://linux-hardware.org/?probe=e6e7199511) | Feb 22, 2021 |
| ASUSTek       | X456UF                      | Notebook    | [f69a109f5c](https://linux-hardware.org/?probe=f69a109f5c) | Feb 14, 2021 |
| HP            | G42                         | Notebook    | [7e1ebb9cf3](https://linux-hardware.org/?probe=7e1ebb9cf3) | Feb 13, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [6c0820678b](https://linux-hardware.org/?probe=6c0820678b) | Feb 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [92518dacfe](https://linux-hardware.org/?probe=92518dacfe) | Feb 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4f8464acc9](https://linux-hardware.org/?probe=4f8464acc9) | Feb 10, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [b50872caf4](https://linux-hardware.org/?probe=b50872caf4) | Feb 07, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [7daa68908c](https://linux-hardware.org/?probe=7daa68908c) | Feb 06, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [acb369859f](https://linux-hardware.org/?probe=acb369859f) | Feb 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [aa40d0ff2b](https://linux-hardware.org/?probe=aa40d0ff2b) | Feb 04, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [d6126d9f25](https://linux-hardware.org/?probe=d6126d9f25) | Jan 27, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [9e5a28d45d](https://linux-hardware.org/?probe=9e5a28d45d) | Jan 27, 2021 |
| Dell          | 0WR7PY A01                  | Desktop     | [9b13ab689f](https://linux-hardware.org/?probe=9b13ab689f) | Jan 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [31faebfa48](https://linux-hardware.org/?probe=31faebfa48) | Jan 23, 2021 |
| Dell          | Latitude 3440               | Notebook    | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [353fb07166](https://linux-hardware.org/?probe=353fb07166) | Jan 20, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [dd87c824a0](https://linux-hardware.org/?probe=dd87c824a0) | Jan 18, 2021 |
| HP            | G42                         | Notebook    | [b4a8c3727b](https://linux-hardware.org/?probe=b4a8c3727b) | Jan 13, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9e291d5782](https://linux-hardware.org/?probe=9e291d5782) | Jan 12, 2021 |
| HP            | Notebook                    | Notebook    | [6bb93d5d1d](https://linux-hardware.org/?probe=6bb93d5d1d) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [d410f07eef](https://linux-hardware.org/?probe=d410f07eef) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [15ba146bfe](https://linux-hardware.org/?probe=15ba146bfe) | Jan 03, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [f3c691cbf8](https://linux-hardware.org/?probe=f3c691cbf8) | Jan 01, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e8d73a49e5](https://linux-hardware.org/?probe=e8d73a49e5) | Dec 30, 2020 |
| HP            | Pavilion g4                 | Notebook    | [c495b342b0](https://linux-hardware.org/?probe=c495b342b0) | Dec 30, 2020 |
| ASUSTek       | TP500LN                     | Notebook    | [36ae52e7d3](https://linux-hardware.org/?probe=36ae52e7d3) | Dec 27, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [fa76a31b79](https://linux-hardware.org/?probe=fa76a31b79) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [7e473c8d12](https://linux-hardware.org/?probe=7e473c8d12) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [645dfe5a80](https://linux-hardware.org/?probe=645dfe5a80) | Dec 23, 2020 |
| Dell          | 0PU052                      | Desktop     | [520a4ef3d0](https://linux-hardware.org/?probe=520a4ef3d0) | Dec 23, 2020 |
| Biostar       | A320MH                      | Desktop     | [a6b1134a37](https://linux-hardware.org/?probe=a6b1134a37) | Dec 18, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [41d76fb580](https://linux-hardware.org/?probe=41d76fb580) | Dec 17, 2020 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [a0b90b128d](https://linux-hardware.org/?probe=a0b90b128d) | Dec 16, 2020 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [9af064ae47](https://linux-hardware.org/?probe=9af064ae47) | Dec 16, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [414fc579a1](https://linux-hardware.org/?probe=414fc579a1) | Dec 02, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [4d1d3b1722](https://linux-hardware.org/?probe=4d1d3b1722) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [cf6242caca](https://linux-hardware.org/?probe=cf6242caca) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [afbf8ce7bc](https://linux-hardware.org/?probe=afbf8ce7bc) | Dec 01, 2020 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [967bb7f4d6](https://linux-hardware.org/?probe=967bb7f4d6) | Nov 30, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [400561434f](https://linux-hardware.org/?probe=400561434f) | Nov 27, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [151262b7a2](https://linux-hardware.org/?probe=151262b7a2) | Nov 26, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eecae3dcbf](https://linux-hardware.org/?probe=eecae3dcbf) | Nov 26, 2020 |
| Dell          | G3 3590                     | Notebook    | [d76accb676](https://linux-hardware.org/?probe=d76accb676) | Nov 18, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db8eeca79f](https://linux-hardware.org/?probe=db8eeca79f) | Nov 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [f617d36143](https://linux-hardware.org/?probe=f617d36143) | Nov 12, 2020 |
| Gigabyte      | Z490 VISION D               | Desktop     | [af58d1579d](https://linux-hardware.org/?probe=af58d1579d) | Nov 09, 2020 |
| Acer          | TM4750                      | Notebook    | [8380f08a89](https://linux-hardware.org/?probe=8380f08a89) | Nov 07, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [4c1052e401](https://linux-hardware.org/?probe=4c1052e401) | Nov 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [b2a86aaf94](https://linux-hardware.org/?probe=b2a86aaf94) | Nov 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [50772450d3](https://linux-hardware.org/?probe=50772450d3) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [5021546be8](https://linux-hardware.org/?probe=5021546be8) | Oct 30, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [adc51544ee](https://linux-hardware.org/?probe=adc51544ee) | Oct 29, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | Notebook    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Acer          | TM4750                      | Notebook    | [2f46c4d024](https://linux-hardware.org/?probe=2f46c4d024) | Oct 27, 2020 |
| Acer          | TM4750                      | Notebook    | [29124f29f8](https://linux-hardware.org/?probe=29124f29f8) | Oct 23, 2020 |
| Dell          | G3 3590                     | Notebook    | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b6aa803efb](https://linux-hardware.org/?probe=b6aa803efb) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [02a2657831](https://linux-hardware.org/?probe=02a2657831) | Oct 20, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [5c8d0c0991](https://linux-hardware.org/?probe=5c8d0c0991) | Oct 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a37736727](https://linux-hardware.org/?probe=1a37736727) | Oct 13, 2020 |
| Dell          | 06D7TR A02                  | Desktop     | [1fff522fa1](https://linux-hardware.org/?probe=1fff522fa1) | Oct 13, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [e8e5a3c2ac](https://linux-hardware.org/?probe=e8e5a3c2ac) | Oct 12, 2020 |
| Sony          | VGN-Z27GN_X                 | Notebook    | [a9230212d3](https://linux-hardware.org/?probe=a9230212d3) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [80297bebea](https://linux-hardware.org/?probe=80297bebea) | Sep 17, 2020 |
| HP            | Pavilion dv6                | Notebook    | [f48a018bbb](https://linux-hardware.org/?probe=f48a018bbb) | Sep 16, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [5eaf26f820](https://linux-hardware.org/?probe=5eaf26f820) | Sep 15, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [4e3ee75e9b](https://linux-hardware.org/?probe=4e3ee75e9b) | Sep 15, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f7f932b330](https://linux-hardware.org/?probe=f7f932b330) | Sep 14, 2020 |
| Acer          | Aspire ES1-420              | Notebook    | [730ae12528](https://linux-hardware.org/?probe=730ae12528) | Sep 10, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [828c695fab](https://linux-hardware.org/?probe=828c695fab) | Sep 06, 2020 |
| HP            | Pavilion dv6                | Notebook    | [47c4b0fdaa](https://linux-hardware.org/?probe=47c4b0fdaa) | Sep 03, 2020 |
| Dell          | Inspiron 5482               | Convertible | [4085a729ac](https://linux-hardware.org/?probe=4085a729ac) | Sep 03, 2020 |
| Dell          | 0RW203                      | Desktop     | [594ab9e6d3](https://linux-hardware.org/?probe=594ab9e6d3) | Sep 02, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [0930a62ca5](https://linux-hardware.org/?probe=0930a62ca5) | Aug 21, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| ASUSTek       | VivoBook S15 X530UN         | Notebook    | [64e65fe674](https://linux-hardware.org/?probe=64e65fe674) | Aug 11, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [bc44361c47](https://linux-hardware.org/?probe=bc44361c47) | Aug 02, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [e8cc620228](https://linux-hardware.org/?probe=e8cc620228) | Aug 02, 2020 |
| Unknown       | Unknown                     | Phone       | [38378b572a](https://linux-hardware.org/?probe=38378b572a) | Aug 01, 2020 |
| HP            | Presario CQ43               | Notebook    | [df780756ee](https://linux-hardware.org/?probe=df780756ee) | Jul 31, 2020 |
| HP            | Presario CQ43               | Notebook    | [102ab797a7](https://linux-hardware.org/?probe=102ab797a7) | Jul 31, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f99c1674c](https://linux-hardware.org/?probe=3f99c1674c) | Jul 30, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [dbbc5219fd](https://linux-hardware.org/?probe=dbbc5219fd) | Jul 27, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [c85ae35bff](https://linux-hardware.org/?probe=c85ae35bff) | Jul 25, 2020 |
| Dell          | Latitude 7285               | Tablet      | [ed3aa05fd5](https://linux-hardware.org/?probe=ed3aa05fd5) | Jul 25, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [81e5774167](https://linux-hardware.org/?probe=81e5774167) | Jul 24, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [1856c4ccbf](https://linux-hardware.org/?probe=1856c4ccbf) | Jul 23, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7fa880215f](https://linux-hardware.org/?probe=7fa880215f) | Jul 21, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2bfaffc9c5](https://linux-hardware.org/?probe=2bfaffc9c5) | Jul 21, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [7b83e5785f](https://linux-hardware.org/?probe=7b83e5785f) | Jul 19, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [d45acf2543](https://linux-hardware.org/?probe=d45acf2543) | Jul 18, 2020 |
| Unknown       | Unknown                     | Phone       | [c0d8474803](https://linux-hardware.org/?probe=c0d8474803) | Jul 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [4b144fb616](https://linux-hardware.org/?probe=4b144fb616) | Jul 14, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7d9a43933e](https://linux-hardware.org/?probe=7d9a43933e) | Jul 14, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [48cdbb3d36](https://linux-hardware.org/?probe=48cdbb3d36) | Jul 11, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [f5ff1447a7](https://linux-hardware.org/?probe=f5ff1447a7) | Jul 08, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [a97a2e14e2](https://linux-hardware.org/?probe=a97a2e14e2) | Jul 06, 2020 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [0aa18d5241](https://linux-hardware.org/?probe=0aa18d5241) | Jul 05, 2020 |
| Dell          | Latitude E6440              | Notebook    | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5d32eb1d75](https://linux-hardware.org/?probe=5d32eb1d75) | Jun 30, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [33534eca13](https://linux-hardware.org/?probe=33534eca13) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6ae79e439f](https://linux-hardware.org/?probe=6ae79e439f) | Jun 28, 2020 |
| Acer          | Aspire 4738                 | Notebook    | [519a7577c0](https://linux-hardware.org/?probe=519a7577c0) | Jun 28, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [0cd3f983c9](https://linux-hardware.org/?probe=0cd3f983c9) | Jun 26, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [bad4de6363](https://linux-hardware.org/?probe=bad4de6363) | Jun 26, 2020 |
| Dell          | Latitude E6440              | Notebook    | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4833031b9b](https://linux-hardware.org/?probe=4833031b9b) | Jun 23, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [99ff555015](https://linux-hardware.org/?probe=99ff555015) | Jun 21, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [05556ef252](https://linux-hardware.org/?probe=05556ef252) | Jun 19, 2020 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0a15b3f355](https://linux-hardware.org/?probe=0a15b3f355) | Jun 18, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [eac1260628](https://linux-hardware.org/?probe=eac1260628) | Jun 17, 2020 |
| Unknown       | Unknown                     | Phone       | [6566b884d6](https://linux-hardware.org/?probe=6566b884d6) | Jun 15, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [3ab69ab51e](https://linux-hardware.org/?probe=3ab69ab51e) | Jun 10, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [ba4a677fab](https://linux-hardware.org/?probe=ba4a677fab) | Jun 10, 2020 |
| HP            | 14                          | Notebook    | [5a36b38b50](https://linux-hardware.org/?probe=5a36b38b50) | Jun 07, 2020 |
| Fujitsu       | LIFEBOOK S761               | Notebook    | [7d4e0682de](https://linux-hardware.org/?probe=7d4e0682de) | Jun 07, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [6c1d889b0d](https://linux-hardware.org/?probe=6c1d889b0d) | Jun 06, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [709dcae624](https://linux-hardware.org/?probe=709dcae624) | Jun 06, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [11c6b72a1b](https://linux-hardware.org/?probe=11c6b72a1b) | Jun 03, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ecf8e72f94](https://linux-hardware.org/?probe=ecf8e72f94) | May 31, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [b335d617f7](https://linux-hardware.org/?probe=b335d617f7) | May 26, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [865933043f](https://linux-hardware.org/?probe=865933043f) | May 26, 2020 |
| Acer          | EQ45M                       | Desktop     | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d2113ac640](https://linux-hardware.org/?probe=d2113ac640) | May 21, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [1882c535de](https://linux-hardware.org/?probe=1882c535de) | May 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [445fc4fef9](https://linux-hardware.org/?probe=445fc4fef9) | May 19, 2020 |
| Dell          | 0PU052                      | Desktop     | [40ab4a84b5](https://linux-hardware.org/?probe=40ab4a84b5) | May 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8156a3eef6](https://linux-hardware.org/?probe=8156a3eef6) | May 11, 2020 |
| SNS Networ... | JOI Book 150                | Notebook    | [3d61c3722c](https://linux-hardware.org/?probe=3d61c3722c) | May 11, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [f92d9768ce](https://linux-hardware.org/?probe=f92d9768ce) | May 07, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [b119ccc5f2](https://linux-hardware.org/?probe=b119ccc5f2) | May 07, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4893a0cfcd](https://linux-hardware.org/?probe=4893a0cfcd) | May 06, 2020 |
| Dell          | 0RY007                      | Desktop     | [4d44e2723d](https://linux-hardware.org/?probe=4d44e2723d) | May 04, 2020 |
| HP            | 14                          | Notebook    | [c0318bc179](https://linux-hardware.org/?probe=c0318bc179) | Apr 30, 2020 |
| Acer          | EQ45M                       | Desktop     | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| Dell          | 0C3YXR A01                  | Desktop     | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| BUSH          | Windows tablet              | Notebook    | [a25abad9de](https://linux-hardware.org/?probe=a25abad9de) | Apr 18, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [9c68002e3d](https://linux-hardware.org/?probe=9c68002e3d) | Apr 13, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [0444963962](https://linux-hardware.org/?probe=0444963962) | Apr 12, 2020 |
| MSI           | B150M Night Elf             | Desktop     | [01013b611d](https://linux-hardware.org/?probe=01013b611d) | Apr 11, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [1211d7770c](https://linux-hardware.org/?probe=1211d7770c) | Mar 15, 2020 |
| Acer          | TM4750                      | Notebook    | [bedf724360](https://linux-hardware.org/?probe=bedf724360) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [db9b7453f2](https://linux-hardware.org/?probe=db9b7453f2) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [69bbe5f0ee](https://linux-hardware.org/?probe=69bbe5f0ee) | Mar 11, 2020 |
| Dell          | Inspiron 1464               | Notebook    | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [46ad418d75](https://linux-hardware.org/?probe=46ad418d75) | Feb 24, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [c1b65d99ff](https://linux-hardware.org/?probe=c1b65d99ff) | Feb 23, 2020 |
| Teclast       | F5                          | Convertible | [23690a5a6e](https://linux-hardware.org/?probe=23690a5a6e) | Feb 16, 2020 |
| Acer          | Aspire 4736Z                | Notebook    | [a6e2ff9c02](https://linux-hardware.org/?probe=a6e2ff9c02) | Feb 15, 2020 |
| ASUSTek       | P6T SE                      | Desktop     | [05737b4c23](https://linux-hardware.org/?probe=05737b4c23) | Feb 11, 2020 |
| HP            | 3647h                       | Desktop     | [06df72e240](https://linux-hardware.org/?probe=06df72e240) | Feb 08, 2020 |
| HP            | ProBook 645 G1              | Notebook    | [18fb680615](https://linux-hardware.org/?probe=18fb680615) | Feb 04, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [5ab23205d8](https://linux-hardware.org/?probe=5ab23205d8) | Jan 21, 2020 |
| ASUSTek       | P8Z77-M                     | Desktop     | [9247337003](https://linux-hardware.org/?probe=9247337003) | Jan 20, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [1b04478121](https://linux-hardware.org/?probe=1b04478121) | Jan 14, 2020 |
| Chuwi         | LapBook Pro                 | Notebook    | [f9d248ac7c](https://linux-hardware.org/?probe=f9d248ac7c) | Jan 03, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3b64de1ec8](https://linux-hardware.org/?probe=3b64de1ec8) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [31643f4ace](https://linux-hardware.org/?probe=31643f4ace) | Dec 31, 2019 |
| Lenovo        | G500s 20245                 | Notebook    | [82346138d0](https://linux-hardware.org/?probe=82346138d0) | Dec 30, 2019 |
| HP            | ProBook 4545s               | Notebook    | [66e278f8a6](https://linux-hardware.org/?probe=66e278f8a6) | Dec 29, 2019 |
| HP            | ProBook 4545s               | Notebook    | [7c1a6a786f](https://linux-hardware.org/?probe=7c1a6a786f) | Dec 29, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [02d013ad00](https://linux-hardware.org/?probe=02d013ad00) | Dec 20, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0c7973b78](https://linux-hardware.org/?probe=c0c7973b78) | Nov 20, 2019 |
| Supermicro    | K1SPE-IN001                 | Server      | [5f6d0233a8](https://linux-hardware.org/?probe=5f6d0233a8) | Nov 18, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [9e78c03471](https://linux-hardware.org/?probe=9e78c03471) | Nov 17, 2019 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [875f14ed53](https://linux-hardware.org/?probe=875f14ed53) | Nov 13, 2019 |
| Dell          | Vostro V130                 | Notebook    | [ca716fdbad](https://linux-hardware.org/?probe=ca716fdbad) | Nov 09, 2019 |
| Dell          | Vostro V130                 | Notebook    | [0ba8558483](https://linux-hardware.org/?probe=0ba8558483) | Nov 08, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [7ce70fa206](https://linux-hardware.org/?probe=7ce70fa206) | Oct 25, 2019 |
| Acer          | Swift SF314-55G             | Notebook    | [8526e89541](https://linux-hardware.org/?probe=8526e89541) | Oct 16, 2019 |
| ASUSTek       | X456URK                     | Notebook    | [03b7432783](https://linux-hardware.org/?probe=03b7432783) | Oct 10, 2019 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [b37e090603](https://linux-hardware.org/?probe=b37e090603) | Oct 06, 2019 |
| HP            | 0AA8h                       | Desktop     | [a60543a450](https://linux-hardware.org/?probe=a60543a450) | Sep 07, 2019 |
| HP            | ZBook 15                    | Notebook    | [f9aaccbfe0](https://linux-hardware.org/?probe=f9aaccbfe0) | Sep 06, 2019 |
| Dell          | Latitude E7440              | Notebook    | [04bd492077](https://linux-hardware.org/?probe=04bd492077) | Sep 06, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [ae117eb491](https://linux-hardware.org/?probe=ae117eb491) | Sep 03, 2019 |
| Dell          | 0RY007                      | Desktop     | [576ec7dcd0](https://linux-hardware.org/?probe=576ec7dcd0) | Aug 22, 2019 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [d9d789a4f2](https://linux-hardware.org/?probe=d9d789a4f2) | Aug 21, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [3442bbe40c](https://linux-hardware.org/?probe=3442bbe40c) | Aug 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f8d49fa793](https://linux-hardware.org/?probe=f8d49fa793) | Aug 03, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [46b9ff1fff](https://linux-hardware.org/?probe=46b9ff1fff) | Aug 03, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [a91c21a426](https://linux-hardware.org/?probe=a91c21a426) | Aug 02, 2019 |
| HP            | ProLiant DL60 Gen9          | Server      | [140daf886e](https://linux-hardware.org/?probe=140daf886e) | Jul 24, 2019 |
| ASUSTek       | H81M-C                      | Desktop     | [38a96dff85](https://linux-hardware.org/?probe=38a96dff85) | Jul 02, 2019 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [62b0b05a66](https://linux-hardware.org/?probe=62b0b05a66) | Jul 01, 2019 |
| ASUSTek       | X450CP                      | Notebook    | [2931234c98](https://linux-hardware.org/?probe=2931234c98) | May 02, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [c7b00947af](https://linux-hardware.org/?probe=c7b00947af) | Apr 30, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [35e3cab7fd](https://linux-hardware.org/?probe=35e3cab7fd) | Apr 24, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3783735e9b](https://linux-hardware.org/?probe=3783735e9b) | Apr 23, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [672cf7aa7f](https://linux-hardware.org/?probe=672cf7aa7f) | Apr 20, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [5202aae85e](https://linux-hardware.org/?probe=5202aae85e) | Feb 26, 2019 |
| ASUSTek       | X101H                       | Notebook    | [bfa018d76d](https://linux-hardware.org/?probe=bfa018d76d) | Jan 21, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [323f6e2eeb](https://linux-hardware.org/?probe=323f6e2eeb) | Dec 17, 2018 |
| ASRock        | X79 Extreme9                | Desktop     | [c96c05c47b](https://linux-hardware.org/?probe=c96c05c47b) | Nov 30, 2018 |
| Dell          | XPS L521X                   | Notebook    | [3f3c8f2571](https://linux-hardware.org/?probe=3f3c8f2571) | Nov 25, 2018 |
| Dell          | Latitude E6520              | Notebook    | [166d529d12](https://linux-hardware.org/?probe=166d529d12) | Nov 12, 2018 |
| HP            | 2820h                       | Desktop     | [1f42af0283](https://linux-hardware.org/?probe=1f42af0283) | Dec 17, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [8381b26177](https://linux-hardware.org/?probe=8381b26177) | Jan 27, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [799ee32fce](https://linux-hardware.org/?probe=799ee32fce) | Jan 21, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Malaysia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 60        | 13.42%  |
| Ubuntu 18.04        | 24        | 5.37%   |
| Ubuntu 22.04        | 20        | 4.47%   |
| Debian 11           | 14        | 3.13%   |
| OpenMandriva 4.3    | 12        | 2.68%   |
| Zorin 16            | 11        | 2.46%   |
| Pop!_OS 22.04       | 11        | 2.46%   |
| OpenMandriva 4.2    | 11        | 2.46%   |
| Pop!_OS 20.10       | 10        | 2.24%   |
| ArcoLinux Rolling   | 10        | 2.24%   |
| Pop!_OS 21.04       | 9         | 2.01%   |
| OpenMandriva 4.50   | 9         | 2.01%   |
| OpenMandriva 23.01  | 9         | 2.01%   |
| KDE neon 20.04      | 9         | 2.01%   |
| Pop!_OS 20.04       | 8         | 1.79%   |
| Fedora 33           | 8         | 1.79%   |
| Ubuntu 19.04        | 7         | 1.57%   |
| OpenMandriva 23.03  | 7         | 1.57%   |
| Fedora 37           | 7         | 1.57%   |
| Linux Mint 19.3     | 6         | 1.34%   |
| Fedora 34           | 6         | 1.34%   |
| Linux Mint 21.1     | 5         | 1.12%   |
| EndeavourOS Rolling | 5         | 1.12%   |
| Arch Rolling        | 5         | 1.12%   |
| Arch                | 5         | 1.12%   |
| Zorin 15            | 4         | 0.89%   |
| Ubuntu 21.04        | 4         | 0.89%   |
| Ubuntu 20.10        | 4         | 0.89%   |
| Ubuntu 19.10        | 4         | 0.89%   |
| Ubuntu 16.04        | 4         | 0.89%   |
| Manjaro             | 4         | 0.89%   |
| Linux Mint 20.2     | 4         | 0.89%   |
| Elementary 6.1      | 4         | 0.89%   |
| Elementary 5.1.7    | 4         | 0.89%   |
| Android             | 4         | 0.89%   |
| Xubuntu 22.04       | 3         | 0.67%   |
| Xubuntu 18.04       | 3         | 0.67%   |
| Ubuntu 21.10        | 3         | 0.67%   |
| Linux Mint 20.1     | 3         | 0.67%   |
| KDE neon 22.04      | 3         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 129       | 30.21%  |
| OpenMandriva  | 45        | 10.54%  |
| Pop!_OS       | 36        | 8.43%   |
| Fedora        | 28        | 6.56%   |
| Linux Mint    | 22        | 5.15%   |
| Debian        | 17        | 3.98%   |
| Zorin         | 16        | 3.75%   |
| Manjaro       | 13        | 3.04%   |
| KDE neon      | 13        | 3.04%   |
| Elementary    | 11        | 2.58%   |
| ArcoLinux     | 10        | 2.34%   |
| Arch          | 10        | 2.34%   |
| Endless       | 8         | 1.87%   |
| Xubuntu       | 7         | 1.64%   |
| Lubuntu       | 7         | 1.64%   |
| Kubuntu       | 6         | 1.41%   |
| EndeavourOS   | 6         | 1.41%   |
| Kali          | 5         | 1.17%   |
| CentOS        | 4         | 0.94%   |
| Android       | 4         | 0.94%   |
| SteamOS       | 3         | 0.7%    |
| Ubuntu Unity  | 2         | 0.47%   |
| Ubuntu MATE   | 2         | 0.47%   |
| Ubuntu Budgie | 2         | 0.47%   |
| ROSA          | 2         | 0.47%   |
| openSUSE      | 2         | 0.47%   |
| Nobara        | 2         | 0.47%   |
| Gentoo        | 2         | 0.47%   |
| Archcraft     | 2         | 0.47%   |
| Xero          | 1         | 0.23%   |
| Ultramarine   | 1         | 0.23%   |
| Rocky Linux   | 1         | 0.23%   |
| Reborn OS     | 1         | 0.23%   |
| Raspbian      | 1         | 0.23%   |
| Peppermint    | 1         | 0.23%   |
| MX            | 1         | 0.23%   |
| LMDE          | 1         | 0.23%   |
| Linux Lite    | 1         | 0.23%   |
| BuildRoot     | 1         | 0.23%   |
| Axyl          | 1         | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 10        | 2.08%   |
| 5.16.7-desktop-1omv4003  | 9         | 1.87%   |
| 6.2.6-desktop-1omv2390   | 8         | 1.66%   |
| 5.4.0-58-generic         | 8         | 1.66%   |
| 5.4.0-42-generic         | 8         | 1.66%   |
| 6.1.1-desktop-1omv2290   | 6         | 1.25%   |
| 5.15.0-58-generic        | 6         | 1.25%   |
| 5.15.0-52-generic        | 6         | 1.25%   |
| 5.13.19-6-pve            | 6         | 1.25%   |
| 5.11.0-7620-generic      | 6         | 1.25%   |
| 5.12.4-desktop-1omv4050  | 5         | 1.04%   |
| 5.11.0-27-generic        | 5         | 1.04%   |
| 6.3.9-arch1-1            | 4         | 0.83%   |
| 5.4.0-7634-generic       | 4         | 0.83%   |
| 5.4.0-40-generic         | 4         | 0.83%   |
| 5.15.0-56-generic        | 4         | 0.83%   |
| 5.0.0-37-generic         | 4         | 0.83%   |
| 6.2.6-76060206-generic   | 3         | 0.62%   |
| 6.0.12-76060006-generic  | 3         | 0.62%   |
| 5.8.0-7642-generic       | 3         | 0.62%   |
| 5.8.0-7630-generic       | 3         | 0.62%   |
| 5.4.0-54-generic         | 3         | 0.62%   |
| 5.4.0-52-generic         | 3         | 0.62%   |
| 5.4.0-48-generic         | 3         | 0.62%   |
| 5.4.0-37-generic         | 3         | 0.62%   |
| 5.3.0-53-generic         | 3         | 0.62%   |
| 5.3.0-46-generic         | 3         | 0.62%   |
| 5.19.0-38-generic        | 3         | 0.62%   |
| 5.19.0-32-generic        | 3         | 0.62%   |
| 5.16.3-desktop-2omv4050  | 3         | 0.62%   |
| 5.15.0-46-generic        | 3         | 0.62%   |
| 5.15.0-40-generic        | 3         | 0.62%   |
| 5.15.0-39-generic        | 3         | 0.62%   |
| 5.15.0-25-generic        | 3         | 0.62%   |
| 5.13.0-7614-generic      | 3         | 0.62%   |
| 5.13.0-22-generic        | 3         | 0.62%   |
| 5.11.0-7614-generic      | 3         | 0.62%   |
| 5.11.0-46-generic        | 3         | 0.62%   |
| 5.11.0-43-generic        | 3         | 0.62%   |
| 5.11.0-34-generic        | 3         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 14.85%  |
| 5.15.0  | 36        | 7.86%   |
| 5.11.0  | 30        | 6.55%   |
| 5.8.0   | 26        | 5.68%   |
| 4.15.0  | 20        | 4.37%   |
| 5.3.0   | 19        | 4.15%   |
| 5.13.0  | 19        | 4.15%   |
| 5.0.0   | 18        | 3.93%   |
| 5.19.0  | 12        | 2.62%   |
| 6.2.6   | 11        | 2.4%    |
| 5.10.14 | 10        | 2.18%   |
| 5.16.7  | 9         | 1.97%   |
| 6.1.1   | 7         | 1.53%   |
| 5.10.0  | 7         | 1.53%   |
| 5.13.19 | 6         | 1.31%   |
| 4.18.0  | 6         | 1.31%   |
| 6.0.12  | 5         | 1.09%   |
| 5.17.1  | 5         | 1.09%   |
| 5.12.4  | 5         | 1.09%   |
| 6.3.9   | 4         | 0.87%   |
| 5.18.0  | 4         | 0.87%   |
| 5.9.0   | 3         | 0.66%   |
| 5.16.3  | 3         | 0.66%   |
| 5.16.15 | 3         | 0.66%   |
| 6.2.8   | 2         | 0.44%   |
| 6.1.4   | 2         | 0.44%   |
| 6.1.0   | 2         | 0.44%   |
| 5.9.1   | 2         | 0.44%   |
| 5.19.9  | 2         | 0.44%   |
| 5.19.12 | 2         | 0.44%   |
| 5.17.6  | 2         | 0.44%   |
| 5.17.5  | 2         | 0.44%   |
| 5.15.35 | 2         | 0.44%   |
| 5.14.18 | 2         | 0.44%   |
| 5.14.0  | 2         | 0.44%   |
| 5.13.13 | 2         | 0.44%   |
| 5.12.9  | 2         | 0.44%   |
| 5.12.7  | 2         | 0.44%   |
| 5.12.15 | 2         | 0.44%   |
| 5.11.18 | 2         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 15.04%  |
| 5.15    | 50        | 11.06%  |
| 5.11    | 35        | 7.74%   |
| 5.8     | 33        | 7.3%    |
| 5.13    | 28        | 6.19%   |
| 5.10    | 27        | 5.97%   |
| 4.15    | 20        | 4.42%   |
| 5.3     | 19        | 4.2%    |
| 5.19    | 19        | 4.2%    |
| 5.16    | 18        | 3.98%   |
| 5.0     | 18        | 3.98%   |
| 6.2     | 17        | 3.76%   |
| 5.12    | 13        | 2.88%   |
| 6.1     | 12        | 2.65%   |
| 6.0     | 10        | 2.21%   |
| 6.3     | 9         | 1.99%   |
| 5.18    | 9         | 1.99%   |
| 5.17    | 9         | 1.99%   |
| 5.9     | 8         | 1.77%   |
| 5.14    | 8         | 1.77%   |
| 4.18    | 6         | 1.33%   |
| 3.10    | 3         | 0.66%   |
| 5.7     | 2         | 0.44%   |
| 5.6     | 2         | 0.44%   |
| 4.9     | 2         | 0.44%   |
| 4.4     | 2         | 0.44%   |
| 3.18    | 2         | 0.44%   |
| 4.19    | 1         | 0.22%   |
| 4.10    | 1         | 0.22%   |
| 4.1     | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 396       | 97.3%   |
| i686    | 5         | 1.23%   |
| armv8l  | 3         | 0.74%   |
| armv7l  | 2         | 0.49%   |
| aarch64 | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 188       | 43.82%  |
| KDE5          | 84        | 19.58%  |
| Unknown       | 42        | 9.79%   |
| XFCE          | 29        | 6.76%   |
| X-Cinnamon    | 19        | 4.43%   |
| KDE           | 13        | 3.03%   |
| Openbox       | 12        | 2.8%    |
| Pantheon      | 11        | 2.56%   |
| MATE          | 10        | 2.33%   |
| LXQt          | 6         | 1.4%    |
| Unity         | 2         | 0.47%   |
| LXDE          | 2         | 0.47%   |
| GNOME Classic | 2         | 0.47%   |
| Budgie        | 2         | 0.47%   |
| bspwm         | 2         | 0.47%   |
| Peppermint    | 1         | 0.23%   |
| i3            | 1         | 0.23%   |
| Hyprland      | 1         | 0.23%   |
| herbstluftwm  | 1         | 0.23%   |
| Cinnamon      | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 330       | 77.83%  |
| Wayland | 61        | 14.39%  |
| Unknown | 21        | 4.95%   |
| Tty     | 12        | 2.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 221       | 52.62%  |
| SDDM    | 81        | 19.29%  |
| GDM3    | 40        | 9.52%   |
| GDM     | 37        | 8.81%   |
| LightDM | 34        | 8.1%    |
| TDM     | 5         | 1.19%   |
| LXDM    | 2         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 320       | 77.29%  |
| Unknown | 31        | 7.49%   |
| en_GB   | 28        | 6.76%   |
| en_SG   | 16        | 3.86%   |
| C       | 4         | 0.97%   |
| en_AU   | 3         | 0.72%   |
| zh_CN   | 2         | 0.48%   |
| ms_MY   | 2         | 0.48%   |
| en_MY   | 2         | 0.48%   |
| zh_TW   | 1         | 0.24%   |
| zh_SG   | 1         | 0.24%   |
| ja_JP   | 1         | 0.24%   |
| id_ID   | 1         | 0.24%   |
| en_HK   | 1         | 0.24%   |
| de_DE   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 224       | 53.98%  |
| EFI  | 191       | 46.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 307       | 73.62%  |
| Btrfs   | 36        | 8.63%   |
| Overlay | 35        | 8.39%   |
| Zfs     | 13        | 3.12%   |
| Unknown | 13        | 3.12%   |
| Xfs     | 9         | 2.16%   |
| Ext2    | 2         | 0.48%   |
| Tmpfs   | 1         | 0.24%   |
| Ext3    | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 230       | 55.16%  |
| GPT     | 137       | 32.85%  |
| MBR     | 50        | 11.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 336       | 80.19%  |
| Yes       | 83        | 19.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 279       | 66.91%  |
| Yes       | 138       | 33.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 73        | 17.94%  |
| Dell                    | 68        | 16.71%  |
| Hewlett-Packard         | 52        | 12.78%  |
| Lenovo                  | 40        | 9.83%   |
| Gigabyte Technology     | 37        | 9.09%   |
| MSI                     | 26        | 6.39%   |
| Acer                    | 24        | 5.9%    |
| Intel                   | 16        | 3.93%   |
| Apple                   | 8         | 1.97%   |
| Unknown                 | 7         | 1.72%   |
| ASRock                  | 6         | 1.47%   |
| Biostar                 | 5         | 1.23%   |
| Sony                    | 4         | 0.98%   |
| Fujitsu                 | 4         | 0.98%   |
| Samsung Electronics     | 3         | 0.74%   |
| HUAWEI                  | 3         | 0.74%   |
| Raspberry Pi Foundation | 2         | 0.49%   |
| NEC Computers           | 2         | 0.49%   |
| ILLEGEAR                | 2         | 0.49%   |
| ECS                     | 2         | 0.49%   |
| Chuwi                   | 2         | 0.49%   |
| Acidanthera             | 2         | 0.49%   |
| Vorke                   | 1         | 0.25%   |
| Valve                   | 1         | 0.25%   |
| Toshiba                 | 1         | 0.25%   |
| Timi                    | 1         | 0.25%   |
| Teclast                 | 1         | 0.25%   |
| System76                | 1         | 0.25%   |
| Supermicro              | 1         | 0.25%   |
| SNS Network (M)         | 1         | 0.25%   |
| Shuttle                 | 1         | 0.25%   |
| Seco                    | 1         | 0.25%   |
| ONDA                    | 1         | 0.25%   |
| Infinix                 | 1         | 0.25%   |
| HONOR                   | 1         | 0.25%   |
| GPD                     | 1         | 0.25%   |
| BUSH                    | 1         | 0.25%   |
| AZW                     | 1         | 0.25%   |
| ASRockRack              | 1         | 0.25%   |
| AMI                     | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel DH61WW AAG23116-204         | 8         | 1.97%   |
| ASUS All Series                   | 8         | 1.97%   |
| Unknown                           | 7         | 1.72%   |
| Gigabyte Z77M-D3H                 | 6         | 1.47%   |
| MSI MS-7C52                       | 5         | 1.23%   |
| HP Notebook                       | 5         | 1.23%   |
| Gigabyte B85M-D3H                 | 5         | 1.23%   |
| MSI MS-7817                       | 3         | 0.74%   |
| Intel DH61WW AAG23116-300         | 3         | 0.74%   |
| Dell OptiPlex 755                 | 3         | 0.74%   |
| MSI MS-7C81                       | 2         | 0.49%   |
| MSI MS-7B89                       | 2         | 0.49%   |
| MSI Modern 14 B5M                 | 2         | 0.49%   |
| Intel MAHOBAY                     | 2         | 0.49%   |
| HP Pavilion dv6                   | 2         | 0.49%   |
| HP Laptop 15-bs0xx                | 2         | 0.49%   |
| HP ENVY 4                         | 2         | 0.49%   |
| HP EliteBook 8470p                | 2         | 0.49%   |
| HP EliteBook 840 G2               | 2         | 0.49%   |
| HP Compaq Presario CQ40           | 2         | 0.49%   |
| Gigabyte X570 UD                  | 2         | 0.49%   |
| Gigabyte B450M S2H                | 2         | 0.49%   |
| Dell XPS 8940                     | 2         | 0.49%   |
| Dell XPS 15 7590                  | 2         | 0.49%   |
| Dell OptiPlex 990                 | 2         | 0.49%   |
| Dell Latitude E6520               | 2         | 0.49%   |
| Dell Latitude E6440               | 2         | 0.49%   |
| Dell Latitude 3410                | 2         | 0.49%   |
| Biostar G41D3C                    | 2         | 0.49%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI   | 2         | 0.49%   |
| ASUS P8Z77-V LX                   | 2         | 0.49%   |
| ASUS K45VD                        | 2         | 0.49%   |
| ASUS K43SD                        | 2         | 0.49%   |
| Apple MacBookPro8,1               | 2         | 0.49%   |
| Vorke V1 Plus                     | 1         | 0.25%   |
| Valve Jupiter                     | 1         | 0.25%   |
| Toshiba dynabook Satellite B552/H | 1         | 0.25%   |
| Timi RedmiBook 14 II              | 1         | 0.25%   |
| Teclast F5                        | 1         | 0.25%   |
| System76 Galago Pro               | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Latitude       | 20        | 4.91%   |
| Lenovo ThinkPad     | 18        | 4.42%   |
| Dell Inspiron       | 18        | 4.42%   |
| Acer Aspire         | 14        | 3.44%   |
| Intel DH61WW        | 11        | 2.7%    |
| Dell OptiPlex       | 11        | 2.7%    |
| HP Pavilion         | 8         | 1.97%   |
| HP Compaq           | 8         | 1.97%   |
| Dell XPS            | 8         | 1.97%   |
| ASUS All            | 8         | 1.97%   |
| HP EliteBook        | 7         | 1.72%   |
| Dell Precision      | 7         | 1.72%   |
| Unknown             | 7         | 1.72%   |
| Gigabyte Z77M-D3H   | 6         | 1.47%   |
| MSI MS-7C52         | 5         | 1.23%   |
| Lenovo IdeaPad      | 5         | 1.23%   |
| HP Notebook         | 5         | 1.23%   |
| HP Laptop           | 5         | 1.23%   |
| Gigabyte B85M-D3H   | 5         | 1.23%   |
| ASUS ROG            | 5         | 1.23%   |
| Gigabyte X570       | 4         | 0.98%   |
| ASUS VivoBook       | 4         | 0.98%   |
| ASUS TUF            | 4         | 0.98%   |
| MSI MS-7817         | 3         | 0.74%   |
| Lenovo ThinkStation | 3         | 0.74%   |
| Lenovo ThinkCentre  | 3         | 0.74%   |
| HP ENVY             | 3         | 0.74%   |
| Gigabyte B450M      | 3         | 0.74%   |
| Fujitsu LIFEBOOK    | 3         | 0.74%   |
| ASUS P8B75-M        | 3         | 0.74%   |
| Apple MacBookPro8   | 3         | 0.74%   |
| Acer Nitro          | 3         | 0.74%   |
| RPi Raspberry       | 2         | 0.49%   |
| MSI MS-7C81         | 2         | 0.49%   |
| MSI MS-7B89         | 2         | 0.49%   |
| MSI Modern          | 2         | 0.49%   |
| Lenovo Yoga         | 2         | 0.49%   |
| Intel MAHOBAY       | 2         | 0.49%   |
| HP ProLiant         | 2         | 0.49%   |
| HP ProBook          | 2         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 44        | 10.81%  |
| 2013    | 40        | 9.83%   |
| 2019    | 38        | 9.34%   |
| 2012    | 38        | 9.34%   |
| 2018    | 36        | 8.85%   |
| 2020    | 35        | 8.6%    |
| 2021    | 31        | 7.62%   |
| 2015    | 24        | 5.9%    |
| 2017    | 22        | 5.41%   |
| 2010    | 20        | 4.91%   |
| 2014    | 17        | 4.18%   |
| 2008    | 17        | 4.18%   |
| 2009    | 12        | 2.95%   |
| 2016    | 10        | 2.46%   |
| 2007    | 10        | 2.46%   |
| 2022    | 6         | 1.47%   |
| Unknown | 5         | 1.23%   |
| 2023    | 1         | 0.25%   |
| 2006    | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 211       | 51.84%  |
| Desktop        | 162       | 39.8%   |
| Convertible    | 9         | 2.21%   |
| All in one     | 7         | 1.72%   |
| Server         | 5         | 1.23%   |
| Phone          | 4         | 0.98%   |
| Tablet         | 4         | 0.98%   |
| Mini pc        | 3         | 0.74%   |
| System on chip | 2         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 380       | 93.37%  |
| Enabled  | 27        | 6.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 405       | 99.51%  |
| Yes  | 2         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 93        | 22.63%  |
| 16.01-24.0  | 83        | 20.19%  |
| 3.01-4.0    | 80        | 19.46%  |
| 8.01-16.0   | 76        | 18.49%  |
| 32.01-64.0  | 32        | 7.79%   |
| 1.01-2.0    | 17        | 4.14%   |
| 64.01-256.0 | 14        | 3.41%   |
| 24.01-32.0  | 7         | 1.7%    |
| 2.01-3.0    | 7         | 1.7%    |
| 0.51-1.0    | 2         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 148       | 32.46%  |
| 2.01-3.0    | 134       | 29.39%  |
| 3.01-4.0    | 67        | 14.69%  |
| 4.01-8.0    | 47        | 10.31%  |
| 0.51-1.0    | 29        | 6.36%   |
| 8.01-16.0   | 15        | 3.29%   |
| 0.01-0.5    | 5         | 1.1%    |
| 32.01-64.0  | 4         | 0.88%   |
| 24.01-32.0  | 3         | 0.66%   |
| 64.01-256.0 | 2         | 0.44%   |
| 16.01-24.0  | 1         | 0.22%   |
| Unknown     | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 225       | 53.57%  |
| 2      | 114       | 27.14%  |
| 3      | 36        | 8.57%   |
| 4      | 19        | 4.52%   |
| 5      | 9         | 2.14%   |
| 7      | 6         | 1.43%   |
| 8      | 4         | 0.95%   |
| 6      | 4         | 0.95%   |
| 10     | 1         | 0.24%   |
| 9      | 1         | 0.24%   |
| 0      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 274       | 66.99%  |
| Yes       | 135       | 33.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 344       | 84.52%  |
| No        | 63        | 15.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 331       | 80.54%  |
| No        | 80        | 19.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 60.88%  |
| No        | 160       | 39.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Malaysia | 407       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 156       | 35.45%  |
| Petaling Jaya          | 48        | 10.91%  |
| Shah Alam              | 17        | 3.86%   |
| Johor Bahru            | 15        | 3.41%   |
| Puchong Batu Dua Belas | 14        | 3.18%   |
| Subang Jaya            | 13        | 2.95%   |
| Ipoh                   | 12        | 2.73%   |
| Kota Kinabalu          | 11        | 2.5%    |
| George Town            | 11        | 2.5%    |
| Seremban               | 10        | 2.27%   |
| Sungai Buloh           | 9         | 2.05%   |
| Malacca                | 8         | 1.82%   |
| Kota Bharu             | 8         | 1.82%   |
| Kajang                 | 8         | 1.82%   |
| Kuching                | 7         | 1.59%   |
| Sungai Petani          | 5         | 1.14%   |
| Kulim                  | 5         | 1.14%   |
| Tawau                  | 4         | 0.91%   |
| Skudai                 | 4         | 0.91%   |
| Marabu                 | 4         | 0.91%   |
| Kulai                  | 4         | 0.91%   |
| Klang                  | 4         | 0.91%   |
| Cyberjaya              | 4         | 0.91%   |
| Cheras                 | 4         | 0.91%   |
| Butterworth            | 4         | 0.91%   |
| Bayan Lepas            | 4         | 0.91%   |
| Ampang                 | 4         | 0.91%   |
| Seri Kembangan         | 3         | 0.68%   |
| Putrajaya              | 3         | 0.68%   |
| Semenyih               | 2         | 0.45%   |
| Rawang                 | 2         | 0.45%   |
| Nibong Tebal           | 2         | 0.45%   |
| Long Seridan           | 2         | 0.45%   |
| Bukit Mertajam         | 2         | 0.45%   |
| Ayer Itam              | 2         | 0.45%   |
| Alor Star              | 2         | 0.45%   |
| Taman Senai            | 1         | 0.23%   |
| Taiping                | 1         | 0.23%   |
| Sibu                   | 1         | 0.23%   |
| Sepang                 | 1         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 117       | 192    | 17.86%  |
| WDC                         | 103       | 175    | 15.73%  |
| Kingston                    | 53        | 71     | 8.09%   |
| Samsung Electronics         | 51        | 74     | 7.79%   |
| Toshiba                     | 45        | 53     | 6.87%   |
| Sandisk                     | 26        | 35     | 3.97%   |
| Unknown                     | 25        | 33     | 3.82%   |
| HGST                        | 19        | 22     | 2.9%    |
| A-DATA Technology           | 18        | 30     | 2.75%   |
| Intel                       | 16        | 24     | 2.44%   |
| Apacer                      | 13        | 19     | 1.98%   |
| PNY                         | 12        | 37     | 1.83%   |
| Crucial                     | 12        | 20     | 1.83%   |
| SK hynix                    | 9         | 9      | 1.37%   |
| Micron Technology           | 8         | 12     | 1.22%   |
| Hitachi                     | 8         | 13     | 1.22%   |
| Phison                      | 7         | 10     | 1.07%   |
| KIOXIA                      | 7         | 8      | 1.07%   |
| Transcend                   | 6         | 7      | 0.92%   |
| China                       | 6         | 6      | 0.92%   |
| Hewlett-Packard             | 5         | 5      | 0.76%   |
| Corsair                     | 5         | 13     | 0.76%   |
| TO Exter                    | 4         | 6      | 0.61%   |
| SPCC                        | 4         | 5      | 0.61%   |
| Silicon Motion              | 4         | 5      | 0.61%   |
| Phison Electronics          | 4         | 5      | 0.61%   |
| Patriot                     | 4         | 5      | 0.61%   |
| Kingston Technology Company | 3         | 3      | 0.46%   |
| Gigabyte Technology         | 3         | 3      | 0.46%   |
| ADATA Technology            | 3         | 3      | 0.46%   |
| XPG                         | 2         | 3      | 0.31%   |
| Verbatim                    | 2         | 2      | 0.31%   |
| Team                        | 2         | 2      | 0.31%   |
| Plextor                     | 2         | 2      | 0.31%   |
| Pioneer                     | 2         | 2      | 0.31%   |
| OCZ                         | 2         | 4      | 0.31%   |
| Netac                       | 2         | 2      | 0.31%   |
| Micron/Crucial Technology   | 2         | 3      | 0.31%   |
| KIOXIA-EXCERIA              | 2         | 4      | 0.31%   |
| Kingchuxing                 | 2         | 2      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 14        | 1.92%   |
| Toshiba MQ01ABD100 1TB             | 9         | 1.24%   |
| Seagate ST3500414CS 500GB          | 8         | 1.1%    |
| WDC WD5000AAKX-75U6AA0 500GB       | 7         | 0.96%   |
| WDC WD2500AAKX-753CA1 250GB        | 7         | 0.96%   |
| Seagate ST2000DM008-2UB102 2TB     | 7         | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB     | 7         | 0.96%   |
| Toshiba MQ04ABF100 1TB             | 6         | 0.82%   |
| PNY 1TB SATA SSD                   | 6         | 0.82%   |
| HGST HTS545050A7E680 500GB         | 6         | 0.82%   |
| Crucial CT500MX500SSD1 500GB       | 6         | 0.82%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 5         | 0.69%   |
| WDC WD20EZRX-00D8PB0 2TB           | 5         | 0.69%   |
| Unknown MMC Card  32GB             | 5         | 0.69%   |
| Seagate ST500LT012-1DG142 500GB    | 5         | 0.69%   |
| Seagate ST500DM002-1BD142 500GB    | 5         | 0.69%   |
| Seagate ST380815AS 80GB            | 5         | 0.69%   |
| Samsung HD103SJ 1TB                | 5         | 0.69%   |
| Kingston SA400S37480G 480GB SSD    | 5         | 0.69%   |
| Corsair Force MP510 240GB          | 5         | 0.69%   |
| Apacer AS340 120GB SSD             | 5         | 0.69%   |
| TO Exter nal USB 3.0 1TB           | 4         | 0.55%   |
| Seagate ST500DM002-1BC142 500GB    | 4         | 0.55%   |
| Seagate ST3160815AS 160GB          | 4         | 0.55%   |
| Seagate ST1000LM048-2E7172 1TB     | 4         | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 0.55%   |
| SanDisk SSD PLUS 240GB             | 4         | 0.55%   |
| Samsung SSD 860 EVO 250GB          | 4         | 0.55%   |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.55%   |
| HGST HTS721010A9E630 1TB           | 4         | 0.55%   |
| A-DATA SX8200PNP 256GB             | 4         | 0.55%   |
| A-DATA SU650 120GB SSD             | 4         | 0.55%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 3         | 0.41%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 3         | 0.41%   |
| WDC WD3200AAKS-00SBA0 320GB        | 3         | 0.41%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 3         | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.41%   |
| Unknown MMC Card  64GB             | 3         | 0.41%   |
| Unknown MMC Card                   | 3         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 114       | 189    | 39.58%  |
| WDC                 | 88        | 160    | 30.56%  |
| Toshiba             | 38        | 45     | 13.19%  |
| HGST                | 19        | 22     | 6.6%    |
| Samsung Electronics | 10        | 16     | 3.47%   |
| Hitachi             | 8         | 13     | 2.78%   |
| Unknown             | 2         | 2      | 0.69%   |
| Hewlett-Packard     | 2         | 2      | 0.69%   |
| Fujitsu             | 2         | 2      | 0.69%   |
| USB3.0              | 1         | 1      | 0.35%   |
| Maxtor              | 1         | 2      | 0.35%   |
| JMicron Technology  | 1         | 1      | 0.35%   |
| ASMT                | 1         | 1      | 0.35%   |
| Apple               | 1         | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 44        | 56     | 21.36%  |
| Samsung Electronics | 22        | 32     | 10.68%  |
| SanDisk             | 15        | 19     | 7.28%   |
| Apacer              | 13        | 19     | 6.31%   |
| Crucial             | 12        | 20     | 5.83%   |
| PNY                 | 11        | 36     | 5.34%   |
| A-DATA Technology   | 10        | 10     | 4.85%   |
| Transcend           | 6         | 6      | 2.91%   |
| Intel               | 6         | 9      | 2.91%   |
| China               | 6         | 6      | 2.91%   |
| WDC                 | 5         | 5      | 2.43%   |
| TO Exter            | 4         | 6      | 1.94%   |
| SPCC                | 4         | 5      | 1.94%   |
| Patriot             | 4         | 5      | 1.94%   |
| Micron Technology   | 4         | 8      | 1.94%   |
| Verbatim            | 2         | 2      | 0.97%   |
| Toshiba             | 2         | 2      | 0.97%   |
| Team                | 2         | 2      | 0.97%   |
| Seagate             | 2         | 2      | 0.97%   |
| Plextor             | 2         | 2      | 0.97%   |
| Pioneer             | 2         | 2      | 0.97%   |
| OCZ                 | 2         | 4      | 0.97%   |
| Netac               | 2         | 2      | 0.97%   |
| KIOXIA-EXCERIA      | 2         | 4      | 0.97%   |
| KimMiDi             | 2         | 2      | 0.97%   |
| Hewlett-Packard     | 2         | 2      | 0.97%   |
| External            | 2         | 2      | 0.97%   |
| Colorful            | 2         | 2      | 0.97%   |
| Teclast             | 1         | 1      | 0.49%   |
| sk600               | 1         | 1      | 0.49%   |
| SK hynix            | 1         | 1      | 0.49%   |
| SATAFIRM            | 1         | 1      | 0.49%   |
| MAXSUN              | 1         | 1      | 0.49%   |
| LS                  | 1         | 1      | 0.49%   |
| LITEON              | 1         | 1      | 0.49%   |
| Kingmax             | 1         | 1      | 0.49%   |
| Hikvision           | 1         | 2      | 0.49%   |
| Gigabyte Technology | 1         | 1      | 0.49%   |
| FORESEE             | 1         | 1      | 0.49%   |
| ASMT                | 1         | 2      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 240       | 457    | 42.93%  |
| SSD     | 177       | 289    | 31.66%  |
| NVMe    | 109       | 181    | 19.5%   |
| MMC     | 21        | 28     | 3.76%   |
| Unknown | 12        | 15     | 2.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 331       | 730    | 68.11%  |
| NVMe | 108       | 179    | 22.22%  |
| SAS  | 26        | 33     | 5.35%   |
| MMC  | 21        | 28     | 4.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 257       | 424    | 60.19%  |
| 0.51-1.0   | 130       | 228    | 30.44%  |
| 1.01-2.0   | 31        | 75     | 7.26%   |
| 3.01-4.0   | 6         | 15     | 1.41%   |
| 4.01-10.0  | 2         | 3      | 0.47%   |
| 2.01-3.0   | 1         | 1      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 118       | 27.19%  |
| 251-500        | 97        | 22.35%  |
| 501-1000       | 60        | 13.82%  |
| 1-20           | 41        | 9.45%   |
| 51-100         | 32        | 7.37%   |
| 1001-2000      | 28        | 6.45%   |
| 21-50          | 22        | 5.07%   |
| Unknown        | 18        | 4.15%   |
| More than 3000 | 11        | 2.53%   |
| 2001-3000      | 7         | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 193       | 43.37%  |
| 21-50          | 70        | 15.73%  |
| 101-250        | 52        | 11.69%  |
| 51-100         | 45        | 10.11%  |
| 251-500        | 31        | 6.97%   |
| Unknown        | 18        | 4.04%   |
| 501-1000       | 16        | 3.6%    |
| 1001-2000      | 10        | 2.25%   |
| More than 3000 | 6         | 1.35%   |
| 2001-3000      | 3         | 0.67%   |
| 0              | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB                   | 7         | 7      | 14.89%  |
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 4.26%   |
| Seagate ST9320325AS 320GB                      | 2         | 2      | 4.26%   |
| Seagate ST3500414CS 500GB                      | 2         | 3      | 4.26%   |
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 2.13%   |
| WDC WD800AAJS-00PSA0 80GB                      | 1         | 1      | 2.13%   |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 2.13%   |
| WDC WD5000AAKX-753CA1 500GB                    | 1         | 1      | 2.13%   |
| WDC WD5000AAKX-00ERMA0 500GB                   | 1         | 1      | 2.13%   |
| WDC WD5000AADS-00S9B0 500GB                    | 1         | 1      | 2.13%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 2.13%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 2.13%   |
| WDC WD10EZEX-60WN4A0 1TB                       | 1         | 1      | 2.13%   |
| WDC WD10EZEX-08WN4A0 1TB                       | 1         | 1      | 2.13%   |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 2.13%   |
| Toshiba MK1059GSMP 1TB                         | 1         | 1      | 2.13%   |
| SPCC Solid State Disk 256GB                    | 1         | 1      | 2.13%   |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 2.13%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.13%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 1      | 2.13%   |
| Seagate ST380211AS 80GB                        | 1         | 1      | 2.13%   |
| Seagate ST3320620A 320GB                       | 1         | 1      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 2.13%   |
| Samsung Electronics SSD PM830 2.5 7mm 512GB    | 1         | 1      | 2.13%   |
| Samsung Electronics HM160HI 160GB              | 1         | 1      | 2.13%   |
| PNY 1TB SATA SSD                               | 1         | 6      | 2.13%   |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 2      | 2.13%   |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 2.13%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 2.13%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 2.13%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 3      | 2.13%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 2.13%   |
| Hitachi HDS721050CLA362 500GB                  | 1         | 1      | 2.13%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 2.13%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 2.13%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 2.13%   |
| Hewlett-Packard SSD S700 120GB                 | 1         | 1      | 2.13%   |
| Unknown                                        | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 17        | 17     | 36.96%  |
| Seagate                   | 9         | 11     | 19.57%  |
| Toshiba                   | 4         | 4      | 8.7%    |
| Hitachi                   | 4         | 6      | 8.7%    |
| HGST                      | 3         | 3      | 6.52%   |
| Samsung Electronics       | 2         | 2      | 4.35%   |
| SPCC                      | 1         | 1      | 2.17%   |
| PNY                       | 1         | 6      | 2.17%   |
| Micron/Crucial Technology | 1         | 2      | 2.17%   |
| Micron Technology         | 1         | 1      | 2.17%   |
| Kingston                  | 1         | 1      | 2.17%   |
| Hewlett-Packard           | 1         | 1      | 2.17%   |
| Unknown                   | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 16     | 43.24%  |
| Seagate             | 9         | 11     | 24.32%  |
| Toshiba             | 4         | 4      | 10.81%  |
| Hitachi             | 4         | 6      | 10.81%  |
| HGST                | 3         | 3      | 8.11%   |
| Samsung Electronics | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 41     | 80%     |
| SSD  | 8         | 13     | 17.78%  |
| NVMe | 1         | 2      | 2.22%   |

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
| Detected | 256       | 577    | 56.89%  |
| Works    | 150       | 337    | 33.33%  |
| Malfunc  | 44        | 56     | 9.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 294       | 58.8%   |
| AMD                          | 64        | 12.8%   |
| SanDisk                      | 21        | 4.2%    |
| Samsung Electronics          | 21        | 4.2%    |
| Phison Electronics           | 19        | 3.8%    |
| Kingston Technology Company  | 12        | 2.4%    |
| ADATA Technology             | 9         | 1.8%    |
| SK hynix                     | 8         | 1.6%    |
| ASMedia Technology           | 8         | 1.6%    |
| Silicon Motion               | 7         | 1.4%    |
| Nvidia                       | 7         | 1.4%    |
| KIOXIA                       | 7         | 1.4%    |
| Toshiba America Info Systems | 5         | 1%      |
| Micron Technology            | 4         | 0.8%    |
| Marvell Technology Group     | 4         | 0.8%    |
| JMicron Technology           | 4         | 0.8%    |
| Micron/Crucial Technology    | 2         | 0.4%    |
| Silicon Image                | 1         | 0.2%    |
| Lite-On IT Corp. / Plextor   | 1         | 0.2%    |
| Hewlett-Packard              | 1         | 0.2%    |
| Biwin Storage Technology     | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 51        | 8.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 26        | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 23        | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 21        | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 3.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 16        | 2.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 1.7%    |
| Phison E12 NVMe Controller                                                     | 10        | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 10        | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 10        | 1.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 1.53%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 1.53%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 9         | 1.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.02%   |
| Phison PS5013 E13 NVMe Controller                                              | 6         | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.02%   |
| AMD FCH SATA Controller D                                                      | 6         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 0.85%   |
| Intel SSD 660P Series                                                          | 5         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 0.85%   |
| Intel 82Q35 Express PT IDER Controller                                         | 5         | 0.85%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.85%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.68%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 4         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 285       | 57.81%  |
| NVMe | 108       | 21.91%  |
| IDE  | 55        | 11.16%  |
| RAID | 45        | 9.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 317       | 77.89%  |
| AMD    | 84        | 20.64%  |
| ARM    | 6         | 1.47%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz              | 9         | 2.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.96%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 8         | 1.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 5         | 1.22%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 5         | 1.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.98%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 0.98%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.98%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 4         | 0.98%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 0.98%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 0.98%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 3         | 0.73%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.73%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.73%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 0.73%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 3         | 0.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.73%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.73%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.73%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 3         | 0.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.73%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.73%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 3         | 0.73%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.73%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.73%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 0.73%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 0.73%   |
| Intel Xeon CPU X5450 @ 3.00GHz                | 2         | 0.49%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.49%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.49%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 107       | 26.16%  |
| Intel Core i7           | 61        | 14.91%  |
| Intel Core i3           | 43        | 10.51%  |
| AMD Ryzen 5             | 30        | 7.33%   |
| Intel Core 2 Duo        | 22        | 5.38%   |
| Other                   | 21        | 5.13%   |
| Intel Pentium           | 19        | 4.65%   |
| Intel Celeron           | 17        | 4.16%   |
| Intel Xeon              | 12        | 2.93%   |
| AMD Ryzen 7             | 11        | 2.69%   |
| Intel Atom              | 6         | 1.47%   |
| Intel Pentium Dual-Core | 5         | 1.22%   |
| Intel Core 2 Quad       | 5         | 1.22%   |
| AMD Ryzen 9             | 5         | 1.22%   |
| AMD A6                  | 5         | 1.22%   |
| AMD Ryzen 3             | 4         | 0.98%   |
| AMD Athlon              | 4         | 0.98%   |
| AMD Ryzen Threadripper  | 3         | 0.73%   |
| AMD Ryzen 7 PRO         | 3         | 0.73%   |
| AMD A10                 | 3         | 0.73%   |
| Intel Core i9           | 2         | 0.49%   |
| ARM BCM                 | 2         | 0.49%   |
| ARM AArch64             | 2         | 0.49%   |
| AMD FX                  | 2         | 0.49%   |
| AMD E                   | 2         | 0.49%   |
| AMD Athlon 64 X2        | 2         | 0.49%   |
| AMD A4                  | 2         | 0.49%   |
| AMD A12                 | 2         | 0.49%   |
| Intel Pentium Dual      | 1         | 0.24%   |
| Intel Genuine           | 1         | 0.24%   |
| AMD Ryzen Embedded      | 1         | 0.24%   |
| AMD Phenom II X6        | 1         | 0.24%   |
| AMD Phenom II X4        | 1         | 0.24%   |
| AMD EPYC                | 1         | 0.24%   |
| AMD Athlon X2           | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 180       | 44.12%  |
| 4      | 140       | 34.31%  |
| 6      | 44        | 10.78%  |
| 8      | 21        | 5.15%   |
| 16     | 7         | 1.72%   |
| 1      | 6         | 1.47%   |
| 12     | 4         | 0.98%   |
| 14     | 2         | 0.49%   |
| 10     | 2         | 0.49%   |
| 64     | 1         | 0.25%   |
| 3      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 403       | 99.02%  |
| 2      | 4         | 0.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 266       | 65.04%  |
| 1      | 142       | 34.72%  |
| 4      | 1         | 0.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 403       | 98.77%  |
| Unknown        | 5         | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 24.53%  |
| 0x206a7    | 36        | 8.49%   |
| 0x306c3    | 30        | 7.08%   |
| 0x306a9    | 28        | 6.6%    |
| 0x1067a    | 17        | 4.01%   |
| 0x906ea    | 11        | 2.59%   |
| 0x806e9    | 10        | 2.36%   |
| 0x08108109 | 10        | 2.36%   |
| 0x40651    | 8         | 1.89%   |
| 0x306d4    | 7         | 1.65%   |
| 0x806ea    | 6         | 1.42%   |
| 0x506e3    | 6         | 1.42%   |
| 0x406e3    | 6         | 1.42%   |
| 0x20655    | 6         | 1.42%   |
| 0xa0652    | 5         | 1.18%   |
| 0x6fb      | 5         | 1.18%   |
| 0x20652    | 5         | 1.18%   |
| 0x08701021 | 5         | 1.18%   |
| 0x906e9    | 4         | 0.94%   |
| 0x806ec    | 4         | 0.94%   |
| 0x806eb    | 4         | 0.94%   |
| 0x806c1    | 4         | 0.94%   |
| 0x706a1    | 4         | 0.94%   |
| 0x6fd      | 4         | 0.94%   |
| 0x10676    | 4         | 0.94%   |
| 0x08600104 | 4         | 0.94%   |
| 0x06001119 | 4         | 0.94%   |
| 0xa0653    | 3         | 0.71%   |
| 0x90672    | 3         | 0.71%   |
| 0x806d1    | 3         | 0.71%   |
| 0x406c4    | 3         | 0.71%   |
| 0x30678    | 3         | 0.71%   |
| 0x0a50000b | 3         | 0.71%   |
| 0x0a20120a | 3         | 0.71%   |
| 0xa0671    | 2         | 0.47%   |
| 0xa0655    | 2         | 0.47%   |
| 0x906eb    | 2         | 0.47%   |
| 0x706e5    | 2         | 0.47%   |
| 0x706a8    | 2         | 0.47%   |
| 0x406c3    | 2         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 12.53%  |
| SandyBridge      | 47        | 11.55%  |
| Haswell          | 46        | 11.3%   |
| IvyBridge        | 42        | 10.32%  |
| Penryn           | 26        | 6.39%   |
| Zen+             | 19        | 4.67%   |
| Skylake          | 16        | 3.93%   |
| Zen 3            | 15        | 3.69%   |
| Zen 2            | 15        | 3.69%   |
| Unknown          | 15        | 3.69%   |
| Westmere         | 13        | 3.19%   |
| CometLake        | 13        | 3.19%   |
| Silvermont       | 10        | 2.46%   |
| Core             | 10        | 2.46%   |
| Broadwell        | 9         | 2.21%   |
| Zen              | 8         | 1.97%   |
| TigerLake        | 6         | 1.47%   |
| Piledriver       | 6         | 1.47%   |
| IceLake          | 6         | 1.47%   |
| Goldmont plus    | 6         | 1.47%   |
| Alderlake Hybrid | 6         | 1.47%   |
| Nehalem          | 3         | 0.74%   |
| K10              | 3         | 0.74%   |
| Excavator        | 3         | 0.74%   |
| Steamroller      | 2         | 0.49%   |
| K8 Hammer        | 2         | 0.49%   |
| Jaguar           | 2         | 0.49%   |
| Bonnell          | 2         | 0.49%   |
| Bobcat           | 2         | 0.49%   |
| K8 & K10 hybrid  | 1         | 0.25%   |
| K10 Llano        | 1         | 0.25%   |
| Goldmont         | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 243       | 48.6%   |
| Nvidia                     | 143       | 28.6%   |
| AMD                        | 108       | 21.6%   |
| ASPEED Technology          | 4         | 0.8%    |
| Matrox Electronics Systems | 2         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 6.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 3.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 2.35%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 2.15%   |
| Intel HD Graphics 620                                                                    | 10        | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 1.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.76%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.37%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 7         | 1.37%   |
| Intel UHD Graphics 620                                                                   | 7         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.17%   |
| AMD Renoir                                                                               | 6         | 1.17%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5         | 0.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 0.98%   |
| Intel HD Graphics 630                                                                    | 5         | 0.98%   |
| Intel HD Graphics 530                                                                    | 5         | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.98%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4         | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.78%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 0.78%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.59%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 3         | 0.59%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.59%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 155       | 37.9%   |
| 1 x AMD              | 74        | 18.09%  |
| 1 x Nvidia           | 72        | 17.6%   |
| Intel + Nvidia       | 60        | 14.67%  |
| Intel + AMD          | 20        | 4.89%   |
| 2 x AMD              | 8         | 1.96%   |
| AMD + Nvidia         | 7         | 1.71%   |
| Other                | 6         | 1.47%   |
| Nvidia + ASPEED      | 3         | 0.73%   |
| 1 x Matrox           | 2         | 0.49%   |
| 2 x AMD + 3 x Nvidia | 1         | 0.24%   |
| 1 x ASPEED           | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 320       | 77.11%  |
| Proprietary | 78        | 18.8%   |
| Unknown     | 17        | 4.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 222       | 53.24%  |
| 1.01-2.0   | 68        | 16.31%  |
| 0.51-1.0   | 38        | 9.11%   |
| 3.01-4.0   | 31        | 7.43%   |
| 0.01-0.5   | 31        | 7.43%   |
| 7.01-8.0   | 15        | 3.6%    |
| 5.01-6.0   | 6         | 1.44%   |
| 8.01-16.0  | 4         | 0.96%   |
| 2.01-3.0   | 2         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 54        | 12.44%  |
| Samsung Electronics     | 46        | 10.6%   |
| Dell                    | 45        | 10.37%  |
| Chimei Innolux          | 40        | 9.22%   |
| LG Display              | 35        | 8.06%   |
| BOE                     | 31        | 7.14%   |
| BenQ                    | 22        | 5.07%   |
| Acer                    | 22        | 5.07%   |
| Hewlett-Packard         | 19        | 4.38%   |
| Goldstar                | 18        | 4.15%   |
| AOC                     | 15        | 3.46%   |
| Sharp                   | 12        | 2.76%   |
| Philips                 | 11        | 2.53%   |
| ViewSonic               | 7         | 1.61%   |
| Apple                   | 7         | 1.61%   |
| Lenovo                  | 5         | 1.15%   |
| Chi Mei Optoelectronics | 4         | 0.92%   |
| Toshiba                 | 3         | 0.69%   |
| Panasonic               | 3         | 0.69%   |
| ASUSTek Computer        | 3         | 0.69%   |
| Unknown                 | 2         | 0.46%   |
| PANDA                   | 2         | 0.46%   |
| LG Electronics          | 2         | 0.46%   |
| InnoLux Display         | 2         | 0.46%   |
| Denver                  | 2         | 0.46%   |
| Unknown                 | 2         | 0.46%   |
| Xiaomi                  | 1         | 0.23%   |
| Valve                   | 1         | 0.23%   |
| TRI                     | 1         | 0.23%   |
| Sony                    | 1         | 0.23%   |
| NCS                     | 1         | 0.23%   |
| MStar                   | 1         | 0.23%   |
| MSI                     | 1         | 0.23%   |
| LTM                     | 1         | 0.23%   |
| LG Philips              | 1         | 0.23%   |
| InfoVision              | 1         | 0.23%   |
| HUYINIUDA               | 1         | 0.23%   |
| HJC                     | 1         | 0.23%   |
| EXP                     | 1         | 0.23%   |
| Envision Peripherals    | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 7         | 1.57%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                          | 6         | 1.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 4         | 0.9%    |
| Dell E2720HS DELA15E 1920x1080 600x340mm 27.2-inch                        | 4         | 0.9%    |
| BenQ EX3203R BNQ7F66 2560x1440 698x393mm 31.5-inch                        | 4         | 0.9%    |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 4         | 0.9%    |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 3         | 0.67%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                        | 3         | 0.67%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 3         | 0.67%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.67%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 3         | 0.67%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                         | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 3         | 0.67%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                         | 3         | 0.67%   |
| Sharp LCD SHP10C9 1920x540                                                | 2         | 0.45%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch         | 2         | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 2         | 0.45%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch          | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.45%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 2         | 0.45%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                   | 2         | 0.45%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.45%   |
| Hewlett-Packard LCD Monitor P221                                          | 2         | 0.45%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch                | 2         | 0.45%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                        | 2         | 0.45%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.45%   |
| Dell LCD Monitor E2720HS 1920x1080                                        | 2         | 0.45%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch           | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.45%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                        | 2         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 168       | 40.1%   |
| 1366x768 (WXGA)    | 118       | 28.16%  |
| 1600x900 (HD+)     | 23        | 5.49%   |
| 3840x2160 (4K)     | 22        | 5.25%   |
| 2560x1440 (QHD)    | 16        | 3.82%   |
| 1280x800 (WXGA)    | 9         | 2.15%   |
| 2560x1080          | 6         | 1.43%   |
| 1920x1200 (WUXGA)  | 6         | 1.43%   |
| 1440x900 (WXGA+)   | 6         | 1.43%   |
| 1360x768           | 6         | 1.43%   |
| Unknown            | 5         | 1.19%   |
| 1680x1050 (WSXGA+) | 4         | 0.95%   |
| 2160x1440          | 3         | 0.72%   |
| 1280x1024 (SXGA)   | 3         | 0.72%   |
| 1024x768 (XGA)     | 3         | 0.72%   |
| 5760x1080          | 2         | 0.48%   |
| 1920x540           | 2         | 0.48%   |
| 1600x1200          | 2         | 0.48%   |
| 1280x720 (HD)      | 2         | 0.48%   |
| 800x1280           | 1         | 0.24%   |
| 5440x1080          | 1         | 0.24%   |
| 5120x1440          | 1         | 0.24%   |
| 3840x1080          | 1         | 0.24%   |
| 3440x1440          | 1         | 0.24%   |
| 3120x1600          | 1         | 0.24%   |
| 3000x2000          | 1         | 0.24%   |
| 2880x1920          | 1         | 0.24%   |
| 2560x1600          | 1         | 0.24%   |
| 2240x1400          | 1         | 0.24%   |
| 1360x765           | 1         | 0.24%   |
| 1280x960           | 1         | 0.24%   |
| 1024x600           | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 82        | 18.94%  |
| 14      | 57        | 13.16%  |
| 13      | 44        | 10.16%  |
| 24      | 34        | 7.85%   |
| 23      | 32        | 7.39%   |
| 21      | 25        | 5.77%   |
| 18      | 23        | 5.31%   |
| 27      | 22        | 5.08%   |
| Unknown | 20        | 4.62%   |
| 31      | 14        | 3.23%   |
| 19      | 13        | 3%      |
| 20      | 12        | 2.77%   |
| 17      | 10        | 2.31%   |
| 12      | 8         | 1.85%   |
| 32      | 6         | 1.39%   |
| 11      | 6         | 1.39%   |
| 34      | 4         | 0.92%   |
| 22      | 3         | 0.69%   |
| 84      | 2         | 0.46%   |
| 72      | 2         | 0.46%   |
| 52      | 2         | 0.46%   |
| 28      | 2         | 0.46%   |
| 25      | 2         | 0.46%   |
| 7       | 2         | 0.46%   |
| 65      | 1         | 0.23%   |
| 55      | 1         | 0.23%   |
| 39      | 1         | 0.23%   |
| 35      | 1         | 0.23%   |
| 16      | 1         | 0.23%   |
| 10      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 168       | 39.07%  |
| 501-600     | 83        | 19.3%   |
| 401-500     | 75        | 17.44%  |
| 201-300     | 31        | 7.21%   |
| Unknown     | 20        | 4.65%   |
| 601-700     | 19        | 4.42%   |
| 351-400     | 12        | 2.79%   |
| 701-800     | 10        | 2.33%   |
| 1501-2000   | 4         | 0.93%   |
| 1001-1500   | 4         | 0.93%   |
| 801-900     | 2         | 0.47%   |
| 101-200     | 1         | 0.23%   |
| 1-100       | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 316       | 81.03%  |
| 16/10   | 29        | 7.44%   |
| Unknown | 17        | 4.36%   |
| 3/2     | 7         | 1.79%   |
| 21/9    | 7         | 1.79%   |
| 5/4     | 5         | 1.28%   |
| 4/3     | 5         | 1.28%   |
| 32/9    | 2         | 0.51%   |
| 1.00    | 1         | 0.26%   |
| 0.67    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 89        | 20.7%   |
| 101-110        | 82        | 19.07%  |
| 201-250        | 80        | 18.6%   |
| 151-200        | 31        | 7.21%   |
| 351-500        | 25        | 5.81%   |
| 141-150        | 24        | 5.58%   |
| 301-350        | 22        | 5.12%   |
| Unknown        | 20        | 4.65%   |
| 71-80          | 13        | 3.02%   |
| 251-300        | 11        | 2.56%   |
| More than 1000 | 8         | 1.86%   |
| 61-70          | 7         | 1.63%   |
| 121-130        | 7         | 1.63%   |
| 51-60          | 6         | 1.4%    |
| 1-40           | 2         | 0.47%   |
| 41-50          | 1         | 0.23%   |
| 111-120        | 1         | 0.23%   |
| 501-1000       | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 154       | 36.41%  |
| 101-120       | 122       | 28.84%  |
| 121-160       | 99        | 23.4%   |
| Unknown       | 20        | 4.73%   |
| 161-240       | 15        | 3.55%   |
| 1-50          | 10        | 2.36%   |
| More than 240 | 3         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 331       | 80.34%  |
| 2     | 58        | 14.08%  |
| 0     | 21        | 5.1%    |
| 3     | 2         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 216       | 32.73%  |
| Intel                             | 191       | 28.94%  |
| Qualcomm Atheros                  | 91        | 13.79%  |
| Broadcom                          | 39        | 5.91%   |
| TP-Link                           | 24        | 3.64%   |
| Ralink Technology                 | 19        | 2.88%   |
| D-Link                            | 11        | 1.67%   |
| Xiaomi                            | 9         | 1.36%   |
| Qualcomm Atheros Communications   | 9         | 1.36%   |
| MediaTek                          | 7         | 1.06%   |
| Ralink                            | 5         | 0.76%   |
| Nvidia                            | 5         | 0.76%   |
| Broadcom Limited                  | 5         | 0.76%   |
| ASIX Electronics                  | 4         | 0.61%   |
| Samsung Electronics               | 3         | 0.45%   |
| OPPO Electronics                  | 3         | 0.45%   |
| Huawei Technologies               | 3         | 0.45%   |
| InterBiometrics                   | 2         | 0.3%    |
| Aquantia                          | 2         | 0.3%    |
| Tehuti Networks                   | 1         | 0.15%   |
| Sundance Technology Inc / IC Plus | 1         | 0.15%   |
| Marvell Technology Group          | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| DisplayLink                       | 1         | 0.15%   |
| D-Link System                     | 1         | 0.15%   |
| Attansic Technology               | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |
| Apple                             | 1         | 0.15%   |
| American Megatrends               | 1         | 0.15%   |
| AboCom Systems                    | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 145       | 19.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 3.18%   |
| Intel Wi-Fi 6 AX200                                               | 16        | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 1.46%   |
| Realtek 802.11ac NIC                                              | 11        | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.46%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.46%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 1.32%   |
| TP-Link Archer T4U ver.3                                          | 9         | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.19%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 8         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.06%   |
| TP-Link 802.11n NIC                                               | 7         | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 7         | 0.93%   |
| Intel Wireless 7265                                               | 7         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6         | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 6         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                   | 6         | 0.79%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 6         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.66%   |
| Intel Wireless 3165                                               | 5         | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.66%   |
| Intel I211 Gigabit Network Connection                             | 5         | 0.66%   |
| Intel Ethernet Connection (11) I219-V                             | 5         | 0.66%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 128       | 35.46%  |
| Qualcomm Atheros                | 68        | 18.84%  |
| Realtek Semiconductor           | 58        | 16.07%  |
| Broadcom                        | 25        | 6.93%   |
| TP-Link                         | 24        | 6.65%   |
| Ralink Technology               | 19        | 5.26%   |
| D-Link                          | 11        | 3.05%   |
| Qualcomm Atheros Communications | 9         | 2.49%   |
| MediaTek                        | 7         | 1.94%   |
| Ralink                          | 5         | 1.39%   |
| Broadcom Limited                | 4         | 1.11%   |
| D-Link System                   | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |
| AboCom Systems                  | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 16        | 4.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 14        | 3.84%   |
| Realtek 802.11ac NIC                                                                 | 11        | 3.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 11        | 3.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 11        | 3.01%   |
| Intel Wireless 8265 / 8275                                                           | 11        | 3.01%   |
| TP-Link Archer T4U ver.3                                                             | 9         | 2.47%   |
| Ralink MT7601U Wireless Adapter                                                      | 9         | 2.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 8         | 2.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 8         | 2.19%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 8         | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 8         | 2.19%   |
| TP-Link 802.11n NIC                                                                  | 7         | 1.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 7         | 1.92%   |
| Intel Wireless 7265                                                                  | 7         | 1.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 6         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 6         | 1.64%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 6         | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 6         | 1.64%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 5         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 5         | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 5         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 5         | 1.37%   |
| Intel Wireless 3165                                                                  | 5         | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 5         | 1.37%   |
| Intel Centrino Wireless-N 2230                                                       | 5         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                             | 5         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 5         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 4         | 1.1%    |
| Intel Wireless-AC 9260                                                               | 4         | 1.1%    |
| Intel Wireless 7260                                                                  | 4         | 1.1%    |
| Intel Wireless 3160                                                                  | 4         | 1.1%    |
| Intel Wi-Fi 6 AX201                                                                  | 4         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                                       | 4         | 1.1%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 4         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3         | 0.82%   |
| Ralink RT5572 Wireless Adapter                                                       | 3         | 0.82%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 189       | 50.4%   |
| Intel                             | 103       | 27.47%  |
| Qualcomm Atheros                  | 28        | 7.47%   |
| Broadcom                          | 18        | 4.8%    |
| Xiaomi                            | 9         | 2.4%    |
| Nvidia                            | 5         | 1.33%   |
| ASIX Electronics                  | 4         | 1.07%   |
| OPPO Electronics                  | 3         | 0.8%    |
| Huawei Technologies               | 3         | 0.8%    |
| Samsung Electronics               | 2         | 0.53%   |
| Aquantia                          | 2         | 0.53%   |
| Tehuti Networks                   | 1         | 0.27%   |
| Sundance Technology Inc / IC Plus | 1         | 0.27%   |
| Marvell Technology Group          | 1         | 0.27%   |
| JMicron Technology                | 1         | 0.27%   |
| DisplayLink                       | 1         | 0.27%   |
| Broadcom Limited                  | 1         | 0.27%   |
| Attansic Technology               | 1         | 0.27%   |
| Apple                             | 1         | 0.27%   |
| American Megatrends               | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 145       | 37.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 6.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 4.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 3.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.85%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.3%    |
| Intel I211 Gigabit Network Connection                             | 5         | 1.3%    |
| Intel Ethernet Connection (11) I219-V                             | 5         | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.04%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 1.04%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.04%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4         | 1.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.78%   |
| OPPO CPH2411                                                      | 3         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.78%   |
| Huawei LLD-L21                                                    | 3         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.52%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.52%   |
| Intel I350 Gigabit Fiber Network Connection                       | 2         | 0.52%   |
| Intel Ethernet Controller X550                                    | 2         | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 343       | 50.59%  |
| WiFi     | 331       | 48.82%  |
| Modem    | 4         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 265       | 63.86%  |
| Ethernet | 150       | 36.14%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 215       | 52.57%  |
| 1     | 154       | 37.65%  |
| 0     | 23        | 5.62%   |
| 3     | 12        | 2.93%   |
| 4     | 2         | 0.49%   |
| 9     | 1         | 0.24%   |
| 8     | 1         | 0.24%   |
| 5     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 300       | 71.43%  |
| Yes  | 120       | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 102       | 40.32%  |
| Cambridge Silicon Radio         | 24        | 9.49%   |
| Realtek Semiconductor           | 20        | 7.91%   |
| Qualcomm Atheros Communications | 18        | 7.11%   |
| IMC Networks                    | 16        | 6.32%   |
| Broadcom                        | 14        | 5.53%   |
| Foxconn / Hon Hai               | 13        | 5.14%   |
| Apple                           | 12        | 4.74%   |
| Lite-On Technology              | 10        | 3.95%   |
| Dell                            | 5         | 1.98%   |
| Hewlett-Packard                 | 4         | 1.58%   |
| Realtek                         | 3         | 1.19%   |
| TP-Link                         | 2         | 0.79%   |
| Ralink                          | 2         | 0.79%   |
| MediaTek                        | 2         | 0.79%   |
| D-Link                          | 2         | 0.79%   |
| Ralink Technology               | 1         | 0.4%    |
| ASUSTek Computer                | 1         | 0.4%    |
| Askey Computer                  | 1         | 0.4%    |
| Alps Electric                   | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 33        | 13.04%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 24        | 9.49%   |
| Intel AX201 Bluetooth                                                               | 17        | 6.72%   |
| Intel AX200 Bluetooth                                                               | 17        | 6.72%   |
| Realtek Bluetooth Radio                                                             | 12        | 4.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 12        | 4.74%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 2.77%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 2.37%   |
| IMC Networks Bluetooth Device                                                       | 6         | 2.37%   |
| Apple Bluetooth Host Controller                                                     | 6         | 2.37%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.98%   |
| Intel AX210 Bluetooth                                                               | 5         | 1.98%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 1.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1.58%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.58%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.58%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.58%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.19%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.19%   |
| Intel Bluetooth Device                                                              | 3         | 1.19%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.19%   |
| TP-Link UB500 Adapter                                                               | 2         | 0.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.79%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.79%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.79%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.79%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.79%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.79%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.79%   |
| D-Link DBT-122 Bluetooth adapter                                                    | 2         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 300       | 54.15%  |
| AMD                         | 105       | 18.95%  |
| Nvidia                      | 104       | 18.77%  |
| C-Media Electronics         | 8         | 1.44%   |
| Logitech                    | 7         | 1.26%   |
| JMTek                       | 4         | 0.72%   |
| ASUSTek Computer            | 3         | 0.54%   |
| Texas Instruments           | 2         | 0.36%   |
| Samsung Electronics         | 2         | 0.36%   |
| RODE Microphones            | 2         | 0.36%   |
| Realtek Semiconductor       | 2         | 0.36%   |
| Generalplus Technology      | 2         | 0.36%   |
| Setek Elektronik            | 1         | 0.18%   |
| Razer USA                   | 1         | 0.18%   |
| Plantronics                 | 1         | 0.18%   |
| MVSILICON.INC.              | 1         | 0.18%   |
| MosArt Semiconductor        | 1         | 0.18%   |
| GYROCOM C&C                 | 1         | 0.18%   |
| GN Netcom                   | 1         | 0.18%   |
| FiiO Electronics Technology | 1         | 0.18%   |
| DCMT Technology             | 1         | 0.18%   |
| Creative Labs               | 1         | 0.18%   |
| Cooler Master               | 1         | 0.18%   |
| Cambridge Audio             | 1         | 0.18%   |
| Barco Display Systems       | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 42        | 6.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 42        | 6.47%   |
| AMD Family 17h/19h HD Audio Controller                                            | 37        | 5.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 29        | 4.47%   |
| Intel Sunrise Point-LP HD Audio                                                   | 27        | 4.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 19        | 2.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 18        | 2.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 18        | 2.77%   |
| Nvidia GF108 High Definition Audio Controller                                     | 16        | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                        | 15        | 2.31%   |
| AMD Starship/Matisse HD Audio Controller                                          | 15        | 2.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 15        | 2.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 13        | 2%      |
| AMD FCH Azalia Controller                                                         | 10        | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9         | 1.39%   |
| Intel 8 Series HD Audio Controller                                                | 9         | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9         | 1.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9         | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 8         | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                             | 8         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                         | 8         | 1.23%   |
| Intel Broadwell-U Audio Controller                                                | 8         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7         | 1.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 7         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 6         | 0.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 6         | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 6         | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6         | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6         | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5         | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5         | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5         | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                                     | 5         | 0.77%   |
| AMD Trinity HDMI Audio Controller                                                 | 5         | 0.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5         | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                          | 5         | 0.77%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 69        | 27.71%  |
| Samsung Electronics | 42        | 16.87%  |
| SK hynix            | 40        | 16.06%  |
| Corsair             | 18        | 7.23%   |
| Micron Technology   | 16        | 6.43%   |
| Unknown             | 11        | 4.42%   |
| Nanya Technology    | 7         | 2.81%   |
| A-DATA Technology   | 7         | 2.81%   |
| Kingmax             | 5         | 2.01%   |
| Apacer              | 5         | 2.01%   |
| Ramaxel Technology  | 4         | 1.61%   |
| Unknown (ABCD)      | 3         | 1.2%    |
| Team                | 3         | 1.2%    |
| Crucial             | 3         | 1.2%    |
| Silicon Power       | 2         | 0.8%    |
| Kimtigo             | 2         | 0.8%    |
| G.Skill             | 2         | 0.8%    |
| Elpida              | 2         | 0.8%    |
| Unknown (08AE)      | 1         | 0.4%    |
| Transcend           | 1         | 0.4%    |
| SemsoTai            | 1         | 0.4%    |
| PNY                 | 1         | 0.4%    |
| Patriot Memory      | 1         | 0.4%    |
| MAXSUN              | 1         | 0.4%    |
| Kinlstuo            | 1         | 0.4%    |
| Hewlett-Packard     | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s              | 6         | 2.26%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 5         | 1.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.51%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 4         | 1.51%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 3         | 1.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.13%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 1.13%   |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                 | 3         | 1.13%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 0.75%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.75%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.75%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.75%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.75%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.75%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.75%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.75%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.75%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.75%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.75%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.75%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 2         | 0.75%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s            | 2         | 0.75%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 2         | 0.75%   |
| Kingston RAM 99U5428-082.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.75%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 0.75%   |
| Kingmax RAM FLFE85F-C8KM9 2GB DIMM DDR3 1333MT/s                 | 2         | 0.75%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.75%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.75%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.38%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 86        | 41.75%  |
| DDR3    | 84        | 40.78%  |
| SDRAM   | 14        | 6.8%    |
| DDR2    | 7         | 3.4%    |
| LPDDR4  | 6         | 2.91%   |
| LPDDR3  | 4         | 1.94%   |
| DDR5    | 2         | 0.97%   |
| Unknown | 2         | 0.97%   |
| DDR     | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 114       | 55.88%  |
| DIMM         | 81        | 39.71%  |
| Row Of Chips | 8         | 3.92%   |
| FB-DIMM      | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 79        | 34.96%  |
| 4096  | 68        | 30.09%  |
| 2048  | 33        | 14.6%   |
| 16384 | 24        | 10.62%  |
| 32768 | 17        | 7.52%   |
| 1024  | 5         | 2.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 56        | 24.89%  |
| 3200    | 32        | 14.22%  |
| 2667    | 32        | 14.22%  |
| 1333    | 17        | 7.56%   |
| 1334    | 15        | 6.67%   |
| 2400    | 14        | 6.22%   |
| 2133    | 8         | 3.56%   |
| 3600    | 6         | 2.67%   |
| 667     | 6         | 2.67%   |
| 800     | 5         | 2.22%   |
| Unknown | 5         | 2.22%   |
| 1067    | 4         | 1.78%   |
| 4800    | 2         | 0.89%   |
| 4267    | 2         | 0.89%   |
| 4199    | 2         | 0.89%   |
| 3933    | 2         | 0.89%   |
| 1867    | 2         | 0.89%   |
| 1800    | 2         | 0.89%   |
| 1066    | 2         | 0.89%   |
| 8400    | 1         | 0.44%   |
| 5600    | 1         | 0.44%   |
| 3534    | 1         | 0.44%   |
| 3466    | 1         | 0.44%   |
| 3333    | 1         | 0.44%   |
| 3266    | 1         | 0.44%   |
| 3000    | 1         | 0.44%   |
| 2933    | 1         | 0.44%   |
| 2134    | 1         | 0.44%   |
| 2048    | 1         | 0.44%   |
| 1866    | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 3         | 21.43%  |
| Samsung Electronics | 3         | 21.43%  |
| Canon               | 3         | 21.43%  |
| Brother Industries  | 3         | 21.43%  |
| Prolific Technology | 1         | 7.14%   |
| Hewlett-Packard     | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-3400 Series       | 3         | 21.43%  |
| Canon E410 series             | 2         | 14.29%  |
| Seiko Epson L310 Series       | 1         | 7.14%   |
| Seiko Epson L210 Series       | 1         | 7.14%   |
| Seiko Epson ET-2710 Series    | 1         | 7.14%   |
| Prolific PL2305 Parallel Port | 1         | 7.14%   |
| HP Ink Tank 110 series        | 1         | 7.14%   |
| Canon LBP6030w/6018w          | 1         | 7.14%   |
| Brother DCP-J105              | 1         | 7.14%   |
| Brother DCP-1610W             | 1         | 7.14%   |
| Brother DCP-1510              | 1         | 7.14%   |

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
| Chicony Electronics                    | 41        | 18.22%  |
| Microdia                               | 26        | 11.56%  |
| IMC Networks                           | 21        | 9.33%   |
| Realtek Semiconductor                  | 17        | 7.56%   |
| Sunplus Innovation Technology          | 16        | 7.11%   |
| Logitech                               | 13        | 5.78%   |
| Suyin                                  | 11        | 4.89%   |
| Bison Electronics                      | 11        | 4.89%   |
| Apple                                  | 10        | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.56%   |
| Generalplus Technology                 | 7         | 3.11%   |
| Quanta                                 | 6         | 2.67%   |
| Alcor Micro                            | 4         | 1.78%   |
| Acer                                   | 4         | 1.78%   |
| YGTek                                  | 3         | 1.33%   |
| Syntek                                 | 3         | 1.33%   |
| Silicon Motion                         | 3         | 1.33%   |
| Luxvisions Innotech Limited            | 3         | 1.33%   |
| Lite-On Technology                     | 3         | 1.33%   |
| Lenovo                                 | 2         | 0.89%   |
| Z-Star Microelectronics                | 1         | 0.44%   |
| WCM_USB                                | 1         | 0.44%   |
| vivo                                   | 1         | 0.44%   |
| USB Camera                             | 1         | 0.44%   |
| Sonix Technology                       | 1         | 0.44%   |
| Samsung Electronics                    | 1         | 0.44%   |
| Ricoh                                  | 1         | 0.44%   |
| Primax Electronics                     | 1         | 0.44%   |
| OmniVision Technologies                | 1         | 0.44%   |
| Jieli Technology                       | 1         | 0.44%   |
| eMPIA Technology                       | 1         | 0.44%   |
| Cubeternet                             | 1         | 0.44%   |
| ARC International                      | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 11        | 4.89%   |
| Chicony USB2.0 VGA UVC WebCam                           | 9         | 4%      |
| Sunplus Integrated_Webcam_HD                            | 5         | 2.22%   |
| Chicony Integrated Camera                               | 5         | 2.22%   |
| Chicony HD WebCam                                       | 5         | 2.22%   |
| Realtek Integrated_Webcam_HD                            | 4         | 1.78%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 4         | 1.78%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.78%   |
| Generalplus GENERAL WEBCAM                              | 4         | 1.78%   |
| Chicony USB2.0 HD UVC WebCam                            | 4         | 1.78%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 4         | 1.78%   |
| YGTek Webcam                                            | 3         | 1.33%   |
| Logitech Webcam C270                                    | 3         | 1.33%   |
| Logitech HD Pro Webcam C920                             | 3         | 1.33%   |
| IMC Networks Integrated Camera                          | 3         | 1.33%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.33%   |
| Chicony HP HD Webcam                                    | 3         | 1.33%   |
| Apple FaceTime HD Camera                                | 3         | 1.33%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 0.89%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 0.89%   |
| Suyin 1.3M HD WebCam                                    | 2         | 0.89%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 0.89%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 0.89%   |
| Realtek USB Camera                                      | 2         | 0.89%   |
| Realtek HD WebCam                                       | 2         | 0.89%   |
| Quanta HP TrueVision HD Camera                          | 2         | 0.89%   |
| Quanta HD Webcam                                        | 2         | 0.89%   |
| Microdia Webcam Vitade AF                               | 2         | 0.89%   |
| Microdia USB 2.0 Camera                                 | 2         | 0.89%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.89%   |
| Logitech Webcam C170                                    | 2         | 0.89%   |
| Lite-On Integrated Camera                               | 2         | 0.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 0.89%   |
| IMC Networks ov9734_azurewave_camera                    | 2         | 0.89%   |
| Generalplus 808 Camera #9 (web-cam mode)                | 2         | 0.89%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.89%   |
| Bison Integrated Camera                                 | 2         | 0.89%   |
| Bison EasyCamera                                        | 2         | 0.89%   |
| Bison BisonCam,NB Pro                                   | 2         | 0.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 25.81%  |
| Synaptics                  | 7         | 22.58%  |
| Shenzhen Goodix Technology | 6         | 19.35%  |
| Elan Microelectronics      | 3         | 9.68%   |
| AuthenTec                  | 3         | 9.68%   |
| Upek                       | 2         | 6.45%   |
| LighTuning Technology      | 1         | 3.23%   |
| Focal-systems.Corp         | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                          | 3         | 9.68%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 2         | 6.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 6.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 2         | 6.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 2         | 6.45%   |
| Shenzhen Goodix  Fingerprint Device                         | 2         | 6.45%   |
| Elan ELAN:ARM-M4                                            | 2         | 6.45%   |
| Validity Sensors VFS491                                     | 1         | 3.23%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 3.23%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 1         | 3.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 3.23%   |
| Validity Sensors Fingerprint scanner                        | 1         | 3.23%   |
| Synaptics WBDI Fingerprint Reader USB 086                   | 1         | 3.23%   |
| Synaptics  WBDI                                             | 1         | 3.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 3.23%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 1         | 3.23%   |
| Focal-systems.Corp FT9201Fingerprint.                       | 1         | 3.23%   |
| Elan ELAN:Fingerprint                                       | 1         | 3.23%   |
| AuthenTec Fingerprint Sensor                                | 1         | 3.23%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 3.23%   |
| AuthenTec AES1660 Fingerprint Sensor                        | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 75%     |
| O2 Micro    | 1         | 8.33%   |
| Lenovo      | 1         | 8.33%   |
| Alcor Micro | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Broadcom 58200                                                               | 2         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Broadcom 5880                                                                | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 306       | 73.56%  |
| 1     | 93        | 22.36%  |
| 2     | 13        | 3.13%   |
| 3     | 2         | 0.48%   |
| 6     | 1         | 0.24%   |
| 4     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 24.6%   |
| Graphics card            | 30        | 23.81%  |
| Net/wireless             | 24        | 19.05%  |
| Chipcard                 | 10        | 7.94%   |
| Multimedia controller    | 8         | 6.35%   |
| Communication controller | 5         | 3.97%   |
| Unassigned class         | 3         | 2.38%   |
| Storage                  | 3         | 2.38%   |
| Bluetooth                | 3         | 2.38%   |
| Storage/ide              | 2         | 1.59%   |
| Sound                    | 2         | 1.59%   |
| Net/ethernet             | 2         | 1.59%   |
| Network                  | 1         | 0.79%   |
| Card reader              | 1         | 0.79%   |
| Camera                   | 1         | 0.79%   |

