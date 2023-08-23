Linux in Brazil - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 11620

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | 300E5M/300E5L               | [9aa2cd7b81](https://linux-hardware.org/?probe=9aa2cd7b81) | Aug 12, 2023 |
| Notebook      | NJx0MU                      | [6f230d02c1](https://linux-hardware.org/?probe=6f230d02c1) | Aug 12, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | [1b7c441369](https://linux-hardware.org/?probe=1b7c441369) | Aug 12, 2023 |
| Multilaser    | PC024                       | [3311e26ac5](https://linux-hardware.org/?probe=3311e26ac5) | Aug 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [53196a01fa](https://linux-hardware.org/?probe=53196a01fa) | Aug 12, 2023 |
| Dell          | Inspiron 5558               | [5bb31ccda3](https://linux-hardware.org/?probe=5bb31ccda3) | Aug 12, 2023 |
| Dell          | G3 3579                     | [09ba53e3c1](https://linux-hardware.org/?probe=09ba53e3c1) | Aug 12, 2023 |
| Acer          | Aspire F5-573G              | [019f3a6d1f](https://linux-hardware.org/?probe=019f3a6d1f) | Aug 11, 2023 |
| Acer          | Nitro AN517-54              | [4daff2c43f](https://linux-hardware.org/?probe=4daff2c43f) | Aug 11, 2023 |
| Unknown       | Unknown                     | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| Dell          | G15 5520                    | [3bec284af8](https://linux-hardware.org/?probe=3bec284af8) | Aug 11, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [83879b8247](https://linux-hardware.org/?probe=83879b8247) | Aug 11, 2023 |
| Notebook      | NJx0MU                      | [ea4ae0e0f3](https://linux-hardware.org/?probe=ea4ae0e0f3) | Aug 11, 2023 |
| Acer          | Aspire A515-51              | [4856b9b32f](https://linux-hardware.org/?probe=4856b9b32f) | Aug 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [97e0c46487](https://linux-hardware.org/?probe=97e0c46487) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| Notebook      | NJx0MU                      | [2db90ee24e](https://linux-hardware.org/?probe=2db90ee24e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [30748e95eb](https://linux-hardware.org/?probe=30748e95eb) | Aug 11, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7fe6adce5e](https://linux-hardware.org/?probe=7fe6adce5e) | Aug 10, 2023 |
| Acer          | Aspire E5-571G              | [6c55de5ac8](https://linux-hardware.org/?probe=6c55de5ac8) | Aug 10, 2023 |
| Avell High... | A70 HYB                     | [9b03ae1cd3](https://linux-hardware.org/?probe=9b03ae1cd3) | Aug 10, 2023 |
| HP            | Folio 13                    | [67121fc711](https://linux-hardware.org/?probe=67121fc711) | Aug 10, 2023 |
| Avell         | A70 ION                     | [6ab02a34e4](https://linux-hardware.org/?probe=6ab02a34e4) | Aug 10, 2023 |
| Avell         | A70 ION                     | [b71c176ce3](https://linux-hardware.org/?probe=b71c176ce3) | Aug 10, 2023 |
| Acer          | Nitro AN517-51              | [bd3b7989f0](https://linux-hardware.org/?probe=bd3b7989f0) | Aug 10, 2023 |
| Dell          | Vostro 3501                 | [d606f83745](https://linux-hardware.org/?probe=d606f83745) | Aug 10, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [4446f503d5](https://linux-hardware.org/?probe=4446f503d5) | Aug 10, 2023 |
| Positivo      | Presley 3                   | [16ddbd1a75](https://linux-hardware.org/?probe=16ddbd1a75) | Aug 10, 2023 |
| HP            | Folio 13                    | [889aae1772](https://linux-hardware.org/?probe=889aae1772) | Aug 10, 2023 |
| Positivo      | Presley 3                   | [9edde2ea30](https://linux-hardware.org/?probe=9edde2ea30) | Aug 09, 2023 |
| ASRock        | H81M-HG4 R4.0               | [26c322239f](https://linux-hardware.org/?probe=26c322239f) | Aug 09, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | [4bd13ae71d](https://linux-hardware.org/?probe=4bd13ae71d) | Aug 09, 2023 |
| Acer          | Aspire A515-54G             | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Dell          | Inspiron 15 3515            | [7ce5fc846b](https://linux-hardware.org/?probe=7ce5fc846b) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| Dell          | Inspiron 15 3511            | [13cec81a99](https://linux-hardware.org/?probe=13cec81a99) | Aug 08, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d6b7da58e7](https://linux-hardware.org/?probe=d6b7da58e7) | Aug 08, 2023 |
| Acer          | Aspire A515-51G             | [1105c8c2ea](https://linux-hardware.org/?probe=1105c8c2ea) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [dd127ca2df](https://linux-hardware.org/?probe=dd127ca2df) | Aug 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | [788c24d04a](https://linux-hardware.org/?probe=788c24d04a) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ec7a911951](https://linux-hardware.org/?probe=ec7a911951) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| Acer          | Aspire E5-553G              | [f7845429c8](https://linux-hardware.org/?probe=f7845429c8) | Aug 07, 2023 |
| Acer          | Nitro AN517-52              | [d24385ceb8](https://linux-hardware.org/?probe=d24385ceb8) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| HP            | 250 G6 Notebook PC          | [c130dece41](https://linux-hardware.org/?probe=c130dece41) | Aug 06, 2023 |
| Dell          | Inspiron 5547               | [8f33c0cf28](https://linux-hardware.org/?probe=8f33c0cf28) | Aug 06, 2023 |
| Notebook      | 1745                        | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| Dell          | Inspiron 15-3567            | [2e8d48f9bc](https://linux-hardware.org/?probe=2e8d48f9bc) | Aug 06, 2023 |
| HP            | Pavilion dm4                | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [52b9918d42](https://linux-hardware.org/?probe=52b9918d42) | Aug 06, 2023 |
| Dell          | Inspiron N4050              | [af35c9ce49](https://linux-hardware.org/?probe=af35c9ce49) | Aug 05, 2023 |
| Acer          | Aspire E5-553G              | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6de5534e97](https://linux-hardware.org/?probe=6de5534e97) | Aug 05, 2023 |
| Dell          | Latitude 5410               | [2838e5d74c](https://linux-hardware.org/?probe=2838e5d74c) | Aug 05, 2023 |
| Dell          | Latitude E5440              | [f6981c56b7](https://linux-hardware.org/?probe=f6981c56b7) | Aug 05, 2023 |
| Multilaser    | PC024                       | [85a4bdd497](https://linux-hardware.org/?probe=85a4bdd497) | Aug 05, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [f03fa524d7](https://linux-hardware.org/?probe=f03fa524d7) | Aug 05, 2023 |
| Multilaser    | PC13X                       | [2f79cffddd](https://linux-hardware.org/?probe=2f79cffddd) | Aug 05, 2023 |
| HP            | Pavilion g4                 | [2094186715](https://linux-hardware.org/?probe=2094186715) | Aug 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [24a5183e69](https://linux-hardware.org/?probe=24a5183e69) | Aug 05, 2023 |
| Dell          | G15 5520                    | [baca0d14f5](https://linux-hardware.org/?probe=baca0d14f5) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8292d9f518](https://linux-hardware.org/?probe=8292d9f518) | Aug 04, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | [8b6b5ff142](https://linux-hardware.org/?probe=8b6b5ff142) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Acer          | Nitro AN517-54              | [aee5a21c76](https://linux-hardware.org/?probe=aee5a21c76) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | [bd88b4e8fa](https://linux-hardware.org/?probe=bd88b4e8fa) | Aug 04, 2023 |
| ASUSTek       | UX490UAR                    | [6a305978e3](https://linux-hardware.org/?probe=6a305978e3) | Aug 03, 2023 |
| Dell          | Inspiron 5566               | [21d7f13381](https://linux-hardware.org/?probe=21d7f13381) | Aug 03, 2023 |
| Lenovo        | ThinkPad Edge E431 6277C... | [6c542a6490](https://linux-hardware.org/?probe=6c542a6490) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | [25dcc9a7c5](https://linux-hardware.org/?probe=25dcc9a7c5) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [67d851300e](https://linux-hardware.org/?probe=67d851300e) | Aug 03, 2023 |
| Positivo      | Q232B                       | [006d77a18c](https://linux-hardware.org/?probe=006d77a18c) | Aug 02, 2023 |
| Acer          | Aspire E1-572               | [af04d8d764](https://linux-hardware.org/?probe=af04d8d764) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Dell          | Inspiron 5566               | [c4e404738e](https://linux-hardware.org/?probe=c4e404738e) | Aug 01, 2023 |
| Apple         | MacBookPro8,1               | [56e2fa207e](https://linux-hardware.org/?probe=56e2fa207e) | Aug 01, 2023 |
| Itautec       | Infoway a7420               | [da7459a0ea](https://linux-hardware.org/?probe=da7459a0ea) | Aug 01, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [1f69ed5c1e](https://linux-hardware.org/?probe=1f69ed5c1e) | Aug 01, 2023 |
| HP            | Pavilion 14                 | [313aedd888](https://linux-hardware.org/?probe=313aedd888) | Jul 31, 2023 |
| Acer          | Aspire V3-571               | [9b9830aedf](https://linux-hardware.org/?probe=9b9830aedf) | Jul 31, 2023 |
| Dell          | Inspiron 7520               | [b87690f890](https://linux-hardware.org/?probe=b87690f890) | Jul 31, 2023 |
| Dell          | Latitude E5510              | [b9208e8c08](https://linux-hardware.org/?probe=b9208e8c08) | Jul 31, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | [8e49dde20d](https://linux-hardware.org/?probe=8e49dde20d) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | [8d6d8b9243](https://linux-hardware.org/?probe=8d6d8b9243) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | [13e9f3fa3c](https://linux-hardware.org/?probe=13e9f3fa3c) | Jul 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | [9268d1c4f9](https://linux-hardware.org/?probe=9268d1c4f9) | Jul 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Acer          | Aspire A315-53              | [28ff56233b](https://linux-hardware.org/?probe=28ff56233b) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [f3de23350d](https://linux-hardware.org/?probe=f3de23350d) | Jul 30, 2023 |
| Dell          | Inspiron 5547               | [3be466c09c](https://linux-hardware.org/?probe=3be466c09c) | Jul 30, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [2a0777f1fd](https://linux-hardware.org/?probe=2a0777f1fd) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | [24c271e6fd](https://linux-hardware.org/?probe=24c271e6fd) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | [bb2245d195](https://linux-hardware.org/?probe=bb2245d195) | Jul 30, 2023 |
| Dell          | Inspiron 5577               | [10b634ac99](https://linux-hardware.org/?probe=10b634ac99) | Jul 29, 2023 |
| Acer          | Nitro AN515-52              | [393c4b7fd3](https://linux-hardware.org/?probe=393c4b7fd3) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| HP            | Folio 13                    | [baaa648a4b](https://linux-hardware.org/?probe=baaa648a4b) | Jul 29, 2023 |
| Lenovo        | Unknown                     | [a1dac68b95](https://linux-hardware.org/?probe=a1dac68b95) | Jul 29, 2023 |
| Samsung       | 550XDA                      | [c140c9176e](https://linux-hardware.org/?probe=c140c9176e) | Jul 29, 2023 |
| Dell          | Inspiron N4050              | [701402e2a7](https://linux-hardware.org/?probe=701402e2a7) | Jul 29, 2023 |
| HP            | 250 G8 Notebook PC          | [502747dd18](https://linux-hardware.org/?probe=502747dd18) | Jul 29, 2023 |
| Dell          | Latitude 5400               | [9416ce803c](https://linux-hardware.org/?probe=9416ce803c) | Jul 28, 2023 |
| Dell          | Inspiron 7520               | [7509644961](https://linux-hardware.org/?probe=7509644961) | Jul 28, 2023 |
| Acer          | Aspire 5350                 | [698672b19c](https://linux-hardware.org/?probe=698672b19c) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [8ca0357bf1](https://linux-hardware.org/?probe=8ca0357bf1) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [bca814cbb5](https://linux-hardware.org/?probe=bca814cbb5) | Jul 28, 2023 |
| Acer          | Aspire A515-45              | [6287e66ff2](https://linux-hardware.org/?probe=6287e66ff2) | Jul 27, 2023 |
| HP            | EliteBook 8540w             | [d91f2ff8ba](https://linux-hardware.org/?probe=d91f2ff8ba) | Jul 27, 2023 |
| A14CR         | Unknown                     | [4ceb4f6761](https://linux-hardware.org/?probe=4ceb4f6761) | Jul 27, 2023 |
| Compaq        | PRESARIOCQ18                | [c528c90b50](https://linux-hardware.org/?probe=c528c90b50) | Jul 27, 2023 |
| Biostar       | B450MHP                     | [bb12598429](https://linux-hardware.org/?probe=bb12598429) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| Multilaser    | PC024                       | [fa5b5a3146](https://linux-hardware.org/?probe=fa5b5a3146) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| HP            | Folio 13                    | [a3269c0930](https://linux-hardware.org/?probe=a3269c0930) | Jul 26, 2023 |
| HP            | Pavilion 11 x360 PC         | [8daa291377](https://linux-hardware.org/?probe=8daa291377) | Jul 26, 2023 |
| Dell          | G3 3579                     | [b6b50ffa46](https://linux-hardware.org/?probe=b6b50ffa46) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | [2e810b1c93](https://linux-hardware.org/?probe=2e810b1c93) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | [4171fc8925](https://linux-hardware.org/?probe=4171fc8925) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| HP            | ProBook 640 G2              | [f6400e37f6](https://linux-hardware.org/?probe=f6400e37f6) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| HP            | ProBook 640 G2              | [7814bf14ac](https://linux-hardware.org/?probe=7814bf14ac) | Jul 26, 2023 |
| Valve         | Jupiter                     | [8ba9103155](https://linux-hardware.org/?probe=8ba9103155) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [9878121979](https://linux-hardware.org/?probe=9878121979) | Jul 26, 2023 |
| Notebook      | NJx0MU                      | [f720b1a032](https://linux-hardware.org/?probe=f720b1a032) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6c978ec74d](https://linux-hardware.org/?probe=6c978ec74d) | Jul 26, 2023 |
| Dell          | Inspiron 3501               | [62bcc903fd](https://linux-hardware.org/?probe=62bcc903fd) | Jul 25, 2023 |
| Acer          | Aspire A514-54              | [787270abee](https://linux-hardware.org/?probe=787270abee) | Jul 25, 2023 |
| Acer          | Aspire E5-571G              | [3f39162908](https://linux-hardware.org/?probe=3f39162908) | Jul 25, 2023 |
| Dell          | Inspiron 5548               | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| Positivo      | S14SL01                     | [7ee0f7e8d1](https://linux-hardware.org/?probe=7ee0f7e8d1) | Jul 25, 2023 |
| Compaq        | Presario CQ-23              | [b78363eeaf](https://linux-hardware.org/?probe=b78363eeaf) | Jul 25, 2023 |
| Toshiba       | IS 1442                     | [3a66df4c2d](https://linux-hardware.org/?probe=3a66df4c2d) | Jul 25, 2023 |
| Notebook      | NJx0MU                      | [c675a3feab](https://linux-hardware.org/?probe=c675a3feab) | Jul 25, 2023 |
| Dell          | Latitude 3420               | [18d920dab2](https://linux-hardware.org/?probe=18d920dab2) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f1844a5f28](https://linux-hardware.org/?probe=f1844a5f28) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | [ae6caf81d7](https://linux-hardware.org/?probe=ae6caf81d7) | Jul 24, 2023 |
| OEM           | Unknown                     | [d0d59fb363](https://linux-hardware.org/?probe=d0d59fb363) | Jul 24, 2023 |
| Acer          | Aspire A515-45              | [e1de4fabc7](https://linux-hardware.org/?probe=e1de4fabc7) | Jul 24, 2023 |
| Dell          | G15 5510                    | [18ceaecd85](https://linux-hardware.org/?probe=18ceaecd85) | Jul 24, 2023 |
| LG Electro... | R490-G.BR51P1               | [eecedbc045](https://linux-hardware.org/?probe=eecedbc045) | Jul 24, 2023 |
| Dell          | Inspiron 13-5378            | [7f6b8fc2db](https://linux-hardware.org/?probe=7f6b8fc2db) | Jul 23, 2023 |
| OEM           | Unknown                     | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| HP            | EliteBook 2530p             | [3733be1f95](https://linux-hardware.org/?probe=3733be1f95) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [808ae8a334](https://linux-hardware.org/?probe=808ae8a334) | Jul 22, 2023 |
| Sony          | SVF15213CBB                 | [569ed328f7](https://linux-hardware.org/?probe=569ed328f7) | Jul 22, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [c361b3b1ac](https://linux-hardware.org/?probe=c361b3b1ac) | Jul 22, 2023 |
| Samsung       | 550XDA                      | [c298263c6c](https://linux-hardware.org/?probe=c298263c6c) | Jul 22, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [a9af1efc27](https://linux-hardware.org/?probe=a9af1efc27) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [031d46c9d0](https://linux-hardware.org/?probe=031d46c9d0) | Jul 21, 2023 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [fc45e9b064](https://linux-hardware.org/?probe=fc45e9b064) | Jul 21, 2023 |
| Avell High... | B.ON                        | [8269a683ef](https://linux-hardware.org/?probe=8269a683ef) | Jul 21, 2023 |
| LG Electro... | S425-G.BC31P1               | [2f54821f3f](https://linux-hardware.org/?probe=2f54821f3f) | Jul 21, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [2269e1f3d7](https://linux-hardware.org/?probe=2269e1f3d7) | Jul 21, 2023 |
| Dell          | Latitude 5290               | [66860827b9](https://linux-hardware.org/?probe=66860827b9) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| Dell          | Inspiron 15 5510            | [df2bfbf3e1](https://linux-hardware.org/?probe=df2bfbf3e1) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [c7e1f17f9e](https://linux-hardware.org/?probe=c7e1f17f9e) | Jul 20, 2023 |
| Alienware     | m15 R6                      | [93d5e98358](https://linux-hardware.org/?probe=93d5e98358) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [9b44d7bd03](https://linux-hardware.org/?probe=9b44d7bd03) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [da1ea699ed](https://linux-hardware.org/?probe=da1ea699ed) | Jul 19, 2023 |
| Gateway       | NV55C                       | [a87e93c2a7](https://linux-hardware.org/?probe=a87e93c2a7) | Jul 19, 2023 |
| Unknown       | Unknown                     | [7ff33d80d7](https://linux-hardware.org/?probe=7ff33d80d7) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | [cdad3aa931](https://linux-hardware.org/?probe=cdad3aa931) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bddb3e26c1](https://linux-hardware.org/?probe=bddb3e26c1) | Jul 19, 2023 |
| Avell High... | B.ON                        | [bf1f683383](https://linux-hardware.org/?probe=bf1f683383) | Jul 18, 2023 |
| LG Electro... | P420-G.BE42P1               | [9dea573574](https://linux-hardware.org/?probe=9dea573574) | Jul 18, 2023 |
| Positivo      | N4340                       | [fdcc9c264b](https://linux-hardware.org/?probe=fdcc9c264b) | Jul 18, 2023 |
| Positivo      | N4340                       | [1a7db9f33d](https://linux-hardware.org/?probe=1a7db9f33d) | Jul 18, 2023 |
| Positivo      | W942SW_SW1                  | [f8f65185cd](https://linux-hardware.org/?probe=f8f65185cd) | Jul 18, 2023 |
| Positivo      | Mobile                      | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [4cdb03ec24](https://linux-hardware.org/?probe=4cdb03ec24) | Jul 18, 2023 |
| Multilaser    | PC024                       | [b1220586b0](https://linux-hardware.org/?probe=b1220586b0) | Jul 18, 2023 |
| Acer          | Aspire A515-51G             | [0236d26da7](https://linux-hardware.org/?probe=0236d26da7) | Jul 17, 2023 |
| Multilaser    | PC024                       | [04c0168bce](https://linux-hardware.org/?probe=04c0168bce) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [86f515ebce](https://linux-hardware.org/?probe=86f515ebce) | Jul 17, 2023 |
| Multilaser    | PC204                       | [35e4b7c5c9](https://linux-hardware.org/?probe=35e4b7c5c9) | Jul 17, 2023 |
| Unknown       | TU-142                      | [d62ade82c2](https://linux-hardware.org/?probe=d62ade82c2) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4abe81669a](https://linux-hardware.org/?probe=4abe81669a) | Jul 17, 2023 |
| LG Electro... | A410-G.BC48P1               | [947acba673](https://linux-hardware.org/?probe=947acba673) | Jul 17, 2023 |
| Digibras      | NH4CU53                     | [14efcb6869](https://linux-hardware.org/?probe=14efcb6869) | Jul 17, 2023 |
| Acer          | Aspire A315-23G             | [df26ae3dab](https://linux-hardware.org/?probe=df26ae3dab) | Jul 17, 2023 |
| Acer          | Aspire 5920                 | [f574cf0363](https://linux-hardware.org/?probe=f574cf0363) | Jul 16, 2023 |
| Intel         | powered classmate PC        | [fc6b28eb14](https://linux-hardware.org/?probe=fc6b28eb14) | Jul 16, 2023 |
| Dell          | G15 5520                    | [ed22e67151](https://linux-hardware.org/?probe=ed22e67151) | Jul 16, 2023 |
| Compaq        | 420                         | [e5b8695df7](https://linux-hardware.org/?probe=e5b8695df7) | Jul 16, 2023 |
| Dell          | Vostro 5470                 | [0e3bc07183](https://linux-hardware.org/?probe=0e3bc07183) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [7278a4ed50](https://linux-hardware.org/?probe=7278a4ed50) | Jul 16, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46cfd28279](https://linux-hardware.org/?probe=46cfd28279) | Jul 16, 2023 |
| Acer          | Aspire 5750                 | [e46208d592](https://linux-hardware.org/?probe=e46208d592) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [45c881b739](https://linux-hardware.org/?probe=45c881b739) | Jul 16, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [9b0f9e2480](https://linux-hardware.org/?probe=9b0f9e2480) | Jul 16, 2023 |
| Dell          | Inspiron 3442               | [4767e5dc31](https://linux-hardware.org/?probe=4767e5dc31) | Jul 15, 2023 |
| Acer          | Aspire A515-41G             | [a9cb1108f6](https://linux-hardware.org/?probe=a9cb1108f6) | Jul 15, 2023 |
| HP            | ProBook 640 G1              | [d7512ceea8](https://linux-hardware.org/?probe=d7512ceea8) | Jul 15, 2023 |
| Positivo      | Mobile                      | [fdc2d91a25](https://linux-hardware.org/?probe=fdc2d91a25) | Jul 15, 2023 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [804b227bff](https://linux-hardware.org/?probe=804b227bff) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c9cc25539e](https://linux-hardware.org/?probe=c9cc25539e) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [5fe3ea6d25](https://linux-hardware.org/?probe=5fe3ea6d25) | Jul 15, 2023 |
| Samsung       | 300E5K/300E5Q               | [92bd2944cb](https://linux-hardware.org/?probe=92bd2944cb) | Jul 15, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | [dd92f9ce05](https://linux-hardware.org/?probe=dd92f9ce05) | Jul 14, 2023 |
| Alienware     | m15 R7                      | [99e796a389](https://linux-hardware.org/?probe=99e796a389) | Jul 14, 2023 |
| Alienware     | m15 R7                      | [e80cfeb390](https://linux-hardware.org/?probe=e80cfeb390) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S4NR00    | [281c5a429c](https://linux-hardware.org/?probe=281c5a429c) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [29a9ad60a6](https://linux-hardware.org/?probe=29a9ad60a6) | Jul 13, 2023 |
| Dell          | Inspiron 1525               | [d63b2efc8b](https://linux-hardware.org/?probe=d63b2efc8b) | Jul 13, 2023 |
| Acer          | Nitro AN515-45              | [c347746634](https://linux-hardware.org/?probe=c347746634) | Jul 13, 2023 |
| Apple         | MacBookPro10,1              | [adad96c487](https://linux-hardware.org/?probe=adad96c487) | Jul 13, 2023 |
| HP            | EliteBook 8440p             | [f7a66609af](https://linux-hardware.org/?probe=f7a66609af) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [56b110f152](https://linux-hardware.org/?probe=56b110f152) | Jul 13, 2023 |
| Dell          | Inspiron 5458               | [4760e0c113](https://linux-hardware.org/?probe=4760e0c113) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | [ad9fd505fa](https://linux-hardware.org/?probe=ad9fd505fa) | Jul 13, 2023 |
| Positivo      | A14CR6A                     | [7ad49c61bd](https://linux-hardware.org/?probe=7ad49c61bd) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [392b02a797](https://linux-hardware.org/?probe=392b02a797) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| HP            | Compaq Presario CQ40        | [fbc602a7b6](https://linux-hardware.org/?probe=fbc602a7b6) | Jul 12, 2023 |
| Positivo      | Mobile                      | [463636c0a2](https://linux-hardware.org/?probe=463636c0a2) | Jul 12, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [480fe73577](https://linux-hardware.org/?probe=480fe73577) | Jul 12, 2023 |
| Positivo      | Donatello                   | [c9740822e6](https://linux-hardware.org/?probe=c9740822e6) | Jul 12, 2023 |
| Acer          | Aspire A515-54              | [64e1f03cea](https://linux-hardware.org/?probe=64e1f03cea) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8980149c48](https://linux-hardware.org/?probe=8980149c48) | Jul 11, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [e688a998bc](https://linux-hardware.org/?probe=e688a998bc) | Jul 11, 2023 |
| HP            | Folio 13                    | [864b74d611](https://linux-hardware.org/?probe=864b74d611) | Jul 11, 2023 |
| Dell          | Inspiron 7520               | [154a4104b1](https://linux-hardware.org/?probe=154a4104b1) | Jul 11, 2023 |
| Dell          | Inspiron 7560               | [a761bfffd2](https://linux-hardware.org/?probe=a761bfffd2) | Jul 11, 2023 |
| HP            | Folio 13                    | [35d5a3c2a3](https://linux-hardware.org/?probe=35d5a3c2a3) | Jul 11, 2023 |
| Dell          | Latitude E5410              | [8d980136c2](https://linux-hardware.org/?probe=8d980136c2) | Jul 10, 2023 |
| Acer          | Aspire A315-23              | [b5a021ae8a](https://linux-hardware.org/?probe=b5a021ae8a) | Jul 10, 2023 |
| Avell High... | A52 LIV                     | [eeee2d0bf9](https://linux-hardware.org/?probe=eeee2d0bf9) | Jul 10, 2023 |
| Dell          | Latitude 3490               | [6fcb4ace67](https://linux-hardware.org/?probe=6fcb4ace67) | Jul 10, 2023 |
| Compaq        | 420                         | [6f4350d53e](https://linux-hardware.org/?probe=6f4350d53e) | Jul 10, 2023 |
| Acer          | Nitro AN515-43              | [b463aaca78](https://linux-hardware.org/?probe=b463aaca78) | Jul 10, 2023 |
| Dell          | Inspiron 3521               | [49c5ec535d](https://linux-hardware.org/?probe=49c5ec535d) | Jul 09, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [ccc541ee78](https://linux-hardware.org/?probe=ccc541ee78) | Jul 09, 2023 |
| Samsung       | 950XDB/951XDB/950XDY        | [5e41313f45](https://linux-hardware.org/?probe=5e41313f45) | Jul 09, 2023 |
| Dell          | Inspiron 5566               | [afc295d4b4](https://linux-hardware.org/?probe=afc295d4b4) | Jul 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [065b0237d3](https://linux-hardware.org/?probe=065b0237d3) | Jul 09, 2023 |
| Notebook      | NJx0MU                      | [cc7487e50f](https://linux-hardware.org/?probe=cc7487e50f) | Jul 09, 2023 |
| Dell          | Latitude 5400               | [e8b701bf4e](https://linux-hardware.org/?probe=e8b701bf4e) | Jul 09, 2023 |
| Acer          | Predator G3-572             | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| HP            | G42                         | [e215b464bf](https://linux-hardware.org/?probe=e215b464bf) | Jul 09, 2023 |
| HP            | ProBook 6460b               | [af3006237f](https://linux-hardware.org/?probe=af3006237f) | Jul 09, 2023 |
| HP            | Pavilion dm3                | [a1bc8d5217](https://linux-hardware.org/?probe=a1bc8d5217) | Jul 09, 2023 |
| Notebook      | NJx0MU                      | [502c216e98](https://linux-hardware.org/?probe=502c216e98) | Jul 08, 2023 |
| Multilaser    | MLSH1H LINUX                | [e699ffe719](https://linux-hardware.org/?probe=e699ffe719) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Dell          | Inspiron 13-5378            | [8337bfbb61](https://linux-hardware.org/?probe=8337bfbb61) | Jul 08, 2023 |
| HP            | 14                          | [71d49b008d](https://linux-hardware.org/?probe=71d49b008d) | Jul 08, 2023 |
| HP            | 14                          | [ba511c29ac](https://linux-hardware.org/?probe=ba511c29ac) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [28b061f34f](https://linux-hardware.org/?probe=28b061f34f) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [dd8bd37036](https://linux-hardware.org/?probe=dd8bd37036) | Jul 08, 2023 |
| Acer          | Aspire A315-53              | [488366cee5](https://linux-hardware.org/?probe=488366cee5) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [63669f1312](https://linux-hardware.org/?probe=63669f1312) | Jul 08, 2023 |
| Acer          | Nitro AN515-44              | [d695952680](https://linux-hardware.org/?probe=d695952680) | Jul 07, 2023 |
| HP            | Folio 13                    | [dd1a09fa9d](https://linux-hardware.org/?probe=dd1a09fa9d) | Jul 07, 2023 |
| Samsung       | 300E5M/300E5L               | [f60025eb2c](https://linux-hardware.org/?probe=f60025eb2c) | Jul 07, 2023 |
| Timi          | RedmiBook Pro 14S           | [54262c3aeb](https://linux-hardware.org/?probe=54262c3aeb) | Jul 07, 2023 |
| Acer          | Mammoth                     | [2cac6d75d0](https://linux-hardware.org/?probe=2cac6d75d0) | Jul 07, 2023 |
| Sony          | VPCSB25FB                   | [fda12b9c70](https://linux-hardware.org/?probe=fda12b9c70) | Jul 07, 2023 |
| Dell          | Inspiron N4030              | [7fca58229c](https://linux-hardware.org/?probe=7fca58229c) | Jul 07, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [fdb4fd8cb4](https://linux-hardware.org/?probe=fdb4fd8cb4) | Jul 07, 2023 |
| Dell          | Inspiron 5447               | [284afde913](https://linux-hardware.org/?probe=284afde913) | Jul 07, 2023 |
| Dell          | Inspiron 5447               | [22e09bd073](https://linux-hardware.org/?probe=22e09bd073) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7991ee84b](https://linux-hardware.org/?probe=f7991ee84b) | Jul 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [681a43f02f](https://linux-hardware.org/?probe=681a43f02f) | Jul 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [6539d1f91c](https://linux-hardware.org/?probe=6539d1f91c) | Jul 06, 2023 |
| Dell          | Latitude E6420              | [620b3c9397](https://linux-hardware.org/?probe=620b3c9397) | Jul 06, 2023 |
| Dell          | G3 3590                     | [e3cfb2968a](https://linux-hardware.org/?probe=e3cfb2968a) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| Apple         | MacBookPro7,1               | [c85ac748f8](https://linux-hardware.org/?probe=c85ac748f8) | Jul 06, 2023 |
| HP            | Pavilion dv4 2055br         | [d06fc3c63a](https://linux-hardware.org/?probe=d06fc3c63a) | Jul 06, 2023 |
| Acer          | Nitro AN517-54              | [2943ff2787](https://linux-hardware.org/?probe=2943ff2787) | Jul 06, 2023 |
| Dell          | Latitude 3420               | [346bb9a98d](https://linux-hardware.org/?probe=346bb9a98d) | Jul 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [9b01a450b1](https://linux-hardware.org/?probe=9b01a450b1) | Jul 05, 2023 |
| Lenovo        | G405                        | [2246272bf6](https://linux-hardware.org/?probe=2246272bf6) | Jul 05, 2023 |
| Dell          | Latitude 3490               | [a730cef547](https://linux-hardware.org/?probe=a730cef547) | Jul 05, 2023 |
| Dell          | G3 3590                     | [35906fded9](https://linux-hardware.org/?probe=35906fded9) | Jul 05, 2023 |
| ASUSTek       | VX7SX                       | [2ef4295d22](https://linux-hardware.org/?probe=2ef4295d22) | Jul 05, 2023 |
| Lenovo        | Yoga 510-14ISK 80UK         | [7a1c9a74b9](https://linux-hardware.org/?probe=7a1c9a74b9) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [708fb65c2c](https://linux-hardware.org/?probe=708fb65c2c) | Jul 05, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | [e8f0daea94](https://linux-hardware.org/?probe=e8f0daea94) | Jul 04, 2023 |
| Standard      | ECT                         | [42f38309b9](https://linux-hardware.org/?probe=42f38309b9) | Jul 04, 2023 |
| Dell          | Vostro 1000                 | [b83feae6f5](https://linux-hardware.org/?probe=b83feae6f5) | Jul 04, 2023 |
| Acer          | Aspire ES1-411              | [898ea84872](https://linux-hardware.org/?probe=898ea84872) | Jul 04, 2023 |
| Notebook      | NJx0MU                      | [700348835b](https://linux-hardware.org/?probe=700348835b) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [7ee43d9cad](https://linux-hardware.org/?probe=7ee43d9cad) | Jul 03, 2023 |
| Positivo      | C14CU51                     | [8b8d839dc0](https://linux-hardware.org/?probe=8b8d839dc0) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| GPD           | MicroPC                     | [f666f4c574](https://linux-hardware.org/?probe=f666f4c574) | Jul 03, 2023 |
| HP            | Folio 13                    | [faf3cb7d1f](https://linux-hardware.org/?probe=faf3cb7d1f) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [f78f6977d9](https://linux-hardware.org/?probe=f78f6977d9) | Jul 03, 2023 |
| Lenovo        | ThinkPad T420 4180AG3       | [21fe808c05](https://linux-hardware.org/?probe=21fe808c05) | Jul 02, 2023 |
| Notebook      | NJx0MU                      | [63a0b07325](https://linux-hardware.org/?probe=63a0b07325) | Jul 02, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [8120591fdf](https://linux-hardware.org/?probe=8120591fdf) | Jul 02, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [4a3acc3b0d](https://linux-hardware.org/?probe=4a3acc3b0d) | Jul 02, 2023 |
| Positivo      | Q464B                       | [9dad5f0aa1](https://linux-hardware.org/?probe=9dad5f0aa1) | Jul 02, 2023 |
| Dell          | Inspiron 5566               | [c0fa0d6c73](https://linux-hardware.org/?probe=c0fa0d6c73) | Jul 02, 2023 |
| Samsung       | 300E5K/300E5Q               | [5248df0795](https://linux-hardware.org/?probe=5248df0795) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | [07f04b7377](https://linux-hardware.org/?probe=07f04b7377) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | [65c2a81637](https://linux-hardware.org/?probe=65c2a81637) | Jul 01, 2023 |
| Unknown       | Unknown                     | [8b4c8e0e14](https://linux-hardware.org/?probe=8b4c8e0e14) | Jul 01, 2023 |
| Acer          | JM11-MS                     | [ad02c854e0](https://linux-hardware.org/?probe=ad02c854e0) | Jul 01, 2023 |
| Dell          | Inspiron 5457               | [af20c68e45](https://linux-hardware.org/?probe=af20c68e45) | Jul 01, 2023 |
| Notebook      | NJx0MU                      | [6896f4aafb](https://linux-hardware.org/?probe=6896f4aafb) | Jul 01, 2023 |
| Apple         | MacBookPro8,2               | [8386acaa29](https://linux-hardware.org/?probe=8386acaa29) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Toshiba       | IS 1413G                    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| eMachines     | eME443                      | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| Notebook      | NJx0MU                      | [136060092c](https://linux-hardware.org/?probe=136060092c) | Jun 30, 2023 |
| Positivo      | Mobile                      | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [3aa4a11068](https://linux-hardware.org/?probe=3aa4a11068) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [3a8a822af9](https://linux-hardware.org/?probe=3a8a822af9) | Jun 30, 2023 |
| Positivo      | S14CT01                     | [b70845bd08](https://linux-hardware.org/?probe=b70845bd08) | Jun 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [cfbc8c8a97](https://linux-hardware.org/?probe=cfbc8c8a97) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Positivo      | H14CU02                     | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| Dell          | Inspiron 1440               | [ed9bcaecd2](https://linux-hardware.org/?probe=ed9bcaecd2) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| Sony          | SVE17137CXB                 | [ed6f82dc16](https://linux-hardware.org/?probe=ed6f82dc16) | Jun 29, 2023 |
| Acer          | Nitro AN515-55              | [a41ff8c573](https://linux-hardware.org/?probe=a41ff8c573) | Jun 29, 2023 |
| Dell          | Inspiron N5010              | [5683980090](https://linux-hardware.org/?probe=5683980090) | Jun 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [f64ccf77fb](https://linux-hardware.org/?probe=f64ccf77fb) | Jun 28, 2023 |
| Toshiba       | PORTEGE R500                | [2c6448083e](https://linux-hardware.org/?probe=2c6448083e) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| Notebook      | NJx0MU                      | [235e541e2d](https://linux-hardware.org/?probe=235e541e2d) | Jun 28, 2023 |
| Acer          | Aspire 4349                 | [9064db77e4](https://linux-hardware.org/?probe=9064db77e4) | Jun 28, 2023 |
| Samsung       | 550XCJ/550XCR               | [bca3e799e0](https://linux-hardware.org/?probe=bca3e799e0) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Clevo         | M540SS Bottom               | [4b613733a0](https://linux-hardware.org/?probe=4b613733a0) | Jun 27, 2023 |
| Samsung       | 305U1A                      | [cd7de3aecf](https://linux-hardware.org/?probe=cd7de3aecf) | Jun 27, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ec69000909](https://linux-hardware.org/?probe=ec69000909) | Jun 27, 2023 |
| Acer          | Nitro AN515-45              | [0bfb7dc30a](https://linux-hardware.org/?probe=0bfb7dc30a) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [fce3ec0379](https://linux-hardware.org/?probe=fce3ec0379) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [5eac5b8b6d](https://linux-hardware.org/?probe=5eac5b8b6d) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| Acer          | Aspire VX5-591G             | [b4bd8360ea](https://linux-hardware.org/?probe=b4bd8360ea) | Jun 27, 2023 |
| Acer          | Aspire VX5-591G             | [1ffeb058e9](https://linux-hardware.org/?probe=1ffeb058e9) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | [0052df6a90](https://linux-hardware.org/?probe=0052df6a90) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| Samsung       | 305U1A                      | [ab46376842](https://linux-hardware.org/?probe=ab46376842) | Jun 27, 2023 |
| Samsung       | 305U1A                      | [b2f2c2b000](https://linux-hardware.org/?probe=b2f2c2b000) | Jun 26, 2023 |
| Dell          | Inspiron 3442               | [6e179dbfb0](https://linux-hardware.org/?probe=6e179dbfb0) | Jun 26, 2023 |
| Daten Tecn... | ESTELAR                     | [d5f99bced6](https://linux-hardware.org/?probe=d5f99bced6) | Jun 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e89c1b2b89](https://linux-hardware.org/?probe=e89c1b2b89) | Jun 26, 2023 |
| eMachines     | E525                        | [9e477a5fad](https://linux-hardware.org/?probe=9e477a5fad) | Jun 26, 2023 |
| Acer          | Nitro AN517-54              | [9af91d0ced](https://linux-hardware.org/?probe=9af91d0ced) | Jun 26, 2023 |
| Acer          | Aspire A515-51              | [ee5172b420](https://linux-hardware.org/?probe=ee5172b420) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| Acer          | Nitro AN517-54              | [9a87719748](https://linux-hardware.org/?probe=9a87719748) | Jun 25, 2023 |
| Acer          | Aspire A515-56              | [710bc10bf8](https://linux-hardware.org/?probe=710bc10bf8) | Jun 25, 2023 |
| Acer          | Aspire A515-56              | [a9b805ab66](https://linux-hardware.org/?probe=a9b805ab66) | Jun 25, 2023 |
| Notebook      | NJx0MU                      | [47a0ae93f4](https://linux-hardware.org/?probe=47a0ae93f4) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | [bce89b670d](https://linux-hardware.org/?probe=bce89b670d) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| Dell          | Latitude E6430              | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | PORTEGE R500                | [e327093da9](https://linux-hardware.org/?probe=e327093da9) | Jun 25, 2023 |
| Lenovo        | V15 G2 ITL 82ME             | [3fde30195c](https://linux-hardware.org/?probe=3fde30195c) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Lenovo        | ThinkPad T440p 20AWS2820... | [0ea92a193f](https://linux-hardware.org/?probe=0ea92a193f) | Jun 24, 2023 |
| Dell          | G5 5590                     | [6d6974b0eb](https://linux-hardware.org/?probe=6d6974b0eb) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | [dcfef21d2b](https://linux-hardware.org/?probe=dcfef21d2b) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | [62d08bd4ca](https://linux-hardware.org/?probe=62d08bd4ca) | Jun 24, 2023 |
| Dell          | Inspiron 3583               | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | [60034feb35](https://linux-hardware.org/?probe=60034feb35) | Jun 23, 2023 |
| Dell          | Latitude 3420               | [730bdb05fe](https://linux-hardware.org/?probe=730bdb05fe) | Jun 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [007cf1edce](https://linux-hardware.org/?probe=007cf1edce) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [e03310c8e8](https://linux-hardware.org/?probe=e03310c8e8) | Jun 22, 2023 |
| ASUSTek       | X45U                        | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| Dell          | Inspiron 11-3168            | [8407c1d3cb](https://linux-hardware.org/?probe=8407c1d3cb) | Jun 22, 2023 |
| Samsung       | 550XDA                      | [f20386ccdd](https://linux-hardware.org/?probe=f20386ccdd) | Jun 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [42cb7025f1](https://linux-hardware.org/?probe=42cb7025f1) | Jun 22, 2023 |
| Dell          | Inspiron 15 3511            | [0ef8557b4d](https://linux-hardware.org/?probe=0ef8557b4d) | Jun 22, 2023 |
| Acer          | Nitro AN515-44              | [d43ff293c1](https://linux-hardware.org/?probe=d43ff293c1) | Jun 22, 2023 |
| Positivo      | Mobile                      | [f9a55866f0](https://linux-hardware.org/?probe=f9a55866f0) | Jun 22, 2023 |
| Positivo      | Mobile                      | [25df2e5abc](https://linux-hardware.org/?probe=25df2e5abc) | Jun 22, 2023 |
| Dell          | Inspiron 1525               | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| Dell          | Inspiron 5557               | [cc0794fa6e](https://linux-hardware.org/?probe=cc0794fa6e) | Jun 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [817361caf5](https://linux-hardware.org/?probe=817361caf5) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e67932c5a0](https://linux-hardware.org/?probe=e67932c5a0) | Jun 21, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [8a05558ee0](https://linux-hardware.org/?probe=8a05558ee0) | Jun 20, 2023 |
| Acer          | Nitro AN517-51              | [b4423e6ac2](https://linux-hardware.org/?probe=b4423e6ac2) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [c40e92156c](https://linux-hardware.org/?probe=c40e92156c) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c0dc86bdc1](https://linux-hardware.org/?probe=c0dc86bdc1) | Jun 19, 2023 |
| HP            | EliteBook 8460p             | [2192185525](https://linux-hardware.org/?probe=2192185525) | Jun 18, 2023 |
| Lenovo        | IdeaPad Flex14 SharkBay     | [e904a7b3ce](https://linux-hardware.org/?probe=e904a7b3ce) | Jun 18, 2023 |
| Lenovo        | IdeaPad Flex14 SharkBay     | [cb84a2778b](https://linux-hardware.org/?probe=cb84a2778b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [d237a2bfe6](https://linux-hardware.org/?probe=d237a2bfe6) | Jun 18, 2023 |
| Dell          | Inspiron 5566               | [be5a148c53](https://linux-hardware.org/?probe=be5a148c53) | Jun 18, 2023 |
| HP            | EliteBook 8460p             | [c0de332a8b](https://linux-hardware.org/?probe=c0de332a8b) | Jun 18, 2023 |
| Acer          | Aspire E5-574               | [ca656065e5](https://linux-hardware.org/?probe=ca656065e5) | Jun 17, 2023 |
| Samsung       | 300E5K/300E5Q               | [a281272278](https://linux-hardware.org/?probe=a281272278) | Jun 17, 2023 |
| Avell High... | A70 HYB                     | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| Sony          | SVF15213CBW                 | [4fcc62d3ac](https://linux-hardware.org/?probe=4fcc62d3ac) | Jun 17, 2023 |
| HP            | Pavilion dv7                | [f010c487a1](https://linux-hardware.org/?probe=f010c487a1) | Jun 17, 2023 |
| Acer          | Nitro AN517-51              | [d2f2f70083](https://linux-hardware.org/?probe=d2f2f70083) | Jun 16, 2023 |
| Unknown       | Unknown                     | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| eMachines     | eMD728                      | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| Unknown       | Unknown                     | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a6f63a08e2](https://linux-hardware.org/?probe=a6f63a08e2) | Jun 15, 2023 |
| Apple         | MacBookAir4,1               | [e8575f0a34](https://linux-hardware.org/?probe=e8575f0a34) | Jun 15, 2023 |
| System76      | Gazelle                     | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| Positivo      | Q4128C-S                    | [1fab0b0752](https://linux-hardware.org/?probe=1fab0b0752) | Jun 15, 2023 |
| Dell          | Latitude 5480               | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| Acer          | Aspire A315-54K             | [472d8bc7df](https://linux-hardware.org/?probe=472d8bc7df) | Jun 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [49e4d6ccb3](https://linux-hardware.org/?probe=49e4d6ccb3) | Jun 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0c3df957ce](https://linux-hardware.org/?probe=0c3df957ce) | Jun 14, 2023 |
| Samsung       | 670Z5E                      | [20f84530c7](https://linux-hardware.org/?probe=20f84530c7) | Jun 14, 2023 |
| Acer          | Aspire A315-23G             | [18a5adccb6](https://linux-hardware.org/?probe=18a5adccb6) | Jun 14, 2023 |
| Acer          | Nitro AN517-54              | [d0187875be](https://linux-hardware.org/?probe=d0187875be) | Jun 13, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | [5223ed2efd](https://linux-hardware.org/?probe=5223ed2efd) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | [e25224b362](https://linux-hardware.org/?probe=e25224b362) | Jun 13, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [1439681971](https://linux-hardware.org/?probe=1439681971) | Jun 13, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3a8d104147](https://linux-hardware.org/?probe=3a8d104147) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [d2e4302f28](https://linux-hardware.org/?probe=d2e4302f28) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [e858489484](https://linux-hardware.org/?probe=e858489484) | Jun 13, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [c765305160](https://linux-hardware.org/?probe=c765305160) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | X451MA                      | [bfa5493aa2](https://linux-hardware.org/?probe=bfa5493aa2) | Jun 12, 2023 |
| Positivo      | C14CR01                     | [11d46971fa](https://linux-hardware.org/?probe=11d46971fa) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a1cbc5571a](https://linux-hardware.org/?probe=a1cbc5571a) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Dell          | G3 3579                     | [c04bf46d3e](https://linux-hardware.org/?probe=c04bf46d3e) | Jun 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9747487f82](https://linux-hardware.org/?probe=9747487f82) | Jun 11, 2023 |
| Dell          | Latitude 3420               | [07061e9d7d](https://linux-hardware.org/?probe=07061e9d7d) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | [c610b3b9fe](https://linux-hardware.org/?probe=c610b3b9fe) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | [88d3849db5](https://linux-hardware.org/?probe=88d3849db5) | Jun 10, 2023 |
| Acer          | Aspire E5-574G              | [8ca78da386](https://linux-hardware.org/?probe=8ca78da386) | Jun 10, 2023 |
| Acer          | Aspire E1-572               | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| Valve         | Jupiter                     | [c1e32f24ee](https://linux-hardware.org/?probe=c1e32f24ee) | Jun 10, 2023 |
| Acer          | Nitro AN515-44              | [b3531502a8](https://linux-hardware.org/?probe=b3531502a8) | Jun 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| Dell          | Vostro 3460                 | [e8ed8e8b1e](https://linux-hardware.org/?probe=e8ed8e8b1e) | Jun 09, 2023 |
| Dell          | Vostro 1310                 | [05fc6f167c](https://linux-hardware.org/?probe=05fc6f167c) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Dell          | Latitude E7240              | [1d8eb4fce4](https://linux-hardware.org/?probe=1d8eb4fce4) | Jun 09, 2023 |
| Dell          | Latitude E7240              | [da22551dca](https://linux-hardware.org/?probe=da22551dca) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| Dell          | G15 5520                    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Dell          | G15 5520                    | [8d48df5869](https://linux-hardware.org/?probe=8d48df5869) | Jun 07, 2023 |
| Dell          | Inspiron 15 5510            | [98d7cb7ea7](https://linux-hardware.org/?probe=98d7cb7ea7) | Jun 07, 2023 |
| Toshiba       | Satellite C855-233          | [fb90f9aa02](https://linux-hardware.org/?probe=fb90f9aa02) | Jun 07, 2023 |
| Dell          | Inspiron 5548               | [e67581e121](https://linux-hardware.org/?probe=e67581e121) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Google        | Chell                       | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| Acer          | Predator PH315-52           | [f7178495c7](https://linux-hardware.org/?probe=f7178495c7) | Jun 07, 2023 |
| Positivo      | Mobile                      | [12d5c3248c](https://linux-hardware.org/?probe=12d5c3248c) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [2f138401f6](https://linux-hardware.org/?probe=2f138401f6) | Jun 06, 2023 |
| HP            | Laptop 14s-dq1xxx           | [8f99826bf1](https://linux-hardware.org/?probe=8f99826bf1) | Jun 06, 2023 |
| Notebook      | NJx0MU                      | [0f91c977f0](https://linux-hardware.org/?probe=0f91c977f0) | Jun 06, 2023 |
| Apple         | MacBookAir7,2               | [44cf28ec0e](https://linux-hardware.org/?probe=44cf28ec0e) | Jun 05, 2023 |
| Compaq        | CQ-27                       | [ae3d9bce8c](https://linux-hardware.org/?probe=ae3d9bce8c) | Jun 05, 2023 |
| Acer          | Nitro AN515-52              | [e9d79e576b](https://linux-hardware.org/?probe=e9d79e576b) | Jun 05, 2023 |
| ASUSTek       | VX7SX                       | [ddf3010e73](https://linux-hardware.org/?probe=ddf3010e73) | Jun 05, 2023 |
| Samsung       | 950XEE                      | [cc47fd0df0](https://linux-hardware.org/?probe=cc47fd0df0) | Jun 05, 2023 |
| Notebook      | NJx0MU                      | [ce1569ee48](https://linux-hardware.org/?probe=ce1569ee48) | Jun 05, 2023 |
| Acer          | Aspire A315-42G             | [eb67866c74](https://linux-hardware.org/?probe=eb67866c74) | Jun 05, 2023 |
| Dell          | Latitude 3410               | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| Dell          | Latitude 3410               | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| Dell          | Inspiron N4030              | [4d82d8bf8b](https://linux-hardware.org/?probe=4d82d8bf8b) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Dell          | Inspiron 5437               | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Compaq        | 420                         | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| Samsung       | 670Z5E                      | [647589cbbd](https://linux-hardware.org/?probe=647589cbbd) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | [3c92b81349](https://linux-hardware.org/?probe=3c92b81349) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | [1aca93ba38](https://linux-hardware.org/?probe=1aca93ba38) | Jun 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [664282cc84](https://linux-hardware.org/?probe=664282cc84) | Jun 02, 2023 |
| Dell          | G15 5520                    | [5880c98c54](https://linux-hardware.org/?probe=5880c98c54) | Jun 02, 2023 |
| Acer          | Nitro AN515-51              | [2dc3c08466](https://linux-hardware.org/?probe=2dc3c08466) | Jun 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [55c7d4b615](https://linux-hardware.org/?probe=55c7d4b615) | Jun 02, 2023 |
| HP            | 420                         | [0e369b273b](https://linux-hardware.org/?probe=0e369b273b) | Jun 02, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [ea337d3d2a](https://linux-hardware.org/?probe=ea337d3d2a) | Jun 02, 2023 |
| Lenovo        | G400s VILG1                 | [fee541ee18](https://linux-hardware.org/?probe=fee541ee18) | Jun 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [33e440f44f](https://linux-hardware.org/?probe=33e440f44f) | Jun 01, 2023 |
| HP            | Pavilion dv6600             | [5e2867ee61](https://linux-hardware.org/?probe=5e2867ee61) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | [17621fb846](https://linux-hardware.org/?probe=17621fb846) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Notebook      | NJx0MU                      | [46f5148174](https://linux-hardware.org/?probe=46f5148174) | Jun 01, 2023 |
| Samsung       | 300E5K/300E5Q               | [00d2d07850](https://linux-hardware.org/?probe=00d2d07850) | May 31, 2023 |
| Unknown       | Unknown                     | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| HP            | Pavilion dv4                | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Apple         | MacBookPro7,1               | [4fc174a983](https://linux-hardware.org/?probe=4fc174a983) | May 31, 2023 |
| Toshiba       | IS 1413G                    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| Notebook      | NJx0MU                      | [dab4e98680](https://linux-hardware.org/?probe=dab4e98680) | May 31, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1b457302ec](https://linux-hardware.org/?probe=1b457302ec) | May 31, 2023 |
| Acer          | Nitro AN515-51              | [d3ee3757e0](https://linux-hardware.org/?probe=d3ee3757e0) | May 30, 2023 |
| Notebook      | P15SM-A/SM1-A               | [e71d8e3bc0](https://linux-hardware.org/?probe=e71d8e3bc0) | May 30, 2023 |
| Dell          | Inspiron 15-3567            | [e51e0ef0da](https://linux-hardware.org/?probe=e51e0ef0da) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| Unknown       | Unknown                     | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| Samsung       | RV419/RV420                 | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| Notebook      | NJx0MU                      | [c0ec67e3b1](https://linux-hardware.org/?probe=c0ec67e3b1) | May 30, 2023 |
| Dell          | Inspiron 1525               | [29d2e377ad](https://linux-hardware.org/?probe=29d2e377ad) | May 29, 2023 |
| Acer          | Aspire A515-57              | [e9f91331b2](https://linux-hardware.org/?probe=e9f91331b2) | May 29, 2023 |
| Avell High... | A70 MOB                     | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | Inspiron 1525               | [7adfc9796d](https://linux-hardware.org/?probe=7adfc9796d) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [981a09e39a](https://linux-hardware.org/?probe=981a09e39a) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [e36e944a92](https://linux-hardware.org/?probe=e36e944a92) | May 29, 2023 |
| Dell          | Inspiron 5447               | [270e3cd993](https://linux-hardware.org/?probe=270e3cd993) | May 29, 2023 |
| HP            | Pavilion g4                 | [12bef484db](https://linux-hardware.org/?probe=12bef484db) | May 29, 2023 |
| Notebook      | NJx0MU                      | [f46b9b1b6a](https://linux-hardware.org/?probe=f46b9b1b6a) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [14e5763b6f](https://linux-hardware.org/?probe=14e5763b6f) | May 29, 2023 |
| Apple         | MacBookAir5,1               | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Acer          | Aspire VX5-591G             | [1db96272fe](https://linux-hardware.org/?probe=1db96272fe) | May 29, 2023 |
| Dell          | Inspiron 1525               | [99540846c4](https://linux-hardware.org/?probe=99540846c4) | May 28, 2023 |
| Dell          | Inspiron 1525               | [99c9a792f5](https://linux-hardware.org/?probe=99c9a792f5) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [95793a85de](https://linux-hardware.org/?probe=95793a85de) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [7c9addaf1c](https://linux-hardware.org/?probe=7c9addaf1c) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1b4eb11af8](https://linux-hardware.org/?probe=1b4eb11af8) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [77e5b682ff](https://linux-hardware.org/?probe=77e5b682ff) | May 28, 2023 |
| Unknown       | Unknown                     | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Positivo      | N1250                       | [f014b93eba](https://linux-hardware.org/?probe=f014b93eba) | May 28, 2023 |
| Dell          | Inspiron 5421               | [c559e851a2](https://linux-hardware.org/?probe=c559e851a2) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| Dell          | Vostro 5402                 | [41a9c1dcf2](https://linux-hardware.org/?probe=41a9c1dcf2) | May 28, 2023 |
| Acer          | Aspire A515-45              | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Latitude 7490               | [fbad4c1a53](https://linux-hardware.org/?probe=fbad4c1a53) | May 27, 2023 |
| Dell          | Latitude 7490               | [00c44ed00c](https://linux-hardware.org/?probe=00c44ed00c) | May 27, 2023 |
| Positivo      | C14CR21TV                   | [f3907d940d](https://linux-hardware.org/?probe=f3907d940d) | May 27, 2023 |
| HP            | 1000                        | [f3b014fa71](https://linux-hardware.org/?probe=f3b014fa71) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [82cad47c63](https://linux-hardware.org/?probe=82cad47c63) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [09cc59aa19](https://linux-hardware.org/?probe=09cc59aa19) | May 27, 2023 |
| HP            | Pavilion dm4                | [708daa02e2](https://linux-hardware.org/?probe=708daa02e2) | May 26, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [8b93a6ab33](https://linux-hardware.org/?probe=8b93a6ab33) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Itautec       | Infoway                     | [03be6afc10](https://linux-hardware.org/?probe=03be6afc10) | May 26, 2023 |
| Dell          | Inspiron 15-3567            | [0f79b43742](https://linux-hardware.org/?probe=0f79b43742) | May 26, 2023 |
| Samsung       | 550XDA                      | [6cc9f3cbe4](https://linux-hardware.org/?probe=6cc9f3cbe4) | May 26, 2023 |
| Acer          | Predator PT316-51s          | [0242988287](https://linux-hardware.org/?probe=0242988287) | May 26, 2023 |
| HP            | ProBook 645 G1              | [347779f3bf](https://linux-hardware.org/?probe=347779f3bf) | May 26, 2023 |
| A14CR         | Unknown                     | [a504061244](https://linux-hardware.org/?probe=a504061244) | May 25, 2023 |
| Clevo         | P150HMx                     | [d6c90a2c0c](https://linux-hardware.org/?probe=d6c90a2c0c) | May 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffdb62c45](https://linux-hardware.org/?probe=0ffdb62c45) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [3304e68c39](https://linux-hardware.org/?probe=3304e68c39) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [c885a13922](https://linux-hardware.org/?probe=c885a13922) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [897b688aba](https://linux-hardware.org/?probe=897b688aba) | May 25, 2023 |
| PHILCO ELE... | PNB15.6AP34H1W10            | [dc91cb92af](https://linux-hardware.org/?probe=dc91cb92af) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86666c3371](https://linux-hardware.org/?probe=86666c3371) | May 24, 2023 |
| Avell High... | A72 HYB                     | [c6f131b8b1](https://linux-hardware.org/?probe=c6f131b8b1) | May 24, 2023 |
| Avell High... | A72 HYB                     | [d54fb61d87](https://linux-hardware.org/?probe=d54fb61d87) | May 24, 2023 |
| Dell          | XPS 13 9300                 | [255811069a](https://linux-hardware.org/?probe=255811069a) | May 23, 2023 |
| Dell          | Inspiron 3583               | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| Dell          | Vostro 5402                 | [e6834866ba](https://linux-hardware.org/?probe=e6834866ba) | May 23, 2023 |
| Dell          | Inspiron 1525               | [a92437f5aa](https://linux-hardware.org/?probe=a92437f5aa) | May 23, 2023 |
| Chuwi         | HeroBook Air                | [724db856f3](https://linux-hardware.org/?probe=724db856f3) | May 23, 2023 |
| Notebook      | NJx0MU                      | [1ff1bde0f0](https://linux-hardware.org/?probe=1ff1bde0f0) | May 23, 2023 |
| Dell          | Inspiron 1525               | [2afda2396c](https://linux-hardware.org/?probe=2afda2396c) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84717aefdf](https://linux-hardware.org/?probe=84717aefdf) | May 22, 2023 |
| Acer          | Swift SF514-56T             | [81a0e002b7](https://linux-hardware.org/?probe=81a0e002b7) | May 22, 2023 |
| Dell          | Inspiron 3443               | [35923f74b5](https://linux-hardware.org/?probe=35923f74b5) | May 22, 2023 |
| Dell          | Inspiron 7520               | [eeca18ff12](https://linux-hardware.org/?probe=eeca18ff12) | May 22, 2023 |
| Samsung       | 300E5M/300E5L               | [ebd65238d8](https://linux-hardware.org/?probe=ebd65238d8) | May 22, 2023 |
| Notebook      | NJx0MU                      | [98473b6b1e](https://linux-hardware.org/?probe=98473b6b1e) | May 22, 2023 |
| Philco        | 14H                         | [5dbb0cb3b7](https://linux-hardware.org/?probe=5dbb0cb3b7) | May 21, 2023 |
| Dell          | XPS 13 9310                 | [19be933f8a](https://linux-hardware.org/?probe=19be933f8a) | May 21, 2023 |
| Toshiba       | IS 1413G                    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| Acer          | Nitro AN517-54              | [105fb43fc1](https://linux-hardware.org/?probe=105fb43fc1) | May 20, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [42ab4c7e67](https://linux-hardware.org/?probe=42ab4c7e67) | May 20, 2023 |
| Acer          | Nitro AN515-54              | [4f27fb9c64](https://linux-hardware.org/?probe=4f27fb9c64) | May 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| Acer          | Aspire A315-42G             | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3442               | [a8bb37c78e](https://linux-hardware.org/?probe=a8bb37c78e) | May 19, 2023 |
| Avell High... | A40 LIV                     | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [9475bc847b](https://linux-hardware.org/?probe=9475bc847b) | May 19, 2023 |
| Dell          | Vostro 15 3515              | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad T400 2767E53       | [5cd6c87b7e](https://linux-hardware.org/?probe=5cd6c87b7e) | May 18, 2023 |
| Dell          | Vostro 15 3510              | [e5e7213107](https://linux-hardware.org/?probe=e5e7213107) | May 18, 2023 |
| Lenovo        | ThinkPad T490s 20NXS01Y0... | [277ed003ce](https://linux-hardware.org/?probe=277ed003ce) | May 18, 2023 |
| Dell          | Inspiron 3583               | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8EG0... | [0735cab104](https://linux-hardware.org/?probe=0735cab104) | May 18, 2023 |
| Clevo         | P150HMx                     | [17e11751ef](https://linux-hardware.org/?probe=17e11751ef) | May 18, 2023 |
| Clevo         | P150HMx                     | [f749300168](https://linux-hardware.org/?probe=f749300168) | May 18, 2023 |
| Lenovo        | IdeaPad Z470                | [158feeb98d](https://linux-hardware.org/?probe=158feeb98d) | May 18, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | [681fd36c12](https://linux-hardware.org/?probe=681fd36c12) | May 18, 2023 |
| Dell          | Inspiron 15 3511            | [255961cb74](https://linux-hardware.org/?probe=255961cb74) | May 18, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a167afa608](https://linux-hardware.org/?probe=a167afa608) | May 17, 2023 |
| Acer          | Nitro AN517-54              | [9372615767](https://linux-hardware.org/?probe=9372615767) | May 17, 2023 |
| Dell          | Latitude E7240              | [1990186432](https://linux-hardware.org/?probe=1990186432) | May 17, 2023 |
| Dell          | Inspiron 15-7568            | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Dell          | Latitude 5420               | [ddd072b69c](https://linux-hardware.org/?probe=ddd072b69c) | May 16, 2023 |
| Acer          | Aspire 5050                 | [44f9abca04](https://linux-hardware.org/?probe=44f9abca04) | May 16, 2023 |
| Dell          | Latitude 7420               | [4e1680877b](https://linux-hardware.org/?probe=4e1680877b) | May 16, 2023 |
| Samsung       | 550XDA                      | [75bc1cdfb3](https://linux-hardware.org/?probe=75bc1cdfb3) | May 16, 2023 |
| Acer          | Aspire E5-571               | [6094f7a191](https://linux-hardware.org/?probe=6094f7a191) | May 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [055aae99b8](https://linux-hardware.org/?probe=055aae99b8) | May 16, 2023 |
| Toshiba       | IS 1413G                    | [df01be5efd](https://linux-hardware.org/?probe=df01be5efd) | May 16, 2023 |
| PHILCO ELE... | PNB15.6AP34H1W10            | [4c4c7467ec](https://linux-hardware.org/?probe=4c4c7467ec) | May 16, 2023 |
| Positivo      | Q4128C-S                    | [05c0522fe3](https://linux-hardware.org/?probe=05c0522fe3) | May 16, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [fe4f47ccc9](https://linux-hardware.org/?probe=fe4f47ccc9) | May 15, 2023 |
| Dell          | Inspiron 3542               | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| Dell          | G3 3590                     | [75a6a8a107](https://linux-hardware.org/?probe=75a6a8a107) | May 15, 2023 |
| Acer          | Aspire A515-45              | [2375fac142](https://linux-hardware.org/?probe=2375fac142) | May 15, 2023 |
| Dell          | G3 3590                     | [b19462038d](https://linux-hardware.org/?probe=b19462038d) | May 15, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [f199f11aa5](https://linux-hardware.org/?probe=f199f11aa5) | May 15, 2023 |
| Acer          | AO532h                      | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Dell          | Inspiron N5010              | [98f448ed70](https://linux-hardware.org/?probe=98f448ed70) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5dadcb24d0](https://linux-hardware.org/?probe=5dadcb24d0) | May 15, 2023 |
| Valve         | Jupiter                     | [dca8b16469](https://linux-hardware.org/?probe=dca8b16469) | May 15, 2023 |
| ASUSTek       | K45VM                       | [eaef457c8a](https://linux-hardware.org/?probe=eaef457c8a) | May 15, 2023 |
| Dell          | G15 5510                    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Notebook      | NJx0MU                      | [7feff56d1d](https://linux-hardware.org/?probe=7feff56d1d) | May 15, 2023 |
| Dell          | Inspiron 3583               | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| Lenovo        | ThinkPad T420 4236PJ2       | [22a9e8213e](https://linux-hardware.org/?probe=22a9e8213e) | May 14, 2023 |
| Intel         | W7650                       | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Notebook      | NJx0MU                      | [41c5120619](https://linux-hardware.org/?probe=41c5120619) | May 14, 2023 |
| Dell          | Vostro 5471                 | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Toshiba       | IS 1413G                    | [821d79dc3f](https://linux-hardware.org/?probe=821d79dc3f) | May 14, 2023 |
| Dell          | System Inspiron N4120       | [c7f1c9e542](https://linux-hardware.org/?probe=c7f1c9e542) | May 14, 2023 |
| Acer          | Aspire A315-23              | [64237b5d6e](https://linux-hardware.org/?probe=64237b5d6e) | May 14, 2023 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [9eb38c956d](https://linux-hardware.org/?probe=9eb38c956d) | May 14, 2023 |
| HP            | Compaq Presario CQ40        | [22d379cd2f](https://linux-hardware.org/?probe=22d379cd2f) | May 13, 2023 |
| Samsung       | 550XDA                      | [5f562807be](https://linux-hardware.org/?probe=5f562807be) | May 13, 2023 |
| Notebook      | NJx0MU                      | [b14b7c3725](https://linux-hardware.org/?probe=b14b7c3725) | May 13, 2023 |
| Notebook      | NJx0MU                      | [9759b380bb](https://linux-hardware.org/?probe=9759b380bb) | May 13, 2023 |
| Dell          | Inspiron 7580               | [01d9730a88](https://linux-hardware.org/?probe=01d9730a88) | May 12, 2023 |
| Toshiba       | STI NA 1401                 | [c9aa3a7539](https://linux-hardware.org/?probe=c9aa3a7539) | May 12, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [ee8fe21e76](https://linux-hardware.org/?probe=ee8fe21e76) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| Positivo      | J14GL11                     | [bfdf0df9b8](https://linux-hardware.org/?probe=bfdf0df9b8) | May 12, 2023 |
| Multilaser    | PC150                       | [0a59946a8f](https://linux-hardware.org/?probe=0a59946a8f) | May 12, 2023 |
| Positivo      | J14GL11                     | [9594837399](https://linux-hardware.org/?probe=9594837399) | May 11, 2023 |
| Itautec       | Infoway w7440               | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Alienware     | m15 R6                      | [bfa28cc7bd](https://linux-hardware.org/?probe=bfa28cc7bd) | May 11, 2023 |
| Alienware     | m15 R7                      | [d481f5a70d](https://linux-hardware.org/?probe=d481f5a70d) | May 10, 2023 |
| Dell          | Inspiron 5590               | [117a2b318d](https://linux-hardware.org/?probe=117a2b318d) | May 10, 2023 |
| Dell          | Inspiron 5590               | [9c53d54cae](https://linux-hardware.org/?probe=9c53d54cae) | May 10, 2023 |
| HP            | ENVY 15                     | [ba0636efe5](https://linux-hardware.org/?probe=ba0636efe5) | May 10, 2023 |
| Dell          | Inspiron 5566               | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Dell          | Inspiron 15 5510            | [174505e46f](https://linux-hardware.org/?probe=174505e46f) | May 10, 2023 |
| Notebook      | NJx0MU                      | [af88b26379](https://linux-hardware.org/?probe=af88b26379) | May 09, 2023 |
| Alienware     | m15 R7                      | [cfd5f51d93](https://linux-hardware.org/?probe=cfd5f51d93) | May 09, 2023 |
| Acer          | Aspire A515-45              | [922a0d7b9e](https://linux-hardware.org/?probe=922a0d7b9e) | May 09, 2023 |
| Acer          | Aspire A515-45              | [4df8233d54](https://linux-hardware.org/?probe=4df8233d54) | May 09, 2023 |
| Avell High... | A40 LIV                     | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Acer          | Aspire A514-54              | [dafa2886a3](https://linux-hardware.org/?probe=dafa2886a3) | May 09, 2023 |
| Dell          | Inspiron 3442               | [e858474ff0](https://linux-hardware.org/?probe=e858474ff0) | May 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [205b8a8ca7](https://linux-hardware.org/?probe=205b8a8ca7) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Samsung       | 550XBE/350XBE               | [479ad5c021](https://linux-hardware.org/?probe=479ad5c021) | May 08, 2023 |
| Avell High... | A65 MOB                     | [d6c6781535](https://linux-hardware.org/?probe=d6c6781535) | May 08, 2023 |
| Avell High... | 1513                        | [6e383641d6](https://linux-hardware.org/?probe=6e383641d6) | May 08, 2023 |
| Notebook      | NJx0MU                      | [9e877e8df9](https://linux-hardware.org/?probe=9e877e8df9) | May 08, 2023 |
| Samsung       | 530XBB                      | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | Latitude 7490               | [c871c848b9](https://linux-hardware.org/?probe=c871c848b9) | May 08, 2023 |
| Positivo      | S14CT01                     | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Toshiba       | IS 1413G                    | [c437a16a33](https://linux-hardware.org/?probe=c437a16a33) | May 07, 2023 |
| Biostar       | A320MH                      | [5b240feaed](https://linux-hardware.org/?probe=5b240feaed) | May 07, 2023 |
| Itautec       | Infoway a7420               | [52788f2c92](https://linux-hardware.org/?probe=52788f2c92) | May 07, 2023 |
| HP            | Pavilion dm4                | [8f79a54339](https://linux-hardware.org/?probe=8f79a54339) | May 07, 2023 |
| Dell          | Vostro 14-3468              | [0a096de0e1](https://linux-hardware.org/?probe=0a096de0e1) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | [9a510bb01b](https://linux-hardware.org/?probe=9a510bb01b) | May 06, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [696525cf17](https://linux-hardware.org/?probe=696525cf17) | May 06, 2023 |
| ASUSTek       | X441BA                      | [326309c1f1](https://linux-hardware.org/?probe=326309c1f1) | May 06, 2023 |
| ASUSTek       | X441BA                      | [dee3bc2cdb](https://linux-hardware.org/?probe=dee3bc2cdb) | May 06, 2023 |
| Acer          | Nitro AN517-54              | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [384cc356fc](https://linux-hardware.org/?probe=384cc356fc) | May 06, 2023 |
| Avell High... | A70 HYB                     | [0d871806d1](https://linux-hardware.org/?probe=0d871806d1) | May 05, 2023 |
| Avell High... | A70 HYB                     | [9519eef96f](https://linux-hardware.org/?probe=9519eef96f) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f2c390eb7e](https://linux-hardware.org/?probe=f2c390eb7e) | May 05, 2023 |
| ASUSTek       | K45VM                       | [09e73cade8](https://linux-hardware.org/?probe=09e73cade8) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7046c6c99](https://linux-hardware.org/?probe=f7046c6c99) | May 05, 2023 |
| Positivo      | N4350                       | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| Dell          | Inspiron 7520               | [2ae295d2a0](https://linux-hardware.org/?probe=2ae295d2a0) | May 05, 2023 |
| Acer          | Aspire E1-421               | [45bca26278](https://linux-hardware.org/?probe=45bca26278) | May 05, 2023 |
| Dell          | Inspiron 5490               | [a6c9c8b3b5](https://linux-hardware.org/?probe=a6c9c8b3b5) | May 05, 2023 |
| Avell High... | A40 LIV                     | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| Dell          | Inspiron 5402               | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Avell High... | C62 LIV                     | [b53a07f1a3](https://linux-hardware.org/?probe=b53a07f1a3) | May 04, 2023 |
| Acer          | Aspire A515-52G             | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| Unknown       | E450                        | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Dell          | Latitude 3470               | [532cd0124e](https://linux-hardware.org/?probe=532cd0124e) | May 04, 2023 |
| Lenovo        | B490 37722XP                | [62808a2dee](https://linux-hardware.org/?probe=62808a2dee) | May 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [42c07a1fe0](https://linux-hardware.org/?probe=42c07a1fe0) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [bbe569dff7](https://linux-hardware.org/?probe=bbe569dff7) | May 03, 2023 |
| ASUSTek       | X751LJ                      | [708ac49447](https://linux-hardware.org/?probe=708ac49447) | May 03, 2023 |
| ASUSTek       | X751LJ                      | [66e45eac2c](https://linux-hardware.org/?probe=66e45eac2c) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| Acer          | Nitro AN517-54              | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| Toshiba       | IS 1413G                    | [81a4d2ac8b](https://linux-hardware.org/?probe=81a4d2ac8b) | May 03, 2023 |
| Adreamer      | PN1308P                     | [8ae75bc5a0](https://linux-hardware.org/?probe=8ae75bc5a0) | May 02, 2023 |
| Dell          | Inspiron 3501               | [6e70e21e58](https://linux-hardware.org/?probe=6e70e21e58) | May 02, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [143b75f514](https://linux-hardware.org/?probe=143b75f514) | May 02, 2023 |
| Samsung       | 550XDA                      | [4bea46787f](https://linux-hardware.org/?probe=4bea46787f) | May 02, 2023 |
| Notebook      | NJx0MU                      | [b7ff999133](https://linux-hardware.org/?probe=b7ff999133) | May 02, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a5ac1bf5b4](https://linux-hardware.org/?probe=a5ac1bf5b4) | May 01, 2023 |
| Notebook      | NJx0MU                      | [c56afa707e](https://linux-hardware.org/?probe=c56afa707e) | May 01, 2023 |
| Dell          | Inspiron 5458               | [c38d3e6513](https://linux-hardware.org/?probe=c38d3e6513) | May 01, 2023 |
| Dell          | Inspiron 7460               | [696014fc68](https://linux-hardware.org/?probe=696014fc68) | May 01, 2023 |
| Notebook      | NJx0MU                      | [99a39f6696](https://linux-hardware.org/?probe=99a39f6696) | May 01, 2023 |
| Acer          | Nitro AN517-54              | [593a6b247f](https://linux-hardware.org/?probe=593a6b247f) | May 01, 2023 |
| Notebook      | NJx0MU                      | [66a3f8bc3a](https://linux-hardware.org/?probe=66a3f8bc3a) | May 01, 2023 |
| Unknown       | Unknown                     | [8978b9aa5f](https://linux-hardware.org/?probe=8978b9aa5f) | May 01, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [a7d6d782b2](https://linux-hardware.org/?probe=a7d6d782b2) | May 01, 2023 |
| Notebook      | NJx0MU                      | [193fb3ba91](https://linux-hardware.org/?probe=193fb3ba91) | Apr 30, 2023 |
| Unknown       | Unknown                     | [070854df6b](https://linux-hardware.org/?probe=070854df6b) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| Positivo      | Q464C                       | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | [5fd8f6db6e](https://linux-hardware.org/?probe=5fd8f6db6e) | Apr 30, 2023 |
| Acer          | Nitro AN515-45              | [9b28e69254](https://linux-hardware.org/?probe=9b28e69254) | Apr 30, 2023 |
| Positivo      | S14CT01                     | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| HP            | Pavilion dm4                | [3473d4b312](https://linux-hardware.org/?probe=3473d4b312) | Apr 29, 2023 |
| Apple         | MacBookPro9,2               | [1e75efbfab](https://linux-hardware.org/?probe=1e75efbfab) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Dell          | Inspiron 15-3567            | [33e30c562d](https://linux-hardware.org/?probe=33e30c562d) | Apr 29, 2023 |
| ASUSTek       | Z550SA                      | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| Acer          | Aspire E5-571               | [1d36dafa86](https://linux-hardware.org/?probe=1d36dafa86) | Apr 28, 2023 |
| HP            | Presario CQ43               | [c14c79b3cf](https://linux-hardware.org/?probe=c14c79b3cf) | Apr 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [6a56164bfd](https://linux-hardware.org/?probe=6a56164bfd) | Apr 27, 2023 |
| Acer          | Aspire A315-54              | [8137aa9008](https://linux-hardware.org/?probe=8137aa9008) | Apr 27, 2023 |
| Dell          | Inspiron 5558               | [9f3b8c952d](https://linux-hardware.org/?probe=9f3b8c952d) | Apr 27, 2023 |
| Notebook      | NJx0MU                      | [2306f31aa2](https://linux-hardware.org/?probe=2306f31aa2) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [393c7b06d5](https://linux-hardware.org/?probe=393c7b06d5) | Apr 26, 2023 |
| Dell          | Inspiron 7580               | [d9fe7034bd](https://linux-hardware.org/?probe=d9fe7034bd) | Apr 26, 2023 |
| Dell          | G15 5510                    | [9dcb76f7c1](https://linux-hardware.org/?probe=9dcb76f7c1) | Apr 26, 2023 |
| Dell          | G15 5510                    | [4030b4f936](https://linux-hardware.org/?probe=4030b4f936) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| Apple         | MacBookAir7,2               | [7cbf188375](https://linux-hardware.org/?probe=7cbf188375) | Apr 26, 2023 |
| Apple         | MacBookAir7,2               | [b94d783285](https://linux-hardware.org/?probe=b94d783285) | Apr 26, 2023 |
| Notebook      | NJx0MU                      | [a660a768ce](https://linux-hardware.org/?probe=a660a768ce) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| Acer          | Nitro AN517-54              | [9fe0f33003](https://linux-hardware.org/?probe=9fe0f33003) | Apr 26, 2023 |
| Toshiba       | IS 1413G                    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [5c79032176](https://linux-hardware.org/?probe=5c79032176) | Apr 25, 2023 |
| HP            | Pavilion g4                 | [5e2040a91f](https://linux-hardware.org/?probe=5e2040a91f) | Apr 25, 2023 |
| Login Info... | LOG-S14BW01-CD              | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| Dell          | G15 5515                    | [a0dd3f2003](https://linux-hardware.org/?probe=a0dd3f2003) | Apr 25, 2023 |
| Avell High... | A70 HYB BS                  | [c7b5f9ef04](https://linux-hardware.org/?probe=c7b5f9ef04) | Apr 25, 2023 |
| Acer          | Nitro AN515-51              | [48e88f7bd1](https://linux-hardware.org/?probe=48e88f7bd1) | Apr 25, 2023 |
| Dell          | Vostro 3550                 | [653c3c4650](https://linux-hardware.org/?probe=653c3c4650) | Apr 25, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [afcce1c52c](https://linux-hardware.org/?probe=afcce1c52c) | Apr 25, 2023 |
| Dell          | G3 3500                     | [46996524d0](https://linux-hardware.org/?probe=46996524d0) | Apr 25, 2023 |
| Purism        | Librem 14                   | [8462dbaccb](https://linux-hardware.org/?probe=8462dbaccb) | Apr 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [1b26b3f89b](https://linux-hardware.org/?probe=1b26b3f89b) | Apr 24, 2023 |
| Notebook      | N85_N87HCHNHZ               | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| Dell          | Vostro 15 3515              | [13c75fa32e](https://linux-hardware.org/?probe=13c75fa32e) | Apr 24, 2023 |
| Apple         | MacBookPro8,1               | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Gateway       | NV55C                       | [3c560a28cf](https://linux-hardware.org/?probe=3c560a28cf) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2e7585d261](https://linux-hardware.org/?probe=2e7585d261) | Apr 24, 2023 |
| Dell          | Inspiron 11-3168            | [5ac6392b05](https://linux-hardware.org/?probe=5ac6392b05) | Apr 24, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e562ba35c6](https://linux-hardware.org/?probe=e562ba35c6) | Apr 23, 2023 |
| Dell          | G15 5520                    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| HP            | G42                         | [1d5b2eefc3](https://linux-hardware.org/?probe=1d5b2eefc3) | Apr 23, 2023 |
| ASUSTek       | X45C                        | [759ed58d76](https://linux-hardware.org/?probe=759ed58d76) | Apr 23, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [90b7213592](https://linux-hardware.org/?probe=90b7213592) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9a92345b08](https://linux-hardware.org/?probe=9a92345b08) | Apr 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0e798db6a8](https://linux-hardware.org/?probe=0e798db6a8) | Apr 23, 2023 |
| Dell          | G15 5520                    | [238c8f53aa](https://linux-hardware.org/?probe=238c8f53aa) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [8bb0353706](https://linux-hardware.org/?probe=8bb0353706) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [b699c8ed48](https://linux-hardware.org/?probe=b699c8ed48) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [f5c282ca6c](https://linux-hardware.org/?probe=f5c282ca6c) | Apr 22, 2023 |
| Dell          | G15 5520                    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| Acer          | Nitro AN515-54              | [452177f9a5](https://linux-hardware.org/?probe=452177f9a5) | Apr 21, 2023 |
| Digibras      | NH4CU53                     | [d6571e3d78](https://linux-hardware.org/?probe=d6571e3d78) | Apr 21, 2023 |
| Multilaser    | PC13X                       | [d1144e31a1](https://linux-hardware.org/?probe=d1144e31a1) | Apr 21, 2023 |
| Positivo      | N6440                       | [b0a1fe417d](https://linux-hardware.org/?probe=b0a1fe417d) | Apr 21, 2023 |
| Dell          | Inspiron 3501               | [e09f00bead](https://linux-hardware.org/?probe=e09f00bead) | Apr 20, 2023 |
| HP            | Pavilion g4                 | [96a0210940](https://linux-hardware.org/?probe=96a0210940) | Apr 20, 2023 |
| Dell          | XPS 13 9310                 | [55685c168f](https://linux-hardware.org/?probe=55685c168f) | Apr 20, 2023 |
| Samsung       | 550P5C/550P7C               | [3648dd39f8](https://linux-hardware.org/?probe=3648dd39f8) | Apr 20, 2023 |
| Dell          | Inspiron 7460               | [bbfe51bf3c](https://linux-hardware.org/?probe=bbfe51bf3c) | Apr 19, 2023 |
| Acer          | AO722                       | [5fe24a9991](https://linux-hardware.org/?probe=5fe24a9991) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [e492c87b46](https://linux-hardware.org/?probe=e492c87b46) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [b15f47258b](https://linux-hardware.org/?probe=b15f47258b) | Apr 18, 2023 |
| Dell          | Vostro 3480                 | [f2f48756e6](https://linux-hardware.org/?probe=f2f48756e6) | Apr 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [90c4ba9f6e](https://linux-hardware.org/?probe=90c4ba9f6e) | Apr 17, 2023 |
| HP            | 240 G4 Notebook PC          | [6410232c86](https://linux-hardware.org/?probe=6410232c86) | Apr 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [961e1f1908](https://linux-hardware.org/?probe=961e1f1908) | Apr 17, 2023 |
| Avell High... | A70 MOB                     | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Dell          | Inspiron 5566               | [5e9ebca163](https://linux-hardware.org/?probe=5e9ebca163) | Apr 17, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [acd0161868](https://linux-hardware.org/?probe=acd0161868) | Apr 17, 2023 |
| Multilaser    | PC13X                       | [3b755838a2](https://linux-hardware.org/?probe=3b755838a2) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| HP            | 240 G2                      | [ca6ae60a2b](https://linux-hardware.org/?probe=ca6ae60a2b) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [482a8c29cc](https://linux-hardware.org/?probe=482a8c29cc) | Apr 16, 2023 |
| Valve         | Jupiter                     | [6c83afd9b3](https://linux-hardware.org/?probe=6c83afd9b3) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Aspire A515-45              | [5ce7874f2e](https://linux-hardware.org/?probe=5ce7874f2e) | Apr 16, 2023 |
| Itautec       | Infoway                     | [c046d6e093](https://linux-hardware.org/?probe=c046d6e093) | Apr 16, 2023 |
| Positivo      | C14CR01                     | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f7cf140a28](https://linux-hardware.org/?probe=f7cf140a28) | Apr 16, 2023 |
| Acer          | Nitro AN515-54              | [73c46e2901](https://linux-hardware.org/?probe=73c46e2901) | Apr 15, 2023 |
| Dell          | Inspiron 5566               | [3decfdc1f6](https://linux-hardware.org/?probe=3decfdc1f6) | Apr 15, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [dfed605628](https://linux-hardware.org/?probe=dfed605628) | Apr 15, 2023 |
| Dell          | Inspiron 7460               | [ae861b54cd](https://linux-hardware.org/?probe=ae861b54cd) | Apr 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| Avell High... | B.ON                        | [0ac252a73b](https://linux-hardware.org/?probe=0ac252a73b) | Apr 14, 2023 |
| Positivo      | Q4128C-S                    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| Samsung       | 670Z5E                      | [96bcf536e6](https://linux-hardware.org/?probe=96bcf536e6) | Apr 14, 2023 |
| Samsung       | 670Z5E                      | [dff09c0918](https://linux-hardware.org/?probe=dff09c0918) | Apr 14, 2023 |
| Acer          | Nitro AN515-54              | [07a2ba2393](https://linux-hardware.org/?probe=07a2ba2393) | Apr 13, 2023 |
| Dell          | Inspiron 5515               | [e7306b2521](https://linux-hardware.org/?probe=e7306b2521) | Apr 13, 2023 |
| Dell          | Inspiron 15-3567            | [c200475e1f](https://linux-hardware.org/?probe=c200475e1f) | Apr 13, 2023 |
| Acer          | Aspire A515-54G             | [eedb55e1ba](https://linux-hardware.org/?probe=eedb55e1ba) | Apr 13, 2023 |
| Dell          | Inspiron 15-3567            | [ae928fe177](https://linux-hardware.org/?probe=ae928fe177) | Apr 13, 2023 |
| Toshiba       | IS 1413G                    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Positivo      | H14SU08                     | [8e8d14728f](https://linux-hardware.org/?probe=8e8d14728f) | Apr 13, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c53ec6a9c0](https://linux-hardware.org/?probe=c53ec6a9c0) | Apr 13, 2023 |
| Positivo      | Q4128C-S                    | [a46ba9bff2](https://linux-hardware.org/?probe=a46ba9bff2) | Apr 12, 2023 |
| Positivo      | Q4128C-S                    | [3b5a11f774](https://linux-hardware.org/?probe=3b5a11f774) | Apr 12, 2023 |
| Intel         | powered classmate PC        | [79b262de52](https://linux-hardware.org/?probe=79b262de52) | Apr 12, 2023 |
| Acer          | Nitro AN515-44              | [12ca37afd3](https://linux-hardware.org/?probe=12ca37afd3) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Dell          | G3 3579                     | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Samsung       | 550XCJ/550XCR               | [c074d665d9](https://linux-hardware.org/?probe=c074d665d9) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [845a04c326](https://linux-hardware.org/?probe=845a04c326) | Apr 11, 2023 |
| Intel         | W7650                       | [3e4c54a5f0](https://linux-hardware.org/?probe=3e4c54a5f0) | Apr 11, 2023 |
| HP            | Unknown                     | [abc7d95b62](https://linux-hardware.org/?probe=abc7d95b62) | Apr 11, 2023 |
| Acer          | Aspire E5-471               | [6e44530b23](https://linux-hardware.org/?probe=6e44530b23) | Apr 11, 2023 |
| HP            | 250 G8 Notebook PC          | [a60609df80](https://linux-hardware.org/?probe=a60609df80) | Apr 11, 2023 |
| Acer          | Aspire A515-57              | [f577606375](https://linux-hardware.org/?probe=f577606375) | Apr 11, 2023 |
| Acer          | Aspire E5-471               | [dbcbf972e5](https://linux-hardware.org/?probe=dbcbf972e5) | Apr 11, 2023 |
| Dell          | Inspiron N5110              | [4506c94bfd](https://linux-hardware.org/?probe=4506c94bfd) | Apr 11, 2023 |
| Avell High... | A52 HYB                     | [0795bca947](https://linux-hardware.org/?probe=0795bca947) | Apr 11, 2023 |
| Samsung       | 550XDA                      | [e1d5d2f193](https://linux-hardware.org/?probe=e1d5d2f193) | Apr 11, 2023 |
| Acer          | Aspire E5-511               | [f66d23c175](https://linux-hardware.org/?probe=f66d23c175) | Apr 10, 2023 |
| Dell          | Inspiron 3583               | [502c993dfd](https://linux-hardware.org/?probe=502c993dfd) | Apr 10, 2023 |
| Notebook      | NJx0MU                      | [2bb9767ca7](https://linux-hardware.org/?probe=2bb9767ca7) | Apr 10, 2023 |
| Notebook      | NJx0MU                      | [681be67c93](https://linux-hardware.org/?probe=681be67c93) | Apr 09, 2023 |
| Acer          | Aspire 5538                 | [3128c45dbc](https://linux-hardware.org/?probe=3128c45dbc) | Apr 09, 2023 |
| Samsung       | RV419                       | [88985a3d0d](https://linux-hardware.org/?probe=88985a3d0d) | Apr 09, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | [779e8396d6](https://linux-hardware.org/?probe=779e8396d6) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [19fd2b6d0d](https://linux-hardware.org/?probe=19fd2b6d0d) | Apr 09, 2023 |
| Toshiba       | IS 1413G                    | [be9d1636a7](https://linux-hardware.org/?probe=be9d1636a7) | Apr 09, 2023 |
| Dell          | Inspiron N5110              | [6514811aaf](https://linux-hardware.org/?probe=6514811aaf) | Apr 09, 2023 |
| Avell High... | A52 HYB                     | [7da3b9f780](https://linux-hardware.org/?probe=7da3b9f780) | Apr 09, 2023 |
| Acer          | Aspire A515-57              | [e04fc7e8e8](https://linux-hardware.org/?probe=e04fc7e8e8) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [bc402eee2e](https://linux-hardware.org/?probe=bc402eee2e) | Apr 09, 2023 |
| HP            | ProBook 6470b               | [9926dac4aa](https://linux-hardware.org/?probe=9926dac4aa) | Apr 08, 2023 |
| Acer          | Aspire A515-51G             | [34d03fbbcd](https://linux-hardware.org/?probe=34d03fbbcd) | Apr 08, 2023 |
| Sony          | VJF155F11X-B0811B           | [89f9cc86a7](https://linux-hardware.org/?probe=89f9cc86a7) | Apr 08, 2023 |
| MSI           | Katana GF76 11UD            | [6f9a54256f](https://linux-hardware.org/?probe=6f9a54256f) | Apr 07, 2023 |
| Acer          | Aspire 5517                 | [bbedb2d88e](https://linux-hardware.org/?probe=bbedb2d88e) | Apr 07, 2023 |
| HP            | EliteBook 2530p             | [66ec38445f](https://linux-hardware.org/?probe=66ec38445f) | Apr 07, 2023 |
| Acer          | Aspire A515-52              | [3d9e5a4546](https://linux-hardware.org/?probe=3d9e5a4546) | Apr 07, 2023 |
| Positivo      | H14BT58                     | [135bb6e61a](https://linux-hardware.org/?probe=135bb6e61a) | Apr 06, 2023 |
| Dell          | Inspiron 3584               | [50f052ef1c](https://linux-hardware.org/?probe=50f052ef1c) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cd6431fbf5](https://linux-hardware.org/?probe=cd6431fbf5) | Apr 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBC... | [f4dd5b1a73](https://linux-hardware.org/?probe=f4dd5b1a73) | Apr 05, 2023 |
| Multilaser    | PC13X                       | [85579abbc9](https://linux-hardware.org/?probe=85579abbc9) | Apr 05, 2023 |
| Evolute       | B14HM21                     | [be41163512](https://linux-hardware.org/?probe=be41163512) | Apr 05, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | [473898ff0e](https://linux-hardware.org/?probe=473898ff0e) | Apr 04, 2023 |
| Acer          | Aspire 4349                 | [43ae04b9c3](https://linux-hardware.org/?probe=43ae04b9c3) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| Samsung       | 767XCL                      | [b5a44d9194](https://linux-hardware.org/?probe=b5a44d9194) | Apr 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [777f7d0fc4](https://linux-hardware.org/?probe=777f7d0fc4) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8a7681ab18](https://linux-hardware.org/?probe=8a7681ab18) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Timi          | RedmiBook Pro 14S           | [e3eb0fe882](https://linux-hardware.org/?probe=e3eb0fe882) | Apr 02, 2023 |
| Samsung       | 550P5C/550P7C               | [8e6191f4bb](https://linux-hardware.org/?probe=8e6191f4bb) | Apr 02, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [e42bc1dd05](https://linux-hardware.org/?probe=e42bc1dd05) | Apr 02, 2023 |
| ASUSTek       | X451CA                      | [81002767d0](https://linux-hardware.org/?probe=81002767d0) | Apr 02, 2023 |
| Multilaser    | PC150                       | [0bcb0ca7ba](https://linux-hardware.org/?probe=0bcb0ca7ba) | Apr 02, 2023 |
| Toshiba       | IS 1413G                    | [76a94d8c87](https://linux-hardware.org/?probe=76a94d8c87) | Apr 02, 2023 |
| Alienware     | m15 R7                      | [68b2947cdb](https://linux-hardware.org/?probe=68b2947cdb) | Apr 02, 2023 |
| Dell          | Latitude E5400              | [4b69d7d67c](https://linux-hardware.org/?probe=4b69d7d67c) | Apr 02, 2023 |
| Dell          | Inspiron 5458               | [38b9db2538](https://linux-hardware.org/?probe=38b9db2538) | Apr 01, 2023 |
| Samsung       | 767XCL                      | [a3167908c0](https://linux-hardware.org/?probe=a3167908c0) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | [207edc0a25](https://linux-hardware.org/?probe=207edc0a25) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | [14751f18b3](https://linux-hardware.org/?probe=14751f18b3) | Apr 01, 2023 |
| Itautec       | Infoway w7535               | [48a539f108](https://linux-hardware.org/?probe=48a539f108) | Apr 01, 2023 |
| Valve         | Jupiter                     | [816e9cb6f6](https://linux-hardware.org/?probe=816e9cb6f6) | Apr 01, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [93ef0bb287](https://linux-hardware.org/?probe=93ef0bb287) | Apr 01, 2023 |
| Samsung       | 270E5G/270E5U               | [67b91e463a](https://linux-hardware.org/?probe=67b91e463a) | Mar 31, 2023 |
| Acer          | Aspire A315-54K             | [d325177071](https://linux-hardware.org/?probe=d325177071) | Mar 31, 2023 |
| Positivo      | S14CT01                     | [a47919fcc4](https://linux-hardware.org/?probe=a47919fcc4) | Mar 31, 2023 |
| Quanta        | QL3 TBD                     | [21673aecac](https://linux-hardware.org/?probe=21673aecac) | Mar 31, 2023 |
| Dell          | Vostro V131                 | [53538c2ae9](https://linux-hardware.org/?probe=53538c2ae9) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7597a96654](https://linux-hardware.org/?probe=7597a96654) | Mar 31, 2023 |
| Dell          | Inspiron 5567               | [fe5578a96e](https://linux-hardware.org/?probe=fe5578a96e) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| Acer          | Aspire A515-56              | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Positivo      | S14SL01                     | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| Acer          | Prespa M                    | [a6541a27d9](https://linux-hardware.org/?probe=a6541a27d9) | Mar 30, 2023 |
| Dell          | Vostro 5402                 | [27b9c84cbe](https://linux-hardware.org/?probe=27b9c84cbe) | Mar 30, 2023 |
| Dell          | Inspiron 3421               | [5418efd855](https://linux-hardware.org/?probe=5418efd855) | Mar 30, 2023 |
| Lenovo        | Yoga 510-14ISK 80UK         | [722c1e9d68](https://linux-hardware.org/?probe=722c1e9d68) | Mar 30, 2023 |
| Dell          | Latitude 3490               | [16d4f0954b](https://linux-hardware.org/?probe=16d4f0954b) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Dell          | Vostro 3480                 | [83cb13ffb4](https://linux-hardware.org/?probe=83cb13ffb4) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| Apple         | MacBookAir9,1               | [1fe20bdfcb](https://linux-hardware.org/?probe=1fe20bdfcb) | Mar 30, 2023 |
| Positivo      | Q232A                       | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Dell          | Inspiron 5566               | [7b53b4da78](https://linux-hardware.org/?probe=7b53b4da78) | Mar 29, 2023 |
| Positivo      | Q232A                       | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| ASUSTek       | X751LJ                      | [cf5d71e2b3](https://linux-hardware.org/?probe=cf5d71e2b3) | Mar 29, 2023 |
| Samsung       | 370E4K                      | [68e9294ac9](https://linux-hardware.org/?probe=68e9294ac9) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| Samsung       | 670Z5E                      | [2bf528dfb1](https://linux-hardware.org/?probe=2bf528dfb1) | Mar 29, 2023 |
| Samsung       | 300E5M/300E5L               | [9d48f53259](https://linux-hardware.org/?probe=9d48f53259) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Dell          | Inspiron 7520               | [8258074853](https://linux-hardware.org/?probe=8258074853) | Mar 28, 2023 |
| HP            | Compaq Presario CQ40        | [7f2e65257c](https://linux-hardware.org/?probe=7f2e65257c) | Mar 28, 2023 |
| HP            | Compaq Presario CQ40        | [9ee954843e](https://linux-hardware.org/?probe=9ee954843e) | Mar 28, 2023 |
| Positivo      | Mobile                      | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Dell          | Vostro 14-5480              | [b1ef6303a6](https://linux-hardware.org/?probe=b1ef6303a6) | Mar 28, 2023 |
| Positivo      | Mobile                      | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| Dell          | G3 3579                     | [55b5db4326](https://linux-hardware.org/?probe=55b5db4326) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| Notebook      | NJx0MU                      | [bd4eec08fb](https://linux-hardware.org/?probe=bd4eec08fb) | Mar 27, 2023 |
| Dell          | Inspiron 5448               | [b800b24cbd](https://linux-hardware.org/?probe=b800b24cbd) | Mar 27, 2023 |
| Dell          | G15 5515                    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| Acer          | Aspire A515-41G             | [33bccb2234](https://linux-hardware.org/?probe=33bccb2234) | Mar 27, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| Positivo      | Smash2                      | [b61791c478](https://linux-hardware.org/?probe=b61791c478) | Mar 26, 2023 |
| MSI           | CR620                       | [2fce81cc28](https://linux-hardware.org/?probe=2fce81cc28) | Mar 26, 2023 |
| Notebook      | NJx0MU                      | [5a95cd6ad5](https://linux-hardware.org/?probe=5a95cd6ad5) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | [5c3f0186de](https://linux-hardware.org/?probe=5c3f0186de) | Mar 26, 2023 |
| Dell          | G3 3590                     | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| Sony          | SVF14215CXB                 | [624af23eb4](https://linux-hardware.org/?probe=624af23eb4) | Mar 26, 2023 |
| Acer          | Nitro AN515-54              | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| Samsung       | 550XDA                      | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2df4a612b4](https://linux-hardware.org/?probe=2df4a612b4) | Mar 25, 2023 |
| Acer          | Aspire 4740                 | [c4e47e53dc](https://linux-hardware.org/?probe=c4e47e53dc) | Mar 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [27ff485a92](https://linux-hardware.org/?probe=27ff485a92) | Mar 25, 2023 |
| Acer          | Aspire ES1-411              | [1a4caa9a83](https://linux-hardware.org/?probe=1a4caa9a83) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a9ffd21a7f](https://linux-hardware.org/?probe=a9ffd21a7f) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [9e55d83acd](https://linux-hardware.org/?probe=9e55d83acd) | Mar 23, 2023 |
| Samsung       | 530XBB                      | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| Avell High... | B.ON                        | [0fe36e1e74](https://linux-hardware.org/?probe=0fe36e1e74) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| Lenovo        | ThinkPad L450 20DSA25V01    | [68b1ae2c5d](https://linux-hardware.org/?probe=68b1ae2c5d) | Mar 23, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [64c4a47e0e](https://linux-hardware.org/?probe=64c4a47e0e) | Mar 23, 2023 |
| Acer          | Nitro AN515-44              | [fca39bd9eb](https://linux-hardware.org/?probe=fca39bd9eb) | Mar 22, 2023 |
| Samsung       | 550XDA                      | [b145c438d7](https://linux-hardware.org/?probe=b145c438d7) | Mar 22, 2023 |
| Acer          | Nitro AN515-44              | [e07e3320b1](https://linux-hardware.org/?probe=e07e3320b1) | Mar 22, 2023 |
| Acer          | Nitro AN517-54              | [ebe6cc115e](https://linux-hardware.org/?probe=ebe6cc115e) | Mar 22, 2023 |
| HP            | Pavilion dv4                | [20adc36857](https://linux-hardware.org/?probe=20adc36857) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1165b3734c](https://linux-hardware.org/?probe=1165b3734c) | Mar 21, 2023 |
| Avell High... | A62 LIV                     | [14dab05208](https://linux-hardware.org/?probe=14dab05208) | Mar 21, 2023 |
| Toshiba       | Satellite A305              | [ed7bc92488](https://linux-hardware.org/?probe=ed7bc92488) | Mar 21, 2023 |
| Dell          | Vostro 14-5480              | [ee892df403](https://linux-hardware.org/?probe=ee892df403) | Mar 21, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [b6b5eb415f](https://linux-hardware.org/?probe=b6b5eb415f) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 927       | 11.2%   |
| Ubuntu 18.04       | 598       | 7.23%   |
| Ubuntu 22.04       | 323       | 3.9%    |
| Pop!_OS 20.04      | 194       | 2.34%   |
| Linux Mint 20      | 189       | 2.28%   |
| Linux Mint 19.3    | 166       | 2.01%   |
| OpenMandriva 4.2   | 158       | 1.91%   |
| Pop!_OS 22.04      | 151       | 1.82%   |
| OpenMandriva 4.3   | 151       | 1.82%   |
| Linux Mint 20.3    | 143       | 1.73%   |
| Manjaro            | 134       | 1.62%   |
| Linux Mint 19.1    | 122       | 1.47%   |
| Zorin 16           | 120       | 1.45%   |
| Linux Mint 20.1    | 120       | 1.45%   |
| Ubuntu 19.04       | 117       | 1.41%   |
| Arch               | 114       | 1.38%   |
| Linux Mint 20.2    | 113       | 1.37%   |
| KDE neon 20.04     | 113       | 1.37%   |
| Debian 11          | 112       | 1.35%   |
| Ubuntu 19.10       | 106       | 1.28%   |
| Arch Rolling       | 97        | 1.17%   |
| Zorin 15           | 94        | 1.14%   |
| Linux Mint 21.1    | 90        | 1.09%   |
| Debian 10          | 83        | 1%      |
| Fedora 35          | 80        | 0.97%   |
| Fedora 38          | 79        | 0.95%   |
| Fedora 34          | 73        | 0.88%   |
| Pop!_OS 21.10      | 71        | 0.86%   |
| Fedora 37          | 71        | 0.86%   |
| Fedora 32          | 69        | 0.83%   |
| Endless 3.7.8      | 69        | 0.83%   |
| Xubuntu 20.04      | 68        | 0.82%   |
| OpenMandriva 23.01 | 68        | 0.82%   |
| Fedora 36          | 68        | 0.82%   |
| Pop!_OS 21.04      | 67        | 0.81%   |
| Endless 3.9.5      | 67        | 0.81%   |
| Kubuntu 20.04      | 62        | 0.75%   |
| Pop!_OS 20.10      | 60        | 0.73%   |
| Fedora 33          | 60        | 0.73%   |
| Linux Mint 21      | 58        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2280      | 28.93%  |
| Linux Mint    | 1037      | 13.16%  |
| Endless       | 880       | 11.17%  |
| Pop!_OS       | 524       | 6.65%   |
| Fedora        | 513       | 6.51%   |
| OpenMandriva  | 451       | 5.72%   |
| Debian        | 267       | 3.39%   |
| Manjaro       | 239       | 3.03%   |
| Zorin         | 218       | 2.77%   |
| Arch          | 201       | 2.55%   |
| KDE neon      | 153       | 1.94%   |
| Xubuntu       | 128       | 1.62%   |
| Kubuntu       | 126       | 1.6%    |
| openSUSE      | 75        | 0.95%   |
| Lubuntu       | 75        | 0.95%   |
| Elementary    | 66        | 0.84%   |
| Ubuntu MATE   | 63        | 0.8%    |
| ROSA          | 56        | 0.71%   |
| Ubuntu Unity  | 53        | 0.67%   |
| Kali          | 50        | 0.63%   |
| LMDE          | 39        | 0.49%   |
| ArcoLinux     | 32        | 0.41%   |
| Deepin        | 31        | 0.39%   |
| Ubuntu Budgie | 28        | 0.36%   |
| Clear Linux   | 26        | 0.33%   |
| BigLinux      | 24        | 0.3%    |
| LinuxFX       | 21        | 0.27%   |
| EndeavourOS   | 18        | 0.23%   |
| SteamOS       | 11        | 0.14%   |
| Parrot        | 11        | 0.14%   |
| BlackPanther  | 11        | 0.14%   |
| Reborn OS     | 10        | 0.13%   |
| Garuda Linux  | 10        | 0.13%   |
| CentOS        | 10        | 0.13%   |
| Nobara        | 9         | 0.11%   |
| UbuntuDDE     | 8         | 0.1%    |
| Peppermint    | 8         | 0.1%    |
| MX            | 8         | 0.1%    |
| Gentoo        | 8         | 0.1%    |
| Solus         | 7         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 471       | 5.3%    |
| 5.8.0-14-generic         | 291       | 3.27%   |
| 5.10.14-desktop-1omv4002 | 152       | 1.71%   |
| 5.16.7-desktop-1omv4003  | 144       | 1.62%   |
| 5.4.0-19-generic         | 114       | 1.28%   |
| 5.3.0-28-generic         | 108       | 1.21%   |
| 5.11.0-35-generic        | 96        | 1.08%   |
| 5.15.0-56-generic        | 76        | 0.85%   |
| 5.4.0-7634-generic       | 74        | 0.83%   |
| 5.4.0-48-generic         | 72        | 0.81%   |
| 5.4.0-40-generic         | 70        | 0.79%   |
| 4.15.0-46-generic        | 70        | 0.79%   |
| 6.1.1-desktop-1omv2290   | 66        | 0.74%   |
| 5.4.0-26-generic         | 64        | 0.72%   |
| 5.4.0-58-generic         | 61        | 0.69%   |
| 5.4.0-52-generic         | 57        | 0.64%   |
| 5.4.0-47-generic         | 54        | 0.61%   |
| 5.3.0-19-generic         | 50        | 0.56%   |
| 6.2.6-desktop-1omv2390   | 49        | 0.55%   |
| 5.3.0-23-generic         | 47        | 0.53%   |
| 5.3.0-46-generic         | 46        | 0.52%   |
| 5.0.0-32-generic         | 46        | 0.52%   |
| 5.4.0-29-generic         | 44        | 0.49%   |
| 4.18.0-15-generic        | 44        | 0.49%   |
| 5.3.0-40-generic         | 43        | 0.48%   |
| 5.4.0-65-generic         | 42        | 0.47%   |
| 5.15.0-47-generic        | 42        | 0.47%   |
| 5.4.0-39-generic         | 41        | 0.46%   |
| 5.15.0-52-generic        | 41        | 0.46%   |
| 5.15.0-46-generic        | 41        | 0.46%   |
| 5.0.0-37-generic         | 41        | 0.46%   |
| 5.4.0-80-generic         | 40        | 0.45%   |
| 5.4.0-70-generic         | 39        | 0.44%   |
| 5.0.0-25-generic         | 39        | 0.44%   |
| 5.15.0-58-generic        | 38        | 0.43%   |
| 5.13.0-30-generic        | 38        | 0.43%   |
| 5.11.0-7620-generic      | 38        | 0.43%   |
| 4.18.0-16-generic        | 38        | 0.43%   |
| 5.4.0-91-generic         | 37        | 0.42%   |
| 5.4.0-37-generic         | 37        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 1852      | 21.93%  |
| 5.8.0   | 625       | 7.4%    |
| 5.15.0  | 568       | 6.73%   |
| 5.3.0   | 535       | 6.34%   |
| 4.15.0  | 517       | 6.12%   |
| 5.11.0  | 442       | 5.23%   |
| 5.0.0   | 320       | 3.79%   |
| 5.13.0  | 277       | 3.28%   |
| 4.18.0  | 232       | 2.75%   |
| 5.19.0  | 205       | 2.43%   |
| 5.10.14 | 154       | 1.82%   |
| 5.10.0  | 152       | 1.8%    |
| 5.16.7  | 144       | 1.71%   |
| 4.19.0  | 101       | 1.2%    |
| 6.2.6   | 86        | 1.02%   |
| 6.1.1   | 73        | 0.86%   |
| 6.2.0   | 51        | 0.6%    |
| 6.1.0   | 42        | 0.5%    |
| 5.17.5  | 35        | 0.41%   |
| 6.0.12  | 32        | 0.38%   |
| 5.16.11 | 30        | 0.36%   |
| 5.14.0  | 28        | 0.33%   |
| 4.4.0   | 27        | 0.32%   |
| 5.7.9   | 26        | 0.31%   |
| 4.9.0   | 23        | 0.27%   |
| 5.15.15 | 20        | 0.24%   |
| 5.15.5  | 19        | 0.23%   |
| 6.2.15  | 17        | 0.2%    |
| 6.0.0   | 17        | 0.2%    |
| 5.9.16  | 17        | 0.2%    |
| 5.7.0   | 17        | 0.2%    |
| 5.6.19  | 16        | 0.19%   |
| 5.16.19 | 16        | 0.19%   |
| 5.11.12 | 16        | 0.19%   |
| 5.3.18  | 15        | 0.18%   |
| 5.18.10 | 15        | 0.18%   |
| 5.16.15 | 15        | 0.18%   |
| 5.17.0  | 14        | 0.17%   |
| 6.2.11  | 13        | 0.15%   |
| 5.9.11  | 13        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1925      | 23.08%  |
| 5.15    | 739       | 8.86%   |
| 5.8     | 694       | 8.32%   |
| 5.3     | 579       | 6.94%   |
| 4.15    | 517       | 6.2%    |
| 5.11    | 509       | 6.1%    |
| 5.10    | 411       | 4.93%   |
| 5.0     | 345       | 4.14%   |
| 5.13    | 332       | 3.98%   |
| 5.16    | 272       | 3.26%   |
| 5.19    | 250       | 3%      |
| 4.18    | 248       | 2.97%   |
| 6.2     | 229       | 2.75%   |
| 6.1     | 210       | 2.52%   |
| 4.19    | 118       | 1.42%   |
| 6.0     | 112       | 1.34%   |
| 5.7     | 101       | 1.21%   |
| 5.17    | 98        | 1.18%   |
| 5.14    | 89        | 1.07%   |
| 5.18    | 78        | 0.94%   |
| 5.6     | 68        | 0.82%   |
| 5.9     | 66        | 0.79%   |
| 5.12    | 61        | 0.73%   |
| 6.3     | 58        | 0.7%    |
| 4.9     | 47        | 0.56%   |
| 6.4     | 45        | 0.54%   |
| 5.5     | 32        | 0.38%   |
| 4.4     | 30        | 0.36%   |
| 5.1     | 28        | 0.34%   |
| 5.2     | 15        | 0.18%   |
| 4.13    | 7         | 0.08%   |
| 4.20    | 5         | 0.06%   |
| 4.14    | 4         | 0.05%   |
| 4.10    | 4         | 0.05%   |
| 4.1     | 4         | 0.05%   |
| 3.10    | 3         | 0.04%   |
| 4.17    | 2         | 0.02%   |
| 6       | 1         | 0.01%   |
| 4.8     | 1         | 0.01%   |
| 4.12    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 7333      | 97.63%  |
| i686   | 176       | 2.34%   |
| armv7l | 2         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3912      | 49.9%   |
| Unknown         | 988       | 12.6%   |
| KDE5            | 917       | 11.7%   |
| X-Cinnamon      | 629       | 8.02%   |
| XFCE            | 506       | 6.45%   |
| MATE            | 199       | 2.54%   |
| KDE             | 160       | 2.04%   |
| Cinnamon        | 136       | 1.73%   |
| LXQt            | 78        | 0.99%   |
| Pantheon        | 59        | 0.75%   |
| Unity           | 55        | 0.7%    |
| Deepin          | 42        | 0.54%   |
| Budgie          | 39        | 0.5%    |
| LXDE            | 34        | 0.43%   |
| KDE4            | 25        | 0.32%   |
| i3              | 22        | 0.28%   |
| GNOME Classic   | 10        | 0.13%   |
| sway            | 5         | 0.06%   |
| awesome         | 5         | 0.06%   |
| Hyprland        | 4         | 0.05%   |
| GNOME Flashback | 3         | 0.04%   |
| Openbox         | 2         | 0.03%   |
| Enlightenment   | 2         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| icewm           | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| GNOME-Classic   | 1         | 0.01%   |
| fluxbox         | 1         | 0.01%   |
| bspwm           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 6223      | 80.55%  |
| Wayland | 965       | 12.49%  |
| Unknown | 505       | 6.54%   |
| Tty     | 33        | 0.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4903      | 62.71%  |
| GDM     | 793       | 10.14%  |
| SDDM    | 790       | 10.1%   |
| GDM3    | 572       | 7.32%   |
| LightDM | 430       | 5.5%    |
| TDM     | 292       | 3.73%   |
| KDM     | 26        | 0.33%   |
| XDM     | 6         | 0.08%   |
| SLiM    | 4         | 0.05%   |
| MDM     | 1         | 0.01%   |
| Ly      | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang      | Notebooks | Percent |
|-----------|-----------|---------|
| pt_BR     | 5140      | 66.97%  |
| en_US     | 1390      | 18.11%  |
| Unknown   | 916       | 11.93%  |
| C         | 110       | 1.43%   |
| en_GB     | 41        | 0.53%   |
| pt_PT     | 31        | 0.4%    |
| es_ES     | 13        | 0.17%   |
| en_CA     | 6         | 0.08%   |
| fr_FR     | 5         | 0.07%   |
| POSIX     | 3         | 0.04%   |
| de_DE     | 3         | 0.04%   |
| ja_JP     | 2         | 0.03%   |
| it_IT     | 2         | 0.03%   |
| ru_RU     | 1         | 0.01%   |
| pt_BR~    | 1         | 0.01%   |
| pt_BRutf8 | 1         | 0.01%   |
| es_PY     | 1         | 0.01%   |
| es_MX     | 1         | 0.01%   |
| es_CL     | 1         | 0.01%   |
| es_AR     | 1         | 0.01%   |
| en_DK     | 1         | 0.01%   |
| en-US     | 1         | 0.01%   |
| em_US     | 1         | 0.01%   |
| de_CH     | 1         | 0.01%   |
| C.UTF8    | 1         | 0.01%   |
| ar_EG     | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3870      | 50.25%  |
| BIOS | 3831      | 49.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5986      | 77.61%  |
| Btrfs   | 616       | 7.99%   |
| Overlay | 521       | 6.75%   |
| Unknown | 389       | 5.04%   |
| Tmpfs   | 86        | 1.12%   |
| Xfs     | 55        | 0.71%   |
| Zfs     | 27        | 0.35%   |
| Ext2    | 11        | 0.14%   |
| F2fs    | 10        | 0.13%   |
| Ext3    | 10        | 0.13%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5109      | 66.11%  |
| GPT     | 1913      | 24.75%  |
| MBR     | 706       | 9.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6894      | 90.75%  |
| Yes       | 703       | 9.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5963      | 78.18%  |
| Yes       | 1664      | 21.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 1724      | 22.96%  |
| Acer                   | 1454      | 19.36%  |
| Lenovo                 | 951       | 12.66%  |
| Samsung Electronics    | 625       | 8.32%   |
| Hewlett-Packard        | 510       | 6.79%   |
| Positivo               | 494       | 6.58%   |
| ASUSTek Computer       | 427       | 5.69%   |
| Sony                   | 158       | 2.1%    |
| Apple                  | 101       | 1.34%   |
| LG Electronics         | 96        | 1.28%   |
| Avell High Performance | 89        | 1.19%   |
| Itautec                | 72        | 0.96%   |
| Digibras               | 71        | 0.95%   |
| Unknown                | 68        | 0.91%   |
| Semp Toshiba           | 66        | 0.88%   |
| Intel                  | 52        | 0.69%   |
| Multilaser             | 45        | 0.6%    |
| Compaq                 | 43        | 0.57%   |
| Philco                 | 41        | 0.55%   |
| Positivo Bahia - VAIO  | 38        | 0.51%   |
| Toshiba                | 36        | 0.48%   |
| OEM                    | 32        | 0.43%   |
| Notebook               | 28        | 0.37%   |
| Clevo                  | 25        | 0.33%   |
| Gateway                | 21        | 0.28%   |
| Compal                 | 19        | 0.25%   |
| Google                 | 18        | 0.24%   |
| MSI                    | 17        | 0.23%   |
| Alienware              | 15        | 0.2%    |
| eMachines              | 13        | 0.17%   |
| Quanta                 | 12        | 0.16%   |
| Standard               | 11        | 0.15%   |
| Timi                   | 10        | 0.13%   |
| Daten Tecnologia       | 10        | 0.13%   |
| Valve                  | 8         | 0.11%   |
| Chuwi                  | 8         | 0.11%   |
| CCE                    | 7         | 0.09%   |
| Login Informatica      | 6         | 0.08%   |
| LNV                    | 5         | 0.07%   |
| TPVAOC                 | 4         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                         | 138       | 1.84%   |
| Positivo Mobile                             | 124       | 1.65%   |
| Unknown                                     | 115       | 1.53%   |
| Acer Nitro AN515-44                         | 87        | 1.16%   |
| Acer Aspire A315-53                         | 69        | 0.92%   |
| Samsung 340XAA/350XAA/550XAA                | 68        | 0.91%   |
| Dell Inspiron 5566                          | 68        | 0.91%   |
| Lenovo IdeaPad S145-15API 81V7              | 64        | 0.85%   |
| Dell Inspiron 3583                          | 59        | 0.79%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 58        | 0.77%   |
| Dell Inspiron 15-3567                       | 58        | 0.77%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 56        | 0.75%   |
| Acer Aspire A315-34                         | 54        | 0.72%   |
| Acer Nitro AN517-51                         | 53        | 0.71%   |
| Acer Aspire A515-51                         | 51        | 0.68%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 49        | 0.65%   |
| Samsung 300E5M/300E5L                       | 47        | 0.63%   |
| Acer Nitro AN515-43                         | 46        | 0.61%   |
| Dell Inspiron 3442                          | 43        | 0.57%   |
| Samsung 550XDA                              | 42        | 0.56%   |
| HP G42                                      | 42        | 0.56%   |
| Positivo S14CT01                            | 41        | 0.55%   |
| Dell Inspiron N4050                         | 39        | 0.52%   |
| Acer Nitro AN515-52                         | 39        | 0.52%   |
| Dell Inspiron 3421                          | 38        | 0.51%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 37        | 0.49%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 34        | 0.45%   |
| HP Pavilion g4                              | 34        | 0.45%   |
| Digibras NH4CU03                            | 34        | 0.45%   |
| Dell Inspiron 7520                          | 34        | 0.45%   |
| Dell Inspiron 5458                          | 33        | 0.44%   |
| Acer Aspire E1-571                          | 33        | 0.44%   |
| Dell Inspiron 1545                          | 32        | 0.43%   |
| Dell Inspiron 1525                          | 32        | 0.43%   |
| Acer Aspire E5-571                          | 32        | 0.43%   |
| Itautec Infoway                             | 30        | 0.4%    |
| Dell G3 3590                                | 30        | 0.4%    |
| Acer Aspire A515-51G                        | 30        | 0.4%    |
| Dell Inspiron 5437                          | 29        | 0.39%   |
| ASUS VivoBook_ASUSLaptop X515DA_X515DA      | 29        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 1106      | 14.73%  |
| Acer Aspire       | 940       | 12.52%  |
| Lenovo IdeaPad    | 525       | 6.99%   |
| Acer Nitro        | 414       | 5.51%   |
| Dell Vostro       | 235       | 3.13%   |
| Lenovo ThinkPad   | 213       | 2.84%   |
| HP Pavilion       | 202       | 2.69%   |
| Dell Latitude     | 192       | 2.56%   |
| ASUS VivoBook     | 135       | 1.8%    |
| Positivo Mobile   | 124       | 1.65%   |
| Unknown           | 115       | 1.53%   |
| Itautec Infoway   | 72        | 0.96%   |
| Samsung 340XAA    | 68        | 0.91%   |
| Dell G3           | 60        | 0.8%    |
| HP ProBook        | 51        | 0.68%   |
| Samsung RV411     | 47        | 0.63%   |
| Samsung 300E5M    | 47        | 0.63%   |
| Samsung 550XDA    | 42        | 0.56%   |
| HP G42            | 42        | 0.56%   |
| Positivo S14CT01  | 41        | 0.55%   |
| Dell System       | 39        | 0.52%   |
| Acer Predator     | 38        | 0.51%   |
| HP EliteBook      | 37        | 0.49%   |
| Semp Toshiba IS   | 34        | 0.45%   |
| Digibras NH4CU03  | 34        | 0.45%   |
| HP Compaq         | 31        | 0.41%   |
| Toshiba Satellite | 29        | 0.39%   |
| Samsung 550XBE    | 28        | 0.37%   |
| Digibras NH4CU53  | 28        | 0.37%   |
| Compaq Presario   | 28        | 0.37%   |
| Dell G15          | 27        | 0.36%   |
| Samsung 370E4K    | 26        | 0.35%   |
| Samsung 270E5J    | 25        | 0.33%   |
| Lenovo G400s      | 25        | 0.33%   |
| Dell XPS          | 25        | 0.33%   |
| Samsung RV415     | 24        | 0.32%   |
| Samsung 300E5EV   | 24        | 0.32%   |
| Samsung 300E4C    | 24        | 0.32%   |
| Positivo Q232A    | 24        | 0.32%   |
| Positivo H14BT58  | 24        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 975       | 12.98%  |
| 2012    | 762       | 10.15%  |
| 2011    | 685       | 9.12%   |
| 2018    | 604       | 8.04%   |
| 2013    | 583       | 7.76%   |
| 2017    | 560       | 7.46%   |
| 2016    | 547       | 7.28%   |
| 2020    | 455       | 6.06%   |
| 2010    | 452       | 6.02%   |
| 2014    | 403       | 5.37%   |
| 2021    | 401       | 5.34%   |
| 2015    | 332       | 4.42%   |
| 2008    | 270       | 3.6%    |
| 2009    | 232       | 3.09%   |
| 2007    | 94        | 1.25%   |
| 2022    | 71        | 0.95%   |
| 2006    | 38        | 0.51%   |
| Unknown | 28        | 0.37%   |
| 2005    | 9         | 0.12%   |
| 2023    | 5         | 0.07%   |
| 2004    | 4         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7510      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6433      | 84.81%  |
| Enabled  | 1152      | 15.19%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7488      | 99.71%  |
| Yes  | 22        | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2506      | 32.83%  |
| 3.01-4.0    | 2087      | 27.34%  |
| 8.01-16.0   | 1057      | 13.85%  |
| 16.01-24.0  | 997       | 13.06%  |
| 1.01-2.0    | 548       | 7.18%   |
| 2.01-3.0    | 184       | 2.41%   |
| 32.01-64.0  | 152       | 1.99%   |
| 24.01-32.0  | 40        | 0.52%   |
| 0.51-1.0    | 34        | 0.45%   |
| 64.01-256.0 | 27        | 0.35%   |
| 0.01-0.5    | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3017      | 36.35%  |
| 2.01-3.0   | 2325      | 28.02%  |
| 3.01-4.0   | 1110      | 13.38%  |
| 4.01-8.0   | 1043      | 12.57%  |
| 0.51-1.0   | 544       | 6.56%   |
| 8.01-16.0  | 201       | 2.42%   |
| 0.01-0.5   | 41        | 0.49%   |
| 16.01-24.0 | 13        | 0.16%   |
| 32.01-64.0 | 3         | 0.04%   |
| Unknown    | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5354      | 69.94%  |
| 2      | 2074      | 27.09%  |
| 3      | 155       | 2.02%   |
| 0      | 56        | 0.73%   |
| 4      | 16        | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4703      | 62.3%   |
| Yes       | 2846      | 37.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6628      | 88.04%  |
| No        | 900       | 11.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7277      | 96.59%  |
| No        | 257       | 3.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5412      | 71.29%  |
| No        | 2180      | 28.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 7510      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 920       | 11.66%  |
| Rio de Janeiro        | 417       | 5.29%   |
| Brasília             | 252       | 3.19%   |
| Curitiba              | 231       | 2.93%   |
| Belo Horizonte        | 219       | 2.78%   |
| Fortaleza             | 184       | 2.33%   |
| Porto Alegre          | 166       | 2.1%    |
| Salvador              | 122       | 1.55%   |
| Campinas              | 118       | 1.5%    |
| Recife                | 104       | 1.32%   |
| Goiânia              | 92        | 1.17%   |
| Florianópolis        | 86        | 1.09%   |
| Santo André          | 85        | 1.08%   |
| Natal                 | 83        | 1.05%   |
| Osasco                | 68        | 0.86%   |
| Campo Grande          | 66        | 0.84%   |
| Manaus                | 65        | 0.82%   |
| Sao Luís             | 64        | 0.81%   |
| Sao José dos Campos  | 64        | 0.81%   |
| Joao Pessoa           | 59        | 0.75%   |
| Niterói              | 54        | 0.68%   |
| Teresina              | 52        | 0.66%   |
| Maringá              | 52        | 0.66%   |
| Belém                | 52        | 0.66%   |
| Guarulhos             | 50        | 0.63%   |
| Uberlândia           | 49        | 0.62%   |
| Sorocaba              | 49        | 0.62%   |
| Aracaju               | 49        | 0.62%   |
| Joinville             | 46        | 0.58%   |
| Ribeirao Preto        | 44        | 0.56%   |
| Londrina              | 44        | 0.56%   |
| Maceió               | 43        | 0.55%   |
| Cuiabá               | 38        | 0.48%   |
| Sao Jose              | 37        | 0.47%   |
| Juiz de Fora          | 35        | 0.44%   |
| Sao Carlos            | 34        | 0.43%   |
| Sao Bernardo do Campo | 33        | 0.42%   |
| Canoas                | 33        | 0.42%   |
| Vitória              | 31        | 0.39%   |
| Americana             | 30        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 2035      | 2487   | 21.73%  |
| Seagate                        | 1393      | 1665   | 14.88%  |
| Kingston                       | 893       | 1072   | 9.54%   |
| Samsung Electronics            | 660       | 861    | 7.05%   |
| Toshiba                        | 633       | 740    | 6.76%   |
| SanDisk                        | 540       | 715    | 5.77%   |
| Unknown                        | 416       | 558    | 4.44%   |
| A-DATA Technology              | 390       | 499    | 4.16%   |
| Intel                          | 273       | 336    | 2.92%   |
| Hitachi                        | 201       | 244    | 2.15%   |
| China                          | 191       | 239    | 2.04%   |
| ADATA Technology               | 185       | 214    | 1.98%   |
| Crucial                        | 166       | 227    | 1.77%   |
| SK hynix                       | 128       | 163    | 1.37%   |
| LITEON                         | 109       | 129    | 1.16%   |
| HGST                           | 108       | 128    | 1.15%   |
| Silicon Motion                 | 74        | 88     | 0.79%   |
| KingSpec                       | 66        | 74     | 0.7%    |
| SSSTC                          | 50        | 51     | 0.53%   |
| JMicron Technology             | 44        | 50     | 0.47%   |
| Fujitsu                        | 44        | 51     | 0.47%   |
| Apple                          | 40        | 50     | 0.43%   |
| Solid State Storage            | 37        | 43     | 0.4%    |
| Lexar                          | 37        | 47     | 0.4%    |
| Solid State Storage Technology | 35        | 48     | 0.37%   |
| Phison                         | 35        | 38     | 0.37%   |
| Netac                          | 35        | 40     | 0.37%   |
| KIOXIA                         | 35        | 42     | 0.37%   |
| Micron Technology              | 26        | 27     | 0.28%   |
| Corsair                        | 26        | 26     | 0.28%   |
| Realtek Semiconductor          | 25        | 32     | 0.27%   |
| Unknown                        | 24        | 28     | 0.26%   |
| PNY                            | 23        | 34     | 0.25%   |
| XrayDisk                       | 19        | 23     | 0.2%    |
| Patriot                        | 19        | 22     | 0.2%    |
| Hewlett-Packard                | 19        | 22     | 0.2%    |
| Smart                          | 18        | 20     | 0.19%   |
| Kingston Technology Company    | 18        | 19     | 0.19%   |
| XPG                            | 16        | 20     | 0.17%   |
| WALRAM                         | 15        | 15     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 482       | 5.01%   |
| Kingston SA400S37240G 240GB SSD     | 309       | 3.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 265       | 2.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 230       | 2.39%   |
| Kingston SA400S37480G 480GB SSD     | 170       | 1.77%   |
| Kingston SA400S37120G 120GB SSD     | 140       | 1.45%   |
| Toshiba MQ01ABD100 1TB              | 139       | 1.44%   |
| WDC WD10SPZX-24Z10 1TB              | 130       | 1.35%   |
| Unknown MMC Card  32GB              | 125       | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB      | 104       | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB            | 102       | 1.06%   |
| Intel NVMe SSD Drive 512GB          | 98        | 1.02%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 91        | 0.95%   |
| WDC WD10SPZX-75Z10T2 1TB            | 82        | 0.85%   |
| Samsung HM321HI 320GB               | 80        | 0.83%   |
| Toshiba MQ04ABF100 1TB              | 78        | 0.81%   |
| Seagate ST9500325AS 500GB           | 78        | 0.81%   |
| SanDisk NVMe SSD Drive 512GB        | 73        | 0.76%   |
| SanDisk SSD PLUS 240GB              | 70        | 0.73%   |
| Intel SSDPEKKW256G7 256GB           | 70        | 0.73%   |
| ADATA NVMe SSD Drive 256GB          | 68        | 0.71%   |
| Kingston SV300S37A120G 120GB SSD    | 64        | 0.66%   |
| WDC WD10JPVX-75JC3T0 1TB            | 62        | 0.64%   |
| Seagate Expansion 1TB               | 62        | 0.64%   |
| SanDisk SSD PLUS 120GB              | 59        | 0.61%   |
| Toshiba MQ01ABF050 500GB            | 56        | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 55        | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB      | 55        | 0.57%   |
| Seagate ST500LT012-9WS142 500GB     | 54        | 0.56%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 54        | 0.56%   |
| A-DATA IM2P33F3A NVMe 256GB         | 53        | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 50        | 0.52%   |
| WDC WD10JPCX-24UE4T0 1TB            | 48        | 0.5%    |
| Crucial CT240BX500SSD1 240GB        | 48        | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 47        | 0.49%   |
| Toshiba MQ01ABD050 500GB            | 43        | 0.45%   |
| WDC WD10SPZX-75Z10T1 1TB            | 42        | 0.44%   |
| Seagate ST1000LM014-1EJ164 1TB      | 41        | 0.43%   |
| Intel NVMe SSD Drive 256GB          | 40        | 0.42%   |
| Seagate ST1000LM048-2E7172 1TB      | 38        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1812      | 2135   | 40.09%  |
| Seagate             | 1383      | 1651   | 30.6%   |
| Toshiba             | 598       | 696    | 13.23%  |
| Samsung Electronics | 292       | 339    | 6.46%   |
| Hitachi             | 201       | 244    | 4.45%   |
| HGST                | 108       | 128    | 2.39%   |
| Fujitsu             | 43        | 49     | 0.95%   |
| JMicron Technology  | 38        | 44     | 0.84%   |
| Unknown             | 22        | 27     | 0.49%   |
| Apple               | 13        | 16     | 0.29%   |
| WALRAM              | 1         | 1      | 0.02%   |
| USB3.0              | 1         | 1      | 0.02%   |
| Phison              | 1         | 1      | 0.02%   |
| Maxtor 6            | 1         | 1      | 0.02%   |
| Maxtor              | 1         | 1      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| IBM/Hitachi         | 1         | 2      | 0.02%   |
| External            | 1         | 1      | 0.02%   |
| CLOVER              | 1         | 1      | 0.02%   |
| ASMT                | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 852       | 1015   | 30.34%  |
| SanDisk             | 342       | 473    | 12.18%  |
| Samsung Electronics | 231       | 323    | 8.23%   |
| WDC                 | 212       | 263    | 7.55%   |
| A-DATA Technology   | 197       | 240    | 7.02%   |
| China               | 191       | 239    | 6.8%    |
| Crucial             | 157       | 214    | 5.59%   |
| LITEON              | 100       | 120    | 3.56%   |
| KingSpec            | 62        | 70     | 2.21%   |
| Lexar               | 36        | 46     | 1.28%   |
| Netac               | 30        | 33     | 1.07%   |
| Apple               | 25        | 31     | 0.89%   |
| PNY                 | 23        | 34     | 0.82%   |
| Intel               | 23        | 27     | 0.82%   |
| Corsair             | 21        | 21     | 0.75%   |
| Smart               | 18        | 20     | 0.64%   |
| Patriot             | 18        | 21     | 0.64%   |
| SK hynix            | 16        | 19     | 0.57%   |
| Hewlett-Packard     | 15        | 17     | 0.53%   |
| Unknown             | 13        | 14     | 0.46%   |
| LITEONIT            | 13        | 20     | 0.46%   |
| KingDian            | 13        | 19     | 0.46%   |
| Gigabyte Technology | 13        | 19     | 0.46%   |
| Unknown             | 13        | 14     | 0.46%   |
| XrayDisk            | 12        | 13     | 0.43%   |
| Toshiba             | 10        | 14     | 0.36%   |
| Seagate             | 9         | 10     | 0.32%   |
| Win Memory          | 8         | 9      | 0.28%   |
| Micron Technology   | 8         | 9      | 0.28%   |
| WALRAM              | 7         | 7      | 0.25%   |
| BHT                 | 7         | 7      | 0.25%   |
| SAGE                | 6         | 10     | 0.21%   |
| BIWIN               | 6         | 6      | 0.21%   |
| HUSKY               | 5         | 6      | 0.18%   |
| Transcend           | 4         | 4      | 0.14%   |
| S3+                 | 4         | 4      | 0.14%   |
| Maxtor              | 4         | 4      | 0.14%   |
| Lenovo              | 4         | 4      | 0.14%   |
| Advantech           | 4         | 5      | 0.14%   |
| Vaseky              | 3         | 4      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4430      | 5340   | 49.02%  |
| SSD     | 2619      | 3508   | 28.98%  |
| NVMe    | 1566      | 2073   | 17.33%  |
| MMC     | 344       | 484    | 3.81%   |
| Unknown | 79        | 100    | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6221      | 8687   | 74.66%  |
| NVMe | 1566      | 2073   | 18.8%   |
| MMC  | 344       | 484    | 4.13%   |
| SAS  | 201       | 261    | 2.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4403      | 5808   | 64.12%  |
| 0.51-1.0   | 2326      | 2874   | 33.87%  |
| 1.01-2.0   | 127       | 154    | 1.85%   |
| 3.01-4.0   | 5         | 5      | 0.07%   |
| 4.01-10.0  | 5         | 6      | 0.07%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2360      | 29.8%   |
| 251-500        | 2004      | 25.3%   |
| 501-1000       | 1409      | 17.79%  |
| 1-20           | 578       | 7.3%    |
| 51-100         | 478       | 6.04%   |
| 1001-2000      | 438       | 5.53%   |
| 21-50          | 388       | 4.9%    |
| Unknown        | 119       | 1.5%    |
| 2001-3000      | 80        | 1.01%   |
| More than 3000 | 66        | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3099      | 37.71%  |
| 21-50          | 1953      | 23.77%  |
| 101-250        | 1079      | 13.13%  |
| 51-100         | 1069      | 13.01%  |
| 251-500        | 527       | 6.41%   |
| 501-1000       | 256       | 3.12%   |
| Unknown        | 119       | 1.45%   |
| 1001-2000      | 93        | 1.13%   |
| 2001-3000      | 11        | 0.13%   |
| More than 3000 | 10        | 0.12%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 36        | 40     | 7.14%   |
| Seagate ST9500325AS 500GB           | 21        | 23     | 4.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 19        | 21     | 3.77%   |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 13     | 2.58%   |
| Toshiba MQ01ABD100 1TB              | 12        | 12     | 2.38%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 12     | 1.98%   |
| Seagate ST9320325AS 320GB           | 8         | 8      | 1.59%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 1.39%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 7      | 1.19%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 6         | 6      | 1.19%   |
| Toshiba MQ02ABD100H 1TB             | 6         | 9      | 1.19%   |
| Toshiba MQ01ABD050 500GB            | 6         | 6      | 1.19%   |
| Samsung Electronics HM160HI 160GB   | 6         | 6      | 1.19%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 7      | 1.19%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 6      | 1.19%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 5         | 6      | 0.99%   |
| WDC WD10JPCX-24UE4T0 1TB            | 5         | 5      | 0.99%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 0.99%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 0.99%   |
| Seagate ST1000LM048-2E7172 1TB      | 5         | 6      | 0.99%   |
| Seagate ST1000LM014-1EJ164 1TB      | 5         | 5      | 0.99%   |
| Samsung Electronics HM321HI 320GB   | 5         | 5      | 0.99%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 0.99%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 4         | 4      | 0.79%   |
| Seagate ST9500423AS 500GB           | 4         | 4      | 0.79%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 4      | 0.79%   |
| SanDisk SSD PLUS 480GB              | 4         | 4      | 0.79%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 4      | 0.79%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 0.79%   |
| HGST HCC545050A7E380 500GB          | 4         | 4      | 0.79%   |
| China SSD 120GB                     | 4         | 4      | 0.79%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 3         | 3      | 0.6%    |
| WDC WD3200BPVT-00JJ5T0 320GB        | 3         | 5      | 0.6%    |
| WDC WD10SPZX-24Z10T0 1TB            | 3         | 4      | 0.6%    |
| WDC WD10SPZX-24Z10 1TB              | 3         | 3      | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 3      | 0.6%    |
| Toshiba MQ01ACF050 500GB            | 3         | 3      | 0.6%    |
| Toshiba MQ01ABD032 320GB            | 3         | 3      | 0.6%    |
| Toshiba MK5065GSXF 500GB            | 3         | 3      | 0.6%    |
| Toshiba MK5061GSYN 500GB            | 3         | 4      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 171       | 188    | 34.2%   |
| WDC                 | 91        | 101    | 18.2%   |
| Toshiba             | 73        | 81     | 14.6%   |
| Hitachi             | 32        | 35     | 6.4%    |
| Samsung Electronics | 29        | 40     | 5.8%    |
| Kingston            | 23        | 27     | 4.6%    |
| SanDisk             | 14        | 14     | 2.8%    |
| China               | 12        | 13     | 2.4%    |
| HGST                | 11        | 11     | 2.2%    |
| A-DATA Technology   | 8         | 9      | 1.6%    |
| LITEON              | 4         | 4      | 0.8%    |
| Fujitsu             | 4         | 5      | 0.8%    |
| PNY                 | 3         | 5      | 0.6%    |
| KingSpec            | 3         | 3      | 0.6%    |
| Intel               | 3         | 3      | 0.6%    |
| WALRAM              | 2         | 2      | 0.4%    |
| Crucial             | 2         | 2      | 0.4%    |
| Apple               | 2         | 2      | 0.4%    |
| XrayDisk            | 1         | 1      | 0.2%    |
| XPG                 | 1         | 1      | 0.2%    |
| SSSTC               | 1         | 1      | 0.2%    |
| SK hynix            | 1         | 1      | 0.2%    |
| Silicon Motion      | 1         | 1      | 0.2%    |
| ShiJi               | 1         | 4      | 0.2%    |
| OCZ                 | 1         | 1      | 0.2%    |
| Netac               | 1         | 1      | 0.2%    |
| Micron Technology   | 1         | 1      | 0.2%    |
| LITEONIT            | 1         | 2      | 0.2%    |
| Kross Elegance      | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| ADATA Technology    | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 171       | 188    | 42.54%  |
| WDC                 | 85        | 95     | 21.14%  |
| Toshiba             | 72        | 80     | 17.91%  |
| Hitachi             | 32        | 35     | 7.96%   |
| Samsung Electronics | 25        | 36     | 6.22%   |
| HGST                | 11        | 11     | 2.74%   |
| Fujitsu             | 4         | 5      | 1%      |
| JMicron Technology  | 1         | 1      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 401       | 452    | 80.36%  |
| SSD  | 84        | 92     | 16.83%  |
| NVMe | 14        | 18     | 2.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 16.67%  |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 8.33%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 8.33%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 8.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 8.33%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 8.33%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 8.33%   |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 8.33%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 41.67%  |
| WDC                 | 2         | 2      | 16.67%  |
| Toshiba             | 2         | 2      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Maxtor              | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5454      | 8236   | 69.25%  |
| Works    | 1920      | 2694   | 24.38%  |
| Malfunc  | 489       | 562    | 6.21%   |
| Failed   | 12        | 12     | 0.15%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6209      | 73.17%  |
| AMD                              | 715       | 8.43%   |
| ADATA Technology                 | 389       | 4.58%   |
| SanDisk                          | 237       | 2.79%   |
| Samsung Electronics              | 161       | 1.9%    |
| Solid State Storage Technology   | 131       | 1.54%   |
| SK hynix                         | 107       | 1.26%   |
| Silicon Integrated Systems [SiS] | 98        | 1.15%   |
| Silicon Motion                   | 82        | 0.97%   |
| Kingston Technology Company      | 61        | 0.72%   |
| Phison Electronics               | 45        | 0.53%   |
| Realtek Semiconductor            | 37        | 0.44%   |
| Nvidia                           | 37        | 0.44%   |
| KIOXIA                           | 33        | 0.39%   |
| VIA Technologies                 | 24        | 0.28%   |
| Toshiba America Info Systems     | 24        | 0.28%   |
| Micron/Crucial Technology        | 21        | 0.25%   |
| Micron Technology                | 18        | 0.21%   |
| Lite-On Technology               | 18        | 0.21%   |
| MAXIO Technology (Hangzhou)      | 10        | 0.12%   |
| Union Memory (Shenzhen)          | 7         | 0.08%   |
| Marvell Technology Group         | 6         | 0.07%   |
| Netac Technology                 | 4         | 0.05%   |
| Shenzhen Longsys Electronics     | 3         | 0.04%   |
| Apple                            | 3         | 0.04%   |
| TenaFe                           | 1         | 0.01%   |
| Seagate Technology               | 1         | 0.01%   |
| O2 Micro                         | 1         | 0.01%   |
| Lenovo                           | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |
| Beijing Starblaze Technology     | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1025      | 10.98%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 836       | 8.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 649       | 6.95%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 526       | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 482       | 5.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 395       | 4.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 324       | 3.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 310       | 3.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 248       | 2.66%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 206       | 2.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 206       | 2.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 159       | 1.7%    |
| Intel Tiger Lake-LP SATA Controller                                              | 156       | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 148       | 1.59%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                              | 148       | 1.59%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                      | 145       | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 137       | 1.47%   |
| Intel Comet Lake SATA AHCI Controller                                            | 134       | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 134       | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                              | 132       | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 132       | 1.41%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 124       | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 124       | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 116       | 1.24%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 97        | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 96        | 1.03%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 81        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 80        | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 79        | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 77        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 77        | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 69        | 0.74%   |
| ADATA A Non-Volatile memory controller                                           | 69        | 0.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 68        | 0.73%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 58        | 0.62%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 58        | 0.62%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 57        | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 56        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 50        | 0.54%   |
| Samsung NVMe SSD Controller 980                                                  | 49        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 6106      | 67.99%  |
| NVMe | 1571      | 17.49%  |
| RAID | 720       | 8.02%   |
| IDE  | 584       | 6.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 6733      | 89.65%  |
| AMD    | 775       | 10.32%  |
| ARM    | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 264       | 3.51%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 166       | 2.21%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 152       | 2.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 140       | 1.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 132       | 1.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 131       | 1.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 130       | 1.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 129       | 1.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 123       | 1.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 110       | 1.46%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 110       | 1.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 102       | 1.36%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 97        | 1.29%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 96        | 1.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 96        | 1.28%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 95        | 1.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 92        | 1.22%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 92        | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 91        | 1.21%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 87        | 1.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 83        | 1.1%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 82        | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 81        | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 79        | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 76        | 1.01%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 75        | 1%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 75        | 1%      |
| Intel Core i3-4005U CPU @ 1.70GHz             | 73        | 0.97%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 69        | 0.92%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 68        | 0.9%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 68        | 0.9%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 67        | 0.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 66        | 0.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 63        | 0.84%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 62        | 0.83%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 61        | 0.81%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 58        | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 58        | 0.77%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 58        | 0.77%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 57        | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2169      | 28.87%  |
| Intel Core i7                  | 1509      | 20.09%  |
| Intel Core i3                  | 1169      | 15.56%  |
| Intel Celeron                  | 567       | 7.55%   |
| Other                          | 332       | 4.42%   |
| Intel Core 2 Duo               | 280       | 3.73%   |
| Intel Atom                     | 268       | 3.57%   |
| AMD Ryzen 5                    | 203       | 2.7%    |
| AMD Ryzen 7                    | 185       | 2.46%   |
| Intel Pentium Dual-Core        | 143       | 1.9%    |
| Intel Pentium                  | 140       | 1.86%   |
| Intel Pentium Dual             | 76        | 1.01%   |
| AMD E                          | 51        | 0.68%   |
| AMD C-60                       | 39        | 0.52%   |
| AMD E1                         | 34        | 0.45%   |
| AMD A4                         | 29        | 0.39%   |
| Intel Genuine                  | 27        | 0.36%   |
| AMD A6                         | 27        | 0.36%   |
| AMD C-70                       | 23        | 0.31%   |
| Intel Core 2                   | 22        | 0.29%   |
| AMD A10                        | 22        | 0.29%   |
| AMD C-50                       | 18        | 0.24%   |
| Intel Celeron Dual-Core        | 17        | 0.23%   |
| AMD A12                        | 15        | 0.2%    |
| AMD Ryzen 3                    | 13        | 0.17%   |
| AMD Mobile Sempron             | 12        | 0.16%   |
| Intel Celeron M                | 11        | 0.15%   |
| AMD Ryzen 9                    | 9         | 0.12%   |
| AMD Athlon II                  | 9         | 0.12%   |
| AMD Turion 64 Mobile           | 7         | 0.09%   |
| AMD Turion X2 Dual-Core Mobile | 6         | 0.08%   |
| AMD Turion 64 X2 Mobile        | 6         | 0.08%   |
| AMD Turion II                  | 5         | 0.07%   |
| AMD Phenom II                  | 5         | 0.07%   |
| AMD Athlon 64 X2               | 5         | 0.07%   |
| Intel Pentium M                | 4         | 0.05%   |
| Intel Pentium Gold             | 4         | 0.05%   |
| AMD Turion Neo X2              | 4         | 0.05%   |
| AMD Ryzen 7 PRO                | 4         | 0.05%   |
| AMD A8                         | 4         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4712      | 62.73%  |
| 4       | 2126      | 28.3%   |
| 6       | 313       | 4.17%   |
| 8       | 164       | 2.18%   |
| 1       | 155       | 2.06%   |
| 14      | 18        | 0.24%   |
| 12      | 13        | 0.17%   |
| 10      | 4         | 0.05%   |
| Unknown | 3         | 0.04%   |
| 5       | 2         | 0.03%   |
| 3       | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7510      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5680      | 75.55%  |
| 1       | 1834      | 24.39%  |
| Unknown | 3         | 0.04%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7194      | 95.3%   |
| Unknown        | 295       | 3.91%   |
| 32-bit         | 45        | 0.6%    |
| 64-bit         | 15        | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1700      | 21.77%  |
| 0x306a9    | 605       | 7.75%   |
| 0x206a7    | 604       | 7.74%   |
| 0x806e9    | 398       | 5.1%    |
| 0x40651    | 345       | 4.42%   |
| 0x806ec    | 322       | 4.12%   |
| 0x20655    | 303       | 3.88%   |
| 0x906ea    | 299       | 3.83%   |
| 0x306d4    | 285       | 3.65%   |
| 0x406e3    | 273       | 3.5%    |
| 0x1067a    | 265       | 3.39%   |
| 0x806ea    | 252       | 3.23%   |
| 0x806c1    | 189       | 2.42%   |
| 0x406c4    | 165       | 2.11%   |
| 0x6fd      | 153       | 1.96%   |
| 0x08108109 | 91        | 1.17%   |
| 0x05000119 | 89        | 1.14%   |
| 0x08600103 | 87        | 1.11%   |
| 0x30678    | 85        | 1.09%   |
| 0x906e9    | 84        | 1.08%   |
| 0x706e5    | 78        | 1%      |
| 0x08108102 | 67        | 0.86%   |
| 0x706a1    | 61        | 0.78%   |
| 0x306c3    | 59        | 0.76%   |
| 0x906ed    | 58        | 0.74%   |
| 0x406c3    | 56        | 0.72%   |
| 0x706a8    | 54        | 0.69%   |
| 0xa0652    | 53        | 0.68%   |
| 0x20652    | 51        | 0.65%   |
| 0x806eb    | 50        | 0.64%   |
| 0x106ca    | 47        | 0.6%    |
| 0x10676    | 34        | 0.44%   |
| 0x30661    | 33        | 0.42%   |
| 0x08608103 | 29        | 0.37%   |
| 0x03000027 | 29        | 0.37%   |
| 0x506c9    | 28        | 0.36%   |
| 0x05000029 | 28        | 0.36%   |
| 0x10661    | 26        | 0.33%   |
| 0x506e3    | 24        | 0.31%   |
| 0x0a50000c | 21        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1821      | 24.23%  |
| IvyBridge        | 750       | 9.98%   |
| SandyBridge      | 730       | 9.71%   |
| Haswell          | 491       | 6.53%   |
| Westmere         | 425       | 5.66%   |
| Silvermont       | 375       | 4.99%   |
| Skylake          | 365       | 4.86%   |
| Penryn           | 358       | 4.76%   |
| Broadwell        | 337       | 4.48%   |
| TigerLake        | 255       | 3.39%   |
| Core             | 241       | 3.21%   |
| Zen+             | 199       | 2.65%   |
| Bobcat           | 153       | 2.04%   |
| Goldmont plus    | 135       | 1.8%    |
| IceLake          | 124       | 1.65%   |
| Unknown          | 106       | 1.41%   |
| Bonnell          | 101       | 1.34%   |
| Zen 2            | 97        | 1.29%   |
| CometLake        | 94        | 1.25%   |
| K8 Hammer        | 45        | 0.6%    |
| Excavator        | 43        | 0.57%   |
| Goldmont         | 34        | 0.45%   |
| K10 Llano        | 33        | 0.44%   |
| Alderlake Hybrid | 31        | 0.41%   |
| Zen 3            | 29        | 0.39%   |
| Zen              | 29        | 0.39%   |
| K10              | 28        | 0.37%   |
| P6               | 24        | 0.32%   |
| Jaguar           | 22        | 0.29%   |
| Nehalem          | 12        | 0.16%   |
| K8 & K10 hybrid  | 11        | 0.15%   |
| Piledriver       | 10        | 0.13%   |
| Puma             | 4         | 0.05%   |
| Steamroller      | 2         | 0.03%   |
| NetBurst         | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6457      | 66.38%  |
| Nvidia                           | 1959      | 20.14%  |
| AMD                              | 1189      | 12.22%  |
| Silicon Integrated Systems [SiS] | 98        | 1.01%   |
| VIA Technologies                 | 24        | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 740       | 7.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 716       | 7.17%   |
| Intel HD Graphics 620                                                                    | 522       | 5.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 412       | 4.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 399       | 4%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 390       | 3.91%   |
| Intel HD Graphics 5500                                                                   | 316       | 3.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 300       | 3%      |
| Intel UHD Graphics 620                                                                   | 299       | 2.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 293       | 2.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 274       | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 267       | 2.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 263       | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 214       | 2.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 198       | 1.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 176       | 1.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 147       | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 142       | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 142       | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 135       | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 108       | 1.08%   |
| Nvidia TU117M                                                                            | 106       | 1.06%   |
| Intel HD Graphics 630                                                                    | 106       | 1.06%   |
| Nvidia GP108M [GeForce MX150]                                                            | 99        | 0.99%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 97        | 0.97%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 95        | 0.95%   |
| AMD Renoir                                                                               | 95        | 0.95%   |
| Nvidia GM108M [GeForce MX110]                                                            | 94        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 92        | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 88        | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 85        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 80        | 0.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 73        | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 68        | 0.68%   |
| AMD Lucienne                                                                             | 59        | 0.59%   |
| Nvidia GP108M [GeForce MX250]                                                            | 56        | 0.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 52        | 0.52%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 48        | 0.48%   |
| Nvidia GP108M [GeForce MX230]                                                            | 46        | 0.46%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 45        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 4393      | 58.39%  |
| Intel + Nvidia | 1663      | 22.1%   |
| 1 x AMD        | 559       | 7.43%   |
| Intel + AMD    | 395       | 5.25%   |
| AMD + Nvidia   | 158       | 2.1%    |
| 1 x Nvidia     | 137       | 1.82%   |
| 1 x SiS        | 98        | 1.3%    |
| 2 x AMD        | 76        | 1.01%   |
| 1 x VIA        | 24        | 0.32%   |
| 2 x Intel      | 17        | 0.23%   |
| Other          | 4         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6148      | 81%     |
| Proprietary | 1225      | 16.14%  |
| Unknown     | 217       | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5389      | 70.25%  |
| 1.01-2.0   | 1061      | 13.83%  |
| 0.01-0.5   | 552       | 7.2%    |
| 3.01-4.0   | 390       | 5.08%   |
| 0.51-1.0   | 180       | 2.35%   |
| 5.01-6.0   | 68        | 0.89%   |
| 2.01-3.0   | 16        | 0.21%   |
| 7.01-8.0   | 13        | 0.17%   |
| 8.01-16.0  | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 1623      | 18.98%  |
| AU Optronics            | 1565      | 18.3%   |
| Chimei Innolux          | 1254      | 14.66%  |
| LG Display              | 1162      | 13.59%  |
| Samsung Electronics     | 870       | 10.17%  |
| Goldstar                | 457       | 5.34%   |
| AOC                     | 174       | 2.03%   |
| Dell                    | 172       | 2.01%   |
| Chi Mei Optoelectronics | 161       | 1.88%   |
| InfoVision              | 126       | 1.47%   |
| PANDA                   | 120       | 1.4%    |
| Apple                   | 99        | 1.16%   |
| Philips                 | 97        | 1.13%   |
| Lenovo                  | 59        | 0.69%   |
| Acer                    | 57        | 0.67%   |
| CPT                     | 49        | 0.57%   |
| HannStar                | 47        | 0.55%   |
| LG Philips              | 41        | 0.48%   |
| Sony                    | 35        | 0.41%   |
| SLD                     | 33        | 0.39%   |
| Hewlett-Packard         | 33        | 0.39%   |
| InnoLux Display         | 30        | 0.35%   |
| Sharp                   | 23        | 0.27%   |
| MTD                     | 20        | 0.23%   |
| KDC                     | 14        | 0.16%   |
| Panasonic               | 13        | 0.15%   |
| BenQ                    | 12        | 0.14%   |
| STA                     | 11        | 0.13%   |
| Toshiba                 | 10        | 0.12%   |
| ASUSTek Computer        | 10        | 0.12%   |
| Unknown                 | 9         | 0.11%   |
| SKY                     | 9         | 0.11%   |
| GDH                     | 9         | 0.11%   |
| Valve                   | 7         | 0.08%   |
| Unknown (XXX)           | 7         | 0.08%   |
| NCS                     | 7         | 0.08%   |
| ITE                     | 7         | 0.08%   |
| RTK                     | 6         | 0.07%   |
| MStar                   | 6         | 0.07%   |
| HB@                     | 6         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 121       | 1.41%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 121       | 1.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 117       | 1.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 115       | 1.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 108       | 1.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 107       | 1.24%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 102       | 1.19%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 101       | 1.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 84        | 0.98%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 77        | 0.9%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 77        | 0.9%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 75        | 0.87%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 73        | 0.85%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 70        | 0.81%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 69        | 0.8%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 64        | 0.74%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 64        | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 59        | 0.69%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 59        | 0.69%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 57        | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 56        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 56        | 0.65%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.63%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 54        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 54        | 0.63%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 50        | 0.58%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 50        | 0.58%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 48        | 0.56%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 47        | 0.55%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 47        | 0.55%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 46        | 0.53%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 46        | 0.53%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 44        | 0.51%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 42        | 0.49%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 40        | 0.47%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 40        | 0.47%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 39        | 0.45%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                 | 39        | 0.45%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 38        | 0.44%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 38        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4474      | 54.84%  |
| 1920x1080 (FHD)    | 2375      | 29.11%  |
| 1280x800 (WXGA)    | 318       | 3.9%    |
| 1600x900 (HD+)     | 175       | 2.14%   |
| 2560x1080          | 167       | 2.05%   |
| 3840x2160 (4K)     | 117       | 1.43%   |
| 1440x900 (WXGA+)   | 102       | 1.25%   |
| 1360x768           | 77        | 0.94%   |
| 2560x1440 (QHD)    | 65        | 0.8%    |
| 1920x1200 (WUXGA)  | 51        | 0.63%   |
| 1024x600           | 42        | 0.51%   |
| 1280x1024 (SXGA)   | 32        | 0.39%   |
| 1680x1050 (WSXGA+) | 30        | 0.37%   |
| 1024x768 (XGA)     | 21        | 0.26%   |
| 1920x540           | 18        | 0.22%   |
| 2560x1600          | 16        | 0.2%    |
| 1280x720 (HD)      | 10        | 0.12%   |
| 2288x1287          | 8         | 0.1%    |
| Unknown            | 8         | 0.1%    |
| 800x1280           | 7         | 0.09%   |
| 3840x2400          | 6         | 0.07%   |
| 2880x1800          | 6         | 0.07%   |
| 3840x1080          | 3         | 0.04%   |
| 3440x1440          | 3         | 0.04%   |
| 3200x1800 (QHD+)   | 3         | 0.04%   |
| 1280x960           | 3         | 0.04%   |
| 2160x1440          | 2         | 0.02%   |
| 1024x576           | 2         | 0.02%   |
| 4240x1080          | 1         | 0.01%   |
| 3926x1080          | 1         | 0.01%   |
| 3840x1600          | 1         | 0.01%   |
| 3600x1080          | 1         | 0.01%   |
| 3286x1080          | 1         | 0.01%   |
| 3200x2000          | 1         | 0.01%   |
| 2880x900           | 1         | 0.01%   |
| 2646x800           | 1         | 0.01%   |
| 2640x800           | 1         | 0.01%   |
| 2400x1600          | 1         | 0.01%   |
| 2304x1440          | 1         | 0.01%   |
| 2256x1504          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3667      | 42.96%  |
| 14      | 1610      | 18.86%  |
| 13      | 1362      | 15.96%  |
| 21      | 255       | 2.99%   |
| 23      | 221       | 2.59%   |
| 17      | 196       | 2.3%    |
| 18      | 175       | 2.05%   |
| 34      | 152       | 1.78%   |
| 24      | 127       | 1.49%   |
| 11      | 120       | 1.41%   |
| 27      | 102       | 1.19%   |
| 12      | 59        | 0.69%   |
| 31      | 53        | 0.62%   |
| 20      | 51        | 0.6%    |
| 19      | 51        | 0.6%    |
| Unknown | 50        | 0.59%   |
| 10      | 46        | 0.54%   |
| 40      | 29        | 0.34%   |
| 28      | 25        | 0.29%   |
| 72      | 20        | 0.23%   |
| 32      | 19        | 0.22%   |
| 54      | 18        | 0.21%   |
| 22      | 18        | 0.21%   |
| 84      | 17        | 0.2%    |
| 52      | 17        | 0.2%    |
| 16      | 17        | 0.2%    |
| 46      | 9         | 0.11%   |
| 37      | 9         | 0.11%   |
| 26      | 8         | 0.09%   |
| 47      | 7         | 0.08%   |
| 7       | 7         | 0.08%   |
| 58      | 3         | 0.04%   |
| 48      | 3         | 0.04%   |
| 65      | 2         | 0.02%   |
| 55      | 2         | 0.02%   |
| 142     | 1         | 0.01%   |
| 60      | 1         | 0.01%   |
| 57      | 1         | 0.01%   |
| 49      | 1         | 0.01%   |
| 43      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 6306      | 74.45%  |
| 401-500        | 541       | 6.39%   |
| 501-600        | 438       | 5.17%   |
| 201-300        | 428       | 5.05%   |
| 351-400        | 300       | 3.54%   |
| 701-800        | 171       | 2.02%   |
| 601-700        | 85        | 1%      |
| 1001-1500      | 64        | 0.76%   |
| Unknown        | 50        | 0.59%   |
| 801-900        | 39        | 0.46%   |
| 1501-2000      | 37        | 0.44%   |
| 1-100          | 7         | 0.08%   |
| 901-1000       | 3         | 0.04%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6653      | 88.81%  |
| 16/10   | 546       | 7.29%   |
| 21/9    | 172       | 2.3%    |
| 4/3     | 40        | 0.53%   |
| 5/4     | 32        | 0.43%   |
| Unknown | 24        | 0.32%   |
| 3/2     | 13        | 0.17%   |
| 0.67    | 7         | 0.09%   |
| 32/9    | 3         | 0.04%   |
| 1.00    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3648      | 42.79%  |
| 81-90          | 2819      | 33.06%  |
| 201-250        | 544       | 6.38%   |
| 351-500        | 230       | 2.7%    |
| 141-150        | 182       | 2.13%   |
| 151-200        | 174       | 2.04%   |
| 71-80          | 148       | 1.74%   |
| 121-130        | 139       | 1.63%   |
| 51-60          | 120       | 1.41%   |
| 301-350        | 107       | 1.25%   |
| More than 1000 | 84        | 0.99%   |
| 501-1000       | 60        | 0.7%    |
| Unknown        | 50        | 0.59%   |
| 61-70          | 46        | 0.54%   |
| 41-50          | 46        | 0.54%   |
| 251-300        | 40        | 0.47%   |
| 91-100         | 35        | 0.41%   |
| 131-140        | 33        | 0.39%   |
| 111-120        | 14        | 0.16%   |
| 1-40           | 7         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 4628      | 55.54%  |
| 121-160       | 2104      | 25.25%  |
| 51-100        | 1266      | 15.19%  |
| 161-240       | 139       | 1.67%   |
| 1-50          | 121       | 1.45%   |
| Unknown       | 50        | 0.6%    |
| More than 240 | 24        | 0.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6057      | 78.61%  |
| 2     | 1373      | 17.82%  |
| 0     | 208       | 2.7%    |
| 3     | 65        | 0.84%   |
| 4     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5469      | 41.62%  |
| Qualcomm Atheros                  | 3236      | 24.63%  |
| Intel                             | 2421      | 18.43%  |
| Broadcom                          | 723       | 5.5%    |
| JMicron Technology                | 209       | 1.59%   |
| Marvell Technology Group          | 188       | 1.43%   |
| Broadcom Limited                  | 155       | 1.18%   |
| Ralink                            | 140       | 1.07%   |
| Silicon Integrated Systems [SiS]  | 98        | 0.75%   |
| Ralink Technology                 | 86        | 0.65%   |
| TP-Link                           | 63        | 0.48%   |
| Samsung Electronics               | 52        | 0.4%    |
| ASIX Electronics                  | 33        | 0.25%   |
| Motorola PCS                      | 32        | 0.24%   |
| MediaTek                          | 29        | 0.22%   |
| Nvidia                            | 25        | 0.19%   |
| Xiaomi                            | 24        | 0.18%   |
| VIA Technologies                  | 24        | 0.18%   |
| Qualcomm Atheros Communications   | 24        | 0.18%   |
| D-Link                            | 17        | 0.13%   |
| ICS Advent                        | 11        | 0.08%   |
| D-Link System                     | 10        | 0.08%   |
| DisplayLink                       | 8         | 0.06%   |
| LG Electronics                    | 5         | 0.04%   |
| Lenovo                            | 5         | 0.04%   |
| Dell                              | 5         | 0.04%   |
| Huawei Technologies               | 4         | 0.03%   |
| Ericsson Business Mobile Networks | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Qualcomm                          | 3         | 0.02%   |
| Microsoft                         | 3         | 0.02%   |
| Edimax Technology                 | 3         | 0.02%   |
| AMD                               | 3         | 0.02%   |
| OPPO Electronics                  | 2         | 0.02%   |
| NetGear                           | 2         | 0.02%   |
| Micro Star International          | 2         | 0.02%   |
| ASUSTek Computer                  | 2         | 0.02%   |
| Arduino SA                        | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| Spreadtrum Communications         | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3169      | 22.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1459      | 10.13%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 870       | 6.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 777       | 5.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 589       | 4.09%   |
| Intel Wi-Fi 6 AX200                                               | 325       | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 309       | 2.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 302       | 2.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 299       | 2.08%   |
| Intel Wi-Fi 6 AX201                                               | 238       | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 221       | 1.53%   |
| Intel Wireless 7265                                               | 175       | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 168       | 1.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 155       | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 133       | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 129       | 0.9%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 121       | 0.84%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 105       | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 101       | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 101       | 0.7%    |
| Intel Wireless 7260                                               | 97        | 0.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 95        | 0.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 91        | 0.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 90        | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 85        | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 85        | 0.59%   |
| Intel Wireless 3165                                               | 84        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 81        | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 81        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 78        | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 74        | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 73        | 0.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 69        | 0.48%   |
| Intel Centrino Advanced-N 6235                                    | 68        | 0.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 64        | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 0.44%   |
| Intel Wireless 3160                                               | 64        | 0.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 63        | 0.44%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 60        | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 60        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3044      | 40.36%  |
| Intel                                 | 2362      | 31.31%  |
| Realtek Semiconductor                 | 1147      | 15.21%  |
| Broadcom                              | 521       | 6.91%   |
| Ralink                                | 140       | 1.86%   |
| Broadcom Limited                      | 97        | 1.29%   |
| Ralink Technology                     | 86        | 1.14%   |
| TP-Link                               | 47        | 0.62%   |
| MediaTek                              | 26        | 0.34%   |
| Qualcomm Atheros Communications       | 24        | 0.32%   |
| D-Link                                | 17        | 0.23%   |
| D-Link System                         | 10        | 0.13%   |
| Dell                                  | 4         | 0.05%   |
| Microsoft                             | 3         | 0.04%   |
| Edimax Technology                     | 3         | 0.04%   |
| NetGear                               | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Sierra Wireless                       | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Linksys                               | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| Ericsson Business Mobile Networks     | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 870       | 11.48%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 777       | 10.25%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 589       | 7.77%   |
| Intel Wi-Fi 6 AX200                                                     | 325       | 4.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 309       | 4.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 302       | 3.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 299       | 3.94%   |
| Intel Wi-Fi 6 AX201                                                     | 238       | 3.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 221       | 2.92%   |
| Intel Wireless 7265                                                     | 175       | 2.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 168       | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 133       | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 129       | 1.7%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 105       | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 101       | 1.33%   |
| Intel Wireless 7260                                                     | 97        | 1.28%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 90        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 85        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 85        | 1.12%   |
| Intel Wireless 3165                                                     | 84        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 81        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 74        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 69        | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 68        | 0.9%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 64        | 0.84%   |
| Intel Wireless 3160                                                     | 64        | 0.84%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 63        | 0.83%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 60        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 60        | 0.79%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 59        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 59        | 0.78%   |
| Intel Wireless 8265 / 8275                                              | 55        | 0.73%   |
| Ralink MT7601U Wireless Adapter                                         | 53        | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 53        | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 53        | 0.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 52        | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 51        | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 49        | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 49        | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 44        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4883      | 72.56%  |
| Qualcomm Atheros                 | 423       | 6.29%   |
| Intel                            | 356       | 5.29%   |
| Broadcom                         | 283       | 4.21%   |
| JMicron Technology               | 209       | 3.11%   |
| Marvell Technology Group         | 188       | 2.79%   |
| Silicon Integrated Systems [SiS] | 98        | 1.46%   |
| Broadcom Limited                 | 65        | 0.97%   |
| Samsung Electronics              | 35        | 0.52%   |
| ASIX Electronics                 | 33        | 0.49%   |
| Xiaomi                           | 24        | 0.36%   |
| VIA Technologies                 | 24        | 0.36%   |
| Nvidia                           | 24        | 0.36%   |
| Motorola PCS                     | 24        | 0.36%   |
| TP-Link                          | 16        | 0.24%   |
| ICS Advent                       | 11        | 0.16%   |
| DisplayLink                      | 8         | 0.12%   |
| Lenovo                           | 5         | 0.07%   |
| Attansic Technology              | 4         | 0.06%   |
| Qualcomm                         | 3         | 0.04%   |
| LG Electronics                   | 3         | 0.04%   |
| OPPO Electronics                 | 2         | 0.03%   |
| MediaTek                         | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.01%   |
| Spreadtrum Communications        | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.01%   |
| Huawei Technologies              | 1         | 0.01%   |
| Apple                            | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3169      | 46.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1459      | 21.56%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 155       | 2.29%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 121       | 1.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 101       | 1.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 95        | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 91        | 1.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 81        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 78        | 1.15%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 73        | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 64        | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 58        | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 56        | 0.83%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 54        | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 44        | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                              | 41        | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 39        | 0.58%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 38        | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 38        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 35        | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                                          | 34        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 31        | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 30        | 0.44%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 28        | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 28        | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 24        | 0.35%   |
| Motorola PCS XT1032                                                            | 24        | 0.35%   |
| Intel Ethernet Connection I219-LM                                              | 24        | 0.35%   |
| Intel 82577LM Gigabit Network Connection                                       | 24        | 0.35%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 23        | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 22        | 0.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 22        | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 21        | 0.31%   |
| Intel Ethernet Connection I218-LM                                              | 21        | 0.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 18        | 0.27%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 18        | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 18        | 0.27%   |
| Intel Ethernet Connection I217-LM                                              | 18        | 0.27%   |
| Intel Ethernet Connection (13) I219-LM                                         | 18        | 0.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 17        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7275      | 52.17%  |
| Ethernet | 6618      | 47.45%  |
| Modem    | 41        | 0.29%   |
| Unknown  | 12        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6275      | 79.53%  |
| Ethernet | 1613      | 20.44%  |
| Modem    | 1         | 0.01%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6236      | 82.79%  |
| 1     | 1032      | 13.7%   |
| 0     | 253       | 3.36%   |
| 3     | 11        | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5795      | 75.02%  |
| Yes  | 1930      | 24.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2008      | 36.87%  |
| Qualcomm Atheros Communications | 1549      | 28.44%  |
| Lite-On Technology              | 677       | 12.43%  |
| Broadcom                        | 208       | 3.82%   |
| Realtek Semiconductor           | 192       | 3.53%   |
| IMC Networks                    | 149       | 2.74%   |
| Foxconn / Hon Hai               | 124       | 2.28%   |
| Cambridge Silicon Radio         | 101       | 1.85%   |
| Apple                           | 98        | 1.8%    |
| Dell                            | 80        | 1.47%   |
| Hewlett-Packard                 | 62        | 1.14%   |
| Ralink                          | 53        | 0.97%   |
| Smart Modular Technologies      | 43        | 0.79%   |
| Qcom                            | 27        | 0.5%    |
| Ralink Technology               | 17        | 0.31%   |
| Foxconn International           | 13        | 0.24%   |
| Alps Electric                   | 13        | 0.24%   |
| Askey Computer                  | 10        | 0.18%   |
| Toshiba                         | 6         | 0.11%   |
| Opticis                         | 5         | 0.09%   |
| Micro Star International        | 4         | 0.07%   |
| ASUSTek Computer                | 4         | 0.07%   |
| Syntek                          | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 896       | 16.45%  |
| Intel Bluetooth wireless interface                                                  | 646       | 11.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 548       | 10.06%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 379       | 6.96%   |
| Intel AX200 Bluetooth                                                               | 321       | 5.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 247       | 4.54%   |
| Intel AX201 Bluetooth                                                               | 241       | 4.43%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 139       | 2.55%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 130       | 2.39%   |
| Realtek Bluetooth Radio                                                             | 128       | 2.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 123       | 2.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 101       | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 97        | 1.78%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 94        | 1.73%   |
| Lite-On Bluetooth Device                                                            | 89        | 1.63%   |
| IMC Networks Bluetooth Radio                                                        | 80        | 1.47%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 65        | 1.19%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 60        | 1.1%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 59        | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 58        | 1.07%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 58        | 1.07%   |
| Ralink RT3290 Bluetooth                                                             | 53        | 0.97%   |
| Apple Bluetooth Host Controller                                                     | 47        | 0.86%   |
| Smart Modular Bluetooth Device                                                      | 43        | 0.79%   |
| Dell Wireless 365 Bluetooth                                                         | 35        | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 32        | 0.59%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 32        | 0.59%   |
| IMC Networks Bluetooth Device                                                       | 31        | 0.57%   |
| Apple Bluetooth USB Host Controller                                                 | 30        | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 28        | 0.51%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.44%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 24        | 0.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 23        | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 23        | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 21        | 0.39%   |
| Lite-On Wireless_Device                                                             | 21        | 0.39%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 18        | 0.33%   |
| Dell DW375 Bluetooth Module                                                         | 17        | 0.31%   |
| Realtek RTL8723A Bluetooth                                                          | 16        | 0.29%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 16        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 6426      | 73.9%   |
| Nvidia                                          | 957       | 11.01%  |
| AMD                                             | 811       | 9.33%   |
| Silicon Integrated Systems [SiS]                | 98        | 1.13%   |
| C-Media Electronics                             | 78        | 0.9%    |
| Logitech                                        | 49        | 0.56%   |
| Generalplus Technology                          | 48        | 0.55%   |
| VIA Technologies                                | 24        | 0.28%   |
| Kingston Technology                             | 24        | 0.28%   |
| JMTek                                           | 20        | 0.23%   |
| Texas Instruments                               | 14        | 0.16%   |
| Corsair                                         | 12        | 0.14%   |
| Microsoft                                       | 11        | 0.13%   |
| Realtek Semiconductor                           | 10        | 0.11%   |
| Plantronics                                     | 10        | 0.11%   |
| GN Netcom                                       | 9         | 0.1%    |
| Sony                                            | 7         | 0.08%   |
| Samsung Electronics                             | 6         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.07%   |
| Dell                                            | 5         | 0.06%   |
| Samson Technologies                             | 4         | 0.05%   |
| Razer USA                                       | 4         | 0.05%   |
| Jieli Technology                                | 4         | 0.05%   |
| JBL                                             | 4         | 0.05%   |
| SteelSeries ApS                                 | 3         | 0.03%   |
| Meizu                                           | 3         | 0.03%   |
| Lenovo                                          | 3         | 0.03%   |
| Goldvish                                        | 3         | 0.03%   |
| Focusrite-Novation                              | 3         | 0.03%   |
| BEHRINGER International                         | 3         | 0.03%   |
| Turtle Beach                                    | 2         | 0.02%   |
| Tdlasunnic                                      | 2         | 0.02%   |
| M-Audio                                         | 2         | 0.02%   |
| EDFIER                                          | 2         | 0.02%   |
| BY EDIFIER                                      | 2         | 0.02%   |
| Astro Gaming                                    | 2         | 0.02%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.01%   |
| Winbond Electronics                             | 1         | 0.01%   |
| Trust                                           | 1         | 0.01%   |
| Tenx Technology                                 | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1170      | 11.54%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 965       | 9.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 515       | 5.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 436       | 4.3%    |
| Intel 8 Series HD Audio Controller                                                                | 414       | 4.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 412       | 4.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 410       | 4.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 407       | 4.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 356       | 3.51%   |
| Intel Broadwell-U Audio Controller                                                                | 336       | 3.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 334       | 3.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 296       | 2.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 284       | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 254       | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 222       | 2.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 196       | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 163       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 159       | 1.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 156       | 1.54%   |
| AMD Wrestler HDMI Audio                                                                           | 144       | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 135       | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 129       | 1.27%   |
| AMD FCH Azalia Controller                                                                         | 121       | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 110       | 1.09%   |
| Intel CM238 HD Audio Controller                                                                   | 107       | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 101       | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 99        | 0.98%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 95        | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 86        | 0.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 84        | 0.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 77        | 0.76%   |
| Intel Comet Lake PCH cAVS                                                                         | 74        | 0.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 72        | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 58        | 0.57%   |
| Generalplus Technology USB Audio Device                                                           | 48        | 0.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 45        | 0.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 43        | 0.42%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 42        | 0.41%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 42        | 0.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 36        | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 572       | 18.81%  |
| Samsung Electronics | 413       | 13.58%  |
| SK hynix            | 286       | 9.4%    |
| Unknown             | 284       | 9.34%   |
| Kingston            | 282       | 9.27%   |
| A-DATA Technology   | 252       | 8.29%   |
| Teikon              | 157       | 5.16%   |
| Micron Technology   | 129       | 4.24%   |
| Smart Brazil        | 117       | 3.85%   |
| Crucial             | 80        | 2.63%   |
| Corsair             | 66        | 2.17%   |
| High Bridge         | 64        | 2.1%    |
| Elpida              | 45        | 1.48%   |
| Unknown (ABCD)      | 32        | 1.05%   |
| Unknown             | 29        | 0.95%   |
| Multilaser          | 25        | 0.82%   |
| Apacer              | 19        | 0.62%   |
| Nanya Technology    | 17        | 0.56%   |
| Kllisre             | 14        | 0.46%   |
| Patriot             | 13        | 0.43%   |
| Ramaxel Technology  | 12        | 0.39%   |
| HT Micron           | 12        | 0.39%   |
| PUSKILL             | 10        | 0.33%   |
| Smart Modular       | 7         | 0.23%   |
| Avant               | 7         | 0.23%   |
| Unknown (0x0B5E)    | 6         | 0.2%    |
| Team                | 5         | 0.16%   |
| Atermiter           | 5         | 0.16%   |
| Walton Chaintech    | 4         | 0.13%   |
| RZX                 | 4         | 0.13%   |
| HBS                 | 4         | 0.13%   |
| Carry               | 4         | 0.13%   |
| Super Talent        | 3         | 0.1%    |
| Qimonda             | 3         | 0.1%    |
| Kreton              | 3         | 0.1%    |
| Kingmax             | 3         | 0.1%    |
| G.Skill             | 3         | 0.1%    |
| 48spaces            | 3         | 0.1%    |
| Unknown (8A02)      | 2         | 0.07%   |
| Unknown (898F)      | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s  | 82        | 2.48%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 52        | 1.57%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 51        | 1.54%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 46        | 1.39%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 45        | 1.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 45        | 1.36%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 40        | 1.21%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 39        | 1.18%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 33        | 1%      |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 33        | 1%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 32        | 0.97%   |
| Unknown                                                          | 29        | 0.88%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 25        | 0.76%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 25        | 0.76%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 25        | 0.76%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.73%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 24        | 0.73%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 23        | 0.7%    |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 23        | 0.7%    |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 21        | 0.64%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 21        | 0.64%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 21        | 0.64%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.61%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 19        | 0.58%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 19        | 0.58%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 18        | 0.54%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 18        | 0.54%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 17        | 0.51%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 16        | 0.48%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 16        | 0.48%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 16        | 0.48%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 16        | 0.48%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s             | 16        | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 15        | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 14        | 0.42%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s           | 14        | 0.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 0.42%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 14        | 0.42%   |
| A-DATA RAM 4JQA-0622AC 4GB SODIMM DDR4 3200MT/s                  | 14        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1134      | 45.11%  |
| DDR4    | 993       | 39.5%   |
| DDR2    | 153       | 6.09%   |
| LPDDR4  | 69        | 2.74%   |
| SDRAM   | 67        | 2.67%   |
| LPDDR3  | 32        | 1.27%   |
| DRAM    | 20        | 0.8%    |
| DDR5    | 20        | 0.8%    |
| DDR     | 12        | 0.48%   |
| Unknown | 7         | 0.28%   |
| LPDDR5  | 6         | 0.24%   |
| RAM     | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2377      | 94.74%  |
| Row Of Chips | 103       | 4.11%   |
| Unknown      | 16        | 0.64%   |
| DIMM         | 11        | 0.44%   |
| Chip         | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 1127      | 39.19%  |
| 8192  | 780       | 27.12%  |
| 2048  | 570       | 19.82%  |
| 16384 | 272       | 9.46%   |
| 1024  | 89        | 3.09%   |
| 32768 | 33        | 1.15%   |
| 512   | 5         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 716       | 25.25%  |
| 2667    | 527       | 18.58%  |
| 2400    | 322       | 11.35%  |
| 1334    | 237       | 8.36%   |
| 3200    | 219       | 7.72%   |
| 1333    | 208       | 7.33%   |
| Unknown | 93        | 3.28%   |
| 2133    | 92        | 3.24%   |
| 800     | 63        | 2.22%   |
| 667     | 62        | 2.19%   |
| 1066    | 49        | 1.73%   |
| 4199    | 41        | 1.45%   |
| 1067    | 39        | 1.38%   |
| 4267    | 25        | 0.88%   |
| 975     | 22        | 0.78%   |
| 533     | 22        | 0.78%   |
| 2048    | 21        | 0.74%   |
| 4800    | 19        | 0.67%   |
| 1867    | 11        | 0.39%   |
| 3266    | 10        | 0.35%   |
| 8400    | 6         | 0.21%   |
| 6400    | 6         | 0.21%   |
| 3733    | 5         | 0.18%   |
| 1200    | 4         | 0.14%   |
| 2933    | 2         | 0.07%   |
| 400     | 2         | 0.07%   |
| 5600    | 1         | 0.04%   |
| 3466    | 1         | 0.04%   |
| 3400    | 1         | 0.04%   |
| 3000    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 1866    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1400    | 1         | 0.04%   |
| 666     | 1         | 0.04%   |
| 2       | 1         | 0.04%   |
| 1       | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 38.33%  |
| Seiko Epson         | 21        | 35%     |
| Canon               | 7         | 11.67%  |
| Samsung Electronics | 5         | 8.33%   |
| Brother Industries  | 2         | 3.33%   |
| Xerox               | 1         | 1.67%   |
| MIIIW               | 1         | 1.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                    | 7         | 11.67%  |
| HP LaserJet 1020                              | 3         | 5%      |
| HP DeskJet 2700 series                        | 3         | 5%      |
| Seiko Epson L6160 Series                      | 2         | 3.33%   |
| Seiko Epson L396 Series                       | 2         | 3.33%   |
| Seiko Epson L355 Series                       | 2         | 3.33%   |
| Samsung M2020 Series                          | 2         | 3.33%   |
| HP LaserJet Professional P1102w               | 2         | 3.33%   |
| HP Ink Tank Wireless 410 series               | 2         | 3.33%   |
| HP Deskjet 3050 J610 series                   | 2         | 3.33%   |
| HP Deskjet 2540 series                        | 2         | 3.33%   |
| Canon PIXMA MG3600 Series                     | 2         | 3.33%   |
| Canon G3000 series                            | 2         | 3.33%   |
| Xerox Phaser 3040                             | 1         | 1.67%   |
| Seiko Epson XP-230 Series                     | 1         | 1.67%   |
| Seiko Epson Thermal Receipt Printer [TM-T20]  | 1         | 1.67%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.67%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]  | 1         | 1.67%   |
| Seiko Epson L805 Series                       | 1         | 1.67%   |
| Seiko Epson L380 Series                       | 1         | 1.67%   |
| Seiko Epson L360 Series                       | 1         | 1.67%   |
| Seiko Epson ET-2700 Series                    | 1         | 1.67%   |
| Samsung SCX-4623 Series                       | 1         | 1.67%   |
| Samsung SCX-4200 series                       | 1         | 1.67%   |
| Samsung M332x 382x 402x Series                | 1         | 1.67%   |
| MIIIW MW Keyboard Air Mini                    | 1         | 1.67%   |
| HP LaserJet P2015 series                      | 1         | 1.67%   |
| HP LaserJet 1018                              | 1         | 1.67%   |
| HP DeskJet F4200 series                       | 1         | 1.67%   |
| HP DeskJet F4100 Printer series               | 1         | 1.67%   |
| HP DeskJet D1360                              | 1         | 1.67%   |
| HP DeskJet 3630 series                        | 1         | 1.67%   |
| HP DeskJet 2300 series                        | 1         | 1.67%   |
| HP DeskJet 2130 series                        | 1         | 1.67%   |
| HP Deskjet 1510                               | 1         | 1.67%   |
| Canon G4010 series                            | 1         | 1.67%   |
| Canon G4000 series                            | 1         | 1.67%   |
| Canon G3010 series                            | 1         | 1.67%   |
| Brother HL-5250DN Printer                     | 1         | 1.67%   |
| Brother DCP-7040                              | 1         | 1.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Hewlett-Packard | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP ScanJet 2400c                   | 1         | 20%     |
| HP Scanjet 200                     | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 20%     |
| Canon CanoScan LiDE 110            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1453      | 21.1%   |
| Microdia                               | 839       | 12.18%  |
| Realtek Semiconductor                  | 693       | 10.06%  |
| Quanta                                 | 633       | 9.19%   |
| Silicon Motion                         | 556       | 8.07%   |
| Sunplus Innovation Technology          | 518       | 7.52%   |
| Bison Electronics                      | 374       | 5.43%   |
| IMC Networks                           | 318       | 4.62%   |
| Suyin                                  | 288       | 4.18%   |
| Syntek                                 | 230       | 3.34%   |
| Alcor Micro                            | 130       | 1.89%   |
| Apple                                  | 99        | 1.44%   |
| Acer                                   | 95        | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) | 88        | 1.28%   |
| Logitech                               | 61        | 0.89%   |
| Samsung Electronics                    | 57        | 0.83%   |
| Ricoh                                  | 50        | 0.73%   |
| ALi                                    | 43        | 0.62%   |
| Sonix Technology                       | 40        | 0.58%   |
| Lite-On Technology                     | 26        | 0.38%   |
| Importek                               | 25        | 0.36%   |
| OmniVision Technologies                | 24        | 0.35%   |
| Z-Star Microelectronics                | 20        | 0.29%   |
| icSpring                               | 20        | 0.29%   |
| Unknown                                | 18        | 0.26%   |
| Y Media                                | 14        | 0.2%    |
| SunplusIT                              | 13        | 0.19%   |
| Lenovo                                 | 12        | 0.17%   |
| Generalplus Technology                 | 12        | 0.17%   |
| LG Electronics                         | 10        | 0.15%   |
| Intel                                  | 9         | 0.13%   |
| Pixart Imaging                         | 8         | 0.12%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 0.1%    |
| Primax Electronics                     | 7         | 0.1%    |
| Microsoft                              | 7         | 0.1%    |
| Luxvisions Innotech Limited            | 7         | 0.1%    |
| Image Processor                        | 7         | 0.1%    |
| Camera                                 | 7         | 0.1%    |
| Jieli Technology                       | 6         | 0.09%   |
| GEMBIRD                                | 6         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 323       | 4.69%   |
| Realtek Integrated_Webcam_HD              | 303       | 4.4%    |
| Quanta HD User Facing                     | 278       | 4.03%   |
| Chicony HD WebCam                         | 263       | 3.81%   |
| Chicony HD User Facing                    | 226       | 3.28%   |
| Sunplus Integrated_Webcam_HD              | 209       | 3.03%   |
| Silicon Motion Web Camera                 | 208       | 3.02%   |
| Quanta VGA WebCam                         | 181       | 2.63%   |
| Chicony Integrated Camera                 | 161       | 2.34%   |
| Chicony VGA WebCam                        | 143       | 2.07%   |
| Syntek Integrated Camera                  | 130       | 1.89%   |
| Sunplus HD WebCam                         | 113       | 1.64%   |
| Realtek Integrated Webcam                 | 113       | 1.64%   |
| Quanta HD Webcam                          | 104       | 1.51%   |
| Chicony USB 2.0 Camera                    | 92        | 1.33%   |
| Alcor Micro USB 2.0 Camera                | 80        | 1.16%   |
| Microdia Laptop_Integrated_Webcam_HD      | 78        | 1.13%   |
| Bison BisonCam, NB Pro                    | 76        | 1.1%    |
| Bison EasyCamera                          | 63        | 0.91%   |
| Samsung Galaxy series, misc. (MTP mode)   | 57        | 0.83%   |
| Realtek USB Camera                        | 57        | 0.83%   |
| Microdia Dell Laptop Integrated Webcam HD | 57        | 0.83%   |
| IMC Networks Integrated Camera            | 56        | 0.81%   |
| Silicon Motion WebCam SC-10HDD12636N      | 54        | 0.78%   |
| Microdia Integrated Webcam HD             | 52        | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 51        | 0.74%   |
| Bison VGA WebCam                          | 46        | 0.67%   |
| Suyin Integrated_Webcam_HD                | 45        | 0.65%   |
| Silicon Motion WebCam SCB-1100N           | 43        | 0.62%   |
| Silicon Motion WebCam SC-13HDL11939N      | 43        | 0.62%   |
| IMC Networks USB2.0 HD UVC WebCam         | 43        | 0.62%   |
| Syntek EasyCamera                         | 41        | 0.59%   |
| Sonix USB2.0 HD UVC WebCam                | 40        | 0.58%   |
| Silicon Motion WebCam SC-0311139N         | 40        | 0.58%   |
| Realtek HD WebCam                         | 40        | 0.58%   |
| Bison Lenovo EasyCamera                   | 40        | 0.58%   |
| Chicony EasyCamera                        | 39        | 0.57%   |
| Microdia Integrated Webcam                | 37        | 0.54%   |
| Realtek EasyCamera                        | 36        | 0.52%   |
| Apple FaceTime HD Camera                  | 36        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 296       | 49.33%  |
| Synaptics                  | 63        | 10.5%   |
| AuthenTec                  | 63        | 10.5%   |
| Upek                       | 58        | 9.67%   |
| Shenzhen Goodix Technology | 52        | 8.67%   |
| LighTuning Technology      | 32        | 5.33%   |
| Samsung Electronics        | 17        | 2.83%   |
| Elan Microelectronics      | 10        | 1.67%   |
| STMicroelectronics         | 4         | 0.67%   |
| Focal-systems.Corp         | 2         | 0.33%   |
| Next Biometrics            | 1         | 0.17%   |
| DigitalPersona             | 1         | 0.17%   |
| Dell                       | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 112       | 18.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 49        | 8.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 5%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 27        | 4.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 4.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 26        | 4.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 26        | 4.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 24        | 4%      |
| Validity Sensors Fingerprint scanner                                       | 22        | 3.67%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 20        | 3.33%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 3.17%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 3%      |
| Samsung Fingerprint Device                                                 | 17        | 2.83%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 2.5%    |
| AuthenTec AES2810                                                          | 14        | 2.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.33%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 13        | 2.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 2%      |
| Validity Sensors VFS491                                                    | 11        | 1.83%   |
| AuthenTec Fingerprint Sensor                                               | 11        | 1.83%   |
| Elan ELAN:Fingerprint                                                      | 10        | 1.67%   |
| Synaptics  WBDI                                                            | 9         | 1.5%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.33%   |
| Upek TCS5B Fingerprint sensor                                              | 8         | 1.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.17%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1%      |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.83%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.67%   |
| AuthenTec AES1600                                                          | 4         | 0.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.33%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.33%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.17%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.17%   |
| Synaptics WBDI Device                                                      | 1         | 0.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 88        | 54.66%  |
| Alcor Micro               | 25        | 15.53%  |
| Lenovo                    | 14        | 8.7%    |
| Upek                      | 10        | 6.21%   |
| Giesecke & Devrient       | 8         | 4.97%   |
| Watchdata                 | 5         | 3.11%   |
| Aladdin Knowledge Systems | 5         | 3.11%   |
| O2 Micro                  | 3         | 1.86%   |
| SCM Microsystems          | 1         | 0.62%   |
| Gemalto (was Gemplus)     | 1         | 0.62%   |
| Advanced Card Systems     | 1         | 0.62%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 25        | 15.53%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 15.53%  |
| Broadcom 5880                                                                | 23        | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 13.66%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 11.18%  |
| Lenovo Integrated Smart Card Reader                                          | 14        | 8.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 6.21%   |
| Giesecke & Devrient StarSign CUT                                             | 6         | 3.73%   |
| Watchdata USB Key                                                            | 5         | 3.11%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 3.11%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.24%   |
| Giesecke & Devrient StarSign CUT S                                           | 2         | 1.24%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.62%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.62%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.62%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.62%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5775      | 75.56%  |
| 1     | 1616      | 21.14%  |
| 2     | 210       | 2.75%   |
| 3     | 24        | 0.31%   |
| 4     | 9         | 0.12%   |
| 7     | 4         | 0.05%   |
| 5     | 3         | 0.04%   |
| 8     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 628       | 29.61%  |
| Fingerprint reader       | 598       | 28.19%  |
| Multimedia controller    | 226       | 10.66%  |
| Net/wireless             | 176       | 8.3%    |
| Chipcard                 | 142       | 6.69%   |
| Bluetooth                | 89        | 4.2%    |
| Camera                   | 67        | 3.16%   |
| Storage                  | 44        | 2.07%   |
| Communication controller | 44        | 2.07%   |
| Sound                    | 35        | 1.65%   |
| Net/ethernet             | 26        | 1.23%   |
| Flash memory             | 21        | 0.99%   |
| Card reader              | 8         | 0.38%   |
| Modem                    | 7         | 0.33%   |
| Firewire controller      | 4         | 0.19%   |
| Network                  | 3         | 0.14%   |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |

