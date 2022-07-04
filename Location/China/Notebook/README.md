Linux in China - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in China.

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

Total: 742

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [4b2106c800](https://linux-hardware.org/?probe=4b2106c800) | Jun 29, 2022 |
| Intel Clie... | LAPKC71F                    | [1a50f7c080](https://linux-hardware.org/?probe=1a50f7c080) | Jun 27, 2022 |
| Dell          | Precision 3541              | [816c91b81b](https://linux-hardware.org/?probe=816c91b81b) | Jun 25, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eaf51fc79f](https://linux-hardware.org/?probe=eaf51fc79f) | Jun 24, 2022 |
| IPASON        | SMN86A                      | [834382148b](https://linux-hardware.org/?probe=834382148b) | Jun 21, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [8b520f803c](https://linux-hardware.org/?probe=8b520f803c) | Jun 21, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [385b65c320](https://linux-hardware.org/?probe=385b65c320) | Jun 19, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [fb120ddb6d](https://linux-hardware.org/?probe=fb120ddb6d) | Jun 19, 2022 |
| HUAWEI        | KPR-WX9                     | [4c08060155](https://linux-hardware.org/?probe=4c08060155) | Jun 18, 2022 |
| ASUSTek       | S550CM                      | [43ddcf21fb](https://linux-hardware.org/?probe=43ddcf21fb) | Jun 17, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [8d56f09226](https://linux-hardware.org/?probe=8d56f09226) | Jun 17, 2022 |
| HP            | EliteBook 2170p             | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| Clevo         | P7xxTM(1)                   | [48afb16c13](https://linux-hardware.org/?probe=48afb16c13) | Jun 16, 2022 |
| Timi          | TM1701                      | [e57d1ac956](https://linux-hardware.org/?probe=e57d1ac956) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Timi          | A7S                         | [a43809f0a8](https://linux-hardware.org/?probe=a43809f0a8) | Jun 12, 2022 |
| Acer          | Aspire T5000                | [38e164657d](https://linux-hardware.org/?probe=38e164657d) | Jun 11, 2022 |
| HP            | OMEN by Laptop              | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [96dfe73713](https://linux-hardware.org/?probe=96dfe73713) | Jun 07, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [6d46a6107c](https://linux-hardware.org/?probe=6d46a6107c) | Jun 06, 2022 |
| Acer          | Nitro AN515-57              | [ecef8fb98e](https://linux-hardware.org/?probe=ecef8fb98e) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [5f55de3d8e](https://linux-hardware.org/?probe=5f55de3d8e) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [db08be8e6c](https://linux-hardware.org/?probe=db08be8e6c) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [818930c012](https://linux-hardware.org/?probe=818930c012) | Jun 04, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [ee8d9751b0](https://linux-hardware.org/?probe=ee8d9751b0) | Jun 01, 2022 |
| Acer          | Aspire T5000                | [55aaebdab5](https://linux-hardware.org/?probe=55aaebdab5) | May 31, 2022 |
| HP            | ProBook 455 15.6 inch G9... | [d4698d909e](https://linux-hardware.org/?probe=d4698d909e) | May 31, 2022 |
| Acer          | Aspire T5000                | [7bdeb5fb3b](https://linux-hardware.org/?probe=7bdeb5fb3b) | May 31, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [3d58c27cd7](https://linux-hardware.org/?probe=3d58c27cd7) | May 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5e77f9d2f9](https://linux-hardware.org/?probe=5e77f9d2f9) | May 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [114a036605](https://linux-hardware.org/?probe=114a036605) | May 28, 2022 |
| Apple         | MacBookPro15,2              | [c0fe1740e0](https://linux-hardware.org/?probe=c0fe1740e0) | May 25, 2022 |
| Dell          | Latitude 5300               | [b2e8f91f15](https://linux-hardware.org/?probe=b2e8f91f15) | May 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [f2c3a907b7](https://linux-hardware.org/?probe=f2c3a907b7) | May 24, 2022 |
| Dell          | Latitude 3490               | [36a2ce11ef](https://linux-hardware.org/?probe=36a2ce11ef) | May 22, 2022 |
| Google        | Atlas                       | [d9406ed20d](https://linux-hardware.org/?probe=d9406ed20d) | May 21, 2022 |
| Apple         | MacBookPro16,1              | [a60048a58a](https://linux-hardware.org/?probe=a60048a58a) | May 19, 2022 |
| Lenovo        | IdeaPad U430p 20269         | [bcf848458f](https://linux-hardware.org/?probe=bcf848458f) | May 18, 2022 |
| Apple         | MacBookPro16,1              | [e5c6c46d14](https://linux-hardware.org/?probe=e5c6c46d14) | May 18, 2022 |
| MECHREVO      | X10Ti-S Series GM7MPHS      | [3af043f369](https://linux-hardware.org/?probe=3af043f369) | May 17, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [2b7a0725f0](https://linux-hardware.org/?probe=2b7a0725f0) | May 14, 2022 |
| Lenovo        | ThinkPad S2 5th Gen 20R7... | [a4ba7cbcfa](https://linux-hardware.org/?probe=a4ba7cbcfa) | May 13, 2022 |
| Google        | Atlas                       | [ae85df2f65](https://linux-hardware.org/?probe=ae85df2f65) | May 12, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [b0db2e2b60](https://linux-hardware.org/?probe=b0db2e2b60) | May 11, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [f62715aee5](https://linux-hardware.org/?probe=f62715aee5) | May 11, 2022 |
| Clevo         | P7xxTM(1)                   | [fdebb20557](https://linux-hardware.org/?probe=fdebb20557) | May 10, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | [428f653301](https://linux-hardware.org/?probe=428f653301) | May 05, 2022 |
| Timi          | Redmi G                     | [a2738a4d6e](https://linux-hardware.org/?probe=a2738a4d6e) | May 05, 2022 |
| Dell          | Latitude 7420               | [7fd2239abb](https://linux-hardware.org/?probe=7fd2239abb) | May 05, 2022 |
| Google        | Atlas                       | [dce87f3691](https://linux-hardware.org/?probe=dce87f3691) | May 05, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | [6103e540b9](https://linux-hardware.org/?probe=6103e540b9) | May 04, 2022 |
| Dell          | Latitude 5300               | [fa0246b764](https://linux-hardware.org/?probe=fa0246b764) | May 04, 2022 |
| Dell          | Precision 3541              | [feaee0b7ff](https://linux-hardware.org/?probe=feaee0b7ff) | May 04, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [b812cd9eb1](https://linux-hardware.org/?probe=b812cd9eb1) | May 04, 2022 |
| Lenovo        | IdeaPad Y470 20090          | [690c12e995](https://linux-hardware.org/?probe=690c12e995) | May 03, 2022 |
| HP            | G42                         | [6ee2b19fc7](https://linux-hardware.org/?probe=6ee2b19fc7) | May 01, 2022 |
| HP            | G42                         | [731ba8d968](https://linux-hardware.org/?probe=731ba8d968) | May 01, 2022 |
| HP            | G42                         | [e23740df6e](https://linux-hardware.org/?probe=e23740df6e) | Apr 30, 2022 |
| HP            | G42                         | [f6ca4559f5](https://linux-hardware.org/?probe=f6ca4559f5) | Apr 30, 2022 |
| Dell          | Inspiron 7400               | [0c0af6919d](https://linux-hardware.org/?probe=0c0af6919d) | Apr 29, 2022 |
| Dell          | Inspiron 7400               | [8e5289a5e7](https://linux-hardware.org/?probe=8e5289a5e7) | Apr 28, 2022 |
| HUAWEI        | NBM-WXX9                    | [4f15ab06cc](https://linux-hardware.org/?probe=4f15ab06cc) | Apr 28, 2022 |
| Lenovo        | AILZx                       | [efa15d667f](https://linux-hardware.org/?probe=efa15d667f) | Apr 26, 2022 |
| Timi          | RedmiBook Pro 15S           | [07ccc93cd4](https://linux-hardware.org/?probe=07ccc93cd4) | Apr 25, 2022 |
| Timi          | TM1612                      | [9e6b6f4737](https://linux-hardware.org/?probe=9e6b6f4737) | Apr 24, 2022 |
| GreatWall     | TN140A2                     | [69043361cf](https://linux-hardware.org/?probe=69043361cf) | Apr 24, 2022 |
| Dell          | Latitude 5290               | [e373cb6fa1](https://linux-hardware.org/?probe=e373cb6fa1) | Apr 23, 2022 |
| Lenovo        | Legion Y7000 81FW           | [c56c469d4f](https://linux-hardware.org/?probe=c56c469d4f) | Apr 21, 2022 |
| Acer          | Swift SF314-512             | [d7e77fd856](https://linux-hardware.org/?probe=d7e77fd856) | Apr 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5f78518f42](https://linux-hardware.org/?probe=5f78518f42) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3faf048414](https://linux-hardware.org/?probe=3faf048414) | Apr 18, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| Apple         | MacBookPro12,1              | [3c5f232016](https://linux-hardware.org/?probe=3c5f232016) | Apr 17, 2022 |
| Timi          | RedmiBook Pro 15S           | [e29970db9c](https://linux-hardware.org/?probe=e29970db9c) | Apr 16, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [7e346154a5](https://linux-hardware.org/?probe=7e346154a5) | Apr 16, 2022 |
| Timi          | A34                         | [ff24fc7e19](https://linux-hardware.org/?probe=ff24fc7e19) | Apr 15, 2022 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [2394088db1](https://linux-hardware.org/?probe=2394088db1) | Apr 14, 2022 |
| HONOR         | NBD-WXX9                    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a86b688768](https://linux-hardware.org/?probe=a86b688768) | Apr 11, 2022 |
| Lenovo        | XiaoXin Air 13IML 81WV      | [c5ae7c810d](https://linux-hardware.org/?probe=c5ae7c810d) | Apr 09, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [e8e6eefea7](https://linux-hardware.org/?probe=e8e6eefea7) | Apr 09, 2022 |
| HP            | OMEN by Laptop 17-ck1xxx    | [10654de5c8](https://linux-hardware.org/?probe=10654de5c8) | Apr 08, 2022 |
| HP            | OMEN by Laptop 17-ck1xxx    | [60cd34cb85](https://linux-hardware.org/?probe=60cd34cb85) | Apr 07, 2022 |
| Lenovo        | ThinkPad S2 5th Gen 20R7... | [4e1cbba139](https://linux-hardware.org/?probe=4e1cbba139) | Apr 07, 2022 |
| Timi          | TM1701                      | [e2930f3884](https://linux-hardware.org/?probe=e2930f3884) | Apr 06, 2022 |
| IPASON        | MaxBook P1                  | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| Lenovo        | ThinkPad L470 20J5A240CD    | [2c7d1c1f02](https://linux-hardware.org/?probe=2c7d1c1f02) | Apr 04, 2022 |
| Timi          | RedmiBook Pro 15S           | [9c1fd6c304](https://linux-hardware.org/?probe=9c1fd6c304) | Apr 04, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [f1f8a33de1](https://linux-hardware.org/?probe=f1f8a33de1) | Apr 03, 2022 |
| Gigabyte      | P65                         | [28a10c32cf](https://linux-hardware.org/?probe=28a10c32cf) | Apr 02, 2022 |
| MECHREVO      | X10 Pro Series GM7TG8S      | [eceb9b69ed](https://linux-hardware.org/?probe=eceb9b69ed) | Apr 01, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [802940c8ef](https://linux-hardware.org/?probe=802940c8ef) | Mar 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [51f7153768](https://linux-hardware.org/?probe=51f7153768) | Mar 30, 2022 |
| Gigabyte      | AERO 15WV8                  | [8fdae867c0](https://linux-hardware.org/?probe=8fdae867c0) | Mar 30, 2022 |
| Unknown       | X133                        | [996dfaa50f](https://linux-hardware.org/?probe=996dfaa50f) | Mar 28, 2022 |
| Lenovo        | ThinkPad R400 2784A48       | [f760bbcc2f](https://linux-hardware.org/?probe=f760bbcc2f) | Mar 27, 2022 |
| Lenovo        | ThinkPad R400 2784A48       | [b7093f8912](https://linux-hardware.org/?probe=b7093f8912) | Mar 27, 2022 |
| Acer          | Swift SF314-510G            | [a105ea5158](https://linux-hardware.org/?probe=a105ea5158) | Mar 27, 2022 |
| Lenovo        | ThinkPad A485 20MU0007CD    | [1e231d6b08](https://linux-hardware.org/?probe=1e231d6b08) | Mar 26, 2022 |
| Timi          | A7S                         | [c39211692e](https://linux-hardware.org/?probe=c39211692e) | Mar 25, 2022 |
| Timi          | Mi Laptop Pro 15            | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4A... | [a257719dcf](https://linux-hardware.org/?probe=a257719dcf) | Mar 23, 2022 |
| HUAWEI        | FRD-WX9                     | [e027a60ac6](https://linux-hardware.org/?probe=e027a60ac6) | Mar 23, 2022 |
| IBM           | Unknown                     | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [c99fae499f](https://linux-hardware.org/?probe=c99fae499f) | Mar 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [ee813d0051](https://linux-hardware.org/?probe=ee813d0051) | Mar 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [6adea9d280](https://linux-hardware.org/?probe=6adea9d280) | Mar 19, 2022 |
| Timi          | RedmiBook Pro 15S           | [c06992ac2b](https://linux-hardware.org/?probe=c06992ac2b) | Mar 18, 2022 |
| Notebook      | NH5xAx                      | [cddad9e5c8](https://linux-hardware.org/?probe=cddad9e5c8) | Mar 17, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | [7e92a522e9](https://linux-hardware.org/?probe=7e92a522e9) | Mar 16, 2022 |
| Dell          | Vostro 3401                 | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | [70a5dc4f94](https://linux-hardware.org/?probe=70a5dc4f94) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | [8fdeae3b33](https://linux-hardware.org/?probe=8fdeae3b33) | Mar 12, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | [9c61029e1f](https://linux-hardware.org/?probe=9c61029e1f) | Mar 11, 2022 |
| Lenovo        | G580 20150                  | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Samsung       | 500R5L/501R5L/500R5P/550... | [8d792e6db0](https://linux-hardware.org/?probe=8d792e6db0) | Mar 09, 2022 |
| Timi          | RedmiBook Air 13            | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Toshiba       | Satellite C850-C008         | [d18b844729](https://linux-hardware.org/?probe=d18b844729) | Mar 07, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [e1da80ec6f](https://linux-hardware.org/?probe=e1da80ec6f) | Mar 05, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c697a91a8e](https://linux-hardware.org/?probe=c697a91a8e) | Mar 02, 2022 |
| Dell          | Latitude 7285               | [8d3fe46d72](https://linux-hardware.org/?probe=8d3fe46d72) | Mar 01, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [f2fb3da876](https://linux-hardware.org/?probe=f2fb3da876) | Mar 01, 2022 |
| Shanghai Z... | ZXE CRB                     | [7fe4a3390b](https://linux-hardware.org/?probe=7fe4a3390b) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | TM1709                      | [16e699bea8](https://linux-hardware.org/?probe=16e699bea8) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| LG Electro... | 16Z90P-G.AA56C              | [f4b91cfb92](https://linux-hardware.org/?probe=f4b91cfb92) | Feb 22, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [215889b22b](https://linux-hardware.org/?probe=215889b22b) | Feb 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [b91f497b74](https://linux-hardware.org/?probe=b91f497b74) | Feb 19, 2022 |
| Lenovo        | XiaoXinPro 14IHU 2021 82... | [d994752dc6](https://linux-hardware.org/?probe=d994752dc6) | Feb 15, 2022 |
| MSI           | WT72 2OM                    | [e266645b4a](https://linux-hardware.org/?probe=e266645b4a) | Feb 14, 2022 |
| Dell          | System Inspiron N4110       | [695b7bb3dd](https://linux-hardware.org/?probe=695b7bb3dd) | Feb 14, 2022 |
| Unknown       | Unknown                     | [fa14786b94](https://linux-hardware.org/?probe=fa14786b94) | Feb 13, 2022 |
| Acer          | Swift SF314-510G            | [6c4dbc81d8](https://linux-hardware.org/?probe=6c4dbc81d8) | Feb 12, 2022 |
| Dell          | Inspiron 7472               | [62bdd11635](https://linux-hardware.org/?probe=62bdd11635) | Feb 11, 2022 |
| Dell          | G7 7500                     | [61f4625e4c](https://linux-hardware.org/?probe=61f4625e4c) | Feb 11, 2022 |
| Lenovo        | ThinkPad T61p 64608VU       | [73fddf3dcc](https://linux-hardware.org/?probe=73fddf3dcc) | Feb 10, 2022 |
| Lenovo        | ThinkPad X230 2324A14       | [502457cef5](https://linux-hardware.org/?probe=502457cef5) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76733NJ        | [42dec79e1d](https://linux-hardware.org/?probe=42dec79e1d) | Feb 08, 2022 |
| MSI           | GS66 Stealth 10UH           | [a154ac8369](https://linux-hardware.org/?probe=a154ac8369) | Feb 08, 2022 |
| Lenovo        | Unknown                     | [8f315e1abe](https://linux-hardware.org/?probe=8f315e1abe) | Feb 07, 2022 |
| HUAWEI        | KLV-WX9                     | [80eec7db33](https://linux-hardware.org/?probe=80eec7db33) | Feb 07, 2022 |
| Lenovo        | Unknown                     | [bf281646d9](https://linux-hardware.org/?probe=bf281646d9) | Feb 07, 2022 |
| Dell          | Inspiron 3476               | [468adecdcc](https://linux-hardware.org/?probe=468adecdcc) | Feb 05, 2022 |
| Lenovo        | ThinkPad E450 20DCA07JCD    | [ce693a499b](https://linux-hardware.org/?probe=ce693a499b) | Feb 05, 2022 |
| Timi          | TM1612                      | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| Synology      | DS216+                      | [f4d851d128](https://linux-hardware.org/?probe=f4d851d128) | Feb 04, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [5802ec7cbc](https://linux-hardware.org/?probe=5802ec7cbc) | Jan 30, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [d2d9c64d63](https://linux-hardware.org/?probe=d2d9c64d63) | Jan 30, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fb18e68215](https://linux-hardware.org/?probe=fb18e68215) | Jan 22, 2022 |
| Timi          | A7S                         | [9c419e0bab](https://linux-hardware.org/?probe=9c419e0bab) | Jan 20, 2022 |
| Acer          | Aspire V5-471G              | [7c07d2e27d](https://linux-hardware.org/?probe=7c07d2e27d) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [51d6b35ddf](https://linux-hardware.org/?probe=51d6b35ddf) | Jan 17, 2022 |
| Lenovo        | ThinkPad T470 20HDA022CD    | [3b3eeaa6b7](https://linux-hardware.org/?probe=3b3eeaa6b7) | Jan 14, 2022 |
| Synology      | DS216+                      | [8650ca59f1](https://linux-hardware.org/?probe=8650ca59f1) | Jan 10, 2022 |
| Dell          | Latitude E6400              | [ba6b82b98b](https://linux-hardware.org/?probe=ba6b82b98b) | Jan 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [45d678095f](https://linux-hardware.org/?probe=45d678095f) | Jan 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [666b0b18f5](https://linux-hardware.org/?probe=666b0b18f5) | Dec 30, 2021 |
| Lenovo        | V310-14ISK 80SX             | [ad94c90825](https://linux-hardware.org/?probe=ad94c90825) | Dec 29, 2021 |
| Samsung       | 500R5L/501R5L/500R5P/550... | [1f24ba261b](https://linux-hardware.org/?probe=1f24ba261b) | Dec 27, 2021 |
| Google        | Akemi                       | [295fd594af](https://linux-hardware.org/?probe=295fd594af) | Dec 27, 2021 |
| HP            | EliteBook 8470w             | [87c1cb1da7](https://linux-hardware.org/?probe=87c1cb1da7) | Dec 23, 2021 |
| Lenovo        | Legion Y7000 81FW           | [a7cc31a69f](https://linux-hardware.org/?probe=a7cc31a69f) | Dec 22, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| Acer          | Aspire 4752                 | [e3c15cfedb](https://linux-hardware.org/?probe=e3c15cfedb) | Dec 14, 2021 |
| Acer          | Aspire 4752                 | [5559a99303](https://linux-hardware.org/?probe=5559a99303) | Dec 14, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c029d9c42b](https://linux-hardware.org/?probe=c029d9c42b) | Dec 14, 2021 |
| HP            | ProBook 440 G6              | [bf19b30902](https://linux-hardware.org/?probe=bf19b30902) | Dec 13, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [bd4021ec3d](https://linux-hardware.org/?probe=bd4021ec3d) | Dec 11, 2021 |
| Insyde        | CherryTrail                 | [1525831810](https://linux-hardware.org/?probe=1525831810) | Dec 11, 2021 |
| Lenovo        | Legion Y9000X 2020 81YY     | [acd0b9c831](https://linux-hardware.org/?probe=acd0b9c831) | Dec 11, 2021 |
| HASEE Comp... | E400                        | [32bee165ba](https://linux-hardware.org/?probe=32bee165ba) | Dec 11, 2021 |
| HP            | ProBook 440 G6              | [8c952bfc3d](https://linux-hardware.org/?probe=8c952bfc3d) | Dec 11, 2021 |
| Fujitsu       | FMVNQ8P9                    | [fe3a7ec790](https://linux-hardware.org/?probe=fe3a7ec790) | Dec 10, 2021 |
| Fujitsu       | FMVNQ8P9                    | [c6f3827cb1](https://linux-hardware.org/?probe=c6f3827cb1) | Dec 09, 2021 |
| Fujitsu       | FMVNQ8P9                    | [04ca55ea2b](https://linux-hardware.org/?probe=04ca55ea2b) | Dec 09, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| Lenovo        | B41-80 80LG                 | [96e84134f0](https://linux-hardware.org/?probe=96e84134f0) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [63dade9d7b](https://linux-hardware.org/?probe=63dade9d7b) | Dec 01, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [8e84498214](https://linux-hardware.org/?probe=8e84498214) | Nov 30, 2021 |
| Lenovo        | Unknown                     | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Timi          | A7S                         | [625bafd45f](https://linux-hardware.org/?probe=625bafd45f) | Nov 27, 2021 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [109d14527f](https://linux-hardware.org/?probe=109d14527f) | Nov 27, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [27a4935e65](https://linux-hardware.org/?probe=27a4935e65) | Nov 26, 2021 |
| Jemper        | EZPAD WS_reserve            | [de173db361](https://linux-hardware.org/?probe=de173db361) | Nov 25, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [69c06885de](https://linux-hardware.org/?probe=69c06885de) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [6da7601574](https://linux-hardware.org/?probe=6da7601574) | Nov 18, 2021 |
| Lenovo        | ThinkPad T430 2347G61       | [12ee1cee2b](https://linux-hardware.org/?probe=12ee1cee2b) | Nov 16, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [8c23aaf339](https://linux-hardware.org/?probe=8c23aaf339) | Nov 15, 2021 |
| MSI           | Delta 15 A5EFK              | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| Dell          | Inspiron 7447               | [4ca16063da](https://linux-hardware.org/?probe=4ca16063da) | Nov 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [00e34bc46e](https://linux-hardware.org/?probe=00e34bc46e) | Nov 11, 2021 |
| Jumper        | EZbook                      | [f1391c1f4b](https://linux-hardware.org/?probe=f1391c1f4b) | Nov 10, 2021 |
| Dell          | Inspiron 7472               | [2508fadf63](https://linux-hardware.org/?probe=2508fadf63) | Nov 10, 2021 |
| Dell          | XPS 15 9570                 | [67670eea60](https://linux-hardware.org/?probe=67670eea60) | Nov 07, 2021 |
| Dell          | G15 5515                    | [1e5e0ab274](https://linux-hardware.org/?probe=1e5e0ab274) | Nov 06, 2021 |
| Google        | Akemi                       | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [17339fe912](https://linux-hardware.org/?probe=17339fe912) | Nov 03, 2021 |
| Notebook      | NH5xAx                      | [7aa37239c1](https://linux-hardware.org/?probe=7aa37239c1) | Nov 03, 2021 |
| Dell          | XPS 13 9343                 | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| Timi          | A34R                        | [f5385d6b10](https://linux-hardware.org/?probe=f5385d6b10) | Oct 31, 2021 |
| Acer          | Aspire 4752                 | [8a74691ba9](https://linux-hardware.org/?probe=8a74691ba9) | Oct 30, 2021 |
| Dell          | G3 3500                     | [a2d09beb8d](https://linux-hardware.org/?probe=a2d09beb8d) | Oct 25, 2021 |
| Toshiba       | dynabook Satellite T772/... | [070723f36c](https://linux-hardware.org/?probe=070723f36c) | Oct 24, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [2815629b34](https://linux-hardware.org/?probe=2815629b34) | Oct 21, 2021 |
| HUAWEI        | HLYL-WXX9                   | [9f2d69e4c4](https://linux-hardware.org/?probe=9f2d69e4c4) | Oct 20, 2021 |
| Dell          | G3 3500                     | [ec734562a6](https://linux-hardware.org/?probe=ec734562a6) | Oct 19, 2021 |
| Timi          | A34                         | [e2fbec93e6](https://linux-hardware.org/?probe=e2fbec93e6) | Oct 17, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T2A... | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [00196d9727](https://linux-hardware.org/?probe=00196d9727) | Oct 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4aa5287a00](https://linux-hardware.org/?probe=4aa5287a00) | Oct 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [050314f62a](https://linux-hardware.org/?probe=050314f62a) | Oct 13, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [d3fdfb0745](https://linux-hardware.org/?probe=d3fdfb0745) | Oct 13, 2021 |
| Acer          | Swift SF314-42              | [bce3e39f4c](https://linux-hardware.org/?probe=bce3e39f4c) | Oct 10, 2021 |
| Acer          | Swift SF314-42              | [1c4fbe0fa4](https://linux-hardware.org/?probe=1c4fbe0fa4) | Oct 10, 2021 |
| HP            | 520                         | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| HP            | ZHAN 66 Pro G1              | [a1a1c41c6a](https://linux-hardware.org/?probe=a1a1c41c6a) | Oct 09, 2021 |
| Notebook      | NH5xAx                      | [d63fd746be](https://linux-hardware.org/?probe=d63fd746be) | Oct 09, 2021 |
| HP            | ZHAN 66 Pro G1              | [fcc291e2f1](https://linux-hardware.org/?probe=fcc291e2f1) | Oct 08, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [cbb2ea622b](https://linux-hardware.org/?probe=cbb2ea622b) | Oct 07, 2021 |
| HP            | ZHAN 66 Pro 15 G3           | [0f58e969f6](https://linux-hardware.org/?probe=0f58e969f6) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Timi          | TM1613                      | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Lenovo        | Legion Y7000 2020 82AV      | [64d71e1177](https://linux-hardware.org/?probe=64d71e1177) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1b471b415d](https://linux-hardware.org/?probe=1b471b415d) | Sep 29, 2021 |
| Lenovo        | G510 20238                  | [5f5ae3035b](https://linux-hardware.org/?probe=5f5ae3035b) | Sep 29, 2021 |
| Lenovo        | XiaoXinAir 14ALC 2021 82... | [df352fba0f](https://linux-hardware.org/?probe=df352fba0f) | Sep 27, 2021 |
| Acer          | Nitro AN515-52              | [bb17541aae](https://linux-hardware.org/?probe=bb17541aae) | Sep 26, 2021 |
| Terrans Fo... | AMD                         | [db4b9e36ab](https://linux-hardware.org/?probe=db4b9e36ab) | Sep 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [01362b36bf](https://linux-hardware.org/?probe=01362b36bf) | Sep 24, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | [be9156bd20](https://linux-hardware.org/?probe=be9156bd20) | Sep 24, 2021 |
| Lenovo        | XiaoXin-15IWL 2019 81QS     | [f726b13948](https://linux-hardware.org/?probe=f726b13948) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | [0a99b9ac87](https://linux-hardware.org/?probe=0a99b9ac87) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | [ea86578390](https://linux-hardware.org/?probe=ea86578390) | Sep 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTA0... | [9a59e3a4f1](https://linux-hardware.org/?probe=9a59e3a4f1) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | [18cbc8a35f](https://linux-hardware.org/?probe=18cbc8a35f) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | [5debd35710](https://linux-hardware.org/?probe=5debd35710) | Sep 18, 2021 |
| GXNOVA Com... | GX2                         | [ab148b2b4e](https://linux-hardware.org/?probe=ab148b2b4e) | Sep 14, 2021 |
| Notebook      | P65xHP                      | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAA... | [ebcb7d7982](https://linux-hardware.org/?probe=ebcb7d7982) | Sep 14, 2021 |
| HP            | 431                         | [c2510d05b4](https://linux-hardware.org/?probe=c2510d05b4) | Sep 12, 2021 |
| HP            | 431                         | [d19b47e4d8](https://linux-hardware.org/?probe=d19b47e4d8) | Sep 12, 2021 |
| Sony          | SVT11215CGW                 | [0e12747ab1](https://linux-hardware.org/?probe=0e12747ab1) | Sep 12, 2021 |
| HP            | EliteBook 840 G5            | [35ee0ea8e4](https://linux-hardware.org/?probe=35ee0ea8e4) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [025d2a8ddb](https://linux-hardware.org/?probe=025d2a8ddb) | Sep 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [9bbf3f2d82](https://linux-hardware.org/?probe=9bbf3f2d82) | Sep 05, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [3758bf5026](https://linux-hardware.org/?probe=3758bf5026) | Sep 01, 2021 |
| Timi          | TM1613                      | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Dell          | Latitude E6530              | [5996acf813](https://linux-hardware.org/?probe=5996acf813) | Aug 31, 2021 |
| GPD           | G1618-03                    | [d680dd4360](https://linux-hardware.org/?probe=d680dd4360) | Aug 31, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| HUAWEI        | KPL-W0X                     | [27b23ba02b](https://linux-hardware.org/?probe=27b23ba02b) | Aug 29, 2021 |
| HP            | EliteBook 840 G3            | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| Lenovo        | ThinkPad X220 429044C       | [20057996af](https://linux-hardware.org/?probe=20057996af) | Aug 27, 2021 |
| Dell          | XPS 13 9305                 | [08b5160307](https://linux-hardware.org/?probe=08b5160307) | Aug 27, 2021 |
| Lenovo        | K4450 20229                 | [70e7af9fae](https://linux-hardware.org/?probe=70e7af9fae) | Aug 26, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4563619600](https://linux-hardware.org/?probe=4563619600) | Aug 25, 2021 |
| Lenovo        | K4450 20229                 | [e1c019df72](https://linux-hardware.org/?probe=e1c019df72) | Aug 24, 2021 |
| Lenovo        | ThinkPad E455 20DEA027CD    | [8edb3642cb](https://linux-hardware.org/?probe=8edb3642cb) | Aug 22, 2021 |
| Timi          | TM1612                      | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [321cf3c58f](https://linux-hardware.org/?probe=321cf3c58f) | Aug 18, 2021 |
| Acer          | Nitro AN515-57              | [3c18d3a700](https://linux-hardware.org/?probe=3c18d3a700) | Aug 17, 2021 |
| Alienware     | m17                         | [5fdd4a64a3](https://linux-hardware.org/?probe=5fdd4a64a3) | Aug 17, 2021 |
| Lenovo        | Legion R9000K2021H 82N6     | [048b8332cc](https://linux-hardware.org/?probe=048b8332cc) | Aug 13, 2021 |
| Lenovo        | ThinkPad L430 2466EY7       | [b93128f327](https://linux-hardware.org/?probe=b93128f327) | Aug 12, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5e1cc5b229](https://linux-hardware.org/?probe=5e1cc5b229) | Aug 11, 2021 |
| MSI           | GP66 Leopard 11UG           | [98a65d0b3b](https://linux-hardware.org/?probe=98a65d0b3b) | Aug 10, 2021 |
| ASUSTek       | FX503VD                     | [7c2b153867](https://linux-hardware.org/?probe=7c2b153867) | Aug 08, 2021 |
| Fujitsu       | LIFEBOOK V1020              | [8eff816347](https://linux-hardware.org/?probe=8eff816347) | Aug 08, 2021 |
| Dell          | Latitude 5290 2-in-1        | [293b45eded](https://linux-hardware.org/?probe=293b45eded) | Aug 07, 2021 |
| GPD           | G1618-03                    | [25a0b540aa](https://linux-hardware.org/?probe=25a0b540aa) | Aug 07, 2021 |
| Dell          | Inspiron 11-3168            | [67552d79ac](https://linux-hardware.org/?probe=67552d79ac) | Aug 05, 2021 |
| Lenovo        | ZHAOYANG K3-ITL 82E3        | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| Apple         | MacBookPro16,1              | [124425a1ed](https://linux-hardware.org/?probe=124425a1ed) | Jul 28, 2021 |
| MSI           | GT62VR 7RE                  | [5f02658195](https://linux-hardware.org/?probe=5f02658195) | Jul 27, 2021 |
| Dell          | Latitude 7390 2-in-1        | [e411a84d3c](https://linux-hardware.org/?probe=e411a84d3c) | Jul 26, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [1722982c29](https://linux-hardware.org/?probe=1722982c29) | Jul 26, 2021 |
| Apple         | MacBookPro11,1              | [e4d71ee9a8](https://linux-hardware.org/?probe=e4d71ee9a8) | Jul 24, 2021 |
| Intel         | Corbett Park CRB Revisio... | [17f1a1e73e](https://linux-hardware.org/?probe=17f1a1e73e) | Jul 21, 2021 |
| Lenovo        | Legion R70002020 82B6       | [d620ec97eb](https://linux-hardware.org/?probe=d620ec97eb) | Jul 21, 2021 |
| Lenovo        | G50-70m 20423               | [0b1a40c724](https://linux-hardware.org/?probe=0b1a40c724) | Jul 21, 2021 |
| Lenovo        | ThinkPad X230 23257Y1       | [f282cf1244](https://linux-hardware.org/?probe=f282cf1244) | Jul 18, 2021 |
| Toshiba       | NB300                       | [03b62f85cb](https://linux-hardware.org/?probe=03b62f85cb) | Jul 15, 2021 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | [dd73dac900](https://linux-hardware.org/?probe=dd73dac900) | Jul 15, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | [d563d62b5f](https://linux-hardware.org/?probe=d563d62b5f) | Jul 14, 2021 |
| Dell          | XPS 13 9305                 | [60c8b3011a](https://linux-hardware.org/?probe=60c8b3011a) | Jul 12, 2021 |
| HASEE Comp... | Computer                    | [641cab4c92](https://linux-hardware.org/?probe=641cab4c92) | Jul 11, 2021 |
| Clevo         | P7xxTM(1)                   | [98eeef735f](https://linux-hardware.org/?probe=98eeef735f) | Jul 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9d18d07e36](https://linux-hardware.org/?probe=9d18d07e36) | Jul 06, 2021 |
| HUAWEI        | HLYL-WXX9                   | [26b5b9e3d3](https://linux-hardware.org/?probe=26b5b9e3d3) | Jul 06, 2021 |
| ASUSTek       | VivoBook S14 X411UF         | [f5a3e8f307](https://linux-hardware.org/?probe=f5a3e8f307) | Jul 06, 2021 |
| Acer          | Swift SF314-42              | [d90c6cbf04](https://linux-hardware.org/?probe=d90c6cbf04) | Jul 04, 2021 |
| Lenovo        | ZHAOYANG CF4620Z-A123 59... | [6f716961de](https://linux-hardware.org/?probe=6f716961de) | Jun 29, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [279dea011e](https://linux-hardware.org/?probe=279dea011e) | Jun 28, 2021 |
| Terrans Fo... | X511                        | [7c131d9b3c](https://linux-hardware.org/?probe=7c131d9b3c) | Jun 27, 2021 |
| HUAWEI        | HN-WX9X                     | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Toshiba       | Satellite C600              | [2be9935e22](https://linux-hardware.org/?probe=2be9935e22) | Jun 25, 2021 |
| Dell          | G7 7500                     | [fc4a38d0b1](https://linux-hardware.org/?probe=fc4a38d0b1) | Jun 23, 2021 |
| Apple         | MacBookAir5,2               | [6c83856ca5](https://linux-hardware.org/?probe=6c83856ca5) | Jun 22, 2021 |
| Toshiba       | Satellite C850-C008         | [91fc03f063](https://linux-hardware.org/?probe=91fc03f063) | Jun 21, 2021 |
| Timi          | TM1612                      | [c4fb55cbfd](https://linux-hardware.org/?probe=c4fb55cbfd) | Jun 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [f1200f8ad1](https://linux-hardware.org/?probe=f1200f8ad1) | Jun 20, 2021 |
| Timi          | TM1612                      | [dcb999a722](https://linux-hardware.org/?probe=dcb999a722) | Jun 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [4373344c26](https://linux-hardware.org/?probe=4373344c26) | Jun 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | [43ef80b625](https://linux-hardware.org/?probe=43ef80b625) | Jun 19, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [439593d28e](https://linux-hardware.org/?probe=439593d28e) | Jun 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [45b203fa1d](https://linux-hardware.org/?probe=45b203fa1d) | Jun 19, 2021 |
| MSI           | GS66 Stealth 10SFS          | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| Dell          | Inspiron 3576               | [c9a19ce57f](https://linux-hardware.org/?probe=c9a19ce57f) | Jun 18, 2021 |
| MSI           | GS66 Stealth 10SFS          | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| Hampoo        | Cherry Trail CR V300        | [344ff5676f](https://linux-hardware.org/?probe=344ff5676f) | Jun 16, 2021 |
| Lenovo        | Legion Y9000K 2019 SE 81... | [374ace3f30](https://linux-hardware.org/?probe=374ace3f30) | Jun 15, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [54128eb7cf](https://linux-hardware.org/?probe=54128eb7cf) | Jun 13, 2021 |
| HP            | Pavilion 15                 | [9e0e3015c3](https://linux-hardware.org/?probe=9e0e3015c3) | Jun 13, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [c178189191](https://linux-hardware.org/?probe=c178189191) | Jun 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [8834a1f44c](https://linux-hardware.org/?probe=8834a1f44c) | Jun 11, 2021 |
| Acer          | Swift SF314-42              | [41d143b254](https://linux-hardware.org/?probe=41d143b254) | Jun 09, 2021 |
| Dell          | XPS 13 9370                 | [c8937f439d](https://linux-hardware.org/?probe=c8937f439d) | Jun 09, 2021 |
| HUAWEI        | HLY-WX9XX                   | [72f511586b](https://linux-hardware.org/?probe=72f511586b) | Jun 09, 2021 |
| HASEE Comp... | CW67S                       | [3012373a54](https://linux-hardware.org/?probe=3012373a54) | Jun 08, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [efb0b681f0](https://linux-hardware.org/?probe=efb0b681f0) | Jun 05, 2021 |
| Timi          | TM1612                      | [40318f2d95](https://linux-hardware.org/?probe=40318f2d95) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [173f1c74f4](https://linux-hardware.org/?probe=173f1c74f4) | Jun 04, 2021 |
| Lenovo        | ThinkPad X230 23257Y1       | [d507dfaef3](https://linux-hardware.org/?probe=d507dfaef3) | Jun 02, 2021 |
| HP            | ProBook 430 G3              | [7a11677611](https://linux-hardware.org/?probe=7a11677611) | Jun 01, 2021 |
| Lenovo        | ZHAOYANG K29 20186          | [f02d15e805](https://linux-hardware.org/?probe=f02d15e805) | May 31, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [b6047b1557](https://linux-hardware.org/?probe=b6047b1557) | May 31, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| HUAWEI        | KPR-WX9                     | [9c73a8d7d6](https://linux-hardware.org/?probe=9c73a8d7d6) | May 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| Dell          | Latitude E6440              | [c4842eda94](https://linux-hardware.org/?probe=c4842eda94) | May 24, 2021 |
| Acer          | Swift SF314-42              | [5dca660f7e](https://linux-hardware.org/?probe=5dca660f7e) | May 22, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [c9e7ae41ba](https://linux-hardware.org/?probe=c9e7ae41ba) | May 21, 2021 |
| Lenovo        | ThinkPad X220 4290BB8       | [e147d7b57e](https://linux-hardware.org/?probe=e147d7b57e) | May 21, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| HUAWEI        | MACH-WX9                    | [6331748487](https://linux-hardware.org/?probe=6331748487) | May 20, 2021 |
| ASUSTek       | UX302LA                     | [c04c98c26f](https://linux-hardware.org/?probe=c04c98c26f) | May 19, 2021 |
| HP            | Laptop 14s-fr0xxx           | [ee4105df76](https://linux-hardware.org/?probe=ee4105df76) | May 18, 2021 |
| MSI           | GS60 6QE                    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI           | GS60 6QE                    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| Dell          | Vostro 13 5310              | [ed812af95a](https://linux-hardware.org/?probe=ed812af95a) | May 17, 2021 |
| Dell          | Inspiron 7370               | [ee3ff1a75d](https://linux-hardware.org/?probe=ee3ff1a75d) | May 15, 2021 |
| HUAWEI        | HLY-WX9XX                   | [96c74bb052](https://linux-hardware.org/?probe=96c74bb052) | May 14, 2021 |
| Jumper        | EZbook                      | [8a28589e34](https://linux-hardware.org/?probe=8a28589e34) | May 13, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [049f443199](https://linux-hardware.org/?probe=049f443199) | May 11, 2021 |
| Jumper        | EZbook                      | [9c48c2d8c5](https://linux-hardware.org/?probe=9c48c2d8c5) | May 07, 2021 |
| HP            | EliteBook 745 G5            | [21422647b7](https://linux-hardware.org/?probe=21422647b7) | May 06, 2021 |
| Jumper        | EZbook                      | [741a5fbc51](https://linux-hardware.org/?probe=741a5fbc51) | May 06, 2021 |
| HP            | EliteBook 830 G5            | [b3ffc8d1cb](https://linux-hardware.org/?probe=b3ffc8d1cb) | May 04, 2021 |
| Lenovo        | ThinkPad E480 20KN000UCD    | [f665cfa22e](https://linux-hardware.org/?probe=f665cfa22e) | May 04, 2021 |
| Lenovo        | ThinkPad E14 20RA002JCD     | [ca3b61c51a](https://linux-hardware.org/?probe=ca3b61c51a) | May 04, 2021 |
| ASUSTek       | X455LJ                      | [e769a18f8a](https://linux-hardware.org/?probe=e769a18f8a) | May 04, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| HP            | ZHAN 99 G2 Mobile Workst... | [8647f6f8fb](https://linux-hardware.org/?probe=8647f6f8fb) | Apr 29, 2021 |
| Dell          | XPS 15 9560                 | [6ee00932dc](https://linux-hardware.org/?probe=6ee00932dc) | Apr 29, 2021 |
| HASEE Comp... | QTC6                        | [7f1f85fd8c](https://linux-hardware.org/?probe=7f1f85fd8c) | Apr 28, 2021 |
| Dell          | Inspiron 3482               | [a8ab0451de](https://linux-hardware.org/?probe=a8ab0451de) | Apr 27, 2021 |
| Lenovo        | ZHAOYANG K43c-80 81HX       | [de6628af88](https://linux-hardware.org/?probe=de6628af88) | Apr 27, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [5f7bac315c](https://linux-hardware.org/?probe=5f7bac315c) | Apr 19, 2021 |
| Acer          | Swift SF313-52              | [0f4028c401](https://linux-hardware.org/?probe=0f4028c401) | Apr 19, 2021 |
| Samsung       | 535U4C                      | [1bdb581e3d](https://linux-hardware.org/?probe=1bdb581e3d) | Apr 17, 2021 |
| Dell          | XPS 15 9570                 | [ee1c82a186](https://linux-hardware.org/?probe=ee1c82a186) | Apr 15, 2021 |
| Samsung       | 535U4C                      | [1f61906add](https://linux-hardware.org/?probe=1f61906add) | Apr 15, 2021 |
| HASEE Comp... | Unknown                     | [5abcc341b3](https://linux-hardware.org/?probe=5abcc341b3) | Apr 14, 2021 |
| HASEE Comp... | Unknown                     | [76f3519f3f](https://linux-hardware.org/?probe=76f3519f3f) | Apr 14, 2021 |
| Lenovo        | ThinkPad T410s 2912B99      | [cce75356c4](https://linux-hardware.org/?probe=cce75356c4) | Apr 11, 2021 |
| HP            | EliteBook 8770w             | [4b01a44998](https://linux-hardware.org/?probe=4b01a44998) | Apr 10, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7c883d58c6](https://linux-hardware.org/?probe=7c883d58c6) | Apr 10, 2021 |
| Lenovo        | V10 ThinkPad X63            | [60ee0c7112](https://linux-hardware.org/?probe=60ee0c7112) | Apr 08, 2021 |
| Lenovo        | V10 ThinkPad X63            | [dfa1081980](https://linux-hardware.org/?probe=dfa1081980) | Apr 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [e03bf9d1a9](https://linux-hardware.org/?probe=e03bf9d1a9) | Apr 07, 2021 |
| MECHREVO      | S3 Pro                      | [a8656190d7](https://linux-hardware.org/?probe=a8656190d7) | Apr 04, 2021 |
| Dell          | System XPS L702X            | [e15be45763](https://linux-hardware.org/?probe=e15be45763) | Apr 04, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [66d76dda01](https://linux-hardware.org/?probe=66d76dda01) | Apr 03, 2021 |
| GPD           | P2 MAX                      | [b07bc1f694](https://linux-hardware.org/?probe=b07bc1f694) | Apr 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [aa8f00686c](https://linux-hardware.org/?probe=aa8f00686c) | Apr 01, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [7ffd62b3fa](https://linux-hardware.org/?probe=7ffd62b3fa) | Mar 31, 2021 |
| Lenovo        | Unknown                     | [98ed905fb1](https://linux-hardware.org/?probe=98ed905fb1) | Mar 28, 2021 |
| Lenovo        | ThinkPad X230 2324DM2       | [2cf882da9e](https://linux-hardware.org/?probe=2cf882da9e) | Mar 28, 2021 |
| Dell          | Latitude E6400              | [ac6d60eaa9](https://linux-hardware.org/?probe=ac6d60eaa9) | Mar 26, 2021 |
| Dell          | Latitude E6400              | [7b97516ad8](https://linux-hardware.org/?probe=7b97516ad8) | Mar 26, 2021 |
| Acer          | Swift SF314-42              | [4ff6ff15fc](https://linux-hardware.org/?probe=4ff6ff15fc) | Mar 26, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [16f1d9e647](https://linux-hardware.org/?probe=16f1d9e647) | Mar 18, 2021 |
| HP            | ZHAN 99 G2 Mobile Workst... | [d16fc044eb](https://linux-hardware.org/?probe=d16fc044eb) | Mar 18, 2021 |
| Acer          | Swift SF314-42              | [a95086c30b](https://linux-hardware.org/?probe=a95086c30b) | Mar 18, 2021 |
| Acer          | Swift SF314-42              | [d98e2dea30](https://linux-hardware.org/?probe=d98e2dea30) | Mar 17, 2021 |
| Acer          | Swift SF314-42              | [e10243fa5c](https://linux-hardware.org/?probe=e10243fa5c) | Mar 17, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [b96252ab8f](https://linux-hardware.org/?probe=b96252ab8f) | Mar 15, 2021 |
| Timi          | Mi Laptop Pro 15            | [d73ebe56eb](https://linux-hardware.org/?probe=d73ebe56eb) | Mar 11, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | [4202717644](https://linux-hardware.org/?probe=4202717644) | Mar 05, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | [3b64f161c0](https://linux-hardware.org/?probe=3b64f161c0) | Mar 05, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | [f3cfea77ac](https://linux-hardware.org/?probe=f3cfea77ac) | Mar 04, 2021 |
| Lenovo        | ThinkPad X220 4291HL8       | [f8dd5d3807](https://linux-hardware.org/?probe=f8dd5d3807) | Mar 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [96a3577708](https://linux-hardware.org/?probe=96a3577708) | Feb 24, 2021 |
| HP            | 1000                        | [2ab8891f42](https://linux-hardware.org/?probe=2ab8891f42) | Feb 23, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [93e1220042](https://linux-hardware.org/?probe=93e1220042) | Feb 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | [78ec6d58ba](https://linux-hardware.org/?probe=78ec6d58ba) | Feb 22, 2021 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [bbace409ed](https://linux-hardware.org/?probe=bbace409ed) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [df1e1e308b](https://linux-hardware.org/?probe=df1e1e308b) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [94362e140c](https://linux-hardware.org/?probe=94362e140c) | Feb 18, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [6e1c4be9d8](https://linux-hardware.org/?probe=6e1c4be9d8) | Feb 17, 2021 |
| HASEE Comp... | E460                        | [5af90fef31](https://linux-hardware.org/?probe=5af90fef31) | Feb 17, 2021 |
| Timi          | TM1703                      | [53183984c3](https://linux-hardware.org/?probe=53183984c3) | Feb 14, 2021 |
| Timi          | Mi Laptop Pro 15            | [5b5df6dbfc](https://linux-hardware.org/?probe=5b5df6dbfc) | Feb 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [3792a88564](https://linux-hardware.org/?probe=3792a88564) | Feb 08, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [797c58c227](https://linux-hardware.org/?probe=797c58c227) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d538017b75](https://linux-hardware.org/?probe=d538017b75) | Feb 04, 2021 |
| Timi          | RedmiBook 14 II             | [1ed34422ce](https://linux-hardware.org/?probe=1ed34422ce) | Feb 02, 2021 |
| HUAWEI        | NBLL-WXX9                   | [b8558ad233](https://linux-hardware.org/?probe=b8558ad233) | Feb 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c0cd6afd03](https://linux-hardware.org/?probe=c0cd6afd03) | Feb 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [2135ddb8dd](https://linux-hardware.org/?probe=2135ddb8dd) | Feb 02, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | [8db56c19da](https://linux-hardware.org/?probe=8db56c19da) | Feb 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [39c3dd1edd](https://linux-hardware.org/?probe=39c3dd1edd) | Feb 02, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [32ba9cc321](https://linux-hardware.org/?probe=32ba9cc321) | Jan 29, 2021 |
| HP            | EliteBook 840 G1            | [11db0c5d50](https://linux-hardware.org/?probe=11db0c5d50) | Jan 27, 2021 |
| Lenovo        | Legion Y7000 81FW           | [a7106e3642](https://linux-hardware.org/?probe=a7106e3642) | Jan 27, 2021 |
| Timi          | RedmiBook 14 II             | [f888388942](https://linux-hardware.org/?probe=f888388942) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [583f0d9ea2](https://linux-hardware.org/?probe=583f0d9ea2) | Jan 22, 2021 |
| Dell          | Precision 5750              | [11a4cc2ef1](https://linux-hardware.org/?probe=11a4cc2ef1) | Jan 19, 2021 |
| HP            | Pavilion Notebook           | [66efbfed55](https://linux-hardware.org/?probe=66efbfed55) | Jan 19, 2021 |
| Lenovo        | IdeaPad 320C-15IKB 81FU     | [32af8085e3](https://linux-hardware.org/?probe=32af8085e3) | Jan 15, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [1e5e57866d](https://linux-hardware.org/?probe=1e5e57866d) | Jan 14, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [4149fbf824](https://linux-hardware.org/?probe=4149fbf824) | Jan 14, 2021 |
| Lenovo        | Unknown                     | [38c41d5178](https://linux-hardware.org/?probe=38c41d5178) | Jan 13, 2021 |
| Lenovo        | Legion Y7000 81FW           | [ca1391c20d](https://linux-hardware.org/?probe=ca1391c20d) | Jan 13, 2021 |
| Lenovo        | Legion Y7000 81FW           | [1a4ee1ce22](https://linux-hardware.org/?probe=1a4ee1ce22) | Jan 13, 2021 |
| HP            | ZHAN 66 Pro 15 G3           | [309b0b4383](https://linux-hardware.org/?probe=309b0b4383) | Jan 12, 2021 |
| HP            | ProBook 6565b               | [517e898344](https://linux-hardware.org/?probe=517e898344) | Jan 12, 2021 |
| Lenovo        | Legion Y7000 81FW           | [8b678d540d](https://linux-hardware.org/?probe=8b678d540d) | Jan 06, 2021 |
| Lenovo        | Legion Y7000 81FW           | [95eb2199fd](https://linux-hardware.org/?probe=95eb2199fd) | Jan 06, 2021 |
| Dell          | G3 3500                     | [584259b642](https://linux-hardware.org/?probe=584259b642) | Jan 02, 2021 |
| Lenovo        | Unknown                     | [bfa46b3e89](https://linux-hardware.org/?probe=bfa46b3e89) | Jan 01, 2021 |
| Dell          | G3 3579                     | [200c758b4b](https://linux-hardware.org/?probe=200c758b4b) | Jan 01, 2021 |
| ASUSTek       | F81Se                       | [78420c272f](https://linux-hardware.org/?probe=78420c272f) | Dec 30, 2020 |
| ASUSTek       | F81Se                       | [f88933df38](https://linux-hardware.org/?probe=f88933df38) | Dec 30, 2020 |
| Lenovo        | G580 20150                  | [3e777432b1](https://linux-hardware.org/?probe=3e777432b1) | Dec 29, 2020 |
| Lenovo        | Unknown                     | [d789a34be2](https://linux-hardware.org/?probe=d789a34be2) | Dec 29, 2020 |
| Lenovo        | Unknown                     | [9ea48b71d6](https://linux-hardware.org/?probe=9ea48b71d6) | Dec 29, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [258a4745bf](https://linux-hardware.org/?probe=258a4745bf) | Dec 29, 2020 |
| Timi          | RedmiBook 14 II             | [6d6ce6a47a](https://linux-hardware.org/?probe=6d6ce6a47a) | Dec 29, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | [c9a2d0d9e0](https://linux-hardware.org/?probe=c9a2d0d9e0) | Dec 28, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [dc8521e74c](https://linux-hardware.org/?probe=dc8521e74c) | Dec 28, 2020 |
| ASUSTek       | F81Se                       | [f33f999200](https://linux-hardware.org/?probe=f33f999200) | Dec 26, 2020 |
| Dell          | Inspiron 1010               | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| HASEE Comp... | PF4WN2F                     | [9855617493](https://linux-hardware.org/?probe=9855617493) | Dec 15, 2020 |
| Lenovo        | ThinkPad X230 2325DV4       | [03eaed4dcb](https://linux-hardware.org/?probe=03eaed4dcb) | Dec 11, 2020 |
| GPD           | P2 MAX                      | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| HUAWEI        | HLY-WX9XX                   | [87cfa2982d](https://linux-hardware.org/?probe=87cfa2982d) | Dec 09, 2020 |
| Unknown       | Unknown                     | [8b7c746735](https://linux-hardware.org/?probe=8b7c746735) | Dec 08, 2020 |
| HUAWEI        | HLY-WX9XX                   | [290c53b26c](https://linux-hardware.org/?probe=290c53b26c) | Dec 08, 2020 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [a9e2438f51](https://linux-hardware.org/?probe=a9e2438f51) | Nov 28, 2020 |
| Lenovo        | Legion Y9000X 2020 81TH     | [2aa8c29fb4](https://linux-hardware.org/?probe=2aa8c29fb4) | Nov 21, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [73c5a8bd67](https://linux-hardware.org/?probe=73c5a8bd67) | Nov 19, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [23418fe6cc](https://linux-hardware.org/?probe=23418fe6cc) | Nov 19, 2020 |
| Apple         | MacBookPro11,3              | [a01b45c371](https://linux-hardware.org/?probe=a01b45c371) | Nov 17, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [37dbdd4b85](https://linux-hardware.org/?probe=37dbdd4b85) | Nov 16, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | [5182cf15a5](https://linux-hardware.org/?probe=5182cf15a5) | Nov 16, 2020 |
| Acer          | Aspire V5-571G              | [49707be15c](https://linux-hardware.org/?probe=49707be15c) | Nov 16, 2020 |
| Lenovo        | Y430P 20435                 | [2ee9b87c44](https://linux-hardware.org/?probe=2ee9b87c44) | Nov 15, 2020 |
| HASEE Comp... | QTH6                        | [a2a60413b1](https://linux-hardware.org/?probe=a2a60413b1) | Nov 13, 2020 |
| HASEE Comp... | QL9S                        | [a1bd3a60dc](https://linux-hardware.org/?probe=a1bd3a60dc) | Nov 13, 2020 |
| HASEE Comp... | QL9S                        | [799ba586bd](https://linux-hardware.org/?probe=799ba586bd) | Nov 13, 2020 |
| Dell          | Inspiron 3576               | [d68d6cdf18](https://linux-hardware.org/?probe=d68d6cdf18) | Nov 13, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | [069182cff6](https://linux-hardware.org/?probe=069182cff6) | Nov 12, 2020 |
| Dell          | Latitude 5490               | [894bd38b38](https://linux-hardware.org/?probe=894bd38b38) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | [28c7cf4458](https://linux-hardware.org/?probe=28c7cf4458) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | [b4fbf1f2e6](https://linux-hardware.org/?probe=b4fbf1f2e6) | Nov 11, 2020 |
| Dell          | Precision 7510              | [5cb1751259](https://linux-hardware.org/?probe=5cb1751259) | Nov 11, 2020 |
| Sony          | VPCZ115FC                   | [7e886b81d0](https://linux-hardware.org/?probe=7e886b81d0) | Nov 09, 2020 |
| Lenovo        | Unknown                     | [d689908218](https://linux-hardware.org/?probe=d689908218) | Nov 08, 2020 |
| Lenovo        | ThinkPad X250 20CLA272CD    | [a9075402e1](https://linux-hardware.org/?probe=a9075402e1) | Nov 08, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | [907de62181](https://linux-hardware.org/?probe=907de62181) | Oct 31, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [1affea93fd](https://linux-hardware.org/?probe=1affea93fd) | Oct 27, 2020 |
| HUAWEI        | HLY-WX9XX                   | [e930aac9b6](https://linux-hardware.org/?probe=e930aac9b6) | Oct 27, 2020 |
| HUAWEI        | KPL-W0X                     | [cf48a4f7b0](https://linux-hardware.org/?probe=cf48a4f7b0) | Oct 26, 2020 |
| Lenovo        | M5400 20281                 | [08fa33ca8e](https://linux-hardware.org/?probe=08fa33ca8e) | Oct 22, 2020 |
| HP            | ZHAN 66 Pro 15 G2           | [adb6a00cd2](https://linux-hardware.org/?probe=adb6a00cd2) | Oct 22, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [f101c9246f](https://linux-hardware.org/?probe=f101c9246f) | Oct 17, 2020 |
| Dell          | G3 3500                     | [5cb1ce307e](https://linux-hardware.org/?probe=5cb1ce307e) | Oct 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [5af00a6f4a](https://linux-hardware.org/?probe=5af00a6f4a) | Oct 13, 2020 |
| Unknown       | Unknown                     | [b4ead91a12](https://linux-hardware.org/?probe=b4ead91a12) | Oct 05, 2020 |
| HP            | ZHAN 66 Pro 14 G2           | [b690ea4e11](https://linux-hardware.org/?probe=b690ea4e11) | Oct 03, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [88e5775f0f](https://linux-hardware.org/?probe=88e5775f0f) | Oct 02, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [2972557e3e](https://linux-hardware.org/?probe=2972557e3e) | Oct 02, 2020 |
| Lenovo        | ThinkPad E580 20KS002BCD    | [e89a66365d](https://linux-hardware.org/?probe=e89a66365d) | Sep 29, 2020 |
| Lenovo        | M5400 20281                 | [839f6b0ddc](https://linux-hardware.org/?probe=839f6b0ddc) | Sep 28, 2020 |
| Dell          | Inspiron 7720               | [cafa640700](https://linux-hardware.org/?probe=cafa640700) | Sep 27, 2020 |
| HUAWEI        | KPL-W0X                     | [b53090f7ec](https://linux-hardware.org/?probe=b53090f7ec) | Sep 20, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [814cb96243](https://linux-hardware.org/?probe=814cb96243) | Sep 19, 2020 |
| HP            | ProBook 6565b               | [92c570e1f9](https://linux-hardware.org/?probe=92c570e1f9) | Sep 18, 2020 |
| Lenovo        | ThinkPad T450s 20BX002GH... | [2e10a094c7](https://linux-hardware.org/?probe=2e10a094c7) | Sep 17, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | [dae1221cfd](https://linux-hardware.org/?probe=dae1221cfd) | Sep 16, 2020 |
| HUAWEI        | HLY-WX9XX                   | [55bf2ea24a](https://linux-hardware.org/?probe=55bf2ea24a) | Sep 16, 2020 |
| Dell          | Precision 5510              | [f4f4ec51bf](https://linux-hardware.org/?probe=f4f4ec51bf) | Sep 09, 2020 |
| Lenovo        | IdeaPad S410 20301          | [b4410055a6](https://linux-hardware.org/?probe=b4410055a6) | Aug 31, 2020 |
| Lenovo        | Unknown                     | [7dad252a0d](https://linux-hardware.org/?probe=7dad252a0d) | Aug 31, 2020 |
| Intel         | H81U                        | [9dfe47a2b3](https://linux-hardware.org/?probe=9dfe47a2b3) | Aug 26, 2020 |
| Intel         | H81U                        | [65f88785ff](https://linux-hardware.org/?probe=65f88785ff) | Aug 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f0150526b6](https://linux-hardware.org/?probe=f0150526b6) | Aug 24, 2020 |
| HUAWEI        | HLY-WX9XX                   | [d53a271c2a](https://linux-hardware.org/?probe=d53a271c2a) | Aug 23, 2020 |
| Lenovo        | Unknown                     | [7ba1cf5064](https://linux-hardware.org/?probe=7ba1cf5064) | Aug 19, 2020 |
| HUAWEI        | HLY-WX9XX                   | [fb2ef05779](https://linux-hardware.org/?probe=fb2ef05779) | Aug 17, 2020 |
| Dell          | Inspiron N4050              | [c51c0d5538](https://linux-hardware.org/?probe=c51c0d5538) | Aug 15, 2020 |
| HASEE Comp... | GJ5CN64                     | [629359f065](https://linux-hardware.org/?probe=629359f065) | Aug 07, 2020 |
| Sony          | VPCYB35JC                   | [7872a30f96](https://linux-hardware.org/?probe=7872a30f96) | Aug 06, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [b948b0ffe7](https://linux-hardware.org/?probe=b948b0ffe7) | Aug 03, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | [0f826bb295](https://linux-hardware.org/?probe=0f826bb295) | Aug 03, 2020 |
| Lenovo        | Unknown                     | [570aec33e6](https://linux-hardware.org/?probe=570aec33e6) | Aug 02, 2020 |
| Lenovo        | Unknown                     | [cdabfce7b7](https://linux-hardware.org/?probe=cdabfce7b7) | Aug 02, 2020 |
| TR            | ThundeRobot                 | [c22560abf3](https://linux-hardware.org/?probe=c22560abf3) | Aug 02, 2020 |
| Acer          | Aspire 4560                 | [aacc9842e1](https://linux-hardware.org/?probe=aacc9842e1) | Aug 01, 2020 |
| HP            | EliteBook 820 G2            | [0defe9b34c](https://linux-hardware.org/?probe=0defe9b34c) | Aug 01, 2020 |
| HP            | EliteBook 820 G2            | [44e1ce47dc](https://linux-hardware.org/?probe=44e1ce47dc) | Aug 01, 2020 |
| Lenovo        | ThinkPad W550s 20E2000CM... | [fae2775795](https://linux-hardware.org/?probe=fae2775795) | Jul 30, 2020 |
| Teclast       | tPAD                        | [2fdb26f348](https://linux-hardware.org/?probe=2fdb26f348) | Jul 29, 2020 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [cb12b1101c](https://linux-hardware.org/?probe=cb12b1101c) | Jul 20, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [a577a84015](https://linux-hardware.org/?probe=a577a84015) | Jul 12, 2020 |
| Dell          | XPS 15 7590                 | [cc4958e2d1](https://linux-hardware.org/?probe=cc4958e2d1) | Jul 12, 2020 |
| HP            | ZHAN 66 Pro G1              | [a2da22d929](https://linux-hardware.org/?probe=a2da22d929) | Jul 11, 2020 |
| Lenovo        | ThinkPad P53 20QQA01JCD     | [38faa849ff](https://linux-hardware.org/?probe=38faa849ff) | Jul 08, 2020 |
| Lenovo        | ThinkPad X395 20NL000YCD    | [8ce881d65e](https://linux-hardware.org/?probe=8ce881d65e) | Jul 06, 2020 |
| Dell          | Inspiron N4050              | [2a05830be5](https://linux-hardware.org/?probe=2a05830be5) | Jul 05, 2020 |
| Lenovo        | IdeaPad Y460                | [eec296f86e](https://linux-hardware.org/?probe=eec296f86e) | Jul 04, 2020 |
| HP            | Laptop 14s-dk0xxx           | [6d2e4339ac](https://linux-hardware.org/?probe=6d2e4339ac) | Jul 02, 2020 |
| HP            | ProBook 6565b               | [19bad7a13f](https://linux-hardware.org/?probe=19bad7a13f) | Jun 30, 2020 |
| HP            | ProBook 6565b               | [3a81652253](https://linux-hardware.org/?probe=3a81652253) | Jun 30, 2020 |
| Dell          | Precision 5520              | [c2407629ef](https://linux-hardware.org/?probe=c2407629ef) | Jun 30, 2020 |
| Dell          | XPS 15 9500                 | [b0029da795](https://linux-hardware.org/?probe=b0029da795) | Jun 27, 2020 |
| Dell          | XPS 15 9570                 | [2a82160500](https://linux-hardware.org/?probe=2a82160500) | Jun 19, 2020 |
| HUAWEI        | HLY-WX9XX                   | [f532f4f740](https://linux-hardware.org/?probe=f532f4f740) | Jun 17, 2020 |
| HP            | ENVY Laptop 13-ah1xxx       | [b9c34fddc7](https://linux-hardware.org/?probe=b9c34fddc7) | Jun 15, 2020 |
| AVITA         | NS14A8                      | [6148b267ec](https://linux-hardware.org/?probe=6148b267ec) | Jun 13, 2020 |
| HP            | ENVY Laptop 13-ah1xxx       | [3fa545e765](https://linux-hardware.org/?probe=3fa545e765) | Jun 12, 2020 |
| HUAWEI        | HLY-WX9XX                   | [443ec260d7](https://linux-hardware.org/?probe=443ec260d7) | Jun 12, 2020 |
| HP            | ENVY Laptop 13-ah1xxx       | [ed5af09293](https://linux-hardware.org/?probe=ed5af09293) | Jun 09, 2020 |
| Lenovo        | Y430P 20435                 | [1a02a65fe2](https://linux-hardware.org/?probe=1a02a65fe2) | Jun 07, 2020 |
| HUAWEI        | KPR-WX9                     | [383ede6256](https://linux-hardware.org/?probe=383ede6256) | Jun 06, 2020 |
| Lenovo        | XiaoXinAir-14IIL 2020 81... | [761aaee925](https://linux-hardware.org/?probe=761aaee925) | Jun 06, 2020 |
| Lenovo        | ThinkPad W500 4063RT3       | [1263b95cf5](https://linux-hardware.org/?probe=1263b95cf5) | Jun 01, 2020 |
| HUAWEI        | HLY-WX9XX                   | [e4105f6fc1](https://linux-hardware.org/?probe=e4105f6fc1) | May 31, 2020 |
| Lenovo        | ThinkPad T470 20HDA01MCD    | [bd45efa3fb](https://linux-hardware.org/?probe=bd45efa3fb) | May 29, 2020 |
| Acer          | Aspire E5-553G              | [334a330b2b](https://linux-hardware.org/?probe=334a330b2b) | May 29, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [1ef79c4312](https://linux-hardware.org/?probe=1ef79c4312) | May 27, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [49337f4321](https://linux-hardware.org/?probe=49337f4321) | May 27, 2020 |
| ASUSTek       | T100TAF                     | [6d2999ebb1](https://linux-hardware.org/?probe=6d2999ebb1) | May 26, 2020 |
| Sony          | SVF15N17DJS                 | [da222707b2](https://linux-hardware.org/?probe=da222707b2) | May 26, 2020 |
| LG Electro... | 13Z990-V.AA53C              | [2674ee06bd](https://linux-hardware.org/?probe=2674ee06bd) | May 24, 2020 |
| Lenovo        | Legion Y9000X 2020 81TH     | [bd60f2ac06](https://linux-hardware.org/?probe=bd60f2ac06) | May 22, 2020 |
| Lenovo        | ThinkPad X220 4287A11       | [ac9926d32d](https://linux-hardware.org/?probe=ac9926d32d) | May 19, 2020 |
| Dell          | Inspiron 7537               | [5e800e551c](https://linux-hardware.org/?probe=5e800e551c) | May 18, 2020 |
| Unknown       | Unknown                     | [e70916ddfb](https://linux-hardware.org/?probe=e70916ddfb) | May 18, 2020 |
| HUAWEI        | HLY-WX9XX                   | [ffd9df1914](https://linux-hardware.org/?probe=ffd9df1914) | May 14, 2020 |
| ASUSTek       | X541UJ                      | [d02c3d787d](https://linux-hardware.org/?probe=d02c3d787d) | May 11, 2020 |
| ASUSTek       | X541UJ                      | [7f3ef9343e](https://linux-hardware.org/?probe=7f3ef9343e) | May 11, 2020 |
| ASUSTek       | X541UJ                      | [b9be90e66e](https://linux-hardware.org/?probe=b9be90e66e) | May 11, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | [8d8b69ef00](https://linux-hardware.org/?probe=8d8b69ef00) | May 10, 2020 |
| Dell          | Latitude E6220              | [a4db1d31a5](https://linux-hardware.org/?probe=a4db1d31a5) | May 05, 2020 |
| Dell          | Latitude E6220              | [c0152a3b02](https://linux-hardware.org/?probe=c0152a3b02) | May 05, 2020 |
| Lenovo        | ThinkPad X201s 5397G4C      | [e37ac78744](https://linux-hardware.org/?probe=e37ac78744) | May 05, 2020 |
| Acer          | Aspire E1-471G              | [6ebcffa76b](https://linux-hardware.org/?probe=6ebcffa76b) | May 04, 2020 |
| Lenovo        | ZHAOYANG E42-80 80T8        | [58d0c0c1af](https://linux-hardware.org/?probe=58d0c0c1af) | May 03, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [729a079629](https://linux-hardware.org/?probe=729a079629) | Apr 28, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [6e5f544240](https://linux-hardware.org/?probe=6e5f544240) | Apr 28, 2020 |
| Samsung       | R440                        | [2b527c692e](https://linux-hardware.org/?probe=2b527c692e) | Apr 21, 2020 |
| Samsung       | R440                        | [7c20fb1986](https://linux-hardware.org/?probe=7c20fb1986) | Apr 21, 2020 |
| HUAWEI        | WRT-WX9                     | [38be8071f2](https://linux-hardware.org/?probe=38be8071f2) | Apr 19, 2020 |
| Lenovo        | Legion Y9000X 2020 81TH     | [bc52c2ff9a](https://linux-hardware.org/?probe=bc52c2ff9a) | Apr 12, 2020 |
| Lenovo        | ThinkPad X220 4287A11       | [97e8cae9bb](https://linux-hardware.org/?probe=97e8cae9bb) | Apr 11, 2020 |
| HP            | Laptop 14-bw0xx             | [50cfedd24a](https://linux-hardware.org/?probe=50cfedd24a) | Apr 11, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [ca529580d5](https://linux-hardware.org/?probe=ca529580d5) | Apr 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2e5075d2e8](https://linux-hardware.org/?probe=2e5075d2e8) | Apr 10, 2020 |
| HUAWEI        | MACHC-WAX9                  | [4d780e5077](https://linux-hardware.org/?probe=4d780e5077) | Apr 09, 2020 |
| Insyde        | Braswell                    | [ad8f4d2408](https://linux-hardware.org/?probe=ad8f4d2408) | Apr 07, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [e6963791cb](https://linux-hardware.org/?probe=e6963791cb) | Apr 07, 2020 |
| HP            | EliteBook 8770w             | [c8c1149b77](https://linux-hardware.org/?probe=c8c1149b77) | Apr 04, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | [a602b4a98e](https://linux-hardware.org/?probe=a602b4a98e) | Apr 02, 2020 |
| HUAWEI        | KLVC-WXX9                   | [dc892ce89f](https://linux-hardware.org/?probe=dc892ce89f) | Mar 22, 2020 |
| Lenovo        | ThinkPad X220 4290FP2       | [46bf7f136a](https://linux-hardware.org/?probe=46bf7f136a) | Mar 22, 2020 |
| Dell          | Latitude E7250              | [db8f980af7](https://linux-hardware.org/?probe=db8f980af7) | Mar 21, 2020 |
| Lenovo        | XiaoXin V4000 80MY          | [f84cb81dba](https://linux-hardware.org/?probe=f84cb81dba) | Mar 18, 2020 |
| MECHREVO      | X9Ti-R Series GK7CP0S       | [ee88c9e543](https://linux-hardware.org/?probe=ee88c9e543) | Mar 13, 2020 |
| MECHREVO      | X9Ti-R Series GK7CP0S       | [f65b70dee5](https://linux-hardware.org/?probe=f65b70dee5) | Mar 12, 2020 |
| Acer          | Aspire V5-552G              | [1e7e0572b2](https://linux-hardware.org/?probe=1e7e0572b2) | Mar 12, 2020 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [005dfa63d7](https://linux-hardware.org/?probe=005dfa63d7) | Mar 07, 2020 |
| HP            | Pavilion dv6                | [f125c0e156](https://linux-hardware.org/?probe=f125c0e156) | Mar 05, 2020 |
| Acer          | Aspire VN7-792G             | [3924df2c92](https://linux-hardware.org/?probe=3924df2c92) | Feb 28, 2020 |
| Dell          | Inspiron 15-3567            | [676d073b68](https://linux-hardware.org/?probe=676d073b68) | Feb 24, 2020 |
| Dell          | Inspiron 15-3567            | [426bc40176](https://linux-hardware.org/?probe=426bc40176) | Feb 24, 2020 |
| ASUSTek       | 1015B                       | [04ff15312c](https://linux-hardware.org/?probe=04ff15312c) | Feb 24, 2020 |
| ASUSTek       | 1015B                       | [63d24474a4](https://linux-hardware.org/?probe=63d24474a4) | Feb 24, 2020 |
| Dell          | Inspiron 7559               | [6f0a1ae634](https://linux-hardware.org/?probe=6f0a1ae634) | Feb 22, 2020 |
| ASUSTek       | N82JQ                       | [f03777a2b9](https://linux-hardware.org/?probe=f03777a2b9) | Feb 20, 2020 |
| Lenovo        | XiaoXin Air 13IWL 81J8      | [4d3479c7df](https://linux-hardware.org/?probe=4d3479c7df) | Feb 19, 2020 |
| Unknown       | p6                          | [235b076f4f](https://linux-hardware.org/?probe=235b076f4f) | Feb 19, 2020 |
| HUAWEI        | KPRC-WX0                    | [8cfec181a0](https://linux-hardware.org/?probe=8cfec181a0) | Feb 18, 2020 |
| Acer          | Aspire 4736Z                | [2b6edf8d9a](https://linux-hardware.org/?probe=2b6edf8d9a) | Feb 15, 2020 |
| Lenovo        | ThinkPad T440s 20ARS2H40... | [0f32bfa665](https://linux-hardware.org/?probe=0f32bfa665) | Feb 11, 2020 |
| Dell          | Precision 5510              | [bab9a0d0c8](https://linux-hardware.org/?probe=bab9a0d0c8) | Feb 11, 2020 |
| Dell          | Precision 5510              | [4c17778c81](https://linux-hardware.org/?probe=4c17778c81) | Feb 05, 2020 |
| Lenovo        | ZHAOYANG E40-80 80HR        | [78f39c1935](https://linux-hardware.org/?probe=78f39c1935) | Feb 05, 2020 |
| Timi          | TM1709                      | [ffc5e87668](https://linux-hardware.org/?probe=ffc5e87668) | Feb 03, 2020 |
| HP            | Laptop 15-db0xxx            | [03731a6e89](https://linux-hardware.org/?probe=03731a6e89) | Jan 28, 2020 |
| Toshiba       | Satellite L55-B             | [cbf62518f7](https://linux-hardware.org/?probe=cbf62518f7) | Jan 25, 2020 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | [cb91151a43](https://linux-hardware.org/?probe=cb91151a43) | Jan 22, 2020 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | [f3558727ea](https://linux-hardware.org/?probe=f3558727ea) | Jan 22, 2020 |
| HUAWEI        | HLY-WX9XX                   | [9f6e79326e](https://linux-hardware.org/?probe=9f6e79326e) | Jan 14, 2020 |
| Sony          | VGN-CR322H_P                | [459dd43900](https://linux-hardware.org/?probe=459dd43900) | Jan 11, 2020 |
| Sony          | VGN-CR322H_P                | [a131f14c28](https://linux-hardware.org/?probe=a131f14c28) | Jan 11, 2020 |
| MSI           | GF72 8RE                    | [ff9ee83e94](https://linux-hardware.org/?probe=ff9ee83e94) | Jan 09, 2020 |
| Dell          | Inspiron 7560               | [262434461f](https://linux-hardware.org/?probe=262434461f) | Jan 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [95488c6be1](https://linux-hardware.org/?probe=95488c6be1) | Jan 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [925412ddcd](https://linux-hardware.org/?probe=925412ddcd) | Jan 02, 2020 |
| Lenovo        | ThinkPad T530 2429C54       | [e100864771](https://linux-hardware.org/?probe=e100864771) | Jan 02, 2020 |
| Timi          | TM1709                      | [3914d93846](https://linux-hardware.org/?probe=3914d93846) | Dec 29, 2019 |
| HUAWEI        | WRT-WX9                     | [895ba48236](https://linux-hardware.org/?probe=895ba48236) | Dec 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [79fd5db054](https://linux-hardware.org/?probe=79fd5db054) | Dec 28, 2019 |
| MECHREVO      | Z2 Air Series GK5CP5X       | [9959b07810](https://linux-hardware.org/?probe=9959b07810) | Dec 28, 2019 |
| Dell          | Latitude 7300               | [f576ddf5dc](https://linux-hardware.org/?probe=f576ddf5dc) | Dec 25, 2019 |
| HUAWEI        | KPRC-WX0                    | [53631f5f96](https://linux-hardware.org/?probe=53631f5f96) | Dec 20, 2019 |
| HUAWEI        | KPRC-WX0                    | [243373ad36](https://linux-hardware.org/?probe=243373ad36) | Dec 19, 2019 |
| Timi          | TM1701                      | [4dcfeff869](https://linux-hardware.org/?probe=4dcfeff869) | Dec 19, 2019 |
| Timi          | TM1701                      | [452b0f742b](https://linux-hardware.org/?probe=452b0f742b) | Dec 19, 2019 |
| Lenovo        | Legion Y9000X 2020 81TH     | [dbca41493b](https://linux-hardware.org/?probe=dbca41493b) | Dec 16, 2019 |
| Dell          | Latitude E7450              | [611a318d07](https://linux-hardware.org/?probe=611a318d07) | Dec 14, 2019 |
| HUAWEI        | KPL-W0X                     | [85df07509c](https://linux-hardware.org/?probe=85df07509c) | Dec 13, 2019 |
| Lenovo        | Legion Y9000X 2020 81TH     | [626a3add4b](https://linux-hardware.org/?probe=626a3add4b) | Dec 09, 2019 |
| Lenovo        | ThinkPad T440s 20AQS0110... | [7d62d9cb36](https://linux-hardware.org/?probe=7d62d9cb36) | Dec 06, 2019 |
| Dell          | Inspiron 5498               | [6028d35682](https://linux-hardware.org/?probe=6028d35682) | Dec 03, 2019 |
| Lenovo        | ThinkPad X220 Tablet 429... | [73176f470c](https://linux-hardware.org/?probe=73176f470c) | Nov 24, 2019 |
| Lenovo        | XiaoXin Air 15IKBR 81GY     | [772f437ade](https://linux-hardware.org/?probe=772f437ade) | Nov 22, 2019 |
| Lenovo        | ThinkPad X220 Tablet 429... | [3cb609415c](https://linux-hardware.org/?probe=3cb609415c) | Nov 17, 2019 |
| HP            | OMEN by Laptop 17-cb0xxx    | [8295b3db5f](https://linux-hardware.org/?probe=8295b3db5f) | Nov 13, 2019 |
| HP            | Notebook                    | [4aae147ff7](https://linux-hardware.org/?probe=4aae147ff7) | Nov 01, 2019 |
| Lenovo        | ThinkPad T470 20HDA01FCD    | [83338c47ea](https://linux-hardware.org/?probe=83338c47ea) | Oct 19, 2019 |
| Dell          | Inspiron 3541               | [91758c6727](https://linux-hardware.org/?probe=91758c6727) | Oct 19, 2019 |
| Lenovo        | ThinkPad T470 20HDA01FCD    | [6d6e604144](https://linux-hardware.org/?probe=6d6e604144) | Oct 18, 2019 |
| ASUSTek       | X455LD                      | [33104ec50e](https://linux-hardware.org/?probe=33104ec50e) | Oct 17, 2019 |
| ASUSTek       | P2440UQ                     | [e75ef73723](https://linux-hardware.org/?probe=e75ef73723) | Oct 15, 2019 |
| Sony          | VGN-TZ37N_X                 | [7b4b0311ea](https://linux-hardware.org/?probe=7b4b0311ea) | Oct 07, 2019 |
| Dell          | Latitude E4200              | [1e42f988c0](https://linux-hardware.org/?probe=1e42f988c0) | Oct 05, 2019 |
| Sony          | VGN-TZ37N_X                 | [7fb842e685](https://linux-hardware.org/?probe=7fb842e685) | Oct 05, 2019 |
| GPD           | MicroPC                     | [8fc0176f69](https://linux-hardware.org/?probe=8fc0176f69) | Sep 28, 2019 |
| H3C           | C100                        | [ffeae72515](https://linux-hardware.org/?probe=ffeae72515) | Sep 25, 2019 |
| Unknown       | Unknown                     | [4f9b8fb05a](https://linux-hardware.org/?probe=4f9b8fb05a) | Sep 05, 2019 |
| Dell          | Precision 7540              | [840094a0e1](https://linux-hardware.org/?probe=840094a0e1) | Aug 27, 2019 |
| Dell          | Precision 7540              | [da3219e516](https://linux-hardware.org/?probe=da3219e516) | Aug 22, 2019 |
| HP            | OMEN by Laptop              | [faa579ff30](https://linux-hardware.org/?probe=faa579ff30) | Aug 22, 2019 |
| Lenovo        | ThinkPad T480 20L5001YCD    | [7d7e6ad5d5](https://linux-hardware.org/?probe=7d7e6ad5d5) | Aug 21, 2019 |
| Acer          | Aspire V3-571G              | [e95e422e8a](https://linux-hardware.org/?probe=e95e422e8a) | Aug 15, 2019 |
| Apple         | MacBookAir7,2               | [da4eaeda69](https://linux-hardware.org/?probe=da4eaeda69) | Aug 02, 2019 |
| Apple         | MacBookAir7,2               | [58d8b334ea](https://linux-hardware.org/?probe=58d8b334ea) | Aug 02, 2019 |
| Dell          | Precision 5530              | [23f5fb44a9](https://linux-hardware.org/?probe=23f5fb44a9) | Jul 31, 2019 |
| HP            | OMEN by Laptop 15-ce0xx     | [6e93995c1c](https://linux-hardware.org/?probe=6e93995c1c) | Jul 25, 2019 |
| HP            | OMEN by Laptop 15-ce0xx     | [04b0989528](https://linux-hardware.org/?probe=04b0989528) | Jul 25, 2019 |
| HP            | OMEN by Laptop 15-ce0xx     | [565953b703](https://linux-hardware.org/?probe=565953b703) | Jul 24, 2019 |
| HP            | OMEN by Laptop 15-ce0xx     | [a6db64d021](https://linux-hardware.org/?probe=a6db64d021) | Jul 24, 2019 |
| ASUSTek       | Zephyrus S GX531GW_GX531... | [383a34edd1](https://linux-hardware.org/?probe=383a34edd1) | Jul 23, 2019 |
| HP            | ProBook 455R G6             | [0d375562bd](https://linux-hardware.org/?probe=0d375562bd) | Jul 17, 2019 |
| HP            | ProBook 455R G6             | [12d1faa353](https://linux-hardware.org/?probe=12d1faa353) | Jul 17, 2019 |
| Lenovo        | M40-70 20445                | [afd92bf265](https://linux-hardware.org/?probe=afd92bf265) | Jul 15, 2019 |
| Alienware     | 17                          | [d5269a87b6](https://linux-hardware.org/?probe=d5269a87b6) | Jul 10, 2019 |
| Dell          | Latitude 7390               | [dbb0ffdb96](https://linux-hardware.org/?probe=dbb0ffdb96) | Jul 07, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4b9beb25c2](https://linux-hardware.org/?probe=4b9beb25c2) | Jul 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [af9708b601](https://linux-hardware.org/?probe=af9708b601) | Jul 03, 2019 |
| Lenovo        | ThinkPad E485 20KUA00FCD    | [12b55814de](https://linux-hardware.org/?probe=12b55814de) | Jun 30, 2019 |
| Acer          | Aspire V3-571G              | [b2644c9243](https://linux-hardware.org/?probe=b2644c9243) | Jun 30, 2019 |
| Lenovo        | ThinkPad Edge E531 68851... | [c25904b3ca](https://linux-hardware.org/?probe=c25904b3ca) | Jun 27, 2019 |
| Lenovo        | IdeaPad Y430 20005          | [5988593465](https://linux-hardware.org/?probe=5988593465) | Jun 21, 2019 |
| Dell          | Inspiron 5488               | [1e82deb58e](https://linux-hardware.org/?probe=1e82deb58e) | Jun 20, 2019 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | [f7a1ce2a5b](https://linux-hardware.org/?probe=f7a1ce2a5b) | Jun 15, 2019 |
| Lenovo        | ThinkPad T400 276711U       | [3a3a57b619](https://linux-hardware.org/?probe=3a3a57b619) | Jun 14, 2019 |
| Timi          | TM1701                      | [cde89e0f6e](https://linux-hardware.org/?probe=cde89e0f6e) | Jun 13, 2019 |
| Lenovo        | ZHAOYANG E42-80 80T9        | [bd7312440f](https://linux-hardware.org/?probe=bd7312440f) | Jun 13, 2019 |
| BenQ          | Joybook R43                 | [f367ae30d1](https://linux-hardware.org/?probe=f367ae30d1) | May 27, 2019 |
| MECHREVO      | X6Ti Series                 | [c27e2b94d0](https://linux-hardware.org/?probe=c27e2b94d0) | May 23, 2019 |
| HP            | EliteBook 8770w             | [ea9a7cc6f1](https://linux-hardware.org/?probe=ea9a7cc6f1) | May 15, 2019 |
| Dell          | Inspiron 3568               | [fb4851964c](https://linux-hardware.org/?probe=fb4851964c) | May 14, 2019 |
| Unknown       | Unknown                     | [f00e135a18](https://linux-hardware.org/?probe=f00e135a18) | May 07, 2019 |
| HP            | ENVY Laptop 13-ad1xx        | [62c7769c30](https://linux-hardware.org/?probe=62c7769c30) | May 06, 2019 |
| HP            | EliteBook 8770w             | [06ce50566b](https://linux-hardware.org/?probe=06ce50566b) | May 06, 2019 |
| Lenovo        | IdeaPad Y470 20090          | [df1a1447c6](https://linux-hardware.org/?probe=df1a1447c6) | May 05, 2019 |
| Lenovo        | ZHAOYANG E40-70 80EQ003R... | [0a41151a39](https://linux-hardware.org/?probe=0a41151a39) | May 01, 2019 |
| Dell          | Precision 5510              | [37725757fc](https://linux-hardware.org/?probe=37725757fc) | Apr 28, 2019 |
| Dell          | Precision 5510              | [77456e54b0](https://linux-hardware.org/?probe=77456e54b0) | Apr 28, 2019 |
| Lenovo        | ZHAOYANG E40-70 80EQ003R... | [1b42c99fc5](https://linux-hardware.org/?probe=1b42c99fc5) | Apr 15, 2019 |
| Lenovo        | ZHAOYANG E40-70 80EQ003R... | [d69b467ad1](https://linux-hardware.org/?probe=d69b467ad1) | Apr 12, 2019 |
| Lenovo        | ZHAOYANG E42-80 80T9        | [cd29b46afd](https://linux-hardware.org/?probe=cd29b46afd) | Apr 07, 2019 |
| Dell          | Inspiron 7447               | [ecb26ec38f](https://linux-hardware.org/?probe=ecb26ec38f) | Apr 01, 2019 |
| Lenovo        | ThinkPad R400 7445A64       | [c5fb273856](https://linux-hardware.org/?probe=c5fb273856) | Mar 31, 2019 |
| Timi          | TM1801                      | [abab034f2c](https://linux-hardware.org/?probe=abab034f2c) | Mar 31, 2019 |
| Lenovo        | ThinkPad R400 7445A64       | [ca66ac8ff7](https://linux-hardware.org/?probe=ca66ac8ff7) | Mar 31, 2019 |
| MSI           | GL62 6QF                    | [a8aec7c577](https://linux-hardware.org/?probe=a8aec7c577) | Mar 31, 2019 |
| Lenovo        | ThinkPad P50 20EQS0UP00     | [c30803f7e0](https://linux-hardware.org/?probe=c30803f7e0) | Mar 31, 2019 |
| Lenovo        | ThinkPad P50 20EQS0UP00     | [723ee99eb3](https://linux-hardware.org/?probe=723ee99eb3) | Mar 31, 2019 |
| Dell          | Latitude E5420              | [d53b90fc99](https://linux-hardware.org/?probe=d53b90fc99) | Mar 30, 2019 |
| Dell          | Latitude E5420              | [19583c2aa2](https://linux-hardware.org/?probe=19583c2aa2) | Mar 29, 2019 |
| HASEE Comp... | CN17S                       | [5d40a7ddb4](https://linux-hardware.org/?probe=5d40a7ddb4) | Mar 17, 2019 |
| ASUSTek       | G501VW                      | [66160704ce](https://linux-hardware.org/?probe=66160704ce) | Mar 15, 2019 |
| Dell          | Inspiron 15 7000 Gaming     | [f8e464a0c0](https://linux-hardware.org/?probe=f8e464a0c0) | Feb 22, 2019 |
| Notebook      | P95_HR                      | [c8a8910a82](https://linux-hardware.org/?probe=c8a8910a82) | Feb 21, 2019 |
| Toshiba       | Satellite L855              | [2393db4d67](https://linux-hardware.org/?probe=2393db4d67) | Feb 19, 2019 |
| Lenovo        | Unknown                     | [433ec22487](https://linux-hardware.org/?probe=433ec22487) | Jan 07, 2019 |
| Lenovo        | Unknown                     | [e43d9001ec](https://linux-hardware.org/?probe=e43d9001ec) | Jan 07, 2019 |
| ASUSTek       | UX31E                       | [2333e930af](https://linux-hardware.org/?probe=2333e930af) | Dec 06, 2018 |
| Timi          | TM1709                      | [c8d28d98f3](https://linux-hardware.org/?probe=c8d28d98f3) | Dec 04, 2018 |
| HASEE Comp... | P870TM_TM1                  | [a7db7c544f](https://linux-hardware.org/?probe=a7db7c544f) | Nov 26, 2018 |
| Timi          | TM1604                      | [09435f5ab9](https://linux-hardware.org/?probe=09435f5ab9) | Nov 26, 2018 |
| HASEE Comp... | P870TM_TM1                  | [8ba4b8de88](https://linux-hardware.org/?probe=8ba4b8de88) | Nov 23, 2018 |
| HASEE Comp... | P870TM_TM1                  | [93547de344](https://linux-hardware.org/?probe=93547de344) | Nov 23, 2018 |
| Fujitsu       | LIFEBOOK U2010              | [c4e618e233](https://linux-hardware.org/?probe=c4e618e233) | Nov 01, 2018 |
| Dell          | Inspiron 11-3157            | [22a545025c](https://linux-hardware.org/?probe=22a545025c) | Oct 29, 2018 |
| MSI           | GE60 0NC\0ND                | [4500f40ba8](https://linux-hardware.org/?probe=4500f40ba8) | Oct 26, 2018 |
| MSI           | GE60 0NC\0ND                | [50d4655cc8](https://linux-hardware.org/?probe=50d4655cc8) | Oct 26, 2018 |
| Lenovo        | ThinkPad Edge E431 62771... | [c843257cd9](https://linux-hardware.org/?probe=c843257cd9) | Oct 26, 2018 |
| Lenovo        | ThinkPad Edge E431 62771... | [b79afee742](https://linux-hardware.org/?probe=b79afee742) | Oct 26, 2018 |
| Lenovo        | B450 1S16800336200F7        | [23ed383b90](https://linux-hardware.org/?probe=23ed383b90) | Sep 25, 2018 |
| Lenovo        | ThinkPad X240 20AMS0KG00    | [1069f23a4c](https://linux-hardware.org/?probe=1069f23a4c) | Jul 03, 2018 |
| Dell          | Inspiron 3559               | [b3ad3b61ac](https://linux-hardware.org/?probe=b3ad3b61ac) | Jun 03, 2018 |
| Dell          | Inspiron 3559               | [15b2cb5350](https://linux-hardware.org/?probe=15b2cb5350) | May 02, 2018 |
| Dell          | Inspiron 3559               | [d068125f3c](https://linux-hardware.org/?probe=d068125f3c) | Apr 28, 2018 |
| Dell          | Inspiron 3559               | [5d77eff84b](https://linux-hardware.org/?probe=5d77eff84b) | Apr 28, 2018 |
| ASUSTek       | K56CB                       | [c2992a0291](https://linux-hardware.org/?probe=c2992a0291) | Apr 14, 2018 |
| Dell          | Inspiron 3559               | [f1d49b5cb9](https://linux-hardware.org/?probe=f1d49b5cb9) | Feb 25, 2018 |
| Lenovo        | Erazer Y40-70 20407         | [3aaa7ea4d0](https://linux-hardware.org/?probe=3aaa7ea4d0) | Feb 12, 2018 |
| Dell          | Inspiron 7560               | [49389100fc](https://linux-hardware.org/?probe=49389100fc) | Apr 15, 2017 |
| MSI           | GS60 6QC                    | [404f145917](https://linux-hardware.org/?probe=404f145917) | May 18, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 91        | 16.43%  |
| Ubuntu 18.04                 | 68        | 12.27%  |
| Arch                         | 26        | 4.69%   |
| Debian 11                    | 21        | 3.79%   |
| OpenMandriva 4.2             | 14        | 2.53%   |
| Arch Rolling                 | 13        | 2.35%   |
| Manjaro                      | 12        | 2.17%   |
| Ubuntu 22.04                 | 11        | 1.99%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 1.81%   |
| Gentoo 2.7                   | 10        | 1.81%   |
| Debian 10                    | 10        | 1.81%   |
| Ubuntu 21.10                 | 9         | 1.62%   |
| Ubuntu 19.04                 | 9         | 1.62%   |
| OpenMandriva 4.3             | 9         | 1.62%   |
| Linux Mint 20.1              | 9         | 1.62%   |
| KDE neon 20.04               | 9         | 1.62%   |
| Fedora 33                    | 9         | 1.62%   |
| UOS 20                       | 8         | 1.44%   |
| Linux Mint 20                | 7         | 1.26%   |
| Gentoo 2.6                   | 7         | 1.26%   |
| Fedora 35                    | 7         | 1.26%   |
| Debian Testing               | 7         | 1.26%   |
| Ubuntu 19.10                 | 6         | 1.08%   |
| Ubuntu 16.04                 | 6         | 1.08%   |
| ROSA R10                     | 6         | 1.08%   |
| ArcoLinux Rolling            | 6         | 1.08%   |
| Ubuntu 21.04                 | 5         | 0.9%    |
| Manjaro 18.1.4               | 5         | 0.9%    |
| Linux Mint 20.3              | 5         | 0.9%    |
| Fedora 34                    | 5         | 0.9%    |
| Ubuntu 20.10                 | 4         | 0.72%   |
| Fedora 32                    | 4         | 0.72%   |
| Fedora 31                    | 4         | 0.72%   |
| CentOS 8                     | 4         | 0.72%   |
| OpenMandriva 4.50            | 3         | 0.54%   |
| Manjaro 21.2.6               | 3         | 0.54%   |
| Manjaro 20.2                 | 3         | 0.54%   |
| Linux Mint 20.2              | 3         | 0.54%   |
| Kubuntu 20.04                | 3         | 0.54%   |
| CentOS 7                     | 3         | 0.54%   |
| BlackPanther 18.1            | 3         | 0.54%   |
| Xubuntu 20.04                | 2         | 0.36%   |
| Pop!_OS 21.10                | 2         | 0.36%   |
| Pop!_OS 20.10                | 2         | 0.36%   |
| Pop!_OS 20.04                | 2         | 0.36%   |
| MX 19                        | 2         | 0.36%   |
| Manjaro 21.2.5               | 2         | 0.36%   |
| Manjaro 21.0.5               | 2         | 0.36%   |
| Manjaro 20.2.1               | 2         | 0.36%   |
| Manjaro 20.0                 | 2         | 0.36%   |
| LMDE 4                       | 2         | 0.36%   |
| Kylin V10.1                  | 2         | 0.36%   |
| Kylin V10                    | 2         | 0.36%   |
| Kubuntu 22.04                | 2         | 0.36%   |
| Kubuntu 21.04                | 2         | 0.36%   |
| Guix                         | 2         | 0.36%   |
| Gentoo 2.8                   | 2         | 0.36%   |
| Fedora 30                    | 2         | 0.36%   |
| Deepin 20                    | 2         | 0.36%   |
| Xubuntu 18.04                | 1         | 0.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 205       | 37.68%  |
| Manjaro      | 42        | 7.72%   |
| Arch         | 40        | 7.35%   |
| Debian       | 38        | 6.99%   |
| Fedora       | 30        | 5.51%   |
| OpenMandriva | 26        | 4.78%   |
| Linux Mint   | 24        | 4.41%   |
| Gentoo       | 18        | 3.31%   |
| Deepin       | 16        | 2.94%   |
| openSUSE     | 13        | 2.39%   |
| KDE neon     | 10        | 1.84%   |
| Kubuntu      | 9         | 1.65%   |
| CentOS       | 8         | 1.47%   |
| ROSA         | 7         | 1.29%   |
| Pop!_OS      | 7         | 1.29%   |
| Kali         | 6         | 1.1%    |
| ArcoLinux    | 6         | 1.1%    |
| Xubuntu      | 4         | 0.74%   |
| Kylin        | 4         | 0.74%   |
| Elementary   | 4         | 0.74%   |
| Ubuntu MATE  | 3         | 0.55%   |
| BlackPanther | 3         | 0.55%   |
| MX           | 2         | 0.37%   |
| LMDE         | 2         | 0.37%   |
| Guix         | 2         | 0.37%   |
| Clear Linux  | 2         | 0.37%   |
| Ubuntu Kylin | 1         | 0.18%   |
| Trisquel     | 1         | 0.18%   |
| Solus        | 1         | 0.18%   |
| Rocky Linux  | 1         | 0.18%   |
| RHEL         | 1         | 0.18%   |
| PureOS       | 1         | 0.18%   |
| Openeuler    | 1         | 0.18%   |
| Lubuntu      | 1         | 0.18%   |
| Garuda Linux | 1         | 0.18%   |
| Endless      | 1         | 0.18%   |
| DSM          | 1         | 0.18%   |
| Atz          | 1         | 0.18%   |
| Artix        | 1         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 13        | 2.17%   |
| 5.4.0-42-generic         | 11        | 1.84%   |
| 5.16.7-desktop-1omv4003  | 9         | 1.51%   |
| 5.10.0-8-amd64           | 9         | 1.51%   |
| 5.13.0-30-generic        | 6         | 1%      |
| 4.18.0-25-generic        | 6         | 1%      |
| 5.13.0-35-generic        | 5         | 0.84%   |
| 5.8.0-55-generic         | 4         | 0.67%   |
| 5.4.0-53-generic         | 4         | 0.67%   |
| 5.4.0-48-generic         | 4         | 0.67%   |
| 5.4.0-33-generic         | 4         | 0.67%   |
| 5.4.0-29-generic         | 4         | 0.67%   |
| 5.4.0-107-generic        | 4         | 0.67%   |
| 5.3.0-46-generic         | 4         | 0.67%   |
| 5.15.0-2-amd64           | 4         | 0.67%   |
| 5.13.0-28-generic        | 4         | 0.67%   |
| 5.11.0-34-generic        | 4         | 0.67%   |
| 5.11.0-25-generic        | 4         | 0.67%   |
| 5.10.41-amd64-desktop    | 4         | 0.67%   |
| 5.10.0-9-amd64           | 4         | 0.67%   |
| 5.10.0-1011-oem          | 4         | 0.67%   |
| 5.0.0-13-generic         | 4         | 0.67%   |
| 5.9.16-1-MANJARO         | 3         | 0.5%    |
| 5.8.0-50-generic         | 3         | 0.5%    |
| 5.6.14-desktop-2bP       | 3         | 0.5%    |
| 5.4.2-1-MANJARO          | 3         | 0.5%    |
| 5.4.0-74-generic         | 3         | 0.5%    |
| 5.4.0-73-generic         | 3         | 0.5%    |
| 5.4.0-70-generic         | 3         | 0.5%    |
| 5.4.0-58-generic         | 3         | 0.5%    |
| 5.4.0-52-generic         | 3         | 0.5%    |
| 5.4.0-47-generic         | 3         | 0.5%    |
| 5.4.0-39-generic         | 3         | 0.5%    |
| 5.3.0-28-generic         | 3         | 0.5%    |
| 5.3.0-24-generic         | 3         | 0.5%    |
| 5.15.0-27-generic        | 3         | 0.5%    |
| 5.15.0-25-generic        | 3         | 0.5%    |
| 5.13.0-41-generic        | 3         | 0.5%    |
| 5.13.0-40-generic        | 3         | 0.5%    |
| 5.13.0-39-generic        | 3         | 0.5%    |
| 5.12.4-desktop-1omv4050  | 3         | 0.5%    |
| 5.11.0-43-generic        | 3         | 0.5%    |
| 5.11.0-37-generic        | 3         | 0.5%    |
| 5.11.0-36-generic        | 3         | 0.5%    |
| 5.10.60-amd64-desktop    | 3         | 0.5%    |
| 5.10.36-2-MANJARO        | 3         | 0.5%    |
| 5.10.27-gentoo           | 3         | 0.5%    |
| 5.0.0-23-generic         | 3         | 0.5%    |
| 4.18.0-17-generic        | 3         | 0.5%    |
| 4.18.0-16-generic        | 3         | 0.5%    |
| 4.18.0-15-generic        | 3         | 0.5%    |
| 4.15.0-45-generic        | 3         | 0.5%    |
| 5.8.3-arch1-1            | 2         | 0.33%   |
| 5.8.15-301.fc33.x86_64   | 2         | 0.33%   |
| 5.8.0-63-generic         | 2         | 0.33%   |
| 5.8.0-59-generic         | 2         | 0.33%   |
| 5.8.0-48-generic         | 2         | 0.33%   |
| 5.8.0-43-generic         | 2         | 0.33%   |
| 5.8.0-050800-generic     | 2         | 0.33%   |
| 5.7.7-amd64-desktop      | 2         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 80        | 13.82%  |
| 5.10.0  | 34        | 5.87%   |
| 5.13.0  | 31        | 5.35%   |
| 5.11.0  | 31        | 5.35%   |
| 5.8.0   | 27        | 4.66%   |
| 4.15.0  | 26        | 4.49%   |
| 4.18.0  | 25        | 4.32%   |
| 5.3.0   | 23        | 3.97%   |
| 5.15.0  | 16        | 2.76%   |
| 5.0.0   | 16        | 2.76%   |
| 5.10.14 | 13        | 2.25%   |
| 4.19.0  | 12        | 2.07%   |
| 5.16.7  | 10        | 1.73%   |
| 5.6.14  | 5         | 0.86%   |
| 5.9.16  | 4         | 0.69%   |
| 5.6.0   | 4         | 0.69%   |
| 5.16.0  | 4         | 0.69%   |
| 5.10.41 | 4         | 0.69%   |
| 5.10.27 | 4         | 0.69%   |
| 4.9.60  | 4         | 0.69%   |
| 5.9.11  | 3         | 0.52%   |
| 5.4.2   | 3         | 0.52%   |
| 5.4.18  | 3         | 0.52%   |
| 5.17.5  | 3         | 0.52%   |
| 5.17.1  | 3         | 0.52%   |
| 5.14.0  | 3         | 0.52%   |
| 5.12.4  | 3         | 0.52%   |
| 5.11.12 | 3         | 0.52%   |
| 5.10.60 | 3         | 0.52%   |
| 5.10.36 | 3         | 0.52%   |
| 3.10.0  | 3         | 0.52%   |
| 5.8.9   | 2         | 0.35%   |
| 5.8.3   | 2         | 0.35%   |
| 5.8.18  | 2         | 0.35%   |
| 5.8.15  | 2         | 0.35%   |
| 5.8.12  | 2         | 0.35%   |
| 5.7.7   | 2         | 0.35%   |
| 5.7.10  | 2         | 0.35%   |
| 5.5.2   | 2         | 0.35%   |
| 5.4.3   | 2         | 0.35%   |
| 5.4.23  | 2         | 0.35%   |
| 5.3.18  | 2         | 0.35%   |
| 5.3.15  | 2         | 0.35%   |
| 5.18.5  | 2         | 0.35%   |
| 5.18.1  | 2         | 0.35%   |
| 5.17.9  | 2         | 0.35%   |
| 5.17.4  | 2         | 0.35%   |
| 5.16.11 | 2         | 0.35%   |
| 5.15.6  | 2         | 0.35%   |
| 5.15.5  | 2         | 0.35%   |
| 5.15.32 | 2         | 0.35%   |
| 5.15.28 | 2         | 0.35%   |
| 5.15.23 | 2         | 0.35%   |
| 5.15.12 | 2         | 0.35%   |
| 5.14.9  | 2         | 0.35%   |
| 5.14.6  | 2         | 0.35%   |
| 5.14.16 | 2         | 0.35%   |
| 5.14.14 | 2         | 0.35%   |
| 5.14.12 | 2         | 0.35%   |
| 5.14.10 | 2         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 100       | 17.45%  |
| 5.10    | 72        | 12.57%  |
| 5.11    | 44        | 7.68%   |
| 5.8     | 40        | 6.98%   |
| 5.15    | 39        | 6.81%   |
| 5.13    | 37        | 6.46%   |
| 5.3     | 30        | 5.24%   |
| 4.18    | 27        | 4.71%   |
| 4.15    | 26        | 4.54%   |
| 5.16    | 20        | 3.49%   |
| 5.0     | 18        | 3.14%   |
| 5.14    | 16        | 2.79%   |
| 4.19    | 15        | 2.62%   |
| 5.6     | 13        | 2.27%   |
| 5.17    | 13        | 2.27%   |
| 5.9     | 10        | 1.75%   |
| 5.12    | 10        | 1.75%   |
| 5.7     | 8         | 1.4%    |
| 5.5     | 6         | 1.05%   |
| 4.9     | 6         | 1.05%   |
| 5.18    | 4         | 0.7%    |
| 3.10    | 4         | 0.7%    |
| 5.1     | 3         | 0.52%   |
| 4.14    | 2         | 0.35%   |
| 5.2     | 1         | 0.17%   |
| 4.6     | 1         | 0.17%   |
| 4.4     | 1         | 0.17%   |
| 4.20    | 1         | 0.17%   |
| 4.17    | 1         | 0.17%   |
| 4.13    | 1         | 0.17%   |
| 4.12    | 1         | 0.17%   |
| 4.10    | 1         | 0.17%   |
| 4.1     | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 524       | 98.5%   |
| i686    | 6         | 1.13%   |
| aarch64 | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 230       | 42.05%  |
| KDE5            | 93        | 17%     |
| Unknown         | 76        | 13.89%  |
| XFCE            | 32        | 5.85%   |
| KDE             | 24        | 4.39%   |
| X-Cinnamon      | 23        | 4.2%    |
| Deepin          | 17        | 3.11%   |
| i3              | 12        | 2.19%   |
| MATE            | 9         | 1.65%   |
| Pantheon        | 4         | 0.73%   |
| UKUI            | 3         | 0.55%   |
| LXDE            | 3         | 0.55%   |
| KDE4            | 3         | 0.55%   |
| GNOME Flashback | 3         | 0.55%   |
| Cinnamon        | 3         | 0.55%   |
| Budgie          | 3         | 0.55%   |
| Unity           | 2         | 0.37%   |
| GNUstep         | 2         | 0.37%   |
| GNOME Classic   | 2         | 0.37%   |
| xmonad          | 1         | 0.18%   |
| LXQt            | 1         | 0.18%   |
| bspwm           | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 422       | 77.29%  |
| Wayland | 71        | 13%     |
| Unknown | 42        | 7.69%   |
| Tty     | 11        | 2.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 233       | 42.75%  |
| GDM     | 92        | 16.88%  |
| SDDM    | 87        | 15.96%  |
| GDM3    | 47        | 8.62%   |
| LightDM | 46        | 8.44%   |
| TDM     | 35        | 6.42%   |
| KDM     | 2         | 0.37%   |
| XDM     | 1         | 0.18%   |
| SLiM    | 1         | 0.18%   |
| LXDM    | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| zh_CN   | 226       | 41.77%  |
| en_US   | 201       | 37.15%  |
| Unknown | 88        | 16.27%  |
| en_HK   | 6         | 1.11%   |
| en_GB   | 5         | 0.92%   |
| mn_CN   | 4         | 0.74%   |
| en_AU   | 2         | 0.37%   |
| th_TH   | 1         | 0.18%   |
| POSIX   | 1         | 0.18%   |
| ja_JP   | 1         | 0.18%   |
| fr_FR   | 1         | 0.18%   |
| en_ZA   | 1         | 0.18%   |
| de_DE   | 1         | 0.18%   |
| C.UTF8  | 1         | 0.18%   |
| C       | 1         | 0.18%   |
| .en_US  | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 373       | 68.82%  |
| BIOS | 169       | 31.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 432       | 79.85%  |
| Btrfs   | 46        | 8.5%    |
| Overlay | 21        | 3.88%   |
| Xfs     | 18        | 3.33%   |
| Unknown | 17        | 3.14%   |
| Zfs     | 3         | 0.55%   |
| F2fs    | 3         | 0.55%   |
| Tmpfs   | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 267       | 49.72%  |
| Unknown | 232       | 43.2%   |
| MBR     | 38        | 7.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 480       | 88.4%   |
| Yes       | 63        | 11.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 302       | 56.55%  |
| Yes       | 232       | 43.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 186       | 35.03%  |
| Dell                           | 72        | 13.56%  |
| Hewlett-Packard                | 55        | 10.36%  |
| HUAWEI                         | 39        | 7.34%   |
| Timi                           | 28        | 5.27%   |
| ASUSTek Computer               | 24        | 4.52%   |
| Acer                           | 21        | 3.95%   |
| HASEE Computer                 | 12        | 2.26%   |
| MSI                            | 11        | 2.07%   |
| Apple                          | 9         | 1.69%   |
| Unknown                        | 7         | 1.32%   |
| Toshiba                        | 6         | 1.13%   |
| Sony                           | 6         | 1.13%   |
| MECHREVO                       | 6         | 1.13%   |
| GPD                            | 4         | 0.75%   |
| Samsung Electronics            | 3         | 0.56%   |
| Notebook                       | 3         | 0.56%   |
| Google                         | 3         | 0.56%   |
| Fujitsu                        | 3         | 0.56%   |
| Terrans Force                  | 2         | 0.38%   |
| LG Electronics                 | 2         | 0.38%   |
| Jumper                         | 2         | 0.38%   |
| IPASON                         | 2         | 0.38%   |
| Intel                          | 2         | 0.38%   |
| Insyde                         | 2         | 0.38%   |
| Gigabyte Technology            | 2         | 0.38%   |
| Alienware                      | 2         | 0.38%   |
| TR                             | 1         | 0.19%   |
| Teclast                        | 1         | 0.19%   |
| Synology                       | 1         | 0.19%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.19%   |
| Schenker                       | 1         | 0.19%   |
| Razer                          | 1         | 0.19%   |
| Jemper                         | 1         | 0.19%   |
| Intel Client Systems           | 1         | 0.19%   |
| IBM                            | 1         | 0.19%   |
| HONOR                          | 1         | 0.19%   |
| Hampoo                         | 1         | 0.19%   |
| H3C                            | 1         | 0.19%   |
| GXNOVA Computer                | 1         | 0.19%   |
| GreatWall                      | 1         | 0.19%   |
| Clevo                          | 1         | 0.19%   |
| BenQ                           | 1         | 0.19%   |
| AVITA                          | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 13        | 2.45%   |
| HUAWEI HLY-WX9XX                     | 8         | 1.51%   |
| Timi TM1701                          | 5         | 0.94%   |
| Lenovo Legion R9000P2021H 82JQ       | 5         | 0.94%   |
| Lenovo Legion R7000 2020 82B6        | 5         | 0.94%   |
| Lenovo ThinkBook 15p Gen 2 21B1      | 4         | 0.75%   |
| HUAWEI BOHK-WAX9X                    | 4         | 0.75%   |
| Timi TM1709                          | 3         | 0.56%   |
| Timi RedmiBook Pro 15S               | 3         | 0.56%   |
| Timi RedmiBook 14 II                 | 3         | 0.56%   |
| Lenovo ZHAOYANG K4e-ITL 82F8         | 3         | 0.56%   |
| Lenovo XiaoXinPro-13IML 2019 81XB    | 3         | 0.56%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN    | 3         | 0.56%   |
| Lenovo XiaoXin-15ARE 2020 81YR       | 3         | 0.56%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 3         | 0.56%   |
| Lenovo Legion Y7000 81FW             | 3         | 0.56%   |
| HUAWEI NBLK-WAX9X                    | 3         | 0.56%   |
| HUAWEI KPRC-WX0                      | 3         | 0.56%   |
| HUAWEI KPR-WX9                       | 3         | 0.56%   |
| HUAWEI KPL-W0X                       | 3         | 0.56%   |
| HP ENVY Laptop 13-ad1xx              | 3         | 0.56%   |
| Dell XPS 15 9570                     | 3         | 0.56%   |
| Acer Swift SF314-42                  | 3         | 0.56%   |
| Timi TM1613                          | 2         | 0.38%   |
| Timi Mi Laptop Pro 15                | 2         | 0.38%   |
| Lenovo ZHAOYANG E42-80 80T9          | 2         | 0.38%   |
| Lenovo Yoga 14sARH 2021 82LB         | 2         | 0.38%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM    | 2         | 0.38%   |
| Lenovo ThinkPad T14 Gen 1 20UD0004CD | 2         | 0.38%   |
| Lenovo ThinkPad E555 20DHA01MCD      | 2         | 0.38%   |
| Lenovo ThinkBook 14p Gen 2 20YN      | 2         | 0.38%   |
| Lenovo Legion Y9000X 2020 81TH       | 2         | 0.38%   |
| Lenovo Legion R7000P2020H 82GR       | 2         | 0.38%   |
| Lenovo IdeaPad Y470 20090            | 2         | 0.38%   |
| Jumper EZbook                        | 2         | 0.38%   |
| HUAWEI WRT-WX9                       | 2         | 0.38%   |
| HUAWEI KLVL-WXX9                     | 2         | 0.38%   |
| HUAWEI HLYL-WXX9                     | 2         | 0.38%   |
| HP ZHAN 66 Pro G1                    | 2         | 0.38%   |
| HP ZHAN 66 Pro A 14 G3               | 2         | 0.38%   |
| HP ZHAN 66 Pro 15 G3                 | 2         | 0.38%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC     | 2         | 0.38%   |
| HP OMEN by Laptop 15-ce0xx           | 2         | 0.38%   |
| HP OMEN by Laptop                    | 2         | 0.38%   |
| GPD P2 MAX                           | 2         | 0.38%   |
| Google Akemi                         | 2         | 0.38%   |
| Dell XPS 13 9305                     | 2         | 0.38%   |
| Dell Precision 5510                  | 2         | 0.38%   |
| Dell Inspiron N4050                  | 2         | 0.38%   |
| Dell Inspiron 7560                   | 2         | 0.38%   |
| Dell Inspiron 7472                   | 2         | 0.38%   |
| Dell Inspiron 7447                   | 2         | 0.38%   |
| Dell Inspiron 3559                   | 2         | 0.38%   |
| Dell G3 3500                         | 2         | 0.38%   |
| Apple MacBookPro16,1                 | 2         | 0.38%   |
| Apple MacBookAir7,2                  | 2         | 0.38%   |
| Acer Swift SF314-510G                | 2         | 0.38%   |
| Acer Nitro AN515-57                  | 2         | 0.38%   |
| Acer Aspire 4752                     | 2         | 0.38%   |
| TR ThundeRobot                       | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 82        | 15.44%  |
| Lenovo Legion           | 27        | 5.08%   |
| Dell Inspiron           | 27        | 5.08%   |
| Dell Latitude           | 18        | 3.39%   |
| Unknown                 | 13        | 2.45%   |
| Lenovo ZHAOYANG         | 12        | 2.26%   |
| Lenovo ThinkBook        | 12        | 2.26%   |
| HP ZHAN                 | 11        | 2.07%   |
| HP EliteBook            | 11        | 2.07%   |
| Acer Aspire             | 11        | 2.07%   |
| Lenovo IdeaPad          | 10        | 1.88%   |
| Dell XPS                | 10        | 1.88%   |
| HP OMEN                 | 9         | 1.69%   |
| HUAWEI HLY-WX9XX        | 8         | 1.51%   |
| Dell Precision          | 8         | 1.51%   |
| Timi RedmiBook          | 7         | 1.32%   |
| HP ProBook              | 7         | 1.32%   |
| Acer Swift              | 7         | 1.32%   |
| Timi TM1701             | 5         | 0.94%   |
| Lenovo XiaoXin          | 5         | 0.94%   |
| HP ENVY                 | 5         | 0.94%   |
| Toshiba Satellite       | 4         | 0.75%   |
| HUAWEI BOHK-WAX9X       | 4         | 0.75%   |
| HP Pavilion             | 4         | 0.75%   |
| Timi TM1709             | 3         | 0.56%   |
| Timi Mi                 | 3         | 0.56%   |
| Lenovo Yoga             | 3         | 0.56%   |
| Lenovo XiaoXinPro-13IML | 3         | 0.56%   |
| Lenovo XiaoXinPro       | 3         | 0.56%   |
| Lenovo XiaoXinAir-14ARE | 3         | 0.56%   |
| Lenovo XiaoXin-15ARE    | 3         | 0.56%   |
| HUAWEI NBLK-WAX9X       | 3         | 0.56%   |
| HUAWEI KPRC-WX0         | 3         | 0.56%   |
| HUAWEI KPR-WX9          | 3         | 0.56%   |
| HUAWEI KPL-W0X          | 3         | 0.56%   |
| HP Laptop               | 3         | 0.56%   |
| Dell G3                 | 3         | 0.56%   |
| ASUS ASUS               | 3         | 0.56%   |
| Acer Nitro              | 3         | 0.56%   |
| Timi TM1613             | 2         | 0.38%   |
| MSI GS66                | 2         | 0.38%   |
| MSI GS60                | 2         | 0.38%   |
| Lenovo XiaoXinPro-13ARE | 2         | 0.38%   |
| Jumper EZbook           | 2         | 0.38%   |
| HUAWEI WRT-WX9          | 2         | 0.38%   |
| HUAWEI KLVL-WXX9        | 2         | 0.38%   |
| HUAWEI HLYL-WXX9        | 2         | 0.38%   |
| GPD P2                  | 2         | 0.38%   |
| Google Akemi            | 2         | 0.38%   |
| Fujitsu LIFEBOOK        | 2         | 0.38%   |
| Dell Vostro             | 2         | 0.38%   |
| Dell System             | 2         | 0.38%   |
| ASUS Zenbook            | 2         | 0.38%   |
| ASUS ROG                | 2         | 0.38%   |
| Apple MacBookPro16      | 2         | 0.38%   |
| Apple MacBookPro11      | 2         | 0.38%   |
| Apple MacBookAir7       | 2         | 0.38%   |
| TR ThundeRobot          | 1         | 0.19%   |
| Toshiba NB300           | 1         | 0.19%   |
| Toshiba dynabook        | 1         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 88        | 16.57%  |
| 2019 | 79        | 14.88%  |
| 2021 | 78        | 14.69%  |
| 2018 | 56        | 10.55%  |
| 2017 | 41        | 7.72%   |
| 2015 | 31        | 5.84%   |
| 2016 | 30        | 5.65%   |
| 2012 | 29        | 5.46%   |
| 2011 | 25        | 4.71%   |
| 2014 | 21        | 3.95%   |
| 2013 | 19        | 3.58%   |
| 2009 | 8         | 1.51%   |
| 2008 | 8         | 1.51%   |
| 2010 | 7         | 1.32%   |
| 2022 | 6         | 1.13%   |
| 2007 | 4         | 0.75%   |
| 2006 | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 531       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 469       | 87.34%  |
| Enabled  | 68        | 12.66%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 528       | 99.44%  |
| Yes  | 3         | 0.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 145       | 27%     |
| 16.01-24.0  | 133       | 24.77%  |
| 8.01-16.0   | 130       | 24.21%  |
| 3.01-4.0    | 60        | 11.17%  |
| 32.01-64.0  | 38        | 7.08%   |
| 1.01-2.0    | 10        | 1.86%   |
| 24.01-32.0  | 9         | 1.68%   |
| 64.01-256.0 | 6         | 1.12%   |
| 0.51-1.0    | 5         | 0.93%   |
| Unknown     | 1         | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 163       | 28.3%   |
| 2.01-3.0   | 155       | 26.91%  |
| 4.01-8.0   | 103       | 17.88%  |
| 3.01-4.0   | 92        | 15.97%  |
| 0.51-1.0   | 31        | 5.38%   |
| 8.01-16.0  | 22        | 3.82%   |
| 0.01-0.5   | 7         | 1.22%   |
| Unknown    | 2         | 0.35%   |
| 24.01-32.0 | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 341       | 63.38%  |
| 2      | 167       | 31.04%  |
| 3      | 25        | 4.65%   |
| 0      | 3         | 0.56%   |
| 4      | 2         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 457       | 85.58%  |
| Yes       | 77        | 14.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 389       | 72.98%  |
| No        | 144       | 27.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 519       | 97.74%  |
| No        | 12        | 2.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 447       | 83.86%  |
| No        | 86        | 16.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| China   | 531       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Beijing          | 94        | 16.73%  |
| Shanghai         | 48        | 8.54%   |
| Guangzhou        | 46        | 8.19%   |
| Shenzhen         | 43        | 7.65%   |
| Hangzhou         | 21        | 3.74%   |
| Chengdu          | 17        | 3.02%   |
| Wuhan            | 16        | 2.85%   |
| Xi'an            | 11        | 1.96%   |
| Nanjing          | 11        | 1.96%   |
| Tianjin          | 10        | 1.78%   |
| Xuhui            | 8         | 1.42%   |
| Nanning          | 8         | 1.42%   |
| Hefei            | 8         | 1.42%   |
| Dalian           | 8         | 1.42%   |
| Zhengzhou        | 7         | 1.25%   |
| Dongguan         | 7         | 1.25%   |
| Changsha         | 7         | 1.25%   |
| Suzhou           | 6         | 1.07%   |
| Shenyang         | 6         | 1.07%   |
| Huangpu          | 6         | 1.07%   |
| Fuzhou           | 6         | 1.07%   |
| Chongqing        | 6         | 1.07%   |
| Changchun        | 6         | 1.07%   |
| Qingdao          | 5         | 0.89%   |
| Pudong           | 5         | 0.89%   |
| Kunming          | 5         | 0.89%   |
| Xining           | 4         | 0.71%   |
| Jinan            | 4         | 0.71%   |
| Hohhot           | 4         | 0.71%   |
| Guiyang          | 4         | 0.71%   |
| Foshan           | 4         | 0.71%   |
| Xinyang          | 3         | 0.53%   |
| Xiamen           | 3         | 0.53%   |
| Taiyuan          | 3         | 0.53%   |
| Jinrongjie       | 3         | 0.53%   |
| Haidian          | 3         | 0.53%   |
| Baoqiao          | 3         | 0.53%   |
| Zhaoqing         | 2         | 0.36%   |
| Yanqing          | 2         | 0.36%   |
| Xicheng District | 2         | 0.36%   |
| Ürümqi         | 2         | 0.36%   |
| Shijiazhuang     | 2         | 0.36%   |
| Shaoxing         | 2         | 0.36%   |
| Qikeshu          | 2         | 0.36%   |
| Ningbo           | 2         | 0.36%   |
| Nanyang          | 2         | 0.36%   |
| Meizhou          | 2         | 0.36%   |
| Liuli            | 2         | 0.36%   |
| Lishui           | 2         | 0.36%   |
| Jilin City       | 2         | 0.36%   |
| Jiangmen         | 2         | 0.36%   |
| Hongkou          | 2         | 0.36%   |
| Hengshui         | 2         | 0.36%   |
| Chancheng        | 2         | 0.36%   |
| Zhongshan        | 1         | 0.18%   |
| Zhenjiang        | 1         | 0.18%   |
| Zhaojia          | 1         | 0.18%   |
| Yunnan           | 1         | 0.18%   |
| Yingchuan        | 1         | 0.18%   |
| Yan’an         | 1         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 165       | 199    | 22.73%  |
| WDC                         | 79        | 96     | 10.88%  |
| Seagate                     | 66        | 75     | 9.09%   |
| Toshiba                     | 52        | 59     | 7.16%   |
| SK hynix                    | 36        | 45     | 4.96%   |
| SanDisk                     | 35        | 42     | 4.82%   |
| Intel                       | 27        | 36     | 3.72%   |
| Unknown                     | 26        | 32     | 3.58%   |
| Micron Technology           | 19        | 19     | 2.62%   |
| HGST                        | 19        | 23     | 2.62%   |
| Plextor                     | 15        | 15     | 2.07%   |
| Kingston                    | 14        | 16     | 1.93%   |
| LITEON                      | 12        | 14     | 1.65%   |
| Lenovo                      | 9         | 12     | 1.24%   |
| Hitachi                     | 9         | 13     | 1.24%   |
| Crucial                     | 9         | 11     | 1.24%   |
| A-DATA Technology           | 8         | 11     | 1.1%    |
| Apple                       | 7         | 7      | 0.96%   |
| Silicon Motion              | 6         | 6      | 0.83%   |
| JMicron Technology          | 6         | 4      | 0.83%   |
| Unknown                     | 6         | 6      | 0.83%   |
| Transcend                   | 5         | 6      | 0.69%   |
| KIOXIA                      | 5         | 8      | 0.69%   |
| Teclast                     | 4         | 4      | 0.55%   |
| Phison                      | 4         | 5      | 0.55%   |
| Netac                       | 4         | 4      | 0.55%   |
| Hewlett-Packard             | 4         | 4      | 0.55%   |
| GALAX                       | 4         | 4      | 0.55%   |
| FORESEE                     | 4         | 6      | 0.55%   |
| External                    | 4         | 6      | 0.55%   |
| Colorful                    | 4         | 5      | 0.55%   |
| China                       | 4         | 5      | 0.55%   |
| KIOXIA-EXCERIA              | 3         | 6      | 0.41%   |
| KingSpec                    | 3         | 3      | 0.41%   |
| KINGBANK                    | 3         | 5      | 0.41%   |
| Fujitsu                     | 3         | 3      | 0.41%   |
| Phison Electronics          | 2         | 2      | 0.28%   |
| Lexar                       | 2         | 2      | 0.28%   |
| Kingchuxing                 | 2         | 2      | 0.28%   |
| Hikvision                   | 2         | 2      | 0.28%   |
| ADATA Technology            | 2         | 2      | 0.28%   |
| Xinsujie                    | 1         | 1      | 0.14%   |
| WDC WDS1                    | 1         | 1      | 0.14%   |
| WDC PC S                    | 1         | 1      | 0.14%   |
| UNIC2                       | 1         | 1      | 0.14%   |
| UMIS                        | 1         | 1      | 0.14%   |
| TurXun                      | 1         | 1      | 0.14%   |
| TU100Pro                    | 1         | 1      | 0.14%   |
| TO Exter                    | 1         | 1      | 0.14%   |
| RECADATA                    | 1         | 1      | 0.14%   |
| Q200                        | 1         | 1      | 0.14%   |
| OEM                         | 1         | 1      | 0.14%   |
| MR                          | 1         | 3      | 0.14%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.14%   |
| LuminouTek                  | 1         | 1      | 0.14%   |
| LITEONIT                    | 1         | 1      | 0.14%   |
| Lite-On                     | 1         | 1      | 0.14%   |
| LenovoSPEED                 | 1         | 1      | 0.14%   |
| Lanbo                       | 1         | 1      | 0.14%   |
| Kston                       | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB              | 20        | 2.65%   |
| Seagate ST1000LM035-1RK172 1TB            | 13        | 1.72%   |
| Samsung MZVLB512HBJQ-000L2 512GB          | 13        | 1.72%   |
| HGST HTS721010A9E630 1TB                  | 12        | 1.59%   |
| SanDisk NVMe SSD Drive 512GB              | 11        | 1.46%   |
| SK hynix NVMe SSD Drive 512GB             | 9         | 1.19%   |
| Samsung NVMe SSD Drive 1024GB             | 9         | 1.19%   |
| Samsung NVMe SSD Drive 256GB              | 8         | 1.06%   |
| Samsung MZVLB512HBJQ-000L7 512GB          | 8         | 1.06%   |
| Samsung MZVLB512HAJQ-00000 512GB          | 8         | 1.06%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD       | 7         | 0.93%   |
| Seagate ST500LT012-1DG142 500GB           | 7         | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB            | 7         | 0.93%   |
| Seagate ST500LM021-1KJ152 500GB           | 6         | 0.79%   |
| Seagate ST2000LM007-1R8174 2TB            | 6         | 0.79%   |
| Plextor PX-128M6S 128GB SSD               | 6         | 0.79%   |
| Unknown                                   | 6         | 0.79%   |
| Toshiba MQ01ABD100 1TB                    | 5         | 0.66%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB    | 5         | 0.66%   |
| Samsung SSD 860 EVO 500GB                 | 5         | 0.66%   |
| Intel SSDPEKNW010T8 1TB                   | 5         | 0.66%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 4         | 0.53%   |
| Toshiba NVMe SSD Drive 512GB              | 4         | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 4         | 0.53%   |
| Samsung MZVLB1T0HBLR-000L2 1TB            | 4         | 0.53%   |
| Samsung MZNLH512HALU-00000 512GB SSD      | 4         | 0.53%   |
| Samsung MZ7KM480HMHQ-000 480GB SSD        | 4         | 0.53%   |
| Micron MTFDHBA512TDV 512GB                | 4         | 0.53%   |
| JMicron Generic 2TB                       | 4         | 0.53%   |
| HGST HTS725050A7E630 500GB                | 4         | 0.53%   |
| External USB3.0 120GB                     | 4         | 0.53%   |
| WDC WD10SPZX-22Z10T0 1TB                  | 3         | 0.4%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB      | 3         | 0.4%    |
| WDC PC SN730 SDBPNTY-512G-1101 512GB      | 3         | 0.4%    |
| WDC PC SN720 SDAPNTW-512G-1006 512GB      | 3         | 0.4%    |
| Unknown MMC Card  64GB                    | 3         | 0.4%    |
| Toshiba TR200 240GB SSD                   | 3         | 0.4%    |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 3         | 0.4%    |
| SK hynix HFM512GDJTNI-82A0A 512GB         | 3         | 0.4%    |
| Seagate ST9500325AS 500GB                 | 3         | 0.4%    |
| SanDisk Ultra 3D NVMe 1TB                 | 3         | 0.4%    |
| Samsung NVMe SSD Drive 1TB                | 3         | 0.4%    |
| Samsung MZVLW256HEHP-00000 256GB          | 3         | 0.4%    |
| Samsung MZVLQ512HBLU-00B00 512GB          | 3         | 0.4%    |
| Samsung MZVL2512HCJQ-00BL2 512GB          | 3         | 0.4%    |
| Samsung MZALQ512HALU-000L2 512GB          | 3         | 0.4%    |
| KIOXIA NVMe SSD Drive 512GB               | 3         | 0.4%    |
| Intel SSDPEKKW256G8 256GB                 | 3         | 0.4%    |
| Intel SSDPEKKF360G7H 360GB                | 3         | 0.4%    |
| Intel NVMe SSD Drive 1024GB               | 3         | 0.4%    |
| WDC WDS200T2G0A-00JH30 2TB SSD            | 2         | 0.26%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 2         | 0.26%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 2         | 0.26%   |
| WDC WD10SPZX-22Z10T1 1TB                  | 2         | 0.26%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 2         | 0.26%   |
| WDC WD10JPCX-24UE4T0 1TB                  | 2         | 0.26%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB      | 2         | 0.26%   |
| WDC PC SN720 SDAPNTW-512G-1127 512GB      | 2         | 0.26%   |
| WDC PC SN720 SDAPNTW-256G-1127 256GB      | 2         | 0.26%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB      | 2         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 74     | 40.24%  |
| WDC                 | 42        | 51     | 25.61%  |
| HGST                | 19        | 23     | 11.59%  |
| Toshiba             | 14        | 18     | 8.54%   |
| Hitachi             | 9         | 13     | 5.49%   |
| Samsung Electronics | 5         | 6      | 3.05%   |
| JMicron Technology  | 4         | 4      | 2.44%   |
| Fujitsu             | 3         | 3      | 1.83%   |
| ASMT                | 1         | 1      | 0.61%   |
| ACASIS              | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 53     | 22.55%  |
| SanDisk             | 15        | 17     | 7.35%   |
| Plextor             | 14        | 14     | 6.86%   |
| Toshiba             | 13        | 14     | 6.37%   |
| LITEON              | 11        | 13     | 5.39%   |
| Kingston            | 9         | 10     | 4.41%   |
| WDC                 | 7         | 7      | 3.43%   |
| Micron Technology   | 7         | 7      | 3.43%   |
| Lenovo              | 6         | 7      | 2.94%   |
| Crucial             | 6         | 8      | 2.94%   |
| A-DATA Technology   | 6         | 9      | 2.94%   |
| Transcend           | 4         | 5      | 1.96%   |
| Teclast             | 4         | 4      | 1.96%   |
| SK hynix            | 4         | 4      | 1.96%   |
| Netac               | 4         | 4      | 1.96%   |
| Intel               | 4         | 4      | 1.96%   |
| GALAX               | 4         | 4      | 1.96%   |
| China               | 4         | 5      | 1.96%   |
| Apple               | 4         | 4      | 1.96%   |
| Unknown             | 3         | 3      | 1.47%   |
| Phison              | 2         | 3      | 0.98%   |
| Lexar               | 2         | 2      | 0.98%   |
| Kingchuxing         | 2         | 2      | 0.98%   |
| FORESEE             | 2         | 2      | 0.98%   |
| Colorful            | 2         | 2      | 0.98%   |
| Xinsujie            | 1         | 1      | 0.49%   |
| WDC WDS1            | 1         | 1      | 0.49%   |
| Unknown             | 1         | 1      | 0.49%   |
| UNIC2               | 1         | 1      | 0.49%   |
| TurXun              | 1         | 1      | 0.49%   |
| TO Exter            | 1         | 1      | 0.49%   |
| Q200                | 1         | 1      | 0.49%   |
| MR                  | 1         | 3      | 0.49%   |
| LITEONIT            | 1         | 1      | 0.49%   |
| Lite-On             | 1         | 1      | 0.49%   |
| LenovoSPEED         | 1         | 1      | 0.49%   |
| Lanbo               | 1         | 1      | 0.49%   |
| KingSpec            | 1         | 1      | 0.49%   |
| KING                | 1         | 1      | 0.49%   |
| Hikvision           | 1         | 1      | 0.49%   |
| Hewlett-Packard     | 1         | 1      | 0.49%   |
| GLOWAY              | 1         | 1      | 0.49%   |
| Galaxy              | 1         | 1      | 0.49%   |
| EAGET               | 1         | 2      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 291       | 387    | 42.92%  |
| SSD     | 184       | 229    | 27.14%  |
| HDD     | 156       | 194    | 23.01%  |
| MMC     | 24        | 29     | 3.54%   |
| Unknown | 23        | 24     | 3.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 291       | 381    | 45.47%  |
| SATA | 285       | 408    | 44.53%  |
| SAS  | 40        | 45     | 6.25%   |
| MMC  | 24        | 29     | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 203       | 266    | 61.33%  |
| 0.51-1.0   | 100       | 120    | 30.21%  |
| 1.01-2.0   | 23        | 29     | 6.95%   |
| 3.01-4.0   | 3         | 5      | 0.91%   |
| 10.01-20.0 | 1         | 2      | 0.3%    |
| 4.01-10.0  | 1         | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 153       | 27.77%  |
| 101-250        | 137       | 24.86%  |
| 501-1000       | 85        | 15.43%  |
| 51-100         | 49        | 8.89%   |
| 1001-2000      | 38        | 6.9%    |
| 1-20           | 33        | 5.99%   |
| 21-50          | 20        | 3.63%   |
| More than 3000 | 13        | 2.36%   |
| 2001-3000      | 12        | 2.18%   |
| Unknown        | 11        | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 229       | 40.39%  |
| 21-50          | 91        | 16.05%  |
| 101-250        | 76        | 13.4%   |
| 51-100         | 64        | 11.29%  |
| 251-500        | 52        | 9.17%   |
| 501-1000       | 26        | 4.59%   |
| 1001-2000      | 11        | 1.94%   |
| Unknown        | 11        | 1.94%   |
| More than 3000 | 5         | 0.88%   |
| 2001-3000      | 2         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM048-2E7172 1TB               | 2         | 2      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 7.69%   |
| WDC WD10SPZX-60Z10T0 1TB                     | 1         | 1      | 3.85%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 3.85%   |
| Toshiba MK3259GSXP 320GB                     | 1         | 1      | 3.85%   |
| Toshiba MK2555GSX 250GB                      | 1         | 1      | 3.85%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 2      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 3.85%   |
| SanDisk SSD U100 128GB                       | 1         | 1      | 3.85%   |
| SanDisk SD9SN8W-256G-1006 256GB SSD          | 1         | 1      | 3.85%   |
| Samsung Electronics MZVLW512HMJP-00000 512GB | 1         | 1      | 3.85%   |
| Plextor PX-128M6S 128GB SSD                  | 1         | 1      | 3.85%   |
| Netac SSD 120GB                              | 1         | 1      | 3.85%   |
| Intel SSDPEKKF256G7H 256GB                   | 1         | 1      | 3.85%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 3.85%   |
| Hitachi HTS541060G9SA00 64GB                 | 1         | 1      | 3.85%   |
| Hitachi HTS541040G9AT00 40GB                 | 1         | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.85%   |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 3.85%   |
| Fujitsu MHV2100BH PL 100GB                   | 1         | 1      | 3.85%   |
| Crucial M4-CT128M4SSD1 128GB                 | 1         | 1      | 3.85%   |
| Crucial CT240M500SSD1 240GB                  | 1         | 1      | 3.85%   |
| A-DATA Technology SP900 128GB SSD            | 1         | 2      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 26.92%  |
| Toshiba             | 3         | 3      | 11.54%  |
| Hitachi             | 3         | 3      | 11.54%  |
| SanDisk             | 2         | 2      | 7.69%   |
| HGST                | 2         | 2      | 7.69%   |
| Crucial             | 2         | 2      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Plextor             | 1         | 1      | 3.85%   |
| Netac               | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 2      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 41.18%  |
| Toshiba | 3         | 3      | 17.65%  |
| Hitachi | 3         | 3      | 17.65%  |
| HGST    | 2         | 2      | 11.76%  |
| WDC     | 1         | 1      | 5.88%   |
| Fujitsu | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 18     | 65.38%  |
| SSD  | 7         | 8      | 26.92%  |
| NVMe | 2         | 2      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Samsung Electronics HS06THB 64GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 272       | 425    | 48.14%  |
| Works    | 266       | 409    | 47.08%  |
| Malfunc  | 26        | 28     | 4.6%    |
| Failed   | 1         | 1      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 314       | 46.11%  |
| Samsung Electronics              | 124       | 18.21%  |
| AMD                              | 64        | 9.4%    |
| SanDisk                          | 50        | 7.34%   |
| SK hynix                         | 32        | 4.7%    |
| Toshiba America Info Systems     | 24        | 3.52%   |
| Silicon Motion                   | 13        | 1.91%   |
| Micron Technology                | 12        | 1.76%   |
| KIOXIA                           | 10        | 1.47%   |
| Phison Electronics               | 5         | 0.73%   |
| Kingston Technology Company      | 5         | 0.73%   |
| ADATA Technology                 | 4         | 0.59%   |
| Shenzhen Longsys Electronics     | 3         | 0.44%   |
| Micron/Crucial Technology        | 3         | 0.44%   |
| Marvell Technology Group         | 3         | 0.44%   |
| Apple                            | 3         | 0.44%   |
| Zhaoxin                          | 2         | 0.29%   |
| Silicon Integrated Systems [SiS] | 2         | 0.29%   |
| Lite-On Technology               | 2         | 0.29%   |
| Biwin Storage Technology         | 2         | 0.29%   |
| Union Memory (Shenzhen)          | 1         | 0.15%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.15%   |
| Lenovo                           | 1         | 0.15%   |
| JMicron Technology               | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 77        | 10.77%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 62        | 8.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 54        | 7.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 32        | 4.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 22        | 3.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 20        | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 19        | 2.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 2.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 17        | 2.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 17        | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 16        | 2.24%   |
| Samsung NVMe SSD Controller 980                                                  | 16        | 2.24%   |
| SK hynix Gold P31 SSD                                                            | 15        | 2.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 1.96%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 13        | 1.82%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 1.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 1.68%   |
| Micron Non-Volatile memory controller                                            | 12        | 1.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 10        | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 10        | 1.4%    |
| SK hynix Non-Volatile memory controller                                          | 9         | 1.26%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 9         | 1.26%   |
| Intel SSD 660P Series                                                            | 9         | 1.26%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 8         | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 1.12%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 1.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 1.12%   |
| KIOXIA Non-Volatile memory controller                                            | 7         | 0.98%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 7         | 0.98%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 7         | 0.98%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 6         | 0.84%   |
| SK hynix BC511                                                                   | 6         | 0.84%   |
| Intel SSD 600P Series                                                            | 5         | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 0.7%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 4         | 0.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 4         | 0.56%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 0.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 0.56%   |
| ADATA Non-Volatile memory controller                                             | 4         | 0.56%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.42%   |
| Samsung Electronics SATA controller                                              | 3         | 0.42%   |
| Phison NVMe Storage Controller                                                   | 3         | 0.42%   |
| KIOXIA NVMe SSD                                                                  | 3         | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.42%   |
| Apple ANS2 NVMe Controller                                                       | 3         | 0.42%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 0.42%   |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                                 | 2         | 0.28%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.28%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.28%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.28%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.28%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.28%   |
| Micron/Crucial Non-Volatile memory controller                                    | 2         | 0.28%   |
| Marvell Group Marvell Non-Volatile memory controller                             | 2         | 0.28%   |
| Lite-On Non-Volatile memory controller                                           | 2         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 335       | 49.34%  |
| NVMe | 293       | 43.15%  |
| RAID | 35        | 5.15%   |
| IDE  | 16        | 2.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 406       | 76.46%  |
| AMD          | 122       | 22.98%  |
| CentaurHauls | 2         | 0.38%   |
| PHYTIUM      | 1         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 18        | 3.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 16        | 3.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 3.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 15        | 2.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 2.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 2.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 2.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 2.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 11        | 2.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 1.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 1.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 1.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.51%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 1.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.32%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 7         | 1.32%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 7         | 1.32%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 6         | 1.13%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 1.13%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 1.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.94%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.94%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.94%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 0.94%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.75%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 0.75%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 4         | 0.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.75%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 4         | 0.75%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 3         | 0.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 0.56%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 0.56%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 3         | 0.56%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.56%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 3         | 0.56%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.56%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.56%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 0.56%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 2         | 0.38%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 2         | 0.38%   |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 2         | 0.38%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.38%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 2         | 0.38%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.38%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.38%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.38%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.38%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.38%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 2         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 146       | 27.5%   |
| Intel Core i7           | 133       | 25.05%  |
| AMD Ryzen 5             | 50        | 9.42%   |
| Other                   | 47        | 8.85%   |
| AMD Ryzen 7             | 38        | 7.16%   |
| Intel Core i3           | 26        | 4.9%    |
| Intel Core 2 Duo        | 11        | 2.07%   |
| Intel Atom              | 11        | 2.07%   |
| Intel Celeron           | 10        | 1.88%   |
| AMD Ryzen 7 PRO         | 8         | 1.51%   |
| AMD Ryzen 9             | 5         | 0.94%   |
| AMD A6                  | 5         | 0.94%   |
| AMD A10                 | 5         | 0.94%   |
| Intel Pentium           | 4         | 0.75%   |
| Intel Core m3           | 4         | 0.75%   |
| Intel Xeon              | 3         | 0.56%   |
| Intel Pentium Dual      | 3         | 0.56%   |
| Intel Core i9           | 3         | 0.56%   |
| AMD Ryzen 5 PRO         | 3         | 0.56%   |
| Intel Core M            | 2         | 0.38%   |
| AMD A8                  | 2         | 0.38%   |
| Intel Pentium Silver    | 1         | 0.19%   |
| Intel Pentium M         | 1         | 0.19%   |
| Intel Core Duo          | 1         | 0.19%   |
| Intel Core 2            | 1         | 0.19%   |
| Intel Core              | 1         | 0.19%   |
| Intel Celeron Dual-Core | 1         | 0.19%   |
| AMD Ryzen 3             | 1         | 0.19%   |
| AMD E2                  | 1         | 0.19%   |
| AMD E                   | 1         | 0.19%   |
| AMD C-50                | 1         | 0.19%   |
| AMD Athlon              | 1         | 0.19%   |
| AMD A4                  | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 223       | 41.92%  |
| 2       | 172       | 32.33%  |
| 6       | 63        | 11.84%  |
| 8       | 62        | 11.65%  |
| 1       | 6         | 1.13%   |
| 12      | 3         | 0.56%   |
| 14      | 2         | 0.38%   |
| Unknown | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 531       | 99.81%  |
| Unknown | 1         | 0.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 458       | 85.93%  |
| 1       | 74        | 13.88%  |
| Unknown | 1         | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 524       | 98.5%   |
| 32-bit         | 4         | 0.75%   |
| Unknown        | 4         | 0.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 16.51%  |
| 0x906ea    | 29        | 5.32%   |
| 0x306a9    | 29        | 5.32%   |
| 0x806ea    | 28        | 5.14%   |
| 0x806ec    | 24        | 4.4%    |
| 0x806e9    | 22        | 4.04%   |
| 0x806c1    | 21        | 3.85%   |
| 0x206a7    | 20        | 3.67%   |
| 0x08600106 | 20        | 3.67%   |
| 0x0a50000c | 19        | 3.49%   |
| 0x40651    | 18        | 3.3%    |
| 0x306d4    | 16        | 2.94%   |
| 0x506e3    | 15        | 2.75%   |
| 0x406e3    | 15        | 2.75%   |
| 0x08108102 | 15        | 2.75%   |
| 0x306c3    | 13        | 2.39%   |
| 0xa0652    | 12        | 2.2%    |
| 0x08600104 | 12        | 2.2%    |
| 0x906e9    | 9         | 1.65%   |
| 0x806d1    | 9         | 1.65%   |
| 0x08108109 | 9         | 1.65%   |
| 0x1067a    | 6         | 1.1%    |
| 0x806eb    | 5         | 0.92%   |
| 0x706e5    | 5         | 0.92%   |
| 0x08600103 | 5         | 0.92%   |
| 0xa0660    | 4         | 0.73%   |
| 0x6fd      | 4         | 0.73%   |
| 0x406c3    | 4         | 0.73%   |
| 0x08101007 | 4         | 0.73%   |
| 0x906a3    | 3         | 0.55%   |
| 0x706a1    | 3         | 0.55%   |
| 0x20655    | 3         | 0.55%   |
| 0x0a50000b | 3         | 0.55%   |
| 0x08701013 | 3         | 0.55%   |
| 0x08600102 | 3         | 0.55%   |
| 0x906ed    | 2         | 0.37%   |
| 0x806c2    | 2         | 0.37%   |
| 0x706a8    | 2         | 0.37%   |
| 0x506ca    | 2         | 0.37%   |
| 0x30678    | 2         | 0.37%   |
| 0x106e5    | 2         | 0.37%   |
| 0x106ca    | 2         | 0.37%   |
| 0x106c2    | 2         | 0.37%   |
| 0x08608103 | 2         | 0.37%   |
| 0x07030105 | 2         | 0.37%   |
| 0x0700010f | 2         | 0.37%   |
| 0x06003109 | 2         | 0.37%   |
| 0x06001119 | 2         | 0.37%   |
| 0x6fb      | 1         | 0.18%   |
| 0x6f2      | 1         | 0.18%   |
| 0x6ec      | 1         | 0.18%   |
| 0x6d8      | 1         | 0.18%   |
| 0x506c9    | 1         | 0.18%   |
| 0x406c4    | 1         | 0.18%   |
| 0x40661    | 1         | 0.18%   |
| 0x306a8    | 1         | 0.18%   |
| 0x20652    | 1         | 0.18%   |
| 0x10676    | 1         | 0.18%   |
| 0x0a404101 | 1         | 0.18%   |
| 0x08101016 | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 149       | 28.01%  |
| Zen 2            | 44        | 8.27%   |
| Haswell          | 34        | 6.39%   |
| Skylake          | 33        | 6.2%    |
| IvyBridge        | 33        | 6.2%    |
| TigerLake        | 32        | 6.02%   |
| Zen 3            | 27        | 5.08%   |
| Zen+             | 25        | 4.7%    |
| SandyBridge      | 23        | 4.32%   |
| Broadwell        | 19        | 3.57%   |
| CometLake        | 18        | 3.38%   |
| IceLake          | 14        | 2.63%   |
| Silvermont       | 11        | 2.07%   |
| Penryn           | 10        | 1.88%   |
| Unknown          | 8         | 1.5%    |
| Zen              | 7         | 1.32%   |
| Core             | 6         | 1.13%   |
| Westmere         | 5         | 0.94%   |
| Goldmont plus    | 5         | 0.94%   |
| Bonnell          | 4         | 0.75%   |
| Steamroller      | 3         | 0.56%   |
| Goldmont         | 3         | 0.56%   |
| Excavator        | 3         | 0.56%   |
| Puma             | 2         | 0.38%   |
| Piledriver       | 2         | 0.38%   |
| P6               | 2         | 0.38%   |
| Nehalem          | 2         | 0.38%   |
| K10 Llano        | 2         | 0.38%   |
| Jaguar           | 2         | 0.38%   |
| Bobcat           | 2         | 0.38%   |
| Alderlake Hybrid | 2         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 372       | 50.13%  |
| Nvidia                           | 215       | 28.98%  |
| AMD                              | 152       | 20.49%  |
| Zhaoxin                          | 2         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 38        | 5.01%   |
| Intel UHD Graphics 620                                                                   | 35        | 4.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 32        | 4.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 3.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 27        | 3.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25        | 3.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 2.77%   |
| AMD Cezanne                                                                              | 20        | 2.64%   |
| Intel HD Graphics 620                                                                    | 19        | 2.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 2.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 2.24%   |
| Nvidia GP108M [GeForce MX150]                                                            | 16        | 2.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 2.11%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 15        | 1.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.71%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.71%   |
| Nvidia GP108M [GeForce MX250]                                                            | 12        | 1.58%   |
| Intel HD Graphics 530                                                                    | 12        | 1.58%   |
| Nvidia TU117M [GeForce MX450]                                                            | 10        | 1.32%   |
| Nvidia TU117M                                                                            | 10        | 1.32%   |
| Intel HD Graphics 630                                                                    | 10        | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 1.19%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 8         | 1.05%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 1.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.05%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 1.05%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 0.79%   |
| Intel Comet Lake UHD Graphics                                                            | 6         | 0.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.66%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.66%   |
| Intel UHD Graphics 615                                                                   | 5         | 0.66%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 4         | 0.53%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 4         | 0.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.53%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.53%   |
| AMD Jet XT [Radeon R5 M240]                                                              | 4         | 0.53%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 3         | 0.4%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.4%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.4%    |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 0.4%    |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 0.4%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.4%    |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 3         | 0.4%    |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.4%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.4%    |
| Nvidia GK107M [GeForce GT 650M]                                                          | 3         | 0.4%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 0.4%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.4%    |
| Intel HD Graphics 500                                                                    | 3         | 0.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.4%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 178       | 33.33%  |
| Intel + Nvidia | 163       | 30.52%  |
| 1 x AMD        | 93        | 17.42%  |
| 1 x Nvidia     | 36        | 6.74%   |
| Intel + AMD    | 32        | 5.99%   |
| AMD + Nvidia   | 16        | 3%      |
| 2 x AMD        | 11        | 2.06%   |
| 2 x Intel      | 2         | 0.37%   |
| 1 x Zhaoxin    | 2         | 0.37%   |
| 1 x SiS        | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 408       | 75.84%  |
| Proprietary | 105       | 19.52%  |
| Unknown     | 25        | 4.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 285       | 52.49%  |
| 1.01-2.0   | 84        | 15.47%  |
| 0.01-0.5   | 53        | 9.76%   |
| 0.51-1.0   | 48        | 8.84%   |
| 3.01-4.0   | 37        | 6.81%   |
| 5.01-6.0   | 22        | 4.05%   |
| 7.01-8.0   | 10        | 1.84%   |
| 8.01-16.0  | 3         | 0.55%   |
| 2.01-3.0   | 1         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 93        | 16.17%  |
| AU Optronics            | 88        | 15.3%   |
| LG Display              | 85        | 14.78%  |
| Chimei Innolux          | 85        | 14.78%  |
| Sharp                   | 31        | 5.39%   |
| Samsung Electronics     | 28        | 4.87%   |
| Lenovo                  | 18        | 3.13%   |
| CSO                     | 17        | 2.96%   |
| Dell                    | 16        | 2.78%   |
| AOC                     | 13        | 2.26%   |
| PANDA                   | 11        | 1.91%   |
| InfoVision              | 9         | 1.57%   |
| Apple                   | 9         | 1.57%   |
| Hewlett-Packard         | 6         | 1.04%   |
| Philips                 | 5         | 0.87%   |
| Goldstar                | 5         | 0.87%   |
| TMX                     | 4         | 0.7%    |
| LGD                     | 3         | 0.52%   |
| Chi Mei Optoelectronics | 3         | 0.52%   |
| BOE Technology Group    | 3         | 0.52%   |
| BenQ                    | 3         | 0.52%   |
| SGT                     | 2         | 0.35%   |
| Panasonic               | 2         | 0.35%   |
| JDI                     | 2         | 0.35%   |
| IPS                     | 2         | 0.35%   |
| InnoLux Display         | 2         | 0.35%   |
| Acer                    | 2         | 0.35%   |
| ViewSonic               | 1         | 0.17%   |
| Unknown                 | 1         | 0.17%   |
| Sony                    | 1         | 0.17%   |
| RTK                     | 1         | 0.17%   |
| QSM                     | 1         | 0.17%   |
| Pixio                   | 1         | 0.17%   |
| MStar                   | 1         | 0.17%   |
| MSI                     | 1         | 0.17%   |
| Mi                      | 1         | 0.17%   |
| MAG                     | 1         | 0.17%   |
| LG Philips              | 1         | 0.17%   |
| KOIOS                   | 1         | 0.17%   |
| KIG                     | 1         | 0.17%   |
| JXG                     | 1         | 0.17%   |
| HYD                     | 1         | 0.17%   |
| HKC                     | 1         | 0.17%   |
| HannStar                | 1         | 0.17%   |
| GKK                     | 1         | 0.17%   |
| DST                     | 1         | 0.17%   |
| Denver                  | 1         | 0.17%   |
| CPT                     | 1         | 0.17%   |
| CMN                     | 1         | 0.17%   |
| CHR                     | 1         | 0.17%   |
| CHD                     | 1         | 0.17%   |
| Cbox                    | 1         | 0.17%   |
| ASUSTek Computer        | 1         | 0.17%   |
| AMT International       | 1         | 0.17%   |
| AML                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 1.55%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 7         | 1.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 7         | 1.21%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 6         | 1.03%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 6         | 1.03%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 5         | 0.86%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 0.86%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 4         | 0.69%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 4         | 0.69%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.69%   |
| InfoVision LCD Monitor IVO061F 1920x1080 344x194mm 15.5-inch          | 4         | 0.69%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 4         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 4         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 4         | 0.69%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 4         | 0.69%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 4         | 0.69%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 4         | 0.69%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch               | 3         | 0.52%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.52%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.52%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch          | 3         | 0.52%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 3         | 0.52%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 3         | 0.52%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 3         | 0.52%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 3         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1603 1920x1080 355x199mm 16.0-inch      | 3         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 3         | 0.52%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 3         | 0.52%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 3         | 0.52%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 3         | 0.52%   |
| AU Optronics LCD Monitor AUO45ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.52%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 3         | 0.52%   |
| AOC 2491W AOC2491 1920x1080 521x293mm 23.5-inch                       | 3         | 0.52%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 309x174mm 14.0-inch  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 2         | 0.34%   |
| PANDA LCD Monitor NCP005C 2560x1600 302x189mm 14.0-inch               | 2         | 0.34%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 2         | 0.34%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.34%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0619 1920x1080 309x174mm 14.0-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0576 1920x1080 294x165mm 13.3-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD03FE 1920x1080 345x194mm 15.6-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch           | 2         | 0.34%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch            | 2         | 0.34%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 299       | 55.47%  |
| 1366x768 (WXGA)    | 94        | 17.44%  |
| 3840x2160 (4K)     | 29        | 5.38%   |
| 2560x1440 (QHD)    | 25        | 4.64%   |
| 2560x1600          | 22        | 4.08%   |
| 1600x900 (HD+)     | 8         | 1.48%   |
| 1440x900 (WXGA+)   | 8         | 1.48%   |
| 2160x1440          | 7         | 1.3%    |
| 2880x1800          | 6         | 1.11%   |
| 1920x1200 (WUXGA)  | 6         | 1.11%   |
| 1280x800 (WXGA)    | 6         | 1.11%   |
| 1680x1050 (WSXGA+) | 4         | 0.74%   |
| 3200x2000          | 3         | 0.56%   |
| 2240x1400          | 3         | 0.56%   |
| 3072x1920          | 2         | 0.37%   |
| 3000x2000          | 2         | 0.37%   |
| 1024x600           | 2         | 0.37%   |
| 3840x2400          | 1         | 0.19%   |
| 3840x1080          | 1         | 0.19%   |
| 3440x1440          | 1         | 0.19%   |
| 3200x1800 (QHD+)   | 1         | 0.19%   |
| 2880x1920          | 1         | 0.19%   |
| 2560x1080          | 1         | 0.19%   |
| 2256x1504          | 1         | 0.19%   |
| 1920x540           | 1         | 0.19%   |
| 1920x1280          | 1         | 0.19%   |
| 1792x768           | 1         | 0.19%   |
| 1400x1050          | 1         | 0.19%   |
| 1024x768 (XGA)     | 1         | 0.19%   |
| Unknown            | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 171       | 29.79%  |
| 13      | 126       | 21.95%  |
| 14      | 108       | 18.82%  |
| 12      | 25        | 4.36%   |
| 27      | 23        | 4.01%   |
| 23      | 23        | 4.01%   |
| 24      | 21        | 3.66%   |
| 16      | 20        | 3.48%   |
| 17      | 18        | 3.14%   |
| Unknown | 12        | 2.09%   |
| 21      | 4         | 0.7%    |
| 11      | 4         | 0.7%    |
| 40      | 3         | 0.52%   |
| 22      | 3         | 0.52%   |
| 18      | 3         | 0.52%   |
| 19      | 2         | 0.35%   |
| 10      | 2         | 0.35%   |
| 63      | 1         | 0.17%   |
| 43      | 1         | 0.17%   |
| 34      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |
| 25      | 1         | 0.17%   |
| 20      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 346       | 60.38%  |
| 201-300     | 97        | 16.93%  |
| 501-600     | 63        | 10.99%  |
| 351-400     | 32        | 5.58%   |
| 401-500     | 13        | 2.27%   |
| Unknown     | 12        | 2.09%   |
| 801-900     | 3         | 0.52%   |
| 601-700     | 3         | 0.52%   |
| 701-800     | 2         | 0.35%   |
| 1001-1500   | 1         | 0.17%   |
| 901-1000    | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 417       | 81.93%  |
| 16/10   | 63        | 12.38%  |
| 3/2     | 14        | 2.75%   |
| Unknown | 11        | 2.16%   |
| 4/3     | 2         | 0.39%   |
| 21/9    | 2         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 180       | 31.3%   |
| 101-110        | 176       | 30.61%  |
| 71-80          | 55        | 9.57%   |
| 201-250        | 45        | 7.83%   |
| 61-70          | 23        | 4%      |
| 301-350        | 23        | 4%      |
| 121-130        | 18        | 3.13%   |
| 111-120        | 12        | 2.09%   |
| Unknown        | 12        | 2.09%   |
| 151-200        | 6         | 1.04%   |
| 251-300        | 5         | 0.87%   |
| 91-100         | 5         | 0.87%   |
| 51-60          | 4         | 0.7%    |
| 501-1000       | 4         | 0.7%    |
| 351-500        | 2         | 0.35%   |
| 41-50          | 2         | 0.35%   |
| 141-150        | 2         | 0.35%   |
| More than 1000 | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 275       | 48.67%  |
| 101-120       | 101       | 17.88%  |
| 161-240       | 88        | 15.58%  |
| 51-100        | 58        | 10.27%  |
| More than 240 | 31        | 5.49%   |
| Unknown       | 12        | 2.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 423       | 78.48%  |
| 2     | 85        | 15.77%  |
| 0     | 27        | 5.01%   |
| 3     | 4         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 339       | 41.09%  |
| Realtek Semiconductor            | 287       | 34.79%  |
| Qualcomm Atheros                 | 87        | 10.55%  |
| Broadcom                         | 22        | 2.67%   |
| Broadcom Limited                 | 17        | 2.06%   |
| MediaTek                         | 11        | 1.33%   |
| ASIX Electronics                 | 11        | 1.33%   |
| Xiaomi                           | 8         | 0.97%   |
| Huawei Technologies              | 6         | 0.73%   |
| Ralink                           | 5         | 0.61%   |
| Ralink Technology                | 3         | 0.36%   |
| Quectel Wireless Solutions       | 3         | 0.36%   |
| Qualcomm                         | 3         | 0.36%   |
| Marvell Technology Group         | 3         | 0.36%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.24%   |
| Silicon Integrated Systems [SiS] | 2         | 0.24%   |
| Sierra Wireless                  | 2         | 0.24%   |
| OPPO Electronics                 | 2         | 0.24%   |
| Wilocity                         | 1         | 0.12%   |
| TP-Link                          | 1         | 0.12%   |
| ST-Ericsson                      | 1         | 0.12%   |
| Shenzhen Goodix Technology       | 1         | 0.12%   |
| Qualcomm Atheros Communications  | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.12%   |
| Meizu                            | 1         | 0.12%   |
| ICS Advent                       | 1         | 0.12%   |
| Hewlett-Packard                  | 1         | 0.12%   |
| Dell                             | 1         | 0.12%   |
| Attansic Technology              | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 177       | 18.59%  |
| Intel Wi-Fi 6 AX200                                                     | 50        | 5.25%   |
| Intel Wireless 8265 / 8275                                              | 43        | 4.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 3.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 31        | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 25        | 2.63%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 2.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 21        | 2.21%   |
| Intel Wireless 7265                                                     | 19        | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 18        | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 1.68%   |
| Intel Wireless 7260                                                     | 14        | 1.47%   |
| Intel Wireless 3165                                                     | 14        | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 1.47%   |
| Intel Wireless 8260                                                     | 12        | 1.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 1.16%   |
| Intel Ethernet Connection (4) I219-V                                    | 10        | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 8         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 8         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.74%   |
| Intel Wireless 3160                                                     | 7         | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                   | 6         | 0.63%   |
| Intel Ethernet Connection (10) I219-V                                   | 6         | 0.63%   |
| Huawei COL-L29                                                          | 6         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.53%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.53%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.53%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                                | 5         | 0.53%   |
| ASIX AX88772B                                                           | 5         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                           | 5         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 4         | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 4         | 0.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.42%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.42%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                                    | 4         | 0.42%   |
| Intel Ethernet Connection (13) I219-V                                   | 4         | 0.42%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 0.42%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 4         | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.32%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 3         | 0.32%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.32%   |
| Quectel Wireless Solutions Quectel EM05-CE                              | 3         | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 3         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 3         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 327       | 60.78%  |
| Realtek Semiconductor           | 78        | 14.5%   |
| Qualcomm Atheros                | 71        | 13.2%   |
| Broadcom                        | 18        | 3.35%   |
| Broadcom Limited                | 12        | 2.23%   |
| MediaTek                        | 11        | 2.04%   |
| Ralink                          | 5         | 0.93%   |
| Ralink Technology               | 3         | 0.56%   |
| Quectel Wireless Solutions      | 3         | 0.56%   |
| Xiaomi                          | 2         | 0.37%   |
| Sierra Wireless                 | 2         | 0.37%   |
| Wilocity                        | 1         | 0.19%   |
| TP-Link                         | 1         | 0.19%   |
| Qualcomm Atheros Communications | 1         | 0.19%   |
| Qualcomm                        | 1         | 0.19%   |
| Hewlett-Packard                 | 1         | 0.19%   |
| Dell                            | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 50        | 9.28%   |
| Intel Wireless 8265 / 8275                                              | 43        | 7.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 6.86%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 4.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 3.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 21        | 3.9%    |
| Intel Wireless 7265                                                     | 19        | 3.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 2.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 2.97%   |
| Intel Wireless 7260                                                     | 14        | 2.6%    |
| Intel Wireless 3165                                                     | 14        | 2.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 2.6%    |
| Intel Wireless 8260                                                     | 12        | 2.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 2.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 8         | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.48%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 8         | 1.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.3%    |
| Intel Wireless 3160                                                     | 7         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.93%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.93%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.93%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 0.74%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 4         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.56%   |
| Quectel Wireless Solutions Quectel EM05-CE                              | 3         | 0.56%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.56%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 3         | 0.56%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 0.56%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 3         | 0.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.56%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 2         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.37%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 2         | 0.37%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.37%   |
| Intel Centrino Wireless-N 105                                           | 2         | 0.37%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.37%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.37%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.37%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 0.37%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 239       | 59.9%   |
| Intel                            | 91        | 22.81%  |
| Qualcomm Atheros                 | 23        | 5.76%   |
| ASIX Electronics                 | 11        | 2.76%   |
| Xiaomi                           | 6         | 1.5%    |
| Huawei Technologies              | 6         | 1.5%    |
| Broadcom Limited                 | 5         | 1.25%   |
| Broadcom                         | 5         | 1.25%   |
| Marvell Technology Group         | 3         | 0.75%   |
| Silicon Integrated Systems [SiS] | 2         | 0.5%    |
| OPPO Electronics                 | 2         | 0.5%    |
| ZTE WCDMA Technologies MSM       | 1         | 0.25%   |
| Qualcomm                         | 1         | 0.25%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.25%   |
| ICS Advent                       | 1         | 0.25%   |
| Attansic Technology              | 1         | 0.25%   |
| Apple                            | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 177       | 43.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 31        | 7.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 25        | 6.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 18        | 4.44%   |
| Intel Ethernet Connection (4) I219-V                                 | 10        | 2.47%   |
| Intel Ethernet Connection (4) I219-LM                                | 6         | 1.48%   |
| Intel Ethernet Connection (3) I218-LM                                | 6         | 1.48%   |
| Intel Ethernet Connection (10) I219-V                                | 6         | 1.48%   |
| Huawei COL-L29                                                       | 6         | 1.48%   |
| Intel 82567LM Gigabit Network Connection                             | 5         | 1.23%   |
| ASIX AX88772B                                                        | 5         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                        | 5         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 4         | 0.99%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 4         | 0.99%   |
| Intel Ethernet Connection I218-LM                                    | 4         | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                 | 4         | 0.99%   |
| Intel Ethernet Connection (13) I219-V                                | 4         | 0.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 3         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                    | 3         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 3         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 3         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 3         | 0.74%   |
| Intel Ethernet Connection I217-LM                                    | 3         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                | 3         | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 3         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 2         | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 2         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 2         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 2         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                | 2         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 2         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 2         | 0.49%   |
| OPPO Find X2 Lite                                                    | 2         | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                 | 2         | 0.49%   |
| Intel I211 Gigabit Network Connection                                | 2         | 0.49%   |
| Intel Ethernet controller                                            | 2         | 0.49%   |
| Intel Ethernet Connection I219-V                                     | 2         | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                | 2         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                 | 2         | 0.49%   |
| Intel 82577LM Gigabit Network Connection                             | 2         | 0.49%   |
| Intel 82567LF Gigabit Network Connection                             | 2         | 0.49%   |
| Intel 82566MM Gigabit Network Connection                             | 2         | 0.49%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe              | 2         | 0.49%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                       | 1         | 0.25%   |
| Realtek USB 10/100 LAN                                               | 1         | 0.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 0.25%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.25%   |
| Qualcomm POCO F2 Pro                                                 | 1         | 0.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1         | 0.25%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                | 1         | 0.25%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                           | 1         | 0.25%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller              | 1         | 0.25%   |
| Intel Ethernet Controller I225-V                                     | 1         | 0.25%   |
| Intel Ethernet Connection I218-V                                     | 1         | 0.25%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 0.25%   |
| Intel Ethernet Connection (10) I219-LM                               | 1         | 0.25%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 0.25%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 0.25%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 0.25%   |
| ICS Advent USB 10/100 LAN                                            | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 519       | 56.91%  |
| Ethernet | 385       | 42.21%  |
| Unknown  | 6         | 0.66%   |
| Modem    | 2         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 412       | 75.18%  |
| Ethernet | 136       | 24.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 333       | 62.71%  |
| 1     | 178       | 33.52%  |
| 3     | 10        | 1.88%   |
| 0     | 9         | 1.69%   |
| 6     | 1         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 467       | 86.48%  |
| Yes  | 73        | 13.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 275       | 61.38%  |
| Qualcomm Atheros Communications | 39        | 8.71%   |
| Realtek Semiconductor           | 38        | 8.48%   |
| Realtek                         | 23        | 5.13%   |
| Broadcom                        | 17        | 3.79%   |
| Foxconn / Hon Hai               | 11        | 2.46%   |
| Lite-On Technology              | 8         | 1.79%   |
| IMC Networks                    | 8         | 1.79%   |
| Apple                           | 7         | 1.56%   |
| Opticis                         | 4         | 0.89%   |
| Dell                            | 4         | 0.89%   |
| Ralink                          | 3         | 0.67%   |
| Cambridge Silicon Radio         | 3         | 0.67%   |
| Taiyo Yuden                     | 2         | 0.45%   |
| Alps Electric                   | 2         | 0.45%   |
| Toshiba                         | 1         | 0.22%   |
| Hewlett-Packard                 | 1         | 0.22%   |
| Foxconn International           | 1         | 0.22%   |
| ASUSTek Computer                | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 102       | 22.77%  |
| Intel Bluetooth Device                              | 55        | 12.28%  |
| Intel AX200 Bluetooth                               | 47        | 10.49%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 44        | 9.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 27        | 6.03%   |
| Realtek Bluetooth Radio                             | 25        | 5.58%   |
| Realtek Bluetooth Radio                             | 23        | 5.13%   |
| Intel AX210 Bluetooth                               | 9         | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.56%   |
| Realtek RTL8723B Bluetooth                          | 6         | 1.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.89%   |
| Opticis Bluetooth Radio                             | 4         | 0.89%   |
| Lite-On Bluetooth Device                            | 4         | 0.89%   |
| Ralink RT3290 Bluetooth                             | 3         | 0.67%   |
| IMC Networks Wireless_Device                        | 3         | 0.67%   |
| IMC Networks Bluetooth Device                       | 3         | 0.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 3         | 0.67%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.67%   |
| Apple Bluetooth Host Controller                     | 3         | 0.67%   |
| Taiyo Yuden Bluetooth Device                        | 2         | 0.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.45%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]         | 2         | 0.45%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.45%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.45%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.45%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 0.45%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.22%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.22%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.22%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.22%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.22%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.22%   |
| Foxconn / Hon Hai BCM2045A0                         | 1         | 0.22%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.22%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.22%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.22%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 0.22%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.22%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 0.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.22%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.22%   |
| Alps Electric Bluetooth Adapter                     | 1         | 0.22%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 394       | 60.99%  |
| AMD                              | 131       | 20.28%  |
| Nvidia                           | 101       | 15.63%  |
| Huawei Technologies              | 3         | 0.46%   |
| Apple                            | 3         | 0.46%   |
| Zhaoxin                          | 2         | 0.31%   |
| Silicon Integrated Systems [SiS] | 2         | 0.31%   |
| Generalplus Technology           | 2         | 0.31%   |
| C-Media Electronics              | 2         | 0.31%   |
| XMOS                             | 1         | 0.15%   |
| Specialix                        | 1         | 0.15%   |
| Realtek Semiconductor            | 1         | 0.15%   |
| JMTek                            | 1         | 0.15%   |
| BY EDIFIER                       | 1         | 0.15%   |
| ACTIONS                          | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 103       | 12.88%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 80        | 10%     |
| AMD Renoir Radeon High Definition Audio Controller                                                | 51        | 6.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 35        | 4.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 33        | 4.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 32        | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 32        | 4%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 2.63%   |
| Nvidia Audio device                                                                               | 19        | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 19        | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 18        | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 2.25%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 17        | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 2.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 2%      |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.63%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 1.38%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.13%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 1.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 0.63%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.38%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.38%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.38%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.38%   |
| Huawei Technologies USB-C HEADSET                                                                 | 3         | 0.38%   |
| Apple Audio Device                                                                                | 3         | 0.38%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.38%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.38%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 2         | 0.25%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 2         | 0.25%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.25%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.25%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 0.25%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.25%   |
| Generalplus Technology IMYB 7.1 Channel                                                           | 2         | 0.25%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.25%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.25%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.25%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 129       | 33.42%  |
| SK hynix            | 96        | 24.87%  |
| Micron Technology   | 46        | 11.92%  |
| Kingston            | 41        | 10.62%  |
| Unknown             | 18        | 4.66%   |
| Ramaxel Technology  | 15        | 3.89%   |
| Crucial             | 8         | 2.07%   |
| A-DATA Technology   | 6         | 1.55%   |
| Elpida              | 5         | 1.3%    |
| Transcend           | 4         | 1.04%   |
| Unknown (ABCD)      | 3         | 0.78%   |
| Corsair             | 2         | 0.52%   |
| Apacer              | 2         | 0.52%   |
| Unknown (08C8)      | 1         | 0.26%   |
| Unknown (08B5)      | 1         | 0.26%   |
| Team                | 1         | 0.26%   |
| Shenzhen WODPOSIT   | 1         | 0.26%   |
| SHARETRONIC         | 1         | 0.26%   |
| Nanya Technology    | 1         | 0.26%   |
| MTASE               | 1         | 0.26%   |
| Lexar Co Limited    | 1         | 0.26%   |
| Lenovo              | 1         | 0.26%   |
| G.Skill             | 1         | 0.26%   |
| Essencore           | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 10        | 2.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 9         | 2.21%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s        | 7         | 1.72%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 5         | 1.23%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 5         | 1.23%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 5         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 5         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 5         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 5         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 4         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 0.98%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.98%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s         | 4         | 0.98%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 4         | 0.98%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s      | 4         | 0.98%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                | 4         | 0.98%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s             | 4         | 0.98%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.74%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 3         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 3         | 0.74%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 3         | 0.74%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 3         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 0.74%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.74%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 3         | 0.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 3         | 0.74%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.74%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 3         | 0.74%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 3         | 0.74%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s           | 3         | 0.74%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 3         | 0.74%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 3         | 0.74%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s               | 3         | 0.74%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s             | 3         | 0.74%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 2         | 0.49%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                | 2         | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.49%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.49%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s              | 2         | 0.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 2         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s              | 2         | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.49%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.49%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.49%   |
| SK hynix RAM H9HCNNNCPUMLHR-NME 4096MB SODIMM LPDDR4 3733MT/s       | 2         | 0.49%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.49%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 2         | 0.49%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s              | 2         | 0.49%   |
| Samsung RAM M473B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.49%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.49%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 2         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 202       | 59.59%  |
| DDR3    | 77        | 22.71%  |
| LPDDR3  | 27        | 7.96%   |
| LPDDR4  | 20        | 5.9%    |
| DDR2    | 5         | 1.47%   |
| Unknown | 4         | 1.18%   |
| SDRAM   | 3         | 0.88%   |
| DDR     | 1         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 254       | 74.93%  |
| Row Of Chips | 81        | 23.89%  |
| Chip         | 3         | 0.88%   |
| DIMM         | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 173       | 48.32%  |
| 4096  | 104       | 29.05%  |
| 16384 | 47        | 13.13%  |
| 2048  | 21        | 5.87%   |
| 32768 | 8         | 2.23%   |
| 1024  | 5         | 1.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 95        | 26.99%  |
| 3200    | 83        | 23.58%  |
| 1600    | 60        | 17.05%  |
| 2133    | 26        | 7.39%   |
| 2400    | 23        | 6.53%   |
| 4267    | 13        | 3.69%   |
| 1867    | 12        | 3.41%   |
| 1333    | 7         | 1.99%   |
| 1334    | 6         | 1.7%    |
| 3266    | 3         | 0.85%   |
| 1067    | 3         | 0.85%   |
| 667     | 3         | 0.85%   |
| 4800    | 2         | 0.57%   |
| 4199    | 2         | 0.57%   |
| 3733    | 2         | 0.57%   |
| 2666    | 2         | 0.57%   |
| 266     | 2         | 0.57%   |
| 6400    | 1         | 0.28%   |
| 4266    | 1         | 0.28%   |
| 3000    | 1         | 0.28%   |
| 2933    | 1         | 0.28%   |
| 2048    | 1         | 0.28%   |
| 1066    | 1         | 0.28%   |
| 800     | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 66.67%  |
| Canon           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| HP Officejet 4500 G510g-m | 1         | 33.33%  |
| HP LaserJet 1020          | 1         | 33.33%  |
| Canon iP1100 series       | 1         | 33.33%  |

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
| Chicony Electronics                    | 97        | 20.82%  |
| IMC Networks                           | 75        | 16.09%  |
| Acer                                   | 53        | 11.37%  |
| Realtek Semiconductor                  | 32        | 6.87%   |
| Microdia                               | 31        | 6.65%   |
| Sunplus Innovation Technology          | 29        | 6.22%   |
| Quanta                                 | 26        | 5.58%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 5.58%   |
| Syntek                                 | 16        | 3.43%   |
| Suyin                                  | 15        | 3.22%   |
| Lite-On Technology                     | 10        | 2.15%   |
| Luxvisions Innotech Limited            | 8         | 1.72%   |
| Apple                                  | 7         | 1.5%    |
| Silicon Motion                         | 5         | 1.07%   |
| Alcor Micro                            | 5         | 1.07%   |
| Ricoh                                  | 4         | 0.86%   |
| Logitech                               | 3         | 0.64%   |
| Lenovo                                 | 3         | 0.64%   |
| Importek                               | 3         | 0.64%   |
| Z-Star Microelectronics                | 2         | 0.43%   |
| Nebraska Furniture Mart                | 2         | 0.43%   |
| GEMBIRD                                | 2         | 0.43%   |
| Y Media                                | 1         | 0.21%   |
| Unknown                                | 1         | 0.21%   |
| U0AS01A-0                              | 1         | 0.21%   |
| Sonix Technology                       | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| Mitsumi                                | 1         | 0.21%   |
| icSpring                               | 1         | 0.21%   |
| Google                                 | 1         | 0.21%   |
| Goodong Industry                       | 1         | 0.21%   |
| Genesys Logic                          | 1         | 0.21%   |
| Cypress Semiconductor                  | 1         | 0.21%   |
| Cubeternet                             | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 42        | 8.97%   |
| IMC Networks Integrated Camera                                             | 29        | 6.2%    |
| Microdia Integrated_Webcam_HD                                              | 22        | 4.7%    |
| Acer Integrated Camera                                                     | 20        | 4.27%   |
| IMC Networks HD Camera                                                     | 19        | 4.06%   |
| Realtek Integrated_Webcam_HD                                               | 12        | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam               | 12        | 2.56%   |
| Chicony HD Webcam                                                          | 11        | 2.35%   |
| Syntek Integrated Camera                                                   | 10        | 2.14%   |
| Sunplus Integrated_Webcam_HD                                               | 10        | 2.14%   |
| Quanta hm1091_techfront                                                    | 7         | 1.5%    |
| Sunplus HD WebCam                                                          | 6         | 1.28%   |
| Realtek Integrated Webcam                                                  | 6         | 1.28%   |
| Quanta HP HD Camera                                                        | 6         | 1.28%   |
| Luxvisions Innotech Limited Integrated Camera                              | 6         | 1.28%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 6         | 1.28%   |
| IMC Networks ov9734_azurewave_camera                                       | 6         | 1.28%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 6         | 1.28%   |
| Acer BisonCam, NB Pro                                                      | 6         | 1.28%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 5         | 1.07%   |
| Realtek HP Wide Vision HD Camera                                           | 5         | 1.07%   |
| Quanta HD User Facing                                                      | 5         | 1.07%   |
| Lite-On Integrated Camera                                                  | 5         | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 5         | 1.07%   |
| Acer Lenovo EasyCamera                                                     | 5         | 1.07%   |
| Silicon Motion 300k Pixel Camera                                           | 4         | 0.85%   |
| IMC Networks Lenovo EasyCamera                                             | 4         | 0.85%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 4         | 0.85%   |
| Chicony Integrated Camera (1280x720@30)                                    | 4         | 0.85%   |
| Chicony HP HD Camera                                                       | 4         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 0.85%   |
| Acer SunplusIT Integrated Camera                                           | 4         | 0.85%   |
| Syntek Lenovo EasyCamera                                                   | 3         | 0.64%   |
| Suyin 1.3M HD WebCam                                                       | 3         | 0.64%   |
| Sunplus HP Wide Vision HD                                                  | 3         | 0.64%   |
| Microdia Webcam Vitade AF                                                  | 3         | 0.64%   |
| Lite-On HP HD Camera                                                       | 3         | 0.64%   |
| Chicony USB 2.0 Camera                                                     | 3         | 0.64%   |
| Chicony HP Wide Vision HD Camera                                           | 3         | 0.64%   |
| Chicony EasyCamera                                                         | 3         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 3         | 0.64%   |
| Acer ThinkPad Integrated Camera                                            | 3         | 0.64%   |
| Acer HD Webcam                                                             | 3         | 0.64%   |
| Acer BisonCam,NB Pro                                                       | 3         | 0.64%   |
| Syntek EasyCamera                                                          | 2         | 0.43%   |
| Suyin Lenovo EasyCamera                                                    | 2         | 0.43%   |
| Suyin Integrated_Webcam_HD                                                 | 2         | 0.43%   |
| Suyin Integrated Webcam                                                    | 2         | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 2         | 0.43%   |
| Sunplus Integrated_Webcam_FHD                                              | 2         | 0.43%   |
| Realtek USB Camera                                                         | 2         | 0.43%   |
| Realtek Lenovo EasyCamera                                                  | 2         | 0.43%   |
| Quanta ov9734_techfront_camera                                             | 2         | 0.43%   |
| Nebraska Furniture Mart USB 2.0 PC cam                                     | 2         | 0.43%   |
| Importek TOSHIBA Web Camera - HD                                           | 2         | 0.43%   |
| IMC Networks SunplusIT Integrated Camera                                   | 2         | 0.43%   |
| Chicony Lenovo Integrated Webcam                                           | 2         | 0.43%   |
| Chicony HD User Facing                                                     | 2         | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 2         | 0.43%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 47        | 33.81%  |
| Validity Sensors           | 36        | 25.9%   |
| Synaptics                  | 32        | 23.02%  |
| Elan Microelectronics      | 11        | 7.91%   |
| Upek                       | 8         | 5.76%   |
| AuthenTec                  | 3         | 2.16%   |
| STMicroelectronics         | 1         | 0.72%   |
| LighTuning Technology      | 1         | 0.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 25        | 17.99%  |
| Shenzhen Goodix Fingerprint Reader                                         | 20        | 14.39%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 12.95%  |
| Elan ELAN:Fingerprint                                                      | 10        | 7.19%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 6.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 5.04%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 5.04%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 4.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.88%   |
| Validity Sensors VFS491                                                    | 3         | 2.16%   |
| Synaptics WBDI Device                                                      | 3         | 2.16%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 1.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.44%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.44%   |
| Unknown                                                                    | 2         | 1.44%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.72%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.72%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.72%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.72%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.72%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.72%   |
| AuthenTec AES2810                                                          | 1         | 0.72%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 80%     |
| Upek        | 1         | 6.67%   |
| Clay Logic  | 1         | 6.67%   |
| Alcor Micro | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 13.33%  |
| Broadcom 58200                                                               | 2         | 13.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.67%   |
| Clay Logic CanoKey                                                           | 1         | 6.67%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 283       | 51.74%  |
| 1     | 217       | 39.67%  |
| 2     | 38        | 6.95%   |
| 4     | 4         | 0.73%   |
| 3     | 3         | 0.55%   |
| 8     | 1         | 0.18%   |
| 5     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 136       | 43.17%  |
| Graphics card            | 77        | 24.44%  |
| Multimedia controller    | 22        | 6.98%   |
| Net/wireless             | 20        | 6.35%   |
| Chipcard                 | 14        | 4.44%   |
| Communication controller | 9         | 2.86%   |
| Sound                    | 8         | 2.54%   |
| Camera                   | 8         | 2.54%   |
| Bluetooth                | 8         | 2.54%   |
| Network                  | 4         | 1.27%   |
| Storage                  | 3         | 0.95%   |
| Card reader              | 2         | 0.63%   |
| Unassigned class         | 1         | 0.32%   |
| Storage/ata              | 1         | 0.32%   |
| Net/ethernet             | 1         | 0.32%   |
| Modem                    | 1         | 0.32%   |

