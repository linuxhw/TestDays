Solus - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Solus.

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

Total: 128

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S340-15API 81NC     | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Acer          | Aspire A315-54              | [9e0bbc26f4](https://linux-hardware.org/?probe=9e0bbc26f4) | Jul 22, 2022 |
| AZW           | SEi                         | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| GPU Compan... | GWTC116-2                   | [d0c0f4f120](https://linux-hardware.org/?probe=d0c0f4f120) | Jul 06, 2022 |
| GPU Compan... | GWTC116-2                   | [9d0dd21c70](https://linux-hardware.org/?probe=9d0dd21c70) | Jul 06, 2022 |
| HP            | ProBook 450 G5              | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 450 G5              | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| Google        | Edgar                       | [fef9eeb5db](https://linux-hardware.org/?probe=fef9eeb5db) | May 02, 2022 |
| Lenovo        | Z50-70 20354                | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| Dell          | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
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
| Dell          | Inspiron N5040              | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| Howard Com... | W350                        | [7434be9250](https://linux-hardware.org/?probe=7434be9250) | Dec 10, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ad5138a45f](https://linux-hardware.org/?probe=ad5138a45f) | Dec 04, 2019 |
| Acer          | Aspire E5-575G              | [99d56262c0](https://linux-hardware.org/?probe=99d56262c0) | Dec 03, 2019 |
| HP            | Pavilion 17                 | [09c3d61b20](https://linux-hardware.org/?probe=09c3d61b20) | Nov 18, 2019 |
| HP            | Stream Laptop 14-cb1XX      | [372f025649](https://linux-hardware.org/?probe=372f025649) | Nov 18, 2019 |
| HP            | 255 G1                      | [0a0d476781](https://linux-hardware.org/?probe=0a0d476781) | Nov 06, 2019 |
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
| Solus 4.1    | 39        | 41.49%  |
| Solus 4.3    | 24        | 25.53%  |
| Solus 4.0    | 17        | 18.09%  |
| Solus 4.2    | 13        | 13.83%  |
| Solus 3.9999 | 1         | 1.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Solus | 91        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 9         | 9.28%   |
| 5.6.4-152.current   | 5         | 5.15%   |
| 5.6.19-159.current  | 5         | 5.15%   |
| 5.6.13-153.current  | 4         | 4.12%   |
| 5.5.7-150.current   | 4         | 4.12%   |
| 5.15.50-216.current | 4         | 4.12%   |
| 5.3.7-132.current   | 3         | 3.09%   |
| 5.2.20-130.current  | 3         | 3.09%   |
| 5.15.32-213.current | 3         | 3.09%   |
| 5.14.21-210.current | 3         | 3.09%   |
| 5.13.1-187.current  | 3         | 3.09%   |
| 5.11.22-180.current | 3         | 3.09%   |
| 5.6.18-156.current  | 2         | 2.06%   |
| 5.5.4-148.current   | 2         | 2.06%   |
| 5.5.11-151.current  | 2         | 2.06%   |
| 5.4.12-144.current  | 2         | 2.06%   |
| 5.3.15-138.current  | 2         | 2.06%   |
| 5.3.10-134.current  | 2         | 2.06%   |
| 5.2.2-122.current   | 2         | 2.06%   |
| 5.14.16-205.current | 2         | 2.06%   |
| 5.13.6-190.current  | 2         | 2.06%   |
| 5.13.12-193.current | 2         | 2.06%   |
| 5.12.10-182.current | 2         | 2.06%   |
| 5.11.9-176.current  | 2         | 2.06%   |
| 5.11.12-177.current | 2         | 2.06%   |
| 5.10.12-171.current | 2         | 2.06%   |
| 5.6.18-155.current  | 1         | 1.03%   |
| 5.5.3-147.current   | 1         | 1.03%   |
| 5.4.12-143.current  | 1         | 1.03%   |
| 5.4.1-137.current   | 1         | 1.03%   |
| 5.2.13-126.current  | 1         | 1.03%   |
| 5.15.37-214.current | 1         | 1.03%   |
| 5.15.26-211.current | 1         | 1.03%   |
| 5.14.7-198.current  | 1         | 1.03%   |
| 5.14.16-204.current | 1         | 1.03%   |
| 5.14.15-203.current | 1         | 1.03%   |
| 5.14.12-201.current | 1         | 1.03%   |
| 5.13.15-194.current | 1         | 1.03%   |
| 5.13.0-186.current  | 1         | 1.03%   |
| 5.10.7-168.current  | 1         | 1.03%   |
| 5.10.2-164.current  | 1         | 1.03%   |
| 5.10.15-172.current | 1         | 1.03%   |
| 5.0.16-116.current  | 1         | 1.03%   |
| 4.20.16-112.current | 1         | 1.03%   |
| 4.18.16-97.current  | 1         | 1.03%   |
| 4.14.221-168.lts    | 1         | 1.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.6.19   | 14        | 14.43%  |
| 5.6.4    | 5         | 5.15%   |
| 5.6.13   | 4         | 4.12%   |
| 5.5.7    | 4         | 4.12%   |
| 5.15.50  | 4         | 4.12%   |
| 5.6.18   | 3         | 3.09%   |
| 5.4.12   | 3         | 3.09%   |
| 5.3.7    | 3         | 3.09%   |
| 5.2.20   | 3         | 3.09%   |
| 5.15.32  | 3         | 3.09%   |
| 5.14.21  | 3         | 3.09%   |
| 5.14.16  | 3         | 3.09%   |
| 5.13.1   | 3         | 3.09%   |
| 5.11.22  | 3         | 3.09%   |
| 5.5.4    | 2         | 2.06%   |
| 5.5.11   | 2         | 2.06%   |
| 5.3.15   | 2         | 2.06%   |
| 5.3.10   | 2         | 2.06%   |
| 5.2.2    | 2         | 2.06%   |
| 5.13.6   | 2         | 2.06%   |
| 5.13.12  | 2         | 2.06%   |
| 5.12.10  | 2         | 2.06%   |
| 5.11.9   | 2         | 2.06%   |
| 5.11.12  | 2         | 2.06%   |
| 5.10.12  | 2         | 2.06%   |
| 5.5.3    | 1         | 1.03%   |
| 5.4.1    | 1         | 1.03%   |
| 5.2.13   | 1         | 1.03%   |
| 5.15.37  | 1         | 1.03%   |
| 5.15.26  | 1         | 1.03%   |
| 5.14.7   | 1         | 1.03%   |
| 5.14.15  | 1         | 1.03%   |
| 5.14.12  | 1         | 1.03%   |
| 5.13.15  | 1         | 1.03%   |
| 5.13.0   | 1         | 1.03%   |
| 5.10.7   | 1         | 1.03%   |
| 5.10.2   | 1         | 1.03%   |
| 5.10.15  | 1         | 1.03%   |
| 5.0.16   | 1         | 1.03%   |
| 4.20.16  | 1         | 1.03%   |
| 4.18.16  | 1         | 1.03%   |
| 4.14.221 | 1         | 1.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.6     | 26        | 27.08%  |
| 5.5     | 9         | 9.38%   |
| 5.15    | 9         | 9.38%   |
| 5.14    | 9         | 9.38%   |
| 5.13    | 9         | 9.38%   |
| 5.3     | 7         | 7.29%   |
| 5.2     | 6         | 6.25%   |
| 5.11    | 6         | 6.25%   |
| 5.10    | 5         | 5.21%   |
| 5.4     | 4         | 4.17%   |
| 5.12    | 2         | 2.08%   |
| 5.0     | 1         | 1.04%   |
| 4.20    | 1         | 1.04%   |
| 4.18    | 1         | 1.04%   |
| 4.14    | 1         | 1.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 91        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 46        | 48.94%  |
| Unknown | 22        | 23.4%   |
| MATE    | 9         | 9.57%   |
| KDE     | 9         | 9.57%   |
| GNOME   | 5         | 5.32%   |
| KDE5    | 3         | 3.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 91        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 68        | 73.91%  |
| TDM     | 12        | 13.04%  |
| LightDM | 7         | 7.61%   |
| SDDM    | 4         | 4.35%   |
| GDM     | 1         | 1.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 49        | 53.26%  |
| Unknown | 10        | 10.87%  |
| en_GB   | 6         | 6.52%   |
| pt_BR   | 3         | 3.26%   |
| fr_FR   | 3         | 3.26%   |
| en_AU   | 3         | 3.26%   |
| tr_TR   | 2         | 2.17%   |
| pl_PL   | 2         | 2.17%   |
| it_IT   | 2         | 2.17%   |
| es_ES   | 2         | 2.17%   |
| en_NZ   | 2         | 2.17%   |
| de_DE   | 2         | 2.17%   |
| uk_UA   | 1         | 1.09%   |
| ru_RU   | 1         | 1.09%   |
| es_CL   | 1         | 1.09%   |
| en_IN   | 1         | 1.09%   |
| en_CA   | 1         | 1.09%   |
| de_AT   | 1         | 1.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 62.37%  |
| BIOS | 35        | 37.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 85        | 92.39%  |
| Unknown | 7         | 7.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 60        | 65.22%  |
| GPT     | 26        | 28.26%  |
| MBR     | 6         | 6.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 93.41%  |
| Yes       | 6         | 6.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 81.32%  |
| Yes       | 17        | 18.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 16        | 17.58%  |
| Lenovo                 | 15        | 16.48%  |
| Dell                   | 15        | 16.48%  |
| Acer                   | 14        | 15.38%  |
| Toshiba                | 6         | 6.59%   |
| ASUSTek Computer       | 6         | 6.59%   |
| Google                 | 3         | 3.3%    |
| Sony                   | 2         | 2.2%    |
| Samsung Electronics    | 2         | 2.2%    |
| Apple                  | 2         | 2.2%    |
| Timi                   | 1         | 1.1%    |
| Panasonic              | 1         | 1.1%    |
| Packard Bell           | 1         | 1.1%    |
| Howard Computers       | 1         | 1.1%    |
| GPU Company            | 1         | 1.1%    |
| Gigabyte Technology    | 1         | 1.1%    |
| Framework              | 1         | 1.1%    |
| Chuwi                  | 1         | 1.1%    |
| AZW                    | 1         | 1.1%    |
| Avell High Performance | 1         | 1.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G5                                     | 2         | 2.2%    |
| Acer Aspire E5-575G                                   | 2         | 2.2%    |
| Toshiba TECRA R840                                    | 1         | 1.1%    |
| Toshiba Satellite P50-A                               | 1         | 1.1%    |
| Toshiba Satellite L855                                | 1         | 1.1%    |
| Toshiba Satellite L655                                | 1         | 1.1%    |
| Toshiba PORTEGE Z20T-B                                | 1         | 1.1%    |
| Timi TM1701                                           | 1         | 1.1%    |
| Sony VPCYB15AB                                        | 1         | 1.1%    |
| Sony VPCEB1S1E                                        | 1         | 1.1%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 1.1%    |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 1.1%    |
| Panasonic CF-C2CCEZXCM                                | 1         | 1.1%    |
| Packard Bell EasyNote TS11HR                          | 1         | 1.1%    |
| Lenovo Z51-70 80K6                                    | 1         | 1.1%    |
| Lenovo Z50-70 20354                                   | 1         | 1.1%    |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 1.1%    |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 1.1%    |
| Lenovo ThinkPad W530 243852U                          | 1         | 1.1%    |
| Lenovo ThinkPad T480 20L5S08L00                       | 1         | 1.1%    |
| Lenovo ThinkPad T440p 20AN009CUS                      | 1         | 1.1%    |
| Lenovo ThinkPad T430 2349CV2                          | 1         | 1.1%    |
| Lenovo ThinkPad T410 2522Y1L                          | 1         | 1.1%    |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW                 | 1         | 1.1%    |
| Lenovo ThinkPad Edge E440 20C5A03300                  | 1         | 1.1%    |
| Lenovo Legion Y530-15ICH 81FV                         | 1         | 1.1%    |
| Lenovo IdeaPad S340-15API 81NC                        | 1         | 1.1%    |
| Lenovo IdeaPad 330S-15IKB 81F5                        | 1         | 1.1%    |
| Lenovo IdeaPad 320-15ISK 80XH                         | 1         | 1.1%    |
| Howard Computers W350                                 | 1         | 1.1%    |
| HP Stream Laptop 14-cb1XX                             | 1         | 1.1%    |
| HP ProBook 650 G1                                     | 1         | 1.1%    |
| HP ProBook 6470b                                      | 1         | 1.1%    |
| HP ProBook 440 G4                                     | 1         | 1.1%    |
| HP Presario C700                                      | 1         | 1.1%    |
| HP Pavilion Laptop 15-cw0xxx                          | 1         | 1.1%    |
| HP Pavilion dv7                                       | 1         | 1.1%    |
| HP Pavilion dv6                                       | 1         | 1.1%    |
| HP Pavilion 17                                        | 1         | 1.1%    |
| HP OMEN Laptop 15-en0xxx                              | 1         | 1.1%    |
| HP ENVY dv7                                           | 1         | 1.1%    |
| HP EliteBook 8770w                                    | 1         | 1.1%    |
| HP EliteBook 840 G3                                   | 1         | 1.1%    |
| HP 255 G1                                             | 1         | 1.1%    |
| GPU Company GWTC116-2                                 | 1         | 1.1%    |
| Google Kip                                            | 1         | 1.1%    |
| Google Edgar                                          | 1         | 1.1%    |
| Google Delbin                                         | 1         | 1.1%    |
| Gigabyte AORUS 17G KB                                 | 1         | 1.1%    |
| Framework Laptop                                      | 1         | 1.1%    |
| Dell XPS 15 9560                                      | 1         | 1.1%    |
| Dell XPS 13 9380                                      | 1         | 1.1%    |
| Dell XPS 13 9360                                      | 1         | 1.1%    |
| Dell XPS 13 7390                                      | 1         | 1.1%    |
| Dell Vostro 3446                                      | 1         | 1.1%    |
| Dell Vostro 15-3568                                   | 1         | 1.1%    |
| Dell Latitude E6220                                   | 1         | 1.1%    |
| Dell Latitude 7490                                    | 1         | 1.1%    |
| Dell Latitude 7390                                    | 1         | 1.1%    |
| Dell Latitude 5580                                    | 1         | 1.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 9         | 9.89%   |
| Acer Aspire                  | 9         | 9.89%   |
| HP ProBook                   | 5         | 5.49%   |
| Dell Inspiron                | 5         | 5.49%   |
| HP Pavilion                  | 4         | 4.4%    |
| Dell XPS                     | 4         | 4.4%    |
| Dell Latitude                | 4         | 4.4%    |
| Toshiba Satellite            | 3         | 3.3%    |
| Lenovo IdeaPad               | 3         | 3.3%    |
| Acer Swift                   | 3         | 3.3%    |
| HP EliteBook                 | 2         | 2.2%    |
| Dell Vostro                  | 2         | 2.2%    |
| Toshiba TECRA                | 1         | 1.1%    |
| Toshiba PORTEGE              | 1         | 1.1%    |
| Timi TM1701                  | 1         | 1.1%    |
| Sony VPCYB15AB               | 1         | 1.1%    |
| Sony VPCEB1S1E               | 1         | 1.1%    |
| Samsung 300E5EV              | 1         | 1.1%    |
| Samsung 270E5K               | 1         | 1.1%    |
| Panasonic CF-C2CCEZXCM       | 1         | 1.1%    |
| Packard Bell EasyNote        | 1         | 1.1%    |
| Lenovo Z51-70                | 1         | 1.1%    |
| Lenovo Z50-70                | 1         | 1.1%    |
| Lenovo Legion                | 1         | 1.1%    |
| Howard Computers W350        | 1         | 1.1%    |
| HP Stream                    | 1         | 1.1%    |
| HP Presario                  | 1         | 1.1%    |
| HP OMEN                      | 1         | 1.1%    |
| HP ENVY                      | 1         | 1.1%    |
| HP 255                       | 1         | 1.1%    |
| GPU Company GWTC116-2        | 1         | 1.1%    |
| Google Kip                   | 1         | 1.1%    |
| Google Edgar                 | 1         | 1.1%    |
| Google Delbin                | 1         | 1.1%    |
| Gigabyte AORUS               | 1         | 1.1%    |
| Framework Laptop             | 1         | 1.1%    |
| Chuwi LapBook                | 1         | 1.1%    |
| AZW SEi                      | 1         | 1.1%    |
| Avell High Performance Avell | 1         | 1.1%    |
| ASUS ZenBook                 | 1         | 1.1%    |
| ASUS X556UQK                 | 1         | 1.1%    |
| ASUS VivoBook                | 1         | 1.1%    |
| ASUS TUF                     | 1         | 1.1%    |
| ASUS N53SV                   | 1         | 1.1%    |
| ASUS K45A                    | 1         | 1.1%    |
| Apple MacBookPro10           | 1         | 1.1%    |
| Apple MacBook5               | 1         | 1.1%    |
| Acer Predator                | 1         | 1.1%    |
| Acer Nitro                   | 1         | 1.1%    |
| Unknown                      | 1         | 1.1%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 12        | 13.19%  |
| 2016 | 11        | 12.09%  |
| 2019 | 9         | 9.89%   |
| 2012 | 9         | 9.89%   |
| 2017 | 8         | 8.79%   |
| 2014 | 7         | 7.69%   |
| 2013 | 6         | 6.59%   |
| 2021 | 5         | 5.49%   |
| 2020 | 5         | 5.49%   |
| 2011 | 5         | 5.49%   |
| 2010 | 4         | 4.4%    |
| 2008 | 4         | 4.4%    |
| 2009 | 3         | 3.3%    |
| 2015 | 2         | 2.2%    |
| 2007 | 1         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 91        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 91        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 88        | 96.7%   |
| Yes  | 3         | 3.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 23        | 25%     |
| 8.01-16.0   | 21        | 22.83%  |
| 4.01-8.0    | 19        | 20.65%  |
| 16.01-24.0  | 18        | 19.57%  |
| 32.01-64.0  | 5         | 5.43%   |
| 1.01-2.0    | 3         | 3.26%   |
| 2.01-3.0    | 2         | 2.17%   |
| 64.01-256.0 | 1         | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 37        | 38.54%  |
| 2.01-3.0  | 27        | 28.13%  |
| 4.01-8.0  | 14        | 14.58%  |
| 3.01-4.0  | 10        | 10.42%  |
| 0.51-1.0  | 7         | 7.29%   |
| 8.01-16.0 | 1         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 73.63%  |
| 2      | 23        | 25.27%  |
| 3      | 1         | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 59.34%  |
| Yes       | 37        | 40.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 81.32%  |
| No        | 17        | 18.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 80.22%  |
| No        | 18        | 19.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 19        | 20.88%  |
| India              | 8         | 8.79%   |
| Brazil             | 6         | 6.59%   |
| Netherlands        | 5         | 5.49%   |
| UK                 | 3         | 3.3%    |
| Spain              | 3         | 3.3%    |
| Poland             | 3         | 3.3%    |
| France             | 3         | 3.3%    |
| Australia          | 3         | 3.3%    |
| Ukraine            | 2         | 2.2%    |
| Turkey             | 2         | 2.2%    |
| Russia             | 2         | 2.2%    |
| New Zealand        | 2         | 2.2%    |
| Indonesia          | 2         | 2.2%    |
| Guatemala          | 2         | 2.2%    |
| Chile              | 2         | 2.2%    |
| Vietnam            | 1         | 1.1%    |
| Venezuela          | 1         | 1.1%    |
| Switzerland        | 1         | 1.1%    |
| Sweden             | 1         | 1.1%    |
| Saudi Arabia       | 1         | 1.1%    |
| Oman               | 1         | 1.1%    |
| Norway             | 1         | 1.1%    |
| Nepal              | 1         | 1.1%    |
| Mexico             | 1         | 1.1%    |
| Latvia             | 1         | 1.1%    |
| Japan              | 1         | 1.1%    |
| Italy              | 1         | 1.1%    |
| Iran               | 1         | 1.1%    |
| Hungary            | 1         | 1.1%    |
| Greece             | 1         | 1.1%    |
| Germany            | 1         | 1.1%    |
| Finland            | 1         | 1.1%    |
| Dominican Republic | 1         | 1.1%    |
| China              | 1         | 1.1%    |
| Canada             | 1         | 1.1%    |
| Belgium            | 1         | 1.1%    |
| Belarus            | 1         | 1.1%    |
| Austria            | 1         | 1.1%    |
| Albania            | 1         | 1.1%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Melbourne                 | 3         | 3.16%   |
| Guatemala City            | 2         | 2.11%   |
| Columbus                  | 2         | 2.11%   |
| Auckland                  | 2         | 2.11%   |
| Amsterdam                 | 2         | 2.11%   |
| Zhytomyr                  | 1         | 1.05%   |
| Yverdon-les-Bains         | 1         | 1.05%   |
| Wendell                   | 1         | 1.05%   |
| Vineland                  | 1         | 1.05%   |
| Vienna                    | 1         | 1.05%   |
| Vasco da Gama             | 1         | 1.05%   |
| Toronto                   | 1         | 1.05%   |
| Tirana                    | 1         | 1.05%   |
| The Hague                 | 1         | 1.05%   |
| Terranuova Bracciolini    | 1         | 1.05%   |
| Teresopolis               | 1         | 1.05%   |
| Tehran                    | 1         | 1.05%   |
| Stroudsburg               | 1         | 1.05%   |
| Stare Babice              | 1         | 1.05%   |
| St Petersburg             | 1         | 1.05%   |
| Severna Park              | 1         | 1.05%   |
| Semarang                  | 1         | 1.05%   |
| Santo Domingo Este        | 1         | 1.05%   |
| Santiago                  | 1         | 1.05%   |
| San Francisco del Rincón | 1         | 1.05%   |
| San Francisco             | 1         | 1.05%   |
| Saint-Just-Saint-Rambert  | 1         | 1.05%   |
| Riyadh                    | 1         | 1.05%   |
| Riga                      | 1         | 1.05%   |
| Red Oak                   | 1         | 1.05%   |
| Quilicura                 | 1         | 1.05%   |
| Portland                  | 1         | 1.05%   |
| Port Orange               | 1         | 1.05%   |
| Pomeroy                   | 1         | 1.05%   |
| Pessac                    | 1         | 1.05%   |
| Paracuellos de Jarama     | 1         | 1.05%   |
| Oslo                      | 1         | 1.05%   |
| New York                  | 1         | 1.05%   |
| Muscat                    | 1         | 1.05%   |
| Moscow                    | 1         | 1.05%   |
| Mohali                    | 1         | 1.05%   |
| Minsk                     | 1         | 1.05%   |
| Minneapolis               | 1         | 1.05%   |
| Milwaukee                 | 1         | 1.05%   |
| Málaga                   | 1         | 1.05%   |
| Makkah                    | 1         | 1.05%   |
| Madrid                    | 1         | 1.05%   |
| Lviv                      | 1         | 1.05%   |
| Lubbock                   | 1         | 1.05%   |
| Linter                    | 1         | 1.05%   |
| Lahti                     | 1         | 1.05%   |
| Kayseri                   | 1         | 1.05%   |
| Kathmandu                 | 1         | 1.05%   |
| Jeddah                    | 1         | 1.05%   |
| Jakarta                   | 1         | 1.05%   |
| Istanbul                  | 1         | 1.05%   |
| Ilford                    | 1         | 1.05%   |
| Ichinoseki                | 1         | 1.05%   |
| Hyderabad                 | 1         | 1.05%   |
| Humble                    | 1         | 1.05%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 18     | 14.66%  |
| Toshiba             | 15        | 18     | 12.93%  |
| Samsung Electronics | 14        | 15     | 12.07%  |
| Seagate             | 11        | 12     | 9.48%   |
| SanDisk             | 8         | 10     | 6.9%    |
| SK hynix            | 7         | 7      | 6.03%   |
| Kingston            | 7         | 7      | 6.03%   |
| Unknown             | 6         | 6      | 5.17%   |
| Micron Technology   | 5         | 6      | 4.31%   |
| Intel               | 5         | 7      | 4.31%   |
| Crucial             | 3         | 4      | 2.59%   |
| Silicon Motion      | 2         | 2      | 1.72%   |
| Hitachi             | 2         | 2      | 1.72%   |
| Transcend           | 1         | 1      | 0.86%   |
| SABRENT             | 1         | 1      | 0.86%   |
| PNY                 | 1         | 1      | 0.86%   |
| Phison              | 1         | 1      | 0.86%   |
| Lenovo              | 1         | 1      | 0.86%   |
| KIOXIA              | 1         | 1      | 0.86%   |
| KingFast            | 1         | 1      | 0.86%   |
| HGST                | 1         | 1      | 0.86%   |
| Gigabyte Technology | 1         | 1      | 0.86%   |
| FORESEE             | 1         | 1      | 0.86%   |
| Apple               | 1         | 1      | 0.86%   |
| Advantech           | 1         | 1      | 0.86%   |
| AAPL                | 1         | 1      | 0.86%   |
| A-DATA Technology   | 1         | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 5         | 4.2%    |
| SK hynix NVMe SSD Drive 128GB           | 3         | 2.52%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 2.52%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 2.52%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 1.68%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 1.68%   |
| Unknown MMC Card  32GB                  | 2         | 1.68%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.68%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.84%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.84%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.84%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 0.84%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 1         | 0.84%   |
| WDC WD2500LPVX-22V0TT0 250GB            | 1         | 0.84%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.84%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.84%   |
| WDC WD2500BEVT-00A23T0 250GB            | 1         | 0.84%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.84%   |
| WDC WD10JPVX-08JC3T5 1TB                | 1         | 0.84%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.84%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB    | 1         | 0.84%   |
| Unknown USB DISK 3.2 1TB                | 1         | 0.84%   |
| Unknown MMC Card  64GB                  | 1         | 0.84%   |
| Unknown MMC Card  128GB                 | 1         | 0.84%   |
| Unknown AJNB4R  16GB                    | 1         | 0.84%   |
| Transcend TS240GSSD220S 240GB           | 1         | 0.84%   |
| Toshiba THNSNJ256GVNU 256GB SSD         | 1         | 0.84%   |
| Toshiba THNS128GG4BNAA 128GB SSD        | 1         | 0.84%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.84%   |
| Toshiba NVMe SSD Drive 256GB            | 1         | 0.84%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.84%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.84%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.84%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.84%   |
| Toshiba MK5055GSX 500GB                 | 1         | 0.84%   |
| Toshiba KXG60ZNV512G NVMe 512GB         | 1         | 0.84%   |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB | 1         | 0.84%   |
| SK hynix NVMe SSD Drive 500GB           | 1         | 0.84%   |
| SK hynix NVMe SSD Drive 256GB           | 1         | 0.84%   |
| SK hynix HFM512GDJTNG-8310A 512GB       | 1         | 0.84%   |
| Silicon Motion NVMe SSD Drive 512GB     | 1         | 0.84%   |
| Silicon Motion IM2P33F8BR1-512GB        | 1         | 0.84%   |
| Seagate ST9750420AS 752GB               | 1         | 0.84%   |
| Seagate ST9500325AS 500GB               | 1         | 0.84%   |
| Seagate ST9320325AS 320GB               | 1         | 0.84%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.84%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 0.84%   |
| Seagate ST250LM004 HN-M250MBB 250GB     | 1         | 0.84%   |
| Seagate ST2000LX001-1RG174 2TB          | 1         | 0.84%   |
| Seagate ST1000LX001-1EM164 1TB          | 1         | 0.84%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 0.84%   |
| Seagate ST1000LM014-SSHD-8GB            | 1         | 0.84%   |
| SanDisk X400 M.2 2280 256GB SSD         | 1         | 0.84%   |
| SanDisk SDSSDA120G 120GB                | 1         | 0.84%   |
| SanDisk SD7SN6S512G1001 512GB SSD       | 1         | 0.84%   |
| SanDisk NVMe SSD Drive 1TB              | 1         | 0.84%   |
| SanDisk Extreme Pro 1TB                 | 1         | 0.84%   |
| SanDisk DF4032  32GB                    | 1         | 0.84%   |
| Samsung SSD 970 EVO Plus 2TB            | 1         | 0.84%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 14     | 34.21%  |
| Seagate | 11        | 12     | 28.95%  |
| Toshiba | 9         | 12     | 23.68%  |
| Hitachi | 2         | 2      | 5.26%   |
| SABRENT | 1         | 1      | 2.63%   |
| HGST    | 1         | 1      | 2.63%   |
| AAPL    | 1         | 1      | 2.63%   |

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
| HDD     | 37        | 43     | 33.94%  |
| SSD     | 35        | 40     | 32.11%  |
| NVMe    | 29        | 37     | 26.61%  |
| MMC     | 6         | 6      | 5.5%    |
| Unknown | 2         | 2      | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 63        | 81     | 61.76%  |
| NVMe | 29        | 37     | 28.43%  |
| MMC  | 6         | 6      | 5.88%   |
| SAS  | 4         | 4      | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 54     | 64.29%  |
| 0.51-1.0   | 24        | 28     | 34.29%  |
| 1.01-2.0   | 1         | 1      | 1.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 42        | 45.65%  |
| 251-500    | 20        | 21.74%  |
| 501-1000   | 12        | 13.04%  |
| 1001-2000  | 7         | 7.61%   |
| 21-50      | 4         | 4.35%   |
| 51-100     | 3         | 3.26%   |
| 1-20       | 2         | 2.17%   |
| Unknown    | 2         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 39        | 40.21%  |
| 21-50     | 19        | 19.59%  |
| 51-100    | 13        | 13.4%   |
| 101-250   | 11        | 11.34%  |
| 251-500   | 9         | 9.28%   |
| 1001-2000 | 2         | 2.06%   |
| 501-1000  | 2         | 2.06%   |
| Unknown   | 2         | 2.06%   |

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
| Detected | 65        | 91     | 67.71%  |
| Works    | 27        | 33     | 28.13%  |
| Malfunc  | 4         | 4      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 67        | 62.04%  |
| AMD                          | 9         | 8.33%   |
| SK hynix                     | 7         | 6.48%   |
| Toshiba America Info Systems | 5         | 4.63%   |
| SanDisk                      | 5         | 4.63%   |
| Samsung Electronics          | 5         | 4.63%   |
| Silicon Motion               | 2         | 1.85%   |
| Kingston Technology Company  | 2         | 1.85%   |
| Phison Electronics           | 1         | 0.93%   |
| Nvidia                       | 1         | 0.93%   |
| Micron Technology            | 1         | 0.93%   |
| Lenovo                       | 1         | 0.93%   |
| JMicron Technology           | 1         | 0.93%   |
| ADATA Technology             | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 10.81%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 7.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 7.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 5.41%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 3.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 3.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.8%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 2         | 1.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 1.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.8%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.8%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 1.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.8%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.9%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.9%    |
| SK hynix PC300 NVMe Solid State Drive 256GB                                      | 1         | 0.9%    |
| SK hynix Gold P31 SSD                                                            | 1         | 0.9%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.9%    |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.9%    |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.9%    |
| Micron Non-Volatile memory controller                                            | 1         | 0.9%    |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.9%    |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.9%    |
| Intel SSD 660P Series                                                            | 1         | 0.9%    |
| Intel SSD 600P Series                                                            | 1         | 0.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.9%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 71        | 67.62%  |
| NVMe | 28        | 26.67%  |
| RAID | 3         | 2.86%   |
| IDE  | 3         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 81        | 89.01%  |
| AMD    | 10        | 10.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 6.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 4.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 3.3%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 3.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 3.3%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.2%    |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 2.2%    |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 2.2%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 2.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.2%    |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 2.2%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 2.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.2%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.2%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.1%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 1.1%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.1%    |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 1.1%    |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 1.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.1%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.1%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.1%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.1%    |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.1%    |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.1%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.1%    |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 1.1%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.1%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.1%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.1%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.1%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.1%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.1%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.1%    |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.1%    |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 1.1%    |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1.1%    |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.1%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.1%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.1%    |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 1.1%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.1%    |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.1%    |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz          | 1         | 1.1%    |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.1%    |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.1%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.1%    |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 1.1%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.1%    |
| Intel Celeron CPU B830 @ 1.80GHz              | 1         | 1.1%    |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 1.1%    |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 1.1%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 33        | 36.26%  |
| Intel Core i7        | 21        | 23.08%  |
| Intel Celeron        | 8         | 8.79%   |
| Intel Core i3        | 6         | 6.59%   |
| Other                | 4         | 4.4%    |
| Intel Core 2 Duo     | 4         | 4.4%    |
| AMD Ryzen 7          | 4         | 4.4%    |
| AMD Ryzen 5          | 3         | 3.3%    |
| Intel Pentium        | 2         | 2.2%    |
| Intel Pentium Silver | 1         | 1.1%    |
| Intel Pentium Dual   | 1         | 1.1%    |
| Intel Core M         | 1         | 1.1%    |
| Intel Atom           | 1         | 1.1%    |
| AMD E1               | 1         | 1.1%    |
| AMD E                | 1         | 1.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 58.24%  |
| 4      | 31        | 34.07%  |
| 6      | 4         | 4.4%    |
| 8      | 2         | 2.2%    |
| 1      | 1         | 1.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 91        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 70        | 76.92%  |
| 1      | 21        | 23.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 87        | 94.57%  |
| Unknown        | 5         | 5.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ea    | 9         | 9.68%   |
| 0x306a9    | 8         | 8.6%    |
| 0x206a7    | 7         | 7.53%   |
| 0x806e9    | 6         | 6.45%   |
| 0x40651    | 5         | 5.38%   |
| Unknown    | 5         | 5.38%   |
| 0x306c3    | 4         | 4.3%    |
| 0x20655    | 4         | 4.3%    |
| 0x906ea    | 3         | 3.23%   |
| 0x906e9    | 3         | 3.23%   |
| 0x806ec    | 3         | 3.23%   |
| 0x806c1    | 3         | 3.23%   |
| 0x706a1    | 3         | 3.23%   |
| 0x406e3    | 3         | 3.23%   |
| 0x306d4    | 3         | 3.23%   |
| 0x08108102 | 3         | 3.23%   |
| 0x6fd      | 2         | 2.15%   |
| 0x30678    | 2         | 2.15%   |
| 0x1067a    | 2         | 2.15%   |
| 0xa0652    | 1         | 1.08%   |
| 0x906c0    | 1         | 1.08%   |
| 0x806eb    | 1         | 1.08%   |
| 0x706a8    | 1         | 1.08%   |
| 0x506e3    | 1         | 1.08%   |
| 0x20652    | 1         | 1.08%   |
| 0x10676    | 1         | 1.08%   |
| 0x10661    | 1         | 1.08%   |
| 0x0a50000c | 1         | 1.08%   |
| 0x08600106 | 1         | 1.08%   |
| 0x08108109 | 1         | 1.08%   |
| 0x0810100b | 1         | 1.08%   |
| 0x06006704 | 1         | 1.08%   |
| 0x05000119 | 1         | 1.08%   |
| 0x05000029 | 1         | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 28.57%  |
| Haswell       | 10        | 10.99%  |
| IvyBridge     | 8         | 8.79%   |
| SandyBridge   | 7         | 7.69%   |
| Westmere      | 5         | 5.49%   |
| Zen+          | 4         | 4.4%    |
| Skylake       | 4         | 4.4%    |
| Goldmont plus | 4         | 4.4%    |
| TigerLake     | 3         | 3.3%    |
| Silvermont    | 3         | 3.3%    |
| Penryn        | 3         | 3.3%    |
| Core          | 3         | 3.3%    |
| Broadwell     | 3         | 3.3%    |
| Bobcat        | 2         | 2.2%    |
| Zen 3         | 1         | 1.1%    |
| Zen 2         | 1         | 1.1%    |
| Zen           | 1         | 1.1%    |
| Tremont       | 1         | 1.1%    |
| Excavator     | 1         | 1.1%    |
| CometLake     | 1         | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 61.48%  |
| Nvidia | 28        | 22.95%  |
| AMD    | 19        | 15.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 8         | 6.45%   |
| Intel HD Graphics 620                                                                    | 7         | 5.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 5.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 3.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.23%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 2.42%   |
| Intel HD Graphics 630                                                                    | 3         | 2.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.42%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.61%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1.61%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.61%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 1.61%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.61%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.61%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.81%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.81%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.81%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 0.81%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.81%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.81%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 0.81%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.81%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.81%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.81%   |
| Intel HD Graphics 530                                                                    | 1         | 0.81%   |
| Intel HD Graphics 520                                                                    | 1         | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.81%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.81%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 0.81%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.81%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.81%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.81%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 0.81%   |
| AMD Renoir                                                                               | 1         | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.81%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 0.81%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 51.65%  |
| Intel + Nvidia | 24        | 26.37%  |
| 1 x AMD        | 12        | 13.19%  |
| Intel + AMD    | 4         | 4.4%    |
| AMD + Nvidia   | 3         | 3.3%    |
| 1 x Nvidia     | 1         | 1.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 73        | 80.22%  |
| Proprietary | 18        | 19.78%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 53.85%  |
| 1.01-2.0   | 17        | 18.68%  |
| 0.51-1.0   | 10        | 10.99%  |
| 3.01-4.0   | 6         | 6.59%   |
| 0.01-0.5   | 6         | 6.59%   |
| 5.01-6.0   | 3         | 3.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 24.07%  |
| LG Display              | 14        | 12.96%  |
| BOE                     | 13        | 12.04%  |
| Samsung Electronics     | 12        | 11.11%  |
| Chimei Innolux          | 12        | 11.11%  |
| Lenovo                  | 4         | 3.7%    |
| Goldstar                | 4         | 3.7%    |
| Sharp                   | 3         | 2.78%   |
| PANDA                   | 2         | 1.85%   |
| Chi Mei Optoelectronics | 2         | 1.85%   |
| BenQ                    | 2         | 1.85%   |
| Apple                   | 2         | 1.85%   |
| AOC                     | 2         | 1.85%   |
| ___                     | 1         | 0.93%   |
| Unknown                 | 1         | 0.93%   |
| Toshiba                 | 1         | 0.93%   |
| Sony                    | 1         | 0.93%   |
| Philips                 | 1         | 0.93%   |
| GKK                     | 1         | 0.93%   |
| Dell                    | 1         | 0.93%   |
| CSO                     | 1         | 0.93%   |
| Ancor Communications    | 1         | 0.93%   |
| Acer                    | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch      | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.83%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.92%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.92%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch             | 1         | 0.92%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.92%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.92%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.92%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.92%   |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch  | 1         | 0.92%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch   | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch  | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4250 1920x1080 276x156mm 12.5-inch | 1         | 0.92%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.92%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 0.92%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch     | 1         | 0.92%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                 | 1         | 0.92%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.92%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.92%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD044F 1920x1080 344x194mm 15.5-inch          | 1         | 0.92%   |
| LG Display LCD Monitor LGD0404 1366x768 277x156mm 12.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0383 1600x900 382x215mm 17.3-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 1         | 0.92%   |
| LG Display LCD Monitor LGD020C 1600x900 345x194mm 15.6-inch           | 1         | 0.92%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 0.92%   |
| Lenovo LCD Monitor LEN4074 1440x900 287x180mm 13.3-inch               | 1         | 0.92%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch               | 1         | 0.92%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                   | 1         | 0.92%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 0.92%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1         | 0.92%   |
| Goldstar E2241 GSM581A 1920x1080 477x268mm 21.5-inch                  | 1         | 0.92%   |
| Goldstar E1911 GSM4BF9 1366x768 410x230mm 18.5-inch                   | 1         | 0.92%   |
| GKK MONITOR GKK3034 1920x1080                                         | 1         | 0.92%   |
| Dell G2410 DEL404B 1920x1080 531x298mm 24.0-inch                      | 1         | 0.92%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                 | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 0.92%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 1         | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 44.44%  |
| 1366x768 (WXGA)    | 33        | 33.33%  |
| 1600x900 (HD+)     | 7         | 7.07%   |
| 3840x2160 (4K)     | 3         | 3.03%   |
| 1440x900 (WXGA+)   | 3         | 3.03%   |
| 1280x800 (WXGA)    | 3         | 3.03%   |
| 2560x1600          | 1         | 1.01%   |
| 2560x1440 (QHD)    | 1         | 1.01%   |
| 2560x1080          | 1         | 1.01%   |
| 2256x1504          | 1         | 1.01%   |
| 1680x1050 (WSXGA+) | 1         | 1.01%   |
| 1360x768           | 1         | 1.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 51        | 47.66%  |
| 13      | 19        | 17.76%  |
| 14      | 9         | 8.41%   |
| 17      | 7         | 6.54%   |
| 21      | 4         | 3.74%   |
| 24      | 3         | 2.8%    |
| 23      | 3         | 2.8%    |
| 27      | 2         | 1.87%   |
| 12      | 2         | 1.87%   |
| 11      | 2         | 1.87%   |
| 72      | 1         | 0.93%   |
| 40      | 1         | 0.93%   |
| 34      | 1         | 0.93%   |
| 18      | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 67        | 63.21%  |
| 201-300     | 13        | 12.26%  |
| 351-400     | 9         | 8.49%   |
| 501-600     | 7         | 6.6%    |
| 401-500     | 6         | 5.66%   |
| 801-900     | 1         | 0.94%   |
| 701-800     | 1         | 0.94%   |
| 1501-2000   | 1         | 0.94%   |
| Unknown     | 1         | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 83        | 90.22%  |
| 16/10 | 6         | 6.52%   |
| 3/2   | 2         | 2.17%   |
| 21/9  | 1         | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 50        | 46.73%  |
| 81-90          | 21        | 19.63%  |
| 201-250        | 9         | 8.41%   |
| 71-80          | 7         | 6.54%   |
| 121-130        | 7         | 6.54%   |
| 61-70          | 2         | 1.87%   |
| 51-60          | 2         | 1.87%   |
| 301-350        | 2         | 1.87%   |
| More than 1000 | 1         | 0.93%   |
| 351-500        | 1         | 0.93%   |
| 151-200        | 1         | 0.93%   |
| 141-150        | 1         | 0.93%   |
| 501-1000       | 1         | 0.93%   |
| 91-100         | 1         | 0.93%   |
| Unknown        | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 38.83%  |
| 101-120       | 35        | 33.98%  |
| 51-100        | 15        | 14.56%  |
| 161-240       | 8         | 7.77%   |
| More than 240 | 3         | 2.91%   |
| 1-50          | 1         | 0.97%   |
| Unknown       | 1         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 76        | 82.61%  |
| 2     | 14        | 15.22%  |
| 3     | 2         | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 47        | 31.54%  |
| Realtek Semiconductor         | 45        | 30.2%   |
| Qualcomm Atheros              | 28        | 18.79%  |
| Broadcom                      | 9         | 6.04%   |
| Marvell Technology Group      | 3         | 2.01%   |
| Ralink                        | 2         | 1.34%   |
| Dell                          | 2         | 1.34%   |
| TP-Link                       | 1         | 0.67%   |
| T & A Mobile Phones           | 1         | 0.67%   |
| Sierra Wireless               | 1         | 0.67%   |
| Samsung Electronics           | 1         | 0.67%   |
| Ralink Technology             | 1         | 0.67%   |
| Qualcomm                      | 1         | 0.67%   |
| OnePlus Technology (Shenzhen) | 1         | 0.67%   |
| Nvidia                        | 1         | 0.67%   |
| MediaTek                      | 1         | 0.67%   |
| Lenovo                        | 1         | 0.67%   |
| Jolla Oy                      | 1         | 0.67%   |
| Hewlett-Packard               | 1         | 0.67%   |
| Android                       | 1         | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 16.95%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 8         | 4.52%   |
| Intel Wireless 8265 / 8275                                                     | 8         | 4.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 3.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 3.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 6         | 3.39%   |
| Intel Wireless 7260                                                            | 5         | 2.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 2.26%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 4         | 2.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 3         | 1.69%   |
| Intel Wireless 7265                                                            | 3         | 1.69%   |
| Intel Wireless 3165                                                            | 3         | 1.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 1.13%   |
| Intel Wireless 8260                                                            | 2         | 1.13%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.13%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                  | 2         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 1.13%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 2         | 1.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 2         | 1.13%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.56%   |
| T & A Mobile Phones 5087Z                                                      | 1         | 0.56%   |
| Sierra Wireless EM7305                                                         | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.56%   |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.56%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.56%   |
| Qualcomm Android                                                               | 1         | 0.56%   |
| OnePlus (Shenzhen) OnePlus                                                     | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.56%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.56%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.56%   |
| Lenovo Thinkpad LAN                                                            | 1         | 0.56%   |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 0.56%   |
| Intel Wireless 3160                                                            | 1         | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 0.56%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 1         | 0.56%   |
| Intel Ultimate N WiFi Link 5300                                                | 1         | 0.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 48.96%  |
| Qualcomm Atheros      | 25        | 26.04%  |
| Realtek Semiconductor | 10        | 10.42%  |
| Broadcom              | 7         | 7.29%   |
| Ralink                | 2         | 2.08%   |
| Sierra Wireless       | 1         | 1.04%   |
| Ralink Technology     | 1         | 1.04%   |
| MediaTek              | 1         | 1.04%   |
| Hewlett-Packard       | 1         | 1.04%   |
| Dell                  | 1         | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 8.33%   |
| Intel Wireless 8265 / 8275                                     | 8         | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 6.25%   |
| Intel Wireless 7260                                            | 5         | 5.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 4.17%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 4.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 3.13%   |
| Intel Wireless 7265                                            | 3         | 3.13%   |
| Intel Wireless 3165                                            | 3         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 2.08%   |
| Intel Wireless 8260                                            | 2         | 2.08%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.08%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.08%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 2.08%   |
| Sierra Wireless EM7305                                         | 1         | 1.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.04%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.04%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 1.04%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.04%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.04%   |
| Intel Wireless 3160                                            | 1         | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.04%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1.04%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.04%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.04%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.04%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.04%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.04%   |
| HP lt4112 Gobi 4G Module Network Device                        | 1         | 1.04%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.04%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 51.28%  |
| Intel                    | 20        | 25.64%  |
| Qualcomm Atheros         | 5         | 6.41%   |
| Marvell Technology Group | 3         | 3.85%   |
| Broadcom                 | 3         | 3.85%   |
| TP-Link                  | 1         | 1.28%   |
| Samsung Electronics      | 1         | 1.28%   |
| Qualcomm                 | 1         | 1.28%   |
| Nvidia                   | 1         | 1.28%   |
| Lenovo                   | 1         | 1.28%   |
| Jolla Oy                 | 1         | 1.28%   |
| Android                  | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 38.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 8.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 7.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 2.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.28%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.28%   |
| Qualcomm Android                                                               | 1         | 1.28%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.28%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.28%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 1.28%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 1.28%   |
| Lenovo Thinkpad LAN                                                            | 1         | 1.28%   |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 1.28%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.28%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.28%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.28%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.28%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.28%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.28%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.28%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.28%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.28%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.28%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 1.28%   |
| Android Android                                                                | 1         | 1.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 54.17%  |
| Ethernet | 74        | 44.05%  |
| Unknown  | 2         | 1.19%   |
| Modem    | 1         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 86.96%  |
| Ethernet | 12        | 13.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 71        | 78.02%  |
| 1     | 19        | 20.88%  |
| 0     | 1         | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 91.21%  |
| Yes  | 8         | 8.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 49.32%  |
| Qualcomm Atheros Communications | 9         | 12.33%  |
| Lite-On Technology              | 9         | 12.33%  |
| Realtek Semiconductor           | 4         | 5.48%   |
| IMC Networks                    | 3         | 4.11%   |
| Broadcom                        | 3         | 4.11%   |
| Foxconn / Hon Hai               | 2         | 2.74%   |
| Apple                           | 2         | 2.74%   |
| Toshiba                         | 1         | 1.37%   |
| Ralink                          | 1         | 1.37%   |
| Hewlett-Packard                 | 1         | 1.37%   |
| Dell                            | 1         | 1.37%   |
| Cambridge Silicon Radio         | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 21        | 28.77%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 6.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 5.48%   |
| Intel AX200 Bluetooth                                                               | 4         | 5.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 4.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 4.11%   |
| Intel AX201 Bluetooth                                                               | 3         | 4.11%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.74%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.74%   |
| Intel Bluetooth Device                                                              | 2         | 2.74%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.74%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 1.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.37%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1.37%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.37%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.37%   |
| Lite-On Wireless_Device                                                             | 1         | 1.37%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.37%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.37%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.37%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.37%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.37%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.37%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.37%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.37%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 80        | 72.07%  |
| AMD                 | 15        | 13.51%  |
| Nvidia              | 13        | 11.71%  |
| Samsung Electronics | 1         | 0.9%    |
| GYROCOM C&C         | 1         | 0.9%    |
| Conexant Systems    | 1         | 0.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 13.74%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 6.87%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 4.58%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 4.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 3.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 3.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.29%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 2.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.29%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.29%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.53%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.53%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.53%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.53%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.76%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.76%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.76%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.76%   |
| GYROCOM C&C Fiio E10                                                                              | 1         | 0.76%   |
| Conexant Systems Hi-Res Audio                                                                     | 1         | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.76%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.76%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.76%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 28.57%  |
| SK hynix            | 9         | 18.37%  |
| A-DATA Technology   | 5         | 10.2%   |
| Kingston            | 4         | 8.16%   |
| Nanya Technology    | 3         | 6.12%   |
| Micron Technology   | 3         | 6.12%   |
| Crucial             | 3         | 6.12%   |
| Unknown             | 2         | 4.08%   |
| Ramaxel Technology  | 2         | 4.08%   |
| Elpida              | 2         | 4.08%   |
| Team                | 1         | 2.04%   |
| G.Skill             | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 2         | 4.08%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 2         | 4.08%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 2.04%   |
| Unknown RAM Module 1GB SODIMM DDR                                   | 1         | 2.04%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 2.04%   |
| SK hynix RAM Module 2048MB SODIMM DDR2 800MT/s                      | 1         | 2.04%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 2.04%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 2.04%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 2.04%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.04%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 2.04%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 2.04%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 2.04%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 2.04%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 2.04%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 2.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 2.04%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 2.04%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 2.04%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 2.04%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s           | 1         | 2.04%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 1         | 2.04%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s              | 1         | 2.04%   |
| Ramaxel RAM RMT3170EB68E9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 2.04%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s             | 1         | 2.04%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 1         | 2.04%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s               | 1         | 2.04%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s            | 1         | 2.04%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 1         | 2.04%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s               | 1         | 2.04%   |
| Kingston RAM 99U5663-003.A00G 16GB SODIMM DDR4 2400MT/s             | 1         | 2.04%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s             | 1         | 2.04%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s              | 1         | 2.04%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s              | 1         | 2.04%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s                       | 1         | 2.04%   |
| Elpida RAM EBJ81UG8BBU0-GN-F 8GB SODIMM DDR3 1600MT/s               | 1         | 2.04%   |
| Crucial RAM CT8G4SFS824A.C8FE 8192MB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Crucial RAM CT32G4SFD832A.M16FB 32GB SODIMM DDR4 3200MT/s           | 1         | 2.04%   |
| Crucial RAM CB4GS2400.M8E 4096MB SODIMM DDR4 2400MT/s               | 1         | 2.04%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2400MT/s                       | 1         | 2.04%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                       | 1         | 2.04%   |
| A-DATA RAM AO1P24HC8T1-B2NS 8GB SODIMM DDR4 2133MT/s                | 1         | 2.04%   |
| A-DATA RAM AO1P21FC4R1-B2MS 4096MB SODIMM DDR4 2133MT/s             | 1         | 2.04%   |
| A-DATA RAM AM1P26KC8T1-BBSS 8GB SODIMM DDR4 2667MT/s                | 1         | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 46.15%  |
| DDR3   | 12        | 30.77%  |
| LPDDR3 | 4         | 10.26%  |
| DDR2   | 2         | 5.13%   |
| SDRAM  | 1         | 2.56%   |
| LPDDR4 | 1         | 2.56%   |
| DDR    | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 92.11%  |
| Row Of Chips | 3         | 7.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 43.59%  |
| 4096  | 11        | 28.21%  |
| 2048  | 5         | 12.82%  |
| 16384 | 3         | 7.69%   |
| 32768 | 2         | 5.13%   |
| 1024  | 1         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 20.93%  |
| 2667    | 8         | 18.6%   |
| 2400    | 5         | 11.63%  |
| 2133    | 5         | 11.63%  |
| 3200    | 4         | 9.3%    |
| 1334    | 2         | 4.65%   |
| Unknown | 2         | 4.65%   |
| 4267    | 1         | 2.33%   |
| 3266    | 1         | 2.33%   |
| 2048    | 1         | 2.33%   |
| 1867    | 1         | 2.33%   |
| 1333    | 1         | 2.33%   |
| 1067    | 1         | 2.33%   |
| 800     | 1         | 2.33%   |
| 667     | 1         | 2.33%   |

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
| Chicony Electronics                    | 20        | 23.81%  |
| Realtek Semiconductor                  | 10        | 11.9%   |
| Microdia                               | 9         | 10.71%  |
| IMC Networks                           | 8         | 9.52%   |
| Quanta                                 | 6         | 7.14%   |
| Acer                                   | 5         | 5.95%   |
| Sunplus Innovation Technology          | 4         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.76%   |
| Suyin                                  | 3         | 3.57%   |
| Logitech                               | 3         | 3.57%   |
| Lite-On Technology                     | 3         | 3.57%   |
| Lenovo                                 | 2         | 2.38%   |
| Importek                               | 2         | 2.38%   |
| Unknown                                | 1         | 1.19%   |
| Syntek                                 | 1         | 1.19%   |
| Silicon Motion                         | 1         | 1.19%   |
| Intel                                  | 1         | 1.19%   |
| Apple                                  | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                     | 6         | 7.06%   |
| Realtek HD WebCam                                                     | 3         | 3.53%   |
| Microdia Integrated_Webcam_HD                                         | 3         | 3.53%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 3         | 3.53%   |
| Chicony Integrated Camera                                             | 3         | 3.53%   |
| Suyin HP TrueVision HD Integrated Webcam                              | 2         | 2.35%   |
| Sunplus Integrated_Webcam_HD                                          | 2         | 2.35%   |
| Realtek Integrated Webcam_HD                                          | 2         | 2.35%   |
| Quanta HD User Facing                                                 | 2         | 2.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                                    | 2         | 2.35%   |
| IMC Networks Integrated Camera                                        | 2         | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                         | 2         | 2.35%   |
| Unknown ATIV VGA CAMERA                                               | 1         | 1.18%   |
| Syntek USB2.0 Camera                                                  | 1         | 1.18%   |
| Suyin 1.3M HD WebCam                                                  | 1         | 1.18%   |
| Sunplus Laptop_Integrated_Webcam_HD                                   | 1         | 1.18%   |
| Sunplus Laptop Integrated WebCam HD                                   | 1         | 1.18%   |
| Silicon Motion WebCam SC-10HDD12636N                                  | 1         | 1.18%   |
| Realtek Laptop Camera                                                 | 1         | 1.18%   |
| Realtek Integrated Webcam HD                                          | 1         | 1.18%   |
| Realtek Integrated Webcam                                             | 1         | 1.18%   |
| Realtek Integrated Camera                                             | 1         | 1.18%   |
| Realtek HP Truevision HD                                              | 1         | 1.18%   |
| Quanta VGA WebCam                                                     | 1         | 1.18%   |
| Quanta USB2.0 HD UVC WebCam                                           | 1         | 1.18%   |
| Quanta HP Wide Vision HD Camera                                       | 1         | 1.18%   |
| Quanta HP TrueVision HD Webcam                                        | 1         | 1.18%   |
| Microdia Webcam                                                       | 1         | 1.18%   |
| Microdia USB 2.0 Camera                                               | 1         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 1.18%   |
| Microdia Integrated Webcam HD                                         | 1         | 1.18%   |
| Microdia HDP Webcam USB                                               | 1         | 1.18%   |
| Microdia Dell Laptop Integrated Webcam HD                             | 1         | 1.18%   |
| Logitech Webcam C310                                                  | 1         | 1.18%   |
| Logitech Webcam C270                                                  | 1         | 1.18%   |
| Logitech HD Pro Webcam C920                                           | 1         | 1.18%   |
| Lite-On Integrated Camera                                             | 1         | 1.18%   |
| Lite-On HP HD Webcam                                                  | 1         | 1.18%   |
| Lite-On HP HD Camera                                                  | 1         | 1.18%   |
| Lenovo UVC Camera                                                     | 1         | 1.18%   |
| Lenovo Integrated Webcam [R5U877]                                     | 1         | 1.18%   |
| Intel RealSense 3D Camera (Front F200)                                | 1         | 1.18%   |
| Importek TOSHIBA Web Camera - HD                                      | 1         | 1.18%   |
| Importek Laptop Integrated Webcam                                     | 1         | 1.18%   |
| IMC Networks UVC VGA Webcam                                           | 1         | 1.18%   |
| Chicony VGA WebCam                                                    | 1         | 1.18%   |
| Chicony TOSHIBA Web Camera - FHD                                      | 1         | 1.18%   |
| Chicony TOSHIBA Web Camera - 5M                                       | 1         | 1.18%   |
| Chicony Sony Visual Communication Camera                              | 1         | 1.18%   |
| Chicony Integrated HP HD Webcam                                       | 1         | 1.18%   |
| Chicony HP Webcam                                                     | 1         | 1.18%   |
| Chicony HP Truevision HD camera                                       | 1         | 1.18%   |
| Chicony HP HD Camera                                                  | 1         | 1.18%   |
| Chicony HD WebCam (Acer)                                              | 1         | 1.18%   |
| Chicony EasyCamera                                                    | 1         | 1.18%   |
| Chicony CNF9055 Toshiba Webcam                                        | 1         | 1.18%   |
| Chicony 2.0M UVC WebCam                                               | 1         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam          | 1         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera       | 1         | 1.18%   |
| Apple FaceTime HD Camera (Built-in)                                   | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 11        | 52.38%  |
| Upek                  | 2         | 9.52%   |
| Synaptics             | 2         | 9.52%   |
| LighTuning Technology | 2         | 9.52%   |
| Elan Microelectronics | 2         | 9.52%   |
| AuthenTec             | 2         | 9.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 19.05%  |
| Validity Sensors Fingerprint scanner                   | 2         | 9.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 9.52%   |
| Elan ELAN:Fingerprint                                  | 2         | 9.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.76%   |
| Validity Sensors VFS491                                | 1         | 4.76%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.76%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4.76%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.76%   |
| AuthenTec AES2810                                      | 1         | 4.76%   |

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
| 0     | 58        | 63.74%  |
| 1     | 24        | 26.37%  |
| 2     | 9         | 9.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 21        | 47.73%  |
| Net/wireless          | 7         | 15.91%  |
| Chipcard              | 6         | 13.64%  |
| Multimedia controller | 3         | 6.82%   |
| Graphics card         | 2         | 4.55%   |
| Unassigned class      | 1         | 2.27%   |
| Storage               | 1         | 2.27%   |
| Net/ethernet          | 1         | 2.27%   |
| Camera                | 1         | 2.27%   |
| Bluetooth             | 1         | 2.27%   |

