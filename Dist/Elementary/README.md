Elementary - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Elementary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

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

Total: 3366

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f10a2b06fd](https://linux-hardware.org/?probe=f10a2b06fd) | Jan 06, 2025 |
| MSI           | G31TM-P21                   | Desktop     | [7f868dd6f9](https://linux-hardware.org/?probe=7f868dd6f9) | Jan 06, 2025 |
| Samsung       | 900X3C/900X4C/900X4D        | Notebook    | [cbe6ed9631](https://linux-hardware.org/?probe=cbe6ed9631) | Jan 05, 2025 |
| Digma Pro     | Minimax U1 DPP5-8CXN01      | Mini pc     | [c6d2f011fa](https://linux-hardware.org/?probe=c6d2f011fa) | Jan 05, 2025 |
| Dell          | Inspiron 1545               | Notebook    | [6d5ccbb5f9](https://linux-hardware.org/?probe=6d5ccbb5f9) | Jan 05, 2025 |
| Dell          | XPS L412Z                   | Notebook    | [d8b969a9e6](https://linux-hardware.org/?probe=d8b969a9e6) | Jan 05, 2025 |
| Dell          | XPS L412Z                   | Notebook    | [f4cfef6dcc](https://linux-hardware.org/?probe=f4cfef6dcc) | Jan 05, 2025 |
| Apple         | MacBook3,1                  | Notebook    | [be78213991](https://linux-hardware.org/?probe=be78213991) | Jan 05, 2025 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [79752b904b](https://linux-hardware.org/?probe=79752b904b) | Jan 04, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [d5f19c64ad](https://linux-hardware.org/?probe=d5f19c64ad) | Jan 04, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [7961299452](https://linux-hardware.org/?probe=7961299452) | Jan 04, 2025 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [bbf6d05761](https://linux-hardware.org/?probe=bbf6d05761) | Jan 03, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [c208215b7f](https://linux-hardware.org/?probe=c208215b7f) | Jan 03, 2025 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [7b1adcdde1](https://linux-hardware.org/?probe=7b1adcdde1) | Jan 03, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [cacf1ad26f](https://linux-hardware.org/?probe=cacf1ad26f) | Jan 02, 2025 |
| Lenovo        | G585 20137                  | Notebook    | [f7dac7bbad](https://linux-hardware.org/?probe=f7dac7bbad) | Jan 02, 2025 |
| Intel         | H61                         | Desktop     | [0f76193421](https://linux-hardware.org/?probe=0f76193421) | Jan 02, 2025 |
| Medion        | Akoya E6240T                | Notebook    | [dc4b306a46](https://linux-hardware.org/?probe=dc4b306a46) | Jan 02, 2025 |
| Dell          | Latitude 5400               | Notebook    | [7a418a2cca](https://linux-hardware.org/?probe=7a418a2cca) | Jan 01, 2025 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f7cc7cc8d1](https://linux-hardware.org/?probe=f7cc7cc8d1) | Jan 01, 2025 |
| MSI           | A88XM-E35 V2                | Desktop     | [d3df8a394a](https://linux-hardware.org/?probe=d3df8a394a) | Dec 30, 2024 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [1de7d2e8fb](https://linux-hardware.org/?probe=1de7d2e8fb) | Dec 30, 2024 |
| ASUSTek       | H110M-D                     | Desktop     | [a61b42dd42](https://linux-hardware.org/?probe=a61b42dd42) | Dec 29, 2024 |
| ASUSTek       | X555LDB                     | Notebook    | [f11b5b7320](https://linux-hardware.org/?probe=f11b5b7320) | Dec 29, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [e36139662d](https://linux-hardware.org/?probe=e36139662d) | Dec 28, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [3dd541f1a9](https://linux-hardware.org/?probe=3dd541f1a9) | Dec 28, 2024 |
| HP            | ProBook 645 G2              | Notebook    | [b57a3a877b](https://linux-hardware.org/?probe=b57a3a877b) | Dec 27, 2024 |
| NEC Comput... | PC-LL750MSW                 | Notebook    | [55d20a7230](https://linux-hardware.org/?probe=55d20a7230) | Dec 27, 2024 |
| Dell          | Inspiron 15-3552            | Notebook    | [1d01677080](https://linux-hardware.org/?probe=1d01677080) | Dec 27, 2024 |
| Packard Be... | EasyNote TJ75               | Notebook    | [7a5bc8251a](https://linux-hardware.org/?probe=7a5bc8251a) | Dec 27, 2024 |
| Packard Be... | EasyNote TJ75               | Notebook    | [b46109e7f3](https://linux-hardware.org/?probe=b46109e7f3) | Dec 27, 2024 |
| Sony          | SVF14213CLB                 | Notebook    | [dbcabf3c36](https://linux-hardware.org/?probe=dbcabf3c36) | Dec 27, 2024 |
| Pegatron      | A15                         | Notebook    | [2649401416](https://linux-hardware.org/?probe=2649401416) | Dec 26, 2024 |
| ASRock        | X570 Extreme4               | Desktop     | [65cad1da61](https://linux-hardware.org/?probe=65cad1da61) | Dec 26, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [8230b0cf45](https://linux-hardware.org/?probe=8230b0cf45) | Dec 25, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f288e84971](https://linux-hardware.org/?probe=f288e84971) | Dec 25, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [4225950551](https://linux-hardware.org/?probe=4225950551) | Dec 25, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | Notebook    | [d1227bd0de](https://linux-hardware.org/?probe=d1227bd0de) | Dec 25, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [4c23073f21](https://linux-hardware.org/?probe=4c23073f21) | Dec 25, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [2729b6a19c](https://linux-hardware.org/?probe=2729b6a19c) | Dec 25, 2024 |
| Gigabyte      | B85M-HD3                    | Desktop     | [83d5947a2c](https://linux-hardware.org/?probe=83d5947a2c) | Dec 24, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [4e79bebde8](https://linux-hardware.org/?probe=4e79bebde8) | Dec 24, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [89e8e5ad41](https://linux-hardware.org/?probe=89e8e5ad41) | Dec 24, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [d824794995](https://linux-hardware.org/?probe=d824794995) | Dec 23, 2024 |
| Samsung       | SR58P                       | Notebook    | [70e6a978b7](https://linux-hardware.org/?probe=70e6a978b7) | Dec 23, 2024 |
| Dell          | Latitude E6520              | Notebook    | [2bae6e63bb](https://linux-hardware.org/?probe=2bae6e63bb) | Dec 23, 2024 |
| Dell          | XPS 15 9550                 | Notebook    | [f1502af093](https://linux-hardware.org/?probe=f1502af093) | Dec 23, 2024 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [a649caaa82](https://linux-hardware.org/?probe=a649caaa82) | Dec 23, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [cb4b9da83f](https://linux-hardware.org/?probe=cb4b9da83f) | Dec 22, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [59c289d5b9](https://linux-hardware.org/?probe=59c289d5b9) | Dec 22, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [48537b040b](https://linux-hardware.org/?probe=48537b040b) | Dec 22, 2024 |
| Dell          | 0MWYPT A00                  | Desktop     | [98cc5ad973](https://linux-hardware.org/?probe=98cc5ad973) | Dec 22, 2024 |
| Dell          | 0MWYPT A00                  | Desktop     | [dd73af7555](https://linux-hardware.org/?probe=dd73af7555) | Dec 22, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [762ab31569](https://linux-hardware.org/?probe=762ab31569) | Dec 22, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [4c934647d2](https://linux-hardware.org/?probe=4c934647d2) | Dec 21, 2024 |
| ASUSTek       | X555LDB                     | Notebook    | [783e6ed502](https://linux-hardware.org/?probe=783e6ed502) | Dec 20, 2024 |
| AWOW          | NY PC BOX                   | Mini pc     | [d787dd8103](https://linux-hardware.org/?probe=d787dd8103) | Dec 20, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [8e8317c6a6](https://linux-hardware.org/?probe=8e8317c6a6) | Dec 19, 2024 |
| ASUSTek       | UX30                        | Notebook    | [d75f3afdf6](https://linux-hardware.org/?probe=d75f3afdf6) | Dec 18, 2024 |
| Dell          | Precision 5530              | Notebook    | [3292cf1103](https://linux-hardware.org/?probe=3292cf1103) | Dec 18, 2024 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9a64691207](https://linux-hardware.org/?probe=9a64691207) | Dec 17, 2024 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [987844d0b8](https://linux-hardware.org/?probe=987844d0b8) | Dec 17, 2024 |
| HP            | 8266                        | Desktop     | [ccd7d6b235](https://linux-hardware.org/?probe=ccd7d6b235) | Dec 17, 2024 |
| ASUSTek       | X751MA                      | Notebook    | [016d948a0c](https://linux-hardware.org/?probe=016d948a0c) | Dec 17, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [03d550b439](https://linux-hardware.org/?probe=03d550b439) | Dec 17, 2024 |
| GEEKOM        | A8                          | Desktop     | [821fae98e5](https://linux-hardware.org/?probe=821fae98e5) | Dec 17, 2024 |
| HP            | Pavilion dv6                | Notebook    | [89ec19d64a](https://linux-hardware.org/?probe=89ec19d64a) | Dec 17, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [28d3412139](https://linux-hardware.org/?probe=28d3412139) | Dec 17, 2024 |
| HP            | Laptop 17-by3xxx            | Notebook    | [cb8341eaca](https://linux-hardware.org/?probe=cb8341eaca) | Dec 17, 2024 |
| Pegatron      | A15                         | Notebook    | [266dd27eba](https://linux-hardware.org/?probe=266dd27eba) | Dec 16, 2024 |
| HP            | 83E8                        | Desktop     | [77d40d025a](https://linux-hardware.org/?probe=77d40d025a) | Dec 16, 2024 |
| Intel         | Unknown                     | Desktop     | [fcbbdc5c06](https://linux-hardware.org/?probe=fcbbdc5c06) | Dec 16, 2024 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [f521816a4d](https://linux-hardware.org/?probe=f521816a4d) | Dec 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [abfa48ae27](https://linux-hardware.org/?probe=abfa48ae27) | Dec 15, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [059cf0cd47](https://linux-hardware.org/?probe=059cf0cd47) | Dec 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [256e4c3f4a](https://linux-hardware.org/?probe=256e4c3f4a) | Dec 15, 2024 |
| HP            | ProBook 6570b               | Notebook    | [70dbe6620b](https://linux-hardware.org/?probe=70dbe6620b) | Dec 14, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [4a2f8153d2](https://linux-hardware.org/?probe=4a2f8153d2) | Dec 14, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [f9eae65d13](https://linux-hardware.org/?probe=f9eae65d13) | Dec 14, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [4427bcded0](https://linux-hardware.org/?probe=4427bcded0) | Dec 14, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [5641fb7941](https://linux-hardware.org/?probe=5641fb7941) | Dec 14, 2024 |
| HP            | 8299                        | Desktop     | [44a762b74e](https://linux-hardware.org/?probe=44a762b74e) | Dec 14, 2024 |
| HP            | 8299                        | Desktop     | [f0c7982d81](https://linux-hardware.org/?probe=f0c7982d81) | Dec 14, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [8c0f6ed012](https://linux-hardware.org/?probe=8c0f6ed012) | Dec 14, 2024 |
| Acer          | Aspire A515-48M             | Notebook    | [1bd13cf77f](https://linux-hardware.org/?probe=1bd13cf77f) | Dec 14, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [262a2aa975](https://linux-hardware.org/?probe=262a2aa975) | Dec 13, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [1ab4a28fcf](https://linux-hardware.org/?probe=1ab4a28fcf) | Dec 13, 2024 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [37664cf5d9](https://linux-hardware.org/?probe=37664cf5d9) | Dec 13, 2024 |
| Sony          | SVS1313V9RB                 | Notebook    | [52421e92ce](https://linux-hardware.org/?probe=52421e92ce) | Dec 12, 2024 |
| Sony          | SVS1313V9RB                 | Notebook    | [53c77f8751](https://linux-hardware.org/?probe=53c77f8751) | Dec 12, 2024 |
| Unknown       | Unknown                     | Notebook    | [2e17fa2c66](https://linux-hardware.org/?probe=2e17fa2c66) | Dec 12, 2024 |
| Chuwi         | UBook                       | Notebook    | [08e88467cb](https://linux-hardware.org/?probe=08e88467cb) | Dec 12, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [ad8b7d1b8f](https://linux-hardware.org/?probe=ad8b7d1b8f) | Dec 12, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [6b05e8feb0](https://linux-hardware.org/?probe=6b05e8feb0) | Dec 12, 2024 |
| ASUSTek       | X550CL                      | Notebook    | [e471757e1c](https://linux-hardware.org/?probe=e471757e1c) | Dec 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8444dbbcc1](https://linux-hardware.org/?probe=8444dbbcc1) | Dec 10, 2024 |
| Microtech     | ebookPro                    | Notebook    | [4e6f89ca56](https://linux-hardware.org/?probe=4e6f89ca56) | Dec 10, 2024 |
| Acer          | Swift SF314-56G             | Notebook    | [64815f9248](https://linux-hardware.org/?probe=64815f9248) | Dec 09, 2024 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [9319560a05](https://linux-hardware.org/?probe=9319560a05) | Dec 09, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [fc797d558c](https://linux-hardware.org/?probe=fc797d558c) | Dec 08, 2024 |
| Unknown       | Unknown                     | Notebook    | [bd30f7f45d](https://linux-hardware.org/?probe=bd30f7f45d) | Dec 08, 2024 |
| HP            | 82C0                        | Mini pc     | [f6987473a1](https://linux-hardware.org/?probe=f6987473a1) | Dec 07, 2024 |
| Dell          | Latitude 3340               | Notebook    | [07c627667a](https://linux-hardware.org/?probe=07c627667a) | Dec 07, 2024 |
| HP            | Laptop 17z-ca100            | Notebook    | [e6144203c6](https://linux-hardware.org/?probe=e6144203c6) | Dec 07, 2024 |
| SK hynix      | 10WWA464B                   | Tablet      | [56ca392159](https://linux-hardware.org/?probe=56ca392159) | Dec 07, 2024 |
| eMachines     | eME732Z                     | Notebook    | [1c64772130](https://linux-hardware.org/?probe=1c64772130) | Dec 06, 2024 |
| Panasonic     | CF-52PFP54QL                | Notebook    | [bcafd21454](https://linux-hardware.org/?probe=bcafd21454) | Dec 06, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3c0b439ef8](https://linux-hardware.org/?probe=3c0b439ef8) | Dec 06, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [477a7b324b](https://linux-hardware.org/?probe=477a7b324b) | Dec 06, 2024 |
| HUAWEI        | BC11HGSA0 V100R003          | Server      | [ea4033794a](https://linux-hardware.org/?probe=ea4033794a) | Dec 05, 2024 |
| Lenovo        | IdeaPad S205 1038D8G        | Notebook    | [78b460173f](https://linux-hardware.org/?probe=78b460173f) | Dec 05, 2024 |
| Chuwi         | UBook                       | Notebook    | [ddba94874a](https://linux-hardware.org/?probe=ddba94874a) | Dec 04, 2024 |
| HP            | Pavilion dv7                | Notebook    | [8d22c82b8d](https://linux-hardware.org/?probe=8d22c82b8d) | Dec 04, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [915a1dbb22](https://linux-hardware.org/?probe=915a1dbb22) | Dec 04, 2024 |
| HP            | EliteBook 2170p             | Notebook    | [39de9fd95f](https://linux-hardware.org/?probe=39de9fd95f) | Dec 04, 2024 |
| Intel         | B75 V1.1                    | Desktop     | [d6aad9d651](https://linux-hardware.org/?probe=d6aad9d651) | Dec 03, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [8517a48127](https://linux-hardware.org/?probe=8517a48127) | Dec 03, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [c2dd28599e](https://linux-hardware.org/?probe=c2dd28599e) | Dec 03, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [085d5938c0](https://linux-hardware.org/?probe=085d5938c0) | Dec 03, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [99cb99a15c](https://linux-hardware.org/?probe=99cb99a15c) | Dec 03, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [f0195c6929](https://linux-hardware.org/?probe=f0195c6929) | Dec 02, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [a12ee189e3](https://linux-hardware.org/?probe=a12ee189e3) | Dec 02, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [1a9a544a72](https://linux-hardware.org/?probe=1a9a544a72) | Dec 02, 2024 |
| Intel         | X99-P4 V5.11                | Desktop     | [b5079a1a8d](https://linux-hardware.org/?probe=b5079a1a8d) | Dec 02, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [114cab1a48](https://linux-hardware.org/?probe=114cab1a48) | Dec 02, 2024 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [ffa565d696](https://linux-hardware.org/?probe=ffa565d696) | Dec 02, 2024 |
| Intel         | D945GCL AAD75361-301        | Desktop     | [f04b1a58c2](https://linux-hardware.org/?probe=f04b1a58c2) | Dec 01, 2024 |
| Intel         | D945GCL AAD75361-301        | Desktop     | [fc715bb336](https://linux-hardware.org/?probe=fc715bb336) | Dec 01, 2024 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [dde09fe131](https://linux-hardware.org/?probe=dde09fe131) | Dec 01, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [424834b527](https://linux-hardware.org/?probe=424834b527) | Dec 01, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [deda79f6f5](https://linux-hardware.org/?probe=deda79f6f5) | Dec 01, 2024 |
| ASRock        | H310CM-HG4                  | Desktop     | [86f4d79f62](https://linux-hardware.org/?probe=86f4d79f62) | Dec 01, 2024 |
| ASUSTek       | K93SV                       | Notebook    | [53af6a8e17](https://linux-hardware.org/?probe=53af6a8e17) | Nov 30, 2024 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [7b063d3dd7](https://linux-hardware.org/?probe=7b063d3dd7) | Nov 30, 2024 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [b69d5786a5](https://linux-hardware.org/?probe=b69d5786a5) | Nov 30, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [344eaec320](https://linux-hardware.org/?probe=344eaec320) | Nov 29, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [f7578fb476](https://linux-hardware.org/?probe=f7578fb476) | Nov 29, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [a817c04b09](https://linux-hardware.org/?probe=a817c04b09) | Nov 29, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [dbc6940414](https://linux-hardware.org/?probe=dbc6940414) | Nov 29, 2024 |
| HP            | Pavilion dv7                | Notebook    | [1ae9d9a604](https://linux-hardware.org/?probe=1ae9d9a604) | Nov 29, 2024 |
| Dell          | Latitude 5420               | Notebook    | [9e6c2d1825](https://linux-hardware.org/?probe=9e6c2d1825) | Nov 28, 2024 |
| MicroByte     | ezbook                      | Notebook    | [167d9d082a](https://linux-hardware.org/?probe=167d9d082a) | Nov 28, 2024 |
| HP            | 3647h                       | Desktop     | [de1eb15f76](https://linux-hardware.org/?probe=de1eb15f76) | Nov 28, 2024 |
| Google        | Delbin                      | Notebook    | [e4f8dab394](https://linux-hardware.org/?probe=e4f8dab394) | Nov 27, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [7e022f0097](https://linux-hardware.org/?probe=7e022f0097) | Nov 27, 2024 |
| Apple         | Mac-F2218FA9                | All in one  | [3972b418fc](https://linux-hardware.org/?probe=3972b418fc) | Nov 27, 2024 |
| Lenovo        | ThinkCentre M81 7517A2F     | Desktop     | [51de0395d0](https://linux-hardware.org/?probe=51de0395d0) | Nov 27, 2024 |
| Acer          | Aspire E3-111               | Notebook    | [f90ddc6433](https://linux-hardware.org/?probe=f90ddc6433) | Nov 26, 2024 |
| Lenovo        | ThinkCentre M81 7517A2F     | Desktop     | [6ae2f479e0](https://linux-hardware.org/?probe=6ae2f479e0) | Nov 26, 2024 |
| Apple         | Mac-F2218FA9                | All in one  | [73767665be](https://linux-hardware.org/?probe=73767665be) | Nov 26, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [a42587525c](https://linux-hardware.org/?probe=a42587525c) | Nov 25, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [1d464cc8ce](https://linux-hardware.org/?probe=1d464cc8ce) | Nov 25, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [d24fd529d4](https://linux-hardware.org/?probe=d24fd529d4) | Nov 25, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [0b3205081d](https://linux-hardware.org/?probe=0b3205081d) | Nov 22, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [d7914ef50d](https://linux-hardware.org/?probe=d7914ef50d) | Nov 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [8ecfb38136](https://linux-hardware.org/?probe=8ecfb38136) | Nov 22, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [582b81fd6f](https://linux-hardware.org/?probe=582b81fd6f) | Nov 22, 2024 |
| ASRock        | 945GCM-S                    | Desktop     | [c1060979e3](https://linux-hardware.org/?probe=c1060979e3) | Nov 21, 2024 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [c785c1f7dd](https://linux-hardware.org/?probe=c785c1f7dd) | Nov 21, 2024 |
| HP            | ProBook 6560b               | Notebook    | [72ddcb1cf2](https://linux-hardware.org/?probe=72ddcb1cf2) | Nov 20, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [058f6bf1ac](https://linux-hardware.org/?probe=058f6bf1ac) | Nov 20, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [541dd7b9fb](https://linux-hardware.org/?probe=541dd7b9fb) | Nov 19, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [3f2eff0083](https://linux-hardware.org/?probe=3f2eff0083) | Nov 18, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [bf3651f419](https://linux-hardware.org/?probe=bf3651f419) | Nov 18, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b5f2062c2c](https://linux-hardware.org/?probe=b5f2062c2c) | Nov 18, 2024 |
| Lenovo        | ThinkPad X260 20F5A2FXTH    | Notebook    | [8609525ceb](https://linux-hardware.org/?probe=8609525ceb) | Nov 18, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [7d86d39596](https://linux-hardware.org/?probe=7d86d39596) | Nov 17, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [001f8b1280](https://linux-hardware.org/?probe=001f8b1280) | Nov 17, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | Notebook    | [8715440da3](https://linux-hardware.org/?probe=8715440da3) | Nov 17, 2024 |
| Dell          | Inspiron N5030              | Notebook    | [acf692231b](https://linux-hardware.org/?probe=acf692231b) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [0d4cb9a88f](https://linux-hardware.org/?probe=0d4cb9a88f) | Nov 16, 2024 |
| HP            | 1998                        | Desktop     | [021e8262ce](https://linux-hardware.org/?probe=021e8262ce) | Nov 16, 2024 |
| Lenovo        | G50-80 80L0                 | Notebook    | [d31664cad1](https://linux-hardware.org/?probe=d31664cad1) | Nov 15, 2024 |
| HP            | 212B                        | Desktop     | [35097b8ab0](https://linux-hardware.org/?probe=35097b8ab0) | Nov 15, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [0259216292](https://linux-hardware.org/?probe=0259216292) | Nov 15, 2024 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [9d0d676179](https://linux-hardware.org/?probe=9d0d676179) | Nov 14, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7029186fa5](https://linux-hardware.org/?probe=7029186fa5) | Nov 14, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [2f0fa7a4fa](https://linux-hardware.org/?probe=2f0fa7a4fa) | Nov 11, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [fc06ee6598](https://linux-hardware.org/?probe=fc06ee6598) | Nov 10, 2024 |
| Dell          | 0T4VP9 A00                  | All in one  | [939efc4955](https://linux-hardware.org/?probe=939efc4955) | Nov 10, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [68c27eb24c](https://linux-hardware.org/?probe=68c27eb24c) | Nov 10, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [a6930afc53](https://linux-hardware.org/?probe=a6930afc53) | Nov 10, 2024 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [155af73dbd](https://linux-hardware.org/?probe=155af73dbd) | Nov 10, 2024 |
| Winnovo       | Vocbook                     | Convertible | [be7ba030af](https://linux-hardware.org/?probe=be7ba030af) | Nov 09, 2024 |
| Apple         | MacBookPro5,2               | Notebook    | [a0db5bcf03](https://linux-hardware.org/?probe=a0db5bcf03) | Nov 08, 2024 |
| Acer          | Aspire E5-771               | Notebook    | [9b889ed10a](https://linux-hardware.org/?probe=9b889ed10a) | Nov 08, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [41cbe4313e](https://linux-hardware.org/?probe=41cbe4313e) | Nov 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [0b5989c295](https://linux-hardware.org/?probe=0b5989c295) | Nov 06, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [71249fccac](https://linux-hardware.org/?probe=71249fccac) | Nov 06, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [ebcff700e9](https://linux-hardware.org/?probe=ebcff700e9) | Nov 06, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f37b129292](https://linux-hardware.org/?probe=f37b129292) | Nov 05, 2024 |
| LTD Delovo... | 15Y                         | Notebook    | [5553e46796](https://linux-hardware.org/?probe=5553e46796) | Nov 04, 2024 |
| LTD Delovo... | 15Y                         | Notebook    | [0187f0b5ab](https://linux-hardware.org/?probe=0187f0b5ab) | Nov 04, 2024 |
| Samsung       | 940XFG                      | Notebook    | [8d09e8db06](https://linux-hardware.org/?probe=8d09e8db06) | Nov 04, 2024 |
| Gigabyte      | B550 UD AC-Y1               | Desktop     | [f146362156](https://linux-hardware.org/?probe=f146362156) | Nov 04, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [f0b28bde30](https://linux-hardware.org/?probe=f0b28bde30) | Nov 03, 2024 |
| Dell          | Latitude 7420               | Notebook    | [2454ee0dbb](https://linux-hardware.org/?probe=2454ee0dbb) | Nov 03, 2024 |
| Lenovo        | G700 20251                  | Notebook    | [3af4ad6599](https://linux-hardware.org/?probe=3af4ad6599) | Nov 01, 2024 |
| Acer          | Aspire V3-772               | Notebook    | [9d4e69ab29](https://linux-hardware.org/?probe=9d4e69ab29) | Nov 01, 2024 |
| Acer          | Aspire V3-772               | Notebook    | [a48e5acfb4](https://linux-hardware.org/?probe=a48e5acfb4) | Nov 01, 2024 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [a8d14fa552](https://linux-hardware.org/?probe=a8d14fa552) | Nov 01, 2024 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [b39c2af6f5](https://linux-hardware.org/?probe=b39c2af6f5) | Oct 31, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [55ef342a18](https://linux-hardware.org/?probe=55ef342a18) | Oct 31, 2024 |
| HP            | ProBook 4535s               | Notebook    | [f66c124f3a](https://linux-hardware.org/?probe=f66c124f3a) | Oct 31, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [ed3df2f39c](https://linux-hardware.org/?probe=ed3df2f39c) | Oct 31, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [3fe4d1a80a](https://linux-hardware.org/?probe=3fe4d1a80a) | Oct 31, 2024 |
| ASUSTek       | K46CB                       | Notebook    | [e081c9ab8c](https://linux-hardware.org/?probe=e081c9ab8c) | Oct 30, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [91eb0db216](https://linux-hardware.org/?probe=91eb0db216) | Oct 30, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [0e0a0fd3c5](https://linux-hardware.org/?probe=0e0a0fd3c5) | Oct 30, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1755d407c9](https://linux-hardware.org/?probe=1755d407c9) | Oct 29, 2024 |
| HP            | Compaq 15                   | Notebook    | [fd2b849a08](https://linux-hardware.org/?probe=fd2b849a08) | Oct 28, 2024 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3cf2d45223](https://linux-hardware.org/?probe=3cf2d45223) | Oct 28, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd7ca76c96](https://linux-hardware.org/?probe=cd7ca76c96) | Oct 27, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [59f6758081](https://linux-hardware.org/?probe=59f6758081) | Oct 25, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [73fb34d315](https://linux-hardware.org/?probe=73fb34d315) | Oct 25, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c4829d7d0c](https://linux-hardware.org/?probe=c4829d7d0c) | Oct 25, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e114c5afe5](https://linux-hardware.org/?probe=e114c5afe5) | Oct 24, 2024 |
| Dell          | Latitude 7370               | Notebook    | [355bbe7ecc](https://linux-hardware.org/?probe=355bbe7ecc) | Oct 24, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [92672f3d2c](https://linux-hardware.org/?probe=92672f3d2c) | Oct 23, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [8bbb5c5a53](https://linux-hardware.org/?probe=8bbb5c5a53) | Oct 23, 2024 |
| HP            | ProBook 6465b               | Notebook    | [3afb9ebed6](https://linux-hardware.org/?probe=3afb9ebed6) | Oct 23, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [ee7a3727e4](https://linux-hardware.org/?probe=ee7a3727e4) | Oct 23, 2024 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [1d8bed869f](https://linux-hardware.org/?probe=1d8bed869f) | Oct 23, 2024 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [18058066d2](https://linux-hardware.org/?probe=18058066d2) | Oct 22, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [a899fd963a](https://linux-hardware.org/?probe=a899fd963a) | Oct 22, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [6c25a578b8](https://linux-hardware.org/?probe=6c25a578b8) | Oct 22, 2024 |
| Sony          | VPCEJ1Z1E                   | Notebook    | [d1da65abb4](https://linux-hardware.org/?probe=d1da65abb4) | Oct 22, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [25dc97604a](https://linux-hardware.org/?probe=25dc97604a) | Oct 22, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [76d8c86d01](https://linux-hardware.org/?probe=76d8c86d01) | Oct 22, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [5cca2e9488](https://linux-hardware.org/?probe=5cca2e9488) | Oct 22, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [faeb5479f8](https://linux-hardware.org/?probe=faeb5479f8) | Oct 21, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e188597923](https://linux-hardware.org/?probe=e188597923) | Oct 19, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [f63adab3c7](https://linux-hardware.org/?probe=f63adab3c7) | Oct 19, 2024 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [afb324991b](https://linux-hardware.org/?probe=afb324991b) | Oct 18, 2024 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [3337802835](https://linux-hardware.org/?probe=3337802835) | Oct 18, 2024 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [c16cede43b](https://linux-hardware.org/?probe=c16cede43b) | Oct 18, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [4792d62928](https://linux-hardware.org/?probe=4792d62928) | Oct 17, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [83508d3840](https://linux-hardware.org/?probe=83508d3840) | Oct 17, 2024 |
| Samsung       | 940XFG                      | Notebook    | [741f7a6544](https://linux-hardware.org/?probe=741f7a6544) | Oct 17, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [d3b5f5da93](https://linux-hardware.org/?probe=d3b5f5da93) | Oct 17, 2024 |
| HP            | 2B3B                        | All in one  | [83af71f2e9](https://linux-hardware.org/?probe=83af71f2e9) | Oct 16, 2024 |
| HP            | 2B3B                        | All in one  | [6eb2a2cd32](https://linux-hardware.org/?probe=6eb2a2cd32) | Oct 16, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d0ac53c68a](https://linux-hardware.org/?probe=d0ac53c68a) | Oct 16, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [043f4904ae](https://linux-hardware.org/?probe=043f4904ae) | Oct 15, 2024 |
| Acer          | Aspire 7736                 | Notebook    | [be7f2e237f](https://linux-hardware.org/?probe=be7f2e237f) | Oct 15, 2024 |
| ASUSTek       | X555LPB                     | Notebook    | [2f3f2073da](https://linux-hardware.org/?probe=2f3f2073da) | Oct 14, 2024 |
| Acer          | Aspire 7736                 | Notebook    | [96c83e0281](https://linux-hardware.org/?probe=96c83e0281) | Oct 14, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [d2d644c166](https://linux-hardware.org/?probe=d2d644c166) | Oct 13, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [0615e499e7](https://linux-hardware.org/?probe=0615e499e7) | Oct 13, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [cee555c4f8](https://linux-hardware.org/?probe=cee555c4f8) | Oct 13, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [030dbaca80](https://linux-hardware.org/?probe=030dbaca80) | Oct 13, 2024 |
| Positivo      | VJF154                      | Notebook    | [dbd1be19a4](https://linux-hardware.org/?probe=dbd1be19a4) | Oct 12, 2024 |
| Positivo      | VJF154                      | Notebook    | [11a95affa0](https://linux-hardware.org/?probe=11a95affa0) | Oct 12, 2024 |
| Sony          | VPCEJ1Z1E                   | Notebook    | [627da18a5d](https://linux-hardware.org/?probe=627da18a5d) | Oct 12, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [8a25a02400](https://linux-hardware.org/?probe=8a25a02400) | Oct 12, 2024 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [2db6bf65e8](https://linux-hardware.org/?probe=2db6bf65e8) | Oct 12, 2024 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [a9cb352415](https://linux-hardware.org/?probe=a9cb352415) | Oct 12, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [ca109e5057](https://linux-hardware.org/?probe=ca109e5057) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [08d25ef16b](https://linux-hardware.org/?probe=08d25ef16b) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [6c5d0a8a4b](https://linux-hardware.org/?probe=6c5d0a8a4b) | Oct 12, 2024 |
| HP            | 15                          | Notebook    | [812b65f0fe](https://linux-hardware.org/?probe=812b65f0fe) | Oct 11, 2024 |
| HP            | 829E                        | Mini pc     | [ef4f5e2642](https://linux-hardware.org/?probe=ef4f5e2642) | Oct 11, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [3623e327b2](https://linux-hardware.org/?probe=3623e327b2) | Oct 11, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [64cebe30ad](https://linux-hardware.org/?probe=64cebe30ad) | Oct 10, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [c6f89b972d](https://linux-hardware.org/?probe=c6f89b972d) | Oct 09, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [425000adaf](https://linux-hardware.org/?probe=425000adaf) | Oct 08, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [bf025aaa26](https://linux-hardware.org/?probe=bf025aaa26) | Oct 08, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [ecf4696b37](https://linux-hardware.org/?probe=ecf4696b37) | Oct 07, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [01cd6549a5](https://linux-hardware.org/?probe=01cd6549a5) | Oct 06, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [0f138dcac0](https://linux-hardware.org/?probe=0f138dcac0) | Oct 06, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [c8c6a6269b](https://linux-hardware.org/?probe=c8c6a6269b) | Oct 06, 2024 |
| ARCELIK       | 1M7-GNB1595B6I7             | Notebook    | [cbf522f76a](https://linux-hardware.org/?probe=cbf522f76a) | Oct 05, 2024 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [38dabad22e](https://linux-hardware.org/?probe=38dabad22e) | Oct 05, 2024 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [11ca375fb2](https://linux-hardware.org/?probe=11ca375fb2) | Oct 05, 2024 |
| Sony          | VPCEC3L1E                   | Notebook    | [748694aa38](https://linux-hardware.org/?probe=748694aa38) | Oct 05, 2024 |
| Dell          | 0P096C A00                  | Desktop     | [29a648fa32](https://linux-hardware.org/?probe=29a648fa32) | Oct 05, 2024 |
| Dell          | 0P096C A00                  | Desktop     | [5a4a3dac5c](https://linux-hardware.org/?probe=5a4a3dac5c) | Oct 05, 2024 |
| Positivo      | VJF154                      | Notebook    | [70bb906734](https://linux-hardware.org/?probe=70bb906734) | Oct 04, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [bafb1e1519](https://linux-hardware.org/?probe=bafb1e1519) | Oct 04, 2024 |
| Dell          | Latitude E6520              | Notebook    | [5af0de6a9c](https://linux-hardware.org/?probe=5af0de6a9c) | Oct 04, 2024 |
| Dell          | Precision 5530              | Notebook    | [7d736763e8](https://linux-hardware.org/?probe=7d736763e8) | Oct 04, 2024 |
| Alienware     | 17 R3                       | Notebook    | [b22f85d157](https://linux-hardware.org/?probe=b22f85d157) | Oct 03, 2024 |
| Samsung       | 900X3F                      | Notebook    | [12e6b46207](https://linux-hardware.org/?probe=12e6b46207) | Oct 03, 2024 |
| Samsung       | 900X3F                      | Notebook    | [5b7f51059a](https://linux-hardware.org/?probe=5b7f51059a) | Oct 03, 2024 |
| Intel         | JSL MRD                     | Desktop     | [6be233c711](https://linux-hardware.org/?probe=6be233c711) | Oct 02, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a3cab13a1b](https://linux-hardware.org/?probe=a3cab13a1b) | Oct 02, 2024 |
| HP            | G60                         | Notebook    | [b2cbfa9c26](https://linux-hardware.org/?probe=b2cbfa9c26) | Oct 02, 2024 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [b9f265012b](https://linux-hardware.org/?probe=b9f265012b) | Oct 01, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1046a844db](https://linux-hardware.org/?probe=1046a844db) | Sep 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [bfd414e273](https://linux-hardware.org/?probe=bfd414e273) | Sep 30, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [39053cddd2](https://linux-hardware.org/?probe=39053cddd2) | Sep 29, 2024 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [add5dd6115](https://linux-hardware.org/?probe=add5dd6115) | Sep 29, 2024 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [a0e31d8395](https://linux-hardware.org/?probe=a0e31d8395) | Sep 29, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [f6c50cc494](https://linux-hardware.org/?probe=f6c50cc494) | Sep 28, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [ea1547836b](https://linux-hardware.org/?probe=ea1547836b) | Sep 27, 2024 |
| Intel         | IPC-ADN2L                   | Desktop     | [7aaa04ef0f](https://linux-hardware.org/?probe=7aaa04ef0f) | Sep 27, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [ce465db6d8](https://linux-hardware.org/?probe=ce465db6d8) | Sep 26, 2024 |
| realme        | RMNBXXXX                    | Notebook    | [a56e71a36d](https://linux-hardware.org/?probe=a56e71a36d) | Sep 25, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [eb1144d5d0](https://linux-hardware.org/?probe=eb1144d5d0) | Sep 23, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8fe6745261](https://linux-hardware.org/?probe=8fe6745261) | Sep 23, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [d02c3ea8d2](https://linux-hardware.org/?probe=d02c3ea8d2) | Sep 22, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [de3ad3dcb2](https://linux-hardware.org/?probe=de3ad3dcb2) | Sep 22, 2024 |
| Acer          | Aspire E5-511G              | Notebook    | [eb212c1295](https://linux-hardware.org/?probe=eb212c1295) | Sep 21, 2024 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [7259f3460a](https://linux-hardware.org/?probe=7259f3460a) | Sep 21, 2024 |
| Samsung       | 900X3J                      | Notebook    | [84b81dc973](https://linux-hardware.org/?probe=84b81dc973) | Sep 19, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [754a9d1a14](https://linux-hardware.org/?probe=754a9d1a14) | Sep 19, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [0bc35e551d](https://linux-hardware.org/?probe=0bc35e551d) | Sep 18, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [e386b9f60a](https://linux-hardware.org/?probe=e386b9f60a) | Sep 18, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [22c790176f](https://linux-hardware.org/?probe=22c790176f) | Sep 18, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [96ebcfea10](https://linux-hardware.org/?probe=96ebcfea10) | Sep 18, 2024 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [a44bd15d85](https://linux-hardware.org/?probe=a44bd15d85) | Sep 17, 2024 |
| Acer          | Aspire E5-511G              | Notebook    | [0b1a846a69](https://linux-hardware.org/?probe=0b1a846a69) | Sep 17, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [a2f78f9d5a](https://linux-hardware.org/?probe=a2f78f9d5a) | Sep 17, 2024 |
| HP            | Pavilion 17                 | Notebook    | [fb7884d776](https://linux-hardware.org/?probe=fb7884d776) | Sep 16, 2024 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f73ff9c739](https://linux-hardware.org/?probe=f73ff9c739) | Sep 16, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [79316bc8bf](https://linux-hardware.org/?probe=79316bc8bf) | Sep 16, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [d030037b8b](https://linux-hardware.org/?probe=d030037b8b) | Sep 14, 2024 |
| Acer          | Aspire 7745G                | Notebook    | [76a55f9bb1](https://linux-hardware.org/?probe=76a55f9bb1) | Sep 14, 2024 |
| Dell          | Inspiron 3721               | Notebook    | [dd0fd36c69](https://linux-hardware.org/?probe=dd0fd36c69) | Sep 14, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7a6f092e7a](https://linux-hardware.org/?probe=7a6f092e7a) | Sep 13, 2024 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [156f5f004e](https://linux-hardware.org/?probe=156f5f004e) | Sep 13, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [ce91008479](https://linux-hardware.org/?probe=ce91008479) | Sep 13, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [ca52ff1c29](https://linux-hardware.org/?probe=ca52ff1c29) | Sep 13, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [9f8697d54c](https://linux-hardware.org/?probe=9f8697d54c) | Sep 13, 2024 |
| Alienware     | 17 R3                       | Notebook    | [d95edb94cd](https://linux-hardware.org/?probe=d95edb94cd) | Sep 13, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [bb130f4634](https://linux-hardware.org/?probe=bb130f4634) | Sep 11, 2024 |
| ASUSTek       | ET2700I                     | Desktop     | [0faf2541ce](https://linux-hardware.org/?probe=0faf2541ce) | Sep 11, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [0c7144d06b](https://linux-hardware.org/?probe=0c7144d06b) | Sep 10, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [cd6caa40b8](https://linux-hardware.org/?probe=cd6caa40b8) | Sep 10, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [62da51972f](https://linux-hardware.org/?probe=62da51972f) | Sep 10, 2024 |
| HP            | 8620                        | Mini pc     | [08d49cd98c](https://linux-hardware.org/?probe=08d49cd98c) | Sep 10, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [38ef54ca0c](https://linux-hardware.org/?probe=38ef54ca0c) | Sep 09, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [3e57e1486e](https://linux-hardware.org/?probe=3e57e1486e) | Sep 09, 2024 |
| Intel         | IPC-ADN2L                   | Desktop     | [274c57803d](https://linux-hardware.org/?probe=274c57803d) | Sep 09, 2024 |
| Sony          | SVF15A1B4E                  | Notebook    | [08c43f2d50](https://linux-hardware.org/?probe=08c43f2d50) | Sep 09, 2024 |
| Pegatron      | 2A94h                       | Desktop     | [5a721a5edc](https://linux-hardware.org/?probe=5a721a5edc) | Sep 08, 2024 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [c5902bc488](https://linux-hardware.org/?probe=c5902bc488) | Sep 06, 2024 |
| Gigabyte      | H81M-S2H                    | Desktop     | [8c3768316c](https://linux-hardware.org/?probe=8c3768316c) | Sep 05, 2024 |
| Dell          | Inspiron 3721               | Notebook    | [8c75a1af97](https://linux-hardware.org/?probe=8c75a1af97) | Sep 05, 2024 |
| Acidanther... | Mac-63001698E7A34814 iMa... | All in one  | [fd799d8177](https://linux-hardware.org/?probe=fd799d8177) | Sep 04, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [efc36fa140](https://linux-hardware.org/?probe=efc36fa140) | Sep 03, 2024 |
| Dell          | Inspiron 3721               | Notebook    | [8a051dce97](https://linux-hardware.org/?probe=8a051dce97) | Sep 03, 2024 |
| Acer          | TravelMate 5735Z            | Notebook    | [b59bdd3310](https://linux-hardware.org/?probe=b59bdd3310) | Sep 02, 2024 |
| Lenovo        | ThinkCentre Edge71 1607R... | Desktop     | [29cdb0e2f5](https://linux-hardware.org/?probe=29cdb0e2f5) | Sep 02, 2024 |
| Dell          | Latitude 5510               | Notebook    | [634228ff35](https://linux-hardware.org/?probe=634228ff35) | Sep 02, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [41e0375932](https://linux-hardware.org/?probe=41e0375932) | Sep 02, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [c1c6557769](https://linux-hardware.org/?probe=c1c6557769) | Sep 01, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [7a30d49834](https://linux-hardware.org/?probe=7a30d49834) | Sep 01, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [fcfa738334](https://linux-hardware.org/?probe=fcfa738334) | Sep 01, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [8175aeac94](https://linux-hardware.org/?probe=8175aeac94) | Aug 31, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [60e3c48bbc](https://linux-hardware.org/?probe=60e3c48bbc) | Aug 30, 2024 |
| ASUSTek       | TP300LA                     | Notebook    | [55fb687fea](https://linux-hardware.org/?probe=55fb687fea) | Aug 30, 2024 |
| Dell          | Latitude E5420              | Notebook    | [1aa4784afb](https://linux-hardware.org/?probe=1aa4784afb) | Aug 29, 2024 |
| ASUSTek       | 1015PX                      | Notebook    | [b83d98a551](https://linux-hardware.org/?probe=b83d98a551) | Aug 29, 2024 |
| Dell          | XPS 13 9365                 | Convertible | [d28dc2d575](https://linux-hardware.org/?probe=d28dc2d575) | Aug 29, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [9f47f2b01b](https://linux-hardware.org/?probe=9f47f2b01b) | Aug 29, 2024 |
| MSI           | H77MA-G43                   | Desktop     | [73df0e9be3](https://linux-hardware.org/?probe=73df0e9be3) | Aug 28, 2024 |
| MSI           | H77MA-G43                   | Desktop     | [c3687b0959](https://linux-hardware.org/?probe=c3687b0959) | Aug 28, 2024 |
| Gigabyte      | Z790 UD                     | Desktop     | [fd328d5314](https://linux-hardware.org/?probe=fd328d5314) | Aug 28, 2024 |
| Gigabyte      | Z790 UD                     | Desktop     | [01f402c213](https://linux-hardware.org/?probe=01f402c213) | Aug 28, 2024 |
| ASUSTek       | ET2700I                     | Desktop     | [46b00a17dd](https://linux-hardware.org/?probe=46b00a17dd) | Aug 28, 2024 |
| ASUSTek       | ET2700I                     | Desktop     | [69b47ec3cd](https://linux-hardware.org/?probe=69b47ec3cd) | Aug 28, 2024 |
| ASRock        | B450M/ac R2.0               | Desktop     | [0946b4faad](https://linux-hardware.org/?probe=0946b4faad) | Aug 28, 2024 |
| Gigabyte      | G5 GD                       | Notebook    | [2840fa5a43](https://linux-hardware.org/?probe=2840fa5a43) | Aug 27, 2024 |
| HP            | 0B54h D                     | Desktop     | [3e361ce6dd](https://linux-hardware.org/?probe=3e361ce6dd) | Aug 27, 2024 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [2aa427ea2b](https://linux-hardware.org/?probe=2aa427ea2b) | Aug 27, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [a0dc16409e](https://linux-hardware.org/?probe=a0dc16409e) | Aug 26, 2024 |
| Pegatron      | 2A94h                       | Desktop     | [6ec199373b](https://linux-hardware.org/?probe=6ec199373b) | Aug 25, 2024 |
| ASRock        | B450M/ac R2.0               | Desktop     | [0026cbe5e3](https://linux-hardware.org/?probe=0026cbe5e3) | Aug 25, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [5add020da3](https://linux-hardware.org/?probe=5add020da3) | Aug 25, 2024 |
| HP            | 1495                        | Desktop     | [76595d0137](https://linux-hardware.org/?probe=76595d0137) | Aug 24, 2024 |
| HP            | 1495                        | Desktop     | [d7f96fb46e](https://linux-hardware.org/?probe=d7f96fb46e) | Aug 24, 2024 |
| Toshiba       | Satellite C660D             | Notebook    | [fb51658e06](https://linux-hardware.org/?probe=fb51658e06) | Aug 23, 2024 |
| MSI           | GF63 8RC                    | Notebook    | [ea6d76ec59](https://linux-hardware.org/?probe=ea6d76ec59) | Aug 23, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [b366ec9d80](https://linux-hardware.org/?probe=b366ec9d80) | Aug 23, 2024 |
| Dell          | 0PU052                      | Desktop     | [95f1504d6a](https://linux-hardware.org/?probe=95f1504d6a) | Aug 22, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [a8f4d7f114](https://linux-hardware.org/?probe=a8f4d7f114) | Aug 22, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [de194919c2](https://linux-hardware.org/?probe=de194919c2) | Aug 21, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [e9a7ac7834](https://linux-hardware.org/?probe=e9a7ac7834) | Aug 21, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [d0d7bb7dae](https://linux-hardware.org/?probe=d0d7bb7dae) | Aug 20, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [b31f952991](https://linux-hardware.org/?probe=b31f952991) | Aug 19, 2024 |
| Dell          | 0VG93V A00                  | Desktop     | [b81443c816](https://linux-hardware.org/?probe=b81443c816) | Aug 18, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [a377e590da](https://linux-hardware.org/?probe=a377e590da) | Aug 18, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [5040de05ac](https://linux-hardware.org/?probe=5040de05ac) | Aug 18, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [b7eb460f7e](https://linux-hardware.org/?probe=b7eb460f7e) | Aug 17, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [dc84101f95](https://linux-hardware.org/?probe=dc84101f95) | Aug 17, 2024 |
| Dell          | 0VG93V A00                  | Desktop     | [c6be5f6727](https://linux-hardware.org/?probe=c6be5f6727) | Aug 17, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2ffa4f7ffc](https://linux-hardware.org/?probe=2ffa4f7ffc) | Aug 15, 2024 |
| Dell          | G15 5510                    | Notebook    | [bd868cf551](https://linux-hardware.org/?probe=bd868cf551) | Aug 15, 2024 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [9b3874ab72](https://linux-hardware.org/?probe=9b3874ab72) | Aug 13, 2024 |
| Apple         | MacBookAir1,1               | Notebook    | [46b20c4ffe](https://linux-hardware.org/?probe=46b20c4ffe) | Aug 10, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [7d330bfd8a](https://linux-hardware.org/?probe=7d330bfd8a) | Aug 09, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [65290bf0ab](https://linux-hardware.org/?probe=65290bf0ab) | Aug 09, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [48b9938f65](https://linux-hardware.org/?probe=48b9938f65) | Aug 08, 2024 |
| Apple         | MacBookAir4,2               | Notebook    | [463b931271](https://linux-hardware.org/?probe=463b931271) | Aug 08, 2024 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [d3e0797e5b](https://linux-hardware.org/?probe=d3e0797e5b) | Aug 07, 2024 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [2b569bdccd](https://linux-hardware.org/?probe=2b569bdccd) | Aug 07, 2024 |
| HP            | G56                         | Notebook    | [28f40c35e9](https://linux-hardware.org/?probe=28f40c35e9) | Aug 07, 2024 |
| HP            | Compaq 6730b (KE717AV)      | Notebook    | [c6ce1872c3](https://linux-hardware.org/?probe=c6ce1872c3) | Aug 07, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [9359d579a1](https://linux-hardware.org/?probe=9359d579a1) | Aug 07, 2024 |
| GPU Compan... | GWTC116-2                   | Convertible | [ba98e8dc1f](https://linux-hardware.org/?probe=ba98e8dc1f) | Aug 05, 2024 |
| GPU Compan... | GWTC116-2                   | Convertible | [0cc2187ba3](https://linux-hardware.org/?probe=0cc2187ba3) | Aug 05, 2024 |
| Gigabyte      | H81M-S2H                    | Desktop     | [66bcb40057](https://linux-hardware.org/?probe=66bcb40057) | Aug 05, 2024 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [917cec826a](https://linux-hardware.org/?probe=917cec826a) | Aug 04, 2024 |
| Lenovo        | Unknown                     | Notebook    | [f228fbc5ba](https://linux-hardware.org/?probe=f228fbc5ba) | Aug 04, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [bb3e675ece](https://linux-hardware.org/?probe=bb3e675ece) | Aug 04, 2024 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [87d6ed8c38](https://linux-hardware.org/?probe=87d6ed8c38) | Aug 03, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [ffa298e6de](https://linux-hardware.org/?probe=ffa298e6de) | Aug 03, 2024 |
| Lenovo        | B50-80 80EW                 | Notebook    | [39cd7e2e3c](https://linux-hardware.org/?probe=39cd7e2e3c) | Aug 03, 2024 |
| Lenovo        | ThinkPad T480 20L6S0HG00    | Notebook    | [641f0fa927](https://linux-hardware.org/?probe=641f0fa927) | Aug 03, 2024 |
| Gigabyte      | H81M-S2H                    | Desktop     | [dcf87ade71](https://linux-hardware.org/?probe=dcf87ade71) | Aug 03, 2024 |
| ASUSTek       | P5G41-M LX                  | Desktop     | [b3b334d874](https://linux-hardware.org/?probe=b3b334d874) | Aug 01, 2024 |
| Dell          | 0MG3PY A00                  | Desktop     | [558c13f467](https://linux-hardware.org/?probe=558c13f467) | Aug 01, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [1d828595b9](https://linux-hardware.org/?probe=1d828595b9) | Jul 30, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [6332bb4a7c](https://linux-hardware.org/?probe=6332bb4a7c) | Jul 29, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [00af61adcc](https://linux-hardware.org/?probe=00af61adcc) | Jul 29, 2024 |
| Google        | Dratini                     | Notebook    | [8bb5dafec1](https://linux-hardware.org/?probe=8bb5dafec1) | Jul 28, 2024 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [fd419bc9ef](https://linux-hardware.org/?probe=fd419bc9ef) | Jul 27, 2024 |
| Unknown       | Unknown                     | Notebook    | [350031c0ed](https://linux-hardware.org/?probe=350031c0ed) | Jul 27, 2024 |
| Apple         | MacBookAir4,2               | Notebook    | [9d37505b50](https://linux-hardware.org/?probe=9d37505b50) | Jul 26, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [67670a0f4a](https://linux-hardware.org/?probe=67670a0f4a) | Jul 25, 2024 |
| Lenovo        | ThinkPad T490s 20NYS12E0... | Notebook    | [1e7a4734ce](https://linux-hardware.org/?probe=1e7a4734ce) | Jul 25, 2024 |
| AZW           | MINI S                      | Desktop     | [d8754c0201](https://linux-hardware.org/?probe=d8754c0201) | Jul 25, 2024 |
| Gigabyte      | H310M H x.x                 | Desktop     | [c89938fbbb](https://linux-hardware.org/?probe=c89938fbbb) | Jul 25, 2024 |
| ASRock        | B360M-HDV                   | Desktop     | [94cbafc49e](https://linux-hardware.org/?probe=94cbafc49e) | Jul 24, 2024 |
| Lenovo        | ThinkPad T490s 20NYS12E0... | Notebook    | [c80f2e729d](https://linux-hardware.org/?probe=c80f2e729d) | Jul 23, 2024 |
| Lenovo        | B50-80 80EW                 | Notebook    | [1896ed136c](https://linux-hardware.org/?probe=1896ed136c) | Jul 23, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [72c27fa1c1](https://linux-hardware.org/?probe=72c27fa1c1) | Jul 23, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [2c279e3d69](https://linux-hardware.org/?probe=2c279e3d69) | Jul 22, 2024 |
| HP            | ENVY 17                     | Notebook    | [8d586d3909](https://linux-hardware.org/?probe=8d586d3909) | Jul 22, 2024 |
| HP            | ENVY 17                     | Notebook    | [f97fdd96f8](https://linux-hardware.org/?probe=f97fdd96f8) | Jul 22, 2024 |
| HP            | Pavilion 17                 | Notebook    | [ea65b65978](https://linux-hardware.org/?probe=ea65b65978) | Jul 22, 2024 |
| Sony          | VPCEB2H4E                   | Notebook    | [144fb934d0](https://linux-hardware.org/?probe=144fb934d0) | Jul 22, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [298b035882](https://linux-hardware.org/?probe=298b035882) | Jul 22, 2024 |
| Apple         | Mac-F2238AC8                | All in one  | [90a03b6f59](https://linux-hardware.org/?probe=90a03b6f59) | Jul 21, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [2bac99deff](https://linux-hardware.org/?probe=2bac99deff) | Jul 21, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [2baabb5540](https://linux-hardware.org/?probe=2baabb5540) | Jul 20, 2024 |
| Medion        | E2293 MD61120               | Convertible | [5894704b59](https://linux-hardware.org/?probe=5894704b59) | Jul 20, 2024 |
| HP            | 250 G5 Notebook PC          | Notebook    | [687e56399a](https://linux-hardware.org/?probe=687e56399a) | Jul 20, 2024 |
| Lenovo        | ThinkPad E480 20KN009QGE    | Notebook    | [96b86c74c8](https://linux-hardware.org/?probe=96b86c74c8) | Jul 19, 2024 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [8f90dcefce](https://linux-hardware.org/?probe=8f90dcefce) | Jul 19, 2024 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [7c793c4a04](https://linux-hardware.org/?probe=7c793c4a04) | Jul 18, 2024 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [64685a555f](https://linux-hardware.org/?probe=64685a555f) | Jul 18, 2024 |
| Dell          | Inspiron 3580               | Notebook    | [8ef4654d8c](https://linux-hardware.org/?probe=8ef4654d8c) | Jul 18, 2024 |
| HP            | 8245 001                    | All in one  | [66ad5acbdd](https://linux-hardware.org/?probe=66ad5acbdd) | Jul 17, 2024 |
| AMI           | Intel                       | Desktop     | [461763ad20](https://linux-hardware.org/?probe=461763ad20) | Jul 17, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [dccbf42cb3](https://linux-hardware.org/?probe=dccbf42cb3) | Jul 16, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [4f3c1e544b](https://linux-hardware.org/?probe=4f3c1e544b) | Jul 15, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [e673ae4869](https://linux-hardware.org/?probe=e673ae4869) | Jul 14, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [20850127a9](https://linux-hardware.org/?probe=20850127a9) | Jul 14, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [4da9ebe6b5](https://linux-hardware.org/?probe=4da9ebe6b5) | Jul 13, 2024 |
| Dell          | Inspiron 3580               | Notebook    | [7a2073b0b4](https://linux-hardware.org/?probe=7a2073b0b4) | Jul 13, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [54ed747270](https://linux-hardware.org/?probe=54ed747270) | Jul 13, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [a675a84975](https://linux-hardware.org/?probe=a675a84975) | Jul 12, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [d7d8b022c8](https://linux-hardware.org/?probe=d7d8b022c8) | Jul 12, 2024 |
| HP            | G42                         | Notebook    | [1ab8c40d0d](https://linux-hardware.org/?probe=1ab8c40d0d) | Jul 11, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [0f57d516a6](https://linux-hardware.org/?probe=0f57d516a6) | Jul 10, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [d2fc5858f7](https://linux-hardware.org/?probe=d2fc5858f7) | Jul 10, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [5e25885998](https://linux-hardware.org/?probe=5e25885998) | Jul 09, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [be9af5afe2](https://linux-hardware.org/?probe=be9af5afe2) | Jul 08, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | Notebook    | [fdb5740619](https://linux-hardware.org/?probe=fdb5740619) | Jul 08, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | Notebook    | [344a3a1381](https://linux-hardware.org/?probe=344a3a1381) | Jul 08, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | Notebook    | [389c663679](https://linux-hardware.org/?probe=389c663679) | Jul 08, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | Notebook    | [72dc55770d](https://linux-hardware.org/?probe=72dc55770d) | Jul 08, 2024 |
| Dell          | 0K240Y A03                  | Desktop     | [fd2e6133c8](https://linux-hardware.org/?probe=fd2e6133c8) | Jul 07, 2024 |
| Dell          | 0K240Y A03                  | Desktop     | [7409d9aee8](https://linux-hardware.org/?probe=7409d9aee8) | Jul 07, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [7f3622744d](https://linux-hardware.org/?probe=7f3622744d) | Jul 07, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [bb167dd1e3](https://linux-hardware.org/?probe=bb167dd1e3) | Jul 07, 2024 |
| Dell          | 0K240Y A03                  | Desktop     | [25538a3377](https://linux-hardware.org/?probe=25538a3377) | Jul 06, 2024 |
| Compaq        | Presario CQ-17              | Notebook    | [ac298b1a45](https://linux-hardware.org/?probe=ac298b1a45) | Jul 04, 2024 |
| Dell          | Precision 7720              | Notebook    | [26f2413f41](https://linux-hardware.org/?probe=26f2413f41) | Jul 04, 2024 |
| Lenovo        | Y520-15IKBA 80WY            | Notebook    | [e3fc209866](https://linux-hardware.org/?probe=e3fc209866) | Jul 03, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [22f634f998](https://linux-hardware.org/?probe=22f634f998) | Jul 02, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [605b774f63](https://linux-hardware.org/?probe=605b774f63) | Jul 02, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [e09d0fb605](https://linux-hardware.org/?probe=e09d0fb605) | Jul 01, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [f91526c63f](https://linux-hardware.org/?probe=f91526c63f) | Jul 01, 2024 |
| Lenovo        | 3309 SDK0T76530 WIN 3556... | Mini pc     | [dcef7100e1](https://linux-hardware.org/?probe=dcef7100e1) | Jul 01, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [ef55e011c4](https://linux-hardware.org/?probe=ef55e011c4) | Jun 28, 2024 |
| HP            | 0B54h D                     | Desktop     | [a1df6af082](https://linux-hardware.org/?probe=a1df6af082) | Jun 27, 2024 |
| HP            | Pavilion dv6                | Notebook    | [25259c90d4](https://linux-hardware.org/?probe=25259c90d4) | Jun 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [bed62e6b3c](https://linux-hardware.org/?probe=bed62e6b3c) | Jun 26, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [c8bce44bed](https://linux-hardware.org/?probe=c8bce44bed) | Jun 26, 2024 |
| Samsung       | 305V4A/305V5A               | Notebook    | [e4f376bd36](https://linux-hardware.org/?probe=e4f376bd36) | Jun 26, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [85c379a6a8](https://linux-hardware.org/?probe=85c379a6a8) | Jun 25, 2024 |
| Dell          | Latitude E4310              | Notebook    | [c2303e5967](https://linux-hardware.org/?probe=c2303e5967) | Jun 25, 2024 |
| Dell          | Latitude E4310              | Notebook    | [f985372e98](https://linux-hardware.org/?probe=f985372e98) | Jun 25, 2024 |
| MSI           | B365M PRO-VDH               | Desktop     | [bf340a8641](https://linux-hardware.org/?probe=bf340a8641) | Jun 25, 2024 |
| HP            | Pavilion dv2000 (GM691LA... | Notebook    | [de1b028bbb](https://linux-hardware.org/?probe=de1b028bbb) | Jun 24, 2024 |
| ASUSTek       | K42F                        | Notebook    | [384052ea34](https://linux-hardware.org/?probe=384052ea34) | Jun 24, 2024 |
| ASUSTek       | K42F                        | Notebook    | [7978cdf8b4](https://linux-hardware.org/?probe=7978cdf8b4) | Jun 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6e291c60fd](https://linux-hardware.org/?probe=6e291c60fd) | Jun 22, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [14565c27bf](https://linux-hardware.org/?probe=14565c27bf) | Jun 22, 2024 |
| Lenovo        | ThinkPad T530 2392CTO       | Notebook    | [e7921f65ce](https://linux-hardware.org/?probe=e7921f65ce) | Jun 20, 2024 |
| Dell          | Latitude E7440              | Notebook    | [5fc427cc24](https://linux-hardware.org/?probe=5fc427cc24) | Jun 20, 2024 |
| Dell          | Inspiron N4010              | Notebook    | [dad60b8122](https://linux-hardware.org/?probe=dad60b8122) | Jun 20, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [59ab2f562b](https://linux-hardware.org/?probe=59ab2f562b) | Jun 19, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [c2e291249c](https://linux-hardware.org/?probe=c2e291249c) | Jun 19, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [e381ac4c82](https://linux-hardware.org/?probe=e381ac4c82) | Jun 19, 2024 |
| ECS           | H110M-C3D/C3V               | Desktop     | [0029341c8c](https://linux-hardware.org/?probe=0029341c8c) | Jun 18, 2024 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | Notebook    | [f476dc9a4c](https://linux-hardware.org/?probe=f476dc9a4c) | Jun 18, 2024 |
| Dell          | System XPS L502X            | Notebook    | [58023857ae](https://linux-hardware.org/?probe=58023857ae) | Jun 17, 2024 |
| MSI           | MS-7267                     | Desktop     | [59fc27aa13](https://linux-hardware.org/?probe=59fc27aa13) | Jun 17, 2024 |
| MSI           | MS-7267                     | Desktop     | [02fc0d7625](https://linux-hardware.org/?probe=02fc0d7625) | Jun 17, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f5a682fbe7](https://linux-hardware.org/?probe=f5a682fbe7) | Jun 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [14aecfba4d](https://linux-hardware.org/?probe=14aecfba4d) | Jun 16, 2024 |
| Dell          | Latitude 5424 Rugged        | Notebook    | [8ce01f0186](https://linux-hardware.org/?probe=8ce01f0186) | Jun 16, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [8d51939a60](https://linux-hardware.org/?probe=8d51939a60) | Jun 16, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [8eac8a90fb](https://linux-hardware.org/?probe=8eac8a90fb) | Jun 15, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [36b06bd4db](https://linux-hardware.org/?probe=36b06bd4db) | Jun 15, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e2f4b2305a](https://linux-hardware.org/?probe=e2f4b2305a) | Jun 15, 2024 |
| ASUSTek       | G750JS                      | Notebook    | [1be0b00e6a](https://linux-hardware.org/?probe=1be0b00e6a) | Jun 15, 2024 |
| Dell          | Latitude 5424 Rugged        | Notebook    | [2286699120](https://linux-hardware.org/?probe=2286699120) | Jun 14, 2024 |
| Chuwi         | UBook XPro                  | Notebook    | [1a9ca58ced](https://linux-hardware.org/?probe=1a9ca58ced) | Jun 13, 2024 |
| ASUSTek       | K501UX                      | Notebook    | [ccf68ea2d8](https://linux-hardware.org/?probe=ccf68ea2d8) | Jun 13, 2024 |
| Myway         | U1306i                      | Notebook    | [a029a374de](https://linux-hardware.org/?probe=a029a374de) | Jun 12, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [ef3581ab2b](https://linux-hardware.org/?probe=ef3581ab2b) | Jun 12, 2024 |
| Google        | Nospike                     | Notebook    | [da6fe22637](https://linux-hardware.org/?probe=da6fe22637) | Jun 12, 2024 |
| Google        | Nospike                     | Notebook    | [86096b4ac8](https://linux-hardware.org/?probe=86096b4ac8) | Jun 11, 2024 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [b1067e137b](https://linux-hardware.org/?probe=b1067e137b) | Jun 11, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [cbccdbbf42](https://linux-hardware.org/?probe=cbccdbbf42) | Jun 10, 2024 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [af3d2280af](https://linux-hardware.org/?probe=af3d2280af) | Jun 10, 2024 |
| HP            | Compaq Presario CQ61        | Notebook    | [ab0cc4ab6b](https://linux-hardware.org/?probe=ab0cc4ab6b) | Jun 09, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [f30cff4982](https://linux-hardware.org/?probe=f30cff4982) | Jun 09, 2024 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [2bde6824fc](https://linux-hardware.org/?probe=2bde6824fc) | Jun 09, 2024 |
| ASUSTek       | X45U                        | Notebook    | [21e364e5a7](https://linux-hardware.org/?probe=21e364e5a7) | Jun 07, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [6cc3abff8f](https://linux-hardware.org/?probe=6cc3abff8f) | Jun 06, 2024 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [2f2a24345a](https://linux-hardware.org/?probe=2f2a24345a) | Jun 05, 2024 |
| ASUSTek       | PRIME H510M-K R2.0          | Desktop     | [a15ecb15f8](https://linux-hardware.org/?probe=a15ecb15f8) | Jun 05, 2024 |
| Dell          | Latitude E6440              | Notebook    | [74814a37e4](https://linux-hardware.org/?probe=74814a37e4) | Jun 05, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [d20ab5f5be](https://linux-hardware.org/?probe=d20ab5f5be) | Jun 03, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [14d13ac22c](https://linux-hardware.org/?probe=14d13ac22c) | Jun 03, 2024 |
| Lenovo        | V580c 20160                 | Notebook    | [7895c2caac](https://linux-hardware.org/?probe=7895c2caac) | Jun 03, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [93f930012f](https://linux-hardware.org/?probe=93f930012f) | Jun 02, 2024 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [a627db0998](https://linux-hardware.org/?probe=a627db0998) | Jun 02, 2024 |
| Unknown       | V00                         | Mini pc     | [bf8529b43c](https://linux-hardware.org/?probe=bf8529b43c) | May 31, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [11cbeead14](https://linux-hardware.org/?probe=11cbeead14) | May 31, 2024 |
| Dell          | Latitude E6320              | Notebook    | [356970f66c](https://linux-hardware.org/?probe=356970f66c) | May 30, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [0e706f4bcd](https://linux-hardware.org/?probe=0e706f4bcd) | May 30, 2024 |
| Microsoft     | Surface Laptop              | Tablet      | [48281eaad7](https://linux-hardware.org/?probe=48281eaad7) | May 29, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [b545c96334](https://linux-hardware.org/?probe=b545c96334) | May 28, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [493e19c3c5](https://linux-hardware.org/?probe=493e19c3c5) | May 27, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [ed07af0db2](https://linux-hardware.org/?probe=ed07af0db2) | May 27, 2024 |
| Dell          | Latitude E4310              | Notebook    | [28638e3182](https://linux-hardware.org/?probe=28638e3182) | May 27, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [640586659d](https://linux-hardware.org/?probe=640586659d) | May 24, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [174405df46](https://linux-hardware.org/?probe=174405df46) | May 24, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [2919242003](https://linux-hardware.org/?probe=2919242003) | May 23, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [5a3bf3b0e5](https://linux-hardware.org/?probe=5a3bf3b0e5) | May 23, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [67d2c0a830](https://linux-hardware.org/?probe=67d2c0a830) | May 23, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [8789f1352d](https://linux-hardware.org/?probe=8789f1352d) | May 23, 2024 |
| Gigabyte      | GA-6PXSVT 01234567          | Server      | [0c8c032d4a](https://linux-hardware.org/?probe=0c8c032d4a) | May 22, 2024 |
| Gigabyte      | GA-6PXSVT 01234567          | Server      | [437fb8cb40](https://linux-hardware.org/?probe=437fb8cb40) | May 21, 2024 |
| Dell          | Inspiron 3442               | Notebook    | [3fa98588d7](https://linux-hardware.org/?probe=3fa98588d7) | May 20, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e010a46aaa](https://linux-hardware.org/?probe=e010a46aaa) | May 20, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [81ca91875c](https://linux-hardware.org/?probe=81ca91875c) | May 19, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [9af9e45749](https://linux-hardware.org/?probe=9af9e45749) | May 19, 2024 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [ef53a24225](https://linux-hardware.org/?probe=ef53a24225) | May 19, 2024 |
| Lenovo        | U41-70 80JV                 | Notebook    | [5570ce9cbf](https://linux-hardware.org/?probe=5570ce9cbf) | May 18, 2024 |
| Gigabyte      | H310M H x.x                 | Desktop     | [6c986e95fa](https://linux-hardware.org/?probe=6c986e95fa) | May 17, 2024 |
| Lenovo        | ThinkCentre A58 761179G     | Desktop     | [0f92c56231](https://linux-hardware.org/?probe=0f92c56231) | May 17, 2024 |
| HP            | Compaq 6730b (KE717AV)      | Notebook    | [3832c9ecea](https://linux-hardware.org/?probe=3832c9ecea) | May 14, 2024 |
| Dell          | 08VX12 A00                  | Desktop     | [da62c2beb8](https://linux-hardware.org/?probe=da62c2beb8) | May 14, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2b749bf5c4](https://linux-hardware.org/?probe=2b749bf5c4) | May 14, 2024 |
| HP            | Pavilion 17                 | Notebook    | [1a80d822d4](https://linux-hardware.org/?probe=1a80d822d4) | May 14, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [2fadb82e07](https://linux-hardware.org/?probe=2fadb82e07) | May 14, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7982277925](https://linux-hardware.org/?probe=7982277925) | May 13, 2024 |
| HP            | Pavilion g4                 | Notebook    | [e4d725eba3](https://linux-hardware.org/?probe=e4d725eba3) | May 11, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5b949515c2](https://linux-hardware.org/?probe=5b949515c2) | May 11, 2024 |
| Dell          | Latitude E6320              | Notebook    | [3d34ee9056](https://linux-hardware.org/?probe=3d34ee9056) | May 10, 2024 |
| Dell          | Inspiron 3481               | Notebook    | [78cf24846f](https://linux-hardware.org/?probe=78cf24846f) | May 09, 2024 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [fea6956058](https://linux-hardware.org/?probe=fea6956058) | May 08, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e475e36ab0](https://linux-hardware.org/?probe=e475e36ab0) | May 06, 2024 |
| Packard Be... | EasyNote LM81               | Notebook    | [0ea4d18648](https://linux-hardware.org/?probe=0ea4d18648) | May 06, 2024 |
| Samsung       | 550XDA                      | Notebook    | [1ea7dfb8ae](https://linux-hardware.org/?probe=1ea7dfb8ae) | May 06, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0f43840d58](https://linux-hardware.org/?probe=0f43840d58) | May 06, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [3c0f7c8c00](https://linux-hardware.org/?probe=3c0f7c8c00) | May 06, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [7ad59bc402](https://linux-hardware.org/?probe=7ad59bc402) | May 05, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [a88155be11](https://linux-hardware.org/?probe=a88155be11) | May 05, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [80f71c25c1](https://linux-hardware.org/?probe=80f71c25c1) | May 05, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [2e67b6ba22](https://linux-hardware.org/?probe=2e67b6ba22) | May 04, 2024 |
| Samsung       | DP700A7D-S04IT SEC_SW_RE... | All in one  | [7ddb4bb85e](https://linux-hardware.org/?probe=7ddb4bb85e) | May 04, 2024 |
| Lenovo        | ThinkPad T530 2429HR5       | Notebook    | [c5640e6fae](https://linux-hardware.org/?probe=c5640e6fae) | May 04, 2024 |
| Dell          | Latitude 5490               | Notebook    | [b31473028c](https://linux-hardware.org/?probe=b31473028c) | May 04, 2024 |
| Packard Be... | EasyNote LM81               | Notebook    | [44ead9f439](https://linux-hardware.org/?probe=44ead9f439) | May 03, 2024 |
| Google        | Nospike                     | Notebook    | [549d690ae1](https://linux-hardware.org/?probe=549d690ae1) | May 02, 2024 |
| Samsung       | DP700A7D-S04IT SEC_SW_RE... | All in one  | [3ba7fa0ef2](https://linux-hardware.org/?probe=3ba7fa0ef2) | May 01, 2024 |
| Dell          | Latitude 5490               | Notebook    | [c83e9f5562](https://linux-hardware.org/?probe=c83e9f5562) | May 01, 2024 |
| Lenovo        | IdeaPad P400 Touch 20211    | Notebook    | [cacd80cba3](https://linux-hardware.org/?probe=cacd80cba3) | May 01, 2024 |
| HP            | ProBook 470 G5              | Notebook    | [8ba873e85d](https://linux-hardware.org/?probe=8ba873e85d) | Apr 30, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [29d73efd4a](https://linux-hardware.org/?probe=29d73efd4a) | Apr 30, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [022ece0282](https://linux-hardware.org/?probe=022ece0282) | Apr 30, 2024 |
| MSI           | GT62VR 6RE                  | Notebook    | [b7768b7ee9](https://linux-hardware.org/?probe=b7768b7ee9) | Apr 28, 2024 |
| Medion        | MS-7797                     | Desktop     | [a72c95890e](https://linux-hardware.org/?probe=a72c95890e) | Apr 28, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [0dbed15c85](https://linux-hardware.org/?probe=0dbed15c85) | Apr 27, 2024 |
| Gigabyte      | B250M-D2VX-SI-CF            | Desktop     | [5c277491cf](https://linux-hardware.org/?probe=5c277491cf) | Apr 27, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [0ce65136da](https://linux-hardware.org/?probe=0ce65136da) | Apr 27, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [803b388305](https://linux-hardware.org/?probe=803b388305) | Apr 26, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3471ca7905](https://linux-hardware.org/?probe=3471ca7905) | Apr 26, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [8da3b01d13](https://linux-hardware.org/?probe=8da3b01d13) | Apr 26, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [6609c77480](https://linux-hardware.org/?probe=6609c77480) | Apr 26, 2024 |
| MSI           | MS-B090                     | All in one  | [06780aaa5b](https://linux-hardware.org/?probe=06780aaa5b) | Apr 26, 2024 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [ee55351883](https://linux-hardware.org/?probe=ee55351883) | Apr 25, 2024 |
| HP            | EliteBook 745 G4            | Notebook    | [f38a6451f0](https://linux-hardware.org/?probe=f38a6451f0) | Apr 24, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [c12789125b](https://linux-hardware.org/?probe=c12789125b) | Apr 24, 2024 |
| HP            | Pavilion dv6                | Notebook    | [c8d73c3a23](https://linux-hardware.org/?probe=c8d73c3a23) | Apr 24, 2024 |
| HP            | Pavilion dv6                | Notebook    | [08f01fc7ed](https://linux-hardware.org/?probe=08f01fc7ed) | Apr 24, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [ff74a6262e](https://linux-hardware.org/?probe=ff74a6262e) | Apr 23, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [674850b624](https://linux-hardware.org/?probe=674850b624) | Apr 23, 2024 |
| Unknown       | Unknown                     | Notebook    | [def20611a4](https://linux-hardware.org/?probe=def20611a4) | Apr 23, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [c7cbc009ef](https://linux-hardware.org/?probe=c7cbc009ef) | Apr 23, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [39ed7553a3](https://linux-hardware.org/?probe=39ed7553a3) | Apr 23, 2024 |
| TECNO         | MEGABOOK T1                 | Notebook    | [01fc56cf5b](https://linux-hardware.org/?probe=01fc56cf5b) | Apr 22, 2024 |
| Medion        | MS-7797                     | Desktop     | [810a7d7810](https://linux-hardware.org/?probe=810a7d7810) | Apr 22, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [3f4e9ae066](https://linux-hardware.org/?probe=3f4e9ae066) | Apr 21, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [e70b7338c2](https://linux-hardware.org/?probe=e70b7338c2) | Apr 21, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [9e2621b213](https://linux-hardware.org/?probe=9e2621b213) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [8740fd113c](https://linux-hardware.org/?probe=8740fd113c) | Apr 19, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [8b925ca8f0](https://linux-hardware.org/?probe=8b925ca8f0) | Apr 19, 2024 |
| ECS           | H110M-C3D/C3V               | Desktop     | [7fffccead5](https://linux-hardware.org/?probe=7fffccead5) | Apr 17, 2024 |
| ASUSTek       | K42F                        | Notebook    | [d127923f98](https://linux-hardware.org/?probe=d127923f98) | Apr 17, 2024 |
| HP            | Pavilion x2 Detachable      | Notebook    | [9e5556a266](https://linux-hardware.org/?probe=9e5556a266) | Apr 17, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [847e24305d](https://linux-hardware.org/?probe=847e24305d) | Apr 16, 2024 |
| Apple         | MacBookPro16,1              | Notebook    | [40fd2c63cb](https://linux-hardware.org/?probe=40fd2c63cb) | Apr 16, 2024 |
| Dell          | 0D24M8 A02                  | Desktop     | [96b0ae2f86](https://linux-hardware.org/?probe=96b0ae2f86) | Apr 16, 2024 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [32237e05f1](https://linux-hardware.org/?probe=32237e05f1) | Apr 15, 2024 |
| DEPO Compu... | W25CEW                      | Notebook    | [6653a2975d](https://linux-hardware.org/?probe=6653a2975d) | Apr 15, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0018ad80c4](https://linux-hardware.org/?probe=0018ad80c4) | Apr 14, 2024 |
| Apple         | MacBookAir7,1               | Notebook    | [c1be5d2dd6](https://linux-hardware.org/?probe=c1be5d2dd6) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5a62c14a1f](https://linux-hardware.org/?probe=5a62c14a1f) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [97f0209510](https://linux-hardware.org/?probe=97f0209510) | Apr 14, 2024 |
| Medion        | Z370H4-EM                   | Desktop     | [39cb6c0afb](https://linux-hardware.org/?probe=39cb6c0afb) | Apr 13, 2024 |
| Acer          | Aspire 6935                 | Notebook    | [d26ee0494f](https://linux-hardware.org/?probe=d26ee0494f) | Apr 13, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [e57c02860c](https://linux-hardware.org/?probe=e57c02860c) | Apr 13, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [f64263bd19](https://linux-hardware.org/?probe=f64263bd19) | Apr 12, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [569f9614a5](https://linux-hardware.org/?probe=569f9614a5) | Apr 12, 2024 |
| HP            | ProBook 6360b               | Notebook    | [81b9d0706b](https://linux-hardware.org/?probe=81b9d0706b) | Apr 11, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [461d5dfd8d](https://linux-hardware.org/?probe=461d5dfd8d) | Apr 11, 2024 |
| MSI           | MEG Z590 UNIFY              | Desktop     | [88f634c670](https://linux-hardware.org/?probe=88f634c670) | Apr 11, 2024 |
| MSI           | MEG Z590 UNIFY              | Desktop     | [2336b3cd38](https://linux-hardware.org/?probe=2336b3cd38) | Apr 11, 2024 |
| HP            | 2B13 A01                    | All in one  | [30160f86ab](https://linux-hardware.org/?probe=30160f86ab) | Apr 10, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | Notebook    | [35b206d8f8](https://linux-hardware.org/?probe=35b206d8f8) | Apr 10, 2024 |
| HP            | EliteBook 745 G4            | Notebook    | [0d92302707](https://linux-hardware.org/?probe=0d92302707) | Apr 09, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [ac137b7cb7](https://linux-hardware.org/?probe=ac137b7cb7) | Apr 09, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [e964beb301](https://linux-hardware.org/?probe=e964beb301) | Apr 09, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [3ab1d66e10](https://linux-hardware.org/?probe=3ab1d66e10) | Apr 08, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [9099f440bc](https://linux-hardware.org/?probe=9099f440bc) | Apr 08, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [7efef6a0ae](https://linux-hardware.org/?probe=7efef6a0ae) | Apr 07, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [d28398beb7](https://linux-hardware.org/?probe=d28398beb7) | Apr 07, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [ccdb5dcad9](https://linux-hardware.org/?probe=ccdb5dcad9) | Apr 07, 2024 |
| HP            | 18E7                        | Desktop     | [467ac72efe](https://linux-hardware.org/?probe=467ac72efe) | Apr 07, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [a90b694613](https://linux-hardware.org/?probe=a90b694613) | Apr 06, 2024 |
| Gigabyte      | 945GME-DS2                  | Desktop     | [37085a5c3f](https://linux-hardware.org/?probe=37085a5c3f) | Apr 06, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [27d64e5b3c](https://linux-hardware.org/?probe=27d64e5b3c) | Apr 05, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [733d6c6e2b](https://linux-hardware.org/?probe=733d6c6e2b) | Apr 05, 2024 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8603f205ba](https://linux-hardware.org/?probe=8603f205ba) | Apr 05, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | Notebook    | [3d64dfc3a9](https://linux-hardware.org/?probe=3d64dfc3a9) | Apr 04, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [e2cef27ef8](https://linux-hardware.org/?probe=e2cef27ef8) | Apr 03, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9bc584b914](https://linux-hardware.org/?probe=9bc584b914) | Apr 03, 2024 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [eaa5927086](https://linux-hardware.org/?probe=eaa5927086) | Apr 03, 2024 |
| HP            | 18E7                        | Desktop     | [9dadc64d70](https://linux-hardware.org/?probe=9dadc64d70) | Apr 03, 2024 |
| HP            | Pavilion dv7                | Notebook    | [483e1957a4](https://linux-hardware.org/?probe=483e1957a4) | Apr 02, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [fe5490324f](https://linux-hardware.org/?probe=fe5490324f) | Apr 01, 2024 |
| ASUSTek       | EX-B150M-V3                 | Desktop     | [0c643b047e](https://linux-hardware.org/?probe=0c643b047e) | Apr 01, 2024 |
| ASUSTek       | EX-B150M-V3                 | Desktop     | [c6772f244f](https://linux-hardware.org/?probe=c6772f244f) | Apr 01, 2024 |
| Medion        | E6217                       | Notebook    | [c2ca377a05](https://linux-hardware.org/?probe=c2ca377a05) | Mar 31, 2024 |
| HP            | Pavilion dv7                | Notebook    | [a86e8cccf5](https://linux-hardware.org/?probe=a86e8cccf5) | Mar 31, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6cec34e881](https://linux-hardware.org/?probe=6cec34e881) | Mar 30, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c010c5876b](https://linux-hardware.org/?probe=c010c5876b) | Mar 30, 2024 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [f30dd46998](https://linux-hardware.org/?probe=f30dd46998) | Mar 29, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b68181d354](https://linux-hardware.org/?probe=b68181d354) | Mar 29, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [5b4456a2d6](https://linux-hardware.org/?probe=5b4456a2d6) | Mar 29, 2024 |
| Dell          | Inspiron 5423               | Notebook    | [0c6c4c6a58](https://linux-hardware.org/?probe=0c6c4c6a58) | Mar 29, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [a87aa51bf9](https://linux-hardware.org/?probe=a87aa51bf9) | Mar 29, 2024 |
| MSI           | A68HM-E33 V2                | Desktop     | [22b44252e3](https://linux-hardware.org/?probe=22b44252e3) | Mar 28, 2024 |
| Lenovo        | ThinkPad W500 40623CG       | Notebook    | [71c868292f](https://linux-hardware.org/?probe=71c868292f) | Mar 27, 2024 |
| Lenovo        | ThinkPad W500 40623CG       | Notebook    | [01d1ef9c31](https://linux-hardware.org/?probe=01d1ef9c31) | Mar 26, 2024 |
| Lenovo        | ThinkPad T410 2537CQ7       | Notebook    | [8b91ec68dd](https://linux-hardware.org/?probe=8b91ec68dd) | Mar 26, 2024 |
| Lenovo        | ThinkPad T450s 20BX0011G... | Notebook    | [3e86099c28](https://linux-hardware.org/?probe=3e86099c28) | Mar 26, 2024 |
| Lenovo        | ThinkCentre Edge91 1895B... | Desktop     | [991944129e](https://linux-hardware.org/?probe=991944129e) | Mar 26, 2024 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [e9afd87037](https://linux-hardware.org/?probe=e9afd87037) | Mar 25, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [30717fbd15](https://linux-hardware.org/?probe=30717fbd15) | Mar 25, 2024 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [42ab03e71f](https://linux-hardware.org/?probe=42ab03e71f) | Mar 25, 2024 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [9a817cbe67](https://linux-hardware.org/?probe=9a817cbe67) | Mar 24, 2024 |
| Lenovo        | ThinkPad T450s 20BX0011G... | Notebook    | [598015ca49](https://linux-hardware.org/?probe=598015ca49) | Mar 24, 2024 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [92aa3b7c70](https://linux-hardware.org/?probe=92aa3b7c70) | Mar 24, 2024 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [57ee067ff2](https://linux-hardware.org/?probe=57ee067ff2) | Mar 24, 2024 |
| Samsung       | 535U3C                      | Notebook    | [6b29450ac6](https://linux-hardware.org/?probe=6b29450ac6) | Mar 23, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [20d2290d1c](https://linux-hardware.org/?probe=20d2290d1c) | Mar 23, 2024 |
| HP            | 0B54h D                     | Desktop     | [7b38927e17](https://linux-hardware.org/?probe=7b38927e17) | Mar 23, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e5c5d49216](https://linux-hardware.org/?probe=e5c5d49216) | Mar 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [5af36d3a4e](https://linux-hardware.org/?probe=5af36d3a4e) | Mar 22, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [89e6d122a0](https://linux-hardware.org/?probe=89e6d122a0) | Mar 22, 2024 |
| HP            | 0B54h D                     | Desktop     | [0af537dbcd](https://linux-hardware.org/?probe=0af537dbcd) | Mar 22, 2024 |
| ASRock        | X570 Extreme4               | Desktop     | [f7bd9e9cce](https://linux-hardware.org/?probe=f7bd9e9cce) | Mar 21, 2024 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [4769499461](https://linux-hardware.org/?probe=4769499461) | Mar 21, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [a32e851ddd](https://linux-hardware.org/?probe=a32e851ddd) | Mar 21, 2024 |
| Unknown       | AM02                        | Mini pc     | [ad3f00a84a](https://linux-hardware.org/?probe=ad3f00a84a) | Mar 20, 2024 |
| HP            | ENVY 17                     | Notebook    | [0ee4da384d](https://linux-hardware.org/?probe=0ee4da384d) | Mar 20, 2024 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [78bd592741](https://linux-hardware.org/?probe=78bd592741) | Mar 17, 2024 |
| MSI           | GE70 2QE                    | Notebook    | [31b45c6de7](https://linux-hardware.org/?probe=31b45c6de7) | Mar 17, 2024 |
| HP            | Laptop 17-by3xxx            | Notebook    | [430290e97d](https://linux-hardware.org/?probe=430290e97d) | Mar 17, 2024 |
| Dell          | Latitude E6420              | Notebook    | [dc953135d3](https://linux-hardware.org/?probe=dc953135d3) | Mar 16, 2024 |
| Dell          | Latitude E7240              | Notebook    | [d159f296d4](https://linux-hardware.org/?probe=d159f296d4) | Mar 16, 2024 |
| ASUSTek       | X541UAK                     | Notebook    | [4b33512569](https://linux-hardware.org/?probe=4b33512569) | Mar 16, 2024 |
| Apple         | Mac-F2268CC8                | All in one  | [d90e75a37d](https://linux-hardware.org/?probe=d90e75a37d) | Mar 15, 2024 |
| Dell          | Latitude E7470              | Notebook    | [4addfb5619](https://linux-hardware.org/?probe=4addfb5619) | Mar 14, 2024 |
| Dell          | Latitude E7470              | Notebook    | [fbf1fe3963](https://linux-hardware.org/?probe=fbf1fe3963) | Mar 14, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [36653be57c](https://linux-hardware.org/?probe=36653be57c) | Mar 13, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [8b2310099c](https://linux-hardware.org/?probe=8b2310099c) | Mar 13, 2024 |
| MSI           | A68HM-E33 V2                | Desktop     | [52b29bf885](https://linux-hardware.org/?probe=52b29bf885) | Mar 12, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [cfb2591a20](https://linux-hardware.org/?probe=cfb2591a20) | Mar 12, 2024 |
| ASRock        | H110M-HDS                   | Desktop     | [0b9ca9c2ca](https://linux-hardware.org/?probe=0b9ca9c2ca) | Mar 12, 2024 |
| ASRock        | H110M-HDS                   | Desktop     | [0d754901a3](https://linux-hardware.org/?probe=0d754901a3) | Mar 12, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [9160e106f1](https://linux-hardware.org/?probe=9160e106f1) | Mar 12, 2024 |
| Dell          | 0D24M8 A02                  | Desktop     | [70a8364913](https://linux-hardware.org/?probe=70a8364913) | Mar 11, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [89b268f1f8](https://linux-hardware.org/?probe=89b268f1f8) | Mar 11, 2024 |
| HP            | EliteBook x360 1030 G7 N... | Convertible | [0f0640b2bf](https://linux-hardware.org/?probe=0f0640b2bf) | Mar 10, 2024 |
| Dell          | 0M6C7G A00                  | Desktop     | [666c6ad495](https://linux-hardware.org/?probe=666c6ad495) | Mar 10, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [22f1633f40](https://linux-hardware.org/?probe=22f1633f40) | Mar 09, 2024 |
| ASUSTek       | X541UAK                     | Notebook    | [8b527dc9c9](https://linux-hardware.org/?probe=8b527dc9c9) | Mar 09, 2024 |
| HP            | ENVY Notebook               | Notebook    | [6ab7868737](https://linux-hardware.org/?probe=6ab7868737) | Mar 08, 2024 |
| Biostar       | B350GT5                     | Desktop     | [61f8cce525](https://linux-hardware.org/?probe=61f8cce525) | Mar 08, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [486387c7ef](https://linux-hardware.org/?probe=486387c7ef) | Mar 08, 2024 |
| Unknown       | AM02                        | Mini pc     | [3a7ef0d16c](https://linux-hardware.org/?probe=3a7ef0d16c) | Mar 08, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [16b3359307](https://linux-hardware.org/?probe=16b3359307) | Mar 07, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4d569e557d](https://linux-hardware.org/?probe=4d569e557d) | Mar 07, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [f701ce67f5](https://linux-hardware.org/?probe=f701ce67f5) | Mar 07, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [4c046066f7](https://linux-hardware.org/?probe=4c046066f7) | Mar 05, 2024 |
| Lenovo        | ThinkPad X250 20CLS3NA00    | Notebook    | [ecea244114](https://linux-hardware.org/?probe=ecea244114) | Mar 03, 2024 |
| Unknown       | Unknown                     | Notebook    | [2ca2d631cc](https://linux-hardware.org/?probe=2ca2d631cc) | Mar 02, 2024 |
| Acer          | FIH57                       | Desktop     | [4b9a9a43f3](https://linux-hardware.org/?probe=4b9a9a43f3) | Mar 02, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [54ddd297a5](https://linux-hardware.org/?probe=54ddd297a5) | Mar 02, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [d7d8cc5cc7](https://linux-hardware.org/?probe=d7d8cc5cc7) | Mar 02, 2024 |
| ASUSTek       | Zenbook UP6502ZD_Q539ZD     | Convertible | [23bb682fb2](https://linux-hardware.org/?probe=23bb682fb2) | Mar 02, 2024 |
| HP            | ProBook 4540s               | Notebook    | [46cdfe37d6](https://linux-hardware.org/?probe=46cdfe37d6) | Mar 02, 2024 |
| HP            | ProBook 4540s               | Notebook    | [ec5752452f](https://linux-hardware.org/?probe=ec5752452f) | Mar 02, 2024 |
| HP            | 8434 11                     | Desktop     | [aa98b6327d](https://linux-hardware.org/?probe=aa98b6327d) | Mar 02, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [bcac46fe58](https://linux-hardware.org/?probe=bcac46fe58) | Mar 01, 2024 |
| HP            | 8434 11                     | Desktop     | [5b25b65016](https://linux-hardware.org/?probe=5b25b65016) | Mar 01, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [10c92b676a](https://linux-hardware.org/?probe=10c92b676a) | Feb 29, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [681e76d909](https://linux-hardware.org/?probe=681e76d909) | Feb 29, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [ca45519759](https://linux-hardware.org/?probe=ca45519759) | Feb 29, 2024 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [f785899192](https://linux-hardware.org/?probe=f785899192) | Feb 29, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [11a760c545](https://linux-hardware.org/?probe=11a760c545) | Feb 28, 2024 |
| HP            | 15                          | Notebook    | [6fb113d856](https://linux-hardware.org/?probe=6fb113d856) | Feb 28, 2024 |
| Dell          | 0D24M8 A02                  | Desktop     | [d67f57356b](https://linux-hardware.org/?probe=d67f57356b) | Feb 28, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [9a57de6e15](https://linux-hardware.org/?probe=9a57de6e15) | Feb 27, 2024 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [55a45151a3](https://linux-hardware.org/?probe=55a45151a3) | Feb 27, 2024 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [9b5af4edf6](https://linux-hardware.org/?probe=9b5af4edf6) | Feb 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [49ac7f8a77](https://linux-hardware.org/?probe=49ac7f8a77) | Feb 27, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7167de20ce](https://linux-hardware.org/?probe=7167de20ce) | Feb 27, 2024 |
| Lenovo        | V15 G1 IML 82NB             | Notebook    | [b51e9d56f2](https://linux-hardware.org/?probe=b51e9d56f2) | Feb 27, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b1c31d32ab](https://linux-hardware.org/?probe=b1c31d32ab) | Feb 27, 2024 |
| Intel         | X79Turbo V1.x               | Desktop     | [09f942e7f4](https://linux-hardware.org/?probe=09f942e7f4) | Feb 26, 2024 |
| ASUSTek       | X441UA                      | Notebook    | [1185900ace](https://linux-hardware.org/?probe=1185900ace) | Feb 26, 2024 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | Notebook    | [61e571e08f](https://linux-hardware.org/?probe=61e571e08f) | Feb 26, 2024 |
| Acer          | TravelMate P256-MG          | Notebook    | [abcfd5362f](https://linux-hardware.org/?probe=abcfd5362f) | Feb 25, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [ca33f4c1c6](https://linux-hardware.org/?probe=ca33f4c1c6) | Feb 25, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [6d31b35e19](https://linux-hardware.org/?probe=6d31b35e19) | Feb 25, 2024 |
| ASUSTek       | Zenbook UP6502ZD_Q539ZD     | Convertible | [773d48d7bc](https://linux-hardware.org/?probe=773d48d7bc) | Feb 25, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [be026cabc8](https://linux-hardware.org/?probe=be026cabc8) | Feb 24, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [082b9f50ab](https://linux-hardware.org/?probe=082b9f50ab) | Feb 23, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [56b060901d](https://linux-hardware.org/?probe=56b060901d) | Feb 23, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [83bf2661f0](https://linux-hardware.org/?probe=83bf2661f0) | Feb 23, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [627c4721b6](https://linux-hardware.org/?probe=627c4721b6) | Feb 21, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | Notebook    | [96fb9606bf](https://linux-hardware.org/?probe=96fb9606bf) | Feb 20, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | Notebook    | [520188b3c6](https://linux-hardware.org/?probe=520188b3c6) | Feb 20, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [ba02f5d2ae](https://linux-hardware.org/?probe=ba02f5d2ae) | Feb 18, 2024 |
| Slimbook      | Essential 14                | Notebook    | [05c319f707](https://linux-hardware.org/?probe=05c319f707) | Feb 18, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [f11ff820e7](https://linux-hardware.org/?probe=f11ff820e7) | Feb 18, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [a4b236fd41](https://linux-hardware.org/?probe=a4b236fd41) | Feb 17, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [b5bad706ef](https://linux-hardware.org/?probe=b5bad706ef) | Feb 15, 2024 |
| HP            | 245 G8                      | Notebook    | [c66563da68](https://linux-hardware.org/?probe=c66563da68) | Feb 14, 2024 |
| Dell          | Vostro 1540                 | Notebook    | [ed9ed14ad8](https://linux-hardware.org/?probe=ed9ed14ad8) | Feb 14, 2024 |
| HP            | ZBook 15                    | Notebook    | [bcb41f3b4c](https://linux-hardware.org/?probe=bcb41f3b4c) | Feb 14, 2024 |
| MSI           | GF72VR 7RF                  | Notebook    | [8fb108b426](https://linux-hardware.org/?probe=8fb108b426) | Feb 13, 2024 |
| Gigabyte      | H110N-CF                    | Desktop     | [c6a69fce12](https://linux-hardware.org/?probe=c6a69fce12) | Feb 10, 2024 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [fd10cd8983](https://linux-hardware.org/?probe=fd10cd8983) | Feb 09, 2024 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ae6f0a23e2](https://linux-hardware.org/?probe=ae6f0a23e2) | Feb 09, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d1856c355f](https://linux-hardware.org/?probe=d1856c355f) | Feb 08, 2024 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [d099546e70](https://linux-hardware.org/?probe=d099546e70) | Feb 07, 2024 |
| Intel         | X79Turbo V1.x               | Desktop     | [35c4b20053](https://linux-hardware.org/?probe=35c4b20053) | Feb 07, 2024 |
| Shenzhen M... | F7BSD                       | Mini pc     | [80270fd106](https://linux-hardware.org/?probe=80270fd106) | Feb 07, 2024 |
| Shenzhen M... | F7BSD                       | Mini pc     | [5136f59a7b](https://linux-hardware.org/?probe=5136f59a7b) | Feb 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [498af1a9a2](https://linux-hardware.org/?probe=498af1a9a2) | Feb 06, 2024 |
| Apple         | Mac-F2208EC8                | Mini pc     | [ba8a28b37e](https://linux-hardware.org/?probe=ba8a28b37e) | Feb 06, 2024 |
| Microsoft     | Surface Book 2              | Tablet      | [0434a0132b](https://linux-hardware.org/?probe=0434a0132b) | Feb 06, 2024 |
| Teclast       | F7                          | Notebook    | [04b33deb97](https://linux-hardware.org/?probe=04b33deb97) | Feb 04, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [fdc21a05c2](https://linux-hardware.org/?probe=fdc21a05c2) | Feb 02, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [2cca1daa38](https://linux-hardware.org/?probe=2cca1daa38) | Feb 01, 2024 |
| Acer          | AOD255                      | Notebook    | [43304c651c](https://linux-hardware.org/?probe=43304c651c) | Feb 01, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d1a7f0cddb](https://linux-hardware.org/?probe=d1a7f0cddb) | Jan 31, 2024 |
| HP            | Pavilion g6                 | Notebook    | [acd0ae9c04](https://linux-hardware.org/?probe=acd0ae9c04) | Jan 31, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [973c263365](https://linux-hardware.org/?probe=973c263365) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [7b3a60ae2d](https://linux-hardware.org/?probe=7b3a60ae2d) | Jan 30, 2024 |
| Acer          | Aspire E5-571               | Notebook    | [6ebe6ae5be](https://linux-hardware.org/?probe=6ebe6ae5be) | Jan 28, 2024 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [cff86cc0d9](https://linux-hardware.org/?probe=cff86cc0d9) | Jan 27, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | Notebook    | [1c0f2e8a2f](https://linux-hardware.org/?probe=1c0f2e8a2f) | Jan 26, 2024 |
| Dell          | Latitude E7240              | Notebook    | [d8e5d4a8da](https://linux-hardware.org/?probe=d8e5d4a8da) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [81338699ce](https://linux-hardware.org/?probe=81338699ce) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [9f021a2102](https://linux-hardware.org/?probe=9f021a2102) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [34369cc7eb](https://linux-hardware.org/?probe=34369cc7eb) | Jan 25, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [83f7e8b344](https://linux-hardware.org/?probe=83f7e8b344) | Jan 24, 2024 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [d48bdbaec0](https://linux-hardware.org/?probe=d48bdbaec0) | Jan 24, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [14eec10d5e](https://linux-hardware.org/?probe=14eec10d5e) | Jan 24, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [3361cf9ae9](https://linux-hardware.org/?probe=3361cf9ae9) | Jan 23, 2024 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [40f906871e](https://linux-hardware.org/?probe=40f906871e) | Jan 22, 2024 |
| Gigabyte      | EP43-UD3L                   | Desktop     | [6a2153a6b9](https://linux-hardware.org/?probe=6a2153a6b9) | Jan 21, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [7104f7e7cf](https://linux-hardware.org/?probe=7104f7e7cf) | Jan 21, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | Notebook    | [63d8796a60](https://linux-hardware.org/?probe=63d8796a60) | Jan 20, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [8ffb8f68ca](https://linux-hardware.org/?probe=8ffb8f68ca) | Jan 19, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [86d22c9b40](https://linux-hardware.org/?probe=86d22c9b40) | Jan 17, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [641df770ba](https://linux-hardware.org/?probe=641df770ba) | Jan 17, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5489e559cd](https://linux-hardware.org/?probe=5489e559cd) | Jan 14, 2024 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [41076ef28d](https://linux-hardware.org/?probe=41076ef28d) | Jan 14, 2024 |
| Gigabyte      | EP43-UD3L                   | Desktop     | [8dc280e4fc](https://linux-hardware.org/?probe=8dc280e4fc) | Jan 13, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ab653ac7ff](https://linux-hardware.org/?probe=ab653ac7ff) | Jan 11, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [62374d5cbd](https://linux-hardware.org/?probe=62374d5cbd) | Jan 11, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [f24b7483b8](https://linux-hardware.org/?probe=f24b7483b8) | Jan 11, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3b77d9a786](https://linux-hardware.org/?probe=3b77d9a786) | Jan 11, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7cf8b59aee](https://linux-hardware.org/?probe=7cf8b59aee) | Jan 10, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [75835b3764](https://linux-hardware.org/?probe=75835b3764) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [c3a6a2da37](https://linux-hardware.org/?probe=c3a6a2da37) | Jan 09, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [0f75efabe9](https://linux-hardware.org/?probe=0f75efabe9) | Jan 08, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [3a4a960ff8](https://linux-hardware.org/?probe=3a4a960ff8) | Jan 06, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [75fc0fa74a](https://linux-hardware.org/?probe=75fc0fa74a) | Jan 06, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | Notebook    | [deadd2cf3d](https://linux-hardware.org/?probe=deadd2cf3d) | Jan 05, 2024 |
| HP            | Laptop 17-by3xxx            | Notebook    | [32486bf070](https://linux-hardware.org/?probe=32486bf070) | Jan 04, 2024 |
| Dell          | Latitude E7440              | Notebook    | [75ba78537c](https://linux-hardware.org/?probe=75ba78537c) | Jan 03, 2024 |
| Positivo      | C4128A-15                   | Notebook    | [52bd86685b](https://linux-hardware.org/?probe=52bd86685b) | Jan 03, 2024 |
| HP            | 3397                        | Desktop     | [3339eb00ce](https://linux-hardware.org/?probe=3339eb00ce) | Jan 03, 2024 |
| Medion        | E11202                      | Notebook    | [cb45690620](https://linux-hardware.org/?probe=cb45690620) | Jan 01, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [9ab6343dd7](https://linux-hardware.org/?probe=9ab6343dd7) | Jan 01, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [0120368c3a](https://linux-hardware.org/?probe=0120368c3a) | Jan 01, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [4e8ac17eb6](https://linux-hardware.org/?probe=4e8ac17eb6) | Dec 31, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [4351871367](https://linux-hardware.org/?probe=4351871367) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | Notebook    | [6416d967b8](https://linux-hardware.org/?probe=6416d967b8) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | Notebook    | [bd9afc6d73](https://linux-hardware.org/?probe=bd9afc6d73) | Dec 30, 2023 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [a55f917cf6](https://linux-hardware.org/?probe=a55f917cf6) | Dec 29, 2023 |
| Medion        | E11202                      | Notebook    | [9db140d63c](https://linux-hardware.org/?probe=9db140d63c) | Dec 28, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [76305a2c98](https://linux-hardware.org/?probe=76305a2c98) | Dec 28, 2023 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [de165da202](https://linux-hardware.org/?probe=de165da202) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [d39de69e1b](https://linux-hardware.org/?probe=d39de69e1b) | Dec 27, 2023 |
| THTF          | WUJIE 14                    | Notebook    | [c402523a2c](https://linux-hardware.org/?probe=c402523a2c) | Dec 25, 2023 |
| THTF          | WUJIE 14                    | Notebook    | [39ee354a27](https://linux-hardware.org/?probe=39ee354a27) | Dec 25, 2023 |
| Medion        | E11202                      | Notebook    | [af0c7baf03](https://linux-hardware.org/?probe=af0c7baf03) | Dec 22, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [8a8a35c616](https://linux-hardware.org/?probe=8a8a35c616) | Dec 21, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9839cacb3a](https://linux-hardware.org/?probe=9839cacb3a) | Dec 19, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [8268b72759](https://linux-hardware.org/?probe=8268b72759) | Dec 19, 2023 |
| HP            | 0AA8h                       | Desktop     | [49435a98d1](https://linux-hardware.org/?probe=49435a98d1) | Dec 19, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [38866fae79](https://linux-hardware.org/?probe=38866fae79) | Dec 17, 2023 |
| HP            | 3397                        | Desktop     | [7b379848f1](https://linux-hardware.org/?probe=7b379848f1) | Dec 16, 2023 |
| HP            | 0AA8h                       | Desktop     | [5264c3d3e1](https://linux-hardware.org/?probe=5264c3d3e1) | Dec 16, 2023 |
| HP            | 0AA8h                       | Desktop     | [e20c0fc21b](https://linux-hardware.org/?probe=e20c0fc21b) | Dec 16, 2023 |
| Dell          | Precision 7560              | Notebook    | [0f83098df3](https://linux-hardware.org/?probe=0f83098df3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [abc0a9283d](https://linux-hardware.org/?probe=abc0a9283d) | Dec 14, 2023 |
| ECS           | G41T-M                      | Desktop     | [a0017f196c](https://linux-hardware.org/?probe=a0017f196c) | Dec 14, 2023 |
| ASUSTek       | X75A1                       | Notebook    | [e7d274ca96](https://linux-hardware.org/?probe=e7d274ca96) | Dec 13, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [4d416a35fa](https://linux-hardware.org/?probe=4d416a35fa) | Dec 12, 2023 |
| Sony          | SVE11115ELW                 | Notebook    | [68fa8c6081](https://linux-hardware.org/?probe=68fa8c6081) | Dec 10, 2023 |
| Sony          | SVE11115ELW                 | Notebook    | [567787c7d3](https://linux-hardware.org/?probe=567787c7d3) | Dec 10, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [1b291de7ca](https://linux-hardware.org/?probe=1b291de7ca) | Dec 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5a75d4827a](https://linux-hardware.org/?probe=5a75d4827a) | Dec 10, 2023 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | Notebook    | [4c18329d9d](https://linux-hardware.org/?probe=4c18329d9d) | Dec 09, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [8167f60069](https://linux-hardware.org/?probe=8167f60069) | Dec 05, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [8ca2d01e7c](https://linux-hardware.org/?probe=8ca2d01e7c) | Dec 05, 2023 |
| ASUSTek       | Z97-AR                      | Desktop     | [70936627e8](https://linux-hardware.org/?probe=70936627e8) | Dec 05, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [cfc7698579](https://linux-hardware.org/?probe=cfc7698579) | Dec 04, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [844b16d408](https://linux-hardware.org/?probe=844b16d408) | Dec 03, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5bbcf82cf2](https://linux-hardware.org/?probe=5bbcf82cf2) | Nov 30, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [fa8d37e46b](https://linux-hardware.org/?probe=fa8d37e46b) | Nov 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| HP            | Pavilion dv7                | Notebook    | [c617d0a2d4](https://linux-hardware.org/?probe=c617d0a2d4) | Nov 26, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [cf1e883f11](https://linux-hardware.org/?probe=cf1e883f11) | Nov 25, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [a642075264](https://linux-hardware.org/?probe=a642075264) | Nov 25, 2023 |
| Jetway        | TI61M5                      | Desktop     | [dff0fcc796](https://linux-hardware.org/?probe=dff0fcc796) | Nov 25, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [862134fc6e](https://linux-hardware.org/?probe=862134fc6e) | Nov 24, 2023 |
| Dell          | Inspiron N5040              | Notebook    | [3b51468cdf](https://linux-hardware.org/?probe=3b51468cdf) | Nov 24, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [541efb8e16](https://linux-hardware.org/?probe=541efb8e16) | Nov 24, 2023 |
| Jetway        | TI61M5                      | Desktop     | [968d83ba14](https://linux-hardware.org/?probe=968d83ba14) | Nov 21, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [a2d556bc01](https://linux-hardware.org/?probe=a2d556bc01) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [cdc6379993](https://linux-hardware.org/?probe=cdc6379993) | Nov 19, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [840adf8528](https://linux-hardware.org/?probe=840adf8528) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [886c5bc9a6](https://linux-hardware.org/?probe=886c5bc9a6) | Nov 19, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [8b3abafe9b](https://linux-hardware.org/?probe=8b3abafe9b) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [bcd7007cde](https://linux-hardware.org/?probe=bcd7007cde) | Nov 19, 2023 |
| iOTA          | IOTA2320                    | Notebook    | [5c4d630f23](https://linux-hardware.org/?probe=5c4d630f23) | Nov 19, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5a27242e70](https://linux-hardware.org/?probe=5a27242e70) | Nov 18, 2023 |
| HP            | Pavilion dv7                | Notebook    | [4c482baa30](https://linux-hardware.org/?probe=4c482baa30) | Nov 18, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e05cf328e2](https://linux-hardware.org/?probe=e05cf328e2) | Nov 18, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [8def310709](https://linux-hardware.org/?probe=8def310709) | Nov 16, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [d3a64f5368](https://linux-hardware.org/?probe=d3a64f5368) | Nov 16, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [794f73f426](https://linux-hardware.org/?probe=794f73f426) | Nov 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5ddcb0cf64](https://linux-hardware.org/?probe=5ddcb0cf64) | Nov 15, 2023 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [334569cac2](https://linux-hardware.org/?probe=334569cac2) | Nov 15, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [f191f17f2a](https://linux-hardware.org/?probe=f191f17f2a) | Nov 14, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [88c5f988d8](https://linux-hardware.org/?probe=88c5f988d8) | Nov 13, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [882de5a591](https://linux-hardware.org/?probe=882de5a591) | Nov 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c920563c0b](https://linux-hardware.org/?probe=c920563c0b) | Nov 12, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [3595c8f9d1](https://linux-hardware.org/?probe=3595c8f9d1) | Nov 12, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a49fe13ac0](https://linux-hardware.org/?probe=a49fe13ac0) | Nov 11, 2023 |
| HP            | 245 G8                      | Notebook    | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP            | 245 G8                      | Notebook    | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [9b881d355c](https://linux-hardware.org/?probe=9b881d355c) | Nov 09, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [860fc63d0d](https://linux-hardware.org/?probe=860fc63d0d) | Nov 09, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [a814c93afe](https://linux-hardware.org/?probe=a814c93afe) | Nov 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [5c39f44ed5](https://linux-hardware.org/?probe=5c39f44ed5) | Nov 08, 2023 |
| Dell          | G7 7500                     | Notebook    | [91adca1093](https://linux-hardware.org/?probe=91adca1093) | Nov 07, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [f8cecbac55](https://linux-hardware.org/?probe=f8cecbac55) | Nov 07, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [ab41e88ca3](https://linux-hardware.org/?probe=ab41e88ca3) | Nov 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d90141a70e](https://linux-hardware.org/?probe=d90141a70e) | Nov 06, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [2d3d09097d](https://linux-hardware.org/?probe=2d3d09097d) | Nov 06, 2023 |
| Dell          | G7 7500                     | Notebook    | [3678c5437b](https://linux-hardware.org/?probe=3678c5437b) | Nov 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [99b0c9edcf](https://linux-hardware.org/?probe=99b0c9edcf) | Nov 06, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [2d84377719](https://linux-hardware.org/?probe=2d84377719) | Nov 06, 2023 |
| HP            | 245 G8                      | Notebook    | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| HP            | Spectre Pro G1              | Notebook    | [78bce56071](https://linux-hardware.org/?probe=78bce56071) | Nov 05, 2023 |
| HP            | ProBook 6545b               | Notebook    | [a81427fffa](https://linux-hardware.org/?probe=a81427fffa) | Nov 05, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2cc662a279](https://linux-hardware.org/?probe=2cc662a279) | Nov 05, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [2053de6443](https://linux-hardware.org/?probe=2053de6443) | Nov 05, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [f8e737dbde](https://linux-hardware.org/?probe=f8e737dbde) | Nov 03, 2023 |
| HONOR         | NMH-WDX9                    | Notebook    | [11e32e2482](https://linux-hardware.org/?probe=11e32e2482) | Nov 03, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [a81d5bbd02](https://linux-hardware.org/?probe=a81d5bbd02) | Nov 03, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [684c7d7bf7](https://linux-hardware.org/?probe=684c7d7bf7) | Nov 03, 2023 |
| HP            | 0B54h D                     | Desktop     | [4ec7776a76](https://linux-hardware.org/?probe=4ec7776a76) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [72a5b8f06a](https://linux-hardware.org/?probe=72a5b8f06a) | Nov 02, 2023 |
| Alienware     | 14                          | Notebook    | [3d3be9ce75](https://linux-hardware.org/?probe=3d3be9ce75) | Nov 01, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [a9ed160c1c](https://linux-hardware.org/?probe=a9ed160c1c) | Nov 01, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [7efb8849d2](https://linux-hardware.org/?probe=7efb8849d2) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [e25974d32d](https://linux-hardware.org/?probe=e25974d32d) | Oct 31, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [5a1d90c1a7](https://linux-hardware.org/?probe=5a1d90c1a7) | Oct 30, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a115d38855](https://linux-hardware.org/?probe=a115d38855) | Oct 29, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [300d56f39e](https://linux-hardware.org/?probe=300d56f39e) | Oct 29, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [29a362f501](https://linux-hardware.org/?probe=29a362f501) | Oct 29, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [b5e0b9a020](https://linux-hardware.org/?probe=b5e0b9a020) | Oct 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [38ed4f25af](https://linux-hardware.org/?probe=38ed4f25af) | Oct 27, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [61b133ac1e](https://linux-hardware.org/?probe=61b133ac1e) | Oct 27, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | Desktop     | [b9ec438e43](https://linux-hardware.org/?probe=b9ec438e43) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [3b82b142b1](https://linux-hardware.org/?probe=3b82b142b1) | Oct 26, 2023 |
| Dell          | Latitude E6520              | Notebook    | [dbbca588de](https://linux-hardware.org/?probe=dbbca588de) | Oct 26, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [a8b1ad0f53](https://linux-hardware.org/?probe=a8b1ad0f53) | Oct 25, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [5713b2f30e](https://linux-hardware.org/?probe=5713b2f30e) | Oct 24, 2023 |
| Dell          | Latitude E6400              | Notebook    | [250c9ddcfe](https://linux-hardware.org/?probe=250c9ddcfe) | Oct 24, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [89f29afb19](https://linux-hardware.org/?probe=89f29afb19) | Oct 24, 2023 |
| ASUSTek       | P5G41-M LX2/GB              | Desktop     | [ffc0782186](https://linux-hardware.org/?probe=ffc0782186) | Oct 23, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [2100dab18e](https://linux-hardware.org/?probe=2100dab18e) | Oct 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [6a3537c763](https://linux-hardware.org/?probe=6a3537c763) | Oct 23, 2023 |
| Dell          | Latitude E6520              | Notebook    | [c2fd0014ab](https://linux-hardware.org/?probe=c2fd0014ab) | Oct 23, 2023 |
| Acer          | G33T-AM                     | Desktop     | [7b42f4db1d](https://linux-hardware.org/?probe=7b42f4db1d) | Oct 23, 2023 |
| Acer          | G33T-AM                     | Desktop     | [70f67a6f11](https://linux-hardware.org/?probe=70f67a6f11) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3431e88cbe](https://linux-hardware.org/?probe=3431e88cbe) | Oct 22, 2023 |
| Google        | Cave                        | Notebook    | [287887d308](https://linux-hardware.org/?probe=287887d308) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [855c6109eb](https://linux-hardware.org/?probe=855c6109eb) | Oct 20, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [85eb0ffd0c](https://linux-hardware.org/?probe=85eb0ffd0c) | Oct 19, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | Desktop     | [7ad6760006](https://linux-hardware.org/?probe=7ad6760006) | Oct 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [13b6b396e9](https://linux-hardware.org/?probe=13b6b396e9) | Oct 18, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [036b6067b8](https://linux-hardware.org/?probe=036b6067b8) | Oct 18, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [78164f9bcc](https://linux-hardware.org/?probe=78164f9bcc) | Oct 18, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | Desktop     | [bc7e7d2817](https://linux-hardware.org/?probe=bc7e7d2817) | Oct 17, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [1e3660c797](https://linux-hardware.org/?probe=1e3660c797) | Oct 17, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [3dde86d447](https://linux-hardware.org/?probe=3dde86d447) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [87edaec977](https://linux-hardware.org/?probe=87edaec977) | Oct 17, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [47f6f3760d](https://linux-hardware.org/?probe=47f6f3760d) | Oct 17, 2023 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [f01b625d01](https://linux-hardware.org/?probe=f01b625d01) | Oct 16, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [2f6c2f44d3](https://linux-hardware.org/?probe=2f6c2f44d3) | Oct 15, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [23c3f61285](https://linux-hardware.org/?probe=23c3f61285) | Oct 14, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [a654820b23](https://linux-hardware.org/?probe=a654820b23) | Oct 13, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [de2f74b12a](https://linux-hardware.org/?probe=de2f74b12a) | Oct 13, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a5d87b55d9](https://linux-hardware.org/?probe=a5d87b55d9) | Oct 12, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [b756b81d33](https://linux-hardware.org/?probe=b756b81d33) | Oct 12, 2023 |
| Lenovo        | B570 1068FRG                | Notebook    | [e912de748b](https://linux-hardware.org/?probe=e912de748b) | Oct 11, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [6324053514](https://linux-hardware.org/?probe=6324053514) | Oct 10, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [7bbfda81b1](https://linux-hardware.org/?probe=7bbfda81b1) | Oct 10, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [c41bac6f71](https://linux-hardware.org/?probe=c41bac6f71) | Oct 09, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0c8f955052](https://linux-hardware.org/?probe=0c8f955052) | Oct 08, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [61890a8e2e](https://linux-hardware.org/?probe=61890a8e2e) | Oct 08, 2023 |
| Dell          | 0GTK4K A02                  | Desktop     | [05d87a2b59](https://linux-hardware.org/?probe=05d87a2b59) | Oct 08, 2023 |
| Dell          | 0GTK4K A02                  | Desktop     | [7480d29d9f](https://linux-hardware.org/?probe=7480d29d9f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [ccc23328e5](https://linux-hardware.org/?probe=ccc23328e5) | Oct 07, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [39ee83fbf5](https://linux-hardware.org/?probe=39ee83fbf5) | Oct 06, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [21ec0f4129](https://linux-hardware.org/?probe=21ec0f4129) | Oct 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a49cef1179](https://linux-hardware.org/?probe=a49cef1179) | Oct 04, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d91dd7bed6](https://linux-hardware.org/?probe=d91dd7bed6) | Oct 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [3513d5bcf3](https://linux-hardware.org/?probe=3513d5bcf3) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [c643f10970](https://linux-hardware.org/?probe=c643f10970) | Sep 24, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [945e2bc260](https://linux-hardware.org/?probe=945e2bc260) | Sep 24, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [e9478deeae](https://linux-hardware.org/?probe=e9478deeae) | Sep 23, 2023 |
| Dell          | Latitude E7270              | Notebook    | [874b8a2ad5](https://linux-hardware.org/?probe=874b8a2ad5) | Sep 23, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9229686681](https://linux-hardware.org/?probe=9229686681) | Sep 23, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [ca346761d3](https://linux-hardware.org/?probe=ca346761d3) | Sep 23, 2023 |
| HP            | Laptop 17-by4xxx            | Notebook    | [dd1d978c67](https://linux-hardware.org/?probe=dd1d978c67) | Sep 22, 2023 |
| HP            | 2ADC                        | Desktop     | [b4794f247b](https://linux-hardware.org/?probe=b4794f247b) | Sep 21, 2023 |
| HP            | 2ADC                        | Desktop     | [7e9eb06b31](https://linux-hardware.org/?probe=7e9eb06b31) | Sep 21, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [c8bbae1068](https://linux-hardware.org/?probe=c8bbae1068) | Sep 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [603ddfc4cf](https://linux-hardware.org/?probe=603ddfc4cf) | Sep 18, 2023 |
| ASUSTek       | VM42                        | Desktop     | [ca9a3b42d0](https://linux-hardware.org/?probe=ca9a3b42d0) | Sep 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 743       | 31%     |
| Elementary 7.1   | 588       | 24.53%  |
| Elementary 7     | 254       | 10.6%   |
| Elementary 5.1.7 | 240       | 10.01%  |
| Elementary 6     | 233       | 9.72%   |
| Elementary 8     | 83        | 3.46%   |
| Elementary 5.0   | 55        | 2.29%   |
| Elementary 5.1   | 46        | 1.92%   |
| Elementary 5.1.6 | 35        | 1.46%   |
| Elementary 5.1.4 | 33        | 1.38%   |
| Elementary 5.1.2 | 29        | 1.21%   |
| Elementary 5.1.3 | 23        | 0.96%   |
| Elementary 0.4.1 | 17        | 0.71%   |
| Elementary 5.1.5 | 11        | 0.46%   |
| Elementary 6.0   | 7         | 0.29%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 2301      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-43-generic | 138       | 5.36%   |
| 6.2.0-33-generic  | 107       | 4.16%   |
| 5.15.0-58-generic | 90        | 3.5%    |
| 6.8.0-49-generic  | 59        | 2.29%   |
| 5.11.0-40-generic | 57        | 2.22%   |
| 5.15.0-46-generic | 55        | 2.14%   |
| 5.13.0-28-generic | 54        | 2.1%    |
| 6.8.0-40-generic  | 52        | 2.02%   |
| 5.11.0-41-generic | 52        | 2.02%   |
| 5.15.0-56-generic | 46        | 1.79%   |
| 5.11.0-27-generic | 40        | 1.55%   |
| 6.8.0-51-generic  | 39        | 1.52%   |
| 6.5.0-41-generic  | 38        | 1.48%   |
| 6.5.0-35-generic  | 38        | 1.48%   |
| 5.13.0-30-generic | 38        | 1.48%   |
| 5.13.0-27-generic | 36        | 1.4%    |
| 5.13.0-39-generic | 35        | 1.36%   |
| 6.8.0-45-generic  | 33        | 1.28%   |
| 6.5.0-28-generic  | 33        | 1.28%   |
| 5.4.0-42-generic  | 32        | 1.24%   |
| 6.5.0-26-generic  | 29        | 1.13%   |
| 5.15.0-52-generic | 28        | 1.09%   |
| 6.8.0-48-generic  | 27        | 1.05%   |
| 5.13.0-40-generic | 27        | 1.05%   |
| 5.11.0-38-generic | 27        | 1.05%   |
| 6.2.0-26-generic  | 25        | 0.97%   |
| 5.15.0-41-generic | 25        | 0.97%   |
| 5.11.0-37-generic | 25        | 0.97%   |
| 5.0.0-37-generic  | 25        | 0.97%   |
| 6.8.0-47-generic  | 24        | 0.93%   |
| 5.19.0-46-generic | 24        | 0.93%   |
| 5.19.0-41-generic | 23        | 0.89%   |
| 5.15.0-48-generic | 23        | 0.89%   |
| 5.13.0-35-generic | 23        | 0.89%   |
| 6.2.0-36-generic  | 22        | 0.86%   |
| 5.19.0-35-generic | 22        | 0.86%   |
| 5.19.0-32-generic | 22        | 0.86%   |
| 5.3.0-62-generic  | 21        | 0.82%   |
| 5.15.0-53-generic | 20        | 0.78%   |
| 5.13.0-37-generic | 20        | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 391       | 16.14%  |
| 5.15.0  | 350       | 14.45%  |
| 5.13.0  | 284       | 11.73%  |
| 6.5.0   | 248       | 10.24%  |
| 6.8.0   | 241       | 9.95%   |
| 6.2.0   | 222       | 9.17%   |
| 5.4.0   | 222       | 9.17%   |
| 5.19.0  | 135       | 5.57%   |
| 5.3.0   | 111       | 4.58%   |
| 4.15.0  | 87        | 3.59%   |
| 5.0.0   | 32        | 1.32%   |
| 5.8.0   | 14        | 0.58%   |
| 5.14.0  | 4         | 0.17%   |
| 4.18.0  | 4         | 0.17%   |
| 4.13.0  | 4         | 0.17%   |
| 5.10.0  | 3         | 0.12%   |
| 4.4.0   | 3         | 0.12%   |
| 6.5.5   | 2         | 0.08%   |
| 5.15.5  | 2         | 0.08%   |
| 5.15.36 | 2         | 0.08%   |
| 5.15.12 | 2         | 0.08%   |
| 4.10.0  | 2         | 0.08%   |
| 6.8.8   | 1         | 0.04%   |
| 6.7.3   | 1         | 0.04%   |
| 6.7.10  | 1         | 0.04%   |
| 6.5.7   | 1         | 0.04%   |
| 6.4.5   | 1         | 0.04%   |
| 6.3.13  | 1         | 0.04%   |
| 6.2.8   | 1         | 0.04%   |
| 6.2.7   | 1         | 0.04%   |
| 6.2.2   | 1         | 0.04%   |
| 6.2.14  | 1         | 0.04%   |
| 6.12.6  | 1         | 0.04%   |
| 6.11.5  | 1         | 0.04%   |
| 6.1.9   | 1         | 0.04%   |
| 6.1.8   | 1         | 0.04%   |
| 6.1.6   | 1         | 0.04%   |
| 6.1.0   | 1         | 0.04%   |
| 6.0.8   | 1         | 0.04%   |
| 6.0.0   | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 391       | 16.17%  |
| 5.15    | 363       | 15.01%  |
| 5.13    | 284       | 11.75%  |
| 6.5     | 251       | 10.38%  |
| 6.8     | 242       | 10.01%  |
| 6.2     | 225       | 9.31%   |
| 5.4     | 224       | 9.26%   |
| 5.19    | 139       | 5.75%   |
| 5.3     | 113       | 4.67%   |
| 4.15    | 87        | 3.6%    |
| 5.0     | 33        | 1.36%   |
| 5.8     | 16        | 0.66%   |
| 5.14    | 8         | 0.33%   |
| 6.1     | 4         | 0.17%   |
| 5.16    | 4         | 0.17%   |
| 5.10    | 4         | 0.17%   |
| 4.18    | 4         | 0.17%   |
| 4.13    | 4         | 0.17%   |
| 4.4     | 3         | 0.12%   |
| 6.7     | 2         | 0.08%   |
| 6.0     | 2         | 0.08%   |
| 5.5     | 2         | 0.08%   |
| 5.17    | 2         | 0.08%   |
| 4.10    | 2         | 0.08%   |
| 6.4     | 1         | 0.04%   |
| 6.3     | 1         | 0.04%   |
| 6.12    | 1         | 0.04%   |
| 6.11    | 1         | 0.04%   |
| 5.9     | 1         | 0.04%   |
| 5.7     | 1         | 0.04%   |
| 5.6     | 1         | 0.04%   |
| 5.2     | 1         | 0.04%   |
| 5.18    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2300      | 99.96%  |
| aarch64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pantheon      | 2189      | 94.31%  |
| Unknown       | 106       | 4.57%   |
| GNOME         | 15        | 0.65%   |
| X-Cinnamon    | 4         | 0.17%   |
| KDE5          | 2         | 0.09%   |
| XFCE          | 1         | 0.04%   |
| Unity         | 1         | 0.04%   |
| MATE          | 1         | 0.04%   |
| GNOME Classic | 1         | 0.04%   |
| Budgie        | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2295      | 99.65%  |
| Wayland | 5         | 0.22%   |
| Unknown | 2         | 0.09%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1890      | 81.12%  |
| LightDM | 362       | 15.54%  |
| TDM     | 69        | 2.96%   |
| GDM     | 5         | 0.21%   |
| SDDM    | 2         | 0.09%   |
| GDM3    | 2         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 953       | 40.97%  |
| de_DE   | 259       | 11.13%  |
| es_ES   | 179       | 7.7%    |
| ru_RU   | 135       | 5.8%    |
| pt_BR   | 94        | 4.04%   |
| en_GB   | 93        | 4%      |
| fr_FR   | 90        | 3.87%   |
| it_IT   | 80        | 3.44%   |
| Unknown | 65        | 2.79%   |
| pl_PL   | 46        | 1.98%   |
| en_CA   | 32        | 1.38%   |
| en_AU   | 30        | 1.29%   |
| nl_NL   | 29        | 1.25%   |
| tr_TR   | 21        | 0.9%    |
| pt_PT   | 19        | 0.82%   |
| hu_HU   | 18        | 0.77%   |
| sv_SE   | 17        | 0.73%   |
| cs_CZ   | 12        | 0.52%   |
| en_IN   | 11        | 0.47%   |
| de_CH   | 11        | 0.47%   |
| zh_CN   | 9         | 0.39%   |
| nb_NO   | 9         | 0.39%   |
| es_MX   | 9         | 0.39%   |
| uk_UA   | 7         | 0.3%    |
| id_ID   | 6         | 0.26%   |
| fr_CA   | 6         | 0.26%   |
| fi_FI   | 6         | 0.26%   |
| el_GR   | 6         | 0.26%   |
| da_DK   | 6         | 0.26%   |
| ja_JP   | 5         | 0.21%   |
| hr_HR   | 4         | 0.17%   |
| es_EC   | 4         | 0.17%   |
| en_ZA   | 4         | 0.17%   |
| ca_ES   | 4         | 0.17%   |
| bg_BG   | 4         | 0.17%   |
| zh_TW   | 3         | 0.13%   |
| es_AR   | 3         | 0.13%   |
| C       | 3         | 0.13%   |
| ko_KR   | 2         | 0.09%   |
| gl_ES   | 2         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1375      | 58.84%  |
| EFI  | 962       | 41.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2178      | 94.08%  |
| Btrfs    | 39        | 1.68%   |
| Tmpfs    | 36        | 1.56%   |
| Overlay  | 25        | 1.08%   |
| Unknown  | 21        | 0.91%   |
| Xfs      | 13        | 0.56%   |
| Reiserfs | 1         | 0.04%   |
| Ext3     | 1         | 0.04%   |
| Ext2     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1937      | 83.17%  |
| GPT     | 312       | 13.4%   |
| MBR     | 80        | 3.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2224      | 96.53%  |
| Yes       | 80        | 3.47%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2093      | 90.33%  |
| Yes       | 224       | 9.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 349       | 15.17%  |
| Lenovo              | 322       | 13.99%  |
| Apple               | 305       | 13.26%  |
| ASUSTek Computer    | 285       | 12.39%  |
| Dell                | 249       | 10.82%  |
| Acer                | 125       | 5.43%   |
| Gigabyte Technology | 101       | 4.39%   |
| MSI                 | 84        | 3.65%   |
| ASRock              | 44        | 1.91%   |
| HUAWEI              | 39        | 1.69%   |
| Toshiba             | 36        | 1.56%   |
| Samsung Electronics | 31        | 1.35%   |
| Intel               | 31        | 1.35%   |
| Sony                | 24        | 1.04%   |
| Unknown             | 19        | 0.83%   |
| Fujitsu             | 16        | 0.7%    |
| Microsoft           | 15        | 0.65%   |
| Google              | 13        | 0.56%   |
| Medion              | 11        | 0.48%   |
| Biostar             | 10        | 0.43%   |
| Packard Bell        | 9         | 0.39%   |
| Pegatron            | 8         | 0.35%   |
| Chuwi               | 8         | 0.35%   |
| Alienware           | 8         | 0.35%   |
| Foxconn             | 7         | 0.3%    |
| LG Electronics      | 6         | 0.26%   |
| Star Labs           | 5         | 0.22%   |
| Notebook            | 5         | 0.22%   |
| ECS                 | 5         | 0.22%   |
| AMI                 | 5         | 0.22%   |
| Timi                | 4         | 0.17%   |
| Positivo            | 4         | 0.17%   |
| eMachines           | 4         | 0.17%   |
| Compaq              | 4         | 0.17%   |
| Wortmann AG         | 3         | 0.13%   |
| TUXEDO              | 3         | 0.13%   |
| Teclast             | 3         | 0.13%   |
| Razer               | 3         | 0.13%   |
| Panasonic           | 3         | 0.13%   |
| MACHINIST           | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 23        | 1%      |
| Apple MacBookPro8,1          | 22        | 0.96%   |
| Apple MacBookPro9,2          | 19        | 0.83%   |
| Apple MacBookAir7,2          | 19        | 0.83%   |
| ASUS All Series              | 12        | 0.52%   |
| Apple iMac7,1                | 10        | 0.43%   |
| Apple MacBookPro8,2          | 9         | 0.39%   |
| Apple MacBookPro7,1          | 8         | 0.35%   |
| Apple MacBookPro6,2          | 8         | 0.35%   |
| Apple MacBookPro5,5          | 8         | 0.35%   |
| Apple iMac8,1                | 8         | 0.35%   |
| HP Notebook                  | 7         | 0.3%    |
| Apple MacBookAir6,2          | 7         | 0.3%    |
| Apple MacBook5,1             | 7         | 0.3%    |
| Apple iMac12,1               | 7         | 0.3%    |
| HP Pavilion g6               | 6         | 0.26%   |
| HP Pavilion dv7              | 6         | 0.26%   |
| HP Pavilion 17               | 6         | 0.26%   |
| Dell Inspiron 15-3567        | 6         | 0.26%   |
| ASUS PRIME A320M-K           | 6         | 0.26%   |
| Apple MacBookPro9,1          | 6         | 0.26%   |
| Apple MacBookPro11,2         | 6         | 0.26%   |
| Apple MacBookAir3,1          | 6         | 0.26%   |
| Apple MacBook4,1             | 6         | 0.26%   |
| Apple iMac9,1                | 6         | 0.26%   |
| Apple iMac14,1               | 6         | 0.26%   |
| Apple iMac11,3               | 6         | 0.26%   |
| Lenovo G50-45 80E3           | 5         | 0.22%   |
| HUAWEI NBLB-WAX9N            | 5         | 0.22%   |
| HUAWEI MACHD-WXX9            | 5         | 0.22%   |
| HP Laptop 15-bw0xx           | 5         | 0.22%   |
| HP EliteBook 840 G3          | 5         | 0.22%   |
| HP 15                        | 5         | 0.22%   |
| Dell Latitude E6400          | 5         | 0.22%   |
| Dell Inspiron 1545           | 5         | 0.22%   |
| ASUS ZenBook UX425EA_UX425EA | 5         | 0.22%   |
| Apple Macmini6,1             | 5         | 0.22%   |
| Apple Macmini5,1             | 5         | 0.22%   |
| Apple MacBookAir4,2          | 5         | 0.22%   |
| MSI MS-7C02                  | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 130       | 5.65%   |
| Lenovo IdeaPad     | 90        | 3.91%   |
| Acer Aspire        | 86        | 3.74%   |
| HP Pavilion        | 72        | 3.13%   |
| Dell Latitude      | 69        | 3%      |
| Dell Inspiron      | 69        | 3%      |
| HP ProBook         | 50        | 2.17%   |
| HP EliteBook       | 42        | 1.83%   |
| HP Laptop          | 41        | 1.78%   |
| Apple MacBookPro8  | 35        | 1.52%   |
| ASUS PRIME         | 32        | 1.39%   |
| Dell OptiPlex      | 31        | 1.35%   |
| Toshiba Satellite  | 28        | 1.22%   |
| Dell XPS           | 28        | 1.22%   |
| ASUS VivoBook      | 26        | 1.13%   |
| ASUS ROG           | 25        | 1.09%   |
| Apple MacBookPro9  | 25        | 1.09%   |
| Unknown            | 23        | 1%      |
| ASUS ZenBook       | 22        | 0.96%   |
| Apple MacBookAir7  | 21        | 0.91%   |
| Lenovo ThinkCentre | 19        | 0.83%   |
| HP ENVY            | 19        | 0.83%   |
| Dell Precision     | 19        | 0.83%   |
| Apple MacBookPro11 | 19        | 0.83%   |
| HP Compaq          | 18        | 0.78%   |
| Apple MacBookPro5  | 18        | 0.78%   |
| Dell Vostro        | 16        | 0.7%    |
| Microsoft Surface  | 15        | 0.65%   |
| ASUS TUF           | 15        | 0.65%   |
| Acer Swift         | 15        | 0.65%   |
| ASUS All           | 12        | 0.52%   |
| Apple iMac14       | 12        | 0.52%   |
| Lenovo Yoga        | 11        | 0.48%   |
| Apple MacBookAir6  | 11        | 0.48%   |
| Apple iMac11       | 11        | 0.48%   |
| Fujitsu LIFEBOOK   | 10        | 0.43%   |
| Apple iMac7        | 10        | 0.43%   |
| Apple iMac12       | 10        | 0.43%   |
| Apple MacBook5     | 9         | 0.39%   |
| Lenovo Legion      | 8         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 223       | 9.69%   |
| 2018    | 202       | 8.78%   |
| 2013    | 183       | 7.95%   |
| 2011    | 178       | 7.74%   |
| 2020    | 172       | 7.48%   |
| 2019    | 165       | 7.17%   |
| 2010    | 155       | 6.74%   |
| 2021    | 148       | 6.43%   |
| 2017    | 141       | 6.13%   |
| 2014    | 134       | 5.82%   |
| 2015    | 133       | 5.78%   |
| 2016    | 128       | 5.56%   |
| 2009    | 99        | 4.3%    |
| 2008    | 90        | 3.91%   |
| 2022    | 55        | 2.39%   |
| 2007    | 46        | 2%      |
| 2023    | 31        | 1.35%   |
| 2024    | 9         | 0.39%   |
| 2006    | 6         | 0.26%   |
| Unknown | 2         | 0.09%   |
| 2005    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1470      | 63.89%  |
| Desktop        | 584       | 25.38%  |
| All in one     | 101       | 4.39%   |
| Convertible    | 55        | 2.39%   |
| Mini pc        | 52        | 2.26%   |
| Tablet         | 31        | 1.35%   |
| Server         | 7         | 0.3%    |
| System on chip | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2136      | 92.35%  |
| Enabled  | 177       | 7.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2282      | 99.17%  |
| Yes  | 19        | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 706       | 30.43%  |
| 16.01-24.0  | 444       | 19.14%  |
| 3.01-4.0    | 440       | 18.97%  |
| 8.01-16.0   | 405       | 17.46%  |
| 32.01-64.0  | 165       | 7.11%   |
| 1.01-2.0    | 70        | 3.02%   |
| 2.01-3.0    | 32        | 1.38%   |
| 64.01-256.0 | 30        | 1.29%   |
| 24.01-32.0  | 26        | 1.12%   |
| 0.51-1.0    | 2         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 842       | 33.68%  |
| 2.01-3.0   | 810       | 32.4%   |
| 3.01-4.0   | 405       | 16.2%   |
| 4.01-8.0   | 314       | 12.56%  |
| 0.51-1.0   | 64        | 2.56%   |
| 8.01-16.0  | 61        | 2.44%   |
| 16.01-24.0 | 2         | 0.08%   |
| 32.01-64.0 | 1         | 0.04%   |
| 24.01-32.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1532      | 65.44%  |
| 2       | 584       | 24.95%  |
| 3       | 118       | 5.04%   |
| 4       | 51        | 2.18%   |
| 5       | 24        | 1.03%   |
| 0       | 12        | 0.51%   |
| 6       | 10        | 0.43%   |
| 7       | 6         | 0.26%   |
| 9       | 2         | 0.09%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1467      | 63.23%  |
| Yes       | 853       | 36.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1895      | 82.32%  |
| No        | 407       | 17.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1985      | 85.89%  |
| No        | 326       | 14.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1697      | 73.24%  |
| No        | 620       | 26.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 351       | 15.21%  |
| Germany      | 256       | 11.09%  |
| Brazil       | 135       | 5.85%   |
| Russia       | 133       | 5.76%   |
| UK           | 96        | 4.16%   |
| Italy        | 95        | 4.12%   |
| Spain        | 85        | 3.68%   |
| France       | 75        | 3.25%   |
| India        | 68        | 2.95%   |
| Canada       | 67        | 2.9%    |
| Mexico       | 61        | 2.64%   |
| Poland       | 54        | 2.34%   |
| Indonesia    | 52        | 2.25%   |
| Australia    | 49        | 2.12%   |
| Netherlands  | 47        | 2.04%   |
| Turkey       | 36        | 1.56%   |
| Argentina    | 34        | 1.47%   |
| Austria      | 33        | 1.43%   |
| Sweden       | 28        | 1.21%   |
| Portugal     | 26        | 1.13%   |
| Belgium      | 26        | 1.13%   |
| Switzerland  | 25        | 1.08%   |
| Hungary      | 21        | 0.91%   |
| Ukraine      | 20        | 0.87%   |
| Czechia      | 20        | 0.87%   |
| Chile        | 20        | 0.87%   |
| Greece       | 17        | 0.74%   |
| Romania      | 15        | 0.65%   |
| Norway       | 15        | 0.65%   |
| Colombia     | 15        | 0.65%   |
| Malaysia     | 14        | 0.61%   |
| Finland      | 14        | 0.61%   |
| South Africa | 13        | 0.56%   |
| Ireland      | 12        | 0.52%   |
| New Zealand  | 11        | 0.48%   |
| China        | 11        | 0.48%   |
| Bulgaria     | 11        | 0.48%   |
| Denmark      | 10        | 0.43%   |
| Egypt        | 9         | 0.39%   |
| Belarus      | 9         | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 39        | 1.61%   |
| Berlin         | 22        | 0.91%   |
| Warsaw         | 21        | 0.87%   |
| Munich         | 19        | 0.78%   |
| Vienna         | 17        | 0.7%    |
| Madrid         | 17        | 0.7%    |
| Istanbul       | 16        | 0.66%   |
| Hamburg        | 16        | 0.66%   |
| Sydney         | 14        | 0.58%   |
| St Petersburg  | 14        | 0.58%   |
| Milan          | 14        | 0.58%   |
| Paris          | 13        | 0.54%   |
| Los Angeles    | 13        | 0.54%   |
| Rio de Janeiro | 12        | 0.49%   |
| Sao Paulo      | 11        | 0.45%   |
| Melbourne      | 11        | 0.45%   |
| Jakarta        | 11        | 0.45%   |
| Rome           | 10        | 0.41%   |
| Fortaleza      | 10        | 0.41%   |
| Delhi          | 10        | 0.41%   |
| Budapest       | 10        | 0.41%   |
| Santiago       | 9         | 0.37%   |
| Perth          | 9         | 0.37%   |
| Novosibirsk    | 9         | 0.37%   |
| Mexico City    | 9         | 0.37%   |
| Stuttgart      | 8         | 0.33%   |
| Montreal       | 8         | 0.33%   |
| Dublin         | 8         | 0.33%   |
| Athens         | 8         | 0.33%   |
| The Hague      | 7         | 0.29%   |
| Prague         | 7         | 0.29%   |
| Córdoba       | 7         | 0.29%   |
| Valencia       | 6         | 0.25%   |
| Surabaya       | 6         | 0.25%   |
| Stockholm      | 6         | 0.25%   |
| San Jose       | 6         | 0.25%   |
| Mumbai         | 6         | 0.25%   |
| Krakow         | 6         | 0.25%   |
| Dresden        | 6         | 0.25%   |
| Cairo          | 6         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 420       | 573    | 13.29%  |
| WDC                         | 384       | 511    | 12.15%  |
| Seagate                     | 353       | 460    | 11.17%  |
| Toshiba                     | 211       | 262    | 6.68%   |
| Sandisk                     | 201       | 236    | 6.36%   |
| Kingston                    | 188       | 244    | 5.95%   |
| Unknown                     | 140       | 185    | 4.43%   |
| Crucial                     | 130       | 159    | 4.11%   |
| Apple                       | 113       | 131    | 3.58%   |
| Hitachi                     | 92        | 101    | 2.91%   |
| Intel                       | 71        | 95     | 2.25%   |
| SK hynix                    | 68        | 82     | 2.15%   |
| HGST                        | 65        | 78     | 2.06%   |
| A-DATA Technology           | 49        | 56     | 1.55%   |
| Micron Technology           | 42        | 46     | 1.33%   |
| China                       | 40        | 51     | 1.27%   |
| KIOXIA                      | 30        | 43     | 0.95%   |
| PNY                         | 24        | 32     | 0.76%   |
| Silicon Motion              | 22        | 24     | 0.7%    |
| Unknown                     | 21        | 24     | 0.66%   |
| Phison                      | 20        | 22     | 0.63%   |
| Micron/Crucial Technology   | 20        | 27     | 0.63%   |
| LITEON                      | 18        | 18     | 0.57%   |
| Intenso                     | 17        | 20     | 0.54%   |
| Transcend                   | 16        | 19     | 0.51%   |
| Fujitsu                     | 16        | 18     | 0.51%   |
| SPCC                        | 14        | 14     | 0.44%   |
| Patriot                     | 14        | 17     | 0.44%   |
| Phison Electronics          | 13        | 13     | 0.41%   |
| JMicron Technology          | 13        | 13     | 0.41%   |
| OCZ                         | 11        | 17     | 0.35%   |
| Netac                       | 10        | 11     | 0.32%   |
| Hewlett-Packard             | 10        | 15     | 0.32%   |
| Apacer                      | 10        | 12     | 0.32%   |
| Team                        | 9         | 12     | 0.28%   |
| Realtek Semiconductor       | 9         | 12     | 0.28%   |
| Kingston Technology Company | 9         | 9      | 0.28%   |
| Gigabyte Technology         | 9         | 9      | 0.28%   |
| MAXIO Technology (Hangzhou) | 8         | 10     | 0.25%   |
| Corsair                     | 8         | 8      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                      | 56        | 1.66%   |
| Unknown MMC Card  64GB                               | 31        | 0.92%   |
| Toshiba MQ01ABD100 1TB                               | 31        | 0.92%   |
| Unknown MMC Card  32GB                               | 29        | 0.86%   |
| Seagate ST1000LM035-1RK172 1TB                       | 25        | 0.74%   |
| Samsung SSD 850 EVO 250GB                            | 25        | 0.74%   |
| Kingston SA400S37120G 120GB SSD                      | 25        | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 24        | 0.71%   |
| Samsung NVMe SSD Drive 512GB                         | 22        | 0.65%   |
| Samsung NVMe SSD Drive 256GB                         | 21        | 0.62%   |
| Unknown                                              | 21        | 0.62%   |
| Seagate ST500LT012-1DG142 500GB                      | 20        | 0.59%   |
| Samsung SSD 860 EVO 500GB                            | 20        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 19        | 0.56%   |
| Seagate ST500DM002-1BD142 500GB                      | 19        | 0.56%   |
| HGST HTS721010A9E630 1TB                             | 19        | 0.56%   |
| Crucial CT240BX500SSD1 240GB                         | 19        | 0.56%   |
| Unknown MMC Card  128GB                              | 18        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 17        | 0.5%    |
| Crucial CT500MX500SSD1 500GB                         | 17        | 0.5%    |
| Toshiba MQ04ABF100 1TB                               | 16        | 0.47%   |
| Toshiba MQ01ABF050 500GB                             | 16        | 0.47%   |
| SanDisk NVMe SSD Drive 512GB                         | 16        | 0.47%   |
| Samsung SSD 860 EVO 250GB                            | 16        | 0.47%   |
| Samsung NVMe SSD Drive 500GB                         | 16        | 0.47%   |
| Samsung SSD 850 EVO 500GB                            | 15        | 0.44%   |
| Kingston SA400S37480G 480GB SSD                      | 15        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 14        | 0.42%   |
| Unknown MMC Card  16GB                               | 13        | 0.39%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 13        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                     | 13        | 0.39%   |
| HGST HTS545050A7E680 500GB                           | 13        | 0.39%   |
| Samsung SSD 860 EVO 1TB                              | 12        | 0.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 12        | 0.36%   |
| Intel NVMe SSD Drive 512GB                           | 12        | 0.36%   |
| Apple SSD SM0128G 121GB                              | 12        | 0.36%   |
| Seagate ST1000DM010-2EP102 1TB                       | 11        | 0.33%   |
| Samsung NVMe SSD Drive 1TB                           | 11        | 0.33%   |
| Crucial CT480BX500SSD1 480GB                         | 11        | 0.33%   |
| Apple HDD HTS541010A9E662 1TB                        | 11        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 345       | 444    | 31.45%  |
| WDC                 | 299       | 393    | 27.26%  |
| Toshiba             | 167       | 207    | 15.22%  |
| Hitachi             | 92        | 101    | 8.39%   |
| HGST                | 65        | 78     | 5.93%   |
| Samsung Electronics | 37        | 43     | 3.37%   |
| Apple               | 34        | 37     | 3.1%    |
| Fujitsu             | 16        | 18     | 1.46%   |
| Unknown             | 7         | 8      | 0.64%   |
| JMicron Technology  | 7         | 7      | 0.64%   |
| Maxtor              | 5         | 5      | 0.46%   |
| TO Exter            | 4         | 4      | 0.36%   |
| Hewlett-Packard     | 4         | 7      | 0.36%   |
| ASMT                | 4         | 4      | 0.36%   |
| SABRENT             | 3         | 3      | 0.27%   |
| StoreJet            | 1         | 1      | 0.09%   |
| Shenzhen            | 1         | 1      | 0.09%   |
| NETAPP              | 1         | 1      | 0.09%   |
| Generic-            | 1         | 1      | 0.09%   |
| FC-1307             | 1         | 1      | 0.09%   |
| External            | 1         | 1      | 0.09%   |
| Ext Hard            | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 220       | 290    | 17.81%  |
| Kingston            | 166       | 203    | 13.44%  |
| Crucial             | 127       | 155    | 10.28%  |
| SanDisk             | 117       | 137    | 9.47%   |
| Apple               | 78        | 86     | 6.32%   |
| WDC                 | 69        | 85     | 5.59%   |
| A-DATA Technology   | 42        | 48     | 3.4%    |
| China               | 40        | 51     | 3.24%   |
| Intel               | 30        | 37     | 2.43%   |
| PNY                 | 24        | 32     | 1.94%   |
| Micron Technology   | 19        | 21     | 1.54%   |
| Toshiba             | 18        | 22     | 1.46%   |
| LITEON              | 17        | 17     | 1.38%   |
| Transcend           | 16        | 19     | 1.3%    |
| Intenso             | 16        | 19     | 1.3%    |
| SPCC                | 14        | 14     | 1.13%   |
| Patriot             | 14        | 17     | 1.13%   |
| SK hynix            | 13        | 13     | 1.05%   |
| OCZ                 | 11        | 17     | 0.89%   |
| Apacer              | 10        | 12     | 0.81%   |
| Team                | 9         | 12     | 0.73%   |
| Unknown             | 9         | 9      | 0.73%   |
| Corsair             | 8         | 8      | 0.65%   |
| Netac               | 7         | 7      | 0.57%   |
| GOODRAM             | 7         | 10     | 0.57%   |
| Lexar               | 6         | 6      | 0.49%   |
| KingDian            | 6         | 9      | 0.49%   |
| Hewlett-Packard     | 6         | 8      | 0.49%   |
| Gigabyte Technology | 6         | 6      | 0.49%   |
| NGFF                | 5         | 6      | 0.4%    |
| LITEONIT            | 5         | 5      | 0.4%    |
| HUSKY               | 5         | 10     | 0.4%    |
| Plextor             | 4         | 6      | 0.32%   |
| OWC                 | 4         | 4      | 0.32%   |
| KingSpec            | 4         | 5      | 0.32%   |
| Emtec               | 4         | 5      | 0.32%   |
| Seagate             | 3         | 5      | 0.24%   |
| FORESEE             | 3         | 3      | 0.24%   |
| BIWIN               | 3         | 3      | 0.24%   |
| XrayDisk            | 2         | 4      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1115      | 1503   | 38.28%  |
| HDD     | 973       | 1367   | 33.4%   |
| NVMe    | 617       | 835    | 21.18%  |
| MMC     | 126       | 157    | 4.33%   |
| Unknown | 82        | 113    | 2.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1795      | 2834   | 67.71%  |
| NVMe | 617       | 830    | 23.27%  |
| MMC  | 126       | 157    | 4.75%   |
| SAS  | 113       | 154    | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1392      | 1941   | 66.73%  |
| 0.51-1.0   | 534       | 710    | 25.6%   |
| 1.01-2.0   | 100       | 131    | 4.79%   |
| 2.01-3.0   | 26        | 46     | 1.25%   |
| 3.01-4.0   | 20        | 23     | 0.96%   |
| 4.01-10.0  | 13        | 18     | 0.62%   |
| 10.01-20.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 917       | 38.68%  |
| 251-500        | 632       | 26.66%  |
| 501-1000       | 343       | 14.47%  |
| 51-100         | 173       | 7.3%    |
| 1001-2000      | 113       | 4.77%   |
| 21-50          | 89        | 3.75%   |
| More than 3000 | 38        | 1.6%    |
| 2001-3000      | 33        | 1.39%   |
| 1-20           | 27        | 1.14%   |
| Unknown        | 6         | 0.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1089      | 43.89%  |
| 21-50          | 625       | 25.19%  |
| 51-100         | 270       | 10.88%  |
| 101-250        | 244       | 9.83%   |
| 251-500        | 115       | 4.64%   |
| 501-1000       | 73        | 2.94%   |
| 1001-2000      | 39        | 1.57%   |
| 2001-3000      | 11        | 0.44%   |
| More than 3000 | 9         | 0.36%   |
| Unknown        | 6         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 1      | 1.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 1      | 1.59%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 1      | 1.59%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 1.59%   |
| WDC WD5000AAKX-221CA1 500GB         | 1         | 1      | 1.59%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 1.59%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 1      | 1.59%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 1      | 1.59%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 1.59%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1         | 1      | 1.59%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 1      | 1.59%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.59%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 1.59%   |
| Toshiba KBG30ZPZ128G 128GB          | 1         | 1      | 1.59%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.59%   |
| Seagate ST500LM030-2E717D 500GB     | 1         | 1      | 1.59%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.59%   |
| Seagate ST3500414CS 500GB           | 1         | 2      | 1.59%   |
| Seagate ST3500312CS 500GB           | 1         | 1      | 1.59%   |
| Seagate ST3320613AS 320GB           | 1         | 1      | 1.59%   |
| Seagate ST3250820AS 250GB           | 1         | 1      | 1.59%   |
| Seagate ST3250312AS 250GB           | 1         | 1      | 1.59%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 1.59%   |
| Seagate ST3160813AS 160GB           | 1         | 1      | 1.59%   |
| Seagate ST3160318AS 160GB           | 1         | 1      | 1.59%   |
| Seagate ST2000DM006-2DM164 2TB      | 1         | 1      | 1.59%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 1         | 1      | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 1.59%   |
| SanDisk SSD PLUS 240GB              | 1         | 1      | 1.59%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 1.59%   |
| SanDisk SD7SB3Q256G1002 256GB SSD   | 1         | 1      | 1.59%   |
| Samsung Electronics HM320II 320GB   | 1         | 1      | 1.59%   |
| Samsung Electronics HD322GJ 320GB   | 1         | 1      | 1.59%   |
| Samsung Electronics HD204UI 2TB     | 1         | 1      | 1.59%   |
| Samsung Electronics HD160JJ 160GB   | 1         | 1      | 1.59%   |
| OCZ VECTOR150 240GB SSD             | 1         | 1      | 1.59%   |
| LS 128GB M300                       | 1         | 1      | 1.59%   |
| Kingston SV300S37A240G 240GB SSD    | 1         | 1      | 1.59%   |
| Kingston SUV400S37480G 480GB SSD    | 1         | 1      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 23.81%  |
| WDC                 | 11        | 11     | 17.46%  |
| Hitachi             | 5         | 5      | 7.94%   |
| HGST                | 5         | 5      | 7.94%   |
| Samsung Electronics | 4         | 4      | 6.35%   |
| Kingston            | 4         | 4      | 6.35%   |
| Toshiba             | 3         | 3      | 4.76%   |
| SanDisk             | 3         | 3      | 4.76%   |
| Crucial             | 3         | 3      | 4.76%   |
| Apple               | 3         | 3      | 4.76%   |
| OCZ                 | 1         | 1      | 1.59%   |
| LS                  | 1         | 1      | 1.59%   |
| Intel               | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 2      | 1.59%   |
| China               | 1         | 1      | 1.59%   |
| BIWIN               | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 34.88%  |
| WDC                 | 9         | 9      | 20.93%  |
| Hitachi             | 5         | 5      | 11.63%  |
| HGST                | 5         | 5      | 11.63%  |
| Samsung Electronics | 4         | 4      | 9.3%    |
| Toshiba             | 2         | 2      | 4.65%   |
| Apple               | 2         | 2      | 4.65%   |
| Fujitsu             | 1         | 2      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 45     | 66.67%  |
| SSD  | 18        | 18     | 30%     |
| NVMe | 2         | 2      | 3.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-75Z10T1 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2030      | 3486   | 85.19%  |
| Works    | 293       | 423    | 12.3%   |
| Malfunc  | 59        | 65     | 2.48%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1622      | 58.9%   |
| AMD                            | 313       | 11.37%  |
| Samsung Electronics            | 234       | 8.5%    |
| Sandisk                        | 106       | 3.85%   |
| Nvidia                         | 78        | 2.83%   |
| SK hynix                       | 53        | 1.92%   |
| Phison Electronics             | 35        | 1.27%   |
| Kingston Technology Company    | 33        | 1.2%    |
| Toshiba America Info Systems   | 31        | 1.13%   |
| KIOXIA                         | 29        | 1.05%   |
| Marvell Technology Group       | 27        | 0.98%   |
| ASMedia Technology             | 25        | 0.91%   |
| Silicon Motion                 | 23        | 0.84%   |
| Micron/Crucial Technology      | 23        | 0.84%   |
| Micron Technology              | 23        | 0.84%   |
| ADATA Technology               | 15        | 0.54%   |
| JMicron Technology             | 14        | 0.51%   |
| Realtek Semiconductor          | 11        | 0.4%    |
| Union Memory (Shenzhen)        | 9         | 0.33%   |
| MAXIO Technology (Hangzhou)    | 9         | 0.33%   |
| Lite-On Technology             | 6         | 0.22%   |
| Shenzhen Longsys Electronics   | 5         | 0.18%   |
| Yangtze Memory Technologies    | 4         | 0.15%   |
| Solid State Storage Technology | 3         | 0.11%   |
| Seagate Technology             | 3         | 0.11%   |
| LSI Logic / Symbios Logic      | 3         | 0.11%   |
| Broadcom / LSI                 | 3         | 0.11%   |
| Apple                          | 3         | 0.11%   |
| VIA Technologies               | 2         | 0.07%   |
| Silicon Image                  | 2         | 0.07%   |
| INNOGRIT                       | 2         | 0.07%   |
| Hewlett-Packard                | 2         | 0.07%   |
| Biwin Storage Technology       | 2         | 0.07%   |
| Solidigm                       | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 238       | 7.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 154       | 5.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 149       | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 119       | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 99        | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 84        | 2.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 76        | 2.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 68        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 60        | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 54        | 1.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 51        | 1.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 50        | 1.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 49        | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 43        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 41        | 1.34%   |
| Nvidia MCP79 AHCI Controller                                                            | 40        | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 39        | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 37        | 1.21%   |
| AMD 400 Series Chipset SATA Controller                                                  | 37        | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 36        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 36        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 35        | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 34        | 1.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 34        | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 33        | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 33        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 30        | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 27        | 0.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 26        | 0.85%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 24        | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 24        | 0.78%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 24        | 0.78%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 23        | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23        | 0.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 23        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 22        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 22        | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 21        | 0.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 19        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1760      | 62.97%  |
| NVMe | 616       | 22.04%  |
| IDE  | 223       | 7.98%   |
| RAID | 191       | 6.83%   |
| SAS  | 3         | 0.11%   |
| SCSI | 2         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1896      | 82.4%   |
| AMD    | 404       | 17.56%  |
| ARM    | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 1.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 33        | 1.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 1.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 23        | 1%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 23        | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 21        | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 16        | 0.7%    |
| Intel Core i5-2415M CPU @ 2.30GHz             | 16        | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 0.65%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 15        | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 15        | 0.65%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 15        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 14        | 0.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 14        | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 0.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.56%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 0.56%   |
| AMD Ryzen 5 3600 6-Core Processor             | 13        | 0.56%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 12        | 0.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 11        | 0.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 11        | 0.48%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 11        | 0.48%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 11        | 0.48%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 0.48%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 11        | 0.48%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 11        | 0.48%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 10        | 0.43%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 10        | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 9         | 0.39%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.39%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 9         | 0.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 608       | 26.41%  |
| Intel Core i7           | 438       | 19.03%  |
| Intel Core i3           | 202       | 8.77%   |
| Other                   | 148       | 6.43%   |
| Intel Core 2 Duo        | 144       | 6.26%   |
| Intel Celeron           | 132       | 5.73%   |
| AMD Ryzen 5             | 106       | 4.6%    |
| AMD Ryzen 7             | 68        | 2.95%   |
| Intel Pentium           | 53        | 2.3%    |
| Intel Xeon              | 49        | 2.13%   |
| Intel Pentium Dual-Core | 30        | 1.3%    |
| AMD Ryzen 3             | 26        | 1.13%   |
| Intel Atom              | 25        | 1.09%   |
| AMD A8                  | 21        | 0.91%   |
| AMD A6                  | 19        | 0.83%   |
| AMD A4                  | 19        | 0.83%   |
| AMD Ryzen 9             | 18        | 0.78%   |
| AMD FX                  | 18        | 0.78%   |
| Intel Pentium Silver    | 16        | 0.7%    |
| Intel Core 2 Quad       | 16        | 0.7%    |
| AMD A10                 | 11        | 0.48%   |
| AMD Phenom II X4        | 10        | 0.43%   |
| Intel Core i9           | 9         | 0.39%   |
| Intel Core 2            | 9         | 0.39%   |
| AMD A12                 | 8         | 0.35%   |
| Intel Core m3           | 7         | 0.3%    |
| AMD Ryzen 5 PRO         | 7         | 0.3%    |
| AMD Athlon              | 7         | 0.3%    |
| Intel Pentium Dual      | 6         | 0.26%   |
| AMD E1                  | 6         | 0.26%   |
| Intel Genuine           | 4         | 0.17%   |
| Intel Celeron Dual-Core | 4         | 0.17%   |
| AMD Ryzen 7 PRO         | 4         | 0.17%   |
| AMD E                   | 4         | 0.17%   |
| AMD Athlon II X4        | 4         | 0.17%   |
| AMD Athlon II X2        | 4         | 0.17%   |
| Intel Core m5           | 3         | 0.13%   |
| AMD V140                | 3         | 0.13%   |
| AMD E2                  | 3         | 0.13%   |
| Intel Pentium Gold      | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1118      | 48.52%  |
| 4      | 826       | 35.85%  |
| 6      | 155       | 6.73%   |
| 8      | 119       | 5.16%   |
| 1      | 27        | 1.17%   |
| 12     | 23        | 1%      |
| 10     | 11        | 0.48%   |
| 16     | 8         | 0.35%   |
| 3      | 8         | 0.35%   |
| 14     | 4         | 0.17%   |
| 5      | 2         | 0.09%   |
| 28     | 1         | 0.04%   |
| 20     | 1         | 0.04%   |
| 18     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2289      | 99.48%  |
| 2      | 12        | 0.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1548      | 67.16%  |
| 1      | 757       | 32.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2290      | 99.48%  |
| Unknown        | 11        | 0.48%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 980       | 41.65%  |
| 0x206a7    | 141       | 5.99%   |
| 0x306a9    | 106       | 4.5%    |
| 0x306c3    | 71        | 3.02%   |
| 0x1067a    | 63        | 2.68%   |
| 0x40651    | 52        | 2.21%   |
| 0x806c1    | 44        | 1.87%   |
| 0x806e9    | 43        | 1.83%   |
| 0x406e3    | 43        | 1.83%   |
| 0x806ea    | 40        | 1.7%    |
| 0x806ec    | 39        | 1.66%   |
| 0x306d4    | 34        | 1.44%   |
| 0x20655    | 31        | 1.32%   |
| 0x906ea    | 28        | 1.19%   |
| 0x906e9    | 28        | 1.19%   |
| 0x08108109 | 25        | 1.06%   |
| 0x10676    | 23        | 0.98%   |
| 0x20652    | 22        | 0.93%   |
| 0x30678    | 21        | 0.89%   |
| 0x706a1    | 19        | 0.81%   |
| 0x506e3    | 19        | 0.81%   |
| 0x706e5    | 18        | 0.76%   |
| 0x08701021 | 18        | 0.76%   |
| 0x806eb    | 15        | 0.64%   |
| 0x06006705 | 15        | 0.64%   |
| 0x706a8    | 14        | 0.59%   |
| 0x406c3    | 14        | 0.59%   |
| 0x106e5    | 14        | 0.59%   |
| 0x506c9    | 13        | 0.55%   |
| 0x08600106 | 13        | 0.55%   |
| 0xa0652    | 12        | 0.51%   |
| 0x6fb      | 12        | 0.51%   |
| 0x906ed    | 11        | 0.47%   |
| 0x406c4    | 11        | 0.47%   |
| 0x08608103 | 11        | 0.47%   |
| 0x0800820d | 11        | 0.47%   |
| 0x06001119 | 11        | 0.47%   |
| 0x010000c8 | 11        | 0.47%   |
| 0x40661    | 10        | 0.42%   |
| 0x0a50000c | 10        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 341       | 14.81%  |
| Haswell          | 235       | 10.21%  |
| SandyBridge      | 233       | 10.12%  |
| IvyBridge        | 198       | 8.6%    |
| Penryn           | 164       | 7.12%   |
| Skylake          | 119       | 5.17%   |
| Westmere         | 96        | 4.17%   |
| TigerLake        | 83        | 3.61%   |
| Unknown          | 75        | 3.26%   |
| Broadwell        | 70        | 3.04%   |
| Zen+             | 68        | 2.95%   |
| Silvermont       | 66        | 2.87%   |
| Zen 2            | 61        | 2.65%   |
| Goldmont plus    | 61        | 2.65%   |
| Core             | 56        | 2.43%   |
| Excavator        | 45        | 1.95%   |
| IceLake          | 39        | 1.69%   |
| Zen              | 38        | 1.65%   |
| Zen 3            | 37        | 1.61%   |
| CometLake        | 33        | 1.43%   |
| K10              | 30        | 1.3%    |
| Piledriver       | 26        | 1.13%   |
| Nehalem          | 24        | 1.04%   |
| Puma             | 19        | 0.83%   |
| Goldmont         | 17        | 0.74%   |
| Bobcat           | 13        | 0.56%   |
| Steamroller      | 10        | 0.43%   |
| Jaguar           | 9         | 0.39%   |
| Alderlake Hybrid | 9         | 0.39%   |
| Bonnell          | 6         | 0.26%   |
| Tremont          | 5         | 0.22%   |
| K10 Llano        | 5         | 0.22%   |
| Bulldozer        | 5         | 0.22%   |
| NetBurst         | 3         | 0.13%   |
| K8 Hammer        | 2         | 0.09%   |
| K8 & K10 hybrid  | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1484      | 55%     |
| Nvidia                     | 611       | 22.65%  |
| AMD                        | 596       | 22.09%  |
| Matrox Electronics Systems | 2         | 0.07%   |
| ATI Technologies           | 2         | 0.07%   |
| Huawei Technologies        | 1         | 0.04%   |
| Conexant Systems           | 1         | 0.04%   |
| ASPEED Technology          | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 184       | 6.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 134       | 4.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 90        | 3.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 68        | 2.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 67        | 2.41%   |
| Intel HD Graphics 620                                                                    | 65        | 2.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 63        | 2.27%   |
| Intel UHD Graphics 620                                                                   | 53        | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 50        | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 46        | 1.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 45        | 1.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 45        | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 40        | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 37        | 1.33%   |
| Intel HD Graphics 5500                                                                   | 37        | 1.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 37        | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 1.19%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 33        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 32        | 1.15%   |
| Nvidia C79 [GeForce 9400M]                                                               | 28        | 1.01%   |
| Intel HD Graphics 630                                                                    | 28        | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 0.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 25        | 0.9%    |
| AMD Lucienne                                                                             | 25        | 0.9%    |
| Intel HD Graphics 6000                                                                   | 23        | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 23        | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 23        | 0.83%   |
| Intel HD Graphics 530                                                                    | 22        | 0.79%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 21        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 20        | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 20        | 0.72%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 20        | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 19        | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 18        | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 17        | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 0.58%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 0.54%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 15        | 0.54%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 15        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 1113      | 48.22%  |
| 1 x AMD                        | 460       | 19.93%  |
| 1 x Nvidia                     | 325       | 14.08%  |
| Intel + Nvidia                 | 253       | 10.96%  |
| Intel + AMD                    | 81        | 3.51%   |
| 2 x AMD                        | 34        | 1.47%   |
| AMD + Nvidia                   | 18        | 0.78%   |
| 2 x Nvidia                     | 12        | 0.52%   |
| Other                          | 5         | 0.22%   |
| 1 x Matrox                     | 2         | 0.09%   |
| Intel + 2 x AMD                | 2         | 0.09%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.04%   |
| Nvidia + ASPEED                | 1         | 0.04%   |
| 1 x Huawei Technologies        | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2037      | 87.95%  |
| Proprietary | 235       | 10.15%  |
| Unknown     | 44        | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1586      | 67.81%  |
| 1.01-2.0   | 230       | 9.83%   |
| 0.01-0.5   | 182       | 7.78%   |
| 0.51-1.0   | 137       | 5.86%   |
| 3.01-4.0   | 101       | 4.32%   |
| 7.01-8.0   | 53        | 2.27%   |
| 5.01-6.0   | 29        | 1.24%   |
| 8.01-16.0  | 12        | 0.51%   |
| 2.01-3.0   | 8         | 0.34%   |
| 16.01-24.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 292       | 11.84%  |
| Apple                   | 278       | 11.27%  |
| Samsung Electronics     | 259       | 10.5%   |
| BOE                     | 234       | 9.49%   |
| LG Display              | 229       | 9.29%   |
| Chimei Innolux          | 214       | 8.68%   |
| Dell                    | 103       | 4.18%   |
| Goldstar                | 100       | 4.06%   |
| Hewlett-Packard         | 76        | 3.08%   |
| Acer                    | 61        | 2.47%   |
| Sharp                   | 51        | 2.07%   |
| AOC                     | 51        | 2.07%   |
| Lenovo                  | 47        | 1.91%   |
| Chi Mei Optoelectronics | 38        | 1.54%   |
| Philips                 | 36        | 1.46%   |
| BenQ                    | 36        | 1.46%   |
| Ancor Communications    | 28        | 1.14%   |
| PANDA                   | 23        | 0.93%   |
| ViewSonic               | 18        | 0.73%   |
| LG Electronics          | 17        | 0.69%   |
| InfoVision              | 15        | 0.61%   |
| Sony                    | 13        | 0.53%   |
| Vizio                   | 12        | 0.49%   |
| Panasonic               | 12        | 0.49%   |
| Unknown                 | 11        | 0.45%   |
| Fujitsu Siemens         | 10        | 0.41%   |
| ASUSTek Computer        | 10        | 0.41%   |
| CSO                     | 8         | 0.32%   |
| Toshiba                 | 7         | 0.28%   |
| NEC Computers           | 7         | 0.28%   |
| HKC                     | 7         | 0.28%   |
| HannStar                | 7         | 0.28%   |
| MSI                     | 6         | 0.24%   |
| Eizo                    | 6         | 0.24%   |
| CPT                     | 6         | 0.24%   |
| Mi                      | 5         | 0.2%    |
| LG Philips              | 5         | 0.2%    |
| Iiyama                  | 5         | 0.2%    |
| ___                     | 4         | 0.16%   |
| Vestel Elektronik       | 3         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 18        | 0.71%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 17        | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 14        | 0.55%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 14        | 0.55%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 14        | 0.55%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 14        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 13        | 0.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 12        | 0.47%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                     | 12        | 0.47%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 10        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 10        | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 10        | 0.4%    |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                 | 10        | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 9         | 0.36%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 9         | 0.36%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch               | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 8         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 8         | 0.32%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 8         | 0.32%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 8         | 0.32%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 8         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 7         | 0.28%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch          | 7         | 0.28%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 7         | 0.28%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 7         | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 7         | 0.28%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 7         | 0.28%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 7         | 0.28%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                     | 7         | 0.28%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                | 7         | 0.28%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 6         | 0.24%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 6         | 0.24%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 6         | 0.24%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 6         | 0.24%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch        | 6         | 0.24%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch               | 6         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 939       | 39.42%  |
| 1366x768 (WXGA)    | 535       | 22.46%  |
| 3840x2160 (4K)     | 136       | 5.71%   |
| 1280x800 (WXGA)    | 115       | 4.83%   |
| 1600x900 (HD+)     | 109       | 4.58%   |
| 2560x1440 (QHD)    | 98        | 4.11%   |
| 1440x900 (WXGA+)   | 82        | 3.44%   |
| 1680x1050 (WSXGA+) | 69        | 2.9%    |
| 1920x1200 (WUXGA)  | 50        | 2.1%    |
| 1280x1024 (SXGA)   | 37        | 1.55%   |
| 2880x1800          | 30        | 1.26%   |
| 2560x1600          | 21        | 0.88%   |
| 2560x1080          | 18        | 0.76%   |
| Unknown            | 18        | 0.76%   |
| 3440x1440          | 14        | 0.59%   |
| 1360x768           | 14        | 0.59%   |
| 3840x1080          | 10        | 0.42%   |
| 2160x1440          | 8         | 0.34%   |
| 3000x2000          | 7         | 0.29%   |
| 3840x2400          | 6         | 0.25%   |
| 1024x600           | 6         | 0.25%   |
| 3200x1800 (QHD+)   | 5         | 0.21%   |
| 1920x540           | 5         | 0.21%   |
| 1600x1200          | 5         | 0.21%   |
| 2880x1920          | 4         | 0.17%   |
| 1920x1280          | 4         | 0.17%   |
| 5120x1440          | 3         | 0.13%   |
| 3840x1200          | 2         | 0.08%   |
| 3072x1920          | 2         | 0.08%   |
| 2736x1824          | 2         | 0.08%   |
| 2288x1287          | 2         | 0.08%   |
| 2048x1152          | 2         | 0.08%   |
| 1680x945           | 2         | 0.08%   |
| 1400x1050          | 2         | 0.08%   |
| 1280x720 (HD)      | 2         | 0.08%   |
| 7680x2160          | 1         | 0.04%   |
| 7680x1600          | 1         | 0.04%   |
| 5760x2160          | 1         | 0.04%   |
| 5760x1080          | 1         | 0.04%   |
| 4480x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 636       | 25.75%  |
| 13      | 382       | 15.47%  |
| 14      | 215       | 8.7%    |
| 27      | 152       | 6.15%   |
| 24      | 128       | 5.18%   |
| 17      | 120       | 4.86%   |
| 21      | 119       | 4.82%   |
| Unknown | 108       | 4.37%   |
| 23      | 106       | 4.29%   |
| 31      | 56        | 2.27%   |
| 11      | 52        | 2.11%   |
| 19      | 44        | 1.78%   |
| 20      | 43        | 1.74%   |
| 12      | 41        | 1.66%   |
| 22      | 35        | 1.42%   |
| 18      | 34        | 1.38%   |
| 34      | 25        | 1.01%   |
| 84      | 19        | 0.77%   |
| 32      | 17        | 0.69%   |
| 16      | 16        | 0.65%   |
| 72      | 13        | 0.53%   |
| 54      | 13        | 0.53%   |
| 10      | 12        | 0.49%   |
| 26      | 9         | 0.36%   |
| 40      | 8         | 0.32%   |
| 25      | 8         | 0.32%   |
| 36      | 5         | 0.2%    |
| 29      | 5         | 0.2%    |
| 49      | 4         | 0.16%   |
| 48      | 4         | 0.16%   |
| 43      | 4         | 0.16%   |
| 42      | 4         | 0.16%   |
| 33      | 4         | 0.16%   |
| 65      | 3         | 0.12%   |
| 60      | 3         | 0.12%   |
| 28      | 3         | 0.12%   |
| 64      | 2         | 0.08%   |
| 55      | 2         | 0.08%   |
| 52      | 2         | 0.08%   |
| 39      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 999       | 41.04%  |
| 501-600        | 368       | 15.12%  |
| 201-300        | 349       | 14.34%  |
| 401-500        | 250       | 10.27%  |
| 351-400        | 140       | 5.75%   |
| Unknown        | 108       | 4.44%   |
| 601-700        | 76        | 3.12%   |
| 701-800        | 50        | 2.05%   |
| 1001-1500      | 36        | 1.48%   |
| 1501-2000      | 34        | 1.4%    |
| 801-900        | 16        | 0.66%   |
| 901-1000       | 7         | 0.29%   |
| More than 2000 | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1678      | 74.18%  |
| 16/10   | 366       | 16.18%  |
| Unknown | 97        | 4.29%   |
| 3/2     | 37        | 1.64%   |
| 5/4     | 33        | 1.46%   |
| 21/9    | 31        | 1.37%   |
| 4/3     | 8         | 0.35%   |
| 32/9    | 4         | 0.18%   |
| 6/5     | 2         | 0.09%   |
| 3.73    | 1         | 0.04%   |
| 3.40    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 634       | 25.88%  |
| 81-90          | 451       | 18.41%  |
| 201-250        | 295       | 12.04%  |
| 301-350        | 157       | 6.41%   |
| 71-80          | 143       | 5.84%   |
| 151-200        | 120       | 4.9%    |
| 351-500        | 108       | 4.41%   |
| Unknown        | 108       | 4.41%   |
| 121-130        | 80        | 3.27%   |
| More than 1000 | 64        | 2.61%   |
| 251-300        | 59        | 2.41%   |
| 51-60          | 53        | 2.16%   |
| 141-150        | 49        | 2%      |
| 61-70          | 40        | 1.63%   |
| 501-1000       | 33        | 1.35%   |
| 131-140        | 24        | 0.98%   |
| 111-120        | 15        | 0.61%   |
| 41-50          | 12        | 0.49%   |
| 91-100         | 5         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 777       | 32.43%  |
| 121-160       | 651       | 27.17%  |
| 51-100        | 599       | 25%     |
| 161-240       | 155       | 6.47%   |
| Unknown       | 108       | 4.51%   |
| 1-50          | 55        | 2.3%    |
| More than 240 | 51        | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1994      | 85.29%  |
| 2     | 279       | 11.93%  |
| 0     | 36        | 1.54%   |
| 3     | 28        | 1.2%    |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1128      | 31.91%  |
| Intel                             | 950       | 26.87%  |
| Broadcom                          | 426       | 12.05%  |
| Qualcomm Atheros                  | 406       | 11.49%  |
| Broadcom Limited                  | 93        | 2.63%   |
| Marvell Technology Group          | 67        | 1.9%    |
| Nvidia                            | 57        | 1.61%   |
| TP-Link                           | 49        | 1.39%   |
| Ralink Technology                 | 42        | 1.19%   |
| MediaTek                          | 37        | 1.05%   |
| Ralink                            | 30        | 0.85%   |
| Samsung Electronics               | 27        | 0.76%   |
| Xiaomi                            | 22        | 0.62%   |
| ASIX Electronics                  | 20        | 0.57%   |
| Huawei Technologies               | 13        | 0.37%   |
| Sierra Wireless                   | 12        | 0.34%   |
| Qualcomm Atheros Communications   | 11        | 0.31%   |
| D-Link                            | 11        | 0.31%   |
| Qualcomm                          | 8         | 0.23%   |
| OPPO Electronics                  | 8         | 0.23%   |
| Hewlett-Packard                   | 8         | 0.23%   |
| Ericsson Business Mobile Networks | 8         | 0.23%   |
| D-Link System                     | 8         | 0.23%   |
| Google                            | 6         | 0.17%   |
| Dell                              | 6         | 0.17%   |
| Apple                             | 6         | 0.17%   |
| NetGear                           | 5         | 0.14%   |
| Microsoft                         | 5         | 0.14%   |
| Linksys                           | 5         | 0.14%   |
| ASUSTek Computer                  | 5         | 0.14%   |
| Lenovo                            | 4         | 0.11%   |
| Edimax Technology                 | 4         | 0.11%   |
| JMicron Technology                | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| TRENDnet                          | 2         | 0.06%   |
| Motorola PCS                      | 2         | 0.06%   |
| Mercucys                          | 2         | 0.06%   |
| LG Electronics                    | 2         | 0.06%   |
| ICS Advent                        | 2         | 0.06%   |
| Fibocom                           | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 718       | 17.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 168       | 4.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 79        | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 75        | 1.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 74        | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 66        | 1.58%   |
| Intel Wi-Fi 6 AX201                                                    | 64        | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 63        | 1.51%   |
| Intel Wireless 8260                                                    | 59        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 56        | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 55        | 1.32%   |
| Intel Wireless 8265 / 8275                                             | 54        | 1.29%   |
| Intel Wi-Fi 6 AX200                                                    | 54        | 1.29%   |
| Intel Wireless 7265                                                    | 50        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 48        | 1.15%   |
| Intel Wireless 7260                                                    | 48        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 47        | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 45        | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 44        | 1.05%   |
| Nvidia MCP79 Ethernet                                                  | 41        | 0.98%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 41        | 0.98%   |
| Intel Wireless 3165                                                    | 39        | 0.93%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 38        | 0.91%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 35        | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 34        | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 33        | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 32        | 0.77%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 31        | 0.74%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 31        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                          | 31        | 0.74%   |
| Intel Ethernet Connection I217-LM                                      | 30        | 0.72%   |
| Broadcom BCM4321 802.11a/b/g/n                                         | 30        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 30        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 29        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 0.65%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 27        | 0.65%   |
| Intel I211 Gigabit Network Connection                                  | 27        | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 26        | 0.62%   |
| Ralink MT7601U Wireless Adapter                                        | 24        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 23        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 753       | 35.57%  |
| Realtek Semiconductor           | 353       | 16.67%  |
| Broadcom                        | 351       | 16.58%  |
| Qualcomm Atheros                | 337       | 15.92%  |
| Broadcom Limited                | 79        | 3.73%   |
| TP-Link                         | 48        | 2.27%   |
| Ralink Technology               | 42        | 1.98%   |
| Ralink                          | 30        | 1.42%   |
| MediaTek                        | 26        | 1.23%   |
| Marvell Technology Group        | 13        | 0.61%   |
| Sierra Wireless                 | 12        | 0.57%   |
| Qualcomm Atheros Communications | 11        | 0.52%   |
| D-Link                          | 9         | 0.43%   |
| D-Link System                   | 7         | 0.33%   |
| ASUSTek Computer                | 5         | 0.24%   |
| Qualcomm                        | 4         | 0.19%   |
| NetGear                         | 4         | 0.19%   |
| Microsoft                       | 4         | 0.19%   |
| Linksys                         | 4         | 0.19%   |
| Edimax Technology               | 4         | 0.19%   |
| Dell                            | 3         | 0.14%   |
| TRENDnet                        | 2         | 0.09%   |
| Mercucys                        | 2         | 0.09%   |
| Fibocom                         | 2         | 0.09%   |
| Belkin Components               | 2         | 0.09%   |
| ZyXEL Communications            | 1         | 0.05%   |
| ZyDAS                           | 1         | 0.05%   |
| Sitecom Europe                  | 1         | 0.05%   |
| LG Electronics                  | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| BUFFALO                         | 1         | 0.05%   |
| AVM                             | 1         | 0.05%   |
| AirTies Wireless Networks       | 1         | 0.05%   |
| Accton Technology               | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4331 802.11a/b/g/n                                       | 74        | 3.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 66        | 3.1%    |
| Intel Wi-Fi 6 AX201                                                  | 64        | 3%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 63        | 2.96%   |
| Intel Wireless 8260                                                  | 59        | 2.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 56        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 55        | 2.58%   |
| Intel Wireless 8265 / 8275                                           | 54        | 2.53%   |
| Intel Wi-Fi 6 AX200                                                  | 54        | 2.53%   |
| Intel Wireless 7265                                                  | 50        | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 48        | 2.25%   |
| Intel Wireless 7260                                                  | 48        | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 47        | 2.21%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 45        | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 44        | 2.06%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 41        | 1.92%   |
| Intel Wireless 3165                                                  | 39        | 1.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 35        | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 34        | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 33        | 1.55%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 31        | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                        | 31        | 1.45%   |
| Broadcom BCM4321 802.11a/b/g/n                                       | 30        | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 30        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 29        | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 26        | 1.22%   |
| Ralink MT7601U Wireless Adapter                                      | 24        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 23        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 23        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 23        | 1.08%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 21        | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 20        | 0.94%   |
| Intel Wireless 3160                                                  | 20        | 0.94%   |
| Realtek 802.11ac NIC                                                 | 19        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 19        | 0.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 19        | 0.89%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 19        | 0.89%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 18        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 18        | 0.84%   |
| Intel Centrino Advanced-N 6235                                       | 18        | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 965       | 48.57%  |
| Intel                             | 449       | 22.6%   |
| Broadcom                          | 203       | 10.22%  |
| Qualcomm Atheros                  | 109       | 5.49%   |
| Nvidia                            | 57        | 2.87%   |
| Marvell Technology Group          | 54        | 2.72%   |
| Xiaomi                            | 22        | 1.11%   |
| ASIX Electronics                  | 20        | 1.01%   |
| Samsung Electronics               | 15        | 0.75%   |
| Broadcom Limited                  | 15        | 0.75%   |
| MediaTek                          | 11        | 0.55%   |
| Huawei Technologies               | 10        | 0.5%    |
| OPPO Electronics                  | 8         | 0.4%    |
| Google                            | 6         | 0.3%    |
| Apple                             | 6         | 0.3%    |
| Qualcomm                          | 4         | 0.2%    |
| Lenovo                            | 4         | 0.2%    |
| JMicron Technology                | 3         | 0.15%   |
| Motorola PCS                      | 2         | 0.1%    |
| ICS Advent                        | 2         | 0.1%    |
| Hewlett-Packard                   | 2         | 0.1%    |
| D-Link                            | 2         | 0.1%    |
| Attansic Technology               | 2         | 0.1%    |
| Aquantia                          | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |
| vivo                              | 1         | 0.05%   |
| VIA Technologies                  | 1         | 0.05%   |
| TP-Link                           | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus | 1         | 0.05%   |
| NetGear                           | 1         | 0.05%   |
| Microsoft                         | 1         | 0.05%   |
| LSI                               | 1         | 0.05%   |
| Linksys                           | 1         | 0.05%   |
| LG Electronics                    | 1         | 0.05%   |
| HMD Global                        | 1         | 0.05%   |
| DisplayLink                       | 1         | 0.05%   |
| D-Link System                     | 1         | 0.05%   |
| ADMtek                            | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 718       | 35.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 168       | 8.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 79        | 3.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 75        | 3.73%   |
| Nvidia MCP79 Ethernet                                                  | 41        | 2.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 38        | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 32        | 1.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 31        | 1.54%   |
| Intel Ethernet Connection I217-LM                                      | 30        | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 1.34%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 27        | 1.34%   |
| Intel I211 Gigabit Network Connection                                  | 27        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 22        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                   | 22        | 1.1%    |
| Intel Ethernet Connection I218-LM                                      | 20        | 1%      |
| Intel 82577LM Gigabit Network Connection                               | 20        | 1%      |
| Intel Ethernet Connection I219-LM                                      | 18        | 0.9%    |
| Intel Ethernet Connection (7) I219-V                                   | 18        | 0.9%    |
| Intel 82579V Gigabit Network Connection                                | 18        | 0.9%    |
| Intel Ethernet Connection (4) I219-V                                   | 17        | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 16        | 0.8%    |
| Intel Ethernet Controller I225-V                                       | 16        | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 15        | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 14        | 0.7%    |
| Intel Ethernet Connection I217-V                                       | 14        | 0.7%    |
| ASIX AX88179 Gigabit Ethernet                                          | 14        | 0.7%    |
| Intel Ethernet Connection I219-V                                       | 12        | 0.6%    |
| Intel 82567LM Gigabit Network Connection                               | 12        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 0.55%   |
| Intel 82574L Gigabit Network Connection                                | 11        | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 11        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 10        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 9         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 9         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 9         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9         | 0.45%   |
| Huawei FOA-LX9                                                         | 8         | 0.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 8         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 7         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1990      | 50.79%  |
| Ethernet | 1887      | 48.16%  |
| Modem    | 38        | 0.97%   |
| Unknown  | 3         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1551      | 66.25%  |
| Ethernet | 789       | 33.7%   |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1372      | 59.47%  |
| 1     | 859       | 37.23%  |
| 0     | 37        | 1.6%    |
| 3     | 33        | 1.43%   |
| 4     | 5         | 0.22%   |
| 5     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 1703      | 72.96%  |
| Yes     | 630       | 26.99%  |
| Unknown | 1         | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 636       | 37.08%  |
| Apple                           | 302       | 17.61%  |
| Realtek Semiconductor           | 183       | 10.67%  |
| Qualcomm Atheros Communications | 131       | 7.64%   |
| Cambridge Silicon Radio         | 79        | 4.61%   |
| Broadcom                        | 78        | 4.55%   |
| Lite-On Technology              | 55        | 3.21%   |
| Foxconn / Hon Hai               | 54        | 3.15%   |
| IMC Networks                    | 48        | 2.8%    |
| Hewlett-Packard                 | 24        | 1.4%    |
| Dell                            | 20        | 1.17%   |
| Toshiba                         | 17        | 0.99%   |
| ASUSTek Computer                | 16        | 0.93%   |
| Ralink                          | 15        | 0.87%   |
| Realtek                         | 14        | 0.82%   |
| Marvell Semiconductor           | 12        | 0.7%    |
| MediaTek                        | 4         | 0.23%   |
| Foxconn International           | 4         | 0.23%   |
| TP-Link                         | 3         | 0.17%   |
| Qcom                            | 3         | 0.17%   |
| Unknown                         | 3         | 0.17%   |
| Belkin Components               | 2         | 0.12%   |
| Askey Computer                  | 2         | 0.12%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Smart Modular Technologies      | 1         | 0.06%   |
| Ralink Technology               | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Logitech                        | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| Alps Electric                   | 1         | 0.06%   |
| Actions                         | 1         | 0.06%   |
| 3Com                            | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 271       | 15.8%   |
| Apple Bluetooth Host Controller                                                     | 137       | 7.99%   |
| Intel AX201 Bluetooth                                                               | 121       | 7.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 102       | 5.95%   |
| Realtek Bluetooth Radio                                                             | 98        | 5.71%   |
| Apple Bluetooth USB Host Controller                                                 | 90        | 5.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 79        | 4.61%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 69        | 4.02%   |
| Intel AX200 Bluetooth                                                               | 53        | 3.09%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 47        | 2.74%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 44        | 2.57%   |
| Apple Bluetooth HCI                                                                 | 31        | 1.81%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 25        | 1.46%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 24        | 1.4%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 20        | 1.17%   |
| Intel AX210 Bluetooth                                                               | 19        | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 17        | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 16        | 0.93%   |
| Ralink RT3290 Bluetooth                                                             | 15        | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 15        | 0.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 15        | 0.87%   |
| Lite-On Bluetooth Device                                                            | 15        | 0.87%   |
| Realtek Bluetooth Radio                                                             | 14        | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 14        | 0.82%   |
| Realtek 802.11ac WLAN Adapter                                                       | 13        | 0.76%   |
| IMC Networks Wireless_Device                                                        | 13        | 0.76%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 0.7%    |
| Intel AX211 Bluetooth                                                               | 12        | 0.7%    |
| Dell DW375 Bluetooth Module                                                         | 12        | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 0.64%   |
| Realtek RTL8821A Bluetooth                                                          | 10        | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 0.52%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 8         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 8         | 0.47%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 8         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 7         | 0.41%   |
| IMC Networks Bluetooth Device                                                       | 7         | 0.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 7         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1794      | 58.72%  |
| AMD                                          | 570       | 18.66%  |
| Nvidia                                       | 451       | 14.76%  |
| C-Media Electronics                          | 58        | 1.9%    |
| Logitech                                     | 24        | 0.79%   |
| Creative Labs                                | 17        | 0.56%   |
| Generalplus Technology                       | 14        | 0.46%   |
| JMTek                                        | 9         | 0.29%   |
| Texas Instruments                            | 8         | 0.26%   |
| GN Netcom                                    | 8         | 0.26%   |
| Realtek Semiconductor                        | 5         | 0.16%   |
| Razer USA                                    | 5         | 0.16%   |
| Corsair                                      | 5         | 0.16%   |
| Dell                                         | 4         | 0.13%   |
| Creative Technology                          | 4         | 0.13%   |
| BEHRINGER International                      | 4         | 0.13%   |
| Hewlett-Packard                              | 3         | 0.1%    |
| Cambridge Silicon Radio                      | 3         | 0.1%    |
| ASUSTek Computer                             | 3         | 0.1%    |
| Thesycon Systemsoftware & Consulting         | 2         | 0.07%   |
| SteelSeries ApS                              | 2         | 0.07%   |
| Sony                                         | 2         | 0.07%   |
| Plantronics                                  | 2         | 0.07%   |
| Native Instruments                           | 2         | 0.07%   |
| Microsoft                                    | 2         | 0.07%   |
| Micro Star International                     | 2         | 0.07%   |
| M-Audio                                      | 2         | 0.07%   |
| KTMicro                                      | 2         | 0.07%   |
| Kingston Technology                          | 2         | 0.07%   |
| Jieli Technology                             | 2         | 0.07%   |
| Huawei Technologies                          | 2         | 0.07%   |
| Guillemot                                    | 2         | 0.07%   |
| Goldvish                                     | 2         | 0.07%   |
| Focusrite-Novation                           | 2         | 0.07%   |
| fifine Microphones                           | 2         | 0.07%   |
| ESS Technology                               | 2         | 0.07%   |
| Apple                                        | 2         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| YUAN High-Tech Development                   | 1         | 0.03%   |
| Yealink Network Technology                   | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 219       | 6.01%   |
| Intel Sunrise Point-LP HD Audio                                            | 204       | 5.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 198       | 5.43%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 161       | 4.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 128       | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 108       | 2.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 91        | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 91        | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 83        | 2.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 81        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 78        | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 70        | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 69        | 1.89%   |
| Intel Broadwell-U Audio Controller                                         | 68        | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 67        | 1.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 64        | 1.76%   |
| AMD FCH Azalia Controller                                                  | 64        | 1.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 61        | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                               | 48        | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                   | 46        | 1.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 44        | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 44        | 1.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 44        | 1.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 42        | 1.15%   |
| Nvidia MCP79 High Definition Audio                                         | 41        | 1.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 41        | 1.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 38        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 37        | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 36        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 34        | 0.93%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 31        | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                         | 28        | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 28        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 27        | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 27        | 0.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 27        | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 25        | 0.69%   |
| AMD High Definition Audio Controller                                       | 25        | 0.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 25        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 157       | 24.49%  |
| SK hynix            | 111       | 17.32%  |
| Kingston            | 77        | 12.01%  |
| Micron Technology   | 76        | 11.86%  |
| Unknown             | 47        | 7.33%   |
| Crucial             | 32        | 4.99%   |
| Elpida              | 18        | 2.81%   |
| Corsair             | 17        | 2.65%   |
| Unknown (ABCD)      | 14        | 2.18%   |
| A-DATA Technology   | 13        | 2.03%   |
| G.Skill             | 12        | 1.87%   |
| Ramaxel Technology  | 10        | 1.56%   |
| Nanya Technology    | 6         | 0.94%   |
| Transcend           | 4         | 0.62%   |
| Smart               | 4         | 0.62%   |
| Patriot             | 4         | 0.62%   |
| Unknown             | 4         | 0.62%   |
| Timetec             | 3         | 0.47%   |
| GSkill              | 3         | 0.47%   |
| Apacer              | 3         | 0.47%   |
| Team                | 2         | 0.31%   |
| PNY                 | 2         | 0.31%   |
| Multilaser          | 2         | 0.31%   |
| AMD                 | 2         | 0.31%   |
| Unknown (82B5)      | 1         | 0.16%   |
| Unknown (0x5846)    | 1         | 0.16%   |
| Unknown (0x198)     | 1         | 0.16%   |
| Unknown (0x038A)    | 1         | 0.16%   |
| Toshiba             | 1         | 0.16%   |
| Smart Brazil        | 1         | 0.16%   |
| SHARETRONIC         | 1         | 0.16%   |
| Qimonda             | 1         | 0.16%   |
| pqi                 | 1         | 0.16%   |
| Neo Forza           | 1         | 0.16%   |
| Melco               | 1         | 0.16%   |
| Magnum Tech         | 1         | 0.16%   |
| Kllisre             | 1         | 0.16%   |
| Hewlett-Packard     | 1         | 0.16%   |
| CSX                 | 1         | 0.16%   |
| Avant               | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 12        | 1.77%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 1.03%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.74%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 4         | 0.59%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 4         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.59%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 4         | 0.59%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.59%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.59%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 4         | 0.59%   |
| Unknown                                                          | 4         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 3         | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 3         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.44%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.44%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 3         | 0.44%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 3         | 0.44%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.44%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 3         | 0.44%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.44%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.44%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 218       | 40.75%  |
| DDR4    | 207       | 38.69%  |
| LPDDR4  | 38        | 7.1%    |
| DDR2    | 27        | 5.05%   |
| LPDDR3  | 17        | 3.18%   |
| SDRAM   | 13        | 2.43%   |
| Unknown | 8         | 1.5%    |
| LPDDR5  | 3         | 0.56%   |
| DDR5    | 2         | 0.37%   |
| DRAM    | 1         | 0.19%   |
| DDR     | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 373       | 69.46%  |
| DIMM         | 110       | 20.48%  |
| Row Of Chips | 48        | 8.94%   |
| Chip         | 4         | 0.74%   |
| FB-DIMM      | 1         | 0.19%   |
| Unknown      | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 243       | 40.23%  |
| 4096  | 177       | 29.3%   |
| 2048  | 88        | 14.57%  |
| 16384 | 68        | 11.26%  |
| 1024  | 18        | 2.98%   |
| 32768 | 9         | 1.49%   |
| 512   | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 130       | 21.96%  |
| 2667    | 89        | 15.03%  |
| 3200    | 68        | 11.49%  |
| 1333    | 51        | 8.61%   |
| 2400    | 48        | 8.11%   |
| 2133    | 37        | 6.25%   |
| 1334    | 20        | 3.38%   |
| 667     | 16        | 2.7%    |
| 800     | 15        | 2.53%   |
| 4267    | 14        | 2.36%   |
| 1867    | 14        | 2.36%   |
| 1067    | 12        | 2.03%   |
| 1066    | 9         | 1.52%   |
| 3600    | 6         | 1.01%   |
| 3266    | 6         | 1.01%   |
| 3733    | 5         | 0.84%   |
| 1800    | 4         | 0.68%   |
| 8400    | 3         | 0.51%   |
| 4800    | 3         | 0.51%   |
| 4266    | 3         | 0.51%   |
| 4199    | 3         | 0.51%   |
| 1866    | 3         | 0.51%   |
| 975     | 3         | 0.51%   |
| Unknown | 3         | 0.51%   |
| 7500    | 2         | 0.34%   |
| 3466    | 2         | 0.34%   |
| 3066    | 2         | 0.34%   |
| 2933    | 2         | 0.34%   |
| 2048    | 2         | 0.34%   |
| 1639    | 2         | 0.34%   |
| 6400    | 1         | 0.17%   |
| 4000    | 1         | 0.17%   |
| 3866    | 1         | 0.17%   |
| 3400    | 1         | 0.17%   |
| 3334    | 1         | 0.17%   |
| 3007    | 1         | 0.17%   |
| 3000    | 1         | 0.17%   |
| 2934    | 1         | 0.17%   |
| 2800    | 1         | 0.17%   |
| 2733    | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 15        | 29.41%  |
| Canon                           | 8         | 15.69%  |
| Brother Industries              | 8         | 15.69%  |
| Samsung Electronics             | 7         | 13.73%  |
| Seiko Epson                     | 4         | 7.84%   |
| Lexmark International           | 3         | 5.88%   |
| Xerox                           | 2         | 3.92%   |
| QUIN                            | 1         | 1.96%   |
| Prolific Technology             | 1         | 1.96%   |
| Dymo-CoStar                     | 1         | 1.96%   |
| cab Produkttechnik GmbH & Co KG | 1         | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                  | 3         | 5.88%   |
| Samsung M2070 Series                                  | 2         | 3.92%   |
| Xerox Phaser 3610                                     | 1         | 1.96%   |
| Xerox Phaser 3040                                     | 1         | 1.96%   |
| Seiko Epson XP-4100 Series                            | 1         | 1.96%   |
| Seiko Epson XP-205 207 Series                         | 1         | 1.96%   |
| Seiko Epson L355 Series                               | 1         | 1.96%   |
| Seiko Epson ET-2600 Series                            | 1         | 1.96%   |
| Samsung M288x Series                                  | 1         | 1.96%   |
| Samsung C48x Series Color Laser Multifunction Printer | 1         | 1.96%   |
| QUIN Label Printer                                    | 1         | 1.96%   |
| Prolific PL2305 Parallel Port                         | 1         | 1.96%   |
| Lexmark International Laser Printer E210              | 1         | 1.96%   |
| Lexmark International InkJet Color Printer            | 1         | 1.96%   |
| Lexmark International f+ imaging M40adn               | 1         | 1.96%   |
| HP Smart Tank 580-590 series                          | 1         | 1.96%   |
| HP Printing Support                                   | 1         | 1.96%   |
| HP OfficeJet 5200 series                              | 1         | 1.96%   |
| HP LaserJet Pro M201dw                                | 1         | 1.96%   |
| HP LaserJet M101-M106                                 | 1         | 1.96%   |
| HP LaserJet 1320                                      | 1         | 1.96%   |
| HP LaserJet 1300                                      | 1         | 1.96%   |
| HP LaserJet 1020                                      | 1         | 1.96%   |
| HP Ink Tank 110 series                                | 1         | 1.96%   |
| HP Deskjet F4500 series                               | 1         | 1.96%   |
| HP Deskjet 3520 series                                | 1         | 1.96%   |
| HP DeskJet 2700 series                                | 1         | 1.96%   |
| HP DeskJet 2620 All-in-One Printer                    | 1         | 1.96%   |
| HP Deskjet 2050 J510                                  | 1         | 1.96%   |
| HP Deskjet 1000 J110 series                           | 1         | 1.96%   |
| Dymo-CoStar LabelWriter 450                           | 1         | 1.96%   |
| Canon TR8500 series                                   | 1         | 1.96%   |
| Canon PIXMA MX390 Series                              | 1         | 1.96%   |
| Canon PIXMA MG3600 Series                             | 1         | 1.96%   |
| Canon PIXMA MG2500 Series                             | 1         | 1.96%   |
| Canon MF4320-4350                                     | 1         | 1.96%   |
| Canon LBP3360                                         | 1         | 1.96%   |
| Canon G3000 series                                    | 1         | 1.96%   |
| Canon CanoScan LiDE 300                               | 1         | 1.96%   |
| cab Produkttechnik GmbH & Co KG EOS2/300              | 1         | 1.96%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 66.67%  |
| Seiko Epson | 2         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 16.67%  |
| Seiko Epson ES-H300 [GT-2500]                           | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 16.67%  |
| Canon CanoScan LIDE 25                                  | 1         | 16.67%  |
| Canon CanoScan LiDE 110                                 | 1         | 16.67%  |
| Canon CanoScan LiDE 100                                 | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 298       | 18.53%  |
| Apple                                  | 236       | 14.68%  |
| Realtek Semiconductor                  | 122       | 7.59%   |
| IMC Networks                           | 118       | 7.34%   |
| Microdia                               | 113       | 7.03%   |
| Quanta                                 | 83        | 5.16%   |
| Sunplus Innovation Technology          | 81        | 5.04%   |
| Bison Electronics                      | 73        | 4.54%   |
| Cheng Uei Precision Industry (Foxlink) | 67        | 4.17%   |
| Suyin                                  | 50        | 3.11%   |
| Syntek                                 | 44        | 2.74%   |
| Logitech                               | 43        | 2.67%   |
| Silicon Motion                         | 30        | 1.87%   |
| Lite-On Technology                     | 30        | 1.87%   |
| Alcor Micro                            | 26        | 1.62%   |
| Acer                                   | 21        | 1.31%   |
| Luxvisions Innotech Limited            | 20        | 1.24%   |
| Microsoft                              | 15        | 0.93%   |
| Ricoh                                  | 12        | 0.75%   |
| Samsung Electronics                    | 11        | 0.68%   |
| Lenovo                                 | 11        | 0.68%   |
| Generalplus Technology                 | 8         | 0.5%    |
| SunplusIT                              | 7         | 0.44%   |
| Importek                               | 6         | 0.37%   |
| Z-Star Microelectronics                | 5         | 0.31%   |
| Sonix Technology                       | 5         | 0.31%   |
| Primax Electronics                     | 5         | 0.31%   |
| LG Electronics                         | 5         | 0.31%   |
| ALi                                    | 5         | 0.31%   |
| KYE Systems (Mouse Systems)            | 4         | 0.25%   |
| GEMBIRD                                | 4         | 0.25%   |
| Cubeternet                             | 4         | 0.25%   |
| Y Media                                | 3         | 0.19%   |
| Jieli Technology                       | 3         | 0.19%   |
| Sunplus Technology                     | 2         | 0.12%   |
| ShineTech                              | 2         | 0.12%   |
| Shine-optics                           | 2         | 0.12%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.12%   |
| Razer USA                              | 2         | 0.12%   |
| icSpring                               | 2         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Apple Built-in iSight                   | 87        | 5.36%   |
| Apple FaceTime HD Camera                | 60        | 3.7%    |
| Chicony Integrated Camera               | 59        | 3.64%   |
| Apple FaceTime HD Camera (Built-in)     | 44        | 2.71%   |
| Realtek Integrated_Webcam_HD            | 37        | 2.28%   |
| IMC Networks USB2.0 HD UVC WebCam       | 35        | 2.16%   |
| Microdia Integrated_Webcam_HD           | 32        | 1.97%   |
| IMC Networks Integrated Camera          | 31        | 1.91%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 31        | 1.91%   |
| Chicony HD WebCam                       | 27        | 1.66%   |
| Syntek Integrated Camera                | 20        | 1.23%   |
| Sunplus Integrated_Webcam_HD            | 19        | 1.17%   |
| Microdia Integrated Webcam              | 14        | 0.86%   |
| Logitech HD Pro Webcam C920             | 14        | 0.86%   |
| Lite-On Integrated Camera               | 14        | 0.86%   |
| Chicony HP Truevision HD                | 14        | 0.86%   |
| Apple FaceTime Camera                   | 14        | 0.86%   |
| Realtek USB Camera                      | 13        | 0.8%    |
| Quanta HP Webcam                        | 13        | 0.8%    |
| Chicony EasyCamera                      | 12        | 0.74%   |
| Syntek EasyCamera                       | 11        | 0.68%   |
| Microdia USB 2.0 Camera                 | 11        | 0.68%   |
| Chicony HP Truevision HD camera         | 11        | 0.68%   |
| Chicony HP HD Webcam [Fixed]            | 11        | 0.68%   |
| Bison Integrated Camera                 | 11        | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode) | 10        | 0.62%   |
| Realtek Integrated Webcam               | 10        | 0.62%   |
| Quanta HP TrueVision HD Camera          | 10        | 0.62%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 10        | 0.62%   |
| Bison Lenovo EasyCamera                 | 10        | 0.62%   |
| Alcor Micro USB 2.0 Camera              | 10        | 0.62%   |
| Syntek Lenovo EasyCamera                | 9         | 0.55%   |
| Sunplus HD WebCam                       | 9         | 0.55%   |
| Realtek USB2.0 HD UVC WebCam            | 9         | 0.55%   |
| Quanta HD User Facing                   | 9         | 0.55%   |
| Chicony USB2.0 VGA UVC WebCam           | 9         | 0.55%   |
| Chicony USB 2.0 Camera                  | 9         | 0.55%   |
| Quanta HD Camera                        | 8         | 0.49%   |
| Chicony VGA WebCam                      | 8         | 0.49%   |
| Chicony HP HD Camera                    | 8         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 99        | 38.67%  |
| Synaptics                  | 60        | 23.44%  |
| Shenzhen Goodix Technology | 41        | 16.02%  |
| LighTuning Technology      | 18        | 7.03%   |
| Upek                       | 12        | 4.69%   |
| Elan Microelectronics      | 11        | 4.3%    |
| AuthenTec                  | 10        | 3.91%   |
| STMicroelectronics         | 2         | 0.78%   |
| Focal-systems.Corp         | 2         | 0.78%   |
| Samsung Electronics        | 1         | 0.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 32        | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 8.2%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 5.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 5.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 5.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 4.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 4.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 4.3%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 3.13%   |
| Validity Sensors VFS491                                                    | 7         | 2.73%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.34%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.34%   |
| Synaptics UWP WBDI                                                         | 6         | 2.34%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 2.34%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 1.95%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 1.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.56%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.56%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.56%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.56%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.56%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.17%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.17%   |
| Synaptics WBDI                                                             | 3         | 1.17%   |
| Synaptics  WBDI                                                            | 3         | 1.17%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.17%   |
| Elan WBF Fingerprint Sensor                                                | 3         | 1.17%   |
| AuthenTec AES2810                                                          | 3         | 1.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.78%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.78%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.78%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.78%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 0.78%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.78%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.39%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 49        | 49.49%  |
| Alcor Micro                       | 25        | 25.25%  |
| O2 Micro                          | 7         | 7.07%   |
| Upek                              | 6         | 6.06%   |
| Lenovo                            | 6         | 6.06%   |
| VASCO Data Security International | 1         | 1.01%   |
| SCM Microsystems                  | 1         | 1.01%   |
| OmniKey                           | 1         | 1.01%   |
| Gemalto (was Gemplus)             | 1         | 1.01%   |
| Feitian Technologies              | 1         | 1.01%   |
| Chicony Electronics               | 1         | 1.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 25.25%  |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 21.21%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 11.11%  |
| Broadcom 5880                                                                | 9         | 9.09%   |
| Broadcom 58200                                                               | 8         | 8.08%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 6.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 6.06%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 6.06%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 1.01%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.01%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 1.01%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.01%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.01%   |
| Feitian Technologies SCR301                                                  | 1         | 1.01%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.01%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1617      | 69.31%  |
| 1     | 571       | 24.47%  |
| 2     | 125       | 5.36%   |
| 3     | 16        | 0.69%   |
| 4     | 2         | 0.09%   |
| 9     | 1         | 0.04%   |
| 8     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 254       | 29.1%   |
| Net/wireless             | 192       | 21.99%  |
| Graphics card            | 130       | 14.89%  |
| Multimedia controller    | 96        | 11%     |
| Chipcard                 | 94        | 10.77%  |
| Bluetooth                | 19        | 2.18%   |
| Camera                   | 15        | 1.72%   |
| Storage                  | 14        | 1.6%    |
| Sound                    | 13        | 1.49%   |
| Net/ethernet             | 10        | 1.15%   |
| Communication controller | 10        | 1.15%   |
| Unassigned class         | 8         | 0.92%   |
| Card reader              | 7         | 0.8%    |
| Network                  | 5         | 0.57%   |
| Storage/raid             | 3         | 0.34%   |
| Storage/ide              | 1         | 0.11%   |
| Storage/ata              | 1         | 0.11%   |
| Modem                    | 1         | 0.11%   |

