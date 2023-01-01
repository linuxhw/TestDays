Ubuntu Budgie 22.04 - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie_22.04/Notebook/README.md).

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

Total: 104

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Dell          | 0RW199                      | Desktop     | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | Notebook    | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | Notebook    | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| HP            | 828A                        | Desktop     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.15.0-27-generic     | 11        | 12.5%   |
| 5.15.0-52-generic     | 9         | 10.23%  |
| 5.15.0-50-generic     | 7         | 7.95%   |
| 5.15.0-48-generic     | 6         | 6.82%   |
| 5.15.0-30-generic     | 6         | 6.82%   |
| 5.15.0-46-generic     | 5         | 5.68%   |
| 5.15.0-39-generic     | 5         | 5.68%   |
| 5.15.0-33-generic     | 4         | 4.55%   |
| 5.15.0-25-generic     | 4         | 4.55%   |
| 5.15.0-56-generic     | 3         | 3.41%   |
| 5.15.0-53-generic     | 3         | 3.41%   |
| 5.15.0-47-generic     | 3         | 3.41%   |
| 5.15.0-43-generic     | 3         | 3.41%   |
| 5.15.0-40-generic     | 3         | 3.41%   |
| 5.15.0-41-generic     | 2         | 2.27%   |
| 5.19.0-051900-generic | 1         | 1.14%   |
| 5.17.2-051702-generic | 1         | 1.14%   |
| 5.16.2                | 1         | 1.14%   |
| 5.15.0-52-lowlatency  | 1         | 1.14%   |
| 5.15.0-47-lowlatency  | 1         | 1.14%   |
| 5.15.0-35-generic     | 1         | 1.14%   |
| 5.15.0-18-generic     | 1         | 1.14%   |
| 5.15.0-10056-tuxedo   | 1         | 1.14%   |
| 5.15.0-10052-tuxedo   | 1         | 1.14%   |
| 5.15.0-10047-tuxedo   | 1         | 1.14%   |
| 5.15.0-10041-tuxedo   | 1         | 1.14%   |
| 5.13.0-44-generic     | 1         | 1.14%   |
| 5.13.0-35-generic     | 1         | 1.14%   |
| 5.13.0-19-generic     | 1         | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 77        | 92.77%  |
| 5.13.0  | 3         | 3.61%   |
| 5.19.0  | 1         | 1.2%    |
| 5.17.2  | 1         | 1.2%    |
| 5.16.2  | 1         | 1.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 77        | 92.77%  |
| 5.13    | 3         | 3.61%   |
| 5.19    | 1         | 1.2%    |
| 5.17    | 1         | 1.2%    |
| 5.16    | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 83        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 80        | 96.39%  |
| GNOME  | 3         | 3.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 81        | 97.59%  |
| Wayland | 2         | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 56        | 67.47%  |
| Unknown | 19        | 22.89%  |
| GDM3    | 7         | 8.43%   |
| GDM     | 1         | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 31        | 37.35%  |
| de_DE | 11        | 13.25%  |
| fr_FR | 9         | 10.84%  |
| pt_BR | 6         | 7.23%   |
| en_GB | 5         | 6.02%   |
| en_CA | 3         | 3.61%   |
| ru_RU | 2         | 2.41%   |
| hu_HU | 2         | 2.41%   |
| es_MX | 2         | 2.41%   |
| es_ES | 2         | 2.41%   |
| it_IT | 1         | 1.2%    |
| fr_BE | 1         | 1.2%    |
| es_PE | 1         | 1.2%    |
| es_EC | 1         | 1.2%    |
| es_CL | 1         | 1.2%    |
| en_NZ | 1         | 1.2%    |
| en_IE | 1         | 1.2%    |
| el_GR | 1         | 1.2%    |
| cs_CZ | 1         | 1.2%    |
| C     | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 51        | 60.71%  |
| EFI  | 33        | 39.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 74        | 89.16%  |
| Overlay | 5         | 6.02%   |
| Btrfs   | 3         | 3.61%   |
| Xfs     | 1         | 1.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 44        | 53.01%  |
| Unknown | 36        | 43.37%  |
| MBR     | 3         | 3.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 80.72%  |
| Yes       | 16        | 19.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 71.43%  |
| Yes       | 24        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 13        | 15.66%  |
| Dell                   | 12        | 14.46%  |
| Hewlett-Packard        | 11        | 13.25%  |
| Gigabyte Technology    | 8         | 9.64%   |
| ASUSTek Computer       | 8         | 9.64%   |
| MSI                    | 5         | 6.02%   |
| Apple                  | 5         | 6.02%   |
| TUXEDO                 | 4         | 4.82%   |
| Intel                  | 3         | 3.61%   |
| Google                 | 2         | 2.41%   |
| Toshiba                | 1         | 1.2%    |
| Timi                   | 1         | 1.2%    |
| Samsung Electronics    | 1         | 1.2%    |
| Razer                  | 1         | 1.2%    |
| Fujitsu                | 1         | 1.2%    |
| Digibras               | 1         | 1.2%    |
| Chuwi                  | 1         | 1.2%    |
| Biostar                | 1         | 1.2%    |
| AXIOO                  | 1         | 1.2%    |
| Avell High Performance | 1         | 1.2%    |
| ASRock                 | 1         | 1.2%    |
| Acer                   | 1         | 1.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.2%    |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.2%    |
| TUXEDO Book BA1510                                   | 1         | 1.2%    |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.2%    |
| Toshiba Satellite A505                               | 1         | 1.2%    |
| Timi TM1604                                          | 1         | 1.2%    |
| Samsung 740U3M                                       | 1         | 1.2%    |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.2%    |
| MSI MS-7C95                                          | 1         | 1.2%    |
| MSI MS-7B86                                          | 1         | 1.2%    |
| MSI MS-7A32                                          | 1         | 1.2%    |
| MSI Modern 15 A10M                                   | 1         | 1.2%    |
| MSI GL62 6QF                                         | 1         | 1.2%    |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.2%    |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.2%    |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.2%    |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.2%    |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.2%    |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.2%    |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.2%    |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.2%    |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.2%    |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.2%    |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.2%    |
| Lenovo G500 20236                                    | 1         | 1.2%    |
| Lenovo G50-45 80E3                                   | 1         | 1.2%    |
| Intel STK1A32SC                                      | 1         | 1.2%    |
| Intel NUC12WSKi7                                     | 1         | 1.2%    |
| Intel DP55WB AAE64798-206                            | 1         | 1.2%    |
| HP Z440 Workstation                                  | 1         | 1.2%    |
| HP Spectre x360 Convertible 15t-df100                | 1         | 1.2%    |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.2%    |
| HP ProBook 445 G7                                    | 1         | 1.2%    |
| HP Pavilion g6                                       | 1         | 1.2%    |
| HP ENVY 17                                           | 1         | 1.2%    |
| HP ElitePad 1000 G2                                  | 1         | 1.2%    |
| HP EliteDesk 800 G1 DM                               | 1         | 1.2%    |
| HP EliteBook 840 G3                                  | 1         | 1.2%    |
| HP All-in-One 22-c0xx                                | 1         | 1.2%    |
| HP 750-417c                                          | 1         | 1.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 6.02%   |
| Lenovo IdeaPad    | 4         | 4.82%   |
| Dell Inspiron     | 4         | 4.82%   |
| ASUS VivoBook     | 3         | 3.61%   |
| TUXEDO Book       | 2         | 2.41%   |
| HP ProBook        | 2         | 2.41%   |
| Dell XPS          | 2         | 2.41%   |
| Dell Precision    | 2         | 2.41%   |
| Dell Latitude     | 2         | 2.41%   |
| TUXEDO Polaris    | 1         | 1.2%    |
| TUXEDO Aura       | 1         | 1.2%    |
| Toshiba Satellite | 1         | 1.2%    |
| Timi TM1604       | 1         | 1.2%    |
| Samsung 740U3M    | 1         | 1.2%    |
| Razer Blade       | 1         | 1.2%    |
| MSI MS-7C95       | 1         | 1.2%    |
| MSI MS-7B86       | 1         | 1.2%    |
| MSI MS-7A32       | 1         | 1.2%    |
| MSI Modern        | 1         | 1.2%    |
| MSI GL62          | 1         | 1.2%    |
| Lenovo V15        | 1         | 1.2%    |
| Lenovo Legion     | 1         | 1.2%    |
| Lenovo G500       | 1         | 1.2%    |
| Lenovo G50-45     | 1         | 1.2%    |
| Intel STK1A32SC   | 1         | 1.2%    |
| Intel NUC12WSKi7  | 1         | 1.2%    |
| Intel DP55WB      | 1         | 1.2%    |
| HP Z440           | 1         | 1.2%    |
| HP Spectre        | 1         | 1.2%    |
| HP Pavilion       | 1         | 1.2%    |
| HP ENVY           | 1         | 1.2%    |
| HP ElitePad       | 1         | 1.2%    |
| HP EliteDesk      | 1         | 1.2%    |
| HP EliteBook      | 1         | 1.2%    |
| HP All-in-One     | 1         | 1.2%    |
| HP 750-417c       | 1         | 1.2%    |
| Google Rabbid     | 1         | 1.2%    |
| Google Boten      | 1         | 1.2%    |
| Gigabyte X570S    | 1         | 1.2%    |
| Gigabyte M68MT-S2 | 1         | 1.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 13        | 15.66%  |
| 2020 | 12        | 14.46%  |
| 2018 | 8         | 9.64%   |
| 2019 | 7         | 8.43%   |
| 2016 | 7         | 8.43%   |
| 2014 | 6         | 7.23%   |
| 2010 | 5         | 6.02%   |
| 2017 | 4         | 4.82%   |
| 2013 | 4         | 4.82%   |
| 2022 | 3         | 3.61%   |
| 2015 | 3         | 3.61%   |
| 2011 | 3         | 3.61%   |
| 2009 | 3         | 3.61%   |
| 2008 | 3         | 3.61%   |
| 2012 | 2         | 2.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 52        | 62.65%  |
| Desktop     | 23        | 27.71%  |
| Convertible | 4         | 4.82%   |
| Mini pc     | 2         | 2.41%   |
| All in one  | 2         | 2.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 95.18%  |
| Enabled  | 4         | 4.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 81        | 97.59%  |
| Yes  | 2         | 2.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 23        | 27.71%  |
| 16.01-24.0      | 23        | 27.71%  |
| 8.01-16.0       | 15        | 18.07%  |
| 32.01-64.0      | 8         | 9.64%   |
| 3.01-4.0        | 8         | 9.64%   |
| 64.01-256.0     | 2         | 2.41%   |
| 1.01-2.0        | 2         | 2.41%   |
| More than 256.0 | 1         | 1.2%    |
| 24.01-32.0      | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 29        | 33.72%  |
| 2.01-3.0   | 26        | 30.23%  |
| 4.01-8.0   | 18        | 20.93%  |
| 3.01-4.0   | 7         | 8.14%   |
| 8.01-16.0  | 5         | 5.81%   |
| 24.01-32.0 | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 54.76%  |
| 2      | 27        | 32.14%  |
| 3      | 5         | 5.95%   |
| 4      | 3         | 3.57%   |
| 6      | 2         | 2.38%   |
| 7      | 1         | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 74.7%   |
| Yes       | 21        | 25.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 77.11%  |
| No        | 19        | 22.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 85.54%  |
| No        | 12        | 14.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 72.29%  |
| No        | 23        | 27.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 20        | 24.1%   |
| Germany            | 10        | 12.05%  |
| France             | 8         | 9.64%   |
| Brazil             | 7         | 8.43%   |
| UK                 | 2         | 2.41%   |
| Switzerland        | 2         | 2.41%   |
| Slovenia           | 2         | 2.41%   |
| Mexico             | 2         | 2.41%   |
| Hungary            | 2         | 2.41%   |
| Greece             | 2         | 2.41%   |
| Canada             | 2         | 2.41%   |
| Sweden             | 1         | 1.2%    |
| Spain              | 1         | 1.2%    |
| Russia             | 1         | 1.2%    |
| Romania            | 1         | 1.2%    |
| Poland             | 1         | 1.2%    |
| Peru               | 1         | 1.2%    |
| Norway             | 1         | 1.2%    |
| New Zealand        | 1         | 1.2%    |
| Netherlands        | 1         | 1.2%    |
| Italy              | 1         | 1.2%    |
| Ireland            | 1         | 1.2%    |
| Indonesia          | 1         | 1.2%    |
| Ghana              | 1         | 1.2%    |
| Ecuador            | 1         | 1.2%    |
| Dominican Republic | 1         | 1.2%    |
| Czechia            | 1         | 1.2%    |
| Croatia            | 1         | 1.2%    |
| Chile              | 1         | 1.2%    |
| Cabo Verde         | 1         | 1.2%    |
| Belgium            | 1         | 1.2%    |
| Belarus            | 1         | 1.2%    |
| Austria            | 1         | 1.2%    |
| Argentina          | 1         | 1.2%    |
| Algeria            | 1         | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Milwaukee             | 2         | 2.38%   |
| Budapest              | 2         | 2.38%   |
| Athens                | 2         | 2.38%   |
| Zurich                | 1         | 1.19%   |
| West Lafayette        | 1         | 1.19%   |
| Wertheim am Main      | 1         | 1.19%   |
| Weisswasser           | 1         | 1.19%   |
| Warsaw                | 1         | 1.19%   |
| Walled Lake           | 1         | 1.19%   |
| Vienna                | 1         | 1.19%   |
| Victoria              | 1         | 1.19%   |
| Venray                | 1         | 1.19%   |
| Trondheim             | 1         | 1.19%   |
| Tocantins             | 1         | 1.19%   |
| Targu Frumos          | 1         | 1.19%   |
| Tarakan               | 1         | 1.19%   |
| Tann                  | 1         | 1.19%   |
| Tampa                 | 1         | 1.19%   |
| Sunnyvale             | 1         | 1.19%   |
| St Petersburg         | 1         | 1.19%   |
| Siegen                | 1         | 1.19%   |
| Sétif                | 1         | 1.19%   |
| Seelze                | 1         | 1.19%   |
| Seattle               | 1         | 1.19%   |
| Sao Paulo             | 1         | 1.19%   |
| Sao Bernardo do Campo | 1         | 1.19%   |
| Santo Domingo Este    | 1         | 1.19%   |
| Santiago              | 1         | 1.19%   |
| San Luis Potosí City | 1         | 1.19%   |
| Saint-Gilles          | 1         | 1.19%   |
| Rueil-Malmaison       | 1         | 1.19%   |
| Recife                | 1         | 1.19%   |
| Queens                | 1         | 1.19%   |
| Pula                  | 1         | 1.19%   |
| Puebla City           | 1         | 1.19%   |
| Praia                 | 1         | 1.19%   |
| Postojna              | 1         | 1.19%   |
| Pine Island           | 1         | 1.19%   |
| Ostrava               | 1         | 1.19%   |
| Orvault               | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 20        | 36     | 15.63%  |
| Seagate                        | 12        | 17     | 9.38%   |
| Unknown                        | 10        | 10     | 7.81%   |
| WDC                            | 9         | 11     | 7.03%   |
| Toshiba                        | 9         | 10     | 7.03%   |
| Crucial                        | 8         | 9      | 6.25%   |
| SK hynix                       | 5         | 5      | 3.91%   |
| SanDisk                        | 5         | 6      | 3.91%   |
| Intel                          | 5         | 7      | 3.91%   |
| Micron Technology              | 4         | 4      | 3.13%   |
| Kingston                       | 4         | 5      | 3.13%   |
| SPCC                           | 3         | 3      | 2.34%   |
| JMicron Technology             | 3         | 3      | 2.34%   |
| China                          | 3         | 4      | 2.34%   |
| Phison                         | 2         | 2      | 1.56%   |
| OCZ                            | 2         | 2      | 1.56%   |
| A-DATA Technology              | 2         | 2      | 1.56%   |
| Zheino                         | 1         | 1      | 0.78%   |
| VISIPRO                        | 1         | 1      | 0.78%   |
| Union Memory                   | 1         | 1      | 0.78%   |
| Transcend                      | 1         | 1      | 0.78%   |
| TO Exter                       | 1         | 1      | 0.78%   |
| Solid State Storage Technology | 1         | 1      | 0.78%   |
| SABRENT                        | 1         | 1      | 0.78%   |
| Realtek Semiconductor          | 1         | 1      | 0.78%   |
| PNY                            | 1         | 1      | 0.78%   |
| Phison Electronics             | 1         | 1      | 0.78%   |
| OWC                            | 1         | 1      | 0.78%   |
| Netac                          | 1         | 1      | 0.78%   |
| Mushkin                        | 1         | 1      | 0.78%   |
| Maxtor                         | 1         | 1      | 0.78%   |
| LITEON                         | 1         | 1      | 0.78%   |
| KIOXIA                         | 1         | 1      | 0.78%   |
| HGST                           | 1         | 1      | 0.78%   |
| Hewlett-Packard                | 1         | 1      | 0.78%   |
| Corsair                        | 1         | 2      | 0.78%   |
| ASMT109x                       | 1         | 1      | 0.78%   |
| Apple                          | 1         | 1      | 0.78%   |
| Unknown                        | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.42%   |
| Unknown SD64G  64GB                    | 2         | 1.42%   |
| Unknown SD/MMC/MS PRO 64GB             | 2         | 1.42%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 1.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 1.42%   |
| SanDisk SDSSDA120G 120GB               | 2         | 1.42%   |
| Samsung SSD 980 PRO 2TB                | 2         | 1.42%   |
| Samsung SSD 980 500GB                  | 2         | 1.42%   |
| Samsung SSD 870 EVO 250GB              | 2         | 1.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 1.42%   |
| JMicron Generic 240GB SSD              | 2         | 1.42%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 1.42%   |
| Crucial CT1000MX500SSD1 1TB            | 2         | 1.42%   |
| Zheino CHN-25SATAC3-120 120GB          | 1         | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.71%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.71%   |
| WDC WD40PURZ-85TTDY0 4TB               | 1         | 0.71%   |
| WDC WD1600AAJS-60WAA0 160GB            | 1         | 0.71%   |
| WDC WD10JPVX-75JC3T0 1TB               | 1         | 0.71%   |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 0.71%   |
| WDC WD10EADS-00M2B0 1TB                | 1         | 0.71%   |
| WDC PC SN730 NVMe 256GB                | 1         | 0.71%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB   | 1         | 0.71%   |
| VISIPRO SSD 256GB                      | 1         | 0.71%   |
| Unknown SL128  128GB                   | 1         | 0.71%   |
| Unknown SA16G  16GB                    | 1         | 0.71%   |
| Unknown NCard  4GB                     | 1         | 0.71%   |
| Unknown MMC128  128GB                  | 1         | 0.71%   |
| Unknown MMC Card  64GB                 | 1         | 0.71%   |
| Unknown MMC Card  128GB                | 1         | 0.71%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD | 1         | 0.71%   |
| Transcend TS128GMTE110S 128GB          | 1         | 0.71%   |
| Toshiba XG6 NVMe SSD Controller 256GB  | 1         | 0.71%   |
| Toshiba TR150 480GB SSD                | 1         | 0.71%   |
| Toshiba MQ04ABF100 1TB                 | 1         | 0.71%   |
| Toshiba KXG50ZNV512G NVMe 512GB        | 1         | 0.71%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 1         | 0.71%   |
| Toshiba KBG30ZMT256G 256GB             | 1         | 0.71%   |
| Toshiba HDWD240 4TB                    | 1         | 0.71%   |
| Toshiba HDWD220 2TB                    | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 16     | 40%     |
| WDC                 | 7         | 8      | 23.33%  |
| Toshiba             | 4         | 4      | 13.33%  |
| Unknown             | 2         | 2      | 6.67%   |
| Samsung Electronics | 2         | 3      | 6.67%   |
| Maxtor              | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| ASMT109x            | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 20     | 17.39%  |
| Crucial             | 8         | 9      | 17.39%  |
| China               | 3         | 4      | 6.52%   |
| SPCC                | 2         | 2      | 4.35%   |
| SanDisk             | 2         | 2      | 4.35%   |
| Micron Technology   | 2         | 2      | 4.35%   |
| JMicron Technology  | 2         | 2      | 4.35%   |
| Zheino              | 1         | 1      | 2.17%   |
| WDC                 | 1         | 1      | 2.17%   |
| VISIPRO             | 1         | 1      | 2.17%   |
| Union Memory        | 1         | 1      | 2.17%   |
| Toshiba             | 1         | 1      | 2.17%   |
| TO Exter            | 1         | 1      | 2.17%   |
| SK hynix            | 1         | 1      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| OWC                 | 1         | 1      | 2.17%   |
| OCZ                 | 1         | 1      | 2.17%   |
| Netac               | 1         | 1      | 2.17%   |
| Mushkin             | 1         | 1      | 2.17%   |
| LITEON              | 1         | 1      | 2.17%   |
| Kingston            | 1         | 2      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| Hewlett-Packard     | 1         | 1      | 2.17%   |
| Corsair             | 1         | 2      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 38        | 62     | 34.86%  |
| NVMe    | 37        | 48     | 33.94%  |
| HDD     | 23        | 36     | 21.1%   |
| MMC     | 10        | 12     | 9.17%   |
| Unknown | 1         | 1      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 92     | 48.57%  |
| NVMe | 37        | 47     | 35.24%  |
| MMC  | 10        | 12     | 9.52%   |
| SAS  | 7         | 8      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 67     | 65.22%  |
| 0.51-1.0   | 16        | 22     | 23.19%  |
| 1.01-2.0   | 5         | 6      | 7.25%   |
| 3.01-4.0   | 3         | 3      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 32.53%  |
| 251-500        | 22        | 26.51%  |
| 51-100         | 10        | 12.05%  |
| 501-1000       | 7         | 8.43%   |
| 1001-2000      | 6         | 7.23%   |
| 21-50          | 4         | 4.82%   |
| More than 3000 | 3         | 3.61%   |
| 1-20           | 3         | 3.61%   |
| 2001-3000      | 1         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 23        | 27.38%  |
| 1-20      | 23        | 27.38%  |
| 101-250   | 13        | 15.48%  |
| 51-100    | 12        | 14.29%  |
| 251-500   | 6         | 7.14%   |
| 501-1000  | 4         | 4.76%   |
| 1001-2000 | 2         | 2.38%   |
| 2001-3000 | 1         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 55        | 105    | 60.44%  |
| Works    | 34        | 52     | 37.36%  |
| Malfunc  | 2         | 2      | 2.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 48        | 45.28%  |
| AMD                            | 17        | 16.04%  |
| Samsung Electronics            | 11        | 10.38%  |
| SanDisk                        | 4         | 3.77%   |
| Toshiba America Info Systems   | 3         | 2.83%   |
| Phison Electronics             | 3         | 2.83%   |
| Nvidia                         | 3         | 2.83%   |
| Kingston Technology Company    | 3         | 2.83%   |
| SK hynix                       | 2         | 1.89%   |
| Micron Technology              | 2         | 1.89%   |
| KIOXIA                         | 2         | 1.89%   |
| Transcend                      | 1         | 0.94%   |
| Solid State Storage Technology | 1         | 0.94%   |
| Seagate Technology             | 1         | 0.94%   |
| Realtek Semiconductor          | 1         | 0.94%   |
| OCZ Technology Group           | 1         | 0.94%   |
| Marvell Technology Group       | 1         | 0.94%   |
| JMicron Technology             | 1         | 0.94%   |
| ADATA Technology               | 1         | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 11        | 9.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 7         | 5.83%   |
| Intel Volume Management Device NVMe RAID Controller                          | 4         | 3.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 3         | 2.5%    |
| Samsung NVMe SSD Controller 980                                              | 3         | 2.5%    |
| Intel Non-Volatile memory controller                                         | 3         | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 1.67%   |
| Phison PS5013 E13 NVMe Controller                                            | 2         | 1.67%   |
| Nvidia MCP79 AHCI Controller                                                 | 2         | 1.67%   |
| Micron Non-Volatile memory controller                                        | 2         | 1.67%   |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 1.67%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 2         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 2         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 2         | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 2         | 1.67%   |
| AMD 500 Series Chipset SATA Controller                                       | 2         | 1.67%   |
| AMD 400 Series Chipset SATA Controller                                       | 2         | 1.67%   |
| Transcend Non-Volatile memory controller                                     | 1         | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.83%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.83%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 0.83%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 0.83%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 0.83%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 0.83%   |
| Seagate Non-Volatile memory controller                                       | 1         | 0.83%   |
| SanDisk WD Blue SN570 NVMe SSD                                               | 1         | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 1         | 0.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 0.83%   |
| Samsung NVMe SSD Controller 172X                                             | 1         | 0.83%   |
| Realtek Realtek Non-Volatile memory controller                               | 1         | 0.83%   |
| Phison NVMe Storage Controller                                               | 1         | 0.83%   |
| OCZ Group RD400/400A SSD                                                     | 1         | 0.83%   |
| Nvidia MCP61 SATA Controller                                                 | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 57        | 52.29%  |
| NVMe | 37        | 33.94%  |
| IDE  | 9         | 8.26%   |
| RAID | 6         | 5.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 75.9%   |
| AMD    | 20        | 24.1%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 4.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 2.41%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 2.41%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 2.41%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.41%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.41%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.41%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 2.41%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.41%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 2.41%   |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 1.2%    |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 1.2%    |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 1.2%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.2%    |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.2%    |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.2%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.2%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.2%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.2%    |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 1.2%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.2%    |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 1.2%    |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1         | 1.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.2%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.2%    |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 1.2%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.2%    |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 1.2%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.2%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 19        | 22.89%  |
| Other                | 11        | 13.25%  |
| Intel Core i7        | 9         | 10.84%  |
| AMD Ryzen 5          | 9         | 10.84%  |
| Intel Celeron        | 6         | 7.23%   |
| Intel Core i3        | 4         | 4.82%   |
| Intel Atom           | 4         | 4.82%   |
| Intel Xeon           | 3         | 3.61%   |
| Intel Core 2 Duo     | 3         | 3.61%   |
| AMD Ryzen 7          | 2         | 2.41%   |
| Intel Pentium Silver | 1         | 1.2%    |
| Intel Pentium        | 1         | 1.2%    |
| Intel Core i9        | 1         | 1.2%    |
| Intel Core 2 Quad    | 1         | 1.2%    |
| AMD Ryzen 9          | 1         | 1.2%    |
| AMD Ryzen 3          | 1         | 1.2%    |
| AMD Phenom II X4     | 1         | 1.2%    |
| AMD FX               | 1         | 1.2%    |
| AMD Athlon II X3     | 1         | 1.2%    |
| AMD Athlon           | 1         | 1.2%    |
| AMD A8               | 1         | 1.2%    |
| AMD A4               | 1         | 1.2%    |
| AMD A10              | 1         | 1.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 36        | 43.37%  |
| 2      | 28        | 33.73%  |
| 6      | 7         | 8.43%   |
| 8      | 6         | 7.23%   |
| 12     | 2         | 2.41%   |
| 16     | 1         | 1.2%    |
| 10     | 1         | 1.2%    |
| 3      | 1         | 1.2%    |
| 1      | 1         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 98.8%   |
| 2      | 1         | 1.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 68.67%  |
| 1      | 26        | 31.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 83        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 52.94%  |
| 0x806c1    | 3         | 3.53%   |
| 0x206a7    | 3         | 3.53%   |
| 0x08600106 | 3         | 3.53%   |
| 0x08108102 | 3         | 3.53%   |
| 0x806ec    | 2         | 2.35%   |
| 0x706a8    | 2         | 2.35%   |
| 0x406f1    | 2         | 2.35%   |
| 0x306a9    | 2         | 2.35%   |
| 0x0a50000c | 2         | 2.35%   |
| 0xa0671    | 1         | 1.18%   |
| 0x906eb    | 1         | 1.18%   |
| 0x906ea    | 1         | 1.18%   |
| 0x906a3    | 1         | 1.18%   |
| 0x806eb    | 1         | 1.18%   |
| 0x806d1    | 1         | 1.18%   |
| 0x506c9    | 1         | 1.18%   |
| 0x406c4    | 1         | 1.18%   |
| 0x40651    | 1         | 1.18%   |
| 0x306d4    | 1         | 1.18%   |
| 0x30678    | 1         | 1.18%   |
| 0x20655    | 1         | 1.18%   |
| 0x106e5    | 1         | 1.18%   |
| 0x1067a    | 1         | 1.18%   |
| 0x10677    | 1         | 1.18%   |
| 0x08108109 | 1         | 1.18%   |
| 0x07030104 | 1         | 1.18%   |
| 0x06001119 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 16.87%  |
| Zen+             | 6         | 7.23%   |
| TigerLake        | 6         | 7.23%   |
| Penryn           | 5         | 6.02%   |
| IvyBridge        | 5         | 6.02%   |
| Unknown          | 5         | 6.02%   |
| Zen 3            | 4         | 4.82%   |
| Skylake          | 4         | 4.82%   |
| Silvermont       | 4         | 4.82%   |
| Zen 2            | 3         | 3.61%   |
| SandyBridge      | 3         | 3.61%   |
| Icelake          | 3         | 3.61%   |
| Haswell          | 3         | 3.61%   |
| Goldmont plus    | 3         | 3.61%   |
| Broadwell        | 3         | 3.61%   |
| Nehalem          | 2         | 2.41%   |
| K10              | 2         | 2.41%   |
| Westmere         | 1         | 1.2%    |
| Steamroller      | 1         | 1.2%    |
| Puma             | 1         | 1.2%    |
| Piledriver       | 1         | 1.2%    |
| Goldmont         | 1         | 1.2%    |
| CometLake        | 1         | 1.2%    |
| Bulldozer        | 1         | 1.2%    |
| Alderlake Hybrid | 1         | 1.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 53.54%  |
| Nvidia | 23        | 23.23%  |
| AMD    | 23        | 23.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 5.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 4.95%   |
| Intel UHD Graphics 620                                                      | 4         | 3.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 2.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 2.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 2.97%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 2.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 2.97%   |
| AMD Renoir                                                                  | 3         | 2.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 2.97%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 1.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.98%   |
| Intel JasperLake [UHD Graphics]                                             | 2         | 1.98%   |
| Intel HD Graphics 620                                                       | 2         | 1.98%   |
| Intel HD Graphics 530                                                       | 2         | 1.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.98%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 1.98%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                      | 1         | 0.99%   |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.99%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.99%   |
| Nvidia GP108M [GeForce MX230]                                               | 1         | 0.99%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.99%   |
| Nvidia GP104GL [Quadro P4000]                                               | 1         | 0.99%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.99%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 0.99%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 0.99%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1         | 0.99%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1         | 0.99%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1         | 0.99%   |
| Nvidia GF110 [GeForce GTX 570]                                              | 1         | 0.99%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 0.99%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                          | 1         | 0.99%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1         | 0.99%   |
| Nvidia C79 [GeForce 9400]                                                   | 1         | 0.99%   |
| Nvidia C79 [GeForce 9400M]                                                  | 1         | 0.99%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1         | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 0.99%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 44.58%  |
| 1 x AMD        | 18        | 21.69%  |
| Intel + Nvidia | 11        | 13.25%  |
| 1 x Nvidia     | 10        | 12.05%  |
| Intel + AMD    | 2         | 2.41%   |
| AMD + Nvidia   | 2         | 2.41%   |
| Other          | 1         | 1.2%    |
| 2 x Intel      | 1         | 1.2%    |
| 2 x AMD        | 1         | 1.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 71        | 85.54%  |
| Proprietary | 10        | 12.05%  |
| Unknown     | 2         | 2.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 75.9%   |
| 1.01-2.0   | 7         | 8.43%   |
| 0.01-0.5   | 6         | 7.23%   |
| 7.01-8.0   | 3         | 3.61%   |
| 0.51-1.0   | 3         | 3.61%   |
| 3.01-4.0   | 1         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 16        | 17.58%  |
| Chimei Innolux          | 15        | 16.48%  |
| BOE                     | 14        | 15.38%  |
| AU Optronics            | 7         | 7.69%   |
| LG Display              | 5         | 5.49%   |
| Apple                   | 5         | 5.49%   |
| Hewlett-Packard         | 4         | 4.4%    |
| Sharp                   | 3         | 3.3%    |
| Philips                 | 3         | 3.3%    |
| SANYO                   | 2         | 2.2%    |
| Goldstar                | 2         | 2.2%    |
| Vestel Elektronik       | 1         | 1.1%    |
| Unknown (XXX)           | 1         | 1.1%    |
| Unknown (AAA)           | 1         | 1.1%    |
| Sony                    | 1         | 1.1%    |
| Panasonic               | 1         | 1.1%    |
| ONN                     | 1         | 1.1%    |
| MStar                   | 1         | 1.1%    |
| Lenovo                  | 1         | 1.1%    |
| IBM                     | 1         | 1.1%    |
| Fujitsu Siemens         | 1         | 1.1%    |
| Denver                  | 1         | 1.1%    |
| Dell                    | 1         | 1.1%    |
| Chi Mei Optoelectronics | 1         | 1.1%    |
| BenQ                    | 1         | 1.1%    |
| AOC                     | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 2.17%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch   | 1         | 1.09%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 1         | 1.09%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1         | 1.09%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 1.09%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 1.09%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 1.09%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 1.09%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                 | 1         | 1.09%   |
| SANYO LCD SAN0A12 1920x540                                             | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch   | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 1.09%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1         | 1.09%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch      | 1         | 1.09%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 1.09%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 480x270mm 21.7-inch      | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 1.09%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch      | 1         | 1.09%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1         | 1.09%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                | 1         | 1.09%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch               | 1         | 1.09%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch                | 1         | 1.09%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                    | 1         | 1.09%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                                | 1         | 1.09%   |
| ONN ONN50 ONN3458 3840x2160 575x323mm 26.0-inch                        | 1         | 1.09%   |
| MStar LCD TV MST9000 1360x768                                          | 1         | 1.09%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch            | 1         | 1.09%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch            | 1         | 1.09%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch               | 1         | 1.09%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                  | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 42.53%  |
| 1366x768 (WXGA)    | 16        | 18.39%  |
| 3840x2160 (4K)     | 6         | 6.9%    |
| 2560x1440 (QHD)    | 5         | 5.75%   |
| 1920x1200 (WUXGA)  | 4         | 4.6%    |
| 1920x540           | 3         | 3.45%   |
| 1680x1050 (WSXGA+) | 3         | 3.45%   |
| 1600x900 (HD+)     | 3         | 3.45%   |
| 1280x800 (WXGA)    | 3         | 3.45%   |
| 3456x2160          | 1         | 1.15%   |
| 3440x1440          | 1         | 1.15%   |
| 2880x1800          | 1         | 1.15%   |
| 2560x1600          | 1         | 1.15%   |
| 1440x900 (WXGA+)   | 1         | 1.15%   |
| 1360x768           | 1         | 1.15%   |
| 1280x1024 (SXGA)   | 1         | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 27.47%  |
| 13      | 14        | 15.38%  |
| 27      | 7         | 7.69%   |
| 24      | 6         | 6.59%   |
| 14      | 6         | 6.59%   |
| 21      | 5         | 5.49%   |
| 23      | 4         | 4.4%    |
| 17      | 4         | 4.4%    |
| 11      | 3         | 3.3%    |
| Unknown | 3         | 3.3%    |
| 40      | 2         | 2.2%    |
| 31      | 2         | 2.2%    |
| 84      | 1         | 1.1%    |
| 72      | 1         | 1.1%    |
| 60      | 1         | 1.1%    |
| 54      | 1         | 1.1%    |
| 47      | 1         | 1.1%    |
| 34      | 1         | 1.1%    |
| 33      | 1         | 1.1%    |
| 26      | 1         | 1.1%    |
| 18      | 1         | 1.1%    |
| 10      | 1         | 1.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 41.11%  |
| 501-600     | 16        | 17.78%  |
| 201-300     | 11        | 12.22%  |
| 401-500     | 7         | 7.78%   |
| 351-400     | 5         | 5.56%   |
| 1001-1500   | 3         | 3.33%   |
| Unknown     | 3         | 3.33%   |
| 801-900     | 2         | 2.22%   |
| 701-800     | 2         | 2.22%   |
| 601-700     | 2         | 2.22%   |
| 1501-2000   | 2         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 65        | 79.27%  |
| 16/10   | 13        | 15.85%  |
| 32/9    | 1         | 1.22%   |
| 3/2     | 1         | 1.22%   |
| 21/9    | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 28.09%  |
| 81-90          | 16        | 17.98%  |
| 201-250        | 10        | 11.24%  |
| 301-350        | 7         | 7.87%   |
| More than 1000 | 4         | 4.49%   |
| 71-80          | 4         | 4.49%   |
| 351-500        | 4         | 4.49%   |
| 121-130        | 4         | 4.49%   |
| 51-60          | 3         | 3.37%   |
| 251-300        | 3         | 3.37%   |
| 501-1000       | 3         | 3.37%   |
| Unknown        | 3         | 3.37%   |
| 41-50          | 1         | 1.12%   |
| 151-200        | 1         | 1.12%   |
| 141-150        | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 28.09%  |
| 101-120       | 21        | 23.6%   |
| 51-100        | 20        | 22.47%  |
| 161-240       | 9         | 10.11%  |
| 1-50          | 6         | 6.74%   |
| More than 240 | 5         | 5.62%   |
| Unknown       | 3         | 3.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 71        | 84.52%  |
| 2     | 12        | 14.29%  |
| 0     | 1         | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 36.97%  |
| Realtek Semiconductor | 43        | 36.13%  |
| Qualcomm Atheros      | 10        | 8.4%    |
| Broadcom              | 9         | 7.56%   |
| Nvidia                | 3         | 2.52%   |
| MediaTek              | 3         | 2.52%   |
| Hewlett-Packard       | 2         | 1.68%   |
| Broadcom Limited      | 2         | 1.68%   |
| Ralink Technology     | 1         | 0.84%   |
| Huawei Technologies   | 1         | 0.84%   |
| ASIX Electronics      | 1         | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 25        | 17.61%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 4.23%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 4.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.82%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 2.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.41%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 1.41%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.41%   |
| Intel Wireless 8260                                                     | 2         | 1.41%   |
| Intel Wireless 7265                                                     | 2         | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.41%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 1.41%   |
| Intel Ethernet Controller I225-V                                        | 2         | 1.41%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 1.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 1.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.7%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.7%    |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.7%    |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.7%    |
| Realtek 802.11ac NIC                                                    | 1         | 0.7%    |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.7%    |
| Nvidia MCP61 Ethernet                                                   | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 49.32%  |
| Realtek Semiconductor | 15        | 20.55%  |
| Qualcomm Atheros      | 8         | 10.96%  |
| Broadcom              | 8         | 10.96%  |
| MediaTek              | 3         | 4.11%   |
| Ralink Technology     | 1         | 1.37%   |
| Hewlett-Packard       | 1         | 1.37%   |
| Broadcom Limited      | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 6         | 8.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 6.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5.48%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 5.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 5.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 4.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.74%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.74%   |
| Intel Wireless 8260                                                     | 2         | 2.74%   |
| Intel Wireless 7265                                                     | 2         | 2.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.74%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.37%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.37%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.37%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.37%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.37%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.37%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.37%   |
| Intel Wireless 7260                                                     | 1         | 1.37%   |
| Intel Wireless 3165                                                     | 1         | 1.37%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.37%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.37%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.37%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 1         | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 58.46%  |
| Intel                 | 15        | 23.08%  |
| Broadcom              | 4         | 6.15%   |
| Nvidia                | 3         | 4.62%   |
| Qualcomm Atheros      | 2         | 3.08%   |
| Hewlett-Packard       | 1         | 1.54%   |
| Broadcom Limited      | 1         | 1.54%   |
| ASIX Electronics      | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 36.76%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 8.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.94%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.94%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.47%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.47%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.47%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.47%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.47%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.47%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.47%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.47%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.47%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 1.47%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.47%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 52.21%  |
| Ethernet | 64        | 47.06%  |
| Modem    | 1         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 68.67%  |
| Ethernet | 26        | 31.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 55.42%  |
| 1     | 33        | 39.76%  |
| 0     | 4         | 4.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 71.76%  |
| Yes  | 24        | 28.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 51.67%  |
| Realtek Semiconductor           | 6         | 10%     |
| Qualcomm Atheros Communications | 5         | 8.33%   |
| Apple                           | 5         | 8.33%   |
| Broadcom                        | 3         | 5%      |
| IMC Networks                    | 2         | 3.33%   |
| Dell                            | 2         | 3.33%   |
| Cambridge Silicon Radio         | 2         | 3.33%   |
| Unknown                         | 1         | 1.67%   |
| MediaTek                        | 1         | 1.67%   |
| Lite-On Technology              | 1         | 1.67%   |
| Foxconn International           | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 15%     |
| Intel AX201 Bluetooth                               | 9         | 15%     |
| Realtek Bluetooth Radio                             | 4         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 6.67%   |
| Intel AX200 Bluetooth                               | 4         | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 5%      |
| Apple Bluetooth USB Host Controller                 | 3         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.33%   |
| Intel AX210 Bluetooth                               | 2         | 3.33%   |
| Dell DW375 Bluetooth Module                         | 2         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.33%   |
| Apple Bluetooth Host Controller                     | 2         | 3.33%   |
| Unknown Bluetooth Device                            | 1         | 1.67%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.67%   |
| MediaTek Wireless_Device                            | 1         | 1.67%   |
| Lite-On Bluetooth Radio                             | 1         | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.67%   |
| Intel Bluetooth Device                              | 1         | 1.67%   |
| IMC Networks Wireless_Device                        | 1         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.67%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 56        | 56%     |
| AMD                   | 23        | 23%     |
| Nvidia                | 15        | 15%     |
| Plantronics           | 2         | 2%      |
| Texas Instruments     | 1         | 1%      |
| Realtek Semiconductor | 1         | 1%      |
| LINE TECH INDUSTRIAL  | 1         | 1%      |
| Apple                 | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 9.92%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 7.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 5.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 4.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 4.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 4.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 3.31%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 2.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.48%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.48%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.65%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 1.65%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.65%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 1.65%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.65%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.83%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.83%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 0.83%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.83%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.83%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.83%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.83%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.83%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.83%   |
| Nvidia GF110 High Definition Audio Controller                              | 1         | 0.83%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 25.42%  |
| SK hynix            | 13        | 22.03%  |
| Kingston            | 9         | 15.25%  |
| Crucial             | 5         | 8.47%   |
| Micron Technology   | 3         | 5.08%   |
| Unknown (ABCD)      | 2         | 3.39%   |
| Ramaxel Technology  | 2         | 3.39%   |
| Elpida              | 2         | 3.39%   |
| Unknown             | 1         | 1.69%   |
| Transcend           | 1         | 1.69%   |
| Teikon              | 1         | 1.69%   |
| fef5                | 1         | 1.69%   |
| Corsair             | 1         | 1.69%   |
| A-DATA Technology   | 1         | 1.69%   |
| 8945000080AD        | 1         | 1.69%   |
| Unknown             | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.23%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 3.23%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 3.23%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.61%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 1.61%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.61%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.61%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 1.61%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.61%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.61%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 1         | 1.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.61%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.61%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.61%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.61%   |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s         | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s             | 1         | 1.61%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.61%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 1         | 1.61%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.61%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s     | 1         | 1.61%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Micron RAM 16JTF51264AZ-1G4D1 4GB DIMM DDR3 1333MT/s             | 1         | 1.61%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 27        | 56.25%  |
| DDR3    | 13        | 27.08%  |
| LPDDR4  | 6         | 12.5%   |
| SDRAM   | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 69.57%  |
| DIMM         | 9         | 19.57%  |
| Row Of Chips | 3         | 6.52%   |
| Chip         | 1         | 2.17%   |
| Unknown      | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 44.9%   |
| 4096  | 11        | 22.45%  |
| 16384 | 7         | 14.29%  |
| 32768 | 4         | 8.16%   |
| 2048  | 4         | 8.16%   |
| 1024  | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 12        | 23.08%  |
| 2667  | 9         | 17.31%  |
| 2400  | 9         | 17.31%  |
| 1600  | 9         | 17.31%  |
| 1333  | 3         | 5.77%   |
| 4267  | 2         | 3.85%   |
| 1067  | 2         | 3.85%   |
| 1066  | 2         | 3.85%   |
| 3600  | 1         | 1.92%   |
| 3266  | 1         | 1.92%   |
| 2133  | 1         | 1.92%   |
| 1334  | 1         | 1.92%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung ML-1510 Laser Printer | 1         | 33.33%  |
| HP LaserJet 1320              | 1         | 33.33%  |
| Canon LiDE 400                | 1         | 33.33%  |

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
| Chicony Electronics                    | 12        | 22.64%  |
| IMC Networks                           | 7         | 13.21%  |
| Realtek Semiconductor                  | 5         | 9.43%   |
| Apple                                  | 5         | 9.43%   |
| Acer                                   | 4         | 7.55%   |
| Syntek                                 | 3         | 5.66%   |
| Sunplus Innovation Technology          | 3         | 5.66%   |
| Microdia                               | 3         | 5.66%   |
| Logitech                               | 2         | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.77%   |
| Unknown                                | 1         | 1.89%   |
| Samsung Electronics                    | 1         | 1.89%   |
| Quanta                                 | 1         | 1.89%   |
| Polycom                                | 1         | 1.89%   |
| DJJHFA1BIF5595                         | 1         | 1.89%   |
| Alcor Micro                            | 1         | 1.89%   |
| Unknown                                | 1         | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 3         | 5.66%   |
| IMC Networks Integrated Camera                                             | 3         | 5.66%   |
| Syntek Integrated Camera                                                   | 2         | 3.77%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 3.77%   |
| Logitech HD Pro Webcam C920                                                | 2         | 3.77%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 3.77%   |
| Chicony Integrated Camera                                                  | 2         | 3.77%   |
| Chicony HD Webcam                                                          | 2         | 3.77%   |
| Apple FaceTime HD Camera                                                   | 2         | 3.77%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 3.77%   |
| Unknown ATIV VGA CAMERA                                                    | 1         | 1.89%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.89%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.89%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.89%   |
| Sunplus HD WebCam                                                          | 1         | 1.89%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.89%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 1.89%   |
| Realtek Integrated Webcam                                                  | 1         | 1.89%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 1.89%   |
| Polycom Poly Studio P5 webcam                                              | 1         | 1.89%   |
| Microdia Camera                                                            | 1         | 1.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.89%   |
| IMC Networks Integrated RGB Camera                                         | 1         | 1.89%   |
| DJJHFA1BIF5595 HP HD Camera                                                | 1         | 1.89%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.89%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 1.89%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.89%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.89%   |
| Chicony HP Wide Vision FHD Camera                                          | 1         | 1.89%   |
| Chicony HP Truevision HD camera                                            | 1         | 1.89%   |
| Chicony HP Integrated Webcam                                               | 1         | 1.89%   |
| Chicony HP HD Camera                                                       | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.89%   |
| Apple iSight in LED Cinema Display                                         | 1         | 1.89%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 1.89%   |
| Apple Built-in iSight                                                      | 1         | 1.89%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 1.89%   |
| Acer Integrated Camera                                                     | 1         | 1.89%   |
| Acer EasyCamera                                                            | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 36.36%  |
| Shenzhen Goodix Technology | 4         | 36.36%  |
| Validity Sensors           | 2         | 18.18%  |
| Elan Microelectronics      | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 2         | 18.18%  |
| Unknown                                           | 2         | 18.18%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 9.09%   |
| Shenzhen Goodix FingerPrint                       | 1         | 9.09%   |
| Elan ELAN:Fingerprint                             | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 58        | 69.88%  |
| 1     | 17        | 20.48%  |
| 2     | 5         | 6.02%   |
| 6     | 1         | 1.2%    |
| 4     | 1         | 1.2%    |
| 3     | 1         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 28.57%  |
| Graphics card            | 6         | 17.14%  |
| Net/wireless             | 5         | 14.29%  |
| Sound                    | 3         | 8.57%   |
| Unassigned class         | 2         | 5.71%   |
| Communication controller | 2         | 5.71%   |
| Chipcard                 | 2         | 5.71%   |
| Camera                   | 2         | 5.71%   |
| Net/ethernet             | 1         | 2.86%   |
| Multimedia controller    | 1         | 2.86%   |
| Bluetooth                | 1         | 2.86%   |

