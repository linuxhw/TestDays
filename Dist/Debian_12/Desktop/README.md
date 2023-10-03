Debian 12 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 12.

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

Total: 712

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProLiant MicroServer Gen... | [aeb0b469c8](https://linux-hardware.org/?probe=aeb0b469c8) | Oct 01, 2023 |
| Google        | Jerry                       | [467be71aaf](https://linux-hardware.org/?probe=467be71aaf) | Sep 30, 2023 |
| Lenovo        | 0B98401 PRO                 | [17bb772d78](https://linux-hardware.org/?probe=17bb772d78) | Sep 29, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3473652871](https://linux-hardware.org/?probe=3473652871) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [5c38fe5e79](https://linux-hardware.org/?probe=5c38fe5e79) | Sep 28, 2023 |
| Pegatron      | JESSE                       | [3f6cf71237](https://linux-hardware.org/?probe=3f6cf71237) | Sep 28, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [62ba806672](https://linux-hardware.org/?probe=62ba806672) | Sep 28, 2023 |
| ASRock        | B450 Pro4 R2.0              | [82562e75c3](https://linux-hardware.org/?probe=82562e75c3) | Sep 28, 2023 |
| Shenzhen M... | F7BAA                       | [a59f2cf9f2](https://linux-hardware.org/?probe=a59f2cf9f2) | Sep 28, 2023 |
| MSI           | Z97 PC Mate                 | [15a7321226](https://linux-hardware.org/?probe=15a7321226) | Sep 27, 2023 |
| MSI           | Z97 PC Mate                 | [18bf7cff74](https://linux-hardware.org/?probe=18bf7cff74) | Sep 27, 2023 |
| Unknown       | Unknown                     | [2bf5f64c14](https://linux-hardware.org/?probe=2bf5f64c14) | Sep 27, 2023 |
| Gigabyte      | GA-970A-D3                  | [a4d1820df5](https://linux-hardware.org/?probe=a4d1820df5) | Sep 27, 2023 |
| Gigabyte      | GA-880GM-USB3L              | [f160911c14](https://linux-hardware.org/?probe=f160911c14) | Sep 27, 2023 |
| Lenovo        | 0B98401 PRO                 | [2cdf3dac45](https://linux-hardware.org/?probe=2cdf3dac45) | Sep 27, 2023 |
| YANYU         | H17SL                       | [5966ae64d0](https://linux-hardware.org/?probe=5966ae64d0) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS440           | [11efb68800](https://linux-hardware.org/?probe=11efb68800) | Sep 26, 2023 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [4a36dbb8ff](https://linux-hardware.org/?probe=4a36dbb8ff) | Sep 26, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [19858af3cd](https://linux-hardware.org/?probe=19858af3cd) | Sep 26, 2023 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | [14c3077129](https://linux-hardware.org/?probe=14c3077129) | Sep 24, 2023 |
| MSI           | Z370-A PRO                  | [77c3039fdc](https://linux-hardware.org/?probe=77c3039fdc) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [5e6e35397a](https://linux-hardware.org/?probe=5e6e35397a) | Sep 24, 2023 |
| Dell          | 0D4MD1 A04                  | [4d7943532f](https://linux-hardware.org/?probe=4d7943532f) | Sep 24, 2023 |
| Gigabyte      | B85M-D3H                    | [e568bc8439](https://linux-hardware.org/?probe=e568bc8439) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e96b971928](https://linux-hardware.org/?probe=e96b971928) | Sep 23, 2023 |
| Dell          | 0NW6H5 A00                  | [c3221c93ca](https://linux-hardware.org/?probe=c3221c93ca) | Sep 23, 2023 |
| Dell          | 0PC5F7 A01                  | [887558c8f3](https://linux-hardware.org/?probe=887558c8f3) | Sep 23, 2023 |
| Dell          | 03KWTV A02                  | [991ec32c75](https://linux-hardware.org/?probe=991ec32c75) | Sep 23, 2023 |
| Gigabyte      | B250M-Gaming5-CF            | [f18f8ef020](https://linux-hardware.org/?probe=f18f8ef020) | Sep 23, 2023 |
| Shenzhen M... | F6BFC                       | [9a906f1b75](https://linux-hardware.org/?probe=9a906f1b75) | Sep 22, 2023 |
| Dell          | 0NW6H5 A00                  | [7df92bb8f5](https://linux-hardware.org/?probe=7df92bb8f5) | Sep 22, 2023 |
| MSI           | X470 GAMING PLUS            | [d22a656bef](https://linux-hardware.org/?probe=d22a656bef) | Sep 22, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [2137a7a54b](https://linux-hardware.org/?probe=2137a7a54b) | Sep 22, 2023 |
| ASUSTek       | P7P55D                      | [ff8d00073e](https://linux-hardware.org/?probe=ff8d00073e) | Sep 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [f870f9e3ac](https://linux-hardware.org/?probe=f870f9e3ac) | Sep 21, 2023 |
| Gigabyte      | Z790 AERO G                 | [0c99fa225e](https://linux-hardware.org/?probe=0c99fa225e) | Sep 20, 2023 |
| iEi           | SAT3 V1.03                  | [d303736416](https://linux-hardware.org/?probe=d303736416) | Sep 20, 2023 |
| Gigabyte      | Z270-Gaming K3              | [63bebc9690](https://linux-hardware.org/?probe=63bebc9690) | Sep 20, 2023 |
| CWWK          | MINIPC-G12                  | [003a19cc19](https://linux-hardware.org/?probe=003a19cc19) | Sep 20, 2023 |
| Gigabyte      | Z790 AERO G                 | [6ded2501bf](https://linux-hardware.org/?probe=6ded2501bf) | Sep 20, 2023 |
| BESSTAR Te... | HM90                        | [bbb35ce98b](https://linux-hardware.org/?probe=bbb35ce98b) | Sep 20, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d9002e7e3](https://linux-hardware.org/?probe=6d9002e7e3) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c53d44303e](https://linux-hardware.org/?probe=c53d44303e) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| Gigabyte      | H81M-DS2                    | [85d35b008d](https://linux-hardware.org/?probe=85d35b008d) | Sep 19, 2023 |
| MSI           | A320M-A PRO                 | [03da63d741](https://linux-hardware.org/?probe=03da63d741) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [b06b302844](https://linux-hardware.org/?probe=b06b302844) | Sep 19, 2023 |
| Gigabyte      | 970A-DS3P                   | [0ddcc2944f](https://linux-hardware.org/?probe=0ddcc2944f) | Sep 19, 2023 |
| HP            | 82A2                        | [cc179a17a8](https://linux-hardware.org/?probe=cc179a17a8) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [a64dc1766a](https://linux-hardware.org/?probe=a64dc1766a) | Sep 18, 2023 |
| MSI           | MS-7366                     | [96731b6fc6](https://linux-hardware.org/?probe=96731b6fc6) | Sep 18, 2023 |
| ASUSTek       | J1800I-C                    | [970e148d8d](https://linux-hardware.org/?probe=970e148d8d) | Sep 18, 2023 |
| MSI           | H81M-P33                    | [d0287bbd0f](https://linux-hardware.org/?probe=d0287bbd0f) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [3faff3c0aa](https://linux-hardware.org/?probe=3faff3c0aa) | Sep 18, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [cfa7fbd3fe](https://linux-hardware.org/?probe=cfa7fbd3fe) | Sep 18, 2023 |
| AZW           | U59                         | [2bc9b4b184](https://linux-hardware.org/?probe=2bc9b4b184) | Sep 17, 2023 |
| Gigabyte      | H97-HD3                     | [ac1361d323](https://linux-hardware.org/?probe=ac1361d323) | Sep 17, 2023 |
| HP            | 1905                        | [688c5ddf16](https://linux-hardware.org/?probe=688c5ddf16) | Sep 17, 2023 |
| HP            | 1905                        | [562179ca0e](https://linux-hardware.org/?probe=562179ca0e) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | [8af23c2e56](https://linux-hardware.org/?probe=8af23c2e56) | Sep 17, 2023 |
| MSI           | X470 GAMING PLUS            | [35d0dc4629](https://linux-hardware.org/?probe=35d0dc4629) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | [50bfb485e5](https://linux-hardware.org/?probe=50bfb485e5) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | [d795a474b2](https://linux-hardware.org/?probe=d795a474b2) | Sep 16, 2023 |
| MSI           | B460M-A PRO                 | [b2d52a5d1c](https://linux-hardware.org/?probe=b2d52a5d1c) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6a908941cd](https://linux-hardware.org/?probe=6a908941cd) | Sep 16, 2023 |
| ASRock        | B450M Pro4                  | [3974827c3e](https://linux-hardware.org/?probe=3974827c3e) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [effa0104c0](https://linux-hardware.org/?probe=effa0104c0) | Sep 16, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [72ec01815f](https://linux-hardware.org/?probe=72ec01815f) | Sep 16, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [923d176004](https://linux-hardware.org/?probe=923d176004) | Sep 15, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [caba916cf4](https://linux-hardware.org/?probe=caba916cf4) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [2f12035902](https://linux-hardware.org/?probe=2f12035902) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [c46a08bb48](https://linux-hardware.org/?probe=c46a08bb48) | Sep 15, 2023 |
| Supermicro    | X11SSH-F                    | [aa351597ea](https://linux-hardware.org/?probe=aa351597ea) | Sep 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | [e9d6d94486](https://linux-hardware.org/?probe=e9d6d94486) | Sep 15, 2023 |
| JINGSHA       | X99-D8I                     | [2865a9b1e6](https://linux-hardware.org/?probe=2865a9b1e6) | Sep 15, 2023 |
| ASUSTek       | PRIME H510M-A               | [b66654e80e](https://linux-hardware.org/?probe=b66654e80e) | Sep 14, 2023 |
| ASUSTek       | P8H61/USB3                  | [cf48b0b959](https://linux-hardware.org/?probe=cf48b0b959) | Sep 14, 2023 |
| Lenovo        | ThinkServer TS440           | [8ffd465a75](https://linux-hardware.org/?probe=8ffd465a75) | Sep 14, 2023 |
| SolidRun      | CEX7 Platform               | [2a695cf7f9](https://linux-hardware.org/?probe=2a695cf7f9) | Sep 13, 2023 |
| AZW           | MINI S 10                   | [f6bc099f62](https://linux-hardware.org/?probe=f6bc099f62) | Sep 13, 2023 |
| SolidRun      | CEX7 Platform               | [06b4774756](https://linux-hardware.org/?probe=06b4774756) | Sep 13, 2023 |
| ASUSTek       | H110M-R                     | [3530c6e606](https://linux-hardware.org/?probe=3530c6e606) | Sep 13, 2023 |
| Supermicro    | X11SSH-F                    | [3a9630bdc5](https://linux-hardware.org/?probe=3a9630bdc5) | Sep 13, 2023 |
| Gigabyte      | H110M-H-CF                  | [31cc220aae](https://linux-hardware.org/?probe=31cc220aae) | Sep 12, 2023 |
| Dell          | 02N3WF A01                  | [9bd19e6fbf](https://linux-hardware.org/?probe=9bd19e6fbf) | Sep 12, 2023 |
| ASUSTek       | H110M-K                     | [ba05e7b3a7](https://linux-hardware.org/?probe=ba05e7b3a7) | Sep 12, 2023 |
| MSI           | H510M-A PRO                 | [f1a2a6d936](https://linux-hardware.org/?probe=f1a2a6d936) | Sep 12, 2023 |
| Gigabyte      | GA-870A-UD3                 | [b3acd03fb0](https://linux-hardware.org/?probe=b3acd03fb0) | Sep 12, 2023 |
| Dell          | 0GM819                      | [9917a9587a](https://linux-hardware.org/?probe=9917a9587a) | Sep 12, 2023 |
| ASRock        | B560M-HDV                   | [4df04c540a](https://linux-hardware.org/?probe=4df04c540a) | Sep 11, 2023 |
| Gigabyte      | M68MT-S2                    | [cb129260e1](https://linux-hardware.org/?probe=cb129260e1) | Sep 11, 2023 |
| ECS           | G31T-M9                     | [9d2ba7fe88](https://linux-hardware.org/?probe=9d2ba7fe88) | Sep 11, 2023 |
| Gigabyte      | GA-M56S-S3                  | [df2602c134](https://linux-hardware.org/?probe=df2602c134) | Sep 11, 2023 |
| MSI           | MS-B9091                    | [5b1250945b](https://linux-hardware.org/?probe=5b1250945b) | Sep 11, 2023 |
| ASUSTek       | P8H61/USB3                  | [d93600fc7c](https://linux-hardware.org/?probe=d93600fc7c) | Sep 11, 2023 |
| HP            | 8643 SMVB                   | [867d0c64be](https://linux-hardware.org/?probe=867d0c64be) | Sep 11, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | [6db516900f](https://linux-hardware.org/?probe=6db516900f) | Sep 10, 2023 |
| MSI           | Z370-A PRO                  | [b23d13eddc](https://linux-hardware.org/?probe=b23d13eddc) | Sep 10, 2023 |
| Shenzhen M... | HX90G                       | [fda84a9c7c](https://linux-hardware.org/?probe=fda84a9c7c) | Sep 10, 2023 |
| ASUSTek       | TS10                        | [ad867c5e25](https://linux-hardware.org/?probe=ad867c5e25) | Sep 10, 2023 |
| MSI           | B350 TOMAHAWK               | [2a7d4dfb14](https://linux-hardware.org/?probe=2a7d4dfb14) | Sep 09, 2023 |
| Gigabyte      | B85M-D3H                    | [9e26f5a8d3](https://linux-hardware.org/?probe=9e26f5a8d3) | Sep 09, 2023 |
| AZW           | U59                         | [e199a9df01](https://linux-hardware.org/?probe=e199a9df01) | Sep 09, 2023 |
| MSI           | MS-B9091                    | [226300a88d](https://linux-hardware.org/?probe=226300a88d) | Sep 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e9fc2a82f](https://linux-hardware.org/?probe=5e9fc2a82f) | Sep 09, 2023 |
| ASRock        | AB350 Gaming-ITX/ac         | [a4e0bc39ba](https://linux-hardware.org/?probe=a4e0bc39ba) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | [9b24a3d874](https://linux-hardware.org/?probe=9b24a3d874) | Sep 09, 2023 |
| MSI           | MS-B1711                    | [4c68221aae](https://linux-hardware.org/?probe=4c68221aae) | Sep 08, 2023 |
| HP            | 83E0                        | [44faaa5738](https://linux-hardware.org/?probe=44faaa5738) | Sep 08, 2023 |
| Acer          | Veriton M2632G V:1.0        | [a0363f72e3](https://linux-hardware.org/?probe=a0363f72e3) | Sep 08, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e30ef028b9](https://linux-hardware.org/?probe=e30ef028b9) | Sep 08, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [69c2d2f0d0](https://linux-hardware.org/?probe=69c2d2f0d0) | Sep 08, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | [8a5a4accb2](https://linux-hardware.org/?probe=8a5a4accb2) | Sep 08, 2023 |
| Gigabyte      | H610M H DDR4                | [72516e7752](https://linux-hardware.org/?probe=72516e7752) | Sep 07, 2023 |
| Intel         | HM570                       | [ea25bde02e](https://linux-hardware.org/?probe=ea25bde02e) | Sep 07, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [7684d60e85](https://linux-hardware.org/?probe=7684d60e85) | Sep 07, 2023 |
| Gigabyte      | Z790 UD                     | [3f67617c93](https://linux-hardware.org/?probe=3f67617c93) | Sep 07, 2023 |
| ASRock        | Z97 Killer                  | [a1537a06ee](https://linux-hardware.org/?probe=a1537a06ee) | Sep 07, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [602bfb550f](https://linux-hardware.org/?probe=602bfb550f) | Sep 06, 2023 |
| ASRock        | Z97M OC Formula             | [1f2c20e8cf](https://linux-hardware.org/?probe=1f2c20e8cf) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [19dc657d04](https://linux-hardware.org/?probe=19dc657d04) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [f20b630cf8](https://linux-hardware.org/?probe=f20b630cf8) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | [2b9d42ccc9](https://linux-hardware.org/?probe=2b9d42ccc9) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | [8415f054e5](https://linux-hardware.org/?probe=8415f054e5) | Sep 05, 2023 |
| Techvision    | TVI7309X B0                 | [846d8027c3](https://linux-hardware.org/?probe=846d8027c3) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | [85e1b123db](https://linux-hardware.org/?probe=85e1b123db) | Sep 04, 2023 |
| MSI           | Z370-A PRO                  | [b670e69634](https://linux-hardware.org/?probe=b670e69634) | Sep 04, 2023 |
| MSI           | PRO X670-P WIFI             | [326596a962](https://linux-hardware.org/?probe=326596a962) | Sep 04, 2023 |
| Dell          | 0CU409                      | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [2292824064](https://linux-hardware.org/?probe=2292824064) | Sep 04, 2023 |
| Gigabyte      | B85M-D3H                    | [9d4d9e6ffa](https://linux-hardware.org/?probe=9d4d9e6ffa) | Sep 03, 2023 |
| HP            | 1825                        | [38d038d2ad](https://linux-hardware.org/?probe=38d038d2ad) | Sep 03, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [c3dc3fd84b](https://linux-hardware.org/?probe=c3dc3fd84b) | Sep 02, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [3ea725d275](https://linux-hardware.org/?probe=3ea725d275) | Sep 02, 2023 |
| ASRock        | B650M PG Riptide            | [0f1a250c7f](https://linux-hardware.org/?probe=0f1a250c7f) | Sep 02, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [0075af1992](https://linux-hardware.org/?probe=0075af1992) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | [ec5d9509f6](https://linux-hardware.org/?probe=ec5d9509f6) | Sep 01, 2023 |
| ASUSTek       | P8Q77-M                     | [0192700365](https://linux-hardware.org/?probe=0192700365) | Sep 01, 2023 |
| Dell          | 0GM819                      | [8144006f85](https://linux-hardware.org/?probe=8144006f85) | Aug 31, 2023 |
| Dell          | 0GM819                      | [f7c99aa51b](https://linux-hardware.org/?probe=f7c99aa51b) | Aug 31, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [1cea30e36a](https://linux-hardware.org/?probe=1cea30e36a) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | [20b35a5d4f](https://linux-hardware.org/?probe=20b35a5d4f) | Aug 30, 2023 |
| Lenovo        | 102F SDK0Q40081 WIN 3305... | [b6478eb429](https://linux-hardware.org/?probe=b6478eb429) | Aug 29, 2023 |
| HP            | 82A2                        | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| BESSTAR Te... | TH50                        | [816347743d](https://linux-hardware.org/?probe=816347743d) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Gigabyte      | H410M S2H V3                | [c772f3df30](https://linux-hardware.org/?probe=c772f3df30) | Aug 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eef69bf730](https://linux-hardware.org/?probe=eef69bf730) | Aug 28, 2023 |
| langchao      | IPM41-D3                    | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| Essentiel ... | MS-7848                     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [3067310cf8](https://linux-hardware.org/?probe=3067310cf8) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0cc7a0f138](https://linux-hardware.org/?probe=0cc7a0f138) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| Unknown       | Unknown                     | [7e6d5fa7bc](https://linux-hardware.org/?probe=7e6d5fa7bc) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [241fead3e6](https://linux-hardware.org/?probe=241fead3e6) | Aug 25, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [815a77392c](https://linux-hardware.org/?probe=815a77392c) | Aug 25, 2023 |
| HP            | 18E4                        | [e209d700ef](https://linux-hardware.org/?probe=e209d700ef) | Aug 25, 2023 |
| Unknown       | Unknown                     | [0e86c5864d](https://linux-hardware.org/?probe=0e86c5864d) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| Intel         | DN2820FYK H24582-201        | [bb1402894c](https://linux-hardware.org/?probe=bb1402894c) | Aug 24, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [eeff109a12](https://linux-hardware.org/?probe=eeff109a12) | Aug 24, 2023 |
| HC Technol... | HCAR357-NR                  | [3cd017db11](https://linux-hardware.org/?probe=3cd017db11) | Aug 24, 2023 |
| MSI           | MAG B560 TORPEDO            | [a3ec958f0c](https://linux-hardware.org/?probe=a3ec958f0c) | Aug 23, 2023 |
| MSI           | MAG B560 TORPEDO            | [79db65495a](https://linux-hardware.org/?probe=79db65495a) | Aug 23, 2023 |
| HP            | 8835                        | [6d48f6a632](https://linux-hardware.org/?probe=6d48f6a632) | Aug 23, 2023 |
| HP            | 8835                        | [01d495ff7c](https://linux-hardware.org/?probe=01d495ff7c) | Aug 23, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [78bfc9060d](https://linux-hardware.org/?probe=78bfc9060d) | Aug 23, 2023 |
| Supermicro    | H12SSL-i                    | [0981b40b5c](https://linux-hardware.org/?probe=0981b40b5c) | Aug 22, 2023 |
| ASUSTek       | E35M1-M                     | [5b3a30e3bc](https://linux-hardware.org/?probe=5b3a30e3bc) | Aug 22, 2023 |
| Inspur        | H110H4-EM                   | [75ce94f0f9](https://linux-hardware.org/?probe=75ce94f0f9) | Aug 21, 2023 |
| ASUSTek       | E35M1-M                     | [c3207e25fd](https://linux-hardware.org/?probe=c3207e25fd) | Aug 21, 2023 |
| Unknown       | Unknown                     | [4d4fcc02f3](https://linux-hardware.org/?probe=4d4fcc02f3) | Aug 21, 2023 |
| Dell          | 06X1TJ A00                  | [85ba56b138](https://linux-hardware.org/?probe=85ba56b138) | Aug 20, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [109c0dbb17](https://linux-hardware.org/?probe=109c0dbb17) | Aug 20, 2023 |
| MSI           | B450M BAZOOKA               | [569655b0f2](https://linux-hardware.org/?probe=569655b0f2) | Aug 20, 2023 |
| ASRockRack    | EP2C612D16C-4L              | [61802adf5b](https://linux-hardware.org/?probe=61802adf5b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | [8b6ec2d9e2](https://linux-hardware.org/?probe=8b6ec2d9e2) | Aug 19, 2023 |
| ASRockRack    | EP2C612D16C-4L              | [52d818cdbd](https://linux-hardware.org/?probe=52d818cdbd) | Aug 19, 2023 |
| MSI           | KA790GX-M                   | [050157c33b](https://linux-hardware.org/?probe=050157c33b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | [cf83ce90b0](https://linux-hardware.org/?probe=cf83ce90b0) | Aug 19, 2023 |
| Dell          | 06X1TJ A00                  | [9580f6451c](https://linux-hardware.org/?probe=9580f6451c) | Aug 19, 2023 |
| HP            | 8266                        | [22a06599a1](https://linux-hardware.org/?probe=22a06599a1) | Aug 19, 2023 |
| Dell          | 0PU052                      | [2b5816a194](https://linux-hardware.org/?probe=2b5816a194) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [c3d45a0b50](https://linux-hardware.org/?probe=c3d45a0b50) | Aug 18, 2023 |
| HP            | 3047h                       | [a6a9afac2a](https://linux-hardware.org/?probe=a6a9afac2a) | Aug 18, 2023 |
| HP            | 3047h                       | [762697d775](https://linux-hardware.org/?probe=762697d775) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5f5f5280d8](https://linux-hardware.org/?probe=5f5f5280d8) | Aug 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [097825338b](https://linux-hardware.org/?probe=097825338b) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [7911ff1df6](https://linux-hardware.org/?probe=7911ff1df6) | Aug 18, 2023 |
| ASUSTek       | CM1630                      | [c1fd29e307](https://linux-hardware.org/?probe=c1fd29e307) | Aug 18, 2023 |
| Intel         | X99H                        | [ee1fff7602](https://linux-hardware.org/?probe=ee1fff7602) | Aug 17, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [1742c682fc](https://linux-hardware.org/?probe=1742c682fc) | Aug 16, 2023 |
| Apple         | Mac-F221BEC8                | [2db998a2ca](https://linux-hardware.org/?probe=2db998a2ca) | Aug 16, 2023 |
| Lenovo        | 1036 NO DPK                 | [61eb0b10f6](https://linux-hardware.org/?probe=61eb0b10f6) | Aug 16, 2023 |
| ASUSTek       | PRIME A320M-R               | [0e1d37c108](https://linux-hardware.org/?probe=0e1d37c108) | Aug 16, 2023 |
| PCWare        | IPMH110G                    | [c07caba6a9](https://linux-hardware.org/?probe=c07caba6a9) | Aug 16, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [a247bcbeb2](https://linux-hardware.org/?probe=a247bcbeb2) | Aug 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ec0576c5aa](https://linux-hardware.org/?probe=ec0576c5aa) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c5ad691377](https://linux-hardware.org/?probe=c5ad691377) | Aug 14, 2023 |
| Lenovo        | ThinkCentre M58p 7220AR1    | [2bc1532fb7](https://linux-hardware.org/?probe=2bc1532fb7) | Aug 14, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | [448534f935](https://linux-hardware.org/?probe=448534f935) | Aug 13, 2023 |
| ASRock        | B550M PG Riptide            | [642c45af5d](https://linux-hardware.org/?probe=642c45af5d) | Aug 13, 2023 |
| ASRock        | B85M Pro4                   | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| CWWK          | CW-J6-6L                    | [8321dcc5ea](https://linux-hardware.org/?probe=8321dcc5ea) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f6d84a4dd](https://linux-hardware.org/?probe=4f6d84a4dd) | Aug 12, 2023 |
| MSI           | G33M                        | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| Dell          | 06X1TJ A00                  | [91ecb8253e](https://linux-hardware.org/?probe=91ecb8253e) | Aug 11, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a0350a164c](https://linux-hardware.org/?probe=a0350a164c) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| ASUSTek       | Pro WS 565-ACE              | [3d9112e038](https://linux-hardware.org/?probe=3d9112e038) | Aug 09, 2023 |
| Unknown       | AB07H                       | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| Gigabyte      | H81M-S2H                    | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| ASRock        | B460M Pro4                  | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| Foxconn       | 2ADA                        | [17d44b6d2c](https://linux-hardware.org/?probe=17d44b6d2c) | Aug 06, 2023 |
| ASRock        | Q1900M                      | [51f69dffd5](https://linux-hardware.org/?probe=51f69dffd5) | Aug 06, 2023 |
| Lenovo        | 1036 NO DPK                 | [d039bb9d5c](https://linux-hardware.org/?probe=d039bb9d5c) | Aug 06, 2023 |
| Gigabyte      | B85M-D3H                    | [ed642341d8](https://linux-hardware.org/?probe=ed642341d8) | Aug 06, 2023 |
| MSI           | B450M MORTAR MAX            | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| Shenzhen M... | HX90G                       | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| ASRockRack    | X470D4U                     | [3c7626751d](https://linux-hardware.org/?probe=3c7626751d) | Aug 04, 2023 |
| Acer          | Veriton M2632G V:1.0        | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Gigabyte      | B85M-D3H                    | [5157c58f81](https://linux-hardware.org/?probe=5157c58f81) | Aug 04, 2023 |
| ASUSTek       | H81M-C                      | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| Dell          | 06X1TJ A00                  | [ac23fbd687](https://linux-hardware.org/?probe=ac23fbd687) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| Lenovo        | 1036 NO DPK                 | [a3f6a98176](https://linux-hardware.org/?probe=a3f6a98176) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | [3aa878541c](https://linux-hardware.org/?probe=3aa878541c) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [909896213c](https://linux-hardware.org/?probe=909896213c) | Aug 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [fd259f2acd](https://linux-hardware.org/?probe=fd259f2acd) | Aug 02, 2023 |
| Gigabyte      | B85M-D3H                    | [4e092275e4](https://linux-hardware.org/?probe=4e092275e4) | Aug 02, 2023 |
| Dell          | 06X1TJ A00                  | [5f9df619f5](https://linux-hardware.org/?probe=5f9df619f5) | Aug 02, 2023 |
| ASUSTek       | Z170-A                      | [3367a6e149](https://linux-hardware.org/?probe=3367a6e149) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Unknown       | Unknown                     | [a15a3cfa70](https://linux-hardware.org/?probe=a15a3cfa70) | Jul 30, 2023 |
| Dell          | 0Y5DDC A00                  | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| MSI           | B250 PC MATE                | [9163341ff4](https://linux-hardware.org/?probe=9163341ff4) | Jul 30, 2023 |
| ASRock        | A620M-HDV/M.2+              | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| Dell          | 05GD68 A00                  | [47759e14b4](https://linux-hardware.org/?probe=47759e14b4) | Jul 28, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| AZW           | MINI S 10                   | [3501ec2e9a](https://linux-hardware.org/?probe=3501ec2e9a) | Jul 28, 2023 |
| ASUSTek       | PRIME B350M-A               | [d52776a0a8](https://linux-hardware.org/?probe=d52776a0a8) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| ASRock        | H470M-HVS                   | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| Intel         | X99H                        | [1e85498a86](https://linux-hardware.org/?probe=1e85498a86) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | [a375e21964](https://linux-hardware.org/?probe=a375e21964) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [d0e6321772](https://linux-hardware.org/?probe=d0e6321772) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [28ea1c85d1](https://linux-hardware.org/?probe=28ea1c85d1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [3fd18c9a77](https://linux-hardware.org/?probe=3fd18c9a77) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [d974298840](https://linux-hardware.org/?probe=d974298840) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [b06f493001](https://linux-hardware.org/?probe=b06f493001) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [894bb319dc](https://linux-hardware.org/?probe=894bb319dc) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [7ec6d64d2f](https://linux-hardware.org/?probe=7ec6d64d2f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [09662b0f5d](https://linux-hardware.org/?probe=09662b0f5d) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [3c8721254c](https://linux-hardware.org/?probe=3c8721254c) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [7dfa96789f](https://linux-hardware.org/?probe=7dfa96789f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [c538742db7](https://linux-hardware.org/?probe=c538742db7) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [9da53986f9](https://linux-hardware.org/?probe=9da53986f9) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [c950f7dbc1](https://linux-hardware.org/?probe=c950f7dbc1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | [dcf4ead958](https://linux-hardware.org/?probe=dcf4ead958) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [759b0f997f](https://linux-hardware.org/?probe=759b0f997f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [a1ef57fb8e](https://linux-hardware.org/?probe=a1ef57fb8e) | Jul 26, 2023 |
| ASRock        | A320M Pro4                  | [9ecdd1e4d3](https://linux-hardware.org/?probe=9ecdd1e4d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [f45c4baaa3](https://linux-hardware.org/?probe=f45c4baaa3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [7abbda5ed3](https://linux-hardware.org/?probe=7abbda5ed3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [67036356d3](https://linux-hardware.org/?probe=67036356d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [5a134aede2](https://linux-hardware.org/?probe=5a134aede2) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [28c92b6f8d](https://linux-hardware.org/?probe=28c92b6f8d) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | [808dae186a](https://linux-hardware.org/?probe=808dae186a) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | [b45586c5cf](https://linux-hardware.org/?probe=b45586c5cf) | Jul 26, 2023 |
| Lenovo        | 1036 NO DPK                 | [725aae77c4](https://linux-hardware.org/?probe=725aae77c4) | Jul 26, 2023 |
| Gigabyte      | X570 GAMING X               | [f67be57cba](https://linux-hardware.org/?probe=f67be57cba) | Jul 26, 2023 |
| Gigabyte      | Z77X-UD3H                   | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [d60f3de4c7](https://linux-hardware.org/?probe=d60f3de4c7) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Lenovo        | ThinkServer TS140           | [24b688cbfd](https://linux-hardware.org/?probe=24b688cbfd) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| MSI           | H110M PRO-VD                | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| Lenovo        | 1036 NO DPK                 | [15c9141aa3](https://linux-hardware.org/?probe=15c9141aa3) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| Lenovo        | ThinkServer TS140           | [8c41263814](https://linux-hardware.org/?probe=8c41263814) | Jul 23, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [8dbf2477d3](https://linux-hardware.org/?probe=8dbf2477d3) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4bd62a58b8](https://linux-hardware.org/?probe=4bd62a58b8) | Jul 22, 2023 |
| ASUSTek       | P5Q-PRO                     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [cb0ad6375e](https://linux-hardware.org/?probe=cb0ad6375e) | Jul 20, 2023 |
| Unknown       | Unknown                     | [ce80e4d17f](https://linux-hardware.org/?probe=ce80e4d17f) | Jul 18, 2023 |
| ASUSTek       | H81M-K                      | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| ASUSTek       | B85M-E/BR                   | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| ASRockRack    | X470D4U                     | [9bd188ee9b](https://linux-hardware.org/?probe=9bd188ee9b) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Foxconn       | 2A8C                        | [539fb9855b](https://linux-hardware.org/?probe=539fb9855b) | Jul 18, 2023 |
| ASUSTek       | H81M-C                      | [d75cfffdca](https://linux-hardware.org/?probe=d75cfffdca) | Jul 17, 2023 |
| MSI           | 2A9C                        | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| ASUSTek       | B85M-G                      | [fc5b33ac00](https://linux-hardware.org/?probe=fc5b33ac00) | Jul 17, 2023 |
| MSI           | 2A9C                        | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| Unknown       | Unknown                     | [29ed3e238d](https://linux-hardware.org/?probe=29ed3e238d) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [151797320d](https://linux-hardware.org/?probe=151797320d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e760f4570f](https://linux-hardware.org/?probe=e760f4570f) | Jul 16, 2023 |
| Google        | Guado                       | [4216aa46a6](https://linux-hardware.org/?probe=4216aa46a6) | Jul 16, 2023 |
| Google        | Guado                       | [9a3e217e78](https://linux-hardware.org/?probe=9a3e217e78) | Jul 15, 2023 |
| Gigabyte      | X79-UD3                     | [ce378ce93b](https://linux-hardware.org/?probe=ce378ce93b) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| Biostar       | FX9830M                     | [db3c95d18d](https://linux-hardware.org/?probe=db3c95d18d) | Jul 15, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| Dell          | 0NDYHG A01                  | [f3723937e1](https://linux-hardware.org/?probe=f3723937e1) | Jul 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [9404c94281](https://linux-hardware.org/?probe=9404c94281) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a63f044df1](https://linux-hardware.org/?probe=a63f044df1) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| ASUSTek       | H110M-R                     | [b52ebf4fc9](https://linux-hardware.org/?probe=b52ebf4fc9) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| HP            | 8643 SMVB                   | [1d6544e56b](https://linux-hardware.org/?probe=1d6544e56b) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| Gigabyte      | X570 AORUS PRO              | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| ASRock        | 4Core1600-GLAN              | [3e733151f2](https://linux-hardware.org/?probe=3e733151f2) | Jul 11, 2023 |
| Foxconn       | G33M03                      | [487435e6e7](https://linux-hardware.org/?probe=487435e6e7) | Jul 11, 2023 |
| ASUSTek       | Z170-A                      | [cbcf43d3dd](https://linux-hardware.org/?probe=cbcf43d3dd) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| ASUSTek       | H81M-K                      | [6593286092](https://linux-hardware.org/?probe=6593286092) | Jul 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | [ce682089cb](https://linux-hardware.org/?probe=ce682089cb) | Jul 10, 2023 |
| HP            | 2B38                        | [94e5178425](https://linux-hardware.org/?probe=94e5178425) | Jul 10, 2023 |
| Gigabyte      | B650 GAMING X AX            | [64e129ec04](https://linux-hardware.org/?probe=64e129ec04) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1e27d93bb4](https://linux-hardware.org/?probe=1e27d93bb4) | Jul 09, 2023 |
| Dell          | 0V8WGR A00                  | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| Dell          | 0CU409                      | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| ASRock        | B550 Taichi Razer Editio... | [c5578cae9e](https://linux-hardware.org/?probe=c5578cae9e) | Jul 07, 2023 |
| HP            | 2B4B                        | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| HP            | 2B4B                        | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| MSI           | B250M PRO-VDH               | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f99a1ccf8f](https://linux-hardware.org/?probe=f99a1ccf8f) | Jul 06, 2023 |
| HP            | 8860 A                      | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [7e3ad6f5a7](https://linux-hardware.org/?probe=7e3ad6f5a7) | Jul 05, 2023 |
| Gigabyte      | MZBSWAP-00                  | [4e61ff196e](https://linux-hardware.org/?probe=4e61ff196e) | Jul 05, 2023 |
| ASRock        | 990FX Killer                | [696e4c24d1](https://linux-hardware.org/?probe=696e4c24d1) | Jul 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [3707ca3e1d](https://linux-hardware.org/?probe=3707ca3e1d) | Jul 05, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [8c224974f3](https://linux-hardware.org/?probe=8c224974f3) | Jul 04, 2023 |
| MSI           | Z170A GAMING M3             | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| iEi           | SAT3 V1.03                  | [fa5767b5f5](https://linux-hardware.org/?probe=fa5767b5f5) | Jul 03, 2023 |
| HP            | 0AECh D                     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| Unknown       | AB07H                       | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| Shenzhen M... | F6BFC                       | [61bc4ee589](https://linux-hardware.org/?probe=61bc4ee589) | Jul 02, 2023 |
| Lenovo        | 1036 NO DPK                 | [12a82e799d](https://linux-hardware.org/?probe=12a82e799d) | Jul 01, 2023 |
| MSI           | Z490-A PRO                  | [eb4b65c767](https://linux-hardware.org/?probe=eb4b65c767) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [91e094e5c8](https://linux-hardware.org/?probe=91e094e5c8) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | [f1eddf9437](https://linux-hardware.org/?probe=f1eddf9437) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| Dell          | 0PU052                      | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [a996f391dc](https://linux-hardware.org/?probe=a996f391dc) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [d6823d5ec7](https://linux-hardware.org/?probe=d6823d5ec7) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| OEM           | Unknown                     | [0448bbee67](https://linux-hardware.org/?probe=0448bbee67) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| Lenovo        | 1048 SDK0K17763 WIN 1801... | [d903758323](https://linux-hardware.org/?probe=d903758323) | Jun 27, 2023 |
| Dell          | 0PU052                      | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Gigabyte      | H310MD2P-CF                 | [1ad319cfc7](https://linux-hardware.org/?probe=1ad319cfc7) | Jun 26, 2023 |
| BESSTAR Te... | B550                        | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| JINGSHA       | Unknown                     | [2ae6ac9599](https://linux-hardware.org/?probe=2ae6ac9599) | Jun 25, 2023 |
| Biostar       | X370GTN                     | [80b2b1d180](https://linux-hardware.org/?probe=80b2b1d180) | Jun 25, 2023 |
| Intel         | H55                         | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Gigabyte      | EP45C-DS3R                  | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| ASUSTek       | K30BF_M32BF                 | [46a7aaf9f1](https://linux-hardware.org/?probe=46a7aaf9f1) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [51b5eb0fa2](https://linux-hardware.org/?probe=51b5eb0fa2) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | [655b20a34b](https://linux-hardware.org/?probe=655b20a34b) | Jun 23, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| Acer          | Aspire X1700                | [aac17ef2f2](https://linux-hardware.org/?probe=aac17ef2f2) | Jun 22, 2023 |
| AMI           | Intel                       | [1a4a632d56](https://linux-hardware.org/?probe=1a4a632d56) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | X670E PG Lightning          | [b8e19a16f9](https://linux-hardware.org/?probe=b8e19a16f9) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| MSI           | H110M PRO-D                 | [b652abc634](https://linux-hardware.org/?probe=b652abc634) | Jun 21, 2023 |
| HP            | 1588h                       | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| ASRock        | B760 Pro RS/D4              | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| Dell          | 0RW203                      | [6872d8e6c5](https://linux-hardware.org/?probe=6872d8e6c5) | Jun 20, 2023 |
| ASUSTek       | P8H67-M                     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| MSI           | B550-A PRO                  | [b0f066ab7e](https://linux-hardware.org/?probe=b0f066ab7e) | Jun 18, 2023 |
| Intel         | H81                         | [5cda43eb30](https://linux-hardware.org/?probe=5cda43eb30) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| HP            | 2B38                        | [b84e03e083](https://linux-hardware.org/?probe=b84e03e083) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| ASRock        | B760 Pro RS/D4              | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| ASUSTek       | PRIME B450M-A               | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| HP            | 2820h                       | [77b54a0343](https://linux-hardware.org/?probe=77b54a0343) | Jun 14, 2023 |
| HP            | 2820h                       | [40e65d7a30](https://linux-hardware.org/?probe=40e65d7a30) | Jun 14, 2023 |
| Intel         | DG41TY AAE47335-203         | [4f1d844d48](https://linux-hardware.org/?probe=4f1d844d48) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3117d89b20](https://linux-hardware.org/?probe=3117d89b20) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [3feaf0bd19](https://linux-hardware.org/?probe=3feaf0bd19) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [5fc5be3367](https://linux-hardware.org/?probe=5fc5be3367) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [aba284328c](https://linux-hardware.org/?probe=aba284328c) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [b899120507](https://linux-hardware.org/?probe=b899120507) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [051cebacd1](https://linux-hardware.org/?probe=051cebacd1) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [221a4431e2](https://linux-hardware.org/?probe=221a4431e2) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [85abf9e475](https://linux-hardware.org/?probe=85abf9e475) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [40df819ebb](https://linux-hardware.org/?probe=40df819ebb) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9ed186ba56](https://linux-hardware.org/?probe=9ed186ba56) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [2a4d82175c](https://linux-hardware.org/?probe=2a4d82175c) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [1df32db310](https://linux-hardware.org/?probe=1df32db310) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [9949220d98](https://linux-hardware.org/?probe=9949220d98) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | [d801927769](https://linux-hardware.org/?probe=d801927769) | Jun 13, 2023 |
| Shuttle       | FM10 V10                    | [f1396e2cce](https://linux-hardware.org/?probe=f1396e2cce) | Jun 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [d85ad203ff](https://linux-hardware.org/?probe=d85ad203ff) | Jun 13, 2023 |
| Gigabyte      | H61M-DS2                    | [06c6c417c9](https://linux-hardware.org/?probe=06c6c417c9) | Jun 13, 2023 |
| ECS           | G31T-M9                     | [ba2a738c96](https://linux-hardware.org/?probe=ba2a738c96) | Jun 13, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [86ab821b84](https://linux-hardware.org/?probe=86ab821b84) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [8943f697bc](https://linux-hardware.org/?probe=8943f697bc) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-K               | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| ASRock        | H310CM-HDV                  | [a810b267ef](https://linux-hardware.org/?probe=a810b267ef) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| ASUSTek       | A68HM-PLUS                  | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | [756a317dd6](https://linux-hardware.org/?probe=756a317dd6) | Jun 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0aeb6a400a](https://linux-hardware.org/?probe=0aeb6a400a) | Jun 11, 2023 |
| ASUSTek       | P7H55D-M PRO                | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| ECS           | G31T-M9                     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| ASUSTek       | M4A78T-E                    | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| Gigabyte      | GA-M56S-S3                  | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| Gigabyte      | M68MT-S2                    | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| ECS           | G31T-M9                     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Gigabyte      | GA-M56S-S3                  | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| HC Technol... | HCAR357-NR                  | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [853bd25ca5](https://linux-hardware.org/?probe=853bd25ca5) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [3a9fb692f1](https://linux-hardware.org/?probe=3a9fb692f1) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [9b549fe65a](https://linux-hardware.org/?probe=9b549fe65a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [db685837d0](https://linux-hardware.org/?probe=db685837d0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [968b38e0b9](https://linux-hardware.org/?probe=968b38e0b9) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [c9a04d8da0](https://linux-hardware.org/?probe=c9a04d8da0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [238931757a](https://linux-hardware.org/?probe=238931757a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [e190e991a6](https://linux-hardware.org/?probe=e190e991a6) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [0816e77499](https://linux-hardware.org/?probe=0816e77499) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [ff143ac918](https://linux-hardware.org/?probe=ff143ac918) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| Gigabyte      | H61M-DS2                    | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| ASRock        | H110M-HDV R3.0              | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| ECS           | G31T-M9                     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| Gigabyte      | M68MT-S2                    | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [80c2e03e4e](https://linux-hardware.org/?probe=80c2e03e4e) | May 29, 2023 |
| ECS           | G31T-M9                     | [8f4cd5b132](https://linux-hardware.org/?probe=8f4cd5b132) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [ffe8469edc](https://linux-hardware.org/?probe=ffe8469edc) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [e9f274ad89](https://linux-hardware.org/?probe=e9f274ad89) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | [62a5559050](https://linux-hardware.org/?probe=62a5559050) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | [a9c147d701](https://linux-hardware.org/?probe=a9c147d701) | May 29, 2023 |
| ASRock        | J4105-ITX                   | [570bc894da](https://linux-hardware.org/?probe=570bc894da) | May 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9e0fc265de](https://linux-hardware.org/?probe=9e0fc265de) | May 29, 2023 |
| Gigabyte      | Z690 AERO G                 | [5d4d7c7ef4](https://linux-hardware.org/?probe=5d4d7c7ef4) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [bcdfc5a2bf](https://linux-hardware.org/?probe=bcdfc5a2bf) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | [68cb8bdf49](https://linux-hardware.org/?probe=68cb8bdf49) | May 27, 2023 |
| Biostar       | A10N-8800E                  | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [4862d28e3f](https://linux-hardware.org/?probe=4862d28e3f) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [92836191e9](https://linux-hardware.org/?probe=92836191e9) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [0d449702e3](https://linux-hardware.org/?probe=0d449702e3) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [a5fbe0c1ba](https://linux-hardware.org/?probe=a5fbe0c1ba) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [f9fd99a8b7](https://linux-hardware.org/?probe=f9fd99a8b7) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [6c87853f8c](https://linux-hardware.org/?probe=6c87853f8c) | May 26, 2023 |
| ASUSTek       | H81M-C                      | [138348e6eb](https://linux-hardware.org/?probe=138348e6eb) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [388eed2f8e](https://linux-hardware.org/?probe=388eed2f8e) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [1bc02afebc](https://linux-hardware.org/?probe=1bc02afebc) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [485617123a](https://linux-hardware.org/?probe=485617123a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [d1933e40f4](https://linux-hardware.org/?probe=d1933e40f4) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [db84f366d0](https://linux-hardware.org/?probe=db84f366d0) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [4d7f19ec5b](https://linux-hardware.org/?probe=4d7f19ec5b) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [adb7acad13](https://linux-hardware.org/?probe=adb7acad13) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [897503110a](https://linux-hardware.org/?probe=897503110a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | [7ddbfedd32](https://linux-hardware.org/?probe=7ddbfedd32) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [96202d100a](https://linux-hardware.org/?probe=96202d100a) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [faa830a26c](https://linux-hardware.org/?probe=faa830a26c) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [03d0e0d8d7](https://linux-hardware.org/?probe=03d0e0d8d7) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [f76e433d68](https://linux-hardware.org/?probe=f76e433d68) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [610a5f2bb3](https://linux-hardware.org/?probe=610a5f2bb3) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | [f10a5bd0f9](https://linux-hardware.org/?probe=f10a5bd0f9) | May 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | [7a40f97a17](https://linux-hardware.org/?probe=7a40f97a17) | May 26, 2023 |
| MSI           | H110M PRO-VD                | [387793dfb2](https://linux-hardware.org/?probe=387793dfb2) | May 25, 2023 |
| ASUSTek       | P9X79                       | [142c9c4384](https://linux-hardware.org/?probe=142c9c4384) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [7b4b86c1ea](https://linux-hardware.org/?probe=7b4b86c1ea) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | [15c2f741bf](https://linux-hardware.org/?probe=15c2f741bf) | May 25, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [ac28804681](https://linux-hardware.org/?probe=ac28804681) | May 25, 2023 |
| ASUSTek       | E35M1-M                     | [c62d813dd9](https://linux-hardware.org/?probe=c62d813dd9) | May 24, 2023 |
| Gigabyte      | GA-M56S-S3                  | [3898315bde](https://linux-hardware.org/?probe=3898315bde) | May 24, 2023 |
| Gigabyte      | M61PME-S2                   | [e147bb9d5e](https://linux-hardware.org/?probe=e147bb9d5e) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [17f5577d63](https://linux-hardware.org/?probe=17f5577d63) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [d06b734926](https://linux-hardware.org/?probe=d06b734926) | May 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [3ee24557f7](https://linux-hardware.org/?probe=3ee24557f7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| ASRock        | H270 Performance            | [b3f7fdc329](https://linux-hardware.org/?probe=b3f7fdc329) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [91aa0c376a](https://linux-hardware.org/?probe=91aa0c376a) | May 22, 2023 |
| ASUSTek       | H81M-K                      | [98f94bccb6](https://linux-hardware.org/?probe=98f94bccb6) | May 22, 2023 |
| Gigabyte      | B250M-D2V-CF                | [71fc64d684](https://linux-hardware.org/?probe=71fc64d684) | May 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d4460792c6](https://linux-hardware.org/?probe=d4460792c6) | May 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| ASRock        | H470M-HVS                   | [919ed7f9e1](https://linux-hardware.org/?probe=919ed7f9e1) | May 20, 2023 |
| HP            | 1905                        | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [0f034f50a0](https://linux-hardware.org/?probe=0f034f50a0) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | [cdb86f0326](https://linux-hardware.org/?probe=cdb86f0326) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | [8c80042f1e](https://linux-hardware.org/?probe=8c80042f1e) | May 19, 2023 |
| ASRock        | X370 Taichi                 | [94bf603662](https://linux-hardware.org/?probe=94bf603662) | May 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5e003a073d](https://linux-hardware.org/?probe=5e003a073d) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| ASUSTek       | P5B-VM SE                   | [dce4e8be7c](https://linux-hardware.org/?probe=dce4e8be7c) | May 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [b9410e67b1](https://linux-hardware.org/?probe=b9410e67b1) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [9505c6130c](https://linux-hardware.org/?probe=9505c6130c) | May 16, 2023 |
| Gigabyte      | B760 AORUS ELITE AX         | [b1ab3ebdd4](https://linux-hardware.org/?probe=b1ab3ebdd4) | May 15, 2023 |
| ASRock        | H470M-HVS                   | [36cb64f82a](https://linux-hardware.org/?probe=36cb64f82a) | May 15, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [878a94a7c7](https://linux-hardware.org/?probe=878a94a7c7) | May 13, 2023 |
| Gigabyte      | Z690 AERO G                 | [a199ff9b72](https://linux-hardware.org/?probe=a199ff9b72) | May 13, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a2a47b4c35](https://linux-hardware.org/?probe=a2a47b4c35) | May 12, 2023 |
| Gigabyte      | H61M-DS2                    | [de18c72638](https://linux-hardware.org/?probe=de18c72638) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [92a39a22a2](https://linux-hardware.org/?probe=92a39a22a2) | May 12, 2023 |
| ASRock        | H470M-HVS                   | [72aed73d34](https://linux-hardware.org/?probe=72aed73d34) | May 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [0625860f59](https://linux-hardware.org/?probe=0625860f59) | May 10, 2023 |
| ECS           | G31T-M9                     | [25fd5432f0](https://linux-hardware.org/?probe=25fd5432f0) | May 10, 2023 |
| MSI           | H81M-P33                    | [c3902a3649](https://linux-hardware.org/?probe=c3902a3649) | May 10, 2023 |
| ASRock        | H470M-HVS                   | [e61f99e96e](https://linux-hardware.org/?probe=e61f99e96e) | May 10, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [401db07b93](https://linux-hardware.org/?probe=401db07b93) | May 08, 2023 |
| ASRock        | B760 Pro RS/D4              | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| HP            | 1589                        | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [be7c8943ce](https://linux-hardware.org/?probe=be7c8943ce) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| MSI           | B450 TOMAHAWK               | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| Unknown       | Unknown                     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASRock        | A320M-HDV R3.0              | [d395c6168d](https://linux-hardware.org/?probe=d395c6168d) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| HP            | 8309                        | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| ASUSTek       | Z170-A                      | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| ASRock        | 960GC-GS FX                 | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c5f2fa1c5a](https://linux-hardware.org/?probe=c5f2fa1c5a) | Apr 25, 2023 |
| MSI           | X370 GAMING PLUS            | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [9c3e15de68](https://linux-hardware.org/?probe=9c3e15de68) | Apr 22, 2023 |
| ASUSTek       | P5N-D                       | [c1af2b9a2c](https://linux-hardware.org/?probe=c1af2b9a2c) | Apr 22, 2023 |
| HP            | ProLiant ML150 G6           | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e1da556a0b](https://linux-hardware.org/?probe=e1da556a0b) | Apr 19, 2023 |
| MSI           | H110M PRO-VD                | [d04a1b7f36](https://linux-hardware.org/?probe=d04a1b7f36) | Apr 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| Biostar       | A10N-8800E                  | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Acer          | WG43M                       | [a3a49836f9](https://linux-hardware.org/?probe=a3a49836f9) | Apr 15, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| Gigabyte      | H61M-DS2                    | [e0b6eda111](https://linux-hardware.org/?probe=e0b6eda111) | Apr 11, 2023 |
| ASUSTek       | P7H55                       | [8ee190d352](https://linux-hardware.org/?probe=8ee190d352) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| ASUSTek       | P7H55                       | [89966b216e](https://linux-hardware.org/?probe=89966b216e) | Apr 07, 2023 |
| QTQD          | Unknown                     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| MSI           | Z68A-GD65                   | [a8939164e7](https://linux-hardware.org/?probe=a8939164e7) | Apr 06, 2023 |
| Gigabyte      | B550 UD AC                  | [a639dfd228](https://linux-hardware.org/?probe=a639dfd228) | Apr 06, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [55ea8a957b](https://linux-hardware.org/?probe=55ea8a957b) | Apr 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| ASUSTek       | VM42                        | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5f9965b18e](https://linux-hardware.org/?probe=5f9965b18e) | Apr 05, 2023 |
| Gigabyte      | Z68A-D3-B3                  | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| Gigabyte      | H61M-DS2                    | [5a83d4ef1e](https://linux-hardware.org/?probe=5a83d4ef1e) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [1b35a0e9f7](https://linux-hardware.org/?probe=1b35a0e9f7) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [734efd13d3](https://linux-hardware.org/?probe=734efd13d3) | Apr 03, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Gigabyte      | H61M-DS2                    | [35e4f876ca](https://linux-hardware.org/?probe=35e4f876ca) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [fca09d31a2](https://linux-hardware.org/?probe=fca09d31a2) | Mar 31, 2023 |
| ASRock        | B760M Pro RS/D4             | [6a63402e9c](https://linux-hardware.org/?probe=6a63402e9c) | Mar 31, 2023 |
| ASUSTek       | P8H67-M                     | [3806b33cae](https://linux-hardware.org/?probe=3806b33cae) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f310910b0e](https://linux-hardware.org/?probe=f310910b0e) | Mar 30, 2023 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | [08af010307](https://linux-hardware.org/?probe=08af010307) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [82118905ba](https://linux-hardware.org/?probe=82118905ba) | Mar 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6cc34607d1](https://linux-hardware.org/?probe=6cc34607d1) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4fe0ddab4b](https://linux-hardware.org/?probe=4fe0ddab4b) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5969fea8f0](https://linux-hardware.org/?probe=5969fea8f0) | Mar 28, 2023 |
| Gigabyte      | H97M-HD3                    | [1b531d5ada](https://linux-hardware.org/?probe=1b531d5ada) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| HP            | 895D                        | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| ASUSTek       | PRIME X470-PRO              | [a05e768cca](https://linux-hardware.org/?probe=a05e768cca) | Mar 25, 2023 |
| Gigabyte      | H61M-DS2                    | [cea1787057](https://linux-hardware.org/?probe=cea1787057) | Mar 24, 2023 |
| ASUSTek       | PRIME Z690-P                | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ECS           | G31T-M9                     | [e314bf5403](https://linux-hardware.org/?probe=e314bf5403) | Mar 23, 2023 |
| Techvision    | TVI7309X B0                 | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [6b25c70b9f](https://linux-hardware.org/?probe=6b25c70b9f) | Mar 21, 2023 |
| Intel         | STK2M3W64CC H89289-506      | [5386cc221b](https://linux-hardware.org/?probe=5386cc221b) | Mar 19, 2023 |
| Techvision    | TVI7309X B0                 | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| Gigabyte      | M52L-S3P                    | [89660a09c2](https://linux-hardware.org/?probe=89660a09c2) | Mar 17, 2023 |
| ASUSTek       | M4A88T-M                    | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b843a727ce](https://linux-hardware.org/?probe=b843a727ce) | Mar 15, 2023 |
| Unknown       | Unknown                     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| MSI           | H110M PRO-VH PLUS           | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| HP            | 8076 MVB,A                  | [20150077f5](https://linux-hardware.org/?probe=20150077f5) | Mar 11, 2023 |
| Gigabyte      | B360M D2V                   | [dd67a26e98](https://linux-hardware.org/?probe=dd67a26e98) | Mar 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cfacdb386a](https://linux-hardware.org/?probe=cfacdb386a) | Mar 09, 2023 |
| ASUSTek       | PRIME X570-P                | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| HP            | 82B4                        | [47d445cfa6](https://linux-hardware.org/?probe=47d445cfa6) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ae03ade800](https://linux-hardware.org/?probe=ae03ade800) | Mar 04, 2023 |
| ASUSTek       | PRIME H510M-K               | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Intel         | D945GCPE AAD97209-201       | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| ASRock        | X370 Professional Gaming    | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| ASUSTek       | PRIME X399-A                | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Dell          | 0T065F A01                  | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [d442995b00](https://linux-hardware.org/?probe=d442995b00) | Feb 19, 2023 |
| Lenovo        | 3164 NOK                    | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B450M H                     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| HP            | 3648h                       | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| Unknown       | Unknown                     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| Unknown       | Unknown                     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [517a5a9e81](https://linux-hardware.org/?probe=517a5a9e81) | Feb 13, 2023 |
| Gigabyte      | B450M H                     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [4b19274da1](https://linux-hardware.org/?probe=4b19274da1) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| HP            | 2B36                        | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.1.0-4-amd64             | 141      | 25.22%  |
| 6.1.0-9-amd64             | 88       | 15.74%  |
| 6.1.0-10-amd64            | 88       | 15.74%  |
| 6.1.0-11-amd64            | 65       | 11.63%  |
| 6.1.0-12-amd64            | 33       | 5.9%    |
| 6.1.0-7-amd64             | 29       | 5.19%   |
| 6.1.0-6-amd64             | 13       | 2.33%   |
| 6.1.0-3-amd64             | 12       | 2.15%   |
| 6.1.0-5-amd64             | 10       | 1.79%   |
| 6.4.0-0.deb12.2-amd64     | 8        | 1.43%   |
| 6.2.16-3-pve              | 7        | 1.25%   |
| 6.1.0-8-amd64             | 6        | 1.07%   |
| 6.2.16-12-pve             | 4        | 0.72%   |
| 6.2.16-8-pve              | 3        | 0.54%   |
| 6.2.16-14-pve             | 3        | 0.54%   |
| 6.0.0-6-amd64             | 3        | 0.54%   |
| 6.2.16-6-pve              | 2        | 0.36%   |
| 6.2.16-10-pve             | 2        | 0.36%   |
| 6.0.0-2-amd64             | 2        | 0.36%   |
| 6.5.3-amd64               | 1        | 0.18%   |
| 6.4.6-1-liquorix-amd64    | 1        | 0.18%   |
| 6.4.3-1-liquorix-amd64    | 1        | 0.18%   |
| 6.4.11-1-liquorix-amd64   | 1        | 0.18%   |
| 6.4.10-3-liquorix-amd64   | 1        | 0.18%   |
| 6.4.0-1mx-ahs-amd64       | 1        | 0.18%   |
| 6.4.0-01280-g7116cae43716 | 1        | 0.18%   |
| 6.3.9-i7                  | 1        | 0.18%   |
| 6.3.5-x64v3-xanmod1       | 1        | 0.18%   |
| 6.3.3-tkg-cfs             | 1        | 0.18%   |
| 6.3.0-1-amd64             | 1        | 0.18%   |
| 6.3.0-0-amd64             | 1        | 0.18%   |
| 6.2.8-x64v3-xanmod1       | 1        | 0.18%   |
| 6.2.16-5-pve              | 1        | 0.18%   |
| 6.2.16-4-pve              | 1        | 0.18%   |
| 6.2.16-2-pve              | 1        | 0.18%   |
| 6.2.11-3-liquorix-amd64   | 1        | 0.18%   |
| 6.1.9-x64v3-xanmod1       | 1        | 0.18%   |
| 6.1.38-i3                 | 1        | 0.18%   |
| 6.1.27-mab64              | 1        | 0.18%   |
| 6.1.13-x64v1-xanmod1      | 1        | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.0    | 478      | 87.55%  |
| 6.2.16   | 24       | 4.4%    |
| 6.4.0    | 10       | 1.83%   |
| 6.0.0    | 7        | 1.28%   |
| 5.10.0   | 4        | 0.73%   |
| 6.3.0    | 2        | 0.37%   |
| 6.5.3    | 1        | 0.18%   |
| 6.4.6    | 1        | 0.18%   |
| 6.4.3    | 1        | 0.18%   |
| 6.4.11   | 1        | 0.18%   |
| 6.4.10   | 1        | 0.18%   |
| 6.3.9    | 1        | 0.18%   |
| 6.3.5    | 1        | 0.18%   |
| 6.3.3    | 1        | 0.18%   |
| 6.2.8    | 1        | 0.18%   |
| 6.2.11   | 1        | 0.18%   |
| 6.1.9    | 1        | 0.18%   |
| 6.1.38   | 1        | 0.18%   |
| 6.1.27   | 1        | 0.18%   |
| 6.1.13   | 1        | 0.18%   |
| 6.1.11   | 1        | 0.18%   |
| 5.15.90  | 1        | 0.18%   |
| 5.15.108 | 1        | 0.18%   |
| 5.15.0   | 1        | 0.18%   |
| 5.10.142 | 1        | 0.18%   |
| 4.19.0   | 1        | 0.18%   |
| 4.1.42   | 1        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 483      | 88.46%  |
| 6.2     | 26       | 4.76%   |
| 6.4     | 14       | 2.56%   |
| 6.0     | 7        | 1.28%   |
| 6.3     | 5        | 0.92%   |
| 5.10    | 5        | 0.92%   |
| 5.15    | 3        | 0.55%   |
| 6.5     | 1        | 0.18%   |
| 4.19    | 1        | 0.18%   |
| 4.1     | 1        | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 537      | 98.9%   |
| i686        | 2        | 0.37%   |
| ppc64       | 1        | 0.18%   |
| loongarch64 | 1        | 0.18%   |
| armv7l      | 1        | 0.18%   |
| aarch64     | 1        | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 217      | 39.89%  |
| GNOME           | 118      | 21.69%  |
| KDE5            | 96       | 17.65%  |
| XFCE            | 35       | 6.43%   |
| X-Cinnamon      | 25       | 4.6%    |
| MATE            | 21       | 3.86%   |
| LXQt            | 10       | 1.84%   |
| LXDE            | 9        | 1.65%   |
| i3              | 5        | 0.92%   |
| GNOME Flashback | 2        | 0.37%   |
| Cinnamon        | 2        | 0.37%   |
| openbox         | 1        | 0.18%   |
| GNOME Classic   | 1        | 0.18%   |
| dwm             | 1        | 0.18%   |
| Cutefish        | 1        | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 207      | 37.91%  |
| Unknown | 181      | 33.15%  |
| Wayland | 115      | 21.06%  |
| Tty     | 43       | 7.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 321      | 58.79%  |
| LightDM | 78       | 14.29%  |
| GDM3    | 74       | 13.55%  |
| SDDM    | 67       | 12.27%  |
| XDM     | 2        | 0.37%   |
| SLiM    | 2        | 0.37%   |
| Ly      | 1        | 0.18%   |
| LXDM    | 1        | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 165      | 30.33%  |
| ru_RU      | 158      | 29.04%  |
| de_DE      | 45       | 8.27%   |
| en_GB      | 29       | 5.33%   |
| Unknown    | 21       | 3.86%   |
| fr_FR      | 15       | 2.76%   |
| pt_BR      | 14       | 2.57%   |
| es_ES      | 12       | 2.21%   |
| en_CA      | 10       | 1.84%   |
| pl_PL      | 7        | 1.29%   |
| it_IT      | 6        | 1.1%    |
| es_AR      | 6        | 1.1%    |
| en_IN      | 6        | 1.1%    |
| zh_CN      | 5        | 0.92%   |
| fi_FI      | 4        | 0.74%   |
| en_ZA      | 4        | 0.74%   |
| en_AU      | 4        | 0.74%   |
| nl_NL      | 2        | 0.37%   |
| ja_JP      | 2        | 0.37%   |
| hu_HU      | 2        | 0.37%   |
| fr_BE      | 2        | 0.37%   |
| es_VE      | 2        | 0.37%   |
| es_PE      | 2        | 0.37%   |
| en_IE      | 2        | 0.37%   |
| zh_TW      | 1        | 0.18%   |
| sv_SE      | 1        | 0.18%   |
| nl_BE      | 1        | 0.18%   |
| ko_KR      | 1        | 0.18%   |
| it_IT@euro | 1        | 0.18%   |
| id_ID      | 1        | 0.18%   |
| fr_CA      | 1        | 0.18%   |
| es_EC      | 1        | 0.18%   |
| es_CU      | 1        | 0.18%   |
| es_CL      | 1        | 0.18%   |
| en_NZ      | 1        | 0.18%   |
| en_IL      | 1        | 0.18%   |
| en_HK      | 1        | 0.18%   |
| en_DK      | 1        | 0.18%   |
| el_GR      | 1        | 0.18%   |
| de_CH      | 1        | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 328      | 60.18%  |
| EFI  | 217      | 39.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 324      | 59.34%  |
| Overlay | 167      | 30.59%  |
| Btrfs   | 31       | 5.68%   |
| Tmpfs   | 9        | 1.65%   |
| Zfs     | 7        | 1.28%   |
| Xfs     | 7        | 1.28%   |
| Ext3    | 1        | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 261      | 47.89%  |
| MBR     | 183      | 33.58%  |
| Unknown | 101      | 18.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 457      | 84.01%  |
| Yes       | 87       | 15.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 306      | 56.35%  |
| Yes       | 237      | 43.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 159      | 29.28%  |
| Gigabyte Technology                  | 95       | 17.5%   |
| MSI                                  | 57       | 10.5%   |
| ASRock                               | 55       | 10.13%  |
| Lenovo                               | 32       | 5.89%   |
| Hewlett-Packard                      | 29       | 5.34%   |
| Dell                                 | 22       | 4.05%   |
| Intel                                | 12       | 2.21%   |
| Unknown                              | 10       | 1.84%   |
| Supermicro                           | 7        | 1.29%   |
| Fujitsu                              | 7        | 1.29%   |
| Shenzhen Meigao Electronic Equipment | 5        | 0.92%   |
| Foxconn                              | 5        | 0.92%   |
| ECS                                  | 4        | 0.74%   |
| Acer                                 | 4        | 0.74%   |
| Biostar                              | 3        | 0.55%   |
| BESSTAR Tech                         | 3        | 0.55%   |
| AZW                                  | 3        | 0.55%   |
| ASRockRack                           | 3        | 0.55%   |
| Techvision                           | 2        | 0.37%   |
| JINGSHA                              | 2        | 0.37%   |
| Huanan                               | 2        | 0.37%   |
| HC Technology.                       | 2        | 0.37%   |
| Google                               | 2        | 0.37%   |
| CWWK                                 | 2        | 0.37%   |
| YANYU                                | 1        | 0.18%   |
| SolidRun                             | 1        | 0.18%   |
| Shuttle                              | 1        | 0.18%   |
| QTQD                                 | 1        | 0.18%   |
| Pegatron                             | 1        | 0.18%   |
| PCWare                               | 1        | 0.18%   |
| OEM                                  | 1        | 0.18%   |
| Loongson                             | 1        | 0.18%   |
| langchao                             | 1        | 0.18%   |
| JGINYUE                              | 1        | 0.18%   |
| Inspur                               | 1        | 0.18%   |
| iEi                                  | 1        | 0.18%   |
| Fujitsu Siemens                      | 1        | 0.18%   |
| Essentiel B                          | 1        | 0.18%   |
| Apple                                | 1        | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 29       | 5.34%   |
| ASRock H470M-HVS                    | 20       | 3.68%   |
| Unknown                             | 13       | 2.39%   |
| Lenovo ThinkCentre M55p 8808D8U     | 12       | 2.21%   |
| ASUS PRIME B450M-K                  | 10       | 1.84%   |
| Gigabyte H81M-S2V                   | 8        | 1.47%   |
| Gigabyte A320M-S2H V2               | 7        | 1.29%   |
| MSI MS-7996                         | 6        | 1.1%    |
| ASUS S20 K29                        | 6        | 1.1%    |
| ASUS ProArt X670E-CREATOR WIFI      | 5        | 0.92%   |
| Supermicro SYS-5019S-ML             | 4        | 0.74%   |
| Gigabyte X570 GAMING X              | 4        | 0.74%   |
| ECS G31T-M9                         | 4        | 0.74%   |
| Lenovo ThinkStation P520 30BFS44D00 | 3        | 0.55%   |
| Gigabyte M56S-S3                    | 3        | 0.55%   |
| Gigabyte B450 AORUS ELITE           | 3        | 0.55%   |
| Dell OptiPlex 755                   | 3        | 0.55%   |
| ASUS ROG STRIX X570-E GAMING        | 3        | 0.55%   |
| ASUS PRIME B450M-A                  | 3        | 0.55%   |
| Techvision TVI7309X                 | 2        | 0.37%   |
| Supermicro X8ST3                    | 2        | 0.37%   |
| MSI MS-7C37                         | 2        | 0.37%   |
| MSI MS-7C02                         | 2        | 0.37%   |
| MSI MS-7B85                         | 2        | 0.37%   |
| MSI MS-7B79                         | 2        | 0.37%   |
| MSI MS-7A34                         | 2        | 0.37%   |
| MSI MS-7817                         | 2        | 0.37%   |
| Intel X99                           | 2        | 0.37%   |
| HP Z230 Tower Workstation           | 2        | 0.37%   |
| HP ProDesk 400 G4 SFF               | 2        | 0.37%   |
| HP Compaq 6005 Pro MT PC            | 2        | 0.37%   |
| HC Technology. HCAR357-NR           | 2        | 0.37%   |
| Gigabyte M68MT-S2                   | 2        | 0.37%   |
| Gigabyte H61M-DS2 REV 1.2           | 2        | 0.37%   |
| Gigabyte H110M-H                    | 2        | 0.37%   |
| Gigabyte GA-MA78GM-S2H              | 2        | 0.37%   |
| Gigabyte B550M DS3H                 | 2        | 0.37%   |
| Gigabyte B450M H                    | 2        | 0.37%   |
| Gigabyte B450M DS3H                 | 2        | 0.37%   |
| Gigabyte B250M-DS3H                 | 2        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 39       | 7.18%   |
| ASUS All                | 29       | 5.34%   |
| Lenovo ThinkCentre      | 20       | 3.68%   |
| ASRock H470M-HVS        | 20       | 3.68%   |
| ASUS ROG                | 18       | 3.31%   |
| Dell OptiPlex           | 14       | 2.58%   |
| Unknown                 | 13       | 2.39%   |
| ASUS TUF                | 11       | 2.03%   |
| Lenovo ThinkStation     | 8        | 1.47%   |
| Gigabyte H81M-S2V       | 8        | 1.47%   |
| Gigabyte A320M-S2H      | 7        | 1.29%   |
| MSI MS-7996             | 6        | 1.1%    |
| Gigabyte X570           | 6        | 1.1%    |
| Gigabyte B450M          | 6        | 1.1%    |
| ASUS S20                | 6        | 1.1%    |
| HP ProDesk              | 5        | 0.92%   |
| Gigabyte B450           | 5        | 0.92%   |
| ASUS ProArt             | 5        | 0.92%   |
| Supermicro SYS-5019S-ML | 4        | 0.74%   |
| HP EliteDesk            | 4        | 0.74%   |
| HP Compaq               | 4        | 0.74%   |
| Gigabyte B550M          | 4        | 0.74%   |
| ECS G31T-M9             | 4        | 0.74%   |
| Gigabyte M56S-S3        | 3        | 0.55%   |
| Fujitsu ESPRIMO         | 3        | 0.55%   |
| Dell Precision          | 3        | 0.55%   |
| ASUS Pro                | 3        | 0.55%   |
| ASUS P5G41T-M           | 3        | 0.55%   |
| Acer Aspire             | 3        | 0.55%   |
| Techvision TVI7309X     | 2        | 0.37%   |
| Supermicro X8ST3        | 2        | 0.37%   |
| MSI MS-7C37             | 2        | 0.37%   |
| MSI MS-7C02             | 2        | 0.37%   |
| MSI MS-7B85             | 2        | 0.37%   |
| MSI MS-7B79             | 2        | 0.37%   |
| MSI MS-7A34             | 2        | 0.37%   |
| MSI MS-7817             | 2        | 0.37%   |
| Intel X99               | 2        | 0.37%   |
| Huanan X99-F8           | 2        | 0.37%   |
| HP Z230                 | 2        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 58       | 10.68%  |
| 2021    | 54       | 9.94%   |
| 2022    | 50       | 9.21%   |
| 2020    | 45       | 8.29%   |
| 2014    | 37       | 6.81%   |
| 2019    | 31       | 5.71%   |
| 2012    | 31       | 5.71%   |
| 2013    | 27       | 4.97%   |
| 2009    | 27       | 4.97%   |
| 2016    | 26       | 4.79%   |
| 2023    | 25       | 4.6%    |
| 2017    | 25       | 4.6%    |
| 2007    | 25       | 4.6%    |
| 2015    | 23       | 4.24%   |
| 2008    | 19       | 3.5%    |
| 2011    | 18       | 3.31%   |
| 2010    | 17       | 3.13%   |
| Unknown | 4        | 0.74%   |
| 2002    | 1        | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 543      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 526      | 96.87%  |
| Enabled  | 17       | 3.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 542      | 99.82%  |
| Yes  | 1        | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 115      | 21.02%  |
| 16.01-24.0      | 100      | 18.28%  |
| 4.01-8.0        | 85       | 15.54%  |
| 3.01-4.0        | 72       | 13.16%  |
| 8.01-16.0       | 72       | 13.16%  |
| 64.01-256.0     | 52       | 9.51%   |
| 24.01-32.0      | 20       | 3.66%   |
| 1.01-2.0        | 17       | 3.11%   |
| 2.01-3.0        | 6        | 1.1%    |
| More than 256.0 | 4        | 0.73%   |
| 0.51-1.0        | 3        | 0.55%   |
| Unknown         | 1        | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 135      | 24.37%  |
| 1.01-2.0    | 115      | 20.76%  |
| 4.01-8.0    | 112      | 20.22%  |
| 2.01-3.0    | 86       | 15.52%  |
| 3.01-4.0    | 48       | 8.66%   |
| 8.01-16.0   | 26       | 4.69%   |
| 0.01-0.5    | 15       | 2.71%   |
| 16.01-24.0  | 8        | 1.44%   |
| 24.01-32.0  | 5        | 0.9%    |
| 32.01-64.0  | 2        | 0.36%   |
| 64.01-256.0 | 1        | 0.18%   |
| Unknown     | 1        | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 262      | 47.99%  |
| 2      | 132      | 24.18%  |
| 3      | 69       | 12.64%  |
| 4      | 39       | 7.14%   |
| 5      | 15       | 2.75%   |
| 6      | 12       | 2.2%    |
| 0      | 4        | 0.73%   |
| 8      | 3        | 0.55%   |
| 7      | 3        | 0.55%   |
| 10     | 2        | 0.37%   |
| 32     | 1        | 0.18%   |
| 29     | 1        | 0.18%   |
| 27     | 1        | 0.18%   |
| 19     | 1        | 0.18%   |
| 9      | 1        | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 392      | 72.06%  |
| Yes       | 152      | 27.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 536      | 98.71%  |
| No        | 7        | 1.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 349      | 64.27%  |
| Yes       | 194      | 35.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 377      | 68.8%   |
| Yes       | 171      | 31.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 173      | 31.74%  |
| USA          | 84       | 15.41%  |
| Germany      | 62       | 11.38%  |
| UK           | 17       | 3.12%   |
| Brazil       | 17       | 3.12%   |
| Spain        | 15       | 2.75%   |
| France       | 15       | 2.75%   |
| Canada       | 13       | 2.39%   |
| Italy        | 12       | 2.2%    |
| Poland       | 11       | 2.02%   |
| India        | 8        | 1.47%   |
| Argentina    | 7        | 1.28%   |
| Netherlands  | 6        | 1.1%    |
| Finland      | 6        | 1.1%    |
| Australia    | 6        | 1.1%    |
| Switzerland  | 5        | 0.92%   |
| Slovakia     | 5        | 0.92%   |
| Sweden       | 4        | 0.73%   |
| Portugal     | 4        | 0.73%   |
| Hungary      | 4        | 0.73%   |
| China        | 4        | 0.73%   |
| Belgium      | 4        | 0.73%   |
| South Africa | 3        | 0.55%   |
| Romania      | 3        | 0.55%   |
| Mexico       | 3        | 0.55%   |
| Japan        | 3        | 0.55%   |
| Indonesia    | 3        | 0.55%   |
| Hong Kong    | 3        | 0.55%   |
| Austria      | 3        | 0.55%   |
| Venezuela    | 2        | 0.37%   |
| Thailand     | 2        | 0.37%   |
| Singapore    | 2        | 0.37%   |
| Peru         | 2        | 0.37%   |
| Norway       | 2        | 0.37%   |
| Morocco      | 2        | 0.37%   |
| Israel       | 2        | 0.37%   |
| Ireland      | 2        | 0.37%   |
| Greece       | 2        | 0.37%   |
| Denmark      | 2        | 0.37%   |
| Vietnam      | 1        | 0.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 140      | 25.59%  |
| Bangor            | 17       | 3.11%   |
| Moscow            | 7        | 1.28%   |
| Frankfurt am Main | 7        | 1.28%   |
| St Petersburg     | 6        | 1.1%    |
| Ufa               | 5        | 0.91%   |
| Manchester        | 5        | 0.91%   |
| Vienna            | 4        | 0.73%   |
| Toronto           | 4        | 0.73%   |
| Rozhanovce        | 4        | 0.73%   |
| Paris             | 4        | 0.73%   |
| Madrid            | 4        | 0.73%   |
| Gladbeck          | 4        | 0.73%   |
| Berlin            | 4        | 0.73%   |
| Stockholm         | 3        | 0.55%   |
| Ruda Śląska     | 3        | 0.55%   |
| Hamburg           | 3        | 0.55%   |
| Bonn              | 3        | 0.55%   |
| Zurich            | 2        | 0.37%   |
| Veliky Novgorod   | 2        | 0.37%   |
| Tsukuba           | 2        | 0.37%   |
| Tel Aviv          | 2        | 0.37%   |
| Sydney            | 2        | 0.37%   |
| Singapore         | 2        | 0.37%   |
| Rio de Janeiro    | 2        | 0.37%   |
| Richmond          | 2        | 0.37%   |
| Recife            | 2        | 0.37%   |
| Paderborn         | 2        | 0.37%   |
| Ottawa            | 2        | 0.37%   |
| Nakhon Pathom     | 2        | 0.37%   |
| Milan             | 2        | 0.37%   |
| Lüneburg         | 2        | 0.37%   |
| Lima              | 2        | 0.37%   |
| Hounslow          | 2        | 0.37%   |
| Hofheim am Taunus | 2        | 0.37%   |
| Helsinki          | 2        | 0.37%   |
| Gilbert           | 2        | 0.37%   |
| Espoo             | 2        | 0.37%   |
| Dublin            | 2        | 0.37%   |
| Delhi             | 2        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 179      | 313    | 19.35%  |
| Samsung Electronics         | 131      | 199    | 14.16%  |
| Seagate                     | 124      | 189    | 13.41%  |
| Crucial                     | 72       | 86     | 7.78%   |
| Toshiba                     | 59       | 74     | 6.38%   |
| Kingston                    | 56       | 62     | 6.05%   |
| SanDisk                     | 42       | 50     | 4.54%   |
| Hitachi                     | 28       | 32     | 3.03%   |
| Netac                       | 24       | 25     | 2.59%   |
| Intel                       | 14       | 16     | 1.51%   |
| China                       | 12       | 13     | 1.3%    |
| Unknown                     | 10       | 15     | 1.08%   |
| HGST                        | 10       | 44     | 1.08%   |
| Transcend                   | 9        | 12     | 0.97%   |
| SPCC                        | 9        | 10     | 0.97%   |
| Kingston Technology Company | 9        | 13     | 0.97%   |
| Silicon Motion              | 7        | 7      | 0.76%   |
| Hewlett-Packard             | 7        | 9      | 0.76%   |
| GOODRAM                     | 7        | 15     | 0.76%   |
| A-DATA Technology           | 7        | 7      | 0.76%   |
| PNY                         | 5        | 7      | 0.54%   |
| Plextor                     | 5        | 5      | 0.54%   |
| Phison Electronics          | 5        | 11     | 0.54%   |
| Micron Technology           | 5        | 5      | 0.54%   |
| KIOXIA-EXCERIA              | 5        | 5      | 0.54%   |
| Phison                      | 4        | 5      | 0.43%   |
| Micron/Crucial Technology   | 4        | 5      | 0.43%   |
| MAXIO Technology (Hangzhou) | 4        | 4      | 0.43%   |
| Apacer                      | 4        | 6      | 0.43%   |
| SK hynix                    | 3        | 4      | 0.32%   |
| Maxtor                      | 3        | 3      | 0.32%   |
| LITEON                      | 3        | 3      | 0.32%   |
| KIOXIA                      | 3        | 3      | 0.32%   |
| JMicron Technology          | 3        | 3      | 0.32%   |
| ZHITAI                      | 2        | 3      | 0.22%   |
| XPG                         | 2        | 5      | 0.22%   |
| SABRENT                     | 2        | 2      | 0.22%   |
| Patriot                     | 2        | 2      | 0.22%   |
| OCZ                         | 2        | 2      | 0.22%   |
| Intenso                     | 2        | 2      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Netac SSD 240GB                                       | 19       | 1.75%   |
| Crucial CT480BX500SSD1 480GB                          | 19       | 1.75%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 15       | 1.38%   |
| Toshiba HDWD110 1TB                                   | 14       | 1.29%   |
| Crucial CT240BX500SSD1 240GB                          | 14       | 1.29%   |
| Kingston SA400S37240G 240GB SSD                       | 12       | 1.1%    |
| Samsung SSD 980 PRO 1TB                               | 11       | 1.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB   | 11       | 1.01%   |
| Crucial CT1000MX500SSD1 1TB                           | 11       | 1.01%   |
| Seagate ST1000DM003-1ER162 1TB                        | 9        | 0.83%   |
| Kingston SA400S37480G 480GB SSD                       | 9        | 0.83%   |
| Kingston SA400S37120G 120GB SSD                       | 9        | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 8        | 0.74%   |
| Toshiba DT01ACA050 500GB                              | 8        | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB                        | 8        | 0.74%   |
| Samsung SSD 870 EVO 500GB                             | 8        | 0.74%   |
| Toshiba DT01ACA100 1TB                                | 7        | 0.64%   |
| Seagate ST500DM002-1BD142 500GB                       | 7        | 0.64%   |
| Samsung SSD 970 EVO Plus 1TB                          | 7        | 0.64%   |
| Samsung SSD 860 EVO 500GB                             | 7        | 0.64%   |
| Samsung SSD 850 EVO 500GB                             | 7        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 7        | 0.64%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB               | 7        | 0.64%   |
| Crucial CT500MX500SSD1 500GB                          | 7        | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 6        | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB                        | 6        | 0.55%   |
| Samsung SSD 980 500GB                                 | 6        | 0.55%   |
| Samsung SSD 970 EVO Plus 500GB                        | 6        | 0.55%   |
| Samsung SSD 860 EVO 250GB                             | 6        | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5        | 0.46%   |
| Seagate ST2000DM006-2DM164 2TB                        | 5        | 0.46%   |
| SanDisk NVMe SSD Drive 1TB                            | 5        | 0.46%   |
| Samsung SSD 980 1TB                                   | 5        | 0.46%   |
| Samsung SSD 970 EVO 1TB                               | 5        | 0.46%   |
| Samsung SSD 860 EVO 1TB                               | 5        | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                      | 5        | 0.46%   |
| WDC WD40EFRX-68WT0N0 4TB                              | 4        | 0.37%   |
| WDC WD3000HLFS-01G6U0 304GB                           | 4        | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 4        | 0.37%   |
| WDC WD20EARX-00PASB0 2TB                              | 4        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 152      | 270    | 39.58%  |
| Seagate             | 121      | 186    | 31.51%  |
| Toshiba             | 54       | 69     | 14.06%  |
| Hitachi             | 28       | 32     | 7.29%   |
| HGST                | 10       | 44     | 2.6%    |
| Unknown             | 4        | 4      | 1.04%   |
| Samsung Electronics | 4        | 5      | 1.04%   |
| Maxtor              | 3        | 3      | 0.78%   |
| SABRENT             | 2        | 2      | 0.52%   |
| Hewlett-Packard     | 2        | 3      | 0.52%   |
| USB                 | 1        | 1      | 0.26%   |
| External            | 1        | 1      | 0.26%   |
| Apple               | 1        | 1      | 0.26%   |
| Unknown             | 1        | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 68       | 85     | 20.3%   |
| Crucial             | 59       | 67     | 17.61%  |
| Kingston            | 44       | 48     | 13.13%  |
| WDC                 | 23       | 32     | 6.87%   |
| Netac               | 23       | 24     | 6.87%   |
| SanDisk             | 17       | 19     | 5.07%   |
| China               | 12       | 13     | 3.58%   |
| Intel               | 9        | 10     | 2.69%   |
| SPCC                | 8        | 8      | 2.39%   |
| Transcend           | 7        | 10     | 2.09%   |
| GOODRAM             | 7        | 11     | 2.09%   |
| PNY                 | 5        | 7      | 1.49%   |
| Plextor             | 4        | 4      | 1.19%   |
| Hewlett-Packard     | 4        | 4      | 1.19%   |
| A-DATA Technology   | 4        | 4      | 1.19%   |
| Micron Technology   | 3        | 3      | 0.9%    |
| LITEON              | 3        | 3      | 0.9%    |
| Apacer              | 3        | 3      | 0.9%    |
| Seagate             | 2        | 2      | 0.6%    |
| Patriot             | 2        | 2      | 0.6%    |
| OCZ                 | 2        | 2      | 0.6%    |
| JMicron Technology  | 2        | 2      | 0.6%    |
| Intenso             | 2        | 2      | 0.6%    |
| TrekStor            | 1        | 1      | 0.3%    |
| Toshiba             | 1        | 1      | 0.3%    |
| TO Exter            | 1        | 1      | 0.3%    |
| Timetec             | 1        | 2      | 0.3%    |
| T-FORCE             | 1        | 2      | 0.3%    |
| SSSTC               | 1        | 1      | 0.3%    |
| Rogueware           | 1        | 2      | 0.3%    |
| OCZ-VERTEX3         | 1        | 1      | 0.3%    |
| NGFF                | 1        | 1      | 0.3%    |
| MSI                 | 1        | 1      | 0.3%    |
| KOWIN               | 1        | 1      | 0.3%    |
| KIOXIA-EXCERIA      | 1        | 1      | 0.3%    |
| KingSpec            | 1        | 1      | 0.3%    |
| Innodisk            | 1        | 1      | 0.3%    |
| Gigabyte Technology | 1        | 1      | 0.3%    |
| Fanxiang            | 1        | 1      | 0.3%    |
| EZCOOL              | 1        | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 323      | 622    | 40.17%  |
| SSD     | 285      | 390    | 35.45%  |
| NVMe    | 184      | 291    | 22.89%  |
| Unknown | 8        | 13     | 1%      |
| MMC     | 4        | 6      | 0.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 463      | 926    | 67.1%   |
| NVMe | 184      | 289    | 26.67%  |
| SAS  | 39       | 101    | 5.65%   |
| MMC  | 4        | 6      | 0.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 343      | 457    | 51.73%  |
| 0.51-1.0   | 168      | 235    | 25.34%  |
| 1.01-2.0   | 64       | 110    | 9.65%   |
| 3.01-4.0   | 35       | 70     | 5.28%   |
| 4.01-10.0  | 26       | 100    | 3.92%   |
| 2.01-3.0   | 21       | 29     | 3.17%   |
| 10.01-20.0 | 6        | 11     | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 162      | 29.51%  |
| 101-250        | 74       | 13.48%  |
| 501-1000       | 69       | 12.57%  |
| More than 3000 | 68       | 12.39%  |
| 251-500        | 60       | 10.93%  |
| 1001-2000      | 45       | 8.2%    |
| 2001-3000      | 27       | 4.92%   |
| 1-20           | 19       | 3.46%   |
| 51-100         | 14       | 2.55%   |
| 21-50          | 11       | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 162      | 29.24%  |
| 1-20           | 132      | 23.83%  |
| 101-250        | 53       | 9.57%   |
| 21-50          | 49       | 8.84%   |
| 251-500        | 37       | 6.68%   |
| 1001-2000      | 32       | 5.78%   |
| 501-1000       | 31       | 5.6%    |
| More than 3000 | 24       | 4.33%   |
| 51-100         | 24       | 4.33%   |
| 2001-3000      | 10       | 1.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB        | 12       | 12     | 10.62%  |
| WDC WD3200AAJS-00L7A0 320GB         | 3        | 3      | 2.65%   |
| Seagate ST3250410AS 250GB           | 3        | 3      | 2.65%   |
| WDC WD30EFRX-68EUZN0 3TB            | 2        | 2      | 1.77%   |
| WDC WD10EARS-00MVWB0 1TB            | 2        | 2      | 1.77%   |
| Seagate ST2000DX001-1CM164 2TB      | 2        | 3      | 1.77%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 2      | 1.77%   |
| Samsung Electronics SSD 970 EVO 1TB | 2        | 2      | 1.77%   |
| Maxtor STM3160815AS 160GB           | 2        | 2      | 1.77%   |
| Hitachi HDS721050CLA362 500GB       | 2        | 4      | 1.77%   |
| Hitachi HDS721010CLA332 1TB         | 2        | 2      | 1.77%   |
| ZHITAI TiPlus5000 512GB             | 1        | 1      | 0.88%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1        | 2      | 0.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1      | 0.88%   |
| WDC WD80EMAZ-00WJTA0 8TB            | 1        | 11     | 0.88%   |
| WDC WD800AAJS-60WAA0 80GB           | 1        | 1      | 0.88%   |
| WDC WD7500BPKX-80HPJT0 752GB        | 1        | 1      | 0.88%   |
| WDC WD5000AZLX-22JKKA0 500GB        | 1        | 2      | 0.88%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1        | 1      | 0.88%   |
| WDC WD5000AAKS-00A7B0 500GB         | 1        | 1      | 0.88%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1      | 0.88%   |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 3      | 0.88%   |
| WDC WD400BD-60LRA0 40GB             | 1        | 1      | 0.88%   |
| WDC WD400BB-75CAA0 40GB             | 1        | 1      | 0.88%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1        | 1      | 0.88%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 1      | 0.88%   |
| WDC WD2500AAKX-001CA0 250GB         | 1        | 1      | 0.88%   |
| WDC WD2500AAKS-00VSA0 250GB         | 1        | 2      | 0.88%   |
| WDC WD2500AAJS-00YZCA0 250GB        | 1        | 1      | 0.88%   |
| WDC WD2500AAJS-00B4A0 250GB         | 1        | 1      | 0.88%   |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 1      | 0.88%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 0.88%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 0.88%   |
| WDC WD1600AAJS-00B4A0 160GB         | 1        | 1      | 0.88%   |
| WDC WD10JPVX-08JC3T5 1TB            | 1        | 1      | 0.88%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1      | 0.88%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1        | 1      | 0.88%   |
| WDC WD10EALX-009BA0 1TB             | 1        | 1      | 0.88%   |
| WDC WD10EADS-00L5B1 1TB             | 1        | 1      | 0.88%   |
| WDC WD1000DHTZ-04N21V0 1TB          | 1        | 1      | 0.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 47       | 63     | 42.34%  |
| Seagate             | 25       | 29     | 22.52%  |
| Samsung Electronics | 10       | 11     | 9.01%   |
| Hitachi             | 8        | 10     | 7.21%   |
| Kingston            | 3        | 3      | 2.7%    |
| Crucial             | 3        | 3      | 2.7%    |
| Toshiba             | 2        | 2      | 1.8%    |
| SanDisk             | 2        | 2      | 1.8%    |
| Maxtor              | 2        | 2      | 1.8%    |
| Intel               | 2        | 2      | 1.8%    |
| ZHITAI              | 1        | 1      | 0.9%    |
| SSSTC               | 1        | 1      | 0.9%    |
| Mushkin             | 1        | 1      | 0.9%    |
| LITEON              | 1        | 1      | 0.9%    |
| KingSpec            | 1        | 1      | 0.9%    |
| Apple               | 1        | 1      | 0.9%    |
| A-DATA Technology   | 1        | 1      | 0.9%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 44       | 59     | 52.38%  |
| Seagate             | 25       | 29     | 29.76%  |
| Hitachi             | 8        | 10     | 9.52%   |
| Toshiba             | 2        | 2      | 2.38%   |
| Samsung Electronics | 2        | 3      | 2.38%   |
| Maxtor              | 2        | 2      | 2.38%   |
| Apple               | 1        | 1      | 1.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 75       | 106    | 73.53%  |
| SSD  | 22       | 23     | 21.57%  |
| NVMe | 5        | 5      | 4.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 375      | 802    | 60.39%  |
| Detected | 145      | 384    | 23.35%  |
| Malfunc  | 99       | 134    | 15.94%  |
| Failed   | 1        | 1      | 0.16%   |
| Limited  | 1        | 1      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 344      | 42.36%  |
| AMD                            | 175      | 21.55%  |
| Samsung Electronics            | 72       | 8.87%   |
| Sandisk                        | 34       | 4.19%   |
| ASMedia Technology             | 29       | 3.57%   |
| Kingston Technology Company    | 22       | 2.71%   |
| Micron/Crucial Technology      | 19       | 2.34%   |
| Phison Electronics             | 16       | 1.97%   |
| JMicron Technology             | 14       | 1.72%   |
| Nvidia                         | 11       | 1.35%   |
| Marvell Technology Group       | 10       | 1.23%   |
| Silicon Motion                 | 9        | 1.11%   |
| Toshiba America Info Systems   | 6        | 0.74%   |
| LSI Logic / Symbios Logic      | 5        | 0.62%   |
| KIOXIA                         | 5        | 0.62%   |
| ADATA Technology               | 5        | 0.62%   |
| MAXIO Technology (Hangzhou)    | 4        | 0.49%   |
| Silicon Image                  | 3        | 0.37%   |
| Broadcom / LSI                 | 3        | 0.37%   |
| Yangtze Memory Technologies    | 2        | 0.25%   |
| VIA Technologies               | 2        | 0.25%   |
| Transcend                      | 2        | 0.25%   |
| SK hynix                       | 2        | 0.25%   |
| Micron Technology              | 2        | 0.25%   |
| Biwin Storage Technology       | 2        | 0.25%   |
| Adaptec                        | 2        | 0.25%   |
| Solid State Storage Technology | 1        | 0.12%   |
| Seagate Technology             | 1        | 0.12%   |
| Realtek Semiconductor          | 1        | 0.12%   |
| Radian Memory Systems          | 1        | 0.12%   |
| Netac Technology               | 1        | 0.12%   |
| Loongson Technology            | 1        | 0.12%   |
| INNOGRIT                       | 1        | 0.12%   |
| IBM                            | 1        | 0.12%   |
| HighPoint Technologies         | 1        | 0.12%   |
| Hewlett-Packard                | 1        | 0.12%   |
| Artop Electronic               | 1        | 0.12%   |
| 3ware                          | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 105      | 10.61%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 55       | 5.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 50       | 5.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 34       | 3.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 32       | 3.23%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 29       | 2.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 27       | 2.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 27       | 2.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 26       | 2.63%   |
| AMD 500 Series Chipset SATA Controller                                                  | 22       | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18       | 1.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 1.72%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 15       | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 1.52%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 13       | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 1.31%   |
| Samsung NVMe SSD Controller 980                                                         | 12       | 1.21%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 12       | 1.21%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 1.21%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10       | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.01%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 0.91%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 0.91%   |
| Intel 82Q963/Q965 PT IDER Controller                                                    | 9        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 0.91%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 8        | 0.81%   |
| Phison E12 NVMe Controller                                                              | 8        | 0.81%   |
| Kingston Company Company Non-Volatile memory controller                                 | 8        | 0.81%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 8        | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 0.71%   |
| AMD FCH SATA Controller D                                                               | 7        | 0.71%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 6        | 0.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6        | 0.61%   |
| JMicron JMB368 IDE controller                                                           | 6        | 0.61%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 0.61%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 457      | 58.22%  |
| NVMe | 180      | 22.93%  |
| IDE  | 103      | 13.12%  |
| RAID | 37       | 4.71%   |
| SAS  | 6        | 0.76%   |
| SCSI | 2        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 350      | 64.46%  |
| AMD               | 189      | 34.81%  |
| ARM               | 2        | 0.37%   |
| Loongson          | 1        | 0.18%   |
| CHRP IBM,8233-E8B | 1        | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz           | 22       | 4.04%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 17       | 3.13%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 12       | 2.21%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 11       | 2.02%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 10       | 1.84%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 10       | 1.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 1.47%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 8        | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.47%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 7        | 1.29%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 7        | 1.29%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 7        | 1.29%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 6        | 1.1%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 6        | 1.1%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 6        | 1.1%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 6        | 1.1%    |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 1.1%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 0.92%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 5        | 0.92%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 5        | 0.92%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 4        | 0.74%   |
| Intel Xeon CPU E3-1240 v6 @ 3.70GHz         | 4        | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 0.74%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 4        | 0.74%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.74%   |
| Intel 13th Gen Core i7-13700K               | 4        | 0.74%   |
| Intel 12th Gen Core i5-12400F               | 4        | 0.74%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 0.74%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 0.74%   |
| Intel Xeon W-2135 CPU @ 3.70GHz             | 3        | 0.55%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 3        | 0.55%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 3        | 0.55%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 3        | 0.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.55%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.55%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.55%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 3        | 0.55%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 3        | 0.55%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 67       | 12.34%  |
| Intel Core i7           | 64       | 11.79%  |
| AMD Ryzen 5             | 47       | 8.66%   |
| Other                   | 46       | 8.47%   |
| AMD Ryzen 7             | 46       | 8.47%   |
| Intel Pentium           | 39       | 7.18%   |
| Intel Xeon              | 36       | 6.63%   |
| AMD Ryzen 9             | 28       | 5.16%   |
| Intel Core i3           | 27       | 4.97%   |
| Intel Celeron           | 21       | 3.87%   |
| AMD Ryzen 3             | 14       | 2.58%   |
| Intel Core 2            | 13       | 2.39%   |
| Intel Core 2 Duo        | 12       | 2.21%   |
| AMD FX                  | 12       | 2.21%   |
| Intel Pentium Dual-Core | 11       | 2.03%   |
| Intel Core 2 Quad       | 7        | 1.29%   |
| AMD Ryzen 5 PRO         | 6        | 1.1%    |
| AMD Phenom II X4        | 4        | 0.74%   |
| AMD Athlon 64 X2        | 4        | 0.74%   |
| AMD Athlon              | 4        | 0.74%   |
| Intel Pentium Gold      | 3        | 0.55%   |
| AMD Phenom II X3        | 3        | 0.55%   |
| AMD Athlon II X3        | 3        | 0.55%   |
| AMD Athlon II X2        | 3        | 0.55%   |
| Intel Pentium 4         | 2        | 0.37%   |
| Intel Core i9           | 2        | 0.37%   |
| AMD Phenom II X6        | 2        | 0.37%   |
| AMD GX                  | 2        | 0.37%   |
| AMD EPYC                | 2        | 0.37%   |
| AMD A6                  | 2        | 0.37%   |
| Intel Pentium Silver    | 1        | 0.18%   |
| Intel Genuine           | 1        | 0.18%   |
| Intel Core m3           | 1        | 0.18%   |
| Intel Atom              | 1        | 0.18%   |
| AMD Ryzen Threadripper  | 1        | 0.18%   |
| AMD PRO A10             | 1        | 0.18%   |
| AMD Phenom              | 1        | 0.18%   |
| AMD E                   | 1        | 0.18%   |
| AMD Athlon II X4        | 1        | 0.18%   |
| AMD A8                  | 1        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 168      | 30.94%  |
| 2      | 139      | 25.6%   |
| 8      | 85       | 15.65%  |
| 6      | 71       | 13.08%  |
| 12     | 24       | 4.42%   |
| 16     | 18       | 3.31%   |
| 3      | 10       | 1.84%   |
| 1      | 8        | 1.47%   |
| 24     | 7        | 1.29%   |
| 10     | 7        | 1.29%   |
| 14     | 3        | 0.55%   |
| 22     | 2        | 0.37%   |
| 5      | 1        | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 536      | 98.71%  |
| 2      | 7        | 1.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 330      | 60.77%  |
| 1      | 212      | 39.04%  |
| 4      | 1        | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 540      | 99.45%  |
| Unknown        | 2        | 0.37%   |
| 32-bit         | 1        | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 144      | 26.33%  |
| 0x306c3    | 56       | 10.24%  |
| 0xa0655    | 22       | 4.02%   |
| 0x1067a    | 21       | 3.84%   |
| 0x906e9    | 18       | 3.29%   |
| 0x08108109 | 17       | 3.11%   |
| 0x506e3    | 16       | 2.93%   |
| 0x0a601203 | 15       | 2.74%   |
| 0x0a50000d | 14       | 2.56%   |
| 0x6f2      | 12       | 2.19%   |
| 0x90672    | 10       | 1.83%   |
| 0x306a9    | 10       | 1.83%   |
| 0x206a7    | 10       | 1.83%   |
| 0x906ea    | 9        | 1.65%   |
| 0x0a20120a | 9        | 1.65%   |
| 0x08701021 | 9        | 1.65%   |
| 0xb0671    | 8        | 1.46%   |
| 0x0800820d | 7        | 1.28%   |
| 0x0a201016 | 6        | 1.1%    |
| 0x08600106 | 6        | 1.1%    |
| 0x08101016 | 6        | 1.1%    |
| 0x0810100b | 6        | 1.1%    |
| 0x06000852 | 6        | 1.1%    |
| 0x406f1    | 5        | 0.91%   |
| 0x08001138 | 5        | 0.91%   |
| 0xa0653    | 4        | 0.73%   |
| 0x906c0    | 4        | 0.73%   |
| 0x10676    | 4        | 0.73%   |
| 0xa0671    | 3        | 0.55%   |
| 0x90675    | 3        | 0.55%   |
| 0x50654    | 3        | 0.55%   |
| 0x20655    | 3        | 0.55%   |
| 0x106a5    | 3        | 0.55%   |
| 0x0600611a | 3        | 0.55%   |
| 0x010000c6 | 3        | 0.55%   |
| 0xb06e0    | 2        | 0.37%   |
| 0x906ed    | 2        | 0.37%   |
| 0x906a3    | 2        | 0.37%   |
| 0x806c2    | 2        | 0.37%   |
| 0x706a1    | 2        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 77       | 14.15%  |
| Zen 3            | 45       | 8.27%   |
| KabyLake         | 44       | 8.09%   |
| CometLake        | 35       | 6.43%   |
| Unknown          | 34       | 6.25%   |
| Zen 2            | 32       | 5.88%   |
| Zen+             | 31       | 5.7%    |
| Penryn           | 31       | 5.7%    |
| Skylake          | 28       | 5.15%   |
| Alderlake Hybrid | 25       | 4.6%    |
| Zen              | 19       | 3.49%   |
| Core             | 19       | 3.49%   |
| SandyBridge      | 18       | 3.31%   |
| K10              | 18       | 3.31%   |
| IvyBridge        | 16       | 2.94%   |
| Piledriver       | 11       | 2.02%   |
| Westmere         | 7        | 1.29%   |
| Nehalem          | 7        | 1.29%   |
| Broadwell        | 7        | 1.29%   |
| Tremont          | 6        | 1.1%    |
| Silvermont       | 6        | 1.1%    |
| TigerLake        | 4        | 0.74%   |
| K8 Hammer        | 4        | 0.74%   |
| Excavator        | 4        | 0.74%   |
| Icelake          | 3        | 0.55%   |
| Goldmont plus    | 3        | 0.55%   |
| NetBurst         | 2        | 0.37%   |
| Jaguar           | 2        | 0.37%   |
| Gracemont        | 2        | 0.37%   |
| Steamroller      | 1        | 0.18%   |
| Goldmont         | 1        | 0.18%   |
| Bulldozer        | 1        | 0.18%   |
| Bobcat           | 1        | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 192      | 33.22%  |
| AMD                        | 185      | 32.01%  |
| Nvidia                     | 184      | 31.83%  |
| ASPEED Technology          | 11       | 1.9%    |
| Matrox Electronics Systems | 5        | 0.87%   |
| Loongson Technology        | 1        | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 35       | 5.91%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 22       | 3.72%   |
| Nvidia GF108 [GeForce GT 730]                                               | 19       | 3.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 18       | 3.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 18       | 3.04%   |
| AMD Raphael                                                                 | 15       | 2.53%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 15       | 2.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 14       | 2.36%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 13       | 2.2%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 13       | 2.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12       | 2.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 12       | 2.03%   |
| ASPEED Technology ASPEED Graphics Family                                    | 11       | 1.86%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 1.69%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 9        | 1.52%   |
| Intel HD Graphics 630                                                       | 9        | 1.52%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 9        | 1.52%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 9        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 1.35%   |
| Intel HD Graphics 530                                                       | 8        | 1.35%   |
| AMD Renoir                                                                  | 8        | 1.35%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 8        | 1.35%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 1.01%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 6        | 1.01%   |
| Intel HD Graphics 510                                                       | 6        | 1.01%   |
| Intel AlderLake-S GT1                                                       | 6        | 1.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.01%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 1.01%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 0.84%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 5        | 0.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 0.84%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 5        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 0.68%   |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 0.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4        | 0.68%   |
| Intel JasperLake [UHD Graphics]                                             | 4        | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 4        | 0.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 4        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 161      | 29.54%  |
| 1 x AMD                 | 159      | 29.17%  |
| 1 x Nvidia              | 157      | 28.81%  |
| Intel + Nvidia          | 19       | 3.49%   |
| 2 x AMD                 | 12       | 2.2%    |
| 1 x ASPEED              | 10       | 1.83%   |
| AMD + Nvidia            | 6        | 1.1%    |
| Other                   | 5        | 0.92%   |
| 1 x Matrox              | 5        | 0.92%   |
| Intel + AMD             | 5        | 0.92%   |
| 2 x Intel               | 2        | 0.37%   |
| 2 x Nvidia              | 1        | 0.18%   |
| 1 x Loongson Technology | 1        | 0.18%   |
| AMD + Matrox            | 1        | 0.18%   |
| AMD + ASPEED            | 1        | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 313      | 57.64%  |
| Unknown     | 162      | 29.83%  |
| Proprietary | 68       | 12.52%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 358      | 65.69%  |
| 7.01-8.0   | 41       | 7.52%   |
| 0.01-0.5   | 34       | 6.24%   |
| 3.01-4.0   | 30       | 5.5%    |
| 1.01-2.0   | 30       | 5.5%    |
| 0.51-1.0   | 16       | 2.94%   |
| 8.01-16.0  | 15       | 2.75%   |
| 5.01-6.0   | 9        | 1.65%   |
| 16.01-24.0 | 7        | 1.28%   |
| 2.01-3.0   | 4        | 0.73%   |
| 4.01-5.0   | 1        | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 61       | 14.77%  |
| Dell                 | 42       | 10.17%  |
| Goldstar             | 39       | 9.44%   |
| Hewlett-Packard      | 33       | 7.99%   |
| Ancor Communications | 30       | 7.26%   |
| BenQ                 | 23       | 5.57%   |
| Acer                 | 23       | 5.57%   |
| AOC                  | 21       | 5.08%   |
| Lenovo               | 14       | 3.39%   |
| Philips              | 13       | 3.15%   |
| ASUSTek Computer     | 11       | 2.66%   |
| LG Electronics       | 8        | 1.94%   |
| Iiyama               | 8        | 1.94%   |
| Sceptre Tech         | 7        | 1.69%   |
| ViewSonic            | 5        | 1.21%   |
| Unknown              | 5        | 1.21%   |
| Unknown              | 4        | 0.97%   |
| Sony                 | 4        | 0.97%   |
| Fujitsu Siemens      | 4        | 0.97%   |
| Vizio                | 3        | 0.73%   |
| RTK                  | 3        | 0.73%   |
| Mi                   | 3        | 0.73%   |
| HKC                  | 3        | 0.73%   |
| Panasonic            | 2        | 0.48%   |
| MStar                | 2        | 0.48%   |
| MSD                  | 2        | 0.48%   |
| MiTAC                | 2        | 0.48%   |
| Hitachi              | 2        | 0.48%   |
| HannStar             | 2        | 0.48%   |
| Gigabyte Technology  | 2        | 0.48%   |
| CHR                  | 2        | 0.48%   |
| YSD                  | 1        | 0.24%   |
| Vita                 | 1        | 0.24%   |
| TCT                  | 1        | 0.24%   |
| TCL                  | 1        | 0.24%   |
| SAC                  | 1        | 0.24%   |
| Plain Tree Systems   | 1        | 0.24%   |
| Pixio                | 1        | 0.24%   |
| PCT                  | 1        | 0.24%   |
| Orion                | 1        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch  | 15       | 3.43%   |
| Unknown                                                                | 5        | 1.14%   |
| Ancor Communications ASUS VB178 ACI1714 1280x1024 338x270mm 17.0-inch  | 4        | 0.92%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 3        | 0.69%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                       | 3        | 0.69%   |
| Hewlett-Packard 23xi HWP3032 1920x1080 509x286mm 23.0-inch             | 3        | 0.69%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 3        | 0.69%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                     | 3        | 0.69%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 3        | 0.69%   |
| Sceptre Tech Sceptre Y32 SPT0CAD 2560x1440 697x392mm 31.5-inch         | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 950x540mm 43.0-inch  | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 0.46%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 0.46%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 0.46%   |
| RTK FHD HDR RTK3B3A 1920x1080 344x195mm 15.6-inch                      | 2        | 0.46%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 2        | 0.46%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                | 2        | 0.46%   |
| MStar Demo MST0030 1360x765 1150x650mm 52.0-inch                       | 2        | 0.46%   |
| LG Electronics LCD Monitor LG FULL HD                                  | 2        | 0.46%   |
| Lenovo T27hv-20 LEN62A9 2560x1440 597x336mm 27.0-inch                  | 2        | 0.46%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch               | 2        | 0.46%   |
| Hewlett-Packard Z27n HWP3216 2560x1440 597x336mm 27.0-inch             | 2        | 0.46%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2        | 0.46%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 2        | 0.46%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                 | 2        | 0.46%   |
| Dell G3223Q DEL428C 3840x2160 710x400mm 32.1-inch                      | 2        | 0.46%   |
| Dell E2414H DEL4091 1920x1080 531x299mm 24.0-inch                      | 2        | 0.46%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                      | 2        | 0.46%   |
| BenQ G2222HDL BNQ785A 1920x1080 477x268mm 21.5-inch                    | 2        | 0.46%   |
| AOC 22B2WG5 AOC2202 1920x1080 477x268mm 21.5-inch                      | 2        | 0.46%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 2        | 0.46%   |
| YSD HDMI YSD0190 1440x900 368x207mm 16.6-inch                          | 1        | 0.23%   |
| Vizio E421VA VIZ0072 1920x1080 930x523mm 42.0-inch                     | 1        | 0.23%   |
| Vizio E320-A0 VIZ0095 1366x768 697x392mm 31.5-inch                     | 1        | 0.23%   |
| Vizio D24f-F1 VIZ1027 1920x1080 527x296mm 23.8-inch                    | 1        | 0.23%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                     | 1        | 0.23%   |
| ViewSonic VX2458 Series VSC36AF 1920x1080 521x293mm 23.5-inch          | 1        | 0.23%   |
| ViewSonic VG2755-2K VSC4E37 2560x1440 597x336mm 27.0-inch              | 1        | 0.23%   |
| ViewSonic VG175 VSCDD00 1280x1024 345x276mm 17.4-inch                  | 1        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 173      | 43.03%  |
| 3840x2160 (4K)     | 53       | 13.18%  |
| 2560x1440 (QHD)    | 45       | 11.19%  |
| 1280x1024 (SXGA)   | 18       | 4.48%   |
| Unknown            | 16       | 3.98%   |
| 1920x1200 (WUXGA)  | 11       | 2.74%   |
| 1680x1050 (WSXGA+) | 11       | 2.74%   |
| 1600x900 (HD+)     | 11       | 2.74%   |
| 1366x768 (WXGA)    | 11       | 2.74%   |
| 3440x1440          | 8        | 1.99%   |
| 1440x900 (WXGA+)   | 8        | 1.99%   |
| 2560x1080          | 7        | 1.74%   |
| 1360x768           | 5        | 1.24%   |
| 4480x1440          | 4        | 1%      |
| 2288x1287          | 3        | 0.75%   |
| 1920x540           | 3        | 0.75%   |
| 7680x2160          | 2        | 0.5%    |
| 3840x1600          | 2        | 0.5%    |
| 3840x1200          | 2        | 0.5%    |
| 3840x1080          | 2        | 0.5%    |
| 7280x2160          | 1        | 0.25%   |
| 6400x2160          | 1        | 0.25%   |
| 6400x1440          | 1        | 0.25%   |
| 5760x2160          | 1        | 0.25%   |
| 3286x1080          | 1        | 0.25%   |
| 1600x1200          | 1        | 0.25%   |
| 1400x1050          | 1        | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 66       | 16.34%  |
| 24      | 61       | 15.1%   |
| 21      | 61       | 15.1%   |
| 23      | 41       | 10.15%  |
| Unknown | 35       | 8.66%   |
| 31      | 18       | 4.46%   |
| 18      | 15       | 3.71%   |
| 19      | 13       | 3.22%   |
| 34      | 12       | 2.97%   |
| 20      | 12       | 2.97%   |
| 17      | 11       | 2.72%   |
| 84      | 7        | 1.73%   |
| 32      | 7        | 1.73%   |
| 22      | 6        | 1.49%   |
| 142     | 3        | 0.74%   |
| 52      | 3        | 0.74%   |
| 40      | 3        | 0.74%   |
| 15      | 3        | 0.74%   |
| 72      | 2        | 0.5%    |
| 54      | 2        | 0.5%    |
| 48      | 2        | 0.5%    |
| 46      | 2        | 0.5%    |
| 39      | 2        | 0.5%    |
| 33      | 2        | 0.5%    |
| 28      | 2        | 0.5%    |
| 26      | 2        | 0.5%    |
| 16      | 2        | 0.5%    |
| 85      | 1        | 0.25%   |
| 49      | 1        | 0.25%   |
| 43      | 1        | 0.25%   |
| 42      | 1        | 0.25%   |
| 41      | 1        | 0.25%   |
| 38      | 1        | 0.25%   |
| 37      | 1        | 0.25%   |
| 35      | 1        | 0.25%   |
| 14      | 1        | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 155      | 39.74%  |
| 401-500        | 98       | 25.13%  |
| Unknown        | 35       | 8.97%   |
| 601-700        | 24       | 6.15%   |
| 701-800        | 21       | 5.38%   |
| 301-350        | 15       | 3.85%   |
| 1501-2000      | 10       | 2.56%   |
| 1001-1500      | 10       | 2.56%   |
| 801-900        | 7        | 1.79%   |
| 351-400        | 7        | 1.79%   |
| 901-1000       | 4        | 1.03%   |
| More than 2000 | 3        | 0.77%   |
| 201-300        | 1        | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 262      | 70.81%  |
| 16/10   | 33       | 8.92%   |
| Unknown | 31       | 8.38%   |
| 21/9    | 17       | 4.59%   |
| 5/4     | 16       | 4.32%   |
| 4/3     | 3        | 0.81%   |
| 1.00    | 3        | 0.81%   |
| 6/5     | 2        | 0.54%   |
| 32/9    | 2        | 0.54%   |
| 3/2     | 1        | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 134      | 33.33%  |
| 301-350        | 67       | 16.67%  |
| 351-500        | 42       | 10.45%  |
| 151-200        | 37       | 9.2%    |
| Unknown        | 35       | 8.71%   |
| 251-300        | 24       | 5.97%   |
| 141-150        | 23       | 5.72%   |
| More than 1000 | 21       | 5.22%   |
| 501-1000       | 12       | 2.99%   |
| 101-110        | 4        | 1%      |
| 131-140        | 2        | 0.5%    |
| 111-120        | 1        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 202      | 52.88%  |
| 101-120 | 94       | 24.61%  |
| Unknown | 35       | 9.16%   |
| 121-160 | 23       | 6.02%   |
| 161-240 | 15       | 3.93%   |
| 1-50    | 13       | 3.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 296      | 54.31%  |
| 0     | 181      | 33.21%  |
| 2     | 59       | 10.83%  |
| 3     | 9        | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 359      | 47.93%  |
| Intel                           | 214      | 28.57%  |
| Qualcomm Atheros                | 32       | 4.27%   |
| MediaTek                        | 26       | 3.47%   |
| Broadcom                        | 17       | 2.27%   |
| Ralink Technology               | 14       | 1.87%   |
| Nvidia                          | 11       | 1.47%   |
| TP-Link                         | 9        | 1.2%    |
| Aquantia                        | 8        | 1.07%   |
| Marvell Technology Group        | 5        | 0.67%   |
| ASUSTek Computer                | 4        | 0.53%   |
| ASIX Electronics                | 4        | 0.53%   |
| Samsung Electronics             | 3        | 0.4%    |
| QinHeng Electronics             | 3        | 0.4%    |
| Broadcom Limited                | 3        | 0.4%    |
| Ralink                          | 2        | 0.27%   |
| Qualcomm Atheros Communications | 2        | 0.27%   |
| Mellanox Technologies           | 2        | 0.27%   |
| D-Link System                   | 2        | 0.27%   |
| D-Link                          | 2        | 0.27%   |
| American Megatrends             | 2        | 0.27%   |
| 3Com                            | 2        | 0.27%   |
| Texas Instruments               | 1        | 0.13%   |
| SysKonnect                      | 1        | 0.13%   |
| Solarflare Communications       | 1        | 0.13%   |
| SEGGER                          | 1        | 0.13%   |
| Raspberry Pi                    | 1        | 0.13%   |
| Qualcomm                        | 1        | 0.13%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.13%   |
| NetGear                         | 1        | 0.13%   |
| Motorola PCS                    | 1        | 0.13%   |
| Microsoft                       | 1        | 0.13%   |
| Microchip Technology            | 1        | 0.13%   |
| MCS                             | 1        | 0.13%   |
| Loongson Technology             | 1        | 0.13%   |
| Linksys                         | 1        | 0.13%   |
| Insyde Software                 | 1        | 0.13%   |
| IBM                             | 1        | 0.13%   |
| Google                          | 1        | 0.13%   |
| Emulex                          | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 281      | 33.14%  |
| Realtek RTL8125 2.5GbE Controller                                   | 41       | 4.83%   |
| Intel Ethernet Controller I225-V                                    | 31       | 3.66%   |
| Intel Wi-Fi 6 AX200                                                 | 27       | 3.18%   |
| Intel I211 Gigabit Network Connection                               | 22       | 2.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 15       | 1.77%   |
| Intel Ethernet Connection (2) I219-V                                | 15       | 1.77%   |
| Intel Ethernet Connection I217-LM                                   | 14       | 1.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 13       | 1.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 13       | 1.53%   |
| Intel 82566DM Gigabit Network Connection                            | 12       | 1.42%   |
| Intel I210 Gigabit Network Connection                               | 11       | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 10       | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10       | 1.18%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 9        | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller         | 8        | 0.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 8        | 0.94%   |
| Intel 700 Series Chipset Family Wi-Fi                               | 8        | 0.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 7        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6        | 0.71%   |
| Realtek 802.11ac NIC                                                | 6        | 0.71%   |
| Intel Ethernet Controller I226-V                                    | 6        | 0.71%   |
| Intel Ethernet Connection I217-V                                    | 6        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6        | 0.71%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 0.71%   |
| Ralink MT7601U Wireless Adapter                                     | 5        | 0.59%   |
| Intel Wireless 7260                                                 | 5        | 0.59%   |
| Intel 82574L Gigabit Network Connection                             | 5        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)      | 4        | 0.47%   |
| Nvidia MCP61 Ethernet                                               | 4        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 4        | 0.47%   |
| Intel Wireless-AC 9260                                              | 4        | 0.47%   |
| Intel Ethernet Connection (11) I219-LM                              | 4        | 0.47%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 4        | 0.47%   |
| Intel 82579V Gigabit Network Connection                             | 4        | 0.47%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 4        | 0.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 3        | 0.35%   |
| TP-Link 802.11ac WLAN Adapter                                       | 3        | 0.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 3        | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 83       | 38.97%  |
| Realtek Semiconductor           | 40       | 18.78%  |
| MediaTek                        | 25       | 11.74%  |
| Qualcomm Atheros                | 18       | 8.45%   |
| Ralink Technology               | 14       | 6.57%   |
| TP-Link                         | 9        | 4.23%   |
| Broadcom                        | 6        | 2.82%   |
| ASUSTek Computer                | 4        | 1.88%   |
| Ralink                          | 2        | 0.94%   |
| Qualcomm Atheros Communications | 2        | 0.94%   |
| D-Link                          | 2        | 0.94%   |
| Broadcom Limited                | 2        | 0.94%   |
| NetGear                         | 1        | 0.47%   |
| Microsoft                       | 1        | 0.47%   |
| Marvell Technology Group        | 1        | 0.47%   |
| Linksys                         | 1        | 0.47%   |
| Edimax Technology               | 1        | 0.47%   |
| Belkin Components               | 1        | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 27       | 12.56%  |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 13       | 6.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13       | 6.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 9        | 4.19%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8        | 3.72%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 8        | 3.72%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 7        | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6        | 2.79%   |
| Realtek 802.11ac NIC                                           | 6        | 2.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6        | 2.79%   |
| Ralink MT7601U Wireless Adapter                                | 5        | 2.33%   |
| Intel Wireless 7260                                            | 5        | 2.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4        | 1.86%   |
| Intel Wireless-AC 9260                                         | 4        | 1.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3        | 1.4%    |
| TP-Link 802.11ac WLAN Adapter                                  | 3        | 1.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3        | 1.4%    |
| Ralink RT5572 Wireless Adapter                                 | 3        | 1.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3        | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3        | 1.4%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 3        | 1.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2        | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                 | 2        | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 0.93%   |
| Intel Wireless 8260                                            | 2        | 0.93%   |
| Intel Wireless 7265                                            | 2        | 0.93%   |
| Intel Wireless 3165                                            | 2        | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2        | 0.93%   |
| ASUS 802.11ac NIC                                              | 2        | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 0.47%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 1        | 0.47%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.47%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1        | 0.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 0.47%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 353      | 58.54%  |
| Intel                     | 171      | 28.36%  |
| Qualcomm Atheros          | 16       | 2.65%   |
| Nvidia                    | 11       | 1.82%   |
| Broadcom                  | 11       | 1.82%   |
| Aquantia                  | 8        | 1.33%   |
| Marvell Technology Group  | 4        | 0.66%   |
| ASIX Electronics          | 4        | 0.66%   |
| Samsung Electronics       | 3        | 0.5%    |
| Mellanox Technologies     | 2        | 0.33%   |
| D-Link System             | 2        | 0.33%   |
| American Megatrends       | 2        | 0.33%   |
| 3Com                      | 2        | 0.33%   |
| SysKonnect                | 1        | 0.17%   |
| Solarflare Communications | 1        | 0.17%   |
| Qualcomm                  | 1        | 0.17%   |
| Motorola PCS              | 1        | 0.17%   |
| Microchip Technology      | 1        | 0.17%   |
| MediaTek                  | 1        | 0.17%   |
| Loongson Technology       | 1        | 0.17%   |
| Insyde Software           | 1        | 0.17%   |
| IBM                       | 1        | 0.17%   |
| Google                    | 1        | 0.17%   |
| Emulex                    | 1        | 0.17%   |
| DisplayLink               | 1        | 0.17%   |
| Broadcom Limited          | 1        | 0.17%   |
| Accton Technology         | 1        | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 281      | 45.03%  |
| Realtek RTL8125 2.5GbE Controller                                   | 41       | 6.57%   |
| Intel Ethernet Controller I225-V                                    | 31       | 4.97%   |
| Intel I211 Gigabit Network Connection                               | 22       | 3.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 15       | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                | 15       | 2.4%    |
| Intel Ethernet Connection I217-LM                                   | 14       | 2.24%   |
| Intel 82566DM Gigabit Network Connection                            | 12       | 1.92%   |
| Intel I210 Gigabit Network Connection                               | 11       | 1.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 10       | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10       | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 8        | 1.28%   |
| Intel Ethernet Controller I226-V                                    | 6        | 0.96%   |
| Intel Ethernet Connection I217-V                                    | 6        | 0.96%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 0.96%   |
| Intel 82574L Gigabit Network Connection                             | 5        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.64%   |
| Nvidia MCP61 Ethernet                                               | 4        | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 4        | 0.64%   |
| Intel Ethernet Connection (11) I219-LM                              | 4        | 0.64%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                | 4        | 0.64%   |
| Intel 82579V Gigabit Network Connection                             | 4        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 4        | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 3        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 3        | 0.48%   |
| Nvidia MCP65 Ethernet                                               | 3        | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                               | 3        | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                               | 3        | 0.48%   |
| Intel Ethernet Connection (14) I219-V                               | 3        | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 3        | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                       | 3        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 2        | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2        | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 2        | 0.32%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                       | 2        | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 2        | 0.32%   |
| Nvidia MCP73 Ethernet                                               | 2        | 0.32%   |
| Intel Ethernet Connection (2) I218-LM                               | 2        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 536      | 72.73%  |
| WiFi     | 193      | 26.19%  |
| Modem    | 6        | 0.81%   |
| Unknown  | 2        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 459      | 83.3%   |
| WiFi     | 92       | 16.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 343      | 62.82%  |
| 2     | 156      | 28.57%  |
| 3     | 26       | 4.76%   |
| 4     | 12       | 2.2%    |
| 6     | 4        | 0.73%   |
| 0     | 3        | 0.55%   |
| 12    | 1        | 0.18%   |
| 9     | 1        | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 429      | 78.86%  |
| Yes  | 115      | 21.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 71       | 40.57%  |
| Realtek Semiconductor           | 26       | 14.86%  |
| Cambridge Silicon Radio         | 23       | 13.14%  |
| MediaTek                        | 14       | 8%      |
| ASUSTek Computer                | 7        | 4%      |
| Foxconn / Hon Hai               | 6        | 3.43%   |
| Broadcom                        | 6        | 3.43%   |
| TP-Link                         | 5        | 2.86%   |
| Qualcomm Atheros Communications | 4        | 2.29%   |
| IMC Networks                    | 3        | 1.71%   |
| Apple                           | 2        | 1.14%   |
| Actions                         | 2        | 1.14%   |
| Realtek                         | 1        | 0.57%   |
| Lite-On Technology              | 1        | 0.57%   |
| Integrated System Solution      | 1        | 0.57%   |
| HTC (High Tech Computer)        | 1        | 0.57%   |
| Edimax Technology               | 1        | 0.57%   |
| Dynex                           | 1        | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                                              | 23       | 13.14%  |
| Intel AX200 Bluetooth                                                | 23       | 13.14%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 23       | 13.14%  |
| MediaTek Wireless_Device                                             | 14       | 8%      |
| Intel Bluetooth wireless interface                                   | 11       | 6.29%   |
| Intel AX201 Bluetooth                                                | 10       | 5.71%   |
| Intel Bluetooth Device                                               | 9        | 5.14%   |
| Intel AX210 Bluetooth                                                | 9        | 5.14%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6        | 3.43%   |
| TP-Link UB5A Adapter                                                 | 5        | 2.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 4        | 2.29%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 4        | 2.29%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 4        | 2.29%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 3        | 1.71%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3        | 1.71%   |
| IMC Networks Bluetooth Radio                                         | 3        | 1.71%   |
| Actions general adapter                                              | 2        | 1.14%   |
| Realtek Bluetooth Radio                                              | 1        | 0.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 0.57%   |
| Lite-On Bluetooth Device                                             | 1        | 0.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.57%   |
| Integrated System Solution Bluetooth Device                          | 1        | 0.57%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.57%   |
| Edimax Bluetooth Adapter                                             | 1        | 0.57%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.57%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                    | 1        | 0.57%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.57%   |
| ASUS BCM20702A0                                                      | 1        | 0.57%   |
| ASUS ASUS USB-BT500                                                  | 1        | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 0.57%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 325      | 38.33%  |
| AMD                                          | 221      | 26.06%  |
| Nvidia                                       | 180      | 21.23%  |
| C-Media Electronics                          | 23       | 2.71%   |
| Logitech                                     | 9        | 1.06%   |
| Creative Labs                                | 8        | 0.94%   |
| ASUSTek Computer                             | 8        | 0.94%   |
| Micro Star International                     | 6        | 0.71%   |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.59%   |
| Realtek Semiconductor                        | 5        | 0.59%   |
| Focusrite-Novation                           | 5        | 0.59%   |
| Texas Instruments                            | 4        | 0.47%   |
| JMTek                                        | 4        | 0.47%   |
| GN Netcom                                    | 4        | 0.47%   |
| SteelSeries ApS                              | 3        | 0.35%   |
| Kingston Technology                          | 3        | 0.35%   |
| Generalplus Technology                       | 3        | 0.35%   |
| Corsair                                      | 3        | 0.35%   |
| BR23                                         | 3        | 0.35%   |
| Blue Microphones                             | 3        | 0.35%   |
| Razer USA                                    | 2        | 0.24%   |
| Yamaha                                       | 1        | 0.12%   |
| VIA Technologies                             | 1        | 0.12%   |
| USB MICROPHONE                               | 1        | 0.12%   |
| Tdlasunnic                                   | 1        | 0.12%   |
| Schiit Audio                                 | 1        | 0.12%   |
| Samson Technologies                          | 1        | 0.12%   |
| OPPO Electronics                             | 1        | 0.12%   |
| Loongson Technology                          | 1        | 0.12%   |
| Hewlett-Packard                              | 1        | 0.12%   |
| Global Sun Technology                        | 1        | 0.12%   |
| Giga-Byte Technology                         | 1        | 0.12%   |
| Dell                                         | 1        | 0.12%   |
| DCMT Technology                              | 1        | 0.12%   |
| D&M Holdings (Denon/Marantz)                 | 1        | 0.12%   |
| Creative Technology                          | 1        | 0.12%   |
| Cayin                                        | 1        | 0.12%   |
| Bose                                         | 1        | 0.12%   |
| BlackWeb                                     | 1        | 0.12%   |
| BEHRINGER International                      | 1        | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 73       | 7.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 61       | 5.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 47       | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 46       | 4.45%   |
| Intel 200 Series PCH HD Audio                                              | 35       | 3.39%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 28       | 2.71%   |
| Intel Comet Lake PCH cAVS                                                  | 27       | 2.61%   |
| Nvidia GF108 High Definition Audio Controller                              | 25       | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25       | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 24       | 2.32%   |
| Nvidia TU106 High Definition Audio Controller                              | 23       | 2.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21       | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20       | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19       | 1.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 18       | 1.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 17       | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17       | 1.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 17       | 1.65%   |
| Intel Alder Lake-S HD Audio Controller                                     | 14       | 1.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 14       | 1.36%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 12       | 1.16%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 12       | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 11       | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 11       | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10       | 0.97%   |
| Nvidia GP108 High Definition Audio Controller                              | 10       | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 10       | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 10       | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10       | 0.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 0.87%   |
| Nvidia High Definition Audio Controller                                    | 8        | 0.77%   |
| Nvidia GA102 High Definition Audio Controller                              | 8        | 0.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 8        | 0.77%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 0.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 0.68%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 0.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7        | 0.68%   |
| ASUSTek Computer USB Audio                                                 | 7        | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 110      | 23.06%  |
| Unknown                                 | 69       | 14.47%  |
| Crucial                                 | 50       | 10.48%  |
| Samsung Electronics                     | 48       | 10.06%  |
| SK hynix                                | 31       | 6.5%    |
| G.Skill                                 | 31       | 6.5%    |
| Corsair                                 | 31       | 6.5%    |
| Hikvision                               | 18       | 3.77%   |
| A-DATA Technology                       | 14       | 2.94%   |
| Unknown                                 | 12       | 2.52%   |
| Micron Technology                       | 11       | 2.31%   |
| Patriot                                 | 9        | 1.89%   |
| Micro Memory Bank                       | 8        | 1.68%   |
| Team                                    | 5        | 1.05%   |
| AMD                                     | 3        | 0.63%   |
| Toshiba                                 | 2        | 0.42%   |
| Patriot Memory (PDP Systems)            | 2        | 0.42%   |
| Elpida                                  | 2        | 0.42%   |
| V-Color                                 | 1        | 0.21%   |
| Unknown (ABCD)                          | 1        | 0.21%   |
| Unknown (0x7FFF)                        | 1        | 0.21%   |
| Unknown (0x0E9D)                        | 1        | 0.21%   |
| Transcend                               | 1        | 0.21%   |
| Smart                                   | 1        | 0.21%   |
| Silicon Power Computer & Communications | 1        | 0.21%   |
| Shenzhen Mic                            | 1        | 0.21%   |
| Ramaxel Technology                      | 1        | 0.21%   |
| PUSKILL                                 | 1        | 0.21%   |
| Nanya Technology                        | 1        | 0.21%   |
| KLEVV                                   | 1        | 0.21%   |
| KingSpec                                | 1        | 0.21%   |
| Kingmax                                 | 1        | 0.21%   |
| Kimtigo Semiconductor (HK) Limited      | 1        | 0.21%   |
| Hewlett-Packard                         | 1        | 0.21%   |
| Gigabyte Technology                     | 1        | 0.21%   |
| GeIL                                    | 1        | 0.21%   |
| Avant                                   | 1        | 0.21%   |
| Apacer                                  | 1        | 0.21%   |
| 48spaces                                | 1        | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s                          | 18       | 3.49%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s                            | 15       | 2.91%   |
| Unknown                                                                          | 12       | 2.33%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                              | 10       | 1.94%   |
| Unknown RAM Module 2GB DIMM SDRAM                                                | 8        | 1.55%   |
| Micro Memory Bank RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 2GB DIMM DDR2 667MT/s | 8        | 1.55%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                            | 7        | 1.36%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                             | 6        | 1.16%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                             | 6        | 1.16%   |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s                                   | 6        | 1.16%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s                           | 6        | 1.16%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                            | 6        | 1.16%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                              | 5        | 0.97%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                             | 5        | 0.97%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                             | 4        | 0.78%   |
| Unknown RAM Module 1GB DIMM SDRAM                                                | 4        | 0.78%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                                         | 3        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                         | 3        | 0.58%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                              | 3        | 0.58%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                              | 3        | 0.58%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                              | 3        | 0.58%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                             | 3        | 0.58%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s                              | 3        | 0.58%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s                             | 3        | 0.58%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6000MT/s                             | 3        | 0.58%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s                            | 3        | 0.58%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s                             | 3        | 0.58%   |
| Crucial RAM 524D313238363441413636372E384648FFFF 1GB DIMM DDR2 667MT/s           | 3        | 0.58%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                                      | 3        | 0.58%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                        | 2        | 0.39%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                             | 2        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                         | 2        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                         | 2        | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                         | 2        | 0.39%   |
| Unknown RAM Module 1GB DIMM 800MT/s                                              | 2        | 0.39%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s                             | 2        | 0.39%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s                                       | 2        | 0.39%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s                              | 2        | 0.39%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s                             | 2        | 0.39%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s                             | 2        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 222      | 50.34%  |
| DDR3    | 102      | 23.13%  |
| DDR2    | 29       | 6.58%   |
| DDR5    | 28       | 6.35%   |
| Unknown | 28       | 6.35%   |
| SDRAM   | 21       | 4.76%   |
| DDR     | 6        | 1.36%   |
| LPDDR4  | 4        | 0.91%   |
| LPDDR3  | 1        | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 389      | 89.02%  |
| SODIMM       | 42       | 9.61%   |
| Row Of Chips | 3        | 0.69%   |
| RIMM         | 2        | 0.46%   |
| FB-DIMM      | 1        | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 154      | 32.7%   |
| 16384 | 90       | 19.11%  |
| 4096  | 84       | 17.83%  |
| 2048  | 67       | 14.23%  |
| 32768 | 46       | 9.77%   |
| 1024  | 21       | 4.46%   |
| 512   | 7        | 1.49%   |
| 65536 | 1        | 0.21%   |
| 64    | 1        | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 55       | 11.65%  |
| 3200    | 54       | 11.44%  |
| 2667    | 53       | 11.23%  |
| 1333    | 39       | 8.26%   |
| 3600    | 37       | 7.84%   |
| 2400    | 23       | 4.87%   |
| 667     | 23       | 4.87%   |
| 2133    | 22       | 4.66%   |
| 1866    | 18       | 3.81%   |
| Unknown | 15       | 3.18%   |
| 800     | 14       | 2.97%   |
| 4333    | 10       | 2.12%   |
| 6000    | 9        | 1.91%   |
| 4800    | 9        | 1.91%   |
| 1066    | 8        | 1.69%   |
| 3000    | 6        | 1.27%   |
| 2666    | 6        | 1.27%   |
| 1867    | 6        | 1.27%   |
| 5200    | 5        | 1.06%   |
| 3400    | 5        | 1.06%   |
| 3266    | 5        | 1.06%   |
| 3800    | 3        | 0.64%   |
| 3733    | 3        | 0.64%   |
| 2866    | 3        | 0.64%   |
| 1067    | 3        | 0.64%   |
| 3933    | 2        | 0.42%   |
| 3534    | 2        | 0.42%   |
| 3334    | 2        | 0.42%   |
| 2933    | 2        | 0.42%   |
| 2800    | 2        | 0.42%   |
| 1800    | 2        | 0.42%   |
| 1648    | 2        | 0.42%   |
| 1639    | 2        | 0.42%   |
| 7000    | 1        | 0.21%   |
| 6800    | 1        | 0.21%   |
| 6400    | 1        | 0.21%   |
| 5800    | 1        | 0.21%   |
| 5600    | 1        | 0.21%   |
| 5354    | 1        | 0.21%   |
| 4199    | 1        | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 6        | 28.57%  |
| Brother Industries  | 5        | 23.81%  |
| Hewlett-Packard     | 3        | 14.29%  |
| Samsung Electronics | 2        | 9.52%   |
| Dymo-CoStar         | 2        | 9.52%   |
| Zebra               | 1        | 4.76%   |
| Seiko Epson         | 1        | 4.76%   |
| Pantum              | 1        | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon MF3010                           | 2        | 9.52%   |
| Zebra Printer                          | 1        | 4.76%   |
| Seiko Epson ET-4850 Series             | 1        | 4.76%   |
| Samsung M2070 Series                   | 1        | 4.76%   |
| Samsung M2020 Series                   | 1        | 4.76%   |
| Pantum P2500W series                   | 1        | 4.76%   |
| HP Officejet 4500 G510a-f              | 1        | 4.76%   |
| HP LaserJet P2035                      | 1        | 4.76%   |
| HP ENVY 5540 series                    | 1        | 4.76%   |
| Dymo-CoStar DYMO LabelWriter DUO       | 1        | 4.76%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 4.76%   |
| Canon TS3100 series                    | 1        | 4.76%   |
| Canon PIXMA iP4300 Printer             | 1        | 4.76%   |
| Canon MF4010 series                    | 1        | 4.76%   |
| Canon LiDE 400                         | 1        | 4.76%   |
| Brother HL-L2390DW                     | 1        | 4.76%   |
| Brother HL-3040CN series               | 1        | 4.76%   |
| Brother HL-1110 series                 | 1        | 4.76%   |
| Brother DCP-L8450CDW                   | 1        | 4.76%   |
| Brother DCP-7030                       | 1        | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 40%     |
| Seiko Epson     | 1        | 20%     |
| Plustek         | 1        | 20%     |
| Hewlett-Packard | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1        | 20%     |
| Plustek 1200dpi USB Scanner                       | 1        | 20%     |
| HP ScanJet 82x0C                                  | 1        | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20                | 1        | 20%     |
| Canon CanoScan LiDE 210                           | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 35       | 41.67%  |
| Microsoft                     | 10       | 11.9%   |
| Generalplus Technology        | 5        | 5.95%   |
| Microdia                      | 4        | 4.76%   |
| Sunplus Innovation Technology | 3        | 3.57%   |
| Samsung Electronics           | 3        | 3.57%   |
| KYE Systems (Mouse Systems)   | 3        | 3.57%   |
| Z-Star Microelectronics       | 2        | 2.38%   |
| Realtek Semiconductor         | 2        | 2.38%   |
| Jieli Technology              | 2        | 2.38%   |
| ValueHD                       | 1        | 1.19%   |
| Tobii Technology AB           | 1        | 1.19%   |
| Ruision                       | 1        | 1.19%   |
| Quanta                        | 1        | 1.19%   |
| Magic Control Technology      | 1        | 1.19%   |
| MacroSilicon                  | 1        | 1.19%   |
| IMC Networks                  | 1        | 1.19%   |
| Hewlett-Packard               | 1        | 1.19%   |
| GEMBIRD                       | 1        | 1.19%   |
| EVGA                          | 1        | 1.19%   |
| Creative Technology           | 1        | 1.19%   |
| Chicony Electronics           | 1        | 1.19%   |
| AVerMedia Technologies        | 1        | 1.19%   |
| Aveo Technology               | 1        | 1.19%   |
| Apple                         | 1        | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 11       | 13.1%   |
| Logitech HD Pro Webcam C920                | 10       | 11.9%   |
| Microsoft LifeCam HD-3000                  | 5        | 5.95%   |
| Generalplus CAMERA - UVC                   | 5        | 5.95%   |
| Logitech C922 Pro Stream Webcam            | 4        | 4.76%   |
| Samsung Galaxy series, misc. (MTP mode)    | 3        | 3.57%   |
| Sunplus Integrated_Webcam_HD               | 2        | 2.38%   |
| Realtek Full HD webcam                     | 2        | 2.38%   |
| Microdia Webcam Vitade AF                  | 2        | 2.38%   |
| Logitech HD Webcam C525                    | 2        | 2.38%   |
| Logitech CrystalCam                        | 2        | 2.38%   |
| Jieli USB PHY 2.0                          | 2        | 2.38%   |
| Z-Star Venus USB2.0 Camera                 | 1        | 1.19%   |
| Z-Star A4 tech USB2.0 Camera               | 1        | 1.19%   |
| ValueHD PTZOptics                          | 1        | 1.19%   |
| Tobii AB EyeChip                           | 1        | 1.19%   |
| Sunplus USB 2.0 Camera                     | 1        | 1.19%   |
| Ruision UVC Camera                         | 1        | 1.19%   |
| Quanta RGB-IR Camera                       | 1        | 1.19%   |
| Microsoft Modern Webcam                    | 1        | 1.19%   |
| Microsoft MicrosoftÂ LifeCam Studio       | 1        | 1.19%   |
| Microsoft MicrosoftÂ LifeCam Cinema       | 1        | 1.19%   |
| Microsoft LifeCam VX-800                   | 1        | 1.19%   |
| Microsoft LifeCam HD-5000                  | 1        | 1.19%   |
| Microdia USB 2.0 Camera                    | 1        | 1.19%   |
| Microdia Sonix USB 2.0 Camera              | 1        | 1.19%   |
| Magic Control j5 WebCam JVCU435            | 1        | 1.19%   |
| MacroSilicon USB3. 0 capture               | 1        | 1.19%   |
| Logitech Webcam C170                       | 1        | 1.19%   |
| Logitech StreamCam                         | 1        | 1.19%   |
| Logitech C930c                             | 1        | 1.19%   |
| Logitech BRIO 4K Stream Edition            | 1        | 1.19%   |
| Logitech BRIO                              | 1        | 1.19%   |
| Logitech B525 HD Webcam                    | 1        | 1.19%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 1.19%   |
| KYE Systems (Mouse Systems) Genius Webcam  | 1        | 1.19%   |
| KYE Systems (Mouse Systems) FaceCam 1000X  | 1        | 1.19%   |
| IMC Networks USB 2.0 Camera                | 1        | 1.19%   |
| HP Webcam 3110                             | 1        | 1.19%   |
| GEMBIRD USB2.0 PC CAMERA                   | 1        | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 50%     |
| SCM Microsystems      | 1        | 25%     |
| Cherry                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 2        | 50%     |
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 25%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC       | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 330      | 60.44%  |
| 1     | 192      | 35.16%  |
| 2     | 22       | 4.03%   |
| 5     | 2        | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 170      | 76.92%  |
| Net/wireless             | 22       | 9.95%   |
| Unassigned class         | 9        | 4.07%   |
| Bluetooth                | 4        | 1.81%   |
| Sound                    | 3        | 1.36%   |
| Communication controller | 3        | 1.36%   |
| Storage/raid             | 2        | 0.9%    |
| Multimedia controller    | 2        | 0.9%    |
| Camera                   | 2        | 0.9%    |
| Wireless                 | 1        | 0.45%   |
| Network                  | 1        | 0.45%   |
| Modem                    | 1        | 0.45%   |
| Chipcard                 | 1        | 0.45%   |

