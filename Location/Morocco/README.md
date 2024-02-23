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

Total: 457

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 312A NOK                    | Desktop     | [366174cd75](https://linux-hardware.org/?probe=366174cd75) | Feb 02, 2024 |
| HP            | 15                          | Notebook    | [b99530abd5](https://linux-hardware.org/?probe=b99530abd5) | Feb 01, 2024 |
| HP            | 15                          | Notebook    | [874ae10280](https://linux-hardware.org/?probe=874ae10280) | Feb 01, 2024 |
| HP            | 620                         | Notebook    | [adcf9577e4](https://linux-hardware.org/?probe=adcf9577e4) | Feb 01, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [e65c871d95](https://linux-hardware.org/?probe=e65c871d95) | Jan 31, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [1433f11bba](https://linux-hardware.org/?probe=1433f11bba) | Jan 31, 2024 |
| Dell          | 02K9CR A01                  | Desktop     | [72df486f35](https://linux-hardware.org/?probe=72df486f35) | Jan 31, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [4cb29324fc](https://linux-hardware.org/?probe=4cb29324fc) | Jan 30, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [dea06ca305](https://linux-hardware.org/?probe=dea06ca305) | Jan 30, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [83eec08588](https://linux-hardware.org/?probe=83eec08588) | Jan 30, 2024 |
| Sony          | VPCF12A4E                   | Notebook    | [66fb5f96a0](https://linux-hardware.org/?probe=66fb5f96a0) | Jan 30, 2024 |
| HP            | ProBook 6560b               | Notebook    | [7b9f78e8df](https://linux-hardware.org/?probe=7b9f78e8df) | Jan 23, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [ea1922427f](https://linux-hardware.org/?probe=ea1922427f) | Jan 19, 2024 |
| Dell          | Latitude 7390               | Notebook    | [837b633afe](https://linux-hardware.org/?probe=837b633afe) | Jan 14, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [106a150b97](https://linux-hardware.org/?probe=106a150b97) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [f6b222e444](https://linux-hardware.org/?probe=f6b222e444) | Jan 06, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [0af2ce345e](https://linux-hardware.org/?probe=0af2ce345e) | Jan 06, 2024 |
| HP            | ZBook Studio G3             | Notebook    | [21b560e443](https://linux-hardware.org/?probe=21b560e443) | Jan 04, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [a6ba47a6e6](https://linux-hardware.org/?probe=a6ba47a6e6) | Jan 01, 2024 |
| HP            | 18E7                        | Desktop     | [f5115e035f](https://linux-hardware.org/?probe=f5115e035f) | Dec 30, 2023 |
| Dell          | Latitude E5470              | Notebook    | [71121b89c8](https://linux-hardware.org/?probe=71121b89c8) | Dec 25, 2023 |
| HP            | 090Ch                       | Desktop     | [06e9f893bc](https://linux-hardware.org/?probe=06e9f893bc) | Dec 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [3441aa81e6](https://linux-hardware.org/?probe=3441aa81e6) | Dec 23, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [cdbe6b267f](https://linux-hardware.org/?probe=cdbe6b267f) | Dec 19, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [6fc9570e4f](https://linux-hardware.org/?probe=6fc9570e4f) | Dec 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [73c69f2b50](https://linux-hardware.org/?probe=73c69f2b50) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [4053f6be95](https://linux-hardware.org/?probe=4053f6be95) | Dec 12, 2023 |
| HP            | 18E7                        | Desktop     | [dad5884f78](https://linux-hardware.org/?probe=dad5884f78) | Dec 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [04ed98dd4a](https://linux-hardware.org/?probe=04ed98dd4a) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| HP            | 3031h                       | Desktop     | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e62aa2185a](https://linux-hardware.org/?probe=e62aa2185a) | Dec 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [4282694224](https://linux-hardware.org/?probe=4282694224) | Dec 01, 2023 |
| Dell          | OptiPlex 745                | Desktop     | [1abbad3f94](https://linux-hardware.org/?probe=1abbad3f94) | Nov 23, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [8b3abafe9b](https://linux-hardware.org/?probe=8b3abafe9b) | Nov 19, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [8cc0e1c14d](https://linux-hardware.org/?probe=8cc0e1c14d) | Nov 09, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [db3f0ac717](https://linux-hardware.org/?probe=db3f0ac717) | Oct 31, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| LG Electro... | R310-K.AP31B                | Notebook    | [ac3922c573](https://linux-hardware.org/?probe=ac3922c573) | Oct 24, 2023 |
| HP            | 1998                        | Desktop     | [d37c482ca8](https://linux-hardware.org/?probe=d37c482ca8) | Oct 19, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [a5a8709f77](https://linux-hardware.org/?probe=a5a8709f77) | Oct 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | Notebook    | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [e66ff52b09](https://linux-hardware.org/?probe=e66ff52b09) | Oct 13, 2023 |
| HP            | 18E4                        | Desktop     | [6707337e0c](https://linux-hardware.org/?probe=6707337e0c) | Oct 03, 2023 |
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
| Ubuntu 20.04       | 43        | 12.43%  |
| Ubuntu 22.04       | 32        | 9.25%   |
| Ubuntu 18.04       | 17        | 4.91%   |
| Debian 11          | 14        | 4.05%   |
| OpenMandriva 4.2   | 12        | 3.47%   |
| KDE neon 20.04     | 11        | 3.18%   |
| OpenMandriva 4.3   | 10        | 2.89%   |
| Pop!_OS 22.04      | 7         | 2.02%   |
| Linux Mint 20.2    | 7         | 2.02%   |
| Fedora 38          | 7         | 2.02%   |
| Arch Rolling       | 7         | 2.02%   |
| Zorin 16           | 6         | 1.73%   |
| OpenMandriva 23.01 | 6         | 1.73%   |
| Ubuntu Unity 16.04 | 5         | 1.45%   |
| Ubuntu 20.10       | 5         | 1.45%   |
| OpenMandriva 4.50  | 5         | 1.45%   |
| Linux Mint 20.3    | 5         | 1.45%   |
| Fedora 33          | 5         | 1.45%   |
| ArcoLinux Rolling  | 5         | 1.45%   |
| Xero Rolling       | 4         | 1.16%   |
| Ubuntu 19.10       | 4         | 1.16%   |
| Linux Mint 21      | 4         | 1.16%   |
| Debian 12          | 4         | 1.16%   |
| Arch               | 4         | 1.16%   |
| Manjaro            | 3         | 0.87%   |
| Linux Mint 21.1    | 3         | 0.87%   |
| Linux Mint 19.3    | 3         | 0.87%   |
| Kali 2023.3        | 3         | 0.87%   |
| Fedora 39          | 3         | 0.87%   |
| Zorin 17           | 2         | 0.58%   |
| Zorin 15           | 2         | 0.58%   |
| Xubuntu 20.04      | 2         | 0.58%   |
| Void Linux         | 2         | 0.58%   |
| Ubuntu 23.04       | 2         | 0.58%   |
| Ubuntu 21.10       | 2         | 0.58%   |
| Ubuntu 21.04       | 2         | 0.58%   |
| Ubuntu 16.04       | 2         | 0.58%   |
| Pop!_OS 21.10      | 2         | 0.58%   |
| Pop!_OS 21.04      | 2         | 0.58%   |
| Pop!_OS 20.10      | 2         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 105       | 32.31%  |
| OpenMandriva | 36        | 11.08%  |
| Linux Mint   | 23        | 7.08%   |
| Fedora       | 21        | 6.46%   |
| Debian       | 19        | 5.85%   |
| Pop!_OS      | 13        | 4%      |
| KDE neon     | 13        | 4%      |
| Kali         | 12        | 3.69%   |
| Zorin        | 10        | 3.08%   |
| Arch         | 10        | 3.08%   |
| Manjaro      | 7         | 2.15%   |
| Ubuntu Unity | 6         | 1.85%   |
| ArcoLinux    | 5         | 1.54%   |
| Xero         | 4         | 1.23%   |
| Elementary   | 4         | 1.23%   |
| Xubuntu      | 3         | 0.92%   |
| Ubuntu MATE  | 3         | 0.92%   |
| Endless      | 3         | 0.92%   |
| Void Linux   | 2         | 0.62%   |
| SteamOS      | 2         | 0.62%   |
| Raspbian     | 2         | 0.62%   |
| Parrot       | 2         | 0.62%   |
| openSUSE     | 2         | 0.62%   |
| Nobara       | 2         | 0.62%   |
| Lubuntu      | 2         | 0.62%   |
| EndeavourOS  | 2         | 0.62%   |
| BlackPanther | 2         | 0.62%   |
| ROSA         | 1         | 0.31%   |
| RHEL         | 1         | 0.31%   |
| Pear OS      | 1         | 0.31%   |
| LMDE         | 1         | 0.31%   |
| Linux Lite   | 1         | 0.31%   |
| Kubuntu      | 1         | 0.31%   |
| CentOS       | 1         | 0.31%   |
| BunsenLabs   | 1         | 0.31%   |
| blendOS      | 1         | 0.31%   |
| Android      | 1         | 0.31%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 12        | 3.3%    |
| 5.16.7-desktop-1omv4003  | 11        | 3.02%   |
| 6.1.1-desktop-1omv2290   | 6         | 1.65%   |
| 6.2.0-33-generic         | 5         | 1.37%   |
| 5.4.0-58-generic         | 5         | 1.37%   |
| 5.4.0-48-generic         | 5         | 1.37%   |
| 5.13.0-40-generic        | 5         | 1.37%   |
| 5.8.0-43-generic         | 4         | 1.1%    |
| 5.4.0-42-generic         | 4         | 1.1%    |
| 5.12.4-desktop-1omv4050  | 4         | 1.1%    |
| 5.11.0-37-generic        | 4         | 1.1%    |
| 6.5.0-15-generic         | 3         | 0.82%   |
| 6.5.0-14-generic         | 3         | 0.82%   |
| 6.4.11-desktop-1omv2390  | 3         | 0.82%   |
| 6.2.0-37-generic         | 3         | 0.82%   |
| 5.8.0-38-generic         | 3         | 0.82%   |
| 5.3.0-40-generic         | 3         | 0.82%   |
| 5.19.0-41-generic        | 3         | 0.82%   |
| 5.19.0-38-generic        | 3         | 0.82%   |
| 5.17.5-76051705-generic  | 3         | 0.82%   |
| 5.15.0-58-generic        | 3         | 0.82%   |
| 5.15.0-52-generic        | 3         | 0.82%   |
| 5.15.0-46-generic        | 3         | 0.82%   |
| 5.15.0-41-generic        | 3         | 0.82%   |
| 5.13.0-27-generic        | 3         | 0.82%   |
| 5.10.0-21-amd64          | 3         | 0.82%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.55%   |
| 6.2.6-76060206-generic   | 2         | 0.55%   |
| 6.2.14-300.fc38.x86_64   | 2         | 0.55%   |
| 6.1.0-9-amd64            | 2         | 0.55%   |
| 5.8.0-48-generic         | 2         | 0.55%   |
| 5.8.0-33-generic         | 2         | 0.55%   |
| 5.4.0-96-generic         | 2         | 0.55%   |
| 5.4.0-90-generic         | 2         | 0.55%   |
| 5.4.0-88-generic         | 2         | 0.55%   |
| 5.4.0-74-generic         | 2         | 0.55%   |
| 5.4.0-65-generic         | 2         | 0.55%   |
| 5.4.0-59-generic         | 2         | 0.55%   |
| 5.4.0-37-generic         | 2         | 0.55%   |
| 5.4.0-33-generic         | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 11.82%  |
| 5.15.0  | 34        | 9.8%    |
| 5.8.0   | 18        | 5.19%   |
| 5.11.0  | 17        | 4.9%    |
| 4.15.0  | 17        | 4.9%    |
| 5.10.0  | 15        | 4.32%   |
| 5.13.0  | 14        | 4.03%   |
| 6.2.0   | 12        | 3.46%   |
| 5.3.0   | 12        | 3.46%   |
| 5.10.14 | 12        | 3.46%   |
| 5.16.7  | 11        | 3.17%   |
| 5.19.0  | 10        | 2.88%   |
| 6.5.0   | 9         | 2.59%   |
| 6.1.0   | 7         | 2.02%   |
| 6.1.1   | 6         | 1.73%   |
| 5.0.0   | 6         | 1.73%   |
| 5.12.4  | 4         | 1.15%   |
| 4.18.0  | 4         | 1.15%   |
| 6.4.11  | 3         | 0.86%   |
| 6.2.9   | 3         | 0.86%   |
| 6.2.6   | 3         | 0.86%   |
| 5.17.5  | 3         | 0.86%   |
| 5.14.0  | 3         | 0.86%   |
| 4.19.0  | 3         | 0.86%   |
| 6.5.5   | 2         | 0.58%   |
| 6.4.6   | 2         | 0.58%   |
| 6.4.10  | 2         | 0.58%   |
| 6.2.14  | 2         | 0.58%   |
| 6.0.0   | 2         | 0.58%   |
| 5.18.19 | 2         | 0.58%   |
| 5.16.0  | 2         | 0.58%   |
| 5.14.14 | 2         | 0.58%   |
| 6.6.9   | 1         | 0.29%   |
| 6.6.8   | 1         | 0.29%   |
| 6.6.7   | 1         | 0.29%   |
| 6.6.5   | 1         | 0.29%   |
| 6.6.4   | 1         | 0.29%   |
| 6.6.1   | 1         | 0.29%   |
| 6.5.9   | 1         | 0.29%   |
| 6.5.8   | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 11.85%  |
| 5.15    | 41        | 11.85%  |
| 5.10    | 33        | 9.54%   |
| 6.2     | 21        | 6.07%   |
| 5.8     | 21        | 6.07%   |
| 5.11    | 20        | 5.78%   |
| 4.15    | 17        | 4.91%   |
| 5.13    | 16        | 4.62%   |
| 6.5     | 15        | 4.34%   |
| 6.1     | 15        | 4.34%   |
| 5.19    | 14        | 4.05%   |
| 5.16    | 14        | 4.05%   |
| 5.3     | 12        | 3.47%   |
| 6.4     | 8         | 2.31%   |
| 6.6     | 6         | 1.73%   |
| 6.3     | 6         | 1.73%   |
| 5.17    | 6         | 1.73%   |
| 5.14    | 6         | 1.73%   |
| 5.0     | 6         | 1.73%   |
| 5.18    | 5         | 1.45%   |
| 4.18    | 5         | 1.45%   |
| 6.0     | 4         | 1.16%   |
| 5.12    | 4         | 1.16%   |
| 4.19    | 3         | 0.87%   |
| 5.7     | 1         | 0.29%   |
| 5.6     | 1         | 0.29%   |
| 4.9     | 1         | 0.29%   |
| 4.4     | 1         | 0.29%   |
| 4.14    | 1         | 0.29%   |
| 4.13    | 1         | 0.29%   |
| 3.18    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 304       | 95.6%   |
| i686   | 11        | 3.46%   |
| armv8l | 1         | 0.31%   |
| armv7l | 1         | 0.31%   |
| armv6l | 1         | 0.31%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 165       | 50.15%  |
| KDE5            | 68        | 20.67%  |
| Unknown         | 19        | 5.78%   |
| XFCE            | 18        | 5.47%   |
| X-Cinnamon      | 17        | 5.17%   |
| KDE             | 9         | 2.74%   |
| Unity           | 6         | 1.82%   |
| MATE            | 6         | 1.82%   |
| Pantheon        | 4         | 1.22%   |
| LXDE            | 3         | 0.91%   |
| i3              | 3         | 0.91%   |
| Cinnamon        | 3         | 0.91%   |
| GNOME Flashback | 2         | 0.61%   |
| xmonad          | 1         | 0.3%    |
| sway            | 1         | 0.3%    |
| qtile           | 1         | 0.3%    |
| LXQt            | 1         | 0.3%    |
| KDE4            | 1         | 0.3%    |
| Budgie          | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 237       | 72.04%  |
| Wayland | 78        | 23.71%  |
| Unknown | 10        | 3.04%   |
| Tty     | 4         | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 142       | 42.51%  |
| SDDM    | 63        | 18.86%  |
| GDM3    | 48        | 14.37%  |
| GDM     | 40        | 11.98%  |
| LightDM | 36        | 10.78%  |
| TDM     | 4         | 1.2%    |
| KDM     | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 179       | 55.59%  |
| fr_FR   | 91        | 28.26%  |
| Unknown | 20        | 6.21%   |
| en_GB   | 14        | 4.35%   |
| C       | 4         | 1.24%   |
| de_DE   | 3         | 0.93%   |
| en_AG   | 2         | 0.62%   |
| ar_MA   | 2         | 0.62%   |
| it_IT   | 1         | 0.31%   |
| fr_MA   | 1         | 0.31%   |
| fr_CH   | 1         | 0.31%   |
| fr_BE   | 1         | 0.31%   |
| es_ES   | 1         | 0.31%   |
| ar_EG   | 1         | 0.31%   |
| ar_DZ   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 191       | 59.69%  |
| EFI  | 129       | 40.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 240       | 74.77%  |
| Overlay | 36        | 11.21%  |
| Btrfs   | 28        | 8.72%   |
| Tmpfs   | 9         | 2.8%    |
| Unknown | 5         | 1.56%   |
| Xfs     | 3         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 148       | 45.96%  |
| GPT     | 118       | 36.65%  |
| MBR     | 56        | 17.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 271       | 84.95%  |
| Yes       | 48        | 15.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 202       | 62.73%  |
| Yes       | 120       | 37.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 114       | 35.96%  |
| Dell                    | 54        | 17.03%  |
| Lenovo                  | 48        | 15.14%  |
| ASUSTek Computer        | 28        | 8.83%   |
| Acer                    | 10        | 3.15%   |
| Toshiba                 | 9         | 2.84%   |
| Apple                   | 5         | 1.58%   |
| Sony                    | 4         | 1.26%   |
| Foxconn                 | 4         | 1.26%   |
| Packard Bell            | 3         | 0.95%   |
| Unknown                 | 3         | 0.95%   |
| Timi                    | 2         | 0.63%   |
| Samsung Electronics     | 2         | 0.63%   |
| Raspberry Pi Foundation | 2         | 0.63%   |
| Medion                  | 2         | 0.63%   |
| HUAWEI                  | 2         | 0.63%   |
| Gigabyte Technology     | 2         | 0.63%   |
| eMachines               | 2         | 0.63%   |
| American Megatrends     | 2         | 0.63%   |
| Valve                   | 1         | 0.32%   |
| TUXEDO                  | 1         | 0.32%   |
| TrekStor                | 1         | 0.32%   |
| Thomson                 | 1         | 0.32%   |
| SINTRONES               | 1         | 0.32%   |
| Razer                   | 1         | 0.32%   |
| Pegatron                | 1         | 0.32%   |
| MSI                     | 1         | 0.32%   |
| Mediacom                | 1         | 0.32%   |
| Linx                    | 1         | 0.32%   |
| LG Electronics          | 1         | 0.32%   |
| GPD                     | 1         | 0.32%   |
| Google                  | 1         | 0.32%   |
| Fujitsu Siemens         | 1         | 0.32%   |
| Fujitsu                 | 1         | 0.32%   |
| ECS                     | 1         | 0.32%   |
| Clevo                   | 1         | 0.32%   |
| Casper                  | 1         | 0.32%   |
| ASRock                  | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP ProDesk 600 G1 TWR                  | 4         | 1.26%   |
| HP EliteBook 8440p                     | 4         | 1.26%   |
| Unknown                                | 4         | 1.26%   |
| HP Pavilion g6                         | 3         | 0.95%   |
| HP Laptop 15-dw3xxx                    | 3         | 0.95%   |
| HP EliteDesk 800 G1 SFF                | 3         | 0.95%   |
| HP EliteBook 840 G3                    | 3         | 0.95%   |
| HP EliteBook 840 G2                    | 3         | 0.95%   |
| ASUS X540LA                            | 3         | 0.95%   |
| Timi TM1701                            | 2         | 0.63%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.63%   |
| Lenovo IdeaPad L3 15IML05 81Y3         | 2         | 0.63%   |
| HP ZBook 15                            | 2         | 0.63%   |
| HP Z620 Workstation                    | 2         | 0.63%   |
| HP ProBook 650 G1                      | 2         | 0.63%   |
| HP ProBook 6470b                       | 2         | 0.63%   |
| HP ProBook 640 G1                      | 2         | 0.63%   |
| HP Pavilion 15                         | 2         | 0.63%   |
| HP Notebook                            | 2         | 0.63%   |
| HP EliteDesk 800 G1 TWR                | 2         | 0.63%   |
| HP EliteBook 8460p                     | 2         | 0.63%   |
| HP EliteBook 830 G5                    | 2         | 0.63%   |
| HP Compaq Elite 8300 SFF               | 2         | 0.63%   |
| HP Compaq Elite 8300 CMT               | 2         | 0.63%   |
| HP Compaq dc7900 Small Form Factor     | 2         | 0.63%   |
| HP Compaq dc7800 Convertible Minitower | 2         | 0.63%   |
| HP Compaq 8200 Elite CMT PC            | 2         | 0.63%   |
| HP 250 G5 Notebook PC                  | 2         | 0.63%   |
| Dell OptiPlex 790                      | 2         | 0.63%   |
| Dell Latitude E7450                    | 2         | 0.63%   |
| Dell Latitude E6520                    | 2         | 0.63%   |
| Dell Latitude E6410                    | 2         | 0.63%   |
| ASUS X555LD                            | 2         | 0.63%   |
| Acer Aspire ES1-523                    | 2         | 0.63%   |
| Valve Jupiter                          | 1         | 0.32%   |
| TUXEDO N13xWU                          | 1         | 0.32%   |
| TrekStor Surfbook W2                   | 1         | 0.32%   |
| Toshiba Satellite Pro L300             | 1         | 0.32%   |
| Toshiba Satellite Pro C650             | 1         | 0.32%   |
| Toshiba Satellite L750                 | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 32        | 10.09%  |
| Lenovo ThinkPad       | 26        | 8.2%    |
| HP EliteBook          | 22        | 6.94%   |
| HP Compaq             | 18        | 5.68%   |
| HP ProBook            | 12        | 3.79%   |
| HP Pavilion           | 11        | 3.47%   |
| Toshiba Satellite     | 9         | 2.84%   |
| HP Laptop             | 9         | 2.84%   |
| Dell OptiPlex         | 8         | 2.52%   |
| HP ProDesk            | 7         | 2.21%   |
| Acer Aspire           | 7         | 2.21%   |
| Lenovo IdeaPad        | 6         | 1.89%   |
| HP EliteDesk          | 6         | 1.89%   |
| Dell Precision        | 6         | 1.89%   |
| HP 250                | 5         | 1.58%   |
| Lenovo ThinkCentre    | 4         | 1.26%   |
| HP ZBook              | 4         | 1.26%   |
| ASUS ROG              | 4         | 1.26%   |
| Unknown               | 4         | 1.26%   |
| Packard Bell EasyNote | 3         | 0.95%   |
| Lenovo ThinkBook      | 3         | 0.95%   |
| Dell Vostro           | 3         | 0.95%   |
| Dell Inspiron         | 3         | 0.95%   |
| ASUS X540LA           | 3         | 0.95%   |
| Timi TM1701           | 2         | 0.63%   |
| RPi Raspberry         | 2         | 0.63%   |
| Lenovo ThinkStation   | 2         | 0.63%   |
| HP Z620               | 2         | 0.63%   |
| HP Notebook           | 2         | 0.63%   |
| HP dc5000             | 2         | 0.63%   |
| Dell XPS              | 2         | 0.63%   |
| ASUS X555LD           | 2         | 0.63%   |
| ASUS PRIME            | 2         | 0.63%   |
| Valve Jupiter         | 1         | 0.32%   |
| TUXEDO N13xWU         | 1         | 0.32%   |
| TrekStor Surfbook     | 1         | 0.32%   |
| Thomson N14C4WH64     | 1         | 0.32%   |
| Sony VPCF12A4E        | 1         | 0.32%   |
| Sony VPCEH1L8E        | 1         | 0.32%   |
| Sony VGN-FW11L        | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 37        | 11.67%  |
| 2011    | 30        | 9.46%   |
| 2018    | 29        | 9.15%   |
| 2010    | 26        | 8.2%    |
| 2014    | 24        | 7.57%   |
| 2016    | 23        | 7.26%   |
| 2012    | 23        | 7.26%   |
| 2020    | 19        | 5.99%   |
| 2015    | 19        | 5.99%   |
| 2017    | 17        | 5.36%   |
| 2021    | 15        | 4.73%   |
| 2019    | 15        | 4.73%   |
| 2007    | 10        | 3.15%   |
| 2008    | 9         | 2.84%   |
| 2009    | 8         | 2.52%   |
| 2022    | 3         | 0.95%   |
| 2006    | 3         | 0.95%   |
| 2004    | 3         | 0.95%   |
| Unknown | 2         | 0.63%   |
| 2023    | 1         | 0.32%   |
| 2005    | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 228       | 71.92%  |
| Desktop        | 78        | 24.61%  |
| Convertible    | 6         | 1.89%   |
| System on chip | 2         | 0.63%   |
| Phone          | 1         | 0.32%   |
| Tablet         | 1         | 0.32%   |
| All in one     | 1         | 0.32%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 302       | 93.79%  |
| Enabled  | 20        | 6.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 315       | 99.37%  |
| Yes  | 2         | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 106       | 33.02%  |
| 3.01-4.0    | 78        | 24.3%   |
| 16.01-24.0  | 42        | 13.08%  |
| 8.01-16.0   | 41        | 12.77%  |
| 1.01-2.0    | 21        | 6.54%   |
| 32.01-64.0  | 11        | 3.43%   |
| 24.01-32.0  | 7         | 2.18%   |
| 2.01-3.0    | 7         | 2.18%   |
| 64.01-256.0 | 5         | 1.56%   |
| 0.51-1.0    | 2         | 0.62%   |
| 0.01-0.5    | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 125       | 36.13%  |
| 2.01-3.0  | 107       | 30.92%  |
| 4.01-8.0  | 46        | 13.29%  |
| 3.01-4.0  | 44        | 12.72%  |
| 0.51-1.0  | 18        | 5.2%    |
| 8.01-16.0 | 4         | 1.16%   |
| 0.01-0.5  | 2         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 241       | 75.08%  |
| 2      | 62        | 19.31%  |
| 3      | 15        | 4.67%   |
| 4      | 3         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 52.68%  |
| Yes       | 150       | 47.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 284       | 89.59%  |
| No        | 33        | 10.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 281       | 88.36%  |
| No        | 37        | 11.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 60%     |
| No        | 128       | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Morocco | 317       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Casablanca    | 85        | 24.85%  |
| Marrakesh     | 33        | 9.65%   |
| Fes           | 28        | 8.19%   |
| Rabat         | 27        | 7.89%   |
| Agadir        | 25        | 7.31%   |
| Tangier       | 19        | 5.56%   |
| Salé         | 16        | 4.68%   |
| Kenitra       | 15        | 4.39%   |
| Oujda         | 12        | 3.51%   |
| Meknes        | 12        | 3.51%   |
| Khouribga     | 7         | 2.05%   |
| Nador         | 5         | 1.46%   |
| Tiznit        | 4         | 1.17%   |
| El Jadida     | 4         | 1.17%   |
| Temara        | 3         | 0.88%   |
| Taza          | 3         | 0.88%   |
| Beni Mellal   | 3         | 0.88%   |
| Youssoufia    | 2         | 0.58%   |
| Tétouan      | 2         | 0.58%   |
| Skhirate      | 2         | 0.58%   |
| Safi          | 2         | 0.58%   |
| Mohammedia    | 2         | 0.58%   |
| Guelmim       | 2         | 0.58%   |
| Berrechid     | 2         | 0.58%   |
| Berkane       | 2         | 0.58%   |
| Tit Mellil    | 1         | 0.29%   |
| Taroudant     | 1         | 0.29%   |
| Targuist      | 1         | 0.29%   |
| Taourirt      | 1         | 0.29%   |
| Taounate      | 1         | 0.29%   |
| Sidi Slimane  | 1         | 0.29%   |
| Sidi Lmokhtar | 1         | 0.29%   |
| Sidi Kacem    | 1         | 0.29%   |
| Settat        | 1         | 0.29%   |
| Sefrou        | 1         | 0.29%   |
| Oulmes        | 1         | 0.29%   |
| Ouirgane      | 1         | 0.29%   |
| Midelt        | 1         | 0.29%   |
| Ksar El Kebir | 1         | 0.29%   |
| Khemisset     | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 62        | 80     | 15.86%  |
| WDC                         | 57        | 75     | 14.58%  |
| Samsung Electronics         | 53        | 67     | 13.55%  |
| Toshiba                     | 45        | 62     | 11.51%  |
| Hitachi                     | 24        | 29     | 6.14%   |
| Unknown                     | 19        | 25     | 4.86%   |
| HGST                        | 13        | 14     | 3.32%   |
| SanDisk                     | 11        | 11     | 2.81%   |
| Intel                       | 11        | 12     | 2.81%   |
| Kingston                    | 7         | 9      | 1.79%   |
| Apple                       | 7         | 7      | 1.79%   |
| SK hynix                    | 6         | 6      | 1.53%   |
| China                       | 6         | 7      | 1.53%   |
| Micron Technology           | 5         | 7      | 1.28%   |
| KIOXIA                      | 5         | 5      | 1.28%   |
| PNY                         | 4         | 5      | 1.02%   |
| LITEON                      | 4         | 4      | 1.02%   |
| Fujitsu                     | 4         | 4      | 1.02%   |
| Crucial                     | 4         | 5      | 1.02%   |
| Phison                      | 3         | 4      | 0.77%   |
| KingFast                    | 3         | 4      | 0.77%   |
| Unknown                     | 3         | 3      | 0.77%   |
| TwinMOS                     | 2         | 2      | 0.51%   |
| LITEONIT                    | 2         | 2      | 0.51%   |
| KingDian                    | 2         | 7      | 0.51%   |
| GOODRAM                     | 2         | 2      | 0.51%   |
| Transcend                   | 1         | 1      | 0.26%   |
| Supersonic                  | 1         | 2      | 0.26%   |
| SPCC                        | 1         | 2      | 0.26%   |
| ShiJi                       | 1         | 2      | 0.26%   |
| Realtek Semiconductor       | 1         | 1      | 0.26%   |
| RCESSD                      | 1         | 1      | 0.26%   |
| O2 Micro                    | 1         | 1      | 0.26%   |
| Mushkin                     | 1         | 1      | 0.26%   |
| MSI                         | 1         | 1      | 0.26%   |
| Maxtor                      | 1         | 1      | 0.26%   |
| Magnetic Data               | 1         | 1      | 0.26%   |
| Lexar                       | 1         | 1      | 0.26%   |
| Kingston Technology Company | 1         | 1      | 0.26%   |
| KingSpec                    | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                   | 6         | 1.46%   |
| Toshiba MQ04ABF100 1TB                            | 5         | 1.22%   |
| Toshiba MQ01ABF050 500GB                          | 5         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB                    | 5         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 5         | 1.22%   |
| Unknown MMC Card  32GB                            | 4         | 0.97%   |
| Toshiba MQ01ABD050 500GB                          | 4         | 0.97%   |
| Seagate ST500DM002-1BD142 500GB                   | 4         | 0.97%   |
| Samsung NVMe SSD Drive 512GB                      | 4         | 0.97%   |
| WDC WD5000AAKX-60U6AA0 500GB                      | 3         | 0.73%   |
| Unknown MMC Card  64GB                            | 3         | 0.73%   |
| Toshiba MQ01ACF050 500GB                          | 3         | 0.73%   |
| Toshiba MQ01ABD100 1TB                            | 3         | 0.73%   |
| Seagate ST9500325AS 500GB                         | 3         | 0.73%   |
| Seagate ST500LM000-1EJ162 500GB                   | 3         | 0.73%   |
| Seagate ST3250312AS 250GB                         | 3         | 0.73%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 3         | 0.73%   |
| Intel SSDSC2BF180A4H 180GB                        | 3         | 0.73%   |
| Hitachi HUA723020ALA641 2TB                       | 3         | 0.73%   |
| HGST HTS725050A7E630 500GB                        | 3         | 0.73%   |
| HGST HTS545050A7E680 500GB                        | 3         | 0.73%   |
| Unknown                                           | 3         | 0.73%   |
| WDC WD800JD-00LSA0 80GB                           | 2         | 0.49%   |
| WDC WD5000LPCX-80VHAT1 500GB                      | 2         | 0.49%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 2         | 0.49%   |
| WDC WD5000AZLX-60K2TA0 500GB                      | 2         | 0.49%   |
| WDC WD1600BEVT-22ZCT0 160GB                       | 2         | 0.49%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 2         | 0.49%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 2         | 0.49%   |
| Unknown MMC Card  16GB                            | 2         | 0.49%   |
| TwinMOS SSD 256GB                                 | 2         | 0.49%   |
| Toshiba MQ01ABD050V -63 500GB                     | 2         | 0.49%   |
| Toshiba KXG50ZNV256G 256GB                        | 2         | 0.49%   |
| Seagate ST500VT000-1DK142 500GB                   | 2         | 0.49%   |
| Seagate ST500LM021-1KJ152 500GB                   | 2         | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 2         | 0.49%   |
| Seagate ST250DM000-1BD141 250GB                   | 2         | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.49%   |
| Samsung MZVLW256HEHP-000L7 256GB                  | 2         | 0.49%   |
| Samsung MZVLB512HAJQ-000L7 512GB                  | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 80     | 30.39%  |
| WDC                 | 52        | 70     | 25.49%  |
| Toshiba             | 36        | 45     | 17.65%  |
| Hitachi             | 24        | 29     | 11.76%  |
| HGST                | 13        | 14     | 6.37%   |
| Samsung Electronics | 7         | 10     | 3.43%   |
| Fujitsu             | 4         | 4      | 1.96%   |
| Apple               | 2         | 2      | 0.98%   |
| Maxtor              | 1         | 1      | 0.49%   |
| Magnetic Data       | 1         | 1      | 0.49%   |
| IBM/Hitachi         | 1         | 1      | 0.49%   |
| HPE                 | 1         | 2      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 25     | 18.81%  |
| SanDisk             | 8         | 8      | 7.92%   |
| Kingston            | 6         | 8      | 5.94%   |
| Intel               | 6         | 7      | 5.94%   |
| China               | 6         | 7      | 5.94%   |
| Micron Technology   | 5         | 7      | 4.95%   |
| PNY                 | 4         | 5      | 3.96%   |
| LITEON              | 4         | 4      | 3.96%   |
| Crucial             | 4         | 5      | 3.96%   |
| SK hynix            | 3         | 3      | 2.97%   |
| KingFast            | 3         | 3      | 2.97%   |
| Apple               | 3         | 3      | 2.97%   |
| TwinMOS             | 2         | 2      | 1.98%   |
| Toshiba             | 2         | 2      | 1.98%   |
| LITEONIT            | 2         | 2      | 1.98%   |
| KingDian            | 2         | 7      | 1.98%   |
| GOODRAM             | 2         | 2      | 1.98%   |
| Unknown             | 2         | 2      | 1.98%   |
| WDC                 | 1         | 1      | 0.99%   |
| Transcend           | 1         | 1      | 0.99%   |
| Supersonic          | 1         | 2      | 0.99%   |
| SPCC                | 1         | 2      | 0.99%   |
| RCESSD              | 1         | 1      | 0.99%   |
| Mushkin             | 1         | 1      | 0.99%   |
| MSI                 | 1         | 1      | 0.99%   |
| Lexar               | 1         | 1      | 0.99%   |
| KingSpec            | 1         | 1      | 0.99%   |
| Indilinx            | 1         | 1      | 0.99%   |
| HS-SSD-E100         | 1         | 1      | 0.99%   |
| Hewlett-Packard     | 1         | 1      | 0.99%   |
| BIWIN               | 1         | 1      | 0.99%   |
| Bestoss             | 1         | 1      | 0.99%   |
| Apacer              | 1         | 1      | 0.99%   |
| AFOX                | 1         | 1      | 0.99%   |
| A-DATA Technology   | 1         | 1      | 0.99%   |
| 2.5"                | 1         | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 187       | 259    | 51.23%  |
| SSD     | 95        | 122    | 26.03%  |
| NVMe    | 61        | 78     | 16.71%  |
| MMC     | 19        | 25     | 5.21%   |
| Unknown | 3         | 6      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 258       | 383    | 75.88%  |
| NVMe | 61        | 78     | 17.94%  |
| MMC  | 19        | 25     | 5.59%   |
| SAS  | 2         | 4      | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 202       | 271    | 72.92%  |
| 0.51-1.0   | 63        | 93     | 22.74%  |
| 1.01-2.0   | 8         | 12     | 2.89%   |
| 2.01-3.0   | 2         | 3      | 0.72%   |
| 3.01-4.0   | 1         | 1      | 0.36%   |
| 4.01-10.0  | 1         | 1      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 101       | 30.7%   |
| 251-500        | 78        | 23.71%  |
| 51-100         | 37        | 11.25%  |
| 1-20           | 34        | 10.33%  |
| 501-1000       | 29        | 8.81%   |
| 21-50          | 24        | 7.29%   |
| 1001-2000      | 11        | 3.34%   |
| Unknown        | 7         | 2.13%   |
| More than 3000 | 6         | 1.82%   |
| 2001-3000      | 2         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 149       | 43.06%  |
| 21-50          | 81        | 23.41%  |
| 51-100         | 43        | 12.43%  |
| 101-250        | 39        | 11.27%  |
| 251-500        | 14        | 4.05%   |
| Unknown        | 7         | 2.02%   |
| More than 3000 | 4         | 1.16%   |
| 1001-2000      | 4         | 1.16%   |
| 501-1000       | 4         | 1.16%   |
| 2001-3000      | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB                         | 3         | 3      | 5.88%   |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB                  | 3         | 3      | 5.88%   |
| Seagate ST500LM021-1KJ152 500GB                  | 2         | 2      | 3.92%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 3.92%   |
| Hitachi HDS721680PLA380 80GB                     | 2         | 3      | 3.92%   |
| WDC WD800AAJS-60WAA0 80GB                        | 1         | 1      | 1.96%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 1.96%   |
| WDC WD2500BEVS-22UST0 250GB                      | 1         | 1      | 1.96%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 1.96%   |
| WDC WD2500AAJS-60Z0A0 250GB                      | 1         | 1      | 1.96%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.96%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 6      | 1.96%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 1.96%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 1.96%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 1.96%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 1.96%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 1.96%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 1.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 1.96%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 1.96%   |
| Seagate ST340016A 40GB                           | 1         | 1      | 1.96%   |
| Seagate ST340014AS 40GB                          | 1         | 1      | 1.96%   |
| Seagate ST3250312AS 250GB                        | 1         | 1      | 1.96%   |
| Seagate ST3160318AS 160GB                        | 1         | 1      | 1.96%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 1.96%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 1.96%   |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 1.96%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 1.96%   |
| Maxtor 6E040L0 40GB                              | 1         | 1      | 1.96%   |
| Kingston SA400S37480G 480GB SSD                  | 1         | 2      | 1.96%   |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 1.96%   |
| HPE MM1000GBKAL 1TB                              | 1         | 2      | 1.96%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 1.96%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 1.96%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 1.96%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 1.96%   |
| HGST HTS545032A7E660 320GB                       | 1         | 1      | 1.96%   |
| Fujitsu MHX2300BT 304GB                          | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 31.37%  |
| Toshiba             | 8         | 8      | 15.69%  |
| WDC                 | 7         | 12     | 13.73%  |
| Hitachi             | 6         | 8      | 11.76%  |
| HGST                | 3         | 3      | 5.88%   |
| Samsung Electronics | 2         | 2      | 3.92%   |
| Fujitsu             | 2         | 2      | 3.92%   |
| SanDisk             | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| Maxtor              | 1         | 1      | 1.96%   |
| Kingston            | 1         | 2      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| HPE                 | 1         | 2      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 34.78%  |
| Toshiba             | 8         | 8      | 17.39%  |
| WDC                 | 7         | 12     | 15.22%  |
| Hitachi             | 6         | 8      | 13.04%  |
| HGST                | 3         | 3      | 6.52%   |
| Fujitsu             | 2         | 2      | 4.35%   |
| Samsung Electronics | 1         | 1      | 2.17%   |
| Maxtor              | 1         | 1      | 2.17%   |
| HPE                 | 1         | 2      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 54     | 90%     |
| SSD  | 5         | 6      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD800JD-00LSA0 80GB                    | 2         | 3      | 50%     |
| WDC WD2500BEVT-22A23T0 250GB               | 1         | 2      | 25%     |
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
| Detected | 181       | 267    | 52.31%  |
| Works    | 111       | 157    | 32.08%  |
| Malfunc  | 50        | 60     | 14.45%  |
| Failed   | 4         | 6      | 1.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 256       | 73.99%  |
| Samsung Electronics              | 29        | 8.38%   |
| AMD                              | 23        | 6.65%   |
| Toshiba America Info Systems     | 7         | 2.02%   |
| SanDisk                          | 6         | 1.73%   |
| KIOXIA                           | 5         | 1.45%   |
| SK hynix                         | 3         | 0.87%   |
| Phison Electronics               | 3         | 0.87%   |
| Nvidia                           | 3         | 0.87%   |
| Silicon Integrated Systems [SiS] | 2         | 0.58%   |
| Kingston Technology Company      | 2         | 0.58%   |
| Realtek Semiconductor            | 1         | 0.29%   |
| O2 Micro                         | 1         | 0.29%   |
| LSI Logic / Symbios Logic        | 1         | 0.29%   |
| JMicron Technology               | 1         | 0.29%   |
| Broadcom / LSI                   | 1         | 0.29%   |
| Apple                            | 1         | 0.29%   |
| ADATA Technology                 | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 24        | 6.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24        | 6.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 23        | 5.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 18        | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17        | 4.29%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 15        | 3.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 14        | 3.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 3.54%   |
| Intel SATA Controller [RAID mode]                                                       | 13        | 3.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 2.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8         | 2.02%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.02%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8         | 2.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 2.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5         | 1.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.01%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4         | 1.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3         | 0.76%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 3         | 0.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 3         | 0.76%   |
| Intel SSD 660P Series                                                                   | 3         | 0.76%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3         | 0.76%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.51%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 0.51%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                   | 2         | 0.51%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.51%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.51%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 223       | 60.43%  |
| NVMe | 61        | 16.53%  |
| RAID | 45        | 12.2%   |
| IDE  | 36        | 9.76%   |
| SAS  | 3         | 0.81%   |
| SCSI | 1         | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 283       | 89.27%  |
| AMD    | 31        | 9.78%   |
| ARM    | 3         | 0.95%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 2.21%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 1.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6         | 1.89%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 1.89%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 1.89%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 5         | 1.58%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 5         | 1.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 1.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 1.58%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5         | 1.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 1.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 5         | 1.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.26%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 4         | 1.26%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.26%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 0.95%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 0.95%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.95%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 3         | 0.95%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 0.95%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 2         | 0.63%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 2         | 0.63%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.63%   |
| Intel Pentium 4 CPU 2.80GHz                 | 2         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.63%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 0.63%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 2         | 0.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 0.63%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 0.63%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.63%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 119       | 37.54%  |
| Intel Core i7           | 51        | 16.09%  |
| Intel Core i3           | 38        | 11.99%  |
| Intel Core 2 Duo        | 17        | 5.36%   |
| Other                   | 14        | 4.42%   |
| Intel Celeron           | 11        | 3.47%   |
| Intel Xeon              | 10        | 3.15%   |
| AMD Ryzen 5             | 7         | 2.21%   |
| Intel Atom              | 6         | 1.89%   |
| Intel Pentium Dual-Core | 4         | 1.26%   |
| AMD Ryzen 9             | 3         | 0.95%   |
| AMD Ryzen 7             | 3         | 0.95%   |
| AMD E1                  | 3         | 0.95%   |
| Intel Pentium 4         | 2         | 0.63%   |
| Intel Pentium           | 2         | 0.63%   |
| Intel Core 2            | 2         | 0.63%   |
| ARM BCM                 | 2         | 0.63%   |
| AMD C-60                | 2         | 0.63%   |
| AMD Athlon 64 X2        | 2         | 0.63%   |
| AMD A8                  | 2         | 0.63%   |
| AMD A6                  | 2         | 0.63%   |
| Intel Pentium Silver    | 1         | 0.32%   |
| Intel Pentium M         | 1         | 0.32%   |
| Intel Pentium Gold      | 1         | 0.32%   |
| Intel Pentium Dual      | 1         | 0.32%   |
| Intel Genuine           | 1         | 0.32%   |
| Intel Core i9           | 1         | 0.32%   |
| Intel Core 2 Quad       | 1         | 0.32%   |
| Intel Celeron M         | 1         | 0.32%   |
| ARM AArch64             | 1         | 0.32%   |
| AMD Ryzen 7 PRO         | 1         | 0.32%   |
| AMD Ryzen 3             | 1         | 0.32%   |
| AMD Phenom II X6        | 1         | 0.32%   |
| AMD E                   | 1         | 0.32%   |
| AMD Athlon XP           | 1         | 0.32%   |
| AMD A4                  | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 172       | 54.26%  |
| 4      | 109       | 34.38%  |
| 6      | 11        | 3.47%   |
| 1      | 9         | 2.84%   |
| 8      | 7         | 2.21%   |
| 12     | 4         | 1.26%   |
| 16     | 3         | 0.95%   |
| 10     | 2         | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 312       | 98.42%  |
| 2      | 5         | 1.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 216       | 68.14%  |
| 1      | 101       | 31.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 307       | 96.85%  |
| 32-bit         | 6         | 1.89%   |
| Unknown        | 4         | 1.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 30.98%  |
| 0x206a7    | 26        | 7.98%   |
| 0x306c3    | 19        | 5.83%   |
| 0x306a9    | 16        | 4.91%   |
| 0x306d4    | 14        | 4.29%   |
| 0x806ea    | 13        | 3.99%   |
| 0x40651    | 11        | 3.37%   |
| 0x806ec    | 10        | 3.07%   |
| 0x20655    | 9         | 2.76%   |
| 0x1067a    | 9         | 2.76%   |
| 0x806c1    | 7         | 2.15%   |
| 0x506e3    | 7         | 2.15%   |
| 0x806e9    | 6         | 1.84%   |
| 0x406e3    | 6         | 1.84%   |
| 0x6fd      | 5         | 1.53%   |
| 0x20652    | 5         | 1.53%   |
| 0x30678    | 4         | 1.23%   |
| 0x906e9    | 3         | 0.92%   |
| 0x6fb      | 3         | 0.92%   |
| 0x206d7    | 3         | 0.92%   |
| 0x10676    | 3         | 0.92%   |
| 0x0a50000c | 3         | 0.92%   |
| 0x08701021 | 3         | 0.92%   |
| 0x906ea    | 2         | 0.61%   |
| 0x706e5    | 2         | 0.61%   |
| 0x406c4    | 2         | 0.61%   |
| 0x406c3    | 2         | 0.61%   |
| 0x08108102 | 2         | 0.61%   |
| 0x07030105 | 2         | 0.61%   |
| 0x0700010f | 2         | 0.61%   |
| 0x05000119 | 2         | 0.61%   |
| 0xf41      | 1         | 0.31%   |
| 0xf29      | 1         | 0.31%   |
| 0xb06a3    | 1         | 0.31%   |
| 0x90675    | 1         | 0.31%   |
| 0x806eb    | 1         | 0.31%   |
| 0x806d1    | 1         | 0.31%   |
| 0x706a1    | 1         | 0.31%   |
| 0x6ec      | 1         | 0.31%   |
| 0x6e8      | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 49        | 15.46%  |
| KabyLake         | 48        | 15.14%  |
| SandyBridge      | 32        | 10.09%  |
| Skylake          | 25        | 7.89%   |
| Westmere         | 21        | 6.62%   |
| IvyBridge        | 21        | 6.62%   |
| Broadwell        | 18        | 5.68%   |
| Penryn           | 16        | 5.05%   |
| Silvermont       | 11        | 3.47%   |
| Core             | 11        | 3.47%   |
| TigerLake        | 9         | 2.84%   |
| Unknown          | 7         | 2.21%   |
| Zen 3            | 5         | 1.58%   |
| IceLake          | 5         | 1.58%   |
| Zen+             | 4         | 1.26%   |
| Zen 2            | 4         | 1.26%   |
| Bobcat           | 4         | 1.26%   |
| P6               | 3         | 0.95%   |
| Alderlake Hybrid | 3         | 0.95%   |
| Puma             | 2         | 0.63%   |
| NetBurst         | 2         | 0.63%   |
| Nehalem          | 2         | 0.63%   |
| K8 Hammer        | 2         | 0.63%   |
| Jaguar           | 2         | 0.63%   |
| Goldmont plus    | 2         | 0.63%   |
| Bonnell          | 2         | 0.63%   |
| Piledriver       | 1         | 0.32%   |
| K6               | 1         | 0.32%   |
| K10 Llano        | 1         | 0.32%   |
| K10              | 1         | 0.32%   |
| Goldmont         | 1         | 0.32%   |
| Excavator        | 1         | 0.32%   |
| CometLake        | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 246       | 66.49%  |
| Nvidia                           | 77        | 20.81%  |
| AMD                              | 46        | 12.43%  |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 6.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 5.05%   |
| Intel UHD Graphics 620                                                                   | 18        | 4.79%   |
| Intel HD Graphics 5500                                                                   | 16        | 4.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 4.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 3.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 3.19%   |
| Intel HD Graphics 530                                                                    | 11        | 2.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 2.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.66%   |
| Intel HD Graphics 620                                                                    | 9         | 2.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.33%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.8%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.8%    |
| Nvidia GM107GL [Quadro K2200]                                                            | 3         | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.8%    |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.8%    |
| Intel HD Graphics 630                                                                    | 3         | 0.8%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.8%    |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.53%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.53%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.53%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.53%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 2         | 0.53%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 189       | 59.43%  |
| Intel + Nvidia | 45        | 14.15%  |
| 1 x AMD        | 36        | 11.32%  |
| 1 x Nvidia     | 31        | 9.75%   |
| Intel + AMD    | 8         | 2.52%   |
| Other          | 3         | 0.94%   |
| 2 x Intel      | 2         | 0.63%   |
| 2 x Nvidia     | 1         | 0.31%   |
| 2 x AMD        | 1         | 0.31%   |
| 1 x SiS        | 1         | 0.31%   |
| AMD + Nvidia   | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 273       | 84.78%  |
| Proprietary | 35        | 10.87%  |
| Unknown     | 14        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 225       | 69.44%  |
| 1.01-2.0   | 36        | 11.11%  |
| 0.01-0.5   | 31        | 9.57%   |
| 3.01-4.0   | 15        | 4.63%   |
| 0.51-1.0   | 13        | 4.01%   |
| 7.01-8.0   | 3         | 0.93%   |
| 2.01-3.0   | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 45        | 14.71%  |
| Samsung Electronics     | 44        | 14.38%  |
| AU Optronics            | 44        | 14.38%  |
| Chimei Innolux          | 41        | 13.4%   |
| BOE                     | 31        | 10.13%  |
| Dell                    | 18        | 5.88%   |
| Hewlett-Packard         | 17        | 5.56%   |
| InfoVision              | 8         | 2.61%   |
| Lenovo                  | 6         | 1.96%   |
| Goldstar                | 6         | 1.96%   |
| Apple                   | 5         | 1.63%   |
| LG Philips              | 4         | 1.31%   |
| Chi Mei Optoelectronics | 4         | 1.31%   |
| Sharp                   | 3         | 0.98%   |
| Iiyama                  | 3         | 0.98%   |
| BenQ                    | 3         | 0.98%   |
| Acer                    | 3         | 0.98%   |
| Philips                 | 2         | 0.65%   |
| MSI                     | 2         | 0.65%   |
| Fujitsu Siemens         | 2         | 0.65%   |
| Ancor Communications    | 2         | 0.65%   |
| Valve                   | 1         | 0.33%   |
| TMX                     | 1         | 0.33%   |
| Sony                    | 1         | 0.33%   |
| RTK                     | 1         | 0.33%   |
| PANDA                   | 1         | 0.33%   |
| NEC Computers           | 1         | 0.33%   |
| NCS                     | 1         | 0.33%   |
| MiTAC                   | 1         | 0.33%   |
| Medion                  | 1         | 0.33%   |
| LGD                     | 1         | 0.33%   |
| IBM                     | 1         | 0.33%   |
| CNC                     | 1         | 0.33%   |
| Unknown                 | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 1.3%    |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 3         | 0.97%   |
| Dell E2414H DEL4090 1920x1080 531x299mm 24.0-inch                        | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 0.97%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.65%   |
| MSI G24C6 MSI3BA0 1920x1080 521x293mm 23.5-inch                          | 2         | 0.65%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.65%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 0.65%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.65%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 2         | 0.65%   |
| InfoVision LCD Monitor IVO0535 1920x1080 294x165mm 13.3-inch             | 2         | 0.65%   |
| Hewlett-Packard 25x HPN357E 1920x1080 544x303mm 24.5-inch                | 2         | 0.65%   |
| Dell E198FP DELA028 1280x1024 380x305mm 19.2-inch                        | 2         | 0.65%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.65%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                    | 2         | 0.65%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 2         | 0.65%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.65%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.32%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.32%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.32%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP14A8 3840x2400 288x180mm 13.4-inch                  | 1         | 0.32%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch     | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch     | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 106       | 35.57%  |
| 1920x1080 (FHD)    | 105       | 35.23%  |
| 1600x900 (HD+)     | 21        | 7.05%   |
| 1680x1050 (WSXGA+) | 10        | 3.36%   |
| 1440x900 (WXGA+)   | 10        | 3.36%   |
| 1280x1024 (SXGA)   | 10        | 3.36%   |
| 3840x2160 (4K)     | 8         | 2.68%   |
| 1280x800 (WXGA)    | 8         | 2.68%   |
| 2560x1440 (QHD)    | 3         | 1.01%   |
| 1024x600           | 3         | 1.01%   |
| 3840x2400          | 2         | 0.67%   |
| 1920x1200 (WUXGA)  | 2         | 0.67%   |
| 800x1280           | 1         | 0.34%   |
| 2880x1800          | 1         | 0.34%   |
| 2560x1600          | 1         | 0.34%   |
| 2520x1680          | 1         | 0.34%   |
| 1680x945           | 1         | 0.34%   |
| 1400x1050          | 1         | 0.34%   |
| 1360x768           | 1         | 0.34%   |
| 1280x720 (HD)      | 1         | 0.34%   |
| 1152x864           | 1         | 0.34%   |
| 1024x768 (XGA)     | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 124       | 40.26%  |
| 14      | 34        | 11.04%  |
| 13      | 32        | 10.39%  |
| 24      | 18        | 5.84%   |
| 17      | 14        | 4.55%   |
| 12      | 14        | 4.55%   |
| 19      | 11        | 3.57%   |
| 23      | 10        | 3.25%   |
| 22      | 9         | 2.92%   |
| 27      | 7         | 2.27%   |
| 21      | 6         | 1.95%   |
| 18      | 6         | 1.95%   |
| Unknown | 4         | 1.3%    |
| 20      | 3         | 0.97%   |
| 11      | 3         | 0.97%   |
| 84      | 2         | 0.65%   |
| 10      | 2         | 0.65%   |
| 72      | 1         | 0.32%   |
| 58      | 1         | 0.32%   |
| 54      | 1         | 0.32%   |
| 52      | 1         | 0.32%   |
| 43      | 1         | 0.32%   |
| 32      | 1         | 0.32%   |
| 31      | 1         | 0.32%   |
| 16      | 1         | 0.32%   |
| 7       | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 176       | 57.33%  |
| 201-300     | 35        | 11.4%   |
| 501-600     | 32        | 10.42%  |
| 401-500     | 29        | 9.45%   |
| 351-400     | 19        | 6.19%   |
| Unknown     | 4         | 1.3%    |
| 601-700     | 3         | 0.98%   |
| 1501-2000   | 3         | 0.98%   |
| 1001-1500   | 3         | 0.98%   |
| 701-800     | 1         | 0.33%   |
| 901-1000    | 1         | 0.33%   |
| 1-100       | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 239       | 80.47%  |
| 16/10   | 37        | 12.46%  |
| 5/4     | 10        | 3.37%   |
| 4/3     | 4         | 1.35%   |
| Unknown | 4         | 1.35%   |
| 3/2     | 2         | 0.67%   |
| 0.67    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 124       | 40.39%  |
| 81-90          | 52        | 16.94%  |
| 201-250        | 35        | 11.4%   |
| 151-200        | 17        | 5.54%   |
| 71-80          | 13        | 4.23%   |
| 61-70          | 13        | 4.23%   |
| 141-150        | 9         | 2.93%   |
| 301-350        | 7         | 2.28%   |
| 121-130        | 7         | 2.28%   |
| More than 1000 | 6         | 1.95%   |
| 251-300        | 6         | 1.95%   |
| Unknown        | 4         | 1.3%    |
| 51-60          | 3         | 0.98%   |
| 351-500        | 2         | 0.65%   |
| 41-50          | 2         | 0.65%   |
| 131-140        | 2         | 0.65%   |
| 111-120        | 2         | 0.65%   |
| 1-40           | 1         | 0.33%   |
| 501-1000       | 1         | 0.33%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 109       | 35.74%  |
| 121-160       | 82        | 26.89%  |
| 51-100        | 78        | 25.57%  |
| 161-240       | 23        | 7.54%   |
| 1-50          | 6         | 1.97%   |
| Unknown       | 4         | 1.31%   |
| More than 240 | 3         | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 289       | 90.03%  |
| 2     | 20        | 6.23%   |
| 0     | 12        | 3.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 182       | 36.99%  |
| Realtek Semiconductor            | 129       | 26.22%  |
| Qualcomm Atheros                 | 54        | 10.98%  |
| Broadcom                         | 44        | 8.94%   |
| Ralink Technology                | 24        | 4.88%   |
| Ralink                           | 11        | 2.24%   |
| TP-Link                          | 8         | 1.63%   |
| Broadcom Limited                 | 6         | 1.22%   |
| Dell                             | 4         | 0.81%   |
| Xiaomi                           | 3         | 0.61%   |
| Sierra Wireless                  | 3         | 0.61%   |
| Nvidia                           | 3         | 0.61%   |
| Marvell Technology Group         | 3         | 0.61%   |
| Samsung Electronics              | 2         | 0.41%   |
| Lenovo                           | 2         | 0.41%   |
| Huawei Technologies              | 2         | 0.41%   |
| D-Link System                    | 2         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Qualcomm Atheros Communications  | 1         | 0.2%    |
| Qualcomm                         | 1         | 0.2%    |
| Microchip Technology             | 1         | 0.2%    |
| MediaTek                         | 1         | 0.2%    |
| JMicron Technology               | 1         | 0.2%    |
| Gemtek                           | 1         | 0.2%    |
| Fibocom                          | 1         | 0.2%    |
| Arduino SA                       | 1         | 0.2%    |
| Aquantia                         | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 75        | 12.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 26        | 4.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 26        | 4.27%   |
| Intel Ethernet Connection I217-LM                                      | 20        | 3.28%   |
| Intel Wireless 8265 / 8275                                             | 18        | 2.96%   |
| Ralink MT7601U Wireless Adapter                                        | 13        | 2.13%   |
| Intel Wireless 8260                                                    | 13        | 2.13%   |
| Intel Wireless 7265                                                    | 12        | 1.97%   |
| Intel Ethernet Connection (2) I219-LM                                  | 12        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 1.81%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.64%   |
| Ralink RT5370 Wireless Adapter                                         | 9         | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.48%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.48%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 1.48%   |
| Intel Centrino Advanced-N 6200                                         | 8         | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 8         | 1.31%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 7         | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 7         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.15%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 7         | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.99%   |
| Intel Wireless 7260                                                    | 6         | 0.99%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 0.99%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 0.99%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 6         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.82%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.82%   |
| Intel Centrino Advanced-N 6235                                         | 5         | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.66%   |
| Intel WiFi Link 5100                                                   | 4         | 0.66%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 0.66%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 41.14%  |
| Qualcomm Atheros                | 48        | 16.05%  |
| Realtek Semiconductor           | 40        | 13.38%  |
| Broadcom                        | 30        | 10.03%  |
| Ralink Technology               | 24        | 8.03%   |
| Ralink                          | 11        | 3.68%   |
| TP-Link                         | 8         | 2.68%   |
| Broadcom Limited                | 4         | 1.34%   |
| Sierra Wireless                 | 3         | 1%      |
| Dell                            | 3         | 1%      |
| Qualcomm Atheros Communications | 1         | 0.33%   |
| MediaTek                        | 1         | 0.33%   |
| Gemtek                          | 1         | 0.33%   |
| Fibocom                         | 1         | 0.33%   |
| D-Link System                   | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 18        | 5.94%   |
| Ralink MT7601U Wireless Adapter                                | 13        | 4.29%   |
| Intel Wireless 8260                                            | 13        | 4.29%   |
| Intel Wireless 7265                                            | 12        | 3.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 3.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.3%    |
| Ralink RT5370 Wireless Adapter                                 | 9         | 2.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 2.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.97%   |
| Intel Centrino Advanced-N 6200                                 | 8         | 2.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 2.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7         | 2.31%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 7         | 2.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.31%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 2.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 2.31%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.98%   |
| Intel Wireless 7260                                            | 6         | 1.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.65%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.65%   |
| Intel WiFi Link 5100                                           | 4         | 1.32%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.32%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 3         | 0.99%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.99%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.99%   |
| Intel Wireless 3165                                            | 3         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 0.99%   |
| Sierra Wireless EM7455                                         | 2         | 0.66%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.66%   |
| Realtek 802.11ac NIC                                           | 2         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 134       | 45.12%  |
| Realtek Semiconductor            | 109       | 36.7%   |
| Broadcom                         | 18        | 6.06%   |
| Qualcomm Atheros                 | 13        | 4.38%   |
| Xiaomi                           | 3         | 1.01%   |
| Nvidia                           | 3         | 1.01%   |
| Marvell Technology Group         | 3         | 1.01%   |
| Samsung Electronics              | 2         | 0.67%   |
| Lenovo                           | 2         | 0.67%   |
| Huawei Technologies              | 2         | 0.67%   |
| Broadcom Limited                 | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Qualcomm                         | 1         | 0.34%   |
| Microchip Technology             | 1         | 0.34%   |
| JMicron Technology               | 1         | 0.34%   |
| D-Link System                    | 1         | 0.34%   |
| Aquantia                         | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 75        | 24.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 26        | 8.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 26        | 8.58%   |
| Intel Ethernet Connection I217-LM                                      | 20        | 6.6%    |
| Intel Ethernet Connection (2) I219-LM                                  | 12        | 3.96%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 3.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 2.97%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 2.97%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 1.98%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 1.98%   |
| Intel Ethernet Connection I217-V                                       | 5         | 1.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 1.32%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.99%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.99%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.99%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.99%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 3         | 0.99%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 3         | 0.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.66%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 0.66%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 0.66%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.66%   |
| Huawei STG-LX1                                                         | 2         | 0.66%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.66%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                    | 2         | 0.66%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1         | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.33%   |
| Qualcomm Redmi 9T                                                      | 1         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 283       | 49.91%  |
| WiFi     | 281       | 49.56%  |
| Modem    | 3         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 234       | 73.35%  |
| Ethernet | 85        | 26.65%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 213       | 66.98%  |
| 1     | 90        | 28.3%   |
| 0     | 8         | 2.52%   |
| 3     | 6         | 1.89%   |
| 7     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 317       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 44.27%  |
| Realtek Semiconductor           | 21        | 10.94%  |
| Qualcomm Atheros Communications | 21        | 10.94%  |
| Broadcom                        | 15        | 7.81%   |
| IMC Networks                    | 8         | 4.17%   |
| Dell                            | 7         | 3.65%   |
| Lite-On Technology              | 6         | 3.13%   |
| Hewlett-Packard                 | 6         | 3.13%   |
| Cambridge Silicon Radio         | 6         | 3.13%   |
| Ralink                          | 5         | 2.6%    |
| Apple                           | 4         | 2.08%   |
| Toshiba                         | 2         | 1.04%   |
| Foxconn / Hon Hai               | 2         | 1.04%   |
| ASUSTek Computer                | 2         | 1.04%   |
| Foxconn International           | 1         | 0.52%   |
| Alps Electric                   | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 48        | 25%     |
| Realtek Bluetooth Radio                                                             | 14        | 7.29%   |
| Intel AX201 Bluetooth                                                               | 12        | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 3.65%   |
| Intel AX200 Bluetooth                                                               | 7         | 3.65%   |
| IMC Networks Bluetooth Device                                                       | 6         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.6%    |
| Ralink RT3290 Bluetooth                                                             | 5         | 2.6%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 2.6%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.6%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 2.6%    |
| Dell DW375 Bluetooth Module                                                         | 4         | 2.08%   |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 2.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 1.56%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.04%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 1.04%   |
| Intel Bluetooth Device                                                              | 2         | 1.04%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 1.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.04%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.04%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.52%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 0.52%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.52%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.52%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.52%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.52%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 1         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.52%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 278       | 72.4%   |
| Nvidia                           | 49        | 12.76%  |
| AMD                              | 40        | 10.42%  |
| Silicon Integrated Systems [SiS] | 2         | 0.52%   |
| Lenovo                           | 2         | 0.52%   |
| GN Netcom                        | 2         | 0.52%   |
| Nordic Semiconductor ASA         | 1         | 0.26%   |
| Medeli Electronics               | 1         | 0.26%   |
| Logitech                         | 1         | 0.26%   |
| Kingston Technology              | 1         | 0.26%   |
| Hewlett-Packard                  | 1         | 0.26%   |
| Generalplus Technology           | 1         | 0.26%   |
| GEMBIRD                          | 1         | 0.26%   |
| Focusrite-Novation               | 1         | 0.26%   |
| EDFIER                           | 1         | 0.26%   |
| C-Media Electronics              | 1         | 0.26%   |
| ASUSTek Computer                 | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 8.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 27        | 5.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 23        | 4.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 4.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 4.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 4.06%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 4.06%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 3.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 3.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 2.99%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 2.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 1.5%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.28%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.07%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.07%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 0.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 0.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.85%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.64%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.64%   |
| Nvidia Audio device                                                                               | 3         | 0.64%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.64%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.64%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 68        | 29.44%  |
| SK hynix            | 60        | 25.97%  |
| Micron Technology   | 30        | 12.99%  |
| Kingston            | 23        | 9.96%   |
| Unknown             | 8         | 3.46%   |
| Ramaxel Technology  | 5         | 2.16%   |
| Nanya Technology    | 5         | 2.16%   |
| Elpida              | 5         | 2.16%   |
| Crucial             | 4         | 1.73%   |
| Corsair             | 4         | 1.73%   |
| A-DATA Technology   | 4         | 1.73%   |
| Sesame              | 2         | 0.87%   |
| Qimonda             | 2         | 0.87%   |
| Unknown             | 2         | 0.87%   |
| Wilk                | 1         | 0.43%   |
| Unknown (83DA)      | 1         | 0.43%   |
| Transcend           | 1         | 0.43%   |
| Toshiba             | 1         | 0.43%   |
| TakeMS              | 1         | 0.43%   |
| G.Skill             | 1         | 0.43%   |
| Avant               | 1         | 0.43%   |
| ASint Technology    | 1         | 0.43%   |
| Apacer              | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s        | 4         | 1.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 1.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 1.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 1.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 1.19%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s         | 3         | 1.19%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 3         | 1.19%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s         | 3         | 1.19%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                | 2         | 0.79%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s        | 2         | 0.79%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 0.79%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 0.79%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                 | 2         | 0.79%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                   | 2         | 0.79%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s    | 2         | 0.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.79%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 0.79%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 0.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.79%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s       | 2         | 0.79%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 2         | 0.79%   |
| Kingston RAM HP687515-H66-MCN 4096MB SODIMM DDR3 1600MT/s   | 2         | 0.79%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 2         | 0.79%   |
| Unknown                                                     | 2         | 0.79%   |
| Wilk RAM Module 16GB DIMM DDR4 2667MT/s                     | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.4%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s              | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM                                 | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 81        | 45.51%  |
| DDR4    | 62        | 34.83%  |
| DDR2    | 11        | 6.18%   |
| SDRAM   | 10        | 5.62%   |
| LPDDR4  | 5         | 2.81%   |
| LPDDR3  | 4         | 2.25%   |
| Unknown | 3         | 1.69%   |
| DDR5    | 1         | 0.56%   |
| DDR     | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 69.23%  |
| DIMM         | 42        | 24.85%  |
| Row Of Chips | 7         | 4.14%   |
| Unknown      | 2         | 1.18%   |
| RIMM         | 1         | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 69        | 35.03%  |
| 8192  | 65        | 32.99%  |
| 2048  | 29        | 14.72%  |
| 16384 | 17        | 8.63%   |
| 1024  | 11        | 5.58%   |
| 32768 | 2         | 1.02%   |
| 512   | 2         | 1.02%   |
| 256   | 1         | 0.51%   |
| 128   | 1         | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 55        | 27.36%  |
| 2667    | 25        | 12.44%  |
| 3200    | 16        | 7.96%   |
| 2400    | 14        | 6.97%   |
| 1334    | 14        | 6.97%   |
| 1333    | 13        | 6.47%   |
| 2133    | 12        | 5.97%   |
| 667     | 7         | 3.48%   |
| Unknown | 5         | 2.49%   |
| 1648    | 4         | 1.99%   |
| 1066    | 4         | 1.99%   |
| 800     | 4         | 1.99%   |
| 3600    | 3         | 1.49%   |
| 1867    | 3         | 1.49%   |
| 1067    | 3         | 1.49%   |
| 4199    | 2         | 1%      |
| 3266    | 2         | 1%      |
| 975     | 2         | 1%      |
| 4800    | 1         | 0.5%    |
| 4267    | 1         | 0.5%    |
| 4000    | 1         | 0.5%    |
| 3733    | 1         | 0.5%    |
| 3400    | 1         | 0.5%    |
| 2666    | 1         | 0.5%    |
| 1866    | 1         | 0.5%    |
| 1800    | 1         | 0.5%    |
| 1639    | 1         | 0.5%    |
| 1331    | 1         | 0.5%    |
| 400     | 1         | 0.5%    |
| 333     | 1         | 0.5%    |
| 266     | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 66.67%  |
| Canon           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP LaserJet P1005      | 1         | 33.33%  |
| HP Deskjet 3510 series | 1         | 33.33%  |
| Canon MB2000 series    | 1         | 33.33%  |

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
| Chicony Electronics                    | 57        | 27.94%  |
| IMC Networks                           | 21        | 10.29%  |
| Realtek Semiconductor                  | 18        | 8.82%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 8.82%   |
| Suyin                                  | 12        | 5.88%   |
| Sunplus Innovation Technology          | 12        | 5.88%   |
| Lite-On Technology                     | 12        | 5.88%   |
| Microdia                               | 9         | 4.41%   |
| Quanta                                 | 7         | 3.43%   |
| Syntek                                 | 4         | 1.96%   |
| Ricoh                                  | 4         | 1.96%   |
| Bison Electronics                      | 4         | 1.96%   |
| Apple                                  | 4         | 1.96%   |
| Logitech                               | 3         | 1.47%   |
| Alcor Micro                            | 3         | 1.47%   |
| Luxvisions Innotech Limited            | 2         | 0.98%   |
| ALi                                    | 2         | 0.98%   |
| Acer                                   | 2         | 0.98%   |
| Z-Star Microelectronics                | 1         | 0.49%   |
| USB Camera                             | 1         | 0.49%   |
| Sunplus Technology                     | 1         | 0.49%   |
| Sonix Technology                       | 1         | 0.49%   |
| Silicon Motion                         | 1         | 0.49%   |
| ShineTech                              | 1         | 0.49%   |
| OPPO Electronics                       | 1         | 0.49%   |
| Nebraska Furniture Mart                | 1         | 0.49%   |
| LG Innotek                             | 1         | 0.49%   |
| Jieli Technology                       | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 4.37%   |
| IMC Networks Integrated Camera                              | 7         | 3.4%    |
| Realtek Integrated_Webcam_HD                                | 6         | 2.91%   |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 2.91%   |
| Chicony HP Webcam                                           | 6         | 2.91%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 5         | 2.43%   |
| Realtek USB Camera                                          | 4         | 1.94%   |
| Lite-On HP HD Camera                                        | 4         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 1.94%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 1.46%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 1.46%   |
| Microdia Integrated Webcam                                  | 3         | 1.46%   |
| Lite-On HP HD Webcam                                        | 3         | 1.46%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.46%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.46%   |
| Chicony HP Wide Vision HD Camera                            | 3         | 1.46%   |
| Chicony HP HD Webcam                                        | 3         | 1.46%   |
| Chicony HP HD Camera                                        | 3         | 1.46%   |
| Syntek Lenovo EasyCamera                                    | 2         | 0.97%   |
| Suyin Sony Visual Communication Camera                      | 2         | 0.97%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 0.97%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.97%   |
| Sunplus HP Universal Camera                                 | 2         | 0.97%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 0.97%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 0.97%   |
| Quanta HD Webcam                                            | 2         | 0.97%   |
| Microdia Integrated_Webcam_HD                               | 2         | 0.97%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 0.97%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 0.97%   |
| IMC Networks Integrated Webcam                              | 2         | 0.97%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 0.97%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 0.97%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 0.97%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 0.97%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 0.97%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 0.97%   |
| Chicony HP Truevision HD                                    | 2         | 0.97%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 2         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 0.97%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 32        | 65.31%  |
| Synaptics                  | 9         | 18.37%  |
| Elan Microelectronics      | 4         | 8.16%   |
| Shenzhen Goodix Technology | 2         | 4.08%   |
| Upek                       | 1         | 2.04%   |
| Focal-systems.Corp         | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 22.45%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 10.2%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 10.2%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 10.2%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 6.12%   |
| Validity Sensors VFS491                                                    | 2         | 4.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 4.08%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.08%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.04%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 2.04%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.04%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.04%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.04%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 61.76%  |
| Alcor Micro | 9         | 26.47%  |
| O2 Micro    | 4         | 11.76%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 29.41%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 26.47%  |
| Broadcom 5880                                                                | 5         | 14.71%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 11.76%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.88%   |
| Broadcom 58200                                                               | 2         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 206       | 63.38%  |
| 1     | 96        | 29.54%  |
| 2     | 19        | 5.85%   |
| 3     | 3         | 0.92%   |
| 5     | 1         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 33.56%  |
| Graphics card            | 27        | 18.49%  |
| Chipcard                 | 27        | 18.49%  |
| Net/wireless             | 13        | 8.9%    |
| Bluetooth                | 6         | 4.11%   |
| Storage                  | 5         | 3.42%   |
| Camera                   | 4         | 2.74%   |
| Unassigned class         | 3         | 2.05%   |
| Multimedia controller    | 3         | 2.05%   |
| Communication controller | 3         | 2.05%   |
| Sound                    | 2         | 1.37%   |
| Net/ethernet             | 2         | 1.37%   |
| Network                  | 1         | 0.68%   |
| Modem                    | 1         | 0.68%   |

