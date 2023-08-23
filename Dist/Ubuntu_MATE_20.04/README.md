Ubuntu MATE 20.04 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE_20.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE_20.04/Notebook/README.md).

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

Total: 865

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P6X58D-E                    | Desktop     | [84a5ec2d0b](https://linux-hardware.org/?probe=84a5ec2d0b) | Aug 01, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [b42a0455f7](https://linux-hardware.org/?probe=b42a0455f7) | Jul 26, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [60809c13e6](https://linux-hardware.org/?probe=60809c13e6) | Jul 15, 2023 |
| HP            | 339A                        | Desktop     | [8d051ead1c](https://linux-hardware.org/?probe=8d051ead1c) | Jul 05, 2023 |
| Dell          | G5 5590                     | Notebook    | [c956c1fd2e](https://linux-hardware.org/?probe=c956c1fd2e) | Jul 03, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [69b69e2a09](https://linux-hardware.org/?probe=69b69e2a09) | Jun 30, 2023 |
| Dell          | Studio 1558                 | Notebook    | [66e76ea87d](https://linux-hardware.org/?probe=66e76ea87d) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [2eeb463035](https://linux-hardware.org/?probe=2eeb463035) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [ef129b5a6c](https://linux-hardware.org/?probe=ef129b5a6c) | Jun 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| Avell High... | A72 HYB                     | Notebook    | [c6f131b8b1](https://linux-hardware.org/?probe=c6f131b8b1) | May 24, 2023 |
| Avell High... | A72 HYB                     | Notebook    | [d54fb61d87](https://linux-hardware.org/?probe=d54fb61d87) | May 24, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [5b51a121e2](https://linux-hardware.org/?probe=5b51a121e2) | May 18, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [456582ed94](https://linux-hardware.org/?probe=456582ed94) | May 03, 2023 |
| ASRock        | H170A-X1                    | Desktop     | [a89448e417](https://linux-hardware.org/?probe=a89448e417) | Apr 28, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [83f752ffd8](https://linux-hardware.org/?probe=83f752ffd8) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [ecefe27269](https://linux-hardware.org/?probe=ecefe27269) | Apr 13, 2023 |
| ASUSTek       | U6Sg                        | Notebook    | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| Dell          | Latitude E6320              | Notebook    | [a6a0d01947](https://linux-hardware.org/?probe=a6a0d01947) | Mar 31, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [ce6f515364](https://linux-hardware.org/?probe=ce6f515364) | Mar 19, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [0bb94771bc](https://linux-hardware.org/?probe=0bb94771bc) | Mar 18, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [4a54741fec](https://linux-hardware.org/?probe=4a54741fec) | Mar 12, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [fb3c4afbaa](https://linux-hardware.org/?probe=fb3c4afbaa) | Feb 26, 2023 |
| ASUSTek       | P5K                         | Desktop     | [1769888b2b](https://linux-hardware.org/?probe=1769888b2b) | Feb 23, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [68dcf39492](https://linux-hardware.org/?probe=68dcf39492) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [127e027611](https://linux-hardware.org/?probe=127e027611) | Feb 10, 2023 |
| BESSTAR Te... | CB9                         | Mini pc     | [23fe29b164](https://linux-hardware.org/?probe=23fe29b164) | Feb 05, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [91dea34a76](https://linux-hardware.org/?probe=91dea34a76) | Jan 20, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [08502cda27](https://linux-hardware.org/?probe=08502cda27) | Jan 20, 2023 |
| HP            | 805A                        | Desktop     | [5fdeec8d8a](https://linux-hardware.org/?probe=5fdeec8d8a) | Jan 14, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [d92542c9e8](https://linux-hardware.org/?probe=d92542c9e8) | Jan 14, 2023 |
| Acer          | AO756                       | Notebook    | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| Dell          | G5 5590                     | Notebook    | [c0bba3f9fd](https://linux-hardware.org/?probe=c0bba3f9fd) | Jan 04, 2023 |
| Dell          | G5 5590                     | Notebook    | [cb89cf0f00](https://linux-hardware.org/?probe=cb89cf0f00) | Jan 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [73de62ce79](https://linux-hardware.org/?probe=73de62ce79) | Jan 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [03ca911bb7](https://linux-hardware.org/?probe=03ca911bb7) | Jan 01, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [13c0ee7f2d](https://linux-hardware.org/?probe=13c0ee7f2d) | Jan 01, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a323cc954e](https://linux-hardware.org/?probe=a323cc954e) | Dec 30, 2022 |
| Toshiba       | Satellite C50D-C            | Notebook    | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c3835ed07f](https://linux-hardware.org/?probe=c3835ed07f) | Dec 20, 2022 |
| Dell          | 0P67HD A00                  | Desktop     | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| MSI           | H81M-E34                    | Desktop     | [a9cc317647](https://linux-hardware.org/?probe=a9cc317647) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1b37803020](https://linux-hardware.org/?probe=1b37803020) | Dec 04, 2022 |
| HP            | 3397                        | Desktop     | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ef9a6b217c](https://linux-hardware.org/?probe=ef9a6b217c) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [f01dec11e4](https://linux-hardware.org/?probe=f01dec11e4) | Nov 21, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| Sony          | VGN-CR120E                  | Notebook    | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [1117e533c3](https://linux-hardware.org/?probe=1117e533c3) | Nov 11, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Dell          | Studio 1558                 | Notebook    | [8b5cb100a8](https://linux-hardware.org/?probe=8b5cb100a8) | Nov 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [e4af6d51f3](https://linux-hardware.org/?probe=e4af6d51f3) | Oct 31, 2022 |
| Samsung       | 760XBE                      | Notebook    | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Samsung       | 760XBE                      | Notebook    | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [7640c7a49f](https://linux-hardware.org/?probe=7640c7a49f) | Oct 20, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| HP            | 15                          | Notebook    | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Dell          | Precision 7520              | Notebook    | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [8774a8312b](https://linux-hardware.org/?probe=8774a8312b) | Sep 13, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [e36022370b](https://linux-hardware.org/?probe=e36022370b) | Sep 08, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| HP            | Pavilion dv5                | Notebook    | [dd2f0b859b](https://linux-hardware.org/?probe=dd2f0b859b) | Aug 24, 2022 |
| ASUSTek       | M4A78-E                     | Desktop     | [76028e78e9](https://linux-hardware.org/?probe=76028e78e9) | Aug 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [e8b519c4de](https://linux-hardware.org/?probe=e8b519c4de) | Aug 18, 2022 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [a5ed221478](https://linux-hardware.org/?probe=a5ed221478) | Aug 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [9655bf78d0](https://linux-hardware.org/?probe=9655bf78d0) | Aug 05, 2022 |
| Google        | Swanky                      | Notebook    | [f54bdd7887](https://linux-hardware.org/?probe=f54bdd7887) | Aug 04, 2022 |
| Google        | Swanky                      | Notebook    | [daac706167](https://linux-hardware.org/?probe=daac706167) | Aug 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [5d5fd15071](https://linux-hardware.org/?probe=5d5fd15071) | Jul 28, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [59d8bb1e10](https://linux-hardware.org/?probe=59d8bb1e10) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [a8bcc56e78](https://linux-hardware.org/?probe=a8bcc56e78) | Jul 26, 2022 |
| ONDA          | H110-MINI V3.00 Ver:3.00    | Desktop     | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| BESSTAR Te... | CB9                         | Mini pc     | [faa42224f0](https://linux-hardware.org/?probe=faa42224f0) | Jul 18, 2022 |
| Dell          | Latitude XT                 | Notebook    | [9d9deeace5](https://linux-hardware.org/?probe=9d9deeace5) | Jul 10, 2022 |
| Dell          | Latitude XT                 | Notebook    | [b0a096fb7d](https://linux-hardware.org/?probe=b0a096fb7d) | Jul 10, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0cdcc2c0e0](https://linux-hardware.org/?probe=0cdcc2c0e0) | Jul 10, 2022 |
| MicroByte     | ezbook                      | Notebook    | [0f08faf963](https://linux-hardware.org/?probe=0f08faf963) | Jul 08, 2022 |
| Dell          | 0M6C7G A00                  | Desktop     | [5eee0db64f](https://linux-hardware.org/?probe=5eee0db64f) | Jul 03, 2022 |
| HP            | 2B0D A01                    | All in one  | [43b3fd0fd4](https://linux-hardware.org/?probe=43b3fd0fd4) | Jul 01, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e048d9df09](https://linux-hardware.org/?probe=e048d9df09) | Jun 17, 2022 |
| MSI           | 3664h                       | Desktop     | [5fbb22c653](https://linux-hardware.org/?probe=5fbb22c653) | Jun 15, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [94abe2c8af](https://linux-hardware.org/?probe=94abe2c8af) | Jun 13, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [3de31234b3](https://linux-hardware.org/?probe=3de31234b3) | Jun 12, 2022 |
| Dell          | 0HV8FN A01                  | Desktop     | [33d201cb1d](https://linux-hardware.org/?probe=33d201cb1d) | Jun 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [d9e8d3957e](https://linux-hardware.org/?probe=d9e8d3957e) | Jun 06, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [20544feb00](https://linux-hardware.org/?probe=20544feb00) | Jun 03, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [73746e5672](https://linux-hardware.org/?probe=73746e5672) | Jun 03, 2022 |
| Fujitsu       | LIFEBOOK E5511              | Notebook    | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | Notebook    | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| INP           | i1000BTS                    | Desktop     | [95da2ada33](https://linux-hardware.org/?probe=95da2ada33) | May 24, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Medion        | Akoya E6415                 | Notebook    | [32545030d4](https://linux-hardware.org/?probe=32545030d4) | May 16, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [c8900ed973](https://linux-hardware.org/?probe=c8900ed973) | May 15, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [8b912c2c4f](https://linux-hardware.org/?probe=8b912c2c4f) | May 15, 2022 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [4d68e6fd8d](https://linux-hardware.org/?probe=4d68e6fd8d) | May 12, 2022 |
| HP            | 3031h                       | Desktop     | [4a57ff5761](https://linux-hardware.org/?probe=4a57ff5761) | May 10, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [86c82d9ca0](https://linux-hardware.org/?probe=86c82d9ca0) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [a55c5c5c9f](https://linux-hardware.org/?probe=a55c5c5c9f) | May 03, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [b2b220b65d](https://linux-hardware.org/?probe=b2b220b65d) | Apr 25, 2022 |
| Dell          | Precision 3561              | Notebook    | [26fa0f202c](https://linux-hardware.org/?probe=26fa0f202c) | Apr 20, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [83ffe21604](https://linux-hardware.org/?probe=83ffe21604) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7a9f6e1de7](https://linux-hardware.org/?probe=7a9f6e1de7) | Apr 13, 2022 |
| Samsung       | R505                        | Notebook    | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| Dell          | Latitude E5400              | Notebook    | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [c640615939](https://linux-hardware.org/?probe=c640615939) | Apr 10, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| Gigabyte      | H470M DS3H                  | Desktop     | [bbfc43c637](https://linux-hardware.org/?probe=bbfc43c637) | Apr 05, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [5f45322780](https://linux-hardware.org/?probe=5f45322780) | Apr 04, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [42cf748563](https://linux-hardware.org/?probe=42cf748563) | Apr 03, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [8340e366fc](https://linux-hardware.org/?probe=8340e366fc) | Mar 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [3a8a0e2c0c](https://linux-hardware.org/?probe=3a8a0e2c0c) | Mar 26, 2022 |
| Dell          | 05KX61 A00                  | Server      | [77d570f7ae](https://linux-hardware.org/?probe=77d570f7ae) | Mar 25, 2022 |
| Dell          | Studio 1558                 | Notebook    | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Dell          | Vostro 3350                 | Notebook    | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| HP            | Pavilion dv7                | Notebook    | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [7bbbcc53c1](https://linux-hardware.org/?probe=7bbbcc53c1) | Mar 14, 2022 |
| Dell          | OptiPlex 980                | Desktop     | [14cf2b23f7](https://linux-hardware.org/?probe=14cf2b23f7) | Mar 14, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [d59f0b152c](https://linux-hardware.org/?probe=d59f0b152c) | Mar 10, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [776d052837](https://linux-hardware.org/?probe=776d052837) | Mar 09, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [6382c70064](https://linux-hardware.org/?probe=6382c70064) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [8e3573295d](https://linux-hardware.org/?probe=8e3573295d) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [d57f5c8ce3](https://linux-hardware.org/?probe=d57f5c8ce3) | Mar 07, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [b18f6804d6](https://linux-hardware.org/?probe=b18f6804d6) | Mar 02, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [43c3e7c4a0](https://linux-hardware.org/?probe=43c3e7c4a0) | Mar 02, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [beeb081772](https://linux-hardware.org/?probe=beeb081772) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| Pegatron      | Narra6                      | Desktop     | [ad9a06f14d](https://linux-hardware.org/?probe=ad9a06f14d) | Feb 25, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| Lenovo        | ThinkPad T460p 20FW000VU... | Notebook    | [9cbb915f78](https://linux-hardware.org/?probe=9cbb915f78) | Feb 18, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [0747de6777](https://linux-hardware.org/?probe=0747de6777) | Feb 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [b6459dbb39](https://linux-hardware.org/?probe=b6459dbb39) | Feb 12, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [e58751112a](https://linux-hardware.org/?probe=e58751112a) | Feb 11, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| Acer          | Aspire 7735                 | Notebook    | [38d97cd9da](https://linux-hardware.org/?probe=38d97cd9da) | Feb 06, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [451c540217](https://linux-hardware.org/?probe=451c540217) | Feb 05, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8f2181125e](https://linux-hardware.org/?probe=8f2181125e) | Jan 27, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [fab2b2828e](https://linux-hardware.org/?probe=fab2b2828e) | Jan 26, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [8062682731](https://linux-hardware.org/?probe=8062682731) | Jan 25, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [55067d6afe](https://linux-hardware.org/?probe=55067d6afe) | Jan 21, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | Desktop     | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | Desktop     | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | Desktop     | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3d19d1297](https://linux-hardware.org/?probe=c3d19d1297) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | Desktop     | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [3c8e26636b](https://linux-hardware.org/?probe=3c8e26636b) | Jan 15, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d2fa7ede7](https://linux-hardware.org/?probe=9d2fa7ede7) | Jan 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2fbac2ebd5](https://linux-hardware.org/?probe=2fbac2ebd5) | Jan 12, 2022 |
| Dell          | Latitude E5400              | Notebook    | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [4103077e59](https://linux-hardware.org/?probe=4103077e59) | Jan 08, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [faef08af10](https://linux-hardware.org/?probe=faef08af10) | Jan 06, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [f3838abaaf](https://linux-hardware.org/?probe=f3838abaaf) | Jan 04, 2022 |
| HP            | ProLiant DL120 G7           | Server      | [70c39995ec](https://linux-hardware.org/?probe=70c39995ec) | Jan 03, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| Gigabyte      | MZ71-CE0-00 01000100        | Server      | [6d2ee30f72](https://linux-hardware.org/?probe=6d2ee30f72) | Dec 31, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [82163f143b](https://linux-hardware.org/?probe=82163f143b) | Dec 29, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | Notebook    | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [1fbef2b76c](https://linux-hardware.org/?probe=1fbef2b76c) | Dec 23, 2021 |
| Lenovo        | G580 2189                   | Notebook    | [843f8c04fe](https://linux-hardware.org/?probe=843f8c04fe) | Dec 21, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| AZW           | GK mini                     | Mini pc     | [bb4770d627](https://linux-hardware.org/?probe=bb4770d627) | Dec 17, 2021 |
| HP            | ENVY Notebook               | Notebook    | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| Acer          | Aspire ES1-523              | Notebook    | [66a8186276](https://linux-hardware.org/?probe=66a8186276) | Dec 15, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [3bd9548bab](https://linux-hardware.org/?probe=3bd9548bab) | Dec 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| MSI           | H61M-S20                    | Desktop     | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [2cd39490da](https://linux-hardware.org/?probe=2cd39490da) | Dec 02, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [50acb69e6e](https://linux-hardware.org/?probe=50acb69e6e) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Dell          | Latitude E6400              | Notebook    | [170f397883](https://linux-hardware.org/?probe=170f397883) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [3b06bfa748](https://linux-hardware.org/?probe=3b06bfa748) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| HP            | 3646h                       | Desktop     | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | Desktop     | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [9b13286f92](https://linux-hardware.org/?probe=9b13286f92) | Nov 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3d2583b1f1](https://linux-hardware.org/?probe=3d2583b1f1) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| Dell          | 0T656F A01                  | Desktop     | [06f4633f1b](https://linux-hardware.org/?probe=06f4633f1b) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [8b5c3b008f](https://linux-hardware.org/?probe=8b5c3b008f) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bf8ac4dc12](https://linux-hardware.org/?probe=bf8ac4dc12) | Nov 24, 2021 |
| Dell          | Precision 5560              | Notebook    | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [b8f5329824](https://linux-hardware.org/?probe=b8f5329824) | Nov 22, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [da444f9b8f](https://linux-hardware.org/?probe=da444f9b8f) | Nov 22, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [a13103a9ad](https://linux-hardware.org/?probe=a13103a9ad) | Nov 20, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [63f392ea8b](https://linux-hardware.org/?probe=63f392ea8b) | Nov 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [162531d482](https://linux-hardware.org/?probe=162531d482) | Nov 16, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2cdd151d75](https://linux-hardware.org/?probe=2cdd151d75) | Nov 14, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Notebook    | [e881f41269](https://linux-hardware.org/?probe=e881f41269) | Nov 14, 2021 |
| AMI           | Unknown                     | Notebook    | [d1cd5b09e1](https://linux-hardware.org/?probe=d1cd5b09e1) | Nov 12, 2021 |
| Toshiba       | Satellite C665              | Notebook    | [a136cdd51d](https://linux-hardware.org/?probe=a136cdd51d) | Nov 11, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [61bfe5dfa7](https://linux-hardware.org/?probe=61bfe5dfa7) | Nov 11, 2021 |
| HP            | ZBook 15                    | Notebook    | [835fb0e921](https://linux-hardware.org/?probe=835fb0e921) | Nov 10, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [dd8a96b615](https://linux-hardware.org/?probe=dd8a96b615) | Nov 09, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [89aff3881c](https://linux-hardware.org/?probe=89aff3881c) | Nov 09, 2021 |
| ASUSTek       | A55BM-E                     | Desktop     | [fd25737c58](https://linux-hardware.org/?probe=fd25737c58) | Nov 09, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [c0b1971c18](https://linux-hardware.org/?probe=c0b1971c18) | Nov 09, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| Rockchip      | Unknown                     | Soc         | [de559ac6d9](https://linux-hardware.org/?probe=de559ac6d9) | Nov 08, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e21897758d](https://linux-hardware.org/?probe=e21897758d) | Nov 07, 2021 |
| GPD           | P2 MAX                      | Notebook    | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [05e3caa05c](https://linux-hardware.org/?probe=05e3caa05c) | Nov 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [60ffb9d428](https://linux-hardware.org/?probe=60ffb9d428) | Oct 31, 2021 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [6e1fbe4dde](https://linux-hardware.org/?probe=6e1fbe4dde) | Oct 27, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Dell          | Precision 7520              | Notebook    | [83df635945](https://linux-hardware.org/?probe=83df635945) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [4946a6a02c](https://linux-hardware.org/?probe=4946a6a02c) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [0ad429cea5](https://linux-hardware.org/?probe=0ad429cea5) | Oct 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [cd2454732b](https://linux-hardware.org/?probe=cd2454732b) | Oct 25, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [4ba408d68c](https://linux-hardware.org/?probe=4ba408d68c) | Oct 23, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Rockchip      | Unknown                     | Soc         | [e7c44d5f41](https://linux-hardware.org/?probe=e7c44d5f41) | Oct 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [27b0a66ceb](https://linux-hardware.org/?probe=27b0a66ceb) | Oct 20, 2021 |
| Lenovo        | ThinkPad L512 2598A59       | Notebook    | [0bc832bd49](https://linux-hardware.org/?probe=0bc832bd49) | Oct 19, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [2bc2b5c1d6](https://linux-hardware.org/?probe=2bc2b5c1d6) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [b566b7f862](https://linux-hardware.org/?probe=b566b7f862) | Oct 13, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [26453872b1](https://linux-hardware.org/?probe=26453872b1) | Oct 12, 2021 |
| ASUSTek       | N43SL                       | Notebook    | [c5adc8860e](https://linux-hardware.org/?probe=c5adc8860e) | Oct 09, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [219e5cd0d5](https://linux-hardware.org/?probe=219e5cd0d5) | Oct 04, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [f0ff9a911e](https://linux-hardware.org/?probe=f0ff9a911e) | Oct 03, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5f6c245dc5](https://linux-hardware.org/?probe=5f6c245dc5) | Sep 28, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [5422d3bf1d](https://linux-hardware.org/?probe=5422d3bf1d) | Sep 27, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [060da3d3ab](https://linux-hardware.org/?probe=060da3d3ab) | Sep 26, 2021 |
| HP            | 8265                        | Desktop     | [f840aed42d](https://linux-hardware.org/?probe=f840aed42d) | Sep 21, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| HP            | 3397                        | Desktop     | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [3c40bbda61](https://linux-hardware.org/?probe=3c40bbda61) | Sep 18, 2021 |
| ASRock        | H110M-STX                   | Desktop     | [6bb90d3b07](https://linux-hardware.org/?probe=6bb90d3b07) | Sep 16, 2021 |
| Teclast       | F15S                        | Notebook    | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | Notebook    | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | Notebook    | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | Notebook    | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [14109edfc9](https://linux-hardware.org/?probe=14109edfc9) | Sep 07, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [cb82d03efe](https://linux-hardware.org/?probe=cb82d03efe) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Acer          | Spin SP111-33               | Convertible | [2a5ddf7be8](https://linux-hardware.org/?probe=2a5ddf7be8) | Sep 05, 2021 |
| HP            | 3396                        | Desktop     | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [c594736488](https://linux-hardware.org/?probe=c594736488) | Aug 30, 2021 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [16250b0c12](https://linux-hardware.org/?probe=16250b0c12) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [41e440c2e5](https://linux-hardware.org/?probe=41e440c2e5) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e086d2eb61](https://linux-hardware.org/?probe=e086d2eb61) | Aug 29, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| Packard Be... | EasyNote SL65               | Notebook    | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | Notebook    | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| Acer          | Extensa 5630                | Notebook    | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| ASRock        | M3A785GMH/128M              | Desktop     | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| HP            | Notebook                    | Notebook    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| MSI           | X79A-GD45                   | Desktop     | [c5b78e1a01](https://linux-hardware.org/?probe=c5b78e1a01) | Aug 13, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [bbfbd42562](https://linux-hardware.org/?probe=bbfbd42562) | Aug 07, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | Notebook    | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | Notebook    | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASRock        | Q1900M                      | Desktop     | [700f4a0ca1](https://linux-hardware.org/?probe=700f4a0ca1) | Aug 02, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [e706b18dd8](https://linux-hardware.org/?probe=e706b18dd8) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | Notebook    | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [6dcb19e468](https://linux-hardware.org/?probe=6dcb19e468) | Jul 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [647fe69592](https://linux-hardware.org/?probe=647fe69592) | Jul 22, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| MSI           | H61M-E33                    | Desktop     | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
| Dell          | Studio 1558                 | Notebook    | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | Notebook    | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [d49086311b](https://linux-hardware.org/?probe=d49086311b) | Jul 12, 2021 |
| Unknown       | TB-4000                     | Desktop     | [fb3e1984b0](https://linux-hardware.org/?probe=fb3e1984b0) | Jul 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [ae14beb6fd](https://linux-hardware.org/?probe=ae14beb6fd) | Jul 09, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [ebd157141b](https://linux-hardware.org/?probe=ebd157141b) | Jul 08, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [4b2c3ea073](https://linux-hardware.org/?probe=4b2c3ea073) | Jul 07, 2021 |
| ASUSTek       | Z170-AR                     | Desktop     | [37343856a5](https://linux-hardware.org/?probe=37343856a5) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | Notebook    | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [9bb3c8dbe9](https://linux-hardware.org/?probe=9bb3c8dbe9) | Jul 02, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [55bdc0f976](https://linux-hardware.org/?probe=55bdc0f976) | Jun 28, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | Pavilion dv7                | Notebook    | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [7fba4b1b78](https://linux-hardware.org/?probe=7fba4b1b78) | Jun 23, 2021 |
| Dell          | Latitude E6400              | Notebook    | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| HP            | 1495                        | Desktop     | [03ab704550](https://linux-hardware.org/?probe=03ab704550) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [c71b41c7a8](https://linux-hardware.org/?probe=c71b41c7a8) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [f39e5005bd](https://linux-hardware.org/?probe=f39e5005bd) | Jun 20, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d41809b4c9](https://linux-hardware.org/?probe=d41809b4c9) | Jun 19, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [b10313d89f](https://linux-hardware.org/?probe=b10313d89f) | Jun 17, 2021 |
| eMachines     | EL1352                      | Desktop     | [f175ae71f2](https://linux-hardware.org/?probe=f175ae71f2) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [0616fdb086](https://linux-hardware.org/?probe=0616fdb086) | Jun 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [3d47d96665](https://linux-hardware.org/?probe=3d47d96665) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c9bea47caa](https://linux-hardware.org/?probe=c9bea47caa) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c9c757474a](https://linux-hardware.org/?probe=c9c757474a) | Jun 12, 2021 |
| Dell          | Latitude E6510              | Notebook    | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23dc47130c](https://linux-hardware.org/?probe=23dc47130c) | Jun 10, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [1ab4ff25ab](https://linux-hardware.org/?probe=1ab4ff25ab) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b5aa561890](https://linux-hardware.org/?probe=b5aa561890) | Jun 05, 2021 |
| ASUSTek       | K73SJ                       | Notebook    | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | Notebook    | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [d732611ebb](https://linux-hardware.org/?probe=d732611ebb) | Jun 02, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [913ea68973](https://linux-hardware.org/?probe=913ea68973) | May 31, 2021 |
| Inventec      | Z CLASS A02                 | Desktop     | [7fc4815cbd](https://linux-hardware.org/?probe=7fc4815cbd) | May 29, 2021 |
| HP            | Pavilion                    | Notebook    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| Dell          | Precision M4800             | Notebook    | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | Notebook    | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [6b9dbebe2f](https://linux-hardware.org/?probe=6b9dbebe2f) | May 18, 2021 |
| Acer          | C-AXC-605                   | Desktop     | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [c56840df98](https://linux-hardware.org/?probe=c56840df98) | May 17, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f1592b156b](https://linux-hardware.org/?probe=f1592b156b) | May 16, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | Notebook    | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | Notebook    | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Dell          | G7 7588                     | Notebook    | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| Cube          | i18-L                       | Notebook    | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| HP            | Pavilion                    | Notebook    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [9ff1a95290](https://linux-hardware.org/?probe=9ff1a95290) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Intel         | S5520HC E26045-407          | Server      | [61dfd26e01](https://linux-hardware.org/?probe=61dfd26e01) | Apr 24, 2021 |
| Intel         | S5520HC E26045-407          | Server      | [28bf977c65](https://linux-hardware.org/?probe=28bf977c65) | Apr 24, 2021 |
| ONE-NETBOO... | A1                          | Notebook    | [86c38b0aca](https://linux-hardware.org/?probe=86c38b0aca) | Apr 23, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [289a9d70d9](https://linux-hardware.org/?probe=289a9d70d9) | Apr 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [d5310b7f74](https://linux-hardware.org/?probe=d5310b7f74) | Apr 15, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [fb0db0afbd](https://linux-hardware.org/?probe=fb0db0afbd) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [236be7c7e7](https://linux-hardware.org/?probe=236be7c7e7) | Apr 12, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bf634bb665](https://linux-hardware.org/?probe=bf634bb665) | Apr 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c2aed97877](https://linux-hardware.org/?probe=c2aed97877) | Apr 08, 2021 |
| HP            | 15                          | Notebook    | [acc9ccddfa](https://linux-hardware.org/?probe=acc9ccddfa) | Apr 08, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [946c22503a](https://linux-hardware.org/?probe=946c22503a) | Apr 07, 2021 |
| HP            | ProBook 4530s               | Notebook    | [12a7784eb4](https://linux-hardware.org/?probe=12a7784eb4) | Apr 06, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1d9693a3dc](https://linux-hardware.org/?probe=1d9693a3dc) | Apr 05, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [16218d28da](https://linux-hardware.org/?probe=16218d28da) | Apr 04, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fa8acecaa2](https://linux-hardware.org/?probe=fa8acecaa2) | Apr 01, 2021 |
| HP            | 3397                        | Desktop     | [e5812883ce](https://linux-hardware.org/?probe=e5812883ce) | Mar 31, 2021 |
| Dell          | Latitude E7250              | Notebook    | [d88e8eb416](https://linux-hardware.org/?probe=d88e8eb416) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| Dell          | Latitude 7310               | Notebook    | [9f4c2f64a5](https://linux-hardware.org/?probe=9f4c2f64a5) | Mar 30, 2021 |
| Dell          | Latitude E7250              | Notebook    | [d1716d96f2](https://linux-hardware.org/?probe=d1716d96f2) | Mar 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [dc5e67af5a](https://linux-hardware.org/?probe=dc5e67af5a) | Mar 27, 2021 |
| ASRock        | H310M-STX                   | Desktop     | [419277b830](https://linux-hardware.org/?probe=419277b830) | Mar 26, 2021 |
| Acer          | Aspire 4740                 | Notebook    | [3551944dd9](https://linux-hardware.org/?probe=3551944dd9) | Mar 25, 2021 |
| Supermicro    | X10SRM-TFA                  | Server      | [3fc4f3458f](https://linux-hardware.org/?probe=3fc4f3458f) | Mar 24, 2021 |
| Samsung       | 760XBE                      | Notebook    | [3cacabef7b](https://linux-hardware.org/?probe=3cacabef7b) | Mar 23, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [92bcacad15](https://linux-hardware.org/?probe=92bcacad15) | Mar 22, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e9b0291347](https://linux-hardware.org/?probe=e9b0291347) | Mar 21, 2021 |
| Samsung       | 760XBE                      | Notebook    | [26e28d0645](https://linux-hardware.org/?probe=26e28d0645) | Mar 21, 2021 |
| HP            | 1497                        | Desktop     | [d35a7eef80](https://linux-hardware.org/?probe=d35a7eef80) | Mar 19, 2021 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [e4faf817fd](https://linux-hardware.org/?probe=e4faf817fd) | Mar 19, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [cc01498ee9](https://linux-hardware.org/?probe=cc01498ee9) | Mar 18, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9210657e45](https://linux-hardware.org/?probe=9210657e45) | Mar 17, 2021 |
| ASRock        | 960GM-S3 FX                 | Desktop     | [5784a74c50](https://linux-hardware.org/?probe=5784a74c50) | Mar 17, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [f58ddcc3f4](https://linux-hardware.org/?probe=f58ddcc3f4) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [1919b6a57f](https://linux-hardware.org/?probe=1919b6a57f) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [2b8f8e4cec](https://linux-hardware.org/?probe=2b8f8e4cec) | Mar 14, 2021 |
| MSI           | B85M-P33                    | Desktop     | [e7d2bb8e63](https://linux-hardware.org/?probe=e7d2bb8e63) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [957f68f2b7](https://linux-hardware.org/?probe=957f68f2b7) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [839bc4873c](https://linux-hardware.org/?probe=839bc4873c) | Mar 08, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [b5cf5849a1](https://linux-hardware.org/?probe=b5cf5849a1) | Mar 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cc361e0dbf](https://linux-hardware.org/?probe=cc361e0dbf) | Mar 04, 2021 |
| HP            | 2B2C                        | Desktop     | [20c11c9bbc](https://linux-hardware.org/?probe=20c11c9bbc) | Mar 04, 2021 |
| Medion        | B460H6-EM                   | Desktop     | [2ab61e6080](https://linux-hardware.org/?probe=2ab61e6080) | Mar 03, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [0286dc8c95](https://linux-hardware.org/?probe=0286dc8c95) | Mar 02, 2021 |
| HP            | Pavilion g7                 | Notebook    | [41d55a3dd7](https://linux-hardware.org/?probe=41d55a3dd7) | Feb 26, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [53ada57eb3](https://linux-hardware.org/?probe=53ada57eb3) | Feb 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| Unknown       | XH61X000.100                | Desktop     | [029de8905d](https://linux-hardware.org/?probe=029de8905d) | Feb 17, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [5bd6c548d2](https://linux-hardware.org/?probe=5bd6c548d2) | Feb 15, 2021 |
| JINGSHA       | Unknown                     | Desktop     | [01ab676e78](https://linux-hardware.org/?probe=01ab676e78) | Feb 15, 2021 |
| Positivo      | N8X0EK1                     | Notebook    | [c6ac8d6eca](https://linux-hardware.org/?probe=c6ac8d6eca) | Feb 15, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [87f43dfecd](https://linux-hardware.org/?probe=87f43dfecd) | Feb 12, 2021 |
| Dell          | Latitude E6500              | Notebook    | [75d199bcfd](https://linux-hardware.org/?probe=75d199bcfd) | Feb 12, 2021 |
| Dell          | Studio 1747                 | Notebook    | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [bd107eb4ae](https://linux-hardware.org/?probe=bd107eb4ae) | Feb 10, 2021 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [fa48450d71](https://linux-hardware.org/?probe=fa48450d71) | Feb 09, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [952ca96633](https://linux-hardware.org/?probe=952ca96633) | Feb 09, 2021 |
| Notebook      | W310CZ/CZ-T                 | Notebook    | [2b60fc9e91](https://linux-hardware.org/?probe=2b60fc9e91) | Feb 09, 2021 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [bbff698cb8](https://linux-hardware.org/?probe=bbff698cb8) | Feb 09, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [394af8312b](https://linux-hardware.org/?probe=394af8312b) | Feb 07, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [0e61287ad7](https://linux-hardware.org/?probe=0e61287ad7) | Feb 07, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ad3df90a2e](https://linux-hardware.org/?probe=ad3df90a2e) | Feb 06, 2021 |
| Gateway       | DX4885                      | Desktop     | [48628b0b95](https://linux-hardware.org/?probe=48628b0b95) | Feb 03, 2021 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [e39393dcdb](https://linux-hardware.org/?probe=e39393dcdb) | Feb 02, 2021 |
| Intel         | H61M-S1                     | Desktop     | [38a03ee5be](https://linux-hardware.org/?probe=38a03ee5be) | Jan 31, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [73b3295031](https://linux-hardware.org/?probe=73b3295031) | Jan 29, 2021 |
| Dell          | G7 7588                     | Notebook    | [ae6d47978a](https://linux-hardware.org/?probe=ae6d47978a) | Jan 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [20d082d72c](https://linux-hardware.org/?probe=20d082d72c) | Jan 26, 2021 |
| ASUSTek       | LITHIUM                     | Desktop     | [e2c8ad85fb](https://linux-hardware.org/?probe=e2c8ad85fb) | Jan 24, 2021 |
| ASUSTek       | LITHIUM                     | Desktop     | [3f3f25d596](https://linux-hardware.org/?probe=3f3f25d596) | Jan 24, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [4695d8c639](https://linux-hardware.org/?probe=4695d8c639) | Jan 24, 2021 |
| ASUSTek       | P5N-D                       | Desktop     | [cac7f8ae52](https://linux-hardware.org/?probe=cac7f8ae52) | Jan 23, 2021 |
| ASUSTek       | P5N-D                       | Desktop     | [b637c75d21](https://linux-hardware.org/?probe=b637c75d21) | Jan 23, 2021 |
| Acer          | Spin SP111-33               | Convertible | [0a09d00b74](https://linux-hardware.org/?probe=0a09d00b74) | Jan 23, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | Notebook    | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [f2e3b573f5](https://linux-hardware.org/?probe=f2e3b573f5) | Jan 16, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [e8b3cf2cbd](https://linux-hardware.org/?probe=e8b3cf2cbd) | Jan 14, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [8117aff9b0](https://linux-hardware.org/?probe=8117aff9b0) | Jan 14, 2021 |
| Medion        | X682X                       | Notebook    | [bf7dbceaa3](https://linux-hardware.org/?probe=bf7dbceaa3) | Jan 13, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [5e5ca98e54](https://linux-hardware.org/?probe=5e5ca98e54) | Jan 13, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [86c7eb6c5b](https://linux-hardware.org/?probe=86c7eb6c5b) | Jan 11, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [474542bd76](https://linux-hardware.org/?probe=474542bd76) | Jan 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7faa994c80](https://linux-hardware.org/?probe=7faa994c80) | Jan 10, 2021 |
| ASUSTek       | P7P55 LX                    | Desktop     | [d13d4667c3](https://linux-hardware.org/?probe=d13d4667c3) | Jan 09, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [7b2ec8b1a2](https://linux-hardware.org/?probe=7b2ec8b1a2) | Jan 08, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [1b3b03be98](https://linux-hardware.org/?probe=1b3b03be98) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [4f385a65db](https://linux-hardware.org/?probe=4f385a65db) | Jan 03, 2021 |
| Samsung       | SR58P                       | Notebook    | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| MSI           | H87-G43                     | Desktop     | [8b1363882c](https://linux-hardware.org/?probe=8b1363882c) | Jan 03, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1483935c23](https://linux-hardware.org/?probe=1483935c23) | Jan 02, 2021 |
| Acer          | Aspire E1-532P              | Notebook    | [a1f1287741](https://linux-hardware.org/?probe=a1f1287741) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [30041ef295](https://linux-hardware.org/?probe=30041ef295) | Jan 01, 2021 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [708c6c3ab6](https://linux-hardware.org/?probe=708c6c3ab6) | Dec 28, 2020 |
| HP            | Notebook                    | Notebook    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | Notebook    | [cfa92bb7f3](https://linux-hardware.org/?probe=cfa92bb7f3) | Dec 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e50d894b93](https://linux-hardware.org/?probe=e50d894b93) | Dec 28, 2020 |
| ASUSTek       | X302LA                      | Notebook    | [f5dde37fb9](https://linux-hardware.org/?probe=f5dde37fb9) | Dec 26, 2020 |
| Gigabyte      | Z97-HD3                     | Desktop     | [417a2cbe50](https://linux-hardware.org/?probe=417a2cbe50) | Dec 26, 2020 |
| ASUSTek       | X302LA                      | Notebook    | [a35e9f4b28](https://linux-hardware.org/?probe=a35e9f4b28) | Dec 25, 2020 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [8d897ef7a8](https://linux-hardware.org/?probe=8d897ef7a8) | Dec 24, 2020 |
| Star Labs     | LabTop                      | Notebook    | [b8c8467e92](https://linux-hardware.org/?probe=b8c8467e92) | Dec 20, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [46e2c41ee6](https://linux-hardware.org/?probe=46e2c41ee6) | Dec 17, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9ad04d0568](https://linux-hardware.org/?probe=9ad04d0568) | Dec 16, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e9fb6116b3](https://linux-hardware.org/?probe=e9fb6116b3) | Dec 14, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| HP            | 82A2                        | Desktop     | [8b443d9da5](https://linux-hardware.org/?probe=8b443d9da5) | Dec 12, 2020 |
| HP            | 82A2                        | Desktop     | [58faddeba3](https://linux-hardware.org/?probe=58faddeba3) | Dec 12, 2020 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [e1d03e259e](https://linux-hardware.org/?probe=e1d03e259e) | Dec 09, 2020 |
| Toshiba       | Satellite Pro L500          | Notebook    | [d01d9e0d34](https://linux-hardware.org/?probe=d01d9e0d34) | Dec 08, 2020 |
| Dell          | Inspiron 3520               | Notebook    | [be6f5d9f85](https://linux-hardware.org/?probe=be6f5d9f85) | Dec 07, 2020 |
| Gigabyte      | EP45T-EXTREME               | Desktop     | [9320edd724](https://linux-hardware.org/?probe=9320edd724) | Dec 07, 2020 |
| Dell          | Latitude D630               | Notebook    | [475177f3da](https://linux-hardware.org/?probe=475177f3da) | Dec 07, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [5862508036](https://linux-hardware.org/?probe=5862508036) | Dec 06, 2020 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [eba95d11b5](https://linux-hardware.org/?probe=eba95d11b5) | Dec 04, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2f04deaf4e](https://linux-hardware.org/?probe=2f04deaf4e) | Dec 03, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [ee0aa7b52f](https://linux-hardware.org/?probe=ee0aa7b52f) | Dec 02, 2020 |
| Dell          | Precision 7710              | Notebook    | [f017e7a0d2](https://linux-hardware.org/?probe=f017e7a0d2) | Nov 30, 2020 |
| Acer          | Aspire E5-523               | Notebook    | [cfd9403111](https://linux-hardware.org/?probe=cfd9403111) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Dell          | Latitude E6400              | Notebook    | [a39e2e7fa3](https://linux-hardware.org/?probe=a39e2e7fa3) | Nov 27, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [49224bd7f8](https://linux-hardware.org/?probe=49224bd7f8) | Nov 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [833a22d4ee](https://linux-hardware.org/?probe=833a22d4ee) | Nov 20, 2020 |
| HP            | EliteBook 830 G6            | Notebook    | [c47a2f5f86](https://linux-hardware.org/?probe=c47a2f5f86) | Nov 18, 2020 |
| ASUSTek       | WS C246M PRO Series         | Desktop     | [502bd89093](https://linux-hardware.org/?probe=502bd89093) | Nov 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [08c8440950](https://linux-hardware.org/?probe=08c8440950) | Nov 17, 2020 |
| ASUSTek       | WS C246M PRO Series         | Desktop     | [dc20d9cf64](https://linux-hardware.org/?probe=dc20d9cf64) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | Notebook    | [968f302807](https://linux-hardware.org/?probe=968f302807) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | Notebook    | [2a9231cde8](https://linux-hardware.org/?probe=2a9231cde8) | Nov 17, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [b8e7eedfed](https://linux-hardware.org/?probe=b8e7eedfed) | Nov 17, 2020 |
| Dell          | Latitude E6420              | Notebook    | [3452613a4c](https://linux-hardware.org/?probe=3452613a4c) | Nov 16, 2020 |
| Dell          | 0WG864                      | Desktop     | [1c2384097b](https://linux-hardware.org/?probe=1c2384097b) | Nov 15, 2020 |
| HP            | 1790                        | Desktop     | [02138cec8b](https://linux-hardware.org/?probe=02138cec8b) | Nov 08, 2020 |
| HP            | 1905                        | Desktop     | [6f20f6aa7d](https://linux-hardware.org/?probe=6f20f6aa7d) | Nov 08, 2020 |
| Intel         | SLIMBOOK                    | Desktop     | [2250e4a10f](https://linux-hardware.org/?probe=2250e4a10f) | Nov 07, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | 3397                        | Desktop     | [17188b10a3](https://linux-hardware.org/?probe=17188b10a3) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [659c1c8745](https://linux-hardware.org/?probe=659c1c8745) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [248ce84271](https://linux-hardware.org/?probe=248ce84271) | Nov 05, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [c30e84eeae](https://linux-hardware.org/?probe=c30e84eeae) | Nov 04, 2020 |
| Dell          | Latitude E6420              | Notebook    | [6cdd815251](https://linux-hardware.org/?probe=6cdd815251) | Nov 04, 2020 |
| Dell          | Latitude E6420              | Notebook    | [10d44f2853](https://linux-hardware.org/?probe=10d44f2853) | Nov 04, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [686d0b8c4f](https://linux-hardware.org/?probe=686d0b8c4f) | Nov 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [39ba29b6a3](https://linux-hardware.org/?probe=39ba29b6a3) | Nov 02, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4f36ffb293](https://linux-hardware.org/?probe=4f36ffb293) | Nov 01, 2020 |
| Supermicro    | X10SAE                      | Server      | [ef95821afc](https://linux-hardware.org/?probe=ef95821afc) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [d9a9dae79a](https://linux-hardware.org/?probe=d9a9dae79a) | Oct 31, 2020 |
| Lenovo        | ThinkCentre M58p 6234DJ1    | Desktop     | [69bc4fbb1b](https://linux-hardware.org/?probe=69bc4fbb1b) | Oct 30, 2020 |
| HP            | 1493                        | Desktop     | [34134cab7f](https://linux-hardware.org/?probe=34134cab7f) | Oct 30, 2020 |
| HP            | 1493                        | Desktop     | [dd1964d532](https://linux-hardware.org/?probe=dd1964d532) | Oct 30, 2020 |
| Lenovo        | ThinkPad E520 1143B5G       | Notebook    | [146fc730d7](https://linux-hardware.org/?probe=146fc730d7) | Oct 29, 2020 |
| MSI           | GE72 7RE                    | Notebook    | [f75b251f96](https://linux-hardware.org/?probe=f75b251f96) | Oct 29, 2020 |
| HP            | 1497                        | Desktop     | [1d068e5c77](https://linux-hardware.org/?probe=1d068e5c77) | Oct 28, 2020 |
| HP            | 3047h                       | Desktop     | [4f58775069](https://linux-hardware.org/?probe=4f58775069) | Oct 28, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [a13afb5c54](https://linux-hardware.org/?probe=a13afb5c54) | Oct 27, 2020 |
| Acer          | Aspire 5715Z                | Notebook    | [a2fca6b9da](https://linux-hardware.org/?probe=a2fca6b9da) | Oct 26, 2020 |
| Lenovo        | V570 HuronRiver Platform    | Notebook    | [62082c183e](https://linux-hardware.org/?probe=62082c183e) | Oct 26, 2020 |
| ASUSTek       | X751LK                      | Notebook    | [0dad6a22c5](https://linux-hardware.org/?probe=0dad6a22c5) | Oct 26, 2020 |
| HP            | Pavilion dv7                | Notebook    | [59e2fce913](https://linux-hardware.org/?probe=59e2fce913) | Oct 26, 2020 |
| Dell          | Precision M4800             | Notebook    | [2f91204b5e](https://linux-hardware.org/?probe=2f91204b5e) | Oct 26, 2020 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [dd929b231e](https://linux-hardware.org/?probe=dd929b231e) | Oct 26, 2020 |
| ASRock        | G31M-GS                     | Desktop     | [0a9aa8dcd2](https://linux-hardware.org/?probe=0a9aa8dcd2) | Oct 26, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [fd598f0888](https://linux-hardware.org/?probe=fd598f0888) | Oct 25, 2020 |
| Biostar       | A320MH                      | Desktop     | [8c1edce824](https://linux-hardware.org/?probe=8c1edce824) | Oct 24, 2020 |
| Dell          | 0V6XGW A00                  | Desktop     | [1518ff90f9](https://linux-hardware.org/?probe=1518ff90f9) | Oct 24, 2020 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [ab60c752a9](https://linux-hardware.org/?probe=ab60c752a9) | Oct 23, 2020 |
| HP            | 3047h                       | Desktop     | [ecba048272](https://linux-hardware.org/?probe=ecba048272) | Oct 21, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [658b7105e1](https://linux-hardware.org/?probe=658b7105e1) | Oct 21, 2020 |
| Dell          | G3 3590                     | Notebook    | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| HP            | 3047h                       | Desktop     | [4c9083177a](https://linux-hardware.org/?probe=4c9083177a) | Oct 21, 2020 |
| HP            | 3047h                       | Desktop     | [67e7807767](https://linux-hardware.org/?probe=67e7807767) | Oct 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | Notebook    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| HP            | 3047h                       | Desktop     | [4dd1cde645](https://linux-hardware.org/?probe=4dd1cde645) | Oct 20, 2020 |
| Dell          | Latitude E6430              | Notebook    | [67b44ea2b4](https://linux-hardware.org/?probe=67b44ea2b4) | Oct 20, 2020 |
| HP            | 3047h                       | Desktop     | [d84da1ea3e](https://linux-hardware.org/?probe=d84da1ea3e) | Oct 20, 2020 |
| HP            | 3047h                       | Desktop     | [134da552c2](https://linux-hardware.org/?probe=134da552c2) | Oct 20, 2020 |
| HP            | 304Ah                       | Desktop     | [3163a2892d](https://linux-hardware.org/?probe=3163a2892d) | Oct 19, 2020 |
| HP            | 3397                        | Desktop     | [8bdef2c49c](https://linux-hardware.org/?probe=8bdef2c49c) | Oct 19, 2020 |
| HP            | Compaq 6730s                | Notebook    | [b8d5fd5eea](https://linux-hardware.org/?probe=b8d5fd5eea) | Oct 19, 2020 |
| HP            | Notebook                    | Notebook    | [669e2e8ce6](https://linux-hardware.org/?probe=669e2e8ce6) | Oct 19, 2020 |
| Lenovo        | G50-80 80R0                 | Notebook    | [51ec4152a2](https://linux-hardware.org/?probe=51ec4152a2) | Oct 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e5aa6a33a6](https://linux-hardware.org/?probe=e5aa6a33a6) | Oct 18, 2020 |
| HP            | 3397                        | Desktop     | [5a6fac5a0f](https://linux-hardware.org/?probe=5a6fac5a0f) | Oct 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c45c0eb7e4](https://linux-hardware.org/?probe=c45c0eb7e4) | Oct 16, 2020 |
| HP            | ProBook 4430s               | Notebook    | [c816b204bf](https://linux-hardware.org/?probe=c816b204bf) | Oct 15, 2020 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2c4fc7773a](https://linux-hardware.org/?probe=2c4fc7773a) | Oct 14, 2020 |
| Lenovo        | ThinkPad X270 20HN0013MX    | Notebook    | [3dbb81e06d](https://linux-hardware.org/?probe=3dbb81e06d) | Oct 14, 2020 |
| Dell          | 042P49 A01                  | Desktop     | [44c14427a0](https://linux-hardware.org/?probe=44c14427a0) | Oct 13, 2020 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d386e709dc](https://linux-hardware.org/?probe=d386e709dc) | Oct 12, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a489f1cb59](https://linux-hardware.org/?probe=a489f1cb59) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [097db248db](https://linux-hardware.org/?probe=097db248db) | Oct 12, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [72e115769d](https://linux-hardware.org/?probe=72e115769d) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [41141f049e](https://linux-hardware.org/?probe=41141f049e) | Oct 11, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2c0322f113](https://linux-hardware.org/?probe=2c0322f113) | Oct 10, 2020 |
| Dell          | 0FR6WH A01                  | Desktop     | [2776ae6a1a](https://linux-hardware.org/?probe=2776ae6a1a) | Oct 09, 2020 |
| Dell          | 0T656F A01                  | Desktop     | [f44db9c73a](https://linux-hardware.org/?probe=f44db9c73a) | Oct 09, 2020 |
| Pegatron      | 2A84h                       | Desktop     | [a8d97c37b7](https://linux-hardware.org/?probe=a8d97c37b7) | Oct 08, 2020 |
| Dell          | 0HN7XN A00                  | Desktop     | [885b19f22a](https://linux-hardware.org/?probe=885b19f22a) | Oct 08, 2020 |
| Dell          | Latitude E6420              | Notebook    | [1e2a1974f2](https://linux-hardware.org/?probe=1e2a1974f2) | Oct 08, 2020 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [01948526e2](https://linux-hardware.org/?probe=01948526e2) | Oct 08, 2020 |
| Acer          | Aspire 5715Z                | Notebook    | [e112fe04f3](https://linux-hardware.org/?probe=e112fe04f3) | Oct 08, 2020 |
| HP            | 3646h                       | Desktop     | [d5dd5824e3](https://linux-hardware.org/?probe=d5dd5824e3) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [1f6fe3684d](https://linux-hardware.org/?probe=1f6fe3684d) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [8872b79e71](https://linux-hardware.org/?probe=8872b79e71) | Oct 07, 2020 |
| Medion        | E15302                      | Notebook    | [957a41b1b5](https://linux-hardware.org/?probe=957a41b1b5) | Oct 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2866055b35](https://linux-hardware.org/?probe=2866055b35) | Oct 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e91b4e0378](https://linux-hardware.org/?probe=e91b4e0378) | Oct 07, 2020 |
| Dell          | 0TVR1F A01                  | Desktop     | [3de8c4e65d](https://linux-hardware.org/?probe=3de8c4e65d) | Oct 06, 2020 |
| Dell          | 0TVR1F A01                  | Desktop     | [ae1a5155a6](https://linux-hardware.org/?probe=ae1a5155a6) | Oct 05, 2020 |
| Gigabyte      | B460M DS3H                  | Desktop     | [c607051cd6](https://linux-hardware.org/?probe=c607051cd6) | Oct 04, 2020 |
| Gigabyte      | B460M DS3H                  | Desktop     | [a96b9c0e32](https://linux-hardware.org/?probe=a96b9c0e32) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [28bab55cdf](https://linux-hardware.org/?probe=28bab55cdf) | Oct 02, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | Notebook    | [e2a36190d7](https://linux-hardware.org/?probe=e2a36190d7) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [65476de549](https://linux-hardware.org/?probe=65476de549) | Sep 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f3137e99a6](https://linux-hardware.org/?probe=f3137e99a6) | Sep 29, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [16d07f52d6](https://linux-hardware.org/?probe=16d07f52d6) | Sep 29, 2020 |
| HP            | 3047h                       | Desktop     | [8276b976a7](https://linux-hardware.org/?probe=8276b976a7) | Sep 28, 2020 |
| Medion        | E2228T MD61250              | Convertible | [bcd49135b7](https://linux-hardware.org/?probe=bcd49135b7) | Sep 26, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7bab2d2c6c](https://linux-hardware.org/?probe=7bab2d2c6c) | Sep 26, 2020 |
| HP            | 1497                        | Desktop     | [3c6ed08ddd](https://linux-hardware.org/?probe=3c6ed08ddd) | Sep 25, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [21991336a9](https://linux-hardware.org/?probe=21991336a9) | Sep 25, 2020 |
| Dell          | 09M8Y8 A01                  | Desktop     | [7086c0ba36](https://linux-hardware.org/?probe=7086c0ba36) | Sep 25, 2020 |
| System76      | Serval WS                   | Notebook    | [7add8e6511](https://linux-hardware.org/?probe=7add8e6511) | Sep 25, 2020 |
| Dell          | Precision M6700             | Notebook    | [1b20609aaa](https://linux-hardware.org/?probe=1b20609aaa) | Sep 25, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [3140b90a75](https://linux-hardware.org/?probe=3140b90a75) | Sep 24, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4150c870a5](https://linux-hardware.org/?probe=4150c870a5) | Sep 24, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7b9403ff54](https://linux-hardware.org/?probe=7b9403ff54) | Sep 24, 2020 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [ac61b9b105](https://linux-hardware.org/?probe=ac61b9b105) | Sep 23, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a53b5a24b](https://linux-hardware.org/?probe=1a53b5a24b) | Sep 21, 2020 |
| Intel         | DG43GT AAE62768-301         | Desktop     | [028847b86e](https://linux-hardware.org/?probe=028847b86e) | Sep 21, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [91c2f7bfb9](https://linux-hardware.org/?probe=91c2f7bfb9) | Sep 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [6fa6138bb4](https://linux-hardware.org/?probe=6fa6138bb4) | Sep 18, 2020 |
| Dell          | 0WX729                      | Desktop     | [f2cc61a6f1](https://linux-hardware.org/?probe=f2cc61a6f1) | Sep 17, 2020 |
| Dell          | Latitude E6410              | Notebook    | [8a3b88673f](https://linux-hardware.org/?probe=8a3b88673f) | Sep 17, 2020 |
| Dell          | 0WX729                      | Desktop     | [4fdbabe245](https://linux-hardware.org/?probe=4fdbabe245) | Sep 17, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [d026d40366](https://linux-hardware.org/?probe=d026d40366) | Sep 17, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | Notebook    | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Dell          | Latitude E6410              | Notebook    | [8930b7e16f](https://linux-hardware.org/?probe=8930b7e16f) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [299b899172](https://linux-hardware.org/?probe=299b899172) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [b45cb0028d](https://linux-hardware.org/?probe=b45cb0028d) | Sep 16, 2020 |
| Dell          | 0D441T A01                  | Desktop     | [a5c5a78a7c](https://linux-hardware.org/?probe=a5c5a78a7c) | Sep 16, 2020 |
| HP            | Compaq 8710w (GC124EA#AK... | Notebook    | [dc5006e254](https://linux-hardware.org/?probe=dc5006e254) | Sep 15, 2020 |
| Dell          | 0TW904                      | Desktop     | [20994a3808](https://linux-hardware.org/?probe=20994a3808) | Sep 15, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [092f9a6491](https://linux-hardware.org/?probe=092f9a6491) | Sep 15, 2020 |
| HP            | G42                         | Notebook    | [9cb42d6f5f](https://linux-hardware.org/?probe=9cb42d6f5f) | Sep 15, 2020 |
| HP            | G42                         | Notebook    | [72d647e1b9](https://linux-hardware.org/?probe=72d647e1b9) | Sep 15, 2020 |
| Dell          | 0T656F A01                  | Desktop     | [a004d9a942](https://linux-hardware.org/?probe=a004d9a942) | Sep 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [740ac03586](https://linux-hardware.org/?probe=740ac03586) | Sep 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f64d2d6e24](https://linux-hardware.org/?probe=f64d2d6e24) | Sep 13, 2020 |
| HP            | 18E7                        | Desktop     | [18852c6be3](https://linux-hardware.org/?probe=18852c6be3) | Sep 11, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [0bba6eaf71](https://linux-hardware.org/?probe=0bba6eaf71) | Sep 11, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| Dell          | 0T656F A01                  | Desktop     | [6b43e65d15](https://linux-hardware.org/?probe=6b43e65d15) | Sep 10, 2020 |
| Dell          | 0TVR1F A01                  | Desktop     | [22aaefa03b](https://linux-hardware.org/?probe=22aaefa03b) | Sep 10, 2020 |
| Dell          | 042P49 A01                  | Desktop     | [282331caa5](https://linux-hardware.org/?probe=282331caa5) | Sep 10, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [bfc77d64c6](https://linux-hardware.org/?probe=bfc77d64c6) | Sep 09, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [d269751a9e](https://linux-hardware.org/?probe=d269751a9e) | Sep 09, 2020 |
| Acer          | Aspire A315-42G             | Notebook    | [ab24b14a42](https://linux-hardware.org/?probe=ab24b14a42) | Sep 09, 2020 |
| Dell          | 0PV3YR A05                  | Server      | [0e92eb8c77](https://linux-hardware.org/?probe=0e92eb8c77) | Sep 09, 2020 |
| Dell          | 0N820C A02                  | Desktop     | [a43f37d51e](https://linux-hardware.org/?probe=a43f37d51e) | Sep 08, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [c39d1b0af6](https://linux-hardware.org/?probe=c39d1b0af6) | Sep 05, 2020 |
| MSI           | Creator TRX40               | Desktop     | [48149893d7](https://linux-hardware.org/?probe=48149893d7) | Sep 04, 2020 |
| HP            | 3397                        | Desktop     | [e9da9cd17f](https://linux-hardware.org/?probe=e9da9cd17f) | Sep 03, 2020 |
| HP            | 339A                        | Desktop     | [5f29fd9231](https://linux-hardware.org/?probe=5f29fd9231) | Sep 03, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e3bc793dc3](https://linux-hardware.org/?probe=e3bc793dc3) | Sep 03, 2020 |
| HP            | 3397                        | Desktop     | [a8ea68de6d](https://linux-hardware.org/?probe=a8ea68de6d) | Sep 03, 2020 |
| Dell          | Latitude E6420              | Notebook    | [676828b4d4](https://linux-hardware.org/?probe=676828b4d4) | Sep 03, 2020 |
| MSI           | MEG X570 UNIFY              | Desktop     | [7e2dae216d](https://linux-hardware.org/?probe=7e2dae216d) | Sep 03, 2020 |
| Dell          | 03K80F A00                  | Desktop     | [a3452cb614](https://linux-hardware.org/?probe=a3452cb614) | Sep 02, 2020 |
| Dell          | 0HY9JP A00                  | Desktop     | [e797b1bf14](https://linux-hardware.org/?probe=e797b1bf14) | Sep 02, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2b44d73e4b](https://linux-hardware.org/?probe=2b44d73e4b) | Sep 02, 2020 |
| HP            | 1497                        | Desktop     | [edf6c3ecfa](https://linux-hardware.org/?probe=edf6c3ecfa) | Sep 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [6057658605](https://linux-hardware.org/?probe=6057658605) | Sep 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [9b1f1928c7](https://linux-hardware.org/?probe=9b1f1928c7) | Sep 01, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [461e0244f4](https://linux-hardware.org/?probe=461e0244f4) | Aug 31, 2020 |
| Positivo      | Mobile                      | Notebook    | [2249764f28](https://linux-hardware.org/?probe=2249764f28) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [cae373d70b](https://linux-hardware.org/?probe=cae373d70b) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c77cf6f3fa](https://linux-hardware.org/?probe=c77cf6f3fa) | Aug 30, 2020 |
| Toshiba       | Satellite M500              | Notebook    | [42449081bb](https://linux-hardware.org/?probe=42449081bb) | Aug 29, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [b26cdf0225](https://linux-hardware.org/?probe=b26cdf0225) | Aug 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dbb2bb4c60](https://linux-hardware.org/?probe=dbb2bb4c60) | Aug 28, 2020 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b39122c844](https://linux-hardware.org/?probe=b39122c844) | Aug 25, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [8d0d4f27be](https://linux-hardware.org/?probe=8d0d4f27be) | Aug 22, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [97eeff2c12](https://linux-hardware.org/?probe=97eeff2c12) | Aug 22, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [7d6c45eed4](https://linux-hardware.org/?probe=7d6c45eed4) | Aug 20, 2020 |
| Intel         | Unknown                     | Desktop     | [0792f8e763](https://linux-hardware.org/?probe=0792f8e763) | Aug 20, 2020 |
| ASRock        | 990FX Extreme4              | Desktop     | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [f3ea863c21](https://linux-hardware.org/?probe=f3ea863c21) | Aug 19, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | Notebook    | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [83214468ce](https://linux-hardware.org/?probe=83214468ce) | Aug 17, 2020 |
| MSI           | GP72MVR 7RFX                | Notebook    | [39da2f58b5](https://linux-hardware.org/?probe=39da2f58b5) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [844d21cfba](https://linux-hardware.org/?probe=844d21cfba) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [d568758fb5](https://linux-hardware.org/?probe=d568758fb5) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [93e07b3103](https://linux-hardware.org/?probe=93e07b3103) | Aug 16, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [021ed0aac6](https://linux-hardware.org/?probe=021ed0aac6) | Aug 16, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0e5e076914](https://linux-hardware.org/?probe=0e5e076914) | Aug 15, 2020 |
| GPD           | MicroPC                     | Notebook    | [bb39ae1b31](https://linux-hardware.org/?probe=bb39ae1b31) | Aug 15, 2020 |
| Sony          | VPCEH1S1E                   | Notebook    | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3e086d75b0](https://linux-hardware.org/?probe=3e086d75b0) | Aug 12, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ab576b0cd8](https://linux-hardware.org/?probe=ab576b0cd8) | Aug 12, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [f2da7fe3f0](https://linux-hardware.org/?probe=f2da7fe3f0) | Aug 12, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [27573f027c](https://linux-hardware.org/?probe=27573f027c) | Aug 12, 2020 |
| Intel         | Unknown                     | Desktop     | [aca06096b6](https://linux-hardware.org/?probe=aca06096b6) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1c6f36de59](https://linux-hardware.org/?probe=1c6f36de59) | Aug 10, 2020 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [608ff52425](https://linux-hardware.org/?probe=608ff52425) | Aug 06, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [93bb4b7ef5](https://linux-hardware.org/?probe=93bb4b7ef5) | Aug 06, 2020 |
| HP            | Pavilion dm1                | Notebook    | [ccb974921b](https://linux-hardware.org/?probe=ccb974921b) | Aug 05, 2020 |
| Gigabyte      | Z77P-D3                     | Desktop     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [7bfd99a9bd](https://linux-hardware.org/?probe=7bfd99a9bd) | Aug 05, 2020 |
| Dell          | System XPS L702X            | Notebook    | [86885b0835](https://linux-hardware.org/?probe=86885b0835) | Aug 04, 2020 |
| MSI           | GV62 8RD                    | Notebook    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [bd1790913e](https://linux-hardware.org/?probe=bd1790913e) | Aug 03, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [09aac7d871](https://linux-hardware.org/?probe=09aac7d871) | Aug 01, 2020 |
| Dell          | Precision M4800             | Notebook    | [defc3ac914](https://linux-hardware.org/?probe=defc3ac914) | Aug 01, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8936a7017a](https://linux-hardware.org/?probe=8936a7017a) | Jul 28, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [3ee7d0dc49](https://linux-hardware.org/?probe=3ee7d0dc49) | Jul 28, 2020 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [efd445830e](https://linux-hardware.org/?probe=efd445830e) | Jul 27, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [a1ea369f96](https://linux-hardware.org/?probe=a1ea369f96) | Jul 27, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [e9661e7816](https://linux-hardware.org/?probe=e9661e7816) | Jul 27, 2020 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [dfb8a55f7f](https://linux-hardware.org/?probe=dfb8a55f7f) | Jul 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [3ff385285a](https://linux-hardware.org/?probe=3ff385285a) | Jul 26, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [12424c5a76](https://linux-hardware.org/?probe=12424c5a76) | Jul 25, 2020 |
| HP            | Pavilion g4                 | Notebook    | [a10cfaa6e2](https://linux-hardware.org/?probe=a10cfaa6e2) | Jul 24, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [6affb516f1](https://linux-hardware.org/?probe=6affb516f1) | Jul 24, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [8a3873a0c3](https://linux-hardware.org/?probe=8a3873a0c3) | Jul 24, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [3e594f7ff4](https://linux-hardware.org/?probe=3e594f7ff4) | Jul 24, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [baa26535f9](https://linux-hardware.org/?probe=baa26535f9) | Jul 23, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [9dbcace7db](https://linux-hardware.org/?probe=9dbcace7db) | Jul 21, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [292d396a46](https://linux-hardware.org/?probe=292d396a46) | Jul 21, 2020 |
| Dell          | Vostro 3560                 | Notebook    | [c83b65951c](https://linux-hardware.org/?probe=c83b65951c) | Jul 20, 2020 |
| HP            | ZBook 17 G2                 | Notebook    | [61d82db95d](https://linux-hardware.org/?probe=61d82db95d) | Jul 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [8e5e5de5c3](https://linux-hardware.org/?probe=8e5e5de5c3) | Jul 20, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [9577cafcf7](https://linux-hardware.org/?probe=9577cafcf7) | Jul 19, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [c3a79140eb](https://linux-hardware.org/?probe=c3a79140eb) | Jul 18, 2020 |
| Lenovo        | ThinkPad T490 20N3CTO1WW    | Notebook    | [b6f9682f0b](https://linux-hardware.org/?probe=b6f9682f0b) | Jul 15, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [5657a6a512](https://linux-hardware.org/?probe=5657a6a512) | Jul 14, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [68e6b713ca](https://linux-hardware.org/?probe=68e6b713ca) | Jul 14, 2020 |
| Dell          | G7 7588                     | Notebook    | [8c4a8875bd](https://linux-hardware.org/?probe=8c4a8875bd) | Jul 14, 2020 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [bd28d2c132](https://linux-hardware.org/?probe=bd28d2c132) | Jul 13, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [eba8df9bea](https://linux-hardware.org/?probe=eba8df9bea) | Jul 12, 2020 |
| Dell          | G7 7588                     | Notebook    | [aee8398552](https://linux-hardware.org/?probe=aee8398552) | Jul 12, 2020 |
| HP            | 8434 11                     | Desktop     | [377d6d5aa4](https://linux-hardware.org/?probe=377d6d5aa4) | Jul 10, 2020 |
| Lenovo        | ThinkCentre A70 7844P8U     | Desktop     | [30edd53934](https://linux-hardware.org/?probe=30edd53934) | Jul 09, 2020 |
| Sony          | VPCF1290X                   | Notebook    | [f7c7a3ca92](https://linux-hardware.org/?probe=f7c7a3ca92) | Jul 08, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [096c493c42](https://linux-hardware.org/?probe=096c493c42) | Jul 06, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [f4dd6bbdec](https://linux-hardware.org/?probe=f4dd6bbdec) | Jul 06, 2020 |
| Lenovo        | ThinkPad 11e 20D9CTO1WW     | Notebook    | [11c17aa062](https://linux-hardware.org/?probe=11c17aa062) | Jul 05, 2020 |
| Acer          | Aspire 7750G                | Notebook    | [f6a31e475d](https://linux-hardware.org/?probe=f6a31e475d) | Jul 05, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [7e6be23ee7](https://linux-hardware.org/?probe=7e6be23ee7) | Jul 04, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8bcdced5b3](https://linux-hardware.org/?probe=8bcdced5b3) | Jul 04, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [994e71e658](https://linux-hardware.org/?probe=994e71e658) | Jul 03, 2020 |
| HP            | 250 G4                      | Notebook    | [ca40ef5473](https://linux-hardware.org/?probe=ca40ef5473) | Jul 02, 2020 |
| MSI           | A78M-E35                    | Desktop     | [baf6228acf](https://linux-hardware.org/?probe=baf6228acf) | Jul 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f7afeb0f26](https://linux-hardware.org/?probe=f7afeb0f26) | Jul 01, 2020 |
| HP            | Pavilion g6                 | Notebook    | [0175164903](https://linux-hardware.org/?probe=0175164903) | Jul 01, 2020 |
| Unknown       | Unknown                     | Soc         | [537289447f](https://linux-hardware.org/?probe=537289447f) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c1d0ef500e](https://linux-hardware.org/?probe=c1d0ef500e) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6a9b477b88](https://linux-hardware.org/?probe=6a9b477b88) | Jun 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [cd4ada5990](https://linux-hardware.org/?probe=cd4ada5990) | Jun 28, 2020 |
| HP            | Pavilion g6                 | Notebook    | [efc97f097b](https://linux-hardware.org/?probe=efc97f097b) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [944b66e3ba](https://linux-hardware.org/?probe=944b66e3ba) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [3f58959650](https://linux-hardware.org/?probe=3f58959650) | Jun 24, 2020 |
| Lenovo        | ThinkPad T520 4243RS6       | Notebook    | [881175c7ec](https://linux-hardware.org/?probe=881175c7ec) | Jun 23, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [143bbac73c](https://linux-hardware.org/?probe=143bbac73c) | Jun 23, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [c5a7e2708f](https://linux-hardware.org/?probe=c5a7e2708f) | Jun 22, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [1f2d306b05](https://linux-hardware.org/?probe=1f2d306b05) | Jun 20, 2020 |
| IBM           | 9210KGT                     | Desktop     | [28e9762210](https://linux-hardware.org/?probe=28e9762210) | Jun 16, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2290a03a3](https://linux-hardware.org/?probe=e2290a03a3) | Jun 16, 2020 |
| Lenovo        | ThinkPad X240 qqqq          | Notebook    | [04328e30ac](https://linux-hardware.org/?probe=04328e30ac) | Jun 15, 2020 |
| Sony          | VPCF1290X                   | Notebook    | [55652dadf6](https://linux-hardware.org/?probe=55652dadf6) | Jun 15, 2020 |
| Dell          | 0JTHY5 A00                  | All in one  | [5da41dbee9](https://linux-hardware.org/?probe=5da41dbee9) | Jun 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8fce25fa5d](https://linux-hardware.org/?probe=8fce25fa5d) | Jun 13, 2020 |
| Lenovo        | ThinkPad T430 2349H86       | Notebook    | [5ef2ab445e](https://linux-hardware.org/?probe=5ef2ab445e) | Jun 13, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | Notebook    | [5467542c77](https://linux-hardware.org/?probe=5467542c77) | Jun 12, 2020 |
| HP            | Pavilion g6                 | Notebook    | [78f5ccb141](https://linux-hardware.org/?probe=78f5ccb141) | Jun 11, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [02f2a001e1](https://linux-hardware.org/?probe=02f2a001e1) | Jun 11, 2020 |
| ASRock        | H110M-STX                   | Desktop     | [3c35aef096](https://linux-hardware.org/?probe=3c35aef096) | Jun 10, 2020 |
| Dell          | 0478VN A00                  | Desktop     | [f02bda5144](https://linux-hardware.org/?probe=f02bda5144) | Jun 09, 2020 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [61fe34704e](https://linux-hardware.org/?probe=61fe34704e) | Jun 08, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [4c810c7859](https://linux-hardware.org/?probe=4c810c7859) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [35995e9a53](https://linux-hardware.org/?probe=35995e9a53) | Jun 06, 2020 |
| ASUSTek       | X541SA                      | Notebook    | [508fc56922](https://linux-hardware.org/?probe=508fc56922) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [d6bcbe862e](https://linux-hardware.org/?probe=d6bcbe862e) | Jun 05, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8dbad33afb](https://linux-hardware.org/?probe=8dbad33afb) | Jun 05, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8177bd99b7](https://linux-hardware.org/?probe=8177bd99b7) | Jun 05, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [56c24dddd4](https://linux-hardware.org/?probe=56c24dddd4) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [140b5cec40](https://linux-hardware.org/?probe=140b5cec40) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [9c5c59ed91](https://linux-hardware.org/?probe=9c5c59ed91) | May 30, 2020 |
| Packard Be... | EasyNote ME69BMP            | Notebook    | [7023dc94da](https://linux-hardware.org/?probe=7023dc94da) | May 28, 2020 |
| Dell          | Precision M6800             | Notebook    | [fac8dbf769](https://linux-hardware.org/?probe=fac8dbf769) | May 28, 2020 |
| Packard Be... | EasyNote ME69BMP            | Notebook    | [17cb4d2a9a](https://linux-hardware.org/?probe=17cb4d2a9a) | May 28, 2020 |
| Dell          | Precision M4800             | Notebook    | [4f404379b5](https://linux-hardware.org/?probe=4f404379b5) | May 27, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | Notebook    | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Toshiba       | Satellite M500              | Notebook    | [89bc529650](https://linux-hardware.org/?probe=89bc529650) | May 23, 2020 |
| Sony          | VPCF1290X                   | Notebook    | [6d41a82565](https://linux-hardware.org/?probe=6d41a82565) | May 22, 2020 |
| Sony          | VPCF1290X                   | Notebook    | [e260c25549](https://linux-hardware.org/?probe=e260c25549) | May 20, 2020 |
| IBM           | 9210KGT                     | Desktop     | [784c83d7d6](https://linux-hardware.org/?probe=784c83d7d6) | May 19, 2020 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8fd77159e9](https://linux-hardware.org/?probe=8fd77159e9) | May 19, 2020 |
| ASUSTek       | X541SA                      | Notebook    | [af59d45f16](https://linux-hardware.org/?probe=af59d45f16) | May 19, 2020 |
| Dell          | 0WF810                      | Desktop     | [24f1a1287d](https://linux-hardware.org/?probe=24f1a1287d) | May 17, 2020 |
| Dell          | 0WF810                      | Desktop     | [6ae0e21069](https://linux-hardware.org/?probe=6ae0e21069) | May 17, 2020 |
| Dell          | 0WF810                      | Desktop     | [e6f27fd467](https://linux-hardware.org/?probe=e6f27fd467) | May 17, 2020 |
| Dell          | Latitude E6400              | Notebook    | [5575a3dc87](https://linux-hardware.org/?probe=5575a3dc87) | May 17, 2020 |
| Dell          | Latitude E6400              | Notebook    | [4ad76f6e55](https://linux-hardware.org/?probe=4ad76f6e55) | May 16, 2020 |
| Dell          | Latitude E6400              | Notebook    | [9c8f7c7f2c](https://linux-hardware.org/?probe=9c8f7c7f2c) | May 16, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4806bd297f](https://linux-hardware.org/?probe=4806bd297f) | May 16, 2020 |
| Dell          | Latitude E6400              | Notebook    | [0e2b5d699e](https://linux-hardware.org/?probe=0e2b5d699e) | May 16, 2020 |
| HP            | 250 G1                      | Notebook    | [bc48855d22](https://linux-hardware.org/?probe=bc48855d22) | May 16, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| Lenovo        | SDK0E50510 WIN 262507961... | Desktop     | [0400e155ee](https://linux-hardware.org/?probe=0400e155ee) | May 10, 2020 |
| Lenovo        | ThinkPad X240 20AMS08816    | Notebook    | [5581eee295](https://linux-hardware.org/?probe=5581eee295) | May 10, 2020 |
| Dell          | System XPS L502X            | Notebook    | [f095fb06d8](https://linux-hardware.org/?probe=f095fb06d8) | May 09, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [567162aae3](https://linux-hardware.org/?probe=567162aae3) | May 09, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1d17b00751](https://linux-hardware.org/?probe=1d17b00751) | May 05, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9a72c58dee](https://linux-hardware.org/?probe=9a72c58dee) | May 04, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a3765f096d](https://linux-hardware.org/?probe=a3765f096d) | May 04, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c5b6d15b98](https://linux-hardware.org/?probe=c5b6d15b98) | May 04, 2020 |
| Samsung       | 550P5C/550P7C               | Notebook    | [4262f676d3](https://linux-hardware.org/?probe=4262f676d3) | May 04, 2020 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [88dd0cfbcb](https://linux-hardware.org/?probe=88dd0cfbcb) | May 02, 2020 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [530009d42a](https://linux-hardware.org/?probe=530009d42a) | May 02, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [015ef81b51](https://linux-hardware.org/?probe=015ef81b51) | May 02, 2020 |
| ASUSTek       | G73Sw                       | Notebook    | [d4abec1a93](https://linux-hardware.org/?probe=d4abec1a93) | May 02, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [f986b480ad](https://linux-hardware.org/?probe=f986b480ad) | May 01, 2020 |
| Dell          | Inspiron 3576               | Notebook    | [4dc9474ba1](https://linux-hardware.org/?probe=4dc9474ba1) | Apr 29, 2020 |
| Intel         | D946GZIS AAD45436-306       | Desktop     | [483b574b1a](https://linux-hardware.org/?probe=483b574b1a) | Apr 25, 2020 |
| Sony          | VPCS12X9E                   | Notebook    | [3631a4d89d](https://linux-hardware.org/?probe=3631a4d89d) | Apr 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ba2c3155d7](https://linux-hardware.org/?probe=ba2c3155d7) | Apr 22, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | Notebook    | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| HP            | EliteBook 755 G5            | Notebook    | [db0ea12ab8](https://linux-hardware.org/?probe=db0ea12ab8) | Apr 16, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [154b970640](https://linux-hardware.org/?probe=154b970640) | Mar 25, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [513772febc](https://linux-hardware.org/?probe=513772febc) | Mar 01, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [ad9b0ebdf6](https://linux-hardware.org/?probe=ad9b0ebdf6) | Feb 25, 2020 |
| Acer          | Aspire V3-574G              | Notebook    | [471f9aa9b0](https://linux-hardware.org/?probe=471f9aa9b0) | Jan 02, 2020 |
| MSI           | GP72 6QF                    | Notebook    | [98dc37dc79](https://linux-hardware.org/?probe=98dc37dc79) | Oct 21, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_MATE_20.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-48-generic  | 39        | 5.49%   |
| 5.4.0-42-generic  | 39        | 5.49%   |
| 5.4.0-52-generic  | 31        | 4.36%   |
| 5.4.0-47-generic  | 22        | 3.09%   |
| 5.4.0-40-generic  | 18        | 2.53%   |
| 5.4.0-45-generic  | 16        | 2.25%   |
| 5.4.0-65-generic  | 15        | 2.11%   |
| 5.4.0-94-generic  | 13        | 1.83%   |
| 5.4.0-58-generic  | 13        | 1.83%   |
| 5.11.0-40-generic | 13        | 1.83%   |
| 5.4.0-26-generic  | 11        | 1.55%   |
| 5.4.0-89-generic  | 10        | 1.41%   |
| 5.4.0-56-generic  | 10        | 1.41%   |
| 5.4.0-31-generic  | 10        | 1.41%   |
| 5.4.0-29-generic  | 10        | 1.41%   |
| 5.8.0-59-generic  | 9         | 1.27%   |
| 5.8.0-50-generic  | 9         | 1.27%   |
| 5.4.0-81-generic  | 9         | 1.27%   |
| 5.4.0-66-generic  | 9         | 1.27%   |
| 5.4.0-74-generic  | 8         | 1.13%   |
| 5.4.0-37-generic  | 8         | 1.13%   |
| 5.13.0-30-generic | 8         | 1.13%   |
| 5.11.0-43-generic | 8         | 1.13%   |
| 5.8.0-48-generic  | 7         | 0.98%   |
| 5.4.0-80-generic  | 7         | 0.98%   |
| 5.4.0-67-generic  | 7         | 0.98%   |
| 5.4.0-33-generic  | 7         | 0.98%   |
| 5.13.0-39-generic | 7         | 0.98%   |
| 5.11.0-38-generic | 7         | 0.98%   |
| 5.8.0-53-generic  | 6         | 0.84%   |
| 5.8.0-43-generic  | 6         | 0.84%   |
| 5.4.0-90-generic  | 6         | 0.84%   |
| 5.4.0-73-generic  | 6         | 0.84%   |
| 5.4.0-72-generic  | 6         | 0.84%   |
| 5.4.0-54-generic  | 6         | 0.84%   |
| 5.4.0-51-generic  | 6         | 0.84%   |
| 5.4.0-1019-raspi  | 6         | 0.84%   |
| 5.11.0-37-generic | 6         | 0.84%   |
| 5.4.0-91-generic  | 5         | 0.7%    |
| 5.4.0-62-generic  | 5         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 425       | 65.69%  |
| 5.11.0  | 53        | 8.19%   |
| 5.8.0   | 52        | 8.04%   |
| 5.13.0  | 46        | 7.11%   |
| 5.15.0  | 30        | 4.64%   |
| 5.14.0  | 6         | 0.93%   |
| 5.10.27 | 4         | 0.62%   |
| 4.9.277 | 4         | 0.62%   |
| 5.3.0   | 2         | 0.31%   |
| 5.10.0  | 2         | 0.31%   |
| 4.4.154 | 2         | 0.31%   |
| 6.1.12  | 1         | 0.15%   |
| 5.9.3   | 1         | 0.15%   |
| 5.9.0   | 1         | 0.15%   |
| 5.8.17  | 1         | 0.15%   |
| 5.7.6   | 1         | 0.15%   |
| 5.7.0   | 1         | 0.15%   |
| 5.6.7   | 1         | 0.15%   |
| 5.5.11  | 1         | 0.15%   |
| 5.4.236 | 1         | 0.15%   |
| 5.4.167 | 1         | 0.15%   |
| 5.17.0  | 1         | 0.15%   |
| 5.16.0  | 1         | 0.15%   |
| 5.15.6  | 1         | 0.15%   |
| 5.15.34 | 1         | 0.15%   |
| 5.15.29 | 1         | 0.15%   |
| 5.15.27 | 1         | 0.15%   |
| 5.15.12 | 1         | 0.15%   |
| 5.10.5  | 1         | 0.15%   |
| 4.9.230 | 1         | 0.15%   |
| 4.14.89 | 1         | 0.15%   |
| 3.16.85 | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 427       | 66%     |
| 5.8     | 53        | 8.19%   |
| 5.11    | 53        | 8.19%   |
| 5.13    | 46        | 7.11%   |
| 5.15    | 35        | 5.41%   |
| 5.10    | 7         | 1.08%   |
| 5.14    | 6         | 0.93%   |
| 4.9     | 5         | 0.77%   |
| 5.9     | 2         | 0.31%   |
| 5.7     | 2         | 0.31%   |
| 5.3     | 2         | 0.31%   |
| 4.4     | 2         | 0.31%   |
| 6.1     | 1         | 0.15%   |
| 5.6     | 1         | 0.15%   |
| 5.5     | 1         | 0.15%   |
| 5.17    | 1         | 0.15%   |
| 5.16    | 1         | 0.15%   |
| 4.14    | 1         | 0.15%   |
| 3.16    | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 601       | 94.35%  |
| aarch64 | 30        | 4.71%   |
| armv7l  | 6         | 0.94%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 622       | 97.65%  |
| Cinnamon   | 5         | 0.78%   |
| X-Cinnamon | 3         | 0.47%   |
| GNOME      | 3         | 0.47%   |
| Trinity    | 1         | 0.16%   |
| KDE5       | 1         | 0.16%   |
| i3         | 1         | 0.16%   |
| Budgie     | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 614       | 96.24%  |
| Tty     | 18        | 2.82%   |
| Wayland | 6         | 0.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 230       | 35.17%  |
| TDM     | 214       | 32.72%  |
| Unknown | 170       | 25.99%  |
| GDM     | 28        | 4.28%   |
| GDM3    | 8         | 1.22%   |
| SLiM    | 2         | 0.31%   |
| SDDM    | 2         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 201       | 31.41%  |
| pt_BR | 86        | 13.44%  |
| fr_FR | 61        | 9.53%   |
| de_DE | 47        | 7.34%   |
| en_GB | 33        | 5.16%   |
| es_ES | 22        | 3.44%   |
| C     | 22        | 3.44%   |
| it_IT | 19        | 2.97%   |
| ru_RU | 18        | 2.81%   |
| en_CA | 17        | 2.66%   |
| el_GR | 17        | 2.66%   |
| es_AR | 11        | 1.72%   |
| pl_PL | 8         | 1.25%   |
| en_AU | 7         | 1.09%   |
| ru_UA | 6         | 0.94%   |
| en_IN | 6         | 0.94%   |
| de_CH | 6         | 0.94%   |
| nl_NL | 4         | 0.63%   |
| hu_HU | 4         | 0.63%   |
| cs_CZ | 4         | 0.63%   |
| fi_FI | 3         | 0.47%   |
| en_PH | 3         | 0.47%   |
| ca_ES | 3         | 0.47%   |
| sv_SE | 2         | 0.31%   |
| hr_HR | 2         | 0.31%   |
| fr_CA | 2         | 0.31%   |
| da_DK | 2         | 0.31%   |
| zh_TW | 1         | 0.16%   |
| zh_CN | 1         | 0.16%   |
| uk_UA | 1         | 0.16%   |
| sk_SK | 1         | 0.16%   |
| nl_BE | 1         | 0.16%   |
| lv_LV | 1         | 0.16%   |
| ja_JP | 1         | 0.16%   |
| fr_CH | 1         | 0.16%   |
| fr_BE | 1         | 0.16%   |
| eu_ES | 1         | 0.16%   |
| et_EE | 1         | 0.16%   |
| es_UY | 1         | 0.16%   |
| es_PR | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 328       | 51.17%  |
| EFI  | 313       | 48.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 594       | 92.96%  |
| Overlay | 24        | 3.76%   |
| Btrfs   | 7         | 1.1%    |
| Zfs     | 5         | 0.78%   |
| Xfs     | 4         | 0.63%   |
| Ext3    | 2         | 0.31%   |
| Tmpfs   | 1         | 0.16%   |
| Jfs     | 1         | 0.16%   |
| ExX4    | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 237       | 36.86%  |
| Unknown | 212       | 32.97%  |
| MBR     | 194       | 30.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 567       | 87.77%  |
| Yes       | 79        | 12.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 449       | 69.61%  |
| Yes       | 196       | 30.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 112       | 17.58%  |
| Dell                    | 111       | 17.43%  |
| ASUSTek Computer        | 89        | 13.97%  |
| Lenovo                  | 75        | 11.77%  |
| Gigabyte Technology     | 40        | 6.28%   |
| MSI                     | 29        | 4.55%   |
| ASRock                  | 25        | 3.92%   |
| Raspberry Pi Foundation | 24        | 3.77%   |
| Acer                    | 23        | 3.61%   |
| Intel                   | 14        | 2.2%    |
| Toshiba                 | 10        | 1.57%   |
| Samsung Electronics     | 8         | 1.26%   |
| Hardkernel              | 8         | 1.26%   |
| Apple                   | 6         | 0.94%   |
| Medion                  | 5         | 0.78%   |
| Unknown                 | 5         | 0.78%   |
| Sony                    | 4         | 0.63%   |
| Pegatron                | 3         | 0.47%   |
| Packard Bell            | 3         | 0.47%   |
| Avell High Performance  | 3         | 0.47%   |
| Supermicro              | 2         | 0.31%   |
| Rockchip                | 2         | 0.31%   |
| Positivo                | 2         | 0.31%   |
| Notebook                | 2         | 0.31%   |
| GPD                     | 2         | 0.31%   |
| Fujitsu                 | 2         | 0.31%   |
| ECS                     | 2         | 0.31%   |
| Biostar                 | 2         | 0.31%   |
| Wortmann AG             | 1         | 0.16%   |
| TUXEDO                  | 1         | 0.16%   |
| Teclast                 | 1         | 0.16%   |
| System76                | 1         | 0.16%   |
| Star Labs               | 1         | 0.16%   |
| Semp Toshiba            | 1         | 0.16%   |
| Polaroid                | 1         | 0.16%   |
| Pine Microsystems       | 1         | 0.16%   |
| ONE-NETBOOK TECHNOLOGY  | 1         | 0.16%   |
| ONDA                    | 1         | 0.16%   |
| MicroByte               | 1         | 0.16%   |
| JINGSHA                 | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 10        | 1.57%   |
| RPi Raspberry Pi 4 Model B Rev 1.2 | 8         | 1.26%   |
| HP Compaq Elite 8300 SFF           | 8         | 1.26%   |
| HP Compaq 6005 Pro SFF PC          | 8         | 1.26%   |
| ASUS All Series                    | 7         | 1.1%    |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 6         | 0.94%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 5         | 0.78%   |
| Dell OptiPlex 3010                 | 5         | 0.78%   |
| Dell Latitude E6420                | 5         | 0.78%   |
| RPi Raspberry Pi                   | 4         | 0.63%   |
| HP Pavilion dv7                    | 4         | 0.63%   |
| Hardkernel ODROID-N2Plus           | 4         | 0.63%   |
| Dell OptiPlex GX520                | 4         | 0.63%   |
| Dell OptiPlex 390                  | 4         | 0.63%   |
| Dell OptiPlex 360                  | 4         | 0.63%   |
| ASRock B450M Pro4                  | 4         | 0.63%   |
| HP Pavilion g6                     | 3         | 0.47%   |
| HP Notebook                        | 3         | 0.47%   |
| HP Compaq 6200 Pro SFF PC          | 3         | 0.47%   |
| Dell Precision M4800               | 3         | 0.47%   |
| Dell OptiPlex 330                  | 3         | 0.47%   |
| Dell Latitude E6410                | 3         | 0.47%   |
| ASUS M5A78L-M/USB3                 | 3         | 0.47%   |
| Toshiba Satellite C660             | 2         | 0.31%   |
| MSI MS-7C94                        | 2         | 0.31%   |
| MSI MS-7817                        | 2         | 0.31%   |
| MSI MS-7680                        | 2         | 0.31%   |
| Lenovo ThinkBook 14s Yoga ITL 20WE | 2         | 0.31%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2  | 2         | 0.31%   |
| HP x2 Detachable 10-p0XX           | 2         | 0.31%   |
| HP EliteBook 8470p                 | 2         | 0.31%   |
| HP Compaq 8000 Elite SFF PC        | 2         | 0.31%   |
| HP Compaq 4000 Pro SFF PC          | 2         | 0.31%   |
| HP 15                              | 2         | 0.31%   |
| Hardkernel ODROID-C4               | 2         | 0.31%   |
| Hardkernel Odroid XU4              | 2         | 0.31%   |
| Gigabyte Z97-HD3                   | 2         | 0.31%   |
| Gigabyte Z590 UD AC                | 2         | 0.31%   |
| Gigabyte B450M DS3H                | 2         | 0.31%   |
| Dell XPS 13 9360                   | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 41        | 6.44%   |
| Dell OptiPlex            | 38        | 5.97%   |
| HP Compaq                | 34        | 5.34%   |
| RPi Raspberry            | 24        | 3.77%   |
| Dell Latitude            | 23        | 3.61%   |
| HP Pavilion              | 22        | 3.45%   |
| Acer Aspire              | 16        | 2.51%   |
| Dell Precision           | 14        | 2.2%    |
| Lenovo IdeaPad           | 11        | 1.73%   |
| HP EliteBook             | 11        | 1.73%   |
| Toshiba Satellite        | 10        | 1.57%   |
| Dell Inspiron            | 10        | 1.57%   |
| Unknown                  | 10        | 1.57%   |
| ASUS PRIME               | 8         | 1.26%   |
| Dell XPS                 | 7         | 1.1%    |
| Dell Vostro              | 7         | 1.1%    |
| ASUS All                 | 7         | 1.1%    |
| HP ProBook               | 6         | 0.94%   |
| HP 250                   | 6         | 0.94%   |
| Lenovo ThinkCentre       | 4         | 0.63%   |
| Lenovo ThinkBook         | 4         | 0.63%   |
| HP ZBook                 | 4         | 0.63%   |
| HP Laptop                | 4         | 0.63%   |
| Hardkernel ODROID-N2Plus | 4         | 0.63%   |
| ASUS VivoBook            | 4         | 0.63%   |
| ASUS ROG                 | 4         | 0.63%   |
| ASUS M5A78L-M            | 4         | 0.63%   |
| ASRock B450M             | 4         | 0.63%   |
| Packard Bell EasyNote    | 3         | 0.47%   |
| HP ProLiant              | 3         | 0.47%   |
| HP Notebook              | 3         | 0.47%   |
| Dell Studio              | 3         | 0.47%   |
| ASUS TUF                 | 3         | 0.47%   |
| ASUS M5A97               | 3         | 0.47%   |
| MSI MS-7C94              | 2         | 0.31%   |
| MSI MS-7817              | 2         | 0.31%   |
| MSI MS-7680              | 2         | 0.31%   |
| Lenovo Legion            | 2         | 0.31%   |
| Lenovo IdeaPadFlex       | 2         | 0.31%   |
| Lenovo Flex              | 2         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 75        | 11.77%  |
| 2020    | 61        | 9.58%   |
| 2012    | 61        | 9.58%   |
| 2018    | 53        | 8.32%   |
| 2013    | 47        | 7.38%   |
| 2019    | 43        | 6.75%   |
| 2014    | 37        | 5.81%   |
| 2008    | 37        | 5.81%   |
| 2015    | 33        | 5.18%   |
| 2009    | 33        | 5.18%   |
| 2010    | 31        | 4.87%   |
| 2016    | 28        | 4.4%    |
| 2017    | 25        | 3.92%   |
| 2021    | 24        | 3.77%   |
| Unknown | 24        | 3.77%   |
| 2007    | 12        | 1.88%   |
| 2006    | 6         | 0.94%   |
| 2005    | 6         | 0.94%   |
| 2022    | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 301       | 47.25%  |
| Desktop        | 264       | 41.44%  |
| System on chip | 35        | 5.49%   |
| Convertible    | 11        | 1.73%   |
| Mini pc        | 9         | 1.41%   |
| Server         | 9         | 1.41%   |
| Tablet         | 4         | 0.63%   |
| All in one     | 4         | 0.63%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 593       | 92.95%  |
| Enabled  | 45        | 7.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 636       | 99.84%  |
| Yes  | 1         | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 194       | 30.17%  |
| 4.01-8.0        | 124       | 19.28%  |
| 8.01-16.0       | 99        | 15.4%   |
| 16.01-24.0      | 89        | 13.84%  |
| 32.01-64.0      | 50        | 7.78%   |
| 64.01-256.0     | 32        | 4.98%   |
| 1.01-2.0        | 24        | 3.73%   |
| 2.01-3.0        | 13        | 2.02%   |
| 24.01-32.0      | 11        | 1.71%   |
| 0.51-1.0        | 6         | 0.93%   |
| More than 256.0 | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 245       | 36.03%  |
| 2.01-3.0   | 145       | 21.32%  |
| 0.51-1.0   | 97        | 14.26%  |
| 4.01-8.0   | 80        | 11.76%  |
| 3.01-4.0   | 74        | 10.88%  |
| 8.01-16.0  | 17        | 2.5%    |
| 0.01-0.5   | 11        | 1.62%   |
| 24.01-32.0 | 5         | 0.74%   |
| 16.01-24.0 | 4         | 0.59%   |
| 32.01-64.0 | 2         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 414       | 63.21%  |
| 2      | 158       | 24.12%  |
| 3      | 45        | 6.87%   |
| 4      | 19        | 2.9%    |
| 5      | 5         | 0.76%   |
| 7      | 3         | 0.46%   |
| 0      | 3         | 0.46%   |
| 10     | 2         | 0.31%   |
| 8      | 2         | 0.31%   |
| 6      | 2         | 0.31%   |
| 11     | 1         | 0.15%   |
| 9      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 337       | 52.57%  |
| Yes       | 304       | 47.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 558       | 87.46%  |
| No        | 80        | 12.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 418       | 65.01%  |
| No        | 225       | 34.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 331       | 51.56%  |
| Yes       | 311       | 48.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Brazil      | 101       | 15.76%  |
| USA         | 83        | 12.95%  |
| France      | 65        | 10.14%  |
| Germany     | 61        | 9.52%   |
| UK          | 34        | 5.3%    |
| Spain       | 30        | 4.68%   |
| Italy       | 25        | 3.9%    |
| Russia      | 24        | 3.74%   |
| Greece      | 21        | 3.28%   |
| Canada      | 19        | 2.96%   |
| Argentina   | 15        | 2.34%   |
| Netherlands | 13        | 2.03%   |
| Switzerland | 11        | 1.72%   |
| Ukraine     | 10        | 1.56%   |
| Poland      | 8         | 1.25%   |
| Australia   | 8         | 1.25%   |
| Czechia     | 7         | 1.09%   |
| Indonesia   | 6         | 0.94%   |
| India       | 6         | 0.94%   |
| Hungary     | 6         | 0.94%   |
| Finland     | 6         | 0.94%   |
| Austria     | 6         | 0.94%   |
| Sweden      | 5         | 0.78%   |
| Norway      | 4         | 0.62%   |
| Mexico      | 4         | 0.62%   |
| Denmark     | 4         | 0.62%   |
| Belgium     | 4         | 0.62%   |
| Turkey      | 3         | 0.47%   |
| Taiwan      | 3         | 0.47%   |
| Croatia     | 3         | 0.47%   |
| Chile       | 3         | 0.47%   |
| Vietnam     | 2         | 0.31%   |
| Thailand    | 2         | 0.31%   |
| Portugal    | 2         | 0.31%   |
| Philippines | 2         | 0.31%   |
| Malaysia    | 2         | 0.31%   |
| Japan       | 2         | 0.31%   |
| Ireland     | 2         | 0.31%   |
| Estonia     | 2         | 0.31%   |
| Bulgaria    | 2         | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 71        | 10.66%  |
| Athens                | 14        | 2.1%    |
| Paris                 | 12        | 1.8%    |
| Berlin                | 10        | 1.5%    |
| Moscow                | 9         | 1.35%   |
| Rome                  | 5         | 0.75%   |
| Montpellier           | 5         | 0.75%   |
| Kyiv                  | 5         | 0.75%   |
| Barcelona             | 5         | 0.75%   |
| Thessaloniki          | 4         | 0.6%    |
| Manchester            | 4         | 0.6%    |
| Hamburg               | 4         | 0.6%    |
| Amsterdam             | 4         | 0.6%    |
| Zurich                | 3         | 0.45%   |
| Southampton           | 3         | 0.45%   |
| Sneek                 | 3         | 0.45%   |
| Saint-Cloud           | 3         | 0.45%   |
| Rio de Janeiro        | 3         | 0.45%   |
| Montreal              | 3         | 0.45%   |
| Melbourne             | 3         | 0.45%   |
| Madrid                | 3         | 0.45%   |
| Karlsruhe             | 3         | 0.45%   |
| Burnaby               | 3         | 0.45%   |
| Budapest              | 3         | 0.45%   |
| Zagreb                | 2         | 0.3%    |
| Yekaterinburg         | 2         | 0.3%    |
| Windsor               | 2         | 0.3%    |
| Vigo                  | 2         | 0.3%    |
| Vienna                | 2         | 0.3%    |
| Trondheim             | 2         | 0.3%    |
| The Hague             | 2         | 0.3%    |
| Tainan City           | 2         | 0.3%    |
| Singen                | 2         | 0.3%    |
| Seville               | 2         | 0.3%    |
| Sao José dos Pinhais | 2         | 0.3%    |
| Santeramo in Colle    | 2         | 0.3%    |
| San Diego             | 2         | 0.3%    |
| Samara                | 2         | 0.3%    |
| Prague                | 2         | 0.3%    |
| Porto Alegre          | 2         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 161       | 224    | 18.21%  |
| Seagate                   | 151       | 211    | 17.08%  |
| Samsung Electronics       | 117       | 163    | 13.24%  |
| Unknown                   | 66        | 82     | 7.47%   |
| Kingston                  | 58        | 73     | 6.56%   |
| Toshiba                   | 56        | 75     | 6.33%   |
| SanDisk                   | 40        | 49     | 4.52%   |
| Hitachi                   | 31        | 36     | 3.51%   |
| Crucial                   | 25        | 36     | 2.83%   |
| Intel                     | 23        | 29     | 2.6%    |
| SK hynix                  | 17        | 22     | 1.92%   |
| A-DATA Technology         | 15        | 17     | 1.7%    |
| HGST                      | 8         | 10     | 0.9%    |
| China                     | 8         | 9      | 0.9%    |
| Silicon Motion            | 6         | 7      | 0.68%   |
| PNY                       | 6         | 7      | 0.68%   |
| KIOXIA                    | 6         | 7      | 0.68%   |
| Phison                    | 5         | 5      | 0.57%   |
| Patriot                   | 5         | 7      | 0.57%   |
| Micron Technology         | 5         | 6      | 0.57%   |
| Transcend                 | 4         | 5      | 0.45%   |
| Intenso                   | 4         | 4      | 0.45%   |
| Apacer                    | 4         | 5      | 0.45%   |
| Maxtor                    | 3         | 7      | 0.34%   |
| LITEONIT                  | 3         | 4      | 0.34%   |
| LITEON                    | 3         | 3      | 0.34%   |
| JMicron Technology        | 3         | 6      | 0.34%   |
| Fujitsu                   | 3         | 3      | 0.34%   |
| SAGE                      | 2         | 2      | 0.23%   |
| SABRENT                   | 2         | 2      | 0.23%   |
| Micron/Crucial Technology | 2         | 4      | 0.23%   |
| KingSpec                  | 2         | 2      | 0.23%   |
| Hewlett-Packard           | 2         | 2      | 0.23%   |
| XPG                       | 1         | 1      | 0.11%   |
| X872                      | 1         | 1      | 0.11%   |
| Vaseky                    | 1         | 1      | 0.11%   |
| USB3.0                    | 1         | 1      | 0.11%   |
| Union Memory              | 1         | 1      | 0.11%   |
| UMIS                      | 1         | 1      | 0.11%   |
| TO Exter                  | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  32GB             | 15        | 1.56%   |
| Seagate ST500DM002-1BD142 500GB    | 14        | 1.46%   |
| Unknown MMC Card  64GB             | 13        | 1.35%   |
| Kingston SA400S37240G 240GB SSD    | 12        | 1.25%   |
| Kingston SA400S37120G 120GB SSD    | 12        | 1.25%   |
| Unknown MMC Card  16GB             | 8         | 0.83%   |
| Samsung SSD 860 EVO 500GB          | 8         | 0.83%   |
| Toshiba MQ01ABF050 500GB           | 7         | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB     | 7         | 0.73%   |
| WDC WD5000AAKX-083CA1 500GB        | 6         | 0.63%   |
| WDC WD5000AAKX-003CA0 500GB        | 6         | 0.63%   |
| Unknown MMC Card  128GB            | 6         | 0.63%   |
| Seagate ST3500418AS 500GB          | 6         | 0.63%   |
| Seagate ST320LT007-9ZV142 320GB    | 6         | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB     | 6         | 0.63%   |
| Toshiba DT01ACA100 1TB             | 5         | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB     | 5         | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB     | 5         | 0.52%   |
| Samsung HD322HJ 320GB              | 5         | 0.52%   |
| Kingston SV300S37A120G 120GB SSD   | 5         | 0.52%   |
| Kingston SA400S37480G 480GB SSD    | 5         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 4         | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB           | 4         | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB           | 4         | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4         | 0.42%   |
| Toshiba MQ04ABF100 1TB             | 4         | 0.42%   |
| Toshiba DT01ACA050 500GB           | 4         | 0.42%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB     | 4         | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 0.42%   |
| SanDisk SSD PLUS 480GB             | 4         | 0.42%   |
| Samsung SSD 850 EVO 500GB          | 4         | 0.42%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 0.42%   |
| Crucial CT500MX500SSD1 500GB       | 4         | 0.42%   |
| A-DATA SU650 120GB SSD             | 4         | 0.42%   |
| WDC WD2500AAKX-753CA1 250GB        | 3         | 0.31%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 3         | 0.31%   |
| WDC WD10SPZX-21Z10T0 1TB           | 3         | 0.31%   |
| WDC WD10EZEX-08M2NA0 1TB           | 3         | 0.31%   |
| Unknown DA4064  64GB               | 3         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 150       | 209    | 37.13%  |
| WDC                 | 132       | 181    | 32.67%  |
| Toshiba             | 47        | 65     | 11.63%  |
| Hitachi             | 31        | 36     | 7.67%   |
| Samsung Electronics | 24        | 27     | 5.94%   |
| HGST                | 8         | 10     | 1.98%   |
| Fujitsu             | 3         | 3      | 0.74%   |
| Unknown             | 2         | 2      | 0.5%    |
| Maxtor              | 2         | 5      | 0.5%    |
| USB3.0              | 1         | 1      | 0.25%   |
| LaCie               | 1         | 1      | 0.25%   |
| JMicron Technology  | 1         | 2      | 0.25%   |
| Hewlett-Packard     | 1         | 1      | 0.25%   |
| ASMT109x            | 1         | 2      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 62        | 85     | 22.3%   |
| Kingston            | 52        | 62     | 18.71%  |
| SanDisk             | 32        | 40     | 11.51%  |
| Crucial             | 23        | 34     | 8.27%   |
| WDC                 | 19        | 27     | 6.83%   |
| A-DATA Technology   | 12        | 14     | 4.32%   |
| Intel               | 10        | 15     | 3.6%    |
| China               | 8         | 9      | 2.88%   |
| PNY                 | 6         | 7      | 2.16%   |
| Transcend           | 4         | 5      | 1.44%   |
| Intenso             | 4         | 4      | 1.44%   |
| Apacer              | 4         | 5      | 1.44%   |
| Toshiba             | 3         | 3      | 1.08%   |
| Patriot             | 3         | 5      | 1.08%   |
| LITEONIT            | 3         | 4      | 1.08%   |
| SK hynix            | 2         | 4      | 0.72%   |
| Seagate             | 2         | 2      | 0.72%   |
| SAGE                | 2         | 2      | 0.72%   |
| Micron Technology   | 2         | 3      | 0.72%   |
| LITEON              | 2         | 2      | 0.72%   |
| KingSpec            | 2         | 2      | 0.72%   |
| Vaseky              | 1         | 1      | 0.36%   |
| TO Exter            | 1         | 1      | 0.36%   |
| SMI                 | 1         | 1      | 0.36%   |
| Smart               | 1         | 1      | 0.36%   |
| Ramos Technology    | 1         | 1      | 0.36%   |
| Plextor             | 1         | 1      | 0.36%   |
| OCZ                 | 1         | 1      | 0.36%   |
| Netac               | 1         | 1      | 0.36%   |
| Mushkin             | 1         | 1      | 0.36%   |
| Maxtor              | 1         | 2      | 0.36%   |
| Lexar               | 1         | 1      | 0.36%   |
| Leven               | 1         | 1      | 0.36%   |
| LDLC                | 1         | 1      | 0.36%   |
| HS-SSD-E100         | 1         | 1      | 0.36%   |
| FORESEE             | 1         | 1      | 0.36%   |
| Emtec               | 1         | 1      | 0.36%   |
| Dogfish             | 1         | 1      | 0.36%   |
| ASMT                | 1         | 2      | 0.36%   |
| AMD                 | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 350       | 545    | 43.91%  |
| SSD     | 245       | 358    | 30.74%  |
| NVMe    | 132       | 171    | 16.56%  |
| MMC     | 63        | 84     | 7.9%    |
| Unknown | 7         | 9      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 499       | 872    | 68.83%  |
| NVMe | 130       | 169    | 17.93%  |
| MMC  | 63        | 84     | 8.69%   |
| SAS  | 33        | 42     | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 389       | 550    | 61.36%  |
| 0.51-1.0   | 154       | 206    | 24.29%  |
| 1.01-2.0   | 54        | 74     | 8.52%   |
| 3.01-4.0   | 15        | 22     | 2.37%   |
| 4.01-10.0  | 12        | 27     | 1.89%   |
| 2.01-3.0   | 8         | 15     | 1.26%   |
| 10.01-20.0 | 2         | 9      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 183       | 27.77%  |
| 101-250        | 149       | 22.61%  |
| 501-1000       | 93        | 14.11%  |
| 1001-2000      | 55        | 8.35%   |
| 51-100         | 41        | 6.22%   |
| More than 3000 | 38        | 5.77%   |
| 21-50          | 31        | 4.7%    |
| 1-20           | 31        | 4.7%    |
| 2001-3000      | 26        | 3.95%   |
| Unknown        | 12        | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 232       | 34.27%  |
| 21-50          | 101       | 14.92%  |
| 101-250        | 100       | 14.77%  |
| 51-100         | 86        | 12.7%   |
| 251-500        | 62        | 9.16%   |
| 501-1000       | 34        | 5.02%   |
| 1001-2000      | 26        | 3.84%   |
| 2001-3000      | 14        | 2.07%   |
| Unknown        | 12        | 1.77%   |
| More than 3000 | 10        | 1.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 5         | 5      | 5.05%   |
| WDC WD5000AAKX-083CA1 500GB       | 4         | 4      | 4.04%   |
| Seagate ST320LT007-9ZV142 320GB   | 4         | 4      | 4.04%   |
| WDC WD5000AAKX-003CA0 500GB       | 2         | 2      | 2.02%   |
| WDC WD3200BEVT-60ZCT1 320GB       | 2         | 2      | 2.02%   |
| WDC WD2500AAKX-753CA1 250GB       | 2         | 2      | 2.02%   |
| Toshiba MK7559GSXP 752GB          | 2         | 2      | 2.02%   |
| Seagate ST3500418AS 500GB         | 2         | 2      | 2.02%   |
| Samsung Electronics HD502HJ 500GB | 2         | 2      | 2.02%   |
| WDC WD7500BPVT-75HXZT1 752GB      | 1         | 1      | 1.01%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1         | 1      | 1.01%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 1.01%   |
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 2      | 1.01%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1         | 1      | 1.01%   |
| WDC WD40EFAX-68JH4N0 4TB          | 1         | 2      | 1.01%   |
| WDC WD3200BEKT-60V5T1 320GB       | 1         | 1      | 1.01%   |
| WDC WD3200AAJS-40VWA1 320GB       | 1         | 1      | 1.01%   |
| WDC WD2500YS-01SHB1 256GB         | 1         | 1      | 1.01%   |
| WDC WD2500AAKX-75U6AA0 250GB      | 1         | 1      | 1.01%   |
| WDC WD2500AAJS-75M0A0 249GB       | 1         | 1      | 1.01%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1         | 1      | 1.01%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 2      | 1.01%   |
| WDC WD15EADS-00P8B0 1TB           | 1         | 1      | 1.01%   |
| WDC WD1200JD-00HBB0 120GB         | 1         | 1      | 1.01%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 1.01%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1         | 1      | 1.01%   |
| WDC WD10EFRX-68PJCN0 1TB          | 1         | 1      | 1.01%   |
| WDC WD10EARS-00MVWB0 1TB          | 1         | 1      | 1.01%   |
| WDC WD1001FALS-40Y6A0 1TB         | 1         | 1      | 1.01%   |
| Vaseky V820/1TB 1024GB            | 1         | 1      | 1.01%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 1.01%   |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 1.01%   |
| Toshiba MK5055GSX 500GB           | 1         | 1      | 1.01%   |
| Toshiba MK2565GSXN 250GB          | 1         | 1      | 1.01%   |
| Toshiba MK2555GSX 250GB           | 1         | 1      | 1.01%   |
| Toshiba DT01ACA100 1TB            | 1         | 1      | 1.01%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 1.01%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 1.01%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 1.01%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 1.01%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 33     | 31.96%  |
| WDC                 | 28        | 33     | 28.87%  |
| Toshiba             | 9         | 9      | 9.28%   |
| Samsung Electronics | 8         | 9      | 8.25%   |
| Hitachi             | 6         | 6      | 6.19%   |
| SanDisk             | 2         | 2      | 2.06%   |
| Intel               | 2         | 2      | 2.06%   |
| A-DATA Technology   | 2         | 4      | 2.06%   |
| Vaseky              | 1         | 1      | 1.03%   |
| OCZ                 | 1         | 1      | 1.03%   |
| Maxtor              | 1         | 1      | 1.03%   |
| Kingston            | 1         | 1      | 1.03%   |
| HGST                | 1         | 2      | 1.03%   |
| Fujitsu             | 1         | 1      | 1.03%   |
| Crucial             | 1         | 1      | 1.03%   |
| China               | 1         | 1      | 1.03%   |
| ASMT                | 1         | 2      | 1.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 33     | 37.35%  |
| WDC                 | 28        | 33     | 33.73%  |
| Toshiba             | 9         | 9      | 10.84%  |
| Samsung Electronics | 6         | 7      | 7.23%   |
| Hitachi             | 6         | 6      | 7.23%   |
| Maxtor              | 1         | 1      | 1.2%    |
| HGST                | 1         | 2      | 1.2%    |
| Fujitsu             | 1         | 1      | 1.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 80        | 92     | 86.02%  |
| SSD  | 13        | 17     | 13.98%  |

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
| Works    | 352       | 590    | 50.94%  |
| Detected | 249       | 468    | 36.03%  |
| Malfunc  | 90        | 109    | 13.02%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 433       | 60.39%  |
| AMD                              | 108       | 15.06%  |
| Samsung Electronics              | 36        | 5.02%   |
| SanDisk                          | 19        | 2.65%   |
| SK hynix                         | 14        | 1.95%   |
| Marvell Technology Group         | 13        | 1.81%   |
| ASMedia Technology               | 12        | 1.67%   |
| Nvidia                           | 11        | 1.53%   |
| Toshiba America Info Systems     | 9         | 1.26%   |
| Silicon Motion                   | 9         | 1.26%   |
| Phison Electronics               | 9         | 1.26%   |
| Kingston Technology Company      | 8         | 1.12%   |
| KIOXIA                           | 5         | 0.7%    |
| Micron/Crucial Technology        | 4         | 0.56%   |
| JMicron Technology               | 4         | 0.56%   |
| ADATA Technology                 | 4         | 0.56%   |
| Micron Technology                | 3         | 0.42%   |
| LSI Logic / Symbios Logic        | 3         | 0.42%   |
| VIA Technologies                 | 2         | 0.28%   |
| Union Memory (Shenzhen)          | 2         | 0.28%   |
| Silicon Integrated Systems [SiS] | 2         | 0.28%   |
| Hewlett-Packard                  | 2         | 0.28%   |
| Solid State Storage Technology   | 1         | 0.14%   |
| Realtek Semiconductor            | 1         | 0.14%   |
| Lite-On Technology               | 1         | 0.14%   |
| Integrated Technology Express    | 1         | 0.14%   |
| 3ware                            | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 59        | 6.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 39        | 4.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 35        | 4.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 30        | 3.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26        | 3.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 25        | 2.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23        | 2.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21        | 2.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 20        | 2.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 19        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 19        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18        | 2.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17        | 1.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 16        | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 15        | 1.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13        | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 1.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10        | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 9         | 1.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 8         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 0.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7         | 0.82%   |
| SK hynix BC511 NVMe SSD                                                                 | 6         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6         | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 6         | 0.7%    |
| Samsung NVMe SSD Controller 980                                                         | 6         | 0.7%    |
| Nvidia MCP61 SATA Controller                                                            | 6         | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 0.7%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 450       | 61.31%  |
| NVMe | 128       | 17.44%  |
| IDE  | 113       | 15.4%   |
| RAID | 38        | 5.18%   |
| SAS  | 5         | 0.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 478       | 75.04%  |
| AMD    | 123       | 19.31%  |
| ARM    | 36        | 5.65%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Processor                           | 30        | 4.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 10        | 1.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 7         | 1.1%    |
| AMD Phenom II X4 B97 Processor          | 7         | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 6         | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 0.94%   |
| Intel Pentium 4 CPU 3.00GHz             | 5         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 5         | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 5         | 0.78%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 5         | 0.78%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 5         | 0.78%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 5         | 0.78%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 5         | 0.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 0.78%   |
| Intel Pentium D CPU 2.80GHz             | 4         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 0.63%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 4         | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 0.63%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 4         | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 0.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 4         | 0.63%   |
| Intel Core i5-2500 CPU @ 3.30GHz        | 4         | 0.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 0.63%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz    | 4         | 0.63%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 4         | 0.63%   |
| ARM BCM2835 Processor                   | 4         | 0.63%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4         | 0.63%   |
| AMD FX-8350 Eight-Core Processor        | 4         | 0.63%   |
| Intel Pentium CPU N3540 @ 2.16GHz       | 3         | 0.47%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 0.47%   |
| Intel Core i7-3930K CPU @ 3.20GHz       | 3         | 0.47%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 3         | 0.47%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 3         | 0.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 0.47%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 3         | 0.47%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 3         | 0.47%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 3         | 0.47%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 3         | 0.47%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 3         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 139       | 21.82%  |
| Intel Core i7                  | 106       | 16.64%  |
| Other                          | 55        | 8.63%   |
| Intel Core i3                  | 53        | 8.32%   |
| Intel Core 2 Duo               | 33        | 5.18%   |
| Intel Celeron                  | 25        | 3.92%   |
| Intel Pentium                  | 24        | 3.77%   |
| AMD Ryzen 5                    | 20        | 3.14%   |
| Intel Xeon                     | 18        | 2.83%   |
| AMD Ryzen 7                    | 16        | 2.51%   |
| AMD FX                         | 14        | 2.2%    |
| AMD Phenom II X4               | 11        | 1.73%   |
| Intel Core 2 Quad              | 10        | 1.57%   |
| Intel Atom                     | 10        | 1.57%   |
| Intel Pentium Dual-Core        | 9         | 1.41%   |
| AMD Ryzen 9                    | 8         | 1.26%   |
| AMD Athlon II X2               | 7         | 1.1%    |
| Intel Pentium 4                | 5         | 0.78%   |
| Intel Pentium D                | 4         | 0.63%   |
| Intel Core 2                   | 4         | 0.63%   |
| ARM BCM                        | 4         | 0.63%   |
| AMD Ryzen 3                    | 4         | 0.63%   |
| AMD A8                         | 4         | 0.63%   |
| AMD A6                         | 4         | 0.63%   |
| AMD A4                         | 4         | 0.63%   |
| Intel Pentium Silver           | 3         | 0.47%   |
| Intel Pentium Dual             | 3         | 0.47%   |
| Intel Core m3                  | 3         | 0.47%   |
| AMD Ryzen Threadripper         | 3         | 0.47%   |
| AMD Athlon                     | 3         | 0.47%   |
| Intel Genuine                  | 2         | 0.31%   |
| Intel Core M                   | 2         | 0.31%   |
| Intel Core i9                  | 2         | 0.31%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.31%   |
| AMD Ryzen 7 PRO                | 2         | 0.31%   |
| AMD Ryzen 5 PRO                | 2         | 0.31%   |
| AMD Athlon II X4               | 2         | 0.31%   |
| Intel Xeon Silver              | 1         | 0.16%   |
| Intel Core 2 Extreme           | 1         | 0.16%   |
| Intel Celeron Dual-Core        | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 268       | 42.01%  |
| 4      | 258       | 40.44%  |
| 6      | 48        | 7.52%   |
| 8      | 31        | 4.86%   |
| 1      | 10        | 1.57%   |
| 16     | 7         | 1.1%    |
| 12     | 7         | 1.1%    |
| 3      | 4         | 0.63%   |
| 24     | 2         | 0.31%   |
| 32     | 1         | 0.16%   |
| 14     | 1         | 0.16%   |
| 10     | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 620       | 97.33%  |
| 2      | 16        | 2.51%   |
| 4      | 1         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 365       | 57.21%  |
| 1      | 273       | 42.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 610       | 95.61%  |
| Unknown        | 27        | 4.23%   |
| 64-bit         | 1         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 15.24%  |
| 0x306a9    | 56        | 8.71%   |
| 0x206a7    | 54        | 8.4%    |
| 0x306c3    | 39        | 6.07%   |
| 0x1067a    | 30        | 4.67%   |
| 0x010000c8 | 16        | 2.49%   |
| 0x6fd      | 14        | 2.18%   |
| 0x306d4    | 14        | 2.18%   |
| 0x806ec    | 13        | 2.02%   |
| 0x806e9    | 13        | 2.02%   |
| 0x906ea    | 11        | 1.71%   |
| 0x906e9    | 10        | 1.56%   |
| 0x40651    | 10        | 1.56%   |
| 0x806c1    | 9         | 1.4%    |
| 0x506e3    | 9         | 1.4%    |
| 0x406c4    | 9         | 1.4%    |
| 0x20655    | 9         | 1.4%    |
| 0x08701021 | 9         | 1.4%    |
| 0x06000852 | 9         | 1.4%    |
| 0x806ea    | 8         | 1.24%   |
| 0x406e3    | 8         | 1.24%   |
| 0x30678    | 8         | 1.24%   |
| 0x106e5    | 8         | 1.24%   |
| 0x706e5    | 7         | 1.09%   |
| 0x6fb      | 7         | 1.09%   |
| 0x08600106 | 7         | 1.09%   |
| 0x20652    | 6         | 0.93%   |
| 0x08108102 | 6         | 0.93%   |
| 0xa0671    | 5         | 0.78%   |
| 0x706a1    | 5         | 0.78%   |
| 0x10676    | 5         | 0.78%   |
| 0x08701013 | 5         | 0.78%   |
| 0xf41      | 4         | 0.62%   |
| 0xa0653    | 4         | 0.62%   |
| 0x906ed    | 4         | 0.62%   |
| 0x6f6      | 4         | 0.62%   |
| 0x206d7    | 4         | 0.62%   |
| 0x08108109 | 4         | 0.62%   |
| 0x0800820d | 4         | 0.62%   |
| 0x06006705 | 4         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 74        | 11.62%  |
| SandyBridge      | 66        | 10.36%  |
| IvyBridge        | 61        | 9.58%   |
| Haswell          | 59        | 9.26%   |
| Penryn           | 39        | 6.12%   |
| Unknown          | 39        | 6.12%   |
| Core             | 28        | 4.4%    |
| Zen 2            | 25        | 3.92%   |
| K10              | 25        | 3.92%   |
| Silvermont       | 23        | 3.61%   |
| Skylake          | 22        | 3.45%   |
| Westmere         | 17        | 2.67%   |
| Broadwell        | 17        | 2.67%   |
| Piledriver       | 16        | 2.51%   |
| Zen+             | 14        | 2.2%    |
| Icelake          | 14        | 2.2%    |
| Zen              | 13        | 2.04%   |
| Nehalem          | 11        | 1.73%   |
| CometLake        | 11        | 1.73%   |
| TigerLake        | 9         | 1.41%   |
| NetBurst         | 9         | 1.41%   |
| Goldmont plus    | 8         | 1.26%   |
| Zen 3            | 6         | 0.94%   |
| Excavator        | 6         | 0.94%   |
| Puma             | 5         | 0.78%   |
| Goldmont         | 4         | 0.63%   |
| K8 & K10 hybrid  | 3         | 0.47%   |
| Steamroller      | 2         | 0.31%   |
| K8 Hammer        | 2         | 0.31%   |
| Bulldozer        | 2         | 0.31%   |
| Bonnell          | 2         | 0.31%   |
| Bobcat           | 2         | 0.31%   |
| Alderlake Hybrid | 2         | 0.31%   |
| Jaguar           | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 376       | 53.87%  |
| Nvidia                           | 162       | 23.21%  |
| AMD                              | 153       | 21.92%  |
| Matrox Electronics Systems       | 3         | 0.43%   |
| ASPEED Technology                | 3         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 6.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 4.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 18        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 2.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 1.97%   |
| Intel HD Graphics 5500                                                                   | 14        | 1.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 14        | 1.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.4%    |
| AMD RS880 [Radeon HD 4200]                                                               | 10        | 1.4%    |
| Intel UHD Graphics 620                                                                   | 9         | 1.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.26%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 9         | 1.26%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 1.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 8         | 1.12%   |
| AMD Renoir                                                                               | 8         | 1.12%   |
| Nvidia GT218 [GeForce 210]                                                               | 7         | 0.98%   |
| Intel HD Graphics 620                                                                    | 7         | 0.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 0.98%   |
| Intel HD Graphics 630                                                                    | 6         | 0.84%   |
| Intel HD Graphics 530                                                                    | 6         | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 0.84%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 0.84%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 5         | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 288       | 45.14%  |
| 1 x AMD                  | 125       | 19.59%  |
| 1 x Nvidia               | 92        | 14.42%  |
| Intel + Nvidia           | 64        | 10.03%  |
| Other                    | 36        | 5.64%   |
| Intel + AMD              | 17        | 2.66%   |
| 2 x AMD                  | 5         | 0.78%   |
| 1 x Matrox               | 3         | 0.47%   |
| AMD + Nvidia             | 2         | 0.31%   |
| 2 x Nvidia               | 1         | 0.16%   |
| 1 x SiS                  | 1         | 0.16%   |
| Nvidia + ASPEED          | 1         | 0.16%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.16%   |
| 1 x ASPEED               | 1         | 0.16%   |
| AMD + ASPEED             | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 484       | 75.51%  |
| Proprietary | 105       | 16.38%  |
| Unknown     | 52        | 8.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 387       | 60%     |
| 0.01-0.5   | 70        | 10.85%  |
| 1.01-2.0   | 64        | 9.92%   |
| 0.51-1.0   | 56        | 8.68%   |
| 3.01-4.0   | 30        | 4.65%   |
| 7.01-8.0   | 22        | 3.41%   |
| 5.01-6.0   | 9         | 1.4%    |
| 2.01-3.0   | 4         | 0.62%   |
| 16.01-24.0 | 3         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 95        | 14.37%  |
| Dell                    | 87        | 13.16%  |
| AU Optronics            | 69        | 10.44%  |
| LG Display              | 61        | 9.23%   |
| Chimei Innolux          | 48        | 7.26%   |
| BOE                     | 32        | 4.84%   |
| Goldstar                | 31        | 4.69%   |
| Philips                 | 24        | 3.63%   |
| Hewlett-Packard         | 23        | 3.48%   |
| BenQ                    | 15        | 2.27%   |
| Ancor Communications    | 15        | 2.27%   |
| Acer                    | 14        | 2.12%   |
| Chi Mei Optoelectronics | 13        | 1.97%   |
| AOC                     | 12        | 1.82%   |
| ViewSonic               | 9         | 1.36%   |
| Unknown                 | 8         | 1.21%   |
| PANDA                   | 8         | 1.21%   |
| Lenovo                  | 7         | 1.06%   |
| Iiyama                  | 7         | 1.06%   |
| Sharp                   | 6         | 0.91%   |
| Apple                   | 5         | 0.76%   |
| Vizio                   | 4         | 0.61%   |
| NEC Computers           | 4         | 0.61%   |
| LG Philips              | 4         | 0.61%   |
| HannStar                | 4         | 0.61%   |
| Sony                    | 3         | 0.45%   |
| Medion                  | 3         | 0.45%   |
| InnoLux Display         | 3         | 0.45%   |
| Belinea                 | 3         | 0.45%   |
| Vestel Elektronik       | 2         | 0.3%    |
| Toshiba                 | 2         | 0.3%    |
| LG Electronics          | 2         | 0.3%    |
| Insignia                | 2         | 0.3%    |
| Gateway                 | 2         | 0.3%    |
| Fujitsu Siemens         | 2         | 0.3%    |
| Eizo                    | 2         | 0.3%    |
| CSO                     | 2         | 0.3%    |
| ___                     | 1         | 0.15%   |
| VIZ                     | 1         | 0.15%   |
| Targa                   | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                        | 31        | 4.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.87%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                        | 5         | 0.73%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch            | 4         | 0.58%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.58%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.44%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch        | 3         | 0.44%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 3         | 0.44%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 0.44%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 3         | 0.44%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                        | 3         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.44%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.44%   |
| Vizio VA26LHDTV10T VIZ0035 1920x1080 640x360mm 28.9-inch                 | 2         | 0.29%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 2         | 0.29%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                        | 2         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch        | 2         | 0.29%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                  | 2         | 0.29%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.29%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.29%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.29%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.29%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 2         | 0.29%   |
| Iiyama PL2740HS IVM6662 1920x1080 598x336mm 27.0-inch                    | 2         | 0.29%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch              | 2         | 0.29%   |
| Goldstar W2253 GSM56DB 1920x1080 477x268mm 21.5-inch                     | 2         | 0.29%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 2         | 0.29%   |
| Goldstar E2340 GSM57A6 1920x1080 510x290mm 23.1-inch                     | 2         | 0.29%   |
| Goldstar 23LC1R GSM5617 1360x768 930x523mm 42.0-inch                     | 2         | 0.29%   |
| Dell U3415W DELA0A6 3440x1440 798x335mm 34.1-inch                        | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 228       | 35.63%  |
| 1366x768 (WXGA)    | 136       | 21.25%  |
| 1280x1024 (SXGA)   | 63        | 9.84%   |
| 1600x900 (HD+)     | 32        | 5%      |
| 3840x2160 (4K)     | 28        | 4.38%   |
| 2560x1440 (QHD)    | 24        | 3.75%   |
| 1440x900 (WXGA+)   | 21        | 3.28%   |
| 1680x1050 (WSXGA+) | 19        | 2.97%   |
| 1920x1200 (WUXGA)  | 17        | 2.66%   |
| 1280x800 (WXGA)    | 16        | 2.5%    |
| 1360x768           | 14        | 2.19%   |
| Unknown            | 9         | 1.41%   |
| 3440x1440          | 5         | 0.78%   |
| 1600x1200          | 5         | 0.78%   |
| 3200x1800 (QHD+)   | 2         | 0.31%   |
| 2560x1600          | 2         | 0.31%   |
| 6400x1080          | 1         | 0.16%   |
| 5360x1440          | 1         | 0.16%   |
| 5040x1050          | 1         | 0.16%   |
| 4240x1440          | 1         | 0.16%   |
| 3840x1200          | 1         | 0.16%   |
| 3840x1080          | 1         | 0.16%   |
| 3520x1200          | 1         | 0.16%   |
| 3000x1920          | 1         | 0.16%   |
| 2880x1800          | 1         | 0.16%   |
| 2736x1824          | 1         | 0.16%   |
| 2640x1024          | 1         | 0.16%   |
| 2160x1440          | 1         | 0.16%   |
| 1920x540           | 1         | 0.16%   |
| 1680x945           | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1280x720 (HD)      | 1         | 0.16%   |
| 1152x864           | 1         | 0.16%   |
| 1024x768 (XGA)     | 1         | 0.16%   |
| 1024x600           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 147       | 22.21%  |
| 17      | 85        | 12.84%  |
| 13      | 48        | 7.25%   |
| 14      | 46        | 6.95%   |
| 24      | 43        | 6.5%    |
| Unknown | 41        | 6.19%   |
| 21      | 38        | 5.74%   |
| 23      | 35        | 5.29%   |
| 27      | 31        | 4.68%   |
| 18      | 24        | 3.63%   |
| 19      | 18        | 2.72%   |
| 22      | 17        | 2.57%   |
| 12      | 14        | 2.11%   |
| 31      | 11        | 1.66%   |
| 11      | 10        | 1.51%   |
| 84      | 6         | 0.91%   |
| 72      | 6         | 0.91%   |
| 20      | 6         | 0.91%   |
| 34      | 4         | 0.6%    |
| 10      | 4         | 0.6%    |
| 52      | 3         | 0.45%   |
| 46      | 3         | 0.45%   |
| 40      | 3         | 0.45%   |
| 36      | 3         | 0.45%   |
| 25      | 3         | 0.45%   |
| 42      | 2         | 0.3%    |
| 33      | 2         | 0.3%    |
| 32      | 2         | 0.3%    |
| 65      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 48      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 29      | 1         | 0.15%   |
| 16      | 1         | 0.15%   |
| 8       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 266       | 40.74%  |
| 501-600     | 104       | 15.93%  |
| 401-500     | 92        | 14.09%  |
| 201-300     | 50        | 7.66%   |
| 351-400     | 47        | 7.2%    |
| Unknown     | 41        | 6.28%   |
| 601-700     | 14        | 2.14%   |
| 1501-2000   | 12        | 1.84%   |
| 701-800     | 11        | 1.68%   |
| 1001-1500   | 9         | 1.38%   |
| 801-900     | 4         | 0.61%   |
| 901-1000    | 2         | 0.31%   |
| 101-200     | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 426       | 69.38%  |
| 16/10   | 74        | 12.05%  |
| 5/4     | 55        | 8.96%   |
| Unknown | 33        | 5.37%   |
| 4/3     | 8         | 1.3%    |
| 3/2     | 8         | 1.3%    |
| 6/5     | 4         | 0.65%   |
| 21/9    | 4         | 0.65%   |
| 1.96    | 1         | 0.16%   |
| 0.62    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 142       | 21.65%  |
| 201-250        | 102       | 15.55%  |
| 81-90          | 73        | 11.13%  |
| 141-150        | 72        | 10.98%  |
| Unknown        | 41        | 6.25%   |
| 151-200        | 36        | 5.49%   |
| 301-350        | 31        | 4.73%   |
| 121-130        | 23        | 3.51%   |
| 251-300        | 22        | 3.35%   |
| 71-80          | 21        | 3.2%    |
| 351-500        | 18        | 2.74%   |
| More than 1000 | 17        | 2.59%   |
| 61-70          | 14        | 2.13%   |
| 501-1000       | 13        | 1.98%   |
| 51-60          | 10        | 1.52%   |
| 131-140        | 10        | 1.52%   |
| 111-120        | 5         | 0.76%   |
| 41-50          | 4         | 0.61%   |
| 1-40           | 1         | 0.15%   |
| 91-100         | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 244       | 38.13%  |
| 101-120       | 172       | 26.88%  |
| 121-160       | 124       | 19.38%  |
| Unknown       | 41        | 6.41%   |
| 161-240       | 28        | 4.38%   |
| 1-50          | 21        | 3.28%   |
| More than 240 | 10        | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 522       | 80.93%  |
| 2     | 83        | 12.87%  |
| 0     | 31        | 4.81%   |
| 3     | 9         | 1.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 313       | 34.7%   |
| Intel                             | 284       | 31.49%  |
| Qualcomm Atheros                  | 100       | 11.09%  |
| Broadcom                          | 69        | 7.65%   |
| Broadcom Limited                  | 16        | 1.77%   |
| Ralink Technology                 | 14        | 1.55%   |
| Ralink                            | 12        | 1.33%   |
| TP-Link                           | 10        | 1.11%   |
| Marvell Technology Group          | 10        | 1.11%   |
| Nvidia                            | 9         | 1%      |
| Xiaomi                            | 5         | 0.55%   |
| Qualcomm Atheros Communications   | 5         | 0.55%   |
| Microchip Technology              | 5         | 0.55%   |
| Aquantia                          | 5         | 0.55%   |
| Sierra Wireless                   | 4         | 0.44%   |
| ASUSTek Computer                  | 4         | 0.44%   |
| ASIX Electronics                  | 4         | 0.44%   |
| Samsung Electronics               | 3         | 0.33%   |
| NetGear                           | 3         | 0.33%   |
| Edimax Technology                 | 3         | 0.33%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.22%   |
| Linksys                           | 2         | 0.22%   |
| Ericsson Business Mobile Networks | 2         | 0.22%   |
| D-Link System                     | 2         | 0.22%   |
| ZyDAS                             | 1         | 0.11%   |
| Tenda                             | 1         | 0.11%   |
| STMicroelectronics                | 1         | 0.11%   |
| Sitecom Europe                    | 1         | 0.11%   |
| Qualcomm                          | 1         | 0.11%   |
| QLogic                            | 1         | 0.11%   |
| Netchip Technology                | 1         | 0.11%   |
| Microsoft                         | 1         | 0.11%   |
| MediaTek                          | 1         | 0.11%   |
| Lenovo                            | 1         | 0.11%   |
| Huawei Technologies               | 1         | 0.11%   |
| Hewlett-Packard                   | 1         | 0.11%   |
| Fibocom                           | 1         | 0.11%   |
| Dell                              | 1         | 0.11%   |
| Belkin Components                 | 1         | 0.11%   |
| Attansic Technology               | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 210       | 19.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 4.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45        | 4.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 1.8%    |
| Intel Wi-Fi 6 AX200                                               | 18        | 1.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17        | 1.61%   |
| Intel Wireless 7265                                               | 17        | 1.61%   |
| Intel Wireless 7260                                               | 17        | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 16        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 16        | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 14        | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 1.23%   |
| Intel Wireless 3165                                               | 13        | 1.23%   |
| Intel I211 Gigabit Network Connection                             | 13        | 1.23%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 0.95%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 0.66%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                   | 6         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 6         | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 6         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 0.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 6         | 0.57%   |
| Intel Centrino Advanced-N 6235                                    | 6         | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.57%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 6         | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 190       | 42.79%  |
| Qualcomm Atheros                | 79        | 17.79%  |
| Realtek Semiconductor           | 69        | 15.54%  |
| Broadcom                        | 27        | 6.08%   |
| Ralink Technology               | 14        | 3.15%   |
| Ralink                          | 12        | 2.7%    |
| Broadcom Limited                | 12        | 2.7%    |
| TP-Link                         | 10        | 2.25%   |
| Qualcomm Atheros Communications | 5         | 1.13%   |
| Sierra Wireless                 | 4         | 0.9%    |
| ASUSTek Computer                | 4         | 0.9%    |
| NetGear                         | 3         | 0.68%   |
| Edimax Technology               | 3         | 0.68%   |
| Linksys                         | 2         | 0.45%   |
| ZyDAS                           | 1         | 0.23%   |
| Xiaomi                          | 1         | 0.23%   |
| Sitecom Europe                  | 1         | 0.23%   |
| Qualcomm                        | 1         | 0.23%   |
| Microsoft                       | 1         | 0.23%   |
| MediaTek                        | 1         | 0.23%   |
| Hewlett-Packard                 | 1         | 0.23%   |
| Fibocom                         | 1         | 0.23%   |
| Dell                            | 1         | 0.23%   |
| Belkin Components               | 1         | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 18        | 4.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 3.83%   |
| Intel Wireless 7265                                                     | 17        | 3.83%   |
| Intel Wireless 7260                                                     | 17        | 3.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 3.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 3.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.93%   |
| Intel Wireless 3165                                                     | 13        | 2.93%   |
| Intel Wireless 8265 / 8275                                              | 11        | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.58%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.58%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 6         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 1.35%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.35%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.13%   |
| Ralink RT5370 Wireless Adapter                                          | 5         | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.13%   |
| Intel Wireless 8260                                                     | 5         | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.13%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.9%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 4         | 0.9%    |
| Realtek 802.11ac NIC                                                    | 4         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.9%    |
| Intel Wireless-AC 9260                                                  | 4         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.9%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 3         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 290       | 49.15%  |
| Intel                            | 173       | 29.32%  |
| Broadcom                         | 45        | 7.63%   |
| Qualcomm Atheros                 | 28        | 4.75%   |
| Marvell Technology Group         | 10        | 1.69%   |
| Nvidia                           | 9         | 1.53%   |
| Microchip Technology             | 5         | 0.85%   |
| Broadcom Limited                 | 5         | 0.85%   |
| Aquantia                         | 5         | 0.85%   |
| Xiaomi                           | 4         | 0.68%   |
| ASIX Electronics                 | 4         | 0.68%   |
| Silicon Integrated Systems [SiS] | 2         | 0.34%   |
| Samsung Electronics              | 2         | 0.34%   |
| D-Link System                    | 2         | 0.34%   |
| Tenda                            | 1         | 0.17%   |
| QLogic                           | 1         | 0.17%   |
| Netchip Technology               | 1         | 0.17%   |
| Lenovo                           | 1         | 0.17%   |
| Huawei Technologies              | 1         | 0.17%   |
| Attansic Technology              | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 210       | 34.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 7.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45        | 7.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 3.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 2.79%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 2.3%    |
| Intel I211 Gigabit Network Connection                             | 13        | 2.13%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10        | 1.64%   |
| Intel Ethernet Connection I217-V                                  | 7         | 1.15%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.98%   |
| Nvidia MCP61 Ethernet                                             | 6         | 0.98%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.98%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.98%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 6         | 0.98%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 5         | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.82%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.82%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 5         | 0.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.66%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.49%   |
| Intel 82578DM Gigabit Network Connection                          | 3         | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.49%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 3         | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 557       | 56.89%  |
| WiFi     | 418       | 42.7%   |
| Modem    | 4         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 327       | 51.58%  |
| Ethernet | 307       | 48.42%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 316       | 49.3%   |
| 1     | 269       | 41.97%  |
| 0     | 40        | 6.24%   |
| 3     | 11        | 1.72%   |
| 4     | 3         | 0.47%   |
| 14    | 1         | 0.16%   |
| 6     | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 555       | 86.45%  |
| Yes  | 87        | 13.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 149       | 47%     |
| Qualcomm Atheros Communications | 31        | 9.78%   |
| Realtek Semiconductor           | 28        | 8.83%   |
| Broadcom                        | 27        | 8.52%   |
| Cambridge Silicon Radio         | 23        | 7.26%   |
| Dell                            | 13        | 4.1%    |
| IMC Networks                    | 11        | 3.47%   |
| Lite-On Technology              | 10        | 3.15%   |
| ASUSTek Computer                | 7         | 2.21%   |
| Apple                           | 5         | 1.58%   |
| Foxconn / Hon Hai               | 4         | 1.26%   |
| Ralink                          | 3         | 0.95%   |
| Ralink Technology               | 2         | 0.63%   |
| Toshiba                         | 1         | 0.32%   |
| Foxconn International           | 1         | 0.32%   |
| Conwise Technology              | 1         | 0.32%   |
| Belkin Components               | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 68        | 21.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 25        | 7.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 7.26%   |
| Intel AX201 Bluetooth                               | 19        | 5.99%   |
| Realtek Bluetooth Radio                             | 16        | 5.05%   |
| Intel AX200 Bluetooth                               | 16        | 5.05%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 3.15%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 2.84%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 2.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 2.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 2.21%   |
| IMC Networks Bluetooth Device                       | 7         | 2.21%   |
| Dell DW375 Bluetooth Module                         | 7         | 2.21%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 1.89%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 1.26%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 1.26%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 1.26%   |
| Ralink RT3290 Bluetooth                             | 3         | 0.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.95%   |
| Lite-On Bluetooth Device                            | 3         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3         | 0.95%   |
| Apple Bluetooth HCI                                 | 3         | 0.95%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.63%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.63%   |
| Intel AX210 Bluetooth                               | 2         | 0.63%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.63%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 2         | 0.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.63%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.63%   |
| ASUS ASUS USB-BT500                                 | 2         | 0.63%   |
| Toshiba Bluetooth Radio                             | 1         | 0.32%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 457       | 56.49%  |
| AMD                                            | 153       | 18.91%  |
| Nvidia                                         | 132       | 16.32%  |
| C-Media Electronics                            | 12        | 1.48%   |
| Logitech                                       | 6         | 0.74%   |
| Realtek Semiconductor                          | 5         | 0.62%   |
| Lenovo                                         | 3         | 0.37%   |
| Kingston Technology                            | 3         | 0.37%   |
| Generalplus Technology                         | 3         | 0.37%   |
| Corsair                                        | 3         | 0.37%   |
| Silicon Integrated Systems [SiS]               | 2         | 0.25%   |
| Razer USA                                      | 2         | 0.25%   |
| Plantronics                                    | 2         | 0.25%   |
| JMTek                                          | 2         | 0.25%   |
| Jieli Technology                               | 2         | 0.25%   |
| Hewlett-Packard                                | 2         | 0.25%   |
| GN Netcom                                      | 2         | 0.25%   |
| Creative Labs                                  | 2         | 0.25%   |
| XMOS                                           | 1         | 0.12%   |
| Thesycon Systemsoftware & Consulting           | 1         | 0.12%   |
| Sony                                           | 1         | 0.12%   |
| Siemens Information and Communication Products | 1         | 0.12%   |
| No brand                                       | 1         | 0.12%   |
| Micro Star International                       | 1         | 0.12%   |
| Meizu                                          | 1         | 0.12%   |
| Focusrite-Novation                             | 1         | 0.12%   |
| FiiO Electronics Technology                    | 1         | 0.12%   |
| Elite Silicon                                  | 1         | 0.12%   |
| Dell                                           | 1         | 0.12%   |
| Creative Technology                            | 1         | 0.12%   |
| Conexant Systems                               | 1         | 0.12%   |
| BEHRINGER International                        | 1         | 0.12%   |
| ASUSTek Computer                               | 1         | 0.12%   |
| Alesis                                         | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 63        | 6.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 57        | 5.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 40        | 4.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 39        | 4.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 33        | 3.46%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 31        | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 29        | 3.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 25        | 2.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 2.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 1.78%   |
| Intel Broadwell-U Audio Controller                                                                | 17        | 1.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 1.68%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 16        | 1.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 1.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 13        | 1.36%   |
| AMD FCH Azalia Controller                                                                         | 13        | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 1.26%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 1.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 1.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 1.26%   |
| Nvidia High Definition Audio Controller                                                           | 11        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 0.94%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 8         | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 8         | 0.84%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 0.84%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 8         | 0.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 8         | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 93        | 17.88%  |
| Kingston                                         | 78        | 15%     |
| SK hynix                                         | 75        | 14.42%  |
| Unknown                                          | 68        | 13.08%  |
| Micron Technology                                | 40        | 7.69%   |
| Crucial                                          | 29        | 5.58%   |
| Corsair                                          | 25        | 4.81%   |
| G.Skill                                          | 17        | 3.27%   |
| Ramaxel Technology                               | 12        | 2.31%   |
| Nanya Technology                                 | 12        | 2.31%   |
| Elpida                                           | 12        | 2.31%   |
| Smart                                            | 10        | 1.92%   |
| A-DATA Technology                                | 8         | 1.54%   |
| Unknown (ABCD)                                   | 5         | 0.96%   |
| Patriot                                          | 5         | 0.96%   |
| Teikon                                           | 4         | 0.77%   |
| Team                                             | 4         | 0.77%   |
| Qimonda                                          | 2         | 0.38%   |
| Netlist                                          | 2         | 0.38%   |
| HBS                                              | 2         | 0.38%   |
| GOODRAM                                          | 2         | 0.38%   |
| Unknown                                          | 2         | 0.38%   |
| Unknown (9B0D)                                   | 1         | 0.19%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.19%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.19%   |
| Unknown (00FFFFFFFFFFFFFF)                       | 1         | 0.19%   |
| Transcend                                        | 1         | 0.19%   |
| Toshiba                                          | 1         | 0.19%   |
| Kreton                                           | 1         | 0.19%   |
| Goldenmars                                       | 1         | 0.19%   |
| Golden Empire                                    | 1         | 0.19%   |
| GeIL                                             | 1         | 0.19%   |
| Atermiter                                        | 1         | 0.19%   |
| ASint Technology                                 | 1         | 0.19%   |
| Apacer                                           | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 7         | 1.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 6         | 1.08%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                     | 6         | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 0.9%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s             | 5         | 0.9%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 4         | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                        | 4         | 0.72%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                  | 4         | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 4         | 0.72%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                           | 3         | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 3         | 0.54%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s             | 3         | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s          | 3         | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 3         | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s             | 3         | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.54%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.54%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                      | 3         | 0.54%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 3         | 0.54%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s             | 3         | 0.54%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s           | 3         | 0.54%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s         | 3         | 0.54%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                      | 2         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                    | 2         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR3                             | 2         | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                      | 2         | 0.36%   |
| Unknown RAM Module 2048MB SODIMM DRAM                             | 2         | 0.36%   |
| Unknown RAM Module 2048MB DIMM SDRAM                              | 2         | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s                      | 2         | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 2         | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                       | 2         | 0.36%   |
| Unknown RAM Module 1024MB DIMM SDRAM                              | 2         | 0.36%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s                        | 2         | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2         | 0.36%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                | 2         | 0.36%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.36%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 2         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 200       | 44.54%  |
| DDR4    | 139       | 30.96%  |
| DDR2    | 36        | 8.02%   |
| SDRAM   | 22        | 4.9%    |
| Unknown | 16        | 3.56%   |
| LPDDR3  | 12        | 2.67%   |
| LPDDR4  | 11        | 2.45%   |
| DDR     | 9         | 2%      |
| DRAM    | 3         | 0.67%   |
| DDR5    | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 229       | 52.16%  |
| DIMM         | 185       | 42.14%  |
| Row Of Chips | 21        | 4.78%   |
| Chip         | 3         | 0.68%   |
| RIMM         | 1         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 153       | 31.55%  |
| 8192  | 142       | 29.28%  |
| 2048  | 96        | 19.79%  |
| 16384 | 54        | 11.13%  |
| 32768 | 19        | 3.92%   |
| 1024  | 19        | 3.92%   |
| 1536  | 1         | 0.21%   |
| 512   | 1         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 119       | 24.74%  |
| 1333    | 54        | 11.23%  |
| 2667    | 52        | 10.81%  |
| 3200    | 45        | 9.36%   |
| 2400    | 28        | 5.82%   |
| 1334    | 24        | 4.99%   |
| 800     | 19        | 3.95%   |
| 667     | 19        | 3.95%   |
| 2133    | 18        | 3.74%   |
| Unknown | 12        | 2.49%   |
| 1066    | 10        | 2.08%   |
| 533     | 8         | 1.66%   |
| 3266    | 7         | 1.46%   |
| 1067    | 7         | 1.46%   |
| 4199    | 6         | 1.25%   |
| 1867    | 5         | 1.04%   |
| 3400    | 4         | 0.83%   |
| 3000    | 4         | 0.83%   |
| 49926   | 3         | 0.62%   |
| 3600    | 3         | 0.62%   |
| 2048    | 3         | 0.62%   |
| 1866    | 3         | 0.62%   |
| 3866    | 2         | 0.42%   |
| 3800    | 2         | 0.42%   |
| 3733    | 2         | 0.42%   |
| 2933    | 2         | 0.42%   |
| 2800    | 2         | 0.42%   |
| 2666    | 2         | 0.42%   |
| 975     | 2         | 0.42%   |
| 400     | 2         | 0.42%   |
| 4800    | 1         | 0.21%   |
| 4267    | 1         | 0.21%   |
| 3534    | 1         | 0.21%   |
| 3533    | 1         | 0.21%   |
| 3466    | 1         | 0.21%   |
| 3100    | 1         | 0.21%   |
| 2473    | 1         | 0.21%   |
| 2000    | 1         | 0.21%   |
| 1800    | 1         | 0.21%   |
| 1450    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 8         | 28.57%  |
| Brother Industries     | 7         | 25%     |
| Seiko Epson            | 3         | 10.71%  |
| Canon                  | 3         | 10.71%  |
| Samsung Electronics    | 2         | 7.14%   |
| QinHeng Electronics    | 2         | 7.14%   |
| Panasonic (Matsushita) | 1         | 3.57%   |
| Lexmark International  | 1         | 3.57%   |
| BIXOLON                | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Brother Printer                            | 3         | 10.34%  |
| QinHeng CH340S                             | 2         | 6.9%    |
| HP LaserJet Professional P 1102w           | 2         | 6.9%    |
| Seiko Epson WF-2010 Series                 | 1         | 3.45%   |
| Seiko Epson Printer                        | 1         | 3.45%   |
| Seiko Epson L310 Series                    | 1         | 3.45%   |
| Samsung M2020 Series                       | 1         | 3.45%   |
| Samsung CLX-4190 Series                    | 1         | 3.45%   |
| Panasonic (Matsushita) KX-MB2130RU         | 1         | 3.45%   |
| Lexmark International InkJet Color Printer | 1         | 3.45%   |
| HP Officejet 4500 G510a-f                  | 1         | 3.45%   |
| HP LaserJet 1022                           | 1         | 3.45%   |
| HP LaserJet 1020                           | 1         | 3.45%   |
| HP Deskjet F4500 series                    | 1         | 3.45%   |
| HP Deskjet 3050 J610 series                | 1         | 3.45%   |
| HP DeskJet 2130 series                     | 1         | 3.45%   |
| Canon PIXMA MG2500 Series                  | 1         | 3.45%   |
| Canon Pixma iP4500 Printer                 | 1         | 3.45%   |
| Canon LBP7010C/7018C                       | 1         | 3.45%   |
| Brother MFC-L2710DN series                 | 1         | 3.45%   |
| Brother HL-3170CDW series                  | 1         | 3.45%   |
| Brother HL-1440 Laser Printer              | 1         | 3.45%   |
| Brother DCP-L2540DW                        | 1         | 3.45%   |
| Brother DCP-7055 scanner/printer           | 1         | 3.45%   |
| BIXOLON BIXOLON_SLP-T400                   | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 50%     |
| Canon       | 3         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]  | 1         | 16.67%  |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1         | 16.67%  |
| Seiko Epson ES-D400 [GT-S80]                      | 1         | 16.67%  |
| Canon CanoScan LiDE 90                            | 1         | 16.67%  |
| Canon CanoScan LiDE 210                           | 1         | 16.67%  |
| Canon CanoScan LiDE 110                           | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 89        | 27.64%  |
| Microdia                               | 32        | 9.94%   |
| Sunplus Innovation Technology          | 20        | 6.21%   |
| Logitech                               | 17        | 5.28%   |
| IMC Networks                           | 17        | 5.28%   |
| Bison Electronics                      | 15        | 4.66%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.35%   |
| Realtek Semiconductor                  | 13        | 4.04%   |
| Acer                                   | 13        | 4.04%   |
| Quanta                                 | 11        | 3.42%   |
| Syntek                                 | 9         | 2.8%    |
| Ricoh                                  | 9         | 2.8%    |
| Apple                                  | 8         | 2.48%   |
| Suyin                                  | 7         | 2.17%   |
| Silicon Motion                         | 6         | 1.86%   |
| Lite-On Technology                     | 5         | 1.55%   |
| Luxvisions Innotech Limited            | 4         | 1.24%   |
| Microsoft                              | 3         | 0.93%   |
| Alcor Micro                            | 3         | 0.93%   |
| Z-Star Microelectronics                | 2         | 0.62%   |
| Samsung Electronics                    | 2         | 0.62%   |
| LG Electronics                         | 2         | 0.62%   |
| KYE Systems (Mouse Systems)            | 2         | 0.62%   |
| Importek                               | 2         | 0.62%   |
| Creative Technology                    | 2         | 0.62%   |
| Aveo Technology                        | 2         | 0.62%   |
| Y Media                                | 1         | 0.31%   |
| Sunplus Technology                     | 1         | 0.31%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.31%   |
| Ruision                                | 1         | 0.31%   |
| Primax Electronics                     | 1         | 0.31%   |
| MacroSilicon                           | 1         | 0.31%   |
| Lenovo                                 | 1         | 0.31%   |
| Jieli Technology                       | 1         | 0.31%   |
| Google                                 | 1         | 0.31%   |
| Generalplus Technology                 | 1         | 0.31%   |
| DigiTech                               | 1         | 0.31%   |
| Cubeternet                             | 1         | 0.31%   |
| ARC International                      | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 19        | 5.86%   |
| Sunplus Integrated_Webcam_HD                            | 9         | 2.78%   |
| Microdia Integrated_Webcam_HD                           | 9         | 2.78%   |
| Logitech Webcam C270                                    | 7         | 2.16%   |
| Chicony USB2.0 VGA UVC WebCam                           | 7         | 2.16%   |
| Chicony HD WebCam                                       | 6         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 1.54%   |
| Acer Integrated Camera                                  | 5         | 1.54%   |
| Syntek Integrated Camera                                | 4         | 1.23%   |
| Ricoh HD Webcam                                         | 4         | 1.23%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 4         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 4         | 1.23%   |
| Bison BisonCam, NB Pro                                  | 4         | 1.23%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 4         | 1.23%   |
| Suyin HP TrueVision HD Integrated Webcam                | 3         | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 3         | 0.93%   |
| Realtek USB Camera                                      | 3         | 0.93%   |
| Realtek Integrated_Webcam_HD                            | 3         | 0.93%   |
| Quanta HD User Facing                                   | 3         | 0.93%   |
| Microdia USB 2.0 Camera                                 | 3         | 0.93%   |
| Microdia Integrated Webcam                              | 3         | 0.93%   |
| Lite-On HP HD Camera                                    | 3         | 0.93%   |
| IMC Networks Integrated Camera                          | 3         | 0.93%   |
| Chicony Integrated IR Camera                            | 3         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 0.93%   |
| Chicony HP Wide Vision HD Camera                        | 3         | 0.93%   |
| Chicony HP HD Webcam                                    | 3         | 0.93%   |
| Chicony CNF9055 Toshiba Webcam                          | 3         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 3         | 0.93%   |
| Bison Integrated Camera                                 | 3         | 0.93%   |
| Syntek Lenovo EasyCamera                                | 2         | 0.62%   |
| Syntek EasyCamera                                       | 2         | 0.62%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 0.62%   |
| Sunplus Dell Integrated Webcam                          | 2         | 0.62%   |
| Silicon Motion WebCam SC-13HDL11939N                    | 2         | 0.62%   |
| Silicon Motion 300k Pixel Camera                        | 2         | 0.62%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 2         | 0.62%   |
| Ricoh Sony Visual Communication Camera                  | 2         | 0.62%   |
| Ricoh Laptop_Integrated_Webcam_FHD                      | 2         | 0.62%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 44.83%  |
| Synaptics                  | 15        | 25.86%  |
| Shenzhen Goodix Technology | 6         | 10.34%  |
| Upek                       | 3         | 5.17%   |
| Elan Microelectronics      | 3         | 5.17%   |
| STMicroelectronics         | 1         | 1.72%   |
| Samsung Electronics        | 1         | 1.72%   |
| LighTuning Technology      | 1         | 1.72%   |
| Focal-systems.Corp         | 1         | 1.72%   |
| AuthenTec                  | 1         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 6         | 10.34%  |
| Validity Sensors VFS5011 Fingerprint Reader                 | 5         | 8.62%   |
| Validity Sensors VFS491                                     | 4         | 6.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                | 4         | 6.9%    |
| Shenzhen Goodix Fingerprint Reader                          | 4         | 6.9%    |
| Validity Sensors VFS495 Fingerprint Reader                  | 3         | 5.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 2         | 3.45%   |
| Validity Sensors Synaptics WBDI                             | 2         | 3.45%   |
| Validity Sensors Fingerprint scanner                        | 2         | 3.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 3.45%   |
| Synaptics WBDI                                              | 2         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 2         | 3.45%   |
| Synaptics Fingerprint reader [HP G6]                        | 2         | 3.45%   |
| Elan ELAN:Fingerprint                                       | 2         | 3.45%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 1.72%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 1         | 1.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 1.72%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 1         | 1.72%   |
| Upek TCS5B Fingerprint sensor                               | 1         | 1.72%   |
| Synaptics WBDI Fingerprint Reader USB 102                   | 1         | 1.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 1.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint    | 1         | 1.72%   |
| STMicroelectronics Fingerprint Reader                       | 1         | 1.72%   |
| Shenzhen Goodix  FingerPrint Device                         | 1         | 1.72%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 1.72%   |
| Samsung Fingerprint Device                                  | 1         | 1.72%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 1         | 1.72%   |
| Focal-systems.Corp FT9201Fingerprint.                       | 1         | 1.72%   |
| Elan ELAN:ARM-M4                                            | 1         | 1.72%   |
| AuthenTec AES2810                                           | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 23        | 56.1%   |
| Alcor Micro           | 9         | 21.95%  |
| Upek                  | 2         | 4.88%   |
| O2 Micro              | 2         | 4.88%   |
| Lenovo                | 2         | 4.88%   |
| Gemalto (was Gemplus) | 1         | 2.44%   |
| Chicony Electronics   | 1         | 2.44%   |
| Advanced Card Systems | 1         | 2.44%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 24.39%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 21.95%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 19.51%  |
| Broadcom 5880                                                                | 3         | 7.32%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.88%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.88%   |
| Broadcom 58200                                                               | 2         | 4.88%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.44%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 2.44%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 480       | 74.42%  |
| 1     | 131       | 20.31%  |
| 2     | 27        | 4.19%   |
| 3     | 3         | 0.47%   |
| 8     | 2         | 0.31%   |
| 4     | 2         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 27.75%  |
| Graphics card            | 44        | 21.05%  |
| Chipcard                 | 38        | 18.18%  |
| Net/wireless             | 16        | 7.66%   |
| Communication controller | 10        | 4.78%   |
| Storage                  | 8         | 3.83%   |
| Unassigned class         | 5         | 2.39%   |
| Multimedia controller    | 5         | 2.39%   |
| Bluetooth                | 5         | 2.39%   |
| Sound                    | 4         | 1.91%   |
| Network                  | 4         | 1.91%   |
| Camera                   | 4         | 1.91%   |
| Firewire controller      | 2         | 0.96%   |
| Card reader              | 2         | 0.96%   |
| Tv card                  | 1         | 0.48%   |
| Storage/ata              | 1         | 0.48%   |
| Net/ethernet             | 1         | 0.48%   |
| Flash memory             | 1         | 0.48%   |

