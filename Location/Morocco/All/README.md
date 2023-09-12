Linux in Morocco - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Morocco/Desktop/README.md) and [notebooks](/Location/Morocco/Notebook/README.md).

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

Total: 402

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X260 20F5S2WX0R    | Notebook    | [cb338af601](https://linux-hardware.org/?probe=cb338af601) | Sep 04, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6df7fe9dca](https://linux-hardware.org/?probe=6df7fe9dca) | Sep 02, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [e180d8d91b](https://linux-hardware.org/?probe=e180d8d91b) | Aug 31, 2023 |
| HP            | Bloog                       | Notebook    | [17077dd340](https://linux-hardware.org/?probe=17077dd340) | Aug 26, 2023 |
| HP            | 3031h                       | Desktop     | [4ce70764b2](https://linux-hardware.org/?probe=4ce70764b2) | Aug 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [74a73b0208](https://linux-hardware.org/?probe=74a73b0208) | Aug 13, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| Acer          | Nitro AN515-53              | Notebook    | [368352c126](https://linux-hardware.org/?probe=368352c126) | Jul 12, 2023 |
| HP            | 158A                        | Desktop     | [4d915b56e7](https://linux-hardware.org/?probe=4d915b56e7) | Jul 08, 2023 |
| HP            | 0AECh D                     | Desktop     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Dell          | Latitude 5540               | Notebook    | [bdf022bb03](https://linux-hardware.org/?probe=bdf022bb03) | Jul 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| HP            | 21F5 0A                     | Desktop     | [dd990a6e99](https://linux-hardware.org/?probe=dd990a6e99) | Jun 26, 2023 |
| Dell          | Latitude 5289               | Notebook    | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [14227e270f](https://linux-hardware.org/?probe=14227e270f) | May 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [21bf9f3d3f](https://linux-hardware.org/?probe=21bf9f3d3f) | May 12, 2023 |
| Dell          | Latitude 5510               | Notebook    | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | Notebook    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| HP            | 1589                        | Desktop     | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| HP            | Pavilion g6                 | Notebook    | [3c4ec29c8a](https://linux-hardware.org/?probe=3c4ec29c8a) | May 05, 2023 |
| American M... | XA133PR110                  | Notebook    | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HP            | 15                          | Notebook    | [17b9906d58](https://linux-hardware.org/?probe=17b9906d58) | May 01, 2023 |
| HP            | 15                          | Notebook    | [8fb1f3c8f8](https://linux-hardware.org/?probe=8fb1f3c8f8) | May 01, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3592ce514a](https://linux-hardware.org/?probe=3592ce514a) | Apr 29, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| HP            | ProBook 5320m               | Notebook    | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| American M... | XA133PR110                  | Notebook    | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| American M... | XA133PR110                  | Notebook    | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| HP            | 0AECh D                     | Desktop     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| HP            | 1494                        | Desktop     | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| HP            | 89B4 A                      | Desktop     | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Dell          | Latitude 5400               | Notebook    | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Dell          | Latitude 5400               | Notebook    | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Dell          | Latitude E5450              | Notebook    | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Dell          | Latitude E6520              | Notebook    | [2774f2cb16](https://linux-hardware.org/?probe=2774f2cb16) | Mar 01, 2023 |
| ASUSTek       | X751LK                      | Notebook    | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [39b27e9850](https://linux-hardware.org/?probe=39b27e9850) | Feb 19, 2023 |
| Dell          | Latitude E7450              | Notebook    | [16f40c9f6a](https://linux-hardware.org/?probe=16f40c9f6a) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [41f9974254](https://linux-hardware.org/?probe=41f9974254) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [b82ad16853](https://linux-hardware.org/?probe=b82ad16853) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [76dd43711a](https://linux-hardware.org/?probe=76dd43711a) | Feb 08, 2023 |
| Toshiba       | Satellite C855-1LG          | Notebook    | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Dell          | Latitude 3500               | Notebook    | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| HP            | 18E7                        | Desktop     | [db4ef3e5f4](https://linux-hardware.org/?probe=db4ef3e5f4) | Jan 30, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [b33f2d5606](https://linux-hardware.org/?probe=b33f2d5606) | Jan 28, 2023 |
| Dell          | Latitude E6410              | Notebook    | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [c5379f6dc1](https://linux-hardware.org/?probe=c5379f6dc1) | Jan 12, 2023 |
| Dell          | 0MN1TX A02                  | Desktop     | [e0099da561](https://linux-hardware.org/?probe=e0099da561) | Jan 11, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [2c092397ea](https://linux-hardware.org/?probe=2c092397ea) | Jan 05, 2023 |
| Dell          | Latitude 5510               | Notebook    | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [15582a281d](https://linux-hardware.org/?probe=15582a281d) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [57fa4478d0](https://linux-hardware.org/?probe=57fa4478d0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Dell          | Latitude D820               | Notebook    | [29df917188](https://linux-hardware.org/?probe=29df917188) | Dec 16, 2022 |
| Dell          | Latitude D820               | Notebook    | [27f19eafce](https://linux-hardware.org/?probe=27f19eafce) | Dec 16, 2022 |
| Dell          | Latitude E7250              | Notebook    | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [5bbe558b2f](https://linux-hardware.org/?probe=5bbe558b2f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS3YN00    | Notebook    | [636921b46c](https://linux-hardware.org/?probe=636921b46c) | Nov 24, 2022 |
| HP            | 15                          | Notebook    | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [c4e67c5f10](https://linux-hardware.org/?probe=c4e67c5f10) | Nov 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| HP            | 15                          | Notebook    | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| HP            | 2AA2                        | Desktop     | [36f40353c8](https://linux-hardware.org/?probe=36f40353c8) | Oct 25, 2022 |
| Linx          | LINX12X64                   | Tablet      | [132f0a1803](https://linux-hardware.org/?probe=132f0a1803) | Oct 24, 2022 |
| Linx          | LINX12X64                   | Tablet      | [5f78d7109f](https://linux-hardware.org/?probe=5f78d7109f) | Oct 24, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | Latitude E4310              | Notebook    | [318726cca9](https://linux-hardware.org/?probe=318726cca9) | Oct 14, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [e31d2052e5](https://linux-hardware.org/?probe=e31d2052e5) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [1bcfb0642f](https://linux-hardware.org/?probe=1bcfb0642f) | Oct 06, 2022 |
| HP            | 1497                        | Desktop     | [17a2f79f3f](https://linux-hardware.org/?probe=17a2f79f3f) | Oct 04, 2022 |
| HP            | 1497                        | Desktop     | [fab365512a](https://linux-hardware.org/?probe=fab365512a) | Oct 04, 2022 |
| HP            | 1497                        | Desktop     | [86ab60b437](https://linux-hardware.org/?probe=86ab60b437) | Sep 30, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [805d4161a8](https://linux-hardware.org/?probe=805d4161a8) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | Desktop     | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| HP            | 18E4                        | Desktop     | [2c113164fd](https://linux-hardware.org/?probe=2c113164fd) | Sep 05, 2022 |
| Dell          | Latitude 5490               | Notebook    | [a3f76e546f](https://linux-hardware.org/?probe=a3f76e546f) | Sep 01, 2022 |
| ASUSTek       | K72Jk                       | Notebook    | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3cca56dc74](https://linux-hardware.org/?probe=3cca56dc74) | Aug 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| Dell          | Latitude E5500              | Notebook    | [5d04270674](https://linux-hardware.org/?probe=5d04270674) | Aug 08, 2022 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [90197434fc](https://linux-hardware.org/?probe=90197434fc) | Aug 08, 2022 |
| HP            | 198E                        | Desktop     | [4327be921d](https://linux-hardware.org/?probe=4327be921d) | Aug 06, 2022 |
| HP            | 198E                        | Desktop     | [284e29b3ea](https://linux-hardware.org/?probe=284e29b3ea) | Aug 06, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [acb31e0818](https://linux-hardware.org/?probe=acb31e0818) | Jul 18, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| Dell          | Latitude D620               | Notebook    | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [44b541373b](https://linux-hardware.org/?probe=44b541373b) | Jul 08, 2022 |
| Dell          | Latitude E6420              | Notebook    | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [334e57a8b2](https://linux-hardware.org/?probe=334e57a8b2) | Jun 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ed68bc8e1d](https://linux-hardware.org/?probe=ed68bc8e1d) | May 31, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | Notebook    | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | Notebook    | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | Notebook    | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [45ad38e728](https://linux-hardware.org/?probe=45ad38e728) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d809b304eb](https://linux-hardware.org/?probe=d809b304eb) | Apr 14, 2022 |
| HP            | Presario C500 (GF852EA#A... | Notebook    | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | Notebook    | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| Medion        | S4401 MD61533               | Convertible | [0017875c99](https://linux-hardware.org/?probe=0017875c99) | Mar 30, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | Notebook    | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | Notebook    | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| HP            | 18E4                        | Desktop     | [e7d597600e](https://linux-hardware.org/?probe=e7d597600e) | Feb 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | Notebook    | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | Notebook    | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | Notebook    | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | Notebook    | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | 3396                        | Desktop     | [e9486b13b8](https://linux-hardware.org/?probe=e9486b13b8) | Jan 20, 2022 |
| HP            | Pavilion g6                 | Notebook    | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| HP            | 1589                        | Desktop     | [402f1722ab](https://linux-hardware.org/?probe=402f1722ab) | Jan 09, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | Notebook    | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| HP            | 8054                        | Desktop     | [13d18f87fe](https://linux-hardware.org/?probe=13d18f87fe) | Dec 30, 2021 |
| HP            | 8054                        | Desktop     | [fcf6deb221](https://linux-hardware.org/?probe=fcf6deb221) | Dec 30, 2021 |
| Timi          | TM1701                      | Notebook    | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| HP            | 1998                        | Desktop     | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | Aspire One 522              | Notebook    | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8a415c9db8](https://linux-hardware.org/?probe=8a415c9db8) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [3027f5288e](https://linux-hardware.org/?probe=3027f5288e) | Dec 04, 2021 |
| HP            | 1998                        | Desktop     | [ffa6c0b239](https://linux-hardware.org/?probe=ffa6c0b239) | Dec 01, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | Notebook    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | Notebook    | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | Notebook    | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [63385716b2](https://linux-hardware.org/?probe=63385716b2) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f8670ddd99](https://linux-hardware.org/?probe=f8670ddd99) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b4fb9ffc24](https://linux-hardware.org/?probe=b4fb9ffc24) | Nov 18, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [acb0ed7655](https://linux-hardware.org/?probe=acb0ed7655) | Nov 16, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b4ebd974c1](https://linux-hardware.org/?probe=b4ebd974c1) | Nov 15, 2021 |
| Apple         | MacBookPro13,3              | Notebook    | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | 1589                        | Desktop     | [789cbfc3fa](https://linux-hardware.org/?probe=789cbfc3fa) | Nov 10, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [70ae8e4cdf](https://linux-hardware.org/?probe=70ae8e4cdf) | Oct 30, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 18E7                        | Desktop     | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | Notebook    | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | Notebook    | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| HP            | 3032h                       | Desktop     | [6914386d3d](https://linux-hardware.org/?probe=6914386d3d) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | Notebook    | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| HP            | 1589                        | Desktop     | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [565fbea977](https://linux-hardware.org/?probe=565fbea977) | Oct 10, 2021 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [92bc4bf86c](https://linux-hardware.org/?probe=92bc4bf86c) | Oct 04, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| HP            | 18E7                        | Desktop     | [e1aa6d3e49](https://linux-hardware.org/?probe=e1aa6d3e49) | Sep 19, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [99c878cd5e](https://linux-hardware.org/?probe=99c878cd5e) | Sep 04, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cece1a32de](https://linux-hardware.org/?probe=cece1a32de) | Aug 21, 2021 |
| HP            | 0AACh                       | Desktop     | [588b35da24](https://linux-hardware.org/?probe=588b35da24) | Aug 21, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [49eb3e8236](https://linux-hardware.org/?probe=49eb3e8236) | Aug 18, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3e73238fc6](https://linux-hardware.org/?probe=3e73238fc6) | Aug 13, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f0faf00d2f](https://linux-hardware.org/?probe=f0faf00d2f) | Aug 09, 2021 |
| Dell          | 0NX0PH A01                  | Desktop     | [8416267437](https://linux-hardware.org/?probe=8416267437) | Aug 09, 2021 |
| HP            | 15                          | Notebook    | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | Notebook    | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| HP            | 339A                        | Desktop     | [7ea04a15cb](https://linux-hardware.org/?probe=7ea04a15cb) | Jul 18, 2021 |
| HP            | 339A                        | Desktop     | [31018180f8](https://linux-hardware.org/?probe=31018180f8) | Jul 16, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | Notebook    | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [77e63e8902](https://linux-hardware.org/?probe=77e63e8902) | Jul 06, 2021 |
| HP            | 3396                        | Desktop     | [28e2f6399c](https://linux-hardware.org/?probe=28e2f6399c) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [513f79e441](https://linux-hardware.org/?probe=513f79e441) | May 26, 2021 |
| HP            | 0AACh                       | Desktop     | [92920ff59a](https://linux-hardware.org/?probe=92920ff59a) | May 26, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| MSI           | 2A9C                        | Desktop     | [db1be00449](https://linux-hardware.org/?probe=db1be00449) | May 02, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| Foxconn       | 2ACA                        | Desktop     | [04556ec49b](https://linux-hardware.org/?probe=04556ec49b) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | Notebook    | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | Notebook    | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7a6947637a](https://linux-hardware.org/?probe=7a6947637a) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [635fc4a0a2](https://linux-hardware.org/?probe=635fc4a0a2) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6bccb5f740](https://linux-hardware.org/?probe=6bccb5f740) | Mar 15, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [1c76380527](https://linux-hardware.org/?probe=1c76380527) | Mar 06, 2021 |
| HP            | 1495                        | Desktop     | [ca9664aff0](https://linux-hardware.org/?probe=ca9664aff0) | Mar 05, 2021 |
| HP            | Notebook                    | Notebook    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [ab67b7aab9](https://linux-hardware.org/?probe=ab67b7aab9) | Feb 22, 2021 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | Notebook    | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | Notebook    | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [c10de13cf0](https://linux-hardware.org/?probe=c10de13cf0) | Feb 05, 2021 |
| Acer          | AO722                       | Notebook    | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7861f8622e](https://linux-hardware.org/?probe=7861f8622e) | Feb 01, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [3475dcd9b6](https://linux-hardware.org/?probe=3475dcd9b6) | Jan 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [8d7a3472b3](https://linux-hardware.org/?probe=8d7a3472b3) | Jan 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | Notebook    | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | Notebook    | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| HP            | 158A                        | Desktop     | [afd1e7439b](https://linux-hardware.org/?probe=afd1e7439b) | Dec 28, 2020 |
| Dell          | Latitude E6440              | Notebook    | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4a4ce9f5d2](https://linux-hardware.org/?probe=4a4ce9f5d2) | Dec 25, 2020 |
| HP            | 650                         | Notebook    | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | Notebook    | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | Notebook    | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| HP            | 304Ah                       | Desktop     | [d5f7af2482](https://linux-hardware.org/?probe=d5f7af2482) | Nov 23, 2020 |
| Dell          | Latitude E6440              | Notebook    | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [193c57b056](https://linux-hardware.org/?probe=193c57b056) | Nov 10, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| Dell          | 0MWYPT A01                  | Desktop     | [3134def56f](https://linux-hardware.org/?probe=3134def56f) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | Notebook    | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | Notebook    | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | Notebook    | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| HP            | 3398                        | Desktop     | [6b7ea8d306](https://linux-hardware.org/?probe=6b7ea8d306) | Aug 27, 2020 |
| Dell          | Latitude E5270              | Notebook    | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | Notebook    | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| HP            | 3397                        | Desktop     | [de9945e027](https://linux-hardware.org/?probe=de9945e027) | Jun 30, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | Notebook    | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | Notebook    | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | Notebook    | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | Notebook    | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | Notebook    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| HP            | 0A04h                       | Desktop     | [c0b180275b](https://linux-hardware.org/?probe=c0b180275b) | May 05, 2020 |
| HP            | 0A04h                       | Desktop     | [bb34c7e807](https://linux-hardware.org/?probe=bb34c7e807) | May 05, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | Notebook    | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | Notebook    | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 3397                        | Desktop     | [37ddb2349c](https://linux-hardware.org/?probe=37ddb2349c) | Mar 20, 2020 |
| HP            | 250 G3                      | Notebook    | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | Notebook    | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | Notebook    | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Unknown       | Unknown                     | Phone       | [4ff689998e](https://linux-hardware.org/?probe=4ff689998e) | Feb 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | Notebook    | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | Notebook    | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | Notebook    | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | Notebook    | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| HP            | 1494                        | Desktop     | [af749848e8](https://linux-hardware.org/?probe=af749848e8) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | Notebook    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | Notebook    | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | Notebook    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Dell          | 0D28YY A03                  | Desktop     | [0be7a39100](https://linux-hardware.org/?probe=0be7a39100) | Jul 14, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | Notebook    | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [730a048dd9](https://linux-hardware.org/?probe=730a048dd9) | Dec 20, 2018 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [36a6a5ce8c](https://linux-hardware.org/?probe=36a6a5ce8c) | Dec 20, 2018 |
| ASUSTek       | F5VL                        | Notebook    | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |
| Dell          | 0DR845                      | Desktop     | [3e45e16507](https://linux-hardware.org/?probe=3e45e16507) | Sep 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 43        | 14.19%  |
| Ubuntu 22.04       | 23        | 7.59%   |
| Ubuntu 18.04       | 17        | 5.61%   |
| Debian 11          | 14        | 4.62%   |
| OpenMandriva 4.2   | 12        | 3.96%   |
| KDE neon 20.04     | 11        | 3.63%   |
| OpenMandriva 4.3   | 10        | 3.3%    |
| Linux Mint 20.2    | 7         | 2.31%   |
| Pop!_OS 22.04      | 6         | 1.98%   |
| OpenMandriva 23.01 | 6         | 1.98%   |
| Zorin 16           | 5         | 1.65%   |
| Ubuntu Unity 16.04 | 5         | 1.65%   |
| Ubuntu 20.10       | 5         | 1.65%   |
| OpenMandriva 4.50  | 5         | 1.65%   |
| Linux Mint 20.3    | 5         | 1.65%   |
| Fedora 38          | 5         | 1.65%   |
| Fedora 33          | 5         | 1.65%   |
| ArcoLinux Rolling  | 5         | 1.65%   |
| Ubuntu 19.10       | 4         | 1.32%   |
| Linux Mint 21      | 4         | 1.32%   |
| Arch               | 4         | 1.32%   |
| Manjaro            | 3         | 0.99%   |
| Linux Mint 21.1    | 3         | 0.99%   |
| Linux Mint 19.3    | 3         | 0.99%   |
| Debian 12          | 3         | 0.99%   |
| Arch Rolling       | 3         | 0.99%   |
| Zorin 15           | 2         | 0.66%   |
| Xubuntu 20.04      | 2         | 0.66%   |
| Xero Rolling       | 2         | 0.66%   |
| Void Linux         | 2         | 0.66%   |
| Ubuntu 21.10       | 2         | 0.66%   |
| Ubuntu 21.04       | 2         | 0.66%   |
| Ubuntu 16.04       | 2         | 0.66%   |
| Pop!_OS 21.10      | 2         | 0.66%   |
| Pop!_OS 21.04      | 2         | 0.66%   |
| Pop!_OS 20.10      | 2         | 0.66%   |
| Parrot 5.0         | 2         | 0.66%   |
| OpenMandriva 23.90 | 2         | 0.66%   |
| KDE neon 22.04     | 2         | 0.66%   |
| Kali 2019.4        | 2         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 94        | 32.98%  |
| OpenMandriva | 33        | 11.58%  |
| Linux Mint   | 22        | 7.72%   |
| Debian       | 17        | 5.96%   |
| Fedora       | 16        | 5.61%   |
| KDE neon     | 13        | 4.56%   |
| Pop!_OS      | 12        | 4.21%   |
| Kali         | 9         | 3.16%   |
| Zorin        | 7         | 2.46%   |
| Manjaro      | 7         | 2.46%   |
| Arch         | 7         | 2.46%   |
| Ubuntu Unity | 6         | 2.11%   |
| ArcoLinux    | 5         | 1.75%   |
| Xubuntu      | 3         | 1.05%   |
| Ubuntu MATE  | 3         | 1.05%   |
| Endless      | 3         | 1.05%   |
| Xero         | 2         | 0.7%    |
| Void Linux   | 2         | 0.7%    |
| SteamOS      | 2         | 0.7%    |
| Raspbian     | 2         | 0.7%    |
| Parrot       | 2         | 0.7%    |
| openSUSE     | 2         | 0.7%    |
| EndeavourOS  | 2         | 0.7%    |
| Elementary   | 2         | 0.7%    |
| BlackPanther | 2         | 0.7%    |
| ROSA         | 1         | 0.35%   |
| RHEL         | 1         | 0.35%   |
| Pear OS      | 1         | 0.35%   |
| Nobara       | 1         | 0.35%   |
| Lubuntu      | 1         | 0.35%   |
| Kubuntu      | 1         | 0.35%   |
| CentOS       | 1         | 0.35%   |
| BunsenLabs   | 1         | 0.35%   |
| blendOS      | 1         | 0.35%   |
| Android      | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 12        | 3.74%   |
| 5.16.7-desktop-1omv4003  | 11        | 3.43%   |
| 6.1.1-desktop-1omv2290   | 6         | 1.87%   |
| 5.4.0-58-generic         | 5         | 1.56%   |
| 5.4.0-48-generic         | 5         | 1.56%   |
| 5.13.0-40-generic        | 5         | 1.56%   |
| 5.8.0-43-generic         | 4         | 1.25%   |
| 5.4.0-42-generic         | 4         | 1.25%   |
| 5.12.4-desktop-1omv4050  | 4         | 1.25%   |
| 5.11.0-37-generic        | 4         | 1.25%   |
| 5.8.0-38-generic         | 3         | 0.93%   |
| 5.3.0-40-generic         | 3         | 0.93%   |
| 5.19.0-41-generic        | 3         | 0.93%   |
| 5.19.0-38-generic        | 3         | 0.93%   |
| 5.17.5-76051705-generic  | 3         | 0.93%   |
| 5.15.0-58-generic        | 3         | 0.93%   |
| 5.15.0-52-generic        | 3         | 0.93%   |
| 5.15.0-46-generic        | 3         | 0.93%   |
| 5.15.0-41-generic        | 3         | 0.93%   |
| 5.13.0-27-generic        | 3         | 0.93%   |
| 5.10.0-21-amd64          | 3         | 0.93%   |
| 6.2.6-76060206-generic   | 2         | 0.62%   |
| 6.2.14-300.fc38.x86_64   | 2         | 0.62%   |
| 6.1.0-9-amd64            | 2         | 0.62%   |
| 5.8.0-48-generic         | 2         | 0.62%   |
| 5.8.0-33-generic         | 2         | 0.62%   |
| 5.4.0-96-generic         | 2         | 0.62%   |
| 5.4.0-90-generic         | 2         | 0.62%   |
| 5.4.0-88-generic         | 2         | 0.62%   |
| 5.4.0-74-generic         | 2         | 0.62%   |
| 5.4.0-65-generic         | 2         | 0.62%   |
| 5.4.0-59-generic         | 2         | 0.62%   |
| 5.4.0-37-generic         | 2         | 0.62%   |
| 5.4.0-33-generic         | 2         | 0.62%   |
| 5.4.0-29-generic         | 2         | 0.62%   |
| 5.3.0-kali2-686-pae      | 2         | 0.62%   |
| 5.3.0-51-generic         | 2         | 0.62%   |
| 5.3.0-28-generic         | 2         | 0.62%   |
| 5.18.19_1                | 2         | 0.62%   |
| 5.15.0-57-generic        | 2         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 13.49%  |
| 5.15.0  | 31        | 10.2%   |
| 5.8.0   | 18        | 5.92%   |
| 5.11.0  | 17        | 5.59%   |
| 4.15.0  | 17        | 5.59%   |
| 5.10.0  | 15        | 4.93%   |
| 5.13.0  | 14        | 4.61%   |
| 5.3.0   | 12        | 3.95%   |
| 5.10.14 | 12        | 3.95%   |
| 5.16.7  | 11        | 3.62%   |
| 5.19.0  | 10        | 3.29%   |
| 6.1.1   | 6         | 1.97%   |
| 5.0.0   | 6         | 1.97%   |
| 6.1.0   | 5         | 1.64%   |
| 5.12.4  | 4         | 1.32%   |
| 4.18.0  | 4         | 1.32%   |
| 6.2.6   | 3         | 0.99%   |
| 5.17.5  | 3         | 0.99%   |
| 5.14.0  | 3         | 0.99%   |
| 4.19.0  | 3         | 0.99%   |
| 6.2.9   | 2         | 0.66%   |
| 6.2.14  | 2         | 0.66%   |
| 6.0.0   | 2         | 0.66%   |
| 5.18.19 | 2         | 0.66%   |
| 5.16.0  | 2         | 0.66%   |
| 5.14.14 | 2         | 0.66%   |
| 6.4.9   | 1         | 0.33%   |
| 6.4.6   | 1         | 0.33%   |
| 6.4.11  | 1         | 0.33%   |
| 6.4.10  | 1         | 0.33%   |
| 6.3.7   | 1         | 0.33%   |
| 6.3.6   | 1         | 0.33%   |
| 6.3.4   | 1         | 0.33%   |
| 6.3.2   | 1         | 0.33%   |
| 6.3.12  | 1         | 0.33%   |
| 6.2.10  | 1         | 0.33%   |
| 6.2.0   | 1         | 0.33%   |
| 6.1.7   | 1         | 0.33%   |
| 6.1.6   | 1         | 0.33%   |
| 6.0.14  | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 13.53%  |
| 5.15    | 38        | 12.54%  |
| 5.10    | 33        | 10.89%  |
| 5.8     | 21        | 6.93%   |
| 5.11    | 20        | 6.6%    |
| 4.15    | 17        | 5.61%   |
| 5.13    | 16        | 5.28%   |
| 5.19    | 14        | 4.62%   |
| 5.16    | 14        | 4.62%   |
| 6.1     | 13        | 4.29%   |
| 5.3     | 12        | 3.96%   |
| 6.2     | 9         | 2.97%   |
| 5.17    | 6         | 1.98%   |
| 5.14    | 6         | 1.98%   |
| 5.0     | 6         | 1.98%   |
| 6.3     | 5         | 1.65%   |
| 5.18    | 5         | 1.65%   |
| 4.18    | 5         | 1.65%   |
| 6.4     | 4         | 1.32%   |
| 6.0     | 4         | 1.32%   |
| 5.12    | 4         | 1.32%   |
| 4.19    | 3         | 0.99%   |
| 5.7     | 1         | 0.33%   |
| 5.6     | 1         | 0.33%   |
| 4.9     | 1         | 0.33%   |
| 4.4     | 1         | 0.33%   |
| 4.14    | 1         | 0.33%   |
| 4.13    | 1         | 0.33%   |
| 3.18    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 267       | 95.36%  |
| i686   | 10        | 3.57%   |
| armv8l | 1         | 0.36%   |
| armv7l | 1         | 0.36%   |
| armv6l | 1         | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 141       | 48.96%  |
| KDE5            | 61        | 21.18%  |
| Unknown         | 19        | 6.6%    |
| X-Cinnamon      | 16        | 5.56%   |
| XFCE            | 15        | 5.21%   |
| KDE             | 9         | 3.13%   |
| Unity           | 6         | 2.08%   |
| MATE            | 6         | 2.08%   |
| LXDE            | 3         | 1.04%   |
| Cinnamon        | 3         | 1.04%   |
| Pantheon        | 2         | 0.69%   |
| xmonad          | 1         | 0.35%   |
| sway            | 1         | 0.35%   |
| qtile           | 1         | 0.35%   |
| KDE4            | 1         | 0.35%   |
| i3              | 1         | 0.35%   |
| GNOME Flashback | 1         | 0.35%   |
| Budgie          | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 222       | 77.35%  |
| Wayland | 52        | 18.12%  |
| Unknown | 9         | 3.14%   |
| Tty     | 4         | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 129       | 44.18%  |
| SDDM    | 55        | 18.84%  |
| GDM     | 38        | 13.01%  |
| GDM3    | 35        | 11.99%  |
| LightDM | 30        | 10.27%  |
| TDM     | 4         | 1.37%   |
| KDM     | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 157       | 55.48%  |
| fr_FR   | 78        | 27.56%  |
| Unknown | 20        | 7.07%   |
| en_GB   | 13        | 4.59%   |
| de_DE   | 3         | 1.06%   |
| C       | 3         | 1.06%   |
| en_AG   | 2         | 0.71%   |
| ar_MA   | 2         | 0.71%   |
| fr_MA   | 1         | 0.35%   |
| fr_CH   | 1         | 0.35%   |
| fr_BE   | 1         | 0.35%   |
| es_ES   | 1         | 0.35%   |
| ar_EG   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 167       | 59.43%  |
| EFI  | 114       | 40.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 213       | 75.8%   |
| Overlay | 35        | 12.46%  |
| Btrfs   | 22        | 7.83%   |
| Unknown | 5         | 1.78%   |
| Xfs     | 3         | 1.07%   |
| Tmpfs   | 3         | 1.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 135       | 47.7%   |
| GPT     | 99        | 34.98%  |
| MBR     | 49        | 17.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 237       | 84.34%  |
| Yes       | 44        | 15.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 60.99%  |
| Yes       | 110       | 39.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 98        | 35.13%  |
| Dell                    | 47        | 16.85%  |
| Lenovo                  | 42        | 15.05%  |
| ASUSTek Computer        | 26        | 9.32%   |
| Acer                    | 9         | 3.23%   |
| Toshiba                 | 8         | 2.87%   |
| Apple                   | 4         | 1.43%   |
| Sony                    | 3         | 1.08%   |
| Packard Bell            | 3         | 1.08%   |
| Foxconn                 | 3         | 1.08%   |
| Unknown                 | 3         | 1.08%   |
| Timi                    | 2         | 0.72%   |
| Samsung Electronics     | 2         | 0.72%   |
| Raspberry Pi Foundation | 2         | 0.72%   |
| Medion                  | 2         | 0.72%   |
| HUAWEI                  | 2         | 0.72%   |
| Gigabyte Technology     | 2         | 0.72%   |
| eMachines               | 2         | 0.72%   |
| American Megatrends     | 2         | 0.72%   |
| Valve                   | 1         | 0.36%   |
| TUXEDO                  | 1         | 0.36%   |
| TrekStor                | 1         | 0.36%   |
| SINTRONES               | 1         | 0.36%   |
| Razer                   | 1         | 0.36%   |
| Pegatron                | 1         | 0.36%   |
| MSI                     | 1         | 0.36%   |
| Mediacom                | 1         | 0.36%   |
| Linx                    | 1         | 0.36%   |
| GPD                     | 1         | 0.36%   |
| Google                  | 1         | 0.36%   |
| Fujitsu Siemens         | 1         | 0.36%   |
| Fujitsu                 | 1         | 0.36%   |
| ECS                     | 1         | 0.36%   |
| Clevo                   | 1         | 0.36%   |
| Casper                  | 1         | 0.36%   |
| ASRock                  | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP EliteBook 8440p                     | 4         | 1.43%   |
| Unknown                                | 4         | 1.43%   |
| HP ProDesk 600 G1 TWR                  | 3         | 1.08%   |
| HP Pavilion g6                         | 3         | 1.08%   |
| HP Laptop 15-dw3xxx                    | 3         | 1.08%   |
| HP EliteBook 840 G2                    | 3         | 1.08%   |
| ASUS X540LA                            | 3         | 1.08%   |
| Timi TM1701                            | 2         | 0.72%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.72%   |
| Lenovo IdeaPad L3 15IML05 81Y3         | 2         | 0.72%   |
| HP ZBook 15                            | 2         | 0.72%   |
| HP Z620 Workstation                    | 2         | 0.72%   |
| HP ProBook 650 G1                      | 2         | 0.72%   |
| HP ProBook 6470b                       | 2         | 0.72%   |
| HP Notebook                            | 2         | 0.72%   |
| HP EliteDesk 800 G1 TWR                | 2         | 0.72%   |
| HP EliteDesk 800 G1 SFF                | 2         | 0.72%   |
| HP EliteBook 8460p                     | 2         | 0.72%   |
| HP Compaq Elite 8300 SFF               | 2         | 0.72%   |
| HP Compaq Elite 8300 CMT               | 2         | 0.72%   |
| HP Compaq dc7800 Convertible Minitower | 2         | 0.72%   |
| HP Compaq 8200 Elite CMT PC            | 2         | 0.72%   |
| HP 250 G5 Notebook PC                  | 2         | 0.72%   |
| Dell OptiPlex 790                      | 2         | 0.72%   |
| Dell Latitude E7450                    | 2         | 0.72%   |
| Dell Latitude E6520                    | 2         | 0.72%   |
| Dell Latitude E6410                    | 2         | 0.72%   |
| Acer Aspire ES1-523                    | 2         | 0.72%   |
| Valve Jupiter                          | 1         | 0.36%   |
| TUXEDO N13xWU                          | 1         | 0.36%   |
| TrekStor Surfbook W2                   | 1         | 0.36%   |
| Toshiba Satellite Pro C650             | 1         | 0.36%   |
| Toshiba Satellite L750                 | 1         | 0.36%   |
| Toshiba Satellite L50-B                | 1         | 0.36%   |
| Toshiba Satellite L50-A-1EL            | 1         | 0.36%   |
| Toshiba Satellite L50-A-1DG            | 1         | 0.36%   |
| Toshiba Satellite C855-2CF             | 1         | 0.36%   |
| Toshiba Satellite C855-1LG             | 1         | 0.36%   |
| Toshiba Satellite C660                 | 1         | 0.36%   |
| Sony VPCEH1L8E                         | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 30        | 10.75%  |
| Lenovo ThinkPad       | 22        | 7.89%   |
| HP EliteBook          | 19        | 6.81%   |
| HP Compaq             | 17        | 6.09%   |
| HP Pavilion           | 10        | 3.58%   |
| HP ProBook            | 9         | 3.23%   |
| HP Laptop             | 9         | 3.23%   |
| Toshiba Satellite     | 8         | 2.87%   |
| Dell OptiPlex         | 6         | 2.15%   |
| Acer Aspire           | 6         | 2.15%   |
| Lenovo IdeaPad        | 5         | 1.79%   |
| HP ProDesk            | 5         | 1.79%   |
| HP EliteDesk          | 5         | 1.79%   |
| HP 250                | 4         | 1.43%   |
| Dell Precision        | 4         | 1.43%   |
| ASUS ROG              | 4         | 1.43%   |
| Unknown               | 4         | 1.43%   |
| Packard Bell EasyNote | 3         | 1.08%   |
| Lenovo ThinkCentre    | 3         | 1.08%   |
| Lenovo ThinkBook      | 3         | 1.08%   |
| HP ZBook              | 3         | 1.08%   |
| Dell Vostro           | 3         | 1.08%   |
| ASUS X540LA           | 3         | 1.08%   |
| Timi TM1701           | 2         | 0.72%   |
| RPi Raspberry         | 2         | 0.72%   |
| Lenovo ThinkStation   | 2         | 0.72%   |
| HP Z620               | 2         | 0.72%   |
| HP Notebook           | 2         | 0.72%   |
| Dell XPS              | 2         | 0.72%   |
| Dell Inspiron         | 2         | 0.72%   |
| ASUS PRIME            | 2         | 0.72%   |
| Valve Jupiter         | 1         | 0.36%   |
| TUXEDO N13xWU         | 1         | 0.36%   |
| TrekStor Surfbook     | 1         | 0.36%   |
| Sony VPCEH1L8E        | 1         | 0.36%   |
| Sony VGN-FW11L        | 1         | 0.36%   |
| Sony SVE14122CAW      | 1         | 0.36%   |
| SINTRONES AMB-5000G1  | 1         | 0.36%   |
| Samsung 355V4C        | 1         | 0.36%   |
| Samsung 300E4A        | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 31        | 11.11%  |
| 2011    | 28        | 10.04%  |
| 2010    | 24        | 8.6%    |
| 2018    | 23        | 8.24%   |
| 2014    | 22        | 7.89%   |
| 2012    | 21        | 7.53%   |
| 2016    | 18        | 6.45%   |
| 2015    | 18        | 6.45%   |
| 2017    | 17        | 6.09%   |
| 2020    | 16        | 5.73%   |
| 2021    | 15        | 5.38%   |
| 2019    | 13        | 4.66%   |
| 2007    | 9         | 3.23%   |
| 2009    | 7         | 2.51%   |
| 2008    | 6         | 2.15%   |
| 2022    | 3         | 1.08%   |
| 2006    | 2         | 0.72%   |
| 2004    | 2         | 0.72%   |
| Unknown | 2         | 0.72%   |
| 2023    | 1         | 0.36%   |
| 2005    | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 202       | 72.4%   |
| Desktop        | 67        | 24.01%  |
| Convertible    | 5         | 1.79%   |
| System on chip | 2         | 0.72%   |
| Phone          | 1         | 0.36%   |
| Tablet         | 1         | 0.36%   |
| All in one     | 1         | 0.36%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 266       | 93.66%  |
| Enabled  | 18        | 6.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 277       | 99.28%  |
| Yes  | 2         | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 90        | 32.03%  |
| 3.01-4.0    | 70        | 24.91%  |
| 8.01-16.0   | 38        | 13.52%  |
| 16.01-24.0  | 36        | 12.81%  |
| 1.01-2.0    | 18        | 6.41%   |
| 32.01-64.0  | 8         | 2.85%   |
| 24.01-32.0  | 7         | 2.49%   |
| 2.01-3.0    | 6         | 2.14%   |
| 64.01-256.0 | 5         | 1.78%   |
| 0.51-1.0    | 2         | 0.71%   |
| 0.01-0.5    | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 115       | 37.7%   |
| 2.01-3.0  | 89        | 29.18%  |
| 3.01-4.0  | 40        | 13.11%  |
| 4.01-8.0  | 39        | 12.79%  |
| 0.51-1.0  | 16        | 5.25%   |
| 8.01-16.0 | 4         | 1.31%   |
| 0.01-0.5  | 2         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 214       | 75.62%  |
| 2      | 52        | 18.37%  |
| 3      | 14        | 4.95%   |
| 4      | 3         | 1.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 146       | 52.33%  |
| Yes       | 133       | 47.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 89.25%  |
| No        | 30        | 10.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 248       | 88.57%  |
| No        | 32        | 11.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 60.28%  |
| No        | 112       | 39.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Morocco | 279       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Casablanca       | 75        | 25.08%  |
| Marrakesh        | 28        | 9.36%   |
| Rabat            | 24        | 8.03%   |
| Fes              | 23        | 7.69%   |
| Agadir           | 22        | 7.36%   |
| Salé            | 15        | 5.02%   |
| Tangier          | 14        | 4.68%   |
| Kenitra          | 12        | 4.01%   |
| Meknes           | 10        | 3.34%   |
| Oujda            | 9         | 3.01%   |
| Khouribga        | 7         | 2.34%   |
| Nador            | 5         | 1.67%   |
| Tiznit           | 4         | 1.34%   |
| El Jadida        | 4         | 1.34%   |
| Temara           | 3         | 1%      |
| Taza             | 3         | 1%      |
| Beni Mellal      | 3         | 1%      |
| Youssoufia       | 2         | 0.67%   |
| Tétouan         | 2         | 0.67%   |
| Skhirate         | 2         | 0.67%   |
| Safi             | 2         | 0.67%   |
| Mohammedia       | 2         | 0.67%   |
| Guelmim          | 2         | 0.67%   |
| Berkane          | 2         | 0.67%   |
| Tit Mellil       | 1         | 0.33%   |
| Targuist         | 1         | 0.33%   |
| Taourirt         | 1         | 0.33%   |
| Taounate         | 1         | 0.33%   |
| Sidi Slimane     | 1         | 0.33%   |
| Sidi Lmokhtar    | 1         | 0.33%   |
| Sidi Kacem       | 1         | 0.33%   |
| Settat           | 1         | 0.33%   |
| Sefrou           | 1         | 0.33%   |
| Ouirgane         | 1         | 0.33%   |
| Midelt           | 1         | 0.33%   |
| Ksar El Kebir    | 1         | 0.33%   |
| Khemisset        | 1         | 0.33%   |
| Karia Ba Mohamed | 1         | 0.33%   |
| Inezgane         | 1         | 0.33%   |
| Errachidia       | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 57        | 74     | 16.67%  |
| WDC                         | 48        | 64     | 14.04%  |
| Samsung Electronics         | 43        | 56     | 12.57%  |
| Toshiba                     | 37        | 53     | 10.82%  |
| Hitachi                     | 21        | 26     | 6.14%   |
| Unknown                     | 17        | 23     | 4.97%   |
| HGST                        | 12        | 12     | 3.51%   |
| SanDisk                     | 11        | 11     | 3.22%   |
| Intel                       | 10        | 11     | 2.92%   |
| Kingston                    | 7         | 9      | 2.05%   |
| Apple                       | 6         | 6      | 1.75%   |
| SK hynix                    | 5         | 5      | 1.46%   |
| KIOXIA                      | 5         | 5      | 1.46%   |
| China                       | 5         | 6      | 1.46%   |
| PNY                         | 4         | 5      | 1.17%   |
| Micron Technology           | 4         | 6      | 1.17%   |
| LITEON                      | 4         | 4      | 1.17%   |
| Fujitsu                     | 4         | 4      | 1.17%   |
| Crucial                     | 4         | 5      | 1.17%   |
| Phison                      | 3         | 4      | 0.88%   |
| KingFast                    | 3         | 4      | 0.88%   |
| Unknown                     | 3         | 3      | 0.88%   |
| KingDian                    | 2         | 6      | 0.58%   |
| GOODRAM                     | 2         | 2      | 0.58%   |
| TwinMOS                     | 1         | 1      | 0.29%   |
| Transcend                   | 1         | 1      | 0.29%   |
| Supersonic                  | 1         | 2      | 0.29%   |
| SPCC                        | 1         | 2      | 0.29%   |
| ShiJi                       | 1         | 2      | 0.29%   |
| Realtek Semiconductor       | 1         | 1      | 0.29%   |
| RCESSD                      | 1         | 1      | 0.29%   |
| O2 Micro                    | 1         | 1      | 0.29%   |
| Mushkin                     | 1         | 1      | 0.29%   |
| Magnetic Data               | 1         | 1      | 0.29%   |
| LITEONIT                    | 1         | 1      | 0.29%   |
| Lexar                       | 1         | 1      | 0.29%   |
| Kingston Technology Company | 1         | 1      | 0.29%   |
| KingSpec                    | 1         | 1      | 0.29%   |
| Intenso                     | 1         | 2      | 0.29%   |
| Indilinx                    | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 6         | 1.66%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 1.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 1.39%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 1.11%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 1.11%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 3         | 0.83%   |
| Unknown MMC Card  32GB                 | 3         | 0.83%   |
| Toshiba MQ01ACF050 500GB               | 3         | 0.83%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.83%   |
| Toshiba MQ01ABD050 500GB               | 3         | 0.83%   |
| Seagate ST9500325AS 500GB              | 3         | 0.83%   |
| Seagate ST500LM000-1EJ162 500GB        | 3         | 0.83%   |
| Seagate ST500DM002-1BD142 500GB        | 3         | 0.83%   |
| Seagate ST3250312AS 250GB              | 3         | 0.83%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.83%   |
| Intel SSDSC2BF180A4H 180GB             | 3         | 0.83%   |
| Hitachi HUA723020ALA641 2TB            | 3         | 0.83%   |
| HGST HTS725050A7E630 500GB             | 3         | 0.83%   |
| HGST HTS545050A7E680 500GB             | 3         | 0.83%   |
| Unknown                                | 3         | 0.83%   |
| WDC WD800JD-00LSA0 80GB                | 2         | 0.55%   |
| WDC WD5000LPCX-80VHAT1 500GB           | 2         | 0.55%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 0.55%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 0.55%   |
| WDC WD10SPZX-60Z10T0 1TB               | 2         | 0.55%   |
| Unknown MMC Card  64GB                 | 2         | 0.55%   |
| Unknown MMC Card  16GB                 | 2         | 0.55%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.55%   |
| Toshiba MQ01ABD050V -63 500GB          | 2         | 0.55%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.55%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 0.55%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 0.55%   |
| Samsung MZVLB512HAJQ-000L7 512GB       | 2         | 0.55%   |
| Samsung MZVLB1T0HALR-00000 1TB         | 2         | 0.55%   |
| Samsung MZ7LN128HCHP-000H1 128GB SSD   | 2         | 0.55%   |
| PNY CS900 120GB SSD                    | 2         | 0.55%   |
| LITEON IT LCS-128L9S-HP 128GB SSD      | 2         | 0.55%   |
| KingFast SSD 256GB                     | 2         | 0.55%   |
| Hitachi HUS724030ALE641 3TB            | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 74     | 31.67%  |
| WDC                 | 44        | 60     | 24.44%  |
| Toshiba             | 31        | 40     | 17.22%  |
| Hitachi             | 21        | 26     | 11.67%  |
| HGST                | 12        | 12     | 6.67%   |
| Samsung Electronics | 6         | 9      | 3.33%   |
| Fujitsu             | 4         | 4      | 2.22%   |
| Apple               | 2         | 2      | 1.11%   |
| Magnetic Data       | 1         | 1      | 0.56%   |
| IBM/Hitachi         | 1         | 1      | 0.56%   |
| HPE                 | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 18     | 15.29%  |
| SanDisk             | 8         | 8      | 9.41%   |
| Kingston            | 6         | 8      | 7.06%   |
| Intel               | 5         | 6      | 5.88%   |
| China               | 5         | 6      | 5.88%   |
| PNY                 | 4         | 5      | 4.71%   |
| Micron Technology   | 4         | 6      | 4.71%   |
| LITEON              | 4         | 4      | 4.71%   |
| Crucial             | 4         | 5      | 4.71%   |
| SK hynix            | 3         | 3      | 3.53%   |
| KingFast            | 3         | 3      | 3.53%   |
| KingDian            | 2         | 6      | 2.35%   |
| GOODRAM             | 2         | 2      | 2.35%   |
| Apple               | 2         | 2      | 2.35%   |
| Unknown             | 2         | 2      | 2.35%   |
| WDC                 | 1         | 1      | 1.18%   |
| TwinMOS             | 1         | 1      | 1.18%   |
| Transcend           | 1         | 1      | 1.18%   |
| Toshiba             | 1         | 1      | 1.18%   |
| Supersonic          | 1         | 2      | 1.18%   |
| SPCC                | 1         | 2      | 1.18%   |
| RCESSD              | 1         | 1      | 1.18%   |
| Mushkin             | 1         | 1      | 1.18%   |
| LITEONIT            | 1         | 1      | 1.18%   |
| Lexar               | 1         | 1      | 1.18%   |
| KingSpec            | 1         | 1      | 1.18%   |
| Indilinx            | 1         | 1      | 1.18%   |
| HS-SSD-E100         | 1         | 1      | 1.18%   |
| Hewlett-Packard     | 1         | 1      | 1.18%   |
| BIWIN               | 1         | 1      | 1.18%   |
| Apacer              | 1         | 1      | 1.18%   |
| A-DATA Technology   | 1         | 1      | 1.18%   |
| 2.5"                | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 167       | 230    | 52.19%  |
| SSD     | 79        | 104    | 24.69%  |
| NVMe    | 54        | 70     | 16.88%  |
| MMC     | 17        | 23     | 5.31%   |
| Unknown | 3         | 6      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 227       | 336    | 75.67%  |
| NVMe | 54        | 70     | 18%     |
| MMC  | 17        | 23     | 5.67%   |
| SAS  | 2         | 4      | 0.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 175       | 234    | 71.72%  |
| 0.51-1.0   | 57        | 84     | 23.36%  |
| 1.01-2.0   | 8         | 11     | 3.28%   |
| 2.01-3.0   | 2         | 3      | 0.82%   |
| 3.01-4.0   | 1         | 1      | 0.41%   |
| 4.01-10.0  | 1         | 1      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 26.83%  |
| 251-500        | 74        | 25.78%  |
| 51-100         | 33        | 11.5%   |
| 1-20           | 31        | 10.8%   |
| 501-1000       | 26        | 9.06%   |
| 21-50          | 22        | 7.67%   |
| 1001-2000      | 10        | 3.48%   |
| Unknown        | 7         | 2.44%   |
| More than 3000 | 5         | 1.74%   |
| 2001-3000      | 2         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 131       | 42.95%  |
| 21-50          | 66        | 21.64%  |
| 51-100         | 39        | 12.79%  |
| 101-250        | 37        | 12.13%  |
| 251-500        | 13        | 4.26%   |
| Unknown        | 7         | 2.3%    |
| 1001-2000      | 4         | 1.31%   |
| 501-1000       | 4         | 1.31%   |
| More than 3000 | 3         | 0.98%   |
| 2001-3000      | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                        | 3         | 3      | 6.82%   |
| Seagate ST500DM002-1BD142 500GB                  | 3         | 3      | 6.82%   |
| Toshiba MQ01ABD050 500GB                         | 2         | 2      | 4.55%   |
| Seagate ST500LM021-1KJ152 500GB                  | 2         | 2      | 4.55%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 4.55%   |
| Hitachi HDS721680PLA380 80GB                     | 2         | 3      | 4.55%   |
| WDC WD800AAJS-60WAA0 80GB                        | 1         | 1      | 2.27%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 2.27%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 2.27%   |
| WDC WD2500AAJS-60Z0A0 250GB                      | 1         | 1      | 2.27%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 5      | 2.27%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.27%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 2.27%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 2.27%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 2.27%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 2.27%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 2.27%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.27%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 2.27%   |
| Seagate ST340016A 40GB                           | 1         | 1      | 2.27%   |
| Seagate ST340014AS 40GB                          | 1         | 1      | 2.27%   |
| Seagate ST3250312AS 250GB                        | 1         | 1      | 2.27%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 2.27%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.27%   |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 2.27%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 2.27%   |
| Kingston SA400S37480G 480GB SSD                  | 1         | 2      | 2.27%   |
| HPE MM1000GBKAL 1TB                              | 1         | 1      | 2.27%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 2.27%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 2.27%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 2.27%   |
| HGST HTS545032A7E660 320GB                       | 1         | 1      | 2.27%   |
| Fujitsu MHX2300BT 304GB                          | 1         | 1      | 2.27%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 2.27%   |
| Apple HDD HTS541010A9E662 1TB                    | 1         | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 34.09%  |
| Toshiba             | 7         | 7      | 15.91%  |
| Hitachi             | 6         | 8      | 13.64%  |
| WDC                 | 5         | 9      | 11.36%  |
| Samsung Electronics | 2         | 2      | 4.55%   |
| HGST                | 2         | 2      | 4.55%   |
| Fujitsu             | 2         | 2      | 4.55%   |
| SanDisk             | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| Kingston            | 1         | 2      | 2.27%   |
| HPE                 | 1         | 1      | 2.27%   |
| Apple               | 1         | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 37.5%   |
| Toshiba             | 7         | 7      | 17.5%   |
| Hitachi             | 6         | 8      | 15%     |
| WDC                 | 5         | 9      | 12.5%   |
| HGST                | 2         | 2      | 5%      |
| Fujitsu             | 2         | 2      | 5%      |
| Samsung Electronics | 1         | 1      | 2.5%    |
| HPE                 | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 46     | 90.7%   |
| SSD  | 4         | 5      | 9.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD800JD-00LSA0 80GB                    | 2         | 3      | 50%     |
| WDC WD2500BEVT-22A23T0 208GB               | 1         | 2      | 25%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 5      | 75%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 162       | 240    | 53.29%  |
| Works    | 95        | 136    | 31.25%  |
| Malfunc  | 43        | 51     | 14.14%  |
| Failed   | 4         | 6      | 1.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 223       | 73.36%  |
| Samsung Electronics              | 25        | 8.22%   |
| AMD                              | 22        | 7.24%   |
| Toshiba America Info Systems     | 5         | 1.64%   |
| SanDisk                          | 5         | 1.64%   |
| KIOXIA                           | 5         | 1.64%   |
| Phison Electronics               | 3         | 0.99%   |
| Nvidia                           | 3         | 0.99%   |
| SK hynix                         | 2         | 0.66%   |
| Silicon Integrated Systems [SiS] | 2         | 0.66%   |
| Kingston Technology Company      | 2         | 0.66%   |
| Realtek Semiconductor            | 1         | 0.33%   |
| O2 Micro                         | 1         | 0.33%   |
| LSI Logic / Symbios Logic        | 1         | 0.33%   |
| JMicron Technology               | 1         | 0.33%   |
| Broadcom / LSI                   | 1         | 0.33%   |
| Apple                            | 1         | 0.33%   |
| ADATA Technology                 | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 22        | 6.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 20        | 5.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19        | 5.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15        | 4.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 15        | 4.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 14        | 4.01%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 4.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 3.44%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.29%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 2.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 8         | 2.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7         | 2.01%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 2.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 2.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 2.01%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.72%   |
| Samsung NVMe SSD Controller 980                                                         | 5         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.15%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 3         | 0.86%   |
| Intel SSD 660P Series                                                                   | 3         | 0.86%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3         | 0.86%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3         | 0.86%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3         | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.86%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.86%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 0.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.57%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 2         | 0.57%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 0.57%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.57%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.57%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 197       | 60.43%  |
| NVMe | 54        | 16.56%  |
| RAID | 40        | 12.27%  |
| IDE  | 31        | 9.51%   |
| SAS  | 3         | 0.92%   |
| SCSI | 1         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 246       | 88.17%  |
| AMD    | 30        | 10.75%  |
| ARM    | 3         | 1.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 2.51%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 2.15%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 2.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 1.79%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 1.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5         | 1.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 1.79%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 1.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.43%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.43%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.43%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.43%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.08%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3         | 1.08%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.08%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.08%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 1.08%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 3         | 1.08%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.08%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 2         | 0.72%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 2         | 0.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.72%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 0.72%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 2         | 0.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 0.72%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.72%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.72%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.72%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 0.72%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.72%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 2         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 101       | 36.2%   |
| Intel Core i7           | 46        | 16.49%  |
| Intel Core i3           | 34        | 12.19%  |
| Other                   | 14        | 5.02%   |
| Intel Core 2 Duo        | 13        | 4.66%   |
| Intel Xeon              | 9         | 3.23%   |
| Intel Celeron           | 8         | 2.87%   |
| Intel Atom              | 6         | 2.15%   |
| AMD Ryzen 5             | 6         | 2.15%   |
| Intel Pentium Dual-Core | 4         | 1.43%   |
| AMD Ryzen 9             | 3         | 1.08%   |
| AMD Ryzen 7             | 3         | 1.08%   |
| AMD E1                  | 3         | 1.08%   |
| Intel Pentium           | 2         | 0.72%   |
| ARM BCM                 | 2         | 0.72%   |
| AMD C-60                | 2         | 0.72%   |
| AMD Athlon 64 X2        | 2         | 0.72%   |
| AMD A8                  | 2         | 0.72%   |
| AMD A6                  | 2         | 0.72%   |
| Intel Pentium Silver    | 1         | 0.36%   |
| Intel Pentium M         | 1         | 0.36%   |
| Intel Pentium Gold      | 1         | 0.36%   |
| Intel Pentium Dual      | 1         | 0.36%   |
| Intel Pentium 4         | 1         | 0.36%   |
| Intel Genuine           | 1         | 0.36%   |
| Intel Core i9           | 1         | 0.36%   |
| Intel Core 2 Quad       | 1         | 0.36%   |
| Intel Core 2            | 1         | 0.36%   |
| Intel Celeron M         | 1         | 0.36%   |
| ARM AArch64             | 1         | 0.36%   |
| AMD Ryzen 7 PRO         | 1         | 0.36%   |
| AMD Ryzen 3             | 1         | 0.36%   |
| AMD Phenom II X6        | 1         | 0.36%   |
| AMD E                   | 1         | 0.36%   |
| AMD Athlon XP           | 1         | 0.36%   |
| AMD A4                  | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 152       | 54.48%  |
| 4      | 93        | 33.33%  |
| 6      | 10        | 3.58%   |
| 1      | 8         | 2.87%   |
| 8      | 7         | 2.51%   |
| 12     | 4         | 1.43%   |
| 16     | 3         | 1.08%   |
| 10     | 2         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 274       | 98.21%  |
| 2      | 5         | 1.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 194       | 69.53%  |
| 1      | 85        | 30.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 270       | 96.77%  |
| 32-bit         | 5         | 1.79%   |
| Unknown        | 4         | 1.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 65        | 22.89%  |
| 0x206a7    | 25        | 8.8%    |
| 0x306c3    | 19        | 6.69%   |
| 0x306a9    | 16        | 5.63%   |
| 0x306d4    | 14        | 4.93%   |
| 0x806ea    | 12        | 4.23%   |
| 0x40651    | 11        | 3.87%   |
| 0x806ec    | 9         | 3.17%   |
| 0x20655    | 9         | 3.17%   |
| 0x1067a    | 8         | 2.82%   |
| 0x806c1    | 7         | 2.46%   |
| 0x506e3    | 7         | 2.46%   |
| 0x806e9    | 6         | 2.11%   |
| 0x406e3    | 6         | 2.11%   |
| 0x6fd      | 5         | 1.76%   |
| 0x20652    | 5         | 1.76%   |
| 0x30678    | 4         | 1.41%   |
| 0x906e9    | 3         | 1.06%   |
| 0x6fb      | 3         | 1.06%   |
| 0x206d7    | 3         | 1.06%   |
| 0x10676    | 3         | 1.06%   |
| 0x0a50000c | 3         | 1.06%   |
| 0x08701021 | 3         | 1.06%   |
| 0x906ea    | 2         | 0.7%    |
| 0x706e5    | 2         | 0.7%    |
| 0x406c4    | 2         | 0.7%    |
| 0x406c3    | 2         | 0.7%    |
| 0x08108102 | 2         | 0.7%    |
| 0x07030105 | 2         | 0.7%    |
| 0x0700010f | 2         | 0.7%    |
| 0x05000119 | 2         | 0.7%    |
| 0xf29      | 1         | 0.35%   |
| 0xb06a3    | 1         | 0.35%   |
| 0x90675    | 1         | 0.35%   |
| 0x806eb    | 1         | 0.35%   |
| 0x806d1    | 1         | 0.35%   |
| 0x706a1    | 1         | 0.35%   |
| 0x6ec      | 1         | 0.35%   |
| 0x6e8      | 1         | 0.35%   |
| 0x6d8      | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 14.7%   |
| Haswell          | 41        | 14.7%   |
| SandyBridge      | 30        | 10.75%  |
| Westmere         | 20        | 7.17%   |
| Skylake          | 19        | 6.81%   |
| IvyBridge        | 19        | 6.81%   |
| Broadwell        | 17        | 6.09%   |
| Penryn           | 13        | 4.66%   |
| Silvermont       | 10        | 3.58%   |
| TigerLake        | 9         | 3.23%   |
| Core             | 9         | 3.23%   |
| Unknown          | 7         | 2.51%   |
| Zen 3            | 5         | 1.79%   |
| Zen 2            | 4         | 1.43%   |
| IceLake          | 4         | 1.43%   |
| Bobcat           | 4         | 1.43%   |
| Zen+             | 3         | 1.08%   |
| P6               | 3         | 1.08%   |
| Alderlake Hybrid | 3         | 1.08%   |
| Puma             | 2         | 0.72%   |
| K8 Hammer        | 2         | 0.72%   |
| Jaguar           | 2         | 0.72%   |
| Goldmont plus    | 2         | 0.72%   |
| Bonnell          | 2         | 0.72%   |
| Piledriver       | 1         | 0.36%   |
| NetBurst         | 1         | 0.36%   |
| Nehalem          | 1         | 0.36%   |
| K6               | 1         | 0.36%   |
| K10 Llano        | 1         | 0.36%   |
| K10              | 1         | 0.36%   |
| Excavator        | 1         | 0.36%   |
| CometLake        | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 214       | 65.64%  |
| Nvidia                           | 70        | 21.47%  |
| AMD                              | 41        | 12.58%  |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 7.55%   |
| Intel HD Graphics 5500                                                                   | 16        | 4.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 4.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 4.83%   |
| Intel UHD Graphics 620                                                                   | 14        | 4.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 3.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.02%   |
| Intel HD Graphics 620                                                                    | 9         | 2.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.11%   |
| Intel HD Graphics 530                                                                    | 7         | 2.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.51%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.21%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.91%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.91%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 3         | 0.91%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.91%   |
| Intel HD Graphics 630                                                                    | 3         | 0.91%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.91%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.6%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.6%    |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.6%    |
| Nvidia GM204GL [Quadro M4000]                                                            | 2         | 0.6%    |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.6%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.6%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.6%    |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.6%    |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 165       | 58.93%  |
| Intel + Nvidia | 41        | 14.64%  |
| 1 x AMD        | 32        | 11.43%  |
| 1 x Nvidia     | 28        | 10%     |
| Intel + AMD    | 7         | 2.5%    |
| Other          | 3         | 1.07%   |
| 2 x Nvidia     | 1         | 0.36%   |
| 2 x AMD        | 1         | 0.36%   |
| 1 x SiS        | 1         | 0.36%   |
| AMD + Nvidia   | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 237       | 83.45%  |
| Proprietary | 34        | 11.97%  |
| Unknown     | 13        | 4.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 194       | 68.07%  |
| 1.01-2.0   | 34        | 11.93%  |
| 0.01-0.5   | 29        | 10.18%  |
| 3.01-4.0   | 13        | 4.56%   |
| 0.51-1.0   | 11        | 3.86%   |
| 7.01-8.0   | 3         | 1.05%   |
| 2.01-3.0   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 41        | 15.19%  |
| LG Display              | 40        | 14.81%  |
| AU Optronics            | 39        | 14.44%  |
| Chimei Innolux          | 34        | 12.59%  |
| BOE                     | 27        | 10%     |
| Dell                    | 16        | 5.93%   |
| Hewlett-Packard         | 15        | 5.56%   |
| InfoVision              | 8         | 2.96%   |
| Lenovo                  | 5         | 1.85%   |
| Goldstar                | 5         | 1.85%   |
| Chi Mei Optoelectronics | 4         | 1.48%   |
| Apple                   | 4         | 1.48%   |
| Sharp                   | 3         | 1.11%   |
| LG Philips              | 3         | 1.11%   |
| BenQ                    | 3         | 1.11%   |
| Acer                    | 3         | 1.11%   |
| Philips                 | 2         | 0.74%   |
| MSI                     | 2         | 0.74%   |
| Iiyama                  | 2         | 0.74%   |
| Fujitsu Siemens         | 2         | 0.74%   |
| Ancor Communications    | 2         | 0.74%   |
| Valve                   | 1         | 0.37%   |
| TMX                     | 1         | 0.37%   |
| RTK                     | 1         | 0.37%   |
| PANDA                   | 1         | 0.37%   |
| MiTAC                   | 1         | 0.37%   |
| Medion                  | 1         | 0.37%   |
| LGD                     | 1         | 0.37%   |
| IBM                     | 1         | 0.37%   |
| CNC                     | 1         | 0.37%   |
| Unknown                 | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 4         | 1.47%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 3         | 1.1%    |
| Dell E2414H DEL4090 1920x1080 530x300mm 24.0-inch                        | 3         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 1.1%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.1%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.74%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                          | 2         | 0.74%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.74%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.74%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.74%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch               | 2         | 0.74%   |
| InfoVision LCD Monitor IVO0535 1920x1080 294x165mm 13.3-inch             | 2         | 0.74%   |
| Hewlett-Packard 25x HPN357E 1920x1080 544x303mm 24.5-inch                | 2         | 0.74%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 2         | 0.74%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.74%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.74%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.37%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.37%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.37%   |
| Sharp LCD Monitor SHP14A8 3840x2400 288x180mm 13.4-inch                  | 1         | 0.37%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch     | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch     | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch     | 1         | 0.37%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch       | 1         | 0.37%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 1         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.37%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 531x299mm 24.0-inch        | 1         | 0.37%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch        | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 98        | 37.26%  |
| 1920x1080 (FHD)    | 91        | 34.6%   |
| 1600x900 (HD+)     | 17        | 6.46%   |
| 3840x2160 (4K)     | 8         | 3.04%   |
| 1440x900 (WXGA+)   | 8         | 3.04%   |
| 1280x1024 (SXGA)   | 8         | 3.04%   |
| 1680x1050 (WSXGA+) | 7         | 2.66%   |
| 1280x800 (WXGA)    | 7         | 2.66%   |
| 1024x600           | 3         | 1.14%   |
| 3840x2400          | 2         | 0.76%   |
| 2560x1440 (QHD)    | 2         | 0.76%   |
| 1920x1200 (WUXGA)  | 2         | 0.76%   |
| 800x1280           | 1         | 0.38%   |
| 2880x1800          | 1         | 0.38%   |
| 2560x1600          | 1         | 0.38%   |
| 2520x1680          | 1         | 0.38%   |
| 1680x945           | 1         | 0.38%   |
| 1400x1050          | 1         | 0.38%   |
| 1360x768           | 1         | 0.38%   |
| 1280x720 (HD)      | 1         | 0.38%   |
| 1152x864           | 1         | 0.38%   |
| 1024x768 (XGA)     | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 41.54%  |
| 14      | 28        | 10.29%  |
| 13      | 25        | 9.19%   |
| 24      | 18        | 6.62%   |
| 12      | 13        | 4.78%   |
| 17      | 12        | 4.41%   |
| 23      | 9         | 3.31%   |
| 19      | 9         | 3.31%   |
| 27      | 7         | 2.57%   |
| 22      | 5         | 1.84%   |
| 21      | 5         | 1.84%   |
| 18      | 5         | 1.84%   |
| Unknown | 4         | 1.47%   |
| 20      | 3         | 1.1%    |
| 11      | 3         | 1.1%    |
| 84      | 2         | 0.74%   |
| 10      | 2         | 0.74%   |
| 72      | 1         | 0.37%   |
| 58      | 1         | 0.37%   |
| 54      | 1         | 0.37%   |
| 52      | 1         | 0.37%   |
| 43      | 1         | 0.37%   |
| 32      | 1         | 0.37%   |
| 31      | 1         | 0.37%   |
| 16      | 1         | 0.37%   |
| 7       | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 155       | 57.2%   |
| 501-600     | 31        | 11.44%  |
| 201-300     | 31        | 11.44%  |
| 401-500     | 23        | 8.49%   |
| 351-400     | 15        | 5.54%   |
| Unknown     | 4         | 1.48%   |
| 601-700     | 3         | 1.11%   |
| 1501-2000   | 3         | 1.11%   |
| 1001-1500   | 3         | 1.11%   |
| 701-800     | 1         | 0.37%   |
| 901-1000    | 1         | 0.37%   |
| 1-100       | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 214       | 81.99%  |
| 16/10   | 29        | 11.11%  |
| 5/4     | 8         | 3.07%   |
| Unknown | 4         | 1.53%   |
| 4/3     | 3         | 1.15%   |
| 3/2     | 2         | 0.77%   |
| 0.67    | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 113       | 41.7%   |
| 81-90          | 41        | 15.13%  |
| 201-250        | 29        | 10.7%   |
| 151-200        | 14        | 5.17%   |
| 61-70          | 13        | 4.8%    |
| 71-80          | 10        | 3.69%   |
| 141-150        | 9         | 3.32%   |
| 301-350        | 7         | 2.58%   |
| More than 1000 | 6         | 2.21%   |
| 251-300        | 6         | 2.21%   |
| 121-130        | 5         | 1.85%   |
| Unknown        | 4         | 1.48%   |
| 51-60          | 3         | 1.11%   |
| 351-500        | 2         | 0.74%   |
| 41-50          | 2         | 0.74%   |
| 131-140        | 2         | 0.74%   |
| 111-120        | 2         | 0.74%   |
| 1-40           | 1         | 0.37%   |
| 501-1000       | 1         | 0.37%   |
| 91-100         | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 97        | 36.06%  |
| 51-100        | 70        | 26.02%  |
| 121-160       | 69        | 25.65%  |
| 161-240       | 20        | 7.43%   |
| 1-50          | 6         | 2.23%   |
| Unknown       | 4         | 1.49%   |
| More than 240 | 3         | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 255       | 90.11%  |
| 2     | 18        | 6.36%   |
| 0     | 10        | 3.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 157       | 36.51%  |
| Realtek Semiconductor            | 117       | 27.21%  |
| Qualcomm Atheros                 | 51        | 11.86%  |
| Broadcom                         | 36        | 8.37%   |
| Ralink Technology                | 20        | 4.65%   |
| Ralink                           | 10        | 2.33%   |
| TP-Link                          | 6         | 1.4%    |
| Broadcom Limited                 | 4         | 0.93%   |
| Xiaomi                           | 3         | 0.7%    |
| Nvidia                           | 3         | 0.7%    |
| Dell                             | 3         | 0.7%    |
| Sierra Wireless                  | 2         | 0.47%   |
| Marvell Technology Group         | 2         | 0.47%   |
| Lenovo                           | 2         | 0.47%   |
| D-Link System                    | 2         | 0.47%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Samsung Electronics              | 1         | 0.23%   |
| Qualcomm Atheros Communications  | 1         | 0.23%   |
| Qualcomm                         | 1         | 0.23%   |
| Microchip Technology             | 1         | 0.23%   |
| MediaTek                         | 1         | 0.23%   |
| JMicron Technology               | 1         | 0.23%   |
| Huawei Technologies              | 1         | 0.23%   |
| Gemtek                           | 1         | 0.23%   |
| Fibocom                          | 1         | 0.23%   |
| Arduino SA                       | 1         | 0.23%   |
| Aquantia                         | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 13.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 4.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 3.94%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 3.19%   |
| Intel Wireless 8265 / 8275                                        | 13        | 2.44%   |
| Intel Wireless 7265                                               | 12        | 2.25%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 2.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.88%   |
| Ralink RT5370 Wireless Adapter                                    | 9         | 1.69%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.69%   |
| Intel Wireless 8260                                               | 9         | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.31%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.31%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 6         | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.94%   |
| Intel Wireless 7260                                               | 5         | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.94%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.75%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.75%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 108       | 41.38%  |
| Qualcomm Atheros                | 45        | 17.24%  |
| Realtek Semiconductor           | 36        | 13.79%  |
| Broadcom                        | 24        | 9.2%    |
| Ralink Technology               | 20        | 7.66%   |
| Ralink                          | 10        | 3.83%   |
| TP-Link                         | 6         | 2.3%    |
| Broadcom Limited                | 3         | 1.15%   |
| Sierra Wireless                 | 2         | 0.77%   |
| Dell                            | 2         | 0.77%   |
| Qualcomm Atheros Communications | 1         | 0.38%   |
| MediaTek                        | 1         | 0.38%   |
| Gemtek                          | 1         | 0.38%   |
| Fibocom                         | 1         | 0.38%   |
| D-Link System                   | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 13        | 4.94%   |
| Intel Wireless 7265                                            | 12        | 4.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 3.8%    |
| Ralink RT5370 Wireless Adapter                                 | 9         | 3.42%   |
| Ralink MT7601U Wireless Adapter                                | 9         | 3.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 3.42%   |
| Intel Wireless 8260                                            | 9         | 3.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 3.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.66%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 2.66%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 2.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.28%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 2.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 2.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 5         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.9%    |
| Intel Wireless 7260                                            | 5         | 1.9%    |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.9%    |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 1.9%    |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 1.14%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.14%   |
| Intel Wireless 3165                                            | 3         | 1.14%   |
| Intel WiFi Link 5100                                           | 3         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.14%   |
| Sierra Wireless EM7455                                         | 2         | 0.76%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.76%   |
| Realtek 802.11ac NIC                                           | 2         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 114       | 43.68%  |
| Realtek Semiconductor            | 100       | 38.31%  |
| Broadcom                         | 16        | 6.13%   |
| Qualcomm Atheros                 | 12        | 4.6%    |
| Xiaomi                           | 3         | 1.15%   |
| Nvidia                           | 3         | 1.15%   |
| Marvell Technology Group         | 2         | 0.77%   |
| Lenovo                           | 2         | 0.77%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |
| Samsung Electronics              | 1         | 0.38%   |
| Qualcomm                         | 1         | 0.38%   |
| Microchip Technology             | 1         | 0.38%   |
| JMicron Technology               | 1         | 0.38%   |
| Huawei Technologies              | 1         | 0.38%   |
| D-Link System                    | 1         | 0.38%   |
| Broadcom Limited                 | 1         | 0.38%   |
| Aquantia                         | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 71        | 26.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 26        | 9.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 7.87%   |
| Intel Ethernet Connection I217-LM                                              | 17        | 6.37%   |
| Intel 82577LM Gigabit Network Connection                                       | 11        | 4.12%   |
| Intel Ethernet Connection (3) I218-LM                                          | 9         | 3.37%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8         | 3%      |
| Intel Ethernet Connection I218-LM                                              | 5         | 1.87%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 1.5%    |
| Intel I211 Gigabit Network Connection                                          | 4         | 1.5%    |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.12%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 1.12%   |
| Intel Ethernet Connection I217-V                                               | 3         | 1.12%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.12%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.12%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 1.12%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 1.12%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 3         | 1.12%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.75%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 0.75%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 2         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.75%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.37%   |
| Qualcomm Redmi Note 8                                                          | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.37%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.37%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 1         | 0.37%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.37%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 248       | 49.7%   |
| Ethernet | 248       | 49.7%   |
| Modem    | 3         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 203       | 72.5%   |
| Ethernet | 77        | 27.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 190       | 67.86%  |
| 1     | 76        | 27.14%  |
| 0     | 7         | 2.5%    |
| 3     | 6         | 2.14%   |
| 7     | 1         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 279       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 42.94%  |
| Realtek Semiconductor           | 21        | 12.35%  |
| Qualcomm Atheros Communications | 20        | 11.76%  |
| Broadcom                        | 11        | 6.47%   |
| IMC Networks                    | 8         | 4.71%   |
| Dell                            | 7         | 4.12%   |
| Ralink                          | 5         | 2.94%   |
| Lite-On Technology              | 5         | 2.94%   |
| Hewlett-Packard                 | 5         | 2.94%   |
| Cambridge Silicon Radio         | 5         | 2.94%   |
| Apple                           | 3         | 1.76%   |
| Toshiba                         | 2         | 1.18%   |
| ASUSTek Computer                | 2         | 1.18%   |
| Foxconn International           | 1         | 0.59%   |
| Foxconn / Hon Hai               | 1         | 0.59%   |
| Alps Electric                   | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 22.94%  |
| Realtek Bluetooth Radio                             | 16        | 9.41%   |
| Intel AX201 Bluetooth                               | 11        | 6.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 5.29%   |
| Intel AX200 Bluetooth                               | 7         | 4.12%   |
| IMC Networks Bluetooth Device                       | 6         | 3.53%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.94%   |
| Ralink RT3290 Bluetooth                             | 5         | 2.94%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 2.94%   |
| Intel Bluetooth Device                              | 4         | 2.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 2.35%   |
| Dell DW375 Bluetooth Module                         | 4         | 2.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.18%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.18%   |
| Dell Wireless 360 Bluetooth                         | 2         | 1.18%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 1.18%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.18%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.18%   |
| Toshiba Bluetooth Device                            | 1         | 0.59%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.59%   |
| IMC Networks Wireless_Device                        | 1         | 0.59%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.59%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.59%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.59%   |
| Dell Wireless 350 Bluetooth                         | 1         | 0.59%   |
| Broadcom HP Portable Valentine                      | 1         | 0.59%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.59%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.59%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.59%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter    | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 241       | 71.51%  |
| Nvidia                           | 44        | 13.06%  |
| AMD                              | 35        | 10.39%  |
| Silicon Integrated Systems [SiS] | 2         | 0.59%   |
| Lenovo                           | 2         | 0.59%   |
| GN Netcom                        | 2         | 0.59%   |
| Nordic Semiconductor ASA         | 1         | 0.3%    |
| Medeli Electronics               | 1         | 0.3%    |
| Logitech                         | 1         | 0.3%    |
| Kingston Technology              | 1         | 0.3%    |
| Hewlett-Packard                  | 1         | 0.3%    |
| Generalplus Technology           | 1         | 0.3%    |
| GEMBIRD                          | 1         | 0.3%    |
| Focusrite-Novation               | 1         | 0.3%    |
| EDFIER                           | 1         | 0.3%    |
| C-Media Electronics              | 1         | 0.3%    |
| ASUSTek Computer                 | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 33        | 8.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 5.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 5.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 22        | 5.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 20        | 4.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18        | 4.38%   |
| Intel Broadwell-U Audio Controller                                         | 17        | 4.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 16        | 3.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 3.89%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 3.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 3.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 2.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 2.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.46%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6         | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 1.46%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 1.22%   |
| Nvidia High Definition Audio Controller                                    | 4         | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.97%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 0.73%   |
| Nvidia Audio device                                                        | 3         | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.73%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3         | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3         | 0.73%   |
| AMD Wrestler HDMI Audio                                                    | 3         | 0.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 0.49%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.49%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 29.56%  |
| SK hynix            | 53        | 26.11%  |
| Micron Technology   | 27        | 13.3%   |
| Kingston            | 20        | 9.85%   |
| Unknown             | 6         | 2.96%   |
| Ramaxel Technology  | 4         | 1.97%   |
| Nanya Technology    | 4         | 1.97%   |
| Elpida              | 4         | 1.97%   |
| Crucial             | 4         | 1.97%   |
| Corsair             | 4         | 1.97%   |
| A-DATA Technology   | 4         | 1.97%   |
| Sesame              | 2         | 0.99%   |
| Unknown             | 2         | 0.99%   |
| Wilk                | 1         | 0.49%   |
| Transcend           | 1         | 0.49%   |
| Toshiba             | 1         | 0.49%   |
| TakeMS              | 1         | 0.49%   |
| Qimonda             | 1         | 0.49%   |
| G.Skill             | 1         | 0.49%   |
| Avant               | 1         | 0.49%   |
| ASint Technology    | 1         | 0.49%   |
| Apacer              | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s        | 4         | 1.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 1.8%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 1.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 1.35%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s         | 3         | 1.35%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 3         | 1.35%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 3         | 1.35%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s        | 2         | 0.9%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 0.9%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                 | 2         | 0.9%    |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                   | 2         | 0.9%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.9%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 2         | 0.9%    |
| Kingston RAM HP687515-H66-MCN 4GB SODIMM DDR3 1600MT/s      | 2         | 0.9%    |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 2         | 0.9%    |
| Unknown                                                     | 2         | 0.9%    |
| Wilk RAM Module 16GB DIMM DDR4 2667MT/s                     | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s              | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM                                 | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 0.45%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s         | 1         | 0.45%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s        | 1         | 0.45%   |
| TakeMS RAM TMS2GB264C081-665U 2048MB DIMM DDR2 667MT/s      | 1         | 0.45%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1         | 0.45%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s             | 1         | 0.45%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                  | 1         | 0.45%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                      | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 73        | 47.71%  |
| DDR4    | 52        | 33.99%  |
| DDR2    | 8         | 5.23%   |
| SDRAM   | 7         | 4.58%   |
| LPDDR4  | 5         | 3.27%   |
| LPDDR3  | 3         | 1.96%   |
| Unknown | 3         | 1.96%   |
| DDR5    | 1         | 0.65%   |
| DDR     | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 68.97%  |
| DIMM         | 37        | 25.52%  |
| Row Of Chips | 5         | 3.45%   |
| Unknown      | 2         | 1.38%   |
| RIMM         | 1         | 0.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 64        | 37.21%  |
| 8192  | 57        | 33.14%  |
| 2048  | 22        | 12.79%  |
| 16384 | 14        | 8.14%   |
| 1024  | 9         | 5.23%   |
| 32768 | 2         | 1.16%   |
| 512   | 2         | 1.16%   |
| 256   | 1         | 0.58%   |
| 128   | 1         | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 52        | 29.55%  |
| 2667    | 21        | 11.93%  |
| 3200    | 15        | 8.52%   |
| 1334    | 14        | 7.95%   |
| 2400    | 12        | 6.82%   |
| 1333    | 12        | 6.82%   |
| 2133    | 8         | 4.55%   |
| 1648    | 4         | 2.27%   |
| 1066    | 4         | 2.27%   |
| 800     | 4         | 2.27%   |
| 667     | 4         | 2.27%   |
| 3600    | 3         | 1.7%    |
| Unknown | 3         | 1.7%    |
| 3266    | 2         | 1.14%   |
| 1867    | 2         | 1.14%   |
| 1067    | 2         | 1.14%   |
| 975     | 2         | 1.14%   |
| 4800    | 1         | 0.57%   |
| 4267    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 3733    | 1         | 0.57%   |
| 3400    | 1         | 0.57%   |
| 2666    | 1         | 0.57%   |
| 1866    | 1         | 0.57%   |
| 1639    | 1         | 0.57%   |
| 1331    | 1         | 0.57%   |
| 400     | 1         | 0.57%   |
| 333     | 1         | 0.57%   |
| 266     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP Deskjet 3510 series | 1         | 50%     |
| Canon MB2000 series    | 1         | 50%     |

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
| Chicony Electronics                    | 48        | 26.67%  |
| IMC Networks                           | 19        | 10.56%  |
| Realtek Semiconductor                  | 17        | 9.44%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 9.44%   |
| Sunplus Innovation Technology          | 11        | 6.11%   |
| Suyin                                  | 10        | 5.56%   |
| Lite-On Technology                     | 9         | 5%      |
| Microdia                               | 8         | 4.44%   |
| Quanta                                 | 7         | 3.89%   |
| Bison Electronics                      | 5         | 2.78%   |
| Ricoh                                  | 4         | 2.22%   |
| Apple                                  | 4         | 2.22%   |
| Syntek                                 | 3         | 1.67%   |
| Logitech                               | 3         | 1.67%   |
| Luxvisions Innotech Limited            | 2         | 1.11%   |
| ALi                                    | 2         | 1.11%   |
| Alcor Micro                            | 2         | 1.11%   |
| Z-Star Microelectronics                | 1         | 0.56%   |
| Sunplus Technology                     | 1         | 0.56%   |
| Sonix Technology                       | 1         | 0.56%   |
| Silicon Motion                         | 1         | 0.56%   |
| ShineTech                              | 1         | 0.56%   |
| OPPO Electronics                       | 1         | 0.56%   |
| Jieli Technology                       | 1         | 0.56%   |
| icSpring                               | 1         | 0.56%   |
| Acer                                   | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 3.87%   |
| IMC Networks Integrated Camera                              | 6         | 3.31%   |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 3.31%   |
| Chicony HP Webcam                                           | 5         | 2.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 5         | 2.76%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.21%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 2.21%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 1.66%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 1.66%   |
| Realtek USB Camera                                          | 3         | 1.66%   |
| Microdia Integrated Webcam                                  | 3         | 1.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.66%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.66%   |
| Chicony HP HD Webcam                                        | 3         | 1.66%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.1%    |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 1.1%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.1%    |
| Sunplus HP Universal Camera                                 | 2         | 1.1%    |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.1%    |
| Quanta HP Wide Vision HD Camera                             | 2         | 1.1%    |
| Quanta HD Webcam                                            | 2         | 1.1%    |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.1%    |
| Lite-On HP HD Webcam                                        | 2         | 1.1%    |
| Lite-On HP HD Camera                                        | 2         | 1.1%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.1%    |
| IMC Networks Integrated Webcam                              | 2         | 1.1%    |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.1%    |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.1%    |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.1%    |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.1%    |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.1%    |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.1%    |
| Chicony HP Truevision HD                                    | 2         | 1.1%    |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.1%    |
| Bison Integrated Camera                                     | 2         | 1.1%    |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 1.1%    |
| Z-Star Vimicro USB2.0 Camera                                | 1         | 0.55%   |
| Syntek EasyCamera                                           | 1         | 0.55%   |
| Suyin WebCam                                                | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 29        | 67.44%  |
| Synaptics                  | 6         | 13.95%  |
| Elan Microelectronics      | 4         | 9.3%    |
| Shenzhen Goodix Technology | 2         | 4.65%   |
| Upek                       | 1         | 2.33%   |
| Focal-systems.Corp         | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 23.26%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 11.63%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 9.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 6.98%   |
| Validity Sensors VFS491                                                    | 2         | 4.65%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.65%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.65%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 2.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.33%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.33%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 66.67%  |
| Alcor Micro | 6         | 20%     |
| O2 Micro    | 4         | 13.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 13.33%  |
| Broadcom 5880                                                                | 4         | 13.33%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.67%   |
| Broadcom 58200                                                               | 2         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 178       | 62.24%  |
| 1     | 87        | 30.42%  |
| 2     | 17        | 5.94%   |
| 3     | 3         | 1.05%   |
| 5     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 32.33%  |
| Chipcard                 | 26        | 19.55%  |
| Graphics card            | 24        | 18.05%  |
| Net/wireless             | 12        | 9.02%   |
| Bluetooth                | 6         | 4.51%   |
| Storage                  | 5         | 3.76%   |
| Camera                   | 4         | 3.01%   |
| Unassigned class         | 3         | 2.26%   |
| Communication controller | 3         | 2.26%   |
| Sound                    | 2         | 1.5%    |
| Net/ethernet             | 2         | 1.5%    |
| Multimedia controller    | 2         | 1.5%    |
| Modem                    | 1         | 0.75%   |

