Linux in Italy - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 8801

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [9d27bb4f90](https://linux-hardware.org/?probe=9d27bb4f90) | Dec 01, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [1df1f552ff](https://linux-hardware.org/?probe=1df1f552ff) | Dec 01, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [961f58c143](https://linux-hardware.org/?probe=961f58c143) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [a8236e24a5](https://linux-hardware.org/?probe=a8236e24a5) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [ab421fd2d4](https://linux-hardware.org/?probe=ab421fd2d4) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [198d7f2534](https://linux-hardware.org/?probe=198d7f2534) | Dec 01, 2022 |
| ASUSTek       | K52F                        | Notebook    | [63c08600c3](https://linux-hardware.org/?probe=63c08600c3) | Dec 01, 2022 |
| ASUSTek       | K52F                        | Notebook    | [4276cc2cb9](https://linux-hardware.org/?probe=4276cc2cb9) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [4f517e816d](https://linux-hardware.org/?probe=4f517e816d) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| MSI           | Boston                      | Desktop     | [0564f7ed2d](https://linux-hardware.org/?probe=0564f7ed2d) | Nov 30, 2022 |
| HP            | 304Ah                       | Desktop     | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [dfe92c80c1](https://linux-hardware.org/?probe=dfe92c80c1) | Nov 30, 2022 |
| Dell          | Studio 1558                 | Notebook    | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c552ca011c](https://linux-hardware.org/?probe=c552ca011c) | Nov 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [0866a64897](https://linux-hardware.org/?probe=0866a64897) | Nov 30, 2022 |
| Apple         | MacBookAir8,1               | Notebook    | [7581ef0e85](https://linux-hardware.org/?probe=7581ef0e85) | Nov 29, 2022 |
| IBM           | MSI-9151 Boards             | Desktop     | [720ff829b9](https://linux-hardware.org/?probe=720ff829b9) | Nov 29, 2022 |
| HP            | 3048h                       | Desktop     | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [719921de81](https://linux-hardware.org/?probe=719921de81) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [f998b6a0d9](https://linux-hardware.org/?probe=f998b6a0d9) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [d5702f8b2d](https://linux-hardware.org/?probe=d5702f8b2d) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [640a031786](https://linux-hardware.org/?probe=640a031786) | Nov 29, 2022 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [cbb0c1dca7](https://linux-hardware.org/?probe=cbb0c1dca7) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | Notebook    | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | Notebook    | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [a9697f1e7a](https://linux-hardware.org/?probe=a9697f1e7a) | Nov 28, 2022 |
| HP            | 843B                        | Desktop     | [19bd35484c](https://linux-hardware.org/?probe=19bd35484c) | Nov 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [becbfa5cc7](https://linux-hardware.org/?probe=becbfa5cc7) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [0d99651537](https://linux-hardware.org/?probe=0d99651537) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [3f660318ea](https://linux-hardware.org/?probe=3f660318ea) | Nov 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [c306dcfa4f](https://linux-hardware.org/?probe=c306dcfa4f) | Nov 27, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [44a305db4d](https://linux-hardware.org/?probe=44a305db4d) | Nov 27, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [02c62a5eb8](https://linux-hardware.org/?probe=02c62a5eb8) | Nov 27, 2022 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [63d2134051](https://linux-hardware.org/?probe=63d2134051) | Nov 27, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [8f510e55e2](https://linux-hardware.org/?probe=8f510e55e2) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [6206268283](https://linux-hardware.org/?probe=6206268283) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | G5 5587                     | Notebook    | [689db41249](https://linux-hardware.org/?probe=689db41249) | Nov 27, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [f397d89e9b](https://linux-hardware.org/?probe=f397d89e9b) | Nov 27, 2022 |
| Lenovo        | ThinkPad X280 20KES2DD0D    | Notebook    | [394b24459c](https://linux-hardware.org/?probe=394b24459c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | Notebook    | [f91c391079](https://linux-hardware.org/?probe=f91c391079) | Nov 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [b5260b5609](https://linux-hardware.org/?probe=b5260b5609) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [eb0921d1f6](https://linux-hardware.org/?probe=eb0921d1f6) | Nov 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [e3c2051d8f](https://linux-hardware.org/?probe=e3c2051d8f) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [57e4892065](https://linux-hardware.org/?probe=57e4892065) | Nov 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ce7815f106](https://linux-hardware.org/?probe=ce7815f106) | Nov 26, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [949860da0f](https://linux-hardware.org/?probe=949860da0f) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [0569fa8cc9](https://linux-hardware.org/?probe=0569fa8cc9) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | Notebook    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
| Sony          | SVP1121X9EB                 | Notebook    | [78df785a47](https://linux-hardware.org/?probe=78df785a47) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| ASUSTek       | X202E                       | Notebook    | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [4d8bd1760a](https://linux-hardware.org/?probe=4d8bd1760a) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| HP            | 3397                        | Desktop     | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [d044aabfec](https://linux-hardware.org/?probe=d044aabfec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Dell          | Latitude 3450               | Notebook    | [d7af694917](https://linux-hardware.org/?probe=d7af694917) | Nov 25, 2022 |
| ASUSTek       | P8H61-I LX/RM/SI            | Desktop     | [61cfa154b0](https://linux-hardware.org/?probe=61cfa154b0) | Nov 24, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| MSI           | H81M-E33                    | Desktop     | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Alienware     | 15                          | Notebook    | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [2d1c8c7ea5](https://linux-hardware.org/?probe=2d1c8c7ea5) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [30081f61ca](https://linux-hardware.org/?probe=30081f61ca) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [9e33d3b8f1](https://linux-hardware.org/?probe=9e33d3b8f1) | Nov 24, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [b0d1e2e0ba](https://linux-hardware.org/?probe=b0d1e2e0ba) | Nov 24, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [894c4e9ebf](https://linux-hardware.org/?probe=894c4e9ebf) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [7ce85c6de5](https://linux-hardware.org/?probe=7ce85c6de5) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e4904d14cc](https://linux-hardware.org/?probe=e4904d14cc) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [fd8121fecd](https://linux-hardware.org/?probe=fd8121fecd) | Nov 22, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | Desktop     | [14c0f082d8](https://linux-hardware.org/?probe=14c0f082d8) | Nov 22, 2022 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [e497c428f0](https://linux-hardware.org/?probe=e497c428f0) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [d0bd92a5e0](https://linux-hardware.org/?probe=d0bd92a5e0) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [b4cc2dc00b](https://linux-hardware.org/?probe=b4cc2dc00b) | Nov 22, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [dc74022dc5](https://linux-hardware.org/?probe=dc74022dc5) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Microtech     | etabPro4+                   | Tablet      | [4fe8061ebd](https://linux-hardware.org/?probe=4fe8061ebd) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [923ccf8b76](https://linux-hardware.org/?probe=923ccf8b76) | Nov 22, 2022 |
| HP            | 83E2                        | Desktop     | [b04e1014da](https://linux-hardware.org/?probe=b04e1014da) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| ASUSTek       | GL503VS                     | Notebook    | [18fa411a6d](https://linux-hardware.org/?probe=18fa411a6d) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Latitude 9420               | Notebook    | [ddf8c8749c](https://linux-hardware.org/?probe=ddf8c8749c) | Nov 21, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [a94bd1fd5a](https://linux-hardware.org/?probe=a94bd1fd5a) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [7ccd7842c1](https://linux-hardware.org/?probe=7ccd7842c1) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [c14020107c](https://linux-hardware.org/?probe=c14020107c) | Nov 21, 2022 |
| HP            | 2AF3                        | Desktop     | [babcb0bf93](https://linux-hardware.org/?probe=babcb0bf93) | Nov 21, 2022 |
| Microtech     | etabPro4+                   | Tablet      | [ccf3636310](https://linux-hardware.org/?probe=ccf3636310) | Nov 21, 2022 |
| Google        | Sasuke                      | Notebook    | [35330e59ad](https://linux-hardware.org/?probe=35330e59ad) | Nov 20, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [aaa2d66240](https://linux-hardware.org/?probe=aaa2d66240) | Nov 20, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [3ecbc7acb4](https://linux-hardware.org/?probe=3ecbc7acb4) | Nov 20, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [cd2b457ffb](https://linux-hardware.org/?probe=cd2b457ffb) | Nov 20, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | Desktop     | [07ca09898f](https://linux-hardware.org/?probe=07ca09898f) | Nov 20, 2022 |
| HP            | Notebook                    | Notebook    | [1278403b39](https://linux-hardware.org/?probe=1278403b39) | Nov 20, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | Notebook    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [eeefed51e4](https://linux-hardware.org/?probe=eeefed51e4) | Nov 20, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [b9d2b8c218](https://linux-hardware.org/?probe=b9d2b8c218) | Nov 20, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [9f6c38b4ee](https://linux-hardware.org/?probe=9f6c38b4ee) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Acer          | aspire5740                  | Notebook    | [6cdc4f5cfc](https://linux-hardware.org/?probe=6cdc4f5cfc) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [835c000337](https://linux-hardware.org/?probe=835c000337) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | Desktop     | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| HP            | 8767 A                      | Desktop     | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [4f04b7d627](https://linux-hardware.org/?probe=4f04b7d627) | Nov 19, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [3b15bcfd88](https://linux-hardware.org/?probe=3b15bcfd88) | Nov 19, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| Olidata       | T7700                       | Notebook    | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f1724d63d5](https://linux-hardware.org/?probe=f1724d63d5) | Nov 19, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c2d79be90d](https://linux-hardware.org/?probe=c2d79be90d) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| HP            | Presario CQ58               | Notebook    | [fc1d1892ef](https://linux-hardware.org/?probe=fc1d1892ef) | Nov 19, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [c11ad764af](https://linux-hardware.org/?probe=c11ad764af) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [865fa07274](https://linux-hardware.org/?probe=865fa07274) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [68d651f36b](https://linux-hardware.org/?probe=68d651f36b) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| Sony          | VPCYA1C5E                   | Notebook    | [416067b991](https://linux-hardware.org/?probe=416067b991) | Nov 18, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [a61b66e4ed](https://linux-hardware.org/?probe=a61b66e4ed) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [945910eb8a](https://linux-hardware.org/?probe=945910eb8a) | Nov 18, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [f58db71272](https://linux-hardware.org/?probe=f58db71272) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [e18aef24ac](https://linux-hardware.org/?probe=e18aef24ac) | Nov 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | Notebook    | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Acer          | E946GZ                      | Desktop     | [f084e099d5](https://linux-hardware.org/?probe=f084e099d5) | Nov 17, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [19d18ac52c](https://linux-hardware.org/?probe=19d18ac52c) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | Notebook    | [aa7f8583b6](https://linux-hardware.org/?probe=aa7f8583b6) | Nov 17, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [3f03d0cbaa](https://linux-hardware.org/?probe=3f03d0cbaa) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | Notebook    | [c15d4ee015](https://linux-hardware.org/?probe=c15d4ee015) | Nov 17, 2022 |
| Mediacom      | FlexBook_edge13-M-FBE13     | Notebook    | [b5106cb728](https://linux-hardware.org/?probe=b5106cb728) | Nov 17, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| HP            | 250 G4                      | Notebook    | [3f2660a101](https://linux-hardware.org/?probe=3f2660a101) | Nov 16, 2022 |
| HP            | 250 G4                      | Notebook    | [cc4a368fd3](https://linux-hardware.org/?probe=cc4a368fd3) | Nov 16, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [61f5cf6214](https://linux-hardware.org/?probe=61f5cf6214) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [78601d078c](https://linux-hardware.org/?probe=78601d078c) | Nov 16, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [8312099aa4](https://linux-hardware.org/?probe=8312099aa4) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d62ee2298d](https://linux-hardware.org/?probe=d62ee2298d) | Nov 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [e2492ba1c1](https://linux-hardware.org/?probe=e2492ba1c1) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [df8344d098](https://linux-hardware.org/?probe=df8344d098) | Nov 16, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| Chuwi         | LarkBox X                   | Mini pc     | [cbfdfc82b4](https://linux-hardware.org/?probe=cbfdfc82b4) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Fujitsu       | LIFEBOOK E557               | Notebook    | [a57972523b](https://linux-hardware.org/?probe=a57972523b) | Nov 15, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [699ea2cc17](https://linux-hardware.org/?probe=699ea2cc17) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| System76      | Oryx Pro                    | Notebook    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | A58M-A/USB3                 | Desktop     | [f6342a3d18](https://linux-hardware.org/?probe=f6342a3d18) | Nov 15, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [403bc1b6b5](https://linux-hardware.org/?probe=403bc1b6b5) | Nov 14, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [6209796b42](https://linux-hardware.org/?probe=6209796b42) | Nov 14, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [b6e353af2b](https://linux-hardware.org/?probe=b6e353af2b) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [c642a76e3e](https://linux-hardware.org/?probe=c642a76e3e) | Nov 14, 2022 |
| Huanan        | X99-F8                      | Desktop     | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| ASUSTek       | N751JX                      | Notebook    | [cea52af467](https://linux-hardware.org/?probe=cea52af467) | Nov 14, 2022 |
| Olidata       | T7700                       | Notebook    | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [d28a778811](https://linux-hardware.org/?probe=d28a778811) | Nov 14, 2022 |
| Microtech     | ebookLite                   | Notebook    | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [211fdda09b](https://linux-hardware.org/?probe=211fdda09b) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [9fe2a7d245](https://linux-hardware.org/?probe=9fe2a7d245) | Nov 14, 2022 |
| Acer          | TravelMate P259-G2-MG       | Notebook    | [27d3da0f8a](https://linux-hardware.org/?probe=27d3da0f8a) | Nov 14, 2022 |
| HP            | 802F                        | Desktop     | [8e7dbc3f9f](https://linux-hardware.org/?probe=8e7dbc3f9f) | Nov 14, 2022 |
| HP            | 802F                        | Desktop     | [89441a53f7](https://linux-hardware.org/?probe=89441a53f7) | Nov 14, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [c3573fb12b](https://linux-hardware.org/?probe=c3573fb12b) | Nov 14, 2022 |
| Sony          | VGN-NS21M_W                 | Notebook    | [b3f4aef7a4](https://linux-hardware.org/?probe=b3f4aef7a4) | Nov 14, 2022 |
| Packard Be... | DOT S                       | Notebook    | [4e6d343f5c](https://linux-hardware.org/?probe=4e6d343f5c) | Nov 14, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [99c1eee67d](https://linux-hardware.org/?probe=99c1eee67d) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [36df61fb32](https://linux-hardware.org/?probe=36df61fb32) | Nov 13, 2022 |
| HP            | 3397                        | Desktop     | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| MSI           | Z97A GAMING 7               | Desktop     | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Lenovo        | ThinkPad L450 20DSS1GD00    | Notebook    | [b0ea02b16c](https://linux-hardware.org/?probe=b0ea02b16c) | Nov 13, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| MSI           | ZH77A-G43                   | Desktop     | [a8f49c1ad8](https://linux-hardware.org/?probe=a8f49c1ad8) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | Notebook    | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7d72f2fa26](https://linux-hardware.org/?probe=7d72f2fa26) | Nov 12, 2022 |
| MSI           | MS-7309                     | Desktop     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| Gigabyte      | 970A-DS3                    | Desktop     | [7c25342680](https://linux-hardware.org/?probe=7c25342680) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [768efc0c32](https://linux-hardware.org/?probe=768efc0c32) | Nov 12, 2022 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [c033c311f3](https://linux-hardware.org/?probe=c033c311f3) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Acer          | aspire5740                  | Notebook    | [5218638790](https://linux-hardware.org/?probe=5218638790) | Nov 12, 2022 |
| Microtech     | ebookLite                   | Notebook    | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [0dff6ba2e2](https://linux-hardware.org/?probe=0dff6ba2e2) | Nov 12, 2022 |
| Acer          | aspire5740                  | Notebook    | [ba3ea314f0](https://linux-hardware.org/?probe=ba3ea314f0) | Nov 12, 2022 |
| HP            | 15                          | Notebook    | [bebef9206b](https://linux-hardware.org/?probe=bebef9206b) | Nov 12, 2022 |
| Unknown       | 775i65G                     | Desktop     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [361f37b08d](https://linux-hardware.org/?probe=361f37b08d) | Nov 11, 2022 |
| ASUSTek       | P5L1394                     | Desktop     | [d4c699bf10](https://linux-hardware.org/?probe=d4c699bf10) | Nov 11, 2022 |
| Dell          | Latitude E6440              | Notebook    | [7d35b21aae](https://linux-hardware.org/?probe=7d35b21aae) | Nov 11, 2022 |
| Unknown       | 1.0                         | Desktop     | [d07852e419](https://linux-hardware.org/?probe=d07852e419) | Nov 11, 2022 |
| ASUSTek       | X550JD                      | Notebook    | [9c88cc6c32](https://linux-hardware.org/?probe=9c88cc6c32) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4fddb7605a](https://linux-hardware.org/?probe=4fddb7605a) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [779188af6a](https://linux-hardware.org/?probe=779188af6a) | Nov 11, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [1759cf3bec](https://linux-hardware.org/?probe=1759cf3bec) | Nov 11, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [969fa6c183](https://linux-hardware.org/?probe=969fa6c183) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [08963a61fb](https://linux-hardware.org/?probe=08963a61fb) | Nov 10, 2022 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [78a6cdf739](https://linux-hardware.org/?probe=78a6cdf739) | Nov 10, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [132ffe6588](https://linux-hardware.org/?probe=132ffe6588) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [befb8455f0](https://linux-hardware.org/?probe=befb8455f0) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fc22f217b3](https://linux-hardware.org/?probe=fc22f217b3) | Nov 10, 2022 |
| ASRock        | B365 Pro4                   | Desktop     | [3069280223](https://linux-hardware.org/?probe=3069280223) | Nov 10, 2022 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [89839b84cb](https://linux-hardware.org/?probe=89839b84cb) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [31e940a232](https://linux-hardware.org/?probe=31e940a232) | Nov 10, 2022 |
| Microtech     | ebookLite                   | Notebook    | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Timi          | TM1701                      | Notebook    | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [dafce5f727](https://linux-hardware.org/?probe=dafce5f727) | Nov 09, 2022 |
| HP            | 15                          | Notebook    | [c301aa00eb](https://linux-hardware.org/?probe=c301aa00eb) | Nov 09, 2022 |
| MSI           | GL63 8RD                    | Notebook    | [e10069a2f8](https://linux-hardware.org/?probe=e10069a2f8) | Nov 09, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | Notebook    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [8939445388](https://linux-hardware.org/?probe=8939445388) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | Desktop     | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [a2e9b34d94](https://linux-hardware.org/?probe=a2e9b34d94) | Nov 09, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [439ec3a470](https://linux-hardware.org/?probe=439ec3a470) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [420aaf8ede](https://linux-hardware.org/?probe=420aaf8ede) | Nov 09, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [4bdd2e5e51](https://linux-hardware.org/?probe=4bdd2e5e51) | Nov 08, 2022 |
| Sony          | VGN-CS11Z_R                 | Notebook    | [865efadfee](https://linux-hardware.org/?probe=865efadfee) | Nov 08, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [f0634d863e](https://linux-hardware.org/?probe=f0634d863e) | Nov 08, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [2e0a3f4943](https://linux-hardware.org/?probe=2e0a3f4943) | Nov 08, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [a7ede6f17c](https://linux-hardware.org/?probe=a7ede6f17c) | Nov 08, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [656885b89d](https://linux-hardware.org/?probe=656885b89d) | Nov 08, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [19000343fd](https://linux-hardware.org/?probe=19000343fd) | Nov 08, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| Lenovo        | Flex 5-14ALC05 82HU         | Convertible | [2082ce8e0f](https://linux-hardware.org/?probe=2082ce8e0f) | Nov 08, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [11c3b15916](https://linux-hardware.org/?probe=11c3b15916) | Nov 08, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [9b54aae918](https://linux-hardware.org/?probe=9b54aae918) | Nov 08, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [46e5fff8cf](https://linux-hardware.org/?probe=46e5fff8cf) | Nov 08, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [f36e8a56db](https://linux-hardware.org/?probe=f36e8a56db) | Nov 08, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [b373db743a](https://linux-hardware.org/?probe=b373db743a) | Nov 08, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [6d246a753e](https://linux-hardware.org/?probe=6d246a753e) | Nov 08, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [47ac77d647](https://linux-hardware.org/?probe=47ac77d647) | Nov 08, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [a35aee6ec2](https://linux-hardware.org/?probe=a35aee6ec2) | Nov 08, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [92cf5ed7b4](https://linux-hardware.org/?probe=92cf5ed7b4) | Nov 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [b8f810cd9e](https://linux-hardware.org/?probe=b8f810cd9e) | Nov 07, 2022 |
| Dell          | 0X231R A01                  | Desktop     | [5846e23f06](https://linux-hardware.org/?probe=5846e23f06) | Nov 07, 2022 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [da4eb1c67f](https://linux-hardware.org/?probe=da4eb1c67f) | Nov 07, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [3339953a1e](https://linux-hardware.org/?probe=3339953a1e) | Nov 07, 2022 |
| Dell          | Precision M4500             | Notebook    | [0ace37e277](https://linux-hardware.org/?probe=0ace37e277) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [32b59c7a7d](https://linux-hardware.org/?probe=32b59c7a7d) | Nov 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ddca3f4758](https://linux-hardware.org/?probe=ddca3f4758) | Nov 06, 2022 |
| HP            | Notebook                    | Notebook    | [59b70f4c7c](https://linux-hardware.org/?probe=59b70f4c7c) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f0c8aff40f](https://linux-hardware.org/?probe=f0c8aff40f) | Nov 06, 2022 |
| Dell          | Latitude E6440              | Notebook    | [68593d9a9d](https://linux-hardware.org/?probe=68593d9a9d) | Nov 06, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [2ac38253fa](https://linux-hardware.org/?probe=2ac38253fa) | Nov 06, 2022 |
| Teclast       | F6 Pro                      | Notebook    | [bfba140f45](https://linux-hardware.org/?probe=bfba140f45) | Nov 06, 2022 |
| ASRock        | B365 Pro4                   | Desktop     | [6c37cfce25](https://linux-hardware.org/?probe=6c37cfce25) | Nov 06, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4777921b9b](https://linux-hardware.org/?probe=4777921b9b) | Nov 06, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a7c6078b6d](https://linux-hardware.org/?probe=a7c6078b6d) | Nov 06, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [912bfcc57e](https://linux-hardware.org/?probe=912bfcc57e) | Nov 06, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [a2d210c1c5](https://linux-hardware.org/?probe=a2d210c1c5) | Nov 06, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [d6313173c8](https://linux-hardware.org/?probe=d6313173c8) | Nov 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [317efeba98](https://linux-hardware.org/?probe=317efeba98) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | Notebook    | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [f13b221630](https://linux-hardware.org/?probe=f13b221630) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [55d115647e](https://linux-hardware.org/?probe=55d115647e) | Nov 06, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [ec4fd96563](https://linux-hardware.org/?probe=ec4fd96563) | Nov 06, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [4c9e9f49aa](https://linux-hardware.org/?probe=4c9e9f49aa) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [958f0c8551](https://linux-hardware.org/?probe=958f0c8551) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [578079d456](https://linux-hardware.org/?probe=578079d456) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| Acer          | Aspire 5741G                | Notebook    | [10c1cb72e2](https://linux-hardware.org/?probe=10c1cb72e2) | Nov 05, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [10170218bb](https://linux-hardware.org/?probe=10170218bb) | Nov 05, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [309c12cc50](https://linux-hardware.org/?probe=309c12cc50) | Nov 05, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [6479b746b8](https://linux-hardware.org/?probe=6479b746b8) | Nov 05, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| Google        | Sasuke                      | Notebook    | [216a160b84](https://linux-hardware.org/?probe=216a160b84) | Nov 05, 2022 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [56d14a3b3f](https://linux-hardware.org/?probe=56d14a3b3f) | Nov 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1534af11b9](https://linux-hardware.org/?probe=1534af11b9) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| HP            | 8053                        | Desktop     | [20c566d4e7](https://linux-hardware.org/?probe=20c566d4e7) | Nov 05, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [0c65bd2797](https://linux-hardware.org/?probe=0c65bd2797) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| Dell          | Inspiron 7570               | Notebook    | [158f7b0bcd](https://linux-hardware.org/?probe=158f7b0bcd) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| HP            | Pro x2 410 G1 PC            | Notebook    | [9ac029fa2c](https://linux-hardware.org/?probe=9ac029fa2c) | Nov 05, 2022 |
| HP            | Pro x2 410 G1 PC            | Notebook    | [6b6622e981](https://linux-hardware.org/?probe=6b6622e981) | Nov 05, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [204c296466](https://linux-hardware.org/?probe=204c296466) | Nov 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6494c493cb](https://linux-hardware.org/?probe=6494c493cb) | Nov 04, 2022 |
| HP            | Spectre x360 Conv 15        | Convertible | [f1d5f7705f](https://linux-hardware.org/?probe=f1d5f7705f) | Nov 04, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [809577d2bb](https://linux-hardware.org/?probe=809577d2bb) | Nov 04, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [78b49e6f73](https://linux-hardware.org/?probe=78b49e6f73) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [3614ee4149](https://linux-hardware.org/?probe=3614ee4149) | Nov 04, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [6a9cb1ae1d](https://linux-hardware.org/?probe=6a9cb1ae1d) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [c58816cb3d](https://linux-hardware.org/?probe=c58816cb3d) | Nov 04, 2022 |
| Lenovo        | B50-45 80F0                 | Notebook    | [2d36803ec6](https://linux-hardware.org/?probe=2d36803ec6) | Nov 04, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [72b1a49ec9](https://linux-hardware.org/?probe=72b1a49ec9) | Nov 04, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [99e32a37ff](https://linux-hardware.org/?probe=99e32a37ff) | Nov 04, 2022 |
| ASUSTek       | ROG Strix G513IE_G513IE     | Notebook    | [1d1783ca36](https://linux-hardware.org/?probe=1d1783ca36) | Nov 04, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [2101c9063a](https://linux-hardware.org/?probe=2101c9063a) | Nov 04, 2022 |
| ASUSTek       | ROG Strix G513IE_G513IE     | Notebook    | [1333104aae](https://linux-hardware.org/?probe=1333104aae) | Nov 04, 2022 |
| ASUSTek       | Unknown                     | Notebook    | [f1a58eaa87](https://linux-hardware.org/?probe=f1a58eaa87) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [17157970ee](https://linux-hardware.org/?probe=17157970ee) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [7479ad8a79](https://linux-hardware.org/?probe=7479ad8a79) | Nov 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [d04fddb1cc](https://linux-hardware.org/?probe=d04fddb1cc) | Nov 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [9cb27611ff](https://linux-hardware.org/?probe=9cb27611ff) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [b46456d0c2](https://linux-hardware.org/?probe=b46456d0c2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [e57ec28998](https://linux-hardware.org/?probe=e57ec28998) | Nov 03, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [4599565d35](https://linux-hardware.org/?probe=4599565d35) | Nov 03, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [97d8c001ef](https://linux-hardware.org/?probe=97d8c001ef) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [2c28f25521](https://linux-hardware.org/?probe=2c28f25521) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [0847d7c7e6](https://linux-hardware.org/?probe=0847d7c7e6) | Nov 03, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | Desktop     | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [7c6f7aa3e8](https://linux-hardware.org/?probe=7c6f7aa3e8) | Nov 03, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Dell          | 0W5363                      | Desktop     | [20c6f0d689](https://linux-hardware.org/?probe=20c6f0d689) | Nov 03, 2022 |
| Dell          | Latitude 7280               | Notebook    | [ec1ac4ec28](https://linux-hardware.org/?probe=ec1ac4ec28) | Nov 03, 2022 |
| Dell          | 0W5363                      | Desktop     | [7400a9beb1](https://linux-hardware.org/?probe=7400a9beb1) | Nov 03, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [f4de2cf149](https://linux-hardware.org/?probe=f4de2cf149) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430 23501B6       | Notebook    | [f059837f31](https://linux-hardware.org/?probe=f059837f31) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | Notebook    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e2f82d9c90](https://linux-hardware.org/?probe=e2f82d9c90) | Nov 03, 2022 |
| Microtech     | CoreBook                    | Notebook    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [ec7425c123](https://linux-hardware.org/?probe=ec7425c123) | Nov 03, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [2bab719066](https://linux-hardware.org/?probe=2bab719066) | Nov 03, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e4206174ca](https://linux-hardware.org/?probe=e4206174ca) | Nov 03, 2022 |
| Lenovo        | ThinkPad Edge E530 3259M... | Notebook    | [2bca9d747b](https://linux-hardware.org/?probe=2bca9d747b) | Nov 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [695b3d82a7](https://linux-hardware.org/?probe=695b3d82a7) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [9b9e55c471](https://linux-hardware.org/?probe=9b9e55c471) | Nov 02, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [ccaedd7155](https://linux-hardware.org/?probe=ccaedd7155) | Nov 02, 2022 |
| ASUSTek       | H81T                        | Desktop     | [7598a634e6](https://linux-hardware.org/?probe=7598a634e6) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [a3b1926b7e](https://linux-hardware.org/?probe=a3b1926b7e) | Nov 02, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [dd24c26ffa](https://linux-hardware.org/?probe=dd24c26ffa) | Nov 02, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Laptop                      | Notebook    | [e1cd3de91a](https://linux-hardware.org/?probe=e1cd3de91a) | Nov 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| Dell          | 0GWHMW A01                  | Desktop     | [732eaeede7](https://linux-hardware.org/?probe=732eaeede7) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| HP            | G42                         | Notebook    | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Jumper        | EZbook                      | Notebook    | [08ec434199](https://linux-hardware.org/?probe=08ec434199) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | Notebook    | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [961f664871](https://linux-hardware.org/?probe=961f664871) | Nov 02, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [f22ebdf694](https://linux-hardware.org/?probe=f22ebdf694) | Nov 01, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [a27142d25c](https://linux-hardware.org/?probe=a27142d25c) | Nov 01, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | Notebook    | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Dell          | Precision 7530              | Notebook    | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| HP            | ProBook 4530s               | Notebook    | [34682f3bfe](https://linux-hardware.org/?probe=34682f3bfe) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | Notebook    | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| MSI           | B75A-IE35                   | Desktop     | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| Lenovo        | ThinkPad L590 20Q7001KIX    | Notebook    | [c8e545615f](https://linux-hardware.org/?probe=c8e545615f) | Nov 01, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| ASUSTek       | BM2AD_D510MT_D310MT         | Desktop     | [8f2b0bc926](https://linux-hardware.org/?probe=8f2b0bc926) | Nov 01, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [921b1a7ebf](https://linux-hardware.org/?probe=921b1a7ebf) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [fd97cf3ecb](https://linux-hardware.org/?probe=fd97cf3ecb) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | Notebook    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a14fa00a56](https://linux-hardware.org/?probe=a14fa00a56) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bfa1db2eb1](https://linux-hardware.org/?probe=bfa1db2eb1) | Nov 01, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [ca5a47c66a](https://linux-hardware.org/?probe=ca5a47c66a) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [d39c952932](https://linux-hardware.org/?probe=d39c952932) | Nov 01, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [2532d13f74](https://linux-hardware.org/?probe=2532d13f74) | Nov 01, 2022 |
| Dell          | Precision 3510              | Notebook    | [a87bb1e8dd](https://linux-hardware.org/?probe=a87bb1e8dd) | Nov 01, 2022 |
| Acer          | Aspire one                  | Notebook    | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [0301f1ddf1](https://linux-hardware.org/?probe=0301f1ddf1) | Oct 31, 2022 |
| Acer          | Aspire V5-561G              | Notebook    | [ea7f8f381b](https://linux-hardware.org/?probe=ea7f8f381b) | Oct 31, 2022 |
| SANTECH       | NL5xRU                      | Notebook    | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| ASUSTek       | CG8480                      | Desktop     | [0f7c1dc1cf](https://linux-hardware.org/?probe=0f7c1dc1cf) | Oct 31, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [ced3229025](https://linux-hardware.org/?probe=ced3229025) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [71eeeaef9e](https://linux-hardware.org/?probe=71eeeaef9e) | Oct 31, 2022 |
| HP            | 3397                        | Desktop     | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [027cfb43c4](https://linux-hardware.org/?probe=027cfb43c4) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [113930496e](https://linux-hardware.org/?probe=113930496e) | Oct 31, 2022 |
| Acer          | Aspire one                  | Notebook    | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [e309413fea](https://linux-hardware.org/?probe=e309413fea) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2934bab108](https://linux-hardware.org/?probe=2934bab108) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [13741c554f](https://linux-hardware.org/?probe=13741c554f) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e6e466cd8f](https://linux-hardware.org/?probe=e6e466cd8f) | Oct 31, 2022 |
| MSI           | 990FXA-GD80                 | Desktop     | [baaa1111ec](https://linux-hardware.org/?probe=baaa1111ec) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge E530 3259M... | Notebook    | [aa1f78db58](https://linux-hardware.org/?probe=aa1f78db58) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge E530 3259M... | Notebook    | [26b5f59993](https://linux-hardware.org/?probe=26b5f59993) | Oct 31, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [600587e66a](https://linux-hardware.org/?probe=600587e66a) | Oct 31, 2022 |
| Acer          | Nitro AN517-55              | Notebook    | [9653f093e1](https://linux-hardware.org/?probe=9653f093e1) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3fbcca75d5](https://linux-hardware.org/?probe=3fbcca75d5) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [08cf9e2ccd](https://linux-hardware.org/?probe=08cf9e2ccd) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [209fa66bb9](https://linux-hardware.org/?probe=209fa66bb9) | Oct 30, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [c128f85cdc](https://linux-hardware.org/?probe=c128f85cdc) | Oct 30, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| HP            | x2 210                      | Notebook    | [8ed0a97ee9](https://linux-hardware.org/?probe=8ed0a97ee9) | Oct 30, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [f8c58b7061](https://linux-hardware.org/?probe=f8c58b7061) | Oct 30, 2022 |
| Sony          | VAIO                        | All in one  | [b295b1cb6f](https://linux-hardware.org/?probe=b295b1cb6f) | Oct 30, 2022 |
| Chuwi         | LarkBox X                   | Mini pc     | [5cd057be2a](https://linux-hardware.org/?probe=5cd057be2a) | Oct 30, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [10aa435a0b](https://linux-hardware.org/?probe=10aa435a0b) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [e28a25b18a](https://linux-hardware.org/?probe=e28a25b18a) | Oct 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [1f7df5159e](https://linux-hardware.org/?probe=1f7df5159e) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [faa61ea635](https://linux-hardware.org/?probe=faa61ea635) | Oct 30, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | Desktop     | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [89595b2fa9](https://linux-hardware.org/?probe=89595b2fa9) | Oct 30, 2022 |
| HP            | 1495                        | Desktop     | [b62f9d83b9](https://linux-hardware.org/?probe=b62f9d83b9) | Oct 30, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [80d6d99bcf](https://linux-hardware.org/?probe=80d6d99bcf) | Oct 30, 2022 |
| Intel         | NUC7i7BNB J31145-314        | Mini pc     | [9fd1f28183](https://linux-hardware.org/?probe=9fd1f28183) | Oct 30, 2022 |
| HP            | ProBook 6560b               | Notebook    | [89feda4b09](https://linux-hardware.org/?probe=89feda4b09) | Oct 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [4e4e0ac802](https://linux-hardware.org/?probe=4e4e0ac802) | Oct 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [8887bce606](https://linux-hardware.org/?probe=8887bce606) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [69198e503e](https://linux-hardware.org/?probe=69198e503e) | Oct 29, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [f6b00cb10f](https://linux-hardware.org/?probe=f6b00cb10f) | Oct 29, 2022 |
| Toshiba       | Satellite L50-A-1D6         | Notebook    | [77f308d89c](https://linux-hardware.org/?probe=77f308d89c) | Oct 29, 2022 |
| HP            | 18E7                        | Desktop     | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [f54f6d6354](https://linux-hardware.org/?probe=f54f6d6354) | Oct 29, 2022 |
| SANTECH       | PCx0Dx                      | Notebook    | [24462321e8](https://linux-hardware.org/?probe=24462321e8) | Oct 29, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6549416d9d](https://linux-hardware.org/?probe=6549416d9d) | Oct 29, 2022 |
| Dell          | Precision 3570              | Notebook    | [fb016d8d01](https://linux-hardware.org/?probe=fb016d8d01) | Oct 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1925c8ce1f](https://linux-hardware.org/?probe=1925c8ce1f) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| Dell          | Precision 3510              | Notebook    | [bc9324156f](https://linux-hardware.org/?probe=bc9324156f) | Oct 29, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [20d95ce78c](https://linux-hardware.org/?probe=20d95ce78c) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| HP            | Pavilion dv5                | Notebook    | [8bd42e12c3](https://linux-hardware.org/?probe=8bd42e12c3) | Oct 29, 2022 |
| ASRock        | 890GX Extreme3              | Desktop     | [ff1af2eaf0](https://linux-hardware.org/?probe=ff1af2eaf0) | Oct 29, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [6555e01443](https://linux-hardware.org/?probe=6555e01443) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [f51161d005](https://linux-hardware.org/?probe=f51161d005) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [4c4e1b6871](https://linux-hardware.org/?probe=4c4e1b6871) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [ffb4369f83](https://linux-hardware.org/?probe=ffb4369f83) | Oct 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [be41a03a4d](https://linux-hardware.org/?probe=be41a03a4d) | Oct 29, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [b3dd383a83](https://linux-hardware.org/?probe=b3dd383a83) | Oct 29, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [95af9b0439](https://linux-hardware.org/?probe=95af9b0439) | Oct 29, 2022 |
| Insyde        | Braswell                    | Notebook    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [e3662dc3bd](https://linux-hardware.org/?probe=e3662dc3bd) | Oct 29, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [7b414a3c7c](https://linux-hardware.org/?probe=7b414a3c7c) | Oct 29, 2022 |
| HP            | Pavilion dv6                | Notebook    | [6406b8b769](https://linux-hardware.org/?probe=6406b8b769) | Oct 29, 2022 |
| HP            | Pavilion dv6                | Notebook    | [7873dfb4cf](https://linux-hardware.org/?probe=7873dfb4cf) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [880d3ba9c9](https://linux-hardware.org/?probe=880d3ba9c9) | Oct 29, 2022 |
| Dell          | Latitude 5531               | Notebook    | [cdea65fd5c](https://linux-hardware.org/?probe=cdea65fd5c) | Oct 29, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [0d76cc7e31](https://linux-hardware.org/?probe=0d76cc7e31) | Oct 29, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [4ead64f80f](https://linux-hardware.org/?probe=4ead64f80f) | Oct 28, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [d3043c50ae](https://linux-hardware.org/?probe=d3043c50ae) | Oct 28, 2022 |
| Chuwi         | LapBook Pro                 | Notebook    | [d362ed14bf](https://linux-hardware.org/?probe=d362ed14bf) | Oct 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| MSI           | Prestige 15 A12UC           | Notebook    | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| Acer          | MCP7A                       | Desktop     | [c14a31f6ab](https://linux-hardware.org/?probe=c14a31f6ab) | Oct 28, 2022 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| Unknown       | 775V88+                     | Desktop     | [f1a685b497](https://linux-hardware.org/?probe=f1a685b497) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [7205cfe7b4](https://linux-hardware.org/?probe=7205cfe7b4) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [0696abd43c](https://linux-hardware.org/?probe=0696abd43c) | Oct 28, 2022 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | Desktop     | [8c85b7ec2e](https://linux-hardware.org/?probe=8c85b7ec2e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [d42867d201](https://linux-hardware.org/?probe=d42867d201) | Oct 28, 2022 |
| Dell          | Precision 3510              | Notebook    | [b1f2e24e41](https://linux-hardware.org/?probe=b1f2e24e41) | Oct 28, 2022 |
| Dell          | Precision 3510              | Notebook    | [bb81eb9627](https://linux-hardware.org/?probe=bb81eb9627) | Oct 28, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| MSI           | H81M-P33                    | Desktop     | [16a78334cd](https://linux-hardware.org/?probe=16a78334cd) | Oct 28, 2022 |
| Lenovo        | ThinkPad P52 20M9S1EM00     | Notebook    | [40de74c5c5](https://linux-hardware.org/?probe=40de74c5c5) | Oct 28, 2022 |
| Microsoft     | Surface Go 2                | Tablet      | [b720c57302](https://linux-hardware.org/?probe=b720c57302) | Oct 28, 2022 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [cbf597cec1](https://linux-hardware.org/?probe=cbf597cec1) | Oct 28, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e06398e1bc](https://linux-hardware.org/?probe=e06398e1bc) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [83179a6cea](https://linux-hardware.org/?probe=83179a6cea) | Oct 28, 2022 |
| Dell          | Latitude 5521               | Notebook    | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7d99f01f0e](https://linux-hardware.org/?probe=7d99f01f0e) | Oct 28, 2022 |
| Lenovo        | ThinkPad W540 20BHS0730D    | Notebook    | [f24dc12e06](https://linux-hardware.org/?probe=f24dc12e06) | Oct 28, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [98b47019d1](https://linux-hardware.org/?probe=98b47019d1) | Oct 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ac6f0daea9](https://linux-hardware.org/?probe=ac6f0daea9) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | Desktop     | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| MSI           | Modern 14 B10RBSW           | Notebook    | [9c3c17a82e](https://linux-hardware.org/?probe=9c3c17a82e) | Oct 28, 2022 |
| Lenovo        | 3172 NOK                    | Mini pc     | [1ddbbf71eb](https://linux-hardware.org/?probe=1ddbbf71eb) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1759cbebe1](https://linux-hardware.org/?probe=1759cbebe1) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6314ec0dd1](https://linux-hardware.org/?probe=6314ec0dd1) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [f575803f23](https://linux-hardware.org/?probe=f575803f23) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [fc35e765fd](https://linux-hardware.org/?probe=fc35e765fd) | Oct 28, 2022 |
| MSI           | Katana GF66 11UC            | Notebook    | [83088617d3](https://linux-hardware.org/?probe=83088617d3) | Oct 28, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [db8c0489f4](https://linux-hardware.org/?probe=db8c0489f4) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [033cc83715](https://linux-hardware.org/?probe=033cc83715) | Oct 28, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [176fa68922](https://linux-hardware.org/?probe=176fa68922) | Oct 28, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [85019658e9](https://linux-hardware.org/?probe=85019658e9) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1d64fb48e7](https://linux-hardware.org/?probe=1d64fb48e7) | Oct 27, 2022 |
| Timi          | TM1701                      | Notebook    | [f246345845](https://linux-hardware.org/?probe=f246345845) | Oct 27, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [53832f0517](https://linux-hardware.org/?probe=53832f0517) | Oct 27, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [30d97ad99e](https://linux-hardware.org/?probe=30d97ad99e) | Oct 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [a03935aadd](https://linux-hardware.org/?probe=a03935aadd) | Oct 27, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8cf00ceef5](https://linux-hardware.org/?probe=8cf00ceef5) | Oct 27, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [99f9bbd5ad](https://linux-hardware.org/?probe=99f9bbd5ad) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [639503102e](https://linux-hardware.org/?probe=639503102e) | Oct 27, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [d3c4092754](https://linux-hardware.org/?probe=d3c4092754) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [3a9f97607d](https://linux-hardware.org/?probe=3a9f97607d) | Oct 27, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| Packard Be... | IMEDIA S3810                | Desktop     | [f492fb9369](https://linux-hardware.org/?probe=f492fb9369) | Oct 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [069ce9d405](https://linux-hardware.org/?probe=069ce9d405) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [36b663cec7](https://linux-hardware.org/?probe=36b663cec7) | Oct 27, 2022 |
| MSI           | H81M-E33                    | Desktop     | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [e00fd51503](https://linux-hardware.org/?probe=e00fd51503) | Oct 27, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [664bf1184f](https://linux-hardware.org/?probe=664bf1184f) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| Dell          | Latitude 9420               | Notebook    | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [1e14922876](https://linux-hardware.org/?probe=1e14922876) | Oct 27, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [0c037323d9](https://linux-hardware.org/?probe=0c037323d9) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| HP            | ProBook 6560b               | Notebook    | [222a5c2dbe](https://linux-hardware.org/?probe=222a5c2dbe) | Oct 27, 2022 |
| MSI           | X58 Pro                     | Desktop     | [6c449246c8](https://linux-hardware.org/?probe=6c449246c8) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [670823778e](https://linux-hardware.org/?probe=670823778e) | Oct 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7be37b6a2d](https://linux-hardware.org/?probe=7be37b6a2d) | Oct 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [19859b5baf](https://linux-hardware.org/?probe=19859b5baf) | Oct 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b682a38061](https://linux-hardware.org/?probe=b682a38061) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| MSI           | MS-B1061                    | All in one  | [6a736e8849](https://linux-hardware.org/?probe=6a736e8849) | Oct 27, 2022 |
| Lenovo        | Yoga 720-13IKB              | Convertible | [1ca9551d4d](https://linux-hardware.org/?probe=1ca9551d4d) | Oct 27, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [b51a20d480](https://linux-hardware.org/?probe=b51a20d480) | Oct 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [810ec3e083](https://linux-hardware.org/?probe=810ec3e083) | Oct 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0d31bc8f88](https://linux-hardware.org/?probe=0d31bc8f88) | Oct 27, 2022 |
| HP            | 1589                        | Desktop     | [4a15b6de0f](https://linux-hardware.org/?probe=4a15b6de0f) | Oct 27, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [9b8f917e6b](https://linux-hardware.org/?probe=9b8f917e6b) | Oct 27, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [f1a5637218](https://linux-hardware.org/?probe=f1a5637218) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [51877edd1e](https://linux-hardware.org/?probe=51877edd1e) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aca9e00b3d](https://linux-hardware.org/?probe=aca9e00b3d) | Oct 27, 2022 |
| Lenovo        | ThinkPad X260 20F5S2WX05    | Notebook    | [710f95eab8](https://linux-hardware.org/?probe=710f95eab8) | Oct 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5YM0... | Notebook    | [c348de09bf](https://linux-hardware.org/?probe=c348de09bf) | Oct 26, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [0d705b0971](https://linux-hardware.org/?probe=0d705b0971) | Oct 26, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [4aa258716b](https://linux-hardware.org/?probe=4aa258716b) | Oct 26, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [26d1b8b2b2](https://linux-hardware.org/?probe=26d1b8b2b2) | Oct 26, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [44d47f5024](https://linux-hardware.org/?probe=44d47f5024) | Oct 26, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [85b4bc70fa](https://linux-hardware.org/?probe=85b4bc70fa) | Oct 26, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [25765f4a76](https://linux-hardware.org/?probe=25765f4a76) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [82fcc1ecc7](https://linux-hardware.org/?probe=82fcc1ecc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad T480 20L50000IX    | Notebook    | [bcb1b11c50](https://linux-hardware.org/?probe=bcb1b11c50) | Oct 26, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [03fc94fc36](https://linux-hardware.org/?probe=03fc94fc36) | Oct 26, 2022 |
| Intel         | H55                         | Desktop     | [f634aefb9a](https://linux-hardware.org/?probe=f634aefb9a) | Oct 26, 2022 |
| MSI           | ZH77A-G43                   | Desktop     | [ff43c876e9](https://linux-hardware.org/?probe=ff43c876e9) | Oct 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [469345600b](https://linux-hardware.org/?probe=469345600b) | Oct 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [d4ebaa71a2](https://linux-hardware.org/?probe=d4ebaa71a2) | Oct 26, 2022 |
| Acer          | Extensa 2540                | Notebook    | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [06f33f301b](https://linux-hardware.org/?probe=06f33f301b) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8a718e0ade](https://linux-hardware.org/?probe=8a718e0ade) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | Notebook    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [94d8bc13bb](https://linux-hardware.org/?probe=94d8bc13bb) | Oct 26, 2022 |
| Timi          | A7S                         | Notebook    | [004df6b9a1](https://linux-hardware.org/?probe=004df6b9a1) | Oct 26, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [60d57edbfb](https://linux-hardware.org/?probe=60d57edbfb) | Oct 26, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [1ede815931](https://linux-hardware.org/?probe=1ede815931) | Oct 26, 2022 |
| Lenovo        | ThinkPad T450 20BUS0S902    | Notebook    | [1115da2433](https://linux-hardware.org/?probe=1115da2433) | Oct 26, 2022 |
| MSI           | Stealth GS66 12UH           | Notebook    | [3c985bb814](https://linux-hardware.org/?probe=3c985bb814) | Oct 26, 2022 |
| MSI           | Stealth GS66 12UH           | Notebook    | [336132b016](https://linux-hardware.org/?probe=336132b016) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | Desktop     | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| HP            | 1494                        | Desktop     | [fa63090109](https://linux-hardware.org/?probe=fa63090109) | Oct 26, 2022 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [1d55c9b411](https://linux-hardware.org/?probe=1d55c9b411) | Oct 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b05308c0f0](https://linux-hardware.org/?probe=b05308c0f0) | Oct 26, 2022 |
| Dell          | Latitude E5570              | Notebook    | [2d59f069b4](https://linux-hardware.org/?probe=2d59f069b4) | Oct 26, 2022 |
| HP            | 8509                        | Desktop     | [81bfb5a782](https://linux-hardware.org/?probe=81bfb5a782) | Oct 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [40447b0a52](https://linux-hardware.org/?probe=40447b0a52) | Oct 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [040b99188b](https://linux-hardware.org/?probe=040b99188b) | Oct 26, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [5265f4d89f](https://linux-hardware.org/?probe=5265f4d89f) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [4b28c73302](https://linux-hardware.org/?probe=4b28c73302) | Oct 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7b20f93496](https://linux-hardware.org/?probe=7b20f93496) | Oct 26, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [042ffc026d](https://linux-hardware.org/?probe=042ffc026d) | Oct 26, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [0a658be9fc](https://linux-hardware.org/?probe=0a658be9fc) | Oct 26, 2022 |
| Timi          | A7S                         | Notebook    | [77a87009dd](https://linux-hardware.org/?probe=77a87009dd) | Oct 26, 2022 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [1ded224c69](https://linux-hardware.org/?probe=1ded224c69) | Oct 26, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [53e6b23ebf](https://linux-hardware.org/?probe=53e6b23ebf) | Oct 26, 2022 |
| Dell          | Inspiron 7586               | Convertible | [1cc713f6d8](https://linux-hardware.org/?probe=1cc713f6d8) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [705e51d33e](https://linux-hardware.org/?probe=705e51d33e) | Oct 25, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [50c68d9bb4](https://linux-hardware.org/?probe=50c68d9bb4) | Oct 25, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [a48316f550](https://linux-hardware.org/?probe=a48316f550) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [824eb583d8](https://linux-hardware.org/?probe=824eb583d8) | Oct 25, 2022 |
| Samsung       | 767XCL                      | Notebook    | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f196a9762f](https://linux-hardware.org/?probe=f196a9762f) | Oct 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8062ec17fd](https://linux-hardware.org/?probe=8062ec17fd) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2d7fa062e3](https://linux-hardware.org/?probe=2d7fa062e3) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| HP            | Pavilion dv6                | Notebook    | [03e2594419](https://linux-hardware.org/?probe=03e2594419) | Oct 25, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [72532e08fe](https://linux-hardware.org/?probe=72532e08fe) | Oct 25, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [da04330684](https://linux-hardware.org/?probe=da04330684) | Oct 25, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [5f9de95e9c](https://linux-hardware.org/?probe=5f9de95e9c) | Oct 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [264fcfd9f1](https://linux-hardware.org/?probe=264fcfd9f1) | Oct 25, 2022 |
| Dell          | Precision M6800             | Notebook    | [6c15780d7a](https://linux-hardware.org/?probe=6c15780d7a) | Oct 25, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b35333d9c0](https://linux-hardware.org/?probe=b35333d9c0) | Oct 25, 2022 |
| HP            | ENVY 15                     | Notebook    | [faf3ff2256](https://linux-hardware.org/?probe=faf3ff2256) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [cca91f3fe8](https://linux-hardware.org/?probe=cca91f3fe8) | Oct 25, 2022 |
| Dell          | Latitude E7270              | Notebook    | [7f2c8b9e9c](https://linux-hardware.org/?probe=7f2c8b9e9c) | Oct 25, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [06c00dc8d5](https://linux-hardware.org/?probe=06c00dc8d5) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [8f34a9c24c](https://linux-hardware.org/?probe=8f34a9c24c) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [a8c29545e6](https://linux-hardware.org/?probe=a8c29545e6) | Oct 25, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [82ee095168](https://linux-hardware.org/?probe=82ee095168) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [a38f9baa55](https://linux-hardware.org/?probe=a38f9baa55) | Oct 25, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [6764a6860f](https://linux-hardware.org/?probe=6764a6860f) | Oct 25, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [b5dcdb6844](https://linux-hardware.org/?probe=b5dcdb6844) | Oct 25, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [be4e6c1903](https://linux-hardware.org/?probe=be4e6c1903) | Oct 25, 2022 |
| Sony          | VAIO                        | All in one  | [27e76b1c76](https://linux-hardware.org/?probe=27e76b1c76) | Oct 25, 2022 |
| ASRock        | 4Core1600-GLAN/M            | Desktop     | [33bf20761f](https://linux-hardware.org/?probe=33bf20761f) | Oct 25, 2022 |
| Unknown       | 1.0                         | Desktop     | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| Pegatron      | Benicia                     | Desktop     | [3735dca311](https://linux-hardware.org/?probe=3735dca311) | Oct 25, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [1f939e0414](https://linux-hardware.org/?probe=1f939e0414) | Oct 25, 2022 |
| IBM           | 81Y7045                     | Server      | [27bd1ebecd](https://linux-hardware.org/?probe=27bd1ebecd) | Oct 25, 2022 |
| Dell          | Latitude 5500               | Notebook    | [6e1b321740](https://linux-hardware.org/?probe=6e1b321740) | Oct 25, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [badb0d5aee](https://linux-hardware.org/?probe=badb0d5aee) | Oct 25, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f4174b55a2](https://linux-hardware.org/?probe=f4174b55a2) | Oct 25, 2022 |
| HP            | 805F                        | Desktop     | [eaa3994f86](https://linux-hardware.org/?probe=eaa3994f86) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [485025af1a](https://linux-hardware.org/?probe=485025af1a) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [ab5d5a6170](https://linux-hardware.org/?probe=ab5d5a6170) | Oct 25, 2022 |
| LG Electro... | 17Z90N-V.AA55D              | Notebook    | [bf40de3f5a](https://linux-hardware.org/?probe=bf40de3f5a) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [040714e135](https://linux-hardware.org/?probe=040714e135) | Oct 25, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [a78a644cc1](https://linux-hardware.org/?probe=a78a644cc1) | Oct 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6a9d81591f](https://linux-hardware.org/?probe=6a9d81591f) | Oct 25, 2022 |
| Lenovo        | 318E NOK                    | Desktop     | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [72b73a6552](https://linux-hardware.org/?probe=72b73a6552) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b2bb88f27f](https://linux-hardware.org/?probe=b2bb88f27f) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [26415e4b74](https://linux-hardware.org/?probe=26415e4b74) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| HP            | 650                         | Notebook    | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [ef9fdf5dcd](https://linux-hardware.org/?probe=ef9fdf5dcd) | Oct 25, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [2a1b8eb060](https://linux-hardware.org/?probe=2a1b8eb060) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ca207e0798](https://linux-hardware.org/?probe=ca207e0798) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| Dell          | Precision 3530              | Notebook    | [8d806f9e53](https://linux-hardware.org/?probe=8d806f9e53) | Oct 25, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [f8aa3a7277](https://linux-hardware.org/?probe=f8aa3a7277) | Oct 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [30c305f07c](https://linux-hardware.org/?probe=30c305f07c) | Oct 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3146a3d644](https://linux-hardware.org/?probe=3146a3d644) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [1c68e176b6](https://linux-hardware.org/?probe=1c68e176b6) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [0c13fbf129](https://linux-hardware.org/?probe=0c13fbf129) | Oct 25, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [6cffc39cfc](https://linux-hardware.org/?probe=6cffc39cfc) | Oct 25, 2022 |
| PC Special... | N13xWU                      | Notebook    | [4d728f13c9](https://linux-hardware.org/?probe=4d728f13c9) | Oct 25, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [c3008c5d9a](https://linux-hardware.org/?probe=c3008c5d9a) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7f9028d036](https://linux-hardware.org/?probe=7f9028d036) | Oct 25, 2022 |
| PC Special... | N13xWU                      | Notebook    | [58b775c64c](https://linux-hardware.org/?probe=58b775c64c) | Oct 25, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [86b8ce83b2](https://linux-hardware.org/?probe=86b8ce83b2) | Oct 25, 2022 |
| Lenovo        | FLEX5 81X2                  | Convertible | [fcaaf240af](https://linux-hardware.org/?probe=fcaaf240af) | Oct 25, 2022 |
| Lenovo        | FLEX5 81X2                  | Convertible | [6416af743e](https://linux-hardware.org/?probe=6416af743e) | Oct 25, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a26efdcfb5](https://linux-hardware.org/?probe=a26efdcfb5) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [811985183a](https://linux-hardware.org/?probe=811985183a) | Oct 25, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4e87fd9438](https://linux-hardware.org/?probe=4e87fd9438) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [b31fec75e1](https://linux-hardware.org/?probe=b31fec75e1) | Oct 25, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [4474edfd79](https://linux-hardware.org/?probe=4474edfd79) | Oct 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7b59865f68](https://linux-hardware.org/?probe=7b59865f68) | Oct 25, 2022 |
| Dell          | G15 5511                    | Notebook    | [0f47c64bab](https://linux-hardware.org/?probe=0f47c64bab) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [20278229cd](https://linux-hardware.org/?probe=20278229cd) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| Microsoft     | Surface Laptop 4            | Tablet      | [4bff3b131d](https://linux-hardware.org/?probe=4bff3b131d) | Oct 25, 2022 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| MSI           | Z97-G55 SLI                 | Desktop     | [25ddd5274f](https://linux-hardware.org/?probe=25ddd5274f) | Oct 25, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4584821ae6](https://linux-hardware.org/?probe=4584821ae6) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [74ca211759](https://linux-hardware.org/?probe=74ca211759) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [65060e7656](https://linux-hardware.org/?probe=65060e7656) | Oct 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [122a54b0c2](https://linux-hardware.org/?probe=122a54b0c2) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [169601c723](https://linux-hardware.org/?probe=169601c723) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [efb9c3d448](https://linux-hardware.org/?probe=efb9c3d448) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a55a6ef774](https://linux-hardware.org/?probe=a55a6ef774) | Oct 25, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [52a4b91a1e](https://linux-hardware.org/?probe=52a4b91a1e) | Oct 25, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [aaed1997fd](https://linux-hardware.org/?probe=aaed1997fd) | Oct 25, 2022 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [7e6d814d87](https://linux-hardware.org/?probe=7e6d814d87) | Oct 25, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [f827f47265](https://linux-hardware.org/?probe=f827f47265) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [42647c28ba](https://linux-hardware.org/?probe=42647c28ba) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [18931ec5f6](https://linux-hardware.org/?probe=18931ec5f6) | Oct 25, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [da7fe35832](https://linux-hardware.org/?probe=da7fe35832) | Oct 25, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [e176b2ac7c](https://linux-hardware.org/?probe=e176b2ac7c) | Oct 25, 2022 |
| MSI           | Z170A GAMING M7             | Desktop     | [3326f67ecf](https://linux-hardware.org/?probe=3326f67ecf) | Oct 25, 2022 |
| ASUSTek       | X555LI                      | Notebook    | [fe6b4aa2a6](https://linux-hardware.org/?probe=fe6b4aa2a6) | Oct 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [35cf015c33](https://linux-hardware.org/?probe=35cf015c33) | Oct 25, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [5a6d4ce6e7](https://linux-hardware.org/?probe=5a6d4ce6e7) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [dc70e52da3](https://linux-hardware.org/?probe=dc70e52da3) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [7c4edd1a6d](https://linux-hardware.org/?probe=7c4edd1a6d) | Oct 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| Sony          | SVE1712Z1EB                 | Notebook    | [23b6ac5cde](https://linux-hardware.org/?probe=23b6ac5cde) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [3fbd9c277d](https://linux-hardware.org/?probe=3fbd9c277d) | Oct 24, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [a0e0f661af](https://linux-hardware.org/?probe=a0e0f661af) | Oct 24, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [6560f717c9](https://linux-hardware.org/?probe=6560f717c9) | Oct 24, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [1bbbcd4843](https://linux-hardware.org/?probe=1bbbcd4843) | Oct 24, 2022 |
| Lenovo        | ThinkPad L380 Yoga 20M7C... | Convertible | [c9577d0d5a](https://linux-hardware.org/?probe=c9577d0d5a) | Oct 24, 2022 |
| Dell          | Inspiron 16 7610            | Notebook    | [96ae3c2941](https://linux-hardware.org/?probe=96ae3c2941) | Oct 24, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [02e8dbe21d](https://linux-hardware.org/?probe=02e8dbe21d) | Oct 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [15ced71b20](https://linux-hardware.org/?probe=15ced71b20) | Oct 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c6134bcca2](https://linux-hardware.org/?probe=c6134bcca2) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [a9235eda91](https://linux-hardware.org/?probe=a9235eda91) | Oct 24, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [f569841512](https://linux-hardware.org/?probe=f569841512) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [8994af98ff](https://linux-hardware.org/?probe=8994af98ff) | Oct 24, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [ad6b09bddc](https://linux-hardware.org/?probe=ad6b09bddc) | Oct 24, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [44375f0b06](https://linux-hardware.org/?probe=44375f0b06) | Oct 24, 2022 |
| Microsoft     | Surface Laptop 4            | Tablet      | [bdb6b876db](https://linux-hardware.org/?probe=bdb6b876db) | Oct 24, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [4948eb3b16](https://linux-hardware.org/?probe=4948eb3b16) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [1deed99314](https://linux-hardware.org/?probe=1deed99314) | Oct 24, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [ee86cdac2a](https://linux-hardware.org/?probe=ee86cdac2a) | Oct 24, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [aeae483e35](https://linux-hardware.org/?probe=aeae483e35) | Oct 24, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Notebook      | PCX0DX                      | Notebook    | [e29790dc3c](https://linux-hardware.org/?probe=e29790dc3c) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fc7326f81b](https://linux-hardware.org/?probe=fc7326f81b) | Oct 24, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [581fb21345](https://linux-hardware.org/?probe=581fb21345) | Oct 24, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [2510215a0b](https://linux-hardware.org/?probe=2510215a0b) | Oct 24, 2022 |
| MSI           | GE62 7RE                    | Notebook    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [c76c6f0a0e](https://linux-hardware.org/?probe=c76c6f0a0e) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [95ad909dc8](https://linux-hardware.org/?probe=95ad909dc8) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| Dell          | 0M5WNK A00                  | Desktop     | [fad0f2f50e](https://linux-hardware.org/?probe=fad0f2f50e) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9b7ac9b23e](https://linux-hardware.org/?probe=9b7ac9b23e) | Oct 24, 2022 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [e5264df501](https://linux-hardware.org/?probe=e5264df501) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b63ff47508](https://linux-hardware.org/?probe=b63ff47508) | Oct 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [aaf3b72437](https://linux-hardware.org/?probe=aaf3b72437) | Oct 24, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [d953ededc3](https://linux-hardware.org/?probe=d953ededc3) | Oct 24, 2022 |
| Olivetti      | Olibook P75B                | Notebook    | [a1b4023949](https://linux-hardware.org/?probe=a1b4023949) | Oct 24, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [dc8eab937b](https://linux-hardware.org/?probe=dc8eab937b) | Oct 24, 2022 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [43650773c9](https://linux-hardware.org/?probe=43650773c9) | Oct 24, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [905f41afd6](https://linux-hardware.org/?probe=905f41afd6) | Oct 24, 2022 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| HP            | 3048h                       | Desktop     | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [aea737fcab](https://linux-hardware.org/?probe=aea737fcab) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1dea808353](https://linux-hardware.org/?probe=1dea808353) | Oct 24, 2022 |
| Dell          | Latitude E5500              | Notebook    | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f4182ec2e9](https://linux-hardware.org/?probe=f4182ec2e9) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [e198c305e4](https://linux-hardware.org/?probe=e198c305e4) | Oct 24, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [d663683611](https://linux-hardware.org/?probe=d663683611) | Oct 24, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [506468af47](https://linux-hardware.org/?probe=506468af47) | Oct 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [417beae8e5](https://linux-hardware.org/?probe=417beae8e5) | Oct 24, 2022 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [93068b4cf8](https://linux-hardware.org/?probe=93068b4cf8) | Oct 24, 2022 |
| Packard Be... | DOT S                       | Notebook    | [f280a6ccbc](https://linux-hardware.org/?probe=f280a6ccbc) | Oct 24, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [19ccd70ee8](https://linux-hardware.org/?probe=19ccd70ee8) | Oct 24, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [01c09a61ae](https://linux-hardware.org/?probe=01c09a61ae) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0ca2dff493](https://linux-hardware.org/?probe=0ca2dff493) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [fb3feaef06](https://linux-hardware.org/?probe=fb3feaef06) | Oct 24, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [a1e654c422](https://linux-hardware.org/?probe=a1e654c422) | Oct 24, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [0ffbef18a5](https://linux-hardware.org/?probe=0ffbef18a5) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 232465G       | Notebook    | [4cfe90552b](https://linux-hardware.org/?probe=4cfe90552b) | Oct 24, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [a8ab16a5c5](https://linux-hardware.org/?probe=a8ab16a5c5) | Oct 24, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [164b8dd0d8](https://linux-hardware.org/?probe=164b8dd0d8) | Oct 24, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a6190e6271](https://linux-hardware.org/?probe=a6190e6271) | Oct 24, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [8ae3d6c328](https://linux-hardware.org/?probe=8ae3d6c328) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES4VB00    | Notebook    | [f7b39d371a](https://linux-hardware.org/?probe=f7b39d371a) | Oct 24, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [20dcade848](https://linux-hardware.org/?probe=20dcade848) | Oct 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [22a138a507](https://linux-hardware.org/?probe=22a138a507) | Oct 24, 2022 |
| HUAWEI        | MateBook D                  | Notebook    | [b219f88756](https://linux-hardware.org/?probe=b219f88756) | Oct 24, 2022 |
| Dell          | Latitude 7490               | Notebook    | [96759bdb49](https://linux-hardware.org/?probe=96759bdb49) | Oct 24, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [802e0f0c61](https://linux-hardware.org/?probe=802e0f0c61) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Dell          | 0RW199                      | Desktop     | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [37a0403fc9](https://linux-hardware.org/?probe=37a0403fc9) | Oct 24, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [5a928ace3b](https://linux-hardware.org/?probe=5a928ace3b) | Oct 24, 2022 |
| Dell          | Latitude E7240              | Notebook    | [33c37015df](https://linux-hardware.org/?probe=33c37015df) | Oct 24, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [9e56111afe](https://linux-hardware.org/?probe=9e56111afe) | Oct 24, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [7c960c6ce8](https://linux-hardware.org/?probe=7c960c6ce8) | Oct 24, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [b39d63f4f2](https://linux-hardware.org/?probe=b39d63f4f2) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [40f916420e](https://linux-hardware.org/?probe=40f916420e) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [753874362e](https://linux-hardware.org/?probe=753874362e) | Oct 23, 2022 |
| HP            | 3397                        | Desktop     | [6f58590d3d](https://linux-hardware.org/?probe=6f58590d3d) | Oct 23, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [406538a0de](https://linux-hardware.org/?probe=406538a0de) | Oct 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [8fec9e2536](https://linux-hardware.org/?probe=8fec9e2536) | Oct 22, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [7361aed7f9](https://linux-hardware.org/?probe=7361aed7f9) | Oct 22, 2022 |
| Acer          | Aspire 5733                 | Notebook    | [ef561df926](https://linux-hardware.org/?probe=ef561df926) | Oct 22, 2022 |
| Dell          | Latitude E6440              | Notebook    | [030896045a](https://linux-hardware.org/?probe=030896045a) | Oct 22, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [74c290e909](https://linux-hardware.org/?probe=74c290e909) | Oct 22, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [07fb028e18](https://linux-hardware.org/?probe=07fb028e18) | Oct 22, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [f460f8dc4e](https://linux-hardware.org/?probe=f460f8dc4e) | Oct 22, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [d0a1d2c4f5](https://linux-hardware.org/?probe=d0a1d2c4f5) | Oct 22, 2022 |
| MSI           | X58 Pro                     | Desktop     | [96db21189e](https://linux-hardware.org/?probe=96db21189e) | Oct 22, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [9ea661d3b9](https://linux-hardware.org/?probe=9ea661d3b9) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [c63a7ccdeb](https://linux-hardware.org/?probe=c63a7ccdeb) | Oct 21, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [86740d9460](https://linux-hardware.org/?probe=86740d9460) | Oct 21, 2022 |
| LG Electro... | 16Z90P-G.AP75D              | Notebook    | [1e1526e9d8](https://linux-hardware.org/?probe=1e1526e9d8) | Oct 21, 2022 |
| Lenovo        | ThinkPad E550 20DFCTO1WW    | Notebook    | [0249022aca](https://linux-hardware.org/?probe=0249022aca) | Oct 20, 2022 |
| ASUSTek       | P7P55-M                     | Desktop     | [3ff254b938](https://linux-hardware.org/?probe=3ff254b938) | Oct 20, 2022 |
| Acer          | One S1003                   | Tablet      | [304c23119d](https://linux-hardware.org/?probe=304c23119d) | Oct 20, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [68a04f2544](https://linux-hardware.org/?probe=68a04f2544) | Oct 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f966d5d584](https://linux-hardware.org/?probe=f966d5d584) | Oct 20, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d042d922e5](https://linux-hardware.org/?probe=d042d922e5) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [7640c7a49f](https://linux-hardware.org/?probe=7640c7a49f) | Oct 20, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e455bef105](https://linux-hardware.org/?probe=e455bef105) | Oct 20, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [e3fef524ee](https://linux-hardware.org/?probe=e3fef524ee) | Oct 20, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [f31749db41](https://linux-hardware.org/?probe=f31749db41) | Oct 20, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [8ae5de2c7d](https://linux-hardware.org/?probe=8ae5de2c7d) | Oct 20, 2022 |
| Sony          | SVE1513B1EW                 | Notebook    | [77ef0b542b](https://linux-hardware.org/?probe=77ef0b542b) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | Desktop     | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [87e23bcbe6](https://linux-hardware.org/?probe=87e23bcbe6) | Oct 19, 2022 |
| Dell          | 0HY175 A03                  | Desktop     | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| Microtech     | CoreBook                    | Notebook    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | Notebook    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| Dell          | Inspiron 7590               | Notebook    | [43ec5b2df8](https://linux-hardware.org/?probe=43ec5b2df8) | Oct 19, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | 805D                        | Desktop     | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [116fff483b](https://linux-hardware.org/?probe=116fff483b) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [1fbb05ae6b](https://linux-hardware.org/?probe=1fbb05ae6b) | Oct 18, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [20703ba8b3](https://linux-hardware.org/?probe=20703ba8b3) | Oct 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [08327d561d](https://linux-hardware.org/?probe=08327d561d) | Oct 18, 2022 |
| AZW           | SER V01                     | Mini pc     | [b106ebaef6](https://linux-hardware.org/?probe=b106ebaef6) | Oct 18, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [2c47736da1](https://linux-hardware.org/?probe=2c47736da1) | Oct 18, 2022 |
| MSI           | Summit E16Flip A11UCT       | Notebook    | [f1ec40e34d](https://linux-hardware.org/?probe=f1ec40e34d) | Oct 17, 2022 |
| HP            | 3048h                       | Desktop     | [624ad8a33c](https://linux-hardware.org/?probe=624ad8a33c) | Oct 17, 2022 |
| HP            | 3048h                       | Desktop     | [1b3d31f720](https://linux-hardware.org/?probe=1b3d31f720) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [a1e9be5323](https://linux-hardware.org/?probe=a1e9be5323) | Oct 17, 2022 |
| Lenovo        | ThinkPad T60 1952CTO        | Notebook    | [f84f14587b](https://linux-hardware.org/?probe=f84f14587b) | Oct 17, 2022 |
| Samsung       | R509                        | Notebook    | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| HP            | 255 G3                      | Notebook    | [a6ef9f4649](https://linux-hardware.org/?probe=a6ef9f4649) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [76a82ca1e6](https://linux-hardware.org/?probe=76a82ca1e6) | Oct 17, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [594b141136](https://linux-hardware.org/?probe=594b141136) | Oct 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [57436f7d31](https://linux-hardware.org/?probe=57436f7d31) | Oct 17, 2022 |
| Notebook      | W230SS                      | Notebook    | [abb5e7fda8](https://linux-hardware.org/?probe=abb5e7fda8) | Oct 16, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [5c38639fff](https://linux-hardware.org/?probe=5c38639fff) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0cceedcb07](https://linux-hardware.org/?probe=0cceedcb07) | Oct 16, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [eae5ab7d9c](https://linux-hardware.org/?probe=eae5ab7d9c) | Oct 16, 2022 |
| MSI           | MS-B1711                    | Desktop     | [231d1c3373](https://linux-hardware.org/?probe=231d1c3373) | Oct 16, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [4aff854065](https://linux-hardware.org/?probe=4aff854065) | Oct 16, 2022 |
| MSI           | MS-B1711                    | Desktop     | [964bad6988](https://linux-hardware.org/?probe=964bad6988) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Packard Be... | IMEDIA S3712                | Desktop     | [d9aa81c4c3](https://linux-hardware.org/?probe=d9aa81c4c3) | Oct 15, 2022 |
| ASUSTek       | H87M-PRO                    | Desktop     | [4f1304fbdd](https://linux-hardware.org/?probe=4f1304fbdd) | Oct 15, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [7a8b3b953d](https://linux-hardware.org/?probe=7a8b3b953d) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b1eab51bd7](https://linux-hardware.org/?probe=b1eab51bd7) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | X555UA                      | Notebook    | [f0adae0aba](https://linux-hardware.org/?probe=f0adae0aba) | Oct 14, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4fbce46637](https://linux-hardware.org/?probe=4fbce46637) | Oct 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [afe4e30588](https://linux-hardware.org/?probe=afe4e30588) | Oct 14, 2022 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [39fee1c62f](https://linux-hardware.org/?probe=39fee1c62f) | Oct 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ea66320118](https://linux-hardware.org/?probe=ea66320118) | Oct 14, 2022 |
| Intel         | STK2MV64CC H89290-502       | Desktop     | [85670dc1fe](https://linux-hardware.org/?probe=85670dc1fe) | Oct 14, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| Dell          | Studio 1555                 | Notebook    | [52104abe69](https://linux-hardware.org/?probe=52104abe69) | Oct 13, 2022 |
| HP            | EliteBook x360 1020 G2      | Convertible | [02dbb4bfa3](https://linux-hardware.org/?probe=02dbb4bfa3) | Oct 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [e2db064195](https://linux-hardware.org/?probe=e2db064195) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [273721cef2](https://linux-hardware.org/?probe=273721cef2) | Oct 12, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [457bef52a9](https://linux-hardware.org/?probe=457bef52a9) | Oct 12, 2022 |
| Supermicro    | C7P67                       | Desktop     | [70613229ac](https://linux-hardware.org/?probe=70613229ac) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [df55c5c266](https://linux-hardware.org/?probe=df55c5c266) | Oct 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [00d174fcf4](https://linux-hardware.org/?probe=00d174fcf4) | Oct 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| ASUSTek       | E402MA                      | Notebook    | [807cf84523](https://linux-hardware.org/?probe=807cf84523) | Oct 11, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [8926251d64](https://linux-hardware.org/?probe=8926251d64) | Oct 11, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [0e8d79a9a9](https://linux-hardware.org/?probe=0e8d79a9a9) | Oct 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [e060b11754](https://linux-hardware.org/?probe=e060b11754) | Oct 11, 2022 |
| HP            | Presario CQ57               | Notebook    | [b67f538b81](https://linux-hardware.org/?probe=b67f538b81) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [aa8415aa98](https://linux-hardware.org/?probe=aa8415aa98) | Oct 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [f3a23a25c6](https://linux-hardware.org/?probe=f3a23a25c6) | Oct 10, 2022 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [c8ee640a4d](https://linux-hardware.org/?probe=c8ee640a4d) | Oct 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [d00832c27c](https://linux-hardware.org/?probe=d00832c27c) | Oct 09, 2022 |
| ASUSTek       | P552LA                      | Notebook    | [6985e4f01e](https://linux-hardware.org/?probe=6985e4f01e) | Oct 09, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fda26adf83](https://linux-hardware.org/?probe=fda26adf83) | Oct 09, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a5511bd426](https://linux-hardware.org/?probe=a5511bd426) | Oct 09, 2022 |
| Fujitsu Si... | AMILO Pa 1538               | Notebook    | [11d843f241](https://linux-hardware.org/?probe=11d843f241) | Oct 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 875       | 13.67%  |
| Ubuntu 18.04        | 554       | 8.65%   |
| Ubuntu 22.04        | 277       | 4.33%   |
| OpenMandriva 4.2    | 211       | 3.3%    |
| OpenMandriva 4.3    | 160       | 2.5%    |
| Fedora 36           | 143       | 2.23%   |
| Arch Rolling        | 138       | 2.16%   |
| Debian 11           | 137       | 2.14%   |
| Ubuntu 20.10        | 129       | 2.01%   |
| Arch                | 123       | 1.92%   |
| Ubuntu 19.10        | 120       | 1.87%   |
| Ubuntu 19.04        | 108       | 1.69%   |
| Xubuntu 18.04       | 104       | 1.62%   |
| KDE neon 20.04      | 101       | 1.58%   |
| Xubuntu 20.04       | 100       | 1.56%   |
| Ubuntu 21.10        | 96        | 1.5%    |
| Linux Mint 20.3     | 86        | 1.34%   |
| Ubuntu 21.04        | 83        | 1.3%    |
| Debian 10           | 78        | 1.22%   |
| Pop!_OS 22.04       | 74        | 1.16%   |
| Zorin 16            | 72        | 1.12%   |
| Zorin 15            | 68        | 1.06%   |
| Ubuntu 18.10        | 68        | 1.06%   |
| Fedora 35           | 68        | 1.06%   |
| Linux Mint 19.3     | 65        | 1.02%   |
| Kubuntu 20.04       | 65        | 1.02%   |
| ROSA R10            | 62        | 0.97%   |
| Linux Mint 21       | 62        | 0.97%   |
| Linux Mint 20.1     | 60        | 0.94%   |
| Linux Mint 20.2     | 58        | 0.91%   |
| Pop!_OS 20.10       | 57        | 0.89%   |
| Manjaro             | 56        | 0.87%   |
| Fedora 33           | 54        | 0.84%   |
| Linux Mint 20       | 53        | 0.83%   |
| Ubuntu 22.10        | 49        | 0.77%   |
| Fedora 32           | 46        | 0.72%   |
| EndeavourOS Rolling | 46        | 0.72%   |
| Kubuntu 22.04       | 45        | 0.7%    |
| Fedora 34           | 41        | 0.64%   |
| OpenMandriva 4.50   | 40        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2277      | 37.35%  |
| OpenMandriva  | 420       | 6.89%   |
| Linux Mint    | 402       | 6.59%   |
| Fedora        | 388       | 6.36%   |
| Xubuntu       | 281       | 4.61%   |
| Debian        | 274       | 4.49%   |
| Arch          | 257       | 4.22%   |
| Pop!_OS       | 225       | 3.69%   |
| Manjaro       | 188       | 3.08%   |
| ROSA          | 177       | 2.9%    |
| Kubuntu       | 167       | 2.74%   |
| Zorin         | 150       | 2.46%   |
| KDE neon      | 128       | 2.1%    |
| Lubuntu       | 79        | 1.3%    |
| Ubuntu MATE   | 65        | 1.07%   |
| openSUSE      | 55        | 0.9%    |
| EndeavourOS   | 52        | 0.85%   |
| Endless       | 47        | 0.77%   |
| Elementary    | 47        | 0.77%   |
| Ubuntu Unity  | 39        | 0.64%   |
| Clear Linux   | 34        | 0.56%   |
| BlackPanther  | 34        | 0.56%   |
| Gentoo        | 27        | 0.44%   |
| ArcoLinux     | 27        | 0.44%   |
| LMDE          | 24        | 0.39%   |
| MX            | 22        | 0.36%   |
| Peppermint    | 20        | 0.33%   |
| Kali          | 19        | 0.31%   |
| Garuda Linux  | 18        | 0.3%    |
| Ubuntu Budgie | 16        | 0.26%   |
| LinuxFX       | 11        | 0.18%   |
| Parrot        | 10        | 0.16%   |
| Ubuntu Studio | 9         | 0.15%   |
| CentOS        | 8         | 0.13%   |
| Raspbian      | 7         | 0.11%   |
| Chrome OS     | 7         | 0.11%   |
| Slackware     | 6         | 0.1%    |
| Q4OS          | 5         | 0.08%   |
| Xero          | 4         | 0.07%   |
| SteamOS       | 4         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 204       | 2.89%   |
| 5.15.0-52-generic        | 164       | 2.32%   |
| 5.16.7-desktop-1omv4003  | 156       | 2.21%   |
| 5.4.0-42-generic         | 125       | 1.77%   |
| 5.4.0-52-generic         | 81        | 1.15%   |
| 5.15.0-47-generic        | 70        | 0.99%   |
| 5.3.0-46-generic         | 66        | 0.93%   |
| 5.4.0-26-generic         | 65        | 0.92%   |
| 5.15.0-46-generic        | 63        | 0.89%   |
| 5.4.0-58-generic         | 60        | 0.85%   |
| 5.4.0-29-generic         | 59        | 0.84%   |
| 5.3.0-40-generic         | 58        | 0.82%   |
| 5.4.0-48-generic         | 56        | 0.79%   |
| 5.3.0-42-generic         | 48        | 0.68%   |
| 5.4.0-54-generic         | 46        | 0.65%   |
| 5.15.0-43-generic        | 41        | 0.58%   |
| 6.0.2-arch1-1            | 40        | 0.57%   |
| 5.4.0-28-generic         | 40        | 0.57%   |
| 5.19.0-23-generic        | 39        | 0.55%   |
| 5.0.0-37-generic         | 39        | 0.55%   |
| 5.4.0-56-generic         | 38        | 0.54%   |
| 5.4.0-37-generic         | 38        | 0.54%   |
| 5.4.0-33-generic         | 38        | 0.54%   |
| 5.4.0-47-generic         | 37        | 0.52%   |
| 5.15.0-48-generic        | 37        | 0.52%   |
| 5.11.0-38-generic        | 37        | 0.52%   |
| 5.15.0-53-generic        | 36        | 0.51%   |
| 5.4.0-40-generic         | 35        | 0.5%    |
| 5.13.0-28-generic        | 35        | 0.5%    |
| 5.15.0-50-generic        | 34        | 0.48%   |
| 5.15.0-41-generic        | 33        | 0.47%   |
| 5.13.0-39-generic        | 33        | 0.47%   |
| 5.10.0-19-amd64          | 33        | 0.47%   |
| 5.4.0-31-generic         | 31        | 0.44%   |
| 5.19.16-200.fc36.x86_64  | 31        | 0.44%   |
| 4.18.16-desktop-1bP      | 31        | 0.44%   |
| 4.18.0-15-generic        | 31        | 0.44%   |
| 5.8.0-48-generic         | 30        | 0.42%   |
| 5.3.0-51-generic         | 30        | 0.42%   |
| 5.0.0-32-generic         | 30        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1218      | 18.45%  |
| 5.15.0  | 535       | 8.1%    |
| 4.15.0  | 461       | 6.98%   |
| 5.8.0   | 394       | 5.97%   |
| 5.3.0   | 384       | 5.82%   |
| 5.11.0  | 308       | 4.67%   |
| 5.13.0  | 289       | 4.38%   |
| 5.0.0   | 224       | 3.39%   |
| 5.10.14 | 205       | 3.11%   |
| 5.10.0  | 164       | 2.48%   |
| 5.16.7  | 159       | 2.41%   |
| 4.18.0  | 157       | 2.38%   |
| 5.19.0  | 105       | 1.59%   |
| 6.0.2   | 81        | 1.23%   |
| 4.19.0  | 75        | 1.14%   |
| 5.19.16 | 47        | 0.71%   |
| 4.9.60  | 36        | 0.55%   |
| 4.9.20  | 36        | 0.55%   |
| 4.18.16 | 33        | 0.5%    |
| 5.17.5  | 32        | 0.48%   |
| 5.19.6  | 28        | 0.42%   |
| 6.0.6   | 27        | 0.41%   |
| 4.4.0   | 25        | 0.38%   |
| 6.0.5   | 20        | 0.3%    |
| 6.0.0   | 20        | 0.3%    |
| 5.16.11 | 20        | 0.3%    |
| 5.17.1  | 19        | 0.29%   |
| 5.12.4  | 18        | 0.27%   |
| 6.0.7   | 17        | 0.26%   |
| 6.0.9   | 16        | 0.24%   |
| 5.19.4  | 16        | 0.24%   |
| 5.18.0  | 15        | 0.23%   |
| 5.17.0  | 15        | 0.23%   |
| 5.16.0  | 15        | 0.23%   |
| 6.0.8   | 14        | 0.21%   |
| 5.8.18  | 14        | 0.21%   |
| 5.19.12 | 14        | 0.21%   |
| 5.6.0   | 13        | 0.2%    |
| 5.4.32  | 13        | 0.2%    |
| 5.18.12 | 13        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1297      | 19.87%  |
| 5.15    | 678       | 10.39%  |
| 5.8     | 464       | 7.11%   |
| 4.15    | 463       | 7.09%   |
| 5.10    | 458       | 7.02%   |
| 5.3     | 414       | 6.34%   |
| 5.11    | 370       | 5.67%   |
| 5.13    | 321       | 4.92%   |
| 5.19    | 283       | 4.34%   |
| 5.16    | 245       | 3.75%   |
| 5.0     | 231       | 3.54%   |
| 6.0     | 205       | 3.14%   |
| 4.18    | 197       | 3.02%   |
| 4.9     | 121       | 1.85%   |
| 5.17    | 104       | 1.59%   |
| 4.19    | 100       | 1.53%   |
| 5.18    | 92        | 1.41%   |
| 5.9     | 82        | 1.26%   |
| 5.14    | 71        | 1.09%   |
| 5.6     | 64        | 0.98%   |
| 5.12    | 62        | 0.95%   |
| 5.7     | 50        | 0.77%   |
| 5.5     | 47        | 0.72%   |
| 4.4     | 27        | 0.41%   |
| 4.1     | 16        | 0.25%   |
| 5.2     | 13        | 0.2%    |
| 4.13    | 12        | 0.18%   |
| 5.1     | 7         | 0.11%   |
| 4.20    | 5         | 0.08%   |
| 4.17    | 5         | 0.08%   |
| 4.12    | 5         | 0.08%   |
| 4.14    | 4         | 0.06%   |
| 6.1     | 3         | 0.05%   |
| 3.10    | 3         | 0.05%   |
| 4.16    | 2         | 0.03%   |
| 4.8     | 1         | 0.02%   |
| 4.7     | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.4     | 1         | 0.02%   |
| 3.14    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 5572      | 94.2%   |
| i686    | 304       | 5.14%   |
| aarch64 | 30        | 0.51%   |
| armv7l  | 9         | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2642      | 42.87%  |
| KDE5             | 1071      | 17.38%  |
| Unknown          | 798       | 12.95%  |
| XFCE             | 520       | 8.44%   |
| X-Cinnamon       | 321       | 5.21%   |
| MATE             | 167       | 2.71%   |
| KDE              | 135       | 2.19%   |
| KDE4             | 108       | 1.75%   |
| LXQt             | 91        | 1.48%   |
| Pantheon         | 45        | 0.73%   |
| Cinnamon         | 45        | 0.73%   |
| LXDE             | 42        | 0.68%   |
| Unity            | 40        | 0.65%   |
| GNOME Flashback  | 25        | 0.41%   |
| Budgie           | 25        | 0.41%   |
| i3               | 18        | 0.29%   |
| GNOME Classic    | 10        | 0.16%   |
| Deepin           | 10        | 0.16%   |
| Openbox          | 8         | 0.13%   |
| sway             | 6         | 0.1%    |
| Hyprland         | 5         | 0.08%   |
| Trinity          | 4         | 0.06%   |
| lightdm-xsession | 4         | 0.06%   |
| DWM              | 4         | 0.06%   |
| bspwm            | 4         | 0.06%   |
| xubuntu          | 2         | 0.03%   |
| qtile            | 2         | 0.03%   |
| Enlightenment    | 2         | 0.03%   |
| ubuntu           | 1         | 0.02%   |
| none+i3          | 1         | 0.02%   |
| none+bspwm       | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| herbstluftwm     | 1         | 0.02%   |
| gamescope        | 1         | 0.02%   |
| FVWM             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| awesome          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4740      | 77.93%  |
| Wayland | 856       | 14.07%  |
| Unknown | 410       | 6.74%   |
| Tty     | 76        | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3059      | 49.83%  |
| SDDM    | 1011      | 16.47%  |
| GDM     | 668       | 10.88%  |
| GDM3    | 593       | 9.66%   |
| LightDM | 502       | 8.18%   |
| TDM     | 168       | 2.74%   |
| KDM     | 111       | 1.81%   |
| XDM     | 12        | 0.2%    |
| LXDM    | 4         | 0.07%   |
| SLiM    | 3         | 0.05%   |
| GREETD  | 3         | 0.05%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| it_IT        | 3742      | 61.7%   |
| en_US        | 1155      | 19.04%  |
| Unknown      | 849       | 14%     |
| en_GB        | 131       | 2.16%   |
| C            | 82        | 1.35%   |
| de_DE        | 18        | 0.3%    |
| fr_FR        | 13        | 0.21%   |
| es_ES        | 11        | 0.18%   |
| ru_RU        | 8         | 0.13%   |
| it_CH        | 8         | 0.13%   |
| de_IT        | 8         | 0.13%   |
| POSIX        | 6         | 0.1%    |
| en_IE        | 4         | 0.07%   |
| de_AT        | 4         | 0.07%   |
| en_AU        | 3         | 0.05%   |
| en_AG        | 3         | 0.05%   |
| en_US.UTF8   | 2         | 0.03%   |
| ro_RO        | 1         | 0.02%   |
| pt_BR        | 1         | 0.02%   |
| pl_PL        | 1         | 0.02%   |
| it_ITutf8    | 1         | 0.02%   |
| it_IT@euro   | 1         | 0.02%   |
| it_IT.UTF -8 | 1         | 0.02%   |
| hu_HU        | 1         | 0.02%   |
| fur_IT       | 1         | 0.02%   |
| fr_BE        | 1         | 0.02%   |
| es_US        | 1         | 0.02%   |
| es_MX        | 1         | 0.02%   |
| en_US@euro   | 1         | 0.02%   |
| en_US.utf-8  | 1         | 0.02%   |
| en_US.ASCII  | 1         | 0.02%   |
| en_IN        | 1         | 0.02%   |
| Default      | 1         | 0.02%   |
| C.UTF8       | 1         | 0.02%   |
| bg_BG        | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3200      | 53.19%  |
| EFI  | 2816      | 46.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4702      | 78.09%  |
| Overlay  | 535       | 8.89%   |
| Btrfs    | 417       | 6.93%   |
| Unknown  | 230       | 3.82%   |
| Xfs      | 58        | 0.96%   |
| Zfs      | 26        | 0.43%   |
| Ext2     | 18        | 0.3%    |
| Ext3     | 14        | 0.23%   |
| F2fs     | 8         | 0.13%   |
| Tmpfs    | 6         | 0.1%    |
| XXX4     | 2         | 0.03%   |
| Aufs     | 2         | 0.03%   |
| XXXX     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3331      | 55.15%  |
| GPT     | 2014      | 33.34%  |
| MBR     | 695       | 11.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5101      | 84.73%  |
| Yes       | 919       | 15.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3814      | 63.29%  |
| Yes       | 2212      | 36.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1282      | 21.7%   |
| Hewlett-Packard         | 982       | 16.62%  |
| Lenovo                  | 654       | 11.07%  |
| Acer                    | 486       | 8.23%   |
| Dell                    | 483       | 8.18%   |
| MSI                     | 326       | 5.52%   |
| ASRock                  | 275       | 4.65%   |
| Gigabyte Technology     | 209       | 3.54%   |
| Apple                   | 124       | 2.1%    |
| Toshiba                 | 93        | 1.57%   |
| Intel                   | 92        | 1.56%   |
| Sony                    | 85        | 1.44%   |
| HUAWEI                  | 72        | 1.22%   |
| Samsung Electronics     | 63        | 1.07%   |
| Fujitsu                 | 61        | 1.03%   |
| Unknown                 | 58        | 0.98%   |
| Packard Bell            | 52        | 0.88%   |
| Pegatron                | 34        | 0.58%   |
| Fujitsu Siemens         | 30        | 0.51%   |
| Raspberry Pi Foundation | 29        | 0.49%   |
| Mediacom                | 24        | 0.41%   |
| Chuwi                   | 24        | 0.41%   |
| Teclast                 | 23        | 0.39%   |
| Foxconn                 | 21        | 0.36%   |
| AMI                     | 18        | 0.3%    |
| Notebook                | 16        | 0.27%   |
| Microtech               | 15        | 0.25%   |
| Microsoft               | 15        | 0.25%   |
| Timi                    | 14        | 0.24%   |
| BESSTAR Tech            | 14        | 0.24%   |
| Supermicro              | 11        | 0.19%   |
| TUXEDO                  | 10        | 0.17%   |
| PC Specialist           | 10        | 0.17%   |
| AZW                     | 10        | 0.17%   |
| eMachines               | 9         | 0.15%   |
| SANTECH                 | 8         | 0.14%   |
| Biostar                 | 8         | 0.14%   |
| Alienware               | 8         | 0.14%   |
| IBM                     | 7         | 0.12%   |
| TYAN Computer           | 6         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 73        | 1.24%   |
| ASUS All Series                            | 67        | 1.13%   |
| HP Pavilion dv6                            | 49        | 0.83%   |
| HP Notebook                                | 31        | 0.52%   |
| HP Pavilion 15                             | 21        | 0.36%   |
| HP Pavilion g6                             | 20        | 0.34%   |
| HUAWEI NBLK-WAX9X                          | 14        | 0.24%   |
| ASUS PRIME A320M-K                         | 14        | 0.24%   |
| MSI MS-7C37                                | 13        | 0.22%   |
| HP 255 G8 Notebook PC                      | 13        | 0.22%   |
| MSI MS-7B86                                | 12        | 0.2%    |
| HP 255 G7 Notebook PC                      | 12        | 0.2%    |
| HP 15                                      | 12        | 0.2%    |
| Dell XPS 15 7590                           | 12        | 0.2%    |
| Dell OptiPlex 7010                         | 12        | 0.2%    |
| HP G62                                     | 11        | 0.19%   |
| HP 255 G6 Notebook PC                      | 11        | 0.19%   |
| Apple MacBook4,1                           | 11        | 0.19%   |
| RPi Raspberry Pi                           | 10        | 0.17%   |
| MSI MS-7C56                                | 10        | 0.17%   |
| Mediacom SmartBook 14 FullHD - SB14UC      | 10        | 0.17%   |
| HP Compaq Elite 8300 SFF                   | 10        | 0.17%   |
| HP 250 G6 Notebook PC                      | 10        | 0.17%   |
| ASUS T101HA                                | 10        | 0.17%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 9         | 0.15%   |
| HUAWEI KLVL-WXX9                           | 9         | 0.15%   |
| HP Pavilion x2 Detachable                  | 9         | 0.15%   |
| Dell XPS 15 9560                           | 9         | 0.15%   |
| Lenovo V145-15AST 81MT                     | 8         | 0.14%   |
| HP ProBook 450 G5                          | 8         | 0.14%   |
| HP Laptop 15s-eq2xxx                       | 8         | 0.14%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD     | 8         | 0.14%   |
| ASUS TUF Gaming X570-PLUS                  | 8         | 0.14%   |
| ASUS K53SC                                 | 8         | 0.14%   |
| Supermicro H8DM8-2                         | 7         | 0.12%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 7         | 0.12%   |
| Microtech ebookPro                         | 7         | 0.12%   |
| Lenovo G50-45 80E3                         | 7         | 0.12%   |
| HP ProBook 450 G6                          | 7         | 0.12%   |
| HP Pavilion Notebook                       | 7         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 310       | 5.25%   |
| Lenovo ThinkPad       | 264       | 4.47%   |
| HP Pavilion           | 227       | 3.84%   |
| Dell Latitude         | 140       | 2.37%   |
| HP Compaq             | 135       | 2.29%   |
| Lenovo IdeaPad        | 119       | 2.01%   |
| ASUS PRIME            | 100       | 1.69%   |
| HP EliteBook          | 91        | 1.54%   |
| ASUS VivoBook         | 86        | 1.46%   |
| Dell XPS              | 83        | 1.4%    |
| Dell Inspiron         | 83        | 1.4%    |
| Toshiba Satellite     | 81        | 1.37%   |
| Unknown               | 73        | 1.24%   |
| HP ProBook            | 71        | 1.2%    |
| HP Laptop             | 70        | 1.18%   |
| ASUS All              | 67        | 1.13%   |
| Dell OptiPlex         | 66        | 1.12%   |
| ASUS ROG              | 58        | 0.98%   |
| HP 255                | 50        | 0.85%   |
| ASUS TUF              | 47        | 0.8%    |
| Dell Precision        | 44        | 0.74%   |
| Lenovo ThinkCentre    | 42        | 0.71%   |
| HP 250                | 40        | 0.68%   |
| Fujitsu LIFEBOOK      | 35        | 0.59%   |
| Dell Vostro           | 34        | 0.58%   |
| Acer Extensa          | 32        | 0.54%   |
| HP Notebook           | 31        | 0.52%   |
| RPi Raspberry         | 29        | 0.49%   |
| Acer Swift            | 29        | 0.49%   |
| Lenovo ThinkBook      | 28        | 0.47%   |
| Acer TravelMate       | 27        | 0.46%   |
| Lenovo Yoga           | 25        | 0.42%   |
| HP ENVY               | 24        | 0.41%   |
| Acer Veriton          | 24        | 0.41%   |
| Packard Bell EasyNote | 21        | 0.36%   |
| Fujitsu ESPRIMO       | 21        | 0.36%   |
| ASUS P8H61-M          | 18        | 0.3%    |
| Packard Bell IMEDIA   | 17        | 0.29%   |
| Apple MacBookPro11    | 16        | 0.27%   |
| Microsoft Surface     | 15        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 513       | 8.68%   |
| 2019    | 488       | 8.26%   |
| 2020    | 464       | 7.85%   |
| 2013    | 410       | 6.94%   |
| 2012    | 380       | 6.43%   |
| 2017    | 378       | 6.4%    |
| 2008    | 377       | 6.38%   |
| 2011    | 372       | 6.3%    |
| 2009    | 358       | 6.06%   |
| 2010    | 344       | 5.82%   |
| 2014    | 343       | 5.81%   |
| 2021    | 321       | 5.43%   |
| 2016    | 320       | 5.42%   |
| 2015    | 308       | 5.21%   |
| 2007    | 234       | 3.96%   |
| 2006    | 129       | 2.18%   |
| 2005    | 60        | 1.02%   |
| 2022    | 53        | 0.9%    |
| Unknown | 34        | 0.58%   |
| 2004    | 14        | 0.24%   |
| 2003    | 5         | 0.08%   |
| 2001    | 2         | 0.03%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3324      | 56.26%  |
| Desktop        | 2184      | 36.97%  |
| Convertible    | 120       | 2.03%   |
| Mini pc        | 84        | 1.42%   |
| All in one     | 75        | 1.27%   |
| Tablet         | 66        | 1.12%   |
| System on chip | 37        | 0.63%   |
| Server         | 17        | 0.29%   |
| Phone          | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 5520      | 92.82%  |
| Enabled  | 427       | 7.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5898      | 99.83%  |
| Yes  | 10        | 0.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1441      | 24.07%  |
| 4.01-8.0        | 1378      | 23.02%  |
| 16.01-24.0      | 1046      | 17.47%  |
| 8.01-16.0       | 1024      | 17.1%   |
| 1.01-2.0        | 394       | 6.58%   |
| 32.01-64.0      | 370       | 6.18%   |
| 2.01-3.0        | 116       | 1.94%   |
| 64.01-256.0     | 73        | 1.22%   |
| 0.51-1.0        | 73        | 1.22%   |
| 24.01-32.0      | 61        | 1.02%   |
| 0.01-0.5        | 6         | 0.1%    |
| More than 256.0 | 5         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2642      | 40.67%  |
| 2.01-3.0   | 1516      | 23.34%  |
| 4.01-8.0   | 726       | 11.18%  |
| 3.01-4.0   | 713       | 10.98%  |
| 0.51-1.0   | 607       | 9.34%   |
| 8.01-16.0  | 180       | 2.77%   |
| 0.01-0.5   | 85        | 1.31%   |
| 16.01-24.0 | 17        | 0.26%   |
| 24.01-32.0 | 6         | 0.09%   |
| Unknown    | 3         | 0.05%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3687      | 60.83%  |
| 2       | 1521      | 25.09%  |
| 3       | 444       | 7.33%   |
| 4       | 193       | 3.18%   |
| 5       | 89        | 1.47%   |
| 0       | 53        | 0.87%   |
| 6       | 38        | 0.63%   |
| 7       | 14        | 0.23%   |
| 8       | 10        | 0.16%   |
| 10      | 4         | 0.07%   |
| 9       | 3         | 0.05%   |
| 12      | 2         | 0.03%   |
| Unknown | 2         | 0.03%   |
| 13      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3024      | 50.81%  |
| Yes       | 2927      | 49.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5074      | 85.59%  |
| No        | 854       | 14.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4495      | 75.74%  |
| No        | 1440      | 24.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3235      | 53.99%  |
| No        | 2757      | 46.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 5908      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Milan               | 804       | 12.21%  |
| Rome                | 699       | 10.61%  |
| Turin               | 224       | 3.4%    |
| Bologna             | 150       | 2.28%   |
| Naples              | 131       | 1.99%   |
| Florence            | 120       | 1.82%   |
| Genoa               | 98        | 1.49%   |
| Rho                 | 89        | 1.35%   |
| Padova              | 84        | 1.28%   |
| Palermo             | 73        | 1.11%   |
| Verona              | 64        | 0.97%   |
| Brescia             | 50        | 0.76%   |
| Bari                | 48        | 0.73%   |
| Catania             | 47        | 0.71%   |
| Trieste             | 46        | 0.7%    |
| Parma               | 37        | 0.56%   |
| Venice              | 36        | 0.55%   |
| Reggio Emilia       | 34        | 0.52%   |
| Modena              | 32        | 0.49%   |
| Bergamo             | 32        | 0.49%   |
| Pisa                | 31        | 0.47%   |
| Trento              | 30        | 0.46%   |
| Cagliari            | 30        | 0.46%   |
| Pescara             | 28        | 0.43%   |
| Casalecchio di Reno | 28        | 0.43%   |
| Bolzano             | 27        | 0.41%   |
| Sesto San Giovanni  | 26        | 0.39%   |
| Perugia             | 26        | 0.39%   |
| Monza               | 25        | 0.38%   |
| Taranto             | 24        | 0.36%   |
| Mestre              | 21        | 0.32%   |
| Udine               | 20        | 0.3%    |
| Seregno             | 20        | 0.3%    |
| Forlì              | 19        | 0.29%   |
| Vicenza             | 18        | 0.27%   |
| Legnano             | 18        | 0.27%   |
| Como                | 18        | 0.27%   |
| Reggio Calabria     | 17        | 0.26%   |
| Cesena              | 17        | 0.26%   |
| Salerno             | 16        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1363      | 1900   | 16.1%   |
| Seagate                   | 1248      | 1868   | 14.74%  |
| WDC                       | 1209      | 1783   | 14.28%  |
| Kingston                  | 544       | 711    | 6.43%   |
| Toshiba                   | 514       | 700    | 6.07%   |
| Crucial                   | 473       | 581    | 5.59%   |
| SanDisk                   | 423       | 564    | 5%      |
| Unknown                   | 395       | 535    | 4.67%   |
| Hitachi                   | 352       | 446    | 4.16%   |
| SK hynix                  | 182       | 218    | 2.15%   |
| HGST                      | 180       | 233    | 2.13%   |
| Maxtor                    | 165       | 224    | 1.95%   |
| Micron Technology         | 126       | 152    | 1.49%   |
| Intel                     | 122       | 150    | 1.44%   |
| Phison                    | 89        | 118    | 1.05%   |
| China                     | 59        | 65     | 0.7%    |
| SPCC                      | 52        | 62     | 0.61%   |
| KIOXIA                    | 51        | 67     | 0.6%    |
| Fujitsu                   | 49        | 57     | 0.58%   |
| Transcend                 | 41        | 51     | 0.48%   |
| Intenso                   | 41        | 50     | 0.48%   |
| Apple                     | 41        | 50     | 0.48%   |
| Corsair                   | 36        | 52     | 0.43%   |
| A-DATA Technology         | 35        | 46     | 0.41%   |
| Micron/Crucial Technology | 29        | 36     | 0.34%   |
| KingDian                  | 29        | 35     | 0.34%   |
| PNY                       | 28        | 35     | 0.33%   |
| JMicron Technology        | 28        | 30     | 0.33%   |
| LITEON                    | 23        | 28     | 0.27%   |
| Patriot                   | 21        | 28     | 0.25%   |
| Drevo                     | 21        | 23     | 0.25%   |
| OCZ                       | 20        | 22     | 0.24%   |
| Netac                     | 20        | 22     | 0.24%   |
| Teclast                   | 18        | 22     | 0.21%   |
| Silicon Motion            | 18        | 23     | 0.21%   |
| Phison Electronics        | 17        | 19     | 0.2%    |
| SABRENT                   | 16        | 16     | 0.19%   |
| LITEONIT                  | 16        | 25     | 0.19%   |
| Unknown                   | 16        | 21     | 0.19%   |
| TCSUNBOW                  | 15        | 17     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 136       | 1.47%   |
| Samsung SSD 860 EVO 500GB                         | 124       | 1.34%   |
| Crucial CT500MX500SSD1 500GB                      | 110       | 1.19%   |
| Samsung SSD 850 EVO 250GB                         | 106       | 1.15%   |
| Seagate ST500DM002-1BD142 500GB                   | 92        | 0.99%   |
| Samsung SSD 850 EVO 500GB                         | 83        | 0.9%    |
| Kingston SA400S37480G 480GB SSD                   | 81        | 0.88%   |
| Unknown MMC Card  32GB                            | 77        | 0.83%   |
| Toshiba MQ01ABF050 500GB                          | 63        | 0.68%   |
| Samsung SSD 860 EVO 250GB                         | 63        | 0.68%   |
| Crucial CT240BX500SSD1 240GB                      | 61        | 0.66%   |
| Unknown MMC Card  64GB                            | 60        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                    | 59        | 0.64%   |
| Toshiba DT01ACA100 1TB                            | 52        | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 51        | 0.55%   |
| Seagate ST500LT012-1DG142 500GB                   | 48        | 0.52%   |
| Kingston SA400S37120G 120GB SSD                   | 48        | 0.52%   |
| HGST HTS721010A9E630 1TB                          | 46        | 0.5%    |
| HGST HTS545050A7E680 500GB                        | 46        | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB                    | 45        | 0.49%   |
| Kingston SV300S37A120G 120GB SSD                  | 45        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                       | 45        | 0.49%   |
| Seagate ST3500418AS 500GB                         | 43        | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB                    | 43        | 0.46%   |
| Samsung NVMe SSD Drive 512GB                      | 43        | 0.46%   |
| SanDisk SSD PLUS 240GB                            | 42        | 0.45%   |
| Crucial CT480BX500SSD1 480GB                      | 42        | 0.45%   |
| Seagate M3 Portable 4TB                           | 40        | 0.43%   |
| Samsung SSD 840 EVO 250GB                         | 39        | 0.42%   |
| Seagate ST31000528AS 1TB                          | 38        | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 38        | 0.41%   |
| Seagate ST9500325AS 500GB                         | 37        | 0.4%    |
| Samsung SSD 860 EVO 1TB                           | 37        | 0.4%    |
| Toshiba MQ01ABD100 1TB                            | 36        | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB                    | 35        | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 34        | 0.37%   |
| Samsung NVMe SSD Drive 500GB                      | 34        | 0.37%   |
| SanDisk NVMe SSD Drive 512GB                      | 33        | 0.36%   |
| Phison Sabrent 512GB                              | 32        | 0.35%   |
| Seagate Expansion 1TB                             | 31        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1212      | 1805   | 33.8%   |
| WDC                 | 1026      | 1511   | 28.61%  |
| Toshiba             | 381       | 513    | 10.62%  |
| Hitachi             | 352       | 446    | 9.82%   |
| HGST                | 179       | 232    | 4.99%   |
| Maxtor              | 165       | 224    | 4.6%    |
| Samsung Electronics | 131       | 165    | 3.65%   |
| Fujitsu             | 49        | 57     | 1.37%   |
| Unknown             | 42        | 51     | 1.17%   |
| Apple               | 10        | 12     | 0.28%   |
| ASMT                | 8         | 11     | 0.22%   |
| IBM/Hitachi         | 4         | 5      | 0.11%   |
| HGST HTS            | 4         | 4      | 0.11%   |
| WD MediaMax         | 2         | 2      | 0.06%   |
| Intenso             | 2         | 4      | 0.06%   |
| Inateck             | 2         | 2      | 0.06%   |
| ASMT109x            | 2         | 2      | 0.06%   |
| USB3.0              | 1         | 1      | 0.03%   |
| USB 3.0             | 1         | 2      | 0.03%   |
| USB                 | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| Promise             | 1         | 1      | 0.03%   |
| PI-041              | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 2      | 0.03%   |
| Initio              | 1         | 1      | 0.03%   |
| IBM-ESXS            | 1         | 2      | 0.03%   |
| IBM-207x            | 1         | 4      | 0.03%   |
| Hewlett-Packard     | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| FC-1307             | 1         | 2      | 0.03%   |
| DAS                 | 1         | 4      | 0.03%   |
| Config              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 775       | 1050   | 26.94%  |
| Kingston            | 468       | 610    | 16.27%  |
| Crucial             | 433       | 534    | 15.05%  |
| SanDisk             | 266       | 353    | 9.25%   |
| WDC                 | 98        | 134    | 3.41%   |
| Micron Technology   | 63        | 77     | 2.19%   |
| China               | 58        | 64     | 2.02%   |
| Toshiba             | 46        | 65     | 1.6%    |
| SPCC                | 42        | 50     | 1.46%   |
| SK hynix            | 42        | 49     | 1.46%   |
| Transcend           | 39        | 49     | 1.36%   |
| Intenso             | 34        | 40     | 1.18%   |
| Intel               | 33        | 43     | 1.15%   |
| Corsair             | 30        | 45     | 1.04%   |
| KingDian            | 28        | 34     | 0.97%   |
| A-DATA Technology   | 28        | 38     | 0.97%   |
| PNY                 | 26        | 32     | 0.9%    |
| Apple               | 23        | 24     | 0.8%    |
| Patriot             | 21        | 28     | 0.73%   |
| LITEON              | 20        | 23     | 0.7%    |
| OCZ                 | 19        | 21     | 0.66%   |
| Teclast             | 18        | 22     | 0.63%   |
| Netac               | 17        | 18     | 0.59%   |
| LITEONIT            | 16        | 25     | 0.56%   |
| Drevo               | 16        | 17     | 0.56%   |
| GOODRAM             | 15        | 20     | 0.52%   |
| TCSUNBOW            | 13        | 14     | 0.45%   |
| Dogfish             | 13        | 17     | 0.45%   |
| JMicron Technology  | 12        | 13     | 0.42%   |
| Verbatim            | 9         | 14     | 0.31%   |
| Unknown             | 9         | 10     | 0.31%   |
| Team                | 9         | 13     | 0.31%   |
| FORESEE             | 9         | 11     | 0.31%   |
| BAITITON            | 8         | 8      | 0.28%   |
| Unknown             | 8         | 13     | 0.28%   |
| Microtech           | 7         | 16     | 0.24%   |
| KingSpec            | 7         | 9      | 0.24%   |
| Lexar               | 5         | 5      | 0.17%   |
| ASMT                | 5         | 5      | 0.17%   |
| USB3.0              | 4         | 4      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3040      | 5071   | 40.07%  |
| SSD     | 2573      | 3722   | 33.91%  |
| NVMe    | 1474      | 2032   | 19.43%  |
| MMC     | 356       | 501    | 4.69%   |
| Unknown | 144       | 181    | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4620      | 8605   | 68.52%  |
| NVMe | 1458      | 1999   | 21.62%  |
| MMC  | 356       | 501    | 5.28%   |
| SAS  | 309       | 402    | 4.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3829      | 5933   | 67.14%  |
| 0.51-1.0   | 1356      | 1966   | 23.78%  |
| 1.01-2.0   | 298       | 491    | 5.23%   |
| 2.01-3.0   | 86        | 149    | 1.51%   |
| 3.01-4.0   | 83        | 148    | 1.46%   |
| 4.01-10.0  | 44        | 94     | 0.77%   |
| 10.01-20.0 | 7         | 12     | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1751      | 28.04%  |
| 251-500        | 1390      | 22.26%  |
| 501-1000       | 733       | 11.74%  |
| 1-20           | 558       | 8.94%   |
| 51-100         | 519       | 8.31%   |
| 1001-2000      | 414       | 6.63%   |
| 21-50          | 299       | 4.79%   |
| More than 3000 | 237       | 3.8%    |
| 2001-3000      | 177       | 2.83%   |
| Unknown        | 166       | 2.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2698      | 41.78%  |
| 21-50          | 970       | 15.02%  |
| 101-250        | 769       | 11.91%  |
| 51-100         | 719       | 11.14%  |
| 251-500        | 471       | 7.29%   |
| 501-1000       | 336       | 5.2%    |
| Unknown        | 166       | 2.57%   |
| 1001-2000      | 164       | 2.54%   |
| More than 3000 | 95        | 1.47%   |
| 2001-3000      | 69        | 1.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 15        | 17     | 3.02%   |
| HGST HTS545050A7E680 500GB            | 12        | 13     | 2.41%   |
| Seagate ST9500325AS 500GB             | 8         | 8      | 1.61%   |
| Seagate ST3500418AS 500GB             | 8         | 12     | 1.61%   |
| Hitachi HTS725050A9A364 500GB         | 7         | 7      | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 6      | 1.21%   |
| WDC WD3200BEVT-60A23T0 320GB          | 5         | 5      | 1.01%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 5      | 1.01%   |
| Maxtor STM3250310AS 250GB             | 5         | 5      | 1.01%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 4         | 4      | 0.8%    |
| Unknown MM0500EANCR 500GB             | 4         | 9      | 0.8%    |
| Toshiba MQ01ABF050 500GB              | 4         | 4      | 0.8%    |
| Seagate ST31500341AS 1TB              | 4         | 4      | 0.8%    |
| Seagate ST31000528AS 1TB              | 4         | 7      | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 4      | 0.8%    |
| Maxtor STM3320820AS 320GB             | 4         | 4      | 0.8%    |
| Hitachi HTS545050A7E380 500GB         | 4         | 4      | 0.8%    |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 0.8%    |
| WDC WD40EFRX-68N32N0 4TB              | 3         | 4      | 0.6%    |
| WDC WD20EFRX-68EUZN0 2TB              | 3         | 4      | 0.6%    |
| SK hynix HFS512G39TND-N210A 512GB SSD | 3         | 3      | 0.6%    |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.6%    |
| Seagate ST3500413AS 500GB             | 3         | 5      | 0.6%    |
| Seagate ST3500320AS 500GB             | 3         | 3      | 0.6%    |
| SanDisk SSD PLUS 480GB                | 3         | 3      | 0.6%    |
| Samsung Electronics SSD 970 EVO 1TB   | 3         | 3      | 0.6%    |
| Samsung Electronics SSD 860 EVO 500GB | 3         | 4      | 0.6%    |
| Samsung Electronics HD103UJ 1TB       | 3         | 3      | 0.6%    |
| Maxtor 6Y080L0 81GB                   | 3         | 3      | 0.6%    |
| Kingston SA400S37480G 480GB SSD       | 3         | 3      | 0.6%    |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.6%    |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.6%    |
| Hitachi HTS543225L9A300 250GB         | 3         | 3      | 0.6%    |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 0.6%    |
| HGST HTS541010A9E680 1TB              | 3         | 4      | 0.6%    |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 0.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 2         | 2      | 0.4%    |
| WDC WD5000BEVT-22ZAT0 500GB           | 2         | 2      | 0.4%    |
| WDC WD40PURZ-85TTDY0 4TB              | 2         | 2      | 0.4%    |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 2      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 133       | 175    | 27.42%  |
| WDC                 | 98        | 117    | 20.21%  |
| Hitachi             | 59        | 63     | 12.16%  |
| Toshiba             | 31        | 31     | 6.39%   |
| Maxtor              | 30        | 33     | 6.19%   |
| Samsung Electronics | 28        | 31     | 5.77%   |
| HGST                | 25        | 27     | 5.15%   |
| Kingston            | 14        | 14     | 2.89%   |
| Crucial             | 12        | 12     | 2.47%   |
| Micron Technology   | 8         | 8      | 1.65%   |
| SK hynix            | 7         | 8      | 1.44%   |
| SanDisk             | 6         | 6      | 1.24%   |
| Unknown             | 5         | 10     | 1.03%   |
| Intel               | 5         | 6      | 1.03%   |
| Fujitsu             | 4         | 4      | 0.82%   |
| Drevo               | 3         | 3      | 0.62%   |
| TCSUNBOW            | 2         | 2      | 0.41%   |
| OCZ                 | 2         | 2      | 0.41%   |
| Intenso             | 2         | 2      | 0.41%   |
| BAITITON            | 2         | 2      | 0.41%   |
| WDC WDS2            | 1         | 1      | 0.21%   |
| WD MediaMax         | 1         | 1      | 0.21%   |
| Transcend           | 1         | 2      | 0.21%   |
| LITEONIT            | 1         | 1      | 0.21%   |
| LITEON              | 1         | 1      | 0.21%   |
| KingSpec            | 1         | 1      | 0.21%   |
| KingDian            | 1         | 1      | 0.21%   |
| Corsair             | 1         | 2      | 0.21%   |
| ASMT                | 1         | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 133       | 175    | 33.17%  |
| WDC                 | 96        | 114    | 23.94%  |
| Hitachi             | 59        | 63     | 14.71%  |
| Toshiba             | 30        | 30     | 7.48%   |
| Maxtor              | 30        | 33     | 7.48%   |
| HGST                | 25        | 27     | 6.23%   |
| Samsung Electronics | 17        | 18     | 4.24%   |
| Unknown             | 5         | 10     | 1.25%   |
| Fujitsu             | 4         | 4      | 1%      |
| WD MediaMax         | 1         | 1      | 0.25%   |
| ASMT                | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 376       | 476    | 81.74%  |
| SSD  | 74        | 79     | 16.09%  |
| NVMe | 10        | 12     | 2.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB            | 2         | 4      | 14.29%  |
| Seagate ST500DM002-1BD142 500GB      | 2         | 3      | 14.29%  |
| WDC WD5000BEVT-26A0RT0 500GB         | 1         | 1      | 7.14%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 1      | 7.14%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1      | 7.14%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 1      | 7.14%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 7.14%   |
| Seagate STM3250318AS 250GB           | 1         | 1      | 7.14%   |
| Seagate ST2000LX001-1RG174 2TB       | 1         | 1      | 7.14%   |
| Hitachi HTS725050A7E630 500GB        | 1         | 1      | 7.14%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 7.14%   |
| Hitachi HTS543216L9A300 160GB        | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 9      | 42.86%  |
| WDC     | 4         | 4      | 28.57%  |
| Hitachi | 3         | 3      | 21.43%  |
| Toshiba | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3676      | 7068   | 57.69%  |
| Works    | 2231      | 3855   | 35.01%  |
| Malfunc  | 451       | 567    | 7.08%   |
| Failed   | 14        | 17     | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4022      | 56.3%   |
| AMD                              | 976       | 13.66%  |
| Samsung Electronics              | 552       | 7.73%   |
| SanDisk                          | 228       | 3.19%   |
| Nvidia                           | 172       | 2.41%   |
| SK hynix                         | 131       | 1.83%   |
| JMicron Technology               | 118       | 1.65%   |
| Phison Electronics               | 117       | 1.64%   |
| Marvell Technology Group         | 109       | 1.53%   |
| ASMedia Technology               | 102       | 1.43%   |
| Toshiba America Info Systems     | 90        | 1.26%   |
| Kingston Technology Company      | 87        | 1.22%   |
| Micron Technology                | 68        | 0.95%   |
| Micron/Crucial Technology        | 67        | 0.94%   |
| KIOXIA                           | 59        | 0.83%   |
| VIA Technologies                 | 54        | 0.76%   |
| Silicon Integrated Systems [SiS] | 31        | 0.43%   |
| Silicon Motion                   | 26        | 0.36%   |
| ADATA Technology                 | 15        | 0.21%   |
| Adaptec                          | 15        | 0.21%   |
| Union Memory (Shenzhen)          | 13        | 0.18%   |
| Silicon Image                    | 11        | 0.15%   |
| Broadcom / LSI                   | 9         | 0.13%   |
| Apple                            | 9         | 0.13%   |
| Solid State Storage Technology   | 8         | 0.11%   |
| LSI Logic / Symbios Logic        | 7         | 0.1%    |
| Lenovo                           | 6         | 0.08%   |
| Realtek Semiconductor            | 5         | 0.07%   |
| Lite-On Technology               | 5         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.06%   |
| Seagate Technology               | 3         | 0.04%   |
| Promise Technology               | 3         | 0.04%   |
| Hewlett-Packard                  | 3         | 0.04%   |
| Broadcom                         | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| ULi Electronics                  | 2         | 0.03%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| INNOGRIT                         | 2         | 0.03%   |
| HighPoint Technologies           | 2         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 639       | 7.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 312       | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 295       | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 234       | 2.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 230       | 2.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 210       | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 196       | 2.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 166       | 1.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 160       | 1.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 147       | 1.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 138       | 1.64%   |
| Samsung NVMe SSD Controller 980                                                | 129       | 1.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 122       | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 120       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 119       | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 118       | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 117       | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 116       | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 116       | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 101       | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 101       | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 98        | 1.16%   |
| Intel SATA Controller [RAID mode]                                              | 96        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 93        | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                            | 91        | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 88        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 84        | 1%      |
| Phison E12 NVMe Controller                                                     | 79        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 79        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 77        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 72        | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 71        | 0.84%   |
| Micron Non-Volatile memory controller                                          | 68        | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 68        | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 67        | 0.79%   |
| JMicron JMB363 SATA/IDE Controller                                             | 62        | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 57        | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 56        | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 55        | 0.65%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 55        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4083      | 56.21%  |
| NVMe | 1471      | 20.25%  |
| IDE  | 1203      | 16.56%  |
| RAID | 490       | 6.75%   |
| SCSI | 9         | 0.12%   |
| SAS  | 8         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4602      | 77.89%  |
| AMD          | 1263      | 21.38%  |
| ARM          | 39        | 0.66%   |
| CentaurHauls | 3         | 0.05%   |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 75        | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 64        | 1.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 62        | 1.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 58        | 0.98%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 57        | 0.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 48        | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 46        | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 46        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 43        | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 42        | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 40        | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 39        | 0.66%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 39        | 0.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 39        | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 39        | 0.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 36        | 0.61%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 35        | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 35        | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 33        | 0.56%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 32        | 0.54%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 32        | 0.54%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 29        | 0.49%   |
| ARM Processor                                 | 28        | 0.47%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 0.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 27        | 0.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 27        | 0.46%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 27        | 0.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 26        | 0.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 26        | 0.44%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 25        | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 24        | 0.41%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 24        | 0.41%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 23        | 0.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 23        | 0.39%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 23        | 0.39%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 23        | 0.39%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 22        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1180      | 19.95%  |
| Intel Core i5           | 1125      | 19.02%  |
| Intel Core i3           | 424       | 7.17%   |
| Intel Core 2 Duo        | 363       | 6.14%   |
| Intel Celeron           | 319       | 5.39%   |
| AMD Ryzen 5             | 267       | 4.51%   |
| Other                   | 257       | 4.34%   |
| Intel Atom              | 219       | 3.7%    |
| AMD Ryzen 7             | 199       | 3.36%   |
| Intel Pentium Dual-Core | 107       | 1.81%   |
| Intel Pentium           | 107       | 1.81%   |
| Intel Core 2 Quad       | 98        | 1.66%   |
| Intel Xeon              | 90        | 1.52%   |
| Intel Core 2            | 66        | 1.12%   |
| Intel Pentium Dual      | 65        | 1.1%    |
| Intel Pentium 4         | 60        | 1.01%   |
| AMD Ryzen 3             | 60        | 1.01%   |
| AMD FX                  | 60        | 1.01%   |
| AMD A8                  | 54        | 0.91%   |
| AMD Ryzen 9             | 52        | 0.88%   |
| AMD Athlon 64 X2        | 48        | 0.81%   |
| AMD E1                  | 43        | 0.73%   |
| AMD A4                  | 41        | 0.69%   |
| AMD A10                 | 39        | 0.66%   |
| Intel Genuine           | 38        | 0.64%   |
| AMD A6                  | 38        | 0.64%   |
| Intel Core i9           | 37        | 0.63%   |
| AMD Sempron             | 30        | 0.51%   |
| AMD Phenom II X4        | 26        | 0.44%   |
| AMD E2                  | 24        | 0.41%   |
| Intel Pentium D         | 23        | 0.39%   |
| AMD Phenom II X6        | 19        | 0.32%   |
| Intel Pentium Silver    | 18        | 0.3%    |
| AMD Athlon II X2        | 18        | 0.3%    |
| AMD Turion 64 X2 Mobile | 15        | 0.25%   |
| AMD Ryzen 5 PRO         | 15        | 0.25%   |
| AMD Athlon              | 15        | 0.25%   |
| Intel Pentium M         | 14        | 0.24%   |
| AMD Ryzen 7 PRO         | 14        | 0.24%   |
| AMD Phenom              | 14        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2506      | 42.36%  |
| 4       | 2204      | 37.25%  |
| 6       | 459       | 7.76%   |
| 8       | 315       | 5.32%   |
| 1       | 280       | 4.73%   |
| 12      | 49        | 0.83%   |
| 3       | 30        | 0.51%   |
| 16      | 19        | 0.32%   |
| 10      | 19        | 0.32%   |
| 14      | 18        | 0.3%    |
| 24      | 5         | 0.08%   |
| Unknown | 5         | 0.08%   |
| 20      | 2         | 0.03%   |
| 5       | 2         | 0.03%   |
| 64      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5857      | 99.14%  |
| 2       | 47        | 0.8%    |
| Unknown | 3         | 0.05%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3456      | 58.41%  |
| 1       | 2456      | 41.51%  |
| Unknown | 5         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5718      | 96.59%  |
| 32-bit         | 116       | 1.96%   |
| Unknown        | 84        | 1.42%   |
| 64-bit         | 2         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1171      | 19.22%  |
| 0x206a7    | 339       | 5.56%   |
| 0x306a9    | 303       | 4.97%   |
| 0x1067a    | 271       | 4.45%   |
| 0x306c3    | 252       | 4.14%   |
| 0x806ea    | 149       | 2.45%   |
| 0x906ea    | 134       | 2.2%    |
| 0x40651    | 127       | 2.08%   |
| 0x806ec    | 123       | 2.02%   |
| 0x6fd      | 122       | 2%      |
| 0x806e9    | 120       | 1.97%   |
| 0x406e3    | 116       | 1.9%    |
| 0x806c1    | 114       | 1.87%   |
| 0x506e3    | 113       | 1.85%   |
| 0x20655    | 105       | 1.72%   |
| 0x906e9    | 103       | 1.69%   |
| 0x10676    | 95        | 1.56%   |
| 0x306d4    | 81        | 1.33%   |
| 0x08701021 | 80        | 1.31%   |
| 0x08108109 | 79        | 1.3%    |
| 0x6fb      | 76        | 1.25%   |
| 0x406c4    | 71        | 1.17%   |
| 0x30678    | 64        | 1.05%   |
| 0x406c3    | 59        | 0.97%   |
| 0x706a1    | 58        | 0.95%   |
| 0x706e5    | 57        | 0.94%   |
| 0x20652    | 55        | 0.9%    |
| 0x806eb    | 48        | 0.79%   |
| 0x6f6      | 46        | 0.76%   |
| 0x0a50000c | 46        | 0.76%   |
| 0x106e5    | 44        | 0.72%   |
| 0x706a8    | 43        | 0.71%   |
| 0x06006705 | 43        | 0.71%   |
| 0x010000c8 | 43        | 0.71%   |
| 0x506c9    | 41        | 0.67%   |
| 0x106ca    | 41        | 0.67%   |
| 0xa0652    | 38        | 0.62%   |
| 0x08608103 | 38        | 0.62%   |
| 0x0800820d | 37        | 0.61%   |
| 0x906ed    | 35        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 878       | 14.84%  |
| Haswell          | 477       | 8.06%   |
| Penryn           | 447       | 7.56%   |
| SandyBridge      | 410       | 6.93%   |
| IvyBridge        | 371       | 6.27%   |
| Core             | 319       | 5.39%   |
| Skylake          | 288       | 4.87%   |
| Silvermont       | 236       | 3.99%   |
| Westmere         | 200       | 3.38%   |
| Zen 2            | 196       | 3.31%   |
| Zen+             | 168       | 2.84%   |
| K10              | 151       | 2.55%   |
| TigerLake        | 139       | 2.35%   |
| Unknown          | 129       | 2.18%   |
| Goldmont plus    | 117       | 1.98%   |
| CometLake        | 113       | 1.91%   |
| K8 Hammer        | 110       | 1.86%   |
| Zen 3            | 108       | 1.83%   |
| Broadwell        | 97        | 1.64%   |
| Excavator        | 95        | 1.61%   |
| Bonnell          | 92        | 1.56%   |
| Zen              | 90        | 1.52%   |
| NetBurst         | 90        | 1.52%   |
| IceLake          | 89        | 1.5%    |
| Piledriver       | 84        | 1.42%   |
| Nehalem          | 84        | 1.42%   |
| Goldmont         | 56        | 0.95%   |
| P6               | 55        | 0.93%   |
| Puma             | 44        | 0.74%   |
| Jaguar           | 44        | 0.74%   |
| K10 Llano        | 30        | 0.51%   |
| Bobcat           | 30        | 0.51%   |
| Steamroller      | 27        | 0.46%   |
| Alderlake Hybrid | 23        | 0.39%   |
| K8 & K10 hybrid  | 15        | 0.25%   |
| Bulldozer        | 9         | 0.15%   |
| Tremont          | 3         | 0.05%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3283      | 47.55%  |
| Nvidia                                       | 1990      | 28.82%  |
| AMD                                          | 1572      | 22.77%  |
| Silicon Integrated Systems [SiS]             | 18        | 0.26%   |
| Matrox Electronics Systems                   | 16        | 0.23%   |
| VIA Technologies                             | 15        | 0.22%   |
| ASPEED Technology                            | 6         | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.04%   |
| S3 Graphics                                  | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 282       | 3.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 220       | 3.06%   |
| Intel UHD Graphics 620                                                                   | 162       | 2.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 154       | 2.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 152       | 2.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 129       | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 129       | 1.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 126       | 1.75%   |
| Intel HD Graphics 620                                                                    | 122       | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 120       | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 109       | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 101       | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 100       | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 99        | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 96        | 1.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 89        | 1.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 83        | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 81        | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 80        | 1.11%   |
| Intel HD Graphics 5500                                                                   | 78        | 1.09%   |
| AMD Renoir                                                                               | 78        | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 68        | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 68        | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 65        | 0.91%   |
| Intel HD Graphics 630                                                                    | 65        | 0.91%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 63        | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 63        | 0.88%   |
| Intel HD Graphics 530                                                                    | 60        | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 59        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 58        | 0.81%   |
| AMD Lucienne                                                                             | 57        | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                               | 56        | 0.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 55        | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 54        | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 54        | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 49        | 0.68%   |
| Intel HD Graphics 500                                                                    | 48        | 0.67%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 48        | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 47        | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 45        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2322      | 39.18%  |
| 1 x AMD                 | 1235      | 20.84%  |
| 1 x Nvidia              | 1167      | 19.69%  |
| Intel + Nvidia          | 757       | 12.77%  |
| Intel + AMD             | 157       | 2.65%   |
| 2 x AMD                 | 120       | 2.02%   |
| AMD + Nvidia            | 52        | 0.88%   |
| Other                   | 43        | 0.73%   |
| 1 x SiS                 | 18        | 0.3%    |
| 1 x VIA                 | 15        | 0.25%   |
| 1 x Matrox              | 9         | 0.15%   |
| 2 x Nvidia              | 8         | 0.13%   |
| Nvidia + Matrox         | 4         | 0.07%   |
| 2 x Intel               | 3         | 0.05%   |
| 1 x XGI                 | 3         | 0.05%   |
| 1 x ASPEED              | 3         | 0.05%   |
| Nvidia + ASPEED         | 2         | 0.03%   |
| AMD + Matrox            | 2         | 0.03%   |
| 3 x AMD                 | 1         | 0.02%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.02%   |
| 1 x S3 Graphics         | 1         | 0.02%   |
| Intel + 2 x AMD         | 1         | 0.02%   |
| AMD + 2 x Nvidia        | 1         | 0.02%   |
| AMD + ASPEED            | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4819      | 80.41%  |
| Proprietary | 961       | 16.04%  |
| Unknown     | 213       | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3126      | 51.52%  |
| 0.01-0.5   | 888       | 14.64%  |
| 1.01-2.0   | 832       | 13.71%  |
| 0.51-1.0   | 559       | 9.21%   |
| 3.01-4.0   | 333       | 5.49%   |
| 7.01-8.0   | 141       | 2.32%   |
| 5.01-6.0   | 118       | 1.94%   |
| 2.01-3.0   | 42        | 0.69%   |
| 8.01-16.0  | 26        | 0.43%   |
| 4.01-5.0   | 1         | 0.02%   |
| 16.01-24.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 929       | 14.99%  |
| AU Optronics            | 748       | 12.07%  |
| Chimei Innolux          | 542       | 8.74%   |
| LG Display              | 516       | 8.32%   |
| BOE                     | 475       | 7.66%   |
| Hewlett-Packard         | 299       | 4.82%   |
| Goldstar                | 296       | 4.77%   |
| Philips                 | 289       | 4.66%   |
| Ancor Communications    | 251       | 4.05%   |
| Acer                    | 197       | 3.18%   |
| Dell                    | 152       | 2.45%   |
| BenQ                    | 141       | 2.27%   |
| Chi Mei Optoelectronics | 125       | 2.02%   |
| Sharp                   | 109       | 1.76%   |
| AOC                     | 107       | 1.73%   |
| Apple                   | 106       | 1.71%   |
| Lenovo                  | 86        | 1.39%   |
| HannStar                | 65        | 1.05%   |
| LG Philips              | 58        | 0.94%   |
| Sony                    | 56        | 0.9%    |
| PANDA                   | 48        | 0.77%   |
| Unknown                 | 35        | 0.56%   |
| LG Electronics          | 34        | 0.55%   |
| InfoVision              | 32        | 0.52%   |
| ASUSTek Computer        | 31        | 0.5%    |
| CPT                     | 21        | 0.34%   |
| Eizo                    | 20        | 0.32%   |
| MSI                     | 17        | 0.27%   |
| Fujitsu Siemens         | 17        | 0.27%   |
| Toshiba                 | 15        | 0.24%   |
| CSO                     | 15        | 0.24%   |
| Vestel Elektronik       | 13        | 0.21%   |
| Quanta Display          | 13        | 0.21%   |
| LGD                     | 13        | 0.21%   |
| Packard Bell            | 12        | 0.19%   |
| Panasonic               | 10        | 0.16%   |
| NEC Computers           | 10        | 0.16%   |
| Iiyama                  | 10        | 0.16%   |
| Belinea                 | 10        | 0.16%   |
| HPN                     | 9         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 59        | 0.93%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 35        | 0.55%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 33        | 0.52%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 31        | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 30        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 29        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 27        | 0.42%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 27        | 0.42%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 26        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 26        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 25        | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 24        | 0.38%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 23        | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 23        | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 23        | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 23        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 21        | 0.33%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 20        | 0.31%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 19        | 0.3%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 19        | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 18        | 0.28%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 18        | 0.28%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 18        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 17        | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 17        | 0.27%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 16        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 16        | 0.25%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 14        | 0.22%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                      | 14        | 0.22%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 14        | 0.22%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 14        | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 14        | 0.22%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 13        | 0.2%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 13        | 0.2%    |
| LG Display LCD Monitor LGD045C 1366x768 344x194mm 15.5-inch              | 13        | 0.2%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 13        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 13        | 0.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.2%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 13        | 0.2%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 12        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2548      | 42.66%  |
| 1366x768 (WXGA)    | 1271      | 21.28%  |
| 3840x2160 (4K)     | 289       | 4.84%   |
| 1280x1024 (SXGA)   | 277       | 4.64%   |
| 1280x800 (WXGA)    | 262       | 4.39%   |
| 1440x900 (WXGA+)   | 208       | 3.48%   |
| 1680x1050 (WSXGA+) | 181       | 3.03%   |
| 2560x1440 (QHD)    | 165       | 2.76%   |
| 1600x900 (HD+)     | 157       | 2.63%   |
| 1920x1200 (WUXGA)  | 91        | 1.52%   |
| 1360x768           | 60        | 1%      |
| 1024x600           | 54        | 0.9%    |
| Unknown            | 54        | 0.9%    |
| 2560x1080          | 38        | 0.64%   |
| 1024x768 (XGA)     | 35        | 0.59%   |
| 2560x1600          | 30        | 0.5%    |
| 2160x1440          | 26        | 0.44%   |
| 3440x1440          | 25        | 0.42%   |
| 3840x1080          | 23        | 0.39%   |
| 2880x1800          | 19        | 0.32%   |
| 1600x1200          | 14        | 0.23%   |
| 3840x2400          | 12        | 0.2%    |
| 1920x540           | 11        | 0.18%   |
| 1280x720 (HD)      | 10        | 0.17%   |
| 3200x1800 (QHD+)   | 8         | 0.13%   |
| 1920x1280          | 8         | 0.13%   |
| 3000x2000          | 7         | 0.12%   |
| 2736x1824          | 6         | 0.1%    |
| 3072x1920          | 5         | 0.08%   |
| 2880x1920          | 4         | 0.07%   |
| 2288x1287          | 4         | 0.07%   |
| 2256x1504          | 4         | 0.07%   |
| 1400x1050          | 4         | 0.07%   |
| 4480x1440          | 3         | 0.05%   |
| 3840x1600          | 3         | 0.05%   |
| 3200x1080          | 3         | 0.05%   |
| 2520x1680          | 3         | 0.05%   |
| 1280x768           | 3         | 0.05%   |
| 8960x2160          | 2         | 0.03%   |
| 800x1280           | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1930      | 31.11%  |
| 13      | 513       | 8.27%   |
| 27      | 424       | 6.83%   |
| 24      | 424       | 6.83%   |
| 21      | 380       | 6.13%   |
| Unknown | 346       | 5.58%   |
| 14      | 335       | 5.4%    |
| 23      | 333       | 5.37%   |
| 17      | 299       | 4.82%   |
| 19      | 247       | 3.98%   |
| 18      | 139       | 2.24%   |
| 12      | 107       | 1.72%   |
| 22      | 97        | 1.56%   |
| 20      | 96        | 1.55%   |
| 10      | 68        | 1.1%    |
| 31      | 66        | 1.06%   |
| 11      | 63        | 1.02%   |
| 34      | 58        | 0.93%   |
| 84      | 36        | 0.58%   |
| 16      | 33        | 0.53%   |
| 54      | 27        | 0.44%   |
| 72      | 23        | 0.37%   |
| 25      | 20        | 0.32%   |
| 32      | 16        | 0.26%   |
| 40      | 15        | 0.24%   |
| 52      | 8         | 0.13%   |
| 42      | 8         | 0.13%   |
| 48      | 7         | 0.11%   |
| 47      | 7         | 0.11%   |
| 37      | 7         | 0.11%   |
| 28      | 7         | 0.11%   |
| 26      | 7         | 0.11%   |
| 46      | 6         | 0.1%    |
| 65      | 5         | 0.08%   |
| 39      | 5         | 0.08%   |
| 8       | 5         | 0.08%   |
| 142     | 4         | 0.06%   |
| 60      | 4         | 0.06%   |
| 43      | 4         | 0.06%   |
| 33      | 4         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2574      | 42.04%  |
| 501-600        | 1096      | 17.9%   |
| 401-500        | 812       | 13.26%  |
| 201-300        | 541       | 8.84%   |
| 351-400        | 369       | 6.03%   |
| Unknown        | 346       | 5.65%   |
| 601-700        | 122       | 1.99%   |
| 701-800        | 78        | 1.27%   |
| 1001-1500      | 72        | 1.18%   |
| 1501-2000      | 61        | 1%      |
| 801-900        | 30        | 0.49%   |
| 901-1000       | 11        | 0.18%   |
| 101-200        | 7         | 0.11%   |
| More than 2000 | 4         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4147      | 72.58%  |
| 16/10   | 787       | 13.77%  |
| Unknown | 287       | 5.02%   |
| 5/4     | 263       | 4.6%    |
| 3/2     | 74        | 1.3%    |
| 4/3     | 68        | 1.19%   |
| 21/9    | 62        | 1.09%   |
| 6/5     | 12        | 0.21%   |
| 32/9    | 6         | 0.11%   |
| 1.00    | 4         | 0.07%   |
| 0.62    | 2         | 0.04%   |
| 2.65    | 1         | 0.02%   |
| 2.21    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1925      | 31.3%   |
| 201-250        | 995       | 16.18%  |
| 81-90          | 602       | 9.79%   |
| 151-200        | 483       | 7.85%   |
| 301-350        | 431       | 7.01%   |
| Unknown        | 346       | 5.63%   |
| 71-80          | 245       | 3.98%   |
| 141-150        | 214       | 3.48%   |
| 351-500        | 145       | 2.36%   |
| 121-130        | 141       | 2.29%   |
| 251-300        | 135       | 2.2%    |
| More than 1000 | 119       | 1.93%   |
| 61-70          | 99        | 1.61%   |
| 41-50          | 67        | 1.09%   |
| 51-60          | 65        | 1.06%   |
| 501-1000       | 61        | 0.99%   |
| 131-140        | 30        | 0.49%   |
| 111-120        | 24        | 0.39%   |
| 91-100         | 17        | 0.28%   |
| 1-40           | 6         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2170      | 35.93%  |
| 101-120       | 1612      | 26.69%  |
| 121-160       | 1387      | 22.96%  |
| Unknown       | 346       | 5.73%   |
| 161-240       | 321       | 5.31%   |
| 1-50          | 108       | 1.79%   |
| More than 240 | 96        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4996      | 83%     |
| 2     | 728       | 12.1%   |
| 0     | 230       | 3.82%   |
| 3     | 62        | 1.03%   |
| 4     | 3         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3197      | 35.74%  |
| Intel                             | 2537      | 28.36%  |
| Qualcomm Atheros                  | 1130      | 12.63%  |
| Broadcom                          | 554       | 6.19%   |
| Marvell Technology Group          | 185       | 2.07%   |
| Nvidia                            | 132       | 1.48%   |
| Broadcom Limited                  | 127       | 1.42%   |
| Ralink Technology                 | 119       | 1.33%   |
| TP-Link                           | 113       | 1.26%   |
| Ralink                            | 98        | 1.1%    |
| MediaTek                          | 66        | 0.74%   |
| Qualcomm Atheros Communications   | 48        | 0.54%   |
| Huawei Technologies               | 47        | 0.53%   |
| D-Link System                     | 38        | 0.42%   |
| ASIX Electronics                  | 35        | 0.39%   |
| Samsung Electronics               | 32        | 0.36%   |
| VIA Technologies                  | 30        | 0.34%   |
| D-Link                            | 29        | 0.32%   |
| Sitecom Europe                    | 28        | 0.31%   |
| Xiaomi                            | 27        | 0.3%    |
| Dell                              | 25        | 0.28%   |
| Silicon Integrated Systems [SiS]  | 23        | 0.26%   |
| NetGear                           | 21        | 0.23%   |
| ASUSTek Computer                  | 19        | 0.21%   |
| Sierra Wireless                   | 17        | 0.19%   |
| JMicron Technology                | 16        | 0.18%   |
| Ericsson Business Mobile Networks | 16        | 0.18%   |
| Microsoft                         | 15        | 0.17%   |
| Attansic Technology               | 15        | 0.17%   |
| Belkin Components                 | 11        | 0.12%   |
| Qualcomm                          | 10        | 0.11%   |
| Microchip Technology              | 10        | 0.11%   |
| Hewlett-Packard                   | 10        | 0.11%   |
| DisplayLink                       | 10        | 0.11%   |
| OPPO Electronics                  | 8         | 0.09%   |
| Gemtek                            | 8         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 7         | 0.08%   |
| Lenovo                            | 7         | 0.08%   |
| Aquantia                          | 7         | 0.08%   |
| Apple                             | 7         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2180      | 21.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 395       | 3.83%   |
| Intel Wi-Fi 6 AX200                                                     | 195       | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 190       | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 184       | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 176       | 1.71%   |
| Intel Wireless 8265 / 8275                                              | 163       | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 152       | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 150       | 1.46%   |
| Intel Wireless 7265                                                     | 136       | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 131       | 1.27%   |
| Intel Wireless 3165                                                     | 129       | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 118       | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 101       | 0.98%   |
| Intel Wi-Fi 6 AX201                                                     | 99        | 0.96%   |
| Intel I211 Gigabit Network Connection                                   | 94        | 0.91%   |
| Intel Ethernet Connection (2) I219-V                                    | 94        | 0.91%   |
| Intel Wireless 7260                                                     | 91        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 85        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 79        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 77        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 74        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 74        | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 71        | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 71        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 70        | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 69        | 0.67%   |
| Intel 82579V Gigabit Network Connection                                 | 66        | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 0.63%   |
| Intel Wireless 8260                                                     | 64        | 0.62%   |
| Intel WiFi Link 5100                                                    | 64        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 64        | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                       | 63        | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                           | 55        | 0.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 53        | 0.51%   |
| Intel Ethernet Connection I217-LM                                       | 51        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 48        | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 45        | 0.44%   |
| Qualcomm Atheros AR9271 802.11n                                         | 45        | 0.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1893      | 39.88%  |
| Qualcomm Atheros                      | 945       | 19.91%  |
| Realtek Semiconductor                 | 814       | 17.15%  |
| Broadcom                              | 361       | 7.6%    |
| Ralink Technology                     | 119       | 2.51%   |
| TP-Link                               | 104       | 2.19%   |
| Ralink                                | 98        | 2.06%   |
| Broadcom Limited                      | 71        | 1.5%    |
| MediaTek                              | 57        | 1.2%    |
| Qualcomm Atheros Communications       | 48        | 1.01%   |
| D-Link System                         | 30        | 0.63%   |
| D-Link                                | 28        | 0.59%   |
| Sitecom Europe                        | 27        | 0.57%   |
| NetGear                               | 21        | 0.44%   |
| ASUSTek Computer                      | 18        | 0.38%   |
| Sierra Wireless                       | 17        | 0.36%   |
| Dell                                  | 16        | 0.34%   |
| Microsoft                             | 12        | 0.25%   |
| Belkin Components                     | 11        | 0.23%   |
| Marvell Technology Group              | 9         | 0.19%   |
| Gemtek                                | 8         | 0.17%   |
| Linksys                               | 6         | 0.13%   |
| AVM                                   | 6         | 0.13%   |
| Fibocom                               | 5         | 0.11%   |
| ZyDAS                                 | 4         | 0.08%   |
| Hewlett-Packard                       | 3         | 0.06%   |
| ZyXEL Communications                  | 2         | 0.04%   |
| U.S. Robotics                         | 2         | 0.04%   |
| Qualcomm                              | 2         | 0.04%   |
| Qcom                                  | 2         | 0.04%   |
| Edimax Technology                     | 2         | 0.04%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Fiberline                             | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 195       | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 184       | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 176       | 3.69%   |
| Intel Wireless 8265 / 8275                                              | 163       | 3.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 152       | 3.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 150       | 3.14%   |
| Intel Wireless 7265                                                     | 136       | 2.85%   |
| Intel Wireless 3165                                                     | 129       | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 118       | 2.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 101       | 2.12%   |
| Intel Wi-Fi 6 AX201                                                     | 99        | 2.07%   |
| Intel Wireless 7260                                                     | 91        | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 85        | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 77        | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 74        | 1.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 74        | 1.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 71        | 1.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 71        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 70        | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 69        | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 1.36%   |
| Intel Wireless 8260                                                     | 64        | 1.34%   |
| Intel WiFi Link 5100                                                    | 64        | 1.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 64        | 1.34%   |
| Broadcom BCM43142 802.11b/g/n                                           | 55        | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 53        | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 45        | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                         | 45        | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 45        | 0.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 41        | 0.86%   |
| Intel Wireless-AC 9260                                                  | 41        | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 40        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 38        | 0.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 37        | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 37        | 0.78%   |
| Realtek 802.11ac NIC                                                    | 35        | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 35        | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 33        | 0.69%   |
| Intel Centrino Advanced-N 6200                                          | 32        | 0.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 30        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2894      | 54.05%  |
| Intel                             | 1195      | 22.32%  |
| Qualcomm Atheros                  | 299       | 5.58%   |
| Broadcom                          | 257       | 4.8%    |
| Marvell Technology Group          | 176       | 3.29%   |
| Nvidia                            | 131       | 2.45%   |
| Broadcom Limited                  | 57        | 1.06%   |
| Huawei Technologies               | 39        | 0.73%   |
| ASIX Electronics                  | 35        | 0.65%   |
| Samsung Electronics               | 30        | 0.56%   |
| VIA Technologies                  | 29        | 0.54%   |
| Xiaomi                            | 27        | 0.5%    |
| Silicon Integrated Systems [SiS]  | 21        | 0.39%   |
| JMicron Technology                | 16        | 0.3%    |
| Attansic Technology               | 15        | 0.28%   |
| DisplayLink                       | 10        | 0.19%   |
| TP-Link                           | 9         | 0.17%   |
| MediaTek                          | 9         | 0.17%   |
| Qualcomm                          | 8         | 0.15%   |
| OPPO Electronics                  | 8         | 0.15%   |
| D-Link System                     | 8         | 0.15%   |
| Lenovo                            | 7         | 0.13%   |
| Aquantia                          | 7         | 0.13%   |
| Apple                             | 7         | 0.13%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.11%   |
| Microchip Technology              | 6         | 0.11%   |
| HMD Global                        | 6         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.09%   |
| 3Com                              | 5         | 0.09%   |
| T & A Mobile Phones               | 4         | 0.07%   |
| Motorola PCS                      | 4         | 0.07%   |
| LG Electronics                    | 3         | 0.06%   |
| ICS Advent                        | 3         | 0.06%   |
| Spreadtrum Communications         | 2         | 0.04%   |
| Google                            | 2         | 0.04%   |
| Foxconn / Hon Hai                 | 2         | 0.04%   |
| ULi Electronics                   | 1         | 0.02%   |
| Sundance Technology Inc / IC Plus | 1         | 0.02%   |
| Standard Microsystems             | 1         | 0.02%   |
| Sitecom Europe                    | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2180      | 40.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 395       | 7.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 190       | 3.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 131       | 2.41%   |
| Intel I211 Gigabit Network Connection                             | 94        | 1.73%   |
| Intel Ethernet Connection (2) I219-V                              | 94        | 1.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 79        | 1.46%   |
| Intel 82579V Gigabit Network Connection                           | 66        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 51        | 0.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 48        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 38        | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 38        | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 38        | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 37        | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 35        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 35        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 34        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 32        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 30        | 0.55%   |
| Intel 82567LM Gigabit Network Connection                          | 30        | 0.55%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 30        | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 29        | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 29        | 0.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 27        | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 27        | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 27        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 26        | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 26        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 26        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 25        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 24        | 0.44%   |
| Huawei SNE-LX1                                                    | 23        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.41%   |
| Nvidia MCP77 Ethernet                                             | 22        | 0.41%   |
| Intel Ethernet Connection (10) I219-V                             | 22        | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 22        | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 21        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5061      | 52.42%  |
| WiFi     | 4493      | 46.54%  |
| Modem    | 89        | 0.92%   |
| Unknown  | 11        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3517      | 58.33%  |
| Ethernet | 2508      | 41.6%   |
| Unknown  | 3         | 0.05%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3214      | 54.24%  |
| 1     | 2460      | 41.51%  |
| 0     | 145       | 2.45%   |
| 3     | 89        | 1.5%    |
| 4     | 13        | 0.22%   |
| 5     | 2         | 0.03%   |
| 12    | 1         | 0.02%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5639      | 94.8%   |
| Yes  | 309       | 5.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1430      | 43.7%   |
| Realtek Semiconductor           | 376       | 11.49%  |
| Cambridge Silicon Radio         | 211       | 6.45%   |
| Qualcomm Atheros Communications | 203       | 6.2%    |
| Broadcom                        | 181       | 5.53%   |
| IMC Networks                    | 167       | 5.1%    |
| Lite-On Technology              | 145       | 4.43%   |
| Apple                           | 115       | 3.51%   |
| Foxconn / Hon Hai               | 114       | 3.48%   |
| Hewlett-Packard                 | 57        | 1.74%   |
| ASUSTek Computer                | 51        | 1.56%   |
| Realtek                         | 45        | 1.38%   |
| Dell                            | 39        | 1.19%   |
| Toshiba                         | 28        | 0.86%   |
| Ralink                          | 28        | 0.86%   |
| Alps Electric                   | 14        | 0.43%   |
| Marvell Semiconductor           | 9         | 0.28%   |
| Integrated System Solution      | 9         | 0.28%   |
| Ralink Technology               | 7         | 0.21%   |
| MediaTek                        | 7         | 0.21%   |
| Foxconn International           | 5         | 0.15%   |
| Askey Computer                  | 4         | 0.12%   |
| TP-Link                         | 3         | 0.09%   |
| Sitecom Europe                  | 3         | 0.09%   |
| Chicony Electronics             | 3         | 0.09%   |
| Belkin Components               | 3         | 0.09%   |
| Unknown                         | 2         | 0.06%   |
| Taiyo Yuden                     | 2         | 0.06%   |
| D-Link System                   | 2         | 0.06%   |
| Conwise Technology              | 2         | 0.06%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| Fujitsu Siemens Computers       | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 606       | 18.52%  |
| Realtek Bluetooth Radio                                                             | 238       | 7.27%   |
| Intel AX201 Bluetooth                                                               | 225       | 6.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 217       | 6.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 211       | 6.45%   |
| Intel AX200 Bluetooth                                                               | 179       | 5.47%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 112       | 3.42%   |
| IMC Networks Bluetooth Device                                                       | 88        | 2.69%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 73        | 2.23%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 63        | 1.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 48        | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 47        | 1.44%   |
| Realtek Bluetooth Radio                                                             | 45        | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 45        | 1.37%   |
| Apple Bluetooth Host Controller                                                     | 45        | 1.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 44        | 1.34%   |
| Lite-On Bluetooth Device                                                            | 38        | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 38        | 1.16%   |
| IMC Networks Bluetooth Radio                                                        | 36        | 1.1%    |
| Broadcom BCM2045 Bluetooth                                                          | 36        | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 35        | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 34        | 1.04%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 29        | 0.89%   |
| Ralink RT3290 Bluetooth                                                             | 28        | 0.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 28        | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 26        | 0.79%   |
| Apple Bluetooth USB Host Controller                                                 | 26        | 0.79%   |
| Apple Bluetooth HCI                                                                 | 26        | 0.79%   |
| Intel AX210 Bluetooth                                                               | 24        | 0.73%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 23        | 0.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 22        | 0.67%   |
| Intel Bluetooth Device                                                              | 18        | 0.55%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 16        | 0.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 16        | 0.49%   |
| IMC Networks Wireless_Device                                                        | 15        | 0.46%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 15        | 0.46%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 15        | 0.46%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 13        | 0.4%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 13        | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4298      | 55.12%  |
| AMD                                  | 1550      | 19.88%  |
| Nvidia                               | 1276      | 16.37%  |
| C-Media Electronics                  | 124       | 1.59%   |
| Logitech                             | 48        | 0.62%   |
| Creative Labs                        | 40        | 0.51%   |
| VIA Technologies                     | 38        | 0.49%   |
| Silicon Integrated Systems [SiS]     | 31        | 0.4%    |
| JMTek                                | 24        | 0.31%   |
| GN Netcom                            | 22        | 0.28%   |
| Texas Instruments                    | 19        | 0.24%   |
| Creative Technology                  | 17        | 0.22%   |
| Realtek Semiconductor                | 15        | 0.19%   |
| Razer USA                            | 15        | 0.19%   |
| M-Audio                              | 15        | 0.19%   |
| Generalplus Technology               | 15        | 0.19%   |
| Focusrite-Novation                   | 14        | 0.18%   |
| BEHRINGER International              | 10        | 0.13%   |
| Kingston Technology                  | 9         | 0.12%   |
| Tenx Technology                      | 8         | 0.1%    |
| Plantronics                          | 8         | 0.1%    |
| Trust                                | 7         | 0.09%   |
| Samson Technologies                  | 7         | 0.09%   |
| Micro Star International             | 7         | 0.09%   |
| Lenovo                               | 7         | 0.09%   |
| Ensoniq                              | 7         | 0.09%   |
| Dell                                 | 7         | 0.09%   |
| ASUSTek Computer                     | 7         | 0.09%   |
| Microsoft                            | 6         | 0.08%   |
| CMX Systems                          | 6         | 0.08%   |
| Apple                                | 6         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.06%   |
| Cambridge Silicon Radio              | 5         | 0.06%   |
| Yamaha                               | 4         | 0.05%   |
| XMOS                                 | 4         | 0.05%   |
| SAVITECH                             | 4         | 0.05%   |
| Huawei Technologies                  | 4         | 0.05%   |
| Hewlett-Packard                      | 4         | 0.05%   |
| Fujitsu                              | 4         | 0.05%   |
| Corsair                              | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 450       | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 378       | 4.15%   |
| AMD Family 17h/19h HD Audio Controller                                     | 372       | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 368       | 4.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 287       | 3.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 280       | 3.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 261       | 2.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 237       | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 203       | 2.23%   |
| AMD FCH Azalia Controller                                                  | 193       | 2.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 186       | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 181       | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 173       | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 162       | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 156       | 1.71%   |
| AMD Starship/Matisse HD Audio Controller                                   | 155       | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 154       | 1.69%   |
| Intel 8 Series HD Audio Controller                                         | 154       | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 142       | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 139       | 1.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 122       | 1.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 121       | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 116       | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 109       | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                   | 107       | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 103       | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                              | 101       | 1.11%   |
| Nvidia High Definition Audio Controller                                    | 100       | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 95        | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 93        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 92        | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 90        | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 89        | 0.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 85        | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 84        | 0.92%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 75        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                  | 73        | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 66        | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 64        | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                         | 63        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 776       | 22.07%  |
| SK hynix                     | 575       | 16.35%  |
| Kingston                     | 444       | 12.63%  |
| Unknown                      | 433       | 12.32%  |
| Micron Technology            | 344       | 9.78%   |
| Crucial                      | 235       | 6.68%   |
| Corsair                      | 203       | 5.77%   |
| G.Skill                      | 74        | 2.1%    |
| Ramaxel Technology           | 67        | 1.91%   |
| Unknown (ABCD)               | 66        | 1.88%   |
| Elpida                       | 58        | 1.65%   |
| A-DATA Technology            | 52        | 1.48%   |
| Nanya Technology             | 38        | 1.08%   |
| Team                         | 28        | 0.8%    |
| Patriot                      | 22        | 0.63%   |
| Unknown                      | 14        | 0.4%    |
| Transcend                    | 11        | 0.31%   |
| ASint Technology             | 10        | 0.28%   |
| Unifosa                      | 7         | 0.2%    |
| Qimonda                      | 6         | 0.17%   |
| Toshiba                      | 5         | 0.14%   |
| 48spaces                     | 4         | 0.11%   |
| Timetec                      | 3         | 0.09%   |
| Hewlett-Packard              | 3         | 0.09%   |
| GeIL                         | 3         | 0.09%   |
| Unknown (AB)                 | 2         | 0.06%   |
| Silicon Power                | 2         | 0.06%   |
| PLEXHD                       | 2         | 0.06%   |
| Patriot Memory (PDP Systems) | 2         | 0.06%   |
| Goldkey                      | 2         | 0.06%   |
| A Force                      | 2         | 0.06%   |
| V-Color                      | 1         | 0.03%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.03%   |
| Unknown (0x8551)             | 1         | 0.03%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.03%   |
| Unigen                       | 1         | 0.03%   |
| TwinMOS                      | 1         | 0.03%   |
| Thermaltake                  | 1         | 0.03%   |
| TakeMS                       | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 49        | 1.3%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 35        | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 33        | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 30        | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 26        | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 25        | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 25        | 0.66%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.58%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 21        | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 20        | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 19        | 0.5%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 19        | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 17        | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 17        | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 17        | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 16        | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 15        | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 15        | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 15        | 0.4%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 15        | 0.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 14        | 0.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.37%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 14        | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 14        | 0.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 14        | 0.37%   |
| Unknown                                                          | 14        | 0.37%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 13        | 0.34%   |
| Unknown RAM Module 4096MB DIMM DDR2 266MT/s                      | 13        | 0.34%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 13        | 0.34%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 13        | 0.34%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1349      | 43.61%  |
| DDR3    | 1055      | 34.11%  |
| DDR2    | 226       | 7.31%   |
| LPDDR4  | 146       | 4.72%   |
| SDRAM   | 112       | 3.62%   |
| LPDDR3  | 82        | 2.65%   |
| Unknown | 71        | 2.3%    |
| DDR     | 28        | 0.91%   |
| DDR5    | 12        | 0.39%   |
| DRAM    | 10        | 0.32%   |
| LPDDR5  | 2         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1797      | 58.53%  |
| DIMM         | 1040      | 33.88%  |
| Row Of Chips | 219       | 7.13%   |
| Chip         | 8         | 0.26%   |
| FB-DIMM      | 4         | 0.13%   |
| Unknown      | 2         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1199      | 36%     |
| 4096  | 1007      | 30.23%  |
| 2048  | 519       | 15.58%  |
| 16384 | 379       | 11.38%  |
| 1024  | 138       | 4.14%   |
| 32768 | 48        | 1.44%   |
| 512   | 33        | 0.99%   |
| 256   | 5         | 0.15%   |
| 3072  | 2         | 0.06%   |
| 32    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 634       | 19.07%  |
| 2667    | 476       | 14.32%  |
| 3200    | 421       | 12.66%  |
| 2400    | 273       | 8.21%   |
| 1333    | 220       | 6.62%   |
| 2133    | 150       | 4.51%   |
| 1334    | 125       | 3.76%   |
| Unknown | 115       | 3.46%   |
| 667     | 102       | 3.07%   |
| 3600    | 95        | 2.86%   |
| 800     | 95        | 2.86%   |
| 1867    | 75        | 2.26%   |
| 1066    | 49        | 1.47%   |
| 4267    | 47        | 1.41%   |
| 3266    | 35        | 1.05%   |
| 1067    | 31        | 0.93%   |
| 3000    | 26        | 0.78%   |
| 2933    | 23        | 0.69%   |
| 3466    | 22        | 0.66%   |
| 533     | 21        | 0.63%   |
| 3733    | 20        | 0.6%    |
| 3400    | 18        | 0.54%   |
| 1866    | 18        | 0.54%   |
| 4199    | 16        | 0.48%   |
| 2048    | 16        | 0.48%   |
| 8400    | 15        | 0.45%   |
| 1800    | 15        | 0.45%   |
| 266     | 15        | 0.45%   |
| 4800    | 14        | 0.42%   |
| 400     | 13        | 0.39%   |
| 2666    | 10        | 0.3%    |
| 3800    | 9         | 0.27%   |
| 975     | 9         | 0.27%   |
| 333     | 9         | 0.27%   |
| 2800    | 7         | 0.21%   |
| 2000    | 7         | 0.21%   |
| 4266    | 6         | 0.18%   |
| 1639    | 5         | 0.15%   |
| 49926   | 4         | 0.12%   |
| 3333    | 4         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 95        | 37.25%  |
| Samsung Electronics   | 43        | 16.86%  |
| Canon                 | 34        | 13.33%  |
| Brother Industries    | 31        | 12.16%  |
| Seiko Epson           | 25        | 9.8%    |
| Lexmark International | 4         | 1.57%   |
| Dymo-CoStar           | 4         | 1.57%   |
| Xerox                 | 3         | 1.18%   |
| Pantum                | 3         | 1.18%   |
| Prolific Technology   | 2         | 0.78%   |
| Oki Data              | 2         | 0.78%   |
| Apple                 | 2         | 0.78%   |
| Toshiba TEC           | 1         | 0.39%   |
| Sato                  | 1         | 0.39%   |
| Sagem                 | 1         | 0.39%   |
| Ricoh                 | 1         | 0.39%   |
| QinHeng Electronics   | 1         | 0.39%   |
| Kyocera               | 1         | 0.39%   |
| ICS Advent            | 1         | 0.39%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2510 Series                                            | 8         | 3.13%   |
| Samsung M2020 Series                                                  | 7         | 2.73%   |
| HP OfficeJet 6950                                                     | 7         | 2.73%   |
| Samsung M267x 287x Series                                             | 6         | 2.34%   |
| HP Deskjet 2050 J510                                                  | 6         | 2.34%   |
| Seiko Epson Printer                                                   | 5         | 1.95%   |
| Samsung ML-216x Series Laser Printer                                  | 5         | 1.95%   |
| HP ENVY 4520 series                                                   | 5         | 1.95%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 4         | 1.56%   |
| HP LaserJet 1018                                                      | 4         | 1.56%   |
| Canon PIXMA MG3600 Series                                             | 4         | 1.56%   |
| Samsung ML-1660 Series                                                | 3         | 1.17%   |
| Samsung ML-1640 Series Laser Printer                                  | 3         | 1.17%   |
| Samsung M2070 Series                                                  | 3         | 1.17%   |
| Samsung Composite Device                                              | 3         | 1.17%   |
| HP Officejet 2620 series                                              | 3         | 1.17%   |
| HP LaserJet Professional P 1102w                                      | 3         | 1.17%   |
| HP LaserJet P1102                                                     | 3         | 1.17%   |
| HP LaserJet P1005                                                     | 3         | 1.17%   |
| HP LaserJet 1200                                                      | 3         | 1.17%   |
| HP ENVY 5000 series                                                   | 3         | 1.17%   |
| HP Deskjet F4500 series                                               | 3         | 1.17%   |
| Dymo-CoStar LabelWriter 450                                           | 3         | 1.17%   |
| Canon LiDE 400                                                        | 3         | 1.17%   |
| Brother MFC-L2700DW                                                   | 3         | 1.17%   |
| Brother HL-3140CW series                                              | 3         | 1.17%   |
| Brother DCP-1610W                                                     | 3         | 1.17%   |
| Samsung SCX-4623 Series                                               | 2         | 0.78%   |
| Prolific PL2305 Parallel Port                                         | 2         | 0.78%   |
| Oki Data USB Device                                                   | 2         | 0.78%   |
| Lexmark International InkJet Color Printer                            | 2         | 0.78%   |
| HP Officejet Pro 6230                                                 | 2         | 0.78%   |
| HP OfficeJet 5200 series                                              | 2         | 0.78%   |
| HP OfficeJet 4650 series                                              | 2         | 0.78%   |
| HP Officejet 4630 series                                              | 2         | 0.78%   |
| HP Officejet 4500 G510n-z                                             | 2         | 0.78%   |
| HP OfficeJet 3830 series                                              | 2         | 0.78%   |
| HP LaserJet P2055 series                                              | 2         | 0.78%   |
| HP LaserJet 1010                                                      | 2         | 0.78%   |
| HP DeskJet F4200 series                                               | 2         | 0.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 36        | 52.17%  |
| Seiko Epson        | 18        | 26.09%  |
| Hewlett-Packard    | 9         | 13.04%  |
| Mustek Systems     | 4         | 5.8%    |
| Ultima Electronics | 1         | 1.45%   |
| Plustek            | 1         | 1.45%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 8         | 11.43%  |
| Canon CanoScan LiDE 210                                                               | 5         | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4         | 5.71%   |
| Canon CanoScan LiDE 120                                                               | 4         | 5.71%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 4.29%   |
| Canon CanoScan LiDE 100                                                               | 3         | 4.29%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 2         | 2.86%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2         | 2.86%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 2.86%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2         | 2.86%   |
| HP Scanjet 200                                                                        | 2         | 2.86%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 2.86%   |
| Canon CanoScan LIDE 25                                                                | 2         | 2.86%   |
| Canon CanoScan LiDE 220                                                               | 2         | 2.86%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.43%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 1.43%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 1.43%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1         | 1.43%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.43%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.43%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 1.43%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1         | 1.43%   |
| Seiko Epson ES-D400 [GT-S80]                                                          | 1         | 1.43%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                                            | 1         | 1.43%   |
| Plustek 600DPI USB Scanner                                                            | 1         | 1.43%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.43%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 1.43%   |
| HP Scanjet G2710                                                                      | 1         | 1.43%   |
| HP ScanJet 3800c                                                                      | 1         | 1.43%   |
| HP ScanJet 3570c                                                                      | 1         | 1.43%   |
| HP ScanJet 3400cse                                                                    | 1         | 1.43%   |
| HP ScanJet 2400c                                                                      | 1         | 1.43%   |
| HP PSC 1200                                                                           | 1         | 1.43%   |
| HP HP4470C                                                                            | 1         | 1.43%   |
| Canon CanoScan LiDE 90                                                                | 1         | 1.43%   |
| Canon CanoScan LiDE 700F                                                              | 1         | 1.43%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 1.43%   |
| Canon CanoScan LiDE 60                                                                | 1         | 1.43%   |
| Canon CanoScan 4400F                                                                  | 1         | 1.43%   |
| Canon CanoScan 4200F                                                                  | 1         | 1.43%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 843       | 23.39%  |
| IMC Networks                           | 391       | 10.85%  |
| Microdia                               | 268       | 7.44%   |
| Realtek Semiconductor                  | 257       | 7.13%   |
| Acer                                   | 241       | 6.69%   |
| Logitech                               | 177       | 4.91%   |
| Suyin                                  | 167       | 4.63%   |
| Quanta                                 | 161       | 4.47%   |
| Sunplus Innovation Technology          | 153       | 4.25%   |
| Cheng Uei Precision Industry (Foxlink) | 131       | 3.63%   |
| Apple                                  | 96        | 2.66%   |
| Alcor Micro                            | 87        | 2.41%   |
| Syntek                                 | 78        | 2.16%   |
| Lite-On Technology                     | 75        | 2.08%   |
| Microsoft                              | 53        | 1.47%   |
| Luxvisions Innotech Limited            | 44        | 1.22%   |
| Ricoh                                  | 43        | 1.19%   |
| Silicon Motion                         | 41        | 1.14%   |
| Z-Star Microelectronics                | 24        | 0.67%   |
| Samsung Electronics                    | 20        | 0.55%   |
| ARC International                      | 17        | 0.47%   |
| Generalplus Technology                 | 15        | 0.42%   |
| Trust                                  | 14        | 0.39%   |
| ALi                                    | 14        | 0.39%   |
| Primax Electronics                     | 13        | 0.36%   |
| KYE Systems (Mouse Systems)            | 10        | 0.28%   |
| GEMBIRD                                | 10        | 0.28%   |
| USB Camera                             | 9         | 0.25%   |
| Cubeternet                             | 9         | 0.25%   |
| Genesys Logic                          | 8         | 0.22%   |
| SunplusIT                              | 7         | 0.19%   |
| Sunplus Technology                     | 7         | 0.19%   |
| Lenovo                                 | 7         | 0.19%   |
| WaveRider Communications               | 6         | 0.17%   |
| Sunplus IT                             | 6         | 0.17%   |
| Importek                               | 6         | 0.17%   |
| Huawei Technologies                    | 6         | 0.17%   |
| DJKANA19IDX53W                         | 6         | 0.17%   |
| DigiTech                               | 6         | 0.17%   |
| 2M UVC CAMERA                          | 6         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 126       | 3.47%   |
| Microdia Integrated_Webcam_HD                           | 88        | 2.42%   |
| Chicony HD Webcam                                       | 81        | 2.23%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 72        | 1.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 68        | 1.87%   |
| Realtek Integrated_Webcam_HD                            | 63        | 1.74%   |
| IMC Networks Integrated Camera                          | 61        | 1.68%   |
| Realtek USB Camera                                      | 58        | 1.6%    |
| Acer Integrated Camera                                  | 57        | 1.57%   |
| Logitech Webcam C270                                    | 54        | 1.49%   |
| Alcor Micro USB 2.0 Camera                              | 41        | 1.13%   |
| Chicony USB2.0 HD UVC WebCam                            | 40        | 1.1%    |
| Syntek Integrated Camera                                | 39        | 1.07%   |
| Chicony USB2.0 VGA UVC WebCam                           | 38        | 1.05%   |
| Sunplus Integrated_Webcam_HD                            | 34        | 0.94%   |
| Chicony HP TrueVision HD                                | 34        | 0.94%   |
| Apple Built-in iSight                                   | 32        | 0.88%   |
| Quanta HP TrueVision HD Camera                          | 31        | 0.85%   |
| Acer Lenovo EasyCamera                                  | 30        | 0.83%   |
| Chicony HP Webcam                                       | 28        | 0.77%   |
| Chicony FJ Camera                                       | 28        | 0.77%   |
| Apple iPhone 5/5C/5S/6/SE                               | 28        | 0.77%   |
| Chicony HP HD Camera                                    | 27        | 0.74%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 26        | 0.72%   |
| Quanta HP Webcam                                        | 25        | 0.69%   |
| Microsoft LifeCam HD-3000                               | 25        | 0.69%   |
| Logitech HD Pro Webcam C920                             | 24        | 0.66%   |
| Sunplus HD WebCam                                       | 23        | 0.63%   |
| Microdia Webcam Vitade AF                               | 23        | 0.63%   |
| Chicony HP Wide Vision HD Camera                        | 23        | 0.63%   |
| Chicony HP TrueVision HD Camera                         | 23        | 0.63%   |
| Alcor Micro Asus Integrated Webcam                      | 22        | 0.61%   |
| Realtek USB2.0 VGA UVC WebCam                           | 21        | 0.58%   |
| Microdia Sonix USB 2.0 Camera                           | 21        | 0.58%   |
| Logitech Webcam C170                                    | 21        | 0.58%   |
| IMC Networks ov9734_azurewave_camera                    | 21        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 21        | 0.58%   |
| Acer HD Webcam                                          | 21        | 0.58%   |
| Suyin HP Truevision HD                                  | 20        | 0.55%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 20        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 180       | 29.46%  |
| Synaptics                  | 153       | 25.04%  |
| Shenzhen Goodix Technology | 107       | 17.51%  |
| Elan Microelectronics      | 65        | 10.64%  |
| AuthenTec                  | 34        | 5.56%   |
| Upek                       | 32        | 5.24%   |
| LighTuning Technology      | 32        | 5.24%   |
| STMicroelectronics         | 4         | 0.65%   |
| Focal-systems.Corp         | 4         | 0.65%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 70        | 11.46%  |
| Unknown                                                                    | 56        | 9.17%   |
| Elan ELAN:ARM-M4                                                           | 41        | 6.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 37        | 6.06%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 5.4%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 4.42%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 4.42%   |
| Elan ELAN:Fingerprint                                                      | 24        | 3.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 22        | 3.6%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 18        | 2.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 2.95%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.78%   |
| Synaptics  WBDI                                                            | 17        | 2.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 2.45%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 2.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 2.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.96%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 1.96%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.8%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.64%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 1.64%   |
| Validity Sensors VFS491                                                    | 9         | 1.47%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.31%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 1.15%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.15%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.15%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 0.98%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 6         | 0.98%   |
| AuthenTec AES1600                                                          | 6         | 0.98%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.82%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.82%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 0.82%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.65%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.65%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.49%   |
| AuthenTec AES2810                                                          | 3         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.49%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 93        | 34.32%  |
| Alcor Micro               | 71        | 26.2%   |
| O2 Micro                  | 27        | 9.96%   |
| Advanced Card Systems     | 19        | 7.01%   |
| Lenovo                    | 15        | 5.54%   |
| BIT4ID                    | 9         | 3.32%   |
| Upek                      | 8         | 2.95%   |
| Gemalto (was Gemplus)     | 8         | 2.95%   |
| Realtek Semiconductor     | 7         | 2.58%   |
| SCM Microsystems          | 3         | 1.11%   |
| OmniKey                   | 3         | 1.11%   |
| Clay Logic                | 3         | 1.11%   |
| Reiner SCT Kartensysteme  | 2         | 0.74%   |
| Microchip Technology      | 1         | 0.37%   |
| In Focus Systems          | 1         | 0.37%   |
| Fujitsu Siemens Computers | 1         | 0.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 67        | 24.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 11.03%  |
| Broadcom 58200                                                               | 26        | 9.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 8.46%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 6.99%   |
| Broadcom 5880                                                                | 16        | 5.88%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 16        | 5.88%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 5.51%   |
| BIT4ID miniLector EVO                                                        | 9         | 3.31%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 2.94%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 7         | 2.57%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.84%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.47%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.47%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.1%    |
| Clay Logic Nitrokey Pro                                                      | 3         | 1.1%    |
| Advanced Card Systems ACR122U                                                | 3         | 1.1%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.74%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.37%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.37%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.37%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.37%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.37%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.37%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.37%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.37%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.37%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4350      | 72.12%  |
| 1     | 1354      | 22.45%  |
| 2     | 285       | 4.72%   |
| 3     | 25        | 0.41%   |
| 4     | 11        | 0.18%   |
| 5     | 5         | 0.08%   |
| 6     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 605       | 30.4%   |
| Graphics card            | 445       | 22.36%  |
| Net/wireless             | 252       | 12.66%  |
| Chipcard                 | 224       | 11.26%  |
| Multimedia controller    | 87        | 4.37%   |
| Communication controller | 68        | 3.42%   |
| Camera                   | 67        | 3.37%   |
| Bluetooth                | 54        | 2.71%   |
| Sound                    | 30        | 1.51%   |
| Unassigned class         | 28        | 1.41%   |
| Storage                  | 28        | 1.41%   |
| Card reader              | 22        | 1.11%   |
| Modem                    | 21        | 1.06%   |
| Flash memory             | 18        | 0.9%    |
| Net/ethernet             | 14        | 0.7%    |
| Network                  | 6         | 0.3%    |
| Storage/raid             | 5         | 0.25%   |
| Dvb card                 | 5         | 0.25%   |
| Firewire controller      | 4         | 0.2%    |
| Video                    | 2         | 0.1%    |
| Tv card                  | 2         | 0.1%    |
| Storage/ide              | 2         | 0.1%    |
| Storage/nvme             | 1         | 0.05%   |

