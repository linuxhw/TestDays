Linux in Kazakhstan - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Kazakhstan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Kazakhstan/Desktop/README.md) and [notebooks](/Location/Kazakhstan/Notebook/README.md).

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

Total: 620

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 5750G                | Notebook    | [7e229f1bb3](https://linux-hardware.org/?probe=7e229f1bb3) | May 06, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [20d01c5be2](https://linux-hardware.org/?probe=20d01c5be2) | May 06, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [278ffc84de](https://linux-hardware.org/?probe=278ffc84de) | May 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [20420f0426](https://linux-hardware.org/?probe=20420f0426) | May 02, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [62b044e6e7](https://linux-hardware.org/?probe=62b044e6e7) | Apr 29, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [9444fc82ad](https://linux-hardware.org/?probe=9444fc82ad) | Apr 29, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [6ee3965a21](https://linux-hardware.org/?probe=6ee3965a21) | Apr 29, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [f05f85c143](https://linux-hardware.org/?probe=f05f85c143) | Apr 28, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [f7290e5680](https://linux-hardware.org/?probe=f7290e5680) | Apr 25, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [f0f822fa1b](https://linux-hardware.org/?probe=f0f822fa1b) | Apr 25, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [0ca4241f02](https://linux-hardware.org/?probe=0ca4241f02) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [0324fe4cc6](https://linux-hardware.org/?probe=0324fe4cc6) | Apr 23, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [37a57a968f](https://linux-hardware.org/?probe=37a57a968f) | Apr 19, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [5f4832051e](https://linux-hardware.org/?probe=5f4832051e) | Apr 14, 2022 |
| ASRock        | B250 Pro4                   | Desktop     | [cb77fb75b5](https://linux-hardware.org/?probe=cb77fb75b5) | Apr 14, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [32371c52a6](https://linux-hardware.org/?probe=32371c52a6) | Apr 13, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [ef0b36db62](https://linux-hardware.org/?probe=ef0b36db62) | Apr 11, 2022 |
| MSI           | MS-7365                     | Desktop     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                      | Desktop     | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| Dell          | Latitude 3520               | Notebook    | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | Notebook    | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| HP            | 0A08h                       | Desktop     | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [e3071e1f70](https://linux-hardware.org/?probe=e3071e1f70) | Apr 02, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [609849a9e7](https://linux-hardware.org/?probe=609849a9e7) | Apr 02, 2022 |
| MSI           | MS-7346                     | Desktop     | [207eda5f34](https://linux-hardware.org/?probe=207eda5f34) | Mar 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9acdb9482d](https://linux-hardware.org/?probe=9acdb9482d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d941ebafc6](https://linux-hardware.org/?probe=d941ebafc6) | Mar 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a767a6e123](https://linux-hardware.org/?probe=a767a6e123) | Mar 28, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [27b65f8212](https://linux-hardware.org/?probe=27b65f8212) | Mar 23, 2022 |
| ASRock        | 890GX Extreme4              | Desktop     | [3c57e1ac31](https://linux-hardware.org/?probe=3c57e1ac31) | Mar 20, 2022 |
| ASRock        | 890GX Extreme4              | Desktop     | [8c38c582bf](https://linux-hardware.org/?probe=8c38c582bf) | Mar 20, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [406c69d7cd](https://linux-hardware.org/?probe=406c69d7cd) | Mar 18, 2022 |
| MSI           | MS-7346                     | Desktop     | [2c94f0863d](https://linux-hardware.org/?probe=2c94f0863d) | Mar 16, 2022 |
| Dell          | 0V6XGW A01                  | Desktop     | [7b091c2035](https://linux-hardware.org/?probe=7b091c2035) | Mar 13, 2022 |
| MSI           | MS-7346                     | Desktop     | [0be963d491](https://linux-hardware.org/?probe=0be963d491) | Mar 13, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [59a21d0aa2](https://linux-hardware.org/?probe=59a21d0aa2) | Mar 11, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [6f53445c9d](https://linux-hardware.org/?probe=6f53445c9d) | Mar 05, 2022 |
| MSI           | MS-7346                     | Desktop     | [369821f3f9](https://linux-hardware.org/?probe=369821f3f9) | Feb 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [de5c811791](https://linux-hardware.org/?probe=de5c811791) | Feb 21, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [565ef5309f](https://linux-hardware.org/?probe=565ef5309f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [823e19e6d3](https://linux-hardware.org/?probe=823e19e6d3) | Feb 19, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [21e91da000](https://linux-hardware.org/?probe=21e91da000) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [38d5887ae2](https://linux-hardware.org/?probe=38d5887ae2) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ed75c609e4](https://linux-hardware.org/?probe=ed75c609e4) | Feb 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [470a550d41](https://linux-hardware.org/?probe=470a550d41) | Feb 16, 2022 |
| ECS           | G41T-R3                     | Desktop     | [ad4ba21957](https://linux-hardware.org/?probe=ad4ba21957) | Feb 13, 2022 |
| Lenovo        | ThinkPad T460 20FMS2TG0D    | Notebook    | [f51933de6d](https://linux-hardware.org/?probe=f51933de6d) | Feb 10, 2022 |
| Biostar       | H61MLV                      | Desktop     | [675b0c3faf](https://linux-hardware.org/?probe=675b0c3faf) | Feb 07, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [cd91d445e6](https://linux-hardware.org/?probe=cd91d445e6) | Jan 30, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [c1703ee8ee](https://linux-hardware.org/?probe=c1703ee8ee) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | Notebook    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a6a7106d83](https://linux-hardware.org/?probe=a6a7106d83) | Jan 26, 2022 |
| ASRock        | G31M-VS                     | Desktop     | [d456869dd7](https://linux-hardware.org/?probe=d456869dd7) | Jan 14, 2022 |
| Samsung       | N100SP                      | Notebook    | [47ec2e67d9](https://linux-hardware.org/?probe=47ec2e67d9) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0b4b86fd4d](https://linux-hardware.org/?probe=0b4b86fd4d) | Dec 30, 2021 |
| Acer          | Predator PO3-620            | Desktop     | [d33f608e2e](https://linux-hardware.org/?probe=d33f608e2e) | Dec 27, 2021 |
| HP            | Pavilion 15                 | Notebook    | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| eMachines     | ET1850                      | Desktop     | [cffccff919](https://linux-hardware.org/?probe=cffccff919) | Dec 20, 2021 |
| Lenovo        | MAHOBAY No DPK              | All in one  | [968b139684](https://linux-hardware.org/?probe=968b139684) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [b294d0719f](https://linux-hardware.org/?probe=b294d0719f) | Dec 14, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [38cf5730b3](https://linux-hardware.org/?probe=38cf5730b3) | Dec 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [4501078e9a](https://linux-hardware.org/?probe=4501078e9a) | Dec 08, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [985ed9e52c](https://linux-hardware.org/?probe=985ed9e52c) | Dec 05, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [16586b274a](https://linux-hardware.org/?probe=16586b274a) | Nov 20, 2021 |
| ASUSTek       | X51RL                       | Notebook    | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [924d961707](https://linux-hardware.org/?probe=924d961707) | Nov 12, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [67a9ba5988](https://linux-hardware.org/?probe=67a9ba5988) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [9145964032](https://linux-hardware.org/?probe=9145964032) | Oct 30, 2021 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [83857e3215](https://linux-hardware.org/?probe=83857e3215) | Oct 29, 2021 |
| ASUSTek       | N56DP                       | Notebook    | [7332da68ec](https://linux-hardware.org/?probe=7332da68ec) | Oct 25, 2021 |
| Biostar       | H61MLV2                     | Desktop     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1c2a383c4f](https://linux-hardware.org/?probe=1c2a383c4f) | Oct 20, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e7abad8af5](https://linux-hardware.org/?probe=e7abad8af5) | Oct 20, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [10a67c9e23](https://linux-hardware.org/?probe=10a67c9e23) | Oct 16, 2021 |
| Acer          | Aspire A315-55KG            | Notebook    | [79534f4c8c](https://linux-hardware.org/?probe=79534f4c8c) | Oct 10, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [1103bd0a01](https://linux-hardware.org/?probe=1103bd0a01) | Oct 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [008072f061](https://linux-hardware.org/?probe=008072f061) | Oct 05, 2021 |
| Athermiter... | X99 Beta vk.com/@2485616    | Desktop     | [6006da0a12](https://linux-hardware.org/?probe=6006da0a12) | Oct 01, 2021 |
| ASRock        | G31M-VS                     | Desktop     | [79a5ef3dad](https://linux-hardware.org/?probe=79a5ef3dad) | Sep 22, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [96463d6903](https://linux-hardware.org/?probe=96463d6903) | Sep 16, 2021 |
| Lenovo        | ThinkPad T480 20L6SBGK00    | Notebook    | [fc6636e0b5](https://linux-hardware.org/?probe=fc6636e0b5) | Sep 09, 2021 |
| HP            | ProBook 4320s               | Notebook    | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| ASRock        | G31M-VS                     | Desktop     | [ea71d93f96](https://linux-hardware.org/?probe=ea71d93f96) | Aug 26, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [d35224de9f](https://linux-hardware.org/?probe=d35224de9f) | Aug 07, 2021 |
| HP            | Pavilion dm1                | Notebook    | [ac0e534d86](https://linux-hardware.org/?probe=ac0e534d86) | Aug 01, 2021 |
| ASUSTek       | H61M-E                      | Desktop     | [d312398917](https://linux-hardware.org/?probe=d312398917) | Jul 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | 635                         | Notebook    | [06f1ff97b5](https://linux-hardware.org/?probe=06f1ff97b5) | Jul 24, 2021 |
| Elenberg      | EL_T1011                    | Notebook    | [c2e05805b1](https://linux-hardware.org/?probe=c2e05805b1) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [d977beba9e](https://linux-hardware.org/?probe=d977beba9e) | Jul 22, 2021 |
| HP            | 15                          | Notebook    | [fcc367258f](https://linux-hardware.org/?probe=fcc367258f) | Jul 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [b7fe3d0d08](https://linux-hardware.org/?probe=b7fe3d0d08) | Jul 16, 2021 |
| Lenovo        | ThinkPad T580 20L9S0D100    | Notebook    | [e7f9397916](https://linux-hardware.org/?probe=e7f9397916) | Jul 02, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [1d185733d4](https://linux-hardware.org/?probe=1d185733d4) | Jun 24, 2021 |
| Lenovo        | 0x36BF SDK0J40688 WIN 34... | All in one  | [5ee73859b3](https://linux-hardware.org/?probe=5ee73859b3) | Jun 21, 2021 |
| Lenovo        | 0x36BF SDK0J40688 WIN 34... | All in one  | [001cc3458f](https://linux-hardware.org/?probe=001cc3458f) | Jun 21, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [ad17a21f6e](https://linux-hardware.org/?probe=ad17a21f6e) | Jun 16, 2021 |
| Acer          | Mandolin                    | Notebook    | [c5a4b06851](https://linux-hardware.org/?probe=c5a4b06851) | Jun 13, 2021 |
| Biostar       | H81MHV3                     | Desktop     | [0a593d3966](https://linux-hardware.org/?probe=0a593d3966) | Jun 01, 2021 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | Notebook    | [6b37e8a34b](https://linux-hardware.org/?probe=6b37e8a34b) | May 25, 2021 |
| HP            | 8245 001                    | All in one  | [40434f824a](https://linux-hardware.org/?probe=40434f824a) | May 24, 2021 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1b292e7e77](https://linux-hardware.org/?probe=1b292e7e77) | May 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e74c6f6436](https://linux-hardware.org/?probe=e74c6f6436) | May 16, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [b79dcdb648](https://linux-hardware.org/?probe=b79dcdb648) | May 03, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [b02527f8e5](https://linux-hardware.org/?probe=b02527f8e5) | May 03, 2021 |
| Intel         | DB65AL AAG12530-306         | Desktop     | [8cf2183901](https://linux-hardware.org/?probe=8cf2183901) | May 03, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [1a6e48b6a6](https://linux-hardware.org/?probe=1a6e48b6a6) | Apr 29, 2021 |
| MSI           | P55-GD65                    | Desktop     | [773fc40103](https://linux-hardware.org/?probe=773fc40103) | Apr 24, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [b4f123b6df](https://linux-hardware.org/?probe=b4f123b6df) | Apr 20, 2021 |
| Acer          | AO722                       | Notebook    | [6d09f4a364](https://linux-hardware.org/?probe=6d09f4a364) | Apr 20, 2021 |
| ASUSTek       | X550LA                      | Notebook    | [69647941af](https://linux-hardware.org/?probe=69647941af) | Apr 20, 2021 |
| Acer          | AOHAPPY2                    | Notebook    | [1ab9a823ac](https://linux-hardware.org/?probe=1ab9a823ac) | Apr 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [895cfbdea8](https://linux-hardware.org/?probe=895cfbdea8) | Mar 31, 2021 |
| HP            | ENVY m6                     | Notebook    | [1f794c0fc3](https://linux-hardware.org/?probe=1f794c0fc3) | Mar 29, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [324235179d](https://linux-hardware.org/?probe=324235179d) | Mar 19, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e373906f4c](https://linux-hardware.org/?probe=e373906f4c) | Mar 17, 2021 |
| ASUSTek       | S301LA                      | Notebook    | [c8c4934145](https://linux-hardware.org/?probe=c8c4934145) | Mar 17, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af8d6ec07e](https://linux-hardware.org/?probe=af8d6ec07e) | Mar 17, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | Desktop     | [003b473b29](https://linux-hardware.org/?probe=003b473b29) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| Acer          | Predator PH317-54           | Notebook    | [0e97801264](https://linux-hardware.org/?probe=0e97801264) | Mar 12, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [c58e02d129](https://linux-hardware.org/?probe=c58e02d129) | Mar 07, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [d08f840a09](https://linux-hardware.org/?probe=d08f840a09) | Mar 07, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [676848c0ea](https://linux-hardware.org/?probe=676848c0ea) | Mar 01, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [9924631e4c](https://linux-hardware.org/?probe=9924631e4c) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [fb1f894d4f](https://linux-hardware.org/?probe=fb1f894d4f) | Feb 22, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [4e22c88014](https://linux-hardware.org/?probe=4e22c88014) | Feb 18, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [7b39e6bd46](https://linux-hardware.org/?probe=7b39e6bd46) | Feb 15, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [19b6410050](https://linux-hardware.org/?probe=19b6410050) | Feb 12, 2021 |
| Unknown       | Unknown                     | Soc         | [15a8630182](https://linux-hardware.org/?probe=15a8630182) | Feb 06, 2021 |
| Sony          | VGN-NR430E                  | Notebook    | [62beb0a340](https://linux-hardware.org/?probe=62beb0a340) | Feb 04, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e5c078c0d7](https://linux-hardware.org/?probe=e5c078c0d7) | Jan 23, 2021 |
| Acer          | Aspire A315-55KG            | Notebook    | [c62e2ea4ae](https://linux-hardware.org/?probe=c62e2ea4ae) | Jan 22, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [5a8bae0bc9](https://linux-hardware.org/?probe=5a8bae0bc9) | Jan 17, 2021 |
| Acer          | Aspire V3-551G              | Notebook    | [16932ea052](https://linux-hardware.org/?probe=16932ea052) | Jan 13, 2021 |
| Acer          | Aspire V3-551G              | Notebook    | [b697976568](https://linux-hardware.org/?probe=b697976568) | Jan 13, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [80552a83cd](https://linux-hardware.org/?probe=80552a83cd) | Jan 11, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [e99dbcff3b](https://linux-hardware.org/?probe=e99dbcff3b) | Jan 11, 2021 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [07ee20e1ca](https://linux-hardware.org/?probe=07ee20e1ca) | Jan 02, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [a673d3a8c7](https://linux-hardware.org/?probe=a673d3a8c7) | Dec 23, 2020 |
| Acer          | Extensa 2519                | Notebook    | [bc19a19f7c](https://linux-hardware.org/?probe=bc19a19f7c) | Dec 22, 2020 |
| eMachines     | ET1850                      | Desktop     | [c50ea84e0d](https://linux-hardware.org/?probe=c50ea84e0d) | Dec 18, 2020 |
| eMachines     | ET1850                      | Desktop     | [102dd1fc47](https://linux-hardware.org/?probe=102dd1fc47) | Dec 18, 2020 |
| ASRock        | N68-S                       | Desktop     | [3533e8dac5](https://linux-hardware.org/?probe=3533e8dac5) | Dec 16, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [cd5bccf387](https://linux-hardware.org/?probe=cd5bccf387) | Dec 13, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f6edf147c0](https://linux-hardware.org/?probe=f6edf147c0) | Dec 13, 2020 |
| Gigabyte      | Z87M-HD3                    | Desktop     | [42b04fe8bb](https://linux-hardware.org/?probe=42b04fe8bb) | Dec 06, 2020 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [874d67029b](https://linux-hardware.org/?probe=874d67029b) | Dec 02, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [7041c80e3b](https://linux-hardware.org/?probe=7041c80e3b) | Nov 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d081baf21f](https://linux-hardware.org/?probe=d081baf21f) | Nov 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f149c45438](https://linux-hardware.org/?probe=f149c45438) | Nov 21, 2020 |
| ASRock        | N68-S                       | Desktop     | [6692a45ac3](https://linux-hardware.org/?probe=6692a45ac3) | Nov 14, 2020 |
| MSI           | X58 Pro-E                   | Desktop     | [d85b89db2e](https://linux-hardware.org/?probe=d85b89db2e) | Nov 11, 2020 |
| Dell          | G3 3500                     | Notebook    | [d6386ecea5](https://linux-hardware.org/?probe=d6386ecea5) | Nov 07, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [29bf11dd7c](https://linux-hardware.org/?probe=29bf11dd7c) | Nov 03, 2020 |
| MSI           | MS-7346                     | Desktop     | [b297f8721b](https://linux-hardware.org/?probe=b297f8721b) | Oct 31, 2020 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fec4f6d683](https://linux-hardware.org/?probe=fec4f6d683) | Oct 31, 2020 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [2c2ff12670](https://linux-hardware.org/?probe=2c2ff12670) | Oct 31, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [42aa2abab3](https://linux-hardware.org/?probe=42aa2abab3) | Oct 26, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [f6e1215c02](https://linux-hardware.org/?probe=f6e1215c02) | Oct 22, 2020 |
| ASUSTek       | U47A                        | Notebook    | [b7c3bb57cf](https://linux-hardware.org/?probe=b7c3bb57cf) | Oct 20, 2020 |
| HP            | Pavilion 17                 | Notebook    | [d016742bce](https://linux-hardware.org/?probe=d016742bce) | Oct 20, 2020 |
| HP            | 250 G3                      | Notebook    | [100536aea2](https://linux-hardware.org/?probe=100536aea2) | Oct 17, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [3ec85a9391](https://linux-hardware.org/?probe=3ec85a9391) | Oct 15, 2020 |
| ASRock        | H61iCafe                    | Desktop     | [a44ad4ab39](https://linux-hardware.org/?probe=a44ad4ab39) | Oct 08, 2020 |
| Gigabyte      | P55A-UD3R                   | Desktop     | [be3a1d8c92](https://linux-hardware.org/?probe=be3a1d8c92) | Oct 05, 2020 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1ad6b7a819](https://linux-hardware.org/?probe=1ad6b7a819) | Oct 01, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [1f6a3f87d7](https://linux-hardware.org/?probe=1f6a3f87d7) | Sep 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [e9482aee87](https://linux-hardware.org/?probe=e9482aee87) | Sep 28, 2020 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [5c317250db](https://linux-hardware.org/?probe=5c317250db) | Sep 27, 2020 |
| HP            | 250 G3                      | Notebook    | [c0207d3878](https://linux-hardware.org/?probe=c0207d3878) | Sep 24, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [71b1302861](https://linux-hardware.org/?probe=71b1302861) | Sep 24, 2020 |
| Quanta        | 2AC5                        | All in one  | [55450c73c0](https://linux-hardware.org/?probe=55450c73c0) | Sep 13, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [4b713d932f](https://linux-hardware.org/?probe=4b713d932f) | Sep 10, 2020 |
| Lenovo        | ThinkPad E580 20KS004GRK    | Notebook    | [0a7dbcc4b4](https://linux-hardware.org/?probe=0a7dbcc4b4) | Sep 09, 2020 |
| HP            | Pavilion 17                 | Notebook    | [994f18c32f](https://linux-hardware.org/?probe=994f18c32f) | Sep 09, 2020 |
| HP            | ProLiant DL360 G5           | Server      | [b3175c4255](https://linux-hardware.org/?probe=b3175c4255) | Sep 05, 2020 |
| Acer          | Aspire ES1-523              | Notebook    | [e335200dd8](https://linux-hardware.org/?probe=e335200dd8) | Sep 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9968af0598](https://linux-hardware.org/?probe=9968af0598) | Aug 25, 2020 |
| ASUSTek       | 1001HA                      | Notebook    | [7935f0bc4a](https://linux-hardware.org/?probe=7935f0bc4a) | Aug 23, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [b6c1db4e4f](https://linux-hardware.org/?probe=b6c1db4e4f) | Aug 23, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [5b434b68bf](https://linux-hardware.org/?probe=5b434b68bf) | Aug 23, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [db44f2aca3](https://linux-hardware.org/?probe=db44f2aca3) | Aug 22, 2020 |
| Biostar       | G41-M7                      | Desktop     | [a50a75af2a](https://linux-hardware.org/?probe=a50a75af2a) | Aug 11, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [81c427fc6a](https://linux-hardware.org/?probe=81c427fc6a) | Aug 09, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [c29fe11da1](https://linux-hardware.org/?probe=c29fe11da1) | Aug 05, 2020 |
| Dell          | Latitude E6440              | Notebook    | [a023894374](https://linux-hardware.org/?probe=a023894374) | Aug 01, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [790a29d708](https://linux-hardware.org/?probe=790a29d708) | Jul 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [10566660a8](https://linux-hardware.org/?probe=10566660a8) | Jul 17, 2020 |
| Intel         | DB65AL AAG12530-306         | Desktop     | [03daa1b244](https://linux-hardware.org/?probe=03daa1b244) | Jul 09, 2020 |
| Intel         | DB65AL AAG12530-306         | Desktop     | [ca67687f31](https://linux-hardware.org/?probe=ca67687f31) | Jul 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b762726155](https://linux-hardware.org/?probe=b762726155) | Jul 08, 2020 |
| Intel         | DB65AL AAG12530-306         | Desktop     | [c64ad86725](https://linux-hardware.org/?probe=c64ad86725) | Jul 07, 2020 |
| Intel         | DB65AL AAG12530-306         | Desktop     | [c2c3f83b11](https://linux-hardware.org/?probe=c2c3f83b11) | Jul 07, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [812155ca3b](https://linux-hardware.org/?probe=812155ca3b) | Jun 29, 2020 |
| HP            | ProLiant DL360 G5           | Server      | [2af0fad914](https://linux-hardware.org/?probe=2af0fad914) | Jun 19, 2020 |
| HP            | ProLiant DL360 G5           | Server      | [908a5e8c78](https://linux-hardware.org/?probe=908a5e8c78) | Jun 19, 2020 |
| Acidanther... | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [30536633cf](https://linux-hardware.org/?probe=30536633cf) | Jun 10, 2020 |
| ASUSTek       | H61M-K                      | Desktop     | [955b5a5e27](https://linux-hardware.org/?probe=955b5a5e27) | Jun 08, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [61c053a60a](https://linux-hardware.org/?probe=61c053a60a) | May 31, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [b524806f7a](https://linux-hardware.org/?probe=b524806f7a) | May 31, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [1509883885](https://linux-hardware.org/?probe=1509883885) | May 31, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [5d042bc26a](https://linux-hardware.org/?probe=5d042bc26a) | May 31, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [5c70b2f02d](https://linux-hardware.org/?probe=5c70b2f02d) | May 31, 2020 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [c0fc07b2e3](https://linux-hardware.org/?probe=c0fc07b2e3) | May 27, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [d2c4164b1c](https://linux-hardware.org/?probe=d2c4164b1c) | May 24, 2020 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a34ec38bca](https://linux-hardware.org/?probe=a34ec38bca) | May 22, 2020 |
| ASRock        | Q1900M                      | Desktop     | [5998519fca](https://linux-hardware.org/?probe=5998519fca) | May 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [470074b671](https://linux-hardware.org/?probe=470074b671) | May 14, 2020 |
| Acidanther... | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [38f55a1a22](https://linux-hardware.org/?probe=38f55a1a22) | May 10, 2020 |
| Acer          | TravelMate 5742G            | Notebook    | [3b5409d855](https://linux-hardware.org/?probe=3b5409d855) | May 08, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c2f0ff23ad](https://linux-hardware.org/?probe=c2f0ff23ad) | May 02, 2020 |
| Gigabyte      | EP43-S3L                    | Desktop     | [ce53a132ad](https://linux-hardware.org/?probe=ce53a132ad) | Apr 22, 2020 |
| ASUSTek       | U47A                        | Notebook    | [3b85d1aeb4](https://linux-hardware.org/?probe=3b85d1aeb4) | Apr 20, 2020 |
| HPE           | ProLiant DL360 Gen10        | Server      | [326e6f0067](https://linux-hardware.org/?probe=326e6f0067) | Apr 12, 2020 |
| HP            | Compaq 6510b (GB867EA#AC... | Notebook    | [ebb74b0be7](https://linux-hardware.org/?probe=ebb74b0be7) | Apr 06, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [b44935169f](https://linux-hardware.org/?probe=b44935169f) | Mar 31, 2020 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [8dddac7046](https://linux-hardware.org/?probe=8dddac7046) | Mar 25, 2020 |
| Intel         | DB65AL AAG12530-306         | Desktop     | [37eadd87d7](https://linux-hardware.org/?probe=37eadd87d7) | Mar 24, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [57ade58668](https://linux-hardware.org/?probe=57ade58668) | Mar 22, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [7ad6b7b58b](https://linux-hardware.org/?probe=7ad6b7b58b) | Mar 22, 2020 |
| ASRock        | H61M-VG3                    | Desktop     | [13be5c5114](https://linux-hardware.org/?probe=13be5c5114) | Mar 14, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [c219a39d00](https://linux-hardware.org/?probe=c219a39d00) | Mar 05, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [6f409ce91c](https://linux-hardware.org/?probe=6f409ce91c) | Mar 05, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [fd882c0a0a](https://linux-hardware.org/?probe=fd882c0a0a) | Mar 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [dc2a796221](https://linux-hardware.org/?probe=dc2a796221) | Mar 01, 2020 |
| HP            | Presario CQ57               | Notebook    | [3de9f386b3](https://linux-hardware.org/?probe=3de9f386b3) | Feb 19, 2020 |
| Acer          | Aspire V5-572P              | Notebook    | [e87893d9ae](https://linux-hardware.org/?probe=e87893d9ae) | Feb 17, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [1a22c7e1bd](https://linux-hardware.org/?probe=1a22c7e1bd) | Feb 16, 2020 |
| HP            | Presario CQ57               | Notebook    | [e89b7e8846](https://linux-hardware.org/?probe=e89b7e8846) | Feb 14, 2020 |
| Acer          | Aspire XXXX                 | Notebook    | [ce7f974b21](https://linux-hardware.org/?probe=ce7f974b21) | Feb 11, 2020 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | Desktop     | [bdd6336c5c](https://linux-hardware.org/?probe=bdd6336c5c) | Feb 10, 2020 |
| ASUSTek       | H81-GAMER                   | Desktop     | [d8091352aa](https://linux-hardware.org/?probe=d8091352aa) | Feb 09, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [fc9249082d](https://linux-hardware.org/?probe=fc9249082d) | Feb 08, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [52e1f3b9aa](https://linux-hardware.org/?probe=52e1f3b9aa) | Feb 07, 2020 |
| Biostar       | B75MU3B                     | Desktop     | [78def272e2](https://linux-hardware.org/?probe=78def272e2) | Feb 06, 2020 |
| Biostar       | B75MU3B                     | Desktop     | [41f7bff636](https://linux-hardware.org/?probe=41f7bff636) | Feb 04, 2020 |
| Biostar       | B75MU3B                     | Desktop     | [9f8d0c9af4](https://linux-hardware.org/?probe=9f8d0c9af4) | Feb 04, 2020 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [4d8aed3739](https://linux-hardware.org/?probe=4d8aed3739) | Jan 31, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | Notebook    | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [d48f36b5c1](https://linux-hardware.org/?probe=d48f36b5c1) | Jan 28, 2020 |
| HP            | Mini 110-3500               | Notebook    | [70d6715873](https://linux-hardware.org/?probe=70d6715873) | Jan 28, 2020 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [016eb3ca52](https://linux-hardware.org/?probe=016eb3ca52) | Jan 22, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | Notebook    | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| OEM           | Unknown                     | Desktop     | [0df2000649](https://linux-hardware.org/?probe=0df2000649) | Jan 12, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [76fd2a40e6](https://linux-hardware.org/?probe=76fd2a40e6) | Jan 10, 2020 |
| ASUSTek       | G46VW                       | Notebook    | [17b6106770](https://linux-hardware.org/?probe=17b6106770) | Dec 27, 2019 |
| ASUSTek       | G46VW                       | Notebook    | [d589eb2b88](https://linux-hardware.org/?probe=d589eb2b88) | Dec 27, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [a0554a7e66](https://linux-hardware.org/?probe=a0554a7e66) | Dec 25, 2019 |
| Intel         | DH55PJ AAE93812-302         | Desktop     | [a57dcf32aa](https://linux-hardware.org/?probe=a57dcf32aa) | Dec 20, 2019 |
| ASRock        | Q1900M                      | Desktop     | [5eb2001292](https://linux-hardware.org/?probe=5eb2001292) | Dec 20, 2019 |
| ASRock        | Q1900M                      | Desktop     | [335780a80a](https://linux-hardware.org/?probe=335780a80a) | Dec 20, 2019 |
| ASRock        | Q1900M                      | Desktop     | [e172c49517](https://linux-hardware.org/?probe=e172c49517) | Dec 13, 2019 |
| ASRock        | Q1900M                      | Desktop     | [64dd5674ce](https://linux-hardware.org/?probe=64dd5674ce) | Dec 12, 2019 |
| HP            | Pavilion g6                 | Notebook    | [2b1a415af5](https://linux-hardware.org/?probe=2b1a415af5) | Dec 12, 2019 |
| ASRock        | Q1900M                      | Desktop     | [3dfc58d779](https://linux-hardware.org/?probe=3dfc58d779) | Dec 12, 2019 |
| ASRock        | Q1900M                      | Desktop     | [4af3f1fddf](https://linux-hardware.org/?probe=4af3f1fddf) | Dec 12, 2019 |
| Lenovo        | V580c 20160                 | Notebook    | [a90c5bff19](https://linux-hardware.org/?probe=a90c5bff19) | Dec 11, 2019 |
| ASRock        | Q1900M                      | Desktop     | [aa067c312b](https://linux-hardware.org/?probe=aa067c312b) | Dec 08, 2019 |
| ASRock        | Q1900M                      | Desktop     | [ad0273e304](https://linux-hardware.org/?probe=ad0273e304) | Dec 08, 2019 |
| ASRock        | Q1900M                      | Desktop     | [d0a2e8e9cf](https://linux-hardware.org/?probe=d0a2e8e9cf) | Dec 08, 2019 |
| ASRock        | Q1900M                      | Desktop     | [ef443fca31](https://linux-hardware.org/?probe=ef443fca31) | Dec 08, 2019 |
| ASRock        | Q1900M                      | Desktop     | [d0137a63e9](https://linux-hardware.org/?probe=d0137a63e9) | Dec 08, 2019 |
| MSI           | B75A-G43                    | Desktop     | [6dd3e491f5](https://linux-hardware.org/?probe=6dd3e491f5) | Dec 04, 2019 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [8444d1b8a5](https://linux-hardware.org/?probe=8444d1b8a5) | Dec 02, 2019 |
| Acer          | Aspire A517-51G             | Notebook    | [73dafbb15e](https://linux-hardware.org/?probe=73dafbb15e) | Nov 25, 2019 |
| Acer          | Aspire A517-51G             | Notebook    | [c4cfb14692](https://linux-hardware.org/?probe=c4cfb14692) | Nov 25, 2019 |
| Acer          | Aspire A517-51G             | Notebook    | [73d25e486f](https://linux-hardware.org/?probe=73d25e486f) | Nov 25, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [f50938f6b5](https://linux-hardware.org/?probe=f50938f6b5) | Nov 24, 2019 |
| Dell          | Latitude 7280               | Notebook    | [d18e59c26a](https://linux-hardware.org/?probe=d18e59c26a) | Nov 23, 2019 |
| Dell          | Latitude 7280               | Notebook    | [0e0be8ef86](https://linux-hardware.org/?probe=0e0be8ef86) | Nov 23, 2019 |
| Dell          | Latitude 7280               | Notebook    | [f6081d54b1](https://linux-hardware.org/?probe=f6081d54b1) | Nov 23, 2019 |
| Dell          | Latitude 7280               | Notebook    | [53190bc040](https://linux-hardware.org/?probe=53190bc040) | Nov 23, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [d93b73ac97](https://linux-hardware.org/?probe=d93b73ac97) | Nov 22, 2019 |
| Acer          | TravelMate 7750G            | Notebook    | [51f6c04c3c](https://linux-hardware.org/?probe=51f6c04c3c) | Oct 30, 2019 |
| Sony          | VPCEH2M1R                   | Notebook    | [7f2ba2a282](https://linux-hardware.org/?probe=7f2ba2a282) | Oct 22, 2019 |
| Acer          | TravelMate 7750G            | Notebook    | [da9e154609](https://linux-hardware.org/?probe=da9e154609) | Oct 15, 2019 |
| HP            | Presario CQ57               | Notebook    | [fee13f8ed2](https://linux-hardware.org/?probe=fee13f8ed2) | Oct 08, 2019 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [0aea361308](https://linux-hardware.org/?probe=0aea361308) | Sep 09, 2019 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [65b6a535e2](https://linux-hardware.org/?probe=65b6a535e2) | Sep 09, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [90108d8974](https://linux-hardware.org/?probe=90108d8974) | Sep 08, 2019 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [c8c1a01026](https://linux-hardware.org/?probe=c8c1a01026) | Sep 04, 2019 |
| ASUSTek       | P8Z77-M                     | Desktop     | [988203ee61](https://linux-hardware.org/?probe=988203ee61) | Aug 31, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [60161c7891](https://linux-hardware.org/?probe=60161c7891) | Aug 28, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e79b69efe5](https://linux-hardware.org/?probe=e79b69efe5) | Aug 20, 2019 |
| EPoX Compu... | nForce4 DDR: 8NPA7I / 8N... | Desktop     | [3912cd3c3a](https://linux-hardware.org/?probe=3912cd3c3a) | Aug 15, 2019 |
| Dell          | 0GDG8Y A00                  | Desktop     | [201fe8de92](https://linux-hardware.org/?probe=201fe8de92) | Aug 10, 2019 |
| MSI           | X470 GAMING PRO             | Desktop     | [01eb97a943](https://linux-hardware.org/?probe=01eb97a943) | Jul 26, 2019 |
| MSI           | X470 GAMING PRO             | Desktop     | [868720add8](https://linux-hardware.org/?probe=868720add8) | Jul 26, 2019 |
| Gigabyte      | P35-DS3L                    | Desktop     | [54231260ff](https://linux-hardware.org/?probe=54231260ff) | Jul 26, 2019 |
| Gigabyte      | P35-DS3L                    | Desktop     | [6db0f0b43c](https://linux-hardware.org/?probe=6db0f0b43c) | Jul 26, 2019 |
| ASUSTek       | X541SC                      | Notebook    | [6458c4f07b](https://linux-hardware.org/?probe=6458c4f07b) | Jul 22, 2019 |
| HP            | Compaq nc6320 (ES479EA#A... | Notebook    | [cf41ab5f1a](https://linux-hardware.org/?probe=cf41ab5f1a) | Jul 15, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [e4b342382f](https://linux-hardware.org/?probe=e4b342382f) | Jul 06, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [8e5d415bf0](https://linux-hardware.org/?probe=8e5d415bf0) | Jul 06, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [f135bbe64e](https://linux-hardware.org/?probe=f135bbe64e) | Jul 06, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [166081ce08](https://linux-hardware.org/?probe=166081ce08) | Jul 04, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [0446579039](https://linux-hardware.org/?probe=0446579039) | Jun 26, 2019 |
| MSI           | G31M3-F V2                  | Desktop     | [3f04b83dfd](https://linux-hardware.org/?probe=3f04b83dfd) | Jun 25, 2019 |
| MSI           | G31M3-F V2                  | Desktop     | [70820eed2b](https://linux-hardware.org/?probe=70820eed2b) | Jun 23, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [03073baad2](https://linux-hardware.org/?probe=03073baad2) | Jun 21, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [f2ec70a030](https://linux-hardware.org/?probe=f2ec70a030) | Jun 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [13304c8b21](https://linux-hardware.org/?probe=13304c8b21) | Jun 20, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [78913150c4](https://linux-hardware.org/?probe=78913150c4) | Jun 20, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [4f2b27bc14](https://linux-hardware.org/?probe=4f2b27bc14) | Jun 19, 2019 |
| HPE           | ProLiant BL460c Gen10       | Server      | [9e91d0ed19](https://linux-hardware.org/?probe=9e91d0ed19) | Jun 14, 2019 |
| HP            | 09F0h                       | Desktop     | [59817a0992](https://linux-hardware.org/?probe=59817a0992) | Jun 09, 2019 |
| ASUSTek       | X541SC                      | Notebook    | [021030c4a5](https://linux-hardware.org/?probe=021030c4a5) | May 26, 2019 |
| HP            | Pavilion dv6                | Notebook    | [7a702bbcca](https://linux-hardware.org/?probe=7a702bbcca) | May 18, 2019 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f72a33f2be](https://linux-hardware.org/?probe=f72a33f2be) | May 17, 2019 |
| Gigabyte      | H77-DS3H                    | Desktop     | [5cecb224c0](https://linux-hardware.org/?probe=5cecb224c0) | May 13, 2019 |
| Acer          | Aspire E5-575G              | Notebook    | [933bd023a3](https://linux-hardware.org/?probe=933bd023a3) | May 07, 2019 |
| ASUSTek       | X550CA                      | Notebook    | [bee231aa07](https://linux-hardware.org/?probe=bee231aa07) | May 07, 2019 |
| MSI           | MS-7346                     | Desktop     | [f9012833e0](https://linux-hardware.org/?probe=f9012833e0) | May 05, 2019 |
| MSI           | MS-7346                     | Desktop     | [dfb809a0c6](https://linux-hardware.org/?probe=dfb809a0c6) | May 05, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [780fb49d18](https://linux-hardware.org/?probe=780fb49d18) | May 04, 2019 |
| Gigabyte      | H110-D3-CF                  | Desktop     | [e3e358c6c5](https://linux-hardware.org/?probe=e3e358c6c5) | May 02, 2019 |
| Gigabyte      | H110-D3-CF                  | Desktop     | [9ba1176343](https://linux-hardware.org/?probe=9ba1176343) | May 02, 2019 |
| Gigabyte      | H110-D3-CF                  | Desktop     | [0f667174d7](https://linux-hardware.org/?probe=0f667174d7) | May 02, 2019 |
| ASUSTek       | X102BA                      | Notebook    | [a7f7276e3d](https://linux-hardware.org/?probe=a7f7276e3d) | May 02, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [d8da30496e](https://linux-hardware.org/?probe=d8da30496e) | May 01, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [15c7a444a3](https://linux-hardware.org/?probe=15c7a444a3) | Apr 30, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [4030941deb](https://linux-hardware.org/?probe=4030941deb) | Apr 29, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [4da71877c6](https://linux-hardware.org/?probe=4da71877c6) | Apr 28, 2019 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [5ac945fc44](https://linux-hardware.org/?probe=5ac945fc44) | Apr 24, 2019 |
| ASUSTek       | X751LN                      | Notebook    | [9cf06d20fa](https://linux-hardware.org/?probe=9cf06d20fa) | Apr 24, 2019 |
| ASUSTek       | X541SC                      | Notebook    | [0837a78e1f](https://linux-hardware.org/?probe=0837a78e1f) | Apr 24, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [5c7abc670f](https://linux-hardware.org/?probe=5c7abc670f) | Apr 22, 2019 |
| ASUSTek       | X751LN                      | Notebook    | [5ca452f41e](https://linux-hardware.org/?probe=5ca452f41e) | Apr 22, 2019 |
| Biostar       | B75MU3B                     | Desktop     | [263bae9f6d](https://linux-hardware.org/?probe=263bae9f6d) | Apr 21, 2019 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0fc0eb1dfe](https://linux-hardware.org/?probe=0fc0eb1dfe) | Apr 14, 2019 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [a8c17634fa](https://linux-hardware.org/?probe=a8c17634fa) | Apr 13, 2019 |
| HP            | ProBook 470 G4              | Notebook    | [5e83946400](https://linux-hardware.org/?probe=5e83946400) | Apr 12, 2019 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [9a3017958a](https://linux-hardware.org/?probe=9a3017958a) | Apr 03, 2019 |
| Biostar       | H81MLC                      | Desktop     | [21b0c1af4d](https://linux-hardware.org/?probe=21b0c1af4d) | Mar 26, 2019 |
| Gigabyte      | H61M-S1                     | Desktop     | [1471f5c744](https://linux-hardware.org/?probe=1471f5c744) | Mar 26, 2019 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [700fc16ac3](https://linux-hardware.org/?probe=700fc16ac3) | Mar 23, 2019 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [b1e3c957d6](https://linux-hardware.org/?probe=b1e3c957d6) | Mar 20, 2019 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [98718d3ebc](https://linux-hardware.org/?probe=98718d3ebc) | Mar 20, 2019 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [6e008cbf9c](https://linux-hardware.org/?probe=6e008cbf9c) | Mar 20, 2019 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [7302d607c3](https://linux-hardware.org/?probe=7302d607c3) | Mar 19, 2019 |
| ASRock        | B85 Pro4                    | Desktop     | [8c2f28bdd7](https://linux-hardware.org/?probe=8c2f28bdd7) | Mar 14, 2019 |
| ASRock        | B85 Pro4                    | Desktop     | [9cf5db3af5](https://linux-hardware.org/?probe=9cf5db3af5) | Mar 11, 2019 |
| Toshiba       | Satellite P105              | Notebook    | [fed8975477](https://linux-hardware.org/?probe=fed8975477) | Mar 04, 2019 |
| ASRock        | B85 Pro4                    | Desktop     | [6193a4e4db](https://linux-hardware.org/?probe=6193a4e4db) | Mar 02, 2019 |
| Intel         | DG965RY AAD41691-205        | Desktop     | [9e17250cd3](https://linux-hardware.org/?probe=9e17250cd3) | Feb 25, 2019 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [f100f0f205](https://linux-hardware.org/?probe=f100f0f205) | Feb 24, 2019 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [7de51a6093](https://linux-hardware.org/?probe=7de51a6093) | Feb 18, 2019 |
| HP            | 21D0                        | Desktop     | [e12ecb452a](https://linux-hardware.org/?probe=e12ecb452a) | Feb 15, 2019 |
| ECS           | P4M800PRO-M                 | Desktop     | [9b79e448af](https://linux-hardware.org/?probe=9b79e448af) | Feb 10, 2019 |
| eMachines     | ET1850                      | Desktop     | [49d2d34eb5](https://linux-hardware.org/?probe=49d2d34eb5) | Feb 09, 2019 |
| ECS           | P4M800PRO-M                 | Desktop     | [4fa72ec332](https://linux-hardware.org/?probe=4fa72ec332) | Jan 22, 2019 |
| Toshiba       | Satellite C660              | Notebook    | [6badaf723c](https://linux-hardware.org/?probe=6badaf723c) | Jan 20, 2019 |
| Toshiba       | Satellite C660              | Notebook    | [606ef746d1](https://linux-hardware.org/?probe=606ef746d1) | Jan 20, 2019 |
| Toshiba       | Satellite C660              | Notebook    | [5dc1080f85](https://linux-hardware.org/?probe=5dc1080f85) | Jan 20, 2019 |
| Toshiba       | Satellite C660              | Notebook    | [aa10ea857e](https://linux-hardware.org/?probe=aa10ea857e) | Jan 15, 2019 |
| ASUSTek       | K50IE                       | Notebook    | [82bb70f126](https://linux-hardware.org/?probe=82bb70f126) | Jan 02, 2019 |
| HP            | Pavilion g6                 | Notebook    | [dfee480fdd](https://linux-hardware.org/?probe=dfee480fdd) | Jan 01, 2019 |
| HP            | Pavilion g6                 | Notebook    | [d680875c98](https://linux-hardware.org/?probe=d680875c98) | Jan 01, 2019 |
| HP            | Pavilion g6                 | Notebook    | [00e7757462](https://linux-hardware.org/?probe=00e7757462) | Jan 01, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [8e5547337f](https://linux-hardware.org/?probe=8e5547337f) | Dec 28, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [88c4e3862d](https://linux-hardware.org/?probe=88c4e3862d) | Dec 27, 2018 |
| Acer          | Aspire E5-575G              | Notebook    | [7d028bb762](https://linux-hardware.org/?probe=7d028bb762) | Dec 25, 2018 |
| ASRock        | B75M R2.0                   | Desktop     | [6e1297e003](https://linux-hardware.org/?probe=6e1297e003) | Dec 19, 2018 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [b54d9c9c47](https://linux-hardware.org/?probe=b54d9c9c47) | Dec 19, 2018 |
| Biostar       | B75MU3B                     | Desktop     | [aebd92ed4e](https://linux-hardware.org/?probe=aebd92ed4e) | Dec 18, 2018 |
| Biostar       | B75MU3B                     | Desktop     | [76612a774a](https://linux-hardware.org/?probe=76612a774a) | Dec 16, 2018 |
| Biostar       | P4M89-M7A Ver:1.0           | Desktop     | [cfcedc1f4f](https://linux-hardware.org/?probe=cfcedc1f4f) | Dec 15, 2018 |
| Acer          | Aspire E5-575G              | Notebook    | [14806ac400](https://linux-hardware.org/?probe=14806ac400) | Dec 14, 2018 |
| MSI           | H61M-P20                    | Desktop     | [805bef206c](https://linux-hardware.org/?probe=805bef206c) | Dec 06, 2018 |
| ASUSTek       | X540SA                      | Notebook    | [7777e9c6ac](https://linux-hardware.org/?probe=7777e9c6ac) | Nov 28, 2018 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [17cd747f59](https://linux-hardware.org/?probe=17cd747f59) | Nov 27, 2018 |
| Packard Be... | DOT S                       | Notebook    | [a0fe87d229](https://linux-hardware.org/?probe=a0fe87d229) | Nov 24, 2018 |
| Packard Be... | DOT S                       | Notebook    | [6267c7c58d](https://linux-hardware.org/?probe=6267c7c58d) | Nov 24, 2018 |
| ASUSTek       | X540SA                      | Notebook    | [9f31b05c88](https://linux-hardware.org/?probe=9f31b05c88) | Nov 23, 2018 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [d07d21914f](https://linux-hardware.org/?probe=d07d21914f) | Oct 27, 2018 |
| ASUSTek       | U47A                        | Notebook    | [0d064a18d0](https://linux-hardware.org/?probe=0d064a18d0) | Oct 24, 2018 |
| ASUSTek       | U47A                        | Notebook    | [5171edd107](https://linux-hardware.org/?probe=5171edd107) | Oct 24, 2018 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [d6841f0c9f](https://linux-hardware.org/?probe=d6841f0c9f) | Oct 24, 2018 |
| HP            | EliteBook 6930p             | Notebook    | [3a9c8124dd](https://linux-hardware.org/?probe=3a9c8124dd) | Oct 23, 2018 |
| HP            | EliteBook 8530p             | Notebook    | [51ba7cee66](https://linux-hardware.org/?probe=51ba7cee66) | Oct 17, 2018 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [120f3b30db](https://linux-hardware.org/?probe=120f3b30db) | Oct 13, 2018 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [ad2e1e8a9c](https://linux-hardware.org/?probe=ad2e1e8a9c) | Oct 12, 2018 |
| Gigabyte      | H97-HD3                     | Desktop     | [57811990c6](https://linux-hardware.org/?probe=57811990c6) | Oct 09, 2018 |
| Gigabyte      | H97-HD3                     | Desktop     | [7df8538369](https://linux-hardware.org/?probe=7df8538369) | Oct 08, 2018 |
| HP            | Pavilion g6                 | Notebook    | [ffb346f134](https://linux-hardware.org/?probe=ffb346f134) | Sep 24, 2018 |
| HP            | Pavilion dv6                | Notebook    | [884d5eb5ec](https://linux-hardware.org/?probe=884d5eb5ec) | Sep 16, 2018 |
| HP            | Pavilion dv6                | Notebook    | [622662ba7d](https://linux-hardware.org/?probe=622662ba7d) | Sep 14, 2018 |
| ECS           | G31T-M7                     | Desktop     | [9524260856](https://linux-hardware.org/?probe=9524260856) | Sep 11, 2018 |
| Unknown       | Unknown                     | Notebook    | [f45f9ee7ff](https://linux-hardware.org/?probe=f45f9ee7ff) | Sep 05, 2018 |
| ASUSTek       | P5K-E                       | Desktop     | [2bf1f5cd4d](https://linux-hardware.org/?probe=2bf1f5cd4d) | Sep 02, 2018 |
| Unknown       | Unknown                     | Notebook    | [07345cdc85](https://linux-hardware.org/?probe=07345cdc85) | Aug 29, 2018 |
| Lenovo        | B50-70 20384                | Notebook    | [b89c577552](https://linux-hardware.org/?probe=b89c577552) | Aug 26, 2018 |
| HP            | ProBook 450 G5              | Notebook    | [8252f20153](https://linux-hardware.org/?probe=8252f20153) | Aug 18, 2018 |
| Lenovo        | G580 20157                  | Notebook    | [b70545cbac](https://linux-hardware.org/?probe=b70545cbac) | Aug 02, 2018 |
| Toshiba       | Portable PC                 | Notebook    | [3f35fe94d9](https://linux-hardware.org/?probe=3f35fe94d9) | Jul 30, 2018 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [91a4bc2623](https://linux-hardware.org/?probe=91a4bc2623) | Jul 23, 2018 |
| Lenovo        | G510 20238                  | Notebook    | [71278987a9](https://linux-hardware.org/?probe=71278987a9) | Jul 20, 2018 |
| HP            | Compaq CQ58                 | Notebook    | [19369b35ae](https://linux-hardware.org/?probe=19369b35ae) | Jul 20, 2018 |
| Lenovo        | Y50-70 20378                | Notebook    | [62a23cd320](https://linux-hardware.org/?probe=62a23cd320) | Jul 11, 2018 |
| Lenovo        | Board                       | Desktop     | [5dabc0431a](https://linux-hardware.org/?probe=5dabc0431a) | Jul 08, 2018 |
| Lenovo        | Board                       | Desktop     | [b40472e4ff](https://linux-hardware.org/?probe=b40472e4ff) | Jul 08, 2018 |
| AMI           | Cherry Trail CR             | Desktop     | [f8d107c1d6](https://linux-hardware.org/?probe=f8d107c1d6) | Jul 05, 2018 |
| HP            | Compaq CQ58                 | Notebook    | [99fa20eba0](https://linux-hardware.org/?probe=99fa20eba0) | Jun 21, 2018 |
| Lenovo        | G580 20157                  | Notebook    | [a202b59883](https://linux-hardware.org/?probe=a202b59883) | Jun 19, 2018 |
| HP            | Compaq CQ58                 | Notebook    | [cb1791cebb](https://linux-hardware.org/?probe=cb1791cebb) | Jun 16, 2018 |
| Digma         | CITI E400                   | Tablet      | [33fcf91ce0](https://linux-hardware.org/?probe=33fcf91ce0) | Jun 15, 2018 |
| Lenovo        | G580 20157                  | Notebook    | [577c2f349c](https://linux-hardware.org/?probe=577c2f349c) | Jun 08, 2018 |
| Sony          | VPCEB1E1R                   | Notebook    | [a75927fc48](https://linux-hardware.org/?probe=a75927fc48) | Jun 03, 2018 |
| Sony          | VPCEB1E1R                   | Notebook    | [1a978a179e](https://linux-hardware.org/?probe=1a978a179e) | Jun 03, 2018 |
| Sony          | VPCEB1E1R                   | Notebook    | [37813189cc](https://linux-hardware.org/?probe=37813189cc) | Jun 02, 2018 |
| Sony          | VPCEB1E1R                   | Notebook    | [408dcf71ce](https://linux-hardware.org/?probe=408dcf71ce) | May 25, 2018 |
| Lenovo        | B50-70 20384                | Notebook    | [c35dc55ced](https://linux-hardware.org/?probe=c35dc55ced) | May 22, 2018 |
| ASRock        | G31M-GS                     | Desktop     | [e7ad4e06b0](https://linux-hardware.org/?probe=e7ad4e06b0) | May 21, 2018 |
| Gigabyte      | H97-HD3                     | Desktop     | [bc90c9abeb](https://linux-hardware.org/?probe=bc90c9abeb) | May 19, 2018 |
| Samsung       | R518                        | Notebook    | [0e9bb77f12](https://linux-hardware.org/?probe=0e9bb77f12) | May 17, 2018 |
| ASRock        | G31M-GS                     | Desktop     | [33e42cb4a1](https://linux-hardware.org/?probe=33e42cb4a1) | May 17, 2018 |
| ASUSTek       | P5K SE                      | Desktop     | [758aa13be2](https://linux-hardware.org/?probe=758aa13be2) | May 15, 2018 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [258a87c77e](https://linux-hardware.org/?probe=258a87c77e) | Apr 18, 2018 |
| Acer          | TravelMate 7750G            | Notebook    | [0d5442243c](https://linux-hardware.org/?probe=0d5442243c) | Apr 13, 2018 |
| Colorful T... | C.G31T Ver2.3               | Desktop     | [fa66706236](https://linux-hardware.org/?probe=fa66706236) | Apr 05, 2018 |
| MSI           | D2415 S26361-D2415-A21      | Desktop     | [4252f362f3](https://linux-hardware.org/?probe=4252f362f3) | Apr 04, 2018 |
| MSI           | D2415 S26361-D2415-A21      | Desktop     | [5b42126fde](https://linux-hardware.org/?probe=5b42126fde) | Apr 04, 2018 |
| Lenovo        | G580 20157                  | Notebook    | [614e35c795](https://linux-hardware.org/?probe=614e35c795) | Mar 22, 2018 |
| HP            | EliteBook 2560p             | Notebook    | [2674660d30](https://linux-hardware.org/?probe=2674660d30) | Mar 18, 2018 |
| MSI           | D2415 S26361-D2415-A21      | Desktop     | [12aefd0226](https://linux-hardware.org/?probe=12aefd0226) | Mar 08, 2018 |
| ECS           | H61H2-M12                   | Desktop     | [9245ae30a0](https://linux-hardware.org/?probe=9245ae30a0) | Mar 05, 2018 |
| Gigabyte      | Z68XP-UD5                   | Desktop     | [5fed078696](https://linux-hardware.org/?probe=5fed078696) | Mar 02, 2018 |
| Gigabyte      | Z68XP-UD5                   | Desktop     | [724ee9b39d](https://linux-hardware.org/?probe=724ee9b39d) | Mar 02, 2018 |
| Gigabyte      | Z68XP-UD5                   | Desktop     | [a5edee18e6](https://linux-hardware.org/?probe=a5edee18e6) | Mar 02, 2018 |
| Acer          | Predator G3-572             | Notebook    | [c888fc259c](https://linux-hardware.org/?probe=c888fc259c) | Feb 28, 2018 |
| Gigabyte      | 965G-DS3                    | Desktop     | [a18c3642c1](https://linux-hardware.org/?probe=a18c3642c1) | Feb 27, 2018 |
| Acer          | Aspire E1-571G              | Notebook    | [ff7067b051](https://linux-hardware.org/?probe=ff7067b051) | Feb 24, 2018 |
| Intel         | DP45SG AAE27733-407         | Desktop     | [a12c16610a](https://linux-hardware.org/?probe=a12c16610a) | Feb 21, 2018 |
| Intel         | DP45SG AAE27733-407         | Desktop     | [01f1eb1b43](https://linux-hardware.org/?probe=01f1eb1b43) | Feb 21, 2018 |
| Gigabyte      | P35-DS3L                    | Desktop     | [b53697cdde](https://linux-hardware.org/?probe=b53697cdde) | Feb 17, 2018 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [7e932c8df9](https://linux-hardware.org/?probe=7e932c8df9) | Feb 14, 2018 |
| ASUSTek       | X550LA                      | Notebook    | [f416c6d195](https://linux-hardware.org/?probe=f416c6d195) | Feb 11, 2018 |
| Lenovo        | IdeaPad Y580                | Notebook    | [e648c1db32](https://linux-hardware.org/?probe=e648c1db32) | Feb 10, 2018 |
| Gigabyte      | EG45M-DS2H                  | Desktop     | [5765dec2f5](https://linux-hardware.org/?probe=5765dec2f5) | Feb 07, 2018 |
| ASRock        | N68-S                       | Desktop     | [938b758f5d](https://linux-hardware.org/?probe=938b758f5d) | Feb 05, 2018 |
| ECS           | H61H2-M12                   | Desktop     | [ccb76d8296](https://linux-hardware.org/?probe=ccb76d8296) | Feb 04, 2018 |
| ASRock        | N68-S                       | Desktop     | [64632c3151](https://linux-hardware.org/?probe=64632c3151) | Feb 03, 2018 |
| Lenovo        | G580 20157                  | Notebook    | [bb7a063753](https://linux-hardware.org/?probe=bb7a063753) | Jan 24, 2018 |
| Sony          | VGN-NW320F                  | Notebook    | [5b4a5cecc3](https://linux-hardware.org/?probe=5b4a5cecc3) | Jan 24, 2018 |
| Sony          | VGN-NW320F                  | Notebook    | [8d00903b16](https://linux-hardware.org/?probe=8d00903b16) | Jan 24, 2018 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [d9f6c2c974](https://linux-hardware.org/?probe=d9f6c2c974) | Jan 21, 2018 |
| HP            | EliteBook 8440p             | Notebook    | [0358601780](https://linux-hardware.org/?probe=0358601780) | Jan 18, 2018 |
| ASRock        | G31M-GS                     | Desktop     | [8b178b91b5](https://linux-hardware.org/?probe=8b178b91b5) | Jan 16, 2018 |
| ASRock        | B150M Pro4S/D3              | Desktop     | [3d61c8f1b1](https://linux-hardware.org/?probe=3d61c8f1b1) | Jan 16, 2018 |
| Lenovo        | V580c 20160                 | Notebook    | [4bc6c74b55](https://linux-hardware.org/?probe=4bc6c74b55) | Jan 13, 2018 |
| Acer          | Aspire E1-571G              | Notebook    | [b60cd6ffc3](https://linux-hardware.org/?probe=b60cd6ffc3) | Jan 12, 2018 |
| Gigabyte      | P55-US3L                    | Desktop     | [31d2b07ed0](https://linux-hardware.org/?probe=31d2b07ed0) | Jan 09, 2018 |
| Gigabyte      | P55-US3L                    | Desktop     | [557edddbbb](https://linux-hardware.org/?probe=557edddbbb) | Jan 09, 2018 |
| ECS           | G31T-M7                     | Desktop     | [a3440d0458](https://linux-hardware.org/?probe=a3440d0458) | Jan 09, 2018 |
| Fujitsu Si... | D2750-A1 S26361-D2750-A1    | Desktop     | [e3d1272ce6](https://linux-hardware.org/?probe=e3d1272ce6) | Jan 08, 2018 |
| MSI           | H61M-P20                    | Desktop     | [ba382d2256](https://linux-hardware.org/?probe=ba382d2256) | Jan 07, 2018 |
| MSI           | H61M-P20                    | Desktop     | [4b88811da8](https://linux-hardware.org/?probe=4b88811da8) | Jan 07, 2018 |
| Dell          | Inspiron M5110              | Notebook    | [bbf43310e5](https://linux-hardware.org/?probe=bbf43310e5) | Jan 05, 2018 |
| Lenovo        | G510 20238                  | Notebook    | [e84d800dfe](https://linux-hardware.org/?probe=e84d800dfe) | Jan 03, 2018 |
| Lenovo        | G510 20238                  | Notebook    | [b322595c10](https://linux-hardware.org/?probe=b322595c10) | Jan 03, 2018 |
| Lenovo        | Board                       | Desktop     | [f744394a1c](https://linux-hardware.org/?probe=f744394a1c) | Dec 29, 2017 |
| Lenovo        | B590 20208                  | Notebook    | [519ce95e23](https://linux-hardware.org/?probe=519ce95e23) | Dec 27, 2017 |
| ASUSTek       | K52Jc                       | Notebook    | [ae0972b81d](https://linux-hardware.org/?probe=ae0972b81d) | Dec 27, 2017 |
| Lenovo        | V580c 20160                 | Notebook    | [973d383d71](https://linux-hardware.org/?probe=973d383d71) | Dec 27, 2017 |
| ASUSTek       | K52Jc                       | Notebook    | [ee5e52dede](https://linux-hardware.org/?probe=ee5e52dede) | Dec 26, 2017 |
| Lenovo        | V580c 20160                 | Notebook    | [6a259da995](https://linux-hardware.org/?probe=6a259da995) | Dec 25, 2017 |
| Lenovo        | V580c 20160                 | Notebook    | [29a6827395](https://linux-hardware.org/?probe=29a6827395) | Dec 25, 2017 |
| Dell          | Inspiron N5110              | Notebook    | [2045f82e75](https://linux-hardware.org/?probe=2045f82e75) | Dec 24, 2017 |
| ASUSTek       | Crosshair III Formula       | Desktop     | [dc9bba3d36](https://linux-hardware.org/?probe=dc9bba3d36) | Dec 23, 2017 |
| Lenovo        | V580c 20160                 | Notebook    | [02e3d74ee6](https://linux-hardware.org/?probe=02e3d74ee6) | Dec 21, 2017 |
| Lenovo        | V580c 20160                 | Notebook    | [58b7d8fec0](https://linux-hardware.org/?probe=58b7d8fec0) | Dec 21, 2017 |
| Lenovo        | V580c 20160                 | Notebook    | [8b68d694a7](https://linux-hardware.org/?probe=8b68d694a7) | Dec 21, 2017 |
| MSI           | H61M-P20                    | Desktop     | [98d085f592](https://linux-hardware.org/?probe=98d085f592) | Dec 17, 2017 |
| Lenovo        | G580 20157                  | Notebook    | [5fb86851a4](https://linux-hardware.org/?probe=5fb86851a4) | Dec 16, 2017 |
| Biostar       | G31-M7 TE                   | Desktop     | [6b7be109df](https://linux-hardware.org/?probe=6b7be109df) | Dec 10, 2017 |
| Biostar       | G31-M7 TE                   | Desktop     | [ff359217e3](https://linux-hardware.org/?probe=ff359217e3) | Dec 10, 2017 |
| HP            | ProBook 4720s               | Notebook    | [ab0b647716](https://linux-hardware.org/?probe=ab0b647716) | Dec 09, 2017 |
| MSI           | H61M-P20                    | Desktop     | [b9e07ffbc6](https://linux-hardware.org/?probe=b9e07ffbc6) | Dec 07, 2017 |
| ECS           | G31T-M7                     | Desktop     | [ab2cc3b591](https://linux-hardware.org/?probe=ab2cc3b591) | Dec 05, 2017 |
| MSI           | H61M-P20                    | Desktop     | [ad1600936f](https://linux-hardware.org/?probe=ad1600936f) | Dec 03, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [f2eec3b185](https://linux-hardware.org/?probe=f2eec3b185) | Dec 03, 2017 |
| MSI           | H61M-P20                    | Desktop     | [c8f3683dd7](https://linux-hardware.org/?probe=c8f3683dd7) | Dec 03, 2017 |
| ASUSTek       | X51RL                       | Notebook    | [701211da24](https://linux-hardware.org/?probe=701211da24) | Dec 02, 2017 |
| Dell          | Inspiron M5110              | Notebook    | [ee88f09ebb](https://linux-hardware.org/?probe=ee88f09ebb) | Nov 30, 2017 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [2930095950](https://linux-hardware.org/?probe=2930095950) | Nov 26, 2017 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [d2fc5a97ed](https://linux-hardware.org/?probe=d2fc5a97ed) | Nov 12, 2017 |
| Acer          | Aspire 5750G                | Notebook    | [9d18d205df](https://linux-hardware.org/?probe=9d18d205df) | Nov 11, 2017 |
| MSI           | G41M4                       | Desktop     | [5b263ddccb](https://linux-hardware.org/?probe=5b263ddccb) | Oct 26, 2017 |
| HP            | Pavilion 17                 | Notebook    | [bb8b43de60](https://linux-hardware.org/?probe=bb8b43de60) | Oct 25, 2017 |
| ASUSTek       | X58L                        | Notebook    | [de2da19087](https://linux-hardware.org/?probe=de2da19087) | Oct 20, 2017 |
| HP            | Pavilion 17                 | Notebook    | [e10238fe47](https://linux-hardware.org/?probe=e10238fe47) | Oct 17, 2017 |
| HP            | Pavilion 17                 | Notebook    | [2e6cca944f](https://linux-hardware.org/?probe=2e6cca944f) | Oct 17, 2017 |
| HP            | Pavilion 17                 | Notebook    | [c7bbead8d7](https://linux-hardware.org/?probe=c7bbead8d7) | Oct 17, 2017 |
| HP            | Pavilion 17                 | Notebook    | [a5e026dcb5](https://linux-hardware.org/?probe=a5e026dcb5) | Oct 17, 2017 |
| HP            | Pavilion 17                 | Notebook    | [47335a4ecd](https://linux-hardware.org/?probe=47335a4ecd) | Oct 17, 2017 |
| MSI           | MS-7360                     | Desktop     | [74b442872c](https://linux-hardware.org/?probe=74b442872c) | Oct 14, 2017 |
| MSI           | MS-7360                     | Desktop     | [e3fea5c9f7](https://linux-hardware.org/?probe=e3fea5c9f7) | Oct 13, 2017 |
| ASRock        | G31M-S                      | Desktop     | [d686d9a6b4](https://linux-hardware.org/?probe=d686d9a6b4) | Oct 09, 2017 |
| ASRock        | G31M-S                      | Desktop     | [a6c7d89da8](https://linux-hardware.org/?probe=a6c7d89da8) | Oct 09, 2017 |
| ECS           | P33T-A                      | Desktop     | [b333446a6e](https://linux-hardware.org/?probe=b333446a6e) | Oct 07, 2017 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [3bf184ba53](https://linux-hardware.org/?probe=3bf184ba53) | Oct 01, 2017 |
| HP            | Pavilion 17                 | Notebook    | [14c01f8439](https://linux-hardware.org/?probe=14c01f8439) | Sep 30, 2017 |
| HP            | Pavilion 17                 | Notebook    | [eaef47cb60](https://linux-hardware.org/?probe=eaef47cb60) | Sep 29, 2017 |
| HP            | Pavilion 17                 | Notebook    | [17a23a5a8d](https://linux-hardware.org/?probe=17a23a5a8d) | Sep 29, 2017 |
| ASUSTek       | K55VD                       | Notebook    | [295b4e18de](https://linux-hardware.org/?probe=295b4e18de) | Sep 24, 2017 |
| HP            | Pavilion 17                 | Notebook    | [61b4d03adc](https://linux-hardware.org/?probe=61b4d03adc) | Sep 23, 2017 |
| Dell          | Inspiron N5050              | Notebook    | [072cf329f6](https://linux-hardware.org/?probe=072cf329f6) | Sep 22, 2017 |
| HP            | Pavilion 17                 | Notebook    | [7851814436](https://linux-hardware.org/?probe=7851814436) | Sep 20, 2017 |
| HP            | Pavilion 17                 | Notebook    | [4fa55c12ae](https://linux-hardware.org/?probe=4fa55c12ae) | Sep 20, 2017 |
| HP            | Pavilion 17                 | Notebook    | [e97c91d788](https://linux-hardware.org/?probe=e97c91d788) | Sep 12, 2017 |
| HP            | Pavilion 17                 | Notebook    | [35eb8597f2](https://linux-hardware.org/?probe=35eb8597f2) | Sep 12, 2017 |
| HP            | Pavilion 17                 | Notebook    | [5226a4b68c](https://linux-hardware.org/?probe=5226a4b68c) | Sep 12, 2017 |
| Dell          | Inspiron 3558               | Notebook    | [a10105f81f](https://linux-hardware.org/?probe=a10105f81f) | Sep 12, 2017 |
| ECS           | P33T-A                      | Desktop     | [370e48dea3](https://linux-hardware.org/?probe=370e48dea3) | Sep 02, 2017 |
| MSI           | P45-C51                     | Desktop     | [3c7abe4dbb](https://linux-hardware.org/?probe=3c7abe4dbb) | Sep 01, 2017 |
| Unknown       | Unknown                     | Desktop     | [5593f71ea9](https://linux-hardware.org/?probe=5593f71ea9) | Aug 31, 2017 |
| MSI           | G41M4                       | Desktop     | [6c2f54fe32](https://linux-hardware.org/?probe=6c2f54fe32) | Aug 28, 2017 |
| MSI           | P45-C51                     | Desktop     | [3605717bc8](https://linux-hardware.org/?probe=3605717bc8) | Aug 24, 2017 |
| Gigabyte      | G41MT-S2                    | Desktop     | [60027a3248](https://linux-hardware.org/?probe=60027a3248) | Aug 24, 2017 |
| Unknown       | Unknown                     | Desktop     | [729dbae58e](https://linux-hardware.org/?probe=729dbae58e) | Aug 18, 2017 |
| MSI           | P45-C51                     | Desktop     | [f19a281f67](https://linux-hardware.org/?probe=f19a281f67) | Aug 17, 2017 |
| Gigabyte      | P55-UD3L                    | Desktop     | [b3c7478840](https://linux-hardware.org/?probe=b3c7478840) | Aug 17, 2017 |
| Gigabyte      | G41M-Combo                  | Desktop     | [46eadd3692](https://linux-hardware.org/?probe=46eadd3692) | Aug 14, 2017 |
| ASUSTek       | K52JV                       | Notebook    | [786ab76c2d](https://linux-hardware.org/?probe=786ab76c2d) | Aug 09, 2017 |
| Sony          | VPCCB2S1R                   | Notebook    | [b5723ad5f5](https://linux-hardware.org/?probe=b5723ad5f5) | Aug 08, 2017 |
| Lenovo        | G580 20157                  | Notebook    | [a1a09287ab](https://linux-hardware.org/?probe=a1a09287ab) | Aug 06, 2017 |
| MSI           | G41M4                       | Desktop     | [0caa615ad2](https://linux-hardware.org/?probe=0caa615ad2) | Aug 05, 2017 |
| Lenovo        | IdeaPad Y580                | Notebook    | [258ed6aea6](https://linux-hardware.org/?probe=258ed6aea6) | Jul 27, 2017 |
| Lenovo        | IdeaPad Y580                | Notebook    | [a40d8297a6](https://linux-hardware.org/?probe=a40d8297a6) | Jul 27, 2017 |
| Lenovo        | IdeaPad Y580                | Notebook    | [493ba2eb0c](https://linux-hardware.org/?probe=493ba2eb0c) | Jul 27, 2017 |
| MSI           | P45-C51                     | Desktop     | [55eb7a334a](https://linux-hardware.org/?probe=55eb7a334a) | Jul 26, 2017 |
| Lenovo        | G510 20238                  | Notebook    | [2613154d7e](https://linux-hardware.org/?probe=2613154d7e) | Jul 24, 2017 |
| eMachines     | E725                        | Notebook    | [05bce34fc0](https://linux-hardware.org/?probe=05bce34fc0) | Jul 23, 2017 |
| Acer          | Aspire V3-551G              | Notebook    | [92da3895dc](https://linux-hardware.org/?probe=92da3895dc) | Jul 18, 2017 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [bdc06eff0a](https://linux-hardware.org/?probe=bdc06eff0a) | Jul 18, 2017 |
| Dell          | Inspiron 5559               | Notebook    | [3753d1a422](https://linux-hardware.org/?probe=3753d1a422) | Jul 18, 2017 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [a62f8e0f39](https://linux-hardware.org/?probe=a62f8e0f39) | Jul 15, 2017 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [0a1ff9ae9c](https://linux-hardware.org/?probe=0a1ff9ae9c) | Jul 14, 2017 |
| Dell          | Inspiron 5759               | Notebook    | [40852e37a5](https://linux-hardware.org/?probe=40852e37a5) | Jul 12, 2017 |
| MSI           | G41M4                       | Desktop     | [42ac99dafe](https://linux-hardware.org/?probe=42ac99dafe) | Jul 12, 2017 |
| MSI           | G41M4                       | Desktop     | [95c6901677](https://linux-hardware.org/?probe=95c6901677) | Jul 12, 2017 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [bf8c80ba08](https://linux-hardware.org/?probe=bf8c80ba08) | Jul 09, 2017 |
| ASUSTek       | H81M-R                      | Desktop     | [1ab9b8b9b0](https://linux-hardware.org/?probe=1ab9b8b9b0) | Jul 01, 2017 |
| ECS           | H61H2-MV                    | Desktop     | [5e3381ae2b](https://linux-hardware.org/?probe=5e3381ae2b) | Jul 01, 2017 |
| Foxconn       | G43M01                      | Desktop     | [5baa8deeea](https://linux-hardware.org/?probe=5baa8deeea) | Jun 17, 2017 |
| Gigabyte      | P31-S3G                     | Desktop     | [7db5b169da](https://linux-hardware.org/?probe=7db5b169da) | Jun 12, 2017 |
| HP            | Pavilion dm3                | Notebook    | [008097ceb1](https://linux-hardware.org/?probe=008097ceb1) | May 30, 2017 |
| ECS           | P33T-A                      | Desktop     | [a226d451b0](https://linux-hardware.org/?probe=a226d451b0) | May 29, 2017 |
| Dell          | Inspiron 3558               | Notebook    | [c7a96bfff1](https://linux-hardware.org/?probe=c7a96bfff1) | May 28, 2017 |
| Dell          | Inspiron 3558               | Notebook    | [11b4a60b6b](https://linux-hardware.org/?probe=11b4a60b6b) | May 28, 2017 |
| Lenovo        | G500 20236                  | Notebook    | [60a1eab059](https://linux-hardware.org/?probe=60a1eab059) | May 26, 2017 |
| ECS           | P33T-A                      | Desktop     | [17dbb18609](https://linux-hardware.org/?probe=17dbb18609) | May 26, 2017 |
| Gigabyte      | P35-DS3L                    | Desktop     | [ed899cd88b](https://linux-hardware.org/?probe=ed899cd88b) | May 25, 2017 |
| HP            | Compaq 6710b (KE120EA#AC... | Notebook    | [278110b61f](https://linux-hardware.org/?probe=278110b61f) | May 22, 2017 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [06e5d46798](https://linux-hardware.org/?probe=06e5d46798) | May 21, 2017 |
| Gigabyte      | EP35-DS3L                   | Desktop     | [fdbccdc938](https://linux-hardware.org/?probe=fdbccdc938) | May 13, 2017 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [ff2477ab47](https://linux-hardware.org/?probe=ff2477ab47) | May 11, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | Notebook    | [e8829d83b4](https://linux-hardware.org/?probe=e8829d83b4) | May 05, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | Notebook    | [b1a33a15ce](https://linux-hardware.org/?probe=b1a33a15ce) | May 04, 2017 |
| Biostar       | NF61S-M2A                   | Desktop     | [7754dbc20e](https://linux-hardware.org/?probe=7754dbc20e) | May 03, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | Notebook    | [dd2f72474b](https://linux-hardware.org/?probe=dd2f72474b) | May 02, 2017 |
| Biostar       | NF61S-M2A                   | Desktop     | [2160a35f31](https://linux-hardware.org/?probe=2160a35f31) | May 01, 2017 |
| Acer          | Aspire E5-511G              | Notebook    | [0110e34364](https://linux-hardware.org/?probe=0110e34364) | May 01, 2017 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [43e1a4811a](https://linux-hardware.org/?probe=43e1a4811a) | May 01, 2017 |
| HP            | ENVY TS 17                  | Notebook    | [74e650e784](https://linux-hardware.org/?probe=74e650e784) | Apr 30, 2017 |
| Unknown       | Unknown                     | Notebook    | [f5351462b1](https://linux-hardware.org/?probe=f5351462b1) | Apr 28, 2017 |
| ASUSTek       | M4N98TD EVO                 | Desktop     | [97b83f48df](https://linux-hardware.org/?probe=97b83f48df) | Apr 26, 2017 |
| ASRock        | G31M-VS                     | Desktop     | [a3dd026e80](https://linux-hardware.org/?probe=a3dd026e80) | Apr 18, 2017 |
| Dell          | Inspiron 5521               | Notebook    | [92a991bcec](https://linux-hardware.org/?probe=92a991bcec) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | Notebook    | [559b234e2e](https://linux-hardware.org/?probe=559b234e2e) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | Notebook    | [9a06660d14](https://linux-hardware.org/?probe=9a06660d14) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | Notebook    | [534d340a7a](https://linux-hardware.org/?probe=534d340a7a) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | Notebook    | [add5384359](https://linux-hardware.org/?probe=add5384359) | Apr 16, 2017 |
| Dell          | Inspiron M5110              | Notebook    | [331bda6305](https://linux-hardware.org/?probe=331bda6305) | Apr 01, 2017 |
| Dell          | Inspiron M5110              | Notebook    | [6d2fc341c7](https://linux-hardware.org/?probe=6d2fc341c7) | Apr 01, 2017 |
| ASUSTek       | M2N4-SLI                    | Desktop     | [1699021b8f](https://linux-hardware.org/?probe=1699021b8f) | Mar 31, 2017 |
| ASUSTek       | M2N4-SLI                    | Desktop     | [a712e10b97](https://linux-hardware.org/?probe=a712e10b97) | Mar 28, 2017 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [fb7fc9c78e](https://linux-hardware.org/?probe=fb7fc9c78e) | Mar 13, 2017 |
| Biostar       | Hi-Fi Z87W                  | Desktop     | [8e13c3fba7](https://linux-hardware.org/?probe=8e13c3fba7) | Mar 11, 2017 |
| MSI           | MS-7346                     | Desktop     | [1f97ef92e1](https://linux-hardware.org/?probe=1f97ef92e1) | Mar 11, 2017 |
| ASUSTek       | H81M-K                      | Desktop     | [0f9345171a](https://linux-hardware.org/?probe=0f9345171a) | Mar 10, 2017 |
| MSI           | MS-7346                     | Desktop     | [b83af770d0](https://linux-hardware.org/?probe=b83af770d0) | Mar 09, 2017 |
| Samsung       | R18                         | Notebook    | [8339a48a6a](https://linux-hardware.org/?probe=8339a48a6a) | Feb 19, 2017 |
| ASUSTek       | N56DP                       | Notebook    | [c4a63674e5](https://linux-hardware.org/?probe=c4a63674e5) | Feb 18, 2017 |
| ASRock        | H61M-HVS                    | Desktop     | [bab5245e0a](https://linux-hardware.org/?probe=bab5245e0a) | Feb 17, 2017 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [a03d8130fe](https://linux-hardware.org/?probe=a03d8130fe) | Feb 06, 2017 |
| ASUSTek       | H61M-K                      | Desktop     | [6c7cca8bcd](https://linux-hardware.org/?probe=6c7cca8bcd) | Feb 05, 2017 |
| ASUSTek       | H61M-K                      | Desktop     | [0fa9b52710](https://linux-hardware.org/?probe=0fa9b52710) | Jan 29, 2017 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [c288b514d5](https://linux-hardware.org/?probe=c288b514d5) | Jan 22, 2017 |
| ASUSTek       | N53SM                       | Notebook    | [26849207d6](https://linux-hardware.org/?probe=26849207d6) | Jan 19, 2017 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [0756a69391](https://linux-hardware.org/?probe=0756a69391) | Jan 07, 2017 |
| Dell          | Inspiron 7720               | Notebook    | [7dff83e247](https://linux-hardware.org/?probe=7dff83e247) | Jan 04, 2017 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [58cb3c3ef1](https://linux-hardware.org/?probe=58cb3c3ef1) | Dec 23, 2016 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [8af0bb111e](https://linux-hardware.org/?probe=8af0bb111e) | Dec 20, 2016 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | Desktop     | [2313e5ca24](https://linux-hardware.org/?probe=2313e5ca24) | Dec 19, 2016 |
| Lenovo        | G565 20071                  | Notebook    | [e6972d050f](https://linux-hardware.org/?probe=e6972d050f) | Dec 16, 2016 |
| Toshiba       | TECRA M5                    | Notebook    | [b4743ce437](https://linux-hardware.org/?probe=b4743ce437) | Dec 12, 2016 |
| ASUSTek       | P5P43TD                     | Desktop     | [6455128f71](https://linux-hardware.org/?probe=6455128f71) | Dec 05, 2016 |
| Packard Be... | DOT S                       | Notebook    | [815f65352b](https://linux-hardware.org/?probe=815f65352b) | Dec 01, 2016 |
| Toshiba       | Satellite C650              | Notebook    | [06c50a161c](https://linux-hardware.org/?probe=06c50a161c) | Nov 29, 2016 |
| ASUSTek       | 1225C                       | Notebook    | [57787e36c2](https://linux-hardware.org/?probe=57787e36c2) | Nov 28, 2016 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [1ed00b7813](https://linux-hardware.org/?probe=1ed00b7813) | Nov 27, 2016 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [45b5c7374e](https://linux-hardware.org/?probe=45b5c7374e) | Nov 27, 2016 |
| Lenovo        | ThinkPad X201 3626MJ5       | Notebook    | [e13b0d2ee7](https://linux-hardware.org/?probe=e13b0d2ee7) | Nov 25, 2016 |
| HP            | 530                         | Notebook    | [b4ade385fd](https://linux-hardware.org/?probe=b4ade385fd) | Nov 24, 2016 |
| Toshiba       | Satellite 5200              | Notebook    | [a79789524b](https://linux-hardware.org/?probe=a79789524b) | Nov 02, 2016 |
| ASUSTek       | H81-PLUS                    | Desktop     | [35990fe890](https://linux-hardware.org/?probe=35990fe890) | Nov 01, 2016 |
| Gigabyte      | G31M-S2L                    | Desktop     | [9b1ec63eb3](https://linux-hardware.org/?probe=9b1ec63eb3) | Oct 28, 2016 |
| ASRock        | H170M Pro4                  | Desktop     | [c5125f0040](https://linux-hardware.org/?probe=c5125f0040) | Sep 30, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ROSA R10           | 56        | 13.69%  |
| ROSA R8.1          | 55        | 13.45%  |
| ROSA R11           | 50        | 12.22%  |
| ROSA R9            | 32        | 7.82%   |
| ROSA R8            | 23        | 5.62%   |
| ROSA R11.1         | 21        | 5.13%   |
| Ubuntu 20.04       | 18        | 4.4%    |
| Ubuntu 18.04       | 10        | 2.44%   |
| KDE neon 20.04     | 10        | 2.44%   |
| OpenMandriva 4.2   | 9         | 2.2%    |
| ROSA 12.2          | 7         | 1.71%   |
| Debian 11          | 7         | 1.71%   |
| Slackware 15.0     | 6         | 1.47%   |
| Arch               | 4         | 0.98%   |
| Ubuntu 18.10       | 3         | 0.73%   |
| ROSA 12.1          | 3         | 0.73%   |
| Linux Mint 20.1    | 3         | 0.73%   |
| Fedora 35          | 3         | 0.73%   |
| Debian 10          | 3         | 0.73%   |
| Arch Rolling       | 3         | 0.73%   |
| ROSA R4-R8         | 2         | 0.49%   |
| ROSA 12            | 2         | 0.49%   |
| OpenMandriva 4.3   | 2         | 0.49%   |
| Manjaro 18.0.0-rc  | 2         | 0.49%   |
| Manjaro            | 2         | 0.49%   |
| Linux Mint 19.3    | 2         | 0.49%   |
| Linux Mint 18.3    | 2         | 0.49%   |
| Kubuntu 19.10      | 2         | 0.49%   |
| KDE neon 18.04     | 2         | 0.49%   |
| Gentoo 2.6         | 2         | 0.49%   |
| Fedora 34          | 2         | 0.49%   |
| CentOS 5           | 2         | 0.49%   |
| Zorin 15           | 1         | 0.24%   |
| Xubuntu 20.04      | 1         | 0.24%   |
| Ubuntu 22.04       | 1         | 0.24%   |
| Ubuntu 21.10       | 1         | 0.24%   |
| Ubuntu 21.04       | 1         | 0.24%   |
| Ubuntu 20.10       | 1         | 0.24%   |
| Ubuntu 19.04       | 1         | 0.24%   |
| Ubuntu 18.08.34    | 1         | 0.24%   |
| Ubuntu 16.04       | 1         | 0.24%   |
| Solus 4.3          | 1         | 0.24%   |
| Rocky Linux 8.4    | 1         | 0.24%   |
| Pop!_OS 20.10      | 1         | 0.24%   |
| Pop!_OS 20.04      | 1         | 0.24%   |
| Peppermint 10      | 1         | 0.24%   |
| Oracle Linux 7.6   | 1         | 0.24%   |
| openSUSE Leap-15.1 | 1         | 0.24%   |
| openSUSE 20210622  | 1         | 0.24%   |
| Manjaro 21.0.7     | 1         | 0.24%   |
| Manjaro 21.0.4     | 1         | 0.24%   |
| Manjaro 20.2       | 1         | 0.24%   |
| Manjaro 20.1.1     | 1         | 0.24%   |
| Manjaro 20.1       | 1         | 0.24%   |
| Manjaro 20.0.3     | 1         | 0.24%   |
| Manjaro 18.1.3     | 1         | 0.24%   |
| Lubuntu 18.04      | 1         | 0.24%   |
| Linux Mint 18.2    | 1         | 0.24%   |
| Kubuntu 20.10      | 1         | 0.24%   |
| Kubuntu 20.04      | 1         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| ROSA         | 226       | 59.79%  |
| Ubuntu       | 37        | 9.79%   |
| Endless      | 17        | 4.5%    |
| KDE neon     | 12        | 3.17%   |
| OpenMandriva | 11        | 2.91%   |
| Debian       | 11        | 2.91%   |
| Manjaro      | 10        | 2.65%   |
| Linux Mint   | 8         | 2.12%   |
| Slackware    | 6         | 1.59%   |
| Fedora       | 6         | 1.59%   |
| Arch         | 5         | 1.32%   |
| Kubuntu      | 4         | 1.06%   |
| CentOS       | 4         | 1.06%   |
| Pop!_OS      | 2         | 0.53%   |
| openSUSE     | 2         | 0.53%   |
| Gentoo       | 2         | 0.53%   |
| Elementary   | 2         | 0.53%   |
| Zorin        | 1         | 0.26%   |
| Xubuntu      | 1         | 0.26%   |
| Solus        | 1         | 0.26%   |
| Rocky Linux  | 1         | 0.26%   |
| Peppermint   | 1         | 0.26%   |
| Oracle Linux | 1         | 0.26%   |
| Lubuntu      | 1         | 0.26%   |
| Finnix       | 1         | 0.26%   |
| Ctlos        | 1         | 0.26%   |
| Clear Linux  | 1         | 0.26%   |
| BlackPanther | 1         | 0.26%   |
| antiX        | 1         | 0.26%   |
| ALT Linux    | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 29        | 6.71%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 28        | 6.48%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 26        | 6.02%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 15        | 3.47%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 10        | 2.31%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 10        | 2.31%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 10        | 2.31%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 9         | 2.08%   |
| 5.10.14-desktop-1omv4002            | 9         | 2.08%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 9         | 2.08%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 8         | 1.85%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 8         | 1.85%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 8         | 1.85%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 7         | 1.62%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 7         | 1.62%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 7         | 1.62%   |
| 5.4.32-generic-2rosa-x86_64         | 6         | 1.39%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 6         | 1.39%   |
| 4.15.0-desktop-45.1rosa-i586        | 6         | 1.39%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 5         | 1.16%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 5         | 1.16%   |
| 5.15.19                             | 4         | 0.93%   |
| 5.10.0-8-amd64                      | 4         | 0.93%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 4         | 0.93%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 4         | 0.93%   |
| 5.8.6-1-MANJARO                     | 3         | 0.69%   |
| 5.4.0-52-generic                    | 3         | 0.69%   |
| 5.0.0-37-generic                    | 3         | 0.69%   |
| 4.9.34-nrj-desktop-1rosa-x86_64     | 3         | 0.69%   |
| 5.8.0-44-generic                    | 2         | 0.46%   |
| 5.8.0-14-generic                    | 2         | 0.46%   |
| 5.4.83-generic-2rosa-x86_64         | 2         | 0.46%   |
| 5.4.32-generic-2rosa-i586           | 2         | 0.46%   |
| 5.4.0-73-generic                    | 2         | 0.46%   |
| 5.4.0-48-generic                    | 2         | 0.46%   |
| 5.4.0-47-generic                    | 2         | 0.46%   |
| 5.4.0-42-generic                    | 2         | 0.46%   |
| 5.4.0-39-generic                    | 2         | 0.46%   |
| 5.16.7-desktop-1omv4003             | 2         | 0.46%   |
| 5.14.17-301.fc35.x86_64             | 2         | 0.46%   |
| 5.13.0-39-generic                   | 2         | 0.46%   |
| 5.11.0-35-generic                   | 2         | 0.46%   |
| 5.11.0-34-generic                   | 2         | 0.46%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 2         | 0.46%   |
| 5.10.0-9-amd64                      | 2         | 0.46%   |
| 4.9.34-nrj-desktop-2rosa-i586       | 2         | 0.46%   |
| 4.9.155-nrj-desktop-1rosa-i586      | 2         | 0.46%   |
| 4.18.16-1-MANJARO                   | 2         | 0.46%   |
| 4.16.0-4-generic                    | 2         | 0.46%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 2         | 0.46%   |
| 4.13.0-32-generic                   | 2         | 0.46%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 2         | 0.46%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 2         | 0.46%   |
| 5.9.8-050908-generic                | 1         | 0.23%   |
| 5.9.6-050906-generic                | 1         | 0.23%   |
| 5.9.1-zen1-1-zen                    | 1         | 0.23%   |
| 5.8.18-1-MANJARO                    | 1         | 0.23%   |
| 5.8.13-21-tkg-upds                  | 1         | 0.23%   |
| 5.8.11-1-MANJARO                    | 1         | 0.23%   |
| 5.8.10-987.native                   | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 61        | 14.32%  |
| 4.9.60  | 37        | 8.69%   |
| 4.9.20  | 36        | 8.45%   |
| 5.4.0   | 24        | 5.63%   |
| 4.1.38  | 19        | 4.46%   |
| 4.9.9   | 17        | 3.99%   |
| 4.1.34  | 17        | 3.99%   |
| 5.11.0  | 11        | 2.58%   |
| 4.9.155 | 11        | 2.58%   |
| 5.10.74 | 9         | 2.11%   |
| 5.10.14 | 9         | 2.11%   |
| 5.0.0   | 9         | 2.11%   |
| 4.9.124 | 9         | 2.11%   |
| 5.4.32  | 8         | 1.88%   |
| 5.3.0   | 8         | 1.88%   |
| 4.9.41  | 8         | 1.88%   |
| 4.9.76  | 7         | 1.64%   |
| 5.8.0   | 6         | 1.41%   |
| 5.10.0  | 6         | 1.41%   |
| 4.9.111 | 6         | 1.41%   |
| 4.18.0  | 6         | 1.41%   |
| 4.9.34  | 5         | 1.17%   |
| 5.15.19 | 4         | 0.94%   |
| 5.13.0  | 4         | 0.94%   |
| 4.9.95  | 4         | 0.94%   |
| 4.19.0  | 4         | 0.94%   |
| 4.13.0  | 4         | 0.94%   |
| 5.8.6   | 3         | 0.7%    |
| 5.16.7  | 3         | 0.7%    |
| 4.18.16 | 3         | 0.7%    |
| 4.1.25  | 3         | 0.7%    |
| 5.4.83  | 2         | 0.47%   |
| 5.14.17 | 2         | 0.47%   |
| 5.10.71 | 2         | 0.47%   |
| 4.16.0  | 2         | 0.47%   |
| 3.14.15 | 2         | 0.47%   |
| 3.10.0  | 2         | 0.47%   |
| 2.6.18  | 2         | 0.47%   |
| 5.9.8   | 1         | 0.23%   |
| 5.9.6   | 1         | 0.23%   |
| 5.9.1   | 1         | 0.23%   |
| 5.8.18  | 1         | 0.23%   |
| 5.8.13  | 1         | 0.23%   |
| 5.8.11  | 1         | 0.23%   |
| 5.8.10  | 1         | 0.23%   |
| 5.7.7   | 1         | 0.23%   |
| 5.7.0   | 1         | 0.23%   |
| 5.6.4   | 1         | 0.23%   |
| 5.6.15  | 1         | 0.23%   |
| 5.4.87  | 1         | 0.23%   |
| 5.4.85  | 1         | 0.23%   |
| 5.4.5   | 1         | 0.23%   |
| 5.4.157 | 1         | 0.23%   |
| 5.4.150 | 1         | 0.23%   |
| 5.3.13  | 1         | 0.23%   |
| 5.17.2  | 1         | 0.23%   |
| 5.17.0  | 1         | 0.23%   |
| 5.15.8  | 1         | 0.23%   |
| 5.15.6  | 1         | 0.23%   |
| 5.15.27 | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 121       | 29.95%  |
| 4.15    | 61        | 15.1%   |
| 5.4     | 39        | 9.65%   |
| 4.1     | 38        | 9.41%   |
| 5.10    | 30        | 7.43%   |
| 5.8     | 13        | 3.22%   |
| 5.11    | 11        | 2.72%   |
| 4.18    | 11        | 2.72%   |
| 5.0     | 10        | 2.48%   |
| 5.3     | 9         | 2.23%   |
| 5.15    | 9         | 2.23%   |
| 5.13    | 6         | 1.49%   |
| 4.19    | 6         | 1.49%   |
| 5.14    | 4         | 0.99%   |
| 4.13    | 4         | 0.99%   |
| 5.9     | 3         | 0.74%   |
| 5.16    | 3         | 0.74%   |
| 2.6     | 3         | 0.74%   |
| 5.7     | 2         | 0.5%    |
| 5.6     | 2         | 0.5%    |
| 5.17    | 2         | 0.5%    |
| 5.12    | 2         | 0.5%    |
| 4.4     | 2         | 0.5%    |
| 4.16    | 2         | 0.5%    |
| 4.12    | 2         | 0.5%    |
| 3.14    | 2         | 0.5%    |
| 3.10    | 2         | 0.5%    |
| 5.1     | 1         | 0.25%   |
| 4.20    | 1         | 0.25%   |
| 4.17    | 1         | 0.25%   |
| 4.14    | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 320       | 84.43%  |
| i686    | 57        | 15.04%  |
| aarch64 | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE4            | 173       | 44.25%  |
| KDE5            | 78        | 19.95%  |
| GNOME           | 54        | 13.81%  |
| Unknown         | 29        | 7.42%   |
| KDE             | 18        | 4.6%    |
| XFCE            | 13        | 3.32%   |
| Cinnamon        | 6         | 1.53%   |
| MATE            | 4         | 1.02%   |
| LXQt            | 4         | 1.02%   |
| X-Cinnamon      | 3         | 0.77%   |
| LXDE            | 3         | 0.77%   |
| Unity           | 2         | 0.51%   |
| sway            | 1         | 0.26%   |
| Pantheon        | 1         | 0.26%   |
| i3              | 1         | 0.26%   |
| GNOME Flashback | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 342       | 90%     |
| Wayland | 20        | 5.26%   |
| Unknown | 14        | 3.68%   |
| Tty     | 4         | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 175       | 44.87%  |
| SDDM    | 87        | 22.31%  |
| Unknown | 81        | 20.77%  |
| GDM     | 24        | 6.15%   |
| TDM     | 10        | 2.56%   |
| LightDM | 10        | 2.56%   |
| GDM3    | 2         | 0.51%   |
| SLiM    | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 230       | 59.59%  |
| ru_RU       | 97        | 25.13%  |
| en_US       | 51        | 13.21%  |
| ru_RU.UTF_8 | 4         | 1.04%   |
| en_GB       | 2         | 0.52%   |
| C           | 2         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 253       | 66.06%  |
| EFI  | 130       | 33.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 209       | 53.45%  |
| Unknown | 146       | 37.34%  |
| Overlay | 18        | 4.6%    |
| Btrfs   | 13        | 3.32%   |
| Xfs     | 2         | 0.51%   |
| Ext3    | 2         | 0.51%   |
| Zfs     | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 155       | 40.05%  |
| Unknown | 144       | 37.21%  |
| GPT     | 88        | 22.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 337       | 87.99%  |
| Yes       | 46        | 12.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 280       | 72.54%  |
| Yes       | 106       | 27.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 71        | 19.09%  |
| Hewlett-Packard     | 55        | 14.78%  |
| Lenovo              | 41        | 11.02%  |
| Gigabyte Technology | 35        | 9.41%   |
| Acer                | 31        | 8.33%   |
| Dell                | 21        | 5.65%   |
| ASRock              | 21        | 5.65%   |
| MSI                 | 14        | 3.76%   |
| Biostar             | 11        | 2.96%   |
| ECS                 | 8         | 2.15%   |
| Unknown             | 8         | 2.15%   |
| Intel               | 7         | 1.88%   |
| Toshiba             | 6         | 1.61%   |
| Fujitsu             | 6         | 1.61%   |
| Foxconn             | 6         | 1.61%   |
| Sony                | 5         | 1.34%   |
| Fujitsu Siemens     | 5         | 1.34%   |
| Samsung Electronics | 4         | 1.08%   |
| Packard Bell        | 3         | 0.81%   |
| HPE                 | 2         | 0.54%   |
| eMachines           | 2         | 0.54%   |
| Acidanthera         | 2         | 0.54%   |
| Quanta              | 1         | 0.27%   |
| OEM                 | 1         | 0.27%   |
| EPoX Computer       | 1         | 0.27%   |
| Elenberg            | 1         | 0.27%   |
| Digma               | 1         | 0.27%   |
| Colorful Technology | 1         | 0.27%   |
| Athermiter/PlexHD   | 1         | 0.27%   |
| AMI                 | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 9         | 2.42%   |
| HP Pavilion g6                                                                           | 5         | 1.34%   |
| ASUS All Series                                                                          | 5         | 1.34%   |
| Lenovo G510 20238                                                                        | 3         | 0.81%   |
| Lenovo G500 20236                                                                        | 3         | 0.81%   |
| Gigabyte P35-DS3L                                                                        | 3         | 0.81%   |
| Fujitsu LIFEBOOK AH531                                                                   | 3         | 0.81%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR                                                     | 3         | 0.81%   |
| Acer Aspire E5-575G                                                                      | 3         | 0.81%   |
| Packard Bell DOT S                                                                       | 2         | 0.54%   |
| MSI MS-7788                                                                              | 2         | 0.54%   |
| Lenovo ThinkPad Edge E530 3259CEG                                                        | 2         | 0.54%   |
| Lenovo ThinkBook 14 G2 ITL 20VD                                                          | 2         | 0.54%   |
| Lenovo Legion Y540-15IRH-PG0 81SY                                                        | 2         | 0.54%   |
| HP ProLiant DL360 G5                                                                     | 2         | 0.54%   |
| HP Presario CQ57                                                                         | 2         | 0.54%   |
| HP Pavilion dv6                                                                          | 2         | 0.54%   |
| HP Compaq CQ58                                                                           | 2         | 0.54%   |
| Gigabyte EP45-DS3L                                                                       | 2         | 0.54%   |
| Foxconn G31MXP FAB:1.1                                                                   | 2         | 0.54%   |
| ECS H61H2-M12                                                                            | 2         | 0.54%   |
| ECS G31T-M7                                                                              | 2         | 0.54%   |
| Dell Inspiron N5110                                                                      | 2         | 0.54%   |
| Biostar B75MU3B                                                                          | 2         | 0.54%   |
| ASUS X51RL                                                                               | 2         | 0.54%   |
| ASUS H61M-K                                                                              | 2         | 0.54%   |
| ASRock Q1900M                                                                            | 2         | 0.54%   |
| ASRock G31M-VS                                                                           | 2         | 0.54%   |
| ASRock G31M-GS                                                                           | 2         | 0.54%   |
| Acidanthera iMac13,2                                                                     | 2         | 0.54%   |
| Acer Aspire V3-551G                                                                      | 2         | 0.54%   |
| Acer Aspire A715-75G                                                                     | 2         | 0.54%   |
| Acer Aspire 5750G                                                                        | 2         | 0.54%   |
| Toshiba TECRA M5                                                                         | 1         | 0.27%   |
| Toshiba Satellite P105                                                                   | 1         | 0.27%   |
| Toshiba Satellite C660                                                                   | 1         | 0.27%   |
| Toshiba Satellite C650                                                                   | 1         | 0.27%   |
| Toshiba Satellite 5200                                                                   | 1         | 0.27%   |
| Toshiba Portable PC                                                                      | 1         | 0.27%   |
| Sony VPCEH2M1R                                                                           | 1         | 0.27%   |
| Sony VPCEB1E1R                                                                           | 1         | 0.27%   |
| Sony VPCCB2S1R                                                                           | 1         | 0.27%   |
| Sony VGN-NW320F                                                                          | 1         | 0.27%   |
| Sony VGN-NR430E                                                                          | 1         | 0.27%   |
| Samsung R518                                                                             | 1         | 0.27%   |
| Samsung R18                                                                              | 1         | 0.27%   |
| Samsung N100SP                                                                           | 1         | 0.27%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.27%   |
| Quanta Pro 3420 AiO PC                                                                   | 1         | 0.27%   |
| Packard Bell EasyNote TE11HC                                                             | 1         | 0.27%   |
| MSI Prestige 14 A10SC                                                                    | 1         | 0.27%   |
| MSI MS-7B79                                                                              | 1         | 0.27%   |
| MSI MS-7758                                                                              | 1         | 0.27%   |
| MSI MS-7592                                                                              | 1         | 0.27%   |
| MSI MS-7583                                                                              | 1         | 0.27%   |
| MSI MS-7529                                                                              | 1         | 0.27%   |
| MSI MS-7522                                                                              | 1         | 0.27%   |
| MSI MS-7519                                                                              | 1         | 0.27%   |
| MSI MS-7365                                                                              | 1         | 0.27%   |
| MSI MS-7360                                                                              | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 20        | 5.38%   |
| Dell Inspiron           | 14        | 3.76%   |
| ASUS VivoBook           | 14        | 3.76%   |
| HP Pavilion             | 13        | 3.49%   |
| Unknown                 | 9         | 2.42%   |
| Lenovo ThinkPad         | 8         | 2.15%   |
| Lenovo IdeaPad          | 8         | 2.15%   |
| HP ProBook              | 8         | 2.15%   |
| HP Compaq               | 7         | 1.88%   |
| HP Laptop               | 5         | 1.34%   |
| HP EliteBook            | 5         | 1.34%   |
| Fujitsu LIFEBOOK        | 5         | 1.34%   |
| ASUS PRIME              | 5         | 1.34%   |
| ASUS All                | 5         | 1.34%   |
| Toshiba Satellite       | 4         | 1.08%   |
| HP ENVY                 | 4         | 1.08%   |
| Lenovo G510             | 3         | 0.81%   |
| Lenovo G500             | 3         | 0.81%   |
| Gigabyte P35-DS3L       | 3         | 0.81%   |
| Foxconn G31MXP          | 3         | 0.81%   |
| Dell Latitude           | 3         | 0.81%   |
| ASUS TUF                | 3         | 0.81%   |
| Acer Predator           | 3         | 0.81%   |
| Packard Bell DOT        | 2         | 0.54%   |
| MSI MS-7788             | 2         | 0.54%   |
| Lenovo ThinkBook        | 2         | 0.54%   |
| Lenovo Legion           | 2         | 0.54%   |
| Lenovo IdeaCentre       | 2         | 0.54%   |
| Intel DG965RY           | 2         | 0.54%   |
| HPE ProLiant            | 2         | 0.54%   |
| HP ProLiant             | 2         | 0.54%   |
| HP Presario             | 2         | 0.54%   |
| HP 250                  | 2         | 0.54%   |
| Gigabyte EP45-DS3L      | 2         | 0.54%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.54%   |
| Fujitsu Siemens AMILO   | 2         | 0.54%   |
| ECS H61H2-M12           | 2         | 0.54%   |
| ECS G31T-M7             | 2         | 0.54%   |
| Biostar B75MU3B         | 2         | 0.54%   |
| ASUS X51RL              | 2         | 0.54%   |
| ASUS ROG                | 2         | 0.54%   |
| ASUS P8H61-M            | 2         | 0.54%   |
| ASUS P8B75-M            | 2         | 0.54%   |
| ASUS P5P43TD            | 2         | 0.54%   |
| ASUS H61M-K             | 2         | 0.54%   |
| ASRock Q1900M           | 2         | 0.54%   |
| ASRock G31M-VS          | 2         | 0.54%   |
| ASRock G31M-GS          | 2         | 0.54%   |
| Acidanthera iMac13      | 2         | 0.54%   |
| Acer TravelMate         | 2         | 0.54%   |
| Acer Nitro              | 2         | 0.54%   |
| Toshiba TECRA           | 1         | 0.27%   |
| Toshiba Portable        | 1         | 0.27%   |
| Sony VPCEH2M1R          | 1         | 0.27%   |
| Sony VPCEB1E1R          | 1         | 0.27%   |
| Sony VPCCB2S1R          | 1         | 0.27%   |
| Sony VGN-NW320F         | 1         | 0.27%   |
| Sony VGN-NR430E         | 1         | 0.27%   |
| Samsung R518            | 1         | 0.27%   |
| Samsung R18             | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 53        | 14.25%  |
| 2011    | 43        | 11.56%  |
| 2008    | 30        | 8.06%   |
| 2009    | 27        | 7.26%   |
| 2018    | 25        | 6.72%   |
| 2013    | 25        | 6.72%   |
| 2007    | 24        | 6.45%   |
| 2020    | 23        | 6.18%   |
| 2017    | 22        | 5.91%   |
| 2010    | 21        | 5.65%   |
| 2019    | 17        | 4.57%   |
| 2014    | 16        | 4.3%    |
| 2016    | 14        | 3.76%   |
| 2015    | 13        | 3.49%   |
| 2021    | 6         | 1.61%   |
| 2006    | 6         | 1.61%   |
| 2005    | 3         | 0.81%   |
| Unknown | 3         | 0.81%   |
| 2003    | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 201       | 54.03%  |
| Desktop        | 157       | 42.2%   |
| All in one     | 6         | 1.61%   |
| Server         | 4         | 1.08%   |
| Convertible    | 2         | 0.54%   |
| System on chip | 1         | 0.27%   |
| Tablet         | 1         | 0.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 362       | 96.79%  |
| Enabled  | 12        | 3.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 372       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 111       | 28.83%  |
| 4.01-8.0    | 90        | 23.38%  |
| 8.01-16.0   | 59        | 15.32%  |
| 16.01-24.0  | 41        | 10.65%  |
| 1.01-2.0    | 31        | 8.05%   |
| 2.01-3.0    | 26        | 6.75%   |
| 32.01-64.0  | 10        | 2.6%    |
| 0.51-1.0    | 9         | 2.34%   |
| 24.01-32.0  | 4         | 1.04%   |
| 64.01-256.0 | 2         | 0.52%   |
| Unknown     | 2         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 176       | 42.82%  |
| 0.51-1.0   | 118       | 28.71%  |
| 2.01-3.0   | 54        | 13.14%  |
| 3.01-4.0   | 22        | 5.35%   |
| 4.01-8.0   | 20        | 4.87%   |
| 8.01-16.0  | 7         | 1.7%    |
| 0.01-0.5   | 7         | 1.7%    |
| Unknown    | 5         | 1.22%   |
| 32.01-64.0 | 1         | 0.24%   |
| 16.01-24.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 244       | 62.56%  |
| 2      | 101       | 25.9%   |
| 3      | 28        | 7.18%   |
| 4      | 8         | 2.05%   |
| 5      | 3         | 0.77%   |
| 0      | 3         | 0.77%   |
| 6      | 2         | 0.51%   |
| 8      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 195       | 51.72%  |
| No        | 182       | 48.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 349       | 93.57%  |
| No        | 24        | 6.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 240       | 64%     |
| No        | 135       | 36%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 210       | 55.56%  |
| Yes       | 168       | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Kazakhstan | 372       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Almaty            | 119       | 28.4%   |
| Nur-Sultan        | 70        | 16.71%  |
| Kostanay          | 32        | 7.64%   |
| Karaganda         | 24        | 5.73%   |
| Pavlodar          | 21        | 5.01%   |
| Ust-Kamenogorsk   | 17        | 4.06%   |
| Shymkent          | 15        | 3.58%   |
| Petropavl         | 14        | 3.34%   |
| Atyrau            | 13        | 3.1%    |
| Aktobe            | 13        | 3.1%    |
| Semey             | 9         | 2.15%   |
| Taraz             | 8         | 1.91%   |
| Temirtau          | 7         | 1.67%   |
| Ridder            | 7         | 1.67%   |
| Kyzylorda         | 5         | 1.19%   |
| Shantobe          | 4         | 0.95%   |
| Oral              | 3         | 0.72%   |
| Balqash           | 3         | 0.72%   |
| Aktas             | 3         | 0.72%   |
| Taldykorgan       | 2         | 0.48%   |
| Stepnogorsk       | 2         | 0.48%   |
| Rudnyy            | 2         | 0.48%   |
| Makhambet         | 2         | 0.48%   |
| Dzhezkazgan       | 2         | 0.48%   |
| Aktau             | 2         | 0.48%   |
| Zyryanovsk        | 1         | 0.24%   |
| ZhangaГ¶zen     | 1         | 0.24%   |
| Zhaksy            | 1         | 0.24%   |
| Uritskiy          | 1         | 0.24%   |
| Tobol             | 1         | 0.24%   |
| Timiryazevo       | 1         | 0.24%   |
| Talghar           | 1         | 0.24%   |
| ShchЕ«chД«nsk | 1         | 0.24%   |
| ShchÅ«chÄ«nsk | 1         | 0.24%   |
| Sarkand           | 1         | 0.24%   |
| Osakarovka        | 1         | 0.24%   |
| LenÄ«nskoe      | 1         | 0.24%   |
| Kokshetau         | 1         | 0.24%   |
| Kaskelen          | 1         | 0.24%   |
| Kapshagay         | 1         | 0.24%   |
| GГјlshat        | 1         | 0.24%   |
| Esil              | 1         | 0.24%   |
| Burma             | 1         | 0.24%   |
| Aksay             | 1         | 0.24%   |
| Akkol'            | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 212    | 27.06%  |
| WDC                 | 89        | 116    | 17.08%  |
| Samsung Electronics | 57        | 82     | 10.94%  |
| Toshiba             | 55        | 68     | 10.56%  |
| Kingston            | 26        | 30     | 4.99%   |
| Hitachi             | 24        | 27     | 4.61%   |
| Unknown             | 16        | 20     | 3.07%   |
| HGST                | 14        | 16     | 2.69%   |
| Transcend           | 12        | 13     | 2.3%    |
| A-DATA Technology   | 9         | 11     | 1.73%   |
| SanDisk             | 8         | 9      | 1.54%   |
| SK Hynix            | 7         | 7      | 1.34%   |
| Apacer              | 7         | 10     | 1.34%   |
| Intel               | 6         | 7      | 1.15%   |
| PLEXTOR             | 5         | 5      | 0.96%   |
| Micron Technology   | 4         | 8      | 0.77%   |
| KIOXIA              | 4         | 6      | 0.77%   |
| Gigabyte Technology | 4         | 4      | 0.77%   |
| GeIL                | 4         | 4      | 0.77%   |
| Team                | 3         | 3      | 0.58%   |
| HUAWEI              | 3         | 3      | 0.58%   |
| Fujitsu             | 3         | 4      | 0.58%   |
| Crucial             | 3         | 4      | 0.58%   |
| China               | 3         | 3      | 0.58%   |
| HPE                 | 2         | 2      | 0.38%   |
| AMD                 | 2         | 2      | 0.38%   |
| TEKET               | 1         | 2      | 0.19%   |
| SPCC                | 1         | 1      | 0.19%   |
| SmartBuy            | 1         | 1      | 0.19%   |
| Phison              | 1         | 1      | 0.19%   |
| Patriot             | 1         | 1      | 0.19%   |
| MAXTOR              | 1         | 1      | 0.19%   |
| KingSpec            | 1         | 1      | 0.19%   |
| Kingmax             | 1         | 1      | 0.19%   |
| Kingchuxing         | 1         | 2      | 0.19%   |
| JMicron             | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 16        | 2.86%   |
| Toshiba DT01ACA050 500GB            | 12        | 2.14%   |
| Seagate ST500DM002-1BD142 500GB     | 12        | 2.14%   |
| Seagate ST1000LM035-1RK172 1TB      | 9         | 1.61%   |
| Seagate ST3500418AS 500GB           | 8         | 1.43%   |
| WDC WD5000AAKX-001CA0 500GB         | 6         | 1.07%   |
| Toshiba MQ04ABF100 1TB              | 6         | 1.07%   |
| Seagate ST3500413AS 500GB           | 6         | 1.07%   |
| Seagate ST3250310AS 249GB           | 6         | 1.07%   |
| Toshiba MQ01ABD100 1TB              | 5         | 0.89%   |
| Toshiba DT01ACA100 1TB              | 5         | 0.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 0.89%   |
| Samsung HD502HJ 500GB               | 5         | 0.89%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 4         | 0.71%   |
| WDC WD10SPZX-21Z10T0 1TB            | 4         | 0.71%   |
| Toshiba MQ01ABF050 500GB            | 4         | 0.71%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 0.71%   |
| Seagate ST380011A 80GB              | 4         | 0.71%   |
| Seagate ST3160815AS 160GB           | 4         | 0.71%   |
| Samsung HD322HJ 320GB               | 4         | 0.71%   |
| Kingston SA400S37240G 240GB SSD     | 4         | 0.71%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 0.71%   |
| Intel NVMe SSD Drive 512GB          | 4         | 0.71%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.71%   |
| Transcend TS120GSSD220S 120GB       | 3         | 0.54%   |
| Toshiba HDWD105 500GB               | 3         | 0.54%   |
| SK Hynix NVMe SSD Drive 512GB       | 3         | 0.54%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 0.54%   |
| Seagate ST380215AS 80GB             | 3         | 0.54%   |
| Seagate ST3802110A 80GB             | 3         | 0.54%   |
| Seagate ST3500320AS 500GB           | 3         | 0.54%   |
| Seagate ST340014A 40GB              | 3         | 0.54%   |
| Seagate ST3320613AS 320GB           | 3         | 0.54%   |
| Seagate ST3250820AS 250GB           | 3         | 0.54%   |
| Seagate ST3250318AS 250GB           | 3         | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 0.54%   |
| Sandisk NVMe SSD Drive 512GB        | 3         | 0.54%   |
| Samsung HD502HI 500GB               | 3         | 0.54%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.54%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 0.54%   |
| Hitachi HTS547550A9E384 500GB       | 3         | 0.54%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 0.54%   |
| HGST HTS545050A7E380 500GB          | 3         | 0.54%   |
| WDC WD800JD-60LSA0 80GB             | 2         | 0.36%   |
| WDC WD7500BPVT-22HXZT3 752GB        | 2         | 0.36%   |
| WDC WD7500BPVT-08HXZT3 752GB        | 2         | 0.36%   |
| WDC WD5000LPVX-00V0TT0 500GB        | 2         | 0.36%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 2         | 0.36%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.36%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 0.36%   |
| WDC WD2000JS-60NCB1 200GB           | 2         | 0.36%   |
| Unknown NCard  32GB                 | 2         | 0.36%   |
| Unknown MMC Card  4GB               | 2         | 0.36%   |
| Unknown MMC Card  16GB              | 2         | 0.36%   |
| Transcend TS240GSSD220S 240GB       | 2         | 0.36%   |
| Toshiba MK5059GSXP 500GB            | 2         | 0.36%   |
| Toshiba HDWD110 1TB                 | 2         | 0.36%   |
| Toshiba DT01ACA200 2TB              | 2         | 0.36%   |
| Seagate ST9320325AS 320GB           | 2         | 0.36%   |
| Seagate ST9250315AS 250GB           | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 139       | 210    | 38.94%  |
| WDC                 | 86        | 113    | 24.09%  |
| Toshiba             | 54        | 67     | 15.13%  |
| Samsung Electronics | 35        | 54     | 9.8%    |
| Hitachi             | 24        | 27     | 6.72%   |
| HGST                | 14        | 16     | 3.92%   |
| Fujitsu             | 3         | 4      | 0.84%   |
| Unknown             | 1         | 1      | 0.28%   |
| MAXTOR              | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 23        | 27     | 22.77%  |
| Transcend           | 12        | 13     | 11.88%  |
| Samsung Electronics | 12        | 14     | 11.88%  |
| Apacer              | 6         | 9      | 5.94%   |
| PLEXTOR             | 5         | 5      | 4.95%   |
| Gigabyte Technology | 4         | 4      | 3.96%   |
| Team                | 3         | 3      | 2.97%   |
| SK Hynix            | 3         | 3      | 2.97%   |
| SanDisk             | 3         | 3      | 2.97%   |
| GeIL                | 3         | 3      | 2.97%   |
| Crucial             | 3         | 4      | 2.97%   |
| China               | 3         | 3      | 2.97%   |
| A-DATA Technology   | 3         | 4      | 2.97%   |
| Micron Technology   | 2         | 2      | 1.98%   |
| Intel               | 2         | 3      | 1.98%   |
| HPE                 | 2         | 2      | 1.98%   |
| AMD                 | 2         | 2      | 1.98%   |
| WDC                 | 1         | 1      | 0.99%   |
| Unknown             | 1         | 1      | 0.99%   |
| TEKET               | 1         | 2      | 0.99%   |
| SPCC                | 1         | 1      | 0.99%   |
| SmartBuy            | 1         | 1      | 0.99%   |
| Patriot             | 1         | 1      | 0.99%   |
| KingSpec            | 1         | 1      | 0.99%   |
| Kingmax             | 1         | 1      | 0.99%   |
| Kingchuxing         | 1         | 2      | 0.99%   |
| JMicron             | 1         | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 300       | 493    | 66.37%  |
| SSD     | 88        | 116    | 19.47%  |
| NVMe    | 43        | 54     | 9.51%   |
| MMC     | 15        | 19     | 3.32%   |
| Unknown | 6         | 6      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 331       | 599    | 82.34%  |
| NVMe | 43        | 54     | 10.7%   |
| MMC  | 15        | 19     | 3.73%   |
| SAS  | 13        | 16     | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 272       | 434    | 68.86%  |
| 0.51-1.0   | 108       | 157    | 27.34%  |
| 1.01-2.0   | 11        | 14     | 2.78%   |
| 3.01-4.0   | 2         | 2      | 0.51%   |
| 2.01-3.0   | 1         | 1      | 0.25%   |
| 4.01-10.0  | 1         | 1      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 106       | 25.85%  |
| 101-250        | 86        | 20.98%  |
| 501-1000       | 61        | 14.88%  |
| 1-20           | 48        | 11.71%  |
| 51-100         | 44        | 10.73%  |
| 21-50          | 30        | 7.32%   |
| 1001-2000      | 24        | 5.85%   |
| Unknown        | 7         | 1.71%   |
| 2001-3000      | 3         | 0.73%   |
| More than 3000 | 1         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 225       | 55.01%  |
| 21-50     | 52        | 12.71%  |
| 101-250   | 42        | 10.27%  |
| 51-100    | 29        | 7.09%   |
| 251-500   | 26        | 6.36%   |
| 501-1000  | 20        | 4.89%   |
| Unknown   | 7         | 1.71%   |
| 1001-2000 | 6         | 1.47%   |
| 2001-3000 | 2         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 6         | 8      | 4.26%   |
| WDC WD5000AAKX-001CA0 500GB         | 5         | 5      | 3.55%   |
| Seagate ST3250310AS 249GB           | 5         | 5      | 3.55%   |
| Seagate ST3802110A 80GB             | 3         | 5      | 2.13%   |
| Seagate ST3500413AS 500GB           | 3         | 3      | 2.13%   |
| Seagate ST3500320AS 500GB           | 3         | 3      | 2.13%   |
| Seagate ST3320613AS 320GB           | 3         | 3      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 2.13%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 3      | 2.13%   |
| WDC WD800JD-60LSA0 80GB             | 2         | 2      | 1.42%   |
| WDC WD5000LPVX-00V0TT0 500GB        | 2         | 4      | 1.42%   |
| WDC WD2000JS-60NCB1 200GB           | 2         | 3      | 1.42%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 1.42%   |
| Toshiba MK5059GSXP 500GB            | 2         | 3      | 1.42%   |
| Toshiba DT01ACA050 500GB            | 2         | 2      | 1.42%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 9      | 1.42%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 5      | 1.42%   |
| Seagate ST380215AS 80GB             | 2         | 2      | 1.42%   |
| Seagate ST3500418AS 500GB           | 2         | 4      | 1.42%   |
| Seagate ST340014A 40GB              | 2         | 2      | 1.42%   |
| Seagate ST3320620AS 320GB           | 2         | 2      | 1.42%   |
| Seagate ST3250820AS 250GB           | 2         | 2      | 1.42%   |
| Seagate ST3160815AS 160GB           | 2         | 2      | 1.42%   |
| Seagate ST3160215AS 160GB           | 2         | 2      | 1.42%   |
| Samsung Electronics HD502HI 500GB   | 2         | 3      | 1.42%   |
| Hitachi HTS547550A9E384 500GB       | 2         | 3      | 1.42%   |
| Hitachi HTS543216L9SA00 160GB       | 2         | 2      | 1.42%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 1.42%   |
| HGST HTS541010A9E680 1TB            | 2         | 3      | 1.42%   |
| WDC WD7500BPVT-24HXZT3 752GB        | 1         | 3      | 0.71%   |
| WDC WD7500BPVT-08HXZT3 752GB        | 1         | 1      | 0.71%   |
| WDC WD5000AVDS-73U7B1 500GB         | 1         | 1      | 0.71%   |
| WDC WD5000AAKX-003CA0 500GB         | 1         | 1      | 0.71%   |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 1      | 0.71%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 1         | 1      | 0.71%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 1         | 1      | 0.71%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 1      | 0.71%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1      | 0.71%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 0.71%   |
| WDC WD3200AAJS-00L7A0 320GB         | 1         | 3      | 0.71%   |
| WDC WD2500AVJS-63B6A0 250GB         | 1         | 1      | 0.71%   |
| WDC WD2500AAKX-001CA0 250GB         | 1         | 1      | 0.71%   |
| WDC WD15EARS-00MVWB0 1TB            | 1         | 1      | 0.71%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 1      | 0.71%   |
| WDC WD10EALX-009BA0 1TB             | 1         | 1      | 0.71%   |
| WDC WD10EADS-00M2B0 1TB             | 1         | 3      | 0.71%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 0.71%   |
| Toshiba MK3263GSX 320GB             | 1         | 1      | 0.71%   |
| Toshiba MK2552GSX 250GB             | 1         | 1      | 0.71%   |
| Toshiba MK1637GSX 160GB             | 1         | 1      | 0.71%   |
| Seagate ST9500325AS 500GB           | 1         | 2      | 0.71%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 0.71%   |
| Seagate ST9250410AS 250GB           | 1         | 1      | 0.71%   |
| Seagate ST9120822AS 120GB           | 1         | 1      | 0.71%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 2      | 0.71%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 0.71%   |
| Seagate ST380817AS 80GB             | 1         | 1      | 0.71%   |
| Seagate ST380815AS 80GB             | 1         | 1      | 0.71%   |
| Seagate ST380013AS 80GB             | 1         | 1      | 0.71%   |
| Seagate ST3500630AS 500GB           | 1         | 1      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 89     | 47.37%  |
| WDC                 | 28        | 37     | 21.05%  |
| Hitachi             | 14        | 16     | 10.53%  |
| Toshiba             | 10        | 11     | 7.52%   |
| Samsung Electronics | 9         | 12     | 6.77%   |
| HGST                | 6         | 7      | 4.51%   |
| PLEXTOR             | 1         | 1      | 0.75%   |
| MAXTOR              | 1         | 1      | 0.75%   |
| Kingston            | 1         | 1      | 0.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 89     | 48.09%  |
| WDC                 | 28        | 37     | 21.37%  |
| Hitachi             | 14        | 16     | 10.69%  |
| Toshiba             | 10        | 11     | 7.63%   |
| Samsung Electronics | 9         | 12     | 6.87%   |
| HGST                | 6         | 7      | 4.58%   |
| MAXTOR              | 1         | 1      | 0.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 118       | 173    | 98.33%  |
| SSD  | 2         | 2      | 1.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD322GJ 320GB | 2         | 2      | 50%     |
| WDC WD3200BPVT-24ZEST0 320GB      | 1         | 1      | 25%     |
| Seagate ST3250318AS 250GB         | 1         | 3      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 3      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 217       | 371    | 49.66%  |
| Malfunc  | 120       | 175    | 27.46%  |
| Detected | 96        | 136    | 21.97%  |
| Failed   | 4         | 6      | 0.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 305       | 69.95%  |
| AMD                           | 39        | 8.94%   |
| JMicron Technology            | 20        | 4.59%   |
| Samsung Electronics           | 13        | 2.98%   |
| Marvell Technology Group      | 10        | 2.29%   |
| Nvidia                        | 8         | 1.83%   |
| Sandisk                       | 5         | 1.15%   |
| SK Hynix                      | 4         | 0.92%   |
| ASMedia Technology            | 4         | 0.92%   |
| Realtek Semiconductor         | 3         | 0.69%   |
| KIOXIA                        | 3         | 0.69%   |
| Kingston Technology Company   | 3         | 0.69%   |
| ADATA Technology              | 3         | 0.69%   |
| VIA Technologies              | 2         | 0.46%   |
| Toshiba America Info Systems  | 2         | 0.46%   |
| Phison Electronics            | 2         | 0.46%   |
| Micron Technology             | 2         | 0.46%   |
| Integrated Technology Express | 2         | 0.46%   |
| Hewlett-Packard               | 2         | 0.46%   |
| Adaptec                       | 2         | 0.46%   |
| Union Memory (Shenzhen)       | 1         | 0.23%   |
| ULi Electronics               | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28        | 5.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 26        | 4.69%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 25        | 4.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 24        | 4.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 21        | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16        | 2.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15        | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 15        | 2.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 2.17%   |
| JMicron JMB368 IDE controller                                                           | 11        | 1.99%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 10        | 1.81%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 10        | 1.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 1.44%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8         | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 8         | 1.44%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8         | 1.44%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 7         | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 6         | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 1.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 6         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 6         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6         | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 5         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 0.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 5         | 0.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 0.9%    |
| Samsung NVMe SSD Controller 980                                                         | 4         | 0.72%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 4         | 0.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 0.72%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4         | 0.72%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4         | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 0.72%   |
| SK Hynix BC511                                                                          | 3         | 0.54%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.54%   |
| Intel SSD 660P Series                                                                   | 3         | 0.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 3         | 0.54%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3         | 0.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 0.54%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 0.36%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.36%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 243       | 56.25%  |
| IDE  | 118       | 27.31%  |
| NVMe | 44        | 10.19%  |
| RAID | 24        | 5.56%   |
| SAS  | 3         | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 324       | 87.1%   |
| AMD    | 47        | 12.63%  |
| ARM    | 1         | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU G630 @ 2.70GHz              | 5         | 1.34%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 1.34%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.07%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.07%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 1.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.07%   |
| Intel Pentium 4 CPU 3.00GHz                   | 3         | 0.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.8%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.8%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.8%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.8%    |
| Intel Core i3-3240 CPU @ 3.40GHz              | 3         | 0.8%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.8%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.8%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.8%    |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3         | 0.8%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.8%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 3         | 0.8%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 3         | 0.8%    |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz          | 3         | 0.8%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 0.8%    |
| AMD A8-4500M APU with Radeon HD Graphics      | 3         | 0.8%    |
| AMD A10-4600M APU with Radeon HD Graphics     | 3         | 0.8%    |
| Intel Xeon Silver 4114 CPU @ 2.20GHz          | 2         | 0.53%   |
| Intel Xeon CPU E5450 @ 3.00GHz                | 2         | 0.53%   |
| Intel Xeon CPU E5420 @ 2.50GHz                | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 2         | 0.53%   |
| Intel Pentium CPU G645 @ 2.90GHz              | 2         | 0.53%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 2         | 0.53%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.53%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.53%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.53%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.53%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.53%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.53%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 2         | 0.53%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.53%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.53%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 2         | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.53%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.53%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.53%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.53%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 0.53%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 2         | 0.53%   |
| Intel Core i3-2348M CPU @ 2.30GHz             | 2         | 0.53%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 79        | 21.12%  |
| Intel Core i3           | 51        | 13.64%  |
| Intel Core i7           | 44        | 11.76%  |
| Intel Core 2 Duo        | 29        | 7.75%   |
| Intel Celeron           | 26        | 6.95%   |
| Intel Pentium           | 18        | 4.81%   |
| Intel Pentium Dual-Core | 14        | 3.74%   |
| Intel Xeon              | 11        | 2.94%   |
| Intel Atom              | 11        | 2.94%   |
| Other                   | 9         | 2.41%   |
| AMD Ryzen 5             | 9         | 2.41%   |
| Intel Pentium 4         | 6         | 1.6%    |
| Intel Genuine           | 6         | 1.6%    |
| Intel Core 2 Quad       | 6         | 1.6%    |
| Intel Pentium Dual      | 5         | 1.34%   |
| Intel Core 2            | 4         | 1.07%   |
| AMD Ryzen 3             | 4         | 1.07%   |
| AMD E                   | 4         | 1.07%   |
| AMD A8                  | 4         | 1.07%   |
| AMD A10                 | 4         | 1.07%   |
| AMD Ryzen 7             | 3         | 0.8%    |
| AMD A4                  | 3         | 0.8%    |
| Intel Xeon Silver       | 2         | 0.53%   |
| Intel Pentium Gold      | 2         | 0.53%   |
| AMD Phenom II X6        | 2         | 0.53%   |
| AMD Phenom II X4        | 2         | 0.53%   |
| AMD Athlon 64 X2        | 2         | 0.53%   |
| AMD A6                  | 2         | 0.53%   |
| Intel Pentium Silver    | 1         | 0.27%   |
| Intel Mobile Pentium 4  | 1         | 0.27%   |
| Intel Core i9           | 1         | 0.27%   |
| Intel Core Duo          | 1         | 0.27%   |
| Intel Core 2 Extreme    | 1         | 0.27%   |
| AMD FX                  | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD C-60                | 1         | 0.27%   |
| AMD Athlon II X2        | 1         | 0.27%   |
| AMD Athlon II           | 1         | 0.27%   |
| AMD Athlon 64           | 1         | 0.27%   |
| AMD A12                 | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 198       | 52.94%  |
| 4       | 109       | 29.14%  |
| Unknown | 22        | 5.88%   |
| 1       | 17        | 4.55%   |
| 6       | 14        | 3.74%   |
| 8       | 10        | 2.67%   |
| 20      | 2         | 0.53%   |
| 12      | 1         | 0.27%   |
| 3       | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 364       | 97.85%  |
| 2       | 7         | 1.88%   |
| Unknown | 1         | 0.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 194       | 52.15%  |
| 1       | 156       | 41.94%  |
| Unknown | 22        | 5.91%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 354       | 95.16%  |
| Unknown        | 10        | 2.69%   |
| 32-bit         | 8         | 2.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 42        | 11.05%  |
| 0x306a9    | 41        | 10.79%  |
| Unknown    | 38        | 10%     |
| 0x1067a    | 36        | 9.47%   |
| 0x306c3    | 19        | 5%      |
| 0x906ea    | 10        | 2.63%   |
| 0x6fd      | 10        | 2.63%   |
| 0x906e9    | 9         | 2.37%   |
| 0x806ea    | 9         | 2.37%   |
| 0x806e9    | 9         | 2.37%   |
| 0x10676    | 9         | 2.37%   |
| 0x20655    | 8         | 2.11%   |
| 0x06001119 | 8         | 2.11%   |
| 0x806c1    | 7         | 1.84%   |
| 0x20652    | 7         | 1.84%   |
| 0x406e3    | 6         | 1.58%   |
| 0x40651    | 6         | 1.58%   |
| 0x6fb      | 5         | 1.32%   |
| 0x406c4    | 5         | 1.32%   |
| 0x30678    | 5         | 1.32%   |
| 0x6e8      | 4         | 1.05%   |
| 0x30661    | 4         | 1.05%   |
| 0xf49      | 3         | 0.79%   |
| 0x806ec    | 3         | 0.79%   |
| 0x706a1    | 3         | 0.79%   |
| 0x506e3    | 3         | 0.79%   |
| 0x10661    | 3         | 0.79%   |
| 0x08108102 | 3         | 0.79%   |
| 0xa0652    | 2         | 0.53%   |
| 0x906ed    | 2         | 0.53%   |
| 0x806eb    | 2         | 0.53%   |
| 0x706e5    | 2         | 0.53%   |
| 0x6f6      | 2         | 0.53%   |
| 0x6f2      | 2         | 0.53%   |
| 0x6ec      | 2         | 0.53%   |
| 0x50654    | 2         | 0.53%   |
| 0x306d4    | 2         | 0.53%   |
| 0x106ca    | 2         | 0.53%   |
| 0x106a5    | 2         | 0.53%   |
| 0x08701021 | 2         | 0.53%   |
| 0x08108109 | 2         | 0.53%   |
| 0x07030105 | 2         | 0.53%   |
| 0x0700010f | 2         | 0.53%   |
| 0x05000119 | 2         | 0.53%   |
| 0x05000029 | 2         | 0.53%   |
| 0x03000027 | 2         | 0.53%   |
| 0x010000dc | 2         | 0.53%   |
| 0x010000c8 | 2         | 0.53%   |
| 0xf65      | 1         | 0.26%   |
| 0xf4a      | 1         | 0.26%   |
| 0xf43      | 1         | 0.26%   |
| 0xf27      | 1         | 0.26%   |
| 0xa0653    | 1         | 0.26%   |
| 0x906ec    | 1         | 0.26%   |
| 0x6fa      | 1         | 0.26%   |
| 0x406c3    | 1         | 0.26%   |
| 0x306e4    | 1         | 0.26%   |
| 0x30673    | 1         | 0.26%   |
| 0x206d7    | 1         | 0.26%   |
| 0x106e5    | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 50        | 13.37%  |
| Penryn        | 48        | 12.83%  |
| SandyBridge   | 44        | 11.76%  |
| IvyBridge     | 44        | 11.76%  |
| Core          | 27        | 7.22%   |
| Haswell       | 26        | 6.95%   |
| Westmere      | 15        | 4.01%   |
| Silvermont    | 14        | 3.74%   |
| Skylake       | 12        | 3.21%   |
| Piledriver    | 9         | 2.41%   |
| TigerLake     | 8         | 2.14%   |
| Zen+          | 7         | 1.87%   |
| NetBurst      | 7         | 1.87%   |
| Bonnell       | 7         | 1.87%   |
| P6            | 6         | 1.6%    |
| K10           | 6         | 1.6%    |
| Zen 2         | 5         | 1.34%   |
| CometLake     | 5         | 1.34%   |
| Bobcat        | 5         | 1.34%   |
| K8 Hammer     | 4         | 1.07%   |
| IceLake       | 4         | 1.07%   |
| Goldmont plus | 4         | 1.07%   |
| Nehalem       | 3         | 0.8%    |
| Unknown       | 3         | 0.8%    |
| Zen           | 2         | 0.53%   |
| Puma          | 2         | 0.53%   |
| K10 Llano     | 2         | 0.53%   |
| Jaguar        | 2         | 0.53%   |
| Broadwell     | 2         | 0.53%   |
| Excavator     | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 198       | 43.52%  |
| Nvidia                     | 175       | 38.46%  |
| AMD                        | 80        | 17.58%  |
| Matrox Electronics Systems | 2         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 6.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 4.37%   |
| Intel UHD Graphics 620                                                                   | 9         | 1.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 1.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 8         | 1.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.46%   |
| Intel HD Graphics 630                                                                    | 7         | 1.46%   |
| Intel HD Graphics 620                                                                    | 7         | 1.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 6         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.25%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 1.25%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.04%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 5         | 1.04%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 1.04%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 5         | 1.04%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 5         | 1.04%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 5         | 1.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.04%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.04%   |
| Nvidia TU117M                                                                            | 4         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.83%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 4         | 0.83%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.83%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.83%   |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 4         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.62%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 3         | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.62%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3         | 0.62%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.62%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 3         | 0.62%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 3         | 0.62%   |
| Nvidia GF119M [GeForce 610M]                                                             | 3         | 0.62%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 3         | 0.62%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 3         | 0.62%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 0.62%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 3         | 0.62%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 3         | 0.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.62%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 3         | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.62%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.62%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 0.62%   |
| AMD Trinity [Radeon HD 7660G]                                                            | 3         | 0.62%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 3         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 120       | 31.83%  |
| 1 x Nvidia     | 117       | 31.03%  |
| Intel + Nvidia | 56        | 14.85%  |
| 1 x AMD        | 48        | 12.73%  |
| Intel + AMD    | 18        | 4.77%   |
| 2 x AMD        | 12        | 3.18%   |
| AMD + Nvidia   | 3         | 0.8%    |
| 1 x Matrox     | 2         | 0.53%   |
| Other          | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 299       | 78.27%  |
| Proprietary | 71        | 18.59%  |
| Unknown     | 12        | 3.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 114       | 29.77%  |
| Unknown    | 105       | 27.42%  |
| 0.51-1.0   | 62        | 16.19%  |
| 0.01-0.5   | 62        | 16.19%  |
| 3.01-4.0   | 27        | 7.05%   |
| 7.01-8.0   | 6         | 1.57%   |
| 5.01-6.0   | 5         | 1.31%   |
| 2.01-3.0   | 1         | 0.26%   |
| 8.01-16.0  | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 71        | 19.14%  |
| AU Optronics            | 55        | 14.82%  |
| LG Display              | 41        | 11.05%  |
| Goldstar                | 26        | 7.01%   |
| Chimei Innolux          | 23        | 6.2%    |
| BOE                     | 22        | 5.93%   |
| Acer                    | 17        | 4.58%   |
| Hewlett-Packard         | 16        | 4.31%   |
| BenQ                    | 16        | 4.31%   |
| Philips                 | 14        | 3.77%   |
| Chi Mei Optoelectronics | 12        | 3.23%   |
| Lenovo                  | 8         | 2.16%   |
| AOC                     | 8         | 2.16%   |
| Dell                    | 7         | 1.89%   |
| ViewSonic               | 3         | 0.81%   |
| Toshiba                 | 3         | 0.81%   |
| LG Philips              | 3         | 0.81%   |
| Sony                    | 2         | 0.54%   |
| Quanta Display          | 2         | 0.54%   |
| PANDA                   | 2         | 0.54%   |
| HannStar                | 2         | 0.54%   |
| Fujitsu Siemens         | 2         | 0.54%   |
| CPT                     | 2         | 0.54%   |
| WY@                     | 1         | 0.27%   |
| VIE                     | 1         | 0.27%   |
| Unknown (XXX)           | 1         | 0.27%   |
| TPU                     | 1         | 0.27%   |
| SKY                     | 1         | 0.27%   |
| Sharp                   | 1         | 0.27%   |
| Seiko/Epson             | 1         | 0.27%   |
| Packard Bell            | 1         | 0.27%   |
| LG Electronics          | 1         | 0.27%   |
| KDC                     | 1         | 0.27%   |
| InfoVision              | 1         | 0.27%   |
| Iiyama                  | 1         | 0.27%   |
| HJW                     | 1         | 0.27%   |
| Ancor Communications    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 1.59%   |
| Samsung Electronics SyncMaster SAM018F 1280x1024 338x270mm 17.0-inch     | 5         | 1.33%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 4         | 1.06%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.06%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 1.06%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.06%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch      | 3         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.8%    |
| BenQ E900W BNQ7905 1440x900 410x256mm 19.0-inch                          | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.8%    |
| Acer V193HQL ACR006D 1366x768 410x230mm 18.5-inch                        | 3         | 0.8%    |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch      | 2         | 0.53%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch     | 2         | 0.53%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch       | 2         | 0.53%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch        | 2         | 0.53%   |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch        | 2         | 0.53%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch         | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch    | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                        | 2         | 0.53%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                      | 2         | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.53%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch              | 2         | 0.53%   |
| Hewlett-Packard 2011 HWP2934 1600x900 443x249mm 20.0-inch                | 2         | 0.53%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 2         | 0.53%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                     | 2         | 0.53%   |
| Goldstar W2242 GSM4B6F 1680x1050 474x296mm 22.0-inch                     | 2         | 0.53%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                      | 2         | 0.53%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 2         | 0.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.53%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 0.53%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.53%   |
| BenQ G700 BNQ7801 1280x1024 338x270mm 17.0-inch                          | 2         | 0.53%   |
| BenQ E900 BNQ7903 1280x1024 376x301mm 19.0-inch                          | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 2         | 0.53%   |
| WY@ Monitor WY@0170 1280x1024                                            | 1         | 0.27%   |
| ViewSonic VX715 VSC4319 1280x1024 338x270mm 17.0-inch                    | 1         | 0.27%   |
| ViewSonic VX2268wm VSC0E23 1680x1050 474x296mm 22.0-inch                 | 1         | 0.27%   |
| ViewSonic LCD Monitor VSC5E1E 1440x900 410x260mm 19.1-inch               | 1         | 0.27%   |
| VIE A/G2356 VIE2300 1920x1080 500x300mm 23.0-inch                        | 1         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 123       | 33.79%  |
| 1366x768 (WXGA)    | 117       | 32.14%  |
| 1280x1024 (SXGA)   | 36        | 9.89%   |
| 1600x900 (HD+)     | 23        | 6.32%   |
| 1440x900 (WXGA+)   | 14        | 3.85%   |
| 1680x1050 (WSXGA+) | 13        | 3.57%   |
| 1280x800 (WXGA)    | 11        | 3.02%   |
| 3840x2160 (4K)     | 5         | 1.37%   |
| 1024x600           | 5         | 1.37%   |
| 1360x768           | 4         | 1.1%    |
| 2560x1440 (QHD)    | 2         | 0.55%   |
| 2560x1080          | 2         | 0.55%   |
| 1920x1200 (WUXGA)  | 2         | 0.55%   |
| 1400x1050          | 2         | 0.55%   |
| 3600x1080          | 1         | 0.27%   |
| 1280x960           | 1         | 0.27%   |
| 1280x720 (HD)      | 1         | 0.27%   |
| 1024x768 (XGA)     | 1         | 0.27%   |
| Unknown            | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 139       | 37.37%  |
| 17      | 39        | 10.48%  |
| 21      | 28        | 7.53%   |
| 18      | 26        | 6.99%   |
| 19      | 24        | 6.45%   |
| 23      | 14        | 3.76%   |
| 14      | 13        | 3.49%   |
| 20      | 11        | 2.96%   |
| 13      | 11        | 2.96%   |
| 27      | 10        | 2.69%   |
| Unknown | 10        | 2.69%   |
| 24      | 9         | 2.42%   |
| 22      | 8         | 2.15%   |
| 10      | 6         | 1.61%   |
| 11      | 4         | 1.08%   |
| 40      | 3         | 0.81%   |
| 72      | 2         | 0.54%   |
| 54      | 2         | 0.54%   |
| 48      | 2         | 0.54%   |
| 43      | 2         | 0.54%   |
| 31      | 2         | 0.54%   |
| 12      | 2         | 0.54%   |
| 64      | 1         | 0.27%   |
| 34      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 16      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 179       | 48.51%  |
| 401-500     | 84        | 22.76%  |
| 351-400     | 32        | 8.67%   |
| 501-600     | 30        | 8.13%   |
| 201-300     | 18        | 4.88%   |
| Unknown     | 10        | 2.71%   |
| 1001-1500   | 5         | 1.36%   |
| 801-900     | 4         | 1.08%   |
| 701-800     | 2         | 0.54%   |
| 601-700     | 2         | 0.54%   |
| 1501-2000   | 2         | 0.54%   |
| 901-1000    | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 270       | 75.42%  |
| 5/4     | 36        | 10.06%  |
| 16/10   | 36        | 10.06%  |
| Unknown | 6         | 1.68%   |
| 4/3     | 5         | 1.4%    |
| 3/2     | 3         | 0.84%   |
| 6/5     | 1         | 0.28%   |
| 21/9    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 138       | 37.2%   |
| 201-250        | 49        | 13.21%  |
| 141-150        | 45        | 12.13%  |
| 151-200        | 44        | 11.86%  |
| 81-90          | 18        | 4.85%   |
| 121-130        | 16        | 4.31%   |
| 301-350        | 11        | 2.96%   |
| Unknown        | 10        | 2.7%    |
| More than 1000 | 7         | 1.89%   |
| 71-80          | 6         | 1.62%   |
| 41-50          | 6         | 1.62%   |
| 501-1000       | 5         | 1.35%   |
| 51-60          | 4         | 1.08%   |
| 351-500        | 4         | 1.08%   |
| 251-300        | 3         | 0.81%   |
| 131-140        | 2         | 0.54%   |
| 91-100         | 2         | 0.54%   |
| 61-70          | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 147       | 39.84%  |
| 101-120 | 128       | 34.69%  |
| 121-160 | 70        | 18.97%  |
| 1-50    | 10        | 2.71%   |
| Unknown | 10        | 2.71%   |
| 161-240 | 4         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 338       | 89.42%  |
| 2     | 26        | 6.88%   |
| 0     | 13        | 3.44%   |
| 3     | 1         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 249       | 43.68%  |
| Intel                           | 109       | 19.12%  |
| Qualcomm Atheros                | 95        | 16.67%  |
| Broadcom                        | 29        | 5.09%   |
| Broadcom Limited                | 14        | 2.46%   |
| Ralink                          | 10        | 1.75%   |
| Huawei Technologies             | 8         | 1.4%    |
| Ralink Technology               | 7         | 1.23%   |
| Marvell Technology Group        | 7         | 1.23%   |
| Qualcomm Atheros Communications | 6         | 1.05%   |
| Nvidia                          | 6         | 1.05%   |
| VIA Technologies                | 4         | 0.7%    |
| Xiaomi                          | 3         | 0.53%   |
| MediaTek                        | 3         | 0.53%   |
| JMicron Technology              | 3         | 0.53%   |
| Hewlett-Packard                 | 3         | 0.53%   |
| D-Link                          | 3         | 0.53%   |
| Samsung Electronics             | 2         | 0.35%   |
| HTC (High Tech Computer)        | 2         | 0.35%   |
| TP-Link                         | 1         | 0.18%   |
| STMicroelectronics              | 1         | 0.18%   |
| Philips (or NXP)                | 1         | 0.18%   |
| Fujitsu Siemens Computers       | 1         | 0.18%   |
| Edimax Technology               | 1         | 0.18%   |
| Android                         | 1         | 0.18%   |
| Accton Technology               | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 163       | 26.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 55        | 8.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 2.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 2.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 9         | 1.44%   |
| Intel Wireless 8265 / 8275                                              | 9         | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 1.28%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.28%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 7         | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                    | 7         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.96%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 0.96%   |
| Huawei E353/E3131                                                       | 6         | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 0.8%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 4         | 0.64%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 0.64%   |
| Intel Wireless 3160                                                     | 4         | 0.64%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.64%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.64%   |
| Intel 82579V Gigabit Network Connection                                 | 4         | 0.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.64%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 4         | 0.64%   |
| Broadcom BCM43227 802.11b/g/n                                           | 4         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 0.48%   |
| Intel WiFi Link 5100                                                    | 3         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                    | 3         | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.48%   |
| Intel 82573L Gigabit Ethernet Controller                                | 3         | 0.48%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                    | 3         | 0.48%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.32%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 2         | 0.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.32%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 0.32%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.32%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 2         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 2         | 0.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.32%   |
| Nvidia CK804 Ethernet Controller                                        | 2         | 0.32%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.32%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 2         | 0.32%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 31.97%  |
| Qualcomm Atheros                | 72        | 29.51%  |
| Realtek Semiconductor           | 32        | 13.11%  |
| Broadcom                        | 24        | 9.84%   |
| Ralink                          | 10        | 4.1%    |
| Ralink Technology               | 7         | 2.87%   |
| Qualcomm Atheros Communications | 6         | 2.46%   |
| Broadcom Limited                | 5         | 2.05%   |
| D-Link                          | 3         | 1.23%   |
| MEDIATEK                        | 2         | 0.82%   |
| TP-Link                         | 1         | 0.41%   |
| Philips (or NXP)                | 1         | 0.41%   |
| Fujitsu Siemens Computers       | 1         | 0.41%   |
| Edimax Technology               | 1         | 0.41%   |
| Accton Technology               | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 17        | 6.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 16        | 6.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 15        | 6.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 14        | 5.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 10        | 4.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 3.69%   |
| Intel Wireless 8265 / 8275                                                            | 9         | 3.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 8         | 3.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 8         | 3.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 6         | 2.46%   |
| Intel Wi-Fi 6 AX201                                                                   | 6         | 2.46%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 5         | 2.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 5         | 2.05%   |
| Intel Centrino Wireless-N 2230                                                        | 5         | 2.05%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 4         | 1.64%   |
| Ralink RT5370 Wireless Adapter                                                        | 4         | 1.64%   |
| Intel Wireless 3160                                                                   | 4         | 1.64%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 4         | 1.64%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 4         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 4         | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 4         | 1.64%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                           | 4         | 1.64%   |
| Broadcom BCM43227 802.11b/g/n                                                         | 4         | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 3         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 1.23%   |
| Intel WiFi Link 5100                                                                  | 3         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 3         | 1.23%   |
| Ralink MT7601U Wireless Adapter                                                       | 2         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 0.82%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 2         | 0.82%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                         | 2         | 0.82%   |
| Intel Wireless 7265                                                                   | 2         | 0.82%   |
| Intel Wireless 7260                                                                   | 2         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 2         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 0.82%   |
| Intel Centrino Wireless-N 100                                                         | 2         | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 0.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 0.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.41%   |
| Realtek RTL8187 Wireless Adapter                                                      | 1         | 0.41%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1         | 0.41%   |
| Realtek 802.11ac NIC                                                                  | 1         | 0.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 1         | 0.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.41%   |
| Qualcomm Atheros AR5523                                                               | 1         | 0.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.41%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.41%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 1         | 0.41%   |
| Philips (or NXP) PTA-128                                                              | 1         | 0.41%   |
| Intel Wireless 8260                                                                   | 1         | 0.41%   |
| Intel Wireless 3165                                                                   | 1         | 0.41%   |
| Intel WiMAX/WiFi Link 5150                                                            | 1         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 233       | 63.32%  |
| Intel                    | 48        | 13.04%  |
| Qualcomm Atheros         | 35        | 9.51%   |
| Broadcom Limited         | 9         | 2.45%   |
| Broadcom                 | 8         | 2.17%   |
| Marvell Technology Group | 7         | 1.9%    |
| Nvidia                   | 6         | 1.63%   |
| Huawei Technologies      | 6         | 1.63%   |
| VIA Technologies         | 4         | 1.09%   |
| Xiaomi                   | 3         | 0.82%   |
| JMicron Technology       | 3         | 0.82%   |
| Samsung Electronics      | 2         | 0.54%   |
| HTC (High Tech Computer) | 2         | 0.54%   |
| MediaTek                 | 1         | 0.27%   |
| Android                  | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 163       | 43.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 55        | 14.71%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 9         | 2.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 8         | 2.14%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 1.87%   |
| Intel Ethernet Connection (2) I219-V                                           | 7         | 1.87%   |
| Huawei E353/E3131                                                              | 6         | 1.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 5         | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 1.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 4         | 1.07%   |
| Intel 82579V Gigabit Network Connection                                        | 4         | 1.07%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 1.07%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 0.8%    |
| Intel 82573L Gigabit Ethernet Controller                                       | 3         | 0.8%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 3         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.53%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 2         | 0.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 2         | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.53%   |
| Nvidia CK804 Ethernet Controller                                               | 2         | 0.53%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.53%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.53%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.53%   |
| Intel 82566DC Gigabit Network Connection                                       | 2         | 0.53%   |
| HTC (High Tech Computer) MT65xx Android Phone                                  | 2         | 0.53%   |
| Broadcom Limited NetXtreme II BCM5708 Gigabit Ethernet                         | 2         | 0.53%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.27%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.27%   |
| Realtek RTL-8129                                                               | 1         | 0.27%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.27%   |
| Realtek RTL-8029(AS)                                                           | 1         | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.27%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.27%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.27%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.27%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.27%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.27%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.27%   |
| MediaTek NOA N2                                                                | 1         | 0.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.27%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.27%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.27%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 0.27%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.27%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.27%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.27%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 348       | 58.59%  |
| WiFi     | 239       | 40.24%  |
| Modem    | 7         | 1.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 212       | 51.21%  |
| WiFi     | 202       | 48.79%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 205       | 55.11%  |
| 1     | 160       | 43.01%  |
| 0     | 4         | 1.08%   |
| 4     | 3         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 372       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 30.95%  |
| Qualcomm Atheros Communications | 17        | 10.12%  |
| IMC Networks                    | 16        | 9.52%   |
| Realtek Semiconductor           | 15        | 8.93%   |
| Lite-On Technology              | 14        | 8.33%   |
| Broadcom                        | 14        | 8.33%   |
| Ralink                          | 8         | 4.76%   |
| Hewlett-Packard                 | 7         | 4.17%   |
| Toshiba                         | 5         | 2.98%   |
| Foxconn / Hon Hai               | 5         | 2.98%   |
| Cambridge Silicon Radio         | 5         | 2.98%   |
| Foxconn International           | 3         | 1.79%   |
| Integrated System Solution      | 2         | 1.19%   |
| ASUSTek Computer                | 2         | 1.19%   |
| Ralink Technology               | 1         | 0.6%    |
| Logitech                        | 1         | 0.6%    |
| Askey Computer                  | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 12.5%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 5.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 5.95%   |
| Realtek Bluetooth Radio                             | 9         | 5.36%   |
| Ralink RT3290 Bluetooth                             | 8         | 4.76%   |
| Intel AX201 Bluetooth                               | 8         | 4.76%   |
| IMC Networks Bluetooth Radio                        | 7         | 4.17%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 3.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 2.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 2.98%   |
| Broadcom HP Portable Valentine                      | 5         | 2.98%   |
| Realtek 802.11n WLAN Adapter                        | 4         | 2.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.38%   |
| Intel AX200 Bluetooth                               | 4         | 2.38%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.79%   |
| Intel Bluetooth Device                              | 3         | 1.79%   |
| IMC Networks Bluetooth Device                       | 3         | 1.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 1.79%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.79%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 1.19%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 1.19%   |
| Lite-On Bluetooth Device                            | 2         | 1.19%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.19%   |
| Integrated System Solution Bluetooth Device         | 2         | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.19%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.19%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.19%   |
| Broadcom BCM20702A0                                 | 2         | 1.19%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.19%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.6%    |
| Toshiba Integrated Bluetooth                        | 1         | 0.6%    |
| Toshiba Askey Bluetooth Module                      | 1         | 0.6%    |
| Realtek RTL8821A Bluetooth                          | 1         | 0.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.6%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.6%    |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.6%    |
| IMC Networks Wireless_Device                        | 1         | 0.6%    |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.6%    |
| IMC Networks Bluetooth module                       | 1         | 0.6%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.6%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.6%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.6%    |
| Askey Bluetooth Device                              | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 307       | 61.9%   |
| Nvidia                 | 101       | 20.36%  |
| AMD                    | 65        | 13.1%   |
| C-Media Electronics    | 5         | 1.01%   |
| VIA Technologies       | 2         | 0.4%    |
| Focusrite-Novation     | 2         | 0.4%    |
| Creative Labs          | 2         | 0.4%    |
| Xilinx                 | 1         | 0.2%    |
| ULi Electronics        | 1         | 0.2%    |
| Sony                   | 1         | 0.2%    |
| Plantronics            | 1         | 0.2%    |
| Pixart Imaging         | 1         | 0.2%    |
| Logitech               | 1         | 0.2%    |
| JMTek                  | 1         | 0.2%    |
| Huawei Technologies    | 1         | 0.2%    |
| Hewlett-Packard        | 1         | 0.2%    |
| GYROCOM C&C            | 1         | 0.2%    |
| Generalplus Technology | 1         | 0.2%    |
| ELMCU                  | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 43        | 7.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 42        | 7.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 42        | 7.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 4.92%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 23        | 4.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 3.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 2.91%   |
| Nvidia High Definition Audio Controller                                                           | 14        | 2.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 14        | 2.55%   |
| AMD FCH Azalia Controller                                                                         | 14        | 2.55%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 1.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 1.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 1.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 1.46%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 1.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.09%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.91%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.91%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 5         | 0.91%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.91%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 5         | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.55%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3         | 0.55%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.55%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 3         | 0.55%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.55%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 3         | 0.55%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.55%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.36%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.36%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 2         | 0.36%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 2         | 0.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.36%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.36%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.36%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Unknown              | 109       | 30.45%  |
| SK Hynix             | 50        | 13.97%  |
| Samsung Electronics  | 46        | 12.85%  |
| Kingston             | 33        | 9.22%   |
| Micron Technology    | 18        | 5.03%   |
| Transcend            | 15        | 4.19%   |
| A-DATA Technology    | 12        | 3.35%   |
| Ramaxel Technology   | 8         | 2.23%   |
| Crucial              | 8         | 2.23%   |
| Silicon Power        | 6         | 1.68%   |
| GeIL                 | 6         | 1.68%   |
| Apacer               | 6         | 1.68%   |
| Nanya Technology     | 5         | 1.4%    |
| Team                 | 4         | 1.12%   |
| Patriot              | 3         | 0.84%   |
| G.Skill              | 3         | 0.84%   |
| Elpida               | 3         | 0.84%   |
| Super Talent         | 2         | 0.56%   |
| SUPER KINGSTEK       | 2         | 0.56%   |
| Qimonda              | 2         | 0.56%   |
| HPE                  | 2         | 0.56%   |
| GOODRAM              | 2         | 0.56%   |
| ASint Technology     | 2         | 0.56%   |
| V-Color              | 1         | 0.28%   |
| Unknown (ABCD)       | 1         | 0.28%   |
| Toshiba              | 1         | 0.28%   |
| SHARETRONIC          | 1         | 0.28%   |
| Qumo                 | 1         | 0.28%   |
| ProMos/Mosel Vitelic | 1         | 0.28%   |
| Kllisre              | 1         | 0.28%   |
| Kingmax              | 1         | 0.28%   |
| KANMEIQi             | 1         | 0.28%   |
| Goldkey              | 1         | 0.28%   |
| Corsair              | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 12        | 3.05%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 10        | 2.54%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 7         | 1.78%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 7         | 1.78%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 5         | 1.27%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 5         | 1.27%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s | 5         | 1.27%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 4         | 1.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 4         | 1.02%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s   | 4         | 1.02%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 4         | 1.02%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 3         | 0.76%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 3         | 0.76%   |
| Transcend RAM JM1333KLU-2G 2GB DIMM DDR3 1333MT/s         | 3         | 0.76%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 0.76%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 0.76%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s    | 3         | 0.76%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 3         | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.76%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s    | 3         | 0.76%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 2         | 0.51%   |
| Unknown RAM Module 4096MB FB-DIMM DDR2 667MT/s            | 2         | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s              | 2         | 0.51%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 2         | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 2         | 0.51%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 2         | 0.51%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s              | 2         | 0.51%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 2         | 0.51%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                | 2         | 0.51%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s               | 2         | 0.51%   |
| Unknown RAM Module 2048MB DIMM 5354MT/s                   | 2         | 0.51%   |
| Unknown RAM Module 1024MB SODIMM DDR                      | 2         | 0.51%   |
| Unknown RAM Module 1024MB DIMM DDR2                       | 2         | 0.51%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s         | 2         | 0.51%   |
| Super Talent RAM SUPERTALENT02 2048MB DIMM DDR3 1600MT/s  | 2         | 0.51%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1024MB SODIMM DDR 667MT/s   | 2         | 0.51%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.51%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.51%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.51%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 0.51%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s | 2         | 0.51%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s | 2         | 0.51%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.51%   |
| Silicon Power RAM DBLT2GN568S 2048MB DIMM DDR3 1333MT/s   | 2         | 0.51%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.51%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.51%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s   | 2         | 0.51%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s  | 2         | 0.51%   |
| GeIL RAM CL9-9-9 D3-1333 8GB DIMM DDR3 1333MT/s           | 2         | 0.51%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s     | 2         | 0.51%   |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s               | 2         | 0.51%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s         | 2         | 0.51%   |
| V-Color RAM TN416G24D817 16384MB SODIMM DDR4 2400MT/s     | 1         | 0.25%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 147       | 49.16%  |
| DDR4    | 52        | 17.39%  |
| Unknown | 32        | 10.7%   |
| DDR2    | 30        | 10.03%  |
| SDRAM   | 28        | 9.36%   |
| DDR     | 7         | 2.34%   |
| LPDDR4  | 2         | 0.67%   |
| LPDDR3  | 1         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 147       | 49.49%  |
| DIMM         | 143       | 48.15%  |
| Row Of Chips | 4         | 1.35%   |
| FB-DIMM      | 3         | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 120       | 33.52%  |
| 2048  | 107       | 29.89%  |
| 8192  | 60        | 16.76%  |
| 1024  | 49        | 13.69%  |
| 16384 | 12        | 3.35%   |
| 512   | 6         | 1.68%   |
| 32768 | 3         | 0.84%   |
| 256   | 1         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 87        | 25.66%  |
| 1333    | 50        | 14.75%  |
| Unknown | 37        | 10.91%  |
| 1334    | 23        | 6.78%   |
| 800     | 21        | 6.19%   |
| 2667    | 20        | 5.9%    |
| 667     | 19        | 5.6%    |
| 2400    | 16        | 4.72%   |
| 3200    | 11        | 3.24%   |
| 1067    | 7         | 2.06%   |
| 2133    | 6         | 1.77%   |
| 533     | 6         | 1.77%   |
| 1066    | 5         | 1.47%   |
| 2666    | 4         | 1.18%   |
| 2048    | 3         | 0.88%   |
| 400     | 3         | 0.88%   |
| 5354    | 2         | 0.59%   |
| 3266    | 2         | 0.59%   |
| 975     | 2         | 0.59%   |
| 8400    | 1         | 0.29%   |
| 4267    | 1         | 0.29%   |
| 4199    | 1         | 0.29%   |
| 3800    | 1         | 0.29%   |
| 3733    | 1         | 0.29%   |
| 3334    | 1         | 0.29%   |
| 3000    | 1         | 0.29%   |
| 2020    | 1         | 0.29%   |
| 1867    | 1         | 0.29%   |
| 1800    | 1         | 0.29%   |
| 1666    | 1         | 0.29%   |
| 1400    | 1         | 0.29%   |
| 1258    | 1         | 0.29%   |
| 666     | 1         | 0.29%   |
| 66      | 1         | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 6         | 35.29%  |
| Samsung Electronics    | 4         | 23.53%  |
| Xerox                  | 3         | 17.65%  |
| Canon                  | 2         | 11.76%  |
| Seiko Epson            | 1         | 5.88%   |
| Panasonic (Matsushita) | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP LaserJet 1018                        | 2         | 11.76%  |
| Xerox WorkCentre 6015B                  | 1         | 5.88%   |
| Xerox Phaser 3160                       | 1         | 5.88%   |
| Xerox Phaser 3020                       | 1         | 5.88%   |
| Seiko Epson L805 Series                 | 1         | 5.88%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 5.88%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 5.88%   |
| Samsung M2020 Series                    | 1         | 5.88%   |
| Samsung CLX-3180 Series                 | 1         | 5.88%   |
| Panasonic (Matsushita) KX-MB1500CX      | 1         | 5.88%   |
| HP LaserJet P1102                       | 1         | 5.88%   |
| HP LaserJet 1020                        | 1         | 5.88%   |
| HP LaserJet 1010                        | 1         | 5.88%   |
| HP Deskjet 2520 series                  | 1         | 5.88%   |
| Canon LBP810                            | 1         | 5.88%   |
| Canon LBP6000                           | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model          | Computers | Percent |
|----------------|-----------|---------|
| HP Scanjet 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 45        | 20.36%  |
| IMC Networks                           | 23        | 10.41%  |
| Quanta                                 | 21        | 9.5%    |
| Realtek Semiconductor                  | 18        | 8.14%   |
| Z-Star Microelectronics                | 11        | 4.98%   |
| Suyin                                  | 11        | 4.98%   |
| Microdia                               | 10        | 4.52%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.52%   |
| Acer                                   | 10        | 4.52%   |
| Sunplus Innovation Technology          | 9         | 4.07%   |
| KYE Systems (Mouse Systems)            | 8         | 3.62%   |
| Logitech                               | 7         | 3.17%   |
| Syntek                                 | 3         | 1.36%   |
| SiGma Micro                            | 3         | 1.36%   |
| Samsung Electronics                    | 3         | 1.36%   |
| Pixart Imaging                         | 3         | 1.36%   |
| Lite-On Technology                     | 3         | 1.36%   |
| Alcor Micro                            | 3         | 1.36%   |
| Silicon Motion                         | 2         | 0.9%    |
| Ricoh                                  | 2         | 0.9%    |
| Primax Electronics                     | 2         | 0.9%    |
| Hewlett-Packard                        | 2         | 0.9%    |
| GEMBIRD                                | 2         | 0.9%    |
| ALi                                    | 2         | 0.9%    |
| Nebraska Furniture Mart                | 1         | 0.45%   |
| Luxvisions Innotech Limited            | 1         | 0.45%   |
| Lenovo                                 | 1         | 0.45%   |
| Jieli Technology                       | 1         | 0.45%   |
| Importek                               | 1         | 0.45%   |
| Generalplus Technology                 | 1         | 0.45%   |
| Aveo Technology                        | 1         | 0.45%   |
| Apple                                  | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                      | 10        | 4.5%    |
| Z-Star Venus USB2.0 Camera                              | 6         | 2.7%    |
| Quanta HD Webcam                                        | 5         | 2.25%   |
| Quanta VGA WebCam                                       | 4         | 1.8%    |
| Quanta HD User Facing                                   | 4         | 1.8%    |
| Chicony Integrated Camera (1280x720@30)                 | 4         | 1.8%    |
| Chicony HD WebCam                                       | 4         | 1.8%    |
| Chicony Fujitsu Integrated Camera                       | 4         | 1.8%    |
| Suyin HP Truevision HD                                  | 3         | 1.35%   |
| Suyin 1.3M HD WebCam                                    | 3         | 1.35%   |
| Sunplus HD Webcam                                       | 3         | 1.35%   |
| SiGma Micro WebCam SiGma Micro                          | 3         | 1.35%   |
| Samsung Galaxy A5 (MTP)                                 | 3         | 1.35%   |
| Realtek Lenovo EasyCamera                               | 3         | 1.35%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 3         | 1.35%   |
| KYE Systems (Mouse Systems) Genius iSlim 330            | 3         | 1.35%   |
| IMC Networks Integrated Camera                          | 3         | 1.35%   |
| Chicony USB2.0 0.3M UVC WebCam                          | 3         | 1.35%   |
| Chicony HP Truevision HD                                | 3         | 1.35%   |
| Acer Lenovo Integrated Webcam                           | 3         | 1.35%   |
| Syntek Lenovo EasyCamera                                | 2         | 0.9%    |
| Suyin Integrated_Webcam_HD                              | 2         | 0.9%    |
| Sunplus Dell HD Webcam                                  | 2         | 0.9%    |
| Realtek USB Camera                                      | 2         | 0.9%    |
| Realtek Integrated Webcam                               | 2         | 0.9%    |
| Realtek HP Truevision HD                                | 2         | 0.9%    |
| Realtek Acer 640 x 480 laptop camera                    | 2         | 0.9%    |
| Quanta HP Webcam                                        | 2         | 0.9%    |
| Microdia Sonix USB 2.0 Camera                           | 2         | 0.9%    |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.9%    |
| Microdia Integrated_Webcam_HD                           | 2         | 0.9%    |
| Logitech Webcam C270                                    | 2         | 0.9%    |
| Logitech Webcam C170                                    | 2         | 0.9%    |
| Lite-On Integrated Camera                               | 2         | 0.9%    |
| IMC Networks USB2.0 UVC HD Webcam                       | 2         | 0.9%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 2         | 0.9%    |
| IMC Networks Lenovo EasyCamera                          | 2         | 0.9%    |
| GEMBIRD USB2.0 PC CAMERA                                | 2         | 0.9%    |
| Chicony VGA WebCam                                      | 2         | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 0.9%    |
| Chicony USB2.0 HD UVC WebCam                            | 2         | 0.9%    |
| Chicony Lenovo EasyCamera                               | 2         | 0.9%    |
| Chicony Integrated Camera                               | 2         | 0.9%    |
| Chicony EasyCamera                                      | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 2         | 0.9%    |
| Acer Lenovo EasyCamera                                  | 2         | 0.9%    |
| Z-Star WebCam SC-03FFL11739P                            | 1         | 0.45%   |
| Z-Star Vimicro USB Camera (Altair)                      | 1         | 0.45%   |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.45%   |
| Z-Star Lenovo USB2.0 UVC Camera                         | 1         | 0.45%   |
| Z-Star Lenovo IdeaCentre Web Camera                     | 1         | 0.45%   |
| Syntek Integrated Camera                                | 1         | 0.45%   |
| Suyin HP Webcam                                         | 1         | 0.45%   |
| Suyin HP TrueVision HD Integrated Webcam                | 1         | 0.45%   |
| Suyin HD WebCam                                         | 1         | 0.45%   |
| Sunplus Integrated Webcam                               | 1         | 0.45%   |
| Sunplus HP Universal Camera                             | 1         | 0.45%   |
| Sunplus ASUS Webcam                                     | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 27.27%  |
| Synaptics                  | 7         | 21.21%  |
| Upek                       | 5         | 15.15%  |
| AuthenTec                  | 5         | 15.15%  |
| STMicroelectronics         | 3         | 9.09%   |
| Shenzhen Goodix Technology | 3         | 9.09%   |
| Elan Microelectronics      | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 5         | 15.15%  |
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 9.09%   |
| STMicroelectronics Fingerprint Reader                     | 3         | 9.09%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 3         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 2         | 6.06%   |
| Validity Sensors Fingerprint scanner                      | 2         | 6.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 6.06%   |
| AuthenTec AES2810                                         | 2         | 6.06%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 3.03%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 3.03%   |
| Synaptics  WBDI                                           | 1         | 3.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 3.03%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 3.03%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 3.03%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 3.03%   |
| Shenzhen Goodix FingerPrint                               | 1         | 3.03%   |
| Elan ELAN:Fingerprint                                     | 1         | 3.03%   |
| Unknown                                                   | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 2         | 50%     |
| Aktiv                 | 1         | 25%     |
| Advanced Card Systems | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader          | 2         | 50%     |
| Aktiv KAZTOKEN                               | 1         | 25%     |
| Advanced Card Systems ACR38 SmartCard Reader | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 296       | 77.28%  |
| 1     | 71        | 18.54%  |
| 2     | 11        | 2.87%   |
| 3     | 4         | 1.04%   |
| 4     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 33%     |
| Graphics card            | 27        | 27%     |
| Net/wireless             | 11        | 11%     |
| Bluetooth                | 9         | 9%      |
| Communication controller | 8         | 8%      |
| Unassigned class         | 3         | 3%      |
| Multimedia controller    | 3         | 3%      |
| Camera                   | 3         | 3%      |
| Chipcard                 | 2         | 2%      |
| Card reader              | 1         | 1%      |

