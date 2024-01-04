Devuan - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Devuan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Devuan/Desktop/README.md) and [notebooks](/Dist/Devuan/Notebook/README.md).

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

Total: 232

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [b66d7c38c1](https://linux-hardware.org/?probe=b66d7c38c1) | Dec 31, 2023 |
| Dell          | 03GCPM A01                  | Server      | [7c11f33356](https://linux-hardware.org/?probe=7c11f33356) | Dec 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [ce4bc6f455](https://linux-hardware.org/?probe=ce4bc6f455) | Dec 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f170615f49](https://linux-hardware.org/?probe=f170615f49) | Dec 14, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [7af6ecc981](https://linux-hardware.org/?probe=7af6ecc981) | Dec 12, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c23aa9b02a](https://linux-hardware.org/?probe=c23aa9b02a) | Dec 10, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [c72f209121](https://linux-hardware.org/?probe=c72f209121) | Dec 05, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8b68261a59](https://linux-hardware.org/?probe=8b68261a59) | Nov 30, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [2961332bce](https://linux-hardware.org/?probe=2961332bce) | Nov 26, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1080... | Notebook    | [37c32a9af7](https://linux-hardware.org/?probe=37c32a9af7) | Nov 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [01866950a6](https://linux-hardware.org/?probe=01866950a6) | Nov 25, 2023 |
| HP            | G62                         | Notebook    | [9d6424c4cc](https://linux-hardware.org/?probe=9d6424c4cc) | Nov 24, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [8e8de2388b](https://linux-hardware.org/?probe=8e8de2388b) | Nov 21, 2023 |
| HP            | Presario C700               | Notebook    | [c8a9963f71](https://linux-hardware.org/?probe=c8a9963f71) | Nov 19, 2023 |
| HP            | Unknown                     | Notebook    | [3827b1fa19](https://linux-hardware.org/?probe=3827b1fa19) | Nov 16, 2023 |
| HP            | Unknown                     | Notebook    | [ef19087623](https://linux-hardware.org/?probe=ef19087623) | Nov 16, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [547a248361](https://linux-hardware.org/?probe=547a248361) | Nov 03, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [21e7b53022](https://linux-hardware.org/?probe=21e7b53022) | Nov 02, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EC00    | Notebook    | [820620d5c4](https://linux-hardware.org/?probe=820620d5c4) | Nov 01, 2023 |
| Intel         | X99                         | Desktop     | [8f60418655](https://linux-hardware.org/?probe=8f60418655) | Oct 30, 2023 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [a54528c1ef](https://linux-hardware.org/?probe=a54528c1ef) | Oct 29, 2023 |
| Samsung       | N150P                       | Notebook    | [83f77d7896](https://linux-hardware.org/?probe=83f77d7896) | Oct 23, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [baacbfa91a](https://linux-hardware.org/?probe=baacbfa91a) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [cf522294f8](https://linux-hardware.org/?probe=cf522294f8) | Oct 18, 2023 |
| TUXEDO        | XP1610                      | Notebook    | [31be190f30](https://linux-hardware.org/?probe=31be190f30) | Oct 13, 2023 |
| Dell          | XPS M1530                   | Notebook    | [b24e393bbb](https://linux-hardware.org/?probe=b24e393bbb) | Sep 23, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [56cd0e05e8](https://linux-hardware.org/?probe=56cd0e05e8) | Sep 22, 2023 |
| PC Special... | P7xxTM1                     | Notebook    | [2bdbc2f2e7](https://linux-hardware.org/?probe=2bdbc2f2e7) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [f23bb97453](https://linux-hardware.org/?probe=f23bb97453) | Sep 11, 2023 |
| Sony          | VGN-FZ140E                  | Notebook    | [361226919e](https://linux-hardware.org/?probe=361226919e) | Sep 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [61906f4e91](https://linux-hardware.org/?probe=61906f4e91) | Sep 07, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [89a0e93fd5](https://linux-hardware.org/?probe=89a0e93fd5) | Sep 05, 2023 |
| Intel         | powered classmate PC        | Notebook    | [f852524db2](https://linux-hardware.org/?probe=f852524db2) | Sep 01, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [44e328b3a0](https://linux-hardware.org/?probe=44e328b3a0) | Aug 24, 2023 |
| Lenovo        | ThinkPad X390 20Q1A005CD    | Notebook    | [c299d4ad92](https://linux-hardware.org/?probe=c299d4ad92) | Aug 15, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| Dell          | 0GX297                      | Desktop     | [0fa81b620e](https://linux-hardware.org/?probe=0fa81b620e) | Aug 14, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [bed2e58bf4](https://linux-hardware.org/?probe=bed2e58bf4) | Aug 14, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [affc999457](https://linux-hardware.org/?probe=affc999457) | Aug 12, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [3e63b3dec0](https://linux-hardware.org/?probe=3e63b3dec0) | Aug 09, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [a036ddad16](https://linux-hardware.org/?probe=a036ddad16) | Aug 09, 2023 |
| Supermicro    | X10SRG-F                    | Desktop     | [3bdaa7bfef](https://linux-hardware.org/?probe=3bdaa7bfef) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [67febbf0c0](https://linux-hardware.org/?probe=67febbf0c0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [606780c010](https://linux-hardware.org/?probe=606780c010) | Jul 24, 2023 |
| Samsung       | 550XDA                      | Notebook    | [c298263c6c](https://linux-hardware.org/?probe=c298263c6c) | Jul 22, 2023 |
| Dell          | Latitude E5500              | Notebook    | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Nokia         | N900                        | Notebook    | [7728c85b90](https://linux-hardware.org/?probe=7728c85b90) | Jul 06, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [d072001450](https://linux-hardware.org/?probe=d072001450) | Jul 04, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [8b04801d40](https://linux-hardware.org/?probe=8b04801d40) | Jun 27, 2023 |
| Lenovo        | ThinkPad T410 2537DA3       | Notebook    | [067b7f26a2](https://linux-hardware.org/?probe=067b7f26a2) | Jun 25, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [82c9c200bc](https://linux-hardware.org/?probe=82c9c200bc) | Jun 20, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7a3f7dcd73](https://linux-hardware.org/?probe=7a3f7dcd73) | Jun 17, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [0e9ccef97f](https://linux-hardware.org/?probe=0e9ccef97f) | May 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [54f07f7d96](https://linux-hardware.org/?probe=54f07f7d96) | May 12, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | Desktop     | [36022cb1ac](https://linux-hardware.org/?probe=36022cb1ac) | May 11, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [0d2ac684c8](https://linux-hardware.org/?probe=0d2ac684c8) | May 08, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [c67960852a](https://linux-hardware.org/?probe=c67960852a) | May 06, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d07874c829](https://linux-hardware.org/?probe=d07874c829) | Apr 24, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5e6b796278](https://linux-hardware.org/?probe=5e6b796278) | Apr 24, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [b9846b05e7](https://linux-hardware.org/?probe=b9846b05e7) | Apr 22, 2023 |
| HP            | 212A                        | Desktop     | [178f3b9c05](https://linux-hardware.org/?probe=178f3b9c05) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [96e067f5c8](https://linux-hardware.org/?probe=96e067f5c8) | Apr 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [549f922cf6](https://linux-hardware.org/?probe=549f922cf6) | Apr 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [a9aa9ab39f](https://linux-hardware.org/?probe=a9aa9ab39f) | Apr 13, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | Desktop     | [491da3c2c2](https://linux-hardware.org/?probe=491da3c2c2) | Apr 10, 2023 |
| Google        | Cyan                        | Notebook    | [f32e15dfef](https://linux-hardware.org/?probe=f32e15dfef) | Apr 09, 2023 |
| MSI           | PH67A-C43                   | Desktop     | [8e7c8a3d67](https://linux-hardware.org/?probe=8e7c8a3d67) | Apr 03, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [ec45a753a5](https://linux-hardware.org/?probe=ec45a753a5) | Apr 02, 2023 |
| Dell          | G5 5505                     | Notebook    | [2552b456b6](https://linux-hardware.org/?probe=2552b456b6) | Mar 29, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [a33a768662](https://linux-hardware.org/?probe=a33a768662) | Mar 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [98ba3a9ce6](https://linux-hardware.org/?probe=98ba3a9ce6) | Mar 25, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [f22446cb1d](https://linux-hardware.org/?probe=f22446cb1d) | Mar 16, 2023 |
| Google        | Bluebird                    | Notebook    | [2d18088551](https://linux-hardware.org/?probe=2d18088551) | Mar 15, 2023 |
| Dell          | Latitude E6230              | Notebook    | [49a9844be8](https://linux-hardware.org/?probe=49a9844be8) | Mar 15, 2023 |
| AMI           | Intel                       | Desktop     | [c2c28fa7e4](https://linux-hardware.org/?probe=c2c28fa7e4) | Mar 15, 2023 |
| Dell          | Latitude E6440              | Notebook    | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [83dcd35e5f](https://linux-hardware.org/?probe=83dcd35e5f) | Mar 12, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [60cd9db1c5](https://linux-hardware.org/?probe=60cd9db1c5) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| MSI           | A320M PRO-E                 | Desktop     | [3e441c86f1](https://linux-hardware.org/?probe=3e441c86f1) | Feb 20, 2023 |
| HP            | 829A                        | Mini pc     | [8791cd83c7](https://linux-hardware.org/?probe=8791cd83c7) | Feb 19, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| MSI           | H67MS-E43                   | Desktop     | [47a6655b3b](https://linux-hardware.org/?probe=47a6655b3b) | Feb 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [63ea9a161f](https://linux-hardware.org/?probe=63ea9a161f) | Jan 31, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [f4349052b8](https://linux-hardware.org/?probe=f4349052b8) | Jan 06, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [1f72002986](https://linux-hardware.org/?probe=1f72002986) | Dec 29, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1d9edd6c97](https://linux-hardware.org/?probe=1d9edd6c97) | Dec 25, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [beeeff23a5](https://linux-hardware.org/?probe=beeeff23a5) | Dec 25, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
| Dell          | Latitude E6530              | Notebook    | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [be4f638bc7](https://linux-hardware.org/?probe=be4f638bc7) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [7254534946](https://linux-hardware.org/?probe=7254534946) | Oct 20, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Lenovo        | ThinkPad T440p              | Notebook    | [270cf10219](https://linux-hardware.org/?probe=270cf10219) | Sep 25, 2022 |
| Lenovo        | ThinkPad T440p              | Notebook    | [bf397424f3](https://linux-hardware.org/?probe=bf397424f3) | Sep 18, 2022 |
| HP            | 1825                        | Desktop     | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
| MSI           | X99S MPOWER                 | Desktop     | [a3c1523b6b](https://linux-hardware.org/?probe=a3c1523b6b) | Jul 27, 2022 |
| Sony          | VPCEE23FX                   | Notebook    | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Dell          | Latitude 7280               | Notebook    | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [045554b70c](https://linux-hardware.org/?probe=045554b70c) | Jul 08, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [407b210bfe](https://linux-hardware.org/?probe=407b210bfe) | Jul 05, 2022 |
| HP            | 18E7                        | Desktop     | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | Notebook    | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [a698baa5f6](https://linux-hardware.org/?probe=a698baa5f6) | Jun 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [001634b95b](https://linux-hardware.org/?probe=001634b95b) | Jun 17, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [5da801634f](https://linux-hardware.org/?probe=5da801634f) | Jun 09, 2022 |
| Dell          | Latitude E6430              | Notebook    | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [2d4c950e2f](https://linux-hardware.org/?probe=2d4c950e2f) | May 25, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [73139cdb17](https://linux-hardware.org/?probe=73139cdb17) | May 25, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [f05a6e7d31](https://linux-hardware.org/?probe=f05a6e7d31) | May 03, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| HP            | Notebook                    | Notebook    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [fe4bb32aa1](https://linux-hardware.org/?probe=fe4bb32aa1) | Apr 14, 2022 |
| Dell          | 014GRG A00                  | Desktop     | [1783efe96b](https://linux-hardware.org/?probe=1783efe96b) | Apr 14, 2022 |
| Lenovo        | ThinkPad T470s 20HGS00P0... | Notebook    | [2c9878c68b](https://linux-hardware.org/?probe=2c9878c68b) | Apr 13, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [1aa66a62c4](https://linux-hardware.org/?probe=1aa66a62c4) | Mar 26, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| HP            | 1825                        | Desktop     | [a7ce5b6b11](https://linux-hardware.org/?probe=a7ce5b6b11) | Mar 03, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [f92ae76fed](https://linux-hardware.org/?probe=f92ae76fed) | Feb 24, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [7ab68e0043](https://linux-hardware.org/?probe=7ab68e0043) | Feb 17, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [824dbdd8ad](https://linux-hardware.org/?probe=824dbdd8ad) | Jan 22, 2022 |
| Online Lab... | SR 42                       | Desktop     | [e3037eb087](https://linux-hardware.org/?probe=e3037eb087) | Jan 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9e14e04f7f](https://linux-hardware.org/?probe=9e14e04f7f) | Jan 22, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [562262b9eb](https://linux-hardware.org/?probe=562262b9eb) | Jan 22, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [9fbdf4dfc2](https://linux-hardware.org/?probe=9fbdf4dfc2) | Jan 17, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | Notebook    | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Notebook      | W230ST                      | Notebook    | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [202ccac61c](https://linux-hardware.org/?probe=202ccac61c) | Dec 30, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [1c15b6b3c7](https://linux-hardware.org/?probe=1c15b6b3c7) | Dec 26, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [899cb98778](https://linux-hardware.org/?probe=899cb98778) | Dec 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [d43a6a6bb8](https://linux-hardware.org/?probe=d43a6a6bb8) | Nov 29, 2021 |
| HP            | 1495                        | Desktop     | [28835849f0](https://linux-hardware.org/?probe=28835849f0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | Notebook    | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7f1b3371a9](https://linux-hardware.org/?probe=7f1b3371a9) | Oct 03, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| MSI           | B360M PRO-VD                | Desktop     | [06e625d98f](https://linux-hardware.org/?probe=06e625d98f) | Oct 02, 2021 |
| Toshiba       | Satellite M40X              | Notebook    | [61fea93e97](https://linux-hardware.org/?probe=61fea93e97) | Oct 01, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | Notebook    | [04747e3df4](https://linux-hardware.org/?probe=04747e3df4) | Sep 19, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | Notebook    | [134b90f474](https://linux-hardware.org/?probe=134b90f474) | Sep 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ffd8fa11af](https://linux-hardware.org/?probe=ffd8fa11af) | Sep 16, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d65f9a48fd](https://linux-hardware.org/?probe=d65f9a48fd) | Sep 04, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | Notebook    | [04256a6e0a](https://linux-hardware.org/?probe=04256a6e0a) | Aug 25, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | Notebook    | [dffbcc492c](https://linux-hardware.org/?probe=dffbcc492c) | Aug 25, 2021 |
| ASUSTek       | K52F                        | Notebook    | [643e3cc4b3](https://linux-hardware.org/?probe=643e3cc4b3) | Aug 13, 2021 |
| MSI           | MS-1688                     | Notebook    | [0ae772d66b](https://linux-hardware.org/?probe=0ae772d66b) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | Notebook    | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| Acer          | Extensa 215-51K             | Notebook    | [1c49c2f4d0](https://linux-hardware.org/?probe=1c49c2f4d0) | Jul 26, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| HP            | 1825                        | Desktop     | [ff75be1ea3](https://linux-hardware.org/?probe=ff75be1ea3) | Jun 06, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [8702580cb4](https://linux-hardware.org/?probe=8702580cb4) | May 26, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [05f1d12390](https://linux-hardware.org/?probe=05f1d12390) | May 26, 2021 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [2ffdc89c2a](https://linux-hardware.org/?probe=2ffdc89c2a) | Apr 28, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [50f8ddb45c](https://linux-hardware.org/?probe=50f8ddb45c) | Apr 28, 2021 |
| ASUSTek       | K55VJ                       | Notebook    | [6fa86f9d25](https://linux-hardware.org/?probe=6fa86f9d25) | Apr 27, 2021 |
| Google        | Tricky                      | Desktop     | [666794d603](https://linux-hardware.org/?probe=666794d603) | Apr 26, 2021 |
| ASUSTek       | K55VJ                       | Notebook    | [aef1b6c71f](https://linux-hardware.org/?probe=aef1b6c71f) | Apr 17, 2021 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [630bbb748a](https://linux-hardware.org/?probe=630bbb748a) | Apr 17, 2021 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [f103eefd66](https://linux-hardware.org/?probe=f103eefd66) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [e802fc9ff5](https://linux-hardware.org/?probe=e802fc9ff5) | Apr 17, 2021 |
| HP            | ProBook 6475b               | Notebook    | [74b0fa77b5](https://linux-hardware.org/?probe=74b0fa77b5) | Apr 14, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e4b76f9137](https://linux-hardware.org/?probe=e4b76f9137) | Apr 10, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [15691fbc42](https://linux-hardware.org/?probe=15691fbc42) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | Notebook    | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [ee6bb68e8c](https://linux-hardware.org/?probe=ee6bb68e8c) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eeebc66137](https://linux-hardware.org/?probe=eeebc66137) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fdf4e6d366](https://linux-hardware.org/?probe=fdf4e6d366) | Mar 17, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | GA-G41M-ES2L                | Desktop     | [592c995804](https://linux-hardware.org/?probe=592c995804) | Jan 30, 2021 |
| Acer          | F672CR R01-A4               | Desktop     | [8d41694165](https://linux-hardware.org/?probe=8d41694165) | Jan 25, 2021 |
| Teclast       | F6 Plus                     | Notebook    | [26ac25681a](https://linux-hardware.org/?probe=26ac25681a) | Jan 08, 2021 |
| Lenovo        | ThinkStation E20 4220CTO    | Desktop     | [f963a2e7f9](https://linux-hardware.org/?probe=f963a2e7f9) | Jan 06, 2021 |
| Dell          | 0GXM1W A04                  | Desktop     | [989f983b51](https://linux-hardware.org/?probe=989f983b51) | Dec 28, 2020 |
| Lenovo        | ThinkStation E20 4220CTO    | Desktop     | [aac28ba905](https://linux-hardware.org/?probe=aac28ba905) | Dec 19, 2020 |
| Dell          | Precision 7530              | Notebook    | [8e0ee186a3](https://linux-hardware.org/?probe=8e0ee186a3) | Dec 04, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [b708be8d9e](https://linux-hardware.org/?probe=b708be8d9e) | Nov 10, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | Notebook    | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Intel         | HURONRIVER                  | Desktop     | [49bdd1a99d](https://linux-hardware.org/?probe=49bdd1a99d) | Oct 29, 2020 |
| ASUSTek       | Maximus V GENE              | Desktop     | [253b5aba98](https://linux-hardware.org/?probe=253b5aba98) | Oct 29, 2020 |
| Nokia         | N900                        | Notebook    | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [cd136e059e](https://linux-hardware.org/?probe=cd136e059e) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | Notebook    | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| Dell          | Precision 7530              | Notebook    | [e6c6dd2734](https://linux-hardware.org/?probe=e6c6dd2734) | Sep 26, 2020 |
| Dell          | Precision 7530              | Notebook    | [81e9306141](https://linux-hardware.org/?probe=81e9306141) | Sep 26, 2020 |
| HP            | 1791                        | Desktop     | [f41fcdc019](https://linux-hardware.org/?probe=f41fcdc019) | Sep 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3d241c321f](https://linux-hardware.org/?probe=3d241c321f) | Sep 20, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [32b487459e](https://linux-hardware.org/?probe=32b487459e) | Sep 16, 2020 |
| ASUSTek       | K52F                        | Notebook    | [cef5147eeb](https://linux-hardware.org/?probe=cef5147eeb) | Aug 30, 2020 |
| Acer          | Aspire 5732Z                | Notebook    | [c4cb936b69](https://linux-hardware.org/?probe=c4cb936b69) | Aug 30, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [6251a9111f](https://linux-hardware.org/?probe=6251a9111f) | Aug 30, 2020 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [0c85729a27](https://linux-hardware.org/?probe=0c85729a27) | Aug 30, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| HP            | 1791                        | Desktop     | [5a21e91155](https://linux-hardware.org/?probe=5a21e91155) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ff5143e508](https://linux-hardware.org/?probe=ff5143e508) | Aug 02, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Lenovo        | IdeaPad Z370                | Notebook    | [51e3108708](https://linux-hardware.org/?probe=51e3108708) | Jun 28, 2020 |
| Dell          | Latitude 5501               | Notebook    | [94ec8d2a1d](https://linux-hardware.org/?probe=94ec8d2a1d) | Jun 28, 2020 |
| Lenovo        | IdeaPad Z370                | Notebook    | [76c985ed75](https://linux-hardware.org/?probe=76c985ed75) | Jun 27, 2020 |
| Dell          | Latitude E7250              | Notebook    | [c2ca61e7bf](https://linux-hardware.org/?probe=c2ca61e7bf) | Jun 23, 2020 |
| ASUSTek       | P5PE-VM                     | Desktop     | [298c1239dd](https://linux-hardware.org/?probe=298c1239dd) | May 20, 2020 |
| MSI           | B350 PC MATE                | Desktop     | [ff3852f02d](https://linux-hardware.org/?probe=ff3852f02d) | Mar 23, 2020 |
| Dell          | Inspiron 1564               | Notebook    | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| MTC           | Montara-GML                 | Notebook    | [227bf1ba1d](https://linux-hardware.org/?probe=227bf1ba1d) | Dec 07, 2019 |
| ASRock        | G31M-VS2                    | Desktop     | [b64547f948](https://linux-hardware.org/?probe=b64547f948) | Dec 06, 2019 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASUSTek       | P5PE-VM                     | Desktop     | [6a89046dfb](https://linux-hardware.org/?probe=6a89046dfb) | Dec 02, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [59ca47d9e7](https://linux-hardware.org/?probe=59ca47d9e7) | Apr 12, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Devuan 4                | 82        | 42.05%  |
| Devuan 5                | 49        | 25.13%  |
| Devuan 3                | 31        | 15.9%   |
| Devuan Testing/unstable | 15        | 7.69%   |
| Devuan 2.1              | 7         | 3.59%   |
| Devuan                  | 6         | 3.08%   |
| Devuan 6                | 2         | 1.03%   |
| Devuan 3.0              | 1         | 0.51%   |
| Devuan 2.0              | 1         | 0.51%   |
| Devuan 1.0.0            | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 184       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.10.0-21-amd64       | 13        | 6.31%   |
| 6.1.0-13-amd64        | 11        | 5.34%   |
| 5.10.0-9-amd64        | 10        | 4.85%   |
| 5.10.0-23-amd64       | 8         | 3.88%   |
| 5.10.0-8-amd64        | 7         | 3.4%    |
| 5.10.0-16-amd64       | 6         | 2.91%   |
| 4.19.0-9-amd64        | 6         | 2.91%   |
| 4.19.0-14-amd64       | 6         | 2.91%   |
| 6.1.0-11-amd64        | 5         | 2.43%   |
| 5.10.0-19-amd64       | 5         | 2.43%   |
| 4.19.0-16-amd64       | 5         | 2.43%   |
| 6.1.0-10-amd64        | 4         | 1.94%   |
| 5.10.0-18-amd64       | 4         | 1.94%   |
| 5.10.0-13-amd64       | 4         | 1.94%   |
| 5.10.0-11-amd64       | 4         | 1.94%   |
| 5.10.0-10-amd64       | 4         | 1.94%   |
| 6.1.0-6-amd64         | 3         | 1.46%   |
| 6.1.0-12-amd64        | 3         | 1.46%   |
| 5.7.0-2-amd64         | 3         | 1.46%   |
| 5.10.0-20-amd64       | 3         | 1.46%   |
| 4.19.0-12-amd64       | 3         | 1.46%   |
| 4.19.0-10-amd64       | 3         | 1.46%   |
| 6.1.0-9-amd64         | 2         | 0.97%   |
| 6.1.0-16-amd64        | 2         | 0.97%   |
| 6.1.0-0.deb11.7-amd64 | 2         | 0.97%   |
| 6.0.0-5-amd64         | 2         | 0.97%   |
| 5.7.0-0.bpo.2-amd64   | 2         | 0.97%   |
| 5.18.0-2-amd64        | 2         | 0.97%   |
| 5.18.0-1-amd64        | 2         | 0.97%   |
| 5.15.0-2-amd64        | 2         | 0.97%   |
| 5.10.0-6-amd64        | 2         | 0.97%   |
| 5.10.0-25-amd64       | 2         | 0.97%   |
| 5.10.0-22-amd64       | 2         | 0.97%   |
| 5.10.0-15-amd64       | 2         | 0.97%   |
| 5.10.0-14-amd64       | 2         | 0.97%   |
| 4.19.0-17-amd64       | 2         | 0.97%   |
| 4.19.0-13-amd64       | 2         | 0.97%   |
| 6.5.0-0.deb12.4-amd64 | 1         | 0.49%   |
| 6.5.0-0.deb12.1-amd64 | 1         | 0.49%   |
| 6.3.0-2-amd64         | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 80        | 40.82%  |
| 6.1.0    | 35        | 17.86%  |
| 4.19.0   | 29        | 14.8%   |
| 4.9.0    | 8         | 4.08%   |
| 5.7.0    | 6         | 3.06%   |
| 6.0.0    | 4         | 2.04%   |
| 5.18.0   | 4         | 2.04%   |
| 5.15.0   | 3         | 1.53%   |
| 6.5.0    | 2         | 1.02%   |
| 5.9.0    | 2         | 1.02%   |
| 5.8.0    | 2         | 1.02%   |
| 5.14.0   | 2         | 1.02%   |
| 6.3.0    | 1         | 0.51%   |
| 6.2.12   | 1         | 0.51%   |
| 6.1.9    | 1         | 0.51%   |
| 6.1.7    | 1         | 0.51%   |
| 6.1.25   | 1         | 0.51%   |
| 5.7.19   | 1         | 0.51%   |
| 5.6.0    | 1         | 0.51%   |
| 5.19.0   | 1         | 0.51%   |
| 5.18.14  | 1         | 0.51%   |
| 5.18.11  | 1         | 0.51%   |
| 5.16.0   | 1         | 0.51%   |
| 5.15.5   | 1         | 0.51%   |
| 5.11.0   | 1         | 0.51%   |
| 5.10.162 | 1         | 0.51%   |
| 5.1.21   | 1         | 0.51%   |
| 5.0.7    | 1         | 0.51%   |
| 4.4.195  | 1         | 0.51%   |
| 4.19.112 | 1         | 0.51%   |
| 4.18.0   | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 81        | 41.33%  |
| 6.1     | 38        | 19.39%  |
| 4.19    | 30        | 15.31%  |
| 4.9     | 8         | 4.08%   |
| 5.7     | 7         | 3.57%   |
| 5.18    | 6         | 3.06%   |
| 6.0     | 4         | 2.04%   |
| 5.15    | 4         | 2.04%   |
| 6.5     | 2         | 1.02%   |
| 5.9     | 2         | 1.02%   |
| 5.8     | 2         | 1.02%   |
| 5.14    | 2         | 1.02%   |
| 6.3     | 1         | 0.51%   |
| 6.2     | 1         | 0.51%   |
| 5.6     | 1         | 0.51%   |
| 5.19    | 1         | 0.51%   |
| 5.16    | 1         | 0.51%   |
| 5.11    | 1         | 0.51%   |
| 5.1     | 1         | 0.51%   |
| 5.0     | 1         | 0.51%   |
| 4.4     | 1         | 0.51%   |
| 4.18    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 176       | 95.65%  |
| i686   | 6         | 3.26%   |
| armv7l | 2         | 1.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| XFCE          | 80        | 41.45%  |
| KDE5          | 28        | 14.51%  |
| Unknown       | 27        | 13.99%  |
| MATE          | 25        | 12.95%  |
| i3            | 8         | 4.15%   |
| LXDE          | 7         | 3.63%   |
| Cinnamon      | 5         | 2.59%   |
| GNOME         | 4         | 2.07%   |
| LXQt          | 3         | 1.55%   |
| Enlightenment | 2         | 1.04%   |
| X-Cinnamon    | 1         | 0.52%   |
| sway          | 1         | 0.52%   |
| Openbox       | 1         | 0.52%   |
| awesome       | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 162       | 86.17%  |
| Tty         | 17        | 9.04%   |
| Unknown     | 6         | 3.19%   |
| Wayland     | 2         | 1.06%   |
| Unspecified | 1         | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 67        | 35.64%  |
| Unknown | 48        | 25.53%  |
| LightDM | 47        | 25%     |
| SDDM    | 16        | 8.51%   |
| XDM     | 3         | 1.6%    |
| NODM    | 2         | 1.06%   |
| LXDM    | 2         | 1.06%   |
| GDM3    | 2         | 1.06%   |
| Ly      | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 75        | 40.11%  |
| en_GB       | 26        | 13.9%   |
| ru_RU       | 11        | 5.88%   |
| pt_BR       | 9         | 4.81%   |
| fr_FR       | 8         | 4.28%   |
| C           | 8         | 4.28%   |
| Unknown     | 8         | 4.28%   |
| it_IT       | 5         | 2.67%   |
| de_DE       | 5         | 2.67%   |
| es_ES       | 4         | 2.14%   |
| en_AU       | 4         | 2.14%   |
| sk_SK       | 3         | 1.6%    |
| fr_BE       | 3         | 1.6%    |
| en_NZ       | 3         | 1.6%    |
| pl_PL       | 2         | 1.07%   |
| en_ZA       | 2         | 1.07%   |
| de_AT       | 2         | 1.07%   |
| ru_UA       | 1         | 0.53%   |
| ru_RU.utf-8 | 1         | 0.53%   |
| es_SV       | 1         | 0.53%   |
| es_MX       | 1         | 0.53%   |
| es_AR       | 1         | 0.53%   |
| en_US.utf-8 | 1         | 0.53%   |
| en_SG       | 1         | 0.53%   |
| en_CA       | 1         | 0.53%   |
| de_CH       | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 99        | 53.23%  |
| EFI  | 87        | 46.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 155       | 84.24%  |
| Btrfs   | 10        | 5.43%   |
| Xfs     | 5         | 2.72%   |
| Unknown | 5         | 2.72%   |
| Overlay | 4         | 2.17%   |
| Ext3    | 2         | 1.09%   |
| Ext2    | 2         | 1.09%   |
| OveXlay | 1         | 0.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 106       | 55.79%  |
| MBR     | 62        | 32.63%  |
| Unknown | 22        | 11.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 79.03%  |
| Yes       | 39        | 20.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 77.3%   |
| Yes       | 42        | 22.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 34        | 18.48%  |
| Dell                | 28        | 15.22%  |
| Hewlett-Packard     | 21        | 11.41%  |
| ASUSTek Computer    | 19        | 10.33%  |
| Gigabyte Technology | 15        | 8.15%   |
| MSI                 | 13        | 7.07%   |
| Acer                | 7         | 3.8%    |
| ASRock              | 5         | 2.72%   |
| Toshiba             | 4         | 2.17%   |
| Intel               | 4         | 2.17%   |
| Samsung Electronics | 3         | 1.63%   |
| Google              | 3         | 1.63%   |
| Apple               | 3         | 1.63%   |
| Sony                | 2         | 1.09%   |
| Nokia               | 2         | 1.09%   |
| Fujitsu Siemens     | 2         | 1.09%   |
| AMI                 | 2         | 1.09%   |
| TUXEDO              | 1         | 0.54%   |
| Teclast             | 1         | 0.54%   |
| Supermicro          | 1         | 0.54%   |
| Sun Microsystems    | 1         | 0.54%   |
| PC Specialist       | 1         | 0.54%   |
| Online Labs         | 1         | 0.54%   |
| Notebook            | 1         | 0.54%   |
| MTC                 | 1         | 0.54%   |
| Microsoft           | 1         | 0.54%   |
| LORD ELECTRONICS    | 1         | 0.54%   |
| IP3 Tech            | 1         | 0.54%   |
| IBM                 | 1         | 0.54%   |
| HUAWEI              | 1         | 0.54%   |
| Fujitsu             | 1         | 0.54%   |
| Chuwi               | 1         | 0.54%   |
| CCE                 | 1         | 0.54%   |
| Unknown             | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nokia N900                                                                               | 2         | 1.09%   |
| Dell Latitude E6430                                                                      | 2         | 1.09%   |
| Unknown                                                                                  | 2         | 1.09%   |
| TUXEDO XP1610                                                                            | 1         | 0.54%   |
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.54%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.54%   |
| Toshiba Satellite L655                                                                   | 1         | 0.54%   |
| Toshiba Satellite L300                                                                   | 1         | 0.54%   |
| Teclast F6 Plus                                                                          | 1         | 0.54%   |
| Supermicro SYS-1018GR-T                                                                  | 1         | 0.54%   |
| Sun Microsystems Ultra 24                                                                | 1         | 0.54%   |
| Sony VPCEE23FX                                                                           | 1         | 0.54%   |
| Sony VGN-FZ140E                                                                          | 1         | 0.54%   |
| Samsung N150P                                                                            | 1         | 0.54%   |
| Samsung 550XDA                                                                           | 1         | 0.54%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.54%   |
| PC Specialist P7xxTM1                                                                    | 1         | 0.54%   |
| Online Labs SR                                                                           | 1         | 0.54%   |
| Notebook W230ST                                                                          | 1         | 0.54%   |
| MTC Montara-GML                                                                          | 1         | 0.54%   |
| MSI MS-7B86                                                                              | 1         | 0.54%   |
| MSI MS-7B84                                                                              | 1         | 0.54%   |
| MSI MS-7B53                                                                              | 1         | 0.54%   |
| MSI MS-7A38                                                                              | 1         | 0.54%   |
| MSI MS-7A36                                                                              | 1         | 0.54%   |
| MSI MS-7A34                                                                              | 1         | 0.54%   |
| MSI MS-7885                                                                              | 1         | 0.54%   |
| MSI MS-7693                                                                              | 1         | 0.54%   |
| MSI MS-7678                                                                              | 1         | 0.54%   |
| MSI MS-7673                                                                              | 1         | 0.54%   |
| MSI MS-1688                                                                              | 1         | 0.54%   |
| MSI Modern 15 A5M                                                                        | 1         | 0.54%   |
| MSI Bravo 15 A4DDR                                                                       | 1         | 0.54%   |
| Microsoft Surface Pro 4                                                                  | 1         | 0.54%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design                                        | 1         | 0.54%   |
| Lenovo Yoga C640-13IML 81UE                                                              | 1         | 0.54%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 0.54%   |
| Lenovo ThinkStation P330 Tiny 30CES09U00                                                 | 1         | 0.54%   |
| Lenovo ThinkStation P330 30C5S1LQ00                                                      | 1         | 0.54%   |
| Lenovo ThinkStation E20 4220CTO                                                          | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 22        | 11.96%  |
| Dell Latitude           | 12        | 6.52%   |
| Acer Aspire             | 6         | 3.26%   |
| Lenovo IdeaPad          | 5         | 2.72%   |
| Dell OptiPlex           | 5         | 2.72%   |
| Toshiba Satellite       | 4         | 2.17%   |
| Dell Inspiron           | 4         | 2.17%   |
| ASUS PRIME              | 4         | 2.17%   |
| Lenovo ThinkStation     | 3         | 1.63%   |
| HP ProBook              | 3         | 1.63%   |
| HP Laptop               | 3         | 1.63%   |
| Nokia N900              | 2         | 1.09%   |
| HP Pavilion             | 2         | 1.09%   |
| HP EliteDesk            | 2         | 1.09%   |
| Dell XPS                | 2         | 1.09%   |
| Dell PowerEdge          | 2         | 1.09%   |
| ASUS ROG                | 2         | 1.09%   |
| Unknown                 | 2         | 1.09%   |
| TUXEDO XP1610           | 1         | 0.54%   |
| Teclast F6              | 1         | 0.54%   |
| Supermicro SYS-1018GR-T | 1         | 0.54%   |
| Sun Microsystems Ultra  | 1         | 0.54%   |
| Sony VPCEE23FX          | 1         | 0.54%   |
| Sony VGN-FZ140E         | 1         | 0.54%   |
| Samsung N150P           | 1         | 0.54%   |
| Samsung 550XDA          | 1         | 0.54%   |
| Samsung 355V4C          | 1         | 0.54%   |
| PC Specialist P7xxTM1   | 1         | 0.54%   |
| Online Labs SR          | 1         | 0.54%   |
| Notebook W230ST         | 1         | 0.54%   |
| MTC Montara-GML         | 1         | 0.54%   |
| MSI MS-7B86             | 1         | 0.54%   |
| MSI MS-7B84             | 1         | 0.54%   |
| MSI MS-7B53             | 1         | 0.54%   |
| MSI MS-7A38             | 1         | 0.54%   |
| MSI MS-7A36             | 1         | 0.54%   |
| MSI MS-7A34             | 1         | 0.54%   |
| MSI MS-7885             | 1         | 0.54%   |
| MSI MS-7693             | 1         | 0.54%   |
| MSI MS-7678             | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 23        | 12.5%   |
| 2019    | 22        | 11.96%  |
| 2012    | 16        | 8.7%    |
| 2013    | 14        | 7.61%   |
| 2017    | 10        | 5.43%   |
| 2014    | 10        | 5.43%   |
| 2011    | 10        | 5.43%   |
| 2010    | 10        | 5.43%   |
| 2020    | 9         | 4.89%   |
| 2016    | 9         | 4.89%   |
| 2008    | 9         | 4.89%   |
| 2021    | 7         | 3.8%    |
| 2015    | 7         | 3.8%    |
| 2009    | 7         | 3.8%    |
| 2022    | 6         | 3.26%   |
| 2007    | 5         | 2.72%   |
| 2006    | 3         | 1.63%   |
| 2023    | 2         | 1.09%   |
| 2005    | 2         | 1.09%   |
| Unknown | 2         | 1.09%   |
| 2000    | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 103       | 55.98%  |
| Desktop     | 67        | 36.41%  |
| Mini pc     | 5         | 2.72%   |
| Tablet      | 3         | 1.63%   |
| Convertible | 3         | 1.63%   |
| Server      | 2         | 1.09%   |
| All in one  | 1         | 0.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 181       | 97.84%  |
| Enabled  | 4         | 2.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 177       | 96.2%   |
| Yes  | 7         | 3.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 39        | 20.97%  |
| 4.01-8.0    | 37        | 19.89%  |
| 8.01-16.0   | 37        | 19.89%  |
| 3.01-4.0    | 25        | 13.44%  |
| 32.01-64.0  | 19        | 10.22%  |
| 1.01-2.0    | 12        | 6.45%   |
| 2.01-3.0    | 6         | 3.23%   |
| 64.01-256.0 | 6         | 3.23%   |
| 0.01-0.5    | 4         | 2.15%   |
| 24.01-32.0  | 1         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 72        | 36.18%  |
| 4.01-8.0   | 33        | 16.58%  |
| 2.01-3.0   | 28        | 14.07%  |
| 0.51-1.0   | 23        | 11.56%  |
| 3.01-4.0   | 20        | 10.05%  |
| 8.01-16.0  | 11        | 5.53%   |
| 0.01-0.5   | 9         | 4.52%   |
| 16.01-24.0 | 2         | 1.01%   |
| 32.01-64.0 | 1         | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 115       | 62.16%  |
| 2      | 34        | 18.38%  |
| 3      | 19        | 10.27%  |
| 4      | 6         | 3.24%   |
| 5      | 5         | 2.7%    |
| 6      | 4         | 2.16%   |
| 7      | 2         | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 64.86%  |
| Yes       | 65        | 35.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 91.35%  |
| No        | 16        | 8.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 66.67%  |
| No        | 62        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 52.69%  |
| Yes       | 88        | 47.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 13.51%  |
| Germany      | 17        | 9.19%   |
| France       | 16        | 8.65%   |
| Russia       | 15        | 8.11%   |
| Brazil       | 13        | 7.03%   |
| Ukraine      | 7         | 3.78%   |
| UK           | 6         | 3.24%   |
| Italy        | 6         | 3.24%   |
| Spain        | 5         | 2.7%    |
| Slovakia     | 5         | 2.7%    |
| Poland       | 5         | 2.7%    |
| Portugal     | 4         | 2.16%   |
| Netherlands  | 4         | 2.16%   |
| Grenada      | 4         | 2.16%   |
| Australia    | 4         | 2.16%   |
| Switzerland  | 3         | 1.62%   |
| New Zealand  | 3         | 1.62%   |
| Hungary      | 3         | 1.62%   |
| Finland      | 3         | 1.62%   |
| Argentina    | 3         | 1.62%   |
| South Africa | 2         | 1.08%   |
| Mexico       | 2         | 1.08%   |
| Israel       | 2         | 1.08%   |
| Indonesia    | 2         | 1.08%   |
| Greece       | 2         | 1.08%   |
| Georgia      | 2         | 1.08%   |
| Canada       | 2         | 1.08%   |
| Belgium      | 2         | 1.08%   |
| Austria      | 2         | 1.08%   |
| Vietnam      | 1         | 0.54%   |
| Tunisia      | 1         | 0.54%   |
| South Korea  | 1         | 0.54%   |
| Singapore    | 1         | 0.54%   |
| Serbia       | 1         | 0.54%   |
| Romania      | 1         | 0.54%   |
| Puerto Rico  | 1         | 0.54%   |
| Norway       | 1         | 0.54%   |
| Lithuania    | 1         | 0.54%   |
| Japan        | 1         | 0.54%   |
| India        | 1         | 0.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Bratislava     | 5         | 2.69%   |
| Bagnolet       | 5         | 2.69%   |
| Saint George's | 4         | 2.15%   |
| Madrid         | 3         | 1.61%   |
| Wroclaw        | 2         | 1.08%   |
| Volzhskiy      | 2         | 1.08%   |
| Toronto        | 2         | 1.08%   |
| Thessaloniki   | 2         | 1.08%   |
| Tel Aviv       | 2         | 1.08%   |
| Tbilisi        | 2         | 1.08%   |
| Sydney         | 2         | 1.08%   |
| Sao Paulo      | 2         | 1.08%   |
| Rio de Janeiro | 2         | 1.08%   |
| Palmyra        | 2         | 1.08%   |
| Nadudvar       | 2         | 1.08%   |
| Munich         | 2         | 1.08%   |
| Milan          | 2         | 1.08%   |
| Lisbon         | 2         | 1.08%   |
| Kyiv           | 2         | 1.08%   |
| Krasnodar      | 2         | 1.08%   |
| Ft. Washington | 2         | 1.08%   |
| Buenos Aires   | 2         | 1.08%   |
| Auckland       | 2         | 1.08%   |
| Amsterdam      | 2         | 1.08%   |
| Yoshkar-Ola    | 1         | 0.54%   |
| Yakutsk        | 1         | 0.54%   |
| Xiamen         | 1         | 0.54%   |
| Windisch       | 1         | 0.54%   |
| Willich        | 1         | 0.54%   |
| Wildberg       | 1         | 0.54%   |
| Waterford      | 1         | 0.54%   |
| Vladikavkaz    | 1         | 0.54%   |
| Vise           | 1         | 0.54%   |
| Vilnius        | 1         | 0.54%   |
| Valbonne       | 1         | 0.54%   |
| Trubchëvsk    | 1         | 0.54%   |
| Tokyo          | 1         | 0.54%   |
| Timonium       | 1         | 0.54%   |
| Tejgaon        | 1         | 0.54%   |
| Tangerang      | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 76     | 17.47%  |
| Seagate             | 33        | 44     | 12.27%  |
| Samsung Electronics | 33        | 54     | 12.27%  |
| Kingston            | 17        | 20     | 6.32%   |
| Unknown             | 14        | 18     | 5.2%    |
| Toshiba             | 13        | 13     | 4.83%   |
| Crucial             | 12        | 15     | 4.46%   |
| Sandisk             | 11        | 11     | 4.09%   |
| Hitachi             | 8         | 8      | 2.97%   |
| SK hynix            | 6         | 6      | 2.23%   |
| Intel               | 6         | 8      | 2.23%   |
| HGST                | 6         | 6      | 2.23%   |
| PNY                 | 5         | 6      | 1.86%   |
| Micron Technology   | 4         | 5      | 1.49%   |
| Team                | 3         | 3      | 1.12%   |
| Netac               | 3         | 3      | 1.12%   |
| LITEON              | 3         | 6      | 1.12%   |
| Fujitsu             | 3         | 3      | 1.12%   |
| China               | 3         | 3      | 1.12%   |
| A-DATA Technology   | 3         | 3      | 1.12%   |
| Maxtor              | 2         | 2      | 0.74%   |
| Lenovo              | 2         | 2      | 0.74%   |
| Intenso             | 2         | 2      | 0.74%   |
| Hewlett-Packard     | 2         | 3      | 0.74%   |
| Dogfish             | 2         | 2      | 0.74%   |
| WD MediaMax         | 1         | 3      | 0.37%   |
| Union Memory        | 1         | 2      | 0.37%   |
| UMIS                | 1         | 1      | 0.37%   |
| Transcend           | 1         | 2      | 0.37%   |
| Teclast             | 1         | 1      | 0.37%   |
| Supermicro          | 1         | 1      | 0.37%   |
| SSSTC               | 1         | 1      | 0.37%   |
| Smart               | 1         | 1      | 0.37%   |
| SABRENT             | 1         | 2      | 0.37%   |
| Plextor             | 1         | 1      | 0.37%   |
| Patriot             | 1         | 1      | 0.37%   |
| Mushkin             | 1         | 1      | 0.37%   |
| LITEONIT            | 1         | 1      | 0.37%   |
| Lexar               | 1         | 1      | 0.37%   |
| Kston               | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 5         | 1.66%   |
| PNY CS900 240GB SSD                  | 4         | 1.33%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 1.33%   |
| Unknown MMC Card  128GB              | 3         | 1%      |
| Samsung SSD 850 EVO 500GB            | 3         | 1%      |
| Samsung SSD 850 EVO 250GB            | 3         | 1%      |
| Kingston SA400S37240G 240GB SSD      | 3         | 1%      |
| Kingston SA400S37120G 120GB SSD      | 3         | 1%      |
| Kingston SA2000M8250G 250GB          | 3         | 1%      |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.66%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 2         | 0.66%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2         | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.66%   |
| WDC WD10EZEX-00BBHA0 1TB             | 2         | 0.66%   |
| WDC WD10EARX-00N0YB0 1TB             | 2         | 0.66%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.66%   |
| Seagate ST9250410AS 250GB            | 2         | 0.66%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.66%   |
| Seagate ST3500418AS 500GB            | 2         | 0.66%   |
| Seagate ST2000DX002-2DV164 2TB       | 2         | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.66%   |
| SanDisk SDSSDX240GG25 240GB          | 2         | 0.66%   |
| Samsung SSD 980 PRO 1TB              | 2         | 0.66%   |
| Samsung SSD 980 1TB                  | 2         | 0.66%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.66%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.66%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.66%   |
| Samsung MZVLW512HMJP-000L7 512GB     | 2         | 0.66%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB | 2         | 0.66%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 0.66%   |
| Hitachi HDS721616PLA380 160GB        | 2         | 0.66%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.66%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.66%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.33%   |
| WDC WDS500G1B0A-00H9H0 500GB SSD     | 1         | 0.33%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.33%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 37        | 63     | 35.58%  |
| Seagate             | 32        | 43     | 30.77%  |
| Toshiba             | 10        | 10     | 9.62%   |
| Hitachi             | 8         | 8      | 7.69%   |
| HGST                | 6         | 6      | 5.77%   |
| Fujitsu             | 3         | 3      | 2.88%   |
| Samsung Electronics | 2         | 3      | 1.92%   |
| Maxtor              | 2         | 2      | 1.92%   |
| SABRENT             | 1         | 2      | 0.96%   |
| IBM/Hitachi         | 1         | 1      | 0.96%   |
| HPE                 | 1         | 2      | 0.96%   |
| Hewlett-Packard     | 1         | 2      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 23     | 20%     |
| Kingston            | 14        | 16     | 14%     |
| SanDisk             | 8         | 8      | 8%      |
| WDC                 | 6         | 7      | 6%      |
| Crucial             | 6         | 8      | 6%      |
| PNY                 | 5         | 6      | 5%      |
| Team                | 3         | 3      | 3%      |
| Netac               | 3         | 3      | 3%      |
| Micron Technology   | 3         | 3      | 3%      |
| China               | 3         | 3      | 3%      |
| SK hynix            | 2         | 2      | 2%      |
| LITEON              | 2         | 5      | 2%      |
| Intenso             | 2         | 2      | 2%      |
| Dogfish             | 2         | 2      | 2%      |
| A-DATA Technology   | 2         | 2      | 2%      |
| Union Memory        | 1         | 2      | 1%      |
| Transcend           | 1         | 2      | 1%      |
| Teclast             | 1         | 1      | 1%      |
| Supermicro          | 1         | 1      | 1%      |
| Smart               | 1         | 1      | 1%      |
| Plextor             | 1         | 1      | 1%      |
| Patriot             | 1         | 1      | 1%      |
| Mushkin             | 1         | 1      | 1%      |
| LITEONIT            | 1         | 1      | 1%      |
| Lexar               | 1         | 1      | 1%      |
| Kston               | 1         | 1      | 1%      |
| KingDian            | 1         | 1      | 1%      |
| Intel               | 1         | 3      | 1%      |
| HXY                 | 1         | 1      | 1%      |
| Hewlett-Packard     | 1         | 1      | 1%      |
| GOODRAM             | 1         | 1      | 1%      |
| Emtec               | 1         | 1      | 1%      |
| Corsair             | 1         | 1      | 1%      |
| Apple               | 1         | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 88        | 116    | 36.21%  |
| HDD     | 86        | 145    | 35.39%  |
| NVMe    | 52        | 69     | 21.4%   |
| MMC     | 14        | 18     | 5.76%   |
| Unknown | 3         | 6      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 142       | 256    | 66.05%  |
| NVMe | 52        | 69     | 24.19%  |
| MMC  | 14        | 18     | 6.51%   |
| SAS  | 7         | 11     | 3.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 111       | 156    | 62.71%  |
| 0.51-1.0   | 38        | 62     | 21.47%  |
| 1.01-2.0   | 18        | 30     | 10.17%  |
| 3.01-4.0   | 5         | 6      | 2.82%   |
| 4.01-10.0  | 3         | 3      | 1.69%   |
| 2.01-3.0   | 2         | 4      | 1.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 43        | 22.51%  |
| 251-500        | 42        | 21.99%  |
| 501-1000       | 26        | 13.61%  |
| 1001-2000      | 19        | 9.95%   |
| 51-100         | 17        | 8.9%    |
| 21-50          | 14        | 7.33%   |
| More than 3000 | 11        | 5.76%   |
| 1-20           | 7         | 3.66%   |
| 2001-3000      | 6         | 3.14%   |
| Unknown        | 6         | 3.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 58        | 30.21%  |
| 101-250        | 34        | 17.71%  |
| 21-50          | 23        | 11.98%  |
| 51-100         | 21        | 10.94%  |
| 251-500        | 19        | 9.9%    |
| 1001-2000      | 11        | 5.73%   |
| 501-1000       | 11        | 5.73%   |
| Unknown        | 6         | 3.13%   |
| More than 3000 | 5         | 2.6%    |
| 2001-3000      | 4         | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-24HXZT3 500GB          | 2         | 2      | 5.41%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 2      | 5.41%   |
| Hitachi HDS721616PLA380 160GB         | 2         | 2      | 5.41%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 5.41%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 2.7%    |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 2.7%    |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 2      | 2.7%    |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 3      | 2.7%    |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 2.7%    |
| WDC WD1502FAEX-007BA0 1TB             | 1         | 1      | 2.7%    |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 2.7%    |
| WDC WD10EARX-00N0YB0 1TB              | 1         | 1      | 2.7%    |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 2.7%    |
| Toshiba MQ02ABF100 1TB                | 1         | 1      | 2.7%    |
| SK hynix SH920 mSATA 128GB SSD        | 1         | 1      | 2.7%    |
| Seagate ST9200420ASG 200GB            | 1         | 1      | 2.7%    |
| Seagate ST3500418AS 500GB             | 1         | 1      | 2.7%    |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 2.7%    |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 2.7%    |
| Samsung Electronics SP2504C 250GB     | 1         | 1      | 2.7%    |
| Samsung Electronics HD160JJ 160GB     | 1         | 1      | 2.7%    |
| Maxtor 6E040L0 40GB                   | 1         | 1      | 2.7%    |
| Kingston SA400S37120G 120GB SSD       | 1         | 1      | 2.7%    |
| Intel SSDSC2BF120A5 120GB             | 1         | 3      | 2.7%    |
| HPE MB4000GEFNA 4TB                   | 1         | 2      | 2.7%    |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 2.7%    |
| Hitachi HTS726060M9AT00 56GB          | 1         | 1      | 2.7%    |
| HGST HTE721010A9E630 1TB              | 1         | 1      | 2.7%    |
| Hewlett-Packard VB0250EAVER 250GB     | 1         | 2      | 2.7%    |
| Fujitsu MHV2060BH PL 64GB             | 1         | 1      | 2.7%    |
| China SSD 256GB                       | 1         | 1      | 2.7%    |
| China SATA SSD 64GB                   | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 13     | 25.71%  |
| Seagate             | 6         | 6      | 17.14%  |
| Hitachi             | 4         | 4      | 11.43%  |
| HGST                | 3         | 3      | 8.57%   |
| Toshiba             | 2         | 2      | 5.71%   |
| Samsung Electronics | 2         | 3      | 5.71%   |
| China               | 2         | 2      | 5.71%   |
| SK hynix            | 1         | 1      | 2.86%   |
| Maxtor              | 1         | 1      | 2.86%   |
| Kingston            | 1         | 1      | 2.86%   |
| Intel               | 1         | 3      | 2.86%   |
| HPE                 | 1         | 2      | 2.86%   |
| Hewlett-Packard     | 1         | 2      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 13     | 31.03%  |
| Seagate             | 6         | 6      | 20.69%  |
| Hitachi             | 4         | 4      | 13.79%  |
| HGST                | 3         | 3      | 10.34%  |
| Toshiba             | 2         | 2      | 6.9%    |
| Samsung Electronics | 1         | 2      | 3.45%   |
| Maxtor              | 1         | 1      | 3.45%   |
| HPE                 | 1         | 2      | 3.45%   |
| Hewlett-Packard     | 1         | 2      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 36     | 82.86%  |
| SSD  | 5         | 7      | 14.29%  |
| NVMe | 1         | 1      | 2.86%   |

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
| Works    | 134       | 240    | 62.91%  |
| Detected | 45        | 70     | 21.13%  |
| Malfunc  | 34        | 44     | 15.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 127       | 57.47%  |
| AMD                              | 30        | 13.57%  |
| Samsung Electronics              | 18        | 8.14%   |
| SanDisk                          | 8         | 3.62%   |
| Micron/Crucial Technology        | 6         | 2.71%   |
| SK hynix                         | 4         | 1.81%   |
| Kingston Technology Company      | 4         | 1.81%   |
| Toshiba America Info Systems     | 3         | 1.36%   |
| Marvell Technology Group         | 3         | 1.36%   |
| Lenovo                           | 2         | 0.9%    |
| Broadcom / LSI                   | 2         | 0.9%    |
| VIA Technologies                 | 1         | 0.45%   |
| Union Memory (Shenzhen)          | 1         | 0.45%   |
| Solid State Storage Technology   | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Nvidia                           | 1         | 0.45%   |
| Micron Technology                | 1         | 0.45%   |
| LSI Logic / Symbios Logic        | 1         | 0.45%   |
| Lite-On Technology               | 1         | 0.45%   |
| KIOXIA                           | 1         | 0.45%   |
| Integrated Technology Express    | 1         | 0.45%   |
| Chelsio Communications           | 1         | 0.45%   |
| ASMedia Technology               | 1         | 0.45%   |
| ADATA Technology                 | 1         | 0.45%   |
| Adaptec                          | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 7.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 3.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 2.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 2.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 2.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 2.3%    |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 2.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.53%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 1.53%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 4         | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 1.53%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.53%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 4         | 1.53%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4         | 1.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.15%   |
| AMD FCH IDE Controller                                                         | 3         | 1.15%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 1.15%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.77%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2         | 0.77%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                 | 2         | 0.77%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.77%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 129       | 57.08%  |
| NVMe | 52        | 23.01%  |
| IDE  | 30        | 13.27%  |
| RAID | 13        | 5.75%   |
| SCSI | 2         | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 147       | 79.89%  |
| AMD    | 35        | 19.02%  |
| ARM    | 2         | 1.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 2.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.62%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 1.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.62%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 2         | 1.08%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 2         | 1.08%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 1.08%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.08%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2         | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.08%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.08%   |
| ARM Nokia RX-51 board Processor             | 2         | 1.08%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 2         | 1.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2         | 1.08%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 1.08%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.08%   |
| AMD FX-8300 Eight-Core Processor            | 2         | 1.08%   |
| Intel Xeon CPU X3460 @ 2.80GHz              | 1         | 0.54%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.54%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1         | 0.54%   |
| Intel Xeon CPU E5-2643 v3 @ 3.40GHz         | 1         | 0.54%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz          | 1         | 0.54%   |
| Intel Xeon CPU E5-2603 v4 @ 1.70GHz         | 1         | 0.54%   |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz         | 1         | 0.54%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1         | 0.54%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.54%   |
| Intel Pentium M processor 1700MHz           | 1         | 0.54%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.54%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 0.54%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.54%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.54%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.54%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.54%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 0.54%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.54%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.54%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.54%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.54%   |
| Intel Genuine CPU T1600 @ 1.66GHz           | 1         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 20%     |
| Intel Core i7           | 31        | 16.76%  |
| Intel Core i3           | 15        | 8.11%   |
| Intel Celeron           | 12        | 6.49%   |
| Intel Core 2 Duo        | 10        | 5.41%   |
| AMD Ryzen 5             | 10        | 5.41%   |
| Other                   | 9         | 4.86%   |
| Intel Xeon              | 8         | 4.32%   |
| AMD Ryzen 7             | 7         | 3.78%   |
| Intel Atom              | 6         | 3.24%   |
| Intel Pentium           | 3         | 1.62%   |
| Intel Core i9           | 3         | 1.62%   |
| Intel Core 2            | 3         | 1.62%   |
| AMD A10                 | 3         | 1.62%   |
| Intel Pentium M         | 2         | 1.08%   |
| Intel Pentium Dual-Core | 2         | 1.08%   |
| Intel Pentium Dual      | 2         | 1.08%   |
| Intel Core 2 Quad       | 2         | 1.08%   |
| AMD Ryzen 3             | 2         | 1.08%   |
| AMD FX                  | 2         | 1.08%   |
| Intel Pentium Silver    | 1         | 0.54%   |
| Intel Pentium Gold      | 1         | 0.54%   |
| Intel Pentium D         | 1         | 0.54%   |
| Intel Pentium 4         | 1         | 0.54%   |
| Intel Genuine           | 1         | 0.54%   |
| Intel Celeron M         | 1         | 0.54%   |
| AMD Sempron             | 1         | 0.54%   |
| AMD Ryzen Threadripper  | 1         | 0.54%   |
| AMD Ryzen 7 PRO         | 1         | 0.54%   |
| AMD E2                  | 1         | 0.54%   |
| AMD E                   | 1         | 0.54%   |
| AMD Athlon II           | 1         | 0.54%   |
| AMD Athlon              | 1         | 0.54%   |
| AMD A8                  | 1         | 0.54%   |
| AMD A6                  | 1         | 0.54%   |
| AMD A4                  | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 79        | 42.93%  |
| 4      | 56        | 30.43%  |
| 6      | 22        | 11.96%  |
| 1      | 12        | 6.52%   |
| 8      | 9         | 4.89%   |
| 12     | 3         | 1.63%   |
| 10     | 2         | 1.09%   |
| 24     | 1         | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 183       | 99.46%  |
| 2      | 1         | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 108       | 58.38%  |
| 1      | 77        | 41.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 176       | 95.65%  |
| 32-bit         | 4         | 2.17%   |
| Unknown        | 4         | 2.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 25.65%  |
| 0x306c3    | 10        | 5.24%   |
| 0x1067a    | 9         | 4.71%   |
| 0x906ea    | 8         | 4.19%   |
| 0x306a9    | 8         | 4.19%   |
| 0x206a7    | 8         | 4.19%   |
| 0x806ec    | 7         | 3.66%   |
| 0x406e3    | 7         | 3.66%   |
| 0x40651    | 4         | 2.09%   |
| 0x20655    | 4         | 2.09%   |
| 0x806ea    | 3         | 1.57%   |
| 0x706a1    | 3         | 1.57%   |
| 0x6fd      | 3         | 1.57%   |
| 0x406c4    | 3         | 1.57%   |
| 0x306d4    | 3         | 1.57%   |
| 0x30678    | 3         | 1.57%   |
| 0x0800820d | 3         | 1.57%   |
| 0x906ed    | 2         | 1.05%   |
| 0x906e9    | 2         | 1.05%   |
| 0x906a3    | 2         | 1.05%   |
| 0x806c1    | 2         | 1.05%   |
| 0x706a8    | 2         | 1.05%   |
| 0x6f6      | 2         | 1.05%   |
| 0x506e3    | 2         | 1.05%   |
| 0x106e5    | 2         | 1.05%   |
| 0x0a20120a | 2         | 1.05%   |
| 0x08701021 | 2         | 1.05%   |
| 0x08608103 | 2         | 1.05%   |
| 0x0810100b | 2         | 1.05%   |
| 0xf49      | 1         | 0.52%   |
| 0xa0655    | 1         | 0.52%   |
| 0xa0653    | 1         | 0.52%   |
| 0x906a4    | 1         | 0.52%   |
| 0x6d8      | 1         | 0.52%   |
| 0x695      | 1         | 0.52%   |
| 0x686      | 1         | 0.52%   |
| 0x506c9    | 1         | 0.52%   |
| 0x406f1    | 1         | 0.52%   |
| 0x406d8    | 1         | 0.52%   |
| 0x306f2    | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 15.68%  |
| Haswell          | 19        | 10.27%  |
| Penryn           | 11        | 5.95%   |
| IvyBridge        | 11        | 5.95%   |
| Skylake          | 10        | 5.41%   |
| SandyBridge      | 10        | 5.41%   |
| Core             | 10        | 5.41%   |
| Silvermont       | 9         | 4.86%   |
| Westmere         | 7         | 3.78%   |
| Unknown          | 7         | 3.78%   |
| Zen 2            | 6         | 3.24%   |
| Zen              | 6         | 3.24%   |
| Zen+             | 5         | 2.7%    |
| Piledriver       | 5         | 2.7%    |
| Goldmont plus    | 5         | 2.7%    |
| Broadwell        | 5         | 2.7%    |
| P6               | 4         | 2.16%   |
| Nehalem          | 4         | 2.16%   |
| TigerLake        | 3         | 1.62%   |
| Zen 3            | 2         | 1.08%   |
| NetBurst         | 2         | 1.08%   |
| Excavator        | 2         | 1.08%   |
| CometLake        | 2         | 1.08%   |
| Bonnell          | 2         | 1.08%   |
| Bobcat           | 2         | 1.08%   |
| Alderlake Hybrid | 2         | 1.08%   |
| Puma             | 1         | 0.54%   |
| K8 Hammer        | 1         | 0.54%   |
| K10 Llano        | 1         | 0.54%   |
| K10              | 1         | 0.54%   |
| Goldmont         | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 112       | 56%     |
| AMD                              | 45        | 22.5%   |
| Nvidia                           | 40        | 20%     |
| Silicon Integrated Systems [SiS] | 1         | 0.5%    |
| Matrox Electronics Systems       | 1         | 0.5%    |
| ASPEED Technology                | 1         | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 3.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.9%    |
| Intel HD Graphics 5500                                                                   | 4         | 1.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.9%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 1.43%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.43%   |
| Intel HD Graphics 620                                                                    | 3         | 1.43%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.43%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.43%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 1.43%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.95%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 0.95%   |
| Nvidia G96CGL [Quadro FX 580]                                                            | 2         | 0.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.95%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.95%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.95%   |
| AMD Lucienne                                                                             | 2         | 0.95%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.48%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.48%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.48%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 47.83%  |
| 1 x AMD        | 36        | 19.57%  |
| 1 x Nvidia     | 26        | 14.13%  |
| Intel + Nvidia | 14        | 7.61%   |
| Other          | 5         | 2.72%   |
| 2 x AMD        | 5         | 2.72%   |
| Intel + AMD    | 4         | 2.17%   |
| 2 x Intel      | 3         | 1.63%   |
| 1 x SiS        | 1         | 0.54%   |
| 1 x Matrox     | 1         | 0.54%   |
| 1 x ASPEED     | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 155       | 83.78%  |
| Proprietary | 20        | 10.81%  |
| Unknown     | 10        | 5.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 122       | 65.24%  |
| 0.01-0.5   | 21        | 11.23%  |
| 0.51-1.0   | 11        | 5.88%   |
| 7.01-8.0   | 9         | 4.81%   |
| 3.01-4.0   | 9         | 4.81%   |
| 1.01-2.0   | 7         | 3.74%   |
| 5.01-6.0   | 5         | 2.67%   |
| 2.01-3.0   | 3         | 1.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 29        | 14.65%  |
| AU Optronics            | 24        | 12.12%  |
| LG Display              | 22        | 11.11%  |
| Chimei Innolux          | 13        | 6.57%   |
| BOE                     | 13        | 6.57%   |
| Hewlett-Packard         | 10        | 5.05%   |
| Dell                    | 8         | 4.04%   |
| Acer                    | 8         | 4.04%   |
| Philips                 | 7         | 3.54%   |
| Goldstar                | 7         | 3.54%   |
| Ancor Communications    | 7         | 3.54%   |
| Lenovo                  | 6         | 3.03%   |
| AOC                     | 6         | 3.03%   |
| Unknown                 | 4         | 2.02%   |
| PANDA                   | 4         | 2.02%   |
| Iiyama                  | 4         | 2.02%   |
| Chi Mei Optoelectronics | 3         | 1.52%   |
| MStar                   | 2         | 1.01%   |
| Apple                   | 2         | 1.01%   |
| ___                     | 1         | 0.51%   |
| ViewSonic               | 1         | 0.51%   |
| Toshiba                 | 1         | 0.51%   |
| STD                     | 1         | 0.51%   |
| Sony                    | 1         | 0.51%   |
| Sharp                   | 1         | 0.51%   |
| MSI                     | 1         | 0.51%   |
| Lenovo Group Limited    | 1         | 0.51%   |
| InnoLux Display         | 1         | 0.51%   |
| InfoVision              | 1         | 0.51%   |
| HJW                     | 1         | 0.51%   |
| Hisense                 | 1         | 0.51%   |
| eMachines               | 1         | 0.51%   |
| Eizo                    | 1         | 0.51%   |
| CVT                     | 1         | 0.51%   |
| CPT                     | 1         | 0.51%   |
| CHI                     | 1         | 0.51%   |
| BenQ                    | 1         | 0.51%   |
| Unknown                 | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.99%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch   | 2         | 0.99%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch      | 2         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch  | 2         | 0.99%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                      | 2         | 0.99%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                         | 2         | 0.99%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 0.99%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch              | 2         | 0.99%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.99%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                      | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch          | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 2         | 0.99%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                     | 2         | 0.99%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1         | 0.5%    |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1         | 0.5%    |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.5%    |
| Unknown LCD Monitor hp L1702 1280x1024                                 | 1         | 0.5%    |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                      | 1         | 0.5%    |
| STD HDMI TV STD00C7 1440x900 698x392mm 31.5-inch                       | 1         | 0.5%    |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                         | 1         | 0.5%    |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.5%    |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch      | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch   | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0029 2048x1536 312x234mm 15.4-inch   | 1         | 0.5%    |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch    | 1         | 0.5%    |
| Samsung Electronics S24B300 SAM08B3 1920x1080 520x290mm 23.4-inch      | 1         | 0.5%    |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SyncMaster                             | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 78        | 41.05%  |
| 1366x768 (WXGA)    | 44        | 23.16%  |
| 3840x2160 (4K)     | 10        | 5.26%   |
| 1280x1024 (SXGA)   | 9         | 4.74%   |
| 1600x900 (HD+)     | 8         | 4.21%   |
| 1920x1200 (WUXGA)  | 6         | 3.16%   |
| 1440x900 (WXGA+)   | 6         | 3.16%   |
| 1280x800 (WXGA)    | 5         | 2.63%   |
| 2560x1440 (QHD)    | 4         | 2.11%   |
| Unknown            | 3         | 1.58%   |
| 5760x1080          | 2         | 1.05%   |
| 3440x1440          | 2         | 1.05%   |
| 2288x1287          | 2         | 1.05%   |
| 1680x1050 (WSXGA+) | 2         | 1.05%   |
| 1600x1200          | 2         | 1.05%   |
| 3000x2000          | 1         | 0.53%   |
| 2736x1824          | 1         | 0.53%   |
| 2160x1440          | 1         | 0.53%   |
| 2048x1152          | 1         | 0.53%   |
| 1360x768           | 1         | 0.53%   |
| 1024x768 (XGA)     | 1         | 0.53%   |
| 1024x600           | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46        | 23.83%  |
| 14      | 18        | 9.33%   |
| 24      | 16        | 8.29%   |
| 21      | 16        | 8.29%   |
| 13      | 13        | 6.74%   |
| 27      | 11        | 5.7%    |
| 12      | 11        | 5.7%    |
| Unknown | 10        | 5.18%   |
| 23      | 9         | 4.66%   |
| 17      | 9         | 4.66%   |
| 11      | 5         | 2.59%   |
| 19      | 4         | 2.07%   |
| 31      | 3         | 1.55%   |
| 18      | 3         | 1.55%   |
| 142     | 2         | 1.04%   |
| 72      | 2         | 1.04%   |
| 54      | 2         | 1.04%   |
| 52      | 2         | 1.04%   |
| 34      | 2         | 1.04%   |
| 25      | 2         | 1.04%   |
| 46      | 1         | 0.52%   |
| 40      | 1         | 0.52%   |
| 26      | 1         | 0.52%   |
| 22      | 1         | 0.52%   |
| 20      | 1         | 0.52%   |
| 16      | 1         | 0.52%   |
| 10      | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 72        | 38.5%   |
| 501-600        | 36        | 19.25%  |
| 201-300        | 25        | 13.37%  |
| 401-500        | 21        | 11.23%  |
| Unknown        | 10        | 5.35%   |
| 351-400        | 8         | 4.28%   |
| 1001-1500      | 5         | 2.67%   |
| 601-700        | 3         | 1.6%    |
| More than 2000 | 2         | 1.07%   |
| 701-800        | 2         | 1.07%   |
| 1501-2000      | 2         | 1.07%   |
| 801-900        | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 131       | 75.72%  |
| 16/10   | 17        | 9.83%   |
| Unknown | 7         | 4.05%   |
| 5/4     | 6         | 3.47%   |
| 4/3     | 4         | 2.31%   |
| 3/2     | 3         | 1.73%   |
| 21/9    | 2         | 1.16%   |
| 1.00    | 2         | 1.16%   |
| 6/5     | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 44        | 23.04%  |
| 201-250        | 34        | 17.8%   |
| 81-90          | 23        | 12.04%  |
| 61-70          | 11        | 5.76%   |
| 301-350        | 11        | 5.76%   |
| Unknown        | 10        | 5.24%   |
| More than 1000 | 8         | 4.19%   |
| 71-80          | 8         | 4.19%   |
| 151-200        | 8         | 4.19%   |
| 251-300        | 7         | 3.66%   |
| 141-150        | 7         | 3.66%   |
| 51-60          | 5         | 2.62%   |
| 351-500        | 5         | 2.62%   |
| 121-130        | 3         | 1.57%   |
| 111-120        | 3         | 1.57%   |
| 501-1000       | 2         | 1.05%   |
| 41-50          | 1         | 0.52%   |
| 131-140        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 57        | 30.32%  |
| 101-120       | 52        | 27.66%  |
| 121-160       | 48        | 25.53%  |
| Unknown       | 10        | 5.32%   |
| 1-50          | 9         | 4.79%   |
| 161-240       | 9         | 4.79%   |
| More than 240 | 3         | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 151       | 79.89%  |
| 2     | 26        | 13.76%  |
| 3     | 6         | 3.17%   |
| 0     | 6         | 3.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 89        | 32.72%  |
| Intel                            | 89        | 32.72%  |
| Qualcomm Atheros                 | 33        | 12.13%  |
| Broadcom                         | 13        | 4.78%   |
| Marvell Technology Group         | 7         | 2.57%   |
| Ralink Technology                | 6         | 2.21%   |
| NetGear                          | 4         | 1.47%   |
| MediaTek                         | 4         | 1.47%   |
| Sierra Wireless                  | 3         | 1.1%    |
| Samsung Electronics              | 3         | 1.1%    |
| Broadcom Limited                 | 3         | 1.1%    |
| TP-Link                          | 2         | 0.74%   |
| JMicron Technology               | 2         | 0.74%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.37%   |
| Xiaomi                           | 1         | 0.37%   |
| VIA Technologies                 | 1         | 0.37%   |
| Solarflare Communications        | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Ralink                           | 1         | 0.37%   |
| Nvidia                           | 1         | 0.37%   |
| ICS Advent                       | 1         | 0.37%   |
| Huawei Technologies              | 1         | 0.37%   |
| DisplayLink                      | 1         | 0.37%   |
| Dell                             | 1         | 0.37%   |
| D-Link System                    | 1         | 0.37%   |
| Chelsio Communications           | 1         | 0.37%   |
| ASIX Electronics                 | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 59        | 18.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 4.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 3.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.17%   |
| Intel Wireless 7260                                                     | 6         | 1.86%   |
| Intel Ethernet Connection (7) I219-LM                                   | 6         | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.86%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.55%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.24%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.24%   |
| Intel Wireless 8260                                                     | 4         | 1.24%   |
| Intel Wireless 7265                                                     | 4         | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.93%   |
| Intel Ethernet Controller I225-V                                        | 3         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.93%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 2         | 0.62%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.62%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.62%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.62%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                 | 2         | 0.62%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.62%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.62%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.62%   |
| Intel I350 Gigabit Network Connection                                   | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 52        | 39.39%  |
| Qualcomm Atheros         | 29        | 21.97%  |
| Realtek Semiconductor    | 22        | 16.67%  |
| Ralink Technology        | 6         | 4.55%   |
| Broadcom                 | 6         | 4.55%   |
| NetGear                  | 4         | 3.03%   |
| Sierra Wireless          | 3         | 2.27%   |
| MediaTek                 | 3         | 2.27%   |
| Broadcom Limited         | 3         | 2.27%   |
| TP-Link                  | 1         | 0.76%   |
| Ralink                   | 1         | 0.76%   |
| Marvell Technology Group | 1         | 0.76%   |
| Dell                     | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 5.3%    |
| Intel Wireless 7260                                                     | 6         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.55%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.03%   |
| Intel Wireless 8260                                                     | 4         | 3.03%   |
| Intel Wireless 7265                                                     | 4         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.27%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 2         | 1.52%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.52%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.52%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                 | 2         | 1.52%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.52%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.52%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.52%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.52%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.52%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.76%   |
| Sierra Wireless EM7455                                                  | 1         | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.76%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.76%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 81        | 43.78%  |
| Intel                            | 66        | 35.68%  |
| Broadcom                         | 7         | 3.78%   |
| Qualcomm Atheros                 | 6         | 3.24%   |
| Marvell Technology Group         | 6         | 3.24%   |
| Samsung Electronics              | 3         | 1.62%   |
| JMicron Technology               | 2         | 1.08%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.54%   |
| Xiaomi                           | 1         | 0.54%   |
| VIA Technologies                 | 1         | 0.54%   |
| TP-Link                          | 1         | 0.54%   |
| Solarflare Communications        | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.54%   |
| Nvidia                           | 1         | 0.54%   |
| MediaTek                         | 1         | 0.54%   |
| ICS Advent                       | 1         | 0.54%   |
| Huawei Technologies              | 1         | 0.54%   |
| DisplayLink                      | 1         | 0.54%   |
| D-Link System                    | 1         | 0.54%   |
| Chelsio Communications           | 1         | 0.54%   |
| ASIX Electronics                 | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 31.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 7.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 6.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 3.19%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.6%    |
| Intel Ethernet Controller I225-V                                  | 3         | 1.6%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.06%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.06%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 1.06%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.06%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.06%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.06%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.06%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.53%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.53%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.53%   |
| MediaTek moto e22                                                 | 1         | 0.53%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.53%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.53%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 169       | 57.09%  |
| WiFi     | 124       | 41.89%  |
| Modem    | 3         | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 99        | 52.66%  |
| WiFi     | 89        | 47.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 101       | 54.3%   |
| 1     | 72        | 38.71%  |
| 0     | 6         | 3.23%   |
| 3     | 3         | 1.61%   |
| 4     | 2         | 1.08%   |
| 7     | 1         | 0.54%   |
| 5     | 1         | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 157       | 85.33%  |
| Yes  | 27        | 14.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 40.45%  |
| Qualcomm Atheros Communications | 10        | 11.24%  |
| Realtek Semiconductor           | 9         | 10.11%  |
| Broadcom                        | 5         | 5.62%   |
| Dell                            | 4         | 4.49%   |
| ASUSTek Computer                | 4         | 4.49%   |
| Lite-On Technology              | 3         | 3.37%   |
| IMC Networks                    | 3         | 3.37%   |
| Cambridge Silicon Radio         | 3         | 3.37%   |
| Foxconn International           | 2         | 2.25%   |
| Foxconn / Hon Hai               | 2         | 2.25%   |
| Apple                           | 2         | 2.25%   |
| TP-Link                         | 1         | 1.12%   |
| Realtek                         | 1         | 1.12%   |
| Ralink                          | 1         | 1.12%   |
| MediaTek                        | 1         | 1.12%   |
| Marvell Semiconductor           | 1         | 1.12%   |
| Hewlett-Packard                 | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 17.98%  |
| Realtek Bluetooth Radio                             | 9         | 10.11%  |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 8.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 8.99%   |
| Intel AX200 Bluetooth                               | 5         | 5.62%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 3.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.25%   |
| Intel Bluetooth Device                              | 2         | 2.25%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 2.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.25%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 2.25%   |
| ASUS Bluetooth Device                               | 2         | 2.25%   |
| TP-Link UB500 Adapter                               | 1         | 1.12%   |
| Realtek Bluetooth Radio                             | 1         | 1.12%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.12%   |
| MediaTek Wireless_Device                            | 1         | 1.12%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.12%   |
| IMC Networks Bluetooth Device                       | 1         | 1.12%   |
| IMC Networks BCM20702A0                             | 1         | 1.12%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.12%   |
| Foxconn / Hon Hai BT                                | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.12%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 1.12%   |
| Broadcom Broadcom BCM2070 Bluetooth Device          | 1         | 1.12%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 1.12%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.12%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.12%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 136       | 56.2%   |
| AMD                              | 43        | 17.77%  |
| Nvidia                           | 31        | 12.81%  |
| Creative Labs                    | 6         | 2.48%   |
| C-Media Electronics              | 4         | 1.65%   |
| Texas Instruments                | 2         | 0.83%   |
| Plantronics                      | 2         | 0.83%   |
| TEAC                             | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Sennheiser Communications        | 1         | 0.41%   |
| Realtek Semiconductor            | 1         | 0.41%   |
| M-Audio                          | 1         | 0.41%   |
| Logitech                         | 1         | 0.41%   |
| KORG                             | 1         | 0.41%   |
| GYROCOM C&C                      | 1         | 0.41%   |
| GN Netcom                        | 1         | 0.41%   |
| Giga-Byte Technology             | 1         | 0.41%   |
| Generalplus Technology           | 1         | 0.41%   |
| Focusrite-Novation               | 1         | 0.41%   |
| Elite Silicon                    | 1         | 0.41%   |
| DCMT Technology                  | 1         | 0.41%   |
| Cirrus Logic                     | 1         | 0.41%   |
| Blue Microphones                 | 1         | 0.41%   |
| Avance Logic                     | 1         | 0.41%   |
| ASUSTek Computer                 | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 13        | 4.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 4.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 3.81%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 3.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 3.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 3.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 3.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 2.77%   |
| AMD FCH Azalia Controller                                                  | 6         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.73%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.73%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 1.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 1.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.38%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.38%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.38%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 1.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.04%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 3         | 1.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.04%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2         | 0.69%   |
| Plantronics HD1                                                            | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 22.22%  |
| SK hynix            | 26        | 13.76%  |
| Unknown             | 24        | 12.7%   |
| Kingston            | 24        | 12.7%   |
| Corsair             | 15        | 7.94%   |
| Micron Technology   | 11        | 5.82%   |
| G.Skill             | 8         | 4.23%   |
| Crucial             | 7         | 3.7%    |
| A-DATA Technology   | 7         | 3.7%    |
| Nanya Technology    | 4         | 2.12%   |
| Unknown (ABCD)      | 3         | 1.59%   |
| Unknown             | 3         | 1.59%   |
| Transcend           | 2         | 1.06%   |
| Ramaxel Technology  | 2         | 1.06%   |
| Unknown (F785)      | 1         | 0.53%   |
| Unknown (130B)      | 1         | 0.53%   |
| Team                | 1         | 0.53%   |
| Smart               | 1         | 0.53%   |
| GOODRAM             | 1         | 0.53%   |
| Goldkey             | 1         | 0.53%   |
| Avant               | 1         | 0.53%   |
| Apacer              | 1         | 0.53%   |
| A Force             | 1         | 0.53%   |
| 4ea5                | 1         | 0.53%   |
| 48spaces            | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 3         | 1.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 3         | 1.42%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 3         | 1.42%   |
| Unknown                                                        | 3         | 1.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 2         | 0.95%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 2         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2         | 0.95%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.95%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.95%   |
| Samsung RAM M471B5173CB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 2         | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 2         | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.95%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.95%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 2         | 0.95%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.95%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 2         | 0.95%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 2         | 0.95%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 3000MT/s          | 2         | 0.95%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s      | 1         | 0.47%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 0.47%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1         | 0.47%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s                     | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM 667MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s                     | 1         | 0.47%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 1         | 0.47%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                     | 1         | 0.47%   |
| Unknown RAM Module 1024MB DIMM DDR                             | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 67        | 41.88%  |
| DDR3    | 62        | 38.75%  |
| DDR2    | 8         | 5%      |
| SDRAM   | 5         | 3.13%   |
| DDR     | 5         | 3.13%   |
| LPDDR4  | 4         | 2.5%    |
| LPDDR3  | 4         | 2.5%    |
| Unknown | 3         | 1.88%   |
| DRAM    | 1         | 0.63%   |
| DDR5    | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 92        | 58.23%  |
| DIMM         | 60        | 37.97%  |
| Row Of Chips | 4         | 2.53%   |
| Chip         | 1         | 0.63%   |
| Unknown      | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 64        | 35.16%  |
| 4096  | 46        | 25.27%  |
| 16384 | 30        | 16.48%  |
| 2048  | 25        | 13.74%  |
| 1024  | 8         | 4.4%    |
| 32768 | 5         | 2.75%   |
| 512   | 1         | 0.55%   |
| 256   | 1         | 0.55%   |
| 128   | 1         | 0.55%   |
| 64    | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 39        | 22.29%  |
| 2667    | 25        | 14.29%  |
| 3200    | 15        | 8.57%   |
| 2400    | 14        | 8%      |
| 1333    | 11        | 6.29%   |
| 2133    | 10        | 5.71%   |
| Unknown | 7         | 4%      |
| 3600    | 6         | 3.43%   |
| 667     | 6         | 3.43%   |
| 1067    | 5         | 2.86%   |
| 800     | 5         | 2.86%   |
| 3400    | 4         | 2.29%   |
| 3266    | 3         | 1.71%   |
| 1867    | 3         | 1.71%   |
| 1800    | 3         | 1.71%   |
| 1066    | 3         | 1.71%   |
| 4199    | 2         | 1.14%   |
| 3000    | 2         | 1.14%   |
| 4800    | 1         | 0.57%   |
| 3666    | 1         | 0.57%   |
| 3534    | 1         | 0.57%   |
| 2933    | 1         | 0.57%   |
| 2666    | 1         | 0.57%   |
| 1866    | 1         | 0.57%   |
| 1632    | 1         | 0.57%   |
| 1334    | 1         | 0.57%   |
| 1200    | 1         | 0.57%   |
| 975     | 1         | 0.57%   |
| 400     | 1         | 0.57%   |
| 100     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 3         | 42.86%  |
| Samsung Electronics    | 1         | 14.29%  |
| Custom Engineering SPA | 1         | 14.29%  |
| Canon                  | 1         | 14.29%  |
| Brother Industries     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-4600 Series         | 1         | 14.29%  |
| HP ENVY 5000 series             | 1         | 14.29%  |
| HP DeskJet F4200 series         | 1         | 14.29%  |
| HP Deskjet 1050 J410            | 1         | 14.29%  |
| Custom Engineering SPA KUBE USB | 1         | 14.29%  |
| Canon G1010 series              | 1         | 14.29%  |
| Brother HL-L2375DW series       | 1         | 14.29%  |

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
| Chicony Electronics                    | 30        | 29.7%   |
| Microdia                               | 8         | 7.92%   |
| Logitech                               | 7         | 6.93%   |
| Bison Electronics                      | 7         | 6.93%   |
| Sunplus Innovation Technology          | 6         | 5.94%   |
| Realtek Semiconductor                  | 5         | 4.95%   |
| IMC Networks                           | 4         | 3.96%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.96%   |
| Quanta                                 | 3         | 2.97%   |
| Lite-On Technology                     | 3         | 2.97%   |
| Acer                                   | 3         | 2.97%   |
| Z-Star Microelectronics                | 2         | 1.98%   |
| Suyin                                  | 2         | 1.98%   |
| KYE Systems (Mouse Systems)            | 2         | 1.98%   |
| Cubeternet                             | 2         | 1.98%   |
| Softkinetic                            | 1         | 0.99%   |
| Silicon Motion                         | 1         | 0.99%   |
| Samsung Electronics                    | 1         | 0.99%   |
| OmniVision Technologies                | 1         | 0.99%   |
| Mustek Systems                         | 1         | 0.99%   |
| Microsoft                              | 1         | 0.99%   |
| MacroSilicon                           | 1         | 0.99%   |
| Luxvisions Innotech Limited            | 1         | 0.99%   |
| LG Electronics                         | 1         | 0.99%   |
| kingcome                               | 1         | 0.99%   |
| Hauppauge                              | 1         | 0.99%   |
| GEMBIRD                                | 1         | 0.99%   |
| Apple                                  | 1         | 0.99%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 10        | 9.9%    |
| Logitech Webcam C270                     | 3         | 2.97%   |
| Chicony HD WebCam                        | 3         | 2.97%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.98%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.98%   |
| Logitech HD Pro Webcam C920              | 2         | 1.98%   |
| IMC Networks Integrated Camera           | 2         | 1.98%   |
| Cubeternet GL-UPC822 UVC WebCam          | 2         | 1.98%   |
| Chicony HP TrueVision HD Camera          | 2         | 1.98%   |
| Chicony EasyCamera                       | 2         | 1.98%   |
| Bison Integrated Camera                  | 2         | 1.98%   |
| Z-Star Webcam                            | 1         | 0.99%   |
| Z-Star A4 TECH USB2.0 PC Camera E        | 1         | 0.99%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 0.99%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.99%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 0.99%   |
| Sunplus Dell Integrated Webcam           | 1         | 0.99%   |
| Sunplus ASUS USB2.0 Webcam               | 1         | 0.99%   |
| Sunplus 720p HD Camera                   | 1         | 0.99%   |
| Softkinetic DepthSense 325               | 1         | 0.99%   |
| Silicon Motion HP Webcam-101             | 1         | 0.99%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1         | 0.99%   |
| Realtek Lenovo EasyCamera                | 1         | 0.99%   |
| Realtek Integrated Webcam_HD             | 1         | 0.99%   |
| Realtek HD 720P Webcam                   | 1         | 0.99%   |
| Quanta Sony Visual Communication Camera  | 1         | 0.99%   |
| Quanta HP HD Camera                      | 1         | 0.99%   |
| Quanta HD User Facing                    | 1         | 0.99%   |
| OmniVision OV2640 Webcam                 | 1         | 0.99%   |
| Mustek Systems USB 2.0 PC Camera         | 1         | 0.99%   |
| Microsoft LifeCam Studio                 | 1         | 0.99%   |
| Microdia Webcam Vitade AF                | 1         | 0.99%   |
| Microdia WebCam SC-13HDL12639P           | 1         | 0.99%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 0.99%   |
| Microdia Integrated_Webcam_HD            | 1         | 0.99%   |
| Microdia Integrated Webcam               | 1         | 0.99%   |
| Microdia Dell Integrated HD Webcam       | 1         | 0.99%   |
| Microdia Camera                          | 1         | 0.99%   |
| Microdia 1.3 MPixel Integrated Webcam    | 1         | 0.99%   |
| MacroSilicon USB3. 0 capture             | 1         | 0.99%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 50%     |
| Validity Sensors           | 3         | 21.43%  |
| STMicroelectronics         | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 2         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 14.29%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics WBDI Device                                  | 1         | 7.14%   |
| Synaptics UWP WBDI                                     | 1         | 7.14%   |
| Synaptics TouchPad                                     | 1         | 7.14%   |
| Synaptics Fingerprint scanner                          | 1         | 7.14%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 55.56%  |
| Alcor Micro | 7         | 38.89%  |
| Lenovo      | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 38.89%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 16.67%  |
| Broadcom 5880                                                                | 2         | 11.11%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.56%   |
| Broadcom 58200                                                               | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 128       | 67.72%  |
| 1     | 44        | 23.28%  |
| 2     | 13        | 6.88%   |
| 3     | 3         | 1.59%   |
| 5     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 15        | 21.43%  |
| Fingerprint reader       | 14        | 20%     |
| Chipcard                 | 13        | 18.57%  |
| Net/wireless             | 7         | 10%     |
| Communication controller | 6         | 8.57%   |
| Unassigned class         | 4         | 5.71%   |
| Camera                   | 4         | 5.71%   |
| Multimedia controller    | 2         | 2.86%   |
| Bluetooth                | 2         | 2.86%   |
| Storage                  | 1         | 1.43%   |
| Net/ethernet             | 1         | 1.43%   |
| Firewire controller      | 1         | 1.43%   |

