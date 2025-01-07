Devuan - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Devuan.

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

Total: 163

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Purism        | Librem 14                   | [5f54d4d304](https://linux-hardware.org/?probe=5f54d4d304) | Jan 01, 2025 |
| Lenovo        | IdeaPad Y460                | [3c6931e293](https://linux-hardware.org/?probe=3c6931e293) | Dec 27, 2024 |
| ASUSTek       | K50IE                       | [6b1d699417](https://linux-hardware.org/?probe=6b1d699417) | Nov 30, 2024 |
| ASUSTek       | K50IE                       | [2b124f3ff4](https://linux-hardware.org/?probe=2b124f3ff4) | Nov 28, 2024 |
| Dell          | Latitude E5500              | [872edd1a02](https://linux-hardware.org/?probe=872edd1a02) | Nov 15, 2024 |
| Acer          | Aspire E5-576               | [a8438fb58b](https://linux-hardware.org/?probe=a8438fb58b) | Nov 13, 2024 |
| Lenovo        | ThinkPad X200 7459D12       | [a34523d690](https://linux-hardware.org/?probe=a34523d690) | Nov 05, 2024 |
| Notebook      | NV4XMB,ME,MZ                | [f32872a46b](https://linux-hardware.org/?probe=f32872a46b) | Oct 22, 2024 |
| Notebook      | NV4XMB,ME,MZ                | [d657be30d1](https://linux-hardware.org/?probe=d657be30d1) | Oct 22, 2024 |
| HP            | Victus by Gaming Laptop ... | [6a8043a39f](https://linux-hardware.org/?probe=6a8043a39f) | Sep 21, 2024 |
| HP            | Victus by Gaming Laptop ... | [17fd2f1a0d](https://linux-hardware.org/?probe=17fd2f1a0d) | Sep 21, 2024 |
| Lenovo        | LOQ 15AHP9 83DX             | [b59950cf4a](https://linux-hardware.org/?probe=b59950cf4a) | Sep 03, 2024 |
| Lenovo        | ThinkPad X230 23259J6       | [3fee175541](https://linux-hardware.org/?probe=3fee175541) | Aug 27, 2024 |
| Dell          | Latitude E6430              | [bdf4eb5fc6](https://linux-hardware.org/?probe=bdf4eb5fc6) | Jul 29, 2024 |
| Framework     | Laptop                      | [8436ce2126](https://linux-hardware.org/?probe=8436ce2126) | Jul 22, 2024 |
| ASUSTek       | TUF Gaming FX505GD          | [e269bf0952](https://linux-hardware.org/?probe=e269bf0952) | Jul 14, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [df123831be](https://linux-hardware.org/?probe=df123831be) | Jul 13, 2024 |
| Lenovo        | ThinkPad X230 4290EM6       | [ec3109a514](https://linux-hardware.org/?probe=ec3109a514) | Jul 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [e482f45dc4](https://linux-hardware.org/?probe=e482f45dc4) | Jul 06, 2024 |
| Acer          | Aspire 5742Z                | [47307ae042](https://linux-hardware.org/?probe=47307ae042) | Jun 23, 2024 |
| Acer          | Nitro AN515-42              | [090323c57b](https://linux-hardware.org/?probe=090323c57b) | May 20, 2024 |
| Dell          | XPS 13 9360                 | [536f8ed319](https://linux-hardware.org/?probe=536f8ed319) | May 09, 2024 |
| System76      | Galago Pro                  | [06d9cca0d2](https://linux-hardware.org/?probe=06d9cca0d2) | Apr 27, 2024 |
| ASUSTek       | 1000H                       | [0463a4d88b](https://linux-hardware.org/?probe=0463a4d88b) | Apr 26, 2024 |
| Apple         | MacBookAir6,1               | [08ca3d5ea0](https://linux-hardware.org/?probe=08ca3d5ea0) | Apr 19, 2024 |
| Dell          | Studio 1558                 | [73fb46028c](https://linux-hardware.org/?probe=73fb46028c) | Apr 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2270faaf14](https://linux-hardware.org/?probe=2270faaf14) | Mar 07, 2024 |
| Lenovo        | ThinkPad X230 23252UU       | [7fb7bfaacd](https://linux-hardware.org/?probe=7fb7bfaacd) | Mar 05, 2024 |
| ASUSTek       | K55VJ                       | [88ee2dbed6](https://linux-hardware.org/?probe=88ee2dbed6) | Mar 03, 2024 |
| MACHENIKE     | T90-V                       | [01cb379c2e](https://linux-hardware.org/?probe=01cb379c2e) | Feb 24, 2024 |
| Maibenben     | MaiBook M                   | [7f6b3c0f92](https://linux-hardware.org/?probe=7f6b3c0f92) | Feb 13, 2024 |
| HP            | EliteBook 840 G6            | [6cac3b71e0](https://linux-hardware.org/?probe=6cac3b71e0) | Feb 01, 2024 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [b66d7c38c1](https://linux-hardware.org/?probe=b66d7c38c1) | Dec 31, 2023 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3834ee3d70](https://linux-hardware.org/?probe=3834ee3d70) | Dec 15, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [7af6ecc981](https://linux-hardware.org/?probe=7af6ecc981) | Dec 12, 2023 |
| Dell          | Latitude E6400              | [c23aa9b02a](https://linux-hardware.org/?probe=c23aa9b02a) | Dec 10, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [c72f209121](https://linux-hardware.org/?probe=c72f209121) | Dec 05, 2023 |
| Dell          | Latitude E6430              | [8b68261a59](https://linux-hardware.org/?probe=8b68261a59) | Nov 30, 2023 |
| Dell          | XPS 13 9370                 | [2961332bce](https://linux-hardware.org/?probe=2961332bce) | Nov 26, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1080... | [37c32a9af7](https://linux-hardware.org/?probe=37c32a9af7) | Nov 25, 2023 |
| HP            | G62                         | [9d6424c4cc](https://linux-hardware.org/?probe=9d6424c4cc) | Nov 24, 2023 |
| Acer          | Aspire A515-54G             | [8e8de2388b](https://linux-hardware.org/?probe=8e8de2388b) | Nov 21, 2023 |
| HP            | Presario C700               | [c8a9963f71](https://linux-hardware.org/?probe=c8a9963f71) | Nov 19, 2023 |
| HP            | Unknown                     | [3827b1fa19](https://linux-hardware.org/?probe=3827b1fa19) | Nov 16, 2023 |
| HP            | Unknown                     | [ef19087623](https://linux-hardware.org/?probe=ef19087623) | Nov 16, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EC00    | [820620d5c4](https://linux-hardware.org/?probe=820620d5c4) | Nov 01, 2023 |
| Samsung       | N150P                       | [83f77d7896](https://linux-hardware.org/?probe=83f77d7896) | Oct 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [cf522294f8](https://linux-hardware.org/?probe=cf522294f8) | Oct 18, 2023 |
| TUXEDO        | XP1610                      | [31be190f30](https://linux-hardware.org/?probe=31be190f30) | Oct 13, 2023 |
| Dell          | XPS M1530                   | [b24e393bbb](https://linux-hardware.org/?probe=b24e393bbb) | Sep 23, 2023 |
| Dell          | Inspiron 3583               | [56cd0e05e8](https://linux-hardware.org/?probe=56cd0e05e8) | Sep 22, 2023 |
| PC Special... | P7xxTM1                     | [2bdbc2f2e7](https://linux-hardware.org/?probe=2bdbc2f2e7) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | [f23bb97453](https://linux-hardware.org/?probe=f23bb97453) | Sep 11, 2023 |
| Sony          | VGN-FZ140E                  | [361226919e](https://linux-hardware.org/?probe=361226919e) | Sep 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [61906f4e91](https://linux-hardware.org/?probe=61906f4e91) | Sep 07, 2023 |
| Dell          | Inspiron 3585               | [89a0e93fd5](https://linux-hardware.org/?probe=89a0e93fd5) | Sep 05, 2023 |
| Intel         | powered classmate PC        | [f852524db2](https://linux-hardware.org/?probe=f852524db2) | Sep 01, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [44e328b3a0](https://linux-hardware.org/?probe=44e328b3a0) | Aug 24, 2023 |
| Lenovo        | ThinkPad X390 20Q1A005CD    | [c299d4ad92](https://linux-hardware.org/?probe=c299d4ad92) | Aug 15, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| ASUSTek       | T200TA                      | [affc999457](https://linux-hardware.org/?probe=affc999457) | Aug 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [67febbf0c0](https://linux-hardware.org/?probe=67febbf0c0) | Jul 27, 2023 |
| Samsung       | 550XDA                      | [c298263c6c](https://linux-hardware.org/?probe=c298263c6c) | Jul 22, 2023 |
| Dell          | Latitude E5500              | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Nokia         | N900                        | [7728c85b90](https://linux-hardware.org/?probe=7728c85b90) | Jul 06, 2023 |
| HP            | EliteBook 840 G6            | [d072001450](https://linux-hardware.org/?probe=d072001450) | Jul 04, 2023 |
| Toshiba       | Satellite L300              | [8b04801d40](https://linux-hardware.org/?probe=8b04801d40) | Jun 27, 2023 |
| Lenovo        | ThinkPad T410 2537DA3       | [067b7f26a2](https://linux-hardware.org/?probe=067b7f26a2) | Jun 25, 2023 |
| HP            | EliteBook 840 G6            | [82c9c200bc](https://linux-hardware.org/?probe=82c9c200bc) | Jun 20, 2023 |
| MSI           | Bravo 15 A4DDR              | [0e9ccef97f](https://linux-hardware.org/?probe=0e9ccef97f) | May 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [54f07f7d96](https://linux-hardware.org/?probe=54f07f7d96) | May 12, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [0d2ac684c8](https://linux-hardware.org/?probe=0d2ac684c8) | May 08, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [c67960852a](https://linux-hardware.org/?probe=c67960852a) | May 06, 2023 |
| HUAWEI        | HN-WX9X                     | [d07874c829](https://linux-hardware.org/?probe=d07874c829) | Apr 24, 2023 |
| Lenovo        | S20-30 20421                | [b9846b05e7](https://linux-hardware.org/?probe=b9846b05e7) | Apr 22, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [96e067f5c8](https://linux-hardware.org/?probe=96e067f5c8) | Apr 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [549f922cf6](https://linux-hardware.org/?probe=549f922cf6) | Apr 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [a9aa9ab39f](https://linux-hardware.org/?probe=a9aa9ab39f) | Apr 13, 2023 |
| Google        | Cyan                        | [f32e15dfef](https://linux-hardware.org/?probe=f32e15dfef) | Apr 09, 2023 |
| Dell          | G5 5505                     | [2552b456b6](https://linux-hardware.org/?probe=2552b456b6) | Mar 29, 2023 |
| ASUSTek       | G750JM                      | [98ba3a9ce6](https://linux-hardware.org/?probe=98ba3a9ce6) | Mar 25, 2023 |
| Google        | Bluebird                    | [2d18088551](https://linux-hardware.org/?probe=2d18088551) | Mar 15, 2023 |
| Dell          | Latitude E6230              | [49a9844be8](https://linux-hardware.org/?probe=49a9844be8) | Mar 15, 2023 |
| Dell          | Latitude E6440              | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Unknown       | Unknown                     | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| HP            | ProBook 640 G1              | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | Aspire E1-572G              | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | Inspiron 15 3511            | [f4349052b8](https://linux-hardware.org/?probe=f4349052b8) | Jan 06, 2023 |
| Dell          | XPS 13 9370                 | [1f72002986](https://linux-hardware.org/?probe=1f72002986) | Dec 29, 2022 |
| HP            | Laptop 14-df0xxx            | [1d9edd6c97](https://linux-hardware.org/?probe=1d9edd6c97) | Dec 25, 2022 |
| HP            | 250 G8 Notebook PC          | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
| Dell          | Latitude E6530              | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Lenovo        | G50-30 80G0                 | [be4f638bc7](https://linux-hardware.org/?probe=be4f638bc7) | Nov 21, 2022 |
| HP            | Laptop 15-bs2xx             | [7254534946](https://linux-hardware.org/?probe=7254534946) | Oct 20, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Lenovo        | ThinkPad T440p              | [270cf10219](https://linux-hardware.org/?probe=270cf10219) | Sep 25, 2022 |
| Lenovo        | ThinkPad T440p              | [bf397424f3](https://linux-hardware.org/?probe=bf397424f3) | Sep 18, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
| Sony          | VPCEE23FX                   | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Toshiba       | Satellite Pro A50-C         | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| Lenovo        | V310-14ISK 80SX             | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Dell          | Latitude 7280               | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| MSI           | Modern 15 A5M               | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Dell          | Latitude E7240              | [045554b70c](https://linux-hardware.org/?probe=045554b70c) | Jul 08, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [001634b95b](https://linux-hardware.org/?probe=001634b95b) | Jun 17, 2022 |
| Dell          | Latitude E6430              | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| Acer          | Aspire E5-553G              | [2d4c950e2f](https://linux-hardware.org/?probe=2d4c950e2f) | May 25, 2022 |
| Acer          | Aspire E5-553G              | [73139cdb17](https://linux-hardware.org/?probe=73139cdb17) | May 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| HP            | Notebook                    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Lenovo        | ThinkPad T470s 20HGS00P0... | [2c9878c68b](https://linux-hardware.org/?probe=2c9878c68b) | Apr 13, 2022 |
| Dell          | Latitude E5540              | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| ASUSTek       | K55VJ                       | [562262b9eb](https://linux-hardware.org/?probe=562262b9eb) | Jan 22, 2022 |
| ASUSTek       | X555LJ                      | [9fbdf4dfc2](https://linux-hardware.org/?probe=9fbdf4dfc2) | Jan 17, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Notebook      | W230ST                      | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [899cb98778](https://linux-hardware.org/?probe=899cb98778) | Dec 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK U7510              | [d43a6a6bb8](https://linux-hardware.org/?probe=d43a6a6bb8) | Nov 29, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7f1b3371a9](https://linux-hardware.org/?probe=7f1b3371a9) | Oct 03, 2021 |
| Toshiba       | Satellite M40X              | [61fea93e97](https://linux-hardware.org/?probe=61fea93e97) | Oct 01, 2021 |
| Acer          | Aspire 5250                 | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | [04747e3df4](https://linux-hardware.org/?probe=04747e3df4) | Sep 19, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | [134b90f474](https://linux-hardware.org/?probe=134b90f474) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | [04256a6e0a](https://linux-hardware.org/?probe=04256a6e0a) | Aug 25, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | [dffbcc492c](https://linux-hardware.org/?probe=dffbcc492c) | Aug 25, 2021 |
| ASUSTek       | K52F                        | [643e3cc4b3](https://linux-hardware.org/?probe=643e3cc4b3) | Aug 13, 2021 |
| MSI           | MS-1688                     | [0ae772d66b](https://linux-hardware.org/?probe=0ae772d66b) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| Acer          | Extensa 215-51K             | [1c49c2f4d0](https://linux-hardware.org/?probe=1c49c2f4d0) | Jul 26, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| ASUSTek       | K55VJ                       | [6fa86f9d25](https://linux-hardware.org/?probe=6fa86f9d25) | Apr 27, 2021 |
| ASUSTek       | K55VJ                       | [aef1b6c71f](https://linux-hardware.org/?probe=aef1b6c71f) | Apr 17, 2021 |
| HP            | ProBook 6475b               | [74b0fa77b5](https://linux-hardware.org/?probe=74b0fa77b5) | Apr 14, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Teclast       | F6 Plus                     | [26ac25681a](https://linux-hardware.org/?probe=26ac25681a) | Jan 08, 2021 |
| Dell          | Precision 7530              | [8e0ee186a3](https://linux-hardware.org/?probe=8e0ee186a3) | Dec 04, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Nokia         | N900                        | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| Dell          | Precision 7530              | [e6c6dd2734](https://linux-hardware.org/?probe=e6c6dd2734) | Sep 26, 2020 |
| Dell          | Precision 7530              | [81e9306141](https://linux-hardware.org/?probe=81e9306141) | Sep 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3d241c321f](https://linux-hardware.org/?probe=3d241c321f) | Sep 20, 2020 |
| ASUSTek       | K52F                        | [cef5147eeb](https://linux-hardware.org/?probe=cef5147eeb) | Aug 30, 2020 |
| Acer          | Aspire 5732Z                | [c4cb936b69](https://linux-hardware.org/?probe=c4cb936b69) | Aug 30, 2020 |
| Toshiba       | Satellite L655              | [6251a9111f](https://linux-hardware.org/?probe=6251a9111f) | Aug 30, 2020 |
| HP            | Pavilion 11 x360 PC         | [0c85729a27](https://linux-hardware.org/?probe=0c85729a27) | Aug 30, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Lenovo        | IdeaPad Z370                | [51e3108708](https://linux-hardware.org/?probe=51e3108708) | Jun 28, 2020 |
| Dell          | Latitude 5501               | [94ec8d2a1d](https://linux-hardware.org/?probe=94ec8d2a1d) | Jun 28, 2020 |
| Lenovo        | IdeaPad Z370                | [76c985ed75](https://linux-hardware.org/?probe=76c985ed75) | Jun 27, 2020 |
| Dell          | Latitude E7250              | [c2ca61e7bf](https://linux-hardware.org/?probe=c2ca61e7bf) | Jun 23, 2020 |
| Dell          | Inspiron 1564               | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| MTC           | Montara-GML                 | [227bf1ba1d](https://linux-hardware.org/?probe=227bf1ba1d) | Dec 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Devuan 5                | 49        | 35.25%  |
| Devuan 4                | 49        | 35.25%  |
| Devuan 3                | 14        | 10.07%  |
| Devuan 6                | 10        | 7.19%   |
| Devuan Testing/unstable | 8         | 5.76%   |
| Devuan                  | 6         | 4.32%   |
| Devuan 9                | 1         | 0.72%   |
| Devuan 3.0              | 1         | 0.72%   |
| Devuan 2.1              | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Devuan | 129       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 6.1.0-13-amd64        | 8         | 5.48%   |
| 5.10.0-21-amd64       | 8         | 5.48%   |
| 5.10.0-23-amd64       | 6         | 4.11%   |
| 6.1.0-11-amd64        | 5         | 3.42%   |
| 5.10.0-16-amd64       | 5         | 3.42%   |
| 5.10.0-9-amd64        | 4         | 2.74%   |
| 5.10.0-13-amd64       | 4         | 2.74%   |
| 4.19.0-9-amd64        | 4         | 2.74%   |
| 6.6.15-amd64          | 3         | 2.05%   |
| 6.1.0-18-amd64        | 3         | 2.05%   |
| 6.1.0-12-amd64        | 3         | 2.05%   |
| 6.1.0-10-amd64        | 3         | 2.05%   |
| 5.7.0-2-amd64         | 3         | 2.05%   |
| 5.10.0-8-amd64        | 3         | 2.05%   |
| 5.10.0-18-amd64       | 3         | 2.05%   |
| 5.10.0-10-amd64       | 3         | 2.05%   |
| 6.9.7-amd64           | 2         | 1.37%   |
| 6.10.6-amd64          | 2         | 1.37%   |
| 6.1.0-9-amd64         | 2         | 1.37%   |
| 6.1.0-6-amd64         | 2         | 1.37%   |
| 6.1.0-28-amd64        | 2         | 1.37%   |
| 6.1.0-26-amd64        | 2         | 1.37%   |
| 6.1.0-21-amd64        | 2         | 1.37%   |
| 6.1.0-0.deb11.7-amd64 | 2         | 1.37%   |
| 5.18.0-2-amd64        | 2         | 1.37%   |
| 5.10.0-25-amd64       | 2         | 1.37%   |
| 5.10.0-20-amd64       | 2         | 1.37%   |
| 5.10.0-19-amd64       | 2         | 1.37%   |
| 5.10.0-11-amd64       | 2         | 1.37%   |
| 4.19.0-17-amd64       | 2         | 1.37%   |
| 4.19.0-16-amd64       | 2         | 1.37%   |
| 4.19.0-14-amd64       | 2         | 1.37%   |
| 6.9.0-rc2             | 1         | 0.68%   |
| 6.7.5-arkd            | 1         | 0.68%   |
| 6.6.13+bpo-amd64      | 1         | 0.68%   |
| 6.5.0-0.deb12.4-amd64 | 1         | 0.68%   |
| 6.12.6-amd64          | 1         | 0.68%   |
| 6.12.0-rc1            | 1         | 0.68%   |
| 6.10.9-amd64          | 1         | 0.68%   |
| 6.1.9                 | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 48        | 34.04%  |
| 6.1.0   | 40        | 28.37%  |
| 4.19.0  | 13        | 9.22%   |
| 4.9.0   | 5         | 3.55%   |
| 5.7.0   | 4         | 2.84%   |
| 6.6.15  | 3         | 2.13%   |
| 6.0.0   | 3         | 2.13%   |
| 5.18.0  | 3         | 2.13%   |
| 6.9.7   | 2         | 1.42%   |
| 6.10.6  | 2         | 1.42%   |
| 6.9.0   | 1         | 0.71%   |
| 6.7.5   | 1         | 0.71%   |
| 6.6.13  | 1         | 0.71%   |
| 6.5.0   | 1         | 0.71%   |
| 6.12.6  | 1         | 0.71%   |
| 6.12.0  | 1         | 0.71%   |
| 6.10.9  | 1         | 0.71%   |
| 6.1.9   | 1         | 0.71%   |
| 6.1.25  | 1         | 0.71%   |
| 5.9.0   | 1         | 0.71%   |
| 5.8.0   | 1         | 0.71%   |
| 5.6.0   | 1         | 0.71%   |
| 5.19.0  | 1         | 0.71%   |
| 5.15.5  | 1         | 0.71%   |
| 5.15.0  | 1         | 0.71%   |
| 5.14.0  | 1         | 0.71%   |
| 5.1.21  | 1         | 0.71%   |
| 4.4.195 | 1         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 48        | 34.04%  |
| 6.1     | 42        | 29.79%  |
| 4.19    | 13        | 9.22%   |
| 4.9     | 5         | 3.55%   |
| 6.6     | 4         | 2.84%   |
| 5.7     | 4         | 2.84%   |
| 6.9     | 3         | 2.13%   |
| 6.10    | 3         | 2.13%   |
| 6.0     | 3         | 2.13%   |
| 5.18    | 3         | 2.13%   |
| 6.12    | 2         | 1.42%   |
| 5.15    | 2         | 1.42%   |
| 6.7     | 1         | 0.71%   |
| 6.5     | 1         | 0.71%   |
| 5.9     | 1         | 0.71%   |
| 5.8     | 1         | 0.71%   |
| 5.6     | 1         | 0.71%   |
| 5.19    | 1         | 0.71%   |
| 5.14    | 1         | 0.71%   |
| 5.1     | 1         | 0.71%   |
| 4.4     | 1         | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 122       | 93.85%  |
| i686   | 6         | 4.62%   |
| armv7l | 2         | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 62        | 46.27%  |
| MATE            | 19        | 14.18%  |
| KDE5            | 17        | 12.69%  |
| Unknown         | 13        | 9.7%    |
| i3              | 5         | 3.73%   |
| LXDE            | 4         | 2.99%   |
| GNOME           | 4         | 2.99%   |
| Trinity         | 2         | 1.49%   |
| LXQt            | 2         | 1.49%   |
| Enlightenment   | 2         | 1.49%   |
| sway            | 1         | 0.75%   |
| Openbox         | 1         | 0.75%   |
| GNOME Flashback | 1         | 0.75%   |
| Cinnamon        | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 117       | 88.64%  |
| Tty         | 7         | 5.3%    |
| Wayland     | 5         | 3.79%   |
| Unknown     | 2         | 1.52%   |
| Unspecified | 1         | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 42        | 31.34%  |
| LightDM | 41        | 30.6%   |
| Unknown | 31        | 23.13%  |
| SDDM    | 10        | 7.46%   |
| XDM     | 3         | 2.24%   |
| GDM3    | 3         | 2.24%   |
| TDM     | 2         | 1.49%   |
| Ly      | 1         | 0.75%   |
| LXDM    | 1         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 61        | 46.21%  |
| en_GB       | 21        | 15.91%  |
| ru_RU       | 9         | 6.82%   |
| pt_BR       | 6         | 4.55%   |
| es_ES       | 5         | 3.79%   |
| C           | 4         | 3.03%   |
| Unknown     | 4         | 3.03%   |
| de_DE       | 3         | 2.27%   |
| it_IT       | 2         | 1.52%   |
| fr_FR       | 2         | 1.52%   |
| en_ZA       | 2         | 1.52%   |
| de_AT       | 2         | 1.52%   |
| ru_UA       | 1         | 0.76%   |
| ru_RU.utf-8 | 1         | 0.76%   |
| pl_PL       | 1         | 0.76%   |
| fr_BE       | 1         | 0.76%   |
| es_SV       | 1         | 0.76%   |
| es_AR       | 1         | 0.76%   |
| en_US.utf-8 | 1         | 0.76%   |
| en_NZ       | 1         | 0.76%   |
| en_DK       | 1         | 0.76%   |
| en_AU       | 1         | 0.76%   |
| de_CH       | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 68        | 51.91%  |
| EFI  | 63        | 48.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 81.54%  |
| Btrfs   | 8         | 6.15%   |
| Unknown | 6         | 4.62%   |
| Xfs     | 4         | 3.08%   |
| Overlay | 3         | 2.31%   |
| OveXlay | 1         | 0.77%   |
| Ext3    | 1         | 0.77%   |
| Ext2    | 1         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 67        | 50.76%  |
| MBR     | 43        | 32.58%  |
| Unknown | 22        | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 86.15%  |
| Yes       | 18        | 13.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 82.31%  |
| Yes       | 23        | 17.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 38        | 29.46%  |
| Dell                | 23        | 17.83%  |
| Hewlett-Packard     | 14        | 10.85%  |
| Acer                | 9         | 6.98%   |
| ASUSTek Computer    | 8         | 6.2%    |
| Toshiba             | 4         | 3.1%    |
| Samsung Electronics | 3         | 2.33%   |
| MSI                 | 3         | 2.33%   |
| Sony                | 2         | 1.55%   |
| Notebook            | 2         | 1.55%   |
| Nokia               | 2         | 1.55%   |
| Google              | 2         | 1.55%   |
| Fujitsu Siemens     | 2         | 1.55%   |
| Apple               | 2         | 1.55%   |
| TUXEDO              | 1         | 0.78%   |
| Teclast             | 1         | 0.78%   |
| System76            | 1         | 0.78%   |
| Purism              | 1         | 0.78%   |
| PC Specialist       | 1         | 0.78%   |
| MTC                 | 1         | 0.78%   |
| Maibenben           | 1         | 0.78%   |
| MACHENIKE           | 1         | 0.78%   |
| Intel               | 1         | 0.78%   |
| IBM                 | 1         | 0.78%   |
| HUAWEI              | 1         | 0.78%   |
| Fujitsu             | 1         | 0.78%   |
| Framework           | 1         | 0.78%   |
| CCE                 | 1         | 0.78%   |
| Unknown             | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Dell Latitude E6430                                                                      | 3         | 2.33%   |
| Nokia N900                                                                               | 2         | 1.55%   |
| Unknown                                                                                  | 2         | 1.55%   |
| TUXEDO XP1610                                                                            | 1         | 0.78%   |
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.78%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.78%   |
| Toshiba Satellite L655                                                                   | 1         | 0.78%   |
| Toshiba Satellite L300                                                                   | 1         | 0.78%   |
| Teclast F6 Plus                                                                          | 1         | 0.78%   |
| System76 Galago Pro                                                                      | 1         | 0.78%   |
| Sony VPCEE23FX                                                                           | 1         | 0.78%   |
| Sony VGN-FZ140E                                                                          | 1         | 0.78%   |
| Samsung N150P                                                                            | 1         | 0.78%   |
| Samsung 550XDA                                                                           | 1         | 0.78%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.78%   |
| Purism Librem 14                                                                         | 1         | 0.78%   |
| PC Specialist P7xxTM1                                                                    | 1         | 0.78%   |
| Notebook W230ST                                                                          | 1         | 0.78%   |
| Notebook NV4XMB,ME,MZ                                                                    | 1         | 0.78%   |
| MTC Montara-GML                                                                          | 1         | 0.78%   |
| MSI MS-1688                                                                              | 1         | 0.78%   |
| MSI Modern 15 A5M                                                                        | 1         | 0.78%   |
| MSI Bravo 15 A4DDR                                                                       | 1         | 0.78%   |
| Maibenben MaiBook M                                                                      | 1         | 0.78%   |
| MACHENIKE T90-V                                                                          | 1         | 0.78%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 0.78%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 0.78%   |
| Lenovo ThinkPad X390 20Q1A005CD                                                          | 1         | 0.78%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 0.78%   |
| Lenovo ThinkPad X240 20AMS2EC00                                                          | 1         | 0.78%   |
| Lenovo ThinkPad X230 4290EM6                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X230 23259J6                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X230 23252UU                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X200 7459D12                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X200 74585FU                                                             | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB006KPB                                              | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1PB                                                 | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 28        | 21.71%  |
| Dell Latitude         | 13        | 10.08%  |
| Acer Aspire           | 7         | 5.43%   |
| Lenovo IdeaPad        | 6         | 4.65%   |
| Toshiba Satellite     | 4         | 3.1%    |
| Dell Inspiron         | 4         | 3.1%    |
| HP ProBook            | 3         | 2.33%   |
| HP Laptop             | 3         | 2.33%   |
| Dell XPS              | 3         | 2.33%   |
| Nokia N900            | 2         | 1.55%   |
| Unknown               | 2         | 1.55%   |
| TUXEDO XP1610         | 1         | 0.78%   |
| Teclast F6            | 1         | 0.78%   |
| System76 Galago       | 1         | 0.78%   |
| Sony VPCEE23FX        | 1         | 0.78%   |
| Sony VGN-FZ140E       | 1         | 0.78%   |
| Samsung N150P         | 1         | 0.78%   |
| Samsung 550XDA        | 1         | 0.78%   |
| Samsung 355V4C        | 1         | 0.78%   |
| Purism Librem         | 1         | 0.78%   |
| PC Specialist P7xxTM1 | 1         | 0.78%   |
| Notebook W230ST       | 1         | 0.78%   |
| Notebook NV4XMB       | 1         | 0.78%   |
| MTC Montara-GML       | 1         | 0.78%   |
| MSI MS-1688           | 1         | 0.78%   |
| MSI Modern            | 1         | 0.78%   |
| MSI Bravo             | 1         | 0.78%   |
| Maibenben MaiBook     | 1         | 0.78%   |
| MACHENIKE T90-V       | 1         | 0.78%   |
| Lenovo V310-14ISK     | 1         | 0.78%   |
| Lenovo S20-30         | 1         | 0.78%   |
| Lenovo LOQ            | 1         | 0.78%   |
| Lenovo G50-30         | 1         | 0.78%   |
| Intel powered         | 1         | 0.78%   |
| IBM ThinkPad          | 1         | 0.78%   |
| HUAWEI HN-WX9X        | 1         | 0.78%   |
| HP Victus             | 1         | 0.78%   |
| HP Presario           | 1         | 0.78%   |
| HP Pavilion           | 1         | 0.78%   |
| HP Notebook           | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2008    | 13        | 10.08%  |
| 2019    | 12        | 9.3%    |
| 2018    | 12        | 9.3%    |
| 2012    | 10        | 7.75%   |
| 2010    | 10        | 7.75%   |
| 2013    | 9         | 6.98%   |
| 2022    | 8         | 6.2%    |
| 2021    | 7         | 5.43%   |
| 2014    | 7         | 5.43%   |
| 2020    | 6         | 4.65%   |
| 2017    | 6         | 4.65%   |
| 2016    | 5         | 3.88%   |
| 2009    | 5         | 3.88%   |
| 2011    | 4         | 3.1%    |
| 2015    | 3         | 2.33%   |
| 2007    | 3         | 2.33%   |
| 2023    | 2         | 1.55%   |
| 2006    | 2         | 1.55%   |
| 2005    | 2         | 1.55%   |
| Unknown | 2         | 1.55%   |
| 2024    | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 129       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 127       | 97.69%  |
| Enabled  | 3         | 2.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 121       | 93.8%   |
| Yes  | 8         | 6.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 34        | 25.95%  |
| 8.01-16.0   | 26        | 19.85%  |
| 16.01-24.0  | 22        | 16.79%  |
| 3.01-4.0    | 21        | 16.03%  |
| 1.01-2.0    | 8         | 6.11%   |
| 32.01-64.0  | 7         | 5.34%   |
| 2.01-3.0    | 7         | 5.34%   |
| 0.01-0.5    | 3         | 2.29%   |
| 64.01-256.0 | 2         | 1.53%   |
| 24.01-32.0  | 1         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 52        | 36.36%  |
| 4.01-8.0   | 23        | 16.08%  |
| 2.01-3.0   | 20        | 13.99%  |
| 0.51-1.0   | 17        | 11.89%  |
| 3.01-4.0   | 14        | 9.79%   |
| 8.01-16.0  | 9         | 6.29%   |
| 0.01-0.5   | 6         | 4.2%    |
| 32.01-64.0 | 1         | 0.7%    |
| 16.01-24.0 | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 75.38%  |
| 2      | 25        | 19.23%  |
| 3      | 5         | 3.85%   |
| 4      | 1         | 0.77%   |
| 0      | 1         | 0.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 66.15%  |
| Yes       | 44        | 33.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 90.77%  |
| No        | 12        | 9.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 93.8%   |
| No        | 8         | 6.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 66.92%  |
| No        | 43        | 33.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 18        | 13.85%  |
| Russia          | 14        | 10.77%  |
| Germany         | 14        | 10.77%  |
| Brazil          | 10        | 7.69%   |
| Spain           | 6         | 4.62%   |
| Ukraine         | 5         | 3.85%   |
| Poland          | 5         | 3.85%   |
| Portugal        | 4         | 3.08%   |
| Italy           | 4         | 3.08%   |
| France          | 4         | 3.08%   |
| Finland         | 4         | 3.08%   |
| Netherlands     | 3         | 2.31%   |
| Hungary         | 3         | 2.31%   |
| Grenada         | 3         | 2.31%   |
| Georgia         | 3         | 2.31%   |
| UK              | 2         | 1.54%   |
| Switzerland     | 2         | 1.54%   |
| South Africa    | 2         | 1.54%   |
| Norway          | 2         | 1.54%   |
| Mexico          | 2         | 1.54%   |
| Greece          | 2         | 1.54%   |
| Austria         | 2         | 1.54%   |
| Vietnam         | 1         | 0.77%   |
| The Netherlands | 1         | 0.77%   |
| Slovakia        | 1         | 0.77%   |
| Serbia          | 1         | 0.77%   |
| Romania         | 1         | 0.77%   |
| New Zealand     | 1         | 0.77%   |
| Lithuania       | 1         | 0.77%   |
| Japan           | 1         | 0.77%   |
| Israel          | 1         | 0.77%   |
| Indonesia       | 1         | 0.77%   |
| Estonia         | 1         | 0.77%   |
| El Salvador     | 1         | 0.77%   |
| Canada          | 1         | 0.77%   |
| Belarus         | 1         | 0.77%   |
| Bangladesh      | 1         | 0.77%   |
| Argentina       | 1         | 0.77%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Wroclaw        | 4         | 3.05%   |
| Tbilisi        | 3         | 2.29%   |
| Saint George's | 3         | 2.29%   |
| Thessaloniki   | 2         | 1.53%   |
| Palmyra        | 2         | 1.53%   |
| Oslo           | 2         | 1.53%   |
| Nadudvar       | 2         | 1.53%   |
| Munich         | 2         | 1.53%   |
| Milan          | 2         | 1.53%   |
| Madrid         | 2         | 1.53%   |
| Lisbon         | 2         | 1.53%   |
| Kyiv           | 2         | 1.53%   |
| Krasnodar      | 2         | 1.53%   |
| Jyväskylä    | 2         | 1.53%   |
| Ft. Washington | 2         | 1.53%   |
| Bagnolet       | 2         | 1.53%   |
| Amsterdam      | 2         | 1.53%   |
| Ypsilanti      | 1         | 0.76%   |
| Yoshkar-Ola    | 1         | 0.76%   |
| Yakutsk        | 1         | 0.76%   |
| Willich        | 1         | 0.76%   |
| Wildberg       | 1         | 0.76%   |
| Whitby         | 1         | 0.76%   |
| Vilnius        | 1         | 0.76%   |
| Valdemorillo   | 1         | 0.76%   |
| Valbonne       | 1         | 0.76%   |
| Trubchëvsk    | 1         | 0.76%   |
| Tokyo          | 1         | 0.76%   |
| Timonium       | 1         | 0.76%   |
| Tel Aviv       | 1         | 0.76%   |
| Tejgaon        | 1         | 0.76%   |
| Tallinn        | 1         | 0.76%   |
| Syktyvkar      | 1         | 0.76%   |
| Staunton       | 1         | 0.76%   |
| St Petersburg  | 1         | 0.76%   |
| Siena          | 1         | 0.76%   |
| Sao Paulo      | 1         | 0.76%   |
| San Salvador   | 1         | 0.76%   |
| Samara         | 1         | 0.76%   |
| Rottenburg     | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 23        | 33     | 14.47%  |
| WDC                         | 18        | 20     | 11.32%  |
| Seagate                     | 15        | 15     | 9.43%   |
| Unknown                     | 13        | 16     | 8.18%   |
| Toshiba                     | 9         | 9      | 5.66%   |
| Kingston                    | 9         | 10     | 5.66%   |
| Crucial                     | 8         | 10     | 5.03%   |
| SanDisk                     | 7         | 7      | 4.4%    |
| Intel                       | 6         | 6      | 3.77%   |
| SK hynix                    | 5         | 5      | 3.14%   |
| Hitachi                     | 5         | 5      | 3.14%   |
| HGST                        | 4         | 4      | 2.52%   |
| PNY                         | 3         | 3      | 1.89%   |
| Micron Technology           | 3         | 4      | 1.89%   |
| LITEON                      | 3         | 6      | 1.89%   |
| Team                        | 2         | 2      | 1.26%   |
| Patriot                     | 2         | 2      | 1.26%   |
| LITEONIT                    | 2         | 2      | 1.26%   |
| Fujitsu                     | 2         | 2      | 1.26%   |
| China                       | 2         | 2      | 1.26%   |
| Union Memory                | 1         | 2      | 0.63%   |
| UMIS                        | 1         | 1      | 0.63%   |
| Teclast                     | 1         | 1      | 0.63%   |
| SSSTC                       | 1         | 1      | 0.63%   |
| Smart                       | 1         | 1      | 0.63%   |
| SABRENT                     | 1         | 2      | 0.63%   |
| Mushkin                     | 1         | 1      | 0.63%   |
| Lexar                       | 1         | 1      | 0.63%   |
| KIOXIA                      | 1         | 1      | 0.63%   |
| Kingston Technology Company | 1         | 1      | 0.63%   |
| KingFast                    | 1         | 1      | 0.63%   |
| Intenso                     | 1         | 1      | 0.63%   |
| HXY                         | 1         | 1      | 0.63%   |
| Hewlett-Packard             | 1         | 1      | 0.63%   |
| DEMO                        | 1         | 1      | 0.63%   |
| Aura                        | 1         | 1      | 0.63%   |
| Apple                       | 1         | 1      | 0.63%   |
| A-DATA Technology           | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 5         | 3.09%   |
| Toshiba MQ04ABF100 1TB               | 4         | 2.47%   |
| Unknown MMC Card  128GB              | 3         | 1.85%   |
| PNY CS900 240GB SSD                  | 3         | 1.85%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.85%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.85%   |
| Seagate ST9250410AS 250GB            | 2         | 1.23%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 1.23%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.23%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 1.23%   |
| Samsung SSD 870 EVO 1TB              | 2         | 1.23%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.23%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.23%   |
| Samsung MZVLW512HMJP-000L7 512GB     | 2         | 1.23%   |
| Patriot Burst 960GB SSD              | 2         | 1.23%   |
| Intel SSDPEKKF256G8L 256GB           | 2         | 1.23%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.23%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.23%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.62%   |
| WDC WDS500G1B0A-00H9H0 500GB SSD     | 1         | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.62%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.62%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.62%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.62%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.62%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.62%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 0.62%   |
| WDC WD2500BEKT-00A25T0 250GB         | 1         | 0.62%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.62%   |
| WDC WD1600BEVT-75A23T0 160GB         | 1         | 0.62%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.62%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.62%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.62%   |
| WDC PC SN540 SDDPNPF-512G-1032 512GB | 1         | 0.62%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.62%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB | 1         | 0.62%   |
| Unknown SD04G  4GB                   | 1         | 0.62%   |
| Unknown SD  8GB                      | 1         | 0.62%   |
| Unknown NVMe SSD Drive 1TB           | 1         | 0.62%   |
| Unknown MMC32G  32GB                 | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 15     | 33.33%  |
| WDC     | 11        | 11     | 24.44%  |
| Toshiba | 7         | 7      | 15.56%  |
| Hitachi | 5         | 5      | 11.11%  |
| HGST    | 4         | 4      | 8.89%   |
| Fujitsu | 2         | 2      | 4.44%   |
| SABRENT | 1         | 2      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 12     | 21.05%  |
| Kingston            | 8         | 8      | 14.04%  |
| SanDisk             | 5         | 5      | 8.77%   |
| Crucial             | 4         | 6      | 7.02%   |
| WDC                 | 3         | 4      | 5.26%   |
| PNY                 | 3         | 3      | 5.26%   |
| Team                | 2         | 2      | 3.51%   |
| SK hynix            | 2         | 2      | 3.51%   |
| Patriot             | 2         | 2      | 3.51%   |
| LITEONIT            | 2         | 2      | 3.51%   |
| LITEON              | 2         | 5      | 3.51%   |
| China               | 2         | 2      | 3.51%   |
| Union Memory        | 1         | 2      | 1.75%   |
| Teclast             | 1         | 1      | 1.75%   |
| Smart               | 1         | 1      | 1.75%   |
| Mushkin             | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| Intenso             | 1         | 1      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| HXY                 | 1         | 1      | 1.75%   |
| Hewlett-Packard     | 1         | 1      | 1.75%   |
| Apple               | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 51        | 64     | 34%     |
| HDD     | 45        | 46     | 30%     |
| NVMe    | 41        | 56     | 27.33%  |
| MMC     | 12        | 15     | 8%      |
| Unknown | 1         | 2      | 0.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 108    | 61.11%  |
| NVMe | 41        | 56     | 28.47%  |
| MMC  | 12        | 15     | 8.33%   |
| SAS  | 3         | 4      | 2.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 77     | 72.34%  |
| 0.51-1.0   | 21        | 27     | 22.34%  |
| 1.01-2.0   | 4         | 5      | 4.26%   |
| 4.01-10.0  | 1         | 1      | 1.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 25.93%  |
| 251-500        | 32        | 23.7%   |
| 501-1000       | 19        | 14.07%  |
| 51-100         | 14        | 10.37%  |
| 21-50          | 9         | 6.67%   |
| 1001-2000      | 9         | 6.67%   |
| 1-20           | 6         | 4.44%   |
| Unknown        | 6         | 4.44%   |
| More than 3000 | 3         | 2.22%   |
| 2001-3000      | 2         | 1.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 34.31%  |
| 101-250        | 23        | 16.79%  |
| 21-50          | 19        | 13.87%  |
| 51-100         | 18        | 13.14%  |
| 251-500        | 14        | 10.22%  |
| Unknown        | 6         | 4.38%   |
| 501-1000       | 5         | 3.65%   |
| 1001-2000      | 3         | 2.19%   |
| More than 3000 | 1         | 0.73%   |
| 2001-3000      | 1         | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB | 2         | 2      | 14.29%  |
| WDC WD5000LPCX-24C6HT0 500GB    | 1         | 1      | 7.14%   |
| WDC WD5000BPVT-24HXZT3 500GB    | 1         | 1      | 7.14%   |
| WDC WD3200BEVT-22A23T0 320GB    | 1         | 1      | 7.14%   |
| WDC WD1600BEVT-75A23T0 160GB    | 1         | 1      | 7.14%   |
| WDC WD10JPCX-24UE4T0 1TB        | 1         | 1      | 7.14%   |
| Seagate ST9200420ASG 200GB      | 1         | 1      | 7.14%   |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 7.14%   |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 7.14%   |
| Intel SSDSC2KF256H6 SATA 256GB  | 1         | 1      | 7.14%   |
| Hitachi HTS727575A9E364 752GB   | 1         | 1      | 7.14%   |
| Hitachi HTS726060M9AT00 56GB    | 1         | 1      | 7.14%   |
| HGST HTS545050A7E680 500GB      | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 35.71%  |
| Seagate | 5         | 5      | 35.71%  |
| Hitachi | 2         | 2      | 14.29%  |
| Intel   | 1         | 1      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 38.46%  |
| Seagate | 5         | 5      | 38.46%  |
| Hitachi | 2         | 2      | 15.38%  |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 92.86%  |
| SSD  | 1         | 1      | 7.14%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 91        | 126    | 66.42%  |
| Detected | 32        | 43     | 23.36%  |
| Malfunc  | 14        | 14     | 10.22%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 87        | 62.14%  |
| Samsung Electronics            | 12        | 8.57%   |
| AMD                            | 12        | 8.57%   |
| SanDisk                        | 6         | 4.29%   |
| SK hynix                       | 3         | 2.14%   |
| Micron/Crucial Technology      | 3         | 2.14%   |
| Micron Technology              | 3         | 2.14%   |
| Toshiba America Info Systems   | 2         | 1.43%   |
| Kingston Technology Company    | 2         | 1.43%   |
| VIA Technologies               | 1         | 0.71%   |
| Union Memory (Shenzhen)        | 1         | 0.71%   |
| Solidigm                       | 1         | 0.71%   |
| Solid State Storage Technology | 1         | 0.71%   |
| Silicon Motion                 | 1         | 0.71%   |
| Shenzhen Longsys Electronics   | 1         | 0.71%   |
| Nvidia                         | 1         | 0.71%   |
| Lite-On Technology             | 1         | 0.71%   |
| KIOXIA                         | 1         | 0.71%   |
| ADATA Technology               | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 11        | 7.19%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 10        | 6.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 7         | 4.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 7         | 4.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 6         | 3.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 5         | 3.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 5         | 3.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 4         | 2.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 4         | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 4         | 2.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 4         | 2.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 4         | 2.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 4         | 2.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 3         | 1.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                                               | 3         | 1.96%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 3         | 1.96%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                                                   | 3         | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 3         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 3         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 3         | 1.96%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                                                        | 2         | 1.31%   |
| Intel SSD 670p Series [Keystone Harbor]                                                                            | 2         | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 2         | 1.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 2         | 1.31%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                                                      | 2         | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                                                          | 2         | 1.31%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                                             | 2         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 2         | 1.31%   |
| VIA VT6421 IDE/SATA Controller                                                                                     | 1         | 0.65%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                                                    | 1         | 0.65%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                                               | 1         | 0.65%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                                                | 1         | 0.65%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                                                               | 1         | 0.65%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                                                     | 1         | 0.65%   |
| SK hynix PC611 NVMe Solid State Drive                                                                              | 1         | 0.65%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                                                        | 1         | 0.65%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 1         | 0.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                                                      | 1         | 0.65%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 0.65%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                                            | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 82        | 56.55%  |
| NVMe | 41        | 28.28%  |
| IDE  | 15        | 10.34%  |
| RAID | 7         | 4.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 108       | 83.72%  |
| AMD    | 19        | 14.73%  |
| ARM    | 2         | 1.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 4.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 2.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.33%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 3         | 2.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.33%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 1.55%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.55%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 1.55%   |
| Intel 12th Gen Core i5-12500H                 | 2         | 1.55%   |
| ARM Nokia RX-51 board Processor               | 2         | 1.55%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.55%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.55%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.55%   |
| Intel Pentium M processor 1700MHz             | 1         | 0.78%   |
| Intel Pentium M processor 1.60GHz             | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.78%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.78%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.78%   |
| Intel Genuine CPU T1600 @ 1.66GHz             | 1         | 0.78%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 1         | 0.78%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.78%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.78%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.78%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 0.78%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.78%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.78%   |
| Intel Core i7-4610M CPU @ 3.00GHz             | 1         | 0.78%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.78%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.78%   |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 0.78%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 25        | 19.38%  |
| Intel Core i5           | 25        | 19.38%  |
| Intel Core i3           | 14        | 10.85%  |
| Other                   | 13        | 10.08%  |
| Intel Core 2 Duo        | 7         | 5.43%   |
| Intel Celeron           | 7         | 5.43%   |
| AMD Ryzen 5             | 7         | 5.43%   |
| Intel Atom              | 5         | 3.88%   |
| AMD Ryzen 7             | 5         | 3.88%   |
| Intel Pentium           | 3         | 2.33%   |
| Intel Core 2            | 3         | 2.33%   |
| Intel Pentium M         | 2         | 1.55%   |
| Intel Pentium Dual-Core | 2         | 1.55%   |
| Intel Core i9           | 2         | 1.55%   |
| Intel Pentium Dual      | 1         | 0.78%   |
| Intel Genuine           | 1         | 0.78%   |
| Intel Celeron M         | 1         | 0.78%   |
| AMD E2                  | 1         | 0.78%   |
| AMD E                   | 1         | 0.78%   |
| AMD Athlon II           | 1         | 0.78%   |
| AMD A8                  | 1         | 0.78%   |
| AMD A6                  | 1         | 0.78%   |
| AMD A10                 | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 71        | 55.04%  |
| 4      | 28        | 21.71%  |
| 6      | 12        | 9.3%    |
| 1      | 9         | 6.98%   |
| 8      | 4         | 3.1%    |
| 12     | 3         | 2.33%   |
| 10     | 2         | 1.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 129       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 90        | 69.23%  |
| 1      | 40        | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 122       | 94.57%  |
| 32-bit         | 4         | 3.1%    |
| Unknown        | 3         | 2.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 34.81%  |
| 0x306a9    | 8         | 5.93%   |
| 0x406e3    | 6         | 4.44%   |
| 0x806ec    | 5         | 3.7%    |
| 0x306c3    | 5         | 3.7%    |
| 0x20655    | 5         | 3.7%    |
| 0x1067a    | 4         | 2.96%   |
| 0x906ea    | 3         | 2.22%   |
| 0x806ea    | 3         | 2.22%   |
| 0x806c1    | 3         | 2.22%   |
| 0x40651    | 3         | 2.22%   |
| 0x306d4    | 3         | 2.22%   |
| 0x30678    | 3         | 2.22%   |
| 0x206a7    | 3         | 2.22%   |
| 0x906a3    | 2         | 1.48%   |
| 0x706a1    | 2         | 1.48%   |
| 0x6fd      | 2         | 1.48%   |
| 0x6f6      | 2         | 1.48%   |
| 0x406c4    | 2         | 1.48%   |
| 0x20652    | 2         | 1.48%   |
| 0x08608103 | 2         | 1.48%   |
| 0x906ed    | 1         | 0.74%   |
| 0x906a4    | 1         | 0.74%   |
| 0x706a8    | 1         | 0.74%   |
| 0x6d8      | 1         | 0.74%   |
| 0x695      | 1         | 0.74%   |
| 0x30661    | 1         | 0.74%   |
| 0x106ca    | 1         | 0.74%   |
| 0x106c2    | 1         | 0.74%   |
| 0x10676    | 1         | 0.74%   |
| 0x0a50000d | 1         | 0.74%   |
| 0x08600106 | 1         | 0.74%   |
| 0x08600102 | 1         | 0.74%   |
| 0x08108109 | 1         | 0.74%   |
| 0x08101016 | 1         | 0.74%   |
| 0x0810100b | 1         | 0.74%   |
| 0x07030105 | 1         | 0.74%   |
| 0x0600611a | 1         | 0.74%   |
| 0x05000119 | 1         | 0.74%   |
| 0x05000101 | 1         | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 16.15%  |
| IvyBridge        | 12        | 9.23%   |
| Haswell          | 10        | 7.69%   |
| Westmere         | 9         | 6.92%   |
| Core             | 8         | 6.15%   |
| Unknown          | 8         | 6.15%   |
| Penryn           | 7         | 5.38%   |
| Skylake          | 6         | 4.62%   |
| Silvermont       | 6         | 4.62%   |
| TigerLake        | 5         | 3.85%   |
| SandyBridge      | 4         | 3.08%   |
| Broadwell        | 4         | 3.08%   |
| Alderlake Hybrid | 4         | 3.08%   |
| Zen              | 3         | 2.31%   |
| P6               | 3         | 2.31%   |
| Goldmont plus    | 3         | 2.31%   |
| Bonnell          | 3         | 2.31%   |
| Zen 3            | 2         | 1.54%   |
| Zen 2            | 2         | 1.54%   |
| Excavator        | 2         | 1.54%   |
| CometLake        | 2         | 1.54%   |
| Bobcat           | 2         | 1.54%   |
| Zen+             | 1         | 0.77%   |
| Puma             | 1         | 0.77%   |
| Piledriver       | 1         | 0.77%   |
| K10              | 1         | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 99        | 66.89%  |
| AMD    | 28        | 18.92%  |
| Nvidia | 21        | 14.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 7.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 5.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 5.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 3.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 3.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.55%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.55%   |
| Intel HD Graphics 620                                                                    | 4         | 2.55%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 2.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.91%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.91%   |
| AMD Lucienne                                                                             | 3         | 1.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.27%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.27%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 1.27%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 1.27%   |
| AMD Barcelo                                                                              | 2         | 1.27%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.64%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.64%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.64%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.64%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.64%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.64%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.64%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.64%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.64%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 55.38%  |
| 1 x AMD        | 18        | 13.85%  |
| Intel + Nvidia | 16        | 12.31%  |
| 2 x Intel      | 6         | 4.62%   |
| 2 x AMD        | 5         | 3.85%   |
| Other          | 4         | 3.08%   |
| 1 x Nvidia     | 4         | 3.08%   |
| Intel + AMD    | 4         | 3.08%   |
| AMD + Nvidia   | 1         | 0.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 118       | 91.47%  |
| Proprietary | 6         | 4.65%   |
| Unknown     | 5         | 3.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 76.34%  |
| 0.01-0.5   | 10        | 7.63%   |
| 0.51-1.0   | 9         | 6.87%   |
| 1.01-2.0   | 6         | 4.58%   |
| 5.01-6.0   | 3         | 2.29%   |
| 3.01-4.0   | 3         | 2.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 24        | 16.55%  |
| LG Display              | 22        | 15.17%  |
| BOE                     | 21        | 14.48%  |
| Chimei Innolux          | 16        | 11.03%  |
| Samsung Electronics     | 15        | 10.34%  |
| Dell                    | 7         | 4.83%   |
| PANDA                   | 5         | 3.45%   |
| Lenovo                  | 4         | 2.76%   |
| Chi Mei Optoelectronics | 4         | 2.76%   |
| Goldstar                | 3         | 2.07%   |
| Sharp                   | 2         | 1.38%   |
| MStar                   | 2         | 1.38%   |
| InnoLux Display         | 2         | 1.38%   |
| Apple                   | 2         | 1.38%   |
| AOC                     | 2         | 1.38%   |
| Acer                    | 2         | 1.38%   |
| ZLX                     | 1         | 0.69%   |
| Unknown                 | 1         | 0.69%   |
| STD                     | 1         | 0.69%   |
| Lenovo Group Limited    | 1         | 0.69%   |
| InfoVision              | 1         | 0.69%   |
| Iiyama                  | 1         | 0.69%   |
| Hisense                 | 1         | 0.69%   |
| HannStar                | 1         | 0.69%   |
| CSO                     | 1         | 0.69%   |
| CPT                     | 1         | 0.69%   |
| Ancor Communications    | 1         | 0.69%   |
| Unknown                 | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch     | 2         | 1.38%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2         | 1.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.38%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 2         | 1.38%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 2         | 1.38%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 2         | 1.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 1.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 1.38%   |
| ZLX Dummy display ZLX0301 1920x1080 480x270mm 21.7-inch               | 1         | 0.69%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.69%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 0.69%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.69%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.69%   |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 1         | 0.69%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 1         | 0.69%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.69%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 344x194mm 15.5-inch         | 1         | 0.69%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.69%   |
| LG Display LCD Monitor LGDD901 1366x768 344x194mm 15.5-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 54        | 39.13%  |
| 1366x768 (WXGA)    | 49        | 35.51%  |
| 1600x900 (HD+)     | 7         | 5.07%   |
| 3840x2160 (4K)     | 6         | 4.35%   |
| 1280x800 (WXGA)    | 6         | 4.35%   |
| 1920x1200 (WUXGA)  | 4         | 2.9%    |
| 2560x1440 (QHD)    | 2         | 1.45%   |
| 1024x600           | 2         | 1.45%   |
| 5760x1080          | 1         | 0.72%   |
| 3200x1800 (QHD+)   | 1         | 0.72%   |
| 2288x1287          | 1         | 0.72%   |
| 2256x1504          | 1         | 0.72%   |
| 2160x1440          | 1         | 0.72%   |
| 1680x1050 (WSXGA+) | 1         | 0.72%   |
| 1440x900 (WXGA+)   | 1         | 0.72%   |
| Unknown            | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 53        | 37.06%  |
| 14      | 19        | 13.29%  |
| 13      | 16        | 11.19%  |
| 12      | 14        | 9.79%   |
| 24      | 9         | 6.29%   |
| 27      | 6         | 4.2%    |
| 11      | 6         | 4.2%    |
| 17      | 4         | 2.8%    |
| 21      | 3         | 2.1%    |
| 52      | 2         | 1.4%    |
| 31      | 2         | 1.4%    |
| 10      | 2         | 1.4%    |
| 142     | 1         | 0.7%    |
| 54      | 1         | 0.7%    |
| 25      | 1         | 0.7%    |
| 23      | 1         | 0.7%    |
| 20      | 1         | 0.7%    |
| 16      | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 79        | 55.63%  |
| 201-300        | 30        | 21.13%  |
| 501-600        | 16        | 11.27%  |
| 351-400        | 6         | 4.23%   |
| 401-500        | 4         | 2.82%   |
| 1001-1500      | 3         | 2.11%   |
| 601-700        | 2         | 1.41%   |
| More than 2000 | 1         | 0.7%    |
| Unknown        | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 107       | 85.6%   |
| 16/10   | 14        | 11.2%   |
| 3/2     | 2         | 1.6%    |
| 1.00    | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 37.06%  |
| 81-90          | 28        | 19.58%  |
| 61-70          | 14        | 9.79%   |
| 201-250        | 9         | 6.29%   |
| 71-80          | 7         | 4.9%    |
| 51-60          | 6         | 4.2%    |
| 301-350        | 6         | 4.2%    |
| 251-300        | 5         | 3.5%    |
| More than 1000 | 4         | 2.8%    |
| 121-130        | 3         | 2.1%    |
| 351-500        | 2         | 1.4%    |
| 41-50          | 2         | 1.4%    |
| 151-200        | 1         | 0.7%    |
| 131-140        | 1         | 0.7%    |
| 111-120        | 1         | 0.7%    |
| Unknown        | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 58        | 41.13%  |
| 101-120       | 39        | 27.66%  |
| 51-100        | 24        | 17.02%  |
| 161-240       | 13        | 9.22%   |
| 1-50          | 4         | 2.84%   |
| More than 240 | 2         | 1.42%   |
| Unknown       | 1         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 109       | 80.15%  |
| 2     | 21        | 15.44%  |
| 3     | 3         | 2.21%   |
| 0     | 3         | 2.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 65        | 30.81%  |
| Realtek Semiconductor      | 59        | 27.96%  |
| Qualcomm Atheros           | 36        | 17.06%  |
| Broadcom                   | 10        | 4.74%   |
| MediaTek                   | 7         | 3.32%   |
| Broadcom Limited           | 5         | 2.37%   |
| Marvell Technology Group   | 4         | 1.9%    |
| Ralink Technology          | 3         | 1.42%   |
| ICS Advent                 | 3         | 1.42%   |
| Sierra Wireless            | 2         | 0.95%   |
| Samsung Electronics        | 2         | 0.95%   |
| Ralink                     | 2         | 0.95%   |
| ZTE WCDMA Technologies MSM | 1         | 0.47%   |
| Xiaomi                     | 1         | 0.47%   |
| VIA Technologies           | 1         | 0.47%   |
| TP-Link                    | 1         | 0.47%   |
| Qualcomm                   | 1         | 0.47%   |
| NetGear                    | 1         | 0.47%   |
| Motorola PCS               | 1         | 0.47%   |
| JMicron Technology         | 1         | 0.47%   |
| Huawei Technologies        | 1         | 0.47%   |
| Edimax Technology          | 1         | 0.47%   |
| DisplayLink                | 1         | 0.47%   |
| Dell                       | 1         | 0.47%   |
| ASIX Electronics           | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 38        | 14.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 4.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 3.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.31%   |
| Intel Wireless 7260                                                     | 5         | 1.92%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.54%   |
| Intel Wireless 8260                                                     | 4         | 1.54%   |
| Intel Wireless 7265                                                     | 4         | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.15%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 1.15%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.15%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 1.15%   |
| ICS Advent USB 10/100 LAN                                               | 3         | 1.15%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 1.15%   |
| Sierra Wireless EM7455                                                  | 2         | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.77%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.77%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.77%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.77%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.77%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 41.73%  |
| Qualcomm Atheros      | 32        | 25.2%   |
| Realtek Semiconductor | 15        | 11.81%  |
| Broadcom              | 7         | 5.51%   |
| MediaTek              | 6         | 4.72%   |
| Broadcom Limited      | 4         | 3.15%   |
| Ralink Technology     | 3         | 2.36%   |
| Sierra Wireless       | 2         | 1.57%   |
| Ralink                | 2         | 1.57%   |
| NetGear               | 1         | 0.79%   |
| Edimax Technology     | 1         | 0.79%   |
| Dell                  | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 7.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 5.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 4.72%   |
| Intel Wireless 7260                                                     | 5         | 3.94%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.15%   |
| Intel Wireless 8260                                                     | 4         | 3.15%   |
| Intel Wireless 7265                                                     | 4         | 3.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 2.36%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.36%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 2.36%   |
| Sierra Wireless EM7455                                                  | 2         | 1.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.57%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 1.57%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 1.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.57%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.57%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.57%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.79%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.79%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.79%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.79%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.79%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.79%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 55        | 43.31%  |
| Intel                    | 42        | 33.07%  |
| Qualcomm Atheros         | 6         | 4.72%   |
| Marvell Technology Group | 4         | 3.15%   |
| Broadcom                 | 4         | 3.15%   |
| ICS Advent               | 3         | 2.36%   |
| Samsung Electronics      | 2         | 1.57%   |
| Xiaomi                   | 1         | 0.79%   |
| VIA Technologies         | 1         | 0.79%   |
| TP-Link                  | 1         | 0.79%   |
| Qualcomm                 | 1         | 0.79%   |
| Motorola PCS             | 1         | 0.79%   |
| MediaTek                 | 1         | 0.79%   |
| JMicron Technology       | 1         | 0.79%   |
| Huawei Technologies      | 1         | 0.79%   |
| DisplayLink              | 1         | 0.79%   |
| Broadcom Limited         | 1         | 0.79%   |
| ASIX Electronics         | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 29.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 10.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 9.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 2.33%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.33%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 2.33%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 2.33%   |
| ICS Advent USB 10/100 LAN                                              | 3         | 2.33%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 1.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.55%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.55%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.55%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.78%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.78%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.78%   |
| Qualcomm POCO F3                                                       | 1         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.78%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.78%   |
| Motorola PCS moto g84 5G                                               | 1         | 0.78%   |
| MediaTek TANK2                                                         | 1         | 0.78%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.78%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 1         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.78%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.78%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.78%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.78%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.78%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 49.79%  |
| Ethernet | 118       | 48.56%  |
| Modem    | 4         | 1.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 90        | 67.16%  |
| Ethernet | 43        | 32.09%  |
| Modem    | 1         | 0.75%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 105       | 81.4%   |
| 1     | 19        | 14.73%  |
| 0     | 5         | 3.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 82.95%  |
| Yes  | 22        | 17.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 36.26%  |
| Qualcomm Atheros Communications | 10        | 10.99%  |
| Broadcom                        | 9         | 9.89%   |
| Realtek Semiconductor           | 8         | 8.79%   |
| Lite-On Technology              | 5         | 5.49%   |
| Dell                            | 5         | 5.49%   |
| Foxconn / Hon Hai               | 4         | 4.4%    |
| Cambridge Silicon Radio         | 4         | 4.4%    |
| IMC Networks                    | 3         | 3.3%    |
| Foxconn International           | 2         | 2.2%    |
| TP-Link                         | 1         | 1.1%    |
| Realtek                         | 1         | 1.1%    |
| Ralink                          | 1         | 1.1%    |
| MediaTek                        | 1         | 1.1%    |
| Hewlett-Packard                 | 1         | 1.1%    |
| Fujitsu                         | 1         | 1.1%    |
| ASUSTek Computer                | 1         | 1.1%    |
| Apple                           | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 15.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 9.89%   |
| Realtek Bluetooth Radio                             | 8         | 8.79%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 8.79%   |
| Intel AX200 Bluetooth                               | 5         | 5.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 5.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 4.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 4.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.2%    |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 2.2%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 2.2%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 2.2%    |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 1.1%    |
| Realtek Bluetooth Radio                             | 1         | 1.1%    |
| Ralink RT3290 Bluetooth                             | 1         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.1%    |
| MediaTek Wireless_Device                            | 1         | 1.1%    |
| Lite-On Bluetooth Device                            | 1         | 1.1%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.1%    |
| Intel AX211 Bluetooth                               | 1         | 1.1%    |
| IMC Networks Wireless_Device                        | 1         | 1.1%    |
| IMC Networks BCM20702A0                             | 1         | 1.1%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.1%    |
| Fujitsu Bluetooth Device                            | 1         | 1.1%    |
| Foxconn / Hon Hai BT                                | 1         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.1%    |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 1.1%    |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.1%    |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 1.1%    |
| Apple Bluetooth USB Host Controller                 | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 105       | 68.63%  |
| AMD                   | 24        | 15.69%  |
| Nvidia                | 14        | 9.15%   |
| C-Media Electronics   | 4         | 2.61%   |
| Samsung Electronics   | 1         | 0.65%   |
| Realtek Semiconductor | 1         | 0.65%   |
| JMTek                 | 1         | 0.65%   |
| GYROCOM C&C           | 1         | 0.65%   |
| GN Netcom             | 1         | 0.65%   |
| Blue Microphones      | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 7.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 6.45%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 12        | 6.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 4.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 4.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 2.69%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 2.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.15%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.61%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 1.08%   |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 1.08%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.08%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.08%   |
| Samsung Electronics USB C Earphones                                        | 1         | 0.54%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 28.35%  |
| SK hynix            | 23        | 18.11%  |
| Kingston            | 13        | 10.24%  |
| Unknown             | 11        | 8.66%   |
| Micron Technology   | 9         | 7.09%   |
| Crucial             | 8         | 6.3%    |
| A-DATA Technology   | 7         | 5.51%   |
| G.Skill             | 3         | 2.36%   |
| Nanya Technology    | 2         | 1.57%   |
| Corsair             | 2         | 1.57%   |
| Unknown             | 2         | 1.57%   |
| Unknown (F785)      | 1         | 0.79%   |
| Unknown (ABCD)      | 1         | 0.79%   |
| Transcend           | 1         | 0.79%   |
| Smart               | 1         | 0.79%   |
| Ramaxel Technology  | 1         | 0.79%   |
| Goldkey             | 1         | 0.79%   |
| Elpida              | 1         | 0.79%   |
| Apacer              | 1         | 0.79%   |
| A Force             | 1         | 0.79%   |
| 4ea5                | 1         | 0.79%   |
| 48spaces            | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 2.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 2.11%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.11%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.41%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 1.41%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.41%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.41%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.41%   |
| Unknown                                                          | 2         | 1.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.7%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.7%    |
| Unknown (F785) RAM Module 16GB SODIMM DDR4 3200MT/s              | 1         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 0.7%    |
| Transcend RAM JM667QSU-2G 2048MB SODIMM DDR2 667MT/s             | 1         | 0.7%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.7%    |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.7%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1066MT/s                     | 1         | 0.7%    |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.7%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.7%    |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 1         | 0.7%    |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 44        | 40.37%  |
| DDR3    | 44        | 40.37%  |
| DDR2    | 7         | 6.42%   |
| SDRAM   | 3         | 2.75%   |
| LPDDR3  | 3         | 2.75%   |
| DDR     | 3         | 2.75%   |
| LPDDR4  | 2         | 1.83%   |
| LPDDR5  | 1         | 0.92%   |
| DDR5    | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 94.34%  |
| Row Of Chips | 4         | 3.77%   |
| Chip         | 1         | 0.94%   |
| Unknown      | 1         | 0.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 42        | 33.33%  |
| 4096  | 32        | 25.4%   |
| 16384 | 21        | 16.67%  |
| 2048  | 21        | 16.67%  |
| 1024  | 6         | 4.76%   |
| 32768 | 3         | 2.38%   |
| 512   | 1         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 26.27%  |
| 2667    | 21        | 17.8%   |
| 3200    | 17        | 14.41%  |
| 2400    | 9         | 7.63%   |
| Unknown | 6         | 5.08%   |
| 1334    | 4         | 3.39%   |
| 1067    | 4         | 3.39%   |
| 800     | 4         | 3.39%   |
| 667     | 4         | 3.39%   |
| 3266    | 3         | 2.54%   |
| 1333    | 3         | 2.54%   |
| 4199    | 2         | 1.69%   |
| 2133    | 2         | 1.69%   |
| 1066    | 2         | 1.69%   |
| 6400    | 1         | 0.85%   |
| 5600    | 1         | 0.85%   |
| 2933    | 1         | 0.85%   |
| 1867    | 1         | 0.85%   |
| 1200    | 1         | 0.85%   |
| 975     | 1         | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 33.33%  |
| Microdia                               | 9         | 8.82%   |
| Bison Electronics                      | 9         | 8.82%   |
| Sunplus Innovation Technology          | 6         | 5.88%   |
| Acer                                   | 6         | 5.88%   |
| Realtek Semiconductor                  | 5         | 4.9%    |
| Quanta                                 | 5         | 4.9%    |
| IMC Networks                           | 5         | 4.9%    |
| Suyin                                  | 4         | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.92%   |
| Luxvisions Innotech Limited            | 3         | 2.94%   |
| Lite-On Technology                     | 2         | 1.96%   |
| Z-Star Microelectronics                | 1         | 0.98%   |
| Silicon Motion                         | 1         | 0.98%   |
| Samsung Electronics                    | 1         | 0.98%   |
| OmniVision Technologies                | 1         | 0.98%   |
| Mustek Systems                         | 1         | 0.98%   |
| Logitech                               | 1         | 0.98%   |
| LG Electronics                         | 1         | 0.98%   |
| Lenovo                                 | 1         | 0.98%   |
| kingcome                               | 1         | 0.98%   |
| Genesys Logic                          | 1         | 0.98%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 11        | 10.78%  |
| Chicony HD WebCam                                           | 4         | 3.92%   |
| Acer BisonCam,NB Pro                                        | 3         | 2.94%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.96%   |
| Microdia Integrated Webcam                                  | 2         | 1.96%   |
| IMC Networks Integrated Camera                              | 2         | 1.96%   |
| Chicony HP TrueVision HD Camera                             | 2         | 1.96%   |
| Chicony EasyCamera                                          | 2         | 1.96%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.96%   |
| Bison Integrated RGB Camera                                 | 2         | 1.96%   |
| Bison BisonCam, NB Pro                                      | 2         | 1.96%   |
| Z-Star Webcam                                               | 1         | 0.98%   |
| Suyin Lenovo EasyCamera Integrated Webcam                   | 1         | 0.98%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 0.98%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.98%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.98%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.98%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.98%   |
| Sunplus DICOTA 4K                                           | 1         | 0.98%   |
| Sunplus Dell Integrated Webcam                              | 1         | 0.98%   |
| Sunplus Asus Webcam                                         | 1         | 0.98%   |
| Sunplus 720p HD Camera                                      | 1         | 0.98%   |
| Silicon Motion HP Webcam-101                                | 1         | 0.98%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.98%   |
| Realtek Lenovo EasyCamera                                   | 1         | 0.98%   |
| Realtek Laptop Camera                                       | 1         | 0.98%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.98%   |
| Quanta USB webcam                                           | 1         | 0.98%   |
| Quanta Sony Visual Communication Camera                     | 1         | 0.98%   |
| Quanta HP HD Camera                                         | 1         | 0.98%   |
| Quanta HD Webcam                                            | 1         | 0.98%   |
| Quanta HD User Facing                                       | 1         | 0.98%   |
| OmniVision OV2640 Webcam                                    | 1         | 0.98%   |
| Mustek Systems USB 2.0 PC Camera                            | 1         | 0.98%   |
| Microdia Webcam Vitade AF                                   | 1         | 0.98%   |
| Microdia WebCam SC-13HDL12639P                              | 1         | 0.98%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 0.98%   |
| Microdia Laptop_Integrated_Webcam_E4HD                      | 1         | 0.98%   |
| Microdia Integrated_Webcam_HD                               | 1         | 0.98%   |
| Microdia Dell Integrated HD Webcam                          | 1         | 0.98%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 38.46%  |
| Validity Sensors           | 3         | 23.08%  |
| STMicroelectronics         | 2         | 15.38%  |
| Upek                       | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| AuthenTec                  | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 15.38%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| Synaptics WBDI Device                                  | 1         | 7.69%   |
| Synaptics TouchPad                                     | 1         | 7.69%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.69%   |
| AuthenTec AES2810                                      | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 52.38%  |
| Alcor Micro | 7         | 33.33%  |
| Upek        | 2         | 9.52%   |
| Lenovo      | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 19.05%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 9.52%   |
| Broadcom 5880                                                                | 2         | 9.52%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.76%   |
| Broadcom 58200                                                               | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 83        | 61.94%  |
| 1     | 34        | 25.37%  |
| 2     | 13        | 9.7%    |
| 3     | 2         | 1.49%   |
| 5     | 1         | 0.75%   |
| 4     | 1         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chipcard                 | 16        | 25.4%   |
| Graphics card            | 14        | 22.22%  |
| Fingerprint reader       | 13        | 20.63%  |
| Net/wireless             | 5         | 7.94%   |
| Camera                   | 5         | 7.94%   |
| Bluetooth                | 3         | 4.76%   |
| Multimedia controller    | 2         | 3.17%   |
| Communication controller | 2         | 3.17%   |
| Storage                  | 1         | 1.59%   |
| Sound                    | 1         | 1.59%   |
| Card reader              | 1         | 1.59%   |

