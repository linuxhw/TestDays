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

Total: 494

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | NBLK-WAX9X                  | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| Lenovo        | V330-15IKB 81AX             | [476a44deee](https://linux-hardware.org/?probe=476a44deee) | Jun 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [8678eeac9b](https://linux-hardware.org/?probe=8678eeac9b) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
| HP            | ZBook 15                    | [def4482b86](https://linux-hardware.org/?probe=def4482b86) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Dell          | Inspiron 5570               | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Dell          | XPS 13 9380                 | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Dell          | XPS 13 9380                 | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| Acer          | Nitro AN515-54              | [c223c83063](https://linux-hardware.org/?probe=c223c83063) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Dell          | Latitude E5520              | [43e2d970b5](https://linux-hardware.org/?probe=43e2d970b5) | Apr 30, 2023 |
| Dell          | Latitude 7420               | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| Dell          | Inspiron 7577               | [84ae892fb4](https://linux-hardware.org/?probe=84ae892fb4) | Apr 19, 2023 |
| HP            | Compaq Presario CQ70        | [030eff02bb](https://linux-hardware.org/?probe=030eff02bb) | Apr 18, 2023 |
| Dell          | Latitude 7420               | [1b2360944e](https://linux-hardware.org/?probe=1b2360944e) | Apr 17, 2023 |
| Lenovo        | S21e-20 80M4                | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Dell          | Latitude 5400               | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| ASUSTek       | G752VM                      | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
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
| Ubuntu 20.04       | 47        | 12.91%  |
| Ubuntu 18.04       | 28        | 7.69%   |
| Ubuntu 22.04       | 24        | 6.59%   |
| Debian 11          | 12        | 3.3%    |
| Pop!_OS 22.04      | 9         | 2.47%   |
| Linux Mint 21.1    | 7         | 1.92%   |
| Fedora 36          | 7         | 1.92%   |
| Debian 10          | 7         | 1.92%   |
| Zorin 16           | 6         | 1.65%   |
| OpenMandriva 4.2   | 6         | 1.65%   |
| Manjaro            | 6         | 1.65%   |
| Linux Mint 21      | 6         | 1.65%   |
| Ubuntu 22.10       | 5         | 1.37%   |
| Ubuntu 19.10       | 5         | 1.37%   |
| Linux Mint 20.3    | 5         | 1.37%   |
| Linux Mint 20.2    | 5         | 1.37%   |
| Linux Mint 20      | 5         | 1.37%   |
| KDE neon 20.04     | 5         | 1.37%   |
| Fedora 37          | 5         | 1.37%   |
| ArcoLinux Rolling  | 5         | 1.37%   |
| Ubuntu 21.10       | 4         | 1.1%    |
| Ubuntu 19.04       | 4         | 1.1%    |
| Pop!_OS 21.10      | 4         | 1.1%    |
| Pop!_OS 20.04      | 4         | 1.1%    |
| OpenMandriva 23.01 | 4         | 1.1%    |
| Lubuntu 20.04      | 4         | 1.1%    |
| Linux Mint 19.3    | 4         | 1.1%    |
| Kubuntu 20.04      | 4         | 1.1%    |
| Fedora 34          | 4         | 1.1%    |
| Debian Unstable    | 4         | 1.1%    |
| BlackPanther 18.1  | 4         | 1.1%    |
| Arch               | 4         | 1.1%    |
| Zorin 15           | 3         | 0.82%   |
| ROSA R10           | 3         | 0.82%   |
| Pop!_OS 20.10      | 3         | 0.82%   |
| Linux Mint 19.2    | 3         | 0.82%   |
| Fedora 33          | 3         | 0.82%   |
| Arch Rolling       | 3         | 0.82%   |
| Ubuntu Unity 16.04 | 2         | 0.55%   |
| Ubuntu MATE 20.04  | 2         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 121       | 34.67%  |
| Linux Mint    | 38        | 10.89%  |
| Debian        | 23        | 6.59%   |
| Pop!_OS       | 22        | 6.3%    |
| Fedora        | 22        | 6.3%    |
| OpenMandriva  | 15        | 4.3%    |
| Manjaro       | 13        | 3.72%   |
| Kubuntu       | 12        | 3.44%   |
| Zorin         | 9         | 2.58%   |
| Arch          | 7         | 2.01%   |
| ROSA          | 6         | 1.72%   |
| Lubuntu       | 6         | 1.72%   |
| KDE neon      | 5         | 1.43%   |
| Elementary    | 5         | 1.43%   |
| ArcoLinux     | 5         | 1.43%   |
| BlackPanther  | 4         | 1.15%   |
| Xubuntu       | 3         | 0.86%   |
| Ubuntu Unity  | 3         | 0.86%   |
| Ubuntu MATE   | 3         | 0.86%   |
| Ubuntu Budgie | 3         | 0.86%   |
| SteamOS       | 3         | 0.86%   |
| openSUSE      | 3         | 0.86%   |
| Endless       | 3         | 0.86%   |
| LMDE          | 2         | 0.57%   |
| Clear Linux   | 2         | 0.57%   |
| CentOS        | 2         | 0.57%   |
| Rocky Linux   | 1         | 0.29%   |
| RHEL          | 1         | 0.29%   |
| Redcore       | 1         | 0.29%   |
| Reborn OS     | 1         | 0.29%   |
| Peppermint    | 1         | 0.29%   |
| Nobara        | 1         | 0.29%   |
| MX            | 1         | 0.29%   |
| Chrome OS     | 1         | 0.29%   |
| BunsenLabs    | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.3.0-46-generic         | 8         | 2.04%   |
| 5.4.0-42-generic         | 6         | 1.53%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.53%   |
| 5.4.0-52-generic         | 5         | 1.28%   |
| 5.19.0-35-generic        | 5         | 1.28%   |
| 5.15.0-52-generic        | 5         | 1.28%   |
| 5.15.0-46-generic        | 5         | 1.28%   |
| 6.1.1-desktop-1omv2290   | 4         | 1.02%   |
| 5.4.0-26-generic         | 4         | 1.02%   |
| 5.15.0-67-generic        | 4         | 1.02%   |
| 5.15.0-56-generic        | 4         | 1.02%   |
| 5.15.0-48-generic        | 4         | 1.02%   |
| 5.4.0-31-generic         | 3         | 0.77%   |
| 5.4.0-29-generic         | 3         | 0.77%   |
| 5.15.0-40-generic        | 3         | 0.77%   |
| 5.11.0-27-generic        | 3         | 0.77%   |
| 5.10.0-14-amd64          | 3         | 0.77%   |
| 4.19.0-9-amd64           | 3         | 0.77%   |
| 4.18.16-desktop-1bP      | 3         | 0.77%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.51%   |
| 6.2.0-20-generic         | 2         | 0.51%   |
| 6.0.9-300.fc37.x86_64    | 2         | 0.51%   |
| 6.0.6-76060006-generic   | 2         | 0.51%   |
| 6.0.12-76060006-generic  | 2         | 0.51%   |
| 6.0.10-300.fc37.x86_64   | 2         | 0.51%   |
| 5.8.0-7625-generic       | 2         | 0.51%   |
| 5.8.0-53-generic         | 2         | 0.51%   |
| 5.8.0-43-generic         | 2         | 0.51%   |
| 5.4.0-91-generic         | 2         | 0.51%   |
| 5.4.0-80-generic         | 2         | 0.51%   |
| 5.4.0-7634-generic       | 2         | 0.51%   |
| 5.4.0-73-generic         | 2         | 0.51%   |
| 5.4.0-72-generic         | 2         | 0.51%   |
| 5.4.0-65-generic         | 2         | 0.51%   |
| 5.4.0-62-generic         | 2         | 0.51%   |
| 5.4.0-58-generic         | 2         | 0.51%   |
| 5.4.0-56-generic         | 2         | 0.51%   |
| 5.4.0-54-generic         | 2         | 0.51%   |
| 5.4.0-53-generic         | 2         | 0.51%   |
| 5.4.0-40-generic         | 2         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 70        | 19.18%  |
| 5.15.0  | 34        | 9.32%   |
| 4.15.0  | 23        | 6.3%    |
| 5.19.0  | 20        | 5.48%   |
| 5.3.0   | 17        | 4.66%   |
| 5.11.0  | 17        | 4.66%   |
| 5.8.0   | 15        | 4.11%   |
| 5.13.0  | 13        | 3.56%   |
| 5.10.0  | 13        | 3.56%   |
| 5.0.0   | 8         | 2.19%   |
| 4.19.0  | 8         | 2.19%   |
| 5.10.14 | 6         | 1.64%   |
| 4.18.0  | 5         | 1.37%   |
| 6.2.0   | 4         | 1.1%    |
| 6.1.1   | 4         | 1.1%    |
| 6.2.6   | 3         | 0.82%   |
| 4.18.16 | 3         | 0.82%   |
| 6.0.9   | 2         | 0.55%   |
| 6.0.6   | 2         | 0.55%   |
| 6.0.12  | 2         | 0.55%   |
| 6.0.10  | 2         | 0.55%   |
| 6.0.0   | 2         | 0.55%   |
| 5.7.9   | 2         | 0.55%   |
| 5.6.7   | 2         | 0.55%   |
| 5.6.15  | 2         | 0.55%   |
| 5.6.0   | 2         | 0.55%   |
| 5.19.1  | 2         | 0.55%   |
| 5.18.17 | 2         | 0.55%   |
| 5.18.0  | 2         | 0.55%   |
| 5.17.5  | 2         | 0.55%   |
| 5.16.7  | 2         | 0.55%   |
| 5.16.11 | 2         | 0.55%   |
| 5.14.0  | 2         | 0.55%   |
| 5.10.42 | 2         | 0.55%   |
| 4.9.60  | 2         | 0.55%   |
| 4.9.41  | 2         | 0.55%   |
| 4.12.14 | 2         | 0.55%   |
| 3.10.0  | 2         | 0.55%   |
| 6.2.8   | 1         | 0.27%   |
| 6.1.31  | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 73        | 20.17%  |
| 5.15    | 40        | 11.05%  |
| 5.19    | 25        | 6.91%   |
| 5.10    | 25        | 6.91%   |
| 4.15    | 23        | 6.35%   |
| 5.3     | 18        | 4.97%   |
| 5.8     | 17        | 4.7%    |
| 5.11    | 17        | 4.7%    |
| 5.13    | 15        | 4.14%   |
| 6.0     | 13        | 3.59%   |
| 4.19    | 9         | 2.49%   |
| 6.2     | 8         | 2.21%   |
| 5.0     | 8         | 2.21%   |
| 4.18    | 8         | 2.21%   |
| 5.6     | 7         | 1.93%   |
| 6.1     | 6         | 1.66%   |
| 5.18    | 6         | 1.66%   |
| 5.17    | 6         | 1.66%   |
| 5.16    | 6         | 1.66%   |
| 5.14    | 6         | 1.66%   |
| 4.9     | 5         | 1.38%   |
| 5.9     | 4         | 1.1%    |
| 5.7     | 4         | 1.1%    |
| 5.12    | 4         | 1.1%    |
| 4.12    | 2         | 0.55%   |
| 3.10    | 2         | 0.55%   |
| 5.2     | 1         | 0.28%   |
| 4.4     | 1         | 0.28%   |
| 4.14    | 1         | 0.28%   |
| 4.13    | 1         | 0.28%   |
| 4.10    | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 325       | 96.44%  |
| i686   | 12        | 3.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 169       | 47.88%  |
| KDE5            | 49        | 13.88%  |
| Unknown         | 41        | 11.61%  |
| X-Cinnamon      | 29        | 8.22%   |
| XFCE            | 17        | 4.82%   |
| KDE             | 11        | 3.12%   |
| LXQt            | 6         | 1.7%    |
| Pantheon        | 5         | 1.42%   |
| MATE            | 5         | 1.42%   |
| Cinnamon        | 5         | 1.42%   |
| i3              | 4         | 1.13%   |
| Unity           | 3         | 0.85%   |
| Budgie          | 3         | 0.85%   |
| KDE4            | 2         | 0.57%   |
| GNOME Classic   | 2         | 0.57%   |
| GNOME Flashback | 1         | 0.28%   |
| BunsenLabs      | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 271       | 79.24%  |
| Wayland | 46        | 13.45%  |
| Unknown | 22        | 6.43%   |
| Tty     | 3         | 0.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 182       | 52.6%   |
| GDM     | 44        | 12.72%  |
| SDDM    | 40        | 11.56%  |
| GDM3    | 34        | 9.83%   |
| LightDM | 31        | 8.96%   |
| TDM     | 12        | 3.47%   |
| KDM     | 2         | 0.58%   |
| SLiM    | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IE   | 167       | 48.27%  |
| en_GB   | 59        | 17.05%  |
| en_US   | 57        | 16.47%  |
| Unknown | 35        | 10.12%  |
| pl_PL   | 12        | 3.47%   |
| en_CA   | 2         | 0.58%   |
| bg_BG   | 2         | 0.58%   |
| zh_CN   | 1         | 0.29%   |
| pt_PT   | 1         | 0.29%   |
| lt_LT   | 1         | 0.29%   |
| it_IT   | 1         | 0.29%   |
| ga_IE   | 1         | 0.29%   |
| fr_FR   | 1         | 0.29%   |
| fr_BE   | 1         | 0.29%   |
| es_ES   | 1         | 0.29%   |
| en_ZA   | 1         | 0.29%   |
| en_IN   | 1         | 0.29%   |
| en_DE   | 1         | 0.29%   |
| C       | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 182       | 53.37%  |
| BIOS | 159       | 46.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 266       | 78.01%  |
| Btrfs               | 30        | 8.8%    |
| Overlay             | 21        | 6.16%   |
| Unknown             | 14        | 4.11%   |
| Xfs                 | 5         | 1.47%   |
| Zfs                 | 3         | 0.88%   |
| Tmpfs               | 1         | 0.29%   |
| Fuse.fuse-overlayfs | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 191       | 55.69%  |
| GPT     | 121       | 35.28%  |
| MBR     | 31        | 9.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 300       | 87.98%  |
| Yes       | 41        | 12.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 260       | 76.25%  |
| Yes       | 81        | 23.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 84        | 24.93%  |
| Lenovo              | 77        | 22.85%  |
| Hewlett-Packard     | 47        | 13.95%  |
| ASUSTek Computer    | 25        | 7.42%   |
| Acer                | 23        | 6.82%   |
| Toshiba             | 12        | 3.56%   |
| Apple               | 9         | 2.67%   |
| Samsung Electronics | 6         | 1.78%   |
| TUXEDO              | 4         | 1.19%   |
| Timi                | 4         | 1.19%   |
| PC Specialist       | 4         | 1.19%   |
| MSI                 | 4         | 1.19%   |
| Medion              | 4         | 1.19%   |
| Valve               | 3         | 0.89%   |
| Notebook            | 3         | 0.89%   |
| HUAWEI              | 3         | 0.89%   |
| Chuwi               | 3         | 0.89%   |
| System76            | 2         | 0.59%   |
| Fujitsu Siemens     | 2         | 0.59%   |
| Entroware           | 2         | 0.59%   |
| eMachines           | 2         | 0.59%   |
| Star Labs           | 1         | 0.3%    |
| Sony                | 1         | 0.3%    |
| SLIMBOOK            | 1         | 0.3%    |
| Schenker            | 1         | 0.3%    |
| Packard Bell        | 1         | 0.3%    |
| Microtech           | 1         | 0.3%    |
| Jumper              | 1         | 0.3%    |
| Google              | 1         | 0.3%    |
| Gigabyte Technology | 1         | 0.3%    |
| Framework           | 1         | 0.3%    |
| Dynabook            | 1         | 0.3%    |
| AVITA               | 1         | 0.3%    |
| Alienware           | 1         | 0.3%    |
| Advent              | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Dell Latitude 7420                | 8         | 2.37%   |
| Valve Jupiter                     | 3         | 0.89%   |
| Lenovo V145-15AST 81MT            | 3         | 0.89%   |
| Dell Latitude E7240               | 3         | 0.89%   |
| Dell Inspiron 13-5378             | 3         | 0.89%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.59%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.59%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.59%   |
| HUAWEI NBLK-WAX9X                 | 2         | 0.59%   |
| HP Pavilion g6                    | 2         | 0.59%   |
| HP OMEN by Laptop 15-dc0xxx       | 2         | 0.59%   |
| HP Notebook                       | 2         | 0.59%   |
| Dell XPS 9320                     | 2         | 0.59%   |
| Dell XPS 13 9310                  | 2         | 0.59%   |
| Dell XPS 13 9300                  | 2         | 0.59%   |
| Dell XPS 13 7390                  | 2         | 0.59%   |
| Dell Precision 5550               | 2         | 0.59%   |
| Dell Latitude E6230               | 2         | 0.59%   |
| Dell Inspiron 7577                | 2         | 0.59%   |
| Dell Inspiron 5570                | 2         | 0.59%   |
| ASUS X501A1                       | 2         | 0.59%   |
| Apple MacBook6,1                  | 2         | 0.59%   |
| Acer Aspire F5-573G               | 2         | 0.59%   |
| Acer Aspire E5-575G               | 2         | 0.59%   |
| TUXEDO InfinityBook Pro 15 v5     | 1         | 0.3%    |
| TUXEDO InfinityBook Pro 14 Gen6   | 1         | 0.3%    |
| Toshiba TECRA R850                | 1         | 0.3%    |
| Toshiba TECRA M4                  | 1         | 0.3%    |
| Toshiba Satellite Pro S500        | 1         | 0.3%    |
| Toshiba Satellite Pro R50-B       | 1         | 0.3%    |
| Toshiba Satellite Pro C660        | 1         | 0.3%    |
| Toshiba Satellite L500            | 1         | 0.3%    |
| Toshiba Satellite L50-C           | 1         | 0.3%    |
| Toshiba Satellite L50-B           | 1         | 0.3%    |
| Toshiba Satellite C50D-A-138      | 1         | 0.3%    |
| Toshiba Satellite C50-B           | 1         | 0.3%    |
| Toshiba Satellite A300            | 1         | 0.3%    |
| Toshiba PORTEGE R830              | 1         | 0.3%    |
| Timi TM1709                       | 1         | 0.3%    |
| Timi TM1703                       | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 42        | 12.46%  |
| Dell Latitude         | 39        | 11.57%  |
| Dell Inspiron         | 19        | 5.64%   |
| Acer Aspire           | 16        | 4.75%   |
| Lenovo IdeaPad        | 15        | 4.45%   |
| HP EliteBook          | 13        | 3.86%   |
| Dell XPS              | 13        | 3.86%   |
| HP Pavilion           | 11        | 3.26%   |
| Toshiba Satellite     | 9         | 2.67%   |
| Dell Precision        | 6         | 1.78%   |
| Valve Jupiter         | 3         | 0.89%   |
| Lenovo V145-15AST     | 3         | 0.89%   |
| Lenovo ThinkBook      | 3         | 0.89%   |
| HP ProBook            | 3         | 0.89%   |
| HP Presario           | 3         | 0.89%   |
| HP Laptop             | 3         | 0.89%   |
| ASUS ZenBook          | 3         | 0.89%   |
| ASUS ROG              | 3         | 0.89%   |
| Apple MacBookPro5     | 3         | 0.89%   |
| Acer Nitro            | 3         | 0.89%   |
| TUXEDO Pulse          | 2         | 0.59%   |
| TUXEDO InfinityBook   | 2         | 0.59%   |
| Toshiba TECRA         | 2         | 0.59%   |
| Lenovo IdeaPadFlex    | 2         | 0.59%   |
| HUAWEI NBLK-WAX9X     | 2         | 0.59%   |
| HP ZBook              | 2         | 0.59%   |
| HP OMEN               | 2         | 0.59%   |
| HP Notebook           | 2         | 0.59%   |
| HP Compaq             | 2         | 0.59%   |
| Fujitsu Siemens AMILO | 2         | 0.59%   |
| Dell Vostro           | 2         | 0.59%   |
| ASUS X501A1           | 2         | 0.59%   |
| ASUS TUF              | 2         | 0.59%   |
| Apple MacBook6        | 2         | 0.59%   |
| Toshiba PORTEGE       | 1         | 0.3%    |
| Timi TM1709           | 1         | 0.3%    |
| Timi TM1703           | 1         | 0.3%    |
| Timi TM1607           | 1         | 0.3%    |
| Timi A35S             | 1         | 0.3%    |
| System76 Galago       | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 41        | 12.17%  |
| 2019 | 35        | 10.39%  |
| 2017 | 29        | 8.61%   |
| 2013 | 25        | 7.42%   |
| 2021 | 24        | 7.12%   |
| 2018 | 24        | 7.12%   |
| 2012 | 23        | 6.82%   |
| 2011 | 21        | 6.23%   |
| 2016 | 20        | 5.93%   |
| 2015 | 18        | 5.34%   |
| 2022 | 15        | 4.45%   |
| 2009 | 14        | 4.15%   |
| 2010 | 13        | 3.86%   |
| 2008 | 13        | 3.86%   |
| 2014 | 10        | 2.97%   |
| 2007 | 7         | 2.08%   |
| 2006 | 3         | 0.89%   |
| 2005 | 1         | 0.3%    |
| 2003 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 337       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 297       | 87.1%   |
| Enabled  | 44        | 12.9%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 335       | 99.41%  |
| Yes  | 2         | 0.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 101       | 29.53%  |
| 16.01-24.0  | 69        | 20.18%  |
| 3.01-4.0    | 60        | 17.54%  |
| 8.01-16.0   | 53        | 15.5%   |
| 32.01-64.0  | 31        | 9.06%   |
| 1.01-2.0    | 13        | 3.8%    |
| 2.01-3.0    | 5         | 1.46%   |
| 24.01-32.0  | 4         | 1.17%   |
| 64.01-256.0 | 3         | 0.88%   |
| 0.51-1.0    | 2         | 0.58%   |
| 0.01-0.5    | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 112       | 30.11%  |
| 2.01-3.0   | 99        | 26.61%  |
| 4.01-8.0   | 62        | 16.67%  |
| 3.01-4.0   | 60        | 16.13%  |
| 0.51-1.0   | 23        | 6.18%   |
| 8.01-16.0  | 11        | 2.96%   |
| 16.01-24.0 | 3         | 0.81%   |
| 0.01-0.5   | 2         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 254       | 73.2%   |
| 2      | 79        | 22.77%  |
| 3      | 12        | 3.46%   |
| 0      | 2         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 224       | 65.88%  |
| Yes       | 116       | 34.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 274       | 80.59%  |
| No        | 66        | 19.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 334       | 98.82%  |
| No        | 4         | 1.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 270       | 79.41%  |
| No        | 70        | 20.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ireland | 337       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dublin              | 190       | 55.23%  |
| Cork                | 22        | 6.4%    |
| Galway              | 18        | 5.23%   |
| Limerick            | 10        | 2.91%   |
| Naas                | 7         | 2.03%   |
| Drogheda            | 6         | 1.74%   |
| Enniscorthy         | 5         | 1.45%   |
| Ennis               | 5         | 1.45%   |
| Navan               | 4         | 1.16%   |
| Dún Laoghaire      | 3         | 0.87%   |
| Wexford             | 2         | 0.58%   |
| Westport            | 2         | 0.58%   |
| Waterford           | 2         | 0.58%   |
| Portlaoise          | 2         | 0.58%   |
| Nenagh              | 2         | 0.58%   |
| Maynooth            | 2         | 0.58%   |
| Lucan               | 2         | 0.58%   |
| Loughrea            | 2         | 0.58%   |
| Kilkenny            | 2         | 0.58%   |
| Donegal             | 2         | 0.58%   |
| Cobh                | 2         | 0.58%   |
| Clonakilty          | 2         | 0.58%   |
| Clane               | 2         | 0.58%   |
| Ballina             | 2         | 0.58%   |
| Athlone             | 2         | 0.58%   |
| Youghal             | 1         | 0.29%   |
| Wicklow             | 1         | 0.29%   |
| Tullow              | 1         | 0.29%   |
| Tullamore           | 1         | 0.29%   |
| Tuam                | 1         | 0.29%   |
| Tobercurry          | 1         | 0.29%   |
| Tallaght            | 1         | 0.29%   |
| Sligo               | 1         | 0.29%   |
| Slane               | 1         | 0.29%   |
| Scarriff            | 1         | 0.29%   |
| Santry              | 1         | 0.29%   |
| Rathcool            | 1         | 0.29%   |
| Oughterard          | 1         | 0.29%   |
| Newmarket on Fergus | 1         | 0.29%   |
| Newcastle           | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 84        | 112    | 20%     |
| WDC                       | 52        | 62     | 12.38%  |
| Seagate                   | 36        | 45     | 8.57%   |
| Unknown                   | 31        | 42     | 7.38%   |
| Toshiba                   | 28        | 33     | 6.67%   |
| SanDisk                   | 26        | 29     | 6.19%   |
| Hitachi                   | 22        | 25     | 5.24%   |
| Crucial                   | 17        | 24     | 4.05%   |
| Micron Technology         | 13        | 14     | 3.1%    |
| KIOXIA                    | 13        | 14     | 3.1%    |
| Kingston                  | 11        | 13     | 2.62%   |
| Intel                     | 11        | 14     | 2.62%   |
| HGST                      | 11        | 12     | 2.62%   |
| SK hynix                  | 10        | 10     | 2.38%   |
| Fujitsu                   | 6         | 7      | 1.43%   |
| PNY                       | 3         | 3      | 0.71%   |
| LITEONIT                  | 3         | 3      | 0.71%   |
| LITEON                    | 3         | 3      | 0.71%   |
| KingSpec                  | 3         | 3      | 0.71%   |
| Transcend                 | 2         | 2      | 0.48%   |
| Silicon Motion            | 2         | 3      | 0.48%   |
| FORESEE                   | 2         | 2      | 0.48%   |
| Apple                     | 2         | 2      | 0.48%   |
| A-DATA Technology         | 2         | 2      | 0.48%   |
| Zheino                    | 1         | 1      | 0.24%   |
| W800S                     | 1         | 2      | 0.24%   |
| Verbatim                  | 1         | 1      | 0.24%   |
| Union Memory              | 1         | 1      | 0.24%   |
| Star                      | 1         | 1      | 0.24%   |
| SPCC                      | 1         | 1      | 0.24%   |
| ShanDianZhe               | 1         | 1      | 0.24%   |
| SABRENT                   | 1         | 2      | 0.24%   |
| QNAP                      | 1         | 1      | 0.24%   |
| Plextor                   | 1         | 1      | 0.24%   |
| Phison Electronics        | 1         | 1      | 0.24%   |
| Phison                    | 1         | 1      | 0.24%   |
| Patriot                   | 1         | 1      | 0.24%   |
| OCZ                       | 1         | 1      | 0.24%   |
| O2 Micro                  | 1         | 2      | 0.24%   |
| Micron/Crucial Technology | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 9         | 2.06%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 8         | 1.83%   |
| SanDisk NVMe SSD Drive 512GB                        | 6         | 1.38%   |
| Unknown MMC Card  32GB                              | 5         | 1.15%   |
| Kingston SA400S37480G 480GB SSD                     | 5         | 1.15%   |
| Unknown MMC Card  64GB                              | 4         | 0.92%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 0.92%   |
| Samsung SSD 860 EVO 500GB                           | 4         | 0.92%   |
| Samsung NVMe SSD Drive 256GB                        | 4         | 0.92%   |
| Hitachi HTS723232A7A364 320GB                       | 4         | 0.92%   |
| HGST HTS721010A9E630 1TB                            | 4         | 0.92%   |
| HGST HTS545050A7E680 500GB                          | 4         | 0.92%   |
| Crucial CT1000MX500SSD1 1TB                         | 4         | 0.92%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 3         | 0.69%   |
| Unknown SL16G  16GB                                 | 3         | 0.69%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.69%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 3         | 0.69%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.69%   |
| Samsung NVMe SSD Drive 512GB                        | 3         | 0.69%   |
| Samsung NVMe SSD Drive 500GB                        | 3         | 0.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 0.69%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 3         | 0.69%   |
| PNY CS900 120GB SSD                                 | 3         | 0.69%   |
| Crucial M4-CT128M4SSD2 128GB                        | 3         | 0.69%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD                      | 2         | 0.46%   |
| WDC WD10SPZX-75Z10T2 1TB                            | 2         | 0.46%   |
| WDC WD10JPVX-00JC3T0 1TB                            | 2         | 0.46%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 2         | 0.46%   |
| WDC PC SN530 NVMe 512GB                             | 2         | 0.46%   |
| Unknown SD/MMC/MS PRO 64GB                          | 2         | 0.46%   |
| Unknown HBG4a2  32GB                                | 2         | 0.46%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 2         | 0.46%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.46%   |
| Toshiba KBG30ZMS256G NVMe 256GB                     | 2         | 0.46%   |
| SK hynix NVMe SSD Drive 2TB                         | 2         | 0.46%   |
| Seagate ST9500420ASG 500GB                          | 2         | 0.46%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.46%   |
| Seagate ST500LM000-1EJ162 500GB                     | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 44     | 26.72%  |
| WDC                 | 33        | 36     | 25.19%  |
| Hitachi             | 22        | 25     | 16.79%  |
| Toshiba             | 15        | 16     | 11.45%  |
| HGST                | 11        | 12     | 8.4%    |
| Fujitsu             | 6         | 7      | 4.58%   |
| Samsung Electronics | 3         | 4      | 2.29%   |
| Unknown             | 2         | 2      | 1.53%   |
| SABRENT             | 1         | 2      | 0.76%   |
| QNAP                | 1         | 1      | 0.76%   |
| LaCie               | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 42     | 27.78%  |
| SanDisk             | 16        | 16     | 12.7%   |
| Crucial             | 16        | 23     | 12.7%   |
| Kingston            | 11        | 13     | 8.73%   |
| WDC                 | 7         | 10     | 5.56%   |
| Toshiba             | 3         | 5      | 2.38%   |
| PNY                 | 3         | 3      | 2.38%   |
| Micron Technology   | 3         | 3      | 2.38%   |
| LITEONIT            | 3         | 3      | 2.38%   |
| KingSpec            | 3         | 3      | 2.38%   |
| SK hynix            | 2         | 2      | 1.59%   |
| LITEON              | 2         | 2      | 1.59%   |
| Intel               | 2         | 2      | 1.59%   |
| FORESEE             | 2         | 2      | 1.59%   |
| Zheino              | 1         | 1      | 0.79%   |
| W800S               | 1         | 2      | 0.79%   |
| Verbatim            | 1         | 1      | 0.79%   |
| Transcend           | 1         | 1      | 0.79%   |
| Star                | 1         | 1      | 0.79%   |
| SPCC                | 1         | 1      | 0.79%   |
| Plextor             | 1         | 1      | 0.79%   |
| Patriot             | 1         | 1      | 0.79%   |
| OCZ                 | 1         | 1      | 0.79%   |
| JMicron Technology  | 1         | 1      | 0.79%   |
| Integral            | 1         | 1      | 0.79%   |
| GOODRAM             | 1         | 1      | 0.79%   |
| faspeed             | 1         | 1      | 0.79%   |
| Emtec               | 1         | 2      | 0.79%   |
| Dogfish             | 1         | 1      | 0.79%   |
| China               | 1         | 6      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |
| A-DATA Technology   | 1         | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 127       | 166    | 31.75%  |
| HDD     | 124       | 151    | 31%     |
| SSD     | 116       | 154    | 29%     |
| MMC     | 28        | 39     | 7%      |
| Unknown | 5         | 5      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 220       | 298    | 57.29%  |
| NVMe | 127       | 166    | 33.07%  |
| MMC  | 28        | 39     | 7.29%   |
| SAS  | 9         | 12     | 2.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 162       | 209    | 68.64%  |
| 0.51-1.0   | 66        | 85     | 27.97%  |
| 1.01-2.0   | 4         | 6      | 1.69%   |
| 3.01-4.0   | 3         | 4      | 1.27%   |
| 2.01-3.0   | 1         | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 105       | 30.17%  |
| 101-250        | 96        | 27.59%  |
| 501-1000       | 40        | 11.49%  |
| 51-100         | 30        | 8.62%   |
| 1-20           | 29        | 8.33%   |
| 1001-2000      | 19        | 5.46%   |
| 21-50          | 13        | 3.74%   |
| Unknown        | 10        | 2.87%   |
| More than 3000 | 4         | 1.15%   |
| 2001-3000      | 2         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 146       | 40.11%  |
| 21-50          | 61        | 16.76%  |
| 101-250        | 57        | 15.66%  |
| 51-100         | 50        | 13.74%  |
| 251-500        | 22        | 6.04%   |
| 501-1000       | 13        | 3.57%   |
| Unknown        | 10        | 2.75%   |
| 1001-2000      | 4         | 1.1%    |
| More than 3000 | 1         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 10%     |
| WDC WD5000LPCX-24VHAT0 500GB                   | 1         | 1      | 5%      |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 5%      |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 5%      |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 5%      |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 5%      |
| Seagate ST910021AS 100GB                       | 1         | 1      | 5%      |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 5%      |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 5%      |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 5%      |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 5%      |
| JMicron Technology Generic 320GB               | 1         | 1      | 5%      |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 5%      |
| Hitachi HTS545032A7E380 320GB                  | 1         | 1      | 5%      |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 2      | 5%      |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 5%      |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 5%      |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 5%      |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 8      | 35%     |
| Toshiba             | 3         | 3      | 15%     |
| WDC                 | 2         | 2      | 10%     |
| Micron Technology   | 2         | 2      | 10%     |
| Seagate             | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| JMicron Technology  | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 7         | 8      | 43.75%  |
| Toshiba             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Seagate             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 17     | 76.47%  |
| SSD  | 4         | 4      | 23.53%  |

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
| Detected | 213       | 320    | 60%     |
| Works    | 125       | 173    | 35.21%  |
| Malfunc  | 16        | 21     | 4.51%   |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 222       | 56.06%  |
| Samsung Electronics          | 48        | 12.12%  |
| AMD                          | 39        | 9.85%   |
| SanDisk                      | 23        | 5.81%   |
| KIOXIA                       | 12        | 3.03%   |
| Toshiba America Info Systems | 11        | 2.78%   |
| Micron Technology            | 10        | 2.53%   |
| SK hynix                     | 8         | 2.02%   |
| Nvidia                       | 8         | 2.02%   |
| Union Memory (Shenzhen)      | 2         | 0.51%   |
| Silicon Motion               | 2         | 0.51%   |
| Phison Electronics           | 2         | 0.51%   |
| Micron/Crucial Technology    | 2         | 0.51%   |
| Transcend                    | 1         | 0.25%   |
| Silicon Image                | 1         | 0.25%   |
| O2 Micro                     | 1         | 0.25%   |
| Lite-On Technology           | 1         | 0.25%   |
| Kingston Technology Company  | 1         | 0.25%   |
| ADATA Technology             | 1         | 0.25%   |
| Adaptec                      | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 39        | 9.24%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 8.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 5.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 4.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 3.55%   |
| Samsung NVMe SSD Controller 980                                                | 13        | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 11        | 2.61%   |
| Micron NVMe Storage Controller                                                 | 10        | 2.37%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 10        | 2.37%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.13%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 8         | 1.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 1.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 1.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.18%   |
| Nvidia MCP79 AHCI Controller                                                   | 5         | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.18%   |
| SanDisk PC SN520 NVMe SSD                                                      | 4         | 0.95%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 0.95%   |
| Intel SSD 660P Series                                                          | 4         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 0.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.95%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.71%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 225       | 55.56%  |
| NVMe | 128       | 31.6%   |
| RAID | 29        | 7.16%   |
| IDE  | 22        | 5.43%   |
| SCSI | 1         | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 275       | 81.36%  |
| AMD    | 63        | 18.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 12        | 3.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 2.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 2.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 2.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.48%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.18%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.18%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.18%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.89%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.89%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.89%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.89%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.89%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.89%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.89%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.89%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.89%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.89%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.89%   |
| AMD Custom APU 0405                           | 3         | 0.89%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 0.89%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.59%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.59%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.59%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.59%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.59%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 76        | 22.49%  |
| Intel Core i5           | 75        | 22.19%  |
| Other                   | 41        | 12.13%  |
| Intel Core i3           | 21        | 6.21%   |
| Intel Celeron           | 20        | 5.92%   |
| Intel Core 2 Duo        | 18        | 5.33%   |
| AMD Ryzen 7             | 13        | 3.85%   |
| AMD Ryzen 5             | 12        | 3.55%   |
| Intel Pentium           | 7         | 2.07%   |
| Intel Atom              | 6         | 1.78%   |
| AMD A8                  | 4         | 1.18%   |
| Intel Core 2            | 3         | 0.89%   |
| AMD Ryzen 9             | 3         | 0.89%   |
| AMD Ryzen 7 PRO         | 3         | 0.89%   |
| AMD E1                  | 3         | 0.89%   |
| Intel Pentium Dual-Core | 2         | 0.59%   |
| Intel Core i9           | 2         | 0.59%   |
| Intel Celeron Dual-Core | 2         | 0.59%   |
| AMD Ryzen 5 PRO         | 2         | 0.59%   |
| AMD E2                  | 2         | 0.59%   |
| AMD A10                 | 2         | 0.59%   |
| Intel Pentium Silver    | 1         | 0.3%    |
| Intel Pentium M         | 1         | 0.3%    |
| Intel Pentium III       | 1         | 0.3%    |
| Intel Pentium Dual      | 1         | 0.3%    |
| Intel Genuine           | 1         | 0.3%    |
| Intel Core m7           | 1         | 0.3%    |
| Intel Core m5           | 1         | 0.3%    |
| Intel Core m3           | 1         | 0.3%    |
| Intel Core 2 Extreme    | 1         | 0.3%    |
| Intel Celeron M         | 1         | 0.3%    |
| AMD Turion 64 X2 Mobile | 1         | 0.3%    |
| AMD Sempron             | 1         | 0.3%    |
| AMD Ryzen 3 PRO         | 1         | 0.3%    |
| AMD Ryzen 3             | 1         | 0.3%    |
| AMD PRO A10             | 1         | 0.3%    |
| AMD Phenom II           | 1         | 0.3%    |
| AMD FX                  | 1         | 0.3%    |
| AMD E                   | 1         | 0.3%    |
| AMD Athlon 64 X2        | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 159       | 47.04%  |
| 4      | 121       | 35.8%   |
| 8      | 20        | 5.92%   |
| 6      | 18        | 5.33%   |
| 1      | 10        | 2.96%   |
| 14     | 5         | 1.48%   |
| 12     | 3         | 0.89%   |
| 10     | 1         | 0.3%    |
| 3      | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 337       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 249       | 73.89%  |
| 1      | 88        | 26.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 328       | 96.76%  |
| Unknown        | 8         | 2.36%   |
| 32-bit         | 3         | 0.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 25.94%  |
| 0x306a9    | 18        | 5.19%   |
| 0x806ec    | 17        | 4.9%    |
| 0x806e9    | 15        | 4.32%   |
| 0x806c1    | 13        | 3.75%   |
| 0x206a7    | 13        | 3.75%   |
| 0x806ea    | 12        | 3.46%   |
| 0x1067a    | 12        | 3.46%   |
| 0x406e3    | 10        | 2.88%   |
| 0x40651    | 10        | 2.88%   |
| 0xa0652    | 7         | 2.02%   |
| 0x906ea    | 7         | 2.02%   |
| 0x906e9    | 6         | 1.73%   |
| 0x306d4    | 6         | 1.73%   |
| 0x306c3    | 6         | 1.73%   |
| 0x30678    | 6         | 1.73%   |
| 0x0a50000c | 6         | 1.73%   |
| 0x406c4    | 5         | 1.44%   |
| 0x20655    | 5         | 1.44%   |
| 0x10676    | 5         | 1.44%   |
| 0x06006705 | 5         | 1.44%   |
| 0x6fd      | 4         | 1.15%   |
| 0x08108102 | 4         | 1.15%   |
| 0x906a3    | 3         | 0.86%   |
| 0x806d1    | 3         | 0.86%   |
| 0x706e5    | 3         | 0.86%   |
| 0x506e3    | 3         | 0.86%   |
| 0x106ca    | 3         | 0.86%   |
| 0x08600106 | 3         | 0.86%   |
| 0x08108109 | 3         | 0.86%   |
| 0x706a8    | 2         | 0.58%   |
| 0x6f6      | 2         | 0.58%   |
| 0x6d8      | 2         | 0.58%   |
| 0x20652    | 2         | 0.58%   |
| 0x08608103 | 2         | 0.58%   |
| 0x08600103 | 2         | 0.58%   |
| 0x07030106 | 2         | 0.58%   |
| 0x0600611a | 2         | 0.58%   |
| 0x06001119 | 2         | 0.58%   |
| 0x05000119 | 2         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 70        | 20.77%  |
| IvyBridge        | 23        | 6.82%   |
| TigerLake        | 22        | 6.53%   |
| Skylake          | 21        | 6.23%   |
| SandyBridge      | 20        | 5.93%   |
| Haswell          | 20        | 5.93%   |
| Penryn           | 17        | 5.04%   |
| Silvermont       | 15        | 4.45%   |
| Westmere         | 11        | 3.26%   |
| Core             | 11        | 3.26%   |
| Unknown          | 11        | 3.26%   |
| Zen 2            | 10        | 2.97%   |
| Zen+             | 9         | 2.67%   |
| Excavator        | 9         | 2.67%   |
| Zen 3            | 8         | 2.37%   |
| IceLake          | 8         | 2.37%   |
| CometLake        | 7         | 2.08%   |
| Broadwell        | 7         | 2.08%   |
| Goldmont plus    | 5         | 1.48%   |
| Zen              | 4         | 1.19%   |
| P6               | 4         | 1.19%   |
| Bobcat           | 4         | 1.19%   |
| Puma             | 3         | 0.89%   |
| K8 Hammer        | 3         | 0.89%   |
| Bonnell          | 3         | 0.89%   |
| Alderlake Hybrid | 3         | 0.89%   |
| Piledriver       | 2         | 0.59%   |
| K10              | 2         | 0.59%   |
| Jaguar           | 2         | 0.59%   |
| Goldmont         | 2         | 0.59%   |
| Nehalem          | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 241       | 58.35%  |
| Nvidia | 102       | 24.7%   |
| AMD    | 70        | 16.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 5.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 3.99%   |
| Intel UHD Graphics 620                                                                   | 15        | 3.52%   |
| Intel HD Graphics 620                                                                    | 15        | 3.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 2.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 2.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 2.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.11%   |
| AMD Renoir                                                                               | 9         | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.88%   |
| Intel HD Graphics 630                                                                    | 7         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.64%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.41%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 6         | 1.41%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.41%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.94%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.94%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.94%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.7%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.7%    |
| Nvidia GM107 [GeForce 940MX]                                                             | 3         | 0.7%    |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 175       | 51.78%  |
| Intel + Nvidia | 61        | 18.05%  |
| 1 x AMD        | 49        | 14.5%   |
| 1 x Nvidia     | 31        | 9.17%   |
| AMD + Nvidia   | 9         | 2.66%   |
| 2 x AMD        | 7         | 2.07%   |
| Intel + AMD    | 5         | 1.48%   |
| 2 x Nvidia     | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 277       | 81.23%  |
| Proprietary | 52        | 15.25%  |
| Unknown     | 12        | 3.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 216       | 62.43%  |
| 0.01-0.5   | 50        | 14.45%  |
| 3.01-4.0   | 26        | 7.51%   |
| 1.01-2.0   | 26        | 7.51%   |
| 0.51-1.0   | 16        | 4.62%   |
| 5.01-6.0   | 6         | 1.73%   |
| 7.01-8.0   | 4         | 1.16%   |
| 2.01-3.0   | 2         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 70        | 17.77%  |
| BOE                     | 61        | 15.48%  |
| LG Display              | 58        | 14.72%  |
| Chimei Innolux          | 35        | 8.88%   |
| Samsung Electronics     | 30        | 7.61%   |
| Dell                    | 25        | 6.35%   |
| Sharp                   | 20        | 5.08%   |
| ViewSonic               | 9         | 2.28%   |
| Lenovo                  | 9         | 2.28%   |
| Chi Mei Optoelectronics | 8         | 2.03%   |
| Apple                   | 8         | 2.03%   |
| PANDA                   | 7         | 1.78%   |
| Hewlett-Packard         | 7         | 1.78%   |
| Goldstar                | 7         | 1.78%   |
| Philips                 | 5         | 1.27%   |
| LG Philips              | 4         | 1.02%   |
| Acer                    | 4         | 1.02%   |
| InfoVision              | 3         | 0.76%   |
| AOC                     | 3         | 0.76%   |
| Valve                   | 2         | 0.51%   |
| MSI                     | 2         | 0.51%   |
| CSO                     | 2         | 0.51%   |
| CPT                     | 2         | 0.51%   |
| BOE Technology Group    | 2         | 0.51%   |
| ___                     | 1         | 0.25%   |
| Vestel Elektronik       | 1         | 0.25%   |
| Unknown                 | 1         | 0.25%   |
| Toshiba                 | 1         | 0.25%   |
| Quanta Display          | 1         | 0.25%   |
| OEM                     | 1         | 0.25%   |
| LGD                     | 1         | 0.25%   |
| Lenovo Group Limited    | 1         | 0.25%   |
| Iiyama                  | 1         | 0.25%   |
| BenQ                    | 1         | 0.25%   |
| Analogix                | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                | 9         | 2.23%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch            | 8         | 1.98%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                    | 8         | 1.98%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 4         | 0.99%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.99%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 4         | 0.99%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 3         | 0.74%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.74%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 0.74%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 3         | 0.74%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.5%    |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch              | 2         | 0.5%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.5%    |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.5%    |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.5%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch | 2         | 0.5%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 2         | 0.5%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.5%    |
| LG Philips LCD Monitor LPLA104 1440x900 367x230mm 17.1-inch          | 2         | 0.5%    |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 2         | 0.5%    |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch         | 2         | 0.5%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 2         | 0.5%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 2         | 0.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 2         | 0.5%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.5%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 2         | 0.5%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 2         | 0.5%    |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch           | 2         | 0.5%    |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch     | 2         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 2         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 169       | 45.68%  |
| 1366x768 (WXGA)    | 90        | 24.32%  |
| 2560x1440 (QHD)    | 15        | 4.05%   |
| 1600x900 (HD+)     | 15        | 4.05%   |
| 3840x2160 (4K)     | 14        | 3.78%   |
| 1280x800 (WXGA)    | 13        | 3.51%   |
| 1920x1200 (WUXGA)  | 11        | 2.97%   |
| 1440x900 (WXGA+)   | 10        | 2.7%    |
| 3440x1440          | 4         | 1.08%   |
| 2560x1600          | 4         | 1.08%   |
| 800x1280           | 3         | 0.81%   |
| 3840x2400          | 3         | 0.81%   |
| 1024x600           | 3         | 0.81%   |
| 3456x2160          | 2         | 0.54%   |
| 3200x1800 (QHD+)   | 2         | 0.54%   |
| 1600x1200          | 2         | 0.54%   |
| 1360x768           | 2         | 0.54%   |
| 1280x1024 (SXGA)   | 2         | 0.54%   |
| 2880x1800          | 1         | 0.27%   |
| 2560x1080          | 1         | 0.27%   |
| 2256x1504          | 1         | 0.27%   |
| 2160x1440          | 1         | 0.27%   |
| 1920x540           | 1         | 0.27%   |
| 1680x1050 (WSXGA+) | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 159       | 39.75%  |
| 14      | 56        | 14%     |
| 13      | 47        | 11.75%  |
| 27      | 25        | 6.25%   |
| 17      | 20        | 5%      |
| 12      | 16        | 4%      |
| 21      | 15        | 3.75%   |
| 24      | 13        | 3.25%   |
| 23      | 9         | 2.25%   |
| Unknown | 8         | 2%      |
| 11      | 6         | 1.5%    |
| 34      | 5         | 1.25%   |
| 31      | 3         | 0.75%   |
| 10      | 3         | 0.75%   |
| 29      | 2         | 0.5%    |
| 18      | 2         | 0.5%    |
| 16      | 2         | 0.5%    |
| 7       | 2         | 0.5%    |
| 84      | 1         | 0.25%   |
| 72      | 1         | 0.25%   |
| 40      | 1         | 0.25%   |
| 25      | 1         | 0.25%   |
| 20      | 1         | 0.25%   |
| 19      | 1         | 0.25%   |
| 3       | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 228       | 57.58%  |
| 201-300     | 55        | 13.89%  |
| 501-600     | 41        | 10.35%  |
| 351-400     | 26        | 6.57%   |
| 401-500     | 18        | 4.55%   |
| 601-700     | 9         | 2.27%   |
| Unknown     | 8         | 2.02%   |
| 701-800     | 5         | 1.26%   |
| 1-100       | 3         | 0.76%   |
| 1501-2000   | 2         | 0.51%   |
| 801-900     | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 274       | 81.07%  |
| 16/10   | 41        | 12.13%  |
| Unknown | 7         | 2.07%   |
| 21/9    | 6         | 1.78%   |
| 3/2     | 3         | 0.89%   |
| 5/4     | 2         | 0.59%   |
| 4/3     | 2         | 0.59%   |
| 0.67    | 2         | 0.59%   |
| 6/5     | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 155       | 38.85%  |
| 81-90          | 77        | 19.3%   |
| 201-250        | 31        | 7.77%   |
| 71-80          | 27        | 6.77%   |
| 301-350        | 26        | 6.52%   |
| 61-70          | 15        | 3.76%   |
| 121-130        | 15        | 3.76%   |
| 351-500        | 9         | 2.26%   |
| Unknown        | 8         | 2.01%   |
| 51-60          | 6         | 1.5%    |
| 111-120        | 5         | 1.25%   |
| 251-300        | 4         | 1%      |
| 151-200        | 4         | 1%      |
| 131-140        | 4         | 1%      |
| 41-50          | 3         | 0.75%   |
| 1-40           | 3         | 0.75%   |
| 141-150        | 3         | 0.75%   |
| More than 1000 | 2         | 0.5%    |
| 501-1000       | 1         | 0.25%   |
| 91-100         | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 171       | 44.53%  |
| 101-120       | 103       | 26.82%  |
| 51-100        | 56        | 14.58%  |
| 161-240       | 31        | 8.07%   |
| More than 240 | 13        | 3.39%   |
| Unknown       | 8         | 2.08%   |
| 1-50          | 2         | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 261       | 75.43%  |
| 2     | 58        | 16.76%  |
| 3     | 14        | 4.05%   |
| 0     | 12        | 3.47%   |
| 4     | 1         | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 198       | 36.26%  |
| Realtek Semiconductor             | 169       | 30.95%  |
| Qualcomm Atheros                  | 63        | 11.54%  |
| Broadcom                          | 38        | 6.96%   |
| Broadcom Limited                  | 9         | 1.65%   |
| Nvidia                            | 8         | 1.47%   |
| MediaTek                          | 8         | 1.47%   |
| Ralink Technology                 | 6         | 1.1%    |
| Marvell Technology Group          | 5         | 0.92%   |
| Lenovo                            | 5         | 0.92%   |
| Ericsson Business Mobile Networks | 5         | 0.92%   |
| ASIX Electronics                  | 5         | 0.92%   |
| Samsung Electronics               | 4         | 0.73%   |
| Ralink                            | 3         | 0.55%   |
| Xiaomi                            | 2         | 0.37%   |
| Qualcomm                          | 2         | 0.37%   |
| Dell                              | 2         | 0.37%   |
| Xilinx                            | 1         | 0.18%   |
| TP-Link                           | 1         | 0.18%   |
| Toshiba                           | 1         | 0.18%   |
| T & A Mobile Phones               | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.18%   |
| NetGear                           | 1         | 0.18%   |
| Microsoft                         | 1         | 0.18%   |
| LSI                               | 1         | 0.18%   |
| ICS Advent                        | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| DisplayLink                       | 1         | 0.18%   |
| Bose                              | 1         | 0.18%   |
| Apple                             | 1         | 0.18%   |
| 3Com                              | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 14.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 4.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 3.35%   |
| Intel Wi-Fi 6 AX200                                               | 21        | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 2.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 17        | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 2.44%   |
| Intel Wireless 8265 / 8275                                        | 15        | 2.29%   |
| Intel Wi-Fi 6 AX201                                               | 15        | 2.29%   |
| Intel Wireless 7260                                               | 14        | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 1.98%   |
| Intel Wireless 8260                                               | 11        | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.37%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 8         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.07%   |
| Intel Wireless 3165                                               | 7         | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 1.07%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.91%   |
| Intel Wireless 7265                                               | 6         | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.76%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.76%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.61%   |
| Intel Wireless 3160                                               | 4         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.61%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 193       | 55.14%  |
| Qualcomm Atheros      | 55        | 15.71%  |
| Realtek Semiconductor | 45        | 12.86%  |
| Broadcom              | 30        | 8.57%   |
| MediaTek              | 8         | 2.29%   |
| Ralink Technology     | 6         | 1.71%   |
| Ralink                | 3         | 0.86%   |
| Broadcom Limited      | 3         | 0.86%   |
| Qualcomm              | 2         | 0.57%   |
| Dell                  | 2         | 0.57%   |
| TP-Link               | 1         | 0.29%   |
| NetGear               | 1         | 0.29%   |
| Apple                 | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 21        | 5.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 4.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 4.55%   |
| Intel Wireless 8265 / 8275                                              | 15        | 4.26%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 4.26%   |
| Intel Wireless 7260                                                     | 14        | 3.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 3.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 3.69%   |
| Intel Wireless 8260                                                     | 11        | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.99%   |
| Intel Wireless 3165                                                     | 7         | 1.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.99%   |
| Intel Wireless 7265                                                     | 6         | 1.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.42%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.14%   |
| Intel Wireless 3160                                                     | 4         | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.85%   |
| Intel WiFi Link 5100                                                    | 3         | 0.85%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 151       | 52.43%  |
| Intel                         | 70        | 24.31%  |
| Qualcomm Atheros              | 15        | 5.21%   |
| Broadcom                      | 11        | 3.82%   |
| Nvidia                        | 8         | 2.78%   |
| Broadcom Limited              | 7         | 2.43%   |
| Marvell Technology Group      | 5         | 1.74%   |
| Lenovo                        | 5         | 1.74%   |
| ASIX Electronics              | 5         | 1.74%   |
| Xiaomi                        | 2         | 0.69%   |
| Samsung Electronics           | 2         | 0.69%   |
| Xilinx                        | 1         | 0.35%   |
| T & A Mobile Phones           | 1         | 0.35%   |
| OnePlus Technology (Shenzhen) | 1         | 0.35%   |
| Microsoft                     | 1         | 0.35%   |
| ICS Advent                    | 1         | 0.35%   |
| DisplayLink                   | 1         | 0.35%   |
| 3Com                          | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 32.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 11%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 7.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 6.53%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 2.75%   |
| Nvidia MCP79 Ethernet                                             | 6         | 2.06%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.37%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 1.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.03%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 1.03%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.03%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.03%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.03%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.69%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.69%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.69%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.69%   |
| Xilinx Ethernet controller                                        | 1         | 0.34%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.34%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.34%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.34%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.34%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.34%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 334       | 53.78%  |
| Ethernet | 274       | 44.12%  |
| Modem    | 13        | 2.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 270       | 76.49%  |
| Ethernet | 83        | 23.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 241       | 71.3%   |
| 1     | 92        | 27.22%  |
| 0     | 3         | 0.89%   |
| 3     | 2         | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 290       | 84.8%   |
| Yes  | 52        | 15.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 150       | 55.35%  |
| Realtek Semiconductor           | 23        | 8.49%   |
| Qualcomm Atheros Communications | 16        | 5.9%    |
| IMC Networks                    | 16        | 5.9%    |
| Broadcom                        | 15        | 5.54%   |
| Lite-On Technology              | 13        | 4.8%    |
| Dell                            | 7         | 2.58%   |
| Apple                           | 7         | 2.58%   |
| Hewlett-Packard                 | 5         | 1.85%   |
| Foxconn / Hon Hai               | 5         | 1.85%   |
| Toshiba                         | 4         | 1.48%   |
| Realtek                         | 3         | 1.11%   |
| Cambridge Silicon Radio         | 3         | 1.11%   |
| Foxconn International           | 2         | 0.74%   |
| Ralink                          | 1         | 0.37%   |
| ASUSTek Computer                | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 61        | 22.51%  |
| Intel AX201 Bluetooth                               | 29        | 10.7%   |
| Intel AX200 Bluetooth                               | 20        | 7.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 6.64%   |
| Realtek Bluetooth Radio                             | 15        | 5.54%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 3.69%   |
| IMC Networks Bluetooth Radio                        | 8         | 2.95%   |
| Intel Bluetooth Device                              | 7         | 2.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 2.21%   |
| Intel AX210 Bluetooth                               | 6         | 2.21%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 2.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.85%   |
| Apple Bluetooth Host Controller                     | 5         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.48%   |
| IMC Networks Wireless_Device                        | 4         | 1.48%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.48%   |
| Realtek RTL8821A Bluetooth                          | 3         | 1.11%   |
| Realtek Bluetooth Radio                             | 3         | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.11%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.11%   |
| Dell DW375 Bluetooth Module                         | 3         | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.11%   |
| Toshiba Bluetooth Device                            | 2         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.74%   |
| Lite-On Wireless_Device                             | 2         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.74%   |
| IMC Networks Bluetooth Device                       | 2         | 0.74%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.74%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.74%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.74%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.37%   |
| Toshiba BCM43142A0                                  | 1         | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.37%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.37%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.37%   |
| Lite-On Bluetooth Radio                             | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 264       | 60.41%  |
| Nvidia                | 66        | 15.1%   |
| AMD                   | 66        | 15.1%   |
| Realtek Semiconductor | 10        | 2.29%   |
| Plantronics           | 7         | 1.6%    |
| GN Netcom             | 5         | 1.14%   |
| Logitech              | 3         | 0.69%   |
| Lenovo                | 3         | 0.69%   |
| RODE Microphones      | 2         | 0.46%   |
| C-Media Electronics   | 2         | 0.46%   |
| VIA Technologies      | 1         | 0.23%   |
| Sony                  | 1         | 0.23%   |
| No brand              | 1         | 0.23%   |
| Kingston Technology   | 1         | 0.23%   |
| Huawei Technologies   | 1         | 0.23%   |
| ESS Technology        | 1         | 0.23%   |
| Creative Technology   | 1         | 0.23%   |
| Conexant Systems      | 1         | 0.23%   |
| AUDIOLAB              | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 48        | 9.36%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 33        | 6.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 4.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 4.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 3.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 3.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.34%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 2.34%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.14%   |
| Realtek Semiconductor USB Audio                                                                   | 10        | 1.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 1.95%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 1.56%   |
| Plantronics Poly Voyager Focus 2 Series                                                           | 7         | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.36%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 1.36%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.36%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 1.36%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 1.17%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.97%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.97%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 0.97%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 29.41%  |
| SK hynix            | 46        | 22.55%  |
| Micron Technology   | 25        | 12.25%  |
| Kingston            | 16        | 7.84%   |
| Unknown             | 14        | 6.86%   |
| Crucial             | 12        | 5.88%   |
| Ramaxel Technology  | 6         | 2.94%   |
| Corsair             | 6         | 2.94%   |
| Elpida              | 4         | 1.96%   |
| Unknown (ABCD)      | 3         | 1.47%   |
| Nanya Technology    | 3         | 1.47%   |
| Transcend           | 1         | 0.49%   |
| SHARETRONIC         | 1         | 0.49%   |
| Patriot             | 1         | 0.49%   |
| G.Skill             | 1         | 0.49%   |
| CSX                 | 1         | 0.49%   |
| Apacer              | 1         | 0.49%   |
| A Force             | 1         | 0.49%   |
| 4ea5                | 1         | 0.49%   |
| Unknown             | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 2.79%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 2.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 2.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.86%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.4%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 1.4%    |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 3         | 1.4%    |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 1.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.93%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.93%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.93%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.93%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.93%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.93%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.93%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.93%   |
| Ramaxel RAM RMSA3230KE68H9F2133 4GB SODIMM DDR4 2133MT/s         | 2         | 0.93%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.93%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.93%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.93%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 4GB Chip DDR3 1333MT/s              | 2         | 0.93%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.47%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                         | 1         | 0.47%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.47%   |
| Unknown RAM Module 256MB SODIMM DRAM                             | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 91        | 51.41%  |
| DDR3    | 47        | 26.55%  |
| LPDDR4  | 13        | 7.34%   |
| DDR2    | 9         | 5.08%   |
| LPDDR3  | 5         | 2.82%   |
| SDRAM   | 4         | 2.26%   |
| DDR5    | 3         | 1.69%   |
| DDR     | 2         | 1.13%   |
| LPDDR5  | 1         | 0.56%   |
| DRAM    | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 156       | 86.19%  |
| Row Of Chips | 19        | 10.5%   |
| Chip         | 4         | 2.21%   |
| Unknown      | 2         | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 72        | 37.5%   |
| 4096  | 52        | 27.08%  |
| 16384 | 32        | 16.67%  |
| 2048  | 21        | 10.94%  |
| 1024  | 7         | 3.65%   |
| 32768 | 6         | 3.13%   |
| 256   | 1         | 0.52%   |
| 128   | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 35        | 18.52%  |
| 1600    | 33        | 17.46%  |
| 3200    | 28        | 14.81%  |
| 2400    | 20        | 10.58%  |
| 2133    | 15        | 7.94%   |
| 1334    | 8         | 4.23%   |
| 4267    | 6         | 3.17%   |
| 3266    | 5         | 2.65%   |
| 800     | 5         | 2.65%   |
| 667     | 5         | 2.65%   |
| 1333    | 4         | 2.12%   |
| 1067    | 4         | 2.12%   |
| 8400    | 3         | 1.59%   |
| 4800    | 3         | 1.59%   |
| 1867    | 3         | 1.59%   |
| 4266    | 2         | 1.06%   |
| 4199    | 2         | 1.06%   |
| 975     | 2         | 1.06%   |
| Unknown | 2         | 1.06%   |
| 6400    | 1         | 0.53%   |
| 2267    | 1         | 0.53%   |
| 2048    | 1         | 0.53%   |
| 533     | 1         | 0.53%   |

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
| Chicony Electronics                    | 73        | 24.41%  |
| Realtek Semiconductor                  | 38        | 12.71%  |
| Microdia                               | 32        | 10.7%   |
| IMC Networks                           | 32        | 10.7%   |
| Sunplus Innovation Technology          | 20        | 6.69%   |
| Quanta                                 | 16        | 5.35%   |
| Acer                                   | 15        | 5.02%   |
| Bison Electronics                      | 11        | 3.68%   |
| Logitech                               | 8         | 2.68%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.34%   |
| Apple                                  | 7         | 2.34%   |
| Suyin                                  | 6         | 2.01%   |
| Samsung Electronics                    | 5         | 1.67%   |
| ALi                                    | 5         | 1.67%   |
| Syntek                                 | 4         | 1.34%   |
| Silicon Motion                         | 4         | 1.34%   |
| Lite-On Technology                     | 4         | 1.34%   |
| Ricoh                                  | 3         | 1%      |
| Z-Star Microelectronics                | 1         | 0.33%   |
| Y Media                                | 1         | 0.33%   |
| Trust                                  | 1         | 0.33%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.33%   |
| Nikon                                  | 1         | 0.33%   |
| Luxvisions Innotech Limited            | 1         | 0.33%   |
| Lenovo                                 | 1         | 0.33%   |
| DigiTech                               | 1         | 0.33%   |
| Alcor Micro                            | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD              | 16        | 5.32%   |
| Realtek Integrated_Webcam_HD               | 14        | 4.65%   |
| Chicony Integrated Camera                  | 12        | 3.99%   |
| IMC Networks Integrated Camera             | 11        | 3.65%   |
| Sunplus Integrated_Webcam_FHD              | 8         | 2.66%   |
| Chicony USB2.0 Camera                      | 7         | 2.33%   |
| Chicony HD WebCam                          | 7         | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam          | 6         | 1.99%   |
| Apple Built-in iSight                      | 6         | 1.99%   |
| Acer Integrated Camera                     | 6         | 1.99%   |
| Sunplus Integrated_Webcam_HD               | 5         | 1.66%   |
| Samsung Galaxy series, misc. (MTP mode)    | 5         | 1.66%   |
| Microdia Integrated Webcam                 | 5         | 1.66%   |
| Realtek Integrated Webcam HD               | 4         | 1.33%   |
| Bison Integrated Camera                    | 4         | 1.33%   |
| Realtek USB2.0 HD UVC WebCam               | 3         | 1%      |
| Logitech HD Pro Webcam C920                | 3         | 1%      |
| Lite-On HP HD Camera                       | 3         | 1%      |
| Chicony Lenovo EasyCamera                  | 3         | 1%      |
| Chicony Integrated Camera (1280x720@30)    | 3         | 1%      |
| Chicony HP Wide Vision HD Camera           | 3         | 1%      |
| Chicony HP HD Camera                       | 3         | 1%      |
| ALi WebCam                                 | 3         | 1%      |
| Syntek Integrated Camera                   | 2         | 0.66%   |
| Syntek EasyCamera                          | 2         | 0.66%   |
| Suyin HP Truevision HD                     | 2         | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 2         | 0.66%   |
| Sunplus HP HD Webcam [Fixed]               | 2         | 0.66%   |
| Realtek USB Camera                         | 2         | 0.66%   |
| Realtek Integrated Webcam                  | 2         | 0.66%   |
| Realtek HP Truevision HD integrated webcam | 2         | 0.66%   |
| Realtek HD WebCam                          | 2         | 0.66%   |
| Realtek EasyCamera                         | 2         | 0.66%   |
| Quanta USB2.0 HD UVC WebCam                | 2         | 0.66%   |
| Quanta ov9734_techfront_camera             | 2         | 0.66%   |
| Quanta HP Webcam                           | 2         | 0.66%   |
| Quanta HP HD Camera                        | 2         | 0.66%   |
| Quanta ACER HD User Facing                 | 2         | 0.66%   |
| Microdia Webcam Vitade AF                  | 2         | 0.66%   |
| Microdia USB 2.0 Camera                    | 2         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 22        | 32.35%  |
| Validity Sensors           | 20        | 29.41%  |
| Shenzhen Goodix Technology | 13        | 19.12%  |
| Upek                       | 4         | 5.88%   |
| AuthenTec                  | 3         | 4.41%   |
| LighTuning Technology      | 2         | 2.94%   |
| Elan Microelectronics      | 2         | 2.94%   |
| STMicroelectronics         | 1         | 1.47%   |
| Focal-systems.Corp         | 1         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 8.82%   |
| Shenzhen Goodix FingerPrint                                | 6         | 8.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 7.35%   |
| Unknown                                                    | 5         | 7.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 5.88%   |
| Shenzhen Goodix  Fingerprint Device                        | 4         | 5.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4.41%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 4.41%   |
| AuthenTec Fingerprint Sensor                               | 3         | 4.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 2.94%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 2.94%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 2.94%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 2.94%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 2         | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 2.94%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 2.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.47%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.47%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.47%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.47%   |
| Validity Sensors Synaptics WBDI                            | 1         | 1.47%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.47%   |
| Synaptics WBDI                                             | 1         | 1.47%   |
| Synaptics UWP WBDI Device                                  | 1         | 1.47%   |
| Synaptics  WBDI                                            | 1         | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.47%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 1.47%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.47%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.47%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.47%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 29        | 61.7%   |
| Alcor Micro | 8         | 17.02%  |
| Upek        | 5         | 10.64%  |
| O2 Micro    | 4         | 8.51%   |
| Lenovo      | 1         | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 14        | 29.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 17.02%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 12.77%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 10.64%  |
| Broadcom 5880                                                                | 5         | 10.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 8.51%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6.38%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.13%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 186       | 53.45%  |
| 1     | 127       | 36.49%  |
| 2     | 29        | 8.33%   |
| 3     | 6         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 67        | 34.72%  |
| Chipcard                 | 42        | 21.76%  |
| Graphics card            | 31        | 16.06%  |
| Net/wireless             | 27        | 13.99%  |
| Camera                   | 6         | 3.11%   |
| Storage                  | 5         | 2.59%   |
| Multimedia controller    | 5         | 2.59%   |
| Communication controller | 3         | 1.55%   |
| Card reader              | 3         | 1.55%   |
| Bluetooth                | 3         | 1.55%   |
| Modem                    | 1         | 0.52%   |

