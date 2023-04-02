Linux in Ireland - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

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

Total: 472

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 15-eh0xx... | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [889ef05f86](https://linux-hardware.org/?probe=889ef05f86) | Mar 30, 2023 |
| Dell          | Inspiron 13-5378            | [2aff972d11](https://linux-hardware.org/?probe=2aff972d11) | Mar 27, 2023 |
| Timi          | A35S                        | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Acer          | Aspire F5-573G              | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| MSI           | GP72 7RE                    | [729f2297cb](https://linux-hardware.org/?probe=729f2297cb) | Mar 23, 2023 |
| Dell          | Latitude 7420               | [ac9a26d11c](https://linux-hardware.org/?probe=ac9a26d11c) | Mar 20, 2023 |
| Samsung       | 940XFG                      | [566a4046f6](https://linux-hardware.org/?probe=566a4046f6) | Mar 18, 2023 |
| Google        | Reks                        | [56296236c5](https://linux-hardware.org/?probe=56296236c5) | Mar 12, 2023 |
| Dell          | Inspiron 5570               | [f6da200721](https://linux-hardware.org/?probe=f6da200721) | Mar 11, 2023 |
| Dell          | Inspiron 5570               | [56e5783575](https://linux-hardware.org/?probe=56e5783575) | Mar 11, 2023 |
| HP            | ProBook 4330s               | [00d887061a](https://linux-hardware.org/?probe=00d887061a) | Mar 10, 2023 |
| Google        | Reks                        | [f877db79d3](https://linux-hardware.org/?probe=f877db79d3) | Mar 09, 2023 |
| Dell          | Latitude 7420               | [00ef839a27](https://linux-hardware.org/?probe=00ef839a27) | Mar 06, 2023 |
| Dell          | Latitude 7420               | [18b4bfe200](https://linux-hardware.org/?probe=18b4bfe200) | Mar 06, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d70aeca173](https://linux-hardware.org/?probe=d70aeca173) | Mar 04, 2023 |
| Dell          | Latitude 7420               | [49bdd8711f](https://linux-hardware.org/?probe=49bdd8711f) | Mar 02, 2023 |
| HP            | EliteBook 755 G5            | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude 7420               | [d3af27a0ac](https://linux-hardware.org/?probe=d3af27a0ac) | Feb 27, 2023 |
| HP            | 655                         | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Valve         | Jupiter                     | [b6f7c77e33](https://linux-hardware.org/?probe=b6f7c77e33) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [bb18722cf2](https://linux-hardware.org/?probe=bb18722cf2) | Feb 21, 2023 |
| Dell          | Latitude E7240              | [fb6daef60c](https://linux-hardware.org/?probe=fb6daef60c) | Feb 17, 2023 |
| Dell          | G15 5520                    | [a5966eaac0](https://linux-hardware.org/?probe=a5966eaac0) | Feb 15, 2023 |
| Dell          | G3 3779                     | [cc77f75f3d](https://linux-hardware.org/?probe=cc77f75f3d) | Feb 15, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [181833b556](https://linux-hardware.org/?probe=181833b556) | Feb 09, 2023 |
| HP            | EliteBook 830 G5            | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Valve         | Jupiter                     | [50727dbbde](https://linux-hardware.org/?probe=50727dbbde) | Feb 02, 2023 |
| Valve         | Jupiter                     | [0323a2bd47](https://linux-hardware.org/?probe=0323a2bd47) | Jan 27, 2023 |
| ASUSTek       | X501A1                      | [a0493c6731](https://linux-hardware.org/?probe=a0493c6731) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [7b23698a1e](https://linux-hardware.org/?probe=7b23698a1e) | Jan 24, 2023 |
| Dell          | Latitude 7420               | [dc99eb6c92](https://linux-hardware.org/?probe=dc99eb6c92) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [7fb655b498](https://linux-hardware.org/?probe=7fb655b498) | Jan 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [397b4da9ab](https://linux-hardware.org/?probe=397b4da9ab) | Jan 21, 2023 |
| Dell          | Inspiron 5770               | [93932bdc92](https://linux-hardware.org/?probe=93932bdc92) | Jan 20, 2023 |
| Dell          | G5 5590                     | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude 5510               | [c9738f8691](https://linux-hardware.org/?probe=c9738f8691) | Jan 18, 2023 |
| Dell          | Inspiron 7560               | [fa1a881ee9](https://linux-hardware.org/?probe=fa1a881ee9) | Jan 17, 2023 |
| Dell          | Inspiron 7560               | [6941e3520e](https://linux-hardware.org/?probe=6941e3520e) | Jan 17, 2023 |
| Dell          | Inspiron 5570               | [5905971b70](https://linux-hardware.org/?probe=5905971b70) | Jan 16, 2023 |
| Valve         | Jupiter                     | [d390e11930](https://linux-hardware.org/?probe=d390e11930) | Jan 11, 2023 |
| Valve         | Jupiter                     | [a181d83115](https://linux-hardware.org/?probe=a181d83115) | Jan 11, 2023 |
| Dell          | Latitude 7420               | [4ce659b05d](https://linux-hardware.org/?probe=4ce659b05d) | Jan 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| Dell          | Latitude E7240              | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| Star Labs     | Lite                        | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| Dell          | Latitude 7420               | [cd159088a3](https://linux-hardware.org/?probe=cd159088a3) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | [1b8d741ea3](https://linux-hardware.org/?probe=1b8d741ea3) | Jan 03, 2023 |
| Samsung       | 940XFG                      | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| Dell          | Latitude 7420               | [60f07d5a45](https://linux-hardware.org/?probe=60f07d5a45) | Dec 16, 2022 |
| Dell          | Latitude 3310               | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Dell          | Latitude E7240              | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| Dynabook      | Satellite Pro C50-H-11G     | [57e8e4ab79](https://linux-hardware.org/?probe=57e8e4ab79) | Dec 06, 2022 |
| ASUSTek       | X510UNR                     | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| Dell          | Latitude 7290               | [3f0e476980](https://linux-hardware.org/?probe=3f0e476980) | Dec 04, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | Inspiron 15-7568            | [9887f68589](https://linux-hardware.org/?probe=9887f68589) | Dec 03, 2022 |
| Acer          | Nitro AN515-46              | [7bdc87a5cc](https://linux-hardware.org/?probe=7bdc87a5cc) | Dec 02, 2022 |
| Acer          | Nitro AN515-46              | [d17ff52554](https://linux-hardware.org/?probe=d17ff52554) | Dec 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [2c077b8cde](https://linux-hardware.org/?probe=2c077b8cde) | Nov 23, 2022 |
| Acer          | Aspire A514-55              | [7bf0186e00](https://linux-hardware.org/?probe=7bf0186e00) | Nov 18, 2022 |
| Chuwi         | X312B                       | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Chuwi         | X312B                       | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Valve         | Jupiter                     | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Chuwi         | X312B                       | [0e6a368329](https://linux-hardware.org/?probe=0e6a368329) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5d2ae18b0a](https://linux-hardware.org/?probe=5d2ae18b0a) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [51a3c87183](https://linux-hardware.org/?probe=51a3c87183) | Nov 10, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | Latitude E6440              | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Dell          | Latitude 7400               | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Toshiba       | PORTEGE R830                | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Timi          | TM1709                      | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| HP            | Pavilion m6                 | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| HP            | Pavilion g6                 | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| HP            | EliteBook 755 G5            | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Samsung       | 935XDB                      | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Samsung       | 935XDB                      | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Jumper        | EZbook                      | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| HP            | EliteBook 840 G1            | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | Stealth GS66 12UGS          | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| Dell          | Latitude E6520              | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| Packard Be... | EasyNote TK85               | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Dell          | Latitude E5440              | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| Dell          | Latitude E6430              | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| PC Special... | NH5xAx                      | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| Dell          | Latitude 9420               | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | XPS 13 9310                 | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Toshiba       | PORTEGE R830                | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291W99       | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Acer          | AOD255                      | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Dell          | Inspiron MM061              | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Dell          | XPS 13 9310                 | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Toshiba       | PORTEGE R830                | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Acer          | Nitro AN515-45              | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| Apple         | MacBookPro5,3               | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Sony          | VPCCB35FG                   | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Dell          | Studio XPS 1640             | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| Dell          | Latitude 7370               | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| Entroware     | Apollo                      | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Dell          | Inspiron 1525               | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| Dell          | XPS 13 9300                 | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | Inspiron 1764               | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| HP            | Pavilion 15                 | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 15                          | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Entroware     | Proteus                     | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| HP            | HDX 18                      | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| HP            | EliteBook Folio G1          | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Acer          | Aspire 5333                 | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| HP            | Pavilion g6                 | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Acer          | Aspire 5920G                | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | X540LA                      | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| HP            | Pavilion m6                 | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| HP            | EliteBook 745 G6            | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| HUAWEI        | BOHL-WXX9                   | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Samsung       | N150/N210/N220              | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| Dell          | System XPS L502X            | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| Acer          | Aspire 5551                 | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| Dell          | Latitude E6420              | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| Notebook      | NL40_50CU                   | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| System76      | Galago Pro                  | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Medion        | E6239 MD99452               | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| HP            | Laptop 14-bs0xx             | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Apple         | MacBook5,1                  | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| Dell          | XPS 13 9360                 | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| Toshiba       | Satellite L50-B             | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| HP            | G70                         | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| Apple         | MacBookPro12,1              | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| HP            | Laptop 14-bs0xx             | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Acer          | Aspire 5349                 | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| Dell          | Latitude E7450              | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| MSI           | WS65 9TK                    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Dell          | Latitude 5480               | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 255 G2                      | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| Dell          | Inspiron 15-3552            | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| SLIMBOOK      | PROX15                      | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Dell          | Latitude E5420              | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Dell          | Vostro 5490                 | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | ThinkPad T520 424329U       | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| HP            | EliteBook 8560w             | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Dell          | Latitude E7240              | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | XPS M1530                   | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| Dell          | Latitude E5450              | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| HP            | Pavilion dv6                | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| Dell          | Inspiron 13-5378            | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | Precision M6300             | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| System76      | Galago Pro                  | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Alienware     | 17 R4                       | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Lenovo        | V145-15AST 81MT             | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Acer          | Aspire ES1-512              | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| Acer          | Aspire E1-572               | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| Advent        | Roma                        | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| System76      | Bonobo Extreme              | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| HP            | Pavilion dv6                | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| ASUSTek       | S550CA                      | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| ASUSTek       | S550CA                      | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| Dell          | Inspiron ME051              | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| eMachines     | eM350                       | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Toshiba       | Satellite Pro C660          | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| Dell          | Latitude E6230              | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Acer          | Aspire E5-575G              | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| Dell          | Latitude E6230              | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 47        | 13.7%   |
| Ubuntu 18.04       | 28        | 8.16%   |
| Ubuntu 22.04       | 21        | 6.12%   |
| Debian 11          | 11        | 3.21%   |
| Pop!_OS 22.04      | 8         | 2.33%   |
| Fedora 36          | 7         | 2.04%   |
| Debian 10          | 7         | 2.04%   |
| Zorin 16           | 6         | 1.75%   |
| OpenMandriva 4.2   | 6         | 1.75%   |
| Ubuntu 19.10       | 5         | 1.46%   |
| Manjaro            | 5         | 1.46%   |
| Linux Mint 21.1    | 5         | 1.46%   |
| Linux Mint 21      | 5         | 1.46%   |
| Linux Mint 20.3    | 5         | 1.46%   |
| Linux Mint 20.2    | 5         | 1.46%   |
| Linux Mint 20      | 5         | 1.46%   |
| KDE neon 20.04     | 5         | 1.46%   |
| ArcoLinux Rolling  | 5         | 1.46%   |
| Ubuntu 21.10       | 4         | 1.17%   |
| Ubuntu 19.04       | 4         | 1.17%   |
| Pop!_OS 21.10      | 4         | 1.17%   |
| Pop!_OS 20.04      | 4         | 1.17%   |
| Lubuntu 20.04      | 4         | 1.17%   |
| Linux Mint 19.3    | 4         | 1.17%   |
| Fedora 37          | 4         | 1.17%   |
| Fedora 34          | 4         | 1.17%   |
| Debian Unstable    | 4         | 1.17%   |
| BlackPanther 18.1  | 4         | 1.17%   |
| Arch               | 4         | 1.17%   |
| Zorin 15           | 3         | 0.87%   |
| Ubuntu 22.10       | 3         | 0.87%   |
| ROSA R10           | 3         | 0.87%   |
| Pop!_OS 20.10      | 3         | 0.87%   |
| OpenMandriva 23.01 | 3         | 0.87%   |
| Linux Mint 19.2    | 3         | 0.87%   |
| Kubuntu 20.04      | 3         | 0.87%   |
| Fedora 33          | 3         | 0.87%   |
| Arch Rolling       | 3         | 0.87%   |
| Ubuntu Unity 16.04 | 2         | 0.58%   |
| Ubuntu MATE 20.04  | 2         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 114       | 34.65%  |
| Linux Mint    | 35        | 10.64%  |
| Debian        | 22        | 6.69%   |
| Pop!_OS       | 21        | 6.38%   |
| Fedora        | 21        | 6.38%   |
| OpenMandriva  | 12        | 3.65%   |
| Manjaro       | 12        | 3.65%   |
| Kubuntu       | 11        | 3.34%   |
| Zorin         | 9         | 2.74%   |
| Arch          | 7         | 2.13%   |
| ROSA          | 6         | 1.82%   |
| Lubuntu       | 6         | 1.82%   |
| KDE neon      | 5         | 1.52%   |
| Elementary    | 5         | 1.52%   |
| ArcoLinux     | 5         | 1.52%   |
| BlackPanther  | 4         | 1.22%   |
| Xubuntu       | 3         | 0.91%   |
| Ubuntu Unity  | 3         | 0.91%   |
| Ubuntu MATE   | 3         | 0.91%   |
| SteamOS       | 3         | 0.91%   |
| openSUSE      | 3         | 0.91%   |
| Endless       | 3         | 0.91%   |
| Ubuntu Budgie | 2         | 0.61%   |
| LMDE          | 2         | 0.61%   |
| Clear Linux   | 2         | 0.61%   |
| CentOS        | 2         | 0.61%   |
| Rocky Linux   | 1         | 0.3%    |
| RHEL          | 1         | 0.3%    |
| Redcore       | 1         | 0.3%    |
| Reborn OS     | 1         | 0.3%    |
| Peppermint    | 1         | 0.3%    |
| Nobara        | 1         | 0.3%    |
| MX            | 1         | 0.3%    |
| Chrome OS     | 1         | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.3.0-46-generic         | 8         | 2.16%   |
| 5.4.0-42-generic         | 6         | 1.62%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.62%   |
| 5.4.0-52-generic         | 5         | 1.35%   |
| 5.19.0-35-generic        | 5         | 1.35%   |
| 5.15.0-52-generic        | 5         | 1.35%   |
| 5.15.0-46-generic        | 5         | 1.35%   |
| 5.4.0-26-generic         | 4         | 1.08%   |
| 5.15.0-67-generic        | 4         | 1.08%   |
| 5.15.0-48-generic        | 4         | 1.08%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.81%   |
| 5.4.0-31-generic         | 3         | 0.81%   |
| 5.4.0-29-generic         | 3         | 0.81%   |
| 5.15.0-56-generic        | 3         | 0.81%   |
| 5.15.0-40-generic        | 3         | 0.81%   |
| 5.11.0-27-generic        | 3         | 0.81%   |
| 5.10.0-14-amd64          | 3         | 0.81%   |
| 4.19.0-9-amd64           | 3         | 0.81%   |
| 4.18.16-desktop-1bP      | 3         | 0.81%   |
| 6.0.6-76060006-generic   | 2         | 0.54%   |
| 6.0.12-76060006-generic  | 2         | 0.54%   |
| 6.0.10-300.fc37.x86_64   | 2         | 0.54%   |
| 5.8.0-7625-generic       | 2         | 0.54%   |
| 5.8.0-53-generic         | 2         | 0.54%   |
| 5.8.0-43-generic         | 2         | 0.54%   |
| 5.4.0-91-generic         | 2         | 0.54%   |
| 5.4.0-80-generic         | 2         | 0.54%   |
| 5.4.0-7634-generic       | 2         | 0.54%   |
| 5.4.0-73-generic         | 2         | 0.54%   |
| 5.4.0-72-generic         | 2         | 0.54%   |
| 5.4.0-65-generic         | 2         | 0.54%   |
| 5.4.0-62-generic         | 2         | 0.54%   |
| 5.4.0-58-generic         | 2         | 0.54%   |
| 5.4.0-56-generic         | 2         | 0.54%   |
| 5.4.0-54-generic         | 2         | 0.54%   |
| 5.4.0-53-generic         | 2         | 0.54%   |
| 5.4.0-40-generic         | 2         | 0.54%   |
| 5.4.0-135-generic        | 2         | 0.54%   |
| 5.3.0-40-generic         | 2         | 0.54%   |
| 5.3.0-18-generic         | 2         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 70        | 20.35%  |
| 5.15.0  | 30        | 8.72%   |
| 4.15.0  | 23        | 6.69%   |
| 5.3.0   | 17        | 4.94%   |
| 5.11.0  | 17        | 4.94%   |
| 5.8.0   | 15        | 4.36%   |
| 5.19.0  | 15        | 4.36%   |
| 5.13.0  | 13        | 3.78%   |
| 5.10.0  | 11        | 3.2%    |
| 5.0.0   | 8         | 2.33%   |
| 4.19.0  | 8         | 2.33%   |
| 5.10.14 | 6         | 1.74%   |
| 4.18.0  | 5         | 1.45%   |
| 6.1.1   | 3         | 0.87%   |
| 4.18.16 | 3         | 0.87%   |
| 6.0.6   | 2         | 0.58%   |
| 6.0.12  | 2         | 0.58%   |
| 6.0.10  | 2         | 0.58%   |
| 5.7.9   | 2         | 0.58%   |
| 5.6.7   | 2         | 0.58%   |
| 5.6.15  | 2         | 0.58%   |
| 5.6.0   | 2         | 0.58%   |
| 5.19.1  | 2         | 0.58%   |
| 5.18.17 | 2         | 0.58%   |
| 5.18.0  | 2         | 0.58%   |
| 5.17.5  | 2         | 0.58%   |
| 5.16.11 | 2         | 0.58%   |
| 5.14.0  | 2         | 0.58%   |
| 5.10.42 | 2         | 0.58%   |
| 4.9.60  | 2         | 0.58%   |
| 4.9.41  | 2         | 0.58%   |
| 4.12.14 | 2         | 0.58%   |
| 3.10.0  | 2         | 0.58%   |
| 6.2.8   | 1         | 0.29%   |
| 6.2.6   | 1         | 0.29%   |
| 6.2.0   | 1         | 0.29%   |
| 6.1.0   | 1         | 0.29%   |
| 6.0.9   | 1         | 0.29%   |
| 6.0.5   | 1         | 0.29%   |
| 6.0.2   | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 73        | 21.41%  |
| 5.15    | 36        | 10.56%  |
| 5.10    | 23        | 6.74%   |
| 4.15    | 23        | 6.74%   |
| 5.19    | 20        | 5.87%   |
| 5.3     | 18        | 5.28%   |
| 5.8     | 17        | 4.99%   |
| 5.11    | 17        | 4.99%   |
| 5.13    | 15        | 4.4%    |
| 6.0     | 11        | 3.23%   |
| 4.19    | 9         | 2.64%   |
| 5.0     | 8         | 2.35%   |
| 4.18    | 8         | 2.35%   |
| 5.6     | 7         | 2.05%   |
| 5.18    | 6         | 1.76%   |
| 5.17    | 6         | 1.76%   |
| 5.14    | 6         | 1.76%   |
| 5.16    | 5         | 1.47%   |
| 4.9     | 5         | 1.47%   |
| 6.1     | 4         | 1.17%   |
| 5.9     | 4         | 1.17%   |
| 5.7     | 4         | 1.17%   |
| 5.12    | 4         | 1.17%   |
| 6.2     | 3         | 0.88%   |
| 4.12    | 2         | 0.59%   |
| 3.10    | 2         | 0.59%   |
| 5.2     | 1         | 0.29%   |
| 4.4     | 1         | 0.29%   |
| 4.14    | 1         | 0.29%   |
| 4.13    | 1         | 0.29%   |
| 4.10    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 306       | 96.23%  |
| i686   | 12        | 3.77%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 159       | 47.6%   |
| KDE5            | 45        | 13.47%  |
| Unknown         | 41        | 12.28%  |
| X-Cinnamon      | 27        | 8.08%   |
| XFCE            | 16        | 4.79%   |
| KDE             | 11        | 3.29%   |
| LXQt            | 6         | 1.8%    |
| Pantheon        | 5         | 1.5%    |
| MATE            | 5         | 1.5%    |
| Cinnamon        | 5         | 1.5%    |
| i3              | 4         | 1.2%    |
| Unity           | 3         | 0.9%    |
| KDE4            | 2         | 0.6%    |
| GNOME Classic   | 2         | 0.6%    |
| Budgie          | 2         | 0.6%    |
| GNOME Flashback | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 259       | 80.19%  |
| Wayland | 39        | 12.07%  |
| Unknown | 22        | 6.81%   |
| Tty     | 3         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 172       | 52.6%   |
| GDM     | 42        | 12.84%  |
| SDDM    | 38        | 11.62%  |
| LightDM | 30        | 9.17%   |
| GDM3    | 30        | 9.17%   |
| TDM     | 12        | 3.67%   |
| KDM     | 2         | 0.61%   |
| SLiM    | 1         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IE   | 154       | 47.09%  |
| en_US   | 55        | 16.82%  |
| en_GB   | 55        | 16.82%  |
| Unknown | 35        | 10.7%   |
| pl_PL   | 12        | 3.67%   |
| en_CA   | 2         | 0.61%   |
| bg_BG   | 2         | 0.61%   |
| zh_CN   | 1         | 0.31%   |
| pt_PT   | 1         | 0.31%   |
| lt_LT   | 1         | 0.31%   |
| it_IT   | 1         | 0.31%   |
| ga_IE   | 1         | 0.31%   |
| fr_FR   | 1         | 0.31%   |
| fr_BE   | 1         | 0.31%   |
| es_ES   | 1         | 0.31%   |
| en_ZA   | 1         | 0.31%   |
| en_IN   | 1         | 0.31%   |
| en_DE   | 1         | 0.31%   |
| C       | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 172       | 53.42%  |
| BIOS | 150       | 46.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 253       | 78.57%  |
| Btrfs               | 27        | 8.39%   |
| Overlay             | 19        | 5.9%    |
| Unknown             | 14        | 4.35%   |
| Xfs                 | 5         | 1.55%   |
| Zfs                 | 3         | 0.93%   |
| Fuse.fuse-overlayfs | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 181       | 56.04%  |
| GPT     | 112       | 34.67%  |
| MBR     | 30        | 9.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 284       | 88.47%  |
| Yes       | 37        | 11.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 242       | 75.39%  |
| Yes       | 79        | 24.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 77        | 24.21%  |
| Lenovo              | 71        | 22.33%  |
| Hewlett-Packard     | 44        | 13.84%  |
| ASUSTek Computer    | 24        | 7.55%   |
| Acer                | 22        | 6.92%   |
| Toshiba             | 12        | 3.77%   |
| Apple               | 9         | 2.83%   |
| Samsung Electronics | 6         | 1.89%   |
| TUXEDO              | 4         | 1.26%   |
| Timi                | 4         | 1.26%   |
| PC Specialist       | 4         | 1.26%   |
| MSI                 | 4         | 1.26%   |
| Medion              | 4         | 1.26%   |
| Valve               | 3         | 0.94%   |
| Notebook            | 3         | 0.94%   |
| Chuwi               | 3         | 0.94%   |
| System76            | 2         | 0.63%   |
| HUAWEI              | 2         | 0.63%   |
| Fujitsu Siemens     | 2         | 0.63%   |
| Entroware           | 2         | 0.63%   |
| eMachines           | 2         | 0.63%   |
| Star Labs           | 1         | 0.31%   |
| Sony                | 1         | 0.31%   |
| SLIMBOOK            | 1         | 0.31%   |
| Schenker            | 1         | 0.31%   |
| Packard Bell        | 1         | 0.31%   |
| Microtech           | 1         | 0.31%   |
| Jumper              | 1         | 0.31%   |
| Google              | 1         | 0.31%   |
| Gigabyte Technology | 1         | 0.31%   |
| Framework           | 1         | 0.31%   |
| Dynabook            | 1         | 0.31%   |
| AVITA               | 1         | 0.31%   |
| Alienware           | 1         | 0.31%   |
| Advent              | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Dell Latitude 7420                | 6         | 1.89%   |
| Valve Jupiter                     | 3         | 0.94%   |
| Lenovo V145-15AST 81MT            | 3         | 0.94%   |
| Dell Latitude E7240               | 3         | 0.94%   |
| Dell Inspiron 13-5378             | 3         | 0.94%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.63%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.63%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.63%   |
| HP Pavilion g6                    | 2         | 0.63%   |
| HP OMEN by Laptop 15-dc0xxx       | 2         | 0.63%   |
| HP Notebook                       | 2         | 0.63%   |
| Dell XPS 9320                     | 2         | 0.63%   |
| Dell XPS 13 9310                  | 2         | 0.63%   |
| Dell XPS 13 9300                  | 2         | 0.63%   |
| Dell XPS 13 7390                  | 2         | 0.63%   |
| Dell Precision 5550               | 2         | 0.63%   |
| Dell Latitude E6230               | 2         | 0.63%   |
| ASUS X501A1                       | 2         | 0.63%   |
| Apple MacBook6,1                  | 2         | 0.63%   |
| Acer Aspire F5-573G               | 2         | 0.63%   |
| Acer Aspire E5-575G               | 2         | 0.63%   |
| TUXEDO InfinityBook Pro 15 v5     | 1         | 0.31%   |
| TUXEDO InfinityBook Pro 14 Gen6   | 1         | 0.31%   |
| Toshiba TECRA R850                | 1         | 0.31%   |
| Toshiba TECRA M4                  | 1         | 0.31%   |
| Toshiba Satellite Pro S500        | 1         | 0.31%   |
| Toshiba Satellite Pro R50-B       | 1         | 0.31%   |
| Toshiba Satellite Pro C660        | 1         | 0.31%   |
| Toshiba Satellite L500            | 1         | 0.31%   |
| Toshiba Satellite L50-C           | 1         | 0.31%   |
| Toshiba Satellite L50-B           | 1         | 0.31%   |
| Toshiba Satellite C50D-A-138      | 1         | 0.31%   |
| Toshiba Satellite C50-B           | 1         | 0.31%   |
| Toshiba Satellite A300            | 1         | 0.31%   |
| Toshiba PORTEGE R830              | 1         | 0.31%   |
| Timi TM1709                       | 1         | 0.31%   |
| Timi TM1703                       | 1         | 0.31%   |
| Timi TM1607                       | 1         | 0.31%   |
| Timi A35S                         | 1         | 0.31%   |
| System76 Galago Pro               | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 39        | 12.26%  |
| Dell Latitude         | 36        | 11.32%  |
| Dell Inspiron         | 16        | 5.03%   |
| Acer Aspire           | 16        | 5.03%   |
| Lenovo IdeaPad        | 15        | 4.72%   |
| HP EliteBook          | 12        | 3.77%   |
| Dell XPS              | 12        | 3.77%   |
| HP Pavilion           | 11        | 3.46%   |
| Toshiba Satellite     | 9         | 2.83%   |
| Dell Precision        | 6         | 1.89%   |
| Valve Jupiter         | 3         | 0.94%   |
| Lenovo V145-15AST     | 3         | 0.94%   |
| Lenovo ThinkBook      | 3         | 0.94%   |
| HP ProBook            | 3         | 0.94%   |
| HP Presario           | 3         | 0.94%   |
| HP Laptop             | 3         | 0.94%   |
| ASUS ZenBook          | 3         | 0.94%   |
| ASUS ROG              | 3         | 0.94%   |
| Apple MacBookPro5     | 3         | 0.94%   |
| TUXEDO Pulse          | 2         | 0.63%   |
| TUXEDO InfinityBook   | 2         | 0.63%   |
| Toshiba TECRA         | 2         | 0.63%   |
| HP OMEN               | 2         | 0.63%   |
| HP Notebook           | 2         | 0.63%   |
| Fujitsu Siemens AMILO | 2         | 0.63%   |
| Dell Vostro           | 2         | 0.63%   |
| ASUS X501A1           | 2         | 0.63%   |
| ASUS TUF              | 2         | 0.63%   |
| Apple MacBook6        | 2         | 0.63%   |
| Acer Nitro            | 2         | 0.63%   |
| Toshiba PORTEGE       | 1         | 0.31%   |
| Timi TM1709           | 1         | 0.31%   |
| Timi TM1703           | 1         | 0.31%   |
| Timi TM1607           | 1         | 0.31%   |
| Timi A35S             | 1         | 0.31%   |
| System76 Galago       | 1         | 0.31%   |
| System76 Bonobo       | 1         | 0.31%   |
| Star Labs Lite        | 1         | 0.31%   |
| Sony VPCCB35FG        | 1         | 0.31%   |
| SLIMBOOK PROX15       | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 39        | 12.26%  |
| 2019 | 31        | 9.75%   |
| 2017 | 26        | 8.18%   |
| 2013 | 25        | 7.86%   |
| 2021 | 24        | 7.55%   |
| 2018 | 23        | 7.23%   |
| 2012 | 22        | 6.92%   |
| 2016 | 20        | 6.29%   |
| 2011 | 20        | 6.29%   |
| 2022 | 14        | 4.4%    |
| 2015 | 14        | 4.4%    |
| 2009 | 14        | 4.4%    |
| 2010 | 13        | 4.09%   |
| 2008 | 12        | 3.77%   |
| 2014 | 9         | 2.83%   |
| 2007 | 7         | 2.2%    |
| 2006 | 3         | 0.94%   |
| 2005 | 1         | 0.31%   |
| 2003 | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 318       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 278       | 86.34%  |
| Enabled  | 44        | 13.66%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 316       | 99.37%  |
| Yes  | 2         | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 94        | 29.1%   |
| 16.01-24.0  | 63        | 19.5%   |
| 3.01-4.0    | 58        | 17.96%  |
| 8.01-16.0   | 52        | 16.1%   |
| 32.01-64.0  | 29        | 8.98%   |
| 1.01-2.0    | 12        | 3.72%   |
| 2.01-3.0    | 5         | 1.55%   |
| 24.01-32.0  | 4         | 1.24%   |
| 64.01-256.0 | 3         | 0.93%   |
| 0.51-1.0    | 2         | 0.62%   |
| 0.01-0.5    | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 110       | 31.34%  |
| 2.01-3.0   | 92        | 26.21%  |
| 3.01-4.0   | 56        | 15.95%  |
| 4.01-8.0   | 55        | 15.67%  |
| 0.51-1.0   | 22        | 6.27%   |
| 8.01-16.0  | 11        | 3.13%   |
| 16.01-24.0 | 3         | 0.85%   |
| 0.01-0.5   | 2         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 239       | 72.87%  |
| 2      | 76        | 23.17%  |
| 3      | 11        | 3.35%   |
| 0      | 2         | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 213       | 66.36%  |
| Yes       | 108       | 33.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 258       | 80.37%  |
| No        | 63        | 19.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 315       | 98.75%  |
| No        | 4         | 1.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 252       | 78.5%   |
| No        | 69        | 21.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ireland | 318       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dublin              | 179       | 54.91%  |
| Cork                | 22        | 6.75%   |
| Galway              | 16        | 4.91%   |
| Limerick            | 11        | 3.37%   |
| Naas                | 7         | 2.15%   |
| Drogheda            | 6         | 1.84%   |
| Ennis               | 5         | 1.53%   |
| Navan               | 4         | 1.23%   |
| Enniscorthy         | 4         | 1.23%   |
| Wexford             | 3         | 0.92%   |
| Lucan               | 3         | 0.92%   |
| Dún Laoghaire      | 3         | 0.92%   |
| Westport            | 2         | 0.61%   |
| Waterford           | 2         | 0.61%   |
| Portlaoise          | 2         | 0.61%   |
| Nenagh              | 2         | 0.61%   |
| Loughrea            | 2         | 0.61%   |
| Kilkenny            | 2         | 0.61%   |
| Donegal             | 2         | 0.61%   |
| Cobh                | 2         | 0.61%   |
| Clonakilty          | 2         | 0.61%   |
| Clane               | 2         | 0.61%   |
| Athlone             | 2         | 0.61%   |
| Youghal             | 1         | 0.31%   |
| Wicklow             | 1         | 0.31%   |
| Tullow              | 1         | 0.31%   |
| Tullamore           | 1         | 0.31%   |
| Tuam                | 1         | 0.31%   |
| Tobercurry          | 1         | 0.31%   |
| Sligo               | 1         | 0.31%   |
| Slane               | 1         | 0.31%   |
| Scarriff            | 1         | 0.31%   |
| Santry              | 1         | 0.31%   |
| Oughterard          | 1         | 0.31%   |
| Newmarket on Fergus | 1         | 0.31%   |
| Newcastle           | 1         | 0.31%   |
| New Ross            | 1         | 0.31%   |
| Monaghan            | 1         | 0.31%   |
| Midleton            | 1         | 0.31%   |
| Meath               | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 79        | 107    | 19.9%   |
| WDC                       | 49        | 58     | 12.34%  |
| Seagate                   | 34        | 43     | 8.56%   |
| Unknown                   | 29        | 39     | 7.3%    |
| Toshiba                   | 27        | 32     | 6.8%    |
| SanDisk                   | 25        | 28     | 6.3%    |
| Hitachi                   | 22        | 25     | 5.54%   |
| Crucial                   | 15        | 22     | 3.78%   |
| Micron Technology         | 11        | 12     | 2.77%   |
| KIOXIA                    | 11        | 12     | 2.77%   |
| Kingston                  | 11        | 13     | 2.77%   |
| Intel                     | 11        | 14     | 2.77%   |
| SK hynix                  | 10        | 10     | 2.52%   |
| HGST                      | 10        | 11     | 2.52%   |
| Fujitsu                   | 6         | 7      | 1.51%   |
| PNY                       | 3         | 3      | 0.76%   |
| LITEONIT                  | 3         | 3      | 0.76%   |
| LITEON                    | 3         | 3      | 0.76%   |
| KingSpec                  | 3         | 3      | 0.76%   |
| Silicon Motion            | 2         | 3      | 0.5%    |
| FORESEE                   | 2         | 2      | 0.5%    |
| Apple                     | 2         | 2      | 0.5%    |
| A-DATA Technology         | 2         | 2      | 0.5%    |
| Zheino                    | 1         | 1      | 0.25%   |
| W800S                     | 1         | 2      | 0.25%   |
| Verbatim                  | 1         | 1      | 0.25%   |
| Union Memory              | 1         | 1      | 0.25%   |
| Star                      | 1         | 1      | 0.25%   |
| SPCC                      | 1         | 1      | 0.25%   |
| ShanDianZhe               | 1         | 1      | 0.25%   |
| SABRENT                   | 1         | 2      | 0.25%   |
| QNAP                      | 1         | 1      | 0.25%   |
| Plextor                   | 1         | 1      | 0.25%   |
| Phison Electronics        | 1         | 1      | 0.25%   |
| Phison                    | 1         | 1      | 0.25%   |
| Patriot                   | 1         | 1      | 0.25%   |
| OCZ                       | 1         | 1      | 0.25%   |
| O2 Micro                  | 1         | 2      | 0.25%   |
| Micron/Crucial Technology | 1         | 1      | 0.25%   |
| LaCie                     | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 9         | 2.18%   |
| SanDisk NVMe SSD Drive 512GB           | 6         | 1.45%   |
| KIOXIA KBG40ZNS512G NVMe 512GB         | 6         | 1.45%   |
| Kingston SA400S37480G 480GB SSD        | 5         | 1.21%   |
| Unknown MMC Card  64GB                 | 4         | 0.97%   |
| Unknown MMC Card  32GB                 | 4         | 0.97%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 0.97%   |
| Samsung SSD 860 EVO 500GB              | 4         | 0.97%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 4         | 0.97%   |
| Hitachi HTS723232A7A364 320GB          | 4         | 0.97%   |
| HGST HTS545050A7E680 500GB             | 4         | 0.97%   |
| Crucial CT1000MX500SSD1 1TB            | 4         | 0.97%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 3         | 0.73%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.73%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.73%   |
| Samsung NVMe SSD Drive 512GB           | 3         | 0.73%   |
| Samsung NVMe SSD Drive 500GB           | 3         | 0.73%   |
| PNY CS900 120GB SSD                    | 3         | 0.73%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.73%   |
| Crucial M4-CT128M4SSD2 128GB           | 3         | 0.73%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD         | 2         | 0.48%   |
| WDC WD10SPZX-75Z10T2 1TB               | 2         | 0.48%   |
| WDC WD10JPVX-00JC3T0 1TB               | 2         | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB               | 2         | 0.48%   |
| WDC PC SN530 NVMe 512GB                | 2         | 0.48%   |
| Unknown SL16G  16GB                    | 2         | 0.48%   |
| Unknown SD/MMC/MS PRO 64GB             | 2         | 0.48%   |
| Unknown HBG4a2  32GB                   | 2         | 0.48%   |
| Toshiba MQ04ABF100 1TB                 | 2         | 0.48%   |
| Toshiba KBG30ZMS256G NVMe 256GB        | 2         | 0.48%   |
| SK hynix NVMe SSD Drive 2TB            | 2         | 0.48%   |
| Seagate ST9500420ASG 500GB             | 2         | 0.48%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 2         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.48%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.48%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 2         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.48%   |
| SanDisk X400 2.5 7MM 256GB SSD         | 2         | 0.48%   |
| SanDisk SD5SG2128G1052E 128GB SSD      | 2         | 0.48%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 42     | 26.19%  |
| WDC                 | 31        | 34     | 24.6%   |
| Hitachi             | 22        | 25     | 17.46%  |
| Toshiba             | 15        | 16     | 11.9%   |
| HGST                | 10        | 11     | 7.94%   |
| Fujitsu             | 6         | 7      | 4.76%   |
| Samsung Electronics | 3         | 4      | 2.38%   |
| Unknown             | 2         | 2      | 1.59%   |
| SABRENT             | 1         | 2      | 0.79%   |
| QNAP                | 1         | 1      | 0.79%   |
| LaCie               | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 42     | 29.17%  |
| SanDisk             | 15        | 15     | 12.5%   |
| Crucial             | 14        | 21     | 11.67%  |
| Kingston            | 11        | 13     | 9.17%   |
| WDC                 | 6         | 9      | 5%      |
| Toshiba             | 3         | 5      | 2.5%    |
| PNY                 | 3         | 3      | 2.5%    |
| LITEONIT            | 3         | 3      | 2.5%    |
| KingSpec            | 3         | 3      | 2.5%    |
| SK hynix            | 2         | 2      | 1.67%   |
| Micron Technology   | 2         | 2      | 1.67%   |
| LITEON              | 2         | 2      | 1.67%   |
| Intel               | 2         | 2      | 1.67%   |
| FORESEE             | 2         | 2      | 1.67%   |
| Zheino              | 1         | 1      | 0.83%   |
| W800S               | 1         | 2      | 0.83%   |
| Verbatim            | 1         | 1      | 0.83%   |
| Star                | 1         | 1      | 0.83%   |
| SPCC                | 1         | 1      | 0.83%   |
| Plextor             | 1         | 1      | 0.83%   |
| Patriot             | 1         | 1      | 0.83%   |
| OCZ                 | 1         | 1      | 0.83%   |
| JMicron Technology  | 1         | 1      | 0.83%   |
| Integral            | 1         | 1      | 0.83%   |
| GOODRAM             | 1         | 1      | 0.83%   |
| faspeed             | 1         | 1      | 0.83%   |
| Emtec               | 1         | 2      | 0.83%   |
| Dogfish             | 1         | 1      | 0.83%   |
| China               | 1         | 5      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |
| A-DATA Technology   | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 119       | 146    | 31.48%  |
| NVMe    | 117       | 155    | 30.95%  |
| SSD     | 111       | 147    | 29.37%  |
| MMC     | 26        | 36     | 6.88%   |
| Unknown | 5         | 5      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 210       | 286    | 58.01%  |
| NVMe | 117       | 155    | 32.32%  |
| MMC  | 26        | 36     | 7.18%   |
| SAS  | 9         | 12     | 2.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 156       | 201    | 68.72%  |
| 0.51-1.0   | 64        | 80     | 28.19%  |
| 1.01-2.0   | 4         | 7      | 1.76%   |
| 4.01-10.0  | 2         | 4      | 0.88%   |
| 3.01-4.0   | 1         | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 97        | 29.57%  |
| 101-250        | 92        | 28.05%  |
| 501-1000       | 39        | 11.89%  |
| 51-100         | 29        | 8.84%   |
| 1-20           | 26        | 7.93%   |
| 1001-2000      | 18        | 5.49%   |
| 21-50          | 11        | 3.35%   |
| Unknown        | 10        | 3.05%   |
| More than 3000 | 4         | 1.22%   |
| 2001-3000      | 2         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 135       | 39.13%  |
| 21-50          | 57        | 16.52%  |
| 101-250        | 56        | 16.23%  |
| 51-100         | 47        | 13.62%  |
| 251-500        | 22        | 6.38%   |
| 501-1000       | 13        | 3.77%   |
| Unknown        | 10        | 2.9%    |
| 1001-2000      | 4         | 1.16%   |
| More than 3000 | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 11.11%  |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 5.56%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 5.56%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 5.56%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 5.56%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 5.56%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 5.56%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 5.56%   |
| JMicron Technology Generic 500GB               | 1         | 1      | 5.56%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 5.56%   |
| Hitachi HTS545032A7E380 320GB                  | 1         | 1      | 5.56%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 2      | 5.56%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 5.56%   |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 5.56%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 5.56%   |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 8      | 38.89%  |
| Toshiba             | 3         | 3      | 16.67%  |
| WDC                 | 1         | 1      | 5.56%   |
| Seagate             | 1         | 1      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| JMicron Technology  | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 8      | 46.67%  |
| Toshiba             | 3         | 3      | 20%     |
| WDC                 | 1         | 1      | 6.67%   |
| Seagate             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |
| Fujitsu             | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 16     | 80%     |
| SSD  | 3         | 3      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 200       | 306    | 59.7%   |
| Works    | 120       | 163    | 35.82%  |
| Malfunc  | 14        | 19     | 4.18%   |
| Failed   | 1         | 1      | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 210       | 56.15%  |
| Samsung Electronics          | 43        | 11.5%   |
| AMD                          | 39        | 10.43%  |
| SanDisk                      | 23        | 6.15%   |
| Toshiba America Info Systems | 10        | 2.67%   |
| KIOXIA                       | 10        | 2.67%   |
| Micron Technology            | 9         | 2.41%   |
| SK hynix                     | 8         | 2.14%   |
| Nvidia                       | 8         | 2.14%   |
| Union Memory (Shenzhen)      | 2         | 0.53%   |
| Silicon Motion               | 2         | 0.53%   |
| Phison Electronics           | 2         | 0.53%   |
| Micron/Crucial Technology    | 2         | 0.53%   |
| Silicon Image                | 1         | 0.27%   |
| O2 Micro                     | 1         | 0.27%   |
| Lite-On Technology           | 1         | 0.27%   |
| Kingston Technology Company  | 1         | 0.27%   |
| ADATA Technology             | 1         | 0.27%   |
| Adaptec                      | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 8.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 34        | 8.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 5.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 4.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 3.5%    |
| Samsung NVMe SSD Controller 980                                                | 13        | 3.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 2.5%    |
| Micron NVMe Storage Controller                                                 | 9         | 2.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 2.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 8         | 2%      |
| KIOXIA NVMe SSD Controller BG4                                                 | 8         | 2%      |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.5%    |
| Nvidia MCP79 AHCI Controller                                                   | 5         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.25%   |
| SanDisk PC SN520 NVMe SSD                                                      | 4         | 1%      |
| SanDisk Non-Volatile memory controller                                         | 4         | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1%      |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1%      |
| Intel SSD 660P Series                                                          | 4         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1%      |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 0.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 214       | 55.87%  |
| NVMe | 118       | 30.81%  |
| RAID | 28        | 7.31%   |
| IDE  | 22        | 5.74%   |
| SCSI | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 257       | 80.56%  |
| AMD    | 62        | 19.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 10        | 3.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 2.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.57%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.25%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.25%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.25%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.94%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.94%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.94%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.94%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.94%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.94%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.94%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.94%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.94%   |
| AMD Custom APU 0405                           | 3         | 0.94%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 0.94%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.63%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.63%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.63%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.63%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 70        | 21.94%  |
| Intel Core i5           | 69        | 21.63%  |
| Other                   | 38        | 11.91%  |
| Intel Core i3           | 21        | 6.58%   |
| Intel Celeron           | 20        | 6.27%   |
| Intel Core 2 Duo        | 18        | 5.64%   |
| AMD Ryzen 7             | 12        | 3.76%   |
| AMD Ryzen 5             | 12        | 3.76%   |
| Intel Atom              | 6         | 1.88%   |
| Intel Pentium           | 5         | 1.57%   |
| AMD A8                  | 4         | 1.25%   |
| Intel Core 2            | 3         | 0.94%   |
| AMD Ryzen 9             | 3         | 0.94%   |
| AMD Ryzen 7 PRO         | 3         | 0.94%   |
| AMD E1                  | 3         | 0.94%   |
| Intel Pentium Dual-Core | 2         | 0.63%   |
| Intel Core i9           | 2         | 0.63%   |
| Intel Celeron Dual-Core | 2         | 0.63%   |
| AMD Ryzen 5 PRO         | 2         | 0.63%   |
| AMD E2                  | 2         | 0.63%   |
| AMD A10                 | 2         | 0.63%   |
| Intel Pentium Silver    | 1         | 0.31%   |
| Intel Pentium M         | 1         | 0.31%   |
| Intel Pentium III       | 1         | 0.31%   |
| Intel Genuine           | 1         | 0.31%   |
| Intel Core m7           | 1         | 0.31%   |
| Intel Core m5           | 1         | 0.31%   |
| Intel Core m3           | 1         | 0.31%   |
| Intel Core 2 Extreme    | 1         | 0.31%   |
| Intel Celeron M         | 1         | 0.31%   |
| AMD Turion 64 X2 Mobile | 1         | 0.31%   |
| AMD Sempron             | 1         | 0.31%   |
| AMD Ryzen 3 PRO         | 1         | 0.31%   |
| AMD Ryzen 3             | 1         | 0.31%   |
| AMD PRO A10             | 1         | 0.31%   |
| AMD Phenom II           | 1         | 0.31%   |
| AMD FX                  | 1         | 0.31%   |
| AMD E                   | 1         | 0.31%   |
| AMD Athlon 64 X2        | 1         | 0.31%   |
| AMD Athlon              | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 154       | 48.28%  |
| 4      | 108       | 33.86%  |
| 8      | 20        | 6.27%   |
| 6      | 18        | 5.64%   |
| 1      | 10        | 3.13%   |
| 14     | 5         | 1.57%   |
| 12     | 2         | 0.63%   |
| 10     | 1         | 0.31%   |
| 3      | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 318       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 234       | 73.58%  |
| 1      | 84        | 26.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 309       | 96.56%  |
| Unknown        | 8         | 2.5%    |
| 32-bit         | 3         | 0.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 23.93%  |
| 0x306a9    | 18        | 5.52%   |
| 0x806ec    | 16        | 4.91%   |
| 0x806e9    | 15        | 4.6%    |
| 0x806c1    | 13        | 3.99%   |
| 0x206a7    | 12        | 3.68%   |
| 0x1067a    | 12        | 3.68%   |
| 0x806ea    | 11        | 3.37%   |
| 0x40651    | 10        | 3.07%   |
| 0x406e3    | 8         | 2.45%   |
| 0xa0652    | 7         | 2.15%   |
| 0x906ea    | 7         | 2.15%   |
| 0x306d4    | 6         | 1.84%   |
| 0x0a50000c | 6         | 1.84%   |
| 0x906e9    | 5         | 1.53%   |
| 0x406c4    | 5         | 1.53%   |
| 0x306c3    | 5         | 1.53%   |
| 0x30678    | 5         | 1.53%   |
| 0x20655    | 5         | 1.53%   |
| 0x10676    | 5         | 1.53%   |
| 0x06006705 | 5         | 1.53%   |
| 0x6fd      | 4         | 1.23%   |
| 0x08108102 | 4         | 1.23%   |
| 0x906a3    | 3         | 0.92%   |
| 0x806d1    | 3         | 0.92%   |
| 0x706e5    | 3         | 0.92%   |
| 0x106ca    | 3         | 0.92%   |
| 0x08600106 | 3         | 0.92%   |
| 0x08108109 | 3         | 0.92%   |
| 0x706a8    | 2         | 0.61%   |
| 0x6f6      | 2         | 0.61%   |
| 0x6d8      | 2         | 0.61%   |
| 0x506e3    | 2         | 0.61%   |
| 0x20652    | 2         | 0.61%   |
| 0x08608103 | 2         | 0.61%   |
| 0x08600103 | 2         | 0.61%   |
| 0x07030106 | 2         | 0.61%   |
| 0x0600611a | 2         | 0.61%   |
| 0x06001119 | 2         | 0.61%   |
| 0x05000119 | 2         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 64        | 20.13%  |
| IvyBridge        | 23        | 7.23%   |
| TigerLake        | 20        | 6.29%   |
| SandyBridge      | 19        | 5.97%   |
| Haswell          | 18        | 5.66%   |
| Skylake          | 17        | 5.35%   |
| Penryn           | 17        | 5.35%   |
| Silvermont       | 14        | 4.4%    |
| Westmere         | 11        | 3.46%   |
| Zen 2            | 10        | 3.14%   |
| Core             | 10        | 3.14%   |
| Unknown          | 10        | 3.14%   |
| Excavator        | 9         | 2.83%   |
| Zen+             | 8         | 2.52%   |
| Zen 3            | 8         | 2.52%   |
| IceLake          | 8         | 2.52%   |
| CometLake        | 7         | 2.2%    |
| Broadwell        | 7         | 2.2%    |
| Goldmont plus    | 5         | 1.57%   |
| Zen              | 4         | 1.26%   |
| P6               | 4         | 1.26%   |
| Bobcat           | 4         | 1.26%   |
| Puma             | 3         | 0.94%   |
| K8 Hammer        | 3         | 0.94%   |
| Bonnell          | 3         | 0.94%   |
| Alderlake Hybrid | 3         | 0.94%   |
| Piledriver       | 2         | 0.63%   |
| K10              | 2         | 0.63%   |
| Jaguar           | 2         | 0.63%   |
| Goldmont         | 2         | 0.63%   |
| Nehalem          | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 225       | 57.84%  |
| Nvidia | 97        | 24.94%  |
| AMD    | 67        | 17.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 5.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 4.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 3.98%   |
| Intel HD Graphics 620                                                                    | 15        | 3.73%   |
| Intel UHD Graphics 620                                                                   | 13        | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 2.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.24%   |
| AMD Renoir                                                                               | 9         | 2.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.74%   |
| Intel HD Graphics 630                                                                    | 6         | 1.49%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.49%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.24%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 1.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1%      |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1%      |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 1%      |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.75%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.75%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 3         | 0.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.75%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 3         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 164       | 51.41%  |
| Intel + Nvidia | 58        | 18.18%  |
| 1 x AMD        | 48        | 15.05%  |
| 1 x Nvidia     | 29        | 9.09%   |
| AMD + Nvidia   | 9         | 2.82%   |
| 2 x AMD        | 7         | 2.19%   |
| Intel + AMD    | 3         | 0.94%   |
| 2 x Nvidia     | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 262       | 81.37%  |
| Proprietary | 49        | 15.22%  |
| Unknown     | 11        | 3.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 200       | 61.16%  |
| 0.01-0.5   | 50        | 15.29%  |
| 3.01-4.0   | 25        | 7.65%   |
| 1.01-2.0   | 25        | 7.65%   |
| 0.51-1.0   | 16        | 4.89%   |
| 5.01-6.0   | 5         | 1.53%   |
| 7.01-8.0   | 4         | 1.22%   |
| 2.01-3.0   | 2         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 65        | 17.62%  |
| LG Display              | 56        | 15.18%  |
| BOE                     | 53        | 14.36%  |
| Chimei Innolux          | 35        | 9.49%   |
| Samsung Electronics     | 29        | 7.86%   |
| Dell                    | 22        | 5.96%   |
| Sharp                   | 20        | 5.42%   |
| Lenovo                  | 8         | 2.17%   |
| Chi Mei Optoelectronics | 8         | 2.17%   |
| Apple                   | 8         | 2.17%   |
| ViewSonic               | 7         | 1.9%    |
| PANDA                   | 7         | 1.9%    |
| Hewlett-Packard         | 7         | 1.9%    |
| Goldstar                | 6         | 1.63%   |
| Philips                 | 5         | 1.36%   |
| Acer                    | 4         | 1.08%   |
| LG Philips              | 3         | 0.81%   |
| InfoVision              | 3         | 0.81%   |
| AOC                     | 3         | 0.81%   |
| Valve                   | 2         | 0.54%   |
| MSI                     | 2         | 0.54%   |
| CSO                     | 2         | 0.54%   |
| CPT                     | 2         | 0.54%   |
| BOE Technology Group    | 2         | 0.54%   |
| ___                     | 1         | 0.27%   |
| Unknown                 | 1         | 0.27%   |
| Toshiba                 | 1         | 0.27%   |
| Quanta Display          | 1         | 0.27%   |
| OEM                     | 1         | 0.27%   |
| LGD                     | 1         | 0.27%   |
| Lenovo Group Limited    | 1         | 0.27%   |
| Iiyama                  | 1         | 0.27%   |
| BenQ                    | 1         | 0.27%   |
| Analogix                | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                | 7         | 1.85%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch            | 6         | 1.59%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                    | 6         | 1.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.06%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 4         | 1.06%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 3         | 0.79%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 3         | 0.79%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.79%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 0.79%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 3         | 0.79%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.53%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch              | 2         | 0.53%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.53%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.53%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch | 2         | 0.53%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 2         | 0.53%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 2         | 0.53%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch         | 2         | 0.53%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 2         | 0.53%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 2         | 0.53%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.53%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 2         | 0.53%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch           | 2         | 0.53%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 2         | 0.53%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.53%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 2         | 0.53%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                | 2         | 0.53%   |
| BOE LCD Monitor BOE05DA 1366x768 277x156mm 12.5-inch                 | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 156       | 44.96%  |
| 1366x768 (WXGA)    | 87        | 25.07%  |
| 1600x900 (HD+)     | 15        | 4.32%   |
| 3840x2160 (4K)     | 13        | 3.75%   |
| 1280x800 (WXGA)    | 13        | 3.75%   |
| 2560x1440 (QHD)    | 12        | 3.46%   |
| 1920x1200 (WUXGA)  | 10        | 2.88%   |
| 1440x900 (WXGA+)   | 9         | 2.59%   |
| 3440x1440          | 4         | 1.15%   |
| 2560x1600          | 4         | 1.15%   |
| 800x1280           | 3         | 0.86%   |
| 3840x2400          | 3         | 0.86%   |
| 1024x600           | 3         | 0.86%   |
| 3456x2160          | 2         | 0.58%   |
| 3200x1800 (QHD+)   | 2         | 0.58%   |
| 1600x1200          | 2         | 0.58%   |
| 1360x768           | 2         | 0.58%   |
| 2880x1800          | 1         | 0.29%   |
| 2560x1080          | 1         | 0.29%   |
| 2256x1504          | 1         | 0.29%   |
| 2160x1440          | 1         | 0.29%   |
| 1920x540           | 1         | 0.29%   |
| 1680x1050 (WSXGA+) | 1         | 0.29%   |
| 1280x1024 (SXGA)   | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 150       | 40.11%  |
| 14      | 54        | 14.44%  |
| 13      | 44        | 11.76%  |
| 27      | 23        | 6.15%   |
| 17      | 18        | 4.81%   |
| 12      | 16        | 4.28%   |
| 24      | 13        | 3.48%   |
| 21      | 12        | 3.21%   |
| 23      | 9         | 2.41%   |
| Unknown | 9         | 2.41%   |
| 34      | 5         | 1.34%   |
| 11      | 5         | 1.34%   |
| 10      | 3         | 0.8%    |
| 31      | 2         | 0.53%   |
| 29      | 2         | 0.53%   |
| 18      | 2         | 0.53%   |
| 7       | 2         | 0.53%   |
| 72      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 25      | 1         | 0.27%   |
| 20      | 1         | 0.27%   |
| 16      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 215       | 58.11%  |
| 201-300     | 53        | 14.32%  |
| 501-600     | 39        | 10.54%  |
| 351-400     | 22        | 5.95%   |
| 401-500     | 15        | 4.05%   |
| Unknown     | 9         | 2.43%   |
| 601-700     | 8         | 2.16%   |
| 701-800     | 5         | 1.35%   |
| 1-100       | 2         | 0.54%   |
| 801-900     | 1         | 0.27%   |
| 1501-2000   | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 258       | 80.88%  |
| 16/10   | 39        | 12.23%  |
| Unknown | 7         | 2.19%   |
| 21/9    | 6         | 1.88%   |
| 3/2     | 3         | 0.94%   |
| 4/3     | 2         | 0.63%   |
| 0.67    | 2         | 0.63%   |
| 5/4     | 1         | 0.31%   |
| 0.62    | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 148       | 39.68%  |
| 81-90          | 73        | 19.57%  |
| 201-250        | 29        | 7.77%   |
| 71-80          | 26        | 6.97%   |
| 301-350        | 24        | 6.43%   |
| 61-70          | 15        | 4.02%   |
| 121-130        | 14        | 3.75%   |
| Unknown        | 9         | 2.41%   |
| 351-500        | 8         | 2.14%   |
| 51-60          | 5         | 1.34%   |
| 251-300        | 4         | 1.07%   |
| 41-50          | 3         | 0.8%    |
| 141-150        | 3         | 0.8%    |
| 131-140        | 3         | 0.8%    |
| 1-40           | 2         | 0.54%   |
| 151-200        | 2         | 0.54%   |
| 111-120        | 2         | 0.54%   |
| More than 1000 | 1         | 0.27%   |
| 501-1000       | 1         | 0.27%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 157       | 43.61%  |
| 101-120       | 99        | 27.5%   |
| 51-100        | 51        | 14.17%  |
| 161-240       | 30        | 8.33%   |
| More than 240 | 12        | 3.33%   |
| Unknown       | 9         | 2.5%    |
| 1-50          | 2         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 247       | 76%     |
| 2     | 54        | 16.62%  |
| 3     | 12        | 3.69%   |
| 0     | 11        | 3.38%   |
| 4     | 1         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 184       | 35.8%   |
| Realtek Semiconductor             | 158       | 30.74%  |
| Qualcomm Atheros                  | 60        | 11.67%  |
| Broadcom                          | 36        | 7%      |
| Broadcom Limited                  | 9         | 1.75%   |
| Nvidia                            | 8         | 1.56%   |
| MediaTek                          | 8         | 1.56%   |
| Ralink Technology                 | 5         | 0.97%   |
| Marvell Technology Group          | 5         | 0.97%   |
| Ericsson Business Mobile Networks | 5         | 0.97%   |
| ASIX Electronics                  | 5         | 0.97%   |
| Samsung Electronics               | 4         | 0.78%   |
| Lenovo                            | 4         | 0.78%   |
| Ralink                            | 3         | 0.58%   |
| Xiaomi                            | 2         | 0.39%   |
| Qualcomm                          | 2         | 0.39%   |
| Dell                              | 2         | 0.39%   |
| Xilinx                            | 1         | 0.19%   |
| TP-Link                           | 1         | 0.19%   |
| Toshiba                           | 1         | 0.19%   |
| T & A Mobile Phones               | 1         | 0.19%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.19%   |
| NetGear                           | 1         | 0.19%   |
| Microsoft                         | 1         | 0.19%   |
| LSI                               | 1         | 0.19%   |
| ICS Advent                        | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| DisplayLink                       | 1         | 0.19%   |
| Bose                              | 1         | 0.19%   |
| Apple                             | 1         | 0.19%   |
| 3Com                              | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 14.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 4.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 3.23%   |
| Intel Wi-Fi 6 AX200                                               | 20        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 3.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 16        | 2.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 2.42%   |
| Intel Wireless 8265 / 8275                                        | 14        | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 2.1%    |
| Intel Wireless 7260                                               | 13        | 2.1%    |
| Intel Wi-Fi 6 AX201                                               | 13        | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.29%   |
| Intel Wireless 8260                                               | 8         | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.13%   |
| Intel Wireless 3165                                               | 7         | 1.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 1.13%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.97%   |
| Intel Wireless 7265                                               | 6         | 0.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.81%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 179       | 54.24%  |
| Qualcomm Atheros      | 52        | 15.76%  |
| Realtek Semiconductor | 44        | 13.33%  |
| Broadcom              | 29        | 8.79%   |
| MediaTek              | 8         | 2.42%   |
| Ralink Technology     | 5         | 1.52%   |
| Ralink                | 3         | 0.91%   |
| Broadcom Limited      | 3         | 0.91%   |
| Qualcomm              | 2         | 0.61%   |
| Dell                  | 2         | 0.61%   |
| TP-Link               | 1         | 0.3%    |
| NetGear               | 1         | 0.3%    |
| Apple                 | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 20        | 6.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 4.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 4.52%   |
| Intel Wireless 8265 / 8275                                              | 14        | 4.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 3.92%   |
| Intel Wireless 7260                                                     | 13        | 3.92%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 3.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.41%   |
| Intel Wireless 8260                                                     | 8         | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.11%   |
| Intel Wireless 3165                                                     | 7         | 2.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 2.11%   |
| Intel Wireless 7265                                                     | 6         | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1.81%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.51%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.2%    |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.2%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.9%    |
| Intel Wireless 3160                                                     | 3         | 0.9%    |
| Intel WiFi Link 5100                                                    | 3         | 0.9%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.9%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.9%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.6%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.6%    |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 141       | 51.65%  |
| Intel                         | 65        | 23.81%  |
| Qualcomm Atheros              | 15        | 5.49%   |
| Broadcom                      | 10        | 3.66%   |
| Nvidia                        | 8         | 2.93%   |
| Broadcom Limited              | 7         | 2.56%   |
| Marvell Technology Group      | 5         | 1.83%   |
| ASIX Electronics              | 5         | 1.83%   |
| Samsung Electronics           | 4         | 1.47%   |
| Lenovo                        | 4         | 1.47%   |
| Xiaomi                        | 2         | 0.73%   |
| Xilinx                        | 1         | 0.37%   |
| T & A Mobile Phones           | 1         | 0.37%   |
| OnePlus Technology (Shenzhen) | 1         | 0.37%   |
| Microsoft                     | 1         | 0.37%   |
| ICS Advent                    | 1         | 0.37%   |
| DisplayLink                   | 1         | 0.37%   |
| 3Com                          | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 32.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 10.51%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 7.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 6.88%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 2.9%    |
| Nvidia MCP79 Ethernet                                             | 6         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.09%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.72%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.72%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.72%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.72%   |
| Xilinx Ethernet controller                                        | 1         | 0.36%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.36%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.36%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 315       | 53.94%  |
| Ethernet | 258       | 44.18%  |
| Modem    | 11        | 1.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 255       | 76.58%  |
| Ethernet | 78        | 23.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 227       | 71.16%  |
| 1     | 87        | 27.27%  |
| 0     | 3         | 0.94%   |
| 3     | 2         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 277       | 85.76%  |
| Yes  | 46        | 14.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 138       | 54.55%  |
| Realtek Semiconductor           | 23        | 9.09%   |
| IMC Networks                    | 16        | 6.32%   |
| Qualcomm Atheros Communications | 15        | 5.93%   |
| Broadcom                        | 15        | 5.93%   |
| Lite-On Technology              | 13        | 5.14%   |
| Apple                           | 7         | 2.77%   |
| Dell                            | 6         | 2.37%   |
| Hewlett-Packard                 | 5         | 1.98%   |
| Toshiba                         | 4         | 1.58%   |
| Foxconn / Hon Hai               | 4         | 1.58%   |
| Realtek                         | 2         | 0.79%   |
| Cambridge Silicon Radio         | 2         | 0.79%   |
| Ralink                          | 1         | 0.4%    |
| Foxconn International           | 1         | 0.4%    |
| ASUSTek Computer                | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 55        | 21.74%  |
| Intel AX201 Bluetooth                               | 27        | 10.67%  |
| Intel AX200 Bluetooth                               | 19        | 7.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 6.72%   |
| Realtek Bluetooth Radio                             | 15        | 5.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 3.56%   |
| IMC Networks Bluetooth Radio                        | 8         | 3.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 2.37%   |
| Intel AX210 Bluetooth                               | 6         | 2.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 2.37%   |
| Apple Bluetooth Host Controller                     | 5         | 1.98%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.58%   |
| Intel Bluetooth Device                              | 4         | 1.58%   |
| IMC Networks Wireless_Device                        | 4         | 1.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.58%   |
| Realtek RTL8821A Bluetooth                          | 3         | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.19%   |
| Toshiba Bluetooth Device                            | 2         | 0.79%   |
| Realtek Bluetooth Radio                             | 2         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.79%   |
| Lite-On Wireless_Device                             | 2         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.79%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.79%   |
| IMC Networks Bluetooth Device                       | 2         | 0.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.79%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.79%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.79%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.79%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.4%    |
| Toshiba BCM43142A0                                  | 1         | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.4%    |
| Ralink RT3290 Bluetooth                             | 1         | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.4%    |
| Lite-On Bluetooth Radio                             | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 246       | 60.15%  |
| AMD                   | 65        | 15.89%  |
| Nvidia                | 63        | 15.4%   |
| Realtek Semiconductor | 8         | 1.96%   |
| Plantronics           | 5         | 1.22%   |
| GN Netcom             | 5         | 1.22%   |
| Logitech              | 3         | 0.73%   |
| RODE Microphones      | 2         | 0.49%   |
| Lenovo                | 2         | 0.49%   |
| C-Media Electronics   | 2         | 0.49%   |
| VIA Technologies      | 1         | 0.24%   |
| Sony                  | 1         | 0.24%   |
| No brand              | 1         | 0.24%   |
| Huawei Technologies   | 1         | 0.24%   |
| ESS Technology        | 1         | 0.24%   |
| Creative Technology   | 1         | 0.24%   |
| Conexant Systems      | 1         | 0.24%   |
| AUDIOLAB              | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 43        | 8.9%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 6.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 5.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 3.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 3.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 3.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 2.48%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 2.48%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.07%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 1.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.86%   |
| Realtek Semiconductor USB Audio                                                                   | 8         | 1.66%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.45%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.45%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.45%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.24%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.24%   |
| Plantronics Poly Voyager Focus 2 Series                                                           | 5         | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.04%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 1.04%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.83%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 57        | 29.23%  |
| SK hynix            | 42        | 21.54%  |
| Micron Technology   | 24        | 12.31%  |
| Kingston            | 16        | 8.21%   |
| Unknown             | 14        | 7.18%   |
| Crucial             | 12        | 6.15%   |
| Corsair             | 6         | 3.08%   |
| Ramaxel Technology  | 5         | 2.56%   |
| Elpida              | 4         | 2.05%   |
| Unknown (ABCD)      | 3         | 1.54%   |
| Nanya Technology    | 3         | 1.54%   |
| Transcend           | 1         | 0.51%   |
| SHARETRONIC         | 1         | 0.51%   |
| Patriot             | 1         | 0.51%   |
| G.Skill             | 1         | 0.51%   |
| CSX                 | 1         | 0.51%   |
| Apacer              | 1         | 0.51%   |
| A Force             | 1         | 0.51%   |
| 4ea5                | 1         | 0.51%   |
| Unknown             | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 2.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 2.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.46%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 1.46%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 1.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.98%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.98%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.98%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.98%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.98%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 4GB Chip DDR3 1333MT/s              | 2         | 0.98%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 0.98%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.49%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.49%   |
| Unknown RAM Module 256MB SODIMM DRAM                             | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 87        | 51.18%  |
| DDR3    | 44        | 25.88%  |
| LPDDR4  | 13        | 7.65%   |
| DDR2    | 9         | 5.29%   |
| LPDDR3  | 5         | 2.94%   |
| SDRAM   | 4         | 2.35%   |
| DDR5    | 3         | 1.76%   |
| DDR     | 2         | 1.18%   |
| LPDDR5  | 1         | 0.59%   |
| DRAM    | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 149       | 85.63%  |
| Row Of Chips | 19        | 10.92%  |
| Chip         | 4         | 2.3%    |
| Unknown      | 2         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 68        | 36.76%  |
| 4096  | 51        | 27.57%  |
| 16384 | 30        | 16.22%  |
| 2048  | 21        | 11.35%  |
| 1024  | 7         | 3.78%   |
| 32768 | 6         | 3.24%   |
| 256   | 1         | 0.54%   |
| 128   | 1         | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 34        | 18.68%  |
| 1600    | 30        | 16.48%  |
| 3200    | 28        | 15.38%  |
| 2400    | 18        | 9.89%   |
| 2133    | 14        | 7.69%   |
| 1334    | 8         | 4.4%    |
| 4267    | 6         | 3.3%    |
| 3266    | 5         | 2.75%   |
| 800     | 5         | 2.75%   |
| 667     | 5         | 2.75%   |
| 1333    | 4         | 2.2%    |
| 1067    | 4         | 2.2%    |
| 8400    | 3         | 1.65%   |
| 4800    | 3         | 1.65%   |
| 1867    | 3         | 1.65%   |
| 4266    | 2         | 1.1%    |
| 4199    | 2         | 1.1%    |
| 975     | 2         | 1.1%    |
| Unknown | 2         | 1.1%    |
| 6400    | 1         | 0.55%   |
| 2267    | 1         | 0.55%   |
| 2048    | 1         | 0.55%   |
| 533     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| STMicroelectronics | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 50%     |
| Brother HL-L2340D series                                  | 1         | 50%     |

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
| Chicony Electronics                    | 66        | 23.57%  |
| Realtek Semiconductor                  | 37        | 13.21%  |
| IMC Networks                           | 31        | 11.07%  |
| Microdia                               | 28        | 10%     |
| Acer                                   | 20        | 7.14%   |
| Sunplus Innovation Technology          | 16        | 5.71%   |
| Quanta                                 | 15        | 5.36%   |
| Logitech                               | 8         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.5%    |
| Apple                                  | 7         | 2.5%    |
| Suyin                                  | 6         | 2.14%   |
| Samsung Electronics                    | 5         | 1.79%   |
| Bison Electronics                      | 5         | 1.79%   |
| ALi                                    | 5         | 1.79%   |
| Syntek                                 | 4         | 1.43%   |
| Silicon Motion                         | 4         | 1.43%   |
| Lite-On Technology                     | 4         | 1.43%   |
| Ricoh                                  | 3         | 1.07%   |
| Z-Star Microelectronics                | 1         | 0.36%   |
| Y Media                                | 1         | 0.36%   |
| Trust                                  | 1         | 0.36%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.36%   |
| Nikon                                  | 1         | 0.36%   |
| Luxvisions Innotech Limited            | 1         | 0.36%   |
| Lenovo                                 | 1         | 0.36%   |
| DigiTech                               | 1         | 0.36%   |
| Alcor Micro                            | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD               | 15        | 5.32%   |
| Microdia Integrated_Webcam_HD              | 13        | 4.61%   |
| IMC Networks Integrated Camera             | 11        | 3.9%    |
| Chicony Integrated Camera                  | 10        | 3.55%   |
| Chicony USB2.0 Camera                      | 7         | 2.48%   |
| Chicony HD WebCam                          | 7         | 2.48%   |
| Sunplus Integrated_Webcam_FHD              | 6         | 2.13%   |
| IMC Networks USB2.0 HD UVC WebCam          | 6         | 2.13%   |
| Apple Built-in iSight                      | 6         | 2.13%   |
| Samsung Galaxy A5 (MTP)                    | 5         | 1.77%   |
| Microdia Integrated Webcam                 | 5         | 1.77%   |
| Acer Integrated Camera                     | 5         | 1.77%   |
| Sunplus Integrated_Webcam_HD               | 4         | 1.42%   |
| Bison Integrated Camera                    | 4         | 1.42%   |
| Acer EasyCamera                            | 4         | 1.42%   |
| Realtek EasyCamera                         | 3         | 1.06%   |
| Logitech HD Pro Webcam C920                | 3         | 1.06%   |
| Lite-On HP HD Camera                       | 3         | 1.06%   |
| Chicony Lenovo EasyCamera                  | 3         | 1.06%   |
| Chicony HP Wide Vision HD Camera           | 3         | 1.06%   |
| ALi WebCam                                 | 3         | 1.06%   |
| Acer BisonCam, NB Pro                      | 3         | 1.06%   |
| Syntek Integrated Camera                   | 2         | 0.71%   |
| Syntek EasyCamera                          | 2         | 0.71%   |
| Suyin HP Truevision HD                     | 2         | 0.71%   |
| Sunplus HP HD Webcam [Fixed]               | 2         | 0.71%   |
| Realtek USB2.0 HD UVC WebCam               | 2         | 0.71%   |
| Realtek Integrated Webcam HD               | 2         | 0.71%   |
| Realtek Integrated Webcam                  | 2         | 0.71%   |
| Realtek HP Truevision HD integrated webcam | 2         | 0.71%   |
| Realtek HD WebCam                          | 2         | 0.71%   |
| Quanta USB2.0 HD UVC WebCam                | 2         | 0.71%   |
| Quanta HP Webcam                           | 2         | 0.71%   |
| Quanta HP HD Camera                        | 2         | 0.71%   |
| Quanta ACER HD User Facing                 | 2         | 0.71%   |
| Microdia Webcam Vitade AF                  | 2         | 0.71%   |
| Microdia USB 2.0 Camera                    | 2         | 0.71%   |
| Logitech B525 HD Webcam                    | 2         | 0.71%   |
| IMC Networks VGA UVC WebCam                | 2         | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam         | 2         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 20        | 31.75%  |
| Validity Sensors           | 18        | 28.57%  |
| Shenzhen Goodix Technology | 12        | 19.05%  |
| Upek                       | 4         | 6.35%   |
| AuthenTec                  | 3         | 4.76%   |
| LighTuning Technology      | 2         | 3.17%   |
| Elan Microelectronics      | 2         | 3.17%   |
| STMicroelectronics         | 1         | 1.59%   |
| Focal-systems.Corp         | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix FingerPrint                                | 6         | 9.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 7.94%   |
| Unknown                                                    | 5         | 7.94%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 6.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 6.35%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 4.76%   |
| AuthenTec Fingerprint Sensor                               | 3         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.17%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 3.17%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 3.17%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 3.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 2         | 3.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 3.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 3.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.59%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.59%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.59%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.59%   |
| Validity Sensors Synaptics WBDI                            | 1         | 1.59%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.59%   |
| Synaptics WBDI                                             | 1         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.59%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 1.59%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.59%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.59%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.59%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 27        | 61.36%  |
| Alcor Micro | 7         | 15.91%  |
| Upek        | 5         | 11.36%  |
| O2 Micro    | 4         | 9.09%   |
| Lenovo      | 1         | 2.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 12        | 27.27%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 15.91%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 13.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 11.36%  |
| Broadcom 5880                                                                | 5         | 11.36%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6.82%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.27%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 175       | 53.19%  |
| 1     | 122       | 37.08%  |
| 2     | 25        | 7.6%    |
| 3     | 7         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 33.88%  |
| Chipcard                 | 39        | 21.31%  |
| Graphics card            | 32        | 17.49%  |
| Net/wireless             | 25        | 13.66%  |
| Camera                   | 6         | 3.28%   |
| Multimedia controller    | 5         | 2.73%   |
| Storage                  | 4         | 2.19%   |
| Communication controller | 3         | 1.64%   |
| Card reader              | 3         | 1.64%   |
| Bluetooth                | 3         | 1.64%   |
| Modem                    | 1         | 0.55%   |

