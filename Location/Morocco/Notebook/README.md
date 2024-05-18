Linux in Morocco - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

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

Total: 364

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X550LD                      | [1c55e1acf7](https://linux-hardware.org/?probe=1c55e1acf7) | May 08, 2024 |
| HP            | Laptop 15-ra0xx             | [4d00a746ff](https://linux-hardware.org/?probe=4d00a746ff) | May 02, 2024 |
| MSI           | GS66 Stealth 10SE           | [e436c09a5c](https://linux-hardware.org/?probe=e436c09a5c) | Apr 30, 2024 |
| ACCENT        | SMART 140                   | [49fb07fe3f](https://linux-hardware.org/?probe=49fb07fe3f) | Apr 27, 2024 |
| Acer          | Aspire 7750G                | [961d70c1de](https://linux-hardware.org/?probe=961d70c1de) | Apr 27, 2024 |
| Acer          | Nitro AN515-46              | [0a90ca1966](https://linux-hardware.org/?probe=0a90ca1966) | Apr 23, 2024 |
| Dell          | Latitude E7240              | [71103e976e](https://linux-hardware.org/?probe=71103e976e) | Apr 21, 2024 |
| HP            | ProBook 450 G0              | [686202a739](https://linux-hardware.org/?probe=686202a739) | Apr 13, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [c4c0c27585](https://linux-hardware.org/?probe=c4c0c27585) | Apr 13, 2024 |
| HP            | ProBook 450 G0              | [becdc6cf99](https://linux-hardware.org/?probe=becdc6cf99) | Apr 12, 2024 |
| HP            | Split 13 x2 Detachable P... | [17c8956856](https://linux-hardware.org/?probe=17c8956856) | Apr 12, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [4d6466d304](https://linux-hardware.org/?probe=4d6466d304) | Apr 10, 2024 |
| HP            | ZBook 17 G5                 | [2b22c5c485](https://linux-hardware.org/?probe=2b22c5c485) | Apr 07, 2024 |
| Fujitsu       | LIFEBOOK S761               | [e73c5851aa](https://linux-hardware.org/?probe=e73c5851aa) | Mar 30, 2024 |
| Dell          | Inspiron 3421               | [a5606e10ad](https://linux-hardware.org/?probe=a5606e10ad) | Mar 27, 2024 |
| ASUSTek       | X550LD                      | [91112364b8](https://linux-hardware.org/?probe=91112364b8) | Mar 26, 2024 |
| ASUSTek       | X550LD                      | [1c72f8459c](https://linux-hardware.org/?probe=1c72f8459c) | Mar 26, 2024 |
| Dell          | Latitude 5480               | [ff785a4ce1](https://linux-hardware.org/?probe=ff785a4ce1) | Mar 22, 2024 |
| Acer          | Aspire E5-771G              | [3b5d0f6921](https://linux-hardware.org/?probe=3b5d0f6921) | Mar 19, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [0339864371](https://linux-hardware.org/?probe=0339864371) | Mar 09, 2024 |
| Dell          | Latitude 5289               | [fe338e3231](https://linux-hardware.org/?probe=fe338e3231) | Mar 09, 2024 |
| Dell          | Latitude E5550              | [4832591086](https://linux-hardware.org/?probe=4832591086) | Mar 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e545b12914](https://linux-hardware.org/?probe=e545b12914) | Mar 07, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [f44261baba](https://linux-hardware.org/?probe=f44261baba) | Feb 24, 2024 |
| Lenovo        | ThinkPad T410 2537VTC       | [a393686fff](https://linux-hardware.org/?probe=a393686fff) | Feb 18, 2024 |
| Acer          | Swift SFX14-51G             | [038f3ddc2e](https://linux-hardware.org/?probe=038f3ddc2e) | Feb 14, 2024 |
| HP            | EliteBook 850 G3            | [a3d2bf6949](https://linux-hardware.org/?probe=a3d2bf6949) | Feb 10, 2024 |
| Dell          | Latitude 5510               | [e0d5fe1c62](https://linux-hardware.org/?probe=e0d5fe1c62) | Feb 07, 2024 |
| HP            | 620                         | [523cfc94c0](https://linux-hardware.org/?probe=523cfc94c0) | Feb 03, 2024 |
| HP            | ProBook 5320m               | [3be604f862](https://linux-hardware.org/?probe=3be604f862) | Feb 03, 2024 |
| HP            | 15                          | [b99530abd5](https://linux-hardware.org/?probe=b99530abd5) | Feb 01, 2024 |
| HP            | 15                          | [874ae10280](https://linux-hardware.org/?probe=874ae10280) | Feb 01, 2024 |
| HP            | 620                         | [adcf9577e4](https://linux-hardware.org/?probe=adcf9577e4) | Feb 01, 2024 |
| ASUSTek       | X555LD                      | [e65c871d95](https://linux-hardware.org/?probe=e65c871d95) | Jan 31, 2024 |
| ASUSTek       | X555LD                      | [1433f11bba](https://linux-hardware.org/?probe=1433f11bba) | Jan 31, 2024 |
| Sony          | VPCF12A4E                   | [66fb5f96a0](https://linux-hardware.org/?probe=66fb5f96a0) | Jan 30, 2024 |
| HP            | ProBook 6560b               | [7b9f78e8df](https://linux-hardware.org/?probe=7b9f78e8df) | Jan 23, 2024 |
| HP            | EliteBook 840 G3            | [ea1922427f](https://linux-hardware.org/?probe=ea1922427f) | Jan 19, 2024 |
| Dell          | Latitude 7390               | [837b633afe](https://linux-hardware.org/?probe=837b633afe) | Jan 14, 2024 |
| HP            | EliteBook 830 G5            | [106a150b97](https://linux-hardware.org/?probe=106a150b97) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | [f6b222e444](https://linux-hardware.org/?probe=f6b222e444) | Jan 06, 2024 |
| HP            | EliteBook 840 G5            | [0af2ce345e](https://linux-hardware.org/?probe=0af2ce345e) | Jan 06, 2024 |
| HP            | ZBook Studio G3             | [21b560e443](https://linux-hardware.org/?probe=21b560e443) | Jan 04, 2024 |
| HP            | ProBook 640 G1              | [a6ba47a6e6](https://linux-hardware.org/?probe=a6ba47a6e6) | Jan 01, 2024 |
| Dell          | Latitude E5470              | [71121b89c8](https://linux-hardware.org/?probe=71121b89c8) | Dec 25, 2023 |
| Acer          | Aspire 7750G                | [cdbe6b267f](https://linux-hardware.org/?probe=cdbe6b267f) | Dec 19, 2023 |
| Acer          | Aspire 7750G                | [6fc9570e4f](https://linux-hardware.org/?probe=6fc9570e4f) | Dec 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | [73c69f2b50](https://linux-hardware.org/?probe=73c69f2b50) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [04ed98dd4a](https://linux-hardware.org/?probe=04ed98dd4a) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| HP            | Pavilion 15                 | [e62aa2185a](https://linux-hardware.org/?probe=e62aa2185a) | Dec 02, 2023 |
| HP            | Pavilion 15                 | [4282694224](https://linux-hardware.org/?probe=4282694224) | Dec 01, 2023 |
| Toshiba       | Satellite Pro L300          | [8cc0e1c14d](https://linux-hardware.org/?probe=8cc0e1c14d) | Nov 09, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | [db3f0ac717](https://linux-hardware.org/?probe=db3f0ac717) | Oct 31, 2023 |
| Thomson       | N14C4WH64                   | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| LG Electro... | R310-K.AP31B                | [ac3922c573](https://linux-hardware.org/?probe=ac3922c573) | Oct 24, 2023 |
| HP            | EliteBook 840 G3            | [a5a8709f77](https://linux-hardware.org/?probe=a5a8709f77) | Oct 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | [e66ff52b09](https://linux-hardware.org/?probe=e66ff52b09) | Oct 13, 2023 |
| Apple         | MacBookAir7,2               | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| HP            | 250 G4                      | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [82b9c0d614](https://linux-hardware.org/?probe=82b9c0d614) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| Acer          | Aspire 5742                 | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0R    | [cb338af601](https://linux-hardware.org/?probe=cb338af601) | Sep 04, 2023 |
| Acer          | Aspire 5742                 | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| Valve         | Jupiter                     | [6df7fe9dca](https://linux-hardware.org/?probe=6df7fe9dca) | Sep 02, 2023 |
| HP            | Bloog                       | [17077dd340](https://linux-hardware.org/?probe=17077dd340) | Aug 26, 2023 |
| Acer          | Nitro AN515-53              | [368352c126](https://linux-hardware.org/?probe=368352c126) | Jul 12, 2023 |
| Dell          | Latitude 5540               | [bdf022bb03](https://linux-hardware.org/?probe=bdf022bb03) | Jul 02, 2023 |
| Dell          | Latitude 5289               | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| Dell          | Latitude E7450              | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| ASUSTek       | UX32LN                      | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HUAWEI        | CREM-WXX9                   | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| Dell          | Latitude E7450              | [14227e270f](https://linux-hardware.org/?probe=14227e270f) | May 19, 2023 |
| HP            | Pavilion g6                 | [21bf9f3d3f](https://linux-hardware.org/?probe=21bf9f3d3f) | May 12, 2023 |
| Dell          | Latitude 5510               | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| HP            | Pavilion g6                 | [3c4ec29c8a](https://linux-hardware.org/?probe=3c4ec29c8a) | May 05, 2023 |
| American M... | XA133PR110                  | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| HP            | EliteBook 830 G5            | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HP            | 15                          | [17b9906d58](https://linux-hardware.org/?probe=17b9906d58) | May 01, 2023 |
| HP            | 15                          | [8fb1f3c8f8](https://linux-hardware.org/?probe=8fb1f3c8f8) | May 01, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| HP            | ProBook 5320m               | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| HP            | Laptop 15-dw2xxx            | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Dell          | Latitude 5400               | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Dell          | Latitude 5400               | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Dell          | Vostro 3500                 | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| HP            | EliteBook 8440p             | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Dell          | Latitude E6520              | [2774f2cb16](https://linux-hardware.org/?probe=2774f2cb16) | Mar 01, 2023 |
| ASUSTek       | X751LK                      | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [39b27e9850](https://linux-hardware.org/?probe=39b27e9850) | Feb 19, 2023 |
| Dell          | Latitude E7450              | [16f40c9f6a](https://linux-hardware.org/?probe=16f40c9f6a) | Feb 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [b82ad16853](https://linux-hardware.org/?probe=b82ad16853) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [76dd43711a](https://linux-hardware.org/?probe=76dd43711a) | Feb 08, 2023 |
| Toshiba       | Satellite C855-1LG          | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Dell          | Latitude 3500               | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| Dell          | Latitude D630               | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [b33f2d5606](https://linux-hardware.org/?probe=b33f2d5606) | Jan 28, 2023 |
| Dell          | Latitude E6410              | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [c5379f6dc1](https://linux-hardware.org/?probe=c5379f6dc1) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [2c092397ea](https://linux-hardware.org/?probe=2c092397ea) | Jan 05, 2023 |
| Dell          | Latitude 5510               | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| SINTRONES     | AMB-5000G1                  | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Dell          | Latitude D820               | [29df917188](https://linux-hardware.org/?probe=29df917188) | Dec 16, 2022 |
| Dell          | Latitude D820               | [27f19eafce](https://linux-hardware.org/?probe=27f19eafce) | Dec 16, 2022 |
| Dell          | Latitude E7250              | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Toshiba       | Satellite L50-B             | [5bbe558b2f](https://linux-hardware.org/?probe=5bbe558b2f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS3YN00    | [636921b46c](https://linux-hardware.org/?probe=636921b46c) | Nov 24, 2022 |
| HP            | 15                          | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | EliteBook 8540w             | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Lenovo        | B50-30 20382                | [c4e67c5f10](https://linux-hardware.org/?probe=c4e67c5f10) | Nov 13, 2022 |
| HP            | 250 G5 Notebook PC          | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| HP            | 15                          | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | Latitude E4310              | [318726cca9](https://linux-hardware.org/?probe=318726cca9) | Oct 14, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| eMachines     | eME528                      | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| Apple         | MacBookPro10,2              | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| HP            | ProBook 650 G1              | [e31d2052e5](https://linux-hardware.org/?probe=e31d2052e5) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | [1bcfb0642f](https://linux-hardware.org/?probe=1bcfb0642f) | Oct 06, 2022 |
| Unknown       | 1.0                         | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| Dell          | Latitude 5490               | [a3f76e546f](https://linux-hardware.org/?probe=a3f76e546f) | Sep 01, 2022 |
| ASUSTek       | K72Jk                       | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| HP            | ProBook 450 G7              | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| Dell          | Latitude E5500              | [5d04270674](https://linux-hardware.org/?probe=5d04270674) | Aug 08, 2022 |
| Acer          | Aspire ES1-523              | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| Dell          | Latitude D620               | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| HP            | Laptop 15-dw3xxx            | [44b541373b](https://linux-hardware.org/?probe=44b541373b) | Jul 08, 2022 |
| Dell          | Latitude E6420              | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| HP            | Presario C500 (GF852EA#A... | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | Pavilion g6                 | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Timi          | TM1701                      | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Acer          | Aspire One 522              | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| ASUSTek       | K72Jr                       | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Apple         | MacBookPro13,3              | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| HP            | Pavilion Power Laptop 15... | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| Razer         | Blade Pro 17 (2019)         | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| HP            | Pavilion Power Laptop 15... | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| HP            | 15                          | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| Unknown       | 1.0                         | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Unknown       | 1.0                         | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| HP            | Notebook                    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| HP            | Pavilion Sleekbook 15       | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Acer          | AO722                       | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| HP            | Pavilion dv7                | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| Dell          | Latitude E6440              | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| HP            | 650                         | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| Dell          | Latitude E6440              | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| Dell          | Latitude E5270              | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| Lenovo        | G50-70 20351                | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 250 G3                      | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Dell          | Inspiron 3521               | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| ASUSTek       | F5VL                        | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 34        | 12.59%  |
| Ubuntu 22.04        | 26        | 9.63%   |
| Ubuntu 18.04        | 13        | 4.81%   |
| KDE neon 20.04      | 10        | 3.7%    |
| OpenMandriva 4.3    | 9         | 3.33%   |
| Fedora 39           | 9         | 3.33%   |
| Debian 11           | 9         | 3.33%   |
| Pop!_OS 22.04       | 7         | 2.59%   |
| Zorin 16            | 6         | 2.22%   |
| OpenMandriva 4.2    | 6         | 2.22%   |
| Linux Mint 20.2     | 6         | 2.22%   |
| OpenMandriva 23.01  | 5         | 1.85%   |
| Fedora 38           | 5         | 1.85%   |
| ArcoLinux Rolling   | 5         | 1.85%   |
| Arch Rolling        | 5         | 1.85%   |
| Zorin 17            | 4         | 1.48%   |
| Xero Rolling        | 4         | 1.48%   |
| Ubuntu Unity 16.04  | 4         | 1.48%   |
| Ubuntu 20.10        | 4         | 1.48%   |
| Ubuntu 19.10        | 4         | 1.48%   |
| Linux Mint 20.3     | 4         | 1.48%   |
| Arch                | 4         | 1.48%   |
| Manjaro             | 3         | 1.11%   |
| Linux Mint 21.3     | 3         | 1.11%   |
| Linux Mint 21.1     | 3         | 1.11%   |
| Xubuntu 20.04       | 2         | 0.74%   |
| Void Linux          | 2         | 0.74%   |
| Ubuntu 23.10        | 2         | 0.74%   |
| Ubuntu 23.04        | 2         | 0.74%   |
| Ubuntu 21.10        | 2         | 0.74%   |
| Ubuntu 21.04        | 2         | 0.74%   |
| Pop!_OS 21.10       | 2         | 0.74%   |
| OpenMandriva 5.0    | 2         | 0.74%   |
| Linux Mint 21       | 2         | 0.74%   |
| Linux Mint 19.3     | 2         | 0.74%   |
| Kali 2023.3         | 2         | 0.74%   |
| Kali 2019.4         | 2         | 0.74%   |
| Fedora 37           | 2         | 0.74%   |
| Fedora 36           | 2         | 0.74%   |
| EndeavourOS Rolling | 2         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 86        | 33.86%  |
| OpenMandriva | 21        | 8.27%   |
| Linux Mint   | 19        | 7.48%   |
| Fedora       | 19        | 7.48%   |
| Zorin        | 11        | 4.33%   |
| Pop!_OS      | 11        | 4.33%   |
| KDE neon     | 11        | 4.33%   |
| Debian       | 11        | 4.33%   |
| Kali         | 9         | 3.54%   |
| Arch         | 8         | 3.15%   |
| Manjaro      | 6         | 2.36%   |
| Ubuntu Unity | 5         | 1.97%   |
| ArcoLinux    | 5         | 1.97%   |
| Xero         | 4         | 1.57%   |
| Endless      | 3         | 1.18%   |
| EndeavourOS  | 3         | 1.18%   |
| Elementary   | 3         | 1.18%   |
| Xubuntu      | 2         | 0.79%   |
| Void Linux   | 2         | 0.79%   |
| Ubuntu MATE  | 2         | 0.79%   |
| SteamOS      | 2         | 0.79%   |
| openSUSE     | 2         | 0.79%   |
| Nobara       | 2         | 0.79%   |
| RHEL         | 1         | 0.39%   |
| Parrot       | 1         | 0.39%   |
| Lubuntu      | 1         | 0.39%   |
| Linux Lite   | 1         | 0.39%   |
| CentOS       | 1         | 0.39%   |
| BunsenLabs   | 1         | 0.39%   |
| blendOS      | 1         | 0.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 9         | 3.15%   |
| 5.10.14-desktop-1omv4002 | 6         | 2.1%    |
| 6.1.1-desktop-1omv2290   | 5         | 1.75%   |
| 5.8.0-43-generic         | 5         | 1.75%   |
| 5.13.0-40-generic        | 5         | 1.75%   |
| 6.2.0-33-generic         | 4         | 1.4%    |
| 5.4.0-58-generic         | 4         | 1.4%    |
| 5.4.0-48-generic         | 4         | 1.4%    |
| 6.8.4-200.fc39.x86_64    | 3         | 1.05%   |
| 6.5.0-26-generic         | 3         | 1.05%   |
| 6.5.0-14-generic         | 3         | 1.05%   |
| 6.2.0-37-generic         | 3         | 1.05%   |
| 5.4.0-42-generic         | 3         | 1.05%   |
| 5.3.0-40-generic         | 3         | 1.05%   |
| 5.17.5-76051705-generic  | 3         | 1.05%   |
| 5.13.0-27-generic        | 3         | 1.05%   |
| 5.11.0-37-generic        | 3         | 1.05%   |
| 6.7.9-200.fc39.x86_64    | 2         | 0.7%    |
| 6.6.2-desktop-1omv2390   | 2         | 0.7%    |
| 6.5.0-21-generic         | 2         | 0.7%    |
| 6.2.6-76060206-generic   | 2         | 0.7%    |
| 6.2.14-300.fc38.x86_64   | 2         | 0.7%    |
| 5.8.0-48-generic         | 2         | 0.7%    |
| 5.8.0-33-generic         | 2         | 0.7%    |
| 5.4.0-96-generic         | 2         | 0.7%    |
| 5.4.0-88-generic         | 2         | 0.7%    |
| 5.4.0-65-generic         | 2         | 0.7%    |
| 5.4.0-37-generic         | 2         | 0.7%    |
| 5.4.0-33-generic         | 2         | 0.7%    |
| 5.4.0-29-generic         | 2         | 0.7%    |
| 5.3.0-kali2-686-pae      | 2         | 0.7%    |
| 5.3.0-51-generic         | 2         | 0.7%    |
| 5.3.0-28-generic         | 2         | 0.7%    |
| 5.19.0-41-generic        | 2         | 0.7%    |
| 5.19.0-38-generic        | 2         | 0.7%    |
| 5.18.19_1                | 2         | 0.7%    |
| 5.15.0-58-generic        | 2         | 0.7%    |
| 5.15.0-53-generic        | 2         | 0.7%    |
| 5.15.0-50-generic        | 2         | 0.7%    |
| 5.15.0-46-generic        | 2         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 12.64%  |
| 5.15.0  | 20        | 7.43%   |
| 5.8.0   | 14        | 5.2%    |
| 6.5.0   | 13        | 4.83%   |
| 5.13.0  | 13        | 4.83%   |
| 5.11.0  | 12        | 4.46%   |
| 4.15.0  | 12        | 4.46%   |
| 6.2.0   | 11        | 4.09%   |
| 5.3.0   | 10        | 3.72%   |
| 5.10.0  | 10        | 3.72%   |
| 5.16.7  | 9         | 3.35%   |
| 5.19.0  | 8         | 2.97%   |
| 5.10.14 | 6         | 2.23%   |
| 5.0.0   | 6         | 2.23%   |
| 6.1.1   | 5         | 1.86%   |
| 6.8.4   | 3         | 1.12%   |
| 6.7.9   | 3         | 1.12%   |
| 6.2.6   | 3         | 1.12%   |
| 5.17.5  | 3         | 1.12%   |
| 4.18.0  | 3         | 1.12%   |
| 6.8.7   | 2         | 0.74%   |
| 6.6.2   | 2         | 0.74%   |
| 6.2.9   | 2         | 0.74%   |
| 6.2.14  | 2         | 0.74%   |
| 6.1.0   | 2         | 0.74%   |
| 5.18.19 | 2         | 0.74%   |
| 5.16.0  | 2         | 0.74%   |
| 5.14.14 | 2         | 0.74%   |
| 4.19.0  | 2         | 0.74%   |
| 6.8.6   | 1         | 0.37%   |
| 6.7.7   | 1         | 0.37%   |
| 6.6.9   | 1         | 0.37%   |
| 6.6.7   | 1         | 0.37%   |
| 6.6.5   | 1         | 0.37%   |
| 6.6.16  | 1         | 0.37%   |
| 6.6.12  | 1         | 0.37%   |
| 6.5.9   | 1         | 0.37%   |
| 6.5.8   | 1         | 0.37%   |
| 6.5.5   | 1         | 0.37%   |
| 6.5.3   | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 12.64%  |
| 5.15    | 26        | 9.67%   |
| 6.2     | 19        | 7.06%   |
| 6.5     | 18        | 6.69%   |
| 5.10    | 17        | 6.32%   |
| 5.8     | 16        | 5.95%   |
| 5.13    | 14        | 5.2%    |
| 5.11    | 14        | 5.2%    |
| 5.16    | 12        | 4.46%   |
| 4.15    | 12        | 4.46%   |
| 5.19    | 11        | 4.09%   |
| 5.3     | 10        | 3.72%   |
| 6.1     | 9         | 3.35%   |
| 6.6     | 7         | 2.6%    |
| 6.8     | 6         | 2.23%   |
| 5.17    | 6         | 2.23%   |
| 5.0     | 6         | 2.23%   |
| 6.3     | 5         | 1.86%   |
| 6.7     | 4         | 1.49%   |
| 6.4     | 4         | 1.49%   |
| 5.18    | 4         | 1.49%   |
| 6.0     | 3         | 1.12%   |
| 5.14    | 3         | 1.12%   |
| 4.18    | 3         | 1.12%   |
| 4.19    | 2         | 0.74%   |
| 5.7     | 1         | 0.37%   |
| 4.4     | 1         | 0.37%   |
| 4.14    | 1         | 0.37%   |
| 4.13    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 241       | 97.18%  |
| i686   | 7         | 2.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 137       | 53.52%  |
| KDE5            | 46        | 17.97%  |
| Unknown         | 15        | 5.86%   |
| XFCE            | 14        | 5.47%   |
| X-Cinnamon      | 14        | 5.47%   |
| KDE             | 6         | 2.34%   |
| Unity           | 5         | 1.95%   |
| Pantheon        | 3         | 1.17%   |
| MATE            | 3         | 1.17%   |
| i3              | 3         | 1.17%   |
| LXQt            | 2         | 0.78%   |
| GNOME Flashback | 2         | 0.78%   |
| Cinnamon        | 2         | 0.78%   |
| xmonad          | 1         | 0.39%   |
| sway            | 1         | 0.39%   |
| Budgie          | 1         | 0.39%   |
| bspwm           | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 179       | 69.65%  |
| Wayland | 69        | 26.85%  |
| Unknown | 7         | 2.72%   |
| Tty     | 2         | 0.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 121       | 46.36%  |
| SDDM    | 44        | 16.86%  |
| GDM3    | 35        | 13.41%  |
| GDM     | 33        | 12.64%  |
| LightDM | 25        | 9.58%   |
| TDM     | 3         | 1.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 147       | 59.04%  |
| fr_FR   | 68        | 27.31%  |
| Unknown | 13        | 5.22%   |
| en_GB   | 9         | 3.61%   |
| de_DE   | 3         | 1.2%    |
| C       | 2         | 0.8%    |
| it_IT   | 1         | 0.4%    |
| fr_MA   | 1         | 0.4%    |
| fr_BE   | 1         | 0.4%    |
| es_ES   | 1         | 0.4%    |
| en_AG   | 1         | 0.4%    |
| ar_MA   | 1         | 0.4%    |
| ar_EG   | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 148       | 59.2%   |
| EFI  | 102       | 40.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 192       | 76.49%  |
| Btrfs   | 25        | 9.96%   |
| Overlay | 22        | 8.76%   |
| Tmpfs   | 8         | 3.19%   |
| Xfs     | 2         | 0.8%    |
| Unknown | 2         | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 121       | 47.83%  |
| GPT     | 87        | 34.39%  |
| MBR     | 45        | 17.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 88%     |
| Yes       | 30        | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 172       | 68.25%  |
| Yes       | 80        | 31.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 80        | 32.26%  |
| Dell                | 43        | 17.34%  |
| Lenovo              | 41        | 16.53%  |
| ASUSTek Computer    | 22        | 8.87%   |
| Acer                | 13        | 5.24%   |
| Toshiba             | 9         | 3.63%   |
| Sony                | 4         | 1.61%   |
| Apple               | 4         | 1.61%   |
| Packard Bell        | 3         | 1.21%   |
| Timi                | 2         | 0.81%   |
| Samsung Electronics | 2         | 0.81%   |
| HUAWEI              | 2         | 0.81%   |
| eMachines           | 2         | 0.81%   |
| Unknown             | 2         | 0.81%   |
| Valve               | 1         | 0.4%    |
| TUXEDO              | 1         | 0.4%    |
| TrekStor            | 1         | 0.4%    |
| Thomson             | 1         | 0.4%    |
| SINTRONES           | 1         | 0.4%    |
| Razer               | 1         | 0.4%    |
| MSI                 | 1         | 0.4%    |
| Medion              | 1         | 0.4%    |
| Mediacom            | 1         | 0.4%    |
| LG Electronics      | 1         | 0.4%    |
| GPD                 | 1         | 0.4%    |
| Google              | 1         | 0.4%    |
| Gigabyte Technology | 1         | 0.4%    |
| Fujitsu Siemens     | 1         | 0.4%    |
| Fujitsu             | 1         | 0.4%    |
| Clevo               | 1         | 0.4%    |
| Casper              | 1         | 0.4%    |
| American Megatrends | 1         | 0.4%    |
| ACCENT              | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP EliteBook 8440p              | 4         | 1.61%   |
| HP Pavilion g6                  | 3         | 1.21%   |
| HP Laptop 15-dw3xxx             | 3         | 1.21%   |
| HP EliteBook 840 G3             | 3         | 1.21%   |
| HP EliteBook 840 G2             | 3         | 1.21%   |
| ASUS X540LA                     | 3         | 1.21%   |
| Unknown                         | 3         | 1.21%   |
| Timi TM1701                     | 2         | 0.81%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 2         | 0.81%   |
| Lenovo IdeaPad L3 15IML05 81Y3  | 2         | 0.81%   |
| HP ZBook 15                     | 2         | 0.81%   |
| HP ProBook 650 G1               | 2         | 0.81%   |
| HP ProBook 6470b                | 2         | 0.81%   |
| HP ProBook 640 G1               | 2         | 0.81%   |
| HP ProBook 450 G0               | 2         | 0.81%   |
| HP Pavilion 15                  | 2         | 0.81%   |
| HP Notebook                     | 2         | 0.81%   |
| HP Laptop 15-ra0xx              | 2         | 0.81%   |
| HP EliteBook 8460p              | 2         | 0.81%   |
| HP EliteBook 830 G5             | 2         | 0.81%   |
| HP 250 G5 Notebook PC           | 2         | 0.81%   |
| Dell Latitude E7450             | 2         | 0.81%   |
| Dell Latitude E6520             | 2         | 0.81%   |
| Dell Latitude E6410             | 2         | 0.81%   |
| ASUS X555LD                     | 2         | 0.81%   |
| Acer Aspire ES1-523             | 2         | 0.81%   |
| Valve Jupiter                   | 1         | 0.4%    |
| TUXEDO N13xWU                   | 1         | 0.4%    |
| TrekStor Surfbook W2            | 1         | 0.4%    |
| Toshiba Satellite Pro L300      | 1         | 0.4%    |
| Toshiba Satellite Pro C650      | 1         | 0.4%    |
| Toshiba Satellite L750          | 1         | 0.4%    |
| Toshiba Satellite L50-B         | 1         | 0.4%    |
| Toshiba Satellite L50-A-1EL     | 1         | 0.4%    |
| Toshiba Satellite L50-A-1DG     | 1         | 0.4%    |
| Toshiba Satellite C855-2CF      | 1         | 0.4%    |
| Toshiba Satellite C855-1LG      | 1         | 0.4%    |
| Toshiba Satellite C660          | 1         | 0.4%    |
| Thomson N14C4WH64               | 1         | 0.4%    |
| Sony VPCF12A4E                  | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 35        | 14.11%  |
| Lenovo ThinkPad       | 26        | 10.48%  |
| HP EliteBook          | 22        | 8.87%   |
| HP ProBook            | 14        | 5.65%   |
| HP Pavilion           | 11        | 4.44%   |
| HP Laptop             | 10        | 4.03%   |
| Toshiba Satellite     | 9         | 3.63%   |
| Acer Aspire           | 8         | 3.23%   |
| Lenovo IdeaPad        | 6         | 2.42%   |
| HP ZBook              | 5         | 2.02%   |
| HP 250                | 5         | 2.02%   |
| Packard Bell EasyNote | 3         | 1.21%   |
| Lenovo ThinkBook      | 3         | 1.21%   |
| Dell Inspiron         | 3         | 1.21%   |
| ASUS Zenbook          | 3         | 1.21%   |
| ASUS X540LA           | 3         | 1.21%   |
| Unknown               | 3         | 1.21%   |
| Timi TM1701           | 2         | 0.81%   |
| HP Notebook           | 2         | 0.81%   |
| HP Compaq             | 2         | 0.81%   |
| Dell Vostro           | 2         | 0.81%   |
| Dell Precision        | 2         | 0.81%   |
| ASUS X555LD           | 2         | 0.81%   |
| Acer Nitro            | 2         | 0.81%   |
| Valve Jupiter         | 1         | 0.4%    |
| TUXEDO N13xWU         | 1         | 0.4%    |
| TrekStor Surfbook     | 1         | 0.4%    |
| Thomson N14C4WH64     | 1         | 0.4%    |
| Sony VPCF12A4E        | 1         | 0.4%    |
| Sony VPCEH1L8E        | 1         | 0.4%    |
| Sony VGN-FW11L        | 1         | 0.4%    |
| Sony SVE14122CAW      | 1         | 0.4%    |
| SINTRONES AMB-5000G1  | 1         | 0.4%    |
| Samsung 355V4C        | 1         | 0.4%    |
| Samsung 300E4A        | 1         | 0.4%    |
| Razer Blade           | 1         | 0.4%    |
| MSI GS66              | 1         | 0.4%    |
| Medion P7615          | 1         | 0.4%    |
| Mediacom WinPad       | 1         | 0.4%    |
| LG R310-K.AP31B       | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 26        | 10.48%  |
| 2018 | 25        | 10.08%  |
| 2011 | 23        | 9.27%   |
| 2010 | 23        | 9.27%   |
| 2016 | 22        | 8.87%   |
| 2014 | 21        | 8.47%   |
| 2020 | 19        | 7.66%   |
| 2015 | 18        | 7.26%   |
| 2017 | 13        | 5.24%   |
| 2012 | 12        | 4.84%   |
| 2019 | 11        | 4.44%   |
| 2021 | 10        | 4.03%   |
| 2009 | 6         | 2.42%   |
| 2008 | 6         | 2.42%   |
| 2022 | 4         | 1.61%   |
| 2007 | 4         | 1.61%   |
| 2023 | 2         | 0.81%   |
| 2006 | 2         | 0.81%   |
| 2005 | 1         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 248       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 235       | 93.63%  |
| Enabled  | 16        | 6.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 246       | 99.19%  |
| Yes  | 2         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 92        | 36.65%  |
| 3.01-4.0   | 64        | 25.5%   |
| 8.01-16.0  | 33        | 13.15%  |
| 16.01-24.0 | 29        | 11.55%  |
| 1.01-2.0   | 14        | 5.58%   |
| 32.01-64.0 | 8         | 3.19%   |
| 2.01-3.0   | 5         | 1.99%   |
| 24.01-32.0 | 4         | 1.59%   |
| 0.51-1.0   | 2         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 95        | 34.93%  |
| 2.01-3.0  | 88        | 32.35%  |
| 4.01-8.0  | 41        | 15.07%  |
| 3.01-4.0  | 31        | 11.4%   |
| 0.51-1.0  | 12        | 4.41%   |
| 8.01-16.0 | 4         | 1.47%   |
| 0.01-0.5  | 1         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 207       | 82.8%   |
| 2      | 38        | 15.2%   |
| 3      | 4         | 1.6%    |
| 4      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 139       | 56.05%  |
| Yes       | 109       | 43.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 87.1%   |
| No        | 32        | 12.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 98.8%   |
| No        | 3         | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 72.62%  |
| No        | 69        | 27.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 248       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Casablanca       | 62        | 22.96%  |
| Marrakesh        | 27        | 10%     |
| Rabat            | 24        | 8.89%   |
| Agadir           | 19        | 7.04%   |
| Fes              | 18        | 6.67%   |
| Kenitra          | 15        | 5.56%   |
| Tangier          | 14        | 5.19%   |
| Oujda            | 13        | 4.81%   |
| Salé            | 12        | 4.44%   |
| Meknes           | 9         | 3.33%   |
| Khouribga        | 7         | 2.59%   |
| Nador            | 5         | 1.85%   |
| Tiznit           | 3         | 1.11%   |
| Guelmim          | 3         | 1.11%   |
| El Jadida        | 3         | 1.11%   |
| Beni Mellal      | 3         | 1.11%   |
| Temara           | 2         | 0.74%   |
| Taza             | 2         | 0.74%   |
| Safi             | 2         | 0.74%   |
| Youssoufia       | 1         | 0.37%   |
| Tit Mellil       | 1         | 0.37%   |
| Tétouan         | 1         | 0.37%   |
| Targuist         | 1         | 0.37%   |
| Taourirt         | 1         | 0.37%   |
| Skhirate         | 1         | 0.37%   |
| Sidi Slimane     | 1         | 0.37%   |
| Sidi Kacem       | 1         | 0.37%   |
| Settat           | 1         | 0.37%   |
| Sefrou           | 1         | 0.37%   |
| Oued Zem         | 1         | 0.37%   |
| Mohammedia       | 1         | 0.37%   |
| Midelt           | 1         | 0.37%   |
| Martil           | 1         | 0.37%   |
| Ksar El Kebir    | 1         | 0.37%   |
| Khemisset        | 1         | 0.37%   |
| Karia Ba Mohamed | 1         | 0.37%   |
| Inezgane         | 1         | 0.37%   |
| Imouzzer Kandar  | 1         | 0.37%   |
| Errachidia       | 1         | 0.37%   |
| Berrechid        | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 41        | 51     | 14.34%  |
| Toshiba                     | 39        | 49     | 13.64%  |
| Samsung Electronics         | 38        | 46     | 13.29%  |
| WDC                         | 35        | 45     | 12.24%  |
| Unknown                     | 16        | 22     | 5.59%   |
| SanDisk                     | 11        | 13     | 3.85%   |
| Hitachi                     | 11        | 12     | 3.85%   |
| HGST                        | 9         | 10     | 3.15%   |
| SK hynix                    | 8         | 8      | 2.8%    |
| Micron Technology           | 8         | 10     | 2.8%    |
| Intel                       | 8         | 9      | 2.8%    |
| Kingston                    | 6         | 7      | 2.1%    |
| Apple                       | 6         | 6      | 2.1%    |
| LITEON                      | 4         | 4      | 1.4%    |
| KIOXIA                      | 4         | 4      | 1.4%    |
| China                       | 4         | 5      | 1.4%    |
| PNY                         | 3         | 4      | 1.05%   |
| LITEONIT                    | 2         | 2      | 0.7%    |
| Kingston Technology Company | 2         | 2      | 0.7%    |
| KingDian                    | 2         | 7      | 0.7%    |
| GOODRAM                     | 2         | 2      | 0.7%    |
| Fujitsu                     | 2         | 2      | 0.7%    |
| Crucial                     | 2         | 2      | 0.7%    |
| Unknown                     | 2         | 2      | 0.7%    |
| TwinMOS                     | 1         | 1      | 0.35%   |
| Transcend                   | 1         | 1      | 0.35%   |
| Team                        | 1         | 1      | 0.35%   |
| Supersonic                  | 1         | 1      | 0.35%   |
| ShiJi                       | 1         | 2      | 0.35%   |
| SG                          | 1         | 1      | 0.35%   |
| RCESSD                      | 1         | 1      | 0.35%   |
| Phison                      | 1         | 1      | 0.35%   |
| O2 Micro                    | 1         | 1      | 0.35%   |
| MSI                         | 1         | 1      | 0.35%   |
| KingSpec                    | 1         | 1      | 0.35%   |
| KingFast                    | 1         | 2      | 0.35%   |
| Intenso                     | 1         | 2      | 0.35%   |
| Indilinx                    | 1         | 1      | 0.35%   |
| IBM/Hitachi                 | 1         | 1      | 0.35%   |
| Hewlett-Packard             | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                             | 5         | 1.69%   |
| Toshiba MQ01ABF050 500GB                           | 5         | 1.69%   |
| Seagate ST500LT012-1DG142 500GB                    | 5         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB                     | 5         | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 5         | 1.69%   |
| Toshiba MQ01ABD050 500GB                           | 4         | 1.35%   |
| Samsung NVMe SSD Drive 512GB                       | 4         | 1.35%   |
| HGST HTS545050A7E680 500GB                         | 4         | 1.35%   |
| Unknown MMC Card  64GB                             | 3         | 1.01%   |
| Unknown MMC Card  32GB                             | 3         | 1.01%   |
| Toshiba MQ01ACF050 500GB                           | 3         | 1.01%   |
| Toshiba MQ01ABD100 1TB                             | 3         | 1.01%   |
| Seagate ST9500325AS 500GB                          | 3         | 1.01%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 3         | 1.01%   |
| WDC WD5000LPCX-80VHAT1 500GB                       | 2         | 0.68%   |
| WDC WD5000LPCX-60VHAT0 500GB                       | 2         | 0.68%   |
| WDC WD1600BEVT-22ZCT0 160GB                        | 2         | 0.68%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 2         | 0.68%   |
| WDC WD10JPVX-60JC3T0 1TB                           | 2         | 0.68%   |
| Unknown MMC Card  16GB                             | 2         | 0.68%   |
| Toshiba KXG50ZNV256G 256GB                         | 2         | 0.68%   |
| Seagate ST9500423AS 500GB                          | 2         | 0.68%   |
| Seagate ST500VT000-1DK142 500GB                    | 2         | 0.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 2         | 0.68%   |
| Seagate ST500LM000-1EJ162 500GB                    | 2         | 0.68%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 0.68%   |
| Samsung MZVLW256HEHP-000L7 256GB                   | 2         | 0.68%   |
| Samsung MZVLB256HAHQ-000H1 256GB                   | 2         | 0.68%   |
| Hitachi HTS723232A7A364 320GB                      | 2         | 0.68%   |
| Hitachi HTS542525K9A300 250GB                      | 2         | 0.68%   |
| Hitachi HTS541616J9SA00 160GB                      | 2         | 0.68%   |
| HGST HTS725050A7E630 500GB                         | 2         | 0.68%   |
| China SSD 256GB                                    | 2         | 0.68%   |
| Unknown                                            | 2         | 0.68%   |
| WDC WDS256G1X0C-00ENX0 256GB                       | 1         | 0.34%   |
| WDC WD5000M21K-60JU6T0 500GB                       | 1         | 0.34%   |
| WDC WD5000LPCX-60VHAT1 500GB                       | 1         | 0.34%   |
| WDC WD5000BPVT-22HXZT1 500GB                       | 1         | 0.34%   |
| WDC WD3200BUCT-63TWBY0 320GB                       | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 51     | 31.78%  |
| Toshiba             | 31        | 36     | 24.03%  |
| WDC                 | 30        | 40     | 23.26%  |
| Hitachi             | 11        | 12     | 8.53%   |
| HGST                | 9         | 10     | 6.98%   |
| Samsung Electronics | 2         | 2      | 1.55%   |
| Fujitsu             | 2         | 2      | 1.55%   |
| Apple               | 2         | 2      | 1.55%   |
| IBM/Hitachi         | 1         | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 15.19%  |
| SanDisk             | 8         | 9      | 10.13%  |
| Micron Technology   | 6         | 8      | 7.59%   |
| Kingston            | 5         | 6      | 6.33%   |
| LITEON              | 4         | 4      | 5.06%   |
| China               | 4         | 5      | 5.06%   |
| Toshiba             | 3         | 3      | 3.8%    |
| SK hynix            | 3         | 3      | 3.8%    |
| PNY                 | 3         | 4      | 3.8%    |
| Intel               | 3         | 4      | 3.8%    |
| Apple               | 3         | 3      | 3.8%    |
| LITEONIT            | 2         | 2      | 2.53%   |
| KingDian            | 2         | 7      | 2.53%   |
| GOODRAM             | 2         | 2      | 2.53%   |
| Crucial             | 2         | 2      | 2.53%   |
| Unknown             | 2         | 2      | 2.53%   |
| TwinMOS             | 1         | 1      | 1.27%   |
| Transcend           | 1         | 1      | 1.27%   |
| Team                | 1         | 1      | 1.27%   |
| Supersonic          | 1         | 1      | 1.27%   |
| RCESSD              | 1         | 1      | 1.27%   |
| MSI                 | 1         | 1      | 1.27%   |
| KingSpec            | 1         | 1      | 1.27%   |
| KingFast            | 1         | 1      | 1.27%   |
| Indilinx            | 1         | 1      | 1.27%   |
| Hewlett-Packard     | 1         | 1      | 1.27%   |
| BIWIN               | 1         | 1      | 1.27%   |
| Bestoss             | 1         | 1      | 1.27%   |
| Apacer              | 1         | 1      | 1.27%   |
| A-DATA Technology   | 1         | 1      | 1.27%   |
| 2.5"                | 1         | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 127       | 156    | 46.01%  |
| SSD     | 77        | 95     | 27.9%   |
| NVMe    | 53        | 68     | 19.2%   |
| MMC     | 16        | 22     | 5.8%    |
| Unknown | 3         | 7      | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 193       | 255    | 73.11%  |
| NVMe | 53        | 68     | 20.08%  |
| MMC  | 16        | 22     | 6.06%   |
| SAS  | 2         | 3      | 0.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 152       | 188    | 76%     |
| 0.51-1.0   | 46        | 61     | 23%     |
| 1.01-2.0   | 2         | 2      | 1%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 78        | 30.35%  |
| 251-500        | 68        | 26.46%  |
| 51-100         | 30        | 11.67%  |
| 501-1000       | 27        | 10.51%  |
| 1-20           | 22        | 8.56%   |
| 21-50          | 17        | 6.61%   |
| 1001-2000      | 9         | 3.5%    |
| Unknown        | 3         | 1.17%   |
| More than 3000 | 2         | 0.78%   |
| 2001-3000      | 1         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 109       | 40.22%  |
| 21-50          | 70        | 25.83%  |
| 101-250        | 36        | 13.28%  |
| 51-100         | 36        | 13.28%  |
| 251-500        | 10        | 3.69%   |
| 501-1000       | 4         | 1.48%   |
| Unknown        | 3         | 1.11%   |
| More than 3000 | 2         | 0.74%   |
| 1001-2000      | 1         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB                         | 3         | 3      | 8.82%   |
| Seagate ST9500325AS 500GB                        | 3         | 4      | 8.82%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 5.88%   |
| HGST HTS545050A7E680 500GB                       | 2         | 3      | 5.88%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 2.94%   |
| WDC WD2500BEVS-22UST0 250GB                      | 1         | 1      | 2.94%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 2.94%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 6      | 2.94%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.94%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 2.94%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 2.94%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 2.94%   |
| Seagate ST9500423AS 500GB                        | 1         | 1      | 2.94%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 2.94%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.94%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 2.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.94%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 2.94%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 2.94%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.94%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 2.94%   |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 2.94%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 2.94%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 2.94%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 2.94%   |
| Apple HDD HTS541010A9E662 1TB                    | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 26.47%  |
| Toshiba             | 8         | 8      | 23.53%  |
| WDC                 | 4         | 9      | 11.76%  |
| Hitachi             | 4         | 5      | 11.76%  |
| HGST                | 3         | 4      | 8.82%   |
| SanDisk             | 1         | 1      | 2.94%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Fujitsu             | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 30%     |
| Toshiba | 8         | 8      | 26.67%  |
| WDC     | 4         | 9      | 13.33%  |
| Hitachi | 4         | 5      | 13.33%  |
| HGST    | 3         | 4      | 10%     |
| Fujitsu | 1         | 1      | 3.33%   |
| Apple   | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 38     | 88.24%  |
| SSD  | 4         | 4      | 11.76%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22A23T0 250GB               | 1         | 2      | 50%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 147       | 203    | 55.47%  |
| Works    | 82        | 100    | 30.94%  |
| Malfunc  | 34        | 42     | 12.83%  |
| Failed   | 2         | 3      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 203       | 74.63%  |
| Samsung Electronics              | 26        | 9.56%   |
| AMD                              | 14        | 5.15%   |
| SanDisk                          | 6         | 2.21%   |
| Toshiba America Info Systems     | 5         | 1.84%   |
| SK hynix                         | 5         | 1.84%   |
| KIOXIA                           | 4         | 1.47%   |
| Kingston Technology Company      | 3         | 1.1%    |
| Micron Technology                | 2         | 0.74%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Phison Electronics               | 1         | 0.37%   |
| O2 Micro                         | 1         | 0.37%   |
| Nvidia                           | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 26        | 8.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 24        | 8.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 21        | 7.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 15        | 5.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 4.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 4.48%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 3.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 3.79%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 3.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 3.1%    |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 2.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 2.07%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 2.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.69%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 0.69%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.69%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 2         | 0.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.69%   |
| Intel SSD 660P Series                                                            | 2         | 0.69%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.69%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 1         | 0.34%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 180       | 63.83%  |
| NVMe | 53        | 18.79%  |
| RAID | 40        | 14.18%  |
| IDE  | 9         | 3.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 229       | 92.34%  |
| AMD    | 19        | 7.66%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 8         | 3.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 2.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 7         | 2.82%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 6         | 2.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 2.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 2.42%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 5         | 2.02%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 5         | 2.02%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 5         | 2.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 2.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.61%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 4         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.61%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 1.21%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.21%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.21%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.21%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 3         | 1.21%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 1.21%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.21%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.21%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.81%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 2         | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.81%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.81%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.81%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.81%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.81%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.81%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.81%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.81%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 2         | 0.81%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 2         | 0.81%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 98        | 39.52%  |
| Intel Core i7           | 45        | 18.15%  |
| Intel Core i3           | 30        | 12.1%   |
| Other                   | 17        | 6.85%   |
| Intel Core 2 Duo        | 13        | 5.24%   |
| Intel Celeron           | 12        | 4.84%   |
| Intel Atom              | 6         | 2.42%   |
| AMD Ryzen 7             | 3         | 1.21%   |
| AMD Ryzen 5             | 3         | 1.21%   |
| AMD E1                  | 3         | 1.21%   |
| Intel Pentium Dual-Core | 2         | 0.81%   |
| AMD C-60                | 2         | 0.81%   |
| AMD A8                  | 2         | 0.81%   |
| AMD A6                  | 2         | 0.81%   |
| Intel Pentium Silver    | 1         | 0.4%    |
| Intel Pentium M         | 1         | 0.4%    |
| Intel Pentium Gold      | 1         | 0.4%    |
| Intel Pentium           | 1         | 0.4%    |
| Intel Genuine           | 1         | 0.4%    |
| Intel Core 2            | 1         | 0.4%    |
| Intel Celeron M         | 1         | 0.4%    |
| AMD Ryzen 9             | 1         | 0.4%    |
| AMD Ryzen 7 PRO         | 1         | 0.4%    |
| AMD A4                  | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 159       | 64.11%  |
| 4      | 67        | 27.02%  |
| 6      | 7         | 2.82%   |
| 8      | 6         | 2.42%   |
| 1      | 5         | 2.02%   |
| 10     | 2         | 0.81%   |
| 14     | 1         | 0.4%    |
| 12     | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 248       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 196       | 79.03%  |
| 1      | 52        | 20.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 243       | 97.98%  |
| 32-bit         | 3         | 1.21%   |
| Unknown        | 2         | 0.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 36.05%  |
| 0x206a7    | 18        | 6.98%   |
| 0x306d4    | 14        | 5.43%   |
| 0x806ea    | 12        | 4.65%   |
| 0x40651    | 12        | 4.65%   |
| 0x806ec    | 9         | 3.49%   |
| 0x306c3    | 9         | 3.49%   |
| 0x20655    | 9         | 3.49%   |
| 0x306a9    | 8         | 3.1%    |
| 0x806c1    | 7         | 2.71%   |
| 0x406e3    | 6         | 2.33%   |
| 0x1067a    | 6         | 2.33%   |
| 0x806e9    | 5         | 1.94%   |
| 0x20652    | 5         | 1.94%   |
| 0x6fd      | 4         | 1.55%   |
| 0x506e3    | 4         | 1.55%   |
| 0x30678    | 4         | 1.55%   |
| 0x0a50000c | 3         | 1.16%   |
| 0x906ea    | 2         | 0.78%   |
| 0x406c4    | 2         | 0.78%   |
| 0x406c3    | 2         | 0.78%   |
| 0x10676    | 2         | 0.78%   |
| 0x07030105 | 2         | 0.78%   |
| 0x0700010f | 2         | 0.78%   |
| 0xb06a3    | 1         | 0.39%   |
| 0x906e9    | 1         | 0.39%   |
| 0x806eb    | 1         | 0.39%   |
| 0x806d1    | 1         | 0.39%   |
| 0x706e5    | 1         | 0.39%   |
| 0x706a1    | 1         | 0.39%   |
| 0x6ec      | 1         | 0.39%   |
| 0x6e8      | 1         | 0.39%   |
| 0x6d8      | 1         | 0.39%   |
| 0x30673    | 1         | 0.39%   |
| 0x30661    | 1         | 0.39%   |
| 0x08108109 | 1         | 0.39%   |
| 0x08108102 | 1         | 0.39%   |
| 0x06006705 | 1         | 0.39%   |
| 0x06001119 | 1         | 0.39%   |
| 0x05000119 | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 16.94%  |
| Haswell          | 35        | 14.11%  |
| SandyBridge      | 22        | 8.87%   |
| Skylake          | 21        | 8.47%   |
| Westmere         | 20        | 8.06%   |
| Broadwell        | 18        | 7.26%   |
| Silvermont       | 12        | 4.84%   |
| IvyBridge        | 12        | 4.84%   |
| TigerLake        | 11        | 4.44%   |
| Penryn           | 11        | 4.44%   |
| Core             | 6         | 2.42%   |
| Unknown          | 6         | 2.42%   |
| IceLake          | 4         | 1.61%   |
| Zen+             | 3         | 1.21%   |
| Zen 3            | 3         | 1.21%   |
| P6               | 3         | 1.21%   |
| Bobcat           | 3         | 1.21%   |
| Puma             | 2         | 0.81%   |
| Jaguar           | 2         | 0.81%   |
| Goldmont plus    | 2         | 0.81%   |
| CometLake        | 2         | 0.81%   |
| Bonnell          | 2         | 0.81%   |
| Alderlake Hybrid | 2         | 0.81%   |
| Piledriver       | 1         | 0.4%    |
| K10 Llano        | 1         | 0.4%    |
| Goldmont         | 1         | 0.4%    |
| Excavator        | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 211       | 68.06%  |
| Nvidia | 64        | 20.65%  |
| AMD    | 35        | 11.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 7.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 6.37%   |
| Intel UHD Graphics 620                                                                   | 17        | 5.41%   |
| Intel HD Graphics 5500                                                                   | 17        | 5.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 4.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 4.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 3.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 3.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.87%   |
| Intel HD Graphics 620                                                                    | 8         | 2.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.91%   |
| Intel HD Graphics 530                                                                    | 6         | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.91%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.27%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.96%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.96%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.96%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.64%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.64%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 2         | 0.64%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.64%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.64%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.64%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.64%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 150       | 60.24%  |
| Intel + Nvidia | 52        | 20.88%  |
| 1 x AMD        | 25        | 10.04%  |
| 1 x Nvidia     | 11        | 4.42%   |
| Intel + AMD    | 8         | 3.21%   |
| AMD + Nvidia   | 2         | 0.8%    |
| 2 x Intel      | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 215       | 84.65%  |
| Proprietary | 28        | 11.02%  |
| Unknown     | 11        | 4.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 187       | 73.33%  |
| 1.01-2.0   | 29        | 11.37%  |
| 0.01-0.5   | 22        | 8.63%   |
| 3.01-4.0   | 9         | 3.53%   |
| 0.51-1.0   | 6         | 2.35%   |
| 7.01-8.0   | 1         | 0.39%   |
| 2.01-3.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 47        | 18.73%  |
| Chimei Innolux          | 45        | 17.93%  |
| AU Optronics            | 43        | 17.13%  |
| Samsung Electronics     | 35        | 13.94%  |
| BOE                     | 35        | 13.94%  |
| Lenovo                  | 6         | 2.39%   |
| InfoVision              | 6         | 2.39%   |
| LG Philips              | 4         | 1.59%   |
| Hewlett-Packard         | 4         | 1.59%   |
| Dell                    | 4         | 1.59%   |
| Chi Mei Optoelectronics | 4         | 1.59%   |
| Apple                   | 4         | 1.59%   |
| Sharp                   | 3         | 1.2%    |
| Valve                   | 1         | 0.4%    |
| TMX                     | 1         | 0.4%    |
| Sony                    | 1         | 0.4%    |
| PANDA                   | 1         | 0.4%    |
| NCS                     | 1         | 0.4%    |
| MSI                     | 1         | 0.4%    |
| LGD                     | 1         | 0.4%    |
| IBM                     | 1         | 0.4%    |
| HannStar                | 1         | 0.4%    |
| Goldstar                | 1         | 0.4%    |
| CNC                     | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 1.58%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 1.58%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 3         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 1.19%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.79%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.79%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.79%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 2         | 0.79%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.79%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 2         | 0.79%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 2         | 0.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.79%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.79%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 2         | 0.79%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch            | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.79%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.4%    |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.4%    |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.4%    |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.4%    |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.4%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch     | 1         | 0.4%    |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch        | 1         | 0.4%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 114       | 46.53%  |
| 1920x1080 (FHD)    | 73        | 29.8%   |
| 1600x900 (HD+)     | 19        | 7.76%   |
| 1280x800 (WXGA)    | 8         | 3.27%   |
| 1440x900 (WXGA+)   | 5         | 2.04%   |
| 1680x1050 (WSXGA+) | 4         | 1.63%   |
| 2560x1440 (QHD)    | 3         | 1.22%   |
| 1024x600           | 3         | 1.22%   |
| 3840x2160 (4K)     | 2         | 0.82%   |
| 2880x1800          | 2         | 0.82%   |
| 800x1280           | 1         | 0.41%   |
| 3840x2400          | 1         | 0.41%   |
| 2560x1600          | 1         | 0.41%   |
| 2520x1680          | 1         | 0.41%   |
| 2240x1400          | 1         | 0.41%   |
| 1920x515           | 1         | 0.41%   |
| 1920x1200 (WUXGA)  | 1         | 0.41%   |
| 1680x945           | 1         | 0.41%   |
| 1400x1050          | 1         | 0.41%   |
| 1360x768           | 1         | 0.41%   |
| 1280x1024 (SXGA)   | 1         | 0.41%   |
| 1024x768 (XGA)     | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 128       | 50.59%  |
| 14      | 34        | 13.44%  |
| 13      | 34        | 13.44%  |
| 12      | 14        | 5.53%   |
| 17      | 11        | 4.35%   |
| 18      | 6         | 2.37%   |
| 23      | 4         | 1.58%   |
| 11      | 4         | 1.58%   |
| 24      | 3         | 1.19%   |
| 22      | 3         | 1.19%   |
| 10      | 2         | 0.79%   |
| Unknown | 2         | 0.79%   |
| 84      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 31      | 1         | 0.4%    |
| 27      | 1         | 0.4%    |
| 21      | 1         | 0.4%    |
| 19      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |
| 7       | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 178       | 70.36%  |
| 201-300     | 35        | 13.83%  |
| 351-400     | 17        | 6.72%   |
| 401-500     | 9         | 3.56%   |
| 501-600     | 8         | 3.16%   |
| Unknown     | 2         | 0.79%   |
| 701-800     | 1         | 0.4%    |
| 601-700     | 1         | 0.4%    |
| 1501-2000   | 1         | 0.4%    |
| 1-100       | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 211       | 86.48%  |
| 16/10   | 24        | 9.84%   |
| 4/3     | 3         | 1.23%   |
| 3/2     | 2         | 0.82%   |
| 5/4     | 1         | 0.41%   |
| 3.73    | 1         | 0.41%   |
| 0.67    | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 127       | 50.2%   |
| 81-90          | 55        | 21.74%  |
| 61-70          | 13        | 5.14%   |
| 71-80          | 12        | 4.74%   |
| 121-130        | 9         | 3.56%   |
| 201-250        | 8         | 3.16%   |
| 141-150        | 5         | 1.98%   |
| 51-60          | 4         | 1.58%   |
| 151-200        | 3         | 1.19%   |
| 351-500        | 2         | 0.79%   |
| 41-50          | 2         | 0.79%   |
| 251-300        | 2         | 0.79%   |
| 131-140        | 2         | 0.79%   |
| 111-120        | 2         | 0.79%   |
| 91-100         | 2         | 0.79%   |
| Unknown        | 2         | 0.79%   |
| More than 1000 | 1         | 0.4%    |
| 1-40           | 1         | 0.4%    |
| 301-350        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 110       | 43.65%  |
| 121-160       | 85        | 33.73%  |
| 51-100        | 32        | 12.7%   |
| 161-240       | 20        | 7.94%   |
| More than 240 | 2         | 0.79%   |
| Unknown       | 2         | 0.79%   |
| 1-50          | 1         | 0.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 227       | 90.08%  |
| 2     | 19        | 7.54%   |
| 0     | 6         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 136       | 35.32%  |
| Realtek Semiconductor    | 109       | 28.31%  |
| Qualcomm Atheros         | 53        | 13.77%  |
| Broadcom                 | 39        | 10.13%  |
| Ralink Technology        | 12        | 3.12%   |
| Ralink                   | 6         | 1.56%   |
| Dell                     | 5         | 1.3%    |
| Sierra Wireless          | 4         | 1.04%   |
| Broadcom Limited         | 4         | 1.04%   |
| Xiaomi                   | 3         | 0.78%   |
| Samsung Electronics      | 2         | 0.52%   |
| MediaTek                 | 2         | 0.52%   |
| Marvell Technology Group | 2         | 0.52%   |
| Lenovo                   | 2         | 0.52%   |
| TP-Link                  | 1         | 0.26%   |
| Qualcomm                 | 1         | 0.26%   |
| Nvidia                   | 1         | 0.26%   |
| JMicron Technology       | 1         | 0.26%   |
| Huawei Technologies      | 1         | 0.26%   |
| Arduino SA               | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 66        | 13.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 25        | 5.07%   |
| Intel Wireless 8265 / 8275                                             | 18        | 3.65%   |
| Intel Wireless 8260                                                    | 15        | 3.04%   |
| Intel Wireless 7265                                                    | 13        | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 12        | 2.43%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 2.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 2.03%   |
| Ralink MT7601U Wireless Adapter                                        | 10        | 2.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.83%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 1.83%   |
| Intel Centrino Advanced-N 6200                                         | 9         | 1.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 8         | 1.62%   |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.42%   |
| Intel Wireless 7260                                                    | 7         | 1.42%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 1.42%   |
| Intel Ethernet Connection I218-LM                                      | 7         | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 7         | 1.42%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 6         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 1.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.01%   |
| Intel Centrino Advanced-N 6235                                         | 5         | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.81%   |
| Intel WiFi Link 5100                                                   | 4         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 0.81%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.61%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 124       | 46.97%  |
| Qualcomm Atheros      | 48        | 18.18%  |
| Realtek Semiconductor | 30        | 11.36%  |
| Broadcom              | 29        | 10.98%  |
| Ralink Technology     | 12        | 4.55%   |
| Ralink                | 6         | 2.27%   |
| Sierra Wireless       | 4         | 1.52%   |
| Dell                  | 4         | 1.52%   |
| Broadcom Limited      | 4         | 1.52%   |
| MediaTek              | 2         | 0.76%   |
| TP-Link               | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 18        | 6.79%   |
| Intel Wireless 8260                                            | 15        | 5.66%   |
| Intel Wireless 7265                                            | 13        | 4.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 4.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.77%   |
| Ralink MT7601U Wireless Adapter                                | 10        | 3.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 3.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 3.4%    |
| Intel Centrino Advanced-N 6200                                 | 9         | 3.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 3.02%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 3.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.64%   |
| Intel Wireless 7260                                            | 7         | 2.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 2.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.26%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.89%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.89%   |
| Intel WiFi Link 5100                                           | 4         | 1.51%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.51%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.13%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.13%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 3         | 1.13%   |
| Sierra Wireless EM7455                                         | 2         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.75%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.75%   |
| Intel Wireless 3165                                            | 2         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.75%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 98        | 43.75%  |
| Intel                    | 88        | 39.29%  |
| Broadcom                 | 13        | 5.8%    |
| Qualcomm Atheros         | 12        | 5.36%   |
| Xiaomi                   | 3         | 1.34%   |
| Samsung Electronics      | 2         | 0.89%   |
| Marvell Technology Group | 2         | 0.89%   |
| Lenovo                   | 2         | 0.89%   |
| Qualcomm                 | 1         | 0.45%   |
| Nvidia                   | 1         | 0.45%   |
| JMicron Technology       | 1         | 0.45%   |
| Huawei Technologies      | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 66        | 29.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 25        | 11.11%  |
| Intel 82577LM Gigabit Network Connection                               | 12        | 5.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 4.89%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 4.44%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 4%      |
| Intel Ethernet Connection I219-LM                                      | 7         | 3.11%   |
| Intel Ethernet Connection I218-LM                                      | 7         | 3.11%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 2.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 2.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 1.78%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 1.33%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.89%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.89%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.89%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.44%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.44%   |
| Qualcomm Nokia G42 5G                                                  | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.44%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.44%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.44%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                    | 1         | 0.44%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.44%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 246       | 53.02%  |
| Ethernet | 215       | 46.34%  |
| Modem    | 3         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 213       | 84.86%  |
| Ethernet | 38        | 15.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 208       | 83.53%  |
| 1     | 34        | 13.65%  |
| 0     | 5         | 2.01%   |
| 7     | 1         | 0.4%    |
| 3     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 248       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 45.9%   |
| Realtek Semiconductor           | 20        | 10.93%  |
| Qualcomm Atheros Communications | 19        | 10.38%  |
| Broadcom                        | 14        | 7.65%   |
| IMC Networks                    | 9         | 4.92%   |
| Dell                            | 7         | 3.83%   |
| Lite-On Technology              | 6         | 3.28%   |
| Hewlett-Packard                 | 6         | 3.28%   |
| Ralink                          | 5         | 2.73%   |
| Foxconn / Hon Hai               | 4         | 2.19%   |
| Apple                           | 3         | 1.64%   |
| Toshiba                         | 1         | 0.55%   |
| Ralink Technology               | 1         | 0.55%   |
| Foxconn International           | 1         | 0.55%   |
| Cambridge Silicon Radio         | 1         | 0.55%   |
| ASUSTek Computer                | 1         | 0.55%   |
| Alps Electric                   | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 29        | 15.85%  |
| Intel Bluetooth wireless interface                                                  | 20        | 10.93%  |
| Intel AX201 Bluetooth                                                               | 11        | 6.01%   |
| Realtek Bluetooth Radio                                                             | 10        | 5.46%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 4.37%   |
| IMC Networks Bluetooth Device                                                       | 7         | 3.83%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 3.28%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 2.73%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.73%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 2.73%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.19%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 2.19%   |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 2.19%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 2.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.64%   |
| Intel AX211 Bluetooth                                                               | 3         | 1.64%   |
| Intel AX200 Bluetooth                                                               | 3         | 1.64%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 1.09%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.09%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 1.09%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.09%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.55%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.55%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.55%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.55%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.55%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.55%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 1         | 0.55%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.55%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 224       | 77.24%  |
| Nvidia                           | 31        | 10.69%  |
| AMD                              | 26        | 8.97%   |
| Lenovo                           | 2         | 0.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Nordic Semiconductor ASA         | 1         | 0.34%   |
| Logitech                         | 1         | 0.34%   |
| GN Netcom                        | 1         | 0.34%   |
| Generalplus Technology           | 1         | 0.34%   |
| Focusrite-Novation               | 1         | 0.34%   |
| ASUSTek Computer                 | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 10.89%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 6.42%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 6.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 5.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 5.03%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 5.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 5.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 4.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 3.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 3.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 2.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.68%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.4%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.12%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.84%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.84%   |
| Nvidia Audio device                                                                               | 3         | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.84%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.84%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.56%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.56%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 48        | 29.63%  |
| SK hynix            | 39        | 24.07%  |
| Micron Technology   | 22        | 13.58%  |
| Kingston            | 19        | 11.73%  |
| Unknown             | 7         | 4.32%   |
| Ramaxel Technology  | 5         | 3.09%   |
| Elpida              | 5         | 3.09%   |
| A-DATA Technology   | 5         | 3.09%   |
| Crucial             | 3         | 1.85%   |
| Nanya Technology    | 2         | 1.23%   |
| Unknown (83DA)      | 1         | 0.62%   |
| Unknown (0B85)      | 1         | 0.62%   |
| Transcend           | 1         | 0.62%   |
| Toshiba             | 1         | 0.62%   |
| Sesame              | 1         | 0.62%   |
| Qimonda             | 1         | 0.62%   |
| ASint Technology    | 1         | 0.62%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 2.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 2.29%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                   | 3         | 1.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s      | 3         | 1.71%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 1.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 3         | 1.71%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 3         | 1.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 1.14%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 2         | 1.14%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                    | 2         | 1.14%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s       | 2         | 1.14%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 2         | 1.14%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s         | 2         | 1.14%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s         | 2         | 1.14%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 2         | 1.14%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s       | 2         | 1.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 2         | 1.14%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 2         | 1.14%   |
| Micron RAM 8KTF51264HZ-1G6P1 4GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 2         | 1.14%   |
| Kingston RAM HP687515-H66-MCN 4GB SODIMM DDR3 1600MT/s         | 2         | 1.14%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 0.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                 | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3                             | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 1         | 0.57%   |
| Unknown (83DA) RAM MGN02G64E1BF2MT-BB 2GB SODIMM DDR3 1067MT/s | 1         | 0.57%   |
| Unknown (0B85) RAM Module 4GB SODIMM DDR3 1600MT/s             | 1         | 0.57%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s            | 1         | 0.57%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s           | 1         | 0.57%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 65        | 49.62%  |
| DDR4    | 46        | 35.11%  |
| DDR2    | 6         | 4.58%   |
| LPDDR4  | 4         | 3.05%   |
| LPDDR3  | 3         | 2.29%   |
| SDRAM   | 2         | 1.53%   |
| DDR5    | 2         | 1.53%   |
| Unknown | 2         | 1.53%   |
| LPDDR5  | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 120       | 93.02%  |
| Row Of Chips | 6         | 4.65%   |
| Unknown      | 2         | 1.55%   |
| DIMM         | 1         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 54        | 36.99%  |
| 4096  | 52        | 35.62%  |
| 2048  | 23        | 15.75%  |
| 16384 | 12        | 8.22%   |
| 1024  | 4         | 2.74%   |
| 32768 | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 42        | 29.79%  |
| 2667    | 25        | 17.73%  |
| 3200    | 16        | 11.35%  |
| 1334    | 13        | 9.22%   |
| 2133    | 8         | 5.67%   |
| 2400    | 7         | 4.96%   |
| 1333    | 5         | 3.55%   |
| Unknown | 4         | 2.84%   |
| 1067    | 3         | 2.13%   |
| 1066    | 3         | 2.13%   |
| 4800    | 2         | 1.42%   |
| 4199    | 2         | 1.42%   |
| 1867    | 2         | 1.42%   |
| 975     | 2         | 1.42%   |
| 800     | 2         | 1.42%   |
| 667     | 2         | 1.42%   |
| 6400    | 1         | 0.71%   |
| 4267    | 1         | 0.71%   |
| 3266    | 1         | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 59        | 27.57%  |
| IMC Networks                           | 21        | 9.81%   |
| Realtek Semiconductor                  | 20        | 9.35%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 8.41%   |
| Lite-On Technology                     | 13        | 6.07%   |
| Suyin                                  | 12        | 5.61%   |
| Sunplus Innovation Technology          | 12        | 5.61%   |
| Microdia                               | 11        | 5.14%   |
| Quanta                                 | 8         | 3.74%   |
| Acer                                   | 5         | 2.34%   |
| Syntek                                 | 4         | 1.87%   |
| Ricoh                                  | 4         | 1.87%   |
| Apple                                  | 4         | 1.87%   |
| Luxvisions Innotech Limited            | 3         | 1.4%    |
| Alcor Micro                            | 3         | 1.4%    |
| ShineTech                              | 2         | 0.93%   |
| Bison Electronics                      | 2         | 0.93%   |
| ALi                                    | 2         | 0.93%   |
| Z-Star Microelectronics                | 1         | 0.47%   |
| Sunplus Technology                     | 1         | 0.47%   |
| Sonix Technology                       | 1         | 0.47%   |
| Silicon Motion                         | 1         | 0.47%   |
| Samsung Electronics                    | 1         | 0.47%   |
| OPPO Electronics                       | 1         | 0.47%   |
| Nebraska Furniture Mart                | 1         | 0.47%   |
| Logitech                               | 1         | 0.47%   |
| LG Innotek                             | 1         | 0.47%   |
| Lenovo                                 | 1         | 0.47%   |
| icSpring                               | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 4.19%   |
| Lite-On HP HD Camera                                        | 6         | 2.79%   |
| IMC Networks Integrated Camera                              | 6         | 2.79%   |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 2.79%   |
| Realtek Integrated_Webcam_HD                                | 5         | 2.33%   |
| Chicony HP Webcam                                           | 5         | 2.33%   |
| Realtek USB Camera                                          | 4         | 1.86%   |
| Microdia Integrated Webcam                                  | 4         | 1.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 1.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 4         | 1.86%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 1.4%    |
| Sunplus Integrated_Webcam_HD                                | 3         | 1.4%    |
| Microdia Integrated_Webcam_HD                               | 3         | 1.4%    |
| Lite-On HP HD Webcam                                        | 3         | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.4%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 3         | 1.4%    |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.4%    |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.4%    |
| Chicony HP Wide Vision HD Camera                            | 3         | 1.4%    |
| Chicony HP HD Webcam                                        | 3         | 1.4%    |
| Chicony HP HD Camera                                        | 3         | 1.4%    |
| Syntek Lenovo EasyCamera                                    | 2         | 0.93%   |
| Suyin Sony Visual Communication Camera                      | 2         | 0.93%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 0.93%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.93%   |
| Sunplus HP Universal Camera                                 | 2         | 0.93%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 0.93%   |
| Realtek Integrated Webcam HD                                | 2         | 0.93%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 0.93%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 0.93%   |
| IMC Networks Integrated Webcam                              | 2         | 0.93%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 0.93%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 0.93%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 0.93%   |
| Chicony HP Truevision HD                                    | 2         | 0.93%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 0.93%   |
| Chicony HD WebCam                                           | 2         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 2         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 32        | 64%     |
| Synaptics                  | 9         | 18%     |
| Elan Microelectronics      | 4         | 8%      |
| Upek                       | 2         | 4%      |
| Shenzhen Goodix Technology | 2         | 4%      |
| Focal-systems.Corp         | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 24%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 12%     |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 8%      |
| Validity Sensors VFS491                                                    | 2         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4%      |
| Elan ELAN:Fingerprint                                                      | 2         | 4%      |
| Elan ELAN:ARM-M4                                                           | 2         | 4%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2%      |
| Synaptics UWP WBDI Device                                                  | 1         | 2%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2%      |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2%      |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2%      |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 62.16%  |
| Alcor Micro | 9         | 24.32%  |
| O2 Micro    | 4         | 10.81%  |
| Lenovo      | 1         | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 27.03%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 24.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 16.22%  |
| Broadcom 5880                                                                | 5         | 13.51%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 5.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.41%   |
| Broadcom 58200                                                               | 2         | 5.41%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 145       | 56.42%  |
| 1     | 87        | 33.85%  |
| 2     | 21        | 8.17%   |
| 3     | 3         | 1.17%   |
| 5     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 50        | 35.21%  |
| Chipcard                 | 30        | 21.13%  |
| Graphics card            | 27        | 19.01%  |
| Net/wireless             | 10        | 7.04%   |
| Bluetooth                | 6         | 4.23%   |
| Storage                  | 5         | 3.52%   |
| Camera                   | 4         | 2.82%   |
| Sound                    | 2         | 1.41%   |
| Net/ethernet             | 2         | 1.41%   |
| Communication controller | 2         | 1.41%   |
| Unassigned class         | 1         | 0.7%    |
| Network                  | 1         | 0.7%    |
| Multimedia controller    | 1         | 0.7%    |
| Modem                    | 1         | 0.7%    |

