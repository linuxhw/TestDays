Kubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

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

Total: 420

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | 255 G8 Notebook PC          | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Google        | Blooglet                    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Acer          | Aspire S3-391               | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| Dell          | Latitude 7430               | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Acer          | Predator G3-571             | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| HP            | Notebook                    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Toshiba       | Satellite P70-B             | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCXR            | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Dell          | Precision 3571              | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | Latitude 5590               | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | EliteBook 8470p             | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Dell          | Latitude 5420               | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Dell          | Latitude 5590               | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Intel         | Unknown                     | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| Dell          | Latitude 5590               | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Unknown       | Unknown                     | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Chuwi         | CoreBook X                  | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Jumper        | EZpad                       | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Haier         | A1420EM                     | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Dell          | Latitude 5590               | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Lenovo        | V130-15IGM 81HL             | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| Jumper        | EZpad                       | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | Pavilion dv6                | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| System76      | Kudu Professional           | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Dell          | Latitude 5590               | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| MSI           | CX61 2PC                    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| Dell          | Latitude 7420               | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| HP            | ProBook 6470b               | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Toshiba       | Satellite C650D             | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Acer          | Swift SF314-43              | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6540              | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Timi          | Mi Laptop Air 12.5          | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| Dell          | Latitude E6320              | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Apple         | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| Unknown       | Unknown                     | [d88cb8b5ae](https://linux-hardware.org/?probe=d88cb8b5ae) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.15.0-52-generic       | 42        | 12.57%  |
| 5.15.0-56-generic       | 29        | 8.68%   |
| 5.15.0-48-generic       | 22        | 6.59%   |
| 5.15.0-53-generic       | 21        | 6.29%   |
| 5.15.0-47-generic       | 21        | 6.29%   |
| 5.15.0-46-generic       | 17        | 5.09%   |
| 5.15.0-43-generic       | 17        | 5.09%   |
| 5.15.0-41-generic       | 17        | 5.09%   |
| 5.15.0-40-generic       | 15        | 4.49%   |
| 5.15.0-25-generic       | 14        | 4.19%   |
| 5.15.0-50-generic       | 12        | 3.59%   |
| 5.15.0-27-generic       | 12        | 3.59%   |
| 5.15.0-33-generic       | 10        | 2.99%   |
| 5.15.0-39-generic       | 6         | 1.8%    |
| 5.15.0-37-generic       | 5         | 1.5%    |
| 5.15.0-43-lowlatency    | 4         | 1.2%    |
| 5.15.0-35-generic       | 4         | 1.2%    |
| 5.15.0-30-generic       | 4         | 1.2%    |
| 5.15.0-18-generic       | 4         | 1.2%    |
| 5.15.0-46-lowlatency    | 3         | 0.9%    |
| 6.0.7-060007-generic    | 2         | 0.6%    |
| 5.19.5-051905-generic   | 2         | 0.6%    |
| 5.17.0-1020-oem         | 2         | 0.6%    |
| 5.15.0-57-generic       | 2         | 0.6%    |
| 5.15.0-53-lowlatency    | 2         | 0.6%    |
| 5.15.0-52-lowlatency    | 2         | 0.6%    |
| 5.15.0-48-lowlatency    | 2         | 0.6%    |
| 5.15.0-32-generic       | 2         | 0.6%    |
| 5.15.0-30-lowlatency    | 2         | 0.6%    |
| 5.15.0-23-generic       | 2         | 0.6%    |
| 5.15.0-10033-tuxedo     | 2         | 0.6%    |
| 5.13.0-19-generic       | 2         | 0.6%    |
| 6.0.6-76060006-generic  | 1         | 0.3%    |
| 6.0.1-060001-generic    | 1         | 0.3%    |
| 6.0.0-t2                | 1         | 0.3%    |
| 6.0.0-1006-oem          | 1         | 0.3%    |
| 6.0.0-060000rc3-generic | 1         | 0.3%    |
| 5.19.2-051902-generic   | 1         | 0.3%    |
| 5.19.11-051911-generic  | 1         | 0.3%    |
| 5.18.6-051806-generic   | 1         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 289       | 90.88%  |
| 5.17.0  | 5         | 1.57%   |
| 6.0.0   | 3         | 0.94%   |
| 5.13.0  | 3         | 0.94%   |
| 6.0.7   | 2         | 0.63%   |
| 5.19.5  | 2         | 0.63%   |
| 6.0.6   | 1         | 0.31%   |
| 6.0.1   | 1         | 0.31%   |
| 5.19.2  | 1         | 0.31%   |
| 5.19.11 | 1         | 0.31%   |
| 5.18.6  | 1         | 0.31%   |
| 5.18.15 | 1         | 0.31%   |
| 5.18.10 | 1         | 0.31%   |
| 5.17.5  | 1         | 0.31%   |
| 5.17.4  | 1         | 0.31%   |
| 5.17.2  | 1         | 0.31%   |
| 5.16.2  | 1         | 0.31%   |
| 5.16.11 | 1         | 0.31%   |
| 5.15.65 | 1         | 0.31%   |
| 5.15.34 | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 290       | 91.48%  |
| 5.17    | 8         | 2.52%   |
| 6.0     | 7         | 2.21%   |
| 5.19    | 4         | 1.26%   |
| 5.18    | 3         | 0.95%   |
| 5.13    | 3         | 0.95%   |
| 5.16    | 2         | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 313       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 307       | 97.77%  |
| GNOME      | 2         | 0.64%   |
| X-Cinnamon | 1         | 0.32%   |
| MATE       | 1         | 0.32%   |
| KDE        | 1         | 0.32%   |
| i3         | 1         | 0.32%   |
| GNUstep    | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 295       | 93.95%  |
| Wayland | 16        | 5.1%    |
| Tty     | 3         | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 235       | 74.84%  |
| Unknown | 55        | 17.52%  |
| GDM3    | 15        | 4.78%   |
| LightDM | 7         | 2.23%   |
| SLiM    | 1         | 0.32%   |
| LXDM    | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 161       | 51.27%  |
| it_IT   | 22        | 7.01%   |
| de_DE   | 19        | 6.05%   |
| ru_RU   | 17        | 5.41%   |
| en_GB   | 12        | 3.82%   |
| fr_FR   | 11        | 3.5%    |
| pl_PL   | 9         | 2.87%   |
| es_ES   | 7         | 2.23%   |
| en_IN   | 7         | 2.23%   |
| pt_BR   | 5         | 1.59%   |
| hu_HU   | 5         | 1.59%   |
| en_AU   | 5         | 1.59%   |
| en_NZ   | 4         | 1.27%   |
| en_CA   | 4         | 1.27%   |
| en_PH   | 3         | 0.96%   |
| tr_TR   | 2         | 0.64%   |
| es_CL   | 2         | 0.64%   |
| en_SG   | 2         | 0.64%   |
| Default | 2         | 0.64%   |
| zh_TW   | 1         | 0.32%   |
| sl_SI   | 1         | 0.32%   |
| ru_UA   | 1         | 0.32%   |
| pt_PT   | 1         | 0.32%   |
| nl_BE   | 1         | 0.32%   |
| ko_KR   | 1         | 0.32%   |
| fr_CH   | 1         | 0.32%   |
| et_EE   | 1         | 0.32%   |
| es_MX   | 1         | 0.32%   |
| es_EC   | 1         | 0.32%   |
| es_CR   | 1         | 0.32%   |
| es_AR   | 1         | 0.32%   |
| en_ZA   | 1         | 0.32%   |
| en_DE   | 1         | 0.32%   |
| da_DK   | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 188       | 59.49%  |
| BIOS | 128       | 40.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 285       | 90.76%  |
| Overlay | 14        | 4.46%   |
| Btrfs   | 11        | 3.5%    |
| Xfs     | 3         | 0.96%   |
| Ext2    | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 207       | 65.71%  |
| Unknown | 91        | 28.89%  |
| MBR     | 17        | 5.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 292       | 93.29%  |
| Yes       | 21        | 6.71%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 192       | 61.15%  |
| Yes       | 122       | 38.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 74        | 23.64%  |
| Hewlett-Packard                | 56        | 17.89%  |
| Dell                           | 47        | 15.02%  |
| ASUSTek Computer               | 28        | 8.95%   |
| Acer                           | 23        | 7.35%   |
| MSI                            | 9         | 2.88%   |
| Apple                          | 8         | 2.56%   |
| HUAWEI                         | 7         | 2.24%   |
| Toshiba                        | 6         | 1.92%   |
| Samsung Electronics            | 6         | 1.92%   |
| TUXEDO                         | 4         | 1.28%   |
| Timi                           | 4         | 1.28%   |
| Google                         | 3         | 0.96%   |
| Gigabyte Technology            | 3         | 0.96%   |
| System76                       | 2         | 0.64%   |
| Sony                           | 2         | 0.64%   |
| Panasonic                      | 2         | 0.64%   |
| Notebook                       | 2         | 0.64%   |
| HONOR                          | 2         | 0.64%   |
| Haier                          | 2         | 0.64%   |
| GPU Company                    | 2         | 0.64%   |
| Unknown                        | 2         | 0.64%   |
| VALE                           | 1         | 0.32%   |
| Tactus                         | 1         | 0.32%   |
| Standard                       | 1         | 0.32%   |
| SLIMBOOK                       | 1         | 0.32%   |
| SK hynix                       | 1         | 0.32%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.32%   |
| SGIN                           | 1         | 0.32%   |
| Schenker                       | 1         | 0.32%   |
| Razer                          | 1         | 0.32%   |
| Monster                        | 1         | 0.32%   |
| LG Electronics                 | 1         | 0.32%   |
| Jumper                         | 1         | 0.32%   |
| Intel                          | 1         | 0.32%   |
| Fujitsu                        | 1         | 0.32%   |
| Framework                      | 1         | 0.32%   |
| Digma                          | 1         | 0.32%   |
| Chuwi                          | 1         | 0.32%   |
| Carbon Systems                 | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 6         | 1.92%   |
| HP Pavilion g6                     | 3         | 0.96%   |
| HP EliteBook 845 G7 Notebook PC    | 3         | 0.96%   |
| Dell XPS 15 9560                   | 3         | 0.96%   |
| Timi TM1701                        | 2         | 0.64%   |
| Lenovo IdeaPad 5 15ARE05 81YQ      | 2         | 0.64%   |
| HUAWEI CREM-WXX9                   | 2         | 0.64%   |
| HP ProBook 6470b                   | 2         | 0.64%   |
| HP ProBook 440 G8 Notebook PC      | 2         | 0.64%   |
| HP Pavilion Laptop 15-eh1xxx       | 2         | 0.64%   |
| HP Pavilion dv6                    | 2         | 0.64%   |
| HP OMEN Laptop 15-en0xxx           | 2         | 0.64%   |
| HP 255 G8 Notebook PC              | 2         | 0.64%   |
| Haier A1420EM                      | 2         | 0.64%   |
| Dell Latitude 3420                 | 2         | 0.64%   |
| Acer Nitro AN517-51                | 2         | 0.64%   |
| Acer Aspire E5-575G                | 2         | 0.64%   |
| VALE Notebook Slim S132            | 1         | 0.32%   |
| TUXEDO Stellaris AMD Gen3 (CZN)    | 1         | 0.32%   |
| TUXEDO Polaris 15 AMD Gen1         | 1         | 0.32%   |
| TUXEDO InfinityBook S 15 Gen6      | 1         | 0.32%   |
| TUXEDO InfinityBook Pro Gen7 (MK1) | 1         | 0.32%   |
| Toshiba TECRA S11                  | 1         | 0.32%   |
| Toshiba Satellite P70-B            | 1         | 0.32%   |
| Toshiba Satellite NB10t-A-102      | 1         | 0.32%   |
| Toshiba Satellite L850             | 1         | 0.32%   |
| Toshiba Satellite L655             | 1         | 0.32%   |
| Toshiba Satellite C650D            | 1         | 0.32%   |
| Timi TM1703                        | 1         | 0.32%   |
| Timi Mi Laptop Air 12.5            | 1         | 0.32%   |
| Tactus GeoBook 140                 | 1         | 0.32%   |
| System76 Lemur Ultra               | 1         | 0.32%   |
| System76 Kudu Professional         | 1         | 0.32%   |
| Sony VGN-NR11Z_T                   | 1         | 0.32%   |
| Sony SVE1512J6EW                   | 1         | 0.32%   |
| SLIMBOOK PROX15-AMD                | 1         | 0.32%   |
| SK hynix Onnyx III                 | 1         | 0.32%   |
| Shanghai Zhaoxin ZXE CRB           | 1         | 0.32%   |
| SGIN laptop                        | 1         | 0.32%   |
| Schenker XMG APEX (Mid 2021)       | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 31        | 9.9%    |
| Lenovo IdeaPad      | 19        | 6.07%   |
| Dell Latitude       | 15        | 4.79%   |
| HP Pavilion         | 13        | 4.15%   |
| Acer Aspire         | 12        | 3.83%   |
| HP ProBook          | 11        | 3.51%   |
| Dell Inspiron       | 11        | 3.51%   |
| Dell XPS            | 9         | 2.88%   |
| HP Laptop           | 8         | 2.56%   |
| HP EliteBook        | 7         | 2.24%   |
| Lenovo ThinkBook    | 6         | 1.92%   |
| ASUS VivoBook       | 6         | 1.92%   |
| Unknown             | 6         | 1.92%   |
| Toshiba Satellite   | 5         | 1.6%    |
| Lenovo Legion       | 5         | 1.6%    |
| Dell Vostro         | 5         | 1.6%    |
| Acer Nitro          | 5         | 1.6%    |
| HP OMEN             | 4         | 1.28%   |
| Dell Precision      | 4         | 1.28%   |
| ASUS ROG            | 4         | 1.28%   |
| Acer Predator       | 3         | 0.96%   |
| TUXEDO InfinityBook | 2         | 0.64%   |
| Timi TM1701         | 2         | 0.64%   |
| Lenovo Yoga         | 2         | 0.64%   |
| HUAWEI CREM-WXX9    | 2         | 0.64%   |
| HP 255              | 2         | 0.64%   |
| Haier A1420EM       | 2         | 0.64%   |
| ASUS ASUS           | 2         | 0.64%   |
| Apple MacBookPro11  | 2         | 0.64%   |
| Acer Swift          | 2         | 0.64%   |
| VALE Notebook       | 1         | 0.32%   |
| TUXEDO Stellaris    | 1         | 0.32%   |
| TUXEDO Polaris      | 1         | 0.32%   |
| Toshiba TECRA       | 1         | 0.32%   |
| Timi TM1703         | 1         | 0.32%   |
| Timi Mi             | 1         | 0.32%   |
| Tactus GeoBook      | 1         | 0.32%   |
| System76 Lemur      | 1         | 0.32%   |
| System76 Kudu       | 1         | 0.32%   |
| Sony VGN-NR11Z      | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 70        | 22.36%  |
| 2020 | 48        | 15.34%  |
| 2022 | 31        | 9.9%    |
| 2012 | 26        | 8.31%   |
| 2019 | 25        | 7.99%   |
| 2014 | 16        | 5.11%   |
| 2016 | 15        | 4.79%   |
| 2011 | 15        | 4.79%   |
| 2018 | 14        | 4.47%   |
| 2017 | 14        | 4.47%   |
| 2013 | 14        | 4.47%   |
| 2015 | 11        | 3.51%   |
| 2010 | 6         | 1.92%   |
| 2008 | 3         | 0.96%   |
| 2007 | 3         | 0.96%   |
| 2009 | 2         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 313       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 272       | 86.62%  |
| Enabled  | 42        | 13.38%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 309       | 98.72%  |
| Yes  | 4         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 94        | 29.75%  |
| 16.01-24.0  | 80        | 25.32%  |
| 8.01-16.0   | 61        | 19.3%   |
| 3.01-4.0    | 33        | 10.44%  |
| 32.01-64.0  | 29        | 9.18%   |
| 64.01-256.0 | 11        | 3.48%   |
| 24.01-32.0  | 5         | 1.58%   |
| 2.01-3.0    | 3         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 86        | 25.98%  |
| 3.01-4.0  | 79        | 23.87%  |
| 1.01-2.0  | 76        | 22.96%  |
| 4.01-8.0  | 70        | 21.15%  |
| 8.01-16.0 | 19        | 5.74%   |
| 0.51-1.0  | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 212       | 66.88%  |
| 2      | 91        | 28.71%  |
| 3      | 9         | 2.84%   |
| 4      | 5         | 1.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 255       | 81.21%  |
| Yes       | 59        | 18.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 227       | 72.52%  |
| No        | 86        | 27.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 312       | 99.68%  |
| No        | 1         | 0.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 270       | 85.44%  |
| No        | 46        | 14.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 54        | 17.25%  |
| Italy       | 33        | 10.54%  |
| Germany     | 26        | 8.31%   |
| Russia      | 24        | 7.67%   |
| France      | 17        | 5.43%   |
| Poland      | 13        | 4.15%   |
| Spain       | 10        | 3.19%   |
| UK          | 9         | 2.88%   |
| Hungary     | 8         | 2.56%   |
| Brazil      | 8         | 2.56%   |
| Indonesia   | 7         | 2.24%   |
| India       | 7         | 2.24%   |
| Switzerland | 6         | 1.92%   |
| Canada      | 5         | 1.6%    |
| Philippines | 4         | 1.28%   |
| New Zealand | 4         | 1.28%   |
| Mexico      | 4         | 1.28%   |
| Estonia     | 4         | 1.28%   |
| Australia   | 4         | 1.28%   |
| Turkey      | 3         | 0.96%   |
| Slovenia    | 3         | 0.96%   |
| Portugal    | 3         | 0.96%   |
| Netherlands | 3         | 0.96%   |
| Denmark     | 3         | 0.96%   |
| Bulgaria    | 3         | 0.96%   |
| Argentina   | 3         | 0.96%   |
| Ukraine     | 2         | 0.64%   |
| Taiwan      | 2         | 0.64%   |
| Sweden      | 2         | 0.64%   |
| South Korea | 2         | 0.64%   |
| Singapore   | 2         | 0.64%   |
| Serbia      | 2         | 0.64%   |
| Romania     | 2         | 0.64%   |
| Lithuania   | 2         | 0.64%   |
| Ireland     | 2         | 0.64%   |
| Greece      | 2         | 0.64%   |
| Ecuador     | 2         | 0.64%   |
| Czechia     | 2         | 0.64%   |
| China       | 2         | 0.64%   |
| Chile       | 2         | 0.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Milan                   | 9         | 2.82%   |
| Moscow                  | 8         | 2.51%   |
| Berlin                  | 5         | 1.57%   |
| Warsaw                  | 4         | 1.25%   |
| St Petersburg           | 4         | 1.25%   |
| Wroclaw                 | 3         | 0.94%   |
| Turin                   | 3         | 0.94%   |
| Tallinn                 | 3         | 0.94%   |
| Sofia                   | 3         | 0.94%   |
| Paris                   | 3         | 0.94%   |
| Budapest                | 3         | 0.94%   |
| Bengaluru               | 3         | 0.94%   |
| Auckland                | 3         | 0.94%   |
| Zurich                  | 2         | 0.63%   |
| Vladivostok             | 2         | 0.63%   |
| Vilnius                 | 2         | 0.63%   |
| Taipei                  | 2         | 0.63%   |
| Singapore               | 2         | 0.63%   |
| Sao Paulo               | 2         | 0.63%   |
| Samara                  | 2         | 0.63%   |
| Rome                    | 2         | 0.63%   |
| Quito                   | 2         | 0.63%   |
| Porto                   | 2         | 0.63%   |
| Parma                   | 2         | 0.63%   |
| Nuremberg               | 2         | 0.63%   |
| Murska Sobota           | 2         | 0.63%   |
| Minneapolis             | 2         | 0.63%   |
| Marseille               | 2         | 0.63%   |
| Madrid                  | 2         | 0.63%   |
| Katerini                | 2         | 0.63%   |
| Jakarta                 | 2         | 0.63%   |
| Jacksonville            | 2         | 0.63%   |
| Granozzo con Monticello | 2         | 0.63%   |
| Dublin                  | 2         | 0.63%   |
| Cologne                 | 2         | 0.63%   |
| Burgos                  | 2         | 0.63%   |
| Bucharest               | 2         | 0.63%   |
| Brooklyn                | 2         | 0.63%   |
| Bologna                 | 2         | 0.63%   |
| Zagreb                  | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 72        | 87     | 17.56%  |
| WDC                            | 44        | 52     | 10.73%  |
| Kingston                       | 29        | 31     | 7.07%   |
| Sandisk                        | 27        | 32     | 6.59%   |
| Toshiba                        | 26        | 33     | 6.34%   |
| SK hynix                       | 26        | 27     | 6.34%   |
| Seagate                        | 23        | 30     | 5.61%   |
| Unknown                        | 20        | 27     | 4.88%   |
| Intel                          | 15        | 17     | 3.66%   |
| Micron Technology              | 12        | 13     | 2.93%   |
| Crucial                        | 12        | 13     | 2.93%   |
| KIOXIA                         | 8         | 8      | 1.95%   |
| HGST                           | 8         | 8      | 1.95%   |
| Hitachi                        | 7         | 7      | 1.71%   |
| Apple                          | 6         | 7      | 1.46%   |
| China                          | 5         | 5      | 1.22%   |
| SSSTC                          | 4         | 4      | 0.98%   |
| Phison                         | 4         | 4      | 0.98%   |
| LITEON                         | 4         | 4      | 0.98%   |
| A-DATA Technology              | 4         | 4      | 0.98%   |
| Unknown                        | 4         | 4      | 0.98%   |
| Silicon Motion                 | 3         | 3      | 0.73%   |
| PNY                            | 3         | 3      | 0.73%   |
| Patriot                        | 3         | 3      | 0.73%   |
| Smart                          | 2         | 2      | 0.49%   |
| SABRENT                        | 2         | 4      | 0.49%   |
| Phison Electronics             | 2         | 2      | 0.49%   |
| Netac                          | 2         | 2      | 0.49%   |
| Micron/Crucial Technology      | 2         | 3      | 0.49%   |
| LITEONIT                       | 2         | 2      | 0.49%   |
| JMicron Technology             | 2         | 2      | 0.49%   |
| Emtec                          | 2         | 2      | 0.49%   |
| VISIPRO                        | 1         | 1      | 0.24%   |
| Verbatim                       | 1         | 1      | 0.24%   |
| USB3.0                         | 1         | 1      | 0.24%   |
| Union Memory                   | 1         | 1      | 0.24%   |
| UMIS                           | 1         | 1      | 0.24%   |
| Team                           | 1         | 1      | 0.24%   |
| SPCC                           | 1         | 1      | 0.24%   |
| Solid State Storage Technology | 1         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                          | 6         | 1.39%   |
| Samsung SSD 860 EVO 500GB                       | 6         | 1.39%   |
| Samsung SSD 980 PRO 1TB                         | 5         | 1.16%   |
| Kingston SA400S37480G 480GB SSD                 | 5         | 1.16%   |
| Toshiba MQ04ABF100 1TB                          | 4         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB                  | 4         | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 4         | 0.93%   |
| Samsung SSD 970 EVO Plus 500GB                  | 4         | 0.93%   |
| Kingston SA400S37240G 240GB SSD                 | 4         | 0.93%   |
| Unknown                                         | 4         | 0.93%   |
| Unknown MMC Card  128GB                         | 3         | 0.7%    |
| SK hynix NVMe SSD Drive 512GB                   | 3         | 0.7%    |
| SK hynix BC711 HFM512GD3JX013N 512GB            | 3         | 0.7%    |
| Samsung SSD 860 QVO 1TB                         | 3         | 0.7%    |
| Samsung SSD 850 EVO 250GB                       | 3         | 0.7%    |
| Samsung PM9A1 NVMe 512GB                        | 3         | 0.7%    |
| Samsung NVMe SSD Drive 512GB                    | 3         | 0.7%    |
| Micron 3400_MTFDKBA1T0TFH 1TB                   | 3         | 0.7%    |
| Kingston SA2000M81000G 1TB                      | 3         | 0.7%    |
| Crucial CT500MX500SSD1 500GB                    | 3         | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                | 2         | 0.46%   |
| WDC WD10SPZX-24Z10 1TB                          | 2         | 0.46%   |
| WDC PC SN730 SDBPNTY-512G                       | 2         | 0.46%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB            | 2         | 0.46%   |
| Unknown MMC64G  64GB                            | 2         | 0.46%   |
| Unknown MMC Card  7GB                           | 2         | 0.46%   |
| Unknown MMC Card  64GB                          | 2         | 0.46%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB          | 2         | 0.46%   |
| SK hynix PC801 NVMe 1TB                         | 2         | 0.46%   |
| SK hynix HFS256G39TND-N210A 256GB SSD           | 2         | 0.46%   |
| Seagate ST9750420AS 752GB                       | 2         | 0.46%   |
| Seagate ST500LM021-1KJ152 500GB                 | 2         | 0.46%   |
| Seagate ST2000LM007-1R8174 2TB                  | 2         | 0.46%   |
| Sandisk WD Blue SN550 NVMe SSD 500GB            | 2         | 0.46%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB | 2         | 0.46%   |
| SanDisk NVMe SSD Drive 1TB                      | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 2TB                    | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 250GB                  | 2         | 0.46%   |
| Samsung SSD 850 EVO 500GB                       | 2         | 0.46%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB          | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 22        | 29     | 30.14%  |
| WDC      | 18        | 18     | 24.66%  |
| Toshiba  | 14        | 17     | 19.18%  |
| HGST     | 8         | 8      | 10.96%  |
| Hitachi  | 7         | 7      | 9.59%   |
| USB3.0   | 1         | 1      | 1.37%   |
| Unknown  | 1         | 1      | 1.37%   |
| KESU     | 1         | 1      | 1.37%   |
| HGST HTS | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 38     | 23.31%  |
| Kingston            | 20        | 22     | 15.04%  |
| SanDisk             | 16        | 19     | 12.03%  |
| Crucial             | 8         | 9      | 6.02%   |
| WDC                 | 7         | 11     | 5.26%   |
| LITEON              | 4         | 4      | 3.01%   |
| Intel               | 4         | 4      | 3.01%   |
| China               | 4         | 4      | 3.01%   |
| Patriot             | 3         | 3      | 2.26%   |
| Apple               | 3         | 3      | 2.26%   |
| A-DATA Technology   | 3         | 3      | 2.26%   |
| Toshiba             | 2         | 5      | 1.5%    |
| Smart               | 2         | 2      | 1.5%    |
| SK hynix            | 2         | 2      | 1.5%    |
| Netac               | 2         | 2      | 1.5%    |
| LITEONIT            | 2         | 2      | 1.5%    |
| Emtec               | 2         | 2      | 1.5%    |
| Unknown             | 2         | 2      | 1.5%    |
| VISIPRO             | 1         | 1      | 0.75%   |
| Verbatim            | 1         | 1      | 0.75%   |
| Team                | 1         | 1      | 0.75%   |
| SPCC                | 1         | 1      | 0.75%   |
| Ramos Technology    | 1         | 1      | 0.75%   |
| R580                | 1         | 1      | 0.75%   |
| PNY                 | 1         | 1      | 0.75%   |
| NGFF                | 1         | 1      | 0.75%   |
| Micron Technology   | 1         | 1      | 0.75%   |
| KingSpec            | 1         | 1      | 0.75%   |
| JMicron Technology  | 1         | 1      | 0.75%   |
| HS-SSD-C100         | 1         | 1      | 0.75%   |
| GOODRAM             | 1         | 1      | 0.75%   |
| Dogfish             | 1         | 1      | 0.75%   |
| Corsair             | 1         | 1      | 0.75%   |
| BAITITON            | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 163       | 201    | 43.24%  |
| SSD     | 118       | 153    | 31.3%   |
| HDD     | 69        | 83     | 18.3%   |
| MMC     | 22        | 28     | 5.84%   |
| Unknown | 5         | 6      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 161       | 196    | 45.1%   |
| SATA | 157       | 218    | 43.98%  |
| MMC  | 22        | 28     | 6.16%   |
| SAS  | 17        | 29     | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 117       | 147    | 62.23%  |
| 0.51-1.0   | 60        | 72     | 31.91%  |
| 1.01-2.0   | 7         | 9      | 3.72%   |
| 3.01-4.0   | 3         | 7      | 1.6%    |
| 4.01-10.0  | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 91        | 28.71%  |
| 101-250        | 76        | 23.97%  |
| 501-1000       | 60        | 18.93%  |
| 1001-2000      | 40        | 12.62%  |
| 51-100         | 25        | 7.89%   |
| 1-20           | 12        | 3.79%   |
| 21-50          | 5         | 1.58%   |
| More than 3000 | 4         | 1.26%   |
| 2001-3000      | 4         | 1.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 84        | 26.5%   |
| 21-50          | 58        | 18.3%   |
| 101-250        | 58        | 18.3%   |
| 251-500        | 45        | 14.2%   |
| 51-100         | 38        | 11.99%  |
| 501-1000       | 24        | 7.57%   |
| 1001-2000      | 8         | 2.52%   |
| More than 3000 | 2         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| SK hynix BC711 HFM512GD3JX013N 512GB                | 2         | 2      | 8.33%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 4.17%   |
| VISIPRO SSD 256GB                                   | 1         | 1      | 4.17%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 4.17%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 1         | 1      | 4.17%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 4.17%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 4.17%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 4.17%   |
| SanDisk SSD U100 128GB                              | 1         | 1      | 4.17%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 4.17%   |
| R580 SSD 60GB                                       | 1         | 1      | 4.17%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 4.17%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 4.17%   |
| Hitachi HTS725050A7E630 500GB                       | 1         | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 4.17%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 4.17%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 4.17%   |
| Crucial CT128M550SSD1 128GB                         | 1         | 1      | 4.17%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 4.17%   |
| BAITITON BT58SSD09S 240GB                           | 1         | 1      | 4.17%   |
| A-DATA Technology XM11 256GB-V2 SSD                 | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| SK hynix          | 3         | 3      | 12.5%   |
| Seagate           | 3         | 3      | 12.5%   |
| Hitachi           | 3         | 3      | 12.5%   |
| Toshiba           | 2         | 2      | 8.33%   |
| SanDisk           | 2         | 2      | 8.33%   |
| HGST              | 2         | 2      | 8.33%   |
| Crucial           | 2         | 2      | 8.33%   |
| WDC               | 1         | 1      | 4.17%   |
| VISIPRO           | 1         | 1      | 4.17%   |
| R580              | 1         | 1      | 4.17%   |
| Micron Technology | 1         | 1      | 4.17%   |
| Kingston          | 1         | 1      | 4.17%   |
| BAITITON          | 1         | 1      | 4.17%   |
| A-DATA Technology | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| Hitachi | 3         | 3      | 30%     |
| Toshiba | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 43.48%  |
| SSD  | 9         | 10     | 39.13%  |
| NVMe | 4         | 4      | 17.39%  |

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
| Works    | 187       | 245    | 54.68%  |
| Detected | 132       | 202    | 38.6%   |
| Malfunc  | 23        | 24     | 6.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 190       | 46.68%  |
| AMD                            | 45        | 11.06%  |
| Samsung Electronics            | 42        | 10.32%  |
| SanDisk                        | 33        | 8.11%   |
| SK hynix                       | 24        | 5.9%    |
| Toshiba America Info Systems   | 13        | 3.19%   |
| Micron Technology              | 11        | 2.7%    |
| Phison Electronics             | 9         | 2.21%   |
| Kingston Technology Company    | 9         | 2.21%   |
| Solid State Storage Technology | 6         | 1.47%   |
| Micron/Crucial Technology      | 6         | 1.47%   |
| KIOXIA                         | 5         | 1.23%   |
| Silicon Motion                 | 3         | 0.74%   |
| Apple                          | 3         | 0.74%   |
| Union Memory (Shenzhen)        | 2         | 0.49%   |
| Zhaoxin                        | 1         | 0.25%   |
| Shenzhen Longsys Electronics   | 1         | 0.25%   |
| Realtek Semiconductor          | 1         | 0.25%   |
| Nvidia                         | 1         | 0.25%   |
| Marvell Technology Group       | 1         | 0.25%   |
| ADATA Technology               | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 42        | 9.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 31        | 7.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 25        | 5.77%   |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 4.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 3.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 3.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 13        | 3%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 3%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 2.54%   |
| Micron Non-Volatile memory controller                                          | 11        | 2.54%   |
| Samsung NVMe SSD Controller 980                                                | 10        | 2.31%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 2.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 2.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 2.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 2.08%   |
| SanDisk Non-Volatile memory controller                                         | 8         | 1.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 8         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 1.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 1.62%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.62%   |
| Solid State Storage Non-Volatile memory controller                             | 6         | 1.39%   |
| SK hynix Non-Volatile memory controller                                        | 6         | 1.39%   |
| Intel SSD 660P Series                                                          | 6         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.39%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 0.92%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 0.92%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.92%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 3         | 0.69%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.69%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.69%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.69%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 207       | 50.24%  |
| NVMe | 161       | 39.08%  |
| RAID | 36        | 8.74%   |
| IDE  | 8         | 1.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 239       | 76.36%  |
| AMD          | 73        | 23.32%  |
| CentaurHauls | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 3.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 3.19%   |
| Intel 12th Gen Core i7-12700H                 | 10        | 3.19%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 3.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 2.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 2.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 7         | 2.24%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 2.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 1.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.28%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 1.28%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 1.28%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 1.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.96%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.96%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 3         | 0.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.96%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.96%   |
| Intel 12th Gen Core i7-1255U                  | 3         | 0.96%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz       | 3         | 0.96%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.96%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.96%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.96%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.64%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 2         | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.64%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 2         | 0.64%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.64%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.64%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.64%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 75        | 23.96%  |
| Intel Core i5           | 65        | 20.77%  |
| Other                   | 58        | 18.53%  |
| AMD Ryzen 7             | 28        | 8.95%   |
| AMD Ryzen 5             | 20        | 6.39%   |
| Intel Celeron           | 16        | 5.11%   |
| Intel Core i3           | 9         | 2.88%   |
| AMD Ryzen 9             | 6         | 1.92%   |
| Intel Core 2 Duo        | 5         | 1.6%    |
| Intel Pentium           | 4         | 1.28%   |
| AMD Ryzen 3             | 4         | 1.28%   |
| Intel Pentium Silver    | 3         | 0.96%   |
| AMD A8                  | 3         | 0.96%   |
| Intel Core i9           | 2         | 0.64%   |
| AMD Ryzen 7 PRO         | 2         | 0.64%   |
| AMD Ryzen 5 PRO         | 2         | 0.64%   |
| AMD E                   | 2         | 0.64%   |
| AMD A6                  | 2         | 0.64%   |
| Intel Core m3           | 1         | 0.32%   |
| Intel Core 2            | 1         | 0.32%   |
| Intel Celeron Dual-Core | 1         | 0.32%   |
| AMD PRO A10             | 1         | 0.32%   |
| AMD FX                  | 1         | 0.32%   |
| AMD A4                  | 1         | 0.32%   |
| AMD A10                 | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 112       | 35.78%  |
| 2      | 103       | 32.91%  |
| 8      | 41        | 13.1%   |
| 6      | 38        | 12.14%  |
| 14     | 12        | 3.83%   |
| 12     | 3         | 0.96%   |
| 10     | 3         | 0.96%   |
| 5      | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 313       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 268       | 85.35%  |
| 1      | 46        | 14.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 313       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 34.91%  |
| 0x306a9    | 19        | 5.97%   |
| 0x806c1    | 18        | 5.66%   |
| 0x0a50000c | 14        | 4.4%    |
| 0x906a3    | 13        | 4.09%   |
| 0x806ea    | 11        | 3.46%   |
| 0x08600106 | 10        | 3.14%   |
| 0x906ea    | 9         | 2.83%   |
| 0x08608103 | 9         | 2.83%   |
| 0x806ec    | 7         | 2.2%    |
| 0x406e3    | 7         | 2.2%    |
| 0x306c3    | 7         | 2.2%    |
| 0x206a7    | 7         | 2.2%    |
| 0x806e9    | 6         | 1.89%   |
| 0xa0652    | 5         | 1.57%   |
| 0x806d1    | 5         | 1.57%   |
| 0x706a8    | 5         | 1.57%   |
| 0x40651    | 5         | 1.57%   |
| 0x906e9    | 4         | 1.26%   |
| 0x08608102 | 4         | 1.26%   |
| 0x08108109 | 4         | 1.26%   |
| 0x906a4    | 3         | 0.94%   |
| 0x806c2    | 3         | 0.94%   |
| 0x506c9    | 3         | 0.94%   |
| 0x20652    | 3         | 0.94%   |
| 0x706a1    | 2         | 0.63%   |
| 0x40661    | 2         | 0.63%   |
| 0x08600103 | 2         | 0.63%   |
| 0x03000027 | 2         | 0.63%   |
| 0x806eb    | 1         | 0.31%   |
| 0x806a1    | 1         | 0.31%   |
| 0x706e5    | 1         | 0.31%   |
| 0x6fd      | 1         | 0.31%   |
| 0x6fb      | 1         | 0.31%   |
| 0x6f6      | 1         | 0.31%   |
| 0x506e3    | 1         | 0.31%   |
| 0x306d4    | 1         | 0.31%   |
| 0x30673    | 1         | 0.31%   |
| 0x1067a    | 1         | 0.31%   |
| 0x0a50000d | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 59        | 18.79%  |
| TigerLake        | 31        | 9.87%   |
| IvyBridge        | 31        | 9.87%   |
| Unknown          | 25        | 7.96%   |
| Zen 3            | 24        | 7.64%   |
| Haswell          | 22        | 7.01%   |
| Alderlake Hybrid | 15        | 4.78%   |
| Zen 2            | 14        | 4.46%   |
| Skylake          | 14        | 4.46%   |
| Goldmont plus    | 13        | 4.14%   |
| SandyBridge      | 12        | 3.82%   |
| Zen+             | 7         | 2.23%   |
| CometLake        | 7         | 2.23%   |
| Icelake          | 6         | 1.91%   |
| Westmere         | 5         | 1.59%   |
| Goldmont         | 4         | 1.27%   |
| Core             | 4         | 1.27%   |
| Penryn           | 3         | 0.96%   |
| Broadwell        | 3         | 0.96%   |
| Silvermont       | 2         | 0.64%   |
| Puma             | 2         | 0.64%   |
| Piledriver       | 2         | 0.64%   |
| K10 Llano        | 2         | 0.64%   |
| Excavator        | 2         | 0.64%   |
| Bobcat           | 2         | 0.64%   |
| Zen              | 1         | 0.32%   |
| Steamroller      | 1         | 0.32%   |
| Nehalem          | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 224       | 52.34%  |
| Nvidia  | 109       | 25.47%  |
| AMD     | 94        | 21.96%  |
| Zhaoxin | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 29        | 6.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 26        | 5.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 19        | 4.33%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 14        | 3.19%   |
| AMD Renoir                                                                            | 14        | 3.19%   |
| AMD Lucienne                                                                          | 14        | 3.19%   |
| Intel UHD Graphics 620                                                                | 13        | 2.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 13        | 2.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 13        | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 11        | 2.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 11        | 2.51%   |
| Intel HD Graphics 620                                                                 | 10        | 2.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 10        | 2.28%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 9         | 2.05%   |
| Intel HD Graphics 630                                                                 | 8         | 1.82%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 7         | 1.59%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 7         | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 7         | 1.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 1.59%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 7         | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 7         | 1.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 6         | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 1.37%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 5         | 1.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 4         | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 0.91%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 4         | 0.91%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 4         | 0.91%   |
| Intel HD Graphics 500                                                                 | 4         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                         | 3         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 3         | 0.68%   |
| Nvidia GM108M [GeForce MX130]                                                         | 3         | 0.68%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 3         | 0.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 0.68%   |
| Intel HD Graphics 5500                                                                | 3         | 0.68%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 3         | 0.68%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 3         | 0.68%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 3         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 126       | 40.26%  |
| Intel + Nvidia | 77        | 24.6%   |
| 1 x AMD        | 49        | 15.65%  |
| Intel + AMD    | 20        | 6.39%   |
| AMD + Nvidia   | 18        | 5.75%   |
| 1 x Nvidia     | 13        | 4.15%   |
| 2 x AMD        | 7         | 2.24%   |
| Other          | 1         | 0.32%   |
| 2 x Nvidia     | 1         | 0.32%   |
| 1 x Zhaoxin    | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 233       | 74.44%  |
| Proprietary | 74        | 23.64%  |
| Unknown     | 6         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 224       | 70.89%  |
| 0.01-0.5   | 36        | 11.39%  |
| 1.01-2.0   | 25        | 7.91%   |
| 3.01-4.0   | 10        | 3.16%   |
| 0.51-1.0   | 10        | 3.16%   |
| 5.01-6.0   | 5         | 1.58%   |
| 7.01-8.0   | 4         | 1.27%   |
| 8.01-16.0  | 2         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 60        | 16.26%  |
| BOE                     | 59        | 15.99%  |
| Chimei Innolux          | 58        | 15.72%  |
| LG Display              | 48        | 13.01%  |
| Samsung Electronics     | 33        | 8.94%   |
| Sharp                   | 15        | 4.07%   |
| Goldstar                | 12        | 3.25%   |
| Dell                    | 9         | 2.44%   |
| Hewlett-Packard         | 8         | 2.17%   |
| Apple                   | 8         | 2.17%   |
| Chi Mei Optoelectronics | 7         | 1.9%    |
| CSO                     | 6         | 1.63%   |
| BenQ                    | 6         | 1.63%   |
| Lenovo                  | 5         | 1.36%   |
| Acer                    | 5         | 1.36%   |
| Philips                 | 4         | 1.08%   |
| InfoVision              | 4         | 1.08%   |
| SLD                     | 2         | 0.54%   |
| Sceptre Tech            | 2         | 0.54%   |
| PANDA                   | 2         | 0.54%   |
| IBM                     | 2         | 0.54%   |
| HKC                     | 2         | 0.54%   |
| ASUSTek Computer        | 2         | 0.54%   |
| Vizio                   | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| MSI                     | 1         | 0.27%   |
| HUAWEI                  | 1         | 0.27%   |
| Gigabyte Technology     | 1         | 0.27%   |
| CVT                     | 1         | 0.27%   |
| CPT                     | 1         | 0.27%   |
| Belinea                 | 1         | 0.27%   |
| AOC                     | 1         | 0.27%   |
| Ancor Communications    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 6         | 1.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 5         | 1.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 4         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 4         | 1.06%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 3         | 0.8%    |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch              | 3         | 0.8%    |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch          | 3         | 0.8%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 3         | 0.8%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.8%    |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                      | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 2         | 0.53%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                   | 2         | 0.53%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 2         | 0.53%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.53%   |
| BOE LCD Monitor BOE0931 2240x1400 302x189mm 14.0-inch                     | 2         | 0.53%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                     | 2         | 0.53%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                     | 2         | 0.53%   |
| BOE LCD Monitor BOE069B 1600x900 382x215mm 17.3-inch                      | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch            | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 175       | 51.47%  |
| 1366x768 (WXGA)    | 72        | 21.18%  |
| 2560x1440 (QHD)    | 18        | 5.29%   |
| 3840x2160 (4K)     | 12        | 3.53%   |
| 1600x900 (HD+)     | 11        | 3.24%   |
| 2560x1600          | 10        | 2.94%   |
| 1920x1200 (WUXGA)  | 9         | 2.65%   |
| 2880x1800          | 8         | 2.35%   |
| 2560x1080          | 4         | 1.18%   |
| 1680x1050 (WSXGA+) | 3         | 0.88%   |
| 3440x1440          | 2         | 0.59%   |
| 2520x1680          | 2         | 0.59%   |
| 2240x1400          | 2         | 0.59%   |
| 1280x800 (WXGA)    | 2         | 0.59%   |
| 1024x768 (XGA)     | 2         | 0.59%   |
| 3840x1080          | 1         | 0.29%   |
| 3072x1920          | 1         | 0.29%   |
| 2256x1504          | 1         | 0.29%   |
| 2160x1440          | 1         | 0.29%   |
| 2160x1350          | 1         | 0.29%   |
| 1920x540           | 1         | 0.29%   |
| 1440x900 (WXGA+)   | 1         | 0.29%   |
| 1280x1024 (SXGA)   | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 159       | 42.86%  |
| 14     | 44        | 11.86%  |
| 13     | 39        | 10.51%  |
| 17     | 29        | 7.82%   |
| 16     | 16        | 4.31%   |
| 24     | 15        | 4.04%   |
| 27     | 12        | 3.23%   |
| 23     | 10        | 2.7%    |
| 21     | 10        | 2.7%    |
| 12     | 7         | 1.89%   |
| 11     | 6         | 1.62%   |
| 34     | 5         | 1.35%   |
| 31     | 3         | 0.81%   |
| 54     | 2         | 0.54%   |
| 25     | 2         | 0.54%   |
| 22     | 2         | 0.54%   |
| 84     | 1         | 0.27%   |
| 78     | 1         | 0.27%   |
| 65     | 1         | 0.27%   |
| 60     | 1         | 0.27%   |
| 49     | 1         | 0.27%   |
| 42     | 1         | 0.27%   |
| 32     | 1         | 0.27%   |
| 28     | 1         | 0.27%   |
| 26     | 1         | 0.27%   |
| 18     | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 229       | 62.74%  |
| 351-400     | 37        | 10.14%  |
| 501-600     | 36        | 9.86%   |
| 201-300     | 33        | 9.04%   |
| 401-500     | 13        | 3.56%   |
| 701-800     | 5         | 1.37%   |
| 1001-1500   | 5         | 1.37%   |
| 601-700     | 4         | 1.1%    |
| 1501-2000   | 2         | 0.55%   |
| 901-1000    | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 264       | 83.28%  |
| 16/10 | 39        | 12.3%   |
| 21/9  | 6         | 1.89%   |
| 3/2   | 4         | 1.26%   |
| 4/3   | 2         | 0.63%   |
| 5/4   | 1         | 0.32%   |
| 32/9  | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 163       | 44.54%  |
| 81-90          | 67        | 18.31%  |
| 201-250        | 27        | 7.38%   |
| 121-130        | 27        | 7.38%   |
| 71-80          | 17        | 4.64%   |
| 301-350        | 13        | 3.55%   |
| 111-120        | 11        | 3.01%   |
| 351-500        | 8         | 2.19%   |
| More than 1000 | 6         | 1.64%   |
| 61-70          | 6         | 1.64%   |
| 51-60          | 6         | 1.64%   |
| 251-300        | 6         | 1.64%   |
| 151-200        | 3         | 0.82%   |
| 141-150        | 2         | 0.55%   |
| 501-1000       | 2         | 0.55%   |
| 131-140        | 1         | 0.27%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 175       | 48.75%  |
| 101-120       | 81        | 22.56%  |
| 51-100        | 47        | 13.09%  |
| 161-240       | 39        | 10.86%  |
| More than 240 | 12        | 3.34%   |
| 1-50          | 5         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 246       | 77.36%  |
| 2     | 54        | 16.98%  |
| 3     | 8         | 2.52%   |
| 0     | 7         | 2.2%    |
| 4     | 3         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 185       | 37%     |
| Intel                             | 169       | 33.8%   |
| Qualcomm Atheros                  | 52        | 10.4%   |
| Broadcom                          | 27        | 5.4%    |
| MediaTek                          | 23        | 4.6%    |
| ASIX Electronics                  | 6         | 1.2%    |
| TP-Link                           | 4         | 0.8%    |
| Sierra Wireless                   | 4         | 0.8%    |
| Samsung Electronics               | 4         | 0.8%    |
| Ralink Technology                 | 3         | 0.6%    |
| Broadcom Limited                  | 3         | 0.6%    |
| Marvell Technology Group          | 2         | 0.4%    |
| Huawei Technologies               | 2         | 0.4%    |
| Google                            | 2         | 0.4%    |
| DisplayLink                       | 2         | 0.4%    |
| Apple                             | 2         | 0.4%    |
| Xiaomi                            | 1         | 0.2%    |
| Qualcomm                          | 1         | 0.2%    |
| Nvidia                            | 1         | 0.2%    |
| Motorola PCS                      | 1         | 0.2%    |
| Lenovo                            | 1         | 0.2%    |
| Hewlett-Packard                   | 1         | 0.2%    |
| Ericsson Business Mobile Networks | 1         | 0.2%    |
| Dell                              | 1         | 0.2%    |
| D-Link System                     | 1         | 0.2%    |
| Belkin Components                 | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 108       | 18.62%  |
| Intel Wi-Fi 6 AX201                                               | 23        | 3.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 3.45%   |
| Intel Wi-Fi 6 AX200                                               | 20        | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 3.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 2.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 2.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 15        | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 2.24%   |
| Intel Wireless 7260                                               | 13        | 2.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.55%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 1.55%   |
| Realtek 802.11n WLAN Adapter                                      | 8         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.38%   |
| Intel Wireless 7265                                               | 7         | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 1.03%   |
| Intel Wireless 8260                                               | 6         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.86%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.69%   |
| Intel Wireless 3165                                               | 4         | 0.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.52%   |
| Realtek 802.11ac NIC                                              | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 161       | 49.24%  |
| Realtek Semiconductor | 64        | 19.57%  |
| Qualcomm Atheros      | 40        | 12.23%  |
| MediaTek              | 23        | 7.03%   |
| Broadcom              | 23        | 7.03%   |
| Sierra Wireless       | 4         | 1.22%   |
| Ralink Technology     | 3         | 0.92%   |
| Broadcom Limited      | 3         | 0.92%   |
| TP-Link               | 2         | 0.61%   |
| Qualcomm              | 1         | 0.31%   |
| Dell                  | 1         | 0.31%   |
| D-Link System         | 1         | 0.31%   |
| Belkin Components     | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 23        | 6.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 6.08%   |
| Intel Wi-Fi 6 AX200                                            | 20        | 6.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 5.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 4.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 3.95%   |
| Intel Wireless 7260                                            | 13        | 3.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 3.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 3.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 3.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 2.74%   |
| Intel Wireless 8265 / 8275                                     | 9         | 2.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 2.74%   |
| Realtek 802.11n WLAN Adapter                                   | 8         | 2.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 2.43%   |
| Intel Wireless 7265                                            | 7         | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 2.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 1.82%   |
| Intel Wireless 8260                                            | 6         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 1.52%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.22%   |
| Intel Wireless 3165                                            | 4         | 1.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.91%   |
| Realtek 802.11ac NIC                                           | 3         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.91%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.91%   |
| Sierra Wireless EM7305 Modem                                   | 2         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.61%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 150       | 61.98%  |
| Intel                    | 48        | 19.83%  |
| Qualcomm Atheros         | 13        | 5.37%   |
| Broadcom                 | 6         | 2.48%   |
| ASIX Electronics         | 6         | 2.48%   |
| Samsung Electronics      | 4         | 1.65%   |
| TP-Link                  | 2         | 0.83%   |
| Marvell Technology Group | 2         | 0.83%   |
| Huawei Technologies      | 2         | 0.83%   |
| Google                   | 2         | 0.83%   |
| DisplayLink              | 2         | 0.83%   |
| Apple                    | 2         | 0.83%   |
| Xiaomi                   | 1         | 0.41%   |
| Nvidia                   | 1         | 0.41%   |
| Lenovo                   | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 108       | 43.55%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 6.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 6.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 6.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.02%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.61%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 1.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.21%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.21%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.21%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.81%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.81%   |
| DisplayLink USB3.0 Dual Video Dock                                | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.4%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.4%    |
| Realtek Realtek Ethernet controller                               | 1         | 0.4%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.4%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.4%    |
| Lenovo Android                                                    | 1         | 0.4%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.4%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 312       | 57.56%  |
| Ethernet | 227       | 41.88%  |
| Modem    | 2         | 0.37%   |
| Unknown  | 1         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 269       | 80.3%   |
| Ethernet | 66        | 19.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 203       | 64.86%  |
| 1     | 99        | 31.63%  |
| 0     | 10        | 3.19%   |
| 3     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 239       | 76.11%  |
| Yes  | 75        | 23.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 48.35%  |
| Realtek Semiconductor           | 36        | 13.19%  |
| Qualcomm Atheros Communications | 22        | 8.06%   |
| IMC Networks                    | 15        | 5.49%   |
| Broadcom                        | 15        | 5.49%   |
| Lite-On Technology              | 14        | 5.13%   |
| Foxconn / Hon Hai               | 13        | 4.76%   |
| Apple                           | 5         | 1.83%   |
| Toshiba                         | 4         | 1.47%   |
| Realtek                         | 4         | 1.47%   |
| Dell                            | 3         | 1.1%    |
| Cambridge Silicon Radio         | 3         | 1.1%    |
| Hewlett-Packard                 | 2         | 0.73%   |
| TP-Link                         | 1         | 0.37%   |
| Foxconn International           | 1         | 0.37%   |
| Edimax Technology               | 1         | 0.37%   |
| ASUSTek Computer                | 1         | 0.37%   |
| Alps Electric                   | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 35        | 12.82%  |
| Intel AX201 Bluetooth                               | 35        | 12.82%  |
| Realtek Bluetooth Radio                             | 29        | 10.62%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 6.96%   |
| Intel AX200 Bluetooth                               | 19        | 6.96%   |
| Intel Bluetooth Device                              | 12        | 4.4%    |
| IMC Networks Wireless_Device                        | 8         | 2.93%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 2.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 2.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 2.56%   |
| Lite-On Wireless_Device                             | 7         | 2.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.2%    |
| Intel AX210 Bluetooth                               | 6         | 2.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 1.83%   |
| Realtek Bluetooth Radio                             | 4         | 1.47%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.47%   |
| Apple Bluetooth Host Controller                     | 4         | 1.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.1%    |
| IMC Networks Bluetooth Radio                        | 3         | 1.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.1%    |
| Broadcom HP Portable SoftSailing                    | 3         | 1.1%    |
| Dell DW375 Bluetooth Module                         | 2         | 0.73%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.73%   |
| TP-Link UB500 Adapter                               | 1         | 0.37%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.37%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.37%   |
| Toshiba Bluetooth Device                            | 1         | 0.37%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.37%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.37%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.37%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.37%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.37%   |
| Lite-On Bluetooth Device                            | 1         | 0.37%   |
| Lite-On BCM43142A0                                  | 1         | 0.37%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.37%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.37%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 237       | 58.52%  |
| AMD                   | 77        | 19.01%  |
| Nvidia                | 62        | 15.31%  |
| C-Media Electronics   | 4         | 0.99%   |
| Realtek Semiconductor | 2         | 0.49%   |
| Razer USA             | 2         | 0.49%   |
| JMTek                 | 2         | 0.49%   |
| Apple                 | 2         | 0.49%   |
| ZOOM                  | 1         | 0.25%   |
| Zhaoxin               | 1         | 0.25%   |
| TerraTec Electronic   | 1         | 0.25%   |
| Sony                  | 1         | 0.25%   |
| Silicon Motion        | 1         | 0.25%   |
| Plantronics           | 1         | 0.25%   |
| Logitech              | 1         | 0.25%   |
| Lenovo                | 1         | 0.25%   |
| Hewlett-Packard       | 1         | 0.25%   |
| GN Netcom             | 1         | 0.25%   |
| Focusrite-Novation    | 1         | 0.25%   |
| DisplayLink           | 1         | 0.25%   |
| Cyber Acoustics       | 1         | 0.25%   |
| Creative Technology   | 1         | 0.25%   |
| Corsair               | 1         | 0.25%   |
| Blue Microphones      | 1         | 0.25%   |
| Arturia               | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 60        | 12.2%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 41        | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 36        | 7.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35        | 7.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 31        | 6.3%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 19        | 3.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 3.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 2.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 1.63%   |
| Intel CM238 HD Audio Controller                                            | 8         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 1.63%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.42%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.42%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.42%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.42%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.81%   |
| Nvidia Audio device                                                        | 4         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.61%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.61%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 0.61%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.41%   |
| Razer USA Kraken Tournament Edition                                        | 2         | 0.41%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 87        | 32.34%  |
| SK hynix            | 56        | 20.82%  |
| Micron Technology   | 31        | 11.52%  |
| Crucial             | 20        | 7.43%   |
| Kingston            | 19        | 7.06%   |
| Unknown (ABCD)      | 9         | 3.35%   |
| A-DATA Technology   | 7         | 2.6%    |
| Elpida              | 5         | 1.86%   |
| Unknown             | 4         | 1.49%   |
| Unknown             | 4         | 1.49%   |
| Wilk                | 2         | 0.74%   |
| Ramaxel Technology  | 2         | 0.74%   |
| Nanya Technology    | 2         | 0.74%   |
| GOODRAM             | 2         | 0.74%   |
| Unknown (8A02)      | 1         | 0.37%   |
| Transcend           | 1         | 0.37%   |
| Teikon              | 1         | 0.37%   |
| Team                | 1         | 0.37%   |
| Super Talent        | 1         | 0.37%   |
| Smart               | 1         | 0.37%   |
| Silicon Power       | 1         | 0.37%   |
| Shenzhen Zhongteng  | 1         | 0.37%   |
| Shenzhen WODPOSIT   | 1         | 0.37%   |
| SHARETRONIC         | 1         | 0.37%   |
| Qimonda             | 1         | 0.37%   |
| Patriot             | 1         | 0.37%   |
| Imation             | 1         | 0.37%   |
| Goldkey             | 1         | 0.37%   |
| G.Skill             | 1         | 0.37%   |
| Essencore Limited   | 1         | 0.37%   |
| Corsair             | 1         | 0.37%   |
| Atermiter           | 1         | 0.37%   |
| AMD                 | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 2.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.42%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.42%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 1.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 1.42%   |
| Unknown                                                          | 4         | 1.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.07%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.07%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.07%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.07%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.07%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 1.07%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.07%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.71%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 2         | 0.71%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.71%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.71%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.71%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.71%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.71%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.71%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.71%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 132       | 59.19%  |
| DDR3   | 56        | 25.11%  |
| LPDDR4 | 20        | 8.97%   |
| DDR5   | 6         | 2.69%   |
| LPDDR5 | 3         | 1.35%   |
| DDR2   | 3         | 1.35%   |
| LPDDR3 | 2         | 0.9%    |
| SDRAM  | 1         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 195       | 84.78%  |
| Row Of Chips | 31        | 13.48%  |
| DIMM         | 2         | 0.87%   |
| Chip         | 2         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 108       | 45%     |
| 4096  | 63        | 26.25%  |
| 16384 | 41        | 17.08%  |
| 2048  | 13        | 5.42%   |
| 32768 | 12        | 5%      |
| 1024  | 3         | 1.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 78        | 33.48%  |
| 2667    | 43        | 18.45%  |
| 1600    | 42        | 18.03%  |
| 2400    | 19        | 8.15%   |
| 1333    | 9         | 3.86%   |
| 4267    | 7         | 3%      |
| 4800    | 6         | 2.58%   |
| 1334    | 6         | 2.58%   |
| 2133    | 5         | 2.15%   |
| 6400    | 3         | 1.29%   |
| 1867    | 3         | 1.29%   |
| 667     | 3         | 1.29%   |
| 4266    | 2         | 0.86%   |
| 8400    | 1         | 0.43%   |
| 3266    | 1         | 0.43%   |
| 2933    | 1         | 0.43%   |
| 2666    | 1         | 0.43%   |
| 2048    | 1         | 0.43%   |
| 1067    | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3110 Series | 1         | 33.33%  |
| Canon iP2600 series      | 1         | 33.33%  |
| Brother HL-2230 series   | 1         | 33.33%  |

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
| Chicony Electronics                    | 62        | 21.16%  |
| Acer                                   | 32        | 10.92%  |
| Microdia                               | 31        | 10.58%  |
| IMC Networks                           | 31        | 10.58%  |
| Quanta                                 | 24        | 8.19%   |
| Realtek Semiconductor                  | 21        | 7.17%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 4.44%   |
| Sunplus Innovation Technology          | 9         | 3.07%   |
| Luxvisions Innotech Limited            | 8         | 2.73%   |
| Logitech                               | 8         | 2.73%   |
| Lite-On Technology                     | 8         | 2.73%   |
| Syntek                                 | 6         | 2.05%   |
| Apple                                  | 5         | 1.71%   |
| Y Media                                | 4         | 1.37%   |
| Silicon Motion                         | 4         | 1.37%   |
| USB Camera                             | 2         | 0.68%   |
| Suyin                                  | 2         | 0.68%   |
| SunplusIT                              | 2         | 0.68%   |
| Samsung Electronics                    | 2         | 0.68%   |
| Alcor Micro                            | 2         | 0.68%   |
| Z-Star Microelectronics                | 1         | 0.34%   |
| Xiaomi                                 | 1         | 0.34%   |
| USB Camera CS                          | 1         | 0.34%   |
| STEREOLABS                             | 1         | 0.34%   |
| Sonix Technology                       | 1         | 0.34%   |
| SN0002                                 | 1         | 0.34%   |
| ShineTech                              | 1         | 0.34%   |
| Novatek Microelectronics               | 1         | 0.34%   |
| Lenovo                                 | 1         | 0.34%   |
| Importek                               | 1         | 0.34%   |
| Huawei Technologies                    | 1         | 0.34%   |
| HRY                                    | 1         | 0.34%   |
| Goodong Industry                       | 1         | 0.34%   |
| Goodong                                | 1         | 0.34%   |
| GEMBIRD                                | 1         | 0.34%   |
| eMPIA Technology                       | 1         | 0.34%   |
| DJJHFA1BIF5595                         | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 15        | 5.1%    |
| Chicony Integrated Camera                                       | 15        | 5.1%    |
| Acer Integrated Camera                                          | 15        | 5.1%    |
| IMC Networks Integrated Camera                                  | 12        | 4.08%   |
| Realtek Integrated_Webcam_HD                                    | 7         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 2.38%   |
| Chicony HD Webcam                                               | 7         | 2.38%   |
| Sunplus Integrated_Webcam_HD                                    | 6         | 2.04%   |
| Quanta HP TrueVision HD Camera                                  | 6         | 2.04%   |
| Chicony HD User Facing                                          | 6         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 1.7%    |
| Y Media USB Camera                                              | 4         | 1.36%   |
| Syntek Integrated Camera                                        | 4         | 1.36%   |
| Quanta HD User Facing                                           | 4         | 1.36%   |
| Microdia Integrated_Webcam_FHD                                  | 4         | 1.36%   |
| Chicony USB2.0 Camera                                           | 4         | 1.36%   |
| Realtek USB Camera                                              | 3         | 1.02%   |
| Quanta HP Wide Vision HD Camera                                 | 3         | 1.02%   |
| Microdia USB 2.0 Camera                                         | 3         | 1.02%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 1.02%   |
| Chicony HP Wide Vision HD Camera                                | 3         | 1.02%   |
| Chicony HP Truevision HD                                        | 3         | 1.02%   |
| Chicony HP HD Camera                                            | 3         | 1.02%   |
| Acer HD Webcam                                                  | 3         | 1.02%   |
| USB Camera USB Camera                                           | 2         | 0.68%   |
| Silicon Motion WebCam SC-13HDL11939N                            | 2         | 0.68%   |
| Samsung Galaxy A5 (MTP)                                         | 2         | 0.68%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 2         | 0.68%   |
| Realtek HD Webcam - Realtek                                     | 2         | 0.68%   |
| Quanta ov9734_techfront_camera                                  | 2         | 0.68%   |
| Quanta HD Webcam                                                | 2         | 0.68%   |
| Quanta HD Camera                                                | 2         | 0.68%   |
| Quanta ACER HD User Facing                                      | 2         | 0.68%   |
| Microdia Webcam Vitade AF                                       | 2         | 0.68%   |
| Microdia Integrated Webcam                                      | 2         | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera                   | 2         | 0.68%   |
| Logitech Webcam C310                                            | 2         | 0.68%   |
| Lite-On Integrated Camera                                       | 2         | 0.68%   |
| Lite-On HP HD Webcam                                            | 2         | 0.68%   |
| Lite-On HP HD Camera                                            | 2         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 22        | 33.85%  |
| Validity Sensors           | 16        | 24.62%  |
| Synaptics                  | 12        | 18.46%  |
| Elan Microelectronics      | 8         | 12.31%  |
| Upek                       | 3         | 4.62%   |
| AuthenTec                  | 2         | 3.08%   |
| STMicroelectronics         | 1         | 1.54%   |
| Focal-systems.Corp         | 1         | 1.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 19        | 29.23%  |
| Elan ELAN:ARM-M4                                           | 5         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 6.15%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 6.15%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 6.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 4.62%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 4.62%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 4.62%   |
| Elan ELAN:Fingerprint                                      | 3         | 4.62%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 2         | 3.08%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 3.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 3.08%   |
| Unknown                                                    | 2         | 3.08%   |
| Validity Sensors VFS491                                    | 1         | 1.54%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.54%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 1.54%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.54%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.54%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.54%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.54%   |
| AuthenTec Fingerprint Sensor                               | 1         | 1.54%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 1.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 42.86%  |
| Alcor Micro | 6         | 28.57%  |
| Upek        | 3         | 14.29%  |
| O2 Micro    | 1         | 4.76%   |
| Lenovo      | 1         | 4.76%   |
| BIT4ID      | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 14.29%  |
| Broadcom 5880                                                                | 3         | 14.29%  |
| Broadcom 58200                                                               | 3         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 9.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4.76%   |
| BIT4ID miniLector EVO                                                        | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 197       | 62.15%  |
| 1     | 91        | 28.71%  |
| 2     | 26        | 8.2%    |
| 9     | 1         | 0.32%   |
| 4     | 1         | 0.32%   |
| 3     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 65        | 43.33%  |
| Graphics card            | 20        | 13.33%  |
| Chipcard                 | 20        | 13.33%  |
| Multimedia controller    | 10        | 6.67%   |
| Camera                   | 10        | 6.67%   |
| Net/wireless             | 9         | 6%      |
| Sound                    | 4         | 2.67%   |
| Bluetooth                | 4         | 2.67%   |
| Communication controller | 3         | 2%      |
| Network                  | 2         | 1.33%   |
| Net/ethernet             | 2         | 1.33%   |
| Modem                    | 1         | 0.67%   |

