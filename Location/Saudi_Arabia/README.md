Linux in Saudi Arabia - Tested Hardware & Statistics
----------------------------------------------------

A project to collect tested hardware configurations for Linux in Saudi Arabia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Saudi_Arabia/Desktop/README.md) and [notebooks](/Location/Saudi_Arabia/Notebook/README.md).

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

Total: 974

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [cb5776f9a8](https://linux-hardware.org/?probe=cb5776f9a8) | Jan 03, 2026 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [e561e361ec](https://linux-hardware.org/?probe=e561e361ec) | Dec 30, 2025 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [1317e74deb](https://linux-hardware.org/?probe=1317e74deb) | Dec 29, 2025 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [dc36d440bb](https://linux-hardware.org/?probe=dc36d440bb) | Dec 25, 2025 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [a7dea29293](https://linux-hardware.org/?probe=a7dea29293) | Dec 23, 2025 |
| Dell          | Inspiron 5502               | Notebook    | [15831e2be1](https://linux-hardware.org/?probe=15831e2be1) | Dec 19, 2025 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [64fde17b91](https://linux-hardware.org/?probe=64fde17b91) | Dec 19, 2025 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e2823eeadf](https://linux-hardware.org/?probe=e2823eeadf) | Dec 18, 2025 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [6fddeef400](https://linux-hardware.org/?probe=6fddeef400) | Dec 18, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [6fa5ef928d](https://linux-hardware.org/?probe=6fa5ef928d) | Dec 17, 2025 |
| JGINYUE       | B650I Night Devil Ver:      | Desktop     | [47e8b9dad6](https://linux-hardware.org/?probe=47e8b9dad6) | Dec 17, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3e7855c339](https://linux-hardware.org/?probe=3e7855c339) | Dec 17, 2025 |
| Lenovo        | B590 20208                  | Notebook    | [bac5762ee0](https://linux-hardware.org/?probe=bac5762ee0) | Dec 16, 2025 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [ce5583c159](https://linux-hardware.org/?probe=ce5583c159) | Dec 13, 2025 |
| ASUSTek       | TUF Gaming B850-PLUS WIF... | Desktop     | [2e9c01e317](https://linux-hardware.org/?probe=2e9c01e317) | Dec 10, 2025 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [9453510f3c](https://linux-hardware.org/?probe=9453510f3c) | Dec 01, 2025 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [2b27f8c457](https://linux-hardware.org/?probe=2b27f8c457) | Nov 30, 2025 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a7283cf6b4](https://linux-hardware.org/?probe=a7283cf6b4) | Nov 30, 2025 |
| Unknown       | Unknown                     | Desktop     | [bf575de6f2](https://linux-hardware.org/?probe=bf575de6f2) | Nov 28, 2025 |
| Chuwi         | CoreBook X                  | Notebook    | [282e58959b](https://linux-hardware.org/?probe=282e58959b) | Nov 28, 2025 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [dd87497fa9](https://linux-hardware.org/?probe=dd87497fa9) | Nov 28, 2025 |
| Acer          | Aspire 5720                 | Notebook    | [1f2e40a1b7](https://linux-hardware.org/?probe=1f2e40a1b7) | Nov 24, 2025 |
| Lenovo        | ThinkPad E16 Gen 3 21SR0... | Notebook    | [e691ddb170](https://linux-hardware.org/?probe=e691ddb170) | Nov 23, 2025 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1c7f2cac4d](https://linux-hardware.org/?probe=1c7f2cac4d) | Nov 22, 2025 |
| Lenovo        | ThinkPad T490 20N2004HAD    | Notebook    | [673ef1ec1f](https://linux-hardware.org/?probe=673ef1ec1f) | Nov 20, 2025 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | Desktop     | [a9377fb2c0](https://linux-hardware.org/?probe=a9377fb2c0) | Nov 20, 2025 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | Desktop     | [64d351156c](https://linux-hardware.org/?probe=64d351156c) | Nov 20, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [d361aed273](https://linux-hardware.org/?probe=d361aed273) | Nov 20, 2025 |
| Lenovo        | B590 20208                  | Notebook    | [d07a89a846](https://linux-hardware.org/?probe=d07a89a846) | Nov 18, 2025 |
| HP            | 2ADC                        | Desktop     | [5f109faeb9](https://linux-hardware.org/?probe=5f109faeb9) | Nov 17, 2025 |
| Lenovo        | ThinkPad T490 20N2004HAD    | Notebook    | [50eec0b73e](https://linux-hardware.org/?probe=50eec0b73e) | Nov 14, 2025 |
| HP            | 2ADC                        | Desktop     | [8b4cc1e7d1](https://linux-hardware.org/?probe=8b4cc1e7d1) | Nov 13, 2025 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [510decf495](https://linux-hardware.org/?probe=510decf495) | Nov 11, 2025 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [8c13376341](https://linux-hardware.org/?probe=8c13376341) | Nov 10, 2025 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [023ffb5068](https://linux-hardware.org/?probe=023ffb5068) | Nov 08, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [e2633b4f8d](https://linux-hardware.org/?probe=e2633b4f8d) | Nov 08, 2025 |
| ASUSTek       | ROG STRIX B850-F GAMING ... | Desktop     | [75214de5d0](https://linux-hardware.org/?probe=75214de5d0) | Nov 07, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [ed18f9234f](https://linux-hardware.org/?probe=ed18f9234f) | Nov 06, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [0f47b7de62](https://linux-hardware.org/?probe=0f47b7de62) | Nov 06, 2025 |
| Huanan        | X99-QD4 V0.1 693H           | Desktop     | [9fedcc0184](https://linux-hardware.org/?probe=9fedcc0184) | Nov 02, 2025 |
| Dell          | 0K240Y A02                  | Desktop     | [1a9f5c2b8b](https://linux-hardware.org/?probe=1a9f5c2b8b) | Nov 02, 2025 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [15cc0edaaf](https://linux-hardware.org/?probe=15cc0edaaf) | Nov 01, 2025 |
| GMKtec        | NucBoxG9                    | Other       | [86d0cdc874](https://linux-hardware.org/?probe=86d0cdc874) | Oct 20, 2025 |
| Dell          | Precision 7530              | Notebook    | [20eaac1694](https://linux-hardware.org/?probe=20eaac1694) | Oct 20, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [0fbb2a9009](https://linux-hardware.org/?probe=0fbb2a9009) | Oct 18, 2025 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [575904142d](https://linux-hardware.org/?probe=575904142d) | Oct 17, 2025 |
| Alienware     | 17                          | Notebook    | [41c377766a](https://linux-hardware.org/?probe=41c377766a) | Oct 16, 2025 |
| Alienware     | 17                          | Notebook    | [85acbdc168](https://linux-hardware.org/?probe=85acbdc168) | Oct 16, 2025 |
| Alienware     | 17                          | Notebook    | [e304588bee](https://linux-hardware.org/?probe=e304588bee) | Oct 15, 2025 |
| Acer          | Aspire A514-54G             | Notebook    | [f1938fe030](https://linux-hardware.org/?probe=f1938fe030) | Oct 13, 2025 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [b7fdc100e3](https://linux-hardware.org/?probe=b7fdc100e3) | Oct 13, 2025 |
| Microsoft     | Surface Pro 7               | Tablet      | [57daa6f1c3](https://linux-hardware.org/?probe=57daa6f1c3) | Oct 12, 2025 |
| Microsoft     | Surface Pro 7               | Tablet      | [cecb3d08e6](https://linux-hardware.org/?probe=cecb3d08e6) | Oct 12, 2025 |
| Gigabyte      | X870 EAGLE WIFI7            | Desktop     | [734f0543c1](https://linux-hardware.org/?probe=734f0543c1) | Oct 10, 2025 |
| Dell          | Inspiron N5010              | Notebook    | [8a0914b2ef](https://linux-hardware.org/?probe=8a0914b2ef) | Oct 10, 2025 |
| Dell          | Inspiron N5010              | Notebook    | [db9fc8e121](https://linux-hardware.org/?probe=db9fc8e121) | Oct 10, 2025 |
| Gigabyte      | X870 EAGLE WIFI7            | Desktop     | [9cbf980c59](https://linux-hardware.org/?probe=9cbf980c59) | Oct 07, 2025 |
| Lenovo        | Yoga 7 2-in-1 14IML9 83D... | Convertible | [09f85a741e](https://linux-hardware.org/?probe=09f85a741e) | Oct 02, 2025 |
| HP            | ENVY x360 Convertible 13... | Convertible | [75b9983726](https://linux-hardware.org/?probe=75b9983726) | Sep 29, 2025 |
| Dell          | 06D7TR A00                  | Desktop     | [914857445a](https://linux-hardware.org/?probe=914857445a) | Sep 28, 2025 |
| HP            | 2ADC                        | Desktop     | [c664551bfb](https://linux-hardware.org/?probe=c664551bfb) | Sep 26, 2025 |
| ASUSTek       | PRIME H610M-A WIFI          | Desktop     | [db8969428a](https://linux-hardware.org/?probe=db8969428a) | Sep 24, 2025 |
| ASUSTek       | PRIME H610M-A WIFI          | Desktop     | [16366146d5](https://linux-hardware.org/?probe=16366146d5) | Sep 23, 2025 |
| Lenovo        | ThinkBook 16 G8 IAL 21SK    | Notebook    | [9f556131d6](https://linux-hardware.org/?probe=9f556131d6) | Sep 22, 2025 |
| Lenovo        | ThinkPad E590 20NB000JAD    | Notebook    | [9556c5e3c2](https://linux-hardware.org/?probe=9556c5e3c2) | Sep 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [bcc527075b](https://linux-hardware.org/?probe=bcc527075b) | Sep 19, 2025 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [b63b08e139](https://linux-hardware.org/?probe=b63b08e139) | Sep 16, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [aa5b87ace8](https://linux-hardware.org/?probe=aa5b87ace8) | Sep 14, 2025 |
| HP            | Pavilion 15                 | Notebook    | [5513973630](https://linux-hardware.org/?probe=5513973630) | Sep 13, 2025 |
| Dell          | 0VD92X A00                  | Desktop     | [f41b17f3f9](https://linux-hardware.org/?probe=f41b17f3f9) | Sep 12, 2025 |
| ASUSTek       | TUF Gaming B850M-PLUS WI... | Desktop     | [ceaaf8672c](https://linux-hardware.org/?probe=ceaaf8672c) | Sep 12, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [07b09aecb9](https://linux-hardware.org/?probe=07b09aecb9) | Sep 07, 2025 |
| MSI           | GS65 Stealth 9SF            | Notebook    | [1c5e8b3995](https://linux-hardware.org/?probe=1c5e8b3995) | Sep 06, 2025 |
| Lenovo        | B50-70 20384                | Notebook    | [e7fdb2b489](https://linux-hardware.org/?probe=e7fdb2b489) | Sep 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5cf11399ec](https://linux-hardware.org/?probe=5cf11399ec) | Sep 02, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [493b8cc21f](https://linux-hardware.org/?probe=493b8cc21f) | Sep 01, 2025 |
| Lenovo        | LOQ 16IRH8 82XW             | Notebook    | [ebf8932e28](https://linux-hardware.org/?probe=ebf8932e28) | Sep 01, 2025 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [e4b8646b35](https://linux-hardware.org/?probe=e4b8646b35) | Aug 29, 2025 |
| Google        | Kip                         | Notebook    | [87dcf77bce](https://linux-hardware.org/?probe=87dcf77bce) | Aug 28, 2025 |
| Valve         | Jupiter                     | Notebook    | [a41a595678](https://linux-hardware.org/?probe=a41a595678) | Aug 23, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [951264a489](https://linux-hardware.org/?probe=951264a489) | Aug 17, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [0be9c5498a](https://linux-hardware.org/?probe=0be9c5498a) | Aug 12, 2025 |
| ASUSTek       | ROG STRIX B850-F GAMING ... | Desktop     | [0d33552bee](https://linux-hardware.org/?probe=0d33552bee) | Aug 12, 2025 |
| Dell          | XPS 9320                    | Notebook    | [e0d00d14a6](https://linux-hardware.org/?probe=e0d00d14a6) | Aug 12, 2025 |
| Dell          | XPS 9320                    | Notebook    | [498cc6cd71](https://linux-hardware.org/?probe=498cc6cd71) | Aug 11, 2025 |
| Lenovo        | ThinkPad E590 20NB0004AD    | Notebook    | [0393c8e3e2](https://linux-hardware.org/?probe=0393c8e3e2) | Aug 11, 2025 |
| Lenovo        | ThinkPad E590 20NB0004AD    | Notebook    | [638208dd77](https://linux-hardware.org/?probe=638208dd77) | Aug 11, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [a7b501c083](https://linux-hardware.org/?probe=a7b501c083) | Aug 10, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [48afb96d3e](https://linux-hardware.org/?probe=48afb96d3e) | Aug 08, 2025 |
| Valve         | Jupiter                     | Notebook    | [80ed3c3f44](https://linux-hardware.org/?probe=80ed3c3f44) | Aug 08, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [4009991bb8](https://linux-hardware.org/?probe=4009991bb8) | Aug 05, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [aeff5dd520](https://linux-hardware.org/?probe=aeff5dd520) | Aug 05, 2025 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [41d7fdff87](https://linux-hardware.org/?probe=41d7fdff87) | Aug 04, 2025 |
| SDZ           | X133                        | Notebook    | [e81d516062](https://linux-hardware.org/?probe=e81d516062) | Jul 31, 2025 |
| Foxconn       | G31MX Series                | Desktop     | [0d64684506](https://linux-hardware.org/?probe=0d64684506) | Jul 28, 2025 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [e256561540](https://linux-hardware.org/?probe=e256561540) | Jul 27, 2025 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [d4a42ee7be](https://linux-hardware.org/?probe=d4a42ee7be) | Jul 20, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [41494d21b1](https://linux-hardware.org/?probe=41494d21b1) | Jul 19, 2025 |
| MSI           | Z390-A PRO                  | Desktop     | [9d16d99c79](https://linux-hardware.org/?probe=9d16d99c79) | Jul 19, 2025 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [e488610cdf](https://linux-hardware.org/?probe=e488610cdf) | Jul 19, 2025 |
| HP            | Laptop 15-da2xxx            | Notebook    | [93317be9bc](https://linux-hardware.org/?probe=93317be9bc) | Jul 16, 2025 |
| HP            | Laptop 15-da2xxx            | Notebook    | [0fed100f19](https://linux-hardware.org/?probe=0fed100f19) | Jul 15, 2025 |
| ASUSTek       | PRIME H610M-A WIFI          | Desktop     | [e45023a036](https://linux-hardware.org/?probe=e45023a036) | Jul 10, 2025 |
| Lenovo        | Yoga 7 2-in-1 14IML9 83D... | Convertible | [83698dbaed](https://linux-hardware.org/?probe=83698dbaed) | Jul 07, 2025 |
| Lenovo        | Yoga 7 2-in-1 14IML9 83D... | Convertible | [4244c45e9a](https://linux-hardware.org/?probe=4244c45e9a) | Jul 06, 2025 |
| AZW           | SER V01                     | Mini pc     | [a1f50b3fe4](https://linux-hardware.org/?probe=a1f50b3fe4) | Jul 05, 2025 |
| ASUSTek       | PRIME H610M-A WIFI          | Desktop     | [ebc1391cfe](https://linux-hardware.org/?probe=ebc1391cfe) | Jun 28, 2025 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [ed35501bf1](https://linux-hardware.org/?probe=ed35501bf1) | Jun 27, 2025 |
| HP            | Pavilion dv6                | Notebook    | [5702da4077](https://linux-hardware.org/?probe=5702da4077) | Jun 26, 2025 |
| Dell          | 0KRC95 A00                  | Desktop     | [2fe6a4f7a5](https://linux-hardware.org/?probe=2fe6a4f7a5) | Jun 25, 2025 |
| Valve         | Jupiter                     | Notebook    | [713e7d12b5](https://linux-hardware.org/?probe=713e7d12b5) | Jun 24, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Notebook    | [68054ca49f](https://linux-hardware.org/?probe=68054ca49f) | Jun 23, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Notebook    | [5e8b522b86](https://linux-hardware.org/?probe=5e8b522b86) | Jun 22, 2025 |
| ASUSTek       | PRIME X870-P WIFI           | Desktop     | [f0c49d6bf5](https://linux-hardware.org/?probe=f0c49d6bf5) | Jun 20, 2025 |
| ASUSTek       | PRIME X870-P WIFI           | Desktop     | [8172c02004](https://linux-hardware.org/?probe=8172c02004) | Jun 20, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | Notebook    | [b2a37a1a7a](https://linux-hardware.org/?probe=b2a37a1a7a) | Jun 15, 2025 |
| Dell          | Precision 5520              | Notebook    | [b191cdb6c9](https://linux-hardware.org/?probe=b191cdb6c9) | Jun 13, 2025 |
| MSI           | Cyborg 15 A13VF             | Notebook    | [ce6f30d3fd](https://linux-hardware.org/?probe=ce6f30d3fd) | Jun 09, 2025 |
| AZW           | SER V1.3                    | Mini pc     | [a9c555921d](https://linux-hardware.org/?probe=a9c555921d) | Jun 09, 2025 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [cd0eb7c1ca](https://linux-hardware.org/?probe=cd0eb7c1ca) | Jun 07, 2025 |
| AZW           | SER V1.3                    | Mini pc     | [caa0dfadc5](https://linux-hardware.org/?probe=caa0dfadc5) | Jun 06, 2025 |
| Microsoft     | Surface Pro 7               | Tablet      | [331e802224](https://linux-hardware.org/?probe=331e802224) | Jun 05, 2025 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [4d0a52853b](https://linux-hardware.org/?probe=4d0a52853b) | Jun 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [5211a5ca4d](https://linux-hardware.org/?probe=5211a5ca4d) | Jun 02, 2025 |
| Toshiba       | Satellite C55t-A            | Notebook    | [f65e2fefd1](https://linux-hardware.org/?probe=f65e2fefd1) | May 31, 2025 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [e8011c461c](https://linux-hardware.org/?probe=e8011c461c) | May 30, 2025 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [d3f950d157](https://linux-hardware.org/?probe=d3f950d157) | May 29, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [375b82e46e](https://linux-hardware.org/?probe=375b82e46e) | May 27, 2025 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [7c4874e6a8](https://linux-hardware.org/?probe=7c4874e6a8) | May 26, 2025 |
| Colorful T... | CVN B650M GAMING FROZEN ... | Desktop     | [75d154f967](https://linux-hardware.org/?probe=75d154f967) | May 21, 2025 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0499d451a8](https://linux-hardware.org/?probe=0499d451a8) | May 21, 2025 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [945b4c0478](https://linux-hardware.org/?probe=945b4c0478) | May 21, 2025 |
| Dell          | Inspiron 5521               | Notebook    | [ce7def4c08](https://linux-hardware.org/?probe=ce7def4c08) | May 21, 2025 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [9244e162d4](https://linux-hardware.org/?probe=9244e162d4) | May 18, 2025 |
| Microsoft     | Surface Pro 9               | Tablet      | [f145f748c7](https://linux-hardware.org/?probe=f145f748c7) | May 16, 2025 |
| AZW           | SER V1.3                    | Mini pc     | [c256863c15](https://linux-hardware.org/?probe=c256863c15) | May 12, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [075a0d49f0](https://linux-hardware.org/?probe=075a0d49f0) | May 08, 2025 |
| ASUSTek       | ROG STRIX B850-F GAMING ... | Desktop     | [b49df5fd48](https://linux-hardware.org/?probe=b49df5fd48) | May 07, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [bad6dbb459](https://linux-hardware.org/?probe=bad6dbb459) | May 07, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [40b8e0a08b](https://linux-hardware.org/?probe=40b8e0a08b) | May 07, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [afdcc4778d](https://linux-hardware.org/?probe=afdcc4778d) | May 07, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [08f098a164](https://linux-hardware.org/?probe=08f098a164) | May 07, 2025 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [9f3cbfbde7](https://linux-hardware.org/?probe=9f3cbfbde7) | May 06, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [d368236e4b](https://linux-hardware.org/?probe=d368236e4b) | May 02, 2025 |
| Dell          | Inspiron 1525               | Notebook    | [1d1cdbe295](https://linux-hardware.org/?probe=1d1cdbe295) | May 01, 2025 |
| Lenovo        | ThinkPad T480s 20L8SAWM0... | Notebook    | [eff24ac691](https://linux-hardware.org/?probe=eff24ac691) | May 01, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [58f0e59411](https://linux-hardware.org/?probe=58f0e59411) | Apr 28, 2025 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [6e493e3bd8](https://linux-hardware.org/?probe=6e493e3bd8) | Apr 28, 2025 |
| Acer          | Predator PO3-620            | Desktop     | [2a00ff8033](https://linux-hardware.org/?probe=2a00ff8033) | Apr 28, 2025 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [b8913f6e59](https://linux-hardware.org/?probe=b8913f6e59) | Apr 24, 2025 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [dab6be5281](https://linux-hardware.org/?probe=dab6be5281) | Apr 24, 2025 |
| Lenovo        | Yoga 7 2-in-1 14IML9 83D... | Convertible | [6b5feb6482](https://linux-hardware.org/?probe=6b5feb6482) | Apr 21, 2025 |
| Dell          | XPS 9320                    | Notebook    | [bd8b33fce4](https://linux-hardware.org/?probe=bd8b33fce4) | Apr 18, 2025 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [d80d33bd76](https://linux-hardware.org/?probe=d80d33bd76) | Apr 18, 2025 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [e604c5aa4e](https://linux-hardware.org/?probe=e604c5aa4e) | Apr 13, 2025 |
| HP            | Notebook                    | Notebook    | [4410242318](https://linux-hardware.org/?probe=4410242318) | Apr 12, 2025 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [89ef5631cd](https://linux-hardware.org/?probe=89ef5631cd) | Apr 11, 2025 |
| Valve         | Jupiter                     | Notebook    | [723f7ca000](https://linux-hardware.org/?probe=723f7ca000) | Apr 08, 2025 |
| Lenovo        | ThinkPad E15 20RD006BUS     | Notebook    | [73c9d22864](https://linux-hardware.org/?probe=73c9d22864) | Apr 05, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [0b06ba73f3](https://linux-hardware.org/?probe=0b06ba73f3) | Apr 05, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [4e95173a4f](https://linux-hardware.org/?probe=4e95173a4f) | Apr 04, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [572d7825a8](https://linux-hardware.org/?probe=572d7825a8) | Apr 03, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [df8c1a2ef1](https://linux-hardware.org/?probe=df8c1a2ef1) | Apr 02, 2025 |
| BESSTAR Te... | TH50                        | Desktop     | [48325b32e4](https://linux-hardware.org/?probe=48325b32e4) | Apr 02, 2025 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [5135dd34d9](https://linux-hardware.org/?probe=5135dd34d9) | Apr 01, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [63ee0ec5ca](https://linux-hardware.org/?probe=63ee0ec5ca) | Mar 25, 2025 |
| Dell          | Latitude 3420               | Notebook    | [4bbff0abc1](https://linux-hardware.org/?probe=4bbff0abc1) | Mar 24, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [01e1603835](https://linux-hardware.org/?probe=01e1603835) | Mar 24, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [a3cc7256a5](https://linux-hardware.org/?probe=a3cc7256a5) | Mar 24, 2025 |
| Valve         | Jupiter                     | Notebook    | [b05593e6d5](https://linux-hardware.org/?probe=b05593e6d5) | Mar 23, 2025 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [54f98b1b07](https://linux-hardware.org/?probe=54f98b1b07) | Mar 20, 2025 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [b0d18e7427](https://linux-hardware.org/?probe=b0d18e7427) | Mar 19, 2025 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [1e090c396f](https://linux-hardware.org/?probe=1e090c396f) | Mar 19, 2025 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [7f58b6a0a6](https://linux-hardware.org/?probe=7f58b6a0a6) | Mar 17, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [9214c6ae38](https://linux-hardware.org/?probe=9214c6ae38) | Mar 16, 2025 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [1c99c545b7](https://linux-hardware.org/?probe=1c99c545b7) | Mar 14, 2025 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | Desktop     | [bd0b1c2a0e](https://linux-hardware.org/?probe=bd0b1c2a0e) | Mar 08, 2025 |
| Unknown       | Unknown                     | Phone       | [aad41e6700](https://linux-hardware.org/?probe=aad41e6700) | Mar 07, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [6709bee986](https://linux-hardware.org/?probe=6709bee986) | Mar 06, 2025 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [7d9443d108](https://linux-hardware.org/?probe=7d9443d108) | Mar 04, 2025 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [90a77cddca](https://linux-hardware.org/?probe=90a77cddca) | Mar 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b17c6df945](https://linux-hardware.org/?probe=b17c6df945) | Mar 03, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [c54ac48db7](https://linux-hardware.org/?probe=c54ac48db7) | Mar 02, 2025 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7402e90fea](https://linux-hardware.org/?probe=7402e90fea) | Mar 01, 2025 |
| Gigabyte      | P35-DS3P                    | Desktop     | [c4bd97c371](https://linux-hardware.org/?probe=c4bd97c371) | Mar 01, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e02a9330a9](https://linux-hardware.org/?probe=e02a9330a9) | Feb 28, 2025 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [21289ee77c](https://linux-hardware.org/?probe=21289ee77c) | Feb 27, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [4c8865e3fa](https://linux-hardware.org/?probe=4c8865e3fa) | Feb 18, 2025 |
| HONOR         | MRA-XXX                     | Notebook    | [8d5d94f630](https://linux-hardware.org/?probe=8d5d94f630) | Feb 16, 2025 |
| HONOR         | MRA-XXX                     | Notebook    | [3de579a6e2](https://linux-hardware.org/?probe=3de579a6e2) | Feb 16, 2025 |
| Valve         | Jupiter                     | Notebook    | [21a54b2a07](https://linux-hardware.org/?probe=21a54b2a07) | Feb 13, 2025 |
| ASUSTek       | PRIME X299-A                | Desktop     | [c5282da1ed](https://linux-hardware.org/?probe=c5282da1ed) | Feb 12, 2025 |
| Dell          | Latitude E5450              | Notebook    | [d460f3428d](https://linux-hardware.org/?probe=d460f3428d) | Feb 12, 2025 |
| Toshiba       | Satellite P55W-C            | Notebook    | [4cdab63f23](https://linux-hardware.org/?probe=4cdab63f23) | Feb 09, 2025 |
| Lenovo        | Yoga 7 2-in-1 14IML9 83D... | Convertible | [6aed8d9351](https://linux-hardware.org/?probe=6aed8d9351) | Feb 06, 2025 |
| Lenovo        | Yoga 7 2-in-1 14IML9 83D... | Convertible | [eefae5d955](https://linux-hardware.org/?probe=eefae5d955) | Feb 06, 2025 |
| Dell          | 0X2MKR A00                  | All in one  | [3854592c00](https://linux-hardware.org/?probe=3854592c00) | Feb 05, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3ca16edf04](https://linux-hardware.org/?probe=3ca16edf04) | Feb 03, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e197c1d90d](https://linux-hardware.org/?probe=e197c1d90d) | Feb 02, 2025 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [9c8caeb6be](https://linux-hardware.org/?probe=9c8caeb6be) | Jan 29, 2025 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [dc7da8be63](https://linux-hardware.org/?probe=dc7da8be63) | Jan 28, 2025 |
| Nvidia        | Jetson AGX Orin Develope... | Soc         | [7dcafb0a15](https://linux-hardware.org/?probe=7dcafb0a15) | Jan 20, 2025 |
| HP            | 8767 A                      | Desktop     | [26ef978001](https://linux-hardware.org/?probe=26ef978001) | Jan 18, 2025 |
| HP            | 8767 A                      | Desktop     | [a241a5930d](https://linux-hardware.org/?probe=a241a5930d) | Jan 18, 2025 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [88879d2d45](https://linux-hardware.org/?probe=88879d2d45) | Jan 17, 2025 |
| ASUSTek       | Zenbook UX3402ZA            | Notebook    | [c39c41567b](https://linux-hardware.org/?probe=c39c41567b) | Jan 12, 2025 |
| Toshiba       | Satellite C40-A             | Notebook    | [5c3bd5d9ed](https://linux-hardware.org/?probe=5c3bd5d9ed) | Jan 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [e2e6a6d2fd](https://linux-hardware.org/?probe=e2e6a6d2fd) | Jan 09, 2025 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [5b784653f8](https://linux-hardware.org/?probe=5b784653f8) | Jan 08, 2025 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [4795563f56](https://linux-hardware.org/?probe=4795563f56) | Jan 06, 2025 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [dfee680354](https://linux-hardware.org/?probe=dfee680354) | Jan 06, 2025 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [de52972775](https://linux-hardware.org/?probe=de52972775) | Jan 05, 2025 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [d82c706a63](https://linux-hardware.org/?probe=d82c706a63) | Jan 05, 2025 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [f3f3a540d4](https://linux-hardware.org/?probe=f3f3a540d4) | Jan 02, 2025 |
| Lenovo        | ThinkPad Edge 0301FFG       | Notebook    | [526994e0a4](https://linux-hardware.org/?probe=526994e0a4) | Dec 31, 2024 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2bb09385c0](https://linux-hardware.org/?probe=2bb09385c0) | Dec 30, 2024 |
| ASUSTek       | PRIME H610M-K ARGB          | Desktop     | [8f2f1603ad](https://linux-hardware.org/?probe=8f2f1603ad) | Dec 29, 2024 |
| ASUSTek       | Zenbook UX3402ZA            | Notebook    | [be06529f29](https://linux-hardware.org/?probe=be06529f29) | Dec 28, 2024 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [b85d81f6b7](https://linux-hardware.org/?probe=b85d81f6b7) | Dec 28, 2024 |
| Lenovo        | ThinkPad T440s 20ARA000A... | Notebook    | [606caa4eb0](https://linux-hardware.org/?probe=606caa4eb0) | Dec 22, 2024 |
| Lenovo        | ThinkPad T440s 20ARA000A... | Notebook    | [813d572708](https://linux-hardware.org/?probe=813d572708) | Dec 22, 2024 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a5df0d3fd9](https://linux-hardware.org/?probe=a5df0d3fd9) | Dec 22, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [e4de3821da](https://linux-hardware.org/?probe=e4de3821da) | Dec 20, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [597e16ba37](https://linux-hardware.org/?probe=597e16ba37) | Dec 19, 2024 |
| Lenovo        | 10064                       | Desktop     | [b162e666ea](https://linux-hardware.org/?probe=b162e666ea) | Dec 15, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [c20e30f7fc](https://linux-hardware.org/?probe=c20e30f7fc) | Dec 13, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [f75f271653](https://linux-hardware.org/?probe=f75f271653) | Dec 03, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [841b30c302](https://linux-hardware.org/?probe=841b30c302) | Dec 03, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c56cdb7a5f](https://linux-hardware.org/?probe=c56cdb7a5f) | Nov 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [eaca726e51](https://linux-hardware.org/?probe=eaca726e51) | Nov 30, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [3d753784a0](https://linux-hardware.org/?probe=3d753784a0) | Nov 28, 2024 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [6ce6b8b12d](https://linux-hardware.org/?probe=6ce6b8b12d) | Nov 26, 2024 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [0671f8101c](https://linux-hardware.org/?probe=0671f8101c) | Nov 21, 2024 |
| HP            | Laptop 15g-br1xx            | Notebook    | [f51b7c2e9d](https://linux-hardware.org/?probe=f51b7c2e9d) | Nov 20, 2024 |
| Kllisre       | E5 F9 V1.0                  | Desktop     | [85d3fa537d](https://linux-hardware.org/?probe=85d3fa537d) | Nov 19, 2024 |
| Gigabyte      | Z790 A PRO X WIFI7          | Desktop     | [96214f288a](https://linux-hardware.org/?probe=96214f288a) | Nov 17, 2024 |
| HP            | ENVY x360 Convertible       | Convertible | [eaec9bbe9c](https://linux-hardware.org/?probe=eaec9bbe9c) | Nov 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [f811772f91](https://linux-hardware.org/?probe=f811772f91) | Nov 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [44366fc1ea](https://linux-hardware.org/?probe=44366fc1ea) | Nov 06, 2024 |
| Lenovo        | NOK                         | Desktop     | [ed6031b7a7](https://linux-hardware.org/?probe=ed6031b7a7) | Nov 06, 2024 |
| Toshiba       | Satellite P55W-C            | Notebook    | [84c58de68f](https://linux-hardware.org/?probe=84c58de68f) | Oct 23, 2024 |
| Toshiba       | Satellite P55W-C            | Notebook    | [2fbe7927f9](https://linux-hardware.org/?probe=2fbe7927f9) | Oct 23, 2024 |
| HP            | Laptop 15-da2xxx            | Notebook    | [2993fbf2fd](https://linux-hardware.org/?probe=2993fbf2fd) | Oct 23, 2024 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [38f8e57e3c](https://linux-hardware.org/?probe=38f8e57e3c) | Oct 18, 2024 |
| Dell          | 06D7TR A01                  | Desktop     | [4330cba698](https://linux-hardware.org/?probe=4330cba698) | Oct 18, 2024 |
| ASUSTek       | H170-PLUS D3                | Desktop     | [379530fc58](https://linux-hardware.org/?probe=379530fc58) | Oct 16, 2024 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [0e64ddf767](https://linux-hardware.org/?probe=0e64ddf767) | Oct 13, 2024 |
| Valve         | Jupiter                     | Notebook    | [2cc13c14ff](https://linux-hardware.org/?probe=2cc13c14ff) | Oct 11, 2024 |
| ASUSTek       | ASUS Zenbook Duo UX8406M... | Tablet      | [e3c86ca015](https://linux-hardware.org/?probe=e3c86ca015) | Oct 11, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [42d1b5a375](https://linux-hardware.org/?probe=42d1b5a375) | Oct 08, 2024 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [7ecac82228](https://linux-hardware.org/?probe=7ecac82228) | Oct 07, 2024 |
| Kllisre       | E5 F9 V1.0                  | Desktop     | [9db5e992cc](https://linux-hardware.org/?probe=9db5e992cc) | Oct 05, 2024 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [842009ca41](https://linux-hardware.org/?probe=842009ca41) | Sep 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [f497c7ae2d](https://linux-hardware.org/?probe=f497c7ae2d) | Sep 30, 2024 |
| TianBei       | GOD88                       | Desktop     | [14aaf1d0f2](https://linux-hardware.org/?probe=14aaf1d0f2) | Sep 27, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [ec357b358b](https://linux-hardware.org/?probe=ec357b358b) | Sep 24, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [ebda65fac2](https://linux-hardware.org/?probe=ebda65fac2) | Sep 23, 2024 |
| Lenovo        | ThinkPad P1 20MD001WUS      | Notebook    | [946c8f41c7](https://linux-hardware.org/?probe=946c8f41c7) | Sep 21, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [9978e53d19](https://linux-hardware.org/?probe=9978e53d19) | Sep 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [483fb4e9e2](https://linux-hardware.org/?probe=483fb4e9e2) | Sep 07, 2024 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [7b953a8f80](https://linux-hardware.org/?probe=7b953a8f80) | Sep 07, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [3d4ad593f5](https://linux-hardware.org/?probe=3d4ad593f5) | Sep 02, 2024 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [ee2689b4e0](https://linux-hardware.org/?probe=ee2689b4e0) | Aug 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5977adeb69](https://linux-hardware.org/?probe=5977adeb69) | Aug 27, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [affe4b35c6](https://linux-hardware.org/?probe=affe4b35c6) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [7a840c3125](https://linux-hardware.org/?probe=7a840c3125) | Aug 18, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d55a76a395](https://linux-hardware.org/?probe=d55a76a395) | Aug 17, 2024 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [ece6c56479](https://linux-hardware.org/?probe=ece6c56479) | Aug 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [752156b44a](https://linux-hardware.org/?probe=752156b44a) | Aug 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [8a69009d48](https://linux-hardware.org/?probe=8a69009d48) | Aug 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [fc2c81e0a1](https://linux-hardware.org/?probe=fc2c81e0a1) | Aug 11, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FD... | Notebook    | [ad6eb57434](https://linux-hardware.org/?probe=ad6eb57434) | Aug 09, 2024 |
| Dell          | 060K5C A06                  | Server      | [075693e3a5](https://linux-hardware.org/?probe=075693e3a5) | Aug 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9f1f1cd1fe](https://linux-hardware.org/?probe=9f1f1cd1fe) | Aug 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [637a30175e](https://linux-hardware.org/?probe=637a30175e) | Jul 28, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [2cb98cd569](https://linux-hardware.org/?probe=2cb98cd569) | Jul 27, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [ba13a043f7](https://linux-hardware.org/?probe=ba13a043f7) | Jul 25, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [8aec486e34](https://linux-hardware.org/?probe=8aec486e34) | Jul 25, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6e210dbe32](https://linux-hardware.org/?probe=6e210dbe32) | Jul 24, 2024 |
| Dell          | 060K5C A06                  | Server      | [5c5692ba57](https://linux-hardware.org/?probe=5c5692ba57) | Jul 24, 2024 |
| Fujitsu       | CELSIUS H730                | Notebook    | [0882a15af4](https://linux-hardware.org/?probe=0882a15af4) | Jul 23, 2024 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [f372a92cfa](https://linux-hardware.org/?probe=f372a92cfa) | Jul 21, 2024 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [8f97d0913c](https://linux-hardware.org/?probe=8f97d0913c) | Jul 20, 2024 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [78050f4878](https://linux-hardware.org/?probe=78050f4878) | Jul 20, 2024 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [1d6f70595c](https://linux-hardware.org/?probe=1d6f70595c) | Jul 19, 2024 |
| ASUSTek       | S550CM                      | Notebook    | [effe093e11](https://linux-hardware.org/?probe=effe093e11) | Jul 17, 2024 |
| Gigabyte      | P35-DS3P                    | Desktop     | [d4cfed27a4](https://linux-hardware.org/?probe=d4cfed27a4) | Jul 16, 2024 |
| Valve         | Galileo                     | Notebook    | [c81b1ef308](https://linux-hardware.org/?probe=c81b1ef308) | Jul 14, 2024 |
| Dell          | G3 3590                     | Notebook    | [df288cdcaf](https://linux-hardware.org/?probe=df288cdcaf) | Jul 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a7eb520a49](https://linux-hardware.org/?probe=a7eb520a49) | Jul 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [05aecfd062](https://linux-hardware.org/?probe=05aecfd062) | Jul 12, 2024 |
| Unknown       | HTC Corporation. MSM8996... | Phone       | [44a3c96a1c](https://linux-hardware.org/?probe=44a3c96a1c) | Jul 08, 2024 |
| Dell          | 0W0CHX A00                  | Desktop     | [8ae15789dd](https://linux-hardware.org/?probe=8ae15789dd) | Jul 08, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [5137ace569](https://linux-hardware.org/?probe=5137ace569) | Jul 08, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [2c427e70fd](https://linux-hardware.org/?probe=2c427e70fd) | Jul 08, 2024 |
| Dell          | 0W0CHX A00                  | Desktop     | [33d77003fc](https://linux-hardware.org/?probe=33d77003fc) | Jul 07, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [1ce1cc819a](https://linux-hardware.org/?probe=1ce1cc819a) | Jul 07, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [c4c28daaee](https://linux-hardware.org/?probe=c4c28daaee) | Jul 07, 2024 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [82d11210a6](https://linux-hardware.org/?probe=82d11210a6) | Jul 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [48b56d8828](https://linux-hardware.org/?probe=48b56d8828) | Jul 02, 2024 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [269dcf91b7](https://linux-hardware.org/?probe=269dcf91b7) | Jul 01, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [6aa7f99b04](https://linux-hardware.org/?probe=6aa7f99b04) | Jun 26, 2024 |
| Razer         | Blade Pro                   | Notebook    | [4e48c6dcde](https://linux-hardware.org/?probe=4e48c6dcde) | Jun 26, 2024 |
| ASRock        | B365M-HDV                   | Desktop     | [bc488687bd](https://linux-hardware.org/?probe=bc488687bd) | Jun 25, 2024 |
| ASRock        | B365M-HDV                   | Desktop     | [4a3bb5f053](https://linux-hardware.org/?probe=4a3bb5f053) | Jun 24, 2024 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [77158c1b27](https://linux-hardware.org/?probe=77158c1b27) | Jun 20, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [644863b6f9](https://linux-hardware.org/?probe=644863b6f9) | Jun 17, 2024 |
| I-Life Dig... | ZED AIR                     | Notebook    | [3d4f3140df](https://linux-hardware.org/?probe=3d4f3140df) | Jun 16, 2024 |
| I-Life Dig... | ZED AIR                     | Notebook    | [c62f439782](https://linux-hardware.org/?probe=c62f439782) | Jun 16, 2024 |
| HUAWEI        | KLVG-XX                     | Notebook    | [b1f7ffbf4a](https://linux-hardware.org/?probe=b1f7ffbf4a) | Jun 14, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE       | Desktop     | [996c152a67](https://linux-hardware.org/?probe=996c152a67) | Jun 12, 2024 |
| GEEKOM        | Mini IT13                   | Desktop     | [a77767e25f](https://linux-hardware.org/?probe=a77767e25f) | Jun 11, 2024 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [b95bd504a0](https://linux-hardware.org/?probe=b95bd504a0) | Jun 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e570948d49](https://linux-hardware.org/?probe=e570948d49) | Jun 10, 2024 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [1b867befe6](https://linux-hardware.org/?probe=1b867befe6) | Jun 10, 2024 |
| MSI           | Modern 14 B4MW              | Notebook    | [ed6e21156a](https://linux-hardware.org/?probe=ed6e21156a) | Jun 10, 2024 |
| HP            | Laptop 15-da2xxx            | Notebook    | [bcf8969f1e](https://linux-hardware.org/?probe=bcf8969f1e) | May 31, 2024 |
| HP            | 83E0                        | Desktop     | [add792a17a](https://linux-hardware.org/?probe=add792a17a) | May 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [44a1aa1433](https://linux-hardware.org/?probe=44a1aa1433) | May 27, 2024 |
| Valve         | Jupiter                     | Notebook    | [1ddb224c47](https://linux-hardware.org/?probe=1ddb224c47) | May 27, 2024 |
| Lenovo        | ThinkPad P50 20EQS3X10C     | Notebook    | [cfccc1ca5a](https://linux-hardware.org/?probe=cfccc1ca5a) | May 27, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [42ad45fdb0](https://linux-hardware.org/?probe=42ad45fdb0) | May 23, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3e96be14e5](https://linux-hardware.org/?probe=3e96be14e5) | May 23, 2024 |
| Lenovo        | ThinkPad P50 20EQS3X10C     | Notebook    | [2859984d97](https://linux-hardware.org/?probe=2859984d97) | May 19, 2024 |
| Valve         | Galileo                     | Notebook    | [1c500922b5](https://linux-hardware.org/?probe=1c500922b5) | May 19, 2024 |
| Valve         | Galileo                     | Notebook    | [9549cb7d85](https://linux-hardware.org/?probe=9549cb7d85) | May 19, 2024 |
| Valve         | Galileo                     | Notebook    | [a85c23cf18](https://linux-hardware.org/?probe=a85c23cf18) | May 19, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c12c2839cb](https://linux-hardware.org/?probe=c12c2839cb) | May 19, 2024 |
| Gigabyte      | Z77-D3H                     | Desktop     | [16824e390f](https://linux-hardware.org/?probe=16824e390f) | May 17, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [73bdf58ea3](https://linux-hardware.org/?probe=73bdf58ea3) | May 15, 2024 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [551dbd7ee2](https://linux-hardware.org/?probe=551dbd7ee2) | May 10, 2024 |
| HP            | Laptop 15-da2xxx            | Notebook    | [d553213278](https://linux-hardware.org/?probe=d553213278) | May 10, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [cf6fc980de](https://linux-hardware.org/?probe=cf6fc980de) | May 07, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3380a14ae9](https://linux-hardware.org/?probe=3380a14ae9) | May 02, 2024 |
| MSI           | GL75 Leopard 10SFK          | Notebook    | [2cde0c8054](https://linux-hardware.org/?probe=2cde0c8054) | Apr 28, 2024 |
| ASUSTek       | G20AJ                       | Desktop     | [bbb2ae3890](https://linux-hardware.org/?probe=bbb2ae3890) | Apr 20, 2024 |
| ASUSTek       | G20AJ                       | Desktop     | [f9741e3c18](https://linux-hardware.org/?probe=f9741e3c18) | Apr 20, 2024 |
| HP            | 2B38                        | Desktop     | [db7129fcde](https://linux-hardware.org/?probe=db7129fcde) | Apr 07, 2024 |
| HP            | 2B38                        | Desktop     | [44386f0027](https://linux-hardware.org/?probe=44386f0027) | Apr 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [8cd7c7653a](https://linux-hardware.org/?probe=8cd7c7653a) | Apr 07, 2024 |
| Lenovo        | B50-70 20384                | Notebook    | [f78c6087ac](https://linux-hardware.org/?probe=f78c6087ac) | Mar 31, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c5020d4c73](https://linux-hardware.org/?probe=c5020d4c73) | Mar 27, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1d78b76824](https://linux-hardware.org/?probe=1d78b76824) | Mar 27, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d11f38f81c](https://linux-hardware.org/?probe=d11f38f81c) | Mar 25, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f07c7e7a17](https://linux-hardware.org/?probe=f07c7e7a17) | Mar 23, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [4f1901506d](https://linux-hardware.org/?probe=4f1901506d) | Mar 22, 2024 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [c55cd9fbac](https://linux-hardware.org/?probe=c55cd9fbac) | Mar 22, 2024 |
| Gigabyte      | B760 DS3H DDR4              | Desktop     | [18eb8a593e](https://linux-hardware.org/?probe=18eb8a593e) | Mar 18, 2024 |
| Dell          | 0JCTF8 A00                  | Desktop     | [eb32037afd](https://linux-hardware.org/?probe=eb32037afd) | Mar 16, 2024 |
| Dell          | 0JCTF8 A00                  | Desktop     | [ff149982e7](https://linux-hardware.org/?probe=ff149982e7) | Mar 16, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [723f208e9b](https://linux-hardware.org/?probe=723f208e9b) | Mar 14, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [a3a7dd03fc](https://linux-hardware.org/?probe=a3a7dd03fc) | Mar 14, 2024 |
| MSI           | GF63 Thin 8SC               | Notebook    | [bbc6edbc2d](https://linux-hardware.org/?probe=bbc6edbc2d) | Mar 09, 2024 |
| ASUSTek       | GL552VX                     | Notebook    | [01ea0912c3](https://linux-hardware.org/?probe=01ea0912c3) | Mar 03, 2024 |
| Lenovo        | MAHOBAY                     | Desktop     | [ea1d8e1132](https://linux-hardware.org/?probe=ea1d8e1132) | Mar 03, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [094127d440](https://linux-hardware.org/?probe=094127d440) | Feb 26, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [adace6bd02](https://linux-hardware.org/?probe=adace6bd02) | Feb 22, 2024 |
| Dell          | Inspiron 3581               | Notebook    | [62a3c2b526](https://linux-hardware.org/?probe=62a3c2b526) | Feb 11, 2024 |
| HP            | 3648h                       | Desktop     | [96e8e58699](https://linux-hardware.org/?probe=96e8e58699) | Feb 11, 2024 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [7cd906021e](https://linux-hardware.org/?probe=7cd906021e) | Feb 07, 2024 |
| Lenovo        | Unknown                     | Notebook    | [46ccd12f05](https://linux-hardware.org/?probe=46ccd12f05) | Feb 04, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [37b70e517a](https://linux-hardware.org/?probe=37b70e517a) | Feb 03, 2024 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [bbc54bcc7c](https://linux-hardware.org/?probe=bbc54bcc7c) | Jan 27, 2024 |
| Dell          | Inspiron 3581               | Notebook    | [7a5cfbd8d3](https://linux-hardware.org/?probe=7a5cfbd8d3) | Jan 25, 2024 |
| Dell          | Inspiron 3581               | Notebook    | [dbf2745f1f](https://linux-hardware.org/?probe=dbf2745f1f) | Jan 25, 2024 |
| Lenovo        | 3740 NOK                    | Desktop     | [2bfb559750](https://linux-hardware.org/?probe=2bfb559750) | Jan 25, 2024 |
| Dell          | Latitude E5540              | Notebook    | [2e1716a6aa](https://linux-hardware.org/?probe=2e1716a6aa) | Jan 22, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [4d83b8cef9](https://linux-hardware.org/?probe=4d83b8cef9) | Jan 19, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [7f0443badf](https://linux-hardware.org/?probe=7f0443badf) | Jan 18, 2024 |
| Toshiba       | Satellite C850-B820         | Notebook    | [321a8ae666](https://linux-hardware.org/?probe=321a8ae666) | Jan 17, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | Desktop     | [803c2f0bd9](https://linux-hardware.org/?probe=803c2f0bd9) | Jan 16, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [a4afc8bb1f](https://linux-hardware.org/?probe=a4afc8bb1f) | Jan 12, 2024 |
| Lenovo        | MAHOBAY                     | Desktop     | [68a882e9f2](https://linux-hardware.org/?probe=68a882e9f2) | Jan 10, 2024 |
| HP            | 2215                        | Desktop     | [cea6ba103b](https://linux-hardware.org/?probe=cea6ba103b) | Jan 07, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e4ce5a17a5](https://linux-hardware.org/?probe=e4ce5a17a5) | Jan 05, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [4c587bc867](https://linux-hardware.org/?probe=4c587bc867) | Jan 04, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [debaccaee2](https://linux-hardware.org/?probe=debaccaee2) | Jan 04, 2024 |
| Dell          | G3 3590                     | Notebook    | [681f15e9c0](https://linux-hardware.org/?probe=681f15e9c0) | Dec 27, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [e778e7923a](https://linux-hardware.org/?probe=e778e7923a) | Dec 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b601b75917](https://linux-hardware.org/?probe=b601b75917) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [d52d7379c3](https://linux-hardware.org/?probe=d52d7379c3) | Dec 06, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [1f793dc2d3](https://linux-hardware.org/?probe=1f793dc2d3) | Nov 28, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [a48bfbc481](https://linux-hardware.org/?probe=a48bfbc481) | Nov 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [f009abd381](https://linux-hardware.org/?probe=f009abd381) | Nov 25, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [78992043bf](https://linux-hardware.org/?probe=78992043bf) | Nov 20, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f4c78fb767](https://linux-hardware.org/?probe=f4c78fb767) | Nov 19, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c845b4f25f](https://linux-hardware.org/?probe=c845b4f25f) | Nov 18, 2023 |
| Valve         | Jupiter                     | Notebook    | [97695463df](https://linux-hardware.org/?probe=97695463df) | Nov 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [8734420ff1](https://linux-hardware.org/?probe=8734420ff1) | Nov 17, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [9aa2678591](https://linux-hardware.org/?probe=9aa2678591) | Nov 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [6c51a94d03](https://linux-hardware.org/?probe=6c51a94d03) | Nov 15, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [d0f2727a4d](https://linux-hardware.org/?probe=d0f2727a4d) | Nov 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [e45cab7f2c](https://linux-hardware.org/?probe=e45cab7f2c) | Nov 12, 2023 |
| ASUSTek       | TUF H310-PLUS GAMING        | Desktop     | [b9e39aa8c1](https://linux-hardware.org/?probe=b9e39aa8c1) | Nov 10, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [02fa7cf5bb](https://linux-hardware.org/?probe=02fa7cf5bb) | Nov 03, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [3e7da65a41](https://linux-hardware.org/?probe=3e7da65a41) | Oct 27, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [6b9e5b921c](https://linux-hardware.org/?probe=6b9e5b921c) | Oct 27, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [5236a2eca3](https://linux-hardware.org/?probe=5236a2eca3) | Oct 26, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [6f746b3af3](https://linux-hardware.org/?probe=6f746b3af3) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [a9dd51be33](https://linux-hardware.org/?probe=a9dd51be33) | Oct 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [08387f2a94](https://linux-hardware.org/?probe=08387f2a94) | Oct 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e2b8718a7d](https://linux-hardware.org/?probe=e2b8718a7d) | Oct 19, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [81c485dfbe](https://linux-hardware.org/?probe=81c485dfbe) | Oct 16, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [6b86dab25f](https://linux-hardware.org/?probe=6b86dab25f) | Oct 16, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e29f6e9ba8](https://linux-hardware.org/?probe=e29f6e9ba8) | Oct 11, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [98784d1e51](https://linux-hardware.org/?probe=98784d1e51) | Oct 08, 2023 |
| Dynabook      | PORTEGE X30W-J              | Convertible | [aa212009a2](https://linux-hardware.org/?probe=aa212009a2) | Oct 06, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e1f02c6934](https://linux-hardware.org/?probe=e1f02c6934) | Oct 03, 2023 |
| HP            | ProBook 6560b               | Notebook    | [c4710bf9c2](https://linux-hardware.org/?probe=c4710bf9c2) | Oct 01, 2023 |
| HP            | 3397                        | Desktop     | [5740126c3c](https://linux-hardware.org/?probe=5740126c3c) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [683cbd037a](https://linux-hardware.org/?probe=683cbd037a) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8064cec888](https://linux-hardware.org/?probe=8064cec888) | Sep 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [7cdaac7be4](https://linux-hardware.org/?probe=7cdaac7be4) | Sep 16, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [192e02b434](https://linux-hardware.org/?probe=192e02b434) | Sep 15, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [b06966adc5](https://linux-hardware.org/?probe=b06966adc5) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [9f459c45cc](https://linux-hardware.org/?probe=9f459c45cc) | Sep 14, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [40df085797](https://linux-hardware.org/?probe=40df085797) | Sep 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [78f326afa5](https://linux-hardware.org/?probe=78f326afa5) | Sep 12, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f913de368f](https://linux-hardware.org/?probe=f913de368f) | Sep 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [423b8d7135](https://linux-hardware.org/?probe=423b8d7135) | Sep 07, 2023 |
| HP            | 3397                        | Desktop     | [b9dabe8514](https://linux-hardware.org/?probe=b9dabe8514) | Aug 31, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [dc63902a68](https://linux-hardware.org/?probe=dc63902a68) | Aug 31, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [082e1c2cc1](https://linux-hardware.org/?probe=082e1c2cc1) | Aug 24, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [b1beaf9e38](https://linux-hardware.org/?probe=b1beaf9e38) | Aug 22, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [088582c57c](https://linux-hardware.org/?probe=088582c57c) | Aug 15, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [4587b7ff26](https://linux-hardware.org/?probe=4587b7ff26) | Aug 14, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| Lenovo        | ThinkPad X1 Yoga 20FRS02... | Convertible | [ba520853af](https://linux-hardware.org/?probe=ba520853af) | Aug 10, 2023 |
| Lenovo        | ThinkPad X1 Yoga 20FRS02... | Convertible | [534fd57945](https://linux-hardware.org/?probe=534fd57945) | Aug 10, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | 3397                        | Desktop     | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [ebf45c27f4](https://linux-hardware.org/?probe=ebf45c27f4) | Aug 07, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [221f9de00a](https://linux-hardware.org/?probe=221f9de00a) | Aug 06, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ea70e92c9a](https://linux-hardware.org/?probe=ea70e92c9a) | Aug 05, 2023 |
| GIADA         | Unknown                     | Notebook    | [cd8b23468a](https://linux-hardware.org/?probe=cd8b23468a) | Aug 03, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [9dcbf7b10c](https://linux-hardware.org/?probe=9dcbf7b10c) | Aug 03, 2023 |
| Toshiba       | Satellite C850-B239         | Notebook    | [a075f60c70](https://linux-hardware.org/?probe=a075f60c70) | Aug 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [570c98e6ab](https://linux-hardware.org/?probe=570c98e6ab) | Aug 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [f54f3f3a4b](https://linux-hardware.org/?probe=f54f3f3a4b) | Aug 01, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70b94de26b](https://linux-hardware.org/?probe=70b94de26b) | Jul 31, 2023 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [42b35cd473](https://linux-hardware.org/?probe=42b35cd473) | Jul 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [fc294ac015](https://linux-hardware.org/?probe=fc294ac015) | Jul 27, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [9e156dd92f](https://linux-hardware.org/?probe=9e156dd92f) | Jul 26, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [35f41c1327](https://linux-hardware.org/?probe=35f41c1327) | Jul 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f371e0efe5](https://linux-hardware.org/?probe=f371e0efe5) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [55639a6416](https://linux-hardware.org/?probe=55639a6416) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8b2077101c](https://linux-hardware.org/?probe=8b2077101c) | Jul 21, 2023 |
| ASUSTek       | H81M-V3                     | Desktop     | [017671472c](https://linux-hardware.org/?probe=017671472c) | Jul 15, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [adf89d2bba](https://linux-hardware.org/?probe=adf89d2bba) | Jul 12, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [35f03cf89f](https://linux-hardware.org/?probe=35f03cf89f) | Jul 10, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b6c778034c](https://linux-hardware.org/?probe=b6c778034c) | Jul 06, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [4d8e159540](https://linux-hardware.org/?probe=4d8e159540) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b7222ef19f](https://linux-hardware.org/?probe=b7222ef19f) | Jul 03, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [6dbef58b31](https://linux-hardware.org/?probe=6dbef58b31) | Jul 02, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [4e2b34c387](https://linux-hardware.org/?probe=4e2b34c387) | Jul 02, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [02a31c9704](https://linux-hardware.org/?probe=02a31c9704) | Jul 01, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [45739a208c](https://linux-hardware.org/?probe=45739a208c) | Jul 01, 2023 |
| Dell          | Latitude 3520               | Notebook    | [6e996e08f9](https://linux-hardware.org/?probe=6e996e08f9) | Jul 01, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c3ae8b2d38](https://linux-hardware.org/?probe=c3ae8b2d38) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [39ec9cf6c4](https://linux-hardware.org/?probe=39ec9cf6c4) | Jun 27, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [dff301aade](https://linux-hardware.org/?probe=dff301aade) | Jun 25, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [c756e98d81](https://linux-hardware.org/?probe=c756e98d81) | Jun 24, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [874b84ce94](https://linux-hardware.org/?probe=874b84ce94) | Jun 24, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [4f0ec49165](https://linux-hardware.org/?probe=4f0ec49165) | Jun 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7da8691a87](https://linux-hardware.org/?probe=7da8691a87) | Jun 17, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [436b4c3ab9](https://linux-hardware.org/?probe=436b4c3ab9) | Jun 16, 2023 |
| DJI           | MANIFOLD 2-C                | Desktop     | [44edfc848e](https://linux-hardware.org/?probe=44edfc848e) | Jun 13, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [5bc14dc937](https://linux-hardware.org/?probe=5bc14dc937) | Jun 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c9765a31c](https://linux-hardware.org/?probe=8c9765a31c) | Jun 11, 2023 |
| Toshiba       | Satellite L635              | Notebook    | [4f124d1525](https://linux-hardware.org/?probe=4f124d1525) | Jun 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [d21eb9432c](https://linux-hardware.org/?probe=d21eb9432c) | Jun 03, 2023 |
| Gigabyte      | P75-D3                      | Desktop     | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| Dell          | XPS 15 9575                 | Convertible | [bed704ac70](https://linux-hardware.org/?probe=bed704ac70) | May 27, 2023 |
| Dell          | Latitude E6520              | Notebook    | [bb8bc9b8ae](https://linux-hardware.org/?probe=bb8bc9b8ae) | May 24, 2023 |
| Google        | Akemi                       | Notebook    | [595f8b1a24](https://linux-hardware.org/?probe=595f8b1a24) | May 20, 2023 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [0d337f6d69](https://linux-hardware.org/?probe=0d337f6d69) | May 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [93979d632e](https://linux-hardware.org/?probe=93979d632e) | May 15, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [155b921e10](https://linux-hardware.org/?probe=155b921e10) | May 13, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [de65a79bf1](https://linux-hardware.org/?probe=de65a79bf1) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [4b76463d57](https://linux-hardware.org/?probe=4b76463d57) | May 06, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [3da35d8bc2](https://linux-hardware.org/?probe=3da35d8bc2) | May 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ae500cf4af](https://linux-hardware.org/?probe=ae500cf4af) | Apr 22, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [4b338ba7f9](https://linux-hardware.org/?probe=4b338ba7f9) | Apr 15, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [84c8a107d4](https://linux-hardware.org/?probe=84c8a107d4) | Apr 06, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [39e1087c79](https://linux-hardware.org/?probe=39e1087c79) | Apr 04, 2023 |
| Dell          | Latitude 7275               | Tablet      | [c118ca04bc](https://linux-hardware.org/?probe=c118ca04bc) | Apr 01, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [46dc3b9655](https://linux-hardware.org/?probe=46dc3b9655) | Mar 31, 2023 |
| ASUSTek       | H81M-V3                     | Desktop     | [fd123bea36](https://linux-hardware.org/?probe=fd123bea36) | Mar 29, 2023 |
| ASUSTek       | H81M-V3                     | Desktop     | [ce98454e55](https://linux-hardware.org/?probe=ce98454e55) | Mar 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [70e9f673c2](https://linux-hardware.org/?probe=70e9f673c2) | Mar 23, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70a7fd895e](https://linux-hardware.org/?probe=70a7fd895e) | Mar 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ca34d8e7d4](https://linux-hardware.org/?probe=ca34d8e7d4) | Mar 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [9509c77e2b](https://linux-hardware.org/?probe=9509c77e2b) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [70e1aa9793](https://linux-hardware.org/?probe=70e1aa9793) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Sony          | VGN-FZ250E                  | Notebook    | [ca7937209b](https://linux-hardware.org/?probe=ca7937209b) | Mar 06, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [82889a28a0](https://linux-hardware.org/?probe=82889a28a0) | Feb 23, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [27f07447f7](https://linux-hardware.org/?probe=27f07447f7) | Feb 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [76cbc7df6d](https://linux-hardware.org/?probe=76cbc7df6d) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [e70b65f78d](https://linux-hardware.org/?probe=e70b65f78d) | Feb 20, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [61befa2690](https://linux-hardware.org/?probe=61befa2690) | Feb 18, 2023 |
| Dell          | Latitude E6520              | Notebook    | [b04c6e8984](https://linux-hardware.org/?probe=b04c6e8984) | Feb 18, 2023 |
| HP            | 8053                        | Desktop     | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| HUAWEI        | MateBook E                  | Tablet      | [072689df7b](https://linux-hardware.org/?probe=072689df7b) | Feb 13, 2023 |
| HUAWEI        | MateBook E                  | Tablet      | [a31eb3e8aa](https://linux-hardware.org/?probe=a31eb3e8aa) | Feb 13, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c4eb0b2a62](https://linux-hardware.org/?probe=c4eb0b2a62) | Feb 11, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [dba0167a53](https://linux-hardware.org/?probe=dba0167a53) | Feb 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [ad403b2126](https://linux-hardware.org/?probe=ad403b2126) | Feb 09, 2023 |
| Medion        | MS-7797                     | Desktop     | [3421cd9be4](https://linux-hardware.org/?probe=3421cd9be4) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e931084a7](https://linux-hardware.org/?probe=0e931084a7) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5566e6facb](https://linux-hardware.org/?probe=5566e6facb) | Feb 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6c1ee5e95d](https://linux-hardware.org/?probe=6c1ee5e95d) | Feb 04, 2023 |
| Unknown       | 1.0                         | Desktop     | [402bce9e43](https://linux-hardware.org/?probe=402bce9e43) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bd0b1f7e94](https://linux-hardware.org/?probe=bd0b1f7e94) | Jan 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [a22071f9ec](https://linux-hardware.org/?probe=a22071f9ec) | Jan 26, 2023 |
| Unknown       | 1.0                         | Desktop     | [85d36881c1](https://linux-hardware.org/?probe=85d36881c1) | Jan 26, 2023 |
| Unknown       | 1.0                         | Desktop     | [a25e1d1008](https://linux-hardware.org/?probe=a25e1d1008) | Jan 26, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [70559c048c](https://linux-hardware.org/?probe=70559c048c) | Jan 25, 2023 |
| Unknown       | 1.0                         | Desktop     | [99201dd05a](https://linux-hardware.org/?probe=99201dd05a) | Jan 24, 2023 |
| Unknown       | 1.0                         | Desktop     | [678e6d3875](https://linux-hardware.org/?probe=678e6d3875) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [476d23dca7](https://linux-hardware.org/?probe=476d23dca7) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| HUAWEI        | MateBook E                  | Tablet      | [8298edf3bc](https://linux-hardware.org/?probe=8298edf3bc) | Jan 19, 2023 |
| HP            | Unknown                     | Notebook    | [fedf225852](https://linux-hardware.org/?probe=fedf225852) | Jan 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| HP            | Unknown                     | Notebook    | [8b89da1da5](https://linux-hardware.org/?probe=8b89da1da5) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [b927a3e937](https://linux-hardware.org/?probe=b927a3e937) | Jan 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [2b476ca470](https://linux-hardware.org/?probe=2b476ca470) | Jan 16, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [b69b2d21e9](https://linux-hardware.org/?probe=b69b2d21e9) | Jan 15, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [26379f8b8d](https://linux-hardware.org/?probe=26379f8b8d) | Jan 11, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [71d684a605](https://linux-hardware.org/?probe=71d684a605) | Jan 11, 2023 |
| Toshiba       | Satellite C850-B561         | Notebook    | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [5ac16a435c](https://linux-hardware.org/?probe=5ac16a435c) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [e662d0e58a](https://linux-hardware.org/?probe=e662d0e58a) | Jan 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2c6b6c2558](https://linux-hardware.org/?probe=2c6b6c2558) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [3a801b9e90](https://linux-hardware.org/?probe=3a801b9e90) | Jan 01, 2023 |
| Acer          | Spin SP513-54N              | Convertible | [0cb6dfa7ce](https://linux-hardware.org/?probe=0cb6dfa7ce) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [eeec310401](https://linux-hardware.org/?probe=eeec310401) | Dec 26, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [13d0daca4c](https://linux-hardware.org/?probe=13d0daca4c) | Dec 23, 2022 |
| HP            | 212B                        | Desktop     | [3df121c98b](https://linux-hardware.org/?probe=3df121c98b) | Dec 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [42584fd968](https://linux-hardware.org/?probe=42584fd968) | Dec 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [eb95cbbbe0](https://linux-hardware.org/?probe=eb95cbbbe0) | Dec 03, 2022 |
| Toshiba       | Satellite L635              | Notebook    | [be223c0ff1](https://linux-hardware.org/?probe=be223c0ff1) | Dec 03, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [a92a0830e9](https://linux-hardware.org/?probe=a92a0830e9) | Nov 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| HP            | 212B                        | Desktop     | [d5cc313fba](https://linux-hardware.org/?probe=d5cc313fba) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4c0e49ae2b](https://linux-hardware.org/?probe=4c0e49ae2b) | Oct 23, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [3e86b56fb8](https://linux-hardware.org/?probe=3e86b56fb8) | Oct 23, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [7f90427c64](https://linux-hardware.org/?probe=7f90427c64) | Oct 15, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f7f3439df7](https://linux-hardware.org/?probe=f7f3439df7) | Oct 11, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [61f05a7c32](https://linux-hardware.org/?probe=61f05a7c32) | Oct 10, 2022 |
| Sony          | SVF15A13SAB                 | Notebook    | [7c39add556](https://linux-hardware.org/?probe=7c39add556) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [de59de7b14](https://linux-hardware.org/?probe=de59de7b14) | Oct 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [bf7151a851](https://linux-hardware.org/?probe=bf7151a851) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| Dell          | G15 5515                    | Notebook    | [ae769dae75](https://linux-hardware.org/?probe=ae769dae75) | Sep 24, 2022 |
| Dell          | G15 5515                    | Notebook    | [893c248dec](https://linux-hardware.org/?probe=893c248dec) | Sep 24, 2022 |
| Dell          | G15 5515                    | Notebook    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a934e23e1f](https://linux-hardware.org/?probe=a934e23e1f) | Sep 16, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c65050e714](https://linux-hardware.org/?probe=c65050e714) | Sep 09, 2022 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [8373c5268a](https://linux-hardware.org/?probe=8373c5268a) | Sep 05, 2022 |
| Dell          | Latitude 7275               | Tablet      | [fce77a6b4b](https://linux-hardware.org/?probe=fce77a6b4b) | Aug 31, 2022 |
| Dell          | Latitude 7275               | Tablet      | [896ceefe29](https://linux-hardware.org/?probe=896ceefe29) | Aug 31, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [b87b0407d9](https://linux-hardware.org/?probe=b87b0407d9) | Aug 29, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [fbb579a5d6](https://linux-hardware.org/?probe=fbb579a5d6) | Aug 29, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [4ecdbb8b4b](https://linux-hardware.org/?probe=4ecdbb8b4b) | Aug 15, 2022 |
| Acer          | Aspire 4752                 | Notebook    | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [154440549c](https://linux-hardware.org/?probe=154440549c) | Aug 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [4f12a5e11e](https://linux-hardware.org/?probe=4f12a5e11e) | Aug 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ed6b6ce93e](https://linux-hardware.org/?probe=ed6b6ce93e) | Aug 03, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [1364037a8f](https://linux-hardware.org/?probe=1364037a8f) | Aug 01, 2022 |
| eMachines     | Unknown                     | Notebook    | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [1ff4c1d5df](https://linux-hardware.org/?probe=1ff4c1d5df) | Jul 10, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [5082bf92e9](https://linux-hardware.org/?probe=5082bf92e9) | Jun 26, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [d0edbadf25](https://linux-hardware.org/?probe=d0edbadf25) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [b7a6099e25](https://linux-hardware.org/?probe=b7a6099e25) | Jun 20, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [4f3e4e102f](https://linux-hardware.org/?probe=4f3e4e102f) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [550ed4b1c0](https://linux-hardware.org/?probe=550ed4b1c0) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [e6e0165682](https://linux-hardware.org/?probe=e6e0165682) | Jun 14, 2022 |
| Dell          | 06WXJT A02                  | Server      | [2dfd532279](https://linux-hardware.org/?probe=2dfd532279) | Jun 08, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [870c420b4b](https://linux-hardware.org/?probe=870c420b4b) | Jun 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [34a1b11f96](https://linux-hardware.org/?probe=34a1b11f96) | Jun 02, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d7d06bf7ef](https://linux-hardware.org/?probe=d7d06bf7ef) | May 26, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [da5f6c9ba0](https://linux-hardware.org/?probe=da5f6c9ba0) | May 23, 2022 |
| MSI           | GF63 Thin 8RCS              | Notebook    | [8cd1ebfa12](https://linux-hardware.org/?probe=8cd1ebfa12) | May 22, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c34e9b0da7](https://linux-hardware.org/?probe=c34e9b0da7) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [b6dc8a3fc8](https://linux-hardware.org/?probe=b6dc8a3fc8) | May 05, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [51d4e9a2e2](https://linux-hardware.org/?probe=51d4e9a2e2) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| Dell          | 0M9KCM A01                  | Desktop     | [76d9159d32](https://linux-hardware.org/?probe=76d9159d32) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [794ab7ba41](https://linux-hardware.org/?probe=794ab7ba41) | Apr 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [b7443972f3](https://linux-hardware.org/?probe=b7443972f3) | Apr 28, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [037284e799](https://linux-hardware.org/?probe=037284e799) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8c3b142c85](https://linux-hardware.org/?probe=8c3b142c85) | Apr 23, 2022 |
| Dell          | Latitude 7275               | Tablet      | [8b373dc563](https://linux-hardware.org/?probe=8b373dc563) | Apr 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [14fa81fab9](https://linux-hardware.org/?probe=14fa81fab9) | Apr 18, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [196f849315](https://linux-hardware.org/?probe=196f849315) | Apr 18, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [0c294047d9](https://linux-hardware.org/?probe=0c294047d9) | Apr 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [50c38c2cc6](https://linux-hardware.org/?probe=50c38c2cc6) | Apr 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [1f799cdbef](https://linux-hardware.org/?probe=1f799cdbef) | Apr 09, 2022 |
| Unknown       | HX90                        | Desktop     | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [45548a6fe5](https://linux-hardware.org/?probe=45548a6fe5) | Apr 07, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [1f1a2dbacc](https://linux-hardware.org/?probe=1f1a2dbacc) | Apr 05, 2022 |
| Dell          | Latitude 7275               | Tablet      | [4e3f9ca88e](https://linux-hardware.org/?probe=4e3f9ca88e) | Apr 02, 2022 |
| Unknown       | HX90                        | Desktop     | [9cb3335bb0](https://linux-hardware.org/?probe=9cb3335bb0) | Apr 01, 2022 |
| Unknown       | HX90                        | Desktop     | [cd18483c45](https://linux-hardware.org/?probe=cd18483c45) | Apr 01, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [464e58f41f](https://linux-hardware.org/?probe=464e58f41f) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [567627010e](https://linux-hardware.org/?probe=567627010e) | Mar 29, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [304f31d5a7](https://linux-hardware.org/?probe=304f31d5a7) | Mar 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bc999f46f9](https://linux-hardware.org/?probe=bc999f46f9) | Mar 28, 2022 |
| Dell          | Latitude 7275               | Tablet      | [1e0ad3b3cd](https://linux-hardware.org/?probe=1e0ad3b3cd) | Mar 27, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [0e1e24ffe0](https://linux-hardware.org/?probe=0e1e24ffe0) | Mar 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [50131c5da4](https://linux-hardware.org/?probe=50131c5da4) | Mar 21, 2022 |
| Acer          | AO751h                      | Notebook    | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [1f00b8ed57](https://linux-hardware.org/?probe=1f00b8ed57) | Mar 21, 2022 |
| Acer          | AO751h                      | Notebook    | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [d52410b817](https://linux-hardware.org/?probe=d52410b817) | Mar 18, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [08239c1637](https://linux-hardware.org/?probe=08239c1637) | Mar 09, 2022 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ce709ce28f](https://linux-hardware.org/?probe=ce709ce28f) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b2f7222ddb](https://linux-hardware.org/?probe=b2f7222ddb) | Feb 27, 2022 |
| Dell          | 0WWJRX A00                  | Desktop     | [bb620cc0f9](https://linux-hardware.org/?probe=bb620cc0f9) | Feb 26, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [007ec5dbf5](https://linux-hardware.org/?probe=007ec5dbf5) | Feb 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [14bcc9219c](https://linux-hardware.org/?probe=14bcc9219c) | Feb 18, 2022 |
| Dell          | Latitude 7275               | Tablet      | [143e5a0a20](https://linux-hardware.org/?probe=143e5a0a20) | Feb 16, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [43b019326c](https://linux-hardware.org/?probe=43b019326c) | Feb 12, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [70f23c3da0](https://linux-hardware.org/?probe=70f23c3da0) | Feb 12, 2022 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [fe9b9a47f1](https://linux-hardware.org/?probe=fe9b9a47f1) | Feb 11, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [73767731d9](https://linux-hardware.org/?probe=73767731d9) | Feb 11, 2022 |
| ASRock        | B365M Phantom Gaming 4      | Desktop     | [9dd59e5403](https://linux-hardware.org/?probe=9dd59e5403) | Feb 08, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e0748343d9](https://linux-hardware.org/?probe=e0748343d9) | Feb 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| HP            | 15                          | Notebook    | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [92f528e80b](https://linux-hardware.org/?probe=92f528e80b) | Jan 13, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [06673a4f1e](https://linux-hardware.org/?probe=06673a4f1e) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [5f7b4e3335](https://linux-hardware.org/?probe=5f7b4e3335) | Jan 12, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [ebd229b5fb](https://linux-hardware.org/?probe=ebd229b5fb) | Jan 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [4debe87ebd](https://linux-hardware.org/?probe=4debe87ebd) | Jan 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [261fe8bda7](https://linux-hardware.org/?probe=261fe8bda7) | Jan 07, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [85f4fcc0b6](https://linux-hardware.org/?probe=85f4fcc0b6) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [f69299cbfb](https://linux-hardware.org/?probe=f69299cbfb) | Jan 03, 2022 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [3fbda09d01](https://linux-hardware.org/?probe=3fbda09d01) | Jan 01, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [be19f6df45](https://linux-hardware.org/?probe=be19f6df45) | Dec 29, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Packard Be... | EasyNote TJ65               | Notebook    | [b98b9252fa](https://linux-hardware.org/?probe=b98b9252fa) | Dec 29, 2021 |
| MSI           | MS-7529                     | Desktop     | [c9b87dcf45](https://linux-hardware.org/?probe=c9b87dcf45) | Dec 27, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [938d24e76e](https://linux-hardware.org/?probe=938d24e76e) | Dec 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [046dcdd20d](https://linux-hardware.org/?probe=046dcdd20d) | Dec 25, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [af71cff698](https://linux-hardware.org/?probe=af71cff698) | Dec 21, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [609baca194](https://linux-hardware.org/?probe=609baca194) | Dec 16, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [35ec8b1dbb](https://linux-hardware.org/?probe=35ec8b1dbb) | Dec 16, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f73c5829df](https://linux-hardware.org/?probe=f73c5829df) | Dec 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [bb9141f09c](https://linux-hardware.org/?probe=bb9141f09c) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b3c42ca2c2](https://linux-hardware.org/?probe=b3c42ca2c2) | Dec 09, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [2a151de62b](https://linux-hardware.org/?probe=2a151de62b) | Dec 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [830882c4e6](https://linux-hardware.org/?probe=830882c4e6) | Dec 07, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [25ca2e2c75](https://linux-hardware.org/?probe=25ca2e2c75) | Dec 04, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [5cc2fbfef5](https://linux-hardware.org/?probe=5cc2fbfef5) | Dec 04, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [e3acd70236](https://linux-hardware.org/?probe=e3acd70236) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 20RA008CAD     | Notebook    | [35fab17b69](https://linux-hardware.org/?probe=35fab17b69) | Dec 01, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [46d5208475](https://linux-hardware.org/?probe=46d5208475) | Nov 28, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [a1abd4e08e](https://linux-hardware.org/?probe=a1abd4e08e) | Nov 26, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [e37587fbac](https://linux-hardware.org/?probe=e37587fbac) | Nov 23, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [b050debd0a](https://linux-hardware.org/?probe=b050debd0a) | Nov 22, 2021 |
| Dell          | G3 3590                     | Notebook    | [605f0870d0](https://linux-hardware.org/?probe=605f0870d0) | Nov 16, 2021 |
| Dell          | G3 3590                     | Notebook    | [5bfafc889c](https://linux-hardware.org/?probe=5bfafc889c) | Nov 16, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [0ff55f060f](https://linux-hardware.org/?probe=0ff55f060f) | Nov 14, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo        | V570 1066AJU                | Notebook    | [ffb36aac10](https://linux-hardware.org/?probe=ffb36aac10) | Nov 05, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [41451fb2a2](https://linux-hardware.org/?probe=41451fb2a2) | Nov 05, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [a5026c4013](https://linux-hardware.org/?probe=a5026c4013) | Oct 21, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [20ca9b4679](https://linux-hardware.org/?probe=20ca9b4679) | Oct 18, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [5233ea30c6](https://linux-hardware.org/?probe=5233ea30c6) | Oct 09, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [65c4bea87a](https://linux-hardware.org/?probe=65c4bea87a) | Oct 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [d91c23c12c](https://linux-hardware.org/?probe=d91c23c12c) | Oct 08, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b22e6dc21a](https://linux-hardware.org/?probe=b22e6dc21a) | Oct 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [428e41ed23](https://linux-hardware.org/?probe=428e41ed23) | Oct 05, 2021 |
| Lenovo        | ThinkPad P52s 20LBS0JC00    | Notebook    | [4c8c63da2f](https://linux-hardware.org/?probe=4c8c63da2f) | Oct 05, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [2e99b047ff](https://linux-hardware.org/?probe=2e99b047ff) | Oct 04, 2021 |
| Dell          | Latitude 7275               | Tablet      | [c844ef39cd](https://linux-hardware.org/?probe=c844ef39cd) | Oct 03, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [85a91a83fa](https://linux-hardware.org/?probe=85a91a83fa) | Oct 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [de6b4e47d4](https://linux-hardware.org/?probe=de6b4e47d4) | Oct 01, 2021 |
| HP            | Laptop 15-da2xxx            | Notebook    | [28332170d1](https://linux-hardware.org/?probe=28332170d1) | Sep 28, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [8c04a9e8df](https://linux-hardware.org/?probe=8c04a9e8df) | Sep 22, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [19374f68da](https://linux-hardware.org/?probe=19374f68da) | Sep 21, 2021 |
| Dell          | 054KM3 A01                  | Desktop     | [6d277dcd36](https://linux-hardware.org/?probe=6d277dcd36) | Sep 18, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [ef4fb4b996](https://linux-hardware.org/?probe=ef4fb4b996) | Aug 28, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e5251674c0](https://linux-hardware.org/?probe=e5251674c0) | Aug 25, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [3d5e02e265](https://linux-hardware.org/?probe=3d5e02e265) | Aug 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [b87783b728](https://linux-hardware.org/?probe=b87783b728) | Aug 18, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [4c8282bb42](https://linux-hardware.org/?probe=4c8282bb42) | Aug 16, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f91acefb07](https://linux-hardware.org/?probe=f91acefb07) | Aug 14, 2021 |
| Dell          | 03X6X0 A06                  | Server      | [d52db39eeb](https://linux-hardware.org/?probe=d52db39eeb) | Jul 26, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [162b090056](https://linux-hardware.org/?probe=162b090056) | Jul 14, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [8d7689bceb](https://linux-hardware.org/?probe=8d7689bceb) | Jul 14, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [5bcc11cd03](https://linux-hardware.org/?probe=5bcc11cd03) | Jul 08, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [9bae1ef315](https://linux-hardware.org/?probe=9bae1ef315) | Jul 07, 2021 |
| ASUSTek       | K43SJ                       | Notebook    | [f4702e95b4](https://linux-hardware.org/?probe=f4702e95b4) | Jul 05, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [08fad9a114](https://linux-hardware.org/?probe=08fad9a114) | Jul 03, 2021 |
| Dell          | 0W0CHX A01                  | Desktop     | [e0a09aa1a5](https://linux-hardware.org/?probe=e0a09aa1a5) | Jul 01, 2021 |
| Dell          | G3 3590                     | Notebook    | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| Dell          | 0XHGV1 A01                  | Desktop     | [4fcd4b7e98](https://linux-hardware.org/?probe=4fcd4b7e98) | Jun 22, 2021 |
| Intel         | BTC-T37                     | Desktop     | [6cd9eb4fd4](https://linux-hardware.org/?probe=6cd9eb4fd4) | Jun 19, 2021 |
| Intel         | BTC-T37                     | Desktop     | [3f0a790d81](https://linux-hardware.org/?probe=3f0a790d81) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [06f25de7e3](https://linux-hardware.org/?probe=06f25de7e3) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [3fcbd5cd4f](https://linux-hardware.org/?probe=3fcbd5cd4f) | Jun 18, 2021 |
| Dell          | G3 3590                     | Notebook    | [877018f0d3](https://linux-hardware.org/?probe=877018f0d3) | Jun 18, 2021 |
| Dell          | G3 3590                     | Notebook    | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [7e5e7767c0](https://linux-hardware.org/?probe=7e5e7767c0) | Jun 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3a001e377](https://linux-hardware.org/?probe=d3a001e377) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a4d00095a1](https://linux-hardware.org/?probe=a4d00095a1) | Jun 01, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [88e51bfd39](https://linux-hardware.org/?probe=88e51bfd39) | May 23, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [ea32add5cd](https://linux-hardware.org/?probe=ea32add5cd) | May 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [96e19f007a](https://linux-hardware.org/?probe=96e19f007a) | May 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cfcef26a52](https://linux-hardware.org/?probe=cfcef26a52) | May 20, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [ed8c410826](https://linux-hardware.org/?probe=ed8c410826) | May 18, 2021 |
| Dell          | 042P49 A00                  | Desktop     | [f146c310d6](https://linux-hardware.org/?probe=f146c310d6) | May 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1d4c05756f](https://linux-hardware.org/?probe=1d4c05756f) | May 01, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [febcf69966](https://linux-hardware.org/?probe=febcf69966) | Apr 28, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [34b2d651e1](https://linux-hardware.org/?probe=34b2d651e1) | Apr 28, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9b03874730](https://linux-hardware.org/?probe=9b03874730) | Apr 27, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e0acc229ef](https://linux-hardware.org/?probe=e0acc229ef) | Apr 25, 2021 |
| Dell          | Latitude E7470              | Notebook    | [1058573f86](https://linux-hardware.org/?probe=1058573f86) | Apr 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [14fd40d980](https://linux-hardware.org/?probe=14fd40d980) | Apr 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b31da2d02](https://linux-hardware.org/?probe=0b31da2d02) | Apr 16, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [82dd7f530a](https://linux-hardware.org/?probe=82dd7f530a) | Apr 09, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [f97ecb74c0](https://linux-hardware.org/?probe=f97ecb74c0) | Apr 09, 2021 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [cd64675ac7](https://linux-hardware.org/?probe=cd64675ac7) | Mar 30, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [9ede240e19](https://linux-hardware.org/?probe=9ede240e19) | Mar 20, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [7d8acdd5b6](https://linux-hardware.org/?probe=7d8acdd5b6) | Mar 19, 2021 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [f568952b1d](https://linux-hardware.org/?probe=f568952b1d) | Mar 10, 2021 |
| Huanan        | X99-F8                      | Desktop     | [3bbee45dc4](https://linux-hardware.org/?probe=3bbee45dc4) | Mar 10, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [5aa53770bf](https://linux-hardware.org/?probe=5aa53770bf) | Mar 06, 2021 |
| Toshiba       | Satellite S55t-A            | Notebook    | [5ed863271a](https://linux-hardware.org/?probe=5ed863271a) | Mar 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c03aab940e](https://linux-hardware.org/?probe=c03aab940e) | Feb 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [66003aa802](https://linux-hardware.org/?probe=66003aa802) | Feb 28, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [290dbb71c2](https://linux-hardware.org/?probe=290dbb71c2) | Feb 25, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [260d78f7c8](https://linux-hardware.org/?probe=260d78f7c8) | Feb 20, 2021 |
| HP            | Pavilion g6                 | Notebook    | [30bcebb4be](https://linux-hardware.org/?probe=30bcebb4be) | Feb 16, 2021 |
| HP            | 8591                        | Desktop     | [b6b7f6af35](https://linux-hardware.org/?probe=b6b7f6af35) | Feb 15, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c8b28bb334](https://linux-hardware.org/?probe=c8b28bb334) | Feb 13, 2021 |
| Lenovo        | ThinkPad E460 20ET000MAD    | Notebook    | [cd000b8e6b](https://linux-hardware.org/?probe=cd000b8e6b) | Feb 11, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [5ed908976b](https://linux-hardware.org/?probe=5ed908976b) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [5407a15ab7](https://linux-hardware.org/?probe=5407a15ab7) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [0802cedb25](https://linux-hardware.org/?probe=0802cedb25) | Feb 09, 2021 |
| Dell          | Latitude E4310              | Notebook    | [9c6781e592](https://linux-hardware.org/?probe=9c6781e592) | Feb 08, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [1d97b5c83d](https://linux-hardware.org/?probe=1d97b5c83d) | Jan 31, 2021 |
| ASUSTek       | ROG Strix G512LWS_G512LW... | Notebook    | [d4d3110510](https://linux-hardware.org/?probe=d4d3110510) | Jan 29, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [5911afaa7a](https://linux-hardware.org/?probe=5911afaa7a) | Jan 27, 2021 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [6bdd3b4a5d](https://linux-hardware.org/?probe=6bdd3b4a5d) | Jan 27, 2021 |
| Acer          | Spin SP111-33               | Convertible | [0a09d00b74](https://linux-hardware.org/?probe=0a09d00b74) | Jan 23, 2021 |
| Toshiba       | Satellite C855D             | Notebook    | [46d5bf62c7](https://linux-hardware.org/?probe=46d5bf62c7) | Jan 19, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [e289a86560](https://linux-hardware.org/?probe=e289a86560) | Jan 16, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [99f1a1ac09](https://linux-hardware.org/?probe=99f1a1ac09) | Jan 16, 2021 |
| Sony          | VGN-FZ250E                  | Notebook    | [d0d77ffe81](https://linux-hardware.org/?probe=d0d77ffe81) | Jan 15, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [92ea4004af](https://linux-hardware.org/?probe=92ea4004af) | Jan 15, 2021 |
| Sony          | VGN-FZ250E                  | Notebook    | [68ddc53941](https://linux-hardware.org/?probe=68ddc53941) | Jan 14, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [b21e44d0c4](https://linux-hardware.org/?probe=b21e44d0c4) | Jan 11, 2021 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [e57dfe6f39](https://linux-hardware.org/?probe=e57dfe6f39) | Dec 30, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [2249011658](https://linux-hardware.org/?probe=2249011658) | Dec 30, 2020 |
| Dell          | 0GN6JF A01                  | Desktop     | [b4ea210c79](https://linux-hardware.org/?probe=b4ea210c79) | Dec 27, 2020 |
| Dell          | Vostro 5470                 | Notebook    | [216df384d8](https://linux-hardware.org/?probe=216df384d8) | Dec 22, 2020 |
| Dell          | Vostro 5470                 | Notebook    | [bec1b16786](https://linux-hardware.org/?probe=bec1b16786) | Dec 22, 2020 |
| LG Electro... | R490-G.ARL5RE2              | Notebook    | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| OEM           | B250                        | Desktop     | [80af247c92](https://linux-hardware.org/?probe=80af247c92) | Dec 09, 2020 |
| HP            | 198E                        | Desktop     | [d6e4336d03](https://linux-hardware.org/?probe=d6e4336d03) | Dec 08, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [6c1033e9f9](https://linux-hardware.org/?probe=6c1033e9f9) | Dec 04, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [1e0a7199b7](https://linux-hardware.org/?probe=1e0a7199b7) | Dec 03, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [239675db8d](https://linux-hardware.org/?probe=239675db8d) | Nov 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [dfcc723611](https://linux-hardware.org/?probe=dfcc723611) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b164be6cfc](https://linux-hardware.org/?probe=b164be6cfc) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [a3ffdab533](https://linux-hardware.org/?probe=a3ffdab533) | Nov 16, 2020 |
| HP            | 843C                        | Desktop     | [fd8c0fa877](https://linux-hardware.org/?probe=fd8c0fa877) | Nov 10, 2020 |
| OEM           | B250                        | Desktop     | [f6bcb7135c](https://linux-hardware.org/?probe=f6bcb7135c) | Nov 10, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | Notebook    | [cce5403051](https://linux-hardware.org/?probe=cce5403051) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| I-Life Dig... | ZED Air Plus                | Notebook    | [b1a43bf9f2](https://linux-hardware.org/?probe=b1a43bf9f2) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [c0ad42acb0](https://linux-hardware.org/?probe=c0ad42acb0) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [b5e6f52433](https://linux-hardware.org/?probe=b5e6f52433) | Nov 04, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e9ca4c8d42](https://linux-hardware.org/?probe=e9ca4c8d42) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c45580b2f3](https://linux-hardware.org/?probe=c45580b2f3) | Oct 28, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [1816b1fb29](https://linux-hardware.org/?probe=1816b1fb29) | Oct 23, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e80544ed81](https://linux-hardware.org/?probe=e80544ed81) | Oct 20, 2020 |
| MSI           | MS-1454                     | Notebook    | [0accbf6c77](https://linux-hardware.org/?probe=0accbf6c77) | Oct 14, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [1d466d105c](https://linux-hardware.org/?probe=1d466d105c) | Oct 12, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e1c5dde63a](https://linux-hardware.org/?probe=e1c5dde63a) | Oct 12, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [a1665a6de1](https://linux-hardware.org/?probe=a1665a6de1) | Sep 26, 2020 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [3ec057ab8d](https://linux-hardware.org/?probe=3ec057ab8d) | Sep 18, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [d52f9c5bc7](https://linux-hardware.org/?probe=d52f9c5bc7) | Sep 18, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [6963343ed4](https://linux-hardware.org/?probe=6963343ed4) | Sep 17, 2020 |
| ASRock        | Z270M Pro4                  | Desktop     | [ed0a963b78](https://linux-hardware.org/?probe=ed0a963b78) | Sep 05, 2020 |
| Clevo         | P15xEMx                     | Notebook    | [83d0f6aae6](https://linux-hardware.org/?probe=83d0f6aae6) | Aug 28, 2020 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [8634132c3a](https://linux-hardware.org/?probe=8634132c3a) | Aug 24, 2020 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [54032f9ee7](https://linux-hardware.org/?probe=54032f9ee7) | Aug 19, 2020 |
| Lenovo        | ThinkPad Edge 0301FFG       | Notebook    | [60d3a68581](https://linux-hardware.org/?probe=60d3a68581) | Aug 10, 2020 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [c04081db17](https://linux-hardware.org/?probe=c04081db17) | Aug 07, 2020 |
| HP            | Pavilion g6                 | Notebook    | [98d75162cc](https://linux-hardware.org/?probe=98d75162cc) | Aug 06, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [41a4a29b16](https://linux-hardware.org/?probe=41a4a29b16) | Aug 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [9138a15fe4](https://linux-hardware.org/?probe=9138a15fe4) | Aug 01, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [fa825c1fce](https://linux-hardware.org/?probe=fa825c1fce) | Jul 26, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [3098a39bdb](https://linux-hardware.org/?probe=3098a39bdb) | Jul 26, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fe429f7077](https://linux-hardware.org/?probe=fe429f7077) | Jul 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f9c494b96b](https://linux-hardware.org/?probe=f9c494b96b) | Jul 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [1c82bd39f0](https://linux-hardware.org/?probe=1c82bd39f0) | Jul 01, 2020 |
| Microsoft     | Surface Pro 7               | Tablet      | [69744692b0](https://linux-hardware.org/?probe=69744692b0) | Jun 30, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [f6884bd3db](https://linux-hardware.org/?probe=f6884bd3db) | Jun 26, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [1a288de2c5](https://linux-hardware.org/?probe=1a288de2c5) | Jun 24, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [aa1c1587d1](https://linux-hardware.org/?probe=aa1c1587d1) | Jun 23, 2020 |
| Acer          | Aspire ES1-572              | Notebook    | [a166c179ea](https://linux-hardware.org/?probe=a166c179ea) | Jun 22, 2020 |
| ASUSTek       | L4000H                      | Notebook    | [d385784b22](https://linux-hardware.org/?probe=d385784b22) | Jun 22, 2020 |
| Dell          | 0GN6JF A01                  | Desktop     | [452e0f2712](https://linux-hardware.org/?probe=452e0f2712) | Jun 16, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [c5f91bc1ff](https://linux-hardware.org/?probe=c5f91bc1ff) | Jun 16, 2020 |
| Dell          | Inspiron N5030              | Notebook    | [5641d9b86e](https://linux-hardware.org/?probe=5641d9b86e) | Jun 14, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6c1261f611](https://linux-hardware.org/?probe=6c1261f611) | Jun 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [eb4135b12e](https://linux-hardware.org/?probe=eb4135b12e) | Jun 07, 2020 |
| Pegatron      | 2A84h                       | Desktop     | [a5884bfb13](https://linux-hardware.org/?probe=a5884bfb13) | Jun 01, 2020 |
| ASUSTek       | UX390UAK                    | Notebook    | [0857b4df77](https://linux-hardware.org/?probe=0857b4df77) | May 27, 2020 |
| Gigabyte      | H61M-S2P                    | Desktop     | [aecc9b0111](https://linux-hardware.org/?probe=aecc9b0111) | May 25, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [447ac858da](https://linux-hardware.org/?probe=447ac858da) | May 24, 2020 |
| Sony          | SVF153290X                  | Notebook    | [e19f1c716f](https://linux-hardware.org/?probe=e19f1c716f) | May 23, 2020 |
| Gigabyte      | B75M-HD3                    | Desktop     | [bedfc8fa0f](https://linux-hardware.org/?probe=bedfc8fa0f) | May 21, 2020 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [874c2cb817](https://linux-hardware.org/?probe=874c2cb817) | May 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [117bc7af0e](https://linux-hardware.org/?probe=117bc7af0e) | May 17, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [1947ac6d52](https://linux-hardware.org/?probe=1947ac6d52) | May 16, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [dc7f6cc9e8](https://linux-hardware.org/?probe=dc7f6cc9e8) | May 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0444dd48d1](https://linux-hardware.org/?probe=0444dd48d1) | May 09, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| HP            | Pavilion dv6                | Notebook    | [8ee1846a65](https://linux-hardware.org/?probe=8ee1846a65) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [bff527c13e](https://linux-hardware.org/?probe=bff527c13e) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8b02fac19f](https://linux-hardware.org/?probe=8b02fac19f) | Apr 26, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [48acf05b1b](https://linux-hardware.org/?probe=48acf05b1b) | Apr 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [640431a321](https://linux-hardware.org/?probe=640431a321) | Apr 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [095b8a5cdc](https://linux-hardware.org/?probe=095b8a5cdc) | Apr 16, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [874b42a4b7](https://linux-hardware.org/?probe=874b42a4b7) | Apr 16, 2020 |
| HP            | 15                          | Notebook    | [68b0d776a9](https://linux-hardware.org/?probe=68b0d776a9) | Apr 08, 2020 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [784de80b54](https://linux-hardware.org/?probe=784de80b54) | Apr 08, 2020 |
| HP            | Notebook                    | Notebook    | [f22cd145c5](https://linux-hardware.org/?probe=f22cd145c5) | Apr 07, 2020 |
| HP            | 15                          | Notebook    | [27ef1499e3](https://linux-hardware.org/?probe=27ef1499e3) | Apr 06, 2020 |
| HP            | 15                          | Notebook    | [0c2b7adf55](https://linux-hardware.org/?probe=0c2b7adf55) | Apr 06, 2020 |
| HP            | 15                          | Notebook    | [ee5fd88936](https://linux-hardware.org/?probe=ee5fd88936) | Apr 03, 2020 |
| HP            | 15                          | Notebook    | [bfd4fe41b3](https://linux-hardware.org/?probe=bfd4fe41b3) | Apr 03, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [cdce411ba5](https://linux-hardware.org/?probe=cdce411ba5) | Mar 13, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [6e7a1c3bc6](https://linux-hardware.org/?probe=6e7a1c3bc6) | Mar 13, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d3d2a3b89f](https://linux-hardware.org/?probe=d3d2a3b89f) | Mar 05, 2020 |
| ASUSTek       | X555QA                      | Notebook    | [2f0a038eaf](https://linux-hardware.org/?probe=2f0a038eaf) | Feb 11, 2020 |
| ASUSTek       | X555QA                      | Notebook    | [e8062aced5](https://linux-hardware.org/?probe=e8062aced5) | Feb 10, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [5aaf89e123](https://linux-hardware.org/?probe=5aaf89e123) | Feb 03, 2020 |
| Dell          | Vostro 1440                 | Notebook    | [203e61a7c9](https://linux-hardware.org/?probe=203e61a7c9) | Feb 01, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [fbdcd4fb9f](https://linux-hardware.org/?probe=fbdcd4fb9f) | Jan 30, 2020 |
| HP            | Notebook                    | Notebook    | [86dc2687ad](https://linux-hardware.org/?probe=86dc2687ad) | Jan 29, 2020 |
| HP            | Notebook                    | Notebook    | [d3e2e18fa2](https://linux-hardware.org/?probe=d3e2e18fa2) | Jan 29, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9c01b939ce](https://linux-hardware.org/?probe=9c01b939ce) | Jan 27, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [916d1cb7c0](https://linux-hardware.org/?probe=916d1cb7c0) | Jan 27, 2020 |
| Toshiba       | QOSMIO X875                 | Notebook    | [a20b2a7dd7](https://linux-hardware.org/?probe=a20b2a7dd7) | Jan 02, 2020 |
| Toshiba       | QOSMIO X875                 | Notebook    | [953a43ae80](https://linux-hardware.org/?probe=953a43ae80) | Jan 02, 2020 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [bb1c5e0c3a](https://linux-hardware.org/?probe=bb1c5e0c3a) | Jan 01, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [0da4e7552a](https://linux-hardware.org/?probe=0da4e7552a) | Dec 29, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [c137a7866b](https://linux-hardware.org/?probe=c137a7866b) | Dec 14, 2019 |
| Lenovo        | ThinkPad X230 2325OA3       | Notebook    | [ad8913bb6b](https://linux-hardware.org/?probe=ad8913bb6b) | Dec 09, 2019 |
| GPD           | MicroPC                     | Notebook    | [37bfeee080](https://linux-hardware.org/?probe=37bfeee080) | Dec 09, 2019 |
| MSI           | 2A78h                       | Desktop     | [83e806e50e](https://linux-hardware.org/?probe=83e806e50e) | Oct 25, 2019 |
| MSI           | 2A78h                       | Desktop     | [b5679811c8](https://linux-hardware.org/?probe=b5679811c8) | Oct 25, 2019 |
| MSI           | B360M GAMING PLUS           | Desktop     | [f54aa10fcc](https://linux-hardware.org/?probe=f54aa10fcc) | Oct 24, 2019 |
| MSI           | B360M GAMING PLUS           | Desktop     | [96ee6c9f88](https://linux-hardware.org/?probe=96ee6c9f88) | Oct 24, 2019 |
| ASUSTek       | SABERTOOTH Z97 MARK 2/US... | Desktop     | [4976e1673d](https://linux-hardware.org/?probe=4976e1673d) | Oct 01, 2019 |
| ASUSTek       | X555LDB                     | Notebook    | [fffe9c8500](https://linux-hardware.org/?probe=fffe9c8500) | Sep 04, 2019 |
| ASUSTek       | X555LDB                     | Notebook    | [60bc2f13a4](https://linux-hardware.org/?probe=60bc2f13a4) | Sep 04, 2019 |
| Dell          | 0HN7XN A01                  | Desktop     | [b9dd067151](https://linux-hardware.org/?probe=b9dd067151) | Aug 18, 2019 |
| Dell          | 0HN7XN A01                  | Desktop     | [67161826ca](https://linux-hardware.org/?probe=67161826ca) | Aug 18, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [0a1b8c3a29](https://linux-hardware.org/?probe=0a1b8c3a29) | Aug 17, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [4b1cbc26db](https://linux-hardware.org/?probe=4b1cbc26db) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [5670d72491](https://linux-hardware.org/?probe=5670d72491) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | Notebook    | [81bd1c9f07](https://linux-hardware.org/?probe=81bd1c9f07) | Aug 13, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [bc9f90fd94](https://linux-hardware.org/?probe=bc9f90fd94) | Jul 20, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [a5dd292f0e](https://linux-hardware.org/?probe=a5dd292f0e) | Jul 20, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [78b4fe060a](https://linux-hardware.org/?probe=78b4fe060a) | Jul 19, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [b3224eb5fc](https://linux-hardware.org/?probe=b3224eb5fc) | Jul 19, 2019 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [f8b4fc087b](https://linux-hardware.org/?probe=f8b4fc087b) | Jul 13, 2019 |
| Sony          | VPCEA36FA                   | Notebook    | [069db5e1d5](https://linux-hardware.org/?probe=069db5e1d5) | Jul 11, 2019 |
| HUAWEI        | MateBook D                  | Notebook    | [0c82ca3724](https://linux-hardware.org/?probe=0c82ca3724) | Jul 06, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [b66944b7d8](https://linux-hardware.org/?probe=b66944b7d8) | Jun 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [630f59eb30](https://linux-hardware.org/?probe=630f59eb30) | Jun 12, 2019 |
| Dell          | Latitude 5285               | Tablet      | [73b87c222f](https://linux-hardware.org/?probe=73b87c222f) | Jun 12, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [3d424bc8d3](https://linux-hardware.org/?probe=3d424bc8d3) | Jun 07, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [8b98fb721c](https://linux-hardware.org/?probe=8b98fb721c) | Jun 07, 2019 |
| Dell          | 0PC5F7 A02                  | Desktop     | [d5c119cb28](https://linux-hardware.org/?probe=d5c119cb28) | Jun 04, 2019 |
| Fujitsu Si... | D2480-A1 S26361-D2480-A1    | Desktop     | [9a655727f9](https://linux-hardware.org/?probe=9a655727f9) | Jun 02, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [5bca621b29](https://linux-hardware.org/?probe=5bca621b29) | May 31, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [ced21dc1f3](https://linux-hardware.org/?probe=ced21dc1f3) | May 21, 2019 |
| Dell          | Latitude 5285               | Tablet      | [fcedd9ded7](https://linux-hardware.org/?probe=fcedd9ded7) | Apr 25, 2019 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [14b4f17a8a](https://linux-hardware.org/?probe=14b4f17a8a) | Apr 22, 2019 |
| Sony          | SVF14N13CXB                 | Notebook    | [37e231ce84](https://linux-hardware.org/?probe=37e231ce84) | Apr 07, 2019 |
| Dell          | 0C27VV A03                  | Desktop     | [4a17c281b7](https://linux-hardware.org/?probe=4a17c281b7) | Apr 05, 2019 |
| HP            | 15                          | Notebook    | [e900ad9cfc](https://linux-hardware.org/?probe=e900ad9cfc) | Mar 15, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [8366ef739b](https://linux-hardware.org/?probe=8366ef739b) | Jan 19, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [8c5dcea151](https://linux-hardware.org/?probe=8c5dcea151) | Jan 07, 2019 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [f238cfd7d7](https://linux-hardware.org/?probe=f238cfd7d7) | Jan 07, 2019 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d44c9b123d](https://linux-hardware.org/?probe=d44c9b123d) | Dec 19, 2018 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b0c7903cb1](https://linux-hardware.org/?probe=b0c7903cb1) | Dec 19, 2018 |
| Lenovo        | NOK                         | Desktop     | [2761f888c3](https://linux-hardware.org/?probe=2761f888c3) | Nov 16, 2018 |
| Acer          | Aspire E1-532P              | Notebook    | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [3e2fa165a6](https://linux-hardware.org/?probe=3e2fa165a6) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [a7272b3797](https://linux-hardware.org/?probe=a7272b3797) | Oct 30, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [9c149f8d89](https://linux-hardware.org/?probe=9c149f8d89) | Oct 28, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [5c682ba446](https://linux-hardware.org/?probe=5c682ba446) | Oct 26, 2018 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [28a72027c5](https://linux-hardware.org/?probe=28a72027c5) | Oct 25, 2018 |
| Gigabyte      | P35-DS3R                    | Desktop     | [2f8f1a592b](https://linux-hardware.org/?probe=2f8f1a592b) | Aug 14, 2018 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [d9e3df518a](https://linux-hardware.org/?probe=d9e3df518a) | Dec 08, 2017 |
| Dell          | 0VNP2H A00                  | Desktop     | [68fa7ad805](https://linux-hardware.org/?probe=68fa7ad805) | Nov 25, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Saudi_Arabia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 43        | 6.56%   |
| Ubuntu 22.04       | 42        | 6.41%   |
| Ubuntu 24.04       | 20        | 3.05%   |
| Pop!_OS 22.04      | 20        | 3.05%   |
| Zorin 17           | 19        | 2.9%    |
| Ubuntu 18.04       | 18        | 2.75%   |
| Arch Rolling       | 17        | 2.6%    |
| Fedora 42          | 16        | 2.44%   |
| Debian 12          | 15        | 2.29%   |
| OpenMandriva 4.3   | 14        | 2.14%   |
| OpenMandriva 4.2   | 13        | 1.98%   |
| Zorin 16           | 10        | 1.53%   |
| OpenMandriva 23.08 | 7         | 1.07%   |
| Manjaro            | 7         | 1.07%   |
| Kubuntu 24.04      | 7         | 1.07%   |
| Ubuntu 20.10       | 6         | 0.92%   |
| Pop!_OS 21.10      | 6         | 0.92%   |
| Linux Mint 22.1    | 6         | 0.92%   |
| Fedora 39          | 6         | 0.92%   |
| Fedora 35          | 6         | 0.92%   |
| Debian 11          | 6         | 0.92%   |
| Ubuntu 25.04       | 5         | 0.76%   |
| Ubuntu 24.10       | 5         | 0.76%   |
| Ubuntu 23.04       | 5         | 0.76%   |
| Ubuntu 19.04       | 5         | 0.76%   |
| Pop!_OS 21.04      | 5         | 0.76%   |
| OpenMandriva 25.90 | 5         | 0.76%   |
| OpenMandriva 24.12 | 5         | 0.76%   |
| KDE neon 20.04     | 5         | 0.76%   |
| Fedora 40          | 5         | 0.76%   |
| Fedora 38          | 5         | 0.76%   |
| ArcoLinux Rolling  | 5         | 0.76%   |
| Arch               | 5         | 0.76%   |
| Zorin 18           | 4         | 0.61%   |
| Ubuntu 21.10       | 4         | 0.61%   |
| Ubuntu 21.04       | 4         | 0.61%   |
| Ubuntu 19.10       | 4         | 0.61%   |
| SteamOS 3.5.19     | 4         | 0.61%   |
| Nobara 37          | 4         | 0.61%   |
| Linux Mint 21.2    | 4         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 154       | 25.5%   |
| OpenMandriva     | 61        | 10.1%   |
| Fedora           | 50        | 8.28%   |
| Zorin            | 35        | 5.79%   |
| Linux Mint       | 31        | 5.13%   |
| Pop!_OS          | 30        | 4.97%   |
| Debian           | 30        | 4.97%   |
| Arch             | 22        | 3.64%   |
| Manjaro          | 18        | 2.98%   |
| Kubuntu          | 18        | 2.98%   |
| Endless          | 18        | 2.98%   |
| Kali             | 16        | 2.65%   |
| SteamOS          | 14        | 2.32%   |
| KDE neon         | 13        | 2.15%   |
| ROSA             | 9         | 1.49%   |
| Nobara           | 6         | 0.99%   |
| Bazzite          | 6         | 0.99%   |
| ArcoLinux        | 6         | 0.99%   |
| openSUSE         | 5         | 0.83%   |
| NixOS            | 5         | 0.83%   |
| Elementary       | 5         | 0.83%   |
| Xubuntu          | 4         | 0.66%   |
| Ubuntu Unity     | 3         | 0.5%    |
| Ubuntu Budgie    | 3         | 0.5%    |
| org.kde.Platform | 3         | 0.5%    |
| LMDE             | 3         | 0.5%    |
| Clear Linux      | 3         | 0.5%    |
| ChimeraOS        | 3         | 0.5%    |
| Ubuntu MATE      | 2         | 0.33%   |
| Solus            | 2         | 0.33%   |
| RHEL             | 2         | 0.33%   |
| Parrot           | 2         | 0.33%   |
| Lubuntu          | 2         | 0.33%   |
| EndeavourOS      | 2         | 0.33%   |
| Android          | 2         | 0.33%   |
| Void Linux       | 1         | 0.17%   |
| Ubuntu Kylin     | 1         | 0.17%   |
| Rocky Linux      | 1         | 0.17%   |
| Q4OS             | 1         | 0.17%   |
| PostmarketOS     | 1         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003     | 13        | 1.8%    |
| 5.10.14-desktop-1omv4002    | 12        | 1.66%   |
| 6.14.2-desktop-3omv2590     | 9         | 1.25%   |
| 6.4.11-desktop-1omv2390     | 7         | 0.97%   |
| 6.2.0-39-generic            | 6         | 0.83%   |
| 5.4.0-42-generic            | 6         | 0.83%   |
| 6.9.3-76060903-generic      | 5         | 0.69%   |
| 6.2.0-26-generic            | 5         | 0.69%   |
| 6.14.0-35-generic           | 5         | 0.69%   |
| 6.1.52-valve16-1-neptune-61 | 5         | 0.69%   |
| 5.19.0-32-generic           | 5         | 0.69%   |
| 6.8.0-49-generic            | 4         | 0.55%   |
| 6.8.0-40-generic            | 4         | 0.55%   |
| 6.5.0-26-generic            | 4         | 0.55%   |
| 6.2.0-32-generic            | 4         | 0.55%   |
| 6.12.1-desktop-1omv2490     | 4         | 0.55%   |
| 5.4.0-19-generic            | 4         | 0.55%   |
| 5.3.0-28-generic            | 4         | 0.55%   |
| 5.19.0-26-generic           | 4         | 0.55%   |
| 5.15.0-58-generic           | 4         | 0.55%   |
| 5.15.0-48-generic           | 4         | 0.55%   |
| 5.13.0-7614-generic         | 4         | 0.55%   |
| 5.11.0-43-generic           | 4         | 0.55%   |
| 4.15.0-15-generic           | 4         | 0.55%   |
| 6.8.0-60-generic            | 3         | 0.42%   |
| 6.8.0-52-generic            | 3         | 0.42%   |
| 6.8.0-51-generic            | 3         | 0.42%   |
| 6.8.0-50-generic            | 3         | 0.42%   |
| 6.5.6-76060506-generic      | 3         | 0.42%   |
| 6.5.0-41-generic            | 3         | 0.42%   |
| 6.5.0-35-generic            | 3         | 0.42%   |
| 6.5.0-14-generic            | 3         | 0.42%   |
| 6.3.8-200.fc38.x86_64       | 3         | 0.42%   |
| 6.2.16-20-pve               | 3         | 0.42%   |
| 6.2.0-34-generic            | 3         | 0.42%   |
| 6.14.0-37-generic           | 3         | 0.42%   |
| 6.14.0-36-generic           | 3         | 0.42%   |
| 6.14.0-33-generic           | 3         | 0.42%   |
| 6.14.0-29-generic           | 3         | 0.42%   |
| 6.14.0-27-generic           | 3         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 44        | 6.39%   |
| 6.8.0   | 39        | 5.66%   |
| 5.4.0   | 37        | 5.37%   |
| 6.5.0   | 25        | 3.63%   |
| 6.14.0  | 25        | 3.63%   |
| 5.8.0   | 25        | 3.63%   |
| 6.2.0   | 24        | 3.48%   |
| 5.19.0  | 24        | 3.48%   |
| 5.11.0  | 21        | 3.05%   |
| 6.1.0   | 19        | 2.76%   |
| 6.11.0  | 17        | 2.47%   |
| 5.3.0   | 16        | 2.32%   |
| 4.15.0  | 15        | 2.18%   |
| 5.13.0  | 14        | 2.03%   |
| 6.14.2  | 13        | 1.89%   |
| 5.16.7  | 13        | 1.89%   |
| 5.10.14 | 12        | 1.74%   |
| 5.10.0  | 10        | 1.45%   |
| 4.18.0  | 10        | 1.45%   |
| 5.0.0   | 8         | 1.16%   |
| 6.4.11  | 7         | 1.02%   |
| 6.9.3   | 6         | 0.87%   |
| 6.1.52  | 6         | 0.87%   |
| 6.2.6   | 4         | 0.58%   |
| 6.12.9  | 4         | 0.58%   |
| 6.12.1  | 4         | 0.58%   |
| 6.9.9   | 3         | 0.44%   |
| 6.8.11  | 3         | 0.44%   |
| 6.7.9   | 3         | 0.44%   |
| 6.5.6   | 3         | 0.44%   |
| 6.5.3   | 3         | 0.44%   |
| 6.4.0   | 3         | 0.44%   |
| 6.3.8   | 3         | 0.44%   |
| 6.2.16  | 3         | 0.44%   |
| 6.17.12 | 3         | 0.44%   |
| 6.16.8  | 3         | 0.44%   |
| 6.11.2  | 3         | 0.44%   |
| 6.1.1   | 3         | 0.44%   |
| 6.0.0   | 3         | 0.44%   |
| 5.16.19 | 3         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 58        | 8.63%   |
| 6.8     | 44        | 6.55%   |
| 6.14    | 43        | 6.4%    |
| 5.4     | 39        | 5.8%    |
| 6.1     | 35        | 5.21%   |
| 6.2     | 33        | 4.91%   |
| 6.5     | 32        | 4.76%   |
| 5.8     | 28        | 4.17%   |
| 5.19    | 28        | 4.17%   |
| 5.10    | 26        | 3.87%   |
| 6.11    | 24        | 3.57%   |
| 5.16    | 24        | 3.57%   |
| 5.11    | 24        | 3.57%   |
| 6.12    | 23        | 3.42%   |
| 5.13    | 17        | 2.53%   |
| 5.3     | 16        | 2.38%   |
| 4.15    | 15        | 2.23%   |
| 6.4     | 14        | 2.08%   |
| 6.9     | 13        | 1.93%   |
| 6.16    | 12        | 1.79%   |
| 6.6     | 11        | 1.64%   |
| 4.18    | 11        | 1.64%   |
| 6.17    | 9         | 1.34%   |
| 6.0     | 9         | 1.34%   |
| 5.0     | 8         | 1.19%   |
| 6.10    | 7         | 1.04%   |
| 6.3     | 6         | 0.89%   |
| 5.18    | 6         | 0.89%   |
| 4.9     | 6         | 0.89%   |
| 6.15    | 5         | 0.74%   |
| 6.13    | 5         | 0.74%   |
| 5.6     | 5         | 0.74%   |
| 5.17    | 5         | 0.74%   |
| 5.14    | 5         | 0.74%   |
| 6.7     | 4         | 0.6%    |
| 5.9     | 4         | 0.6%    |
| 5.5     | 4         | 0.6%    |
| 5.7     | 3         | 0.45%   |
| 5.12    | 2         | 0.3%    |
| 4.19    | 2         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 549       | 98.21%  |
| i686    | 6         | 1.07%   |
| aarch64 | 3         | 0.54%   |
| armv7l  | 1         | 0.18%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 275       | 46.06%  |
| KDE5             | 102       | 17.09%  |
| KDE6             | 54        | 9.05%   |
| Unknown          | 44        | 7.37%   |
| X-Cinnamon       | 33        | 5.53%   |
| XFCE             | 32        | 5.36%   |
| KDE              | 12        | 2.01%   |
| Budgie           | 7         | 1.17%   |
| Pantheon         | 5         | 0.84%   |
| MATE             | 5         | 0.84%   |
| Cinnamon         | 5         | 0.84%   |
| LXQt             | 4         | 0.67%   |
| KDE4             | 4         | 0.67%   |
| Unity            | 3         | 0.5%    |
| Deepin           | 2         | 0.34%   |
| COSMIC           | 2         | 0.34%   |
| UKUI             | 1         | 0.17%   |
| trinity          | 1         | 0.17%   |
| openbox          | 1         | 0.17%   |
| lightdm-xsession | 1         | 0.17%   |
| i3               | 1         | 0.17%   |
| Hyprland         | 1         | 0.17%   |
| DDE              | 1         | 0.17%   |
| bspwm            | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 346       | 59.66%  |
| Wayland | 195       | 33.62%  |
| Unknown | 26        | 4.48%   |
| Tty     | 13        | 2.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 299       | 50.68%  |
| SDDM    | 100       | 16.95%  |
| GDM3    | 94        | 15.93%  |
| GDM     | 48        | 8.14%   |
| LightDM | 35        | 5.93%   |
| TDM     | 9         | 1.53%   |
| KDM     | 4         | 0.68%   |
| GREETD  | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 438       | 76.17%  |
| Unknown | 37        | 6.43%   |
| ar_SA   | 32        | 5.57%   |
| ar_EG   | 24        | 4.17%   |
| en_GB   | 15        | 2.61%   |
| C       | 10        | 1.74%   |
| ar_AE   | 4         | 0.7%    |
| en_AU   | 2         | 0.35%   |
| en_AG   | 2         | 0.35%   |
| ru_RU   | 1         | 0.17%   |
| nl_BE   | 1         | 0.17%   |
| it_IT   | 1         | 0.17%   |
| fr_FR   | 1         | 0.17%   |
| en_IN   | 1         | 0.17%   |
| en_IL   | 1         | 0.17%   |
| de_DE   | 1         | 0.17%   |
| Default | 1         | 0.17%   |
| cs_CZ   | 1         | 0.17%   |
| ar_SY   | 1         | 0.17%   |
| ar_KW   | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 319       | 54.81%  |
| EFI  | 263       | 45.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 375       | 64.77%  |
| Btrfs   | 93        | 16.06%  |
| Tmpfs   | 47        | 8.12%   |
| Overlay | 34        | 5.87%   |
| Unknown | 14        | 2.42%   |
| Xfs     | 10        | 1.73%   |
| Zfs     | 3         | 0.52%   |
| Ext2    | 3         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 305       | 52.23%  |
| GPT     | 247       | 42.29%  |
| MBR     | 32        | 5.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 488       | 85.31%  |
| Yes       | 84        | 14.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 423       | 73.06%  |
| Yes       | 156       | 26.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 94        | 16.82%  |
| Dell                                 | 90        | 16.1%   |
| Lenovo                               | 80        | 14.31%  |
| Hewlett-Packard                      | 64        | 11.45%  |
| MSI                                  | 38        | 6.8%    |
| Gigabyte Technology                  | 34        | 6.08%   |
| Apple                                | 21        | 3.76%   |
| Acer                                 | 21        | 3.76%   |
| Toshiba                              | 13        | 2.33%   |
| Valve                                | 12        | 2.15%   |
| HUAWEI                               | 12        | 2.15%   |
| ASRock                               | 11        | 1.97%   |
| Unknown                              | 8         | 1.43%   |
| Microsoft                            | 7         | 1.25%   |
| Sony                                 | 6         | 1.07%   |
| Samsung Electronics                  | 3         | 0.54%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.36%   |
| Pegatron                             | 2         | 0.36%   |
| Notebook                             | 2         | 0.36%   |
| Intel                                | 2         | 0.36%   |
| I-Life Digital Technologies          | 2         | 0.36%   |
| Huanan                               | 2         | 0.36%   |
| Google                               | 2         | 0.36%   |
| AZW                                  | 2         | 0.36%   |
| ZOTAC                                | 1         | 0.18%   |
| TianBei                              | 1         | 0.18%   |
| SDZ                                  | 1         | 0.18%   |
| Razer                                | 1         | 0.18%   |
| Packard Bell                         | 1         | 0.18%   |
| OEM                                  | 1         | 0.18%   |
| Nvidia                               | 1         | 0.18%   |
| Medion                               | 1         | 0.18%   |
| LG Electronics                       | 1         | 0.18%   |
| Kllisre                              | 1         | 0.18%   |
| JGINYUE                              | 1         | 0.18%   |
| HONOR                                | 1         | 0.18%   |
| GPD                                  | 1         | 0.18%   |
| GMKtec                               | 1         | 0.18%   |
| GIADA                                | 1         | 0.18%   |
| GEEKOM                               | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 12        | 2.15%   |
| Valve Jupiter                              | 10        | 1.79%   |
| Microsoft Surface Pro 7                    | 5         | 0.89%   |
| Dell G3 3590                               | 5         | 0.89%   |
| ASUS All Series                            | 5         | 0.89%   |
| Dell OptiPlex 9020                         | 4         | 0.72%   |
| Dell OptiPlex 7010                         | 4         | 0.72%   |
| Dell Inspiron 3542                         | 4         | 0.72%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 0.72%   |
| ASUS ASUS Zenbook Duo UX8406MA_UX8406MA    | 4         | 0.72%   |
| HP Notebook                                | 3         | 0.54%   |
| HP Laptop 15-da2xxx                        | 3         | 0.54%   |
| HP 15                                      | 3         | 0.54%   |
| Dell OptiPlex 990                          | 3         | 0.54%   |
| Dell OptiPlex 3010                         | 3         | 0.54%   |
| Valve Galileo                              | 2         | 0.36%   |
| MSI MS-7C90                                | 2         | 0.36%   |
| MSI MS-7C37                                | 2         | 0.36%   |
| MSI Modern 14 B5M                          | 2         | 0.36%   |
| Lenovo Legion T5 26IOB6 90RT00TVKS         | 2         | 0.36%   |
| Lenovo Legion Go 8APU1 83E1                | 2         | 0.36%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 2         | 0.36%   |
| Lenovo IdeaPad 3 14IIL05 81WD              | 2         | 0.36%   |
| HUAWEI KLVD-WXX9                           | 2         | 0.36%   |
| HP Pavilion x360 Convertible 14-cd0xxx     | 2         | 0.36%   |
| HP Pavilion Laptop 15-eh0xxx               | 2         | 0.36%   |
| HP Pavilion g6                             | 2         | 0.36%   |
| HP Laptop 15-da0xxx                        | 2         | 0.36%   |
| HP ENVY x360 Convertible 15-ed1xxx         | 2         | 0.36%   |
| HP Compaq Elite 8300 SFF                   | 2         | 0.36%   |
| Gigabyte Z77-D3H                           | 2         | 0.36%   |
| Gigabyte H81M-S2PH                         | 2         | 0.36%   |
| Gigabyte B460MDS3HV2                       | 2         | 0.36%   |
| Dell XPS 9320                              | 2         | 0.36%   |
| Dell Vostro 3888                           | 2         | 0.36%   |
| Dell OptiPlex 9010                         | 2         | 0.36%   |
| Dell OptiPlex 790                          | 2         | 0.36%   |
| Dell OptiPlex 7050                         | 2         | 0.36%   |
| Dell OptiPlex 3050                         | 2         | 0.36%   |
| Dell Latitude 5285                         | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 28        | 5.01%   |
| Dell OptiPlex      | 28        | 5.01%   |
| Dell Inspiron      | 23        | 4.11%   |
| HP Pavilion        | 20        | 3.58%   |
| ASUS VivoBook      | 16        | 2.86%   |
| Lenovo IdeaPad     | 15        | 2.68%   |
| ASUS TUF           | 15        | 2.68%   |
| ASUS PRIME         | 14        | 2.5%    |
| Acer Aspire        | 13        | 2.33%   |
| Toshiba Satellite  | 12        | 2.15%   |
| Dell Latitude      | 12        | 2.15%   |
| ASUS ROG           | 12        | 2.15%   |
| Unknown            | 12        | 2.15%   |
| HP Laptop          | 11        | 1.97%   |
| Valve Jupiter      | 10        | 1.79%   |
| Lenovo ThinkCentre | 9         | 1.61%   |
| Microsoft Surface  | 7         | 1.25%   |
| Lenovo Legion      | 6         | 1.07%   |
| HP ENVY            | 6         | 1.07%   |
| Dell XPS           | 6         | 1.07%   |
| Dell Vostro        | 6         | 1.07%   |
| Dell Precision     | 6         | 1.07%   |
| Lenovo Yoga        | 5         | 0.89%   |
| Dell G3            | 5         | 0.89%   |
| ASUS ASUS          | 5         | 0.89%   |
| ASUS All           | 5         | 0.89%   |
| HP EliteDesk       | 4         | 0.72%   |
| ASUS ZenBook       | 4         | 0.72%   |
| MSI Modern         | 3         | 0.54%   |
| MSI GF63           | 3         | 0.54%   |
| Lenovo IdeaPadFlex | 3         | 0.54%   |
| HP ProBook         | 3         | 0.54%   |
| HP Notebook        | 3         | 0.54%   |
| HP Compaq          | 3         | 0.54%   |
| HP 15              | 3         | 0.54%   |
| ASRock X570        | 3         | 0.54%   |
| Apple MacBookPro11 | 3         | 0.54%   |
| Valve Galileo      | 2         | 0.36%   |
| MSI MS-7C90        | 2         | 0.36%   |
| MSI MS-7C37        | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 59        | 10.55%  |
| 2019    | 59        | 10.55%  |
| 2018    | 56        | 10.02%  |
| 2021    | 47        | 8.41%   |
| 2012    | 40        | 7.16%   |
| 2013    | 32        | 5.72%   |
| 2024    | 29        | 5.19%   |
| 2017    | 29        | 5.19%   |
| 2011    | 29        | 5.19%   |
| 2023    | 28        | 5.01%   |
| 2014    | 28        | 5.01%   |
| 2022    | 25        | 4.47%   |
| 2016    | 25        | 4.47%   |
| 2015    | 22        | 3.94%   |
| 2010    | 14        | 2.5%    |
| 2009    | 11        | 1.97%   |
| 2008    | 7         | 1.25%   |
| 2007    | 7         | 1.25%   |
| 2025    | 5         | 0.89%   |
| 2006    | 3         | 0.54%   |
| Unknown | 3         | 0.54%   |
| 2002    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 290       | 51.88%  |
| Desktop        | 197       | 35.24%  |
| Convertible    | 29        | 5.19%   |
| Tablet         | 21        | 3.76%   |
| Mini pc        | 9         | 1.61%   |
| All in one     | 6         | 1.07%   |
| Server         | 3         | 0.54%   |
| Phone          | 2         | 0.36%   |
| Other          | 1         | 0.18%   |
| System on chip | 1         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 531       | 93.82%  |
| Enabled  | 35        | 6.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 557       | 99.64%  |
| Yes  | 2         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 129       | 22.43%  |
| 4.01-8.0        | 119       | 20.7%   |
| 8.01-16.0       | 109       | 18.96%  |
| 32.01-64.0      | 81        | 14.09%  |
| 3.01-4.0        | 72        | 12.52%  |
| 1.01-2.0        | 20        | 3.48%   |
| 24.01-32.0      | 19        | 3.3%    |
| 64.01-256.0     | 17        | 2.96%   |
| 2.01-3.0        | 6         | 1.04%   |
| More than 256.0 | 2         | 0.35%   |
| 0.51-1.0        | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 163       | 25.63%  |
| 2.01-3.0   | 161       | 25.31%  |
| 4.01-8.0   | 132       | 20.75%  |
| 3.01-4.0   | 115       | 18.08%  |
| 8.01-16.0  | 35        | 5.5%    |
| 0.51-1.0   | 23        | 3.62%   |
| 16.01-24.0 | 5         | 0.79%   |
| 0.01-0.5   | 1         | 0.16%   |
| Unknown    | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 348       | 59.08%  |
| 2      | 143       | 24.28%  |
| 3      | 60        | 10.19%  |
| 4      | 20        | 3.4%    |
| 5      | 9         | 1.53%   |
| 6      | 6         | 1.02%   |
| 0      | 2         | 0.34%   |
| 7      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 408       | 72.47%  |
| Yes       | 155       | 27.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 445       | 78.9%   |
| No        | 119       | 21.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 471       | 83.51%  |
| No        | 93        | 16.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 412       | 72.66%  |
| No        | 155       | 27.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 559       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Riyadh               | 221       | 36.53%  |
| Jeddah               | 126       | 20.83%  |
| Makkah               | 61        | 10.08%  |
| Dammam               | 55        | 9.09%   |
| Medina               | 35        | 5.79%   |
| Al Qatif             | 19        | 3.14%   |
| Baq`a' ash Sharqiyah | 18        | 2.98%   |
| Khobar               | 14        | 2.31%   |
| Ta'if                | 13        | 2.15%   |
| Dhahran              | 8         | 1.32%   |
| Buraidah             | 7         | 1.16%   |
| Abha                 | 5         | 0.83%   |
| Jubail               | 4         | 0.66%   |
| Thuwal               | 3         | 0.5%    |
| Al Kharj             | 3         | 0.5%    |
| Najran               | 2         | 0.33%   |
| At Tuwal             | 2         | 0.33%   |
| Al Faruq             | 2         | 0.33%   |
| Yanbu                | 1         | 0.17%   |
| Shaqra               | 1         | 0.17%   |
| Sayhat               | 1         | 0.17%   |
| Jizan                | 1         | 0.17%   |
| Bisha                | 1         | 0.17%   |
| Al Majāridah        | 1         | 0.17%   |
| Al Hufuf             | 1         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 127       | 202    | 14.82%  |
| Samsung Electronics          | 95        | 137    | 11.09%  |
| Seagate                      | 90        | 128    | 10.5%   |
| Kingston                     | 85        | 136    | 9.92%   |
| SanDisk                      | 68        | 74     | 7.93%   |
| Toshiba                      | 62        | 80     | 7.23%   |
| Unknown                      | 34        | 55     | 3.97%   |
| SK hynix                     | 19        | 43     | 2.22%   |
| Micron Technology            | 18        | 23     | 2.1%    |
| Intel                        | 18        | 30     | 2.1%    |
| Crucial                      | 18        | 23     | 2.1%    |
| Kingston Technology Company  | 17        | 21     | 1.98%   |
| Lexar                        | 14        | 15     | 1.63%   |
| Phison Electronics           | 13        | 24     | 1.52%   |
| Apple                        | 12        | 15     | 1.4%    |
| Team                         | 10        | 12     | 1.17%   |
| Micron/Crucial Technology    | 10        | 12     | 1.17%   |
| Hitachi                      | 10        | 11     | 1.17%   |
| HGST                         | 10        | 15     | 1.17%   |
| China                        | 10        | 12     | 1.17%   |
| MAXIO Technology (Hangzhou)  | 8         | 12     | 0.93%   |
| Silicon Motion               | 7         | 8      | 0.82%   |
| KIOXIA                       | 7         | 11     | 0.82%   |
| JMicron Technology           | 7         | 8      | 0.82%   |
| Phison                       | 6         | 7      | 0.7%    |
| PNY                          | 5         | 6      | 0.58%   |
| Unknown                      | 5         | 5      | 0.58%   |
| XrayDisk                     | 4         | 6      | 0.47%   |
| Realtek Semiconductor        | 4         | 4      | 0.47%   |
| HS-SSD-C100                  | 4         | 5      | 0.47%   |
| Hewlett-Packard              | 4         | 6      | 0.47%   |
| SPCC                         | 3         | 4      | 0.35%   |
| Shenzhen Longsys Electronics | 3         | 3      | 0.35%   |
| KingSpec                     | 3         | 3      | 0.35%   |
| KESU                         | 3         | 3      | 0.35%   |
| Corsair                      | 3         | 3      | 0.35%   |
| SPCC Sol                     | 2         | 2      | 0.23%   |
| LITEON                       | 2         | 2      | 0.23%   |
| Fujitsu                      | 2         | 3      | 0.23%   |
| ASMT                         | 2         | 2      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 29        | 3.09%   |
| Kingston SA400S37480G 480GB SSD                    | 18        | 1.92%   |
| Toshiba MQ04ABF100 1TB                             | 17        | 1.81%   |
| Seagate ST1000LM035-1RK172 1TB                     | 14        | 1.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 12        | 1.28%   |
| Toshiba MQ01ABD100 1TB                             | 9         | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 9         | 0.96%   |
| Kingston Company SNV2S1000G 1TB                    | 8         | 0.85%   |
| Kingston SA400S37960G 960GB SSD                    | 8         | 0.85%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 7         | 0.75%   |
| WDC WD10EZEX-75WN4A1 1TB                           | 7         | 0.75%   |
| Seagate ST500DM002-1BD142 500GB                    | 7         | 0.75%   |
| SanDisk SSD PLUS 240GB                             | 6         | 0.64%   |
| SanDisk NVMe SSD Drive 1TB                         | 6         | 0.64%   |
| Phison PS5013 E13 NVMe Controller 500GB            | 6         | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                | 6         | 0.64%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB   | 6         | 0.64%   |
| Kingston SA400S37120G 120GB SSD                    | 6         | 0.64%   |
| WDC WD5000AAKX-75U6AA0 500GB                       | 5         | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 5         | 0.53%   |
| Toshiba MQ01ABF050 500GB                           | 5         | 0.53%   |
| Samsung SSD 860 EVO 1TB                            | 5         | 0.53%   |
| Samsung NVMe SSD Drive 1024GB                      | 5         | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                        | 5         | 0.53%   |
| Unknown                                            | 5         | 0.53%   |
| WDC WD1003FZEX-00MK2A0 1TB                         | 4         | 0.43%   |
| Unknown MMC Card  64GB                             | 4         | 0.43%   |
| Unknown MMC Card  32GB                             | 4         | 0.43%   |
| Seagate ST1000DM010-2EP102 1TB                     | 4         | 0.43%   |
| Sandisk WD PC SN740 SDDPNQE-2T00-1102 2TB          | 4         | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 4         | 0.43%   |
| SanDisk SSD PLUS 480GB                             | 4         | 0.43%   |
| Samsung SSD 860 EVO 500GB                          | 4         | 0.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 4         | 0.43%   |
| Phison E12 NVMe Controller 1TB                     | 4         | 0.43%   |
| Lexar 128GB SSD                                    | 4         | 0.43%   |
| JMicron Tech 250GB                                 | 4         | 0.43%   |
| Intel SSDPEKNU512GZ 512GB                          | 4         | 0.43%   |
| Intel SSD 660P Series 512GB                        | 4         | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 3         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 105       | 174    | 36.21%  |
| Seagate             | 89        | 127    | 30.69%  |
| Toshiba             | 58        | 68     | 20%     |
| Hitachi             | 10        | 11     | 3.45%   |
| HGST                | 10        | 15     | 3.45%   |
| Samsung Electronics | 3         | 4      | 1.03%   |
| KESU                | 3         | 3      | 1.03%   |
| JMicron Technology  | 3         | 3      | 1.03%   |
| Apple               | 3         | 3      | 1.03%   |
| Unknown             | 2         | 4      | 0.69%   |
| Fujitsu             | 2         | 3      | 0.69%   |
| Maxtor              | 1         | 1      | 0.34%   |
| ASMT                | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 73        | 113    | 30.67%  |
| Samsung Electronics | 30        | 48     | 12.61%  |
| SanDisk             | 28        | 29     | 11.76%  |
| Crucial             | 17        | 20     | 7.14%   |
| WDC                 | 13        | 16     | 5.46%   |
| Lexar               | 11        | 11     | 4.62%   |
| China               | 10        | 12     | 4.2%    |
| Team                | 7         | 9      | 2.94%   |
| Apple               | 7         | 8      | 2.94%   |
| PNY                 | 4         | 5      | 1.68%   |
| Micron Technology   | 4         | 6      | 1.68%   |
| SK hynix            | 3         | 5      | 1.26%   |
| KingSpec            | 3         | 3      | 1.26%   |
| Hewlett-Packard     | 3         | 5      | 1.26%   |
| Unknown             | 3         | 3      | 1.26%   |
| XrayDisk            | 2         | 3      | 0.84%   |
| SPCC Sol            | 2         | 2      | 0.84%   |
| LITEON              | 2         | 2      | 0.84%   |
| A-DATA Technology   | 2         | 2      | 0.84%   |
| YS                  | 1         | 2      | 0.42%   |
| Transcend           | 1         | 1      | 0.42%   |
| Thinkplus           | 1         | 1      | 0.42%   |
| SPCC                | 1         | 2      | 0.42%   |
| OYUNKEY             | 1         | 1      | 0.42%   |
| NVMe                | 1         | 1      | 0.42%   |
| KingFast            | 1         | 1      | 0.42%   |
| KingDian            | 1         | 1      | 0.42%   |
| Intel               | 1         | 4      | 0.42%   |
| HPE                 | 1         | 1      | 0.42%   |
| Hoodisk             | 1         | 1      | 0.42%   |
| GLOWAY              | 1         | 2      | 0.42%   |
| G-DRIVE             | 1         | 1      | 0.42%   |
| Corsair             | 1         | 1      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 257       | 400    | 33.46%  |
| HDD     | 250       | 417    | 32.55%  |
| SSD     | 212       | 322    | 27.6%   |
| MMC     | 32        | 52     | 4.17%   |
| Unknown | 17        | 22     | 2.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 370       | 728    | 54.01%  |
| NVMe | 257       | 396    | 37.52%  |
| MMC  | 32        | 52     | 4.67%   |
| SAS  | 26        | 37     | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 223       | 373    | 46.85%  |
| 0.51-1.0   | 187       | 276    | 39.29%  |
| 1.01-2.0   | 39        | 54     | 8.19%   |
| 3.01-4.0   | 17        | 21     | 3.57%   |
| 2.01-3.0   | 6         | 7      | 1.26%   |
| 4.01-10.0  | 3         | 7      | 0.63%   |
| 10.01-20.0 | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 130       | 21.31%  |
| 101-250        | 124       | 20.33%  |
| 501-1000       | 124       | 20.33%  |
| 1001-2000      | 57        | 9.34%   |
| 51-100         | 40        | 6.56%   |
| 1-20           | 36        | 5.9%    |
| More than 3000 | 34        | 5.57%   |
| 2001-3000      | 27        | 4.43%   |
| 21-50          | 26        | 4.26%   |
| Unknown        | 12        | 1.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 230       | 35.6%   |
| 21-50          | 136       | 21.05%  |
| 51-100         | 76        | 11.76%  |
| 101-250        | 74        | 11.46%  |
| 251-500        | 51        | 7.89%   |
| 501-1000       | 29        | 4.49%   |
| 1001-2000      | 20        | 3.1%    |
| Unknown        | 12        | 1.86%   |
| More than 3000 | 10        | 1.55%   |
| 2001-3000      | 7         | 1.08%   |
| 0              | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB    | 2         | 2      | 5.13%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 2      | 5.13%   |
| Unknown                            | 2         | 2      | 5.13%   |
| YS SSD 240GB                       | 1         | 1      | 2.56%   |
| WDC WD5000AAKS-00WWPA0 500GB       | 1         | 1      | 2.56%   |
| WDC WD40PURZ-85AKKY0 4TB           | 1         | 1      | 2.56%   |
| WDC WD40PURX-64GVNY0 4TB           | 1         | 1      | 2.56%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 2.56%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1         | 1      | 2.56%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1         | 1      | 2.56%   |
| WDC WD1600AAJS-60B4A0 160GB        | 1         | 1      | 2.56%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 2.56%   |
| WDC WD10SPZX-08Z10 1TB             | 1         | 1      | 2.56%   |
| WDC WD10PURZ-85U8XY0 1TB           | 1         | 1      | 2.56%   |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 2.56%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 2.56%   |
| WDC WD10EUCX-73YZ1Y0 1TB           | 1         | 1      | 2.56%   |
| WDC WD Green 2.5 480GB             | 1         | 1      | 2.56%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 2.56%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 2.56%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 2.56%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 2.56%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB    | 1         | 1      | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 2.56%   |
| Seagate ST1000DM003-9YN162 1TB     | 1         | 1      | 2.56%   |
| Seagate ST1000DM003-1CH162 1TB     | 1         | 1      | 2.56%   |
| SanDisk SSD PLUS 480GB             | 1         | 1      | 2.56%   |
| OYUNKEY SSD 120GB                  | 1         | 1      | 2.56%   |
| Kingston SMS200S3240G 240GB SSD    | 1         | 1      | 2.56%   |
| Kingston SA400S37480G 480GB SSD    | 1         | 1      | 2.56%   |
| HPE MK001920GWHRU 2TB SSD          | 1         | 1      | 2.56%   |
| Hitachi HDS721032CLA362 320GB      | 1         | 1      | 2.56%   |
| HGST HTS541075A9E680 752GB         | 1         | 1      | 2.56%   |
| Crucial CT525MX300SSD1 528GB       | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 14        | 14     | 36.84%  |
| Seagate  | 10        | 11     | 26.32%  |
| Toshiba  | 3         | 3      | 7.89%   |
| Kingston | 2         | 2      | 5.26%   |
| Unknown  | 2         | 2      | 5.26%   |
| YS       | 1         | 1      | 2.63%   |
| SanDisk  | 1         | 1      | 2.63%   |
| OYUNKEY  | 1         | 1      | 2.63%   |
| HPE      | 1         | 1      | 2.63%   |
| Hitachi  | 1         | 1      | 2.63%   |
| HGST     | 1         | 1      | 2.63%   |
| Crucial  | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 13     | 46.43%  |
| Seagate | 10        | 11     | 35.71%  |
| Toshiba | 3         | 3      | 10.71%  |
| Hitachi | 1         | 1      | 3.57%   |
| HGST    | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 29     | 76.47%  |
| SSD  | 8         | 10     | 23.53%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| HGST HTS545050A7E380 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 377       | 814    | 61.5%   |
| Works    | 204       | 359    | 33.28%  |
| Malfunc  | 31        | 39     | 5.06%   |
| Failed   | 1         | 1      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 382       | 51.76%  |
| Samsung Electronics              | 71        | 9.62%   |
| AMD                              | 62        | 8.4%    |
| SanDisk                          | 47        | 6.37%   |
| Kingston Technology Company      | 30        | 4.07%   |
| Phison Electronics               | 21        | 2.85%   |
| SK hynix                         | 16        | 2.17%   |
| Micron Technology                | 14        | 1.9%    |
| Micron/Crucial Technology        | 12        | 1.63%   |
| Silicon Motion                   | 10        | 1.36%   |
| MAXIO Technology (Hangzhou)      | 10        | 1.36%   |
| ASMedia Technology               | 9         | 1.22%   |
| KIOXIA                           | 8         | 1.08%   |
| Realtek Semiconductor            | 6         | 0.81%   |
| Toshiba America Info Systems     | 5         | 0.68%   |
| Shenzhen Longsys Electronics     | 4         | 0.54%   |
| JMicron Technology               | 4         | 0.54%   |
| Hosin Global Electronics         | 3         | 0.41%   |
| Broadcom / LSI                   | 3         | 0.41%   |
| Yangtze Memory Technologies      | 2         | 0.27%   |
| Union Memory (Shenzhen)          | 2         | 0.27%   |
| Nvidia                           | 2         | 0.27%   |
| Marvell Technology Group         | 2         | 0.27%   |
| Apple                            | 2         | 0.27%   |
| ADATA Technology                 | 2         | 0.27%   |
| VIA Technologies                 | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| Shenzhen Wodposit Electronics    | 1         | 0.14%   |
| Seagate Technology               | 1         | 0.14%   |
| Netac Technology                 | 1         | 0.14%   |
| LSI Logic / Symbios Logic        | 1         | 0.14%   |
| Lite-On Technology               | 1         | 0.14%   |
| INNOGRIT                         | 1         | 0.14%   |
| Biwin Storage Technology         | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 39        | 4.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 31        | 3.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 2.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 2.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 22        | 2.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 21        | 2.59%   |
| Intel SATA Controller [RAID Mode]                                              | 18        | 2.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 18        | 2.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 17        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 2.1%    |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 1.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 13        | 1.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 1.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 11        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10        | 1.23%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 9         | 1.11%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 9         | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 1.11%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 9         | 1.11%   |
| AMD 400 Series Chipset SATA Controller                                         | 9         | 1.11%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 8         | 0.99%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 8         | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 0.99%   |
| Intel SSD 660P Series                                                          | 8         | 0.99%   |
| Intel RST Volume Management Device Controller                                  | 8         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                         | 8         | 0.99%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 7         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 7         | 0.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 7         | 0.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 0.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7         | 0.86%   |
| AMD 600 Series Chipset SATA Controller                                         | 7         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 6         | 0.74%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 6         | 0.74%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 6         | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 363       | 49.79%  |
| NVMe | 257       | 35.25%  |
| RAID | 70        | 9.6%    |
| IDE  | 38        | 5.21%   |
| SAS  | 1         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 457       | 81.75%  |
| AMD      | 98        | 17.53%  |
| Qualcomm | 2         | 0.36%   |
| ARM      | 2         | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 2.5%    |
| AMD Custom APU 0405                           | 10        | 1.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.25%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.07%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 1.07%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.07%   |
| Intel Core Ultra 9 185H                       | 5         | 0.89%   |
| Intel Core i9-14900K                          | 5         | 0.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 5         | 0.89%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 0.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.89%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 0.71%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 0.71%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 4         | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4         | 0.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.71%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.71%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 4         | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.71%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.71%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.71%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 4         | 0.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.71%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 0.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.71%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 0.71%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 0.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.71%   |
| Intel Core Ultra 7 155H                       | 3         | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 0.53%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.53%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 142       | 25.31%  |
| Intel Core i5           | 125       | 22.28%  |
| Other                   | 76        | 13.55%  |
| Intel Core i3           | 38        | 6.77%   |
| AMD Ryzen 5             | 33        | 5.88%   |
| AMD Ryzen 7             | 26        | 4.63%   |
| Intel Celeron           | 23        | 4.1%    |
| Intel Core 2 Duo        | 15        | 2.67%   |
| AMD Ryzen 9             | 15        | 2.67%   |
| Intel Xeon              | 11        | 1.96%   |
| Intel Core              | 11        | 1.96%   |
| Intel Core i9           | 9         | 1.6%    |
| Intel Atom              | 6         | 1.07%   |
| Intel Pentium Dual-Core | 5         | 0.89%   |
| AMD FX                  | 4         | 0.71%   |
| Intel Pentium           | 3         | 0.53%   |
| Intel Xeon Silver       | 1         | 0.18%   |
| Intel Xeon Gold         | 1         | 0.18%   |
| Intel Pentium Silver    | 1         | 0.18%   |
| Intel Pentium Dual      | 1         | 0.18%   |
| Intel Pentium 4         | 1         | 0.18%   |
| Intel Mobile Pentium 4  | 1         | 0.18%   |
| Intel Genuine           | 1         | 0.18%   |
| Intel Core m5           | 1         | 0.18%   |
| Intel Core m3           | 1         | 0.18%   |
| Intel Core 2 Quad       | 1         | 0.18%   |
| Intel Core 2 Extreme    | 1         | 0.18%   |
| Intel Core 2            | 1         | 0.18%   |
| ARM ARMv7               | 1         | 0.18%   |
| AMD Ryzen Threadripper  | 1         | 0.18%   |
| AMD Ryzen 5 PRO         | 1         | 0.18%   |
| AMD Ryzen 3             | 1         | 0.18%   |
| AMD E2                  | 1         | 0.18%   |
| AMD A4                  | 1         | 0.18%   |
| AMD A12                 | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 207       | 36.96%  |
| 2      | 160       | 28.57%  |
| 6      | 71        | 12.68%  |
| 8      | 52        | 9.29%   |
| 16     | 17        | 3.04%   |
| 12     | 13        | 2.32%   |
| 10     | 13        | 2.32%   |
| 14     | 8         | 1.43%   |
| 1      | 8         | 1.43%   |
| 24     | 6         | 1.07%   |
| 20     | 2         | 0.36%   |
| 40     | 1         | 0.18%   |
| 32     | 1         | 0.18%   |
| 22     | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 555       | 99.28%  |
| 2      | 3         | 0.54%   |
| 16     | 1         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 423       | 75.27%  |
| 1      | 138       | 24.56%  |
| 8      | 1         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 551       | 98.39%  |
| Unknown        | 7         | 1.25%   |
| 32-bit         | 2         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 345       | 57.98%  |
| 0x306a9    | 22        | 3.7%    |
| 0x206a7    | 18        | 3.03%   |
| 0x306c3    | 15        | 2.52%   |
| 0x1067a    | 15        | 2.52%   |
| 0x40651    | 12        | 2.02%   |
| 0x906e9    | 10        | 1.68%   |
| 0x806c1    | 10        | 1.68%   |
| 0x906ea    | 8         | 1.34%   |
| 0x806ea    | 8         | 1.34%   |
| 0x806e9    | 8         | 1.34%   |
| 0x406e3    | 8         | 1.34%   |
| 0x806ec    | 7         | 1.18%   |
| 0x706e5    | 6         | 1.01%   |
| 0x706a1    | 5         | 0.84%   |
| 0xa0653    | 4         | 0.67%   |
| 0xa0652    | 4         | 0.67%   |
| 0x306d4    | 4         | 0.67%   |
| 0x20655    | 4         | 0.67%   |
| 0x08108109 | 4         | 0.67%   |
| 0xa06a4    | 3         | 0.5%    |
| 0x906ed    | 3         | 0.5%    |
| 0x906a3    | 3         | 0.5%    |
| 0x506c9    | 3         | 0.5%    |
| 0x30673    | 3         | 0.5%    |
| 0x20652    | 3         | 0.5%    |
| 0xa0655    | 2         | 0.34%   |
| 0x806eb    | 2         | 0.34%   |
| 0x706a8    | 2         | 0.34%   |
| 0x406c4    | 2         | 0.34%   |
| 0x306e4    | 2         | 0.34%   |
| 0x106e5    | 2         | 0.34%   |
| 0x0a70410a | 2         | 0.34%   |
| 0x0a201016 | 2         | 0.34%   |
| 0x08701021 | 2         | 0.34%   |
| 0x08701013 | 2         | 0.34%   |
| 0x08600106 | 2         | 0.34%   |
| 0x0810100b | 2         | 0.34%   |
| 0x0800820d | 2         | 0.34%   |
| 0x06000852 | 2         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 108       | 19.15%  |
| Unknown           | 68        | 12.06%  |
| Haswell           | 48        | 8.51%   |
| IvyBridge         | 44        | 7.8%    |
| SandyBridge       | 35        | 6.21%   |
| Skylake           | 29        | 5.14%   |
| TigerLake         | 26        | 4.61%   |
| Zen 3             | 23        | 4.08%   |
| CometLake         | 23        | 4.08%   |
| Alderlake Hybrid  | 21        | 3.72%   |
| Zen 2             | 19        | 3.37%   |
| Penryn            | 19        | 3.37%   |
| Icelake           | 15        | 2.66%   |
| Zen+              | 14        | 2.48%   |
| Broadwell         | 13        | 2.3%    |
| Goldmont plus     | 11        | 1.95%   |
| Westmere          | 9         | 1.6%    |
| Silvermont        | 8         | 1.42%   |
| Core              | 7         | 1.24%   |
| Nehalem           | 5         | 0.89%   |
| Piledriver        | 4         | 0.71%   |
| Goldmont          | 4         | 0.71%   |
| Zen               | 2         | 0.35%   |
| NetBurst          | 2         | 0.35%   |
| Meteorlake Hybrid | 2         | 0.35%   |
| Tremont           | 1         | 0.18%   |
| Excavator         | 1         | 0.18%   |
| Bulldozer         | 1         | 0.18%   |
| Bonnell           | 1         | 0.18%   |
| Bobcat            | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 350       | 50.65%  |
| Nvidia                           | 204       | 29.52%  |
| AMD                              | 131       | 18.96%  |
| Matrox Electronics Systems       | 2         | 0.29%   |
| VIA Technologies                 | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| ATI Technologies                 | 1         | 0.14%   |
| ASPEED Technology                | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 29        | 4.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 26        | 3.7%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 22        | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 19        | 2.7%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                      | 16        | 2.28%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                       | 15        | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 14        | 1.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 14        | 1.99%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                         | 11        | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 11        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 10        | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 10        | 1.42%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 10        | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 10        | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 9         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 1.14%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                      | 8         | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 8         | 1.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 8         | 1.14%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 8         | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 7         | 1%      |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                       | 7         | 1%      |
| Intel Core Processor Integrated Graphics Controller                           | 7         | 1%      |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 7         | 1%      |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 7         | 1%      |
| AMD Lucienne                                                                  | 7         | 1%      |
| Nvidia TU117M [GeForce MX450]                                                 | 6         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 6         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 6         | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 6         | 0.85%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                      | 6         | 0.85%   |
| AMD Phoenix1                                                                  | 6         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 5         | 0.71%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 5         | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 5         | 0.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 0.71%   |
| Intel Iris Plus Graphics G7                                                   | 5         | 0.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 5         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 5         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 231       | 40.81%  |
| 1 x Nvidia      | 103       | 18.2%   |
| 1 x AMD         | 90        | 15.9%   |
| Intel + Nvidia  | 86        | 15.19%  |
| Intel + AMD     | 25        | 4.42%   |
| AMD + Nvidia    | 14        | 2.47%   |
| 2 x AMD         | 6         | 1.06%   |
| Other           | 4         | 0.71%   |
| 2 x Intel       | 2         | 0.35%   |
| 1 x Matrox      | 2         | 0.35%   |
| 1 x VIA         | 1         | 0.18%   |
| 1 x SiS         | 1         | 0.18%   |
| Nvidia + ASPEED | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 440       | 76.66%  |
| Proprietary | 101       | 17.6%   |
| Unknown     | 33        | 5.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 396       | 68.51%  |
| 1.01-2.0   | 54        | 9.34%   |
| 3.01-4.0   | 38        | 6.57%   |
| 7.01-8.0   | 29        | 5.02%   |
| 0.01-0.5   | 22        | 3.81%   |
| 0.51-1.0   | 18        | 3.11%   |
| 8.01-16.0  | 11        | 1.9%    |
| 2.01-3.0   | 6         | 1.04%   |
| 5.01-6.0   | 2         | 0.35%   |
| 32.01-64.0 | 1         | 0.17%   |
| 24.01-32.0 | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 75        | 12.84%  |
| Samsung Electronics     | 63        | 10.79%  |
| AU Optronics            | 53        | 9.08%   |
| LG Display              | 52        | 8.9%    |
| Chimei Innolux          | 52        | 8.9%    |
| Dell                    | 36        | 6.16%   |
| BenQ                    | 30        | 5.14%   |
| Lenovo                  | 22        | 3.77%   |
| Goldstar                | 21        | 3.6%    |
| Apple                   | 17        | 2.91%   |
| Sharp                   | 15        | 2.57%   |
| Hewlett-Packard         | 13        | 2.23%   |
| Valve                   | 12        | 2.05%   |
| Acer                    | 9         | 1.54%   |
| Unknown                 | 8         | 1.37%   |
| ViewSonic               | 7         | 1.2%    |
| Sony                    | 7         | 1.2%    |
| ASUSTek Computer        | 6         | 1.03%   |
| AOC                     | 6         | 1.03%   |
| PANDA                   | 5         | 0.86%   |
| InfoVision              | 5         | 0.86%   |
| Gigabyte Technology     | 5         | 0.86%   |
| Chi Mei Optoelectronics | 4         | 0.68%   |
| Ancor Communications    | 4         | 0.68%   |
| SKY                     | 3         | 0.51%   |
| Xiaomi                  | 2         | 0.34%   |
| Unknown (XXX)           | 2         | 0.34%   |
| TMX                     | 2         | 0.34%   |
| TCL                     | 2         | 0.34%   |
| Skyworth                | 2         | 0.34%   |
| SKG                     | 2         | 0.34%   |
| RTK                     | 2         | 0.34%   |
| Philips                 | 2         | 0.34%   |
| Mi                      | 2         | 0.34%   |
| LG Electronics          | 2         | 0.34%   |
| InnoLux Display         | 2         | 0.34%   |
| HUAWEI                  | 2         | 0.34%   |
| CL@                     | 2         | 0.34%   |
| ___                     | 1         | 0.17%   |
| WIT                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 10        | 1.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 7         | 1.16%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch            | 5         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 5         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch   | 4         | 0.67%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                   | 4         | 0.67%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                   | 4         | 0.67%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                   | 4         | 0.67%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                    | 4         | 0.67%   |
| BenQ EX3203R BNQ7F66 2560x1440 698x393mm 31.5-inch                      | 4         | 0.67%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 4         | 0.67%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch          | 4         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 4         | 0.67%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch        | 3         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch    | 3         | 0.5%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 3         | 0.5%    |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch                | 3         | 0.5%    |
| Lenovo LEN G34w-10 LEN66A1 3440x1440 797x334mm 34.0-inch                | 3         | 0.5%    |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                   | 3         | 0.5%    |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                       | 3         | 0.5%    |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                   | 3         | 0.5%    |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                   | 3         | 0.5%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 3         | 0.5%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 3         | 0.5%    |
| BenQ VZ2350 BNQ7B36 1920x1080 509x286mm 23.0-inch                       | 3         | 0.5%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                       | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 3         | 0.5%    |
| Xiaomi Mi TV XMD0076 3840x2160 1110x620mm 50.1-inch                     | 2         | 0.33%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                     | 2         | 0.33%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                    | 2         | 0.33%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                     | 2         | 0.33%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                 | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch   | 2         | 0.33%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch            | 2         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 2         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 250       | 44.33%  |
| 1366x768 (WXGA)    | 118       | 20.92%  |
| 3840x2160 (4K)     | 55        | 9.75%   |
| 2560x1440 (QHD)    | 34        | 6.03%   |
| 800x1280           | 12        | 2.13%   |
| 1920x1200 (WUXGA)  | 10        | 1.77%   |
| 2880x1800          | 9         | 1.6%    |
| 1280x800 (WXGA)    | 8         | 1.42%   |
| 2160x1440          | 7         | 1.24%   |
| 3440x1440          | 6         | 1.06%   |
| 2880x1920          | 6         | 1.06%   |
| 1600x900 (HD+)     | 6         | 1.06%   |
| 2560x1600          | 5         | 0.89%   |
| 1440x900 (WXGA+)   | 5         | 0.89%   |
| Unknown            | 5         | 0.89%   |
| 2560x1080          | 4         | 0.71%   |
| 1680x1050 (WSXGA+) | 4         | 0.71%   |
| 1280x1024 (SXGA)   | 4         | 0.71%   |
| 3840x2400          | 3         | 0.53%   |
| 1920x1280          | 3         | 0.53%   |
| 3840x1600          | 2         | 0.35%   |
| 3840x1080          | 2         | 0.35%   |
| 2256x1504          | 2         | 0.35%   |
| 7040x1440          | 1         | 0.18%   |
| 3456x2160          | 1         | 0.18%   |
| 2736x1824          | 1         | 0.18%   |
| 1360x768           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 159       | 26.99%  |
| 13      | 63        | 10.7%   |
| 14      | 56        | 9.51%   |
| 27      | 47        | 7.98%   |
| 24      | 33        | 5.6%    |
| 23      | 28        | 4.75%   |
| 31      | 26        | 4.41%   |
| 21      | 21        | 3.57%   |
| Unknown | 18        | 3.06%   |
| 18      | 14        | 2.38%   |
| 7       | 13        | 2.21%   |
| 54      | 12        | 2.04%   |
| 12      | 10        | 1.7%    |
| 84      | 9         | 1.53%   |
| 34      | 9         | 1.53%   |
| 17      | 9         | 1.53%   |
| 16      | 9         | 1.53%   |
| 72      | 6         | 1.02%   |
| 32      | 6         | 1.02%   |
| 19      | 5         | 0.85%   |
| 11      | 4         | 0.68%   |
| 63      | 3         | 0.51%   |
| 52      | 3         | 0.51%   |
| 46      | 3         | 0.51%   |
| 40      | 3         | 0.51%   |
| 22      | 3         | 0.51%   |
| 82      | 2         | 0.34%   |
| 48      | 2         | 0.34%   |
| 8       | 2         | 0.34%   |
| 86      | 1         | 0.17%   |
| 75      | 1         | 0.17%   |
| 64      | 1         | 0.17%   |
| 57      | 1         | 0.17%   |
| 55      | 1         | 0.17%   |
| 42      | 1         | 0.17%   |
| 37      | 1         | 0.17%   |
| 29      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 25      | 1         | 0.17%   |
| 20      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 246       | 42.34%  |
| 501-600     | 101       | 17.38%  |
| 201-300     | 53        | 9.12%   |
| 401-500     | 44        | 7.57%   |
| 601-700     | 29        | 4.99%   |
| 1001-1500   | 27        | 4.65%   |
| 1501-2000   | 18        | 3.1%    |
| Unknown     | 18        | 3.1%    |
| 701-800     | 14        | 2.41%   |
| 1-100       | 12        | 2.07%   |
| 351-400     | 10        | 1.72%   |
| 801-900     | 5         | 0.86%   |
| 101-200     | 3         | 0.52%   |
| 901-1000    | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 428       | 79.11%  |
| 16/10   | 45        | 8.32%   |
| 3/2     | 19        | 3.51%   |
| Unknown | 17        | 3.14%   |
| 21/9    | 11        | 2.03%   |
| 0.67    | 10        | 1.85%   |
| 5/4     | 4         | 0.74%   |
| 0.63    | 2         | 0.37%   |
| 0.62    | 2         | 0.37%   |
| 4/3     | 1         | 0.18%   |
| 32/9    | 1         | 0.18%   |
| 0.56    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 159       | 27.18%  |
| 81-90          | 95        | 16.24%  |
| 201-250        | 67        | 11.45%  |
| 301-350        | 49        | 8.38%   |
| More than 1000 | 41        | 7.01%   |
| 351-500        | 41        | 7.01%   |
| 71-80          | 23        | 3.93%   |
| 141-150        | 18        | 3.08%   |
| Unknown        | 18        | 3.08%   |
| 1-40           | 15        | 2.56%   |
| 251-300        | 11        | 1.88%   |
| 151-200        | 11        | 1.88%   |
| 61-70          | 10        | 1.71%   |
| 501-1000       | 9         | 1.54%   |
| 111-120        | 8         | 1.37%   |
| 121-130        | 5         | 0.85%   |
| 51-60          | 4         | 0.68%   |
| 91-100         | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 162       | 28.13%  |
| 121-160       | 155       | 26.91%  |
| 101-120       | 143       | 24.83%  |
| 161-240       | 48        | 8.33%   |
| 1-50          | 26        | 4.51%   |
| More than 240 | 24        | 4.17%   |
| Unknown       | 18        | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 483       | 84.15%  |
| 2     | 61        | 10.63%  |
| 0     | 21        | 3.66%   |
| 3     | 8         | 1.39%   |
| 4     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 301       | 35%     |
| Intel                            | 282       | 32.79%  |
| Qualcomm Atheros                 | 76        | 8.84%   |
| Broadcom                         | 53        | 6.16%   |
| MediaTek                         | 26        | 3.02%   |
| TP-Link                          | 14        | 1.63%   |
| Samsung Electronics              | 14        | 1.63%   |
| Ralink Technology                | 14        | 1.63%   |
| Ralink                           | 10        | 1.16%   |
| ASIX Electronics                 | 9         | 1.05%   |
| Marvell Technology Group         | 6         | 0.7%    |
| Broadcom Limited                 | 5         | 0.58%   |
| Microsoft                        | 4         | 0.47%   |
| Huawei Technologies              | 4         | 0.47%   |
| Qualcomm Atheros Communications  | 3         | 0.35%   |
| Qualcomm                         | 3         | 0.35%   |
| Dell                             | 3         | 0.35%   |
| Apple                            | 3         | 0.35%   |
| Xiaomi                           | 2         | 0.23%   |
| Shenzhen Goodix Technology       | 2         | 0.23%   |
| Nvidia                           | 2         | 0.23%   |
| Novatel Wireless                 | 2         | 0.23%   |
| Linksys                          | 2         | 0.23%   |
| Lenovo                           | 2         | 0.23%   |
| DisplayLink                      | 2         | 0.23%   |
| D-Link                           | 2         | 0.23%   |
| Wilocity                         | 1         | 0.12%   |
| VIA Technologies                 | 1         | 0.12%   |
| T & A Mobile Phones              | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| Realtek                          | 1         | 0.12%   |
| Qualcomm Technologies            | 1         | 0.12%   |
| QinHeng Electronics              | 1         | 0.12%   |
| OPPO Electronics                 | 1         | 0.12%   |
| ICS Advent                       | 1         | 0.12%   |
| Edimax Technology                | 1         | 0.12%   |
| Conexant Systems                 | 1         | 0.12%   |
| BillBoard                        | 1         | 0.12%   |
| Belkin Components                | 1         | 0.12%   |
| Aquantia                         | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 159       | 15.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 42        | 4.19%   |
| Intel Wi-Fi 6 AX200                                                    | 28        | 2.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 27        | 2.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 2.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 20        | 1.99%   |
| Intel Wi-Fi 6 AX201                                                    | 19        | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 17        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 15        | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 15        | 1.5%    |
| Intel Wireless 8265 / 8275                                             | 15        | 1.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 12        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 12        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 10        | 1%      |
| Intel Wireless 8260                                                    | 10        | 1%      |
| Intel Wireless 7265                                                    | 10        | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 10        | 1%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 9         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9         | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 9         | 0.9%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 9         | 0.9%    |
| Intel Meteor Lake PCH CNVi WiFi                                        | 9         | 0.9%    |
| Intel I211 Gigabit Network Connection                                  | 9         | 0.9%    |
| Intel Ethernet Connection (7) I219-V                                   | 9         | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 0.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.9%    |
| Intel Wireless 7260                                                    | 8         | 0.8%    |
| Intel Wireless 3165                                                    | 8         | 0.8%    |
| Intel Ethernet Controller I225-V                                       | 8         | 0.8%    |
| Intel Ethernet Connection I217-LM                                      | 8         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 0.7%    |
| Intel Ethernet Controller I226-V                                       | 7         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 0.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 7         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 0.6%    |
| Realtek 802.11ac NIC                                                   | 6         | 0.6%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 6         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 204       | 40.72%  |
| Realtek Semiconductor           | 109       | 21.76%  |
| Qualcomm Atheros                | 64        | 12.77%  |
| Broadcom                        | 39        | 7.78%   |
| MediaTek                        | 22        | 4.39%   |
| TP-Link                         | 14        | 2.79%   |
| Ralink Technology               | 14        | 2.79%   |
| Ralink                          | 10        | 2%      |
| Broadcom Limited                | 5         | 1%      |
| Qualcomm Atheros Communications | 3         | 0.6%    |
| Qualcomm                        | 3         | 0.6%    |
| Dell                            | 3         | 0.6%    |
| Microsoft                       | 2         | 0.4%    |
| Linksys                         | 2         | 0.4%    |
| D-Link                          | 2         | 0.4%    |
| Wilocity                        | 1         | 0.2%    |
| Realtek                         | 1         | 0.2%    |
| Marvell Technology Group        | 1         | 0.2%    |
| Edimax Technology               | 1         | 0.2%    |
| Belkin Components               | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 28        | 5.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 27        | 5.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 20        | 3.98%   |
| Intel Wi-Fi 6 AX201                                                  | 19        | 3.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 17        | 3.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 15        | 2.99%   |
| Intel Wireless 8265 / 8275                                           | 15        | 2.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 12        | 2.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 10        | 1.99%   |
| Intel Wireless 8260                                                  | 10        | 1.99%   |
| Intel Wireless 7265                                                  | 10        | 1.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 10        | 1.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 9         | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 9         | 1.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 9         | 1.79%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 9         | 1.79%   |
| Intel Meteor Lake PCH CNVi WiFi                                      | 9         | 1.79%   |
| Intel Wireless 7260                                                  | 8         | 1.59%   |
| Intel Wireless 3165                                                  | 8         | 1.59%   |
| Broadcom BCM43142 802.11b/g/n                                        | 8         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 1.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 7         | 1.39%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 7         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 1.2%    |
| Realtek 802.11ac NIC                                                 | 6         | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 6         | 1.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 6         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 6         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 1%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 5         | 1%      |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 5         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 5         | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 4         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 4         | 0.8%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 4         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                           | 4         | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 0.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 4         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 245       | 51.26%  |
| Intel                            | 134       | 28.03%  |
| Broadcom                         | 25        | 5.23%   |
| Qualcomm Atheros                 | 17        | 3.56%   |
| Samsung Electronics              | 14        | 2.93%   |
| ASIX Electronics                 | 9         | 1.88%   |
| Marvell Technology Group         | 5         | 1.05%   |
| MediaTek                         | 4         | 0.84%   |
| Huawei Technologies              | 4         | 0.84%   |
| Xiaomi                           | 2         | 0.42%   |
| Nvidia                           | 2         | 0.42%   |
| Novatel Wireless                 | 2         | 0.42%   |
| Microsoft                        | 2         | 0.42%   |
| Lenovo                           | 2         | 0.42%   |
| DisplayLink                      | 2         | 0.42%   |
| Apple                            | 2         | 0.42%   |
| VIA Technologies                 | 1         | 0.21%   |
| T & A Mobile Phones              | 1         | 0.21%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| Qualcomm Technologies            | 1         | 0.21%   |
| OPPO Electronics                 | 1         | 0.21%   |
| ICS Advent                       | 1         | 0.21%   |
| Aquantia                         | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 159       | 32.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 42        | 8.5%    |
| Realtek RTL8125 2.5GbE Controller                                               | 23        | 4.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 17        | 3.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 15        | 3.04%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 12        | 2.43%   |
| Intel I211 Gigabit Network Connection                                           | 9         | 1.82%   |
| Intel Ethernet Connection (7) I219-V                                            | 9         | 1.82%   |
| Intel Ethernet Connection (2) I219-V                                            | 9         | 1.82%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 9         | 1.82%   |
| Intel Ethernet Controller I225-V                                                | 8         | 1.62%   |
| Intel Ethernet Connection I217-LM                                               | 8         | 1.62%   |
| Intel Ethernet Controller I226-V                                                | 7         | 1.42%   |
| Intel Ethernet Connection (7) I219-LM                                           | 6         | 1.21%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                               | 6         | 1.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 5         | 1.01%   |
| Intel Ethernet Connection I219-LM                                               | 5         | 1.01%   |
| Intel Ethernet Connection (2) I218-V                                            | 5         | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                                           | 4         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                           | 4         | 0.81%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                               | 4         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                     | 3         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                           | 3         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 3         | 0.61%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 3         | 0.61%   |
| Intel Ethernet Connection I218-LM                                               | 3         | 0.61%   |
| Intel Ethernet Connection I217-V                                                | 3         | 0.61%   |
| Intel Ethernet Connection (17) I219-V                                           | 3         | 0.61%   |
| Huawei FOA-LX9                                                                  | 3         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                 | 3         | 0.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 2         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 2         | 0.4%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                      | 2         | 0.4%    |
| Nvidia MCP79 Ethernet                                                           | 2         | 0.4%    |
| Novatel Wireless USB800                                                         | 2         | 0.4%    |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                              | 2         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                            | 2         | 0.4%    |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                             | 2         | 0.4%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                   | 2         | 0.4%    |
| Intel Ethernet Connection (6) I219-V                                            | 2         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 470       | 51.25%  |
| Ethernet | 440       | 47.98%  |
| Modem    | 7         | 0.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 364       | 63.53%  |
| Ethernet | 209       | 36.47%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 284       | 50.62%  |
| 1     | 258       | 45.99%  |
| 3     | 8         | 1.43%   |
| 0     | 6         | 1.07%   |
| 4     | 4         | 0.71%   |
| 5     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 325       | 55.75%  |
| Yes  | 258       | 44.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 187       | 45.17%  |
| Realtek Semiconductor           | 41        | 9.9%    |
| IMC Networks                    | 39        | 9.42%   |
| Qualcomm Atheros Communications | 31        | 7.49%   |
| Cambridge Silicon Radio         | 21        | 5.07%   |
| Foxconn / Hon Hai               | 20        | 4.83%   |
| Apple                           | 18        | 4.35%   |
| Lite-On Technology              | 10        | 2.42%   |
| Broadcom                        | 10        | 2.42%   |
| TP-Link                         | 6         | 1.45%   |
| MediaTek                        | 6         | 1.45%   |
| Toshiba                         | 5         | 1.21%   |
| Dell                            | 5         | 1.21%   |
| Ralink                          | 4         | 0.97%   |
| Realtek                         | 3         | 0.72%   |
| Hewlett-Packard                 | 2         | 0.48%   |
| ASUSTek Computer                | 2         | 0.48%   |
| SiW                             | 1         | 0.24%   |
| Ralink Technology               | 1         | 0.24%   |
| Qcom                            | 1         | 0.24%   |
| Marvell Semiconductor           | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 50        | 12.08%  |
| Intel AX201 Bluetooth                                                               | 40        | 9.66%   |
| Realtek Bluetooth Radio                                                             | 29        | 7%      |
| Intel AX200 Bluetooth                                                               | 27        | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 26        | 6.28%   |
| Intel Bluetooth Device                                                              | 25        | 6.04%   |
| IMC Networks Bluetooth Radio                                                        | 22        | 5.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 21        | 5.07%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 3.86%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 10        | 2.42%   |
| Apple Bluetooth Host Controller                                                     | 9         | 2.17%   |
| IMC Networks Wireless_Device                                                        | 8         | 1.93%   |
| IMC Networks Bluetooth Device                                                       | 8         | 1.93%   |
| TP-Link TP-T@- UB500 Adapter                                                        | 6         | 1.45%   |
| MediaTek Wireless_Device                                                            | 6         | 1.45%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.21%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 1.21%   |
| Intel AX210 Bluetooth                                                               | 5         | 1.21%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 1.21%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.97%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 0.97%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 0.72%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 3         | 0.72%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 0.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.72%   |
| Toshiba RT Bluetooth Radio                                                          | 2         | 0.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.48%   |
| Lite-On Wireless_Device                                                             | 2         | 0.48%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.48%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.48%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.48%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.48%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.48%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.24%   |
| Toshiba Askey for Toshiba                                                           | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 442       | 56.16%  |
| Nvidia                                       | 143       | 18.17%  |
| AMD                                          | 129       | 16.39%  |
| C-Media Electronics                          | 13        | 1.65%   |
| Kingston Technology                          | 9         | 1.14%   |
| ASUSTek Computer                             | 4         | 0.51%   |
| Sony                                         | 3         | 0.38%   |
| Hewlett-Packard                              | 3         | 0.38%   |
| Creative Labs                                | 3         | 0.38%   |
| Tenx Technology                              | 2         | 0.25%   |
| Samson Technologies                          | 2         | 0.25%   |
| Realtek Semiconductor                        | 2         | 0.25%   |
| Razer USA                                    | 2         | 0.25%   |
| MV-SILICON                                   | 2         | 0.25%   |
| Logitech                                     | 2         | 0.25%   |
| JMTek                                        | 2         | 0.25%   |
| Cooler Master                                | 2         | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.13%   |
| VIA Technologies                             | 1         | 0.13%   |
| TTGK Technology                              | 1         | 0.13%   |
| Texas Instruments                            | 1         | 0.13%   |
| Silicon Motion                               | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.13%   |
| Plantronics                                  | 1         | 0.13%   |
| Nreal                                        | 1         | 0.13%   |
| Nordic Semiconductor ASA                     | 1         | 0.13%   |
| Microsoft                                    | 1         | 0.13%   |
| Micro Star International                     | 1         | 0.13%   |
| Lenovo                                       | 1         | 0.13%   |
| KTMicro                                      | 1         | 0.13%   |
| Jieli Technology                             | 1         | 0.13%   |
| GYROCOM C&C                                  | 1         | 0.13%   |
| GN Netcom                                    | 1         | 0.13%   |
| Focusrite-Novation                           | 1         | 0.13%   |
| Efun-SILICON                                 | 1         | 0.13%   |
| Creative Technology                          | 1         | 0.13%   |
| Corsair                                      | 1         | 0.13%   |
| Bose                                         | 1         | 0.13%   |
| Apple                                        | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 55        | 6.07%   |
| Intel Sunrise Point-LP HD Audio                                            | 48        | 5.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 41        | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 34        | 3.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 30        | 3.31%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 28        | 3.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 26        | 2.87%   |
| AMD Radeon High Definition Audio Controller                                | 24        | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 2.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 2.1%    |
| Intel 8 Series HD Audio Controller                                         | 19        | 2.1%    |
| Intel 200 Series PCH HD Audio                                              | 19        | 2.1%    |
| AMD Starship/Matisse HD Audio Controller                                   | 18        | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15        | 1.66%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 1.66%   |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 1.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 13        | 1.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 1.21%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 0.99%   |
| Intel Raptor Lake High Definition Audio Controller                         | 9         | 0.99%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 9         | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 0.99%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 0.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 0.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 0.99%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9         | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.77%   |
| Nvidia AD107 High Definition Audio Controller                              | 7         | 0.77%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 7         | 0.77%   |
| Intel Alder Lake-S HD Audio Controller                                     | 7         | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 73        | 23.7%   |
| SK hynix                             | 58        | 18.83%  |
| Micron Technology                    | 40        | 12.99%  |
| Kingston                             | 34        | 11.04%  |
| Unknown                              | 19        | 6.17%   |
| Crucial                              | 16        | 5.19%   |
| G.Skill                              | 13        | 4.22%   |
| Corsair                              | 12        | 3.9%    |
| Team                                 | 10        | 3.25%   |
| Elpida                               | 4         | 1.3%    |
| Nanya Technology                     | 3         | 0.97%   |
| Hikvision                            | 3         | 0.97%   |
| A-DATA Technology                    | 3         | 0.97%   |
| Unknown                              | 3         | 0.97%   |
| Unknown (ABCD)                       | 2         | 0.65%   |
| Ramaxel Technology                   | 2         | 0.65%   |
| Lexar Co Limited                     | 2         | 0.65%   |
| Unknown (0x0BBA)                     | 1         | 0.32%   |
| Unknown (0x00FFFFFFFFFFFFFF)         | 1         | 0.32%   |
| Transcend                            | 1         | 0.32%   |
| Toshiba                              | 1         | 0.32%   |
| Silicon Power                        | 1         | 0.32%   |
| Patriot Memory (PDP Systems)         | 1         | 0.32%   |
| KLEVV                                | 1         | 0.32%   |
| Kingmax Semiconductor                | 1         | 0.32%   |
| D3860000                             | 1         | 0.32%   |
| Chun Well Technology Holding Limited | 1         | 0.32%   |
| ASint Technology                     | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 4         | 1.23%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 4         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 0.93%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 0.93%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 3         | 0.93%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 3         | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 3         | 0.93%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s      | 3         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 3         | 0.93%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 3         | 0.93%   |
| Micron RAM Module 4GB DIMM DDR3 1333MT/s                      | 3         | 0.93%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s           | 3         | 0.93%   |
| Unknown                                                       | 3         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                   | 2         | 0.62%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s            | 2         | 0.62%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1866MT/s            | 2         | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 2         | 0.62%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.62%   |
| SK hynix RAM HMA851U6DJR6N-XN 4GB DIMM DDR4 3200MT/s          | 2         | 0.62%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s          | 2         | 0.62%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s  | 2         | 0.62%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 2         | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 2         | 0.62%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 2         | 0.62%   |
| SK hynix RAM H58G66BK7BX067 16GB Row Of Chips LPDDR5 8533MT/s | 2         | 0.62%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s      | 2         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 0.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s   | 2         | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 2         | 0.62%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 2         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s        | 2         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 2         | 0.62%   |
| Samsung RAM M378A2G43AB3-CWE 16GB DIMM DDR4 3200MT/s          | 2         | 0.62%   |
| Samsung RAM K3KL8L80CM-MGCT 2GB Row Of Chips LPDDR5 7500MT/s  | 2         | 0.62%   |
| Samsung RAM K3KL3L30CM-BGCT 4GB Row Of Chips LPDDR5 7500MT/s  | 2         | 0.62%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 2         | 0.62%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s       | 2         | 0.62%   |
| Hikvision RAM HKED4162DAA1D0MA1 16GB SODIMM DDR4 2667MT/s     | 2         | 0.62%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s         | 2         | 0.62%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s         | 2         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 125       | 48.83%  |
| DDR3    | 73        | 28.52%  |
| DDR5    | 17        | 6.64%   |
| LPDDR4  | 12        | 4.69%   |
| LPDDR5  | 9         | 3.52%   |
| LPDDR3  | 6         | 2.34%   |
| Unknown | 6         | 2.34%   |
| DDR2    | 5         | 1.95%   |
| SDRAM   | 2         | 0.78%   |
| DDR     | 1         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 141       | 55.08%  |
| DIMM         | 80        | 31.25%  |
| Row Of Chips | 32        | 12.5%   |
| Chip         | 2         | 0.78%   |
| RIMM         | 1         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 111       | 39.64%  |
| 4096  | 71        | 25.36%  |
| 16384 | 47        | 16.79%  |
| 2048  | 24        | 8.57%   |
| 32768 | 19        | 6.79%   |
| 1024  | 4         | 1.43%   |
| 49152 | 2         | 0.71%   |
| 65536 | 1         | 0.36%   |
| 24576 | 1         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 59        | 20.49%  |
| 1600  | 49        | 17.01%  |
| 2667  | 44        | 15.28%  |
| 2400  | 16        | 5.56%   |
| 1333  | 14        | 4.86%   |
| 2133  | 13        | 4.51%   |
| 1334  | 11        | 3.82%   |
| 3600  | 7         | 2.43%   |
| 5600  | 5         | 1.74%   |
| 4267  | 5         | 1.74%   |
| 7500  | 4         | 1.39%   |
| 4800  | 4         | 1.39%   |
| 3733  | 4         | 1.39%   |
| 3266  | 4         | 1.39%   |
| 1866  | 4         | 1.39%   |
| 1067  | 4         | 1.39%   |
| 800   | 4         | 1.39%   |
| 6000  | 3         | 1.04%   |
| 1867  | 3         | 1.04%   |
| 667   | 3         | 1.04%   |
| 12800 | 2         | 0.69%   |
| 8533  | 2         | 0.69%   |
| 8400  | 2         | 0.69%   |
| 6400  | 2         | 0.69%   |
| 4266  | 2         | 0.69%   |
| 4000  | 2         | 0.69%   |
| 2933  | 2         | 0.69%   |
| 38122 | 1         | 0.35%   |
| 8000  | 1         | 0.35%   |
| 7467  | 1         | 0.35%   |
| 7000  | 1         | 0.35%   |
| 4199  | 1         | 0.35%   |
| 3466  | 1         | 0.35%   |
| 3400  | 1         | 0.35%   |
| 2666  | 1         | 0.35%   |
| 1800  | 1         | 0.35%   |
| 1648  | 1         | 0.35%   |
| 1639  | 1         | 0.35%   |
| 1066  | 1         | 0.35%   |
| 975   | 1         | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 8         | 66.67%  |
| Brother Industries     | 3         | 25%     |
| Panasonic (Matsushita) | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Brother HL-2130 series             | 2         | 15.38%  |
| Panasonic (Matsushita) KX-MB1500RU | 1         | 7.69%   |
| HP LaserJet P2055 series           | 1         | 7.69%   |
| HP LaserJet P2015 series           | 1         | 7.69%   |
| HP LaserJet CP 1025                | 1         | 7.69%   |
| HP LaserJet 400 M401dne            | 1         | 7.69%   |
| HP LaserJet 1020                   | 1         | 7.69%   |
| HP HP LaserJet M101-M106           | 1         | 7.69%   |
| HP DeskJet Plus 4100 series        | 1         | 7.69%   |
| HP DeskJet 2700 series             | 1         | 7.69%   |
| HP DeskJet 2130 series             | 1         | 7.69%   |
| Brother DCP-T300                   | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 500F | 1         | 50%     |
| Canon CanoScan LiDE 120  | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 59        | 19.8%   |
| IMC Networks                           | 35        | 11.74%  |
| Bison Electronics                      | 31        | 10.4%   |
| Microdia                               | 25        | 8.39%   |
| Apple                                  | 20        | 6.71%   |
| Sunplus Innovation Technology          | 16        | 5.37%   |
| Realtek Semiconductor                  | 16        | 5.37%   |
| Quanta                                 | 16        | 5.37%   |
| Lite-On Technology                     | 9         | 3.02%   |
| Suyin                                  | 8         | 2.68%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.68%   |
| Shinetech                              | 6         | 2.01%   |
| Microsoft                              | 6         | 2.01%   |
| Luxvisions Innotech Limited            | 5         | 1.68%   |
| Importek                               | 5         | 1.68%   |
| Samsung Electronics                    | 4         | 1.34%   |
| Syntek                                 | 3         | 1.01%   |
| Logitech                               | 3         | 1.01%   |
| Alcor Micro                            | 3         | 1.01%   |
| Z-Star Microelectronics                | 2         | 0.67%   |
| Sonix Technology                       | 2         | 0.67%   |
| Silicon Motion                         | 2         | 0.67%   |
| Ricoh                                  | 2         | 0.67%   |
| OmniVision Technologies                | 2         | 0.67%   |
| Lenovo                                 | 2         | 0.67%   |
| ARC International                      | 2         | 0.67%   |
| Anker PowerConf C200                   | 2         | 0.67%   |
| TXD                                    | 1         | 0.34%   |
| HYGD-XH--241023                        | 1         | 0.34%   |
| DigiTech                               | 1         | 0.34%   |
| Arkmicro Technologies                  | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 20        | 6.64%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 14        | 4.65%   |
| Microdia Integrated_Webcam_HD                        | 13        | 4.32%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 12        | 3.99%   |
| Bison Integrated Camera                              | 11        | 3.65%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 11        | 3.65%   |
| Chicony HP Wide Vision HD Camera                     | 6         | 1.99%   |
| Sunplus Integrated_Webcam_HD                         | 5         | 1.66%   |
| Shinetech USB2.0 FHD UVC WebCam                      | 5         | 1.66%   |
| Samsung Galaxy series, misc. (MTP mode)              | 4         | 1.33%   |
| Quanta HP Wide Vision HD Camera                      | 4         | 1.33%   |
| Bison SunplusIT Integrated Camera                    | 4         | 1.33%   |
| Apple FaceTime HD Camera (Built-in)                  | 4         | 1.33%   |
| Apple FaceTime HD Camera                             | 4         | 1.33%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 1%      |
| Lite-On HP TrueVision HD Camera                      | 3         | 1%      |
| IMC Networks Integrated Camera                       | 3         | 1%      |
| IMC Networks HD Camera                               | 3         | 1%      |
| Chicony HD WebCam                                    | 3         | 1%      |
| Chicony EasyCamera                                   | 3         | 1%      |
| Bison Lenovo EasyCamera                              | 3         | 1%      |
| Bison HD Webcam                                      | 3         | 1%      |
| Syntek Integrated Camera                             | 2         | 0.66%   |
| Suyin Integrated_Webcam_HD                           | 2         | 0.66%   |
| Suyin 1.3M HD WebCam                                 | 2         | 0.66%   |
| Sunplus HD WebCam                                    | 2         | 0.66%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 0.66%   |
| Realtek Integrated_Webcam_HD                         | 2         | 0.66%   |
| Realtek Integrated Webcam HD                         | 2         | 0.66%   |
| Realtek Integrated Webcam                            | 2         | 0.66%   |
| Realtek HP Truevision HD integrated webcam           | 2         | 0.66%   |
| Realtek HP Truevision HD                             | 2         | 0.66%   |
| Quanta ov9734_techfront_camera                       | 2         | 0.66%   |
| Quanta HD User Facing                                | 2         | 0.66%   |
| Quanta HD Camera                                     | 2         | 0.66%   |
| OmniVision OV2640 Webcam                             | 2         | 0.66%   |
| Microsoft LifeCam HD-3000                            | 2         | 0.66%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 0.66%   |
| Microdia HP Integrated Webcam                        | 2         | 0.66%   |
| Microdia Dell Laptop Integrated Webcam HD            | 2         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 22        | 38.6%   |
| Shenzhen Goodix Technology | 13        | 22.81%  |
| Validity Sensors           | 9         | 15.79%  |
| Elan Microelectronics      | 8         | 14.04%  |
| Upek                       | 2         | 3.51%   |
| LighTuning Technology      | 2         | 3.51%   |
| AuthenTec                  | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 17.54%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 10.53%  |
| Elan ELAN:ARM-M4                                                           | 6         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 7.02%   |
| Synaptics  WBDI                                                            | 3         | 5.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 3.51%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.51%   |
| Synaptics WBDI                                                             | 2         | 3.51%   |
| Synaptics Fingerprint scanner                                              | 2         | 3.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.51%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.51%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.75%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.75%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.75%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.75%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.75%   |
| Synaptics UWP WBDI                                                         | 1         | 1.75%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.75%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.75%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.75%   |
| AuthenTec AES2810                                                          | 1         | 1.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 55.56%  |
| Alcor Micro | 3         | 33.33%  |
| O2 Micro    | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Broadcom 5880                                                                | 2         | 22.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 396       | 67.81%  |
| 1     | 150       | 25.68%  |
| 2     | 28        | 4.79%   |
| 3     | 6         | 1.03%   |
| 4     | 3         | 0.51%   |
| 5     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 58        | 26.24%  |
| Fingerprint reader       | 57        | 25.79%  |
| Net/wireless             | 30        | 13.57%  |
| Multimedia controller    | 25        | 11.31%  |
| Communication controller | 13        | 5.88%   |
| Unassigned class         | 8         | 3.62%   |
| Chipcard                 | 8         | 3.62%   |
| Camera                   | 5         | 2.26%   |
| Bluetooth                | 5         | 2.26%   |
| Sound                    | 4         | 1.81%   |
| Modem                    | 2         | 0.9%    |
| Storage/raid             | 1         | 0.45%   |
| Storage/ide              | 1         | 0.45%   |
| Storage                  | 1         | 0.45%   |
| Network                  | 1         | 0.45%   |
| Dvb card                 | 1         | 0.45%   |
| Card reader              | 1         | 0.45%   |

