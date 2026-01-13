Linux in Latvia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Latvia.

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

Total: 460

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 5750G                | [9c51173486](https://linux-hardware.org/?probe=9c51173486) | Jan 02, 2026 |
| Acer          | Aspire 5750G                | [118f3a1d96](https://linux-hardware.org/?probe=118f3a1d96) | Jan 02, 2026 |
| Acer          | Aspire 5750G                | [7e26321ea2](https://linux-hardware.org/?probe=7e26321ea2) | Dec 28, 2025 |
| HP            | 15                          | [3e11bcc056](https://linux-hardware.org/?probe=3e11bcc056) | Dec 23, 2025 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [0796e298e6](https://linux-hardware.org/?probe=0796e298e6) | Dec 19, 2025 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [305cba68c0](https://linux-hardware.org/?probe=305cba68c0) | Dec 12, 2025 |
| Gigabyte      | B450M DS3H-CF               | [51c2f99db8](https://linux-hardware.org/?probe=51c2f99db8) | Dec 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b750fafd03](https://linux-hardware.org/?probe=b750fafd03) | Nov 28, 2025 |
| Samsung       | RV410/RV510/S3510/E3510     | [367cf5b828](https://linux-hardware.org/?probe=367cf5b828) | Nov 23, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c94445cd5c](https://linux-hardware.org/?probe=c94445cd5c) | Nov 19, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7e8b87ad3e](https://linux-hardware.org/?probe=7e8b87ad3e) | Nov 13, 2025 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [885235042c](https://linux-hardware.org/?probe=885235042c) | Oct 31, 2025 |
| Lenovo        | B50-30 80ES                 | [c4440ffc20](https://linux-hardware.org/?probe=c4440ffc20) | Oct 22, 2025 |
| eMachines     | eME732ZG                    | [9bf289be10](https://linux-hardware.org/?probe=9bf289be10) | Oct 21, 2025 |
| Wortmann      | CR700                       | [a5334d477f](https://linux-hardware.org/?probe=a5334d477f) | Oct 09, 2025 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [9899d172db](https://linux-hardware.org/?probe=9899d172db) | Oct 05, 2025 |
| ASUSTek       | Q302LAB                     | [38491c798c](https://linux-hardware.org/?probe=38491c798c) | Sep 15, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e300266057](https://linux-hardware.org/?probe=e300266057) | Sep 15, 2025 |
| HP            | Laptop 15s-eq1xxx           | [c73f420fda](https://linux-hardware.org/?probe=c73f420fda) | Aug 31, 2025 |
| Apple         | MacBookPro8,1               | [0316bf2081](https://linux-hardware.org/?probe=0316bf2081) | Aug 30, 2025 |
| Toshiba       | Satellite C660              | [018c620eaf](https://linux-hardware.org/?probe=018c620eaf) | Aug 04, 2025 |
| ASUSTek       | K55A                        | [2d0252f673](https://linux-hardware.org/?probe=2d0252f673) | Aug 01, 2025 |
| Wortmann      | CR700                       | [bfcf41b931](https://linux-hardware.org/?probe=bfcf41b931) | Jul 20, 2025 |
| Lenovo        | ThinkPad X280 20KES9Y100    | [38c8a6b24b](https://linux-hardware.org/?probe=38c8a6b24b) | Jul 01, 2025 |
| Dell          | Pro 13 Premium PA13250      | [b50588b911](https://linux-hardware.org/?probe=b50588b911) | Jul 01, 2025 |
| Dell          | Pro 13 Premium PA13250      | [d5a629d5fe](https://linux-hardware.org/?probe=d5a629d5fe) | Jun 12, 2025 |
| Lenovo        | ThinkPad E14 Gen 6 21M30... | [d589daa890](https://linux-hardware.org/?probe=d589daa890) | Jun 03, 2025 |
| Wortmann      | CR700                       | [0bf87a4a34](https://linux-hardware.org/?probe=0bf87a4a34) | May 15, 2025 |
| Apple         | MacBookPro10,2              | [a5c84e68ed](https://linux-hardware.org/?probe=a5c84e68ed) | May 03, 2025 |
| HP            | Pavilion g6                 | [69d4a56750](https://linux-hardware.org/?probe=69d4a56750) | May 02, 2025 |
| HP            | Laptop 15s-eq2xxx           | [acf76d2820](https://linux-hardware.org/?probe=acf76d2820) | Apr 28, 2025 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [83d3076e92](https://linux-hardware.org/?probe=83d3076e92) | Apr 26, 2025 |
| Dell          | Latitude 7450               | [b776729c52](https://linux-hardware.org/?probe=b776729c52) | Apr 14, 2025 |
| Dell          | Precision 5520              | [02d34a0c00](https://linux-hardware.org/?probe=02d34a0c00) | Apr 11, 2025 |
| Dell          | Precision 5520              | [473a105ac5](https://linux-hardware.org/?probe=473a105ac5) | Apr 11, 2025 |
| Lenovo        | ThinkPad T480 20L6S23900    | [59d403bbc9](https://linux-hardware.org/?probe=59d403bbc9) | Mar 27, 2025 |
| Apple         | MacBookPro12,1              | [50da8df3b4](https://linux-hardware.org/?probe=50da8df3b4) | Mar 17, 2025 |
| Apple         | MacBookPro12,1              | [e8f8d2379d](https://linux-hardware.org/?probe=e8f8d2379d) | Mar 17, 2025 |
| Apple         | MacBookPro12,1              | [7365fabcc5](https://linux-hardware.org/?probe=7365fabcc5) | Mar 14, 2025 |
| Apple         | MacBookPro12,1              | [9024dae4cc](https://linux-hardware.org/?probe=9024dae4cc) | Mar 14, 2025 |
| Lenovo        | ThinkPad L450 20DT0003MH    | [c5b3a3935b](https://linux-hardware.org/?probe=c5b3a3935b) | Mar 13, 2025 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [49bbb4dce0](https://linux-hardware.org/?probe=49bbb4dce0) | Mar 11, 2025 |
| Wortmann      | CR700                       | [e616fb7387](https://linux-hardware.org/?probe=e616fb7387) | Mar 08, 2025 |
| Lenovo        | ThinkPad T480 20L6S23900    | [f177b856bc](https://linux-hardware.org/?probe=f177b856bc) | Feb 25, 2025 |
| Dell          | Vostro 3525                 | [40f9e4d2fa](https://linux-hardware.org/?probe=40f9e4d2fa) | Feb 14, 2025 |
| HP            | EliteBook 840 G2            | [a425dfd97b](https://linux-hardware.org/?probe=a425dfd97b) | Feb 05, 2025 |
| Dell          | Latitude 7450               | [77f7d60121](https://linux-hardware.org/?probe=77f7d60121) | Feb 05, 2025 |
| Dell          | Latitude 7450               | [803349d056](https://linux-hardware.org/?probe=803349d056) | Jan 15, 2025 |
| Apple         | MacBookPro9,1               | [061cbd2eda](https://linux-hardware.org/?probe=061cbd2eda) | Jan 12, 2025 |
| Dell          | Latitude E6320              | [3baff0aea1](https://linux-hardware.org/?probe=3baff0aea1) | Jan 11, 2025 |
| Dell          | Latitude E6320              | [01561cb356](https://linux-hardware.org/?probe=01561cb356) | Jan 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [2be9a5ca1c](https://linux-hardware.org/?probe=2be9a5ca1c) | Jan 05, 2025 |
| HP            | Compaq Presario CQ56        | [3365fbb5bc](https://linux-hardware.org/?probe=3365fbb5bc) | Jan 04, 2025 |
| Acer          | Aspire 5755G                | [d824794995](https://linux-hardware.org/?probe=d824794995) | Dec 23, 2024 |
| Dell          | Vostro 3525                 | [ca69855de4](https://linux-hardware.org/?probe=ca69855de4) | Dec 06, 2024 |
| Sony          | VPCEE4E1E                   | [a859b089fd](https://linux-hardware.org/?probe=a859b089fd) | Dec 02, 2024 |
| Dell          | Vostro 3525                 | [e4ebed04a3](https://linux-hardware.org/?probe=e4ebed04a3) | Nov 30, 2024 |
| ASUSTek       | K53SV                       | [8e09c4ddbe](https://linux-hardware.org/?probe=8e09c4ddbe) | Nov 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [45fd5080cc](https://linux-hardware.org/?probe=45fd5080cc) | Nov 26, 2024 |
| mPTech        | ARC 11.6 128GB HD           | [107d02aac0](https://linux-hardware.org/?probe=107d02aac0) | Nov 12, 2024 |
| Wortmann      | CR700                       | [0e6bd50e12](https://linux-hardware.org/?probe=0e6bd50e12) | Oct 27, 2024 |
| Dell          | Vostro 3550                 | [855f0534c1](https://linux-hardware.org/?probe=855f0534c1) | Oct 22, 2024 |
| Valve         | Galileo                     | [df3b9380db](https://linux-hardware.org/?probe=df3b9380db) | Oct 11, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [1e9a7618df](https://linux-hardware.org/?probe=1e9a7618df) | Oct 01, 2024 |
| Dell          | Inspiron N5110              | [39053cddd2](https://linux-hardware.org/?probe=39053cddd2) | Sep 29, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [037b72296e](https://linux-hardware.org/?probe=037b72296e) | Sep 29, 2024 |
| Wortmann      | CR700                       | [3fade1540e](https://linux-hardware.org/?probe=3fade1540e) | Sep 20, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [a6b9e47c58](https://linux-hardware.org/?probe=a6b9e47c58) | Sep 13, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [032a7cae6f](https://linux-hardware.org/?probe=032a7cae6f) | Sep 09, 2024 |
| Dell          | System XPS L502X            | [7d1efcbe6a](https://linux-hardware.org/?probe=7d1efcbe6a) | Sep 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [472ba394b6](https://linux-hardware.org/?probe=472ba394b6) | Sep 02, 2024 |
| Dell          | Inspiron 3521               | [a5f30f105b](https://linux-hardware.org/?probe=a5f30f105b) | Aug 20, 2024 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [7f7717743d](https://linux-hardware.org/?probe=7f7717743d) | Aug 08, 2024 |
| MSI           | Stealth 16 AI Studio A1V... | [3a5fc2d641](https://linux-hardware.org/?probe=3a5fc2d641) | Aug 07, 2024 |
| HP            | Laptop 14-bs0xx             | [f994ec5854](https://linux-hardware.org/?probe=f994ec5854) | Aug 01, 2024 |
| Valve         | Galileo                     | [c62dd4aca9](https://linux-hardware.org/?probe=c62dd4aca9) | Jul 29, 2024 |
| Valve         | Galileo                     | [f4a8db2e5f](https://linux-hardware.org/?probe=f4a8db2e5f) | Jul 29, 2024 |
| Lenovo        | Unknown                     | [556b32d378](https://linux-hardware.org/?probe=556b32d378) | Jul 15, 2024 |
| Acer          | Nitro AN515-57              | [f381bc43a0](https://linux-hardware.org/?probe=f381bc43a0) | Jul 05, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [e70a20fd46](https://linux-hardware.org/?probe=e70a20fd46) | Jul 01, 2024 |
| Wortmann      | CR700                       | [638b1918fb](https://linux-hardware.org/?probe=638b1918fb) | Jul 01, 2024 |
| mPTech        | ARC 11.6 128GB HD           | [b01bbdb3a1](https://linux-hardware.org/?probe=b01bbdb3a1) | Jun 22, 2024 |
| mPTech        | ARC 11.6 128GB HD           | [1db6414aba](https://linux-hardware.org/?probe=1db6414aba) | Jun 16, 2024 |
| Lenovo        | ThinkPad T500 20827MG       | [812523cb5e](https://linux-hardware.org/?probe=812523cb5e) | May 29, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [1e579e7bc9](https://linux-hardware.org/?probe=1e579e7bc9) | May 22, 2024 |
| Wortmann      | CR700                       | [695f76d8f3](https://linux-hardware.org/?probe=695f76d8f3) | May 12, 2024 |
| HP            | Victus by Gaming Laptop ... | [24cf77eb91](https://linux-hardware.org/?probe=24cf77eb91) | May 07, 2024 |
| Lenovo        | ThinkPad X201 3626HMG       | [c445ea85c4](https://linux-hardware.org/?probe=c445ea85c4) | May 02, 2024 |
| HP            | Victus by Gaming Laptop ... | [9318ac5f47](https://linux-hardware.org/?probe=9318ac5f47) | Apr 30, 2024 |
| ASUSTek       | X541SA                      | [23ea4a0287](https://linux-hardware.org/?probe=23ea4a0287) | Apr 09, 2024 |
| ASUSTek       | X541SA                      | [0f5bd53c6f](https://linux-hardware.org/?probe=0f5bd53c6f) | Apr 08, 2024 |
| ASUSTek       | X541SA                      | [b3f083db5c](https://linux-hardware.org/?probe=b3f083db5c) | Apr 06, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [0855016a44](https://linux-hardware.org/?probe=0855016a44) | Apr 01, 2024 |
| Wortmann      | CR700                       | [e8bf0a5a61](https://linux-hardware.org/?probe=e8bf0a5a61) | Mar 27, 2024 |
| ASUSTek       | X55A                        | [9631a046b9](https://linux-hardware.org/?probe=9631a046b9) | Mar 19, 2024 |
| ASUSTek       | X55A                        | [c37422f48f](https://linux-hardware.org/?probe=c37422f48f) | Mar 13, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [e655e5c1da](https://linux-hardware.org/?probe=e655e5c1da) | Mar 11, 2024 |
| Dell          | Latitude E6500              | [0c10bab3da](https://linux-hardware.org/?probe=0c10bab3da) | Mar 10, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [0c55a3dc95](https://linux-hardware.org/?probe=0c55a3dc95) | Mar 10, 2024 |
| Acer          | Aspire 5730                 | [cba983dfb3](https://linux-hardware.org/?probe=cba983dfb3) | Mar 08, 2024 |
| Dell          | Vostro 15 3510              | [856ce9544e](https://linux-hardware.org/?probe=856ce9544e) | Mar 07, 2024 |
| Wortmann      | CR700                       | [faed1b3618](https://linux-hardware.org/?probe=faed1b3618) | Mar 06, 2024 |
| HP            | 250 G6 Notebook PC          | [88ca3f1029](https://linux-hardware.org/?probe=88ca3f1029) | Feb 20, 2024 |
| Apple         | MacBookPro11,1              | [bc1e6e90c1](https://linux-hardware.org/?probe=bc1e6e90c1) | Feb 10, 2024 |
| Apple         | MacBookPro11,1              | [0c1b63b275](https://linux-hardware.org/?probe=0c1b63b275) | Feb 10, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [12e32cbc19](https://linux-hardware.org/?probe=12e32cbc19) | Jan 19, 2024 |
| Dell          | Inspiron 3501               | [75a54dcccf](https://linux-hardware.org/?probe=75a54dcccf) | Jan 13, 2024 |
| Dell          | Precision M4800             | [47508330f1](https://linux-hardware.org/?probe=47508330f1) | Dec 26, 2023 |
| HP            | 250 G6 Notebook PC          | [552bc11608](https://linux-hardware.org/?probe=552bc11608) | Dec 19, 2023 |
| MSI           | Katana GF76 12UC            | [6667f9e88d](https://linux-hardware.org/?probe=6667f9e88d) | Dec 08, 2023 |
| HP            | ProBook 450 G0              | [80f6017066](https://linux-hardware.org/?probe=80f6017066) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ce86d3d6](https://linux-hardware.org/?probe=76ce86d3d6) | Nov 26, 2023 |
| TUXEDO        | Gemini Gen2                 | [43d1c51e23](https://linux-hardware.org/?probe=43d1c51e23) | Nov 17, 2023 |
| Wortmann      | CR700                       | [0c5f9ff4c6](https://linux-hardware.org/?probe=0c5f9ff4c6) | Nov 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [dc40a2bbb1](https://linux-hardware.org/?probe=dc40a2bbb1) | Nov 10, 2023 |
| Wortmann      | CR700                       | [45ed4d1320](https://linux-hardware.org/?probe=45ed4d1320) | Nov 07, 2023 |
| TUXEDO        | Unknown                     | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Wortmann      | CR700                       | [916c9bceda](https://linux-hardware.org/?probe=916c9bceda) | Oct 15, 2023 |
| Packard Be... | EasyNote TE11HC             | [75cbcab213](https://linux-hardware.org/?probe=75cbcab213) | Oct 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| MSI           | Katana GF76 11UE            | [8327fd670f](https://linux-hardware.org/?probe=8327fd670f) | Sep 23, 2023 |
| HP            | ProBook 450 G1              | [feffc725af](https://linux-hardware.org/?probe=feffc725af) | Sep 23, 2023 |
| Packard Be... | EasyNote TE11HC             | [0d897e53cf](https://linux-hardware.org/?probe=0d897e53cf) | Sep 21, 2023 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | [432c1d0b94](https://linux-hardware.org/?probe=432c1d0b94) | Sep 18, 2023 |
| Packard Be... | EasyNote TE11HC             | [7f55f1b615](https://linux-hardware.org/?probe=7f55f1b615) | Sep 08, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [89ce951011](https://linux-hardware.org/?probe=89ce951011) | Sep 05, 2023 |
| Acer          | Aspire A515-56              | [435cb2d610](https://linux-hardware.org/?probe=435cb2d610) | Sep 03, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [ba81140205](https://linux-hardware.org/?probe=ba81140205) | Aug 31, 2023 |
| Acer          | Aspire A515-56              | [501ee4caf7](https://linux-hardware.org/?probe=501ee4caf7) | Aug 20, 2023 |
| ASUSTek       | N56VJ                       | [d552e1a450](https://linux-hardware.org/?probe=d552e1a450) | Aug 08, 2023 |
| Wortmann      | CR700                       | [2f3379e14e](https://linux-hardware.org/?probe=2f3379e14e) | Jul 31, 2023 |
| HP            | ProBook 4530s               | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [631e54097b](https://linux-hardware.org/?probe=631e54097b) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [192f8de028](https://linux-hardware.org/?probe=192f8de028) | Jul 18, 2023 |
| HP            | Pavilion dv6500             | [a714d595da](https://linux-hardware.org/?probe=a714d595da) | Jul 10, 2023 |
| Packard Be... | EasyNote TE11HC             | [9b40832f50](https://linux-hardware.org/?probe=9b40832f50) | Jul 09, 2023 |
| Unknown       | Unknown                     | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| Sony          | VPCCW2S8E                   | [4a3af37e51](https://linux-hardware.org/?probe=4a3af37e51) | Jul 05, 2023 |
| Wortmann      | CR700                       | [b198dccb29](https://linux-hardware.org/?probe=b198dccb29) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Gigabyte      | P55V6                       | [63d0cd064b](https://linux-hardware.org/?probe=63d0cd064b) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| Wortmann      | CR700                       | [189f1ae92b](https://linux-hardware.org/?probe=189f1ae92b) | May 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Dell          | Latitude 5330               | [3cc5328fee](https://linux-hardware.org/?probe=3cc5328fee) | May 16, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [65b165e2f1](https://linux-hardware.org/?probe=65b165e2f1) | May 12, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [66b49186cb](https://linux-hardware.org/?probe=66b49186cb) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| HUAWEI        | BOD-WXX9                    | [1909a7f824](https://linux-hardware.org/?probe=1909a7f824) | May 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [6e0d5c7f28](https://linux-hardware.org/?probe=6e0d5c7f28) | May 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [136fd4098d](https://linux-hardware.org/?probe=136fd4098d) | May 01, 2023 |
| HP            | 250 G6 Notebook PC          | [90e4883dca](https://linux-hardware.org/?probe=90e4883dca) | Apr 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [641374c815](https://linux-hardware.org/?probe=641374c815) | Apr 23, 2023 |
| Dell          | Latitude 5400               | [70899bc374](https://linux-hardware.org/?probe=70899bc374) | Apr 12, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [6a6e2f88f4](https://linux-hardware.org/?probe=6a6e2f88f4) | Apr 12, 2023 |
| Acer          | Aspire 5250                 | [f2040ffb31](https://linux-hardware.org/?probe=f2040ffb31) | Apr 09, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [52b4a5a0f0](https://linux-hardware.org/?probe=52b4a5a0f0) | Apr 08, 2023 |
| ASUSTek       | X553MA                      | [0a307c8c2b](https://linux-hardware.org/?probe=0a307c8c2b) | Apr 07, 2023 |
| Apple         | MacBookAir5,2               | [5a1cd8556c](https://linux-hardware.org/?probe=5a1cd8556c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| Acer          | Extensa 5630                | [e78d4a3c28](https://linux-hardware.org/?probe=e78d4a3c28) | Mar 14, 2023 |
| Wortmann      | CR700                       | [a48e22ffc5](https://linux-hardware.org/?probe=a48e22ffc5) | Mar 07, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| HP            | Pavilion 17                 | [1a50084a52](https://linux-hardware.org/?probe=1a50084a52) | Feb 19, 2023 |
| Fujitsu       | STYLISTIC Q704              | [9d36ad089c](https://linux-hardware.org/?probe=9d36ad089c) | Feb 18, 2023 |
| Dell          | Latitude 5330               | [497897c322](https://linux-hardware.org/?probe=497897c322) | Feb 16, 2023 |
| Lenovo        | ZIWB2                       | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| Dell          | Latitude 5330               | [aa55aaad48](https://linux-hardware.org/?probe=aa55aaad48) | Feb 16, 2023 |
| Chuwi         | Hi10 Go                     | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| Lenovo        | ZIWB2                       | [b7ff6b4dd5](https://linux-hardware.org/?probe=b7ff6b4dd5) | Feb 02, 2023 |
| Acer          | Aspire 5532                 | [88e8887c6c](https://linux-hardware.org/?probe=88e8887c6c) | Jan 27, 2023 |
| ASUSTek       | X550CL                      | [e98a955b1a](https://linux-hardware.org/?probe=e98a955b1a) | Jan 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Acer          | Extensa 5630                | [ae62db30e8](https://linux-hardware.org/?probe=ae62db30e8) | Jan 23, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [40719006ae](https://linux-hardware.org/?probe=40719006ae) | Jan 23, 2023 |
| Wortmann      | CR700                       | [0d40cf0690](https://linux-hardware.org/?probe=0d40cf0690) | Jan 22, 2023 |
| MSI           | CR500                       | [4aaddddd7f](https://linux-hardware.org/?probe=4aaddddd7f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9cb7b18b35](https://linux-hardware.org/?probe=9cb7b18b35) | Jan 20, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [95e7b7d833](https://linux-hardware.org/?probe=95e7b7d833) | Jan 20, 2023 |
| Lenovo        | G70-80 80FF                 | [1ce03f27f3](https://linux-hardware.org/?probe=1ce03f27f3) | Jan 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [8026c0d5b2](https://linux-hardware.org/?probe=8026c0d5b2) | Jan 17, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [68bd2484a1](https://linux-hardware.org/?probe=68bd2484a1) | Jan 04, 2023 |
| HP            | G62                         | [4d80c95e73](https://linux-hardware.org/?probe=4d80c95e73) | Dec 18, 2022 |
| Dell          | Inspiron N5050              | [cc139ec3a3](https://linux-hardware.org/?probe=cc139ec3a3) | Dec 17, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | [5fca69ae89](https://linux-hardware.org/?probe=5fca69ae89) | Dec 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [259226594a](https://linux-hardware.org/?probe=259226594a) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [b3c750c720](https://linux-hardware.org/?probe=b3c750c720) | Dec 11, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | [e4fe543570](https://linux-hardware.org/?probe=e4fe543570) | Dec 10, 2022 |
| ASUSTek       | X550MD                      | [e5058b43c3](https://linux-hardware.org/?probe=e5058b43c3) | Dec 05, 2022 |
| ASUSTek       | F3Sg                        | [f5ae748125](https://linux-hardware.org/?probe=f5ae748125) | Dec 04, 2022 |
| MSI           | GV72 7RE                    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| ASUSTek       | G751JL                      | [1bfbfafe68](https://linux-hardware.org/?probe=1bfbfafe68) | Nov 29, 2022 |
| ASUSTek       | X453MA                      | [f30a5c4808](https://linux-hardware.org/?probe=f30a5c4808) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [585b6910fa](https://linux-hardware.org/?probe=585b6910fa) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [138231da75](https://linux-hardware.org/?probe=138231da75) | Nov 26, 2022 |
| MSI           | Modern 14 B4MW              | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Wortmann      | CR700                       | [7030308edf](https://linux-hardware.org/?probe=7030308edf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X260 20F5S5Q200    | [c2e041fd54](https://linux-hardware.org/?probe=c2e041fd54) | Oct 21, 2022 |
| ASUSTek       | X553MA                      | [ade1f0f879](https://linux-hardware.org/?probe=ade1f0f879) | Oct 14, 2022 |
| Toshiba       | Satellite L350              | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| Acer          | Aspire 5250                 | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| Acer          | Aspire 5742                 | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| HP            | EliteBook 8440p             | [1f0f196305](https://linux-hardware.org/?probe=1f0f196305) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| HP            | ProBook 450 G1              | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [88fc37216d](https://linux-hardware.org/?probe=88fc37216d) | Aug 15, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| Lenovo        | G70-80 80FF                 | [495516e19d](https://linux-hardware.org/?probe=495516e19d) | Aug 08, 2022 |
| Acer          | Aspire A315-42              | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Acer          | Aspire 5730                 | [b4877f21ad](https://linux-hardware.org/?probe=b4877f21ad) | Jul 23, 2022 |
| Wortmann      | CR700                       | [3aa2d086b9](https://linux-hardware.org/?probe=3aa2d086b9) | Jul 23, 2022 |
| Wortmann      | CR700                       | [27d04b5577](https://linux-hardware.org/?probe=27d04b5577) | Jul 23, 2022 |
| Acer          | Aspire A515-51G             | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| Dell          | Precision 3561              | [fab553a2b2](https://linux-hardware.org/?probe=fab553a2b2) | Jun 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| HP            | ProBook 450 G0              | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e75d068a21](https://linux-hardware.org/?probe=e75d068a21) | Jun 02, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6f5d1c9f06](https://linux-hardware.org/?probe=6f5d1c9f06) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6e46286500](https://linux-hardware.org/?probe=6e46286500) | May 21, 2022 |
| Acer          | Aspire A315-42              | [cd2a742b8c](https://linux-hardware.org/?probe=cd2a742b8c) | May 18, 2022 |
| Dell          | Inspiron 3543               | [3a940a3394](https://linux-hardware.org/?probe=3a940a3394) | May 11, 2022 |
| Valve         | Jupiter                     | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Dell          | Inspiron 3543               | [7fb19b7da4](https://linux-hardware.org/?probe=7fb19b7da4) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| Dell          | Latitude E7440              | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [c3ac98aa71](https://linux-hardware.org/?probe=c3ac98aa71) | Apr 11, 2022 |
| Dell          | Latitude 5590               | [6e22c70e48](https://linux-hardware.org/?probe=6e22c70e48) | Apr 05, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [086d7749d3](https://linux-hardware.org/?probe=086d7749d3) | Apr 03, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [1a8680a665](https://linux-hardware.org/?probe=1a8680a665) | Mar 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d63ab08c03](https://linux-hardware.org/?probe=d63ab08c03) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [5af22f3639](https://linux-hardware.org/?probe=5af22f3639) | Mar 07, 2022 |
| HP            | EliteBook 8570w             | [a97a0ba0ee](https://linux-hardware.org/?probe=a97a0ba0ee) | Feb 27, 2022 |
| Dell          | Inspiron 3531               | [d2d231ddeb](https://linux-hardware.org/?probe=d2d231ddeb) | Feb 24, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ae4eca9e09](https://linux-hardware.org/?probe=ae4eca9e09) | Feb 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| Lenovo        | G70-80 80FF                 | [0771453742](https://linux-hardware.org/?probe=0771453742) | Jan 25, 2022 |
| Apple         | MacBookPro8,1               | [9b3d91c6df](https://linux-hardware.org/?probe=9b3d91c6df) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| Razer         | Blade 15 Advanced Model ... | [c07445f559](https://linux-hardware.org/?probe=c07445f559) | Jan 23, 2022 |
| Lenovo        | G70-80 80FF                 | [c69ec5ad5b](https://linux-hardware.org/?probe=c69ec5ad5b) | Jan 17, 2022 |
| Razer         | Blade 15 Advanced Model ... | [6f992c3b94](https://linux-hardware.org/?probe=6f992c3b94) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | [95724a0980](https://linux-hardware.org/?probe=95724a0980) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Lenovo        | G70-80 80FF                 | [b1279c6db3](https://linux-hardware.org/?probe=b1279c6db3) | Jan 02, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [0d09c12302](https://linux-hardware.org/?probe=0d09c12302) | Dec 28, 2021 |
| Lenovo        | G70-80 80FF                 | [4210ac05a8](https://linux-hardware.org/?probe=4210ac05a8) | Dec 26, 2021 |
| Dell          | Inspiron 3543               | [2b61a95031](https://linux-hardware.org/?probe=2b61a95031) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | [7d2faf3b37](https://linux-hardware.org/?probe=7d2faf3b37) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | [6df4a50194](https://linux-hardware.org/?probe=6df4a50194) | Dec 21, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| ASUSTek       | E402SA                      | [2a140138d3](https://linux-hardware.org/?probe=2a140138d3) | Dec 12, 2021 |
| Lenovo        | G70-80 80FF                 | [7d694ce256](https://linux-hardware.org/?probe=7d694ce256) | Dec 09, 2021 |
| Dell          | Latitude 7420               | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [c7726d6967](https://linux-hardware.org/?probe=c7726d6967) | Nov 23, 2021 |
| Acer          | NC-E5-572G-7222             | [1c2a0c3295](https://linux-hardware.org/?probe=1c2a0c3295) | Nov 19, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [0c603f1589](https://linux-hardware.org/?probe=0c603f1589) | Nov 16, 2021 |
| HUAWEI        | MACHD-WXX9                  | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| HP            | EliteBook 850 G4            | [e6643f7ed1](https://linux-hardware.org/?probe=e6643f7ed1) | Oct 28, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| HP            | G62                         | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| ASUSTek       | N550JV                      | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [f4a4e754c5](https://linux-hardware.org/?probe=f4a4e754c5) | Sep 22, 2021 |
| HP            | 250 G6 Notebook PC          | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [eb5215553d](https://linux-hardware.org/?probe=eb5215553d) | Sep 18, 2021 |
| HP            | EliteBook 840 G3            | [5ac93f6014](https://linux-hardware.org/?probe=5ac93f6014) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [c5ebbbd9c2](https://linux-hardware.org/?probe=c5ebbbd9c2) | Aug 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [516c59e9bb](https://linux-hardware.org/?probe=516c59e9bb) | Aug 26, 2021 |
| Sony          | VPCCW2S8E                   | [a8c2dc6942](https://linux-hardware.org/?probe=a8c2dc6942) | Aug 26, 2021 |
| HP            | EliteBook 840 G1            | [82b2192d48](https://linux-hardware.org/?probe=82b2192d48) | Aug 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d26b653261](https://linux-hardware.org/?probe=d26b653261) | Aug 23, 2021 |
| Dell          | G3 3579                     | [6042d3630a](https://linux-hardware.org/?probe=6042d3630a) | Aug 22, 2021 |
| Dell          | G3 3579                     | [902b56f744](https://linux-hardware.org/?probe=902b56f744) | Aug 22, 2021 |
| HP            | Pavilion dv7                | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | EliteBook 8470p             | [c718b061d2](https://linux-hardware.org/?probe=c718b061d2) | Aug 05, 2021 |
| HP            | HDX 16                      | [47273f74b5](https://linux-hardware.org/?probe=47273f74b5) | Aug 02, 2021 |
| HP            | HDX 16                      | [aa6b70deac](https://linux-hardware.org/?probe=aa6b70deac) | Aug 02, 2021 |
| Toshiba       | Satellite L850-1LK          | [8e8d84c8eb](https://linux-hardware.org/?probe=8e8d84c8eb) | Jul 30, 2021 |
| Dell          | Vostro 1015                 | [0e16f2bc9c](https://linux-hardware.org/?probe=0e16f2bc9c) | Jul 30, 2021 |
| Toshiba       | Satellite L850-1LK          | [b0b636bbee](https://linux-hardware.org/?probe=b0b636bbee) | Jul 30, 2021 |
| HP            | HDX 16                      | [627219df22](https://linux-hardware.org/?probe=627219df22) | Jul 25, 2021 |
| Timi          | A35S                        | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [55460937e0](https://linux-hardware.org/?probe=55460937e0) | Jul 14, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| Dell          | Latitude 7420               | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| HP            | HDX 16                      | [ba1ae87cbe](https://linux-hardware.org/?probe=ba1ae87cbe) | Jul 07, 2021 |
| Acer          | Predator PH317-53           | [1e5cb90c22](https://linux-hardware.org/?probe=1e5cb90c22) | Jul 06, 2021 |
| HP            | Pavilion dv6500             | [135215864a](https://linux-hardware.org/?probe=135215864a) | Jun 19, 2021 |
| Dell          | Latitude 5520               | [9929364f77](https://linux-hardware.org/?probe=9929364f77) | Jun 01, 2021 |
| Acer          | AO725                       | [1a095f9c0f](https://linux-hardware.org/?probe=1a095f9c0f) | May 17, 2021 |
| Lenovo        | Y50-70 20378                | [cc68265730](https://linux-hardware.org/?probe=cc68265730) | May 15, 2021 |
| Dell          | Inspiron 3583               | [7e3064fadf](https://linux-hardware.org/?probe=7e3064fadf) | May 10, 2021 |
| Dell          | Inspiron 3583               | [29e5e6b501](https://linux-hardware.org/?probe=29e5e6b501) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [de14cb7c23](https://linux-hardware.org/?probe=de14cb7c23) | May 06, 2021 |
| Dell          | Inspiron 5720               | [28fc1b9fd7](https://linux-hardware.org/?probe=28fc1b9fd7) | Apr 20, 2021 |
| Acer          | Aspire E5-774G              | [17734000ae](https://linux-hardware.org/?probe=17734000ae) | Apr 14, 2021 |
| Lenovo        | G50-80 80E5                 | [d6b6146396](https://linux-hardware.org/?probe=d6b6146396) | Apr 14, 2021 |
| Dell          | Inspiron 5720               | [2bff145cfe](https://linux-hardware.org/?probe=2bff145cfe) | Apr 10, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [3c5c72b0fb](https://linux-hardware.org/?probe=3c5c72b0fb) | Mar 20, 2021 |
| Dell          | Latitude 5400               | [002c23ff4b](https://linux-hardware.org/?probe=002c23ff4b) | Mar 19, 2021 |
| Dell          | Latitude E5400              | [0b3108a091](https://linux-hardware.org/?probe=0b3108a091) | Mar 04, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [35b79852e1](https://linux-hardware.org/?probe=35b79852e1) | Feb 06, 2021 |
| ASUSTek       | F3Sg                        | [98e32533f7](https://linux-hardware.org/?probe=98e32533f7) | Feb 06, 2021 |
| Dell          | Inspiron 5720               | [548a61cbe6](https://linux-hardware.org/?probe=548a61cbe6) | Jan 24, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [61f2500518](https://linux-hardware.org/?probe=61f2500518) | Jan 08, 2021 |
| Dell          | Latitude E6330              | [06a79c3a7f](https://linux-hardware.org/?probe=06a79c3a7f) | Jan 05, 2021 |
| ASUSTek       | N56VM                       | [795cfd3d9a](https://linux-hardware.org/?probe=795cfd3d9a) | Dec 30, 2020 |
| Lenovo        | G70-80 80FF                 | [069f4b154c](https://linux-hardware.org/?probe=069f4b154c) | Dec 27, 2020 |
| Lenovo        | V110-15IAP 80TG             | [5bb5bac2f1](https://linux-hardware.org/?probe=5bb5bac2f1) | Dec 26, 2020 |
| Quanta        | TW8/SW8/DW8                 | [705e766496](https://linux-hardware.org/?probe=705e766496) | Dec 18, 2020 |
| Quanta        | TW8/SW8/DW8                 | [5501a16739](https://linux-hardware.org/?probe=5501a16739) | Dec 18, 2020 |
| Fujitsu       | STYLISTIC Q704              | [ae32e0d51d](https://linux-hardware.org/?probe=ae32e0d51d) | Dec 14, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [46c6cef9b6](https://linux-hardware.org/?probe=46c6cef9b6) | Nov 27, 2020 |
| Lenovo        | G70-80 80FF                 | [7563d834dc](https://linux-hardware.org/?probe=7563d834dc) | Nov 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Lenovo        | G70-80 80FF                 | [814d9b3267](https://linux-hardware.org/?probe=814d9b3267) | Nov 26, 2020 |
| Acer          | Aspire E5-774G              | [792da7f209](https://linux-hardware.org/?probe=792da7f209) | Nov 21, 2020 |
| ASUSTek       | N56VZ                       | [fb3694b0fb](https://linux-hardware.org/?probe=fb3694b0fb) | Nov 21, 2020 |
| Fujitsu       | STYLISTIC Q704              | [a016928cb6](https://linux-hardware.org/?probe=a016928cb6) | Nov 20, 2020 |
| Fujitsu       | STYLISTIC Q704              | [6cee0ffad6](https://linux-hardware.org/?probe=6cee0ffad6) | Nov 20, 2020 |
| Acer          | Nitro AN515-54              | [6b6517fc84](https://linux-hardware.org/?probe=6b6517fc84) | Nov 17, 2020 |
| ASUSTek       | F9S                         | [dbadd20bba](https://linux-hardware.org/?probe=dbadd20bba) | Nov 15, 2020 |
| ASUSTek       | X751LD                      | [1ddab278fa](https://linux-hardware.org/?probe=1ddab278fa) | Nov 13, 2020 |
| ASUSTek       | X751LD                      | [518aedab56](https://linux-hardware.org/?probe=518aedab56) | Nov 13, 2020 |
| ASUSTek       | F9S                         | [17861d40da](https://linux-hardware.org/?probe=17861d40da) | Nov 09, 2020 |
| Acer          | Aspire E1-570               | [cfca189393](https://linux-hardware.org/?probe=cfca189393) | Oct 29, 2020 |
| Packard Be... | EasyNote LE69KB             | [c31d50e8e1](https://linux-hardware.org/?probe=c31d50e8e1) | Oct 24, 2020 |
| Packard Be... | EasyNote LE69KB             | [5d55b9b791](https://linux-hardware.org/?probe=5d55b9b791) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | [21ce46139c](https://linux-hardware.org/?probe=21ce46139c) | Oct 19, 2020 |
| Acer          | Predator PH317-53           | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| HP            | Pavilion dv6700             | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| Toshiba       | Satellite L750              | [8a4c97a585](https://linux-hardware.org/?probe=8a4c97a585) | Sep 16, 2020 |
| HP            | Pavilion dv6700             | [d74f453116](https://linux-hardware.org/?probe=d74f453116) | Aug 16, 2020 |
| MSI           | GP75 Leopard 9SD            | [b8b363d7ff](https://linux-hardware.org/?probe=b8b363d7ff) | Aug 07, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMH    | [872482ce6e](https://linux-hardware.org/?probe=872482ce6e) | Aug 07, 2020 |
| HP            | Pavilion dv6700             | [fbc9ab283a](https://linux-hardware.org/?probe=fbc9ab283a) | Aug 03, 2020 |
| HP            | Pavilion dv6700             | [b217a06354](https://linux-hardware.org/?probe=b217a06354) | Aug 02, 2020 |
| Acer          | TravelMate P215-51G         | [8916655d52](https://linux-hardware.org/?probe=8916655d52) | Jul 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | 240 G7 Notebook PC          | [e9c46bd761](https://linux-hardware.org/?probe=e9c46bd761) | Jun 28, 2020 |
| Acer          | Swift SF314-41              | [0255fcb566](https://linux-hardware.org/?probe=0255fcb566) | Jun 26, 2020 |
| HP            | Pavilion dv6000 (RP297UA... | [1bd24ff33d](https://linux-hardware.org/?probe=1bd24ff33d) | May 27, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [23bc453b75](https://linux-hardware.org/?probe=23bc453b75) | May 10, 2020 |
| HP            | ProBook 430 G6              | [b06dadce70](https://linux-hardware.org/?probe=b06dadce70) | May 08, 2020 |
| Acer          | Aspire ES1-512              | [79811a61ef](https://linux-hardware.org/?probe=79811a61ef) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | [ff056eb6ed](https://linux-hardware.org/?probe=ff056eb6ed) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | [b2b82bcafa](https://linux-hardware.org/?probe=b2b82bcafa) | Apr 25, 2020 |
| ASUSTek       | N56VZ                       | [c8abfa271f](https://linux-hardware.org/?probe=c8abfa271f) | Apr 20, 2020 |
| Dell          | Inspiron 5559               | [5d3e49216d](https://linux-hardware.org/?probe=5d3e49216d) | Apr 18, 2020 |
| Lenovo        | G550 20023                  | [2caebc20ee](https://linux-hardware.org/?probe=2caebc20ee) | Apr 18, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [2c05881776](https://linux-hardware.org/?probe=2c05881776) | Apr 15, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [5541279306](https://linux-hardware.org/?probe=5541279306) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [9e32edc48a](https://linux-hardware.org/?probe=9e32edc48a) | Apr 14, 2020 |
| Toshiba       | Satellite C660              | [e0f010109e](https://linux-hardware.org/?probe=e0f010109e) | Apr 12, 2020 |
| Toshiba       | Satellite C660              | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Dell          | Inspiron 5770               | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| Dell          | Latitude E6230              | [a285b7f196](https://linux-hardware.org/?probe=a285b7f196) | Mar 24, 2020 |
| Toshiba       | Satellite C50D-B            | [837144a177](https://linux-hardware.org/?probe=837144a177) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [57cecbbbce](https://linux-hardware.org/?probe=57cecbbbce) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [8633a66df2](https://linux-hardware.org/?probe=8633a66df2) | Mar 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [72d22ff1c1](https://linux-hardware.org/?probe=72d22ff1c1) | Mar 23, 2020 |
| Lenovo        | G50-70 20351                | [526787b49d](https://linux-hardware.org/?probe=526787b49d) | Mar 08, 2020 |
| ASUSTek       | F3Sg                        | [808275816b](https://linux-hardware.org/?probe=808275816b) | Mar 01, 2020 |
| Acer          | Aspire 5742G                | [9e4356444d](https://linux-hardware.org/?probe=9e4356444d) | Feb 28, 2020 |
| MSI           | GT62VR 6RE                  | [6bb81391a7](https://linux-hardware.org/?probe=6bb81391a7) | Feb 26, 2020 |
| Dell          | Inspiron 5720               | [83127ec84c](https://linux-hardware.org/?probe=83127ec84c) | Feb 22, 2020 |
| ASUSTek       | BU401LAV                    | [adba948317](https://linux-hardware.org/?probe=adba948317) | Feb 16, 2020 |
| Dell          | Inspiron 3584               | [12adda1f05](https://linux-hardware.org/?probe=12adda1f05) | Feb 09, 2020 |
| Dell          | Inspiron 3584               | [5dd6368254](https://linux-hardware.org/?probe=5dd6368254) | Feb 09, 2020 |
| Lenovo        | ThinkPad T430 2347HM4       | [126922ef61](https://linux-hardware.org/?probe=126922ef61) | Feb 02, 2020 |
| Dell          | Latitude E6230              | [809af46e15](https://linux-hardware.org/?probe=809af46e15) | Jan 26, 2020 |
| Dell          | Inspiron 1720               | [14c0a5f6f7](https://linux-hardware.org/?probe=14c0a5f6f7) | Jan 24, 2020 |
| HP            | Laptop 15-db0xxx            | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Lenovo        | ThinkPad T400 6475GC8       | [8263c74190](https://linux-hardware.org/?probe=8263c74190) | Dec 15, 2019 |
| HP            | EliteBook 840 G3            | [90bee29cfb](https://linux-hardware.org/?probe=90bee29cfb) | Dec 08, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | [f7ce0a6b8b](https://linux-hardware.org/?probe=f7ce0a6b8b) | Dec 06, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | [a67a12b126](https://linux-hardware.org/?probe=a67a12b126) | Dec 02, 2019 |
| Dell          | Latitude D630               | [64fec98df4](https://linux-hardware.org/?probe=64fec98df4) | Nov 28, 2019 |
| Acer          | Aspire A515-52G             | [0804d7107b](https://linux-hardware.org/?probe=0804d7107b) | Nov 24, 2019 |
| Acer          | Aspire 5739G                | [363190383f](https://linux-hardware.org/?probe=363190383f) | Nov 23, 2019 |
| Dell          | Latitude E5510              | [e9955b821e](https://linux-hardware.org/?probe=e9955b821e) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [b777297060](https://linux-hardware.org/?probe=b777297060) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [ba39e36ce1](https://linux-hardware.org/?probe=ba39e36ce1) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [a749310754](https://linux-hardware.org/?probe=a749310754) | Nov 17, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [321694ee65](https://linux-hardware.org/?probe=321694ee65) | Nov 16, 2019 |
| HP            | 250 G3                      | [65119a8793](https://linux-hardware.org/?probe=65119a8793) | Oct 17, 2019 |
| ASUSTek       | T100TA                      | [3b8a5ea4c5](https://linux-hardware.org/?probe=3b8a5ea4c5) | Oct 14, 2019 |
| Lenovo        | G70-80 80FF                 | [7c2a22f9c0](https://linux-hardware.org/?probe=7c2a22f9c0) | Oct 06, 2019 |
| Lenovo        | ThinkPad T495 20NK000HMH    | [e97740f470](https://linux-hardware.org/?probe=e97740f470) | Oct 05, 2019 |
| Dell          | Latitude E5510              | [df0c96aafe](https://linux-hardware.org/?probe=df0c96aafe) | Sep 19, 2019 |
| Dell          | Latitude E6230              | [2a12cfbc23](https://linux-hardware.org/?probe=2a12cfbc23) | Sep 18, 2019 |
| HP            | EliteBook 8440p             | [a689023dbd](https://linux-hardware.org/?probe=a689023dbd) | Aug 16, 2019 |
| HP            | EliteBook 8440p             | [beb52301b4](https://linux-hardware.org/?probe=beb52301b4) | Aug 16, 2019 |
| HP            | Laptop 15-bw0xx             | [d02cb45d1e](https://linux-hardware.org/?probe=d02cb45d1e) | Jul 17, 2019 |
| Lenovo        | G70-80 80FF                 | [bc2409772a](https://linux-hardware.org/?probe=bc2409772a) | Jul 02, 2019 |
| Acer          | Extensa 5220                | [c8eddeab31](https://linux-hardware.org/?probe=c8eddeab31) | Jun 30, 2019 |
| Dell          | Inspiron N5010              | [efc321ccd7](https://linux-hardware.org/?probe=efc321ccd7) | May 30, 2019 |
| Dell          | Latitude E6230              | [963d3ebfe9](https://linux-hardware.org/?probe=963d3ebfe9) | May 22, 2019 |
| Toshiba       | Satellite C660              | [57bab28e56](https://linux-hardware.org/?probe=57bab28e56) | May 09, 2019 |
| ASUSTek       | X540SA                      | [a5d1a1f3db](https://linux-hardware.org/?probe=a5d1a1f3db) | Apr 28, 2019 |
| HP            | EliteBook 8560w             | [41b1ae7140](https://linux-hardware.org/?probe=41b1ae7140) | Apr 24, 2019 |
| HP            | ProBook 455 G3              | [f8936a4237](https://linux-hardware.org/?probe=f8936a4237) | Apr 07, 2019 |
| HP            | ProBook 655 G1              | [b1f95b092a](https://linux-hardware.org/?probe=b1f95b092a) | Mar 20, 2019 |
| Dell          | Inspiron 5720               | [4f91b6cf7c](https://linux-hardware.org/?probe=4f91b6cf7c) | Mar 19, 2019 |
| HP            | EliteBook 840 G3            | [be32c043b0](https://linux-hardware.org/?probe=be32c043b0) | Mar 19, 2019 |
| Lenovo        | ThinkPad P71 20HK0005PB     | [c61dcde6cf](https://linux-hardware.org/?probe=c61dcde6cf) | Feb 26, 2019 |
| HP            | ProBook 655 G1              | [2ec1ca3497](https://linux-hardware.org/?probe=2ec1ca3497) | Feb 25, 2019 |
| Dell          | Inspiron 1720               | [0b9fd4ad58](https://linux-hardware.org/?probe=0b9fd4ad58) | Nov 25, 2018 |
| HP            | ProBook 655 G1              | [60b0fba200](https://linux-hardware.org/?probe=60b0fba200) | Nov 23, 2018 |
| HP            | ProBook 655 G1              | [bb508c6afa](https://linux-hardware.org/?probe=bb508c6afa) | Nov 23, 2018 |
| Advent        | Roma                        | [36d20501b0](https://linux-hardware.org/?probe=36d20501b0) | Nov 16, 2018 |
| Advent        | Roma                        | [d7e4c674fb](https://linux-hardware.org/?probe=d7e4c674fb) | Nov 13, 2018 |
| ASUSTek       | N53SM                       | [4d5ff2b12c](https://linux-hardware.org/?probe=4d5ff2b12c) | Nov 12, 2018 |
| Advent        | Roma                        | [7f39913676](https://linux-hardware.org/?probe=7f39913676) | Nov 12, 2018 |
| HP            | Laptop 15-bw0xx             | [dd3560057b](https://linux-hardware.org/?probe=dd3560057b) | Oct 18, 2018 |
| ASUSTek       | X551MA                      | [941fa4532f](https://linux-hardware.org/?probe=941fa4532f) | Sep 16, 2018 |
| ASUSTek       | X551MA                      | [41403ed51e](https://linux-hardware.org/?probe=41403ed51e) | Sep 16, 2018 |
| Lenovo        | G70-80 80FF                 | [b2df76fa94](https://linux-hardware.org/?probe=b2df76fa94) | Jul 10, 2018 |
| Lenovo        | G70-80 80FF                 | [2c5daea589](https://linux-hardware.org/?probe=2c5daea589) | Jul 04, 2018 |
| Lenovo        | G70-80 80FF                 | [81a1c4ab2a](https://linux-hardware.org/?probe=81a1c4ab2a) | Jun 29, 2018 |
| Acer          | Aspire V5-552G              | [06f831207c](https://linux-hardware.org/?probe=06f831207c) | May 12, 2018 |
| HP            | Laptop 15-bw0xx             | [962546fb29](https://linux-hardware.org/?probe=962546fb29) | Mar 17, 2018 |
| Dell          | XPS MXC062                  | [c4448e72da](https://linux-hardware.org/?probe=c4448e72da) | Mar 01, 2018 |
| Samsung       | R528/R728                   | [f4aac127be](https://linux-hardware.org/?probe=f4aac127be) | Feb 24, 2018 |
| ASUSTek       | K73BE                       | [a66962c2cb](https://linux-hardware.org/?probe=a66962c2cb) | Jan 22, 2018 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [736fd47a6c](https://linux-hardware.org/?probe=736fd47a6c) | Nov 09, 2017 |
| ASUSTek       | X553MA                      | [27e37bc3c6](https://linux-hardware.org/?probe=27e37bc3c6) | Nov 04, 2017 |
| ASUSTek       | X551MA                      | [b32fe81f6d](https://linux-hardware.org/?probe=b32fe81f6d) | Sep 21, 2017 |
| ASUSTek       | X553MA                      | [140ec82ebd](https://linux-hardware.org/?probe=140ec82ebd) | Sep 01, 2017 |
| Dell          | XPS L501X                   | [dad4007dd5](https://linux-hardware.org/?probe=dad4007dd5) | Jul 30, 2017 |
| Dell          | Inspiron 1720               | [c9ecc51acf](https://linux-hardware.org/?probe=c9ecc51acf) | Jul 14, 2017 |
| eMachines     | Unknown                     | [ed52c8a528](https://linux-hardware.org/?probe=ed52c8a528) | Apr 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [3e8f4ab377](https://linux-hardware.org/?probe=3e8f4ab377) | Mar 31, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0d0109d420](https://linux-hardware.org/?probe=0d0109d420) | Mar 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [7be53aba27](https://linux-hardware.org/?probe=7be53aba27) | Mar 22, 2017 |
| ASUSTek       | K73BE                       | [6b5bb270b2](https://linux-hardware.org/?probe=6b5bb270b2) | Mar 19, 2017 |
| ASUSTek       | F9S                         | [932ca241f8](https://linux-hardware.org/?probe=932ca241f8) | Feb 19, 2017 |
| ASUSTek       | K53SD                       | [7ccf014558](https://linux-hardware.org/?probe=7ccf014558) | Nov 06, 2016 |
| ASUSTek       | K73BE                       | [bf7bf43a14](https://linux-hardware.org/?probe=bf7bf43a14) | Oct 30, 2016 |
| Dell          | Inspiron 1720               | [94502c2b70](https://linux-hardware.org/?probe=94502c2b70) | Oct 26, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 23        | 6.99%   |
| ROSA R11           | 14        | 4.26%   |
| Arch Rolling       | 12        | 3.65%   |
| Ubuntu 18.04       | 10        | 3.04%   |
| Pop!_OS 22.04      | 10        | 3.04%   |
| Debian 11          | 8         | 2.43%   |
| Ubuntu 22.04       | 7         | 2.13%   |
| ROSA R9            | 7         | 2.13%   |
| ROSA R10           | 6         | 1.82%   |
| OpenMandriva 4.3   | 6         | 1.82%   |
| Manjaro            | 6         | 1.82%   |
| Arch               | 6         | 1.82%   |
| ROSA R8.1          | 5         | 1.52%   |
| ROSA R11.1         | 5         | 1.52%   |
| Linux Mint 20.3    | 5         | 1.52%   |
| Debian 12          | 5         | 1.52%   |
| ROSA R8            | 4         | 1.22%   |
| ROSA 12.3          | 4         | 1.22%   |
| Pop!_OS 21.04      | 4         | 1.22%   |
| Pop!_OS 20.10      | 4         | 1.22%   |
| OpenMandriva 23.08 | 4         | 1.22%   |
| Linux Mint 21      | 4         | 1.22%   |
| KDE neon 22.04     | 4         | 1.22%   |
| KDE neon 20.04     | 4         | 1.22%   |
| Fedora 42          | 4         | 1.22%   |
| Fedora 40          | 4         | 1.22%   |
| ArcoLinux Rolling  | 4         | 1.22%   |
| Ubuntu 19.10       | 3         | 0.91%   |
| ROSA 12.1          | 3         | 0.91%   |
| OpenMandriva 25.90 | 3         | 0.91%   |
| Linux Mint 22.1    | 3         | 0.91%   |
| Linux Mint 21.2    | 3         | 0.91%   |
| Linux Mint 19      | 3         | 0.91%   |
| Linux Mint 18.3    | 3         | 0.91%   |
| Fedora 41          | 3         | 0.91%   |
| Fedora 37          | 3         | 0.91%   |
| Fedora 34          | 3         | 0.91%   |
| Zorin 17           | 2         | 0.61%   |
| Zorin 16           | 2         | 0.61%   |
| Xubuntu 20.04      | 2         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 57        | 19.39%  |
| ROSA          | 38        | 12.93%  |
| Linux Mint    | 27        | 9.18%   |
| Fedora        | 21        | 7.14%   |
| Pop!_OS       | 19        | 6.46%   |
| OpenMandriva  | 19        | 6.46%   |
| Debian        | 18        | 6.12%   |
| Arch          | 18        | 6.12%   |
| Manjaro       | 11        | 3.74%   |
| KDE neon      | 9         | 3.06%   |
| Zorin         | 5         | 1.7%    |
| Kubuntu       | 5         | 1.7%    |
| Elementary    | 5         | 1.7%    |
| ArcoLinux     | 5         | 1.7%    |
| Xubuntu       | 4         | 1.36%   |
| Ubuntu Unity  | 3         | 1.02%   |
| SteamOS       | 3         | 1.02%   |
| openSUSE      | 3         | 1.02%   |
| Kali          | 3         | 1.02%   |
| Bazzite       | 3         | 1.02%   |
| Garuda Linux  | 2         | 0.68%   |
| Endless       | 2         | 0.68%   |
| EndeavourOS   | 2         | 0.68%   |
| Void Linux    | 1         | 0.34%   |
| Ubuntu Budgie | 1         | 0.34%   |
| TUXEDO OS     | 1         | 0.34%   |
| Solus         | 1         | 0.34%   |
| Peppermint    | 1         | 0.34%   |
| Parrot        | 1         | 0.34%   |
| Oracle Linux  | 1         | 0.34%   |
| Nobara        | 1         | 0.34%   |
| NixOS         | 1         | 0.34%   |
| MX            | 1         | 0.34%   |
| Lubuntu       | 1         | 0.34%   |
| GNOME OS      | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 6         | 1.6%    |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 1.6%    |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 1.6%    |
| 6.14.2-desktop-3omv2590            | 4         | 1.07%   |
| 5.4.0-42-generic                   | 4         | 1.07%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 1.07%   |
| 5.8.0-7630-generic                 | 3         | 0.8%    |
| 5.15.0-58-generic                  | 3         | 0.8%    |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 3         | 0.8%    |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 0.8%    |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 0.8%    |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 0.8%    |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 3         | 0.8%    |
| 6.8.7-300.fc40.x86_64              | 2         | 0.53%   |
| 6.8.0-55-generic                   | 2         | 0.53%   |
| 6.8.0-51-generic                   | 2         | 0.53%   |
| 6.8.0-49-generic                   | 2         | 0.53%   |
| 6.8.0-40-generic                   | 2         | 0.53%   |
| 6.4.8-desktop-2omv2390             | 2         | 0.53%   |
| 6.4.11-desktop-1omv2390            | 2         | 0.53%   |
| 6.2.6-76060206-generic             | 2         | 0.53%   |
| 6.2.0-20-generic                   | 2         | 0.53%   |
| 6.16.3-76061603-generic            | 2         | 0.53%   |
| 6.16.12-200.fc42.x86_64            | 2         | 0.53%   |
| 6.1.1-desktop-1omv2290             | 2         | 0.53%   |
| 5.8.0-48-generic                   | 2         | 0.53%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 0.53%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.53%   |
| 5.4.0-80-generic                   | 2         | 0.53%   |
| 5.4.0-26-generic                   | 2         | 0.53%   |
| 5.15.79-generic-1rosa2021.1-x86_64 | 2         | 0.53%   |
| 5.15.75-generic-1rosa2021.1-x86_64 | 2         | 0.53%   |
| 5.15.0-91-generic                  | 2         | 0.53%   |
| 5.15.0-86-generic                  | 2         | 0.53%   |
| 5.15.0-67-generic                  | 2         | 0.53%   |
| 5.15.0-56-generic                  | 2         | 0.53%   |
| 5.15.0-52-generic                  | 2         | 0.53%   |
| 5.15.0-46-generic                  | 2         | 0.53%   |
| 5.13.6-arch1-1                     | 2         | 0.53%   |
| 5.13.0-25-generic                  | 2         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 33        | 9.46%   |
| 4.15.0  | 22        | 6.3%    |
| 5.15.0  | 19        | 5.44%   |
| 6.8.0   | 12        | 3.44%   |
| 5.11.0  | 11        | 3.15%   |
| 5.8.0   | 10        | 2.87%   |
| 5.13.0  | 10        | 2.87%   |
| 5.10.0  | 8         | 2.29%   |
| 6.2.0   | 7         | 2.01%   |
| 6.5.0   | 6         | 1.72%   |
| 5.3.0   | 6         | 1.72%   |
| 5.16.7  | 6         | 1.72%   |
| 4.9.20  | 6         | 1.72%   |
| 6.14.2  | 5         | 1.43%   |
| 6.11.0  | 4         | 1.15%   |
| 6.1.0   | 4         | 1.15%   |
| 5.10.74 | 4         | 1.15%   |
| 5.0.0   | 4         | 1.15%   |
| 4.18.0  | 4         | 1.15%   |
| 6.2.6   | 3         | 0.86%   |
| 6.14.0  | 3         | 0.86%   |
| 5.19.0  | 3         | 0.86%   |
| 5.17.1  | 3         | 0.86%   |
| 4.9.60  | 3         | 0.86%   |
| 4.9.41  | 3         | 0.86%   |
| 4.9.155 | 3         | 0.86%   |
| 4.1.34  | 3         | 0.86%   |
| 6.9.7   | 2         | 0.57%   |
| 6.8.7   | 2         | 0.57%   |
| 6.6.1   | 2         | 0.57%   |
| 6.4.8   | 2         | 0.57%   |
| 6.4.11  | 2         | 0.57%   |
| 6.17.7  | 2         | 0.57%   |
| 6.16.3  | 2         | 0.57%   |
| 6.16.12 | 2         | 0.57%   |
| 6.15.4  | 2         | 0.57%   |
| 6.1.1   | 2         | 0.57%   |
| 6.0.9   | 2         | 0.57%   |
| 5.4.83  | 2         | 0.57%   |
| 5.4.72  | 2         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 38        | 11.21%  |
| 5.15    | 30        | 8.85%   |
| 4.15    | 22        | 6.49%   |
| 4.9     | 16        | 4.72%   |
| 6.8     | 15        | 4.42%   |
| 5.13    | 15        | 4.42%   |
| 5.10    | 15        | 4.42%   |
| 6.1     | 14        | 4.13%   |
| 5.8     | 12        | 3.54%   |
| 5.11    | 12        | 3.54%   |
| 6.2     | 10        | 2.95%   |
| 6.14    | 10        | 2.95%   |
| 5.16    | 9         | 2.65%   |
| 6.5     | 8         | 2.36%   |
| 6.12    | 8         | 2.36%   |
| 6.0     | 7         | 2.06%   |
| 6.11    | 6         | 1.77%   |
| 5.3     | 6         | 1.77%   |
| 5.19    | 6         | 1.77%   |
| 5.12    | 6         | 1.77%   |
| 6.6     | 5         | 1.47%   |
| 6.4     | 5         | 1.47%   |
| 6.16    | 5         | 1.47%   |
| 6.9     | 4         | 1.18%   |
| 6.13    | 4         | 1.18%   |
| 5.18    | 4         | 1.18%   |
| 5.17    | 4         | 1.18%   |
| 5.14    | 4         | 1.18%   |
| 5.0     | 4         | 1.18%   |
| 4.18    | 4         | 1.18%   |
| 4.1     | 4         | 1.18%   |
| 6.17    | 3         | 0.88%   |
| 5.5     | 3         | 0.88%   |
| 6.7     | 2         | 0.59%   |
| 6.3     | 2         | 0.59%   |
| 6.15    | 2         | 0.59%   |
| 5.9     | 2         | 0.59%   |
| 4.4     | 2         | 0.59%   |
| 4.19    | 2         | 0.59%   |
| 4.13    | 2         | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 278       | 96.86%  |
| i686   | 9         | 3.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 111       | 36.04%  |
| KDE5              | 62        | 20.13%  |
| KDE4              | 25        | 8.12%   |
| Unknown           | 22        | 7.14%   |
| XFCE              | 21        | 6.82%   |
| KDE6              | 13        | 4.22%   |
| X-Cinnamon        | 12        | 3.9%    |
| MATE              | 10        | 3.25%   |
| Pantheon          | 5         | 1.62%   |
| LXQt              | 5         | 1.62%   |
| KDE               | 5         | 1.62%   |
| Budgie            | 4         | 1.3%    |
| Unity             | 3         | 0.97%   |
| i3                | 3         | 0.97%   |
| Cinnamon          | 3         | 0.97%   |
| x-session-manager | 1         | 0.32%   |
| sway              | 1         | 0.32%   |
| LXDE              | 1         | 0.32%   |
| COSMIC            | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 210       | 70%     |
| Wayland | 73        | 24.33%  |
| Unknown | 11        | 3.67%   |
| Tty     | 6         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 119       | 39.8%   |
| SDDM    | 54        | 18.06%  |
| GDM     | 39        | 13.04%  |
| GDM3    | 25        | 8.36%   |
| LightDM | 24        | 8.03%   |
| KDM     | 24        | 8.03%   |
| TDM     | 11        | 3.68%   |
| SLiM    | 1         | 0.33%   |
| MDM     | 1         | 0.33%   |
| LDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 165       | 55.37%  |
| Unknown     | 44        | 14.77%  |
| ru_RU       | 36        | 12.08%  |
| lv_LV       | 29        | 9.73%   |
| en_GB       | 11        | 3.69%   |
| C           | 5         | 1.68%   |
| de_DE       | 2         | 0.67%   |
| ru_UA       | 1         | 0.34%   |
| ru_RU.UTF_8 | 1         | 0.34%   |
| POSIX       | 1         | 0.34%   |
| pl_PL       | 1         | 0.34%   |
| fr_FR       | 1         | 0.34%   |
| en_AG       | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 155       | 53.08%  |
| EFI  | 137       | 46.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 206       | 69.36%  |
| Btrfs   | 41        | 13.8%   |
| Overlay | 17        | 5.72%   |
| Unknown | 16        | 5.39%   |
| Tmpfs   | 11        | 3.7%    |
| Xfs     | 4         | 1.35%   |
| Zfs     | 2         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 126       | 42%     |
| GPT     | 125       | 41.67%  |
| MBR     | 49        | 16.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 264       | 88.59%  |
| Yes       | 34        | 11.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 218       | 74.91%  |
| Yes       | 73        | 25.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 72        | 25.09%  |
| ASUSTek Computer    | 48        | 16.72%  |
| Hewlett-Packard     | 41        | 14.29%  |
| Dell                | 39        | 13.59%  |
| Acer                | 27        | 9.41%   |
| MSI                 | 9         | 3.14%   |
| Apple               | 8         | 2.79%   |
| Toshiba             | 7         | 2.44%   |
| Samsung Electronics | 5         | 1.74%   |
| Fujitsu Siemens     | 5         | 1.74%   |
| Valve               | 3         | 1.05%   |
| Packard Bell        | 3         | 1.05%   |
| HUAWEI              | 3         | 1.05%   |
| TUXEDO              | 2         | 0.7%    |
| Sony                | 2         | 0.7%    |
| Gigabyte Technology | 2         | 0.7%    |
| eMachines           | 2         | 0.7%    |
| Wortmann AG         | 1         | 0.35%   |
| Timi                | 1         | 0.35%   |
| Razer               | 1         | 0.35%   |
| Quanta              | 1         | 0.35%   |
| mPTech              | 1         | 0.35%   |
| Fujitsu             | 1         | 0.35%   |
| Chuwi               | 1         | 0.35%   |
| Advent              | 1         | 0.35%   |
| Unknown             | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 4         | 1.39%   |
| Toshiba Satellite C660                                | 3         | 1.05%   |
| HP EliteBook 840 G3                                   | 3         | 1.05%   |
| HP 250 G6 Notebook PC                                 | 3         | 1.05%   |
| ASUS X553MA                                           | 3         | 1.05%   |
| Apple MacBookPro8,1                                   | 3         | 1.05%   |
| Valve Galileo                                         | 2         | 0.7%    |
| Lenovo Legion 5 15ACH6H 82JU                          | 2         | 0.7%    |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 0.7%    |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 0.7%    |
| HP G62                                                | 2         | 0.7%    |
| HP EliteBook 8440p                                    | 2         | 0.7%    |
| Fujitsu Siemens LIFEBOOK S6420                        | 2         | 0.7%    |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 0.7%    |
| ASUS X551MA                                           | 2         | 0.7%    |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA              | 2         | 0.7%    |
| Wortmann AG CR700                                     | 1         | 0.35%   |
| Valve Jupiter                                         | 1         | 0.35%   |
| TUXEDO Gemini Gen2                                    | 1         | 0.35%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.35%   |
| Toshiba Satellite L750                                | 1         | 0.35%   |
| Toshiba Satellite L350                                | 1         | 0.35%   |
| Toshiba Satellite C50D-B                              | 1         | 0.35%   |
| Timi A35S                                             | 1         | 0.35%   |
| Sony VPCEE4E1E                                        | 1         | 0.35%   |
| Sony VPCCW2S8E                                        | 1         | 0.35%   |
| Samsung RV410/RV510/S3510/E3510                       | 1         | 0.35%   |
| Samsung R528/R728                                     | 1         | 0.35%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.35%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.35%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.35%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.35%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.35%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.35%   |
| Packard Bell EasyNote LM85                            | 1         | 0.35%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.35%   |
| MSI Stealth 16 AI Studio A1VIG                        | 1         | 0.35%   |
| MSI Modern 14 B4MW                                    | 1         | 0.35%   |
| MSI Katana GF76 12UC                                  | 1         | 0.35%   |
| MSI Katana GF76 11UE                                  | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 38        | 13.24%  |
| Acer Aspire              | 17        | 5.92%   |
| Lenovo IdeaPad           | 16        | 5.57%   |
| Dell Inspiron            | 14        | 4.88%   |
| HP EliteBook             | 13        | 4.53%   |
| Dell Latitude            | 13        | 4.53%   |
| ASUS VivoBook            | 10        | 3.48%   |
| Toshiba Satellite        | 7         | 2.44%   |
| HP Pavilion              | 7         | 2.44%   |
| Lenovo Legion            | 5         | 1.74%   |
| HP ProBook               | 5         | 1.74%   |
| HP Laptop                | 5         | 1.74%   |
| HP 250                   | 4         | 1.39%   |
| Dell Vostro              | 4         | 1.39%   |
| Unknown                  | 4         | 1.39%   |
| Packard Bell EasyNote    | 3         | 1.05%   |
| Lenovo ThinkBook         | 3         | 1.05%   |
| Fujitsu Siemens LIFEBOOK | 3         | 1.05%   |
| Dell Precision           | 3         | 1.05%   |
| ASUS Zenbook             | 3         | 1.05%   |
| ASUS X553MA              | 3         | 1.05%   |
| ASUS TUF                 | 3         | 1.05%   |
| Apple MacBookPro8        | 3         | 1.05%   |
| Acer Nitro               | 3         | 1.05%   |
| Valve Galileo            | 2         | 0.7%    |
| MSI Katana               | 2         | 0.7%    |
| HP G62                   | 2         | 0.7%    |
| Fujitsu Siemens AMILO    | 2         | 0.7%    |
| Dell XPS                 | 2         | 0.7%    |
| ASUS X551MA              | 2         | 0.7%    |
| ASUS ROG                 | 2         | 0.7%    |
| ASUS ASUS                | 2         | 0.7%    |
| Acer Extensa             | 2         | 0.7%    |
| Wortmann AG CR700        | 1         | 0.35%   |
| Valve Jupiter            | 1         | 0.35%   |
| TUXEDO Gemini            | 1         | 0.35%   |
| Timi A35S                | 1         | 0.35%   |
| Sony VPCEE4E1E           | 1         | 0.35%   |
| Sony VPCCW2S8E           | 1         | 0.35%   |
| Samsung RV410            | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 24        | 8.36%   |
| 2011 | 24        | 8.36%   |
| 2021 | 22        | 7.67%   |
| 2020 | 20        | 6.97%   |
| 2015 | 20        | 6.97%   |
| 2013 | 20        | 6.97%   |
| 2014 | 19        | 6.62%   |
| 2012 | 19        | 6.62%   |
| 2018 | 17        | 5.92%   |
| 2010 | 17        | 5.92%   |
| 2017 | 16        | 5.57%   |
| 2008 | 15        | 5.23%   |
| 2016 | 11        | 3.83%   |
| 2009 | 11        | 3.83%   |
| 2022 | 9         | 3.14%   |
| 2023 | 8         | 2.79%   |
| 2007 | 7         | 2.44%   |
| 2024 | 4         | 1.39%   |
| 2006 | 3         | 1.05%   |
| 2025 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 287       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 263       | 90.69%  |
| Enabled  | 27        | 9.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 286       | 99.65%  |
| Yes  | 1         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 79        | 27.15%  |
| 3.01-4.0    | 77        | 26.46%  |
| 8.01-16.0   | 47        | 16.15%  |
| 16.01-24.0  | 42        | 14.43%  |
| 32.01-64.0  | 19        | 6.53%   |
| 2.01-3.0    | 10        | 3.44%   |
| 1.01-2.0    | 8         | 2.75%   |
| 24.01-32.0  | 6         | 2.06%   |
| 0.51-1.0    | 2         | 0.69%   |
| 64.01-256.0 | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 97        | 30.03%  |
| 2.01-3.0   | 79        | 24.46%  |
| 4.01-8.0   | 54        | 16.72%  |
| 3.01-4.0   | 39        | 12.07%  |
| 0.51-1.0   | 33        | 10.22%  |
| 8.01-16.0  | 17        | 5.26%   |
| 16.01-24.0 | 3         | 0.93%   |
| 0.01-0.5   | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 216       | 74.48%  |
| 2      | 65        | 22.41%  |
| 3      | 6         | 2.07%   |
| 0      | 2         | 0.69%   |
| 4      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 184       | 63.01%  |
| Yes       | 108       | 36.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 85.12%  |
| No        | 43        | 14.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 279       | 97.21%  |
| No        | 8         | 2.79%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 75.77%  |
| No        | 71        | 24.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Latvia  | 287       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Riga                    | 227       | 73.46%  |
| Liepāja                | 9         | 2.91%   |
| Jelgava                 | 8         | 2.59%   |
| Daugavpils              | 7         | 2.27%   |
| Salaspils               | 3         | 0.97%   |
| Jūrmala                | 3         | 0.97%   |
| Jaunolaine              | 3         | 0.97%   |
| Jaunmarupe              | 3         | 0.97%   |
| Iecava                  | 3         | 0.97%   |
| Adazi                   | 3         | 0.97%   |
| Valmiera                | 2         | 0.65%   |
| Saulkrasti              | 2         | 0.65%   |
| Rēzekne                | 2         | 0.65%   |
| Malpils                 | 2         | 0.65%   |
| Kuldīga                | 2         | 0.65%   |
| Ķekava                 | 2         | 0.65%   |
| Jēkabpils              | 2         | 0.65%   |
| Cēsis                  | 2         | 0.65%   |
| Zvejniekciems           | 1         | 0.32%   |
| Ventspils               | 1         | 0.32%   |
| Ulbroka                 | 1         | 0.32%   |
| Tukums                  | 1         | 0.32%   |
| Tiraine                 | 1         | 0.32%   |
| Smiltene                | 1         | 0.32%   |
| Saulkalne               | 1         | 0.32%   |
| Saldus                  | 1         | 0.32%   |
| Preiļi                 | 1         | 0.32%   |
| Pļaviņas              | 1         | 0.32%   |
| Ozolnieki               | 1         | 0.32%   |
| Ogre                    | 1         | 0.32%   |
| Nereta                  | 1         | 0.32%   |
| Lizums                  | 1         | 0.32%   |
| Limbaži                | 1         | 0.32%   |
| Jēkabpils Municipality | 1         | 0.32%   |
| Inčukalns              | 1         | 0.32%   |
| Garkalne                | 1         | 0.32%   |
| Garciems                | 1         | 0.32%   |
| Dobele                  | 1         | 0.32%   |
| Dagda                   | 1         | 0.32%   |
| Bukulti                 | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 57        | 76     | 16.38%  |
| Seagate                     | 44        | 52     | 12.64%  |
| Kingston                    | 36        | 62     | 10.34%  |
| WDC                         | 33        | 44     | 9.48%   |
| Toshiba                     | 29        | 32     | 8.33%   |
| Micron Technology           | 14        | 16     | 4.02%   |
| Hitachi                     | 14        | 18     | 4.02%   |
| Unknown                     | 12        | 14     | 3.45%   |
| SK hynix                    | 12        | 14     | 3.45%   |
| SanDisk                     | 10        | 21     | 2.87%   |
| HGST                        | 10        | 19     | 2.87%   |
| Intel                       | 9         | 11     | 2.59%   |
| KIOXIA                      | 7         | 10     | 2.01%   |
| A-DATA Technology           | 6         | 7      | 1.72%   |
| Patriot                     | 5         | 11     | 1.44%   |
| Crucial                     | 5         | 5      | 1.44%   |
| Apple                       | 5         | 5      | 1.44%   |
| SPCC                        | 3         | 3      | 0.86%   |
| Kingston Technology Company | 3         | 4      | 0.86%   |
| Unknown                     | 3         | 6      | 0.86%   |
| Phison Electronics          | 2         | 2      | 0.57%   |
| Phison                      | 2         | 2      | 0.57%   |
| LITEON                      | 2         | 2      | 0.57%   |
| Lexar                       | 2         | 2      | 0.57%   |
| Integral                    | 2         | 2      | 0.57%   |
| China                       | 2         | 2      | 0.57%   |
| Verbatim                    | 1         | 1      | 0.29%   |
| USB                         | 1         | 1      | 0.29%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.29%   |
| SSSTC                       | 1         | 1      | 0.29%   |
| Realtek                     | 1         | 1      | 0.29%   |
| PNY                         | 1         | 1      | 0.29%   |
| Plextor                     | 1         | 1      | 0.29%   |
| Platinet                    | 1         | 1      | 0.29%   |
| OCZ                         | 1         | 1      | 0.29%   |
| Netac                       | 1         | 1      | 0.29%   |
| LITEONIT                    | 1         | 1      | 0.29%   |
| LITEON C                    | 1         | 1      | 0.29%   |
| KingSpec                    | 1         | 1      | 0.29%   |
| Kingchuxing                 | 1         | 18     | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 8         | 2.23%   |
| Seagate ST500LT012-1DG142 500GB                   | 7         | 1.96%   |
| Kingston SV300S37A120G 120GB SSD                  | 7         | 1.96%   |
| Toshiba MQ01ABF050 500GB                          | 6         | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB                    | 6         | 1.68%   |
| Seagate ST1000LM048-2E7172 1TB                    | 4         | 1.12%   |
| Samsung SSD 850 EVO 500GB                         | 4         | 1.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.12%   |
| Hitachi HTS545050B9A300 500GB                     | 4         | 1.12%   |
| Toshiba MQ04ABF100 1TB                            | 3         | 0.84%   |
| Toshiba MQ01ABD100 1TB                            | 3         | 0.84%   |
| Seagate ST9500325AS 500GB                         | 3         | 0.84%   |
| Seagate ST9160821AS 160GB                         | 3         | 0.84%   |
| Seagate ST500LT012-9WS142 500GB                   | 3         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 3         | 0.84%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD               | 3         | 0.84%   |
| Samsung SSD 860 EVO 500GB                         | 3         | 0.84%   |
| Hitachi HTS547575A9E384 752GB                     | 3         | 0.84%   |
| Hitachi HTS545050A7E380 500GB                     | 3         | 0.84%   |
| HGST HTS545050A7E680 500GB                        | 3         | 0.84%   |
| Unknown                                           | 3         | 0.84%   |
| WDC WD5000LPVX-80V0TT0 500GB                      | 2         | 0.56%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.56%   |
| WDC WD5000BPVT-22HXZT3 500GB                      | 2         | 0.56%   |
| Unknown NVMe SSD Drive 512GB                      | 2         | 0.56%   |
| Unknown MMC Card  128GB                           | 2         | 0.56%   |
| Toshiba MK8034GSX 80GB                            | 2         | 0.56%   |
| Toshiba MK6465GSX 640GB                           | 2         | 0.56%   |
| SPCC Solid State Disk 128GB                       | 2         | 0.56%   |
| SK hynix HFM512GDJTNG-8310A 512GB                 | 2         | 0.56%   |
| SK hynix BC511 NVMe 256GB                         | 2         | 0.56%   |
| Seagate ST320LT007-9ZV142 320GB                   | 2         | 0.56%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 2         | 0.56%   |
| SanDisk NVMe SSD Drive 512GB                      | 2         | 0.56%   |
| SanDisk NVMe SSD Drive 256GB                      | 2         | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB                    | 2         | 0.56%   |
| Samsung SSD 870 QVO 1TB                           | 2         | 0.56%   |
| Samsung SSD 860 PRO 256GB                         | 2         | 0.56%   |
| Samsung NVMe SSD Drive 1TB                        | 2         | 0.56%   |
| Samsung MZVL4512HBLU-00BTW 512GB                  | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 52     | 35.2%   |
| WDC                 | 26        | 35     | 20.8%   |
| Toshiba             | 23        | 26     | 18.4%   |
| Hitachi             | 14        | 18     | 11.2%   |
| HGST                | 10        | 19     | 8%      |
| Samsung Electronics | 4         | 5      | 3.2%    |
| USB                 | 1         | 1      | 0.8%    |
| Unknown             | 1         | 1      | 0.8%    |
| Fujitsu             | 1         | 1      | 0.8%    |
| Apple               | 1         | 1      | 0.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 31        | 54     | 27.93%  |
| Samsung Electronics | 28        | 38     | 25.23%  |
| A-DATA Technology   | 6         | 7      | 5.41%   |
| Patriot             | 5         | 11     | 4.5%    |
| Crucial             | 5         | 5      | 4.5%    |
| SanDisk             | 4         | 7      | 3.6%    |
| Apple               | 4         | 4      | 3.6%    |
| SPCC                | 3         | 3      | 2.7%    |
| Micron Technology   | 3         | 3      | 2.7%    |
| WDC                 | 2         | 2      | 1.8%    |
| LITEON              | 2         | 2      | 1.8%    |
| Integral            | 2         | 2      | 1.8%    |
| China               | 2         | 2      | 1.8%    |
| Unknown             | 2         | 4      | 1.8%    |
| Verbatim            | 1         | 1      | 0.9%    |
| Toshiba             | 1         | 1      | 0.9%    |
| PNY                 | 1         | 1      | 0.9%    |
| Plextor             | 1         | 1      | 0.9%    |
| Platinet            | 1         | 1      | 0.9%    |
| OCZ                 | 1         | 1      | 0.9%    |
| LITEONIT            | 1         | 1      | 0.9%    |
| LITEON C            | 1         | 1      | 0.9%    |
| Lexar               | 1         | 1      | 0.9%    |
| KingSpec            | 1         | 1      | 0.9%    |
| Intenso             | 1         | 1      | 0.9%    |
| GOODRAM             | 1         | 1      | 0.9%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 120       | 159    | 36.14%  |
| SSD     | 105       | 156    | 31.63%  |
| NVMe    | 97        | 132    | 29.22%  |
| MMC     | 8         | 11     | 2.41%   |
| Unknown | 2         | 27     | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 199       | 328    | 63.58%  |
| NVMe | 97        | 130    | 30.99%  |
| SAS  | 9         | 16     | 2.88%   |
| MMC  | 8         | 11     | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 160       | 236    | 72.4%   |
| 0.51-1.0   | 55        | 73     | 24.89%  |
| 1.01-2.0   | 6         | 6      | 2.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 102       | 32.69%  |
| 251-500        | 73        | 23.4%   |
| 501-1000       | 46        | 14.74%  |
| 1-20           | 23        | 7.37%   |
| 1001-2000      | 21        | 6.73%   |
| 51-100         | 21        | 6.73%   |
| 21-50          | 11        | 3.53%   |
| Unknown        | 8         | 2.56%   |
| 2001-3000      | 6         | 1.92%   |
| More than 3000 | 1         | 0.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 135       | 42.72%  |
| 21-50     | 52        | 16.46%  |
| 51-100    | 39        | 12.34%  |
| 101-250   | 37        | 11.71%  |
| 251-500   | 22        | 6.96%   |
| 501-1000  | 16        | 5.06%   |
| Unknown   | 8         | 2.53%   |
| 1001-2000 | 6         | 1.9%    |
| 2001-3000 | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB      | 3         | 3      | 9.09%   |
| Seagate ST9500325AS 500GB            | 2         | 4      | 6.06%   |
| HGST HTS545050A7E680 500GB           | 2         | 2      | 6.06%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 1      | 3.03%   |
| WDC WD3200BEVT-75ZCT0 320GB          | 1         | 4      | 3.03%   |
| WDC WD1600BEVS-60RST0 160GB          | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 3.03%   |
| Toshiba MK8034GSX 80GB               | 1         | 1      | 3.03%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 3.03%   |
| Toshiba MK6465GSX 640GB              | 1         | 1      | 3.03%   |
| SSSTC CL4-4D256-Q79 256GB            | 1         | 1      | 3.03%   |
| Seagate ST9500420AS 500GB            | 1         | 1      | 3.03%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 3.03%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 3.03%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 3.03%   |
| Samsung Electronics HN-M750MBB 752GB | 1         | 1      | 3.03%   |
| Samsung Electronics HM321HI 320GB    | 1         | 1      | 3.03%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1      | 3.03%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1      | 3.03%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 2      | 3.03%   |
| Hitachi HTS725050A9A364 500GB        | 1         | 1      | 3.03%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 3.03%   |
| Hitachi HTS542516K9SA00 160GB        | 1         | 1      | 3.03%   |
| HGST HTS725050A7E630 500GB           | 1         | 1      | 3.03%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 3.03%   |
| HGST HTS721010A9E630 1TB             | 1         | 2      | 3.03%   |
| HGST HTS541075A9E680 752GB           | 1         | 2      | 3.03%   |
| HGST HTS541010B7E610 1TB             | 1         | 1      | 3.03%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 11     | 27.27%  |
| HGST                | 8         | 11     | 24.24%  |
| Toshiba             | 4         | 4      | 12.12%  |
| WDC                 | 3         | 6      | 9.09%   |
| Kingston            | 3         | 4      | 9.09%   |
| Hitachi             | 3         | 3      | 9.09%   |
| Samsung Electronics | 2         | 2      | 6.06%   |
| SSSTC               | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 11     | 31.03%  |
| HGST                | 8         | 11     | 27.59%  |
| Toshiba             | 4         | 4      | 13.79%  |
| WDC                 | 3         | 6      | 10.34%  |
| Hitachi             | 3         | 3      | 10.34%  |
| Samsung Electronics | 2         | 2      | 6.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 37     | 87.5%   |
| SSD  | 3         | 4      | 9.38%   |
| NVMe | 1         | 1      | 3.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB     | 1         | 1      | 50%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 139       | 247    | 46.18%  |
| Works    | 128       | 194    | 42.52%  |
| Malfunc  | 32        | 42     | 10.63%  |
| Failed   | 2         | 2      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 211       | 61.7%   |
| Samsung Electronics            | 30        | 8.77%   |
| AMD                            | 30        | 8.77%   |
| SK hynix                       | 12        | 3.51%   |
| SanDisk                        | 12        | 3.51%   |
| Micron Technology              | 11        | 3.22%   |
| Kingston Technology Company    | 9         | 2.63%   |
| KIOXIA                         | 8         | 2.34%   |
| Toshiba America Info Systems   | 4         | 1.17%   |
| Phison Electronics             | 4         | 1.17%   |
| Union Memory (Shenzhen)        | 2         | 0.58%   |
| Nvidia                         | 2         | 0.58%   |
| Solidigm                       | 1         | 0.29%   |
| Solid State Storage Technology | 1         | 0.29%   |
| Silicon Motion                 | 1         | 0.29%   |
| Silicon Image                  | 1         | 0.29%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.29%   |
| Marvell Technology Group       | 1         | 0.29%   |
| ADATA Technology               | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 7.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 24        | 6.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 20        | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 19        | 5.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 18        | 4.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 3.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 2.95%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 2.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 2.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 2.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 2.41%   |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 2.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 2.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 1.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 1.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.88%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 1.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 6         | 1.61%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 6         | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 1.34%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.34%   |
| Intel SSD 660P Series                                                            | 4         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.07%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3         | 0.8%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 3         | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.8%    |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 3         | 0.8%    |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 3         | 0.8%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 3         | 0.8%    |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                       | 3         | 0.8%    |
| Intel Tiger Lake SATA AHCI Controller                                            | 3         | 0.8%    |
| Intel SSD 670p Series [Keystone Harbor]                                          | 3         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.8%    |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 2         | 0.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.54%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                | 2         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 217       | 59.78%  |
| NVMe | 100       | 27.55%  |
| RAID | 25        | 6.89%   |
| IDE  | 21        | 5.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 233       | 81.18%  |
| AMD    | 54        | 18.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 2.09%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 2.09%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 2.09%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.39%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.39%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 1.39%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 1.05%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 1.05%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.05%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.05%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.05%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.05%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.05%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 1.05%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.05%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.05%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.05%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.05%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.05%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.7%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.7%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.7%    |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.7%    |
| Intel Core i7-10875H CPU @ 2.30GHz            | 2         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.7%    |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 67        | 23.34%  |
| Intel Core i7           | 45        | 15.68%  |
| Other                   | 30        | 10.45%  |
| Intel Core i3           | 26        | 9.06%   |
| Intel Core 2 Duo        | 20        | 6.97%   |
| Intel Celeron           | 20        | 6.97%   |
| AMD Ryzen 5             | 15        | 5.23%   |
| AMD Ryzen 7             | 13        | 4.53%   |
| Intel Pentium           | 11        | 3.83%   |
| Intel Pentium Dual-Core | 4         | 1.39%   |
| AMD Ryzen 7 PRO         | 4         | 1.39%   |
| Intel Pentium Dual      | 3         | 1.05%   |
| Intel Genuine           | 3         | 1.05%   |
| Intel Core              | 3         | 1.05%   |
| AMD A10                 | 3         | 1.05%   |
| Intel Core 2            | 2         | 0.7%    |
| AMD Turion 64 X2 Mobile | 2         | 0.7%    |
| AMD Ryzen 3             | 2         | 0.7%    |
| AMD E1                  | 2         | 0.7%    |
| AMD A8                  | 2         | 0.7%    |
| Intel Xeon              | 1         | 0.35%   |
| Intel Pentium Gold      | 1         | 0.35%   |
| Intel Celeron Dual-Core | 1         | 0.35%   |
| Intel Atom              | 1         | 0.35%   |
| AMD Ryzen 5 PRO         | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD C-70                | 1         | 0.35%   |
| AMD Athlon II           | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 157       | 54.51%  |
| 4      | 82        | 28.47%  |
| 8      | 22        | 7.64%   |
| 6      | 16        | 5.56%   |
| 1      | 4         | 1.39%   |
| 14     | 2         | 0.69%   |
| 10     | 2         | 0.69%   |
| 24     | 1         | 0.35%   |
| 16     | 1         | 0.35%   |
| 12     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 287       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 203       | 70.49%  |
| 1      | 85        | 29.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 285       | 99.3%   |
| 32-bit         | 1         | 0.35%   |
| Unknown        | 1         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 38.98%  |
| 0x306a9    | 14        | 4.75%   |
| 0x406e3    | 12        | 4.07%   |
| 0x206a7    | 12        | 4.07%   |
| 0x1067a    | 10        | 3.39%   |
| 0x6fd      | 9         | 3.05%   |
| 0x30678    | 9         | 3.05%   |
| 0x906ea    | 8         | 2.71%   |
| 0x806c1    | 7         | 2.37%   |
| 0x306d4    | 7         | 2.37%   |
| 0x20655    | 7         | 2.37%   |
| 0x40651    | 5         | 1.69%   |
| 0x306c3    | 5         | 1.69%   |
| 0x806ec    | 4         | 1.36%   |
| 0x806ea    | 4         | 1.36%   |
| 0x806e9    | 4         | 1.36%   |
| 0x08108102 | 4         | 1.36%   |
| 0x06001119 | 4         | 1.36%   |
| 0xa0652    | 3         | 1.02%   |
| 0x906e9    | 3         | 1.02%   |
| 0x506e3    | 3         | 1.02%   |
| 0x10676    | 3         | 1.02%   |
| 0x05000119 | 3         | 1.02%   |
| 0x706a8    | 2         | 0.68%   |
| 0x6fa      | 2         | 0.68%   |
| 0x6f6      | 2         | 0.68%   |
| 0x406c3    | 2         | 0.68%   |
| 0x20652    | 2         | 0.68%   |
| 0x0a50000c | 2         | 0.68%   |
| 0x0a404102 | 2         | 0.68%   |
| 0x08600106 | 2         | 0.68%   |
| 0x08600103 | 2         | 0.68%   |
| 0x08108109 | 2         | 0.68%   |
| 0xb06a2    | 1         | 0.34%   |
| 0x906ed    | 1         | 0.34%   |
| 0x906a3    | 1         | 0.34%   |
| 0x806eb    | 1         | 0.34%   |
| 0x806d1    | 1         | 0.34%   |
| 0x706a1    | 1         | 0.34%   |
| 0x6fb      | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 37        | 12.89%  |
| SandyBridge       | 23        | 8.01%   |
| IvyBridge         | 23        | 8.01%   |
| Skylake           | 19        | 6.62%   |
| Core              | 17        | 5.92%   |
| Silvermont        | 16        | 5.57%   |
| Penryn            | 16        | 5.57%   |
| Westmere          | 15        | 5.23%   |
| TigerLake         | 15        | 5.23%   |
| Unknown           | 15        | 5.23%   |
| Haswell           | 14        | 4.88%   |
| Broadwell         | 12        | 4.18%   |
| Zen 2             | 11        | 3.83%   |
| Zen+              | 9         | 3.14%   |
| Zen 3             | 8         | 2.79%   |
| CometLake         | 5         | 1.74%   |
| Alderlake Hybrid  | 5         | 1.74%   |
| Piledriver        | 4         | 1.39%   |
| Goldmont plus     | 3         | 1.05%   |
| Bobcat            | 3         | 1.05%   |
| Puma              | 2         | 0.7%    |
| Meteorlake Hybrid | 2         | 0.7%    |
| K8 Hammer         | 2         | 0.7%    |
| Jaguar            | 2         | 0.7%    |
| Icelake           | 2         | 0.7%    |
| Excavator         | 2         | 0.7%    |
| P6                | 1         | 0.35%   |
| Nehalem           | 1         | 0.35%   |
| Lunarlake Hybrid  | 1         | 0.35%   |
| K10               | 1         | 0.35%   |
| Goldmont          | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 207       | 58.15%  |
| Nvidia | 82        | 23.03%  |
| AMD    | 67        | 18.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 5.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 5.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 4.9%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 14        | 3.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 3.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.72%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 10        | 2.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.18%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 8         | 2.18%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 6         | 1.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.36%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.09%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.09%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 4         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.09%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.09%   |
| AMD Barcelo                                                                              | 4         | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.82%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.82%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.82%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.82%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.82%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 3         | 0.82%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 3         | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.82%   |
| Intel Broadwell-U GT1 [HD Graphics]                                                      | 3         | 0.82%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.82%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 3         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 138       | 48.08%  |
| Intel + Nvidia | 57        | 19.86%  |
| 1 x AMD        | 49        | 17.07%  |
| 1 x Nvidia     | 20        | 6.97%   |
| Intel + AMD    | 9         | 3.14%   |
| 2 x AMD        | 5         | 1.74%   |
| AMD + Nvidia   | 5         | 1.74%   |
| 2 x Intel      | 4         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 245       | 82.77%  |
| Proprietary | 40        | 13.51%  |
| Unknown     | 11        | 3.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 182       | 61.28%  |
| 1.01-2.0   | 44        | 14.81%  |
| 0.01-0.5   | 31        | 10.44%  |
| 0.51-1.0   | 17        | 5.72%   |
| 3.01-4.0   | 16        | 5.39%   |
| 5.01-6.0   | 4         | 1.35%   |
| 7.01-8.0   | 3         | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 70        | 21.74%  |
| LG Display              | 46        | 14.29%  |
| BOE                     | 41        | 12.73%  |
| Samsung Electronics     | 38        | 11.8%   |
| Chimei Innolux          | 37        | 11.49%  |
| Dell                    | 20        | 6.21%   |
| Chi Mei Optoelectronics | 8         | 2.48%   |
| Apple                   | 8         | 2.48%   |
| Goldstar                | 7         | 2.17%   |
| PANDA                   | 6         | 1.86%   |
| Lenovo                  | 6         | 1.86%   |
| BenQ                    | 5         | 1.55%   |
| Sharp                   | 3         | 0.93%   |
| LG Philips              | 3         | 0.93%   |
| InfoVision              | 3         | 0.93%   |
| Acer                    | 3         | 0.93%   |
| Valve                   | 2         | 0.62%   |
| Sony                    | 2         | 0.62%   |
| Seiko/Epson             | 2         | 0.62%   |
| Philips                 | 2         | 0.62%   |
| Hitachi                 | 2         | 0.62%   |
| Xiaomi                  | 1         | 0.31%   |
| Tianma XM               | 1         | 0.31%   |
| Quanta Display          | 1         | 0.31%   |
| Panasonic               | 1         | 0.31%   |
| LGD                     | 1         | 0.31%   |
| IBM                     | 1         | 0.31%   |
| Hewlett-Packard         | 1         | 0.31%   |
| HannStar                | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 1.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.2%    |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 4         | 1.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 1.2%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 3         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.9%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.9%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.9%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 0.9%    |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                      | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.6%    |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch                  | 2         | 0.6%    |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 2         | 0.6%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.6%    |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                       | 2         | 0.6%    |
| Dell P2416D DELA0C3 2560x1440 527x296mm 23.8-inch                        | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch         | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN143F 1920x1200 301x188mm 14.0-inch         | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 2         | 0.6%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.6%    |
| BOE LCD Monitor BOE061D 1366x768 309x173mm 13.9-inch                     | 2         | 0.6%    |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.6%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 2         | 0.6%    |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch           | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 117       | 38.36%  |
| 1366x768 (WXGA)    | 93        | 30.49%  |
| 1600x900 (HD+)     | 16        | 5.25%   |
| 1280x800 (WXGA)    | 16        | 5.25%   |
| 2560x1440 (QHD)    | 10        | 3.28%   |
| 1920x1200 (WUXGA)  | 10        | 3.28%   |
| 3840x2160 (4K)     | 8         | 2.62%   |
| 1440x900 (WXGA+)   | 7         | 2.3%    |
| 2560x1600          | 5         | 1.64%   |
| 1280x1024 (SXGA)   | 4         | 1.31%   |
| 3440x1440          | 3         | 0.98%   |
| 1680x1050 (WSXGA+) | 3         | 0.98%   |
| 800x1280           | 2         | 0.66%   |
| 2880x1800          | 2         | 0.66%   |
| 7680x2160          | 1         | 0.33%   |
| 3840x2400          | 1         | 0.33%   |
| 3840x1080          | 1         | 0.33%   |
| 3456x2160          | 1         | 0.33%   |
| 3000x2000          | 1         | 0.33%   |
| 2160x1440          | 1         | 0.33%   |
| 1360x768           | 1         | 0.33%   |
| 1280x720 (HD)      | 1         | 0.33%   |
| Unknown            | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 153       | 47.08%  |
| 14      | 33        | 10.15%  |
| 13      | 33        | 10.15%  |
| 17      | 22        | 6.77%   |
| 24      | 14        | 4.31%   |
| 12      | 13        | 4%      |
| 27      | 8         | 2.46%   |
| 23      | 6         | 1.85%   |
| 16      | 6         | 1.85%   |
| 21      | 5         | 1.54%   |
| 31      | 4         | 1.23%   |
| 19      | 4         | 1.23%   |
| 11      | 4         | 1.23%   |
| Unknown | 4         | 1.23%   |
| 40      | 3         | 0.92%   |
| 65      | 2         | 0.62%   |
| 35      | 2         | 0.62%   |
| 7       | 2         | 0.62%   |
| 84      | 1         | 0.31%   |
| 48      | 1         | 0.31%   |
| 43      | 1         | 0.31%   |
| 34      | 1         | 0.31%   |
| 25      | 1         | 0.31%   |
| 22      | 1         | 0.31%   |
| 18      | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 203       | 62.85%  |
| 201-300     | 34        | 10.53%  |
| 351-400     | 30        | 9.29%   |
| 501-600     | 27        | 8.36%   |
| 401-500     | 8         | 2.48%   |
| 801-900     | 5         | 1.55%   |
| 601-700     | 4         | 1.24%   |
| Unknown     | 4         | 1.24%   |
| 1001-1500   | 3         | 0.93%   |
| 1-100       | 2         | 0.62%   |
| 701-800     | 1         | 0.31%   |
| 1501-2000   | 1         | 0.31%   |
| 901-1000    | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 230       | 78.77%  |
| 16/10   | 44        | 15.07%  |
| 5/4     | 4         | 1.37%   |
| 3/2     | 4         | 1.37%   |
| Unknown | 4         | 1.37%   |
| 21/9    | 3         | 1.03%   |
| 0.62    | 2         | 0.68%   |
| 32/9    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 151       | 46.6%   |
| 81-90          | 55        | 16.98%  |
| 201-250        | 21        | 6.48%   |
| 121-130        | 21        | 6.48%   |
| 61-70          | 13        | 4.01%   |
| 71-80          | 11        | 3.4%    |
| 301-350        | 8         | 2.47%   |
| 351-500        | 7         | 2.16%   |
| 151-200        | 7         | 2.16%   |
| 501-1000       | 5         | 1.54%   |
| 51-60          | 4         | 1.23%   |
| 111-120        | 4         | 1.23%   |
| Unknown        | 4         | 1.23%   |
| 251-300        | 3         | 0.93%   |
| 91-100         | 3         | 0.93%   |
| More than 1000 | 2         | 0.62%   |
| 1-40           | 2         | 0.62%   |
| 131-140        | 2         | 0.62%   |
| 141-150        | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 127       | 39.44%  |
| 101-120       | 105       | 32.61%  |
| 51-100        | 54        | 16.77%  |
| 161-240       | 23        | 7.14%   |
| More than 240 | 5         | 1.55%   |
| 1-50          | 4         | 1.24%   |
| Unknown       | 4         | 1.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 239       | 81.29%  |
| 2     | 42        | 14.29%  |
| 3     | 6         | 2.04%   |
| 0     | 6         | 2.04%   |
| 4     | 1         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 156       | 33.84%  |
| Intel                      | 142       | 30.8%   |
| Qualcomm Atheros           | 64        | 13.88%  |
| Broadcom                   | 31        | 6.72%   |
| Broadcom Limited           | 11        | 2.39%   |
| MediaTek                   | 9         | 1.95%   |
| Marvell Technology Group   | 7         | 1.52%   |
| Samsung Electronics        | 6         | 1.3%    |
| Ralink                     | 6         | 1.3%    |
| Ralink Technology          | 5         | 1.08%   |
| Lenovo                     | 4         | 0.87%   |
| TP-Link                    | 3         | 0.65%   |
| Qualcomm                   | 3         | 0.65%   |
| Xiaomi                     | 2         | 0.43%   |
| vivo                       | 2         | 0.43%   |
| Nvidia                     | 2         | 0.43%   |
| Huawei Technologies        | 2         | 0.43%   |
| Hewlett-Packard            | 2         | 0.43%   |
| U-Blox                     | 1         | 0.22%   |
| Shenzhen Goodix Technology | 1         | 0.22%   |
| Google                     | 1         | 0.22%   |
| D-Link System              | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 94        | 16.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 6.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 11        | 1.97%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 1.61%   |
| Intel Wireless 8265 / 8275                                             | 9         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 8         | 1.43%   |
| Intel Wireless 8260                                                    | 8         | 1.43%   |
| Intel Wi-Fi 6 AX200                                                    | 8         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.25%   |
| Intel Wireless 3160                                                    | 7         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7         | 1.25%   |
| Intel Wireless 7265                                                    | 6         | 1.07%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 6         | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 6         | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 1.07%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5         | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 5         | 0.89%   |
| Intel Wireless 7260                                                    | 5         | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 0.89%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 0.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 5         | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 4         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 0.72%   |
| Intel Centrino Advanced-N 6200                                         | 4         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 3         | 0.54%   |
| Ralink RT5370 Wireless Adapter                                         | 3         | 0.54%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 3         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 139       | 47.77%  |
| Qualcomm Atheros      | 56        | 19.24%  |
| Realtek Semiconductor | 41        | 14.09%  |
| Broadcom              | 23        | 7.9%    |
| MediaTek              | 8         | 2.75%   |
| Ralink                | 6         | 2.06%   |
| Broadcom Limited      | 6         | 2.06%   |
| Ralink Technology     | 5         | 1.72%   |
| TP-Link               | 3         | 1.03%   |
| Qualcomm              | 3         | 1.03%   |
| D-Link System         | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 12        | 4.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 11        | 3.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 11        | 3.75%   |
| Intel Wi-Fi 6 AX201                                                  | 11        | 3.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10        | 3.41%   |
| Intel Wireless 8265 / 8275                                           | 9         | 3.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 8         | 2.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 8         | 2.73%   |
| Intel Wireless 8260                                                  | 8         | 2.73%   |
| Intel Wi-Fi 6 AX200                                                  | 8         | 2.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 8         | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 2.39%   |
| Intel Wireless 3160                                                  | 7         | 2.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 2.39%   |
| Intel Wireless 7265                                                  | 6         | 2.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 6         | 2.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 6         | 2.05%   |
| Broadcom BCM43142 802.11b/g/n                                        | 6         | 2.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 5         | 1.71%   |
| Intel Wireless 7260                                                  | 5         | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 5         | 1.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 5         | 1.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 4         | 1.37%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4         | 1.37%   |
| Intel Centrino Advanced-N 6200                                       | 4         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 1.37%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 3         | 1.02%   |
| Ralink RT5370 Wireless Adapter                                       | 3         | 1.02%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 3         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 3         | 1.02%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 3         | 1.02%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 3         | 1.02%   |
| Intel WiFi Link 5100                                                 | 3         | 1.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 3         | 1.02%   |
| Intel Ultimate N WiFi Link 5300                                      | 3         | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 1.02%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 145       | 55.34%  |
| Intel                    | 52        | 19.85%  |
| Broadcom                 | 17        | 6.49%   |
| Qualcomm Atheros         | 15        | 5.73%   |
| Marvell Technology Group | 7         | 2.67%   |
| Samsung Electronics      | 6         | 2.29%   |
| Broadcom Limited         | 5         | 1.91%   |
| Lenovo                   | 4         | 1.53%   |
| Xiaomi                   | 2         | 0.76%   |
| vivo                     | 2         | 0.76%   |
| Nvidia                   | 2         | 0.76%   |
| Huawei Technologies      | 2         | 0.76%   |
| MediaTek                 | 1         | 0.38%   |
| Hewlett-Packard          | 1         | 0.38%   |
| Google                   | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 94        | 35.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 14.45%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 4.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 3.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5         | 1.9%    |
| Intel 82577LM Gigabit Network Connection                               | 5         | 1.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 1.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 3         | 1.14%   |
| Intel Ethernet Connection I219-V                                       | 3         | 1.14%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.14%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.76%   |
| vivo 1820                                                              | 2         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.76%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.76%   |
| Lenovo Thinkpad LAN                                                    | 2         | 0.76%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.76%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.76%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 0.76%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 0.76%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                 | 2         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.38%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.38%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.38%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.38%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 279       | 53.14%  |
| Ethernet | 243       | 46.29%  |
| Modem    | 3         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 235       | 79.66%  |
| Ethernet | 60        | 20.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 225       | 78.4%   |
| 1     | 58        | 20.21%  |
| 3     | 2         | 0.7%    |
| 0     | 2         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 266       | 92.04%  |
| Yes  | 23        | 7.96%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 42.79%  |
| Realtek Semiconductor           | 29        | 13.06%  |
| IMC Networks                    | 19        | 8.56%   |
| Qualcomm Atheros Communications | 16        | 7.21%   |
| Lite-On Technology              | 13        | 5.86%   |
| Broadcom                        | 13        | 5.86%   |
| Apple                           | 8         | 3.6%    |
| Dell                            | 6         | 2.7%    |
| Hewlett-Packard                 | 4         | 1.8%    |
| Foxconn / Hon Hai               | 4         | 1.8%    |
| Toshiba                         | 3         | 1.35%   |
| TP-Link                         | 2         | 0.9%    |
| Ralink                          | 2         | 0.9%    |
| Cambridge Silicon Radio         | 2         | 0.9%    |
| USI                             | 1         | 0.45%   |
| Taiyo Yuden                     | 1         | 0.45%   |
| Ralink Technology               | 1         | 0.45%   |
| Qcom                            | 1         | 0.45%   |
| Fujitsu                         | 1         | 0.45%   |
| ASUSTek Computer                | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 14.86%  |
| Intel AX201 Bluetooth                               | 17        | 7.66%   |
| Realtek Bluetooth Radio                             | 16        | 7.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 6.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 3.6%    |
| Intel AX200 Bluetooth                               | 8         | 3.6%    |
| IMC Networks Bluetooth Radio                        | 7         | 3.15%   |
| Apple Bluetooth Host Controller                     | 7         | 3.15%   |
| Intel Bluetooth Device                              | 6         | 2.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.25%   |
| IMC Networks Wireless_Device                        | 5         | 2.25%   |
| Realtek RTL8723B Bluetooth                          | 4         | 1.8%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.8%    |
| Intel AX210 Bluetooth                               | 4         | 1.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.35%   |
| Lite-On Bluetooth Device                            | 3         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.35%   |
| IMC Networks Bluetooth Device                       | 3         | 1.35%   |
| Broadcom BCM2045 Bluetooth                          | 3         | 1.35%   |
| TP-Link TP-T@- UB500 Adapter                        | 2         | 0.9%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.9%    |
| Realtek RTL8821A Bluetooth                          | 2         | 0.9%    |
| Ralink RT3290 Bluetooth                             | 2         | 0.9%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.9%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.9%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.9%    |
| Dell Wireless 355 Bluetooth                         | 2         | 0.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.9%    |
| Broadcom HP Portable SoftSailing                    | 2         | 0.9%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.9%    |
| USI Bluetooth Device                                | 1         | 0.45%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.45%   |
| Toshiba Bluetooth Device                            | 1         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 230       | 64.25%  |
| AMD                   | 59        | 16.48%  |
| Nvidia                | 48        | 13.41%  |
| Logitech              | 4         | 1.12%   |
| C-Media Electronics   | 4         | 1.12%   |
| Lenovo                | 3         | 0.84%   |
| Realtek Semiconductor | 2         | 0.56%   |
| Sony                  | 1         | 0.28%   |
| Razer USA             | 1         | 0.28%   |
| Microsoft             | 1         | 0.28%   |
| GYROCOM C&C           | 1         | 0.28%   |
| GN Netcom             | 1         | 0.28%   |
| Creative Technology   | 1         | 0.28%   |
| Apple                 | 1         | 0.28%   |
| Unknown               | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 34        | 8%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 6.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 5.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 4.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 3.76%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 16        | 3.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 3.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.82%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 2.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.35%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 2.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.88%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.88%   |
| AMD Radeon High Definition Audio Controller                                                       | 8         | 1.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.94%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.94%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.94%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.71%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 3         | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.71%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 56        | 26.42%  |
| SK hynix            | 49        | 23.11%  |
| Unknown             | 29        | 13.68%  |
| Kingston            | 29        | 13.68%  |
| Micron Technology   | 18        | 8.49%   |
| Crucial             | 6         | 2.83%   |
| Ramaxel Technology  | 5         | 2.36%   |
| G.Skill             | 3         | 1.42%   |
| Elpida              | 3         | 1.42%   |
| Corsair             | 2         | 0.94%   |
| A-DATA Technology   | 2         | 0.94%   |
| Unknown             | 2         | 0.94%   |
| Unknown (ABCD)      | 1         | 0.47%   |
| Toshiba             | 1         | 0.47%   |
| PNY                 | 1         | 0.47%   |
| Patriot             | 1         | 0.47%   |
| Nanya Technology    | 1         | 0.47%   |
| INNOVATION PC       | 1         | 0.47%   |
| GOODRAM             | 1         | 0.47%   |
| ASint Technology    | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 2.26%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 4         | 1.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 4         | 1.81%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 4         | 1.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 4         | 1.81%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 4         | 1.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s    | 4         | 1.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 3         | 1.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.36%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s    | 3         | 1.36%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 1.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s              | 2         | 0.9%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 2         | 0.9%    |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s               | 2         | 0.9%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 2         | 0.9%    |
| Unknown RAM Module 2GB SODIMM 533MT/s                    | 2         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 2         | 0.9%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 0.9%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s   | 2         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 2         | 0.9%    |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s | 2         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 0.9%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 0.9%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 2         | 0.9%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 2         | 0.9%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s    | 2         | 0.9%    |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s     | 2         | 0.9%    |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s  | 2         | 0.9%    |
| Unknown                                                  | 2         | 0.9%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s              | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s              | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s               | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s            | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s            | 1         | 0.45%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s             | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s            | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DRAM                       | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s              | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR3                       | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s               | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 38.15%  |
| DDR3    | 64        | 36.99%  |
| DDR2    | 17        | 9.83%   |
| LPDDR5  | 6         | 3.47%   |
| LPDDR4  | 6         | 3.47%   |
| SDRAM   | 4         | 2.31%   |
| DDR5    | 4         | 2.31%   |
| Unknown | 3         | 1.73%   |
| LPDDR3  | 1         | 0.58%   |
| DRAM    | 1         | 0.58%   |
| DDR     | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 92.98%  |
| Row Of Chips | 10        | 5.85%   |
| Chip         | 1         | 0.58%   |
| Unknown      | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 67        | 34.54%  |
| 8192  | 56        | 28.87%  |
| 2048  | 31        | 15.98%  |
| 16384 | 26        | 13.4%   |
| 32768 | 8         | 4.12%   |
| 1024  | 5         | 2.58%   |
| 512   | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 46        | 24.08%  |
| 2667    | 31        | 16.23%  |
| 3200    | 28        | 14.66%  |
| 667     | 12        | 6.28%   |
| 1333    | 11        | 5.76%   |
| 2400    | 9         | 4.71%   |
| 2133    | 8         | 4.19%   |
| 1334    | 8         | 4.19%   |
| 6400    | 4         | 2.09%   |
| 5600    | 4         | 2.09%   |
| 4267    | 3         | 1.57%   |
| 1066    | 3         | 1.57%   |
| 800     | 3         | 1.57%   |
| Unknown | 3         | 1.57%   |
| 8400    | 2         | 1.05%   |
| 2048    | 2         | 1.05%   |
| 1867    | 2         | 1.05%   |
| 1067    | 2         | 1.05%   |
| 533     | 2         | 1.05%   |
| 8533    | 1         | 0.52%   |
| 7467    | 1         | 0.52%   |
| 4199    | 1         | 0.52%   |
| 3266    | 1         | 0.52%   |
| 2933    | 1         | 0.52%   |
| 1639    | 1         | 0.52%   |
| 975     | 1         | 0.52%   |
| 200     | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 60%     |
| Samsung Electronics | 2         | 40%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet 1018         | 2         | 40%     |
| Samsung SCX-4100 Scanner | 1         | 20%     |
| Samsung SCX-3200 Series  | 1         | 20%     |
| HP LaserJet P1102        | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 64        | 26.34%  |
| IMC Networks                           | 26        | 10.7%   |
| Realtek Semiconductor                  | 23        | 9.47%   |
| Microdia                               | 16        | 6.58%   |
| Bison Electronics                      | 16        | 6.58%   |
| Suyin                                  | 12        | 4.94%   |
| Sunplus Innovation Technology          | 12        | 4.94%   |
| Quanta                                 | 12        | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.29%   |
| Syntek                                 | 7         | 2.88%   |
| Lite-On Technology                     | 7         | 2.88%   |
| Apple                                  | 7         | 2.88%   |
| Luxvisions Innotech Limited            | 6         | 2.47%   |
| Shinetech                              | 4         | 1.65%   |
| Silicon Motion                         | 3         | 1.23%   |
| Ricoh                                  | 3         | 1.23%   |
| Lenovo                                 | 3         | 1.23%   |
| Z-Star Microelectronics                | 2         | 0.82%   |
| Sonix Technology                       | 1         | 0.41%   |
| Samsung Electronics                    | 1         | 0.41%   |
| Primax Electronics                     | 1         | 0.41%   |
| OmniVision Technologies                | 1         | 0.41%   |
| Microsoft                              | 1         | 0.41%   |
| icSpring                               | 1         | 0.41%   |
| Genesys Logic                          | 1         | 0.41%   |
| DigiTech                               | 1         | 0.41%   |
| Arkmicro Technologies                  | 1         | 0.41%   |
| ALi                                    | 1         | 0.41%   |
| Alcor Micro                            | 1         | 0.41%   |
| Acer                                   | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 12        | 4.86%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 8         | 3.24%   |
| IMC Networks Integrated Camera                              | 7         | 2.83%   |
| Realtek Integrated_Webcam_HD                                | 6         | 2.43%   |
| Microdia Integrated_Webcam_HD                               | 5         | 2.02%   |
| Lite-On Integrated Camera                                   | 5         | 2.02%   |
| Chicony Integrated Camera (1280x720@30)                     | 5         | 2.02%   |
| Chicony HD WebCam                                           | 5         | 2.02%   |
| Bison Lenovo EasyCamera                                     | 5         | 2.02%   |
| Sunplus Asus Webcam                                         | 4         | 1.62%   |
| Realtek USB Camera                                          | 4         | 1.62%   |
| Microdia Integrated Webcam                                  | 4         | 1.62%   |
| Chicony USB2.0 VGA UVC WebCam                               | 4         | 1.62%   |
| Chicony USB2.0 HD UVC WebCam                                | 4         | 1.62%   |
| Chicony HP Truevision HD camera                             | 4         | 1.62%   |
| Chicony HP HD Camera                                        | 4         | 1.62%   |
| Chicony HD User Facing                                      | 4         | 1.62%   |
| Syntek Integrated Camera                                    | 3         | 1.21%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.21%   |
| ShineTech USB2.0 HD UVC WebCam                              | 3         | 1.21%   |
| Realtek Integrated Webcam                                   | 3         | 1.21%   |
| Realtek HP Webcam                                           | 3         | 1.21%   |
| Chicony CNF9055 Toshiba Webcam                              | 3         | 1.21%   |
| Apple FaceTime HD Camera                                    | 3         | 1.21%   |
| Suyin HD WebCam                                             | 2         | 0.81%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.81%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 0.81%   |
| Ricoh Integrated Webcam                                     | 2         | 0.81%   |
| Quanta Laptop_Integrated_Webcam_2HDM                        | 2         | 0.81%   |
| Quanta HD Webcam                                            | 2         | 0.81%   |
| Microdia Lenovo EasyCamera                                  | 2         | 0.81%   |
| Luxvisions Innotech Limited Integrated RGB Camera           | 2         | 0.81%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 0.81%   |
| Lenovo Integrated Webcam                                    | 2         | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 0.81%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 0.81%   |
| IMC Networks Lenovo EasyCamera                              | 2         | 0.81%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 0.81%   |
| Chicony HP Webcam                                           | 2         | 0.81%   |
| Chicony HP HD Webcam                                        | 2         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 40%     |
| Synaptics                  | 14        | 28%     |
| AuthenTec                  | 5         | 10%     |
| Upek                       | 4         | 8%      |
| STMicroelectronics         | 2         | 4%      |
| Shenzhen Goodix Technology | 2         | 4%      |
| Elan Microelectronics      | 2         | 4%      |
| LighTuning Technology      | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 8%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 8%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 6%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 6%      |
| Validity Sensors VFS491                                                    | 2         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 2         | 4%      |
| Synaptics UWP WBDI Device                                                  | 2         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4%      |
| STMicroelectronics Fingerprint Reader                                      | 2         | 4%      |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 4%      |
| Elan ELAN:Fingerprint                                                      | 2         | 4%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2%      |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2%      |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2%      |
| AuthenTec AES1600                                                          | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 17        | 54.84%  |
| Broadcom    | 10        | 32.26%  |
| Lenovo      | 2         | 6.45%   |
| Upek        | 1         | 3.23%   |
| O2 Micro    | 1         | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                         | 17        | 54.84%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 4         | 12.9%   |
| Broadcom BCM5880 Secure Applications Processor                              | 3         | 9.68%   |
| Lenovo Integrated Smart Card Reader                                         | 2         | 6.45%   |
| Broadcom 58200                                                              | 2         | 6.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                  | 1         | 3.23%   |
| O2 Micro OZ776 CCID Smartcard Reader                                        | 1         | 3.23%   |
| Broadcom 5880                                                               | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 173       | 58.45%  |
| 1     | 90        | 30.41%  |
| 2     | 29        | 9.8%    |
| 3     | 3         | 1.01%   |
| 4     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 32.03%  |
| Graphics card            | 38        | 24.84%  |
| Chipcard                 | 25        | 16.34%  |
| Net/wireless             | 14        | 9.15%   |
| Multimedia controller    | 11        | 7.19%   |
| Camera                   | 6         | 3.92%   |
| Communication controller | 3         | 1.96%   |
| Storage                  | 2         | 1.31%   |
| Card reader              | 2         | 1.31%   |
| Bluetooth                | 2         | 1.31%   |
| Net/ethernet             | 1         | 0.65%   |

