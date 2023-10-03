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

Total: 411

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir7,2               | Notebook    | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [82b9c0d614](https://linux-hardware.org/?probe=82b9c0d614) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| Dell          | 077RRV A00                  | Desktop     | [5ebc4171ff](https://linux-hardware.org/?probe=5ebc4171ff) | Sep 08, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 43        | 13.87%  |
| Ubuntu 22.04       | 25        | 8.06%   |
| Ubuntu 18.04       | 17        | 5.48%   |
| Debian 11          | 14        | 4.52%   |
| OpenMandriva 4.2   | 12        | 3.87%   |
| KDE neon 20.04     | 11        | 3.55%   |
| OpenMandriva 4.3   | 10        | 3.23%   |
| Pop!_OS 22.04      | 7         | 2.26%   |
| Linux Mint 20.2    | 7         | 2.26%   |
| OpenMandriva 23.01 | 6         | 1.94%   |
| Zorin 16           | 5         | 1.61%   |
| Ubuntu Unity 16.04 | 5         | 1.61%   |
| Ubuntu 20.10       | 5         | 1.61%   |
| OpenMandriva 4.50  | 5         | 1.61%   |
| Linux Mint 20.3    | 5         | 1.61%   |
| Fedora 38          | 5         | 1.61%   |
| Fedora 33          | 5         | 1.61%   |
| ArcoLinux Rolling  | 5         | 1.61%   |
| Ubuntu 19.10       | 4         | 1.29%   |
| Linux Mint 21      | 4         | 1.29%   |
| Arch Rolling       | 4         | 1.29%   |
| Arch               | 4         | 1.29%   |
| Manjaro            | 3         | 0.97%   |
| Linux Mint 21.1    | 3         | 0.97%   |
| Linux Mint 19.3    | 3         | 0.97%   |
| Debian 12          | 3         | 0.97%   |
| Zorin 15           | 2         | 0.65%   |
| Xubuntu 20.04      | 2         | 0.65%   |
| Xero Rolling       | 2         | 0.65%   |
| Void Linux         | 2         | 0.65%   |
| Ubuntu 23.04       | 2         | 0.65%   |
| Ubuntu 21.10       | 2         | 0.65%   |
| Ubuntu 21.04       | 2         | 0.65%   |
| Ubuntu 16.04       | 2         | 0.65%   |
| Pop!_OS 21.10      | 2         | 0.65%   |
| Pop!_OS 21.04      | 2         | 0.65%   |
| Pop!_OS 20.10      | 2         | 0.65%   |
| Parrot 5.0         | 2         | 0.65%   |
| OpenMandriva 23.90 | 2         | 0.65%   |
| KDE neon 22.04     | 2         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 98        | 33.56%  |
| OpenMandriva | 33        | 11.3%   |
| Linux Mint   | 22        | 7.53%   |
| Debian       | 17        | 5.82%   |
| Fedora       | 16        | 5.48%   |
| Pop!_OS      | 13        | 4.45%   |
| KDE neon     | 13        | 4.45%   |
| Kali         | 9         | 3.08%   |
| Arch         | 8         | 2.74%   |
| Zorin        | 7         | 2.4%    |
| Manjaro      | 7         | 2.4%    |
| Ubuntu Unity | 6         | 2.05%   |
| ArcoLinux    | 5         | 1.71%   |
| Xubuntu      | 3         | 1.03%   |
| Ubuntu MATE  | 3         | 1.03%   |
| Endless      | 3         | 1.03%   |
| Elementary   | 3         | 1.03%   |
| Xero         | 2         | 0.68%   |
| Void Linux   | 2         | 0.68%   |
| SteamOS      | 2         | 0.68%   |
| Raspbian     | 2         | 0.68%   |
| Parrot       | 2         | 0.68%   |
| openSUSE     | 2         | 0.68%   |
| EndeavourOS  | 2         | 0.68%   |
| BlackPanther | 2         | 0.68%   |
| ROSA         | 1         | 0.34%   |
| RHEL         | 1         | 0.34%   |
| Pear OS      | 1         | 0.34%   |
| Nobara       | 1         | 0.34%   |
| Lubuntu      | 1         | 0.34%   |
| Kubuntu      | 1         | 0.34%   |
| CentOS       | 1         | 0.34%   |
| BunsenLabs   | 1         | 0.34%   |
| blendOS      | 1         | 0.34%   |
| Android      | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 12        | 3.66%   |
| 5.16.7-desktop-1omv4003  | 11        | 3.35%   |
| 6.1.1-desktop-1omv2290   | 6         | 1.83%   |
| 5.4.0-58-generic         | 5         | 1.52%   |
| 5.4.0-48-generic         | 5         | 1.52%   |
| 5.13.0-40-generic        | 5         | 1.52%   |
| 6.2.0-33-generic         | 4         | 1.22%   |
| 5.8.0-43-generic         | 4         | 1.22%   |
| 5.4.0-42-generic         | 4         | 1.22%   |
| 5.12.4-desktop-1omv4050  | 4         | 1.22%   |
| 5.11.0-37-generic        | 4         | 1.22%   |
| 5.8.0-38-generic         | 3         | 0.91%   |
| 5.3.0-40-generic         | 3         | 0.91%   |
| 5.19.0-41-generic        | 3         | 0.91%   |
| 5.19.0-38-generic        | 3         | 0.91%   |
| 5.17.5-76051705-generic  | 3         | 0.91%   |
| 5.15.0-58-generic        | 3         | 0.91%   |
| 5.15.0-52-generic        | 3         | 0.91%   |
| 5.15.0-46-generic        | 3         | 0.91%   |
| 5.15.0-41-generic        | 3         | 0.91%   |
| 5.13.0-27-generic        | 3         | 0.91%   |
| 5.10.0-21-amd64          | 3         | 0.91%   |
| 6.2.6-76060206-generic   | 2         | 0.61%   |
| 6.2.14-300.fc38.x86_64   | 2         | 0.61%   |
| 6.1.0-9-amd64            | 2         | 0.61%   |
| 5.8.0-48-generic         | 2         | 0.61%   |
| 5.8.0-33-generic         | 2         | 0.61%   |
| 5.4.0-96-generic         | 2         | 0.61%   |
| 5.4.0-90-generic         | 2         | 0.61%   |
| 5.4.0-88-generic         | 2         | 0.61%   |
| 5.4.0-74-generic         | 2         | 0.61%   |
| 5.4.0-65-generic         | 2         | 0.61%   |
| 5.4.0-59-generic         | 2         | 0.61%   |
| 5.4.0-37-generic         | 2         | 0.61%   |
| 5.4.0-33-generic         | 2         | 0.61%   |
| 5.4.0-29-generic         | 2         | 0.61%   |
| 5.3.0-kali2-686-pae      | 2         | 0.61%   |
| 5.3.0-51-generic         | 2         | 0.61%   |
| 5.3.0-28-generic         | 2         | 0.61%   |
| 5.18.19_1                | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 13.18%  |
| 5.15.0  | 31        | 9.97%   |
| 5.8.0   | 18        | 5.79%   |
| 5.11.0  | 17        | 5.47%   |
| 4.15.0  | 17        | 5.47%   |
| 5.10.0  | 15        | 4.82%   |
| 5.13.0  | 14        | 4.5%    |
| 5.3.0   | 12        | 3.86%   |
| 5.10.14 | 12        | 3.86%   |
| 5.16.7  | 11        | 3.54%   |
| 5.19.0  | 10        | 3.22%   |
| 6.2.0   | 6         | 1.93%   |
| 6.1.1   | 6         | 1.93%   |
| 5.0.0   | 6         | 1.93%   |
| 6.1.0   | 5         | 1.61%   |
| 5.12.4  | 4         | 1.29%   |
| 4.18.0  | 4         | 1.29%   |
| 6.2.6   | 3         | 0.96%   |
| 5.17.5  | 3         | 0.96%   |
| 5.14.0  | 3         | 0.96%   |
| 4.19.0  | 3         | 0.96%   |
| 6.4.6   | 2         | 0.64%   |
| 6.2.9   | 2         | 0.64%   |
| 6.2.14  | 2         | 0.64%   |
| 6.0.0   | 2         | 0.64%   |
| 5.18.19 | 2         | 0.64%   |
| 5.16.0  | 2         | 0.64%   |
| 5.14.14 | 2         | 0.64%   |
| 6.5.3   | 1         | 0.32%   |
| 6.4.9   | 1         | 0.32%   |
| 6.4.11  | 1         | 0.32%   |
| 6.4.10  | 1         | 0.32%   |
| 6.3.7   | 1         | 0.32%   |
| 6.3.6   | 1         | 0.32%   |
| 6.3.4   | 1         | 0.32%   |
| 6.3.2   | 1         | 0.32%   |
| 6.3.12  | 1         | 0.32%   |
| 6.2.10  | 1         | 0.32%   |
| 6.1.7   | 1         | 0.32%   |
| 6.1.6   | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 13.23%  |
| 5.15    | 38        | 12.26%  |
| 5.10    | 33        | 10.65%  |
| 5.8     | 21        | 6.77%   |
| 5.11    | 20        | 6.45%   |
| 4.15    | 17        | 5.48%   |
| 5.13    | 16        | 5.16%   |
| 6.2     | 14        | 4.52%   |
| 5.19    | 14        | 4.52%   |
| 5.16    | 14        | 4.52%   |
| 6.1     | 13        | 4.19%   |
| 5.3     | 12        | 3.87%   |
| 5.17    | 6         | 1.94%   |
| 5.14    | 6         | 1.94%   |
| 5.0     | 6         | 1.94%   |
| 6.4     | 5         | 1.61%   |
| 6.3     | 5         | 1.61%   |
| 5.18    | 5         | 1.61%   |
| 4.18    | 5         | 1.61%   |
| 6.0     | 4         | 1.29%   |
| 5.12    | 4         | 1.29%   |
| 4.19    | 3         | 0.97%   |
| 6.5     | 1         | 0.32%   |
| 5.7     | 1         | 0.32%   |
| 5.6     | 1         | 0.32%   |
| 4.9     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.14    | 1         | 0.32%   |
| 4.13    | 1         | 0.32%   |
| 3.18    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 273       | 95.45%  |
| i686   | 10        | 3.5%    |
| armv8l | 1         | 0.35%   |
| armv7l | 1         | 0.35%   |
| armv6l | 1         | 0.35%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 146       | 49.49%  |
| KDE5            | 61        | 20.68%  |
| Unknown         | 19        | 6.44%   |
| X-Cinnamon      | 16        | 5.42%   |
| XFCE            | 15        | 5.08%   |
| KDE             | 9         | 3.05%   |
| Unity           | 6         | 2.03%   |
| MATE            | 6         | 2.03%   |
| Pantheon        | 3         | 1.02%   |
| LXDE            | 3         | 1.02%   |
| Cinnamon        | 3         | 1.02%   |
| GNOME Flashback | 2         | 0.68%   |
| xmonad          | 1         | 0.34%   |
| sway            | 1         | 0.34%   |
| qtile           | 1         | 0.34%   |
| KDE4            | 1         | 0.34%   |
| i3              | 1         | 0.34%   |
| Budgie          | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 225       | 76.53%  |
| Wayland | 55        | 18.71%  |
| Unknown | 10        | 3.4%    |
| Tty     | 4         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 130       | 43.48%  |
| SDDM    | 55        | 18.39%  |
| GDM3    | 40        | 13.38%  |
| GDM     | 39        | 13.04%  |
| LightDM | 30        | 10.03%  |
| TDM     | 4         | 1.34%   |
| KDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 159       | 55.02%  |
| fr_FR   | 82        | 28.37%  |
| Unknown | 20        | 6.92%   |
| en_GB   | 13        | 4.5%    |
| de_DE   | 3         | 1.04%   |
| C       | 3         | 1.04%   |
| en_AG   | 2         | 0.69%   |
| ar_MA   | 2         | 0.69%   |
| fr_MA   | 1         | 0.35%   |
| fr_CH   | 1         | 0.35%   |
| fr_BE   | 1         | 0.35%   |
| es_ES   | 1         | 0.35%   |
| ar_EG   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 170       | 59.03%  |
| EFI  | 118       | 40.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 218       | 75.69%  |
| Overlay | 35        | 12.15%  |
| Btrfs   | 22        | 7.64%   |
| Tmpfs   | 5         | 1.74%   |
| Unknown | 5         | 1.74%   |
| Xfs     | 3         | 1.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 136       | 46.9%   |
| GPT     | 105       | 36.21%  |
| MBR     | 49        | 16.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 243       | 84.67%  |
| Yes       | 44        | 15.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 177       | 61.46%  |
| Yes       | 111       | 38.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 101       | 35.44%  |
| Dell                    | 48        | 16.84%  |
| Lenovo                  | 43        | 15.09%  |
| ASUSTek Computer        | 26        | 9.12%   |
| Acer                    | 9         | 3.16%   |
| Toshiba                 | 8         | 2.81%   |
| Apple                   | 5         | 1.75%   |
| Sony                    | 3         | 1.05%   |
| Packard Bell            | 3         | 1.05%   |
| Foxconn                 | 3         | 1.05%   |
| Unknown                 | 3         | 1.05%   |
| Timi                    | 2         | 0.7%    |
| Samsung Electronics     | 2         | 0.7%    |
| Raspberry Pi Foundation | 2         | 0.7%    |
| Medion                  | 2         | 0.7%    |
| HUAWEI                  | 2         | 0.7%    |
| Gigabyte Technology     | 2         | 0.7%    |
| eMachines               | 2         | 0.7%    |
| American Megatrends     | 2         | 0.7%    |
| Valve                   | 1         | 0.35%   |
| TUXEDO                  | 1         | 0.35%   |
| TrekStor                | 1         | 0.35%   |
| SINTRONES               | 1         | 0.35%   |
| Razer                   | 1         | 0.35%   |
| Pegatron                | 1         | 0.35%   |
| MSI                     | 1         | 0.35%   |
| Mediacom                | 1         | 0.35%   |
| Linx                    | 1         | 0.35%   |
| GPD                     | 1         | 0.35%   |
| Google                  | 1         | 0.35%   |
| Fujitsu Siemens         | 1         | 0.35%   |
| Fujitsu                 | 1         | 0.35%   |
| ECS                     | 1         | 0.35%   |
| Clevo                   | 1         | 0.35%   |
| Casper                  | 1         | 0.35%   |
| ASRock                  | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP EliteBook 8440p                     | 4         | 1.4%    |
| Unknown                                | 4         | 1.4%    |
| HP ProDesk 600 G1 TWR                  | 3         | 1.05%   |
| HP Pavilion g6                         | 3         | 1.05%   |
| HP Laptop 15-dw3xxx                    | 3         | 1.05%   |
| HP EliteBook 840 G2                    | 3         | 1.05%   |
| ASUS X540LA                            | 3         | 1.05%   |
| Timi TM1701                            | 2         | 0.7%    |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.7%    |
| Lenovo IdeaPad L3 15IML05 81Y3         | 2         | 0.7%    |
| HP ZBook 15                            | 2         | 0.7%    |
| HP Z620 Workstation                    | 2         | 0.7%    |
| HP ProBook 650 G1                      | 2         | 0.7%    |
| HP ProBook 6470b                       | 2         | 0.7%    |
| HP Notebook                            | 2         | 0.7%    |
| HP EliteDesk 800 G1 TWR                | 2         | 0.7%    |
| HP EliteDesk 800 G1 SFF                | 2         | 0.7%    |
| HP EliteBook 8460p                     | 2         | 0.7%    |
| HP Compaq Elite 8300 SFF               | 2         | 0.7%    |
| HP Compaq Elite 8300 CMT               | 2         | 0.7%    |
| HP Compaq dc7800 Convertible Minitower | 2         | 0.7%    |
| HP Compaq 8200 Elite CMT PC            | 2         | 0.7%    |
| HP 250 G5 Notebook PC                  | 2         | 0.7%    |
| Dell OptiPlex 790                      | 2         | 0.7%    |
| Dell Latitude E7450                    | 2         | 0.7%    |
| Dell Latitude E6520                    | 2         | 0.7%    |
| Dell Latitude E6410                    | 2         | 0.7%    |
| Acer Aspire ES1-523                    | 2         | 0.7%    |
| Valve Jupiter                          | 1         | 0.35%   |
| TUXEDO N13xWU                          | 1         | 0.35%   |
| TrekStor Surfbook W2                   | 1         | 0.35%   |
| Toshiba Satellite Pro C650             | 1         | 0.35%   |
| Toshiba Satellite L750                 | 1         | 0.35%   |
| Toshiba Satellite L50-B                | 1         | 0.35%   |
| Toshiba Satellite L50-A-1EL            | 1         | 0.35%   |
| Toshiba Satellite L50-A-1DG            | 1         | 0.35%   |
| Toshiba Satellite C855-2CF             | 1         | 0.35%   |
| Toshiba Satellite C855-1LG             | 1         | 0.35%   |
| Toshiba Satellite C660                 | 1         | 0.35%   |
| Sony VPCEH1L8E                         | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 30        | 10.53%  |
| Lenovo ThinkPad       | 22        | 7.72%   |
| HP EliteBook          | 19        | 6.67%   |
| HP Compaq             | 17        | 5.96%   |
| HP ProBook            | 10        | 3.51%   |
| HP Pavilion           | 10        | 3.51%   |
| HP Laptop             | 9         | 3.16%   |
| Toshiba Satellite     | 8         | 2.81%   |
| Dell OptiPlex         | 7         | 2.46%   |
| Lenovo IdeaPad        | 6         | 2.11%   |
| Acer Aspire           | 6         | 2.11%   |
| HP ProDesk            | 5         | 1.75%   |
| HP EliteDesk          | 5         | 1.75%   |
| HP 250                | 5         | 1.75%   |
| Dell Precision        | 4         | 1.4%    |
| ASUS ROG              | 4         | 1.4%    |
| Unknown               | 4         | 1.4%    |
| Packard Bell EasyNote | 3         | 1.05%   |
| Lenovo ThinkCentre    | 3         | 1.05%   |
| Lenovo ThinkBook      | 3         | 1.05%   |
| HP ZBook              | 3         | 1.05%   |
| Dell Vostro           | 3         | 1.05%   |
| ASUS X540LA           | 3         | 1.05%   |
| Timi TM1701           | 2         | 0.7%    |
| RPi Raspberry         | 2         | 0.7%    |
| Lenovo ThinkStation   | 2         | 0.7%    |
| HP Z620               | 2         | 0.7%    |
| HP Notebook           | 2         | 0.7%    |
| Dell XPS              | 2         | 0.7%    |
| Dell Inspiron         | 2         | 0.7%    |
| ASUS PRIME            | 2         | 0.7%    |
| Valve Jupiter         | 1         | 0.35%   |
| TUXEDO N13xWU         | 1         | 0.35%   |
| TrekStor Surfbook     | 1         | 0.35%   |
| Sony VPCEH1L8E        | 1         | 0.35%   |
| Sony VGN-FW11L        | 1         | 0.35%   |
| Sony SVE14122CAW      | 1         | 0.35%   |
| SINTRONES AMB-5000G1  | 1         | 0.35%   |
| Samsung 355V4C        | 1         | 0.35%   |
| Samsung 300E4A        | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 32        | 11.23%  |
| 2011    | 28        | 9.82%   |
| 2018    | 24        | 8.42%   |
| 2010    | 24        | 8.42%   |
| 2014    | 22        | 7.72%   |
| 2012    | 21        | 7.37%   |
| 2015    | 20        | 7.02%   |
| 2016    | 19        | 6.67%   |
| 2020    | 17        | 5.96%   |
| 2017    | 17        | 5.96%   |
| 2021    | 15        | 5.26%   |
| 2019    | 13        | 4.56%   |
| 2007    | 9         | 3.16%   |
| 2009    | 7         | 2.46%   |
| 2008    | 6         | 2.11%   |
| 2022    | 3         | 1.05%   |
| 2006    | 2         | 0.7%    |
| 2004    | 2         | 0.7%    |
| Unknown | 2         | 0.7%    |
| 2023    | 1         | 0.35%   |
| 2005    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 207       | 72.63%  |
| Desktop        | 68        | 23.86%  |
| Convertible    | 5         | 1.75%   |
| System on chip | 2         | 0.7%    |
| Phone          | 1         | 0.35%   |
| Tablet         | 1         | 0.35%   |
| All in one     | 1         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 272       | 93.79%  |
| Enabled  | 18        | 6.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 283       | 99.3%   |
| Yes  | 2         | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 90        | 31.36%  |
| 3.01-4.0    | 73        | 25.44%  |
| 8.01-16.0   | 39        | 13.59%  |
| 16.01-24.0  | 37        | 12.89%  |
| 1.01-2.0    | 18        | 6.27%   |
| 32.01-64.0  | 9         | 3.14%   |
| 24.01-32.0  | 7         | 2.44%   |
| 2.01-3.0    | 6         | 2.09%   |
| 64.01-256.0 | 5         | 1.74%   |
| 0.51-1.0    | 2         | 0.7%    |
| 0.01-0.5    | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 116       | 37.3%   |
| 2.01-3.0  | 94        | 30.23%  |
| 3.01-4.0  | 40        | 12.86%  |
| 4.01-8.0  | 39        | 12.54%  |
| 0.51-1.0  | 16        | 5.14%   |
| 8.01-16.0 | 4         | 1.29%   |
| 0.01-0.5  | 2         | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 218       | 75.43%  |
| 2      | 54        | 18.69%  |
| 3      | 14        | 4.84%   |
| 4      | 3         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 151       | 52.98%  |
| Yes       | 134       | 47.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 254       | 89.12%  |
| No        | 31        | 10.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 253       | 88.46%  |
| No        | 33        | 11.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 60.76%  |
| No        | 113       | 39.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Morocco | 285       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Casablanca       | 76        | 24.84%  |
| Marrakesh        | 29        | 9.48%   |
| Rabat            | 25        | 8.17%   |
| Fes              | 24        | 7.84%   |
| Agadir           | 23        | 7.52%   |
| Tangier          | 15        | 4.9%    |
| Salé            | 15        | 4.9%    |
| Kenitra          | 12        | 3.92%   |
| Meknes           | 11        | 3.59%   |
| Oujda            | 9         | 2.94%   |
| Khouribga        | 7         | 2.29%   |
| Nador            | 5         | 1.63%   |
| Tiznit           | 4         | 1.31%   |
| El Jadida        | 4         | 1.31%   |
| Temara           | 3         | 0.98%   |
| Taza             | 3         | 0.98%   |
| Beni Mellal      | 3         | 0.98%   |
| Youssoufia       | 2         | 0.65%   |
| Tétouan         | 2         | 0.65%   |
| Skhirate         | 2         | 0.65%   |
| Safi             | 2         | 0.65%   |
| Mohammedia       | 2         | 0.65%   |
| Guelmim          | 2         | 0.65%   |
| Berkane          | 2         | 0.65%   |
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

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 57        | 74     | 16.24%  |
| WDC                         | 49        | 65     | 13.96%  |
| Samsung Electronics         | 45        | 58     | 12.82%  |
| Toshiba                     | 39        | 55     | 11.11%  |
| Hitachi                     | 22        | 27     | 6.27%   |
| Unknown                     | 17        | 23     | 4.84%   |
| HGST                        | 13        | 13     | 3.7%    |
| SanDisk                     | 11        | 11     | 3.13%   |
| Intel                       | 10        | 11     | 2.85%   |
| Kingston                    | 7         | 9      | 1.99%   |
| Apple                       | 7         | 7      | 1.99%   |
| SK hynix                    | 5         | 5      | 1.42%   |
| KIOXIA                      | 5         | 5      | 1.42%   |
| China                       | 5         | 6      | 1.42%   |
| PNY                         | 4         | 5      | 1.14%   |
| Micron Technology           | 4         | 6      | 1.14%   |
| LITEON                      | 4         | 4      | 1.14%   |
| Fujitsu                     | 4         | 4      | 1.14%   |
| Crucial                     | 4         | 5      | 1.14%   |
| Phison                      | 3         | 4      | 0.85%   |
| KingFast                    | 3         | 4      | 0.85%   |
| Unknown                     | 3         | 3      | 0.85%   |
| KingDian                    | 2         | 6      | 0.57%   |
| GOODRAM                     | 2         | 2      | 0.57%   |
| TwinMOS                     | 1         | 1      | 0.28%   |
| Transcend                   | 1         | 1      | 0.28%   |
| Supersonic                  | 1         | 2      | 0.28%   |
| SPCC                        | 1         | 2      | 0.28%   |
| ShiJi                       | 1         | 2      | 0.28%   |
| Realtek Semiconductor       | 1         | 1      | 0.28%   |
| RCESSD                      | 1         | 1      | 0.28%   |
| O2 Micro                    | 1         | 1      | 0.28%   |
| Mushkin                     | 1         | 1      | 0.28%   |
| MSI                         | 1         | 1      | 0.28%   |
| Magnetic Data               | 1         | 1      | 0.28%   |
| LITEONIT                    | 1         | 1      | 0.28%   |
| Lexar                       | 1         | 1      | 0.28%   |
| Kingston Technology Company | 1         | 1      | 0.28%   |
| KingSpec                    | 1         | 1      | 0.28%   |
| Intenso                     | 1         | 2      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 6         | 1.62%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 1.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 1.35%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 1.08%   |
| Toshiba MQ01ABD050 500GB               | 4         | 1.08%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 1.08%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 3         | 0.81%   |
| Unknown MMC Card  32GB                 | 3         | 0.81%   |
| Toshiba MQ01ACF050 500GB               | 3         | 0.81%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.81%   |
| Seagate ST9500325AS 500GB              | 3         | 0.81%   |
| Seagate ST500LM000-1EJ162 500GB        | 3         | 0.81%   |
| Seagate ST500DM002-1BD142 500GB        | 3         | 0.81%   |
| Seagate ST3250312AS 250GB              | 3         | 0.81%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.81%   |
| Intel SSDSC2BF180A4H 180GB             | 3         | 0.81%   |
| Hitachi HUA723020ALA641 2TB            | 3         | 0.81%   |
| HGST HTS725050A7E630 500GB             | 3         | 0.81%   |
| HGST HTS545050A7E680 500GB             | 3         | 0.81%   |
| Unknown                                | 3         | 0.81%   |
| WDC WD800JD-00LSA0 80GB                | 2         | 0.54%   |
| WDC WD5000LPCX-80VHAT1 500GB           | 2         | 0.54%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 0.54%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB               | 2         | 0.54%   |
| Unknown MMC Card  64GB                 | 2         | 0.54%   |
| Unknown MMC Card  16GB                 | 2         | 0.54%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.54%   |
| Toshiba MQ01ABD050V -63 500GB          | 2         | 0.54%   |
| Toshiba KXG50ZNV256G 256GB             | 2         | 0.54%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.54%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 0.54%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 0.54%   |
| Samsung MZVLB512HAJQ-000L7 512GB       | 2         | 0.54%   |
| Samsung MZVLB1T0HALR-00000 1TB         | 2         | 0.54%   |
| Samsung MZ7LN128HCHP-000H1 128GB SSD   | 2         | 0.54%   |
| PNY CS900 120GB SSD                    | 2         | 0.54%   |
| LITEON IT LCS-128L9S-HP 128GB SSD      | 2         | 0.54%   |
| KingFast SSD 256GB                     | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 74     | 31.15%  |
| WDC                 | 44        | 60     | 24.04%  |
| Toshiba             | 32        | 41     | 17.49%  |
| Hitachi             | 22        | 27     | 12.02%  |
| HGST                | 13        | 13     | 7.1%    |
| Samsung Electronics | 6         | 9      | 3.28%   |
| Fujitsu             | 4         | 4      | 2.19%   |
| Apple               | 2         | 2      | 1.09%   |
| Magnetic Data       | 1         | 1      | 0.55%   |
| IBM/Hitachi         | 1         | 1      | 0.55%   |
| HPE                 | 1         | 1      | 0.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 20     | 16.85%  |
| SanDisk             | 8         | 8      | 8.99%   |
| Kingston            | 6         | 8      | 6.74%   |
| Intel               | 5         | 6      | 5.62%   |
| China               | 5         | 6      | 5.62%   |
| PNY                 | 4         | 5      | 4.49%   |
| Micron Technology   | 4         | 6      | 4.49%   |
| LITEON              | 4         | 4      | 4.49%   |
| Crucial             | 4         | 5      | 4.49%   |
| SK hynix            | 3         | 3      | 3.37%   |
| KingFast            | 3         | 3      | 3.37%   |
| Apple               | 3         | 3      | 3.37%   |
| KingDian            | 2         | 6      | 2.25%   |
| GOODRAM             | 2         | 2      | 2.25%   |
| Unknown             | 2         | 2      | 2.25%   |
| WDC                 | 1         | 1      | 1.12%   |
| TwinMOS             | 1         | 1      | 1.12%   |
| Transcend           | 1         | 1      | 1.12%   |
| Toshiba             | 1         | 1      | 1.12%   |
| Supersonic          | 1         | 2      | 1.12%   |
| SPCC                | 1         | 2      | 1.12%   |
| RCESSD              | 1         | 1      | 1.12%   |
| Mushkin             | 1         | 1      | 1.12%   |
| MSI                 | 1         | 1      | 1.12%   |
| LITEONIT            | 1         | 1      | 1.12%   |
| Lexar               | 1         | 1      | 1.12%   |
| KingSpec            | 1         | 1      | 1.12%   |
| Indilinx            | 1         | 1      | 1.12%   |
| HS-SSD-E100         | 1         | 1      | 1.12%   |
| Hewlett-Packard     | 1         | 1      | 1.12%   |
| BIWIN               | 1         | 1      | 1.12%   |
| Apacer              | 1         | 1      | 1.12%   |
| A-DATA Technology   | 1         | 1      | 1.12%   |
| 2.5"                | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 169       | 233    | 51.52%  |
| SSD     | 83        | 108    | 25.3%   |
| NVMe    | 56        | 72     | 17.07%  |
| MMC     | 17        | 23     | 5.18%   |
| Unknown | 3         | 6      | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 232       | 343    | 75.57%  |
| NVMe | 56        | 72     | 18.24%  |
| MMC  | 17        | 23     | 5.54%   |
| SAS  | 2         | 4      | 0.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 180       | 240    | 72%     |
| 0.51-1.0   | 57        | 84     | 22.8%   |
| 1.01-2.0   | 9         | 12     | 3.6%    |
| 2.01-3.0   | 2         | 3      | 0.8%    |
| 3.01-4.0   | 1         | 1      | 0.4%    |
| 4.01-10.0  | 1         | 1      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 82        | 27.89%  |
| 251-500        | 75        | 25.51%  |
| 51-100         | 33        | 11.22%  |
| 1-20           | 31        | 10.54%  |
| 501-1000       | 26        | 8.84%   |
| 21-50          | 22        | 7.48%   |
| 1001-2000      | 10        | 3.4%    |
| Unknown        | 7         | 2.38%   |
| More than 3000 | 6         | 2.04%   |
| 2001-3000      | 2         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 135       | 43.27%  |
| 21-50          | 68        | 21.79%  |
| 51-100         | 39        | 12.5%   |
| 101-250        | 37        | 11.86%  |
| 251-500        | 13        | 4.17%   |
| Unknown        | 7         | 2.24%   |
| More than 3000 | 4         | 1.28%   |
| 1001-2000      | 4         | 1.28%   |
| 501-1000       | 4         | 1.28%   |
| 2001-3000      | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB                         | 3         | 3      | 6.52%   |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 6.52%   |
| Seagate ST500DM002-1BD142 500GB                  | 3         | 3      | 6.52%   |
| Seagate ST500LM021-1KJ152 500GB                  | 2         | 2      | 4.35%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 4.35%   |
| Hitachi HDS721680PLA380 80GB                     | 2         | 3      | 4.35%   |
| WDC WD800AAJS-60WAA0 80GB                        | 1         | 1      | 2.17%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 2.17%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 2.17%   |
| WDC WD2500AAJS-60Z0A0 250GB                      | 1         | 1      | 2.17%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 5      | 2.17%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.17%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 2.17%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 2.17%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 2.17%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 2.17%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.17%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 2.17%   |
| Seagate ST340016A 40GB                           | 1         | 1      | 2.17%   |
| Seagate ST340014AS 40GB                          | 1         | 1      | 2.17%   |
| Seagate ST3250312AS 250GB                        | 1         | 1      | 2.17%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 2.17%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.17%   |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 2.17%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 2.17%   |
| Kingston SA400S37480G 480GB SSD                  | 1         | 2      | 2.17%   |
| HPE MM1000GBKAL 1TB                              | 1         | 1      | 2.17%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 2.17%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 2.17%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 2.17%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 2.17%   |
| HGST HTS545032A7E660 320GB                       | 1         | 1      | 2.17%   |
| Fujitsu MHX2300BT 304GB                          | 1         | 1      | 2.17%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 2.17%   |
| Apple HDD HTS541010A9E662 1TB                    | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 32.61%  |
| Toshiba             | 8         | 8      | 17.39%  |
| Hitachi             | 6         | 8      | 13.04%  |
| WDC                 | 5         | 9      | 10.87%  |
| HGST                | 3         | 3      | 6.52%   |
| Samsung Electronics | 2         | 2      | 4.35%   |
| Fujitsu             | 2         | 2      | 4.35%   |
| SanDisk             | 1         | 1      | 2.17%   |
| Micron Technology   | 1         | 1      | 2.17%   |
| Kingston            | 1         | 2      | 2.17%   |
| HPE                 | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 35.71%  |
| Toshiba             | 8         | 8      | 19.05%  |
| Hitachi             | 6         | 8      | 14.29%  |
| WDC                 | 5         | 9      | 11.9%   |
| HGST                | 3         | 3      | 7.14%   |
| Fujitsu             | 2         | 2      | 4.76%   |
| Samsung Electronics | 1         | 1      | 2.38%   |
| HPE                 | 1         | 1      | 2.38%   |
| Apple               | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 48     | 91.11%  |
| SSD  | 4         | 5      | 8.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD800JD-00LSA0 80GB                    | 2         | 3      | 50%     |
| WDC WD2500BEVT-22A23T0 208GB               | 1         | 2      | 25%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 5      | 75%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 164       | 243    | 52.56%  |
| Works    | 99        | 140    | 31.73%  |
| Malfunc  | 45        | 53     | 14.42%  |
| Failed   | 4         | 6      | 1.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 228       | 73.08%  |
| Samsung Electronics              | 26        | 8.33%   |
| AMD                              | 22        | 7.05%   |
| Toshiba America Info Systems     | 6         | 1.92%   |
| SanDisk                          | 6         | 1.92%   |
| KIOXIA                           | 5         | 1.6%    |
| Phison Electronics               | 3         | 0.96%   |
| Nvidia                           | 3         | 0.96%   |
| SK hynix                         | 2         | 0.64%   |
| Silicon Integrated Systems [SiS] | 2         | 0.64%   |
| Kingston Technology Company      | 2         | 0.64%   |
| Realtek Semiconductor            | 1         | 0.32%   |
| O2 Micro                         | 1         | 0.32%   |
| LSI Logic / Symbios Logic        | 1         | 0.32%   |
| JMicron Technology               | 1         | 0.32%   |
| Broadcom / LSI                   | 1         | 0.32%   |
| Apple                            | 1         | 0.32%   |
| ADATA Technology                 | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 23        | 6.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 20        | 5.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20        | 5.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15        | 4.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 15        | 4.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 14        | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 3.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 3.36%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.24%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 2.24%   |
| Intel SATA Controller [RAID mode]                                                       | 8         | 2.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 8         | 2.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.68%   |
| Samsung NVMe SSD Controller 980                                                         | 5         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.12%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 3         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 3         | 0.84%   |
| Intel SSD 660P Series                                                                   | 3         | 0.84%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3         | 0.84%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3         | 0.84%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3         | 0.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.84%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 0.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.56%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 0.56%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                   | 2         | 0.56%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.56%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.56%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 201       | 60.18%  |
| NVMe | 56        | 16.77%  |
| RAID | 42        | 12.57%  |
| IDE  | 31        | 9.28%   |
| SAS  | 3         | 0.9%    |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 252       | 88.42%  |
| AMD    | 30        | 10.53%  |
| ARM    | 3         | 1.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 2.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 2.11%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 2.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 1.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 1.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5         | 1.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 1.75%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 1.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.4%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.4%    |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.05%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3         | 1.05%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.05%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.05%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.05%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 1.05%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 3         | 1.05%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.05%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 2         | 0.7%    |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 2         | 0.7%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 0.7%    |
| Intel Core i7-7600U CPU @ 2.80GHz           | 2         | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 0.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.7%    |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.7%    |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.7%    |
| Intel Core i5-4200M CPU @ 2.50GHz           | 2         | 0.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 104       | 36.49%  |
| Intel Core i7           | 47        | 16.49%  |
| Intel Core i3           | 35        | 12.28%  |
| Other                   | 14        | 4.91%   |
| Intel Core 2 Duo        | 13        | 4.56%   |
| Intel Xeon              | 9         | 3.16%   |
| Intel Celeron           | 9         | 3.16%   |
| Intel Atom              | 6         | 2.11%   |
| AMD Ryzen 5             | 6         | 2.11%   |
| Intel Pentium Dual-Core | 4         | 1.4%    |
| AMD Ryzen 9             | 3         | 1.05%   |
| AMD Ryzen 7             | 3         | 1.05%   |
| AMD E1                  | 3         | 1.05%   |
| Intel Pentium           | 2         | 0.7%    |
| ARM BCM                 | 2         | 0.7%    |
| AMD C-60                | 2         | 0.7%    |
| AMD Athlon 64 X2        | 2         | 0.7%    |
| AMD A8                  | 2         | 0.7%    |
| AMD A6                  | 2         | 0.7%    |
| Intel Pentium Silver    | 1         | 0.35%   |
| Intel Pentium M         | 1         | 0.35%   |
| Intel Pentium Gold      | 1         | 0.35%   |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Pentium 4         | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core i9           | 1         | 0.35%   |
| Intel Core 2 Quad       | 1         | 0.35%   |
| Intel Core 2            | 1         | 0.35%   |
| Intel Celeron M         | 1         | 0.35%   |
| ARM AArch64             | 1         | 0.35%   |
| AMD Ryzen 7 PRO         | 1         | 0.35%   |
| AMD Ryzen 3             | 1         | 0.35%   |
| AMD Phenom II X6        | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD Athlon XP           | 1         | 0.35%   |
| AMD A4                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 156       | 54.74%  |
| 4      | 94        | 32.98%  |
| 6      | 11        | 3.86%   |
| 1      | 8         | 2.81%   |
| 8      | 7         | 2.46%   |
| 12     | 4         | 1.4%    |
| 16     | 3         | 1.05%   |
| 10     | 2         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 280       | 98.25%  |
| 2      | 5         | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 199       | 69.82%  |
| 1      | 86        | 30.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 276       | 96.84%  |
| 32-bit         | 5         | 1.75%   |
| Unknown        | 4         | 1.4%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 24.74%  |
| 0x206a7    | 25        | 8.59%   |
| 0x306c3    | 19        | 6.53%   |
| 0x306a9    | 16        | 5.5%    |
| 0x306d4    | 14        | 4.81%   |
| 0x806ea    | 12        | 4.12%   |
| 0x40651    | 11        | 3.78%   |
| 0x806ec    | 9         | 3.09%   |
| 0x20655    | 9         | 3.09%   |
| 0x1067a    | 8         | 2.75%   |
| 0x806c1    | 7         | 2.41%   |
| 0x506e3    | 7         | 2.41%   |
| 0x806e9    | 6         | 2.06%   |
| 0x406e3    | 6         | 2.06%   |
| 0x6fd      | 5         | 1.72%   |
| 0x20652    | 5         | 1.72%   |
| 0x30678    | 4         | 1.37%   |
| 0x906e9    | 3         | 1.03%   |
| 0x6fb      | 3         | 1.03%   |
| 0x206d7    | 3         | 1.03%   |
| 0x10676    | 3         | 1.03%   |
| 0x0a50000c | 3         | 1.03%   |
| 0x08701021 | 3         | 1.03%   |
| 0x906ea    | 2         | 0.69%   |
| 0x706e5    | 2         | 0.69%   |
| 0x406c4    | 2         | 0.69%   |
| 0x406c3    | 2         | 0.69%   |
| 0x08108102 | 2         | 0.69%   |
| 0x07030105 | 2         | 0.69%   |
| 0x0700010f | 2         | 0.69%   |
| 0x05000119 | 2         | 0.69%   |
| 0xf29      | 1         | 0.34%   |
| 0xb06a3    | 1         | 0.34%   |
| 0x90675    | 1         | 0.34%   |
| 0x806eb    | 1         | 0.34%   |
| 0x806d1    | 1         | 0.34%   |
| 0x706a1    | 1         | 0.34%   |
| 0x6ec      | 1         | 0.34%   |
| 0x6e8      | 1         | 0.34%   |
| 0x6d8      | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 14.74%  |
| Haswell          | 42        | 14.74%  |
| SandyBridge      | 30        | 10.53%  |
| Westmere         | 20        | 7.02%   |
| Skylake          | 20        | 7.02%   |
| IvyBridge        | 19        | 6.67%   |
| Broadwell        | 18        | 6.32%   |
| Penryn           | 13        | 4.56%   |
| Silvermont       | 11        | 3.86%   |
| TigerLake        | 9         | 3.16%   |
| Core             | 9         | 3.16%   |
| Unknown          | 7         | 2.46%   |
| Zen 3            | 5         | 1.75%   |
| IceLake          | 5         | 1.75%   |
| Zen 2            | 4         | 1.4%    |
| Bobcat           | 4         | 1.4%    |
| Zen+             | 3         | 1.05%   |
| P6               | 3         | 1.05%   |
| Alderlake Hybrid | 3         | 1.05%   |
| Puma             | 2         | 0.7%    |
| K8 Hammer        | 2         | 0.7%    |
| Jaguar           | 2         | 0.7%    |
| Goldmont plus    | 2         | 0.7%    |
| Bonnell          | 2         | 0.7%    |
| Piledriver       | 1         | 0.35%   |
| NetBurst         | 1         | 0.35%   |
| Nehalem          | 1         | 0.35%   |
| K6               | 1         | 0.35%   |
| K10 Llano        | 1         | 0.35%   |
| K10              | 1         | 0.35%   |
| Excavator        | 1         | 0.35%   |
| CometLake        | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 220       | 66.07%  |
| Nvidia                           | 71        | 21.32%  |
| AMD                              | 41        | 12.31%  |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 7.4%    |
| Intel HD Graphics 5500                                                                   | 16        | 4.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 4.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 4.73%   |
| Intel UHD Graphics 620                                                                   | 14        | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 2.96%   |
| Intel HD Graphics 620                                                                    | 9         | 2.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 2.66%   |
| Intel HD Graphics 530                                                                    | 8         | 2.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.48%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.18%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.89%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.89%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 3         | 0.89%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.89%   |
| Intel HD Graphics 630                                                                    | 3         | 0.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.89%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.59%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.59%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.59%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 2         | 0.59%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.59%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 170       | 59.44%  |
| Intel + Nvidia | 42        | 14.69%  |
| 1 x AMD        | 32        | 11.19%  |
| 1 x Nvidia     | 28        | 9.79%   |
| Intel + AMD    | 7         | 2.45%   |
| Other          | 3         | 1.05%   |
| 2 x Nvidia     | 1         | 0.35%   |
| 2 x AMD        | 1         | 0.35%   |
| 1 x SiS        | 1         | 0.35%   |
| AMD + Nvidia   | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 243       | 83.79%  |
| Proprietary | 34        | 11.72%  |
| Unknown     | 13        | 4.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 200       | 68.49%  |
| 1.01-2.0   | 34        | 11.64%  |
| 0.01-0.5   | 29        | 9.93%   |
| 3.01-4.0   | 14        | 4.79%   |
| 0.51-1.0   | 11        | 3.77%   |
| 7.01-8.0   | 3         | 1.03%   |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 41        | 14.8%   |
| LG Display              | 41        | 14.8%   |
| AU Optronics            | 39        | 14.08%  |
| Chimei Innolux          | 37        | 13.36%  |
| BOE                     | 27        | 9.75%   |
| Dell                    | 16        | 5.78%   |
| Hewlett-Packard         | 15        | 5.42%   |
| InfoVision              | 8         | 2.89%   |
| Goldstar                | 6         | 2.17%   |
| Lenovo                  | 5         | 1.81%   |
| Apple                   | 5         | 1.81%   |
| Chi Mei Optoelectronics | 4         | 1.44%   |
| Sharp                   | 3         | 1.08%   |
| LG Philips              | 3         | 1.08%   |
| Iiyama                  | 3         | 1.08%   |
| BenQ                    | 3         | 1.08%   |
| Acer                    | 3         | 1.08%   |
| Philips                 | 2         | 0.72%   |
| MSI                     | 2         | 0.72%   |
| Fujitsu Siemens         | 2         | 0.72%   |
| Ancor Communications    | 2         | 0.72%   |
| Valve                   | 1         | 0.36%   |
| TMX                     | 1         | 0.36%   |
| RTK                     | 1         | 0.36%   |
| PANDA                   | 1         | 0.36%   |
| MiTAC                   | 1         | 0.36%   |
| Medion                  | 1         | 0.36%   |
| LGD                     | 1         | 0.36%   |
| IBM                     | 1         | 0.36%   |
| CNC                     | 1         | 0.36%   |
| Unknown                 | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 3         | 1.08%   |
| Dell E2414H DEL4090 1920x1080 530x300mm 24.0-inch                        | 3         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 1.08%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.08%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.72%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                          | 2         | 0.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.72%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.72%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch               | 2         | 0.72%   |
| InfoVision LCD Monitor IVO0535 1920x1080 294x165mm 13.3-inch             | 2         | 0.72%   |
| Hewlett-Packard 25x HPN357E 1920x1080 544x303mm 24.5-inch                | 2         | 0.72%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 0.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.72%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.72%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.36%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP14A8 3840x2400 288x180mm 13.4-inch                  | 1         | 0.36%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch     | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch     | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 338x270mm 17.0-inch     | 1         | 0.36%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch       | 1         | 0.36%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 1         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 99        | 36.67%  |
| 1920x1080 (FHD)    | 93        | 34.44%  |
| 1600x900 (HD+)     | 18        | 6.67%   |
| 1440x900 (WXGA+)   | 10        | 3.7%    |
| 3840x2160 (4K)     | 8         | 2.96%   |
| 1680x1050 (WSXGA+) | 8         | 2.96%   |
| 1280x1024 (SXGA)   | 8         | 2.96%   |
| 1280x800 (WXGA)    | 7         | 2.59%   |
| 1024x600           | 3         | 1.11%   |
| 3840x2400          | 2         | 0.74%   |
| 2560x1440 (QHD)    | 2         | 0.74%   |
| 1920x1200 (WUXGA)  | 2         | 0.74%   |
| 800x1280           | 1         | 0.37%   |
| 2880x1800          | 1         | 0.37%   |
| 2560x1600          | 1         | 0.37%   |
| 2520x1680          | 1         | 0.37%   |
| 1680x945           | 1         | 0.37%   |
| 1400x1050          | 1         | 0.37%   |
| 1360x768           | 1         | 0.37%   |
| 1280x720 (HD)      | 1         | 0.37%   |
| 1152x864           | 1         | 0.37%   |
| 1024x768 (XGA)     | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 116       | 41.58%  |
| 14      | 29        | 10.39%  |
| 13      | 26        | 9.32%   |
| 24      | 18        | 6.45%   |
| 12      | 13        | 4.66%   |
| 17      | 12        | 4.3%    |
| 23      | 9         | 3.23%   |
| 19      | 9         | 3.23%   |
| 27      | 7         | 2.51%   |
| 22      | 6         | 2.15%   |
| 18      | 6         | 2.15%   |
| 21      | 5         | 1.79%   |
| Unknown | 4         | 1.43%   |
| 20      | 3         | 1.08%   |
| 11      | 3         | 1.08%   |
| 84      | 2         | 0.72%   |
| 10      | 2         | 0.72%   |
| 72      | 1         | 0.36%   |
| 58      | 1         | 0.36%   |
| 54      | 1         | 0.36%   |
| 52      | 1         | 0.36%   |
| 43      | 1         | 0.36%   |
| 32      | 1         | 0.36%   |
| 31      | 1         | 0.36%   |
| 16      | 1         | 0.36%   |
| 7       | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 159       | 57.19%  |
| 201-300     | 32        | 11.51%  |
| 501-600     | 31        | 11.15%  |
| 401-500     | 25        | 8.99%   |
| 351-400     | 15        | 5.4%    |
| Unknown     | 4         | 1.44%   |
| 601-700     | 3         | 1.08%   |
| 1501-2000   | 3         | 1.08%   |
| 1001-1500   | 3         | 1.08%   |
| 701-800     | 1         | 0.36%   |
| 901-1000    | 1         | 0.36%   |
| 1-100       | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 218       | 81.34%  |
| 16/10   | 32        | 11.94%  |
| 5/4     | 8         | 2.99%   |
| Unknown | 4         | 1.49%   |
| 4/3     | 3         | 1.12%   |
| 3/2     | 2         | 0.75%   |
| 0.67    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 116       | 41.73%  |
| 81-90          | 43        | 15.47%  |
| 201-250        | 30        | 10.79%  |
| 151-200        | 15        | 5.4%    |
| 61-70          | 13        | 4.68%   |
| 71-80          | 10        | 3.6%    |
| 141-150        | 9         | 3.24%   |
| 301-350        | 7         | 2.52%   |
| More than 1000 | 6         | 2.16%   |
| 251-300        | 6         | 2.16%   |
| 121-130        | 5         | 1.8%    |
| Unknown        | 4         | 1.44%   |
| 51-60          | 3         | 1.08%   |
| 351-500        | 2         | 0.72%   |
| 41-50          | 2         | 0.72%   |
| 131-140        | 2         | 0.72%   |
| 111-120        | 2         | 0.72%   |
| 1-40           | 1         | 0.36%   |
| 501-1000       | 1         | 0.36%   |
| 91-100         | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 98        | 35.51%  |
| 121-160       | 73        | 26.45%  |
| 51-100        | 72        | 26.09%  |
| 161-240       | 20        | 7.25%   |
| 1-50          | 6         | 2.17%   |
| Unknown       | 4         | 1.45%   |
| More than 240 | 3         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 260       | 89.97%  |
| 2     | 19        | 6.57%   |
| 0     | 10        | 3.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 161       | 36.43%  |
| Realtek Semiconductor            | 119       | 26.92%  |
| Qualcomm Atheros                 | 51        | 11.54%  |
| Broadcom                         | 38        | 8.6%    |
| Ralink Technology                | 21        | 4.75%   |
| Ralink                           | 10        | 2.26%   |
| TP-Link                          | 6         | 1.36%   |
| Broadcom Limited                 | 5         | 1.13%   |
| Xiaomi                           | 3         | 0.68%   |
| Nvidia                           | 3         | 0.68%   |
| Dell                             | 3         | 0.68%   |
| Sierra Wireless                  | 2         | 0.45%   |
| Samsung Electronics              | 2         | 0.45%   |
| Marvell Technology Group         | 2         | 0.45%   |
| Lenovo                           | 2         | 0.45%   |
| Huawei Technologies              | 2         | 0.45%   |
| D-Link System                    | 2         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Qualcomm Atheros Communications  | 1         | 0.23%   |
| Qualcomm                         | 1         | 0.23%   |
| Microchip Technology             | 1         | 0.23%   |
| MediaTek                         | 1         | 0.23%   |
| JMicron Technology               | 1         | 0.23%   |
| Gemtek                           | 1         | 0.23%   |
| Fibocom                          | 1         | 0.23%   |
| Arduino SA                       | 1         | 0.23%   |
| Aquantia                         | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 13.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 4.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 4.04%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 3.12%   |
| Intel Wireless 8265 / 8275                                        | 13        | 2.39%   |
| Intel Wireless 7265                                               | 12        | 2.2%    |
| Intel 82577LM Gigabit Network Connection                          | 11        | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.83%   |
| Ralink MT7601U Wireless Adapter                                   | 10        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.83%   |
| Ralink RT5370 Wireless Adapter                                    | 9         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.65%   |
| Intel Wireless 8260                                               | 9         | 1.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 1.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.28%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.28%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 6         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.92%   |
| Intel Wireless 7260                                               | 5         | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.92%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 5         | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.73%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.73%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.73%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 41.2%   |
| Qualcomm Atheros                | 45        | 16.85%  |
| Realtek Semiconductor           | 36        | 13.48%  |
| Broadcom                        | 26        | 9.74%   |
| Ralink Technology               | 21        | 7.87%   |
| Ralink                          | 10        | 3.75%   |
| TP-Link                         | 6         | 2.25%   |
| Broadcom Limited                | 4         | 1.5%    |
| Sierra Wireless                 | 2         | 0.75%   |
| Dell                            | 2         | 0.75%   |
| Qualcomm Atheros Communications | 1         | 0.37%   |
| MediaTek                        | 1         | 0.37%   |
| Gemtek                          | 1         | 0.37%   |
| Fibocom                         | 1         | 0.37%   |
| D-Link System                   | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 13        | 4.83%   |
| Intel Wireless 7265                                            | 12        | 4.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.72%   |
| Ralink MT7601U Wireless Adapter                                | 10        | 3.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 3.72%   |
| Ralink RT5370 Wireless Adapter                                 | 9         | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 3.35%   |
| Intel Wireless 8260                                            | 9         | 3.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 3.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.6%    |
| Intel Wi-Fi 6 AX200                                            | 7         | 2.6%    |
| Intel Centrino Advanced-N 6200                                 | 7         | 2.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.23%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 2.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 2.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 5         | 1.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.86%   |
| Intel Wireless 7260                                            | 5         | 1.86%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.86%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 1.86%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 1.12%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.12%   |
| Intel Wireless 3165                                            | 3         | 1.12%   |
| Intel WiFi Link 5100                                           | 3         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.12%   |
| Sierra Wireless EM7455                                         | 2         | 0.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.74%   |
| Realtek 802.11ac NIC                                           | 2         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 116       | 43.45%  |
| Realtek Semiconductor            | 102       | 38.2%   |
| Broadcom                         | 16        | 5.99%   |
| Qualcomm Atheros                 | 12        | 4.49%   |
| Xiaomi                           | 3         | 1.12%   |
| Nvidia                           | 3         | 1.12%   |
| Samsung Electronics              | 2         | 0.75%   |
| Marvell Technology Group         | 2         | 0.75%   |
| Lenovo                           | 2         | 0.75%   |
| Huawei Technologies              | 2         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Qualcomm                         | 1         | 0.37%   |
| Microchip Technology             | 1         | 0.37%   |
| JMicron Technology               | 1         | 0.37%   |
| D-Link System                    | 1         | 0.37%   |
| Broadcom Limited                 | 1         | 0.37%   |
| Aquantia                         | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 72        | 26.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 26        | 9.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 8.06%   |
| Intel Ethernet Connection I217-LM                                              | 17        | 6.23%   |
| Intel 82577LM Gigabit Network Connection                                       | 11        | 4.03%   |
| Intel Ethernet Connection (3) I218-LM                                          | 9         | 3.3%    |
| Intel Ethernet Connection (2) I219-LM                                          | 9         | 3.3%    |
| Intel Ethernet Connection I218-LM                                              | 5         | 1.83%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 1.47%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 1.47%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.47%   |
| Intel Ethernet Connection I217-V                                               | 4         | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.1%    |
| Intel I210 Gigabit Network Connection                                          | 3         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.1%    |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 1.1%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 1.1%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 3         | 1.1%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.73%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 0.73%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 2         | 0.73%   |
| Huawei JKM-LX1                                                                 | 2         | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.73%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.37%   |
| Qualcomm Redmi Note 8                                                          | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.37%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.37%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 1         | 0.37%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 253       | 49.71%  |
| Ethernet | 253       | 49.71%  |
| Modem    | 3         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 206       | 72.28%  |
| Ethernet | 79        | 27.72%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 193       | 67.48%  |
| 1     | 79        | 27.62%  |
| 0     | 7         | 2.45%   |
| 3     | 6         | 2.1%    |
| 7     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 285       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 42.86%  |
| Realtek Semiconductor           | 21        | 12%     |
| Qualcomm Atheros Communications | 20        | 11.43%  |
| Broadcom                        | 13        | 7.43%   |
| IMC Networks                    | 8         | 4.57%   |
| Dell                            | 7         | 4%      |
| Ralink                          | 5         | 2.86%   |
| Lite-On Technology              | 5         | 2.86%   |
| Hewlett-Packard                 | 5         | 2.86%   |
| Cambridge Silicon Radio         | 5         | 2.86%   |
| Apple                           | 4         | 2.29%   |
| Toshiba                         | 2         | 1.14%   |
| ASUSTek Computer                | 2         | 1.14%   |
| Foxconn International           | 1         | 0.57%   |
| Foxconn / Hon Hai               | 1         | 0.57%   |
| Alps Electric                   | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 22.29%  |
| Realtek Bluetooth Radio                             | 14        | 8%      |
| Intel AX201 Bluetooth                               | 11        | 6.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 5.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 4%      |
| Intel AX200 Bluetooth                               | 7         | 4%      |
| IMC Networks Bluetooth Device                       | 6         | 3.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.86%   |
| Ralink RT3290 Bluetooth                             | 5         | 2.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 2.29%   |
| Dell DW375 Bluetooth Module                         | 4         | 2.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.71%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 1.71%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.71%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.14%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.14%   |
| Dell Wireless 360 Bluetooth                         | 2         | 1.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.14%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.14%   |
| Toshiba Bluetooth Device                            | 1         | 0.57%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.57%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.57%   |
| Intel Bluetooth Device                              | 1         | 0.57%   |
| IMC Networks Wireless_Device                        | 1         | 0.57%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.57%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.57%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.57%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.57%   |
| Dell Wireless 350 Bluetooth                         | 1         | 0.57%   |
| Broadcom HP Portable Valentine                      | 1         | 0.57%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 247       | 71.8%   |
| Nvidia                           | 45        | 13.08%  |
| AMD                              | 35        | 10.17%  |
| Silicon Integrated Systems [SiS] | 2         | 0.58%   |
| Lenovo                           | 2         | 0.58%   |
| GN Netcom                        | 2         | 0.58%   |
| Nordic Semiconductor ASA         | 1         | 0.29%   |
| Medeli Electronics               | 1         | 0.29%   |
| Logitech                         | 1         | 0.29%   |
| Kingston Technology              | 1         | 0.29%   |
| Hewlett-Packard                  | 1         | 0.29%   |
| Generalplus Technology           | 1         | 0.29%   |
| GEMBIRD                          | 1         | 0.29%   |
| Focusrite-Novation               | 1         | 0.29%   |
| EDFIER                           | 1         | 0.29%   |
| C-Media Electronics              | 1         | 0.29%   |
| ASUSTek Computer                 | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 7.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 5.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 23        | 5.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 5.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 4.52%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 4.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 4.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 3.81%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 3.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 3.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 2.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.14%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 2.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.43%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.19%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.95%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.71%   |
| Nvidia Audio device                                                                               | 3         | 0.71%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.71%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.71%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.48%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 62        | 29.52%  |
| SK hynix            | 55        | 26.19%  |
| Micron Technology   | 29        | 13.81%  |
| Kingston            | 20        | 9.52%   |
| Unknown             | 6         | 2.86%   |
| Elpida              | 5         | 2.38%   |
| Ramaxel Technology  | 4         | 1.9%    |
| Nanya Technology    | 4         | 1.9%    |
| Crucial             | 4         | 1.9%    |
| Corsair             | 4         | 1.9%    |
| A-DATA Technology   | 4         | 1.9%    |
| Sesame              | 2         | 0.95%   |
| Unknown             | 2         | 0.95%   |
| Wilk                | 1         | 0.48%   |
| Transcend           | 1         | 0.48%   |
| Toshiba             | 1         | 0.48%   |
| TakeMS              | 1         | 0.48%   |
| Qimonda             | 1         | 0.48%   |
| G.Skill             | 1         | 0.48%   |
| Avant               | 1         | 0.48%   |
| ASint Technology    | 1         | 0.48%   |
| Apacer              | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s        | 4         | 1.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 1.74%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 1.74%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s   | 3         | 1.3%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 1.3%    |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s         | 3         | 1.3%    |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 3         | 1.3%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 3         | 1.3%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s        | 2         | 0.87%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.87%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 0.87%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 0.87%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                 | 2         | 0.87%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                   | 2         | 0.87%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s    | 2         | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.87%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.87%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 0.87%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.87%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1866MT/s       | 2         | 0.87%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 2         | 0.87%   |
| Kingston RAM HP687515-H66-MCN 4GB SODIMM DDR3 1600MT/s      | 2         | 0.87%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 2         | 0.87%   |
| Unknown                                                     | 2         | 0.87%   |
| Wilk RAM Module 16GB DIMM DDR4 2667MT/s                     | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s              | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM                                 | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 0.43%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s         | 1         | 0.43%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s           | 1         | 0.43%   |
| TakeMS RAM TMS2GB264C081-665U 2048MB DIMM DDR2 667MT/s      | 1         | 0.43%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 76        | 47.8%   |
| DDR4    | 55        | 34.59%  |
| DDR2    | 8         | 5.03%   |
| SDRAM   | 7         | 4.4%    |
| LPDDR4  | 5         | 3.14%   |
| LPDDR3  | 3         | 1.89%   |
| Unknown | 3         | 1.89%   |
| DDR5    | 1         | 0.63%   |
| DDR     | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 69.74%  |
| DIMM         | 37        | 24.34%  |
| Row Of Chips | 6         | 3.95%   |
| Unknown      | 2         | 1.32%   |
| RIMM         | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 67        | 37.43%  |
| 8192  | 58        | 32.4%   |
| 2048  | 23        | 12.85%  |
| 16384 | 16        | 8.94%   |
| 1024  | 9         | 5.03%   |
| 32768 | 2         | 1.12%   |
| 512   | 2         | 1.12%   |
| 256   | 1         | 0.56%   |
| 128   | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 54        | 29.67%  |
| 2667    | 23        | 12.64%  |
| 3200    | 15        | 8.24%   |
| 1334    | 14        | 7.69%   |
| 2400    | 12        | 6.59%   |
| 1333    | 12        | 6.59%   |
| 2133    | 9         | 4.95%   |
| 1648    | 4         | 2.2%    |
| 1066    | 4         | 2.2%    |
| 800     | 4         | 2.2%    |
| 667     | 4         | 2.2%    |
| 3600    | 3         | 1.65%   |
| 1867    | 3         | 1.65%   |
| Unknown | 3         | 1.65%   |
| 3266    | 2         | 1.1%    |
| 1067    | 2         | 1.1%    |
| 975     | 2         | 1.1%    |
| 4800    | 1         | 0.55%   |
| 4267    | 1         | 0.55%   |
| 4199    | 1         | 0.55%   |
| 3733    | 1         | 0.55%   |
| 3400    | 1         | 0.55%   |
| 2666    | 1         | 0.55%   |
| 1866    | 1         | 0.55%   |
| 1639    | 1         | 0.55%   |
| 1331    | 1         | 0.55%   |
| 400     | 1         | 0.55%   |
| 333     | 1         | 0.55%   |
| 266     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 27.17%  |
| IMC Networks                           | 19        | 10.33%  |
| Realtek Semiconductor                  | 17        | 9.24%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 9.24%   |
| Sunplus Innovation Technology          | 11        | 5.98%   |
| Suyin                                  | 10        | 5.43%   |
| Lite-On Technology                     | 10        | 5.43%   |
| Microdia                               | 8         | 4.35%   |
| Quanta                                 | 7         | 3.8%    |
| Bison Electronics                      | 5         | 2.72%   |
| Syntek                                 | 4         | 2.17%   |
| Ricoh                                  | 4         | 2.17%   |
| Apple                                  | 4         | 2.17%   |
| Logitech                               | 3         | 1.63%   |
| Luxvisions Innotech Limited            | 2         | 1.09%   |
| ALi                                    | 2         | 1.09%   |
| Alcor Micro                            | 2         | 1.09%   |
| Z-Star Microelectronics                | 1         | 0.54%   |
| Sunplus Technology                     | 1         | 0.54%   |
| Sonix Technology                       | 1         | 0.54%   |
| Silicon Motion                         | 1         | 0.54%   |
| ShineTech                              | 1         | 0.54%   |
| OPPO Electronics                       | 1         | 0.54%   |
| Jieli Technology                       | 1         | 0.54%   |
| icSpring                               | 1         | 0.54%   |
| Acer                                   | 1         | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 3.78%   |
| IMC Networks Integrated Camera                              | 6         | 3.24%   |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 3.24%   |
| Chicony HP Webcam                                           | 6         | 3.24%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 5         | 2.7%    |
| Realtek Integrated_Webcam_HD                                | 4         | 2.16%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 2.16%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 1.62%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 1.62%   |
| Realtek USB Camera                                          | 3         | 1.62%   |
| Microdia Integrated Webcam                                  | 3         | 1.62%   |
| Lite-On HP HD Webcam                                        | 3         | 1.62%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.62%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.62%   |
| Chicony HP Wide Vision HD Camera                            | 3         | 1.62%   |
| Chicony HP HD Webcam                                        | 3         | 1.62%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.08%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 1.08%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.08%   |
| Sunplus HP Universal Camera                                 | 2         | 1.08%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.08%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 1.08%   |
| Quanta HD Webcam                                            | 2         | 1.08%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.08%   |
| Lite-On HP HD Camera                                        | 2         | 1.08%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.08%   |
| IMC Networks Integrated Webcam                              | 2         | 1.08%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.08%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.08%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.08%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.08%   |
| Chicony HP Truevision HD                                    | 2         | 1.08%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.08%   |
| Bison Integrated Camera                                     | 2         | 1.08%   |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 1.08%   |
| Z-Star Vimicro USB2.0 Camera                                | 1         | 0.54%   |
| Syntek Integrated Camera                                    | 1         | 0.54%   |
| Syntek EasyCamera                                           | 1         | 0.54%   |
| Suyin WebCam                                                | 1         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 68.18%  |
| Synaptics                  | 6         | 13.64%  |
| Elan Microelectronics      | 4         | 9.09%   |
| Shenzhen Goodix Technology | 2         | 4.55%   |
| Upek                       | 1         | 2.27%   |
| Focal-systems.Corp         | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 25%     |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 11.36%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 6.82%   |
| Validity Sensors VFS491                                                    | 2         | 4.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.55%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.55%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.27%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.27%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 2.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.27%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.27%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.27%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.27%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.27%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 66.67%  |
| Alcor Micro | 6         | 20%     |
| O2 Micro    | 4         | 13.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 181       | 61.99%  |
| 1     | 89        | 30.48%  |
| 2     | 17        | 5.82%   |
| 3     | 4         | 1.37%   |
| 5     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 31.88%  |
| Chipcard                 | 26        | 18.84%  |
| Graphics card            | 25        | 18.12%  |
| Net/wireless             | 13        | 9.42%   |
| Bluetooth                | 6         | 4.35%   |
| Storage                  | 5         | 3.62%   |
| Camera                   | 4         | 2.9%    |
| Unassigned class         | 3         | 2.17%   |
| Multimedia controller    | 3         | 2.17%   |
| Communication controller | 3         | 2.17%   |
| Sound                    | 2         | 1.45%   |
| Net/ethernet             | 2         | 1.45%   |
| Network                  | 1         | 0.72%   |
| Modem                    | 1         | 0.72%   |

