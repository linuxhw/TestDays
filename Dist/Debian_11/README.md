Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

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

Total: 9960

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | G50-45 80E3                 | Notebook    | [801eeb31ef](https://linux-hardware.org/?probe=801eeb31ef) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7c01de63e1](https://linux-hardware.org/?probe=7c01de63e1) | May 08, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b245c99221](https://linux-hardware.org/?probe=b245c99221) | May 07, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ab33f7c9fc](https://linux-hardware.org/?probe=ab33f7c9fc) | May 06, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [b1caabc9b5](https://linux-hardware.org/?probe=b1caabc9b5) | May 05, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [264e965e8b](https://linux-hardware.org/?probe=264e965e8b) | May 04, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8f6497f948](https://linux-hardware.org/?probe=8f6497f948) | May 04, 2024 |
| Acer          | Aspire E1-531               | Notebook    | [27d57e495a](https://linux-hardware.org/?probe=27d57e495a) | May 04, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [f4dbf33638](https://linux-hardware.org/?probe=f4dbf33638) | May 02, 2024 |
| Dell          | Precision 5510              | Notebook    | [a010faffda](https://linux-hardware.org/?probe=a010faffda) | May 01, 2024 |
| Acer          | Aspire M5910                | Desktop     | [61b5809dc9](https://linux-hardware.org/?probe=61b5809dc9) | May 01, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90d5348bf5](https://linux-hardware.org/?probe=90d5348bf5) | Apr 28, 2024 |
| Acer          | Aspire E1-532               | Notebook    | [b50154d060](https://linux-hardware.org/?probe=b50154d060) | Apr 28, 2024 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [d486386bde](https://linux-hardware.org/?probe=d486386bde) | Apr 26, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [a5fcd90239](https://linux-hardware.org/?probe=a5fcd90239) | Apr 26, 2024 |
| Dell          | Precision M6800             | Notebook    | [1d41e8bb92](https://linux-hardware.org/?probe=1d41e8bb92) | Apr 25, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a61a96f7dd](https://linux-hardware.org/?probe=a61a96f7dd) | Apr 24, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [e61e4963d5](https://linux-hardware.org/?probe=e61e4963d5) | Apr 23, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [50751e1c9e](https://linux-hardware.org/?probe=50751e1c9e) | Apr 22, 2024 |
| Acer          | Aspire S3                   | Notebook    | [e43ba2d3ae](https://linux-hardware.org/?probe=e43ba2d3ae) | Apr 21, 2024 |
| Colorful T... | C.A68M-E V15                | Desktop     | [b0b7690daa](https://linux-hardware.org/?probe=b0b7690daa) | Apr 20, 2024 |
| Dell          | Precision M6800             | Notebook    | [c44a2aee51](https://linux-hardware.org/?probe=c44a2aee51) | Apr 20, 2024 |
| Unknown       | i855-W83627HF               | Desktop     | [e1c3562c4a](https://linux-hardware.org/?probe=e1c3562c4a) | Apr 18, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [01121cc898](https://linux-hardware.org/?probe=01121cc898) | Apr 18, 2024 |
| Gigabyte      | X570 UD                     | Desktop     | [5240449916](https://linux-hardware.org/?probe=5240449916) | Apr 18, 2024 |
| ASRock        | B550 Pro4                   | Desktop     | [f906fa4f7c](https://linux-hardware.org/?probe=f906fa4f7c) | Apr 18, 2024 |
| HP            | 805B                        | Desktop     | [d5bf7c2652](https://linux-hardware.org/?probe=d5bf7c2652) | Apr 18, 2024 |
| HP            | 245 G6                      | Notebook    | [17b7e55361](https://linux-hardware.org/?probe=17b7e55361) | Apr 17, 2024 |
| HP            | 245 G6                      | Notebook    | [7c3534813c](https://linux-hardware.org/?probe=7c3534813c) | Apr 17, 2024 |
| Supermicro    | X11DPi-NT                   | Server      | [5a3102ebe7](https://linux-hardware.org/?probe=5a3102ebe7) | Apr 17, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [0d46687bb7](https://linux-hardware.org/?probe=0d46687bb7) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [ba12ac8498](https://linux-hardware.org/?probe=ba12ac8498) | Apr 17, 2024 |
| AMI           | Cherry Trail CR             | Desktop     | [e60bc95699](https://linux-hardware.org/?probe=e60bc95699) | Apr 16, 2024 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [7ccf67d720](https://linux-hardware.org/?probe=7ccf67d720) | Apr 16, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [7cad8d2493](https://linux-hardware.org/?probe=7cad8d2493) | Apr 16, 2024 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [1ede6792e9](https://linux-hardware.org/?probe=1ede6792e9) | Apr 16, 2024 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [d6865e9438](https://linux-hardware.org/?probe=d6865e9438) | Apr 14, 2024 |
| Dell          | 0FRVY0 A00                  | Server      | [097c771b65](https://linux-hardware.org/?probe=097c771b65) | Apr 13, 2024 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [84f25faab3](https://linux-hardware.org/?probe=84f25faab3) | Apr 12, 2024 |
| ASRock        | Z690 PG Riptide             | Desktop     | [b5891958b5](https://linux-hardware.org/?probe=b5891958b5) | Apr 12, 2024 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [716fbdb5b2](https://linux-hardware.org/?probe=716fbdb5b2) | Apr 12, 2024 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [57b8f56426](https://linux-hardware.org/?probe=57b8f56426) | Apr 12, 2024 |
| Olimex        | A20-OLinuXino-LIME2-eMMC    | Soc         | [37be09f11b](https://linux-hardware.org/?probe=37be09f11b) | Apr 11, 2024 |
| HP            | 1998                        | Desktop     | [c0b0ec87ec](https://linux-hardware.org/?probe=c0b0ec87ec) | Apr 10, 2024 |
| HP            | Presario V6000 (GH918EA#... | Notebook    | [19c9124453](https://linux-hardware.org/?probe=19c9124453) | Apr 10, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [c3ee8b2d3d](https://linux-hardware.org/?probe=c3ee8b2d3d) | Apr 09, 2024 |
| Lenovo        | 32E6 NOK                    | Desktop     | [b560c0d5fe](https://linux-hardware.org/?probe=b560c0d5fe) | Apr 09, 2024 |
| Lenovo        | 3740 NOK                    | Desktop     | [355c32d663](https://linux-hardware.org/?probe=355c32d663) | Apr 09, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a50be3e60f](https://linux-hardware.org/?probe=a50be3e60f) | Apr 09, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [fb71c7fef7](https://linux-hardware.org/?probe=fb71c7fef7) | Apr 08, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [4661f5b412](https://linux-hardware.org/?probe=4661f5b412) | Apr 08, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a0b38f568d](https://linux-hardware.org/?probe=a0b38f568d) | Apr 08, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [708da72614](https://linux-hardware.org/?probe=708da72614) | Apr 07, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [e927b8e190](https://linux-hardware.org/?probe=e927b8e190) | Apr 06, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [304df5369f](https://linux-hardware.org/?probe=304df5369f) | Apr 06, 2024 |
| Acer          | Aspire 3690                 | Notebook    | [a3091a1ceb](https://linux-hardware.org/?probe=a3091a1ceb) | Apr 06, 2024 |
| MSI           | MS-B0A21                    | Desktop     | [e74fc30957](https://linux-hardware.org/?probe=e74fc30957) | Apr 05, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [e759ee33bf](https://linux-hardware.org/?probe=e759ee33bf) | Apr 04, 2024 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [0c26980268](https://linux-hardware.org/?probe=0c26980268) | Apr 03, 2024 |
| Juana Mans... | SF20GM7                     | Notebook    | [8571d52a38](https://linux-hardware.org/?probe=8571d52a38) | Apr 02, 2024 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [b45101bd55](https://linux-hardware.org/?probe=b45101bd55) | Apr 02, 2024 |
| Rockchip      | Orange Pi 5                 | Soc         | [0bc6342638](https://linux-hardware.org/?probe=0bc6342638) | Apr 02, 2024 |
| ASUSTek       | N55SF                       | Notebook    | [69918bf880](https://linux-hardware.org/?probe=69918bf880) | Apr 01, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8875ed3afe](https://linux-hardware.org/?probe=8875ed3afe) | Apr 01, 2024 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [38d1d0b6b6](https://linux-hardware.org/?probe=38d1d0b6b6) | Mar 31, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [8b3c41683d](https://linux-hardware.org/?probe=8b3c41683d) | Mar 30, 2024 |
| Gigabyte      | X570 UD                     | Desktop     | [539238d399](https://linux-hardware.org/?probe=539238d399) | Mar 29, 2024 |
| ASRock        | B550 Pro4                   | Desktop     | [9144eb7fe4](https://linux-hardware.org/?probe=9144eb7fe4) | Mar 29, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d84d712a77](https://linux-hardware.org/?probe=d84d712a77) | Mar 29, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [7542f194a2](https://linux-hardware.org/?probe=7542f194a2) | Mar 28, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [91c6a3e118](https://linux-hardware.org/?probe=91c6a3e118) | Mar 28, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [34d7c41e80](https://linux-hardware.org/?probe=34d7c41e80) | Mar 28, 2024 |
| ASUSTek       | F52Q                        | Notebook    | [edb335c489](https://linux-hardware.org/?probe=edb335c489) | Mar 27, 2024 |
| Digma         | EVE 15 C419 ES5065EW        | Notebook    | [83810dcd33](https://linux-hardware.org/?probe=83810dcd33) | Mar 26, 2024 |
| HP            | Presario V2000 (EH459UA#... | Notebook    | [af3a09ea38](https://linux-hardware.org/?probe=af3a09ea38) | Mar 26, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [6940ab6143](https://linux-hardware.org/?probe=6940ab6143) | Mar 24, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [05267117e8](https://linux-hardware.org/?probe=05267117e8) | Mar 23, 2024 |
| Primux Tec... | Primux ioxbook 1402FX       | Notebook    | [53e6d67001](https://linux-hardware.org/?probe=53e6d67001) | Mar 23, 2024 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [4558c9a4f4](https://linux-hardware.org/?probe=4558c9a4f4) | Mar 22, 2024 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [870960dbb0](https://linux-hardware.org/?probe=870960dbb0) | Mar 21, 2024 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| MSI           | Z97 GAMING 3                | Desktop     | [ed6f176128](https://linux-hardware.org/?probe=ed6f176128) | Mar 20, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [73f72d473b](https://linux-hardware.org/?probe=73f72d473b) | Mar 19, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b526dd935f](https://linux-hardware.org/?probe=b526dd935f) | Mar 19, 2024 |
| JGINYUE       | X99-D8 Server V1.0          | Desktop     | [aad6effeb0](https://linux-hardware.org/?probe=aad6effeb0) | Mar 18, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [fecb6cf968](https://linux-hardware.org/?probe=fecb6cf968) | Mar 18, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [e467a62b44](https://linux-hardware.org/?probe=e467a62b44) | Mar 18, 2024 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [0018e3e74d](https://linux-hardware.org/?probe=0018e3e74d) | Mar 16, 2024 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [08ca6f8423](https://linux-hardware.org/?probe=08ca6f8423) | Mar 14, 2024 |
| Dell          | Latitude 5401               | Notebook    | [651b3a2f09](https://linux-hardware.org/?probe=651b3a2f09) | Mar 14, 2024 |
| Toshiba       | All In One PC MP            | All in one  | [540c821d0f](https://linux-hardware.org/?probe=540c821d0f) | Mar 14, 2024 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [6d006ade6c](https://linux-hardware.org/?probe=6d006ade6c) | Mar 13, 2024 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [f7ddcc5c64](https://linux-hardware.org/?probe=f7ddcc5c64) | Mar 13, 2024 |
| Intel         | X58 V1608                   | Desktop     | [48e5f0f5a6](https://linux-hardware.org/?probe=48e5f0f5a6) | Mar 13, 2024 |
| Intel         | X58 V1608                   | Desktop     | [84ccc96b6b](https://linux-hardware.org/?probe=84ccc96b6b) | Mar 13, 2024 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [2a14a96457](https://linux-hardware.org/?probe=2a14a96457) | Mar 12, 2024 |
| Dell          | System XPS L702X            | Notebook    | [09313dcc56](https://linux-hardware.org/?probe=09313dcc56) | Mar 11, 2024 |
| Lenovo        | ThinkPad X230 2325AEG       | Notebook    | [8e4dbd3b9a](https://linux-hardware.org/?probe=8e4dbd3b9a) | Mar 10, 2024 |
| Supermicro    | X9DR3-F                     | Desktop     | [f4f1646c44](https://linux-hardware.org/?probe=f4f1646c44) | Mar 10, 2024 |
| HPE           | ProLiant DL20 Gen10 Plus    | Server      | [afb2f8105a](https://linux-hardware.org/?probe=afb2f8105a) | Mar 09, 2024 |
| HP            | Compaq Presario CQ50        | Notebook    | [a690fc2f4c](https://linux-hardware.org/?probe=a690fc2f4c) | Mar 06, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [cad73d3451](https://linux-hardware.org/?probe=cad73d3451) | Mar 06, 2024 |
| HP            | ENVY x360 Convertible       | Convertible | [d6aa64ff6c](https://linux-hardware.org/?probe=d6aa64ff6c) | Mar 06, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [585ba3971c](https://linux-hardware.org/?probe=585ba3971c) | Mar 05, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [3fecbdffcd](https://linux-hardware.org/?probe=3fecbdffcd) | Mar 05, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [35d70301d6](https://linux-hardware.org/?probe=35d70301d6) | Mar 04, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [dede36b712](https://linux-hardware.org/?probe=dede36b712) | Mar 04, 2024 |
| Lenovo        | ThinkPad A275 20KDS01S00    | Notebook    | [21f2a28872](https://linux-hardware.org/?probe=21f2a28872) | Mar 04, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [e69e7cf8f3](https://linux-hardware.org/?probe=e69e7cf8f3) | Mar 02, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [f526190f31](https://linux-hardware.org/?probe=f526190f31) | Mar 01, 2024 |
| Pegatron      | IPM41-D3                    | Desktop     | [5249318369](https://linux-hardware.org/?probe=5249318369) | Feb 29, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [66a88413c4](https://linux-hardware.org/?probe=66a88413c4) | Feb 28, 2024 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [57284c6e0e](https://linux-hardware.org/?probe=57284c6e0e) | Feb 28, 2024 |
| VANT          | MOOVE2-14                   | Notebook    | [9d5df13f40](https://linux-hardware.org/?probe=9d5df13f40) | Feb 27, 2024 |
| HP            | ProLiant DL165 G7           | Server      | [8850a77792](https://linux-hardware.org/?probe=8850a77792) | Feb 27, 2024 |
| Packard Be... | H17HV                       | Notebook    | [aa7bdcf198](https://linux-hardware.org/?probe=aa7bdcf198) | Feb 27, 2024 |
| ASUSTek       | M2N-E                       | Desktop     | [b3041e34a7](https://linux-hardware.org/?probe=b3041e34a7) | Feb 27, 2024 |
| HP            | ProBook 4540s               | Notebook    | [da8c81f864](https://linux-hardware.org/?probe=da8c81f864) | Feb 27, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [ad9632b089](https://linux-hardware.org/?probe=ad9632b089) | Feb 27, 2024 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [d44ed1a56f](https://linux-hardware.org/?probe=d44ed1a56f) | Feb 26, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [16759c3ced](https://linux-hardware.org/?probe=16759c3ced) | Feb 26, 2024 |
| HP            | Pavilion dv7                | Notebook    | [4712b3d187](https://linux-hardware.org/?probe=4712b3d187) | Feb 25, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [702dee066a](https://linux-hardware.org/?probe=702dee066a) | Feb 25, 2024 |
| Dell          | Inspiron 15 3511            | Notebook    | [cf8780be93](https://linux-hardware.org/?probe=cf8780be93) | Feb 24, 2024 |
| HP            | Compaq Presario CQ50        | Notebook    | [dc0f4d581f](https://linux-hardware.org/?probe=dc0f4d581f) | Feb 23, 2024 |
| congatec      | conga-MA7 B.4               | Mini pc     | [3ebbc89b09](https://linux-hardware.org/?probe=3ebbc89b09) | Feb 23, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [033fe9a8a6](https://linux-hardware.org/?probe=033fe9a8a6) | Feb 22, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [ed5e87fbaf](https://linux-hardware.org/?probe=ed5e87fbaf) | Feb 21, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [2d163839aa](https://linux-hardware.org/?probe=2d163839aa) | Feb 21, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [ec826c4feb](https://linux-hardware.org/?probe=ec826c4feb) | Feb 20, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [847d92dde1](https://linux-hardware.org/?probe=847d92dde1) | Feb 20, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ed69d93c9c](https://linux-hardware.org/?probe=ed69d93c9c) | Feb 19, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [b6fb308e13](https://linux-hardware.org/?probe=b6fb308e13) | Feb 19, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [d166d054d9](https://linux-hardware.org/?probe=d166d054d9) | Feb 18, 2024 |
| HP            | ProLiant DL380p Gen8        | Server      | [9e2f7a350a](https://linux-hardware.org/?probe=9e2f7a350a) | Feb 17, 2024 |
| Toshiba       | Satellite C670D-121         | Notebook    | [e72d5daf72](https://linux-hardware.org/?probe=e72d5daf72) | Feb 17, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0fe8b08e8c](https://linux-hardware.org/?probe=0fe8b08e8c) | Feb 16, 2024 |
| ASUSTek       | P12R-M Series 60SB0AU0-S... | Server      | [f61de673d0](https://linux-hardware.org/?probe=f61de673d0) | Feb 16, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c795e9fcb9](https://linux-hardware.org/?probe=c795e9fcb9) | Feb 16, 2024 |
| Toshiba       | Satellite C670D-121         | Notebook    | [31876b1946](https://linux-hardware.org/?probe=31876b1946) | Feb 15, 2024 |
| Dell          | 05842Y A00                  | Desktop     | [50fc41ef5c](https://linux-hardware.org/?probe=50fc41ef5c) | Feb 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [64bdaa6db8](https://linux-hardware.org/?probe=64bdaa6db8) | Feb 15, 2024 |
| Lenovo        | ThinkCentre M91p 4518A4M    | Desktop     | [56739f7004](https://linux-hardware.org/?probe=56739f7004) | Feb 15, 2024 |
| HP            | ProLiant DL380p Gen8        | Server      | [b1d8a070e5](https://linux-hardware.org/?probe=b1d8a070e5) | Feb 15, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [b3ffbe3673](https://linux-hardware.org/?probe=b3ffbe3673) | Feb 14, 2024 |
| Rockchip      | RK3318 BOX                  | Soc         | [9b806c989c](https://linux-hardware.org/?probe=9b806c989c) | Feb 13, 2024 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [b734675c3c](https://linux-hardware.org/?probe=b734675c3c) | Feb 13, 2024 |
| ASUSTek       | X751LB                      | Notebook    | [e2b955fef7](https://linux-hardware.org/?probe=e2b955fef7) | Feb 12, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [0c27b7881f](https://linux-hardware.org/?probe=0c27b7881f) | Feb 12, 2024 |
| YANYU         | EPIC-C19                    | Desktop     | [9a93a8fd98](https://linux-hardware.org/?probe=9a93a8fd98) | Feb 12, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2ef5e51010](https://linux-hardware.org/?probe=2ef5e51010) | Feb 12, 2024 |
| Dell          | Latitude E6440              | Notebook    | [af1136c398](https://linux-hardware.org/?probe=af1136c398) | Feb 11, 2024 |
| Dell          | Latitude E6440              | Notebook    | [3d82406435](https://linux-hardware.org/?probe=3d82406435) | Feb 11, 2024 |
| Positivo B... | VJFE59F11X-B0821H           | Notebook    | [749f5aacff](https://linux-hardware.org/?probe=749f5aacff) | Feb 10, 2024 |
| Toshiba       | Satellite L755              | Notebook    | [51db691206](https://linux-hardware.org/?probe=51db691206) | Feb 09, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [225644e904](https://linux-hardware.org/?probe=225644e904) | Feb 09, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [ba8e24ef8f](https://linux-hardware.org/?probe=ba8e24ef8f) | Feb 08, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [1c2ec48565](https://linux-hardware.org/?probe=1c2ec48565) | Feb 08, 2024 |
| Intel         | NUC7JYB J67969-401          | Mini pc     | [54c69c7b5e](https://linux-hardware.org/?probe=54c69c7b5e) | Feb 08, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [9ce8b249bf](https://linux-hardware.org/?probe=9ce8b249bf) | Feb 07, 2024 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [10a9284561](https://linux-hardware.org/?probe=10a9284561) | Feb 07, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [08432d000e](https://linux-hardware.org/?probe=08432d000e) | Feb 07, 2024 |
| ASRock        | G31M-GS                     | Desktop     | [50925f48af](https://linux-hardware.org/?probe=50925f48af) | Feb 06, 2024 |
| HP            | Compaq 15                   | Notebook    | [beb2ca6a98](https://linux-hardware.org/?probe=beb2ca6a98) | Feb 06, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [d8d66e42bc](https://linux-hardware.org/?probe=d8d66e42bc) | Feb 05, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [8c4de7da42](https://linux-hardware.org/?probe=8c4de7da42) | Feb 05, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [db79d01310](https://linux-hardware.org/?probe=db79d01310) | Feb 05, 2024 |
| Acer          | Aspire 7741                 | Notebook    | [65e4664bc8](https://linux-hardware.org/?probe=65e4664bc8) | Feb 03, 2024 |
| HP            | Pavilion g4                 | Notebook    | [c918dcf201](https://linux-hardware.org/?probe=c918dcf201) | Feb 03, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [f7d0fcd205](https://linux-hardware.org/?probe=f7d0fcd205) | Feb 02, 2024 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [88794835fb](https://linux-hardware.org/?probe=88794835fb) | Feb 02, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a3932a77fb](https://linux-hardware.org/?probe=a3932a77fb) | Feb 01, 2024 |
| HP            | 15                          | Notebook    | [5abc868cce](https://linux-hardware.org/?probe=5abc868cce) | Jan 31, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [a2536bd0a5](https://linux-hardware.org/?probe=a2536bd0a5) | Jan 31, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1127b13645](https://linux-hardware.org/?probe=1127b13645) | Jan 30, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [385d8d4782](https://linux-hardware.org/?probe=385d8d4782) | Jan 29, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [66d4abe24d](https://linux-hardware.org/?probe=66d4abe24d) | Jan 29, 2024 |
| HP            | 3397                        | Desktop     | [fcbc5b3ac6](https://linux-hardware.org/?probe=fcbc5b3ac6) | Jan 29, 2024 |
| ASUSTek       | N550JK                      | Notebook    | [097f96652f](https://linux-hardware.org/?probe=097f96652f) | Jan 29, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [dbbc24a0ed](https://linux-hardware.org/?probe=dbbc24a0ed) | Jan 28, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [5c34879ea0](https://linux-hardware.org/?probe=5c34879ea0) | Jan 28, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [4a48eb8f58](https://linux-hardware.org/?probe=4a48eb8f58) | Jan 28, 2024 |
| HP            | Compaq nc6320 (EN371UA#A... | Notebook    | [24bcfc0005](https://linux-hardware.org/?probe=24bcfc0005) | Jan 28, 2024 |
| Supermicro    | X13DEI                      | Server      | [044e82e684](https://linux-hardware.org/?probe=044e82e684) | Jan 27, 2024 |
| Dell          | 01W23F A05                  | Server      | [93f017d8b0](https://linux-hardware.org/?probe=93f017d8b0) | Jan 27, 2024 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [380fafe6a3](https://linux-hardware.org/?probe=380fafe6a3) | Jan 27, 2024 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [b0019abd70](https://linux-hardware.org/?probe=b0019abd70) | Jan 26, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [aa46ef22c8](https://linux-hardware.org/?probe=aa46ef22c8) | Jan 24, 2024 |
| MSI           | GL62M 7RDX                  | Notebook    | [bd42ee7dc8](https://linux-hardware.org/?probe=bd42ee7dc8) | Jan 24, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [f5a09bd7f0](https://linux-hardware.org/?probe=f5a09bd7f0) | Jan 23, 2024 |
| Intel         | S1200SP H57532-250          | Server      | [94a4904dc7](https://linux-hardware.org/?probe=94a4904dc7) | Jan 22, 2024 |
| Inventec      | D CLASS A02                 | Desktop     | [25d4886028](https://linux-hardware.org/?probe=25d4886028) | Jan 22, 2024 |
| Rockchip      | RK3288 Asus Tinker          | Soc         | [b21fbd5b1c](https://linux-hardware.org/?probe=b21fbd5b1c) | Jan 22, 2024 |
| ASRock        | H61M-HVS                    | Desktop     | [3cfc574d2d](https://linux-hardware.org/?probe=3cfc574d2d) | Jan 22, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [58f6bacae6](https://linux-hardware.org/?probe=58f6bacae6) | Jan 21, 2024 |
| MACHINIST     | X99 PR9                     | Desktop     | [2cac18e4ae](https://linux-hardware.org/?probe=2cac18e4ae) | Jan 21, 2024 |
| Dell          | Latitude D630               | Notebook    | [bf9ce8c208](https://linux-hardware.org/?probe=bf9ce8c208) | Jan 21, 2024 |
| Dell          | Latitude D630               | Notebook    | [b2a68014db](https://linux-hardware.org/?probe=b2a68014db) | Jan 21, 2024 |
| Lenovo        | ThinkPad T490 20N2000RRT    | Notebook    | [b48f14a503](https://linux-hardware.org/?probe=b48f14a503) | Jan 20, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [37613f1ec6](https://linux-hardware.org/?probe=37613f1ec6) | Jan 20, 2024 |
| IBM           | 94Y7718 SIT                 | Server      | [4c4fece75e](https://linux-hardware.org/?probe=4c4fece75e) | Jan 19, 2024 |
| IBM           | 69Y1006 SIT                 | Server      | [b9e00770bb](https://linux-hardware.org/?probe=b9e00770bb) | Jan 19, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [b09c608815](https://linux-hardware.org/?probe=b09c608815) | Jan 19, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [5b5d90211c](https://linux-hardware.org/?probe=5b5d90211c) | Jan 18, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [930cd5c4f3](https://linux-hardware.org/?probe=930cd5c4f3) | Jan 17, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3bb258a169](https://linux-hardware.org/?probe=3bb258a169) | Jan 15, 2024 |
| Multilaser    | MLGW08                      | Notebook    | [abfe537d6f](https://linux-hardware.org/?probe=abfe537d6f) | Jan 15, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [1d65e65b24](https://linux-hardware.org/?probe=1d65e65b24) | Jan 14, 2024 |
| Unknown       | Unknown                     | Soc         | [8eb428515e](https://linux-hardware.org/?probe=8eb428515e) | Jan 14, 2024 |
| ASRock        | C2750D4I                    | Desktop     | [c1426b3157](https://linux-hardware.org/?probe=c1426b3157) | Jan 14, 2024 |
| HP            | Compaq 6720s                | Notebook    | [4b6c283ab3](https://linux-hardware.org/?probe=4b6c283ab3) | Jan 13, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [02122a5ac3](https://linux-hardware.org/?probe=02122a5ac3) | Jan 13, 2024 |
| ASUSTek       | Z87-C                       | Desktop     | [acc914cabd](https://linux-hardware.org/?probe=acc914cabd) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [a485e19625](https://linux-hardware.org/?probe=a485e19625) | Jan 12, 2024 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [854720405d](https://linux-hardware.org/?probe=854720405d) | Jan 12, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7eabdfe5d0](https://linux-hardware.org/?probe=7eabdfe5d0) | Jan 12, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [d04339c0dc](https://linux-hardware.org/?probe=d04339c0dc) | Jan 12, 2024 |
| HP            | 348 G5                      | Notebook    | [a7c6a60aaf](https://linux-hardware.org/?probe=a7c6a60aaf) | Jan 12, 2024 |
| HP            | 530 Notebook PC(GH634AA#... | Notebook    | [a17c4145f4](https://linux-hardware.org/?probe=a17c4145f4) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [5479dc0213](https://linux-hardware.org/?probe=5479dc0213) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [48bddf33da](https://linux-hardware.org/?probe=48bddf33da) | Jan 11, 2024 |
| Unknown       | Unknown                     | Notebook    | [0f2d55f419](https://linux-hardware.org/?probe=0f2d55f419) | Jan 11, 2024 |
| Unknown       | Unknown                     | Notebook    | [f5d4b22b3c](https://linux-hardware.org/?probe=f5d4b22b3c) | Jan 11, 2024 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [e4bcfdfed2](https://linux-hardware.org/?probe=e4bcfdfed2) | Jan 10, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [8f4190a60f](https://linux-hardware.org/?probe=8f4190a60f) | Jan 10, 2024 |
| HP            | ENVY x360 Convertible       | Convertible | [5223d11808](https://linux-hardware.org/?probe=5223d11808) | Jan 10, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [90b63b0d8a](https://linux-hardware.org/?probe=90b63b0d8a) | Jan 10, 2024 |
| HP            | EliteBook 2530p             | Notebook    | [0de99e6532](https://linux-hardware.org/?probe=0de99e6532) | Jan 09, 2024 |
| HP            | ProBook 6545b               | Notebook    | [278d4aea3c](https://linux-hardware.org/?probe=278d4aea3c) | Jan 09, 2024 |
| TI            | AM335x PocketBeagle         | Soc         | [dc70357482](https://linux-hardware.org/?probe=dc70357482) | Jan 09, 2024 |
| Acer          | TMP455-M                    | Notebook    | [559512a222](https://linux-hardware.org/?probe=559512a222) | Jan 09, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [6f8302ddde](https://linux-hardware.org/?probe=6f8302ddde) | Jan 08, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ded26713a9](https://linux-hardware.org/?probe=ded26713a9) | Jan 08, 2024 |
| Dell          | Precision 5570              | Notebook    | [acc6213478](https://linux-hardware.org/?probe=acc6213478) | Jan 08, 2024 |
| HP            | 350 G2                      | Notebook    | [75e4063ce8](https://linux-hardware.org/?probe=75e4063ce8) | Jan 07, 2024 |
| Toshiba       | PORTEGE R500                | Notebook    | [315837012b](https://linux-hardware.org/?probe=315837012b) | Jan 07, 2024 |
| MSI           | X79A-GD65                   | Desktop     | [55c0071638](https://linux-hardware.org/?probe=55c0071638) | Jan 06, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [a44b8f65f6](https://linux-hardware.org/?probe=a44b8f65f6) | Jan 06, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [78696f8410](https://linux-hardware.org/?probe=78696f8410) | Jan 05, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [408830a147](https://linux-hardware.org/?probe=408830a147) | Jan 05, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [90e3c8644a](https://linux-hardware.org/?probe=90e3c8644a) | Jan 05, 2024 |
| Phoenix Co... | PSB514 A12                  | Desktop     | [424bbc0491](https://linux-hardware.org/?probe=424bbc0491) | Jan 03, 2024 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [63582c85bf](https://linux-hardware.org/?probe=63582c85bf) | Jan 03, 2024 |
| Unknown       | Unknown                     | Other       | [ceb8edb5ac](https://linux-hardware.org/?probe=ceb8edb5ac) | Jan 03, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [ee8caab1b7](https://linux-hardware.org/?probe=ee8caab1b7) | Jan 03, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2f74327d87](https://linux-hardware.org/?probe=2f74327d87) | Jan 01, 2024 |
| HP            | 1495                        | Desktop     | [48d0ae2bf5](https://linux-hardware.org/?probe=48d0ae2bf5) | Dec 30, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [80604ec459](https://linux-hardware.org/?probe=80604ec459) | Dec 30, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [529b92f758](https://linux-hardware.org/?probe=529b92f758) | Dec 28, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [4118aee355](https://linux-hardware.org/?probe=4118aee355) | Dec 28, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [f1144c99b2](https://linux-hardware.org/?probe=f1144c99b2) | Dec 27, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7b5e390f00](https://linux-hardware.org/?probe=7b5e390f00) | Dec 27, 2023 |
| Gigabyte      | P55-UD4P                    | Desktop     | [62b547894e](https://linux-hardware.org/?probe=62b547894e) | Dec 25, 2023 |
| eMachines     | EMCP61M                     | Desktop     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfc1d4289e](https://linux-hardware.org/?probe=dfc1d4289e) | Dec 22, 2023 |
| Gigabyte      | MZ72-HB0-00 01020102        | Server      | [771f7edd98](https://linux-hardware.org/?probe=771f7edd98) | Dec 22, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [22b9c27eb8](https://linux-hardware.org/?probe=22b9c27eb8) | Dec 21, 2023 |
| HP            | 3396                        | Desktop     | [d0d084ecc8](https://linux-hardware.org/?probe=d0d084ecc8) | Dec 20, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [25a077d35e](https://linux-hardware.org/?probe=25a077d35e) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | Desktop     | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| Clevo         | W240BU                      | Notebook    | [a0d883bb3d](https://linux-hardware.org/?probe=a0d883bb3d) | Dec 20, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [85233c464d](https://linux-hardware.org/?probe=85233c464d) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [acebee7435](https://linux-hardware.org/?probe=acebee7435) | Dec 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9133031c56](https://linux-hardware.org/?probe=9133031c56) | Dec 18, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [058c14cd39](https://linux-hardware.org/?probe=058c14cd39) | Dec 17, 2023 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [e4c855bedc](https://linux-hardware.org/?probe=e4c855bedc) | Dec 16, 2023 |
| Dell          | 0M5WNK A02                  | Desktop     | [f47a8fcf1f](https://linux-hardware.org/?probe=f47a8fcf1f) | Dec 15, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [dfa5dc9cd9](https://linux-hardware.org/?probe=dfa5dc9cd9) | Dec 14, 2023 |
| Sony          | VPCEG18FG                   | Notebook    | [3cf20aa9ea](https://linux-hardware.org/?probe=3cf20aa9ea) | Dec 14, 2023 |
| HP            | ProBook 4540s               | Notebook    | [24875256cd](https://linux-hardware.org/?probe=24875256cd) | Dec 14, 2023 |
| Acer          | Aspire 1510 Rev.A           | Desktop     | [452be93d1b](https://linux-hardware.org/?probe=452be93d1b) | Dec 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [920939b6c0](https://linux-hardware.org/?probe=920939b6c0) | Dec 13, 2023 |
| Unknown       | AMedia X96 Max+             | Soc         | [4df1c17523](https://linux-hardware.org/?probe=4df1c17523) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [1ef755944c](https://linux-hardware.org/?probe=1ef755944c) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [e4fcf233c5](https://linux-hardware.org/?probe=e4fcf233c5) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ae61f1039f](https://linux-hardware.org/?probe=ae61f1039f) | Dec 09, 2023 |
| AZW           | MINI S                      | Desktop     | [2512b54e60](https://linux-hardware.org/?probe=2512b54e60) | Dec 09, 2023 |
| Hardkernel    | ODROID-M1                   | Soc         | [39d65538cb](https://linux-hardware.org/?probe=39d65538cb) | Dec 08, 2023 |
| Dell          | 0KP561                      | Desktop     | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [21b8166e02](https://linux-hardware.org/?probe=21b8166e02) | Dec 06, 2023 |
| Intel         | H61                         | Desktop     | [fbc4dc7436](https://linux-hardware.org/?probe=fbc4dc7436) | Dec 06, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [523404e018](https://linux-hardware.org/?probe=523404e018) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6d4537080b](https://linux-hardware.org/?probe=6d4537080b) | Dec 05, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [82dedf4be4](https://linux-hardware.org/?probe=82dedf4be4) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | Notebook    | [01485bc011](https://linux-hardware.org/?probe=01485bc011) | Dec 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2afc97f78a](https://linux-hardware.org/?probe=2afc97f78a) | Dec 03, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| Sony          | VPCEB46FX                   | Notebook    | [b331dc017f](https://linux-hardware.org/?probe=b331dc017f) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [c4f3b7fec9](https://linux-hardware.org/?probe=c4f3b7fec9) | Dec 01, 2023 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [b0c7a29604](https://linux-hardware.org/?probe=b0c7a29604) | Dec 01, 2023 |
| MSI           | A78M-E45                    | Desktop     | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | Desktop     | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b0642c446](https://linux-hardware.org/?probe=2b0642c446) | Nov 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [1b7f8a15dd](https://linux-hardware.org/?probe=1b7f8a15dd) | Nov 29, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | Desktop     | [af727ea890](https://linux-hardware.org/?probe=af727ea890) | Nov 29, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [7ff2232073](https://linux-hardware.org/?probe=7ff2232073) | Nov 29, 2023 |
| MSI           | X299 GAMING PRO CARBON      | Desktop     | [07d105a830](https://linux-hardware.org/?probe=07d105a830) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| Daten Tecn... | DCM3A-4                     | Notebook    | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [ea6ad73049](https://linux-hardware.org/?probe=ea6ad73049) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [54b3a350cc](https://linux-hardware.org/?probe=54b3a350cc) | Nov 27, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [a7890b3e79](https://linux-hardware.org/?probe=a7890b3e79) | Nov 27, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [b784691187](https://linux-hardware.org/?probe=b784691187) | Nov 27, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [1e36c88b83](https://linux-hardware.org/?probe=1e36c88b83) | Nov 27, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f0b4d1d85c](https://linux-hardware.org/?probe=f0b4d1d85c) | Nov 26, 2023 |
| MSI           | B85M-G43                    | Desktop     | [c8c114c2df](https://linux-hardware.org/?probe=c8c114c2df) | Nov 26, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [5bf94efca1](https://linux-hardware.org/?probe=5bf94efca1) | Nov 26, 2023 |
| AZW           | U59                         | Desktop     | [b03056a1ad](https://linux-hardware.org/?probe=b03056a1ad) | Nov 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6706fb6f0f](https://linux-hardware.org/?probe=6706fb6f0f) | Nov 23, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [eff446af17](https://linux-hardware.org/?probe=eff446af17) | Nov 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [26da233e2b](https://linux-hardware.org/?probe=26da233e2b) | Nov 21, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [729045e89d](https://linux-hardware.org/?probe=729045e89d) | Nov 21, 2023 |
| IBM           | 94Y7718 SIT                 | Server      | [80a223d120](https://linux-hardware.org/?probe=80a223d120) | Nov 21, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [09b6107952](https://linux-hardware.org/?probe=09b6107952) | Nov 20, 2023 |
| Dell          | 0D6H9T A02                  | Desktop     | [034fe5ff39](https://linux-hardware.org/?probe=034fe5ff39) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| HP            | 1905                        | Desktop     | [7718b065fd](https://linux-hardware.org/?probe=7718b065fd) | Nov 20, 2023 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [67cba6139f](https://linux-hardware.org/?probe=67cba6139f) | Nov 20, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3ec9fbcdea](https://linux-hardware.org/?probe=3ec9fbcdea) | Nov 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9d71a8e453](https://linux-hardware.org/?probe=9d71a8e453) | Nov 20, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [2ffe9e80d4](https://linux-hardware.org/?probe=2ffe9e80d4) | Nov 19, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fa116d20dc](https://linux-hardware.org/?probe=fa116d20dc) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a566513a93](https://linux-hardware.org/?probe=a566513a93) | Nov 19, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [9a96aff4c7](https://linux-hardware.org/?probe=9a96aff4c7) | Nov 18, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [e5673cd079](https://linux-hardware.org/?probe=e5673cd079) | Nov 18, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [1b1258a703](https://linux-hardware.org/?probe=1b1258a703) | Nov 17, 2023 |
| SIEMENS       | A5E49569366 RS-AF           | Desktop     | [07d3a028ec](https://linux-hardware.org/?probe=07d3a028ec) | Nov 17, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [204303d116](https://linux-hardware.org/?probe=204303d116) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [026b13382d](https://linux-hardware.org/?probe=026b13382d) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [893762777e](https://linux-hardware.org/?probe=893762777e) | Nov 17, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e7e00bb090](https://linux-hardware.org/?probe=e7e00bb090) | Nov 16, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [477b965e66](https://linux-hardware.org/?probe=477b965e66) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| Phoenix/Si... | M730SR                      | Notebook    | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [e90f4e1799](https://linux-hardware.org/?probe=e90f4e1799) | Nov 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [01ce54e1ed](https://linux-hardware.org/?probe=01ce54e1ed) | Nov 14, 2023 |
| Packard Be... | EasyNote TK81               | Notebook    | [a44fd2dc7a](https://linux-hardware.org/?probe=a44fd2dc7a) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [f9bfe70cef](https://linux-hardware.org/?probe=f9bfe70cef) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [af04867373](https://linux-hardware.org/?probe=af04867373) | Nov 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [57e4a13fab](https://linux-hardware.org/?probe=57e4a13fab) | Nov 13, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [2bc7d7c816](https://linux-hardware.org/?probe=2bc7d7c816) | Nov 13, 2023 |
| WanYou        | WanYouChunXiao              | Desktop     | [82c62804fc](https://linux-hardware.org/?probe=82c62804fc) | Nov 13, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8b8d073259](https://linux-hardware.org/?probe=8b8d073259) | Nov 13, 2023 |
| Intel         | NUC5i5RYB H40999-505        | Mini pc     | [26e08a35c7](https://linux-hardware.org/?probe=26e08a35c7) | Nov 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [4a9666ef8a](https://linux-hardware.org/?probe=4a9666ef8a) | Nov 12, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [29b6fb8a4f](https://linux-hardware.org/?probe=29b6fb8a4f) | Nov 11, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [a83ac39876](https://linux-hardware.org/?probe=a83ac39876) | Nov 10, 2023 |
| Acer          | EG43M                       | Desktop     | [53270970b2](https://linux-hardware.org/?probe=53270970b2) | Nov 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [afeda2ac5e](https://linux-hardware.org/?probe=afeda2ac5e) | Nov 08, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [25387a2c6f](https://linux-hardware.org/?probe=25387a2c6f) | Nov 08, 2023 |
| Lenovo        | ThinkPad X121e 30515YG      | Notebook    | [4008ec0eb0](https://linux-hardware.org/?probe=4008ec0eb0) | Nov 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Lenovo        | ThinkPad T470 20HES3JR02    | Notebook    | [4cdded6623](https://linux-hardware.org/?probe=4cdded6623) | Nov 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5b992d974a](https://linux-hardware.org/?probe=5b992d974a) | Nov 06, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| Acer          | AO532h                      | Notebook    | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [212105774f](https://linux-hardware.org/?probe=212105774f) | Nov 02, 2023 |
| ASRock        | Z77 WS                      | Desktop     | [73b9354a1a](https://linux-hardware.org/?probe=73b9354a1a) | Nov 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8c9de8be4f](https://linux-hardware.org/?probe=8c9de8be4f) | Nov 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c35f9a55aa](https://linux-hardware.org/?probe=c35f9a55aa) | Nov 02, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | Desktop     | [b684f82e3c](https://linux-hardware.org/?probe=b684f82e3c) | Nov 01, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b9c3643e62](https://linux-hardware.org/?probe=b9c3643e62) | Nov 01, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b9d1b13098](https://linux-hardware.org/?probe=b9d1b13098) | Oct 31, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [2d90a96dfb](https://linux-hardware.org/?probe=2d90a96dfb) | Oct 31, 2023 |
| Unknown       | Unknown                     | Soc         | [c1888a18d4](https://linux-hardware.org/?probe=c1888a18d4) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [8b1fe7cf44](https://linux-hardware.org/?probe=8b1fe7cf44) | Oct 30, 2023 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [af90b19d11](https://linux-hardware.org/?probe=af90b19d11) | Oct 30, 2023 |
| Supermicro    | X8DTH                       | Server      | [25d685c01e](https://linux-hardware.org/?probe=25d685c01e) | Oct 30, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [081a87b55c](https://linux-hardware.org/?probe=081a87b55c) | Oct 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [57441db309](https://linux-hardware.org/?probe=57441db309) | Oct 29, 2023 |
| Shenzhen M... | TH80                        | Desktop     | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [afa984b0d3](https://linux-hardware.org/?probe=afa984b0d3) | Oct 28, 2023 |
| Acer          | Aspire A115-31              | Notebook    | [137821ca25](https://linux-hardware.org/?probe=137821ca25) | Oct 28, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B4I... | Notebook    | [afce107e0d](https://linux-hardware.org/?probe=afce107e0d) | Oct 26, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [fa28d68e1b](https://linux-hardware.org/?probe=fa28d68e1b) | Oct 26, 2023 |
| Matsushita... | CF-30CTWAZBM                | Notebook    | [4211783dac](https://linux-hardware.org/?probe=4211783dac) | Oct 25, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [f1ee66826b](https://linux-hardware.org/?probe=f1ee66826b) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [0f58ce148b](https://linux-hardware.org/?probe=0f58ce148b) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [36f77e9a81](https://linux-hardware.org/?probe=36f77e9a81) | Oct 24, 2023 |
| MSI           | GT62VR 6RD                  | Notebook    | [0d10c5251c](https://linux-hardware.org/?probe=0d10c5251c) | Oct 23, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [047f359430](https://linux-hardware.org/?probe=047f359430) | Oct 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2de56b09e8](https://linux-hardware.org/?probe=2de56b09e8) | Oct 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| Unknown       | Unknown                     | Soc         | [0a48bce51e](https://linux-hardware.org/?probe=0a48bce51e) | Oct 21, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [dc33bae348](https://linux-hardware.org/?probe=dc33bae348) | Oct 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [deaf93db4b](https://linux-hardware.org/?probe=deaf93db4b) | Oct 21, 2023 |
| OrangePi      | 4 LTS                       | Soc         | [46dd11286b](https://linux-hardware.org/?probe=46dd11286b) | Oct 21, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [0d55c2a6af](https://linux-hardware.org/?probe=0d55c2a6af) | Oct 20, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [1ec00092e6](https://linux-hardware.org/?probe=1ec00092e6) | Oct 19, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [745f21d8bc](https://linux-hardware.org/?probe=745f21d8bc) | Oct 19, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [c1f0e34df5](https://linux-hardware.org/?probe=c1f0e34df5) | Oct 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [67365133d9](https://linux-hardware.org/?probe=67365133d9) | Oct 17, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [ea7e37eb5d](https://linux-hardware.org/?probe=ea7e37eb5d) | Oct 17, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d48d54a951](https://linux-hardware.org/?probe=d48d54a951) | Oct 16, 2023 |
| Rockchip      | RK3288 Asus Tinker Board... | Soc         | [b51d195a9b](https://linux-hardware.org/?probe=b51d195a9b) | Oct 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e8dd286f6d](https://linux-hardware.org/?probe=e8dd286f6d) | Oct 16, 2023 |
| libre-comp... | aml-s905x-cc                | Soc         | [6a64c8bbf2](https://linux-hardware.org/?probe=6a64c8bbf2) | Oct 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [34f4a7b2a5](https://linux-hardware.org/?probe=34f4a7b2a5) | Oct 15, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7d2501217c](https://linux-hardware.org/?probe=7d2501217c) | Oct 15, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2686ddd07b](https://linux-hardware.org/?probe=2686ddd07b) | Oct 15, 2023 |
| Quantum en... | HackBoard 2                 | Desktop     | [27781c0b8a](https://linux-hardware.org/?probe=27781c0b8a) | Oct 14, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [5f59c8dd03](https://linux-hardware.org/?probe=5f59c8dd03) | Oct 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00F0GE    | Notebook    | [61c5a7e37a](https://linux-hardware.org/?probe=61c5a7e37a) | Oct 13, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [37a3b14ed3](https://linux-hardware.org/?probe=37a3b14ed3) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| Dell          | Latitude E6520              | Notebook    | [30a511af92](https://linux-hardware.org/?probe=30a511af92) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [679e27a869](https://linux-hardware.org/?probe=679e27a869) | Oct 12, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [1489eccd85](https://linux-hardware.org/?probe=1489eccd85) | Oct 12, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [925371c475](https://linux-hardware.org/?probe=925371c475) | Oct 11, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [b16ee3559a](https://linux-hardware.org/?probe=b16ee3559a) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0cbd266486](https://linux-hardware.org/?probe=0cbd266486) | Oct 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [941644a3ed](https://linux-hardware.org/?probe=941644a3ed) | Oct 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [427ca84f59](https://linux-hardware.org/?probe=427ca84f59) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f53b6f5e53](https://linux-hardware.org/?probe=f53b6f5e53) | Oct 11, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [8606120535](https://linux-hardware.org/?probe=8606120535) | Oct 10, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [0198bbbc8c](https://linux-hardware.org/?probe=0198bbbc8c) | Oct 10, 2023 |
| IBM           | 94Y7614                     | Server      | [e9f6bf0852](https://linux-hardware.org/?probe=e9f6bf0852) | Oct 10, 2023 |
| Supermicro    | X10SLM-F                    | Server      | [a47217adb4](https://linux-hardware.org/?probe=a47217adb4) | Oct 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [601fd070ec](https://linux-hardware.org/?probe=601fd070ec) | Oct 10, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [855d2e95a7](https://linux-hardware.org/?probe=855d2e95a7) | Oct 09, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [74a043fcf5](https://linux-hardware.org/?probe=74a043fcf5) | Oct 09, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [e763607fe3](https://linux-hardware.org/?probe=e763607fe3) | Oct 09, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7912f11c78](https://linux-hardware.org/?probe=7912f11c78) | Oct 08, 2023 |
| Lenovo        | Legion Y920-17IKB Laptop... | Notebook    | [881454bd02](https://linux-hardware.org/?probe=881454bd02) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | Notebook    | [cae6954f11](https://linux-hardware.org/?probe=cae6954f11) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | Notebook    | [ca68af85fb](https://linux-hardware.org/?probe=ca68af85fb) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b54dca932a](https://linux-hardware.org/?probe=b54dca932a) | Oct 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [71bc4e1d3f](https://linux-hardware.org/?probe=71bc4e1d3f) | Oct 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [fea9ed801a](https://linux-hardware.org/?probe=fea9ed801a) | Oct 07, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [63ad812f2f](https://linux-hardware.org/?probe=63ad812f2f) | Oct 06, 2023 |
| Exo           | Smart Serie L               | Notebook    | [812041d985](https://linux-hardware.org/?probe=812041d985) | Oct 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bf88efbfff](https://linux-hardware.org/?probe=bf88efbfff) | Oct 05, 2023 |
| Philco Inf... | EC10IS2                     | Notebook    | [f85315b46a](https://linux-hardware.org/?probe=f85315b46a) | Oct 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [a6849f7516](https://linux-hardware.org/?probe=a6849f7516) | Oct 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7ff4fd8349](https://linux-hardware.org/?probe=7ff4fd8349) | Oct 02, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [3779ac7003](https://linux-hardware.org/?probe=3779ac7003) | Oct 01, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [6443df8957](https://linux-hardware.org/?probe=6443df8957) | Oct 01, 2023 |
| Packard Be... | EasyNote LM98               | Notebook    | [8fdf8eee6c](https://linux-hardware.org/?probe=8fdf8eee6c) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aae60ff071](https://linux-hardware.org/?probe=aae60ff071) | Oct 01, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| Dell          | Latitude 5410               | Notebook    | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4aa68077](https://linux-hardware.org/?probe=ba4aa68077) | Sep 30, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| Supermicro    | X11DDW-NT                   | Server      | [c7b049f922](https://linux-hardware.org/?probe=c7b049f922) | Sep 29, 2023 |
| Dell          | Latitude 5410               | Notebook    | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [f004fa8e32](https://linux-hardware.org/?probe=f004fa8e32) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [3646127006](https://linux-hardware.org/?probe=3646127006) | Sep 27, 2023 |
| Intel         | DP35DP AAD81073-206         | Desktop     | [426e9aff0f](https://linux-hardware.org/?probe=426e9aff0f) | Sep 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [acde6e2ba0](https://linux-hardware.org/?probe=acde6e2ba0) | Sep 26, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8a7db88ae5](https://linux-hardware.org/?probe=8a7db88ae5) | Sep 25, 2023 |
| MSI           | MS-7318                     | Desktop     | [0e03a1818a](https://linux-hardware.org/?probe=0e03a1818a) | Sep 24, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [971f03180e](https://linux-hardware.org/?probe=971f03180e) | Sep 24, 2023 |
| HP            | 250 G4                      | Notebook    | [c9dac1b4d5](https://linux-hardware.org/?probe=c9dac1b4d5) | Sep 23, 2023 |
| HP            | 1905                        | Desktop     | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [ae8071638f](https://linux-hardware.org/?probe=ae8071638f) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1e9774c53c](https://linux-hardware.org/?probe=1e9774c53c) | Sep 22, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [85c3791741](https://linux-hardware.org/?probe=85c3791741) | Sep 21, 2023 |
| MSI           | MS-7318                     | Desktop     | [38f011e50d](https://linux-hardware.org/?probe=38f011e50d) | Sep 21, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [c96e63c738](https://linux-hardware.org/?probe=c96e63c738) | Sep 20, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [6f6fbfc86f](https://linux-hardware.org/?probe=6f6fbfc86f) | Sep 20, 2023 |
| Dell          | Precision 5560              | Notebook    | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | Notebook    | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Dell          | Precision 7550              | Notebook    | [75394df91f](https://linux-hardware.org/?probe=75394df91f) | Sep 19, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [6879449933](https://linux-hardware.org/?probe=6879449933) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [e14140ad96](https://linux-hardware.org/?probe=e14140ad96) | Sep 18, 2023 |
| Gigabyte      | H55N-USB3                   | Desktop     | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| HP            | 8158 A01                    | Mini pc     | [bd8aa3d09c](https://linux-hardware.org/?probe=bd8aa3d09c) | Sep 18, 2023 |
| Acer          | TravelMate P446-MG          | Notebook    | [08d9d6868b](https://linux-hardware.org/?probe=08d9d6868b) | Sep 17, 2023 |
| Supermicro    | X9DR3-F                     | Desktop     | [c2f0532df1](https://linux-hardware.org/?probe=c2f0532df1) | Sep 17, 2023 |
| Google        | Droid                       | Notebook    | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [f8e68bfc81](https://linux-hardware.org/?probe=f8e68bfc81) | Sep 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [f89ec253d3](https://linux-hardware.org/?probe=f89ec253d3) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | Notebook    | [3eb787f2ec](https://linux-hardware.org/?probe=3eb787f2ec) | Sep 15, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae1f2b94e5](https://linux-hardware.org/?probe=ae1f2b94e5) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| MSI           | 970A-G46                    | Desktop     | [722b900724](https://linux-hardware.org/?probe=722b900724) | Sep 11, 2023 |
| Panasonic     | CF-19RHR3DPM                | Notebook    | [11484f2d00](https://linux-hardware.org/?probe=11484f2d00) | Sep 10, 2023 |
| Dell          | Precision 5530              | Notebook    | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| ASRock        | H81M-HG4                    | Desktop     | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| HP            | 876C SMVB                   | Desktop     | [f122d202cc](https://linux-hardware.org/?probe=f122d202cc) | Sep 10, 2023 |
| Acer          | Extensa 5220                | Notebook    | [c4ea757260](https://linux-hardware.org/?probe=c4ea757260) | Sep 10, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [91decda3c9](https://linux-hardware.org/?probe=91decda3c9) | Sep 09, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [724826d84b](https://linux-hardware.org/?probe=724826d84b) | Sep 09, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [9ce78af6e9](https://linux-hardware.org/?probe=9ce78af6e9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e8fe3531c7](https://linux-hardware.org/?probe=e8fe3531c7) | Sep 08, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6bea6e300b](https://linux-hardware.org/?probe=6bea6e300b) | Sep 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da21e863a4](https://linux-hardware.org/?probe=da21e863a4) | Sep 07, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | Desktop     | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | Desktop     | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | Desktop     | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | Desktop     | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0841c5e196](https://linux-hardware.org/?probe=0841c5e196) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8d52d37e1e](https://linux-hardware.org/?probe=8d52d37e1e) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [c6d9dc5a3b](https://linux-hardware.org/?probe=c6d9dc5a3b) | Sep 03, 2023 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c3fe8cb8e9](https://linux-hardware.org/?probe=c3fe8cb8e9) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [e0133bb14e](https://linux-hardware.org/?probe=e0133bb14e) | Sep 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a200aa5407](https://linux-hardware.org/?probe=a200aa5407) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7e93b2a981](https://linux-hardware.org/?probe=7e93b2a981) | Sep 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| HP            | 1495                        | Desktop     | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| HP            | ProBook 6460b               | Notebook    | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [52306fce15](https://linux-hardware.org/?probe=52306fce15) | Aug 29, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| HP            | 1495                        | Desktop     | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [5d748b1e22](https://linux-hardware.org/?probe=5d748b1e22) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| HP            | 158A                        | Desktop     | [e154a48901](https://linux-hardware.org/?probe=e154a48901) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| Rockchip      | RK3568 EVB1 DDR4 V10        | Soc         | [846c733ed7](https://linux-hardware.org/?probe=846c733ed7) | Aug 24, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a1bdeba9c8](https://linux-hardware.org/?probe=a1bdeba9c8) | Aug 23, 2023 |
| Lenovo        | IdeaPad Z485 20151          | Notebook    | [599346f806](https://linux-hardware.org/?probe=599346f806) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | Notebook    | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [93853db701](https://linux-hardware.org/?probe=93853db701) | Aug 21, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [f9058bcea1](https://linux-hardware.org/?probe=f9058bcea1) | Aug 21, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [5f5f76ff98](https://linux-hardware.org/?probe=5f5f76ff98) | Aug 21, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cb4da51551](https://linux-hardware.org/?probe=cb4da51551) | Aug 21, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [fd5614f8d1](https://linux-hardware.org/?probe=fd5614f8d1) | Aug 21, 2023 |
| Bananapi      | BPI-M5                      | Soc         | [0bd2202791](https://linux-hardware.org/?probe=0bd2202791) | Aug 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [fb3c8c793c](https://linux-hardware.org/?probe=fb3c8c793c) | Aug 19, 2023 |
| Medion        | MS-7728                     | Desktop     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [8b347c4d9d](https://linux-hardware.org/?probe=8b347c4d9d) | Aug 19, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [b88e1a5605](https://linux-hardware.org/?probe=b88e1a5605) | Aug 18, 2023 |
| Acer          | Aspire one                  | Notebook    | [47131c09b2](https://linux-hardware.org/?probe=47131c09b2) | Aug 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [4906f87d9e](https://linux-hardware.org/?probe=4906f87d9e) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | Notebook    | [66c997fdec](https://linux-hardware.org/?probe=66c997fdec) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | Notebook    | [e57e76260c](https://linux-hardware.org/?probe=e57e76260c) | Aug 16, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [defef9b917](https://linux-hardware.org/?probe=defef9b917) | Aug 16, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [12e5d1c399](https://linux-hardware.org/?probe=12e5d1c399) | Aug 15, 2023 |
| Unknown       | Variscite DART-MX8M-MINI... | Soc         | [a185c83285](https://linux-hardware.org/?probe=a185c83285) | Aug 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [4c24f10db4](https://linux-hardware.org/?probe=4c24f10db4) | Aug 15, 2023 |
| Dell          | 0CT017                      | Desktop     | [0800c86065](https://linux-hardware.org/?probe=0800c86065) | Aug 14, 2023 |
| Unknown       | CN700-8237                  | Desktop     | [5890f075f7](https://linux-hardware.org/?probe=5890f075f7) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [650f840aa5](https://linux-hardware.org/?probe=650f840aa5) | Aug 13, 2023 |
| Lenovo        | ThinkPad W530 24477V0       | Notebook    | [2e09955f2f](https://linux-hardware.org/?probe=2e09955f2f) | Aug 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c7bc7c3f16](https://linux-hardware.org/?probe=c7bc7c3f16) | Aug 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3508d6c711](https://linux-hardware.org/?probe=3508d6c711) | Aug 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a28cd220cd](https://linux-hardware.org/?probe=a28cd220cd) | Aug 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [f62d9a8a9a](https://linux-hardware.org/?probe=f62d9a8a9a) | Aug 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ed029dd5e3](https://linux-hardware.org/?probe=ed029dd5e3) | Aug 12, 2023 |
| ASRock        | J4125B-ITX                  | Desktop     | [fa9ebd523f](https://linux-hardware.org/?probe=fa9ebd523f) | Aug 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [053608e18a](https://linux-hardware.org/?probe=053608e18a) | Aug 11, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| ASUSTek       | 1005PE                      | Notebook    | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| AZW           | GTR V01                     | Mini pc     | [8b0b0e8cc4](https://linux-hardware.org/?probe=8b0b0e8cc4) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| HP            | 8433 11                     | Desktop     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [42d4093f63](https://linux-hardware.org/?probe=42d4093f63) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| Biostar       | B365MHC                     | Desktop     | [1a7d051f1e](https://linux-hardware.org/?probe=1a7d051f1e) | Aug 06, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4b57f7d6ea](https://linux-hardware.org/?probe=4b57f7d6ea) | Aug 06, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [217bd70a25](https://linux-hardware.org/?probe=217bd70a25) | Aug 06, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [079428c572](https://linux-hardware.org/?probe=079428c572) | Aug 05, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [663f989185](https://linux-hardware.org/?probe=663f989185) | Aug 05, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [c157382bd3](https://linux-hardware.org/?probe=c157382bd3) | Aug 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da2ada0c83](https://linux-hardware.org/?probe=da2ada0c83) | Aug 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [1b1f671f30](https://linux-hardware.org/?probe=1b1f671f30) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | Desktop     | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [18f95b58ac](https://linux-hardware.org/?probe=18f95b58ac) | Aug 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [df3495c01c](https://linux-hardware.org/?probe=df3495c01c) | Aug 04, 2023 |
| HP            | Lantis                      | Notebook    | [2c917365b3](https://linux-hardware.org/?probe=2c917365b3) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [349de8928b](https://linux-hardware.org/?probe=349de8928b) | Aug 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [127555ff0c](https://linux-hardware.org/?probe=127555ff0c) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| Packard Be... | H17HV                       | Notebook    | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | Desktop     | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cd8671be26](https://linux-hardware.org/?probe=cd8671be26) | Jul 31, 2023 |
| NEC Comput... | PC-VY22GXZCA                | Notebook    | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Intel         | NUC7i7DNB J83500-207        | Mini pc     | [e18855dc59](https://linux-hardware.org/?probe=e18855dc59) | Jul 30, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | Notebook    | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| Sony          | SVS13A1Z9RN                 | Notebook    | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [4cbba6622f](https://linux-hardware.org/?probe=4cbba6622f) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [8cf3decf30](https://linux-hardware.org/?probe=8cf3decf30) | Jul 28, 2023 |
| Acer          | Extensa 215-32              | Notebook    | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [e873051e73](https://linux-hardware.org/?probe=e873051e73) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | Notebook    | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| ABIT          | NF7-S/NF7,NF7-V,1.0         | Desktop     | [f5184af4e0](https://linux-hardware.org/?probe=f5184af4e0) | Jul 27, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [b2dd23136f](https://linux-hardware.org/?probe=b2dd23136f) | Jul 26, 2023 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [c7373023dd](https://linux-hardware.org/?probe=c7373023dd) | Jul 26, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2fa28e6952](https://linux-hardware.org/?probe=2fa28e6952) | Jul 26, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [64d86600a4](https://linux-hardware.org/?probe=64d86600a4) | Jul 26, 2023 |
| Dell          | 09CGW2 A04                  | Server      | [159d6b1be1](https://linux-hardware.org/?probe=159d6b1be1) | Jul 26, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [787c6a9252](https://linux-hardware.org/?probe=787c6a9252) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| HP            | ProLiant DL580 G7           | Server      | [5a9a1e320d](https://linux-hardware.org/?probe=5a9a1e320d) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9243bb6a08](https://linux-hardware.org/?probe=9243bb6a08) | Jul 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [73f0811a7b](https://linux-hardware.org/?probe=73f0811a7b) | Jul 23, 2023 |
| Dell          | Latitude E7250              | Notebook    | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| Dell          | 0K7CVF A03                  | Server      | [228949ef5a](https://linux-hardware.org/?probe=228949ef5a) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | Desktop     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | Desktop     | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [b2938336ce](https://linux-hardware.org/?probe=b2938336ce) | Jul 22, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | Notebook    | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8f26110e1a](https://linux-hardware.org/?probe=8f26110e1a) | Jul 20, 2023 |
| AAEON         | GENE-CML5 V1.0              | Desktop     | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [98cddbfe0e](https://linux-hardware.org/?probe=98cddbfe0e) | Jul 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | Notebook    | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [da4d6e8a5c](https://linux-hardware.org/?probe=da4d6e8a5c) | Jul 18, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [00c711574a](https://linux-hardware.org/?probe=00c711574a) | Jul 17, 2023 |
| HP            | 805A                        | Desktop     | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | X505BA                      | Notebook    | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0d3af45e51](https://linux-hardware.org/?probe=0d3af45e51) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Dell          | Latitude E6440              | Notebook    | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [15d31e889c](https://linux-hardware.org/?probe=15d31e889c) | Jul 16, 2023 |
| Unknown       | Unknown                     | Soc         | [99bfa94ff7](https://linux-hardware.org/?probe=99bfa94ff7) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | Desktop     | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [d2620e5fee](https://linux-hardware.org/?probe=d2620e5fee) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | Notebook    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| Acer          | Aspire R7-371T              | Notebook    | [c4f6270bdb](https://linux-hardware.org/?probe=c4f6270bdb) | Jul 15, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [8ca31a1cfb](https://linux-hardware.org/?probe=8ca31a1cfb) | Jul 15, 2023 |
| Intel         | M70KLP2SB M22209-100        | Server      | [afa5fbc4a3](https://linux-hardware.org/?probe=afa5fbc4a3) | Jul 14, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [e6d47a005f](https://linux-hardware.org/?probe=e6d47a005f) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | Notebook    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c4af2e9b6c](https://linux-hardware.org/?probe=c4af2e9b6c) | Jul 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [70b2ff6533](https://linux-hardware.org/?probe=70b2ff6533) | Jul 13, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [13f3a107dc](https://linux-hardware.org/?probe=13f3a107dc) | Jul 13, 2023 |
| MSI           | H170M PRO-VDH               | Desktop     | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| Dell          | Latitude E6330              | Notebook    | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | Desktop     | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| Positivo      | Mobile                      | Notebook    | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | Desktop     | [b330e5c4fb](https://linux-hardware.org/?probe=b330e5c4fb) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | Desktop     | [c0fb949fdc](https://linux-hardware.org/?probe=c0fb949fdc) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [02a820f6b2](https://linux-hardware.org/?probe=02a820f6b2) | Jul 11, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [544563aaae](https://linux-hardware.org/?probe=544563aaae) | Jul 11, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [1e6fc6f253](https://linux-hardware.org/?probe=1e6fc6f253) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ba7cde1766](https://linux-hardware.org/?probe=ba7cde1766) | Jul 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [798f921e70](https://linux-hardware.org/?probe=798f921e70) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| AZW           | U59                         | Desktop     | [5cf3ddbe4b](https://linux-hardware.org/?probe=5cf3ddbe4b) | Jul 08, 2023 |
| AZW           | U59                         | Desktop     | [ea367423d1](https://linux-hardware.org/?probe=ea367423d1) | Jul 08, 2023 |
| AZW           | MINI S                      | Desktop     | [b13eb96728](https://linux-hardware.org/?probe=b13eb96728) | Jul 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0a2ad7c1a6](https://linux-hardware.org/?probe=0a2ad7c1a6) | Jul 08, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | Notebook    | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f4b26c97fe](https://linux-hardware.org/?probe=f4b26c97fe) | Jul 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8daacdd31c](https://linux-hardware.org/?probe=8daacdd31c) | Jul 06, 2023 |
| Dell          | 0WKGTH A02                  | Server      | [4bbbfd7eb9](https://linux-hardware.org/?probe=4bbbfd7eb9) | Jul 05, 2023 |
| HP            | 895C                        | Desktop     | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e57d7c40d](https://linux-hardware.org/?probe=1e57d7c40d) | Jul 05, 2023 |
| NEC Comput... | PC-VK27MBZCG                | Notebook    | [5db0d02025](https://linux-hardware.org/?probe=5db0d02025) | Jul 04, 2023 |
| Dell          | 0KYWH7 A00                  | Desktop     | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [b7328dc212](https://linux-hardware.org/?probe=b7328dc212) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| Dell          | 0X904N A05                  | Server      | [b7335a46c8](https://linux-hardware.org/?probe=b7335a46c8) | Jul 03, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [e000de29fe](https://linux-hardware.org/?probe=e000de29fe) | Jul 03, 2023 |
| EPoX Compu... | Intel I945 DDR2 : 5P945-... | Desktop     | [5aa77af58f](https://linux-hardware.org/?probe=5aa77af58f) | Jul 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8bb4af1cb5](https://linux-hardware.org/?probe=8bb4af1cb5) | Jul 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cd68e8f8b](https://linux-hardware.org/?probe=7cd68e8f8b) | Jul 03, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [8e758ec922](https://linux-hardware.org/?probe=8e758ec922) | Jul 03, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ed37dd6278](https://linux-hardware.org/?probe=ed37dd6278) | Jul 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [f17cce1847](https://linux-hardware.org/?probe=f17cce1847) | Jul 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [2eb6c4356c](https://linux-hardware.org/?probe=2eb6c4356c) | Jul 02, 2023 |
| Unknown       | Unknown                     | Soc         | [bc8f4620bd](https://linux-hardware.org/?probe=bc8f4620bd) | Jul 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a66c76ab6c](https://linux-hardware.org/?probe=a66c76ab6c) | Jul 02, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [bac142132d](https://linux-hardware.org/?probe=bac142132d) | Jul 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [24adbf0475](https://linux-hardware.org/?probe=24adbf0475) | Jul 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [bd84f79486](https://linux-hardware.org/?probe=bd84f79486) | Jul 01, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [b89ca471ef](https://linux-hardware.org/?probe=b89ca471ef) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [7e37520061](https://linux-hardware.org/?probe=7e37520061) | Jun 30, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cb1bcce659](https://linux-hardware.org/?probe=cb1bcce659) | Jun 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cb124d729](https://linux-hardware.org/?probe=7cb124d729) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| Dell          | Latitude 7370               | Notebook    | [cb11921012](https://linux-hardware.org/?probe=cb11921012) | Jun 28, 2023 |
| Shuttle       | FS61                        | Desktop     | [a67d2edea8](https://linux-hardware.org/?probe=a67d2edea8) | Jun 28, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [f60ead06fd](https://linux-hardware.org/?probe=f60ead06fd) | Jun 28, 2023 |
| Lenovo        | ThinkPad X280 20KF001RUK    | Notebook    | [a1da72b9a5](https://linux-hardware.org/?probe=a1da72b9a5) | Jun 27, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [65fb07ed8d](https://linux-hardware.org/?probe=65fb07ed8d) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [baf77629c1](https://linux-hardware.org/?probe=baf77629c1) | Jun 26, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [fe211e4239](https://linux-hardware.org/?probe=fe211e4239) | Jun 26, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b4fcf1904c](https://linux-hardware.org/?probe=b4fcf1904c) | Jun 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [29cc577c0c](https://linux-hardware.org/?probe=29cc577c0c) | Jun 26, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [695dd94347](https://linux-hardware.org/?probe=695dd94347) | Jun 25, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9dce40179d](https://linux-hardware.org/?probe=9dce40179d) | Jun 25, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| Google        | Kip                         | Notebook    | [4e1bfd359e](https://linux-hardware.org/?probe=4e1bfd359e) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [2d49269787](https://linux-hardware.org/?probe=2d49269787) | Jun 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [71f114122e](https://linux-hardware.org/?probe=71f114122e) | Jun 23, 2023 |
| Lenovo        | Edge 15 80H1                | Notebook    | [aff25effc2](https://linux-hardware.org/?probe=aff25effc2) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| HP            | 3397                        | Desktop     | [8c9be2f4c0](https://linux-hardware.org/?probe=8c9be2f4c0) | Jun 23, 2023 |
| VIT           | P2423                       | Notebook    | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [d419086209](https://linux-hardware.org/?probe=d419086209) | Jun 22, 2023 |
| Supermicro    | X8DTU                       | Server      | [d8d978bd73](https://linux-hardware.org/?probe=d8d978bd73) | Jun 22, 2023 |
| HP            | 3397                        | Desktop     | [a47ce0d4dc](https://linux-hardware.org/?probe=a47ce0d4dc) | Jun 22, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a7b7b2c413](https://linux-hardware.org/?probe=a7b7b2c413) | Jun 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [72f4d53246](https://linux-hardware.org/?probe=72f4d53246) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d4bd011ff9](https://linux-hardware.org/?probe=d4bd011ff9) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [e1fdcf84b3](https://linux-hardware.org/?probe=e1fdcf84b3) | Jun 21, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [f18c138ec9](https://linux-hardware.org/?probe=f18c138ec9) | Jun 21, 2023 |
| Lenovo        | 01GR176                     | Server      | [6d28cbec97](https://linux-hardware.org/?probe=6d28cbec97) | Jun 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| MSI           | H81M-P33                    | Desktop     | [62fb9cda50](https://linux-hardware.org/?probe=62fb9cda50) | Jun 20, 2023 |
| Dell          | 06FW8P A02                  | Desktop     | [f65ec61ffc](https://linux-hardware.org/?probe=f65ec61ffc) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | Notebook    | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Amlogic       | Meson GXL (S905X) P212 D... | Soc         | [7c79fa6641](https://linux-hardware.org/?probe=7c79fa6641) | Jun 19, 2023 |
| Dell          | 0PU052                      | Desktop     | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1559b0a68d](https://linux-hardware.org/?probe=1559b0a68d) | Jun 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [640ff2ce2e](https://linux-hardware.org/?probe=640ff2ce2e) | Jun 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| AZW           | U59                         | Desktop     | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [ec95321dfb](https://linux-hardware.org/?probe=ec95321dfb) | Jun 17, 2023 |
| Dell          | Precision M2800             | Notebook    | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1cabb1c87f](https://linux-hardware.org/?probe=1cabb1c87f) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| HP            | 1589                        | Desktop     | [6bfe1d5b63](https://linux-hardware.org/?probe=6bfe1d5b63) | Jun 15, 2023 |
| Medion        | E6214                       | Notebook    | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c1375ab639](https://linux-hardware.org/?probe=c1375ab639) | Jun 15, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2754ddde7f](https://linux-hardware.org/?probe=2754ddde7f) | Jun 15, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [4cc6199522](https://linux-hardware.org/?probe=4cc6199522) | Jun 15, 2023 |
| Dell          | Latitude 5480               | Notebook    | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [6e241e56cf](https://linux-hardware.org/?probe=6e241e56cf) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f9ebdca1bd](https://linux-hardware.org/?probe=f9ebdca1bd) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| Supermicro    | X11DPU                      | Server      | [f7937cfbf6](https://linux-hardware.org/?probe=f7937cfbf6) | Jun 14, 2023 |
| Supermicro    | X11DPH-T                    | Server      | [ed5dc59bc2](https://linux-hardware.org/?probe=ed5dc59bc2) | Jun 14, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [3b954125c5](https://linux-hardware.org/?probe=3b954125c5) | Jun 13, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [84cd8a6537](https://linux-hardware.org/?probe=84cd8a6537) | Jun 13, 2023 |
| HP            | 2AED                        | Desktop     | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| Intel         | JSL MRD                     | Desktop     | [764e533752](https://linux-hardware.org/?probe=764e533752) | Jun 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b4a1eae7be](https://linux-hardware.org/?probe=b4a1eae7be) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [675f082570](https://linux-hardware.org/?probe=675f082570) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | Notebook    | [45b16c1cdf](https://linux-hardware.org/?probe=45b16c1cdf) | Jun 12, 2023 |
| Fujitsu       | LIFEBOOK A514               | Notebook    | [1da963b3f4](https://linux-hardware.org/?probe=1da963b3f4) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [2ea9fd5a4a](https://linux-hardware.org/?probe=2ea9fd5a4a) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [9ed0a99c90](https://linux-hardware.org/?probe=9ed0a99c90) | Jun 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [5bc42066ca](https://linux-hardware.org/?probe=5bc42066ca) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [f7397ff305](https://linux-hardware.org/?probe=f7397ff305) | Jun 11, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | Notebook    | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5e3b6bfb4c](https://linux-hardware.org/?probe=5e3b6bfb4c) | Jun 11, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [8772d55075](https://linux-hardware.org/?probe=8772d55075) | Jun 10, 2023 |
| Dell          | Latitude 7440               | Notebook    | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4527394e](https://linux-hardware.org/?probe=ba4527394e) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | Notebook    | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| Acidanther... | MacBookPro15,2              | Notebook    | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [af396cb333](https://linux-hardware.org/?probe=af396cb333) | Jun 10, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [012e8255f3](https://linux-hardware.org/?probe=012e8255f3) | Jun 09, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [50844825e2](https://linux-hardware.org/?probe=50844825e2) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | Notebook    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | Notebook    | [d992393271](https://linux-hardware.org/?probe=d992393271) | Jun 08, 2023 |
| Lenovo        | ThinkPad X131e 3374A17      | Notebook    | [dd385507aa](https://linux-hardware.org/?probe=dd385507aa) | Jun 08, 2023 |
| HP            | Pavilion 17                 | Notebook    | [da809f90cc](https://linux-hardware.org/?probe=da809f90cc) | Jun 07, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| HP            | ProBook 4530s               | Notebook    | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | Notebook    | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | Desktop     | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| MSI           | Pulse GL66 12UDK            | Notebook    | [8c9a9eb310](https://linux-hardware.org/?probe=8c9a9eb310) | Jun 06, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [2532dfadd0](https://linux-hardware.org/?probe=2532dfadd0) | Jun 06, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [5cc10b1e1e](https://linux-hardware.org/?probe=5cc10b1e1e) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [c685007aa8](https://linux-hardware.org/?probe=c685007aa8) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [72eb9f0d86](https://linux-hardware.org/?probe=72eb9f0d86) | Jun 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da03bf4e08](https://linux-hardware.org/?probe=da03bf4e08) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | Notebook    | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| ASUSTek       | Q502LA                      | Notebook    | [679a477085](https://linux-hardware.org/?probe=679a477085) | Jun 04, 2023 |
| Clevo         | M670SRU                     | Notebook    | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | Notebook    | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| AVITA         | NS14A8                      | Notebook    | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [01e8918ef6](https://linux-hardware.org/?probe=01e8918ef6) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | Notebook    | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| Lenovo        | ThinkPad E420 1141R79       | Notebook    | [7f66bf0045](https://linux-hardware.org/?probe=7f66bf0045) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | Notebook    | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [b1513dc005](https://linux-hardware.org/?probe=b1513dc005) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Gigabyte      | P75-D3                      | Desktop     | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | Desktop     | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | Latitude E6430              | Notebook    | [b129765265](https://linux-hardware.org/?probe=b129765265) | Jun 02, 2023 |
| Dell          | 0D456H A00                  | Server      | [4e0d53d64d](https://linux-hardware.org/?probe=4e0d53d64d) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [2a1e548be7](https://linux-hardware.org/?probe=2a1e548be7) | Jun 01, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [ea09e45a4f](https://linux-hardware.org/?probe=ea09e45a4f) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| Dell          | Latitude E5510              | Notebook    | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a4363d8242](https://linux-hardware.org/?probe=a4363d8242) | Jun 01, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [19043cab25](https://linux-hardware.org/?probe=19043cab25) | Jun 01, 2023 |
| Positivo      | C500                        | Notebook    | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| ASUSTek       | X200LA                      | Notebook    | [ae3925153d](https://linux-hardware.org/?probe=ae3925153d) | May 31, 2023 |
| ASUSTek       | 1225B                       | Notebook    | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [1e5f49bbf4](https://linux-hardware.org/?probe=1e5f49bbf4) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aad1baf686](https://linux-hardware.org/?probe=aad1baf686) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Dell          | Latitude 5411               | Notebook    | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | Notebook    | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| Intel         | X99                         | Desktop     | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| Dell          | Latitude E5510              | Notebook    | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| ASUSTek       | P4S8L                       | Desktop     | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 966       | 12.39%  |
| 5.10.0-7-amd64         | 693       | 8.89%   |
| 5.10.0-10-amd64        | 577       | 7.4%    |
| 5.10.0-21-amd64        | 469       | 6.02%   |
| 5.10.0-20-amd64        | 378       | 4.85%   |
| 5.10.0-16-amd64        | 373       | 4.79%   |
| 5.10.0-9-amd64         | 327       | 4.2%    |
| 5.10.0-19-amd64        | 294       | 3.77%   |
| 5.10.0-18-amd64        | 294       | 3.77%   |
| 5.10.0-13-amd64        | 265       | 3.4%    |
| 5.10.0-23-amd64        | 223       | 2.86%   |
| 5.10.0-11-amd64        | 193       | 2.48%   |
| 5.10.0-2-amd64         | 158       | 2.03%   |
| 5.10.0-14-amd64        | 141       | 1.81%   |
| 5.10.0-17-amd64        | 126       | 1.62%   |
| 5.10.0-15-amd64        | 110       | 1.41%   |
| 5.10.0-22-amd64        | 107       | 1.37%   |
| 5.10.0-26-amd64        | 75        | 0.96%   |
| 5.10.0-12-amd64        | 73        | 0.94%   |
| 5.10.0-28-amd64        | 47        | 0.6%    |
| 6.0.0-0.deb11.6-amd64  | 46        | 0.59%   |
| 5.10.0-6-amd64         | 46        | 0.59%   |
| 5.18.0-0.deb11.4-amd64 | 45        | 0.58%   |
| 5.10.0-25-amd64        | 44        | 0.56%   |
| 6.1.21-v8+             | 38        | 0.49%   |
| 5.16.0-0.bpo.4-amd64   | 38        | 0.49%   |
| 5.15.0-2-amd64         | 36        | 0.46%   |
| 5.10.0-27-amd64        | 35        | 0.45%   |
| 5.10.0-13-686-pae      | 30        | 0.38%   |
| 6.0.0-0.deb11.2-amd64  | 29        | 0.37%   |
| 5.19.0-0.deb11.2-amd64 | 27        | 0.35%   |
| 5.18.0-0.bpo.1-amd64   | 26        | 0.33%   |
| 5.15.74-1-pve          | 25        | 0.32%   |
| 5.14.0-0.bpo.2-amd64   | 25        | 0.32%   |
| 6.1.0-0.deb11.7-amd64  | 24        | 0.31%   |
| 5.13.19-6-pve          | 24        | 0.31%   |
| 5.15.85-1-pve          | 22        | 0.28%   |
| 5.15.102-1-pve         | 21        | 0.27%   |
| 5.15.107-2-pve         | 20        | 0.26%   |
| 6.1.0-0.deb11.5-amd64  | 19        | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 5733      | 79.8%   |
| 6.0.0    | 104       | 1.45%   |
| 6.1.0    | 99        | 1.38%   |
| 5.18.0   | 99        | 1.38%   |
| 5.15.0   | 79        | 1.1%    |
| 5.16.0   | 72        | 1%      |
| 5.19.0   | 62        | 0.86%   |
| 5.13.19  | 60        | 0.84%   |
| 5.14.0   | 43        | 0.6%    |
| 6.1.21   | 38        | 0.53%   |
| 5.15.107 | 35        | 0.49%   |
| 5.15.74  | 29        | 0.4%    |
| 5.11.22  | 26        | 0.36%   |
| 5.17.0   | 25        | 0.35%   |
| 5.15.85  | 22        | 0.31%   |
| 5.15.102 | 21        | 0.29%   |
| 5.15.84  | 20        | 0.28%   |
| 5.15.83  | 19        | 0.26%   |
| 5.15.39  | 19        | 0.26%   |
| 5.15.30  | 19        | 0.26%   |
| 5.15.32  | 18        | 0.25%   |
| 5.15.35  | 17        | 0.24%   |
| 5.15.76  | 16        | 0.22%   |
| 5.15.53  | 15        | 0.21%   |
| 5.10.92  | 15        | 0.21%   |
| 5.15.61  | 13        | 0.18%   |
| 5.15.108 | 13        | 0.18%   |
| 5.15.126 | 11        | 0.15%   |
| 5.15.104 | 10        | 0.14%   |
| 4.19.0   | 10        | 0.14%   |
| 6.2.16   | 8         | 0.11%   |
| 6.1.15   | 8         | 0.11%   |
| 5.19.17  | 8         | 0.11%   |
| 5.15.60  | 8         | 0.11%   |
| 5.10.110 | 8         | 0.11%   |
| 6.2.6    | 7         | 0.1%    |
| 5.13.0   | 7         | 0.1%    |
| 5.10.63  | 7         | 0.1%    |
| 5.10.60  | 7         | 0.1%    |
| 6.2.9    | 6         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10     | 5826      | 81.6%   |
| 5.15     | 428       | 5.99%   |
| 6.1      | 173       | 2.42%   |
| 6.0      | 120       | 1.68%   |
| 5.18     | 108       | 1.51%   |
| 5.16     | 84        | 1.18%   |
| 5.19     | 83        | 1.16%   |
| 5.13     | 80        | 1.12%   |
| 5.14     | 50        | 0.7%    |
| 6.2      | 35        | 0.49%   |
| 5.17     | 35        | 0.49%   |
| 5.11     | 35        | 0.49%   |
| 4.19     | 12        | 0.17%   |
| 5.4      | 11        | 0.15%   |
| 5.12     | 9         | 0.13%   |
| 6.3      | 7         | 0.1%    |
| 5        | 5         | 0.07%   |
| 4.9      | 5         | 0.07%   |
| 6.5      | 4         | 0.06%   |
| 6.4      | 4         | 0.06%   |
| 4.4      | 4         | 0.06%   |
| 6.7      | 3         | 0.04%   |
| 6.6      | 3         | 0.04%   |
| 5.9      | 3         | 0.04%   |
| 5.1      | 3         | 0.04%   |
| 3.18     | 2         | 0.03%   |
| 6        | 1         | 0.01%   |
| 5.8      | 1         | 0.01%   |
| 5.5      | 1         | 0.01%   |
| 5.15.6   | 1         | 0.01%   |
| 5.10.164 | 1         | 0.01%   |
| 4.14     | 1         | 0.01%   |
| 3.8      | 1         | 0.01%   |
| 3.10     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6500      | 93.07%  |
| aarch64 | 233       | 3.34%   |
| i686    | 208       | 2.98%   |
| armv7l  | 36        | 0.52%   |
| riscv64 | 6         | 0.09%   |
| i586    | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2597      | 36.61%  |
| GNOME             | 1568      | 22.11%  |
| XFCE              | 821       | 11.57%  |
| KDE5              | 784       | 11.05%  |
| MATE              | 273       | 3.85%   |
| LXDE              | 231       | 3.26%   |
| X-Cinnamon        | 213       | 3%      |
| Cinnamon          | 171       | 2.41%   |
| LXQt              | 96        | 1.35%   |
| i3                | 72        | 1.02%   |
| KDE               | 55        | 0.78%   |
| Openbox           | 44        | 0.62%   |
| GNOME Flashback   | 41        | 0.58%   |
| lightdm-xsession  | 28        | 0.39%   |
| Trinity           | 22        | 0.31%   |
| GNOME Classic     | 15        | 0.21%   |
| Budgie            | 15        | 0.21%   |
| sway              | 5         | 0.07%   |
| awesome           | 5         | 0.07%   |
| DWM               | 4         | 0.06%   |
| x-session-manager | 3         | 0.04%   |
| ICEWM             | 3         | 0.04%   |
| Enlightenment     | 3         | 0.04%   |
| Cutefish          | 3         | 0.04%   |
| BunsenLabs        | 3         | 0.04%   |
| GNUstep           | 2         | 0.03%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| Unity             | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| TOS:GNOME         | 1         | 0.01%   |
| Phosh:GNOME       | 1         | 0.01%   |
| mwm               | 1         | 0.01%   |
| matchbox          | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |
| gnome-xorg        | 1         | 0.01%   |
| fvwm              | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| e16-session       | 1         | 0.01%   |
| default           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 3288      | 46.43%  |
| Unknown     | 1868      | 26.38%  |
| Wayland     | 1008      | 14.24%  |
| Tty         | 907       | 12.81%  |
| Unspecified | 6         | 0.08%   |
| Web         | 4         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3335      | 47.22%  |
| LightDM | 1440      | 20.39%  |
| GDM     | 1250      | 17.7%   |
| SDDM    | 690       | 9.77%   |
| TDM     | 156       | 2.21%   |
| GDM3    | 133       | 1.88%   |
| XDM     | 18        | 0.25%   |
| SLiM    | 15        | 0.21%   |
| LXDM    | 12        | 0.17%   |
| NODM    | 8         | 0.11%   |
| SU      | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2392      | 33.9%   |
| ru_RU   | 958       | 13.58%  |
| Unknown | 947       | 13.42%  |
| de_DE   | 424       | 6.01%   |
| en_GB   | 356       | 5.05%   |
| fr_FR   | 353       | 5%      |
| es_ES   | 202       | 2.86%   |
| it_IT   | 163       | 2.31%   |
| pt_BR   | 156       | 2.21%   |
| pl_PL   | 112       | 1.59%   |
| C       | 88        | 1.25%   |
| en_CA   | 82        | 1.16%   |
| en_AU   | 82        | 1.16%   |
| es_MX   | 53        | 0.75%   |
| es_AR   | 48        | 0.68%   |
| zh_CN   | 46        | 0.65%   |
| es_VE   | 32        | 0.45%   |
| en_IN   | 32        | 0.45%   |
| hu_HU   | 31        | 0.44%   |
| en_IE   | 30        | 0.43%   |
| ja_JP   | 24        | 0.34%   |
| de_CH   | 24        | 0.34%   |
| de_AT   | 23        | 0.33%   |
| nl_NL   | 20        | 0.28%   |
| en_NZ   | 18        | 0.26%   |
| fi_FI   | 17        | 0.24%   |
| sv_SE   | 16        | 0.23%   |
| pt_PT   | 16        | 0.23%   |
| es_CO   | 14        | 0.2%    |
| es_CL   | 14        | 0.2%    |
| cs_CZ   | 13        | 0.18%   |
| tr_TR   | 12        | 0.17%   |
| nl_BE   | 12        | 0.17%   |
| fr_CH   | 12        | 0.17%   |
| fr_BE   | 12        | 0.17%   |
| en_ZA   | 12        | 0.17%   |
| ca_ES   | 10        | 0.14%   |
| zh_TW   | 9         | 0.13%   |
| nb_NO   | 9         | 0.13%   |
| en_SG   | 9         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4065      | 57.61%  |
| BIOS | 2991      | 42.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 4653      | 66.29%  |
| Overlay | 1896      | 27.01%  |
| Btrfs   | 210       | 2.99%   |
| Zfs     | 117       | 1.67%   |
| Xfs     | 72        | 1.03%   |
| Tmpfs   | 31        | 0.44%   |
| Ext3    | 16        | 0.23%   |
| Ext2    | 10        | 0.14%   |
| Unknown | 9         | 0.13%   |
| Rootfs  | 3         | 0.04%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4228      | 59.9%   |
| MBR     | 1910      | 27.06%  |
| Unknown | 921       | 13.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5721      | 81.16%  |
| Yes       | 1328      | 18.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4947      | 70.23%  |
| Yes       | 2097      | 29.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 992       | 14.21%  |
| Lenovo                  | 964       | 13.81%  |
| Hewlett-Packard         | 768       | 11%     |
| Apple                   | 695       | 9.95%   |
| Dell                    | 683       | 9.78%   |
| Gigabyte Technology     | 431       | 6.17%   |
| MSI                     | 318       | 4.55%   |
| Acer                    | 254       | 3.64%   |
| ASRock                  | 244       | 3.49%   |
| Intel                   | 170       | 2.43%   |
| Raspberry Pi Foundation | 166       | 2.38%   |
| Google                  | 141       | 2.02%   |
| Unknown                 | 113       | 1.62%   |
| Supermicro              | 70        | 1%      |
| Fujitsu                 | 59        | 0.85%   |
| Toshiba                 | 57        | 0.82%   |
| ECS                     | 49        | 0.7%    |
| Aquarius                | 47        | 0.67%   |
| Samsung Electronics     | 44        | 0.63%   |
| AZW                     | 37        | 0.53%   |
| ASRockRack              | 34        | 0.49%   |
| HUAWEI                  | 28        | 0.4%    |
| Foxconn                 | 28        | 0.4%    |
| Sony                    | 20        | 0.29%   |
| Packard Bell            | 19        | 0.27%   |
| Notebook                | 19        | 0.27%   |
| Pegatron                | 18        | 0.26%   |
| Medion                  | 16        | 0.23%   |
| AMI                     | 15        | 0.21%   |
| BESSTAR Tech            | 14        | 0.2%    |
| Microsoft               | 13        | 0.19%   |
| Inventec                | 13        | 0.19%   |
| Hardkernel              | 13        | 0.19%   |
| Biostar                 | 13        | 0.19%   |
| Rockchip                | 12        | 0.17%   |
| IBM                     | 12        | 0.17%   |
| sunxi                   | 11        | 0.16%   |
| Positivo                | 11        | 0.16%   |
| Panasonic               | 10        | 0.14%   |
| Clevo                   | 10        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 353       | 5.06%   |
| Unknown                                   | 125       | 1.79%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 1.63%   |
| ASUS All Series                           | 83        | 1.19%   |
| Apple MacBookAir7,2                       | 77        | 1.1%    |
| Apple MacBookAir7,1                       | 77        | 1.1%    |
| Google Enguarde                           | 74        | 1.06%   |
| ASUS S20 K29                              | 55        | 0.79%   |
| Apple MacBook2,1                          | 55        | 0.79%   |
| Aquarius NS585                            | 44        | 0.63%   |
| MSI MS-7996                               | 39        | 0.56%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 32        | 0.46%   |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.34%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 23        | 0.33%   |
| Google Terra                              | 23        | 0.33%   |
| MSI MS-7817                               | 22        | 0.32%   |
| ECS G31T-M9                               | 22        | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 21        | 0.3%    |
| Apple MacBook4,1                          | 21        | 0.3%    |
| RPi Raspberry Pi 4 Model B Rev 1.5        | 20        | 0.29%   |
| ASRock H470M-HVS                          | 20        | 0.29%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 19        | 0.27%   |
| Supermicro Super Server                   | 18        | 0.26%   |
| HP Notebook                               | 18        | 0.26%   |
| Gigabyte H81M-S2V                         | 18        | 0.26%   |
| ASUS PRIME H510M-A                        | 17        | 0.24%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.23%   |
| Gigabyte H410M S2H                        | 16        | 0.23%   |
| ECS H61H2-M13                             | 16        | 0.23%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.21%   |
| Acer Aspire A315-23                       | 15        | 0.21%   |
| ASUS 1005HA                               | 14        | 0.2%    |
| RPi Raspberry Pi                          | 13        | 0.19%   |
| HP Pavilion g6                            | 13        | 0.19%   |
| Google Reks                               | 13        | 0.19%   |
| Dell OptiPlex 7010                        | 13        | 0.19%   |
| AZW U59                                   | 12        | 0.17%   |
| AZW MINI S                                | 12        | 0.17%   |
| RPi Raspberry Pi 400 Rev 1.0              | 11        | 0.16%   |
| Gigabyte B450M DS3H                       | 11        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 599       | 8.58%   |
| Apple MacBook5     | 353       | 5.06%   |
| Dell Latitude      | 191       | 2.74%   |
| RPi Raspberry      | 166       | 2.38%   |
| Acer Aspire        | 163       | 2.33%   |
| Apple MacBookAir7  | 154       | 2.21%   |
| ASUS PRIME         | 147       | 2.11%   |
| Dell Inspiron      | 145       | 2.08%   |
| Unknown            | 125       | 1.79%   |
| Lenovo IdeaPad     | 118       | 1.69%   |
| HP EliteBook       | 110       | 1.58%   |
| Dell OptiPlex      | 101       | 1.45%   |
| HP Pavilion        | 94        | 1.35%   |
| ASUS All           | 83        | 1.19%   |
| HP Compaq          | 82        | 1.17%   |
| Dell Precision     | 80        | 1.15%   |
| HP Laptop          | 76        | 1.09%   |
| Google Enguarde    | 74        | 1.06%   |
| Lenovo ThinkCentre | 66        | 0.95%   |
| HP ProBook         | 62        | 0.89%   |
| ASUS ROG           | 62        | 0.89%   |
| ASUS S20           | 55        | 0.79%   |
| Apple MacBook2     | 55        | 0.79%   |
| Dell XPS           | 53        | 0.76%   |
| ASUS TUF           | 51        | 0.73%   |
| Toshiba Satellite  | 44        | 0.63%   |
| Dell PowerEdge     | 44        | 0.63%   |
| Aquarius NS585     | 44        | 0.63%   |
| HP ProLiant        | 43        | 0.62%   |
| ASUS VivoBook      | 43        | 0.62%   |
| Dell Vostro        | 40        | 0.57%   |
| MSI MS-7996        | 39        | 0.56%   |
| ASUS P8H61-M       | 32        | 0.46%   |
| HP ENVY            | 27        | 0.39%   |
| HP EliteDesk       | 27        | 0.39%   |
| ASUS ASUS          | 26        | 0.37%   |
| Gigabyte B450M     | 25        | 0.36%   |
| HP ZBook           | 24        | 0.34%   |
| Google Terra       | 23        | 0.33%   |
| ASUS ZenBook       | 23        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 777       | 11.13%  |
| 2021    | 644       | 9.22%   |
| 2009    | 575       | 8.24%   |
| 2019    | 518       | 7.42%   |
| 2012    | 491       | 7.03%   |
| 2018    | 470       | 6.73%   |
| 2013    | 402       | 5.76%   |
| 2011    | 365       | 5.23%   |
| 2015    | 361       | 5.17%   |
| 2017    | 356       | 5.1%    |
| 2022    | 319       | 4.57%   |
| 2014    | 317       | 4.54%   |
| 2016    | 274       | 3.92%   |
| 2007    | 252       | 3.61%   |
| Unknown | 244       | 3.49%   |
| 2010    | 243       | 3.48%   |
| 2008    | 212       | 3.04%   |
| 2006    | 55        | 0.79%   |
| 2005    | 38        | 0.54%   |
| 2023    | 36        | 0.52%   |
| 2003    | 15        | 0.21%   |
| 2004    | 11        | 0.16%   |
| 2001    | 3         | 0.04%   |
| 2024    | 2         | 0.03%   |
| 2002    | 1         | 0.01%   |
| 2000    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3489      | 49.97%  |
| Desktop        | 2600      | 37.24%  |
| System on chip | 256       | 3.67%   |
| Convertible    | 204       | 2.92%   |
| Mini pc        | 175       | 2.51%   |
| Server         | 158       | 2.26%   |
| All in one     | 60        | 0.86%   |
| Tablet         | 34        | 0.49%   |
| Phone          | 4         | 0.06%   |
| Other          | 1         | 0.01%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6625      | 94.45%  |
| Enabled  | 389       | 5.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6828      | 97.78%  |
| Yes  | 155       | 2.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1601      | 22.72%  |
| 16.01-24.0      | 1262      | 17.91%  |
| 3.01-4.0        | 1250      | 17.74%  |
| 8.01-16.0       | 884       | 12.54%  |
| 1.01-2.0        | 676       | 9.59%   |
| 32.01-64.0      | 591       | 8.39%   |
| 64.01-256.0     | 348       | 4.94%   |
| 2.01-3.0        | 136       | 1.93%   |
| 0.51-1.0        | 135       | 1.92%   |
| 24.01-32.0      | 101       | 1.43%   |
| 0.01-0.5        | 32        | 0.45%   |
| More than 256.0 | 30        | 0.43%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2469      | 33.46%  |
| 0.51-1.0        | 1284      | 17.4%   |
| 2.01-3.0        | 1229      | 16.66%  |
| 4.01-8.0        | 828       | 11.22%  |
| 3.01-4.0        | 662       | 8.97%   |
| 0.01-0.5        | 382       | 5.18%   |
| 8.01-16.0       | 294       | 3.98%   |
| 16.01-24.0      | 91        | 1.23%   |
| 32.01-64.0      | 68        | 0.92%   |
| 24.01-32.0      | 38        | 0.51%   |
| 64.01-256.0     | 30        | 0.41%   |
| More than 256.0 | 2         | 0.03%   |
| Unknown         | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4728      | 66.48%  |
| 2      | 1308      | 18.39%  |
| 3      | 422       | 5.93%   |
| 4      | 248       | 3.49%   |
| 5      | 118       | 1.66%   |
| 6      | 72        | 1.01%   |
| 0      | 59        | 0.83%   |
| 7      | 45        | 0.63%   |
| 8      | 40        | 0.56%   |
| 9      | 17        | 0.24%   |
| 10     | 13        | 0.18%   |
| 13     | 10        | 0.14%   |
| 12     | 7         | 0.1%    |
| 11     | 5         | 0.07%   |
| 14     | 4         | 0.06%   |
| 28     | 2         | 0.03%   |
| 19     | 2         | 0.03%   |
| 18     | 2         | 0.03%   |
| 16     | 2         | 0.03%   |
| 79     | 1         | 0.01%   |
| 47     | 1         | 0.01%   |
| 29     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |
| 21     | 1         | 0.01%   |
| 15     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4787      | 68.34%  |
| Yes       | 2218      | 31.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6025      | 86.17%  |
| No        | 967       | 13.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4678      | 66.85%  |
| No        | 2320      | 33.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3863      | 55.08%  |
| No        | 3150      | 44.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1780      | 25.44%  |
| Russia       | 1050      | 15%     |
| Germany      | 664       | 9.49%   |
| France       | 451       | 6.44%   |
| Spain        | 265       | 3.79%   |
| Italy        | 228       | 3.26%   |
| Brazil       | 215       | 3.07%   |
| UK           | 183       | 2.62%   |
| Poland       | 173       | 2.47%   |
| Canada       | 144       | 2.06%   |
| Australia    | 114       | 1.63%   |
| Netherlands  | 112       | 1.6%    |
| Switzerland  | 100       | 1.43%   |
| Mexico       | 83        | 1.19%   |
| China        | 82        | 1.17%   |
| Argentina    | 77        | 1.1%    |
| Sweden       | 57        | 0.81%   |
| Belgium      | 54        | 0.77%   |
| Austria      | 53        | 0.76%   |
| Hungary      | 51        | 0.73%   |
| Ukraine      | 50        | 0.71%   |
| India        | 50        | 0.71%   |
| Finland      | 46        | 0.66%   |
| Czechia      | 43        | 0.61%   |
| Portugal     | 41        | 0.59%   |
| Norway       | 41        | 0.59%   |
| Turkey       | 40        | 0.57%   |
| Venezuela    | 37        | 0.53%   |
| Bulgaria     | 36        | 0.51%   |
| Japan        | 35        | 0.5%    |
| Romania      | 30        | 0.43%   |
| Ireland      | 28        | 0.4%    |
| Greece       | 27        | 0.39%   |
| Taiwan       | 24        | 0.34%   |
| New Zealand  | 24        | 0.34%   |
| Denmark      | 24        | 0.34%   |
| Malaysia     | 23        | 0.33%   |
| Colombia     | 23        | 0.33%   |
| Croatia      | 22        | 0.31%   |
| South Africa | 19        | 0.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Bangor            | 758       | 10.38%  |
| Voronezh          | 715       | 9.79%   |
| Dover-Foxcroft    | 304       | 4.16%   |
| Moscow            | 82        | 1.12%   |
| Paris             | 69        | 0.94%   |
| St Petersburg     | 64        | 0.88%   |
| Seville           | 53        | 0.73%   |
| Berlin            | 46        | 0.63%   |
| Warsaw            | 41        | 0.56%   |
| Madrid            | 40        | 0.55%   |
| Vienna            | 38        | 0.52%   |
| Munich            | 35        | 0.48%   |
| Barcelona         | 33        | 0.45%   |
| Milan             | 32        | 0.44%   |
| Zurich            | 30        | 0.41%   |
| Amsterdam         | 30        | 0.41%   |
| Sao Paulo         | 29        | 0.4%    |
| Falkenstein       | 25        | 0.34%   |
| Toronto           | 24        | 0.33%   |
| Sydney            | 24        | 0.33%   |
| Frankfurt am Main | 24        | 0.33%   |
| Hamburg           | 23        | 0.31%   |
| Brisbane          | 23        | 0.31%   |
| Perm              | 22        | 0.3%    |
| Melbourne         | 22        | 0.3%    |
| London            | 20        | 0.27%   |
| Helsinki          | 20        | 0.27%   |
| Istanbul          | 19        | 0.26%   |
| Buenos Aires      | 19        | 0.26%   |
| Stuttgart         | 18        | 0.25%   |
| Dublin            | 18        | 0.25%   |
| Prague            | 17        | 0.23%   |
| Leipzig           | 17        | 0.23%   |
| Kuala Lumpur      | 17        | 0.23%   |
| Cologne           | 17        | 0.23%   |
| San Jose          | 16        | 0.22%   |
| Chicago           | 16        | 0.22%   |
| Athens            | 16        | 0.22%   |
| Sofia             | 15        | 0.21%   |
| Rome              | 15        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1431      | 2114   | 14.76%  |
| WDC                 | 1267      | 2074   | 13.07%  |
| Seagate             | 1207      | 2252   | 12.45%  |
| Toshiba             | 672       | 976    | 6.93%   |
| Kingston            | 584       | 762    | 6.03%   |
| Unknown             | 567       | 735    | 5.85%   |
| Crucial             | 437       | 539    | 4.51%   |
| SanDisk             | 379       | 474    | 3.91%   |
| Fujitsu             | 285       | 297    | 2.94%   |
| Hitachi             | 280       | 377    | 2.89%   |
| Intel               | 222       | 315    | 2.29%   |
| Apple               | 199       | 239    | 2.05%   |
| SK hynix            | 192       | 241    | 1.98%   |
| A-DATA Technology   | 170       | 284    | 1.75%   |
| HGST                | 160       | 290    | 1.65%   |
| Micron Technology   | 132       | 159    | 1.36%   |
| China               | 115       | 132    | 1.19%   |
| Unknown             | 83        | 90     | 0.86%   |
| KIOXIA              | 68        | 74     | 0.7%    |
| PNY                 | 64        | 121    | 0.66%   |
| SPCC                | 61        | 72     | 0.63%   |
| Transcend           | 51        | 58     | 0.53%   |
| Phison              | 45        | 56     | 0.46%   |
| Intenso             | 41        | 53     | 0.42%   |
| Hewlett-Packard     | 41        | 94     | 0.42%   |
| JMicron Technology  | 37        | 41     | 0.38%   |
| Corsair             | 37        | 58     | 0.38%   |
| Netac               | 36        | 96     | 0.37%   |
| LITEON              | 36        | 43     | 0.37%   |
| Patriot             | 35        | 42     | 0.36%   |
| SABRENT             | 30        | 31     | 0.31%   |
| GOODRAM             | 29        | 46     | 0.3%    |
| OCZ                 | 27        | 32     | 0.28%   |
| Silicon Motion      | 26        | 32     | 0.27%   |
| Team                | 24        | 48     | 0.25%   |
| Maxtor              | 24        | 29     | 0.25%   |
| Gigabyte Technology | 22        | 24     | 0.23%   |
| Apacer              | 21        | 21     | 0.22%   |
| LITEONIT            | 20        | 27     | 0.21%   |
| ASMT                | 20        | 28     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 237       | 2.22%   |
| Kingston SA400S37240G 240GB SSD    | 136       | 1.27%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 122       | 1.14%   |
| Seagate ST500DM002-1BD142 500GB    | 84        | 0.79%   |
| Unknown                            | 83        | 0.78%   |
| Crucial CT480BX500SSD1 480GB       | 78        | 0.73%   |
| Apple SSD AP0128H 121GB            | 77        | 0.72%   |
| Apple SSD SM0128G 121GB            | 72        | 0.67%   |
| Kingston SV300S37A120G 120GB SSD   | 67        | 0.63%   |
| Kingston SA400S37120G 120GB SSD    | 66        | 0.62%   |
| Toshiba DT01ACA050 500GB           | 64        | 0.6%    |
| Samsung SSD 860 EVO 500GB          | 64        | 0.6%    |
| Kingston SA400S37480G 480GB SSD    | 64        | 0.6%    |
| Samsung SSD 860 EVO 250GB          | 60        | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB       | 59        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB     | 58        | 0.54%   |
| Crucial CT500MX500SSD1 500GB       | 58        | 0.54%   |
| Toshiba MK1655GSXF 160GB           | 53        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB        | 53        | 0.5%    |
| Unknown MMC Card  32GB             | 50        | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB     | 50        | 0.47%   |
| A-DATA SU800 512GB SSD             | 48        | 0.45%   |
| Samsung SSD 850 EVO 250GB          | 46        | 0.43%   |
| Samsung SSD 860 EVO 1TB            | 44        | 0.41%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.4%    |
| Samsung SSD 850 EVO 500GB          | 43        | 0.4%    |
| Crucial CT240BX500SSD1 240GB       | 42        | 0.39%   |
| Unknown AGND3R  16GB               | 40        | 0.37%   |
| Toshiba DT01ACA100 1TB             | 40        | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB     | 40        | 0.37%   |
| Samsung SSD 870 EVO 500GB          | 40        | 0.37%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 37        | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 37        | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB     | 36        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB     | 36        | 0.34%   |
| Samsung SSD 980 1TB                | 34        | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB           | 33        | 0.31%   |
| Toshiba MQ04ABF100 1TB             | 32        | 0.3%    |
| Hitachi HDS721050CLA362 500GB      | 32        | 0.3%    |
| Toshiba MQ01ABF050 500GB           | 31        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1173      | 2179   | 31.63%  |
| WDC                 | 951       | 1620   | 25.64%  |
| Toshiba             | 566       | 843    | 15.26%  |
| Fujitsu             | 285       | 297    | 7.68%   |
| Hitachi             | 280       | 377    | 7.55%   |
| HGST                | 159       | 288    | 4.29%   |
| Samsung Electronics | 94        | 114    | 2.53%   |
| SABRENT             | 30        | 31     | 0.81%   |
| Unknown             | 29        | 38     | 0.78%   |
| JMicron Technology  | 23        | 27     | 0.62%   |
| Maxtor              | 22        | 24     | 0.59%   |
| Hewlett-Packard     | 21        | 64     | 0.57%   |
| Apple               | 15        | 18     | 0.4%    |
| Intenso             | 5         | 5      | 0.13%   |
| TO Exter            | 4         | 4      | 0.11%   |
| ASMT                | 4         | 8      | 0.11%   |
| ASMedia             | 4         | 4      | 0.11%   |
| QNAP                | 3         | 4      | 0.08%   |
| IBM-ESXS            | 3         | 5      | 0.08%   |
| HPE                 | 3         | 10     | 0.08%   |
| USB3.0              | 2         | 2      | 0.05%   |
| Unknown (CF)        | 2         | 2      | 0.05%   |
| LaCie               | 2         | 2      | 0.05%   |
| IBM/Hitachi         | 2         | 2      | 0.05%   |
| Unknown             | 2         | 2      | 0.05%   |
| WD MediaMax         | 1         | 6      | 0.03%   |
| USB                 | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| Space ke            | 1         | 1      | 0.03%   |
| SILICONMOTION       | 1         | 1      | 0.03%   |
| SD                  | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| pqi                 | 1         | 1      | 0.03%   |
| Pear 2TB            | 1         | 1      | 0.03%   |
| NAS                 | 1         | 5      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 4      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 670       | 913    | 20.63%  |
| Kingston            | 497       | 644    | 15.31%  |
| Crucial             | 380       | 463    | 11.7%   |
| SanDisk             | 249       | 314    | 7.67%   |
| WDC                 | 141       | 168    | 4.34%   |
| A-DATA Technology   | 123       | 206    | 3.79%   |
| China               | 113       | 130    | 3.48%   |
| Intel               | 98        | 146    | 3.02%   |
| Apple               | 98        | 108    | 3.02%   |
| Micron Technology   | 57        | 78     | 1.76%   |
| SPCC                | 50        | 58     | 1.54%   |
| PNY                 | 50        | 104    | 1.54%   |
| Transcend           | 46        | 53     | 1.42%   |
| Toshiba             | 41        | 50     | 1.26%   |
| SK hynix            | 39        | 49     | 1.2%    |
| Netac               | 35        | 95     | 1.08%   |
| Intenso             | 33        | 43     | 1.02%   |
| Patriot             | 29        | 32     | 0.89%   |
| LITEON              | 29        | 34     | 0.89%   |
| OCZ                 | 27        | 32     | 0.83%   |
| GOODRAM             | 23        | 31     | 0.71%   |
| Team                | 21        | 42     | 0.65%   |
| LITEONIT            | 20        | 27     | 0.62%   |
| Apacer              | 19        | 19     | 0.59%   |
| Unknown             | 17        | 19     | 0.52%   |
| ASMT                | 15        | 19     | 0.46%   |
| Corsair             | 14        | 18     | 0.43%   |
| Seagate             | 13        | 16     | 0.4%    |
| Hewlett-Packard     | 12        | 18     | 0.37%   |
| Gigabyte Technology | 12        | 12     | 0.37%   |
| Plextor             | 9         | 12     | 0.28%   |
| KingDian            | 9         | 9      | 0.28%   |
| Lexar               | 8         | 10     | 0.25%   |
| Unknown             | 7         | 10     | 0.22%   |
| Mushkin             | 7         | 8      | 0.22%   |
| KIOXIA-EXCERIA      | 7         | 10     | 0.22%   |
| Hajaan              | 7         | 8      | 0.22%   |
| NGFF                | 6         | 6      | 0.18%   |
| LDLC                | 6         | 6      | 0.18%   |
| Innodisk            | 6         | 6      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3167      | 6012   | 36.01%  |
| SSD     | 2864      | 4268   | 32.56%  |
| NVMe    | 2063      | 2924   | 23.46%  |
| MMC     | 594       | 735    | 6.75%   |
| Unknown | 107       | 175    | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4954      | 9648   | 61.87%  |
| NVMe | 2056      | 2910   | 25.68%  |
| MMC  | 594       | 735    | 7.42%   |
| SAS  | 403       | 821    | 5.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 3906      | 5541   | 60.99%  |
| 0.51-1.0    | 1459      | 2298   | 22.78%  |
| 1.01-2.0    | 465       | 872    | 7.26%   |
| 3.01-4.0    | 228       | 600    | 3.56%   |
| 4.01-10.0   | 181       | 495    | 2.83%   |
| 2.01-3.0    | 104       | 225    | 1.62%   |
| 10.01-20.0  | 58        | 243    | 0.91%   |
| 20.01-50.0  | 1         | 1      | 0.02%   |
| 50.01-100.0 | 1         | 4      | 0.02%   |
| 0           | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1555      | 21.7%   |
| Unknown        | 1512      | 21.1%   |
| 251-500        | 1203      | 16.79%  |
| 501-1000       | 804       | 11.22%  |
| 51-100         | 453       | 6.32%   |
| 1-20           | 402       | 5.61%   |
| 1001-2000      | 392       | 5.47%   |
| More than 3000 | 369       | 5.15%   |
| 21-50          | 317       | 4.42%   |
| 2001-3000      | 158       | 2.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2665      | 36.42%  |
| Unknown        | 1512      | 20.66%  |
| 21-50          | 700       | 9.57%   |
| 101-250        | 673       | 9.2%    |
| 51-100         | 577       | 7.89%   |
| 251-500        | 425       | 5.81%   |
| 501-1000       | 324       | 4.43%   |
| 1001-2000      | 185       | 2.53%   |
| More than 3000 | 153       | 2.09%   |
| 2001-3000      | 81        | 1.11%   |
| 0              | 22        | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 25        | 25     | 2.39%   |
| Seagate ST500DM002-1BD142 500GB      | 22        | 37     | 2.1%    |
| WDC WD5000AAKX-60U6AA0 500GB         | 21        | 25     | 2.01%   |
| Kingston SV300S37A120G 120GB SSD     | 21        | 21     | 2.01%   |
| Seagate ST9500325AS 500GB            | 11        | 13     | 1.05%   |
| Hitachi HTS543216L9SA02 160GB        | 11        | 11     | 1.05%   |
| Toshiba MK1655GSXF 160GB             | 9         | 9      | 0.86%   |
| Toshiba MK1653GSX 160GB              | 9         | 9      | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 10     | 0.86%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 8         | 8      | 0.76%   |
| Hitachi HDS721050CLA362 500GB        | 8         | 8      | 0.76%   |
| Toshiba DT01ACA050 500GB             | 7         | 8      | 0.67%   |
| Seagate ST9500420AS 500GB            | 7         | 8      | 0.67%   |
| Seagate ST3500418AS 500GB            | 7         | 9      | 0.67%   |
| Seagate ST3250318AS 250GB            | 7         | 7      | 0.67%   |
| Seagate ST250DM000-1BD141 250GB      | 7         | 7      | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB       | 7         | 8      | 0.67%   |
| HGST HTS541010A9E680 1TB             | 7         | 7      | 0.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.57%   |
| Seagate ST31000528AS 1TB             | 6         | 7      | 0.57%   |
| Hitachi HDS721050DLE630 500GB        | 6         | 11     | 0.57%   |
| WDC WD20EARX-00PASB0 2TB             | 5         | 5      | 0.48%   |
| WDC WD20EARS-00MVWB0 2TB             | 5         | 5      | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB             | 5         | 5      | 0.48%   |
| Toshiba MQ01ABF050 500GB             | 5         | 5      | 0.48%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 5      | 0.48%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 5      | 0.48%   |
| Seagate ST3320613AS 320GB            | 5         | 5      | 0.48%   |
| Seagate ST31500341AS 1TB             | 5         | 7      | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 7      | 0.48%   |
| Hitachi HTS542512K9SA00 120GB        | 5         | 6      | 0.48%   |
| HGST HTS725050A7E630 500GB           | 5         | 6      | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 4      | 0.38%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 4         | 5      | 0.38%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 4         | 4      | 0.38%   |
| Toshiba MQ01ABD100 1TB               | 4         | 5      | 0.38%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.38%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.38%   |
| Seagate ST3500413AS 500GB            | 4         | 5      | 0.38%   |
| Seagate ST2000DL003-9VT166 2TB       | 4         | 4      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 266       | 359    | 26.23%  |
| WDC                 | 211       | 269    | 20.81%  |
| Hitachi             | 104       | 126    | 10.26%  |
| Toshiba             | 83        | 91     | 8.19%   |
| Samsung Electronics | 58        | 63     | 5.72%   |
| Kingston            | 47        | 52     | 4.64%   |
| Intel               | 37        | 45     | 3.65%   |
| Fujitsu             | 35        | 38     | 3.45%   |
| HGST                | 27        | 31     | 2.66%   |
| SK hynix            | 21        | 25     | 2.07%   |
| SanDisk             | 17        | 18     | 1.68%   |
| Crucial             | 16        | 21     | 1.58%   |
| A-DATA Technology   | 15        | 18     | 1.48%   |
| Micron Technology   | 14        | 20     | 1.38%   |
| Maxtor              | 10        | 10     | 0.99%   |
| LITEONIT            | 4         | 5      | 0.39%   |
| LITEON              | 4         | 4      | 0.39%   |
| China               | 4         | 4      | 0.39%   |
| Transcend           | 3         | 3      | 0.3%    |
| Hewlett-Packard     | 3         | 5      | 0.3%    |
| Apple               | 3         | 4      | 0.3%    |
| SPCC                | 2         | 2      | 0.2%    |
| ShiJi               | 2         | 2      | 0.2%    |
| PNY                 | 2         | 7      | 0.2%    |
| OCZ                 | 2         | 2      | 0.2%    |
| JMicron Technology  | 2         | 3      | 0.2%    |
| Corsair             | 2         | 2      | 0.2%    |
| Apacer              | 2         | 2      | 0.2%    |
| Unknown             | 2         | 2      | 0.2%    |
| Western Digital     | 1         | 2      | 0.1%    |
| USB3.0              | 1         | 1      | 0.1%    |
| Plextor             | 1         | 1      | 0.1%    |
| Patriot             | 1         | 1      | 0.1%    |
| Netac               | 1         | 1      | 0.1%    |
| Lenovo              | 1         | 1      | 0.1%    |
| KingSpec            | 1         | 1      | 0.1%    |
| KingDian            | 1         | 1      | 0.1%    |
| Intenso             | 1         | 1      | 0.1%    |
| IBM/Hitachi         | 1         | 1      | 0.1%    |
| IBM                 | 1         | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 266       | 359    | 34.77%  |
| WDC                 | 203       | 260    | 26.54%  |
| Hitachi             | 104       | 126    | 13.59%  |
| Toshiba             | 80        | 88     | 10.46%  |
| Fujitsu             | 35        | 38     | 4.58%   |
| Samsung Electronics | 28        | 28     | 3.66%   |
| HGST                | 27        | 31     | 3.53%   |
| Maxtor              | 10        | 10     | 1.31%   |
| Hewlett-Packard     | 3         | 5      | 0.39%   |
| Apple               | 3         | 4      | 0.39%   |
| JMicron Technology  | 2         | 3      | 0.26%   |
| USB3.0              | 1         | 1      | 0.13%   |
| IBM/Hitachi         | 1         | 1      | 0.13%   |
| IBM                 | 1         | 1      | 0.13%   |
| ASMedia             | 1         | 1      | 0.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 727       | 956    | 74.79%  |
| SSD  | 204       | 242    | 20.99%  |
| NVMe | 41        | 52     | 4.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 3.57%   |
| WDC WD4001FFSX-68JNUN0 4TB                      | 1         | 1      | 3.57%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 3.57%   |
| Toshiba MK3276GSXN 320GB                        | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 3.57%   |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 3.57%   |
| Seagate ST500DM005 HD502HJ 500GB                | 1         | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB                 | 1         | 2      | 3.57%   |
| Seagate ST3500830AS 500GB                       | 1         | 1      | 3.57%   |
| Seagate ST3500630A 500GB                        | 1         | 1      | 3.57%   |
| Seagate ST2000NM0011 2TB                        | 1         | 1      | 3.57%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB     | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 980 250GB               | 1         | 1      | 3.57%   |
| Samsung Electronics SSD 980 1TB                 | 1         | 1      | 3.57%   |
| Samsung Electronics SP0802N 80GB                | 1         | 1      | 3.57%   |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 3.57%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 3.57%   |
| Samsung Electronics HD253GJ 250GB               | 1         | 1      | 3.57%   |
| Samsung Electronics HD103SJ 1TB                 | 1         | 1      | 3.57%   |
| KingDian S400 120GB SSD                         | 1         | 1      | 3.57%   |
| Intel SSDSC2KW256G8 256GB                       | 1         | 1      | 3.57%   |
| Inland SATA SSD 128GB                           | 1         | 1      | 3.57%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 3.57%   |
| HGST HUH728080ALN600 8TB                        | 1         | 1      | 3.57%   |
| HGST HTS725050A7E630 500GB                      | 1         | 2      | 3.57%   |
| HGST HDN724040ALE640 4TB                        | 1         | 1      | 3.57%   |
| Hewlett-Packard SSD S700 500GB                  | 1         | 2      | 3.57%   |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 3.57%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 28.57%  |
| Seagate             | 7         | 8      | 25%     |
| HGST                | 3         | 4      | 10.71%  |
| WDC                 | 2         | 2      | 7.14%   |
| Toshiba             | 2         | 2      | 7.14%   |
| KingDian            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Inland              | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 2      | 3.57%   |
| Hewlett-Packard     | 1         | 2      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 5005      | 9411   | 64.79%  |
| Detected | 1743      | 3419   | 22.56%  |
| Malfunc  | 947       | 1250   | 12.26%  |
| Failed   | 28        | 32     | 0.36%   |
| Limited  | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4165      | 49.83%  |
| AMD                              | 1076      | 12.87%  |
| Samsung Electronics              | 838       | 10.03%  |
| Nvidia                           | 436       | 5.22%   |
| SanDisk                          | 331       | 3.96%   |
| SK hynix                         | 147       | 1.76%   |
| ASMedia Technology               | 140       | 1.68%   |
| Phison Electronics               | 118       | 1.41%   |
| Kingston Technology Company      | 106       | 1.27%   |
| Apple                            | 86        | 1.03%   |
| Marvell Technology Group         | 85        | 1.02%   |
| Toshiba America Info Systems     | 78        | 0.93%   |
| Micron/Crucial Technology        | 76        | 0.91%   |
| Micron Technology                | 76        | 0.91%   |
| JMicron Technology               | 75        | 0.9%    |
| LSI Logic / Symbios Logic        | 72        | 0.86%   |
| KIOXIA                           | 67        | 0.8%    |
| Broadcom / LSI                   | 60        | 0.72%   |
| ADATA Technology                 | 58        | 0.69%   |
| Silicon Motion                   | 54        | 0.65%   |
| VIA Technologies                 | 33        | 0.39%   |
| Hewlett-Packard                  | 22        | 0.26%   |
| Solid State Storage Technology   | 18        | 0.22%   |
| Adaptec                          | 18        | 0.22%   |
| MAXIO Technology (Hangzhou)      | 16        | 0.19%   |
| Realtek Semiconductor            | 15        | 0.18%   |
| Union Memory (Shenzhen)          | 10        | 0.12%   |
| Silicon Integrated Systems [SiS] | 9         | 0.11%   |
| Silicon Image                    | 9         | 0.11%   |
| Lite-On Technology               | 9         | 0.11%   |
| Seagate Technology               | 8         | 0.1%    |
| Shenzhen Longsys Electronics     | 7         | 0.08%   |
| INNOGRIT                         | 5         | 0.06%   |
| Lenovo                           | 4         | 0.05%   |
| Yangtze Memory Technologies      | 3         | 0.04%   |
| ULi Electronics                  | 3         | 0.04%   |
| Jiangsu Huacun Elec.             | 3         | 0.04%   |
| Biwin Storage Technology         | 3         | 0.04%   |
| 3ware                            | 3         | 0.04%   |
| Swissbit                         | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 715       | 7.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 434       | 4.53%   |
| Nvidia MCP79 AHCI Controller                                                            | 369       | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 311       | 3.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 272       | 2.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 229       | 2.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 185       | 1.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 166       | 1.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 164       | 1.71%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 159       | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 156       | 1.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 152       | 1.59%   |
| AMD 400 Series Chipset SATA Controller                                                  | 150       | 1.57%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 141       | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 141       | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 131       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 127       | 1.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 120       | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 119       | 1.24%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 111       | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 108       | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 106       | 1.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 101       | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 98        | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 91        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 90        | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 86        | 0.9%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 85        | 0.89%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 84        | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 84        | 0.88%   |
| Intel SATA Controller [RAID mode]                                                       | 84        | 0.88%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 82        | 0.86%   |
| Apple S1X NVMe Controller                                                               | 79        | 0.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 78        | 0.81%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 72        | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 72        | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 70        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 67        | 0.7%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 66        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 64        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4868      | 57.25%  |
| NVMe | 2055      | 24.17%  |
| IDE  | 938       | 11.03%  |
| RAID | 516       | 6.07%   |
| SAS  | 103       | 1.21%   |
| SCSI | 23        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5402      | 77.36%  |
| AMD                   | 1298      | 18.59%  |
| ARM                   | 261       | 3.74%   |
| CentaurHauls          | 8         | 0.11%   |
| sifive,u74-mc         | 4         | 0.06%   |
| Phytium               | 4         | 0.06%   |
| Unknown               | 3         | 0.04%   |
| Qualcomm              | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| HISILICON             | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 355       | 5.08%   |
| ARM Processor                                 | 222       | 3.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 183       | 2.62%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 149       | 2.13%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 92        | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 82        | 1.17%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 63        | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 61        | 0.87%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 0.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 51        | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 51        | 0.73%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 47        | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 45        | 0.64%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 45        | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 42        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 0.57%   |
| AMD Ryzen 5 3600 6-Core Processor             | 38        | 0.54%   |
| Intel Celeron N5105 @ 2.00GHz                 | 36        | 0.51%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 36        | 0.51%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 35        | 0.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 35        | 0.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 34        | 0.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 33        | 0.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 32        | 0.46%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 31        | 0.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 31        | 0.44%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 31        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 30        | 0.43%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 30        | 0.43%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 28        | 0.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.4%    |
| Intel Core i5-10400 CPU @ 2.90GHz             | 28        | 0.4%    |
| Intel Core i7-10700 CPU @ 2.90GHz             | 27        | 0.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 0.39%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 27        | 0.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 26        | 0.37%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.37%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 26        | 0.37%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 26        | 0.37%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 25        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1361      | 19.48%  |
| Intel Core i7           | 832       | 11.91%  |
| Other                   | 805       | 11.52%  |
| Intel Core 2 Duo        | 598       | 8.56%   |
| Intel Celeron           | 508       | 7.27%   |
| Intel Core i3           | 500       | 7.16%   |
| AMD Ryzen 5             | 319       | 4.57%   |
| Intel Xeon              | 277       | 3.97%   |
| Intel Pentium           | 239       | 3.42%   |
| AMD Ryzen 7             | 220       | 3.15%   |
| Intel Atom              | 141       | 2.02%   |
| AMD Ryzen 9             | 109       | 1.56%   |
| Intel Core 2            | 83        | 1.19%   |
| Intel Pentium Dual-Core | 77        | 1.1%    |
| AMD FX                  | 75        | 1.07%   |
| AMD Ryzen 3             | 54        | 0.77%   |
| Intel Core 2 Quad       | 40        | 0.57%   |
| AMD A6                  | 40        | 0.57%   |
| AMD Ryzen 7 PRO         | 33        | 0.47%   |
| Intel Core i9           | 32        | 0.46%   |
| AMD A10                 | 32        | 0.46%   |
| AMD Ryzen 5 PRO         | 26        | 0.37%   |
| Intel Pentium Silver    | 25        | 0.36%   |
| Intel Genuine           | 25        | 0.36%   |
| AMD Ryzen Threadripper  | 25        | 0.36%   |
| AMD Athlon              | 25        | 0.36%   |
| AMD A4                  | 25        | 0.36%   |
| Intel Pentium Gold      | 23        | 0.33%   |
| Intel Pentium M         | 22        | 0.31%   |
| Intel Pentium 4         | 22        | 0.31%   |
| AMD A8                  | 22        | 0.31%   |
| Intel Pentium Dual      | 20        | 0.29%   |
| AMD Athlon II X2        | 19        | 0.27%   |
| ARM Allwinner           | 18        | 0.26%   |
| AMD Athlon 64 X2        | 18        | 0.26%   |
| AMD Phenom II X4        | 17        | 0.24%   |
| AMD GX                  | 17        | 0.24%   |
| AMD E                   | 15        | 0.21%   |
| Intel Celeron M         | 13        | 0.19%   |
| AMD Opteron             | 12        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2947      | 42.15%  |
| 4       | 2367      | 33.85%  |
| 6       | 604       | 8.64%   |
| 8       | 460       | 6.58%   |
| 1       | 228       | 3.26%   |
| 12      | 104       | 1.49%   |
| 16      | 99        | 1.42%   |
| 10      | 45        | 0.64%   |
| 3       | 29        | 0.41%   |
| Unknown | 23        | 0.33%   |
| 24      | 19        | 0.27%   |
| 14      | 19        | 0.27%   |
| 32      | 17        | 0.24%   |
| 20      | 7         | 0.1%    |
| 28      | 5         | 0.07%   |
| 48      | 4         | 0.06%   |
| 18      | 4         | 0.06%   |
| 44      | 2         | 0.03%   |
| 36      | 2         | 0.03%   |
| 192     | 1         | 0.01%   |
| 128     | 1         | 0.01%   |
| 96      | 1         | 0.01%   |
| 80      | 1         | 0.01%   |
| 64      | 1         | 0.01%   |
| 56      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6811      | 97.49%  |
| 2       | 141       | 2.02%   |
| Unknown | 23        | 0.33%   |
| 3       | 6         | 0.09%   |
| 4       | 3         | 0.04%   |
| 8       | 1         | 0.01%   |
| 0       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3979      | 56.92%  |
| 1       | 2988      | 42.74%  |
| Unknown | 23        | 0.33%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6783      | 97.11%  |
| 32-bit         | 122       | 1.75%   |
| Unknown        | 55        | 0.79%   |
| 64-bit         | 25        | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1397      | 19.65%  |
| 0x1067a    | 562       | 7.91%   |
| 0x306c3    | 309       | 4.35%   |
| 0x306a9    | 308       | 4.33%   |
| 0x206a7    | 296       | 4.16%   |
| 0x806c1    | 282       | 3.97%   |
| 0x306d4    | 231       | 3.25%   |
| 0x906ea    | 161       | 2.26%   |
| 0x506e3    | 148       | 2.08%   |
| 0x806ec    | 137       | 1.93%   |
| 0x806e9    | 125       | 1.76%   |
| 0x30678    | 120       | 1.69%   |
| 0x806ea    | 108       | 1.52%   |
| 0x406e3    | 96        | 1.35%   |
| 0x40651    | 93        | 1.31%   |
| 0x08108109 | 89        | 1.25%   |
| 0x906e9    | 86        | 1.21%   |
| 0x406c4    | 86        | 1.21%   |
| 0xa0653    | 80        | 1.13%   |
| 0x6f6      | 74        | 1.04%   |
| 0x906c0    | 73        | 1.03%   |
| 0x08701021 | 70        | 0.98%   |
| 0x906eb    | 65        | 0.91%   |
| 0x0a50000c | 65        | 0.91%   |
| 0x20655    | 64        | 0.9%    |
| 0x706a8    | 63        | 0.89%   |
| 0x08600106 | 62        | 0.87%   |
| 0xa0652    | 58        | 0.82%   |
| 0x10676    | 55        | 0.77%   |
| 0x6fd      | 51        | 0.72%   |
| 0x506c9    | 51        | 0.72%   |
| 0x08608103 | 46        | 0.65%   |
| 0x0600611a | 43        | 0.6%    |
| 0xa0671    | 42        | 0.59%   |
| 0x0a201016 | 42        | 0.59%   |
| 0xa0655    | 41        | 0.58%   |
| 0x706e5    | 41        | 0.58%   |
| 0x306f2    | 36        | 0.51%   |
| 0x106c2    | 36        | 0.51%   |
| 0x0800820d | 36        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 908       | 12.98%  |
| Penryn           | 658       | 9.41%   |
| Haswell          | 546       | 7.8%    |
| Unknown          | 483       | 6.9%    |
| IvyBridge        | 409       | 5.85%   |
| SandyBridge      | 407       | 5.82%   |
| TigerLake        | 328       | 4.69%   |
| Skylake          | 328       | 4.69%   |
| Broadwell        | 274       | 3.92%   |
| Silvermont       | 266       | 3.8%    |
| Zen 2            | 231       | 3.3%    |
| Zen 3            | 220       | 3.14%   |
| CometLake        | 215       | 3.07%   |
| Core             | 204       | 2.92%   |
| Zen+             | 201       | 2.87%   |
| Westmere         | 147       | 2.1%    |
| Goldmont plus    | 103       | 1.47%   |
| Excavator        | 99        | 1.42%   |
| Zen              | 91        | 1.3%    |
| K10              | 84        | 1.2%    |
| Icelake          | 84        | 1.2%    |
| Tremont          | 83        | 1.19%   |
| Piledriver       | 83        | 1.19%   |
| Bonnell          | 78        | 1.11%   |
| Goldmont         | 62        | 0.89%   |
| P6               | 59        | 0.84%   |
| Nehalem          | 49        | 0.7%    |
| Alderlake Hybrid | 48        | 0.69%   |
| Bobcat           | 42        | 0.6%    |
| NetBurst         | 40        | 0.57%   |
| K8 Hammer        | 39        | 0.56%   |
| Puma             | 32        | 0.46%   |
| Jaguar           | 25        | 0.36%   |
| Steamroller      | 24        | 0.34%   |
| Bulldozer        | 20        | 0.29%   |
| K10 Llano        | 12        | 0.17%   |
| K8 & K10 hybrid  | 6         | 0.09%   |
| K6               | 4         | 0.06%   |
| Gracemont        | 2         | 0.03%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4045      | 53.62%  |
| Nvidia                                       | 1901      | 25.2%   |
| AMD                                          | 1362      | 18.05%  |
| Matrox Electronics Systems                   | 109       | 1.44%   |
| ASPEED Technology                            | 106       | 1.41%   |
| VIA Technologies                             | 8         | 0.11%   |
| Silicon Integrated Systems [SiS]             | 7         | 0.09%   |
| Zhaoxin                                      | 3         | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 353       | 4.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 302       | 3.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 278       | 3.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 205       | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 169       | 2.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 169       | 2.16%   |
| Intel HD Graphics 6000                                                                   | 156       | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 148       | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 141       | 1.81%   |
| Intel HD Graphics 620                                                                    | 125       | 1.6%    |
| Intel UHD Graphics 620                                                                   | 124       | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 118       | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 112       | 1.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 111       | 1.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 108       | 1.38%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 107       | 1.37%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 106       | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 102       | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 101       | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 94        | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 91        | 1.17%   |
| Intel HD Graphics 5500                                                                   | 87        | 1.11%   |
| Intel HD Graphics 530                                                                    | 87        | 1.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 86        | 1.1%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 81        | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 79        | 1.01%   |
| Intel Core Processor Integrated Graphics Controller                                      | 77        | 0.99%   |
| Intel JasperLake [UHD Graphics]                                                          | 76        | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 73        | 0.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 72        | 0.92%   |
| Intel HD Graphics 630                                                                    | 70        | 0.9%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 63        | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 62        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 59        | 0.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 59        | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 59        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 58        | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 58        | 0.74%   |
| AMD Lucienne                                                                             | 58        | 0.74%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 57        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 3320      | 47.37%  |
| 1 x Nvidia                        | 1238      | 17.67%  |
| 1 x AMD                           | 1106      | 15.78%  |
| Intel + Nvidia                    | 548       | 7.82%   |
| Other                             | 300       | 4.28%   |
| 1 x Matrox                        | 105       | 1.5%    |
| Intel + AMD                       | 99        | 1.41%   |
| AMD + Nvidia                      | 86        | 1.23%   |
| 1 x ASPEED                        | 82        | 1.17%   |
| 2 x AMD                           | 60        | 0.86%   |
| Nvidia + ASPEED                   | 12        | 0.17%   |
| 2 x Nvidia                        | 9         | 0.13%   |
| AMD + ASPEED                      | 9         | 0.13%   |
| 1 x VIA                           | 8         | 0.11%   |
| 1 x SiS                           | 7         | 0.1%    |
| 2 x Intel                         | 3         | 0.04%   |
| 1 x Zhaoxin                       | 3         | 0.04%   |
| Nvidia + Matrox                   | 3         | 0.04%   |
| Intel + 2 x Nvidia                | 3         | 0.04%   |
| 2 x Nvidia + 1 x ASPEED           | 2         | 0.03%   |
| 3 x AMD                           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x S3 Graphics                   | 1         | 0.01%   |
| Nvidia + XGI                      | 1         | 0.01%   |
| AMD + Matrox                      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4976      | 70.77%  |
| Unknown     | 1489      | 21.18%  |
| Proprietary | 566       | 8.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 5070      | 71.83%  |
| 0.01-0.5       | 822       | 11.65%  |
| 1.01-2.0       | 386       | 5.47%   |
| 0.51-1.0       | 245       | 3.47%   |
| 3.01-4.0       | 240       | 3.4%    |
| 7.01-8.0       | 132       | 1.87%   |
| 5.01-6.0       | 82        | 1.16%   |
| 8.01-16.0      | 39        | 0.55%   |
| 2.01-3.0       | 26        | 0.37%   |
| 16.01-24.0     | 8         | 0.11%   |
| 4.01-5.0       | 5         | 0.07%   |
| More than 64.0 | 1         | 0.01%   |
| 32.01-64.0     | 1         | 0.01%   |
| 24.01-32.0     | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 723       | 11.92%  |
| Apple                   | 664       | 10.95%  |
| Samsung Electronics     | 589       | 9.71%   |
| BOE                     | 500       | 8.24%   |
| LG Display              | 437       | 7.21%   |
| Chimei Innolux          | 424       | 6.99%   |
| Dell                    | 327       | 5.39%   |
| Goldstar                | 258       | 4.25%   |
| Hewlett-Packard         | 172       | 2.84%   |
| Acer                    | 158       | 2.61%   |
| BenQ                    | 147       | 2.42%   |
| AOC                     | 130       | 2.14%   |
| Lenovo                  | 125       | 2.06%   |
| Philips                 | 121       | 2%      |
| Ancor Communications    | 113       | 1.86%   |
| Sharp                   | 78        | 1.29%   |
| Unknown                 | 74        | 1.22%   |
| ViewSonic               | 72        | 1.19%   |
| Chi Mei Optoelectronics | 67        | 1.1%    |
| Iiyama                  | 66        | 1.09%   |
| InfoVision              | 63        | 1.04%   |
| Eizo                    | 42        | 0.69%   |
| PANDA                   | 39        | 0.64%   |
| ASUSTek Computer        | 38        | 0.63%   |
| NEC Computers           | 35        | 0.58%   |
| Sony                    | 34        | 0.56%   |
| HannStar                | 33        | 0.54%   |
| LG Philips              | 24        | 0.4%    |
| LG Electronics          | 23        | 0.38%   |
| Unknown                 | 18        | 0.3%    |
| MSI                     | 17        | 0.28%   |
| CSO                     | 17        | 0.28%   |
| Panasonic               | 15        | 0.25%   |
| Vestel Elektronik       | 14        | 0.23%   |
| Toshiba                 | 12        | 0.2%    |
| Vizio                   | 11        | 0.18%   |
| Medion                  | 10        | 0.16%   |
| Fujitsu Siemens         | 9         | 0.15%   |
| AGO                     | 9         | 0.15%   |
| CPT                     | 8         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                  | 209       | 3.37%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 187       | 3.01%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch        | 112       | 1.8%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 57        | 0.92%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                  | 54        | 0.87%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 42        | 0.68%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 41        | 0.66%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 41        | 0.66%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 38        | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 28        | 0.45%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 28        | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 26        | 0.42%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 25        | 0.4%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 22        | 0.35%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                  | 22        | 0.35%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 21        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 21        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 20        | 0.32%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 18        | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 18        | 0.29%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 18        | 0.29%   |
| Unknown                                                               | 18        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 17        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 16        | 0.26%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 15        | 0.24%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 13        | 0.21%   |
| BenQ GW2470 BNQ78E4 1920x1080 530x300mm 24.0-inch                     | 13        | 0.21%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                  | 13        | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 12        | 0.19%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 12        | 0.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 11        | 0.18%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 11        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 11        | 0.18%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                  | 11        | 0.18%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.18%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 10        | 0.16%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 10        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 10        | 0.16%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 10        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2341      | 40.18%  |
| 1366x768 (WXGA)    | 1024      | 17.58%  |
| 1280x800 (WXGA)    | 539       | 9.25%   |
| 3840x2160 (4K)     | 311       | 5.34%   |
| 1280x1024 (SXGA)   | 222       | 3.81%   |
| 2560x1440 (QHD)    | 219       | 3.76%   |
| 1600x900 (HD+)     | 184       | 3.16%   |
| 1440x900 (WXGA+)   | 175       | 3%      |
| 1920x1200 (WUXGA)  | 126       | 2.16%   |
| 1680x1050 (WSXGA+) | 115       | 1.97%   |
| Unknown            | 67        | 1.15%   |
| 2288x1287          | 59        | 1.01%   |
| 1024x600           | 51        | 0.88%   |
| 1024x768 (XGA)     | 46        | 0.79%   |
| 3440x1440          | 40        | 0.69%   |
| 1360x768           | 39        | 0.67%   |
| 2560x1080          | 38        | 0.65%   |
| 2560x1600          | 27        | 0.46%   |
| 3840x1080          | 23        | 0.39%   |
| 1600x1200          | 23        | 0.39%   |
| 1920x540           | 14        | 0.24%   |
| 3840x2400          | 13        | 0.22%   |
| 2880x1800          | 10        | 0.17%   |
| 2160x1440          | 10        | 0.17%   |
| 1400x1050          | 9         | 0.15%   |
| 2736x1824          | 7         | 0.12%   |
| 1920x1280          | 6         | 0.1%    |
| 4480x1440          | 5         | 0.09%   |
| 2048x1152          | 5         | 0.09%   |
| 5760x1080          | 4         | 0.07%   |
| 3840x1200          | 4         | 0.07%   |
| 3200x1080          | 4         | 0.07%   |
| 1280x720 (HD)      | 4         | 0.07%   |
| 5760x2160          | 3         | 0.05%   |
| 5120x1440          | 3         | 0.05%   |
| 3840x1600          | 3         | 0.05%   |
| 3200x1800 (QHD+)   | 3         | 0.05%   |
| 1800x1200          | 3         | 0.05%   |
| 1024x576           | 3         | 0.05%   |
| 5360x1440          | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1138      | 18.93%  |
| 13      | 1116      | 18.56%  |
| 14      | 445       | 7.4%    |
| 24      | 436       | 7.25%   |
| 27      | 356       | 5.92%   |
| 23      | 326       | 5.42%   |
| 17      | 292       | 4.86%   |
| 21      | 282       | 4.69%   |
| 11      | 265       | 4.41%   |
| Unknown | 199       | 3.31%   |
| 19      | 157       | 2.61%   |
| 12      | 136       | 2.26%   |
| 18      | 116       | 1.93%   |
| 31      | 105       | 1.75%   |
| 22      | 77        | 1.28%   |
| 20      | 77        | 1.28%   |
| 10      | 59        | 0.98%   |
| 34      | 58        | 0.96%   |
| 142     | 57        | 0.95%   |
| 84      | 34        | 0.57%   |
| 32      | 32        | 0.53%   |
| 16      | 29        | 0.48%   |
| 72      | 28        | 0.47%   |
| 54      | 22        | 0.37%   |
| 25      | 22        | 0.37%   |
| 40      | 17        | 0.28%   |
| 28      | 16        | 0.27%   |
| 29      | 13        | 0.22%   |
| 26      | 11        | 0.18%   |
| 65      | 9         | 0.15%   |
| 52      | 9         | 0.15%   |
| 33      | 7         | 0.12%   |
| 48      | 6         | 0.1%    |
| 49      | 5         | 0.08%   |
| 46      | 5         | 0.08%   |
| 43      | 5         | 0.08%   |
| 42      | 5         | 0.08%   |
| 8       | 5         | 0.08%   |
| 39      | 4         | 0.07%   |
| 35      | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1958      | 33.08%  |
| 201-300        | 1299      | 21.95%  |
| 501-600        | 1032      | 17.44%  |
| 401-500        | 599       | 10.12%  |
| 351-400        | 319       | 5.39%   |
| Unknown        | 199       | 3.36%   |
| 601-700        | 178       | 3.01%   |
| 701-800        | 98        | 1.66%   |
| 1001-1500      | 70        | 1.18%   |
| 1501-2000      | 66        | 1.12%   |
| More than 2000 | 58        | 0.98%   |
| 801-900        | 29        | 0.49%   |
| 901-1000       | 8         | 0.14%   |
| 101-200        | 6         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3819      | 69.21%  |
| 16/10   | 1021      | 18.5%   |
| 5/4     | 206       | 3.73%   |
| Unknown | 162       | 2.94%   |
| 4/3     | 94        | 1.7%    |
| 21/9    | 72        | 1.3%    |
| 1.00    | 59        | 1.07%   |
| 3/2     | 49        | 0.89%   |
| 6/5     | 13        | 0.24%   |
| 32/9    | 6         | 0.11%   |
| 2.65    | 5         | 0.09%   |
| 3.40    | 2         | 0.04%   |
| 3.20    | 2         | 0.04%   |
| 1.96    | 2         | 0.04%   |
| 0.56    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 1203      | 20.16%  |
| 101-110        | 1129      | 18.92%  |
| 201-250        | 884       | 14.82%  |
| 301-350        | 365       | 6.12%   |
| 71-80          | 360       | 6.03%   |
| 151-200        | 323       | 5.41%   |
| 51-60          | 268       | 4.49%   |
| 351-500        | 224       | 3.75%   |
| 141-150        | 201       | 3.37%   |
| Unknown        | 199       | 3.34%   |
| More than 1000 | 181       | 3.03%   |
| 251-300        | 165       | 2.77%   |
| 121-130        | 161       | 2.7%    |
| 61-70          | 123       | 2.06%   |
| 41-50          | 58        | 0.97%   |
| 501-1000       | 47        | 0.79%   |
| 131-140        | 31        | 0.52%   |
| 111-120        | 24        | 0.4%    |
| 91-100         | 14        | 0.23%   |
| 1-40           | 6         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1707      | 29.32%  |
| 121-160       | 1660      | 28.52%  |
| 101-120       | 1632      | 28.04%  |
| 161-240       | 386       | 6.63%   |
| Unknown       | 199       | 3.42%   |
| 1-50          | 162       | 2.78%   |
| More than 240 | 75        | 1.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4616      | 65.03%  |
| 0     | 1596      | 22.49%  |
| 2     | 795       | 11.2%   |
| 3     | 88        | 1.24%   |
| 4     | 2         | 0.03%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3269      | 32.32%  |
| Intel                             | 3126      | 30.91%  |
| Qualcomm Atheros                  | 886       | 8.76%   |
| Broadcom                          | 853       | 8.43%   |
| Nvidia                            | 423       | 4.18%   |
| Broadcom Limited                  | 276       | 2.73%   |
| Marvell Technology Group          | 148       | 1.46%   |
| MediaTek                          | 108       | 1.07%   |
| Ralink Technology                 | 83        | 0.82%   |
| TP-Link                           | 81        | 0.8%    |
| ASIX Electronics                  | 64        | 0.63%   |
| Ralink                            | 63        | 0.62%   |
| Samsung Electronics               | 47        | 0.46%   |
| Xiaomi                            | 32        | 0.32%   |
| Microchip Technology              | 32        | 0.32%   |
| Sierra Wireless                   | 31        | 0.31%   |
| Dell                              | 30        | 0.3%    |
| Mellanox Technologies             | 27        | 0.27%   |
| Qualcomm Atheros Communications   | 24        | 0.24%   |
| Qualcomm                          | 23        | 0.23%   |
| Huawei Technologies               | 22        | 0.22%   |
| DisplayLink                       | 21        | 0.21%   |
| Aquantia                          | 20        | 0.2%    |
| NetGear                           | 18        | 0.18%   |
| D-Link System                     | 18        | 0.18%   |
| American Megatrends               | 18        | 0.18%   |
| Lenovo                            | 17        | 0.17%   |
| JMicron Technology                | 15        | 0.15%   |
| D-Link                            | 15        | 0.15%   |
| Ericsson Business Mobile Networks | 14        | 0.14%   |
| Edimax Technology                 | 14        | 0.14%   |
| Dresden Elektronik                | 14        | 0.14%   |
| ASUSTek Computer                  | 14        | 0.14%   |
| Hewlett-Packard                   | 13        | 0.13%   |
| VIA Technologies                  | 12        | 0.12%   |
| Microsoft                         | 12        | 0.12%   |
| Sigma Designs                     | 11        | 0.11%   |
| OPPO Electronics                  | 10        | 0.1%    |
| ICS Advent                        | 10        | 0.1%    |
| Standard Microsystems             | 9         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 2279      | 19.26%  |
| Nvidia MCP79 Ethernet                                                                 | 370       | 3.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 365       | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 322       | 2.72%   |
| Intel Wi-Fi 6 AX201                                                                   | 264       | 2.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 221       | 1.87%   |
| Intel Wi-Fi 6 AX200                                                                   | 206       | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 184       | 1.56%   |
| Intel Wireless 7260                                                                   | 174       | 1.47%   |
| Intel Wireless 8265 / 8275                                                            | 169       | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 167       | 1.41%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 165       | 1.39%   |
| Intel Wireless 7265                                                                   | 160       | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 149       | 1.26%   |
| Intel Ethernet Connection (13) I219-V                                                 | 137       | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 115       | 0.97%   |
| Intel I211 Gigabit Network Connection                                                 | 99        | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 96        | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 96        | 0.81%   |
| Intel Wireless 8260                                                                   | 93        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 92        | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 91        | 0.77%   |
| Intel Wireless 3165                                                                   | 91        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 90        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 90        | 0.76%   |
| Intel Ethernet Controller I225-V                                                      | 90        | 0.76%   |
| Intel I210 Gigabit Network Connection                                                 | 89        | 0.75%   |
| Intel Ethernet Connection I217-LM                                                     | 86        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 82        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 73        | 0.62%   |
| Intel Ethernet Connection (2) I219-V                                                  | 67        | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 64        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 62        | 0.52%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 60        | 0.51%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 58        | 0.49%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                                  | 57        | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 56        | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 55        | 0.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 52        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2180      | 44.55%  |
| Qualcomm Atheros                      | 722       | 14.76%  |
| Realtek Semiconductor                 | 660       | 13.49%  |
| Broadcom                              | 601       | 12.28%  |
| Broadcom Limited                      | 217       | 4.43%   |
| MediaTek                              | 99        | 2.02%   |
| Ralink Technology                     | 83        | 1.7%    |
| Ralink                                | 63        | 1.29%   |
| TP-Link                               | 61        | 1.25%   |
| Sierra Wireless                       | 31        | 0.63%   |
| Qualcomm Atheros Communications       | 24        | 0.49%   |
| Dell                                  | 18        | 0.37%   |
| NetGear                               | 17        | 0.35%   |
| Edimax Technology                     | 14        | 0.29%   |
| ASUSTek Computer                      | 14        | 0.29%   |
| D-Link                                | 12        | 0.25%   |
| Qualcomm                              | 9         | 0.18%   |
| Marvell Technology Group              | 9         | 0.18%   |
| Microsoft                             | 8         | 0.16%   |
| FIBOCOM                               | 8         | 0.16%   |
| D-Link System                         | 8         | 0.16%   |
| Belkin Components                     | 7         | 0.14%   |
| Gemtek                                | 4         | 0.08%   |
| Wilocity                              | 3         | 0.06%   |
| IMC Networks                          | 3         | 0.06%   |
| AVM                                   | 3         | 0.06%   |
| Linksys                               | 2         | 0.04%   |
| Z-Com                                 | 1         | 0.02%   |
| Xiaomi                                | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Hewlett-Packard                       | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| CyberTAN Technology                   | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |
| 3Com                                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 365       | 7.43%   |
| Intel Wi-Fi 6 AX201                                                                   | 264       | 5.37%   |
| Intel Wi-Fi 6 AX200                                                                   | 206       | 4.19%   |
| Intel Wireless 7260                                                                   | 174       | 3.54%   |
| Intel Wireless 8265 / 8275                                                            | 169       | 3.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 167       | 3.4%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 165       | 3.36%   |
| Intel Wireless 7265                                                                   | 160       | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 115       | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 96        | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 96        | 1.95%   |
| Intel Wireless 8260                                                                   | 93        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 92        | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 91        | 1.85%   |
| Intel Wireless 3165                                                                   | 91        | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 90        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 90        | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 82        | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 73        | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 64        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 62        | 1.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 58        | 1.18%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 57        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 56        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 55        | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 52        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 47        | 0.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 43        | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 43        | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 41        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 41        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 39        | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 38        | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 36        | 0.73%   |
| Realtek 802.11ac NIC                                                                  | 32        | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 31        | 0.63%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 30        | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 29        | 0.59%   |
| Intel Wireless 3160                                                                   | 29        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                                        | 29        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2996      | 45.95%  |
| Intel                            | 1856      | 28.47%  |
| Nvidia                           | 422       | 6.47%   |
| Broadcom                         | 304       | 4.66%   |
| Qualcomm Atheros                 | 245       | 3.76%   |
| Marvell Technology Group         | 140       | 2.15%   |
| ASIX Electronics                 | 64        | 0.98%   |
| Broadcom Limited                 | 62        | 0.95%   |
| Samsung Electronics              | 47        | 0.72%   |
| Microchip Technology             | 32        | 0.49%   |
| Xiaomi                           | 31        | 0.48%   |
| Mellanox Technologies            | 24        | 0.37%   |
| DisplayLink                      | 21        | 0.32%   |
| TP-Link                          | 20        | 0.31%   |
| Aquantia                         | 20        | 0.31%   |
| American Megatrends              | 18        | 0.28%   |
| Lenovo                           | 17        | 0.26%   |
| JMicron Technology               | 15        | 0.23%   |
| Huawei Technologies              | 14        | 0.21%   |
| Qualcomm                         | 13        | 0.2%    |
| VIA Technologies                 | 12        | 0.18%   |
| OPPO Electronics                 | 10        | 0.15%   |
| ICS Advent                       | 10        | 0.15%   |
| D-Link System                    | 10        | 0.15%   |
| Standard Microsystems            | 9         | 0.14%   |
| Silicon Integrated Systems [SiS] | 8         | 0.12%   |
| MediaTek                         | 8         | 0.12%   |
| IBM                              | 8         | 0.12%   |
| Cypress Semiconductor            | 6         | 0.09%   |
| 3Com                             | 6         | 0.09%   |
| Motorola PCS                     | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.06%   |
| NetXen Incorporated              | 4         | 0.06%   |
| Hewlett-Packard                  | 4         | 0.06%   |
| Emulex                           | 4         | 0.06%   |
| Attansic Technology              | 4         | 0.06%   |
| QLogic                           | 3         | 0.05%   |
| Microsoft                        | 3         | 0.05%   |
| Insyde Software                  | 3         | 0.05%   |
| Google                           | 3         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2279      | 33.76%  |
| Nvidia MCP79 Ethernet                                                  | 370       | 5.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 322       | 4.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 221       | 3.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 184       | 2.73%   |
| Realtek RTL8125 2.5GbE Controller                                      | 149       | 2.21%   |
| Intel Ethernet Connection (13) I219-V                                  | 137       | 2.03%   |
| Intel I211 Gigabit Network Connection                                  | 99        | 1.47%   |
| Intel Ethernet Controller I225-V                                       | 90        | 1.33%   |
| Intel I210 Gigabit Network Connection                                  | 89        | 1.32%   |
| Intel Ethernet Connection I217-LM                                      | 86        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                                   | 67        | 0.99%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 60        | 0.89%   |
| Intel Ethernet Connection (4) I219-V                                   | 57        | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 52        | 0.77%   |
| Intel 82574L Gigabit Network Connection                                | 52        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                          | 52        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                                  | 51        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                                  | 47        | 0.7%    |
| Intel I350 Gigabit Network Connection                                  | 46        | 0.68%   |
| Intel Ethernet Connection I219-LM                                      | 46        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 44        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                   | 44        | 0.65%   |
| Intel Ethernet Connection (14) I219-V                                  | 43        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 38        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 38        | 0.56%   |
| Intel Ethernet Connection I218-LM                                      | 37        | 0.55%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 35        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 33        | 0.49%   |
| Intel Ethernet Connection (10) I219-V                                  | 33        | 0.49%   |
| Intel Ethernet Connection I217-V                                       | 32        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 30        | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 30        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 29        | 0.43%   |
| Nvidia MCP61 Ethernet                                                  | 29        | 0.43%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 29        | 0.43%   |
| Intel 82577LM Gigabit Network Connection                               | 29        | 0.43%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 28        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 27        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                                  | 27        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6023      | 55.46%  |
| WiFi     | 4674      | 43.04%  |
| Modem    | 146       | 1.34%   |
| Unknown  | 17        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3687      | 53.71%  |
| WiFi     | 3177      | 46.28%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3570      | 50.99%  |
| 1     | 2714      | 38.77%  |
| 0     | 325       | 4.64%   |
| 3     | 213       | 3.04%   |
| 4     | 94        | 1.34%   |
| 6     | 29        | 0.41%   |
| 5     | 24        | 0.34%   |
| 8     | 13        | 0.19%   |
| 7     | 8         | 0.11%   |
| 9     | 3         | 0.04%   |
| 20    | 2         | 0.03%   |
| 12    | 2         | 0.03%   |
| 17    | 1         | 0.01%   |
| 16    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 11    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5692      | 80.85%  |
| Yes  | 1348      | 19.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1761      | 45.04%  |
| Apple                           | 676       | 17.29%  |
| Realtek Semiconductor           | 324       | 8.29%   |
| Qualcomm Atheros Communications | 249       | 6.37%   |
| Cambridge Silicon Radio         | 189       | 4.83%   |
| Broadcom                        | 151       | 3.86%   |
| IMC Networks                    | 128       | 3.27%   |
| Lite-On Technology              | 114       | 2.92%   |
| Foxconn / Hon Hai               | 74        | 1.89%   |
| ASUSTek Computer                | 47        | 1.2%    |
| Dell                            | 41        | 1.05%   |
| Hewlett-Packard                 | 32        | 0.82%   |
| MediaTek                        | 29        | 0.74%   |
| Toshiba                         | 19        | 0.49%   |
| Realtek                         | 16        | 0.41%   |
| Ralink                          | 12        | 0.31%   |
| Ralink Technology               | 6         | 0.15%   |
| TP-Link                         | 5         | 0.13%   |
| Taiyo Yuden                     | 4         | 0.1%    |
| Foxconn International           | 4         | 0.1%    |
| Alps Electric                   | 4         | 0.1%    |
| Marvell Semiconductor           | 3         | 0.08%   |
| Fujitsu                         | 3         | 0.08%   |
| Belkin Components               | 3         | 0.08%   |
| USI                             | 2         | 0.05%   |
| Edimax Technology               | 2         | 0.05%   |
| Unknown                         | 2         | 0.05%   |
| Sitecom Europe                  | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 444       | 11.35%  |
| Intel AX201 Bluetooth                               | 431       | 11.01%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 366       | 9.35%   |
| Intel Bluetooth Device                              | 232       | 5.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 230       | 5.88%   |
| Intel AX200 Bluetooth                               | 196       | 5.01%   |
| Realtek Bluetooth Radio                             | 190       | 4.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 189       | 4.83%   |
| Apple Bluetooth USB Host Controller                 | 174       | 4.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 148       | 3.78%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 1.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 56        | 1.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 54        | 1.38%   |
| Apple Bluetooth Host Controller                     | 48        | 1.23%   |
| Intel AX210 Bluetooth                               | 45        | 1.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 43        | 1.1%    |
| Intel AX211 Bluetooth                               | 42        | 1.07%   |
| Realtek 802.11ac WLAN Adapter                       | 41        | 1.05%   |
| IMC Networks Bluetooth Radio                        | 39        | 1%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 37        | 0.95%   |
| IMC Networks Bluetooth Device                       | 34        | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 32        | 0.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 31        | 0.79%   |
| Lite-On Bluetooth Device                            | 29        | 0.74%   |
| MediaTek Wireless_Device                            | 28        | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.66%   |
| IMC Networks Wireless_Device                        | 24        | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 0.59%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 0.59%   |
| Realtek RTL8723B Bluetooth                          | 21        | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 20        | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 20        | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 0.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 19        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 18        | 0.46%   |
| Realtek Bluetooth Radio                             | 16        | 0.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.36%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 13        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4680      | 55.89%  |
| Nvidia                                       | 1519      | 18.14%  |
| AMD                                          | 1446      | 17.27%  |
| C-Media Electronics                          | 115       | 1.37%   |
| Logitech                                     | 57        | 0.68%   |
| Creative Labs                                | 37        | 0.44%   |
| ASUSTek Computer                             | 30        | 0.36%   |
| Realtek Semiconductor                        | 27        | 0.32%   |
| Texas Instruments                            | 26        | 0.31%   |
| Generalplus Technology                       | 26        | 0.31%   |
| KTMicro                                      | 24        | 0.29%   |
| Lenovo                                       | 23        | 0.27%   |
| Plantronics                                  | 22        | 0.26%   |
| GN Netcom                                    | 18        | 0.21%   |
| Creative Technology                          | 18        | 0.21%   |
| VIA Technologies                             | 16        | 0.19%   |
| JMTek                                        | 16        | 0.19%   |
| Focusrite-Novation                           | 15        | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 13        | 0.16%   |
| Kingston Technology                          | 12        | 0.14%   |
| Micro Star International                     | 11        | 0.13%   |
| SteelSeries ApS                              | 9         | 0.11%   |
| Silicon Integrated Systems [SiS]             | 9         | 0.11%   |
| Hewlett-Packard                              | 9         | 0.11%   |
| RODE Microphones                             | 8         | 0.1%    |
| Razer USA                                    | 8         | 0.1%    |
| Dell                                         | 8         | 0.1%    |
| GYROCOM C&C                                  | 7         | 0.08%   |
| BEHRINGER International                      | 7         | 0.08%   |
| DSEA A/S                                     | 6         | 0.07%   |
| Yamaha                                       | 5         | 0.06%   |
| Tenx Technology                              | 5         | 0.06%   |
| Microsoft                                    | 5         | 0.06%   |
| Giga-Byte Technology                         | 5         | 0.06%   |
| Cambridge Silicon Radio                      | 5         | 0.06%   |
| Sennheiser Communications                    | 4         | 0.05%   |
| M-Audio                                      | 4         | 0.05%   |
| Ensoniq                                      | 4         | 0.05%   |
| Corsair                                      | 4         | 0.05%   |
| Apple                                        | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 487       | 4.91%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 407       | 4.1%    |
| Nvidia MCP79 High Definition Audio                                                                | 373       | 3.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 363       | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 354       | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 332       | 3.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 327       | 3.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 292       | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 260       | 2.62%   |
| Intel Broadwell-U Audio Controller                                                                | 253       | 2.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 248       | 2.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 243       | 2.45%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 207       | 2.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 187       | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 182       | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 180       | 1.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 169       | 1.7%    |
| Intel 200 Series PCH HD Audio                                                                     | 162       | 1.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 133       | 1.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 131       | 1.32%   |
| AMD FCH Azalia Controller                                                                         | 129       | 1.3%    |
| Intel Comet Lake PCH cAVS                                                                         | 126       | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 122       | 1.23%   |
| Intel 8 Series HD Audio Controller                                                                | 122       | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 120       | 1.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 115       | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 110       | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 109       | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 103       | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 101       | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 101       | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 100       | 1.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 96        | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 88        | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 87        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 75        | 0.76%   |
| Intel Jasper Lake HD Audio                                                                        | 74        | 0.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 74        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 72        | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 68        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1437      | 21.41%  |
| SK hynix            | 1362      | 20.29%  |
| Kingston            | 732       | 10.91%  |
| Unknown             | 639       | 9.52%   |
| Micron Technology   | 560       | 8.34%   |
| Crucial             | 534       | 7.96%   |
| Corsair             | 256       | 3.81%   |
| G.Skill             | 162       | 2.41%   |
| Elpida              | 122       | 1.82%   |
| A-DATA Technology   | 112       | 1.67%   |
| Ramaxel Technology  | 93        | 1.39%   |
| Patriot             | 76        | 1.13%   |
| Unknown             | 66        | 0.98%   |
| Unknown (ABCD)      | 65        | 0.97%   |
| Nanya Technology    | 59        | 0.88%   |
| Team                | 38        | 0.57%   |
| GOODRAM             | 37        | 0.55%   |
| Smart               | 33        | 0.49%   |
| Transcend           | 25        | 0.37%   |
| AMD                 | 22        | 0.33%   |
| Hikvision           | 21        | 0.31%   |
| Hewlett-Packard     | 16        | 0.24%   |
| Apacer              | 14        | 0.21%   |
| Timetec             | 12        | 0.18%   |
| Silicon Power       | 9         | 0.13%   |
| Qimonda             | 9         | 0.13%   |
| Avant               | 8         | 0.12%   |
| Unknown (0x5846)    | 7         | 0.1%    |
| PNY                 | 7         | 0.1%    |
| GeIL                | 7         | 0.1%    |
| ASint Technology    | 7         | 0.1%    |
| Wilk                | 5         | 0.07%   |
| Unifosa             | 5         | 0.07%   |
| Infineon            | 5         | 0.07%   |
| Goldkey             | 5         | 0.07%   |
| 48spaces            | 5         | 0.07%   |
| Unknown (0x0DD5)    | 4         | 0.06%   |
| Toshiba             | 4         | 0.06%   |
| Kllisre             | 4         | 0.06%   |
| Kingmax             | 4         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 3.68%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 144       | 2.01%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 69        | 0.96%   |
| Unknown                                                          | 66        | 0.92%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 0.88%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 61        | 0.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 45        | 0.63%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.61%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 41        | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 40        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 36        | 0.5%    |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s         | 36        | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 35        | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 34        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 33        | 0.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 33        | 0.46%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 32        | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 32        | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 31        | 0.43%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 30        | 0.42%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.4%    |
| Crucial RAM CT4G4DFS8213.C8FAR2 4096MB DIMM DDR4 2133MT/s        | 29        | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 27        | 0.38%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 27        | 0.38%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 27        | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 0.36%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.35%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 0.33%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s             | 24        | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 23        | 0.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 22        | 0.31%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 21        | 0.29%   |
| Micron RAM EDF8132A3MA-GD-F 2GB LPDDR3 1600MT/s                  | 21        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2528      | 42.58%  |
| DDR3         | 1951      | 32.86%  |
| DDR2         | 671       | 11.3%   |
| SDRAM        | 193       | 3.25%   |
| Unknown      | 181       | 3.05%   |
| LPDDR4       | 166       | 2.8%    |
| LPDDR3       | 122       | 2.05%   |
| DDR          | 59        | 0.99%   |
| DDR5         | 38        | 0.64%   |
| DRAM         | 21        | 0.35%   |
| LPDDR5       | 6         | 0.1%    |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3383      | 57.2%   |
| DIMM         | 2210      | 37.37%  |
| Row Of Chips | 222       | 3.75%   |
| Unknown      | 55        | 0.93%   |
| Chip         | 28        | 0.47%   |
| RIMM         | 8         | 0.14%   |
| FB-DIMM      | 8         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 2043      | 31.89%  |
| 4096    | 1488      | 23.22%  |
| 2048    | 985       | 15.37%  |
| 16384   | 853       | 13.31%  |
| 1024    | 640       | 9.99%   |
| 32768   | 294       | 4.59%   |
| 512     | 67        | 1.05%   |
| 256     | 18        | 0.28%   |
| 65536   | 11        | 0.17%   |
| 131072  | 1         | 0.02%   |
| 8072    | 1         | 0.02%   |
| 3072    | 1         | 0.02%   |
| 1536    | 1         | 0.02%   |
| 384     | 1         | 0.02%   |
| 128     | 1         | 0.02%   |
| 16      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1247      | 19.6%   |
| 3200    | 986       | 15.5%   |
| 2667    | 779       | 12.25%  |
| 800     | 497       | 7.81%   |
| 1333    | 432       | 6.79%   |
| 2400    | 406       | 6.38%   |
| 2133    | 269       | 4.23%   |
| 667     | 213       | 3.35%   |
| Unknown | 176       | 2.77%   |
| 1334    | 137       | 2.15%   |
| 3600    | 130       | 2.04%   |
| 1867    | 95        | 1.49%   |
| 1866    | 83        | 1.3%    |
| 2666    | 81        | 1.27%   |
| 1067    | 79        | 1.24%   |
| 1066    | 59        | 0.93%   |
| 4267    | 49        | 0.77%   |
| 3266    | 43        | 0.68%   |
| 2933    | 40        | 0.63%   |
| 4800    | 39        | 0.61%   |
| 3733    | 38        | 0.6%    |
| 3400    | 30        | 0.47%   |
| 1800    | 29        | 0.46%   |
| 533     | 29        | 0.46%   |
| 3000    | 28        | 0.44%   |
| 2866    | 27        | 0.42%   |
| 3800    | 24        | 0.38%   |
| 4199    | 23        | 0.36%   |
| 2048    | 23        | 0.36%   |
| 3466    | 19        | 0.3%    |
| 400     | 18        | 0.28%   |
| 3866    | 14        | 0.22%   |
| 333     | 13        | 0.2%    |
| 3933    | 12        | 0.19%   |
| 8400    | 11        | 0.17%   |
| 266     | 11        | 0.17%   |
| 6400    | 10        | 0.16%   |
| 3534    | 10        | 0.16%   |
| 975     | 10        | 0.16%   |
| 4266    | 9         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 47        | 33.1%   |
| Brother Industries     | 25        | 17.61%  |
| Canon                  | 19        | 13.38%  |
| Samsung Electronics    | 11        | 7.75%   |
| Xerox                  | 8         | 5.63%   |
| Seiko Epson            | 8         | 5.63%   |
| Dymo-CoStar            | 4         | 2.82%   |
| Prolific Technology    | 3         | 2.11%   |
| Lexmark International  | 3         | 2.11%   |
| Zebra                  | 2         | 1.41%   |
| Pantum                 | 2         | 1.41%   |
| STMicroelectronics     | 1         | 0.7%    |
| QinHeng Electronics    | 1         | 0.7%    |
| Printer                | 1         | 0.7%    |
| Panasonic (Matsushita) | 1         | 0.7%    |
| Oki Data               | 1         | 0.7%    |
| Kyocera                | 1         | 0.7%    |
| Konica Minolta         | 1         | 0.7%    |
| GODEX INTERNATIONAL    | 1         | 0.7%    |
| Custom Engineering SPA | 1         | 0.7%    |
| Apple                  | 1         | 0.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 4.93%   |
| HP LaserJet 1200                                                      | 5         | 3.52%   |
| Samsung ML-1660 Series                                                | 3         | 2.11%   |
| Prolific PL2305 Parallel Port                                         | 3         | 2.11%   |
| HP LaserJet P1005                                                     | 3         | 2.11%   |
| HP LaserJet M101-M106                                                 | 3         | 2.11%   |
| HP LaserJet 1020                                                      | 3         | 2.11%   |
| Canon PIXMA MG3600 Series                                             | 3         | 2.11%   |
| HP LaserJet 1150                                                      | 2         | 1.41%   |
| HP ENVY 4520 series                                                   | 2         | 1.41%   |
| HP DeskJet 2700 series                                                | 2         | 1.41%   |
| HP DeskJet 2600 series                                                | 2         | 1.41%   |
| HP DeskJet 2130 series                                                | 2         | 1.41%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.41%   |
| Canon PIXMA MX920 Series                                              | 2         | 1.41%   |
| Canon MF4410                                                          | 2         | 1.41%   |
| Canon LiDE 400                                                        | 2         | 1.41%   |
| Canon LiDE 300                                                        | 2         | 1.41%   |
| Canon G3010 series                                                    | 2         | 1.41%   |
| Brother PT-9500PC                                                     | 2         | 1.41%   |
| Brother MFC-7460DN                                                    | 2         | 1.41%   |
| Brother HL-L2395DW series                                             | 2         | 1.41%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.7%    |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.7%    |
| Xerox Phaser 3250                                                     | 1         | 0.7%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.7%    |
| Seiko Epson XP-205 207 Series                                         | 1         | 0.7%    |
| Seiko Epson Printer                                                   | 1         | 0.7%    |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.7%    |
| Seiko Epson M105 Series                                               | 1         | 0.7%    |
| Seiko Epson L120 Series                                               | 1         | 0.7%    |
| Seiko Epson ET-2850 Series                                            | 1         | 0.7%    |
| Seiko Epson ET-2710 Series                                            | 1         | 0.7%    |
| Seiko Epson ET-2700 Series                                            | 1         | 0.7%    |
| Samsung SCX-4x26 Series                                               | 1         | 0.7%    |
| Samsung SCX-472x Series                                               | 1         | 0.7%    |
| Samsung SCX-4650 4x21S Series                                         | 1         | 0.7%    |
| Samsung SCX-3200 Series                                               | 1         | 0.7%    |
| Samsung ML-216x Series Laser Printer                                  | 1         | 0.7%    |
| Samsung ML-2010P Mono Laser Printer                                   | 1         | 0.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 22        | 62.86%  |
| Seiko Epson     | 7         | 20%     |
| Hewlett-Packard | 3         | 8.57%   |
| AGFA-Gevaert NV | 2         | 5.71%   |
| Mustek Systems  | 1         | 2.86%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 6         | 17.14%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 4         | 11.43%  |
| Canon CanoScan LiDE 210                                       | 3         | 8.57%   |
| Canon CanoScan LiDE 120                                       | 2         | 5.71%   |
| Canon CanoScan LiDE 110                                       | 2         | 5.71%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2         | 5.71%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 2.86%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 2.86%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1         | 2.86%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 2.86%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 2.86%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 2.86%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 2.86%   |
| Mustek Systems BearPaw 2400 CU Plus                           | 1         | 2.86%   |
| HP ScanJet Pro 2500 f1                                        | 1         | 2.86%   |
| HP ScanJet 3970c                                              | 1         | 2.86%   |
| HP Scanjet 300                                                | 1         | 2.86%   |
| Canon CanoScan LiDE 60                                        | 1         | 2.86%   |
| Canon CanoScan LIDE 25                                        | 1         | 2.86%   |
| Canon CanoScan 8800F                                          | 1         | 2.86%   |
| Canon CanoScan 5600F                                          | 1         | 2.86%   |
| Canon CanoScan 4400F                                          | 1         | 2.86%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 744       | 22.57%  |
| Bison Electronics                      | 316       | 9.58%   |
| IMC Networks                           | 292       | 8.86%   |
| Quanta                                 | 245       | 7.43%   |
| Microdia                               | 230       | 6.98%   |
| Realtek Semiconductor                  | 200       | 6.07%   |
| Logitech                               | 192       | 5.82%   |
| Sunplus Innovation Technology          | 145       | 4.4%    |
| Cheng Uei Precision Industry (Foxlink) | 97        | 2.94%   |
| Apple                                  | 97        | 2.94%   |
| Acer                                   | 80        | 2.43%   |
| Suyin                                  | 79        | 2.4%    |
| Lite-On Technology                     | 71        | 2.15%   |
| Syntek                                 | 61        | 1.85%   |
| Luxvisions Innotech Limited            | 58        | 1.76%   |
| Silicon Motion                         | 30        | 0.91%   |
| Alcor Micro                            | 27        | 0.82%   |
| Lenovo                                 | 23        | 0.7%    |
| Generalplus Technology                 | 20        | 0.61%   |
| Microsoft                              | 19        | 0.58%   |
| Z-Star Microelectronics                | 17        | 0.52%   |
| Samsung Electronics                    | 16        | 0.49%   |
| Sonix Technology                       | 14        | 0.42%   |
| Ricoh                                  | 13        | 0.39%   |
| Jieli Technology                       | 12        | 0.36%   |
| Creative Technology                    | 12        | 0.36%   |
| Primax Electronics                     | 11        | 0.33%   |
| ARC International                      | 11        | 0.33%   |
| SunplusIT                              | 9         | 0.27%   |
| Importek                               | 9         | 0.27%   |
| Genesys Logic                          | 9         | 0.27%   |
| GEMBIRD                                | 9         | 0.27%   |
| KYE Systems (Mouse Systems)            | 8         | 0.24%   |
| icSpring                               | 6         | 0.18%   |
| ALi                                    | 6         | 0.18%   |
| Y Media                                | 5         | 0.15%   |
| MacroSilicon                           | 5         | 0.15%   |
| Intel                                  | 5         | 0.15%   |
| OmniVision Technologies                | 4         | 0.12%   |
| Google                                 | 4         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 223       | 6.65%   |
| Bison Integrated Camera                             | 125       | 3.73%   |
| Microdia Integrated_Webcam_HD                       | 106       | 3.16%   |
| IMC Networks Integrated Camera                      | 91        | 2.71%   |
| Bison Integrated 5M Camera                          | 73        | 2.18%   |
| Realtek Integrated_Webcam_HD                        | 72        | 2.15%   |
| Quanta Chromebook HD Camera                         | 69        | 2.06%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 66        | 1.97%   |
| Logitech Webcam C270                                | 58        | 1.73%   |
| Chicony HD Webcam                                   | 56        | 1.67%   |
| Bison BisonCam, NB Pro                              | 50        | 1.49%   |
| Chicony Integrated 5M Camera                        | 43        | 1.28%   |
| Sunplus Integrated_Webcam_HD                        | 40        | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                        | 36        | 1.07%   |
| Chicony HP HD Camera                                | 36        | 1.07%   |
| Apple Built-in iSight                               | 36        | 1.07%   |
| Quanta HP TrueVision HD Camera                      | 32        | 0.95%   |
| Quanta HD User Facing                               | 32        | 0.95%   |
| Acer Integrated Camera                              | 32        | 0.95%   |
| Syntek Integrated Camera                            | 31        | 0.92%   |
| Quanta VGA WebCam                                   | 30        | 0.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 30        | 0.89%   |
| Lite-On Integrated Camera                           | 25        | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 24        | 0.72%   |
| Microdia Integrated Webcam                          | 23        | 0.69%   |
| Logitech HD Pro Webcam C920                         | 23        | 0.69%   |
| Realtek USB Camera                                  | 22        | 0.66%   |
| Quanta HP HD Camera                                 | 22        | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 22        | 0.66%   |
| Bison SunplusIT Integrated Camera                   | 22        | 0.66%   |
| Lite-On HP HD Camera                                | 21        | 0.63%   |
| Chicony HP TrueVision HD Camera                     | 21        | 0.63%   |
| Apple FaceTime HD Camera (Built-in)                 | 21        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)             | 20        | 0.6%    |
| Sunplus HD WebCam                                   | 18        | 0.54%   |
| Chicony HD User Facing                              | 17        | 0.51%   |
| Samsung Galaxy series, misc. (MTP mode)             | 16        | 0.48%   |
| Microdia Webcam Vitade AF                           | 16        | 0.48%   |
| Microdia USB 2.0 Camera                             | 16        | 0.48%   |
| Luxvisions Innotech Limited HP HD Camera            | 16        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 293       | 43.02%  |
| Validity Sensors                   | 194       | 28.49%  |
| Shenzhen Goodix Technology         | 73        | 10.72%  |
| AuthenTec                          | 31        | 4.55%   |
| Upek                               | 30        | 4.41%   |
| Elan Microelectronics              | 28        | 4.11%   |
| LighTuning Technology              | 20        | 2.94%   |
| STMicroelectronics                 | 9         | 1.32%   |
| Samsung Electronics                | 1         | 0.15%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.15%   |
| Focal-systems.Corp                 | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 183       | 26.87%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 6.17%   |
| Shenzhen Goodix  Fingerprint Device                                        | 41        | 6.02%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 34        | 4.99%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 4.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 3.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 27        | 3.96%   |
| Validity Sensors Synaptics WBDI                                            | 22        | 3.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 2.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 2.5%    |
| Shenzhen Goodix FingerPrint                                                | 15        | 2.2%    |
| Elan ELAN:Fingerprint                                                      | 15        | 2.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 13        | 1.91%   |
| Elan ELAN:ARM-M4                                                           | 13        | 1.91%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 1.76%   |
| Synaptics Fingerprint reader [HP G6]                                       | 11        | 1.62%   |
| Validity Sensors VFS491                                                    | 10        | 1.47%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.32%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.17%   |
| Synaptics  WBDI                                                            | 8         | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.17%   |
| AuthenTec AES2810                                                          | 8         | 1.17%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.03%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.03%   |
| Synaptics WBDI                                                             | 7         | 1.03%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.88%   |
| Synaptics UWP WBDI                                                         | 6         | 0.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.73%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.59%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.44%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.44%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.44%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.44%   |
| AuthenTec AES1600                                                          | 3         | 0.44%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.29%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 114       | 36.08%  |
| Alcor Micro               | 103       | 32.59%  |
| Upek                      | 25        | 7.91%   |
| O2 Micro                  | 25        | 7.91%   |
| Lenovo                    | 18        | 5.7%    |
| Gemalto (was Gemplus)     | 6         | 1.9%    |
| SCM Microsystems          | 5         | 1.58%   |
| Yubico.com                | 3         | 0.95%   |
| Advanced Card Systems     | 3         | 0.95%   |
| Reiner SCT Kartensysteme  | 2         | 0.63%   |
| Clay Logic                | 2         | 0.63%   |
| Cherry                    | 2         | 0.63%   |
| C3PO                      | 2         | 0.63%   |
| Aladdin Knowledge Systems | 2         | 0.63%   |
| Realtek Semiconductor     | 1         | 0.32%   |
| OmniKey                   | 1         | 0.32%   |
| Feitian Technologies      | 1         | 0.32%   |
| Chicony Electronics       | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 101       | 31.96%  |
| Broadcom 58200                                                               | 37        | 11.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 32        | 10.13%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 25        | 7.91%   |
| Broadcom 5880                                                                | 23        | 7.28%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 6.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 6.33%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.38%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.27%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.95%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.63%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.63%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.63%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.63%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.63%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.63%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.63%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.63%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.32%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.32%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.32%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.32%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.32%   |
| OmniKey CardMan 4321                                                         | 1         | 0.32%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.32%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.32%   |
| Feitian Technologies SCR301                                                  | 1         | 0.32%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.32%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.32%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.32%   |
| C3PO LTC31v2                                                                 | 1         | 0.32%   |
| C3PO KBR36                                                                   | 1         | 0.32%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4103      | 58.08%  |
| 1     | 2367      | 33.51%  |
| 2     | 469       | 6.64%   |
| 3     | 100       | 1.42%   |
| 4     | 18        | 0.25%   |
| 5     | 5         | 0.07%   |
| 7     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1528      | 43.48%  |
| Fingerprint reader       | 678       | 19.29%  |
| Net/wireless             | 314       | 8.94%   |
| Chipcard                 | 287       | 8.17%   |
| Multimedia controller    | 240       | 6.83%   |
| Communication controller | 139       | 3.96%   |
| Unassigned class         | 89        | 2.53%   |
| Bluetooth                | 51        | 1.45%   |
| Sound                    | 35        | 1%      |
| Camera                   | 33        | 0.94%   |
| Card reader              | 30        | 0.85%   |
| Storage                  | 26        | 0.74%   |
| Net/ethernet             | 20        | 0.57%   |
| Network                  | 10        | 0.28%   |
| Modem                    | 8         | 0.23%   |
| Storage/raid             | 7         | 0.2%    |
| Flash memory             | 6         | 0.17%   |
| Tv card                  | 5         | 0.14%   |
| Dvb card                 | 4         | 0.11%   |
| Firewire controller      | 2         | 0.06%   |
| Storage/nvme             | 1         | 0.03%   |
| Storage/ide              | 1         | 0.03%   |

