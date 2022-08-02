EndeavourOS - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/EndeavourOS/Desktop/README.md) and [notebooks](/Dist/EndeavourOS/Notebook/README.md).

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

Total: 761

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Microsoft     | Surface Laptop Go           | Tablet      | [6b7e94ffa5](https://linux-hardware.org/?probe=6b7e94ffa5) | Aug 01, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ec13dcb17f](https://linux-hardware.org/?probe=ec13dcb17f) | Aug 01, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [0bcc9863e3](https://linux-hardware.org/?probe=0bcc9863e3) | Jul 31, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f56b1796ad](https://linux-hardware.org/?probe=f56b1796ad) | Jul 30, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b6dea628df](https://linux-hardware.org/?probe=b6dea628df) | Jul 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1683326024](https://linux-hardware.org/?probe=1683326024) | Jul 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [60b06048f3](https://linux-hardware.org/?probe=60b06048f3) | Jul 24, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [06dd902359](https://linux-hardware.org/?probe=06dd902359) | Jul 23, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [db6770b5f7](https://linux-hardware.org/?probe=db6770b5f7) | Jul 22, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [00f490c5d0](https://linux-hardware.org/?probe=00f490c5d0) | Jul 22, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b3f65d7c35](https://linux-hardware.org/?probe=b3f65d7c35) | Jul 21, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [d7e2758b93](https://linux-hardware.org/?probe=d7e2758b93) | Jul 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| Samsung       | DeskTop System              | Desktop     | [d0d33ec330](https://linux-hardware.org/?probe=d0d33ec330) | Jul 19, 2022 |
| Samsung       | DeskTop System              | Desktop     | [3af9bcc9cb](https://linux-hardware.org/?probe=3af9bcc9cb) | Jul 19, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [76b994344e](https://linux-hardware.org/?probe=76b994344e) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [10be1cd329](https://linux-hardware.org/?probe=10be1cd329) | Jul 18, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | Notebook    | [1a394fdf59](https://linux-hardware.org/?probe=1a394fdf59) | Jul 18, 2022 |
| Lenovo        | ThinkPad E595 20NF001HGE    | Notebook    | [9d3a54dbcf](https://linux-hardware.org/?probe=9d3a54dbcf) | Jul 17, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85a02f5d41](https://linux-hardware.org/?probe=85a02f5d41) | Jul 15, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [93b0330bb3](https://linux-hardware.org/?probe=93b0330bb3) | Jul 14, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HP            | 158B                        | Desktop     | [1f3ebf7ecf](https://linux-hardware.org/?probe=1f3ebf7ecf) | Jul 07, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [b92830b100](https://linux-hardware.org/?probe=b92830b100) | Jul 03, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [36dcdacdb1](https://linux-hardware.org/?probe=36dcdacdb1) | Jul 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5dd727cd5e](https://linux-hardware.org/?probe=5dd727cd5e) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [9aa0a38b17](https://linux-hardware.org/?probe=9aa0a38b17) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [b9b09609b8](https://linux-hardware.org/?probe=b9b09609b8) | Jul 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [7528e47074](https://linux-hardware.org/?probe=7528e47074) | Jun 24, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| MSI           | B450 TOMAHAWK               | Notebook    | [b9a8ce148e](https://linux-hardware.org/?probe=b9a8ce148e) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [16d7a07f8f](https://linux-hardware.org/?probe=16d7a07f8f) | Jun 20, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b0cc04798d](https://linux-hardware.org/?probe=b0cc04798d) | Jun 18, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [dc04d6eb1a](https://linux-hardware.org/?probe=dc04d6eb1a) | Jun 18, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [5c9a2e5312](https://linux-hardware.org/?probe=5c9a2e5312) | Jun 16, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [82a66444ec](https://linux-hardware.org/?probe=82a66444ec) | Jun 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| Dell          | Latitude XT                 | Notebook    | [6ca0e5ca92](https://linux-hardware.org/?probe=6ca0e5ca92) | Jun 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9275d3d785](https://linux-hardware.org/?probe=9275d3d785) | Jun 13, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [2c4fc4748b](https://linux-hardware.org/?probe=2c4fc4748b) | Jun 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| MSI           | B450 TOMAHAWK               | Notebook    | [ed5235f3f4](https://linux-hardware.org/?probe=ed5235f3f4) | Jun 09, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [c27da0faa9](https://linux-hardware.org/?probe=c27da0faa9) | Jun 06, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [343315ec17](https://linux-hardware.org/?probe=343315ec17) | Jun 06, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [5c7a9690cf](https://linux-hardware.org/?probe=5c7a9690cf) | Jun 05, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [51f7ef393f](https://linux-hardware.org/?probe=51f7ef393f) | Jun 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [2f56cc2ac8](https://linux-hardware.org/?probe=2f56cc2ac8) | Jun 04, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [cb5ea65a1d](https://linux-hardware.org/?probe=cb5ea65a1d) | Jun 04, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [e75c214872](https://linux-hardware.org/?probe=e75c214872) | Jun 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eaff4f6db6](https://linux-hardware.org/?probe=eaff4f6db6) | Jun 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [fb18d30478](https://linux-hardware.org/?probe=fb18d30478) | Jun 02, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [e9721391d2](https://linux-hardware.org/?probe=e9721391d2) | Jun 01, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [394d112de5](https://linux-hardware.org/?probe=394d112de5) | May 31, 2022 |
| Dell          | Latitude 5289               | Notebook    | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [462a42a8c9](https://linux-hardware.org/?probe=462a42a8c9) | May 28, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0075e2d9df](https://linux-hardware.org/?probe=0075e2d9df) | May 28, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [4ef7645f2d](https://linux-hardware.org/?probe=4ef7645f2d) | May 28, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [d17aaf4cc5](https://linux-hardware.org/?probe=d17aaf4cc5) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 81X2          | Convertible | [df65cb7a9e](https://linux-hardware.org/?probe=df65cb7a9e) | May 26, 2022 |
| Sony          | VPCCA17FX                   | Notebook    | [4ced9d5222](https://linux-hardware.org/?probe=4ced9d5222) | May 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [52b94e68a9](https://linux-hardware.org/?probe=52b94e68a9) | May 23, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4495957eae](https://linux-hardware.org/?probe=4495957eae) | May 23, 2022 |
| HP            | 0A08h                       | Desktop     | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| Timi          | A35S                        | Notebook    | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| ASRock        | A320M/ac                    | Desktop     | [78ee9c8853](https://linux-hardware.org/?probe=78ee9c8853) | May 20, 2022 |
| HP            | 3647h                       | Desktop     | [eccb82bec8](https://linux-hardware.org/?probe=eccb82bec8) | May 20, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [0bc568827c](https://linux-hardware.org/?probe=0bc568827c) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [bc731dc190](https://linux-hardware.org/?probe=bc731dc190) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [aa810f6e41](https://linux-hardware.org/?probe=aa810f6e41) | May 18, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [798bcbfce3](https://linux-hardware.org/?probe=798bcbfce3) | May 17, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [c4e15012d5](https://linux-hardware.org/?probe=c4e15012d5) | May 15, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| HP            | Notebook                    | Notebook    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3d921b618b](https://linux-hardware.org/?probe=3d921b618b) | May 07, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [7354dedb38](https://linux-hardware.org/?probe=7354dedb38) | May 03, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [bcc65ca336](https://linux-hardware.org/?probe=bcc65ca336) | May 03, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [e40e784775](https://linux-hardware.org/?probe=e40e784775) | May 03, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [b212517217](https://linux-hardware.org/?probe=b212517217) | May 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [79a3d8d3f6](https://linux-hardware.org/?probe=79a3d8d3f6) | May 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [06b533396d](https://linux-hardware.org/?probe=06b533396d) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | Notebook    | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e45e120b35](https://linux-hardware.org/?probe=e45e120b35) | Apr 29, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5754b2db0d](https://linux-hardware.org/?probe=5754b2db0d) | Apr 29, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [41f38e1f81](https://linux-hardware.org/?probe=41f38e1f81) | Apr 28, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a7eeea4f7c](https://linux-hardware.org/?probe=a7eeea4f7c) | Apr 27, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| Dell          | Latitude 7280               | Notebook    | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [3d667e4edf](https://linux-hardware.org/?probe=3d667e4edf) | Apr 21, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [5fdc5a8e7b](https://linux-hardware.org/?probe=5fdc5a8e7b) | Apr 21, 2022 |
| Google        | Celes                       | Notebook    | [a1a2262b88](https://linux-hardware.org/?probe=a1a2262b88) | Apr 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [5a58c1f799](https://linux-hardware.org/?probe=5a58c1f799) | Apr 18, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [583693a1a9](https://linux-hardware.org/?probe=583693a1a9) | Apr 17, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | Notebook    | [10a97e42a3](https://linux-hardware.org/?probe=10a97e42a3) | Apr 17, 2022 |
| Google        | Candy                       | Notebook    | [77b6731597](https://linux-hardware.org/?probe=77b6731597) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2b3ac63766](https://linux-hardware.org/?probe=2b3ac63766) | Apr 16, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [a892a2412c](https://linux-hardware.org/?probe=a892a2412c) | Apr 15, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a2947cf99b](https://linux-hardware.org/?probe=a2947cf99b) | Apr 15, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a6c14df869](https://linux-hardware.org/?probe=a6c14df869) | Apr 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [939dbc38d3](https://linux-hardware.org/?probe=939dbc38d3) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Acer          | Swift SF314-57G             | Notebook    | [b9b31b0528](https://linux-hardware.org/?probe=b9b31b0528) | Apr 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8ea05feeaf](https://linux-hardware.org/?probe=8ea05feeaf) | Apr 13, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [1a48a9a11d](https://linux-hardware.org/?probe=1a48a9a11d) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [d90283da2d](https://linux-hardware.org/?probe=d90283da2d) | Apr 13, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [c3202f68fc](https://linux-hardware.org/?probe=c3202f68fc) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [32f07398c4](https://linux-hardware.org/?probe=32f07398c4) | Apr 12, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| ILLEGEAR      | ROGUE                       | Notebook    | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [13df82ae45](https://linux-hardware.org/?probe=13df82ae45) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [69f81b5d41](https://linux-hardware.org/?probe=69f81b5d41) | Apr 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [31aefcd602](https://linux-hardware.org/?probe=31aefcd602) | Apr 10, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [183521cdae](https://linux-hardware.org/?probe=183521cdae) | Apr 07, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [febbb5b9a2](https://linux-hardware.org/?probe=febbb5b9a2) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [3327822265](https://linux-hardware.org/?probe=3327822265) | Apr 06, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9170392920](https://linux-hardware.org/?probe=9170392920) | Apr 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [87acd223c9](https://linux-hardware.org/?probe=87acd223c9) | Apr 04, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| Samsung       | 930QCA                      | Convertible | [d5991ba91f](https://linux-hardware.org/?probe=d5991ba91f) | Apr 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [58413a83b2](https://linux-hardware.org/?probe=58413a83b2) | Mar 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [dc38374e42](https://linux-hardware.org/?probe=dc38374e42) | Mar 26, 2022 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| Samsung       | 950QDB                      | Convertible | [97642a3dca](https://linux-hardware.org/?probe=97642a3dca) | Mar 23, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3500cd92bf](https://linux-hardware.org/?probe=3500cd92bf) | Mar 19, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [4b3b3cfc11](https://linux-hardware.org/?probe=4b3b3cfc11) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| Acer          | Extensa 2520                | Notebook    | [f070f33060](https://linux-hardware.org/?probe=f070f33060) | Mar 19, 2022 |
| Acer          | Extensa 2520                | Notebook    | [f2003c1f90](https://linux-hardware.org/?probe=f2003c1f90) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [a0a0ba299e](https://linux-hardware.org/?probe=a0a0ba299e) | Mar 15, 2022 |
| Google        | Akemi                       | Notebook    | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [88296140c2](https://linux-hardware.org/?probe=88296140c2) | Mar 11, 2022 |
| Dell          | Precision M6800             | Notebook    | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | Notebook    | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2d2bd57c8b](https://linux-hardware.org/?probe=2d2bd57c8b) | Mar 06, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [677fa0d0a3](https://linux-hardware.org/?probe=677fa0d0a3) | Mar 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [e81420b85c](https://linux-hardware.org/?probe=e81420b85c) | Mar 01, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Eluktronic... | Prometheus XVII             | Notebook    | [0797cebf2d](https://linux-hardware.org/?probe=0797cebf2d) | Feb 26, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f4bc34ce43](https://linux-hardware.org/?probe=f4bc34ce43) | Feb 23, 2022 |
| Dell          | Latitude 3420               | Notebook    | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | Notebook    | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [90e932e714](https://linux-hardware.org/?probe=90e932e714) | Feb 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7ad21cbc90](https://linux-hardware.org/?probe=7ad21cbc90) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [2bfd36f050](https://linux-hardware.org/?probe=2bfd36f050) | Feb 18, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | Notebook    | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Eluktronic... | Prometheus XVII             | Notebook    | [36436d1aff](https://linux-hardware.org/?probe=36436d1aff) | Feb 17, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| MSI           | B450 TOMAHAWK               | Notebook    | [63d492d4bb](https://linux-hardware.org/?probe=63d492d4bb) | Feb 16, 2022 |
| ASUSTek       | UX490UA                     | Notebook    | [5e40078555](https://linux-hardware.org/?probe=5e40078555) | Feb 14, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [879969adee](https://linux-hardware.org/?probe=879969adee) | Feb 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| Dell          | G3 3500                     | Notebook    | [92ee625013](https://linux-hardware.org/?probe=92ee625013) | Feb 09, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [1228be8404](https://linux-hardware.org/?probe=1228be8404) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Dell          | Latitude E4310              | Notebook    | [ef92697af7](https://linux-hardware.org/?probe=ef92697af7) | Feb 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [919eb44cc5](https://linux-hardware.org/?probe=919eb44cc5) | Feb 07, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [28bb1241de](https://linux-hardware.org/?probe=28bb1241de) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [64e32a1354](https://linux-hardware.org/?probe=64e32a1354) | Feb 02, 2022 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| HP            | 1905                        | Desktop     | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c2b7d7cdd1](https://linux-hardware.org/?probe=c2b7d7cdd1) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [ee91c21eb4](https://linux-hardware.org/?probe=ee91c21eb4) | Feb 01, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b8f0614b9c](https://linux-hardware.org/?probe=b8f0614b9c) | Feb 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [be25fc4f46](https://linux-hardware.org/?probe=be25fc4f46) | Feb 01, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [ecb2fdb4a3](https://linux-hardware.org/?probe=ecb2fdb4a3) | Jan 29, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [670589ec65](https://linux-hardware.org/?probe=670589ec65) | Jan 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5c5ac9fe1d](https://linux-hardware.org/?probe=5c5ac9fe1d) | Jan 26, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [317ebaa644](https://linux-hardware.org/?probe=317ebaa644) | Jan 26, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [cc0c86531b](https://linux-hardware.org/?probe=cc0c86531b) | Jan 22, 2022 |
| MSI           | B150M ECO                   | Desktop     | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [56e21b8bd6](https://linux-hardware.org/?probe=56e21b8bd6) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [6586f2d78f](https://linux-hardware.org/?probe=6586f2d78f) | Jan 22, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [a8cf42152e](https://linux-hardware.org/?probe=a8cf42152e) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [b09195fb3c](https://linux-hardware.org/?probe=b09195fb3c) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | Notebook    | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | Notebook    | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [57e7500f2a](https://linux-hardware.org/?probe=57e7500f2a) | Jan 17, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [e1f153a5e6](https://linux-hardware.org/?probe=e1f153a5e6) | Jan 14, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5ca44fe54c](https://linux-hardware.org/?probe=5ca44fe54c) | Jan 10, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [0462560ab2](https://linux-hardware.org/?probe=0462560ab2) | Jan 10, 2022 |
| ASRock        | FM2A88X Pro3+               | Desktop     | [1cc054ed3f](https://linux-hardware.org/?probe=1cc054ed3f) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [2542ffac8a](https://linux-hardware.org/?probe=2542ffac8a) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | Notebook    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c22ba841f6](https://linux-hardware.org/?probe=c22ba841f6) | Jan 06, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [2e5c796311](https://linux-hardware.org/?probe=2e5c796311) | Jan 06, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | Notebook    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | Notebook    | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [608af1b572](https://linux-hardware.org/?probe=608af1b572) | Jan 04, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | Notebook    | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [56db8627d8](https://linux-hardware.org/?probe=56db8627d8) | Jan 04, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| Timi          | A35S                        | Notebook    | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| MSI           | B450 TOMAHAWK               | Notebook    | [c85d7c78e7](https://linux-hardware.org/?probe=c85d7c78e7) | Dec 28, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [b608797946](https://linux-hardware.org/?probe=b608797946) | Dec 28, 2021 |
| LattePanda    | Alpha                       | Desktop     | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda    | Alpha                       | Desktop     | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte      | M68M-S2P                    | Desktop     | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [a4a8130a06](https://linux-hardware.org/?probe=a4a8130a06) | Dec 24, 2021 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [756df875af](https://linux-hardware.org/?probe=756df875af) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [cd01eec1a8](https://linux-hardware.org/?probe=cd01eec1a8) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [4d153ddb81](https://linux-hardware.org/?probe=4d153ddb81) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [deb1a17957](https://linux-hardware.org/?probe=deb1a17957) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [ca89ed6eab](https://linux-hardware.org/?probe=ca89ed6eab) | Dec 23, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [f51d57d3bc](https://linux-hardware.org/?probe=f51d57d3bc) | Dec 21, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Unknown       | Intel X79                   | Desktop     | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0LU0... | Notebook    | [ab6c683160](https://linux-hardware.org/?probe=ab6c683160) | Dec 16, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [16daa16444](https://linux-hardware.org/?probe=16daa16444) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [bc313ce031](https://linux-hardware.org/?probe=bc313ce031) | Dec 15, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a34aa5357b](https://linux-hardware.org/?probe=a34aa5357b) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [6d5612f136](https://linux-hardware.org/?probe=6d5612f136) | Dec 13, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [706fc926ca](https://linux-hardware.org/?probe=706fc926ca) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| Framework     | Laptop                      | Notebook    | [c1a31372f4](https://linux-hardware.org/?probe=c1a31372f4) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | Bravo 15 B5DD               | Notebook    | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| MSI           | GS63VR 6RF                  | Notebook    | [2d9061c72e](https://linux-hardware.org/?probe=2d9061c72e) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| HP            | 15 TS                       | Notebook    | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [ec54ffae7a](https://linux-hardware.org/?probe=ec54ffae7a) | Nov 18, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [778d32ce4b](https://linux-hardware.org/?probe=778d32ce4b) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [9fc3f12603](https://linux-hardware.org/?probe=9fc3f12603) | Nov 16, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7ebeace900](https://linux-hardware.org/?probe=7ebeace900) | Nov 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1cfd4ee9f9](https://linux-hardware.org/?probe=1cfd4ee9f9) | Nov 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [c11672a55e](https://linux-hardware.org/?probe=c11672a55e) | Nov 11, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [c9e5138184](https://linux-hardware.org/?probe=c9e5138184) | Nov 07, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [22ce2703b9](https://linux-hardware.org/?probe=22ce2703b9) | Nov 07, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [5d0bad7c15](https://linux-hardware.org/?probe=5d0bad7c15) | Nov 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [e95d2fa980](https://linux-hardware.org/?probe=e95d2fa980) | Nov 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [85dff2829f](https://linux-hardware.org/?probe=85dff2829f) | Nov 03, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f57c7bbe97](https://linux-hardware.org/?probe=f57c7bbe97) | Nov 03, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [222ce004da](https://linux-hardware.org/?probe=222ce004da) | Nov 01, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [ca3c48f689](https://linux-hardware.org/?probe=ca3c48f689) | Oct 30, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [79e6ef3655](https://linux-hardware.org/?probe=79e6ef3655) | Oct 29, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [6db3b9d661](https://linux-hardware.org/?probe=6db3b9d661) | Oct 29, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3fcea4d382](https://linux-hardware.org/?probe=3fcea4d382) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [cce67d37aa](https://linux-hardware.org/?probe=cce67d37aa) | Oct 28, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [689f9368f1](https://linux-hardware.org/?probe=689f9368f1) | Oct 23, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [7b3cdda6e2](https://linux-hardware.org/?probe=7b3cdda6e2) | Oct 20, 2021 |
| HP            | ENVY 6                      | Notebook    | [94471889b0](https://linux-hardware.org/?probe=94471889b0) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [ff566c77ce](https://linux-hardware.org/?probe=ff566c77ce) | Oct 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [2d3f367fa7](https://linux-hardware.org/?probe=2d3f367fa7) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [6e745a1ec9](https://linux-hardware.org/?probe=6e745a1ec9) | Oct 17, 2021 |
| Dell          | Latitude E6410              | Notebook    | [68d7531397](https://linux-hardware.org/?probe=68d7531397) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [8d0e93e90f](https://linux-hardware.org/?probe=8d0e93e90f) | Oct 16, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [87ab64b604](https://linux-hardware.org/?probe=87ab64b604) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Dell          | Precision M4400             | Notebook    | [bae8becab1](https://linux-hardware.org/?probe=bae8becab1) | Oct 11, 2021 |
| Google        | Kindred                     | Notebook    | [9420945432](https://linux-hardware.org/?probe=9420945432) | Oct 10, 2021 |
| Dell          | Latitude E4300              | Notebook    | [c486155f48](https://linux-hardware.org/?probe=c486155f48) | Oct 10, 2021 |
| Dell          | Latitude E4300              | Notebook    | [52e0d626fa](https://linux-hardware.org/?probe=52e0d626fa) | Oct 10, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7f47afdf06](https://linux-hardware.org/?probe=7f47afdf06) | Oct 10, 2021 |
| UMAX          | J42 Nano                    | Desktop     | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [cc7d0245a7](https://linux-hardware.org/?probe=cc7d0245a7) | Oct 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [ebfe78c927](https://linux-hardware.org/?probe=ebfe78c927) | Oct 08, 2021 |
| Dell          | G3 3500                     | Notebook    | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [849ca2da3d](https://linux-hardware.org/?probe=849ca2da3d) | Oct 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0923a8b728](https://linux-hardware.org/?probe=0923a8b728) | Oct 05, 2021 |
| Dell          | Precision M4400             | Notebook    | [ab43bad624](https://linux-hardware.org/?probe=ab43bad624) | Oct 04, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [e8a2ba9952](https://linux-hardware.org/?probe=e8a2ba9952) | Oct 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9c8bc954a7](https://linux-hardware.org/?probe=9c8bc954a7) | Oct 02, 2021 |
| MSI           | G41M-P33 Combo              | Desktop     | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [dc91b564a8](https://linux-hardware.org/?probe=dc91b564a8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [86c4b5769f](https://linux-hardware.org/?probe=86c4b5769f) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [263233be76](https://linux-hardware.org/?probe=263233be76) | Sep 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| Lenovo        | ThinkPad T480 20L6S3S500    | Notebook    | [067f3cf110](https://linux-hardware.org/?probe=067f3cf110) | Sep 26, 2021 |
| Lenovo        | ThinkPad T470 20HES2SF00    | Notebook    | [9cf10e22a6](https://linux-hardware.org/?probe=9cf10e22a6) | Sep 25, 2021 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a20f426eed](https://linux-hardware.org/?probe=a20f426eed) | Sep 25, 2021 |
| Lenovo        | ThinkPad E460 20ET004LGE    | Notebook    | [b64e2c4a07](https://linux-hardware.org/?probe=b64e2c4a07) | Sep 25, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [c11a70be9e](https://linux-hardware.org/?probe=c11a70be9e) | Sep 24, 2021 |
| Dell          | Precision 3560              | Notebook    | [d9b527db16](https://linux-hardware.org/?probe=d9b527db16) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1e1e40ce8b](https://linux-hardware.org/?probe=1e1e40ce8b) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [711e2e3960](https://linux-hardware.org/?probe=711e2e3960) | Sep 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [8ffa4dd273](https://linux-hardware.org/?probe=8ffa4dd273) | Sep 18, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [3a7231ce53](https://linux-hardware.org/?probe=3a7231ce53) | Sep 17, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [60555ce93d](https://linux-hardware.org/?probe=60555ce93d) | Sep 16, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [8dfad66767](https://linux-hardware.org/?probe=8dfad66767) | Sep 16, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [3e845646c9](https://linux-hardware.org/?probe=3e845646c9) | Sep 15, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | Notebook    | [0fe0fa66d6](https://linux-hardware.org/?probe=0fe0fa66d6) | Sep 14, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | Notebook    | [d5e170957e](https://linux-hardware.org/?probe=d5e170957e) | Sep 14, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [33cee010e8](https://linux-hardware.org/?probe=33cee010e8) | Sep 12, 2021 |
| Dell          | 0JYH5J A00                  | All in one  | [f05e2951a1](https://linux-hardware.org/?probe=f05e2951a1) | Sep 11, 2021 |
| HP            | 8430 1000                   | All in one  | [56c6d48f6e](https://linux-hardware.org/?probe=56c6d48f6e) | Sep 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [c06b4b30a0](https://linux-hardware.org/?probe=c06b4b30a0) | Sep 10, 2021 |
| AMI           | Intel                       | Notebook    | [49dd022241](https://linux-hardware.org/?probe=49dd022241) | Sep 10, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [0c83ae1e11](https://linux-hardware.org/?probe=0c83ae1e11) | Sep 10, 2021 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [167df4c15e](https://linux-hardware.org/?probe=167df4c15e) | Sep 09, 2021 |
| Dell          | Latitude E4310              | Notebook    | [34c3815468](https://linux-hardware.org/?probe=34c3815468) | Sep 02, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [12cf057e04](https://linux-hardware.org/?probe=12cf057e04) | Sep 02, 2021 |
| TrekStor      | Primebook P14               | Notebook    | [026e7277ee](https://linux-hardware.org/?probe=026e7277ee) | Sep 02, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| Dell          | Precision M4400             | Notebook    | [289a2606bd](https://linux-hardware.org/?probe=289a2606bd) | Sep 02, 2021 |
| Intel         | DH55HC AAE70933-504         | Desktop     | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [581b1be43c](https://linux-hardware.org/?probe=581b1be43c) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3ab28e58e](https://linux-hardware.org/?probe=d3ab28e58e) | Aug 30, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [24a34a526e](https://linux-hardware.org/?probe=24a34a526e) | Aug 28, 2021 |
| Lenovo        | IdeaPad 510S-14IKB 80UV     | Notebook    | [146390e85e](https://linux-hardware.org/?probe=146390e85e) | Aug 25, 2021 |
| ASUSTek       | G752VT                      | Notebook    | [23dea85a93](https://linux-hardware.org/?probe=23dea85a93) | Aug 24, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP            | 8906 SMVB                   | Desktop     | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| Dell          | Latitude E7440              | Notebook    | [0de5415ad7](https://linux-hardware.org/?probe=0de5415ad7) | Aug 22, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [4c8282bb42](https://linux-hardware.org/?probe=4c8282bb42) | Aug 16, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [ae8d8171a7](https://linux-hardware.org/?probe=ae8d8171a7) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [5d560f16cc](https://linux-hardware.org/?probe=5d560f16cc) | Aug 12, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [9be95b3419](https://linux-hardware.org/?probe=9be95b3419) | Aug 12, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Gigabyte      | P35-DS3R                    | Desktop     | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [8e9d51a941](https://linux-hardware.org/?probe=8e9d51a941) | Aug 07, 2021 |
| Dell          | 0K240Y A01                  | Desktop     | [5cc92cb5ac](https://linux-hardware.org/?probe=5cc92cb5ac) | Aug 04, 2021 |
| Notebook      | W65_67SZ                    | Notebook    | [ddd6f26db4](https://linux-hardware.org/?probe=ddd6f26db4) | Aug 03, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [1af0342def](https://linux-hardware.org/?probe=1af0342def) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1ccf2e3d28](https://linux-hardware.org/?probe=1ccf2e3d28) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [b5b8bac74a](https://linux-hardware.org/?probe=b5b8bac74a) | Jul 26, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [12d6be24d7](https://linux-hardware.org/?probe=12d6be24d7) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Acer          | Aspire C27-962              | All in one  | [75e1d7295c](https://linux-hardware.org/?probe=75e1d7295c) | Jul 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [a5959b657f](https://linux-hardware.org/?probe=a5959b657f) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [f8f9bf0717](https://linux-hardware.org/?probe=f8f9bf0717) | Jul 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [7cdf389d4c](https://linux-hardware.org/?probe=7cdf389d4c) | Jul 22, 2021 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [4421b175f7](https://linux-hardware.org/?probe=4421b175f7) | Jul 16, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [8d7689bceb](https://linux-hardware.org/?probe=8d7689bceb) | Jul 14, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Acer          | Predator G9-792             | Notebook    | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [f36328f6b3](https://linux-hardware.org/?probe=f36328f6b3) | Jul 12, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [c79cfacd5e](https://linux-hardware.org/?probe=c79cfacd5e) | Jul 05, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [282a2e2926](https://linux-hardware.org/?probe=282a2e2926) | Jul 04, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [14b3d46ef8](https://linux-hardware.org/?probe=14b3d46ef8) | Jul 03, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [3be93cbc0c](https://linux-hardware.org/?probe=3be93cbc0c) | Jul 03, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [181cfa9437](https://linux-hardware.org/?probe=181cfa9437) | Jul 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [a92028f13a](https://linux-hardware.org/?probe=a92028f13a) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | Notebook    | [56a361debf](https://linux-hardware.org/?probe=56a361debf) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | Notebook    | [431df4bc98](https://linux-hardware.org/?probe=431df4bc98) | Jul 01, 2021 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| Dell          | G7 7588                     | Notebook    | [259694c4a1](https://linux-hardware.org/?probe=259694c4a1) | Jun 27, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [4b70691f2e](https://linux-hardware.org/?probe=4b70691f2e) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [397e22935b](https://linux-hardware.org/?probe=397e22935b) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [10c5bbf0f8](https://linux-hardware.org/?probe=10c5bbf0f8) | Jun 18, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2762be36c4](https://linux-hardware.org/?probe=2762be36c4) | Jun 14, 2021 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| HP            | EliteBook Revolve 810       | Notebook    | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | Notebook    | [4c600416f9](https://linux-hardware.org/?probe=4c600416f9) | May 28, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [99ab618bee](https://linux-hardware.org/?probe=99ab618bee) | May 25, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | Notebook    | [684dfb967f](https://linux-hardware.org/?probe=684dfb967f) | May 22, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | Notebook    | [c18360d17e](https://linux-hardware.org/?probe=c18360d17e) | May 22, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c1b869c13a](https://linux-hardware.org/?probe=c1b869c13a) | May 22, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [a666be1df5](https://linux-hardware.org/?probe=a666be1df5) | May 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [457597b9d1](https://linux-hardware.org/?probe=457597b9d1) | May 21, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [e18030e5f0](https://linux-hardware.org/?probe=e18030e5f0) | May 20, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [7e5dbc86b9](https://linux-hardware.org/?probe=7e5dbc86b9) | May 20, 2021 |
| Dell          | Inspiron 7386               | Convertible | [42442e4d61](https://linux-hardware.org/?probe=42442e4d61) | May 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [14b3851754](https://linux-hardware.org/?probe=14b3851754) | May 20, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [585db3001d](https://linux-hardware.org/?probe=585db3001d) | May 19, 2021 |
| Notebook      | NS50MU                      | Notebook    | [8e08645823](https://linux-hardware.org/?probe=8e08645823) | May 19, 2021 |
| Lenovo        | ThinkPad P51 20HHCT01WW     | Notebook    | [3f42eaf28b](https://linux-hardware.org/?probe=3f42eaf28b) | May 19, 2021 |
| HP            | 2B36                        | Desktop     | [62135f1e45](https://linux-hardware.org/?probe=62135f1e45) | May 19, 2021 |
| MSI           | GE72 6QD                    | Notebook    | [7637f1ad9c](https://linux-hardware.org/?probe=7637f1ad9c) | May 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| Dell          | Inspiron 7386               | Convertible | [c6f4d6de84](https://linux-hardware.org/?probe=c6f4d6de84) | May 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [634c63d316](https://linux-hardware.org/?probe=634c63d316) | May 15, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [17af51e9b1](https://linux-hardware.org/?probe=17af51e9b1) | May 14, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9048b606d2](https://linux-hardware.org/?probe=9048b606d2) | May 13, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [fc96347868](https://linux-hardware.org/?probe=fc96347868) | May 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f02e90a00f](https://linux-hardware.org/?probe=f02e90a00f) | May 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | Notebook    | [b3a5056cbf](https://linux-hardware.org/?probe=b3a5056cbf) | May 07, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [365c656e4a](https://linux-hardware.org/?probe=365c656e4a) | May 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [fca3b0c89b](https://linux-hardware.org/?probe=fca3b0c89b) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9e8b256742](https://linux-hardware.org/?probe=9e8b256742) | May 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [e7cd00034c](https://linux-hardware.org/?probe=e7cd00034c) | May 02, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [39f6decf99](https://linux-hardware.org/?probe=39f6decf99) | May 02, 2021 |
| HP            | 255 G4                      | Notebook    | [9070448ace](https://linux-hardware.org/?probe=9070448ace) | May 01, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | Notebook    | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [3d3ef81b3b](https://linux-hardware.org/?probe=3d3ef81b3b) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [dd68978e2b](https://linux-hardware.org/?probe=dd68978e2b) | Apr 28, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [7ee064e334](https://linux-hardware.org/?probe=7ee064e334) | Apr 27, 2021 |
| Acer          | Extensa 2510                | Notebook    | [1f257d3f4e](https://linux-hardware.org/?probe=1f257d3f4e) | Apr 25, 2021 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [764390758a](https://linux-hardware.org/?probe=764390758a) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [eabc0fa5e5](https://linux-hardware.org/?probe=eabc0fa5e5) | Apr 21, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [fae6227cfc](https://linux-hardware.org/?probe=fae6227cfc) | Apr 19, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [0685ce717e](https://linux-hardware.org/?probe=0685ce717e) | Apr 16, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [a635a3acb3](https://linux-hardware.org/?probe=a635a3acb3) | Apr 13, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Toshiba       | Satellite P750              | Notebook    | [d248a5f049](https://linux-hardware.org/?probe=d248a5f049) | Apr 11, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d53c2a8b0e](https://linux-hardware.org/?probe=d53c2a8b0e) | Apr 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Dell          | Inspiron 5391               | Notebook    | [80bf268441](https://linux-hardware.org/?probe=80bf268441) | Apr 08, 2021 |
| Dell          | 0080PM A00                  | Desktop     | [efc9497e6d](https://linux-hardware.org/?probe=efc9497e6d) | Apr 08, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [63e7ed5aa3](https://linux-hardware.org/?probe=63e7ed5aa3) | Apr 07, 2021 |
| Lenovo        | 36EB NOK                    | Desktop     | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [08f8da317e](https://linux-hardware.org/?probe=08f8da317e) | Apr 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [9e5b4c92f4](https://linux-hardware.org/?probe=9e5b4c92f4) | Apr 01, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [6fdb3a7d9e](https://linux-hardware.org/?probe=6fdb3a7d9e) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [269185aba1](https://linux-hardware.org/?probe=269185aba1) | Mar 28, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Dell          | G7 7588                     | Notebook    | [95e0518b2c](https://linux-hardware.org/?probe=95e0518b2c) | Mar 25, 2021 |
| Dell          | Latitude 5300               | Notebook    | [efd4a051e5](https://linux-hardware.org/?probe=efd4a051e5) | Mar 23, 2021 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [2290f44e04](https://linux-hardware.org/?probe=2290f44e04) | Mar 23, 2021 |
| Lenovo        | ThinkPad L460 20FV002EBR    | Notebook    | [f19448d66f](https://linux-hardware.org/?probe=f19448d66f) | Mar 19, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0debcb68ae](https://linux-hardware.org/?probe=0debcb68ae) | Mar 18, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | Notebook    | [e03adb0720](https://linux-hardware.org/?probe=e03adb0720) | Mar 17, 2021 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [31baa57d40](https://linux-hardware.org/?probe=31baa57d40) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [13dfc4a9af](https://linux-hardware.org/?probe=13dfc4a9af) | Mar 17, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [7c5776953c](https://linux-hardware.org/?probe=7c5776953c) | Mar 15, 2021 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [4983586fe5](https://linux-hardware.org/?probe=4983586fe5) | Mar 12, 2021 |
| Dell          | G5 5505                     | Notebook    | [e8e38279d3](https://linux-hardware.org/?probe=e8e38279d3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [062dfb8010](https://linux-hardware.org/?probe=062dfb8010) | Mar 09, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [41de0a7ee7](https://linux-hardware.org/?probe=41de0a7ee7) | Mar 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [eec4ef3dce](https://linux-hardware.org/?probe=eec4ef3dce) | Mar 07, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [bd3a730b32](https://linux-hardware.org/?probe=bd3a730b32) | Mar 03, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [88635c9f76](https://linux-hardware.org/?probe=88635c9f76) | Feb 23, 2021 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [c4ecc96eae](https://linux-hardware.org/?probe=c4ecc96eae) | Feb 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [93115f0746](https://linux-hardware.org/?probe=93115f0746) | Feb 14, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [1bd84f7c03](https://linux-hardware.org/?probe=1bd84f7c03) | Feb 13, 2021 |
| HP            | ZBook 15                    | Notebook    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [67ca38a642](https://linux-hardware.org/?probe=67ca38a642) | Feb 12, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [72f95227fd](https://linux-hardware.org/?probe=72f95227fd) | Feb 11, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [130e9bdb5c](https://linux-hardware.org/?probe=130e9bdb5c) | Feb 11, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [e6937666ae](https://linux-hardware.org/?probe=e6937666ae) | Feb 11, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [e11200bd19](https://linux-hardware.org/?probe=e11200bd19) | Feb 10, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [cef326fa21](https://linux-hardware.org/?probe=cef326fa21) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [43bb3ec644](https://linux-hardware.org/?probe=43bb3ec644) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [5856d93198](https://linux-hardware.org/?probe=5856d93198) | Feb 07, 2021 |
| HP            | ENVY Notebook               | Notebook    | [4f20314e69](https://linux-hardware.org/?probe=4f20314e69) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [311f54d837](https://linux-hardware.org/?probe=311f54d837) | Jan 28, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [4b469e2e7e](https://linux-hardware.org/?probe=4b469e2e7e) | Jan 23, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [335242ec06](https://linux-hardware.org/?probe=335242ec06) | Jan 20, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [43b3323a07](https://linux-hardware.org/?probe=43b3323a07) | Jan 18, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [a0c3014b22](https://linux-hardware.org/?probe=a0c3014b22) | Jan 17, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | Notebook    | [9fd64a3945](https://linux-hardware.org/?probe=9fd64a3945) | Jan 11, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [6499961dbf](https://linux-hardware.org/?probe=6499961dbf) | Jan 09, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [2df429a577](https://linux-hardware.org/?probe=2df429a577) | Jan 06, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [5df2e0f87d](https://linux-hardware.org/?probe=5df2e0f87d) | Jan 06, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| ASUSTek       | Z87-PRO                     | Desktop     | [2ab19967fa](https://linux-hardware.org/?probe=2ab19967fa) | Dec 30, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [4d27980548](https://linux-hardware.org/?probe=4d27980548) | Dec 27, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [08895b552f](https://linux-hardware.org/?probe=08895b552f) | Dec 27, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [f2b808bdd1](https://linux-hardware.org/?probe=f2b808bdd1) | Dec 24, 2020 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [8b792fe096](https://linux-hardware.org/?probe=8b792fe096) | Dec 23, 2020 |
| HP            | 1905                        | Desktop     | [63771015f5](https://linux-hardware.org/?probe=63771015f5) | Dec 22, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| HP            | EliteBook Revolve 810       | Notebook    | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| Apple         | MacBookAir4,2               | Notebook    | [a3ebd820e2](https://linux-hardware.org/?probe=a3ebd820e2) | Dec 17, 2020 |
| Alienware     | 14                          | Notebook    | [3211a0e18d](https://linux-hardware.org/?probe=3211a0e18d) | Dec 12, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [75384533dc](https://linux-hardware.org/?probe=75384533dc) | Dec 06, 2020 |
| Dell          | Precision M6600             | Notebook    | [c3eafadf96](https://linux-hardware.org/?probe=c3eafadf96) | Dec 05, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7e7ad00d75](https://linux-hardware.org/?probe=7e7ad00d75) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7e75c8dc00](https://linux-hardware.org/?probe=7e75c8dc00) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2381ec1bad](https://linux-hardware.org/?probe=2381ec1bad) | Nov 30, 2020 |
| MSI           | GT80S 6QE                   | Notebook    | [a938950688](https://linux-hardware.org/?probe=a938950688) | Nov 28, 2020 |
| MSI           | GT80S 6QE                   | Notebook    | [a07d34dcff](https://linux-hardware.org/?probe=a07d34dcff) | Nov 28, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [0ffe9c1f28](https://linux-hardware.org/?probe=0ffe9c1f28) | Nov 27, 2020 |
| Dell          | Precision M6600             | Notebook    | [990be59736](https://linux-hardware.org/?probe=990be59736) | Nov 21, 2020 |
| ASUSTek       | X550CL                      | Notebook    | [5315051a75](https://linux-hardware.org/?probe=5315051a75) | Nov 21, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2a4a52111f](https://linux-hardware.org/?probe=2a4a52111f) | Nov 21, 2020 |
| Dell          | 0KRC95 A02                  | Desktop     | [af91587001](https://linux-hardware.org/?probe=af91587001) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | Notebook    | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Dell          | 0D4VY1 A00                  | All in one  | [071c584451](https://linux-hardware.org/?probe=071c584451) | Nov 18, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [3de701fc00](https://linux-hardware.org/?probe=3de701fc00) | Nov 12, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [64d986c0ec](https://linux-hardware.org/?probe=64d986c0ec) | Nov 12, 2020 |
| Dell          | 0KRC95 A02                  | Desktop     | [6471eccd57](https://linux-hardware.org/?probe=6471eccd57) | Nov 11, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7a14486580](https://linux-hardware.org/?probe=7a14486580) | Nov 04, 2020 |
| Timi          | TM1607                      | Notebook    | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| HP            | 8455                        | Desktop     | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [5cdfdbceae](https://linux-hardware.org/?probe=5cdfdbceae) | Oct 26, 2020 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [130d636b9e](https://linux-hardware.org/?probe=130d636b9e) | Oct 26, 2020 |
| HP            | 8455                        | Desktop     | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3e19ade739](https://linux-hardware.org/?probe=3e19ade739) | Oct 25, 2020 |
| HP            | Notebook                    | Notebook    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Dell          | 0G214D A00                  | Desktop     | [21319d118b](https://linux-hardware.org/?probe=21319d118b) | Oct 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1e6190a4f2](https://linux-hardware.org/?probe=1e6190a4f2) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [d3265c616b](https://linux-hardware.org/?probe=d3265c616b) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [01f75c41ed](https://linux-hardware.org/?probe=01f75c41ed) | Oct 20, 2020 |
| Microsoft     | Surface Laptop              | Tablet      | [26578393cc](https://linux-hardware.org/?probe=26578393cc) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [502cfa6428](https://linux-hardware.org/?probe=502cfa6428) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [459870a593](https://linux-hardware.org/?probe=459870a593) | Oct 14, 2020 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [eab288b1e2](https://linux-hardware.org/?probe=eab288b1e2) | Oct 13, 2020 |
| ASUSTek       | GL702ZC                     | Notebook    | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [2abc472e43](https://linux-hardware.org/?probe=2abc472e43) | Oct 08, 2020 |
| Acer          | Aspire E5-573               | Notebook    | [89237e04fc](https://linux-hardware.org/?probe=89237e04fc) | Oct 04, 2020 |
| Unknown       | Unknown                     | Notebook    | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| MSI           | MS-7366                     | Desktop     | [ada828f120](https://linux-hardware.org/?probe=ada828f120) | Sep 29, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [a031f4a8a2](https://linux-hardware.org/?probe=a031f4a8a2) | Sep 29, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [4ec2f0a6cc](https://linux-hardware.org/?probe=4ec2f0a6cc) | Sep 29, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ee969068e8](https://linux-hardware.org/?probe=ee969068e8) | Sep 28, 2020 |
| Dell          | G3 3579                     | Notebook    | [6853280510](https://linux-hardware.org/?probe=6853280510) | Sep 28, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a4e794299b](https://linux-hardware.org/?probe=a4e794299b) | Sep 28, 2020 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [9499adb6fc](https://linux-hardware.org/?probe=9499adb6fc) | Sep 26, 2020 |
| MSI           | MS-7366                     | Desktop     | [9938e6501b](https://linux-hardware.org/?probe=9938e6501b) | Sep 24, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [34f1896f7e](https://linux-hardware.org/?probe=34f1896f7e) | Sep 23, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [17e933a69c](https://linux-hardware.org/?probe=17e933a69c) | Sep 21, 2020 |
| HP            | 1497                        | Desktop     | [7cb2cee563](https://linux-hardware.org/?probe=7cb2cee563) | Sep 19, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [50a3035c47](https://linux-hardware.org/?probe=50a3035c47) | Sep 12, 2020 |
| Acer          | TravelMate P633-M           | Notebook    | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3919584d23](https://linux-hardware.org/?probe=3919584d23) | Sep 06, 2020 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [8802aa3282](https://linux-hardware.org/?probe=8802aa3282) | Sep 04, 2020 |
| Dell          | Latitude E6440              | Notebook    | [ddd1e2f728](https://linux-hardware.org/?probe=ddd1e2f728) | Sep 03, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [8b75181a08](https://linux-hardware.org/?probe=8b75181a08) | Sep 03, 2020 |
| ASUSTek       | UX310UA                     | Notebook    | [90e38ace34](https://linux-hardware.org/?probe=90e38ace34) | Sep 03, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [028f3ba060](https://linux-hardware.org/?probe=028f3ba060) | Sep 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [662f61d283](https://linux-hardware.org/?probe=662f61d283) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [143c679f1a](https://linux-hardware.org/?probe=143c679f1a) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2ab9b15cb6](https://linux-hardware.org/?probe=2ab9b15cb6) | Sep 03, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [82736e9fa5](https://linux-hardware.org/?probe=82736e9fa5) | Aug 23, 2020 |
| Dell          | Latitude E6430              | Notebook    | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8790b1b459](https://linux-hardware.org/?probe=8790b1b459) | Aug 12, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [e94f81e5f1](https://linux-hardware.org/?probe=e94f81e5f1) | Aug 12, 2020 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [844cca1bee](https://linux-hardware.org/?probe=844cca1bee) | Aug 09, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [cb7a700ec4](https://linux-hardware.org/?probe=cb7a700ec4) | Aug 07, 2020 |
| Dell          | Inspiron 5485 2n1           | Convertible | [b6c573f5aa](https://linux-hardware.org/?probe=b6c573f5aa) | Aug 05, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [935afc3dde](https://linux-hardware.org/?probe=935afc3dde) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [fd00cb49a3](https://linux-hardware.org/?probe=fd00cb49a3) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [4830a55da9](https://linux-hardware.org/?probe=4830a55da9) | Jul 27, 2020 |
| Dell          | Latitude 7400               | Notebook    | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | Notebook    | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| Dell          | Latitude 7400               | Notebook    | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| Lenovo        | ThinkPad E595 20NFS0TD00    | Notebook    | [7fbac3cf0a](https://linux-hardware.org/?probe=7fbac3cf0a) | Jul 16, 2020 |
| Gigabyte      | B365M DS3H                  | Desktop     | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [ed0f57c08d](https://linux-hardware.org/?probe=ed0f57c08d) | Jul 14, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [54774ae912](https://linux-hardware.org/?probe=54774ae912) | Jul 14, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [85295c522b](https://linux-hardware.org/?probe=85295c522b) | Jul 14, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [6e3c82fbca](https://linux-hardware.org/?probe=6e3c82fbca) | Jul 13, 2020 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI           | B450-A PRO MAX              | Desktop     | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [fc1d360821](https://linux-hardware.org/?probe=fc1d360821) | Jun 29, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1708b21dab](https://linux-hardware.org/?probe=1708b21dab) | Jun 28, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [d0d3d517ef](https://linux-hardware.org/?probe=d0d3d517ef) | Jun 16, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [a2e2a6cf66](https://linux-hardware.org/?probe=a2e2a6cf66) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| Lenovo        | G505s 20255                 | Notebook    | [21f31cf2d0](https://linux-hardware.org/?probe=21f31cf2d0) | Apr 21, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| HP            | EliteBook 8770w             | Notebook    | [44b687a5ef](https://linux-hardware.org/?probe=44b687a5ef) | Jan 31, 2020 |
| HP            | EliteBook 830 G6            | Notebook    | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Acer          | Aspire ES1-520              | Notebook    | [12a0136c2d](https://linux-hardware.org/?probe=12a0136c2d) | Jan 20, 2020 |
| Shinelon C... | W65KJ1_KK1                  | Notebook    | [924a887f7d](https://linux-hardware.org/?probe=924a887f7d) | Dec 09, 2019 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [d5c741f8df](https://linux-hardware.org/?probe=d5c741f8df) | Dec 08, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |
| HP            | Spectre x360 Convertible... | Convertible | [90c646de9c](https://linux-hardware.org/?probe=90c646de9c) | Sep 13, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [3477d2f29e](https://linux-hardware.org/?probe=3477d2f29e) | Sep 10, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [80bdb92976](https://linux-hardware.org/?probe=80bdb92976) | Sep 10, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 401       | 75.23%  |
| EndeavourOS         | 132       | 24.77%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 528       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.15.12-arch1-1    | 20        | 3.32%   |
| 5.17.1-arch1-1     | 11        | 1.82%   |
| 5.17.5-arch1-1     | 10        | 1.66%   |
| 5.15.10-arch1-1    | 9         | 1.49%   |
| 5.17.9-arch1-1     | 8         | 1.33%   |
| 5.15.7-arch1-1     | 8         | 1.33%   |
| 5.14.9-arch2-1     | 8         | 1.33%   |
| 5.13.13-arch1-1    | 8         | 1.33%   |
| 5.11.11-arch1-1    | 8         | 1.33%   |
| 5.9.14-arch1-1     | 7         | 1.16%   |
| 5.18.12-arch1-1    | 7         | 1.16%   |
| 5.16.10-arch1-1    | 7         | 1.16%   |
| 5.9.1-arch1-1      | 6         | 1%      |
| 5.7.7-arch1-1      | 6         | 1%      |
| 5.16.2-arch1-1     | 6         | 1%      |
| 5.15.4-arch1-1     | 6         | 1%      |
| 5.7.8-arch1-1      | 5         | 0.83%   |
| 5.18.3-arch1-1     | 5         | 0.83%   |
| 5.17.4-arch1-1     | 5         | 0.83%   |
| 5.16.8-arch1-1     | 5         | 0.83%   |
| 5.16.4-arch1-1     | 5         | 0.83%   |
| 5.16.16-arch1-1    | 5         | 0.83%   |
| 5.15.8-arch1-1     | 5         | 0.83%   |
| 5.15.2-arch1-1     | 5         | 0.83%   |
| 5.15.11-arch2-1    | 5         | 0.83%   |
| 5.14.2-arch1-2     | 5         | 0.83%   |
| 5.14.14-arch1-1    | 5         | 0.83%   |
| 5.12.14-arch1-1    | 5         | 0.83%   |
| 5.9.10-arch1-1     | 4         | 0.66%   |
| 5.7.12-arch1-1     | 4         | 0.66%   |
| 5.18.7-arch1-1     | 4         | 0.66%   |
| 5.18.5-arch1-1     | 4         | 0.66%   |
| 5.18.1-arch1-1     | 4         | 0.66%   |
| 5.16.14-arch1-1    | 4         | 0.66%   |
| 5.16.13-arch1-1    | 4         | 0.66%   |
| 5.15.12-zen1-1-zen | 4         | 0.66%   |
| 5.14.8-arch1-1     | 4         | 0.66%   |
| 5.14.6-arch1-1     | 4         | 0.66%   |
| 5.14.16-arch1-1    | 4         | 0.66%   |
| 5.12.13-arch1-2    | 4         | 0.66%   |
| 5.11.16-zen1-1-zen | 4         | 0.66%   |
| 5.11.16-arch1-1    | 4         | 0.66%   |
| 5.10.88-2-lts      | 4         | 0.66%   |
| 5.10.15-arch1-1    | 4         | 0.66%   |
| 5.9.8-arch1-1      | 3         | 0.5%    |
| 5.9.2-arch1-1      | 3         | 0.5%    |
| 5.8.5-arch1-1      | 3         | 0.5%    |
| 5.8.10-arch1-1     | 3         | 0.5%    |
| 5.7.6-arch1-1      | 3         | 0.5%    |
| 5.18.9-arch1-1     | 3         | 0.5%    |
| 5.18.6-arch1-1     | 3         | 0.5%    |
| 5.18.12-zen1-1-zen | 3         | 0.5%    |
| 5.18.1-zen1-1-zen  | 3         | 0.5%    |
| 5.17.9-zen1-1-zen  | 3         | 0.5%    |
| 5.17.7-arch1-1     | 3         | 0.5%    |
| 5.17.5-zen1-1-zen  | 3         | 0.5%    |
| 5.17.3-zen1-1-zen  | 3         | 0.5%    |
| 5.17.3-arch1-1     | 3         | 0.5%    |
| 5.16.3-arch1-1     | 3         | 0.5%    |
| 5.16.16-zen1-1-zen | 3         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.12 | 28        | 4.64%   |
| 5.17.1  | 15        | 2.49%   |
| 5.17.5  | 14        | 2.32%   |
| 5.13.13 | 12        | 1.99%   |
| 5.18.12 | 11        | 1.82%   |
| 5.17.9  | 11        | 1.82%   |
| 5.14.9  | 10        | 1.66%   |
| 5.15.7  | 9         | 1.49%   |
| 5.15.4  | 9         | 1.49%   |
| 5.15.10 | 9         | 1.49%   |
| 5.11.11 | 9         | 1.49%   |
| 5.9.1   | 8         | 1.33%   |
| 5.16.16 | 8         | 1.33%   |
| 5.15.2  | 8         | 1.33%   |
| 5.12.13 | 8         | 1.33%   |
| 5.11.16 | 8         | 1.33%   |
| 5.9.14  | 7         | 1.16%   |
| 5.8.5   | 7         | 1.16%   |
| 5.18.1  | 7         | 1.16%   |
| 5.16.4  | 7         | 1.16%   |
| 5.16.2  | 7         | 1.16%   |
| 5.16.10 | 7         | 1.16%   |
| 5.7.7   | 6         | 1%      |
| 5.18.3  | 6         | 1%      |
| 5.17.4  | 6         | 1%      |
| 5.17.3  | 6         | 1%      |
| 5.16.8  | 6         | 1%      |
| 5.15.6  | 6         | 1%      |
| 5.15.11 | 6         | 1%      |
| 5.14.8  | 6         | 1%      |
| 5.14.2  | 6         | 1%      |
| 5.14.14 | 6         | 1%      |
| 5.12.5  | 6         | 1%      |
| 5.12.14 | 6         | 1%      |
| 5.9.8   | 5         | 0.83%   |
| 5.7.8   | 5         | 0.83%   |
| 5.7.12  | 5         | 0.83%   |
| 5.18.5  | 5         | 0.83%   |
| 5.16.14 | 5         | 0.83%   |
| 5.15.8  | 5         | 0.83%   |
| 5.14.6  | 5         | 0.83%   |
| 5.13.4  | 5         | 0.83%   |
| 5.10.88 | 5         | 0.83%   |
| 5.9.10  | 4         | 0.66%   |
| 5.8.10  | 4         | 0.66%   |
| 5.18.7  | 4         | 0.66%   |
| 5.16.13 | 4         | 0.66%   |
| 5.16.1  | 4         | 0.66%   |
| 5.15.13 | 4         | 0.66%   |
| 5.14.16 | 4         | 0.66%   |
| 5.14.11 | 4         | 0.66%   |
| 5.13.9  | 4         | 0.66%   |
| 5.13.12 | 4         | 0.66%   |
| 5.13.10 | 4         | 0.66%   |
| 5.12.15 | 4         | 0.66%   |
| 5.11.14 | 4         | 0.66%   |
| 5.10.15 | 4         | 0.66%   |
| 5.9.2   | 3         | 0.5%    |
| 5.8.14  | 3         | 0.5%    |
| 5.8.12  | 3         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 112       | 19.11%  |
| 5.16    | 66        | 11.26%  |
| 5.17    | 63        | 10.75%  |
| 5.14    | 52        | 8.87%   |
| 5.18    | 47        | 8.02%   |
| 5.12    | 38        | 6.48%   |
| 5.10    | 38        | 6.48%   |
| 5.11    | 37        | 6.31%   |
| 5.9     | 35        | 5.97%   |
| 5.13    | 35        | 5.97%   |
| 5.8     | 24        | 4.1%    |
| 5.7     | 21        | 3.58%   |
| 5.4     | 7         | 1.19%   |
| 5.6     | 5         | 0.85%   |
| 5.5     | 2         | 0.34%   |
| 4.19    | 2         | 0.34%   |
| 5.2     | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 527       | 99.81%  |
| aarch64 | 1         | 0.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 169       | 30.51%  |
| GNOME           | 134       | 24.19%  |
| XFCE            | 113       | 20.4%   |
| X-Cinnamon      | 27        | 4.87%   |
| KDE             | 22        | 3.97%   |
| i3              | 17        | 3.07%   |
| Cinnamon        | 14        | 2.53%   |
| Budgie          | 12        | 2.17%   |
| Unknown         | 11        | 1.99%   |
| MATE            | 7         | 1.26%   |
| LXQt            | 6         | 1.08%   |
| sway            | 5         | 0.9%    |
| GNOME Flashback | 4         | 0.72%   |
| Deepin          | 4         | 0.72%   |
| awesome         | 3         | 0.54%   |
| bspwm           | 2         | 0.36%   |
| LXDE            | 1         | 0.18%   |
| LeftWM          | 1         | 0.18%   |
| jwm             | 1         | 0.18%   |
| herbstluftwm    | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 423       | 78.19%  |
| Wayland | 94        | 17.38%  |
| Tty     | 14        | 2.59%   |
| Unknown | 9         | 1.66%   |
| Web     | 1         | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 156       | 28.73%  |
| SDDM    | 128       | 23.57%  |
| Unknown | 128       | 23.57%  |
| GDM     | 83        | 15.29%  |
| TDM     | 48        | 8.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 267       | 50.38%  |
| en_GB   | 39        | 7.36%   |
| de_DE   | 30        | 5.66%   |
| en_CA   | 24        | 4.53%   |
| it_IT   | 17        | 3.21%   |
| fr_FR   | 16        | 3.02%   |
| en_IN   | 11        | 2.08%   |
| pl_PL   | 10        | 1.89%   |
| ru_RU   | 9         | 1.7%    |
| en_AU   | 9         | 1.7%    |
| Unknown | 9         | 1.7%    |
| nl_NL   | 6         | 1.13%   |
| es_AR   | 6         | 1.13%   |
| pt_BR   | 5         | 0.94%   |
| es_ES   | 5         | 0.94%   |
| en_AG   | 5         | 0.94%   |
| tr_TR   | 4         | 0.75%   |
| sv_SE   | 4         | 0.75%   |
| fi_FI   | 4         | 0.75%   |
| es_MX   | 4         | 0.75%   |
| en_PH   | 4         | 0.75%   |
| en_NZ   | 4         | 0.75%   |
| en_DK   | 4         | 0.75%   |
| nl_BE   | 3         | 0.57%   |
| de_AT   | 3         | 0.57%   |
| pt_PT   | 2         | 0.38%   |
| hu_HU   | 2         | 0.38%   |
| en_ZA   | 2         | 0.38%   |
| en_HK   | 2         | 0.38%   |
| de_CH   | 2         | 0.38%   |
| cs_CZ   | 2         | 0.38%   |
| sl_SI   | 1         | 0.19%   |
| sk_SK   | 1         | 0.19%   |
| ru_UA   | 1         | 0.19%   |
| id_ID   | 1         | 0.19%   |
| hr_HR   | 1         | 0.19%   |
| fr_CA   | 1         | 0.19%   |
| es_US   | 1         | 0.19%   |
| es_PY   | 1         | 0.19%   |
| es_GT   | 1         | 0.19%   |
| es_CR   | 1         | 0.19%   |
| eo      | 1         | 0.19%   |
| en_SG   | 1         | 0.19%   |
| en_MY   | 1         | 0.19%   |
| en_IL   | 1         | 0.19%   |
| en_FI   | 1         | 0.19%   |
| an_ES   | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 352       | 65.67%  |
| BIOS | 184       | 34.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 385       | 72.5%   |
| Btrfs   | 129       | 24.29%  |
| Overlay | 7         | 1.32%   |
| Xfs     | 4         | 0.75%   |
| F2fs    | 2         | 0.38%   |
| Unknown | 2         | 0.38%   |
| XXX4    | 1         | 0.19%   |
| Ext2    | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 356       | 66.67%  |
| Unknown | 137       | 25.66%  |
| MBR     | 41        | 7.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 455       | 85.69%  |
| Yes       | 76        | 14.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 365       | 67.72%  |
| Yes       | 174       | 32.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 103       | 19.51%  |
| ASUSTek Computer    | 100       | 18.94%  |
| Hewlett-Packard     | 57        | 10.8%   |
| Dell                | 56        | 10.61%  |
| Gigabyte Technology | 46        | 8.71%   |
| MSI                 | 43        | 8.14%   |
| Acer                | 25        | 4.73%   |
| ASRock              | 19        | 3.6%    |
| Apple               | 11        | 2.08%   |
| Microsoft           | 8         | 1.52%   |
| HUAWEI              | 7         | 1.33%   |
| Samsung Electronics | 5         | 0.95%   |
| Unknown             | 4         | 0.76%   |
| Toshiba             | 3         | 0.57%   |
| Timi                | 3         | 0.57%   |
| Google              | 3         | 0.57%   |
| ZOTAC               | 2         | 0.38%   |
| TrekStor            | 2         | 0.38%   |
| Schenker            | 2         | 0.38%   |
| Notebook            | 2         | 0.38%   |
| Intel               | 2         | 0.38%   |
| Fujitsu             | 2         | 0.38%   |
| Biostar             | 2         | 0.38%   |
| AMI                 | 2         | 0.38%   |
| UMAX                | 1         | 0.19%   |
| TUXEDO              | 1         | 0.19%   |
| Sony                | 1         | 0.19%   |
| Shinelon Computer   | 1         | 0.19%   |
| Razer               | 1         | 0.19%   |
| Radxa               | 1         | 0.19%   |
| Positivo            | 1         | 0.19%   |
| Pine Microsystems   | 1         | 0.19%   |
| Packard Bell        | 1         | 0.19%   |
| LG Electronics      | 1         | 0.19%   |
| LattePanda          | 1         | 0.19%   |
| ILLEGEAR            | 1         | 0.19%   |
| HONOR               | 1         | 0.19%   |
| Framework           | 1         | 0.19%   |
| Eluktronics         | 1         | 0.19%   |
| Dynabook            | 1         | 0.19%   |
| Chuwi               | 1         | 0.19%   |
| BESSTAR Tech        | 1         | 0.19%   |
| Alienware           | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 6         | 1.14%   |
| MSI MS-7C37                           | 5         | 0.95%   |
| MSI MS-7C02                           | 4         | 0.76%   |
| ASUS ROG STRIX X570-E GAMING          | 4         | 0.76%   |
| Apple MacBookAir7,2                   | 4         | 0.76%   |
| Unknown                               | 4         | 0.76%   |
| MSI MS-7A38                           | 3         | 0.57%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.57%   |
| Gigabyte B550M AORUS PRO              | 3         | 0.57%   |
| ASUS TUF Gaming X570-PLUS             | 3         | 0.57%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 3         | 0.57%   |
| ASRock B450M Pro4                     | 3         | 0.57%   |
| Timi A35S                             | 2         | 0.38%   |
| MSI MS-7C91                           | 2         | 0.38%   |
| MSI MS-7C84                           | 2         | 0.38%   |
| MSI MS-7B86                           | 2         | 0.38%   |
| MSI MS-7850                           | 2         | 0.38%   |
| MSI MS-7798                           | 2         | 0.38%   |
| Microsoft Surface Laptop Go           | 2         | 0.38%   |
| Microsoft Surface Go                  | 2         | 0.38%   |
| Lenovo Yoga 6 13ALC6 82ND             | 2         | 0.38%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB  | 2         | 0.38%   |
| Lenovo IdeaPad Flex-14API 81SS        | 2         | 0.38%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 2         | 0.38%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 2         | 0.38%   |
| HUAWEI MACH-WX9                       | 2         | 0.38%   |
| HUAWEI KLVL-WXX9                      | 2         | 0.38%   |
| HP Z230 Tower Workstation             | 2         | 0.38%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 2         | 0.38%   |
| HP Notebook                           | 2         | 0.38%   |
| HP ENVY x360 Convertible 15-ee0xxx    | 2         | 0.38%   |
| HP ENVY Laptop 13-ba0xxx              | 2         | 0.38%   |
| HP EliteBook 745 G6                   | 2         | 0.38%   |
| HP 255 G7 Notebook PC                 | 2         | 0.38%   |
| HP 250 G7 Notebook PC                 | 2         | 0.38%   |
| Gigabyte H110M-S2                     | 2         | 0.38%   |
| Gigabyte B550 AORUS ELITE V2          | 2         | 0.38%   |
| Gigabyte B450M DS3H                   | 2         | 0.38%   |
| Gigabyte B450 AORUS ELITE             | 2         | 0.38%   |
| Dell XPS 15 7590                      | 2         | 0.38%   |
| Dell OptiPlex 3020                    | 2         | 0.38%   |
| Dell Latitude E6440                   | 2         | 0.38%   |
| Dell Inspiron 3542                    | 2         | 0.38%   |
| Dell G7 7588                          | 2         | 0.38%   |
| Dell G3 3500                          | 2         | 0.38%   |
| Biostar G31-M7 TE                     | 2         | 0.38%   |
| ASUS ROG Zephyrus M16 GU603HR_GU603HR | 2         | 0.38%   |
| ASUS ROG Zephyrus G15 GA503QR_GA503QR | 2         | 0.38%   |
| ASUS ROG CROSSHAIR VIII DARK HERO     | 2         | 0.38%   |
| ASUS K30AD_M31AD_M51AD                | 2         | 0.38%   |
| ASUS GL753VE                          | 2         | 0.38%   |
| ASUS G752VT                           | 2         | 0.38%   |
| ASRock B550M Steel Legend             | 2         | 0.38%   |
| ASRock B450 Pro4                      | 2         | 0.38%   |
| Acer Aspire A515-43                   | 2         | 0.38%   |
| ZOTAC ZBOXNANO-CI520NANO/CI540NANO    | 1         | 0.19%   |
| ZOTAC ZBOX-ECM73070C/53060C           | 1         | 0.19%   |
| UMAX J42 Nano                         | 1         | 0.19%   |
| TUXEDO Pulse 15 Gen1                  | 1         | 0.19%   |
| TrekStor Primebook P14                | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 45        | 8.52%   |
| ASUS ROG             | 30        | 5.68%   |
| Lenovo IdeaPad       | 22        | 4.17%   |
| Dell Latitude        | 17        | 3.22%   |
| Dell Inspiron        | 15        | 2.84%   |
| ASUS TUF             | 14        | 2.65%   |
| Acer Aspire          | 14        | 2.65%   |
| HP Pavilion          | 12        | 2.27%   |
| Lenovo Yoga          | 11        | 2.08%   |
| Microsoft Surface    | 8         | 1.52%   |
| HP Laptop            | 8         | 1.52%   |
| HP ENVY              | 8         | 1.52%   |
| HP EliteBook         | 8         | 1.52%   |
| ASUS PRIME           | 7         | 1.33%   |
| Dell Precision       | 6         | 1.14%   |
| Dell OptiPlex        | 6         | 1.14%   |
| ASUS All             | 6         | 1.14%   |
| MSI MS-7C37          | 5         | 0.95%   |
| Gigabyte B450        | 5         | 0.95%   |
| Dell XPS             | 5         | 0.95%   |
| MSI MS-7C02          | 4         | 0.76%   |
| Lenovo ThinkBook     | 4         | 0.76%   |
| Lenovo IdeaCentre    | 4         | 0.76%   |
| Gigabyte X570        | 4         | 0.76%   |
| Gigabyte B550M       | 4         | 0.76%   |
| Gigabyte B550        | 4         | 0.76%   |
| ASUS VivoBook        | 4         | 0.76%   |
| ASRock B450          | 4         | 0.76%   |
| Apple MacBookAir7    | 4         | 0.76%   |
| Acer Swift           | 4         | 0.76%   |
| Unknown              | 4         | 0.76%   |
| Toshiba Satellite    | 3         | 0.57%   |
| MSI MS-7A38          | 3         | 0.57%   |
| Lenovo ThinkCentre   | 3         | 0.57%   |
| Lenovo Legion        | 3         | 0.57%   |
| HP 255               | 3         | 0.57%   |
| Gigabyte B450M       | 3         | 0.57%   |
| Dell G3              | 3         | 0.57%   |
| ASRock B550M         | 3         | 0.57%   |
| ASRock B450M         | 3         | 0.57%   |
| Timi A35S            | 2         | 0.38%   |
| Schenker XMG         | 2         | 0.38%   |
| MSI MS-7C91          | 2         | 0.38%   |
| MSI MS-7C84          | 2         | 0.38%   |
| MSI MS-7B86          | 2         | 0.38%   |
| MSI MS-7850          | 2         | 0.38%   |
| MSI MS-7798          | 2         | 0.38%   |
| MSI Modern           | 2         | 0.38%   |
| Lenovo IdeaPadFlex   | 2         | 0.38%   |
| HUAWEI MACH-WX9      | 2         | 0.38%   |
| HUAWEI KLVL-WXX9     | 2         | 0.38%   |
| HP Z230              | 2         | 0.38%   |
| HP Notebook          | 2         | 0.38%   |
| HP 250               | 2         | 0.38%   |
| Gigabyte Z97X-Gaming | 2         | 0.38%   |
| Gigabyte Z390        | 2         | 0.38%   |
| Gigabyte H110M-S2    | 2         | 0.38%   |
| Fujitsu CELSIUS      | 2         | 0.38%   |
| Dell G7              | 2         | 0.38%   |
| Biostar G31-M7       | 2         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 76        | 14.39%  |
| 2020    | 74        | 14.02%  |
| 2018    | 73        | 13.83%  |
| 2021    | 70        | 13.26%  |
| 2017    | 39        | 7.39%   |
| 2013    | 34        | 6.44%   |
| 2016    | 31        | 5.87%   |
| 2014    | 29        | 5.49%   |
| 2015    | 27        | 5.11%   |
| 2012    | 27        | 5.11%   |
| 2011    | 16        | 3.03%   |
| 2010    | 8         | 1.52%   |
| 2009    | 8         | 1.52%   |
| 2008    | 8         | 1.52%   |
| 2007    | 4         | 0.76%   |
| 2022    | 3         | 0.57%   |
| Unknown | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 289       | 54.73%  |
| Desktop     | 189       | 35.8%   |
| Convertible | 26        | 4.92%   |
| Tablet      | 9         | 1.7%    |
| All in one  | 9         | 1.7%    |
| Mini pc     | 5         | 0.95%   |
| Server      | 1         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 527       | 99.81%  |
| Enabled  | 1         | 0.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 525       | 99.43%  |
| Yes  | 3         | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 135       | 25.38%  |
| 4.01-8.0    | 126       | 23.68%  |
| 8.01-16.0   | 116       | 21.8%   |
| 32.01-64.0  | 76        | 14.29%  |
| 3.01-4.0    | 47        | 8.83%   |
| 24.01-32.0  | 16        | 3.01%   |
| 64.01-256.0 | 13        | 2.44%   |
| 1.01-2.0    | 3         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 158       | 27.62%  |
| 1.01-2.0   | 142       | 24.83%  |
| 4.01-8.0   | 117       | 20.45%  |
| 3.01-4.0   | 94        | 16.43%  |
| 8.01-16.0  | 29        | 5.07%   |
| 0.51-1.0   | 23        | 4.02%   |
| 16.01-24.0 | 5         | 0.87%   |
| 24.01-32.0 | 2         | 0.35%   |
| 0.01-0.5   | 2         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 274       | 50.37%  |
| 2      | 147       | 27.02%  |
| 3      | 53        | 9.74%   |
| 4      | 37        | 6.8%    |
| 5      | 22        | 4.04%   |
| 6      | 4         | 0.74%   |
| 7      | 3         | 0.55%   |
| 0      | 2         | 0.37%   |
| 9      | 1         | 0.18%   |
| 8      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 415       | 78.15%  |
| Yes       | 116       | 21.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 435       | 82.08%  |
| No        | 95        | 17.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 432       | 81.2%   |
| No        | 100       | 18.8%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 402       | 75.42%  |
| No        | 131       | 24.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 128       | 24.11%  |
| Germany             | 49        | 9.23%   |
| France              | 27        | 5.08%   |
| Canada              | 26        | 4.9%    |
| Italy               | 24        | 4.52%   |
| Poland              | 18        | 3.39%   |
| UK                  | 17        | 3.2%    |
| India               | 16        | 3.01%   |
| Netherlands         | 15        | 2.82%   |
| Brazil              | 14        | 2.64%   |
| Russia              | 11        | 2.07%   |
| Finland             | 10        | 1.88%   |
| Belgium             | 10        | 1.88%   |
| Australia           | 10        | 1.88%   |
| Turkey              | 9         | 1.69%   |
| Spain               | 9         | 1.69%   |
| Argentina           | 9         | 1.69%   |
| Sweden              | 8         | 1.51%   |
| Mexico              | 8         | 1.51%   |
| Austria             | 7         | 1.32%   |
| Indonesia           | 6         | 1.13%   |
| Switzerland         | 5         | 0.94%   |
| Norway              | 5         | 0.94%   |
| Czechia             | 5         | 0.94%   |
| Portugal            | 4         | 0.75%   |
| Philippines         | 4         | 0.75%   |
| New Zealand         | 4         | 0.75%   |
| Hong Kong           | 4         | 0.75%   |
| Greece              | 4         | 0.75%   |
| Vietnam             | 3         | 0.56%   |
| Ukraine             | 3         | 0.56%   |
| Slovenia            | 3         | 0.56%   |
| Romania             | 3         | 0.56%   |
| Malaysia            | 3         | 0.56%   |
| Hungary             | 3         | 0.56%   |
| Denmark             | 3         | 0.56%   |
| Bahrain             | 3         | 0.56%   |
| Thailand            | 2         | 0.38%   |
| South Korea         | 2         | 0.38%   |
| South Africa        | 2         | 0.38%   |
| Slovakia            | 2         | 0.38%   |
| Singapore           | 2         | 0.38%   |
| Saudi Arabia        | 2         | 0.38%   |
| Georgia             | 2         | 0.38%   |
| Croatia             | 2         | 0.38%   |
| Colombia            | 2         | 0.38%   |
| Bulgaria            | 2         | 0.38%   |
| Bangladesh          | 2         | 0.38%   |
| Uruguay             | 1         | 0.19%   |
| Trinidad and Tobago | 1         | 0.19%   |
| Taiwan              | 1         | 0.19%   |
| Sri Lanka           | 1         | 0.19%   |
| Serbia              | 1         | 0.19%   |
| Puerto Rico         | 1         | 0.19%   |
| Paraguay            | 1         | 0.19%   |
| Pakistan            | 1         | 0.19%   |
| Nepal               | 1         | 0.19%   |
| Morocco             | 1         | 0.19%   |
| Lithuania           | 1         | 0.19%   |
| Latvia              | 1         | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 9         | 1.64%   |
| Berlin            | 8         | 1.45%   |
| Toms River        | 7         | 1.27%   |
| Amsterdam         | 6         | 1.09%   |
| Sydney            | 5         | 0.91%   |
| St Petersburg     | 5         | 0.91%   |
| Helsinki          | 5         | 0.91%   |
| Warsaw            | 4         | 0.73%   |
| Victoria          | 4         | 0.73%   |
| Turin             | 4         | 0.73%   |
| Toronto           | 4         | 0.73%   |
| Jacksonville      | 4         | 0.73%   |
| Hamburg           | 4         | 0.73%   |
| Barberton         | 4         | 0.73%   |
| Zurich            | 3         | 0.55%   |
| Wroclaw           | 3         | 0.55%   |
| Villa Ballester   | 3         | 0.55%   |
| Paris             | 3         | 0.55%   |
| Ottawa            | 3         | 0.55%   |
| Oldenburg         | 3         | 0.55%   |
| Moscow            | 3         | 0.55%   |
| Manama            | 3         | 0.55%   |
| Lyon              | 3         | 0.55%   |
| London            | 3         | 0.55%   |
| Istanbul          | 3         | 0.55%   |
| Frankfurt am Main | 3         | 0.55%   |
| Brussels          | 3         | 0.55%   |
| Zapopan           | 2         | 0.36%   |
| Vienna            | 2         | 0.36%   |
| Turku             | 2         | 0.36%   |
| Tuen Mun          | 2         | 0.36%   |
| Sterling          | 2         | 0.36%   |
| Sofia             | 2         | 0.36%   |
| Snohomish         | 2         | 0.36%   |
| Singapore         | 2         | 0.36%   |
| Severna Park      | 2         | 0.36%   |
| Schiedam          | 2         | 0.36%   |
| Rotterdam         | 2         | 0.36%   |
| Pune              | 2         | 0.36%   |
| Prague            | 2         | 0.36%   |
| Portland          | 2         | 0.36%   |
| Porth             | 2         | 0.36%   |
| Phoenix           | 2         | 0.36%   |
| Orlando           | 2         | 0.36%   |
| Milan             | 2         | 0.36%   |
| Miami             | 2         | 0.36%   |
| Mexico City       | 2         | 0.36%   |
| Mannheim          | 2         | 0.36%   |
| Madrid            | 2         | 0.36%   |
| Lille             | 2         | 0.36%   |
| Leipzig           | 2         | 0.36%   |
| K'alak'i T'bilisi | 2         | 0.36%   |
| Jakarta           | 2         | 0.36%   |
| Innsbruck         | 2         | 0.36%   |
| Houston           | 2         | 0.36%   |
| Ho Chi Minh City  | 2         | 0.36%   |
| Geesteren         | 2         | 0.36%   |
| Gdynia            | 2         | 0.36%   |
| Florence          | 2         | 0.36%   |
| Elk Grove         | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 175       | 269    | 19.98%  |
| WDC                            | 122       | 186    | 13.93%  |
| Seagate                        | 112       | 151    | 12.79%  |
| Kingston                       | 54        | 83     | 6.16%   |
| Toshiba                        | 41        | 48     | 4.68%   |
| Crucial                        | 40        | 59     | 4.57%   |
| SanDisk                        | 37        | 44     | 4.22%   |
| SK hynix                       | 28        | 29     | 3.2%    |
| Intel                          | 26        | 35     | 2.97%   |
| Unknown                        | 18        | 26     | 2.05%   |
| Phison                         | 17        | 18     | 1.94%   |
| HGST                           | 16        | 19     | 1.83%   |
| Micron Technology              | 14        | 16     | 1.6%    |
| Hitachi                        | 13        | 13     | 1.48%   |
| A-DATA Technology              | 12        | 19     | 1.37%   |
| KIOXIA                         | 9         | 9      | 1.03%   |
| Apple                          | 8         | 11     | 0.91%   |
| Corsair                        | 7         | 7      | 0.8%    |
| SPCC                           | 6         | 6      | 0.68%   |
| PNY                            | 6         | 6      | 0.68%   |
| China                          | 6         | 6      | 0.68%   |
| XPG                            | 5         | 5      | 0.57%   |
| LITEONIT                       | 5         | 6      | 0.57%   |
| Transcend                      | 4         | 4      | 0.46%   |
| OCZ                            | 4         | 4      | 0.46%   |
| Intenso                        | 4         | 5      | 0.46%   |
| Gigabyte Technology            | 4         | 6      | 0.46%   |
| Mushkin                        | 3         | 3      | 0.34%   |
| Maxone                         | 3         | 3      | 0.34%   |
| JMicron Technology             | 3         | 3      | 0.34%   |
| AMicro                         | 3         | 4      | 0.34%   |
| WDC WDS                        | 2         | 2      | 0.23%   |
| USB3.1                         | 2         | 3      | 0.23%   |
| StoreJet                       | 2         | 2      | 0.23%   |
| SSSTC                          | 2         | 2      | 0.23%   |
| Solid State Storage Technology | 2         | 3      | 0.23%   |
| SABRENT                        | 2         | 2      | 0.23%   |
| Plextor                        | 2         | 3      | 0.23%   |
| Patriot                        | 2         | 4      | 0.23%   |
| Netac                          | 2         | 2      | 0.23%   |
| LITEON                         | 2         | 3      | 0.23%   |
| Lexar                          | 2         | 2      | 0.23%   |
| Leven                          | 2         | 3      | 0.23%   |
| KingSpec                       | 2         | 2      | 0.23%   |
| HFS256G3                       | 2         | 2      | 0.23%   |
| Fujitsu                        | 2         | 2      | 0.23%   |
| Zheino                         | 1         | 1      | 0.11%   |
| V-GeN                          | 1         | 1      | 0.11%   |
| USB3.0                         | 1         | 1      | 0.11%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.11%   |
| UMIS                           | 1         | 1      | 0.11%   |
| UMAX                           | 1         | 1      | 0.11%   |
| Teclast                        | 1         | 3      | 0.11%   |
| Team                           | 1         | 2      | 0.11%   |
| T-FORCE                        | 1         | 1      | 0.11%   |
| RSH-319                        | 1         | 2      | 0.11%   |
| Realtek Semiconductor          | 1         | 1      | 0.11%   |
| Realtek                        | 1         | 1      | 0.11%   |
| Pioneer                        | 1         | 3      | 0.11%   |
| PI-041                         | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB           | 13        | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB    | 11        | 1.1%    |
| Seagate ST2000DM008-2FR102 2TB    | 10        | 1%      |
| Samsung SSD 860 EVO 500GB         | 10        | 1%      |
| Samsung SSD 850 EVO 500GB         | 10        | 1%      |
| Samsung SSD 850 EVO 250GB         | 9         | 0.9%    |
| Kingston SA400S37120G 120GB SSD   | 9         | 0.9%    |
| Crucial CT500MX500SSD1 500GB      | 9         | 0.9%    |
| WDC WD10EZEX-08WN4A0 1TB          | 8         | 0.8%    |
| Seagate ST4000DM004-2CV104 4TB    | 8         | 0.8%    |
| Samsung SSD 970 EVO 500GB         | 8         | 0.8%    |
| Samsung SSD 860 EVO 250GB         | 8         | 0.8%    |
| Kingston SA400S37240G 240GB SSD   | 8         | 0.8%    |
| Samsung NVMe SSD Drive 1TB        | 7         | 0.7%    |
| HGST HTS721010A9E630 1TB          | 7         | 0.7%    |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 6         | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB          | 6         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB   | 6         | 0.6%    |
| Seagate ST2000DM006-2DM164 2TB    | 6         | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB    | 6         | 0.6%    |
| Unknown SD/MMC/MS PRO 64GB        | 5         | 0.5%    |
| Seagate Expansion Desk 4TB        | 5         | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB    | 5         | 0.5%    |
| Samsung SSD 970 EVO 1TB           | 5         | 0.5%    |
| Samsung SSD 870 QVO 1TB           | 5         | 0.5%    |
| Samsung NVMe SSD Drive 512GB      | 5         | 0.5%    |
| Kingston SA400S37480G 480GB SSD   | 5         | 0.5%    |
| Crucial CT1000MX500SSD1 1TB       | 5         | 0.5%    |
| WDC WDS100T3X0C-00SJG0 1TB        | 4         | 0.4%    |
| WDC WDS100T2B0C-00PXH0 1TB        | 4         | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB          | 4         | 0.4%    |
| SK hynix HFM001TD3JX013N 1TB      | 4         | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB    | 4         | 0.4%    |
| SanDisk NVMe SSD Drive 256GB      | 4         | 0.4%    |
| Samsung SSD 980 500GB             | 4         | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB      | 4         | 0.4%    |
| Samsung SSD 870 EVO 250GB         | 4         | 0.4%    |
| Samsung SSD 840 EVO 120GB         | 4         | 0.4%    |
| Samsung NVMe SSD Drive 256GB      | 4         | 0.4%    |
| Samsung NVMe SSD Drive 250GB      | 4         | 0.4%    |
| KIOXIA KBG40ZNV512G 512GB         | 4         | 0.4%    |
| Kingston NVMe SSD Drive 1TB       | 4         | 0.4%    |
| Intel SSDPEKNW512G8H 512GB        | 4         | 0.4%    |
| Intel NVMe SSD Drive 512GB        | 4         | 0.4%    |
| Crucial CT240BX500SSD1 240GB      | 4         | 0.4%    |
| Crucial CT1000P1SSD8 1TB          | 4         | 0.4%    |
| Apple SSD SM0128G 121GB           | 4         | 0.4%    |
| WDC WDS500G3X0C-00SJG0 500GB      | 3         | 0.3%    |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 3         | 0.3%    |
| WDC WD40EZRZ-00GXCB0 4TB          | 3         | 0.3%    |
| WDC WD20EZRZ-00Z5HB0 2TB          | 3         | 0.3%    |
| WDC WD10SPZX-24Z10 1TB            | 3         | 0.3%    |
| WDC WD10EZEX-00RKKA0 1TB          | 3         | 0.3%    |
| Transcend TS240GMTS420S 240GB SSD | 3         | 0.3%    |
| Toshiba MQ04ABF100 1TB            | 3         | 0.3%    |
| Toshiba KBG30ZPZ128G 128GB        | 3         | 0.3%    |
| Toshiba HDWD110 1TB               | 3         | 0.3%    |
| Toshiba DT01ACA100 1TB            | 3         | 0.3%    |
| Seagate ST2000LM007-1R8174 2TB    | 3         | 0.3%    |
| Seagate ST2000DM001-1ER164 2TB    | 3         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 107       | 144    | 40.23%  |
| WDC                 | 81        | 114    | 30.45%  |
| Toshiba             | 23        | 24     | 8.65%   |
| HGST                | 16        | 19     | 6.02%   |
| Hitachi             | 13        | 13     | 4.89%   |
| Samsung Electronics | 6         | 12     | 2.26%   |
| Unknown             | 5         | 5      | 1.88%   |
| Maxone              | 3         | 3      | 1.13%   |
| SABRENT             | 2         | 2      | 0.75%   |
| Fujitsu             | 2         | 2      | 0.75%   |
| StoreJet            | 1         | 1      | 0.38%   |
| RSH-319             | 1         | 2      | 0.38%   |
| PI-041              | 1         | 1      | 0.38%   |
| Maxtor              | 1         | 1      | 0.38%   |
| JMicron Technology  | 1         | 1      | 0.38%   |
| HPE                 | 1         | 1      | 0.38%   |
| Generic-            | 1         | 1      | 0.38%   |
| ASMedia             | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 106       | 146    | 31.36%  |
| Kingston            | 37        | 60     | 10.95%  |
| Crucial             | 33        | 43     | 9.76%   |
| SanDisk             | 24        | 29     | 7.1%    |
| WDC                 | 22        | 31     | 6.51%   |
| Micron Technology   | 8         | 10     | 2.37%   |
| Toshiba             | 7         | 9      | 2.07%   |
| Intel               | 7         | 10     | 2.07%   |
| Apple               | 7         | 10     | 2.07%   |
| China               | 6         | 6      | 1.78%   |
| A-DATA Technology   | 6         | 7      | 1.78%   |
| SK hynix            | 5         | 5      | 1.48%   |
| LITEONIT            | 5         | 6      | 1.48%   |
| Transcend           | 4         | 4      | 1.18%   |
| SPCC                | 4         | 4      | 1.18%   |
| OCZ                 | 4         | 4      | 1.18%   |
| Intenso             | 4         | 5      | 1.18%   |
| PNY                 | 3         | 3      | 0.89%   |
| Mushkin             | 3         | 3      | 0.89%   |
| Gigabyte Technology | 3         | 4      | 0.89%   |
| Corsair             | 3         | 3      | 0.89%   |
| WDC WDS             | 2         | 2      | 0.59%   |
| Seagate             | 2         | 2      | 0.59%   |
| Patriot             | 2         | 4      | 0.59%   |
| Leven               | 2         | 3      | 0.59%   |
| KingSpec            | 2         | 2      | 0.59%   |
| Zheino              | 1         | 1      | 0.3%    |
| V-GeN               | 1         | 1      | 0.3%    |
| USB3.0              | 1         | 1      | 0.3%    |
| Unknown             | 1         | 2      | 0.3%    |
| UMAX                | 1         | 1      | 0.3%    |
| Teclast             | 1         | 3      | 0.3%    |
| Team                | 1         | 2      | 0.3%    |
| StoreJet            | 1         | 1      | 0.3%    |
| Plextor             | 1         | 2      | 0.3%    |
| Pioneer             | 1         | 3      | 0.3%    |
| Phison              | 1         | 1      | 0.3%    |
| Netac               | 1         | 1      | 0.3%    |
| LITEON              | 1         | 1      | 0.3%    |
| Lexar               | 1         | 1      | 0.3%    |
| LDLC                | 1         | 1      | 0.3%    |
| Kingmax             | 1         | 2      | 0.3%    |
| KingFast            | 1         | 1      | 0.3%    |
| KingDian            | 1         | 1      | 0.3%    |
| KINGBANK            | 1         | 1      | 0.3%    |
| Imation             | 1         | 1      | 0.3%    |
| Hewlett-Packard     | 1         | 1      | 0.3%    |
| GOODRAM             | 1         | 1      | 0.3%    |
| FORESEE             | 1         | 1      | 0.3%    |
| Drevo               | 1         | 1      | 0.3%    |
| CT480BX5            | 1         | 1      | 0.3%    |
| ASMT                | 1         | 2      | 0.3%    |
| Apacer              | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 271       | 451    | 35.15%  |
| NVMe    | 254       | 354    | 32.94%  |
| HDD     | 219       | 347    | 28.4%   |
| Unknown | 15        | 19     | 1.95%   |
| MMC     | 12        | 18     | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 363       | 749    | 53.62%  |
| NVMe | 252       | 350    | 37.22%  |
| SAS  | 50        | 72     | 7.39%   |
| MMC  | 12        | 18     | 1.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 263       | 437    | 48.7%   |
| 0.51-1.0   | 175       | 229    | 32.41%  |
| 1.01-2.0   | 54        | 67     | 10%     |
| 3.01-4.0   | 24        | 37     | 4.44%   |
| 2.01-3.0   | 12        | 13     | 2.22%   |
| 4.01-10.0  | 8         | 10     | 1.48%   |
| 10.01-20.0 | 4         | 5      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 113       | 20.62%  |
| 251-500        | 102       | 18.61%  |
| 1001-2000      | 89        | 16.24%  |
| 501-1000       | 86        | 15.69%  |
| More than 3000 | 52        | 9.49%   |
| Unknown        | 37        | 6.75%   |
| 2001-3000      | 30        | 5.47%   |
| 51-100         | 19        | 3.47%   |
| 1-20           | 12        | 2.19%   |
| 21-50          | 8         | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 117       | 20.28%  |
| 101-250        | 96        | 16.64%  |
| 21-50          | 80        | 13.86%  |
| 51-100         | 75        | 13%     |
| 251-500        | 59        | 10.23%  |
| 501-1000       | 44        | 7.63%   |
| 1001-2000      | 42        | 7.28%   |
| Unknown        | 37        | 6.41%   |
| More than 3000 | 17        | 2.95%   |
| 2001-3000      | 10        | 1.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Hitachi HTS545050A7E380 500GB                    | 3         | 3      | 6.12%   |
| HGST HTS721010A9E630 1TB                         | 3         | 3      | 6.12%   |
| Samsung Electronics SSD 970 EVO 500GB            | 2         | 2      | 4.08%   |
| XPG GAMMIX S11 480GB                             | 1         | 1      | 2.04%   |
| WDC WD5000LPVT-22G33T0 500GB                     | 1         | 1      | 2.04%   |
| WDC WD5000AZRX-00A8LB0 500GB                     | 1         | 1      | 2.04%   |
| WDC WD40EFRX-68WT0N0 4TB                         | 1         | 2      | 2.04%   |
| WDC WD20EARX-00PASB0 2TB                         | 1         | 1      | 2.04%   |
| WDC WD2003FZEX-00Z4SA0 2TB                       | 1         | 1      | 2.04%   |
| WDC WD2002FYPS-01U1B0 2TB                        | 1         | 1      | 2.04%   |
| WDC WD10SPZX-24Z10T0 1TB                         | 1         | 1      | 2.04%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 2.04%   |
| WDC WD10EACS-00D6B1 1TB                          | 1         | 1      | 2.04%   |
| Transcend TS240GMTS420S 240GB SSD                | 1         | 1      | 2.04%   |
| Toshiba MK5055GSXF 500GB                         | 1         | 1      | 2.04%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD          | 1         | 1      | 2.04%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.04%   |
| SK hynix SC308 SATA 128GB SSD                    | 1         | 1      | 2.04%   |
| SK hynix HFS512G39TND-N210A 512GB SSD            | 1         | 1      | 2.04%   |
| Seagate ST9320325AS 320GB                        | 1         | 4      | 2.04%   |
| Seagate ST6000VX0023-2EF110 6TB                  | 1         | 1      | 2.04%   |
| Seagate ST500LX012-SSHD-8GB                      | 1         | 1      | 2.04%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.04%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 2.04%   |
| Seagate ST3320620AS 320GB                        | 1         | 1      | 2.04%   |
| Seagate ST1000LM049-2GH172 1TB                   | 1         | 1      | 2.04%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 2.04%   |
| SanDisk SDSSDA240G 240GB                         | 1         | 2      | 2.04%   |
| Samsung Electronics SSD 960 EVO 500GB            | 1         | 1      | 2.04%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.04%   |
| Samsung Electronics HD103SI 1TB                  | 1         | 1      | 2.04%   |
| OCZ VERTEX3 240GB SSD                            | 1         | 1      | 2.04%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 2.04%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 2.04%   |
| Intel SSDSCKKF256H6 SATA 256GB                   | 1         | 1      | 2.04%   |
| Hitachi HDT725025VLA380 250GB                    | 1         | 1      | 2.04%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 2.04%   |
| Fujitsu MHZ2320BH G2 320GB                       | 1         | 1      | 2.04%   |
| Drevo X1 SSD 120GB                               | 1         | 1      | 2.04%   |
| Crucial CT500MX500SSD1 500GB                     | 1         | 3      | 2.04%   |
| Crucial CT1050MX300SSD1 1TB                      | 1         | 1      | 2.04%   |
| Corsair Force LS SSD 120GB                       | 1         | 1      | 2.04%   |
| ASMT ASM1156-PM 120GB SSD                        | 1         | 2      | 2.04%   |
| Apple SSD SM256C 256GB                           | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 18.75%  |
| Seagate             | 6         | 10     | 12.5%   |
| Samsung Electronics | 5         | 5      | 10.42%  |
| Hitachi             | 4         | 4      | 8.33%   |
| HGST                | 4         | 4      | 8.33%   |
| Toshiba             | 3         | 3      | 6.25%   |
| SK hynix            | 2         | 2      | 4.17%   |
| SanDisk             | 2         | 3      | 4.17%   |
| Crucial             | 2         | 4      | 4.17%   |
| XPG                 | 1         | 1      | 2.08%   |
| Transcend           | 1         | 1      | 2.08%   |
| OCZ                 | 1         | 1      | 2.08%   |
| Micron Technology   | 1         | 1      | 2.08%   |
| Kingston            | 1         | 1      | 2.08%   |
| Intel               | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |
| Drevo               | 1         | 1      | 2.08%   |
| Corsair             | 1         | 1      | 2.08%   |
| ASMT                | 1         | 2      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 33.33%  |
| Seagate             | 6         | 10     | 22.22%  |
| Hitachi             | 4         | 4      | 14.81%  |
| HGST                | 4         | 4      | 14.81%  |
| Toshiba             | 2         | 2      | 7.41%   |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Fujitsu             | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 32     | 57.45%  |
| SSD  | 16        | 21     | 34.04%  |
| NVMe | 4         | 4      | 8.51%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HD252HJ 250GB | 1         | 1      | 33.33%  |
| LITEON CA3-8D512 512GB            | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| LITEON              | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 368       | 730    | 61.44%  |
| Detected | 182       | 398    | 30.38%  |
| Malfunc  | 46        | 57     | 7.68%   |
| Failed   | 3         | 4      | 0.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 289       | 39.43%  |
| AMD                            | 144       | 19.65%  |
| Samsung Electronics            | 90        | 12.28%  |
| SanDisk                        | 45        | 6.14%   |
| Phison Electronics             | 26        | 3.55%   |
| SK hynix                       | 22        | 3%      |
| Kingston Technology Company    | 18        | 2.46%   |
| ASMedia Technology             | 17        | 2.32%   |
| Toshiba America Info Systems   | 11        | 1.5%    |
| KIOXIA                         | 11        | 1.5%    |
| Micron/Crucial Technology      | 8         | 1.09%   |
| Micron Technology              | 7         | 0.95%   |
| ADATA Technology               | 7         | 0.95%   |
| Marvell Technology Group       | 6         | 0.82%   |
| Solid State Storage Technology | 5         | 0.68%   |
| Realtek Semiconductor          | 5         | 0.68%   |
| Nvidia                         | 4         | 0.55%   |
| JMicron Technology             | 4         | 0.55%   |
| Silicon Motion                 | 3         | 0.41%   |
| Seagate Technology             | 3         | 0.41%   |
| Union Memory (Shenzhen)        | 2         | 0.27%   |
| Lite-On Technology             | 2         | 0.27%   |
| LSI Logic / Symbios Logic      | 1         | 0.14%   |
| Lenovo                         | 1         | 0.14%   |
| Broadcom / LSI                 | 1         | 0.14%   |
| Apple                          | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 107       | 13.24%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 46        | 5.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 40        | 4.95%   |
| AMD 400 Series Chipset SATA Controller                                         | 36        | 4.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 25        | 3.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 2.97%   |
| Samsung NVMe SSD Controller 980                                                | 21        | 2.6%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 17        | 2.1%    |
| AMD 500 Series Chipset SATA Controller                                         | 17        | 2.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 15        | 1.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 13        | 1.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 13        | 1.61%   |
| Phison E12 NVMe Controller                                                     | 13        | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 1.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 1.49%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 11        | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 1.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 11        | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 10        | 1.24%   |
| Intel SSD 660P Series                                                          | 10        | 1.24%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 9         | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 1.11%   |
| Phison E16 PCIe4 NVMe Controller                                               | 9         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 1.11%   |
| SK hynix Gold P31 SSD                                                          | 8         | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 8         | 0.99%   |
| Micron Non-Volatile memory controller                                          | 7         | 0.87%   |
| Kingston Company A2000 NVMe SSD                                                | 7         | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 0.87%   |
| Kingston Company Company Non-Volatile memory controller                        | 6         | 0.74%   |
| Intel SATA Controller [RAID mode]                                              | 6         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 6         | 0.74%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 5         | 0.62%   |
| Solid State Storage Non-Volatile memory controller                             | 5         | 0.62%   |
| SK hynix Non-Volatile memory controller                                        | 5         | 0.62%   |
| SanDisk Non-Volatile memory controller                                         | 5         | 0.62%   |
| Samsung Electronics SATA controller                                            | 5         | 0.62%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 5         | 0.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 0.62%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 0.62%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.62%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 0.62%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5         | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 0.62%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.5%    |
| Samsung NVMe SSD Controller SM951/PM951                                        | 4         | 0.5%    |
| Realtek Realtek Non-Volatile memory controller                                 | 4         | 0.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 0.5%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 4         | 0.5%    |
| Intel Non-Volatile memory controller                                           | 4         | 0.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 0.5%    |
| AMD FCH SATA Controller D                                                      | 4         | 0.5%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.37%   |
| SK hynix BC511                                                                 | 3         | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 386       | 55.22%  |
| NVMe | 250       | 35.77%  |
| RAID | 39        | 5.58%   |
| IDE  | 22        | 3.15%   |
| SAS  | 2         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 337       | 63.83%  |
| AMD    | 190       | 35.98%  |
| ARM    | 1         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 11        | 2.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 1.89%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 10        | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.7%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 9         | 1.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 1.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 1.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 1.33%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 7         | 1.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.14%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 5         | 0.95%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.95%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 0.95%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.95%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.76%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 4         | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.76%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 4         | 0.76%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 4         | 0.76%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 4         | 0.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.76%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.76%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.76%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 4         | 0.76%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.76%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 4         | 0.76%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 3         | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.57%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 0.57%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 3         | 0.57%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 3         | 0.57%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 0.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.57%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.57%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 0.57%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.57%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 3         | 0.57%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 0.57%   |
| AMD Ryzen 7 5800HS with Radeon Graphics       | 3         | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 0.57%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.57%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 3         | 0.57%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 3         | 0.57%   |
| Intel Pentium CPU 4415Y @ 1.60GHz             | 2         | 0.38%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.38%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.38%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 125       | 23.67%  |
| Intel Core i7           | 110       | 20.83%  |
| AMD Ryzen 5             | 64        | 12.12%  |
| AMD Ryzen 7             | 55        | 10.42%  |
| Other                   | 29        | 5.49%   |
| Intel Core i3           | 28        | 5.3%    |
| AMD Ryzen 9             | 24        | 4.55%   |
| Intel Celeron           | 14        | 2.65%   |
| Intel Xeon              | 10        | 1.89%   |
| AMD Ryzen 3             | 9         | 1.7%    |
| Intel Core 2 Duo        | 8         | 1.52%   |
| AMD Ryzen 7 PRO         | 8         | 1.52%   |
| AMD A4                  | 7         | 1.33%   |
| Intel Pentium           | 5         | 0.95%   |
| AMD A8                  | 4         | 0.76%   |
| Intel Core 2 Quad       | 3         | 0.57%   |
| AMD Ryzen Threadripper  | 3         | 0.57%   |
| AMD FX                  | 3         | 0.57%   |
| Intel Core m3           | 2         | 0.38%   |
| AMD E1                  | 2         | 0.38%   |
| Intel Pentium Gold      | 1         | 0.19%   |
| Intel Pentium Dual-Core | 1         | 0.19%   |
| Intel Pentium Dual      | 1         | 0.19%   |
| Intel Core i9           | 1         | 0.19%   |
| Intel Core 2 Extreme    | 1         | 0.19%   |
| Intel Core 2            | 1         | 0.19%   |
| Intel Atom              | 1         | 0.19%   |
| AMD Ryzen 5 PRO         | 1         | 0.19%   |
| AMD Phenom II X4        | 1         | 0.19%   |
| AMD E                   | 1         | 0.19%   |
| AMD Athlon X4           | 1         | 0.19%   |
| AMD Athlon II X4        | 1         | 0.19%   |
| AMD Athlon II           | 1         | 0.19%   |
| AMD Athlon              | 1         | 0.19%   |
| AMD A10                 | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 200       | 37.81%  |
| 2      | 146       | 27.6%   |
| 6      | 78        | 14.74%  |
| 8      | 77        | 14.56%  |
| 12     | 17        | 3.21%   |
| 16     | 5         | 0.95%   |
| 10     | 3         | 0.57%   |
| 3      | 2         | 0.38%   |
| 32     | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 524       | 99.05%  |
| 2      | 5         | 0.95%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 424       | 80.3%   |
| 1      | 104       | 19.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 525       | 99.43%  |
| Unknown        | 2         | 0.38%   |
| 64-bit         | 1         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 155       | 28.92%  |
| 0x306c3    | 25        | 4.66%   |
| 0x08701021 | 23        | 4.29%   |
| 0x306a9    | 19        | 3.54%   |
| 0x806ea    | 18        | 3.36%   |
| 0x406e3    | 18        | 3.36%   |
| 0x0a50000c | 17        | 3.17%   |
| 0x906ea    | 16        | 2.99%   |
| 0x506e3    | 16        | 2.99%   |
| 0x806e9    | 15        | 2.8%    |
| 0x806ec    | 12        | 2.24%   |
| 0x40651    | 11        | 2.05%   |
| 0x08108109 | 11        | 2.05%   |
| 0x906e9    | 9         | 1.68%   |
| 0x706e5    | 9         | 1.68%   |
| 0x0a201009 | 9         | 1.68%   |
| 0x806c1    | 8         | 1.49%   |
| 0x08701013 | 8         | 1.49%   |
| 0x08600106 | 8         | 1.49%   |
| 0x08600104 | 8         | 1.49%   |
| 0x206a7    | 7         | 1.31%   |
| 0x08608103 | 7         | 1.31%   |
| 0x08108102 | 6         | 1.12%   |
| 0xa0652    | 5         | 0.93%   |
| 0x306d4    | 5         | 0.93%   |
| 0x806eb    | 4         | 0.75%   |
| 0x806d1    | 4         | 0.75%   |
| 0x706a1    | 4         | 0.75%   |
| 0x1067a    | 4         | 0.75%   |
| 0x0a201016 | 4         | 0.75%   |
| 0x08600102 | 4         | 0.75%   |
| 0x0800820d | 4         | 0.75%   |
| 0x08001137 | 4         | 0.75%   |
| 0x406c4    | 3         | 0.56%   |
| 0x20655    | 3         | 0.56%   |
| 0x106a5    | 3         | 0.56%   |
| 0x08001138 | 3         | 0.56%   |
| 0x06006705 | 3         | 0.56%   |
| 0xa0655    | 2         | 0.37%   |
| 0x706a8    | 2         | 0.37%   |
| 0x6fd      | 2         | 0.37%   |
| 0x20652    | 2         | 0.37%   |
| 0x106e5    | 2         | 0.37%   |
| 0x0a50000b | 2         | 0.37%   |
| 0x08600103 | 2         | 0.37%   |
| 0x08101016 | 2         | 0.37%   |
| 0x07000110 | 2         | 0.37%   |
| 0x0700010f | 2         | 0.37%   |
| 0x010000c8 | 2         | 0.37%   |
| 0xa0671    | 1         | 0.19%   |
| 0xa0653    | 1         | 0.19%   |
| 0x906ed    | 1         | 0.19%   |
| 0x906ec    | 1         | 0.19%   |
| 0x906eb    | 1         | 0.19%   |
| 0x906c0    | 1         | 0.19%   |
| 0x906a3    | 1         | 0.19%   |
| 0x90672    | 1         | 0.19%   |
| 0x6fb      | 1         | 0.19%   |
| 0x6f6      | 1         | 0.19%   |
| 0x6f2      | 1         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 98        | 18.56%  |
| Zen 2            | 71        | 13.45%  |
| Haswell          | 52        | 9.85%   |
| Skylake          | 44        | 8.33%   |
| Zen 3            | 41        | 7.77%   |
| Zen+             | 29        | 5.49%   |
| IvyBridge        | 27        | 5.11%   |
| IceLake          | 17        | 3.22%   |
| Zen              | 15        | 2.84%   |
| Unknown          | 15        | 2.84%   |
| TigerLake        | 13        | 2.46%   |
| CometLake        | 13        | 2.46%   |
| SandyBridge      | 11        | 2.08%   |
| Broadwell        | 10        | 1.89%   |
| Westmere         | 8         | 1.52%   |
| Silvermont       | 8         | 1.52%   |
| Penryn           | 8         | 1.52%   |
| Core             | 8         | 1.52%   |
| Excavator        | 7         | 1.33%   |
| Jaguar           | 6         | 1.14%   |
| Goldmont plus    | 6         | 1.14%   |
| Nehalem          | 5         | 0.95%   |
| Piledriver       | 4         | 0.76%   |
| Puma             | 2         | 0.38%   |
| K10              | 2         | 0.38%   |
| Alderlake Hybrid | 2         | 0.38%   |
| Tremont          | 1         | 0.19%   |
| Steamroller      | 1         | 0.19%   |
| K10 Llano        | 1         | 0.19%   |
| Goldmont         | 1         | 0.19%   |
| Bulldozer        | 1         | 0.19%   |
| Bobcat           | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 256       | 39.75%  |
| Nvidia | 208       | 32.3%   |
| AMD    | 180       | 27.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 28        | 4.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 3.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 3.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 3.51%   |
| Intel UHD Graphics 620                                                                   | 22        | 3.35%   |
| AMD Cezanne                                                                              | 22        | 3.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 2.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 2.29%   |
| Intel HD Graphics 620                                                                    | 13        | 1.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 1.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.52%   |
| Intel HD Graphics 530                                                                    | 9         | 1.37%   |
| AMD Lucienne                                                                             | 9         | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8         | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.22%   |
| Intel HD Graphics 630                                                                    | 8         | 1.22%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8         | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.07%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7         | 1.07%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 1.07%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 7         | 1.07%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 6         | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 0.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 5         | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.76%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 5         | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.76%   |
| Intel HD Graphics 5500                                                                   | 5         | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.76%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 5         | 0.76%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 0.76%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.61%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 4         | 0.61%   |
| Nvidia GM108M [GeForce 940M]                                                             | 4         | 0.61%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.61%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.61%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 4         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 0.46%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.46%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.46%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.46%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 3         | 0.46%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 3         | 0.46%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.46%   |
| Intel HD Graphics 615                                                                    | 3         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 157       | 29.62%  |
| 1 x AMD        | 141       | 26.6%   |
| 1 x Nvidia     | 108       | 20.38%  |
| Intel + Nvidia | 81        | 15.28%  |
| AMD + Nvidia   | 17        | 3.21%   |
| Intel + AMD    | 13        | 2.45%   |
| 2 x AMD        | 11        | 2.08%   |
| Other          | 1         | 0.19%   |
| 2 x Nvidia     | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 371       | 70.13%  |
| Proprietary | 157       | 29.68%  |
| Unknown     | 1         | 0.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 280       | 52.24%  |
| 0.01-0.5   | 58        | 10.82%  |
| 1.01-2.0   | 52        | 9.7%    |
| 7.01-8.0   | 45        | 8.4%    |
| 3.01-4.0   | 39        | 7.28%   |
| 0.51-1.0   | 20        | 3.73%   |
| 5.01-6.0   | 19        | 3.54%   |
| 8.01-16.0  | 16        | 2.99%   |
| 2.01-3.0   | 6         | 1.12%   |
| 16.01-24.0 | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 76        | 11.67%  |
| Samsung Electronics     | 70        | 10.75%  |
| LG Display              | 58        | 8.91%   |
| Chimei Innolux          | 54        | 8.29%   |
| BOE                     | 51        | 7.83%   |
| Dell                    | 36        | 5.53%   |
| Goldstar                | 35        | 5.38%   |
| Acer                    | 25        | 3.84%   |
| BenQ                    | 21        | 3.23%   |
| Ancor Communications    | 20        | 3.07%   |
| AOC                     | 19        | 2.92%   |
| Lenovo                  | 18        | 2.76%   |
| Hewlett-Packard         | 14        | 2.15%   |
| Sharp                   | 11        | 1.69%   |
| Apple                   | 11        | 1.69%   |
| ViewSonic               | 10        | 1.54%   |
| Philips                 | 10        | 1.54%   |
| PANDA                   | 10        | 1.54%   |
| InfoVision              | 9         | 1.38%   |
| ASUSTek Computer        | 9         | 1.38%   |
| Iiyama                  | 8         | 1.23%   |
| Vizio                   | 7         | 1.08%   |
| Gigabyte Technology     | 5         | 0.77%   |
| Sony                    | 4         | 0.61%   |
| Panasonic               | 3         | 0.46%   |
| LG Electronics          | 3         | 0.46%   |
| Fujitsu Siemens         | 3         | 0.46%   |
| Valve                   | 2         | 0.31%   |
| Unknown                 | 2         | 0.31%   |
| Sceptre Tech            | 2         | 0.31%   |
| RTK                     | 2         | 0.31%   |
| Pixio                   | 2         | 0.31%   |
| Lenovo Group Limited    | 2         | 0.31%   |
| JDI                     | 2         | 0.31%   |
| CSO                     | 2         | 0.31%   |
| Chi Mei Optoelectronics | 2         | 0.31%   |
| CEX                     | 2         | 0.31%   |
| VOXICON                 | 1         | 0.15%   |
| Unknown (XXX)           | 1         | 0.15%   |
| Sun                     | 1         | 0.15%   |
| SAC                     | 1         | 0.15%   |
| RS                      | 1         | 0.15%   |
| Planar                  | 1         | 0.15%   |
| Orion                   | 1         | 0.15%   |
| NEC Computers           | 1         | 0.15%   |
| MSI                     | 1         | 0.15%   |
| Mi                      | 1         | 0.15%   |
| LG Philips              | 1         | 0.15%   |
| Insignia                | 1         | 0.15%   |
| InnoLux Display         | 1         | 0.15%   |
| Idek Iiyama             | 1         | 0.15%   |
| Hyundai ImageQuest      | 1         | 0.15%   |
| HVR                     | 1         | 0.15%   |
| HPN                     | 1         | 0.15%   |
| HKC                     | 1         | 0.15%   |
| Hitachi                 | 1         | 0.15%   |
| HannStar                | 1         | 0.15%   |
| Grundig                 | 1         | 0.15%   |
| GET                     | 1         | 0.15%   |
| GDH                     | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 5         | 0.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5         | 0.75%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 5         | 0.75%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch           | 4         | 0.6%    |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch               | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 4         | 0.6%    |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 3         | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3         | 0.45%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch      | 3         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 3         | 0.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3         | 0.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 3         | 0.45%   |
| InfoVision LCD Monitor IVO8544 1920x1080 294x165mm 13.3-inch           | 3         | 0.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 3         | 0.45%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch       | 3         | 0.45%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                  | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch         | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch          | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 3         | 0.45%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                      | 3         | 0.45%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 3         | 0.45%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                    | 2         | 0.3%    |
| Valve Index HMD VLV91A8                                                | 2         | 0.3%    |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                | 2         | 0.3%    |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch                | 2         | 0.3%    |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2         | 0.3%    |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch       | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SAM0E35 1920x1080 1210x680mm 54.6-inch | 2         | 0.3%    |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch     | 2         | 0.3%    |
| Samsung Electronics C27FG7x SAM0E42 1920x1080 598x337mm 27.0-inch      | 2         | 0.3%    |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2         | 0.3%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 2         | 0.3%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.3%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 2         | 0.3%    |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch               | 2         | 0.3%    |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 0.3%    |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                   | 2         | 0.3%    |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch               | 2         | 0.3%    |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                  | 2         | 0.3%    |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch           | 2         | 0.3%    |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                   | 2         | 0.3%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2         | 0.3%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 2         | 0.3%    |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch         | 2         | 0.3%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 2         | 0.3%    |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                    | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 300       | 47.92%  |
| 1366x768 (WXGA)    | 83        | 13.26%  |
| 2560x1440 (QHD)    | 58        | 9.27%   |
| 3840x2160 (4K)     | 49        | 7.83%   |
| 1920x1200 (WUXGA)  | 16        | 2.56%   |
| 1440x900 (WXGA+)   | 14        | 2.24%   |
| 1280x1024 (SXGA)   | 12        | 1.92%   |
| Unknown            | 10        | 1.6%    |
| 2560x1080          | 9         | 1.44%   |
| 2560x1600          | 8         | 1.28%   |
| 1600x900 (HD+)     | 8         | 1.28%   |
| 1680x1050 (WSXGA+) | 7         | 1.12%   |
| 3440x1440          | 6         | 0.96%   |
| 3840x1080          | 4         | 0.64%   |
| 2736x1824          | 4         | 0.64%   |
| 2160x1440          | 4         | 0.64%   |
| 1360x768           | 4         | 0.64%   |
| 1280x800 (WXGA)    | 4         | 0.64%   |
| 3840x1600          | 2         | 0.32%   |
| 3456x2160          | 2         | 0.32%   |
| 3000x2000          | 2         | 0.32%   |
| 2880x1800          | 2         | 0.32%   |
| 1800x1200          | 2         | 0.32%   |
| 9840x3840          | 1         | 0.16%   |
| 4480x1440          | 1         | 0.16%   |
| 3840x2400          | 1         | 0.16%   |
| 3840x1440          | 1         | 0.16%   |
| 3840x1200          | 1         | 0.16%   |
| 3520x1080          | 1         | 0.16%   |
| 3240x2160          | 1         | 0.16%   |
| 3200x1800 (QHD+)   | 1         | 0.16%   |
| 3200x1080          | 1         | 0.16%   |
| 2880x1920          | 1         | 0.16%   |
| 2880x1700          | 1         | 0.16%   |
| 2256x1504          | 1         | 0.16%   |
| 2240x1400          | 1         | 0.16%   |
| 1920x540           | 1         | 0.16%   |
| 1600x1200          | 1         | 0.16%   |
| 1024x768 (XGA)     | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 138       | 21.26%  |
| 13      | 80        | 12.33%  |
| 27      | 72        | 11.09%  |
| 24      | 66        | 10.17%  |
| 14      | 44        | 6.78%   |
| 23      | 32        | 4.93%   |
| 21      | 31        | 4.78%   |
| 17      | 28        | 4.31%   |
| Unknown | 21        | 3.24%   |
| 34      | 17        | 2.62%   |
| 31      | 17        | 2.62%   |
| 12      | 12        | 1.85%   |
| 19      | 11        | 1.69%   |
| 18      | 10        | 1.54%   |
| 22      | 8         | 1.23%   |
| 11      | 7         | 1.08%   |
| 54      | 5         | 0.77%   |
| 20      | 5         | 0.77%   |
| 16      | 5         | 0.77%   |
| 84      | 4         | 0.62%   |
| 49      | 4         | 0.62%   |
| 32      | 4         | 0.62%   |
| 10      | 4         | 0.62%   |
| 72      | 2         | 0.31%   |
| 46      | 2         | 0.31%   |
| 42      | 2         | 0.31%   |
| 37      | 2         | 0.31%   |
| 28      | 2         | 0.31%   |
| 25      | 2         | 0.31%   |
| 74      | 1         | 0.15%   |
| 69      | 1         | 0.15%   |
| 65      | 1         | 0.15%   |
| 60      | 1         | 0.15%   |
| 57      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
| 48      | 1         | 0.15%   |
| 47      | 1         | 0.15%   |
| 40      | 1         | 0.15%   |
| 29      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |
| 8       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 228       | 36.13%  |
| 501-600     | 152       | 24.09%  |
| 201-300     | 62        | 9.83%   |
| 401-500     | 58        | 9.19%   |
| 351-400     | 32        | 5.07%   |
| 601-700     | 27        | 4.28%   |
| 701-800     | 21        | 3.33%   |
| Unknown     | 21        | 3.33%   |
| 1001-1500   | 16        | 2.54%   |
| 1501-2000   | 8         | 1.27%   |
| 801-900     | 3         | 0.48%   |
| 901-1000    | 2         | 0.32%   |
| 101-200     | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 436       | 77.3%   |
| 16/10   | 60        | 10.64%  |
| Unknown | 19        | 3.37%   |
| 21/9    | 16        | 2.84%   |
| 3/2     | 14        | 2.48%   |
| 5/4     | 8         | 1.42%   |
| 32/9    | 4         | 0.71%   |
| 4/3     | 3         | 0.53%   |
| 6/5     | 2         | 0.35%   |
| 2.65    | 1         | 0.18%   |
| 0.62    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 138       | 21.56%  |
| 201-250        | 104       | 16.25%  |
| 81-90          | 95        | 14.84%  |
| 301-350        | 73        | 11.41%  |
| 351-500        | 37        | 5.78%   |
| 71-80          | 35        | 5.47%   |
| 251-300        | 27        | 4.22%   |
| 121-130        | 21        | 3.28%   |
| Unknown        | 21        | 3.28%   |
| 151-200        | 19        | 2.97%   |
| More than 1000 | 18        | 2.81%   |
| 141-150        | 13        | 2.03%   |
| 501-1000       | 13        | 2.03%   |
| 51-60          | 7         | 1.09%   |
| 61-70          | 6         | 0.94%   |
| 41-50          | 4         | 0.63%   |
| 131-140        | 4         | 0.63%   |
| 111-120        | 4         | 0.63%   |
| 1-40           | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 188       | 30.77%  |
| 51-100        | 174       | 28.48%  |
| 101-120       | 138       | 22.59%  |
| 161-240       | 53        | 8.67%   |
| Unknown       | 21        | 3.44%   |
| More than 240 | 19        | 3.11%   |
| 1-50          | 18        | 2.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 405       | 75.14%  |
| 2     | 120       | 22.26%  |
| 3     | 12        | 2.23%   |
| 4     | 2         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 319       | 39.33%  |
| Intel                                 | 294       | 36.25%  |
| Qualcomm Atheros                      | 66        | 8.14%   |
| Broadcom                              | 24        | 2.96%   |
| MediaTek                              | 12        | 1.48%   |
| ASIX Electronics                      | 11        | 1.36%   |
| TP-Link                               | 10        | 1.23%   |
| Microsoft                             | 9         | 1.11%   |
| D-Link                                | 7         | 0.86%   |
| Broadcom Limited                      | 7         | 0.86%   |
| Ralink Technology                     | 5         | 0.62%   |
| Sierra Wireless                       | 4         | 0.49%   |
| Marvell Technology Group              | 4         | 0.49%   |
| Samsung Electronics                   | 3         | 0.37%   |
| Ralink                                | 3         | 0.37%   |
| Hewlett-Packard                       | 3         | 0.37%   |
| DisplayLink                           | 3         | 0.37%   |
| Aquantia                              | 3         | 0.37%   |
| Xiaomi                                | 2         | 0.25%   |
| Nvidia                                | 2         | 0.25%   |
| NetGear                               | 2         | 0.25%   |
| Lenovo                                | 2         | 0.25%   |
| Huawei Technologies                   | 2         | 0.25%   |
| Google                                | 2         | 0.25%   |
| Cypress Semiconductor                 | 2         | 0.25%   |
| Wilocity                              | 1         | 0.12%   |
| Motorola PCS                          | 1         | 0.12%   |
| Linksys                               | 1         | 0.12%   |
| InterBiometrics                       | 1         | 0.12%   |
| Fibocom                               | 1         | 0.12%   |
| Exar                                  | 1         | 0.12%   |
| Ericsson Business Mobile Networks     | 1         | 0.12%   |
| Edimax Technology                     | 1         | 0.12%   |
| Apple                                 | 1         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 215       | 22.26%  |
| Intel Wi-Fi 6 AX200                                               | 58        | 6%      |
| Realtek RTL8125 2.5GbE Controller                                 | 26        | 2.69%   |
| Intel I211 Gigabit Network Connection                             | 26        | 2.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 2.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 2.07%   |
| Intel Wireless 8265 / 8275                                        | 20        | 2.07%   |
| Intel Wireless 7260                                               | 17        | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 1.55%   |
| Intel Wireless 7265                                               | 15        | 1.55%   |
| Intel Wireless 8260                                               | 13        | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 12        | 1.24%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.14%   |
| Intel Wireless-AC 9260                                            | 10        | 1.04%   |
| Intel Wireless 3165                                               | 10        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 10        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 1.04%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 9         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 0.83%   |
| Intel Ethernet Controller I225-V                                  | 8         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 0.72%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 0.72%   |
| D-Link 802.11ac NIC                                               | 7         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.62%   |
| Realtek 802.11ac NIC                                              | 6         | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.62%   |
| TP-Link 802.11ac NIC                                              | 5         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5         | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.52%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 5         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.41%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 4         | 0.41%   |
| Intel Wireless 3160                                               | 4         | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.41%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.41%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.41%   |
| Sierra Wireless EM7455                                            | 3         | 0.31%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 257       | 55.15%  |
| Realtek Semiconductor                 | 73        | 15.67%  |
| Qualcomm Atheros                      | 53        | 11.37%  |
| Broadcom                              | 19        | 4.08%   |
| MediaTek                              | 12        | 2.58%   |
| TP-Link                               | 9         | 1.93%   |
| Microsoft                             | 8         | 1.72%   |
| D-Link                                | 7         | 1.5%    |
| Broadcom Limited                      | 6         | 1.29%   |
| Ralink Technology                     | 5         | 1.07%   |
| Sierra Wireless                       | 4         | 0.86%   |
| Marvell Technology Group              | 4         | 0.86%   |
| Ralink                                | 3         | 0.64%   |
| Wilocity                              | 1         | 0.21%   |
| Samsung Electronics                   | 1         | 0.21%   |
| NetGear                               | 1         | 0.21%   |
| Linksys                               | 1         | 0.21%   |
| Edimax Technology                     | 1         | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 58        | 12.37%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 4.26%   |
| Intel Wireless 8265 / 8275                                     | 20        | 4.26%   |
| Intel Wireless 7260                                            | 17        | 3.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15        | 3.2%    |
| Intel Wireless 7265                                            | 15        | 3.2%    |
| Intel Wireless 8260                                            | 13        | 2.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 12        | 2.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 2.35%   |
| Intel Wireless-AC 9260                                         | 10        | 2.13%   |
| Intel Wireless 3165                                            | 10        | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10        | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 2.13%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 1.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 1.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 8         | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 1.49%   |
| D-Link 802.11ac NIC                                            | 7         | 1.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.28%   |
| Realtek 802.11ac NIC                                           | 6         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.28%   |
| TP-Link 802.11ac NIC                                           | 5         | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.07%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 1.07%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.07%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 5         | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 0.85%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 4         | 0.85%   |
| Intel Wireless 3160                                            | 4         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.85%   |
| Sierra Wireless EM7455                                         | 3         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 3         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 0.64%   |
| Microsoft XBOX ACC                                             | 3         | 0.64%   |
| Microsoft Wireless XBox Controller Dongle                      | 3         | 0.64%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 0.64%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 3         | 0.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.43%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                           | 2         | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.43%   |
| Microsoft Xbox 360 Wireless Adapter                            | 2         | 0.43%   |
| MediaTek WiFi                                                  | 2         | 0.43%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 0.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 0.43%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 0.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 0.43%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 0.21%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 286       | 60.08%  |
| Intel                 | 123       | 25.84%  |
| Qualcomm Atheros      | 22        | 4.62%   |
| ASIX Electronics      | 11        | 2.31%   |
| Broadcom              | 9         | 1.89%   |
| DisplayLink           | 3         | 0.63%   |
| Aquantia              | 3         | 0.63%   |
| Xiaomi                | 2         | 0.42%   |
| Samsung Electronics   | 2         | 0.42%   |
| Nvidia                | 2         | 0.42%   |
| Lenovo                | 2         | 0.42%   |
| Google                | 2         | 0.42%   |
| Cypress Semiconductor | 2         | 0.42%   |
| TP-Link               | 1         | 0.21%   |
| NetGear               | 1         | 0.21%   |
| Motorola PCS          | 1         | 0.21%   |
| Microsoft             | 1         | 0.21%   |
| Fibocom               | 1         | 0.21%   |
| Broadcom Limited      | 1         | 0.21%   |
| Apple                 | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 215       | 44.06%  |
| Realtek RTL8125 2.5GbE Controller                                 | 26        | 5.33%   |
| Intel I211 Gigabit Network Connection                             | 26        | 5.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 4.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 4.1%    |
| Intel Ethernet Connection I217-LM                                 | 11        | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 1.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 1.64%   |
| Intel Ethernet Controller I225-V                                  | 8         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.43%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.23%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.02%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.61%   |
| Realtek Realtek Ethernet controller                               | 3         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.41%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2         | 0.41%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.41%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.41%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.41%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.41%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.41%   |
| Cypress K38231_03                                                 | 2         | 0.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.2%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.2%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.2%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.2%    |
| Nvidia MCP73 Ethernet                                             | 1         | 0.2%    |
| Nvidia MCP61 Ethernet                                             | 1         | 0.2%    |
| NetGear LB1120-100NAS                                             | 1         | 0.2%    |
| Motorola PCS moto g(9) play                                       | 1         | 0.2%    |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 1         | 0.2%    |
| Intel I210 Gigabit Network Connection                             | 1         | 0.2%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.2%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.2%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.2%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.2%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.2%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.2%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.2%    |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.2%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.2%    |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.2%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.2%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 433       | 49.6%   |
| WiFi     | 431       | 49.37%  |
| Modem    | 8         | 0.92%   |
| Unknown  | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 343       | 59.86%  |
| Ethernet | 230       | 40.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 279       | 52.54%  |
| 1     | 225       | 42.37%  |
| 3     | 20        | 3.77%   |
| 0     | 4         | 0.75%   |
| 4     | 3         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 419       | 78.03%  |
| Yes  | 118       | 21.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 232       | 55.77%  |
| Realtek Semiconductor           | 55        | 13.22%  |
| Qualcomm Atheros Communications | 24        | 5.77%   |
| Cambridge Silicon Radio         | 18        | 4.33%   |
| Broadcom                        | 18        | 4.33%   |
| IMC Networks                    | 13        | 3.13%   |
| Lite-On Technology              | 12        | 2.88%   |
| Apple                           | 10        | 2.4%    |
| Foxconn / Hon Hai               | 8         | 1.92%   |
| ASUSTek Computer                | 8         | 1.92%   |
| Realtek                         | 4         | 0.96%   |
| Toshiba                         | 3         | 0.72%   |
| Marvell Semiconductor           | 3         | 0.72%   |
| Dell                            | 3         | 0.72%   |
| TP-Link                         | 1         | 0.24%   |
| MediaTek                        | 1         | 0.24%   |
| HTC (High Tech Computer)        | 1         | 0.24%   |
| Foxconn International           | 1         | 0.24%   |
| Dynex                           | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 88        | 21.15%  |
| Intel AX200 Bluetooth                                                | 56        | 13.46%  |
| Realtek Bluetooth Radio                                              | 38        | 9.13%   |
| Intel AX201 Bluetooth                                                | 33        | 7.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 23        | 5.53%   |
| Qualcomm Atheros  Bluetooth Device                                   | 18        | 4.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 18        | 4.33%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 11        | 2.64%   |
| Intel Bluetooth Device                                               | 11        | 2.64%   |
| Intel AX210 Bluetooth                                                | 10        | 2.4%    |
| Apple Bluetooth USB Host Controller                                  | 8         | 1.92%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 6         | 1.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 6         | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 5         | 1.2%    |
| IMC Networks Wireless_Device                                         | 5         | 1.2%    |
| IMC Networks Bluetooth Radio                                         | 5         | 1.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 4         | 0.96%   |
| Realtek Bluetooth Radio                                              | 4         | 0.96%   |
| Lite-On Bluetooth Device                                             | 4         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 3         | 0.72%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 3         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 3         | 0.72%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 3         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 3         | 0.72%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 3         | 0.72%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 2         | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2         | 0.48%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 2         | 0.48%   |
| ASUS Bluetooth Device                                                | 2         | 0.48%   |
| TP-Link TP-hink UB500 Adapter                                        | 1         | 0.24%   |
| Toshiba BCM43142A0                                                   | 1         | 0.24%   |
| Realtek RTL8821A Bluetooth                                           | 1         | 0.24%   |
| Realtek RTL8723B Bluetooth                                           | 1         | 0.24%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1         | 0.24%   |
| MediaTek Wireless_Device                                             | 1         | 0.24%   |
| Lite-On Bluetooth Radio                                              | 1         | 0.24%   |
| Lite-On Atheros Bluetooth                                            | 1         | 0.24%   |
| IMC Networks Bluetooth Device                                        | 1         | 0.24%   |
| IMC Networks Bluetooth                                               | 1         | 0.24%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                    | 1         | 0.24%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.24%   |
| Foxconn International BCM43142A0 Bluetooth module                    | 1         | 0.24%   |
| Foxconn / Hon Hai BT                                                 | 1         | 0.24%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                      | 1         | 0.24%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1         | 0.24%   |
| Dell Wireless 370 Bluetooth Mini-card                                | 1         | 0.24%   |
| Dell DW375 Bluetooth Module                                          | 1         | 0.24%   |
| Dell Broadcom BCM20702A0 Bluetooth                                   | 1         | 0.24%   |
| Broadcom HP Portable Valentine                                       | 1         | 0.24%   |
| Broadcom HP Portable SoftSailing                                     | 1         | 0.24%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                    | 1         | 0.24%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                 | 1         | 0.24%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 1         | 0.24%   |
| Broadcom BCM2045A0                                                   | 1         | 0.24%   |
| Broadcom BCM2045 Bluetooth                                           | 1         | 0.24%   |
| ASUS BT-253 Bluetooth Adapter                                        | 1         | 0.24%   |
| ASUS Bluetooth Adapter                                               | 1         | 0.24%   |
| ASUS BCM20702A0                                                      | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 330       | 38.87%  |
| AMD                                             | 211       | 24.85%  |
| Nvidia                                          | 155       | 18.26%  |
| C-Media Electronics                             | 19        | 2.24%   |
| Texas Instruments                               | 12        | 1.41%   |
| SteelSeries ApS                                 | 12        | 1.41%   |
| Logitech                                        | 12        | 1.41%   |
| JMTek                                           | 7         | 0.82%   |
| Creative Labs                                   | 6         | 0.71%   |
| Kingston Technology                             | 5         | 0.59%   |
| Creative Technology                             | 5         | 0.59%   |
| Sony                                            | 4         | 0.47%   |
| NAD Electronics                                 | 4         | 0.47%   |
| KORG                                            | 4         | 0.47%   |
| Corsair                                         | 4         | 0.47%   |
| Blue Microphones                                | 4         | 0.47%   |
| AKAI                                            | 4         | 0.47%   |
| Valve Software                                  | 3         | 0.35%   |
| Samson Technologies                             | 3         | 0.35%   |
| Realtek Semiconductor                           | 3         | 0.35%   |
| Lenovo                                          | 3         | 0.35%   |
| XMOS                                            | 2         | 0.24%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.24%   |
| Sennheiser Communications                       | 2         | 0.24%   |
| RODE Microphones                                | 2         | 0.24%   |
| Razer USA                                       | 2         | 0.24%   |
| M-Audio                                         | 2         | 0.24%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.24%   |
| Generalplus Technology                          | 2         | 0.24%   |
| AKAI Professional M.I.                          | 2         | 0.24%   |
| Xilinx                                          | 1         | 0.12%   |
| VIA Technologies                                | 1         | 0.12%   |
| Trust                                           | 1         | 0.12%   |
| Tdlasunnic                                      | 1         | 0.12%   |
| Solid State System                              | 1         | 0.12%   |
| Plantronics                                     | 1         | 0.12%   |
| No brand                                        | 1         | 0.12%   |
| Native Instruments                              | 1         | 0.12%   |
| Micro Star International                        | 1         | 0.12%   |
| iConnectivity                                   | 1         | 0.12%   |
| Hewlett-Packard                                 | 1         | 0.12%   |
| GYROCOM C&C                                     | 1         | 0.12%   |
| GN Netcom                                       | 1         | 0.12%   |
| Giga-Byte Technology                            | 1         | 0.12%   |
| Focusrite-Novation                              | 1         | 0.12%   |
| FiiO Electronics Technology                     | 1         | 0.12%   |
| Cooler Master                                   | 1         | 0.12%   |
| Cambridge Silicon Radio                         | 1         | 0.12%   |
| BEHRINGER International                         | 1         | 0.12%   |
| ASUSTek Computer                                | 1         | 0.12%   |
| Apple                                           | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 85        | 8.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 63        | 6.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 56        | 5.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 55        | 5.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 31        | 2.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26        | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 24        | 2.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 24        | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 2.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22        | 2.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19        | 1.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 17        | 1.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 16        | 1.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 14        | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 1.35%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 1.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 1.25%   |
| Nvidia TU106 High Definition Audio Controller                              | 12        | 1.16%   |
| AMD Navi 10 HDMI Audio                                                     | 12        | 1.16%   |
| AMD FCH Azalia Controller                                                  | 12        | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 11        | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 10        | 0.96%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 0.87%   |
| Nvidia GK104 HDMI Audio Controller                                         | 9         | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 9         | 0.87%   |
| Nvidia GM204 High Definition Audio Controller                              | 8         | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 0.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8         | 0.77%   |
| Texas Instruments PCM2902 Audio Codec                                      | 7         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 7         | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 0.58%   |
| Nvidia GA102 High Definition Audio Controller                              | 6         | 0.58%   |
| Intel CM238 HD Audio Controller                                            | 6         | 0.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6         | 0.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 0.58%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 5         | 0.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.48%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.48%   |
| JMTek USB PnP Audio Device                                                 | 5         | 0.48%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 0.48%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 0.48%   |
| AMD High Definition Audio Controller                                       | 5         | 0.48%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.39%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4         | 0.39%   |
| NAD Electronics USB Audio                                                  | 4         | 0.39%   |
| KORG nanoKONTROL2 MIDI Controller                                          | 4         | 0.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 115       | 24.68%  |
| SK hynix            | 81        | 17.38%  |
| Micron Technology   | 50        | 10.73%  |
| Corsair             | 39        | 8.37%   |
| G.Skill             | 37        | 7.94%   |
| Kingston            | 35        | 7.51%   |
| Crucial             | 26        | 5.58%   |
| Unknown             | 25        | 5.36%   |
| A-DATA Technology   | 11        | 2.36%   |
| Ramaxel Technology  | 7         | 1.5%    |
| Patriot             | 7         | 1.5%    |
| Team                | 6         | 1.29%   |
| Unknown (ABCD)      | 5         | 1.07%   |
| Elpida              | 3         | 0.64%   |
| Shenzhen Mic        | 2         | 0.43%   |
| Nanya Technology    | 2         | 0.43%   |
| Unknown             | 2         | 0.43%   |
| V-GeN               | 1         | 0.21%   |
| Strontium           | 1         | 0.21%   |
| Smart Brazil        | 1         | 0.21%   |
| Smart               | 1         | 0.21%   |
| Sesame              | 1         | 0.21%   |
| PNY                 | 1         | 0.21%   |
| Neo Forza           | 1         | 0.21%   |
| Magnum Tech         | 1         | 0.21%   |
| Kllisre             | 1         | 0.21%   |
| KLEVV               | 1         | 0.21%   |
| Golden Empire       | 1         | 0.21%   |
| GeIL                | 1         | 0.21%   |
| AMD                 | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 10        | 1.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.56%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 8         | 1.56%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 1.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 1.17%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 1.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.97%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 5         | 0.97%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.97%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 5         | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 4         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.78%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.78%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.78%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 4         | 0.78%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.58%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.58%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.58%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 3         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.58%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.58%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s        | 3         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 2         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.39%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.39%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR4 3733MT/s             | 2         | 0.39%   |
| SK hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.39%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.39%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 2         | 0.39%   |
| SK hynix RAM HMP351S6AFR8C-S6 4GB SODIMM DDR 800MT/s             | 2         | 0.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.39%   |
| SK hynix RAM H9CCNNNCPTALBR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 2         | 0.39%   |
| Shenzhen Mic RAM MG8A3200C21WE-SA 16GB SODIMM DDR4 3200MT/s      | 2         | 0.39%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1867MT/s              | 2         | 0.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.39%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.39%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 0.39%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.39%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.39%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s              | 2         | 0.39%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s              | 2         | 0.39%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.39%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 247       | 61.29%  |
| DDR3    | 103       | 25.56%  |
| LPDDR4  | 18        | 4.47%   |
| LPDDR3  | 17        | 4.22%   |
| DDR2    | 7         | 1.74%   |
| Unknown | 5         | 1.24%   |
| SDRAM   | 4         | 0.99%   |
| LPDDR5  | 1         | 0.25%   |
| DDR     | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 225       | 55.56%  |
| DIMM         | 133       | 32.84%  |
| Row Of Chips | 39        | 9.63%   |
| Chip         | 5         | 1.23%   |
| RIMM         | 1         | 0.25%   |
| FB-DIMM      | 1         | 0.25%   |
| Unknown      | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 199       | 45.75%  |
| 4096  | 129       | 29.66%  |
| 16384 | 63        | 14.48%  |
| 2048  | 29        | 6.67%   |
| 32768 | 13        | 2.99%   |
| 1024  | 2         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 103       | 23.46%  |
| 1600    | 81        | 18.45%  |
| 2667    | 67        | 15.26%  |
| 2400    | 28        | 6.38%   |
| 3600    | 27        | 6.15%   |
| 2133    | 21        | 4.78%   |
| 1333    | 16        | 3.64%   |
| 1867    | 15        | 3.42%   |
| 3266    | 10        | 2.28%   |
| 3466    | 7         | 1.59%   |
| 1334    | 6         | 1.37%   |
| 3000    | 5         | 1.14%   |
| 800     | 5         | 1.14%   |
| 4267    | 4         | 0.91%   |
| 3733    | 4         | 0.91%   |
| 3400    | 3         | 0.68%   |
| 1800    | 3         | 0.68%   |
| Unknown | 3         | 0.68%   |
| 4266    | 2         | 0.46%   |
| 3866    | 2         | 0.46%   |
| 3333    | 2         | 0.46%   |
| 2733    | 2         | 0.46%   |
| 2666    | 2         | 0.46%   |
| 667     | 2         | 0.46%   |
| 65535   | 1         | 0.23%   |
| 6400    | 1         | 0.23%   |
| 4800    | 1         | 0.23%   |
| 4333    | 1         | 0.23%   |
| 4000    | 1         | 0.23%   |
| 3800    | 1         | 0.23%   |
| 3500    | 1         | 0.23%   |
| 3151    | 1         | 0.23%   |
| 3134    | 1         | 0.23%   |
| 3067    | 1         | 0.23%   |
| 3066    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 2800    | 1         | 0.23%   |
| 2267    | 1         | 0.23%   |
| 2048    | 1         | 0.23%   |
| 1280    | 1         | 0.23%   |
| 1067    | 1         | 0.23%   |
| 1066    | 1         | 0.23%   |
| 400     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 2         | 25%     |
| Hewlett-Packard     | 2         | 25%     |
| Brother Industries  | 2         | 25%     |
| Seiko Epson         | 1         | 12.5%   |
| Pantum              | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 2         | 25%     |
| Seiko Epson WF-2010 Series    | 1         | 12.5%   |
| Pantum P2500W series          | 1         | 12.5%   |
| HP ENVY 5540 series           | 1         | 12.5%   |
| HP DeskJet 2130 series        | 1         | 12.5%   |
| Brother Printer               | 1         | 12.5%   |
| Brother HL-2130 series        | 1         | 12.5%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 18.87%  |
| IMC Networks                           | 43        | 12.11%  |
| Logitech                               | 36        | 10.14%  |
| Microdia                               | 27        | 7.61%   |
| Acer                                   | 27        | 7.61%   |
| Realtek Semiconductor                  | 19        | 5.35%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 4.23%   |
| Syntek                                 | 14        | 3.94%   |
| Sunplus Innovation Technology          | 13        | 3.66%   |
| Quanta                                 | 13        | 3.66%   |
| Lite-On Technology                     | 13        | 3.66%   |
| Apple                                  | 12        | 3.38%   |
| Microsoft                              | 5         | 1.41%   |
| Luxvisions Innotech Limited            | 4         | 1.13%   |
| Valve Software                         | 3         | 0.85%   |
| Suyin                                  | 3         | 0.85%   |
| Lenovo                                 | 3         | 0.85%   |
| Hewlett-Packard                        | 3         | 0.85%   |
| Unknown                                | 2         | 0.56%   |
| Sonix Technology                       | 2         | 0.56%   |
| Silicon Motion                         | 2         | 0.56%   |
| Samsung Electronics                    | 2         | 0.56%   |
| Primax Electronics                     | 2         | 0.56%   |
| Intel                                  | 2         | 0.56%   |
| Google                                 | 2         | 0.56%   |
| Alcor Micro                            | 2         | 0.56%   |
| Y Media                                | 1         | 0.28%   |
| Xiaomi                                 | 1         | 0.28%   |
| Trust                                  | 1         | 0.28%   |
| Tobii Technology AB                    | 1         | 0.28%   |
| Sunplus IT                             | 1         | 0.28%   |
| SN0002                                 | 1         | 0.28%   |
| SJ-180517-N                            | 1         | 0.28%   |
| Ricoh                                  | 1         | 0.28%   |
| Razer USA                              | 1         | 0.28%   |
| MacroSilicon                           | 1         | 0.28%   |
| LG Electronics                         | 1         | 0.28%   |
| Leap Motion                            | 1         | 0.28%   |
| Huawei Technologies                    | 1         | 0.28%   |
| HTC (High Tech Computer)               | 1         | 0.28%   |
| GEMBIRD                                | 1         | 0.28%   |
| EVGA                                   | 1         | 0.28%   |
| Creative Technology                    | 1         | 0.28%   |
| ALi                                    | 1         | 0.28%   |
| Unknown                                | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 20        | 5.63%   |
| Chicony Integrated Camera                                      | 20        | 5.63%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 13        | 3.66%   |
| Chicony HD WebCam                                              | 13        | 3.66%   |
| Microdia Integrated_Webcam_HD                                  | 11        | 3.1%    |
| Acer Integrated Camera                                         | 11        | 3.1%    |
| Syntek Integrated Camera                                       | 9         | 2.54%   |
| Logitech HD Pro Webcam C920                                    | 9         | 2.54%   |
| Realtek Integrated_Webcam_HD                                   | 8         | 2.25%   |
| Logitech Webcam C270                                           | 8         | 2.25%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 6         | 1.69%   |
| Sunplus Integrated_Webcam_HD                                   | 5         | 1.41%   |
| Microdia Integrated Webcam                                     | 5         | 1.41%   |
| Acer HD Webcam                                                 | 5         | 1.41%   |
| Lite-On Integrated Camera                                      | 4         | 1.13%   |
| Lite-On HP Webcam                                              | 4         | 1.13%   |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 1.13%   |
| Chicony HP Wide Vision HD Camera                               | 4         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 4         | 1.13%   |
| Acer EasyCamera                                                | 4         | 1.13%   |
| Valve Software 3D Camera                                       | 3         | 0.85%   |
| Syntek Lenovo EasyCamera                                       | 3         | 0.85%   |
| Sunplus HD WebCam                                              | 3         | 0.85%   |
| Quanta HP HD Camera                                            | 3         | 0.85%   |
| Microdia USB 2.0 Camera                                        | 3         | 0.85%   |
| Microdia Amcrest AWC2198 USB Webcam                            | 3         | 0.85%   |
| Logitech C922 Pro Stream Webcam                                | 3         | 0.85%   |
| IMC Networks ov9734_azurewave_camera                           | 3         | 0.85%   |
| Chicony HD User Facing                                         | 3         | 0.85%   |
| Chicony EasyCamera                                             | 3         | 0.85%   |
| Apple FaceTime HD Camera (Built-in)                            | 3         | 0.85%   |
| Unknown 720p HD Camera                                         | 2         | 0.56%   |
| Syntek EasyCamera                                              | 2         | 0.56%   |
| Sunplus ASUS USB2.0 Webcam                                     | 2         | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 0.56%   |
| Samsung Galaxy A5 (MTP)                                        | 2         | 0.56%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 0.56%   |
| Quanta HD Camera                                               | 2         | 0.56%   |
| Microsoft LifeCam HD-3000                                      | 2         | 0.56%   |
| Microdia Dell Integrated HD Webcam                             | 2         | 0.56%   |
| Luxvisions Innotech Limited Integrated Camera                  | 2         | 0.56%   |
| Logitech Webcam C310                                           | 2         | 0.56%   |
| Logitech Webcam C170                                           | 2         | 0.56%   |
| Logitech C920 PRO HD Webcam                                    | 2         | 0.56%   |
| Lite-On HP Wide Vision HD Camera                               | 2         | 0.56%   |
| Intel RealSense 3D Camera (Front F200)                         | 2         | 0.56%   |
| IMC Networks XiaoMi Webcam                                     | 2         | 0.56%   |
| HP Webcam HD 2300                                              | 2         | 0.56%   |
| Google Nexus/Pixel Device (MTP + debug)                        | 2         | 0.56%   |
| Chicony VGA Webcam                                             | 2         | 0.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 2         | 0.56%   |
| Chicony HP Webcam                                              | 2         | 0.56%   |
| Chicony HP TrueVision HD                                       | 2         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 0.56%   |
| Acer SunplusIT Integrated Camera                               | 2         | 0.56%   |
| Y Media USB Camera                                             | 1         | 0.28%   |
| Xiaomi Mi/Redmi series (PTP + ADB)                             | 1         | 0.28%   |
| Trust Full HD Webcam                                           | 1         | 0.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 25        | 36.76%  |
| Validity Sensors           | 17        | 25%     |
| Shenzhen Goodix Technology | 13        | 19.12%  |
| Elan Microelectronics      | 6         | 8.82%   |
| LighTuning Technology      | 5         | 7.35%   |
| Upek                       | 1         | 1.47%   |
| Samsung Electronics        | 1         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 10        | 14.71%  |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 11.76%  |
| Synaptics  WBDI                                                            | 6         | 8.82%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 7.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 7.35%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 7.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 5.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 5.88%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.94%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.94%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.47%   |
| Validity Sensors VFS491                                                    | 1         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.47%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.47%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.47%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.47%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.47%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 53.57%  |
| Alcor Micro | 10        | 35.71%  |
| O2 Micro    | 1         | 3.57%   |
| Lenovo      | 1         | 3.57%   |
| HID Global  | 1         | 3.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 34.48%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 31.03%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 10.34%  |
| Broadcom 58200                                                               | 3         | 10.34%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.45%   |
| HID Global USB Reader V3                                                     | 1         | 3.45%   |
| Broadcom 5880                                                                | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 358       | 65.93%  |
| 1     | 154       | 28.36%  |
| 2     | 30        | 5.52%   |
| 3     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 68        | 33.17%  |
| Net/ethernet             | 32        | 15.61%  |
| Chipcard                 | 27        | 13.17%  |
| Multimedia controller    | 21        | 10.24%  |
| Graphics card            | 19        | 9.27%   |
| Net/wireless             | 11        | 5.37%   |
| Camera                   | 8         | 3.9%    |
| Network                  | 7         | 3.41%   |
| Bluetooth                | 6         | 2.93%   |
| Unassigned class         | 1         | 0.49%   |
| Storage                  | 1         | 0.49%   |
| Sound                    | 1         | 0.49%   |
| Modem                    | 1         | 0.49%   |
| Dvb card                 | 1         | 0.49%   |
| Communication controller | 1         | 0.49%   |

