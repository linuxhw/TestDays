Linux in Tunisia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Tunisia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Tunisia/Desktop/README.md) and [notebooks](/Location/Tunisia/Notebook/README.md).

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

Total: 242

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [42d050d5ff](https://linux-hardware.org/?probe=42d050d5ff) | Feb 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [09df6de7db](https://linux-hardware.org/?probe=09df6de7db) | Feb 23, 2023 |
| ASUSTek       | UX330CAK                    | Notebook    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [1c8bb5ecfc](https://linux-hardware.org/?probe=1c8bb5ecfc) | Feb 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4cb7a5f214](https://linux-hardware.org/?probe=4cb7a5f214) | Jan 30, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [0eb0b40b2b](https://linux-hardware.org/?probe=0eb0b40b2b) | Jan 23, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [391c3404d3](https://linux-hardware.org/?probe=391c3404d3) | Jan 20, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [993adedd8e](https://linux-hardware.org/?probe=993adedd8e) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a279a876f3](https://linux-hardware.org/?probe=a279a876f3) | Jan 17, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [a48fadfcbd](https://linux-hardware.org/?probe=a48fadfcbd) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [11202d4caa](https://linux-hardware.org/?probe=11202d4caa) | Dec 11, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [8a112e02eb](https://linux-hardware.org/?probe=8a112e02eb) | Dec 11, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [00c90e5b24](https://linux-hardware.org/?probe=00c90e5b24) | Dec 08, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [307022e985](https://linux-hardware.org/?probe=307022e985) | Nov 30, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [778a84af28](https://linux-hardware.org/?probe=778a84af28) | Nov 28, 2022 |
| HP            | Pavilion g6                 | Notebook    | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [50c70cb811](https://linux-hardware.org/?probe=50c70cb811) | Nov 20, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [27756e9ad7](https://linux-hardware.org/?probe=27756e9ad7) | Nov 20, 2022 |
| Intel         | H81                         | Desktop     | [f99a623867](https://linux-hardware.org/?probe=f99a623867) | Nov 17, 2022 |
| Intel         | H81                         | Desktop     | [5bfd56a1f8](https://linux-hardware.org/?probe=5bfd56a1f8) | Nov 17, 2022 |
| AZW           | Gemini M                    | Desktop     | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [9c732b8892](https://linux-hardware.org/?probe=9c732b8892) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [f7cd80c534](https://linux-hardware.org/?probe=f7cd80c534) | Nov 14, 2022 |
| ASUSTek       | UX330CAK                    | Notebook    | [bd7d377985](https://linux-hardware.org/?probe=bd7d377985) | Nov 14, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [bc0831aa5e](https://linux-hardware.org/?probe=bc0831aa5e) | Nov 13, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c4811dfc5e](https://linux-hardware.org/?probe=c4811dfc5e) | Nov 12, 2022 |
| Pegatron      | Benicia                     | Desktop     | [f345c0beb9](https://linux-hardware.org/?probe=f345c0beb9) | Nov 11, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [122263e850](https://linux-hardware.org/?probe=122263e850) | Nov 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7b65a89d4f](https://linux-hardware.org/?probe=7b65a89d4f) | Nov 04, 2022 |
| HP            | 14                          | Notebook    | [7611c14813](https://linux-hardware.org/?probe=7611c14813) | Oct 31, 2022 |
| Lenovo        | ThinkPad E15 20RD001QFE     | Notebook    | [cc9f8c3aad](https://linux-hardware.org/?probe=cc9f8c3aad) | Oct 26, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [bb2647f6c8](https://linux-hardware.org/?probe=bb2647f6c8) | Oct 24, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [bec3ad2194](https://linux-hardware.org/?probe=bec3ad2194) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [f80eb01da1](https://linux-hardware.org/?probe=f80eb01da1) | Oct 13, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [f44ca565c1](https://linux-hardware.org/?probe=f44ca565c1) | Oct 11, 2022 |
| MSI           | MS-B0A41                    | Desktop     | [a0d7f23a22](https://linux-hardware.org/?probe=a0d7f23a22) | Oct 05, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [ad367d006a](https://linux-hardware.org/?probe=ad367d006a) | Sep 22, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [eed790913e](https://linux-hardware.org/?probe=eed790913e) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [22a1cba716](https://linux-hardware.org/?probe=22a1cba716) | Sep 02, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [4fdb057f33](https://linux-hardware.org/?probe=4fdb057f33) | Sep 02, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [659506d72f](https://linux-hardware.org/?probe=659506d72f) | Sep 02, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [739cbda612](https://linux-hardware.org/?probe=739cbda612) | Sep 02, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [a557da948a](https://linux-hardware.org/?probe=a557da948a) | Aug 31, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| HP            | 2AF7                        | Desktop     | [7605e926c4](https://linux-hardware.org/?probe=7605e926c4) | Aug 25, 2022 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [f3facd36da](https://linux-hardware.org/?probe=f3facd36da) | Aug 24, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [f0d245ec0f](https://linux-hardware.org/?probe=f0d245ec0f) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f4fedfb271](https://linux-hardware.org/?probe=f4fedfb271) | Aug 14, 2022 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [7dab66307c](https://linux-hardware.org/?probe=7dab66307c) | Aug 09, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [c57b484523](https://linux-hardware.org/?probe=c57b484523) | Aug 07, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [672cb969fb](https://linux-hardware.org/?probe=672cb969fb) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [edfabf845b](https://linux-hardware.org/?probe=edfabf845b) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 20RA000KFE     | Notebook    | [7193e153ff](https://linux-hardware.org/?probe=7193e153ff) | Jul 20, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Packard Be... | EasyNote ML65               | Notebook    | [c8c6125dc3](https://linux-hardware.org/?probe=c8c6125dc3) | Jul 06, 2022 |
| Packard Be... | EasyNote ML65               | Notebook    | [09d1580fd5](https://linux-hardware.org/?probe=09d1580fd5) | Jul 06, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [2459fb8d6e](https://linux-hardware.org/?probe=2459fb8d6e) | Jul 03, 2022 |
| Dell          | Inspiron N5040              | Notebook    | [81e318d1d5](https://linux-hardware.org/?probe=81e318d1d5) | Jul 03, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | Desktop     | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| HP            | ProBook 455 G3              | Notebook    | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [2218dd9966](https://linux-hardware.org/?probe=2218dd9966) | Jun 07, 2022 |
| Dell          | 05842Y A00                  | Desktop     | [7c67079823](https://linux-hardware.org/?probe=7c67079823) | May 19, 2022 |
| ASUSTek       | X556UV                      | Notebook    | [39b927dfdc](https://linux-hardware.org/?probe=39b927dfdc) | May 11, 2022 |
| Dell          | Latitude 3540               | Notebook    | [a97573f3cf](https://linux-hardware.org/?probe=a97573f3cf) | Apr 29, 2022 |
| Dell          | Latitude 3540               | Notebook    | [a6b8509194](https://linux-hardware.org/?probe=a6b8509194) | Apr 29, 2022 |
| Toshiba       | Satellite Pro L850-B339     | Notebook    | [d884eeae8f](https://linux-hardware.org/?probe=d884eeae8f) | Apr 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [af0e50e873](https://linux-hardware.org/?probe=af0e50e873) | Apr 14, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [9597b0a2d9](https://linux-hardware.org/?probe=9597b0a2d9) | Apr 09, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [03b34db583](https://linux-hardware.org/?probe=03b34db583) | Apr 05, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [e7a152d30a](https://linux-hardware.org/?probe=e7a152d30a) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7c0d1ce382](https://linux-hardware.org/?probe=7c0d1ce382) | Mar 29, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [bc07a3de3d](https://linux-hardware.org/?probe=bc07a3de3d) | Mar 15, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [ddbc85ab3a](https://linux-hardware.org/?probe=ddbc85ab3a) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [4b2b4e7f5a](https://linux-hardware.org/?probe=4b2b4e7f5a) | Mar 10, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [7803f9b898](https://linux-hardware.org/?probe=7803f9b898) | Feb 24, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [49a3015875](https://linux-hardware.org/?probe=49a3015875) | Feb 10, 2022 |
| Intel         | H61                         | Desktop     | [6d80839afa](https://linux-hardware.org/?probe=6d80839afa) | Feb 09, 2022 |
| HP            | Pavilion dv7                | Notebook    | [3bd981aa35](https://linux-hardware.org/?probe=3bd981aa35) | Feb 09, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEP... | Notebook    | [f814537586](https://linux-hardware.org/?probe=f814537586) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [09caab8240](https://linux-hardware.org/?probe=09caab8240) | Feb 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [75acdd40a6](https://linux-hardware.org/?probe=75acdd40a6) | Feb 07, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [06f3844911](https://linux-hardware.org/?probe=06f3844911) | Jan 30, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [0665a1599c](https://linux-hardware.org/?probe=0665a1599c) | Jan 26, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [22dd608151](https://linux-hardware.org/?probe=22dd608151) | Jan 07, 2022 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [391458138f](https://linux-hardware.org/?probe=391458138f) | Jan 07, 2022 |
| HP            | EliteBook 8740w             | Notebook    | [6f583dfeaf](https://linux-hardware.org/?probe=6f583dfeaf) | Dec 27, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [45a5de08c7](https://linux-hardware.org/?probe=45a5de08c7) | Dec 25, 2021 |
| HP            | Notebook                    | Notebook    | [032be84586](https://linux-hardware.org/?probe=032be84586) | Dec 09, 2021 |
| Toshiba       | Satellite C50-A489          | Notebook    | [4d29ea3b9c](https://linux-hardware.org/?probe=4d29ea3b9c) | Dec 04, 2021 |
| Lenovo        | ThinkPad X240 20AMA0WRFR    | Notebook    | [13fe3346fd](https://linux-hardware.org/?probe=13fe3346fd) | Dec 02, 2021 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [d0a08a7a23](https://linux-hardware.org/?probe=d0a08a7a23) | Nov 22, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [507c380abb](https://linux-hardware.org/?probe=507c380abb) | Nov 22, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [d49eff3d64](https://linux-hardware.org/?probe=d49eff3d64) | Nov 21, 2021 |
| Lenovo        | ThinkPad E15 20RD001SFE     | Notebook    | [358e3547b9](https://linux-hardware.org/?probe=358e3547b9) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD001SFE     | Notebook    | [694f05492e](https://linux-hardware.org/?probe=694f05492e) | Nov 17, 2021 |
| HP            | Compaq 6735s                | Notebook    | [6571a6fe6d](https://linux-hardware.org/?probe=6571a6fe6d) | Nov 15, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | Notebook    | [4bc0687791](https://linux-hardware.org/?probe=4bc0687791) | Nov 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [dcd2956978](https://linux-hardware.org/?probe=dcd2956978) | Nov 05, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a509e62c95](https://linux-hardware.org/?probe=a509e62c95) | Nov 05, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [60e3fe1197](https://linux-hardware.org/?probe=60e3fe1197) | Oct 26, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [8f6efb8dbe](https://linux-hardware.org/?probe=8f6efb8dbe) | Oct 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9b0872b3d4](https://linux-hardware.org/?probe=9b0872b3d4) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [9b74440deb](https://linux-hardware.org/?probe=9b74440deb) | Oct 07, 2021 |
| Acer          | Swift SF514-53T             | Notebook    | [e97a52d3d9](https://linux-hardware.org/?probe=e97a52d3d9) | Sep 28, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b882e1c0f7](https://linux-hardware.org/?probe=b882e1c0f7) | Sep 22, 2021 |
| HP            | 1494                        | Desktop     | [ae5165603a](https://linux-hardware.org/?probe=ae5165603a) | Sep 09, 2021 |
| HP            | 1494                        | Desktop     | [62e74e0c1a](https://linux-hardware.org/?probe=62e74e0c1a) | Sep 09, 2021 |
| HP            | 250 G4                      | Notebook    | [b5177b1c13](https://linux-hardware.org/?probe=b5177b1c13) | Sep 08, 2021 |
| HP            | 250 G4                      | Notebook    | [32899cab30](https://linux-hardware.org/?probe=32899cab30) | Sep 08, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e57d0a5518](https://linux-hardware.org/?probe=e57d0a5518) | Sep 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4cdb976c2](https://linux-hardware.org/?probe=d4cdb976c2) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [633e5a9649](https://linux-hardware.org/?probe=633e5a9649) | Aug 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [58fb87de66](https://linux-hardware.org/?probe=58fb87de66) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8d891b7431](https://linux-hardware.org/?probe=8d891b7431) | Aug 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [726ed18d47](https://linux-hardware.org/?probe=726ed18d47) | Jul 25, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | Notebook    | [a347415235](https://linux-hardware.org/?probe=a347415235) | Jul 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [98862925dc](https://linux-hardware.org/?probe=98862925dc) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6ce3d213a](https://linux-hardware.org/?probe=b6ce3d213a) | Jul 06, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [af8d7a6b6f](https://linux-hardware.org/?probe=af8d7a6b6f) | Jun 22, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [77faf70869](https://linux-hardware.org/?probe=77faf70869) | Jun 14, 2021 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [8488c59a11](https://linux-hardware.org/?probe=8488c59a11) | May 18, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [fe125a0b5f](https://linux-hardware.org/?probe=fe125a0b5f) | May 10, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [89cfbb6a0e](https://linux-hardware.org/?probe=89cfbb6a0e) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [884b3d6f69](https://linux-hardware.org/?probe=884b3d6f69) | Apr 21, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [50e1fa29fb](https://linux-hardware.org/?probe=50e1fa29fb) | Apr 16, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [be7a218721](https://linux-hardware.org/?probe=be7a218721) | Apr 12, 2021 |
| Dell          | Latitude E6420              | Notebook    | [901b94b26d](https://linux-hardware.org/?probe=901b94b26d) | Mar 10, 2021 |
| Dell          | Latitude E6420              | Notebook    | [c0d9f82152](https://linux-hardware.org/?probe=c0d9f82152) | Mar 10, 2021 |
| Dell          | Latitude E5440              | Notebook    | [89089cf0ad](https://linux-hardware.org/?probe=89089cf0ad) | Mar 05, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [347d45179a](https://linux-hardware.org/?probe=347d45179a) | Jan 30, 2021 |
| Acer          | Aspire V5-561G              | Notebook    | [4829da6130](https://linux-hardware.org/?probe=4829da6130) | Jan 30, 2021 |
| Dell          | Latitude 7410               | Notebook    | [19e75431d4](https://linux-hardware.org/?probe=19e75431d4) | Jan 30, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [07f0354547](https://linux-hardware.org/?probe=07f0354547) | Jan 29, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [5b18be0dd0](https://linux-hardware.org/?probe=5b18be0dd0) | Jan 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [cb1f74adbd](https://linux-hardware.org/?probe=cb1f74adbd) | Jan 17, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [f4c57eb290](https://linux-hardware.org/?probe=f4c57eb290) | Jan 17, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [95610ff17c](https://linux-hardware.org/?probe=95610ff17c) | Jan 14, 2021 |
| Dell          | Inspiron 3520               | Notebook    | [c1e7a232e0](https://linux-hardware.org/?probe=c1e7a232e0) | Dec 29, 2020 |
| eMachines     | E725                        | Notebook    | [aa660241b3](https://linux-hardware.org/?probe=aa660241b3) | Dec 22, 2020 |
| Dell          | Latitude 7490               | Notebook    | [d42995d26a](https://linux-hardware.org/?probe=d42995d26a) | Dec 21, 2020 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [f52e267cc9](https://linux-hardware.org/?probe=f52e267cc9) | Dec 19, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [e4ab77e8b0](https://linux-hardware.org/?probe=e4ab77e8b0) | Dec 11, 2020 |
| Lenovo        | ThinkPad E15 20RD001QFE     | Notebook    | [d02175d76c](https://linux-hardware.org/?probe=d02175d76c) | Dec 10, 2020 |
| ASUSTek       | UX310UQK                    | Notebook    | [bb566782bc](https://linux-hardware.org/?probe=bb566782bc) | Dec 04, 2020 |
| HP            | Convertible x360 11-ab0X... | Convertible | [6b543e87f8](https://linux-hardware.org/?probe=6b543e87f8) | Nov 26, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [963065205e](https://linux-hardware.org/?probe=963065205e) | Nov 26, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [c1aeee5a95](https://linux-hardware.org/?probe=c1aeee5a95) | Nov 26, 2020 |
| ASUSTek       | X550VX                      | Notebook    | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [563be9ddd8](https://linux-hardware.org/?probe=563be9ddd8) | Nov 21, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [59de1f8260](https://linux-hardware.org/?probe=59de1f8260) | Nov 20, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [64cce3acaa](https://linux-hardware.org/?probe=64cce3acaa) | Nov 04, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [97dee881c4](https://linux-hardware.org/?probe=97dee881c4) | Nov 01, 2020 |
| Dell          | 0TTDMJ A00                  | Desktop     | [aef24f2346](https://linux-hardware.org/?probe=aef24f2346) | Oct 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [a236e15c5d](https://linux-hardware.org/?probe=a236e15c5d) | Oct 25, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [f81c8f31d1](https://linux-hardware.org/?probe=f81c8f31d1) | Oct 10, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [bb4464e5f1](https://linux-hardware.org/?probe=bb4464e5f1) | Oct 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7bf6a7c3a4](https://linux-hardware.org/?probe=7bf6a7c3a4) | Sep 16, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [cdce66a7de](https://linux-hardware.org/?probe=cdce66a7de) | Jul 07, 2020 |
| ASUSTek       | UX360CA                     | Notebook    | [9d6a79d7ac](https://linux-hardware.org/?probe=9d6a79d7ac) | Jun 11, 2020 |
| ASUSTek       | UX360CA                     | Notebook    | [24742e9ec9](https://linux-hardware.org/?probe=24742e9ec9) | Jun 11, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [1cb682ea0f](https://linux-hardware.org/?probe=1cb682ea0f) | Jun 06, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [65d6dca78e](https://linux-hardware.org/?probe=65d6dca78e) | May 27, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [31501ab61b](https://linux-hardware.org/?probe=31501ab61b) | May 11, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [b8e2396d82](https://linux-hardware.org/?probe=b8e2396d82) | May 11, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4ff939d0e2](https://linux-hardware.org/?probe=4ff939d0e2) | Apr 28, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [31b3c13f93](https://linux-hardware.org/?probe=31b3c13f93) | Apr 28, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [73f10216d6](https://linux-hardware.org/?probe=73f10216d6) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [b5721fa9d5](https://linux-hardware.org/?probe=b5721fa9d5) | Apr 22, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [b391bbea48](https://linux-hardware.org/?probe=b391bbea48) | Apr 12, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [30a8d59bdc](https://linux-hardware.org/?probe=30a8d59bdc) | Apr 09, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [fc6eaad779](https://linux-hardware.org/?probe=fc6eaad779) | Apr 09, 2020 |
| ASUSTek       | X556UV                      | Notebook    | [cb5da8627a](https://linux-hardware.org/?probe=cb5da8627a) | Apr 07, 2020 |
| MSI           | MS-7502 Fab D               | Desktop     | [242c5b8d0d](https://linux-hardware.org/?probe=242c5b8d0d) | Mar 30, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [71dbec47eb](https://linux-hardware.org/?probe=71dbec47eb) | Mar 27, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [cc439d9e0f](https://linux-hardware.org/?probe=cc439d9e0f) | Mar 27, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [cb7137a57a](https://linux-hardware.org/?probe=cb7137a57a) | Mar 16, 2020 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [64628c8c11](https://linux-hardware.org/?probe=64628c8c11) | Mar 12, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [7c6e2d2c29](https://linux-hardware.org/?probe=7c6e2d2c29) | Mar 10, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [77bc52c3d9](https://linux-hardware.org/?probe=77bc52c3d9) | Mar 02, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [84ee26b4e7](https://linux-hardware.org/?probe=84ee26b4e7) | Mar 02, 2020 |
| Pegatron      | Eureka3                     | Desktop     | [33ae5ebabc](https://linux-hardware.org/?probe=33ae5ebabc) | Feb 18, 2020 |
| ASUSTek       | X550JX                      | Notebook    | [a1fa3183ed](https://linux-hardware.org/?probe=a1fa3183ed) | Feb 15, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [97b5418b6d](https://linux-hardware.org/?probe=97b5418b6d) | Feb 03, 2020 |
| Lenovo        | ThinkPad T440s 20AQ005NU... | Notebook    | [55d9286a1b](https://linux-hardware.org/?probe=55d9286a1b) | Jan 27, 2020 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [7878eb9e27](https://linux-hardware.org/?probe=7878eb9e27) | Dec 30, 2019 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [21f916c3ef](https://linux-hardware.org/?probe=21f916c3ef) | Dec 30, 2019 |
| Acer          | Aspire E1-570               | Notebook    | [9d92944e6c](https://linux-hardware.org/?probe=9d92944e6c) | Dec 21, 2019 |
| Acer          | Aspire E1-570               | Notebook    | [64702aadcd](https://linux-hardware.org/?probe=64702aadcd) | Dec 21, 2019 |
| Lenovo        | Unknown                     | Notebook    | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Sony          | VPCEH36EF                   | Notebook    | [5b1adbe8f0](https://linux-hardware.org/?probe=5b1adbe8f0) | Dec 10, 2019 |
| Sony          | VPCEH36EF                   | Notebook    | [6518790628](https://linux-hardware.org/?probe=6518790628) | Nov 27, 2019 |
| Dell          | Latitude E6420              | Notebook    | [3f252a50fb](https://linux-hardware.org/?probe=3f252a50fb) | Nov 12, 2019 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [1b5ae66e6f](https://linux-hardware.org/?probe=1b5ae66e6f) | Nov 10, 2019 |
| ASUSTek       | TUF Gaming FX705DD_TUF70... | Notebook    | [a9cc2a8ea0](https://linux-hardware.org/?probe=a9cc2a8ea0) | Nov 01, 2019 |
| Unknown       | Pine Trail - M CRB          | Desktop     | [ef1e6295a8](https://linux-hardware.org/?probe=ef1e6295a8) | Oct 30, 2019 |
| Foxconn       | 2ABF                        | Desktop     | [4521f814c9](https://linux-hardware.org/?probe=4521f814c9) | Sep 17, 2019 |
| Foxconn       | 2ABF                        | Desktop     | [6a57b2ea85](https://linux-hardware.org/?probe=6a57b2ea85) | Sep 17, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b57e5735a5](https://linux-hardware.org/?probe=b57e5735a5) | Sep 13, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [708bc2c339](https://linux-hardware.org/?probe=708bc2c339) | Sep 13, 2019 |
| HP            | 630                         | Notebook    | [8cb4c328bb](https://linux-hardware.org/?probe=8cb4c328bb) | Sep 10, 2019 |
| Acer          | Aspire V5-572G              | Notebook    | [7d046c01d0](https://linux-hardware.org/?probe=7d046c01d0) | Sep 07, 2019 |
| HP            | Pavilion g6                 | Notebook    | [6eebb27f65](https://linux-hardware.org/?probe=6eebb27f65) | Aug 28, 2019 |
| HP            | Laptop                      | Notebook    | [de71114421](https://linux-hardware.org/?probe=de71114421) | Aug 21, 2019 |
| Acer          | Aspire V5-572G              | Notebook    | [90d2c432d6](https://linux-hardware.org/?probe=90d2c432d6) | Aug 17, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [26b5185afb](https://linux-hardware.org/?probe=26b5185afb) | Aug 14, 2019 |
| Pegatron      | 2A94h                       | Desktop     | [3b6656bb11](https://linux-hardware.org/?probe=3b6656bb11) | Jul 04, 2019 |
| Acer          | TravelMate P259-M           | Notebook    | [3693d52bff](https://linux-hardware.org/?probe=3693d52bff) | Nov 09, 2018 |
| Acer          | TravelMate P259-M           | Notebook    | [a951fd5ef9](https://linux-hardware.org/?probe=a951fd5ef9) | Nov 09, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [83d0682234](https://linux-hardware.org/?probe=83d0682234) | Sep 20, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e2076e8303](https://linux-hardware.org/?probe=e2076e8303) | Sep 19, 2018 |
| HP            | Laptop 17-ak0xx             | Notebook    | [24599e9990](https://linux-hardware.org/?probe=24599e9990) | Sep 19, 2018 |
| HP            | Pavilion g6                 | Notebook    | [c93294c4ab](https://linux-hardware.org/?probe=c93294c4ab) | Sep 18, 2018 |
| HP            | Pavilion g6                 | Notebook    | [efc4afba58](https://linux-hardware.org/?probe=efc4afba58) | Aug 10, 2018 |
| HP            | Pavilion g6                 | Notebook    | [494e0c0416](https://linux-hardware.org/?probe=494e0c0416) | Aug 10, 2018 |
| Foxconn       | 2ABF                        | Desktop     | [f6873739a8](https://linux-hardware.org/?probe=f6873739a8) | Mar 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 39        | 22.67%  |
| Ubuntu 18.04       | 17        | 9.88%   |
| Ubuntu 22.04       | 13        | 7.56%   |
| Ubuntu 21.10       | 6         | 3.49%   |
| OpenMandriva 4.2   | 5         | 2.91%   |
| OpenMandriva 4.3   | 4         | 2.33%   |
| Zorin 16           | 3         | 1.74%   |
| Zorin 15           | 3         | 1.74%   |
| Ubuntu 19.10       | 3         | 1.74%   |
| Ubuntu 16.04       | 3         | 1.74%   |
| Pop!_OS 22.04      | 3         | 1.74%   |
| KDE neon 20.04     | 3         | 1.74%   |
| Debian 11          | 3         | 1.74%   |
| Debian 10          | 3         | 1.74%   |
| Ubuntu 21.04       | 2         | 1.16%   |
| Ubuntu 20.10       | 2         | 1.16%   |
| ROSA R10           | 2         | 1.16%   |
| ROSA 12.3          | 2         | 1.16%   |
| Pop!_OS 21.04      | 2         | 1.16%   |
| Manjaro 21.1.0     | 2         | 1.16%   |
| LMDE 4             | 2         | 1.16%   |
| Linux Mint 21.1    | 2         | 1.16%   |
| Linux Mint 20.3    | 2         | 1.16%   |
| Linux Mint 20.2    | 2         | 1.16%   |
| Linux Mint 20      | 2         | 1.16%   |
| KDE neon 22.04     | 2         | 1.16%   |
| Gentoo 2.8         | 2         | 1.16%   |
| Gentoo 2.7         | 2         | 1.16%   |
| Fedora 35          | 2         | 1.16%   |
| Fedora 33          | 2         | 1.16%   |
| ArcoLinux Rolling  | 2         | 1.16%   |
| Arch Rolling       | 2         | 1.16%   |
| Arch               | 2         | 1.16%   |
| Xubuntu 18.04      | 1         | 0.58%   |
| Ubuntu Unity 16.04 | 1         | 0.58%   |
| Ubuntu 19.04       | 1         | 0.58%   |
| Sodalite 35        | 1         | 0.58%   |
| ROSA R8.1          | 1         | 0.58%   |
| ROSA R11           | 1         | 0.58%   |
| Pop!_OS 20.10      | 1         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 81        | 49.69%  |
| OpenMandriva | 9         | 5.52%   |
| Linux Mint   | 9         | 5.52%   |
| Debian       | 7         | 4.29%   |
| Zorin        | 6         | 3.68%   |
| ROSA         | 6         | 3.68%   |
| Pop!_OS      | 6         | 3.68%   |
| Manjaro      | 5         | 3.07%   |
| Fedora       | 5         | 3.07%   |
| Arch         | 4         | 2.45%   |
| KDE neon     | 3         | 1.84%   |
| Gentoo       | 3         | 1.84%   |
| Endless      | 3         | 1.84%   |
| Lubuntu      | 2         | 1.23%   |
| LMDE         | 2         | 1.23%   |
| Elementary   | 2         | 1.23%   |
| ArcoLinux    | 2         | 1.23%   |
| Xubuntu      | 1         | 0.61%   |
| Ubuntu Unity | 1         | 0.61%   |
| Sodalite     | 1         | 0.61%   |
| MX           | 1         | 0.61%   |
| Kubuntu      | 1         | 0.61%   |
| Kali         | 1         | 0.61%   |
| Deepin       | 1         | 0.61%   |
| BlackPanther | 1         | 0.61%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.15.0-58-generic               | 5         | 2.7%    |
| 5.10.14-desktop-1omv4002        | 5         | 2.7%    |
| 5.16.7-desktop-1omv4003         | 4         | 2.16%   |
| 5.15.0-52-generic               | 4         | 2.16%   |
| 5.15.0-46-generic               | 4         | 2.16%   |
| 5.13.0-28-generic               | 4         | 2.16%   |
| 5.3.0-46-generic                | 3         | 1.62%   |
| 5.3.0-40-generic                | 3         | 1.62%   |
| 5.15.0-56-generic               | 3         | 1.62%   |
| 5.15.0-53-generic               | 3         | 1.62%   |
| 5.15.0-43-generic               | 3         | 1.62%   |
| 5.11.0-38-generic               | 3         | 1.62%   |
| 5.8.0-38-generic                | 2         | 1.08%   |
| 5.4.0-72-generic                | 2         | 1.08%   |
| 5.4.0-58-generic                | 2         | 1.08%   |
| 5.4.0-52-generic                | 2         | 1.08%   |
| 5.4.0-42-generic                | 2         | 1.08%   |
| 5.4.0-26-generic                | 2         | 1.08%   |
| 5.3.0-28-generic                | 2         | 1.08%   |
| 5.13.0-44-generic               | 2         | 1.08%   |
| 5.13.0-40-generic               | 2         | 1.08%   |
| 5.11.0-7620-generic             | 2         | 1.08%   |
| 5.11.0-40-generic               | 2         | 1.08%   |
| 5.11.0-27-generic               | 2         | 1.08%   |
| 5.10.27-gentoo                  | 2         | 1.08%   |
| 5.10.0-12-amd64                 | 2         | 1.08%   |
| 5.0.0-25-generic                | 2         | 1.08%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.08%   |
| 4.19.0-6-amd64                  | 2         | 1.08%   |
| 4.15.0-91-generic               | 2         | 1.08%   |
| 6.1.11-060111-generic           | 1         | 0.54%   |
| 5.9.9-arch1-1                   | 1         | 0.54%   |
| 5.9.1-arch1-1                   | 1         | 0.54%   |
| 5.8.15-301.fc33.x86_64          | 1         | 0.54%   |
| 5.8.0-55-generic                | 1         | 0.54%   |
| 5.8.0-50-generic                | 1         | 0.54%   |
| 5.8.0-44-generic                | 1         | 0.54%   |
| 5.8.0-40-generic                | 1         | 0.54%   |
| 5.8.0-33-generic                | 1         | 0.54%   |
| 5.8.0-32-generic                | 1         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 26        | 14.61%  |
| 5.15.0  | 23        | 12.92%  |
| 5.13.0  | 14        | 7.87%   |
| 5.11.0  | 12        | 6.74%   |
| 5.3.0   | 11        | 6.18%   |
| 5.8.0   | 10        | 5.62%   |
| 4.15.0  | 10        | 5.62%   |
| 5.0.0   | 7         | 3.93%   |
| 5.10.14 | 5         | 2.81%   |
| 5.19.0  | 4         | 2.25%   |
| 5.16.7  | 4         | 2.25%   |
| 4.19.0  | 4         | 2.25%   |
| 5.10.0  | 3         | 1.69%   |
| 4.18.0  | 3         | 1.69%   |
| 5.18.0  | 2         | 1.12%   |
| 5.17.5  | 2         | 1.12%   |
| 5.15.75 | 2         | 1.12%   |
| 5.10.27 | 2         | 1.12%   |
| 4.9.60  | 2         | 1.12%   |
| 6.1.11  | 1         | 0.56%   |
| 5.9.9   | 1         | 0.56%   |
| 5.9.1   | 1         | 0.56%   |
| 5.8.15  | 1         | 0.56%   |
| 5.6.14  | 1         | 0.56%   |
| 5.4.80  | 1         | 0.56%   |
| 5.4.143 | 1         | 0.56%   |
| 5.4.119 | 1         | 0.56%   |
| 5.3.8   | 1         | 0.56%   |
| 5.19.13 | 1         | 0.56%   |
| 5.17.15 | 1         | 0.56%   |
| 5.16.9  | 1         | 0.56%   |
| 5.16.18 | 1         | 0.56%   |
| 5.16.11 | 1         | 0.56%   |
| 5.15.84 | 1         | 0.56%   |
| 5.15.77 | 1         | 0.56%   |
| 5.15.76 | 1         | 0.56%   |
| 5.15.5  | 1         | 0.56%   |
| 5.15.46 | 1         | 0.56%   |
| 5.15.16 | 1         | 0.56%   |
| 5.15.11 | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 17.82%  |
| 5.4     | 28        | 16.09%  |
| 5.13    | 15        | 8.62%   |
| 5.11    | 14        | 8.05%   |
| 5.3     | 12        | 6.9%    |
| 5.10    | 12        | 6.9%    |
| 5.8     | 11        | 6.32%   |
| 4.15    | 10        | 5.75%   |
| 5.0     | 7         | 4.02%   |
| 5.16    | 6         | 3.45%   |
| 5.19    | 5         | 2.87%   |
| 4.19    | 4         | 2.3%    |
| 5.17    | 3         | 1.72%   |
| 4.9     | 3         | 1.72%   |
| 4.18    | 3         | 1.72%   |
| 5.9     | 2         | 1.15%   |
| 5.18    | 2         | 1.15%   |
| 6.1     | 1         | 0.57%   |
| 5.6     | 1         | 0.57%   |
| 5.14    | 1         | 0.57%   |
| 5.12    | 1         | 0.57%   |
| 4.4     | 1         | 0.57%   |
| 3.13    | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 156       | 97.5%   |
| i686    | 3         | 1.88%   |
| aarch64 | 1         | 0.63%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 94        | 56.29%  |
| KDE5            | 21        | 12.57%  |
| Unknown         | 17        | 10.18%  |
| X-Cinnamon      | 10        | 5.99%   |
| XFCE            | 7         | 4.19%   |
| KDE4            | 4         | 2.4%    |
| Pantheon        | 3         | 1.8%    |
| GNOME Flashback | 2         | 1.2%    |
| Unity           | 1         | 0.6%    |
| MATE            | 1         | 0.6%    |
| LXQt            | 1         | 0.6%    |
| LXDE            | 1         | 0.6%    |
| i3              | 1         | 0.6%    |
| GNOME Classic   | 1         | 0.6%    |
| DWM             | 1         | 0.6%    |
| Deepin          | 1         | 0.6%    |
| Cinnamon        | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 124       | 74.7%   |
| Wayland | 33        | 19.88%  |
| Unknown | 5         | 3.01%   |
| Tty     | 4         | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 64        | 39.02%  |
| GDM     | 45        | 27.44%  |
| SDDM    | 20        | 12.2%   |
| GDM3    | 20        | 12.2%   |
| LightDM | 11        | 6.71%   |
| KDM     | 4         | 2.44%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 79        | 48.47%  |
| fr_FR   | 48        | 29.45%  |
| Unknown | 19        | 11.66%  |
| en_GB   | 5         | 3.07%   |
| C       | 3         | 1.84%   |
| pt_BR   | 2         | 1.23%   |
| ar_TN   | 2         | 1.23%   |
| en_IN   | 1         | 0.61%   |
| en_CA   | 1         | 0.61%   |
| en_AU   | 1         | 0.61%   |
| en_AG   | 1         | 0.61%   |
| de_DE   | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 93        | 56.36%  |
| BIOS | 72        | 43.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 140       | 86.96%  |
| Overlay | 11        | 6.83%   |
| Unknown | 6         | 3.73%   |
| Btrfs   | 3         | 1.86%   |
| Xfs     | 1         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 45.68%  |
| GPT     | 64        | 39.51%  |
| MBR     | 24        | 14.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 87.12%  |
| Yes       | 21        | 12.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 65.41%  |
| Yes       | 55        | 34.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 40        | 25.16%  |
| ASUSTek Computer        | 28        | 17.61%  |
| Hewlett-Packard         | 25        | 15.72%  |
| Dell                    | 21        | 13.21%  |
| MSI                     | 11        | 6.92%   |
| Acer                    | 10        | 6.29%   |
| Toshiba                 | 6         | 3.77%   |
| Pegatron                | 4         | 2.52%   |
| Samsung Electronics     | 2         | 1.26%   |
| Intel                   | 2         | 1.26%   |
| Foxconn                 | 2         | 1.26%   |
| Sony                    | 1         | 0.63%   |
| Raspberry Pi Foundation | 1         | 0.63%   |
| Packard Bell            | 1         | 0.63%   |
| Gigabyte Technology     | 1         | 0.63%   |
| eMachines               | 1         | 0.63%   |
| AZW                     | 1         | 0.63%   |
| ASRock                  | 1         | 0.63%   |
| Unknown                 | 1         | 0.63%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 3         | 1.89%   |
| HP Pavilion g6                          | 3         | 1.89%   |
| Pegatron VS342AA-AB6 m9801af            | 2         | 1.26%   |
| Lenovo IdeaPad 700-15ISK 80RU           | 2         | 1.26%   |
| Lenovo IdeaPad 5 15ITL05 82FG           | 2         | 1.26%   |
| Lenovo IdeaPad 130-15IKB 81H7           | 2         | 1.26%   |
| HP Pavilion Gaming Laptop 15-ec1xxx     | 2         | 1.26%   |
| Foxconn Pro 3400 Series MT              | 2         | 1.26%   |
| Dell Inspiron 5570                      | 2         | 1.26%   |
| ASUS X556UV                             | 2         | 1.26%   |
| ASUS X553MA                             | 2         | 1.26%   |
| ASUS X550JX                             | 2         | 1.26%   |
| Unknown                                 | 2         | 1.26%   |
| Toshiba Satellite Pro L850-B339         | 1         | 0.63%   |
| Toshiba Satellite L550                  | 1         | 0.63%   |
| Toshiba Satellite L500                  | 1         | 0.63%   |
| Toshiba Satellite C650D                 | 1         | 0.63%   |
| Toshiba Satellite C50-A489              | 1         | 0.63%   |
| Toshiba Satellite A300                  | 1         | 0.63%   |
| Sony VPCEH36EF                          | 1         | 0.63%   |
| Samsung 530U3BI/530U4BI/530U4BH         | 1         | 0.63%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.63%   |
| RPi Raspberry Pi 3 Model B Rev 1.2      | 1         | 0.63%   |
| Pegatron Pro 3010 Microtower PC         | 1         | 0.63%   |
| Pegatron FL437AA-ABF a6641af            | 1         | 0.63%   |
| Packard Bell EasyNote ML65              | 1         | 0.63%   |
| MSI PRO H510 DP21 (MS-B0A4)             | 1         | 0.63%   |
| MSI MS-7C95                             | 1         | 0.63%   |
| MSI MS-7C52                             | 1         | 0.63%   |
| MSI MS-7C09                             | 1         | 0.63%   |
| MSI MS-7A15                             | 1         | 0.63%   |
| MSI MS-7817                             | 1         | 0.63%   |
| MSI MS-7502                             | 1         | 0.63%   |
| MSI Katana GF66 12UC                    | 1         | 0.63%   |
| MSI GF65 Thin 10UE                      | 1         | 0.63%   |
| MSI GF63 Thin 10SCXR                    | 1         | 0.63%   |
| MSI GF63 Thin 10SCSR                    | 1         | 0.63%   |
| Lenovo V310-15ISK 80SY                  | 1         | 0.63%   |
| Lenovo V15-IIL 82C5                     | 1         | 0.63%   |
| Lenovo V15-IGL 82C3                     | 1         | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 22        | 13.84%  |
| Dell Inspiron         | 10        | 6.29%   |
| HP Pavilion           | 9         | 5.66%   |
| Lenovo ThinkPad       | 8         | 5.03%   |
| Acer Aspire           | 7         | 4.4%    |
| Toshiba Satellite     | 6         | 3.77%   |
| Dell Latitude         | 6         | 3.77%   |
| HP Laptop             | 4         | 2.52%   |
| Dell OptiPlex         | 4         | 2.52%   |
| ASUS TUF              | 4         | 2.52%   |
| ASUS PRIME            | 3         | 1.89%   |
| Pegatron VS342AA-AB6  | 2         | 1.26%   |
| MSI GF63              | 2         | 1.26%   |
| HP ProBook            | 2         | 1.26%   |
| HP Compaq             | 2         | 1.26%   |
| HP 250                | 2         | 1.26%   |
| Foxconn Pro           | 2         | 1.26%   |
| ASUS ZenBook          | 2         | 1.26%   |
| ASUS X556UV           | 2         | 1.26%   |
| ASUS X553MA           | 2         | 1.26%   |
| ASUS X550JX           | 2         | 1.26%   |
| ASUS VivoBook         | 2         | 1.26%   |
| ASUS ROG              | 2         | 1.26%   |
| ASUS ASUS             | 2         | 1.26%   |
| Acer Swift            | 2         | 1.26%   |
| Unknown               | 2         | 1.26%   |
| Sony VPCEH36EF        | 1         | 0.63%   |
| Samsung 530U3BI       | 1         | 0.63%   |
| Samsung 300E5EV       | 1         | 0.63%   |
| RPi Raspberry         | 1         | 0.63%   |
| Pegatron Pro          | 1         | 0.63%   |
| Pegatron FL437AA-ABF  | 1         | 0.63%   |
| Packard Bell EasyNote | 1         | 0.63%   |
| MSI PRO               | 1         | 0.63%   |
| MSI MS-7C95           | 1         | 0.63%   |
| MSI MS-7C52           | 1         | 0.63%   |
| MSI MS-7C09           | 1         | 0.63%   |
| MSI MS-7A15           | 1         | 0.63%   |
| MSI MS-7817           | 1         | 0.63%   |
| MSI MS-7502           | 1         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 20        | 12.58%  |
| 2019    | 20        | 12.58%  |
| 2018    | 14        | 8.81%   |
| 2017    | 13        | 8.18%   |
| 2011    | 13        | 8.18%   |
| 2013    | 12        | 7.55%   |
| 2015    | 11        | 6.92%   |
| 2021    | 10        | 6.29%   |
| 2016    | 9         | 5.66%   |
| 2014    | 9         | 5.66%   |
| 2012    | 8         | 5.03%   |
| 2009    | 6         | 3.77%   |
| 2008    | 6         | 3.77%   |
| 2010    | 5         | 3.14%   |
| 2022    | 1         | 0.63%   |
| 2007    | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 124       | 77.99%  |
| Desktop        | 32        | 20.13%  |
| Convertible    | 2         | 1.26%   |
| System on chip | 1         | 0.63%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 147       | 91.88%  |
| Enabled  | 13        | 8.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 159       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 55        | 34.16%  |
| 16.01-24.0 | 32        | 19.88%  |
| 3.01-4.0   | 31        | 19.25%  |
| 8.01-16.0  | 29        | 18.01%  |
| 1.01-2.0   | 6         | 3.73%   |
| 32.01-64.0 | 5         | 3.11%   |
| 2.01-3.0   | 2         | 1.24%   |
| 0.51-1.0   | 1         | 0.62%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 54        | 30.34%  |
| 1.01-2.0  | 51        | 28.65%  |
| 4.01-8.0  | 32        | 17.98%  |
| 3.01-4.0  | 26        | 14.61%  |
| 0.51-1.0  | 6         | 3.37%   |
| 8.01-16.0 | 4         | 2.25%   |
| 0.01-0.5  | 4         | 2.25%   |
| Unknown   | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 116       | 71.17%  |
| 2      | 43        | 26.38%  |
| 4      | 2         | 1.23%   |
| 3      | 1         | 0.61%   |
| 0      | 1         | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 54.38%  |
| Yes       | 73        | 45.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 86.79%  |
| No        | 21        | 13.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 88.13%  |
| No        | 19        | 11.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 73.62%  |
| No        | 43        | 26.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Tunisia | 159       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tunis              | 94        | 53.11%  |
| Aryanah            | 10        | 5.65%   |
| Sousse             | 8         | 4.52%   |
| Bizerte            | 7         | 3.95%   |
| Nabeul             | 6         | 3.39%   |
| Sfax               | 3         | 1.69%   |
| Monastir           | 3         | 1.69%   |
| Centre Urbain Nord | 3         | 1.69%   |
| Ben Arous          | 3         | 1.69%   |
| Rades              | 2         | 1.13%   |
| Mateur             | 2         | 1.13%   |
| Masakin            | 2         | 1.13%   |
| Manouba            | 2         | 1.13%   |
| Mahdia             | 2         | 1.13%   |
| Jedeida            | 2         | 1.13%   |
| Houmt Souk         | 2         | 1.13%   |
| Zarzis             | 1         | 0.56%   |
| Zaouiat Djedidi    | 1         | 0.56%   |
| Wadi Maliz         | 1         | 0.56%   |
| Tebourba           | 1         | 0.56%   |
| Tataouine          | 1         | 0.56%   |
| Sidi Abbes         | 1         | 0.56%   |
| Rafraf             | 1         | 0.56%   |
| Oued Lill          | 1         | 0.56%   |
| Le Bardo           | 1         | 0.56%   |
| La Marsa           | 1         | 0.56%   |
| La Goulette        | 1         | 0.56%   |
| Jendouba           | 1         | 0.56%   |
| Hergla             | 1         | 0.56%   |
| Hammamet           | 1         | 0.56%   |
| Gremda             | 1         | 0.56%   |
| Gafsa              | 1         | 0.56%   |
| El Fahs            | 1         | 0.56%   |
| El Battan          | 1         | 0.56%   |
| Cite 18 Janvier    | 1         | 0.56%   |
| Carthage           | 1         | 0.56%   |
| Borj el Amri       | 1         | 0.56%   |
| Belvedere          | 1         | 0.56%   |
| Bellevue           | 1         | 0.56%   |
| Beja               | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 41        | 52     | 20.5%   |
| WDC                   | 33        | 43     | 16.5%   |
| Toshiba               | 25        | 27     | 12.5%   |
| Samsung Electronics   | 15        | 24     | 7.5%    |
| Team                  | 11        | 13     | 5.5%    |
| SK hynix              | 10        | 12     | 5%      |
| SanDisk               | 8         | 9      | 4%      |
| Hitachi               | 7         | 7      | 3.5%    |
| HGST                  | 7         | 8      | 3.5%    |
| Kingston              | 6         | 8      | 3%      |
| Intel                 | 6         | 6      | 3%      |
| Unknown               | 5         | 6      | 2.5%    |
| Micron Technology     | 5         | 5      | 2.5%    |
| A-DATA Technology     | 4         | 5      | 2%      |
| Fujitsu               | 3         | 3      | 1.5%    |
| PNY                   | 2         | 2      | 1%      |
| UMIS                  | 1         | 1      | 0.5%    |
| TwinMOS               | 1         | 1      | 0.5%    |
| SPCC                  | 1         | 1      | 0.5%    |
| Realtek Semiconductor | 1         | 1      | 0.5%    |
| Phison                | 1         | 1      | 0.5%    |
| Patriot               | 1         | 1      | 0.5%    |
| OCZ                   | 1         | 1      | 0.5%    |
| HS-SSD-E100           | 1         | 1      | 0.5%    |
| EMTEC                 | 1         | 3      | 0.5%    |
| China                 | 1         | 1      | 0.5%    |
| addlink               | 1         | 1      | 0.5%    |
| ADATA Technology      | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 11        | 5.34%   |
| Seagate ST500LT012-1DG142 500GB       | 7         | 3.4%    |
| Toshiba MQ04ABF100 1TB                | 4         | 1.94%   |
| Seagate ST2000LM007-1R8174 2TB        | 4         | 1.94%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 1.46%   |
| Seagate ST1000DM010-2EP102 1TB        | 3         | 1.46%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 1.46%   |
| HGST HTS545050A7E380 500GB            | 3         | 1.46%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 0.97%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 0.97%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 0.97%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 0.97%   |
| WDC WD10EADS-65M2B0 1TB               | 2         | 0.97%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 2         | 0.97%   |
| Toshiba MQ01ABD100 1TB                | 2         | 0.97%   |
| Toshiba MK5076GSX 500GB               | 2         | 0.97%   |
| Toshiba MK3275GSX 320GB               | 2         | 0.97%   |
| Toshiba DT01ACA050 500GB              | 2         | 0.97%   |
| Team T253X2512G 512GB SSD             | 2         | 0.97%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 0.97%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 0.97%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 0.97%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 0.97%   |
| SanDisk NVMe SSD Drive 512GB          | 2         | 0.97%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 0.97%   |
| Intel SSDPEKNW512GZL 512GB            | 2         | 0.97%   |
| Fujitsu MHV2100BH PL 100GB            | 2         | 0.97%   |
| WDC WD6400AAKS-65A7B0 640GB           | 1         | 0.49%   |
| WDC WD5000LPZX-60Z10T0 500GB          | 1         | 0.49%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 0.49%   |
| WDC WD5000LPLX-60ZNTT2 500GB          | 1         | 0.49%   |
| WDC WD5000BPVT-55HXZT3 500GB          | 1         | 0.49%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 0.49%   |
| WDC WD5000AAKS-402AA0 500GB           | 1         | 0.49%   |
| WDC WD5000AACS-00ZUB0 500GB           | 1         | 0.49%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 0.49%   |
| WDC WD3200AAJS-60M0A1 320GB           | 1         | 0.49%   |
| WDC WD2500BPVT-75JJ5T0 250GB          | 1         | 0.49%   |
| WDC WD2500AAJS-75M0A0 250GB           | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 51     | 36.04%  |
| WDC                 | 28        | 37     | 25.23%  |
| Toshiba             | 25        | 27     | 22.52%  |
| Hitachi             | 7         | 7      | 6.31%   |
| HGST                | 7         | 8      | 6.31%   |
| Fujitsu             | 3         | 3      | 2.7%    |
| Samsung Electronics | 1         | 1      | 0.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 7         | 9      | 17.95%  |
| SK hynix            | 6         | 7      | 15.38%  |
| Samsung Electronics | 6         | 10     | 15.38%  |
| SanDisk             | 5         | 5      | 12.82%  |
| PNY                 | 2         | 2      | 5.13%   |
| Kingston            | 2         | 2      | 5.13%   |
| A-DATA Technology   | 2         | 3      | 5.13%   |
| TwinMOS             | 1         | 1      | 2.56%   |
| SPCC                | 1         | 1      | 2.56%   |
| Patriot             | 1         | 1      | 2.56%   |
| OCZ                 | 1         | 1      | 2.56%   |
| Micron Technology   | 1         | 1      | 2.56%   |
| HS-SSD-E100         | 1         | 1      | 2.56%   |
| EMTEC               | 1         | 3      | 2.56%   |
| China               | 1         | 1      | 2.56%   |
| addlink             | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 108       | 134    | 56.25%  |
| NVMe    | 40        | 54     | 20.83%  |
| SSD     | 38        | 49     | 19.79%  |
| MMC     | 4         | 5      | 2.08%   |
| Unknown | 2         | 2      | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 130       | 183    | 73.86%  |
| NVMe | 40        | 54     | 22.73%  |
| MMC  | 4         | 5      | 2.27%   |
| SAS  | 2         | 2      | 1.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 103    | 59.44%  |
| 0.51-1.0   | 51        | 72     | 35.66%  |
| 1.01-2.0   | 7         | 8      | 4.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 53        | 31.93%  |
| 101-250    | 44        | 26.51%  |
| 501-1000   | 25        | 15.06%  |
| 1001-2000  | 14        | 8.43%   |
| 1-20       | 10        | 6.02%   |
| 51-100     | 10        | 6.02%   |
| 21-50      | 6         | 3.61%   |
| 2001-3000  | 2         | 1.2%    |
| Unknown    | 2         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 65        | 37.57%  |
| 101-250   | 33        | 19.08%  |
| 21-50     | 30        | 17.34%  |
| 51-100    | 24        | 13.87%  |
| 251-500   | 8         | 4.62%   |
| 501-1000  | 7         | 4.05%   |
| 1001-2000 | 4         | 2.31%   |
| Unknown   | 2         | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E380 500GB                          | 2         | 3      | 10.53%  |
| WDC WD6400AAKS-65A7B0 640GB                         | 1         | 1      | 5.26%   |
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 5.26%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 5.26%   |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 5.26%   |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 5.26%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 5.26%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 5.26%   |
| Seagate ST3320813AS 320GB                           | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 5.26%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 5.26%   |
| Hitachi HTS547575A9E384 752GB                       | 1         | 1      | 5.26%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 5.26%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 5.26%   |
| EMTEC X250 512GB SSD                                | 1         | 2      | 5.26%   |
| A-DATA Technology SX8100NP 512GB                    | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 7      | 26.32%  |
| Toshiba           | 4         | 5      | 21.05%  |
| Hitachi           | 3         | 3      | 15.79%  |
| WDC               | 2         | 3      | 10.53%  |
| HGST              | 2         | 3      | 10.53%  |
| Micron Technology | 1         | 1      | 5.26%   |
| EMTEC             | 1         | 2      | 5.26%   |
| A-DATA Technology | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 7      | 31.25%  |
| Toshiba | 4         | 5      | 25%     |
| Hitachi | 3         | 3      | 18.75%  |
| WDC     | 2         | 3      | 12.5%   |
| HGST    | 2         | 3      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 21     | 84.21%  |
| SSD  | 2         | 3      | 10.53%  |
| NVMe | 1         | 1      | 5.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK1646GSX 160GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 76        | 107    | 44.44%  |
| Works    | 75        | 111    | 43.86%  |
| Malfunc  | 19        | 25     | 11.11%  |
| Failed   | 1         | 1      | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 133       | 71.12%  |
| AMD                          | 17        | 9.09%   |
| Samsung Electronics          | 8         | 4.28%   |
| SanDisk                      | 7         | 3.74%   |
| SK hynix                     | 4         | 2.14%   |
| Micron Technology            | 4         | 2.14%   |
| Kingston Technology Company  | 4         | 2.14%   |
| Realtek Semiconductor        | 3         | 1.6%    |
| Phison Electronics           | 3         | 1.6%    |
| Union Memory (Shenzhen)      | 1         | 0.53%   |
| Silicon Motion               | 1         | 0.53%   |
| Shenzhen Longsys Electronics | 1         | 0.53%   |
| ADATA Technology             | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 7.28%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13        | 6.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 5.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 4.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 3.88%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 3.4%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 3.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 3.4%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 6         | 2.91%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.94%   |
| Micron Non-Volatile memory controller                                                   | 4         | 1.94%   |
| Kingston Company Company Non-Volatile memory controller                                 | 4         | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 1.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 1.94%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 3         | 1.46%   |
| Intel SSD 660P Series                                                                   | 3         | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.46%   |
| Intel Non-Volatile memory controller                                                    | 3         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.46%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.46%   |
| SK hynix BC511                                                                          | 2         | 0.97%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.97%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.97%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 0.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 0.97%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 123       | 63.4%   |
| NVMe | 40        | 20.62%  |
| RAID | 19        | 9.79%   |
| IDE  | 12        | 6.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 136       | 85.53%  |
| AMD    | 22        | 13.84%  |
| ARM    | 1         | 0.63%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.52%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 2.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 2.52%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.89%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.89%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.26%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.26%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.26%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.26%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.26%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.26%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.26%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.26%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.26%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.26%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.26%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.26%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.26%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2         | 1.26%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.26%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.26%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.26%   |
| Intel Xeon E-2144G CPU @ 3.60GHz              | 1         | 0.63%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.63%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.63%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.63%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.63%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.63%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 1         | 0.63%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.63%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 0.63%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.63%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 44        | 27.67%  |
| Intel Core i7           | 29        | 18.24%  |
| Intel Core i3           | 24        | 15.09%  |
| Other                   | 13        | 8.18%   |
| AMD Ryzen 5             | 10        | 6.29%   |
| Intel Pentium           | 9         | 5.66%   |
| Intel Celeron           | 6         | 3.77%   |
| Intel Core 2 Quad       | 4         | 2.52%   |
| Intel Core 2 Duo        | 4         | 2.52%   |
| Intel Pentium Dual-Core | 2         | 1.26%   |
| AMD Ryzen 7             | 2         | 1.26%   |
| Intel Xeon              | 1         | 0.63%   |
| Intel Core m3           | 1         | 0.63%   |
| Intel Atom              | 1         | 0.63%   |
| AMD Sempron             | 1         | 0.63%   |
| AMD Ryzen 5 PRO         | 1         | 0.63%   |
| AMD Ryzen 3             | 1         | 0.63%   |
| AMD FX                  | 1         | 0.63%   |
| AMD E2                  | 1         | 0.63%   |
| AMD E                   | 1         | 0.63%   |
| AMD A8                  | 1         | 0.63%   |
| AMD A6                  | 1         | 0.63%   |
| AMD A4                  | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 77        | 48.43%  |
| 4       | 60        | 37.74%  |
| 6       | 12        | 7.55%   |
| 8       | 5         | 3.14%   |
| 1       | 2         | 1.26%   |
| 14      | 1         | 0.63%   |
| 12      | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 159       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 124       | 77.5%   |
| 1       | 35        | 21.88%  |
| Unknown | 1         | 0.63%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 158       | 99.37%  |
| Unknown        | 1         | 0.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 20.25%  |
| 0x206a7    | 12        | 7.36%   |
| 0x806ea    | 8         | 4.91%   |
| 0x40651    | 8         | 4.91%   |
| 0x306a9    | 7         | 4.29%   |
| 0x906ea    | 6         | 3.68%   |
| 0x806ec    | 6         | 3.68%   |
| 0x806c1    | 6         | 3.68%   |
| 0x506e3    | 6         | 3.68%   |
| 0x1067a    | 6         | 3.68%   |
| 0xa0652    | 5         | 3.07%   |
| 0x406e3    | 5         | 3.07%   |
| 0x306c3    | 5         | 3.07%   |
| 0x08108109 | 4         | 2.45%   |
| 0x806e9    | 3         | 1.84%   |
| 0x706e5    | 3         | 1.84%   |
| 0x306d4    | 3         | 1.84%   |
| 0x20655    | 3         | 1.84%   |
| 0x706a8    | 2         | 1.23%   |
| 0x406c4    | 2         | 1.23%   |
| 0x30678    | 2         | 1.23%   |
| 0x08600106 | 2         | 1.23%   |
| 0x08108102 | 2         | 1.23%   |
| 0x06006705 | 2         | 1.23%   |
| 0x06006704 | 2         | 1.23%   |
| 0xa0671    | 1         | 0.61%   |
| 0xa0653    | 1         | 0.61%   |
| 0x906e9    | 1         | 0.61%   |
| 0x906a3    | 1         | 0.61%   |
| 0x90672    | 1         | 0.61%   |
| 0x6fd      | 1         | 0.61%   |
| 0x6fb      | 1         | 0.61%   |
| 0x506c9    | 1         | 0.61%   |
| 0x40661    | 1         | 0.61%   |
| 0x20652    | 1         | 0.61%   |
| 0x106ca    | 1         | 0.61%   |
| 0x10677    | 1         | 0.61%   |
| 0x0a50000c | 1         | 0.61%   |
| 0x0a404101 | 1         | 0.61%   |
| 0x08701013 | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 19.5%   |
| Haswell          | 19        | 11.95%  |
| SandyBridge      | 15        | 9.43%   |
| Skylake          | 12        | 7.55%   |
| TigerLake        | 8         | 5.03%   |
| Penryn           | 8         | 5.03%   |
| Zen+             | 7         | 4.4%    |
| IvyBridge        | 7         | 4.4%    |
| CometLake        | 7         | 4.4%    |
| Westmere         | 6         | 3.77%   |
| IceLake          | 6         | 3.77%   |
| Silvermont       | 5         | 3.14%   |
| Zen 2            | 4         | 2.52%   |
| Excavator        | 4         | 2.52%   |
| Broadwell        | 4         | 2.52%   |
| Unknown          | 3         | 1.89%   |
| Zen 3            | 2         | 1.26%   |
| Goldmont plus    | 2         | 1.26%   |
| Core             | 2         | 1.26%   |
| Puma             | 1         | 0.63%   |
| Piledriver       | 1         | 0.63%   |
| K8 & K10 hybrid  | 1         | 0.63%   |
| Goldmont         | 1         | 0.63%   |
| Bonnell          | 1         | 0.63%   |
| Bobcat           | 1         | 0.63%   |
| Alderlake Hybrid | 1         | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 118       | 52.91%  |
| Nvidia | 68        | 30.49%  |
| AMD    | 37        | 16.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 3.56%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 2.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.67%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 2.22%   |
| Intel HD Graphics 620                                                                    | 5         | 2.22%   |
| Intel HD Graphics 530                                                                    | 5         | 2.22%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 1.78%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.78%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.33%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.33%   |
| AMD Renoir                                                                               | 3         | 1.33%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.33%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.89%   |
| Nvidia TU117M                                                                            | 2         | 0.89%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.89%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.89%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 59        | 37.11%  |
| Intel + Nvidia | 44        | 27.67%  |
| 1 x Nvidia     | 18        | 11.32%  |
| 1 x AMD        | 16        | 10.06%  |
| Intel + AMD    | 13        | 8.18%   |
| AMD + Nvidia   | 6         | 3.77%   |
| 2 x AMD        | 2         | 1.26%   |
| Other          | 1         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 125       | 76.22%  |
| Proprietary | 32        | 19.51%  |
| Unknown     | 7         | 4.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 54.88%  |
| 1.01-2.0   | 28        | 17.07%  |
| 3.01-4.0   | 14        | 8.54%   |
| 0.01-0.5   | 14        | 8.54%   |
| 0.51-1.0   | 11        | 6.71%   |
| 5.01-6.0   | 4         | 2.44%   |
| 2.01-3.0   | 2         | 1.22%   |
| 7.01-8.0   | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 33        | 19.19%  |
| Chimei Innolux          | 30        | 17.44%  |
| AU Optronics            | 30        | 17.44%  |
| BOE                     | 26        | 15.12%  |
| LG Display              | 16        | 9.3%    |
| Hewlett-Packard         | 12        | 6.98%   |
| Lenovo                  | 3         | 1.74%   |
| Chi Mei Optoelectronics | 3         | 1.74%   |
| PANDA                   | 2         | 1.16%   |
| Packard Bell            | 2         | 1.16%   |
| MSI                     | 2         | 1.16%   |
| Dell                    | 2         | 1.16%   |
| BenQ                    | 2         | 1.16%   |
| S2-Tek                  | 1         | 0.58%   |
| PKB                     | 1         | 0.58%   |
| Philips                 | 1         | 0.58%   |
| Medion                  | 1         | 0.58%   |
| LG Philips              | 1         | 0.58%   |
| ITE                     | 1         | 0.58%   |
| Goldstar                | 1         | 0.58%   |
| GDH                     | 1         | 0.58%   |
| Acer                    | 1         | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 4%      |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 2.29%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 2.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 2.29%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 3         | 1.71%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 1.71%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.71%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 1.71%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 1.14%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.14%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch           | 2         | 1.14%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch            | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.14%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.14%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.14%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                 | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch        | 2         | 1.14%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch  | 1         | 0.57%   |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch     | 1         | 0.57%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1         | 0.57%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch      | 1         | 0.57%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 1         | 0.57%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 76        | 47.2%   |
| 1366x768 (WXGA)    | 56        | 34.78%  |
| 1600x900 (HD+)     | 12        | 7.45%   |
| 3840x2160 (4K)     | 4         | 2.48%   |
| 1680x1050 (WSXGA+) | 3         | 1.86%   |
| 1280x800 (WXGA)    | 3         | 1.86%   |
| 1280x1024 (SXGA)   | 3         | 1.86%   |
| 3840x1100          | 1         | 0.62%   |
| 2560x1440 (QHD)    | 1         | 0.62%   |
| 1440x900 (WXGA+)   | 1         | 0.62%   |
| 1024x600           | 1         | 0.62%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 93        | 54.07%  |
| 23      | 11        | 6.4%    |
| 17      | 10        | 5.81%   |
| 21      | 9         | 5.23%   |
| 14      | 9         | 5.23%   |
| 13      | 8         | 4.65%   |
| 24      | 7         | 4.07%   |
| 20      | 6         | 3.49%   |
| 27      | 4         | 2.33%   |
| 22      | 2         | 1.16%   |
| 19      | 2         | 1.16%   |
| 12      | 2         | 1.16%   |
| 11      | 2         | 1.16%   |
| Unknown | 2         | 1.16%   |
| 52      | 1         | 0.58%   |
| 42      | 1         | 0.58%   |
| 31      | 1         | 0.58%   |
| 18      | 1         | 0.58%   |
| 10      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 106       | 63.1%   |
| 501-600     | 21        | 12.5%   |
| 401-500     | 18        | 10.71%  |
| 351-400     | 10        | 5.95%   |
| 201-300     | 8         | 4.76%   |
| Unknown     | 2         | 1.19%   |
| 601-700     | 1         | 0.6%    |
| 1001-1500   | 1         | 0.6%    |
| 901-1000    | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 90.32%  |
| 16/10   | 8         | 5.16%   |
| 5/4     | 3         | 1.94%   |
| Unknown | 2         | 1.29%   |
| 3/2     | 1         | 0.65%   |
| 3.40    | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 54.07%  |
| 201-250        | 27        | 15.7%   |
| 81-90          | 13        | 7.56%   |
| 151-200        | 9         | 5.23%   |
| 121-130        | 6         | 3.49%   |
| 301-350        | 4         | 2.33%   |
| 71-80          | 3         | 1.74%   |
| 51-60          | 3         | 1.74%   |
| 141-150        | 3         | 1.74%   |
| 61-70          | 2         | 1.16%   |
| 131-140        | 2         | 1.16%   |
| Unknown        | 2         | 1.16%   |
| More than 1000 | 1         | 0.58%   |
| 351-500        | 1         | 0.58%   |
| 41-50          | 1         | 0.58%   |
| 251-300        | 1         | 0.58%   |
| 501-1000       | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 60        | 35.93%  |
| 121-160       | 53        | 31.74%  |
| 51-100        | 44        | 26.35%  |
| 161-240       | 4         | 2.4%    |
| More than 240 | 2         | 1.2%    |
| 1-50          | 2         | 1.2%    |
| Unknown       | 2         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 132       | 81.99%  |
| 2     | 23        | 14.29%  |
| 0     | 6         | 3.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 117       | 45.7%   |
| Intel                             | 58        | 22.66%  |
| Qualcomm Atheros                  | 34        | 13.28%  |
| Broadcom                          | 13        | 5.08%   |
| Ralink                            | 8         | 3.13%   |
| Ralink Technology                 | 6         | 2.34%   |
| Broadcom Limited                  | 5         | 1.95%   |
| MediaTek                          | 2         | 0.78%   |
| D-Link                            | 2         | 0.78%   |
| TP-Link                           | 1         | 0.39%   |
| Sierra Wireless                   | 1         | 0.39%   |
| Samsung Electronics               | 1         | 0.39%   |
| OPPO                              | 1         | 0.39%   |
| Microchip Technology              | 1         | 0.39%   |
| Marvell Technology Group          | 1         | 0.39%   |
| IMC Networks                      | 1         | 0.39%   |
| ICS Advent                        | 1         | 0.39%   |
| Huawei Technologies               | 1         | 0.39%   |
| Ericsson Business Mobile Networks | 1         | 0.39%   |
| D-Link System                     | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 27.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 9.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 3.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 3.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.35%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 2.35%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 2.35%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.01%   |
| Intel Wireless 8260                                               | 3         | 1.01%   |
| Intel Wireless 7265                                               | 3         | 1.01%   |
| Intel WiFi Link 5100                                              | 3         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.67%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2         | 0.67%   |
| Intel Wireless 7260                                               | 2         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.67%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.67%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.67%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.67%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.67%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 54        | 35.06%  |
| Realtek Semiconductor             | 31        | 20.13%  |
| Qualcomm Atheros                  | 31        | 20.13%  |
| Broadcom                          | 10        | 6.49%   |
| Ralink                            | 8         | 5.19%   |
| Ralink Technology                 | 6         | 3.9%    |
| Broadcom Limited                  | 5         | 3.25%   |
| MediaTek                          | 2         | 1.3%    |
| D-Link                            | 2         | 1.3%    |
| TP-Link                           | 1         | 0.65%   |
| Sierra Wireless                   | 1         | 0.65%   |
| IMC Networks                      | 1         | 0.65%   |
| Ericsson Business Mobile Networks | 1         | 0.65%   |
| D-Link System                     | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 7.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 6.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 5.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.52%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 4.52%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 4.52%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 4.52%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 3.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 2.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.94%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.94%   |
| Intel Wireless 8260                                            | 3         | 1.94%   |
| Intel Wireless 7265                                            | 3         | 1.94%   |
| Intel WiFi Link 5100                                           | 3         | 1.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 1.29%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.29%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2         | 1.29%   |
| Intel Wireless 7260                                            | 2         | 1.29%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.29%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.29%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.29%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.29%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.29%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.29%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.65%   |
| Sierra Wireless EM7455                                         | 1         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 112       | 78.87%  |
| Intel                    | 16        | 11.27%  |
| Qualcomm Atheros         | 5         | 3.52%   |
| Broadcom                 | 3         | 2.11%   |
| Samsung Electronics      | 1         | 0.7%    |
| OPPO                     | 1         | 0.7%    |
| Microchip Technology     | 1         | 0.7%    |
| Marvell Technology Group | 1         | 0.7%    |
| ICS Advent               | 1         | 0.7%    |
| Huawei Technologies      | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 56.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 20.28%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.4%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.4%    |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.4%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.7%    |
| OPPO CPH1923                                                      | 1         | 0.7%    |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.7%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.7%    |
| Intel Ethernet Connection I218-V                                  | 1         | 0.7%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.7%    |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.7%    |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.7%    |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.7%    |
| Huawei HUAWEI                                                     | 1         | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 50.54%  |
| Ethernet | 138       | 49.46%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 69.94%  |
| Ethernet | 49        | 30.06%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 71.88%  |
| 1     | 44        | 27.5%   |
| 0     | 1         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 159       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 38.33%  |
| Realtek Semiconductor           | 20        | 16.67%  |
| Qualcomm Atheros Communications | 20        | 16.67%  |
| Lite-On Technology              | 10        | 8.33%   |
| Broadcom                        | 6         | 5%      |
| IMC Networks                    | 5         | 4.17%   |
| Ralink                          | 4         | 3.33%   |
| Foxconn / Hon Hai               | 3         | 2.5%    |
| Cambridge Silicon Radio         | 2         | 1.67%   |
| Toshiba                         | 1         | 0.83%   |
| Realtek                         | 1         | 0.83%   |
| Hewlett-Packard                 | 1         | 0.83%   |
| Dell                            | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 17        | 14.17%  |
| Intel Bluetooth wireless interface                  | 16        | 13.33%  |
| Realtek Bluetooth Radio                             | 14        | 11.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 9.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.33%   |
| Ralink RT3290 Bluetooth                             | 4         | 3.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 3.33%   |
| Lite-On Bluetooth Device                            | 4         | 3.33%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 2.5%    |
| IMC Networks Bluetooth Radio                        | 3         | 2.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 2.5%    |
| Realtek RTL8723B Bluetooth                          | 2         | 1.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.67%   |
| IMC Networks Wireless_Device                        | 2         | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.67%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.83%   |
| Realtek Bluetooth Radio                             | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.83%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.83%   |
| Lite-On BCM43142A0                                  | 1         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.83%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 137       | 66.5%   |
| Nvidia                  | 35        | 16.99%  |
| AMD                     | 28        | 13.59%  |
| C-Media Electronics     | 2         | 0.97%   |
| Xiamen VBeT Electronics | 1         | 0.49%   |
| Lenovo                  | 1         | 0.49%   |
| JMTek                   | 1         | 0.49%   |
| DSEA A/S                | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 8.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.11%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 4.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 4.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 3.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 3.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 2.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 2.55%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 2.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.13%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.7%    |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.7%    |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.7%    |
| AMD High Definition Audio Controller                                                              | 4         | 1.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.28%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.85%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.85%   |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.85%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.85%   |
| Xiamen VBeT Electronics VT X208                                                                   | 1         | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 29.03%  |
| SK hynix            | 21        | 16.94%  |
| Micron Technology   | 14        | 11.29%  |
| Team                | 11        | 8.87%   |
| Unknown             | 8         | 6.45%   |
| A-DATA Technology   | 7         | 5.65%   |
| Crucial             | 5         | 4.03%   |
| Nanya Technology    | 3         | 2.42%   |
| Kingston            | 3         | 2.42%   |
| Elpida              | 3         | 2.42%   |
| Toshiba             | 2         | 1.61%   |
| Ramaxel Technology  | 2         | 1.61%   |
| Unknown (ABCD)      | 1         | 0.81%   |
| TwinMOS             | 1         | 0.81%   |
| PNY                 | 1         | 0.81%   |
| Patriot             | 1         | 0.81%   |
| Melco               | 1         | 0.81%   |
| Hikvision           | 1         | 0.81%   |
| GOODRAM             | 1         | 0.81%   |
| ASint Technology    | 1         | 0.81%   |
| Unknown             | 1         | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 3         | 2.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 2.29%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 3         | 2.29%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 2.29%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                    | 3         | 2.29%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s             | 2         | 1.53%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s              | 2         | 1.53%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s          | 2         | 1.53%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s           | 2         | 1.53%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 1.53%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s       | 2         | 1.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 1.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 1.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 2         | 1.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 1.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1.53%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 2         | 1.53%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s           | 2         | 1.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3                               | 1         | 0.76%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                 | 1         | 0.76%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.76%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                  | 1         | 0.76%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                         | 1         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.76%   |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s               | 1         | 0.76%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 1         | 0.76%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s             | 1         | 0.76%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                    | 1         | 0.76%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 0.76%   |
| SK hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s       | 1         | 0.76%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s          | 1         | 0.76%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 58.59%  |
| DDR3    | 26        | 26.26%  |
| DDR2    | 5         | 5.05%   |
| SDRAM   | 3         | 3.03%   |
| LPDDR4  | 3         | 3.03%   |
| LPDDR3  | 2         | 2.02%   |
| DDR5    | 1         | 1.01%   |
| Unknown | 1         | 1.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 73.74%  |
| DIMM         | 17        | 17.17%  |
| Row Of Chips | 8         | 8.08%   |
| Chip         | 1         | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 40        | 35.09%  |
| 8192  | 39        | 34.21%  |
| 16384 | 14        | 12.28%  |
| 2048  | 13        | 11.4%   |
| 32768 | 6         | 5.26%   |
| 1024  | 2         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 26        | 23.21%  |
| 3200    | 24        | 21.43%  |
| 1600    | 14        | 12.5%   |
| 2400    | 9         | 8.04%   |
| 1334    | 7         | 6.25%   |
| 1333    | 5         | 4.46%   |
| 2133    | 3         | 2.68%   |
| 1867    | 3         | 2.68%   |
| 1066    | 3         | 2.68%   |
| 667     | 3         | 2.68%   |
| 8400    | 2         | 1.79%   |
| 4199    | 2         | 1.79%   |
| 3266    | 2         | 1.79%   |
| Unknown | 2         | 1.79%   |
| 49926   | 1         | 0.89%   |
| 4800    | 1         | 0.89%   |
| 3800    | 1         | 0.89%   |
| 3000    | 1         | 0.89%   |
| 1648    | 1         | 0.89%   |
| 975     | 1         | 0.89%   |
| 800     | 1         | 0.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 66.67%  |
| Seiko Epson     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L365 Series | 1         | 33.33%  |
| HP LaserJet P1005       | 1         | 33.33%  |
| HP DeskJet 5810 series  | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26        | 22.41%  |
| Realtek Semiconductor                  | 16        | 13.79%  |
| IMC Networks                           | 15        | 12.93%  |
| Acer                                   | 9         | 7.76%   |
| Microdia                               | 8         | 6.9%    |
| Suyin                                  | 7         | 6.03%   |
| Syntek                                 | 6         | 5.17%   |
| Sunplus Innovation Technology          | 6         | 5.17%   |
| Lite-On Technology                     | 5         | 4.31%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.31%   |
| Quanta                                 | 3         | 2.59%   |
| Luxvisions Innotech Limited            | 2         | 1.72%   |
| Silicon Motion                         | 1         | 0.86%   |
| Ricoh                                  | 1         | 0.86%   |
| Lenovo                                 | 1         | 0.86%   |
| Importek                               | 1         | 0.86%   |
| DLEQNA19IFK6G2                         | 1         | 0.86%   |
| Cubeternet                             | 1         | 0.86%   |
| Apple                                  | 1         | 0.86%   |
| Alcor Micro                            | 1         | 0.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 8         | 6.84%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 7         | 5.98%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 3.42%   |
| IMC Networks Integrated Camera                              | 4         | 3.42%   |
| Chicony HD WebCam                                           | 4         | 3.42%   |
| Acer Integrated Camera                                      | 4         | 3.42%   |
| Syntek EasyCamera                                           | 3         | 2.56%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 2.56%   |
| Realtek USB Camera                                          | 3         | 2.56%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.56%   |
| Lite-On Integrated Camera                                   | 3         | 2.56%   |
| Syntek Integrated Camera                                    | 2         | 1.71%   |
| Suyin HP TrueVision HD                                      | 2         | 1.71%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.71%   |
| Realtek EasyCamera                                          | 2         | 1.71%   |
| Quanta HD WebCam                                            | 2         | 1.71%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 1.71%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 2         | 1.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.71%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.71%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.71%   |
| Chicony EasyCamera                                          | 2         | 1.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.71%   |
| Acer Lenovo EasyCamera                                      | 2         | 1.71%   |
| Acer HD Webcam                                              | 2         | 1.71%   |
| Syntek Integrated RGB Camera                                | 1         | 0.85%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.85%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.85%   |
| Suyin HD WebCam                                             | 1         | 0.85%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.85%   |
| Sunplus HD User Facing                                      | 1         | 0.85%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.85%   |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.85%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 0.85%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.85%   |
| Realtek Integrated Webcam                                   | 1         | 0.85%   |
| Realtek HP Webcam                                           | 1         | 0.85%   |
| Quanta HP Webcam                                            | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 40%     |
| Shenzhen Goodix Technology | 2         | 20%     |
| LighTuning Technology      | 2         | 20%     |
| Upek                       | 1         | 10%     |
| Synaptics                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 10%     |
| Validity Sensors Synaptics WBDI                        | 1         | 10%     |
| Validity Sensors Fingerprint scanner                   | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 10%     |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom 5880                                                                | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 123       | 71.51%  |
| 1     | 38        | 22.09%  |
| 3     | 5         | 2.91%   |
| 2     | 5         | 2.91%   |
| 4     | 1         | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 31.67%  |
| Net/wireless             | 12        | 20%     |
| Fingerprint reader       | 10        | 16.67%  |
| Bluetooth                | 6         | 10%     |
| Communication controller | 3         | 5%      |
| Chipcard                 | 3         | 5%      |
| Storage                  | 2         | 3.33%   |
| Sound                    | 1         | 1.67%   |
| Network                  | 1         | 1.67%   |
| Net/ethernet             | 1         | 1.67%   |
| Card reader              | 1         | 1.67%   |
| Camera                   | 1         | 1.67%   |

