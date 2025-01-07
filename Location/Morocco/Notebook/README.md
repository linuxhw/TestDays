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

Total: 412

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 650 G2              | [b2fc855e3e](https://linux-hardware.org/?probe=b2fc855e3e) | Jan 03, 2025 |
| Dell          | Vostro 1500                 | [b5ecc28563](https://linux-hardware.org/?probe=b5ecc28563) | Dec 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [b007439528](https://linux-hardware.org/?probe=b007439528) | Dec 26, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [dae98f533a](https://linux-hardware.org/?probe=dae98f533a) | Dec 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [5655debff7](https://linux-hardware.org/?probe=5655debff7) | Dec 19, 2024 |
| Toshiba       | Satellite C55-B             | [524c33e748](https://linux-hardware.org/?probe=524c33e748) | Dec 16, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [3c936aa4e5](https://linux-hardware.org/?probe=3c936aa4e5) | Dec 16, 2024 |
| HP            | ProBook 6570b               | [70dbe6620b](https://linux-hardware.org/?probe=70dbe6620b) | Dec 14, 2024 |
| HP            | G62                         | [70f9d38537](https://linux-hardware.org/?probe=70f9d38537) | Dec 11, 2024 |
| HP            | Pavilion dv6                | [92fe6246ab](https://linux-hardware.org/?probe=92fe6246ab) | Dec 09, 2024 |
| HP            | Pavilion g6                 | [36c4171d06](https://linux-hardware.org/?probe=36c4171d06) | Nov 21, 2024 |
| HP            | ProBook 6560b               | [72ddcb1cf2](https://linux-hardware.org/?probe=72ddcb1cf2) | Nov 20, 2024 |
| Google        | Drawman                     | [46c461a6e2](https://linux-hardware.org/?probe=46c461a6e2) | Nov 18, 2024 |
| HP            | Notebook                    | [19d1189e7b](https://linux-hardware.org/?probe=19d1189e7b) | Nov 08, 2024 |
| Dell          | Latitude 7490               | [92bf691a6c](https://linux-hardware.org/?probe=92bf691a6c) | Nov 04, 2024 |
| HP            | Notebook                    | [abea0efa1e](https://linux-hardware.org/?probe=abea0efa1e) | Nov 01, 2024 |
| Dell          | Latitude 7490               | [ce28c4199d](https://linux-hardware.org/?probe=ce28c4199d) | Oct 29, 2024 |
| Samsung       | N150/N210/N220              | [eef263185a](https://linux-hardware.org/?probe=eef263185a) | Oct 22, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | [62c3d2eddd](https://linux-hardware.org/?probe=62c3d2eddd) | Oct 17, 2024 |
| Dell          | Latitude 5420               | [622540975d](https://linux-hardware.org/?probe=622540975d) | Oct 10, 2024 |
| HP            | EliteBook 840 G5            | [533e95fac4](https://linux-hardware.org/?probe=533e95fac4) | Oct 09, 2024 |
| HP            | EliteBook 840 G5            | [c40e4f6c66](https://linux-hardware.org/?probe=c40e4f6c66) | Oct 09, 2024 |
| HP            | EliteBook 8470p             | [f71728ea0e](https://linux-hardware.org/?probe=f71728ea0e) | Sep 20, 2024 |
| Packard Be... | ENNS44HR                    | [b47db91782](https://linux-hardware.org/?probe=b47db91782) | Sep 20, 2024 |
| Dell          | Latitude 7490               | [2e22221506](https://linux-hardware.org/?probe=2e22221506) | Sep 19, 2024 |
| Dell          | Latitude 7490               | [b8cce215a5](https://linux-hardware.org/?probe=b8cce215a5) | Sep 18, 2024 |
| Dell          | XPS 15 9550                 | [266c779453](https://linux-hardware.org/?probe=266c779453) | Sep 12, 2024 |
| Dell          | Inspiron 7548               | [150c9ec14f](https://linux-hardware.org/?probe=150c9ec14f) | Sep 09, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [4c19a63fee](https://linux-hardware.org/?probe=4c19a63fee) | Sep 02, 2024 |
| HP            | EliteBook Folio 9480m       | [206392c090](https://linux-hardware.org/?probe=206392c090) | Aug 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [e0af5cb80e](https://linux-hardware.org/?probe=e0af5cb80e) | Aug 19, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [c349c2ef99](https://linux-hardware.org/?probe=c349c2ef99) | Aug 17, 2024 |
| Dell          | Precision M4600             | [fee987030c](https://linux-hardware.org/?probe=fee987030c) | Aug 12, 2024 |
| Dell          | Precision M4600             | [7decf1dba0](https://linux-hardware.org/?probe=7decf1dba0) | Aug 11, 2024 |
| Dell          | Latitude 5420               | [4017046879](https://linux-hardware.org/?probe=4017046879) | Aug 08, 2024 |
| HP            | 15                          | [89bd9fcc15](https://linux-hardware.org/?probe=89bd9fcc15) | Aug 05, 2024 |
| HP            | 15                          | [97a7e86ff2](https://linux-hardware.org/?probe=97a7e86ff2) | Aug 05, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [9eed9965d0](https://linux-hardware.org/?probe=9eed9965d0) | Jul 25, 2024 |
| Toshiba       | Satellite C660              | [682ee2b1d0](https://linux-hardware.org/?probe=682ee2b1d0) | Jul 21, 2024 |
| Dell          | Vostro 3500                 | [8cafc4b7db](https://linux-hardware.org/?probe=8cafc4b7db) | Jul 19, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [add07540e5](https://linux-hardware.org/?probe=add07540e5) | Jul 09, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [efdb6c4558](https://linux-hardware.org/?probe=efdb6c4558) | Jul 06, 2024 |
| Acer          | Aspire E5-575G              | [b8bf8326fd](https://linux-hardware.org/?probe=b8bf8326fd) | Jul 06, 2024 |
| Lenovo        | Legion Pro 7 16IRX9H 83D... | [43fb16f634](https://linux-hardware.org/?probe=43fb16f634) | Jul 03, 2024 |
| Fujitsu       | LIFEBOOK U7511              | [e3ecabe043](https://linux-hardware.org/?probe=e3ecabe043) | Jun 19, 2024 |
| HP            | EliteBook 8740w             | [158dce1091](https://linux-hardware.org/?probe=158dce1091) | Jun 17, 2024 |
| HP            | Laptop 15-bs0xx             | [d7bb8a4ea8](https://linux-hardware.org/?probe=d7bb8a4ea8) | May 17, 2024 |
| Apple         | MacBookPro9,2               | [5b949515c2](https://linux-hardware.org/?probe=5b949515c2) | May 11, 2024 |
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


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 35        | 11.36%  |
| Ubuntu 22.04       | 27        | 8.77%   |
| Ubuntu 18.04       | 13        | 4.22%   |
| KDE neon 20.04     | 10        | 3.25%   |
| Fedora 39          | 10        | 3.25%   |
| OpenMandriva 4.3   | 9         | 2.92%   |
| Debian 11          | 9         | 2.92%   |
| Arch Rolling       | 9         | 2.92%   |
| Pop!_OS 22.04      | 8         | 2.6%    |
| ArcoLinux Rolling  | 8         | 2.6%    |
| Zorin 16           | 7         | 2.27%   |
| OpenMandriva 4.2   | 6         | 1.95%   |
| Linux Mint 20.2    | 6         | 1.95%   |
| Zorin 17           | 5         | 1.62%   |
| OpenMandriva 23.01 | 5         | 1.62%   |
| Fedora 38          | 5         | 1.62%   |
| Xero Rolling       | 4         | 1.3%    |
| Ubuntu Unity 16.04 | 4         | 1.3%    |
| Ubuntu 20.10       | 4         | 1.3%    |
| Ubuntu 19.10       | 4         | 1.3%    |
| Linux Mint 20.3    | 4         | 1.3%    |
| Fedora 40          | 4         | 1.3%    |
| Elementary 7.1     | 4         | 1.3%    |
| Arch               | 4         | 1.3%    |
| Ubuntu 24.04       | 3         | 0.97%   |
| Manjaro            | 3         | 0.97%   |
| Linux Mint 21.3    | 3         | 0.97%   |
| Linux Mint 21.1    | 3         | 0.97%   |
| Xubuntu 20.04      | 2         | 0.65%   |
| Void Linux         | 2         | 0.65%   |
| Ubuntu 23.10       | 2         | 0.65%   |
| Ubuntu 23.04       | 2         | 0.65%   |
| Ubuntu 21.10       | 2         | 0.65%   |
| Ubuntu 21.04       | 2         | 0.65%   |
| Pop!_OS 21.10      | 2         | 0.65%   |
| OpenMandriva 5.0   | 2         | 0.65%   |
| OpenMandriva 24.12 | 2         | 0.65%   |
| OpenMandriva 23.08 | 2         | 0.65%   |
| Linux Mint 22      | 2         | 0.65%   |
| Linux Mint 21      | 2         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 91        | 31.27%  |
| OpenMandriva | 25        | 8.59%   |
| Fedora       | 25        | 8.59%   |
| Linux Mint   | 20        | 6.87%   |
| Zorin        | 13        | 4.47%   |
| Debian       | 13        | 4.47%   |
| Pop!_OS      | 12        | 4.12%   |
| Arch         | 12        | 4.12%   |
| KDE neon     | 11        | 3.78%   |
| Kali         | 9         | 3.09%   |
| ArcoLinux    | 8         | 2.75%   |
| Manjaro      | 7         | 2.41%   |
| Elementary   | 6         | 2.06%   |
| Ubuntu Unity | 5         | 1.72%   |
| Xero         | 4         | 1.37%   |
| Endless      | 3         | 1.03%   |
| EndeavourOS  | 3         | 1.03%   |
| Xubuntu      | 2         | 0.69%   |
| Void Linux   | 2         | 0.69%   |
| Ubuntu MATE  | 2         | 0.69%   |
| SteamOS      | 2         | 0.69%   |
| openSUSE     | 2         | 0.69%   |
| Nobara       | 2         | 0.69%   |
| NixOS        | 2         | 0.69%   |
| Garuda Linux | 2         | 0.69%   |
| RHEL         | 1         | 0.34%   |
| Parrot       | 1         | 0.34%   |
| Lubuntu      | 1         | 0.34%   |
| Linux Lite   | 1         | 0.34%   |
| Kubuntu      | 1         | 0.34%   |
| CentOS       | 1         | 0.34%   |
| BunsenLabs   | 1         | 0.34%   |
| blendOS      | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 9         | 2.76%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.84%   |
| 6.2.0-33-generic         | 5         | 1.53%   |
| 6.1.1-desktop-1omv2290   | 5         | 1.53%   |
| 5.8.0-43-generic         | 5         | 1.53%   |
| 5.13.0-40-generic        | 5         | 1.53%   |
| 5.4.0-58-generic         | 4         | 1.23%   |
| 5.4.0-48-generic         | 4         | 1.23%   |
| 6.8.4-200.fc39.x86_64    | 3         | 0.92%   |
| 6.5.0-26-generic         | 3         | 0.92%   |
| 6.5.0-14-generic         | 3         | 0.92%   |
| 6.2.0-37-generic         | 3         | 0.92%   |
| 5.4.0-42-generic         | 3         | 0.92%   |
| 5.3.0-40-generic         | 3         | 0.92%   |
| 5.17.5-76051705-generic  | 3         | 0.92%   |
| 5.15.0-46-generic        | 3         | 0.92%   |
| 5.13.0-27-generic        | 3         | 0.92%   |
| 5.11.0-37-generic        | 3         | 0.92%   |
| 6.8.0-45-generic         | 2         | 0.61%   |
| 6.7.9-200.fc39.x86_64    | 2         | 0.61%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.61%   |
| 6.5.0-28-generic         | 2         | 0.61%   |
| 6.5.0-21-generic         | 2         | 0.61%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.61%   |
| 6.2.6-76060206-generic   | 2         | 0.61%   |
| 6.2.14-300.fc38.x86_64   | 2         | 0.61%   |
| 6.2.0-39-generic         | 2         | 0.61%   |
| 6.12.1-desktop-1omv2490  | 2         | 0.61%   |
| 6.10.4-zen2-1-zen        | 2         | 0.61%   |
| 5.8.0-48-generic         | 2         | 0.61%   |
| 5.8.0-33-generic         | 2         | 0.61%   |
| 5.4.0-96-generic         | 2         | 0.61%   |
| 5.4.0-88-generic         | 2         | 0.61%   |
| 5.4.0-65-generic         | 2         | 0.61%   |
| 5.4.0-37-generic         | 2         | 0.61%   |
| 5.4.0-33-generic         | 2         | 0.61%   |
| 5.4.0-29-generic         | 2         | 0.61%   |
| 5.3.0-kali2-686-pae      | 2         | 0.61%   |
| 5.3.0-51-generic         | 2         | 0.61%   |
| 5.3.0-28-generic         | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 11.04%  |
| 5.15.0  | 23        | 7.47%   |
| 6.5.0   | 15        | 4.87%   |
| 5.8.0   | 14        | 4.55%   |
| 6.2.0   | 13        | 4.22%   |
| 5.13.0  | 13        | 4.22%   |
| 5.11.0  | 12        | 3.9%    |
| 4.15.0  | 12        | 3.9%    |
| 5.3.0   | 10        | 3.25%   |
| 5.10.0  | 10        | 3.25%   |
| 5.16.7  | 9         | 2.92%   |
| 5.19.0  | 8         | 2.6%    |
| 6.8.0   | 6         | 1.95%   |
| 5.10.14 | 6         | 1.95%   |
| 5.0.0   | 6         | 1.95%   |
| 6.1.1   | 5         | 1.62%   |
| 6.8.4   | 3         | 0.97%   |
| 6.7.9   | 3         | 0.97%   |
| 6.2.6   | 3         | 0.97%   |
| 6.10.3  | 3         | 0.97%   |
| 6.1.0   | 3         | 0.97%   |
| 5.17.5  | 3         | 0.97%   |
| 4.18.0  | 3         | 0.97%   |
| 6.9.5   | 2         | 0.65%   |
| 6.8.7   | 2         | 0.65%   |
| 6.6.2   | 2         | 0.65%   |
| 6.5.3   | 2         | 0.65%   |
| 6.4.11  | 2         | 0.65%   |
| 6.2.9   | 2         | 0.65%   |
| 6.2.14  | 2         | 0.65%   |
| 6.12.1  | 2         | 0.65%   |
| 6.11.0  | 2         | 0.65%   |
| 6.10.4  | 2         | 0.65%   |
| 5.18.19 | 2         | 0.65%   |
| 5.16.0  | 2         | 0.65%   |
| 5.14.14 | 2         | 0.65%   |
| 4.19.0  | 2         | 0.65%   |
| 6.9.7   | 1         | 0.32%   |
| 6.9.6   | 1         | 0.32%   |
| 6.9.3   | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 11.04%  |
| 5.15    | 29        | 9.42%   |
| 6.5     | 21        | 6.82%   |
| 6.2     | 21        | 6.82%   |
| 5.10    | 17        | 5.52%   |
| 5.8     | 16        | 5.19%   |
| 5.13    | 14        | 4.55%   |
| 5.11    | 14        | 4.55%   |
| 6.8     | 12        | 3.9%    |
| 5.16    | 12        | 3.9%    |
| 4.15    | 12        | 3.9%    |
| 5.19    | 11        | 3.57%   |
| 6.6     | 10        | 3.25%   |
| 6.1     | 10        | 3.25%   |
| 5.3     | 10        | 3.25%   |
| 6.10    | 7         | 2.27%   |
| 5.17    | 6         | 1.95%   |
| 5.0     | 6         | 1.95%   |
| 6.9     | 5         | 1.62%   |
| 6.4     | 5         | 1.62%   |
| 6.3     | 5         | 1.62%   |
| 6.11    | 5         | 1.62%   |
| 6.7     | 4         | 1.3%    |
| 5.18    | 4         | 1.3%    |
| 6.12    | 3         | 0.97%   |
| 6.0     | 3         | 0.97%   |
| 5.14    | 3         | 0.97%   |
| 4.18    | 3         | 0.97%   |
| 4.19    | 2         | 0.65%   |
| 5.7     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.14    | 1         | 0.32%   |
| 4.13    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 278       | 97.54%  |
| i686   | 7         | 2.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 153       | 52.22%  |
| KDE5            | 48        | 16.38%  |
| Unknown         | 21        | 7.17%   |
| XFCE            | 17        | 5.8%    |
| X-Cinnamon      | 15        | 5.12%   |
| Pantheon        | 6         | 2.05%   |
| KDE             | 6         | 2.05%   |
| Unity           | 5         | 1.71%   |
| KDE6            | 4         | 1.37%   |
| i3              | 4         | 1.37%   |
| MATE            | 3         | 1.02%   |
| LXQt            | 2         | 0.68%   |
| GNOME Flashback | 2         | 0.68%   |
| Cinnamon        | 2         | 0.68%   |
| xmonad          | 1         | 0.34%   |
| sway            | 1         | 0.34%   |
| Hyprland        | 1         | 0.34%   |
| Budgie          | 1         | 0.34%   |
| bspwm           | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 193       | 65.65%  |
| Wayland | 88        | 29.93%  |
| Unknown | 9         | 3.06%   |
| Tty     | 4         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 138       | 46.15%  |
| SDDM    | 51        | 17.06%  |
| GDM     | 40        | 13.38%  |
| GDM3    | 39        | 13.04%  |
| LightDM | 28        | 9.36%   |
| TDM     | 3         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 169       | 59.09%  |
| fr_FR   | 79        | 27.62%  |
| Unknown | 15        | 5.24%   |
| en_GB   | 9         | 3.15%   |
| de_DE   | 3         | 1.05%   |
| C       | 3         | 1.05%   |
| es_ES   | 2         | 0.7%    |
| it_IT   | 1         | 0.35%   |
| fr_MA   | 1         | 0.35%   |
| fr_BE   | 1         | 0.35%   |
| en_AG   | 1         | 0.35%   |
| ar_MA   | 1         | 0.35%   |
| ar_EG   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 173       | 60.28%  |
| EFI  | 114       | 39.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 212       | 73.61%  |
| Btrfs   | 33        | 11.46%  |
| Overlay | 26        | 9.03%   |
| Tmpfs   | 13        | 4.51%   |
| Xfs     | 2         | 0.69%   |
| Unknown | 2         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 134       | 46.21%  |
| GPT     | 105       | 36.21%  |
| MBR     | 51        | 17.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 253       | 88.15%  |
| Yes       | 34        | 11.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 200       | 69.2%   |
| Yes       | 89        | 30.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 93        | 32.63%  |
| Dell                | 51        | 17.89%  |
| Lenovo              | 48        | 16.84%  |
| ASUSTek Computer    | 23        | 8.07%   |
| Acer                | 14        | 4.91%   |
| Toshiba             | 11        | 3.86%   |
| Apple               | 5         | 1.75%   |
| Sony                | 4         | 1.4%    |
| Packard Bell        | 4         | 1.4%    |
| Samsung Electronics | 3         | 1.05%   |
| Timi                | 2         | 0.7%    |
| HUAWEI              | 2         | 0.7%    |
| Google              | 2         | 0.7%    |
| Fujitsu             | 2         | 0.7%    |
| eMachines           | 2         | 0.7%    |
| Unknown             | 2         | 0.7%    |
| Valve               | 1         | 0.35%   |
| TUXEDO              | 1         | 0.35%   |
| TrekStor            | 1         | 0.35%   |
| Thomson             | 1         | 0.35%   |
| SINTRONES           | 1         | 0.35%   |
| Razer               | 1         | 0.35%   |
| MSI                 | 1         | 0.35%   |
| Medion              | 1         | 0.35%   |
| Mediacom            | 1         | 0.35%   |
| LG Electronics      | 1         | 0.35%   |
| GPD                 | 1         | 0.35%   |
| Gigabyte Technology | 1         | 0.35%   |
| Fujitsu Siemens     | 1         | 0.35%   |
| Clevo               | 1         | 0.35%   |
| Casper              | 1         | 0.35%   |
| American Megatrends | 1         | 0.35%   |
| ACCENT              | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP EliteBook 8440p              | 4         | 1.4%    |
| HP Pavilion g6                  | 3         | 1.05%   |
| HP Notebook                     | 3         | 1.05%   |
| HP Laptop 15-dw3xxx             | 3         | 1.05%   |
| HP EliteBook 840 G3             | 3         | 1.05%   |
| HP EliteBook 840 G2             | 3         | 1.05%   |
| ASUS X540LA                     | 3         | 1.05%   |
| Unknown                         | 3         | 1.05%   |
| Toshiba Satellite C660          | 2         | 0.7%    |
| Timi TM1701                     | 2         | 0.7%    |
| Lenovo ThinkBook 15 G2 ITL 20VE | 2         | 0.7%    |
| Lenovo IdeaPad S145-15IIL 81W8  | 2         | 0.7%    |
| Lenovo IdeaPad L3 15IML05 81Y3  | 2         | 0.7%    |
| HP ZBook 15                     | 2         | 0.7%    |
| HP ProBook 6560b                | 2         | 0.7%    |
| HP ProBook 650 G1               | 2         | 0.7%    |
| HP ProBook 6470b                | 2         | 0.7%    |
| HP ProBook 640 G1               | 2         | 0.7%    |
| HP ProBook 450 G0               | 2         | 0.7%    |
| HP Pavilion 15                  | 2         | 0.7%    |
| HP Laptop 15-ra0xx              | 2         | 0.7%    |
| HP Laptop 15-bs0xx              | 2         | 0.7%    |
| HP EliteBook 8460p              | 2         | 0.7%    |
| HP EliteBook 840 G5             | 2         | 0.7%    |
| HP EliteBook 830 G5             | 2         | 0.7%    |
| HP 250 G5 Notebook PC           | 2         | 0.7%    |
| Dell Vostro 3500                | 2         | 0.7%    |
| Dell Latitude E7450             | 2         | 0.7%    |
| Dell Latitude E6520             | 2         | 0.7%    |
| Dell Latitude E6410             | 2         | 0.7%    |
| Dell Latitude 5420              | 2         | 0.7%    |
| ASUS X555LD                     | 2         | 0.7%    |
| Acer Aspire ES1-523             | 2         | 0.7%    |
| Valve Jupiter                   | 1         | 0.35%   |
| TUXEDO N13xWU                   | 1         | 0.35%   |
| TrekStor Surfbook W2            | 1         | 0.35%   |
| Toshiba Satellite Pro L300      | 1         | 0.35%   |
| Toshiba Satellite Pro C650      | 1         | 0.35%   |
| Toshiba Satellite L750          | 1         | 0.35%   |
| Toshiba Satellite L50-B         | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 38        | 13.33%  |
| Lenovo ThinkPad       | 28        | 9.82%   |
| HP EliteBook          | 26        | 9.12%   |
| HP ProBook            | 18        | 6.32%   |
| HP Pavilion           | 12        | 4.21%   |
| Toshiba Satellite     | 11        | 3.86%   |
| HP Laptop             | 11        | 3.86%   |
| Lenovo IdeaPad        | 9         | 3.16%   |
| Acer Aspire           | 9         | 3.16%   |
| HP ZBook              | 5         | 1.75%   |
| HP 250                | 5         | 1.75%   |
| Dell Vostro           | 4         | 1.4%    |
| Dell Inspiron         | 4         | 1.4%    |
| Packard Bell EasyNote | 3         | 1.05%   |
| Lenovo ThinkBook      | 3         | 1.05%   |
| HP Notebook           | 3         | 1.05%   |
| Dell Precision        | 3         | 1.05%   |
| ASUS Zenbook          | 3         | 1.05%   |
| ASUS X540LA           | 3         | 1.05%   |
| Unknown               | 3         | 1.05%   |
| Timi TM1701           | 2         | 0.7%    |
| HP OMEN               | 2         | 0.7%    |
| HP Compaq             | 2         | 0.7%    |
| Fujitsu LIFEBOOK      | 2         | 0.7%    |
| Dell XPS              | 2         | 0.7%    |
| ASUS X555LD           | 2         | 0.7%    |
| ASUS VivoBook         | 2         | 0.7%    |
| Acer Nitro            | 2         | 0.7%    |
| Valve Jupiter         | 1         | 0.35%   |
| TUXEDO N13xWU         | 1         | 0.35%   |
| TrekStor Surfbook     | 1         | 0.35%   |
| Thomson N14C4WH64     | 1         | 0.35%   |
| Sony VPCF12A4E        | 1         | 0.35%   |
| Sony VPCEH1L8E        | 1         | 0.35%   |
| Sony VGN-FW11L        | 1         | 0.35%   |
| Sony SVE14122CAW      | 1         | 0.35%   |
| SINTRONES AMB-5000G1  | 1         | 0.35%   |
| Samsung N150          | 1         | 0.35%   |
| Samsung 355V4C        | 1         | 0.35%   |
| Samsung 300E4A        | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2010 | 28        | 9.82%   |
| 2018 | 27        | 9.47%   |
| 2011 | 27        | 9.47%   |
| 2013 | 26        | 9.12%   |
| 2016 | 25        | 8.77%   |
| 2014 | 25        | 8.77%   |
| 2020 | 21        | 7.37%   |
| 2015 | 18        | 6.32%   |
| 2019 | 14        | 4.91%   |
| 2017 | 14        | 4.91%   |
| 2012 | 14        | 4.91%   |
| 2021 | 13        | 4.56%   |
| 2008 | 7         | 2.46%   |
| 2009 | 6         | 2.11%   |
| 2022 | 5         | 1.75%   |
| 2007 | 5         | 1.75%   |
| 2023 | 4         | 1.4%    |
| 2024 | 3         | 1.05%   |
| 2006 | 2         | 0.7%    |
| 2005 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 285       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 272       | 94.44%  |
| Enabled  | 16        | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 282       | 98.95%  |
| Yes  | 3         | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 106       | 36.81%  |
| 3.01-4.0    | 70        | 24.31%  |
| 8.01-16.0   | 39        | 13.54%  |
| 16.01-24.0  | 34        | 11.81%  |
| 1.01-2.0    | 15        | 5.21%   |
| 32.01-64.0  | 12        | 4.17%   |
| 2.01-3.0    | 5         | 1.74%   |
| 24.01-32.0  | 4         | 1.39%   |
| 0.51-1.0    | 2         | 0.69%   |
| 64.01-256.0 | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 105       | 33.76%  |
| 2.01-3.0  | 100       | 32.15%  |
| 4.01-8.0  | 50        | 16.08%  |
| 3.01-4.0  | 36        | 11.58%  |
| 0.51-1.0  | 13        | 4.18%   |
| 8.01-16.0 | 6         | 1.93%   |
| 0.01-0.5  | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 236       | 82.23%  |
| 2      | 45        | 15.68%  |
| 3      | 5         | 1.74%   |
| 4      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 167       | 58.6%   |
| Yes       | 118       | 41.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 86.32%  |
| No        | 39        | 13.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 283       | 98.95%  |
| No        | 3         | 1.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 72.41%  |
| No        | 80        | 27.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 285       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Casablanca             | 75        | 24.12%  |
| Marrakesh              | 34        | 10.93%  |
| Rabat                  | 26        | 8.36%   |
| Agadir                 | 22        | 7.07%   |
| Fes                    | 19        | 6.11%   |
| Kenitra                | 16        | 5.14%   |
| Tangier                | 14        | 4.5%    |
| Oujda                  | 14        | 4.5%    |
| Salé                  | 13        | 4.18%   |
| Meknes                 | 10        | 3.22%   |
| Khouribga              | 7         | 2.25%   |
| Nador                  | 5         | 1.61%   |
| Tiznit                 | 4         | 1.29%   |
| El Jadida              | 4         | 1.29%   |
| Taza                   | 3         | 0.96%   |
| Safi                   | 3         | 0.96%   |
| Guelmim                | 3         | 0.96%   |
| Beni Mellal            | 3         | 0.96%   |
| Tétouan               | 2         | 0.64%   |
| Temara                 | 2         | 0.64%   |
| Martil                 | 2         | 0.64%   |
| Berkane                | 2         | 0.64%   |
| Youssoufia             | 1         | 0.32%   |
| Tit Mellil             | 1         | 0.32%   |
| Targuist               | 1         | 0.32%   |
| Taourirt               | 1         | 0.32%   |
| Skhirate               | 1         | 0.32%   |
| Sidi Slimane           | 1         | 0.32%   |
| Sidi Kacem             | 1         | 0.32%   |
| Sidi Allal El Bahraoui | 1         | 0.32%   |
| Settat                 | 1         | 0.32%   |
| Sefrou                 | 1         | 0.32%   |
| Oued Zem               | 1         | 0.32%   |
| Mohammedia             | 1         | 0.32%   |
| Midelt                 | 1         | 0.32%   |
| Laayoune               | 1         | 0.32%   |
| Ksar El Kebir          | 1         | 0.32%   |
| Khemisset              | 1         | 0.32%   |
| Karia Ba Mohamed       | 1         | 0.32%   |
| Inezgane               | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 45        | 55     | 13.72%  |
| Samsung Electronics         | 44        | 52     | 13.41%  |
| Toshiba                     | 40        | 50     | 12.2%   |
| WDC                         | 37        | 48     | 11.28%  |
| Unknown                     | 18        | 25     | 5.49%   |
| SanDisk                     | 16        | 18     | 4.88%   |
| SK hynix                    | 13        | 16     | 3.96%   |
| Hitachi                     | 12        | 13     | 3.66%   |
| Intel                       | 10        | 12     | 3.05%   |
| HGST                        | 10        | 11     | 3.05%   |
| Micron Technology           | 9         | 11     | 2.74%   |
| Kingston                    | 8         | 10     | 2.44%   |
| Apple                       | 7         | 7      | 2.13%   |
| PNY                         | 5         | 6      | 1.52%   |
| KIOXIA                      | 5         | 5      | 1.52%   |
| LITEON                      | 4         | 4      | 1.22%   |
| China                       | 4         | 5      | 1.22%   |
| Unknown                     | 3         | 3      | 0.91%   |
| LITEONIT                    | 2         | 2      | 0.61%   |
| Kingston Technology Company | 2         | 2      | 0.61%   |
| KingDian                    | 2         | 8      | 0.61%   |
| GOODRAM                     | 2         | 2      | 0.61%   |
| Fujitsu                     | 2         | 2      | 0.61%   |
| Crucial                     | 2         | 2      | 0.61%   |
| TwinMOS                     | 1         | 1      | 0.3%    |
| Transcend                   | 1         | 1      | 0.3%    |
| Team                        | 1         | 1      | 0.3%    |
| Supersonic                  | 1         | 1      | 0.3%    |
| ShiJi                       | 1         | 2      | 0.3%    |
| SG                          | 1         | 1      | 0.3%    |
| RCESSD                      | 1         | 1      | 0.3%    |
| Phison Electronics          | 1         | 1      | 0.3%    |
| Phison                      | 1         | 1      | 0.3%    |
| O2 Micro                    | 1         | 1      | 0.3%    |
| MSI                         | 1         | 1      | 0.3%    |
| Micron/Crucial Technology   | 1         | 1      | 0.3%    |
| Lexar                       | 1         | 1      | 0.3%    |
| KingSpec                    | 1         | 1      | 0.3%    |
| KingFast                    | 1         | 2      | 0.3%    |
| Intenso                     | 1         | 2      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                               | 6         | 1.77%   |
| Seagate ST1000LM035-1RK172 1TB                       | 6         | 1.77%   |
| Toshiba MQ01ABF050 500GB                             | 5         | 1.47%   |
| Seagate ST500LT012-1DG142 500GB                      | 5         | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 5         | 1.47%   |
| Unknown MMC Card  64GB                               | 4         | 1.18%   |
| Toshiba MQ01ABD050 500GB                             | 4         | 1.18%   |
| Samsung NVMe SSD Drive 512GB                         | 4         | 1.18%   |
| HGST HTS545050A7E680 500GB                           | 4         | 1.18%   |
| Unknown MMC Card  32GB                               | 3         | 0.88%   |
| Toshiba MQ01ACF050 500GB                             | 3         | 0.88%   |
| Toshiba MQ01ABD100 1TB                               | 3         | 0.88%   |
| Seagate ST9500325AS 500GB                            | 3         | 0.88%   |
| Samsung NVMe SSD Drive 256GB                         | 3         | 0.88%   |
| Unknown                                              | 3         | 0.88%   |
| WDC WD5000LPCX-80VHAT1 500GB                         | 2         | 0.59%   |
| WDC WD5000LPCX-60VHAT0 500GB                         | 2         | 0.59%   |
| WDC WD1600BEVT-22ZCT0 160GB                          | 2         | 0.59%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 2         | 0.59%   |
| WDC WD10JPVX-60JC3T0 1TB                             | 2         | 0.59%   |
| Unknown MMC Card  16GB                               | 2         | 0.59%   |
| Toshiba KXG50ZNV256G 256GB                           | 2         | 0.59%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1TB                 | 2         | 0.59%   |
| SK hynix SC311 SATA 512GB SSD                        | 2         | 0.59%   |
| Seagate ST980811AS 80GB                              | 2         | 0.59%   |
| Seagate ST9500423AS 500GB                            | 2         | 0.59%   |
| Seagate ST500VT000-1DK142 500GB                      | 2         | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 2         | 0.59%   |
| Seagate ST500LM000-1EJ162 500GB                      | 2         | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 2         | 0.59%   |
| SanDisk NVMe SSD Drive 512GB                         | 2         | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 2         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2         | 0.59%   |
| Samsung MZVLW256HEHP-000L7 256GB                     | 2         | 0.59%   |
| Samsung MZVLB256HAHQ-000H1 256GB                     | 2         | 0.59%   |
| PNY CS900 960GB SSD                                  | 2         | 0.59%   |
| Kingston SA400S37240G 240GB SSD                      | 2         | 0.59%   |
| Kingston SA400S37120G 120GB SSD                      | 2         | 0.59%   |
| Intel SSDSC2BF180A4H 180GB                           | 2         | 0.59%   |
| Hitachi HTS723232A7A364 320GB                        | 2         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 55     | 32.14%  |
| WDC                 | 32        | 43     | 22.86%  |
| Toshiba             | 32        | 37     | 22.86%  |
| Hitachi             | 12        | 13     | 8.57%   |
| HGST                | 10        | 11     | 7.14%   |
| Samsung Electronics | 3         | 3      | 2.14%   |
| Apple               | 3         | 3      | 2.14%   |
| Fujitsu             | 2         | 2      | 1.43%   |
| IBM/Hitachi         | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 16.13%  |
| SanDisk             | 10        | 11     | 10.75%  |
| Kingston            | 7         | 9      | 7.53%   |
| Micron Technology   | 6         | 8      | 6.45%   |
| PNY                 | 5         | 6      | 5.38%   |
| SK hynix            | 4         | 6      | 4.3%    |
| LITEON              | 4         | 4      | 4.3%    |
| Intel               | 4         | 5      | 4.3%    |
| China               | 4         | 5      | 4.3%    |
| Toshiba             | 3         | 3      | 3.23%   |
| Apple               | 3         | 3      | 3.23%   |
| LITEONIT            | 2         | 2      | 2.15%   |
| KingDian            | 2         | 8      | 2.15%   |
| GOODRAM             | 2         | 2      | 2.15%   |
| Crucial             | 2         | 2      | 2.15%   |
| Unknown             | 2         | 2      | 2.15%   |
| TwinMOS             | 1         | 1      | 1.08%   |
| Transcend           | 1         | 1      | 1.08%   |
| Team                | 1         | 1      | 1.08%   |
| Supersonic          | 1         | 1      | 1.08%   |
| RCESSD              | 1         | 1      | 1.08%   |
| MSI                 | 1         | 1      | 1.08%   |
| Lexar               | 1         | 1      | 1.08%   |
| KingSpec            | 1         | 1      | 1.08%   |
| KingFast            | 1         | 1      | 1.08%   |
| Indilinx            | 1         | 1      | 1.08%   |
| Hewlett-Packard     | 1         | 1      | 1.08%   |
| Geonix              | 1         | 1      | 1.08%   |
| BIWIN               | 1         | 1      | 1.08%   |
| Bestoss             | 1         | 1      | 1.08%   |
| Apacer              | 1         | 1      | 1.08%   |
| AFOX                | 1         | 1      | 1.08%   |
| A-DATA Technology   | 1         | 1      | 1.08%   |
| 2.5"                | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 138       | 168    | 43.67%  |
| SSD     | 91        | 113    | 28.8%   |
| NVMe    | 66        | 85     | 20.89%  |
| MMC     | 18        | 25     | 5.7%    |
| Unknown | 3         | 7      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 217       | 285    | 71.38%  |
| NVMe | 66        | 84     | 21.71%  |
| MMC  | 18        | 25     | 5.92%   |
| SAS  | 3         | 4      | 0.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 168       | 207    | 75%     |
| 0.51-1.0   | 54        | 72     | 24.11%  |
| 1.01-2.0   | 2         | 2      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 90        | 30.61%  |
| 251-500        | 76        | 25.85%  |
| 501-1000       | 34        | 11.56%  |
| 51-100         | 33        | 11.22%  |
| 1-20           | 26        | 8.84%   |
| 21-50          | 17        | 5.78%   |
| 1001-2000      | 11        | 3.74%   |
| Unknown        | 4         | 1.36%   |
| More than 3000 | 2         | 0.68%   |
| 2001-3000      | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 126       | 40.78%  |
| 21-50          | 73        | 23.62%  |
| 101-250        | 47        | 15.21%  |
| 51-100         | 39        | 12.62%  |
| 251-500        | 13        | 4.21%   |
| 501-1000       | 4         | 1.29%   |
| Unknown        | 4         | 1.29%   |
| More than 3000 | 2         | 0.65%   |
| 1001-2000      | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB                         | 3         | 3      | 8.11%   |
| Seagate ST9500325AS 500GB                        | 3         | 4      | 8.11%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 5.41%   |
| HGST HTS545050A7E680 500GB                       | 2         | 3      | 5.41%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 2.7%    |
| WDC WD2500BEVS-22UST0 250GB                      | 1         | 1      | 2.7%    |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 2.7%    |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 7      | 2.7%    |
| WDC WD10JPVT-00A1YT0 1TB                         | 1         | 1      | 2.7%    |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.7%    |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 2.7%    |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 2.7%    |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 2.7%    |
| Seagate ST9500423AS 500GB                        | 1         | 1      | 2.7%    |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 2.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.7%    |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 2.7%    |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 2.7%    |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.7%    |
| Samsung Electronics MZ7PD128HAFV-000H7 128GB SSD | 1         | 1      | 2.7%    |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 2.7%    |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 2.7%    |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 2.7%    |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 2.7%    |
| HGST HTS725032A7E630 320GB                       | 1         | 1      | 2.7%    |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 2.7%    |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 2.7%    |
| Apple HDD HTS541010A9E662 1TB                    | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 24.32%  |
| Toshiba             | 8         | 8      | 21.62%  |
| WDC                 | 5         | 11     | 13.51%  |
| Hitachi             | 4         | 5      | 10.81%  |
| HGST                | 4         | 5      | 10.81%  |
| Samsung Electronics | 2         | 2      | 5.41%   |
| SanDisk             | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 28.13%  |
| Toshiba | 8         | 8      | 25%     |
| WDC     | 5         | 11     | 15.63%  |
| Hitachi | 4         | 5      | 12.5%   |
| HGST    | 4         | 5      | 12.5%   |
| Fujitsu | 1         | 1      | 3.13%   |
| Apple   | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 41     | 86.49%  |
| SSD  | 5         | 5      | 13.51%  |

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
| Detected | 169       | 229    | 55.59%  |
| Works    | 96        | 120    | 31.58%  |
| Malfunc  | 37        | 46     | 12.17%  |
| Failed   | 2         | 3      | 0.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 230       | 73.72%  |
| Samsung Electronics              | 28        | 8.97%   |
| AMD                              | 14        | 4.49%   |
| SK hynix                         | 9         | 2.88%   |
| SanDisk                          | 9         | 2.88%   |
| Toshiba America Info Systems     | 5         | 1.6%    |
| KIOXIA                           | 5         | 1.6%    |
| Micron Technology                | 3         | 0.96%   |
| Kingston Technology Company      | 3         | 0.96%   |
| Phison Electronics               | 2         | 0.64%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| O2 Micro                         | 1         | 0.32%   |
| Nvidia                           | 1         | 0.32%   |
| Micron/Crucial Technology        | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 28        | 8.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 28        | 8.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 23        | 6.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 18        | 5.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 16        | 4.79%   |
| Intel Volume Management Device NVMe RAID Controller                              | 14        | 4.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 3.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 3.29%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 3.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 2.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 10        | 2.99%   |
| Intel Tiger Lake-LP SATA Controller                                              | 9         | 2.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 2.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 2.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 1.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 5         | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.9%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.6%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 0.6%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 2         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.6%    |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                   | 2         | 0.6%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 2         | 0.6%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.6%    |
| Phison E12 NVMe Controller                                                       | 2         | 0.6%    |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 2         | 0.6%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.6%    |
| Intel SSD 660P Series                                                            | 2         | 0.6%    |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.6%    |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]               | 2         | 0.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 202       | 62.35%  |
| NVMe | 66        | 20.37%  |
| RAID | 45        | 13.89%  |
| IDE  | 11        | 3.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 265       | 92.98%  |
| AMD    | 20        | 7.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 9         | 3.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 2.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 7         | 2.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 7         | 2.46%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 6         | 2.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 2.11%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 2.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 6         | 2.11%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 5         | 1.75%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 5         | 1.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 5         | 1.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 5         | 1.75%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 5         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.4%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.4%    |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 1.4%    |
| Intel Core i7-8650U CPU @ 1.90GHz           | 3         | 1.05%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.05%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.05%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.05%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 1.05%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 3         | 1.05%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 1.05%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 1.05%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 3         | 1.05%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.05%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.7%    |
| Intel Core i7-8850H CPU @ 2.60GHz           | 2         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.7%    |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 111       | 38.95%  |
| Intel Core i7           | 50        | 17.54%  |
| Intel Core i3           | 33        | 11.58%  |
| Other                   | 26        | 9.12%   |
| Intel Core 2 Duo        | 14        | 4.91%   |
| Intel Celeron           | 14        | 4.91%   |
| Intel Atom              | 7         | 2.46%   |
| AMD Ryzen 7             | 4         | 1.4%    |
| AMD Ryzen 5             | 3         | 1.05%   |
| AMD E1                  | 3         | 1.05%   |
| Intel Pentium Dual-Core | 2         | 0.7%    |
| AMD C-60                | 2         | 0.7%    |
| AMD A8                  | 2         | 0.7%    |
| AMD A6                  | 2         | 0.7%    |
| Intel Pentium Silver    | 1         | 0.35%   |
| Intel Pentium M         | 1         | 0.35%   |
| Intel Pentium Gold      | 1         | 0.35%   |
| Intel Pentium           | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core i9           | 1         | 0.35%   |
| Intel Core 2            | 1         | 0.35%   |
| Intel Core              | 1         | 0.35%   |
| Intel Celeron M         | 1         | 0.35%   |
| AMD Ryzen 9             | 1         | 0.35%   |
| AMD Ryzen 7 PRO         | 1         | 0.35%   |
| AMD A4                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 177       | 62.11%  |
| 4      | 79        | 27.72%  |
| 8      | 8         | 2.81%   |
| 6      | 7         | 2.46%   |
| 1      | 6         | 2.11%   |
| 10     | 3         | 1.05%   |
| 14     | 2         | 0.7%    |
| 24     | 1         | 0.35%   |
| 16     | 1         | 0.35%   |
| 12     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 285       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 229       | 80.35%  |
| 1      | 56        | 19.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 98.25%  |
| 32-bit         | 3         | 1.05%   |
| Unknown        | 2         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 127       | 43.05%  |
| 0x206a7    | 19        | 6.44%   |
| 0x306d4    | 14        | 4.75%   |
| 0x806ea    | 12        | 4.07%   |
| 0x40651    | 12        | 4.07%   |
| 0x806ec    | 9         | 3.05%   |
| 0x306c3    | 9         | 3.05%   |
| 0x306a9    | 9         | 3.05%   |
| 0x20655    | 9         | 3.05%   |
| 0x806c1    | 7         | 2.37%   |
| 0x406e3    | 6         | 2.03%   |
| 0x1067a    | 6         | 2.03%   |
| 0x806e9    | 5         | 1.69%   |
| 0x6fd      | 5         | 1.69%   |
| 0x20652    | 5         | 1.69%   |
| 0x506e3    | 4         | 1.36%   |
| 0x30678    | 4         | 1.36%   |
| 0x0a50000c | 3         | 1.02%   |
| 0x906ea    | 2         | 0.68%   |
| 0x406c4    | 2         | 0.68%   |
| 0x406c3    | 2         | 0.68%   |
| 0x10676    | 2         | 0.68%   |
| 0x07030105 | 2         | 0.68%   |
| 0x0700010f | 2         | 0.68%   |
| 0xb06a3    | 1         | 0.34%   |
| 0x906e9    | 1         | 0.34%   |
| 0x806eb    | 1         | 0.34%   |
| 0x806d1    | 1         | 0.34%   |
| 0x706e5    | 1         | 0.34%   |
| 0x706a1    | 1         | 0.34%   |
| 0x6ec      | 1         | 0.34%   |
| 0x6e8      | 1         | 0.34%   |
| 0x6d8      | 1         | 0.34%   |
| 0x30673    | 1         | 0.34%   |
| 0x30661    | 1         | 0.34%   |
| 0x08108109 | 1         | 0.34%   |
| 0x08108102 | 1         | 0.34%   |
| 0x06006705 | 1         | 0.34%   |
| 0x06001119 | 1         | 0.34%   |
| 0x05000119 | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 15.79%  |
| Haswell          | 37        | 12.98%  |
| SandyBridge      | 26        | 9.12%   |
| Skylake          | 24        | 8.42%   |
| Westmere         | 23        | 8.07%   |
| Broadwell        | 20        | 7.02%   |
| TigerLake        | 17        | 5.96%   |
| IvyBridge        | 15        | 5.26%   |
| Silvermont       | 13        | 4.56%   |
| Penryn           | 11        | 3.86%   |
| Unknown          | 8         | 2.81%   |
| Core             | 7         | 2.46%   |
| Alderlake Hybrid | 6         | 2.11%   |
| IceLake          | 5         | 1.75%   |
| Zen 3            | 4         | 1.4%    |
| Zen+             | 3         | 1.05%   |
| P6               | 3         | 1.05%   |
| Bonnell          | 3         | 1.05%   |
| Bobcat           | 3         | 1.05%   |
| Puma             | 2         | 0.7%    |
| Jaguar           | 2         | 0.7%    |
| Goldmont plus    | 2         | 0.7%    |
| CometLake        | 2         | 0.7%    |
| Piledriver       | 1         | 0.35%   |
| K10 Llano        | 1         | 0.35%   |
| Goldmont         | 1         | 0.35%   |
| Excavator        | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 246       | 69.1%   |
| Nvidia | 70        | 19.66%  |
| AMD    | 40        | 11.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 6.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 6.65%   |
| Intel UHD Graphics 620                                                                   | 19        | 5.26%   |
| Intel HD Graphics 5500                                                                   | 19        | 5.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 4.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 4.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 4.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 4.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.77%   |
| Intel HD Graphics 620                                                                    | 9         | 2.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.94%   |
| Intel HD Graphics 530                                                                    | 7         | 1.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.66%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.11%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.83%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.83%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.83%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.55%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.55%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.55%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 2         | 0.55%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.55%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.55%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.55%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.55%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 178       | 62.24%  |
| Intel + Nvidia | 56        | 19.58%  |
| 1 x AMD        | 26        | 9.09%   |
| 1 x Nvidia     | 11        | 3.85%   |
| Intel + AMD    | 11        | 3.85%   |
| AMD + Nvidia   | 3         | 1.05%   |
| 2 x Intel      | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 240       | 82.47%  |
| Proprietary | 31        | 10.65%  |
| Unknown     | 20        | 6.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 218       | 74.66%  |
| 1.01-2.0   | 30        | 10.27%  |
| 0.01-0.5   | 23        | 7.88%   |
| 3.01-4.0   | 10        | 3.42%   |
| 0.51-1.0   | 9         | 3.08%   |
| 7.01-8.0   | 1         | 0.34%   |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 52        | 17.99%  |
| Chimei Innolux          | 50        | 17.3%   |
| AU Optronics            | 50        | 17.3%   |
| BOE                     | 42        | 14.53%  |
| Samsung Electronics     | 38        | 13.15%  |
| Lenovo                  | 7         | 2.42%   |
| InfoVision              | 7         | 2.42%   |
| Sharp                   | 5         | 1.73%   |
| LG Philips              | 5         | 1.73%   |
| Hewlett-Packard         | 5         | 1.73%   |
| Chi Mei Optoelectronics | 5         | 1.73%   |
| Apple                   | 5         | 1.73%   |
| Dell                    | 4         | 1.38%   |
| PANDA                   | 2         | 0.69%   |
| HannStar                | 2         | 0.69%   |
| Valve                   | 1         | 0.35%   |
| TMX                     | 1         | 0.35%   |
| TCL                     | 1         | 0.35%   |
| Sony                    | 1         | 0.35%   |
| NCS                     | 1         | 0.35%   |
| MSI                     | 1         | 0.35%   |
| LGD                     | 1         | 0.35%   |
| IBM                     | 1         | 0.35%   |
| Goldstar                | 1         | 0.35%   |
| CNC                     | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 1.03%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.69%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.69%   |
| LG Display LCD Monitor LGD0504 1366x768 340x190mm 15.3-inch              | 2         | 0.69%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.69%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.69%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.69%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch               | 2         | 0.69%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 294x165mm 13.3-inch         | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.69%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 2         | 0.69%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.69%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 2         | 0.69%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO42EC 1366x768 344x193mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.69%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.34%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.34%   |
| TCL Beyond TV TCL9653 3840x2160 1210x680mm 54.6-inch                     | 1         | 0.34%   |
| Sony LCD Monitor SNY06FA 1600x900 380x210mm 17.1-inch                    | 1         | 0.34%   |
| Sharp LQ156M1JW24 SHP1534 1920x1080 344x194mm 15.5-inch                  | 1         | 0.34%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 128       | 45.23%  |
| 1920x1080 (FHD)    | 84        | 29.68%  |
| 1600x900 (HD+)     | 20        | 7.07%   |
| 1280x800 (WXGA)    | 10        | 3.53%   |
| 1440x900 (WXGA+)   | 5         | 1.77%   |
| 3840x2160 (4K)     | 4         | 1.41%   |
| 2560x1440 (QHD)    | 4         | 1.41%   |
| 1920x1200 (WUXGA)  | 4         | 1.41%   |
| 1680x1050 (WSXGA+) | 4         | 1.41%   |
| 1024x600           | 4         | 1.41%   |
| 2880x1800          | 2         | 0.71%   |
| 2560x1600          | 2         | 0.71%   |
| 2240x1400          | 2         | 0.71%   |
| 1280x1024 (SXGA)   | 2         | 0.71%   |
| 800x1280           | 1         | 0.35%   |
| 3840x2400          | 1         | 0.35%   |
| 2520x1680          | 1         | 0.35%   |
| 1920x515           | 1         | 0.35%   |
| 1680x945           | 1         | 0.35%   |
| 1400x1050          | 1         | 0.35%   |
| 1360x768           | 1         | 0.35%   |
| 1024x768 (XGA)     | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 148       | 50.86%  |
| 14      | 40        | 13.75%  |
| 13      | 38        | 13.06%  |
| 17      | 14        | 4.81%   |
| 12      | 14        | 4.81%   |
| 18      | 6         | 2.06%   |
| 23      | 4         | 1.37%   |
| 11      | 4         | 1.37%   |
| 24      | 3         | 1.03%   |
| 22      | 3         | 1.03%   |
| 16      | 3         | 1.03%   |
| 10      | 3         | 1.03%   |
| 31      | 2         | 0.69%   |
| Unknown | 2         | 0.69%   |
| 84      | 1         | 0.34%   |
| 54      | 1         | 0.34%   |
| 32      | 1         | 0.34%   |
| 27      | 1         | 0.34%   |
| 21      | 1         | 0.34%   |
| 19      | 1         | 0.34%   |
| 7       | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 209       | 72.07%  |
| 201-300     | 37        | 12.76%  |
| 351-400     | 19        | 6.55%   |
| 401-500     | 9         | 3.1%    |
| 501-600     | 8         | 2.76%   |
| 601-700     | 2         | 0.69%   |
| Unknown     | 2         | 0.69%   |
| 701-800     | 1         | 0.34%   |
| 1501-2000   | 1         | 0.34%   |
| 1001-1500   | 1         | 0.34%   |
| 1-100       | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 239       | 85.36%  |
| 16/10   | 31        | 11.07%  |
| 4/3     | 3         | 1.07%   |
| 5/4     | 2         | 0.71%   |
| 3/2     | 2         | 0.71%   |
| 3.73    | 1         | 0.36%   |
| 0.67    | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 147       | 50.52%  |
| 81-90          | 66        | 22.68%  |
| 61-70          | 13        | 4.47%   |
| 71-80          | 11        | 3.78%   |
| 121-130        | 10        | 3.44%   |
| 201-250        | 8         | 2.75%   |
| 141-150        | 6         | 2.06%   |
| 51-60          | 4         | 1.37%   |
| 111-120        | 4         | 1.37%   |
| 351-500        | 3         | 1.03%   |
| 41-50          | 3         | 1.03%   |
| 151-200        | 3         | 1.03%   |
| 131-140        | 3         | 1.03%   |
| More than 1000 | 2         | 0.69%   |
| 251-300        | 2         | 0.69%   |
| 91-100         | 2         | 0.69%   |
| Unknown        | 2         | 0.69%   |
| 1-40           | 1         | 0.34%   |
| 301-350        | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 125       | 43.25%  |
| 121-160       | 99        | 34.26%  |
| 51-100        | 36        | 12.46%  |
| 161-240       | 23        | 7.96%   |
| More than 240 | 3         | 1.04%   |
| Unknown       | 2         | 0.69%   |
| 1-50          | 1         | 0.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 259       | 89.62%  |
| 2     | 22        | 7.61%   |
| 0     | 8         | 2.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 159       | 36.05%  |
| Realtek Semiconductor    | 123       | 27.89%  |
| Qualcomm Atheros         | 57        | 12.93%  |
| Broadcom                 | 44        | 9.98%   |
| Ralink Technology        | 15        | 3.4%    |
| Ralink                   | 8         | 1.81%   |
| Broadcom Limited         | 6         | 1.36%   |
| Sierra Wireless          | 5         | 1.13%   |
| Dell                     | 5         | 1.13%   |
| Xiaomi                   | 3         | 0.68%   |
| Samsung Electronics      | 3         | 0.68%   |
| Marvell Technology Group | 3         | 0.68%   |
| MediaTek                 | 2         | 0.45%   |
| Lenovo                   | 2         | 0.45%   |
| TP-Link                  | 1         | 0.23%   |
| Qualcomm                 | 1         | 0.23%   |
| Nvidia                   | 1         | 0.23%   |
| JMicron Technology       | 1         | 0.23%   |
| Huawei Technologies      | 1         | 0.23%   |
| Arduino SA               | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 74        | 13.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 5.11%   |
| Intel Wireless 8265 / 8275                                             | 20        | 3.53%   |
| Intel Wireless 8260                                                    | 16        | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 13        | 2.29%   |
| Intel Wireless 7265                                                    | 13        | 2.29%   |
| Intel 82577LM Gigabit Network Connection                               | 13        | 2.29%   |
| Ralink MT7601U Wireless Adapter                                        | 12        | 2.12%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.76%   |
| Intel Centrino Advanced-N 6200                                         | 10        | 1.76%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 9         | 1.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 8         | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 8         | 1.41%   |
| Intel Wireless 7260                                                    | 8         | 1.41%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.41%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                          | 8         | 1.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 7         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.06%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                         | 5         | 0.88%   |
| Intel Centrino Advanced-N 6235                                         | 5         | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.71%   |
| Intel WiFi Link 5100                                                   | 4         | 0.71%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 0.71%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 4         | 0.71%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 145       | 47.54%  |
| Qualcomm Atheros      | 52        | 17.05%  |
| Broadcom              | 34        | 11.15%  |
| Realtek Semiconductor | 33        | 10.82%  |
| Ralink Technology     | 15        | 4.92%   |
| Ralink                | 8         | 2.62%   |
| Broadcom Limited      | 6         | 1.97%   |
| Sierra Wireless       | 5         | 1.64%   |
| Dell                  | 4         | 1.31%   |
| MediaTek              | 2         | 0.66%   |
| TP-Link               | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 20        | 6.54%   |
| Intel Wireless 8260                                            | 16        | 5.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 4.25%   |
| Intel Wireless 7265                                            | 13        | 4.25%   |
| Ralink MT7601U Wireless Adapter                                | 12        | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 3.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.27%   |
| Intel Centrino Advanced-N 6200                                 | 10        | 3.27%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 2.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 2.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 2.61%   |
| Intel Wireless 7260                                            | 8         | 2.61%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 2.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 7         | 2.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.63%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.63%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.63%   |
| Intel WiFi Link 5100                                           | 4         | 1.31%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 1.31%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 4         | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 0.98%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 3         | 0.98%   |
| Sierra Wireless EM7455                                         | 2         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.65%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.65%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.65%   |
| Intel Wireless 3165                                            | 2         | 0.65%   |
| Intel Wireless 3160                                            | 2         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 111       | 43.53%  |
| Intel                    | 102       | 40%     |
| Broadcom                 | 15        | 5.88%   |
| Qualcomm Atheros         | 12        | 4.71%   |
| Xiaomi                   | 3         | 1.18%   |
| Marvell Technology Group | 3         | 1.18%   |
| Samsung Electronics      | 2         | 0.78%   |
| Lenovo                   | 2         | 0.78%   |
| Qualcomm                 | 1         | 0.39%   |
| Nvidia                   | 1         | 0.39%   |
| JMicron Technology       | 1         | 0.39%   |
| Huawei Technologies      | 1         | 0.39%   |
| Broadcom Limited         | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 74        | 28.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 11.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 5.45%   |
| Intel 82577LM Gigabit Network Connection                               | 13        | 5.06%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 4.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 3.5%    |
| Intel Ethernet Connection I219-LM                                      | 8         | 3.11%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 3.11%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 2.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 1.56%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 1.17%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.17%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 1.17%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.17%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 1.17%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.78%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.78%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.78%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.39%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.39%   |
| Qualcomm Airtel 4G                                                     | 1         | 0.39%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.39%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.39%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.39%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                    | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 283       | 53.2%   |
| Ethernet | 245       | 46.05%  |
| Modem    | 4         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 243       | 84.38%  |
| Ethernet | 45        | 15.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 238       | 83.22%  |
| 1     | 41        | 14.34%  |
| 0     | 5         | 1.75%   |
| 7     | 1         | 0.35%   |
| 3     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 285       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 100       | 47.62%  |
| Realtek Semiconductor           | 23        | 10.95%  |
| Qualcomm Atheros Communications | 20        | 9.52%   |
| Broadcom                        | 15        | 7.14%   |
| IMC Networks                    | 9         | 4.29%   |
| Dell                            | 8         | 3.81%   |
| Lite-On Technology              | 7         | 3.33%   |
| Hewlett-Packard                 | 7         | 3.33%   |
| Ralink                          | 5         | 2.38%   |
| Foxconn / Hon Hai               | 4         | 1.9%    |
| Apple                           | 4         | 1.9%    |
| Toshiba                         | 3         | 1.43%   |
| Ralink Technology               | 1         | 0.48%   |
| Foxconn International           | 1         | 0.48%   |
| Cambridge Silicon Radio         | 1         | 0.48%   |
| ASUSTek Computer                | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 52        | 24.76%  |
| Intel AX201 Bluetooth                                                               | 18        | 8.57%   |
| Realtek Bluetooth Radio                                                             | 14        | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 3.81%   |
| Intel AX211 Bluetooth                                                               | 7         | 3.33%   |
| IMC Networks Bluetooth Device                                                       | 7         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 2.86%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.38%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 2.38%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.9%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.9%    |
| Intel AX200 Bluetooth                                                               | 4         | 1.9%    |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 1.9%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 1.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.43%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.95%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.95%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.95%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.95%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.95%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.48%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.48%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.48%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.48%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.48%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.48%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 1         | 0.48%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.48%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.48%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 260       | 78.31%  |
| Nvidia                           | 34        | 10.24%  |
| AMD                              | 28        | 8.43%   |
| Lenovo                           | 2         | 0.6%    |
| GN Netcom                        | 2         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| Nordic Semiconductor ASA         | 1         | 0.3%    |
| Logitech                         | 1         | 0.3%    |
| Generalplus Technology           | 1         | 0.3%    |
| Focusrite-Novation               | 1         | 0.3%    |
| ASUSTek Computer                 | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 44        | 10.89%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 6.19%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 6.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 23        | 5.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 5.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 4.95%   |
| Intel Broadwell-U Audio Controller                                                                | 20        | 4.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 4.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 4.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.23%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 9         | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.98%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.49%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.24%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.99%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.99%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.74%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.74%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 3         | 0.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.74%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.74%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.5%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 58        | 30.53%  |
| SK hynix            | 49        | 25.79%  |
| Micron Technology   | 25        | 13.16%  |
| Kingston            | 21        | 11.05%  |
| Unknown             | 7         | 3.68%   |
| Ramaxel Technology  | 5         | 2.63%   |
| Elpida              | 5         | 2.63%   |
| A-DATA Technology   | 5         | 2.63%   |
| Crucial             | 4         | 2.11%   |
| Nanya Technology    | 3         | 1.58%   |
| Transcend           | 2         | 1.05%   |
| Unknown (83DA)      | 1         | 0.53%   |
| Unknown (0B85)      | 1         | 0.53%   |
| Toshiba             | 1         | 0.53%   |
| Sesame              | 1         | 0.53%   |
| Qimonda             | 1         | 0.53%   |
| ASint Technology    | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 2.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 1.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 1.97%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                | 3         | 1.48%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 3         | 1.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 1.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 1.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 3         | 1.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 3         | 1.48%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 3         | 1.48%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 3         | 1.48%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s         | 2         | 0.99%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 0.99%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 0.99%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                 | 2         | 0.99%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s    | 2         | 0.99%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 0.99%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 2         | 0.99%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 0.99%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 0.99%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s       | 2         | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.99%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s       | 2         | 0.99%   |
| Micron RAM 8KTF51264HZ-1G6P1 4GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 2         | 0.99%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 2         | 0.99%   |
| Kingston RAM HP687515-H66-MCN 4GB SODIMM DDR3 1600MT/s      | 2         | 0.99%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s              | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 74        | 48.37%  |
| DDR4    | 56        | 36.6%   |
| DDR2    | 6         | 3.92%   |
| LPDDR4  | 4         | 2.61%   |
| LPDDR5  | 3         | 1.96%   |
| LPDDR3  | 3         | 1.96%   |
| DDR5    | 3         | 1.96%   |
| SDRAM   | 2         | 1.31%   |
| Unknown | 2         | 1.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 140       | 92.11%  |
| Row Of Chips | 9         | 5.92%   |
| Unknown      | 2         | 1.32%   |
| DIMM         | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 62        | 36.47%  |
| 8192  | 61        | 35.88%  |
| 2048  | 22        | 12.94%  |
| 16384 | 19        | 11.18%  |
| 1024  | 4         | 2.35%   |
| 32768 | 2         | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 46        | 28.05%  |
| 2667    | 29        | 17.68%  |
| 3200    | 23        | 14.02%  |
| 1334    | 14        | 8.54%   |
| 2133    | 9         | 5.49%   |
| 2400    | 8         | 4.88%   |
| 1333    | 7         | 4.27%   |
| Unknown | 4         | 2.44%   |
| 1067    | 3         | 1.83%   |
| 1066    | 3         | 1.83%   |
| 6400    | 2         | 1.22%   |
| 4800    | 2         | 1.22%   |
| 4199    | 2         | 1.22%   |
| 1867    | 2         | 1.22%   |
| 975     | 2         | 1.22%   |
| 800     | 2         | 1.22%   |
| 667     | 2         | 1.22%   |
| 7467    | 1         | 0.61%   |
| 5600    | 1         | 0.61%   |
| 4267    | 1         | 0.61%   |
| 3266    | 1         | 0.61%   |

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
| Chicony Electronics                    | 69        | 27.71%  |
| IMC Networks                           | 23        | 9.24%   |
| Realtek Semiconductor                  | 21        | 8.43%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 7.63%   |
| Sunplus Innovation Technology          | 17        | 6.83%   |
| Lite-On Technology                     | 14        | 5.62%   |
| Microdia                               | 13        | 5.22%   |
| Suyin                                  | 12        | 4.82%   |
| Quanta                                 | 12        | 4.82%   |
| Bison Electronics                      | 7         | 2.81%   |
| Luxvisions Innotech Limited            | 6         | 2.41%   |
| Apple                                  | 5         | 2.01%   |
| Syntek                                 | 4         | 1.61%   |
| Ricoh                                  | 4         | 1.61%   |
| Alcor Micro                            | 3         | 1.2%    |
| Z-Star Microelectronics                | 2         | 0.8%    |
| Silicon Motion                         | 2         | 0.8%    |
| Shinetech                              | 2         | 0.8%    |
| ALi                                    | 2         | 0.8%    |
| Acer                                   | 2         | 0.8%    |
| Sunplus Technology                     | 1         | 0.4%    |
| Sonix Technology                       | 1         | 0.4%    |
| Samsung Electronics                    | 1         | 0.4%    |
| OPPO Electronics                       | 1         | 0.4%    |
| OmniVision Technologies                | 1         | 0.4%    |
| Nebraska Furniture Mart                | 1         | 0.4%    |
| Logitech                               | 1         | 0.4%    |
| LG Innotek                             | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| icSpring                               | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 11        | 4.4%    |
| IMC Networks Integrated Camera                              | 7         | 2.8%    |
| Lite-On HP HD Camera                                        | 6         | 2.4%    |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 2.4%    |
| Chicony HP Webcam                                           | 6         | 2.4%    |
| Sunplus Integrated_Webcam_HD                                | 5         | 2%      |
| Realtek Integrated_Webcam_HD                                | 5         | 2%      |
| Microdia Integrated_Webcam_HD                               | 5         | 2%      |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 4         | 1.6%    |
| Microdia Integrated Webcam                                  | 4         | 1.6%    |
| Lite-On HP HD Webcam                                        | 4         | 1.6%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 1.6%    |
| Chicony HP HD Camera                                        | 4         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 4         | 1.6%    |
| Realtek USB Camera                                          | 3         | 1.2%    |
| Quanta HP Wide Vision HD Camera                             | 3         | 1.2%    |
| Quanta HD WebCam                                            | 3         | 1.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.2%    |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.2%    |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.2%    |
| Chicony TOSHIBA Web Camera - HD                             | 3         | 1.2%    |
| Chicony HP Wide Vision HD Camera                            | 3         | 1.2%    |
| Chicony HP HD Webcam [Fixed]                                | 3         | 1.2%    |
| Chicony HP HD Webcam                                        | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 3         | 1.2%    |
| Syntek Lenovo EasyCamera                                    | 2         | 0.8%    |
| Suyin Sony Visual Communication Camera                      | 2         | 0.8%    |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 0.8%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.8%    |
| Sunplus HP Universal Camera                                 | 2         | 0.8%    |
| Sunplus HP HD Webcam [Fixed]                                | 2         | 0.8%    |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 0.8%    |
| Realtek Integrated Webcam_HD                                | 2         | 0.8%    |
| Realtek Integrated Webcam HD                                | 2         | 0.8%    |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 0.8%    |
| Luxvisions Innotech Limited HP HD Camera                    | 2         | 0.8%    |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 0.8%    |
| IMC Networks Integrated Webcam                              | 2         | 0.8%    |
| IMC Networks HP TrueVision HD Camera                        | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 66.04%  |
| Synaptics                  | 9         | 16.98%  |
| Elan Microelectronics      | 4         | 7.55%   |
| Upek                       | 2         | 3.77%   |
| Shenzhen Goodix Technology | 2         | 3.77%   |
| Focal-systems.Corp         | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 22.64%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 11.32%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 11.32%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 9.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 9.43%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.66%   |
| Validity Sensors VFS491                                                    | 2         | 3.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.77%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.77%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.77%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.89%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.89%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.89%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.89%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 1.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 27        | 64.29%  |
| Alcor Micro | 10        | 23.81%  |
| O2 Micro    | 4         | 9.52%   |
| Lenovo      | 1         | 2.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 26.19%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 23.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 14.29%  |
| Broadcom 5880                                                                | 6         | 14.29%  |
| Broadcom 58200                                                               | 4         | 9.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.76%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 166       | 56.46%  |
| 1     | 98        | 33.33%  |
| 2     | 24        | 8.16%   |
| 3     | 4         | 1.36%   |
| 5     | 2         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 32.12%  |
| Chipcard                 | 35        | 21.21%  |
| Graphics card            | 33        | 20%     |
| Net/wireless             | 13        | 7.88%   |
| Storage                  | 6         | 3.64%   |
| Camera                   | 6         | 3.64%   |
| Bluetooth                | 6         | 3.64%   |
| Communication controller | 4         | 2.42%   |
| Sound                    | 3         | 1.82%   |
| Net/ethernet             | 2         | 1.21%   |
| Unassigned class         | 1         | 0.61%   |
| Network                  | 1         | 0.61%   |
| Multimedia controller    | 1         | 0.61%   |
| Modem                    | 1         | 0.61%   |

