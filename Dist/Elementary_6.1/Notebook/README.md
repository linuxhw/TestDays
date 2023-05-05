Elementary 6.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 627

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv7                | [346cbe0e48](https://linux-hardware.org/?probe=346cbe0e48) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [afafdbce36](https://linux-hardware.org/?probe=afafdbce36) | Apr 28, 2023 |
| HP            | EliteBook 2560p             | [ce35b62e32](https://linux-hardware.org/?probe=ce35b62e32) | Apr 27, 2023 |
| HP            | Pavilion dv7                | [e8318168c4](https://linux-hardware.org/?probe=e8318168c4) | Apr 25, 2023 |
| HP            | Pavilion dv7                | [8b90982317](https://linux-hardware.org/?probe=8b90982317) | Apr 23, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | [241411df47](https://linux-hardware.org/?probe=241411df47) | Apr 23, 2023 |
| Apple         | MacBookAir7,1               | [f4b3f86485](https://linux-hardware.org/?probe=f4b3f86485) | Apr 16, 2023 |
| Notebook      | NLx0MU                      | [6d04c51285](https://linux-hardware.org/?probe=6d04c51285) | Apr 11, 2023 |
| Multilaser    | PC150                       | [0bcb0ca7ba](https://linux-hardware.org/?probe=0bcb0ca7ba) | Apr 02, 2023 |
| HP            | Laptop 15-bs2xx             | [b6160f7688](https://linux-hardware.org/?probe=b6160f7688) | Mar 27, 2023 |
| HP            | Laptop 15-bs2xx             | [85966e5691](https://linux-hardware.org/?probe=85966e5691) | Mar 27, 2023 |
| Lenovo        | V510-15IKB 80WQ             | [8df3d7641e](https://linux-hardware.org/?probe=8df3d7641e) | Mar 26, 2023 |
| Lenovo        | G580 20150                  | [489b8775b6](https://linux-hardware.org/?probe=489b8775b6) | Mar 22, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | [0365bfc4ca](https://linux-hardware.org/?probe=0365bfc4ca) | Mar 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [421f6945e6](https://linux-hardware.org/?probe=421f6945e6) | Mar 16, 2023 |
| HUAWEI        | KLVL-WXX9                   | [44db3bc5ec](https://linux-hardware.org/?probe=44db3bc5ec) | Mar 11, 2023 |
| ASUSTek       | K55A                        | [15899be9a8](https://linux-hardware.org/?probe=15899be9a8) | Mar 06, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [fe903be37c](https://linux-hardware.org/?probe=fe903be37c) | Mar 04, 2023 |
| Acer          | Aspire A315-32              | [5203ce8a41](https://linux-hardware.org/?probe=5203ce8a41) | Mar 02, 2023 |
| Toshiba       | Satellite C50D-A            | [3e9201a0fe](https://linux-hardware.org/?probe=3e9201a0fe) | Feb 20, 2023 |
| HP            | EliteBook 8760w             | [456d7c61ce](https://linux-hardware.org/?probe=456d7c61ce) | Feb 14, 2023 |
| HP            | G62                         | [e32c4fdd93](https://linux-hardware.org/?probe=e32c4fdd93) | Feb 13, 2023 |
| Unknown       | Unknown                     | [af50508abe](https://linux-hardware.org/?probe=af50508abe) | Feb 07, 2023 |
| Dell          | Latitude E6400              | [61e0a7ffe7](https://linux-hardware.org/?probe=61e0a7ffe7) | Feb 05, 2023 |
| Acer          | Aspire one 1-132            | [d66a972aa9](https://linux-hardware.org/?probe=d66a972aa9) | Feb 02, 2023 |
| Apple         | MacBookAir6,2               | [2261a77abb](https://linux-hardware.org/?probe=2261a77abb) | Feb 01, 2023 |
| Dell          | XPS 13 9360                 | [9037e30b54](https://linux-hardware.org/?probe=9037e30b54) | Jan 30, 2023 |
| Apple         | MacBookPro11,3              | [b7cec06bcb](https://linux-hardware.org/?probe=b7cec06bcb) | Jan 30, 2023 |
| Sony          | VPCSB11FX                   | [7659c1ba93](https://linux-hardware.org/?probe=7659c1ba93) | Jan 29, 2023 |
| HUAWEI        | MACHD-WXX9                  | [cac5b8faa5](https://linux-hardware.org/?probe=cac5b8faa5) | Jan 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c5168e6b33](https://linux-hardware.org/?probe=c5168e6b33) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | [73977968f5](https://linux-hardware.org/?probe=73977968f5) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | [d526ae42aa](https://linux-hardware.org/?probe=d526ae42aa) | Jan 27, 2023 |
| HP            | EliteBook 2560p             | [d5eae98224](https://linux-hardware.org/?probe=d5eae98224) | Jan 25, 2023 |
| Dell          | G3 3500                     | [e81b4d5e46](https://linux-hardware.org/?probe=e81b4d5e46) | Jan 22, 2023 |
| ASUSTek       | X540UA                      | [dda62597f7](https://linux-hardware.org/?probe=dda62597f7) | Jan 21, 2023 |
| Acer          | TravelMate 5735Z            | [712fdb1fa7](https://linux-hardware.org/?probe=712fdb1fa7) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | [5b1b812b6e](https://linux-hardware.org/?probe=5b1b812b6e) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [032ac1d52e](https://linux-hardware.org/?probe=032ac1d52e) | Jan 18, 2023 |
| Apple         | MacBookPro8,2               | [271f6a7e85](https://linux-hardware.org/?probe=271f6a7e85) | Jan 17, 2023 |
| HP            | ProBook 455R G6             | [6ca9f4f6c0](https://linux-hardware.org/?probe=6ca9f4f6c0) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | AeroBook Pro                | [13da35b0f7](https://linux-hardware.org/?probe=13da35b0f7) | Jan 15, 2023 |
| Lenovo        | Y50-70 20378                | [64ec4b6816](https://linux-hardware.org/?probe=64ec4b6816) | Jan 12, 2023 |
| Lenovo        | Y50-70 20378                | [9cd68b4513](https://linux-hardware.org/?probe=9cd68b4513) | Jan 11, 2023 |
| HP            | ProBook 650 G1              | [1dba72668b](https://linux-hardware.org/?probe=1dba72668b) | Jan 10, 2023 |
| HP            | ProBook 650 G1              | [e6d3982bc0](https://linux-hardware.org/?probe=e6d3982bc0) | Jan 10, 2023 |
| Avell High... | B.ON                        | [23b5b8565e](https://linux-hardware.org/?probe=23b5b8565e) | Jan 10, 2023 |
| Notebook      | NLx0MU                      | [69b46423cb](https://linux-hardware.org/?probe=69b46423cb) | Jan 08, 2023 |
| Notebook      | NLx0MU                      | [e43de3e94e](https://linux-hardware.org/?probe=e43de3e94e) | Jan 08, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3e870855db](https://linux-hardware.org/?probe=3e870855db) | Jan 08, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Dell          | XPS 15 9510                 | [1893fb2388](https://linux-hardware.org/?probe=1893fb2388) | Jan 06, 2023 |
| Dell          | XPS 15 9510                 | [c3fbbaf7de](https://linux-hardware.org/?probe=c3fbbaf7de) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L5000YUS    | [4c735329b6](https://linux-hardware.org/?probe=4c735329b6) | Jan 05, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [3a3164f63f](https://linux-hardware.org/?probe=3a3164f63f) | Jan 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2c6b6c2558](https://linux-hardware.org/?probe=2c6b6c2558) | Jan 04, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [c7d37a7616](https://linux-hardware.org/?probe=c7d37a7616) | Jan 04, 2023 |
| Acer          | TravelMate 5735Z            | [9fa5978af4](https://linux-hardware.org/?probe=9fa5978af4) | Jan 01, 2023 |
| Dell          | System XPS L702X            | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Chuwi         | HeroBook                    | [1664994b07](https://linux-hardware.org/?probe=1664994b07) | Dec 30, 2022 |
| HP            | ProBook 455R G6             | [71c9651ee2](https://linux-hardware.org/?probe=71c9651ee2) | Dec 30, 2022 |
| AMI           | F3C2                        | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [5e094b34a5](https://linux-hardware.org/?probe=5e094b34a5) | Dec 29, 2022 |
| Acer          | Aspire A315-53              | [9c28036440](https://linux-hardware.org/?probe=9c28036440) | Dec 29, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [f5c5147826](https://linux-hardware.org/?probe=f5c5147826) | Dec 28, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [8dfcf5860f](https://linux-hardware.org/?probe=8dfcf5860f) | Dec 28, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | [00ba06cfd1](https://linux-hardware.org/?probe=00ba06cfd1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | [a570034bbc](https://linux-hardware.org/?probe=a570034bbc) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [6de981f1fc](https://linux-hardware.org/?probe=6de981f1fc) | Dec 24, 2022 |
| Avell High... | B.ON                        | [ea8a4babbf](https://linux-hardware.org/?probe=ea8a4babbf) | Dec 24, 2022 |
| Lenovo        | ThinkPad X201 3680HB1       | [41e1719d61](https://linux-hardware.org/?probe=41e1719d61) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680HB1       | [01e9dfa8b8](https://linux-hardware.org/?probe=01e9dfa8b8) | Dec 22, 2022 |
| HP            | EliteBook Folio 1040 G3     | [3d89cf5c71](https://linux-hardware.org/?probe=3d89cf5c71) | Dec 21, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [a285792280](https://linux-hardware.org/?probe=a285792280) | Dec 20, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [f777de4f53](https://linux-hardware.org/?probe=f777de4f53) | Dec 17, 2022 |
| HP            | Pavilion g6                 | [d1bfb26644](https://linux-hardware.org/?probe=d1bfb26644) | Dec 16, 2022 |
| HUAWEI        | NBM-WXX9                    | [a9f5b0866f](https://linux-hardware.org/?probe=a9f5b0866f) | Dec 16, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | [4f1aa7401d](https://linux-hardware.org/?probe=4f1aa7401d) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [615d3e1599](https://linux-hardware.org/?probe=615d3e1599) | Dec 14, 2022 |
| MSI           | GF63 Thin 10SC              | [ed86ad34cf](https://linux-hardware.org/?probe=ed86ad34cf) | Dec 13, 2022 |
| MSI           | GF63 Thin 10SC              | [18c3d0d050](https://linux-hardware.org/?probe=18c3d0d050) | Dec 13, 2022 |
| HP            | Laptop 17-ca0xxx            | [0a7b9bd226](https://linux-hardware.org/?probe=0a7b9bd226) | Dec 12, 2022 |
| HP            | Laptop 17-ca0xxx            | [e2d976c5f4](https://linux-hardware.org/?probe=e2d976c5f4) | Dec 11, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [52546b1dd0](https://linux-hardware.org/?probe=52546b1dd0) | Dec 10, 2022 |
| HP            | ProBook 650 G1              | [46d77ce0b4](https://linux-hardware.org/?probe=46d77ce0b4) | Dec 09, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | 250 G7 Notebook PC          | [1002df8858](https://linux-hardware.org/?probe=1002df8858) | Dec 01, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [d95adc01a7](https://linux-hardware.org/?probe=d95adc01a7) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [4d8bd1760a](https://linux-hardware.org/?probe=4d8bd1760a) | Nov 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [408158ed97](https://linux-hardware.org/?probe=408158ed97) | Nov 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [dce27f6d43](https://linux-hardware.org/?probe=dce27f6d43) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| Apple         | MacBookPro11,3              | [476415b4e4](https://linux-hardware.org/?probe=476415b4e4) | Nov 22, 2022 |
| Dell          | Latitude E6520              | [1801edca03](https://linux-hardware.org/?probe=1801edca03) | Nov 22, 2022 |
| Acer          | Aspire A315-51              | [3d8ef86616](https://linux-hardware.org/?probe=3d8ef86616) | Nov 21, 2022 |
| Lenovo        | G50-45 80E3                 | [680aac00bd](https://linux-hardware.org/?probe=680aac00bd) | Nov 21, 2022 |
| Apple         | MacBookPro12,1              | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| Dell          | Inspiron 5584               | [f11ce2dd6c](https://linux-hardware.org/?probe=f11ce2dd6c) | Nov 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d07cacacde](https://linux-hardware.org/?probe=d07cacacde) | Nov 15, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [b6e353af2b](https://linux-hardware.org/?probe=b6e353af2b) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | [c642a76e3e](https://linux-hardware.org/?probe=c642a76e3e) | Nov 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [32e8c529f0](https://linux-hardware.org/?probe=32e8c529f0) | Nov 14, 2022 |
| Medion        | E7220                       | [7d3df30772](https://linux-hardware.org/?probe=7d3df30772) | Nov 13, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| Apple         | MacBook3,1                  | [3bafc2796b](https://linux-hardware.org/?probe=3bafc2796b) | Nov 11, 2022 |
| Apple         | MacBookPro6,2               | [3c63d3fb1e](https://linux-hardware.org/?probe=3c63d3fb1e) | Nov 11, 2022 |
| Alienware     | m15 R6                      | [63b53e81ed](https://linux-hardware.org/?probe=63b53e81ed) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [22b8b36df5](https://linux-hardware.org/?probe=22b8b36df5) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [3e808157a3](https://linux-hardware.org/?probe=3e808157a3) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| Dell          | Studio 1558                 | [8be31a4335](https://linux-hardware.org/?probe=8be31a4335) | Nov 07, 2022 |
| Dell          | Inspiron 15-3567            | [390f51010e](https://linux-hardware.org/?probe=390f51010e) | Nov 06, 2022 |
| Packard Be... | EasyNote LS44HR             | [375b78c3f3](https://linux-hardware.org/?probe=375b78c3f3) | Nov 06, 2022 |
| Wortmann      | 1220624_1470150             | [2782ad2c3e](https://linux-hardware.org/?probe=2782ad2c3e) | Nov 05, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [505b2c2b5d](https://linux-hardware.org/?probe=505b2c2b5d) | Nov 04, 2022 |
| Sony          | VPCEA1S1R                   | [9dfb83587b](https://linux-hardware.org/?probe=9dfb83587b) | Nov 04, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f8685beefa](https://linux-hardware.org/?probe=f8685beefa) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7d6d6c3c3a](https://linux-hardware.org/?probe=7d6d6c3c3a) | Nov 04, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Laptop 17-ca3xxx            | [2c42913712](https://linux-hardware.org/?probe=2c42913712) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| Toshiba       | TECRA A11                   | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [9b90ea1d4d](https://linux-hardware.org/?probe=9b90ea1d4d) | Oct 27, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| HP            | Laptop 15-bw0xx             | [cdd4d21000](https://linux-hardware.org/?probe=cdd4d21000) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| Apple         | MacBookPro10,1              | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [484cb84d6b](https://linux-hardware.org/?probe=484cb84d6b) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2dd84a41e8](https://linux-hardware.org/?probe=2dd84a41e8) | Oct 17, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [c5b6ba786e](https://linux-hardware.org/?probe=c5b6ba786e) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Dell          | Inspiron 15-3567            | [2b00bd7a92](https://linux-hardware.org/?probe=2b00bd7a92) | Oct 15, 2022 |
| HP            | Pavilion dv7                | [44ae8ac465](https://linux-hardware.org/?probe=44ae8ac465) | Oct 14, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [8926251d64](https://linux-hardware.org/?probe=8926251d64) | Oct 11, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [db3419c5de](https://linux-hardware.org/?probe=db3419c5de) | Oct 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f06f54475b](https://linux-hardware.org/?probe=f06f54475b) | Oct 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [20ea012e04](https://linux-hardware.org/?probe=20ea012e04) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| Lenovo        | V130-15IKB 81HN             | [823a068620](https://linux-hardware.org/?probe=823a068620) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c086a688f1](https://linux-hardware.org/?probe=c086a688f1) | Oct 02, 2022 |
| HUAWEI        | HVY-WXX9                    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Google        | Blooglet                    | [44a9c6559f](https://linux-hardware.org/?probe=44a9c6559f) | Sep 29, 2022 |
| Medion        | Akoya E6422 MD99680         | [52c1708200](https://linux-hardware.org/?probe=52c1708200) | Sep 28, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [18ee2cafd6](https://linux-hardware.org/?probe=18ee2cafd6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [ffc2811bfe](https://linux-hardware.org/?probe=ffc2811bfe) | Sep 27, 2022 |
| Dell          | Latitude E6540              | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Dell          | Latitude E5450              | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| Apple         | MacBookAir6,2               | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Dell          | Inspiron 3493               | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6a0c80f635](https://linux-hardware.org/?probe=6a0c80f635) | Sep 22, 2022 |
| Acer          | Nitro AN515-54              | [7cf2d6a810](https://linux-hardware.org/?probe=7cf2d6a810) | Sep 20, 2022 |
| ASUSTek       | X555LAB                     | [71339e0cfb](https://linux-hardware.org/?probe=71339e0cfb) | Sep 19, 2022 |
| ASUSTek       | X555LAB                     | [a0acb674df](https://linux-hardware.org/?probe=a0acb674df) | Sep 19, 2022 |
| HP            | Laptop 15-bw0xx             | [94baca564e](https://linux-hardware.org/?probe=94baca564e) | Sep 19, 2022 |
| ASUSTek       | X555DG                      | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Clevo         | W54xEU                      | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7861fa17bf](https://linux-hardware.org/?probe=7861fa17bf) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| Dell          | Inspiron 5458               | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | [6b1829aad1](https://linux-hardware.org/?probe=6b1829aad1) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | [9ef29f2258](https://linux-hardware.org/?probe=9ef29f2258) | Sep 12, 2022 |
| HP            | ENVY m6                     | [b9de3b6e35](https://linux-hardware.org/?probe=b9de3b6e35) | Sep 11, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Apple         | MacBookPro11,2              | [47708e7772](https://linux-hardware.org/?probe=47708e7772) | Sep 09, 2022 |
| Apple         | MacBookPro11,4              | [c5d5b88740](https://linux-hardware.org/?probe=c5d5b88740) | Sep 09, 2022 |
| ASUSTek       | GL702VSK                    | [5001a76a0e](https://linux-hardware.org/?probe=5001a76a0e) | Sep 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [3932661b8e](https://linux-hardware.org/?probe=3932661b8e) | Sep 07, 2022 |
| Acer          | Aspire V5-552               | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| Apple         | MacBookPro8,2               | [b37d844ab3](https://linux-hardware.org/?probe=b37d844ab3) | Sep 04, 2022 |
| TUXEDO        | Book XP14 Gen12             | [cfb0fb9451](https://linux-hardware.org/?probe=cfb0fb9451) | Sep 04, 2022 |
| Timi          | TM1701                      | [f23c551375](https://linux-hardware.org/?probe=f23c551375) | Sep 03, 2022 |
| Notebook      | NLx0MU                      | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| Apple         | MacBookPro5,2               | [7f66ca2cc7](https://linux-hardware.org/?probe=7f66ca2cc7) | Aug 29, 2022 |
| Standard      | Unknown                     | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| HP            | Laptop 15-db0xxx            | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| ASUSTek       | X542UA                      | [0bf776cdc1](https://linux-hardware.org/?probe=0bf776cdc1) | Aug 28, 2022 |
| HP            | 240 G7 Notebook PC          | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Complet       | MY8312                      | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Dell          | Inspiron 5537               | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Dell          | Latitude E7250              | [98f4886ef7](https://linux-hardware.org/?probe=98f4886ef7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Apple         | MacBookAir7,1               | [079a951d65](https://linux-hardware.org/?probe=079a951d65) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| ASUSTek       | K52F                        | [cafd25a659](https://linux-hardware.org/?probe=cafd25a659) | Aug 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [08d6e2e6e8](https://linux-hardware.org/?probe=08d6e2e6e8) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| HP            | 240 G7 Notebook PC          | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| Acer          | Aspire V5-552G              | [f51f3093d9](https://linux-hardware.org/?probe=f51f3093d9) | Aug 12, 2022 |
| ASUSTek       | K43E                        | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Dell          | Latitude D630               | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| HP            | Pavilion 17                 | [f06bb8d9ab](https://linux-hardware.org/?probe=f06bb8d9ab) | Aug 07, 2022 |
| HP            | Pavilion 17                 | [9c47c2e4f4](https://linux-hardware.org/?probe=9c47c2e4f4) | Aug 07, 2022 |
| TrekStor      | Notebook Slim S130          | [ba73d094e7](https://linux-hardware.org/?probe=ba73d094e7) | Aug 06, 2022 |
| Sony          | SVS15117FLB                 | [2729210175](https://linux-hardware.org/?probe=2729210175) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| MSI           | Creator 15 A10SET           | [45d9d06fb8](https://linux-hardware.org/?probe=45d9d06fb8) | Aug 05, 2022 |
| Medion        | Akoya E6422 MD99680         | [86cd2f6a0a](https://linux-hardware.org/?probe=86cd2f6a0a) | Aug 05, 2022 |
| Sony          | SVS15117FLB                 | [1f64d30f2f](https://linux-hardware.org/?probe=1f64d30f2f) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [7a0956e5f8](https://linux-hardware.org/?probe=7a0956e5f8) | Aug 04, 2022 |
| ASUSTek       | K43E                        | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| Dell          | Latitude E6400              | [54db9ae43d](https://linux-hardware.org/?probe=54db9ae43d) | Aug 04, 2022 |
| HP            | Pavilion dv6                | [b921b586f6](https://linux-hardware.org/?probe=b921b586f6) | Aug 02, 2022 |
| HP            | 431                         | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Dell          | Latitude E6320              | [34270898c6](https://linux-hardware.org/?probe=34270898c6) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [04487d99ff](https://linux-hardware.org/?probe=04487d99ff) | Jul 30, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| Dell          | Latitude D630               | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | Latitude E6320              | [a5b77aa0e9](https://linux-hardware.org/?probe=a5b77aa0e9) | Jul 28, 2022 |
| Dell          | Latitude 3190               | [36027c80d2](https://linux-hardware.org/?probe=36027c80d2) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [d9a5e0b7e6](https://linux-hardware.org/?probe=d9a5e0b7e6) | Jul 27, 2022 |
| HP            | Pavilion g4                 | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| HP            | 255 G7 Notebook PC          | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f4026901c2](https://linux-hardware.org/?probe=f4026901c2) | Jul 25, 2022 |
| HP            | Pavilion g6                 | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| HP            | EliteBook 8460p             | [b1c5cb2096](https://linux-hardware.org/?probe=b1c5cb2096) | Jul 12, 2022 |
| HP            | Notebook                    | [afaaed48c7](https://linux-hardware.org/?probe=afaaed48c7) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Acer          | Aspire AV15-51              | [1a880a89af](https://linux-hardware.org/?probe=1a880a89af) | Jul 09, 2022 |
| Acer          | Aspire V3-771               | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| HP            | Notebook                    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| HP            | Laptop 15-dy1xxx            | [3fcdd6c039](https://linux-hardware.org/?probe=3fcdd6c039) | Jul 03, 2022 |
| Dell          | XPS 15 9500                 | [7df8533350](https://linux-hardware.org/?probe=7df8533350) | Jul 03, 2022 |
| ASUSTek       | N56VB                       | [88d34c06f3](https://linux-hardware.org/?probe=88d34c06f3) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| ASUSTek       | X553MA                      | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| Apple         | MacBookPro14,2              | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| ASUSTek       | UX303LAB                    | [ae3becae01](https://linux-hardware.org/?probe=ae3becae01) | Jun 24, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Alienware     | m17 R3                      | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| Dell          | Latitude E5510              | [1f6cc92f98](https://linux-hardware.org/?probe=1f6cc92f98) | Jun 18, 2022 |
| HP            | EliteBook 2170p             | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| HP            | ProBook 455R G6             | [31b94c71c7](https://linux-hardware.org/?probe=31b94c71c7) | Jun 16, 2022 |
| HP            | ProBook 455R G6             | [39d04d1188](https://linux-hardware.org/?probe=39d04d1188) | Jun 16, 2022 |
| Samsung       | Lumpy                       | [50dad22fb3](https://linux-hardware.org/?probe=50dad22fb3) | Jun 15, 2022 |
| ASUSTek       | GR8                         | [3cdc341eda](https://linux-hardware.org/?probe=3cdc341eda) | Jun 15, 2022 |
| Samsung       | Lumpy                       | [4137bf9757](https://linux-hardware.org/?probe=4137bf9757) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Apple         | MacBook4,1                  | [83cac56441](https://linux-hardware.org/?probe=83cac56441) | Jun 13, 2022 |
| HP            | ProBook 4540s               | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| Acer          | Aspire A315-21              | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [0ec841e188](https://linux-hardware.org/?probe=0ec841e188) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5768dfe23f](https://linux-hardware.org/?probe=5768dfe23f) | Jun 11, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c76f63fb68](https://linux-hardware.org/?probe=c76f63fb68) | Jun 10, 2022 |
| HP            | ProBook 4540s               | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| HP            | Notebook                    | [f07183fab5](https://linux-hardware.org/?probe=f07183fab5) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| HP            | ProBook 4540s               | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| Apple         | MacBookAir7,2               | [9de74ba486](https://linux-hardware.org/?probe=9de74ba486) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | [eb704f99ee](https://linux-hardware.org/?probe=eb704f99ee) | Jun 04, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| HP            | ProBook 4540s               | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| Samsung       | 300E5M/300E5L               | [baa12d722c](https://linux-hardware.org/?probe=baa12d722c) | Jun 01, 2022 |
| Dell          | XPS 13 9343                 | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| ASUSTek       | X550CA                      | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| Acer          | Swift SF114-32              | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| Apple         | MacBook4,1                  | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| AMI           | Intel                       | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| Sony          | VPCEB23FM                   | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| ASUSTek       | K55A                        | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| Apple         | MacBookPro8,2               | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| eMachines     | E525                        | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| HP            | EliteBook 840 G1            | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| HP            | ProBook 440 G7              | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Acer          | Aspire E5-575G              | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| HP            | Notebook                    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Dell          | Inspiron MM061              | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| Sony          | SVP1321B4E                  | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | MacBookAir7,1               | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| Acer          | Nitro AN517-52              | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| Packard Be... | EasyNote LS11HR             | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | X540SA                      | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| Dell          | Precision 7720              | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Google        | Lulu                        | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Sony          | SVE15115EN                  | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| Apple         | MacBookAir4,2               | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| Timi          | TM1613                      | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Apple         | MacBookPro6,2               | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Dell          | Inspiron 15-3567            | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| ASUSTek       | X555LN                      | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| Lenovo        | G550 20023                  | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| HP            | ProBook 4540s               | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Apple         | MacBookPro8,2               | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| Dell          | Latitude E5400              | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Star Labs     | StarBook                    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| MSI           | GF63 Thin 9SCSR             | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| Wortmann      | 1220729_1470271             | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Latitude 3580               | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary_6.1/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.11.0-43-generic         | 86        | 17.44%  |
| 5.13.0-28-generic         | 32        | 6.49%   |
| 5.15.0-46-generic         | 31        | 6.29%   |
| 5.13.0-30-generic         | 27        | 5.48%   |
| 5.15.0-56-generic         | 24        | 4.87%   |
| 5.13.0-27-generic         | 24        | 4.87%   |
| 5.15.0-41-generic         | 20        | 4.06%   |
| 5.15.0-52-generic         | 19        | 3.85%   |
| 5.15.0-48-generic         | 19        | 3.85%   |
| 5.13.0-40-generic         | 16        | 3.25%   |
| 5.13.0-39-generic         | 16        | 3.25%   |
| 5.11.0-44-generic         | 14        | 2.84%   |
| 5.15.0-58-generic         | 13        | 2.64%   |
| 5.13.0-35-generic         | 13        | 2.64%   |
| 5.15.0-43-generic         | 12        | 2.43%   |
| 5.13.0-37-generic         | 12        | 2.43%   |
| 5.15.0-53-generic         | 11        | 2.23%   |
| 5.13.0-52-generic         | 10        | 2.03%   |
| 5.13.0-41-generic         | 10        | 2.03%   |
| 5.11.0-46-generic         | 10        | 2.03%   |
| 5.13.0-51-generic         | 8         | 1.62%   |
| 5.15.0-57-generic         | 7         | 1.42%   |
| 5.15.0-50-generic         | 7         | 1.42%   |
| 5.13.0-44-generic         | 7         | 1.42%   |
| 5.13.0-48-generic         | 6         | 1.22%   |
| 5.15.0-69-generic         | 5         | 1.01%   |
| 5.11.0-41-generic         | 4         | 0.81%   |
| 5.15.0-67-generic         | 3         | 0.61%   |
| 5.15.0-60-generic         | 3         | 0.61%   |
| 5.13.0-25-generic         | 2         | 0.41%   |
| 5.11.0-40-generic         | 2         | 0.41%   |
| 6.0.0-060000rc7-generic   | 1         | 0.2%    |
| 5.8.0-50-generic          | 1         | 0.2%    |
| 5.4.0-122-generic         | 1         | 0.2%    |
| 5.19.3-051903-generic     | 1         | 0.2%    |
| 5.19.12-051912-generic    | 1         | 0.2%    |
| 5.19.11-xanmod1           | 1         | 0.2%    |
| 5.19.0-8.2-liquorix-amd64 | 1         | 0.2%    |
| 5.18.3-051803-generic     | 1         | 0.2%    |
| 5.16.16-051616-generic    | 1         | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 173       | 37.12%  |
| 5.15.0  | 157       | 33.69%  |
| 5.11.0  | 116       | 24.89%  |
| 5.14.0  | 2         | 0.43%   |
| 6.0.0   | 1         | 0.21%   |
| 5.8.0   | 1         | 0.21%   |
| 5.4.0   | 1         | 0.21%   |
| 5.19.3  | 1         | 0.21%   |
| 5.19.12 | 1         | 0.21%   |
| 5.19.11 | 1         | 0.21%   |
| 5.19.0  | 1         | 0.21%   |
| 5.18.3  | 1         | 0.21%   |
| 5.16.16 | 1         | 0.21%   |
| 5.16.10 | 1         | 0.21%   |
| 5.16.0  | 1         | 0.21%   |
| 5.15.36 | 1         | 0.21%   |
| 5.15.3  | 1         | 0.21%   |
| 5.15.21 | 1         | 0.21%   |
| 5.15.13 | 1         | 0.21%   |
| 5.15.12 | 1         | 0.21%   |
| 5.15.11 | 1         | 0.21%   |
| 5.14.10 | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 173       | 37.2%   |
| 5.15    | 163       | 35.05%  |
| 5.11    | 116       | 24.95%  |
| 5.19    | 4         | 0.86%   |
| 5.14    | 3         | 0.65%   |
| 5.16    | 2         | 0.43%   |
| 6.0     | 1         | 0.22%   |
| 5.8     | 1         | 0.22%   |
| 5.4     | 1         | 0.22%   |
| 5.18    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 452       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 450       | 99.56%  |
| Unknown  | 2         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 452       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 350       | 77.26%  |
| LightDM | 102       | 22.52%  |
| GDM     | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 204       | 45.03%  |
| de_DE   | 57        | 12.58%  |
| es_ES   | 33        | 7.28%   |
| ru_RU   | 24        | 5.3%    |
| en_GB   | 21        | 4.64%   |
| pt_BR   | 20        | 4.42%   |
| fr_FR   | 19        | 4.19%   |
| it_IT   | 18        | 3.97%   |
| nl_NL   | 9         | 1.99%   |
| pl_PL   | 7         | 1.55%   |
| tr_TR   | 6         | 1.32%   |
| pt_PT   | 5         | 1.1%    |
| en_AU   | 5         | 1.1%    |
| en_CA   | 4         | 0.88%   |
| nb_NO   | 3         | 0.66%   |
| zh_CN   | 2         | 0.44%   |
| hu_HU   | 2         | 0.44%   |
| de_CH   | 2         | 0.44%   |
| uk_UA   | 1         | 0.22%   |
| sv_SE   | 1         | 0.22%   |
| id_ID   | 1         | 0.22%   |
| fr_CA   | 1         | 0.22%   |
| et_EE   | 1         | 0.22%   |
| es_MX   | 1         | 0.22%   |
| el_GR   | 1         | 0.22%   |
| cs_CZ   | 1         | 0.22%   |
| ca_ES   | 1         | 0.22%   |
| C       | 1         | 0.22%   |
| bg_BG   | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 309       | 67.61%  |
| BIOS | 148       | 32.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 437       | 96.68%  |
| Overlay | 7         | 1.55%   |
| Btrfs   | 7         | 1.55%   |
| Xfs     | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 366       | 80.62%  |
| GPT     | 76        | 16.74%  |
| MBR     | 12        | 2.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 439       | 97.12%  |
| Yes       | 13        | 2.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 421       | 92.94%  |
| Yes       | 32        | 7.06%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 100       | 22.12%  |
| Hewlett-Packard        | 68        | 15.04%  |
| ASUSTek Computer       | 53        | 11.73%  |
| Apple                  | 52        | 11.5%   |
| Dell                   | 49        | 10.84%  |
| Acer                   | 33        | 7.3%    |
| HUAWEI                 | 15        | 3.32%   |
| Sony                   | 12        | 2.65%   |
| Toshiba                | 10        | 2.21%   |
| MSI                    | 9         | 1.99%   |
| Samsung Electronics    | 8         | 1.77%   |
| Notebook               | 3         | 0.66%   |
| Wortmann AG            | 2         | 0.44%   |
| Timi                   | 2         | 0.44%   |
| Teclast                | 2         | 0.44%   |
| Star Labs              | 2         | 0.44%   |
| Packard Bell           | 2         | 0.44%   |
| Monster                | 2         | 0.44%   |
| Medion                 | 2         | 0.44%   |
| LG Electronics         | 2         | 0.44%   |
| Google                 | 2         | 0.44%   |
| Chuwi                  | 2         | 0.44%   |
| Avell High Performance | 2         | 0.44%   |
| AMI                    | 2         | 0.44%   |
| Alienware              | 2         | 0.44%   |
| TUXEDO                 | 1         | 0.22%   |
| TrekStor               | 1         | 0.22%   |
| Standard               | 1         | 0.22%   |
| Razer                  | 1         | 0.22%   |
| PIPO                   | 1         | 0.22%   |
| Multilaser             | 1         | 0.22%   |
| iOTA                   | 1         | 0.22%   |
| Fujitsu                | 1         | 0.22%   |
| eMachines              | 1         | 0.22%   |
| Complet                | 1         | 0.22%   |
| Compaq                 | 1         | 0.22%   |
| Clevo                  | 1         | 0.22%   |
| Casper                 | 1         | 0.22%   |
| Unknown                | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| HUAWEI MACHD-WXX9              | 5         | 1.11%   |
| Apple MacBookPro8,2            | 5         | 1.11%   |
| Apple MacBookAir6,2            | 5         | 1.11%   |
| Apple MacBook5,1               | 4         | 0.88%   |
| HUAWEI NBLK-WAX9X              | 3         | 0.66%   |
| HP Pavilion g6                 | 3         | 0.66%   |
| HP Notebook                    | 3         | 0.66%   |
| Dell Inspiron 15-3567          | 3         | 0.66%   |
| ASUS ZenBook UX425EA_UX425EA   | 3         | 0.66%   |
| ASUS X550CA                    | 3         | 0.66%   |
| Apple MacBookPro6,2            | 3         | 0.66%   |
| Apple MacBookAir4,2            | 3         | 0.66%   |
| Apple MacBook4,1               | 3         | 0.66%   |
| Timi TM1613                    | 2         | 0.44%   |
| MSI Prestige 15 A11UC          | 2         | 0.44%   |
| MSI Modern 14 B10MW            | 2         | 0.44%   |
| Lenovo Legion Y540-15IRH 81SX  | 2         | 0.44%   |
| Lenovo IdeaPad S145-14AST 81ST | 2         | 0.44%   |
| Lenovo IdeaPad 510-15IKB 80SV  | 2         | 0.44%   |
| Lenovo IdeaPad 330S-15ARR 81FB | 2         | 0.44%   |
| Lenovo IdeaPad 310-15IKB 80TV  | 2         | 0.44%   |
| HP ProBook 650 G1              | 2         | 0.44%   |
| HP ProBook 4540s               | 2         | 0.44%   |
| HP Pavilion g4                 | 2         | 0.44%   |
| HP Pavilion dv7                | 2         | 0.44%   |
| HP Pavilion 17                 | 2         | 0.44%   |
| HP Laptop 15-db0xxx            | 2         | 0.44%   |
| HP Laptop 15-bw0xx             | 2         | 0.44%   |
| HP EliteBook 8460p             | 2         | 0.44%   |
| HP EliteBook 840 G1            | 2         | 0.44%   |
| HP EliteBook 2560p             | 2         | 0.44%   |
| HP 250 G7 Notebook PC          | 2         | 0.44%   |
| Dell XPS 13 9360               | 2         | 0.44%   |
| Dell XPS 13 9343               | 2         | 0.44%   |
| Dell Latitude E6400            | 2         | 0.44%   |
| Dell Inspiron N5050            | 2         | 0.44%   |
| Dell Inspiron 5537             | 2         | 0.44%   |
| Avell High Performance B.ON    | 2         | 0.44%   |
| Apple MacBookPro9,2            | 2         | 0.44%   |
| Apple MacBookPro5,5            | 2         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 46        | 10.18%  |
| Lenovo IdeaPad        | 32        | 7.08%   |
| Acer Aspire           | 23        | 5.09%   |
| Dell Inspiron         | 18        | 3.98%   |
| HP Pavilion           | 16        | 3.54%   |
| Dell Latitude         | 15        | 3.32%   |
| HP EliteBook          | 13        | 2.88%   |
| HP ProBook            | 12        | 2.65%   |
| HP Laptop             | 11        | 2.43%   |
| ASUS VivoBook         | 9         | 1.99%   |
| ASUS ZenBook          | 8         | 1.77%   |
| Toshiba Satellite     | 7         | 1.55%   |
| Apple MacBookPro8     | 7         | 1.55%   |
| Dell XPS              | 6         | 1.33%   |
| Apple MacBookPro11    | 6         | 1.33%   |
| Apple MacBookAir6     | 6         | 1.33%   |
| Lenovo Legion         | 5         | 1.11%   |
| HUAWEI MACHD-WXX9     | 5         | 1.11%   |
| Apple MacBook5        | 5         | 1.11%   |
| Acer Swift            | 5         | 1.11%   |
| Dell Vostro           | 4         | 0.88%   |
| Dell Precision        | 4         | 0.88%   |
| Apple MacBookPro5     | 4         | 0.88%   |
| Apple MacBookAir7     | 4         | 0.88%   |
| MSI Modern            | 3         | 0.66%   |
| Lenovo ThinkBook      | 3         | 0.66%   |
| HUAWEI NBLK-WAX9X     | 3         | 0.66%   |
| HP Notebook           | 3         | 0.66%   |
| ASUS X550CA           | 3         | 0.66%   |
| ASUS ROG              | 3         | 0.66%   |
| Apple MacBookPro9     | 3         | 0.66%   |
| Apple MacBookPro6     | 3         | 0.66%   |
| Apple MacBookAir4     | 3         | 0.66%   |
| Apple MacBook4        | 3         | 0.66%   |
| Acer Nitro            | 3         | 0.66%   |
| Toshiba PORTEGE       | 2         | 0.44%   |
| Timi TM1613           | 2         | 0.44%   |
| Packard Bell EasyNote | 2         | 0.44%   |
| MSI Prestige          | 2         | 0.44%   |
| Lenovo G550           | 2         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 53        | 11.73%  |
| 2021 | 43        | 9.51%   |
| 2019 | 41        | 9.07%   |
| 2018 | 40        | 8.85%   |
| 2012 | 39        | 8.63%   |
| 2013 | 38        | 8.41%   |
| 2016 | 32        | 7.08%   |
| 2011 | 32        | 7.08%   |
| 2015 | 27        | 5.97%   |
| 2017 | 25        | 5.53%   |
| 2010 | 25        | 5.53%   |
| 2014 | 19        | 4.2%    |
| 2009 | 17        | 3.76%   |
| 2008 | 15        | 3.32%   |
| 2022 | 4         | 0.88%   |
| 2007 | 1         | 0.22%   |
| 2006 | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 452       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 375       | 82.24%  |
| Enabled  | 81        | 17.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 447       | 98.89%  |
| Yes  | 5         | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 165       | 36.18%  |
| 3.01-4.0    | 102       | 22.37%  |
| 16.01-24.0  | 76        | 16.67%  |
| 8.01-16.0   | 74        | 16.23%  |
| 32.01-64.0  | 18        | 3.95%   |
| 1.01-2.0    | 13        | 2.85%   |
| 64.01-256.0 | 4         | 0.88%   |
| 24.01-32.0  | 2         | 0.44%   |
| 2.01-3.0    | 2         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 176       | 36.59%  |
| 2.01-3.0   | 153       | 31.81%  |
| 3.01-4.0   | 74        | 15.38%  |
| 4.01-8.0   | 47        | 9.77%   |
| 0.51-1.0   | 16        | 3.33%   |
| 8.01-16.0  | 13        | 2.7%    |
| 24.01-32.0 | 1         | 0.21%   |
| 16.01-24.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 339       | 74.34%  |
| 2      | 106       | 23.25%  |
| 3      | 6         | 1.32%   |
| 4      | 2         | 0.44%   |
| 0      | 2         | 0.44%   |
| 5      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 309       | 67.91%  |
| Yes       | 146       | 32.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 335       | 74.12%  |
| No        | 117       | 25.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 447       | 98.68%  |
| No        | 6         | 1.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 401       | 88.13%  |
| No        | 54        | 11.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 64        | 14.16%  |
| Germany         | 52        | 11.5%   |
| Russia          | 31        | 6.86%   |
| Brazil          | 30        | 6.64%   |
| Italy           | 24        | 5.31%   |
| UK              | 19        | 4.2%    |
| India           | 18        | 3.98%   |
| France          | 14        | 3.1%    |
| Turkey          | 13        | 2.88%   |
| Mexico          | 13        | 2.88%   |
| Indonesia       | 12        | 2.65%   |
| Spain           | 11        | 2.43%   |
| Poland          | 10        | 2.21%   |
| Canada          | 10        | 2.21%   |
| Belgium         | 10        | 2.21%   |
| Australia       | 9         | 1.99%   |
| Netherlands     | 8         | 1.77%   |
| Chile           | 7         | 1.55%   |
| Portugal        | 6         | 1.33%   |
| Romania         | 5         | 1.11%   |
| Austria         | 5         | 1.11%   |
| Argentina       | 5         | 1.11%   |
| Switzerland     | 4         | 0.88%   |
| Norway          | 4         | 0.88%   |
| Ukraine         | 3         | 0.66%   |
| South Africa    | 3         | 0.66%   |
| Singapore       | 3         | 0.66%   |
| Pakistan        | 3         | 0.66%   |
| New Zealand     | 3         | 0.66%   |
| Hungary         | 3         | 0.66%   |
| Czechia         | 3         | 0.66%   |
| Belarus         | 3         | 0.66%   |
| Sweden          | 2         | 0.44%   |
| Serbia          | 2         | 0.44%   |
| North Macedonia | 2         | 0.44%   |
| Iceland         | 2         | 0.44%   |
| Greece          | 2         | 0.44%   |
| Estonia         | 2         | 0.44%   |
| Croatia         | 2         | 0.44%   |
| Colombia        | 2         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 12        | 2.53%   |
| Sydney                 | 7         | 1.48%   |
| St Petersburg          | 7         | 1.48%   |
| Milan                  | 5         | 1.05%   |
| Berlin                 | 5         | 1.05%   |
| The Hague              | 4         | 0.84%   |
| Munich                 | 4         | 0.84%   |
| Istanbul               | 4         | 0.84%   |
| Vienna                 | 3         | 0.63%   |
| Sao Paulo              | 3         | 0.63%   |
| Rome                   | 3         | 0.63%   |
| Minsk                  | 3         | 0.63%   |
| Madrid                 | 3         | 0.63%   |
| Hamburg                | 3         | 0.63%   |
| Fortaleza              | 3         | 0.63%   |
| Cologne                | 3         | 0.63%   |
| Bogor                  | 3         | 0.63%   |
| Austin                 | 3         | 0.63%   |
| Yuba City              | 2         | 0.42%   |
| Yaroslavl              | 2         | 0.42%   |
| Warsaw                 | 2         | 0.42%   |
| Tucson                 | 2         | 0.42%   |
| Toronto                | 2         | 0.42%   |
| Singapore              | 2         | 0.42%   |
| Santo André           | 2         | 0.42%   |
| Puebla City            | 2         | 0.42%   |
| Pozza di Fassa         | 2         | 0.42%   |
| Porto                  | 2         | 0.42%   |
| Paris                  | 2         | 0.42%   |
| Mumbai                 | 2         | 0.42%   |
| Monza                  | 2         | 0.42%   |
| Montornès del Vallès | 2         | 0.42%   |
| Krakow                 | 2         | 0.42%   |
| Kingston               | 2         | 0.42%   |
| Khimki                 | 2         | 0.42%   |
| Jakarta                | 2         | 0.42%   |
| Islamabad              | 2         | 0.42%   |
| Hyderabad              | 2         | 0.42%   |
| Harelbeke              | 2         | 0.42%   |
| Frankfurt am Main      | 2         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 80        | 96     | 14.18%  |
| WDC                         | 57        | 66     | 10.11%  |
| Seagate                     | 50        | 54     | 8.87%   |
| Toshiba                     | 42        | 45     | 7.45%   |
| SanDisk                     | 37        | 42     | 6.56%   |
| Unknown                     | 32        | 37     | 5.67%   |
| Kingston                    | 29        | 32     | 5.14%   |
| Apple                       | 24        | 28     | 4.26%   |
| Crucial                     | 23        | 26     | 4.08%   |
| SK hynix                    | 19        | 24     | 3.37%   |
| HGST                        | 18        | 19     | 3.19%   |
| Intel                       | 15        | 21     | 2.66%   |
| A-DATA Technology           | 13        | 14     | 2.3%    |
| Hitachi                     | 11        | 11     | 1.95%   |
| Micron Technology           | 8         | 9      | 1.42%   |
| Phison                      | 7         | 8      | 1.24%   |
| KIOXIA                      | 6         | 7      | 1.06%   |
| China                       | 6         | 6      | 1.06%   |
| Fujitsu                     | 4         | 4      | 0.71%   |
| SPCC                        | 3         | 3      | 0.53%   |
| Silicon Motion              | 3         | 3      | 0.53%   |
| PNY                         | 3         | 4      | 0.53%   |
| JMicron Technology          | 3         | 3      | 0.53%   |
| Unknown                     | 3         | 3      | 0.53%   |
| Yangtze Memory Technologies | 2         | 2      | 0.35%   |
| Union Memory                | 2         | 2      | 0.35%   |
| UMIS                        | 2         | 2      | 0.35%   |
| Transcend                   | 2         | 2      | 0.35%   |
| TO Exter                    | 2         | 2      | 0.35%   |
| OCZ                         | 2         | 3      | 0.35%   |
| Micron/Crucial Technology   | 2         | 2      | 0.35%   |
| LITEON                      | 2         | 2      | 0.35%   |
| KingDian                    | 2         | 2      | 0.35%   |
| FORESEE                     | 2         | 2      | 0.35%   |
| EYOTA                       | 2         | 2      | 0.35%   |
| Apacer                      | 2         | 4      | 0.35%   |
| ZTE                         | 1         | 1      | 0.18%   |
| XPG                         | 1         | 1      | 0.18%   |
| V-GeN                       | 1         | 1      | 0.18%   |
| Timetec                     | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                  | 12        | 2.07%   |
| Toshiba MQ01ABD100 1TB                            | 10        | 1.72%   |
| Samsung NVMe SSD Drive 512GB                      | 9         | 1.55%   |
| Unknown MMC Card  32GB                            | 8         | 1.38%   |
| Kingston SA400S37240G 240GB SSD                   | 8         | 1.38%   |
| SanDisk NVMe SSD Drive 512GB                      | 7         | 1.2%    |
| Unknown MMC Card  64GB                            | 6         | 1.03%   |
| Toshiba MQ01ABF050 500GB                          | 6         | 1.03%   |
| Samsung NVMe SSD Drive 256GB                      | 6         | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 5         | 0.86%   |
| Toshiba MQ04ABF100 1TB                            | 5         | 0.86%   |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 0.86%   |
| Samsung SSD 850 EVO 250GB                         | 5         | 0.86%   |
| HGST HTS545050A7E680 500GB                        | 5         | 0.86%   |
| SK hynix NVMe SSD Drive 256GB                     | 4         | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 4         | 0.69%   |
| Samsung SSD 860 EVO 500GB                         | 4         | 0.69%   |
| Samsung SSD 860 EVO 250GB                         | 4         | 0.69%   |
| Samsung NVMe SSD Drive 1024GB                     | 4         | 0.69%   |
| Intel NVMe SSD Drive 512GB                        | 4         | 0.69%   |
| HGST HTS541010B7E610 1TB                          | 4         | 0.69%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 3         | 0.52%   |
| Unknown MMC Card  16GB                            | 3         | 0.52%   |
| Unknown MMC Card  128GB                           | 3         | 0.52%   |
| Toshiba NVMe SSD Drive 512GB                      | 3         | 0.52%   |
| Toshiba NVMe SSD Drive 256GB                      | 3         | 0.52%   |
| SK hynix NVMe SSD Drive 512GB                     | 3         | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB             | 3         | 0.52%   |
| SanDisk NVMe SSD Drive 1024GB                     | 3         | 0.52%   |
| Samsung SSD 850 EVO 500GB                         | 3         | 0.52%   |
| Samsung NVMe SSD Drive 1TB                        | 3         | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 0.52%   |
| Samsung MZALQ512HBLU-00BL2 512GB                  | 3         | 0.52%   |
| Phison NVMe SSD Drive 1TB                         | 3         | 0.52%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD               | 3         | 0.52%   |
| Kingston SA400S37120G 120GB SSD                   | 3         | 0.52%   |
| HGST HTS721010A9E630 1TB                          | 3         | 0.52%   |
| Apple SSD SM0512G 500GB                           | 3         | 0.52%   |
| Apple SSD SD0256F 256GB                           | 3         | 0.52%   |
| A-DATA SU650 120GB SSD                            | 3         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 54     | 32.05%  |
| WDC                 | 37        | 44     | 23.72%  |
| Toshiba             | 29        | 30     | 18.59%  |
| HGST                | 18        | 19     | 11.54%  |
| Hitachi             | 11        | 11     | 7.05%   |
| Fujitsu             | 4         | 4      | 2.56%   |
| Unknown             | 2         | 2      | 1.28%   |
| StoreJet            | 1         | 1      | 0.64%   |
| Samsung Electronics | 1         | 1      | 0.64%   |
| JMicron Technology  | 1         | 1      | 0.64%   |
| Generic-            | 1         | 1      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 47     | 19.52%  |
| Crucial             | 23        | 26     | 10.95%  |
| Apple               | 21        | 24     | 10%     |
| Kingston            | 20        | 20     | 9.52%   |
| SanDisk             | 17        | 19     | 8.1%    |
| WDC                 | 12        | 12     | 5.71%   |
| A-DATA Technology   | 10        | 10     | 4.76%   |
| China               | 6         | 6      | 2.86%   |
| Intel               | 5         | 5      | 2.38%   |
| Toshiba             | 4         | 4      | 1.9%    |
| Micron Technology   | 4         | 5      | 1.9%    |
| SPCC                | 3         | 3      | 1.43%   |
| PNY                 | 3         | 4      | 1.43%   |
| Transcend           | 2         | 2      | 0.95%   |
| TO Exter            | 2         | 2      | 0.95%   |
| SK hynix            | 2         | 2      | 0.95%   |
| OCZ                 | 2         | 3      | 0.95%   |
| LITEON              | 2         | 2      | 0.95%   |
| FORESEE             | 2         | 2      | 0.95%   |
| Apacer              | 2         | 4      | 0.95%   |
| Teclast             | 1         | 1      | 0.48%   |
| Team                | 1         | 1      | 0.48%   |
| Super Talent        | 1         | 1      | 0.48%   |
| Star                | 1         | 1      | 0.48%   |
| Smartbuy            | 1         | 1      | 0.48%   |
| Pioneer             | 1         | 1      | 0.48%   |
| Pichau              | 1         | 1      | 0.48%   |
| Phison              | 1         | 2      | 0.48%   |
| Patriot             | 1         | 2      | 0.48%   |
| NGFF                | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| Morebeck-N100       | 1         | 1      | 0.48%   |
| MENGMI              | 1         | 1      | 0.48%   |
| Lexar               | 1         | 1      | 0.48%   |
| KingSpec            | 1         | 1      | 0.48%   |
| KingDian            | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| Hewlett-Packard     | 1         | 1      | 0.48%   |
| GOODRAM             | 1         | 1      | 0.48%   |
| Fanxiang            | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 202       | 231    | 37%     |
| HDD     | 154       | 169    | 28.21%  |
| NVMe    | 141       | 185    | 25.82%  |
| MMC     | 32        | 36     | 5.86%   |
| Unknown | 17        | 18     | 3.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 321       | 395    | 62.33%  |
| NVMe | 140       | 184    | 27.18%  |
| MMC  | 32        | 36     | 6.21%   |
| SAS  | 22        | 24     | 4.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 249       | 297    | 72.59%  |
| 0.51-1.0   | 84        | 89     | 24.49%  |
| 1.01-2.0   | 8         | 12     | 2.33%   |
| 4.01-10.0  | 2         | 2      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 190       | 41.39%  |
| 251-500        | 122       | 26.58%  |
| 501-1000       | 67        | 14.6%   |
| 51-100         | 32        | 6.97%   |
| 21-50          | 21        | 4.58%   |
| 1001-2000      | 18        | 3.92%   |
| 2001-3000      | 3         | 0.65%   |
| 1-20           | 3         | 0.65%   |
| More than 3000 | 2         | 0.44%   |
| Unknown        | 1         | 0.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 208       | 43.61%  |
| 21-50     | 129       | 27.04%  |
| 51-100    | 62        | 13%     |
| 101-250   | 41        | 8.6%    |
| 251-500   | 18        | 3.77%   |
| 501-1000  | 12        | 2.52%   |
| 1001-2000 | 5         | 1.05%   |
| 2001-3000 | 1         | 0.21%   |
| Unknown   | 1         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 12.5%   |
| Seagate ST500LM030-2E717D 500GB  | 1         | 1      | 12.5%   |
| Kingston SV300S37A240G 240GB SSD | 1         | 1      | 12.5%   |
| Kingston SUV400S37480G 480GB SSD | 1         | 1      | 12.5%   |
| HGST HTS545050A7E680 500GB       | 1         | 1      | 12.5%   |
| Crucial CT512M550SSD3 512GB      | 1         | 1      | 12.5%   |
| China SSD 256GB                  | 1         | 1      | 12.5%   |
| Apple SSD SM256C 256GB           | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 2         | 2      | 25%     |
| WDC      | 1         | 1      | 12.5%   |
| Seagate  | 1         | 1      | 12.5%   |
| HGST     | 1         | 1      | 12.5%   |
| Crucial  | 1         | 1      | 12.5%   |
| China    | 1         | 1      | 12.5%   |
| Apple    | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5         | 5      | 62.5%   |
| HDD  | 3         | 3      | 37.5%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 393       | 544    | 82.91%  |
| Works    | 73        | 87     | 15.4%   |
| Malfunc  | 8         | 8      | 1.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 303       | 58.61%  |
| AMD                            | 53        | 10.25%  |
| Samsung Electronics            | 49        | 9.48%   |
| SanDisk                        | 26        | 5.03%   |
| SK hynix                       | 16        | 3.09%   |
| Nvidia                         | 10        | 1.93%   |
| Kingston Technology Company    | 10        | 1.93%   |
| Toshiba America Info Systems   | 9         | 1.74%   |
| Phison Electronics             | 7         | 1.35%   |
| Union Memory (Shenzhen)        | 4         | 0.77%   |
| Micron Technology              | 4         | 0.77%   |
| Marvell Technology Group       | 4         | 0.77%   |
| KIOXIA                         | 4         | 0.77%   |
| Silicon Motion                 | 3         | 0.58%   |
| ADATA Technology               | 3         | 0.58%   |
| Yangtze Memory Technologies    | 2         | 0.39%   |
| Realtek Semiconductor          | 2         | 0.39%   |
| Micron/Crucial Technology      | 2         | 0.39%   |
| Apple                          | 2         | 0.39%   |
| Solid State Storage Technology | 1         | 0.19%   |
| Lite-On Technology             | 1         | 0.19%   |
| Biwin Storage Technology       | 1         | 0.19%   |
| ASMedia Technology             | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 50        | 9.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 41        | 7.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 39        | 7.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 32        | 5.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 20        | 3.67%   |
| Samsung NVMe SSD Controller 980                                                        | 17        | 3.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 15        | 2.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 15        | 2.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 14        | 2.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 14        | 2.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 13        | 2.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 12        | 2.2%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 11        | 2.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 2.02%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 10        | 1.83%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 9         | 1.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 8         | 1.47%   |
| Nvidia MCP79 AHCI Controller                                                           | 8         | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 8         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 8         | 1.47%   |
| Samsung Electronics SATA controller                                                    | 7         | 1.28%   |
| Intel SSD 660P Series                                                                  | 7         | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 7         | 1.28%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 6         | 1.1%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 6         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 6         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 6         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 5         | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 5         | 0.92%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 4         | 0.73%   |
| SK hynix BC511                                                                         | 4         | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 4         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 0.73%   |
| Micron NVMe Storage Controller                                                         | 4         | 0.73%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 4         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 4         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.73%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 337       | 64.07%  |
| NVMe | 136       | 25.86%  |
| RAID | 32        | 6.08%   |
| IDE  | 21        | 3.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 373       | 82.52%  |
| AMD    | 79        | 17.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 15        | 3.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 2.21%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 1.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.55%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 1.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.33%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 1.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 1.11%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 1.11%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 1.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.88%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 0.88%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.88%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.88%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 4         | 0.88%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.88%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.88%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.88%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.66%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.66%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 3         | 0.66%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 0.66%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 3         | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.66%   |
| Intel Core i5-4250U CPU @ 1.30GHz             | 3         | 0.66%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.66%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.66%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.66%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.66%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.66%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 110       | 24.34%  |
| Intel Core i7           | 101       | 22.35%  |
| Intel Core i3           | 47        | 10.4%   |
| Other                   | 38        | 8.41%   |
| Intel Celeron           | 30        | 6.64%   |
| AMD Ryzen 5             | 28        | 6.19%   |
| Intel Core 2 Duo        | 22        | 4.87%   |
| Intel Pentium           | 9         | 1.99%   |
| AMD Ryzen 7             | 9         | 1.99%   |
| AMD A10                 | 6         | 1.33%   |
| Intel Pentium Silver    | 5         | 1.11%   |
| AMD A6                  | 5         | 1.11%   |
| Intel Atom              | 4         | 0.88%   |
| AMD Ryzen 3             | 4         | 0.88%   |
| AMD A8                  | 4         | 0.88%   |
| Intel Pentium Dual-Core | 3         | 0.66%   |
| AMD Ryzen 7 PRO         | 3         | 0.66%   |
| AMD A4                  | 3         | 0.66%   |
| AMD A12                 | 3         | 0.66%   |
| Intel Genuine           | 2         | 0.44%   |
| Intel Celeron Dual-Core | 2         | 0.44%   |
| AMD Ryzen 9             | 2         | 0.44%   |
| AMD Ryzen 5 PRO         | 2         | 0.44%   |
| AMD E1                  | 2         | 0.44%   |
| Intel Pentium Dual      | 1         | 0.22%   |
| Intel Core m5           | 1         | 0.22%   |
| Intel Core m3           | 1         | 0.22%   |
| Intel Core i9           | 1         | 0.22%   |
| Intel Core 2 Quad       | 1         | 0.22%   |
| Intel Core 2            | 1         | 0.22%   |
| AMD Phenom II           | 1         | 0.22%   |
| AMD E                   | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 249       | 55.09%  |
| 4      | 153       | 33.85%  |
| 6      | 27        | 5.97%   |
| 8      | 20        | 4.42%   |
| 1      | 3         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 452       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 345       | 76.16%  |
| 1      | 108       | 23.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 452       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 41        | 8.93%   |
| 0x306a9    | 36        | 7.84%   |
| Unknown    | 31        | 6.75%   |
| 0x806c1    | 25        | 5.45%   |
| 0x40651    | 19        | 4.14%   |
| 0x306d4    | 19        | 4.14%   |
| 0x1067a    | 18        | 3.92%   |
| 0x806e9    | 17        | 3.7%    |
| 0x20655    | 17        | 3.7%    |
| 0x806ec    | 16        | 3.49%   |
| 0x406e3    | 15        | 3.27%   |
| 0x806ea    | 14        | 3.05%   |
| 0x306c3    | 11        | 2.4%    |
| 0xa0652    | 10        | 2.18%   |
| 0x10676    | 8         | 1.74%   |
| 0x08608103 | 8         | 1.74%   |
| 0x08600106 | 8         | 1.74%   |
| 0x08108109 | 8         | 1.74%   |
| 0x06006705 | 8         | 1.74%   |
| 0x706a8    | 7         | 1.53%   |
| 0x706a1    | 7         | 1.53%   |
| 0x506c9    | 7         | 1.53%   |
| 0x20652    | 7         | 1.53%   |
| 0x806eb    | 6         | 1.31%   |
| 0x706e5    | 6         | 1.31%   |
| 0x406c3    | 6         | 1.31%   |
| 0x40661    | 6         | 1.31%   |
| 0x906ea    | 5         | 1.09%   |
| 0x0a50000c | 5         | 1.09%   |
| 0x06001119 | 5         | 1.09%   |
| 0x906e9    | 4         | 0.87%   |
| 0x6fd      | 4         | 0.87%   |
| 0x406c4    | 4         | 0.87%   |
| 0x08108102 | 4         | 0.87%   |
| 0x806c2    | 3         | 0.65%   |
| 0x30678    | 3         | 0.65%   |
| 0x08600104 | 3         | 0.65%   |
| 0x0810100b | 3         | 0.65%   |
| 0x08101007 | 3         | 0.65%   |
| 0x07030105 | 3         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 70        | 15.49%  |
| SandyBridge   | 42        | 9.29%   |
| Haswell       | 38        | 8.41%   |
| IvyBridge     | 37        | 8.19%   |
| TigerLake     | 29        | 6.42%   |
| Penryn        | 26        | 5.75%   |
| Westmere      | 24        | 5.31%   |
| Broadwell     | 20        | 4.42%   |
| Skylake       | 18        | 3.98%   |
| Excavator     | 16        | 3.54%   |
| Goldmont plus | 15        | 3.32%   |
| Zen 2         | 14        | 3.1%    |
| Silvermont    | 14        | 3.1%    |
| Zen+          | 13        | 2.88%   |
| CometLake     | 11        | 2.43%   |
| Unknown       | 11        | 2.43%   |
| IceLake       | 10        | 2.21%   |
| Goldmont      | 7         | 1.55%   |
| Core          | 7         | 1.55%   |
| Zen           | 6         | 1.33%   |
| Zen 3         | 5         | 1.11%   |
| Piledriver    | 5         | 1.11%   |
| Puma          | 4         | 0.88%   |
| Nehalem       | 2         | 0.44%   |
| Jaguar        | 2         | 0.44%   |
| Bobcat        | 2         | 0.44%   |
| Tremont       | 1         | 0.22%   |
| K10 Llano     | 1         | 0.22%   |
| K10           | 1         | 0.22%   |
| Bonnell       | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 337       | 59.96%  |
| AMD    | 121       | 21.53%  |
| Nvidia | 104       | 18.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 38        | 6.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 35        | 5.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 4.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 3.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 3.25%   |
| Intel HD Graphics 620                                                                    | 17        | 2.91%   |
| Intel HD Graphics 5500                                                                   | 15        | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 2.56%   |
| AMD Renoir                                                                               | 14        | 2.39%   |
| Intel UHD Graphics 620                                                                   | 13        | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 2.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 10        | 1.71%   |
| AMD Lucienne                                                                             | 10        | 1.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.54%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.54%   |
| Nvidia C79 [GeForce 9400M]                                                               | 8         | 1.37%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 1.2%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 1.2%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.2%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 1.2%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 1.03%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.03%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.03%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 0.85%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.68%   |
| Intel HD Graphics 500                                                                    | 4         | 0.68%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 4         | 0.68%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.68%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.68%   |
| Nvidia TU117M                                                                            | 3         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 231       | 51.11%  |
| Intel + Nvidia | 76        | 16.81%  |
| 1 x AMD        | 73        | 16.15%  |
| Intel + AMD    | 29        | 6.42%   |
| 1 x Nvidia     | 21        | 4.65%   |
| 2 x AMD        | 14        | 3.1%    |
| AMD + Nvidia   | 5         | 1.11%   |
| 2 x Nvidia     | 2         | 0.44%   |
| Other          | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 403       | 88.77%  |
| Proprietary | 48        | 10.57%  |
| Unknown     | 3         | 0.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 273       | 59.87%  |
| 0.01-0.5   | 63        | 13.82%  |
| 1.01-2.0   | 60        | 13.16%  |
| 0.51-1.0   | 38        | 8.33%   |
| 3.01-4.0   | 12        | 2.63%   |
| 5.01-6.0   | 8         | 1.75%   |
| 7.01-8.0   | 2         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 91        | 18.02%  |
| LG Display              | 69        | 13.66%  |
| BOE                     | 69        | 13.66%  |
| Chimei Innolux          | 66        | 13.07%  |
| Apple                   | 51        | 10.1%   |
| Samsung Electronics     | 39        | 7.72%   |
| Sharp                   | 12        | 2.38%   |
| Lenovo                  | 11        | 2.18%   |
| Dell                    | 11        | 2.18%   |
| Chi Mei Optoelectronics | 10        | 1.98%   |
| PANDA                   | 9         | 1.78%   |
| Hewlett-Packard         | 8         | 1.58%   |
| Goldstar                | 6         | 1.19%   |
| CSO                     | 6         | 1.19%   |
| ViewSonic               | 4         | 0.79%   |
| Sony                    | 4         | 0.79%   |
| InfoVision              | 3         | 0.59%   |
| BenQ                    | 3         | 0.59%   |
| AOC                     | 3         | 0.59%   |
| Acer                    | 3         | 0.59%   |
| Philips                 | 2         | 0.4%    |
| Toshiba                 | 1         | 0.2%    |
| TopView                 | 1         | 0.2%    |
| TMX                     | 1         | 0.2%    |
| Tianma XM               | 1         | 0.2%    |
| Tech Concepts           | 1         | 0.2%    |
| SKG                     | 1         | 0.2%    |
| SANYO                   | 1         | 0.2%    |
| Plain Tree Systems      | 1         | 0.2%    |
| Panasonic               | 1         | 0.2%    |
| Packard Bell            | 1         | 0.2%    |
| LG Philips              | 1         | 0.2%    |
| LG Electronics          | 1         | 0.2%    |
| Konka                   | 1         | 0.2%    |
| KDC                     | 1         | 0.2%    |
| JDI                     | 1         | 0.2%    |
| Iiyama                  | 1         | 0.2%    |
| HUAWEI                  | 1         | 0.2%    |
| HJC                     | 1         | 0.2%    |
| HannStar                | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 1.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 7         | 1.36%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.97%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 5         | 0.97%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.97%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 5         | 0.97%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 5         | 0.97%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.78%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 4         | 0.78%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 4         | 0.78%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 4         | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.78%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 4         | 0.78%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 4         | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 3         | 0.58%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.58%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 0.58%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 3         | 0.58%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 0.58%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.58%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 3         | 0.58%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 3         | 0.58%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.39%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.39%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.39%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.39%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.39%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 2         | 0.39%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 2         | 0.39%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 193       | 40.12%  |
| 1366x768 (WXGA)    | 149       | 30.98%  |
| 1600x900 (HD+)     | 25        | 5.2%    |
| 1440x900 (WXGA+)   | 21        | 4.37%   |
| 1280x800 (WXGA)    | 20        | 4.16%   |
| 3840x2160 (4K)     | 13        | 2.7%    |
| 2560x1440 (QHD)    | 13        | 2.7%    |
| 2880x1800          | 10        | 2.08%   |
| 3000x2000          | 6         | 1.25%   |
| 1920x1200 (WUXGA)  | 6         | 1.25%   |
| 2560x1600          | 4         | 0.83%   |
| 3200x1800 (QHD+)   | 3         | 0.62%   |
| 3840x2400          | 2         | 0.42%   |
| 2560x1080          | 2         | 0.42%   |
| 1680x1050 (WSXGA+) | 2         | 0.42%   |
| 1280x1024 (SXGA)   | 2         | 0.42%   |
| 4240x1080          | 1         | 0.21%   |
| 3840x1100          | 1         | 0.21%   |
| 3072x1920          | 1         | 0.21%   |
| 2160x1440          | 1         | 0.21%   |
| 1920x540           | 1         | 0.21%   |
| 1920x1280          | 1         | 0.21%   |
| 1400x1050          | 1         | 0.21%   |
| 1360x768           | 1         | 0.21%   |
| 1024x600           | 1         | 0.21%   |
| Unknown            | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 194       | 38.34%  |
| 13      | 102       | 20.16%  |
| 14      | 73        | 14.43%  |
| 17      | 35        | 6.92%   |
| 27      | 15        | 2.96%   |
| 11      | 14        | 2.77%   |
| 23      | 13        | 2.57%   |
| 24      | 12        | 2.37%   |
| 12      | 10        | 1.98%   |
| 16      | 5         | 0.99%   |
| Unknown | 5         | 0.99%   |
| 31      | 4         | 0.79%   |
| 21      | 4         | 0.79%   |
| 84      | 3         | 0.59%   |
| 72      | 2         | 0.4%    |
| 52      | 2         | 0.4%    |
| 34      | 2         | 0.4%    |
| 25      | 2         | 0.4%    |
| 18      | 2         | 0.4%    |
| 47      | 1         | 0.2%    |
| 43      | 1         | 0.2%    |
| 33      | 1         | 0.2%    |
| 22      | 1         | 0.2%    |
| 20      | 1         | 0.2%    |
| 19      | 1         | 0.2%    |
| 10      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 304       | 60.68%  |
| 201-300     | 85        | 16.97%  |
| 351-400     | 42        | 8.38%   |
| 501-600     | 40        | 7.98%   |
| 401-500     | 9         | 1.8%    |
| 1501-2000   | 5         | 1%      |
| Unknown     | 5         | 1%      |
| 601-700     | 4         | 0.8%    |
| 701-800     | 3         | 0.6%    |
| 1001-1500   | 3         | 0.6%    |
| 901-1000    | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 368       | 81.24%  |
| 16/10   | 64        | 14.13%  |
| 3/2     | 11        | 2.43%   |
| Unknown | 4         | 0.88%   |
| 5/4     | 2         | 0.44%   |
| 21/9    | 2         | 0.44%   |
| 4/3     | 1         | 0.22%   |
| 3.40    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 194       | 38.49%  |
| 81-90          | 136       | 26.98%  |
| 71-80          | 38        | 7.54%   |
| 121-130        | 29        | 5.75%   |
| 201-250        | 23        | 4.56%   |
| 51-60          | 15        | 2.98%   |
| 301-350        | 15        | 2.98%   |
| 61-70          | 10        | 1.98%   |
| More than 1000 | 7         | 1.39%   |
| 351-500        | 7         | 1.39%   |
| 251-300        | 6         | 1.19%   |
| Unknown        | 5         | 0.99%   |
| 141-150        | 4         | 0.79%   |
| 131-140        | 4         | 0.79%   |
| 111-120        | 4         | 0.79%   |
| 151-200        | 3         | 0.6%    |
| 501-1000       | 2         | 0.4%    |
| 41-50          | 1         | 0.2%    |
| 91-100         | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 204       | 41.05%  |
| 101-120       | 170       | 34.21%  |
| 51-100        | 60        | 12.07%  |
| 161-240       | 35        | 7.04%   |
| More than 240 | 19        | 3.82%   |
| Unknown       | 5         | 1.01%   |
| 1-50          | 4         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 390       | 85.34%  |
| 2     | 57        | 12.47%  |
| 3     | 7         | 1.53%   |
| 0     | 2         | 0.44%   |
| 4     | 1         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 217       | 31.49%  |
| Intel                             | 207       | 30.04%  |
| Qualcomm Atheros                  | 103       | 14.95%  |
| Broadcom                          | 69        | 10.01%  |
| Broadcom Limited                  | 19        | 2.76%   |
| Marvell Technology Group          | 10        | 1.45%   |
| Nvidia                            | 9         | 1.31%   |
| Ralink                            | 6         | 0.87%   |
| MediaTek                          | 6         | 0.87%   |
| TP-Link                           | 5         | 0.73%   |
| ASIX Electronics                  | 4         | 0.58%   |
| Xiaomi                            | 3         | 0.44%   |
| Sierra Wireless                   | 3         | 0.44%   |
| Ralink Technology                 | 3         | 0.44%   |
| Lenovo                            | 3         | 0.44%   |
| D-Link                            | 3         | 0.44%   |
| Huawei Technologies               | 2         | 0.29%   |
| Google                            | 2         | 0.29%   |
| Apple                             | 2         | 0.29%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.15%   |
| TRENDnet                          | 1         | 0.15%   |
| Sitecom Europe                    | 1         | 0.15%   |
| Samsung Electronics               | 1         | 0.15%   |
| Qualcomm                          | 1         | 0.15%   |
| OPPO Electronics                  | 1         | 0.15%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |
| Edimax Technology                 | 1         | 0.15%   |
| Dell                              | 1         | 0.15%   |
| ADMtek                            | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 128       | 15.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44        | 5.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 27        | 3.27%   |
| Intel Wi-Fi 6 AX201                                               | 23        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 2.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 16        | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 1.94%   |
| Intel Wireless 8260                                               | 15        | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.69%   |
| Intel Wireless 8265 / 8275                                        | 14        | 1.69%   |
| Intel Wireless 7265                                               | 13        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 1.57%   |
| Intel Wireless 7260                                               | 12        | 1.45%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 11        | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 1.21%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 10        | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 1.09%   |
| Nvidia MCP79 Ethernet                                             | 9         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.09%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 9         | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.97%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 8         | 0.97%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 7         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.73%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.61%   |
| Intel Wireless 3165                                               | 5         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 198       | 42.31%  |
| Qualcomm Atheros      | 90        | 19.23%  |
| Realtek Semiconductor | 71        | 15.17%  |
| Broadcom              | 65        | 13.89%  |
| Broadcom Limited      | 17        | 3.63%   |
| Ralink                | 6         | 1.28%   |
| TP-Link               | 5         | 1.07%   |
| MediaTek              | 4         | 0.85%   |
| Ralink Technology     | 3         | 0.64%   |
| D-Link                | 3         | 0.64%   |
| Sierra Wireless       | 2         | 0.43%   |
| TRENDnet              | 1         | 0.21%   |
| Sitecom Europe        | 1         | 0.21%   |
| Qualcomm              | 1         | 0.21%   |
| Edimax Technology     | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 27        | 5.73%   |
| Intel Wi-Fi 6 AX201                                            | 23        | 4.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16        | 3.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 3.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 3.4%    |
| Intel Wireless 8260                                            | 15        | 3.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 3.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 14        | 2.97%   |
| Intel Wireless 8265 / 8275                                     | 14        | 2.97%   |
| Intel Wireless 7265                                            | 13        | 2.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 13        | 2.76%   |
| Intel Wireless 7260                                            | 12        | 2.55%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 2.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 2.34%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 11        | 2.34%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 10        | 2.12%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.91%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 9         | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 8         | 1.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 7         | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1.27%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.06%   |
| Intel Wireless 3165                                            | 5         | 1.06%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.06%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 5         | 1.06%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 5         | 1.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 5         | 1.06%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.85%   |
| Intel Ultimate N WiFi Link 5300                                | 4         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 187       | 54.05%  |
| Intel                      | 67        | 19.36%  |
| Qualcomm Atheros           | 25        | 7.23%   |
| Broadcom                   | 22        | 6.36%   |
| Marvell Technology Group   | 10        | 2.89%   |
| Nvidia                     | 9         | 2.6%    |
| ASIX Electronics           | 4         | 1.16%   |
| Xiaomi                     | 3         | 0.87%   |
| Lenovo                     | 3         | 0.87%   |
| Broadcom Limited           | 3         | 0.87%   |
| MediaTek                   | 2         | 0.58%   |
| Google                     | 2         | 0.58%   |
| Apple                      | 2         | 0.58%   |
| ZTE WCDMA Technologies MSM | 1         | 0.29%   |
| Sierra Wireless            | 1         | 0.29%   |
| OPPO Electronics           | 1         | 0.29%   |
| JMicron Technology         | 1         | 0.29%   |
| Huawei Technologies        | 1         | 0.29%   |
| Hewlett-Packard            | 1         | 0.29%   |
| ADMtek                     | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 128       | 36.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 44        | 12.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 4.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 3.14%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 10        | 2.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 9         | 2.57%   |
| Nvidia MCP79 Ethernet                                                          | 9         | 2.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.43%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 1.43%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 4         | 1.14%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.14%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 0.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.86%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.86%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.86%   |
| Lenovo ThinkPad Lan                                                            | 3         | 0.86%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.86%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.57%   |
| MediaTek PRESIDENT_GOLD_10                                                     | 2         | 0.57%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.57%   |
| Intel Ethernet Connection I218-V                                               | 2         | 0.57%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.57%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.57%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 0.57%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.57%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.57%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.57%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                            | 1         | 0.29%   |
| Sierra Wireless EM7345 4G LTE                                                  | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 449       | 57.05%  |
| Ethernet | 333       | 42.31%  |
| Modem    | 4         | 0.51%   |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 383       | 83.81%  |
| Ethernet | 74        | 16.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 306       | 67.55%  |
| 1     | 136       | 30.02%  |
| 0     | 8         | 1.77%   |
| 3     | 3         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 312       | 67.97%  |
| Yes  | 147       | 32.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 165       | 40.64%  |
| Apple                           | 51        | 12.56%  |
| Realtek Semiconductor           | 41        | 10.1%   |
| Qualcomm Atheros Communications | 36        | 8.87%   |
| Lite-On Technology              | 20        | 4.93%   |
| Broadcom                        | 20        | 4.93%   |
| Foxconn / Hon Hai               | 17        | 4.19%   |
| IMC Networks                    | 16        | 3.94%   |
| Hewlett-Packard                 | 9         | 2.22%   |
| Toshiba                         | 7         | 1.72%   |
| Realtek                         | 6         | 1.48%   |
| Dell                            | 6         | 1.48%   |
| Ralink                          | 5         | 1.23%   |
| Cambridge Silicon Radio         | 5         | 1.23%   |
| ASUSTek Computer                | 2         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 66        | 16.26%  |
| Intel AX201 Bluetooth                                                               | 40        | 9.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 31        | 7.64%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 27        | 6.65%   |
| Apple Bluetooth Host Controller                                                     | 26        | 6.4%    |
| Realtek Bluetooth Radio                                                             | 21        | 5.17%   |
| Apple Bluetooth USB Host Controller                                                 | 16        | 3.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 3.2%    |
| Intel AX200 Bluetooth                                                               | 12        | 2.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 8         | 1.97%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 1.97%   |
| Realtek 802.11ac WLAN Adapter                                                       | 6         | 1.48%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 1.48%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 1.23%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.23%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.23%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 5         | 1.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 1.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 1.23%   |
| Apple Bluetooth HCI                                                                 | 5         | 1.23%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.99%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.99%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.99%   |
| IMC Networks Bluetooth Device                                                       | 4         | 0.99%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.99%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 0.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 0.74%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.74%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.74%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.74%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.74%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.74%   |
| Toshiba RT Bluetooth Radio                                                          | 2         | 0.49%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.49%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.49%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 360       | 67.42%  |
| AMD                     | 99        | 18.54%  |
| Nvidia                  | 56        | 10.49%  |
| Logitech                | 3         | 0.56%   |
| Texas Instruments       | 2         | 0.37%   |
| ESS Technology          | 2         | 0.37%   |
| C-Media Electronics     | 2         | 0.37%   |
| SteelSeries ApS         | 1         | 0.19%   |
| Realtek Semiconductor   | 1         | 0.19%   |
| No brand                | 1         | 0.19%   |
| Midiplus                | 1         | 0.19%   |
| Huawei Technologies     | 1         | 0.19%   |
| Goldvish                | 1         | 0.19%   |
| Generalplus Technology  | 1         | 0.19%   |
| Dell                    | 1         | 0.19%   |
| BEHRINGER International | 1         | 0.19%   |
| Apple                   | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 49        | 7.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 45        | 6.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 42        | 6.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 37        | 5.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 29        | 4.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 4.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 3.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 3.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 3.02%   |
| Intel Broadwell-U Audio Controller                                                                | 20        | 3.02%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 3.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18        | 2.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 2.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 15        | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 2.26%   |
| AMD FCH Azalia Controller                                                                         | 13        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 1.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 1.51%   |
| AMD High Definition Audio Controller                                                              | 10        | 1.51%   |
| Nvidia MCP79 High Definition Audio                                                                | 9         | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.21%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 1.06%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 7         | 1.06%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.6%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.45%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 32.43%  |
| SK hynix            | 25        | 22.52%  |
| Micron Technology   | 19        | 17.12%  |
| Kingston            | 6         | 5.41%   |
| Crucial             | 4         | 3.6%    |
| Unknown (ABCD)      | 3         | 2.7%    |
| Unknown             | 3         | 2.7%    |
| G.Skill             | 3         | 2.7%    |
| Elpida              | 3         | 2.7%    |
| A-DATA Technology   | 3         | 2.7%    |
| Ramaxel Technology  | 2         | 1.8%    |
| Transcend           | 1         | 0.9%    |
| Team                | 1         | 0.9%    |
| SHARETRONIC         | 1         | 0.9%    |
| GSkill              | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 4         | 3.36%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 2.52%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 3         | 2.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.52%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 2         | 1.68%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.68%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.68%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.68%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 2         | 1.68%   |
| Unknown RAM Module 8192MB SODIMM DDR3                            | 1         | 0.84%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.84%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 1         | 0.84%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 0.84%   |
| Team RAM TEAMGROUP-SD4-2400 16384MB SODIMM DDR4 2400MT/s         | 1         | 0.84%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 0.84%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.84%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.84%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.84%   |
| SK hynix RAM HMP351S6AFR8C-S6 4GB SODIMM DDR2 800MT/s            | 1         | 0.84%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.84%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.84%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s           | 1         | 0.84%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 0.84%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 0.84%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.84%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.84%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.84%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 0.84%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 49        | 50%     |
| DDR3   | 30        | 30.61%  |
| LPDDR4 | 13        | 13.27%  |
| LPDDR3 | 3         | 3.06%   |
| DDR2   | 2         | 2.04%   |
| SDRAM  | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 84.69%  |
| Row Of Chips | 14        | 14.29%  |
| Chip         | 1         | 1.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 52        | 47.71%  |
| 4096  | 32        | 29.36%  |
| 2048  | 13        | 11.93%  |
| 16384 | 10        | 9.17%   |
| 32768 | 2         | 1.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 22        | 20.56%  |
| 1600    | 22        | 20.56%  |
| 3200    | 21        | 19.63%  |
| 2400    | 11        | 10.28%  |
| 4267    | 7         | 6.54%   |
| 2133    | 5         | 4.67%   |
| 8400    | 3         | 2.8%    |
| 1334    | 3         | 2.8%    |
| 1333    | 3         | 2.8%    |
| 3266    | 2         | 1.87%   |
| 1867    | 2         | 1.87%   |
| 4266    | 1         | 0.93%   |
| 4199    | 1         | 0.93%   |
| 1066    | 1         | 0.93%   |
| 800     | 1         | 0.93%   |
| 667     | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 2         | 28.57%  |
| Xerox                           | 1         | 14.29%  |
| Seiko Epson                     | 1         | 14.29%  |
| Samsung Electronics             | 1         | 14.29%  |
| Prolific Technology             | 1         | 14.29%  |
| cab Produkttechnik GmbH & Co KG | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Xerox Phaser 3610                        | 1         | 14.29%  |
| Seiko Epson L355 Series                  | 1         | 14.29%  |
| Samsung M2020 Series                     | 1         | 14.29%  |
| Prolific PL2305 Parallel Port            | 1         | 14.29%  |
| Canon PIXMA MG2500 Series                | 1         | 14.29%  |
| Canon G3000 series                       | 1         | 14.29%  |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 14.29%  |

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
| Chicony Electronics                    | 93        | 22.25%  |
| IMC Networks                           | 46        | 11%     |
| Apple                                  | 37        | 8.85%   |
| Realtek Semiconductor                  | 34        | 8.13%   |
| Quanta                                 | 27        | 6.46%   |
| Microdia                               | 26        | 6.22%   |
| Bison Electronics                      | 22        | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 21        | 5.02%   |
| Sunplus Innovation Technology          | 18        | 4.31%   |
| Suyin                                  | 16        | 3.83%   |
| Acer                                   | 15        | 3.59%   |
| Syntek                                 | 13        | 3.11%   |
| Alcor Micro                            | 9         | 2.15%   |
| Silicon Motion                         | 8         | 1.91%   |
| Luxvisions Innotech Limited            | 5         | 1.2%    |
| Lenovo                                 | 4         | 0.96%   |
| Logitech                               | 3         | 0.72%   |
| Lite-On Technology                     | 3         | 0.72%   |
| Ricoh                                  | 2         | 0.48%   |
| Primax Electronics                     | 2         | 0.48%   |
| KYE Systems (Mouse Systems)            | 2         | 0.48%   |
| Importek                               | 2         | 0.48%   |
| Foxconn / Hon Hai                      | 2         | 0.48%   |
| ALi                                    | 2         | 0.48%   |
| Y Media                                | 1         | 0.24%   |
| Sony                                   | 1         | 0.24%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.24%   |
| Samsung Electronics                    | 1         | 0.24%   |
| kingcome                               | 1         | 0.24%   |
| Google                                 | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 26        | 6.19%   |
| IMC Networks USB2.0 HD UVC WebCam                | 15        | 3.57%   |
| IMC Networks Integrated Camera                   | 12        | 2.86%   |
| Apple Built-in iSight                            | 12        | 2.86%   |
| Microdia Integrated_Webcam_HD                    | 10        | 2.38%   |
| Chicony HD WebCam                                | 10        | 2.38%   |
| Apple FaceTime HD Camera                         | 10        | 2.38%   |
| Syntek Integrated Camera                         | 9         | 2.14%   |
| Realtek Integrated_Webcam_HD                     | 8         | 1.9%    |
| Sunplus Integrated_Webcam_HD                     | 6         | 1.43%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 6         | 1.43%   |
| Acer Integrated Camera                           | 6         | 1.43%   |
| Quanta HP Webcam                                 | 5         | 1.19%   |
| Quanta HP TrueVision HD Camera                   | 5         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 5         | 1.19%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 5         | 1.19%   |
| Realtek USB2.0 HD UVC WebCam                     | 4         | 0.95%   |
| Realtek USB Camera                               | 4         | 0.95%   |
| Quanta VGA WebCam                                | 4         | 0.95%   |
| Quanta HD User Facing                            | 4         | 0.95%   |
| Chicony USB 2.0 Camera                           | 4         | 0.95%   |
| Chicony EasyCamera                               | 4         | 0.95%   |
| Bison HD Webcam                                  | 4         | 0.95%   |
| Bison EasyCamera                                 | 4         | 0.95%   |
| Apple FaceTime Camera                            | 4         | 0.95%   |
| Alcor Micro SHUNCCM2MP                           | 4         | 0.95%   |
| Syntek EasyCamera                                | 3         | 0.71%   |
| Sunplus HP HD Webcam [Fixed]                     | 3         | 0.71%   |
| Realtek USB2.0 VGA UVC WebCam                    | 3         | 0.71%   |
| Realtek Integrated Webcam                        | 3         | 0.71%   |
| Microdia USB 2.0 Camera                          | 3         | 0.71%   |
| IMC Networks USB2.0 UVC HD Webcam                | 3         | 0.71%   |
| IMC Networks ov9734_azurewave_camera             | 3         | 0.71%   |
| Chicony VGA WebCam                               | 3         | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 0.71%   |
| Chicony Lenovo EasyCamera                        | 3         | 0.71%   |
| Chicony HP TrueVision HD Camera                  | 3         | 0.71%   |
| Chicony HP Truevision HD                         | 3         | 0.71%   |
| Chicony HP HD Webcam [Fixed]                     | 3         | 0.71%   |
| Chicony HP HD Webcam                             | 3         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 33.33%  |
| Synaptics                  | 20        | 26.67%  |
| Shenzhen Goodix Technology | 15        | 20%     |
| Upek                       | 6         | 8%      |
| LighTuning Technology      | 6         | 8%      |
| Elan Microelectronics      | 2         | 2.67%   |
| AuthenTec                  | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 13        | 17.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 7         | 9.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 6         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader                | 5         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 5         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 4         | 5.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 4         | 5.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 4         | 5.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 5.33%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 4%      |
| Validity Sensors VFS491                                    | 3         | 4%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 4%      |
| Validity Sensors VFS301 Fingerprint Reader                 | 2         | 2.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 2.67%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 1.33%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 1.33%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.33%   |
| Synaptics WBDI                                             | 1         | 1.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.33%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 1.33%   |
| Shenzhen Goodix FingerPrint                                | 1         | 1.33%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.33%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.33%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 11        | 42.31%  |
| Alcor Micro           | 7         | 26.92%  |
| Lenovo                | 4         | 15.38%  |
| O2 Micro              | 2         | 7.69%   |
| Upek                  | 1         | 3.85%   |
| Gemalto (was Gemplus) | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 26.92%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 23.08%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 7.69%   |
| Broadcom 58200                                                               | 2         | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.85%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 3.85%   |
| Broadcom 5880                                                                | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 303       | 66.45%  |
| 1     | 119       | 26.1%   |
| 2     | 32        | 7.02%   |
| 3     | 2         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 74        | 39.57%  |
| Multimedia controller | 30        | 16.04%  |
| Chipcard              | 25        | 13.37%  |
| Net/wireless          | 23        | 12.3%   |
| Graphics card         | 18        | 9.63%   |
| Bluetooth             | 5         | 2.67%   |
| Camera                | 4         | 2.14%   |
| Net/ethernet          | 3         | 1.6%    |
| Card reader           | 3         | 1.6%    |
| Storage               | 2         | 1.07%   |

