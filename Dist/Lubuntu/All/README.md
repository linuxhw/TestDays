Lubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

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

Total: 1354

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Toshiba       | NB250                       | Notebook    | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | Presario CQ56               | Notebook    | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | Desktop     | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | 900                         | Notebook    | [ae42d40b7a](https://linux-hardware.org/?probe=ae42d40b7a) | Jul 25, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Samsung       | N130                        | Notebook    | [4874e0173d](https://linux-hardware.org/?probe=4874e0173d) | Jul 17, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [21b83125d8](https://linux-hardware.org/?probe=21b83125d8) | Jul 14, 2022 |
| Standard      | AHV                         | Notebook    | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [08b1b304ae](https://linux-hardware.org/?probe=08b1b304ae) | Jul 11, 2022 |
| Foxconn       | 2ACA                        | Desktop     | [92681ef1e5](https://linux-hardware.org/?probe=92681ef1e5) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [dd80f74e85](https://linux-hardware.org/?probe=dd80f74e85) | Jul 05, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [69e4341e99](https://linux-hardware.org/?probe=69e4341e99) | Jul 05, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [92c11e77c4](https://linux-hardware.org/?probe=92c11e77c4) | Jul 03, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| MSI           | VR630                       | Notebook    | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [357e062693](https://linux-hardware.org/?probe=357e062693) | Jun 25, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [f6f825d83a](https://linux-hardware.org/?probe=f6f825d83a) | Jun 22, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [8522c93ea3](https://linux-hardware.org/?probe=8522c93ea3) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [14ed78a258](https://linux-hardware.org/?probe=14ed78a258) | Jun 11, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| MSI           | MS-AA1511                   | All in one  | [80c9ccb7c7](https://linux-hardware.org/?probe=80c9ccb7c7) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | 3397                        | Desktop     | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| HP            | Berknip                     | Notebook    | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| ASUSTek       | X402CA                      | Notebook    | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [7807aa5ed4](https://linux-hardware.org/?probe=7807aa5ed4) | May 16, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Dell          | 0CRH6C A00                  | Desktop     | [fe2648c1f7](https://linux-hardware.org/?probe=fe2648c1f7) | May 14, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [68ee4b094a](https://linux-hardware.org/?probe=68ee4b094a) | May 13, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5774e3f483](https://linux-hardware.org/?probe=5774e3f483) | May 12, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [f3bd3e55aa](https://linux-hardware.org/?probe=f3bd3e55aa) | May 12, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [3a09364bb2](https://linux-hardware.org/?probe=3a09364bb2) | May 12, 2022 |
| Toshiba       | Satellite P20               | Notebook    | [923779da79](https://linux-hardware.org/?probe=923779da79) | May 11, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Positivo      | AT300b                      | Notebook    | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| ASUSTek       | Rampage III GENE            | Desktop     | [798c1f07f6](https://linux-hardware.org/?probe=798c1f07f6) | May 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| ASUSTek       | 900                         | Notebook    | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | Notebook    | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [4682643304](https://linux-hardware.org/?probe=4682643304) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf9f724f45](https://linux-hardware.org/?probe=bf9f724f45) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [05585fedf4](https://linux-hardware.org/?probe=05585fedf4) | May 04, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| Acer          | Aspire XC100A               | Desktop     | [dbad5c417d](https://linux-hardware.org/?probe=dbad5c417d) | May 04, 2022 |
| ASUSTek       | 900                         | Notebook    | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [dd1df3c77d](https://linux-hardware.org/?probe=dd1df3c77d) | May 02, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| Gigabyte      | M912                        | Notebook    | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [b921f6fbae](https://linux-hardware.org/?probe=b921f6fbae) | Apr 24, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| Mediacom      | GTZS                        | Notebook    | [41939828a4](https://linux-hardware.org/?probe=41939828a4) | Apr 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [12d817136f](https://linux-hardware.org/?probe=12d817136f) | Apr 22, 2022 |
| Google        | Droid                       | Notebook    | [b7b4dc6117](https://linux-hardware.org/?probe=b7b4dc6117) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| Mediacom      | GTZS                        | Notebook    | [edc22ef82a](https://linux-hardware.org/?probe=edc22ef82a) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| Dell          | Latitude E6410              | Notebook    | [e5e350a4a8](https://linux-hardware.org/?probe=e5e350a4a8) | Apr 13, 2022 |
| Google        | Kip                         | Notebook    | [4641a94428](https://linux-hardware.org/?probe=4641a94428) | Apr 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [1a369ad73a](https://linux-hardware.org/?probe=1a369ad73a) | Apr 12, 2022 |
| ASRock        | G31M-S                      | Desktop     | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Samsung       | 950QDB                      | Convertible | [41d1bb5ecf](https://linux-hardware.org/?probe=41d1bb5ecf) | Apr 08, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Gigabyte      | Q77M-D2H                    | Desktop     | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Samsung       | N100SP                      | Notebook    | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Acer          | AOA150                      | Notebook    | [a59a005250](https://linux-hardware.org/?probe=a59a005250) | Mar 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| Intel         | W7650                       | Notebook    | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | Desktop     | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [abdf251dcf](https://linux-hardware.org/?probe=abdf251dcf) | Mar 25, 2022 |
| Haier         | U1520EM                     | Notebook    | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [af80d44a27](https://linux-hardware.org/?probe=af80d44a27) | Mar 23, 2022 |
| HP            | Pavilion g7                 | Notebook    | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| IBM           | Unknown                     | Notebook    | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [d4c7ecbc5e](https://linux-hardware.org/?probe=d4c7ecbc5e) | Mar 20, 2022 |
| Acer          | AO751h                      | Notebook    | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| Google        | Celes                       | Notebook    | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [eb7071ed13](https://linux-hardware.org/?probe=eb7071ed13) | Mar 12, 2022 |
| Nvidia        | Tegra                       | Soc         | [3f369fa012](https://linux-hardware.org/?probe=3f369fa012) | Mar 11, 2022 |
| ASRock        | Q1900M                      | Desktop     | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | Notebook    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| ASUSTek       | M2N-SLI                     | Desktop     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [9c8ac31778](https://linux-hardware.org/?probe=9c8ac31778) | Mar 07, 2022 |
| HP            | 3647h                       | Desktop     | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [96416af97f](https://linux-hardware.org/?probe=96416af97f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | Notebook    | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| HP            | 339A                        | Desktop     | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| Insyde        | N116                        | Notebook    | [a6dd43dfb4](https://linux-hardware.org/?probe=a6dd43dfb4) | Feb 21, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Toshiba       | Satellite S55-B             | Notebook    | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Dell          | 0DR845                      | Desktop     | [73ab1563bc](https://linux-hardware.org/?probe=73ab1563bc) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |
| Alienware     | M17                         | Notebook    | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| Pegatron      | Narra6                      | Desktop     | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5601a4d596](https://linux-hardware.org/?probe=5601a4d596) | Feb 14, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [1f9694d47d](https://linux-hardware.org/?probe=1f9694d47d) | Feb 12, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [677d24e366](https://linux-hardware.org/?probe=677d24e366) | Feb 11, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [3731e90788](https://linux-hardware.org/?probe=3731e90788) | Feb 11, 2022 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [b3977cd496](https://linux-hardware.org/?probe=b3977cd496) | Feb 10, 2022 |
| Positivo      | N600                        | Notebook    | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | Notebook    | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| ASUSTek       | Puffer                      | Desktop     | [a14c8ed9ad](https://linux-hardware.org/?probe=a14c8ed9ad) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | Desktop     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [695855f143](https://linux-hardware.org/?probe=695855f143) | Feb 05, 2022 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [661ffedd80](https://linux-hardware.org/?probe=661ffedd80) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4c355aa7c2](https://linux-hardware.org/?probe=4c355aa7c2) | Feb 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [61fc6b2cb0](https://linux-hardware.org/?probe=61fc6b2cb0) | Feb 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| HP            | 0A80h                       | Desktop     | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | Desktop     | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Toshiba       | Satellite C875              | Notebook    | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Insyde        | i101c                       | Notebook    | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| Dell          | 0FJM8V A03                  | Server      | [398f8f6326](https://linux-hardware.org/?probe=398f8f6326) | Feb 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Google        | Peppy                       | Notebook    | [15cd563f21](https://linux-hardware.org/?probe=15cd563f21) | Jan 27, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| ASUSTek       | GL553VW                     | Notebook    | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [1aa2cd2e8f](https://linux-hardware.org/?probe=1aa2cd2e8f) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | Notebook    | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [804b4adedc](https://linux-hardware.org/?probe=804b4adedc) | Jan 15, 2022 |
| Unknown       | K8Upgrade-1689              | Desktop     | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| Dell          | 07N90W A01                  | Desktop     | [c8db7d01bd](https://linux-hardware.org/?probe=c8db7d01bd) | Jan 15, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Nvidia        | Tegra                       | Soc         | [143a4e3c60](https://linux-hardware.org/?probe=143a4e3c60) | Jan 13, 2022 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [79e8f681f1](https://linux-hardware.org/?probe=79e8f681f1) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [847afd8ac5](https://linux-hardware.org/?probe=847afd8ac5) | Jan 12, 2022 |
| Acer          | WG43M                       | Desktop     | [af76e9bcfe](https://linux-hardware.org/?probe=af76e9bcfe) | Jan 12, 2022 |
| Acer          | WG43M                       | Desktop     | [5784b66aee](https://linux-hardware.org/?probe=5784b66aee) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4c24369bb7](https://linux-hardware.org/?probe=4c24369bb7) | Jan 11, 2022 |
| System76      | Lemur Pro                   | Notebook    | [fa22d4610e](https://linux-hardware.org/?probe=fa22d4610e) | Jan 11, 2022 |
| Positivo      | N600                        | Notebook    | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| HP            | Compaq 6910p (GX316UC#AB... | Notebook    | [0ffa23c15e](https://linux-hardware.org/?probe=0ffa23c15e) | Jan 07, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [c8aafbbc8d](https://linux-hardware.org/?probe=c8aafbbc8d) | Jan 04, 2022 |
| Alienware     | m15                         | Notebook    | [a0d4f93250](https://linux-hardware.org/?probe=a0d4f93250) | Jan 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [eaf2e708d9](https://linux-hardware.org/?probe=eaf2e708d9) | Jan 03, 2022 |
| Acer          | Aspire 7715Z                | Notebook    | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | Notebook    | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Dell          | Latitude 7480               | Notebook    | [a338b67d45](https://linux-hardware.org/?probe=a338b67d45) | Dec 30, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Dell          | Inspiron 15 3515            | Notebook    | [8d130910ab](https://linux-hardware.org/?probe=8d130910ab) | Dec 26, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [f5924cb8b4](https://linux-hardware.org/?probe=f5924cb8b4) | Dec 25, 2021 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | Desktop     | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ea7740294a](https://linux-hardware.org/?probe=ea7740294a) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | AOA150                      | Notebook    | [47cae573c1](https://linux-hardware.org/?probe=47cae573c1) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| Dell          | Latitude E6520              | Notebook    | [c7edb79be7](https://linux-hardware.org/?probe=c7edb79be7) | Dec 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [175dda01f6](https://linux-hardware.org/?probe=175dda01f6) | Dec 15, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b956646608](https://linux-hardware.org/?probe=b956646608) | Dec 12, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [7cf21876b0](https://linux-hardware.org/?probe=7cf21876b0) | Dec 12, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [950da990e7](https://linux-hardware.org/?probe=950da990e7) | Dec 12, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [8419e68dd3](https://linux-hardware.org/?probe=8419e68dd3) | Dec 12, 2021 |
| ASUSTek       | 1015BXO                     | Notebook    | [f9eb963d74](https://linux-hardware.org/?probe=f9eb963d74) | Dec 12, 2021 |
| MSI           | Katana GF76 11UC            | Notebook    | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| Positivo      | AT300b                      | Notebook    | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| HP            | Compaq 6510b (GR691EA#AB... | Notebook    | [4d657211eb](https://linux-hardware.org/?probe=4d657211eb) | Dec 04, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ddafe324b7](https://linux-hardware.org/?probe=ddafe324b7) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [e9b454a745](https://linux-hardware.org/?probe=e9b454a745) | Dec 04, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| HP            | 1497                        | Desktop     | [f848ad29cd](https://linux-hardware.org/?probe=f848ad29cd) | Dec 04, 2021 |
| Acer          | AOD255E                     | Notebook    | [390afd35cb](https://linux-hardware.org/?probe=390afd35cb) | Dec 03, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [b096d0494e](https://linux-hardware.org/?probe=b096d0494e) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [edce40927f](https://linux-hardware.org/?probe=edce40927f) | Dec 01, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| ASUSTek       | CM1435                      | Desktop     | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| HP            | Compaq 6720s                | Notebook    | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [0598f63a64](https://linux-hardware.org/?probe=0598f63a64) | Nov 25, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [4528ddf31d](https://linux-hardware.org/?probe=4528ddf31d) | Nov 25, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Gigabyte      | A520I AC                    | Desktop     | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Dell          | Latitude 3330               | Notebook    | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [2f1bc07165](https://linux-hardware.org/?probe=2f1bc07165) | Nov 17, 2021 |
| Medion        | P6630                       | Notebook    | [edc09031bd](https://linux-hardware.org/?probe=edc09031bd) | Nov 16, 2021 |
| HP            | Pavilion dv6                | Notebook    | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | Notebook    | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Dell          | 0T568R A00                  | Desktop     | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| Intel         | S1200BTL E98681-307         | Server      | [13f02631fe](https://linux-hardware.org/?probe=13f02631fe) | Nov 12, 2021 |
| Acer          | Aspire X1700                | Desktop     | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| Acer          | AO751h                      | Notebook    | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [03bba840c5](https://linux-hardware.org/?probe=03bba840c5) | Nov 07, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [25f858c7b1](https://linux-hardware.org/?probe=25f858c7b1) | Nov 05, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| Mediacom      | GTZS                        | Notebook    | [a2a881793d](https://linux-hardware.org/?probe=a2a881793d) | Nov 03, 2021 |
| Foxconn       | 2AA9h                       | Desktop     | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Medion        | MS-7728                     | Desktop     | [564ffdab3d](https://linux-hardware.org/?probe=564ffdab3d) | Nov 02, 2021 |
| HP            | ProBook 4540s               | Notebook    | [fca622f4c4](https://linux-hardware.org/?probe=fca622f4c4) | Nov 01, 2021 |
| Samsung       | R40/R41                     | Notebook    | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [2c6c86b1fb](https://linux-hardware.org/?probe=2c6c86b1fb) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e12d7e47e6](https://linux-hardware.org/?probe=e12d7e47e6) | Oct 31, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f86520f5a7](https://linux-hardware.org/?probe=f86520f5a7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | Notebook    | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| HP            | 2000                        | Notebook    | [65ec913842](https://linux-hardware.org/?probe=65ec913842) | Oct 27, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [45ba0657f1](https://linux-hardware.org/?probe=45ba0657f1) | Oct 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| Samsung       | N100SP                      | Notebook    | [7e4ef50289](https://linux-hardware.org/?probe=7e4ef50289) | Oct 26, 2021 |
| MSI           | MS-7309                     | Desktop     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| Acer          | TravelMate P253             | Notebook    | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Samsung       | N100SP                      | Notebook    | [4d8eadf806](https://linux-hardware.org/?probe=4d8eadf806) | Oct 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Sony          | VGN-CR11Z_R                 | Notebook    | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Acer          | Aspire ES1-131              | Notebook    | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| Intel         | W7650                       | Notebook    | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [15969208ae](https://linux-hardware.org/?probe=15969208ae) | Oct 18, 2021 |
| Unknown       | X99-D8                      | Desktop     | [e335225bdb](https://linux-hardware.org/?probe=e335225bdb) | Oct 17, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | Notebook    | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| NOBLEX        | E11IS2                      | Notebook    | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | 2000                        | Notebook    | [d84546de1b](https://linux-hardware.org/?probe=d84546de1b) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | Desktop     | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| MSI           | B350 TOMAHAWK PLUS          | Desktop     | [acbc75f1b8](https://linux-hardware.org/?probe=acbc75f1b8) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | Desktop     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2f7c2f51f8](https://linux-hardware.org/?probe=2f7c2f51f8) | Oct 01, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| Sony          | VPCSA2FGX                   | Notebook    | [60cfbaebef](https://linux-hardware.org/?probe=60cfbaebef) | Sep 29, 2021 |
| Pegatron      | Acacia                      | Desktop     | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| ZOTAC         | NM10                        | Desktop     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [29a6b45091](https://linux-hardware.org/?probe=29a6b45091) | Sep 26, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [5ed9f083e1](https://linux-hardware.org/?probe=5ed9f083e1) | Sep 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Foxconn       | Priv                        | Desktop     | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | Desktop     | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [c45de8d3b1](https://linux-hardware.org/?probe=c45de8d3b1) | Sep 21, 2021 |
| Toshiba       | Satellite L20               | Notebook    | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [64604612b2](https://linux-hardware.org/?probe=64604612b2) | Sep 19, 2021 |
| ASUSTek       | P8C WS                      | Desktop     | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| Foxconn       | 2AAF                        | Desktop     | [be2ce05253](https://linux-hardware.org/?probe=be2ce05253) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [b50449f73f](https://linux-hardware.org/?probe=b50449f73f) | Sep 14, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [be96e8a7e1](https://linux-hardware.org/?probe=be96e8a7e1) | Sep 13, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [f1414fdf7b](https://linux-hardware.org/?probe=f1414fdf7b) | Sep 13, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Dell          | 01V648 A03                  | Server      | [f46a021c88](https://linux-hardware.org/?probe=f46a021c88) | Sep 02, 2021 |
| Toshiba       | Satellite A215              | Notebook    | [2d0d778e8e](https://linux-hardware.org/?probe=2d0d778e8e) | Aug 31, 2021 |
| Notebook      | NL40_50GU                   | Notebook    | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| Google        | Careena                     | Notebook    | [ab1bafda25](https://linux-hardware.org/?probe=ab1bafda25) | Aug 27, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [50f9ce0180](https://linux-hardware.org/?probe=50f9ce0180) | Aug 26, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [6e1f484406](https://linux-hardware.org/?probe=6e1f484406) | Aug 24, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0fa53c65bb](https://linux-hardware.org/?probe=0fa53c65bb) | Aug 24, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [63b870739f](https://linux-hardware.org/?probe=63b870739f) | Aug 19, 2021 |
| MSI           | 760GM-E51                   | Desktop     | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| Nvidia        | Tegra                       | Soc         | [369b72f0fd](https://linux-hardware.org/?probe=369b72f0fd) | Aug 18, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [bc09a1e988](https://linux-hardware.org/?probe=bc09a1e988) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | Notebook    | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| HP            | Pavilion g4                 | Notebook    | [f1d3ddf197](https://linux-hardware.org/?probe=f1d3ddf197) | Aug 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [239b740235](https://linux-hardware.org/?probe=239b740235) | Aug 03, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| Dell          | Latitude E5450              | Notebook    | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | 8299                        | Desktop     | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Huanan        | X99-TF V2.0                 | Desktop     | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [db933e0ebd](https://linux-hardware.org/?probe=db933e0ebd) | Jul 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [51a121d461](https://linux-hardware.org/?probe=51a121d461) | Jul 24, 2021 |
| Intel         | DG965SS AAD41678-307        | Desktop     | [d3f38dbf63](https://linux-hardware.org/?probe=d3f38dbf63) | Jul 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [d77a8cde0f](https://linux-hardware.org/?probe=d77a8cde0f) | Jul 23, 2021 |
| HP            | 1495                        | Desktop     | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| Dell          | Inspiron M5040              | Notebook    | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Dell          | 0CN7X8 A05                  | Server      | [e5766c8331](https://linux-hardware.org/?probe=e5766c8331) | Jul 22, 2021 |
| HP            | 0A1Ch E                     | Desktop     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | Desktop     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| Sony          | SVE1113M1EW                 | Notebook    | [b01beadd52](https://linux-hardware.org/?probe=b01beadd52) | Jul 16, 2021 |
| Toshiba       | K201                        | Notebook    | [85abf16ca0](https://linux-hardware.org/?probe=85abf16ca0) | Jul 15, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| Google        | Winky                       | Notebook    | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | Notebook    | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [0f8c7a6b66](https://linux-hardware.org/?probe=0f8c7a6b66) | Jul 12, 2021 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [572b814c9a](https://linux-hardware.org/?probe=572b814c9a) | Jul 11, 2021 |
| Medion        | E3216 MD60900               | Convertible | [bc2d5652f6](https://linux-hardware.org/?probe=bc2d5652f6) | Jul 10, 2021 |
| HP            | 3397                        | Desktop     | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| LEADER        | TW9/SW9                     | Notebook    | [6da16947e1](https://linux-hardware.org/?probe=6da16947e1) | Jul 07, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| ASUSTek       | 1015PE                      | Notebook    | [051265df6e](https://linux-hardware.org/?probe=051265df6e) | Jul 05, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [b083bc08c4](https://linux-hardware.org/?probe=b083bc08c4) | Jul 04, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | Notebook    | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| ASUSTek       | P5K                         | Desktop     | [11fed8f8ae](https://linux-hardware.org/?probe=11fed8f8ae) | Jul 03, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| MSI           | GX780R/GT780R/GT780DXR/G... | Notebook    | [212a084b93](https://linux-hardware.org/?probe=212a084b93) | Jul 01, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [2383fe9425](https://linux-hardware.org/?probe=2383fe9425) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| Intel         | DG41WV AAE90316-102         | Desktop     | [c04c0fcc65](https://linux-hardware.org/?probe=c04c0fcc65) | Jun 25, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [5d8e8c301f](https://linux-hardware.org/?probe=5d8e8c301f) | Jun 24, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [8a1c5e9daf](https://linux-hardware.org/?probe=8a1c5e9daf) | Jun 21, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [d94415969c](https://linux-hardware.org/?probe=d94415969c) | Jun 19, 2021 |
| Notebook      | NHxxRZQ                     | Notebook    | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [5e9110ee62](https://linux-hardware.org/?probe=5e9110ee62) | Jun 18, 2021 |
| IBM           | 8183V6D                     | Desktop     | [d5c4e8c76b](https://linux-hardware.org/?probe=d5c4e8c76b) | Jun 18, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | Desktop     | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [b8cf45e412](https://linux-hardware.org/?probe=b8cf45e412) | Jun 15, 2021 |
| Positivo      | Mobile                      | Notebook    | [050aa55013](https://linux-hardware.org/?probe=050aa55013) | Jun 14, 2021 |
| Samsung       | RC512                       | Notebook    | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | Notebook    | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | Notebook    | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [0eb8caf654](https://linux-hardware.org/?probe=0eb8caf654) | Jun 08, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | Notebook    | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | Notebook    | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | Desktop     | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [5824a05a58](https://linux-hardware.org/?probe=5824a05a58) | Jun 05, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [f4ce6e2f6a](https://linux-hardware.org/?probe=f4ce6e2f6a) | Jun 02, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [52c67d407d](https://linux-hardware.org/?probe=52c67d407d) | May 31, 2021 |
| Lenovo        | ThinkPad T410s 2924C39      | Notebook    | [5dc4a1e557](https://linux-hardware.org/?probe=5dc4a1e557) | May 31, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [2e325cddc1](https://linux-hardware.org/?probe=2e325cddc1) | May 30, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [417206cc6a](https://linux-hardware.org/?probe=417206cc6a) | May 30, 2021 |
| Dell          | Latitude D820               | Notebook    | [5b23528d58](https://linux-hardware.org/?probe=5b23528d58) | May 29, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | Latitude D630               | Notebook    | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| ASUSTek       | K8N                         | Desktop     | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | Desktop     | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [3eb7729825](https://linux-hardware.org/?probe=3eb7729825) | May 23, 2021 |
| HP            | 09C4h                       | Desktop     | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| HP            | 21B4 A01                    | Desktop     | [b2a7cbbc72](https://linux-hardware.org/?probe=b2a7cbbc72) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Dell          | 0HY175 A03                  | Desktop     | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | Desktop     | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [bc53ad8072](https://linux-hardware.org/?probe=bc53ad8072) | May 20, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [6e24cb56ad](https://linux-hardware.org/?probe=6e24cb56ad) | May 19, 2021 |
| ASUSTek       | V-P8H67E                    | Desktop     | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | Desktop     | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| HP            | Presario V5000 (ET820UA#... | Notebook    | [f91a752d4d](https://linux-hardware.org/?probe=f91a752d4d) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [e819e51835](https://linux-hardware.org/?probe=e819e51835) | May 18, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [c23a919651](https://linux-hardware.org/?probe=c23a919651) | May 18, 2021 |
| Acer          | Extensa 5620                | Notebook    | [2da2f6a795](https://linux-hardware.org/?probe=2da2f6a795) | May 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| Lenovo        | ThinkPad X240 20AMS2P400    | Notebook    | [9f6e7024d4](https://linux-hardware.org/?probe=9f6e7024d4) | May 13, 2021 |
| MSI           | H61M-E33                    | Desktop     | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| Sony          | VPCSB1V9E                   | Notebook    | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [a54c655ae8](https://linux-hardware.org/?probe=a54c655ae8) | May 12, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [b755c5449a](https://linux-hardware.org/?probe=b755c5449a) | May 11, 2021 |
| ASUSTek       | K8N                         | Desktop     | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| IBM           | ThinkPad Z60m 25303JM       | Notebook    | [c25352d131](https://linux-hardware.org/?probe=c25352d131) | May 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| IBM           | 8183V6D                     | Desktop     | [0df40278d1](https://linux-hardware.org/?probe=0df40278d1) | May 02, 2021 |
| HP            | Notebook                    | Notebook    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [61af9638d2](https://linux-hardware.org/?probe=61af9638d2) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | IMEDIA S1350                | Desktop     | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| ASRock        | FM2A88M Extreme4+           | Desktop     | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [de8b267423](https://linux-hardware.org/?probe=de8b267423) | Apr 25, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [c660d95c3f](https://linux-hardware.org/?probe=c660d95c3f) | Apr 25, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [cf6ec831df](https://linux-hardware.org/?probe=cf6ec831df) | Apr 25, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | Notebook    | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Vostro A90                  | Notebook    | [21b167db8c](https://linux-hardware.org/?probe=21b167db8c) | Apr 25, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Intel         | DX58SO AAE29331-404         | Desktop     | [e4f384c278](https://linux-hardware.org/?probe=e4f384c278) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | Notebook    | [13e1a6028e](https://linux-hardware.org/?probe=13e1a6028e) | Apr 24, 2021 |
| Dell          | Inspiron 7706 2n1           | Convertible | [82eb222c26](https://linux-hardware.org/?probe=82eb222c26) | Apr 23, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Intel Clie... | LAPQC71B                    | Notebook    | [272956b140](https://linux-hardware.org/?probe=272956b140) | Apr 20, 2021 |
| Acer          | Aspire V5-123               | Notebook    | [448b0afd35](https://linux-hardware.org/?probe=448b0afd35) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Toshiba       | Satellite L35               | Notebook    | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| LG Electro... | S425-L.BC22P1               | Notebook    | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | Notebook    | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| HP            | Compaq 6820s                | Notebook    | [551053e9d6](https://linux-hardware.org/?probe=551053e9d6) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | Notebook    | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | Notebook    | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| Toshiba       | Satellite L450              | Notebook    | [2c5ef0687b](https://linux-hardware.org/?probe=2c5ef0687b) | Apr 13, 2021 |
| Intel         | D525MW AAE93082-401         | Desktop     | [aea7beb5c3](https://linux-hardware.org/?probe=aea7beb5c3) | Apr 12, 2021 |
| HP            | EliteBook 8440p (VV954AV... | Notebook    | [3e0b56daf3](https://linux-hardware.org/?probe=3e0b56daf3) | Apr 12, 2021 |
| ASHI          | Unknown                     | Notebook    | [68a2b34c2f](https://linux-hardware.org/?probe=68a2b34c2f) | Apr 12, 2021 |
| HP            | ProBook 6560b               | Notebook    | [8c2a2cfdef](https://linux-hardware.org/?probe=8c2a2cfdef) | Apr 12, 2021 |
| ASUSTek       | P7P55 LX                    | Desktop     | [219757d806](https://linux-hardware.org/?probe=219757d806) | Apr 11, 2021 |
| Toshiba       | Satellite L40               | Notebook    | [0f6ed90100](https://linux-hardware.org/?probe=0f6ed90100) | Apr 11, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [530be6ce7b](https://linux-hardware.org/?probe=530be6ce7b) | Apr 08, 2021 |
| Acer          | Aspire 5715Z                | Notebook    | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | Notebook    | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [a7f2749d3b](https://linux-hardware.org/?probe=a7f2749d3b) | Apr 06, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| MSI           | Boston                      | Desktop     | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6224897fde](https://linux-hardware.org/?probe=6224897fde) | Mar 29, 2021 |
| HP            | 1589                        | Desktop     | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| HP            | 8054                        | Desktop     | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | Desktop     | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [b477c99ab7](https://linux-hardware.org/?probe=b477c99ab7) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| Dell          | Latitude D810               | Notebook    | [ca3886900f](https://linux-hardware.org/?probe=ca3886900f) | Mar 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | Desktop     | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Toshiba       | Satellite L70-B             | Notebook    | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Samsung       | 950QCG                      | Convertible | [657a462187](https://linux-hardware.org/?probe=657a462187) | Mar 21, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| Lenovo        | S10-3                       | Notebook    | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | System XPS 15Z              | Notebook    | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [8ae162d330](https://linux-hardware.org/?probe=8ae162d330) | Mar 16, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [e099627755](https://linux-hardware.org/?probe=e099627755) | Mar 15, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [2abee1f31e](https://linux-hardware.org/?probe=2abee1f31e) | Mar 14, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [821bcfc074](https://linux-hardware.org/?probe=821bcfc074) | Mar 09, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [47a0bdcb00](https://linux-hardware.org/?probe=47a0bdcb00) | Mar 08, 2021 |
| ASUSTek       | P53E                        | Notebook    | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| IBM           | 2647KNG                     | Notebook    | [65d3c4c3c2](https://linux-hardware.org/?probe=65d3c4c3c2) | Mar 07, 2021 |
| IBM           | 2647KNG                     | Notebook    | [e4d4761cfe](https://linux-hardware.org/?probe=e4d4761cfe) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [8273ed53f3](https://linux-hardware.org/?probe=8273ed53f3) | Mar 04, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| MSI           | Boston                      | Desktop     | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| Dell          | Inspiron 1012               | Notebook    | [e66eef020e](https://linux-hardware.org/?probe=e66eef020e) | Mar 03, 2021 |
| Toshiba       | Satellite A135              | Notebook    | [05bbae8a9c](https://linux-hardware.org/?probe=05bbae8a9c) | Mar 02, 2021 |
| MSI           | MS-1453                     | Notebook    | [2be581dfbb](https://linux-hardware.org/?probe=2be581dfbb) | Mar 02, 2021 |
| MSI           | MS-1453                     | Notebook    | [bfaf417259](https://linux-hardware.org/?probe=bfaf417259) | Mar 02, 2021 |
| Toshiba       | Satellite A135              | Notebook    | [1986fa7acf](https://linux-hardware.org/?probe=1986fa7acf) | Mar 02, 2021 |
| Toshiba       | Satellite A660              | Notebook    | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [439d425d4b](https://linux-hardware.org/?probe=439d425d4b) | Mar 01, 2021 |
| Lenovo        | S10-3                       | Notebook    | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | Desktop     | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Acer          | Aspire 5610                 | Notebook    | [1cac0acc28](https://linux-hardware.org/?probe=1cac0acc28) | Feb 25, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [47d5daa739](https://linux-hardware.org/?probe=47d5daa739) | Feb 25, 2021 |
| Itautec       | Infoway w7430               | Notebook    | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | Notebook    | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c8fa1fd6d2](https://linux-hardware.org/?probe=c8fa1fd6d2) | Feb 23, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [bda750c182](https://linux-hardware.org/?probe=bda750c182) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | Notebook    | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | Notebook    | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| ASRock        | 775VM800                    | Desktop     | [5b04151216](https://linux-hardware.org/?probe=5b04151216) | Feb 15, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [e40f1f67bd](https://linux-hardware.org/?probe=e40f1f67bd) | Feb 15, 2021 |
| Dell          | Inspiron 15-3565            | Notebook    | [7c39aa2965](https://linux-hardware.org/?probe=7c39aa2965) | Feb 14, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [0f15feb522](https://linux-hardware.org/?probe=0f15feb522) | Feb 13, 2021 |
| ASRock        | 775VM800                    | Desktop     | [d292f6ac7b](https://linux-hardware.org/?probe=d292f6ac7b) | Feb 12, 2021 |
| Intel         | ChiefRiver                  | Desktop     | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| Intel         | D945GTP AAC97834-305        | Desktop     | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | M2A-MX                      | Desktop     | [1541b0dbe1](https://linux-hardware.org/?probe=1541b0dbe1) | Feb 09, 2021 |
| ASUSTek       | M2A-MX                      | Desktop     | [391d63e436](https://linux-hardware.org/?probe=391d63e436) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [7c78d0efc3](https://linux-hardware.org/?probe=7c78d0efc3) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [beddd7c01d](https://linux-hardware.org/?probe=beddd7c01d) | Feb 09, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [f08dd9c298](https://linux-hardware.org/?probe=f08dd9c298) | Feb 08, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [a8af34d0ee](https://linux-hardware.org/?probe=a8af34d0ee) | Feb 08, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [32061cad93](https://linux-hardware.org/?probe=32061cad93) | Feb 08, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [bcad30556a](https://linux-hardware.org/?probe=bcad30556a) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | Notebook    | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | Notebook    | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| Supermicro    | X8DA3                       | Server      | [039bf2c96a](https://linux-hardware.org/?probe=039bf2c96a) | Feb 04, 2021 |
| Supermicro    | X8DA3                       | Server      | [3731f93e51](https://linux-hardware.org/?probe=3731f93e51) | Feb 04, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [51102bc7a6](https://linux-hardware.org/?probe=51102bc7a6) | Feb 04, 2021 |
| HP            | Pavilion dv6000 (RP154UA... | Notebook    | [44347b7399](https://linux-hardware.org/?probe=44347b7399) | Jan 31, 2021 |
| HP            | 3048h                       | Desktop     | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | Notebook    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| Dell          | 0TP406                      | Desktop     | [8d298a20d5](https://linux-hardware.org/?probe=8d298a20d5) | Jan 28, 2021 |
| HP            | Notebook                    | Notebook    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Lenovo        | ThinkCentre XXXX 9632AU8    | Desktop     | [cdc139f77e](https://linux-hardware.org/?probe=cdc139f77e) | Jan 24, 2021 |
| MSI           | MS-7270                     | Desktop     | [9e5fa11934](https://linux-hardware.org/?probe=9e5fa11934) | Jan 24, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [8cf59ea427](https://linux-hardware.org/?probe=8cf59ea427) | Jan 23, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [19b2ebc706](https://linux-hardware.org/?probe=19b2ebc706) | Jan 22, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [d5121e6efb](https://linux-hardware.org/?probe=d5121e6efb) | Jan 22, 2021 |
| Dell          | Latitude 3440               | Notebook    | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [fdc50253da](https://linux-hardware.org/?probe=fdc50253da) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [3761191ef4](https://linux-hardware.org/?probe=3761191ef4) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [5446971c89](https://linux-hardware.org/?probe=5446971c89) | Jan 20, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| HP            | ProBook 6360b               | Notebook    | [3e3cda2a19](https://linux-hardware.org/?probe=3e3cda2a19) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | Notebook    | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | Notebook    | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [71a9d08996](https://linux-hardware.org/?probe=71a9d08996) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| HP            | Pavilion g6                 | Notebook    | [23360e9a39](https://linux-hardware.org/?probe=23360e9a39) | Jan 12, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [55f1890303](https://linux-hardware.org/?probe=55f1890303) | Jan 11, 2021 |
| Pegatron      | NARRA3                      | Desktop     | [ebb1428c72](https://linux-hardware.org/?probe=ebb1428c72) | Jan 11, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | Notebook    | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3aca8223d6](https://linux-hardware.org/?probe=3aca8223d6) | Jan 09, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [9764fca96a](https://linux-hardware.org/?probe=9764fca96a) | Jan 08, 2021 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [653ea393e6](https://linux-hardware.org/?probe=653ea393e6) | Jan 06, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [266231dab8](https://linux-hardware.org/?probe=266231dab8) | Jan 04, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [4fe52138ff](https://linux-hardware.org/?probe=4fe52138ff) | Jan 04, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [d86f56eaf3](https://linux-hardware.org/?probe=d86f56eaf3) | Jan 04, 2021 |
| MSI           | MS-7250                     | Desktop     | [72950b548d](https://linux-hardware.org/?probe=72950b548d) | Jan 04, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [48edae2fa9](https://linux-hardware.org/?probe=48edae2fa9) | Jan 04, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [412fb4b348](https://linux-hardware.org/?probe=412fb4b348) | Jan 04, 2021 |
| Sony          | VPCYB35AL                   | Notebook    | [f82ea2b0dc](https://linux-hardware.org/?probe=f82ea2b0dc) | Jan 03, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | Notebook    | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [73f8eb43d6](https://linux-hardware.org/?probe=73f8eb43d6) | Jan 01, 2021 |
| Gigabyte      | H81M-HD3                    | Desktop     | [5df1b1d371](https://linux-hardware.org/?probe=5df1b1d371) | Dec 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| eMachines     | EZ1600                      | All in one  | [a9de3eb91d](https://linux-hardware.org/?probe=a9de3eb91d) | Dec 24, 2020 |
| ASRock        | FM2A88X Pro3+               | Desktop     | [a57902b2df](https://linux-hardware.org/?probe=a57902b2df) | Dec 23, 2020 |
| eMachines     | EZ1600                      | All in one  | [7880997578](https://linux-hardware.org/?probe=7880997578) | Dec 23, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | Desktop     | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Sony          | VPCYB35AL                   | Notebook    | [490e3a1b0a](https://linux-hardware.org/?probe=490e3a1b0a) | Dec 23, 2020 |
| Dell          | 0WG864                      | Desktop     | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | Notebook    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | Notebook    | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | Notebook    | [0377183ebd](https://linux-hardware.org/?probe=0377183ebd) | Dec 20, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | Notebook    | [17467ac4ff](https://linux-hardware.org/?probe=17467ac4ff) | Dec 20, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [cdc016f9d1](https://linux-hardware.org/?probe=cdc016f9d1) | Dec 18, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8402e6dc04](https://linux-hardware.org/?probe=8402e6dc04) | Dec 18, 2020 |
| HP            | 3031h                       | Desktop     | [b1c4657359](https://linux-hardware.org/?probe=b1c4657359) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | Notebook    | [88bd8075b2](https://linux-hardware.org/?probe=88bd8075b2) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | Notebook    | [93cfeab463](https://linux-hardware.org/?probe=93cfeab463) | Dec 16, 2020 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [43ba858067](https://linux-hardware.org/?probe=43ba858067) | Dec 16, 2020 |
| Sony          | VGN-S5XP_B                  | Notebook    | [50c6c9d78a](https://linux-hardware.org/?probe=50c6c9d78a) | Dec 15, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [8cf11c15f8](https://linux-hardware.org/?probe=8cf11c15f8) | Dec 13, 2020 |
| ASUSTek       | K53SD                       | Notebook    | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | Notebook    | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Dell          | 0WG864                      | Desktop     | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [8e251a6942](https://linux-hardware.org/?probe=8e251a6942) | Dec 10, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | Notebook    | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| ASUSTek       | X58L                        | Notebook    | [a7fd194aaa](https://linux-hardware.org/?probe=a7fd194aaa) | Dec 07, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f31b40572a](https://linux-hardware.org/?probe=f31b40572a) | Dec 02, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | Desktop     | [19e0a468d5](https://linux-hardware.org/?probe=19e0a468d5) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | Desktop     | [c76fe73c42](https://linux-hardware.org/?probe=c76fe73c42) | Dec 01, 2020 |
| Gigabyte      | W466U                       | Notebook    | [527d2ea4da](https://linux-hardware.org/?probe=527d2ea4da) | Nov 30, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | Desktop     | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [174de8e1d6](https://linux-hardware.org/?probe=174de8e1d6) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [7b85d35e4d](https://linux-hardware.org/?probe=7b85d35e4d) | Nov 29, 2020 |
| Panasonic     | CF-52PGNBE2M                | Notebook    | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| MSI           | P55-GD80                    | Desktop     | [409cb71474](https://linux-hardware.org/?probe=409cb71474) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | Notebook    | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| HP            | 2820h                       | Desktop     | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | Notebook    | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [63776843ec](https://linux-hardware.org/?probe=63776843ec) | Nov 21, 2020 |
| Pegatron      | Narra6                      | Desktop     | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| LG Electro... | C400-G.BG21P1               | Notebook    | [033a9d8cd0](https://linux-hardware.org/?probe=033a9d8cd0) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb11d08947](https://linux-hardware.org/?probe=bb11d08947) | Nov 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [4f73e063d1](https://linux-hardware.org/?probe=4f73e063d1) | Nov 19, 2020 |
| HP            | Pavilion TS 11              | Notebook    | [a71dfc4983](https://linux-hardware.org/?probe=a71dfc4983) | Nov 19, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [86e6b8d3b3](https://linux-hardware.org/?probe=86e6b8d3b3) | Nov 18, 2020 |
| Positivo      | S14BW01                     | Notebook    | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| MSI           | MS-7250                     | Desktop     | [8f408a7fec](https://linux-hardware.org/?probe=8f408a7fec) | Nov 17, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | 09F8h                       | Desktop     | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [dbe623f2ad](https://linux-hardware.org/?probe=dbe623f2ad) | Nov 14, 2020 |
| ECS           | Iris8                       | Desktop     | [1614d7d736](https://linux-hardware.org/?probe=1614d7d736) | Nov 14, 2020 |
| IBM           | 8183V6D                     | Desktop     | [7784e64311](https://linux-hardware.org/?probe=7784e64311) | Nov 14, 2020 |
| ECS           | Iris8                       | Desktop     | [c2d76cebd4](https://linux-hardware.org/?probe=c2d76cebd4) | Nov 14, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Dell          | Inspiron 5423               | Notebook    | [3bd134ed30](https://linux-hardware.org/?probe=3bd134ed30) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| Unknown       | Unknown                     | Notebook    | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| HP            | Unknown                     | Notebook    | [1cee50e485](https://linux-hardware.org/?probe=1cee50e485) | Nov 07, 2020 |
| Sony          | VGN-S5XP_B                  | Notebook    | [62453951ca](https://linux-hardware.org/?probe=62453951ca) | Nov 06, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [20951f6ce6](https://linux-hardware.org/?probe=20951f6ce6) | Nov 05, 2020 |
| Samsung       | SX11S                       | Notebook    | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| HP            | 650                         | Notebook    | [d1e41ec5c0](https://linux-hardware.org/?probe=d1e41ec5c0) | Nov 03, 2020 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | Notebook    | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | Notebook    | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| IBM           | 8183V6D                     | Desktop     | [440a6a1057](https://linux-hardware.org/?probe=440a6a1057) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | Desktop     | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | Desktop     | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [48cb3a624d](https://linux-hardware.org/?probe=48cb3a624d) | Oct 31, 2020 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [3e90cc2ba4](https://linux-hardware.org/?probe=3e90cc2ba4) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [986ac8d550](https://linux-hardware.org/?probe=986ac8d550) | Oct 30, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | Notebook    | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | Notebook    | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | Notebook    | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Alienware     | 13 R3                       | Notebook    | [c0fc10a320](https://linux-hardware.org/?probe=c0fc10a320) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | Notebook    | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | Notebook    | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | Notebook    | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | Notebook    | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Toshiba       | Satellite L30               | Notebook    | [0504cfe362](https://linux-hardware.org/?probe=0504cfe362) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | Notebook    | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Acer          | Aspire F5-573               | Notebook    | [60b785b9cf](https://linux-hardware.org/?probe=60b785b9cf) | Oct 25, 2020 |
| Dell          | 0J3C2F A02                  | Desktop     | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| Acer          | Extensa 4620                | Notebook    | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| ASRock        | G41M-GS3                    | Desktop     | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | Desktop     | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c1a4649fc7](https://linux-hardware.org/?probe=c1a4649fc7) | Oct 20, 2020 |
| HP            | Presario V5000 (RE317EA#... | Notebook    | [87b9f12d09](https://linux-hardware.org/?probe=87b9f12d09) | Oct 19, 2020 |
| HP            | Presario V5000 (RE317EA#... | Notebook    | [e09f71e34f](https://linux-hardware.org/?probe=e09f71e34f) | Oct 19, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [003da597cd](https://linux-hardware.org/?probe=003da597cd) | Oct 19, 2020 |
| Acer          | Aspire E1-532P              | Notebook    | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| ASUSTek       | P5S800-VM                   | Desktop     | [abb4e0e0c2](https://linux-hardware.org/?probe=abb4e0e0c2) | Oct 17, 2020 |
| HP            | Pavilion zd8000 (EL017EA... | Notebook    | [944d295a6b](https://linux-hardware.org/?probe=944d295a6b) | Oct 16, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | Notebook    | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [706aa7bb74](https://linux-hardware.org/?probe=706aa7bb74) | Oct 13, 2020 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [132e2b687c](https://linux-hardware.org/?probe=132e2b687c) | Oct 13, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LG Electro... | C400-G.BG21P1               | Notebook    | [feb6bd4cac](https://linux-hardware.org/?probe=feb6bd4cac) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | Notebook    | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | Notebook    | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| Dell          | 0KRC95 A01                  | Desktop     | [a6576290b5](https://linux-hardware.org/?probe=a6576290b5) | Oct 10, 2020 |
| MSI           | H97M-E35                    | Desktop     | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | Notebook    | [5171d8bc33](https://linux-hardware.org/?probe=5171d8bc33) | Oct 08, 2020 |
| HP            | Pavilion dv6                | Notebook    | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [53ecc0af0c](https://linux-hardware.org/?probe=53ecc0af0c) | Oct 07, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | Notebook    | [5e75a35a7d](https://linux-hardware.org/?probe=5e75a35a7d) | Oct 07, 2020 |
| HP            | Unknown                     | Notebook    | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| HP            | Unknown                     | Notebook    | [3815163813](https://linux-hardware.org/?probe=3815163813) | Oct 06, 2020 |
| MSI           | H110M ECO                   | Desktop     | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [9a5387bb3b](https://linux-hardware.org/?probe=9a5387bb3b) | Oct 04, 2020 |
| Dell          | Latitude D630               | Notebook    | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [bcac6bcfaf](https://linux-hardware.org/?probe=bcac6bcfaf) | Oct 03, 2020 |
| HP            | Laptop 15-da2xxx            | Notebook    | [a071c6ca32](https://linux-hardware.org/?probe=a071c6ca32) | Sep 30, 2020 |
| Biostar       | N61PC-M2S                   | Desktop     | [f41fe9205d](https://linux-hardware.org/?probe=f41fe9205d) | Sep 30, 2020 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| HP            | Pavilion zx5000 (DS416E#... | Notebook    | [adb08b74c2](https://linux-hardware.org/?probe=adb08b74c2) | Sep 28, 2020 |
| Panasonic     | CF-31JAGAX1M                | Notebook    | [50fe0189f0](https://linux-hardware.org/?probe=50fe0189f0) | Sep 27, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [426bdc3586](https://linux-hardware.org/?probe=426bdc3586) | Sep 24, 2020 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Samsung       | N230                        | Notebook    | [d4ba29fa0c](https://linux-hardware.org/?probe=d4ba29fa0c) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Samsung       | N230                        | Notebook    | [786e9275d0](https://linux-hardware.org/?probe=786e9275d0) | Sep 22, 2020 |
| Gateway       | SX2185                      | Desktop     | [7404f09683](https://linux-hardware.org/?probe=7404f09683) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Apple         | MacBook3,1                  | Notebook    | [900daa65d7](https://linux-hardware.org/?probe=900daa65d7) | Sep 20, 2020 |
| Dell          | 0J3C2F A02                  | Desktop     | [c1cbfad587](https://linux-hardware.org/?probe=c1cbfad587) | Sep 20, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| Lenovo        | 3000 N200 0769ALU           | Notebook    | [16fb38706f](https://linux-hardware.org/?probe=16fb38706f) | Sep 17, 2020 |
| ASUSTek       | 1015PE                      | Notebook    | [9328bb0c6a](https://linux-hardware.org/?probe=9328bb0c6a) | Sep 16, 2020 |
| ASUSTek       | X202EP                      | Notebook    | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [bb9ff1e41f](https://linux-hardware.org/?probe=bb9ff1e41f) | Sep 15, 2020 |
| Sony          | VPCEG25EN                   | Notebook    | [10bd76f50c](https://linux-hardware.org/?probe=10bd76f50c) | Sep 14, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [5c305017e8](https://linux-hardware.org/?probe=5c305017e8) | Sep 13, 2020 |
| Acer          | Prespa M                    | Notebook    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| ASRock        | A320M-DGS                   | Desktop     | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| Acer          | Prespa M                    | Notebook    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| HP            | 0A50h                       | Desktop     | [ace0e3fed5](https://linux-hardware.org/?probe=ace0e3fed5) | Sep 13, 2020 |
| HP            | 0A50h                       | Desktop     | [f70b1ce07f](https://linux-hardware.org/?probe=f70b1ce07f) | Sep 12, 2020 |
| ASUSTek       | F7L                         | Notebook    | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | Notebook    | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | Notebook    | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Samsung       | SX11S                       | Notebook    | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | Notebook    | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | Notebook    | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| ASUSTek       | V-P8H67E                    | Desktop     | [a86b68e7e2](https://linux-hardware.org/?probe=a86b68e7e2) | Sep 05, 2020 |
| Google        | Gandof                      | Notebook    | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [18e30a3f69](https://linux-hardware.org/?probe=18e30a3f69) | Sep 02, 2020 |
| Acer          | Aspire ES1-522              | Notebook    | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Acer          | Aspire ES1-523              | Notebook    | [e0afac617e](https://linux-hardware.org/?probe=e0afac617e) | Aug 31, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| Dell          | 0CU409                      | Desktop     | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| Acer          | Aspire ES1-523              | Notebook    | [b0a8136f20](https://linux-hardware.org/?probe=b0a8136f20) | Aug 25, 2020 |
| ASRock        | A320M-HD                    | Desktop     | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [043232c833](https://linux-hardware.org/?probe=043232c833) | Aug 20, 2020 |
| ASUSTek       | K50C                        | Notebook    | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [955c527ef0](https://linux-hardware.org/?probe=955c527ef0) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| Philco        | 14M-W549                    | Notebook    | [d69911bb55](https://linux-hardware.org/?probe=d69911bb55) | Aug 12, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| PCChips       | A13G                        | Desktop     | [d3bc7edc49](https://linux-hardware.org/?probe=d3bc7edc49) | Aug 09, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | Notebook    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Lenovo        | ThinkCentre M58p 7220W21    | Desktop     | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [f8e01e00f5](https://linux-hardware.org/?probe=f8e01e00f5) | Aug 05, 2020 |
| Toshiba       | Satellite L310              | Notebook    | [eba63dd806](https://linux-hardware.org/?probe=eba63dd806) | Aug 03, 2020 |
| Samsung       | N150/N210/N220              | Notebook    | [e15da00326](https://linux-hardware.org/?probe=e15da00326) | Aug 02, 2020 |
| Positivo      | CHT14B                      | Notebook    | [bb848a6069](https://linux-hardware.org/?probe=bb848a6069) | Aug 01, 2020 |
| Philco        | 14F                         | Desktop     | [8fce6fc79b](https://linux-hardware.org/?probe=8fce6fc79b) | Jul 31, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [10a2f3c16b](https://linux-hardware.org/?probe=10a2f3c16b) | Jul 30, 2020 |
| HP            | 245 G6                      | Notebook    | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | K52Je                       | Notebook    | [5e4fd0731b](https://linux-hardware.org/?probe=5e4fd0731b) | Jul 29, 2020 |
| Dell          | Latitude C840               | Notebook    | [5489df545b](https://linux-hardware.org/?probe=5489df545b) | Jul 28, 2020 |
| ASUSTek       | X101CH                      | Notebook    | [92c248f423](https://linux-hardware.org/?probe=92c248f423) | Jul 27, 2020 |
| ASUSTek       | X101CH                      | Notebook    | [a729294016](https://linux-hardware.org/?probe=a729294016) | Jul 27, 2020 |
| Acer          | AO722                       | Notebook    | [75b6a0b9d5](https://linux-hardware.org/?probe=75b6a0b9d5) | Jul 27, 2020 |
| Lenovo        | SDK0E50515 STD              | Desktop     | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| HP            | ProBook 445 G7              | Notebook    | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| Acer          | V5-171                      | Notebook    | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | Desktop     | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| Acer          | Aspire F5-573               | Notebook    | [af6c0b4c67](https://linux-hardware.org/?probe=af6c0b4c67) | Jul 24, 2020 |
| Positivo      | H14BT58                     | Notebook    | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | Notebook    | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | Desktop     | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| HP            | 085Ch                       | Desktop     | [c22eb5394a](https://linux-hardware.org/?probe=c22eb5394a) | Jul 22, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| HP            | 085Ch                       | Desktop     | [a6b75813e8](https://linux-hardware.org/?probe=a6b75813e8) | Jul 20, 2020 |
| IBM           | eServer x3105 -[434722J]... | Desktop     | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | Notebook    | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [03b6eef668](https://linux-hardware.org/?probe=03b6eef668) | Jul 16, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [61727004f5](https://linux-hardware.org/?probe=61727004f5) | Jul 16, 2020 |
| Dell          | Studio 1555                 | Notebook    | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [b97000d1d8](https://linux-hardware.org/?probe=b97000d1d8) | Jul 16, 2020 |
| Dell          | Latitude D520               | Notebook    | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [94cba10ae4](https://linux-hardware.org/?probe=94cba10ae4) | Jul 15, 2020 |
| ASUSTek       | P5S800-VM                   | Desktop     | [214ec41334](https://linux-hardware.org/?probe=214ec41334) | Jul 14, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [448b62138b](https://linux-hardware.org/?probe=448b62138b) | Jul 14, 2020 |
| ASUSTek       | Q302LA                      | Notebook    | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | Notebook    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | Notebook    | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | Notebook    | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | 3396                        | Desktop     | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| Acer          | Swift SF314-52G             | Notebook    | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | Notebook    | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | Notebook    | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | Desktop     | [66d4b86237](https://linux-hardware.org/?probe=66d4b86237) | Jul 01, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | Notebook    | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Toshiba       | Satellite L20               | Notebook    | [06b394c839](https://linux-hardware.org/?probe=06b394c839) | Jun 27, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| ASUSTek       | 1011PX                      | Notebook    | [868f757bd9](https://linux-hardware.org/?probe=868f757bd9) | Jun 25, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | Notebook    | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| OEM           | I41SI                       | Notebook    | [04a393c6ca](https://linux-hardware.org/?probe=04a393c6ca) | Jun 25, 2020 |
| HP            | Compaq 615                  | Notebook    | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| Acer          | Aspire one                  | Notebook    | [3eefd3d4df](https://linux-hardware.org/?probe=3eefd3d4df) | Jun 23, 2020 |
| Acer          | Aspire one                  | Notebook    | [68e2ee0c29](https://linux-hardware.org/?probe=68e2ee0c29) | Jun 23, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| HP            | 304Ah                       | Desktop     | [196b570551](https://linux-hardware.org/?probe=196b570551) | Jun 23, 2020 |
| HP            | 304Ah                       | Desktop     | [bfe838c10f](https://linux-hardware.org/?probe=bfe838c10f) | Jun 23, 2020 |
| ASUSTek       | K52Je                       | Notebook    | [401a42e02d](https://linux-hardware.org/?probe=401a42e02d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f7cfb3c14a](https://linux-hardware.org/?probe=f7cfb3c14a) | Jun 20, 2020 |
| Dell          | 0Y2MRG A00                  | Desktop     | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| OEM           | I41SI                       | Notebook    | [900d32d15b](https://linux-hardware.org/?probe=900d32d15b) | Jun 20, 2020 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [ee1eb9d6fb](https://linux-hardware.org/?probe=ee1eb9d6fb) | Jun 18, 2020 |
| ASUSTek       | M2R-FVM                     | Desktop     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | 09E0h                       | Desktop     | [4979e74209](https://linux-hardware.org/?probe=4979e74209) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| MSI           | 0A48                        | Desktop     | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | 09E0h                       | Desktop     | [3fbd5af0ab](https://linux-hardware.org/?probe=3fbd5af0ab) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [9e786bc6e0](https://linux-hardware.org/?probe=9e786bc6e0) | Jun 12, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [dbbb512dc1](https://linux-hardware.org/?probe=dbbb512dc1) | Jun 11, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [cf72cf6048](https://linux-hardware.org/?probe=cf72cf6048) | Jun 11, 2020 |
| Toshiba       | Satellite L735              | Notebook    | [71df99e435](https://linux-hardware.org/?probe=71df99e435) | Jun 11, 2020 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [b9bd264405](https://linux-hardware.org/?probe=b9bd264405) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Acer          | Aspire 5734Z                | Notebook    | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| Samsung       | RV413/RV513                 | Notebook    | [7c9043ca0a](https://linux-hardware.org/?probe=7c9043ca0a) | Jun 04, 2020 |
| Sony          | VGN-P610                    | Notebook    | [950506fe40](https://linux-hardware.org/?probe=950506fe40) | Jun 04, 2020 |
| HP            | Pavilion 15                 | Notebook    | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| Sony          | VGN-P610                    | Notebook    | [6c66c60336](https://linux-hardware.org/?probe=6c66c60336) | Jun 02, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| Qbex          | HDC-M                       | Desktop     | [5d547380f0](https://linux-hardware.org/?probe=5d547380f0) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | Desktop     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| ASUSTek       | K45VM                       | Notebook    | [15c4339e00](https://linux-hardware.org/?probe=15c4339e00) | May 30, 2020 |
| HP            | Pavilion dv5                | Notebook    | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [6e0b7c86d5](https://linux-hardware.org/?probe=6e0b7c86d5) | May 30, 2020 |
| Dell          | 0PM561 A00                  | All in one  | [9a4a664a94](https://linux-hardware.org/?probe=9a4a664a94) | May 30, 2020 |
| Positivo      | S14CT01                     | Notebook    | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| HP            | Pavilion dv6                | Notebook    | [2431a0aa32](https://linux-hardware.org/?probe=2431a0aa32) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| Dell          | Latitude C840               | Notebook    | [f56665d93f](https://linux-hardware.org/?probe=f56665d93f) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [a3759de413](https://linux-hardware.org/?probe=a3759de413) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [63b8cdead7](https://linux-hardware.org/?probe=63b8cdead7) | May 27, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [26bdbf2454](https://linux-hardware.org/?probe=26bdbf2454) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [cb7235636f](https://linux-hardware.org/?probe=cb7235636f) | May 27, 2020 |
| ASUSTek       | 1015B                       | Notebook    | [0493e9e9bc](https://linux-hardware.org/?probe=0493e9e9bc) | May 27, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| HP            | Pavilion dv6                | Notebook    | [d2b5ccc307](https://linux-hardware.org/?probe=d2b5ccc307) | May 25, 2020 |
| Dell          | Latitude D420               | Notebook    | [40458ce50c](https://linux-hardware.org/?probe=40458ce50c) | May 25, 2020 |
| ASUSTek       | A8N-SLI                     | Desktop     | [5ccefc89ce](https://linux-hardware.org/?probe=5ccefc89ce) | May 23, 2020 |
| ASUSTek       | A8N-SLI                     | Desktop     | [2c0867a9ec](https://linux-hardware.org/?probe=2c0867a9ec) | May 23, 2020 |
| Dell          | Latitude C840               | Notebook    | [94307b80af](https://linux-hardware.org/?probe=94307b80af) | May 22, 2020 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| Positivo      | Smash                       | Notebook    | [662402d21c](https://linux-hardware.org/?probe=662402d21c) | May 22, 2020 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [f231ceaf4a](https://linux-hardware.org/?probe=f231ceaf4a) | May 21, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [4010948e4f](https://linux-hardware.org/?probe=4010948e4f) | May 20, 2020 |
| HP            | 21B4 A01                    | Desktop     | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [bdd3ec7fdf](https://linux-hardware.org/?probe=bdd3ec7fdf) | May 19, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| Gigabyte      | 8I865G775-G                 | Desktop     | [f7d448edb4](https://linux-hardware.org/?probe=f7d448edb4) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [71f901a69f](https://linux-hardware.org/?probe=71f901a69f) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [bce5724752](https://linux-hardware.org/?probe=bce5724752) | May 18, 2020 |
| ASUSTek       | X201E                       | Notebook    | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| ASUSTek       | 1001HA                      | Notebook    | [973de18bf0](https://linux-hardware.org/?probe=973de18bf0) | May 17, 2020 |
| ASUSTek       | 1001HA                      | Notebook    | [ec49101a42](https://linux-hardware.org/?probe=ec49101a42) | May 17, 2020 |
| Packard Be... | EN Butterfly s              | Notebook    | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| ASUSTek       | F5N                         | Notebook    | [19a648832e](https://linux-hardware.org/?probe=19a648832e) | May 15, 2020 |
| Sony          | VGN-NR430E                  | Notebook    | [6e3da2829e](https://linux-hardware.org/?probe=6e3da2829e) | May 15, 2020 |
| Unknown       | P4M800Pro-8237              | Desktop     | [21d6bc116d](https://linux-hardware.org/?probe=21d6bc116d) | May 15, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [0bf3b29d80](https://linux-hardware.org/?probe=0bf3b29d80) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [597e6a2b14](https://linux-hardware.org/?probe=597e6a2b14) | May 14, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | Desktop     | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| Positivo      | EC10IS1                     | Notebook    | [b66b7b1fe1](https://linux-hardware.org/?probe=b66b7b1fe1) | May 12, 2020 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [7af6f2c4d4](https://linux-hardware.org/?probe=7af6f2c4d4) | May 11, 2020 |
| ASUSTek       | F5N                         | Notebook    | [81878f74de](https://linux-hardware.org/?probe=81878f74de) | May 10, 2020 |
| ASUSTek       | P5S800-VM                   | Desktop     | [a4020f35b9](https://linux-hardware.org/?probe=a4020f35b9) | May 10, 2020 |
| Toshiba       | NB505                       | Notebook    | [26eaa80c8a](https://linux-hardware.org/?probe=26eaa80c8a) | May 10, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [0e50f534db](https://linux-hardware.org/?probe=0e50f534db) | May 10, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [794202d954](https://linux-hardware.org/?probe=794202d954) | May 08, 2020 |
| Dell          | Latitude D810               | Notebook    | [7391f06281](https://linux-hardware.org/?probe=7391f06281) | May 07, 2020 |
| Acer          | Aspire XC-703G              | Desktop     | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | Notebook                    | Notebook    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Dell          | Latitude D810               | Notebook    | [da4ecfc379](https://linux-hardware.org/?probe=da4ecfc379) | May 06, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Clevo         | M540SS Bottom               | Notebook    | [d5e1de02bb](https://linux-hardware.org/?probe=d5e1de02bb) | May 05, 2020 |
| Clevo         | M540SS Bottom               | Notebook    | [84338255ae](https://linux-hardware.org/?probe=84338255ae) | May 05, 2020 |
| HP            | 090Ch                       | Desktop     | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP            | 090Ch                       | Desktop     | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| Gigabyte      | GA-K8NF-9                   | Desktop     | [70a90ff062](https://linux-hardware.org/?probe=70a90ff062) | May 04, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [180e7f281b](https://linux-hardware.org/?probe=180e7f281b) | May 03, 2020 |
| Positivo      | Smash                       | Notebook    | [02a9fd0d4a](https://linux-hardware.org/?probe=02a9fd0d4a) | May 03, 2020 |
| Positivo      | Smash                       | Notebook    | [f9734c79af](https://linux-hardware.org/?probe=f9734c79af) | May 03, 2020 |
| VIA Techno... | P4X266-8233                 | Desktop     | [069ba04b1c](https://linux-hardware.org/?probe=069ba04b1c) | May 02, 2020 |
| Toshiba       | TECRA A3X                   | Notebook    | [52ea725f65](https://linux-hardware.org/?probe=52ea725f65) | May 02, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [fd139d35fc](https://linux-hardware.org/?probe=fd139d35fc) | May 01, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| HP            | 17E2                        | Mini pc     | [fe57173b3f](https://linux-hardware.org/?probe=fe57173b3f) | May 01, 2020 |
| Acer          | Extensa 5630                | Notebook    | [2040fe8553](https://linux-hardware.org/?probe=2040fe8553) | Apr 30, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [91d94aa092](https://linux-hardware.org/?probe=91d94aa092) | Apr 30, 2020 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| Toshiba       | TECRA A8                    | Notebook    | [6110d010ad](https://linux-hardware.org/?probe=6110d010ad) | Apr 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [0fc9a3fc11](https://linux-hardware.org/?probe=0fc9a3fc11) | Apr 28, 2020 |
| Packard Be... | EasyNote_GN45               | Notebook    | [a06ff5e1c7](https://linux-hardware.org/?probe=a06ff5e1c7) | Apr 27, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Standard      | EF20EA                      | Notebook    | [11882357e0](https://linux-hardware.org/?probe=11882357e0) | Apr 26, 2020 |
| ASUSTek       | VM40B                       | Desktop     | [acf2922656](https://linux-hardware.org/?probe=acf2922656) | Apr 26, 2020 |
| ASUSTek       | VM40B                       | Desktop     | [2fc777ae6a](https://linux-hardware.org/?probe=2fc777ae6a) | Apr 26, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| Toshiba       | Satellite U500              | Notebook    | [cbb92d0bb3](https://linux-hardware.org/?probe=cbb92d0bb3) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| MSI           | PR200                       | Notebook    | [4da6b718ee](https://linux-hardware.org/?probe=4da6b718ee) | Apr 22, 2020 |
| MSI           | PR200                       | Notebook    | [bd6e464307](https://linux-hardware.org/?probe=bd6e464307) | Apr 22, 2020 |
| Samsung       | 600B4B/600B5B               | Notebook    | [66fdcd74f6](https://linux-hardware.org/?probe=66fdcd74f6) | Apr 22, 2020 |
| MSI           | Boston                      | Desktop     | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| HP            | Compaq CQ58                 | Notebook    | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2acae4110c](https://linux-hardware.org/?probe=2acae4110c) | Apr 20, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [01b278ea81](https://linux-hardware.org/?probe=01b278ea81) | Apr 20, 2020 |
| Acer          | Aspire X1800                | Desktop     | [beb70c1fc5](https://linux-hardware.org/?probe=beb70c1fc5) | Apr 19, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| ASUSTek       | K52Je                       | Notebook    | [2954b09134](https://linux-hardware.org/?probe=2954b09134) | Apr 17, 2020 |
| ASUSTek       | K52Je                       | Notebook    | [bd4175ea08](https://linux-hardware.org/?probe=bd4175ea08) | Apr 17, 2020 |
| Toshiba       | NB505                       | Notebook    | [174dd8b4cd](https://linux-hardware.org/?probe=174dd8b4cd) | Apr 16, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [4998a5a5b5](https://linux-hardware.org/?probe=4998a5a5b5) | Apr 15, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [6500bad3f7](https://linux-hardware.org/?probe=6500bad3f7) | Apr 14, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [c263eac3e9](https://linux-hardware.org/?probe=c263eac3e9) | Apr 13, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [75fff2a0a6](https://linux-hardware.org/?probe=75fff2a0a6) | Apr 13, 2020 |
| Toshiba       | NB505                       | Notebook    | [a28c9ef432](https://linux-hardware.org/?probe=a28c9ef432) | Apr 12, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [6c0d513235](https://linux-hardware.org/?probe=6c0d513235) | Apr 12, 2020 |
| ASUSTek       | A6R                         | Notebook    | [e298b642f1](https://linux-hardware.org/?probe=e298b642f1) | Apr 11, 2020 |
| eMachines     | EL1360G                     | Desktop     | [53d061d3b2](https://linux-hardware.org/?probe=53d061d3b2) | Apr 11, 2020 |
| Ematic        | EW147                       | Notebook    | [ea27684494](https://linux-hardware.org/?probe=ea27684494) | Apr 11, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| Ematic        | EW147                       | Notebook    | [a6d2f7cfcf](https://linux-hardware.org/?probe=a6d2f7cfcf) | Apr 11, 2020 |
| Phoenix/Si... | M7X0SU                      | Notebook    | [c86682fc32](https://linux-hardware.org/?probe=c86682fc32) | Apr 11, 2020 |
| Dell          | 0MM599                      | Desktop     | [19e2d2af44](https://linux-hardware.org/?probe=19e2d2af44) | Apr 11, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [05de338581](https://linux-hardware.org/?probe=05de338581) | Apr 09, 2020 |
| ASUSTek       | 1000H                       | Notebook    | [ee3f7c6ddc](https://linux-hardware.org/?probe=ee3f7c6ddc) | Apr 09, 2020 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [77cf46ddde](https://linux-hardware.org/?probe=77cf46ddde) | Apr 06, 2020 |
| Toshiba       | NB505                       | Notebook    | [c52e8296ad](https://linux-hardware.org/?probe=c52e8296ad) | Apr 06, 2020 |
| HP            | Pavilion 15                 | Notebook    | [b7c8f5e391](https://linux-hardware.org/?probe=b7c8f5e391) | Apr 05, 2020 |
| HP            | Pavilion 15                 | Notebook    | [812ce15917](https://linux-hardware.org/?probe=812ce15917) | Apr 05, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [053784b92f](https://linux-hardware.org/?probe=053784b92f) | Apr 03, 2020 |
| Gigabyte      | nForce                      | Desktop     | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [7759201b72](https://linux-hardware.org/?probe=7759201b72) | Apr 03, 2020 |
| HP            | Pavilion dm1                | Notebook    | [f3ade8b8f4](https://linux-hardware.org/?probe=f3ade8b8f4) | Apr 02, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [8e8dbf13fb](https://linux-hardware.org/?probe=8e8dbf13fb) | Mar 30, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [d60d4df102](https://linux-hardware.org/?probe=d60d4df102) | Mar 29, 2020 |
| Itautec       | Infoway                     | Notebook    | [6df484929a](https://linux-hardware.org/?probe=6df484929a) | Mar 28, 2020 |
| Dell          | 0WG864                      | Desktop     | [092ae3a8ca](https://linux-hardware.org/?probe=092ae3a8ca) | Mar 27, 2020 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [548577276f](https://linux-hardware.org/?probe=548577276f) | Mar 27, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [daf3f5783d](https://linux-hardware.org/?probe=daf3f5783d) | Mar 27, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [b01aa90028](https://linux-hardware.org/?probe=b01aa90028) | Mar 26, 2020 |
| Dell          | Inspiron 910                | Notebook    | [5a445b86f5](https://linux-hardware.org/?probe=5a445b86f5) | Mar 26, 2020 |
| Sony          | VGN-CS325J                  | Notebook    | [a2f2fc1b18](https://linux-hardware.org/?probe=a2f2fc1b18) | Mar 25, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [cdcf191c24](https://linux-hardware.org/?probe=cdcf191c24) | Mar 25, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [f7fb11c89f](https://linux-hardware.org/?probe=f7fb11c89f) | Mar 25, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [be88d1499a](https://linux-hardware.org/?probe=be88d1499a) | Mar 25, 2020 |
| ASUSTek       | A8V-MQ                      | Desktop     | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| Sony          | VGN-CS325J                  | Notebook    | [628add2bae](https://linux-hardware.org/?probe=628add2bae) | Mar 23, 2020 |
| Sony          | VGN-FE21M                   | Notebook    | [b117ba3f2f](https://linux-hardware.org/?probe=b117ba3f2f) | Mar 22, 2020 |
| Sony          | VGN-CS325J                  | Notebook    | [3eeafc3bdb](https://linux-hardware.org/?probe=3eeafc3bdb) | Mar 22, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b65f9246d0](https://linux-hardware.org/?probe=b65f9246d0) | Mar 21, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [a02304934f](https://linux-hardware.org/?probe=a02304934f) | Mar 21, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [e4588ca61a](https://linux-hardware.org/?probe=e4588ca61a) | Mar 21, 2020 |
| Acer          | Aspire E1-431               | Notebook    | [7a4eb7e049](https://linux-hardware.org/?probe=7a4eb7e049) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | Notebook    | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | Notebook    | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [210babb2ca](https://linux-hardware.org/?probe=210babb2ca) | Mar 19, 2020 |
| Thomson       | NEO14A-4BK64                | Notebook    | [a0cc23a5cf](https://linux-hardware.org/?probe=a0cc23a5cf) | Mar 19, 2020 |
| Thomson       | NEO14A-4BK64                | Notebook    | [38b21006a6](https://linux-hardware.org/?probe=38b21006a6) | Mar 19, 2020 |
| Dell          | Inspiron 910                | Notebook    | [40deae1721](https://linux-hardware.org/?probe=40deae1721) | Mar 18, 2020 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2cdafa2543](https://linux-hardware.org/?probe=2cdafa2543) | Mar 17, 2020 |
| Dell          | 0T287N A03                  | Desktop     | [02ebc6d299](https://linux-hardware.org/?probe=02ebc6d299) | Mar 16, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [d7eb29abd9](https://linux-hardware.org/?probe=d7eb29abd9) | Mar 13, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [3746f6db56](https://linux-hardware.org/?probe=3746f6db56) | Mar 12, 2020 |
| ASUSTek       | 1001PXD                     | Notebook    | [011393aea9](https://linux-hardware.org/?probe=011393aea9) | Mar 12, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | X51R                        | Notebook    | [27bb6f3f14](https://linux-hardware.org/?probe=27bb6f3f14) | Mar 11, 2020 |
| Dell          | Inspiron 910                | Notebook    | [b8ec7ce084](https://linux-hardware.org/?probe=b8ec7ce084) | Mar 10, 2020 |
| Acer          | Aspire ES1-571              | Notebook    | [6fa4f9484a](https://linux-hardware.org/?probe=6fa4f9484a) | Mar 10, 2020 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [c00f70d6a6](https://linux-hardware.org/?probe=c00f70d6a6) | Mar 10, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| Acer          | Aspire ES1-571              | Notebook    | [7980f53bfc](https://linux-hardware.org/?probe=7980f53bfc) | Mar 10, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [709a2484bc](https://linux-hardware.org/?probe=709a2484bc) | Mar 09, 2020 |
| Acer          | Aspire 6930G                | Notebook    | [0ec678525f](https://linux-hardware.org/?probe=0ec678525f) | Mar 09, 2020 |
| Dell          | Inspiron 1464               | Notebook    | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Sony          | VPCYB15AB                   | Notebook    | [af5e9fd3c4](https://linux-hardware.org/?probe=af5e9fd3c4) | Mar 03, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [db39fea346](https://linux-hardware.org/?probe=db39fea346) | Mar 02, 2020 |
| Positivo      | Mobile                      | Notebook    | [3dc5b2844f](https://linux-hardware.org/?probe=3dc5b2844f) | Feb 29, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [168bd28370](https://linux-hardware.org/?probe=168bd28370) | Feb 27, 2020 |
| Positivo      | Mobile                      | Notebook    | [6908d01959](https://linux-hardware.org/?probe=6908d01959) | Feb 26, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| ASUSTek       | CUSL2-M                     | Desktop     | [a20a268bb5](https://linux-hardware.org/?probe=a20a268bb5) | Feb 23, 2020 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [d44a499c90](https://linux-hardware.org/?probe=d44a499c90) | Feb 21, 2020 |
| Dell          | 08HPGT A01                  | Desktop     | [64e6dd4ba1](https://linux-hardware.org/?probe=64e6dd4ba1) | Feb 20, 2020 |
| Toshiba       | Satellite C650D             | Notebook    | [fff96c147a](https://linux-hardware.org/?probe=fff96c147a) | Feb 20, 2020 |
| Dell          | Latitude D630               | Notebook    | [81239fd39f](https://linux-hardware.org/?probe=81239fd39f) | Feb 19, 2020 |
| ASUSTek       | 1005HA                      | Notebook    | [0f5187ce04](https://linux-hardware.org/?probe=0f5187ce04) | Feb 18, 2020 |
| HP            | Stream Notebook             | Notebook    | [413af6cde9](https://linux-hardware.org/?probe=413af6cde9) | Feb 18, 2020 |
| HP            | Stream Notebook             | Notebook    | [305ee95288](https://linux-hardware.org/?probe=305ee95288) | Feb 18, 2020 |
| HP            | Stream Notebook             | Notebook    | [3cc3c65c80](https://linux-hardware.org/?probe=3cc3c65c80) | Feb 18, 2020 |
| Acer          | AOD257                      | Notebook    | [42c2447bcf](https://linux-hardware.org/?probe=42c2447bcf) | Feb 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [147eea4e00](https://linux-hardware.org/?probe=147eea4e00) | Feb 17, 2020 |
| Acer          | Aspire 9420                 | Notebook    | [eb72545df3](https://linux-hardware.org/?probe=eb72545df3) | Feb 13, 2020 |
| Acer          | Aspire 9420                 | Notebook    | [7321cd7d41](https://linux-hardware.org/?probe=7321cd7d41) | Feb 13, 2020 |
| HP            | 0A64h                       | Desktop     | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| Samsung       | 275E4E/275E5E               | Notebook    | [15d64735e6](https://linux-hardware.org/?probe=15d64735e6) | Feb 07, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [064e671b09](https://linux-hardware.org/?probe=064e671b09) | Feb 07, 2020 |
| HP            | 0A64h                       | Desktop     | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [9f00848eda](https://linux-hardware.org/?probe=9f00848eda) | Feb 06, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [00e62f0a24](https://linux-hardware.org/?probe=00e62f0a24) | Feb 04, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [c8da6705be](https://linux-hardware.org/?probe=c8da6705be) | Feb 02, 2020 |
| Acer          | Lugano M                    | Notebook    | [312fa4b009](https://linux-hardware.org/?probe=312fa4b009) | Feb 02, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [10e8be6a70](https://linux-hardware.org/?probe=10e8be6a70) | Feb 02, 2020 |
| Acer          | Aspire E1-530               | Notebook    | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| ASRock        | N73V-S                      | Desktop     | [80b08d6e38](https://linux-hardware.org/?probe=80b08d6e38) | Jan 27, 2020 |
| ASRock        | N73V-S                      | Desktop     | [1f67c1102b](https://linux-hardware.org/?probe=1f67c1102b) | Jan 26, 2020 |
| Gigabyte      | GA-K8NF-9                   | Desktop     | [2b8833407a](https://linux-hardware.org/?probe=2b8833407a) | Jan 25, 2020 |
| MSI           | MS-7369                     | Desktop     | [5c6d33ae36](https://linux-hardware.org/?probe=5c6d33ae36) | Jan 25, 2020 |
| Dell          | Vostro A90                  | Notebook    | [ea2668497d](https://linux-hardware.org/?probe=ea2668497d) | Jan 25, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [cc1a05b68f](https://linux-hardware.org/?probe=cc1a05b68f) | Jan 24, 2020 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [88961c610a](https://linux-hardware.org/?probe=88961c610a) | Jan 23, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [179223c787](https://linux-hardware.org/?probe=179223c787) | Jan 21, 2020 |
| TrekStor      | Surfbook A13B               | Notebook    | [a5b513e810](https://linux-hardware.org/?probe=a5b513e810) | Jan 18, 2020 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [97cfb25196](https://linux-hardware.org/?probe=97cfb25196) | Jan 17, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [5619d74a6f](https://linux-hardware.org/?probe=5619d74a6f) | Jan 13, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [d96168ded2](https://linux-hardware.org/?probe=d96168ded2) | Jan 12, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [947354716f](https://linux-hardware.org/?probe=947354716f) | Jan 07, 2020 |
| HP            | 82DD                        | All in one  | [4cb5c7afef](https://linux-hardware.org/?probe=4cb5c7afef) | Jan 05, 2020 |
| Acer          | Aspire 5542                 | Notebook    | [aeeb077808](https://linux-hardware.org/?probe=aeeb077808) | Jan 05, 2020 |
| Acer          | Aspire 5542                 | Notebook    | [1458705a5f](https://linux-hardware.org/?probe=1458705a5f) | Jan 04, 2020 |
| HP            | 0AA8h                       | Desktop     | [77b5333591](https://linux-hardware.org/?probe=77b5333591) | Jan 04, 2020 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [b3b0d2e40e](https://linux-hardware.org/?probe=b3b0d2e40e) | Dec 30, 2019 |
| HP            | Pavilion dv7                | Notebook    | [1147f13741](https://linux-hardware.org/?probe=1147f13741) | Dec 30, 2019 |
| Dell          | Studio 1555                 | Notebook    | [4507496780](https://linux-hardware.org/?probe=4507496780) | Dec 29, 2019 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [aca2eac05b](https://linux-hardware.org/?probe=aca2eac05b) | Dec 29, 2019 |
| Dell          | Studio 1555                 | Notebook    | [9aba9666d7](https://linux-hardware.org/?probe=9aba9666d7) | Dec 28, 2019 |
| HP            | Pavilion 15                 | Notebook    | [98e4efccb2](https://linux-hardware.org/?probe=98e4efccb2) | Dec 24, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| Toshiba       | Satellite L20               | Notebook    | [563f05aae7](https://linux-hardware.org/?probe=563f05aae7) | Dec 18, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| HP            | Compaq Presario CQ50        | Notebook    | [d672b4583e](https://linux-hardware.org/?probe=d672b4583e) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [3a1243a77f](https://linux-hardware.org/?probe=3a1243a77f) | Dec 12, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [71a8ef2f9c](https://linux-hardware.org/?probe=71a8ef2f9c) | Dec 12, 2019 |
| AAEON         | MF-001 V1.0                 | Desktop     | [08480474f8](https://linux-hardware.org/?probe=08480474f8) | Dec 08, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [74039c6d39](https://linux-hardware.org/?probe=74039c6d39) | Dec 01, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [36a930502d](https://linux-hardware.org/?probe=36a930502d) | Nov 30, 2019 |
| Toshiba       | Satellite Pro S500          | Notebook    | [03ab084bc4](https://linux-hardware.org/?probe=03ab084bc4) | Nov 30, 2019 |
| ASUSTek       | X51RL                       | Notebook    | [2d4367bb57](https://linux-hardware.org/?probe=2d4367bb57) | Nov 29, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [4e229f13aa](https://linux-hardware.org/?probe=4e229f13aa) | Nov 23, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [3bf663653b](https://linux-hardware.org/?probe=3bf663653b) | Nov 23, 2019 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0c7973b78](https://linux-hardware.org/?probe=c0c7973b78) | Nov 20, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [fd9a3df2b6](https://linux-hardware.org/?probe=fd9a3df2b6) | Nov 19, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c4b7195697](https://linux-hardware.org/?probe=c4b7195697) | Nov 18, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [c382fdc34a](https://linux-hardware.org/?probe=c382fdc34a) | Nov 14, 2019 |
| Sony          | SVE14A2V1EW                 | Notebook    | [e80c47963a](https://linux-hardware.org/?probe=e80c47963a) | Nov 12, 2019 |
| ASRock        | H55M                        | Desktop     | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | Desktop     | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| Acer          | Aspire XC-703               | Desktop     | [5e3493c08f](https://linux-hardware.org/?probe=5e3493c08f) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | Desktop     | [d31b932863](https://linux-hardware.org/?probe=d31b932863) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | Desktop     | [0a5f0a6adc](https://linux-hardware.org/?probe=0a5f0a6adc) | Nov 11, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [2e7b8ff7ae](https://linux-hardware.org/?probe=2e7b8ff7ae) | Nov 11, 2019 |
| ASUSTek       | U32U                        | Notebook    | [656773dca2](https://linux-hardware.org/?probe=656773dca2) | Oct 22, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [59fbd049bb](https://linux-hardware.org/?probe=59fbd049bb) | Aug 25, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | Desktop     | [0b0497458b](https://linux-hardware.org/?probe=0b0497458b) | Aug 22, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [d85c2d26cb](https://linux-hardware.org/?probe=d85c2d26cb) | Jul 26, 2019 |
| Acer          | Aspire one 1-431            | Notebook    | [33ff5f5399](https://linux-hardware.org/?probe=33ff5f5399) | Jul 14, 2019 |
| ASRock        | AD525PV3                    | Desktop     | [682bc26535](https://linux-hardware.org/?probe=682bc26535) | Jul 03, 2019 |
| ASUSTek       | 1215B                       | Notebook    | [5e3f89149f](https://linux-hardware.org/?probe=5e3f89149f) | Jun 29, 2019 |
| HP            | ProBook 430 G1              | Notebook    | [9be61e9a2d](https://linux-hardware.org/?probe=9be61e9a2d) | Jun 24, 2019 |
| Dell          | Inspiron 5566               | Notebook    | [a8122ef82d](https://linux-hardware.org/?probe=a8122ef82d) | Apr 26, 2019 |
| ASUSTek       | K55VJ                       | Notebook    | [fac5cee3e3](https://linux-hardware.org/?probe=fac5cee3e3) | Apr 05, 2019 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [b99ee7c099](https://linux-hardware.org/?probe=b99ee7c099) | Apr 02, 2019 |
| Dell          | Inspiron 5566               | Notebook    | [e4dc78de4f](https://linux-hardware.org/?probe=e4dc78de4f) | Mar 28, 2019 |
| ASUSTek       | M2N4-SLI                    | Desktop     | [84abf7384b](https://linux-hardware.org/?probe=84abf7384b) | Mar 24, 2019 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [81ac047bce](https://linux-hardware.org/?probe=81ac047bce) | Mar 10, 2019 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [26ccc6c647](https://linux-hardware.org/?probe=26ccc6c647) | Mar 10, 2019 |
| Unknown       | Unknown                     | Desktop     | [52b4b037a1](https://linux-hardware.org/?probe=52b4b037a1) | Feb 01, 2019 |
| Unknown       | Unknown                     | Desktop     | [f9908c15ca](https://linux-hardware.org/?probe=f9908c15ca) | Feb 01, 2019 |
| Acer          | Aspire F5-771G              | Notebook    | [8f2bbcbea8](https://linux-hardware.org/?probe=8f2bbcbea8) | Dec 23, 2018 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [b54d9c9c47](https://linux-hardware.org/?probe=b54d9c9c47) | Dec 19, 2018 |
| PCWare        | IPX1800G2                   | Desktop     | [1721a635e2](https://linux-hardware.org/?probe=1721a635e2) | Nov 25, 2018 |
| Toshiba       | Satellite L20               | Notebook    | [409df1d9a6](https://linux-hardware.org/?probe=409df1d9a6) | Oct 30, 2018 |
| Toshiba       | Satellite L300              | Notebook    | [c50c4eed87](https://linux-hardware.org/?probe=c50c4eed87) | Sep 02, 2018 |
| ASUSTek       | X200MA                      | Notebook    | [62851925f7](https://linux-hardware.org/?probe=62851925f7) | Jul 27, 2018 |
| Lenovo        | G580 20150                  | Notebook    | [69369b93d2](https://linux-hardware.org/?probe=69369b93d2) | Jul 09, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Lubuntu 20.04   | 393       | 41.63%  |
| Lubuntu 18.04   | 194       | 20.55%  |
| Lubuntu 21.10   | 78        | 8.26%   |
| Lubuntu 19.10   | 62        | 6.57%   |
| Lubuntu 22.04   | 56        | 5.93%   |
| Lubuntu 21.04   | 52        | 5.51%   |
| Lubuntu 20.10   | 47        | 4.98%   |
| Lubuntu 16.04   | 27        | 2.86%   |
| Lubuntu 19.04   | 14        | 1.48%   |
| Lubuntu 18.10   | 11        | 1.17%   |
| Lubuntu         | 3         | 0.32%   |
| Lubuntu 16.10   | 2         | 0.21%   |
| Lubuntu 22.10   | 1         | 0.11%   |
| Lubuntu 20.04.1 | 1         | 0.11%   |
| Lubuntu 17.10   | 1         | 0.11%   |
| Lubuntu 17.04   | 1         | 0.11%   |
| Lubuntu 12.04   | 1         | 0.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 921       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 37        | 3.58%   |
| 5.4.0-52-generic   | 24        | 2.32%   |
| 5.13.0-19-generic  | 18        | 1.74%   |
| 5.13.0-28-generic  | 16        | 1.55%   |
| 5.13.0-40-generic  | 15        | 1.45%   |
| 5.4.0-48-generic   | 14        | 1.35%   |
| 5.4.0-47-generic   | 14        | 1.35%   |
| 5.3.0-46-generic   | 14        | 1.35%   |
| 5.11.0-16-generic  | 14        | 1.35%   |
| 5.4.0-26-generic   | 12        | 1.16%   |
| 5.15.0-41-generic  | 12        | 1.16%   |
| 5.13.0-30-generic  | 12        | 1.16%   |
| 5.8.0-50-generic   | 11        | 1.06%   |
| 5.4.0-54-generic   | 11        | 1.06%   |
| 5.4.0-40-generic   | 11        | 1.06%   |
| 5.13.0-35-generic  | 11        | 1.06%   |
| 5.11.0-27-generic  | 11        | 1.06%   |
| 5.4.0-73-generic   | 10        | 0.97%   |
| 5.4.0-29-generic   | 10        | 0.97%   |
| 5.3.0-18-generic   | 10        | 0.97%   |
| 5.15.0-30-generic  | 10        | 0.97%   |
| 5.8.0-63-generic   | 9         | 0.87%   |
| 5.4.0-72-generic   | 9         | 0.87%   |
| 5.4.0-65-generic   | 9         | 0.87%   |
| 5.4.0-33-generic   | 9         | 0.87%   |
| 5.3.0-51-generic   | 9         | 0.87%   |
| 5.3.0-42-generic   | 9         | 0.87%   |
| 5.3.0-40-generic   | 9         | 0.87%   |
| 5.15.0-27-generic  | 9         | 0.87%   |
| 4.15.0-96-generic  | 9         | 0.87%   |
| 4.15.0-91-generic  | 9         | 0.87%   |
| 4.15.0-112-generic | 9         | 0.87%   |
| 5.11.0-38-generic  | 8         | 0.77%   |
| 5.11.0-37-generic  | 8         | 0.77%   |
| 5.11.0-25-generic  | 8         | 0.77%   |
| 5.8.0-53-generic   | 7         | 0.68%   |
| 5.8.0-49-generic   | 7         | 0.68%   |
| 5.8.0-45-generic   | 7         | 0.68%   |
| 5.8.0-41-generic   | 7         | 0.68%   |
| 5.4.0-58-generic   | 7         | 0.68%   |
| 5.4.0-37-generic   | 7         | 0.68%   |
| 5.15.0-25-generic  | 7         | 0.68%   |
| 5.13.0-22-generic  | 7         | 0.68%   |
| 5.11.0-41-generic  | 7         | 0.68%   |
| 5.11.0-17-generic  | 7         | 0.68%   |
| 4.15.0-106-generic | 7         | 0.68%   |
| 5.8.0-59-generic   | 6         | 0.58%   |
| 5.8.0-55-generic   | 6         | 0.58%   |
| 5.8.0-48-generic   | 6         | 0.58%   |
| 5.4.0-91-generic   | 6         | 0.58%   |
| 5.4.0-89-generic   | 6         | 0.58%   |
| 5.4.0-77-generic   | 6         | 0.58%   |
| 5.4.0-67-generic   | 6         | 0.58%   |
| 5.4.0-66-generic   | 6         | 0.58%   |
| 5.4.0-60-generic   | 6         | 0.58%   |
| 5.4.0-59-generic   | 6         | 0.58%   |
| 5.4.0-51-generic   | 6         | 0.58%   |
| 5.13.0-27-generic  | 6         | 0.58%   |
| 5.11.0-43-generic  | 6         | 0.58%   |
| 5.11.0-40-generic  | 6         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 292       | 30.67%  |
| 4.15.0   | 129       | 13.55%  |
| 5.13.0   | 116       | 12.18%  |
| 5.11.0   | 98        | 10.29%  |
| 5.8.0    | 97        | 10.19%  |
| 5.3.0    | 86        | 9.03%   |
| 5.15.0   | 62        | 6.51%   |
| 5.0.0    | 22        | 2.31%   |
| 4.18.0   | 11        | 1.16%   |
| 4.4.0    | 8         | 0.84%   |
| 5.6.0    | 2         | 0.21%   |
| 4.9.253  | 2         | 0.21%   |
| 4.8.0    | 2         | 0.21%   |
| 4.13.0   | 2         | 0.21%   |
| 4.10.0   | 2         | 0.21%   |
| 5.9.0    | 1         | 0.11%   |
| 5.7.9    | 1         | 0.11%   |
| 5.7.0    | 1         | 0.11%   |
| 5.6.15   | 1         | 0.11%   |
| 5.5.2    | 1         | 0.11%   |
| 5.4.30   | 1         | 0.11%   |
| 5.3.18   | 1         | 0.11%   |
| 5.18.0   | 1         | 0.11%   |
| 5.16.5   | 1         | 0.11%   |
| 5.16.0   | 1         | 0.11%   |
| 5.15.5   | 1         | 0.11%   |
| 5.14.0   | 1         | 0.11%   |
| 5.12.1   | 1         | 0.11%   |
| 5.10.9   | 1         | 0.11%   |
| 5.10.0   | 1         | 0.11%   |
| 4.9.201  | 1         | 0.11%   |
| 4.20.0   | 1         | 0.11%   |
| 4.15.18  | 1         | 0.11%   |
| 4.14.225 | 1         | 0.11%   |
| 4.13.9   | 1         | 0.11%   |
| 3.13.0   | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 293       | 30.78%  |
| 4.15    | 130       | 13.66%  |
| 5.13    | 116       | 12.18%  |
| 5.11    | 98        | 10.29%  |
| 5.8     | 97        | 10.19%  |
| 5.3     | 87        | 9.14%   |
| 5.15    | 63        | 6.62%   |
| 5.0     | 22        | 2.31%   |
| 4.18    | 11        | 1.16%   |
| 4.4     | 8         | 0.84%   |
| 5.6     | 3         | 0.32%   |
| 4.9     | 3         | 0.32%   |
| 4.13    | 3         | 0.32%   |
| 5.7     | 2         | 0.21%   |
| 5.16    | 2         | 0.21%   |
| 5.10    | 2         | 0.21%   |
| 4.8     | 2         | 0.21%   |
| 4.10    | 2         | 0.21%   |
| 5.9     | 1         | 0.11%   |
| 5.5     | 1         | 0.11%   |
| 5.18    | 1         | 0.11%   |
| 5.14    | 1         | 0.11%   |
| 5.12    | 1         | 0.11%   |
| 4.20    | 1         | 0.11%   |
| 4.14    | 1         | 0.11%   |
| 3.13    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 799       | 86.75%  |
| i686    | 114       | 12.38%  |
| aarch64 | 6         | 0.65%   |
| ppc64   | 1         | 0.11%   |
| armv7l  | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| LXQt            | 670       | 72.28%  |
| LXDE            | 199       | 21.47%  |
| Unknown         | 21        | 2.27%   |
| GNOME           | 14        | 1.51%   |
| Openbox         | 7         | 0.76%   |
| KDE5            | 3         | 0.32%   |
| X-Cinnamon      | 2         | 0.22%   |
| GNOME Flashback | 2         | 0.22%   |
| Cinnamon        | 2         | 0.22%   |
| Budgie          | 2         | 0.22%   |
| XFCE            | 1         | 0.11%   |
| MATE            | 1         | 0.11%   |
| Lubuntu         | 1         | 0.11%   |
| KDE             | 1         | 0.11%   |
| i3              | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 893       | 96.44%  |
| Tty         | 24        | 2.59%   |
| Wayland     | 6         | 0.65%   |
| Unknown     | 2         | 0.22%   |
| Unspecified | 1         | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 385       | 41.18%  |
| Unknown | 358       | 38.29%  |
| LightDM | 80        | 8.56%   |
| TDM     | 68        | 7.27%   |
| GDM     | 35        | 3.74%   |
| GDM3    | 4         | 0.43%   |
| XDM     | 3         | 0.32%   |
| LXDM    | 2         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 246       | 26.57%  |
| pt_BR   | 74        | 7.99%   |
| fr_FR   | 74        | 7.99%   |
| it_IT   | 57        | 6.16%   |
| de_DE   | 55        | 5.94%   |
| en_GB   | 50        | 5.4%    |
| C       | 42        | 4.54%   |
| ru_RU   | 35        | 3.78%   |
| Unknown | 31        | 3.35%   |
| pl_PL   | 25        | 2.7%    |
| en_CA   | 22        | 2.38%   |
| es_ES   | 21        | 2.27%   |
| en_AU   | 19        | 2.05%   |
| es_AR   | 11        | 1.19%   |
| cs_CZ   | 10        | 1.08%   |
| tr_TR   | 9         | 0.97%   |
| nl_NL   | 9         | 0.97%   |
| hu_HU   | 9         | 0.97%   |
| en_IN   | 9         | 0.97%   |
| es_MX   | 8         | 0.86%   |
| es_CR   | 8         | 0.86%   |
| ja_JP   | 7         | 0.76%   |
| es_CL   | 6         | 0.65%   |
| fr_BE   | 5         | 0.54%   |
| en_IE   | 5         | 0.54%   |
| nl_BE   | 4         | 0.43%   |
| es_UY   | 4         | 0.43%   |
| es_PE   | 4         | 0.43%   |
| es_CO   | 4         | 0.43%   |
| en_NZ   | 4         | 0.43%   |
| el_GR   | 4         | 0.43%   |
| pt_PT   | 3         | 0.32%   |
| fr_CH   | 3         | 0.32%   |
| fr_CA   | 3         | 0.32%   |
| fi_FI   | 3         | 0.32%   |
| en_ZA   | 3         | 0.32%   |
| en_SG   | 3         | 0.32%   |
| de_AT   | 3         | 0.32%   |
| bg_BG   | 3         | 0.32%   |
| zh_TW   | 2         | 0.22%   |
| ru_UA   | 2         | 0.22%   |
| id_ID   | 2         | 0.22%   |
| es_VE   | 2         | 0.22%   |
| de_CH   | 2         | 0.22%   |
| zh_CN   | 1         | 0.11%   |
| uk_UA   | 1         | 0.11%   |
| sv_SE   | 1         | 0.11%   |
| sr_RS   | 1         | 0.11%   |
| ro_RO   | 1         | 0.11%   |
| nb_NO   | 1         | 0.11%   |
| lt_LT   | 1         | 0.11%   |
| ko_KR   | 1         | 0.11%   |
| hr_HR   | 1         | 0.11%   |
| fa_IR   | 1         | 0.11%   |
| es_GT   | 1         | 0.11%   |
| es_EC   | 1         | 0.11%   |
| es_DO   | 1         | 0.11%   |
| es_BO   | 1         | 0.11%   |
| en_ZM   | 1         | 0.11%   |
| en_PH   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 618       | 66.59%  |
| EFI  | 310       | 33.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 851       | 92.3%   |
| Overlay | 41        | 4.45%   |
| Btrfs   | 11        | 1.19%   |
| Aufs    | 5         | 0.54%   |
| Unknown | 5         | 0.54%   |
| Xfs     | 4         | 0.43%   |
| Ext3    | 2         | 0.22%   |
| Zfs     | 1         | 0.11%   |
| F2fs    | 1         | 0.11%   |
| Ext2    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 466       | 50.32%  |
| GPT     | 240       | 25.92%  |
| MBR     | 220       | 23.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 827       | 89.12%  |
| Yes       | 101       | 10.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 673       | 72.52%  |
| Yes       | 255       | 27.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 165       | 17.92%  |
| ASUSTek Computer        | 120       | 13.03%  |
| Dell                    | 98        | 10.64%  |
| Lenovo                  | 84        | 9.12%   |
| Acer                    | 61        | 6.62%   |
| Toshiba                 | 39        | 4.23%   |
| Gigabyte Technology     | 39        | 4.23%   |
| MSI                     | 37        | 4.02%   |
| ASRock                  | 28        | 3.04%   |
| Samsung Electronics     | 25        | 2.71%   |
| Intel                   | 20        | 2.17%   |
| Sony                    | 17        | 1.85%   |
| Apple                   | 17        | 1.85%   |
| Unknown                 | 15        | 1.63%   |
| Positivo                | 13        | 1.41%   |
| Google                  | 12        | 1.3%    |
| AMI                     | 8         | 0.87%   |
| Pegatron                | 7         | 0.76%   |
| Fujitsu                 | 7         | 0.76%   |
| Foxconn                 | 7         | 0.76%   |
| Packard Bell            | 6         | 0.65%   |
| Fujitsu Siemens         | 6         | 0.65%   |
| Notebook                | 5         | 0.54%   |
| Mediacom                | 5         | 0.54%   |
| IBM                     | 5         | 0.54%   |
| Biostar                 | 5         | 0.54%   |
| Raspberry Pi Foundation | 4         | 0.43%   |
| AAEON                   | 4         | 0.43%   |
| Nvidia                  | 3         | 0.33%   |
| Gateway                 | 3         | 0.33%   |
| Alienware               | 3         | 0.33%   |
| ZOTAC                   | 2         | 0.22%   |
| YASHI                   | 2         | 0.22%   |
| TrekStor                | 2         | 0.22%   |
| Standard                | 2         | 0.22%   |
| Philco                  | 2         | 0.22%   |
| Panasonic               | 2         | 0.22%   |
| Medion                  | 2         | 0.22%   |
| Itautec                 | 2         | 0.22%   |
| Insyde                  | 2         | 0.22%   |
| eMachines               | 2         | 0.22%   |
| Dixonsxp                | 2         | 0.22%   |
| VIA Technologies        | 1         | 0.11%   |
| UNOWHY                  | 1         | 0.11%   |
| Timi                    | 1         | 0.11%   |
| Thomson                 | 1         | 0.11%   |
| System76                | 1         | 0.11%   |
| Supermicro              | 1         | 0.11%   |
| Semp Toshiba            | 1         | 0.11%   |
| Qbex                    | 1         | 0.11%   |
| Prestigio               | 1         | 0.11%   |
| Phoenix/SiS             | 1         | 0.11%   |
| PCWare                  | 1         | 0.11%   |
| PCChips                 | 1         | 0.11%   |
| OEM                     | 1         | 0.11%   |
| Nokia                   | 1         | 0.11%   |
| NOBLEX                  | 1         | 0.11%   |
| Microsoft               | 1         | 0.11%   |
| LG Electronics          | 1         | 0.11%   |
| LEADER                  | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 22        | 2.39%   |
| HP Notebook                         | 7         | 0.76%   |
| Apple MacBookPro8,1                 | 6         | 0.65%   |
| HP Pavilion g6                      | 4         | 0.43%   |
| HP Pavilion dv6                     | 4         | 0.43%   |
| Dell Latitude D630                  | 4         | 0.43%   |
| AAEON MF-001                        | 4         | 0.43%   |
| Nvidia Tegra                        | 3         | 0.33%   |
| MSI MS-7C37                         | 3         | 0.33%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS | 3         | 0.33%   |
| HP ProBook 440 G7                   | 3         | 0.33%   |
| HP Pavilion 15                      | 3         | 0.33%   |
| Dell OptiPlex 790                   | 3         | 0.33%   |
| Dell OptiPlex 7010                  | 3         | 0.33%   |
| ASUS V-P8H67E                       | 3         | 0.33%   |
| ASUS All Series                     | 3         | 0.33%   |
| ASUS 1000H                          | 3         | 0.33%   |
| ASRock FM2A85X Extreme6             | 3         | 0.33%   |
| Acer Aspire 5742G                   | 3         | 0.33%   |
| YASHI MYBOOK 360                    | 2         | 0.22%   |
| Toshiba Satellite L40               | 2         | 0.22%   |
| Toshiba Satellite A205              | 2         | 0.22%   |
| Samsung RV415/RV515                 | 2         | 0.22%   |
| Samsung 275E4E/275E5E               | 2         | 0.22%   |
| Positivo Mobile                     | 2         | 0.22%   |
| Positivo H14BT58                    | 2         | 0.22%   |
| MSI MS-7B89                         | 2         | 0.22%   |
| Mediacom WinPad 11,6 FullHD- WPU11  | 2         | 0.22%   |
| Mediacom GTZS                       | 2         | 0.22%   |
| Lenovo IdeaPad 330-17AST 81D7       | 2         | 0.22%   |
| Lenovo IdeaPad 320-15AST 80XV       | 2         | 0.22%   |
| Lenovo IdeaPad 100-15IBD 80QQ       | 2         | 0.22%   |
| Lenovo G50-30 80G0                  | 2         | 0.22%   |
| Itautec Infoway                     | 2         | 0.22%   |
| HP t620 Quad Core TC                | 2         | 0.22%   |
| HP ProBook 450 G2                   | 2         | 0.22%   |
| HP ProBook 440 G8 Notebook PC       | 2         | 0.22%   |
| HP Pavilion x2 Detachable           | 2         | 0.22%   |
| HP Pavilion g7                      | 2         | 0.22%   |
| HP Pavilion g4                      | 2         | 0.22%   |
| HP Laptop 15-bw0xx                  | 2         | 0.22%   |
| HP EliteBook 840 G1                 | 2         | 0.22%   |
| HP EliteBook 2560p                  | 2         | 0.22%   |
| HP Compaq Presario CQ50             | 2         | 0.22%   |
| HP Compaq Presario C700             | 2         | 0.22%   |
| HP Compaq dc7800 Small Form Factor  | 2         | 0.22%   |
| HP Compaq 6000 Pro SFF PC           | 2         | 0.22%   |
| Gigabyte H81M-DS2                   | 2         | 0.22%   |
| Dell XPS 13 9300                    | 2         | 0.22%   |
| Dell Studio 1555                    | 2         | 0.22%   |
| Dell Latitude 7480                  | 2         | 0.22%   |
| Dell Inspiron N5010                 | 2         | 0.22%   |
| Dell Inspiron 15-3567               | 2         | 0.22%   |
| Dell DM061                          | 2         | 0.22%   |
| Dell Dimension 9100                 | 2         | 0.22%   |
| ASUS PRIME H410M-E                  | 2         | 0.22%   |
| ASUS 1215B                          | 2         | 0.22%   |
| ASUS 1015PE                         | 2         | 0.22%   |
| ASUS 1015BX                         | 2         | 0.22%   |
| ASRock N68-VS3 UCC                  | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 48        | 5.21%   |
| HP Pavilion           | 35        | 3.8%    |
| Toshiba Satellite     | 34        | 3.69%   |
| Dell Inspiron         | 33        | 3.58%   |
| HP Compaq             | 32        | 3.47%   |
| Lenovo IdeaPad        | 29        | 3.15%   |
| Lenovo ThinkPad       | 25        | 2.71%   |
| HP ProBook            | 23        | 2.5%    |
| Unknown               | 22        | 2.39%   |
| Dell Latitude         | 20        | 2.17%   |
| HP EliteBook          | 15        | 1.63%   |
| Dell OptiPlex         | 15        | 1.63%   |
| Lenovo ThinkCentre    | 10        | 1.09%   |
| HP Laptop             | 10        | 1.09%   |
| HP Notebook           | 7         | 0.76%   |
| Dell XPS              | 6         | 0.65%   |
| Dell Vostro           | 6         | 0.65%   |
| ASUS VivoBook         | 6         | 0.65%   |
| ASUS PRIME            | 6         | 0.65%   |
| Apple MacBookPro8     | 6         | 0.65%   |
| HP Presario           | 5         | 0.54%   |
| Fujitsu Siemens AMILO | 5         | 0.54%   |
| RPi Raspberry         | 4         | 0.43%   |
| Packard Bell EasyNote | 4         | 0.43%   |
| HP Spectre            | 4         | 0.43%   |
| Fujitsu LIFEBOOK      | 4         | 0.43%   |
| Dell Studio           | 4         | 0.43%   |
| AAEON MF-001          | 4         | 0.43%   |
| Nvidia Tegra          | 3         | 0.33%   |
| MSI MS-7C37           | 3         | 0.33%   |
| HP t620               | 3         | 0.33%   |
| HP Stream             | 3         | 0.33%   |
| Dell Precision        | 3         | 0.33%   |
| Dell PowerEdge        | 3         | 0.33%   |
| Dell Dimension        | 3         | 0.33%   |
| ASUS V-P8H67E         | 3         | 0.33%   |
| ASUS All              | 3         | 0.33%   |
| ASUS 1000H            | 3         | 0.33%   |
| ASRock FM2A85X        | 3         | 0.33%   |
| Apple MacBookPro10    | 3         | 0.33%   |
| Acer Extensa          | 3         | 0.33%   |
| YASHI MYBOOK          | 2         | 0.22%   |
| Toshiba TECRA         | 2         | 0.22%   |
| Samsung RV415         | 2         | 0.22%   |
| Samsung 275E4E        | 2         | 0.22%   |
| Positivo Mobile       | 2         | 0.22%   |
| Positivo H14BT58      | 2         | 0.22%   |
| Notebook W54          | 2         | 0.22%   |
| MSI MS-7B89           | 2         | 0.22%   |
| Mediacom WinPad       | 2         | 0.22%   |
| Mediacom GTZS         | 2         | 0.22%   |
| Lenovo Yoga           | 2         | 0.22%   |
| Lenovo G50-30         | 2         | 0.22%   |
| Itautec Infoway       | 2         | 0.22%   |
| Intel DG31PR          | 2         | 0.22%   |
| HP EliteDesk          | 2         | 0.22%   |
| HP dc5000             | 2         | 0.22%   |
| HP 245                | 2         | 0.22%   |
| Gigabyte H81M-DS2     | 2         | 0.22%   |
| Gigabyte B450M        | 2         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 92        | 9.99%   |
| 2008    | 77        | 8.36%   |
| 2007    | 75        | 8.14%   |
| 2012    | 71        | 7.71%   |
| 2013    | 68        | 7.38%   |
| 2010    | 68        | 7.38%   |
| 2009    | 57        | 6.19%   |
| 2017    | 51        | 5.54%   |
| 2019    | 50        | 5.43%   |
| 2014    | 46        | 4.99%   |
| 2006    | 41        | 4.45%   |
| 2016    | 40        | 4.34%   |
| 2020    | 39        | 4.23%   |
| 2018    | 37        | 4.02%   |
| 2015    | 36        | 3.91%   |
| 2021    | 31        | 3.37%   |
| 2005    | 18        | 1.95%   |
| Unknown | 10        | 1.09%   |
| 2004    | 5         | 0.54%   |
| 2022    | 4         | 0.43%   |
| 2002    | 2         | 0.22%   |
| 2003    | 1         | 0.11%   |
| 2001    | 1         | 0.11%   |
| 2000    | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 570       | 61.89%  |
| Desktop        | 309       | 33.55%  |
| Convertible    | 11        | 1.19%   |
| Mini pc        | 8         | 0.87%   |
| System on chip | 7         | 0.76%   |
| All in one     | 6         | 0.65%   |
| Server         | 6         | 0.65%   |
| Tablet         | 4         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 878       | 95.23%  |
| Enabled  | 44        | 4.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 906       | 98.37%  |
| Yes  | 15        | 1.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 279       | 29.9%   |
| 4.01-8.0        | 181       | 19.4%   |
| 1.01-2.0        | 168       | 18.01%  |
| 8.01-16.0       | 101       | 10.83%  |
| 16.01-24.0      | 78        | 8.36%   |
| 2.01-3.0        | 47        | 5.04%   |
| 0.51-1.0        | 36        | 3.86%   |
| 32.01-64.0      | 24        | 2.57%   |
| 0.01-0.5        | 7         | 0.75%   |
| 24.01-32.0      | 6         | 0.64%   |
| 64.01-256.0     | 4         | 0.43%   |
| More than 256.0 | 2         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 430       | 43.52%  |
| 0.51-1.0   | 252       | 25.51%  |
| 2.01-3.0   | 133       | 13.46%  |
| 0.01-0.5   | 61        | 6.17%   |
| 4.01-8.0   | 60        | 6.07%   |
| 3.01-4.0   | 41        | 4.15%   |
| 8.01-16.0  | 8         | 0.81%   |
| 32.01-64.0 | 1         | 0.1%    |
| 16.01-24.0 | 1         | 0.1%    |
| Unknown    | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 640       | 68.82%  |
| 2      | 209       | 22.47%  |
| 3      | 23        | 2.47%   |
| 4      | 22        | 2.37%   |
| 0      | 17        | 1.83%   |
| 5      | 11        | 1.18%   |
| 6      | 3         | 0.32%   |
| 7      | 2         | 0.22%   |
| 17     | 1         | 0.11%   |
| 14     | 1         | 0.11%   |
| 10     | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 469       | 50.7%   |
| No        | 456       | 49.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 819       | 88.83%  |
| No        | 103       | 11.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 685       | 74.13%  |
| No        | 239       | 25.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 520       | 55.79%  |
| Yes       | 412       | 44.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 133       | 14.39%  |
| Brazil                 | 92        | 9.96%   |
| France                 | 76        | 8.23%   |
| Italy                  | 70        | 7.58%   |
| Germany                | 67        | 7.25%   |
| Russia                 | 49        | 5.3%    |
| UK                     | 40        | 4.33%   |
| Canada                 | 33        | 3.57%   |
| Poland                 | 26        | 2.81%   |
| Spain                  | 21        | 2.27%   |
| Netherlands            | 20        | 2.16%   |
| Australia              | 18        | 1.95%   |
| Belgium                | 15        | 1.62%   |
| Turkey                 | 14        | 1.52%   |
| Czechia                | 14        | 1.52%   |
| Switzerland            | 12        | 1.3%    |
| Mexico                 | 12        | 1.3%    |
| Hungary                | 12        | 1.3%    |
| Argentina              | 12        | 1.3%    |
| India                  | 10        | 1.08%   |
| Finland                | 10        | 1.08%   |
| Ukraine                | 9         | 0.97%   |
| Indonesia              | 8         | 0.87%   |
| Costa Rica             | 8         | 0.87%   |
| Bulgaria               | 7         | 0.76%   |
| Malaysia               | 6         | 0.65%   |
| Japan                  | 6         | 0.65%   |
| Ireland                | 6         | 0.65%   |
| Colombia               | 6         | 0.65%   |
| Chile                  | 6         | 0.65%   |
| South Africa           | 5         | 0.54%   |
| Portugal               | 5         | 0.54%   |
| New Zealand            | 5         | 0.54%   |
| Greece                 | 5         | 0.54%   |
| Austria                | 5         | 0.54%   |
| Uruguay                | 4         | 0.43%   |
| Sweden                 | 4         | 0.43%   |
| Romania                | 4         | 0.43%   |
| Peru                   | 4         | 0.43%   |
| Slovenia               | 3         | 0.32%   |
| Slovakia               | 3         | 0.32%   |
| Singapore              | 3         | 0.32%   |
| Serbia                 | 3         | 0.32%   |
| Lithuania              | 3         | 0.32%   |
| Ecuador                | 3         | 0.32%   |
| Bosnia and Herzegovina | 3         | 0.32%   |
| Belarus                | 3         | 0.32%   |
| Vietnam                | 2         | 0.22%   |
| Tunisia                | 2         | 0.22%   |
| Taiwan                 | 2         | 0.22%   |
| South Korea            | 2         | 0.22%   |
| Puerto Rico            | 2         | 0.22%   |
| Norway                 | 2         | 0.22%   |
| Luxembourg             | 2         | 0.22%   |
| Iran                   | 2         | 0.22%   |
| Egypt                  | 2         | 0.22%   |
| Denmark                | 2         | 0.22%   |
| Zambia                 | 1         | 0.11%   |
| Venezuela              | 1         | 0.11%   |
| Thailand               | 1         | 0.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Rome              | 11        | 1.14%   |
| Paris             | 10        | 1.04%   |
| Milan             | 10        | 1.04%   |
| Melbourne         | 10        | 1.04%   |
| Moscow            | 9         | 0.93%   |
| Oshawa            | 7         | 0.73%   |
| Heredia           | 7         | 0.73%   |
| Rio de Janeiro    | 6         | 0.62%   |
| Istanbul          | 6         | 0.62%   |
| Zurich            | 5         | 0.52%   |
| Wellington        | 5         | 0.52%   |
| New York          | 5         | 0.52%   |
| Mexico City       | 5         | 0.52%   |
| Warsaw            | 4         | 0.42%   |
| Stuttgart         | 4         | 0.42%   |
| St Petersburg     | 4         | 0.42%   |
| Sao Paulo         | 4         | 0.42%   |
| Prague            | 4         | 0.42%   |
| Porto Alegre      | 4         | 0.42%   |
| Munich            | 4         | 0.42%   |
| Kyiv              | 4         | 0.42%   |
| Kuala Lumpur      | 4         | 0.42%   |
| Helsinki          | 4         | 0.42%   |
| Frankfurt am Main | 4         | 0.42%   |
| Berlin            | 4         | 0.42%   |
| Bengaluru         | 4         | 0.42%   |
| Athens            | 4         | 0.42%   |
| Yekaterinburg     | 3         | 0.31%   |
| Winnipeg          | 3         | 0.31%   |
| Voronezh          | 3         | 0.31%   |
| Vienna            | 3         | 0.31%   |
| Teresina          | 3         | 0.31%   |
| Tampere           | 3         | 0.31%   |
| Sydney            | 3         | 0.31%   |
| Salvador          | 3         | 0.31%   |
| Poznan            | 3         | 0.31%   |
| Pécs             | 3         | 0.31%   |
| Novo Gama         | 3         | 0.31%   |
| Nice              | 3         | 0.31%   |
| Montevideo        | 3         | 0.31%   |
| Lyon              | 3         | 0.31%   |
| Hamburg           | 3         | 0.31%   |
| Fortaleza         | 3         | 0.31%   |
| Florence          | 3         | 0.31%   |
| Dublin            | 3         | 0.31%   |
| Derry             | 3         | 0.31%   |
| Curitiba          | 3         | 0.31%   |
| Cape Town         | 3         | 0.31%   |
| Campinas          | 3         | 0.31%   |
| Buenos Aires      | 3         | 0.31%   |
| Budapest          | 3         | 0.31%   |
| Brasília         | 3         | 0.31%   |
| Bogotá           | 3         | 0.31%   |
| Arluno            | 3         | 0.31%   |
| Wolfsburg         | 2         | 0.21%   |
| Wahroonga         | 2         | 0.21%   |
| Vicosa            | 2         | 0.21%   |
| Venice            | 2         | 0.21%   |
| Varna             | 2         | 0.21%   |
| Valencia          | 2         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 208       | 268    | 18.26%  |
| WDC                 | 199       | 264    | 17.47%  |
| Samsung Electronics | 104       | 155    | 9.13%   |
| Toshiba             | 86        | 95     | 7.55%   |
| Hitachi             | 83        | 101    | 7.29%   |
| Unknown             | 82        | 109    | 7.2%    |
| Kingston            | 52        | 56     | 4.57%   |
| Crucial             | 35        | 49     | 3.07%   |
| SanDisk             | 29        | 34     | 2.55%   |
| Intel               | 24        | 28     | 2.11%   |
| HGST                | 24        | 30     | 2.11%   |
| Fujitsu             | 20        | 21     | 1.76%   |
| Maxtor              | 15        | 16     | 1.32%   |
| A-DATA Technology   | 13        | 15     | 1.14%   |
| SK hynix            | 12        | 12     | 1.05%   |
| China               | 11        | 13     | 0.97%   |
| Apacer              | 9         | 9      | 0.79%   |
| Micron Technology   | 8         | 8      | 0.7%    |
| SPCC                | 6         | 8      | 0.53%   |
| OCZ                 | 6         | 7      | 0.53%   |
| KIOXIA              | 6         | 6      | 0.53%   |
| Transcend           | 4         | 4      | 0.35%   |
| PNY                 | 4         | 4      | 0.35%   |
| Patriot             | 4         | 4      | 0.35%   |
| LITEONIT            | 4         | 4      | 0.35%   |
| LDLC                | 4         | 4      | 0.35%   |
| Intenso             | 4         | 4      | 0.35%   |
| Apple               | 4         | 11     | 0.35%   |
| Unknown             | 4         | 5      | 0.35%   |
| TO Exter            | 3         | 3      | 0.26%   |
| Team                | 3         | 3      | 0.26%   |
| LITEON              | 3         | 4      | 0.26%   |
| JMicron Technology  | 3         | 3      | 0.26%   |
| IBM/Hitachi         | 3         | 4      | 0.26%   |
| USB                 | 2         | 2      | 0.18%   |
| STEC                | 2         | 3      | 0.18%   |
| Silicon Motion      | 2         | 3      | 0.18%   |
| Plextor             | 2         | 4      | 0.18%   |
| Mushkin             | 2         | 2      | 0.18%   |
| Lexar               | 2         | 2      | 0.18%   |
| KingDian            | 2         | 2      | 0.18%   |
| Gigabyte Technology | 2         | 2      | 0.18%   |
| Dogfish             | 2         | 2      | 0.18%   |
| Corsair             | 2         | 2      | 0.18%   |
| ASMT                | 2         | 3      | 0.18%   |
| W800S               | 1         | 1      | 0.09%   |
| Verbatim            | 1         | 1      | 0.09%   |
| TSA                 | 1         | 1      | 0.09%   |
| Teclast             | 1         | 1      | 0.09%   |
| TEAM T25            | 1         | 1      | 0.09%   |
| TCSUNBOW            | 1         | 1      | 0.09%   |
| Smartbuy            | 1         | 1      | 0.09%   |
| ShiJi               | 1         | 1      | 0.09%   |
| PNY USB             | 1         | 1      | 0.09%   |
| Phison Electronics  | 1         | 1      | 0.09%   |
| Phison              | 1         | 5      | 0.09%   |
| ORTIAL              | 1         | 1      | 0.09%   |
| NGFF                | 1         | 1      | 0.09%   |
| MyDigitalSSD        | 1         | 1      | 0.09%   |
| MaxDigital          | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 16        | 1.3%    |
| Kingston SA400S37240G 240GB SSD     | 13        | 1.06%   |
| Unknown MMC Card  64GB              | 9         | 0.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 9         | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 0.73%   |
| Unknown SD/MMC/MS PRO 64GB          | 8         | 0.65%   |
| Toshiba MQ01ABF050 500GB            | 8         | 0.65%   |
| Toshiba MQ01ABD100 1TB              | 8         | 0.65%   |
| Seagate ST9500325AS 500GB           | 8         | 0.65%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 0.65%   |
| Seagate ST500DM002-1BD142 500GB     | 7         | 0.57%   |
| Kingston SA400S37120G 120GB SSD     | 7         | 0.57%   |
| Crucial CT240BX500SSD1 240GB        | 7         | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 6         | 0.49%   |
| Samsung SSD 850 EVO 250GB           | 6         | 0.49%   |
| Toshiba MQ01ABD050 500GB            | 5         | 0.41%   |
| Seagate ST9250315AS 250GB           | 5         | 0.41%   |
| Seagate ST3500418AS 500GB           | 5         | 0.41%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.41%   |
| Kingston SA400S37480G 480GB SSD     | 5         | 0.41%   |
| Crucial CT480BX500SSD1 480GB        | 5         | 0.41%   |
| A-DATA SU650 240GB SSD              | 5         | 0.41%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 0.33%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 4         | 0.33%   |
| Unknown NCard  32GB                 | 4         | 0.33%   |
| Unknown MMC64G  64GB                | 4         | 0.33%   |
| Unknown MMC Card  16GB              | 4         | 0.33%   |
| Unknown DA4064  64GB                | 4         | 0.33%   |
| Seagate ST9320325AS 320GB           | 4         | 0.33%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB      | 4         | 0.33%   |
| Seagate Expansion 1TB               | 4         | 0.33%   |
| Samsung HM321HI 320GB               | 4         | 0.33%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 0.33%   |
| Hitachi HTS543232A7A384 320GB       | 4         | 0.33%   |
| Hitachi HTS543216L9SA00 160GB       | 4         | 0.33%   |
| Hitachi HTS542512K9SA00 120GB       | 4         | 0.33%   |
| Hitachi HTS541616J9SA00 160GB       | 4         | 0.33%   |
| HGST HTS545050A7E680 500GB          | 4         | 0.33%   |
| HGST HTS545050A7E380 500GB          | 4         | 0.33%   |
| Unknown                             | 4         | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 3         | 0.24%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.24%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 3         | 0.24%   |
| WDC WD2500BEVT-80A23T0 250GB        | 3         | 0.24%   |
| WDC WD2500BEVT-22ZCT0 250GB         | 3         | 0.24%   |
| WDC WD20EFRX-68EUZN0 2TB            | 3         | 0.24%   |
| WDC WD10SPZX-24Z10T0 1TB            | 3         | 0.24%   |
| WDC WD10JPVX-60JC3T0 1TB            | 3         | 0.24%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.24%   |
| Unknown MMC Card  128GB             | 3         | 0.24%   |
| Unknown M52516  16GB                | 3         | 0.24%   |
| Unknown 128G32  128GB               | 3         | 0.24%   |
| Toshiba MQ04ABF100 1TB              | 3         | 0.24%   |
| Toshiba MK2546GSX 250GB             | 3         | 0.24%   |
| Toshiba MK1646GSX 160GB             | 3         | 0.24%   |
| TO Exter nal USB 3.0 1TB            | 3         | 0.24%   |
| Seagate ST98823AS 80GB              | 3         | 0.24%   |
| Seagate ST9250410AS 250GB           | 3         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 207       | 266    | 31.46%  |
| WDC                 | 179       | 237    | 27.2%   |
| Hitachi             | 83        | 101    | 12.61%  |
| Toshiba             | 72        | 78     | 10.94%  |
| Samsung Electronics | 43        | 61     | 6.53%   |
| HGST                | 24        | 30     | 3.65%   |
| Fujitsu             | 20        | 21     | 3.04%   |
| Maxtor              | 14        | 15     | 2.13%   |
| Unknown             | 8         | 8      | 1.22%   |
| IBM/Hitachi         | 3         | 4      | 0.46%   |
| USB                 | 2         | 2      | 0.3%    |
| LaCie               | 1         | 1      | 0.15%   |
| Apricorn            | 1         | 1      | 0.15%   |
| Apple               | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 46        | 49     | 14.42%  |
| Samsung Electronics | 44        | 60     | 13.79%  |
| Crucial             | 34        | 48     | 10.66%  |
| SanDisk             | 20        | 25     | 6.27%   |
| Intel               | 19        | 23     | 5.96%   |
| WDC                 | 17        | 20     | 5.33%   |
| China               | 11        | 13     | 3.45%   |
| A-DATA Technology   | 11        | 13     | 3.45%   |
| Apacer              | 9         | 9      | 2.82%   |
| Toshiba             | 8         | 9      | 2.51%   |
| OCZ                 | 6         | 7      | 1.88%   |
| Micron Technology   | 6         | 6      | 1.88%   |
| Transcend           | 4         | 4      | 1.25%   |
| SPCC                | 4         | 4      | 1.25%   |
| PNY                 | 4         | 4      | 1.25%   |
| Patriot             | 4         | 4      | 1.25%   |
| LITEONIT            | 4         | 4      | 1.25%   |
| Intenso             | 4         | 4      | 1.25%   |
| TO Exter            | 3         | 3      | 0.94%   |
| Team                | 3         | 3      | 0.94%   |
| SK hynix            | 3         | 3      | 0.94%   |
| LITEON              | 3         | 4      | 0.94%   |
| LDLC                | 3         | 3      | 0.94%   |
| Unknown             | 2         | 2      | 0.63%   |
| Plextor             | 2         | 4      | 0.63%   |
| Mushkin             | 2         | 2      | 0.63%   |
| Lexar               | 2         | 2      | 0.63%   |
| KingDian            | 2         | 2      | 0.63%   |
| Dogfish             | 2         | 2      | 0.63%   |
| Corsair             | 2         | 2      | 0.63%   |
| ASMT                | 2         | 3      | 0.63%   |
| Apple               | 2         | 8      | 0.63%   |
| W800S               | 1         | 1      | 0.31%   |
| Verbatim            | 1         | 1      | 0.31%   |
| TSA                 | 1         | 1      | 0.31%   |
| Teclast             | 1         | 1      | 0.31%   |
| TEAM T25            | 1         | 1      | 0.31%   |
| TCSUNBOW            | 1         | 1      | 0.31%   |
| Smartbuy            | 1         | 1      | 0.31%   |
| Seagate             | 1         | 1      | 0.31%   |
| PNY USB             | 1         | 1      | 0.31%   |
| ORTIAL              | 1         | 1      | 0.31%   |
| NGFF                | 1         | 1      | 0.31%   |
| MyDigitalSSD        | 1         | 1      | 0.31%   |
| Maxtor              | 1         | 1      | 0.31%   |
| LS                  | 1         | 1      | 0.31%   |
| Londisk             | 1         | 1      | 0.31%   |
| Leven               | 1         | 2      | 0.31%   |
| Lenovo              | 1         | 2      | 0.31%   |
| Kston               | 1         | 3      | 0.31%   |
| KLEVV               | 1         | 1      | 0.31%   |
| KingSpec            | 1         | 3      | 0.31%   |
| Integral            | 1         | 1      | 0.31%   |
| HS-SSD-E100         | 1         | 1      | 0.31%   |
| Hikvision           | 1         | 1      | 0.31%   |
| Hewlett-Packard     | 1         | 6      | 0.31%   |
| GOODRAM             | 1         | 1      | 0.31%   |
| Gigabyte Technology | 1         | 1      | 0.31%   |
| FORESEE             | 1         | 1      | 0.31%   |
| Dell                | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 580       | 826    | 55.08%  |
| SSD     | 303       | 392    | 28.77%  |
| MMC     | 84        | 108    | 7.98%   |
| NVMe    | 75        | 103    | 7.12%   |
| Unknown | 11        | 14     | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 782       | 1180   | 79.88%  |
| MMC  | 84        | 108    | 8.58%   |
| NVMe | 73        | 101    | 7.46%   |
| SAS  | 40        | 54     | 4.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 653       | 871    | 72.96%  |
| 0.51-1.0   | 176       | 255    | 19.66%  |
| 1.01-2.0   | 38        | 48     | 4.25%   |
| 3.01-4.0   | 17        | 31     | 1.9%    |
| 2.01-3.0   | 8         | 9      | 0.89%   |
| 4.01-10.0  | 3         | 4      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 276       | 29.58%  |
| 251-500        | 216       | 23.15%  |
| 51-100         | 102       | 10.93%  |
| 501-1000       | 95        | 10.18%  |
| 21-50          | 73        | 7.82%   |
| 1-20           | 72        | 7.72%   |
| 1001-2000      | 43        | 4.61%   |
| More than 3000 | 29        | 3.11%   |
| 2001-3000      | 22        | 2.36%   |
| Unknown        | 5         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 493       | 51.25%  |
| 21-50          | 173       | 17.98%  |
| 101-250        | 102       | 10.6%   |
| 51-100         | 69        | 7.17%   |
| 251-500        | 40        | 4.16%   |
| 501-1000       | 39        | 4.05%   |
| 1001-2000      | 22        | 2.29%   |
| More than 3000 | 12        | 1.25%   |
| 2001-3000      | 7         | 0.73%   |
| Unknown        | 5         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 3         | 3      | 2.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 2.59%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 3      | 2.59%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.72%   |
| Seagate ST9250315AS 250GB             | 2         | 2      | 1.72%   |
| Hitachi HTS545032B9A300 320GB         | 2         | 2      | 1.72%   |
| Hitachi HTS542512K9SA00 120GB         | 2         | 2      | 1.72%   |
| Apacer 16GB SATA Flash Drive SSD      | 2         | 2      | 1.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.86%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 1      | 0.86%   |
| WDC WD5000LUCT-62C26Y0 500GB          | 1         | 1      | 0.86%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 1      | 0.86%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 1      | 0.86%   |
| WDC WD400EB-00CPF0 40GB               | 1         | 1      | 0.86%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 0.86%   |
| WDC WD3200BEVT-75A23T0 320GB          | 1         | 1      | 0.86%   |
| WDC WD3200BEKT-60PVMT0 320GB          | 1         | 1      | 0.86%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1         | 1      | 0.86%   |
| WDC WD2500HHTZ-04N21V0 250GB          | 1         | 1      | 0.86%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 2      | 0.86%   |
| WDC WD2500AAJS-75M0A0 250GB           | 1         | 1      | 0.86%   |
| WDC WD1600AAJS-60B4A0 160GB           | 1         | 2      | 0.86%   |
| WDC WD1200BEVS-60UST0 120GB           | 1         | 1      | 0.86%   |
| WDC WD1200BEVS-07LAT0 120GB           | 1         | 1      | 0.86%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1      | 0.86%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 1      | 0.86%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 0.86%   |
| WDC WD10EADS-65M2B0 1TB               | 1         | 1      | 0.86%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 0.86%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 0.86%   |
| Toshiba MK5059GSXP 500GB              | 1         | 1      | 0.86%   |
| Toshiba MK3276GSX 320GB               | 1         | 1      | 0.86%   |
| Toshiba MK2046GSX 200GB               | 1         | 1      | 0.86%   |
| TCSUNBOW X1 32GB SSD                  | 1         | 1      | 0.86%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 0.86%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.86%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 0.86%   |
| Seagate ST9250410AS 250GB             | 1         | 1      | 0.86%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 0.86%   |
| Seagate ST9160310AS 160GB             | 1         | 1      | 0.86%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 0.86%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 0.86%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 0.86%   |
| Seagate ST4000DM004-2CV104 4TB        | 1         | 1      | 0.86%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 0.86%   |
| Seagate ST380011A 80GB                | 1         | 1      | 0.86%   |
| Seagate ST360012A 64GB                | 1         | 1      | 0.86%   |
| Seagate ST3360320AS 360GB             | 1         | 1      | 0.86%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 0.86%   |
| Seagate ST3200822AS 200GB             | 1         | 1      | 0.86%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 0.86%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 1      | 0.86%   |
| Seagate ST1000NM0095-2DC10C 1TB       | 1         | 6      | 0.86%   |
| Seagate ST1000DX001-1CM162 1TB        | 1         | 1      | 0.86%   |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 1      | 0.86%   |
| SanDisk SSD PLUS 120GB                | 1         | 1      | 0.86%   |
| Samsung Electronics HM160JI 160GB     | 1         | 1      | 0.86%   |
| Samsung Electronics HM121HI 120GB     | 1         | 5      | 0.86%   |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 0.86%   |
| Samsung Electronics HD253GJ 250GB     | 1         | 1      | 0.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 37     | 27.19%  |
| WDC                 | 20        | 22     | 17.54%  |
| Hitachi             | 15        | 17     | 13.16%  |
| Toshiba             | 5         | 5      | 4.39%   |
| Kingston            | 5         | 5      | 4.39%   |
| HGST                | 5         | 5      | 4.39%   |
| Crucial             | 5         | 5      | 4.39%   |
| Samsung Electronics | 4         | 8      | 3.51%   |
| Fujitsu             | 4         | 4      | 3.51%   |
| Maxtor              | 3         | 3      | 2.63%   |
| Intel               | 3         | 3      | 2.63%   |
| SK hynix            | 2         | 2      | 1.75%   |
| OCZ                 | 2         | 3      | 1.75%   |
| LITEON              | 2         | 2      | 1.75%   |
| Apacer              | 2         | 2      | 1.75%   |
| TCSUNBOW            | 1         | 1      | 0.88%   |
| SanDisk             | 1         | 1      | 0.88%   |
| Mushkin             | 1         | 1      | 0.88%   |
| LDLC                | 1         | 1      | 0.88%   |
| KingSpec            | 1         | 3      | 0.88%   |
| A-DATA Technology   | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 37     | 36.05%  |
| WDC                 | 19        | 21     | 22.09%  |
| Hitachi             | 15        | 17     | 17.44%  |
| Toshiba             | 5         | 5      | 5.81%   |
| HGST                | 5         | 5      | 5.81%   |
| Samsung Electronics | 4         | 8      | 4.65%   |
| Fujitsu             | 4         | 4      | 4.65%   |
| Maxtor              | 3         | 3      | 3.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 83        | 100    | 74.77%  |
| SSD  | 27        | 30     | 24.32%  |
| NVMe | 1         | 1      | 0.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1      | 16.67%  |
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 16.67%  |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 16.67%  |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 16.67%  |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 16.67%  |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 4      | 50%     |
| Samsung Electronics | 2         | 2      | 33.33%  |
| Intel               | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 525       | 812    | 54.12%  |
| Works    | 331       | 493    | 34.12%  |
| Malfunc  | 108       | 131    | 11.13%  |
| Failed   | 6         | 7      | 0.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 603       | 63.74%  |
| AMD                              | 162       | 17.12%  |
| Nvidia                           | 48        | 5.07%   |
| Samsung Electronics              | 20        | 2.11%   |
| JMicron Technology               | 15        | 1.59%   |
| VIA Technologies                 | 11        | 1.16%   |
| Marvell Technology Group         | 11        | 1.16%   |
| SanDisk                          | 10        | 1.06%   |
| Silicon Integrated Systems [SiS] | 7         | 0.74%   |
| ASMedia Technology               | 7         | 0.74%   |
| Toshiba America Info Systems     | 6         | 0.63%   |
| SK hynix                         | 6         | 0.63%   |
| KIOXIA                           | 6         | 0.63%   |
| Kingston Technology Company      | 6         | 0.63%   |
| Silicon Motion                   | 5         | 0.53%   |
| LSI Logic / Symbios Logic        | 4         | 0.42%   |
| Silicon Image                    | 3         | 0.32%   |
| Phison Electronics               | 3         | 0.32%   |
| ULi Electronics                  | 2         | 0.21%   |
| Micron Technology                | 2         | 0.21%   |
| ADATA Technology                 | 2         | 0.21%   |
| Solid State Storage Technology   | 1         | 0.11%   |
| Seagate Technology               | 1         | 0.11%   |
| Micron/Crucial Technology        | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |
| Broadcom / LSI                   | 1         | 0.11%   |
| Broadcom                         | 1         | 0.11%   |
| Adaptec                          | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 92        | 7.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 46        | 3.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 44        | 3.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 37        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 34        | 2.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 34        | 2.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 32        | 2.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 30        | 2.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 29        | 2.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 29        | 2.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 28        | 2.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 26        | 2.18%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 25        | 2.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 19        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 19        | 1.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 18        | 1.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 1.42%   |
| Nvidia MCP61 SATA Controller                                                            | 15        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 14        | 1.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13        | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 13        | 1.09%   |
| Nvidia MCP61 IDE                                                                        | 12        | 1%      |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 11        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 11        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 0.92%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 10        | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 0.84%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 10        | 0.84%   |
| AMD SB600 IDE                                                                           | 10        | 0.84%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 9         | 0.75%   |
| AMD IXP SB4x0 IDE Controller                                                            | 9         | 0.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 8         | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 0.67%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 7         | 0.59%   |
| Nvidia CK804 Serial ATA Controller                                                      | 7         | 0.59%   |
| Nvidia CK804 IDE                                                                        | 7         | 0.59%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 0.59%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 7         | 0.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7         | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 7         | 0.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7         | 0.59%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7         | 0.59%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 0.59%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 0.59%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 6         | 0.5%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 0.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6         | 0.5%    |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 6         | 0.5%    |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 6         | 0.5%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 6         | 0.5%    |
| AMD FCH IDE Controller                                                                  | 6         | 0.5%    |
| VIA VT8237A SATA 2-Port Controller                                                      | 5         | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 0.42%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 5         | 0.42%   |
| Samsung NVMe SSD Controller 980                                                         | 5         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 600       | 58.77%  |
| IDE  | 300       | 29.38%  |
| NVMe | 71        | 6.95%   |
| RAID | 46        | 4.51%   |
| SCSI | 3         | 0.29%   |
| SAS  | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Intel       | 705       | 76.55%  |
| AMD         | 208       | 22.58%  |
| ARM         | 7         | 0.76%   |
| PowerMac7,2 | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 18        | 1.95%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 12        | 1.3%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 8         | 0.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.76%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.76%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 7         | 0.76%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 7         | 0.76%   |
| AMD E-450 APU with Radeon HD Graphics         | 7         | 0.76%   |
| Intel Pentium 4 CPU 2.80GHz                   | 6         | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 0.65%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 6         | 0.65%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 6         | 0.65%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 0.65%   |
| ARM Processor                                 | 6         | 0.65%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 5         | 0.54%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 5         | 0.54%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 5         | 0.54%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 5         | 0.54%   |
| Intel Pentium 4 CPU 3.00GHz                   | 5         | 0.54%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 5         | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 0.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.54%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.54%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 5         | 0.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 5         | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 0.54%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 5         | 0.54%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.54%   |
| AMD E-350 Processor                           | 5         | 0.54%   |
| AMD E-300 APU with Radeon HD Graphics         | 5         | 0.54%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+    | 5         | 0.54%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 4         | 0.43%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 4         | 0.43%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 4         | 0.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 0.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 4         | 0.43%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 4         | 0.43%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.43%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 4         | 0.43%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 4         | 0.43%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 4         | 0.43%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.43%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 0.43%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 4         | 0.43%   |
| AMD E1-1500 APU with Radeon HD Graphics       | 4         | 0.43%   |
| AMD Athlon II X2 250 Processor                | 4         | 0.43%   |
| AMD Athlon 64 Processor 3000+                 | 4         | 0.43%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 4         | 0.43%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.33%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 3         | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 138       | 14.98%  |
| Intel Core i7                  | 85        | 9.23%   |
| Intel Atom                     | 83        | 9.01%   |
| Intel Celeron                  | 76        | 8.25%   |
| Intel Core 2 Duo               | 71        | 7.71%   |
| Intel Core i3                  | 65        | 7.06%   |
| Intel Pentium Dual             | 26        | 2.82%   |
| Intel Pentium                  | 26        | 2.82%   |
| Intel Pentium Dual-Core        | 24        | 2.61%   |
| AMD Athlon 64 X2               | 20        | 2.17%   |
| Other                          | 19        | 2.06%   |
| Intel Core 2                   | 19        | 2.06%   |
| AMD E                          | 17        | 1.85%   |
| Intel Xeon                     | 16        | 1.74%   |
| Intel Pentium 4                | 16        | 1.74%   |
| AMD Ryzen 7                    | 15        | 1.63%   |
| AMD Ryzen 5                    | 15        | 1.63%   |
| AMD E1                         | 12        | 1.3%    |
| AMD A6                         | 12        | 1.3%    |
| Intel Genuine                  | 11        | 1.19%   |
| AMD Athlon II X2               | 10        | 1.09%   |
| AMD A4                         | 10        | 1.09%   |
| Intel Core 2 Quad              | 9         | 0.98%   |
| AMD Athlon 64                  | 8         | 0.87%   |
| AMD A10                        | 8         | 0.87%   |
| AMD Ryzen 3                    | 7         | 0.76%   |
| Intel Celeron M                | 6         | 0.65%   |
| AMD FX                         | 6         | 0.65%   |
| Intel Pentium M                | 5         | 0.54%   |
| AMD E2                         | 5         | 0.54%   |
| AMD A8                         | 5         | 0.54%   |
| Intel Pentium Silver           | 4         | 0.43%   |
| Intel Pentium D                | 4         | 0.43%   |
| AMD Phenom II X4               | 4         | 0.43%   |
| AMD Mobile Sempron             | 4         | 0.43%   |
| AMD Athlon X2                  | 4         | 0.43%   |
| AMD Athlon                     | 4         | 0.43%   |
| Intel Celeron Dual-Core        | 3         | 0.33%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.33%   |
| AMD GX                         | 3         | 0.33%   |
| AMD C-50                       | 3         | 0.33%   |
| Intel Core Duo                 | 2         | 0.22%   |
| AMD Sempron                    | 2         | 0.22%   |
| AMD Ryzen Threadripper         | 2         | 0.22%   |
| AMD Ryzen 7 PRO                | 2         | 0.22%   |
| AMD Phenom II                  | 2         | 0.22%   |
| AMD C-70                       | 2         | 0.22%   |
| AMD C-60                       | 2         | 0.22%   |
| AMD Athlon X4                  | 2         | 0.22%   |
| Intel Pentium III              | 1         | 0.11%   |
| Intel Pentium Gold             | 1         | 0.11%   |
| Intel Mobile Pentium 4         | 1         | 0.11%   |
| Intel Core m3                  | 1         | 0.11%   |
| Intel Core i9                  | 1         | 0.11%   |
| Intel Core 2 Solo              | 1         | 0.11%   |
| Intel Core 2 Extreme           | 1         | 0.11%   |
| ARM BCM                        | 1         | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.11%   |
| AMD Turion 64 X2               | 1         | 0.11%   |
| AMD Turion 64 Mobile           | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 542       | 58.85%  |
| 4      | 229       | 24.86%  |
| 1      | 96        | 10.42%  |
| 8      | 21        | 2.28%   |
| 6      | 19        | 2.06%   |
| 3      | 6         | 0.65%   |
| 12     | 3         | 0.33%   |
| 64     | 1         | 0.11%   |
| 40     | 1         | 0.11%   |
| 20     | 1         | 0.11%   |
| 16     | 1         | 0.11%   |
| 10     | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 914       | 99.24%  |
| 2      | 6         | 0.65%   |
| 4      | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 537       | 58.31%  |
| 2      | 383       | 41.59%  |
| 8      | 1         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 861       | 93.49%  |
| 32-bit         | 52        | 5.65%   |
| Unknown        | 8         | 0.87%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 176       | 18.84%  |
| 0x206a7    | 66        | 7.07%   |
| 0x1067a    | 45        | 4.82%   |
| 0x6fd      | 43        | 4.6%    |
| 0x306a9    | 37        | 3.96%   |
| 0x40651    | 25        | 2.68%   |
| 0x306c3    | 25        | 2.68%   |
| 0x406c4    | 24        | 2.57%   |
| 0x20655    | 23        | 2.46%   |
| 0x05000119 | 22        | 2.36%   |
| 0x30678    | 21        | 2.25%   |
| 0x106ca    | 21        | 2.25%   |
| 0x406e3    | 16        | 1.71%   |
| 0x406c3    | 16        | 1.71%   |
| 0x106c2    | 16        | 1.71%   |
| 0x6fb      | 15        | 1.61%   |
| 0x806ec    | 13        | 1.39%   |
| 0x6f6      | 13        | 1.39%   |
| 0x10676    | 13        | 1.39%   |
| 0x806e9    | 10        | 1.07%   |
| 0x20652    | 10        | 1.07%   |
| 0x06006705 | 10        | 1.07%   |
| 0x6e8      | 9         | 0.96%   |
| 0x6d8      | 9         | 0.96%   |
| 0x306d4    | 9         | 0.96%   |
| 0x0700010f | 9         | 0.96%   |
| 0x05000029 | 9         | 0.96%   |
| 0x706a1    | 8         | 0.86%   |
| 0x06001119 | 8         | 0.86%   |
| 0x010000c8 | 8         | 0.86%   |
| 0x706a8    | 7         | 0.75%   |
| 0x906ea    | 6         | 0.64%   |
| 0x806ea    | 6         | 0.64%   |
| 0x806c1    | 6         | 0.64%   |
| 0x30661    | 6         | 0.64%   |
| 0x906e9    | 5         | 0.54%   |
| 0x6f2      | 5         | 0.54%   |
| 0x506c9    | 5         | 0.54%   |
| 0x10661    | 5         | 0.54%   |
| 0x08701021 | 5         | 0.54%   |
| 0x08600106 | 5         | 0.54%   |
| 0x06000852 | 5         | 0.54%   |
| 0xf41      | 4         | 0.43%   |
| 0x806eb    | 4         | 0.43%   |
| 0x706e5    | 4         | 0.43%   |
| 0x6ec      | 4         | 0.43%   |
| 0x08600103 | 4         | 0.43%   |
| 0x06006704 | 4         | 0.43%   |
| 0xf65      | 3         | 0.32%   |
| 0xf49      | 3         | 0.32%   |
| 0xf43      | 3         | 0.32%   |
| 0xf29      | 3         | 0.32%   |
| 0xa0653    | 3         | 0.32%   |
| 0x906c0    | 3         | 0.32%   |
| 0x6fa      | 3         | 0.32%   |
| 0x506e3    | 3         | 0.32%   |
| 0x30673    | 3         | 0.32%   |
| 0x206d7    | 3         | 0.32%   |
| 0x08108102 | 3         | 0.32%   |
| 0x0810100b | 3         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Core            | 94        | 10.21%  |
| SandyBridge     | 80        | 8.69%   |
| Silvermont      | 73        | 7.93%   |
| Penryn          | 67        | 7.27%   |
| Haswell         | 63        | 6.84%   |
| KabyLake        | 53        | 5.75%   |
| IvyBridge       | 51        | 5.54%   |
| Bonnell         | 44        | 4.78%   |
| Westmere        | 43        | 4.67%   |
| K8 Hammer       | 40        | 4.34%   |
| Bobcat          | 33        | 3.58%   |
| Skylake         | 25        | 2.71%   |
| NetBurst        | 25        | 2.71%   |
| P6              | 24        | 2.61%   |
| K10             | 24        | 2.61%   |
| Excavator       | 21        | 2.28%   |
| Zen 2           | 19        | 2.06%   |
| Goldmont plus   | 17        | 1.85%   |
| Piledriver      | 16        | 1.74%   |
| Zen+            | 13        | 1.41%   |
| Jaguar          | 11        | 1.19%   |
| Broadwell       | 11        | 1.19%   |
| Zen             | 8         | 0.87%   |
| Puma            | 8         | 0.87%   |
| Unknown         | 8         | 0.87%   |
| TigerLake       | 7         | 0.76%   |
| Goldmont        | 7         | 0.76%   |
| CometLake       | 7         | 0.76%   |
| K8 & K10 hybrid | 6         | 0.65%   |
| IceLake         | 6         | 0.65%   |
| Nehalem         | 5         | 0.54%   |
| Zen 3           | 4         | 0.43%   |
| Tremont         | 3         | 0.33%   |
| K10 Llano       | 3         | 0.33%   |
| Steamroller     | 2         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 533       | 53.19%  |
| AMD                              | 246       | 24.55%  |
| Nvidia                           | 204       | 20.36%  |
| VIA Technologies                 | 6         | 0.6%    |
| Silicon Integrated Systems [SiS] | 6         | 0.6%    |
| Matrox Electronics Systems       | 6         | 0.6%    |
| S3 Graphics                      | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 62        | 5.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 44        | 4.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 39        | 3.58%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 39        | 3.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 2.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 2.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 2.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 26        | 2.39%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 25        | 2.3%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 19        | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 17        | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 1.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 1.29%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 1.19%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 12        | 1.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 0.92%   |
| Intel HD Graphics 620                                                                    | 10        | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 0.92%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 10        | 0.92%   |
| AMD Renoir                                                                               | 10        | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                               | 9         | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 0.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9         | 0.83%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 8         | 0.74%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 8         | 0.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 0.64%   |
| Intel HD Graphics 5500                                                                   | 7         | 0.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7         | 0.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.64%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 7         | 0.64%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                 | 7         | 0.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7         | 0.64%   |
| Intel UHD Graphics 620                                                                   | 6         | 0.55%   |
| Intel HD Graphics 530                                                                    | 6         | 0.55%   |
| Intel HD Graphics 500                                                                    | 6         | 0.55%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 6         | 0.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 0.55%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 0.46%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.46%   |
| Intel 82865G Integrated Graphics Controller                                              | 5         | 0.46%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 5         | 0.46%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.46%   |
| AMD Kabini [Radeon HD 8210]                                                              | 5         | 0.46%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 5         | 0.46%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5         | 0.46%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 4         | 0.37%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.37%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 4         | 0.37%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 4         | 0.37%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 4         | 0.37%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.37%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4         | 0.37%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 4         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 453       | 49.08%  |
| 1 x AMD         | 200       | 21.67%  |
| 1 x Nvidia      | 144       | 15.6%   |
| Intel + Nvidia  | 50        | 5.42%   |
| Intel + AMD     | 23        | 2.49%   |
| 2 x AMD         | 19        | 2.06%   |
| Other           | 9         | 0.98%   |
| 1 x VIA         | 6         | 0.65%   |
| 1 x SiS         | 6         | 0.65%   |
| 1 x Matrox      | 5         | 0.54%   |
| AMD + Nvidia    | 4         | 0.43%   |
| 2 x Nvidia      | 2         | 0.22%   |
| 1 x S3 Graphics | 1         | 0.11%   |
| Nvidia + Matrox | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 805       | 87.03%  |
| Proprietary | 80        | 8.65%   |
| Unknown     | 40        | 4.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 497       | 53.5%   |
| 0.01-0.5   | 237       | 25.51%  |
| 1.01-2.0   | 82        | 8.83%   |
| 0.51-1.0   | 68        | 7.32%   |
| 3.01-4.0   | 25        | 2.69%   |
| 7.01-8.0   | 7         | 0.75%   |
| 5.01-6.0   | 5         | 0.54%   |
| 2.01-3.0   | 5         | 0.54%   |
| 8.01-16.0  | 3         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 140       | 15.66%  |
| AU Optronics            | 107       | 11.97%  |
| LG Display              | 80        | 8.95%   |
| Chimei Innolux          | 69        | 7.72%   |
| BOE                     | 59        | 6.6%    |
| Dell                    | 44        | 4.92%   |
| Goldstar                | 33        | 3.69%   |
| Hewlett-Packard         | 31        | 3.47%   |
| Chi Mei Optoelectronics | 29        | 3.24%   |
| Acer                    | 29        | 3.24%   |
| LG Philips              | 23        | 2.57%   |
| HannStar                | 19        | 2.13%   |
| Apple                   | 18        | 2.01%   |
| AOC                     | 17        | 1.9%    |
| Philips                 | 16        | 1.79%   |
| Lenovo                  | 16        | 1.79%   |
| BenQ                    | 14        | 1.57%   |
| Ancor Communications    | 12        | 1.34%   |
| CPT                     | 11        | 1.23%   |
| InfoVision              | 10        | 1.12%   |
| Vizio                   | 7         | 0.78%   |
| Unknown                 | 7         | 0.78%   |
| NEC Computers           | 7         | 0.78%   |
| Iiyama                  | 7         | 0.78%   |
| Sharp                   | 6         | 0.67%   |
| Sony                    | 5         | 0.56%   |
| Sceptre Tech            | 4         | 0.45%   |
| Toshiba                 | 3         | 0.34%   |
| PANDA                   | 3         | 0.34%   |
| LG Electronics          | 3         | 0.34%   |
| Eizo                    | 3         | 0.34%   |
| ___                     | 2         | 0.22%   |
| ViewSonic               | 2         | 0.22%   |
| Videoseven              | 2         | 0.22%   |
| Positivo                | 2         | 0.22%   |
| Plain Tree Systems      | 2         | 0.22%   |
| Panasonic               | 2         | 0.22%   |
| MSI                     | 2         | 0.22%   |
| Lenovo Group Limited    | 2         | 0.22%   |
| IOD                     | 2         | 0.22%   |
| InnoLux Display         | 2         | 0.22%   |
| IBM                     | 2         | 0.22%   |
| Fujitsu Siemens         | 2         | 0.22%   |
| FL_                     | 2         | 0.22%   |
| Elo Touch               | 2         | 0.22%   |
| CVT                     | 2         | 0.22%   |
| ASUSTek Computer        | 2         | 0.22%   |
| Vestel                  | 1         | 0.11%   |
| Unknown (ADA)           | 1         | 0.11%   |
| STD                     | 1         | 0.11%   |
| SHD                     | 1         | 0.11%   |
| Proview                 | 1         | 0.11%   |
| Pioneer                 | 1         | 0.11%   |
| PAR                     | 1         | 0.11%   |
| Nvidia                  | 1         | 0.11%   |
| NCS                     | 1         | 0.11%   |
| MOT                     | 1         | 0.11%   |
| Lite-On                 | 1         | 0.11%   |
| KDC                     | 1         | 0.11%   |
| IPS                     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 10        | 1.11%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 8         | 0.88%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.66%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 5         | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.44%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.44%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 4         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.33%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 331x207mm 15.4-inch            | 3         | 0.33%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch              | 3         | 0.33%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 3         | 0.33%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.33%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch                | 3         | 0.33%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 3         | 0.33%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 3         | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 3         | 0.33%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                        | 3         | 0.33%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 3         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 3         | 0.33%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 3         | 0.33%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.33%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.33%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                     | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.33%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 3         | 0.33%   |
| ___ LCD TV ___0101 1360x768                                              | 2         | 0.22%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                       | 2         | 0.22%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                  | 2         | 0.22%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch     | 2         | 0.22%   |
| Samsung Electronics SyncMaster SAM0119 1280x1024 352x264mm 17.3-inch     | 2         | 0.22%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch        | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.22%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 2         | 0.22%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.22%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch              | 2         | 0.22%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.22%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch             | 2         | 0.22%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                 | 2         | 0.22%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.22%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch              | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 274       | 31.07%  |
| 1920x1080 (FHD)    | 216       | 24.49%  |
| 1280x800 (WXGA)    | 83        | 9.41%   |
| 1280x1024 (SXGA)   | 59        | 6.69%   |
| 1600x900 (HD+)     | 43        | 4.88%   |
| 1680x1050 (WSXGA+) | 36        | 4.08%   |
| 1024x600           | 27        | 3.06%   |
| 1920x1200 (WUXGA)  | 23        | 2.61%   |
| 1440x900 (WXGA+)   | 23        | 2.61%   |
| 2560x1440 (QHD)    | 19        | 2.15%   |
| 3840x2160 (4K)     | 17        | 1.93%   |
| 1024x768 (XGA)     | 10        | 1.13%   |
| Unknown            | 8         | 0.91%   |
| 1360x768           | 7         | 0.79%   |
| 2288x1287          | 4         | 0.45%   |
| 1280x720 (HD)      | 4         | 0.45%   |
| 2560x1600          | 3         | 0.34%   |
| 3840x2400          | 2         | 0.23%   |
| 3600x1200          | 2         | 0.23%   |
| 3440x1440          | 2         | 0.23%   |
| 2880x1800          | 2         | 0.23%   |
| 2560x1080          | 2         | 0.23%   |
| 2048x1536          | 2         | 0.23%   |
| 1920x540           | 2         | 0.23%   |
| 1280x768           | 2         | 0.23%   |
| 5760x2160          | 1         | 0.11%   |
| 3200x1800 (QHD+)   | 1         | 0.11%   |
| 3200x1080          | 1         | 0.11%   |
| 2736x1824          | 1         | 0.11%   |
| 2160x1440          | 1         | 0.11%   |
| 2160x1200          | 1         | 0.11%   |
| 2048x1152          | 1         | 0.11%   |
| 1600x1200          | 1         | 0.11%   |
| 1360x765           | 1         | 0.11%   |
| 1152x864           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 254       | 28.44%  |
| 13      | 85        | 9.52%   |
| 14      | 83        | 9.29%   |
| 17      | 66        | 7.39%   |
| 24      | 43        | 4.82%   |
| 19      | 38        | 4.26%   |
| Unknown | 36        | 4.03%   |
| 11      | 34        | 3.81%   |
| 23      | 33        | 3.7%    |
| 21      | 32        | 3.58%   |
| 27      | 28        | 3.14%   |
| 10      | 27        | 3.02%   |
| 22      | 23        | 2.58%   |
| 20      | 23        | 2.58%   |
| 18      | 19        | 2.13%   |
| 12      | 17        | 1.9%    |
| 31      | 6         | 0.67%   |
| 72      | 5         | 0.56%   |
| 84      | 3         | 0.34%   |
| 34      | 3         | 0.34%   |
| 26      | 3         | 0.34%   |
| 8       | 3         | 0.34%   |
| 48      | 2         | 0.22%   |
| 47      | 2         | 0.22%   |
| 41      | 2         | 0.22%   |
| 39      | 2         | 0.22%   |
| 38      | 2         | 0.22%   |
| 25      | 2         | 0.22%   |
| 9       | 2         | 0.22%   |
| 142     | 1         | 0.11%   |
| 65      | 1         | 0.11%   |
| 63      | 1         | 0.11%   |
| 55      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 42      | 1         | 0.11%   |
| 40      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 33      | 1         | 0.11%   |
| 32      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 16      | 1         | 0.11%   |
| 7       | 1         | 0.11%   |
| 5       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 400       | 45.2%   |
| 201-300        | 119       | 13.45%  |
| 501-600        | 106       | 11.98%  |
| 401-500        | 103       | 11.64%  |
| 351-400        | 75        | 8.47%   |
| Unknown        | 36        | 4.07%   |
| 601-700        | 9         | 1.02%   |
| 1501-2000      | 8         | 0.9%    |
| 1001-1500      | 8         | 0.9%    |
| 801-900        | 6         | 0.68%   |
| 701-800        | 5         | 0.56%   |
| 101-200        | 5         | 0.56%   |
| 901-1000       | 4         | 0.45%   |
| More than 2000 | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 567       | 67.26%  |
| 16/10   | 163       | 19.34%  |
| 5/4     | 56        | 6.64%   |
| Unknown | 28        | 3.32%   |
| 4/3     | 18        | 2.14%   |
| 3/2     | 4         | 0.47%   |
| 21/9    | 4         | 0.47%   |
| 6/5     | 2         | 0.24%   |
| 1.00    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 251       | 28.27%  |
| 81-90          | 139       | 15.65%  |
| 201-250        | 109       | 12.27%  |
| 151-200        | 71        | 8%      |
| 141-150        | 44        | 4.95%   |
| Unknown        | 36        | 4.05%   |
| 51-60          | 34        | 3.83%   |
| 71-80          | 30        | 3.38%   |
| 301-350        | 30        | 3.38%   |
| 41-50          | 29        | 3.27%   |
| 121-130        | 27        | 3.04%   |
| 251-300        | 18        | 2.03%   |
| More than 1000 | 15        | 1.69%   |
| 61-70          | 14        | 1.58%   |
| 501-1000       | 12        | 1.35%   |
| 351-500        | 11        | 1.24%   |
| 131-140        | 8         | 0.9%    |
| 1-40           | 5         | 0.56%   |
| 111-120        | 3         | 0.34%   |
| 91-100         | 2         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 321       | 36.73%  |
| 101-120       | 312       | 35.7%   |
| 121-160       | 157       | 17.96%  |
| Unknown       | 36        | 4.12%   |
| 161-240       | 21        | 2.4%    |
| 1-50          | 19        | 2.17%   |
| More than 240 | 8         | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 816       | 87.37%  |
| 2     | 81        | 8.67%   |
| 0     | 30        | 3.21%   |
| 3     | 6         | 0.64%   |
| 4     | 1         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 482       | 33.66%  |
| Intel                             | 315       | 22%     |
| Qualcomm Atheros                  | 204       | 14.25%  |
| Broadcom                          | 114       | 7.96%   |
| Nvidia                            | 42        | 2.93%   |
| Ralink Technology                 | 39        | 2.72%   |
| Marvell Technology Group          | 36        | 2.51%   |
| Broadcom Limited                  | 35        | 2.44%   |
| Ralink                            | 29        | 2.03%   |
| TP-Link                           | 16        | 1.12%   |
| Samsung Electronics               | 14        | 0.98%   |
| VIA Technologies                  | 9         | 0.63%   |
| Attansic Technology               | 9         | 0.63%   |
| ASIX Electronics                  | 9         | 0.63%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.35%   |
| Xiaomi                            | 4         | 0.28%   |
| Qualcomm Atheros Communications   | 4         | 0.28%   |
| Huawei Technologies               | 4         | 0.28%   |
| D-Link System                     | 4         | 0.28%   |
| Belkin Components                 | 4         | 0.28%   |
| AMD                               | 4         | 0.28%   |
| MediaTek                          | 3         | 0.21%   |
| JMicron Technology                | 3         | 0.21%   |
| Hewlett-Packard                   | 3         | 0.21%   |
| D-Link                            | 3         | 0.21%   |
| 3Com                              | 3         | 0.21%   |
| ULi Electronics                   | 2         | 0.14%   |
| NetGear                           | 2         | 0.14%   |
| Intersil                          | 2         | 0.14%   |
| Fibocom                           | 2         | 0.14%   |
| Dell                              | 2         | 0.14%   |
| ZyXEL Communications              | 1         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| Trident Microsystems              | 1         | 0.07%   |
| T & A Mobile Phones               | 1         | 0.07%   |
| Sitecom Europe                    | 1         | 0.07%   |
| Seeed                             | 1         | 0.07%   |
| Research In Motion                | 1         | 0.07%   |
| Realtek                           | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| Microchip Technology              | 1         | 0.07%   |
| LSI                               | 1         | 0.07%   |
| Logitec                           | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| LG Electronics                    | 1         | 0.07%   |
| Lab126                            | 1         | 0.07%   |
| ICS Advent                        | 1         | 0.07%   |
| Ericsson Business Mobile Networks | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |
| Arduino SA                        | 1         | 0.07%   |
| Aquantia                          | 1         | 0.07%   |
| Apple                             | 1         | 0.07%   |
| ADMtek                            | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 266       | 16.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 106       | 6.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 39        | 2.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 35        | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 33        | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 29        | 1.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 28        | 1.72%   |
| Intel Wireless 7260                                                           | 27        | 1.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 26        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 21        | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 20        | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 18        | 1.1%    |
| Ralink MT7601U Wireless Adapter                                               | 16        | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 15        | 0.92%   |
| Nvidia MCP61 Ethernet                                                         | 14        | 0.86%   |
| Intel Wireless 7265                                                           | 13        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 12        | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 12        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 12        | 0.74%   |
| Intel Wi-Fi 6 AX200                                                           | 12        | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 12        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 11        | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 11        | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 11        | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 10        | 0.61%   |
| Realtek 802.11ac NIC                                                          | 10        | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 10        | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 9         | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 9         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 9         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 9         | 0.55%   |
| Intel Wireless 3165                                                           | 9         | 0.55%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                      | 9         | 0.55%   |
| Attansic AR8152 v2.0 Fast Ethernet                                            | 9         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 8         | 0.49%   |
| Intel Wireless 3160                                                           | 8         | 0.49%   |
| Intel WiFi Link 5100                                                          | 8         | 0.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 7         | 0.43%   |
| Ralink RT5370 Wireless Adapter                                                | 7         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 7         | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 7         | 0.43%   |
| Intel Wireless 8265 / 8275                                                    | 7         | 0.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 7         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 7         | 0.43%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 7         | 0.43%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 6         | 0.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 6         | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 6         | 0.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 6         | 0.37%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 6         | 0.37%   |
| Nvidia CK804 Ethernet Controller                                              | 6         | 0.37%   |
| Intel Wireless 8260                                                           | 6         | 0.37%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 6         | 0.37%   |
| Intel Ethernet Connection I218-LM                                             | 6         | 0.37%   |
| Intel 82579V Gigabit Network Connection                                       | 6         | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 6         | 0.37%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 6         | 0.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 6         | 0.37%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 6         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 226       | 31.43%  |
| Qualcomm Atheros                | 171       | 23.78%  |
| Realtek Semiconductor           | 125       | 17.39%  |
| Broadcom                        | 69        | 9.6%    |
| Ralink Technology               | 39        | 5.42%   |
| Ralink                          | 29        | 4.03%   |
| Broadcom Limited                | 19        | 2.64%   |
| TP-Link                         | 16        | 2.23%   |
| Qualcomm Atheros Communications | 4         | 0.56%   |
| Belkin Components               | 4         | 0.56%   |
| NetGear                         | 2         | 0.28%   |
| MediaTek                        | 2         | 0.28%   |
| D-Link System                   | 2         | 0.28%   |
| D-Link                          | 2         | 0.28%   |
| ZyXEL Communications            | 1         | 0.14%   |
| Sitecom Europe                  | 1         | 0.14%   |
| Samsung Electronics             | 1         | 0.14%   |
| Realtek                         | 1         | 0.14%   |
| Marvell Technology Group        | 1         | 0.14%   |
| Logitec                         | 1         | 0.14%   |
| Linksys                         | 1         | 0.14%   |
| Dell                            | 1         | 0.14%   |
| ASUSTek Computer                | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 39        | 5.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 29        | 4.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 28        | 3.87%   |
| Intel Wireless 7260                                                           | 27        | 3.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 26        | 3.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 21        | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 20        | 2.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 18        | 2.49%   |
| Ralink MT7601U Wireless Adapter                                               | 16        | 2.21%   |
| Intel Wireless 7265                                                           | 13        | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 12        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 12        | 1.66%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 12        | 1.66%   |
| Intel Wi-Fi 6 AX200                                                           | 12        | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 12        | 1.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 11        | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 11        | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 11        | 1.52%   |
| Realtek 802.11ac NIC                                                          | 10        | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 9         | 1.24%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 9         | 1.24%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 9         | 1.24%   |
| Intel Wireless 3165                                                           | 9         | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 8         | 1.11%   |
| Intel Wireless 3160                                                           | 8         | 1.11%   |
| Intel WiFi Link 5100                                                          | 8         | 1.11%   |
| Ralink RT5370 Wireless Adapter                                                | 7         | 0.97%   |
| Intel Wireless 8265 / 8275                                                    | 7         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 7         | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 7         | 0.97%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 6         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 6         | 0.83%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 6         | 0.83%   |
| Intel Wireless 8260                                                           | 6         | 0.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 6         | 0.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 6         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 5         | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 5         | 0.69%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 5         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5         | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 5         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 5         | 0.69%   |
| Intel Centrino Ultimate-N 6300                                                | 5         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 4         | 0.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 4         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 4         | 0.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 4         | 0.55%   |
| Ralink RT5572 Wireless Adapter                                                | 4         | 0.55%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 4         | 0.55%   |
| Intel Wireless-AC 9260                                                        | 4         | 0.55%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 0.55%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 0.55%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 4         | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 4         | 0.55%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 4         | 0.55%   |
| Broadcom Limited BCM4311 802.11a/b/g                                          | 4         | 0.55%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4         | 0.55%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 4         | 0.55%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 4         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 433       | 49.43%  |
| Intel                            | 151       | 17.24%  |
| Qualcomm Atheros                 | 59        | 6.74%   |
| Broadcom                         | 58        | 6.62%   |
| Nvidia                           | 42        | 4.79%   |
| Marvell Technology Group         | 35        | 4%      |
| Broadcom Limited                 | 16        | 1.83%   |
| Samsung Electronics              | 13        | 1.48%   |
| VIA Technologies                 | 9         | 1.03%   |
| Attansic Technology              | 9         | 1.03%   |
| ASIX Electronics                 | 9         | 1.03%   |
| Silicon Integrated Systems [SiS] | 5         | 0.57%   |
| Xiaomi                           | 4         | 0.46%   |
| JMicron Technology               | 3         | 0.34%   |
| Huawei Technologies              | 3         | 0.34%   |
| 3Com                             | 3         | 0.34%   |
| ULi Electronics                  | 2         | 0.23%   |
| Fibocom                          | 2         | 0.23%   |
| D-Link System                    | 2         | 0.23%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.11%   |
| Trident Microsystems             | 1         | 0.11%   |
| T & A Mobile Phones              | 1         | 0.11%   |
| Research In Motion               | 1         | 0.11%   |
| Qualcomm                         | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.11%   |
| Motorola PCS                     | 1         | 0.11%   |
| Microchip Technology             | 1         | 0.11%   |
| MediaTek                         | 1         | 0.11%   |
| LG Electronics                   | 1         | 0.11%   |
| Lab126                           | 1         | 0.11%   |
| Intersil                         | 1         | 0.11%   |
| ICS Advent                       | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |
| D-Link                           | 1         | 0.11%   |
| Aquantia                         | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |
| ADMtek                           | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 266       | 29.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 106       | 11.95%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 35        | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 33        | 3.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 1.69%   |
| Nvidia MCP61 Ethernet                                             | 14        | 1.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 1.13%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 10        | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.01%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 9         | 1.01%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 7         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 7         | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.68%   |
| Nvidia CK804 Ethernet Controller                                  | 6         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.68%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.56%   |
| Nvidia MCP67 Ethernet                                             | 5         | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 5         | 0.56%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 5         | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 4         | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.45%   |
| Nvidia MCP77 Ethernet                                             | 4         | 0.45%   |
| Nvidia MCP73 Ethernet                                             | 4         | 0.45%   |
| Nvidia MCP51 Ethernet Controller                                  | 4         | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.45%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 4         | 0.45%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 4         | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.45%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.45%   |
| Intel 82573L Gigabit Ethernet Controller                          | 4         | 0.45%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 4         | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.45%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 4         | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3         | 0.34%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.34%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.34%   |
| Intel PRO/100 VE Network Connection                               | 3         | 0.34%   |
| Intel NM10/ICH7 Family LAN Controller                             | 3         | 0.34%   |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.34%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.34%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 3         | 0.34%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 3         | 0.34%   |
| ASIX AX88772A Fast Ethernet                                       | 3         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 816       | 53.54%  |
| WiFi     | 686       | 45.01%  |
| Modem    | 21        | 1.38%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 536       | 57.88%  |
| Ethernet | 390       | 42.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 521       | 56.57%  |
| 1     | 337       | 36.59%  |
| 0     | 43        | 4.67%   |
| 3     | 15        | 1.63%   |
| 4     | 4         | 0.43%   |
| 6     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 806       | 86.48%  |
| Yes  | 126       | 13.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 135       | 32.37%  |
| Realtek Semiconductor           | 39        | 9.35%   |
| Qualcomm Atheros Communications | 37        | 8.87%   |
| Cambridge Silicon Radio         | 35        | 8.39%   |
| Broadcom                        | 34        | 8.15%   |
| IMC Networks                    | 17        | 4.08%   |
| Apple                           | 16        | 3.84%   |
| Lite-On Technology              | 15        | 3.6%    |
| Hewlett-Packard                 | 15        | 3.6%    |
| Foxconn / Hon Hai               | 13        | 3.12%   |
| Dell                            | 13        | 3.12%   |
| Toshiba                         | 10        | 2.4%    |
| Ralink                          | 9         | 2.16%   |
| Alps Electric                   | 8         | 1.92%   |
| ASUSTek Computer                | 6         | 1.44%   |
| Ralink Technology               | 2         | 0.48%   |
| MediaTek                        | 2         | 0.48%   |
| Askey Computer                  | 2         | 0.48%   |
| Qcom                            | 1         | 0.24%   |
| Micro Star International        | 1         | 0.24%   |
| Marvell Semiconductor           | 1         | 0.24%   |
| Logitech                        | 1         | 0.24%   |
| Integrated System Solution      | 1         | 0.24%   |
| HTC (High Tech Computer)        | 1         | 0.24%   |
| Fujitsu                         | 1         | 0.24%   |
| Dynex                           | 1         | 0.24%   |
| Chicony Electronics             | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 73        | 17.46%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 35        | 8.37%   |
| Realtek Bluetooth Radio                                                             | 23        | 5.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 20        | 4.78%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 19        | 4.55%   |
| Intel AX200 Bluetooth                                                               | 11        | 2.63%   |
| Intel Bluetooth Device                                                              | 10        | 2.39%   |
| Apple Bluetooth Host Controller                                                     | 10        | 2.39%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 2.15%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 9         | 2.15%   |
| Intel AX201 Bluetooth                                                               | 9         | 2.15%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 1.91%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 1.44%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.44%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.44%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 1.2%    |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.2%    |
| IMC Networks Bluetooth module                                                       | 5         | 1.2%    |
| IMC Networks Bluetooth Device                                                       | 5         | 1.2%    |
| Apple Bluetooth HCI                                                                 | 5         | 1.2%    |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.96%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.96%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 0.96%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.96%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.72%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 0.72%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.72%   |
| Dell Wireless 350 Bluetooth                                                         | 3         | 0.72%   |
| Broadcom HP Portable Bumble Bee                                                     | 3         | 0.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.72%   |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.72%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 3         | 0.72%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.48%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.48%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.48%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.48%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.48%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.48%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.48%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.48%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.48%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.48%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 2         | 0.48%   |
| Askey Bluetooth Device                                                              | 2         | 0.48%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 2         | 0.48%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 2         | 0.48%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.24%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.24%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.24%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.24%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.24%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.24%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.24%   |
| Micro Star International Bluetooth EDR Device                                       | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 617       | 57.77%  |
| AMD                                          | 217       | 20.32%  |
| Nvidia                                       | 149       | 13.95%  |
| C-Media Electronics                          | 18        | 1.69%   |
| VIA Technologies                             | 11        | 1.03%   |
| Creative Labs                                | 10        | 0.94%   |
| Silicon Integrated Systems [SiS]             | 7         | 0.66%   |
| Logitech                                     | 6         | 0.56%   |
| GN Netcom                                    | 4         | 0.37%   |
| XMOS                                         | 3         | 0.28%   |
| ULi Electronics                              | 2         | 0.19%   |
| Texas Instruments                            | 2         | 0.19%   |
| Plantronics                                  | 2         | 0.19%   |
| Generalplus Technology                       | 2         | 0.19%   |
| Creative Technology                          | 2         | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.09%   |
| Unknown                                      | 1         | 0.09%   |
| Realtek Semiconductor                        | 1         | 0.09%   |
| Razer USA                                    | 1         | 0.09%   |
| Nordic Semiconductor ASA                     | 1         | 0.09%   |
| KORG                                         | 1         | 0.09%   |
| Guillemot                                    | 1         | 0.09%   |
| Focusrite-Novation                           | 1         | 0.09%   |
| ESI                                          | 1         | 0.09%   |
| Ensoniq                                      | 1         | 0.09%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.09%   |
| Elgato Systems                               | 1         | 0.09%   |
| Dell                                         | 1         | 0.09%   |
| Cirrus Logic                                 | 1         | 0.09%   |
| ASUSTek Computer                             | 1         | 0.09%   |
| Asahi Kasei Microsystems                     | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 82        | 6.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 62        | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 60        | 4.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 57        | 4.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 53        | 4.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 45        | 3.58%   |
| AMD FCH Azalia Controller                                                                         | 42        | 3.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 41        | 3.26%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 36        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 29        | 2.31%   |
| Intel 8 Series HD Audio Controller                                                                | 28        | 2.23%   |
| AMD Wrestler HDMI Audio                                                                           | 28        | 2.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 27        | 2.15%   |
| Nvidia High Definition Audio Controller                                                           | 25        | 1.99%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 25        | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 1.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 23        | 1.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 20        | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 17        | 1.35%   |
| AMD High Definition Audio Controller                                                              | 17        | 1.35%   |
| Nvidia MCP61 High Definition Audio                                                                | 15        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 11        | 0.88%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 0.8%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 10        | 0.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 0.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 9         | 0.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 9         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 0.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.64%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 0.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 0.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 0.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.48%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 6         | 0.48%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 6         | 0.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 6         | 0.48%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 5         | 0.4%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 5         | 0.4%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 5         | 0.4%    |
| Nvidia MCP67 High Definition Audio                                                                | 5         | 0.4%    |
| Nvidia MCP51 High Definition Audio                                                                | 5         | 0.4%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.4%    |
| Nvidia CK804 AC'97 Audio Controller                                                               | 5         | 0.4%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.4%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 0.4%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 5         | 0.4%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 5         | 0.4%    |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 5         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 140       | 21.94%  |
| Samsung Electronics | 130       | 20.38%  |
| SK hynix            | 104       | 16.3%   |
| Micron Technology   | 52        | 8.15%   |
| Kingston            | 52        | 8.15%   |
| Crucial             | 22        | 3.45%   |
| Corsair             | 22        | 3.45%   |
| Nanya Technology    | 16        | 2.51%   |
| A-DATA Technology   | 15        | 2.35%   |
| G.Skill             | 13        | 2.04%   |
| Elpida              | 12        | 1.88%   |
| Unknown (ABCD)      | 8         | 1.25%   |
| Smart               | 7         | 1.1%    |
| Team                | 4         | 0.63%   |
| Patriot             | 4         | 0.63%   |
| Teikon              | 3         | 0.47%   |
| Qimonda             | 3         | 0.47%   |
| Unknown             | 3         | 0.47%   |
| Transcend           | 2         | 0.31%   |
| Timetec             | 2         | 0.31%   |
| Ramaxel Technology  | 2         | 0.31%   |
| ASint Technology    | 2         | 0.31%   |
| Apacer              | 2         | 0.31%   |
| Unknown (07FB)      | 1         | 0.16%   |
| Unifosa             | 1         | 0.16%   |
| Toshiba             | 1         | 0.16%   |
| Smart Brazil        | 1         | 0.16%   |
| Sesame              | 1         | 0.16%   |
| Princeton           | 1         | 0.16%   |
| PNY                 | 1         | 0.16%   |
| Neo Forza           | 1         | 0.16%   |
| Multilaser          | 1         | 0.16%   |
| Infineon            | 1         | 0.16%   |
| HMD                 | 1         | 0.16%   |
| High Bridge         | 1         | 0.16%   |
| Goldkey             | 1         | 0.16%   |
| Golden Empire       | 1         | 0.16%   |
| e2e4                | 1         | 0.16%   |
| Digiboard           | 1         | 0.16%   |
| Avant               | 1         | 0.16%   |
| 48spaces            | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 12        | 1.72%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 8         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 1.14%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 7         | 1%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 1%      |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 6         | 0.86%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 6         | 0.86%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 5         | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 4         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 4         | 0.57%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 4         | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.57%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 4         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.43%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 3         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 3         | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 3         | 0.43%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 3         | 0.43%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.43%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 3         | 0.43%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 3         | 0.43%   |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                | 3         | 0.43%   |
| Unknown                                                          | 3         | 0.43%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 2         | 0.29%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                   | 2         | 0.29%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 2         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                        | 2         | 0.29%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.29%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 2         | 0.29%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.29%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 0.29%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 2         | 0.29%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 2         | 0.29%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.29%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 2         | 0.29%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 0.29%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 2         | 0.29%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                       | 2         | 0.29%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 2         | 0.29%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 2         | 0.29%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 2         | 0.29%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 2         | 0.29%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.29%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.29%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 250       | 44.72%  |
| DDR4    | 119       | 21.29%  |
| DDR2    | 83        | 14.85%  |
| SDRAM   | 30        | 5.37%   |
| Unknown | 24        | 4.29%   |
| LPDDR4  | 17        | 3.04%   |
| DDR     | 16        | 2.86%   |
| LPDDR3  | 12        | 2.15%   |
| DRAM    | 8         | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 352       | 64.12%  |
| DIMM         | 171       | 31.15%  |
| Row Of Chips | 22        | 4.01%   |
| Unknown      | 3         | 0.55%   |
| Chip         | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 203       | 32.22%  |
| 2048  | 174       | 27.62%  |
| 8192  | 123       | 19.52%  |
| 1024  | 73        | 11.59%  |
| 16384 | 31        | 4.92%   |
| 512   | 15        | 2.38%   |
| 256   | 5         | 0.79%   |
| 32768 | 3         | 0.48%   |
| 128   | 2         | 0.32%   |
| 65536 | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 142       | 23.55%  |
| 1333    | 53        | 8.79%   |
| Unknown | 42        | 6.97%   |
| 667     | 39        | 6.47%   |
| 1334    | 38        | 6.3%    |
| 2667    | 37        | 6.14%   |
| 2400    | 36        | 5.97%   |
| 3200    | 32        | 5.31%   |
| 800     | 26        | 4.31%   |
| 2133    | 22        | 3.65%   |
| 1066    | 18        | 2.99%   |
| 533     | 17        | 2.82%   |
| 1067    | 14        | 2.32%   |
| 1867    | 11        | 1.82%   |
| 2048    | 10        | 1.66%   |
| 1866    | 9         | 1.49%   |
| 400     | 9         | 1.49%   |
| 3266    | 6         | 1%      |
| 4267    | 5         | 0.83%   |
| 3600    | 5         | 0.83%   |
| 333     | 4         | 0.66%   |
| 49926   | 3         | 0.5%    |
| 4199    | 3         | 0.5%    |
| 975     | 3         | 0.5%    |
| 3466    | 2         | 0.33%   |
| 3000    | 2         | 0.33%   |
| 1639    | 2         | 0.33%   |
| 266     | 2         | 0.33%   |
| 41632   | 1         | 0.17%   |
| 8400    | 1         | 0.17%   |
| 3151    | 1         | 0.17%   |
| 3066    | 1         | 0.17%   |
| 2800    | 1         | 0.17%   |
| 2733    | 1         | 0.17%   |
| 2666    | 1         | 0.17%   |
| 1800    | 1         | 0.17%   |
| 1200    | 1         | 0.17%   |
| 2       | 1         | 0.17%   |
| 1       | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 7         | 35%     |
| Samsung Electronics   | 5         | 25%     |
| Brother Industries    | 4         | 20%     |
| Canon                 | 2         | 10%     |
| STMicroelectronics    | 1         | 5%      |
| Lexmark International | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| STMicroelectronics USB Printer P        | 1         | 5%      |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 5%      |
| Samsung SCX-4200 series                 | 1         | 5%      |
| Samsung SCX-3400 Series                 | 1         | 5%      |
| Samsung ML-1640 Series Laser Printer    | 1         | 5%      |
| Samsung M2020 Series                    | 1         | 5%      |
| Lexmark International MS610de           | 1         | 5%      |
| HP PSC 1500 series                      | 1         | 5%      |
| HP OfficeJet 4650 series                | 1         | 5%      |
| HP LaserJet 1200                        | 1         | 5%      |
| HP DeskJet D2460                        | 1         | 5%      |
| HP DeskJet 3630 series                  | 1         | 5%      |
| HP Deskjet 3520 series                  | 1         | 5%      |
| HP Deskjet 1050 J410                    | 1         | 5%      |
| Canon TS5100 series                     | 1         | 5%      |
| Canon MF3110                            | 1         | 5%      |
| Brother PTUSB Printing                  | 1         | 5%      |
| Brother PT-2450DX                       | 1         | 5%      |
| Brother Printer                         | 1         | 5%      |
| Brother DCP-7055W                       | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 2         | 33.33%  |
| Seiko Epson     | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 16.67%  |
| HP scanjet 8270                                               | 1         | 16.67%  |
| HP ScanJet 2400c                                              | 1         | 16.67%  |
| HP HP4470C                                                    | 1         | 16.67%  |
| Canon CanoScan LiDE 500F                                      | 1         | 16.67%  |
| Canon CanoScan LiDE 220                                       | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 127       | 25.3%   |
| IMC Networks                           | 38        | 7.57%   |
| Realtek Semiconductor                  | 37        | 7.37%   |
| Microdia                               | 34        | 6.77%   |
| Suyin                                  | 28        | 5.58%   |
| Acer                                   | 27        | 5.38%   |
| Apple                                  | 21        | 4.18%   |
| Sunplus Innovation Technology          | 19        | 3.78%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 3.78%   |
| Silicon Motion                         | 18        | 3.59%   |
| Quanta                                 | 17        | 3.39%   |
| Alcor Micro                            | 17        | 3.39%   |
| Syntek                                 | 9         | 1.79%   |
| Ricoh                                  | 9         | 1.79%   |
| Logitech                               | 9         | 1.79%   |
| Lite-On Technology                     | 9         | 1.79%   |
| Lenovo                                 | 6         | 1.2%    |
| GEMBIRD                                | 5         | 1%      |
| Z-Star Microelectronics                | 4         | 0.8%    |
| Samsung Electronics                    | 4         | 0.8%    |
| Importek                               | 4         | 0.8%    |
| Microsoft                              | 3         | 0.6%    |
| Luxvisions Innotech Limited            | 3         | 0.6%    |
| Genesys Logic                          | 3         | 0.6%    |
| Generalplus Technology                 | 3         | 0.6%    |
| Unknown                                | 2         | 0.4%    |
| SJ-180517-N                            | 2         | 0.4%    |
| LG Electronics                         | 2         | 0.4%    |
| KYE Systems (Mouse Systems)            | 2         | 0.4%    |
| icSpring                               | 2         | 0.4%    |
| ARC International                      | 2         | 0.4%    |
| ALi                                    | 2         | 0.4%    |
| Y Media                                | 1         | 0.2%    |
| Toshiba                                | 1         | 0.2%    |
| SunplusIT                              | 1         | 0.2%    |
| Sunplus Technology                     | 1         | 0.2%    |
| Pixart Imaging                         | 1         | 0.2%    |
| OmniVision Technologies                | 1         | 0.2%    |
| Novatek Microelectronics               | 1         | 0.2%    |
| Nintendo                               | 1         | 0.2%    |
| Huawei Technologies                    | 1         | 0.2%    |
| Guillemot                              | 1         | 0.2%    |
| GEO Semi                               | 1         | 0.2%    |
| DJJHNA29IE70D3                         | 1         | 0.2%    |
| DigiTech                               | 1         | 0.2%    |
| Creative Technology                    | 1         | 0.2%    |
| AVerMedia Technologies                 | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                         | 12        | 2.38%   |
| Chicony Integrated Camera                            | 10        | 1.98%   |
| Alcor Micro USB 2.0 PC cam                           | 9         | 1.78%   |
| Chicony HP Truevision HD                             | 8         | 1.58%   |
| Chicony EasyCamera                                   | 8         | 1.58%   |
| Chicony HD WebCam                                    | 7         | 1.39%   |
| Apple iPhone 5/5C/5S/6/SE                            | 7         | 1.39%   |
| IMC Networks UVC VGA Webcam                          | 6         | 1.19%   |
| Chicony USB 2.0 Camera                               | 6         | 1.19%   |
| Chicony TOSHIBA Web Camera - HD                      | 6         | 1.19%   |
| Chicony HP HD Webcam                                 | 6         | 1.19%   |
| Apple FaceTime HD Camera                             | 6         | 1.19%   |
| Silicon Motion WebCam SC-0311139N                    | 5         | 0.99%   |
| IMC Networks USB 2.0 UVC VGA WebCam                  | 5         | 0.99%   |
| Chicony HP Webcam                                    | 5         | 0.99%   |
| Chicony 2.0M UVC Webcam / CNF7129                    | 5         | 0.99%   |
| Acer Lenovo EasyCamera                               | 5         | 0.99%   |
| Suyin Acer CrystalEye Webcam                         | 4         | 0.79%   |
| Sunplus HD WebCam                                    | 4         | 0.79%   |
| Samsung Galaxy A5 (MTP)                              | 4         | 0.79%   |
| Quanta HP Webcam                                     | 4         | 0.79%   |
| Microdia 1.3 MPixel Integrated Webcam                | 4         | 0.79%   |
| Lenovo Integrated Webcam [R5U877]                    | 4         | 0.79%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 4         | 0.79%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 0.79%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]    | 4         | 0.79%   |
| Chicony HP HD Camera                                 | 4         | 0.79%   |
| Apple Built-in iSight                                | 4         | 0.79%   |
| Alcor Micro Asus Integrated Webcam                   | 4         | 0.79%   |
| Acer HD WebCam                                       | 4         | 0.79%   |
| Suyin WebCam                                         | 3         | 0.59%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 3         | 0.59%   |
| Sunplus HP HD Webcam [Fixed]                         | 3         | 0.59%   |
| Sunplus ASUS USB2.0 Webcam                           | 3         | 0.59%   |
| Realtek Integrated Webcam HD                         | 3         | 0.59%   |
| Realtek Integrated Webcam                            | 3         | 0.59%   |
| Realtek HP Webcam-101                                | 3         | 0.59%   |
| Quanta HP HD Camera                                  | 3         | 0.59%   |
| Microsoft LifeCam HD-3000                            | 3         | 0.59%   |
| Microdia Sonix USB 2.0 Camera                        | 3         | 0.59%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 3         | 0.59%   |
| Microdia Integrated_Webcam_HD                        | 3         | 0.59%   |
| Lite-On TOSHIBA Web Camera - HD                      | 3         | 0.59%   |
| Lite-On HP HD Camera                                 | 3         | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 0.59%   |
| IMC Networks USB 2.0 Camera                          | 3         | 0.59%   |
| IMC Networks Lenovo EasyCamera                       | 3         | 0.59%   |
| IMC Networks EasyCamera                              | 3         | 0.59%   |
| Chicony Lenovo EasyCamera                            | 3         | 0.59%   |
| Chicony Integrated HP HD Webcam                      | 3         | 0.59%   |
| Chicony HD WebCam (Acer)                             | 3         | 0.59%   |
| Chicony Camera                                       | 3         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 3         | 0.59%   |
| Acer VGA WebCam                                      | 3         | 0.59%   |
| Acer Integrated Camera                               | 3         | 0.59%   |
| Acer BisonCam, NB Pro                                | 3         | 0.59%   |
| Z-Star Webcam                                        | 2         | 0.4%    |
| Unknown 720p HD Camera                               | 2         | 0.4%    |
| Syntek Integrated Camera                             | 2         | 0.4%    |
| Syntek EasyCamera                                    | 2         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 28        | 44.44%  |
| AuthenTec                  | 11        | 17.46%  |
| Upek                       | 7         | 11.11%  |
| STMicroelectronics         | 6         | 9.52%   |
| Synaptics                  | 4         | 6.35%   |
| Shenzhen Goodix Technology | 4         | 6.35%   |
| Samsung Electronics        | 1         | 1.59%   |
| LighTuning Technology      | 1         | 1.59%   |
| Elan Microelectronics      | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 9.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 6         | 9.52%   |
| STMicroelectronics Fingerprint Reader                      | 6         | 9.52%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 4         | 6.35%   |
| Validity Sensors VFS491                                    | 3         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 3         | 4.76%   |
| AuthenTec AES2810                                          | 3         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 3         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 3.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.17%   |
| Validity Sensors Fingerprint scanner                       | 2         | 3.17%   |
| Shenzhen Goodix FingerPrint                                | 2         | 3.17%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 2         | 3.17%   |
| AuthenTec AES1600                                          | 2         | 3.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 1.59%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.59%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.59%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 1.59%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.59%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.59%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 1.59%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 1.59%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 1.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 1.59%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 1.59%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.59%   |
| Samsung Fingerprint Sensor Device - 730B                   | 1         | 1.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 1.59%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.59%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| O2 Micro              | 7         | 30.43%  |
| Alcor Micro           | 7         | 30.43%  |
| Broadcom              | 6         | 26.09%  |
| Upek                  | 1         | 4.35%   |
| Realtek Semiconductor | 1         | 4.35%   |
| OmniKey               | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 30.43%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 21.74%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 13.04%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 8.7%    |
| Broadcom 5880                                                                | 2         | 8.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.35%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 4.35%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 718       | 77.04%  |
| 1     | 175       | 18.78%  |
| 2     | 34        | 3.65%   |
| 3     | 4         | 0.43%   |
| 4     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 63        | 24.9%   |
| Graphics card            | 52        | 20.55%  |
| Net/wireless             | 37        | 14.62%  |
| Chipcard                 | 21        | 8.3%    |
| Bluetooth                | 14        | 5.53%   |
| Communication controller | 11        | 4.35%   |
| Multimedia controller    | 9         | 3.56%   |
| Modem                    | 9         | 3.56%   |
| Camera                   | 7         | 2.77%   |
| Storage                  | 6         | 2.37%   |
| Sound                    | 6         | 2.37%   |
| Net/ethernet             | 6         | 2.37%   |
| Unassigned class         | 4         | 1.58%   |
| Flash memory             | 4         | 1.58%   |
| Card reader              | 2         | 0.79%   |
| Network                  | 1         | 0.4%    |
| Dvb card                 | 1         | 0.4%    |

