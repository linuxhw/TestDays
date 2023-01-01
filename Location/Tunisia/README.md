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

Total: 227

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 37        | 22.56%  |
| Ubuntu 18.04       | 17        | 10.37%  |
| Ubuntu 22.04       | 12        | 7.32%   |
| Ubuntu 21.10       | 6         | 3.66%   |
| OpenMandriva 4.2   | 5         | 3.05%   |
| OpenMandriva 4.3   | 4         | 2.44%   |
| Zorin 15           | 3         | 1.83%   |
| Ubuntu 19.10       | 3         | 1.83%   |
| Ubuntu 16.04       | 3         | 1.83%   |
| Pop!_OS 22.04      | 3         | 1.83%   |
| KDE neon 20.04     | 3         | 1.83%   |
| Debian 11          | 3         | 1.83%   |
| Debian 10          | 3         | 1.83%   |
| Zorin 16           | 2         | 1.22%   |
| Ubuntu 21.04       | 2         | 1.22%   |
| Ubuntu 20.10       | 2         | 1.22%   |
| ROSA R10           | 2         | 1.22%   |
| ROSA 12.3          | 2         | 1.22%   |
| Pop!_OS 21.04      | 2         | 1.22%   |
| Manjaro 21.1.0     | 2         | 1.22%   |
| LMDE 4             | 2         | 1.22%   |
| Linux Mint 20.3    | 2         | 1.22%   |
| Linux Mint 20.2    | 2         | 1.22%   |
| Linux Mint 20      | 2         | 1.22%   |
| KDE neon 22.04     | 2         | 1.22%   |
| Gentoo 2.8         | 2         | 1.22%   |
| Gentoo 2.7         | 2         | 1.22%   |
| Fedora 35          | 2         | 1.22%   |
| Fedora 33          | 2         | 1.22%   |
| ArcoLinux Rolling  | 2         | 1.22%   |
| Arch Rolling       | 2         | 1.22%   |
| Arch               | 2         | 1.22%   |
| Xubuntu 18.04      | 1         | 0.61%   |
| Ubuntu Unity 16.04 | 1         | 0.61%   |
| Ubuntu 19.04       | 1         | 0.61%   |
| Sodalite 35        | 1         | 0.61%   |
| ROSA R8.1          | 1         | 0.61%   |
| ROSA R11           | 1         | 0.61%   |
| Pop!_OS 20.10      | 1         | 0.61%   |
| Manjaro 22.0.0     | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 78        | 50.32%  |
| OpenMandriva | 9         | 5.81%   |
| Linux Mint   | 7         | 4.52%   |
| Debian       | 7         | 4.52%   |
| ROSA         | 6         | 3.87%   |
| Pop!_OS      | 6         | 3.87%   |
| Zorin        | 5         | 3.23%   |
| Manjaro      | 5         | 3.23%   |
| Fedora       | 5         | 3.23%   |
| Arch         | 4         | 2.58%   |
| KDE neon     | 3         | 1.94%   |
| Gentoo       | 3         | 1.94%   |
| Endless      | 3         | 1.94%   |
| Lubuntu      | 2         | 1.29%   |
| LMDE         | 2         | 1.29%   |
| ArcoLinux    | 2         | 1.29%   |
| Xubuntu      | 1         | 0.65%   |
| Ubuntu Unity | 1         | 0.65%   |
| Sodalite     | 1         | 0.65%   |
| Kubuntu      | 1         | 0.65%   |
| Kali         | 1         | 0.65%   |
| Elementary   | 1         | 0.65%   |
| Deepin       | 1         | 0.65%   |
| BlackPanther | 1         | 0.65%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 5         | 2.87%   |
| 5.16.7-desktop-1omv4003         | 4         | 2.3%    |
| 5.15.0-52-generic               | 4         | 2.3%    |
| 5.15.0-46-generic               | 4         | 2.3%    |
| 5.13.0-28-generic               | 4         | 2.3%    |
| 5.3.0-46-generic                | 3         | 1.72%   |
| 5.3.0-40-generic                | 3         | 1.72%   |
| 5.15.0-53-generic               | 3         | 1.72%   |
| 5.15.0-43-generic               | 3         | 1.72%   |
| 5.11.0-38-generic               | 3         | 1.72%   |
| 5.8.0-38-generic                | 2         | 1.15%   |
| 5.4.0-72-generic                | 2         | 1.15%   |
| 5.4.0-58-generic                | 2         | 1.15%   |
| 5.4.0-52-generic                | 2         | 1.15%   |
| 5.4.0-42-generic                | 2         | 1.15%   |
| 5.4.0-26-generic                | 2         | 1.15%   |
| 5.3.0-28-generic                | 2         | 1.15%   |
| 5.13.0-44-generic               | 2         | 1.15%   |
| 5.13.0-40-generic               | 2         | 1.15%   |
| 5.11.0-7620-generic             | 2         | 1.15%   |
| 5.11.0-40-generic               | 2         | 1.15%   |
| 5.11.0-27-generic               | 2         | 1.15%   |
| 5.10.27-gentoo                  | 2         | 1.15%   |
| 5.10.0-12-amd64                 | 2         | 1.15%   |
| 5.0.0-25-generic                | 2         | 1.15%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.15%   |
| 4.19.0-6-amd64                  | 2         | 1.15%   |
| 4.15.0-91-generic               | 2         | 1.15%   |
| 5.9.9-arch1-1                   | 1         | 0.57%   |
| 5.9.1-arch1-1                   | 1         | 0.57%   |
| 5.8.15-301.fc33.x86_64          | 1         | 0.57%   |
| 5.8.0-55-generic                | 1         | 0.57%   |
| 5.8.0-50-generic                | 1         | 0.57%   |
| 5.8.0-44-generic                | 1         | 0.57%   |
| 5.8.0-40-generic                | 1         | 0.57%   |
| 5.8.0-33-generic                | 1         | 0.57%   |
| 5.8.0-32-generic                | 1         | 0.57%   |
| 5.8.0-28-generic                | 1         | 0.57%   |
| 5.8.0-14-generic                | 1         | 0.57%   |
| 5.6.14-desktop-2bP              | 1         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 26        | 15.48%  |
| 5.15.0  | 17        | 10.12%  |
| 5.13.0  | 14        | 8.33%   |
| 5.11.0  | 12        | 7.14%   |
| 5.3.0   | 11        | 6.55%   |
| 5.8.0   | 10        | 5.95%   |
| 4.15.0  | 10        | 5.95%   |
| 5.0.0   | 7         | 4.17%   |
| 5.10.14 | 5         | 2.98%   |
| 5.16.7  | 4         | 2.38%   |
| 4.19.0  | 4         | 2.38%   |
| 5.19.0  | 3         | 1.79%   |
| 4.18.0  | 3         | 1.79%   |
| 5.18.0  | 2         | 1.19%   |
| 5.17.5  | 2         | 1.19%   |
| 5.15.75 | 2         | 1.19%   |
| 5.10.27 | 2         | 1.19%   |
| 5.10.0  | 2         | 1.19%   |
| 4.9.60  | 2         | 1.19%   |
| 5.9.9   | 1         | 0.6%    |
| 5.9.1   | 1         | 0.6%    |
| 5.8.15  | 1         | 0.6%    |
| 5.6.14  | 1         | 0.6%    |
| 5.4.80  | 1         | 0.6%    |
| 5.4.143 | 1         | 0.6%    |
| 5.4.119 | 1         | 0.6%    |
| 5.3.8   | 1         | 0.6%    |
| 5.19.13 | 1         | 0.6%    |
| 5.17.15 | 1         | 0.6%    |
| 5.16.9  | 1         | 0.6%    |
| 5.16.18 | 1         | 0.6%    |
| 5.16.11 | 1         | 0.6%    |
| 5.15.77 | 1         | 0.6%    |
| 5.15.76 | 1         | 0.6%    |
| 5.15.5  | 1         | 0.6%    |
| 5.15.46 | 1         | 0.6%    |
| 5.15.16 | 1         | 0.6%    |
| 5.15.11 | 1         | 0.6%    |
| 5.14.0  | 1         | 0.6%    |
| 5.13.11 | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 16.97%  |
| 5.15    | 25        | 15.15%  |
| 5.13    | 15        | 9.09%   |
| 5.11    | 14        | 8.48%   |
| 5.3     | 12        | 7.27%   |
| 5.8     | 11        | 6.67%   |
| 5.10    | 11        | 6.67%   |
| 4.15    | 10        | 6.06%   |
| 5.0     | 7         | 4.24%   |
| 5.16    | 6         | 3.64%   |
| 5.19    | 4         | 2.42%   |
| 4.19    | 4         | 2.42%   |
| 5.17    | 3         | 1.82%   |
| 4.9     | 3         | 1.82%   |
| 4.18    | 3         | 1.82%   |
| 5.9     | 2         | 1.21%   |
| 5.18    | 2         | 1.21%   |
| 5.6     | 1         | 0.61%   |
| 5.14    | 1         | 0.61%   |
| 5.12    | 1         | 0.61%   |
| 4.4     | 1         | 0.61%   |
| 3.13    | 1         | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 149       | 97.39%  |
| i686    | 3         | 1.96%   |
| aarch64 | 1         | 0.65%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 91        | 57.23%  |
| KDE5            | 20        | 12.58%  |
| Unknown         | 17        | 10.69%  |
| X-Cinnamon      | 8         | 5.03%   |
| XFCE            | 6         | 3.77%   |
| KDE4            | 4         | 2.52%   |
| Pantheon        | 2         | 1.26%   |
| GNOME Flashback | 2         | 1.26%   |
| Unity           | 1         | 0.63%   |
| MATE            | 1         | 0.63%   |
| LXQt            | 1         | 0.63%   |
| LXDE            | 1         | 0.63%   |
| i3              | 1         | 0.63%   |
| GNOME Classic   | 1         | 0.63%   |
| DWM             | 1         | 0.63%   |
| Deepin          | 1         | 0.63%   |
| Cinnamon        | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 117       | 74.05%  |
| Wayland | 32        | 20.25%  |
| Unknown | 5         | 3.16%   |
| Tty     | 4         | 2.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 39.1%   |
| GDM     | 45        | 28.85%  |
| SDDM    | 19        | 12.18%  |
| GDM3    | 18        | 11.54%  |
| LightDM | 9         | 5.77%   |
| KDM     | 4         | 2.56%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 74        | 47.44%  |
| fr_FR   | 48        | 30.77%  |
| Unknown | 19        | 12.18%  |
| en_GB   | 5         | 3.21%   |
| C       | 2         | 1.28%   |
| ar_TN   | 2         | 1.28%   |
| pt_BR   | 1         | 0.64%   |
| en_IN   | 1         | 0.64%   |
| en_CA   | 1         | 0.64%   |
| en_AU   | 1         | 0.64%   |
| en_AG   | 1         | 0.64%   |
| de_DE   | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 88        | 56.05%  |
| BIOS | 69        | 43.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 134       | 87.01%  |
| Overlay | 10        | 6.49%   |
| Unknown | 6         | 3.9%    |
| Btrfs   | 3         | 1.95%   |
| Xfs     | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 71        | 45.81%  |
| GPT     | 61        | 39.35%  |
| MBR     | 23        | 14.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 135       | 87.1%   |
| Yes       | 20        | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 65.13%  |
| Yes       | 53        | 34.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 38        | 25%     |
| Hewlett-Packard         | 25        | 16.45%  |
| ASUSTek Computer        | 25        | 16.45%  |
| Dell                    | 20        | 13.16%  |
| MSI                     | 11        | 7.24%   |
| Acer                    | 9         | 5.92%   |
| Toshiba                 | 6         | 3.95%   |
| Pegatron                | 4         | 2.63%   |
| Samsung Electronics     | 2         | 1.32%   |
| Intel                   | 2         | 1.32%   |
| Foxconn                 | 2         | 1.32%   |
| Sony                    | 1         | 0.66%   |
| Raspberry Pi Foundation | 1         | 0.66%   |
| Packard Bell            | 1         | 0.66%   |
| Gigabyte Technology     | 1         | 0.66%   |
| eMachines               | 1         | 0.66%   |
| AZW                     | 1         | 0.66%   |
| ASRock                  | 1         | 0.66%   |
| Unknown                 | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 3         | 1.97%   |
| HP Pavilion g6                          | 3         | 1.97%   |
| Pegatron VS342AA-AB6 m9801af            | 2         | 1.32%   |
| Lenovo IdeaPad 130-15IKB 81H7           | 2         | 1.32%   |
| HP Pavilion Gaming Laptop 15-ec1xxx     | 2         | 1.32%   |
| Foxconn Pro 3400 Series MT              | 2         | 1.32%   |
| Dell Inspiron 5570                      | 2         | 1.32%   |
| ASUS X556UV                             | 2         | 1.32%   |
| ASUS X550JX                             | 2         | 1.32%   |
| Unknown                                 | 2         | 1.32%   |
| Toshiba Satellite Pro L850-B339         | 1         | 0.66%   |
| Toshiba Satellite L550                  | 1         | 0.66%   |
| Toshiba Satellite L500                  | 1         | 0.66%   |
| Toshiba Satellite C650D                 | 1         | 0.66%   |
| Toshiba Satellite C50-A489              | 1         | 0.66%   |
| Toshiba Satellite A300                  | 1         | 0.66%   |
| Sony VPCEH36EF                          | 1         | 0.66%   |
| Samsung 530U3BI/530U4BI/530U4BH         | 1         | 0.66%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.66%   |
| RPi Raspberry Pi 3 Model B Rev 1.2      | 1         | 0.66%   |
| Pegatron Pro 3010 Microtower PC         | 1         | 0.66%   |
| Pegatron FL437AA-ABF a6641af            | 1         | 0.66%   |
| Packard Bell EasyNote ML65              | 1         | 0.66%   |
| MSI PRO H510 DP21 (MS-B0A4)             | 1         | 0.66%   |
| MSI MS-7C95                             | 1         | 0.66%   |
| MSI MS-7C52                             | 1         | 0.66%   |
| MSI MS-7C09                             | 1         | 0.66%   |
| MSI MS-7A15                             | 1         | 0.66%   |
| MSI MS-7817                             | 1         | 0.66%   |
| MSI MS-7502                             | 1         | 0.66%   |
| MSI Katana GF66 12UC                    | 1         | 0.66%   |
| MSI GF65 Thin 10UE                      | 1         | 0.66%   |
| MSI GF63 Thin 10SCXR                    | 1         | 0.66%   |
| MSI GF63 Thin 10SCSR                    | 1         | 0.66%   |
| Lenovo V310-15ISK 80SY                  | 1         | 0.66%   |
| Lenovo V15-IIL 82C5                     | 1         | 0.66%   |
| Lenovo V15-IGL 82C3                     | 1         | 0.66%   |
| Lenovo ThinkStation P330 30C6S33L00     | 1         | 0.66%   |
| Lenovo ThinkPad X240 20AMA0WRFR         | 1         | 0.66%   |
| Lenovo ThinkPad X201 3680FAG            | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 20        | 13.16%  |
| HP Pavilion           | 9         | 5.92%   |
| Dell Inspiron         | 9         | 5.92%   |
| Lenovo ThinkPad       | 8         | 5.26%   |
| Toshiba Satellite     | 6         | 3.95%   |
| Dell Latitude         | 6         | 3.95%   |
| Acer Aspire           | 6         | 3.95%   |
| HP Laptop             | 4         | 2.63%   |
| Dell OptiPlex         | 4         | 2.63%   |
| ASUS TUF              | 4         | 2.63%   |
| Pegatron VS342AA-AB6  | 2         | 1.32%   |
| MSI GF63              | 2         | 1.32%   |
| HP ProBook            | 2         | 1.32%   |
| HP Compaq             | 2         | 1.32%   |
| HP 250                | 2         | 1.32%   |
| Foxconn Pro           | 2         | 1.32%   |
| ASUS X556UV           | 2         | 1.32%   |
| ASUS X550JX           | 2         | 1.32%   |
| ASUS VivoBook         | 2         | 1.32%   |
| ASUS ROG              | 2         | 1.32%   |
| ASUS PRIME            | 2         | 1.32%   |
| ASUS ASUS             | 2         | 1.32%   |
| Acer Swift            | 2         | 1.32%   |
| Unknown               | 2         | 1.32%   |
| Sony VPCEH36EF        | 1         | 0.66%   |
| Samsung 530U3BI       | 1         | 0.66%   |
| Samsung 300E5EV       | 1         | 0.66%   |
| RPi Raspberry         | 1         | 0.66%   |
| Pegatron Pro          | 1         | 0.66%   |
| Pegatron FL437AA-ABF  | 1         | 0.66%   |
| Packard Bell EasyNote | 1         | 0.66%   |
| MSI PRO               | 1         | 0.66%   |
| MSI MS-7C95           | 1         | 0.66%   |
| MSI MS-7C52           | 1         | 0.66%   |
| MSI MS-7C09           | 1         | 0.66%   |
| MSI MS-7A15           | 1         | 0.66%   |
| MSI MS-7817           | 1         | 0.66%   |
| MSI MS-7502           | 1         | 0.66%   |
| MSI Katana            | 1         | 0.66%   |
| MSI GF65              | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 20        | 13.16%  |
| 2020    | 18        | 11.84%  |
| 2018    | 13        | 8.55%   |
| 2017    | 13        | 8.55%   |
| 2011    | 13        | 8.55%   |
| 2013    | 12        | 7.89%   |
| 2021    | 10        | 6.58%   |
| 2016    | 10        | 6.58%   |
| 2015    | 9         | 5.92%   |
| 2014    | 7         | 4.61%   |
| 2012    | 7         | 4.61%   |
| 2009    | 6         | 3.95%   |
| 2008    | 6         | 3.95%   |
| 2010    | 5         | 3.29%   |
| 2022    | 1         | 0.66%   |
| 2007    | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 118       | 77.63%  |
| Desktop        | 31        | 20.39%  |
| Convertible    | 2         | 1.32%   |
| System on chip | 1         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 142       | 92.81%  |
| Enabled  | 11        | 7.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 54        | 35.06%  |
| 16.01-24.0 | 29        | 18.83%  |
| 8.01-16.0  | 29        | 18.83%  |
| 3.01-4.0   | 28        | 18.18%  |
| 1.01-2.0   | 6         | 3.9%    |
| 32.01-64.0 | 5         | 3.25%   |
| 2.01-3.0   | 2         | 1.3%    |
| 0.51-1.0   | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 51        | 30.18%  |
| 1.01-2.0  | 47        | 27.81%  |
| 4.01-8.0  | 31        | 18.34%  |
| 3.01-4.0  | 26        | 15.38%  |
| 0.51-1.0  | 6         | 3.55%   |
| 0.01-0.5  | 4         | 2.37%   |
| 8.01-16.0 | 3         | 1.78%   |
| Unknown   | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 112       | 72.26%  |
| 2      | 39        | 25.16%  |
| 4      | 2         | 1.29%   |
| 3      | 1         | 0.65%   |
| 0      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 53.59%  |
| Yes       | 71        | 46.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 87.5%   |
| No        | 19        | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 88.24%  |
| No        | 18        | 11.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 73.08%  |
| No        | 42        | 26.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Tunisia | 152       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Tunis              | 88        | 52.07%  |
| Aryanah            | 10        | 5.92%   |
| Sousse             | 7         | 4.14%   |
| Bizerte            | 7         | 4.14%   |
| Nabeul             | 6         | 3.55%   |
| Sfax               | 3         | 1.78%   |
| Monastir           | 3         | 1.78%   |
| Centre Urbain Nord | 3         | 1.78%   |
| Ben Arous          | 3         | 1.78%   |
| Rades              | 2         | 1.18%   |
| Mateur             | 2         | 1.18%   |
| Masakin            | 2         | 1.18%   |
| Manouba            | 2         | 1.18%   |
| Mahdia             | 2         | 1.18%   |
| Jedeida            | 2         | 1.18%   |
| Zarzis             | 1         | 0.59%   |
| Zaouiat Djedidi    | 1         | 0.59%   |
| Wadi Maliz         | 1         | 0.59%   |
| Tebourba           | 1         | 0.59%   |
| Tataouine          | 1         | 0.59%   |
| Sidi Abbes         | 1         | 0.59%   |
| Rafraf             | 1         | 0.59%   |
| Oued Lill          | 1         | 0.59%   |
| Le Bardo           | 1         | 0.59%   |
| La Marsa           | 1         | 0.59%   |
| La Goulette        | 1         | 0.59%   |
| Jendouba           | 1         | 0.59%   |
| Houmt Souk         | 1         | 0.59%   |
| Hergla             | 1         | 0.59%   |
| Hammamet           | 1         | 0.59%   |
| Gremda             | 1         | 0.59%   |
| Gafsa              | 1         | 0.59%   |
| El Fahs            | 1         | 0.59%   |
| El Battan          | 1         | 0.59%   |
| Cite 18 Janvier    | 1         | 0.59%   |
| Carthage           | 1         | 0.59%   |
| Borj el Amri       | 1         | 0.59%   |
| Belvedere          | 1         | 0.59%   |
| Bellevue           | 1         | 0.59%   |
| Beja               | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 39        | 49     | 20.63%  |
| WDC                   | 33        | 43     | 17.46%  |
| Toshiba               | 23        | 25     | 12.17%  |
| Samsung Electronics   | 15        | 22     | 7.94%   |
| Team                  | 11        | 13     | 5.82%   |
| SK hynix              | 10        | 11     | 5.29%   |
| SanDisk               | 8         | 9      | 4.23%   |
| Hitachi               | 6         | 6      | 3.17%   |
| HGST                  | 6         | 7      | 3.17%   |
| Micron Technology     | 5         | 5      | 2.65%   |
| Kingston              | 5         | 7      | 2.65%   |
| Unknown               | 4         | 4      | 2.12%   |
| Intel                 | 4         | 4      | 2.12%   |
| A-DATA Technology     | 4         | 5      | 2.12%   |
| Fujitsu               | 3         | 3      | 1.59%   |
| PNY                   | 2         | 2      | 1.06%   |
| UMIS                  | 1         | 1      | 0.53%   |
| TwinMOS               | 1         | 1      | 0.53%   |
| SPCC                  | 1         | 1      | 0.53%   |
| Realtek Semiconductor | 1         | 1      | 0.53%   |
| Phison                | 1         | 1      | 0.53%   |
| Patriot               | 1         | 1      | 0.53%   |
| OCZ                   | 1         | 1      | 0.53%   |
| HS-SSD-E100           | 1         | 1      | 0.53%   |
| EMTEC                 | 1         | 3      | 0.53%   |
| China                 | 1         | 1      | 0.53%   |
| addlink               | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 11        | 5.64%   |
| Seagate ST500LT012-1DG142 500GB       | 7         | 3.59%   |
| Toshiba MQ04ABF100 1TB                | 4         | 2.05%   |
| Seagate ST2000LM007-1R8174 2TB        | 4         | 2.05%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 1.54%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 1.54%   |
| HGST HTS545050A7E380 500GB            | 3         | 1.54%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 1.03%   |
| WDC WD20SPZX-08UA7 2TB                | 2         | 1.03%   |
| WDC WD10SPZX-08Z10 1TB                | 2         | 1.03%   |
| WDC WD10SPCX-24HWST1 1TB              | 2         | 1.03%   |
| WDC WD10EADS-65M2B0 1TB               | 2         | 1.03%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 2         | 1.03%   |
| Toshiba MQ01ABD100 1TB                | 2         | 1.03%   |
| Toshiba MK5076GSX 500GB               | 2         | 1.03%   |
| Toshiba MK3275GSX 320GB               | 2         | 1.03%   |
| Toshiba DT01ACA050 500GB              | 2         | 1.03%   |
| Team T253X2512G 512GB SSD             | 2         | 1.03%   |
| SK hynix SC311 SATA 256GB SSD         | 2         | 1.03%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 1.03%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 1.03%   |
| Seagate ST1000DM010-2EP102 1TB        | 2         | 1.03%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 1.03%   |
| SanDisk NVMe SSD Drive 512GB          | 2         | 1.03%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 1.03%   |
| Fujitsu MHV2100BH PL 100GB            | 2         | 1.03%   |
| WDC WD6400AAKS-65A7B0 640GB           | 1         | 0.51%   |
| WDC WD5000LPZX-60Z10T0 500GB          | 1         | 0.51%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 0.51%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 0.51%   |
| WDC WD5000LPLX-60ZNTT2 500GB          | 1         | 0.51%   |
| WDC WD5000BPVT-55HXZT3 500GB          | 1         | 0.51%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 0.51%   |
| WDC WD5000AAKS-402AA0 500GB           | 1         | 0.51%   |
| WDC WD5000AACS-00ZUB0 500GB           | 1         | 0.51%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 0.51%   |
| WDC WD3200AAJS-60M0A1 320GB           | 1         | 0.51%   |
| WDC WD2500BPVT-75JJ5T0 250GB          | 1         | 0.51%   |
| WDC WD2500AAJS-75M0A0 249GB           | 1         | 0.51%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 49     | 36.79%  |
| WDC                 | 28        | 37     | 26.42%  |
| Toshiba             | 23        | 25     | 21.7%   |
| Hitachi             | 6         | 6      | 5.66%   |
| HGST                | 6         | 7      | 5.66%   |
| Fujitsu             | 3         | 3      | 2.83%   |
| Samsung Electronics | 1         | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 7         | 9      | 18.42%  |
| SK hynix            | 6         | 6      | 15.79%  |
| Samsung Electronics | 6         | 10     | 15.79%  |
| SanDisk             | 5         | 5      | 13.16%  |
| PNY                 | 2         | 2      | 5.26%   |
| A-DATA Technology   | 2         | 3      | 5.26%   |
| TwinMOS             | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| Patriot             | 1         | 1      | 2.63%   |
| OCZ                 | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| Kingston            | 1         | 1      | 2.63%   |
| HS-SSD-E100         | 1         | 1      | 2.63%   |
| EMTEC               | 1         | 3      | 2.63%   |
| China               | 1         | 1      | 2.63%   |
| addlink             | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 103       | 128    | 56.91%  |
| NVMe    | 37        | 49     | 20.44%  |
| SSD     | 37        | 47     | 20.44%  |
| MMC     | 3         | 3      | 1.66%   |
| Unknown | 1         | 1      | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 125       | 175    | 75.3%   |
| NVMe | 37        | 49     | 22.29%  |
| MMC  | 3         | 3      | 1.81%   |
| SAS  | 1         | 1      | 0.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 98     | 59.12%  |
| 0.51-1.0   | 49        | 69     | 35.77%  |
| 1.01-2.0   | 7         | 8      | 5.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 50        | 31.65%  |
| 101-250    | 43        | 27.22%  |
| 501-1000   | 25        | 15.82%  |
| 1001-2000  | 13        | 8.23%   |
| 1-20       | 9         | 5.7%    |
| 51-100     | 9         | 5.7%    |
| 21-50      | 5         | 3.16%   |
| 2001-3000  | 2         | 1.27%   |
| Unknown    | 2         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 63        | 37.95%  |
| 101-250   | 31        | 18.67%  |
| 21-50     | 27        | 16.27%  |
| 51-100    | 24        | 14.46%  |
| 251-500   | 8         | 4.82%   |
| 501-1000  | 7         | 4.22%   |
| 1001-2000 | 4         | 2.41%   |
| Unknown   | 2         | 1.2%    |

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
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 5.26%   |
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
| Seagate           | 5         | 6      | 26.32%  |
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
| Seagate | 5         | 6      | 31.25%  |
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
| HDD  | 16        | 20     | 84.21%  |
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
| Works    | 73        | 106    | 44.79%  |
| Detected | 70        | 97     | 42.94%  |
| Malfunc  | 19        | 24     | 11.66%  |
| Failed   | 1         | 1      | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 127       | 70.95%  |
| AMD                          | 16        | 8.94%   |
| Samsung Electronics          | 8         | 4.47%   |
| SanDisk                      | 7         | 3.91%   |
| SK hynix                     | 4         | 2.23%   |
| Micron Technology            | 4         | 2.23%   |
| Kingston Technology Company  | 4         | 2.23%   |
| Realtek Semiconductor        | 3         | 1.68%   |
| Phison Electronics           | 3         | 1.68%   |
| Union Memory (Shenzhen)      | 1         | 0.56%   |
| Silicon Motion               | 1         | 0.56%   |
| Shenzhen Longsys Electronics | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 7.73%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 6.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 5.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 4.64%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 3.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 3.61%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 3.09%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 2.58%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 5         | 2.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 2.06%   |
| Micron Non-Volatile memory controller                                                   | 4         | 2.06%   |
| Kingston Company Company Non-Volatile memory controller                                 | 4         | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 2.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 2.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 2.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 2.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4         | 2.06%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 3         | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.55%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.55%   |
| SK hynix BC511                                                                          | 2         | 1.03%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 1.03%   |
| Phison E12 NVMe Controller                                                              | 2         | 1.03%   |
| Intel SSD 660P Series                                                                   | 2         | 1.03%   |
| Intel Non-Volatile memory controller                                                    | 2         | 1.03%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.03%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.52%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 117       | 63.93%  |
| NVMe | 37        | 20.22%  |
| RAID | 17        | 9.29%   |
| IDE  | 12        | 6.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 130       | 85.53%  |
| AMD    | 21        | 13.82%  |
| ARM    | 1         | 0.66%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 3.29%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 2.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.97%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.97%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.97%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.97%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.97%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.32%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.32%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.32%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.32%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.32%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.32%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.32%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.32%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.32%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2         | 1.32%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 1.32%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.32%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.32%   |
| Intel Xeon E-2144G CPU @ 3.60GHz              | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.66%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.66%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.66%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.66%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 1         | 0.66%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.66%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 0.66%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.66%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 28.29%  |
| Intel Core i7           | 28        | 18.42%  |
| Intel Core i3           | 23        | 15.13%  |
| Other                   | 11        | 7.24%   |
| Intel Pentium           | 9         | 5.92%   |
| AMD Ryzen 5             | 9         | 5.92%   |
| Intel Celeron           | 5         | 3.29%   |
| Intel Core 2 Quad       | 4         | 2.63%   |
| Intel Core 2 Duo        | 4         | 2.63%   |
| Intel Pentium Dual-Core | 2         | 1.32%   |
| AMD Ryzen 7             | 2         | 1.32%   |
| Intel Xeon              | 1         | 0.66%   |
| Intel Core m3           | 1         | 0.66%   |
| Intel Atom              | 1         | 0.66%   |
| AMD Sempron             | 1         | 0.66%   |
| AMD Ryzen 5 PRO         | 1         | 0.66%   |
| AMD Ryzen 3             | 1         | 0.66%   |
| AMD FX                  | 1         | 0.66%   |
| AMD E2                  | 1         | 0.66%   |
| AMD E                   | 1         | 0.66%   |
| AMD A8                  | 1         | 0.66%   |
| AMD A6                  | 1         | 0.66%   |
| AMD A4                  | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 74        | 48.68%  |
| 4       | 57        | 37.5%   |
| 6       | 11        | 7.24%   |
| 8       | 5         | 3.29%   |
| 1       | 2         | 1.32%   |
| 14      | 1         | 0.66%   |
| 12      | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 152       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 118       | 77.12%  |
| 1       | 34        | 22.22%  |
| Unknown | 1         | 0.65%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 151       | 99.34%  |
| Unknown        | 1         | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 19.23%  |
| 0x206a7    | 12        | 7.69%   |
| 0x806ea    | 8         | 5.13%   |
| 0x40651    | 8         | 5.13%   |
| 0x306a9    | 7         | 4.49%   |
| 0x906ea    | 6         | 3.85%   |
| 0x806ec    | 6         | 3.85%   |
| 0x1067a    | 6         | 3.85%   |
| 0xa0652    | 5         | 3.21%   |
| 0x806c1    | 5         | 3.21%   |
| 0x506e3    | 5         | 3.21%   |
| 0x406e3    | 5         | 3.21%   |
| 0x306c3    | 5         | 3.21%   |
| 0x08108109 | 4         | 2.56%   |
| 0x806e9    | 3         | 1.92%   |
| 0x706e5    | 3         | 1.92%   |
| 0x306d4    | 3         | 1.92%   |
| 0x20655    | 3         | 1.92%   |
| 0x706a8    | 2         | 1.28%   |
| 0x406c4    | 2         | 1.28%   |
| 0x08600106 | 2         | 1.28%   |
| 0x08108102 | 2         | 1.28%   |
| 0x06006705 | 2         | 1.28%   |
| 0x06006704 | 2         | 1.28%   |
| 0xa0671    | 1         | 0.64%   |
| 0xa0653    | 1         | 0.64%   |
| 0x906e9    | 1         | 0.64%   |
| 0x906a3    | 1         | 0.64%   |
| 0x90672    | 1         | 0.64%   |
| 0x6fd      | 1         | 0.64%   |
| 0x6fb      | 1         | 0.64%   |
| 0x506c9    | 1         | 0.64%   |
| 0x40661    | 1         | 0.64%   |
| 0x30678    | 1         | 0.64%   |
| 0x20652    | 1         | 0.64%   |
| 0x106ca    | 1         | 0.64%   |
| 0x10677    | 1         | 0.64%   |
| 0x0a50000c | 1         | 0.64%   |
| 0x0a404101 | 1         | 0.64%   |
| 0x08701013 | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 20.39%  |
| Haswell          | 18        | 11.84%  |
| SandyBridge      | 14        | 9.21%   |
| Skylake          | 11        | 7.24%   |
| Penryn           | 8         | 5.26%   |
| IvyBridge        | 7         | 4.61%   |
| CometLake        | 7         | 4.61%   |
| Zen+             | 6         | 3.95%   |
| Westmere         | 6         | 3.95%   |
| TigerLake        | 6         | 3.95%   |
| IceLake          | 6         | 3.95%   |
| Zen 2            | 4         | 2.63%   |
| Silvermont       | 4         | 2.63%   |
| Excavator        | 4         | 2.63%   |
| Broadwell        | 4         | 2.63%   |
| Unknown          | 3         | 1.97%   |
| Zen 3            | 2         | 1.32%   |
| Goldmont plus    | 2         | 1.32%   |
| Core             | 2         | 1.32%   |
| Puma             | 1         | 0.66%   |
| Piledriver       | 1         | 0.66%   |
| K8 & K10 hybrid  | 1         | 0.66%   |
| Goldmont         | 1         | 0.66%   |
| Bonnell          | 1         | 0.66%   |
| Bobcat           | 1         | 0.66%   |
| Alderlake Hybrid | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 112       | 52.83%  |
| Nvidia | 63        | 29.72%  |
| AMD    | 37        | 17.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 4.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.67%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 2.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 2.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.8%    |
| Intel HD Graphics 620                                                                    | 5         | 2.34%   |
| Nvidia GP108M [GeForce MX330]                                                            | 4         | 1.87%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.87%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.87%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.87%   |
| Intel HD Graphics 530                                                                    | 4         | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.4%    |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 1.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.4%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.4%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.4%    |
| AMD Renoir                                                                               | 3         | 1.4%    |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 1.4%    |
| Nvidia TU117M                                                                            | 2         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.93%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.93%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.47%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 37.5%   |
| Intel + Nvidia | 40        | 26.32%  |
| 1 x Nvidia     | 17        | 11.18%  |
| 1 x AMD        | 16        | 10.53%  |
| Intel + AMD    | 13        | 8.55%   |
| AMD + Nvidia   | 6         | 3.95%   |
| 2 x AMD        | 2         | 1.32%   |
| Other          | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 120       | 76.43%  |
| Proprietary | 30        | 19.11%  |
| Unknown     | 7         | 4.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 85        | 54.14%  |
| 1.01-2.0   | 28        | 17.83%  |
| 0.01-0.5   | 14        | 8.92%   |
| 3.01-4.0   | 13        | 8.28%   |
| 0.51-1.0   | 11        | 7.01%   |
| 5.01-6.0   | 3         | 1.91%   |
| 2.01-3.0   | 2         | 1.27%   |
| 7.01-8.0   | 1         | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 31        | 18.79%  |
| Chimei Innolux          | 29        | 17.58%  |
| AU Optronics            | 29        | 17.58%  |
| BOE                     | 25        | 15.15%  |
| LG Display              | 14        | 8.48%   |
| Hewlett-Packard         | 12        | 7.27%   |
| Lenovo                  | 3         | 1.82%   |
| Chi Mei Optoelectronics | 3         | 1.82%   |
| PANDA                   | 2         | 1.21%   |
| Packard Bell            | 2         | 1.21%   |
| MSI                     | 2         | 1.21%   |
| Dell                    | 2         | 1.21%   |
| BenQ                    | 2         | 1.21%   |
| S2-Tek                  | 1         | 0.61%   |
| PKB                     | 1         | 0.61%   |
| Philips                 | 1         | 0.61%   |
| Medion                  | 1         | 0.61%   |
| LG Philips              | 1         | 0.61%   |
| ITE                     | 1         | 0.61%   |
| Goldstar                | 1         | 0.61%   |
| GDH                     | 1         | 0.61%   |
| Acer                    | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 3.57%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 2.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 2.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 3         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 1.79%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.79%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 1.19%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch  | 2         | 1.19%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.19%   |
| Hewlett-Packard x20LED HWP2910 1600x900 443x249mm 20.0-inch           | 2         | 1.19%   |
| Hewlett-Packard P224 HPN361E 1920x1080 527x296mm 23.8-inch            | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.19%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.19%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO272D 1920x1080 293x165mm 13.2-inch        | 2         | 1.19%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0284 1280x1024 338x270mm 17.0-inch  | 1         | 0.6%    |
| Samsung Electronics SMB2240 SAM06AD 1920x1080 477x268mm 21.5-inch     | 1         | 0.6%    |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1         | 0.6%    |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch      | 1         | 0.6%    |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch  | 1         | 0.6%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 1         | 0.6%    |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                       | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 46.1%   |
| 1366x768 (WXGA)    | 55        | 35.71%  |
| 1600x900 (HD+)     | 11        | 7.14%   |
| 3840x2160 (4K)     | 4         | 2.6%    |
| 1680x1050 (WSXGA+) | 3         | 1.95%   |
| 1280x800 (WXGA)    | 3         | 1.95%   |
| 1280x1024 (SXGA)   | 3         | 1.95%   |
| 3840x1100          | 1         | 0.65%   |
| 2560x1440 (QHD)    | 1         | 0.65%   |
| 1440x900 (WXGA+)   | 1         | 0.65%   |
| 1024x600           | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 89        | 53.94%  |
| 23      | 10        | 6.06%   |
| 21      | 9         | 5.45%   |
| 17      | 9         | 5.45%   |
| 14      | 8         | 4.85%   |
| 13      | 8         | 4.85%   |
| 24      | 7         | 4.24%   |
| 20      | 6         | 3.64%   |
| 27      | 4         | 2.42%   |
| 22      | 2         | 1.21%   |
| 19      | 2         | 1.21%   |
| 12      | 2         | 1.21%   |
| 11      | 2         | 1.21%   |
| Unknown | 2         | 1.21%   |
| 52      | 1         | 0.61%   |
| 42      | 1         | 0.61%   |
| 31      | 1         | 0.61%   |
| 18      | 1         | 0.61%   |
| 10      | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 62.73%  |
| 501-600     | 20        | 12.42%  |
| 401-500     | 18        | 11.18%  |
| 351-400     | 9         | 5.59%   |
| 201-300     | 8         | 4.97%   |
| Unknown     | 2         | 1.24%   |
| 601-700     | 1         | 0.62%   |
| 1001-1500   | 1         | 0.62%   |
| 901-1000    | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 133       | 89.86%  |
| 16/10   | 8         | 5.41%   |
| 5/4     | 3         | 2.03%   |
| Unknown | 2         | 1.35%   |
| 3/2     | 1         | 0.68%   |
| 3.40    | 1         | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 89        | 53.94%  |
| 201-250        | 26        | 15.76%  |
| 81-90          | 12        | 7.27%   |
| 151-200        | 9         | 5.45%   |
| 121-130        | 5         | 3.03%   |
| 301-350        | 4         | 2.42%   |
| 71-80          | 3         | 1.82%   |
| 51-60          | 3         | 1.82%   |
| 141-150        | 3         | 1.82%   |
| 61-70          | 2         | 1.21%   |
| 131-140        | 2         | 1.21%   |
| Unknown        | 2         | 1.21%   |
| More than 1000 | 1         | 0.61%   |
| 351-500        | 1         | 0.61%   |
| 41-50          | 1         | 0.61%   |
| 251-300        | 1         | 0.61%   |
| 501-1000       | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 57        | 35.63%  |
| 121-160       | 50        | 31.25%  |
| 51-100        | 43        | 26.88%  |
| 161-240       | 4         | 2.5%    |
| More than 240 | 2         | 1.25%   |
| 1-50          | 2         | 1.25%   |
| Unknown       | 2         | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 125       | 81.17%  |
| 2     | 23        | 14.94%  |
| 0     | 6         | 3.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 113       | 45.93%  |
| Intel                             | 55        | 22.36%  |
| Qualcomm Atheros                  | 31        | 12.6%   |
| Broadcom                          | 13        | 5.28%   |
| Ralink                            | 8         | 3.25%   |
| Ralink Technology                 | 6         | 2.44%   |
| Broadcom Limited                  | 5         | 2.03%   |
| MediaTek                          | 2         | 0.81%   |
| D-Link                            | 2         | 0.81%   |
| TP-Link                           | 1         | 0.41%   |
| Sierra Wireless                   | 1         | 0.41%   |
| Samsung Electronics               | 1         | 0.41%   |
| OPPO Electronics                  | 1         | 0.41%   |
| Microchip Technology              | 1         | 0.41%   |
| Marvell Technology Group          | 1         | 0.41%   |
| IMC Networks                      | 1         | 0.41%   |
| ICS Advent                        | 1         | 0.41%   |
| Huawei Technologies               | 1         | 0.41%   |
| Ericsson Business Mobile Networks | 1         | 0.41%   |
| D-Link System                     | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 27.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 9.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 3.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 3.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.09%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.74%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.05%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.05%   |
| Intel Wireless 8260                                               | 3         | 1.05%   |
| Intel Wireless 7265                                               | 3         | 1.05%   |
| Intel WiFi Link 5100                                              | 3         | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.7%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.7%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.7%    |
| Intel Wireless 7260                                               | 2         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.7%    |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.7%    |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 0.7%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.7%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 2         | 0.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 34.69%  |
| Realtek Semiconductor | 31        | 21.09%  |
| Qualcomm Atheros      | 28        | 19.05%  |
| Broadcom              | 10        | 6.8%    |
| Ralink                | 8         | 5.44%   |
| Ralink Technology     | 6         | 4.08%   |
| Broadcom Limited      | 5         | 3.4%    |
| MediaTek              | 2         | 1.36%   |
| D-Link                | 2         | 1.36%   |
| TP-Link               | 1         | 0.68%   |
| Sierra Wireless       | 1         | 0.68%   |
| IMC Networks          | 1         | 0.68%   |
| D-Link System         | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 7.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 6.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.73%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 4.73%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 4.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 4.05%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 3.38%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 3.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 2.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.03%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.03%   |
| Intel Wireless 8260                                            | 3         | 2.03%   |
| Intel Wireless 7265                                            | 3         | 2.03%   |
| Intel WiFi Link 5100                                           | 3         | 2.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.35%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 1.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.35%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.35%   |
| Intel Wireless 7260                                            | 2         | 1.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.35%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.35%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.35%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 2         | 1.35%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.35%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.68%   |
| Sierra Wireless EM7455                                         | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 108       | 78.83%  |
| Intel                    | 16        | 11.68%  |
| Qualcomm Atheros         | 4         | 2.92%   |
| Broadcom                 | 3         | 2.19%   |
| Samsung Electronics      | 1         | 0.73%   |
| OPPO Electronics         | 1         | 0.73%   |
| Microchip Technology     | 1         | 0.73%   |
| Marvell Technology Group | 1         | 0.73%   |
| ICS Advent               | 1         | 0.73%   |
| Huawei Technologies      | 1         | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 57.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 19.57%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.45%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.45%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.72%   |
| OPPO RMX3263                                                      | 1         | 0.72%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.72%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.72%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.72%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.72%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.72%   |
| Huawei HUAWEI                                                     | 1         | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 50.19%  |
| Ethernet | 133       | 49.44%  |
| Modem    | 1         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 108       | 69.23%  |
| Ethernet | 48        | 30.77%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 111       | 72.55%  |
| 1     | 41        | 26.8%   |
| 0     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 37.72%  |
| Realtek Semiconductor           | 20        | 17.54%  |
| Qualcomm Atheros Communications | 19        | 16.67%  |
| Lite-On Technology              | 8         | 7.02%   |
| Broadcom                        | 6         | 5.26%   |
| IMC Networks                    | 5         | 4.39%   |
| Ralink                          | 4         | 3.51%   |
| Foxconn / Hon Hai               | 3         | 2.63%   |
| Cambridge Silicon Radio         | 2         | 1.75%   |
| Toshiba                         | 1         | 0.88%   |
| Realtek                         | 1         | 0.88%   |
| Hewlett-Packard                 | 1         | 0.88%   |
| Dell                            | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 16        | 14.04%  |
| Intel Bluetooth wireless interface                  | 15        | 13.16%  |
| Realtek Bluetooth Radio                             | 14        | 12.28%  |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 9.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 7.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.51%   |
| Ralink RT3290 Bluetooth                             | 4         | 3.51%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 3.51%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 2.63%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 2.63%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.75%   |
| Lite-On Bluetooth Device                            | 2         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.75%   |
| IMC Networks Wireless_Device                        | 2         | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.75%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.88%   |
| Realtek Bluetooth Radio                             | 1         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.88%   |
| Lite-On BCM43142A0                                  | 1         | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.88%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.88%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.88%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 130       | 65.99%  |
| Nvidia                  | 34        | 17.26%  |
| AMD                     | 27        | 13.71%  |
| C-Media Electronics     | 2         | 1.02%   |
| Xiamen VBeT Electronics | 1         | 0.51%   |
| Lenovo                  | 1         | 0.51%   |
| JMTek                   | 1         | 0.51%   |
| DSEA A/S                | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 8.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 4.89%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 4.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 3.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 3.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 3.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 2.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 2.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.22%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.78%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.78%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.78%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.33%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.89%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.89%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.89%   |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.89%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.89%   |
| Xiamen VBeT Electronics VT X208                                                                   | 1         | 0.44%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.44%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 28.69%  |
| SK hynix            | 21        | 17.21%  |
| Micron Technology   | 14        | 11.48%  |
| Team                | 11        | 9.02%   |
| Unknown             | 7         | 5.74%   |
| A-DATA Technology   | 7         | 5.74%   |
| Crucial             | 5         | 4.1%    |
| Nanya Technology    | 3         | 2.46%   |
| Kingston            | 3         | 2.46%   |
| Elpida              | 3         | 2.46%   |
| Toshiba             | 2         | 1.64%   |
| Ramaxel Technology  | 2         | 1.64%   |
| Unknown (ABCD)      | 1         | 0.82%   |
| TwinMOS             | 1         | 0.82%   |
| PNY                 | 1         | 0.82%   |
| Patriot             | 1         | 0.82%   |
| Melco               | 1         | 0.82%   |
| Hikvision           | 1         | 0.82%   |
| GOODRAM             | 1         | 0.82%   |
| ASint Technology    | 1         | 0.82%   |
| Unknown             | 1         | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 2.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 2.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 2.33%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                  | 3         | 2.33%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s           | 2         | 1.55%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s       | 2         | 1.55%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 2         | 1.55%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s         | 2         | 1.55%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s        | 2         | 1.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 1.55%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s     | 2         | 1.55%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 2         | 1.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 1.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 1.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.55%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s         | 2         | 1.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1         | 0.78%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                    | 1         | 0.78%   |
| Unknown RAM Module 4GB DIMM DDR3                             | 1         | 0.78%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s               | 1         | 0.78%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                | 1         | 0.78%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                       | 1         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1         | 0.78%   |
| TwinMOS RAM 9DSDBNZB-5AMP 4GB DIMM DDR3 1333MT/s             | 1         | 0.78%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s          | 1         | 0.78%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s           | 1         | 0.78%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s         | 1         | 0.78%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s         | 1         | 0.78%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.78%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1333MT/s                | 1         | 0.78%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 1         | 0.78%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s        | 1         | 0.78%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 57        | 58.76%  |
| DDR3    | 25        | 25.77%  |
| DDR2    | 5         | 5.15%   |
| SDRAM   | 3         | 3.09%   |
| LPDDR4  | 3         | 3.09%   |
| LPDDR3  | 2         | 2.06%   |
| DDR5    | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 74.23%  |
| DIMM         | 17        | 17.53%  |
| Row Of Chips | 7         | 7.22%   |
| Chip         | 1         | 1.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 39        | 34.82%  |
| 8192  | 38        | 33.93%  |
| 16384 | 14        | 12.5%   |
| 2048  | 13        | 11.61%  |
| 32768 | 6         | 5.36%   |
| 1024  | 2         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 26        | 23.64%  |
| 3200    | 23        | 20.91%  |
| 1600    | 14        | 12.73%  |
| 2400    | 9         | 8.18%   |
| 1334    | 7         | 6.36%   |
| 1333    | 4         | 3.64%   |
| 2133    | 3         | 2.73%   |
| 1867    | 3         | 2.73%   |
| 1066    | 3         | 2.73%   |
| 667     | 3         | 2.73%   |
| 8400    | 2         | 1.82%   |
| 4199    | 2         | 1.82%   |
| 3266    | 2         | 1.82%   |
| Unknown | 2         | 1.82%   |
| 49926   | 1         | 0.91%   |
| 4800    | 1         | 0.91%   |
| 3800    | 1         | 0.91%   |
| 3000    | 1         | 0.91%   |
| 1648    | 1         | 0.91%   |
| 975     | 1         | 0.91%   |
| 800     | 1         | 0.91%   |

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
| Chicony Electronics                    | 24        | 21.62%  |
| Realtek Semiconductor                  | 16        | 14.41%  |
| IMC Networks                           | 14        | 12.61%  |
| Microdia                               | 8         | 7.21%   |
| Acer                                   | 8         | 7.21%   |
| Syntek                                 | 6         | 5.41%   |
| Suyin                                  | 6         | 5.41%   |
| Sunplus Innovation Technology          | 6         | 5.41%   |
| Lite-On Technology                     | 5         | 4.5%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.5%    |
| Quanta                                 | 3         | 2.7%    |
| Luxvisions Innotech Limited            | 3         | 2.7%    |
| Silicon Motion                         | 1         | 0.9%    |
| Ricoh                                  | 1         | 0.9%    |
| Lenovo                                 | 1         | 0.9%    |
| Importek                               | 1         | 0.9%    |
| Cubeternet                             | 1         | 0.9%    |
| Apple                                  | 1         | 0.9%    |
| Alcor Micro                            | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 6.25%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 5.36%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 3.57%   |
| IMC Networks Integrated Camera                              | 4         | 3.57%   |
| Acer Integrated Camera                                      | 4         | 3.57%   |
| Syntek EasyCamera                                           | 3         | 2.68%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 2.68%   |
| Realtek USB Camera                                          | 3         | 2.68%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.68%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 3         | 2.68%   |
| Lite-On Integrated Camera                                   | 3         | 2.68%   |
| Chicony HD WebCam                                           | 3         | 2.68%   |
| Syntek Integrated Camera                                    | 2         | 1.79%   |
| Suyin HP TrueVision HD                                      | 2         | 1.79%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.79%   |
| Realtek EasyCamera                                          | 2         | 1.79%   |
| Quanta HD WebCam                                            | 2         | 1.79%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 1.79%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 1.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.79%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.79%   |
| Chicony EasyCamera                                          | 2         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.79%   |
| Acer HD Webcam                                              | 2         | 1.79%   |
| Syntek Integrated RGB Camera                                | 1         | 0.89%   |
| Suyin USB 2.0 Camera                                        | 1         | 0.89%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.89%   |
| Suyin HD WebCam                                             | 1         | 0.89%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.89%   |
| Sunplus HD User Facing                                      | 1         | 0.89%   |
| Sunplus Dell HD Webcam                                      | 1         | 0.89%   |
| Silicon Motion WebCam SC-13HDL11431N                        | 1         | 0.89%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 0.89%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.89%   |
| Realtek Integrated Webcam                                   | 1         | 0.89%   |
| Realtek HP Webcam                                           | 1         | 0.89%   |
| Quanta HP Webcam                                            | 1         | 0.89%   |
| Microdia Webcam SC-10HDD12636P                              | 1         | 0.89%   |
| Microdia USB 2.0 Camera                                     | 1         | 0.89%   |

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
| 0     | 119       | 72.12%  |
| 1     | 36        | 21.82%  |
| 3     | 5         | 3.03%   |
| 2     | 4         | 2.42%   |
| 4     | 1         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 15        | 26.79%  |
| Net/wireless             | 12        | 21.43%  |
| Fingerprint reader       | 10        | 17.86%  |
| Bluetooth                | 6         | 10.71%  |
| Communication controller | 3         | 5.36%   |
| Chipcard                 | 3         | 5.36%   |
| Storage                  | 2         | 3.57%   |
| Sound                    | 1         | 1.79%   |
| Network                  | 1         | 1.79%   |
| Net/ethernet             | 1         | 1.79%   |
| Card reader              | 1         | 1.79%   |
| Camera                   | 1         | 1.79%   |

