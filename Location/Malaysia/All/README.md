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

Total: 597

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 60        | 13.67%  |
| Ubuntu 18.04        | 24        | 5.47%   |
| Ubuntu 22.04        | 20        | 4.56%   |
| Debian 11           | 14        | 3.19%   |
| Zorin 16            | 11        | 2.51%   |
| Pop!_OS 22.04       | 11        | 2.51%   |
| OpenMandriva 4.3    | 11        | 2.51%   |
| OpenMandriva 4.2    | 11        | 2.51%   |
| Pop!_OS 20.10       | 10        | 2.28%   |
| Pop!_OS 21.04       | 9         | 2.05%   |
| OpenMandriva 4.50   | 9         | 2.05%   |
| OpenMandriva 23.01  | 9         | 2.05%   |
| KDE neon 20.04      | 9         | 2.05%   |
| ArcoLinux Rolling   | 9         | 2.05%   |
| Pop!_OS 20.04       | 8         | 1.82%   |
| Fedora 33           | 8         | 1.82%   |
| Ubuntu 19.04        | 7         | 1.59%   |
| OpenMandriva 23.03  | 7         | 1.59%   |
| Fedora 37           | 7         | 1.59%   |
| Linux Mint 19.3     | 6         | 1.37%   |
| Fedora 34           | 6         | 1.37%   |
| Linux Mint 21.1     | 5         | 1.14%   |
| Arch                | 5         | 1.14%   |
| Zorin 15            | 4         | 0.91%   |
| Ubuntu 21.04        | 4         | 0.91%   |
| Ubuntu 20.10        | 4         | 0.91%   |
| Ubuntu 19.10        | 4         | 0.91%   |
| Ubuntu 16.04        | 4         | 0.91%   |
| Manjaro             | 4         | 0.91%   |
| Linux Mint 20.2     | 4         | 0.91%   |
| EndeavourOS Rolling | 4         | 0.91%   |
| Elementary 6.1      | 4         | 0.91%   |
| Elementary 5.1.7    | 4         | 0.91%   |
| Arch Rolling        | 4         | 0.91%   |
| Xubuntu 22.04       | 3         | 0.68%   |
| Xubuntu 18.04       | 3         | 0.68%   |
| Ubuntu 21.10        | 3         | 0.68%   |
| Linux Mint 20.1     | 3         | 0.68%   |
| KDE neon 22.04      | 3         | 0.68%   |
| Fedora 35           | 3         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 128       | 30.55%  |
| OpenMandriva  | 44        | 10.5%   |
| Pop!_OS       | 36        | 8.59%   |
| Fedora        | 28        | 6.68%   |
| Linux Mint    | 22        | 5.25%   |
| Zorin         | 16        | 3.82%   |
| Debian        | 16        | 3.82%   |
| Manjaro       | 13        | 3.1%    |
| KDE neon      | 13        | 3.1%    |
| Elementary    | 11        | 2.63%   |
| ArcoLinux     | 9         | 2.15%   |
| Arch          | 9         | 2.15%   |
| Endless       | 8         | 1.91%   |
| Xubuntu       | 7         | 1.67%   |
| Lubuntu       | 7         | 1.67%   |
| Kubuntu       | 6         | 1.43%   |
| Kali          | 5         | 1.19%   |
| EndeavourOS   | 5         | 1.19%   |
| CentOS        | 4         | 0.95%   |
| SteamOS       | 3         | 0.72%   |
| Android       | 3         | 0.72%   |
| Ubuntu Unity  | 2         | 0.48%   |
| Ubuntu MATE   | 2         | 0.48%   |
| Ubuntu Budgie | 2         | 0.48%   |
| ROSA          | 2         | 0.48%   |
| openSUSE      | 2         | 0.48%   |
| Nobara        | 2         | 0.48%   |
| Gentoo        | 2         | 0.48%   |
| Xero          | 1         | 0.24%   |
| Ultramarine   | 1         | 0.24%   |
| Rocky Linux   | 1         | 0.24%   |
| Reborn OS     | 1         | 0.24%   |
| Raspbian      | 1         | 0.24%   |
| Peppermint    | 1         | 0.24%   |
| MX            | 1         | 0.24%   |
| LMDE          | 1         | 0.24%   |
| Linux Lite    | 1         | 0.24%   |
| BuildRoot     | 1         | 0.24%   |
| Axyl          | 1         | 0.24%   |
| Archcraft     | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 10        | 2.12%   |
| 5.16.7-desktop-1omv4003  | 9         | 1.91%   |
| 6.2.6-desktop-1omv2390   | 8         | 1.7%    |
| 5.4.0-58-generic         | 8         | 1.7%    |
| 5.4.0-42-generic         | 8         | 1.7%    |
| 6.1.1-desktop-1omv2290   | 6         | 1.27%   |
| 5.15.0-58-generic        | 6         | 1.27%   |
| 5.15.0-52-generic        | 6         | 1.27%   |
| 5.13.19-6-pve            | 6         | 1.27%   |
| 5.11.0-7620-generic      | 6         | 1.27%   |
| 5.12.4-desktop-1omv4050  | 5         | 1.06%   |
| 5.11.0-27-generic        | 5         | 1.06%   |
| 5.4.0-7634-generic       | 4         | 0.85%   |
| 5.4.0-40-generic         | 4         | 0.85%   |
| 5.15.0-56-generic        | 4         | 0.85%   |
| 5.0.0-37-generic         | 4         | 0.85%   |
| 6.2.6-76060206-generic   | 3         | 0.64%   |
| 6.0.12-76060006-generic  | 3         | 0.64%   |
| 5.8.0-7642-generic       | 3         | 0.64%   |
| 5.8.0-7630-generic       | 3         | 0.64%   |
| 5.4.0-54-generic         | 3         | 0.64%   |
| 5.4.0-52-generic         | 3         | 0.64%   |
| 5.4.0-48-generic         | 3         | 0.64%   |
| 5.4.0-37-generic         | 3         | 0.64%   |
| 5.3.0-53-generic         | 3         | 0.64%   |
| 5.3.0-46-generic         | 3         | 0.64%   |
| 5.19.0-38-generic        | 3         | 0.64%   |
| 5.19.0-32-generic        | 3         | 0.64%   |
| 5.16.3-desktop-2omv4050  | 3         | 0.64%   |
| 5.15.0-46-generic        | 3         | 0.64%   |
| 5.15.0-40-generic        | 3         | 0.64%   |
| 5.15.0-39-generic        | 3         | 0.64%   |
| 5.15.0-25-generic        | 3         | 0.64%   |
| 5.13.0-7614-generic      | 3         | 0.64%   |
| 5.13.0-22-generic        | 3         | 0.64%   |
| 5.11.0-7614-generic      | 3         | 0.64%   |
| 5.11.0-46-generic        | 3         | 0.64%   |
| 5.11.0-43-generic        | 3         | 0.64%   |
| 5.11.0-34-generic        | 3         | 0.64%   |
| 5.0.0-32-generic         | 3         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 15.18%  |
| 5.15.0  | 36        | 8.04%   |
| 5.11.0  | 30        | 6.7%    |
| 5.8.0   | 26        | 5.8%    |
| 4.15.0  | 20        | 4.46%   |
| 5.3.0   | 19        | 4.24%   |
| 5.13.0  | 19        | 4.24%   |
| 5.0.0   | 18        | 4.02%   |
| 6.2.6   | 11        | 2.46%   |
| 5.19.0  | 11        | 2.46%   |
| 5.10.14 | 10        | 2.23%   |
| 5.16.7  | 9         | 2.01%   |
| 6.1.1   | 7         | 1.56%   |
| 5.10.0  | 7         | 1.56%   |
| 5.13.19 | 6         | 1.34%   |
| 4.18.0  | 6         | 1.34%   |
| 6.0.12  | 5         | 1.12%   |
| 5.17.1  | 5         | 1.12%   |
| 5.12.4  | 5         | 1.12%   |
| 5.18.0  | 4         | 0.89%   |
| 5.9.0   | 3         | 0.67%   |
| 5.16.3  | 3         | 0.67%   |
| 5.16.15 | 3         | 0.67%   |
| 6.2.8   | 2         | 0.45%   |
| 6.1.4   | 2         | 0.45%   |
| 5.9.1   | 2         | 0.45%   |
| 5.19.9  | 2         | 0.45%   |
| 5.19.12 | 2         | 0.45%   |
| 5.17.6  | 2         | 0.45%   |
| 5.17.5  | 2         | 0.45%   |
| 5.15.35 | 2         | 0.45%   |
| 5.14.18 | 2         | 0.45%   |
| 5.14.0  | 2         | 0.45%   |
| 5.13.13 | 2         | 0.45%   |
| 5.12.9  | 2         | 0.45%   |
| 5.12.7  | 2         | 0.45%   |
| 5.12.15 | 2         | 0.45%   |
| 5.11.18 | 2         | 0.45%   |
| 5.10.79 | 2         | 0.45%   |
| 5.10.42 | 2         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 15.38%  |
| 5.15    | 49        | 11.09%  |
| 5.11    | 35        | 7.92%   |
| 5.8     | 33        | 7.47%   |
| 5.13    | 28        | 6.33%   |
| 5.10    | 27        | 6.11%   |
| 4.15    | 20        | 4.52%   |
| 5.3     | 19        | 4.3%    |
| 5.19    | 18        | 4.07%   |
| 5.0     | 18        | 4.07%   |
| 6.2     | 17        | 3.85%   |
| 5.16    | 17        | 3.85%   |
| 5.12    | 13        | 2.94%   |
| 6.1     | 11        | 2.49%   |
| 6.0     | 10        | 2.26%   |
| 5.18    | 9         | 2.04%   |
| 5.17    | 9         | 2.04%   |
| 5.9     | 8         | 1.81%   |
| 5.14    | 8         | 1.81%   |
| 4.18    | 6         | 1.36%   |
| 6.3     | 4         | 0.9%    |
| 3.10    | 3         | 0.68%   |
| 5.7     | 2         | 0.45%   |
| 5.6     | 2         | 0.45%   |
| 4.4     | 2         | 0.45%   |
| 3.18    | 2         | 0.45%   |
| 4.9     | 1         | 0.23%   |
| 4.19    | 1         | 0.23%   |
| 4.10    | 1         | 0.23%   |
| 4.1     | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 390       | 97.5%   |
| i686   | 5         | 1.25%   |
| armv8l | 3         | 0.75%   |
| armv7l | 2         | 0.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 187       | 44.74%  |
| KDE5          | 80        | 19.14%  |
| Unknown       | 41        | 9.81%   |
| XFCE          | 27        | 6.46%   |
| X-Cinnamon    | 19        | 4.55%   |
| KDE           | 13        | 3.11%   |
| Pantheon      | 11        | 2.63%   |
| Openbox       | 11        | 2.63%   |
| MATE          | 10        | 2.39%   |
| LXQt          | 6         | 1.44%   |
| Unity         | 2         | 0.48%   |
| LXDE          | 2         | 0.48%   |
| GNOME Classic | 2         | 0.48%   |
| Budgie        | 2         | 0.48%   |
| Peppermint    | 1         | 0.24%   |
| i3            | 1         | 0.24%   |
| Hyprland      | 1         | 0.24%   |
| Cinnamon      | 1         | 0.24%   |
| bspwm         | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 324       | 78.07%  |
| Wayland | 59        | 14.22%  |
| Unknown | 20        | 4.82%   |
| Tty     | 12        | 2.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 219       | 53.16%  |
| SDDM    | 78        | 18.93%  |
| GDM3    | 39        | 9.47%   |
| GDM     | 37        | 8.98%   |
| LightDM | 32        | 7.77%   |
| TDM     | 5         | 1.21%   |
| LXDM    | 2         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 316       | 77.64%  |
| Unknown | 31        | 7.62%   |
| en_GB   | 27        | 6.63%   |
| en_SG   | 15        | 3.69%   |
| en_AU   | 3         | 0.74%   |
| C       | 3         | 0.74%   |
| zh_CN   | 2         | 0.49%   |
| ms_MY   | 2         | 0.49%   |
| en_MY   | 2         | 0.49%   |
| zh_TW   | 1         | 0.25%   |
| zh_SG   | 1         | 0.25%   |
| ja_JP   | 1         | 0.25%   |
| id_ID   | 1         | 0.25%   |
| en_HK   | 1         | 0.25%   |
| de_DE   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 220       | 54.19%  |
| EFI  | 186       | 45.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 302       | 74.02%  |
| Overlay | 35        | 8.58%   |
| Btrfs   | 34        | 8.33%   |
| Zfs     | 13        | 3.19%   |
| Unknown | 12        | 2.94%   |
| Xfs     | 9         | 2.21%   |
| Ext2    | 2         | 0.49%   |
| Ext3    | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 228       | 55.75%  |
| GPT     | 131       | 32.03%  |
| MBR     | 50        | 12.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 329       | 80.24%  |
| Yes       | 81        | 19.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 274       | 66.83%  |
| Yes       | 136       | 33.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 73        | 18.25%  |
| Dell                    | 68        | 17%     |
| Hewlett-Packard         | 51        | 12.75%  |
| Lenovo                  | 39        | 9.75%   |
| Gigabyte Technology     | 37        | 9.25%   |
| MSI                     | 25        | 6.25%   |
| Acer                    | 23        | 5.75%   |
| Intel                   | 15        | 3.75%   |
| Apple                   | 8         | 2%      |
| ASRock                  | 6         | 1.5%    |
| Unknown                 | 6         | 1.5%    |
| Biostar                 | 5         | 1.25%   |
| Sony                    | 4         | 1%      |
| Fujitsu                 | 4         | 1%      |
| Samsung Electronics     | 3         | 0.75%   |
| HUAWEI                  | 3         | 0.75%   |
| Raspberry Pi Foundation | 2         | 0.5%    |
| NEC Computers           | 2         | 0.5%    |
| ILLEGEAR                | 2         | 0.5%    |
| ECS                     | 2         | 0.5%    |
| Chuwi                   | 2         | 0.5%    |
| Acidanthera             | 2         | 0.5%    |
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
| HONOR                   | 1         | 0.25%   |
| GPD                     | 1         | 0.25%   |
| BUSH                    | 1         | 0.25%   |
| AZW                     | 1         | 0.25%   |
| ASRockRack              | 1         | 0.25%   |
| AMI                     | 1         | 0.25%   |
| Alienware               | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| ASUS All Series                   | 8         | 2%      |
| Intel DH61WW AAG23116-204         | 7         | 1.75%   |
| Gigabyte Z77M-D3H                 | 6         | 1.5%    |
| Unknown                           | 6         | 1.5%    |
| HP Notebook                       | 5         | 1.25%   |
| Gigabyte B85M-D3H                 | 5         | 1.25%   |
| MSI MS-7C52                       | 4         | 1%      |
| MSI MS-7817                       | 3         | 0.75%   |
| Intel DH61WW AAG23116-300         | 3         | 0.75%   |
| Dell OptiPlex 755                 | 3         | 0.75%   |
| MSI MS-7C81                       | 2         | 0.5%    |
| MSI MS-7B89                       | 2         | 0.5%    |
| MSI Modern 14 B5M                 | 2         | 0.5%    |
| Intel MAHOBAY                     | 2         | 0.5%    |
| HP Pavilion dv6                   | 2         | 0.5%    |
| HP Laptop 15-bs0xx                | 2         | 0.5%    |
| HP ENVY 4                         | 2         | 0.5%    |
| HP EliteBook 8470p                | 2         | 0.5%    |
| HP EliteBook 840 G2               | 2         | 0.5%    |
| HP Compaq Presario CQ40           | 2         | 0.5%    |
| Gigabyte X570 UD                  | 2         | 0.5%    |
| Gigabyte B450M S2H                | 2         | 0.5%    |
| Dell XPS 8940                     | 2         | 0.5%    |
| Dell XPS 15 7590                  | 2         | 0.5%    |
| Dell OptiPlex 990                 | 2         | 0.5%    |
| Dell Latitude E6520               | 2         | 0.5%    |
| Dell Latitude E6440               | 2         | 0.5%    |
| Dell Latitude 3410                | 2         | 0.5%    |
| Biostar G41D3C                    | 2         | 0.5%    |
| ASUS Pro WS WRX80E-SAGE SE WIFI   | 2         | 0.5%    |
| ASUS P8Z77-V LX                   | 2         | 0.5%    |
| ASUS K45VD                        | 2         | 0.5%    |
| ASUS K43SD                        | 2         | 0.5%    |
| Apple MacBookPro8,1               | 2         | 0.5%    |
| Vorke V1 Plus                     | 1         | 0.25%   |
| Valve Jupiter                     | 1         | 0.25%   |
| Toshiba dynabook Satellite B552/H | 1         | 0.25%   |
| Timi RedmiBook 14 II              | 1         | 0.25%   |
| Teclast F5                        | 1         | 0.25%   |
| System76 Galago Pro               | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Latitude       | 20        | 5%      |
| Dell Inspiron       | 18        | 4.5%    |
| Lenovo ThinkPad     | 17        | 4.25%   |
| Acer Aspire         | 14        | 3.5%    |
| Dell OptiPlex       | 11        | 2.75%   |
| Intel DH61WW        | 10        | 2.5%    |
| HP Pavilion         | 8         | 2%      |
| HP Compaq           | 8         | 2%      |
| Dell XPS            | 8         | 2%      |
| ASUS All            | 8         | 2%      |
| HP EliteBook        | 7         | 1.75%   |
| Dell Precision      | 7         | 1.75%   |
| Gigabyte Z77M-D3H   | 6         | 1.5%    |
| Unknown             | 6         | 1.5%    |
| Lenovo IdeaPad      | 5         | 1.25%   |
| HP Notebook         | 5         | 1.25%   |
| HP Laptop           | 5         | 1.25%   |
| Gigabyte B85M-D3H   | 5         | 1.25%   |
| ASUS ROG            | 5         | 1.25%   |
| MSI MS-7C52         | 4         | 1%      |
| Gigabyte X570       | 4         | 1%      |
| ASUS VivoBook       | 4         | 1%      |
| ASUS TUF            | 4         | 1%      |
| MSI MS-7817         | 3         | 0.75%   |
| Lenovo ThinkStation | 3         | 0.75%   |
| Lenovo ThinkCentre  | 3         | 0.75%   |
| HP ENVY             | 3         | 0.75%   |
| Gigabyte B450M      | 3         | 0.75%   |
| Fujitsu LIFEBOOK    | 3         | 0.75%   |
| ASUS P8B75-M        | 3         | 0.75%   |
| Apple MacBookPro8   | 3         | 0.75%   |
| RPi Raspberry       | 2         | 0.5%    |
| MSI MS-7C81         | 2         | 0.5%    |
| MSI MS-7B89         | 2         | 0.5%    |
| MSI Modern          | 2         | 0.5%    |
| Lenovo Yoga         | 2         | 0.5%    |
| Intel MAHOBAY       | 2         | 0.5%    |
| HP ProLiant         | 2         | 0.5%    |
| HP ProBook          | 2         | 0.5%    |
| Biostar G41D3C      | 2         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 43        | 10.75%  |
| 2013    | 40        | 10%     |
| 2019    | 38        | 9.5%    |
| 2012    | 37        | 9.25%   |
| 2018    | 35        | 8.75%   |
| 2020    | 33        | 8.25%   |
| 2021    | 30        | 7.5%    |
| 2015    | 25        | 6.25%   |
| 2017    | 22        | 5.5%    |
| 2010    | 20        | 5%      |
| 2008    | 17        | 4.25%   |
| 2014    | 16        | 4%      |
| 2009    | 12        | 3%      |
| 2016    | 10        | 2.5%    |
| 2007    | 10        | 2.5%    |
| 2022    | 6         | 1.5%    |
| Unknown | 4         | 1%      |
| 2023    | 1         | 0.25%   |
| 2006    | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 207       | 51.75%  |
| Desktop        | 160       | 40%     |
| Convertible    | 9         | 2.25%   |
| All in one     | 7         | 1.75%   |
| Server         | 5         | 1.25%   |
| Tablet         | 4         | 1%      |
| Phone          | 3         | 0.75%   |
| Mini pc        | 3         | 0.75%   |
| System on chip | 2         | 0.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 373       | 93.25%  |
| Enabled  | 27        | 6.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 398       | 99.5%   |
| Yes  | 2         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 92        | 22.77%  |
| 3.01-4.0    | 79        | 19.55%  |
| 16.01-24.0  | 78        | 19.31%  |
| 8.01-16.0   | 76        | 18.81%  |
| 32.01-64.0  | 32        | 7.92%   |
| 1.01-2.0    | 17        | 4.21%   |
| 64.01-256.0 | 14        | 3.47%   |
| 24.01-32.0  | 7         | 1.73%   |
| 2.01-3.0    | 7         | 1.73%   |
| 0.51-1.0    | 2         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 146       | 32.66%  |
| 2.01-3.0    | 132       | 29.53%  |
| 3.01-4.0    | 65        | 14.54%  |
| 4.01-8.0    | 45        | 10.07%  |
| 0.51-1.0    | 29        | 6.49%   |
| 8.01-16.0   | 15        | 3.36%   |
| 32.01-64.0  | 4         | 0.89%   |
| 0.01-0.5    | 4         | 0.89%   |
| 24.01-32.0  | 3         | 0.67%   |
| 64.01-256.0 | 2         | 0.45%   |
| 16.01-24.0  | 1         | 0.22%   |
| Unknown     | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 221       | 53.77%  |
| 2      | 112       | 27.25%  |
| 3      | 35        | 8.52%   |
| 4      | 19        | 4.62%   |
| 5      | 9         | 2.19%   |
| 7      | 6         | 1.46%   |
| 8      | 4         | 0.97%   |
| 6      | 4         | 0.97%   |
| 9      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 267       | 66.42%  |
| Yes       | 135       | 33.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 339       | 84.75%  |
| No        | 61        | 15.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 80.65%  |
| No        | 78        | 19.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 61.19%  |
| No        | 156       | 38.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Malaysia | 400       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 153       | 35.5%   |
| Petaling Jaya          | 48        | 11.14%  |
| Shah Alam              | 17        | 3.94%   |
| Johor Bahru            | 15        | 3.48%   |
| Puchong Batu Dua Belas | 14        | 3.25%   |
| Subang Jaya            | 13        | 3.02%   |
| Kota Kinabalu          | 11        | 2.55%   |
| Ipoh                   | 11        | 2.55%   |
| George Town            | 10        | 2.32%   |
| Sungai Buloh           | 9         | 2.09%   |
| Seremban               | 9         | 2.09%   |
| Malacca                | 8         | 1.86%   |
| Kota Bharu             | 8         | 1.86%   |
| Kajang                 | 8         | 1.86%   |
| Kuching                | 7         | 1.62%   |
| Kulim                  | 5         | 1.16%   |
| Tawau                  | 4         | 0.93%   |
| Sungai Petani          | 4         | 0.93%   |
| Skudai                 | 4         | 0.93%   |
| Marabu                 | 4         | 0.93%   |
| Kulai                  | 4         | 0.93%   |
| Klang                  | 4         | 0.93%   |
| Cyberjaya              | 4         | 0.93%   |
| Butterworth            | 4         | 0.93%   |
| Bayan Lepas            | 4         | 0.93%   |
| Ampang                 | 4         | 0.93%   |
| Seri Kembangan         | 3         | 0.7%    |
| Putrajaya              | 3         | 0.7%    |
| Cheras                 | 3         | 0.7%    |
| Rawang                 | 2         | 0.46%   |
| Nibong Tebal           | 2         | 0.46%   |
| Long Seridan           | 2         | 0.46%   |
| Bukit Mertajam         | 2         | 0.46%   |
| Ayer Itam              | 2         | 0.46%   |
| Alor Star              | 2         | 0.46%   |
| Taman Senai            | 1         | 0.23%   |
| Taiping                | 1         | 0.23%   |
| Sibu                   | 1         | 0.23%   |
| Sepang                 | 1         | 0.23%   |
| Semenyih               | 1         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 116       | 182    | 18.07%  |
| WDC                         | 103       | 175    | 16.04%  |
| Kingston                    | 52        | 70     | 8.1%    |
| Samsung Electronics         | 50        | 73     | 7.79%   |
| Toshiba                     | 44        | 52     | 6.85%   |
| Unknown                     | 25        | 33     | 3.89%   |
| SanDisk                     | 25        | 34     | 3.89%   |
| HGST                        | 18        | 21     | 2.8%    |
| A-DATA Technology           | 18        | 29     | 2.8%    |
| Intel                       | 16        | 24     | 2.49%   |
| Apacer                      | 13        | 19     | 2.02%   |
| PNY                         | 12        | 37     | 1.87%   |
| Crucial                     | 12        | 20     | 1.87%   |
| SK hynix                    | 9         | 9      | 1.4%    |
| Micron Technology           | 8         | 12     | 1.25%   |
| Hitachi                     | 8         | 13     | 1.25%   |
| Phison                      | 7         | 10     | 1.09%   |
| KIOXIA                      | 7         | 8      | 1.09%   |
| China                       | 6         | 6      | 0.93%   |
| Transcend                   | 5         | 6      | 0.78%   |
| TO Exter                    | 4         | 6      | 0.62%   |
| SPCC                        | 4         | 5      | 0.62%   |
| Silicon Motion              | 4         | 5      | 0.62%   |
| Patriot                     | 4         | 5      | 0.62%   |
| Hewlett-Packard             | 4         | 4      | 0.62%   |
| Corsair                     | 4         | 12     | 0.62%   |
| Phison Electronics          | 3         | 4      | 0.47%   |
| Kingston Technology Company | 3         | 3      | 0.47%   |
| Gigabyte Technology         | 3         | 3      | 0.47%   |
| XPG                         | 2         | 3      | 0.31%   |
| Verbatim                    | 2         | 2      | 0.31%   |
| Team                        | 2         | 2      | 0.31%   |
| Plextor                     | 2         | 2      | 0.31%   |
| OCZ                         | 2         | 4      | 0.31%   |
| Netac                       | 2         | 2      | 0.31%   |
| Micron/Crucial Technology   | 2         | 3      | 0.31%   |
| KIOXIA-EXCERIA              | 2         | 4      | 0.31%   |
| Kingchuxing                 | 2         | 2      | 0.31%   |
| KimMiDi                     | 2         | 2      | 0.31%   |
| JMicron Technology          | 2         | 2      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 13        | 1.82%   |
| Toshiba MQ01ABD100 1TB             | 8         | 1.12%   |
| Seagate ST3500414CS 500GB          | 8         | 1.12%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 7         | 0.98%   |
| WDC WD2500AAKX-753CA1 250GB        | 7         | 0.98%   |
| Seagate ST2000DM008-2UB102 2TB     | 7         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 0.98%   |
| Seagate ST1000DM010-2EP102 1TB     | 7         | 0.98%   |
| Toshiba MQ04ABF100 1TB             | 6         | 0.84%   |
| PNY 1TB SATA SSD                   | 6         | 0.84%   |
| HGST HTS545050A7E680 500GB         | 6         | 0.84%   |
| Crucial CT500MX500SSD1 500GB       | 6         | 0.84%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 5         | 0.7%    |
| WDC WD20EZRX-00D8PB0 2TB           | 5         | 0.7%    |
| Unknown MMC Card  32GB             | 5         | 0.7%    |
| Seagate ST500LT012-1DG142 500GB    | 5         | 0.7%    |
| Seagate ST380815AS 80GB            | 5         | 0.7%    |
| Samsung HD103SJ 1TB                | 5         | 0.7%    |
| Kingston SA400S37480G 480GB SSD    | 5         | 0.7%    |
| Apacer AS340 120GB SSD             | 5         | 0.7%    |
| TO Exter nal USB 3.0 1TB           | 4         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB    | 4         | 0.56%   |
| Seagate ST500DM002-1BC142 500GB    | 4         | 0.56%   |
| Seagate ST3160815AS 160GB          | 4         | 0.56%   |
| Seagate ST1000LM048-2E7172 1TB     | 4         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 0.56%   |
| SanDisk SSD PLUS 240GB             | 4         | 0.56%   |
| Samsung SSD 860 EVO 250GB          | 4         | 0.56%   |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.56%   |
| Corsair Force MP510 240GB          | 4         | 0.56%   |
| A-DATA SX8200PNP 256GB             | 4         | 0.56%   |
| A-DATA SU650 120GB SSD             | 4         | 0.56%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 3         | 0.42%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 3         | 0.42%   |
| WDC WD3200AAKS-00SBA0 320GB        | 3         | 0.42%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 3         | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.42%   |
| Unknown MMC Card  64GB             | 3         | 0.42%   |
| Unknown MMC Card                   | 3         | 0.42%   |
| SK hynix NVMe SSD Drive 512GB      | 3         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 113       | 179    | 39.37%  |
| WDC                 | 88        | 160    | 30.66%  |
| Toshiba             | 37        | 44     | 12.89%  |
| HGST                | 18        | 21     | 6.27%   |
| Samsung Electronics | 10        | 16     | 3.48%   |
| Hitachi             | 8         | 13     | 2.79%   |
| Unknown             | 2         | 2      | 0.7%    |
| Hewlett-Packard     | 2         | 2      | 0.7%    |
| Fujitsu             | 2         | 2      | 0.7%    |
| External            | 2         | 2      | 0.7%    |
| USB3.0              | 1         | 1      | 0.35%   |
| Maxtor              | 1         | 2      | 0.35%   |
| JMicron Technology  | 1         | 1      | 0.35%   |
| ASMT                | 1         | 1      | 0.35%   |
| Apple               | 1         | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 43        | 55     | 21.61%  |
| Samsung Electronics | 21        | 31     | 10.55%  |
| SanDisk             | 15        | 19     | 7.54%   |
| Apacer              | 13        | 19     | 6.53%   |
| Crucial             | 12        | 20     | 6.03%   |
| PNY                 | 11        | 36     | 5.53%   |
| A-DATA Technology   | 10        | 10     | 5.03%   |
| Intel               | 6         | 9      | 3.02%   |
| China               | 6         | 6      | 3.02%   |
| WDC                 | 5         | 5      | 2.51%   |
| Transcend           | 5         | 5      | 2.51%   |
| TO Exter            | 4         | 6      | 2.01%   |
| SPCC                | 4         | 5      | 2.01%   |
| Patriot             | 4         | 5      | 2.01%   |
| Micron Technology   | 4         | 8      | 2.01%   |
| Verbatim            | 2         | 2      | 1.01%   |
| Toshiba             | 2         | 2      | 1.01%   |
| Team                | 2         | 2      | 1.01%   |
| Seagate             | 2         | 2      | 1.01%   |
| Plextor             | 2         | 2      | 1.01%   |
| OCZ                 | 2         | 4      | 1.01%   |
| Netac               | 2         | 2      | 1.01%   |
| KIOXIA-EXCERIA      | 2         | 4      | 1.01%   |
| KimMiDi             | 2         | 2      | 1.01%   |
| Colorful            | 2         | 2      | 1.01%   |
| Teclast             | 1         | 1      | 0.5%    |
| sk600               | 1         | 1      | 0.5%    |
| SK hynix            | 1         | 1      | 0.5%    |
| SATAFIRM            | 1         | 1      | 0.5%    |
| Pioneer             | 1         | 1      | 0.5%    |
| LS                  | 1         | 1      | 0.5%    |
| LITEON              | 1         | 1      | 0.5%    |
| Kingmax             | 1         | 1      | 0.5%    |
| JMicron Technology  | 1         | 1      | 0.5%    |
| Hikvision           | 1         | 2      | 0.5%    |
| Hewlett-Packard     | 1         | 1      | 0.5%    |
| Gigabyte Technology | 1         | 1      | 0.5%    |
| FORESEE             | 1         | 1      | 0.5%    |
| ASMT                | 1         | 2      | 0.5%    |
| Apple               | 1         | 2      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 238       | 447    | 43.43%  |
| SSD     | 171       | 282    | 31.2%   |
| NVMe    | 106       | 175    | 19.34%  |
| MMC     | 21        | 28     | 3.83%   |
| Unknown | 12        | 15     | 2.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 326       | 712    | 68.06%  |
| NVMe | 106       | 174    | 22.13%  |
| SAS  | 26        | 33     | 5.43%   |
| MMC  | 21        | 28     | 4.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 253       | 418    | 59.95%  |
| 0.51-1.0   | 127       | 221    | 30.09%  |
| 1.01-2.0   | 33        | 72     | 7.82%   |
| 3.01-4.0   | 6         | 14     | 1.42%   |
| 4.01-10.0  | 2         | 3      | 0.47%   |
| 2.01-3.0   | 1         | 1      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 116       | 27.29%  |
| 251-500        | 95        | 22.35%  |
| 501-1000       | 57        | 13.41%  |
| 1-20           | 40        | 9.41%   |
| 51-100         | 31        | 7.29%   |
| 1001-2000      | 28        | 6.59%   |
| 21-50          | 22        | 5.18%   |
| Unknown        | 18        | 4.24%   |
| More than 3000 | 11        | 2.59%   |
| 2001-3000      | 7         | 1.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 190       | 43.78%  |
| 21-50          | 65        | 14.98%  |
| 101-250        | 51        | 11.75%  |
| 51-100         | 45        | 10.37%  |
| 251-500        | 30        | 6.91%   |
| Unknown        | 18        | 4.15%   |
| 501-1000       | 15        | 3.46%   |
| 1001-2000      | 10        | 2.3%    |
| More than 3000 | 6         | 1.38%   |
| 2001-3000      | 3         | 0.69%   |
| 0              | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB                     | 7         | 7      | 14.89%  |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 4.26%   |
| Seagate ST9320325AS 320GB                        | 2         | 2      | 4.26%   |
| Seagate ST3500414CS 500GB                        | 2         | 3      | 4.26%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 2.13%   |
| WDC WD800AAJS-00PSA0 80GB                        | 1         | 1      | 2.13%   |
| WDC WD5000BPVT-00HXZT1 500GB                     | 1         | 1      | 2.13%   |
| WDC WD5000AAKX-753CA1 500GB                      | 1         | 1      | 2.13%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 1         | 1      | 2.13%   |
| WDC WD5000AADS-00S9B0 500GB                      | 1         | 1      | 2.13%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 2.13%   |
| WDC WD10JPVT-75A1YT0 1TB                         | 1         | 1      | 2.13%   |
| WDC WD10EZEX-60WN4A0 1TB                         | 1         | 1      | 2.13%   |
| WDC WD10EZEX-08WN4A0 1TB                         | 1         | 1      | 2.13%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 2.13%   |
| Toshiba MK1059GSMP 1TB                           | 1         | 1      | 2.13%   |
| SPCC Solid State Disk 256GB                      | 1         | 1      | 2.13%   |
| Seagate ST9750420AS 752GB                        | 1         | 1      | 2.13%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 2.13%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 2.13%   |
| Seagate ST380211AS 80GB                          | 1         | 1      | 2.13%   |
| Seagate ST3320620A 320GB                         | 1         | 1      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.13%   |
| Samsung Electronics SSD PM830 2.5 7mm 512GB      | 1         | 1      | 2.13%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.13%   |
| PNY 1TB SATA SSD                                 | 1         | 6      | 2.13%   |
| Micron/Crucial Technology P1 NVMe PCIe SSD 500GB | 1         | 2      | 2.13%   |
| Micron Technology 1100 SATA 512GB SSD            | 1         | 1      | 2.13%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 2.13%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 2.13%   |
| Hitachi HTS547575A9E384 752GB                    | 1         | 3      | 2.13%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 1      | 2.13%   |
| Hitachi HDS721050CLA362 500GB                    | 1         | 1      | 2.13%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 2.13%   |
| HGST HTS541075A9E680 752GB                       | 1         | 1      | 2.13%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 2.13%   |
| Hewlett-Packard SSD S700 120GB                   | 1         | 1      | 2.13%   |
| Unknown                                          | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 254       | 571    | 57.21%  |
| Works    | 146       | 320    | 32.88%  |
| Malfunc  | 44        | 56     | 9.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 290       | 58.94%  |
| AMD                          | 63        | 12.8%   |
| Samsung Electronics          | 21        | 4.27%   |
| SanDisk                      | 20        | 4.07%   |
| Phison Electronics           | 17        | 3.46%   |
| Kingston Technology Company  | 12        | 2.44%   |
| ADATA Technology             | 9         | 1.83%   |
| SK hynix                     | 8         | 1.63%   |
| ASMedia Technology           | 8         | 1.63%   |
| Silicon Motion               | 7         | 1.42%   |
| Nvidia                       | 7         | 1.42%   |
| KIOXIA                       | 7         | 1.42%   |
| Toshiba America Info Systems | 5         | 1.02%   |
| Micron Technology            | 4         | 0.81%   |
| Marvell Technology Group     | 4         | 0.81%   |
| JMicron Technology           | 4         | 0.81%   |
| Micron/Crucial Technology    | 2         | 0.41%   |
| Silicon Image                | 1         | 0.2%    |
| Lite-On IT Corp. / Plextor   | 1         | 0.2%    |
| Hewlett-Packard              | 1         | 0.2%    |
| Biwin Storage Technology     | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 50        | 8.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 26        | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 23        | 3.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 3.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 3.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 15        | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 10        | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 10        | 1.73%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 1.73%   |
| Phison E12 NVMe Controller                                                     | 9         | 1.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 1.55%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 1.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 9         | 1.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 1.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 1.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.04%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 0.86%   |
| Intel SSD 660P Series                                                          | 5         | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 0.86%   |
| Intel 82Q35 Express PT IDER Controller                                         | 5         | 0.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.86%   |
| AMD FCH SATA Controller D                                                      | 5         | 0.86%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 0.69%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 4         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 282       | 58.02%  |
| NVMe | 106       | 21.81%  |
| IDE  | 54        | 11.11%  |
| RAID | 44        | 9.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 312       | 78%     |
| AMD    | 83        | 20.75%  |
| ARM    | 5         | 1.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz              | 8         | 1.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.99%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 8         | 1.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.24%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 5         | 1.24%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 5         | 1.24%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.24%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1%      |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 1%      |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1%      |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1%      |
| Intel Core i5-10400 CPU @ 2.90GHz             | 4         | 1%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 1%      |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1%      |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 1%      |
| Intel Pentium CPU G630 @ 2.70GHz              | 3         | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.75%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 0.75%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 3         | 0.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.75%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 3         | 0.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.75%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 3         | 0.75%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.75%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.75%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 0.75%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 0.75%   |
| Intel Xeon CPU X5450 @ 3.00GHz                | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.5%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 105       | 26.12%  |
| Intel Core i7           | 59        | 14.68%  |
| Intel Core i3           | 43        | 10.7%   |
| AMD Ryzen 5             | 30        | 7.46%   |
| Intel Core 2 Duo        | 22        | 5.47%   |
| Other                   | 21        | 5.22%   |
| Intel Pentium           | 18        | 4.48%   |
| Intel Celeron           | 17        | 4.23%   |
| Intel Xeon              | 12        | 2.99%   |
| AMD Ryzen 7             | 11        | 2.74%   |
| Intel Atom              | 6         | 1.49%   |
| Intel Pentium Dual-Core | 5         | 1.24%   |
| Intel Core 2 Quad       | 5         | 1.24%   |
| AMD Ryzen 9             | 5         | 1.24%   |
| AMD A6                  | 5         | 1.24%   |
| AMD Ryzen 3             | 4         | 1%      |
| AMD Ryzen Threadripper  | 3         | 0.75%   |
| AMD Ryzen 7 PRO         | 3         | 0.75%   |
| AMD Athlon              | 3         | 0.75%   |
| AMD A10                 | 3         | 0.75%   |
| Intel Core i9           | 2         | 0.5%    |
| ARM BCM                 | 2         | 0.5%    |
| AMD FX                  | 2         | 0.5%    |
| AMD E                   | 2         | 0.5%    |
| AMD Athlon 64 X2        | 2         | 0.5%    |
| AMD A4                  | 2         | 0.5%    |
| AMD A12                 | 2         | 0.5%    |
| Intel Pentium Dual      | 1         | 0.25%   |
| Intel Genuine           | 1         | 0.25%   |
| ARM AArch64             | 1         | 0.25%   |
| AMD Ryzen Embedded      | 1         | 0.25%   |
| AMD Phenom II X6        | 1         | 0.25%   |
| AMD Phenom II X4        | 1         | 0.25%   |
| AMD EPYC                | 1         | 0.25%   |
| AMD Athlon X2           | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 176       | 43.89%  |
| 4      | 137       | 34.16%  |
| 6      | 44        | 10.97%  |
| 8      | 21        | 5.24%   |
| 16     | 7         | 1.75%   |
| 1      | 6         | 1.5%    |
| 12     | 4         | 1%      |
| 14     | 2         | 0.5%    |
| 10     | 2         | 0.5%    |
| 64     | 1         | 0.25%   |
| 3      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 396       | 99%     |
| 2      | 4         | 1%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 261       | 64.93%  |
| 1      | 140       | 34.83%  |
| 4      | 1         | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 396       | 98.75%  |
| Unknown        | 5         | 1.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 23.61%  |
| 0x206a7    | 35        | 8.43%   |
| 0x306c3    | 30        | 7.23%   |
| 0x306a9    | 28        | 6.75%   |
| 0x1067a    | 17        | 4.1%    |
| 0x906ea    | 11        | 2.65%   |
| 0x806e9    | 10        | 2.41%   |
| 0x40651    | 8         | 1.93%   |
| 0x08108109 | 8         | 1.93%   |
| 0x306d4    | 7         | 1.69%   |
| 0x806ea    | 6         | 1.45%   |
| 0x506e3    | 6         | 1.45%   |
| 0x406e3    | 6         | 1.45%   |
| 0x20655    | 6         | 1.45%   |
| 0xa0652    | 5         | 1.2%    |
| 0x6fb      | 5         | 1.2%    |
| 0x20652    | 5         | 1.2%    |
| 0x08701021 | 5         | 1.2%    |
| 0x906e9    | 4         | 0.96%   |
| 0x806ec    | 4         | 0.96%   |
| 0x806eb    | 4         | 0.96%   |
| 0x806c1    | 4         | 0.96%   |
| 0x706a1    | 4         | 0.96%   |
| 0x6fd      | 4         | 0.96%   |
| 0x10676    | 4         | 0.96%   |
| 0x08600104 | 4         | 0.96%   |
| 0x06001119 | 4         | 0.96%   |
| 0xa0653    | 3         | 0.72%   |
| 0x90672    | 3         | 0.72%   |
| 0x806d1    | 3         | 0.72%   |
| 0x406c4    | 3         | 0.72%   |
| 0x30678    | 3         | 0.72%   |
| 0x0a50000b | 3         | 0.72%   |
| 0x0a20120a | 3         | 0.72%   |
| 0xa0671    | 2         | 0.48%   |
| 0xa0655    | 2         | 0.48%   |
| 0x906eb    | 2         | 0.48%   |
| 0x706e5    | 2         | 0.48%   |
| 0x706a8    | 2         | 0.48%   |
| 0x406c3    | 2         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 12.25%  |
| SandyBridge      | 46        | 11.5%   |
| Haswell          | 46        | 11.5%   |
| IvyBridge        | 41        | 10.25%  |
| Penryn           | 26        | 6.5%    |
| Zen+             | 18        | 4.5%    |
| Skylake          | 16        | 4%      |
| Zen 3            | 15        | 3.75%   |
| Zen 2            | 15        | 3.75%   |
| Unknown          | 14        | 3.5%    |
| Westmere         | 13        | 3.25%   |
| CometLake        | 13        | 3.25%   |
| Silvermont       | 10        | 2.5%    |
| Core             | 10        | 2.5%    |
| Broadwell        | 9         | 2.25%   |
| Zen              | 8         | 2%      |
| TigerLake        | 6         | 1.5%    |
| Piledriver       | 6         | 1.5%    |
| Goldmont plus    | 6         | 1.5%    |
| Alderlake Hybrid | 6         | 1.5%    |
| Icelake          | 5         | 1.25%   |
| Nehalem          | 3         | 0.75%   |
| K10              | 3         | 0.75%   |
| Excavator        | 3         | 0.75%   |
| Steamroller      | 2         | 0.5%    |
| K8 Hammer        | 2         | 0.5%    |
| Jaguar           | 2         | 0.5%    |
| Bonnell          | 2         | 0.5%    |
| Bobcat           | 2         | 0.5%    |
| K8 & K10 hybrid  | 1         | 0.25%   |
| K10 Llano        | 1         | 0.25%   |
| Goldmont         | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 239       | 48.58%  |
| Nvidia                     | 139       | 28.25%  |
| AMD                        | 108       | 21.95%  |
| ASPEED Technology          | 4         | 0.81%   |
| Matrox Electronics Systems | 2         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 6.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 3.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 2.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14        | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 2.39%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 2.19%   |
| Intel HD Graphics 620                                                                    | 10        | 1.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 1.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.79%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.39%   |
| Intel UHD Graphics 620                                                                   | 7         | 1.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.39%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 6         | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.19%   |
| AMD Renoir                                                                               | 6         | 1.19%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5         | 0.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 0.99%   |
| Intel HD Graphics 530                                                                    | 5         | 0.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.99%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4         | 0.8%    |
| Intel HD Graphics 630                                                                    | 4         | 0.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.8%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 0.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.6%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.6%    |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.6%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 153       | 38.06%  |
| 1 x AMD              | 74        | 18.41%  |
| 1 x Nvidia           | 70        | 17.41%  |
| Intel + Nvidia       | 58        | 14.43%  |
| Intel + AMD          | 20        | 4.98%   |
| 2 x AMD              | 8         | 1.99%   |
| AMD + Nvidia         | 7         | 1.74%   |
| Other                | 5         | 1.24%   |
| Nvidia + ASPEED      | 3         | 0.75%   |
| 1 x Matrox           | 2         | 0.5%    |
| 2 x AMD + 3 x Nvidia | 1         | 0.25%   |
| 1 x ASPEED           | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 317       | 77.7%   |
| Proprietary | 75        | 18.38%  |
| Unknown     | 16        | 3.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 217       | 53.19%  |
| 1.01-2.0   | 65        | 15.93%  |
| 0.51-1.0   | 38        | 9.31%   |
| 0.01-0.5   | 31        | 7.6%    |
| 3.01-4.0   | 30        | 7.35%   |
| 7.01-8.0   | 15        | 3.68%   |
| 5.01-6.0   | 6         | 1.47%   |
| 8.01-16.0  | 4         | 0.98%   |
| 2.01-3.0   | 2         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 12.47%  |
| Samsung Electronics     | 46        | 10.82%  |
| Dell                    | 43        | 10.12%  |
| Chimei Innolux          | 40        | 9.41%   |
| LG Display              | 34        | 8%      |
| BOE                     | 30        | 7.06%   |
| BenQ                    | 22        | 5.18%   |
| Acer                    | 22        | 5.18%   |
| Hewlett-Packard         | 19        | 4.47%   |
| Goldstar                | 18        | 4.24%   |
| AOC                     | 15        | 3.53%   |
| Sharp                   | 11        | 2.59%   |
| Philips                 | 10        | 2.35%   |
| ViewSonic               | 7         | 1.65%   |
| Apple                   | 7         | 1.65%   |
| Lenovo                  | 5         | 1.18%   |
| Chi Mei Optoelectronics | 4         | 0.94%   |
| Toshiba                 | 3         | 0.71%   |
| Panasonic               | 3         | 0.71%   |
| ASUSTek Computer        | 3         | 0.71%   |
| Unknown                 | 2         | 0.47%   |
| PANDA                   | 2         | 0.47%   |
| LG Electronics          | 2         | 0.47%   |
| InnoLux Display         | 2         | 0.47%   |
| Denver                  | 2         | 0.47%   |
| Unknown                 | 2         | 0.47%   |
| Xiaomi                  | 1         | 0.24%   |
| Valve                   | 1         | 0.24%   |
| TRI                     | 1         | 0.24%   |
| Sony                    | 1         | 0.24%   |
| MStar                   | 1         | 0.24%   |
| MSI                     | 1         | 0.24%   |
| LTM                     | 1         | 0.24%   |
| LG Philips              | 1         | 0.24%   |
| InfoVision              | 1         | 0.24%   |
| HUYINIUDA               | 1         | 0.24%   |
| EXP                     | 1         | 0.24%   |
| Envision Peripherals    | 1         | 0.24%   |
| Eizo                    | 1         | 0.24%   |
| Dinner                  | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 7         | 1.61%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                          | 6         | 1.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 4         | 0.92%   |
| Dell E2720HS DELA15E 1920x1080 600x340mm 27.2-inch                        | 4         | 0.92%   |
| BenQ EX3203R BNQ7F66 2560x1440 698x393mm 31.5-inch                        | 4         | 0.92%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 4         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 3         | 0.69%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 3         | 0.69%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 3         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.69%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 3         | 0.69%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                         | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 3         | 0.69%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                         | 3         | 0.69%   |
| Sharp LCD SHP10C9 1920x540                                                | 2         | 0.46%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch         | 2         | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 2         | 0.46%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch          | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.46%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                        | 2         | 0.46%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 2         | 0.46%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 2         | 0.46%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.46%   |
| Hewlett-Packard LCD Monitor P221                                          | 2         | 0.46%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch                | 2         | 0.46%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                        | 2         | 0.46%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.46%   |
| Dell LCD Monitor E2720HS 1920x1080                                        | 2         | 0.46%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch           | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x174mm 14.0-inch           | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.46%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                        | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 163       | 39.76%  |
| 1366x768 (WXGA)    | 117       | 28.54%  |
| 3840x2160 (4K)     | 22        | 5.37%   |
| 1600x900 (HD+)     | 22        | 5.37%   |
| 2560x1440 (QHD)    | 16        | 3.9%    |
| 1280x800 (WXGA)    | 9         | 2.2%    |
| 2560x1080          | 6         | 1.46%   |
| 1440x900 (WXGA+)   | 6         | 1.46%   |
| 1920x1200 (WUXGA)  | 5         | 1.22%   |
| 1360x768           | 5         | 1.22%   |
| Unknown            | 5         | 1.22%   |
| 1680x1050 (WSXGA+) | 4         | 0.98%   |
| 2160x1440          | 3         | 0.73%   |
| 1280x1024 (SXGA)   | 3         | 0.73%   |
| 1024x768 (XGA)     | 3         | 0.73%   |
| 5760x1080          | 2         | 0.49%   |
| 1920x540           | 2         | 0.49%   |
| 1600x1200          | 2         | 0.49%   |
| 1280x720 (HD)      | 2         | 0.49%   |
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

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 80        | 18.87%  |
| 14      | 55        | 12.97%  |
| 13      | 44        | 10.38%  |
| 24      | 33        | 7.78%   |
| 23      | 31        | 7.31%   |
| 21      | 25        | 5.9%    |
| 27      | 22        | 5.19%   |
| 18      | 22        | 5.19%   |
| Unknown | 19        | 4.48%   |
| 31      | 14        | 3.3%    |
| 19      | 13        | 3.07%   |
| 20      | 12        | 2.83%   |
| 17      | 10        | 2.36%   |
| 12      | 7         | 1.65%   |
| 32      | 6         | 1.42%   |
| 11      | 6         | 1.42%   |
| 34      | 4         | 0.94%   |
| 22      | 3         | 0.71%   |
| 84      | 2         | 0.47%   |
| 72      | 2         | 0.47%   |
| 52      | 2         | 0.47%   |
| 28      | 2         | 0.47%   |
| 25      | 2         | 0.47%   |
| 7       | 2         | 0.47%   |
| 65      | 1         | 0.24%   |
| 55      | 1         | 0.24%   |
| 39      | 1         | 0.24%   |
| 35      | 1         | 0.24%   |
| 16      | 1         | 0.24%   |
| 10      | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 38.95%  |
| 501-600     | 81        | 19.24%  |
| 401-500     | 74        | 17.58%  |
| 201-300     | 30        | 7.13%   |
| 601-700     | 19        | 4.51%   |
| Unknown     | 19        | 4.51%   |
| 351-400     | 12        | 2.85%   |
| 701-800     | 10        | 2.38%   |
| 1501-2000   | 4         | 0.95%   |
| 1001-1500   | 4         | 0.95%   |
| 801-900     | 2         | 0.48%   |
| 101-200     | 1         | 0.24%   |
| 1-100       | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 310       | 81.15%  |
| 16/10   | 28        | 7.33%   |
| Unknown | 17        | 4.45%   |
| 3/2     | 7         | 1.83%   |
| 21/9    | 7         | 1.83%   |
| 5/4     | 5         | 1.31%   |
| 4/3     | 4         | 1.05%   |
| 32/9    | 2         | 0.52%   |
| 1.00    | 1         | 0.26%   |
| 0.67    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 87        | 20.67%  |
| 101-110        | 80        | 19%     |
| 201-250        | 79        | 18.76%  |
| 151-200        | 31        | 7.36%   |
| 351-500        | 25        | 5.94%   |
| 141-150        | 23        | 5.46%   |
| 301-350        | 22        | 5.23%   |
| Unknown        | 19        | 4.51%   |
| 71-80          | 12        | 2.85%   |
| 251-300        | 10        | 2.38%   |
| More than 1000 | 8         | 1.9%    |
| 61-70          | 7         | 1.66%   |
| 121-130        | 7         | 1.66%   |
| 51-60          | 6         | 1.43%   |
| 1-40           | 2         | 0.48%   |
| 41-50          | 1         | 0.24%   |
| 111-120        | 1         | 0.24%   |
| 501-1000       | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 151       | 36.47%  |
| 101-120       | 122       | 29.47%  |
| 121-160       | 95        | 22.95%  |
| Unknown       | 19        | 4.59%   |
| 161-240       | 14        | 3.38%   |
| 1-50          | 10        | 2.42%   |
| More than 240 | 3         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 326       | 80.49%  |
| 2     | 57        | 14.07%  |
| 0     | 20        | 4.94%   |
| 3     | 2         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 213       | 32.82%  |
| Intel                             | 186       | 28.66%  |
| Qualcomm Atheros                  | 91        | 14.02%  |
| Broadcom                          | 39        | 6.01%   |
| TP-Link                           | 22        | 3.39%   |
| Ralink Technology                 | 19        | 2.93%   |
| D-Link                            | 11        | 1.69%   |
| Xiaomi                            | 9         | 1.39%   |
| Qualcomm Atheros Communications   | 9         | 1.39%   |
| MediaTek                          | 7         | 1.08%   |
| Ralink                            | 5         | 0.77%   |
| Nvidia                            | 5         | 0.77%   |
| Broadcom Limited                  | 5         | 0.77%   |
| ASIX Electronics                  | 4         | 0.62%   |
| Samsung Electronics               | 3         | 0.46%   |
| Huawei Technologies               | 3         | 0.46%   |
| OPPO Electronics                  | 2         | 0.31%   |
| InterBiometrics                   | 2         | 0.31%   |
| Aquantia                          | 2         | 0.31%   |
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

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 142       | 19.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 3.23%   |
| Intel Wi-Fi 6 AX200                                               | 16        | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 1.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 1.48%   |
| Realtek 802.11ac NIC                                              | 11        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.48%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.48%   |
| TP-Link Archer T4U ver.3                                          | 9         | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.21%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 1.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 8         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 1.08%   |
| TP-Link 802.11n NIC                                               | 7         | 0.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 7         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 0.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 6         | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.81%   |
| Qualcomm Atheros AR9271 802.11n                                   | 6         | 0.81%   |
| Intel Wireless 7265                                               | 6         | 0.81%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 6         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.67%   |
| Intel Wireless 3165                                               | 5         | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.67%   |
| Intel I211 Gigabit Network Connection                             | 5         | 0.67%   |
| Intel Ethernet Connection (11) I219-V                             | 5         | 0.67%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 124       | 34.93%  |
| Qualcomm Atheros                | 68        | 19.15%  |
| Realtek Semiconductor           | 58        | 16.34%  |
| Broadcom                        | 25        | 7.04%   |
| TP-Link                         | 22        | 6.2%    |
| Ralink Technology               | 19        | 5.35%   |
| D-Link                          | 11        | 3.1%    |
| Qualcomm Atheros Communications | 9         | 2.54%   |
| MediaTek                        | 7         | 1.97%   |
| Ralink                          | 5         | 1.41%   |
| Broadcom Limited                | 4         | 1.13%   |
| D-Link System                   | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |
| AboCom Systems                  | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 16        | 4.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 14        | 3.9%    |
| Realtek 802.11ac NIC                                                                 | 11        | 3.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 11        | 3.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 11        | 3.06%   |
| Intel Wireless 8265 / 8275                                                           | 11        | 3.06%   |
| TP-Link Archer T4U ver.3                                                             | 9         | 2.51%   |
| Ralink MT7601U Wireless Adapter                                                      | 9         | 2.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 8         | 2.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 8         | 2.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 8         | 2.23%   |
| TP-Link 802.11n NIC                                                                  | 7         | 1.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 7         | 1.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 7         | 1.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 6         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 6         | 1.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 6         | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 6         | 1.67%   |
| Intel Wireless 7265                                                                  | 6         | 1.67%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 5         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 5         | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 5         | 1.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 5         | 1.39%   |
| Intel Wireless 3165                                                                  | 5         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 5         | 1.39%   |
| Intel Centrino Wireless-N 2230                                                       | 5         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                             | 5         | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 4         | 1.11%   |
| Intel Wireless-AC 9260                                                               | 4         | 1.11%   |
| Intel Wireless 7260                                                                  | 4         | 1.11%   |
| Intel Wireless 3160                                                                  | 4         | 1.11%   |
| Intel Wi-Fi 6 AX201                                                                  | 4         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                                       | 4         | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4         | 1.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 4         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3         | 0.84%   |
| Ralink RT5572 Wireless Adapter                                                       | 3         | 0.84%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 186       | 50.41%  |
| Intel                             | 101       | 27.37%  |
| Qualcomm Atheros                  | 28        | 7.59%   |
| Broadcom                          | 18        | 4.88%   |
| Xiaomi                            | 9         | 2.44%   |
| Nvidia                            | 5         | 1.36%   |
| ASIX Electronics                  | 4         | 1.08%   |
| Huawei Technologies               | 3         | 0.81%   |
| Samsung Electronics               | 2         | 0.54%   |
| OPPO Electronics                  | 2         | 0.54%   |
| Aquantia                          | 2         | 0.54%   |
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

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 142       | 37.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 6.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 3.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 3.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 2.37%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 2.37%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.32%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.32%   |
| Intel Ethernet Connection (11) I219-V                             | 5         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 1.05%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.05%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.79%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.79%   |
| Huawei ANE-LX1                                                    | 3         | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.53%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 2         | 0.53%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.53%   |
| Intel I350 Gigabit Fiber Network Connection                       | 2         | 0.53%   |
| Intel Ethernet Controller X550                                    | 2         | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 338       | 50.67%  |
| WiFi     | 325       | 48.73%  |
| Modem    | 4         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 262       | 64.06%  |
| Ethernet | 147       | 35.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 212       | 52.74%  |
| 1     | 151       | 37.56%  |
| 0     | 22        | 5.47%   |
| 3     | 12        | 2.99%   |
| 4     | 2         | 0.5%    |
| 9     | 1         | 0.25%   |
| 8     | 1         | 0.25%   |
| 5     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 296       | 71.67%  |
| Yes  | 117       | 28.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 39.6%   |
| Cambridge Silicon Radio         | 24        | 9.6%    |
| Realtek Semiconductor           | 20        | 8%      |
| Qualcomm Atheros Communications | 18        | 7.2%    |
| IMC Networks                    | 16        | 6.4%    |
| Broadcom                        | 14        | 5.6%    |
| Foxconn / Hon Hai               | 13        | 5.2%    |
| Apple                           | 12        | 4.8%    |
| Lite-On Technology              | 10        | 4%      |
| Dell                            | 5         | 2%      |
| Hewlett-Packard                 | 4         | 1.6%    |
| Realtek                         | 3         | 1.2%    |
| TP-Link                         | 2         | 0.8%    |
| Ralink                          | 2         | 0.8%    |
| MediaTek                        | 2         | 0.8%    |
| D-Link                          | 2         | 0.8%    |
| Ralink Technology               | 1         | 0.4%    |
| ASUSTek Computer                | 1         | 0.4%    |
| Askey Computer                  | 1         | 0.4%    |
| Alps Electric                   | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 32        | 12.8%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 24        | 9.6%    |
| Intel AX200 Bluetooth                                                               | 17        | 6.8%    |
| Intel AX201 Bluetooth                                                               | 16        | 6.4%    |
| Realtek Bluetooth Radio                                                             | 12        | 4.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 4.4%    |
| Apple Bluetooth Host Controller                                                     | 9         | 3.6%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 2.8%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 2.4%    |
| IMC Networks Bluetooth Device                                                       | 6         | 2.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 2%      |
| Intel Bluetooth Device                                                              | 5         | 2%      |
| Intel AX210 Bluetooth                                                               | 5         | 2%      |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 1.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1.6%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.6%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.6%    |
| Realtek Bluetooth Radio                                                             | 3         | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.2%    |
| Lite-On Bluetooth Device                                                            | 3         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.2%    |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.2%    |
| TP-Link UB500 Adapter                                                               | 2         | 0.8%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.8%    |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.8%    |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.8%    |
| IMC Networks Wireless_Device                                                        | 2         | 0.8%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.8%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.8%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.8%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.8%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.8%    |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.8%    |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.8%    |
| D-Link DBT-122 Bluetooth adapter                                                    | 2         | 0.8%    |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.8%    |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 295       | 54.33%  |
| AMD                         | 104       | 19.15%  |
| Nvidia                      | 100       | 18.42%  |
| C-Media Electronics         | 8         | 1.47%   |
| Logitech                    | 7         | 1.29%   |
| JMTek                       | 4         | 0.74%   |
| ASUSTek Computer            | 3         | 0.55%   |
| Texas Instruments           | 2         | 0.37%   |
| Samsung Electronics         | 2         | 0.37%   |
| RODE Microphones            | 2         | 0.37%   |
| Realtek Semiconductor       | 2         | 0.37%   |
| Generalplus Technology      | 2         | 0.37%   |
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

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 41        | 6.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 41        | 6.43%   |
| AMD Family 17h/19h HD Audio Controller                                            | 36        | 5.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 29        | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                                   | 27        | 4.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 19        | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 18        | 2.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 18        | 2.82%   |
| Nvidia GF108 High Definition Audio Controller                                     | 15        | 2.35%   |
| AMD Starship/Matisse HD Audio Controller                                          | 15        | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 15        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                        | 14        | 2.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 13        | 2.04%   |
| AMD FCH Azalia Controller                                                         | 10        | 1.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9         | 1.41%   |
| Intel 8 Series HD Audio Controller                                                | 9         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9         | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 8         | 1.25%   |
| Intel Haswell-ULT HD Audio Controller                                             | 8         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                         | 8         | 1.25%   |
| Intel Broadwell-U Audio Controller                                                | 8         | 1.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7         | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                            | 7         | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 6         | 0.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 6         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 6         | 0.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6         | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6         | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5         | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 5         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5         | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5         | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                                     | 5         | 0.78%   |
| AMD Trinity HDMI Audio Controller                                                 | 5         | 0.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5         | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                          | 5         | 0.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 66        | 27.27%  |
| Samsung Electronics | 42        | 17.36%  |
| SK hynix            | 39        | 16.12%  |
| Corsair             | 18        | 7.44%   |
| Micron Technology   | 15        | 6.2%    |
| Unknown             | 11        | 4.55%   |
| Nanya Technology    | 7         | 2.89%   |
| A-DATA Technology   | 7         | 2.89%   |
| Apacer              | 5         | 2.07%   |
| Ramaxel Technology  | 4         | 1.65%   |
| Kingmax             | 4         | 1.65%   |
| Unknown (ABCD)      | 3         | 1.24%   |
| Team                | 3         | 1.24%   |
| Crucial             | 3         | 1.24%   |
| Silicon Power       | 2         | 0.83%   |
| Kimtigo             | 2         | 0.83%   |
| G.Skill             | 2         | 0.83%   |
| Elpida              | 2         | 0.83%   |
| Unknown (08AE)      | 1         | 0.41%   |
| Transcend           | 1         | 0.41%   |
| SemsoTai            | 1         | 0.41%   |
| PNY                 | 1         | 0.41%   |
| Patriot Memory      | 1         | 0.41%   |
| Kinlstuo            | 1         | 0.41%   |
| Hewlett-Packard     | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s              | 6         | 2.33%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 5         | 1.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.56%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 4         | 1.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 3         | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.17%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4096MB SODIMM DDR3 1334MT/s          | 3         | 1.17%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.78%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.78%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.78%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 2         | 0.78%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s            | 2         | 0.78%   |
| Kingston RAM 99U5428-082.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                 | 2         | 0.78%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.78%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2         | 0.78%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.39%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 83        | 41.29%  |
| DDR3    | 83        | 41.29%  |
| SDRAM   | 14        | 6.97%   |
| DDR2    | 7         | 3.48%   |
| LPDDR4  | 5         | 2.49%   |
| LPDDR3  | 4         | 1.99%   |
| DDR5    | 2         | 1%      |
| Unknown | 2         | 1%      |
| DDR     | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 112       | 56.28%  |
| DIMM         | 79        | 39.7%   |
| Row Of Chips | 7         | 3.52%   |
| FB-DIMM      | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 75        | 33.94%  |
| 4096  | 68        | 30.77%  |
| 2048  | 32        | 14.48%  |
| 16384 | 24        | 10.86%  |
| 32768 | 17        | 7.69%   |
| 1024  | 5         | 2.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 56        | 25.45%  |
| 3200    | 32        | 14.55%  |
| 2667    | 29        | 13.18%  |
| 1333    | 16        | 7.27%   |
| 1334    | 15        | 6.82%   |
| 2400    | 14        | 6.36%   |
| 2133    | 8         | 3.64%   |
| 3600    | 6         | 2.73%   |
| 667     | 6         | 2.73%   |
| 800     | 5         | 2.27%   |
| Unknown | 5         | 2.27%   |
| 1067    | 4         | 1.82%   |
| 4800    | 2         | 0.91%   |
| 4267    | 2         | 0.91%   |
| 4199    | 2         | 0.91%   |
| 3933    | 2         | 0.91%   |
| 1867    | 2         | 0.91%   |
| 1800    | 2         | 0.91%   |
| 1066    | 2         | 0.91%   |
| 8400    | 1         | 0.45%   |
| 5600    | 1         | 0.45%   |
| 3534    | 1         | 0.45%   |
| 3466    | 1         | 0.45%   |
| 3266    | 1         | 0.45%   |
| 3000    | 1         | 0.45%   |
| 2933    | 1         | 0.45%   |
| 2134    | 1         | 0.45%   |
| 2048    | 1         | 0.45%   |
| 1866    | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 40        | 18.02%  |
| Microdia                               | 26        | 11.71%  |
| IMC Networks                           | 21        | 9.46%   |
| Realtek Semiconductor                  | 17        | 7.66%   |
| Sunplus Innovation Technology          | 16        | 7.21%   |
| Logitech                               | 13        | 5.86%   |
| Suyin                                  | 11        | 4.95%   |
| Apple                                  | 10        | 4.5%    |
| Bison Electronics                      | 9         | 4.05%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.6%    |
| Generalplus Technology                 | 7         | 3.15%   |
| Quanta                                 | 5         | 2.25%   |
| Acer                                   | 5         | 2.25%   |
| Alcor Micro                            | 4         | 1.8%    |
| Syntek                                 | 3         | 1.35%   |
| Silicon Motion                         | 3         | 1.35%   |
| Luxvisions Innotech Limited            | 3         | 1.35%   |
| Lite-On Technology                     | 3         | 1.35%   |
| HD WEBCAM                              | 3         | 1.35%   |
| Lenovo                                 | 2         | 0.9%    |
| Z-Star Microelectronics                | 1         | 0.45%   |
| WCM_USB                                | 1         | 0.45%   |
| vivo                                   | 1         | 0.45%   |
| Sonix Technology                       | 1         | 0.45%   |
| Samsung Electronics                    | 1         | 0.45%   |
| Ricoh                                  | 1         | 0.45%   |
| Primax Electronics                     | 1         | 0.45%   |
| OmniVision Technologies                | 1         | 0.45%   |
| Jieli Technology                       | 1         | 0.45%   |
| icSpring                               | 1         | 0.45%   |
| eMPIA Technology                       | 1         | 0.45%   |
| Cubeternet                             | 1         | 0.45%   |
| ARC International                      | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 11        | 4.95%   |
| Chicony USB2.0 VGA UVC WebCam                           | 9         | 4.05%   |
| Sunplus Integrated_Webcam_HD                            | 5         | 2.25%   |
| Generalplus GENERAL WEBCAM                              | 5         | 2.25%   |
| Chicony Integrated Camera                               | 5         | 2.25%   |
| Chicony HD WebCam                                       | 5         | 2.25%   |
| Realtek Integrated_Webcam_HD                            | 4         | 1.8%    |
| IMC Networks USB2.0 UVC HD Webcam                       | 4         | 1.8%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.8%    |
| Chicony USB2.0 HD UVC WebCam                            | 4         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 4         | 1.8%    |
| Realtek USB Camera                                      | 3         | 1.35%   |
| Logitech Webcam C270                                    | 3         | 1.35%   |
| Logitech HD Pro Webcam C920                             | 3         | 1.35%   |
| IMC Networks Integrated Camera                          | 3         | 1.35%   |
| HD WEBCAM Web Camera                                    | 3         | 1.35%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.35%   |
| Chicony HP HD Webcam                                    | 3         | 1.35%   |
| Apple FaceTime HD Camera                                | 3         | 1.35%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 0.9%    |
| Suyin 1.3M HD WebCam                                    | 2         | 0.9%    |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 0.9%    |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 0.9%    |
| Realtek HD WebCam                                       | 2         | 0.9%    |
| Quanta HP TrueVision HD Camera                          | 2         | 0.9%    |
| Microdia Webcam Vitade AF                               | 2         | 0.9%    |
| Microdia USB 2.0 Camera                                 | 2         | 0.9%    |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.9%    |
| Logitech Webcam C170                                    | 2         | 0.9%    |
| Lite-On Integrated Camera                               | 2         | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 0.9%    |
| IMC Networks ov9734_azurewave_camera                    | 2         | 0.9%    |
| Generalplus 808 Camera #9 (web-cam mode)                | 2         | 0.9%    |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.9%    |
| Bison EasyCamera                                        | 2         | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 2         | 0.9%    |
| Apple FaceTime HD Camera (Built-in)                     | 2         | 0.9%    |
| Apple Built-in iSight                                   | 2         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 81.82%  |
| O2 Micro    | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 36.36%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Broadcom 58200                                                               | 2         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Broadcom 5880                                                                | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 300       | 73.35%  |
| 1     | 92        | 22.49%  |
| 2     | 13        | 3.18%   |
| 3     | 2         | 0.49%   |
| 6     | 1         | 0.24%   |
| 4     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 24.8%   |
| Graphics card            | 30        | 24%     |
| Net/wireless             | 24        | 19.2%   |
| Chipcard                 | 9         | 7.2%    |
| Multimedia controller    | 8         | 6.4%    |
| Communication controller | 5         | 4%      |
| Unassigned class         | 3         | 2.4%    |
| Storage                  | 3         | 2.4%    |
| Bluetooth                | 3         | 2.4%    |
| Storage/ide              | 2         | 1.6%    |
| Sound                    | 2         | 1.6%    |
| Net/ethernet             | 2         | 1.6%    |
| Network                  | 1         | 0.8%    |
| Card reader              | 1         | 0.8%    |
| Camera                   | 1         | 0.8%    |

