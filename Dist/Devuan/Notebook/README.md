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

Total: 191

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga Slim 7 15ILL9 83HM     | [0e189c5b46](https://linux-hardware.org/?probe=0e189c5b46) | Dec 14, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [ed4340cd1a](https://linux-hardware.org/?probe=ed4340cd1a) | Dec 05, 2025 |
| IBM           | ThinkPad X40 23718EU        | [b7760d34a4](https://linux-hardware.org/?probe=b7760d34a4) | Oct 24, 2025 |
| Dell          | Latitude 7275               | [7f37b4132b](https://linux-hardware.org/?probe=7f37b4132b) | Oct 21, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [b31b577b75](https://linux-hardware.org/?probe=b31b577b75) | Oct 13, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [32b0946cac](https://linux-hardware.org/?probe=32b0946cac) | Sep 25, 2025 |
| Intel         | H81U                        | [3453a83029](https://linux-hardware.org/?probe=3453a83029) | Sep 17, 2025 |
| Lenovo        | G710 20252                  | [4d96941694](https://linux-hardware.org/?probe=4d96941694) | Sep 09, 2025 |
| Lenovo        | ThinkPad T430 2347GR2       | [0327b16100](https://linux-hardware.org/?probe=0327b16100) | Sep 01, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [059fb4f7bb](https://linux-hardware.org/?probe=059fb4f7bb) | Aug 31, 2025 |
| Dell          | MXC051                      | [1aa114333f](https://linux-hardware.org/?probe=1aa114333f) | Aug 31, 2025 |
| HP            | 250 G8 Notebook PC          | [e8330e8df4](https://linux-hardware.org/?probe=e8330e8df4) | Aug 26, 2025 |
| Lenovo        | LOQ 15IAX9 83GS             | [da9ad1e52b](https://linux-hardware.org/?probe=da9ad1e52b) | Aug 26, 2025 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [60fc6d703e](https://linux-hardware.org/?probe=60fc6d703e) | Aug 16, 2025 |
| VIT           | M2420                       | [8b9406ab14](https://linux-hardware.org/?probe=8b9406ab14) | Aug 15, 2025 |
| Lenovo        | IdeaPad Y550 20017          | [9619058707](https://linux-hardware.org/?probe=9619058707) | Jul 15, 2025 |
| Acer          | Aspire A515-54              | [26cea0bfd2](https://linux-hardware.org/?probe=26cea0bfd2) | Jul 10, 2025 |
| ASUSTek       | X555LA                      | [132f009cef](https://linux-hardware.org/?probe=132f009cef) | Jun 25, 2025 |
| HP            | Pavilion dv2700             | [54c8c3e9ce](https://linux-hardware.org/?probe=54c8c3e9ce) | Jun 22, 2025 |
| Fujitsu Si... | AMILO PRO V3515             | [1374490476](https://linux-hardware.org/?probe=1374490476) | Jun 19, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [7ce7e3285a](https://linux-hardware.org/?probe=7ce7e3285a) | Jun 08, 2025 |
| MSI           | Modern 15 A5M               | [9ce8e5a8ff](https://linux-hardware.org/?probe=9ce8e5a8ff) | May 18, 2025 |
| AVERATEC      | E1200                       | [472c4b84ed](https://linux-hardware.org/?probe=472c4b84ed) | May 16, 2025 |
| ASUSTek       | K50IE                       | [9f21e8de10](https://linux-hardware.org/?probe=9f21e8de10) | May 08, 2025 |
| Lenovo        | IdeaPad Y550 20017          | [ab679a51db](https://linux-hardware.org/?probe=ab679a51db) | Apr 16, 2025 |
| ASUSTek       | K50IE                       | [fe847bba58](https://linux-hardware.org/?probe=fe847bba58) | Mar 19, 2025 |
| ASUSTek       | X555LJ                      | [281c68dcbc](https://linux-hardware.org/?probe=281c68dcbc) | Mar 11, 2025 |
| Lenovo        | ThinkPad X200 7459D12       | [75784aa0ab](https://linux-hardware.org/?probe=75784aa0ab) | Jan 20, 2025 |
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
| Lenovo        | ThinkPad X230 23253A2       | [3fee175541](https://linux-hardware.org/?probe=3fee175541) | Aug 27, 2024 |
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
| Devuan 5                | 64        | 40%     |
| Devuan 4                | 50        | 31.25%  |
| Devuan 6                | 15        | 9.38%   |
| Devuan 3                | 14        | 8.75%   |
| Devuan Testing/unstable | 8         | 5%      |
| Devuan                  | 6         | 3.75%   |
| Devuan 9                | 1         | 0.63%   |
| Devuan 3.0              | 1         | 0.63%   |
| Devuan 2.1              | 1         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Devuan | 149       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 6.1.0-13-amd64        | 8         | 4.62%   |
| 5.10.0-21-amd64       | 8         | 4.62%   |
| 5.10.0-23-amd64       | 6         | 3.47%   |
| 6.1.0-11-amd64        | 5         | 2.89%   |
| 6.1.0-10-amd64        | 5         | 2.89%   |
| 5.10.0-16-amd64       | 5         | 2.89%   |
| 6.1.0-38-amd64        | 4         | 2.31%   |
| 6.1.0-28-amd64        | 4         | 2.31%   |
| 5.10.0-9-amd64        | 4         | 2.31%   |
| 5.10.0-13-amd64       | 4         | 2.31%   |
| 4.19.0-9-amd64        | 4         | 2.31%   |
| 6.6.15-amd64          | 3         | 1.73%   |
| 6.1.0-18-amd64        | 3         | 1.73%   |
| 6.1.0-12-amd64        | 3         | 1.73%   |
| 5.7.0-2-amd64         | 3         | 1.73%   |
| 5.10.0-8-amd64        | 3         | 1.73%   |
| 5.10.0-18-amd64       | 3         | 1.73%   |
| 5.10.0-10-amd64       | 3         | 1.73%   |
| 6.9.7-amd64           | 2         | 1.16%   |
| 6.12.38+deb13-amd64   | 2         | 1.16%   |
| 6.10.6-amd64          | 2         | 1.16%   |
| 6.1.0-9-amd64         | 2         | 1.16%   |
| 6.1.0-6-amd64         | 2         | 1.16%   |
| 6.1.0-26-amd64        | 2         | 1.16%   |
| 6.1.0-21-amd64        | 2         | 1.16%   |
| 6.1.0-0.deb11.7-amd64 | 2         | 1.16%   |
| 5.18.0-2-amd64        | 2         | 1.16%   |
| 5.10.0-25-amd64       | 2         | 1.16%   |
| 5.10.0-20-amd64       | 2         | 1.16%   |
| 5.10.0-19-amd64       | 2         | 1.16%   |
| 5.10.0-11-amd64       | 2         | 1.16%   |
| 4.19.0-17-amd64       | 2         | 1.16%   |
| 4.19.0-16-amd64       | 2         | 1.16%   |
| 4.19.0-14-amd64       | 2         | 1.16%   |
| 6.9.0-rc2             | 1         | 0.58%   |
| 6.7.5-arkd            | 1         | 0.58%   |
| 6.6.13+bpo-amd64      | 1         | 0.58%   |
| 6.5.0-0.deb12.4-amd64 | 1         | 0.58%   |
| 6.17.2                | 1         | 0.58%   |
| 6.16.8                | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 56        | 33.73%  |
| 5.10.0  | 49        | 29.52%  |
| 4.19.0  | 13        | 7.83%   |
| 4.9.0   | 5         | 3.01%   |
| 5.7.0   | 4         | 2.41%   |
| 6.6.15  | 3         | 1.81%   |
| 6.0.0   | 3         | 1.81%   |
| 5.18.0  | 3         | 1.81%   |
| 6.9.7   | 2         | 1.2%    |
| 6.12.38 | 2         | 1.2%    |
| 6.10.6  | 2         | 1.2%    |
| 6.9.0   | 1         | 0.6%    |
| 6.7.5   | 1         | 0.6%    |
| 6.6.13  | 1         | 0.6%    |
| 6.5.0   | 1         | 0.6%    |
| 6.17.2  | 1         | 0.6%    |
| 6.16.8  | 1         | 0.6%    |
| 6.12.6  | 1         | 0.6%    |
| 6.12.48 | 1         | 0.6%    |
| 6.12.30 | 1         | 0.6%    |
| 6.12.22 | 1         | 0.6%    |
| 6.12.12 | 1         | 0.6%    |
| 6.12.0  | 1         | 0.6%    |
| 6.10.9  | 1         | 0.6%    |
| 6.1.9   | 1         | 0.6%    |
| 6.1.25  | 1         | 0.6%    |
| 5.9.0   | 1         | 0.6%    |
| 5.8.0   | 1         | 0.6%    |
| 5.6.0   | 1         | 0.6%    |
| 5.19.0  | 1         | 0.6%    |
| 5.15.5  | 1         | 0.6%    |
| 5.15.0  | 1         | 0.6%    |
| 5.14.0  | 1         | 0.6%    |
| 5.1.21  | 1         | 0.6%    |
| 4.4.195 | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 58        | 35.15%  |
| 5.10    | 49        | 29.7%   |
| 4.19    | 13        | 7.88%   |
| 6.12    | 7         | 4.24%   |
| 4.9     | 5         | 3.03%   |
| 6.6     | 4         | 2.42%   |
| 5.7     | 4         | 2.42%   |
| 6.9     | 3         | 1.82%   |
| 6.10    | 3         | 1.82%   |
| 6.0     | 3         | 1.82%   |
| 5.18    | 3         | 1.82%   |
| 5.15    | 2         | 1.21%   |
| 6.7     | 1         | 0.61%   |
| 6.5     | 1         | 0.61%   |
| 6.17    | 1         | 0.61%   |
| 6.16    | 1         | 0.61%   |
| 5.9     | 1         | 0.61%   |
| 5.8     | 1         | 0.61%   |
| 5.6     | 1         | 0.61%   |
| 5.19    | 1         | 0.61%   |
| 5.14    | 1         | 0.61%   |
| 5.1     | 1         | 0.61%   |
| 4.4     | 1         | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 138       | 92%     |
| i686   | 10        | 6.67%   |
| armv7l | 2         | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 70        | 45.16%  |
| MATE            | 19        | 12.26%  |
| KDE5            | 19        | 12.26%  |
| Unknown         | 16        | 10.32%  |
| i3              | 7         | 4.52%   |
| LXDE            | 4         | 2.58%   |
| GNOME           | 4         | 2.58%   |
| X-Cinnamon      | 2         | 1.29%   |
| Trinity         | 2         | 1.29%   |
| Openbox         | 2         | 1.29%   |
| LXQt            | 2         | 1.29%   |
| Enlightenment   | 2         | 1.29%   |
| Cinnamon        | 2         | 1.29%   |
| sway            | 1         | 0.65%   |
| KDE6            | 1         | 0.65%   |
| GNOME Flashback | 1         | 0.65%   |
| awesome         | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 134       | 87.58%  |
| Tty         | 9         | 5.88%   |
| Wayland     | 6         | 3.92%   |
| Unknown     | 3         | 1.96%   |
| Unspecified | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 50        | 32.47%  |
| LightDM | 47        | 30.52%  |
| Unknown | 35        | 22.73%  |
| SDDM    | 11        | 7.14%   |
| GDM3    | 4         | 2.6%    |
| XDM     | 3         | 1.95%   |
| TDM     | 2         | 1.3%    |
| Ly      | 1         | 0.65%   |
| LXDM    | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 68        | 44.74%  |
| en_GB       | 21        | 13.82%  |
| ru_RU       | 11        | 7.24%   |
| pt_BR       | 6         | 3.95%   |
| es_ES       | 6         | 3.95%   |
| C           | 5         | 3.29%   |
| Unknown     | 5         | 3.29%   |
| fr_FR       | 4         | 2.63%   |
| pl_PL       | 3         | 1.97%   |
| de_DE       | 3         | 1.97%   |
| it_IT       | 2         | 1.32%   |
| fr_BE       | 2         | 1.32%   |
| en_ZA       | 2         | 1.32%   |
| en_DK       | 2         | 1.32%   |
| de_AT       | 2         | 1.32%   |
| ru_UA       | 1         | 0.66%   |
| ru_RU.utf-8 | 1         | 0.66%   |
| ko_KR       | 1         | 0.66%   |
| es_SV       | 1         | 0.66%   |
| es_CL       | 1         | 0.66%   |
| es_AR       | 1         | 0.66%   |
| en_US.utf-8 | 1         | 0.66%   |
| en_NZ       | 1         | 0.66%   |
| en_AU       | 1         | 0.66%   |
| de_CH       | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 77        | 50.99%  |
| EFI  | 74        | 49.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 123       | 82%     |
| Btrfs   | 8         | 5.33%   |
| Xfs     | 6         | 4%      |
| Unknown | 6         | 4%      |
| Overlay | 4         | 2.67%   |
| OveXlay | 1         | 0.67%   |
| Ext3    | 1         | 0.67%   |
| Ext2    | 1         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 78        | 51.32%  |
| MBR     | 50        | 32.89%  |
| Unknown | 24        | 15.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 128       | 85.33%  |
| Yes       | 22        | 14.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 80%     |
| Yes       | 30        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 45        | 30.2%   |
| Dell                | 25        | 16.78%  |
| Hewlett-Packard     | 15        | 10.07%  |
| ASUSTek Computer    | 12        | 8.05%   |
| Acer                | 10        | 6.71%   |
| Toshiba             | 4         | 2.68%   |
| Samsung Electronics | 3         | 2.01%   |
| MSI                 | 3         | 2.01%   |
| Fujitsu Siemens     | 3         | 2.01%   |
| Sony                | 2         | 1.34%   |
| Notebook            | 2         | 1.34%   |
| Nokia               | 2         | 1.34%   |
| Intel               | 2         | 1.34%   |
| IBM                 | 2         | 1.34%   |
| Google              | 2         | 1.34%   |
| Apple               | 2         | 1.34%   |
| VIT                 | 1         | 0.67%   |
| TUXEDO              | 1         | 0.67%   |
| Teclast             | 1         | 0.67%   |
| System76            | 1         | 0.67%   |
| Purism              | 1         | 0.67%   |
| PC Specialist       | 1         | 0.67%   |
| MTC                 | 1         | 0.67%   |
| Maibenben           | 1         | 0.67%   |
| MACHENIKE           | 1         | 0.67%   |
| HUAWEI              | 1         | 0.67%   |
| Fujitsu             | 1         | 0.67%   |
| Framework           | 1         | 0.67%   |
| CCE                 | 1         | 0.67%   |
| AVERATEC            | 1         | 0.67%   |
| Unknown             | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Dell Latitude E6430                                                                      | 3         | 2.01%   |
| Nokia N900                                                                               | 2         | 1.34%   |
| ASUS X555LJ                                                                              | 2         | 1.34%   |
| Unknown                                                                                  | 2         | 1.34%   |
| VIT M2420                                                                                | 1         | 0.67%   |
| TUXEDO XP1610                                                                            | 1         | 0.67%   |
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.67%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.67%   |
| Toshiba Satellite L655                                                                   | 1         | 0.67%   |
| Toshiba Satellite L300                                                                   | 1         | 0.67%   |
| Teclast F6 Plus                                                                          | 1         | 0.67%   |
| System76 Galago Pro                                                                      | 1         | 0.67%   |
| Sony VPCEE23FX                                                                           | 1         | 0.67%   |
| Sony VGN-FZ140E                                                                          | 1         | 0.67%   |
| Samsung N150P                                                                            | 1         | 0.67%   |
| Samsung 550XDA                                                                           | 1         | 0.67%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.67%   |
| Purism Librem 14                                                                         | 1         | 0.67%   |
| PC Specialist P7xxTM1                                                                    | 1         | 0.67%   |
| Notebook W230ST                                                                          | 1         | 0.67%   |
| Notebook NV4XMB,ME,MZ                                                                    | 1         | 0.67%   |
| MTC Montara-GML                                                                          | 1         | 0.67%   |
| MSI MS-1688                                                                              | 1         | 0.67%   |
| MSI Modern 15 A5M                                                                        | 1         | 0.67%   |
| MSI Bravo 15 A4DDR                                                                       | 1         | 0.67%   |
| Maibenben MaiBook M                                                                      | 1         | 0.67%   |
| MACHENIKE T90-V                                                                          | 1         | 0.67%   |
| Lenovo Yoga Slim 7 15ILL9 83HM                                                           | 1         | 0.67%   |
| Lenovo V310-14ISK 80SX                                                                   | 1         | 0.67%   |
| Lenovo ThinkPad X60 1707YF8                                                              | 1         | 0.67%   |
| Lenovo ThinkPad X390 20Q1A005CD                                                          | 1         | 0.67%   |
| Lenovo ThinkPad X250 20CLS7WY04                                                          | 1         | 0.67%   |
| Lenovo ThinkPad X240 20AMS2EC00                                                          | 1         | 0.67%   |
| Lenovo ThinkPad X230 4290EM6                                                             | 1         | 0.67%   |
| Lenovo ThinkPad X230 2325DE0                                                             | 1         | 0.67%   |
| Lenovo ThinkPad X230 23253A2                                                             | 1         | 0.67%   |
| Lenovo ThinkPad X230 23252UU                                                             | 1         | 0.67%   |
| Lenovo ThinkPad X230 23247S0                                                             | 1         | 0.67%   |
| Lenovo ThinkPad X220 429053G                                                             | 1         | 0.67%   |
| Lenovo ThinkPad X200 7459D12                                                             | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 30        | 20.13%  |
| Dell Latitude         | 14        | 9.4%    |
| Lenovo IdeaPad        | 8         | 5.37%   |
| Acer Aspire           | 8         | 5.37%   |
| Toshiba Satellite     | 4         | 2.68%   |
| Dell Inspiron         | 4         | 2.68%   |
| HP ProBook            | 3         | 2.01%   |
| HP Laptop             | 3         | 2.01%   |
| Dell XPS              | 3         | 2.01%   |
| Nokia N900            | 2         | 1.34%   |
| Lenovo LOQ            | 2         | 1.34%   |
| IBM ThinkPad          | 2         | 1.34%   |
| HP Pavilion           | 2         | 1.34%   |
| Fujitsu Siemens AMILO | 2         | 1.34%   |
| ASUS X555LJ           | 2         | 1.34%   |
| Unknown               | 2         | 1.34%   |
| VIT M2420             | 1         | 0.67%   |
| TUXEDO XP1610         | 1         | 0.67%   |
| Teclast F6            | 1         | 0.67%   |
| System76 Galago       | 1         | 0.67%   |
| Sony VPCEE23FX        | 1         | 0.67%   |
| Sony VGN-FZ140E       | 1         | 0.67%   |
| Samsung N150P         | 1         | 0.67%   |
| Samsung 550XDA        | 1         | 0.67%   |
| Samsung 355V4C        | 1         | 0.67%   |
| Purism Librem         | 1         | 0.67%   |
| PC Specialist P7xxTM1 | 1         | 0.67%   |
| Notebook W230ST       | 1         | 0.67%   |
| Notebook NV4XMB       | 1         | 0.67%   |
| MTC Montara-GML       | 1         | 0.67%   |
| MSI MS-1688           | 1         | 0.67%   |
| MSI Modern            | 1         | 0.67%   |
| MSI Bravo             | 1         | 0.67%   |
| Maibenben MaiBook     | 1         | 0.67%   |
| MACHENIKE T90-V       | 1         | 0.67%   |
| Lenovo Yoga           | 1         | 0.67%   |
| Lenovo V310-14ISK     | 1         | 0.67%   |
| Lenovo S20-30         | 1         | 0.67%   |
| Lenovo G710           | 1         | 0.67%   |
| Lenovo G50-30         | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 15        | 10.07%  |
| 2008    | 13        | 8.72%   |
| 2018    | 12        | 8.05%   |
| 2012    | 11        | 7.38%   |
| 2013    | 10        | 6.71%   |
| 2010    | 10        | 6.71%   |
| 2021    | 9         | 6.04%   |
| 2022    | 8         | 5.37%   |
| 2014    | 8         | 5.37%   |
| 2017    | 7         | 4.7%    |
| 2020    | 6         | 4.03%   |
| 2016    | 6         | 4.03%   |
| 2009    | 6         | 4.03%   |
| 2011    | 5         | 3.36%   |
| 2015    | 4         | 2.68%   |
| 2007    | 4         | 2.68%   |
| 2006    | 4         | 2.68%   |
| 2005    | 4         | 2.68%   |
| 2024    | 2         | 1.34%   |
| 2023    | 2         | 1.34%   |
| Unknown | 2         | 1.34%   |
| 2025    | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 149       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 148       | 98.01%  |
| Enabled  | 3         | 1.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 141       | 94.63%  |
| Yes  | 8         | 5.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 38        | 25.17%  |
| 8.01-16.0   | 29        | 19.21%  |
| 16.01-24.0  | 24        | 15.89%  |
| 3.01-4.0    | 23        | 15.23%  |
| 1.01-2.0    | 13        | 8.61%   |
| 32.01-64.0  | 9         | 5.96%   |
| 2.01-3.0    | 7         | 4.64%   |
| 0.01-0.5    | 3         | 1.99%   |
| 24.01-32.0  | 2         | 1.32%   |
| 64.01-256.0 | 2         | 1.32%   |
| 0.51-1.0    | 1         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 55        | 33.13%  |
| 4.01-8.0   | 27        | 16.27%  |
| 2.01-3.0   | 27        | 16.27%  |
| 0.51-1.0   | 22        | 13.25%  |
| 3.01-4.0   | 14        | 8.43%   |
| 8.01-16.0  | 10        | 6.02%   |
| 0.01-0.5   | 9         | 5.42%   |
| 32.01-64.0 | 1         | 0.6%    |
| 16.01-24.0 | 1         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 111       | 74%     |
| 2      | 30        | 20%     |
| 3      | 6         | 4%      |
| 0      | 2         | 1.33%   |
| 4      | 1         | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 98        | 65.33%  |
| Yes       | 52        | 34.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 90%     |
| No        | 15        | 10%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 92.62%  |
| No        | 11        | 7.38%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 65.56%  |
| No        | 52        | 34.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 21        | 13.91%  |
| Russia          | 17        | 11.26%  |
| Germany         | 14        | 9.27%   |
| Brazil          | 10        | 6.62%   |
| Spain           | 7         | 4.64%   |
| Poland          | 7         | 4.64%   |
| France          | 7         | 4.64%   |
| Ukraine         | 5         | 3.31%   |
| Portugal        | 4         | 2.65%   |
| Italy           | 4         | 2.65%   |
| Finland         | 4         | 2.65%   |
| UK              | 3         | 1.99%   |
| Netherlands     | 3         | 1.99%   |
| Hungary         | 3         | 1.99%   |
| Grenada         | 3         | 1.99%   |
| Georgia         | 3         | 1.99%   |
| Austria         | 3         | 1.99%   |
| Switzerland     | 2         | 1.32%   |
| South Africa    | 2         | 1.32%   |
| Slovakia        | 2         | 1.32%   |
| Norway          | 2         | 1.32%   |
| Mexico          | 2         | 1.32%   |
| Greece          | 2         | 1.32%   |
| Belarus         | 2         | 1.32%   |
| Argentina       | 2         | 1.32%   |
| Vietnam         | 1         | 0.66%   |
| The Netherlands | 1         | 0.66%   |
| Serbia          | 1         | 0.66%   |
| Romania         | 1         | 0.66%   |
| New Zealand     | 1         | 0.66%   |
| Lithuania       | 1         | 0.66%   |
| Japan           | 1         | 0.66%   |
| Israel          | 1         | 0.66%   |
| Indonesia       | 1         | 0.66%   |
| Iceland         | 1         | 0.66%   |
| Estonia         | 1         | 0.66%   |
| El Salvador     | 1         | 0.66%   |
| China           | 1         | 0.66%   |
| Chile           | 1         | 0.66%   |
| Canada          | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Wroclaw             | 4         | 2.58%   |
| Tbilisi             | 3         | 1.94%   |
| Saint George's      | 3         | 1.94%   |
| Issy-les-Moulineaux | 3         | 1.94%   |
| Amsterdam           | 3         | 1.94%   |
| Thessaloniki        | 2         | 1.29%   |
| Palmyra             | 2         | 1.29%   |
| Oslo                | 2         | 1.29%   |
| Nadudvar            | 2         | 1.29%   |
| Munich              | 2         | 1.29%   |
| Moscow              | 2         | 1.29%   |
| Milan               | 2         | 1.29%   |
| Madrid              | 2         | 1.29%   |
| Lisbon              | 2         | 1.29%   |
| Kyiv                | 2         | 1.29%   |
| Krasnodar           | 2         | 1.29%   |
| Jyväskylä         | 2         | 1.29%   |
| Ft. Washington      | 2         | 1.29%   |
| Bagnolet            | 2         | 1.29%   |
| Ypsilanti           | 1         | 0.65%   |
| Yoshkar-Ola         | 1         | 0.65%   |
| Yakutsk             | 1         | 0.65%   |
| Willich             | 1         | 0.65%   |
| Wildberg            | 1         | 0.65%   |
| Whitby              | 1         | 0.65%   |
| Warsaw              | 1         | 0.65%   |
| Vilnius             | 1         | 0.65%   |
| Vienna              | 1         | 0.65%   |
| Valdemorillo        | 1         | 0.65%   |
| Valbonne            | 1         | 0.65%   |
| Tychy               | 1         | 0.65%   |
| Trubchëvsk         | 1         | 0.65%   |
| Tokyo               | 1         | 0.65%   |
| Timonium            | 1         | 0.65%   |
| Tel Aviv            | 1         | 0.65%   |
| Tejgaon             | 1         | 0.65%   |
| Tallinn             | 1         | 0.65%   |
| Syktyvkar           | 1         | 0.65%   |
| Staunton            | 1         | 0.65%   |
| St Petersburg       | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 29        | 42     | 15.93%  |
| WDC                         | 21        | 26     | 11.54%  |
| Seagate                     | 17        | 17     | 9.34%   |
| Unknown                     | 13        | 16     | 7.14%   |
| Kingston                    | 11        | 14     | 6.04%   |
| Toshiba                     | 9         | 9      | 4.95%   |
| Crucial                     | 9         | 12     | 4.95%   |
| SanDisk                     | 8         | 8      | 4.4%    |
| Intel                       | 8         | 9      | 4.4%    |
| Hitachi                     | 6         | 6      | 3.3%    |
| SK hynix                    | 5         | 5      | 2.75%   |
| HGST                        | 4         | 4      | 2.2%    |
| PNY                         | 3         | 3      | 1.65%   |
| Patriot                     | 3         | 3      | 1.65%   |
| Micron Technology           | 3         | 4      | 1.65%   |
| LITEON                      | 3         | 6      | 1.65%   |
| Fujitsu                     | 3         | 3      | 1.65%   |
| Team                        | 2         | 2      | 1.1%    |
| LITEONIT                    | 2         | 2      | 1.1%    |
| China                       | 2         | 2      | 1.1%    |
| A-DATA Technology           | 2         | 2      | 1.1%    |
| Union Memory                | 1         | 2      | 0.55%   |
| UMIS                        | 1         | 1      | 0.55%   |
| Teclast                     | 1         | 1      | 0.55%   |
| SSSTC                       | 1         | 1      | 0.55%   |
| Smart                       | 1         | 1      | 0.55%   |
| SABRENT                     | 1         | 2      | 0.55%   |
| Mushkin                     | 1         | 1      | 0.55%   |
| Lexar                       | 1         | 1      | 0.55%   |
| KIOXIA                      | 1         | 1      | 0.55%   |
| Kingston Technology Company | 1         | 1      | 0.55%   |
| KingFast                    | 1         | 1      | 0.55%   |
| Intenso                     | 1         | 1      | 0.55%   |
| IBM/Hitachi                 | 1         | 1      | 0.55%   |
| HXY                         | 1         | 1      | 0.55%   |
| Hewlett-Packard             | 1         | 1      | 0.55%   |
| faspeed                     | 1         | 1      | 0.55%   |
| DEMO                        | 1         | 1      | 0.55%   |
| Aura                        | 1         | 1      | 0.55%   |
| Apple                       | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 5         | 2.69%   |
| Toshiba MQ04ABF100 1TB               | 4         | 2.15%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 2.15%   |
| Unknown MMC Card  128GB              | 3         | 1.61%   |
| Samsung SSD 870 EVO 1TB              | 3         | 1.61%   |
| PNY CS900 240GB SSD                  | 3         | 1.61%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.61%   |
| WDC WDS500G2B0A-00SM50 500GB         | 2         | 1.08%   |
| Seagate ST9250410AS 250GB            | 2         | 1.08%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.08%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 1.08%   |
| Samsung SSD 980 PRO 1TB              | 2         | 1.08%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 1.08%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.08%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.08%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.08%   |
| Samsung MZVLW512HMJP-000L7 512GB     | 2         | 1.08%   |
| Patriot Burst 960GB SSD              | 2         | 1.08%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 1.08%   |
| Intel SSDPEKKF256G8L 256GB           | 2         | 1.08%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.08%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.08%   |
| WDC WDS500G1B0A-00H9H0 500GB SSD     | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.54%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.54%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.54%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.54%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.54%   |
| WDC WD3200BEVT-60ZCT0 320GB          | 1         | 0.54%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.54%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 0.54%   |
| WDC WD2500BEKT-00A25T0 250GB         | 1         | 0.54%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.54%   |
| WDC WD1600BEVT-75A23T0 160GB         | 1         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.54%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.54%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.54%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.54%   |
| WDC PC SN540 SDDPNPF-512G-1032 512GB | 1         | 0.54%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 17        | 17     | 34%     |
| WDC         | 12        | 14     | 24%     |
| Toshiba     | 7         | 7      | 14%     |
| Hitachi     | 6         | 6      | 12%     |
| HGST        | 4         | 4      | 8%      |
| Fujitsu     | 3         | 3      | 6%      |
| IBM/Hitachi | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 17     | 22.73%  |
| Kingston            | 9         | 10     | 13.64%  |
| SanDisk             | 5         | 5      | 7.58%   |
| Crucial             | 5         | 8      | 7.58%   |
| WDC                 | 4         | 5      | 6.06%   |
| PNY                 | 3         | 3      | 4.55%   |
| Patriot             | 3         | 3      | 4.55%   |
| Team                | 2         | 2      | 3.03%   |
| SK hynix            | 2         | 2      | 3.03%   |
| LITEONIT            | 2         | 2      | 3.03%   |
| LITEON              | 2         | 5      | 3.03%   |
| China               | 2         | 2      | 3.03%   |
| Union Memory        | 1         | 2      | 1.52%   |
| Teclast             | 1         | 1      | 1.52%   |
| Smart               | 1         | 1      | 1.52%   |
| SABRENT             | 1         | 2      | 1.52%   |
| Mushkin             | 1         | 1      | 1.52%   |
| Micron Technology   | 1         | 1      | 1.52%   |
| Intenso             | 1         | 1      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| HXY                 | 1         | 1      | 1.52%   |
| Hewlett-Packard     | 1         | 1      | 1.52%   |
| faspeed             | 1         | 1      | 1.52%   |
| Apple               | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 59        | 78     | 34.71%  |
| HDD     | 50        | 52     | 29.41%  |
| NVMe    | 48        | 69     | 28.24%  |
| MMC     | 12        | 15     | 7.06%   |
| Unknown | 1         | 2      | 0.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 128    | 61.21%  |
| NVMe | 48        | 68     | 29.09%  |
| MMC  | 12        | 15     | 7.27%   |
| SAS  | 4         | 5      | 2.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 92     | 74.07%  |
| 0.51-1.0   | 23        | 30     | 21.3%   |
| 1.01-2.0   | 3         | 5      | 2.78%   |
| 3.01-4.0   | 2         | 3      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 38        | 24.36%  |
| 101-250        | 37        | 23.72%  |
| 501-1000       | 24        | 15.38%  |
| 51-100         | 18        | 11.54%  |
| 21-50          | 11        | 7.05%   |
| 1001-2000      | 10        | 6.41%   |
| 1-20           | 7         | 4.49%   |
| Unknown        | 6         | 3.85%   |
| More than 3000 | 3         | 1.92%   |
| 2001-3000      | 2         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 57        | 35.63%  |
| 21-50          | 24        | 15%     |
| 101-250        | 24        | 15%     |
| 51-100         | 20        | 12.5%   |
| 251-500        | 18        | 11.25%  |
| Unknown        | 6         | 3.75%   |
| 501-1000       | 5         | 3.13%   |
| 1001-2000      | 4         | 2.5%    |
| More than 3000 | 1         | 0.63%   |
| 2001-3000      | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB   | 2         | 2      | 11.76%  |
| WDC WD5000LPCX-24C6HT0 500GB      | 1         | 1      | 5.88%   |
| WDC WD5000BPVT-24HXZT3 500GB      | 1         | 1      | 5.88%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 5.88%   |
| WDC WD1600BEVT-75A23T0 160GB      | 1         | 1      | 5.88%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 5.88%   |
| Seagate ST9200420ASG 200GB        | 1         | 1      | 5.88%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 5.88%   |
| Seagate ST320LT007-9ZV142 320GB   | 1         | 1      | 5.88%   |
| Seagate ST1000LM014-SSHD-8GB      | 1         | 1      | 5.88%   |
| Intel SSDSC2KF256H6 SATA 256GB    | 1         | 1      | 5.88%   |
| IBM/Hitachi IC25N060ATMR04-0 64GB | 1         | 1      | 5.88%   |
| Hitachi HTS727575A9E364 752GB     | 1         | 1      | 5.88%   |
| Hitachi HTS726060M9AT00 56GB      | 1         | 1      | 5.88%   |
| HGST HTS545050A7E680 500GB        | 1         | 1      | 5.88%   |
| Fujitsu MHV2080AH 80GB            | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 6      | 35.29%  |
| WDC         | 5         | 5      | 29.41%  |
| Hitachi     | 2         | 2      | 11.76%  |
| Intel       | 1         | 1      | 5.88%   |
| IBM/Hitachi | 1         | 1      | 5.88%   |
| HGST        | 1         | 1      | 5.88%   |
| Fujitsu     | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 6      | 37.5%   |
| WDC         | 5         | 5      | 31.25%  |
| Hitachi     | 2         | 2      | 12.5%   |
| IBM/Hitachi | 1         | 1      | 6.25%   |
| HGST        | 1         | 1      | 6.25%   |
| Fujitsu     | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 94.12%  |
| SSD  | 1         | 1      | 5.88%   |

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
| Works    | 104       | 150    | 66.24%  |
| Detected | 36        | 49     | 22.93%  |
| Malfunc  | 17        | 17     | 10.83%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 101       | 61.96%  |
| Samsung Electronics            | 14        | 8.59%   |
| AMD                            | 13        | 7.98%   |
| Sandisk                        | 8         | 4.91%   |
| SK hynix                       | 3         | 1.84%   |
| Micron/Crucial Technology      | 3         | 1.84%   |
| Micron Technology              | 3         | 1.84%   |
| Kingston Technology Company    | 3         | 1.84%   |
| VIA Technologies               | 2         | 1.23%   |
| Toshiba America Info Systems   | 2         | 1.23%   |
| Nvidia                         | 2         | 1.23%   |
| ADATA Technology               | 2         | 1.23%   |
| Union Memory (Shenzhen)        | 1         | 0.61%   |
| Solidigm                       | 1         | 0.61%   |
| Solid State Storage Technology | 1         | 0.61%   |
| Silicon Motion                 | 1         | 0.61%   |
| Shenzhen Longsys Electronics   | 1         | 0.61%   |
| Lite-On Technology             | 1         | 0.61%   |
| KIOXIA                         | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 6.74%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 6.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 4.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 3.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 3.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 3.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 3.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.25%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 2.25%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 1.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.69%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.69%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                    | 2         | 1.12%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 2         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.12%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.12%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 2         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.12%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.56%   |
| VIA VT8237A Integrated SATA RAID Controller                                    | 1         | 0.56%   |
| VIA VT6421 IDE/SATA Controller                                                 | 1         | 0.56%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 0.56%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.56%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 0.56%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                           | 1         | 0.56%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.56%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.56%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 91        | 54.49%  |
| NVMe | 48        | 28.74%  |
| IDE  | 20        | 11.98%  |
| RAID | 8         | 4.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 124       | 83.22%  |
| AMD    | 23        | 15.44%  |
| ARM    | 2         | 1.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 4.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 2.01%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.01%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 3         | 2.01%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 1.34%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.34%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.34%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 1.34%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 1.34%   |
| Intel 12th Gen Core i5-12500H                 | 2         | 1.34%   |
| ARM Nokia RX-51 board Processor               | 2         | 1.34%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.34%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.34%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.34%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 1.34%   |
| Intel Pentium M processor 2.00GHz             | 1         | 0.67%   |
| Intel Pentium M processor 1700MHz             | 1         | 0.67%   |
| Intel Pentium M processor 1200MHz             | 1         | 0.67%   |
| Intel Pentium M processor 1.60GHz             | 1         | 0.67%   |
| Intel Pentium M processor 1.50GHz             | 1         | 0.67%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.67%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.67%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.67%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.67%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.67%   |
| Intel Genuine CPU T1600 @ 1.66GHz             | 1         | 0.67%   |
| Intel Core Ultra 7 256V                       | 1         | 0.67%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.67%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 1         | 0.67%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.67%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.67%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 27        | 18.12%  |
| Intel Core i5           | 26        | 17.45%  |
| Intel Core i3           | 17        | 11.41%  |
| Other                   | 16        | 10.74%  |
| Intel Celeron           | 8         | 5.37%   |
| AMD Ryzen 5             | 8         | 5.37%   |
| Intel Core 2 Duo        | 7         | 4.7%    |
| Intel Pentium M         | 5         | 3.36%   |
| Intel Atom              | 5         | 3.36%   |
| AMD Ryzen 7             | 5         | 3.36%   |
| Intel Pentium Dual-Core | 3         | 2.01%   |
| Intel Pentium           | 3         | 2.01%   |
| Intel Core 2            | 3         | 2.01%   |
| Intel Core i9           | 2         | 1.34%   |
| Intel Celeron M         | 2         | 1.34%   |
| Intel Pentium Dual      | 1         | 0.67%   |
| Intel Genuine           | 1         | 0.67%   |
| Intel Core m5           | 1         | 0.67%   |
| Intel Core              | 1         | 0.67%   |
| AMD Turion 64 X2        | 1         | 0.67%   |
| AMD Ryzen 9             | 1         | 0.67%   |
| AMD E2                  | 1         | 0.67%   |
| AMD E                   | 1         | 0.67%   |
| AMD Athlon II           | 1         | 0.67%   |
| AMD A8                  | 1         | 0.67%   |
| AMD A6                  | 1         | 0.67%   |
| AMD A10                 | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 79        | 53.02%  |
| 4      | 32        | 21.48%  |
| 1      | 14        | 9.4%    |
| 6      | 12        | 8.05%   |
| 8      | 7         | 4.7%    |
| 12     | 3         | 2.01%   |
| 10     | 2         | 1.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 149       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 66.67%  |
| 1      | 50        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 138       | 92.62%  |
| 32-bit         | 8         | 5.37%   |
| Unknown        | 3         | 2.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 33.97%  |
| 0x306a9    | 9         | 5.77%   |
| 0x406e3    | 7         | 4.49%   |
| 0x40651    | 6         | 3.85%   |
| 0x306c3    | 6         | 3.85%   |
| 0x806ec    | 5         | 3.21%   |
| 0x20655    | 5         | 3.21%   |
| 0x1067a    | 5         | 3.21%   |
| 0x806c1    | 4         | 2.56%   |
| 0x206a7    | 4         | 2.56%   |
| 0x906ea    | 3         | 1.92%   |
| 0x806ea    | 3         | 1.92%   |
| 0x6d8      | 3         | 1.92%   |
| 0x306d4    | 3         | 1.92%   |
| 0x30678    | 3         | 1.92%   |
| 0x906a3    | 2         | 1.28%   |
| 0x706a1    | 2         | 1.28%   |
| 0x6fd      | 2         | 1.28%   |
| 0x6f6      | 2         | 1.28%   |
| 0x695      | 2         | 1.28%   |
| 0x406c4    | 2         | 1.28%   |
| 0x20652    | 2         | 1.28%   |
| 0x08608103 | 2         | 1.28%   |
| 0x906ed    | 1         | 0.64%   |
| 0x906a4    | 1         | 0.64%   |
| 0x806eb    | 1         | 0.64%   |
| 0x706a8    | 1         | 0.64%   |
| 0x6e8      | 1         | 0.64%   |
| 0x30661    | 1         | 0.64%   |
| 0x106ca    | 1         | 0.64%   |
| 0x106c2    | 1         | 0.64%   |
| 0x10676    | 1         | 0.64%   |
| 0x0a50000d | 1         | 0.64%   |
| 0x08a00008 | 1         | 0.64%   |
| 0x08600106 | 1         | 0.64%   |
| 0x08600102 | 1         | 0.64%   |
| 0x08108109 | 1         | 0.64%   |
| 0x08101016 | 1         | 0.64%   |
| 0x0810100b | 1         | 0.64%   |
| 0x07030105 | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 14.67%  |
| Haswell          | 14        | 9.33%   |
| IvyBridge        | 13        | 8.67%   |
| Unknown          | 10        | 6.67%   |
| Westmere         | 9         | 6%      |
| Penryn           | 8         | 5.33%   |
| Core             | 8         | 5.33%   |
| Skylake          | 7         | 4.67%   |
| P6               | 7         | 4.67%   |
| TigerLake        | 6         | 4%      |
| Silvermont       | 6         | 4%      |
| SandyBridge      | 5         | 3.33%   |
| Alderlake Hybrid | 5         | 3.33%   |
| Broadwell        | 4         | 2.67%   |
| Zen 3            | 3         | 2%      |
| Zen              | 3         | 2%      |
| Goldmont plus    | 3         | 2%      |
| Excavator        | 3         | 2%      |
| Bonnell          | 3         | 2%      |
| Zen 2            | 2         | 1.33%   |
| CometLake        | 2         | 1.33%   |
| Bobcat           | 2         | 1.33%   |
| Zen+             | 1         | 0.67%   |
| Puma             | 1         | 0.67%   |
| Piledriver       | 1         | 0.67%   |
| K8 Hammer        | 1         | 0.67%   |
| K10              | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 113       | 65.7%   |
| AMD              | 31        | 18.02%  |
| Nvidia           | 27        | 15.7%   |
| VIA Technologies | 1         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 6.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 4.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 4.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 4.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 3.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.75%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 5         | 2.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.75%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 4         | 2.2%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 4         | 2.2%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 4         | 2.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.65%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.65%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 3         | 1.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.65%   |
| AMD Lucienne                                                                             | 3         | 1.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.1%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.1%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.1%    |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 1.1%    |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 2         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.1%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 1.1%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 1.1%    |
| AMD Barcelo                                                                              | 2         | 1.1%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.55%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.55%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.55%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.55%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.55%   |
| Nvidia GP107M [GeForce MX150]                                                            | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 80        | 53.33%  |
| Intel + Nvidia | 20        | 13.33%  |
| 1 x AMD        | 20        | 13.33%  |
| 2 x Intel      | 7         | 4.67%   |
| 2 x AMD        | 6         | 4%      |
| 1 x Nvidia     | 6         | 4%      |
| Other          | 5         | 3.33%   |
| Intel + AMD    | 4         | 2.67%   |
| 1 x VIA        | 1         | 0.67%   |
| AMD + Nvidia   | 1         | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 133       | 88.67%  |
| Unknown     | 10        | 6.67%   |
| Proprietary | 7         | 4.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 75.5%   |
| 0.01-0.5   | 12        | 7.95%   |
| 0.51-1.0   | 10        | 6.62%   |
| 1.01-2.0   | 8         | 5.3%    |
| 5.01-6.0   | 3         | 1.99%   |
| 3.01-4.0   | 3         | 1.99%   |
| 8.01-16.0  | 1         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 27        | 16.67%  |
| AU Optronics            | 25        | 15.43%  |
| LG Display              | 23        | 14.2%   |
| Samsung Electronics     | 18        | 11.11%  |
| Chimei Innolux          | 18        | 11.11%  |
| Dell                    | 7         | 4.32%   |
| PANDA                   | 5         | 3.09%   |
| Lenovo                  | 5         | 3.09%   |
| Chi Mei Optoelectronics | 4         | 2.47%   |
| Sharp                   | 3         | 1.85%   |
| Goldstar                | 3         | 1.85%   |
| MStar                   | 2         | 1.23%   |
| InnoLux Display         | 2         | 1.23%   |
| Apple                   | 2         | 1.23%   |
| AOC                     | 2         | 1.23%   |
| Acer                    | 2         | 1.23%   |
| ZLX                     | 1         | 0.62%   |
| Unknown                 | 1         | 0.62%   |
| TMA                     | 1         | 0.62%   |
| STD                     | 1         | 0.62%   |
| Lenovo Group Limited    | 1         | 0.62%   |
| InfoVision              | 1         | 0.62%   |
| Iiyama                  | 1         | 0.62%   |
| Hisense                 | 1         | 0.62%   |
| HannStar                | 1         | 0.62%   |
| Fujitsu Siemens         | 1         | 0.62%   |
| CSO                     | 1         | 0.62%   |
| CPT                     | 1         | 0.62%   |
| Ancor Communications    | 1         | 0.62%   |
| Unknown                 | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch     | 3         | 1.85%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2         | 1.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.23%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 2         | 1.23%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 2         | 1.23%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 2         | 1.23%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                 | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 1.23%   |
| ZLX Dummy display ZLX0301 1920x1080 480x270mm 21.7-inch               | 1         | 0.62%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.62%   |
| TMA LCD Monitor TMA2036 2880x1800 330x206mm 15.3-inch                 | 1         | 0.62%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 0.62%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.62%   |
| Sharp LCD Monitor SHP144F 1920x1080 276x156mm 12.5-inch               | 1         | 0.62%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.62%   |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 1         | 0.62%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 1         | 0.62%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| PANDA LCD Monitor NCP002E 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 344x194mm 15.5-inch         | 1         | 0.62%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 61        | 39.35%  |
| 1366x768 (WXGA)    | 54        | 34.84%  |
| 1600x900 (HD+)     | 8         | 5.16%   |
| 3840x2160 (4K)     | 6         | 3.87%   |
| 1280x800 (WXGA)    | 6         | 3.87%   |
| 1920x1200 (WUXGA)  | 4         | 2.58%   |
| 2560x1440 (QHD)    | 3         | 1.94%   |
| 1680x1050 (WSXGA+) | 2         | 1.29%   |
| 1440x900 (WXGA+)   | 2         | 1.29%   |
| 1024x600           | 2         | 1.29%   |
| 5760x1080          | 1         | 0.65%   |
| 3200x1800 (QHD+)   | 1         | 0.65%   |
| 2880x1800          | 1         | 0.65%   |
| 2288x1287          | 1         | 0.65%   |
| 2256x1504          | 1         | 0.65%   |
| 2160x1440          | 1         | 0.65%   |
| Unknown            | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 62        | 38.75%  |
| 14      | 22        | 13.75%  |
| 13      | 17        | 10.63%  |
| 12      | 15        | 9.38%   |
| 24      | 10        | 6.25%   |
| 27      | 6         | 3.75%   |
| 11      | 6         | 3.75%   |
| 17      | 5         | 3.13%   |
| 21      | 3         | 1.88%   |
| 52      | 2         | 1.25%   |
| 31      | 2         | 1.25%   |
| 10      | 2         | 1.25%   |
| 142     | 1         | 0.63%   |
| 54      | 1         | 0.63%   |
| 25      | 1         | 0.63%   |
| 23      | 1         | 0.63%   |
| 22      | 1         | 0.63%   |
| 20      | 1         | 0.63%   |
| 16      | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 92        | 57.86%  |
| 201-300        | 31        | 19.5%   |
| 501-600        | 17        | 10.69%  |
| 351-400        | 7         | 4.4%    |
| 401-500        | 5         | 3.14%   |
| 1001-1500      | 3         | 1.89%   |
| 601-700        | 2         | 1.26%   |
| More than 2000 | 1         | 0.63%   |
| Unknown        | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 120       | 85.11%  |
| 16/10   | 17        | 12.06%  |
| 3/2     | 2         | 1.42%   |
| 1.00    | 1         | 0.71%   |
| Unknown | 1         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 62        | 38.75%  |
| 81-90          | 32        | 20%     |
| 61-70          | 15        | 9.38%   |
| 201-250        | 11        | 6.88%   |
| 71-80          | 7         | 4.38%   |
| 51-60          | 6         | 3.75%   |
| 301-350        | 6         | 3.75%   |
| 251-300        | 5         | 3.13%   |
| More than 1000 | 4         | 2.5%    |
| 121-130        | 3         | 1.88%   |
| 351-500        | 2         | 1.25%   |
| 41-50          | 2         | 1.25%   |
| 131-140        | 2         | 1.25%   |
| 151-200        | 1         | 0.63%   |
| 111-120        | 1         | 0.63%   |
| Unknown        | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 63        | 39.87%  |
| 101-120       | 45        | 28.48%  |
| 51-100        | 27        | 17.09%  |
| 161-240       | 16        | 10.13%  |
| 1-50          | 4         | 2.53%   |
| More than 240 | 2         | 1.27%   |
| Unknown       | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 127       | 79.87%  |
| 2     | 23        | 14.47%  |
| 0     | 6         | 3.77%   |
| 3     | 3         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 75        | 30.36%  |
| Realtek Semiconductor      | 67        | 27.13%  |
| Qualcomm Atheros           | 41        | 16.6%   |
| Broadcom                   | 14        | 5.67%   |
| MediaTek                   | 9         | 3.64%   |
| Broadcom Limited           | 6         | 2.43%   |
| Ralink Technology          | 4         | 1.62%   |
| Marvell Technology Group   | 4         | 1.62%   |
| ICS Advent                 | 3         | 1.21%   |
| VIA Technologies           | 2         | 0.81%   |
| TP-Link                    | 2         | 0.81%   |
| Sierra Wireless            | 2         | 0.81%   |
| Samsung Electronics        | 2         | 0.81%   |
| Ralink                     | 2         | 0.81%   |
| ZTE WCDMA Technologies MSM | 1         | 0.4%    |
| Xiaomi                     | 1         | 0.4%    |
| Shenzhen Goodix Technology | 1         | 0.4%    |
| Qualcomm                   | 1         | 0.4%    |
| Nvidia                     | 1         | 0.4%    |
| NetGear                    | 1         | 0.4%    |
| Motorola PCS               | 1         | 0.4%    |
| JMicron Technology         | 1         | 0.4%    |
| Huawei Technologies        | 1         | 0.4%    |
| Hewlett-Packard            | 1         | 0.4%    |
| Edimax Technology          | 1         | 0.4%    |
| DisplayLink                | 1         | 0.4%    |
| Dell                       | 1         | 0.4%    |
| ASIX Electronics           | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 44        | 14.52%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 14        | 4.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 3.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 3.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.65%   |
| Intel Wireless 8260                                                     | 5         | 1.65%   |
| Intel Wireless 7260                                                     | 5         | 1.65%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.32%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 4         | 1.32%   |
| Intel Wireless 7265                                                     | 4         | 1.32%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 4         | 1.32%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.99%   |
| Intel Wireless 8265 / 8275                                              | 3         | 0.99%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 0.99%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.99%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.99%   |
| ICS Advent 10/100M LAN                                                  | 3         | 0.99%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.99%   |
| Sierra Wireless EM7455                                                  | 2         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.66%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 59        | 40.14%  |
| Qualcomm Atheros      | 36        | 24.49%  |
| Realtek Semiconductor | 17        | 11.56%  |
| Broadcom              | 9         | 6.12%   |
| MediaTek              | 8         | 5.44%   |
| Broadcom Limited      | 5         | 3.4%    |
| Ralink Technology     | 4         | 2.72%   |
| Sierra Wireless       | 2         | 1.36%   |
| Ralink                | 2         | 1.36%   |
| TP-Link               | 1         | 0.68%   |
| NetGear               | 1         | 0.68%   |
| Hewlett-Packard       | 1         | 0.68%   |
| Edimax Technology     | 1         | 0.68%   |
| Dell                  | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 6.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.4%    |
| Intel Wireless 8260                                                     | 5         | 3.4%    |
| Intel Wireless 7260                                                     | 5         | 3.4%    |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.72%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 4         | 2.72%   |
| Intel Wireless 7265                                                     | 4         | 2.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 2.04%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.04%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 2.04%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 2.04%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.04%   |
| Sierra Wireless EM7455                                                  | 2         | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.36%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.36%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.36%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 1.36%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 1.36%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.36%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.36%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.36%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.36%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.68%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.68%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.68%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.68%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 62        | 42.76%  |
| Intel                    | 47        | 32.41%  |
| Qualcomm Atheros         | 8         | 5.52%   |
| Broadcom                 | 6         | 4.14%   |
| Marvell Technology Group | 4         | 2.76%   |
| ICS Advent               | 3         | 2.07%   |
| VIA Technologies         | 2         | 1.38%   |
| Samsung Electronics      | 2         | 1.38%   |
| Xiaomi                   | 1         | 0.69%   |
| TP-Link                  | 1         | 0.69%   |
| Qualcomm                 | 1         | 0.69%   |
| Nvidia                   | 1         | 0.69%   |
| Motorola PCS             | 1         | 0.69%   |
| MediaTek                 | 1         | 0.69%   |
| JMicron Technology       | 1         | 0.69%   |
| Huawei Technologies      | 1         | 0.69%   |
| DisplayLink              | 1         | 0.69%   |
| Broadcom Limited         | 1         | 0.69%   |
| ASIX Electronics         | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44        | 29.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 9.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 8.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 2.01%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 2.01%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 2.01%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.01%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 2.01%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 2.01%   |
| ICS Advent 10/100M LAN                                                 | 3         | 2.01%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 1.34%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.34%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.34%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.67%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.67%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.67%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.67%   |
| Qualcomm YUPIK-QRD _SN:AC1D5909                                        | 1         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.67%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.67%   |
| Motorola PCS motorola one 5G ace                                       | 1         | 0.67%   |
| MediaTek A015                                                          | 1         | 0.67%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.67%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                   | 1         | 0.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.67%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.67%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 49.29%  |
| Ethernet | 135       | 48.21%  |
| Modem    | 7         | 2.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 65.16%  |
| Ethernet | 53        | 34.19%  |
| Modem    | 1         | 0.65%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 121       | 81.21%  |
| 1     | 22        | 14.77%  |
| 0     | 6         | 4.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 121       | 81.21%  |
| Yes  | 28        | 18.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 34.95%  |
| Qualcomm Atheros Communications | 12        | 11.65%  |
| Realtek Semiconductor           | 9         | 8.74%   |
| Broadcom                        | 9         | 8.74%   |
| Lite-On Technology              | 6         | 5.83%   |
| IMC Networks                    | 6         | 5.83%   |
| Dell                            | 5         | 4.85%   |
| Foxconn / Hon Hai               | 4         | 3.88%   |
| Cambridge Silicon Radio         | 4         | 3.88%   |
| Foxconn International           | 3         | 2.91%   |
| MediaTek                        | 2         | 1.94%   |
| TP-Link                         | 1         | 0.97%   |
| Realtek                         | 1         | 0.97%   |
| Ralink                          | 1         | 0.97%   |
| Hewlett-Packard                 | 1         | 0.97%   |
| Fujitsu                         | 1         | 0.97%   |
| ASUSTek Computer                | 1         | 0.97%   |
| Apple                           | 1         | 0.97%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 14.56%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 9.71%   |
| Realtek Bluetooth Radio                             | 9         | 8.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 8.74%   |
| Intel AX200 Bluetooth                               | 5         | 4.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 4.85%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 3.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 3.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.91%   |
| IMC Networks Wireless_Device                        | 3         | 2.91%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 2.91%   |
| MediaTek Wireless_Device                            | 2         | 1.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.94%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.94%   |
| TP-Link TP-T@- UB500 Adapter                        | 1         | 0.97%   |
| Realtek Bluetooth Radio                             | 1         | 0.97%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.97%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.97%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.97%   |
| Lite-On Bluetooth Device                            | 1         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.97%   |
| Intel Bluetooth Device                              | 1         | 0.97%   |
| Intel AX210 Bluetooth                               | 1         | 0.97%   |
| IMC Networks Bluetooth Device                       | 1         | 0.97%   |
| IMC Networks BCM20702A0                             | 1         | 0.97%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.97%   |
| Fujitsu Bluetooth Device                            | 1         | 0.97%   |
| Foxconn / Hon Hai BT                                | 1         | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.97%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.97%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.97%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.97%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 0.97%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.97%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 120       | 68.97%  |
| AMD                   | 27        | 15.52%  |
| Nvidia                | 16        | 9.2%    |
| C-Media Electronics   | 4         | 2.3%    |
| VIA Technologies      | 1         | 0.57%   |
| Samsung Electronics   | 1         | 0.57%   |
| Realtek Semiconductor | 1         | 0.57%   |
| JMTek                 | 1         | 0.57%   |
| GYROCOM C&C           | 1         | 0.57%   |
| GN Netcom             | 1         | 0.57%   |
| Blue Microphones      | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 7.01%   |
| AMD Ryzen HD Audio Controller                                              | 14        | 6.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 6.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 4.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 4.21%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 3.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 3.27%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 7         | 3.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 2.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 2.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.34%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.87%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.87%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.4%    |
| AMD FCH Azalia Controller                                                  | 3         | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.93%   |
| Nvidia AD107 High Definition Audio Controller                              | 2         | 0.93%   |
| C-Media Electronics CM106 Like Sound Device                                | 2         | 0.93%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.93%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.93%   |
| AMD High Definition Audio Controller                                       | 2         | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 0.93%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.47%   |
| Samsung Electronics Samsung USB C Earphones                                | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 28.38%  |
| SK hynix            | 25        | 16.89%  |
| Kingston            | 16        | 10.81%  |
| Unknown             | 14        | 9.46%   |
| Micron Technology   | 11        | 7.43%   |
| Crucial             | 9         | 6.08%   |
| A-DATA Technology   | 7         | 4.73%   |
| Nanya Technology    | 3         | 2.03%   |
| G.Skill             | 3         | 2.03%   |
| Ramaxel Technology  | 2         | 1.35%   |
| Corsair             | 2         | 1.35%   |
| Unknown             | 2         | 1.35%   |
| Unknown (F785)      | 1         | 0.68%   |
| Unknown (ABCD)      | 1         | 0.68%   |
| Transcend           | 1         | 0.68%   |
| Smart               | 1         | 0.68%   |
| PUSKILL             | 1         | 0.68%   |
| Goldkey             | 1         | 0.68%   |
| Elpida              | 1         | 0.68%   |
| Apacer              | 1         | 0.68%   |
| AMD                 | 1         | 0.68%   |
| A Force             | 1         | 0.68%   |
| 4ea5                | 1         | 0.68%   |
| 48spaces            | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.44%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 1.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.83%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.83%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 2         | 1.22%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.22%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 1.22%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.22%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.22%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 2         | 1.22%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.22%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.22%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 2         | 1.22%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.22%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.22%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.22%   |
| Unknown                                                          | 2         | 1.22%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.61%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.61%   |
| Unknown (F785) RAM Module 16GB SODIMM DDR4 3200MT/s              | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.61%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR 667MT/s                 | 1         | 0.61%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1066MT/s                     | 1         | 0.61%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 0.61%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 49        | 38.58%  |
| DDR4    | 48        | 37.8%   |
| DDR2    | 7         | 5.51%   |
| SDRAM   | 6         | 4.72%   |
| DDR     | 5         | 3.94%   |
| LPDDR3  | 4         | 3.15%   |
| LPDDR5  | 2         | 1.57%   |
| LPDDR4  | 2         | 1.57%   |
| DDR5    | 2         | 1.57%   |
| DRAM    | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 116       | 94.31%  |
| Row Of Chips | 4         | 3.25%   |
| DIMM         | 1         | 0.81%   |
| Chip         | 1         | 0.81%   |
| Unknown      | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 31.29%  |
| 4096  | 37        | 25.17%  |
| 16384 | 23        | 15.65%  |
| 2048  | 22        | 14.97%  |
| 1024  | 10        | 6.8%    |
| 32768 | 5         | 3.4%    |
| 512   | 3         | 2.04%   |
| 12288 | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 37        | 26.81%  |
| 3200    | 22        | 15.94%  |
| 2667    | 20        | 14.49%  |
| 2400    | 9         | 6.52%   |
| Unknown | 8         | 5.8%    |
| 667     | 5         | 3.62%   |
| 4199    | 4         | 2.9%    |
| 1067    | 4         | 2.9%    |
| 800     | 4         | 2.9%    |
| 3266    | 3         | 2.17%   |
| 1334    | 3         | 2.17%   |
| 1333    | 3         | 2.17%   |
| 8400    | 2         | 1.45%   |
| 6400    | 2         | 1.45%   |
| 2133    | 2         | 1.45%   |
| 1066    | 2         | 1.45%   |
| 533     | 2         | 1.45%   |
| 5600    | 1         | 0.72%   |
| 4800    | 1         | 0.72%   |
| 2933    | 1         | 0.72%   |
| 1867    | 1         | 0.72%   |
| 1200    | 1         | 0.72%   |
| 975     | 1         | 0.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

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
| Chicony Electronics                    | 37        | 32.46%  |
| Bison Electronics                      | 13        | 11.4%   |
| Microdia                               | 9         | 7.89%   |
| Sunplus Innovation Technology          | 6         | 5.26%   |
| Realtek Semiconductor                  | 6         | 5.26%   |
| IMC Networks                           | 6         | 5.26%   |
| Quanta                                 | 5         | 4.39%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.39%   |
| Suyin                                  | 4         | 3.51%   |
| Luxvisions Innotech Limited            | 4         | 3.51%   |
| Acer                                   | 3         | 2.63%   |
| Syntek                                 | 2         | 1.75%   |
| Silicon Motion                         | 2         | 1.75%   |
| Lite-On Technology                     | 2         | 1.75%   |
| Z-Star Microelectronics                | 1         | 0.88%   |
| ShineTech                              | 1         | 0.88%   |
| Samsung Electronics                    | 1         | 0.88%   |
| OmniVision Technologies                | 1         | 0.88%   |
| Mustek Systems                         | 1         | 0.88%   |
| Logitech                               | 1         | 0.88%   |
| LG Electronics                         | 1         | 0.88%   |
| Lenovo                                 | 1         | 0.88%   |
| kingcome                               | 1         | 0.88%   |
| Genesys Logic                          | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 11        | 9.65%   |
| Chicony HD Webcam                                           | 4         | 3.51%   |
| IMC Networks Integrated Camera                              | 3         | 2.63%   |
| Bison Integrated RGB Camera                                 | 3         | 2.63%   |
| Bison BisonCam,NB Pro                                       | 3         | 2.63%   |
| Syntek Integrated Camera                                    | 2         | 1.75%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.75%   |
| Microdia Integrated Webcam                                  | 2         | 1.75%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 1.75%   |
| Chicony HP TrueVision HD Camera                             | 2         | 1.75%   |
| Chicony EasyCamera                                          | 2         | 1.75%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.75%   |
| Z-Star Webcam                                               | 1         | 0.88%   |
| Suyin Lenovo EasyCamera Integrated Webcam                   | 1         | 0.88%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 0.88%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.88%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.88%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.88%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.88%   |
| Sunplus Integrated Camera                                   | 1         | 0.88%   |
| Sunplus Dell Integrated Webcam                              | 1         | 0.88%   |
| Sunplus Asus Webcam                                         | 1         | 0.88%   |
| Sunplus 720p HD Camera                                      | 1         | 0.88%   |
| Silicon Motion Lenovo EasyCamera                            | 1         | 0.88%   |
| Silicon Motion HP Webcam-101                                | 1         | 0.88%   |
| ShineTech USB2.0 HD UVC WebCam                              | 1         | 0.88%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.88%   |
| Realtek USB Camera                                          | 1         | 0.88%   |
| Realtek Lenovo EasyCamera                                   | 1         | 0.88%   |
| Realtek Laptop Camera                                       | 1         | 0.88%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.88%   |
| Quanta USB webcam                                           | 1         | 0.88%   |
| Quanta Sony Visual Communication Camera                     | 1         | 0.88%   |
| Quanta HP HD Camera                                         | 1         | 0.88%   |
| Quanta HD Webcam                                            | 1         | 0.88%   |
| Quanta HD User Facing                                       | 1         | 0.88%   |
| OmniVision OV2640 Webcam                                    | 1         | 0.88%   |
| Mustek Systems USB 2.0 PC Camera                            | 1         | 0.88%   |
| Microdia Webcam Vitade AF                                   | 1         | 0.88%   |
| Microdia WebCam SC-13HDL12639P                              | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 42.86%  |
| Validity Sensors           | 3         | 21.43%  |
| STMicroelectronics         | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 21.43%  |
| Validity Sensors Synaptics WBDI                        | 2         | 14.29%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics WBDI Device                                  | 1         | 7.14%   |
| Synaptics TouchPad                                     | 1         | 7.14%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.14%   |
| AuthenTec AES2810                                      | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 47.83%  |
| Alcor Micro | 8         | 34.78%  |
| Upek        | 3         | 13.04%  |
| Lenovo      | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 34.78%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 17.39%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 17.39%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 13.04%  |
| Broadcom 5880                                                                | 2         | 8.7%    |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.35%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 95        | 61.69%  |
| 1     | 39        | 25.32%  |
| 2     | 16        | 10.39%  |
| 3     | 2         | 1.3%    |
| 5     | 1         | 0.65%   |
| 4     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chipcard                 | 18        | 24.66%  |
| Graphics card            | 17        | 23.29%  |
| Fingerprint reader       | 14        | 19.18%  |
| Net/wireless             | 7         | 9.59%   |
| Camera                   | 5         | 6.85%   |
| Multimedia controller    | 3         | 4.11%   |
| Communication controller | 3         | 4.11%   |
| Bluetooth                | 3         | 4.11%   |
| Storage                  | 1         | 1.37%   |
| Sound                    | 1         | 1.37%   |
| Card reader              | 1         | 1.37%   |

