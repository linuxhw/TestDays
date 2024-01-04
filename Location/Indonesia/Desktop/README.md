Linux in Indonesia - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

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

Total: 480

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | DT1234567890 SEC_SW_REVI... | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| Dell          | 033FF6 A00                  | [f54cfd23ee](https://linux-hardware.org/?probe=f54cfd23ee) | Dec 28, 2023 |
| Dell          | 033FF6 A00                  | [977367b99e](https://linux-hardware.org/?probe=977367b99e) | Dec 26, 2023 |
| AZW           | MINI S 10                   | [fbeeeb79f5](https://linux-hardware.org/?probe=fbeeeb79f5) | Dec 25, 2023 |
| Intel         | B75                         | [65bfc8c4cf](https://linux-hardware.org/?probe=65bfc8c4cf) | Dec 24, 2023 |
| Dell          | 033FF6 A00                  | [88cad415fb](https://linux-hardware.org/?probe=88cad415fb) | Dec 21, 2023 |
| ECS           | H81H3-MV                    | [95bd5100ac](https://linux-hardware.org/?probe=95bd5100ac) | Dec 20, 2023 |
| MSI           | Z77A-G43                    | [9afc3e4d49](https://linux-hardware.org/?probe=9afc3e4d49) | Dec 16, 2023 |
| MSI           | Z77A-G43                    | [25c5c9bb33](https://linux-hardware.org/?probe=25c5c9bb33) | Dec 16, 2023 |
| ASUSTek       | Crosshair V Formula         | [4167bf6fe4](https://linux-hardware.org/?probe=4167bf6fe4) | Dec 08, 2023 |
| Intel         | H61                         | [9951d7579f](https://linux-hardware.org/?probe=9951d7579f) | Dec 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [92a2b35bc8](https://linux-hardware.org/?probe=92a2b35bc8) | Dec 01, 2023 |
| Intel         | H61                         | [a0a26787ca](https://linux-hardware.org/?probe=a0a26787ca) | Nov 30, 2023 |
| Minix         | H61M-USB3 V1.2              | [2024379183](https://linux-hardware.org/?probe=2024379183) | Nov 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [dbfedd49f8](https://linux-hardware.org/?probe=dbfedd49f8) | Nov 21, 2023 |
| Dell          | 0HH807                      | [300ee3d8f5](https://linux-hardware.org/?probe=300ee3d8f5) | Nov 08, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [04327aa85c](https://linux-hardware.org/?probe=04327aa85c) | Nov 06, 2023 |
| ASRock        | B550M Pro4                  | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| Gigabyte      | A520I AC                    | [2b76c45313](https://linux-hardware.org/?probe=2b76c45313) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [5787618dae](https://linux-hardware.org/?probe=5787618dae) | Oct 31, 2023 |
| Dell          | 0HH807                      | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| Acer          | EG31M R01-C3                | [8a4232c8f0](https://linux-hardware.org/?probe=8a4232c8f0) | Oct 26, 2023 |
| Gigabyte      | B550M DS3H                  | [a70d4b8a0d](https://linux-hardware.org/?probe=a70d4b8a0d) | Oct 25, 2023 |
| HP            | 198E                        | [3102593d74](https://linux-hardware.org/?probe=3102593d74) | Oct 25, 2023 |
| MSI           | 770T-C45                    | [bbe901612f](https://linux-hardware.org/?probe=bbe901612f) | Oct 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| ASRock        | B550M Pro4                  | [c1e1d017af](https://linux-hardware.org/?probe=c1e1d017af) | Oct 13, 2023 |
| ASRock        | FM2A68M-DG3+                | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| ASRock        | A88M-G                      | [a918b08771](https://linux-hardware.org/?probe=a918b08771) | Sep 30, 2023 |
| Shenzhen M... | F7BSC                       | [79b4f4f30e](https://linux-hardware.org/?probe=79b4f4f30e) | Sep 30, 2023 |
| Gigabyte      | P31-ES3G                    | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [7c8b825512](https://linux-hardware.org/?probe=7c8b825512) | Sep 29, 2023 |
| ZOTAC         | NM10                        | [8932b16aa1](https://linux-hardware.org/?probe=8932b16aa1) | Sep 27, 2023 |
| Acer          | Aspire M5910                | [5b44d1de35](https://linux-hardware.org/?probe=5b44d1de35) | Sep 25, 2023 |
| MSI           | 2A9C                        | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [877e70bb6f](https://linux-hardware.org/?probe=877e70bb6f) | Sep 14, 2023 |
| MSI           | MS-B9091                    | [5b1250945b](https://linux-hardware.org/?probe=5b1250945b) | Sep 11, 2023 |
| MSI           | MS-B9091                    | [226300a88d](https://linux-hardware.org/?probe=226300a88d) | Sep 09, 2023 |
| MSI           | H310M PRO-VH PLUS           | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Acer          | Veriton M480                | [0c97015cce](https://linux-hardware.org/?probe=0c97015cce) | Sep 05, 2023 |
| Foxconn       | G31MX Series                | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [2180bc1b72](https://linux-hardware.org/?probe=2180bc1b72) | Sep 01, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [f7a484830d](https://linux-hardware.org/?probe=f7a484830d) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| ASRock        | H61M-HVGS                   | [1d023bc980](https://linux-hardware.org/?probe=1d023bc980) | Aug 21, 2023 |
| Intel         | H81                         | [70d2da2312](https://linux-hardware.org/?probe=70d2da2312) | Aug 20, 2023 |
| MSI           | 3666h                       | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Gigabyte      | B365M DS3H                  | [857539aaba](https://linux-hardware.org/?probe=857539aaba) | Aug 14, 2023 |
| Gigabyte      | H61M-DS2                    | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASRock        | B550M Pro4                  | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| ASRock        | H61M-HVGS                   | [f78ce03ad4](https://linux-hardware.org/?probe=f78ce03ad4) | Aug 08, 2023 |
| ASRock        | H61M-HVGS                   | [60d9dcfa89](https://linux-hardware.org/?probe=60d9dcfa89) | Aug 08, 2023 |
| ASUSTek       | P5QD TURBO                  | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | [50be5e5725](https://linux-hardware.org/?probe=50be5e5725) | Aug 05, 2023 |
| MSI           | H81M-E35 V2                 | [2e72dc6560](https://linux-hardware.org/?probe=2e72dc6560) | Aug 04, 2023 |
| Dell          | 0GTK4K A10                  | [b6586709f2](https://linux-hardware.org/?probe=b6586709f2) | Aug 03, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Gigabyte      | H61M-DS2                    | [c78c35de44](https://linux-hardware.org/?probe=c78c35de44) | Jul 23, 2023 |
| HP            | 2187 A01                    | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| ASRock        | H510M-HDV/M.2               | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| MSI           | 2A9C                        | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| Gigabyte      | H81M-S2PV                   | [c1c039384c](https://linux-hardware.org/?probe=c1c039384c) | Jul 11, 2023 |
| Gigabyte      | P55-USB3L                   | [b225c530bd](https://linux-hardware.org/?probe=b225c530bd) | Jul 09, 2023 |
| HP            | 8061                        | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| Intel         | Unknown                     | [3c85a0c7b9](https://linux-hardware.org/?probe=3c85a0c7b9) | Jun 28, 2023 |
| Intel         | Unknown                     | [dbfbe4b6aa](https://linux-hardware.org/?probe=dbfbe4b6aa) | Jun 27, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [9bcbbbd906](https://linux-hardware.org/?probe=9bcbbbd906) | Jun 21, 2023 |
| MSI           | B75MA-P45                   | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| MSI           | B350M MORTAR                | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Unknown       | Unknown                     | [76c1fcc4e5](https://linux-hardware.org/?probe=76c1fcc4e5) | Jun 14, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| ASRock        | X670E Pro RS                | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| MSI           | 2A9C                        | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| Unknown       | Unknown                     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| MSI           | 2A9C                        | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| Intel         | H61                         | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASRock        | B560M Pro4                  | [5491fd5858](https://linux-hardware.org/?probe=5491fd5858) | May 05, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | X300-ITX                    | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| AZW           | U59                         | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| Acer          | EG31M R01-C3                | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| MSI           | H310M PRO-VH PLUS           | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| Gigabyte      | B450M DS3H V2               | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| Gigabyte      | P41T-D3                     | [2941019778](https://linux-hardware.org/?probe=2941019778) | Mar 29, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [8e9a11831c](https://linux-hardware.org/?probe=8e9a11831c) | Mar 24, 2023 |
| Gigabyte      | H81M-S2PV                   | [4b6ecef29b](https://linux-hardware.org/?probe=4b6ecef29b) | Mar 19, 2023 |
| GALAX         | B550M                       | [7b8e9c7506](https://linux-hardware.org/?probe=7b8e9c7506) | Mar 11, 2023 |
| Foxconn       | G31MX Series                | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Intel         | H61                         | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| MSI           | Z97-G43 GAMING              | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASRock        | 970A-G                      | [bfdb227a9d](https://linux-hardware.org/?probe=bfdb227a9d) | Feb 24, 2023 |
| ASRock        | A88M-G                      | [917526ad4d](https://linux-hardware.org/?probe=917526ad4d) | Feb 24, 2023 |
| Unknown       | Unknown                     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| AZW           | U59                         | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Intel         | H61                         | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| ECS           | H81H3-MV                    | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| HP            | 198E                        | [7dedbbef80](https://linux-hardware.org/?probe=7dedbbef80) | Feb 04, 2023 |
| Dell          | 0VRWRC A00                  | [dac4a44a62](https://linux-hardware.org/?probe=dac4a44a62) | Jan 27, 2023 |
| ECS           | H61H2-MV                    | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| ASRock        | B550M Pro4                  | [e2486858b9](https://linux-hardware.org/?probe=e2486858b9) | Jan 17, 2023 |
| Lenovo        | 3102 NO DPK                 | [fa7b131a50](https://linux-hardware.org/?probe=fa7b131a50) | Jan 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [7fefb8d34c](https://linux-hardware.org/?probe=7fefb8d34c) | Jan 15, 2023 |
| Intel         | Unknown                     | [6928fe7911](https://linux-hardware.org/?probe=6928fe7911) | Jan 11, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [fd8b340292](https://linux-hardware.org/?probe=fd8b340292) | Jan 05, 2023 |
| Gigabyte      | B550M AORUS PRO             | [bc36d65732](https://linux-hardware.org/?probe=bc36d65732) | Jan 02, 2023 |
| ASRock        | B550M Pro4                  | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| Biostar       | TA970                       | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| HP            | ProLiant ML110 G7           | [7b4b133211](https://linux-hardware.org/?probe=7b4b133211) | Dec 27, 2022 |
| Lenovo        | SHARKBAY NOK                | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| MSI           | H61M-P20                    | [07b5fe983c](https://linux-hardware.org/?probe=07b5fe983c) | Dec 24, 2022 |
| MSI           | H61M-P20                    | [e1d50cc8f4](https://linux-hardware.org/?probe=e1d50cc8f4) | Dec 24, 2022 |
| Dell          | 0JJW8N A03                  | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| Gigabyte      | 970A-D3P                    | [d09b578699](https://linux-hardware.org/?probe=d09b578699) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| ASRock        | H61M-HVGS                   | [7bde3abe5d](https://linux-hardware.org/?probe=7bde3abe5d) | Dec 08, 2022 |
| ASUSTek       | Z8NA-D6                     | [1cd6da46f3](https://linux-hardware.org/?probe=1cd6da46f3) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-F               | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| Intel         | DH55PJ AAE93812-302         | [de105b99e4](https://linux-hardware.org/?probe=de105b99e4) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| ASRock        | B550M Pro4                  | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| MSI           | H510M PRO                   | [182b91241d](https://linux-hardware.org/?probe=182b91241d) | Nov 20, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| MSI           | 2A9C                        | [a531fd4d8e](https://linux-hardware.org/?probe=a531fd4d8e) | Nov 11, 2022 |
| MSI           | 2A9C                        | [599470c2f4](https://linux-hardware.org/?probe=599470c2f4) | Nov 11, 2022 |
| Intel         | P61A-D3                     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| ASRock        | B550M-ITX/ac                | [6d5c1da4b7](https://linux-hardware.org/?probe=6d5c1da4b7) | Oct 20, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7891f1e18c](https://linux-hardware.org/?probe=7891f1e18c) | Oct 18, 2022 |
| HP            | 198E                        | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| ECS           | A55F2-M4                    | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | H61M-C                      | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| Gigabyte      | H81M-S2PV                   | [e1b3cac9d8](https://linux-hardware.org/?probe=e1b3cac9d8) | Sep 07, 2022 |
| Gigabyte      | B560M DS3H V2               | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Gigabyte      | H170-D3H-CF                 | [75a6e1e9a1](https://linux-hardware.org/?probe=75a6e1e9a1) | Aug 29, 2022 |
| Intel         | H61                         | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| ECS           | H61H2-MV                    | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [903fda443e](https://linux-hardware.org/?probe=903fda443e) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| ECS           | H61H2-MV                    | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| ECS           | H61H2-MV                    | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | [4de0aa7ccf](https://linux-hardware.org/?probe=4de0aa7ccf) | Aug 05, 2022 |
| ASRock        | H61M-HVGS                   | [1c95e4f03d](https://linux-hardware.org/?probe=1c95e4f03d) | Aug 04, 2022 |
| Unknown       | Unknown                     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| Gigabyte      | B365M H                     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| MSI           | 2A9C                        | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASUSTek       | H110M-A/DP                  | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| ASUSTek       | H110M-A/DP                  | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Biostar       | A68N-5600E                  | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| ASUSTek       | P5GC-MX/1333                | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| MSI           | 2A9C                        | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| Wearnes       | T1550-A1                    | [b131cd7e0d](https://linux-hardware.org/?probe=b131cd7e0d) | Jun 16, 2022 |
| Wearnes       | T1550-A1                    | [002ebf8c70](https://linux-hardware.org/?probe=002ebf8c70) | Jun 15, 2022 |
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| ASRock        | A88M-G                      | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Biostar       | GF8200C M2+                 | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASRock        | A88M-G                      | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| Unknown       | Unknown                     | [19345cd924](https://linux-hardware.org/?probe=19345cd924) | May 10, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [56cecf6472](https://linux-hardware.org/?probe=56cecf6472) | May 07, 2022 |
| MSI           | H55M-P33                    | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| Unknown       | Unknown                     | [ca7ee75e52](https://linux-hardware.org/?probe=ca7ee75e52) | Apr 01, 2022 |
| HP            | 3641h                       | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| Koloe         | X58                         | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| Intel         | H55                         | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| ZYREX COMP... | TACTICAL                    | [73a4735670](https://linux-hardware.org/?probe=73a4735670) | Mar 12, 2022 |
| Biostar       | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| MSI           | 2A9C                        | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| Dell          | 02YYK5 A01                  | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [3b3c38ec7d](https://linux-hardware.org/?probe=3b3c38ec7d) | Feb 24, 2022 |
| Acer          | Aspire M3970                | [ba6546f689](https://linux-hardware.org/?probe=ba6546f689) | Feb 24, 2022 |
| Intel         | X79G V2.x                   | [cdc3afd163](https://linux-hardware.org/?probe=cdc3afd163) | Feb 24, 2022 |
| Dell          | 0GM819                      | [28011d003e](https://linux-hardware.org/?probe=28011d003e) | Feb 23, 2022 |
| Intel         | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Dell          | 0VRWRC A00                  | [1e54431036](https://linux-hardware.org/?probe=1e54431036) | Feb 15, 2022 |
| ECS           | A58F2P-M4                   | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Dell          | 0Y7WYT A00                  | [3a6bb92957](https://linux-hardware.org/?probe=3a6bb92957) | Feb 13, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [276233dff5](https://linux-hardware.org/?probe=276233dff5) | Feb 11, 2022 |
| Biostar       | A68MHE                      | [d66f9ea911](https://linux-hardware.org/?probe=d66f9ea911) | Feb 10, 2022 |
| Biostar       | A68MHE                      | [edc710a49e](https://linux-hardware.org/?probe=edc710a49e) | Feb 10, 2022 |
| Biostar       | H81MHV3                     | [897c4f4fa5](https://linux-hardware.org/?probe=897c4f4fa5) | Jan 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [af3d4f8c4d](https://linux-hardware.org/?probe=af3d4f8c4d) | Jan 02, 2022 |
| ASUSTek       | Z97-C                       | [2956508483](https://linux-hardware.org/?probe=2956508483) | Dec 31, 2021 |
| ECS           | H61H2-MV                    | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| Foxconn       | 17A0                        | [f3b593c1cf](https://linux-hardware.org/?probe=f3b593c1cf) | Dec 04, 2021 |
| Foxconn       | 17A0                        | [9683f8f23c](https://linux-hardware.org/?probe=9683f8f23c) | Nov 29, 2021 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [f5f0997eca](https://linux-hardware.org/?probe=f5f0997eca) | Nov 28, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [6d67037961](https://linux-hardware.org/?probe=6d67037961) | Nov 16, 2021 |
| Foxconn       | 17A0                        | [ed1128211e](https://linux-hardware.org/?probe=ed1128211e) | Nov 14, 2021 |
| Foxconn       | 17A0                        | [17ff85bc35](https://linux-hardware.org/?probe=17ff85bc35) | Nov 09, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| ASUSTek       | PRIME H310M-K               | [a6cafee332](https://linux-hardware.org/?probe=a6cafee332) | Nov 02, 2021 |
| MSI           | B350M MORTAR                | [bab0e06723](https://linux-hardware.org/?probe=bab0e06723) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | [4fa9117126](https://linux-hardware.org/?probe=4fa9117126) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | [e4fc3665f7](https://linux-hardware.org/?probe=e4fc3665f7) | Oct 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [93b56b7543](https://linux-hardware.org/?probe=93b56b7543) | Oct 29, 2021 |
| MSI           | B350M MORTAR                | [e94404d654](https://linux-hardware.org/?probe=e94404d654) | Oct 26, 2021 |
| Pegatron      | 2AD4                        | [9e231f71ed](https://linux-hardware.org/?probe=9e231f71ed) | Oct 18, 2021 |
| Gigabyte      | EP45-UD3R                   | [ee1862fa4f](https://linux-hardware.org/?probe=ee1862fa4f) | Oct 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [9d1380f4a8](https://linux-hardware.org/?probe=9d1380f4a8) | Oct 15, 2021 |
| Dell          | 0773VG A01                  | [84fc704eaa](https://linux-hardware.org/?probe=84fc704eaa) | Oct 09, 2021 |
| Lenovo        | H310                        | [ce491df5a4](https://linux-hardware.org/?probe=ce491df5a4) | Oct 06, 2021 |
| ASRock        | AB350 Pro4                  | [4038d4a0a6](https://linux-hardware.org/?probe=4038d4a0a6) | Sep 29, 2021 |
| ASRock        | AB350 Pro4                  | [5854a1e114](https://linux-hardware.org/?probe=5854a1e114) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [410a604bab](https://linux-hardware.org/?probe=410a604bab) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1f251e5ba2](https://linux-hardware.org/?probe=1f251e5ba2) | Sep 29, 2021 |
| ASUSTek       | PRIME H510M-D               | [f8fd88bca1](https://linux-hardware.org/?probe=f8fd88bca1) | Sep 26, 2021 |
| ASRock        | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Foxconn       | 17A0                        | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| Gigabyte      | P31-ES3G                    | [5d60817fb5](https://linux-hardware.org/?probe=5d60817fb5) | Sep 11, 2021 |
| Dell          | 0T10XW A00                  | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| ASUSTek       | H61M-K                      | [541ab60180](https://linux-hardware.org/?probe=541ab60180) | Sep 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [9ab0b9612a](https://linux-hardware.org/?probe=9ab0b9612a) | Aug 30, 2021 |
| ASUSTek       | Z97-C                       | [924e556648](https://linux-hardware.org/?probe=924e556648) | Aug 28, 2021 |
| ASRock        | X300M-STX                   | [246709cb9b](https://linux-hardware.org/?probe=246709cb9b) | Aug 27, 2021 |
| ASUSTek       | H81M-C                      | [83393788bf](https://linux-hardware.org/?probe=83393788bf) | Aug 26, 2021 |
| Gigabyte      | EP45-DS3                    | [a2a6e3ee32](https://linux-hardware.org/?probe=a2a6e3ee32) | Aug 24, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [781fc26452](https://linux-hardware.org/?probe=781fc26452) | Aug 23, 2021 |
| ECS           | A960M-MV                    | [684f50eff8](https://linux-hardware.org/?probe=684f50eff8) | Aug 18, 2021 |
| HP            | 2B3C                        | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| ASUSTek       | P5G41T-M LX3                | [2aa00ea596](https://linux-hardware.org/?probe=2aa00ea596) | Aug 15, 2021 |
| ASRock        | AB350 Pro4                  | [2da83ae7b5](https://linux-hardware.org/?probe=2da83ae7b5) | Aug 12, 2021 |
| ASRock        | B450 Pro4                   | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [b4a1e99fc0](https://linux-hardware.org/?probe=b4a1e99fc0) | Jul 28, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [cc1c71078c](https://linux-hardware.org/?probe=cc1c71078c) | Jul 28, 2021 |
| ASRock        | A320M-HDV                   | [20dc9f0df4](https://linux-hardware.org/?probe=20dc9f0df4) | Jul 27, 2021 |
| ASUSTek       | P5G41T-M LX3                | [85fddcd068](https://linux-hardware.org/?probe=85fddcd068) | Jul 26, 2021 |
| Acer          | Veriton L4630G V:1.0        | [c486fbf03f](https://linux-hardware.org/?probe=c486fbf03f) | Jul 25, 2021 |
| Gigabyte      | B460M DS3H                  | [c989b48f08](https://linux-hardware.org/?probe=c989b48f08) | Jul 24, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Gigabyte      | H61M-DS2                    | [fec68f6675](https://linux-hardware.org/?probe=fec68f6675) | Jul 23, 2021 |
| ECS           | G41T-M12                    | [bc6dbc46b6](https://linux-hardware.org/?probe=bc6dbc46b6) | Jul 23, 2021 |
| Biostar       | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek       | H110M-E/M.2                 | [7f0ce9114c](https://linux-hardware.org/?probe=7f0ce9114c) | Jul 21, 2021 |
| Dell          | 0YXT71 A03                  | [eea8e3b740](https://linux-hardware.org/?probe=eea8e3b740) | Jul 14, 2021 |
| Dell          | 0YXT71 A03                  | [e363457394](https://linux-hardware.org/?probe=e363457394) | Jul 13, 2021 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | [533da05156](https://linux-hardware.org/?probe=533da05156) | Jul 12, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9765ba93ab](https://linux-hardware.org/?probe=9765ba93ab) | Jul 10, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [064817cd28](https://linux-hardware.org/?probe=064817cd28) | Jul 05, 2021 |
| MSI           | 870A-G54                    | [b1b8e74ea3](https://linux-hardware.org/?probe=b1b8e74ea3) | Jun 16, 2021 |
| Biostar       | TA870+                      | [c86568a140](https://linux-hardware.org/?probe=c86568a140) | Jun 09, 2021 |
| Lenovo        | SHARKBAY NOK                | [a3cef73da9](https://linux-hardware.org/?probe=a3cef73da9) | Jun 09, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | [414008f0a3](https://linux-hardware.org/?probe=414008f0a3) | Jun 08, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | [744392b18f](https://linux-hardware.org/?probe=744392b18f) | Jun 08, 2021 |
| MSI           | Z97-G43 GAMING              | [0a074f7196](https://linux-hardware.org/?probe=0a074f7196) | Jun 02, 2021 |
| HP            | 1906                        | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| ECS           | G41T-M12                    | [086ce490f7](https://linux-hardware.org/?probe=086ce490f7) | May 29, 2021 |
| ECS           | A55F2-M4                    | [b08197df02](https://linux-hardware.org/?probe=b08197df02) | May 29, 2021 |
| Gigabyte      | P85-D3                      | [a85613d8a6](https://linux-hardware.org/?probe=a85613d8a6) | May 24, 2021 |
| ECS           | H61H2-M2                    | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| Dell          | 0GDG8Y A00                  | [c75161deac](https://linux-hardware.org/?probe=c75161deac) | May 20, 2021 |
| Gigabyte      | B450M DS3H V2               | [8f39af876c](https://linux-hardware.org/?probe=8f39af876c) | May 19, 2021 |
| ASRock        | H81M-VG4 R2.0               | [80070c566e](https://linux-hardware.org/?probe=80070c566e) | May 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [f900105a8a](https://linux-hardware.org/?probe=f900105a8a) | May 09, 2021 |
| Acer          | Veriton M2611 v1.0          | [82b2ea1868](https://linux-hardware.org/?probe=82b2ea1868) | May 06, 2021 |
| Acer          | Veriton M2611 v1.0          | [218de62b27](https://linux-hardware.org/?probe=218de62b27) | May 06, 2021 |
| Unknown       | Unknown                     | [327d214403](https://linux-hardware.org/?probe=327d214403) | May 04, 2021 |
| Gigabyte      | H81M-DS2                    | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| ECS           | 945GCT-M2                   | [3f73514b16](https://linux-hardware.org/?probe=3f73514b16) | Apr 26, 2021 |
| ECS           | 945GCT-M2                   | [289b6cba53](https://linux-hardware.org/?probe=289b6cba53) | Apr 25, 2021 |
| MSI           | Z97-G43 GAMING              | [ca62d8f11b](https://linux-hardware.org/?probe=ca62d8f11b) | Apr 21, 2021 |
| MSI           | Z97-G43 GAMING              | [f71c55764e](https://linux-hardware.org/?probe=f71c55764e) | Apr 21, 2021 |
| Lenovo        | ThinkCentre A70 7099S3A     | [2fd4915fe8](https://linux-hardware.org/?probe=2fd4915fe8) | Apr 16, 2021 |
| ASRock        | B560M Pro4                  | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASRock        | B450 Pro4                   | [e83e7312c9](https://linux-hardware.org/?probe=e83e7312c9) | Apr 08, 2021 |
| MSI           | B85M GAMING                 | [bf0490433a](https://linux-hardware.org/?probe=bf0490433a) | Apr 07, 2021 |
| MSI           | B550-A PRO                  | [f7ddac6f83](https://linux-hardware.org/?probe=f7ddac6f83) | Apr 02, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [a5d5c057c0](https://linux-hardware.org/?probe=a5d5c057c0) | Mar 24, 2021 |
| MSI           | B460M PRO                   | [3a26303ce0](https://linux-hardware.org/?probe=3a26303ce0) | Mar 21, 2021 |
| MSI           | B460M PRO                   | [82bf6fd41b](https://linux-hardware.org/?probe=82bf6fd41b) | Mar 21, 2021 |
| ASRock        | B450 Pro4                   | [ed1a952ed3](https://linux-hardware.org/?probe=ed1a952ed3) | Mar 17, 2021 |
| Unknown       | Unknown                     | [b4b92701a0](https://linux-hardware.org/?probe=b4b92701a0) | Mar 05, 2021 |
| Biostar       | H61MGV3                     | [85e0a1cacc](https://linux-hardware.org/?probe=85e0a1cacc) | Mar 01, 2021 |
| ASUSTek       | H61M-K                      | [b59c5fdb8a](https://linux-hardware.org/?probe=b59c5fdb8a) | Feb 28, 2021 |
| ASRock        | FM2A68M-HD+                 | [95c5fe898a](https://linux-hardware.org/?probe=95c5fe898a) | Feb 27, 2021 |
| Lenovo        | Unknown                     | [0ca27a0ce2](https://linux-hardware.org/?probe=0ca27a0ce2) | Feb 24, 2021 |
| Gigabyte      | B460M DS3H                  | [fe95f7aef8](https://linux-hardware.org/?probe=fe95f7aef8) | Feb 19, 2021 |
| Biostar       | Hi-Fi A68U3P                | [b1edb9db86](https://linux-hardware.org/?probe=b1edb9db86) | Feb 19, 2021 |
| Biostar       | Hi-Fi A68U3P                | [abc0ef8bc7](https://linux-hardware.org/?probe=abc0ef8bc7) | Feb 19, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [502bc7eb2a](https://linux-hardware.org/?probe=502bc7eb2a) | Feb 04, 2021 |
| Gigabyte      | B460M DS3H                  | [8d369a84ce](https://linux-hardware.org/?probe=8d369a84ce) | Feb 04, 2021 |
| Gigabyte      | B460M DS3H                  | [95883e3fff](https://linux-hardware.org/?probe=95883e3fff) | Feb 04, 2021 |
| HP            | 834F                        | [c849bbc95a](https://linux-hardware.org/?probe=c849bbc95a) | Jan 14, 2021 |
| Lenovo        | 36EB SDK0Q55726 WIN 3273... | [ace52f974e](https://linux-hardware.org/?probe=ace52f974e) | Jan 13, 2021 |
| Gigabyte      | A320M-DS2-CF                | [414638f163](https://linux-hardware.org/?probe=414638f163) | Jan 07, 2021 |
| Gigabyte      | Z370N WIFI-CF               | [9fe6d5b992](https://linux-hardware.org/?probe=9fe6d5b992) | Jan 02, 2021 |
| MSI           | G41M-P26                    | [8d7a10a828](https://linux-hardware.org/?probe=8d7a10a828) | Dec 31, 2020 |
| MSI           | 760GM-P23                   | [9ea9c09319](https://linux-hardware.org/?probe=9ea9c09319) | Dec 27, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [405b8ef206](https://linux-hardware.org/?probe=405b8ef206) | Dec 25, 2020 |
| MSI           | 870A-G54                    | [479ee62f9f](https://linux-hardware.org/?probe=479ee62f9f) | Dec 21, 2020 |
| HP            | 1497                        | [1bfa453ea4](https://linux-hardware.org/?probe=1bfa453ea4) | Dec 19, 2020 |
| HP            | 1497                        | [9b292e4071](https://linux-hardware.org/?probe=9b292e4071) | Dec 19, 2020 |
| MSI           | B360 GAMING PLUS            | [7a77cc7ec2](https://linux-hardware.org/?probe=7a77cc7ec2) | Dec 12, 2020 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [3e44b38d7f](https://linux-hardware.org/?probe=3e44b38d7f) | Dec 03, 2020 |
| ASRock        | H67M                        | [11ccd3281d](https://linux-hardware.org/?probe=11ccd3281d) | Nov 28, 2020 |
| Acer          | Aspire M3970                | [7350b05e56](https://linux-hardware.org/?probe=7350b05e56) | Nov 25, 2020 |
| Acer          | Aspire M3970                | [f380a566c2](https://linux-hardware.org/?probe=f380a566c2) | Nov 25, 2020 |
| Acer          | Veriton X4610G              | [e9ace7d042](https://linux-hardware.org/?probe=e9ace7d042) | Nov 24, 2020 |
| Dell          | 08HPGT A01                  | [d5ae57d261](https://linux-hardware.org/?probe=d5ae57d261) | Nov 20, 2020 |
| ASRock        | B450 Pro4                   | [f24f7ba17e](https://linux-hardware.org/?probe=f24f7ba17e) | Nov 13, 2020 |
| Dell          | 0GY6Y8 A00                  | [613e036e8d](https://linux-hardware.org/?probe=613e036e8d) | Nov 11, 2020 |
| MSI           | H410M PRO-VH                | [e5603638aa](https://linux-hardware.org/?probe=e5603638aa) | Nov 10, 2020 |
| MSI           | 870A-G54                    | [d14df17124](https://linux-hardware.org/?probe=d14df17124) | Nov 08, 2020 |
| HP            | 304Ah                       | [530cc628fb](https://linux-hardware.org/?probe=530cc628fb) | Nov 07, 2020 |
| HP            | 304Ah                       | [0ed06ad934](https://linux-hardware.org/?probe=0ed06ad934) | Nov 04, 2020 |
| Gigabyte      | H81M-Gaming 3               | [8d7b38dbf3](https://linux-hardware.org/?probe=8d7b38dbf3) | Nov 03, 2020 |
| Gigabyte      | H81M-Gaming 3               | [0c6140c86e](https://linux-hardware.org/?probe=0c6140c86e) | Nov 03, 2020 |
| MSI           | B85M GAMING                 | [b2b720adf7](https://linux-hardware.org/?probe=b2b720adf7) | Oct 28, 2020 |
| HP            | 1493                        | [cf9c3c195a](https://linux-hardware.org/?probe=cf9c3c195a) | Oct 24, 2020 |
| Quanta        | 2B03 110                    | [afa8ef9dda](https://linux-hardware.org/?probe=afa8ef9dda) | Oct 20, 2020 |
| ASRock        | X99 Taichi                  | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| Lenovo        | SKYBAY NOK                  | [f02492e188](https://linux-hardware.org/?probe=f02492e188) | Oct 08, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [805323645e](https://linux-hardware.org/?probe=805323645e) | Oct 04, 2020 |
| ASUSTek       | H110M-E/M.2                 | [e937cdfcbc](https://linux-hardware.org/?probe=e937cdfcbc) | Sep 28, 2020 |
| MSI           | B360 GAMING PLUS            | [6b3915fc77](https://linux-hardware.org/?probe=6b3915fc77) | Sep 28, 2020 |
| ASRock        | B365M Phantom Gaming 4      | [9f213e1442](https://linux-hardware.org/?probe=9f213e1442) | Sep 25, 2020 |
| Lenovo        | ThinkCentre M57p 9193A11    | [4d8a70073f](https://linux-hardware.org/?probe=4d8a70073f) | Sep 25, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [8be0a34480](https://linux-hardware.org/?probe=8be0a34480) | Sep 16, 2020 |
| Gigabyte      | H81M-S2PH                   | [b5438c62fc](https://linux-hardware.org/?probe=b5438c62fc) | Sep 16, 2020 |
| ECS           | Z97M-PK                     | [888e740324](https://linux-hardware.org/?probe=888e740324) | Sep 13, 2020 |
| MSI           | B360 GAMING PLUS            | [6c5d768e02](https://linux-hardware.org/?probe=6c5d768e02) | Sep 10, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [c363153de4](https://linux-hardware.org/?probe=c363153de4) | Sep 08, 2020 |
| MSI           | B350M MORTAR                | [ebcd809d62](https://linux-hardware.org/?probe=ebcd809d62) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [6d06e18252](https://linux-hardware.org/?probe=6d06e18252) | Aug 30, 2020 |
| MSI           | B75MA-P33                   | [05483ed2c3](https://linux-hardware.org/?probe=05483ed2c3) | Aug 28, 2020 |
| MSI           | 870A-G54                    | [727980a18d](https://linux-hardware.org/?probe=727980a18d) | Aug 23, 2020 |
| SPECTRUM U... | VA 880G                     | [ef0b289382](https://linux-hardware.org/?probe=ef0b289382) | Aug 21, 2020 |
| ASRock        | A300M-STX                   | [0aeef3e18b](https://linux-hardware.org/?probe=0aeef3e18b) | Aug 19, 2020 |
| Lenovo        | SHARKBAY NOK                | [f205ba371e](https://linux-hardware.org/?probe=f205ba371e) | Aug 19, 2020 |
| MSI           | 870A-G54                    | [292a02f724](https://linux-hardware.org/?probe=292a02f724) | Aug 17, 2020 |
| Biostar       | H310MHC                     | [4331ff5e27](https://linux-hardware.org/?probe=4331ff5e27) | Aug 14, 2020 |
| Dell          | 0D28YY A01                  | [6740e51a94](https://linux-hardware.org/?probe=6740e51a94) | Aug 14, 2020 |
| NEC Comput... | MS-7264LW                   | [63f1552717](https://linux-hardware.org/?probe=63f1552717) | Aug 09, 2020 |
| NEC Comput... | MS-7264LW                   | [bc4eab7fa3](https://linux-hardware.org/?probe=bc4eab7fa3) | Aug 09, 2020 |
| MSI           | B85M GAMING                 | [984c0ed0a7](https://linux-hardware.org/?probe=984c0ed0a7) | Aug 07, 2020 |
| ASRock        | A320M-HDV R4.0              | [87a26416b1](https://linux-hardware.org/?probe=87a26416b1) | Aug 06, 2020 |
| MSI           | H81M-P33                    | [f9cb52c02a](https://linux-hardware.org/?probe=f9cb52c02a) | Aug 05, 2020 |
| ASUSTek       | PRIME H410M-E               | [ecd5a9cdd0](https://linux-hardware.org/?probe=ecd5a9cdd0) | Aug 01, 2020 |
| ASUSTek       | PRIME H410M-E               | [f95e229d75](https://linux-hardware.org/?probe=f95e229d75) | Aug 01, 2020 |
| MSI           | B85M GAMING                 | [ca027f475e](https://linux-hardware.org/?probe=ca027f475e) | Jul 28, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | [5a271f15c2](https://linux-hardware.org/?probe=5a271f15c2) | Jul 28, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [f34a4c062d](https://linux-hardware.org/?probe=f34a4c062d) | Jul 26, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | [1d18d6d402](https://linux-hardware.org/?probe=1d18d6d402) | Jul 25, 2020 |
| MSI           | B85M GAMING                 | [29191c1b1e](https://linux-hardware.org/?probe=29191c1b1e) | Jul 24, 2020 |
| OEM           | G41 775 ICH7 8712           | [bdbd588c54](https://linux-hardware.org/?probe=bdbd588c54) | Jul 24, 2020 |
| MSI           | 870A-G54                    | [74d1532bd8](https://linux-hardware.org/?probe=74d1532bd8) | Jul 15, 2020 |
| MSI           | 870A-G54                    | [9110e601b2](https://linux-hardware.org/?probe=9110e601b2) | Jul 15, 2020 |
| MSI           | 870A-G54                    | [ce919dba00](https://linux-hardware.org/?probe=ce919dba00) | Jul 09, 2020 |
| Intel         | Unknown                     | [9224b78dd5](https://linux-hardware.org/?probe=9224b78dd5) | Jul 07, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [21af10b11c](https://linux-hardware.org/?probe=21af10b11c) | Jul 03, 2020 |
| Nvidia        | NF-MCP68                    | [6b42b5244e](https://linux-hardware.org/?probe=6b42b5244e) | Jun 23, 2020 |
| Unknown       | G41 Series                  | [5f2347032e](https://linux-hardware.org/?probe=5f2347032e) | Jun 16, 2020 |
| MSI           | 870A-G54                    | [4c34d33e03](https://linux-hardware.org/?probe=4c34d33e03) | Jun 15, 2020 |
| ECS           | Z77H2-A2X Deluxe            | [5bb6af2e45](https://linux-hardware.org/?probe=5bb6af2e45) | Jun 14, 2020 |
| ECS           | Z77H2-A2X Deluxe            | [c06f108477](https://linux-hardware.org/?probe=c06f108477) | Jun 14, 2020 |
| MSI           | 870A-G54                    | [8f14b79b6a](https://linux-hardware.org/?probe=8f14b79b6a) | Jun 14, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [ab1f7a9baa](https://linux-hardware.org/?probe=ab1f7a9baa) | Jun 11, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [e30aeca065](https://linux-hardware.org/?probe=e30aeca065) | Jun 11, 2020 |
| ASRock        | G41M-VS3                    | [8918ed5ee1](https://linux-hardware.org/?probe=8918ed5ee1) | May 29, 2020 |
| ASRock        | FM2A68M-DG3+                | [34ec73be33](https://linux-hardware.org/?probe=34ec73be33) | May 29, 2020 |
| ASRock        | FM2A68M-DG3+                | [f56d577ca6](https://linux-hardware.org/?probe=f56d577ca6) | May 29, 2020 |
| Gigabyte      | EP45-DS3LR                  | [1aa541af52](https://linux-hardware.org/?probe=1aa541af52) | May 29, 2020 |
| ECS           | P43G                        | [61bbe10085](https://linux-hardware.org/?probe=61bbe10085) | May 28, 2020 |
| ECS           | P43G                        | [13a37c39ae](https://linux-hardware.org/?probe=13a37c39ae) | May 28, 2020 |
| MSI           | B85M GAMING                 | [ce4c6b31d7](https://linux-hardware.org/?probe=ce4c6b31d7) | May 24, 2020 |
| ASRock        | G41M-VS3                    | [b8573ae92c](https://linux-hardware.org/?probe=b8573ae92c) | May 23, 2020 |
| MSI           | B85M GAMING                 | [aba32f928c](https://linux-hardware.org/?probe=aba32f928c) | May 17, 2020 |
| Gigabyte      | H61M-DS2                    | [16bcd5ac39](https://linux-hardware.org/?probe=16bcd5ac39) | May 02, 2020 |
| MSI           | P55-CD53                    | [afb112f2e5](https://linux-hardware.org/?probe=afb112f2e5) | May 02, 2020 |
| Gigabyte      | H61M-DS2                    | [e16a4f321c](https://linux-hardware.org/?probe=e16a4f321c) | Apr 29, 2020 |
| MSI           | 970A-G45                    | [6ac0a4fa90](https://linux-hardware.org/?probe=6ac0a4fa90) | Apr 26, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [6adbd75b76](https://linux-hardware.org/?probe=6adbd75b76) | Apr 24, 2020 |
| Biostar       | H310MHC                     | [49ba466f80](https://linux-hardware.org/?probe=49ba466f80) | Apr 17, 2020 |
| Biostar       | H310MHC                     | [b7a62e3806](https://linux-hardware.org/?probe=b7a62e3806) | Apr 17, 2020 |
| ECS           | H61H2-M12                   | [ae9b0e4fc7](https://linux-hardware.org/?probe=ae9b0e4fc7) | Apr 15, 2020 |
| ECS           | H61H2-M12                   | [de706540bb](https://linux-hardware.org/?probe=de706540bb) | Apr 15, 2020 |
| ECS           | H61H2-M12                   | [e7b1567091](https://linux-hardware.org/?probe=e7b1567091) | Apr 15, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS            | [de7c9abd9e](https://linux-hardware.org/?probe=de7c9abd9e) | Apr 14, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS            | [39347abd01](https://linux-hardware.org/?probe=39347abd01) | Apr 07, 2020 |
| Inventec      | DQ Class A02                | [8b47d0dec9](https://linux-hardware.org/?probe=8b47d0dec9) | Apr 07, 2020 |
| Inventec      | DQ Class A02                | [de75fa5904](https://linux-hardware.org/?probe=de75fa5904) | Apr 06, 2020 |
| ASRock        | X570 Steel Legend           | [9ebe70290a](https://linux-hardware.org/?probe=9ebe70290a) | Apr 05, 2020 |
| Biostar       | X370GT3                     | [1eba7843c7](https://linux-hardware.org/?probe=1eba7843c7) | Apr 03, 2020 |
| Biostar       | X370GT3                     | [4a91b87778](https://linux-hardware.org/?probe=4a91b87778) | Apr 03, 2020 |
| Dell          | 07C0H8 A00                  | [6863933279](https://linux-hardware.org/?probe=6863933279) | Mar 18, 2020 |
| ASUSTek       | CG8580                      | [a2755006be](https://linux-hardware.org/?probe=a2755006be) | Feb 22, 2020 |
| ASUSTek       | CG8580                      | [ca764ea79e](https://linux-hardware.org/?probe=ca764ea79e) | Feb 22, 2020 |
| ASUSTek       | H81M-E                      | [d4fc5bee1a](https://linux-hardware.org/?probe=d4fc5bee1a) | Feb 21, 2020 |
| ASUSTek       | H81M-E                      | [ee2cf3834b](https://linux-hardware.org/?probe=ee2cf3834b) | Feb 21, 2020 |
| ASUSTek       | H97M-E                      | [583ff222dc](https://linux-hardware.org/?probe=583ff222dc) | Feb 20, 2020 |
| Intel         | Unknown                     | [ed1af52d9b](https://linux-hardware.org/?probe=ed1af52d9b) | Feb 14, 2020 |
| Dell          | 09KPNV A00                  | [a242b5b90b](https://linux-hardware.org/?probe=a242b5b90b) | Feb 07, 2020 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [ef5e60b804](https://linux-hardware.org/?probe=ef5e60b804) | Feb 06, 2020 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [e2ad5e1470](https://linux-hardware.org/?probe=e2ad5e1470) | Feb 06, 2020 |
| Biostar       | B45M2                       | [d5e8a2ad7a](https://linux-hardware.org/?probe=d5e8a2ad7a) | Jan 18, 2020 |
| Biostar       | B45M2                       | [8fde9c57e5](https://linux-hardware.org/?probe=8fde9c57e5) | Jan 18, 2020 |
| MSI           | 2A78h                       | [275a99a2fe](https://linux-hardware.org/?probe=275a99a2fe) | Jan 06, 2020 |
| Intel         | DG31PR AAD97573-306         | [7f477da95d](https://linux-hardware.org/?probe=7f477da95d) | Dec 12, 2019 |
| Biostar       | H310MHC                     | [a2ad758a5a](https://linux-hardware.org/?probe=a2ad758a5a) | Oct 29, 2019 |
| Biostar       | H310MHC                     | [3b6265a2aa](https://linux-hardware.org/?probe=3b6265a2aa) | Oct 29, 2019 |
| Dell          | 0T656F A01                  | [7a0f0d92a8](https://linux-hardware.org/?probe=7a0f0d92a8) | Oct 18, 2019 |
| ECS           | A785GM-AD3                  | [69dee2c465](https://linux-hardware.org/?probe=69dee2c465) | Oct 10, 2019 |
| ASUSTek       | M4A785TD-V EVO              | [85e109926e](https://linux-hardware.org/?probe=85e109926e) | Sep 20, 2019 |
| Intel         | DX58SO AAE29331-703         | [8a2de6109c](https://linux-hardware.org/?probe=8a2de6109c) | Sep 17, 2019 |
| Intel         | DG31PR AAD97573-306         | [1b36a15fbc](https://linux-hardware.org/?probe=1b36a15fbc) | Sep 17, 2019 |
| Intel         | DX58SO AAE29331-703         | [bc3adc24d0](https://linux-hardware.org/?probe=bc3adc24d0) | Sep 12, 2019 |
| ASUSTek       | P5KPL-AM                    | [7da787439e](https://linux-hardware.org/?probe=7da787439e) | Sep 11, 2019 |
| Gigabyte      | H310M S2P                   | [6fffbe0439](https://linux-hardware.org/?probe=6fffbe0439) | Sep 02, 2019 |
| Intel         | D525MW AAE93082-400         | [89a1e0ba41](https://linux-hardware.org/?probe=89a1e0ba41) | Sep 01, 2019 |
| ASUSTek       | P5KPL-AM                    | [11025c5412](https://linux-hardware.org/?probe=11025c5412) | Aug 27, 2019 |
| MSI           | 0AB8                        | [1728939e55](https://linux-hardware.org/?probe=1728939e55) | Aug 22, 2019 |
| ASUSTek       | P5KPL-AM EPU                | [4272d3a201](https://linux-hardware.org/?probe=4272d3a201) | Aug 22, 2019 |
| ASRock        | A320M-HDV R4.0              | [cce7f9292d](https://linux-hardware.org/?probe=cce7f9292d) | Jul 23, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f664fb0c42](https://linux-hardware.org/?probe=f664fb0c42) | Jul 22, 2019 |
| MSI           | H110M PRO-VH PLUS           | [cdce9b48f0](https://linux-hardware.org/?probe=cdce9b48f0) | Jul 20, 2019 |
| Dell          | 02YRK5 A02                  | [18212fdd56](https://linux-hardware.org/?probe=18212fdd56) | Jul 11, 2019 |
| Dell          | 02YRK5 A02                  | [9fa1b2681a](https://linux-hardware.org/?probe=9fa1b2681a) | Jul 10, 2019 |
| Jetway        | TA55MG2-OC                  | [f2e67158f7](https://linux-hardware.org/?probe=f2e67158f7) | Jul 06, 2019 |
| Jetway        | TA55MG2-OC                  | [7ac413972b](https://linux-hardware.org/?probe=7ac413972b) | Jul 06, 2019 |
| Biostar       | R690A-M2T                   | [6c00967a8c](https://linux-hardware.org/?probe=6c00967a8c) | Jul 03, 2019 |
| ASRock        | H61M-VS3                    | [1192feeead](https://linux-hardware.org/?probe=1192feeead) | Jun 20, 2019 |
| HP            | 2B60 MVB                    | [931efec797](https://linux-hardware.org/?probe=931efec797) | Jun 11, 2019 |
| Biostar       | TB250-BTC PRO               | [56d589996a](https://linux-hardware.org/?probe=56d589996a) | May 23, 2019 |
| Biostar       | TB250-BTC PRO               | [41c5a400a2](https://linux-hardware.org/?probe=41c5a400a2) | May 23, 2019 |
| Biostar       | TB250-BTC PRO               | [e5699ad7bf](https://linux-hardware.org/?probe=e5699ad7bf) | May 23, 2019 |
| Biostar       | G31M+                       | [ee05f6ce67](https://linux-hardware.org/?probe=ee05f6ce67) | May 20, 2019 |
| Gigabyte      | H310M DS2                   | [229e72bc4f](https://linux-hardware.org/?probe=229e72bc4f) | May 20, 2019 |
| Lenovo        | MAHOBAY NOK                 | [2e7abfe281](https://linux-hardware.org/?probe=2e7abfe281) | May 18, 2019 |
| Dell          | 0WR7PY A02                  | [6e00c71124](https://linux-hardware.org/?probe=6e00c71124) | May 14, 2019 |
| ASUSTek       | P8H67-V                     | [f39c397507](https://linux-hardware.org/?probe=f39c397507) | May 09, 2019 |
| Intel         | Unknown                     | [a467374ecd](https://linux-hardware.org/?probe=a467374ecd) | Apr 25, 2019 |
| ASUSTek       | P5G41C-M LX                 | [e4433722a7](https://linux-hardware.org/?probe=e4433722a7) | Feb 24, 2019 |
| ASUSTek       | P5G41C-M LX                 | [7e4001ef6e](https://linux-hardware.org/?probe=7e4001ef6e) | Feb 24, 2019 |
| MSI           | 785GM-E51                   | [06046973d6](https://linux-hardware.org/?probe=06046973d6) | Jan 08, 2019 |
| ASRock        | Z77 Professional            | [8bc3d31d80](https://linux-hardware.org/?probe=8bc3d31d80) | Dec 03, 2018 |
| ASRock        | Z77 Professional            | [243ff79ac2](https://linux-hardware.org/?probe=243ff79ac2) | Nov 30, 2018 |
| Dell          | 0J3C2F A02                  | [3b377580ad](https://linux-hardware.org/?probe=3b377580ad) | Nov 07, 2018 |
| Dell          | 0J3C2F A02                  | [17cec4b4ca](https://linux-hardware.org/?probe=17cec4b4ca) | Nov 06, 2018 |
| Intel         | DG31PR AAD97573-306         | [cf36e3e24d](https://linux-hardware.org/?probe=cf36e3e24d) | Oct 20, 2018 |
| ASRock        | G41M-VS3                    | [7bb4fff693](https://linux-hardware.org/?probe=7bb4fff693) | Sep 25, 2018 |
| ASUSTek       | P5QPL-VM EPU                | [6c4195dd46](https://linux-hardware.org/?probe=6c4195dd46) | Jul 30, 2018 |
| ASUSTek       | F1A55-M LX PLUS             | [bd4bad9fd4](https://linux-hardware.org/?probe=bd4bad9fd4) | Apr 23, 2017 |
| ASUSTek       | P5KPL-AM SE                 | [5128fdeca3](https://linux-hardware.org/?probe=5128fdeca3) | Dec 07, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 44       | 12.57%  |
| Ubuntu 18.04                 | 32       | 9.14%   |
| OpenMandriva 4.3             | 20       | 5.71%   |
| Ubuntu 22.04                 | 13       | 3.71%   |
| Zorin 15                     | 10       | 2.86%   |
| OpenMandriva 4.2             | 8        | 2.29%   |
| KDE neon 20.04               | 7        | 2%      |
| Arch Rolling                 | 7        | 2%      |
| Zorin 16                     | 6        | 1.71%   |
| OpenMandriva 23.03           | 6        | 1.71%   |
| Elementary 6.1               | 6        | 1.71%   |
| OpenMandriva 23.01           | 5        | 1.43%   |
| Linux Mint 19.3              | 5        | 1.43%   |
| Fedora 38                    | 5        | 1.43%   |
| ArcoLinux Rolling            | 5        | 1.43%   |
| Xubuntu 20.04                | 4        | 1.14%   |
| Ubuntu Unity 20.04           | 4        | 1.14%   |
| Pop!_OS 22.04                | 4        | 1.14%   |
| Pop!_OS 20.04                | 4        | 1.14%   |
| Fedora 35                    | 4        | 1.14%   |
| Fedora 33                    | 4        | 1.14%   |
| Fedora 32                    | 4        | 1.14%   |
| Debian 12                    | 4        | 1.14%   |
| Arch                         | 4        | 1.14%   |
| Ubuntu 21.10                 | 3        | 0.86%   |
| Ubuntu 20.10                 | 3        | 0.86%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 0.86%   |
| OpenMandriva 4.50            | 3        | 0.86%   |
| Linux Mint 20.1              | 3        | 0.86%   |
| Linux Mint 20                | 3        | 0.86%   |
| Fedora 37                    | 3        | 0.86%   |
| Fedora 36                    | 3        | 0.86%   |
| Elementary 6                 | 3        | 0.86%   |
| Debian 11                    | 3        | 0.86%   |
| Ubuntu 21.04                 | 2        | 0.57%   |
| Ubuntu 19.10                 | 2        | 0.57%   |
| Sparky 6.2                   | 2        | 0.57%   |
| ROSA R10                     | 2        | 0.57%   |
| Rocky Linux 9.1              | 2        | 0.57%   |
| OpenMandriva 23.10           | 2        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 101      | 30.24%  |
| OpenMandriva | 47       | 14.07%  |
| Linux Mint   | 22       | 6.59%   |
| Fedora       | 21       | 6.29%   |
| Zorin        | 18       | 5.39%   |
| Elementary   | 11       | 3.29%   |
| Arch         | 11       | 3.29%   |
| Pop!_OS      | 9        | 2.69%   |
| Endless      | 9        | 2.69%   |
| Debian       | 8        | 2.4%    |
| Manjaro      | 7        | 2.1%    |
| KDE neon     | 7        | 2.1%    |
| Xubuntu      | 6        | 1.8%    |
| ROSA         | 5        | 1.5%    |
| Kubuntu      | 5        | 1.5%    |
| Kali         | 5        | 1.5%    |
| ArcoLinux    | 5        | 1.5%    |
| Ubuntu Unity | 4        | 1.2%    |
| openSUSE     | 4        | 1.2%    |
| Lubuntu      | 3        | 0.9%    |
| Clear Linux  | 3        | 0.9%    |
| Sparky       | 2        | 0.6%    |
| Rocky Linux  | 2        | 0.6%    |
| MX           | 2        | 0.6%    |
| LMDE         | 2        | 0.6%    |
| EndeavourOS  | 2        | 0.6%    |
| CentOS       | 2        | 0.6%    |
| UbuntuDDE    | 1        | 0.3%    |
| Ubuntu MATE  | 1        | 0.3%    |
| RHEL         | 1        | 0.3%    |
| Peux OS      | 1        | 0.3%    |
| Parrot       | 1        | 0.3%    |
| Nobara       | 1        | 0.3%    |
| Lilidog      | 1        | 0.3%    |
| Gentoo       | 1        | 0.3%    |
| Funtoo       | 1        | 0.3%    |
| Deepin       | 1        | 0.3%    |
| Alpine       | 1        | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 19       | 4.95%   |
| 5.4.0-42-generic         | 11       | 2.86%   |
| 5.15.0-56-generic        | 8        | 2.08%   |
| 5.4.0-52-generic         | 7        | 1.82%   |
| 6.2.6-desktop-1omv2390   | 6        | 1.56%   |
| 5.4.0-26-generic         | 6        | 1.56%   |
| 5.4.0-58-generic         | 5        | 1.3%    |
| 5.10.14-desktop-1omv4002 | 5        | 1.3%    |
| 5.8.0-14-generic         | 4        | 1.04%   |
| 5.4.0-80-generic         | 4        | 1.04%   |
| 5.3.0-28-generic         | 4        | 1.04%   |
| 6.1.1-desktop-1omv2290   | 3        | 0.78%   |
| 5.4.0-81-generic         | 3        | 0.78%   |
| 5.15.0-43-generic        | 3        | 0.78%   |
| 5.13.0-41-generic        | 3        | 0.78%   |
| 5.11.12-desktop-1omv4002 | 3        | 0.78%   |
| 5.11.0-43-generic        | 3        | 0.78%   |
| 6.5.5-desktop-1omv2390   | 2        | 0.52%   |
| 6.4.11-desktop-1omv2390  | 2        | 0.52%   |
| 6.3.8-200.fc38.x86_64    | 2        | 0.52%   |
| 6.3.5-desktop-3omv2390   | 2        | 0.52%   |
| 6.2.0-20-generic         | 2        | 0.52%   |
| 6.1.4-desktop-1omv2301   | 2        | 0.52%   |
| 6.1.0-9-amd64            | 2        | 0.52%   |
| 5.8.0-53-generic         | 2        | 0.52%   |
| 5.8.0-45-generic         | 2        | 0.52%   |
| 5.4.0-77-generic         | 2        | 0.52%   |
| 5.4.0-7642-generic       | 2        | 0.52%   |
| 5.4.0-74-generic         | 2        | 0.52%   |
| 5.4.0-65-generic         | 2        | 0.52%   |
| 5.4.0-53-generic         | 2        | 0.52%   |
| 5.4.0-48-generic         | 2        | 0.52%   |
| 5.4.0-37-generic         | 2        | 0.52%   |
| 5.4.0-33-generic         | 2        | 0.52%   |
| 5.4.0-148-generic        | 2        | 0.52%   |
| 5.3.0-46-generic         | 2        | 0.52%   |
| 5.3.0-45-generic         | 2        | 0.52%   |
| 5.3.0-40-generic         | 2        | 0.52%   |
| 5.19.5-desktop-1omv4090  | 2        | 0.52%   |
| 5.19.0-46-generic        | 2        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 63       | 17.12%  |
| 5.15.0  | 26       | 7.07%   |
| 5.16.7  | 20       | 5.43%   |
| 4.15.0  | 17       | 4.62%   |
| 5.8.0   | 16       | 4.35%   |
| 5.11.0  | 15       | 4.08%   |
| 5.3.0   | 14       | 3.8%    |
| 5.13.0  | 13       | 3.53%   |
| 4.18.0  | 13       | 3.53%   |
| 5.0.0   | 10       | 2.72%   |
| 5.10.0  | 8        | 2.17%   |
| 6.2.6   | 7        | 1.9%    |
| 6.1.1   | 6        | 1.63%   |
| 6.1.0   | 6        | 1.63%   |
| 5.19.0  | 6        | 1.63%   |
| 5.10.14 | 5        | 1.36%   |
| 6.5.5   | 4        | 1.09%   |
| 6.2.0   | 4        | 1.09%   |
| 5.9.16  | 3        | 0.82%   |
| 5.14.0  | 3        | 0.82%   |
| 5.11.12 | 3        | 0.82%   |
| 6.5.6   | 2        | 0.54%   |
| 6.5.4   | 2        | 0.54%   |
| 6.5.3   | 2        | 0.54%   |
| 6.5.0   | 2        | 0.54%   |
| 6.4.6   | 2        | 0.54%   |
| 6.4.12  | 2        | 0.54%   |
| 6.4.11  | 2        | 0.54%   |
| 6.3.8   | 2        | 0.54%   |
| 6.3.5   | 2        | 0.54%   |
| 6.1.4   | 2        | 0.54%   |
| 6.0.10  | 2        | 0.54%   |
| 5.8.12  | 2        | 0.54%   |
| 5.19.5  | 2        | 0.54%   |
| 5.17.5  | 2        | 0.54%   |
| 5.16.13 | 2        | 0.54%   |
| 5.16.12 | 2        | 0.54%   |
| 5.13.4  | 2        | 0.54%   |
| 4.19.0  | 2        | 0.54%   |
| 6.6.8   | 1        | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 64       | 17.73%  |
| 5.15    | 29       | 8.03%   |
| 5.10    | 24       | 6.65%   |
| 5.16    | 23       | 6.37%   |
| 5.11    | 20       | 5.54%   |
| 5.8     | 19       | 5.26%   |
| 6.1     | 17       | 4.71%   |
| 4.15    | 17       | 4.71%   |
| 5.13    | 16       | 4.43%   |
| 6.2     | 15       | 4.16%   |
| 5.3     | 14       | 3.88%   |
| 6.5     | 13       | 3.6%    |
| 4.18    | 13       | 3.6%    |
| 5.0     | 10       | 2.77%   |
| 6.0     | 9        | 2.49%   |
| 6.4     | 8        | 2.22%   |
| 5.19    | 8        | 2.22%   |
| 6.3     | 6        | 1.66%   |
| 5.14    | 5        | 1.39%   |
| 5.17    | 4        | 1.11%   |
| 5.12    | 4        | 1.11%   |
| 5.9     | 3        | 0.83%   |
| 5.7     | 3        | 0.83%   |
| 5.6     | 3        | 0.83%   |
| 5.18    | 3        | 0.83%   |
| 4.9     | 3        | 0.83%   |
| 4.19    | 2        | 0.55%   |
| 6.6     | 1        | 0.28%   |
| 5.2     | 1        | 0.28%   |
| 5.1     | 1        | 0.28%   |
| 4.4     | 1        | 0.28%   |
| 4.3     | 1        | 0.28%   |
| 4.17    | 1        | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 318      | 97.25%  |
| i686   | 9        | 2.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 136      | 40.48%  |
| KDE5              | 72       | 21.43%  |
| Unknown           | 42       | 12.5%   |
| XFCE              | 22       | 6.55%   |
| X-Cinnamon        | 16       | 4.76%   |
| Pantheon          | 10       | 2.98%   |
| MATE              | 5        | 1.49%   |
| Unity             | 4        | 1.19%   |
| LXQt              | 4        | 1.19%   |
| KDE               | 3        | 0.89%   |
| Deepin            | 3        | 0.89%   |
| Cinnamon          | 3        | 0.89%   |
| Yaru:ubuntu:GNOME | 2        | 0.6%    |
| lightdm-xsession  | 2        | 0.6%    |
| KDE4              | 2        | 0.6%    |
| i3                | 2        | 0.6%    |
| Peux Gnome        | 1        | 0.3%    |
| LXDE              | 1        | 0.3%    |
| ICEWM             | 1        | 0.3%    |
| GNOME Flashback   | 1        | 0.3%    |
| DWM               | 1        | 0.3%    |
| Cutefish          | 1        | 0.3%    |
| Budgie            | 1        | 0.3%    |
| Bspwm             | 1        | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 250      | 74.63%  |
| Wayland | 50       | 14.93%  |
| Unknown | 29       | 8.66%   |
| Tty     | 6        | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 175      | 51.93%  |
| SDDM    | 69       | 20.47%  |
| GDM     | 33       | 9.79%   |
| LightDM | 28       | 8.31%   |
| GDM3    | 24       | 7.12%   |
| TDM     | 6        | 1.78%   |
| KDM     | 2        | 0.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 261      | 78.61%  |
| Unknown | 34       | 10.24%  |
| id_ID   | 24       | 7.23%   |
| C       | 4        | 1.2%    |
| en_GB   | 3        | 0.9%    |
| it_IT   | 1        | 0.3%    |
| en_IN   | 1        | 0.3%    |
| en_AU   | 1        | 0.3%    |
| en_AG   | 1        | 0.3%    |
| de_DE   | 1        | 0.3%    |
| Default | 1        | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 213      | 63.96%  |
| EFI  | 120      | 36.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 251      | 75.6%   |
| Overlay | 34       | 10.24%  |
| Btrfs   | 23       | 6.93%   |
| Unknown | 11       | 3.31%   |
| Xfs     | 7        | 2.11%   |
| Tmpfs   | 5        | 1.51%   |
| Zfs     | 1        | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 179      | 53.59%  |
| GPT     | 101      | 30.24%  |
| MBR     | 54       | 16.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 283      | 85.24%  |
| Yes       | 49       | 14.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 56.89%  |
| Yes       | 144      | 43.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte Technology                  | 49       | 14.98%  |
| ASUSTek Computer                     | 48       | 14.68%  |
| MSI                                  | 43       | 13.15%  |
| ASRock                               | 40       | 12.23%  |
| Dell                                 | 22       | 6.73%   |
| Intel                                | 18       | 5.5%    |
| ECS                                  | 18       | 5.5%    |
| Biostar                              | 18       | 5.5%    |
| Lenovo                               | 17       | 5.2%    |
| Hewlett-Packard                      | 15       | 4.59%   |
| Acer                                 | 8        | 2.45%   |
| Unknown                              | 5        | 1.53%   |
| Foxconn                              | 3        | 0.92%   |
| AZW                                  | 3        | 0.92%   |
| Pegatron                             | 2        | 0.61%   |
| LORD ELECTRONICS                     | 2        | 0.61%   |
| ZYREX COMPUTER SYSTEMS               | 1        | 0.31%   |
| ZOTAC                                | 1        | 0.31%   |
| Wearnes                              | 1        | 0.31%   |
| SPECTRUM UTAMA                       | 1        | 0.31%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.31%   |
| Samsung Electronics                  | 1        | 0.31%   |
| Quanta                               | 1        | 0.31%   |
| OEM                                  | 1        | 0.31%   |
| Nvidia                               | 1        | 0.31%   |
| NEC Computers                        | 1        | 0.31%   |
| Minix                                | 1        | 0.31%   |
| Koloe                                | 1        | 0.31%   |
| Jetway                               | 1        | 0.31%   |
| Inventec                             | 1        | 0.31%   |
| GALAX                                | 1        | 0.31%   |
| Colorful Technology                  | 1        | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 8        | 2.45%   |
| Intel H61                                         | 7        | 2.14%   |
| ASUS All Series                                   | 5        | 1.53%   |
| Gigabyte H61M-DS2                                 | 4        | 1.22%   |
| Dell OptiPlex 7010                                | 4        | 1.22%   |
| MSI MS-7A37                                       | 3        | 0.92%   |
| ECS H61H2-MV                                      | 3        | 0.92%   |
| ASUS P5KPL-AM SE                                  | 3        | 0.92%   |
| ASRock FM2A68M-DG3+                               | 3        | 0.92%   |
| ASRock B450 Pro4                                  | 3        | 0.92%   |
| ASRock A88M-G                                     | 3        | 0.92%   |
| ASRock A320M-HDV R4.0                             | 3        | 0.92%   |
| MSI MS-7D43                                       | 2        | 0.61%   |
| MSI MS-7B22                                       | 2        | 0.61%   |
| MSI MS-7823                                       | 2        | 0.61%   |
| MSI MS-7817                                       | 2        | 0.61%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 2        | 0.61%   |
| HP ProDesk 400 G2 MT (TPM DP)                     | 2        | 0.61%   |
| Gigabyte GA-78LMT-USB3 6.0                        | 2        | 0.61%   |
| Gigabyte G31M-ES2L                                | 2        | 0.61%   |
| Gigabyte B460MDS3H                                | 2        | 0.61%   |
| Gigabyte A520I AC                                 | 2        | 0.61%   |
| Foxconn Pro 3330 MT                               | 2        | 0.61%   |
| ECS H81H3-MV                                      | 2        | 0.61%   |
| ECS G41T-M12                                      | 2        | 0.61%   |
| ECS A55F2-M4                                      | 2        | 0.61%   |
| Dell OptiPlex 790                                 | 2        | 0.61%   |
| Dell OptiPlex 3020M                               | 2        | 0.61%   |
| Biostar H310MHC                                   | 2        | 0.61%   |
| AZW U59                                           | 2        | 0.61%   |
| ASUS P5GC-MX/1333                                 | 2        | 0.61%   |
| ASUS H61M-K                                       | 2        | 0.61%   |
| ASUS H110M-E/M.2                                  | 2        | 0.61%   |
| ASRock G41M-VS3                                   | 2        | 0.61%   |
| ASRock B560M Pro4                                 | 2        | 0.61%   |
| ASRock B550M Pro4                                 | 2        | 0.61%   |
| ASRock AB350 Pro4                                 | 2        | 0.61%   |
| ASRock A320M-HDV                                  | 2        | 0.61%   |
| Acer Aspire M3970                                 | 2        | 0.61%   |
| ZYREX COMPUTER SYSTEMS TACTICAL                   | 1        | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 14       | 4.28%   |
| Lenovo ThinkCentre     | 10       | 3.06%   |
| ASUS PRIME             | 8        | 2.45%   |
| Unknown                | 8        | 2.45%   |
| Intel H61              | 7        | 2.14%   |
| ASUS ROG               | 6        | 1.83%   |
| Gigabyte H61M-DS2      | 5        | 1.53%   |
| ASUS P5KPL-AM          | 5        | 1.53%   |
| ASUS All               | 5        | 1.53%   |
| ASRock A320M-HDV       | 5        | 1.53%   |
| Acer Veriton           | 5        | 1.53%   |
| HP ProDesk             | 4        | 1.22%   |
| MSI MS-7A37            | 3        | 0.92%   |
| HP Compaq              | 3        | 0.92%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.92%   |
| Gigabyte B550M         | 3        | 0.92%   |
| ECS H61H2-MV           | 3        | 0.92%   |
| Dell Inspiron          | 3        | 0.92%   |
| ASRock FM2A68M-DG3+    | 3        | 0.92%   |
| ASRock B450            | 3        | 0.92%   |
| ASRock A88M-G          | 3        | 0.92%   |
| Acer Aspire            | 3        | 0.92%   |
| MSI MS-7D43            | 2        | 0.61%   |
| MSI MS-7B22            | 2        | 0.61%   |
| MSI MS-7823            | 2        | 0.61%   |
| MSI MS-7817            | 2        | 0.61%   |
| MSI Compaq             | 2        | 0.61%   |
| LORD ELECTRONICS LORD  | 2        | 0.61%   |
| Lenovo IdeaCentre      | 2        | 0.61%   |
| Gigabyte G31M-ES2L     | 2        | 0.61%   |
| Gigabyte B560M         | 2        | 0.61%   |
| Gigabyte B460MDS3H     | 2        | 0.61%   |
| Gigabyte B365M         | 2        | 0.61%   |
| Gigabyte A520I         | 2        | 0.61%   |
| Foxconn Pro            | 2        | 0.61%   |
| ECS H81H3-MV           | 2        | 0.61%   |
| ECS G41T-M12           | 2        | 0.61%   |
| ECS A55F2-M4           | 2        | 0.61%   |
| Dell Vostro            | 2        | 0.61%   |
| Dell Precision         | 2        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 35       | 10.7%   |
| 2011 | 30       | 9.17%   |
| 2012 | 28       | 8.56%   |
| 2010 | 27       | 8.26%   |
| 2014 | 26       | 7.95%   |
| 2017 | 25       | 7.65%   |
| 2020 | 24       | 7.34%   |
| 2018 | 22       | 6.73%   |
| 2019 | 19       | 5.81%   |
| 2009 | 18       | 5.5%    |
| 2021 | 17       | 5.2%    |
| 2016 | 15       | 4.59%   |
| 2008 | 15       | 4.59%   |
| 2015 | 13       | 3.98%   |
| 2007 | 7        | 2.14%   |
| 2022 | 3        | 0.92%   |
| 2023 | 2        | 0.61%   |
| 2006 | 1        | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 327      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 319      | 97.55%  |
| Enabled  | 8        | 2.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 327      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 86       | 25.9%   |
| 8.01-16.0   | 72       | 21.69%  |
| 4.01-8.0    | 65       | 19.58%  |
| 16.01-24.0  | 59       | 17.77%  |
| 32.01-64.0  | 26       | 7.83%   |
| 1.01-2.0    | 12       | 3.61%   |
| 24.01-32.0  | 4        | 1.2%    |
| 2.01-3.0    | 4        | 1.2%    |
| 64.01-256.0 | 4        | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 143      | 38.75%  |
| 2.01-3.0   | 95       | 25.75%  |
| 4.01-8.0   | 45       | 12.2%   |
| 3.01-4.0   | 42       | 11.38%  |
| 0.51-1.0   | 29       | 7.86%   |
| 8.01-16.0  | 8        | 2.17%   |
| 16.01-24.0 | 4        | 1.08%   |
| 0.01-0.5   | 3        | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 166      | 49.11%  |
| 2      | 108      | 31.95%  |
| 3      | 35       | 10.36%  |
| 4      | 17       | 5.03%   |
| 5      | 5        | 1.48%   |
| 6      | 2        | 0.59%   |
| 0      | 2        | 0.59%   |
| 15     | 1        | 0.3%    |
| 8      | 1        | 0.3%    |
| 7      | 1        | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 232      | 69.88%  |
| Yes       | 100      | 30.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 322      | 98.47%  |
| No        | 5        | 1.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 184      | 55.09%  |
| No        | 150      | 44.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 248      | 74.92%  |
| Yes       | 83       | 25.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Indonesia | 327      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Jakarta         | 94       | 26.48%  |
| Bandung         | 36       | 10.14%  |
| Surabaya        | 26       | 7.32%   |
| Yogyakarta      | 21       | 5.92%   |
| Medan           | 13       | 3.66%   |
| Tangerang       | 11       | 3.1%    |
| Semarang        | 11       | 3.1%    |
| Malang          | 9        | 2.54%   |
| South Tangerang | 7        | 1.97%   |
| Depok           | 7        | 1.97%   |
| Bogor           | 7        | 1.97%   |
| Bekasi          | 7        | 1.97%   |
| Banjarmasin     | 6        | 1.69%   |
| Palembang       | 5        | 1.41%   |
| Denpasar        | 4        | 1.13%   |
| Surakarta       | 3        | 0.85%   |
| Srengseng Sawah | 3        | 0.85%   |
| Sleman          | 3        | 0.85%   |
| Salatiga        | 3        | 0.85%   |
| Pasuruan        | 3        | 0.85%   |
| Gresik          | 3        | 0.85%   |
| Batam           | 3        | 0.85%   |
| Tasikmalaya     | 2        | 0.56%   |
| Tanjung Pinang  | 2        | 0.56%   |
| Sukabumi        | 2        | 0.56%   |
| Palu            | 2        | 0.56%   |
| Mataram         | 2        | 0.56%   |
| Makassar        | 2        | 0.56%   |
| Magelang        | 2        | 0.56%   |
| Bantabantaeng   | 2        | 0.56%   |
| Balikpapan      | 2        | 0.56%   |
| Wates           | 1        | 0.28%   |
| Ulee Gle        | 1        | 0.28%   |
| Tuban           | 1        | 0.28%   |
| Tinjomoyo       | 1        | 0.28%   |
| Tanjung Balai   | 1        | 0.28%   |
| South Jakarta   | 1        | 0.28%   |
| Sidoarjo        | 1        | 0.28%   |
| Serang          | 1        | 0.28%   |
| Selong          | 1        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 152      | 213    | 28.36%  |
| WDC                   | 99       | 151    | 18.47%  |
| Samsung Electronics   | 38       | 52     | 7.09%   |
| Toshiba               | 25       | 29     | 4.66%   |
| Hitachi               | 19       | 28     | 3.54%   |
| A-DATA Technology     | 17       | 21     | 3.17%   |
| SanDisk               | 14       | 17     | 2.61%   |
| V-GeN                 | 13       | 15     | 2.43%   |
| Kingston              | 11       | 13     | 2.05%   |
| China                 | 11       | 14     | 2.05%   |
| Unknown               | 9        | 14     | 1.68%   |
| MidasForce            | 9        | 11     | 1.68%   |
| Silicon Motion        | 8        | 9      | 1.49%   |
| Patriot               | 8        | 16     | 1.49%   |
| HGST                  | 8        | 12     | 1.49%   |
| Apacer                | 6        | 8      | 1.12%   |
| Unknown               | 6        | 6      | 1.12%   |
| XPG                   | 5        | 8      | 0.93%   |
| Transcend             | 5        | 8      | 0.93%   |
| ADATA Technology      | 5        | 11     | 0.93%   |
| Maxtor                | 4        | 4      | 0.75%   |
| Intel                 | 4        | 4      | 0.75%   |
| RX7                   | 3        | 4      | 0.56%   |
| Pioneer               | 3        | 3      | 0.56%   |
| OCZ                   | 3        | 3      | 0.56%   |
| JMicron Technology    | 3        | 3      | 0.56%   |
| Hewlett-Packard       | 3        | 3      | 0.56%   |
| Biostar               | 3        | 4      | 0.56%   |
| Team                  | 2        | 2      | 0.37%   |
| T-FORCE               | 2        | 2      | 0.37%   |
| SK hynix              | 2        | 2      | 0.37%   |
| Realtek Semiconductor | 2        | 2      | 0.37%   |
| Ramos Technology      | 2        | 2      | 0.37%   |
| PNY                   | 2        | 3      | 0.37%   |
| External              | 2        | 2      | 0.37%   |
| XSTAR                 | 1        | 1      | 0.19%   |
| Wellcomm              | 1        | 1      | 0.19%   |
| Verbatim              | 1        | 1      | 0.19%   |
| Varro                 | 1        | 1      | 0.19%   |
| TO Exter              | 1        | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST3500312CS 500GB                             | 22       | 3.62%   |
| Seagate ST500DM002-1BD142 500GB                       | 17       | 2.8%    |
| Seagate ST1000DM010-2EP102 1TB                        | 11       | 1.81%   |
| Seagate ST3250318AS 250GB                             | 9        | 1.48%   |
| Seagate ST1000DM003-1ER162 1TB                        | 8        | 1.32%   |
| A-DATA SU650 120GB SSD                                | 7        | 1.15%   |
| Seagate ST2000DM008-2FR102 2TB                        | 6        | 0.99%   |
| Unknown                                               | 6        | 0.99%   |
| Toshiba DT01ACA200 2TB                                | 5        | 0.82%   |
| Seagate ST3500413AS 500GB                             | 5        | 0.82%   |
| Kingston SA400S37120G 120GB SSD                       | 5        | 0.82%   |
| WDC WD5000AAKX-75U6AA0 500GB                          | 4        | 0.66%   |
| WDC WD10EZEX-00WN4A0 1TB                              | 4        | 0.66%   |
| Seagate ST380215AS 80GB                               | 4        | 0.66%   |
| Seagate ST3500418AS 500GB                             | 4        | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                        | 4        | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB                        | 4        | 0.66%   |
| SanDisk SSD PLUS 240GB                                | 4        | 0.66%   |
| Samsung SSD 860 EVO 250GB                             | 4        | 0.66%   |
| Samsung SSD 850 120GB                                 | 4        | 0.66%   |
| MidasForce SSD 120GB                                  | 4        | 0.66%   |
| Hitachi HTS543232A7A384 320GB                         | 4        | 0.66%   |
| HGST HTS545050A7E380 500GB                            | 4        | 0.66%   |
| Apacer AS340 240GB SSD                                | 4        | 0.66%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 3        | 0.49%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                      | 3        | 0.49%   |
| WDC WD1600AVVS-63L2B0 160GB                           | 3        | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3        | 0.49%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 3        | 0.49%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 3        | 0.49%   |
| Toshiba HDWD110 1TB                                   | 3        | 0.49%   |
| Toshiba DT01ACA050 500GB                              | 3        | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 3        | 0.49%   |
| Seagate ST9320325AS 320GB                             | 3        | 0.49%   |
| Seagate ST4000DM004-2CV104 4TB                        | 3        | 0.49%   |
| Seagate ST3160815AS 160GB                             | 3        | 0.49%   |
| Seagate ST3160318AS 160GB                             | 3        | 0.49%   |
| Seagate ST2000DM006-2DM164 2TB                        | 3        | 0.49%   |
| SanDisk SSD PLUS 120GB                                | 3        | 0.49%   |
| Samsung SSD 850 EVO 250GB                             | 3        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 151      | 211    | 47.78%  |
| WDC                 | 89       | 137    | 28.16%  |
| Toshiba             | 24       | 28     | 7.59%   |
| Hitachi             | 19       | 28     | 6.01%   |
| Samsung Electronics | 9        | 9      | 2.85%   |
| HGST                | 8        | 12     | 2.53%   |
| Maxtor              | 4        | 4      | 1.27%   |
| Unknown             | 2        | 2      | 0.63%   |
| Hewlett-Packard     | 2        | 2      | 0.63%   |
| External            | 2        | 2      | 0.63%   |
| Unknown             | 2        | 2      | 0.63%   |
| TO Exter            | 1        | 1      | 0.32%   |
| ExcelStor           | 1        | 1      | 0.32%   |
| CLOVER              | 1        | 1      | 0.32%   |
| Apple               | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 31     | 13.92%  |
| WDC                 | 12       | 12     | 7.59%   |
| SanDisk             | 11       | 13     | 6.96%   |
| China               | 11       | 14     | 6.96%   |
| A-DATA Technology   | 11       | 13     | 6.96%   |
| Kingston            | 10       | 12     | 6.33%   |
| MidasForce          | 9        | 11     | 5.7%    |
| V-GeN               | 8        | 10     | 5.06%   |
| Patriot             | 8        | 16     | 5.06%   |
| Apacer              | 6        | 8      | 3.8%    |
| Transcend           | 4        | 7      | 2.53%   |
| Unknown             | 3        | 4      | 1.9%    |
| Pioneer             | 3        | 3      | 1.9%    |
| OCZ                 | 3        | 3      | 1.9%    |
| Unknown             | 3        | 3      | 1.9%    |
| Team                | 2        | 2      | 1.27%   |
| T-FORCE             | 2        | 2      | 1.27%   |
| Seagate             | 2        | 2      | 1.27%   |
| RX7                 | 2        | 2      | 1.27%   |
| Ramos Technology    | 2        | 2      | 1.27%   |
| JMicron Technology  | 2        | 2      | 1.27%   |
| Intel               | 2        | 2      | 1.27%   |
| Biostar             | 2        | 3      | 1.27%   |
| XSTAR               | 1        | 1      | 0.63%   |
| Wellcomm            | 1        | 1      | 0.63%   |
| Verbatim            | 1        | 1      | 0.63%   |
| Varro               | 1        | 1      | 0.63%   |
| Toshiba             | 1        | 1      | 0.63%   |
| SPCC                | 1        | 1      | 0.63%   |
| SK hynix            | 1        | 1      | 0.63%   |
| PNY                 | 1        | 1      | 0.63%   |
| Memory              | 1        | 1      | 0.63%   |
| Kingmax             | 1        | 1      | 0.63%   |
| Hoodisk             | 1        | 4      | 0.63%   |
| Green House         | 1        | 1      | 0.63%   |
| Gigabyte Technology | 1        | 1      | 0.63%   |
| GALAX               | 1        | 1      | 0.63%   |
| Crucial             | 1        | 1      | 0.63%   |
| Colorful            | 1        | 1      | 0.63%   |
| AS340               | 1        | 1      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 251      | 441    | 56.03%  |
| SSD     | 135      | 198    | 30.13%  |
| NVMe    | 48       | 74     | 10.71%  |
| Unknown | 13       | 14     | 2.9%    |
| MMC     | 1        | 4      | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 307      | 633    | 82.31%  |
| NVMe | 48       | 73     | 12.87%  |
| SAS  | 17       | 21     | 4.56%   |
| MMC  | 1        | 4      | 0.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 249      | 431    | 63.2%   |
| 0.51-1.0   | 87       | 131    | 22.08%  |
| 1.01-2.0   | 39       | 53     | 9.9%    |
| 3.01-4.0   | 9        | 14     | 2.28%   |
| 2.01-3.0   | 7        | 7      | 1.78%   |
| 4.01-10.0  | 3        | 3      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 92       | 26.74%  |
| 251-500        | 71       | 20.64%  |
| 501-1000       | 37       | 10.76%  |
| 51-100         | 34       | 9.88%   |
| 1-20           | 32       | 9.3%    |
| 1001-2000      | 25       | 7.27%   |
| 21-50          | 22       | 6.4%    |
| More than 3000 | 15       | 4.36%   |
| 2001-3000      | 11       | 3.2%    |
| Unknown        | 5        | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 152      | 42.7%   |
| 21-50          | 55       | 15.45%  |
| 101-250        | 43       | 12.08%  |
| 51-100         | 34       | 9.55%   |
| 251-500        | 29       | 8.15%   |
| 501-1000       | 17       | 4.78%   |
| 1001-2000      | 11       | 3.09%   |
| More than 3000 | 8        | 2.25%   |
| Unknown        | 5        | 1.4%    |
| 2001-3000      | 2        | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                 | Desktops | Drives | Percent |
|-------------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 7        | 9      | 8.75%   |
| WDC WD800JD-08LSA0 80GB                               | 2        | 2      | 2.5%    |
| WDC WD3200AAKS-61L9A0 320GB                           | 2        | 3      | 2.5%    |
| WDC WD10EZEX-08M2NA0 1TB                              | 2        | 2      | 2.5%    |
| Seagate ST9250410AS 250GB                             | 2        | 2      | 2.5%    |
| Seagate ST1000DM003-1ER162 1TB                        | 2        | 2      | 2.5%    |
| HGST HTS545050A7E380 500GB                            | 2        | 3      | 2.5%    |
| WDC WD7500BPVT-55HXZT4 752GB                          | 1        | 1      | 1.25%   |
| WDC WD6400AADS-00M2B0 640GB                           | 1        | 1      | 1.25%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 1        | 1      | 1.25%   |
| WDC WD5000AZLX-00JKKA0 500GB                          | 1        | 1      | 1.25%   |
| WDC WD5000AAKX-08ERMA0 500GB                          | 1        | 1      | 1.25%   |
| WDC WD5000AAKX-083CA1 500GB                           | 1        | 1      | 1.25%   |
| WDC WD5000AAKX-001CA0 500GB                           | 1        | 1      | 1.25%   |
| WDC WD5000AADS-00M2B0 500GB                           | 1        | 1      | 1.25%   |
| WDC WD5000AACS-00G8B0 500GB                           | 1        | 1      | 1.25%   |
| WDC WD40EZRX-00SPEB0 4TB                              | 1        | 1      | 1.25%   |
| WDC WD3200JS-63PDB1 320GB                             | 1        | 1      | 1.25%   |
| WDC WD3200BPVT-00HXZT1 320GB                          | 1        | 1      | 1.25%   |
| WDC WD3200AVJS-63B6A0 320GB                           | 1        | 1      | 1.25%   |
| WDC WD3200AAJS-08B4A0 320GB                           | 1        | 1      | 1.25%   |
| WDC WD30EZRZ-00Z5HB0 3TB                              | 1        | 1      | 1.25%   |
| WDC WD30EFRX-68AX9N0 3TB                              | 1        | 1      | 1.25%   |
| WDC WD2503ABYX-01WERA1 256GB                          | 1        | 1      | 1.25%   |
| WDC WD2500AAJS-00L7A0 250GB                           | 1        | 1      | 1.25%   |
| WDC WD20EARX-008FB0 2TB                               | 1        | 1      | 1.25%   |
| WDC WD2000FYYZ-01UL1B1 2TB                            | 1        | 1      | 1.25%   |
| WDC WD1600AVVS-63L2B0 160GB                           | 1        | 1      | 1.25%   |
| WDC WD1600AAJS-00Z4A0 160GB                           | 1        | 1      | 1.25%   |
| Toshiba DT01ACA200 2TB                                | 1        | 1      | 1.25%   |
| T-FORCE SSD 512GB                                     | 1        | 1      | 1.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 1        | 1      | 1.25%   |
| Seagate ST9500420AS 500GB                             | 1        | 1      | 1.25%   |
| Seagate ST9500325AS 500GB                             | 1        | 1      | 1.25%   |
| Seagate ST9320325AS 320GB                             | 1        | 1      | 1.25%   |
| Seagate ST500LT0 12-9WS142 500GB                      | 1        | 1      | 1.25%   |
| Seagate ST3808110AS 80GB                              | 1        | 2      | 1.25%   |
| Seagate ST3500418AS 500GB                             | 1        | 1      | 1.25%   |
| Seagate ST3500413AS 500GB                             | 1        | 1      | 1.25%   |
| Seagate ST3500312CS 500GB                             | 1        | 1      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 25       | 29     | 33.78%  |
| WDC                 | 23       | 29     | 31.08%  |
| Hitachi             | 8        | 8      | 10.81%  |
| HGST                | 3        | 4      | 4.05%   |
| SanDisk             | 2        | 2      | 2.7%    |
| Samsung Electronics | 2        | 2      | 2.7%    |
| Kingston            | 2        | 2      | 2.7%    |
| Toshiba             | 1        | 1      | 1.35%   |
| T-FORCE             | 1        | 1      | 1.35%   |
| Silicon Motion      | 1        | 1      | 1.35%   |
| Maxtor              | 1        | 1      | 1.35%   |
| CLOVER              | 1        | 1      | 1.35%   |
| China               | 1        | 1      | 1.35%   |
| Apple               | 1        | 1      | 1.35%   |
| Apacer              | 1        | 2      | 1.35%   |
| Unknown             | 1        | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 25       | 29     | 37.88%  |
| WDC                 | 23       | 29     | 34.85%  |
| Hitachi             | 8        | 8      | 12.12%  |
| HGST                | 3        | 4      | 4.55%   |
| Samsung Electronics | 2        | 2      | 3.03%   |
| Toshiba             | 1        | 1      | 1.52%   |
| Maxtor              | 1        | 1      | 1.52%   |
| CLOVER              | 1        | 1      | 1.52%   |
| Apple               | 1        | 1      | 1.52%   |
| Unknown             | 1        | 1      | 1.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 55       | 77     | 88.71%  |
| SSD  | 6        | 8      | 9.68%   |
| NVMe | 1        | 1      | 1.61%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3250318AS 250GB | 2        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 201      | 405    | 52.76%  |
| Works    | 117      | 238    | 30.71%  |
| Malfunc  | 61       | 86     | 16.01%  |
| Failed   | 2        | 2      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 235      | 58.46%  |
| AMD                         | 89       | 22.14%  |
| ADATA Technology            | 15       | 3.73%   |
| Silicon Motion              | 12       | 2.99%   |
| ASMedia Technology          | 9        | 2.24%   |
| Samsung Electronics         | 8        | 1.99%   |
| JMicron Technology          | 7        | 1.74%   |
| SanDisk                     | 5        | 1.24%   |
| VIA Technologies            | 4        | 1%      |
| Realtek Semiconductor       | 3        | 0.75%   |
| Phison Electronics          | 3        | 0.75%   |
| Nvidia                      | 3        | 0.75%   |
| Marvell Technology Group    | 3        | 0.75%   |
| MAXIO Technology (Hangzhou) | 2        | 0.5%    |
| Kingston Technology Company | 2        | 0.5%    |
| SK hynix                    | 1        | 0.25%   |
| Biwin Storage Technology    | 1        | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42       | 7.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 41       | 7.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 32       | 5.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 31       | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 25       | 4.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22       | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 22       | 4.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 2.98%   |
| AMD 500 Series Chipset SATA Controller                                                  | 14       | 2.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 12       | 2.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 2.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 2.05%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 11       | 2.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 1.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 9        | 1.68%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 1.68%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 9        | 1.68%   |
| AMD FCH IDE Controller                                                                  | 9        | 1.68%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 1.49%   |
| AMD FCH SATA Controller D                                                               | 8        | 1.49%   |
| AMD 300 Series Chipset SATA Controller                                                  | 8        | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.3%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 0.93%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.93%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.93%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 0.74%   |
| JMicron JMB368 IDE controller                                                           | 4        | 0.74%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.74%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.56%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 3        | 0.56%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 234      | 56.52%  |
| IDE  | 120      | 28.99%  |
| NVMe | 48       | 11.59%  |
| RAID | 11       | 2.66%   |
| SAS  | 1        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 234      | 71.56%  |
| AMD    | 93       | 28.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 9        | 2.74%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 9        | 2.74%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 8        | 2.44%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 8        | 2.44%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 6        | 1.83%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 6        | 1.83%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 1.52%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 5        | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 1.52%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.22%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 1.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 1.22%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 1.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 1.22%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.22%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 4        | 1.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.22%   |
| AMD Phenom II X6 1055T Processor            | 4        | 1.22%   |
| AMD A6-6400K APU with Radeon HD Graphics    | 4        | 1.22%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 3        | 0.91%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 3        | 0.91%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 0.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.91%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.91%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.91%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3        | 0.91%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 0.91%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 3        | 0.91%   |
| Intel Atom CPU D525 @ 1.80GHz               | 3        | 0.91%   |
| Intel 12th Gen Core i5-12400                | 3        | 0.91%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 0.91%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.91%   |
| AMD Ryzen 5 1500X Quad-Core Processor       | 3        | 0.91%   |
| AMD FX-6300 Six-Core Processor              | 3        | 0.91%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.61%   |
| Intel Pentium D CPU 3.00GHz                 | 2        | 0.61%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.61%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 64       | 19.51%  |
| Intel Core i3           | 44       | 13.41%  |
| Intel Core i7           | 34       | 10.37%  |
| Intel Core 2 Duo        | 25       | 7.62%   |
| AMD Ryzen 5             | 24       | 7.32%   |
| Intel Pentium           | 14       | 4.27%   |
| Other                   | 11       | 3.35%   |
| AMD Ryzen 3             | 11       | 3.35%   |
| Intel Core 2 Quad       | 10       | 3.05%   |
| Intel Pentium Dual-Core | 9        | 2.74%   |
| Intel Xeon              | 8        | 2.44%   |
| AMD FX                  | 7        | 2.13%   |
| AMD Ryzen 7             | 6        | 1.83%   |
| AMD Athlon II X2        | 6        | 1.83%   |
| AMD A6                  | 6        | 1.83%   |
| Intel Atom              | 4        | 1.22%   |
| AMD Ryzen 9             | 4        | 1.22%   |
| AMD Phenom II X6        | 4        | 1.22%   |
| AMD Athlon X4           | 4        | 1.22%   |
| AMD A8                  | 4        | 1.22%   |
| Intel Celeron           | 3        | 0.91%   |
| AMD Phenom II X4        | 3        | 0.91%   |
| Intel Pentium Gold      | 2        | 0.61%   |
| Intel Pentium D         | 2        | 0.61%   |
| Intel Genuine           | 2        | 0.61%   |
| Intel Core 2            | 2        | 0.61%   |
| AMD Ryzen 3 PRO         | 2        | 0.61%   |
| AMD GX                  | 2        | 0.61%   |
| AMD Athlon 64 X2        | 2        | 0.61%   |
| AMD Athlon              | 2        | 0.61%   |
| AMD A10                 | 2        | 0.61%   |
| Intel Pentium Dual      | 1        | 0.3%    |
| Intel Core 2 Extreme    | 1        | 0.3%    |
| AMD PRO A8              | 1        | 0.3%    |
| AMD Phenom              | 1        | 0.3%    |
| AMD A4                  | 1        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 129      | 39.33%  |
| 4      | 126      | 38.41%  |
| 6      | 43       | 13.11%  |
| 8      | 15       | 4.57%   |
| 1      | 6        | 1.83%   |
| 12     | 4        | 1.22%   |
| 3      | 3        | 0.91%   |
| 16     | 1        | 0.3%    |
| 10     | 1        | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 326      | 99.69%  |
| 2      | 1        | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 167      | 51.07%  |
| 1      | 160      | 48.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 321      | 98.17%  |
| Unknown        | 5        | 1.53%   |
| 32-bit         | 1        | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 73       | 21.41%  |
| 0x306c3    | 33       | 9.68%   |
| 0x1067a    | 29       | 8.5%    |
| 0x306a9    | 27       | 7.92%   |
| 0x206a7    | 22       | 6.45%   |
| 0x906e9    | 11       | 3.23%   |
| 0x906ea    | 7        | 2.05%   |
| 0x08701021 | 6        | 1.76%   |
| 0x6fd      | 5        | 1.47%   |
| 0x6fb      | 5        | 1.47%   |
| 0x506e3    | 5        | 1.47%   |
| 0x20652    | 5        | 1.47%   |
| 0x06003106 | 5        | 1.47%   |
| 0x010000c8 | 5        | 1.47%   |
| 0xa0655    | 4        | 1.17%   |
| 0x0a50000c | 4        | 1.17%   |
| 0x08001137 | 4        | 1.17%   |
| 0x010000dc | 4        | 1.17%   |
| 0xa0671    | 3        | 0.88%   |
| 0xa0653    | 3        | 0.88%   |
| 0x906ed    | 3        | 0.88%   |
| 0x106e5    | 3        | 0.88%   |
| 0x106a5    | 3        | 0.88%   |
| 0x10676    | 3        | 0.88%   |
| 0x0a201016 | 3        | 0.88%   |
| 0x08108109 | 3        | 0.88%   |
| 0x08101016 | 3        | 0.88%   |
| 0x08101007 | 3        | 0.88%   |
| 0x0800820d | 3        | 0.88%   |
| 0x06001119 | 3        | 0.88%   |
| 0x010000c7 | 3        | 0.88%   |
| 0xf62      | 2        | 0.59%   |
| 0x906eb    | 2        | 0.59%   |
| 0x90675    | 2        | 0.59%   |
| 0x90672    | 2        | 0.59%   |
| 0x6f6      | 2        | 0.59%   |
| 0x206d7    | 2        | 0.59%   |
| 0x106ca    | 2        | 0.59%   |
| 0x0a50000d | 2        | 0.59%   |
| 0x0a20120a | 2        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 40       | 12.23%  |
| Penryn           | 36       | 11.01%  |
| SandyBridge      | 33       | 10.09%  |
| IvyBridge        | 33       | 10.09%  |
| KabyLake         | 28       | 8.56%   |
| Zen              | 16       | 4.89%   |
| K10              | 14       | 4.28%   |
| Core             | 13       | 3.98%   |
| Zen 3            | 12       | 3.67%   |
| Piledriver       | 11       | 3.36%   |
| Zen 2            | 10       | 3.06%   |
| Westmere         | 10       | 3.06%   |
| CometLake        | 9        | 2.75%   |
| Zen+             | 8        | 2.45%   |
| Skylake          | 7        | 2.14%   |
| Unknown          | 7        | 2.14%   |
| Steamroller      | 6        | 1.83%   |
| Nehalem          | 6        | 1.83%   |
| Excavator        | 4        | 1.22%   |
| Bonnell          | 4        | 1.22%   |
| Alderlake Hybrid | 4        | 1.22%   |
| Tremont          | 2        | 0.61%   |
| NetBurst         | 2        | 0.61%   |
| K8 Hammer        | 2        | 0.61%   |
| K10 Llano        | 2        | 0.61%   |
| Jaguar           | 2        | 0.61%   |
| Bulldozer        | 2        | 0.61%   |
| Puma             | 1        | 0.31%   |
| Icelake          | 1        | 0.31%   |
| Gracemont        | 1        | 0.31%   |
| Goldmont plus    | 1        | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 141      | 40.06%  |
| AMD                        | 115      | 32.67%  |
| Nvidia                     | 95       | 26.99%  |
| Matrox Electronics Systems | 1        | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 20       | 5.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 19       | 5.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 18       | 5.03%   |
| Nvidia GT218 [GeForce 210]                                                  | 13       | 3.63%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 13       | 3.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 3.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 10       | 2.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 10       | 2.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 8        | 2.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8        | 2.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 8        | 2.23%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 1.68%   |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 1.68%   |
| Intel HD Graphics 630                                                       | 6        | 1.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.4%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 1.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 1.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 1.4%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 5        | 1.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 1.4%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.12%   |
| Intel HD Graphics 530                                                       | 4        | 1.12%   |
| Intel Core Processor Integrated Graphics Controller                         | 4        | 1.12%   |
| AMD Richland [Radeon HD 8470D]                                              | 4        | 1.12%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.84%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.84%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.84%   |
| Nvidia GK208B [GeForce GT 720]                                              | 3        | 0.84%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 3        | 0.84%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 3        | 0.84%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 3        | 0.84%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 0.84%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 0.84%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 0.84%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.56%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.56%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Intel              | 124      | 37.35%  |
| 1 x AMD                | 105      | 31.63%  |
| 1 x Nvidia             | 88       | 26.51%  |
| Intel + AMD            | 5        | 1.51%   |
| 2 x AMD                | 3        | 0.9%    |
| Intel + Nvidia         | 3        | 0.9%    |
| AMD + Nvidia           | 2        | 0.6%    |
| 1 x Matrox             | 1        | 0.3%    |
| 1 x Intel + 4 x Nvidia | 1        | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 277      | 82.2%   |
| Proprietary | 48       | 14.24%  |
| Unknown     | 12       | 3.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 151      | 44.94%  |
| 1.01-2.0   | 50       | 14.88%  |
| 0.51-1.0   | 44       | 13.1%   |
| 0.01-0.5   | 38       | 11.31%  |
| 3.01-4.0   | 24       | 7.14%   |
| 7.01-8.0   | 12       | 3.57%   |
| 5.01-6.0   | 9        | 2.68%   |
| 8.01-16.0  | 7        | 2.08%   |
| 2.01-3.0   | 1        | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 71       | 23.83%  |
| Samsung Electronics  | 42       | 14.09%  |
| Dell                 | 38       | 12.75%  |
| Hewlett-Packard      | 19       | 6.38%   |
| AOC                  | 17       | 5.7%    |
| Lenovo               | 15       | 5.03%   |
| Acer                 | 13       | 4.36%   |
| Philips              | 12       | 4.03%   |
| ViewSonic            | 10       | 3.36%   |
| LG Electronics       | 7        | 2.35%   |
| BenQ                 | 6        | 2.01%   |
| Toshiba              | 5        | 1.68%   |
| Ancor Communications | 5        | 1.68%   |
| Mi                   | 4        | 1.34%   |
| Unknown              | 3        | 1.01%   |
| Sharp                | 2        | 0.67%   |
| RTK                  | 2        | 0.67%   |
| Panasonic            | 2        | 0.67%   |
| JRY                  | 2        | 0.67%   |
| GDH                  | 2        | 0.67%   |
| ASUSTek Computer     | 2        | 0.67%   |
| Xiaomi               | 1        | 0.34%   |
| Tech Concepts        | 1        | 0.34%   |
| SPC                  | 1        | 0.34%   |
| Sony                 | 1        | 0.34%   |
| S2-Tek               | 1        | 0.34%   |
| RGT                  | 1        | 0.34%   |
| Polaroid             | 1        | 0.34%   |
| PiLot                | 1        | 0.34%   |
| ODH                  | 1        | 0.34%   |
| MSI                  | 1        | 0.34%   |
| LRX                  | 1        | 0.34%   |
| ITE                  | 1        | 0.34%   |
| IPS                  | 1        | 0.34%   |
| HUYINIUDA            | 1        | 0.34%   |
| HRX                  | 1        | 0.34%   |
| HKC                  | 1        | 0.34%   |
| HannStar             | 1        | 0.34%   |
| Haier                | 1        | 0.34%   |
| Gateway              | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 11       | 3.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 9        | 2.88%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 7        | 2.24%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch              | 4        | 1.28%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                     | 4        | 1.28%   |
| Acer X163WL ACR022E 1366x768 344x193mm 15.5-inch                     | 4        | 1.28%   |
| Toshiba LCD-MONITOR LCD1560 1366x768 344x194mm 15.5-inch             | 3        | 0.96%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch    | 3        | 0.96%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 3        | 0.96%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3        | 0.96%   |
| Mi 27 NFGL XMIB004 1920x1080 598x336mm 27.0-inch                     | 3        | 0.96%   |
| Lenovo LEN E2054A LEN60DF 1440x900 419x262mm 19.5-inch               | 3        | 0.96%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch            | 3        | 0.96%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch              | 3        | 0.96%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 3        | 0.96%   |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                     | 3        | 0.96%   |
| Dell E1912H DELF03E 1366x768 410x230mm 18.5-inch                     | 3        | 0.96%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 3        | 0.96%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch            | 2        | 0.64%   |
| Unknown LCD Monitor AcerMFMAV 1440x900                               | 2        | 0.64%   |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                      | 2        | 0.64%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 2        | 0.64%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch  | 2        | 0.64%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2        | 0.64%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2        | 0.64%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch     | 2        | 0.64%   |
| Samsung Electronics LCD Monitor S19D300 1366x768                     | 2        | 0.64%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch    | 2        | 0.64%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                   | 2        | 0.64%   |
| LG Electronics LCD Monitor LG IPS WSXGA 1440x900                     | 2        | 0.64%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch            | 2        | 0.64%   |
| Hewlett-Packard LE1902x HWP2965 1366x768 410x230mm 18.5-inch         | 2        | 0.64%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 2        | 0.64%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                 | 2        | 0.64%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 2        | 0.64%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 2        | 0.64%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                | 2        | 0.64%   |
| Goldstar HD 16 GSM3E92 1366x768 344x194mm 15.5-inch                  | 2        | 0.64%   |
| Goldstar FHD GSM5B54 1920x1080 480x270mm 21.7-inch                   | 2        | 0.64%   |
| Goldstar E1642 GSM3E8C 1366x768 344x194mm 15.5-inch                  | 2        | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 107      | 36.52%  |
| 1366x768 (WXGA)    | 87       | 29.69%  |
| 3840x2160 (4K)     | 23       | 7.85%   |
| 1440x900 (WXGA+)   | 20       | 6.83%   |
| 1600x900 (HD+)     | 10       | 3.41%   |
| 2560x1440 (QHD)    | 8        | 2.73%   |
| 1360x768           | 8        | 2.73%   |
| 1280x1024 (SXGA)   | 8        | 2.73%   |
| 2560x1080          | 5        | 1.71%   |
| 3440x1440          | 4        | 1.37%   |
| 1024x768 (XGA)     | 3        | 1.02%   |
| 3840x1080          | 2        | 0.68%   |
| 1280x720 (HD)      | 2        | 0.68%   |
| Unknown            | 2        | 0.68%   |
| 640x480            | 1        | 0.34%   |
| 5760x2160          | 1        | 0.34%   |
| 1680x1050 (WSXGA+) | 1        | 0.34%   |
| 1280x960           | 1        | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 63       | 21.28%  |
| 21      | 51       | 17.23%  |
| 23      | 31       | 10.47%  |
| 15      | 25       | 8.45%   |
| 19      | 23       | 7.77%   |
| Unknown | 23       | 7.77%   |
| 27      | 19       | 6.42%   |
| 24      | 17       | 5.74%   |
| 34      | 7        | 2.36%   |
| 17      | 6        | 2.03%   |
| 31      | 4        | 1.35%   |
| 84      | 3        | 1.01%   |
| 40      | 3        | 1.01%   |
| 20      | 3        | 1.01%   |
| 48      | 2        | 0.68%   |
| 37      | 2        | 0.68%   |
| 16      | 2        | 0.68%   |
| 13      | 2        | 0.68%   |
| 72      | 1        | 0.34%   |
| 65      | 1        | 0.34%   |
| 60      | 1        | 0.34%   |
| 57      | 1        | 0.34%   |
| 52      | 1        | 0.34%   |
| 42      | 1        | 0.34%   |
| 39      | 1        | 0.34%   |
| 36      | 1        | 0.34%   |
| 35      | 1        | 0.34%   |
| 22      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 132      | 45.52%  |
| 501-600     | 63       | 21.72%  |
| 301-350     | 28       | 9.66%   |
| Unknown     | 23       | 7.93%   |
| 351-400     | 10       | 3.45%   |
| 701-800     | 9        | 3.1%    |
| 801-900     | 7        | 2.41%   |
| 601-700     | 6        | 2.07%   |
| 1001-1500   | 5        | 1.72%   |
| 1501-2000   | 4        | 1.38%   |
| 201-300     | 2        | 0.69%   |
| 901-1000    | 1        | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 224      | 78.32%  |
| Unknown | 22       | 7.69%   |
| 16/10   | 19       | 6.64%   |
| 5/4     | 8        | 2.8%    |
| 21/9    | 8        | 2.8%    |
| 4/3     | 4        | 1.4%    |
| 0.56    | 1        | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 81       | 27.46%  |
| 141-150        | 64       | 21.69%  |
| 151-200        | 41       | 13.9%   |
| 101-110        | 23       | 7.8%    |
| Unknown        | 23       | 7.8%    |
| 301-350        | 19       | 6.44%   |
| 351-500        | 12       | 4.07%   |
| More than 1000 | 10       | 3.39%   |
| 501-1000       | 8        | 2.71%   |
| 251-300        | 5        | 1.69%   |
| 131-140        | 3        | 1.02%   |
| 81-90          | 2        | 0.68%   |
| 111-120        | 2        | 0.68%   |
| 91-100         | 2        | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 175      | 59.93%  |
| 101-120 | 79       | 27.05%  |
| Unknown | 23       | 7.88%   |
| 1-50    | 11       | 3.77%   |
| 161-240 | 2        | 0.68%   |
| 121-160 | 2        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 282      | 84.68%  |
| 2     | 26       | 7.81%   |
| 0     | 25       | 7.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 250      | 49.41%  |
| Intel                           | 84       | 16.6%   |
| Ralink Technology               | 34       | 6.72%   |
| Qualcomm Atheros                | 34       | 6.72%   |
| TP-Link                         | 26       | 5.14%   |
| Xiaomi                          | 12       | 2.37%   |
| Broadcom                        | 11       | 2.17%   |
| Samsung Electronics             | 8        | 1.58%   |
| Qualcomm Atheros Communications | 8        | 1.58%   |
| Ralink                          | 6        | 1.19%   |
| D-Link System                   | 4        | 0.79%   |
| Qualcomm                        | 3        | 0.59%   |
| MediaTek                        | 3        | 0.59%   |
| D-Link                          | 3        | 0.59%   |
| ASIX Electronics                | 3        | 0.59%   |
| OPPO Electronics                | 2        | 0.4%    |
| Nvidia                          | 2        | 0.4%    |
| Marvell Technology Group        | 2        | 0.4%    |
| HMD Global                      | 2        | 0.4%    |
| AboCom Systems                  | 2        | 0.4%    |
| vivo                            | 1        | 0.2%    |
| VIA Technologies                | 1        | 0.2%    |
| QinHeng Electronics             | 1        | 0.2%    |
| ICS Advent                      | 1        | 0.2%    |
| Huawei Technologies             | 1        | 0.2%    |
| Broadcom Limited                | 1        | 0.2%    |
| ASUSTek Computer                | 1        | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 187      | 32.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37       | 6.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 27       | 4.67%   |
| Ralink MT7601U Wireless Adapter                                   | 23       | 3.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 16       | 2.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9        | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 9        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 1.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 8        | 1.38%   |
| Qualcomm Atheros AR9271 802.11n                                   | 8        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7        | 1.21%   |
| Intel Wi-Fi 6 AX200                                               | 7        | 1.21%   |
| Intel I211 Gigabit Network Connection                             | 7        | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6        | 1.04%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 5        | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 5        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5        | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4        | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 0.69%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3        | 0.52%   |
| TP-Link 802.11n NIC                                               | 3        | 0.52%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 3        | 0.52%   |
| Realtek 802.11ac NIC                                              | 3        | 0.52%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.52%   |
| Qualcomm FP3                                                      | 3        | 0.52%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3        | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.52%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.52%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 2        | 0.35%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2        | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 61       | 31.12%  |
| Intel                           | 35       | 17.86%  |
| Ralink Technology               | 34       | 17.35%  |
| TP-Link                         | 25       | 12.76%  |
| Qualcomm Atheros                | 13       | 6.63%   |
| Qualcomm Atheros Communications | 8        | 4.08%   |
| Ralink                          | 6        | 3.06%   |
| Broadcom                        | 4        | 2.04%   |
| D-Link                          | 3        | 1.53%   |
| D-Link System                   | 2        | 1.02%   |
| AboCom Systems                  | 2        | 1.02%   |
| MediaTek                        | 1        | 0.51%   |
| Broadcom Limited                | 1        | 0.51%   |
| ASUSTek Computer                | 1        | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter         | 27       | 13.57%  |
| Ralink MT7601U Wireless Adapter                             | 23       | 11.56%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                | 16       | 8.04%   |
| Realtek RTL8188EE Wireless Network Adapter                  | 9        | 4.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter       | 8        | 4.02%   |
| Qualcomm Atheros AR9271 802.11n                             | 8        | 4.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 7        | 3.52%   |
| Intel Wi-Fi 6 AX200                                         | 7        | 3.52%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter     | 5        | 2.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                       | 5        | 2.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]            | 5        | 2.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth             | 4        | 2.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                            | 4        | 2.01%   |
| TP-Link 802.11n NIC                                         | 3        | 1.51%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)   | 3        | 1.51%   |
| Realtek 802.11ac NIC                                        | 3        | 1.51%   |
| Ralink RT5370 Wireless Adapter                              | 3        | 1.51%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                       | 2        | 1.01%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                         | 2        | 1.01%   |
| Realtek RTL8191SEvB Wireless LAN Controller                 | 2        | 1.01%   |
| Ralink RT2501/RT2573 Wireless Adapter                       | 2        | 1.01%   |
| Ralink RT5392 PCIe Wireless Network Adapter                 | 2        | 1.01%   |
| Intel Wireless-AC 9260                                      | 2        | 1.01%   |
| Intel Wireless 7265                                         | 2        | 1.01%   |
| Intel Wireless 7260                                         | 2        | 1.01%   |
| Intel Wireless 3165                                         | 2        | 1.01%   |
| Intel Wireless 3160                                         | 2        | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                      | 2        | 1.01%   |
| D-Link WLAN controller                                      | 2        | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                               | 2        | 1.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                 | 1        | 0.5%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                       | 1        | 0.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller | 1        | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1        | 0.5%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter             | 1        | 0.5%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                  | 1        | 0.5%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter             | 1        | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                     | 1        | 0.5%    |
| Realtek RTL8187 Wireless Adapter                            | 1        | 0.5%    |
| Ralink RT2070 Wireless Adapter                              | 1        | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 238      | 64.5%   |
| Intel                    | 60       | 16.26%  |
| Qualcomm Atheros         | 22       | 5.96%   |
| Xiaomi                   | 12       | 3.25%   |
| Broadcom                 | 7        | 1.9%    |
| Samsung Electronics      | 6        | 1.63%   |
| Qualcomm                 | 3        | 0.81%   |
| ASIX Electronics         | 3        | 0.81%   |
| OPPO Electronics         | 2        | 0.54%   |
| Nvidia                   | 2        | 0.54%   |
| MediaTek                 | 2        | 0.54%   |
| Marvell Technology Group | 2        | 0.54%   |
| HMD Global               | 2        | 0.54%   |
| D-Link System            | 2        | 0.54%   |
| vivo                     | 1        | 0.27%   |
| VIA Technologies         | 1        | 0.27%   |
| TP-Link                  | 1        | 0.27%   |
| QinHeng Electronics      | 1        | 0.27%   |
| ICS Advent               | 1        | 0.27%   |
| Huawei Technologies      | 1        | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 187      | 49.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37       | 9.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 2.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9        | 2.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 2.39%   |
| Intel I211 Gigabit Network Connection                             | 7        | 1.86%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6        | 1.59%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 4        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3        | 0.8%    |
| Qualcomm FP3                                                      | 3        | 0.8%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3        | 0.8%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.8%    |
| Intel Ethernet Controller I225-V                                  | 3        | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.53%   |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 2        | 0.53%   |
| MediaTek M40Air_EEA                                               | 2        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.53%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.53%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.53%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.53%   |
| HMD Global Nokia7.2                                               | 2        | 0.53%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.53%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 2        | 0.53%   |
| vivo 1820                                                         | 1        | 0.27%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 322      | 63.39%  |
| WiFi     | 184      | 36.22%  |
| Modem    | 2        | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 202      | 60.84%  |
| WiFi     | 129      | 38.86%  |
| Modem    | 1        | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 237      | 71.6%   |
| 2     | 81       | 24.47%  |
| 3     | 10       | 3.02%   |
| 0     | 2        | 0.6%    |
| 4     | 1        | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 314      | 95.44%  |
| Yes  | 15       | 4.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 37       | 43.02%  |
| Intel                           | 34       | 39.53%  |
| Realtek Semiconductor           | 6        | 6.98%   |
| Qualcomm Atheros Communications | 4        | 4.65%   |
| Broadcom                        | 3        | 3.49%   |
| MediaTek                        | 1        | 1.16%   |
| IMC Networks                    | 1        | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 37       | 43.02%  |
| Intel Bluetooth wireless interface                  | 12       | 13.95%  |
| Intel AX200 Bluetooth                               | 7        | 8.14%   |
| Realtek Bluetooth Radio                             | 5        | 5.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 5.81%   |
| Intel Bluetooth Device                              | 5        | 5.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2.33%   |
| Intel AX210 Bluetooth                               | 2        | 2.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2        | 2.33%   |
| Realtek RTL8723B Bluetooth                          | 1        | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 1.16%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 1.16%   |
| Qualcomm Atheros Bluetooth                          | 1        | 1.16%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 1.16%   |
| MediaTek Wireless_Device                            | 1        | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.16%   |
| IMC Networks Bluetooth Radio                        | 1        | 1.16%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1        | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 232      | 47.35%  |
| AMD                                  | 132      | 26.94%  |
| Nvidia                               | 87       | 17.76%  |
| C-Media Electronics                  | 9        | 1.84%   |
| Generalplus Technology               | 5        | 1.02%   |
| Creative Labs                        | 4        | 0.82%   |
| Texas Instruments                    | 3        | 0.61%   |
| Razer USA                            | 2        | 0.41%   |
| KTMicro                              | 2        | 0.41%   |
| JMTek                                | 2        | 0.41%   |
| Weltrend Semiconductor               | 1        | 0.2%    |
| Thesycon Systemsoftware & Consulting | 1        | 0.2%    |
| STMicroelectronics                   | 1        | 0.2%    |
| SteelSeries ApS                      | 1        | 0.2%    |
| Sony                                 | 1        | 0.2%    |
| Solid State Logic                    | 1        | 0.2%    |
| Samson Technologies                  | 1        | 0.2%    |
| Hewlett-Packard                      | 1        | 0.2%    |
| Creative Technology                  | 1        | 0.2%    |
| BR23                                 | 1        | 0.2%    |
| Barco Display Systems                | 1        | 0.2%    |
| ASUSTek Computer                     | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 48       | 8.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 40       | 6.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 34       | 5.85%   |
| AMD Family 17h/19h HD Audio Controller                                     | 26       | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 24       | 4.13%   |
| AMD FCH Azalia Controller                                                  | 21       | 3.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20       | 3.44%   |
| Nvidia High Definition Audio Controller                                    | 17       | 2.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 2.58%   |
| AMD Starship/Matisse HD Audio Controller                                   | 14       | 2.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12       | 2.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12       | 2.07%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 2.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12       | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12       | 2.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 1.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11       | 1.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 1.72%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 9        | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 1.55%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 9        | 1.55%   |
| Nvidia GF108 High Definition Audio Controller                              | 8        | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 1.38%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8        | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 1.03%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 1.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 1.03%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 0.86%   |
| Generalplus Technology USB Audio Device                                    | 5        | 0.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 5        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 5        | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 0.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 0.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 0.69%   |
| AMD Trinity HDMI Audio Controller                                          | 4        | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 34       | 17.26%  |
| Kingston            | 30       | 15.23%  |
| SK hynix            | 22       | 11.17%  |
| Samsung Electronics | 21       | 10.66%  |
| Corsair             | 19       | 9.64%   |
| Team                | 16       | 8.12%   |
| Micron Technology   | 9        | 4.57%   |
| G.Skill             | 8        | 4.06%   |
| Unknown             | 8        | 4.06%   |
| V-GeN               | 7        | 3.55%   |
| Elpida              | 4        | 2.03%   |
| A-DATA Technology   | 3        | 1.52%   |
| Unknown (0x0DD5)    | 2        | 1.02%   |
| Ramaxel Technology  | 2        | 1.02%   |
| Patriot             | 2        | 1.02%   |
| Crucial             | 2        | 1.02%   |
| Visipro             | 1        | 0.51%   |
| Unknown (8AA1)      | 1        | 0.51%   |
| Transcend           | 1        | 0.51%   |
| Super Talent        | 1        | 0.51%   |
| Nanya Technology    | 1        | 0.51%   |
| Kingmax             | 1        | 0.51%   |
| Essencore           | 1        | 0.51%   |
| 04?@                | 1        | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown                                                     | 8        | 3.76%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3800MT/s         | 5        | 2.35%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 3        | 1.41%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 3        | 1.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 3        | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 3        | 1.41%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s         | 3        | 1.41%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 3        | 1.41%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s         | 3        | 1.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 2        | 0.94%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 2        | 0.94%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 2        | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 2        | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                    | 2        | 0.94%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                        | 2        | 0.94%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                    | 2        | 0.94%   |
| Unknown (0x0DD5) RAM AZ8G4SW266-8G 8GB SODIMM DDR4 2667MT/s | 2        | 0.94%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s          | 2        | 0.94%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 2        | 0.94%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s          | 2        | 0.94%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s         | 2        | 0.94%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s        | 2        | 0.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2        | 0.94%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s         | 2        | 0.94%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s         | 2        | 0.94%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s         | 2        | 0.94%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s         | 2        | 0.94%   |
| Micron RAM Module 4GB DIMM DDR3 1333MT/s                    | 2        | 0.94%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s        | 2        | 0.94%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s         | 2        | 0.94%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s       | 2        | 0.94%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s       | 2        | 0.94%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 2        | 0.94%   |
| Visipro RAM T4G86U1-H9H 4096MB DIMM DDR3 1067MT/s           | 1        | 0.47%   |
| V-GeN RAM D4S16GL32A8TS 16384MB DIMM DDR4 3200MT/s          | 1        | 0.47%   |
| V-GeN RAM D4H8GL32A8TXV 8GB DIMM DDR4 2400MT/s              | 1        | 0.47%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s               | 1        | 0.47%   |
| V-GeN RAM D4H8GL24A8 8GB DIMM DDR4 2400MT/s                 | 1        | 0.47%   |
| V-GeN RAM D3S4GL16B8 4GB DIMM DDR3 1333MT/s                 | 1        | 0.47%   |
| V-GeN RAM D3S4GL16A8 4GB DIMM DDR3                          | 1        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 68       | 40.24%  |
| DDR4    | 58       | 34.32%  |
| DDR2    | 14       | 8.28%   |
| SDRAM   | 12       | 7.1%    |
| Unknown | 12       | 7.1%    |
| DDR5    | 3        | 1.78%   |
| DDR     | 2        | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 147      | 90.74%  |
| SODIMM | 15       | 9.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 56       | 30.27%  |
| 8192  | 47       | 25.41%  |
| 2048  | 45       | 24.32%  |
| 16384 | 15       | 8.11%   |
| 32768 | 14       | 7.57%   |
| 1024  | 7        | 3.78%   |
| 512   | 1        | 0.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 37       | 19.58%  |
| 1333    | 33       | 17.46%  |
| 3200    | 13       | 6.88%   |
| 800     | 10       | 5.29%   |
| 2667    | 9        | 4.76%   |
| 2400    | 9        | 4.76%   |
| 1800    | 8        | 4.23%   |
| Unknown | 7        | 3.7%    |
| 3600    | 6        | 3.17%   |
| 667     | 6        | 3.17%   |
| 3800    | 5        | 2.65%   |
| 3733    | 5        | 2.65%   |
| 3400    | 3        | 1.59%   |
| 2133    | 3        | 1.59%   |
| 1867    | 3        | 1.59%   |
| 1067    | 3        | 1.59%   |
| 5200    | 2        | 1.06%   |
| 3151    | 2        | 1.06%   |
| 2666    | 2        | 1.06%   |
| 1866    | 2        | 1.06%   |
| 1066    | 2        | 1.06%   |
| 333     | 2        | 1.06%   |
| 50410   | 1        | 0.53%   |
| 5600    | 1        | 0.53%   |
| 4040    | 1        | 0.53%   |
| 3866    | 1        | 0.53%   |
| 3666    | 1        | 0.53%   |
| 3534    | 1        | 0.53%   |
| 3533    | 1        | 0.53%   |
| 3466    | 1        | 0.53%   |
| 3000    | 1        | 0.53%   |
| 2934    | 1        | 0.53%   |
| 2733    | 1        | 0.53%   |
| 2465    | 1        | 0.53%   |
| 2200    | 1        | 0.53%   |
| 2000    | 1        | 0.53%   |
| 1648    | 1        | 0.53%   |
| 533     | 1        | 0.53%   |
| 400     | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 15       | 68.18%  |
| Hewlett-Packard    | 4        | 18.18%  |
| STMicroelectronics | 1        | 4.55%   |
| Fuji Xerox         | 1        | 4.55%   |
| Brother Industries | 1        | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson L120 Series          | 5        | 22.73%  |
| Seiko Epson L360 Series          | 3        | 13.64%  |
| Seiko Epson L3110 Series         | 2        | 9.09%   |
| Seiko Epson L300 Series          | 2        | 9.09%   |
| STMicroelectronics JRSVC Printer | 1        | 4.55%   |
| Seiko Epson L3210 Series         | 1        | 4.55%   |
| Seiko Epson L310 Series          | 1        | 4.55%   |
| Seiko Epson L1300 Series         | 1        | 4.55%   |
| HP LaserJet P1102                | 1        | 4.55%   |
| HP LaserJet P1006                | 1        | 4.55%   |
| HP DeskJet 5820 series           | 1        | 4.55%   |
| HP DeskJet 2130 series           | 1        | 4.55%   |
| Fuji Xerox DocuPrint M205 b      | 1        | 4.55%   |
| Brother DCP-T310                 | 1        | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia                      | 5        | 10.87%  |
| Logitech                      | 5        | 10.87%  |
| Chicony Electronics           | 5        | 10.87%  |
| ANYKA                         | 4        | 8.7%    |
| IMC Networks                  | 3        | 6.52%   |
| Generalplus Technology        | 3        | 6.52%   |
| Z-Star Microelectronics       | 2        | 4.35%   |
| Jieli Technology              | 2        | 4.35%   |
| GEMBIRD                       | 2        | 4.35%   |
| Cubeternet                    | 2        | 4.35%   |
| Apple                         | 2        | 4.35%   |
| WCM_USB                       | 1        | 2.17%   |
| Sunplus Innovation Technology | 1        | 2.17%   |
| Sonix Technology              | 1        | 2.17%   |
| SN0002                        | 1        | 2.17%   |
| Realtek Semiconductor         | 1        | 2.17%   |
| Razer USA                     | 1        | 2.17%   |
| MacroSilicon                  | 1        | 2.17%   |
| KYE Systems (Mouse Systems)   | 1        | 2.17%   |
| Huawei Technologies           | 1        | 2.17%   |
| Arkmicro Technologies         | 1        | 2.17%   |
| A4Tech                        | 1        | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ANYKA FHD Camera                                  | 4        | 8.7%    |
| Microdia Integrated Camera                        | 3        | 6.52%   |
| Jieli USB PHY 2.0                                 | 2        | 4.35%   |
| IMC Networks Integrated Camera                    | 2        | 4.35%   |
| Generalplus GENERAL WEBCAM                        | 2        | 4.35%   |
| Chicony HP High Definition 1MP Webcam             | 2        | 4.35%   |
| Apple iPhone 5/5C/5S/6/SE                         | 2        | 4.35%   |
| Z-Star USB 2.0 Web Camera                         | 1        | 2.17%   |
| Z-Star Sirius USB2.0 Camera                       | 1        | 2.17%   |
| WCM_USB WEB CAM                                   | 1        | 2.17%   |
| Sunplus WEBCAM ESSENTIELB W1                      | 1        | 2.17%   |
| Sonix GENERAL WEBCAM                              | 1        | 2.17%   |
| SN0002 1080P Web Camera                           | 1        | 2.17%   |
| Realtek NexiGo N960E FHD Webcam                   | 1        | 2.17%   |
| Razer USA Razer Kiyo Pro                          | 1        | 2.17%   |
| Microdia USB camera                               | 1        | 2.17%   |
| Microdia Integrated_Webcam_HD                     | 1        | 2.17%   |
| MacroSilicon USB3. 0 capture                      | 1        | 2.17%   |
| Logitech Webcam C270                              | 1        | 2.17%   |
| Logitech Webcam C170                              | 1        | 2.17%   |
| Logitech Webcam C110                              | 1        | 2.17%   |
| Logitech Logitech Webcam C160                     | 1        | 2.17%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 2.17%   |
| KYE Systems (Mouse Systems) Genius Webcam         | 1        | 2.17%   |
| IMC Networks USB2.0 UVC HD Webcam                 | 1        | 2.17%   |
| Huawei HiCamera                                   | 1        | 2.17%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 1        | 2.17%   |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 2.17%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 2.17%   |
| Cubeternet WebCam                                 | 1        | 2.17%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 1        | 2.17%   |
| Chicony USB 2.0 Camera                            | 1        | 2.17%   |
| Chicony Integrated Camera                         | 1        | 2.17%   |
| Chicony HP Integrated Webcam                      | 1        | 2.17%   |
| Arkmicro USB2.0 PC CAMERA                         | 1        | 2.17%   |
| A4Tech REDRAGON Live Camera                       | 1        | 2.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| STMicroelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 296      | 89.16%  |
| 1     | 33       | 9.94%   |
| 2     | 2        | 0.6%    |
| 3     | 1        | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 14       | 35.9%   |
| Graphics card            | 13       | 33.33%  |
| Communication controller | 3        | 7.69%   |
| Unassigned class         | 2        | 5.13%   |
| Storage/ide              | 2        | 5.13%   |
| Wireless                 | 1        | 2.56%   |
| Net/ethernet             | 1        | 2.56%   |
| Multimedia controller    | 1        | 2.56%   |
| Fingerprint reader       | 1        | 2.56%   |
| Camera                   | 1        | 2.56%   |

