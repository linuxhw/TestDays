Solus - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Solus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 121

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [28c8bc52b8](https://linux-hardware.org/?probe=28c8bc52b8) | Mar 22, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell          | XPS 13 9380                 | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Google        | Delbin                      | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer          | Aspire A315-54              | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| Acer          | Swift SF114-34              | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba       | TECRA R840                  | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Sony          | VPCYB15AB                   | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| Dell          | Latitude 5580               | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Framework     | Laptop                      | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| Dell          | Latitude E6220              | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| Framework     | Laptop                      | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| AZW           | SEi                         | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Acer          | Nitro AN515-45              | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| Dell          | Inspiron 1525               | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell          | Inspiron 1525               | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Acer          | Nitro AN515-45              | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| Acer          | Nitro AN515-45              | [49cd3453c7](https://linux-hardware.org/?probe=49cd3453c7) | Aug 16, 2021 |
| Acer          | Nitro AN515-45              | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Dell          | Vostro 15-3568              | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Dell          | Inspiron 15-3573            | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |
| Dell          | Vostro 15-3568              | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| ASUSTek       | N53SV                       | [53fef6a61a](https://linux-hardware.org/?probe=53fef6a61a) | Jul 08, 2021 |
| Dell          | Inspiron 3537               | [6fc3976633](https://linux-hardware.org/?probe=6fc3976633) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| HP            | ProBook 650 G1              | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| Howard Com... | W350                        | [3e55c8284e](https://linux-hardware.org/?probe=3e55c8284e) | May 28, 2021 |
| Acer          | Aspire E5-575G              | [ce04df7bae](https://linux-hardware.org/?probe=ce04df7bae) | May 23, 2021 |
| Gigabyte      | AORUS 17G KB                | [fd9385ff3c](https://linux-hardware.org/?probe=fd9385ff3c) | Apr 29, 2021 |
| Packard Be... | EasyNote TS11HR             | [5c51b7f289](https://linux-hardware.org/?probe=5c51b7f289) | Apr 25, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| HP            | Pavilion dv7                | [e8b5a1786b](https://linux-hardware.org/?probe=e8b5a1786b) | Apr 08, 2021 |
| HP            | ProBook 650 G1              | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | ProBook 650 G1              | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| Toshiba       | Satellite L855              | [e507a57307](https://linux-hardware.org/?probe=e507a57307) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f1c277189f](https://linux-hardware.org/?probe=f1c277189f) | Feb 16, 2021 |
| Acer          | Aspire 5735                 | [d8b7b99dd0](https://linux-hardware.org/?probe=d8b7b99dd0) | Feb 16, 2021 |
| Toshiba       | Satellite L855              | [7a2993f67a](https://linux-hardware.org/?probe=7a2993f67a) | Feb 03, 2021 |
| Lenovo        | ThinkPad T410 2522Y1L       | [3c4543a94f](https://linux-hardware.org/?probe=3c4543a94f) | Jan 26, 2021 |
| Dell          | XPS 13 9360                 | [56d39c0f21](https://linux-hardware.org/?probe=56d39c0f21) | Jan 02, 2021 |
| Toshiba       | Satellite L855              | [0173204c7f](https://linux-hardware.org/?probe=0173204c7f) | Dec 23, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [26447067ee](https://linux-hardware.org/?probe=26447067ee) | Dec 20, 2020 |
| Acer          | Aspire A315-21              | [5f78418b58](https://linux-hardware.org/?probe=5f78418b58) | Dec 19, 2020 |
| HP            | EliteBook 840 G3            | [708eaf5602](https://linux-hardware.org/?probe=708eaf5602) | Dec 14, 2020 |
| Toshiba       | Satellite L855              | [3d3a517e96](https://linux-hardware.org/?probe=3d3a517e96) | Dec 11, 2020 |
| Sony          | VPCEB1S1E                   | [ebcb16e616](https://linux-hardware.org/?probe=ebcb16e616) | Nov 27, 2020 |
| Panasonic     | CF-C2CCEZXCM                | [cba289e868](https://linux-hardware.org/?probe=cba289e868) | Nov 22, 2020 |
| Acer          | Aspire E1-532P              | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Timi          | TM1701                      | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Apple         | MacBook5,2                  | [b21d4ca9d0](https://linux-hardware.org/?probe=b21d4ca9d0) | Oct 26, 2020 |
| Apple         | MacBook5,2                  | [eb1b0d459f](https://linux-hardware.org/?probe=eb1b0d459f) | Oct 25, 2020 |
| Toshiba       | PORTEGE Z20T-B              | [9d789eba3c](https://linux-hardware.org/?probe=9d789eba3c) | Oct 12, 2020 |
| Toshiba       | Satellite P50-A             | [884731a198](https://linux-hardware.org/?probe=884731a198) | Sep 28, 2020 |
| HP            | ProBook 450 G5              | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C5A... | [2f729ef2af](https://linux-hardware.org/?probe=2f729ef2af) | Sep 11, 2020 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [bcc44c581c](https://linux-hardware.org/?probe=bcc44c581c) | Sep 09, 2020 |
| Dell          | Inspiron 5577               | [b46a79f93e](https://linux-hardware.org/?probe=b46a79f93e) | Sep 03, 2020 |
| Acer          | Aspire ES1-111M             | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [793085b89a](https://linux-hardware.org/?probe=793085b89a) | Aug 15, 2020 |
| HP            | ProBook 440 G4              | [191f1be39f](https://linux-hardware.org/?probe=191f1be39f) | Aug 14, 2020 |
| HP            | ProBook 440 G4              | [c34e36f36e](https://linux-hardware.org/?probe=c34e36f36e) | Aug 10, 2020 |
| HP            | ProBook 440 G4              | [5b6c3861bb](https://linux-hardware.org/?probe=5b6c3861bb) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| Avell High... | Avell G1750 MUV / C65 MU... | [cf035fee07](https://linux-hardware.org/?probe=cf035fee07) | Jul 24, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | Presario C700               | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| ASUSTek       | K45A                        | [57c5b7b4bd](https://linux-hardware.org/?probe=57c5b7b4bd) | Jun 08, 2020 |
| Acer          | Predator PH315-52           | [b5e7780315](https://linux-hardware.org/?probe=b5e7780315) | Jun 04, 2020 |
| Lenovo        | Z51-70 80K6                 | [7b25fce04c](https://linux-hardware.org/?probe=7b25fce04c) | May 24, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [cb0fe570e2](https://linux-hardware.org/?probe=cb0fe570e2) | May 22, 2020 |
| Dell          | Latitude 7390               | [49112c8937](https://linux-hardware.org/?probe=49112c8937) | May 20, 2020 |
| HP            | ProBook 6470b               | [59db0f436f](https://linux-hardware.org/?probe=59db0f436f) | May 13, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [e98c6a162c](https://linux-hardware.org/?probe=e98c6a162c) | May 03, 2020 |
| Toshiba       | Satellite L655              | [32a9d86996](https://linux-hardware.org/?probe=32a9d86996) | May 02, 2020 |
| Acer          | Aspire E1-532P              | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| HP            | Pavilion dv6                | [6939cb8715](https://linux-hardware.org/?probe=6939cb8715) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | [328b82f240](https://linux-hardware.org/?probe=328b82f240) | Apr 11, 2020 |
| HP            | Pavilion dv6                | [0c6dc861d6](https://linux-hardware.org/?probe=0c6dc861d6) | Apr 06, 2020 |
| HP            | Pavilion dv6                | [d459f09cfe](https://linux-hardware.org/?probe=d459f09cfe) | Apr 01, 2020 |
| HP            | Pavilion dv6                | [3d9d707ea7](https://linux-hardware.org/?probe=3d9d707ea7) | Mar 30, 2020 |
| Chuwi         | LapBook SE                  | [f7cfd1b163](https://linux-hardware.org/?probe=f7cfd1b163) | Mar 26, 2020 |
| Acer          | Swift SF314-56              | [3826e4d14c](https://linux-hardware.org/?probe=3826e4d14c) | Mar 24, 2020 |
| Google        | Kip                         | [4f62ee34a3](https://linux-hardware.org/?probe=4f62ee34a3) | Mar 22, 2020 |
| Dell          | Vostro 3446                 | [c42d273e36](https://linux-hardware.org/?probe=c42d273e36) | Mar 12, 2020 |
| HP            | ProBook 450 G5              | [0c527b2640](https://linux-hardware.org/?probe=0c527b2640) | Mar 08, 2020 |
| Acer          | Aspire VN7-792G             | [3924df2c92](https://linux-hardware.org/?probe=3924df2c92) | Feb 28, 2020 |
| Apple         | MacBookPro10,2              | [1281c8c30d](https://linux-hardware.org/?probe=1281c8c30d) | Feb 26, 2020 |
| Lenovo        | ThinkPad T480 20L5S08L00    | [3c23e0d823](https://linux-hardware.org/?probe=3c23e0d823) | Feb 20, 2020 |
| Lenovo        | ThinkPad W530 243852U       | [eb8bd4a219](https://linux-hardware.org/?probe=eb8bd4a219) | Jan 20, 2020 |
| ASUSTek       | X556UQK                     | [5070b3831b](https://linux-hardware.org/?probe=5070b3831b) | Dec 29, 2019 |
| Lenovo        | ThinkPad X301 4057WHQ       | [badcab7790](https://linux-hardware.org/?probe=badcab7790) | Dec 22, 2019 |
| Dell          | Inspiron N5040              | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | [31f9126345](https://linux-hardware.org/?probe=31f9126345) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| Howard Com... | W350                        | [7434be9250](https://linux-hardware.org/?probe=7434be9250) | Dec 10, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ad5138a45f](https://linux-hardware.org/?probe=ad5138a45f) | Dec 04, 2019 |
| Acer          | Aspire E5-575G              | [99d56262c0](https://linux-hardware.org/?probe=99d56262c0) | Dec 03, 2019 |
| HP            | Pavilion 17                 | [09c3d61b20](https://linux-hardware.org/?probe=09c3d61b20) | Nov 18, 2019 |
| HP            | Stream Laptop 14-cb1XX      | [372f025649](https://linux-hardware.org/?probe=372f025649) | Nov 18, 2019 |
| HP            | 255 G1                      | [0a0d476781](https://linux-hardware.org/?probe=0a0d476781) | Nov 06, 2019 |
| HP            | 255 G1                      | [ccb02c7d8e](https://linux-hardware.org/?probe=ccb02c7d8e) | Nov 04, 2019 |
| HP            | 255 G1                      | [2aa8aaffc1](https://linux-hardware.org/?probe=2aa8aaffc1) | Nov 04, 2019 |
| Acer          | Swift SF315-52              | [c5950fe2b2](https://linux-hardware.org/?probe=c5950fe2b2) | Oct 20, 2019 |
| Toshiba       | Unknown                     | [64c90921de](https://linux-hardware.org/?probe=64c90921de) | Oct 18, 2019 |
| Dell          | Latitude 7490               | [2381ee7707](https://linux-hardware.org/?probe=2381ee7707) | Oct 14, 2019 |
| HP            | ENVY dv7                    | [1f13304239](https://linux-hardware.org/?probe=1f13304239) | Oct 06, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | [4e34d8767a](https://linux-hardware.org/?probe=4e34d8767a) | Aug 03, 2019 |
| Dell          | XPS 15 9560                 | [65f14ca77f](https://linux-hardware.org/?probe=65f14ca77f) | Jun 11, 2019 |
| HP            | EliteBook 8770w             | [fdba82a5b5](https://linux-hardware.org/?probe=fdba82a5b5) | Apr 01, 2019 |
| Acer          | Aspire V3-571G              | [0ffa9711e1](https://linux-hardware.org/?probe=0ffa9711e1) | Jan 07, 2019 |
| Acer          | Aspire V3-571G              | [46de1b2636](https://linux-hardware.org/?probe=46de1b2636) | Jan 07, 2019 |
| Acer          | Aspire E1-532P              | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Solus 4.1    | 39        | 44.32%  |
| Solus 4.3    | 18        | 20.45%  |
| Solus 4.0    | 17        | 19.32%  |
| Solus 4.2    | 13        | 14.77%  |
| Solus 3.9999 | 1         | 1.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Solus | 85        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 9         | 10.11%  |
| 5.6.4-152.current   | 5         | 5.62%   |
| 5.6.19-159.current  | 5         | 5.62%   |
| 5.6.13-153.current  | 4         | 4.49%   |
| 5.5.7-150.current   | 4         | 4.49%   |
| 5.3.7-132.current   | 3         | 3.37%   |
| 5.2.20-130.current  | 3         | 3.37%   |
| 5.14.21-210.current | 3         | 3.37%   |
| 5.13.1-187.current  | 3         | 3.37%   |
| 5.11.22-180.current | 3         | 3.37%   |
| 5.6.18-156.current  | 2         | 2.25%   |
| 5.5.4-148.current   | 2         | 2.25%   |
| 5.5.11-151.current  | 2         | 2.25%   |
| 5.4.12-144.current  | 2         | 2.25%   |
| 5.3.15-138.current  | 2         | 2.25%   |
| 5.3.10-134.current  | 2         | 2.25%   |
| 5.2.2-122.current   | 2         | 2.25%   |
| 5.14.16-205.current | 2         | 2.25%   |
| 5.13.6-190.current  | 2         | 2.25%   |
| 5.13.12-193.current | 2         | 2.25%   |
| 5.12.10-182.current | 2         | 2.25%   |
| 5.11.9-176.current  | 2         | 2.25%   |
| 5.11.12-177.current | 2         | 2.25%   |
| 5.10.12-171.current | 2         | 2.25%   |
| 5.6.18-155.current  | 1         | 1.12%   |
| 5.5.3-147.current   | 1         | 1.12%   |
| 5.4.12-143.current  | 1         | 1.12%   |
| 5.4.1-137.current   | 1         | 1.12%   |
| 5.2.13-126.current  | 1         | 1.12%   |
| 5.15.26-211.current | 1         | 1.12%   |
| 5.14.7-198.current  | 1         | 1.12%   |
| 5.14.16-204.current | 1         | 1.12%   |
| 5.14.15-203.current | 1         | 1.12%   |
| 5.14.12-201.current | 1         | 1.12%   |
| 5.13.15-194.current | 1         | 1.12%   |
| 5.13.0-186.current  | 1         | 1.12%   |
| 5.10.7-168.current  | 1         | 1.12%   |
| 5.10.2-164.current  | 1         | 1.12%   |
| 5.10.15-172.current | 1         | 1.12%   |
| 5.0.16-116.current  | 1         | 1.12%   |
| 4.20.16-112.current | 1         | 1.12%   |
| 4.18.16-97.current  | 1         | 1.12%   |
| 4.14.221-168.lts    | 1         | 1.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.6.19   | 14        | 15.73%  |
| 5.6.4    | 5         | 5.62%   |
| 5.6.13   | 4         | 4.49%   |
| 5.5.7    | 4         | 4.49%   |
| 5.6.18   | 3         | 3.37%   |
| 5.4.12   | 3         | 3.37%   |
| 5.3.7    | 3         | 3.37%   |
| 5.2.20   | 3         | 3.37%   |
| 5.14.21  | 3         | 3.37%   |
| 5.14.16  | 3         | 3.37%   |
| 5.13.1   | 3         | 3.37%   |
| 5.11.22  | 3         | 3.37%   |
| 5.5.4    | 2         | 2.25%   |
| 5.5.11   | 2         | 2.25%   |
| 5.3.15   | 2         | 2.25%   |
| 5.3.10   | 2         | 2.25%   |
| 5.2.2    | 2         | 2.25%   |
| 5.13.6   | 2         | 2.25%   |
| 5.13.12  | 2         | 2.25%   |
| 5.12.10  | 2         | 2.25%   |
| 5.11.9   | 2         | 2.25%   |
| 5.11.12  | 2         | 2.25%   |
| 5.10.12  | 2         | 2.25%   |
| 5.5.3    | 1         | 1.12%   |
| 5.4.1    | 1         | 1.12%   |
| 5.2.13   | 1         | 1.12%   |
| 5.15.26  | 1         | 1.12%   |
| 5.14.7   | 1         | 1.12%   |
| 5.14.15  | 1         | 1.12%   |
| 5.14.12  | 1         | 1.12%   |
| 5.13.15  | 1         | 1.12%   |
| 5.13.0   | 1         | 1.12%   |
| 5.10.7   | 1         | 1.12%   |
| 5.10.2   | 1         | 1.12%   |
| 5.10.15  | 1         | 1.12%   |
| 5.0.16   | 1         | 1.12%   |
| 4.20.16  | 1         | 1.12%   |
| 4.18.16  | 1         | 1.12%   |
| 4.14.221 | 1         | 1.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.6     | 26        | 29.55%  |
| 5.5     | 9         | 10.23%  |
| 5.14    | 9         | 10.23%  |
| 5.13    | 9         | 10.23%  |
| 5.3     | 7         | 7.95%   |
| 5.2     | 6         | 6.82%   |
| 5.11    | 6         | 6.82%   |
| 5.10    | 5         | 5.68%   |
| 5.4     | 4         | 4.55%   |
| 5.12    | 2         | 2.27%   |
| 5.15    | 1         | 1.14%   |
| 5.0     | 1         | 1.14%   |
| 4.20    | 1         | 1.14%   |
| 4.18    | 1         | 1.14%   |
| 4.14    | 1         | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 44        | 50%     |
| Unknown | 22        | 25%     |
| KDE     | 9         | 10.23%  |
| MATE    | 8         | 9.09%   |
| GNOME   | 5         | 5.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 85        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 65        | 75.58%  |
| TDM     | 12        | 13.95%  |
| LightDM | 5         | 5.81%   |
| SDDM    | 3         | 3.49%   |
| GDM     | 1         | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 44        | 51.16%  |
| Unknown | 10        | 11.63%  |
| en_GB   | 6         | 6.98%   |
| pt_BR   | 3         | 3.49%   |
| en_AU   | 3         | 3.49%   |
| tr_TR   | 2         | 2.33%   |
| pl_PL   | 2         | 2.33%   |
| it_IT   | 2         | 2.33%   |
| fr_FR   | 2         | 2.33%   |
| es_ES   | 2         | 2.33%   |
| en_NZ   | 2         | 2.33%   |
| de_DE   | 2         | 2.33%   |
| uk_UA   | 1         | 1.16%   |
| ru_RU   | 1         | 1.16%   |
| es_CL   | 1         | 1.16%   |
| en_IN   | 1         | 1.16%   |
| en_CA   | 1         | 1.16%   |
| de_AT   | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 53        | 62.35%  |
| BIOS | 32        | 37.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 79        | 91.86%  |
| Unknown | 7         | 8.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 65.12%  |
| GPT     | 24        | 27.91%  |
| MBR     | 6         | 6.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 92.94%  |
| Yes       | 6         | 7.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 80%     |
| Yes       | 17        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 15        | 17.65%  |
| Dell                   | 14        | 16.47%  |
| Acer                   | 14        | 16.47%  |
| Lenovo                 | 13        | 15.29%  |
| Toshiba                | 6         | 7.06%   |
| ASUSTek Computer       | 6         | 7.06%   |
| Sony                   | 2         | 2.35%   |
| Samsung Electronics    | 2         | 2.35%   |
| Google                 | 2         | 2.35%   |
| Apple                  | 2         | 2.35%   |
| Timi                   | 1         | 1.18%   |
| Panasonic              | 1         | 1.18%   |
| Packard Bell           | 1         | 1.18%   |
| Howard Computers       | 1         | 1.18%   |
| Gigabyte Technology    | 1         | 1.18%   |
| Framework              | 1         | 1.18%   |
| Chuwi                  | 1         | 1.18%   |
| AZW                    | 1         | 1.18%   |
| Avell High Performance | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Acer Aspire E5-575G                                   | 2         | 2.35%   |
| Toshiba TECRA R840                                    | 1         | 1.18%   |
| Toshiba Satellite P50-A                               | 1         | 1.18%   |
| Toshiba Satellite L855                                | 1         | 1.18%   |
| Toshiba Satellite L655                                | 1         | 1.18%   |
| Toshiba PORTEGE Z20T-B                                | 1         | 1.18%   |
| Timi TM1701                                           | 1         | 1.18%   |
| Sony VPCYB15AB                                        | 1         | 1.18%   |
| Sony VPCEB1S1E                                        | 1         | 1.18%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 1.18%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 1.18%   |
| Panasonic CF-C2CCEZXCM                                | 1         | 1.18%   |
| Packard Bell EasyNote TS11HR                          | 1         | 1.18%   |
| Lenovo Z51-70 80K6                                    | 1         | 1.18%   |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 1.18%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 1.18%   |
| Lenovo ThinkPad W530 243852U                          | 1         | 1.18%   |
| Lenovo ThinkPad T480 20L5S08L00                       | 1         | 1.18%   |
| Lenovo ThinkPad T440p 20AN009CUS                      | 1         | 1.18%   |
| Lenovo ThinkPad T430 2349CV2                          | 1         | 1.18%   |
| Lenovo ThinkPad T410 2522Y1L                          | 1         | 1.18%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW                 | 1         | 1.18%   |
| Lenovo ThinkPad Edge E440 20C5A03300                  | 1         | 1.18%   |
| Lenovo Legion Y530-15ICH 81FV                         | 1         | 1.18%   |
| Lenovo IdeaPad 330S-15IKB 81F5                        | 1         | 1.18%   |
| Lenovo IdeaPad 320-15ISK 80XH                         | 1         | 1.18%   |
| Howard Computers W350                                 | 1         | 1.18%   |
| HP Stream Laptop 14-cb1XX                             | 1         | 1.18%   |
| HP ProBook 650 G1                                     | 1         | 1.18%   |
| HP ProBook 6470b                                      | 1         | 1.18%   |
| HP ProBook 450 G5                                     | 1         | 1.18%   |
| HP ProBook 440 G4                                     | 1         | 1.18%   |
| HP Presario C700                                      | 1         | 1.18%   |
| HP Pavilion Laptop 15-cw0xxx                          | 1         | 1.18%   |
| HP Pavilion dv7                                       | 1         | 1.18%   |
| HP Pavilion dv6                                       | 1         | 1.18%   |
| HP Pavilion 17                                        | 1         | 1.18%   |
| HP OMEN Laptop 15-en0xxx                              | 1         | 1.18%   |
| HP ENVY dv7                                           | 1         | 1.18%   |
| HP EliteBook 8770w                                    | 1         | 1.18%   |
| HP EliteBook 840 G3                                   | 1         | 1.18%   |
| HP 255 G1                                             | 1         | 1.18%   |
| Google Kip                                            | 1         | 1.18%   |
| Google Delbin                                         | 1         | 1.18%   |
| Gigabyte AORUS 17G KB                                 | 1         | 1.18%   |
| Framework Laptop                                      | 1         | 1.18%   |
| Dell XPS 15 9560                                      | 1         | 1.18%   |
| Dell XPS 13 9380                                      | 1         | 1.18%   |
| Dell XPS 13 9360                                      | 1         | 1.18%   |
| Dell Vostro 3446                                      | 1         | 1.18%   |
| Dell Vostro 15-3568                                   | 1         | 1.18%   |
| Dell Latitude E6220                                   | 1         | 1.18%   |
| Dell Latitude 7490                                    | 1         | 1.18%   |
| Dell Latitude 7390                                    | 1         | 1.18%   |
| Dell Latitude 5580                                    | 1         | 1.18%   |
| Dell Inspiron N5040                                   | 1         | 1.18%   |
| Dell Inspiron 5577                                    | 1         | 1.18%   |
| Dell Inspiron 3537                                    | 1         | 1.18%   |
| Dell Inspiron 1525                                    | 1         | 1.18%   |
| Dell Inspiron 15-3573                                 | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 9         | 10.59%  |
| Acer Aspire                  | 9         | 10.59%  |
| Dell Inspiron                | 5         | 5.88%   |
| HP ProBook                   | 4         | 4.71%   |
| HP Pavilion                  | 4         | 4.71%   |
| Dell Latitude                | 4         | 4.71%   |
| Toshiba Satellite            | 3         | 3.53%   |
| Dell XPS                     | 3         | 3.53%   |
| Acer Swift                   | 3         | 3.53%   |
| Lenovo IdeaPad               | 2         | 2.35%   |
| HP EliteBook                 | 2         | 2.35%   |
| Dell Vostro                  | 2         | 2.35%   |
| Toshiba TECRA                | 1         | 1.18%   |
| Toshiba PORTEGE              | 1         | 1.18%   |
| Timi TM1701                  | 1         | 1.18%   |
| Sony VPCYB15AB               | 1         | 1.18%   |
| Sony VPCEB1S1E               | 1         | 1.18%   |
| Samsung 300E5EV              | 1         | 1.18%   |
| Samsung 270E5K               | 1         | 1.18%   |
| Panasonic CF-C2CCEZXCM       | 1         | 1.18%   |
| Packard Bell EasyNote        | 1         | 1.18%   |
| Lenovo Z51-70                | 1         | 1.18%   |
| Lenovo Legion                | 1         | 1.18%   |
| Howard Computers W350        | 1         | 1.18%   |
| HP Stream                    | 1         | 1.18%   |
| HP Presario                  | 1         | 1.18%   |
| HP OMEN                      | 1         | 1.18%   |
| HP ENVY                      | 1         | 1.18%   |
| HP 255                       | 1         | 1.18%   |
| Google Kip                   | 1         | 1.18%   |
| Google Delbin                | 1         | 1.18%   |
| Gigabyte AORUS               | 1         | 1.18%   |
| Framework Laptop             | 1         | 1.18%   |
| Chuwi LapBook                | 1         | 1.18%   |
| AZW SEi                      | 1         | 1.18%   |
| Avell High Performance Avell | 1         | 1.18%   |
| ASUS ZenBook                 | 1         | 1.18%   |
| ASUS X556UQK                 | 1         | 1.18%   |
| ASUS VivoBook                | 1         | 1.18%   |
| ASUS TUF                     | 1         | 1.18%   |
| ASUS N53SV                   | 1         | 1.18%   |
| ASUS K45A                    | 1         | 1.18%   |
| Apple MacBookPro10           | 1         | 1.18%   |
| Apple MacBook5               | 1         | 1.18%   |
| Acer Predator                | 1         | 1.18%   |
| Acer Nitro                   | 1         | 1.18%   |
| Unknown                      | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 12        | 14.12%  |
| 2016 | 11        | 12.94%  |
| 2012 | 9         | 10.59%  |
| 2017 | 7         | 8.24%   |
| 2019 | 6         | 7.06%   |
| 2014 | 6         | 7.06%   |
| 2013 | 6         | 7.06%   |
| 2020 | 5         | 5.88%   |
| 2011 | 5         | 5.88%   |
| 2021 | 4         | 4.71%   |
| 2010 | 4         | 4.71%   |
| 2008 | 4         | 4.71%   |
| 2009 | 3         | 3.53%   |
| 2015 | 2         | 2.35%   |
| 2007 | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 85        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 85        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 97.65%  |
| Yes  | 2         | 2.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 21        | 24.42%  |
| 3.01-4.0    | 20        | 23.26%  |
| 4.01-8.0    | 18        | 20.93%  |
| 16.01-24.0  | 16        | 18.6%   |
| 32.01-64.0  | 5         | 5.81%   |
| 1.01-2.0    | 3         | 3.49%   |
| 2.01-3.0    | 2         | 2.33%   |
| 64.01-256.0 | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 32        | 36.78%  |
| 2.01-3.0  | 24        | 27.59%  |
| 4.01-8.0  | 13        | 14.94%  |
| 3.01-4.0  | 10        | 11.49%  |
| 0.51-1.0  | 7         | 8.05%   |
| 8.01-16.0 | 1         | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 62        | 72.94%  |
| 2      | 22        | 25.88%  |
| 3      | 1         | 1.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 57.65%  |
| Yes       | 36        | 42.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 84.71%  |
| No        | 13        | 15.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 80%     |
| No        | 17        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 17        | 20%     |
| India              | 7         | 8.24%   |
| Brazil             | 6         | 7.06%   |
| Netherlands        | 5         | 5.88%   |
| UK                 | 3         | 3.53%   |
| Spain              | 3         | 3.53%   |
| Poland             | 3         | 3.53%   |
| Turkey             | 2         | 2.35%   |
| Russia             | 2         | 2.35%   |
| New Zealand        | 2         | 2.35%   |
| Indonesia          | 2         | 2.35%   |
| Guatemala          | 2         | 2.35%   |
| France             | 2         | 2.35%   |
| Chile              | 2         | 2.35%   |
| Australia          | 2         | 2.35%   |
| Vietnam            | 1         | 1.18%   |
| Venezuela          | 1         | 1.18%   |
| Ukraine            | 1         | 1.18%   |
| Switzerland        | 1         | 1.18%   |
| Sweden             | 1         | 1.18%   |
| Saudi Arabia       | 1         | 1.18%   |
| Oman               | 1         | 1.18%   |
| Norway             | 1         | 1.18%   |
| Nepal              | 1         | 1.18%   |
| Mexico             | 1         | 1.18%   |
| Latvia             | 1         | 1.18%   |
| Japan              | 1         | 1.18%   |
| Italy              | 1         | 1.18%   |
| Iran               | 1         | 1.18%   |
| Hungary            | 1         | 1.18%   |
| Greece             | 1         | 1.18%   |
| Germany            | 1         | 1.18%   |
| Finland            | 1         | 1.18%   |
| Dominican Republic | 1         | 1.18%   |
| China              | 1         | 1.18%   |
| Canada             | 1         | 1.18%   |
| Belgium            | 1         | 1.18%   |
| Belarus            | 1         | 1.18%   |
| Austria            | 1         | 1.18%   |
| Albania            | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Guatemala City        | 2         | 2.33%   |
| Delhi                 | 2         | 2.33%   |
| Columbus              | 2         | 2.33%   |
| Auckland              | 2         | 2.33%   |
| Г„ngelholm         | 1         | 1.16%   |
| Zoutleeuw             | 1         | 1.16%   |
| Yverdon-les-Bains     | 1         | 1.16%   |
| Winchmore Hill        | 1         | 1.16%   |
| Vineland              | 1         | 1.16%   |
| Vienna                | 1         | 1.16%   |
| Toronto               | 1         | 1.16%   |
| Tirana                | 1         | 1.16%   |
| The Hague             | 1         | 1.16%   |
| Tehran                | 1         | 1.16%   |
| Stroudsburg           | 1         | 1.16%   |
| St. Cloud             | 1         | 1.16%   |
| St Petersburg         | 1         | 1.16%   |
| Severna Park          | 1         | 1.16%   |
| Semarang              | 1         | 1.16%   |
| Santo Domingo Este    | 1         | 1.16%   |
| Santiago              | 1         | 1.16%   |
| San Jose              | 1         | 1.16%   |
| Saint Paul            | 1         | 1.16%   |
| Riga                  | 1         | 1.16%   |
| Red Oak               | 1         | 1.16%   |
| Providencia           | 1         | 1.16%   |
| Portland              | 1         | 1.16%   |
| Pessac                | 1         | 1.16%   |
| Parkdale              | 1         | 1.16%   |
| Paracuellos de Jarama | 1         | 1.16%   |
| Oslo                  | 1         | 1.16%   |
| NieporÄ™t          | 1         | 1.16%   |
| New York              | 1         | 1.16%   |
| Navelim               | 1         | 1.16%   |
| Naaldwijk             | 1         | 1.16%   |
| MГЎlaga             | 1         | 1.16%   |
| Muscat                | 1         | 1.16%   |
| Muiderberg            | 1         | 1.16%   |
| Moscow                | 1         | 1.16%   |
| Morioka               | 1         | 1.16%   |
| Minsk                 | 1         | 1.16%   |
| Milwaukee             | 1         | 1.16%   |
| Melbourne             | 1         | 1.16%   |
| Marica                | 1         | 1.16%   |
| Madrid                | 1         | 1.16%   |
| Lubbock               | 1         | 1.16%   |
| Kyiv                  | 1         | 1.16%   |
| Kayseri               | 1         | 1.16%   |
| Kathmandu             | 1         | 1.16%   |
| Jeddah                | 1         | 1.16%   |
| Impruneta             | 1         | 1.16%   |
| Hyvinkaeae            | 1         | 1.16%   |
| Hyderabad             | 1         | 1.16%   |
| Humble                | 1         | 1.16%   |
| HrubieszГіw         | 1         | 1.16%   |
| Hartington            | 1         | 1.16%   |
| Hanoi                 | 1         | 1.16%   |
| Guarulhos             | 1         | 1.16%   |
| Guanajuato City       | 1         | 1.16%   |
| Groningen             | 1         | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 16     | 14.02%  |
| Toshiba             | 15        | 18     | 14.02%  |
| Samsung Electronics | 14        | 15     | 13.08%  |
| Seagate             | 11        | 12     | 10.28%  |
| Sandisk             | 7         | 8      | 6.54%   |
| Kingston            | 7         | 7      | 6.54%   |
| SK Hynix            | 6         | 6      | 5.61%   |
| Unknown             | 5         | 5      | 4.67%   |
| Micron Technology   | 5         | 6      | 4.67%   |
| Intel               | 4         | 5      | 3.74%   |
| Crucial             | 3         | 4      | 2.8%    |
| Silicon Motion      | 2         | 2      | 1.87%   |
| Hitachi             | 2         | 2      | 1.87%   |
| Transcend           | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Lenovo              | 1         | 1      | 0.93%   |
| KingFast            | 1         | 1      | 0.93%   |
| HGST                | 1         | 1      | 0.93%   |
| Gigabyte Technology | 1         | 1      | 0.93%   |
| FORESEE             | 1         | 1      | 0.93%   |
| Apple               | 1         | 1      | 0.93%   |
| Advantech           | 1         | 1      | 0.93%   |
| AAPL                | 1         | 1      | 0.93%   |
| A-DATA Technology   | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 5         | 4.55%   |
| Sandisk NVMe SSD Drive 256GB            | 3         | 2.73%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 2.73%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 1.82%   |
| Unknown MMC Card  32GB                  | 2         | 1.82%   |
| SK Hynix NVMe SSD Drive 128GB           | 2         | 1.82%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.82%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.91%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.91%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.91%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 0.91%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 1         | 0.91%   |
| WDC WD2500LPVX-22V0TT0 250GB            | 1         | 0.91%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.91%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.91%   |
| WDC WD2500BEVT-00A23T0 250GB            | 1         | 0.91%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.91%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.91%   |
| WDC WD10JPVX-08JC3T5 1TB                | 1         | 0.91%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB    | 1         | 0.91%   |
| Unknown USB DISK 3.2 500GB              | 1         | 0.91%   |
| Unknown MMC Card  128GB                 | 1         | 0.91%   |
| Unknown AJNB4R  16GB                    | 1         | 0.91%   |
| Transcend TS240GSSD220S 240GB           | 1         | 0.91%   |
| Toshiba THNSNJ256GVNU 256GB SSD         | 1         | 0.91%   |
| Toshiba THNS128GG4BNAA 128GB SSD        | 1         | 0.91%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.91%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.91%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.91%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.91%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.91%   |
| Toshiba MK5055GSX 500GB                 | 1         | 0.91%   |
| Toshiba KXG60ZNV512G NVMe 512GB         | 1         | 0.91%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 1         | 0.91%   |
| SK Hynix PC401 HFS256GD9TNG-62A0A 256GB | 1         | 0.91%   |
| SK Hynix NVMe SSD Drive 500GB           | 1         | 0.91%   |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 0.91%   |
| SK Hynix HFM512GDJTNG-8310A 512GB       | 1         | 0.91%   |
| Silicon Motion NVMe SSD Drive 512GB     | 1         | 0.91%   |
| Silicon Motion IM2P33F8BR1-512GB        | 1         | 0.91%   |
| Seagate ST9750420AS 752GB               | 1         | 0.91%   |
| Seagate ST9500325AS 500GB               | 1         | 0.91%   |
| Seagate ST9320325AS 320GB               | 1         | 0.91%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.91%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 0.91%   |
| Seagate ST250LM004 HN-M250MBB 250GB     | 1         | 0.91%   |
| Seagate ST2000LX001-1RG174 2TB          | 1         | 0.91%   |
| Seagate ST1000LX001-1EM164 1TB          | 1         | 0.91%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.91%   |
| Seagate ST1000LM014-SSHD-8GB            | 1         | 0.91%   |
| SanDisk X400 M.2 2280 256GB SSD         | 1         | 0.91%   |
| SanDisk SDSSDA120G 120GB                | 1         | 0.91%   |
| SanDisk SD7SN6S512G1001 512GB SSD       | 1         | 0.91%   |
| Sandisk NVMe SSD Drive 1TB              | 1         | 0.91%   |
| SanDisk Extreme Pro 1TB                 | 1         | 0.91%   |
| Samsung SSD 970 EVO Plus 2TB            | 1         | 0.91%   |
| Samsung SSD 860 EVO 500GB               | 1         | 0.91%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 0.91%   |
| Samsung SSD 850 EVO 500GB               | 1         | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 12     | 31.43%  |
| Seagate | 11        | 12     | 31.43%  |
| Toshiba | 9         | 12     | 25.71%  |
| Hitachi | 2         | 2      | 5.71%   |
| HGST    | 1         | 1      | 2.86%   |
| AAPL    | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 24.32%  |
| Kingston            | 5         | 5      | 13.51%  |
| Micron Technology   | 4         | 5      | 10.81%  |
| SanDisk             | 3         | 3      | 8.11%   |
| Intel               | 3         | 4      | 8.11%   |
| Crucial             | 3         | 4      | 8.11%   |
| WDC                 | 2         | 2      | 5.41%   |
| Toshiba             | 2         | 2      | 5.41%   |
| Transcend           | 1         | 1      | 2.7%    |
| PNY                 | 1         | 1      | 2.7%    |
| Gigabyte Technology | 1         | 1      | 2.7%    |
| FORESEE             | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |
| Advantech           | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 35        | 40     | 34.65%  |
| HDD     | 34        | 40     | 33.66%  |
| NVMe    | 26        | 31     | 25.74%  |
| MMC     | 4         | 4      | 3.96%   |
| Unknown | 2         | 2      | 1.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 61        | 79     | 64.89%  |
| NVMe | 26        | 31     | 27.66%  |
| MMC  | 4         | 4      | 4.26%   |
| SAS  | 3         | 3      | 3.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 54     | 67.16%  |
| 0.51-1.0   | 21        | 25     | 31.34%  |
| 1.01-2.0   | 1         | 1      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 41        | 48.24%  |
| 251-500    | 19        | 22.35%  |
| 501-1000   | 9         | 10.59%  |
| 1001-2000  | 7         | 8.24%   |
| 21-50      | 3         | 3.53%   |
| 1-20       | 2         | 2.35%   |
| 51-100     | 2         | 2.35%   |
| Unknown    | 2         | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 37        | 42.53%  |
| 21-50     | 14        | 16.09%  |
| 101-250   | 11        | 12.64%  |
| 51-100    | 11        | 12.64%  |
| 251-500   | 8         | 9.2%    |
| 1001-2000 | 2         | 2.3%    |
| 501-1000  | 2         | 2.3%    |
| Unknown   | 2         | 2.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB                    | 1         | 1      | 25%     |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB   | 1         | 1      | 25%     |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 25%     |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Micron Technology   | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| SSD  | 1         | 1      | 25%     |

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
| Detected | 60        | 81     | 66.67%  |
| Works    | 26        | 32     | 28.89%  |
| Malfunc  | 4         | 4      | 4.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 64        | 63.37%  |
| AMD                          | 8         | 7.92%   |
| SK Hynix                     | 6         | 5.94%   |
| Sandisk                      | 5         | 4.95%   |
| Samsung Electronics          | 5         | 4.95%   |
| Toshiba America Info Systems | 4         | 3.96%   |
| Silicon Motion               | 2         | 1.98%   |
| Kingston Technology Company  | 2         | 1.98%   |
| Nvidia                       | 1         | 0.99%   |
| Micron Technology            | 1         | 0.99%   |
| Lenovo                       | 1         | 0.99%   |
| JMicron Technology           | 1         | 0.99%   |
| ADATA Technology             | 1         | 0.99%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 10.68%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 7.77%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 6.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 5.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.88%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 2.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 2.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.91%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 2         | 1.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 1.94%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.94%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.94%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 1.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.97%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.97%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.97%   |
| SK Hynix PC300 NVMe Solid State Drive 256GB                                      | 1         | 0.97%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.97%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.97%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.97%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.97%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.97%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.97%   |
| Intel SSD 660P Series                                                            | 1         | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.97%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 67        | 68.37%  |
| NVMe | 25        | 25.51%  |
| RAID | 3         | 3.06%   |
| IDE  | 3         | 3.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 89.41%  |
| AMD    | 9         | 10.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 7.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 3.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 3.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 3.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.35%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 2.35%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 2.35%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 2.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 2.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.35%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 2.35%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 2.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.35%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.35%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.18%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 1.18%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.18%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 1.18%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.18%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.18%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.18%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.18%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.18%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.18%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.18%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.18%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.18%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 1.18%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.18%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.18%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.18%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.18%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.18%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.18%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.18%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 1.18%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1.18%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.18%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.18%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.18%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 1.18%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.18%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.18%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz          | 1         | 1.18%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.18%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.18%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 1.18%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.18%   |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 1.18%   |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 1.18%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 1.18%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.18%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.18%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 31        | 36.47%  |
| Intel Core i7        | 20        | 23.53%  |
| Intel Celeron        | 7         | 8.24%   |
| Intel Core i3        | 6         | 7.06%   |
| Other                | 4         | 4.71%   |
| Intel Core 2 Duo     | 4         | 4.71%   |
| AMD Ryzen 7          | 4         | 4.71%   |
| Intel Pentium        | 2         | 2.35%   |
| AMD Ryzen 5          | 2         | 2.35%   |
| Intel Pentium Silver | 1         | 1.18%   |
| Intel Pentium Dual   | 1         | 1.18%   |
| Intel Core M         | 1         | 1.18%   |
| AMD E1               | 1         | 1.18%   |
| AMD E                | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 60%     |
| 4      | 27        | 31.76%  |
| 6      | 4         | 4.71%   |
| 8      | 2         | 2.35%   |
| 1      | 1         | 1.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 77.65%  |
| 1      | 19        | 22.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 94.19%  |
| Unknown        | 5         | 5.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ea    | 8         | 9.3%    |
| 0x306a9    | 8         | 9.3%    |
| 0x206a7    | 7         | 8.14%   |
| 0x806e9    | 6         | 6.98%   |
| 0x40651    | 4         | 4.65%   |
| 0x306c3    | 4         | 4.65%   |
| 0x20655    | 4         | 4.65%   |
| 0x906ea    | 3         | 3.49%   |
| 0x906e9    | 3         | 3.49%   |
| 0x806c1    | 3         | 3.49%   |
| 0x706a1    | 3         | 3.49%   |
| 0x406e3    | 3         | 3.49%   |
| 0x306d4    | 3         | 3.49%   |
| Unknown    | 3         | 3.49%   |
| 0x806ec    | 2         | 2.33%   |
| 0x6fd      | 2         | 2.33%   |
| 0x30678    | 2         | 2.33%   |
| 0x1067a    | 2         | 2.33%   |
| 0x08108102 | 2         | 2.33%   |
| 0xa0652    | 1         | 1.16%   |
| 0x906c0    | 1         | 1.16%   |
| 0x806eb    | 1         | 1.16%   |
| 0x506e3    | 1         | 1.16%   |
| 0x20652    | 1         | 1.16%   |
| 0x10676    | 1         | 1.16%   |
| 0x10661    | 1         | 1.16%   |
| 0x0a50000c | 1         | 1.16%   |
| 0x08600106 | 1         | 1.16%   |
| 0x08108109 | 1         | 1.16%   |
| 0x0810100b | 1         | 1.16%   |
| 0x06006704 | 1         | 1.16%   |
| 0x05000119 | 1         | 1.16%   |
| 0x05000029 | 1         | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 28.24%  |
| Haswell       | 9         | 10.59%  |
| IvyBridge     | 8         | 9.41%   |
| SandyBridge   | 7         | 8.24%   |
| Westmere      | 5         | 5.88%   |
| Skylake       | 4         | 4.71%   |
| Zen+          | 3         | 3.53%   |
| TigerLake     | 3         | 3.53%   |
| Penryn        | 3         | 3.53%   |
| Goldmont plus | 3         | 3.53%   |
| Core          | 3         | 3.53%   |
| Broadwell     | 3         | 3.53%   |
| Silvermont    | 2         | 2.35%   |
| Bobcat        | 2         | 2.35%   |
| Zen 3         | 1         | 1.18%   |
| Zen 2         | 1         | 1.18%   |
| Zen           | 1         | 1.18%   |
| Tremont       | 1         | 1.18%   |
| Excavator     | 1         | 1.18%   |
| CometLake     | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 70        | 61.4%   |
| Nvidia | 26        | 22.81%  |
| AMD    | 18        | 15.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 7         | 6.03%   |
| Intel HD Graphics 620                                                                 | 7         | 6.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 7         | 6.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 6         | 5.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 5         | 4.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 3.45%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 3         | 2.59%   |
| Intel HD Graphics 630                                                                 | 3         | 2.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 2.59%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 2.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 2.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 3         | 2.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 1.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 2         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.72%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 2         | 1.72%   |
| Nvidia GF108M [GeForce GT 540M]                                                       | 2         | 1.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 2         | 1.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 1.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 1.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 2         | 1.72%   |
| Intel HD Graphics 5500                                                                | 2         | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.72%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 2         | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.86%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.86%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.86%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.86%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.86%   |
| Nvidia GM107 [GeForce 940MX]                                                          | 1         | 0.86%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 0.86%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 0.86%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 1         | 0.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 0.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 0.86%   |
| Nvidia C79 [GeForce 9400M G]                                                          | 1         | 0.86%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 0.86%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 0.86%   |
| Intel HD Graphics 5300                                                                | 1         | 0.86%   |
| Intel HD Graphics 530                                                                 | 1         | 0.86%   |
| Intel HD Graphics 520                                                                 | 1         | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 0.86%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                      | 1         | 0.86%   |
| AMD Wrestler [Radeon HD 7310]                                                         | 1         | 0.86%   |
| AMD Wrestler [Radeon HD 6310]                                                         | 1         | 0.86%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                         | 1         | 0.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 0.86%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 1         | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 1         | 0.86%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 0.86%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                          | 1         | 0.86%   |
| AMD Renoir                                                                            | 1         | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 0.86%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 1         | 0.86%   |
| AMD Chelsea XT GL [FirePro M4000]                                                     | 1         | 0.86%   |
| AMD Cezanne                                                                           | 1         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 51.76%  |
| Intel + Nvidia | 22        | 25.88%  |
| 1 x AMD        | 11        | 12.94%  |
| Intel + AMD    | 4         | 4.71%   |
| AMD + Nvidia   | 3         | 3.53%   |
| 1 x Nvidia     | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 69        | 81.18%  |
| Proprietary | 16        | 18.82%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 54.12%  |
| 1.01-2.0   | 15        | 17.65%  |
| 0.51-1.0   | 10        | 11.76%  |
| 0.01-0.5   | 6         | 7.06%   |
| 3.01-4.0   | 5         | 5.88%   |
| 5.01-6.0   | 3         | 3.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 22.77%  |
| LG Display              | 14        | 13.86%  |
| Samsung Electronics     | 12        | 11.88%  |
| BOE                     | 12        | 11.88%  |
| Chimei Innolux          | 10        | 9.9%    |
| Lenovo                  | 4         | 3.96%   |
| Goldstar                | 4         | 3.96%   |
| Sharp                   | 3         | 2.97%   |
| PANDA                   | 2         | 1.98%   |
| Chi Mei Optoelectronics | 2         | 1.98%   |
| BenQ                    | 2         | 1.98%   |
| Apple                   | 2         | 1.98%   |
| AOC                     | 2         | 1.98%   |
| ___                     | 1         | 0.99%   |
| Unknown                 | 1         | 0.99%   |
| Toshiba                 | 1         | 0.99%   |
| Sony                    | 1         | 0.99%   |
| Philips                 | 1         | 0.99%   |
| GKK                     | 1         | 0.99%   |
| Dell                    | 1         | 0.99%   |
| CSO                     | 1         | 0.99%   |
| Acer                    | 1         | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.96%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.98%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.98%   |
| Toshiba Internal LCD TOS5091 1366x768 340x190mm 15.3-inch             | 1         | 0.98%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.98%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.98%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.98%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch  | 1         | 0.98%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch   | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3641 1366x768 353x198mm 15.9-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4250 1920x1080 276x156mm 12.5-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.98%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 0.98%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch     | 1         | 0.98%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                 | 1         | 0.98%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.98%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.98%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0404 1366x768 277x156mm 12.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0383 1600x900 382x215mm 17.3-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD020C 1600x900 345x194mm 15.6-inch           | 1         | 0.98%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4074 1440x900 287x180mm 13.3-inch               | 1         | 0.98%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 1         | 0.98%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                   | 1         | 0.98%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 1         | 0.98%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 1         | 0.98%   |
| Goldstar E2241 GSM581A 1920x1080 477x268mm 21.5-inch                  | 1         | 0.98%   |
| Goldstar E1911 GSM4BF9 1366x768 410x230mm 18.5-inch                   | 1         | 0.98%   |
| GKK MONITOR GKK3034 1920x1080                                         | 1         | 0.98%   |
| Dell G2410 DEL404B 1920x1080 530x300mm 24.0-inch                      | 1         | 0.98%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                 | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch      | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1469 1366x768 309x174mm 14.0-inch       | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 42        | 45.16%  |
| 1366x768 (WXGA)    | 30        | 32.26%  |
| 1600x900 (HD+)     | 7         | 7.53%   |
| 1440x900 (WXGA+)   | 3         | 3.23%   |
| 1280x800 (WXGA)    | 3         | 3.23%   |
| 3840x2160 (4K)     | 2         | 2.15%   |
| 2560x1600          | 1         | 1.08%   |
| 2560x1440 (QHD)    | 1         | 1.08%   |
| 2560x1080          | 1         | 1.08%   |
| 2256x1504          | 1         | 1.08%   |
| 1680x1050 (WSXGA+) | 1         | 1.08%   |
| 1360x768           | 1         | 1.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 48        | 48%     |
| 13      | 17        | 17%     |
| 14      | 9         | 9%      |
| 17      | 7         | 7%      |
| 24      | 3         | 3%      |
| 23      | 3         | 3%      |
| 21      | 3         | 3%      |
| 27      | 2         | 2%      |
| 12      | 2         | 2%      |
| 72      | 1         | 1%      |
| 40      | 1         | 1%      |
| 34      | 1         | 1%      |
| 18      | 1         | 1%      |
| 11      | 1         | 1%      |
| Unknown | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 63.64%  |
| 201-300     | 11        | 11.11%  |
| 351-400     | 9         | 9.09%   |
| 501-600     | 7         | 7.07%   |
| 401-500     | 5         | 5.05%   |
| 801-900     | 1         | 1.01%   |
| 701-800     | 1         | 1.01%   |
| 1501-2000   | 1         | 1.01%   |
| Unknown     | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 77        | 89.53%  |
| 16/10 | 6         | 6.98%   |
| 3/2   | 2         | 2.33%   |
| 21/9  | 1         | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 47%     |
| 81-90          | 20        | 20%     |
| 201-250        | 8         | 8%      |
| 121-130        | 7         | 7%      |
| 71-80          | 6         | 6%      |
| 61-70          | 2         | 2%      |
| 301-350        | 2         | 2%      |
| More than 1000 | 1         | 1%      |
| 51-60          | 1         | 1%      |
| 351-500        | 1         | 1%      |
| 151-200        | 1         | 1%      |
| 141-150        | 1         | 1%      |
| 501-1000       | 1         | 1%      |
| 91-100         | 1         | 1%      |
| Unknown        | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 37        | 38.54%  |
| 101-120       | 32        | 33.33%  |
| 51-100        | 15        | 15.63%  |
| 161-240       | 8         | 8.33%   |
| More than 240 | 2         | 2.08%   |
| 1-50          | 1         | 1.04%   |
| Unknown       | 1         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 71        | 82.56%  |
| 2     | 13        | 15.12%  |
| 3     | 2         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 45        | 31.91%  |
| Realtek Semiconductor         | 42        | 29.79%  |
| Qualcomm Atheros              | 26        | 18.44%  |
| Broadcom                      | 9         | 6.38%   |
| Marvell Technology Group      | 3         | 2.13%   |
| Ralink                        | 2         | 1.42%   |
| Dell                          | 2         | 1.42%   |
| TP-Link                       | 1         | 0.71%   |
| Sierra Wireless               | 1         | 0.71%   |
| Samsung Electronics           | 1         | 0.71%   |
| Ralink Technology             | 1         | 0.71%   |
| Qualcomm                      | 1         | 0.71%   |
| OnePlus Technology (Shenzhen) | 1         | 0.71%   |
| Nvidia                        | 1         | 0.71%   |
| MEDIATEK                      | 1         | 0.71%   |
| Lenovo                        | 1         | 0.71%   |
| Jolla Oy                      | 1         | 0.71%   |
| Hewlett-Packard               | 1         | 0.71%   |
| Android                       | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 28        | 16.67%  |
| Intel Wireless 8265 / 8275                                                     | 8         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 7         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 2.98%   |
| Intel Wireless 7260                                                            | 5         | 2.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 4         | 2.38%   |
| Intel Wireless 3165                                                            | 3         | 1.79%   |
| Intel Wi-Fi 6 AX200                                                            | 3         | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 1.19%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.19%   |
| Intel Wireless 8260                                                            | 2         | 1.19%   |
| Intel Wireless 7265                                                            | 2         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.19%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                  | 2         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 1.19%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 2         | 1.19%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 2         | 1.19%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.6%    |
| Sierra Wireless EM7305                                                         | 1         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.6%    |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1         | 0.6%    |
| Qualcomm Redmi Note 8T                                                         | 1         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.6%    |
| OnePlus (Shenzhen) AC2001                                                      | 1         | 0.6%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.6%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.6%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.6%    |
| Lenovo Thinkpad USB LAN                                                        | 1         | 0.6%    |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 0.6%    |
| Intel Wireless 3160                                                            | 1         | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.6%    |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 1         | 0.6%    |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 0.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 1         | 0.6%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.6%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 50%     |
| Qualcomm Atheros      | 23        | 25.56%  |
| Realtek Semiconductor | 8         | 8.89%   |
| Broadcom              | 7         | 7.78%   |
| Ralink                | 2         | 2.22%   |
| Sierra Wireless       | 1         | 1.11%   |
| Ralink Technology     | 1         | 1.11%   |
| MEDIATEK              | 1         | 1.11%   |
| Hewlett-Packard       | 1         | 1.11%   |
| Dell                  | 1         | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 8         | 8.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 7.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 5.56%   |
| Intel Wireless 7260                                            | 5         | 5.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 4.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 4.44%   |
| Intel Wireless 3165                                            | 3         | 3.33%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 2.22%   |
| Intel Wireless 8260                                            | 2         | 2.22%   |
| Intel Wireless 7265                                            | 2         | 2.22%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.22%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.22%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.22%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 2.22%   |
| Sierra Wireless EM7305                                         | 1         | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.11%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.11%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 1.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.11%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.11%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.11%   |
| Intel Wireless 3160                                            | 1         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1.11%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.11%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.11%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.11%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.11%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.11%   |
| HP lt4112 Gobi 4G Module Network Device                        | 1         | 1.11%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 1.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.11%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 50%     |
| Intel                    | 20        | 26.32%  |
| Qualcomm Atheros         | 5         | 6.58%   |
| Marvell Technology Group | 3         | 3.95%   |
| Broadcom                 | 3         | 3.95%   |
| TP-Link                  | 1         | 1.32%   |
| Samsung Electronics      | 1         | 1.32%   |
| Qualcomm                 | 1         | 1.32%   |
| Nvidia                   | 1         | 1.32%   |
| Lenovo                   | 1         | 1.32%   |
| Jolla Oy                 | 1         | 1.32%   |
| Android                  | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 28        | 36.84%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 9.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 7.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 2.63%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.63%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 2.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.32%   |
| Qualcomm Redmi Note 8T                                                         | 1         | 1.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.32%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.32%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.32%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 1.32%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.32%   |
| Lenovo Thinkpad USB LAN                                                        | 1         | 1.32%   |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 1.32%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.32%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.32%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.32%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.32%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.32%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.32%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.32%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.32%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.32%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.32%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 1.32%   |
| Android Android                                                                | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 53.46%  |
| Ethernet | 72        | 45.28%  |
| Modem    | 1         | 0.63%   |
| Unknown  | 1         | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 61.29%  |
| Ethernet | 48        | 38.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 69        | 81.18%  |
| 1     | 16        | 18.82%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 91.76%  |
| Yes  | 7         | 8.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 50%     |
| Lite-On Technology              | 9         | 13.24%  |
| Qualcomm Atheros Communications | 7         | 10.29%  |
| Realtek Semiconductor           | 3         | 4.41%   |
| IMC Networks                    | 3         | 4.41%   |
| Broadcom                        | 3         | 4.41%   |
| Foxconn / Hon Hai               | 2         | 2.94%   |
| Apple                           | 2         | 2.94%   |
| Toshiba                         | 1         | 1.47%   |
| Ralink                          | 1         | 1.47%   |
| Hewlett-Packard                 | 1         | 1.47%   |
| Dell                            | 1         | 1.47%   |
| Cambridge Silicon Radio         | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 29.41%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 7.35%   |
| Intel Bluetooth Device                                                              | 3         | 4.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 4.41%   |
| Intel AX200 Bluetooth                                                               | 3         | 4.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 2.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.94%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 2.94%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.94%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 1.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.47%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1.47%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.47%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.47%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.47%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.47%   |
| Lite-On Wireless_Device                                                             | 1         | 1.47%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.47%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.47%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.47%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.47%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.47%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.47%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.47%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.47%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.47%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 75        | 71.43%  |
| AMD                 | 14        | 13.33%  |
| Nvidia              | 13        | 12.38%  |
| Samsung Electronics | 1         | 0.95%   |
| GYROCOM C&C         | 1         | 0.95%   |
| Conexant Systems    | 1         | 0.95%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 17        | 13.82%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 7.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 4.88%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6         | 4.88%   |
| Intel Haswell-ULT HD Audio Controller                                             | 5         | 4.07%   |
| Intel 8 Series HD Audio Controller                                                | 5         | 4.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 5         | 4.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4         | 3.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 2.44%   |
| Intel CM238 HD Audio Controller                                                   | 3         | 2.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3         | 2.44%   |
| Intel Cannon Lake PCH cAVS                                                        | 3         | 2.44%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 2.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 2.44%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.63%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.63%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2         | 1.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 1.63%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 1.63%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 2         | 1.63%   |
| Samsung Electronics USBC Headset                                                  | 1         | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.81%   |
| Nvidia MCP79 High Definition Audio                                                | 1         | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1         | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.81%   |
| Nvidia Audio device                                                               | 1         | 0.81%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 0.81%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                         | 1         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1         | 0.81%   |
| GYROCOM C&C Fiio E10                                                              | 1         | 0.81%   |
| Conexant Systems Hi-Res Audio                                                     | 1         | 0.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1         | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 1         | 0.81%   |
| AMD High Definition Audio Controller                                              | 1         | 0.81%   |
| AMD FCH Azalia Controller                                                         | 1         | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 0.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 25.53%  |
| SK Hynix            | 9         | 19.15%  |
| A-DATA Technology   | 5         | 10.64%  |
| Kingston            | 4         | 8.51%   |
| Nanya Technology    | 3         | 6.38%   |
| Micron Technology   | 3         | 6.38%   |
| Crucial             | 3         | 6.38%   |
| Unknown             | 2         | 4.26%   |
| Ramaxel Technology  | 2         | 4.26%   |
| Elpida              | 2         | 4.26%   |
| Team                | 1         | 2.13%   |
| G.Skill             | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 4.26%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s          | 2         | 4.26%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 2.13%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 2.13%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 1         | 2.13%   |
| SK Hynix RAM Module 2048MB SODIMM DDR2 800MT/s                   | 1         | 2.13%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 2.13%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.13%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.13%   |
| SK Hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.13%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.13%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 2.13%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 2.13%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Samsung RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 2.13%   |
| Ramaxel RAM RMT3170EB68E9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 2.13%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 2.13%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s         | 1         | 2.13%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Kingston RAM 99U5663-003.A00G 16GB SODIMM DDR4 2400MT/s          | 1         | 2.13%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s           | 1         | 2.13%   |
| G.Skill RAM F4-3200C22-16GRS 16384MB SODIMM DDR4 3200MT/s        | 1         | 2.13%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| Elpida RAM EBJ81UG8BBU0-GN-F 8192MB SODIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Crucial RAM CT8G4SFS824A.C8FE 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| Crucial RAM CT32G4SFD832A.M16FB 32GB SODIMM DDR4 3200MT/s        | 1         | 2.13%   |
| Crucial RAM CB4GS2400.M8E 4096MB SODIMM DDR4 2400MT/s            | 1         | 2.13%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2400MT/s                    | 1         | 2.13%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 2.13%   |
| A-DATA RAM AO1P24HC8T1-B2NS 8GB SODIMM DDR4 2133MT/s             | 1         | 2.13%   |
| A-DATA RAM AO1P21FC4R1-B2MS 4GB SODIMM DDR4 2133MT/s             | 1         | 2.13%   |
| A-DATA RAM AM1P26KC8T1-BBSS 8GB SODIMM DDR4 2667MT/s             | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 48.65%  |
| DDR3   | 12        | 32.43%  |
| LPDDR3 | 2         | 5.41%   |
| DDR2   | 2         | 5.41%   |
| SDRAM  | 1         | 2.7%    |
| LPDDR4 | 1         | 2.7%    |
| DDR    | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 94.44%  |
| Row Of Chips | 2         | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 40.54%  |
| 4096  | 11        | 29.73%  |
| 2048  | 5         | 13.51%  |
| 16384 | 3         | 8.11%   |
| 32768 | 2         | 5.41%   |
| 1024  | 1         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 21.95%  |
| 2667    | 8         | 19.51%  |
| 2400    | 5         | 12.2%   |
| 3200    | 4         | 9.76%   |
| 2133    | 4         | 9.76%   |
| 1334    | 2         | 4.88%   |
| Unknown | 2         | 4.88%   |
| 4267    | 1         | 2.44%   |
| 3266    | 1         | 2.44%   |
| 2048    | 1         | 2.44%   |
| 1333    | 1         | 2.44%   |
| 1067    | 1         | 2.44%   |
| 800     | 1         | 2.44%   |
| 667     | 1         | 2.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother MFC-9330CDW | 1         | 100%    |

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
| Chicony Electronics                    | 20        | 25.32%  |
| Realtek Semiconductor                  | 9         | 11.39%  |
| IMC Networks                           | 8         | 10.13%  |
| Microdia                               | 7         | 8.86%   |
| Quanta                                 | 6         | 7.59%   |
| Sunplus Innovation Technology          | 4         | 5.06%   |
| Acer                                   | 4         | 5.06%   |
| Suyin                                  | 3         | 3.8%    |
| Logitech                               | 3         | 3.8%    |
| Lite-On Technology                     | 3         | 3.8%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.8%    |
| Lenovo                                 | 2         | 2.53%   |
| Importek                               | 2         | 2.53%   |
| Unknown                                | 1         | 1.27%   |
| Syntek                                 | 1         | 1.27%   |
| Silicon Motion                         | 1         | 1.27%   |
| Intel                                  | 1         | 1.27%   |
| Apple                                  | 1         | 1.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                               | 6         | 7.5%    |
| IMC Networks USB2.0 HD UVC WebCam                               | 3         | 3.75%   |
| Chicony Integrated Camera                                       | 3         | 3.75%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 2         | 2.5%    |
| Sunplus Integrated_Webcam_HD                                    | 2         | 2.5%    |
| Realtek Integrated Webcam_HD                                    | 2         | 2.5%    |
| Realtek HD WebCam                                               | 2         | 2.5%    |
| Quanta HD User Facing                                           | 2         | 2.5%    |
| Microdia Integrated_Webcam_HD                                   | 2         | 2.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                              | 2         | 2.5%    |
| IMC Networks Integrated Camera                                  | 2         | 2.5%    |
| Unknown ATIV VGA CAMERA                                         | 1         | 1.25%   |
| Syntek USB2.0 Camera                                            | 1         | 1.25%   |
| Suyin 1.3M HD WebCam                                            | 1         | 1.25%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 1.25%   |
| Sunplus Laptop Integrated WebCam HD                             | 1         | 1.25%   |
| Silicon Motion WebCam SC-10HDD12636N                            | 1         | 1.25%   |
| Realtek Laptop Camera                                           | 1         | 1.25%   |
| Realtek Integrated Webcam HD                                    | 1         | 1.25%   |
| Realtek Integrated Webcam                                       | 1         | 1.25%   |
| Realtek Integrated Camera                                       | 1         | 1.25%   |
| Realtek HP Truevision HD                                        | 1         | 1.25%   |
| Quanta VGA WebCam                                               | 1         | 1.25%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 1.25%   |
| Quanta HP Wide Vision HD Camera                                 | 1         | 1.25%   |
| Quanta HP TrueVision HD Webcam                                  | 1         | 1.25%   |
| Microdia Webcam                                                 | 1         | 1.25%   |
| Microdia USB 2.0 Camera                                         | 1         | 1.25%   |
| Microdia Laptop_Integrated_Webcam_0.3M                          | 1         | 1.25%   |
| Microdia Integrated Webcam HD                                   | 1         | 1.25%   |
| Microdia Dell Laptop Integrated Webcam HD                       | 1         | 1.25%   |
| Logitech Webcam C310                                            | 1         | 1.25%   |
| Logitech Webcam C270                                            | 1         | 1.25%   |
| Logitech HD Pro Webcam C920                                     | 1         | 1.25%   |
| Lite-On Integrated Camera                                       | 1         | 1.25%   |
| Lite-On HP HD Webcam                                            | 1         | 1.25%   |
| Lite-On HP HD Camera                                            | 1         | 1.25%   |
| Lenovo UVC Camera                                               | 1         | 1.25%   |
| Lenovo Integrated Webcam [R5U877]                               | 1         | 1.25%   |
| Intel RealSense 3D Camera (Front F200)                          | 1         | 1.25%   |
| Importek TOSHIBA Web Camera - HD                                | 1         | 1.25%   |
| Importek Laptop Integrated Webcam                               | 1         | 1.25%   |
| IMC Networks UVC VGA Webcam                                     | 1         | 1.25%   |
| Chicony VGA WebCam                                              | 1         | 1.25%   |
| Chicony TOSHIBA Web Camera - FHD                                | 1         | 1.25%   |
| Chicony TOSHIBA Web Camera - 5M                                 | 1         | 1.25%   |
| Chicony Sony Visual Communication Camera                        | 1         | 1.25%   |
| Chicony Integrated HP HD Webcam                                 | 1         | 1.25%   |
| Chicony HP Webcam                                               | 1         | 1.25%   |
| Chicony HP Truevision HD camera                                 | 1         | 1.25%   |
| Chicony HP HD Camera                                            | 1         | 1.25%   |
| Chicony HD WebCam (Acer)                                        | 1         | 1.25%   |
| Chicony EasyCamera                                              | 1         | 1.25%   |
| Chicony CNF9055 Toshiba Webcam                                  | 1         | 1.25%   |
| Chicony 2.0M UVC WebCam                                         | 1         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam    | 1         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 1.25%   |
| Apple FaceTime HD Camera (Built-in)                             | 1         | 1.25%   |
| Acer USB HD Webcam                                              | 1         | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 10        | 50%     |
| Upek                  | 2         | 10%     |
| Synaptics             | 2         | 10%     |
| LighTuning Technology | 2         | 10%     |
| Elan Microelectronics | 2         | 10%     |
| AuthenTec             | 2         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 15%     |
| Validity Sensors Fingerprint scanner                   | 2         | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 10%     |
| Elan ELAN:Fingerprint                                  | 2         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5%      |
| Validity Sensors VFS491                                | 1         | 5%      |
| Validity Sensors VFS Fingerprint sensor                | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5%      |
| Upek TCS5B Fingerprint sensor                          | 1         | 5%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5%      |
| AuthenTec Fingerprint Sensor                           | 1         | 5%      |
| AuthenTec AES2810                                      | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 2         | 28.57%  |
| Alcor Micro | 2         | 28.57%  |
| O2 Micro    | 1         | 14.29%  |
| Lenovo      | 1         | 14.29%  |
| Broadcom    | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 14.29%  |
| Lenovo Integrated Smart Card Reader                        | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 53        | 62.35%  |
| 1     | 23        | 27.06%  |
| 2     | 9         | 10.59%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 20        | 47.62%  |
| Net/wireless          | 7         | 16.67%  |
| Chipcard              | 6         | 14.29%  |
| Multimedia controller | 2         | 4.76%   |
| Graphics card         | 2         | 4.76%   |
| Unassigned class      | 1         | 2.38%   |
| Storage               | 1         | 2.38%   |
| Net/ethernet          | 1         | 2.38%   |
| Camera                | 1         | 2.38%   |
| Bluetooth             | 1         | 2.38%   |

